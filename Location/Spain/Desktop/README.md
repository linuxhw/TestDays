Linux in Spain - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 2409

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PRO         | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| HP            | 1632                        | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Acer          | Batman A01                  | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [d19e0fb48b](https://linux-hardware.org/?probe=d19e0fb48b) | Sep 30, 2022 |
| Gigabyte      | H81M-D2V                    | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [4707a778dc](https://linux-hardware.org/?probe=4707a778dc) | Sep 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| ASUSTek       | P5K                         | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| ASUSTek       | M5A97 PRO                   | [255a0a928a](https://linux-hardware.org/?probe=255a0a928a) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| Lenovo        | 3098 NOK                    | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| HP            | 2B35                        | [724e0d61e3](https://linux-hardware.org/?probe=724e0d61e3) | Sep 25, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| MSI           | 970 GAMING                  | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Shuttle       | DH470                       | [d00d31309a](https://linux-hardware.org/?probe=d00d31309a) | Sep 23, 2022 |
| Shuttle       | DH470                       | [cb519b4bfe](https://linux-hardware.org/?probe=cb519b4bfe) | Sep 23, 2022 |
| ASUSTek       | P5K                         | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | [d79e046c6d](https://linux-hardware.org/?probe=d79e046c6d) | Sep 22, 2022 |
| ASUSTek       | PRIME X570-P                | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Unknown       | 1.0                         | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [94d45ff789](https://linux-hardware.org/?probe=94d45ff789) | Sep 19, 2022 |
| ASUSTek       | H110M-D                     | [7ea35cc80a](https://linux-hardware.org/?probe=7ea35cc80a) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| ASUSTek       | P5B-Deluxe                  | [0b32a9e842](https://linux-hardware.org/?probe=0b32a9e842) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| ASUSTek       | PRIME B560M-A               | [fab04fe2c7](https://linux-hardware.org/?probe=fab04fe2c7) | Sep 16, 2022 |
| ASRock        | B550M Pro4                  | [7f6ce1e4ea](https://linux-hardware.org/?probe=7f6ce1e4ea) | Sep 14, 2022 |
| Acer          | Aspire X3990                | [64cddc5f85](https://linux-hardware.org/?probe=64cddc5f85) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| ASUSTek       | B85M-G                      | [74a9860a2e](https://linux-hardware.org/?probe=74a9860a2e) | Sep 13, 2022 |
| ASUSTek       | P5Q SE2                     | [1552e587a8](https://linux-hardware.org/?probe=1552e587a8) | Sep 13, 2022 |
| MSI           | MAG Z390M MORTAR            | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| MSI           | B560M PRO                   | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| MSI           | MAG B550 TORPEDO            | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [0caf1e7324](https://linux-hardware.org/?probe=0caf1e7324) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| ASUSTek       | M4N72-E                     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [06d3f051d1](https://linux-hardware.org/?probe=06d3f051d1) | Sep 09, 2022 |
| ASUSTek       | H110M-A                     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| MSI           | IONA                        | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| ASUSTek       | PRIME Z590-A                | [c8a237d75e](https://linux-hardware.org/?probe=c8a237d75e) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| ASUSTek       | H81M-PLUS                   | [ca8d36ee7e](https://linux-hardware.org/?probe=ca8d36ee7e) | Sep 07, 2022 |
| ECS           | GeForce 8000 series         | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Medion        | H61H2-LM3 V1.0              | [96b497db35](https://linux-hardware.org/?probe=96b497db35) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [c0ad8b81fa](https://linux-hardware.org/?probe=c0ad8b81fa) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [9128ddb611](https://linux-hardware.org/?probe=9128ddb611) | Sep 05, 2022 |
| HP            | 8767 A                      | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| Gigabyte      | Z590 GAMING X               | [b84d0acafb](https://linux-hardware.org/?probe=b84d0acafb) | Sep 01, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [12033c4a8b](https://linux-hardware.org/?probe=12033c4a8b) | Aug 31, 2022 |
| MSI           | H97M-G43                    | [978d5b45be](https://linux-hardware.org/?probe=978d5b45be) | Aug 31, 2022 |
| Gigabyte      | P85-D3                      | [71ce0b707c](https://linux-hardware.org/?probe=71ce0b707c) | Aug 31, 2022 |
| Dell          | 09KPNV A00                  | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| Gigabyte      | H81M-D3H                    | [89ced19bd4](https://linux-hardware.org/?probe=89ced19bd4) | Aug 25, 2022 |
| MSI           | H97M-G43                    | [3f781247f0](https://linux-hardware.org/?probe=3f781247f0) | Aug 25, 2022 |
| HP            | 3647h                       | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [a25c6f8d64](https://linux-hardware.org/?probe=a25c6f8d64) | Aug 22, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [f526447f78](https://linux-hardware.org/?probe=f526447f78) | Aug 19, 2022 |
| Gateway       | DS50                        | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [02f9463f2b](https://linux-hardware.org/?probe=02f9463f2b) | Aug 17, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [f223d64d8f](https://linux-hardware.org/?probe=f223d64d8f) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| MSI           | Z490-A PRO                  | [b69d60f568](https://linux-hardware.org/?probe=b69d60f568) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Pegatron      | 2A94                        | [81b0cdd377](https://linux-hardware.org/?probe=81b0cdd377) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| Unknown       | Unknown                     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| Gigabyte      | B365M DS3H                  | [fd9bae65fa](https://linux-hardware.org/?probe=fd9bae65fa) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [1840f48c85](https://linux-hardware.org/?probe=1840f48c85) | Aug 12, 2022 |
| Gigabyte      | B550M DS3H                  | [be29e8b357](https://linux-hardware.org/?probe=be29e8b357) | Aug 11, 2022 |
| HP            | 3397                        | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| ASUSTek       | A68HM-K                     | [f04f6e3bed](https://linux-hardware.org/?probe=f04f6e3bed) | Aug 07, 2022 |
| Alienware     | 0PGRP5 A01                  | [305bf6182f](https://linux-hardware.org/?probe=305bf6182f) | Aug 07, 2022 |
| ASUSTek       | M3A78                       | [bda5207234](https://linux-hardware.org/?probe=bda5207234) | Aug 05, 2022 |
| Unknown       | Intel X79                   | [f013fa996e](https://linux-hardware.org/?probe=f013fa996e) | Aug 04, 2022 |
| ASRock        | H97M Pro4                   | [c290aae7c6](https://linux-hardware.org/?probe=c290aae7c6) | Aug 04, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [8e83e6141d](https://linux-hardware.org/?probe=8e83e6141d) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Acer          | Aspire X3470                | [88ad041430](https://linux-hardware.org/?probe=88ad041430) | Jul 31, 2022 |
| HP            | 2AF7                        | [da51487005](https://linux-hardware.org/?probe=da51487005) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e3a44e4c5b](https://linux-hardware.org/?probe=e3a44e4c5b) | Jul 30, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [db241f583d](https://linux-hardware.org/?probe=db241f583d) | Jul 28, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [d29d943a24](https://linux-hardware.org/?probe=d29d943a24) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [c7c46e080e](https://linux-hardware.org/?probe=c7c46e080e) | Jul 25, 2022 |
| MSI           | B365M PRO-VH                | [f254ee30b7](https://linux-hardware.org/?probe=f254ee30b7) | Jul 25, 2022 |
| Gigabyte      | B365M DS3H                  | [571655453a](https://linux-hardware.org/?probe=571655453a) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [7cc616f3c8](https://linux-hardware.org/?probe=7cc616f3c8) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [793c3d4e22](https://linux-hardware.org/?probe=793c3d4e22) | Jul 24, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [89fadaa563](https://linux-hardware.org/?probe=89fadaa563) | Jul 23, 2022 |
| Intel         | STK1A32SC H95551-301        | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [7cd95094de](https://linux-hardware.org/?probe=7cd95094de) | Jul 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4655fe2442](https://linux-hardware.org/?probe=4655fe2442) | Jul 21, 2022 |
| Dell          | 0GM819                      | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [7ff3bd3639](https://linux-hardware.org/?probe=7ff3bd3639) | Jul 20, 2022 |
| Foxconn       | ETON                        | [1686897e74](https://linux-hardware.org/?probe=1686897e74) | Jul 20, 2022 |
| MACHINIST     | X79 V2.82H                  | [67faad589b](https://linux-hardware.org/?probe=67faad589b) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | Boston                      | [c1474f9d2f](https://linux-hardware.org/?probe=c1474f9d2f) | Jul 15, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Intel         | D34010WYK H14771-304        | [3fe93a38f6](https://linux-hardware.org/?probe=3fe93a38f6) | Jul 13, 2022 |
| Acer          | Aspire X3470                | [61b7216da0](https://linux-hardware.org/?probe=61b7216da0) | Jul 12, 2022 |
| Intel         | D34010WYK H14771-304        | [26c70348e9](https://linux-hardware.org/?probe=26c70348e9) | Jul 12, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| ASRock        | Z170 Extreme4               | [34f14d654f](https://linux-hardware.org/?probe=34f14d654f) | Jul 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [75f0ca97b8](https://linux-hardware.org/?probe=75f0ca97b8) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | [560e81bb64](https://linux-hardware.org/?probe=560e81bb64) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | [4f57a8d7f4](https://linux-hardware.org/?probe=4f57a8d7f4) | Jul 08, 2022 |
| HP            | 18E7                        | [68781cd22f](https://linux-hardware.org/?probe=68781cd22f) | Jul 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [3a20826dbb](https://linux-hardware.org/?probe=3a20826dbb) | Jul 06, 2022 |
| Unknown       | Unknown                     | [c22b57692e](https://linux-hardware.org/?probe=c22b57692e) | Jul 06, 2022 |
| Lenovo        | 3098 NOK                    | [0fb5f3cc66](https://linux-hardware.org/?probe=0fb5f3cc66) | Jul 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5636dc957a](https://linux-hardware.org/?probe=5636dc957a) | Jul 05, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [aed7de4f94](https://linux-hardware.org/?probe=aed7de4f94) | Jul 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [8e5892c130](https://linux-hardware.org/?probe=8e5892c130) | Jul 05, 2022 |
| Gigabyte      | 945GCM-S2L                  | [2d627ba67d](https://linux-hardware.org/?probe=2d627ba67d) | Jul 03, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | [a1ca3ddb17](https://linux-hardware.org/?probe=a1ca3ddb17) | Jul 03, 2022 |
| MSI           | Z87 MPOWER                  | [ba26baf84a](https://linux-hardware.org/?probe=ba26baf84a) | Jun 30, 2022 |
| MSI           | MEG X570 ACE                | [6dff126482](https://linux-hardware.org/?probe=6dff126482) | Jun 30, 2022 |
| HP            | 3647h                       | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| HP            | ProLiant ML110 G7           | [ace3582eee](https://linux-hardware.org/?probe=ace3582eee) | Jun 28, 2022 |
| HP            | ProLiant ML110 G7           | [5d18d90cda](https://linux-hardware.org/?probe=5d18d90cda) | Jun 27, 2022 |
| ASUSTek       | H81M-P PLUS                 | [6c18625cb3](https://linux-hardware.org/?probe=6c18625cb3) | Jun 27, 2022 |
| ASUSTek       | P5K                         | [e401eb71bc](https://linux-hardware.org/?probe=e401eb71bc) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | [48cbc869da](https://linux-hardware.org/?probe=48cbc869da) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | [ea31080862](https://linux-hardware.org/?probe=ea31080862) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [2d1c05fefc](https://linux-hardware.org/?probe=2d1c05fefc) | Jun 26, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [5047471b41](https://linux-hardware.org/?probe=5047471b41) | Jun 26, 2022 |
| Dell          | 0W0CHX A00                  | [874e7081c6](https://linux-hardware.org/?probe=874e7081c6) | Jun 23, 2022 |
| ASUSTek       | H81M-P PLUS                 | [b91a1b0ded](https://linux-hardware.org/?probe=b91a1b0ded) | Jun 22, 2022 |
| Acer          | Aspire X1700                | [6a67f8cba0](https://linux-hardware.org/?probe=6a67f8cba0) | Jun 21, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| Gigabyte      | H61M-USB3H                  | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| HP            | 18E7                        | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [5f5c3fcba9](https://linux-hardware.org/?probe=5f5c3fcba9) | Jun 13, 2022 |
| Gigabyte      | 970A-DS3P                   | [d22ca1b39a](https://linux-hardware.org/?probe=d22ca1b39a) | Jun 12, 2022 |
| HP            | 1496                        | [d6fba97175](https://linux-hardware.org/?probe=d6fba97175) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [a3ca1ea153](https://linux-hardware.org/?probe=a3ca1ea153) | Jun 12, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [839663a1af](https://linux-hardware.org/?probe=839663a1af) | Jun 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | [eb7ee3a693](https://linux-hardware.org/?probe=eb7ee3a693) | Jun 10, 2022 |
| MSI           | MAG B550M MORTAR            | [40c1095611](https://linux-hardware.org/?probe=40c1095611) | Jun 08, 2022 |
| MSI           | H110M PRO-VH                | [ceae668577](https://linux-hardware.org/?probe=ceae668577) | Jun 07, 2022 |
| Gigabyte      | H81M-S2H                    | [4ca91078a2](https://linux-hardware.org/?probe=4ca91078a2) | Jun 07, 2022 |
| Gigabyte      | H61M-USB3H                  | [1f88a2c07c](https://linux-hardware.org/?probe=1f88a2c07c) | Jun 04, 2022 |
| Gigabyte      | H61M-USB3H                  | [3cc513c431](https://linux-hardware.org/?probe=3cc513c431) | Jun 04, 2022 |
| Acer          | F90M R01-D1                 | [ecc8d1f955](https://linux-hardware.org/?probe=ecc8d1f955) | Jun 03, 2022 |
| Gigabyte      | B450 AORUS M                | [bb96d40d38](https://linux-hardware.org/?probe=bb96d40d38) | Jun 03, 2022 |
| ASUSTek       | H81M-P PLUS                 | [8c60f1e8e0](https://linux-hardware.org/?probe=8c60f1e8e0) | Jun 03, 2022 |
| ASUSTek       | P5K                         | [2e621739e6](https://linux-hardware.org/?probe=2e621739e6) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | [3210714de1](https://linux-hardware.org/?probe=3210714de1) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | [9b01043ab8](https://linux-hardware.org/?probe=9b01043ab8) | Jun 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| MSI           | B560M PRO-VDH               | [2e9996424a](https://linux-hardware.org/?probe=2e9996424a) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [580abb0cf9](https://linux-hardware.org/?probe=580abb0cf9) | May 30, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | [b0e56c97d2](https://linux-hardware.org/?probe=b0e56c97d2) | May 28, 2022 |
| ASUSTek       | P5K                         | [2b5230c5f8](https://linux-hardware.org/?probe=2b5230c5f8) | May 27, 2022 |
| ASUSTek       | P5K                         | [b816732403](https://linux-hardware.org/?probe=b816732403) | May 27, 2022 |
| ASRock        | AM2NF6G-VSTA                | [475179d795](https://linux-hardware.org/?probe=475179d795) | May 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | [5dbf3199e0](https://linux-hardware.org/?probe=5dbf3199e0) | May 27, 2022 |
| BESSTAR Te... | UM350                       | [e4082f489e](https://linux-hardware.org/?probe=e4082f489e) | May 27, 2022 |
| HP            | 8767 A                      | [553a8de02a](https://linux-hardware.org/?probe=553a8de02a) | May 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4673dbdffc](https://linux-hardware.org/?probe=4673dbdffc) | May 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [cca34ae407](https://linux-hardware.org/?probe=cca34ae407) | May 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d998776096](https://linux-hardware.org/?probe=d998776096) | May 26, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [8e49a588d4](https://linux-hardware.org/?probe=8e49a588d4) | May 25, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [29dd7760ba](https://linux-hardware.org/?probe=29dd7760ba) | May 25, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ca5eb0e4ff](https://linux-hardware.org/?probe=ca5eb0e4ff) | May 24, 2022 |
| MSI           | B450I GAMING PLUS AC        | [dbc555961b](https://linux-hardware.org/?probe=dbc555961b) | May 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| Foxconn       | 2A8C                        | [eda69f1faf](https://linux-hardware.org/?probe=eda69f1faf) | May 22, 2022 |
| Gigabyte      | B250M-D3H-CF                | [a4275c42f4](https://linux-hardware.org/?probe=a4275c42f4) | May 22, 2022 |
| ASUSTek       | Crosshair IV Formula        | [d6c9df82c6](https://linux-hardware.org/?probe=d6c9df82c6) | May 21, 2022 |
| Packard Be... | MCP73PV                     | [14085bdcf2](https://linux-hardware.org/?probe=14085bdcf2) | May 20, 2022 |
| MSI           | B460M-A PRO                 | [2f1ec161d1](https://linux-hardware.org/?probe=2f1ec161d1) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [a941ac6fa0](https://linux-hardware.org/?probe=a941ac6fa0) | May 19, 2022 |
| HP            | 8591                        | [60c5d4f8ca](https://linux-hardware.org/?probe=60c5d4f8ca) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b2eceeef6d](https://linux-hardware.org/?probe=b2eceeef6d) | May 19, 2022 |
| HP            | 8591                        | [fd05ae27e7](https://linux-hardware.org/?probe=fd05ae27e7) | May 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb6038cd9b](https://linux-hardware.org/?probe=cb6038cd9b) | May 18, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [78a9ab4d15](https://linux-hardware.org/?probe=78a9ab4d15) | May 17, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [26f332bc9c](https://linux-hardware.org/?probe=26f332bc9c) | May 16, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [49a3292018](https://linux-hardware.org/?probe=49a3292018) | May 15, 2022 |
| ASUSTek       | B85M-G                      | [dd305c13de](https://linux-hardware.org/?probe=dd305c13de) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| HP            | 8433 11                     | [d3f305a093](https://linux-hardware.org/?probe=d3f305a093) | May 14, 2022 |
| MSI           | B450M PRO-M2                | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ECS           | Asterope                    | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [e1fc077918](https://linux-hardware.org/?probe=e1fc077918) | May 14, 2022 |
| Gigabyte      | GA-K8NF-9                   | [f9d59e3770](https://linux-hardware.org/?probe=f9d59e3770) | May 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [2ac5991afa](https://linux-hardware.org/?probe=2ac5991afa) | May 13, 2022 |
| Medion        | Z370H4-EM                   | [2030abcd26](https://linux-hardware.org/?probe=2030abcd26) | May 12, 2022 |
| ASUSTek       | B150-PLUS                   | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| ECS           | H81H3-I                     | [e184359c46](https://linux-hardware.org/?probe=e184359c46) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| MSI           | B460M-A PRO                 | [29c0818bcd](https://linux-hardware.org/?probe=29c0818bcd) | May 08, 2022 |
| ASUSTek       | CROSSHAIR                   | [39f623cf4d](https://linux-hardware.org/?probe=39f623cf4d) | May 08, 2022 |
| Acer          | Aspire M1935                | [a679a25c13](https://linux-hardware.org/?probe=a679a25c13) | May 07, 2022 |
| Acer          | Aspire M1935                | [62424ad96d](https://linux-hardware.org/?probe=62424ad96d) | May 07, 2022 |
| HP            | 84FD                        | [f99c153a46](https://linux-hardware.org/?probe=f99c153a46) | May 06, 2022 |
| Gigabyte      | G41MT-S2                    | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| ASRock        | FM2A78M Pro4+               | [7a00557ba5](https://linux-hardware.org/?probe=7a00557ba5) | May 05, 2022 |
| HP            | 1998                        | [b35fc936e5](https://linux-hardware.org/?probe=b35fc936e5) | May 04, 2022 |
| Dell          | 0Y56T3 A00                  | [3bdd958639](https://linux-hardware.org/?probe=3bdd958639) | May 04, 2022 |
| MSI           | H170A PC MATE               | [3ebb871ecc](https://linux-hardware.org/?probe=3ebb871ecc) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASRock        | B365M-HDV                   | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Lenovo        | ThinkCentre M58p 6137E61    | [dbf0d596fc](https://linux-hardware.org/?probe=dbf0d596fc) | May 01, 2022 |
| Intel         | V1.3                        | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASUSTek       | Z87-WS                      | [1c67952875](https://linux-hardware.org/?probe=1c67952875) | Apr 29, 2022 |
| Dell          | 0J37VM A00                  | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| ASRock        | AB350M-HDV                  | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| ASUSTek       | Maximus II Formula          | [66a4342140](https://linux-hardware.org/?probe=66a4342140) | Apr 26, 2022 |
| MSI           | H170A PC MATE               | [558be4bee8](https://linux-hardware.org/?probe=558be4bee8) | Apr 26, 2022 |
| Gigabyte      | P55M-UD2                    | [5f9ffc8d46](https://linux-hardware.org/?probe=5f9ffc8d46) | Apr 24, 2022 |
| MSI           | B250M PRO-VDH               | [a1ff9cf092](https://linux-hardware.org/?probe=a1ff9cf092) | Apr 24, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [347ded3d71](https://linux-hardware.org/?probe=347ded3d71) | Apr 23, 2022 |
| Foxconn       | 945 7AD Series              | [04346c58f5](https://linux-hardware.org/?probe=04346c58f5) | Apr 23, 2022 |
| AZW           | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [14089322a6](https://linux-hardware.org/?probe=14089322a6) | Apr 23, 2022 |
| Gigabyte      | H310M S2H x.x               | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| AMI           | Cherry Trail CR             | [61d45f784c](https://linux-hardware.org/?probe=61d45f784c) | Apr 21, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [8034b9ae8c](https://linux-hardware.org/?probe=8034b9ae8c) | Apr 21, 2022 |
| Dell          | 0WMJ54 A01                  | [37ec4fb91d](https://linux-hardware.org/?probe=37ec4fb91d) | Apr 21, 2022 |
| Dell          | 0JP3NX A01                  | [e1c710c88f](https://linux-hardware.org/?probe=e1c710c88f) | Apr 21, 2022 |
| Dell          | 0JP3NX A01                  | [8e6566a555](https://linux-hardware.org/?probe=8e6566a555) | Apr 21, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0ceaadd5e3](https://linux-hardware.org/?probe=0ceaadd5e3) | Apr 20, 2022 |
| Gigabyte      | P55M-UD2                    | [bc5f8558f3](https://linux-hardware.org/?probe=bc5f8558f3) | Apr 20, 2022 |
| MSI           | A320M-A PRO MAX             | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| Lenovo        | 3098 NOK                    | [a9126e3886](https://linux-hardware.org/?probe=a9126e3886) | Apr 19, 2022 |
| Gigabyte      | H81M-S2H                    | [85082e6de6](https://linux-hardware.org/?probe=85082e6de6) | Apr 19, 2022 |
| ASUSTek       | H87-PLUS                    | [10e97d2168](https://linux-hardware.org/?probe=10e97d2168) | Apr 18, 2022 |
| Gigabyte      | B85M-DS3H                   | [c278a421cd](https://linux-hardware.org/?probe=c278a421cd) | Apr 18, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [fb3e0b6b22](https://linux-hardware.org/?probe=fb3e0b6b22) | Apr 18, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | [d921190f7e](https://linux-hardware.org/?probe=d921190f7e) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [a016ec1bce](https://linux-hardware.org/?probe=a016ec1bce) | Apr 16, 2022 |
| ASUSTek       | P5VD2-MX                    | [57fec52891](https://linux-hardware.org/?probe=57fec52891) | Apr 16, 2022 |
| Medion        | MS-7728                     | [443a5ff3dd](https://linux-hardware.org/?probe=443a5ff3dd) | Apr 15, 2022 |
| MSI           | X470 GAMING PLUS            | [72af1b2afe](https://linux-hardware.org/?probe=72af1b2afe) | Apr 15, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| Lenovo        | 3098 NOK                    | [45b5664eb1](https://linux-hardware.org/?probe=45b5664eb1) | Apr 14, 2022 |
| Unknown       | Unknown                     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [ace1daa3ff](https://linux-hardware.org/?probe=ace1daa3ff) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [c77d1618d1](https://linux-hardware.org/?probe=c77d1618d1) | Apr 13, 2022 |
| Gateway       | DS71                        | [3bd1ad84ce](https://linux-hardware.org/?probe=3bd1ad84ce) | Apr 13, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [c5c12d6818](https://linux-hardware.org/?probe=c5c12d6818) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [f986565b6b](https://linux-hardware.org/?probe=f986565b6b) | Apr 10, 2022 |
| Gigabyte      | Q67M-D2H                    | [c95352a142](https://linux-hardware.org/?probe=c95352a142) | Apr 10, 2022 |
| ASUSTek       | Z87-WS                      | [7706049c53](https://linux-hardware.org/?probe=7706049c53) | Apr 10, 2022 |
| Medion        | MS-7366                     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [22502631b3](https://linux-hardware.org/?probe=22502631b3) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [9cc7cc23d6](https://linux-hardware.org/?probe=9cc7cc23d6) | Apr 10, 2022 |
| ASUSTek       | PRIME A320M-K               | [3845180872](https://linux-hardware.org/?probe=3845180872) | Apr 10, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [862e7ffc88](https://linux-hardware.org/?probe=862e7ffc88) | Apr 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [e20b365083](https://linux-hardware.org/?probe=e20b365083) | Apr 09, 2022 |
| Medion        | MS-7366                     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [f45b500a83](https://linux-hardware.org/?probe=f45b500a83) | Apr 09, 2022 |
| ASUSTek       | H97M-PLUS                   | [b90df26c2a](https://linux-hardware.org/?probe=b90df26c2a) | Apr 08, 2022 |
| ASRock        | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ECS           | Nettle2                     | [65cedbb00d](https://linux-hardware.org/?probe=65cedbb00d) | Apr 07, 2022 |
| HP            | 18E5                        | [b79c804a6a](https://linux-hardware.org/?probe=b79c804a6a) | Apr 05, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [939722b6a7](https://linux-hardware.org/?probe=939722b6a7) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [db18e71352](https://linux-hardware.org/?probe=db18e71352) | Apr 05, 2022 |
| Gigabyte      | GA-990FX-GAMING             | [46756b95b5](https://linux-hardware.org/?probe=46756b95b5) | Apr 03, 2022 |
| Medion        | Z370H4-EM                   | [0f9b0bf367](https://linux-hardware.org/?probe=0f9b0bf367) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Gigabyte      | H81M-S2H                    | [8a810aa9f6](https://linux-hardware.org/?probe=8a810aa9f6) | Apr 02, 2022 |
| MSI           | H81M-E35 V2                 | [a3aea1cbf5](https://linux-hardware.org/?probe=a3aea1cbf5) | Apr 02, 2022 |
| Wistron       | ProLiant ML110 G5           | [ccea23c3b5](https://linux-hardware.org/?probe=ccea23c3b5) | Apr 01, 2022 |
| Wistron       | ProLiant ML110 G5           | [4c01aec65d](https://linux-hardware.org/?probe=4c01aec65d) | Apr 01, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [47e2449cf5](https://linux-hardware.org/?probe=47e2449cf5) | Apr 01, 2022 |
| MSI           | H410M PRO-VH                | [e4ef535529](https://linux-hardware.org/?probe=e4ef535529) | Mar 31, 2022 |
| Unknown       | Unknown                     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| ASUSTek       | PRIME Z390-A                | [5307aba2c3](https://linux-hardware.org/?probe=5307aba2c3) | Mar 30, 2022 |
| ASUSTek       | D940MX                      | [bdc8831182](https://linux-hardware.org/?probe=bdc8831182) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [7c852d78e1](https://linux-hardware.org/?probe=7c852d78e1) | Mar 27, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ce82ab584b](https://linux-hardware.org/?probe=ce82ab584b) | Mar 26, 2022 |
| Gigabyte      | H61M-USB3H                  | [f852a0cb0d](https://linux-hardware.org/?probe=f852a0cb0d) | Mar 26, 2022 |
| Intel         | B75                         | [9f73efdcc8](https://linux-hardware.org/?probe=9f73efdcc8) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [b2c47467cc](https://linux-hardware.org/?probe=b2c47467cc) | Mar 25, 2022 |
| Gigabyte      | GA-73PVM-S2H                | [ac9f20a77c](https://linux-hardware.org/?probe=ac9f20a77c) | Mar 23, 2022 |
| Gigabyte      | 970A-DS3P                   | [012e192ece](https://linux-hardware.org/?probe=012e192ece) | Mar 22, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [5d6041ffc4](https://linux-hardware.org/?probe=5d6041ffc4) | Mar 21, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [7c5dff1166](https://linux-hardware.org/?probe=7c5dff1166) | Mar 21, 2022 |
| HP            | 18E7                        | [727446a2df](https://linux-hardware.org/?probe=727446a2df) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| ECS           | H87H3-M                     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6dd4a41851](https://linux-hardware.org/?probe=6dd4a41851) | Mar 19, 2022 |
| Unknown       | Intel X79                   | [1b92468c15](https://linux-hardware.org/?probe=1b92468c15) | Mar 17, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [bca7145550](https://linux-hardware.org/?probe=bca7145550) | Mar 17, 2022 |
| ECS           | H110I-C4P                   | [de40e2a12d](https://linux-hardware.org/?probe=de40e2a12d) | Mar 16, 2022 |
| Pegatron      | 2ACF                        | [56d5f5b8ec](https://linux-hardware.org/?probe=56d5f5b8ec) | Mar 16, 2022 |
| ASUSTek       | PRIME B450M-A               | [75a7099e71](https://linux-hardware.org/?probe=75a7099e71) | Mar 15, 2022 |
| ASRock        | B150 Gaming K4              | [a03321659f](https://linux-hardware.org/?probe=a03321659f) | Mar 15, 2022 |
| HP            | 1497                        | [0aaa7bf906](https://linux-hardware.org/?probe=0aaa7bf906) | Mar 15, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [e284a60544](https://linux-hardware.org/?probe=e284a60544) | Mar 14, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [e0efdaa76a](https://linux-hardware.org/?probe=e0efdaa76a) | Mar 13, 2022 |
| ASUSTek       | P5QC                        | [144a20f079](https://linux-hardware.org/?probe=144a20f079) | Mar 13, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [06b1c7d30a](https://linux-hardware.org/?probe=06b1c7d30a) | Mar 13, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [41737e64bb](https://linux-hardware.org/?probe=41737e64bb) | Mar 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [e0e46ae824](https://linux-hardware.org/?probe=e0e46ae824) | Mar 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [f225ce7d58](https://linux-hardware.org/?probe=f225ce7d58) | Mar 12, 2022 |
| HP            | 3398                        | [6afe044e03](https://linux-hardware.org/?probe=6afe044e03) | Mar 12, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [72775a871a](https://linux-hardware.org/?probe=72775a871a) | Mar 11, 2022 |
| Dell          | 0F6X5P A00                  | [b58520e2a7](https://linux-hardware.org/?probe=b58520e2a7) | Mar 11, 2022 |
| ASRock        | H81M-VG4 R2.0               | [2d72940994](https://linux-hardware.org/?probe=2d72940994) | Mar 10, 2022 |
| MSI           | Z270 GAMING M3              | [989eec2f5f](https://linux-hardware.org/?probe=989eec2f5f) | Mar 10, 2022 |
| ASRock        | Q1900M                      | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| Dell          | 0J37VM A00                  | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| ASUSTek       | PRIME A320M-K               | [9695618053](https://linux-hardware.org/?probe=9695618053) | Mar 08, 2022 |
| Intel         | DH55TC AAE70932-302         | [60bdf00035](https://linux-hardware.org/?probe=60bdf00035) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | [13a7b2300c](https://linux-hardware.org/?probe=13a7b2300c) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | [245ea26d7f](https://linux-hardware.org/?probe=245ea26d7f) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | [d681586515](https://linux-hardware.org/?probe=d681586515) | Mar 07, 2022 |
| Intel         | DH55TC AAE70932-205         | [459b5909e6](https://linux-hardware.org/?probe=459b5909e6) | Mar 07, 2022 |
| ASRock        | FM2A88X+ Killer             | [c75eb0d27f](https://linux-hardware.org/?probe=c75eb0d27f) | Mar 07, 2022 |
| ASUSTek       | PRIME Z590-A                | [72960138d6](https://linux-hardware.org/?probe=72960138d6) | Mar 06, 2022 |
| ASRock        | X99E-ITX/ac                 | [0cf67f0201](https://linux-hardware.org/?probe=0cf67f0201) | Mar 06, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [727fc2327e](https://linux-hardware.org/?probe=727fc2327e) | Mar 04, 2022 |
| ASUSTek       | PRIME H510M-A               | [472b82d84c](https://linux-hardware.org/?probe=472b82d84c) | Mar 03, 2022 |
| ASRock        | H110M-HDV                   | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| ASUSTek       | P5KPL/EPU                   | [26cc94d2d9](https://linux-hardware.org/?probe=26cc94d2d9) | Mar 02, 2022 |
| HP            | 8054                        | [272944ecda](https://linux-hardware.org/?probe=272944ecda) | Mar 02, 2022 |
| Gigabyte      | H55M-UD2H                   | [074d13c1d2](https://linux-hardware.org/?probe=074d13c1d2) | Mar 01, 2022 |
| ASUSTek       | CM6870                      | [45c8e5fea2](https://linux-hardware.org/?probe=45c8e5fea2) | Mar 01, 2022 |
| ASUSTek       | Z170-PRO                    | [28d2c658a9](https://linux-hardware.org/?probe=28d2c658a9) | Feb 28, 2022 |
| HP            | 0AA8h                       | [e6f96c5f67](https://linux-hardware.org/?probe=e6f96c5f67) | Feb 28, 2022 |
| MSI           | Indio                       | [5005ca76bd](https://linux-hardware.org/?probe=5005ca76bd) | Feb 27, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [f12fd06900](https://linux-hardware.org/?probe=f12fd06900) | Feb 27, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [5a78616e2f](https://linux-hardware.org/?probe=5a78616e2f) | Feb 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4c3afa7f](https://linux-hardware.org/?probe=6d4c3afa7f) | Feb 27, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| MSI           | B560M PRO-VDH               | [707dc0d97b](https://linux-hardware.org/?probe=707dc0d97b) | Feb 26, 2022 |
| ASUSTek       | P5Q DELUXE                  | [bff628fbba](https://linux-hardware.org/?probe=bff628fbba) | Feb 25, 2022 |
| Gigabyte      | H310M S2H                   | [2ee02369e0](https://linux-hardware.org/?probe=2ee02369e0) | Feb 25, 2022 |
| ASUSTek       | PRIME H510M-D               | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Dell          | 0NKW6Y A01                  | [cf92b61f90](https://linux-hardware.org/?probe=cf92b61f90) | Feb 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [76ba570966](https://linux-hardware.org/?probe=76ba570966) | Feb 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0d69aa634e](https://linux-hardware.org/?probe=0d69aa634e) | Feb 22, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [e5706d5397](https://linux-hardware.org/?probe=e5706d5397) | Feb 22, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | [f6f59e8802](https://linux-hardware.org/?probe=f6f59e8802) | Feb 22, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | [90db107d96](https://linux-hardware.org/?probe=90db107d96) | Feb 22, 2022 |
| MSI           | X570-A PRO                  | [6f419a41f3](https://linux-hardware.org/?probe=6f419a41f3) | Feb 20, 2022 |
| HP            | 158A                        | [f31e70e834](https://linux-hardware.org/?probe=f31e70e834) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [ef382cadcd](https://linux-hardware.org/?probe=ef382cadcd) | Feb 18, 2022 |
| ASUSTek       | H110M-D                     | [b3e3d47340](https://linux-hardware.org/?probe=b3e3d47340) | Feb 17, 2022 |
| Gigabyte      | 970A-DS3P                   | [edbe3bb3bb](https://linux-hardware.org/?probe=edbe3bb3bb) | Feb 17, 2022 |
| HP            | 2820h                       | [f45476e17a](https://linux-hardware.org/?probe=f45476e17a) | Feb 17, 2022 |
| ASUSTek       | H110M-D                     | [9b311cac8b](https://linux-hardware.org/?probe=9b311cac8b) | Feb 17, 2022 |
| HP            | 0AA8h                       | [cb11b8e6fb](https://linux-hardware.org/?probe=cb11b8e6fb) | Feb 16, 2022 |
| ASRock        | N68-GS                      | [06e4bc5238](https://linux-hardware.org/?probe=06e4bc5238) | Feb 16, 2022 |
| Gigabyte      | G41MT-D3V                   | [1d0a4e4e9e](https://linux-hardware.org/?probe=1d0a4e4e9e) | Feb 16, 2022 |
| MSI           | H81M-E35 V2                 | [20aafa92dd](https://linux-hardware.org/?probe=20aafa92dd) | Feb 16, 2022 |
| Intel         | X79M-S                      | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| Packard Be... | MCP61                       | [e209ef5de2](https://linux-hardware.org/?probe=e209ef5de2) | Feb 14, 2022 |
| IBM           | 81077AG                     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| Medion        | Z370H4-EM                   | [254b8351a1](https://linux-hardware.org/?probe=254b8351a1) | Feb 14, 2022 |
| Dell          | 0FH884                      | [bd2aa894cc](https://linux-hardware.org/?probe=bd2aa894cc) | Feb 13, 2022 |
| ASUSTek       | A55BM-PLUS                  | [53753f59d3](https://linux-hardware.org/?probe=53753f59d3) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8753c04911](https://linux-hardware.org/?probe=8753c04911) | Feb 13, 2022 |
| Gigabyte      | H110M-S2H-CF                | [50224f8f4c](https://linux-hardware.org/?probe=50224f8f4c) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [f3f17f2dd0](https://linux-hardware.org/?probe=f3f17f2dd0) | Feb 13, 2022 |
| MSI           | H81M-E35 V2                 | [fdba4d1aab](https://linux-hardware.org/?probe=fdba4d1aab) | Feb 13, 2022 |
| MSI           | X99S SLI PLUS               | [dd15aa61af](https://linux-hardware.org/?probe=dd15aa61af) | Feb 13, 2022 |
| Dell          | 0D28YY A00                  | [1fe2aa51aa](https://linux-hardware.org/?probe=1fe2aa51aa) | Feb 13, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [32d9ce9d27](https://linux-hardware.org/?probe=32d9ce9d27) | Feb 12, 2022 |
| Acer          | Aspire X3950                | [28f9470608](https://linux-hardware.org/?probe=28f9470608) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| AZW           | BT3 X                       | [583bf1d943](https://linux-hardware.org/?probe=583bf1d943) | Feb 12, 2022 |
| ASUSTek       | P5G41T-M LX                 | [165720aab0](https://linux-hardware.org/?probe=165720aab0) | Feb 11, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [f4dec544b7](https://linux-hardware.org/?probe=f4dec544b7) | Feb 11, 2022 |
| Gigabyte      | 970A-DS3P                   | [60f9ecb597](https://linux-hardware.org/?probe=60f9ecb597) | Feb 11, 2022 |
| MSI           | H410M PRO-VH                | [6b2970ce21](https://linux-hardware.org/?probe=6b2970ce21) | Feb 11, 2022 |
| ASRock        | G41C-GS R2.0                | [9eed789082](https://linux-hardware.org/?probe=9eed789082) | Feb 10, 2022 |
| ASUSTek       | P8H67-M PRO                 | [fe18f09b36](https://linux-hardware.org/?probe=fe18f09b36) | Feb 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3196a6c153](https://linux-hardware.org/?probe=3196a6c153) | Feb 09, 2022 |
| MSI           | Z390-A PRO                  | [a7c54c30a7](https://linux-hardware.org/?probe=a7c54c30a7) | Feb 09, 2022 |
| HP            | 1497                        | [a80fd6e442](https://linux-hardware.org/?probe=a80fd6e442) | Feb 09, 2022 |
| Gigabyte      | B85M-D3H                    | [add118efcc](https://linux-hardware.org/?probe=add118efcc) | Feb 09, 2022 |
| ECS           | A78F2P-M2                   | [8ddba334a5](https://linux-hardware.org/?probe=8ddba334a5) | Feb 09, 2022 |
| ASRock        | B450M Steel Legend          | [bd05301177](https://linux-hardware.org/?probe=bd05301177) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ASRock        | Z87 Pro3                    | [dea0b07f08](https://linux-hardware.org/?probe=dea0b07f08) | Feb 08, 2022 |
| ASUSTek       | B85M-G                      | [8ed1aa83eb](https://linux-hardware.org/?probe=8ed1aa83eb) | Feb 08, 2022 |
| MSI           | H77MA-G43                   | [67f0fd2098](https://linux-hardware.org/?probe=67f0fd2098) | Feb 08, 2022 |
| Gigabyte      | MTGU5AB-00                  | [21eedf9331](https://linux-hardware.org/?probe=21eedf9331) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [9dd525ae45](https://linux-hardware.org/?probe=9dd525ae45) | Feb 07, 2022 |
| Lenovo        | 3140 NOK                    | [5391d351ee](https://linux-hardware.org/?probe=5391d351ee) | Feb 07, 2022 |
| HP            | 2820h                       | [347b6a83de](https://linux-hardware.org/?probe=347b6a83de) | Feb 07, 2022 |
| Gigabyte      | MZGLKBP-00                  | [e217e9db4a](https://linux-hardware.org/?probe=e217e9db4a) | Feb 07, 2022 |
| HP            | 2820h                       | [7c5fb9c18f](https://linux-hardware.org/?probe=7c5fb9c18f) | Feb 07, 2022 |
| MSI           | B450I GAMING PLUS AC        | [3aa5fa2d91](https://linux-hardware.org/?probe=3aa5fa2d91) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [b918b737c2](https://linux-hardware.org/?probe=b918b737c2) | Feb 06, 2022 |
| MSI           | B450I GAMING PLUS AC        | [0b905c31b5](https://linux-hardware.org/?probe=0b905c31b5) | Feb 05, 2022 |
| Gateway       | DS71                        | [cefb514e23](https://linux-hardware.org/?probe=cefb514e23) | Feb 05, 2022 |
| Gigabyte      | B365M DS3H                  | [6d5ae4cd37](https://linux-hardware.org/?probe=6d5ae4cd37) | Feb 05, 2022 |
| Gigabyte      | B365M DS3H                  | [b11a458ecb](https://linux-hardware.org/?probe=b11a458ecb) | Feb 04, 2022 |
| HP            | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| HP            | 8433 11                     | [a67fa333f1](https://linux-hardware.org/?probe=a67fa333f1) | Feb 01, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [44411daa5a](https://linux-hardware.org/?probe=44411daa5a) | Jan 31, 2022 |
| HP            | 3047h                       | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [bef8f6667a](https://linux-hardware.org/?probe=bef8f6667a) | Jan 28, 2022 |
| ASUSTek       | P8Z77-V                     | [8747994f49](https://linux-hardware.org/?probe=8747994f49) | Jan 27, 2022 |
| Medion        | H61H2-LM3                   | [c8552cc10c](https://linux-hardware.org/?probe=c8552cc10c) | Jan 26, 2022 |
| ASUSTek       | P9X79 WS                    | [ee0e90a869](https://linux-hardware.org/?probe=ee0e90a869) | Jan 26, 2022 |
| ASRock        | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| ASUSTek       | SABERTOOTH 55i              | [5c67654acf](https://linux-hardware.org/?probe=5c67654acf) | Jan 23, 2022 |
| Gigabyte      | GA-MA790XT-UD4P             | [9bb58c340e](https://linux-hardware.org/?probe=9bb58c340e) | Jan 22, 2022 |
| Huanan        | X99-F8                      | [4e1327b556](https://linux-hardware.org/?probe=4e1327b556) | Jan 22, 2022 |
| ASRock        | Z170 Extreme4               | [1484d8fbb7](https://linux-hardware.org/?probe=1484d8fbb7) | Jan 21, 2022 |
| MSI           | Z97 PC Mate                 | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Gigabyte      | H81M-S2H                    | [5a010a60d7](https://linux-hardware.org/?probe=5a010a60d7) | Jan 20, 2022 |
| Dell          | 0D28YY A01                  | [f427224d76](https://linux-hardware.org/?probe=f427224d76) | Jan 20, 2022 |
| ASUSTek       | V-P5G31                     | [ab3ad44c74](https://linux-hardware.org/?probe=ab3ad44c74) | Jan 18, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [00dc05487b](https://linux-hardware.org/?probe=00dc05487b) | Jan 16, 2022 |
| Huanan        | X99-F8                      | [b03aaab88c](https://linux-hardware.org/?probe=b03aaab88c) | Jan 16, 2022 |
| HP            | 8643 SMVB                   | [51bcf449dc](https://linux-hardware.org/?probe=51bcf449dc) | Jan 14, 2022 |
| ASRock        | H61M-VG4                    | [ee03e4043a](https://linux-hardware.org/?probe=ee03e4043a) | Jan 14, 2022 |
| MSI           | B450M BAZOOKA V2            | [6779dfb408](https://linux-hardware.org/?probe=6779dfb408) | Jan 14, 2022 |
| Medion        | Z370H4-EM                   | [a4bb231aa7](https://linux-hardware.org/?probe=a4bb231aa7) | Jan 13, 2022 |
| HP            | 82B4                        | [79444cc816](https://linux-hardware.org/?probe=79444cc816) | Jan 12, 2022 |
| Dell          | 0D28YY A01                  | [34b3a0e6e7](https://linux-hardware.org/?probe=34b3a0e6e7) | Jan 12, 2022 |
| Gigabyte      | B450M GAMING                | [9435764f10](https://linux-hardware.org/?probe=9435764f10) | Jan 11, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [0d866add7c](https://linux-hardware.org/?probe=0d866add7c) | Jan 11, 2022 |
| ASRock        | FM2A88X+ Killer             | [fdcf291970](https://linux-hardware.org/?probe=fdcf291970) | Jan 09, 2022 |
| HP            | 18E7                        | [a46399c837](https://linux-hardware.org/?probe=a46399c837) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| MSI           | B560M PRO-VDH               | [4538696d8c](https://linux-hardware.org/?probe=4538696d8c) | Jan 07, 2022 |
| OEM           | BTC B250                    | [8455850c56](https://linux-hardware.org/?probe=8455850c56) | Jan 07, 2022 |
| ASUSTek       | Z77-A                       | [627b0162be](https://linux-hardware.org/?probe=627b0162be) | Jan 06, 2022 |
| ASRock        | B75 Pro3-M                  | [2daf055722](https://linux-hardware.org/?probe=2daf055722) | Jan 05, 2022 |
| ECS           | GLKM-MINI                   | [d1951b7d67](https://linux-hardware.org/?probe=d1951b7d67) | Jan 05, 2022 |
| HP            | 3047h                       | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| HP            | 2AF9                        | [50fd3d690f](https://linux-hardware.org/?probe=50fd3d690f) | Jan 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [98ed791fc8](https://linux-hardware.org/?probe=98ed791fc8) | Dec 31, 2021 |
| HP            | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [dd7335ec13](https://linux-hardware.org/?probe=dd7335ec13) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [b1574cb081](https://linux-hardware.org/?probe=b1574cb081) | Dec 25, 2021 |
| MSI           | B560M PRO-VDH               | [70287063b9](https://linux-hardware.org/?probe=70287063b9) | Dec 24, 2021 |
| MSI           | B560M PRO-VDH               | [508decf868](https://linux-hardware.org/?probe=508decf868) | Dec 24, 2021 |
| MSI           | B560M PRO-VDH               | [4e8b9c1c51](https://linux-hardware.org/?probe=4e8b9c1c51) | Dec 24, 2021 |
| Huanan        | X79 249PC V2.2              | [2ed1172293](https://linux-hardware.org/?probe=2ed1172293) | Dec 23, 2021 |
| AZW           | Gemini X45                  | [84dd0d27a1](https://linux-hardware.org/?probe=84dd0d27a1) | Dec 23, 2021 |
| MSI           | B250M PRO-VDH               | [c63d35a718](https://linux-hardware.org/?probe=c63d35a718) | Dec 23, 2021 |
| MSI           | A320M PRO-VH PLUS           | [27379a7599](https://linux-hardware.org/?probe=27379a7599) | Dec 22, 2021 |
| Intel         | DH67CL AAG10212-210         | [4cf62d2b87](https://linux-hardware.org/?probe=4cf62d2b87) | Dec 22, 2021 |
| ASRock        | X399 Taichi                 | [16e27617b9](https://linux-hardware.org/?probe=16e27617b9) | Dec 20, 2021 |
| MSI           | B85M-P33                    | [27c88061e8](https://linux-hardware.org/?probe=27c88061e8) | Dec 19, 2021 |
| ASUSTek       | PRIME B350M-A               | [d38d7f8ea2](https://linux-hardware.org/?probe=d38d7f8ea2) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [db6f258b1d](https://linux-hardware.org/?probe=db6f258b1d) | Dec 18, 2021 |
| Supermicro    | X10SDV-6C-TLN4F             | [07aa1e6365](https://linux-hardware.org/?probe=07aa1e6365) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Gigabyte      | H410M S2H V3                | [afff6656ae](https://linux-hardware.org/?probe=afff6656ae) | Dec 16, 2021 |
| Dell          | 0K240Y A01                  | [b1b2542939](https://linux-hardware.org/?probe=b1b2542939) | Dec 16, 2021 |
| MSI           | A320M-A PRO                 | [f3f7e374e1](https://linux-hardware.org/?probe=f3f7e374e1) | Dec 16, 2021 |
| HP            | 84FD                        | [d857edd3b6](https://linux-hardware.org/?probe=d857edd3b6) | Dec 14, 2021 |
| HP            | 84FD                        | [4f585e6406](https://linux-hardware.org/?probe=4f585e6406) | Dec 14, 2021 |
| ASUSTek       | CM6870                      | [05624c26d2](https://linux-hardware.org/?probe=05624c26d2) | Dec 14, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [05db94d8a5](https://linux-hardware.org/?probe=05db94d8a5) | Dec 14, 2021 |
| MSI           | MPG Z590 GAMING PLUS        | [b3a7521bf7](https://linux-hardware.org/?probe=b3a7521bf7) | Dec 14, 2021 |
| Acer          | E415SM                      | [cf0a135e4f](https://linux-hardware.org/?probe=cf0a135e4f) | Dec 12, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | [563310cf3d](https://linux-hardware.org/?probe=563310cf3d) | Dec 12, 2021 |
| ASUSTek       | P6T                         | [b789a1151e](https://linux-hardware.org/?probe=b789a1151e) | Dec 11, 2021 |
| HP            | 0A54h                       | [417e076869](https://linux-hardware.org/?probe=417e076869) | Dec 10, 2021 |
| ASUSTek       | P6T                         | [d04f9d16a8](https://linux-hardware.org/?probe=d04f9d16a8) | Dec 08, 2021 |
| Gigabyte      | H81M-HD3                    | [f74f7d2a25](https://linux-hardware.org/?probe=f74f7d2a25) | Dec 08, 2021 |
| ASUSTek       | Z97-A-USB31                 | [5969d315ee](https://linux-hardware.org/?probe=5969d315ee) | Dec 08, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [87c78340f0](https://linux-hardware.org/?probe=87c78340f0) | Dec 07, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9635235b55](https://linux-hardware.org/?probe=9635235b55) | Dec 06, 2021 |
| ASRock        | ALiveNF6G-VSTA              | [7acdf3e3ad](https://linux-hardware.org/?probe=7acdf3e3ad) | Dec 05, 2021 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | [7bb538c6f0](https://linux-hardware.org/?probe=7bb538c6f0) | Dec 05, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [7f6abaf57b](https://linux-hardware.org/?probe=7f6abaf57b) | Dec 05, 2021 |
| ASUSTek       | Z87-A                       | [e7d4963834](https://linux-hardware.org/?probe=e7d4963834) | Dec 04, 2021 |
| Gigabyte      | H81M-HD3                    | [0ea5966544](https://linux-hardware.org/?probe=0ea5966544) | Dec 04, 2021 |
| MSI           | Z370 PC PRO                 | [e9d80c066a](https://linux-hardware.org/?probe=e9d80c066a) | Dec 04, 2021 |
| ASRock        | G41C-GS R2.0                | [48642d55e0](https://linux-hardware.org/?probe=48642d55e0) | Dec 01, 2021 |
| Acer          | Aspire X1420                | [ff2c8a9378](https://linux-hardware.org/?probe=ff2c8a9378) | Dec 01, 2021 |
| MSI           | B460M-A PRO                 | [f972dc5e2a](https://linux-hardware.org/?probe=f972dc5e2a) | Nov 30, 2021 |
| ASUSTek       | Z87-WS                      | [d08bda679e](https://linux-hardware.org/?probe=d08bda679e) | Nov 30, 2021 |
| MSI           | H410M PRO-VH                | [da53c38fba](https://linux-hardware.org/?probe=da53c38fba) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [1749dd52d5](https://linux-hardware.org/?probe=1749dd52d5) | Nov 28, 2021 |
| MSI           | H410M PRO-VH                | [65f9949ec4](https://linux-hardware.org/?probe=65f9949ec4) | Nov 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [4bbdbb4261](https://linux-hardware.org/?probe=4bbdbb4261) | Nov 27, 2021 |
| Gigabyte      | 945GCMX-S2                  | [e0b139c2a2](https://linux-hardware.org/?probe=e0b139c2a2) | Nov 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| ASRock        | FM2A78M Pro4+               | [1670e83f4d](https://linux-hardware.org/?probe=1670e83f4d) | Nov 24, 2021 |
| ASUSTek       | AM1M-A                      | [5114945f73](https://linux-hardware.org/?probe=5114945f73) | Nov 23, 2021 |
| Gigabyte      | G41MT-S2                    | [8031417427](https://linux-hardware.org/?probe=8031417427) | Nov 23, 2021 |
| ASRock        | 960GC-GS FX                 | [25331654e6](https://linux-hardware.org/?probe=25331654e6) | Nov 23, 2021 |
| Gigabyte      | GA-MA790X-UD4               | [0a19a35ac4](https://linux-hardware.org/?probe=0a19a35ac4) | Nov 22, 2021 |
| NEC Comput... | GA-8I945PM                  | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| HP            | 8055                        | [687064a734](https://linux-hardware.org/?probe=687064a734) | Nov 21, 2021 |
| ASUSTek       | B150-PLUS                   | [3c4c353831](https://linux-hardware.org/?probe=3c4c353831) | Nov 19, 2021 |
| Gigabyte      | G41M-ES2H                   | [8885080689](https://linux-hardware.org/?probe=8885080689) | Nov 19, 2021 |
| ASRock        | G41C-GS R2.0                | [4c0b3b9df0](https://linux-hardware.org/?probe=4c0b3b9df0) | Nov 19, 2021 |
| Gigabyte      | B550M DS3H                  | [93c3ab9ed1](https://linux-hardware.org/?probe=93c3ab9ed1) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [47a9999310](https://linux-hardware.org/?probe=47a9999310) | Nov 17, 2021 |
| ASUSTek       | D300TA                      | [616be7f173](https://linux-hardware.org/?probe=616be7f173) | Nov 17, 2021 |
| Lenovo        | 3168 NOK                    | [28a3c13b73](https://linux-hardware.org/?probe=28a3c13b73) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | [e203b53dd6](https://linux-hardware.org/?probe=e203b53dd6) | Nov 15, 2021 |
| ASUSTek       | PRIME X570-P                | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| MSI           | H81M-P32L                   | [85e36b9cfc](https://linux-hardware.org/?probe=85e36b9cfc) | Nov 15, 2021 |
| ASUSTek       | P6T                         | [bc74d32e1c](https://linux-hardware.org/?probe=bc74d32e1c) | Nov 14, 2021 |
| Gigabyte      | X570 AORUS PRO              | [b0b5f16e06](https://linux-hardware.org/?probe=b0b5f16e06) | Nov 14, 2021 |
| Gigabyte      | G41MT-S2PT                  | [3e5ea61173](https://linux-hardware.org/?probe=3e5ea61173) | Nov 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [086e87d574](https://linux-hardware.org/?probe=086e87d574) | Nov 14, 2021 |
| Gigabyte      | AX370-Gaming K5-CF          | [0529cdf66c](https://linux-hardware.org/?probe=0529cdf66c) | Nov 12, 2021 |
| ASUSTek       | Z170-PRO                    | [d35dc57133](https://linux-hardware.org/?probe=d35dc57133) | Nov 12, 2021 |
| Gigabyte      | EP31-DS3L                   | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [a119684a3e](https://linux-hardware.org/?probe=a119684a3e) | Nov 11, 2021 |
| ASUSTek       | M5A97                       | [027f2fbf96](https://linux-hardware.org/?probe=027f2fbf96) | Nov 11, 2021 |
| ASUSTek       | P7H55-M                     | [33e52a0ca7](https://linux-hardware.org/?probe=33e52a0ca7) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| MSI           | IONA                        | [1b000ee1a0](https://linux-hardware.org/?probe=1b000ee1a0) | Nov 10, 2021 |
| ASUSTek       | PRIME B550M-A               | [269b146e10](https://linux-hardware.org/?probe=269b146e10) | Nov 10, 2021 |
| MSI           | IONA                        | [060bfa8681](https://linux-hardware.org/?probe=060bfa8681) | Nov 10, 2021 |
| Gigabyte      | X570 UD                     | [c5ae0c1fca](https://linux-hardware.org/?probe=c5ae0c1fca) | Nov 09, 2021 |
| ASUSTek       | P7H55-M                     | [d479f8ff66](https://linux-hardware.org/?probe=d479f8ff66) | Nov 09, 2021 |
| Dell          | 0DF42J A00                  | [bea323f69b](https://linux-hardware.org/?probe=bea323f69b) | Nov 09, 2021 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | [a7ba011636](https://linux-hardware.org/?probe=a7ba011636) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-A               | [9456930b53](https://linux-hardware.org/?probe=9456930b53) | Nov 08, 2021 |
| ECS           | H410-SF110                  | [15507f0d31](https://linux-hardware.org/?probe=15507f0d31) | Nov 05, 2021 |
| ASUSTek       | PRIME Z370-P                | [50301dd3e3](https://linux-hardware.org/?probe=50301dd3e3) | Nov 04, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [14c9dda4cd](https://linux-hardware.org/?probe=14c9dda4cd) | Nov 04, 2021 |
| Acer          | RS740DVF                    | [2828e1ed3e](https://linux-hardware.org/?probe=2828e1ed3e) | Nov 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [731013ba31](https://linux-hardware.org/?probe=731013ba31) | Nov 02, 2021 |
| Gigabyte      | P31-ES3G                    | [11d4cc5eda](https://linux-hardware.org/?probe=11d4cc5eda) | Nov 01, 2021 |
| ASUSTek       | Z170-PRO                    | [03f03dfcb8](https://linux-hardware.org/?probe=03f03dfcb8) | Nov 01, 2021 |
| Dell          | 07T4MC A06                  | [5c76cd586e](https://linux-hardware.org/?probe=5c76cd586e) | Nov 01, 2021 |
| ASRock        | X399 Taichi                 | [a26b02e6b0](https://linux-hardware.org/?probe=a26b02e6b0) | Nov 01, 2021 |
| ASUSTek       | Z170-PRO                    | [427c8b8d8f](https://linux-hardware.org/?probe=427c8b8d8f) | Nov 01, 2021 |
| Lenovo        | ThinkStation S10 6483BE3    | [56edf0b800](https://linux-hardware.org/?probe=56edf0b800) | Oct 31, 2021 |
| MSI           | Z370 GAMING PLUS            | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Dell          | 07T4MC A06                  | [29f013d2e2](https://linux-hardware.org/?probe=29f013d2e2) | Oct 30, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [bd2e23a97b](https://linux-hardware.org/?probe=bd2e23a97b) | Oct 30, 2021 |
| HP            | 1998                        | [b9e492678d](https://linux-hardware.org/?probe=b9e492678d) | Oct 29, 2021 |
| Acer          | Aspire XC600 v1.0           | [58dfae44e0](https://linux-hardware.org/?probe=58dfae44e0) | Oct 29, 2021 |
| ASUSTek       | P5Q-PRO                     | [f6317b60dd](https://linux-hardware.org/?probe=f6317b60dd) | Oct 28, 2021 |
| MSI           | A88X-G43                    | [1c7a02bd63](https://linux-hardware.org/?probe=1c7a02bd63) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [369b39d1be](https://linux-hardware.org/?probe=369b39d1be) | Oct 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [5b7faf1cc6](https://linux-hardware.org/?probe=5b7faf1cc6) | Oct 28, 2021 |
| AOpen         | i67QMx-HA R1.03 55DE6100... | [96bd4fe29a](https://linux-hardware.org/?probe=96bd4fe29a) | Oct 27, 2021 |
| Huanan        | X99-F8 V2.0                 | [17b2218dab](https://linux-hardware.org/?probe=17b2218dab) | Oct 27, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [a3a377a482](https://linux-hardware.org/?probe=a3a377a482) | Oct 27, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [2a39ef919c](https://linux-hardware.org/?probe=2a39ef919c) | Oct 26, 2021 |
| ASUSTek       | PRIME Z390-A                | [382b33add2](https://linux-hardware.org/?probe=382b33add2) | Oct 25, 2021 |
| AMI           | Cherry Trail CR             | [9333e233d6](https://linux-hardware.org/?probe=9333e233d6) | Oct 24, 2021 |
| AMI           | Cherry Trail CR             | [7d78a3c31f](https://linux-hardware.org/?probe=7d78a3c31f) | Oct 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b8967bd2fd](https://linux-hardware.org/?probe=b8967bd2fd) | Oct 23, 2021 |
| ASUSTek       | P8H67                       | [d503cec851](https://linux-hardware.org/?probe=d503cec851) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | [7ffce9bbc2](https://linux-hardware.org/?probe=7ffce9bbc2) | Oct 21, 2021 |
| MSI           | B350 TOMAHAWK               | [a119d97189](https://linux-hardware.org/?probe=a119d97189) | Oct 20, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [b010f12ecd](https://linux-hardware.org/?probe=b010f12ecd) | Oct 17, 2021 |
| HP            | 0A58h                       | [631a7049b9](https://linux-hardware.org/?probe=631a7049b9) | Oct 17, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [12db76b549](https://linux-hardware.org/?probe=12db76b549) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-A                | [2a03ec745f](https://linux-hardware.org/?probe=2a03ec745f) | Oct 16, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4379b423f0](https://linux-hardware.org/?probe=4379b423f0) | Oct 15, 2021 |
| ASUSTek       | H110M-D                     | [b0cc9343a8](https://linux-hardware.org/?probe=b0cc9343a8) | Oct 15, 2021 |
| Gigabyte      | H61MA-D3V                   | [a876a8d816](https://linux-hardware.org/?probe=a876a8d816) | Oct 13, 2021 |
| Dell          | 0JP3NX A01                  | [ab8bf375d4](https://linux-hardware.org/?probe=ab8bf375d4) | Oct 13, 2021 |
| Dell          | 0JP3NX A01                  | [b704fe7d0c](https://linux-hardware.org/?probe=b704fe7d0c) | Oct 13, 2021 |
| Lenovo        | SHARKBAY 0B98405 STD        | [6d09c42ade](https://linux-hardware.org/?probe=6d09c42ade) | Oct 12, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [34774c0428](https://linux-hardware.org/?probe=34774c0428) | Oct 12, 2021 |
| Gigabyte      | H61M-D2H-USB3               | [4d07ab8337](https://linux-hardware.org/?probe=4d07ab8337) | Oct 12, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [f619d93316](https://linux-hardware.org/?probe=f619d93316) | Oct 11, 2021 |
| MSI           | B75MA-P45                   | [a6aa274e8b](https://linux-hardware.org/?probe=a6aa274e8b) | Oct 10, 2021 |
| MSI           | B75MA-P45                   | [eb810bdb07](https://linux-hardware.org/?probe=eb810bdb07) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ad1aaa06bc](https://linux-hardware.org/?probe=ad1aaa06bc) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6beb9ddceb](https://linux-hardware.org/?probe=6beb9ddceb) | Oct 09, 2021 |
| ASUSTek       | P8Z77-M                     | [e2837da9c2](https://linux-hardware.org/?probe=e2837da9c2) | Oct 09, 2021 |
| ASRock        | 970 Pro3 R2.0               | [4d11543637](https://linux-hardware.org/?probe=4d11543637) | Oct 08, 2021 |
| ASUSTek       | PRIME B360M-A               | [67d172f550](https://linux-hardware.org/?probe=67d172f550) | Oct 08, 2021 |
| Huanan        | X99-TF V2.0                 | [21ead32720](https://linux-hardware.org/?probe=21ead32720) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | [555747351d](https://linux-hardware.org/?probe=555747351d) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | [5e06d3cb35](https://linux-hardware.org/?probe=5e06d3cb35) | Oct 08, 2021 |
| MSI           | B450M MORTAR MAX            | [0107e8fc03](https://linux-hardware.org/?probe=0107e8fc03) | Oct 07, 2021 |
| HP            | 1998                        | [1a06c2831b](https://linux-hardware.org/?probe=1a06c2831b) | Oct 07, 2021 |
| HP            | 1998                        | [415a7084a2](https://linux-hardware.org/?probe=415a7084a2) | Oct 07, 2021 |
| HP            | 1998                        | [639a06485d](https://linux-hardware.org/?probe=639a06485d) | Oct 07, 2021 |
| HP            | 1998                        | [152a505ffd](https://linux-hardware.org/?probe=152a505ffd) | Oct 07, 2021 |
| Gigabyte      | H61M-S2PV                   | [727cc6a560](https://linux-hardware.org/?probe=727cc6a560) | Oct 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [c52721cde5](https://linux-hardware.org/?probe=c52721cde5) | Oct 06, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [9b3de686b0](https://linux-hardware.org/?probe=9b3de686b0) | Oct 06, 2021 |
| ASUSTek       | P5Q-PRO                     | [478bb5a390](https://linux-hardware.org/?probe=478bb5a390) | Oct 06, 2021 |
| ASRock        | AM1B-ITX                    | [417050a11e](https://linux-hardware.org/?probe=417050a11e) | Oct 06, 2021 |
| ASUSTek       | H110M-D                     | [bdeb7627e2](https://linux-hardware.org/?probe=bdeb7627e2) | Oct 06, 2021 |
| MSI           | Z370M MORTAR                | [a219714b0e](https://linux-hardware.org/?probe=a219714b0e) | Oct 06, 2021 |
| Huanan        | X79 249PC V2.2              | [bf8ddbe5b9](https://linux-hardware.org/?probe=bf8ddbe5b9) | Oct 05, 2021 |
| HP            | 8591                        | [2de119b3d7](https://linux-hardware.org/?probe=2de119b3d7) | Oct 05, 2021 |
| ASUSTek       | PRIME B550M-A               | [a0cb73900a](https://linux-hardware.org/?probe=a0cb73900a) | Oct 03, 2021 |
| ASUSTek       | P8Z77-V                     | [dc7b02f0b8](https://linux-hardware.org/?probe=dc7b02f0b8) | Oct 02, 2021 |
| ASRock        | FM2A88X+ Killer             | [689bc2e25f](https://linux-hardware.org/?probe=689bc2e25f) | Oct 01, 2021 |
| ASRock        | 970 Pro3 R2.0               | [b8751ff1d3](https://linux-hardware.org/?probe=b8751ff1d3) | Sep 30, 2021 |
| HP            | 8591                        | [16548ed5fc](https://linux-hardware.org/?probe=16548ed5fc) | Sep 30, 2021 |
| HP            | 8591                        | [187edb6508](https://linux-hardware.org/?probe=187edb6508) | Sep 30, 2021 |
| ASUSTek       | PRIME B360M-A               | [af2c7a813d](https://linux-hardware.org/?probe=af2c7a813d) | Sep 30, 2021 |
| ASUSTek       | PRIME B360M-A               | [e17f08bb61](https://linux-hardware.org/?probe=e17f08bb61) | Sep 30, 2021 |
| Gigabyte      | GA-880GM-D2H                | [574c5e2762](https://linux-hardware.org/?probe=574c5e2762) | Sep 29, 2021 |
| Gigabyte      | H81M-S2H                    | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [6a78ea4dea](https://linux-hardware.org/?probe=6a78ea4dea) | Sep 26, 2021 |
| HP            | 3397                        | [f71571386a](https://linux-hardware.org/?probe=f71571386a) | Sep 26, 2021 |
| Gigabyte      | H81M-S2H                    | [4199c35f38](https://linux-hardware.org/?probe=4199c35f38) | Sep 25, 2021 |
| Gigabyte      | Z97P-D3                     | [6de73ade49](https://linux-hardware.org/?probe=6de73ade49) | Sep 24, 2021 |
| Gigabyte      | Z97P-D3                     | [d58e52fede](https://linux-hardware.org/?probe=d58e52fede) | Sep 24, 2021 |
| ASUSTek       | P8H77-V LE                  | [76445d703b](https://linux-hardware.org/?probe=76445d703b) | Sep 24, 2021 |
| ASRock        | AM1B-ITX                    | [5ffe158a0b](https://linux-hardware.org/?probe=5ffe158a0b) | Sep 24, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | [1f72eef31e](https://linux-hardware.org/?probe=1f72eef31e) | Sep 23, 2021 |
| Acer          | EG43M                       | [e355190768](https://linux-hardware.org/?probe=e355190768) | Sep 23, 2021 |
| Acer          | EG43M                       | [e9e005a181](https://linux-hardware.org/?probe=e9e005a181) | Sep 23, 2021 |
| Gigabyte      | H410M S2H V2                | [970a619e86](https://linux-hardware.org/?probe=970a619e86) | Sep 23, 2021 |
| ASUSTek       | P8H61-M LX                  | [4a9e9c89f2](https://linux-hardware.org/?probe=4a9e9c89f2) | Sep 23, 2021 |
| Intel         | X79 V1.x                    | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Gigabyte      | Z77-D3H                     | [fd1153a7da](https://linux-hardware.org/?probe=fd1153a7da) | Sep 22, 2021 |
| HP            | 8298                        | [5517c4780d](https://linux-hardware.org/?probe=5517c4780d) | Sep 22, 2021 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [8e5c6eb374](https://linux-hardware.org/?probe=8e5c6eb374) | Sep 21, 2021 |
| MSI           | B450M BAZOOKA               | [952645ef00](https://linux-hardware.org/?probe=952645ef00) | Sep 21, 2021 |
| MSI           | B450M BAZOOKA               | [0916d4b546](https://linux-hardware.org/?probe=0916d4b546) | Sep 20, 2021 |
| MSI           | H81M-E33                    | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| Gigabyte      | H310M S2H x.x               | [d8df9a881c](https://linux-hardware.org/?probe=d8df9a881c) | Sep 20, 2021 |
| MSI           | MS-7255                     | [4cdaa67db9](https://linux-hardware.org/?probe=4cdaa67db9) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1d86899e9a](https://linux-hardware.org/?probe=1d86899e9a) | Sep 19, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [b9c711e311](https://linux-hardware.org/?probe=b9c711e311) | Sep 19, 2021 |
| ASUSTek       | H81M-PLUS                   | [7a0ce4b17e](https://linux-hardware.org/?probe=7a0ce4b17e) | Sep 19, 2021 |
| Gigabyte      | H110M-S2H-CF                | [bf9f9e3bb5](https://linux-hardware.org/?probe=bf9f9e3bb5) | Sep 18, 2021 |
| Gigabyte      | H61M-DS2                    | [3fde672bb3](https://linux-hardware.org/?probe=3fde672bb3) | Sep 17, 2021 |
| Gigabyte      | H61M-DS2                    | [77f32a8e42](https://linux-hardware.org/?probe=77f32a8e42) | Sep 17, 2021 |
| MSI           | Z370 PC PRO                 | [c79178e6db](https://linux-hardware.org/?probe=c79178e6db) | Sep 17, 2021 |
| ASUSTek       | P5QL PRO                    | [1630756269](https://linux-hardware.org/?probe=1630756269) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | [d1a7e38fc8](https://linux-hardware.org/?probe=d1a7e38fc8) | Sep 16, 2021 |
| ASRock        | AM1B-ITX                    | [b15ebc1577](https://linux-hardware.org/?probe=b15ebc1577) | Sep 13, 2021 |
| ASUSTek       | TUF Z270 MARK 2             | [01f321a58c](https://linux-hardware.org/?probe=01f321a58c) | Sep 12, 2021 |
| eMachines     | EL1352                      | [f9df6297b5](https://linux-hardware.org/?probe=f9df6297b5) | Sep 12, 2021 |
| Dell          | 0HR330                      | [f8542f97a0](https://linux-hardware.org/?probe=f8542f97a0) | Sep 12, 2021 |
| Acer          | Veriton M4630G V:1.0        | [1fb7ebe327](https://linux-hardware.org/?probe=1fb7ebe327) | Sep 11, 2021 |
| Gigabyte      | X99-Gaming 5                | [0a8ee7324e](https://linux-hardware.org/?probe=0a8ee7324e) | Sep 09, 2021 |
| HP            | 8767 A                      | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| Gigabyte      | H61M-DS2                    | [8bc230f7dc](https://linux-hardware.org/?probe=8bc230f7dc) | Sep 09, 2021 |
| ASUSTek       | P8H67-M PRO                 | [5027b9aa4d](https://linux-hardware.org/?probe=5027b9aa4d) | Sep 09, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | [7a0ea791be](https://linux-hardware.org/?probe=7a0ea791be) | Sep 05, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | [559710589f](https://linux-hardware.org/?probe=559710589f) | Sep 05, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [5b70c1b26c](https://linux-hardware.org/?probe=5b70c1b26c) | Sep 05, 2021 |
| ASUSTek       | P6T SE                      | [a36cb5b9cc](https://linux-hardware.org/?probe=a36cb5b9cc) | Sep 05, 2021 |
| ASUSTek       | P6T SE                      | [4cf8ae5b21](https://linux-hardware.org/?probe=4cf8ae5b21) | Sep 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | [33d31c555e](https://linux-hardware.org/?probe=33d31c555e) | Sep 02, 2021 |
| Gigabyte      | B460M DS3H V2               | [059a88a1cb](https://linux-hardware.org/?probe=059a88a1cb) | Sep 02, 2021 |
| Gigabyte      | B550M DS3H                  | [20389db1bd](https://linux-hardware.org/?probe=20389db1bd) | Aug 31, 2021 |
| ASUSTek       | PRIME B450M-A II            | [4dc49cd752](https://linux-hardware.org/?probe=4dc49cd752) | Aug 31, 2021 |
| Gigabyte      | H61M-S2PV                   | [6c149c6405](https://linux-hardware.org/?probe=6c149c6405) | Aug 31, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [3f330b3732](https://linux-hardware.org/?probe=3f330b3732) | Aug 31, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [cf52a3a23b](https://linux-hardware.org/?probe=cf52a3a23b) | Aug 31, 2021 |
| MSI           | Z370 PC PRO                 | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [82512abddc](https://linux-hardware.org/?probe=82512abddc) | Aug 29, 2021 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [63fd0a0315](https://linux-hardware.org/?probe=63fd0a0315) | Aug 28, 2021 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [eab6d15d14](https://linux-hardware.org/?probe=eab6d15d14) | Aug 28, 2021 |
| ASRock        | Z77 Pro4                    | [cc1377cf42](https://linux-hardware.org/?probe=cc1377cf42) | Aug 27, 2021 |
| ASRock        | Z77 Pro4                    | [001d1efaee](https://linux-hardware.org/?probe=001d1efaee) | Aug 27, 2021 |
| ASUSTek       | P6T                         | [ad049817af](https://linux-hardware.org/?probe=ad049817af) | Aug 27, 2021 |
| Gigabyte      | P55M-UD2                    | [4701939630](https://linux-hardware.org/?probe=4701939630) | Aug 26, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [3fc8777375](https://linux-hardware.org/?probe=3fc8777375) | Aug 25, 2021 |
| HP            | ProLiant MicroServer        | [a00a7e57b9](https://linux-hardware.org/?probe=a00a7e57b9) | Aug 25, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [50d556cacb](https://linux-hardware.org/?probe=50d556cacb) | Aug 24, 2021 |
| Gigabyte      | Z77X-D3H                    | [a48e5130e8](https://linux-hardware.org/?probe=a48e5130e8) | Aug 23, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [079af91b8f](https://linux-hardware.org/?probe=079af91b8f) | Aug 22, 2021 |
| Gigabyte      | Z170-HD3P-CF                | [8d7072a03f](https://linux-hardware.org/?probe=8d7072a03f) | Aug 22, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [c6fe94a0ba](https://linux-hardware.org/?probe=c6fe94a0ba) | Aug 22, 2021 |
| HP            | 1632                        | [52a448c332](https://linux-hardware.org/?probe=52a448c332) | Aug 22, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [eea45758b7](https://linux-hardware.org/?probe=eea45758b7) | Aug 22, 2021 |
| ASUSTek       | Z77-A                       | [971dc3b5c7](https://linux-hardware.org/?probe=971dc3b5c7) | Aug 21, 2021 |
| ASUSTek       | VM62                        | [9452e7da05](https://linux-hardware.org/?probe=9452e7da05) | Aug 21, 2021 |
| ASUSTek       | A_F_K31DA_K31DAG_K20DA      | [3106355282](https://linux-hardware.org/?probe=3106355282) | Aug 21, 2021 |
| ASUSTek       | PRIME Z590-A                | [e09e01306a](https://linux-hardware.org/?probe=e09e01306a) | Aug 21, 2021 |
| ASUSTek       | P6T                         | [d0495a4765](https://linux-hardware.org/?probe=d0495a4765) | Aug 20, 2021 |
| ASUSTek       | P5G41T-M LX                 | [af1cafb6f6](https://linux-hardware.org/?probe=af1cafb6f6) | Aug 20, 2021 |
| BESSTAR Te... | HM80                        | [60fdee03d6](https://linux-hardware.org/?probe=60fdee03d6) | Aug 19, 2021 |
| MSI           | B450M PRO-M2 MAX            | [cc54b8955c](https://linux-hardware.org/?probe=cc54b8955c) | Aug 19, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1e86163e8a](https://linux-hardware.org/?probe=1e86163e8a) | Aug 18, 2021 |
| Gigabyte      | B560M DS3H                  | [6972f0e79d](https://linux-hardware.org/?probe=6972f0e79d) | Aug 18, 2021 |
| Gigabyte      | Z97N-WIFI                   | [be9383850e](https://linux-hardware.org/?probe=be9383850e) | Aug 17, 2021 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [5c193ba046](https://linux-hardware.org/?probe=5c193ba046) | Aug 17, 2021 |
| Gigabyte      | B550M DS3H                  | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| MSI           | X99S SLI PLUS               | [7852429b64](https://linux-hardware.org/?probe=7852429b64) | Aug 14, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5e9853124d](https://linux-hardware.org/?probe=5e9853124d) | Aug 13, 2021 |
| HP            | 0AA8h                       | [16e8384171](https://linux-hardware.org/?probe=16e8384171) | Aug 13, 2021 |
| MSI           | X99S SLI PLUS               | [cef0cfe1de](https://linux-hardware.org/?probe=cef0cfe1de) | Aug 13, 2021 |
| MSI           | B450M PRO-VDH MAX           | [867615567d](https://linux-hardware.org/?probe=867615567d) | Aug 12, 2021 |
| MSI           | B450M PRO-VDH MAX           | [d5b4c3a310](https://linux-hardware.org/?probe=d5b4c3a310) | Aug 12, 2021 |
| Intel         | D525MW AAE93082-301         | [fc72f0a0ea](https://linux-hardware.org/?probe=fc72f0a0ea) | Aug 11, 2021 |
| Packard Be... | TBGM01                      | [c1a57810e8](https://linux-hardware.org/?probe=c1a57810e8) | Aug 11, 2021 |
| ASRockRack    | X470D4U2/1N1                | [b037023625](https://linux-hardware.org/?probe=b037023625) | Aug 11, 2021 |
| Gigabyte      | GA-990FXA-D3                | [c59dc746e2](https://linux-hardware.org/?probe=c59dc746e2) | Aug 11, 2021 |
| Gigabyte      | B450 AORUS M                | [2de3749bcf](https://linux-hardware.org/?probe=2de3749bcf) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | M5A88-V EVO                 | [66d74f8e04](https://linux-hardware.org/?probe=66d74f8e04) | Aug 09, 2021 |
| Gigabyte      | Z370M D3H-CF                | [ce1da3d925](https://linux-hardware.org/?probe=ce1da3d925) | Aug 09, 2021 |
| ASRock        | 970A-G                      | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Dell          | 0CRH6C A01                  | [fc51c84d7a](https://linux-hardware.org/?probe=fc51c84d7a) | Aug 08, 2021 |
| HP            | 8591                        | [0f34dfc82c](https://linux-hardware.org/?probe=0f34dfc82c) | Aug 06, 2021 |
| Gigabyte      | AX370-Gaming K5-CF          | [d08d8c22f3](https://linux-hardware.org/?probe=d08d8c22f3) | Aug 06, 2021 |
| ASRock        | G41C-GS                     | [d2dfd47189](https://linux-hardware.org/?probe=d2dfd47189) | Aug 06, 2021 |
| Toshiba       | Mobile Intel 4 Series/IC... | [3f16c8f90a](https://linux-hardware.org/?probe=3f16c8f90a) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | [16b2e8c32f](https://linux-hardware.org/?probe=16b2e8c32f) | Aug 06, 2021 |
| Gigabyte      | H81M-S2V                    | [db8fadad17](https://linux-hardware.org/?probe=db8fadad17) | Aug 06, 2021 |
| ASRock        | G41C-GS                     | [a386a767da](https://linux-hardware.org/?probe=a386a767da) | Aug 04, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [f776a4eb93](https://linux-hardware.org/?probe=f776a4eb93) | Aug 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [2637dbf19f](https://linux-hardware.org/?probe=2637dbf19f) | Aug 02, 2021 |
| HP            | 0A54h                       | [fcf5100c59](https://linux-hardware.org/?probe=fcf5100c59) | Aug 01, 2021 |
| MSI           | B450 GAMING PLUS            | [81d89f3a1b](https://linux-hardware.org/?probe=81d89f3a1b) | Aug 01, 2021 |
| ASUSTek       | P5KPL/1600                  | [7880e45d12](https://linux-hardware.org/?probe=7880e45d12) | Jul 31, 2021 |
| HP            | 8169                        | [52b2e59c3e](https://linux-hardware.org/?probe=52b2e59c3e) | Jul 30, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1cf978f1d9](https://linux-hardware.org/?probe=1cf978f1d9) | Jul 30, 2021 |
| ASUSTek       | H81M-P PLUS                 | [cbbefc77ab](https://linux-hardware.org/?probe=cbbefc77ab) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3f0188a6fd](https://linux-hardware.org/?probe=3f0188a6fd) | Jul 28, 2021 |
| ASUSTek       | P8P67                       | [e2d18f1baf](https://linux-hardware.org/?probe=e2d18f1baf) | Jul 28, 2021 |
| ASUSTek       | PRIME Z490-P                | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [6df63b2eac](https://linux-hardware.org/?probe=6df63b2eac) | Jul 27, 2021 |
| Acer          | Aspire XC-705               | [381ff0cfb4](https://linux-hardware.org/?probe=381ff0cfb4) | Jul 26, 2021 |
| Huanan        | X99-TF V2.0                 | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| MSI           | MAG B365M MORTAR            | [19835b0c7f](https://linux-hardware.org/?probe=19835b0c7f) | Jul 26, 2021 |
| MSI           | X570-A PRO                  | [db168e8daa](https://linux-hardware.org/?probe=db168e8daa) | Jul 26, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [4b871929e2](https://linux-hardware.org/?probe=4b871929e2) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| ASUSTek       | Rampage III Extreme         | [f637e33171](https://linux-hardware.org/?probe=f637e33171) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [637cd40ba1](https://linux-hardware.org/?probe=637cd40ba1) | Jul 25, 2021 |
| Medion        | BTDD-LT                     | [11a52f4d52](https://linux-hardware.org/?probe=11a52f4d52) | Jul 24, 2021 |
| MSI           | H110M PRO-VH                | [42bd7fe7d2](https://linux-hardware.org/?probe=42bd7fe7d2) | Jul 23, 2021 |
| Gigabyte      | C1037UN-EU                  | [7dd534813a](https://linux-hardware.org/?probe=7dd534813a) | Jul 22, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [be19556b36](https://linux-hardware.org/?probe=be19556b36) | Jul 20, 2021 |
| HP            | 82F2                        | [bc055927ac](https://linux-hardware.org/?probe=bc055927ac) | Jul 20, 2021 |
| Gigabyte      | H61M-DS2                    | [a6a70ffe29](https://linux-hardware.org/?probe=a6a70ffe29) | Jul 20, 2021 |
| ASUSTek       | B75M-A                      | [ff50f031ed](https://linux-hardware.org/?probe=ff50f031ed) | Jul 20, 2021 |
| ASRock        | H170M Pro4                  | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| MSI           | H61M-E33                    | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| Gigabyte      | B450M S2H                   | [42e923e90f](https://linux-hardware.org/?probe=42e923e90f) | Jul 16, 2021 |
| Dell          | 0YXT71 A01                  | [0237c6287f](https://linux-hardware.org/?probe=0237c6287f) | Jul 16, 2021 |
| Gigabyte      | H410M S2H                   | [d246232e26](https://linux-hardware.org/?probe=d246232e26) | Jul 16, 2021 |
| MSI           | H110M PRO-VH                | [c91d217ad5](https://linux-hardware.org/?probe=c91d217ad5) | Jul 16, 2021 |
| Minix         | NEO Z83-4 V1.1              | [836aaa1936](https://linux-hardware.org/?probe=836aaa1936) | Jul 16, 2021 |
| Gigabyte      | H410M S2H                   | [7ab815b4ae](https://linux-hardware.org/?probe=7ab815b4ae) | Jul 15, 2021 |
| ASRock        | A75M-HVS                    | [95cf5b47dc](https://linux-hardware.org/?probe=95cf5b47dc) | Jul 14, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Gigabyte      | B450M S2H                   | [643e83a867](https://linux-hardware.org/?probe=643e83a867) | Jul 13, 2021 |
| ASUSTek       | P5K SE/EPU                  | [0ea653f30f](https://linux-hardware.org/?probe=0ea653f30f) | Jul 12, 2021 |
| Dell          | 0KWVT8 A02                  | [b0ed7c660f](https://linux-hardware.org/?probe=b0ed7c660f) | Jul 12, 2021 |
| Gigabyte      | H110M-S2H-CF                | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Gigabyte      | H81M-HD3                    | [2664517a1e](https://linux-hardware.org/?probe=2664517a1e) | Jul 12, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [22edc6b8cf](https://linux-hardware.org/?probe=22edc6b8cf) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7325e088ed](https://linux-hardware.org/?probe=7325e088ed) | Jul 10, 2021 |
| Unknown       | TB-4000                     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| MSI           | B560M PRO-VDH               | [472f5ec6b6](https://linux-hardware.org/?probe=472f5ec6b6) | Jul 09, 2021 |
| MSI           | H110M PRO-VH                | [39bbc7b6a9](https://linux-hardware.org/?probe=39bbc7b6a9) | Jul 09, 2021 |
| Huanan        | X79 249PC V2.2              | [82d15f27b4](https://linux-hardware.org/?probe=82d15f27b4) | Jul 09, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9736c8f382](https://linux-hardware.org/?probe=9736c8f382) | Jul 09, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [413c28caa0](https://linux-hardware.org/?probe=413c28caa0) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| ASUSTek       | P7H55                       | [75486a344e](https://linux-hardware.org/?probe=75486a344e) | Jul 08, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | [3db1fed912](https://linux-hardware.org/?probe=3db1fed912) | Jul 07, 2021 |
| Gigabyte      | H81M-S1                     | [4b2c3ea073](https://linux-hardware.org/?probe=4b2c3ea073) | Jul 07, 2021 |
| Gigabyte      | Z77-DS3H                    | [d87f176b36](https://linux-hardware.org/?probe=d87f176b36) | Jul 07, 2021 |
| MSI           | B560M PRO-VDH               | [3cf2658ea3](https://linux-hardware.org/?probe=3cf2658ea3) | Jul 04, 2021 |
| ASUSTek       | Z87-WS                      | [d4c7df753a](https://linux-hardware.org/?probe=d4c7df753a) | Jul 03, 2021 |
| ASRock        | H77 Pro4-M                  | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| ASUSTek       | PRIME Z590-A                | [3884e9d433](https://linux-hardware.org/?probe=3884e9d433) | Jul 02, 2021 |
| HP            | 870C                        | [4a9cc5327e](https://linux-hardware.org/?probe=4a9cc5327e) | Jul 02, 2021 |
| ASUSTek       | M4N78-AM V2                 | [b756564b9b](https://linux-hardware.org/?probe=b756564b9b) | Jul 02, 2021 |
| Gigabyte      | H81M-S2H                    | [edb2d76943](https://linux-hardware.org/?probe=edb2d76943) | Jul 01, 2021 |
| MSI           | B560M PRO-VDH               | [fb97d82a6b](https://linux-hardware.org/?probe=fb97d82a6b) | Jul 01, 2021 |
| MSI           | Z370 PC PRO                 | [59f059212b](https://linux-hardware.org/?probe=59f059212b) | Jun 30, 2021 |
| Acer          | Aspire TC-605               | [7226605ad3](https://linux-hardware.org/?probe=7226605ad3) | Jun 29, 2021 |
| ASUSTek       | P8Z77-V LK                  | [e92157b364](https://linux-hardware.org/?probe=e92157b364) | Jun 28, 2021 |
| Dell          | 0D883F A06                  | [f30832ff03](https://linux-hardware.org/?probe=f30832ff03) | Jun 27, 2021 |
| HP            | 339A                        | [76e58fd311](https://linux-hardware.org/?probe=76e58fd311) | Jun 27, 2021 |
| Gigabyte      | B85M-HD3                    | [995760c11e](https://linux-hardware.org/?probe=995760c11e) | Jun 27, 2021 |
| ASUSTek       | H110M-A/M.2                 | [fd2d0c3aea](https://linux-hardware.org/?probe=fd2d0c3aea) | Jun 25, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | [dab6b0d848](https://linux-hardware.org/?probe=dab6b0d848) | Jun 25, 2021 |
| Gigabyte      | H61M-S2PV                   | [3da8487d5f](https://linux-hardware.org/?probe=3da8487d5f) | Jun 24, 2021 |
| ECS           | H81H3-I                     | [afe36a7b94](https://linux-hardware.org/?probe=afe36a7b94) | Jun 24, 2021 |
| MSI           | B560M PRO-VDH               | [da4c434f55](https://linux-hardware.org/?probe=da4c434f55) | Jun 23, 2021 |
| Lenovo        | ThinkCentre M70e 0830WK7    | [ef51073699](https://linux-hardware.org/?probe=ef51073699) | Jun 22, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d1fe43704d](https://linux-hardware.org/?probe=d1fe43704d) | Jun 22, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [327ce56b50](https://linux-hardware.org/?probe=327ce56b50) | Jun 21, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [258484542f](https://linux-hardware.org/?probe=258484542f) | Jun 21, 2021 |
| Gigabyte      | GA-MA770-DS3                | [484afd8389](https://linux-hardware.org/?probe=484afd8389) | Jun 21, 2021 |
| MSI           | B450M-A PRO MAX             | [85e3582f5f](https://linux-hardware.org/?probe=85e3582f5f) | Jun 19, 2021 |
| Dell          | 0D6H9T A01                  | [1efd9c946f](https://linux-hardware.org/?probe=1efd9c946f) | Jun 18, 2021 |
| HP            | 1495                        | [56251d62e1](https://linux-hardware.org/?probe=56251d62e1) | Jun 17, 2021 |
| ASUSTek       | P5GC-MX/1333                | [c7b83ec204](https://linux-hardware.org/?probe=c7b83ec204) | Jun 16, 2021 |
| ASUSTek       | P5GC-MX/1333                | [c299d91435](https://linux-hardware.org/?probe=c299d91435) | Jun 16, 2021 |
| Gigabyte      | MCMLUAB-00                  | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Gigabyte      | B85-HD3                     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| Intel         | DH55TC AAE70932-303         | [7a2f11778d](https://linux-hardware.org/?probe=7a2f11778d) | Jun 13, 2021 |
| ASRock        | B550 Steel Legend           | [9a3e7a73b3](https://linux-hardware.org/?probe=9a3e7a73b3) | Jun 12, 2021 |
| MSI           | B350 GAMING PLUS            | [0ce81f40cc](https://linux-hardware.org/?probe=0ce81f40cc) | Jun 12, 2021 |
| ASRock        | G41M-VS                     | [e91c542ed4](https://linux-hardware.org/?probe=e91c542ed4) | Jun 11, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [5aee9258a6](https://linux-hardware.org/?probe=5aee9258a6) | Jun 10, 2021 |
| ASUSTek       | P5B-Deluxe                  | [1454659388](https://linux-hardware.org/?probe=1454659388) | Jun 09, 2021 |
| Gigabyte      | M61PME-S2P                  | [8cf8f509bf](https://linux-hardware.org/?probe=8cf8f509bf) | Jun 08, 2021 |
| Gigabyte      | EG41MF-US2H                 | [7869ca1fc6](https://linux-hardware.org/?probe=7869ca1fc6) | Jun 07, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [f98947be5f](https://linux-hardware.org/?probe=f98947be5f) | Jun 05, 2021 |
| Gigabyte      | Z490 AORUS ELITE AC         | [cceeae278f](https://linux-hardware.org/?probe=cceeae278f) | Jun 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE AC         | [efe6970f14](https://linux-hardware.org/?probe=efe6970f14) | Jun 04, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1c0016dc30](https://linux-hardware.org/?probe=1c0016dc30) | Jun 03, 2021 |
| ASUSTek       | P5G41C-M LX                 | [da186487c6](https://linux-hardware.org/?probe=da186487c6) | Jun 03, 2021 |
| Gigabyte      | B450M DS3H-CF               | [dabfe9f136](https://linux-hardware.org/?probe=dabfe9f136) | Jun 02, 2021 |
| ASUSTek       | Q370I-IM-A R2.0             | [52ae050592](https://linux-hardware.org/?probe=52ae050592) | Jun 02, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [1a7c5aee0e](https://linux-hardware.org/?probe=1a7c5aee0e) | Jun 02, 2021 |
| Unknown       | Intel X79                   | [6853a4cb43](https://linux-hardware.org/?probe=6853a4cb43) | Jun 01, 2021 |
| MSI           | B450M BAZOOKA V2            | [3056db282e](https://linux-hardware.org/?probe=3056db282e) | May 31, 2021 |
| Essentiel ... | SmartMOUV series            | [8ae91d28e1](https://linux-hardware.org/?probe=8ae91d28e1) | May 30, 2021 |
| Dell          | 0HX555                      | [962e0b75e4](https://linux-hardware.org/?probe=962e0b75e4) | May 29, 2021 |
| Gigabyte      | X79-UP4                     | [88dd86fbbc](https://linux-hardware.org/?probe=88dd86fbbc) | May 28, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [2696477c0c](https://linux-hardware.org/?probe=2696477c0c) | May 27, 2021 |
| ASUSTek       | P4S800-MX SE                | [7a323363ef](https://linux-hardware.org/?probe=7a323363ef) | May 27, 2021 |
| ASUSTek       | P8Z77-V                     | [6f05aea2c1](https://linux-hardware.org/?probe=6f05aea2c1) | May 26, 2021 |
| Acer          | Aspire X3950                | [722016af18](https://linux-hardware.org/?probe=722016af18) | May 26, 2021 |
| HP            | 18E7                        | [e5e458a769](https://linux-hardware.org/?probe=e5e458a769) | May 26, 2021 |
| HP            | 18E7                        | [0eec8697a8](https://linux-hardware.org/?probe=0eec8697a8) | May 26, 2021 |
| ECS           | NM70-I2                     | [3d11efa233](https://linux-hardware.org/?probe=3d11efa233) | May 26, 2021 |
| MSI           | A320M-A PRO                 | [16e788a5e7](https://linux-hardware.org/?probe=16e788a5e7) | May 26, 2021 |
| Medion        | B150H4-EM                   | [5a59d31e03](https://linux-hardware.org/?probe=5a59d31e03) | May 25, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [b0f626d0e4](https://linux-hardware.org/?probe=b0f626d0e4) | May 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | [3e5f76719a](https://linux-hardware.org/?probe=3e5f76719a) | May 24, 2021 |
| Gigabyte      | B450 AORUS M                | [33e83d70f4](https://linux-hardware.org/?probe=33e83d70f4) | May 24, 2021 |
| Huanan        | X99-F8                      | [40e64a9bd9](https://linux-hardware.org/?probe=40e64a9bd9) | May 24, 2021 |
| Foxconn       | ETON                        | [39497ce3ae](https://linux-hardware.org/?probe=39497ce3ae) | May 24, 2021 |
| Huanan        | X99-F8                      | [0158c76f85](https://linux-hardware.org/?probe=0158c76f85) | May 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | [c75f9d5c0d](https://linux-hardware.org/?probe=c75f9d5c0d) | May 23, 2021 |
| MSI           | X570-A PRO                  | [61a5d17b5b](https://linux-hardware.org/?probe=61a5d17b5b) | May 22, 2021 |
| ASUSTek       | B85M-G                      | [d271efb0c6](https://linux-hardware.org/?probe=d271efb0c6) | May 22, 2021 |
| ASUSTek       | PRIME B450M-A               | [7a2a0a49c8](https://linux-hardware.org/?probe=7a2a0a49c8) | May 22, 2021 |
| ASUSTek       | A88XM-PLUS                  | [8411c23010](https://linux-hardware.org/?probe=8411c23010) | May 22, 2021 |
| Foxconn       | 2ABF                        | [2738ca85c3](https://linux-hardware.org/?probe=2738ca85c3) | May 22, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [07f417aa1b](https://linux-hardware.org/?probe=07f417aa1b) | May 22, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [4e195b668d](https://linux-hardware.org/?probe=4e195b668d) | May 22, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [cf67f59f47](https://linux-hardware.org/?probe=cf67f59f47) | May 21, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [62e430c69c](https://linux-hardware.org/?probe=62e430c69c) | May 21, 2021 |
| ASUSTek       | PRIME B450M-A               | [c5b23dd7cc](https://linux-hardware.org/?probe=c5b23dd7cc) | May 20, 2021 |
| ASUSTek       | F2A55                       | [39cc2ef96b](https://linux-hardware.org/?probe=39cc2ef96b) | May 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [d3237e56e1](https://linux-hardware.org/?probe=d3237e56e1) | May 19, 2021 |
| MSI           | B450 TOMAHAWK               | [3480d8ee33](https://linux-hardware.org/?probe=3480d8ee33) | May 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [dd8f32a8d6](https://linux-hardware.org/?probe=dd8f32a8d6) | May 18, 2021 |
| Wistron       | ProLiant ML110 G6           | [53d1c16f77](https://linux-hardware.org/?probe=53d1c16f77) | May 18, 2021 |
| Wistron       | ProLiant ML110 G6           | [d328ce9f69](https://linux-hardware.org/?probe=d328ce9f69) | May 18, 2021 |
| ASUSTek       | H81M-K                      | [d44e900d30](https://linux-hardware.org/?probe=d44e900d30) | May 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [b07d6adc60](https://linux-hardware.org/?probe=b07d6adc60) | May 18, 2021 |
| ASUSTek       | Z77-A                       | [5569c32840](https://linux-hardware.org/?probe=5569c32840) | May 18, 2021 |
| eMachines     | EL1352                      | [f0fe18214f](https://linux-hardware.org/?probe=f0fe18214f) | May 17, 2021 |
| Gigabyte      | 945GM-S2                    | [4f4fa6d3f6](https://linux-hardware.org/?probe=4f4fa6d3f6) | May 16, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [0f367cfaa2](https://linux-hardware.org/?probe=0f367cfaa2) | May 14, 2021 |
| MSI           | B350M PRO-VDH               | [ea0445f1df](https://linux-hardware.org/?probe=ea0445f1df) | May 14, 2021 |
| Gigabyte      | H81M-S2H                    | [c10b72134d](https://linux-hardware.org/?probe=c10b72134d) | May 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [c75942cc3c](https://linux-hardware.org/?probe=c75942cc3c) | May 14, 2021 |
| ASUSTek       | Z87-WS                      | [90e90490b7](https://linux-hardware.org/?probe=90e90490b7) | May 13, 2021 |
| HP            | 1495                        | [9f708b7e14](https://linux-hardware.org/?probe=9f708b7e14) | May 12, 2021 |
| Huanan        | X99-F8 V2.0                 | [c2569c6c71](https://linux-hardware.org/?probe=c2569c6c71) | May 11, 2021 |
| ASRock        | N68C-S UCC                  | [3c0ef1dbe1](https://linux-hardware.org/?probe=3c0ef1dbe1) | May 11, 2021 |
| Shuttle       | DH310S                      | [3d30bc1c51](https://linux-hardware.org/?probe=3d30bc1c51) | May 10, 2021 |
| Gigabyte      | X58A-UD7                    | [cecf736fb7](https://linux-hardware.org/?probe=cecf736fb7) | May 10, 2021 |
| Dell          | 0PP150 A00                  | [85c12975e9](https://linux-hardware.org/?probe=85c12975e9) | May 10, 2021 |
| MSI           | B250M PRO-VDH               | [62c8feddc5](https://linux-hardware.org/?probe=62c8feddc5) | May 09, 2021 |
| ASUSTek       | Rampage III Extreme         | [00f735b5b6](https://linux-hardware.org/?probe=00f735b5b6) | May 09, 2021 |
| Gigabyte      | X570 UD                     | [44ec529423](https://linux-hardware.org/?probe=44ec529423) | May 09, 2021 |
| ASRock        | X99E-ITX/ac                 | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [0e50c08ab6](https://linux-hardware.org/?probe=0e50c08ab6) | May 08, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [af24409637](https://linux-hardware.org/?probe=af24409637) | May 07, 2021 |
| Gigabyte      | A320M-S2H-CF                | [bb6b82930e](https://linux-hardware.org/?probe=bb6b82930e) | May 07, 2021 |
| Acer          | Veriton S2660G              | [31f3a2c202](https://linux-hardware.org/?probe=31f3a2c202) | May 07, 2021 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [25108d77d7](https://linux-hardware.org/?probe=25108d77d7) | May 06, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [96478f0c82](https://linux-hardware.org/?probe=96478f0c82) | May 06, 2021 |
| Dell          | 0PP150 A00                  | [6b4e0a3965](https://linux-hardware.org/?probe=6b4e0a3965) | May 06, 2021 |
| ASUSTek       | B75M-A                      | [c2c8202896](https://linux-hardware.org/?probe=c2c8202896) | May 05, 2021 |
| ASUSTek       | PRIME Z590-A                | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | Z77X-UD5H                   | [6b108ea92f](https://linux-hardware.org/?probe=6b108ea92f) | May 04, 2021 |
| Gigabyte      | B450M S2H                   | [627e3d2a80](https://linux-hardware.org/?probe=627e3d2a80) | May 03, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [315bc839ec](https://linux-hardware.org/?probe=315bc839ec) | May 01, 2021 |
| Biostar       | TB350-BTC                   | [905cd6f7b5](https://linux-hardware.org/?probe=905cd6f7b5) | May 01, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b5701b4cf9](https://linux-hardware.org/?probe=b5701b4cf9) | Apr 30, 2021 |
| ASUSTek       | PRIME A320M-K               | [8a8f7215cc](https://linux-hardware.org/?probe=8a8f7215cc) | Apr 30, 2021 |
| Gigabyte      | Z77-D3H                     | [b65d1305a4](https://linux-hardware.org/?probe=b65d1305a4) | Apr 29, 2021 |
| Biostar       | TB350-BTC                   | [69ac177ac7](https://linux-hardware.org/?probe=69ac177ac7) | Apr 29, 2021 |
| Gigabyte      | B75M-HD3                    | [a282ebebe6](https://linux-hardware.org/?probe=a282ebebe6) | Apr 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [84be0d6978](https://linux-hardware.org/?probe=84be0d6978) | Apr 27, 2021 |
| MSI           | MEG X570 UNIFY              | [ff1723016b](https://linux-hardware.org/?probe=ff1723016b) | Apr 27, 2021 |
| HP            | 18E6                        | [cf3ed91b8a](https://linux-hardware.org/?probe=cf3ed91b8a) | Apr 27, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [731d132b14](https://linux-hardware.org/?probe=731d132b14) | Apr 26, 2021 |
| ASUSTek       | M2N-E SLI                   | [ff54330a37](https://linux-hardware.org/?probe=ff54330a37) | Apr 26, 2021 |
| Gigabyte      | C1037UN-EU                  | [7fc828532c](https://linux-hardware.org/?probe=7fc828532c) | Apr 26, 2021 |
| HP            | 18E6                        | [40054e3921](https://linux-hardware.org/?probe=40054e3921) | Apr 26, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [aa1913f348](https://linux-hardware.org/?probe=aa1913f348) | Apr 25, 2021 |
| eMachines     | EL1352                      | [7a84e3e1c5](https://linux-hardware.org/?probe=7a84e3e1c5) | Apr 25, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [6dc9bcb3f7](https://linux-hardware.org/?probe=6dc9bcb3f7) | Apr 24, 2021 |
| Medion        | H110H4-CM2                  | [d02f65c757](https://linux-hardware.org/?probe=d02f65c757) | Apr 24, 2021 |
| Medion        | H110H4-CM2                  | [fef3d45e82](https://linux-hardware.org/?probe=fef3d45e82) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [a63e8e0aeb](https://linux-hardware.org/?probe=a63e8e0aeb) | Apr 23, 2021 |
| Huanan        | X99-8M-F V1.1               | [7245a78f49](https://linux-hardware.org/?probe=7245a78f49) | Apr 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5e5d0f3f5c](https://linux-hardware.org/?probe=5e5d0f3f5c) | Apr 23, 2021 |
| ASUSTek       | AT5NM10T-I                  | [00d6759b8d](https://linux-hardware.org/?probe=00d6759b8d) | Apr 23, 2021 |
| Pegatron      | Benicia                     | [517b7af416](https://linux-hardware.org/?probe=517b7af416) | Apr 22, 2021 |
| Huanan        | X99-8M-F V1.1               | [0fa6e09503](https://linux-hardware.org/?probe=0fa6e09503) | Apr 22, 2021 |
| Huanan        | X99-8M-F V1.1               | [59f345bf53](https://linux-hardware.org/?probe=59f345bf53) | Apr 22, 2021 |
| Gigabyte      | H81M-D3H                    | [e1a24cae13](https://linux-hardware.org/?probe=e1a24cae13) | Apr 21, 2021 |
| Gigabyte      | H81M-D3H                    | [cc4a1ac304](https://linux-hardware.org/?probe=cc4a1ac304) | Apr 20, 2021 |
| ASRock        | 990FX Killer                | [09c80fda6c](https://linux-hardware.org/?probe=09c80fda6c) | Apr 19, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c4db602b8f](https://linux-hardware.org/?probe=c4db602b8f) | Apr 19, 2021 |
| ASUSTek       | F2A55                       | [cb6cd15542](https://linux-hardware.org/?probe=cb6cd15542) | Apr 19, 2021 |
| MSI           | H310M PRO-VD PLUS           | [67f23ccd98](https://linux-hardware.org/?probe=67f23ccd98) | Apr 18, 2021 |
| Intel         | DH55TC AAE70932-303         | [fe6ae769bc](https://linux-hardware.org/?probe=fe6ae769bc) | Apr 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [0db8148a33](https://linux-hardware.org/?probe=0db8148a33) | Apr 17, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5bc34889b8](https://linux-hardware.org/?probe=5bc34889b8) | Apr 17, 2021 |
| HP            | ML110 G4                    | [443a299302](https://linux-hardware.org/?probe=443a299302) | Apr 17, 2021 |
| Gigabyte      | AX370-Gaming K5-CF          | [343d4bab96](https://linux-hardware.org/?probe=343d4bab96) | Apr 16, 2021 |
| Gigabyte      | EG41MF-US2H                 | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Gigabyte      | H110M-DS2-CF                | [a96e1ef344](https://linux-hardware.org/?probe=a96e1ef344) | Apr 16, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [06ee276b08](https://linux-hardware.org/?probe=06ee276b08) | Apr 15, 2021 |
| Huanan        | X99-8M-F V1.1               | [83b1c7aa85](https://linux-hardware.org/?probe=83b1c7aa85) | Apr 14, 2021 |
| Dell          | 0N4YC8 A00                  | [adc6b44f76](https://linux-hardware.org/?probe=adc6b44f76) | Apr 14, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [54f1bb3faf](https://linux-hardware.org/?probe=54f1bb3faf) | Apr 13, 2021 |
| ASRock        | H81 Pro BTC R2.0            | [5b6f306c4c](https://linux-hardware.org/?probe=5b6f306c4c) | Apr 13, 2021 |
| ASUSTek       | PRIME B350M-A               | [c6360f8f30](https://linux-hardware.org/?probe=c6360f8f30) | Apr 12, 2021 |
| Dell          | 0VD5HY A07                  | [28dda9b894](https://linux-hardware.org/?probe=28dda9b894) | Apr 12, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [af4b00f5c3](https://linux-hardware.org/?probe=af4b00f5c3) | Apr 12, 2021 |
| MSI           | B150M BAZOOKA               | [4130d9a755](https://linux-hardware.org/?probe=4130d9a755) | Apr 10, 2021 |
| MSI           | IONA                        | [f0a9790c3f](https://linux-hardware.org/?probe=f0a9790c3f) | Apr 10, 2021 |
| Gigabyte      | Z77-D3H                     | [c53d548b79](https://linux-hardware.org/?probe=c53d548b79) | Apr 10, 2021 |
| Gigabyte      | Z77-D3H                     | [09aaa87674](https://linux-hardware.org/?probe=09aaa87674) | Apr 09, 2021 |
| Dell          | 0VRWRC A00                  | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| Huanan        | X99-8M-F V1.1               | [c385824b8a](https://linux-hardware.org/?probe=c385824b8a) | Apr 09, 2021 |
| Huanan        | X99-8M-F V1.1               | [3be55c22f7](https://linux-hardware.org/?probe=3be55c22f7) | Apr 09, 2021 |
| MSI           | Z370 TOMAHAWK               | [00cd4878a3](https://linux-hardware.org/?probe=00cd4878a3) | Apr 08, 2021 |
| Dell          | 0KP561                      | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [7ba5753e40](https://linux-hardware.org/?probe=7ba5753e40) | Apr 08, 2021 |
| Gigabyte      | B75M-HD3                    | [ce5b8f7175](https://linux-hardware.org/?probe=ce5b8f7175) | Apr 08, 2021 |
| ASUSTek       | M3N78-EMH HDMI              | [89a28ead17](https://linux-hardware.org/?probe=89a28ead17) | Apr 07, 2021 |
| MSI           | H110M ECO                   | [83c7dd7f43](https://linux-hardware.org/?probe=83c7dd7f43) | Apr 07, 2021 |
| Gigabyte      | M68MT-S2                    | [77bc487f86](https://linux-hardware.org/?probe=77bc487f86) | Apr 07, 2021 |
| Dell          | 09M8Y8 A01                  | [240dd467a0](https://linux-hardware.org/?probe=240dd467a0) | Apr 07, 2021 |
| MSI           | H170M PRO-VDH               | [5e5fc38226](https://linux-hardware.org/?probe=5e5fc38226) | Apr 07, 2021 |
| MSI           | H170M PRO-VDH               | [917e8c0220](https://linux-hardware.org/?probe=917e8c0220) | Apr 07, 2021 |
| Lenovo        | 36EB NOK                    | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| Medion        | Z370H4-EM                   | [34b723fd44](https://linux-hardware.org/?probe=34b723fd44) | Apr 06, 2021 |
| MSI           | B450M PRO-M2                | [3afef09762](https://linux-hardware.org/?probe=3afef09762) | Apr 06, 2021 |
| Gigabyte      | G41M-ES2L                   | [53a7580233](https://linux-hardware.org/?probe=53a7580233) | Apr 06, 2021 |
| Gigabyte      | P55M-UD2                    | [6160e81f43](https://linux-hardware.org/?probe=6160e81f43) | Apr 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [eaf53b1766](https://linux-hardware.org/?probe=eaf53b1766) | Apr 06, 2021 |
| Gigabyte      | B85M-HD3                    | [830633eff6](https://linux-hardware.org/?probe=830633eff6) | Apr 05, 2021 |
| Gigabyte      | B85M-HD3                    | [332a730e31](https://linux-hardware.org/?probe=332a730e31) | Apr 05, 2021 |
| Medion        | H110H4-CM2                  | [54a13fac4a](https://linux-hardware.org/?probe=54a13fac4a) | Apr 03, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [9b055bd98d](https://linux-hardware.org/?probe=9b055bd98d) | Apr 03, 2021 |
| ASUSTek       | M2V                         | [9b7d8bd5ff](https://linux-hardware.org/?probe=9b7d8bd5ff) | Apr 03, 2021 |
| Gigabyte      | P35-DS3L                    | [21e15b665e](https://linux-hardware.org/?probe=21e15b665e) | Apr 02, 2021 |
| ASUSTek       | B75M-A                      | [6c54090cc0](https://linux-hardware.org/?probe=6c54090cc0) | Apr 02, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [3101fb0cea](https://linux-hardware.org/?probe=3101fb0cea) | Apr 02, 2021 |
| ASUSTek       | AT5NM10T-I                  | [69f5075671](https://linux-hardware.org/?probe=69f5075671) | Apr 01, 2021 |
| ASUSTek       | AT5NM10T-I                  | [ce481ced8a](https://linux-hardware.org/?probe=ce481ced8a) | Apr 01, 2021 |
| ASUSTek       | M5A78L/USB3                 | [9afaeda84f](https://linux-hardware.org/?probe=9afaeda84f) | Apr 01, 2021 |
| Dell          | 0HR330                      | [b41d37ed11](https://linux-hardware.org/?probe=b41d37ed11) | Apr 01, 2021 |
| HP            | 81B3                        | [6487460c3d](https://linux-hardware.org/?probe=6487460c3d) | Apr 01, 2021 |
| HP            | 81B3                        | [5665423fc6](https://linux-hardware.org/?probe=5665423fc6) | Apr 01, 2021 |
| Gigabyte      | Z490 AORUS ULTRA            | [b9270b9c26](https://linux-hardware.org/?probe=b9270b9c26) | Apr 01, 2021 |
| MSI           | H81M-E33                    | [e0909347c4](https://linux-hardware.org/?probe=e0909347c4) | Apr 01, 2021 |
| Pegatron      | Benicia                     | [4e2a1c50d1](https://linux-hardware.org/?probe=4e2a1c50d1) | Apr 01, 2021 |
| Foxconn       | 2ABF                        | [44499a7ea7](https://linux-hardware.org/?probe=44499a7ea7) | Mar 31, 2021 |
| Gigabyte      | B75M-HD3                    | [efba9b0bd6](https://linux-hardware.org/?probe=efba9b0bd6) | Mar 30, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 281      | 16.33%  |
| Ubuntu 18.04                 | 224      | 13.02%  |
| OpenMandriva 4.2             | 85       | 4.94%   |
| Debian 11                    | 52       | 3.02%   |
| OpenMandriva 4.3             | 41       | 2.38%   |
| Debian 10                    | 40       | 2.32%   |
| KDE neon 20.04               | 39       | 2.27%   |
| Manjaro                      | 35       | 2.03%   |
| Ubuntu 22.04                 | 31       | 1.8%    |
| Linux Mint 19.3              | 31       | 1.8%    |
| Ubuntu 19.04                 | 27       | 1.57%   |
| Arch Rolling                 | 27       | 1.57%   |
| Linux Mint 20.1              | 26       | 1.51%   |
| Linux Mint 20.3              | 24       | 1.39%   |
| Arch                         | 24       | 1.39%   |
| Ubuntu 19.10                 | 23       | 1.34%   |
| Ubuntu 20.10                 | 21       | 1.22%   |
| ROSA R10                     | 21       | 1.22%   |
| Zorin 16                     | 20       | 1.16%   |
| Xubuntu 20.04                | 19       | 1.1%    |
| Linux Mint 20                | 19       | 1.1%    |
| Fedora 35                    | 18       | 1.05%   |
| Xubuntu 18.04                | 17       | 0.99%   |
| Ubuntu 21.04                 | 17       | 0.99%   |
| Pop!_OS 20.04                | 15       | 0.87%   |
| Linux Mint 20.2              | 15       | 0.87%   |
| Ubuntu 21.10                 | 14       | 0.81%   |
| Gentoo 2.7                   | 14       | 0.81%   |
| Fedora 36                    | 14       | 0.81%   |
| Fedora 34                    | 14       | 0.81%   |
| Zorin 15                     | 13       | 0.76%   |
| Linux Mint 19.2              | 13       | 0.76%   |
| Kubuntu 20.04                | 13       | 0.76%   |
| Fedora 32                    | 13       | 0.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 12       | 0.7%    |
| Ubuntu 18.10                 | 11       | 0.64%   |
| ROSA R11                     | 11       | 0.64%   |
| Linux Mint 19.1              | 11       | 0.64%   |
| Ubuntu 16.04                 | 10       | 0.58%   |
| Fedora 33                    | 10       | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu            | 628      | 38.5%   |
| Linux Mint        | 138      | 8.46%   |
| OpenMandriva      | 135      | 8.28%   |
| Debian            | 108      | 6.62%   |
| Manjaro           | 71       | 4.35%   |
| Fedora            | 67       | 4.11%   |
| Arch              | 50       | 3.07%   |
| ROSA              | 46       | 2.82%   |
| KDE neon          | 46       | 2.82%   |
| Xubuntu           | 40       | 2.45%   |
| Zorin             | 35       | 2.15%   |
| Pop!_OS           | 34       | 2.08%   |
| Kubuntu           | 28       | 1.72%   |
| Gentoo            | 24       | 1.47%   |
| Ubuntu MATE       | 18       | 1.1%    |
| openSUSE          | 16       | 0.98%   |
| Endless           | 16       | 0.98%   |
| Elementary        | 16       | 0.98%   |
| ArcoLinux         | 14       | 0.86%   |
| Ubuntu Unity      | 13       | 0.8%    |
| BlackPanther      | 11       | 0.67%   |
| Lubuntu           | 7        | 0.43%   |
| MX                | 6        | 0.37%   |
| LMDE              | 6        | 0.37%   |
| Clear Linux       | 6        | 0.37%   |
| Reborn OS         | 5        | 0.31%   |
| Kali              | 5        | 0.31%   |
| Parrot            | 4        | 0.25%   |
| Garuda Linux      | 4        | 0.25%   |
| Ubuntu Budgie     | 3        | 0.18%   |
| EndeavourOS       | 3        | 0.18%   |
| Solus             | 2        | 0.12%   |
| Slackware         | 2        | 0.12%   |
| Xero              | 1        | 0.06%   |
| Void Linux        | 1        | 0.06%   |
| Ultramarine Linux | 1        | 0.06%   |
| Ubuntu Studio     | 1        | 0.06%   |
| Trisquel          | 1        | 0.06%   |
| SteamOS           | 1        | 0.06%   |
| Sparky            | 1        | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 83       | 4.34%   |
| 5.16.7-desktop-1omv4003         | 41       | 2.14%   |
| 5.4.0-42-generic                | 39       | 2.04%   |
| 5.4.0-58-generic                | 24       | 1.26%   |
| 5.4.0-52-generic                | 22       | 1.15%   |
| 5.4.0-48-generic                | 19       | 0.99%   |
| 5.10.0-8-amd64                  | 19       | 0.99%   |
| 5.4.0-54-generic                | 17       | 0.89%   |
| 5.4.0-29-generic                | 17       | 0.89%   |
| 5.4.0-26-generic                | 17       | 0.89%   |
| 5.13.0-30-generic               | 16       | 0.84%   |
| 5.3.0-40-generic                | 15       | 0.78%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 15       | 0.78%   |
| 5.4.0-47-generic                | 14       | 0.73%   |
| 4.15.0-72-generic               | 14       | 0.73%   |
| 5.4.0-37-generic                | 13       | 0.68%   |
| 5.4.0-28-generic                | 13       | 0.68%   |
| 5.11.0-43-generic               | 12       | 0.63%   |
| 5.11.0-27-generic               | 12       | 0.63%   |
| 5.0.0-37-generic                | 12       | 0.63%   |
| 5.4.0-72-generic                | 11       | 0.58%   |
| 5.13.0-39-generic               | 11       | 0.58%   |
| 5.11.0-37-generic               | 11       | 0.58%   |
| 5.0.0-23-generic                | 11       | 0.58%   |
| 4.15.0-47-generic               | 11       | 0.58%   |
| 4.15.0-45-generic               | 11       | 0.58%   |
| 5.8.0-48-generic                | 10       | 0.52%   |
| 5.4.0-65-generic                | 10       | 0.52%   |
| 5.4.0-40-generic                | 10       | 0.52%   |
| 5.3.0-51-generic                | 10       | 0.52%   |
| 5.3.0-28-generic                | 10       | 0.52%   |
| 5.13.0-40-generic               | 10       | 0.52%   |
| 5.13.0-28-generic               | 10       | 0.52%   |
| 5.0.0-32-generic                | 10       | 0.52%   |
| 4.15.0-74-generic               | 10       | 0.52%   |
| 4.15.0-46-generic               | 10       | 0.52%   |
| 5.8.0-43-generic                | 9        | 0.47%   |
| 5.4.0-70-generic                | 9        | 0.47%   |
| 5.4.0-45-generic                | 9        | 0.47%   |
| 5.3.0-46-generic                | 9        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 348      | 19.67%  |
| 4.15.0  | 195      | 11.02%  |
| 5.8.0   | 93       | 5.26%   |
| 5.3.0   | 90       | 5.09%   |
| 5.13.0  | 87       | 4.92%   |
| 5.11.0  | 86       | 4.86%   |
| 5.10.14 | 84       | 4.75%   |
| 5.0.0   | 74       | 4.18%   |
| 5.10.0  | 68       | 3.84%   |
| 5.15.0  | 49       | 2.77%   |
| 5.16.7  | 41       | 2.32%   |
| 4.19.0  | 39       | 2.2%    |
| 4.18.0  | 37       | 2.09%   |
| 4.9.60  | 18       | 1.02%   |
| 4.18.16 | 8        | 0.45%   |
| 5.15.6  | 7        | 0.4%    |
| 4.4.0   | 7        | 0.4%    |
| 5.9.0   | 6        | 0.34%   |
| 5.8.11  | 6        | 0.34%   |
| 5.7.0   | 6        | 0.34%   |
| 5.6.0   | 6        | 0.34%   |
| 5.17.5  | 6        | 0.34%   |
| 4.9.20  | 6        | 0.34%   |
| 5.3.18  | 5        | 0.28%   |
| 5.18.0  | 5        | 0.28%   |
| 5.15.32 | 5        | 0.28%   |
| 5.15.15 | 5        | 0.28%   |
| 5.12.4  | 5        | 0.28%   |
| 5.10.74 | 5        | 0.28%   |
| 5.9.16  | 4        | 0.23%   |
| 5.8.10  | 4        | 0.23%   |
| 5.7.10  | 4        | 0.23%   |
| 5.4.97  | 4        | 0.23%   |
| 5.3.7   | 4        | 0.23%   |
| 5.19.9  | 4        | 0.23%   |
| 5.18.12 | 4        | 0.23%   |
| 5.16.11 | 4        | 0.23%   |
| 5.14.16 | 4        | 0.23%   |
| 5.14.14 | 4        | 0.23%   |
| 5.13.10 | 4        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 375      | 21.45%  |
| 4.15    | 195      | 11.16%  |
| 5.10    | 184      | 10.53%  |
| 5.8     | 122      | 6.98%   |
| 5.11    | 110      | 6.29%   |
| 5.3     | 103      | 5.89%   |
| 5.13    | 103      | 5.89%   |
| 5.15    | 90       | 5.15%   |
| 5.0     | 76       | 4.35%   |
| 5.16    | 60       | 3.43%   |
| 4.18    | 46       | 2.63%   |
| 4.19    | 44       | 2.52%   |
| 4.9     | 36       | 2.06%   |
| 5.14    | 25       | 1.43%   |
| 5.6     | 24       | 1.37%   |
| 5.18    | 22       | 1.26%   |
| 5.7     | 19       | 1.09%   |
| 5.12    | 19       | 1.09%   |
| 5.9     | 18       | 1.03%   |
| 5.19    | 15       | 0.86%   |
| 5.17    | 13       | 0.74%   |
| 5.5     | 11       | 0.63%   |
| 4.4     | 9        | 0.51%   |
| 4.1     | 5        | 0.29%   |
| 5.2     | 4        | 0.23%   |
| 5.1     | 4        | 0.23%   |
| 4.17    | 3        | 0.17%   |
| 4.14    | 3        | 0.17%   |
| 4.8     | 2        | 0.11%   |
| 3.16    | 2        | 0.11%   |
| 6.0     | 1        | 0.06%   |
| 4.20    | 1        | 0.06%   |
| 4.16    | 1        | 0.06%   |
| 4.13    | 1        | 0.06%   |
| 3.10    | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1518     | 96.75%  |
| i686   | 51       | 3.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 674      | 40.43%  |
| KDE5            | 278      | 16.68%  |
| Unknown         | 259      | 15.54%  |
| XFCE            | 112      | 6.72%   |
| X-Cinnamon      | 103      | 6.18%   |
| KDE             | 70       | 4.2%    |
| MATE            | 54       | 3.24%   |
| KDE4            | 21       | 1.26%   |
| Pantheon        | 15       | 0.9%    |
| Cinnamon        | 15       | 0.9%    |
| Unity           | 13       | 0.78%   |
| LXQt            | 12       | 0.72%   |
| i3              | 8        | 0.48%   |
| Budgie          | 8        | 0.48%   |
| Deepin          | 6        | 0.36%   |
| qtile           | 3        | 0.18%   |
| Openbox         | 3        | 0.18%   |
| LXDE            | 3        | 0.18%   |
| xmonad          | 2        | 0.12%   |
| GNOME Flashback | 2        | 0.12%   |
| Trinity         | 1        | 0.06%   |
| ICEWM           | 1        | 0.06%   |
| GNOME Classic   | 1        | 0.06%   |
| fvwm            | 1        | 0.06%   |
| DWM             | 1        | 0.06%   |
| bspwm           | 1        | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1341     | 83.03%  |
| Unknown | 124      | 7.68%   |
| Wayland | 122      | 7.55%   |
| Tty     | 28       | 1.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 966      | 59.26%  |
| SDDM    | 260      | 15.95%  |
| GDM     | 139      | 8.53%   |
| GDM3    | 96       | 5.89%   |
| LightDM | 80       | 4.91%   |
| TDM     | 55       | 3.37%   |
| KDM     | 21       | 1.29%   |
| XDM     | 6        | 0.37%   |
| LXDM    | 4        | 0.25%   |
| Ly      | 2        | 0.12%   |
| SLiM    | 1        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| es_ES          | 937      | 57.45%  |
| Unknown        | 268      | 16.43%  |
| en_US          | 231      | 14.16%  |
| ca_ES          | 49       | 3%      |
| en_GB          | 27       | 1.66%   |
| gl_ES          | 20       | 1.23%   |
| C              | 14       | 0.86%   |
| eu_ES          | 11       | 0.67%   |
| de_DE          | 9        | 0.55%   |
| ru_RU          | 8        | 0.49%   |
| fr_FR          | 7        | 0.43%   |
| it_IT          | 5        | 0.31%   |
| ro_RO          | 4        | 0.25%   |
| en_IE          | 4        | 0.25%   |
| C.UTF8         | 4        | 0.25%   |
| es_ES.UTF8     | 3        | 0.18%   |
| an_ES          | 3        | 0.18%   |
| pt_PT          | 2        | 0.12%   |
| pt_BR          | 2        | 0.12%   |
| pl_PL          | 2        | 0.12%   |
| es_MX          | 2        | 0.12%   |
| es_AR          | 2        | 0.12%   |
| en_DK          | 2        | 0.12%   |
| ca_ES@valencia | 2        | 0.12%   |
| bg_BG          | 2        | 0.12%   |
| spanish        | 1        | 0.06%   |
| POSIX          | 1        | 0.06%   |
| nl_NL          | 1        | 0.06%   |
| es_ES@euro     | 1        | 0.06%   |
| es_ES.utf-8    | 1        | 0.06%   |
| es_EC          | 1        | 0.06%   |
| es_CL          | 1        | 0.06%   |
| eo             | 1        | 0.06%   |
| en_AU          | 1        | 0.06%   |
| de_AT          | 1        | 0.06%   |
| ca_AD          | 1        | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1036     | 64.47%  |
| EFI  | 571      | 35.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1214     | 75.36%  |
| Overlay  | 146      | 9.06%   |
| Unknown  | 95       | 5.9%    |
| Btrfs    | 87       | 5.4%    |
| Ext3     | 29       | 1.8%    |
| Xfs      | 22       | 1.37%   |
| Ext2     | 6        | 0.37%   |
| Zfs      | 5        | 0.31%   |
| Reiserfs | 4        | 0.25%   |
| Tmpfs    | 3        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1061     | 66.11%  |
| GPT     | 364      | 22.68%  |
| MBR     | 180      | 11.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1235     | 76.23%  |
| Yes       | 385      | 23.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 976      | 60.85%  |
| Yes       | 628      | 39.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 446      | 28.44%  |
| Gigabyte Technology | 334      | 21.3%   |
| MSI                 | 205      | 13.07%  |
| Hewlett-Packard     | 110      | 7.02%   |
| ASRock              | 110      | 7.02%   |
| Dell                | 62       | 3.95%   |
| Lenovo              | 56       | 3.57%   |
| Acer                | 46       | 2.93%   |
| Intel               | 30       | 1.91%   |
| Unknown             | 23       | 1.47%   |
| Medion              | 18       | 1.15%   |
| Pegatron            | 17       | 1.08%   |
| ECS                 | 16       | 1.02%   |
| Foxconn             | 11       | 0.7%    |
| Huanan              | 10       | 0.64%   |
| Packard Bell        | 8        | 0.51%   |
| eMachines           | 7        | 0.45%   |
| Shuttle             | 6        | 0.38%   |
| Fujitsu             | 6        | 0.38%   |
| BESSTAR Tech        | 4        | 0.26%   |
| NEC Computers       | 3        | 0.19%   |
| AZW                 | 3        | 0.19%   |
| Wistron             | 2        | 0.13%   |
| Minix               | 2        | 0.13%   |
| MACHINIST           | 2        | 0.13%   |
| IBM                 | 2        | 0.13%   |
| Gateway             | 2        | 0.13%   |
| Biostar             | 2        | 0.13%   |
| Apple               | 2        | 0.13%   |
| AMI                 | 2        | 0.13%   |
| Toshiba             | 1        | 0.06%   |
| TEKNOSERVICE        | 1        | 0.06%   |
| T-bao               | 1        | 0.06%   |
| Supermicro          | 1        | 0.06%   |
| SiYW                | 1        | 0.06%   |
| Seco                | 1        | 0.06%   |
| Point of View       | 1        | 0.06%   |
| OEM_MB              | 1        | 0.06%   |
| OEM                 | 1        | 0.06%   |
| MAXSUN              | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 49       | 3.13%   |
| Unknown                           | 26       | 1.66%   |
| Lenovo ThinkCentre E73 10DR0033SP | 22       | 1.4%    |
| MSI MS-7C37                       | 11       | 0.7%    |
| Gigabyte 970A-DS3P                | 10       | 0.64%   |
| ASUS P5G41T-M LX                  | 10       | 0.64%   |
| MSI MS-7817                       | 9        | 0.57%   |
| Gigabyte B450M DS3H               | 9        | 0.57%   |
| MSI MS-7B79                       | 8        | 0.51%   |
| Gigabyte H110M-S2H                | 8        | 0.51%   |
| ASUS PRIME A320M-K                | 8        | 0.51%   |
| MSI MS-7C02                       | 7        | 0.45%   |
| MSI MS-7B86                       | 7        | 0.45%   |
| Gigabyte H61M-DS2                 | 7        | 0.45%   |
| Gigabyte B450 AORUS M             | 7        | 0.45%   |
| ASUS PRIME B450M-A                | 7        | 0.45%   |
| ASUS P5K                          | 7        | 0.45%   |
| MSI MS-7A38                       | 6        | 0.38%   |
| HP Compaq Elite 8300 SFF          | 6        | 0.38%   |
| ASUS TUF Gaming X570-PLUS         | 6        | 0.38%   |
| ASUS H110M-D                      | 6        | 0.38%   |
| MSI MS-7C91                       | 5        | 0.32%   |
| MSI MS-7B49                       | 5        | 0.32%   |
| MSI MS-7A34                       | 5        | 0.32%   |
| MSI MS-7693                       | 5        | 0.32%   |
| Gigabyte X570 AORUS MASTER        | 5        | 0.32%   |
| Gigabyte H81M-S2H                 | 5        | 0.32%   |
| Gigabyte H81M-S1                  | 5        | 0.32%   |
| Gigabyte H61M-S2PV                | 5        | 0.32%   |
| Gigabyte G31M-ES2L                | 5        | 0.32%   |
| Dell OptiPlex 3050                | 5        | 0.32%   |
| ASUS TUF B450-PLUS GAMING         | 5        | 0.32%   |
| ASUS P5KPL-AM EPU                 | 5        | 0.32%   |
| ASUS M4A785TD-V EVO               | 5        | 0.32%   |
| MSI MS-7C52                       | 4        | 0.26%   |
| MSI MS-7B89                       | 4        | 0.26%   |
| MSI MS-7B84                       | 4        | 0.26%   |
| MSI MS-7B17                       | 4        | 0.26%   |
| Intel DH55TC AAE70932-205         | 4        | 0.26%   |
| Huanan X99-F8                     | 4        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 65       | 4.15%   |
| ASUS All           | 49       | 3.13%   |
| Lenovo ThinkCentre | 46       | 2.93%   |
| HP Compaq          | 46       | 2.93%   |
| Dell OptiPlex      | 43       | 2.74%   |
| ASUS TUF           | 40       | 2.55%   |
| Acer Aspire        | 33       | 2.1%    |
| ASUS ROG           | 30       | 1.91%   |
| Unknown            | 26       | 1.66%   |
| Gigabyte X570      | 19       | 1.21%   |
| Gigabyte B450M     | 14       | 0.89%   |
| Gigabyte B450      | 14       | 0.89%   |
| HP EliteDesk       | 13       | 0.83%   |
| ASUS P5KPL-AM      | 12       | 0.77%   |
| MSI MS-7C37        | 11       | 0.7%    |
| Gigabyte 970A-DS3P | 10       | 0.64%   |
| Dell Precision     | 10       | 0.64%   |
| ASUS P5G41T-M      | 10       | 0.64%   |
| MSI MS-7817        | 9        | 0.57%   |
| HP ProDesk         | 9        | 0.57%   |
| ASUS P8Z77-V       | 9        | 0.57%   |
| MSI MS-7B79        | 8        | 0.51%   |
| Gigabyte H61M-DS2  | 8        | 0.51%   |
| Gigabyte H110M-S2H | 8        | 0.51%   |
| ASUS SABERTOOTH    | 8        | 0.51%   |
| ASUS P8H61-M       | 8        | 0.51%   |
| ASUS P5K           | 8        | 0.51%   |
| MSI MS-7C02        | 7        | 0.45%   |
| MSI MS-7B86        | 7        | 0.45%   |
| ASUS Maximus       | 7        | 0.45%   |
| ASUS M5A78L-M      | 7        | 0.45%   |
| Acer Veriton       | 7        | 0.45%   |
| MSI MS-7A38        | 6        | 0.38%   |
| Lenovo IdeaCentre  | 6        | 0.38%   |
| Intel DH55TC       | 6        | 0.38%   |
| HP Pavilion        | 6        | 0.38%   |
| Gigabyte X470      | 6        | 0.38%   |
| Gigabyte A320M-S2H | 6        | 0.38%   |
| ASUS M5A97         | 6        | 0.38%   |
| ASUS H110M-D       | 6        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 154      | 9.82%   |
| 2013 | 142      | 9.06%   |
| 2012 | 140      | 8.93%   |
| 2019 | 136      | 8.67%   |
| 2014 | 126      | 8.04%   |
| 2010 | 100      | 6.38%   |
| 2009 | 98       | 6.25%   |
| 2011 | 94       | 5.99%   |
| 2020 | 92       | 5.87%   |
| 2017 | 92       | 5.87%   |
| 2008 | 81       | 5.17%   |
| 2016 | 68       | 4.34%   |
| 2007 | 68       | 4.34%   |
| 2015 | 66       | 4.21%   |
| 2006 | 50       | 3.19%   |
| 2021 | 39       | 2.49%   |
| 2005 | 12       | 0.77%   |
| 2022 | 6        | 0.38%   |
| 2004 | 2        | 0.13%   |
| 2002 | 1        | 0.06%   |
| 2001 | 1        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1568     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1539     | 97.9%   |
| Enabled  | 33       | 2.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1568     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 407      | 25.25%  |
| 3.01-4.0    | 311      | 19.29%  |
| 8.01-16.0   | 305      | 18.92%  |
| 4.01-8.0    | 242      | 15.01%  |
| 32.01-64.0  | 181      | 11.23%  |
| 1.01-2.0    | 74       | 4.59%   |
| 64.01-256.0 | 32       | 1.99%   |
| 2.01-3.0    | 26       | 1.61%   |
| 24.01-32.0  | 25       | 1.55%   |
| 0.51-1.0    | 8        | 0.5%    |
| Unknown     | 1        | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 722      | 41.26%  |
| 2.01-3.0   | 414      | 23.66%  |
| 4.01-8.0   | 204      | 11.66%  |
| 3.01-4.0   | 181      | 10.34%  |
| 0.51-1.0   | 143      | 8.17%   |
| 8.01-16.0  | 55       | 3.14%   |
| 0.01-0.5   | 21       | 1.2%    |
| 24.01-32.0 | 4        | 0.23%   |
| 16.01-24.0 | 4        | 0.23%   |
| 32.01-64.0 | 1        | 0.06%   |
| Unknown    | 1        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 595      | 35.82%  |
| 2      | 514      | 30.95%  |
| 3      | 294      | 17.7%   |
| 4      | 139      | 8.37%   |
| 5      | 54       | 3.25%   |
| 6      | 27       | 1.63%   |
| 0      | 12       | 0.72%   |
| 7      | 9        | 0.54%   |
| 8      | 6        | 0.36%   |
| 9      | 5        | 0.3%    |
| 11     | 2        | 0.12%   |
| 10     | 2        | 0.12%   |
| 18     | 1        | 0.06%   |
| 12     | 1        | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 858      | 53.79%  |
| No        | 737      | 46.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1561     | 99.55%  |
| No        | 7        | 0.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 958      | 59.88%  |
| Yes       | 642      | 40.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1140     | 71.38%  |
| Yes       | 457      | 28.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Spain   | 1568     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Madrid                     | 244      | 14.22%  |
| Barcelona                  | 169      | 9.85%   |
| Valencia                   | 63       | 3.67%   |
| Seville                    | 58       | 3.38%   |
| Zaragoza                   | 27       | 1.57%   |
| Ourense                    | 27       | 1.57%   |
| Málaga                    | 27       | 1.57%   |
| Las Palmas de Gran Canaria | 20       | 1.17%   |
| Valladolid                 | 19       | 1.11%   |
| Granada                    | 19       | 1.11%   |
| Murcia                     | 17       | 0.99%   |
| Bilbao                     | 17       | 0.99%   |
| Palma                      | 16       | 0.93%   |
| Vigo                       | 15       | 0.87%   |
| Sabadell                   | 15       | 0.87%   |
| Santa Cruz de Tenerife     | 14       | 0.82%   |
| Almería                   | 13       | 0.76%   |
| Córdoba                   | 11       | 0.64%   |
| Oviedo                     | 10       | 0.58%   |
| Alcobendas                 | 10       | 0.58%   |
| Santander                  | 9        | 0.52%   |
| Gijón                     | 9        | 0.52%   |
| Barakaldo                  | 9        | 0.52%   |
| Alicante                   | 9        | 0.52%   |
| Alcalá de Henares         | 9        | 0.52%   |
| Vitoria-Gasteiz            | 8        | 0.47%   |
| Salamanca                  | 8        | 0.47%   |
| Pamplona                   | 8        | 0.47%   |
| Lugo                       | 8        | 0.47%   |
| Fuenlabrada                | 8        | 0.47%   |
| Terrassa                   | 7        | 0.41%   |
| San Fernando               | 7        | 0.41%   |
| Pontevedra                 | 7        | 0.41%   |
| Mataró                    | 7        | 0.41%   |
| Logroño                   | 7        | 0.41%   |
| Huelva                     | 7        | 0.41%   |
| Girona                     | 7        | 0.41%   |
| Elche                      | 7        | 0.41%   |
| A Coruña                  | 7        | 0.41%   |
| Talavera de la Reina       | 6        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 734      | 1220   | 25.22%  |
| WDC                       | 508      | 802    | 17.46%  |
| Kingston                  | 376      | 551    | 12.92%  |
| Samsung Electronics       | 348      | 585    | 11.96%  |
| Toshiba                   | 204      | 365    | 7.01%   |
| SanDisk                   | 123      | 174    | 4.23%   |
| Crucial                   | 121      | 185    | 4.16%   |
| Hitachi                   | 85       | 103    | 2.92%   |
| Maxtor                    | 34       | 43     | 1.17%   |
| Unknown                   | 28       | 32     | 0.96%   |
| China                     | 27       | 32     | 0.93%   |
| Intel                     | 26       | 32     | 0.89%   |
| Phison                    | 24       | 28     | 0.82%   |
| OCZ                       | 20       | 26     | 0.69%   |
| Silicon Motion            | 17       | 23     | 0.58%   |
| HGST                      | 17       | 22     | 0.58%   |
| Micron/Crucial Technology | 13       | 16     | 0.45%   |
| Corsair                   | 13       | 16     | 0.45%   |
| KingDian                  | 11       | 13     | 0.38%   |
| Fujitsu                   | 11       | 13     | 0.38%   |
| SK hynix                  | 10       | 16     | 0.34%   |
| Transcend                 | 9        | 22     | 0.31%   |
| KIOXIA-EXCERIA            | 9        | 12     | 0.31%   |
| JMicron Technology        | 9        | 10     | 0.31%   |
| USB30                     | 7        | 20     | 0.24%   |
| Emtec                     | 7        | 7      | 0.24%   |
| Unknown                   | 7        | 9      | 0.24%   |
| PNY                       | 6        | 10     | 0.21%   |
| GOODRAM                   | 6        | 7      | 0.21%   |
| Drevo                     | 6        | 9      | 0.21%   |
| A-DATA Technology         | 6        | 8      | 0.21%   |
| Hewlett-Packard           | 5        | 6      | 0.17%   |
| Realtek Semiconductor     | 4        | 5      | 0.14%   |
| Patriot                   | 4        | 9      | 0.14%   |
| Micron Technology         | 4        | 4      | 0.14%   |
| SPCC                      | 3        | 3      | 0.1%    |
| KingSpec                  | 3        | 5      | 0.1%    |
| KingFast                  | 3        | 4      | 0.1%    |
| Intenso                   | 3        | 4      | 0.1%    |
| ASMT                      | 3        | 5      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 117      | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB   | 77       | 2.27%   |
| Seagate ST500DM002-1BD142 500GB  | 67       | 1.97%   |
| Kingston SA400S37120G 120GB SSD  | 56       | 1.65%   |
| Kingston SV300S37A120G 120GB SSD | 54       | 1.59%   |
| Seagate ST3500418AS 500GB        | 52       | 1.53%   |
| Kingston SA400S37480G 480GB SSD  | 47       | 1.39%   |
| Seagate ST1000DM003-1ER162 1TB   | 42       | 1.24%   |
| Seagate ST1000DM003-1CH162 1TB   | 39       | 1.15%   |
| Toshiba DT01ACA100 1TB           | 37       | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB   | 34       | 1%      |
| Samsung SSD 860 EVO 500GB        | 33       | 0.97%   |
| Samsung NVMe SSD Drive 500GB     | 32       | 0.94%   |
| Seagate ST31000528AS 1TB         | 28       | 0.83%   |
| Samsung SSD 850 EVO 500GB        | 25       | 0.74%   |
| Kingston SV300S37A240G 240GB SSD | 23       | 0.68%   |
| WDC WD20EARX-00PASB0 2TB         | 22       | 0.65%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 21       | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB   | 21       | 0.62%   |
| Seagate ST2000DM001-1CH164 2TB   | 21       | 0.62%   |
| Crucial CT500MX500SSD1 500GB     | 21       | 0.62%   |
| Toshiba TR200 240GB SSD          | 20       | 0.59%   |
| Seagate ST2000DM001-1ER164 2TB   | 20       | 0.59%   |
| SanDisk NVMe SSD Drive 500GB     | 20       | 0.59%   |
| Samsung SSD 850 EVO 250GB        | 20       | 0.59%   |
| Toshiba DT01ACA050 500GB         | 19       | 0.56%   |
| Kingston SUV400S37240G 240GB SSD | 19       | 0.56%   |
| Toshiba DT01ACA200 2TB           | 18       | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB         | 17       | 0.5%    |
| Toshiba DT01ACA300 3TB           | 17       | 0.5%    |
| Seagate ST2000DM006-2DM164 2TB   | 17       | 0.5%    |
| SanDisk SSD PLUS 480GB           | 16       | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB   | 16       | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 15       | 0.44%   |
| Unknown SD/MMC/MS PRO 2GB        | 15       | 0.44%   |
| Seagate ST3500413AS 500GB        | 15       | 0.44%   |
| Seagate ST1000DM003-1SB10C 1TB   | 15       | 0.44%   |
| Seagate ST1000DM003-1SB102 1TB   | 15       | 0.44%   |
| Seagate Expansion 1TB            | 15       | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 14       | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 728      | 1209   | 45.84%  |
| WDC                 | 452      | 693    | 28.46%  |
| Toshiba             | 158      | 252    | 9.95%   |
| Hitachi             | 85       | 103    | 5.35%   |
| Samsung Electronics | 80       | 106    | 5.04%   |
| Maxtor              | 30       | 39     | 1.89%   |
| HGST                | 17       | 22     | 1.07%   |
| Unknown             | 15       | 16     | 0.94%   |
| Fujitsu             | 10       | 12     | 0.63%   |
| Hewlett-Packard     | 3        | 4      | 0.19%   |
| ASMT                | 3        | 5      | 0.19%   |
| Quantum             | 1        | 1      | 0.06%   |
| JMicron Technology  | 1        | 1      | 0.06%   |
| Inateck             | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| China               | 1        | 1      | 0.06%   |
| ASMedia             | 1        | 1      | 0.06%   |
| Apple               | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 361      | 523    | 34.91%  |
| Samsung Electronics | 189      | 289    | 18.28%  |
| Crucial             | 110      | 167    | 10.64%  |
| SanDisk             | 85       | 111    | 8.22%   |
| WDC                 | 63       | 91     | 6.09%   |
| Toshiba             | 49       | 107    | 4.74%   |
| China               | 25       | 30     | 2.42%   |
| OCZ                 | 20       | 26     | 1.93%   |
| KingDian            | 11       | 13     | 1.06%   |
| Transcend           | 9        | 22     | 0.87%   |
| Intel               | 9        | 12     | 0.87%   |
| USB30               | 7        | 20     | 0.68%   |
| KIOXIA-EXCERIA      | 7        | 9      | 0.68%   |
| Emtec               | 6        | 6      | 0.58%   |
| GOODRAM             | 5        | 6      | 0.48%   |
| Drevo               | 5        | 7      | 0.48%   |
| A-DATA Technology   | 5        | 7      | 0.48%   |
| Unknown             | 5        | 5      | 0.48%   |
| PNY                 | 4        | 8      | 0.39%   |
| Patriot             | 4        | 9      | 0.39%   |
| Maxtor              | 4        | 4      | 0.39%   |
| Corsair             | 4        | 6      | 0.39%   |
| KingSpec            | 3        | 5      | 0.29%   |
| Intenso             | 3        | 4      | 0.29%   |
| SK hynix            | 2        | 2      | 0.19%   |
| Netac               | 2        | 2      | 0.19%   |
| Hewlett-Packard     | 2        | 2      | 0.19%   |
| BAITITON            | 2        | 2      | 0.19%   |
| XUNZHE800S          | 1        | 2      | 0.1%    |
| TO Exter            | 1        | 1      | 0.1%    |
| Team                | 1        | 1      | 0.1%    |
| TCSUNBOW            | 1        | 1      | 0.1%    |
| TCSUNB0W            | 1        | 1      | 0.1%    |
| SPCC                | 1        | 1      | 0.1%    |
| SMI                 | 1        | 1      | 0.1%    |
| Ramsta              | 1        | 1      | 0.1%    |
| Radeon              | 1        | 2      | 0.1%    |
| Plextor             | 1        | 1      | 0.1%    |
| OYUNKEY             | 1        | 1      | 0.1%    |
| OCZ-VERTEX3         | 1        | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1238     | 2468   | 51.56%  |
| SSD     | 825      | 1534   | 34.36%  |
| NVMe    | 298      | 469    | 12.41%  |
| Unknown | 30       | 39     | 1.25%   |
| MMC     | 10       | 11     | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1484     | 3915   | 79.06%  |
| NVMe | 291      | 460    | 15.5%   |
| SAS  | 92       | 135    | 4.9%    |
| MMC  | 10       | 11     | 0.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1184     | 2340   | 53.77%  |
| 0.51-1.0   | 638      | 1025   | 28.97%  |
| 1.01-2.0   | 237      | 375    | 10.76%  |
| 2.01-3.0   | 62       | 100    | 2.82%   |
| 3.01-4.0   | 58       | 95     | 2.63%   |
| 4.01-10.0  | 22       | 66     | 1%      |
| 10.01-20.0 | 1        | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 415      | 24.25%  |
| 251-500        | 287      | 16.77%  |
| 501-1000       | 254      | 14.85%  |
| 1001-2000      | 188      | 10.99%  |
| More than 3000 | 129      | 7.54%   |
| 1-20           | 119      | 6.95%   |
| 2001-3000      | 117      | 6.84%   |
| 51-100         | 94       | 5.49%   |
| 21-50          | 59       | 3.45%   |
| Unknown        | 49       | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 611      | 34.62%  |
| 21-50          | 263      | 14.9%   |
| 101-250        | 207      | 11.73%  |
| 51-100         | 157      | 8.9%    |
| 251-500        | 140      | 7.93%   |
| 501-1000       | 139      | 7.88%   |
| 1001-2000      | 111      | 6.29%   |
| More than 3000 | 51       | 2.89%   |
| Unknown        | 49       | 2.78%   |
| 2001-3000      | 37       | 2.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 10       | 10     | 4.35%   |
| Seagate ST3500418AS 500GB         | 10       | 16     | 4.35%   |
| Kingston SV300S37A120G 120GB SSD  | 10       | 12     | 4.35%   |
| Seagate ST1000DM003-1CH162 1TB    | 6        | 7      | 2.61%   |
| WDC WD5000AAKX-001CA0 500GB       | 4        | 6      | 1.74%   |
| Seagate ST3500320AS 500GB         | 4        | 7      | 1.74%   |
| Seagate ST31000528AS 1TB          | 4        | 5      | 1.74%   |
| Seagate ST1000DM003-1ER162 1TB    | 4        | 7      | 1.74%   |
| Drevo X1 SSD 120GB                | 4        | 6      | 1.74%   |
| WDC WD20EZRX-00DC0B0 2TB          | 3        | 3      | 1.3%    |
| Seagate ST3250310AS 250GB         | 3        | 3      | 1.3%    |
| Seagate ST31500341AS 1TB          | 3        | 3      | 1.3%    |
| WDC WD6400AAKS-22A7B0 640GB       | 2        | 2      | 0.87%   |
| WDC WD40EZRX-00SPEB0 4TB          | 2        | 3      | 0.87%   |
| WDC WD40EFRX-68WT0N0 4TB          | 2        | 2      | 0.87%   |
| WDC WD2500AAJS-00B4A0 250GB       | 2        | 2      | 0.87%   |
| WDC WD10EARS-00Y5B1 1TB           | 2        | 2      | 0.87%   |
| Seagate ST9500325AS 500GB         | 2        | 3      | 0.87%   |
| Seagate ST500LT012-1DG142 500GB   | 2        | 2      | 0.87%   |
| Seagate ST4000DM004-2CV104 4TB    | 2        | 2      | 0.87%   |
| Seagate ST3500830AS 500GB         | 2        | 3      | 0.87%   |
| Seagate ST3500820AS 500GB         | 2        | 2      | 0.87%   |
| Seagate ST3500312CS 500GB         | 2        | 2      | 0.87%   |
| Seagate ST3200822AS 200GB         | 2        | 5      | 0.87%   |
| Seagate ST3200822A 200GB          | 2        | 2      | 0.87%   |
| Seagate ST3160815AS 160GB         | 2        | 2      | 0.87%   |
| Seagate ST31000333AS 1TB          | 2        | 5      | 0.87%   |
| Seagate ST3000DM001-9YN166 3TB    | 2        | 2      | 0.87%   |
| Seagate ST2000DL003-9VT166 2TB    | 2        | 3      | 0.87%   |
| Samsung Electronics HD501LJ 500GB | 2        | 2      | 0.87%   |
| Maxtor STM3250310AS 250GB         | 2        | 2      | 0.87%   |
| KingDian S280 240GB SSD           | 2        | 2      | 0.87%   |
| WDC WD7500AACS-65D6B0 752GB       | 1        | 1      | 0.43%   |
| WDC WD6400AAKS-75A7B2 640GB       | 1        | 1      | 0.43%   |
| WDC WD6400AAKS-65Z7B0 640GB       | 1        | 1      | 0.43%   |
| WDC WD5000LPLX-00ZNTT0 500GB      | 1        | 2      | 0.43%   |
| WDC WD5000BPVT-22HXZT1 500GB      | 1        | 1      | 0.43%   |
| WDC WD5000BEVT-22ZAT0 500GB       | 1        | 1      | 0.43%   |
| WDC WD5000AZRX-00A8LB0 500GB      | 1        | 1      | 0.43%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 87       | 122    | 39.19%  |
| WDC                 | 48       | 57     | 21.62%  |
| Samsung Electronics | 16       | 17     | 7.21%   |
| Kingston            | 16       | 21     | 7.21%   |
| Hitachi             | 9        | 10     | 4.05%   |
| Toshiba             | 8        | 9      | 3.6%    |
| Maxtor              | 7        | 7      | 3.15%   |
| Drevo               | 5        | 7      | 2.25%   |
| SanDisk             | 4        | 4      | 1.8%    |
| Crucial             | 4        | 4      | 1.8%    |
| China               | 3        | 4      | 1.35%   |
| OCZ                 | 2        | 2      | 0.9%    |
| KingDian            | 2        | 2      | 0.9%    |
| Fujitsu             | 2        | 3      | 0.9%    |
| Transcend           | 1        | 4      | 0.45%   |
| Patriot             | 1        | 1      | 0.45%   |
| Intenso             | 1        | 1      | 0.45%   |
| Intel               | 1        | 1      | 0.45%   |
| Hypertec            | 1        | 1      | 0.45%   |
| HGST                | 1        | 1      | 0.45%   |
| ASMT                | 1        | 2      | 0.45%   |
| A-DATA Technology   | 1        | 1      | 0.45%   |
| Unknown             | 1        | 1      | 0.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 87       | 122    | 49.71%  |
| WDC                 | 48       | 57     | 27.43%  |
| Samsung Electronics | 11       | 12     | 6.29%   |
| Hitachi             | 9        | 10     | 5.14%   |
| Toshiba             | 8        | 9      | 4.57%   |
| Maxtor              | 7        | 7      | 4%      |
| Fujitsu             | 2        | 3      | 1.14%   |
| HGST                | 1        | 1      | 0.57%   |
| China               | 1        | 1      | 0.57%   |
| ASMT                | 1        | 2      | 0.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 159      | 224    | 78.71%  |
| SSD  | 41       | 56     | 20.3%   |
| NVMe | 2        | 2      | 0.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB     | 1        | 1      | 12.5%   |
| Toshiba DT01ACA200 2TB          | 1        | 1      | 12.5%   |
| Seagate ST3500830AS 500GB       | 1        | 1      | 12.5%   |
| Seagate ST31000528AS 1TB        | 1        | 1      | 12.5%   |
| Seagate ST31000520AS 1TB        | 1        | 1      | 12.5%   |
| Seagate ST31000333AS 1TB        | 1        | 1      | 12.5%   |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 12.5%   |
| Hitachi HDS721010DLE630 1TB     | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 50%     |
| WDC                 | 1        | 1      | 12.5%   |
| Toshiba             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Hitachi             | 1        | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1082     | 2926   | 61.03%  |
| Works    | 494      | 1305   | 27.86%  |
| Malfunc  | 189      | 282    | 10.66%  |
| Failed   | 8        | 8      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1045     | 50.17%  |
| AMD                              | 428      | 20.55%  |
| Samsung Electronics              | 109      | 5.23%   |
| Nvidia                           | 68       | 3.26%   |
| ASMedia Technology               | 67       | 3.22%   |
| JMicron Technology               | 66       | 3.17%   |
| SanDisk                          | 58       | 2.78%   |
| Marvell Technology Group         | 55       | 2.64%   |
| Phison Electronics               | 40       | 1.92%   |
| VIA Technologies                 | 26       | 1.25%   |
| Micron/Crucial Technology        | 25       | 1.2%    |
| Kingston Technology Company      | 24       | 1.15%   |
| Silicon Motion                   | 20       | 0.96%   |
| SK hynix                         | 7        | 0.34%   |
| Silicon Integrated Systems [SiS] | 7        | 0.34%   |
| Silicon Image                    | 4        | 0.19%   |
| Realtek Semiconductor            | 4        | 0.19%   |
| Micron Technology                | 4        | 0.19%   |
| LSI Logic / Symbios Logic        | 4        | 0.19%   |
| KIOXIA                           | 4        | 0.19%   |
| Adaptec                          | 3        | 0.14%   |
| Unknown                          | 2        | 0.1%    |
| Toshiba America Info Systems     | 2        | 0.1%    |
| Seagate Technology               | 2        | 0.1%    |
| Integrated Technology Express    | 2        | 0.1%    |
| ADATA Technology                 | 2        | 0.1%    |
| ULi Electronics                  | 1        | 0.05%   |
| OCZ Technology Group             | 1        | 0.05%   |
| HighPoint Technologies           | 1        | 0.05%   |
| Hewlett-Packard                  | 1        | 0.05%   |
| Dell                             | 1        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 262      | 9.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 159      | 5.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 112      | 4.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 108      | 3.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 89       | 3.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 85       | 3.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 75       | 2.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 73       | 2.66%   |
| Intel SATA Controller [RAID mode]                                                       | 67       | 2.44%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 66       | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 65       | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 62       | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 56       | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 55       | 2.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 47       | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 45       | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42       | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42       | 1.53%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 36       | 1.31%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 34       | 1.24%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 32       | 1.17%   |
| AMD 500 Series Chipset SATA Controller                                                  | 32       | 1.17%   |
| Nvidia MCP61 SATA Controller                                                            | 29       | 1.06%   |
| AMD 300 Series Chipset SATA Controller                                                  | 29       | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 25       | 0.91%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 25       | 0.91%   |
| Nvidia MCP61 IDE                                                                        | 23       | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 23       | 0.84%   |
| JMicron JMB368 IDE controller                                                           | 21       | 0.77%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 21       | 0.77%   |
| Phison E12 NVMe Controller                                                              | 20       | 0.73%   |
| AMD FCH IDE Controller                                                                  | 20       | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 19       | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 19       | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 18       | 0.66%   |
| AMD FCH SATA Controller D                                                               | 18       | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 17       | 0.62%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 17       | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 16       | 0.58%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 16       | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1150     | 55.61%  |
| IDE  | 510      | 24.66%  |
| NVMe | 296      | 14.31%  |
| RAID | 100      | 4.84%   |
| SCSI | 8        | 0.39%   |
| SAS  | 4        | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1090     | 69.52%  |
| AMD    | 478      | 30.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 29       | 1.84%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 26       | 1.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 23       | 1.46%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 22       | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 21       | 1.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 19       | 1.2%    |
| AMD FX-8350 Eight-Core Processor            | 18       | 1.14%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 17       | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 17       | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 17       | 1.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 15       | 0.95%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 15       | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 15       | 0.95%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 14       | 0.89%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 13       | 0.82%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 13       | 0.82%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 12       | 0.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 12       | 0.76%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 12       | 0.76%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 12       | 0.76%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 12       | 0.76%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 11       | 0.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 11       | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 11       | 0.7%    |
| Intel Core i5-4440 CPU @ 3.10GHz            | 11       | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 11       | 0.7%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 11       | 0.7%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 10       | 0.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.63%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 10       | 0.63%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 10       | 0.63%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 10       | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 10       | 0.63%   |
| AMD FX-6300 Six-Core Processor              | 10       | 0.63%   |
| Intel Pentium 4 CPU 3.00GHz                 | 9        | 0.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 9        | 0.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 9        | 0.57%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 9        | 0.57%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 9        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 269      | 17.05%  |
| Intel Core i7           | 204      | 12.93%  |
| Intel Core i3           | 146      | 9.25%   |
| AMD Ryzen 5             | 122      | 7.73%   |
| AMD Ryzen 7             | 78       | 4.94%   |
| Intel Core 2 Quad       | 65       | 4.12%   |
| Intel Xeon              | 64       | 4.06%   |
| Intel Core 2 Duo        | 60       | 3.8%    |
| Intel Celeron           | 54       | 3.42%   |
| AMD FX                  | 53       | 3.36%   |
| Intel Pentium           | 47       | 2.98%   |
| Intel Pentium Dual-Core | 42       | 2.66%   |
| Intel Core 2            | 26       | 1.65%   |
| AMD Ryzen 9             | 24       | 1.52%   |
| AMD Ryzen 3             | 24       | 1.52%   |
| Intel Pentium Dual      | 22       | 1.39%   |
| Other                   | 21       | 1.33%   |
| Intel Pentium 4         | 21       | 1.33%   |
| AMD Athlon 64 X2        | 21       | 1.33%   |
| AMD A10                 | 20       | 1.27%   |
| Intel Core i9           | 18       | 1.14%   |
| AMD Athlon II X2        | 18       | 1.14%   |
| AMD Phenom II X4        | 13       | 0.82%   |
| AMD A4                  | 13       | 0.82%   |
| Intel Atom              | 11       | 0.7%    |
| Intel Pentium D         | 10       | 0.63%   |
| AMD Phenom              | 10       | 0.63%   |
| AMD A8                  | 10       | 0.63%   |
| AMD Athlon              | 9        | 0.57%   |
| AMD A6                  | 9        | 0.57%   |
| AMD Phenom II X6        | 7        | 0.44%   |
| AMD Athlon 64           | 7        | 0.44%   |
| Intel Pentium Gold      | 6        | 0.38%   |
| AMD Sempron             | 6        | 0.38%   |
| AMD Ryzen Threadripper  | 6        | 0.38%   |
| AMD Athlon II X4        | 6        | 0.38%   |
| Intel Genuine           | 5        | 0.32%   |
| AMD Athlon X4           | 4        | 0.25%   |
| Intel Pentium Silver    | 3        | 0.19%   |
| AMD Ryzen 5 PRO         | 3        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 603      | 38.12%  |
| 2       | 494      | 31.23%  |
| 6       | 205      | 12.96%  |
| 8       | 132      | 8.34%   |
| 1       | 63       | 3.98%   |
| 12      | 35       | 2.21%   |
| 3       | 19       | 1.2%    |
| 16      | 11       | 0.7%    |
| 10      | 10       | 0.63%   |
| Unknown | 6        | 0.38%   |
| 14      | 2        | 0.13%   |
| 32      | 1        | 0.06%   |
| 24      | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1552     | 98.92%  |
| 2      | 17       | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 800      | 50.7%   |
| 1       | 772      | 48.92%  |
| Unknown | 6        | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1526     | 96.46%  |
| Unknown        | 33       | 2.09%   |
| 64-bit         | 17       | 1.07%   |
| 32-bit         | 6        | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 311      | 19.03%  |
| 0x306c3    | 177      | 10.83%  |
| 0x1067a    | 91       | 5.57%   |
| 0x306a9    | 83       | 5.08%   |
| 0x206a7    | 79       | 4.83%   |
| 0x506e3    | 59       | 3.61%   |
| 0x906ea    | 42       | 2.57%   |
| 0x08701021 | 41       | 2.51%   |
| 0x0800820d | 40       | 2.45%   |
| 0x906e9    | 36       | 2.2%    |
| 0x6fb      | 34       | 2.08%   |
| 0x06000852 | 31       | 1.9%    |
| 0x6fd      | 30       | 1.84%   |
| 0x010000c8 | 27       | 1.65%   |
| 0x08701013 | 24       | 1.47%   |
| 0x06001119 | 24       | 1.47%   |
| 0x08108109 | 22       | 1.35%   |
| 0x6f6      | 18       | 1.1%    |
| 0x906ed    | 17       | 1.04%   |
| 0x906eb    | 17       | 1.04%   |
| 0x20655    | 17       | 1.04%   |
| 0xa0655    | 16       | 0.98%   |
| 0x20652    | 16       | 0.98%   |
| 0x10677    | 15       | 0.92%   |
| 0x106e5    | 14       | 0.86%   |
| 0x10676    | 14       | 0.86%   |
| 0x306f2    | 13       | 0.8%    |
| 0x08001137 | 13       | 0.8%    |
| 0xa0653    | 12       | 0.73%   |
| 0x906ec    | 12       | 0.73%   |
| 0x206d7    | 12       | 0.73%   |
| 0x0a201009 | 11       | 0.67%   |
| 0x0810100b | 11       | 0.67%   |
| 0x0800820b | 11       | 0.67%   |
| 0x206c2    | 10       | 0.61%   |
| 0x08001138 | 10       | 0.61%   |
| 0x6f2      | 9        | 0.55%   |
| 0x0a201016 | 9        | 0.55%   |
| 0x08101016 | 9        | 0.55%   |
| 0xa0671    | 8        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 218      | 13.81%  |
| KabyLake         | 159      | 10.07%  |
| Penryn           | 133      | 8.42%   |
| Core             | 105      | 6.65%   |
| SandyBridge      | 103      | 6.52%   |
| IvyBridge        | 103      | 6.52%   |
| Zen+             | 91       | 5.76%   |
| Zen 2            | 84       | 5.32%   |
| Piledriver       | 77       | 4.88%   |
| Skylake          | 73       | 4.62%   |
| K10              | 68       | 4.31%   |
| Zen              | 54       | 3.42%   |
| Westmere         | 45       | 2.85%   |
| K8 Hammer        | 36       | 2.28%   |
| Zen 3            | 35       | 2.22%   |
| CometLake        | 35       | 2.22%   |
| NetBurst         | 33       | 2.09%   |
| Nehalem          | 27       | 1.71%   |
| Silvermont       | 15       | 0.95%   |
| Steamroller      | 13       | 0.82%   |
| Unknown          | 12       | 0.76%   |
| Icelake          | 7        | 0.44%   |
| Goldmont plus    | 7        | 0.44%   |
| Bulldozer        | 7        | 0.44%   |
| Bonnell          | 7        | 0.44%   |
| K10 Llano        | 6        | 0.38%   |
| Goldmont         | 6        | 0.38%   |
| Broadwell        | 6        | 0.38%   |
| Puma             | 4        | 0.25%   |
| Jaguar           | 3        | 0.19%   |
| TigerLake        | 2        | 0.13%   |
| Excavator        | 2        | 0.13%   |
| K6               | 1        | 0.06%   |
| Bobcat           | 1        | 0.06%   |
| Alderlake Hybrid | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 722      | 43.03%  |
| Intel                                        | 511      | 30.45%  |
| AMD                                          | 424      | 25.27%  |
| VIA Technologies                             | 5        | 0.3%    |
| Silicon Integrated Systems [SiS]             | 5        | 0.3%    |
| Matrox Electronics Systems                   | 4        | 0.24%   |
| ASPEED Technology                            | 4        | 0.24%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.06%   |
| Silicon Motion                               | 1        | 0.06%   |
| ATI Technologies                             | 1        | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 91       | 5.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 86       | 4.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 60       | 3.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 55       | 3.17%   |
| Nvidia GT218 [GeForce 210]                                                               | 53       | 3.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 46       | 2.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40       | 2.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39       | 2.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 35       | 2.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33       | 1.9%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 26       | 1.5%    |
| Intel HD Graphics 630                                                                    | 26       | 1.5%    |
| Intel HD Graphics 530                                                                    | 24       | 1.38%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 23       | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 22       | 1.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 21       | 1.21%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 20       | 1.15%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 19       | 1.1%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 18       | 1.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18       | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18       | 1.04%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 17       | 0.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 17       | 0.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 16       | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 16       | 0.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15       | 0.86%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 14       | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 13       | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 13       | 0.75%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 13       | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13       | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 12       | 0.69%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 12       | 0.69%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 11       | 0.63%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 10       | 0.58%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 10       | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10       | 0.58%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 10       | 0.58%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 9        | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 9        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Nvidia             | 670      | 42.09%  |
| 1 x Intel              | 429      | 26.95%  |
| 1 x AMD                | 385      | 24.18%  |
| Intel + Nvidia         | 34       | 2.14%   |
| 2 x AMD                | 27       | 1.7%    |
| 2 x Nvidia             | 9        | 0.57%   |
| AMD + Nvidia           | 9        | 0.57%   |
| 1 x VIA                | 5        | 0.31%   |
| 1 x SiS                | 5        | 0.31%   |
| Intel + AMD            | 5        | 0.31%   |
| 1 x ASPEED             | 4        | 0.25%   |
| 1 x Matrox             | 3        | 0.19%   |
| Other                  | 1        | 0.06%   |
| 3 x AMD                | 1        | 0.06%   |
| 1 x XGI                | 1        | 0.06%   |
| 1 x Silicon Motion     | 1        | 0.06%   |
| Nvidia + Matrox        | 1        | 0.06%   |
| 1 x Intel + 3 x Nvidia | 1        | 0.06%   |
| Intel + 2 x AMD        | 1        | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1166     | 72.51%  |
| Proprietary | 374      | 23.26%  |
| Unknown     | 68       | 4.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 597      | 36.58%  |
| 1.01-2.0   | 286      | 17.52%  |
| 0.51-1.0   | 188      | 11.52%  |
| 0.01-0.5   | 186      | 11.4%   |
| 3.01-4.0   | 157      | 9.62%   |
| 7.01-8.0   | 132      | 8.09%   |
| 5.01-6.0   | 43       | 2.63%   |
| 2.01-3.0   | 22       | 1.35%   |
| 8.01-16.0  | 18       | 1.1%    |
| 16.01-24.0 | 3        | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 262      | 16.02%  |
| Goldstar                | 230      | 14.07%  |
| Hewlett-Packard         | 147      | 8.99%   |
| BenQ                    | 128      | 7.83%   |
| Acer                    | 127      | 7.77%   |
| Ancor Communications    | 109      | 6.67%   |
| Dell                    | 102      | 6.24%   |
| Philips                 | 94       | 5.75%   |
| AOC                     | 66       | 4.04%   |
| LG Electronics          | 49       | 3%      |
| Unknown                 | 39       | 2.39%   |
| Sony                    | 21       | 1.28%   |
| Lenovo                  | 21       | 1.28%   |
| HannStar                | 19       | 1.16%   |
| ViewSonic               | 18       | 1.1%    |
| ASUSTek Computer        | 13       | 0.8%    |
| Eizo                    | 11       | 0.67%   |
| OEM                     | 9        | 0.55%   |
| Packard Bell            | 8        | 0.49%   |
| MSI                     | 8        | 0.49%   |
| Chi Mei Optoelectronics | 8        | 0.49%   |
| ___                     | 7        | 0.43%   |
| Vestel Elektronik       | 6        | 0.37%   |
| Hitachi                 | 6        | 0.37%   |
| Xiaomi                  | 5        | 0.31%   |
| Iiyama                  | 5        | 0.31%   |
| HPN                     | 5        | 0.31%   |
| Toshiba                 | 4        | 0.24%   |
| NEC Computers           | 4        | 0.24%   |
| MStar                   | 4        | 0.24%   |
| Fujitsu Siemens         | 4        | 0.24%   |
| Targa Visionary         | 3        | 0.18%   |
| Sunplus                 | 3        | 0.18%   |
| RTK                     | 3        | 0.18%   |
| Plain Tree Systems      | 3        | 0.18%   |
| PKB                     | 3        | 0.18%   |
| Panasonic               | 3        | 0.18%   |
| Microstep               | 3        | 0.18%   |
| Mi                      | 3        | 0.18%   |
| IBM                     | 3        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 10       | 0.57%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch   | 9        | 0.51%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 9        | 0.51%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 9        | 0.51%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 9        | 0.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 9        | 0.51%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 9        | 0.51%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 8        | 0.46%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 8        | 0.46%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 7        | 0.4%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 7        | 0.4%    |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch | 7        | 0.4%    |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 6        | 0.34%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 6        | 0.34%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 6        | 0.34%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 6        | 0.34%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 6        | 0.34%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 6        | 0.34%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch           | 6        | 0.34%   |
| Ancor Communications VX231 ACI22E5 1920x1080 576x324mm 26.0-inch      | 6        | 0.34%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch  | 6        | 0.34%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 5        | 0.29%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 5        | 0.29%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 5        | 0.29%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch | 5        | 0.29%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 5        | 0.29%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 5        | 0.29%   |
| BenQ GL2580 BNQ78E5 1920x1080 544x303mm 24.5-inch                     | 5        | 0.29%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 5        | 0.29%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                       | 5        | 0.29%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 5        | 0.29%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                    | 4        | 0.23%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 4        | 0.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4        | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 4        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.23%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 4        | 0.23%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 4        | 0.23%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch           | 4        | 0.23%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 4        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 729      | 45.45%  |
| 1280x1024 (SXGA)   | 158      | 9.85%   |
| 3840x2160 (4K)     | 100      | 6.23%   |
| 1680x1050 (WSXGA+) | 97       | 6.05%   |
| 2560x1440 (QHD)    | 89       | 5.55%   |
| 1366x768 (WXGA)    | 74       | 4.61%   |
| 1440x900 (WXGA+)   | 71       | 4.43%   |
| Unknown            | 47       | 2.93%   |
| 1920x1200 (WUXGA)  | 37       | 2.31%   |
| 1360x768           | 32       | 2%      |
| 2560x1080          | 31       | 1.93%   |
| 1600x900 (HD+)     | 29       | 1.81%   |
| 3440x1440          | 15       | 0.94%   |
| 1024x768 (XGA)     | 14       | 0.87%   |
| 3840x1080          | 12       | 0.75%   |
| 1920x540           | 8        | 0.5%    |
| 1600x1200          | 8        | 0.5%    |
| 4480x1080          | 4        | 0.25%   |
| 3200x1080          | 4        | 0.25%   |
| 3600x1080          | 3        | 0.19%   |
| 3360x1080          | 3        | 0.19%   |
| 2960x1050          | 3        | 0.19%   |
| 2048x1152          | 3        | 0.19%   |
| 5760x2160          | 2        | 0.12%   |
| 4480x1440          | 2        | 0.12%   |
| 3840x1200          | 2        | 0.12%   |
| 2944x1080          | 2        | 0.12%   |
| 2560x1024          | 2        | 0.12%   |
| 2288x1287          | 2        | 0.12%   |
| 800x480            | 1        | 0.06%   |
| 7920x1440          | 1        | 0.06%   |
| 7680x2160          | 1        | 0.06%   |
| 5760x1200          | 1        | 0.06%   |
| 5520x1080          | 1        | 0.06%   |
| 5504x1440          | 1        | 0.06%   |
| 5120x1080          | 1        | 0.06%   |
| 4800x900           | 1        | 0.06%   |
| 4240x1440          | 1        | 0.06%   |
| 3520x1080          | 1        | 0.06%   |
| 3360x1200          | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 220      | 13.52%  |
| Unknown | 219      | 13.46%  |
| 24      | 202      | 12.42%  |
| 27      | 181      | 11.12%  |
| 23      | 165      | 10.14%  |
| 19      | 118      | 7.25%   |
| 18      | 90       | 5.53%   |
| 17      | 89       | 5.47%   |
| 22      | 67       | 4.12%   |
| 34      | 40       | 2.46%   |
| 20      | 40       | 2.46%   |
| 31      | 32       | 1.97%   |
| 84      | 22       | 1.35%   |
| 15      | 19       | 1.17%   |
| 32      | 16       | 0.98%   |
| 25      | 14       | 0.86%   |
| 72      | 13       | 0.8%    |
| 26      | 13       | 0.8%    |
| 54      | 12       | 0.74%   |
| 40      | 7        | 0.43%   |
| 28      | 5        | 0.31%   |
| 12      | 5        | 0.31%   |
| 52      | 4        | 0.25%   |
| 65      | 3        | 0.18%   |
| 60      | 3        | 0.18%   |
| 48      | 3        | 0.18%   |
| 33      | 3        | 0.18%   |
| 142     | 2        | 0.12%   |
| 47      | 2        | 0.12%   |
| 46      | 2        | 0.12%   |
| 43      | 2        | 0.12%   |
| 42      | 2        | 0.12%   |
| 39      | 2        | 0.12%   |
| 29      | 2        | 0.12%   |
| 13      | 2        | 0.12%   |
| 75      | 1        | 0.06%   |
| 63      | 1        | 0.06%   |
| 37      | 1        | 0.06%   |
| 36      | 1        | 0.06%   |
| 35      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 499      | 31.72%  |
| 401-500        | 477      | 30.32%  |
| Unknown        | 219      | 13.92%  |
| 301-350        | 107      | 6.8%    |
| 601-700        | 62       | 3.94%   |
| 351-400        | 62       | 3.94%   |
| 701-800        | 57       | 3.62%   |
| 1501-2000      | 36       | 2.29%   |
| 1001-1500      | 30       | 1.91%   |
| 801-900        | 11       | 0.7%    |
| 201-300        | 6        | 0.38%   |
| 901-1000       | 4        | 0.25%   |
| More than 2000 | 2        | 0.13%   |
| 1-100          | 1        | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 906      | 59.25%  |
| 16/10   | 197      | 12.88%  |
| Unknown | 192      | 12.56%  |
| 5/4     | 144      | 9.42%   |
| 21/9    | 42       | 2.75%   |
| 4/3     | 32       | 2.09%   |
| 3/2     | 10       | 0.65%   |
| 32/9    | 2        | 0.13%   |
| 1.00    | 2        | 0.13%   |
| 6/5     | 1        | 0.07%   |
| 2.00    | 1        | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 529      | 33.08%  |
| 151-200        | 227      | 14.2%   |
| Unknown        | 219      | 13.7%   |
| 301-350        | 185      | 11.57%  |
| 141-150        | 160      | 10.01%  |
| 351-500        | 92       | 5.75%   |
| 251-300        | 75       | 4.69%   |
| More than 1000 | 63       | 3.94%   |
| 501-1000       | 21       | 1.31%   |
| 101-110        | 12       | 0.75%   |
| 111-120        | 7        | 0.44%   |
| 71-80          | 5        | 0.31%   |
| 81-90          | 1        | 0.06%   |
| 61-70          | 1        | 0.06%   |
| 1-40           | 1        | 0.06%   |
| 121-130        | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 908      | 59%     |
| 101-120       | 298      | 19.36%  |
| Unknown       | 219      | 14.23%  |
| 1-50          | 50       | 3.25%   |
| 121-160       | 43       | 2.79%   |
| 161-240       | 20       | 1.3%    |
| More than 240 | 1        | 0.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1288     | 79.9%   |
| 2     | 213      | 13.21%  |
| 0     | 87       | 5.4%    |
| 3     | 23       | 1.43%   |
| 4     | 1        | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1001     | 45.5%   |
| Intel                            | 528      | 24%     |
| Qualcomm Atheros                 | 180      | 8.18%   |
| Ralink Technology                | 69       | 3.14%   |
| TP-Link                          | 60       | 2.73%   |
| Nvidia                           | 58       | 2.64%   |
| Broadcom                         | 58       | 2.64%   |
| Qualcomm Atheros Communications  | 32       | 1.45%   |
| Marvell Technology Group         | 27       | 1.23%   |
| Ralink                           | 23       | 1.05%   |
| D-Link                           | 17       | 0.77%   |
| VIA Technologies                 | 13       | 0.59%   |
| D-Link System                    | 13       | 0.59%   |
| Broadcom Limited                 | 11       | 0.5%    |
| ASUSTek Computer                 | 11       | 0.5%    |
| Xiaomi                           | 9        | 0.41%   |
| Belkin Components                | 8        | 0.36%   |
| Samsung Electronics              | 7        | 0.32%   |
| Microsoft                        | 7        | 0.32%   |
| ZyDAS                            | 5        | 0.23%   |
| Silicon Integrated Systems [SiS] | 5        | 0.23%   |
| Qualcomm                         | 5        | 0.23%   |
| Texas Instruments                | 3        | 0.14%   |
| MediaTek                         | 3        | 0.14%   |
| Gemtek                           | 3        | 0.14%   |
| DisplayLink                      | 3        | 0.14%   |
| ASIX Electronics                 | 3        | 0.14%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.09%   |
| NetGear                          | 2        | 0.09%   |
| Microchip Technology             | 2        | 0.09%   |
| Linksys                          | 2        | 0.09%   |
| Huawei Technologies              | 2        | 0.09%   |
| Aquantia                         | 2        | 0.09%   |
| Apple                            | 2        | 0.09%   |
| Accton Technology                | 2        | 0.09%   |
| 3Com                             | 2        | 0.09%   |
| ZyXEL Communications             | 1        | 0.05%   |
| Wilocity                         | 1        | 0.05%   |
| Wacom                            | 1        | 0.05%   |
| TRENDnet                         | 1        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 824      | 34.02%  |
| Intel I211 Gigabit Network Connection                             | 72       | 2.97%   |
| Intel Ethernet Connection (2) I219-V                              | 66       | 2.73%   |
| Intel Wi-Fi 6 AX200                                               | 62       | 2.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 47       | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45       | 1.86%   |
| Realtek 802.11ac NIC                                              | 33       | 1.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31       | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                   | 28       | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 28       | 1.16%   |
| Nvidia MCP61 Ethernet                                             | 26       | 1.07%   |
| Intel 82579V Gigabit Network Connection                           | 25       | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 22       | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 22       | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22       | 0.91%   |
| Intel Ethernet Connection I217-LM                                 | 22       | 0.91%   |
| Intel Ethernet Connection (2) I218-V                              | 22       | 0.91%   |
| Intel Ethernet Controller I225-V                                  | 19       | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 17       | 0.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 16       | 0.66%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 16       | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 16       | 0.66%   |
| Intel Wireless 3165                                               | 16       | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 15       | 0.62%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 15       | 0.62%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 14       | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 14       | 0.58%   |
| Intel Wireless-AC 9260                                            | 14       | 0.58%   |
| Intel Wireless 7265                                               | 13       | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13       | 0.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 12       | 0.5%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 12       | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 12       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12       | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 12       | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 12       | 0.5%    |
| Realtek RTL8187 Wireless Adapter                                  | 11       | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 161      | 22.93%  |
| Intel                           | 161      | 22.93%  |
| Qualcomm Atheros                | 89       | 12.68%  |
| Ralink Technology               | 69       | 9.83%   |
| TP-Link                         | 57       | 8.12%   |
| Qualcomm Atheros Communications | 32       | 4.56%   |
| Broadcom                        | 27       | 3.85%   |
| Ralink                          | 23       | 3.28%   |
| D-Link                          | 17       | 2.42%   |
| ASUSTek Computer                | 11       | 1.57%   |
| Belkin Components               | 8        | 1.14%   |
| Microsoft                       | 7        | 1%      |
| D-Link System                   | 7        | 1%      |
| ZyDAS                           | 5        | 0.71%   |
| Broadcom Limited                | 4        | 0.57%   |
| Texas Instruments               | 3        | 0.43%   |
| Gemtek                          | 3        | 0.43%   |
| NetGear                         | 2        | 0.28%   |
| MediaTek                        | 2        | 0.28%   |
| Linksys                         | 2        | 0.28%   |
| ZyXEL Communications            | 1        | 0.14%   |
| Xiaomi                          | 1        | 0.14%   |
| Wilocity                        | 1        | 0.14%   |
| Wacom                           | 1        | 0.14%   |
| TRENDnet                        | 1        | 0.14%   |
| Tenda                           | 1        | 0.14%   |
| Standard Microsystems           | 1        | 0.14%   |
| Sitecom Europe                  | 1        | 0.14%   |
| Samsung Electronics             | 1        | 0.14%   |
| Marvell Technology Group        | 1        | 0.14%   |
| Edimax Technology               | 1        | 0.14%   |
| 3Com                            | 1        | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 62       | 8.72%   |
| Realtek 802.11ac NIC                                           | 33       | 4.64%   |
| Qualcomm Atheros AR9271 802.11n                                | 28       | 3.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 22       | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22       | 3.09%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 16       | 2.25%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 16       | 2.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 16       | 2.25%   |
| Intel Wireless 3165                                            | 16       | 2.25%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 14       | 1.97%   |
| Intel Wireless-AC 9260                                         | 14       | 1.97%   |
| Intel Wireless 7265                                            | 13       | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13       | 1.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 12       | 1.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 12       | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12       | 1.69%   |
| Realtek RTL8187 Wireless Adapter                               | 11       | 1.55%   |
| Ralink MT7601U Wireless Adapter                                | 11       | 1.55%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 10       | 1.41%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 10       | 1.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 10       | 1.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 9        | 1.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 1.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 9        | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8        | 1.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 8        | 1.13%   |
| Ralink RT5370 Wireless Adapter                                 | 8        | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7        | 0.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 6        | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 6        | 0.84%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 6        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6        | 0.84%   |
| D-Link 802.11 n WLAN                                           | 6        | 0.84%   |
| TP-Link 802.11ac WLAN Adapter                                  | 5        | 0.7%    |
| TP-Link 802.11ac NIC                                           | 5        | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5        | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 5        | 0.7%    |
| Ralink RT2561/RT61 rev B 802.11g                               | 5        | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 938      | 56.44%  |
| Intel                                  | 433      | 26.05%  |
| Qualcomm Atheros                       | 98       | 5.9%    |
| Nvidia                                 | 58       | 3.49%   |
| Broadcom                               | 31       | 1.87%   |
| Marvell Technology Group               | 27       | 1.62%   |
| VIA Technologies                       | 13       | 0.78%   |
| Xiaomi                                 | 8        | 0.48%   |
| Broadcom Limited                       | 7        | 0.42%   |
| Samsung Electronics                    | 6        | 0.36%   |
| D-Link System                          | 6        | 0.36%   |
| Silicon Integrated Systems [SiS]       | 5        | 0.3%    |
| Qualcomm                               | 5        | 0.3%    |
| TP-Link                                | 3        | 0.18%   |
| DisplayLink                            | 3        | 0.18%   |
| ASIX Electronics                       | 3        | 0.18%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.12%   |
| Aquantia                               | 2        | 0.12%   |
| Apple                                  | 2        | 0.12%   |
| Accton Technology                      | 2        | 0.12%   |
| Spreadtrum Communications              | 1        | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.06%   |
| Microchip Technology                   | 1        | 0.06%   |
| Meizu                                  | 1        | 0.06%   |
| MediaTek                               | 1        | 0.06%   |
| Huawei Technologies                    | 1        | 0.06%   |
| Davicom Semiconductor                  | 1        | 0.06%   |
| American Megatrends                    | 1        | 0.06%   |
| ADMtek                                 | 1        | 0.06%   |
| 3Com                                   | 1        | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 824      | 48.44%  |
| Intel I211 Gigabit Network Connection                             | 72       | 4.23%   |
| Intel Ethernet Connection (2) I219-V                              | 66       | 3.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 47       | 2.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45       | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31       | 1.82%   |
| Intel Ethernet Connection (7) I219-V                              | 28       | 1.65%   |
| Nvidia MCP61 Ethernet                                             | 26       | 1.53%   |
| Intel 82579V Gigabit Network Connection                           | 25       | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 22       | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 22       | 1.29%   |
| Intel Ethernet Connection (2) I218-V                              | 22       | 1.29%   |
| Intel Ethernet Controller I225-V                                  | 19       | 1.12%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 17       | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 15       | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 15       | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 14       | 0.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 12       | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12       | 0.71%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 12       | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 12       | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11       | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 11       | 0.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 10       | 0.59%   |
| Nvidia MCP73 Ethernet                                             | 9        | 0.53%   |
| Intel 82578DC Gigabit Network Connection                          | 9        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8        | 0.47%   |
| Nvidia MCP77 Ethernet                                             | 8        | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7        | 0.41%   |
| Intel NM10/ICH7 Family LAN Controller                             | 7        | 0.41%   |
| Intel Ethernet Connection (11) I219-V                             | 7        | 0.41%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.35%   |
| Intel I210 Gigabit Network Connection                             | 6        | 0.35%   |
| Intel 82578DM Gigabit Network Connection                          | 6        | 0.35%   |
| Intel 82567V-2 Gigabit Network Connection                         | 6        | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1561     | 70.6%   |
| WiFi     | 640      | 28.95%  |
| Modem    | 7        | 0.32%   |
| Unknown  | 3        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1247     | 76.46%  |
| WiFi     | 383      | 23.48%  |
| Modem    | 1        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1121     | 70.68%  |
| 2     | 411      | 25.91%  |
| 3     | 39       | 2.46%   |
| 0     | 8        | 0.5%    |
| 4     | 4        | 0.25%   |
| 5     | 3        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1525     | 97.01%  |
| Yes  | 47       | 2.99%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 180      | 37.97%  |
| Intel                           | 150      | 31.65%  |
| Realtek Semiconductor           | 37       | 7.81%   |
| ASUSTek Computer                | 29       | 6.12%   |
| Broadcom                        | 23       | 4.85%   |
| IMC Networks                    | 10       | 2.11%   |
| Qualcomm Atheros Communications | 9        | 1.9%    |
| Belkin Components               | 9        | 1.9%    |
| Integrated System Solution      | 7        | 1.48%   |
| Apple                           | 7        | 1.48%   |
| TP-Link                         | 2        | 0.42%   |
| Roper                           | 2        | 0.42%   |
| Edimax Technology               | 2        | 0.42%   |
| Dell                            | 2        | 0.42%   |
| Sitecom Europe                  | 1        | 0.21%   |
| MediaTek                        | 1        | 0.21%   |
| Logitech                        | 1        | 0.21%   |
| Lite-On Technology              | 1        | 0.21%   |
| Corsair                         | 1        | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 180      | 37.97%  |
| Intel AX200 Bluetooth                                     | 61       | 12.87%  |
| Intel Bluetooth wireless interface                        | 37       | 7.81%   |
| Realtek Bluetooth Radio                                   | 33       | 6.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 14       | 2.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 14       | 2.95%   |
| Intel Wireless-AC 3168 Bluetooth                          | 13       | 2.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 11       | 2.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 10       | 2.11%   |
| Intel AX201 Bluetooth                                     | 9        | 1.9%    |
| Integrated System Solution Bluetooth Device               | 7        | 1.48%   |
| IMC Networks Bluetooth Radio                              | 6        | 1.27%   |
| ASUS Bluetooth Radio                                      | 5        | 1.05%   |
| Realtek  Bluetooth 4.2 Adapter                            | 4        | 0.84%   |
| Intel AX210 Bluetooth                                     | 4        | 0.84%   |
| Belkin Components Bluetooth Mini Dongle                   | 4        | 0.84%   |
| Apple Bluetooth USB Host Controller                       | 4        | 0.84%   |
| Qualcomm Atheros  Bluetooth Device                        | 3        | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 3        | 0.63%   |
| Broadcom BCM2035 Bluetooth dongle                         | 3        | 0.63%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter     | 3        | 0.63%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 3        | 0.63%   |
| ASUS BCM20702A0                                           | 3        | 0.63%   |
| TP-Link UB500 Adapter                                     | 2        | 0.42%   |
| Roper Class 1 Bluetooth Dongle                            | 2        | 0.42%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 2        | 0.42%   |
| IMC Networks BCM20702A0                                   | 2        | 0.42%   |
| Broadcom Bluetooth Controller                             | 2        | 0.42%   |
| Broadcom BCM2045 Bluetooth                                | 2        | 0.42%   |
| ASUS Bluetooth Device                                     | 2        | 0.42%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1        | 0.21%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 1        | 0.21%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 1        | 0.21%   |
| MediaTek Wireless_Device                                  | 1        | 0.21%   |
| Logitech Bluetooth wireless hub                           | 1        | 0.21%   |
| Lite-On Bluetooth Device                                  | 1        | 0.21%   |
| IMC Networks Wireless_Device                              | 1        | 0.21%   |
| IMC Networks Bluetooth Device                             | 1        | 0.21%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter               | 1        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 1020     | 40.02%  |
| Nvidia                                          | 639      | 25.07%  |
| AMD                                             | 577      | 22.64%  |
| C-Media Electronics                             | 69       | 2.71%   |
| Creative Labs                                   | 35       | 1.37%   |
| Texas Instruments                               | 16       | 0.63%   |
| Logitech                                        | 15       | 0.59%   |
| VIA Technologies                                | 13       | 0.51%   |
| JMTek                                           | 12       | 0.47%   |
| Focusrite-Novation                              | 11       | 0.43%   |
| Kingston Technology                             | 10       | 0.39%   |
| Corsair                                         | 9        | 0.35%   |
| Silicon Integrated Systems [SiS]                | 7        | 0.27%   |
| GN Netcom                                       | 7        | 0.27%   |
| Creative Technology                             | 7        | 0.27%   |
| Generalplus Technology                          | 6        | 0.24%   |
| Ensoniq                                         | 6        | 0.24%   |
| ASUSTek Computer                                | 6        | 0.24%   |
| Plantronics                                     | 5        | 0.2%    |
| M-Audio                                         | 5        | 0.2%    |
| Yamaha                                          | 4        | 0.16%   |
| SteelSeries ApS                                 | 4        | 0.16%   |
| Tenx Technology                                 | 3        | 0.12%   |
| SAVITECH                                        | 3        | 0.12%   |
| Realtek Semiconductor                           | 3        | 0.12%   |
| QinHeng Electronics                             | 3        | 0.12%   |
| DSEA A/S                                        | 3        | 0.12%   |
| BEHRINGER International                         | 3        | 0.12%   |
| XMOS                                            | 2        | 0.08%   |
| Razer USA                                       | 2        | 0.08%   |
| Musical Fidelity                                | 2        | 0.08%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.08%   |
| Hewlett-Packard                                 | 2        | 0.08%   |
| Evolution Electronics                           | 2        | 0.08%   |
| Elite Silicon                                   | 2        | 0.08%   |
| Dell                                            | 2        | 0.08%   |
| Blue Microphones                                | 2        | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.04%   |
| ZOOM                                            | 1        | 0.04%   |
| USB MICROPHONE                                  | 1        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 166      | 5.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 123      | 4.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 117      | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 110      | 3.73%   |
| AMD Starship/Matisse HD Audio Controller                                          | 103      | 3.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 100      | 3.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 98       | 3.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 97       | 3.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 90       | 3.05%   |
| Intel 200 Series PCH HD Audio                                                     | 85       | 2.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 81       | 2.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 75       | 2.54%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 68       | 2.31%   |
| Nvidia High Definition Audio Controller                                           | 66       | 2.24%   |
| AMD Family 17h/19h HD Audio Controller                                            | 57       | 1.93%   |
| AMD FCH Azalia Controller                                                         | 55       | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                        | 51       | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 49       | 1.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 47       | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 41       | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 36       | 1.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 34       | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                                     | 31       | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                                     | 29       | 0.98%   |
| AMD Navi 10 HDMI Audio                                                            | 29       | 0.98%   |
| Nvidia MCP61 High Definition Audio                                                | 28       | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 28       | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                     | 26       | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 26       | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                                | 25       | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 25       | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                                     | 23       | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                     | 22       | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 22       | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                                     | 21       | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                                     | 21       | 0.71%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 19       | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                     | 18       | 0.61%   |
| Intel Comet Lake PCH cAVS                                                         | 18       | 0.61%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 17       | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 206      | 27.21%  |
| Unknown             | 133      | 17.57%  |
| Corsair             | 81       | 10.7%   |
| Crucial             | 78       | 10.3%   |
| Samsung Electronics | 61       | 8.06%   |
| G.Skill             | 58       | 7.66%   |
| SK hynix            | 45       | 5.94%   |
| Micron Technology   | 20       | 2.64%   |
| Elpida              | 9        | 1.19%   |
| Ramaxel Technology  | 6        | 0.79%   |
| Nanya Technology    | 6        | 0.79%   |
| Unifosa             | 5        | 0.66%   |
| Silicon Power       | 5        | 0.66%   |
| Unknown (ABCD)      | 4        | 0.53%   |
| Team                | 4        | 0.53%   |
| Goodram             | 3        | 0.4%    |
| ASint Technology    | 3        | 0.4%    |
| Unknown             | 3        | 0.4%    |
| Transcend           | 2        | 0.26%   |
| Patriot             | 2        | 0.26%   |
| Kllisre             | 2        | 0.26%   |
| Exceleram           | 2        | 0.26%   |
| Atermiter           | 2        | 0.26%   |
| Apacer              | 2        | 0.26%   |
| Wilk                | 1        | 0.13%   |
| Unknown (AB)        | 1        | 0.13%   |
| Unknown (07FB)      | 1        | 0.13%   |
| Thermaltake         | 1        | 0.13%   |
| Qimonda             | 1        | 0.13%   |
| PNY                 | 1        | 0.13%   |
| Pioneer             | 1        | 0.13%   |
| Neo Forza           | 1        | 0.13%   |
| Innodisk            | 1        | 0.13%   |
| Huanan              | 1        | 0.13%   |
| Goldkey             | 1        | 0.13%   |
| GeIL                | 1        | 0.13%   |
| CompuStocx          | 1        | 0.13%   |
| Axiom               | 1        | 0.13%   |
| 48spaces            | 1        | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s           | 17       | 1.96%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s             | 11       | 1.27%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s        | 11       | 1.27%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s             | 10       | 1.15%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s           | 10       | 1.15%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                         | 8        | 0.92%   |
| Unknown RAM Module 2GB DIMM 800MT/s                             | 8        | 0.92%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 8        | 0.92%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s           | 8        | 0.92%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                        | 7        | 0.81%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 7        | 0.81%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                         | 7        | 0.81%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 7        | 0.81%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 6        | 0.69%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s             | 6        | 0.69%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s           | 6        | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                       | 5        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                        | 5        | 0.58%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                          | 5        | 0.58%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s               | 5        | 0.58%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s               | 5        | 0.58%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s             | 5        | 0.58%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s           | 5        | 0.58%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s          | 5        | 0.58%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s           | 5        | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 4        | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                     | 4        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB DIMM DDR3 2133MT/s | 4        | 0.46%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s             | 4        | 0.46%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s             | 4        | 0.46%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3                    | 4        | 0.46%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s           | 4        | 0.46%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1867MT/s            | 4        | 0.46%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s            | 4        | 0.46%   |
| Unknown RAM Module 2GB DIMM 667MT/s                             | 3        | 0.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM                            | 3        | 0.35%   |
| Unknown RAM Module 1GB DIMM 800MT/s                             | 3        | 0.35%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                     | 3        | 0.35%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                     | 3        | 0.35%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                          | 3        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 290      | 42.46%  |
| DDR3    | 239      | 34.99%  |
| Unknown | 61       | 8.93%   |
| DDR2    | 50       | 7.32%   |
| SDRAM   | 31       | 4.54%   |
| DDR     | 8        | 1.17%   |
| LPDDR4  | 4        | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 631      | 93.62%  |
| SODIMM  | 40       | 5.93%   |
| FB-DIMM | 2        | 0.3%    |
| RIMM    | 1        | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 256      | 33.86%  |
| 4096  | 203      | 26.85%  |
| 2048  | 141      | 18.65%  |
| 16384 | 94       | 12.43%  |
| 1024  | 48       | 6.35%   |
| 32768 | 10       | 1.32%   |
| 512   | 4        | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 130      | 17.22%  |
| 1333    | 96       | 12.72%  |
| 2400    | 65       | 8.61%   |
| 3200    | 55       | 7.28%   |
| 3600    | 53       | 7.02%   |
| 800     | 52       | 6.89%   |
| 2133    | 39       | 5.17%   |
| 2667    | 34       | 4.5%    |
| 667     | 30       | 3.97%   |
| 1867    | 26       | 3.44%   |
| 3466    | 24       | 3.18%   |
| 2933    | 17       | 2.25%   |
| 1866    | 16       | 2.12%   |
| Unknown | 14       | 1.85%   |
| 2733    | 12       | 1.59%   |
| 1334    | 8        | 1.06%   |
| 3000    | 7        | 0.93%   |
| 1066    | 7        | 0.93%   |
| 3400    | 6        | 0.79%   |
| 3266    | 6        | 0.79%   |
| 2666    | 5        | 0.66%   |
| 400     | 5        | 0.66%   |
| 3800    | 4        | 0.53%   |
| 3500    | 4        | 0.53%   |
| 2048    | 4        | 0.53%   |
| 1800    | 4        | 0.53%   |
| 3733    | 3        | 0.4%    |
| 1639    | 3        | 0.4%    |
| 533     | 3        | 0.4%    |
| 4199    | 2        | 0.26%   |
| 2800    | 2        | 0.26%   |
| 333     | 2        | 0.26%   |
| 200     | 2        | 0.26%   |
| 57535   | 1        | 0.13%   |
| 8400    | 1        | 0.13%   |
| 4133    | 1        | 0.13%   |
| 3666    | 1        | 0.13%   |
| 3533    | 1        | 0.13%   |
| 3334    | 1        | 0.13%   |
| 3333    | 1        | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 41       | 49.4%   |
| Brother Industries       | 14       | 16.87%  |
| Samsung Electronics      | 9        | 10.84%  |
| Canon                    | 6        | 7.23%   |
| Seiko Epson              | 4        | 4.82%   |
| Oki Data                 | 2        | 2.41%   |
| Dymo-CoStar              | 2        | 2.41%   |
| Ricoh                    | 1        | 1.2%    |
| Magic Control Technology | 1        | 1.2%    |
| Lexmark International    | 1        | 1.2%    |
| Kyocera                  | 1        | 1.2%    |
| Apple                    | 1        | 1.2%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| HP LaserJet 1018                                | 4        | 4.76%   |
| Brother HL-2030 Laser Printer                   | 4        | 4.76%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2        | 2.38%   |
| Samsung M2070 Series                            | 2        | 2.38%   |
| Oki Data USB Device                             | 2        | 2.38%   |
| HP LaserJet 1010                                | 2        | 2.38%   |
| HP ENVY 5000 series                             | 2        | 2.38%   |
| HP ENVY 4520 series                             | 2        | 2.38%   |
| HP DeskJet F2492 All-in-One                     | 2        | 2.38%   |
| HP DeskJet 5550                                 | 2        | 2.38%   |
| HP DeskJet 3630 series                          | 2        | 2.38%   |
| HP DeskJet 2620 All-in-One Printer              | 2        | 2.38%   |
| HP Deskjet 1050 J410                            | 2        | 2.38%   |
| Dymo-CoStar LabelWriter 450                     | 2        | 2.38%   |
| Brother Printer                                 | 2        | 2.38%   |
| Brother DCP-1510                                | 2        | 2.38%   |
| Seiko Epson XP-255 257 Series                   | 1        | 1.19%   |
| Seiko Epson XP-225 Series                       | 1        | 1.19%   |
| Seiko Epson WF-2830 Series                      | 1        | 1.19%   |
| Seiko Epson L1300 Series                        | 1        | 1.19%   |
| Samsung SCX-4300 Series                         | 1        | 1.19%   |
| Samsung SCX-3400 Series                         | 1        | 1.19%   |
| Samsung SCX-3200 Series                         | 1        | 1.19%   |
| Samsung ML-1640 Series Laser Printer            | 1        | 1.19%   |
| Samsung M267x 287x Series                       | 1        | 1.19%   |
| Ricoh SP 112                                    | 1        | 1.19%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1        | 1.19%   |
| Lexmark International B2236dw                   | 1        | 1.19%   |
| Kyocera ECOSYS M5521cdn                         | 1        | 1.19%   |
| HP PSC-1315/PSC-1317                            | 1        | 1.19%   |
| HP Officejet J4500 series                       | 1        | 1.19%   |
| HP OfficeJet 4650 series                        | 1        | 1.19%   |
| HP LaserJet Pro M118-M119                       | 1        | 1.19%   |
| HP LaserJet M14-M17                             | 1        | 1.19%   |
| HP LaserJet 1300                                | 1        | 1.19%   |
| HP LaserJet 1200                                | 1        | 1.19%   |
| HP LaserJet 1020                                | 1        | 1.19%   |
| HP ENVY 5540 series                             | 1        | 1.19%   |
| HP ENVY 4500 series                             | 1        | 1.19%   |
| HP DeskJet F4200 series                         | 1        | 1.19%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 11       | 40.74%  |
| Hewlett-Packard             | 7        | 25.93%  |
| Seiko Epson                 | 5        | 18.52%  |
| Acer Peripherals (now BenQ) | 2        | 7.41%   |
| Mustek Systems              | 1        | 3.7%    |
| KYE Systems (Mouse Systems) | 1        | 3.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 3        | 11.11%  |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2        | 7.41%   |
| HP Scanjet 300                                           | 2        | 7.41%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 7.41%   |
| Canon CanoScan N650U/N656U                               | 2        | 7.41%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2        | 7.41%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1        | 3.7%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 3.7%    |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1        | 3.7%    |
| Mustek Systems ScanExpress 1200 CU                       | 1        | 3.7%    |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1        | 3.7%    |
| HP Scanjet N6010                                         | 1        | 3.7%    |
| HP ScanJet 5200c                                         | 1        | 3.7%    |
| HP ScanJet 4570c                                         | 1        | 3.7%    |
| HP ScanJet 3570c                                         | 1        | 3.7%    |
| HP ScanJet 3300c                                         | 1        | 3.7%    |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 3.7%    |
| Canon CanoScan LiDE 700F                                 | 1        | 3.7%    |
| Canon CanoScan LIDE 25                                   | 1        | 3.7%    |
| Canon CanoScan LiDE 220                                  | 1        | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 90       | 33.58%  |
| Sunplus Innovation Technology | 18       | 6.72%   |
| Microdia                      | 18       | 6.72%   |
| Creative Technology           | 13       | 4.85%   |
| Realtek Semiconductor         | 10       | 3.73%   |
| Generalplus Technology        | 10       | 3.73%   |
| Z-Star Microelectronics       | 7        | 2.61%   |
| Samsung Electronics           | 7        | 2.61%   |
| Chicony Electronics           | 7        | 2.61%   |
| Microsoft                     | 6        | 2.24%   |
| GEMBIRD                       | 6        | 2.24%   |
| Jieli Technology              | 5        | 1.87%   |
| Cubeternet                    | 4        | 1.49%   |
| Arkmicro Technologies         | 4        | 1.49%   |
| ARC International             | 4        | 1.49%   |
| Apple                         | 4        | 1.49%   |
| Alcor Micro                   | 4        | 1.49%   |
| 2M UVC CAMERA                 | 4        | 1.49%   |
| SJ-180517-N                   | 3        | 1.12%   |
| Guillemot                     | 3        | 1.12%   |
| Aveo Technology               | 3        | 1.12%   |
| Xiongmai                      | 2        | 0.75%   |
| WCM_USB                       | 2        | 0.75%   |
| KYE Systems (Mouse Systems)   | 2        | 0.75%   |
| IMC Networks                  | 2        | 0.75%   |
| Huawei Technologies           | 2        | 0.75%   |
| Google                        | 2        | 0.75%   |
| FPL-2053-191010               | 2        | 0.75%   |
| AVerMedia Technologies        | 2        | 0.75%   |
| Xiaomi                        | 1        | 0.37%   |
| Unknown                       | 1        | 0.37%   |
| TANDBERG                      | 1        | 0.37%   |
| SunplusIT                     | 1        | 0.37%   |
| Sunplus Technology            | 1        | 0.37%   |
| Sunplus IT                    | 1        | 0.37%   |
| Sonix Technology              | 1        | 0.37%   |
| Solid Year                    | 1        | 0.37%   |
| SiGma Micro                   | 1        | 0.37%   |
| Razer USA                     | 1        | 0.37%   |
| Pixart Imaging                | 1        | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 23       | 8.55%   |
| Logitech HD Pro Webcam C920                       | 10       | 3.72%   |
| Logitech Webcam C170                              | 9        | 3.35%   |
| Logitech Webcam C310                              | 8        | 2.97%   |
| Samsung Galaxy A5 (MTP)                           | 7        | 2.6%    |
| Microdia Webcam Vitade AF                         | 7        | 2.6%    |
| Logitech Webcam C200                              | 7        | 2.6%    |
| Logitech HD Webcam C525                           | 7        | 2.6%    |
| Generalplus GENERAL WEBCAM                        | 7        | 2.6%    |
| Creative Live! Cam Sync HD [VF0770]               | 6        | 2.23%   |
| Realtek FULL HD 1080P Webcam                      | 5        | 1.86%   |
| Jieli USB PHY 2.0                                 | 5        | 1.86%   |
| Creative Live! Cam Chat HD [VF0700]               | 5        | 1.86%   |
| Sunplus PAPALOOK_229AF                            | 4        | 1.49%   |
| ARC International Camera                          | 4        | 1.49%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam               | 4        | 1.49%   |
| Z-Star Venus USB2.0 Camera                        | 3        | 1.12%   |
| Sunplus Canyon CNS-CWC5 Webcam                    | 3        | 1.12%   |
| Sunplus Aukey-PC-LM1E Camera                      | 3        | 1.12%   |
| SJ-180517-N 1080P Webcam                          | 3        | 1.12%   |
| Microsoft LifeCam HD-3000                         | 3        | 1.12%   |
| Microdia Integrated Camera                        | 3        | 1.12%   |
| Logitech Webcam C210                              | 3        | 1.12%   |
| Logitech QuickCam Pro 9000                        | 3        | 1.12%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 3        | 1.12%   |
| GEMBIRD USB2.0 PC CAMERA                          | 3        | 1.12%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 1.12%   |
| Chicony HP High Definition 1MP Webcam             | 3        | 1.12%   |
| Arkmicro USB2.0 PC CAMERA                         | 3        | 1.12%   |
| Apple iPhone5/5C/5S/6                             | 3        | 1.12%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 2        | 0.74%   |
| Xiongmai web camera                               | 2        | 0.74%   |
| WCM_USB WEB CAM                                   | 2        | 0.74%   |
| Sunplus AUSDOM FHD Camera                         | 2        | 0.74%   |
| Microdia USB Live camera                          | 2        | 0.74%   |
| Logitech QuickCam Orbit/Sphere AF                 | 2        | 0.74%   |
| Logitech QuickCam E 3500                          | 2        | 0.74%   |
| Logitech HD Webcam C615                           | 2        | 0.74%   |
| Logitech C922 Pro Stream Webcam                   | 2        | 0.74%   |
| Huawei HiCamera                                   | 2        | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Alcor Micro               | 14       | 37.84%  |
| Advanced Card Systems     | 7        | 18.92%  |
| Chicony Electronics       | 4        | 10.81%  |
| Realtek Semiconductor     | 2        | 5.41%   |
| OmniKey                   | 2        | 5.41%   |
| Hewlett-Packard           | 2        | 5.41%   |
| Cherry                    | 2        | 5.41%   |
| SCM Microsystems          | 1        | 2.7%    |
| Gemalto (was Gemplus)     | 1        | 2.7%    |
| Fujitsu Siemens Computers | 1        | 2.7%    |
| C3PO                      | 1        | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 10       | 27.03%  |
| Advanced Card Systems ACR38 SmartCard Reader           | 5        | 13.51%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 4        | 10.81%  |
| Alcor Micro Watchdata W 1981                           | 4        | 10.81%  |
| Realtek Semiconductor Smart Card Reader Interface      | 2        | 5.41%   |
| OmniKey CardMan 3021 / 3121                            | 2        | 5.41%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)          | 2        | 5.41%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 2.7%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 2.7%    |
| Fujitsu Siemens Computers SmartCard Reader 2A          | 1        | 2.7%    |
| Cherry SmartTerminal XX1X                              | 1        | 2.7%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC            | 1        | 2.7%    |
| C3PO LTC31v2                                           | 1        | 2.7%    |
| Advanced Card Systems ACR39U                           | 1        | 2.7%    |
| Advanced Card Systems ACR122U                          | 1        | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1375     | 85.51%  |
| 1     | 200      | 12.44%  |
| 2     | 26       | 1.62%   |
| 3     | 4        | 0.25%   |
| 9     | 1        | 0.06%   |
| 6     | 1        | 0.06%   |
| 5     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 84       | 31.46%  |
| Net/wireless             | 62       | 23.22%  |
| Chipcard                 | 21       | 7.87%   |
| Unassigned class         | 20       | 7.49%   |
| Multimedia controller    | 15       | 5.62%   |
| Communication controller | 13       | 4.87%   |
| Bluetooth                | 10       | 3.75%   |
| Sound                    | 9        | 3.37%   |
| Network                  | 8        | 3%      |
| Camera                   | 8        | 3%      |
| Card reader              | 5        | 1.87%   |
| Net/ethernet             | 3        | 1.12%   |
| Firewire controller      | 3        | 1.12%   |
| Dvb card                 | 2        | 0.75%   |
| Storage/ide              | 1        | 0.37%   |
| Storage                  | 1        | 0.37%   |
| Modem                    | 1        | 0.37%   |
| Fingerprint reader       | 1        | 0.37%   |

