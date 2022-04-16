openSUSE - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for openSUSE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 932

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | H110M-DVS R2.0              | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7efbdedc5f](https://linux-hardware.org/?probe=7efbdedc5f) | Apr 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [90486ad164](https://linux-hardware.org/?probe=90486ad164) | Apr 15, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [191880e24b](https://linux-hardware.org/?probe=191880e24b) | Apr 14, 2022 |
| Intel         | D54250WYK H13922-303        | [8619f35452](https://linux-hardware.org/?probe=8619f35452) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| MSI           | B450M PRO-M2 MAX            | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| ASUSTek       | H81M-R                      | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| MSI           | H110M PRO-VH PLUS           | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| HP            | 0A9Ch                       | [5a415a150f](https://linux-hardware.org/?probe=5a415a150f) | Apr 05, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Shuttle       | FS35V4                      | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [eedbf6a10e](https://linux-hardware.org/?probe=eedbf6a10e) | Apr 02, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| Gigabyte      | GA-770T-USB3                | [787cb334c2](https://linux-hardware.org/?probe=787cb334c2) | Mar 28, 2022 |
| ASUSTek       | H81M-R                      | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| ASUSTek       | H81M-R                      | [0d4d2c1358](https://linux-hardware.org/?probe=0d4d2c1358) | Mar 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Gigabyte      | X570 GAMING X               | [5c424251c8](https://linux-hardware.org/?probe=5c424251c8) | Mar 24, 2022 |
| Foxconn       | 2ADA                        | [b9aec6129a](https://linux-hardware.org/?probe=b9aec6129a) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [3429bc98ac](https://linux-hardware.org/?probe=3429bc98ac) | Mar 22, 2022 |
| Colorful T... | A320M-K PRO YV14            | [94393a4d0a](https://linux-hardware.org/?probe=94393a4d0a) | Mar 22, 2022 |
| Pegatron      | 2AB6                        | [9e862658aa](https://linux-hardware.org/?probe=9e862658aa) | Mar 22, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Gigabyte      | B75M-D3H                    | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [651e0fb5eb](https://linux-hardware.org/?probe=651e0fb5eb) | Mar 16, 2022 |
| ASRock        | Z370 Gaming K6              | [90bedd5ff6](https://linux-hardware.org/?probe=90bedd5ff6) | Mar 14, 2022 |
| Gigabyte      | W480 VISION D               | [2e45a56117](https://linux-hardware.org/?probe=2e45a56117) | Mar 14, 2022 |
| MSI           | MEG X570 UNIFY              | [ec1783840e](https://linux-hardware.org/?probe=ec1783840e) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | [ef67eef250](https://linux-hardware.org/?probe=ef67eef250) | Mar 13, 2022 |
| ASRock        | H61M-S1 PLUS                | [56c15fcbf6](https://linux-hardware.org/?probe=56c15fcbf6) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | [2e7a87521b](https://linux-hardware.org/?probe=2e7a87521b) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | [a610ee6ad5](https://linux-hardware.org/?probe=a610ee6ad5) | Mar 12, 2022 |
| Gigabyte      | B460M DS3H AC               | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| HP            | 2129                        | [a6b5f98b78](https://linux-hardware.org/?probe=a6b5f98b78) | Mar 02, 2022 |
| Gigabyte      | B550 AORUS PRO              | [37d07ec6df](https://linux-hardware.org/?probe=37d07ec6df) | Mar 02, 2022 |
| Dell          | 0M858N A01                  | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 0B4Ch D                     | [dc25902f7e](https://linux-hardware.org/?probe=dc25902f7e) | Feb 28, 2022 |
| Intel         | DG41WV AAE90316-104         | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| ASUSTek       | PRIME X370-PRO              | [cd61ef5a5d](https://linux-hardware.org/?probe=cd61ef5a5d) | Feb 20, 2022 |
| MSI           | B450 TOMAHAWK               | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| MSI           | A55M-P33                    | [31c0a9c67c](https://linux-hardware.org/?probe=31c0a9c67c) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [47ff2c9673](https://linux-hardware.org/?probe=47ff2c9673) | Feb 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [91d1953478](https://linux-hardware.org/?probe=91d1953478) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [119cc6c1b1](https://linux-hardware.org/?probe=119cc6c1b1) | Feb 13, 2022 |
| Gigabyte      | B550 VISION D-P             | [e995276798](https://linux-hardware.org/?probe=e995276798) | Feb 07, 2022 |
| MSI           | B450 TOMAHAWK               | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| MSI           | B450 TOMAHAWK               | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| HP            | 2B4B                        | [4205ceb454](https://linux-hardware.org/?probe=4205ceb454) | Feb 01, 2022 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [9cc991a921](https://linux-hardware.org/?probe=9cc991a921) | Jan 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [533df9d207](https://linux-hardware.org/?probe=533df9d207) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| ASUSTek       | SABERTOOTH 55i              | [5c67654acf](https://linux-hardware.org/?probe=5c67654acf) | Jan 23, 2022 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [9ef9599ed3](https://linux-hardware.org/?probe=9ef9599ed3) | Jan 23, 2022 |
| ASUSTek       | H97M-E                      | [394132a26d](https://linux-hardware.org/?probe=394132a26d) | Jan 22, 2022 |
| ASUSTek       | H97M-E                      | [83e0c18dcb](https://linux-hardware.org/?probe=83e0c18dcb) | Jan 22, 2022 |
| Gigabyte      | B450 AORUS M                | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| ASUSTek       | H81M-R                      | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| ASUSTek       | H81M-R                      | [f65a651e3c](https://linux-hardware.org/?probe=f65a651e3c) | Jan 18, 2022 |
| Gigabyte      | G31M-S2C                    | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASRock        | B450M Pro4-F                | [f55512e3bc](https://linux-hardware.org/?probe=f55512e3bc) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | [d8e311c6cc](https://linux-hardware.org/?probe=d8e311c6cc) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| MSI           | P67A-C45                    | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| HP            | 18E5                        | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Biostar       | H77MU3                      | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek       | H97M-E                      | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek       | H97M-E                      | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK               | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| HP            | 2B29                        | [cfb166f99c](https://linux-hardware.org/?probe=cfb166f99c) | Jan 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [980348cf8f](https://linux-hardware.org/?probe=980348cf8f) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [85fc03c636](https://linux-hardware.org/?probe=85fc03c636) | Jan 08, 2022 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [92525df557](https://linux-hardware.org/?probe=92525df557) | Jan 06, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [bfd3b013ad](https://linux-hardware.org/?probe=bfd3b013ad) | Jan 02, 2022 |
| MSI           | C847IS-P33                  | [1ea085e13d](https://linux-hardware.org/?probe=1ea085e13d) | Jan 02, 2022 |
| Dell          | 0RY007                      | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b29f429221](https://linux-hardware.org/?probe=b29f429221) | Dec 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [727d42c466](https://linux-hardware.org/?probe=727d42c466) | Dec 28, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [5f62a9d831](https://linux-hardware.org/?probe=5f62a9d831) | Dec 26, 2021 |
| ASUSTek       | PRIME B550M-A               | [81f1473127](https://linux-hardware.org/?probe=81f1473127) | Dec 26, 2021 |
| Intel         | DG965RY AAD41691-301        | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [9715db22ef](https://linux-hardware.org/?probe=9715db22ef) | Dec 24, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d444bf3364](https://linux-hardware.org/?probe=d444bf3364) | Dec 24, 2021 |
| Pegatron      | 2AE4                        | [491f8d7813](https://linux-hardware.org/?probe=491f8d7813) | Dec 21, 2021 |
| Gigabyte      | B460M DS3H AC               | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| ASUSTek       | PRIME A320M-E               | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| MSI           | A55M-P33                    | [de87849301](https://linux-hardware.org/?probe=de87849301) | Dec 18, 2021 |
| ASUSTek       | P9X79 PRO                   | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| ASUSTek       | P8Z77-V LX                  | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | [85e65dae6a](https://linux-hardware.org/?probe=85e65dae6a) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | [3ff4885854](https://linux-hardware.org/?probe=3ff4885854) | Dec 15, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [ef7ae1fae5](https://linux-hardware.org/?probe=ef7ae1fae5) | Dec 15, 2021 |
| Biostar       | X370GT5                     | [40849a76de](https://linux-hardware.org/?probe=40849a76de) | Dec 14, 2021 |
| ASUSTek       | SABERTOOTH X79              | [3ad9c4f3dc](https://linux-hardware.org/?probe=3ad9c4f3dc) | Dec 14, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [d9c0e54748](https://linux-hardware.org/?probe=d9c0e54748) | Dec 13, 2021 |
| ASUSTek       | P8Z68-V                     | [8febc9ddd7](https://linux-hardware.org/?probe=8febc9ddd7) | Dec 13, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [cf94444ab9](https://linux-hardware.org/?probe=cf94444ab9) | Dec 11, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [beeedd3f54](https://linux-hardware.org/?probe=beeedd3f54) | Dec 11, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [8fb201df89](https://linux-hardware.org/?probe=8fb201df89) | Dec 07, 2021 |
| ASUSTek       | PRO B460M-C                 | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| HP            | 0A9Ch                       | [9bbd755279](https://linux-hardware.org/?probe=9bbd755279) | Dec 07, 2021 |
| HP            | 2B4B                        | [efc81a48f3](https://linux-hardware.org/?probe=efc81a48f3) | Dec 05, 2021 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | [7bb538c6f0](https://linux-hardware.org/?probe=7bb538c6f0) | Dec 05, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [a4718b7be1](https://linux-hardware.org/?probe=a4718b7be1) | Dec 03, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [e75c56906a](https://linux-hardware.org/?probe=e75c56906a) | Dec 01, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [f6ab5c54f6](https://linux-hardware.org/?probe=f6ab5c54f6) | Nov 27, 2021 |
| ASUSTek       | PRO B460M-C                 | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Dell          | 0RW199                      | [f00caa69eb](https://linux-hardware.org/?probe=f00caa69eb) | Nov 26, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | [a6b3b8877b](https://linux-hardware.org/?probe=a6b3b8877b) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | [7546b1e030](https://linux-hardware.org/?probe=7546b1e030) | Nov 24, 2021 |
| Dell          | 0PC5F7 A03                  | [5ee25c6894](https://linux-hardware.org/?probe=5ee25c6894) | Nov 23, 2021 |
| Dell          | 0PC5F7 A03                  | [7995f7e3a8](https://linux-hardware.org/?probe=7995f7e3a8) | Nov 23, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [a351f76025](https://linux-hardware.org/?probe=a351f76025) | Nov 22, 2021 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [c31b46e5b5](https://linux-hardware.org/?probe=c31b46e5b5) | Nov 22, 2021 |
| MSI           | MEG X570 UNIFY              | [1cc474712f](https://linux-hardware.org/?probe=1cc474712f) | Nov 22, 2021 |
| ASRock        | J5040-ITX                   | [0c072ca601](https://linux-hardware.org/?probe=0c072ca601) | Nov 19, 2021 |
| ASRock        | H370M Pro4                  | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| ASUSTek       | PRIME B450M-K               | [6444d420e3](https://linux-hardware.org/?probe=6444d420e3) | Nov 16, 2021 |
| MSI           | H510I PRO WIFI              | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| ASUSTek       | PRIME B450M-K               | [2c7f2bbe1e](https://linux-hardware.org/?probe=2c7f2bbe1e) | Nov 14, 2021 |
| ASRock        | N68C-GS4 FX                 | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [515d95c398](https://linux-hardware.org/?probe=515d95c398) | Nov 14, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [5db9c7e3ed](https://linux-hardware.org/?probe=5db9c7e3ed) | Nov 12, 2021 |
| HP            | 844C                        | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| Gigabyte      | B85M-HD3                    | [f042aedbd9](https://linux-hardware.org/?probe=f042aedbd9) | Nov 12, 2021 |
| ASUSTek       | M4A78T-E                    | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| MSI           | B450M MORTAR MAX            | [b05955d022](https://linux-hardware.org/?probe=b05955d022) | Nov 06, 2021 |
| MSI           | X570-A PRO                  | [377a49cece](https://linux-hardware.org/?probe=377a49cece) | Nov 06, 2021 |
| MSI           | B150M MORTAR                | [58d8ce0102](https://linux-hardware.org/?probe=58d8ce0102) | Nov 05, 2021 |
| Biostar       | H77MU3                      | [620dd98d14](https://linux-hardware.org/?probe=620dd98d14) | Nov 05, 2021 |
| ASUSTek       | H87M-PLUS                   | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [e9c054c1cd](https://linux-hardware.org/?probe=e9c054c1cd) | Nov 03, 2021 |
| ASRock        | X570 Steel Legend           | [f761a8dfa1](https://linux-hardware.org/?probe=f761a8dfa1) | Nov 03, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [276bfdb97e](https://linux-hardware.org/?probe=276bfdb97e) | Nov 03, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | [18ac20be04](https://linux-hardware.org/?probe=18ac20be04) | Nov 03, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | [0c4b94de98](https://linux-hardware.org/?probe=0c4b94de98) | Nov 03, 2021 |
| Dell          | 0KP561                      | [e0c7723977](https://linux-hardware.org/?probe=e0c7723977) | Nov 02, 2021 |
| Dell          | 0KP561                      | [904f09d033](https://linux-hardware.org/?probe=904f09d033) | Nov 02, 2021 |
| MSI           | X58 Pro                     | [e37a1a6dd3](https://linux-hardware.org/?probe=e37a1a6dd3) | Nov 01, 2021 |
| Dell          | 0PC5F7 A03                  | [7599b9831d](https://linux-hardware.org/?probe=7599b9831d) | Nov 01, 2021 |
| Dell          | 0M859N A00                  | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| ASUSTek       | TUF X299 MARK 2             | [eacc1e3f66](https://linux-hardware.org/?probe=eacc1e3f66) | Nov 01, 2021 |
| Dell          | 0PC5F7 A03                  | [e04a41fc30](https://linux-hardware.org/?probe=e04a41fc30) | Oct 31, 2021 |
| ASUSTek       | SABERTOOTH X79              | [0c14ffd402](https://linux-hardware.org/?probe=0c14ffd402) | Oct 30, 2021 |
| Dell          | 0PC5F7 A03                  | [d4c089bc2f](https://linux-hardware.org/?probe=d4c089bc2f) | Oct 30, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [667289d1b9](https://linux-hardware.org/?probe=667289d1b9) | Oct 30, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | [efa327d791](https://linux-hardware.org/?probe=efa327d791) | Oct 28, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [66fa4360dd](https://linux-hardware.org/?probe=66fa4360dd) | Oct 27, 2021 |
| ASUSTek       | PRIME Z390-A                | [382b33add2](https://linux-hardware.org/?probe=382b33add2) | Oct 25, 2021 |
| Dell          | 0KP561                      | [08bbb7d29e](https://linux-hardware.org/?probe=08bbb7d29e) | Oct 22, 2021 |
| ASUSTek       | Maximus VIII HERO           | [9d090ad177](https://linux-hardware.org/?probe=9d090ad177) | Oct 22, 2021 |
| Dell          | 0Y2YM6 A00                  | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell          | 0Y2YM6 A00                  | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [c3c2bded72](https://linux-hardware.org/?probe=c3c2bded72) | Oct 18, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [b4b684e48c](https://linux-hardware.org/?probe=b4b684e48c) | Oct 18, 2021 |
| MSI           | X58 Pro                     | [83bc2fb756](https://linux-hardware.org/?probe=83bc2fb756) | Oct 15, 2021 |
| Dell          | 0PC5F7 A03                  | [10b4482e0f](https://linux-hardware.org/?probe=10b4482e0f) | Oct 12, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [108ff59d0f](https://linux-hardware.org/?probe=108ff59d0f) | Oct 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| HP            | 87D6 SMVB                   | [6db404b73c](https://linux-hardware.org/?probe=6db404b73c) | Oct 08, 2021 |
| Dell          | 0PC5F7 A03                  | [644a49c933](https://linux-hardware.org/?probe=644a49c933) | Oct 06, 2021 |
| Dell          | 0PC5F7 A03                  | [ff4e1fdb3a](https://linux-hardware.org/?probe=ff4e1fdb3a) | Oct 06, 2021 |
| HP            | 8591                        | [2de119b3d7](https://linux-hardware.org/?probe=2de119b3d7) | Oct 05, 2021 |
| ASRock        | H370M Pro4                  | [2865692c58](https://linux-hardware.org/?probe=2865692c58) | Oct 05, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| MSI           | B450M MORTAR MAX            | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [0e54f43704](https://linux-hardware.org/?probe=0e54f43704) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| ASUSTek       | PRIME B460M-K               | [33a2f5f274](https://linux-hardware.org/?probe=33a2f5f274) | Oct 02, 2021 |
| MSI           | Z590-A PRO                  | [3147ae8c58](https://linux-hardware.org/?probe=3147ae8c58) | Oct 01, 2021 |
| HP            | 8591                        | [2473523764](https://linux-hardware.org/?probe=2473523764) | Oct 01, 2021 |
| ASRock        | H110M-G/M.2                 | [fa98bc9cc1](https://linux-hardware.org/?probe=fa98bc9cc1) | Oct 01, 2021 |
| HP            | 8591                        | [16548ed5fc](https://linux-hardware.org/?probe=16548ed5fc) | Sep 30, 2021 |
| HP            | 8591                        | [187edb6508](https://linux-hardware.org/?probe=187edb6508) | Sep 30, 2021 |
| ASUSTek       | PRIME A320M-K               | [22d4ba7e2e](https://linux-hardware.org/?probe=22d4ba7e2e) | Sep 25, 2021 |
| ASUSTek       | M4A78T-E                    | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [fca13979bf](https://linux-hardware.org/?probe=fca13979bf) | Sep 22, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [58f9ca6247](https://linux-hardware.org/?probe=58f9ca6247) | Sep 22, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| VS Company    | G31T-M                      | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek       | AM1M-A/BR                   | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| MSI           | X370 SLI PLUS               | [783d480732](https://linux-hardware.org/?probe=783d480732) | Sep 16, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [84d5715b05](https://linux-hardware.org/?probe=84d5715b05) | Sep 16, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [2a08044752](https://linux-hardware.org/?probe=2a08044752) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [754b5ad560](https://linux-hardware.org/?probe=754b5ad560) | Sep 12, 2021 |
| MSI           | X370 GAMING PRO             | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| Gigabyte      | B450M GAMING                | [e5b03fa6d6](https://linux-hardware.org/?probe=e5b03fa6d6) | Sep 10, 2021 |
| Gigabyte      | B85-HD3-A                   | [db9571e8ce](https://linux-hardware.org/?probe=db9571e8ce) | Sep 09, 2021 |
| MSI           | Z590-A PRO                  | [d4adebf878](https://linux-hardware.org/?probe=d4adebf878) | Sep 06, 2021 |
| HP            | 8056                        | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel         | DG41WV AAE90316-104         | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte      | B85-HD3-A                   | [d181845f45](https://linux-hardware.org/?probe=d181845f45) | Sep 05, 2021 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [b0339d1206](https://linux-hardware.org/?probe=b0339d1206) | Sep 04, 2021 |
| MSI           | B450M MORTAR MAX            | [8518bcca24](https://linux-hardware.org/?probe=8518bcca24) | Sep 01, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [3f330b3732](https://linux-hardware.org/?probe=3f330b3732) | Aug 31, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [cf52a3a23b](https://linux-hardware.org/?probe=cf52a3a23b) | Aug 31, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| Supermicro    | X10DAI                      | [078ab4c114](https://linux-hardware.org/?probe=078ab4c114) | Aug 24, 2021 |
| Foxconn       | 2ADA                        | [4a2ace789c](https://linux-hardware.org/?probe=4a2ace789c) | Aug 24, 2021 |
| HARDKERNEL    | ODROID-H2                   | [98bc091671](https://linux-hardware.org/?probe=98bc091671) | Aug 22, 2021 |
| MSI           | MAG B460 TORPEDO            | [593ba86c4f](https://linux-hardware.org/?probe=593ba86c4f) | Aug 18, 2021 |
| Gigabyte      | H81M-S2H                    | [63a305ffc3](https://linux-hardware.org/?probe=63a305ffc3) | Aug 18, 2021 |
| Gigabyte      | B85-HD3-A                   | [91b0fe5452](https://linux-hardware.org/?probe=91b0fe5452) | Aug 17, 2021 |
| ASUSTek       | A88X-PLUS                   | [5a126bf926](https://linux-hardware.org/?probe=5a126bf926) | Aug 17, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [8d58a29d27](https://linux-hardware.org/?probe=8d58a29d27) | Aug 12, 2021 |
| HP            | 212B                        | [c9d708e504](https://linux-hardware.org/?probe=c9d708e504) | Aug 11, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [034630b7f9](https://linux-hardware.org/?probe=034630b7f9) | Aug 11, 2021 |
| Gigabyte      | Z370M D3H-CF                | [ce1da3d925](https://linux-hardware.org/?probe=ce1da3d925) | Aug 09, 2021 |
| HP            | 8591                        | [0f34dfc82c](https://linux-hardware.org/?probe=0f34dfc82c) | Aug 06, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4e85e3f721](https://linux-hardware.org/?probe=4e85e3f721) | Aug 06, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [ca04a79b3a](https://linux-hardware.org/?probe=ca04a79b3a) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [ffee1e0026](https://linux-hardware.org/?probe=ffee1e0026) | Aug 03, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [2637dbf19f](https://linux-hardware.org/?probe=2637dbf19f) | Aug 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [a740a5cb42](https://linux-hardware.org/?probe=a740a5cb42) | Aug 01, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [34f2f2b2a6](https://linux-hardware.org/?probe=34f2f2b2a6) | Aug 01, 2021 |
| ASUSTek       | PRIME H310M-A               | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI           | B85M-E45                    | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| ASUSTek       | P8P67 DELUXE                | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| ASRock        | B560M Pro4/ac               | [84b1cb28d8](https://linux-hardware.org/?probe=84b1cb28d8) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | [748f864d48](https://linux-hardware.org/?probe=748f864d48) | Jul 25, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [7cd3b13d49](https://linux-hardware.org/?probe=7cd3b13d49) | Jul 20, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | [9552e2989b](https://linux-hardware.org/?probe=9552e2989b) | Jul 19, 2021 |
| Gigabyte      | Z68XP-UD4                   | [ed60f1e7f0](https://linux-hardware.org/?probe=ed60f1e7f0) | Jul 18, 2021 |
| Pegatron      | 2AE4                        | [6ccb7429e8](https://linux-hardware.org/?probe=6ccb7429e8) | Jul 18, 2021 |
| MSI           | CSM-H81M-P32                | [bb1a577dcb](https://linux-hardware.org/?probe=bb1a577dcb) | Jul 16, 2021 |
| MSI           | CSM-H81M-P32                | [8adb253225](https://linux-hardware.org/?probe=8adb253225) | Jul 16, 2021 |
| ASRock        | Z370 Extreme4               | [2bb85ea1fa](https://linux-hardware.org/?probe=2bb85ea1fa) | Jul 16, 2021 |
| MSI           | CSM-H81M-P32                | [33a729d21a](https://linux-hardware.org/?probe=33a729d21a) | Jul 16, 2021 |
| MSI           | CSM-H81M-P32                | [898c0290c3](https://linux-hardware.org/?probe=898c0290c3) | Jul 16, 2021 |
| HP            | 8433 11                     | [b079ccb608](https://linux-hardware.org/?probe=b079ccb608) | Jul 15, 2021 |
| Dell          | 0F6X5P A00                  | [5e32689c02](https://linux-hardware.org/?probe=5e32689c02) | Jul 14, 2021 |
| HP            | 8433 11                     | [ec0b9d119c](https://linux-hardware.org/?probe=ec0b9d119c) | Jul 12, 2021 |
| MSI           | D2415 S26361-D2415-A21      | [b49400f636](https://linux-hardware.org/?probe=b49400f636) | Jul 11, 2021 |
| Dell          | 0D6H9T A00                  | [53bf6514dc](https://linux-hardware.org/?probe=53bf6514dc) | Jul 09, 2021 |
| MSI           | B350 TOMAHAWK               | [27a6ac997b](https://linux-hardware.org/?probe=27a6ac997b) | Jul 03, 2021 |
| ASRock        | X570M Pro4                  | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [734f246fde](https://linux-hardware.org/?probe=734f246fde) | Jul 02, 2021 |
| ASRock        | X570M Pro4                  | [714a2fb6ec](https://linux-hardware.org/?probe=714a2fb6ec) | Jul 02, 2021 |
| ASRock        | X300M-STX                   | [d37f7f02f3](https://linux-hardware.org/?probe=d37f7f02f3) | Jun 27, 2021 |
| HP            | 0A68h                       | [36cfa6a366](https://linux-hardware.org/?probe=36cfa6a366) | Jun 27, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [dfc2f82575](https://linux-hardware.org/?probe=dfc2f82575) | Jun 26, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [3cdc6a847c](https://linux-hardware.org/?probe=3cdc6a847c) | Jun 23, 2021 |
| MSI           | MEG Z390 GODLIKE            | [309968fda4](https://linux-hardware.org/?probe=309968fda4) | Jun 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d1fe43704d](https://linux-hardware.org/?probe=d1fe43704d) | Jun 22, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [75e171067f](https://linux-hardware.org/?probe=75e171067f) | Jun 18, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [918daf4abf](https://linux-hardware.org/?probe=918daf4abf) | Jun 18, 2021 |
| ASRock        | X570 Steel Legend           | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [f6d899ab00](https://linux-hardware.org/?probe=f6d899ab00) | Jun 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [39f357041a](https://linux-hardware.org/?probe=39f357041a) | Jun 17, 2021 |
| Lenovo        | 31900058 STD                | [c05b020e55](https://linux-hardware.org/?probe=c05b020e55) | Jun 13, 2021 |
| Lenovo        | 31900058 STD                | [285f293744](https://linux-hardware.org/?probe=285f293744) | Jun 11, 2021 |
| ASUSTek       | PRIME Z370-A                | [fd3d53cf4d](https://linux-hardware.org/?probe=fd3d53cf4d) | Jun 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b815f252d9](https://linux-hardware.org/?probe=b815f252d9) | Jun 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [b47a3aad4b](https://linux-hardware.org/?probe=b47a3aad4b) | Jun 10, 2021 |
| Pegatron      | 2AD5                        | [503cffa288](https://linux-hardware.org/?probe=503cffa288) | Jun 08, 2021 |
| ASRock        | H370M Pro4                  | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | [fc1d1cd5ec](https://linux-hardware.org/?probe=fc1d1cd5ec) | Jun 07, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [a750453ba5](https://linux-hardware.org/?probe=a750453ba5) | Jun 04, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [9747ab9c9c](https://linux-hardware.org/?probe=9747ab9c9c) | Jun 04, 2021 |
| Lenovo        | 31900058 STD                | [52e4f61567](https://linux-hardware.org/?probe=52e4f61567) | Jun 04, 2021 |
| HP            | 2AA2                        | [65e7cd2d3e](https://linux-hardware.org/?probe=65e7cd2d3e) | Jun 02, 2021 |
| ASRock        | B450M Pro4                  | [0b6c4d4d7b](https://linux-hardware.org/?probe=0b6c4d4d7b) | Jun 01, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [d283998378](https://linux-hardware.org/?probe=d283998378) | Jun 01, 2021 |
| MSI           | MEG Z390 GODLIKE            | [3d0da576b8](https://linux-hardware.org/?probe=3d0da576b8) | May 31, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [62ddf1b4f0](https://linux-hardware.org/?probe=62ddf1b4f0) | May 31, 2021 |
| Biostar       | H77MU3                      | [68732ecd4b](https://linux-hardware.org/?probe=68732ecd4b) | May 26, 2021 |
| ASUSTek       | H110M-R                     | [62b22bfb20](https://linux-hardware.org/?probe=62b22bfb20) | May 26, 2021 |
| MSI           | B250 PC MATE                | [08cc036466](https://linux-hardware.org/?probe=08cc036466) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Lenovo        | 31900058 STD                | [5a88991b4a](https://linux-hardware.org/?probe=5a88991b4a) | May 24, 2021 |
| HP            | 8906 SMVB                   | [b83a47d4f0](https://linux-hardware.org/?probe=b83a47d4f0) | May 24, 2021 |
| ASRock        | H370M Pro4                  | [72deada743](https://linux-hardware.org/?probe=72deada743) | May 23, 2021 |
| Gigabyte      | B450 AORUS M                | [3647d11d65](https://linux-hardware.org/?probe=3647d11d65) | May 23, 2021 |
| Foxconn       | 2ADA                        | [26ad7625f4](https://linux-hardware.org/?probe=26ad7625f4) | May 22, 2021 |
| Dell          | 07T4MC A06                  | [a897526e05](https://linux-hardware.org/?probe=a897526e05) | May 20, 2021 |
| ASUSTek       | F2A55                       | [39cc2ef96b](https://linux-hardware.org/?probe=39cc2ef96b) | May 19, 2021 |
| Medion        | MS-7728                     | [e8a476fe82](https://linux-hardware.org/?probe=e8a476fe82) | May 19, 2021 |
| ASUSTek       | F2A55                       | [1ceca4b4dd](https://linux-hardware.org/?probe=1ceca4b4dd) | May 19, 2021 |
| Foxconn       | 2ADA                        | [c1932872e1](https://linux-hardware.org/?probe=c1932872e1) | May 18, 2021 |
| ASRock        | 890GM Pro3                  | [4c10147742](https://linux-hardware.org/?probe=4c10147742) | May 15, 2021 |
| Dell          | 05GD68 A00                  | [3dc4d47c91](https://linux-hardware.org/?probe=3dc4d47c91) | May 15, 2021 |
| Dell          | 05GD68 A00                  | [b9a128aa7c](https://linux-hardware.org/?probe=b9a128aa7c) | May 15, 2021 |
| MSI           | MS-7048                     | [52c3157c62](https://linux-hardware.org/?probe=52c3157c62) | May 14, 2021 |
| MSI           | MS-7048                     | [36ff46d134](https://linux-hardware.org/?probe=36ff46d134) | May 14, 2021 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [fc1ed40727](https://linux-hardware.org/?probe=fc1ed40727) | May 08, 2021 |
| Dell          | 0C522T A01                  | [91f5ffce1c](https://linux-hardware.org/?probe=91f5ffce1c) | May 08, 2021 |
| HP            | 2129                        | [83dfc4b9d8](https://linux-hardware.org/?probe=83dfc4b9d8) | May 07, 2021 |
| ASUSTek       | PRIME A320M-K               | [70628bdf55](https://linux-hardware.org/?probe=70628bdf55) | May 06, 2021 |
| Intel         | H61                         | [b416bb5507](https://linux-hardware.org/?probe=b416bb5507) | May 06, 2021 |
| Intel         | H61                         | [8df6e992bc](https://linux-hardware.org/?probe=8df6e992bc) | May 06, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [d7a971495e](https://linux-hardware.org/?probe=d7a971495e) | May 05, 2021 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [8e97256ab2](https://linux-hardware.org/?probe=8e97256ab2) | May 04, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [04436cea51](https://linux-hardware.org/?probe=04436cea51) | May 04, 2021 |
| MSI           | B450-A PRO MAX              | [973aaf91ee](https://linux-hardware.org/?probe=973aaf91ee) | May 01, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [757acafcf9](https://linux-hardware.org/?probe=757acafcf9) | May 01, 2021 |
| PCWare        | IPX4105G Pro                | [c7baff772d](https://linux-hardware.org/?probe=c7baff772d) | May 01, 2021 |
| Dell          | 0KC9NP A01                  | [019f1d6c17](https://linux-hardware.org/?probe=019f1d6c17) | Apr 30, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c4532f4a03](https://linux-hardware.org/?probe=c4532f4a03) | Apr 29, 2021 |
| Biostar       | TB350-BTC                   | [69ac177ac7](https://linux-hardware.org/?probe=69ac177ac7) | Apr 29, 2021 |
| ASUSTek       | B75M-A                      | [2fabbbebb9](https://linux-hardware.org/?probe=2fabbbebb9) | Apr 29, 2021 |
| ASUSTek       | B75M-A                      | [23cc5c25c3](https://linux-hardware.org/?probe=23cc5c25c3) | Apr 29, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [c601f4668d](https://linux-hardware.org/?probe=c601f4668d) | Apr 27, 2021 |
| ASRock        | B75M R2.0                   | [7ce74db09a](https://linux-hardware.org/?probe=7ce74db09a) | Apr 25, 2021 |
| ASRock        | H370M Pro4                  | [be75ff3da4](https://linux-hardware.org/?probe=be75ff3da4) | Apr 25, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [56e74a7e11](https://linux-hardware.org/?probe=56e74a7e11) | Apr 20, 2021 |
| HP            | 844C                        | [937c6daedd](https://linux-hardware.org/?probe=937c6daedd) | Apr 19, 2021 |
| HP            | 844C                        | [1e6bc9d216](https://linux-hardware.org/?probe=1e6bc9d216) | Apr 19, 2021 |
| ASUSTek       | F2A55                       | [cb6cd15542](https://linux-hardware.org/?probe=cb6cd15542) | Apr 19, 2021 |
| Unknown       | Unknown                     | [2537b06002](https://linux-hardware.org/?probe=2537b06002) | Apr 18, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [764abcf0c8](https://linux-hardware.org/?probe=764abcf0c8) | Apr 16, 2021 |
| ASUSTek       | P9X79                       | [e9636d21ef](https://linux-hardware.org/?probe=e9636d21ef) | Apr 15, 2021 |
| HP            | 844C                        | [dba1b1f7fb](https://linux-hardware.org/?probe=dba1b1f7fb) | Apr 15, 2021 |
| Unknown       | Unknown                     | [41c83d5661](https://linux-hardware.org/?probe=41c83d5661) | Apr 14, 2021 |
| ASRock        | H370M Pro4                  | [e6b5c6b72b](https://linux-hardware.org/?probe=e6b5c6b72b) | Apr 11, 2021 |
| ASRock        | AB350M-HDV                  | [d4844ab30d](https://linux-hardware.org/?probe=d4844ab30d) | Apr 11, 2021 |
| Gigabyte      | H81M-S2H                    | [fe5b3d8070](https://linux-hardware.org/?probe=fe5b3d8070) | Apr 11, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [94634847c8](https://linux-hardware.org/?probe=94634847c8) | Apr 10, 2021 |
| Unknown       | Unknown                     | [5076f99ff1](https://linux-hardware.org/?probe=5076f99ff1) | Apr 07, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [feb191acdd](https://linux-hardware.org/?probe=feb191acdd) | Apr 06, 2021 |
| ASRock        | FM2A78M Pro4+               | [a0412f631b](https://linux-hardware.org/?probe=a0412f631b) | Apr 05, 2021 |
| ASRock        | 970 Pro3 R2.0               | [56baf6b4ce](https://linux-hardware.org/?probe=56baf6b4ce) | Apr 05, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [63a2489a5f](https://linux-hardware.org/?probe=63a2489a5f) | Apr 04, 2021 |
| Biostar       | X370GT5                     | [49d5f9d25e](https://linux-hardware.org/?probe=49d5f9d25e) | Apr 04, 2021 |
| Biostar       | A960D+                      | [92bb1238c2](https://linux-hardware.org/?probe=92bb1238c2) | Apr 03, 2021 |
| Positivo      | POS-EIH61CE POSITIVO        | [928bffa7df](https://linux-hardware.org/?probe=928bffa7df) | Apr 03, 2021 |
| Dell          | 0KC9NP A01                  | [e04751fdc0](https://linux-hardware.org/?probe=e04751fdc0) | Mar 30, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [6a3cdb9e59](https://linux-hardware.org/?probe=6a3cdb9e59) | Mar 30, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [5bdb7ece94](https://linux-hardware.org/?probe=5bdb7ece94) | Mar 29, 2021 |
| ASUSTek       | F2A55                       | [6028a48bee](https://linux-hardware.org/?probe=6028a48bee) | Mar 28, 2021 |
| Dell          | 0X4N41 A00                  | [370f1a16b9](https://linux-hardware.org/?probe=370f1a16b9) | Mar 28, 2021 |
| Dell          | 0KC9NP A01                  | [d0c5111b95](https://linux-hardware.org/?probe=d0c5111b95) | Mar 25, 2021 |
| Lenovo        | Board                       | [1012458ac7](https://linux-hardware.org/?probe=1012458ac7) | Mar 24, 2021 |
| PCWare        | IPX4105G Pro                | [c2f7bea0d3](https://linux-hardware.org/?probe=c2f7bea0d3) | Mar 21, 2021 |
| Gigabyte      | Z68XP-UD4                   | [6627b90812](https://linux-hardware.org/?probe=6627b90812) | Mar 20, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [4962bcc8e0](https://linux-hardware.org/?probe=4962bcc8e0) | Mar 19, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [e6860a4c7f](https://linux-hardware.org/?probe=e6860a4c7f) | Mar 19, 2021 |
| ASRock        | H77M                        | [59a7fb13f5](https://linux-hardware.org/?probe=59a7fb13f5) | Mar 18, 2021 |
| Intel         | D525MW AAE93082-301         | [1caeea4be4](https://linux-hardware.org/?probe=1caeea4be4) | Mar 18, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [e48b7f8db2](https://linux-hardware.org/?probe=e48b7f8db2) | Mar 16, 2021 |
| Dell          | 0KV3RP A00                  | [ba655d9380](https://linux-hardware.org/?probe=ba655d9380) | Mar 16, 2021 |
| Intel         | DG41WV AAE90316-104         | [af606a347f](https://linux-hardware.org/?probe=af606a347f) | Mar 15, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [d751ec9c6c](https://linux-hardware.org/?probe=d751ec9c6c) | Mar 14, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [e52a7777d0](https://linux-hardware.org/?probe=e52a7777d0) | Mar 13, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b0338dd440](https://linux-hardware.org/?probe=b0338dd440) | Mar 13, 2021 |
| MSI           | X470 GAMING PRO             | [d80b4b42b5](https://linux-hardware.org/?probe=d80b4b42b5) | Mar 10, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [56dfe79cf3](https://linux-hardware.org/?probe=56dfe79cf3) | Mar 09, 2021 |
| ASUSTek       | AM1M-A                      | [bdbb6f7cb7](https://linux-hardware.org/?probe=bdbb6f7cb7) | Mar 09, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [092be03728](https://linux-hardware.org/?probe=092be03728) | Mar 08, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [80ee5053be](https://linux-hardware.org/?probe=80ee5053be) | Mar 06, 2021 |
| ASRock        | Z390 Taichi Ultimate        | [bfdc7b65ca](https://linux-hardware.org/?probe=bfdc7b65ca) | Mar 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [d80f548759](https://linux-hardware.org/?probe=d80f548759) | Mar 04, 2021 |
| MSI           | C236A WORKSTATION           | [dc9e6c2670](https://linux-hardware.org/?probe=dc9e6c2670) | Mar 03, 2021 |
| MSI           | MEG X570 GODLIKE            | [3d2e576c95](https://linux-hardware.org/?probe=3d2e576c95) | Mar 03, 2021 |
| Dell          | 09M8Y8 A01                  | [4997df5506](https://linux-hardware.org/?probe=4997df5506) | Mar 03, 2021 |
| Gigabyte      | G1.Sniper Z87               | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| Dell          | 00V62H A01                  | [e16aa381aa](https://linux-hardware.org/?probe=e16aa381aa) | Mar 01, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [d8b6a8725d](https://linux-hardware.org/?probe=d8b6a8725d) | Mar 01, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [c490b4be99](https://linux-hardware.org/?probe=c490b4be99) | Mar 01, 2021 |
| ASUSTek       | P8H61-M LX                  | [0c1cb15e47](https://linux-hardware.org/?probe=0c1cb15e47) | Feb 28, 2021 |
| ASUSTek       | P8H61-M LX                  | [4774dabe35](https://linux-hardware.org/?probe=4774dabe35) | Feb 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0752151d41](https://linux-hardware.org/?probe=0752151d41) | Feb 26, 2021 |
| Gigabyte      | H81M-S2H                    | [e2f65d26c4](https://linux-hardware.org/?probe=e2f65d26c4) | Feb 25, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6b721d56ba](https://linux-hardware.org/?probe=6b721d56ba) | Feb 25, 2021 |
| ASUSTek       | PRIME X570-P                | [53d26490a1](https://linux-hardware.org/?probe=53d26490a1) | Feb 23, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [c096245d55](https://linux-hardware.org/?probe=c096245d55) | Feb 23, 2021 |
| MSI           | MEG Z390 GODLIKE            | [6f9c1938f3](https://linux-hardware.org/?probe=6f9c1938f3) | Feb 23, 2021 |
| MSI           | C236A WORKSTATION           | [9e2effbe63](https://linux-hardware.org/?probe=9e2effbe63) | Feb 22, 2021 |
| Dell          | 0HD5W2 A01                  | [0bb8bbfe31](https://linux-hardware.org/?probe=0bb8bbfe31) | Feb 22, 2021 |
| Gigabyte      | B550 AORUS PRO V2           | [78c9f0a694](https://linux-hardware.org/?probe=78c9f0a694) | Feb 21, 2021 |
| ASUSTek       | PRIME B350M-A               | [201d0f8a0c](https://linux-hardware.org/?probe=201d0f8a0c) | Feb 20, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [23e2da6146](https://linux-hardware.org/?probe=23e2da6146) | Feb 17, 2021 |
| Gigabyte      | B85M-HD3                    | [84d70bc8d9](https://linux-hardware.org/?probe=84d70bc8d9) | Feb 17, 2021 |
| Dell          | 0KC9NP A01                  | [78abf9e7c9](https://linux-hardware.org/?probe=78abf9e7c9) | Feb 16, 2021 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [e7ce5a5a00](https://linux-hardware.org/?probe=e7ce5a5a00) | Feb 14, 2021 |
| HP            | 339A                        | [9558c4f6bf](https://linux-hardware.org/?probe=9558c4f6bf) | Feb 12, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [7e298b9392](https://linux-hardware.org/?probe=7e298b9392) | Feb 12, 2021 |
| MSI           | MEG Z390 GODLIKE            | [b8da9b15ef](https://linux-hardware.org/?probe=b8da9b15ef) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [ba4b26d5a7](https://linux-hardware.org/?probe=ba4b26d5a7) | Feb 11, 2021 |
| HP            | 339A                        | [18aa064960](https://linux-hardware.org/?probe=18aa064960) | Feb 10, 2021 |
| Gigabyte      | X99-UD5 WIFI-CF             | [f9375b6948](https://linux-hardware.org/?probe=f9375b6948) | Feb 09, 2021 |
| Dell          | 0GY6Y8 A01                  | [e501d04080](https://linux-hardware.org/?probe=e501d04080) | Feb 09, 2021 |
| HP            | ProLiant MicroServer        | [239eccaa55](https://linux-hardware.org/?probe=239eccaa55) | Feb 08, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [53dd7cd620](https://linux-hardware.org/?probe=53dd7cd620) | Feb 08, 2021 |
| ASUSTek       | P7P55 WS SUPERCOMPUTER      | [acbf8ef1e7](https://linux-hardware.org/?probe=acbf8ef1e7) | Feb 07, 2021 |
| Medion        | MS-7797                     | [687b518997](https://linux-hardware.org/?probe=687b518997) | Feb 05, 2021 |
| HP            | 339A                        | [341ab39c21](https://linux-hardware.org/?probe=341ab39c21) | Feb 04, 2021 |
| HP            | 339A                        | [9fdc79703e](https://linux-hardware.org/?probe=9fdc79703e) | Feb 04, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [9875db8f64](https://linux-hardware.org/?probe=9875db8f64) | Feb 04, 2021 |
| Dell          | 0KC9NP A01                  | [cfec475e46](https://linux-hardware.org/?probe=cfec475e46) | Feb 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [912c8c3983](https://linux-hardware.org/?probe=912c8c3983) | Jan 30, 2021 |
| SYWZ          | S210H Series                | [42487ac29c](https://linux-hardware.org/?probe=42487ac29c) | Jan 30, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [9a7601d2fe](https://linux-hardware.org/?probe=9a7601d2fe) | Jan 28, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dbe230fe3f](https://linux-hardware.org/?probe=dbe230fe3f) | Jan 22, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1e5b1ac8ca](https://linux-hardware.org/?probe=1e5b1ac8ca) | Jan 21, 2021 |
| Dell          | 0KC9NP A01                  | [78d65c96a7](https://linux-hardware.org/?probe=78d65c96a7) | Jan 21, 2021 |
| ASUSTek       | PRIME B460M-K               | [e6a66f629c](https://linux-hardware.org/?probe=e6a66f629c) | Jan 20, 2021 |
| MSI           | B450 TOMAHAWK               | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| MSI           | MEG Z390 GODLIKE            | [2a84d71958](https://linux-hardware.org/?probe=2a84d71958) | Jan 19, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | [731e0dfa98](https://linux-hardware.org/?probe=731e0dfa98) | Jan 17, 2021 |
| ASUSTek       | AM1M-A                      | [287cefb90e](https://linux-hardware.org/?probe=287cefb90e) | Jan 17, 2021 |
| ASRock        | B550 Extreme4               | [5be5613703](https://linux-hardware.org/?probe=5be5613703) | Jan 14, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e881933fc](https://linux-hardware.org/?probe=9e881933fc) | Jan 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9589d96b86](https://linux-hardware.org/?probe=9589d96b86) | Jan 13, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [1a25c0df1d](https://linux-hardware.org/?probe=1a25c0df1d) | Jan 13, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [e25d0635f2](https://linux-hardware.org/?probe=e25d0635f2) | Jan 08, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [68c2299ccc](https://linux-hardware.org/?probe=68c2299ccc) | Jan 08, 2021 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [c48a132403](https://linux-hardware.org/?probe=c48a132403) | Jan 08, 2021 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [5434ebcc83](https://linux-hardware.org/?probe=5434ebcc83) | Jan 08, 2021 |
| MSI           | B450M MORTAR MAX            | [37c9cf86aa](https://linux-hardware.org/?probe=37c9cf86aa) | Jan 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [920ed3109b](https://linux-hardware.org/?probe=920ed3109b) | Jan 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [173f6c2595](https://linux-hardware.org/?probe=173f6c2595) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8cb9441f8e](https://linux-hardware.org/?probe=8cb9441f8e) | Jan 04, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [fca0fd3336](https://linux-hardware.org/?probe=fca0fd3336) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [e649876eef](https://linux-hardware.org/?probe=e649876eef) | Jan 03, 2021 |
| Dell          | 0KC9NP A01                  | [f9728dd992](https://linux-hardware.org/?probe=f9728dd992) | Jan 03, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b87505d821](https://linux-hardware.org/?probe=b87505d821) | Jan 01, 2021 |
| ASRock        | B450M Pro4                  | [4959fff90f](https://linux-hardware.org/?probe=4959fff90f) | Dec 31, 2020 |
| ASUSTek       | P7H55-M PRO                 | [0f83d20db6](https://linux-hardware.org/?probe=0f83d20db6) | Dec 30, 2020 |
| Gigabyte      | F2A78M-D3H                  | [f098e40f89](https://linux-hardware.org/?probe=f098e40f89) | Dec 30, 2020 |
| Gigabyte      | AX370-Gaming 5              | [a26af9a455](https://linux-hardware.org/?probe=a26af9a455) | Dec 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | [017a456b07](https://linux-hardware.org/?probe=017a456b07) | Dec 28, 2020 |
| Foxconn       | 2AA9                        | [ad51692f6a](https://linux-hardware.org/?probe=ad51692f6a) | Dec 26, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [4dc58636c5](https://linux-hardware.org/?probe=4dc58636c5) | Dec 25, 2020 |
| Dell          | 0KC9NP A01                  | [b6a365fc1c](https://linux-hardware.org/?probe=b6a365fc1c) | Dec 24, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c53b9f764c](https://linux-hardware.org/?probe=c53b9f764c) | Dec 23, 2020 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [29c8d5d253](https://linux-hardware.org/?probe=29c8d5d253) | Dec 19, 2020 |
| MSI           | MEG Z390 GODLIKE            | [1f5302eb2d](https://linux-hardware.org/?probe=1f5302eb2d) | Dec 18, 2020 |
| ASUSTek       | M4N98TD EVO                 | [6aa0488e7e](https://linux-hardware.org/?probe=6aa0488e7e) | Dec 15, 2020 |
| ASUSTek       | M4N98TD EVO                 | [77d21986c9](https://linux-hardware.org/?probe=77d21986c9) | Dec 15, 2020 |
| Dell          | 0KC9NP A01                  | [33f50f83ff](https://linux-hardware.org/?probe=33f50f83ff) | Dec 14, 2020 |
| Gigabyte      | H81M-S2H                    | [39187348ed](https://linux-hardware.org/?probe=39187348ed) | Dec 14, 2020 |
| MSI           | MEG Z390 GODLIKE            | [9ce1b3ab72](https://linux-hardware.org/?probe=9ce1b3ab72) | Dec 13, 2020 |
| ASUSTek       | PRIME B550M-A               | [9fcf3d613e](https://linux-hardware.org/?probe=9fcf3d613e) | Dec 12, 2020 |
| Gigabyte      | Z68A-D3-B3                  | [78e566249b](https://linux-hardware.org/?probe=78e566249b) | Dec 08, 2020 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [52bcd70f79](https://linux-hardware.org/?probe=52bcd70f79) | Dec 07, 2020 |
| MSI           | B450-A PRO MAX              | [1258e3dd7d](https://linux-hardware.org/?probe=1258e3dd7d) | Dec 02, 2020 |
| Gigabyte      | Z68XP-UD4                   | [b4981872ae](https://linux-hardware.org/?probe=b4981872ae) | Dec 01, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [e6ae2cdc19](https://linux-hardware.org/?probe=e6ae2cdc19) | Nov 28, 2020 |
| MSI           | MEG X570 GODLIKE            | [1444dde245](https://linux-hardware.org/?probe=1444dde245) | Nov 28, 2020 |
| Gigabyte      | A320M-S2H-CF                | [9490258806](https://linux-hardware.org/?probe=9490258806) | Nov 26, 2020 |
| Gigabyte      | Z68XP-UD4                   | [b2f43ea1fc](https://linux-hardware.org/?probe=b2f43ea1fc) | Nov 26, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [e8f69d98b5](https://linux-hardware.org/?probe=e8f69d98b5) | Nov 22, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [2e562e990b](https://linux-hardware.org/?probe=2e562e990b) | Nov 20, 2020 |
| ASRock        | H110M-STX                   | [e4247d95cd](https://linux-hardware.org/?probe=e4247d95cd) | Nov 19, 2020 |
| HP            | 8591                        | [829a5d77e3](https://linux-hardware.org/?probe=829a5d77e3) | Nov 18, 2020 |
| Gigabyte      | Z68A-D3-B3                  | [3bc4011c54](https://linux-hardware.org/?probe=3bc4011c54) | Nov 18, 2020 |
| ASUSTek       | M11BB                       | [ee00977530](https://linux-hardware.org/?probe=ee00977530) | Nov 17, 2020 |
| ASRock        | H110M-STX                   | [aa56dd4d67](https://linux-hardware.org/?probe=aa56dd4d67) | Nov 17, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [37753d30ce](https://linux-hardware.org/?probe=37753d30ce) | Nov 15, 2020 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [3a6b91fc5d](https://linux-hardware.org/?probe=3a6b91fc5d) | Nov 15, 2020 |
| Medion        | MS-7848                     | [a9bc1a10b3](https://linux-hardware.org/?probe=a9bc1a10b3) | Nov 13, 2020 |
| Gigabyte      | Z390 UD                     | [681439cbb2](https://linux-hardware.org/?probe=681439cbb2) | Nov 13, 2020 |
| Gigabyte      | 970A-DS3P                   | [927e9227f3](https://linux-hardware.org/?probe=927e9227f3) | Nov 11, 2020 |
| ASUSTek       | PRIME X570-P                | [798cae3014](https://linux-hardware.org/?probe=798cae3014) | Nov 10, 2020 |
| ASUSTek       | H81M-K                      | [1f723e288a](https://linux-hardware.org/?probe=1f723e288a) | Nov 10, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [03201eed9f](https://linux-hardware.org/?probe=03201eed9f) | Nov 02, 2020 |
| MSI           | MEG X570 GODLIKE            | [4a05958761](https://linux-hardware.org/?probe=4a05958761) | Nov 02, 2020 |
| MSI           | MEG X570 GODLIKE            | [edc31cec40](https://linux-hardware.org/?probe=edc31cec40) | Nov 02, 2020 |
| ASUSTek       | AM1M-A                      | [c70d54792c](https://linux-hardware.org/?probe=c70d54792c) | Nov 02, 2020 |
| MSI           | MEG X570 GODLIKE            | [0cf92f30e5](https://linux-hardware.org/?probe=0cf92f30e5) | Nov 02, 2020 |
| MSI           | MEG X570 GODLIKE            | [c03cffbb16](https://linux-hardware.org/?probe=c03cffbb16) | Nov 01, 2020 |
| Gigabyte      | 970A-DS3P                   | [7ae3293c6d](https://linux-hardware.org/?probe=7ae3293c6d) | Oct 26, 2020 |
| Gigabyte      | 970A-DS3P                   | [0a0001a9b7](https://linux-hardware.org/?probe=0a0001a9b7) | Oct 26, 2020 |
| ASUSTek       | Z97-A                       | [8bb32c8ffd](https://linux-hardware.org/?probe=8bb32c8ffd) | Oct 25, 2020 |
| MSI           | X370 GAMING PRO             | [f4437f3968](https://linux-hardware.org/?probe=f4437f3968) | Oct 24, 2020 |
| MSI           | X370 GAMING PRO             | [122e44014d](https://linux-hardware.org/?probe=122e44014d) | Oct 24, 2020 |
| ASRock        | Z370 Gaming K6              | [1dbe526fb7](https://linux-hardware.org/?probe=1dbe526fb7) | Oct 23, 2020 |
| MSI           | Indio                       | [71ceefd01b](https://linux-hardware.org/?probe=71ceefd01b) | Oct 22, 2020 |
| MSI           | X370 GAMING PRO             | [97a2fcb2ed](https://linux-hardware.org/?probe=97a2fcb2ed) | Oct 21, 2020 |
| Dell          | 096JG8 A01                  | [f7a82d2603](https://linux-hardware.org/?probe=f7a82d2603) | Oct 20, 2020 |
| Dell          | 096JG8 A01                  | [82b04df3cc](https://linux-hardware.org/?probe=82b04df3cc) | Oct 19, 2020 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [0918a03f76](https://linux-hardware.org/?probe=0918a03f76) | Oct 18, 2020 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [40e6083875](https://linux-hardware.org/?probe=40e6083875) | Oct 18, 2020 |
| MSI           | MEG Z390 GODLIKE            | [c3041be9c4](https://linux-hardware.org/?probe=c3041be9c4) | Oct 18, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [8fd6e1ba2d](https://linux-hardware.org/?probe=8fd6e1ba2d) | Oct 17, 2020 |
| Dell          | 096JG8 A01                  | [f8ae9e55ed](https://linux-hardware.org/?probe=f8ae9e55ed) | Oct 17, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [8c97ce4353](https://linux-hardware.org/?probe=8c97ce4353) | Oct 16, 2020 |
| ASRock        | H81M-HDS                    | [552c5a97ad](https://linux-hardware.org/?probe=552c5a97ad) | Oct 15, 2020 |
| Gigabyte      | GA-770T-D3L                 | [5ce33e265c](https://linux-hardware.org/?probe=5ce33e265c) | Oct 13, 2020 |
| ASUSTek       | P5KPL                       | [df66501d2a](https://linux-hardware.org/?probe=df66501d2a) | Oct 13, 2020 |
| ASUSTek       | H81M-K                      | [590c4967c5](https://linux-hardware.org/?probe=590c4967c5) | Oct 12, 2020 |
| Intel         | DG965RY AAD41691-301        | [22be735dca](https://linux-hardware.org/?probe=22be735dca) | Oct 11, 2020 |
| ASUSTek       | AM1M-A                      | [e7f8db7d2d](https://linux-hardware.org/?probe=e7f8db7d2d) | Oct 10, 2020 |
| ASUSTek       | H81M-K                      | [d382547b3e](https://linux-hardware.org/?probe=d382547b3e) | Oct 08, 2020 |
| MSI           | X58 Pro                     | [cba6a4e0ca](https://linux-hardware.org/?probe=cba6a4e0ca) | Oct 07, 2020 |
| ASRock        | AB350M Pro4                 | [d8f8b18b1f](https://linux-hardware.org/?probe=d8f8b18b1f) | Oct 06, 2020 |
| Gigabyte      | B450M DS3H-CF               | [78d7f53242](https://linux-hardware.org/?probe=78d7f53242) | Oct 06, 2020 |
| Dell          | 088DT1 A01                  | [cfd8413eed](https://linux-hardware.org/?probe=cfd8413eed) | Oct 05, 2020 |
| MSI           | MEG Z390 GODLIKE            | [9176d8042b](https://linux-hardware.org/?probe=9176d8042b) | Oct 04, 2020 |
| ASUSTek       | AM1M-A                      | [12f0e8aae9](https://linux-hardware.org/?probe=12f0e8aae9) | Oct 04, 2020 |
| ASUSTek       | AM1M-A                      | [c621d4658d](https://linux-hardware.org/?probe=c621d4658d) | Oct 04, 2020 |
| MSI           | B350 PC MATE                | [a7f2a8d54b](https://linux-hardware.org/?probe=a7f2a8d54b) | Oct 02, 2020 |
| Dell          | 0Y2MRG A00                  | [6f013ef36c](https://linux-hardware.org/?probe=6f013ef36c) | Sep 30, 2020 |
| Biostar       | B350GT5                     | [ff42dadca1](https://linux-hardware.org/?probe=ff42dadca1) | Sep 29, 2020 |
| DIEBOLD       | Canyon                      | [5c25833f80](https://linux-hardware.org/?probe=5c25833f80) | Sep 29, 2020 |
| Medion        | MS-7848                     | [a251bc7a5c](https://linux-hardware.org/?probe=a251bc7a5c) | Sep 28, 2020 |
| MSI           | B450M MORTAR                | [e75e5bb91f](https://linux-hardware.org/?probe=e75e5bb91f) | Sep 28, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [bf255c3c98](https://linux-hardware.org/?probe=bf255c3c98) | Sep 28, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [8987176239](https://linux-hardware.org/?probe=8987176239) | Sep 28, 2020 |
| MSI           | X370 SLI PLUS               | [b25d5e6b09](https://linux-hardware.org/?probe=b25d5e6b09) | Sep 28, 2020 |
| Acer          | Aspire M3985                | [3725c311ad](https://linux-hardware.org/?probe=3725c311ad) | Sep 28, 2020 |
| Gigabyte      | Z370M D3H-CF                | [538d697d23](https://linux-hardware.org/?probe=538d697d23) | Sep 26, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1774bd11c3](https://linux-hardware.org/?probe=1774bd11c3) | Sep 24, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [fb10ccd835](https://linux-hardware.org/?probe=fb10ccd835) | Sep 23, 2020 |
| Acer          | Aspire M3985                | [479a064f43](https://linux-hardware.org/?probe=479a064f43) | Sep 23, 2020 |
| MSI           | Z77A-G45                    | [28a219f7b8](https://linux-hardware.org/?probe=28a219f7b8) | Sep 23, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [e0da087e62](https://linux-hardware.org/?probe=e0da087e62) | Sep 23, 2020 |
| Acer          | Aspire M3985                | [e0595d76f8](https://linux-hardware.org/?probe=e0595d76f8) | Sep 21, 2020 |
| ASUSTek       | P5P43TD PRO                 | [f83e47f0e9](https://linux-hardware.org/?probe=f83e47f0e9) | Sep 19, 2020 |
| ASRock        | X399 Taichi                 | [785a16d818](https://linux-hardware.org/?probe=785a16d818) | Sep 18, 2020 |
| Acer          | Aspire M3985                | [ec61701cf8](https://linux-hardware.org/?probe=ec61701cf8) | Sep 15, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [5d593a476c](https://linux-hardware.org/?probe=5d593a476c) | Sep 13, 2020 |
| ASUSTek       | PRIME X470-PRO              | [6c0de749d5](https://linux-hardware.org/?probe=6c0de749d5) | Sep 12, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [86fb0acbdf](https://linux-hardware.org/?probe=86fb0acbdf) | Sep 12, 2020 |
| ASRock        | B550M-ITX/ac                | [396dd32667](https://linux-hardware.org/?probe=396dd32667) | Sep 12, 2020 |
| Medion        | MS-7848                     | [3668e2caec](https://linux-hardware.org/?probe=3668e2caec) | Sep 12, 2020 |
| Medion        | MS-7848                     | [3427e264ad](https://linux-hardware.org/?probe=3427e264ad) | Sep 11, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [5b867cbda0](https://linux-hardware.org/?probe=5b867cbda0) | Sep 11, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c735d0a13b](https://linux-hardware.org/?probe=c735d0a13b) | Sep 10, 2020 |
| Lenovo        | 3111 NOK                    | [4d68c428bf](https://linux-hardware.org/?probe=4d68c428bf) | Sep 08, 2020 |
| Acer          | Aspire M3985                | [30a468ed65](https://linux-hardware.org/?probe=30a468ed65) | Sep 08, 2020 |
| Gigabyte      | Z68X-UD3H-B3                | [e99234d123](https://linux-hardware.org/?probe=e99234d123) | Sep 06, 2020 |
| Medion        | H110H4-EM                   | [193fe3a164](https://linux-hardware.org/?probe=193fe3a164) | Sep 05, 2020 |
| Acer          | Aspire M3985                | [c557c40673](https://linux-hardware.org/?probe=c557c40673) | Sep 05, 2020 |
| Gigabyte      | MZGLKBP-00                  | [7438c8fe9b](https://linux-hardware.org/?probe=7438c8fe9b) | Sep 05, 2020 |
| Gigabyte      | MZGLKBP-00                  | [c7f8a0a39c](https://linux-hardware.org/?probe=c7f8a0a39c) | Sep 05, 2020 |
| ASUSTek       | Z87-DELUXE                  | [beeac93f6f](https://linux-hardware.org/?probe=beeac93f6f) | Sep 04, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [81072b442a](https://linux-hardware.org/?probe=81072b442a) | Sep 04, 2020 |
| Acer          | Veriton M6620G v1.0         | [b053a10294](https://linux-hardware.org/?probe=b053a10294) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII HERO           | [2dc46d052a](https://linux-hardware.org/?probe=2dc46d052a) | Sep 04, 2020 |
| ASUSTek       | Q170T                       | [a424aaa559](https://linux-hardware.org/?probe=a424aaa559) | Sep 03, 2020 |
| MSI           | B450M MORTAR TITANIUM       | [0b1a465c7e](https://linux-hardware.org/?probe=0b1a465c7e) | Sep 03, 2020 |
| Gigabyte      | B85M-HD3                    | [587f334b75](https://linux-hardware.org/?probe=587f334b75) | Sep 03, 2020 |
| Gigabyte      | B85M-HD3                    | [1cdb83831f](https://linux-hardware.org/?probe=1cdb83831f) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7d08207f9e](https://linux-hardware.org/?probe=7d08207f9e) | Sep 03, 2020 |
| Gigabyte      | Z97X-SLI-CF                 | [8143531f3d](https://linux-hardware.org/?probe=8143531f3d) | Sep 03, 2020 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [99ae7a119f](https://linux-hardware.org/?probe=99ae7a119f) | Sep 03, 2020 |
| Foxconn       | Napa HP P/N                 | [cacded6248](https://linux-hardware.org/?probe=cacded6248) | Sep 03, 2020 |
| HP            | 2B29                        | [6feb4ff797](https://linux-hardware.org/?probe=6feb4ff797) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [60e951219f](https://linux-hardware.org/?probe=60e951219f) | Sep 03, 2020 |
| Gigabyte      | GA-890FXA-UD5               | [0f7250a912](https://linux-hardware.org/?probe=0f7250a912) | Sep 03, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [99e06533dc](https://linux-hardware.org/?probe=99e06533dc) | Sep 01, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [aa076e6629](https://linux-hardware.org/?probe=aa076e6629) | Aug 31, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c5e277cfc7](https://linux-hardware.org/?probe=c5e277cfc7) | Aug 31, 2020 |
| Gigabyte      | H81M-S2H                    | [52408e3992](https://linux-hardware.org/?probe=52408e3992) | Aug 27, 2020 |
| ASRock        | AB350M Pro4                 | [a5338ac2ec](https://linux-hardware.org/?probe=a5338ac2ec) | Aug 22, 2020 |
| ASRock        | Z390 Taichi Ultimate        | [ca2c2cb5e5](https://linux-hardware.org/?probe=ca2c2cb5e5) | Aug 22, 2020 |
| ASUSTek       | Maximus IX HERO             | [f5ccf116d1](https://linux-hardware.org/?probe=f5ccf116d1) | Aug 20, 2020 |
| ASRock        | Z77 Extreme6                | [a23bd9e79b](https://linux-hardware.org/?probe=a23bd9e79b) | Aug 19, 2020 |
| ASRock        | X570 Taichi                 | [b486cc8b6a](https://linux-hardware.org/?probe=b486cc8b6a) | Aug 19, 2020 |
| ASUSTek       | PRIME B350M-A               | [6561d27ae2](https://linux-hardware.org/?probe=6561d27ae2) | Aug 19, 2020 |
| MSI           | MAG Z490 TOMAHAWK           | [ffd532c8d8](https://linux-hardware.org/?probe=ffd532c8d8) | Aug 16, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [28a075d020](https://linux-hardware.org/?probe=28a075d020) | Aug 14, 2020 |
| Dell          | 00V62H A01                  | [8ff1d70139](https://linux-hardware.org/?probe=8ff1d70139) | Aug 13, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [0647358959](https://linux-hardware.org/?probe=0647358959) | Aug 11, 2020 |
| ASUSTek       | PRIME B550M-K               | [4d18520109](https://linux-hardware.org/?probe=4d18520109) | Aug 11, 2020 |
| Gigabyte      | H81M-S2H                    | [dcf20a16b9](https://linux-hardware.org/?probe=dcf20a16b9) | Aug 09, 2020 |
| Lenovo        | Board                       | [2f13897020](https://linux-hardware.org/?probe=2f13897020) | Aug 06, 2020 |
| HP            | 8648                        | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| ASUSTek       | P8H77-M                     | [88086cbdff](https://linux-hardware.org/?probe=88086cbdff) | Aug 03, 2020 |
| ASUSTek       | H87M-PLUS                   | [82f189206f](https://linux-hardware.org/?probe=82f189206f) | Aug 03, 2020 |
| Medion        | MS-7797                     | [ce762bcc91](https://linux-hardware.org/?probe=ce762bcc91) | Aug 02, 2020 |
| Medion        | MS-7797                     | [203bc1dd8b](https://linux-hardware.org/?probe=203bc1dd8b) | Aug 02, 2020 |
| HP            | 158A                        | [d2e2cc626a](https://linux-hardware.org/?probe=d2e2cc626a) | Jul 31, 2020 |
| Acer          | Aspire XC-704               | [f6a89941ca](https://linux-hardware.org/?probe=f6a89941ca) | Jul 31, 2020 |
| Acer          | Aspire XC-704               | [d0ffbeade6](https://linux-hardware.org/?probe=d0ffbeade6) | Jul 30, 2020 |
| HP            | 158A                        | [9bd1ea0c74](https://linux-hardware.org/?probe=9bd1ea0c74) | Jul 30, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [0a636dfdb5](https://linux-hardware.org/?probe=0a636dfdb5) | Jul 28, 2020 |
| HP            | 158A                        | [f3171ac0ef](https://linux-hardware.org/?probe=f3171ac0ef) | Jul 25, 2020 |
| HP            | 158A                        | [42e3f4387f](https://linux-hardware.org/?probe=42e3f4387f) | Jul 25, 2020 |
| Dell          | 0F428D A00                  | [b9f7c69c36](https://linux-hardware.org/?probe=b9f7c69c36) | Jul 24, 2020 |
| Intel         | DH55PJ AAE93812-301         | [179442d724](https://linux-hardware.org/?probe=179442d724) | Jul 24, 2020 |
| Intel         | DH55PJ AAE93812-301         | [32a9208ef5](https://linux-hardware.org/?probe=32a9208ef5) | Jul 24, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4baceaecb7](https://linux-hardware.org/?probe=4baceaecb7) | Jul 21, 2020 |
| Dell          | 00V62H A01                  | [9430ab8395](https://linux-hardware.org/?probe=9430ab8395) | Jul 19, 2020 |
| Supermicro    | H8DM8-2                     | [1f4f0c96fa](https://linux-hardware.org/?probe=1f4f0c96fa) | Jul 17, 2020 |
| Gigabyte      | 970A-DS3P                   | [791afa1495](https://linux-hardware.org/?probe=791afa1495) | Jul 16, 2020 |
| MSI           | X99S SLI PLUS               | [8fd890832e](https://linux-hardware.org/?probe=8fd890832e) | Jul 16, 2020 |
| Dell          | 00V62H A01                  | [6d4845ef55](https://linux-hardware.org/?probe=6d4845ef55) | Jul 15, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [2c462ab887](https://linux-hardware.org/?probe=2c462ab887) | Jul 13, 2020 |
| Acer          | Aspire TC-780               | [c4f7bce4e6](https://linux-hardware.org/?probe=c4f7bce4e6) | Jul 12, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [bded2d0fa6](https://linux-hardware.org/?probe=bded2d0fa6) | Jul 11, 2020 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [ca7a89df7f](https://linux-hardware.org/?probe=ca7a89df7f) | Jul 08, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [18ab3f62bb](https://linux-hardware.org/?probe=18ab3f62bb) | Jul 05, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [bb89b4812f](https://linux-hardware.org/?probe=bb89b4812f) | Jul 05, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [4716a84af9](https://linux-hardware.org/?probe=4716a84af9) | Jul 03, 2020 |
| ASUSTek       | TUF Z270 MARK 2             | [e6aca4abae](https://linux-hardware.org/?probe=e6aca4abae) | Jul 01, 2020 |
| Dell          | 04GJJT A00                  | [6df3d85768](https://linux-hardware.org/?probe=6df3d85768) | Jun 30, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a7476f7ffe](https://linux-hardware.org/?probe=a7476f7ffe) | Jun 29, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [784dc70b26](https://linux-hardware.org/?probe=784dc70b26) | Jun 28, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [cb7d217b6d](https://linux-hardware.org/?probe=cb7d217b6d) | Jun 24, 2020 |
| ASUSTek       | P6T SE                      | [1c5de1fdb3](https://linux-hardware.org/?probe=1c5de1fdb3) | Jun 24, 2020 |
| ASUSTek       | P6T SE                      | [b9698cae7e](https://linux-hardware.org/?probe=b9698cae7e) | Jun 24, 2020 |
| MSI           | Z170A KRAIT GAMING          | [3a071f3edd](https://linux-hardware.org/?probe=3a071f3edd) | Jun 24, 2020 |
| MSI           | Z170A KRAIT GAMING          | [158c9b2720](https://linux-hardware.org/?probe=158c9b2720) | Jun 24, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [aa6c41b30e](https://linux-hardware.org/?probe=aa6c41b30e) | Jun 23, 2020 |
| HP            | 1825                        | [1ce0ef2f2d](https://linux-hardware.org/?probe=1ce0ef2f2d) | Jun 23, 2020 |
| HP            | 1825                        | [489ee428d6](https://linux-hardware.org/?probe=489ee428d6) | Jun 23, 2020 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c6da8ae1c9](https://linux-hardware.org/?probe=c6da8ae1c9) | Jun 22, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [97a7a654be](https://linux-hardware.org/?probe=97a7a654be) | Jun 21, 2020 |
| ASRock        | B450M Pro4                  | [9a737dddc2](https://linux-hardware.org/?probe=9a737dddc2) | Jun 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [695fff7e67](https://linux-hardware.org/?probe=695fff7e67) | Jun 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f3869139dc](https://linux-hardware.org/?probe=f3869139dc) | Jun 17, 2020 |
| Gigabyte      | 990FXA-UD5                  | [72d0af747c](https://linux-hardware.org/?probe=72d0af747c) | Jun 17, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | [39db0a8a39](https://linux-hardware.org/?probe=39db0a8a39) | Jun 17, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [64101f1e6a](https://linux-hardware.org/?probe=64101f1e6a) | Jun 16, 2020 |
| Gigabyte      | H81M-S2H                    | [413ab9d50f](https://linux-hardware.org/?probe=413ab9d50f) | Jun 15, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [e6a2b8f473](https://linux-hardware.org/?probe=e6a2b8f473) | Jun 13, 2020 |
| MSI           | MEG Z390 GODLIKE            | [e73ed17a6f](https://linux-hardware.org/?probe=e73ed17a6f) | Jun 10, 2020 |
| MSI           | MEG Z390 GODLIKE            | [72f7dbaa26](https://linux-hardware.org/?probe=72f7dbaa26) | Jun 10, 2020 |
| HP            | 8433 11                     | [d2e448a763](https://linux-hardware.org/?probe=d2e448a763) | Jun 09, 2020 |
| HP            | 8433 11                     | [96218ef966](https://linux-hardware.org/?probe=96218ef966) | Jun 08, 2020 |
| HP            | 8433 11                     | [a1997f1703](https://linux-hardware.org/?probe=a1997f1703) | Jun 08, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1719093b0f](https://linux-hardware.org/?probe=1719093b0f) | Jun 08, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7270020fe2](https://linux-hardware.org/?probe=7270020fe2) | Jun 04, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1f6dc07299](https://linux-hardware.org/?probe=1f6dc07299) | Jun 01, 2020 |
| MSI           | MEG Z390 GODLIKE            | [0b0469ad5f](https://linux-hardware.org/?probe=0b0469ad5f) | Jun 01, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [63c64427d6](https://linux-hardware.org/?probe=63c64427d6) | May 30, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [dec2e5c845](https://linux-hardware.org/?probe=dec2e5c845) | May 29, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [003ef1954f](https://linux-hardware.org/?probe=003ef1954f) | May 28, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [d7b31a9899](https://linux-hardware.org/?probe=d7b31a9899) | May 27, 2020 |
| Gigabyte      | H81M-S2H                    | [d7fbb16bc0](https://linux-hardware.org/?probe=d7fbb16bc0) | May 27, 2020 |
| Gigabyte      | 990FXA-UD5                  | [360fae2046](https://linux-hardware.org/?probe=360fae2046) | May 27, 2020 |
| Gigabyte      | 990FXA-UD5                  | [04fb6710a5](https://linux-hardware.org/?probe=04fb6710a5) | May 27, 2020 |
| Gigabyte      | 990FXA-UD5                  | [38836b62c5](https://linux-hardware.org/?probe=38836b62c5) | May 26, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | [8665d72931](https://linux-hardware.org/?probe=8665d72931) | May 26, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | [dec98ca9eb](https://linux-hardware.org/?probe=dec98ca9eb) | May 26, 2020 |
| ASRock        | 880GM-LE FX                 | [45c1c813cb](https://linux-hardware.org/?probe=45c1c813cb) | May 26, 2020 |
| ASUSTek       | PRIME Z270-P                | [22b5cb911a](https://linux-hardware.org/?probe=22b5cb911a) | May 25, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [2128da7edf](https://linux-hardware.org/?probe=2128da7edf) | May 25, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [93ee9d0fdb](https://linux-hardware.org/?probe=93ee9d0fdb) | May 25, 2020 |
| Dell          | 0DR845                      | [1f3a84e812](https://linux-hardware.org/?probe=1f3a84e812) | May 25, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | [233f8405a6](https://linux-hardware.org/?probe=233f8405a6) | May 25, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [ac00b230f5](https://linux-hardware.org/?probe=ac00b230f5) | May 23, 2020 |
| Gigabyte      | H67N-USB3-B3                | [94a4ed5b7d](https://linux-hardware.org/?probe=94a4ed5b7d) | May 23, 2020 |
| Gigabyte      | H81M-S2H                    | [9c2f044bc2](https://linux-hardware.org/?probe=9c2f044bc2) | May 23, 2020 |
| Gigabyte      | H110M-S2HP-CF               | [21606791e1](https://linux-hardware.org/?probe=21606791e1) | May 19, 2020 |
| Dell          | 09M8Y8 A01                  | [3a804e8e43](https://linux-hardware.org/?probe=3a804e8e43) | May 18, 2020 |
| MSI           | X470 GAMING PLUS            | [fed539c9e2](https://linux-hardware.org/?probe=fed539c9e2) | May 18, 2020 |
| MSI           | X470 GAMING PLUS            | [5232622f02](https://linux-hardware.org/?probe=5232622f02) | May 18, 2020 |
| Gigabyte      | 970A-DS3P                   | [c12a90607f](https://linux-hardware.org/?probe=c12a90607f) | May 17, 2020 |
| MSI           | MEG Z390 GODLIKE            | [cc598bd270](https://linux-hardware.org/?probe=cc598bd270) | May 17, 2020 |
| Google        | Guado                       | [5f3d8d81f3](https://linux-hardware.org/?probe=5f3d8d81f3) | May 17, 2020 |
| HP            | 1905                        | [e70c3c026a](https://linux-hardware.org/?probe=e70c3c026a) | May 16, 2020 |
| Gigabyte      | 970A-DS3P                   | [ce3d0cc419](https://linux-hardware.org/?probe=ce3d0cc419) | May 14, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [e4f774c6a4](https://linux-hardware.org/?probe=e4f774c6a4) | May 13, 2020 |
| HP            | 822A                        | [82bed7ba0b](https://linux-hardware.org/?probe=82bed7ba0b) | May 13, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [0345580dec](https://linux-hardware.org/?probe=0345580dec) | May 12, 2020 |
| Dell          | 09M8Y8 A01                  | [b7320814a2](https://linux-hardware.org/?probe=b7320814a2) | May 12, 2020 |
| Gigabyte      | H110M-S2HP-CF               | [8630d54b37](https://linux-hardware.org/?probe=8630d54b37) | May 11, 2020 |
| Gigabyte      | A320MA-M.2-CF               | [bd1f929037](https://linux-hardware.org/?probe=bd1f929037) | May 10, 2020 |
| Gigabyte      | A320MA-M.2-CF               | [a654ccb289](https://linux-hardware.org/?probe=a654ccb289) | May 10, 2020 |
| MSI           | Z97 GAMING 5                | [0db6d36330](https://linux-hardware.org/?probe=0db6d36330) | May 06, 2020 |
| ASRock        | 890GM Pro3                  | [b5514f03ef](https://linux-hardware.org/?probe=b5514f03ef) | May 05, 2020 |
| HP            | 822A                        | [84288e49fa](https://linux-hardware.org/?probe=84288e49fa) | May 05, 2020 |
| HP            | 822A                        | [e0bc279762](https://linux-hardware.org/?probe=e0bc279762) | May 05, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [2986f65f6b](https://linux-hardware.org/?probe=2986f65f6b) | May 01, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [cc3ecb19e0](https://linux-hardware.org/?probe=cc3ecb19e0) | Apr 30, 2020 |
| ASUSTek       | M3A78                       | [879a14441e](https://linux-hardware.org/?probe=879a14441e) | Apr 29, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [37bfd5d148](https://linux-hardware.org/?probe=37bfd5d148) | Apr 27, 2020 |
| ASUSTek       | H81M-PLUS                   | [c9d4915469](https://linux-hardware.org/?probe=c9d4915469) | Apr 27, 2020 |
| ASUSTek       | H81M-PLUS                   | [1fdfd4394d](https://linux-hardware.org/?probe=1fdfd4394d) | Apr 27, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | [2c436dd9bf](https://linux-hardware.org/?probe=2c436dd9bf) | Apr 27, 2020 |
| Dell          | 097YXY A00                  | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c3c633e36f](https://linux-hardware.org/?probe=c3c633e36f) | Apr 26, 2020 |
| Gigabyte      | X570 AORUS PRO              | [ec1917c4e3](https://linux-hardware.org/?probe=ec1917c4e3) | Apr 23, 2020 |
| ASUSTek       | PRIME B350M-A               | [da172ed7c3](https://linux-hardware.org/?probe=da172ed7c3) | Apr 23, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [d06586599f](https://linux-hardware.org/?probe=d06586599f) | Apr 22, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [5a09500036](https://linux-hardware.org/?probe=5a09500036) | Apr 22, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [0958e66dbf](https://linux-hardware.org/?probe=0958e66dbf) | Apr 21, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a8c1bea204](https://linux-hardware.org/?probe=a8c1bea204) | Apr 21, 2020 |
| Lenovo        | Annapurna CRB 0B98401 PR... | [8c19809e10](https://linux-hardware.org/?probe=8c19809e10) | Apr 21, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [3146716bfc](https://linux-hardware.org/?probe=3146716bfc) | Apr 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f725798cf2](https://linux-hardware.org/?probe=f725798cf2) | Apr 20, 2020 |
| MSI           | B350 TOMAHAWK               | [e1944a055b](https://linux-hardware.org/?probe=e1944a055b) | Apr 19, 2020 |
| MSI           | B350 TOMAHAWK               | [e03b573d31](https://linux-hardware.org/?probe=e03b573d31) | Apr 19, 2020 |
| MSI           | B350 TOMAHAWK               | [15357f1dc2](https://linux-hardware.org/?probe=15357f1dc2) | Apr 19, 2020 |
| ASRock        | A320M-HDV                   | [66f9f9a7df](https://linux-hardware.org/?probe=66f9f9a7df) | Apr 16, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b6f50271de](https://linux-hardware.org/?probe=b6f50271de) | Apr 15, 2020 |
| MSI           | FM2-A55M-E33                | [2e15f64ca6](https://linux-hardware.org/?probe=2e15f64ca6) | Apr 14, 2020 |
| Lenovo        | 36E1 SDK0J40709 WIN 3259... | [31f5158c61](https://linux-hardware.org/?probe=31f5158c61) | Apr 14, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [3eaeee5b22](https://linux-hardware.org/?probe=3eaeee5b22) | Apr 13, 2020 |
| Gigabyte      | GA-880GA-UD3H               | [8197dc4f8f](https://linux-hardware.org/?probe=8197dc4f8f) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [8ceac6a75e](https://linux-hardware.org/?probe=8ceac6a75e) | Apr 13, 2020 |
| ASUSTek       | Z97-PRO GAMER               | [6b51a788d2](https://linux-hardware.org/?probe=6b51a788d2) | Apr 13, 2020 |
| ASRock        | B450M Pro4                  | [7f112b58fe](https://linux-hardware.org/?probe=7f112b58fe) | Apr 12, 2020 |
| Gigabyte      | 970A-D3P                    | [449ab89e8c](https://linux-hardware.org/?probe=449ab89e8c) | Apr 12, 2020 |
| Gigabyte      | 970A-D3P                    | [7ac396ba62](https://linux-hardware.org/?probe=7ac396ba62) | Apr 12, 2020 |
| Dell          | 0VNP2H A00                  | [6dd524702e](https://linux-hardware.org/?probe=6dd524702e) | Apr 12, 2020 |
| Pegatron      | 2A72h                       | [43f56b437b](https://linux-hardware.org/?probe=43f56b437b) | Apr 12, 2020 |
| Biostar       | A880G+                      | [169a70380e](https://linux-hardware.org/?probe=169a70380e) | Apr 12, 2020 |
| HP            | 8433 11                     | [f79160e1f6](https://linux-hardware.org/?probe=f79160e1f6) | Apr 12, 2020 |
| ASUSTek       | M51BC                       | [c61af9649b](https://linux-hardware.org/?probe=c61af9649b) | Apr 12, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [f1846c7ae8](https://linux-hardware.org/?probe=f1846c7ae8) | Apr 12, 2020 |
| ASUSTek       | H87I-PLUS                   | [c3c3ea78d0](https://linux-hardware.org/?probe=c3c3ea78d0) | Apr 12, 2020 |
| Gigabyte      | GA-770TA-UD3                | [c151f1651f](https://linux-hardware.org/?probe=c151f1651f) | Apr 12, 2020 |
| Fujitsu Si... | D1607 S26361-D1607          | [1661b7d010](https://linux-hardware.org/?probe=1661b7d010) | Apr 12, 2020 |
| Gigabyte      | 970A-D3P                    | [c03441526e](https://linux-hardware.org/?probe=c03441526e) | Apr 12, 2020 |
| Gigabyte      | 970A-D3P                    | [6ec6835b0a](https://linux-hardware.org/?probe=6ec6835b0a) | Apr 12, 2020 |
| ASRock        | A320M-HDV                   | [0e6f3cc091](https://linux-hardware.org/?probe=0e6f3cc091) | Apr 11, 2020 |
| ASRock        | A320M-HDV                   | [70bac91022](https://linux-hardware.org/?probe=70bac91022) | Apr 11, 2020 |
| HP            | 8437                        | [24e23f7e67](https://linux-hardware.org/?probe=24e23f7e67) | Apr 10, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [2308221e30](https://linux-hardware.org/?probe=2308221e30) | Apr 10, 2020 |
| Gigabyte      | Z170X-Gaming 7              | [8bac27b06a](https://linux-hardware.org/?probe=8bac27b06a) | Apr 10, 2020 |
| Gigabyte      | 970A-DS3P                   | [de4d109652](https://linux-hardware.org/?probe=de4d109652) | Apr 10, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [7f3d569b8b](https://linux-hardware.org/?probe=7f3d569b8b) | Apr 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [f1545c9695](https://linux-hardware.org/?probe=f1545c9695) | Apr 10, 2020 |
| Gigabyte      | F2A85XM-D3H                 | [b6def0a686](https://linux-hardware.org/?probe=b6def0a686) | Apr 09, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [bb9c4ad1ed](https://linux-hardware.org/?probe=bb9c4ad1ed) | Apr 09, 2020 |
| MSI           | X370 SLI PLUS               | [a111432dee](https://linux-hardware.org/?probe=a111432dee) | Apr 09, 2020 |
| MSI           | X370 SLI PLUS               | [98a083da5b](https://linux-hardware.org/?probe=98a083da5b) | Apr 09, 2020 |
| MSI           | X370 SLI PLUS               | [f7d08ce703](https://linux-hardware.org/?probe=f7d08ce703) | Apr 09, 2020 |
| ASUSTek       | M5A78L-M LX                 | [604ede218b](https://linux-hardware.org/?probe=604ede218b) | Apr 09, 2020 |
| MSI           | X370 SLI PLUS               | [dc1b100155](https://linux-hardware.org/?probe=dc1b100155) | Apr 09, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [acd2b87f9f](https://linux-hardware.org/?probe=acd2b87f9f) | Apr 09, 2020 |
| Gigabyte      | M68MT-S2                    | [f3a49b7907](https://linux-hardware.org/?probe=f3a49b7907) | Apr 09, 2020 |
| MSI           | X370 SLI PLUS               | [844bed690b](https://linux-hardware.org/?probe=844bed690b) | Apr 09, 2020 |
| DIEBOLD       | Canyon                      | [83b52be34c](https://linux-hardware.org/?probe=83b52be34c) | Apr 09, 2020 |
| ASRock        | Z77 Extreme6                | [69895f85c2](https://linux-hardware.org/?probe=69895f85c2) | Apr 09, 2020 |
| ASRock        | B450M Pro4                  | [795e66049a](https://linux-hardware.org/?probe=795e66049a) | Apr 09, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | [6fffa039fc](https://linux-hardware.org/?probe=6fffa039fc) | Apr 09, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [71673b2f86](https://linux-hardware.org/?probe=71673b2f86) | Apr 09, 2020 |
| Gigabyte      | AX370-Gaming K7             | [cb7cfa0268](https://linux-hardware.org/?probe=cb7cfa0268) | Apr 09, 2020 |
| ASUSTek       | P8Z68-M PRO                 | [8d38bc00af](https://linux-hardware.org/?probe=8d38bc00af) | Apr 09, 2020 |
| ASUSTek       | P8Z68-M PRO                 | [8c5f7b117d](https://linux-hardware.org/?probe=8c5f7b117d) | Apr 09, 2020 |
| ASRock        | A320M-HDV R4.0              | [4902daa1c7](https://linux-hardware.org/?probe=4902daa1c7) | Apr 09, 2020 |
| ASUSTek       | PRIME B350M-A               | [203434d1a8](https://linux-hardware.org/?probe=203434d1a8) | Apr 09, 2020 |
| ASUSTek       | PRIME B350M-A               | [7eebc9f6a9](https://linux-hardware.org/?probe=7eebc9f6a9) | Apr 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [5e1b7d402f](https://linux-hardware.org/?probe=5e1b7d402f) | Apr 08, 2020 |
| ASRock        | B450 Pro4                   | [71e5855b1a](https://linux-hardware.org/?probe=71e5855b1a) | Apr 08, 2020 |
| ASUSTek       | H170 PRO GAMING             | [f9c3afb706](https://linux-hardware.org/?probe=f9c3afb706) | Apr 08, 2020 |
| MSI           | Z68MA-G45                   | [229758509f](https://linux-hardware.org/?probe=229758509f) | Apr 08, 2020 |
| Biostar       | TB250-BTC                   | [fd92f418b8](https://linux-hardware.org/?probe=fd92f418b8) | Apr 08, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [920263168c](https://linux-hardware.org/?probe=920263168c) | Apr 08, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | [87c2007b42](https://linux-hardware.org/?probe=87c2007b42) | Apr 08, 2020 |
| MSI           | X370 SLI PLUS               | [aac9ecac91](https://linux-hardware.org/?probe=aac9ecac91) | Apr 08, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [760ea332f8](https://linux-hardware.org/?probe=760ea332f8) | Apr 08, 2020 |
| MSI           | P67A-C43                    | [15193eda95](https://linux-hardware.org/?probe=15193eda95) | Apr 08, 2020 |
| MSI           | P67A-C43                    | [be8d0e4abe](https://linux-hardware.org/?probe=be8d0e4abe) | Apr 08, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | [e1d0e412e7](https://linux-hardware.org/?probe=e1d0e412e7) | Apr 08, 2020 |
| MSI           | X370 SLI PLUS               | [883833d655](https://linux-hardware.org/?probe=883833d655) | Apr 08, 2020 |
| MSI           | X370 SLI PLUS               | [679b5cc9cb](https://linux-hardware.org/?probe=679b5cc9cb) | Apr 08, 2020 |
| Gigabyte      | H97-D3H-CF                  | [67bd6bf866](https://linux-hardware.org/?probe=67bd6bf866) | Apr 08, 2020 |
| MSI           | B350 TOMAHAWK PLUS          | [0f3d865cbd](https://linux-hardware.org/?probe=0f3d865cbd) | Apr 08, 2020 |
| Gigabyte      | B250M-D2V-CF                | [45b9a81a90](https://linux-hardware.org/?probe=45b9a81a90) | Apr 08, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [de6b6acddd](https://linux-hardware.org/?probe=de6b6acddd) | Apr 08, 2020 |
| ASRock        | H97M Pro4                   | [bdd035da9e](https://linux-hardware.org/?probe=bdd035da9e) | Apr 08, 2020 |
| Lenovo        | SHARKBAY NOK                | [ca34648c4b](https://linux-hardware.org/?probe=ca34648c4b) | Apr 08, 2020 |
| Gigabyte      | X570 AORUS PRO              | [7a88b309fd](https://linux-hardware.org/?probe=7a88b309fd) | Apr 08, 2020 |
| MSI           | B450 GAMING PLUS            | [e295329f75](https://linux-hardware.org/?probe=e295329f75) | Apr 07, 2020 |
| Dell          | 09M8Y8 A01                  | [9039b2afe5](https://linux-hardware.org/?probe=9039b2afe5) | Mar 30, 2020 |
| ASRock        | H61M-DGS                    | [edd5290992](https://linux-hardware.org/?probe=edd5290992) | Mar 25, 2020 |
| HP            | 3032h                       | [9b8163360b](https://linux-hardware.org/?probe=9b8163360b) | Mar 24, 2020 |
| ASRock        | H61M-DGS                    | [0139ccfe4a](https://linux-hardware.org/?probe=0139ccfe4a) | Mar 22, 2020 |
| ASRock        | H61M-DGS                    | [9962376871](https://linux-hardware.org/?probe=9962376871) | Mar 22, 2020 |
| ASRock        | H61M-DGS                    | [118eb7eb96](https://linux-hardware.org/?probe=118eb7eb96) | Mar 22, 2020 |
| HP            | 3048h                       | [6b07a41174](https://linux-hardware.org/?probe=6b07a41174) | Mar 22, 2020 |
| Dell          | 084J0R A00                  | [f2cabfea35](https://linux-hardware.org/?probe=f2cabfea35) | Mar 17, 2020 |
| Gigabyte      | B250M-D3H-CF                | [41ce1c95ce](https://linux-hardware.org/?probe=41ce1c95ce) | Mar 10, 2020 |
| HP            | 0AE8h C                     | [b182587f12](https://linux-hardware.org/?probe=b182587f12) | Mar 07, 2020 |
| HP            | 0AE8h C                     | [b95ac0485f](https://linux-hardware.org/?probe=b95ac0485f) | Mar 07, 2020 |
| Gigabyte      | B250M-D3H-CF                | [6405e327cc](https://linux-hardware.org/?probe=6405e327cc) | Mar 06, 2020 |
| Dell          | 084J0R A00                  | [6fd4795631](https://linux-hardware.org/?probe=6fd4795631) | Mar 06, 2020 |
| Dell          | 084J0R A00                  | [b06cc1739a](https://linux-hardware.org/?probe=b06cc1739a) | Mar 06, 2020 |
| Dell          | 084J0R A00                  | [3f74c47989](https://linux-hardware.org/?probe=3f74c47989) | Mar 03, 2020 |
| Lenovo        | Board                       | [6508f3b3de](https://linux-hardware.org/?probe=6508f3b3de) | Feb 25, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [4f7acb111a](https://linux-hardware.org/?probe=4f7acb111a) | Feb 24, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [b7a513c4e6](https://linux-hardware.org/?probe=b7a513c4e6) | Feb 24, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [6f8a149f72](https://linux-hardware.org/?probe=6f8a149f72) | Feb 21, 2020 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [c6b9727054](https://linux-hardware.org/?probe=c6b9727054) | Feb 15, 2020 |
| Dell          | 0GXM1W A00                  | [56a2970914](https://linux-hardware.org/?probe=56a2970914) | Feb 10, 2020 |
| Gigabyte      | A320M-S2H-CF                | [a7cfce1ebe](https://linux-hardware.org/?probe=a7cfce1ebe) | Feb 06, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [e028d403a9](https://linux-hardware.org/?probe=e028d403a9) | Feb 05, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [cf22e622d2](https://linux-hardware.org/?probe=cf22e622d2) | Feb 05, 2020 |
| MSI           | B350 PC MATE                | [d14ee2bdd4](https://linux-hardware.org/?probe=d14ee2bdd4) | Feb 04, 2020 |
| Medion        | MS-7848                     | [9d104875df](https://linux-hardware.org/?probe=9d104875df) | Feb 03, 2020 |
| MSI           | B450 GAMING PLUS            | [8d6516324f](https://linux-hardware.org/?probe=8d6516324f) | Jan 30, 2020 |
| MSI           | MS-7309                     | [0fffa9ba11](https://linux-hardware.org/?probe=0fffa9ba11) | Jan 26, 2020 |
| MSI           | X570-A PRO                  | [b64fcb103c](https://linux-hardware.org/?probe=b64fcb103c) | Jan 25, 2020 |
| Gigabyte      | GA-970A-D3                  | [ad451ce81e](https://linux-hardware.org/?probe=ad451ce81e) | Jan 25, 2020 |
| Gigabyte      | GA-990XA-UD3                | [c89885a42e](https://linux-hardware.org/?probe=c89885a42e) | Jan 25, 2020 |
| ASUSTek       | P8Z77-M PRO                 | [d084db3066](https://linux-hardware.org/?probe=d084db3066) | Jan 23, 2020 |
| MSI           | MS-7309                     | [9a6f3e5a8b](https://linux-hardware.org/?probe=9a6f3e5a8b) | Jan 21, 2020 |
| Medion        | MS-7848                     | [ea96168a9c](https://linux-hardware.org/?probe=ea96168a9c) | Jan 20, 2020 |
| Medion        | MS-7848                     | [67f9c1a688](https://linux-hardware.org/?probe=67f9c1a688) | Jan 20, 2020 |
| Acer          | Aspire TC-780               | [01fbbc4feb](https://linux-hardware.org/?probe=01fbbc4feb) | Jan 18, 2020 |
| Gigabyte      | 970A-DS3P                   | [87e363c1ed](https://linux-hardware.org/?probe=87e363c1ed) | Jan 10, 2020 |
| Intel         | DH87RL AAG74240-401         | [f85d4dd5e7](https://linux-hardware.org/?probe=f85d4dd5e7) | Jan 08, 2020 |
| Acer          | Aspire TC-780               | [81fd4a66b2](https://linux-hardware.org/?probe=81fd4a66b2) | Jan 06, 2020 |
| MSI           | B450M GAMING PLUS           | [c1f215d1ee](https://linux-hardware.org/?probe=c1f215d1ee) | Jan 05, 2020 |
| HP            | 1495                        | [b21c21a7ce](https://linux-hardware.org/?probe=b21c21a7ce) | Jan 04, 2020 |
| Gigabyte      | Z170-D3H-CF                 | [dedece32f6](https://linux-hardware.org/?probe=dedece32f6) | Jan 03, 2020 |
| MSI           | MS-7048                     | [4dcc71b299](https://linux-hardware.org/?probe=4dcc71b299) | Jan 02, 2020 |
| HP            | 1495                        | [adfa2d3bf5](https://linux-hardware.org/?probe=adfa2d3bf5) | Dec 31, 2019 |
| Gigabyte      | B450M DS3H-CF               | [a417810d4b](https://linux-hardware.org/?probe=a417810d4b) | Dec 27, 2019 |
| Gigabyte      | B450 AORUS M                | [c188ce2fce](https://linux-hardware.org/?probe=c188ce2fce) | Dec 21, 2019 |
| Pegatron      | 2AAE                        | [04a6d42a9c](https://linux-hardware.org/?probe=04a6d42a9c) | Dec 16, 2019 |
| Pegatron      | 2AAE                        | [e142be5f58](https://linux-hardware.org/?probe=e142be5f58) | Dec 16, 2019 |
| Gigabyte      | 970A-DS3P                   | [b815184d9d](https://linux-hardware.org/?probe=b815184d9d) | Dec 02, 2019 |
| ASUSTek       | P5B                         | [de0dc42ca0](https://linux-hardware.org/?probe=de0dc42ca0) | Dec 02, 2019 |
| Biostar       | H77MU3                      | [7ba4eeca79](https://linux-hardware.org/?probe=7ba4eeca79) | Nov 20, 2019 |
| MSI           | Z77A-G41                    | [d1d0ab7e31](https://linux-hardware.org/?probe=d1d0ab7e31) | Nov 16, 2019 |
| ASRock        | H61M-VG3                    | [6bc9ab22bf](https://linux-hardware.org/?probe=6bc9ab22bf) | Nov 11, 2019 |
| ASRock        | B450M Pro4-F                | [51675839c0](https://linux-hardware.org/?probe=51675839c0) | Nov 04, 2019 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [71ef38cc7d](https://linux-hardware.org/?probe=71ef38cc7d) | Oct 28, 2019 |
| ASRock        | Z87 Extreme6                | [64d726ac52](https://linux-hardware.org/?probe=64d726ac52) | Oct 27, 2019 |
| ASUSTek       | Z87-K                       | [a2c50a6a82](https://linux-hardware.org/?probe=a2c50a6a82) | Oct 22, 2019 |
| ASRock        | H61M-VG3                    | [260918f990](https://linux-hardware.org/?probe=260918f990) | Oct 22, 2019 |
| ASUSTek       | Z97-A                       | [598c1572b3](https://linux-hardware.org/?probe=598c1572b3) | Oct 15, 2019 |
| MSI           | MS-7048                     | [8225c7bb98](https://linux-hardware.org/?probe=8225c7bb98) | Oct 04, 2019 |
| MSI           | MS-7048                     | [d98422ed35](https://linux-hardware.org/?probe=d98422ed35) | Oct 03, 2019 |
| Shuttle       | FP35 V10                    | [35d850590e](https://linux-hardware.org/?probe=35d850590e) | Oct 01, 2019 |
| Shuttle       | FP35 V10                    | [a2b4a0fbcc](https://linux-hardware.org/?probe=a2b4a0fbcc) | Oct 01, 2019 |
| Shuttle       | FP35 V10                    | [9ed4b8a5ee](https://linux-hardware.org/?probe=9ed4b8a5ee) | Sep 30, 2019 |
| Gigabyte      | P43-ES3G                    | [952d56c4c1](https://linux-hardware.org/?probe=952d56c4c1) | Sep 28, 2019 |
| Supermicro    | X9DA7/E                     | [9f3d443a21](https://linux-hardware.org/?probe=9f3d443a21) | Sep 17, 2019 |
| Supermicro    | X9DA7/E                     | [785db6577d](https://linux-hardware.org/?probe=785db6577d) | Sep 17, 2019 |
| Supermicro    | X9DA7/E                     | [ab89363e0f](https://linux-hardware.org/?probe=ab89363e0f) | Sep 17, 2019 |
| MSI           | MS-7048                     | [48b394b217](https://linux-hardware.org/?probe=48b394b217) | Sep 05, 2019 |
| MSI           | MS-7048                     | [cde038225b](https://linux-hardware.org/?probe=cde038225b) | Sep 05, 2019 |
| Gigabyte      | P43-ES3G                    | [c8de65a837](https://linux-hardware.org/?probe=c8de65a837) | Sep 05, 2019 |
| Gigabyte      | 970A-DS3P                   | [77ed1ace9f](https://linux-hardware.org/?probe=77ed1ace9f) | Sep 05, 2019 |
| MSI           | NF980-G65                   | [1d2ea48480](https://linux-hardware.org/?probe=1d2ea48480) | Sep 05, 2019 |
| Gigabyte      | P43-ES3G                    | [1bb0edaec6](https://linux-hardware.org/?probe=1bb0edaec6) | Sep 05, 2019 |
| Gigabyte      | P43-ES3G                    | [f9e7d5b085](https://linux-hardware.org/?probe=f9e7d5b085) | Sep 05, 2019 |
| Gigabyte      | 970A-DS3P                   | [f7937043a3](https://linux-hardware.org/?probe=f7937043a3) | Sep 05, 2019 |
| ASUSTek       | PRIME Z390M-PLUS            | [c8c1a01026](https://linux-hardware.org/?probe=c8c1a01026) | Sep 04, 2019 |
| Shuttle       | FP35 V10                    | [d8c7a02357](https://linux-hardware.org/?probe=d8c7a02357) | Aug 30, 2019 |
| Shuttle       | FP35 V10                    | [c0abdbed5a](https://linux-hardware.org/?probe=c0abdbed5a) | Aug 27, 2019 |
| Shuttle       | FP35 V10                    | [df01bd0431](https://linux-hardware.org/?probe=df01bd0431) | Aug 27, 2019 |
| Shuttle       | FP35 V10                    | [a5bdb01259](https://linux-hardware.org/?probe=a5bdb01259) | Aug 27, 2019 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [64e705b2f7](https://linux-hardware.org/?probe=64e705b2f7) | Aug 26, 2019 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [1ae52124aa](https://linux-hardware.org/?probe=1ae52124aa) | Aug 25, 2019 |
| ASRock        | EP2C602                     | [1fe7eac8e2](https://linux-hardware.org/?probe=1fe7eac8e2) | Aug 07, 2019 |
| Dell          | 0KWVT8 A02                  | [6b93dc7fb4](https://linux-hardware.org/?probe=6b93dc7fb4) | Aug 03, 2019 |
| Dell          | 0KWVT8 A02                  | [9ee9dee119](https://linux-hardware.org/?probe=9ee9dee119) | Jul 29, 2019 |
| Intel         | DCP847SKE G80890-106        | [bd61649f10](https://linux-hardware.org/?probe=bd61649f10) | Jul 03, 2019 |
| Intel         | DCP847SKE G80890-106        | [1430dfc991](https://linux-hardware.org/?probe=1430dfc991) | Jul 03, 2019 |
| ASUSTek       | P8Z77-V                     | [6b863a586e](https://linux-hardware.org/?probe=6b863a586e) | Jun 03, 2019 |
| Gigabyte      | H61M-D2H-USB3               | [a0d9e50d4f](https://linux-hardware.org/?probe=a0d9e50d4f) | May 25, 2019 |
| Acer          | Veriton M6620G v1.0         | [4f1a9afa27](https://linux-hardware.org/?probe=4f1a9afa27) | May 21, 2019 |
| Gigabyte      | H61M-D2H-USB3               | [d6570c97a4](https://linux-hardware.org/?probe=d6570c97a4) | May 21, 2019 |
| Gigabyte      | H61M-D2H-USB3               | [ce6816fc41](https://linux-hardware.org/?probe=ce6816fc41) | May 21, 2019 |
| Acer          | Veriton M6620G v1.0         | [2addfaabb1](https://linux-hardware.org/?probe=2addfaabb1) | May 10, 2019 |
| Acer          | Veriton M6620G v1.0         | [cdbfe9b945](https://linux-hardware.org/?probe=cdbfe9b945) | May 09, 2019 |
| ASUSTek       | WS X299 PRO                 | [b31f25bbb7](https://linux-hardware.org/?probe=b31f25bbb7) | May 07, 2019 |
| ASUSTek       | Z87-PRO                     | [d4224e0573](https://linux-hardware.org/?probe=d4224e0573) | May 07, 2019 |
| Dell          | 0HHV7N A00                  | [945e8a152d](https://linux-hardware.org/?probe=945e8a152d) | May 06, 2019 |
| Gigabyte      | 970A-DS3P                   | [ccb5735996](https://linux-hardware.org/?probe=ccb5735996) | Apr 29, 2019 |
| Acer          | Veriton M6620G v1.0         | [d5403368f6](https://linux-hardware.org/?probe=d5403368f6) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [93b787642a](https://linux-hardware.org/?probe=93b787642a) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | [b9cd480eb4](https://linux-hardware.org/?probe=b9cd480eb4) | Apr 27, 2019 |
| Acer          | Veriton M6620G v1.0         | [1c42aae9b4](https://linux-hardware.org/?probe=1c42aae9b4) | Apr 27, 2019 |
| HP            | ProLiant ML150 Gen9         | [d9b1ec3c37](https://linux-hardware.org/?probe=d9b1ec3c37) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | [d61584bf4e](https://linux-hardware.org/?probe=d61584bf4e) | Apr 09, 2019 |
| Gigabyte      | GA-970A-D3                  | [992ca3cb87](https://linux-hardware.org/?probe=992ca3cb87) | Apr 04, 2019 |
| ASUSTek       | M5A78L-M LX/BR              | [632d68aab1](https://linux-hardware.org/?probe=632d68aab1) | Mar 26, 2019 |
| Gigabyte      | P55-UD3R                    | [a25feab854](https://linux-hardware.org/?probe=a25feab854) | Mar 16, 2019 |
| Gigabyte      | 970A-DS3P                   | [4c611c79d7](https://linux-hardware.org/?probe=4c611c79d7) | Feb 13, 2019 |
| Gigabyte      | 970A-DS3P                   | [cbe60f7c7a](https://linux-hardware.org/?probe=cbe60f7c7a) | Feb 13, 2019 |
| HP            | 158A                        | [00f1a302b7](https://linux-hardware.org/?probe=00f1a302b7) | Feb 12, 2019 |
| HP            | 1588h                       | [afc50ce0ed](https://linux-hardware.org/?probe=afc50ce0ed) | Jan 26, 2019 |
| HP            | 1496                        | [c87500a262](https://linux-hardware.org/?probe=c87500a262) | Jan 23, 2019 |
| Lenovo        | MAHOBAY 0B98417 WIN         | [662d44bbb5](https://linux-hardware.org/?probe=662d44bbb5) | Jan 23, 2019 |
| Lenovo        | Board                       | [708c1fb33a](https://linux-hardware.org/?probe=708c1fb33a) | Jan 23, 2019 |
| Dell          | 0D28YY A03                  | [fcda7926df](https://linux-hardware.org/?probe=fcda7926df) | Jan 23, 2019 |
| HP            | 3047h                       | [ca7500c321](https://linux-hardware.org/?probe=ca7500c321) | Jan 23, 2019 |
| HP            | 1588h                       | [884857a1eb](https://linux-hardware.org/?probe=884857a1eb) | Jan 22, 2019 |
| HP            | ProLiant MicroServer        | [25d7f09346](https://linux-hardware.org/?probe=25d7f09346) | Jan 22, 2019 |
| HP            | ProLiant MicroServer        | [2df53ac534](https://linux-hardware.org/?probe=2df53ac534) | Jan 22, 2019 |
| HP            | 1496                        | [8dcc85af72](https://linux-hardware.org/?probe=8dcc85af72) | Jan 20, 2019 |
| HP            | 158A                        | [0c8ebd505c](https://linux-hardware.org/?probe=0c8ebd505c) | Dec 23, 2018 |
| HP            | 158A                        | [949da584eb](https://linux-hardware.org/?probe=949da584eb) | Dec 22, 2018 |
| Gigabyte      | Z170-D3H-CF                 | [b0a40acf4d](https://linux-hardware.org/?probe=b0a40acf4d) | Dec 17, 2018 |
| ASRock        | X370 Professional Gaming    | [d23ffcd474](https://linux-hardware.org/?probe=d23ffcd474) | Dec 05, 2018 |
| HP            | 158A                        | [a7a42a3c72](https://linux-hardware.org/?probe=a7a42a3c72) | Nov 17, 2018 |
| HP            | 158A                        | [96e9dbac63](https://linux-hardware.org/?probe=96e9dbac63) | Nov 17, 2018 |
| ASRock        | AB350 Gaming-ITX/ac         | [06a35ac8f9](https://linux-hardware.org/?probe=06a35ac8f9) | Nov 11, 2018 |
| ASRock        | 880GMH/U3S3                 | [c152e28058](https://linux-hardware.org/?probe=c152e28058) | Nov 05, 2018 |
| ASRock        | X370 Professional Gaming    | [2d8ab831aa](https://linux-hardware.org/?probe=2d8ab831aa) | Nov 04, 2018 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [e30bc2b8f2](https://linux-hardware.org/?probe=e30bc2b8f2) | Nov 02, 2018 |
| Gigabyte      | 965P-DQ6                    | [781abca00d](https://linux-hardware.org/?probe=781abca00d) | Oct 29, 2018 |
| ASRock        | X99 Taichi                  | [789e336ae9](https://linux-hardware.org/?probe=789e336ae9) | Oct 28, 2018 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [bbffb3f1d1](https://linux-hardware.org/?probe=bbffb3f1d1) | Oct 27, 2018 |
| Gigabyte      | Z170X-UD3-CF                | [94ab793eab](https://linux-hardware.org/?probe=94ab793eab) | Oct 26, 2018 |
| Gigabyte      | Z68MX-UD2H-B3               | [50792df026](https://linux-hardware.org/?probe=50792df026) | Oct 26, 2018 |
| ASUSTek       | P6T                         | [5d6303185f](https://linux-hardware.org/?probe=5d6303185f) | Oct 26, 2018 |
| Dell          | 0K240Y A03                  | [ec23fbc3c8](https://linux-hardware.org/?probe=ec23fbc3c8) | Oct 26, 2018 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [041aa23640](https://linux-hardware.org/?probe=041aa23640) | Oct 26, 2018 |
| ASUSTek       | PRIME X370-PRO              | [5980381184](https://linux-hardware.org/?probe=5980381184) | Oct 26, 2018 |
| ASRock        | 970 Pro3                    | [a9bcc94c67](https://linux-hardware.org/?probe=a9bcc94c67) | Jul 31, 2018 |
| ASRock        | 970 Pro3                    | [51153d26f5](https://linux-hardware.org/?probe=51153d26f5) | Jul 31, 2018 |
| ASUSTek       | P5QPL-VM EPU                | [6c4195dd46](https://linux-hardware.org/?probe=6c4195dd46) | Jul 30, 2018 |
| Dell          | 0KWVT8 A02                  | [1f28e01ea6](https://linux-hardware.org/?probe=1f28e01ea6) | Jun 22, 2018 |
| Gigabyte      | B250M-DS3H-CF               | [a6e9875ca9](https://linux-hardware.org/?probe=a6e9875ca9) | Jun 22, 2018 |
| HP            | 09C4h                       | [0f22a261a8](https://linux-hardware.org/?probe=0f22a261a8) | Jan 11, 2016 |
| ASUSTek       | P5KPL-AM SE                 | [5128fdeca3](https://linux-hardware.org/?probe=5128fdeca3) | Dec 07, 2015 |
| ASUSTek       | M4A87TD/USB3                | [d12cf5e919](https://linux-hardware.org/?probe=d12cf5e919) | Dec 07, 2015 |
| Gigabyte      | Q87M-D2H                    | [85356dc9e2](https://linux-hardware.org/?probe=85356dc9e2) | Dec 03, 2015 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| openSUSE Leap-15.2           | 91       | 14.68%  |
| openSUSE Leap-15.1           | 56       | 9.03%   |
| openSUSE Leap-15.3           | 55       | 8.87%   |
| openSUSE Leap-15.0           | 24       | 3.87%   |
| openSUSE 20200405            | 11       | 1.77%   |
| openSUSE 20200407            | 8        | 1.29%   |
| openSUSE 20181022            | 7        | 1.13%   |
| openSUSE Tumbleweed-20211111 | 3        | 0.48%   |
| openSUSE Tumbleweed-20210810 | 3        | 0.48%   |
| openSUSE Tumbleweed-20201229 | 3        | 0.48%   |
| openSUSE 20220310            | 3        | 0.48%   |
| openSUSE 20210916            | 3        | 0.48%   |
| openSUSE 20210606            | 3        | 0.48%   |
| openSUSE 20200826            | 3        | 0.48%   |
| openSUSE 20200410            | 3        | 0.48%   |
| openSUSE 13.2                | 3        | 0.48%   |
| openSUSE Tumbleweed-20220324 | 2        | 0.32%   |
| openSUSE Tumbleweed-20211203 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210929 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210830 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210621 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210524 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210504 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210420 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210401 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210325 | 2        | 0.32%   |
| openSUSE Tumbleweed-20210208 | 2        | 0.32%   |
| openSUSE Tumbleweed-20201111 | 2        | 0.32%   |
| openSUSE Tumbleweed-20200128 | 2        | 0.32%   |
| openSUSE Tumbleweed-20200117 | 2        | 0.32%   |
| openSUSE 20220410            | 2        | 0.32%   |
| openSUSE 20220320            | 2        | 0.32%   |
| openSUSE 20220311            | 2        | 0.32%   |
| openSUSE 20211222            | 2        | 0.32%   |
| openSUSE 20211124            | 2        | 0.32%   |
| openSUSE 20211120            | 2        | 0.32%   |
| openSUSE 20211102            | 2        | 0.32%   |
| openSUSE 20210910            | 2        | 0.32%   |
| openSUSE 20210524            | 2        | 0.32%   |
| openSUSE 20210521            | 2        | 0.32%   |
| openSUSE 20210427            | 2        | 0.32%   |
| openSUSE 20210408            | 2        | 0.32%   |
| openSUSE 20210118            | 2        | 0.32%   |
| openSUSE 20210114            | 2        | 0.32%   |
| openSUSE 20201011            | 2        | 0.32%   |
| openSUSE 20200925            | 2        | 0.32%   |
| openSUSE 20200902            | 2        | 0.32%   |
| openSUSE 20200901            | 2        | 0.32%   |
| openSUSE 20200625            | 2        | 0.32%   |
| openSUSE 20200615            | 2        | 0.32%   |
| openSUSE 20200422            | 2        | 0.32%   |
| openSUSE 20200402            | 2        | 0.32%   |
| openSUSE 20200201            | 2        | 0.32%   |
| openSUSE 20191128            | 2        | 0.32%   |
| openSUSE 20180726            | 2        | 0.32%   |
| openSUSE Tumbleweed-20220413 | 1        | 0.16%   |
| openSUSE Tumbleweed-20220412 | 1        | 0.16%   |
| openSUSE Tumbleweed-20220404 | 1        | 0.16%   |
| openSUSE Tumbleweed-20220403 | 1        | 0.16%   |
| openSUSE Tumbleweed-20220331 | 1        | 0.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| openSUSE | 510      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 4.12.14-lp151.28.44-default | 18       | 2.79%   |
| 5.6.2-1-default             | 15       | 2.32%   |
| 5.6.0-1-default             | 13       | 2.01%   |
| 5.3.18-lp152.63-default     | 12       | 1.86%   |
| 5.3.18-59.37-default        | 12       | 1.86%   |
| 5.3.18-lp152.66-default     | 11       | 1.7%    |
| 5.16.11-1-default           | 11       | 1.7%    |
| 4.12.14-lp151.28.48-default | 11       | 1.7%    |
| 5.3.18-lp152.36-default     | 10       | 1.55%   |
| 5.11.6-1-default            | 10       | 1.55%   |
| 5.10.16-1-default           | 10       | 1.55%   |
| 5.3.18-lp152.41-default     | 9        | 1.39%   |
| 5.14.14-1-default           | 9        | 1.39%   |
| 4.12.14-lp150.11-default    | 9        | 1.39%   |
| 5.3.18-59.19-default        | 8        | 1.24%   |
| 4.18.15-1-default           | 8        | 1.24%   |
| 5.8.0-1-default             | 7        | 1.08%   |
| 5.17.1-1-default            | 7        | 1.08%   |
| 5.12.9-1-default            | 7        | 1.08%   |
| 5.10.7-1-default            | 7        | 1.08%   |
| 5.8.4-1-default             | 6        | 0.93%   |
| 5.8.10-1-default            | 6        | 0.93%   |
| 5.7.9-1-default             | 6        | 0.93%   |
| 5.6.12-1-default            | 6        | 0.93%   |
| 5.12.4-1-default            | 6        | 0.93%   |
| 4.12.14-lp150.12.82-default | 6        | 0.93%   |
| 5.6.4-1-default             | 5        | 0.77%   |
| 5.3.18-lp152.95-default     | 5        | 0.77%   |
| 5.3.18-lp152.57-default     | 5        | 0.77%   |
| 5.3.18-59.27-default        | 5        | 0.77%   |
| 5.16.0-1-default            | 5        | 0.77%   |
| 5.15.8-1-default            | 5        | 0.77%   |
| 5.13.8-1-default            | 5        | 0.77%   |
| 5.11.16-1-default           | 5        | 0.77%   |
| 5.10.1-1-default            | 5        | 0.77%   |
| 5.9.1-1-default             | 4        | 0.62%   |
| 5.8.14-1-default            | 4        | 0.62%   |
| 5.7.11-1-default            | 4        | 0.62%   |
| 5.7.1-1-default             | 4        | 0.62%   |
| 5.6.14-1-default            | 4        | 0.62%   |
| 5.4.10-1-default            | 4        | 0.62%   |
| 5.3.18-lp152.50-default     | 4        | 0.62%   |
| 5.3.18-lp152.33-default     | 4        | 0.62%   |
| 5.3.18-lp152.19-default     | 4        | 0.62%   |
| 5.3.18-59.5-default         | 4        | 0.62%   |
| 5.3.18-59.24-default        | 4        | 0.62%   |
| 5.3.18-150300.59.54-default | 4        | 0.62%   |
| 5.3.12-1-default            | 4        | 0.62%   |
| 5.16.15-1-default           | 4        | 0.62%   |
| 5.15.5-1-default            | 4        | 0.62%   |
| 5.14.6-1-default            | 4        | 0.62%   |
| 5.14.14-2-default           | 4        | 0.62%   |
| 5.14.1-1-default            | 4        | 0.62%   |
| 5.13.4-1-default            | 4        | 0.62%   |
| 5.12.13-1-default           | 4        | 0.62%   |
| 5.12.0-2-default            | 4        | 0.62%   |
| 5.10.4-1-default            | 4        | 0.62%   |
| 4.12.14-lp151.28.52-default | 4        | 0.62%   |
| 4.12.14-lp151.28.40-default | 4        | 0.62%   |
| 4.12.14-lp150.12.22-default | 4        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3.18  | 134      | 21.97%  |
| 4.12.14 | 72       | 11.8%   |
| 5.6.2   | 17       | 2.79%   |
| 5.6.0   | 14       | 2.3%    |
| 5.14.14 | 14       | 2.3%    |
| 5.16.11 | 11       | 1.8%    |
| 5.12.4  | 10       | 1.64%   |
| 5.11.6  | 10       | 1.64%   |
| 5.10.16 | 10       | 1.64%   |
| 5.3.12  | 8        | 1.31%   |
| 4.18.15 | 8        | 1.31%   |
| 5.9.1   | 7        | 1.15%   |
| 5.8.0   | 7        | 1.15%   |
| 5.7.9   | 7        | 1.15%   |
| 5.17.1  | 7        | 1.15%   |
| 5.12.9  | 7        | 1.15%   |
| 5.10.7  | 7        | 1.15%   |
| 5.8.4   | 6        | 0.98%   |
| 5.8.10  | 6        | 0.98%   |
| 5.6.12  | 6        | 0.98%   |
| 5.14.6  | 6        | 0.98%   |
| 5.12.0  | 6        | 0.98%   |
| 5.8.14  | 5        | 0.82%   |
| 5.6.4   | 5        | 0.82%   |
| 5.16.0  | 5        | 0.82%   |
| 5.15.8  | 5        | 0.82%   |
| 5.13.8  | 5        | 0.82%   |
| 5.11.16 | 5        | 0.82%   |
| 5.10.1  | 5        | 0.82%   |
| 5.7.11  | 4        | 0.66%   |
| 5.7.1   | 4        | 0.66%   |
| 5.6.14  | 4        | 0.66%   |
| 5.4.10  | 4        | 0.66%   |
| 5.16.15 | 4        | 0.66%   |
| 5.15.5  | 4        | 0.66%   |
| 5.15.3  | 4        | 0.66%   |
| 5.14.1  | 4        | 0.66%   |
| 5.13.4  | 4        | 0.66%   |
| 5.13.12 | 4        | 0.66%   |
| 5.12.13 | 4        | 0.66%   |
| 5.10.4  | 4        | 0.66%   |
| 5.9.8   | 3        | 0.49%   |
| 5.9.14  | 3        | 0.49%   |
| 5.9.12  | 3        | 0.49%   |
| 5.7.5   | 3        | 0.49%   |
| 5.5.7   | 3        | 0.49%   |
| 5.4.14  | 3        | 0.49%   |
| 5.2.11  | 3        | 0.49%   |
| 5.15.12 | 3        | 0.49%   |
| 5.14.2  | 3        | 0.49%   |
| 5.14.11 | 3        | 0.49%   |
| 5.13.1  | 3        | 0.49%   |
| 5.12.12 | 3        | 0.49%   |
| 5.11.2  | 3        | 0.49%   |
| 5.11.11 | 3        | 0.49%   |
| 5.10.12 | 3        | 0.49%   |
| 5.9.10  | 2        | 0.33%   |
| 5.8.7   | 2        | 0.33%   |
| 5.8.2   | 2        | 0.33%   |
| 5.7.7   | 2        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3     | 148      | 25.39%  |
| 4.12    | 72       | 12.35%  |
| 5.6     | 43       | 7.38%   |
| 5.12    | 33       | 5.66%   |
| 5.14    | 32       | 5.49%   |
| 5.8     | 30       | 5.15%   |
| 5.10    | 29       | 4.97%   |
| 5.16    | 27       | 4.63%   |
| 5.11    | 26       | 4.46%   |
| 5.13    | 22       | 3.77%   |
| 5.7     | 19       | 3.26%   |
| 5.15    | 18       | 3.09%   |
| 5.9     | 17       | 2.92%   |
| 5.5     | 11       | 1.89%   |
| 5.4     | 10       | 1.72%   |
| 5.17    | 9        | 1.54%   |
| 4.18    | 8        | 1.37%   |
| 5.2     | 7        | 1.2%    |
| 5.0     | 4        | 0.69%   |
| 4.20    | 4        | 0.69%   |
| 4.17    | 4        | 0.69%   |
| 4.19    | 3        | 0.51%   |
| 4.4     | 2        | 0.34%   |
| 4.3     | 2        | 0.34%   |
| 3.16    | 2        | 0.34%   |
| 5.1     | 1        | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 508      | 99.61%  |
| i686   | 2        | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KDE5          | 257      | 47.95%  |
| KDE           | 109      | 20.34%  |
| GNOME         | 65       | 12.13%  |
| Unknown       | 55       | 10.26%  |
| XFCE          | 22       | 4.1%    |
| MATE          | 8        | 1.49%   |
| X-Cinnamon    | 3        | 0.56%   |
| LXQt          | 3        | 0.56%   |
| KDE4          | 3        | 0.56%   |
| ICEWM         | 3        | 0.56%   |
| Cinnamon      | 3        | 0.56%   |
| Pantheon      | 1        | 0.19%   |
| LXDE          | 1        | 0.19%   |
| GNOME Classic | 1        | 0.19%   |
| Budgie        | 1        | 0.19%   |
| awesome       | 1        | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 444      | 84.41%  |
| Wayland     | 45       | 8.56%   |
| Tty         | 18       | 3.42%   |
| Unknown     | 17       | 3.23%   |
| Unspecified | 2        | 0.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 228      | 43.43%  |
| LightDM | 206      | 39.24%  |
| SDDM    | 71       | 13.52%  |
| XDM     | 18       | 3.43%   |
| GDM     | 2        | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_US          | 152      | 28.73%  |
| de_DE          | 72       | 13.61%  |
| Unknown        | 72       | 13.61%  |
| POSIX          | 46       | 8.7%    |
| en_GB          | 35       | 6.62%   |
| ru_RU          | 20       | 3.78%   |
| pt_BR          | 19       | 3.59%   |
| fr_FR          | 12       | 2.27%   |
| es_ES          | 12       | 2.27%   |
| pt_PT          | 11       | 2.08%   |
| pl_PL          | 10       | 1.89%   |
| nl_NL          | 8        | 1.51%   |
| it_IT          | 5        | 0.95%   |
| sv_SE          | 4        | 0.76%   |
| nl_BE          | 4        | 0.76%   |
| nb_NO          | 3        | 0.57%   |
| fi_FI          | 3        | 0.57%   |
| es_MX          | 3        | 0.57%   |
| es_AR          | 3        | 0.57%   |
| en_DE          | 3        | 0.57%   |
| zh_CN          | 2        | 0.38%   |
| nn_NO          | 2        | 0.38%   |
| en_CA          | 2        | 0.38%   |
| en_AU          | 2        | 0.38%   |
| C              | 2        | 0.38%   |
| wbp_AU         | 1        | 0.19%   |
| uk_UA          | 1        | 0.19%   |
| tr_TR          | 1        | 0.19%   |
| sl_SI          | 1        | 0.19%   |
| sk_SK          | 1        | 0.19%   |
| ru_UA          | 1        | 0.19%   |
| ro_RO          | 1        | 0.19%   |
| hu_HU          | 1        | 0.19%   |
| hr_HR          | 1        | 0.19%   |
| gsw_CH         | 1        | 0.19%   |
| fr_CH          | 1        | 0.19%   |
| fr_CA          | 1        | 0.19%   |
| en_US.US-ASCII | 1        | 0.19%   |
| en_NL          | 1        | 0.19%   |
| en_IE          | 1        | 0.19%   |
| en_GB.utf-8    | 1        | 0.19%   |
| en_FI          | 1        | 0.19%   |
| en_CH          | 1        | 0.19%   |
| de_DE@utf8     | 1        | 0.19%   |
| cv_RU          | 1        | 0.19%   |
| cs_CZ          | 1        | 0.19%   |
| ca_AD          | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 274      | 53.2%   |
| BIOS | 241      | 46.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 312      | 60%     |
| Ext4    | 144      | 27.69%  |
| Unknown | 30       | 5.77%   |
| Xfs     | 28       | 5.38%   |
| Overlay | 3        | 0.58%   |
| Tmpfs   | 2        | 0.38%   |
| Ext3    | 1        | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 259      | 49.43%  |
| Unknown | 206      | 39.31%  |
| MBR     | 59       | 11.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 445      | 85.41%  |
| Yes       | 76       | 14.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 370      | 70.88%  |
| Yes       | 152      | 29.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 128      | 25.1%   |
| Gigabyte Technology | 98       | 19.22%  |
| MSI                 | 69       | 13.53%  |
| ASRock              | 58       | 11.37%  |
| Hewlett-Packard     | 37       | 7.25%   |
| Dell                | 37       | 7.25%   |
| Lenovo              | 19       | 3.73%   |
| Intel               | 8        | 1.57%   |
| Fujitsu             | 8        | 1.57%   |
| Biostar             | 7        | 1.37%   |
| Pegatron            | 6        | 1.18%   |
| Foxconn             | 5        | 0.98%   |
| Acer                | 5        | 0.98%   |
| Supermicro          | 4        | 0.78%   |
| Medion              | 4        | 0.78%   |
| Shuttle             | 2        | 0.39%   |
| VS Company          | 1        | 0.2%    |
| SYWZ                | 1        | 0.2%    |
| Samsung Electronics | 1        | 0.2%    |
| Positivo            | 1        | 0.2%    |
| PCWare              | 1        | 0.2%    |
| Itautec             | 1        | 0.2%    |
| HARDKERNEL          | 1        | 0.2%    |
| Google              | 1        | 0.2%    |
| Fujitsu Siemens     | 1        | 0.2%    |
| DIEBOLD             | 1        | 0.2%    |
| Colorful Technology | 1        | 0.2%    |
| BESSTAR Tech        | 1        | 0.2%    |
| Apple               | 1        | 0.2%    |
| Alienware           | 1        | 0.2%    |
| Unknown             | 1        | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 16       | 3.14%   |
| Dell OptiPlex 9020           | 6        | 1.18%   |
| ASRock B450M Pro4            | 6        | 1.18%   |
| MSI MS-7C37                  | 5        | 0.98%   |
| MSI MS-7B89                  | 5        | 0.98%   |
| MSI MS-7B86                  | 5        | 0.98%   |
| Gigabyte 970A-DS3P           | 5        | 0.98%   |
| MSI MS-7A34                  | 4        | 0.78%   |
| Gigabyte B450M DS3H          | 4        | 0.78%   |
| ASUS TUF GAMING X570-PLUS    | 4        | 0.78%   |
| MSI MS-7C02                  | 3        | 0.59%   |
| MSI MS-7A33                  | 3        | 0.59%   |
| HP Z620 Workstation          | 3        | 0.59%   |
| HP ProLiant MicroServer      | 3        | 0.59%   |
| Gigabyte X570 AORUS MASTER   | 3        | 0.59%   |
| Gigabyte B450 AORUS M        | 3        | 0.59%   |
| Dell XPS 8700                | 3        | 0.59%   |
| ASUS PRIME A320M-K           | 3        | 0.59%   |
| Pegatron p2-1343w            | 2        | 0.39%   |
| MSI MS-7D09                  | 2        | 0.39%   |
| MSI MS-7C95                  | 2        | 0.39%   |
| MSI MS-7C94                  | 2        | 0.39%   |
| MSI MS-7C35                  | 2        | 0.39%   |
| MSI MS-7B79                  | 2        | 0.39%   |
| MSI MS-7673                  | 2        | 0.39%   |
| HP Z840 Workstation          | 2        | 0.39%   |
| Gigabyte X570 AORUS ELITE    | 2        | 0.39%   |
| Gigabyte X399 AORUS XTREME   | 2        | 0.39%   |
| Gigabyte MZGLKBP-00          | 2        | 0.39%   |
| Gigabyte GA-970A-D3          | 2        | 0.39%   |
| Gigabyte GA-770TA-UD3        | 2        | 0.39%   |
| Gigabyte B250M-DS3H          | 2        | 0.39%   |
| Gigabyte 970A-D3P            | 2        | 0.39%   |
| Dell Precision Tower 5810    | 2        | 0.39%   |
| Dell OptiPlex 990            | 2        | 0.39%   |
| Dell OptiPlex 7010           | 2        | 0.39%   |
| Dell Inspiron 660            | 2        | 0.39%   |
| ASUS TUF GAMING B550-PLUS    | 2        | 0.39%   |
| ASUS SABERTOOTH X79          | 2        | 0.39%   |
| ASUS ROG STRIX X570-E GAMING | 2        | 0.39%   |
| ASUS ROG STRIX X370-F GAMING | 2        | 0.39%   |
| ASUS PRIME X570-P            | 2        | 0.39%   |
| ASUS PRIME X370-PRO          | 2        | 0.39%   |
| ASUS PRIME B350M-A           | 2        | 0.39%   |
| ASUS Maximus VIII HERO       | 2        | 0.39%   |
| ASUS M5A99X EVO R2.0         | 2        | 0.39%   |
| ASUS M5A78L-M/USB3           | 2        | 0.39%   |
| ASUS M4A88TD-V EVO/USB3      | 2        | 0.39%   |
| ASUS CROSSHAIR VI HERO       | 2        | 0.39%   |
| ASUS CROSSHAIR V FORMULA-Z   | 2        | 0.39%   |
| ASUS A0000001                | 2        | 0.39%   |
| ASRock Z390 Taichi Ultimate  | 2        | 0.39%   |
| ASRock Z370 Gaming K6        | 2        | 0.39%   |
| ASRock X570M Pro4            | 2        | 0.39%   |
| ASRock X570 Steel Legend     | 2        | 0.39%   |
| ASRock B450M Pro4-F          | 2        | 0.39%   |
| ASRock AB350M Pro4           | 2        | 0.39%   |
| Acer Veriton M6620G          | 2        | 0.39%   |
| VS Company G31T-M            | 1        | 0.2%    |
| SYWZ S210H Series            | 1        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 22       | 4.31%   |
| Dell OptiPlex          | 19       | 3.73%   |
| ASUS All               | 16       | 3.14%   |
| ASUS ROG               | 14       | 2.75%   |
| Lenovo ThinkCentre     | 12       | 2.35%   |
| ASUS TUF               | 12       | 2.35%   |
| Gigabyte X570          | 8        | 1.57%   |
| ASRock B450M           | 8        | 1.57%   |
| Fujitsu ESPRIMO        | 6        | 1.18%   |
| Dell Inspiron          | 6        | 1.18%   |
| MSI MS-7C37            | 5        | 0.98%   |
| MSI MS-7B89            | 5        | 0.98%   |
| MSI MS-7B86            | 5        | 0.98%   |
| HP Compaq              | 5        | 0.98%   |
| Gigabyte B550          | 5        | 0.98%   |
| Gigabyte B450M         | 5        | 0.98%   |
| Gigabyte B450          | 5        | 0.98%   |
| Gigabyte 970A-DS3P     | 5        | 0.98%   |
| Dell XPS               | 5        | 0.98%   |
| Dell Precision         | 5        | 0.98%   |
| ASUS M5A78L-M          | 5        | 0.98%   |
| MSI MS-7A34            | 4        | 0.78%   |
| HP ProLiant            | 4        | 0.78%   |
| HP Pavilion            | 4        | 0.78%   |
| ASUS SABERTOOTH        | 4        | 0.78%   |
| ASUS CROSSHAIR         | 4        | 0.78%   |
| ASRock X570            | 4        | 0.78%   |
| MSI MS-7C02            | 3        | 0.59%   |
| MSI MS-7A33            | 3        | 0.59%   |
| HP Z620                | 3        | 0.59%   |
| HP EliteDesk           | 3        | 0.59%   |
| ASUS P8Z77-V           | 3        | 0.59%   |
| ASUS Maximus           | 3        | 0.59%   |
| ASRock Z370            | 3        | 0.59%   |
| Acer Aspire            | 3        | 0.59%   |
| Pegatron p2-1343w      | 2        | 0.39%   |
| MSI MS-7D09            | 2        | 0.39%   |
| MSI MS-7C95            | 2        | 0.39%   |
| MSI MS-7C94            | 2        | 0.39%   |
| MSI MS-7C35            | 2        | 0.39%   |
| MSI MS-7B79            | 2        | 0.39%   |
| MSI MS-7673            | 2        | 0.39%   |
| Lenovo ThinkStation    | 2        | 0.39%   |
| Lenovo IdeaCentre      | 2        | 0.39%   |
| HP Z840                | 2        | 0.39%   |
| Gigabyte Z390          | 2        | 0.39%   |
| Gigabyte Z170X-Gaming  | 2        | 0.39%   |
| Gigabyte X399          | 2        | 0.39%   |
| Gigabyte MZGLKBP-00    | 2        | 0.39%   |
| Gigabyte GA-970A-D3    | 2        | 0.39%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.39%   |
| Gigabyte GA-770TA-UD3  | 2        | 0.39%   |
| Gigabyte B250M-DS3H    | 2        | 0.39%   |
| Gigabyte AX370-Gaming  | 2        | 0.39%   |
| Gigabyte 970A-D3P      | 2        | 0.39%   |
| Fujitsu CELSIUS        | 2        | 0.39%   |
| ASUS P9X79             | 2        | 0.39%   |
| ASUS P8H61-M           | 2        | 0.39%   |
| ASUS P6T               | 2        | 0.39%   |
| ASUS M5A99X            | 2        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 64       | 12.55%  |
| 2019 | 62       | 12.16%  |
| 2013 | 47       | 9.22%   |
| 2012 | 47       | 9.22%   |
| 2017 | 43       | 8.43%   |
| 2020 | 41       | 8.04%   |
| 2011 | 36       | 7.06%   |
| 2014 | 33       | 6.47%   |
| 2010 | 32       | 6.27%   |
| 2015 | 25       | 4.9%    |
| 2016 | 24       | 4.71%   |
| 2009 | 20       | 3.92%   |
| 2021 | 13       | 2.55%   |
| 2008 | 9        | 1.76%   |
| 2007 | 7        | 1.37%   |
| 2006 | 4        | 0.78%   |
| 2004 | 2        | 0.39%   |
| 2005 | 1        | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 510      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 490      | 95.52%  |
| Enabled  | 23       | 4.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 509      | 99.8%   |
| Yes  | 1        | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 175      | 33.85%  |
| 8.01-16.0   | 98       | 18.96%  |
| 32.01-64.0  | 96       | 18.57%  |
| 4.01-8.0    | 57       | 11.03%  |
| 3.01-4.0    | 34       | 6.58%   |
| 64.01-256.0 | 29       | 5.61%   |
| 24.01-32.0  | 14       | 2.71%   |
| Unknown     | 9        | 1.74%   |
| 1.01-2.0    | 3        | 0.58%   |
| 2.01-3.0    | 2        | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 144      | 25.26%  |
| 2.01-3.0   | 134      | 23.51%  |
| 1.01-2.0   | 116      | 20.35%  |
| 3.01-4.0   | 87       | 15.26%  |
| 8.01-16.0  | 39       | 6.84%   |
| 0.51-1.0   | 23       | 4.04%   |
| 16.01-24.0 | 10       | 1.75%   |
| Unknown    | 9        | 1.58%   |
| 24.01-32.0 | 3        | 0.53%   |
| 0.01-0.5   | 3        | 0.53%   |
| 32.01-64.0 | 2        | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 149      | 27.85%  |
| 1      | 118      | 22.06%  |
| 3      | 116      | 21.68%  |
| 4      | 75       | 14.02%  |
| 5      | 37       | 6.92%   |
| 6      | 24       | 4.49%   |
| 7      | 11       | 2.06%   |
| 13     | 2        | 0.37%   |
| 10     | 1        | 0.19%   |
| 8      | 1        | 0.19%   |
| 0      | 1        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 266      | 51.75%  |
| No        | 248      | 48.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 507      | 99.41%  |
| No        | 3        | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 313      | 60.78%  |
| Yes       | 202      | 39.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 333      | 64.16%  |
| Yes       | 186      | 35.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Germany            | 105      | 20.43%  |
| USA                | 101      | 19.65%  |
| Brazil             | 29       | 5.64%   |
| Russia             | 28       | 5.45%   |
| Switzerland        | 18       | 3.5%    |
| UK                 | 17       | 3.31%   |
| Netherlands        | 16       | 3.11%   |
| France             | 16       | 3.11%   |
| Spain              | 13       | 2.53%   |
| Sweden             | 11       | 2.14%   |
| Poland             | 10       | 1.95%   |
| Canada             | 10       | 1.95%   |
| Belgium            | 10       | 1.95%   |
| Australia          | 10       | 1.95%   |
| Mexico             | 9        | 1.75%   |
| Italy              | 9        | 1.75%   |
| Portugal           | 6        | 1.17%   |
| Finland            | 6        | 1.17%   |
| Ukraine            | 5        | 0.97%   |
| Norway             | 5        | 0.97%   |
| Serbia             | 4        | 0.78%   |
| Peru               | 4        | 0.78%   |
| India              | 4        | 0.78%   |
| Austria            | 4        | 0.78%   |
| Turkey             | 3        | 0.58%   |
| Romania            | 3        | 0.58%   |
| Japan              | 3        | 0.58%   |
| Israel             | 3        | 0.58%   |
| Hungary            | 3        | 0.58%   |
| Czechia            | 3        | 0.58%   |
| Croatia            | 3        | 0.58%   |
| Bulgaria           | 3        | 0.58%   |
| Argentina          | 3        | 0.58%   |
| Vietnam            | 2        | 0.39%   |
| Thailand           | 2        | 0.39%   |
| Taiwan             | 2        | 0.39%   |
| South Korea        | 2        | 0.39%   |
| Slovakia           | 2        | 0.39%   |
| New Zealand        | 2        | 0.39%   |
| Luxembourg         | 2        | 0.39%   |
| Lithuania          | 2        | 0.39%   |
| Indonesia          | 2        | 0.39%   |
| Greece             | 2        | 0.39%   |
| Colombia           | 2        | 0.39%   |
| China              | 2        | 0.39%   |
| Belarus            | 2        | 0.39%   |
| Slovenia           | 1        | 0.19%   |
| Malaysia           | 1        | 0.19%   |
| Lebanon            | 1        | 0.19%   |
| Kazakhstan         | 1        | 0.19%   |
| Ireland            | 1        | 0.19%   |
| Iceland            | 1        | 0.19%   |
| Guadeloupe         | 1        | 0.19%   |
| El Salvador        | 1        | 0.19%   |
| Dominican Republic | 1        | 0.19%   |
| Cyprus             | 1        | 0.19%   |
| Andorra            | 1        | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Denver                    | 10       | 1.8%    |
| Berlin                    | 7        | 1.26%   |
| Rio de Janeiro            | 6        | 1.08%   |
| Moscow                    | 6        | 1.08%   |
| Frankfurt am Main         | 6        | 1.08%   |
| Zurich                    | 5        | 0.9%    |
| Neuchatel                 | 5        | 0.9%    |
| Kiel                      | 5        | 0.9%    |
| Sydney                    | 4        | 0.72%   |
| Los Angeles               | 4        | 0.72%   |
| Lisbon                    | 4        | 0.72%   |
| Amsterdam                 | 4        | 0.72%   |
| Zagreb                    | 3        | 0.54%   |
| Tokyo                     | 3        | 0.54%   |
| San Jose                  | 3        | 0.54%   |
| Paris                     | 3        | 0.54%   |
| Oberursel                 | 3        | 0.54%   |
| Nice                      | 3        | 0.54%   |
| Munich                    | 3        | 0.54%   |
| Miami                     | 3        | 0.54%   |
| Madrid                    | 3        | 0.54%   |
| Lima                      | 3        | 0.54%   |
| Knetzgau                  | 3        | 0.54%   |
| Joplin                    | 3        | 0.54%   |
| Hamburg                   | 3        | 0.54%   |
| Chicago                   | 3        | 0.54%   |
| Buchholz in der Nordheide | 3        | 0.54%   |
| Belgrade                  | 3        | 0.54%   |
| Xi'an                     | 2        | 0.36%   |
| Wilrijk                   | 2        | 0.36%   |
| Warsaw                    | 2        | 0.36%   |
| Vilnius                   | 2        | 0.36%   |
| Vienna                    | 2        | 0.36%   |
| Ufa                       | 2        | 0.36%   |
| Tomsk                     | 2        | 0.36%   |
| Tettnang Castle           | 2        | 0.36%   |
| Tel Aviv                  | 2        | 0.36%   |
| Stuttgart                 | 2        | 0.36%   |
| Stabroek                  | 2        | 0.36%   |
| St Petersburg             | 2        | 0.36%   |
| Sofia                     | 2        | 0.36%   |
| Schlangenbad              | 2        | 0.36%   |
| Sao Paulo                 | 2        | 0.36%   |
| Rotterdam                 | 2        | 0.36%   |
| Prague                    | 2        | 0.36%   |
| Porto                     | 2        | 0.36%   |
| Phoenix                   | 2        | 0.36%   |
| Perkasie                  | 2        | 0.36%   |
| Oulu                      | 2        | 0.36%   |
| Nottingham                | 2        | 0.36%   |
| Nordenham                 | 2        | 0.36%   |
| Montreal                  | 2        | 0.36%   |
| Mexico City               | 2        | 0.36%   |
| Melbourne                 | 2        | 0.36%   |
| Magdeburg                 | 2        | 0.36%   |
| Kempten (Allgaeu)         | 2        | 0.36%   |
| Kazanâ€™             | 2        | 0.36%   |
| Haarlem                   | 2        | 0.36%   |
| Gothenburg                | 2        | 0.36%   |
| Espoo                     | 2        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 228      | 422    | 20.49%  |
| WDC                       | 212      | 417    | 19.05%  |
| Samsung Electronics       | 196      | 383    | 17.61%  |
| Toshiba                   | 68       | 96     | 6.11%   |
| Kingston                  | 55       | 83     | 4.94%   |
| Crucial                   | 51       | 69     | 4.58%   |
| SanDisk                   | 42       | 56     | 3.77%   |
| Hitachi                   | 28       | 35     | 2.52%   |
| Intel                     | 21       | 26     | 1.89%   |
| A-DATA Technology         | 20       | 26     | 1.8%    |
| Phison                    | 17       | 25     | 1.53%   |
| PNY                       | 13       | 19     | 1.17%   |
| Unknown                   | 12       | 20     | 1.08%   |
| SPCC                      | 11       | 16     | 0.99%   |
| Corsair                   | 10       | 10     | 0.9%    |
| HGST                      | 9        | 17     | 0.81%   |
| Micron Technology         | 8        | 12     | 0.72%   |
| SK Hynix                  | 7        | 15     | 0.63%   |
| OCZ                       | 7        | 12     | 0.63%   |
| Intenso                   | 5        | 8      | 0.45%   |
| Hewlett-Packard           | 5        | 5      | 0.45%   |
| Transcend                 | 4        | 4      | 0.36%   |
| Silicon Motion            | 4        | 4      | 0.36%   |
| MAXTOR                    | 4        | 4      | 0.36%   |
| KingSpec                  | 4        | 9      | 0.36%   |
| JMicron                   | 4        | 4      | 0.36%   |
| Fujitsu                   | 4        | 5      | 0.36%   |
| XPG                       | 3        | 3      | 0.27%   |
| Mushkin                   | 3        | 6      | 0.27%   |
| Micron/Crucial Technology | 3        | 4      | 0.27%   |
| KIOXIA                    | 3        | 3      | 0.27%   |
| China                     | 3        | 3      | 0.27%   |
| Biostar                   | 3        | 5      | 0.27%   |
| TO Exter                  | 2        | 2      | 0.18%   |
| Team                      | 2        | 2      | 0.18%   |
| SMART                     | 2        | 2      | 0.18%   |
| SABRENT                   | 2        | 2      | 0.18%   |
| PLEXTOR                   | 2        | 2      | 0.18%   |
| Phison Electronics        | 2        | 2      | 0.18%   |
| Patriot                   | 2        | 2      | 0.18%   |
| LITEONIT                  | 2        | 2      | 0.18%   |
| GOODRAM                   | 2        | 2      | 0.18%   |
| Gigabyte Technology       | 2        | 6      | 0.18%   |
| GALAX                     | 2        | 2      | 0.18%   |
| Apple                     | 2        | 2      | 0.18%   |
| WD MediaMax               | 1        | 1      | 0.09%   |
| Vaseky                    | 1        | 1      | 0.09%   |
| USB3.0                    | 1        | 1      | 0.09%   |
| USB                       | 1        | 1      | 0.09%   |
| T-CREATE                  | 1        | 1      | 0.09%   |
| SuperTalent               | 1        | 1      | 0.09%   |
| Smartbuy                  | 1        | 1      | 0.09%   |
| Ramsta                    | 1        | 1      | 0.09%   |
| PALIT                     | 1        | 1      | 0.09%   |
| Lite-On                   | 1        | 1      | 0.09%   |
| Lexar                     | 1        | 1      | 0.09%   |
| KingFast                  | 1        | 1      | 0.09%   |
| Inateck                   | 1        | 1      | 0.09%   |
| imation                   | 1        | 1      | 0.09%   |
| HGST HTS                  | 1        | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 20       | 1.48%   |
| Samsung SSD 850 EVO 250GB        | 17       | 1.26%   |
| Seagate ST2000DM008-2FR102 2TB   | 15       | 1.11%   |
| Samsung SSD 860 EVO 1TB          | 14       | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB   | 12       | 0.89%   |
| Seagate ST1000DM003-1CH162 1TB   | 12       | 0.89%   |
| Samsung SSD 850 EVO 500GB        | 12       | 0.89%   |
| Seagate ST3500418AS 500GB        | 11       | 0.81%   |
| Toshiba DT01ACA200 2TB           | 10       | 0.74%   |
| Toshiba DT01ACA100 1TB           | 10       | 0.74%   |
| Samsung SSD 970 EVO Plus 500GB   | 10       | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB         | 9        | 0.67%   |
| Seagate ST2000DM001-1ER164 2TB   | 9        | 0.67%   |
| Samsung SSD 970 EVO 500GB        | 9        | 0.67%   |
| Samsung SSD 860 EVO 250GB        | 9        | 0.67%   |
| Samsung SSD 840 EVO 250GB        | 9        | 0.67%   |
| Kingston SA400S37240G 240GB SSD  | 9        | 0.67%   |
| Seagate ST3000DM008-2DM166 3TB   | 8        | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB   | 8        | 0.59%   |
| Samsung SSD 860 QVO 1TB          | 8        | 0.59%   |
| Crucial CT500MX500SSD1 500GB     | 8        | 0.59%   |
| WDC WD20EFRX-68EUZN0 2TB         | 7        | 0.52%   |
| WDC WD10EZEX-00BN5A0 1TB         | 7        | 0.52%   |
| Unknown SD/MMC/MS PRO 394GB      | 7        | 0.52%   |
| Toshiba HDWD110 1TB              | 7        | 0.52%   |
| Seagate ST500DM002-1BD142 500GB  | 7        | 0.52%   |
| Seagate ST3000DM001-1CH166 3TB   | 7        | 0.52%   |
| Seagate ST2000DX002-2DV164 2TB   | 7        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB   | 7        | 0.52%   |
| Seagate Expansion Desk 6TB       | 7        | 0.52%   |
| Samsung SSD 850 PRO 256GB        | 7        | 0.52%   |
| Kingston SA400S37120G 120GB SSD  | 7        | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 6        | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 6        | 0.44%   |
| Seagate Expansion 1TB            | 6        | 0.44%   |
| SanDisk SDSSDA240G 240GB         | 6        | 0.44%   |
| Sandisk NVMe SSD Drive 1TB       | 6        | 0.44%   |
| Samsung NVMe SSD Drive 1TB       | 6        | 0.44%   |
| Samsung HD501LJ 500GB            | 6        | 0.44%   |
| Crucial CT240BX500SSD1 240GB     | 6        | 0.44%   |
| WDC WD1003FZEX-00K3CA0 1TB       | 5        | 0.37%   |
| Seagate ST4000DM005-2DP166 4TB   | 5        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB   | 5        | 0.37%   |
| Seagate ST2000DM001-1CH164 2TB   | 5        | 0.37%   |
| Seagate ST1000DM003-1SB102 1TB   | 5        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB     | 5        | 0.37%   |
| Samsung SSD 970 EVO 1TB          | 5        | 0.37%   |
| Samsung NVMe SSD Drive 500GB     | 5        | 0.37%   |
| Phison NVMe SSD Drive 240GB      | 5        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD | 5        | 0.37%   |
| Kingston SUV400S37240G 240GB SSD | 5        | 0.37%   |
| WDC WD20EARS-00MVWB0 2TB         | 4        | 0.3%    |
| WDC WD10EZEX-22MFCA0 1TB         | 4        | 0.3%    |
| WDC WD10EARS-00Y5B1 1TB          | 4        | 0.3%    |
| WDC WD1003FZEX-00MK2A0 1TB       | 4        | 0.3%    |
| WDC WD1002FAEX-00Z3A0 1TB        | 4        | 0.3%    |
| Seagate ST3320620AS 320GB        | 4        | 0.3%    |
| Seagate ST2000DM001-9YN164 2TB   | 4        | 0.3%    |
| Seagate ST1000DX001-1CM162 1TB   | 4        | 0.3%    |
| Samsung SSD 860 QVO 2TB          | 4        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 226      | 412    | 39.51%  |
| WDC                 | 184      | 353    | 32.17%  |
| Toshiba             | 56       | 80     | 9.79%   |
| Samsung Electronics | 38       | 60     | 6.64%   |
| Hitachi             | 28       | 35     | 4.9%    |
| HGST                | 9        | 17     | 1.57%   |
| Unknown             | 8        | 9      | 1.4%    |
| MAXTOR              | 4        | 4      | 0.7%    |
| Hewlett-Packard     | 4        | 4      | 0.7%    |
| Fujitsu             | 4        | 5      | 0.7%    |
| SABRENT             | 2        | 2      | 0.35%   |
| JMicron             | 2        | 2      | 0.35%   |
| Intenso             | 2        | 5      | 0.35%   |
| WD MediaMax         | 1        | 1      | 0.17%   |
| USB3.0              | 1        | 1      | 0.17%   |
| USB                 | 1        | 1      | 0.17%   |
| Inateck             | 1        | 1      | 0.17%   |
| ASMT                | 1        | 2      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 119      | 224    | 29.75%  |
| Kingston            | 47       | 72     | 11.75%  |
| Crucial             | 45       | 61     | 11.25%  |
| SanDisk             | 33       | 44     | 8.25%   |
| WDC                 | 32       | 41     | 8%      |
| A-DATA Technology   | 16       | 21     | 4%      |
| PNY                 | 10       | 13     | 2.5%    |
| SPCC                | 9        | 14     | 2.25%   |
| Intel               | 9        | 10     | 2.25%   |
| Toshiba             | 8        | 9      | 2%      |
| Micron Technology   | 8        | 12     | 2%      |
| OCZ                 | 7        | 12     | 1.75%   |
| Corsair             | 6        | 6      | 1.5%    |
| KingSpec            | 4        | 9      | 1%      |
| Transcend           | 3        | 3      | 0.75%   |
| China               | 3        | 3      | 0.75%   |
| Biostar             | 3        | 5      | 0.75%   |
| TO Exter            | 2        | 2      | 0.5%    |
| Team                | 2        | 2      | 0.5%    |
| SMART               | 2        | 2      | 0.5%    |
| SK Hynix            | 2        | 6      | 0.5%    |
| Seagate             | 2        | 2      | 0.5%    |
| Patriot             | 2        | 2      | 0.5%    |
| Mushkin             | 2        | 4      | 0.5%    |
| LITEONIT            | 2        | 2      | 0.5%    |
| Intenso             | 2        | 2      | 0.5%    |
| GOODRAM             | 2        | 2      | 0.5%    |
| GALAX               | 2        | 2      | 0.5%    |
| Apple               | 2        | 2      | 0.5%    |
| Vaseky              | 1        | 1      | 0.25%   |
| SuperTalent         | 1        | 1      | 0.25%   |
| Smartbuy            | 1        | 1      | 0.25%   |
| Ramsta              | 1        | 1      | 0.25%   |
| PLEXTOR             | 1        | 1      | 0.25%   |
| PALIT               | 1        | 1      | 0.25%   |
| KingFast            | 1        | 1      | 0.25%   |
| JMicron             | 1        | 1      | 0.25%   |
| imation             | 1        | 1      | 0.25%   |
| Goldkey             | 1        | 1      | 0.25%   |
| Gigabyte Technology | 1        | 3      | 0.25%   |
| Emtec               | 1        | 1      | 0.25%   |
| Colorful            | 1        | 1      | 0.25%   |
| Apacer              | 1        | 3      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 413      | 994    | 46.25%  |
| SSD     | 314      | 607    | 35.16%  |
| NVMe    | 155      | 258    | 17.36%  |
| Unknown | 10       | 19     | 1.12%   |
| MMC     | 1        | 1      | 0.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 480      | 1532   | 69.87%  |
| NVMe | 155      | 258    | 22.56%  |
| SAS  | 51       | 88     | 7.42%   |
| MMC  | 1        | 1      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 365      | 740    | 43.3%   |
| 0.51-1.0   | 239      | 442    | 28.35%  |
| 1.01-2.0   | 120      | 216    | 14.23%  |
| 2.01-3.0   | 47       | 67     | 5.58%   |
| 3.01-4.0   | 37       | 66     | 4.39%   |
| 4.01-10.0  | 31       | 63     | 3.68%   |
| 10.01-20.0 | 4        | 7      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 191      | 35.37%  |
| 1001-2000      | 114      | 21.11%  |
| 2001-3000      | 72       | 13.33%  |
| 501-1000       | 66       | 12.22%  |
| 251-500        | 41       | 7.59%   |
| 101-250        | 23       | 4.26%   |
| Unknown        | 19       | 3.52%   |
| 51-100         | 6        | 1.11%   |
| 1-20           | 5        | 0.93%   |
| 21-50          | 3        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 101      | 18%     |
| 251-500        | 95       | 16.93%  |
| 501-1000       | 90       | 16.04%  |
| 101-250        | 73       | 13.01%  |
| More than 3000 | 57       | 10.16%  |
| 51-100         | 47       | 8.38%   |
| 2001-3000      | 36       | 6.42%   |
| 1-20           | 27       | 4.81%   |
| Unknown        | 19       | 3.39%   |
| 21-50          | 16       | 2.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB             | 4        | 6      | 3.92%   |
| Seagate ST500DM002-1BD142 500GB       | 3        | 5      | 2.94%   |
| Samsung Electronics HD501LJ 500GB     | 3        | 4      | 2.94%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2        | 5      | 1.96%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 2      | 1.96%   |
| Seagate ST2000DM001-1CH164 2TB        | 2        | 2      | 1.96%   |
| Samsung Electronics HD322HJ 320GB     | 2        | 2      | 1.96%   |
| Samsung Electronics HD103SJ 1TB       | 2        | 3      | 1.96%   |
| WDC WD800AAJS-75M0A0 80GB             | 1        | 1      | 0.98%   |
| WDC WD7500AAKS-00RBA0 752GB           | 1        | 1      | 0.98%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1        | 1      | 0.98%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1        | 1      | 0.98%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1        | 1      | 0.98%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1        | 1      | 0.98%   |
| WDC WD5000AAKX-221CA1 500GB           | 1        | 1      | 0.98%   |
| WDC WD5000AAKS-65A7B0 500GB           | 1        | 1      | 0.98%   |
| WDC WD3200AVJS-63B6A0 320GB           | 1        | 1      | 0.98%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 1        | 1      | 0.98%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 0.98%   |
| WDC WD30EZRZ-00Z5HB0 3TB              | 1        | 1      | 0.98%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 1      | 0.98%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1        | 1      | 0.98%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 1      | 0.98%   |
| WDC WD20EARS-07MVWB0 2TB              | 1        | 1      | 0.98%   |
| WDC WD10JFCX-68N6GN0 1TB              | 1        | 2      | 0.98%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 0.98%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1      | 0.98%   |
| WDC WD10EADS-65M2B1 1TB               | 1        | 1      | 0.98%   |
| WDC WD1003FZEX-00K3CA0 1TB            | 1        | 1      | 0.98%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1        | 1      | 0.98%   |
| Toshiba MQ01ABF050 500GB              | 1        | 1      | 0.98%   |
| Toshiba MK7575GSX 752GB               | 1        | 2      | 0.98%   |
| Toshiba HDWD110 1TB                   | 1        | 1      | 0.98%   |
| Toshiba DT01ACA200 2TB                | 1        | 7      | 0.98%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 0.98%   |
| Toshiba DT01ABA300 3TB                | 1        | 1      | 0.98%   |
| SuperTalent SSD FTM32GX25H 32GB       | 1        | 1      | 0.98%   |
| Seagate ST9500325AS 500GB             | 1        | 1      | 0.98%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1        | 1      | 0.98%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1      | 0.98%   |
| Seagate ST380811AS 80GB               | 1        | 1      | 0.98%   |
| Seagate ST3500820AS 500GB             | 1        | 1      | 0.98%   |
| Seagate ST3500320AS 500GB             | 1        | 1      | 0.98%   |
| Seagate ST3500312CS 500GB             | 1        | 1      | 0.98%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 0.98%   |
| Seagate ST3320613AS 320GB             | 1        | 1      | 0.98%   |
| Seagate ST3250820AS 250GB             | 1        | 1      | 0.98%   |
| Seagate ST3250318AS 250GB             | 1        | 1      | 0.98%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 0.98%   |
| Seagate ST3160812AS 160GB             | 1        | 1      | 0.98%   |
| Seagate ST31000528AS 1TB              | 1        | 1      | 0.98%   |
| Seagate ST3000DM001-9YN166 3TB        | 1        | 1      | 0.98%   |
| Seagate ST3000DM001-1CH166 3TB        | 1        | 1      | 0.98%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 0.98%   |
| Seagate ST2000DM006-2DM164 2TB        | 1        | 1      | 0.98%   |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 1      | 0.98%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 0.98%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 0.98%   |
| Samsung Electronics SV0412H 40GB      | 1        | 1      | 0.98%   |
| Samsung Electronics SSD 860 EVO 250GB | 1        | 1      | 0.98%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 36     | 31.31%  |
| WDC                 | 23       | 28     | 23.23%  |
| Samsung Electronics | 15       | 19     | 15.15%  |
| Toshiba             | 6        | 13     | 6.06%   |
| Kingston            | 4        | 7      | 4.04%   |
| Hitachi             | 4        | 5      | 4.04%   |
| Crucial             | 4        | 4      | 4.04%   |
| MAXTOR              | 3        | 3      | 3.03%   |
| OCZ                 | 2        | 2      | 2.02%   |
| SuperTalent         | 1        | 1      | 1.01%   |
| Patriot             | 1        | 1      | 1.01%   |
| Micron Technology   | 1        | 1      | 1.01%   |
| KingFast            | 1        | 1      | 1.01%   |
| HGST                | 1        | 1      | 1.01%   |
| Hewlett-Packard     | 1        | 1      | 1.01%   |
| Corsair             | 1        | 1      | 1.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 31       | 36     | 38.27%  |
| WDC                 | 23       | 28     | 28.4%   |
| Samsung Electronics | 12       | 16     | 14.81%  |
| Toshiba             | 6        | 13     | 7.41%   |
| Hitachi             | 4        | 5      | 4.94%   |
| MAXTOR              | 3        | 3      | 3.7%    |
| HGST                | 1        | 1      | 1.23%   |
| Hewlett-Packard     | 1        | 1      | 1.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 68       | 103    | 80%     |
| SSD  | 14       | 18     | 16.47%  |
| NVMe | 3        | 3      | 3.53%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD20EADS-00R6B0 2TB           | 1        | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1        | 3      | 33.33%  |
| Hitachi HDS721025CLA382 250GB     | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 3      | 33.33%  |
| Hitachi             | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 312      | 952    | 50.65%  |
| Detected | 218      | 798    | 35.39%  |
| Malfunc  | 83       | 124    | 13.47%  |
| Failed   | 3        | 5      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 274      | 34.55%  |
| AMD                          | 232      | 29.26%  |
| Samsung Electronics          | 66       | 8.32%   |
| ASMedia Technology           | 43       | 5.42%   |
| Phison Electronics           | 28       | 3.53%   |
| Sandisk                      | 25       | 3.15%   |
| Marvell Technology Group     | 22       | 2.77%   |
| JMicron Technology           | 18       | 2.27%   |
| Nvidia                       | 10       | 1.26%   |
| Micron/Crucial Technology    | 10       | 1.26%   |
| Kingston Technology Company  | 10       | 1.26%   |
| Silicon Motion               | 7        | 0.88%   |
| SK Hynix                     | 6        | 0.76%   |
| Toshiba America Info Systems | 5        | 0.63%   |
| Silicon Image                | 5        | 0.63%   |
| ADATA Technology             | 4        | 0.5%    |
| Adaptec                      | 4        | 0.5%    |
| VIA Technologies             | 3        | 0.38%   |
| LSI Logic / Symbios Logic    | 3        | 0.38%   |
| Broadcom / LSI               | 3        | 0.38%   |
| Seagate Technology           | 2        | 0.25%   |
| Realtek Semiconductor        | 2        | 0.25%   |
| Promise Technology           | 2        | 0.25%   |
| Lite-On Technology           | 2        | 0.25%   |
| KIOXIA                       | 2        | 0.25%   |
| Tekram Technology            | 1        | 0.13%   |
| Shenzhen Longsys Electronics | 1        | 0.13%   |
| Biwin Storage Technology     | 1        | 0.13%   |
| ATTO Technology              | 1        | 0.13%   |
| 3ware                        | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 144      | 14.47%  |
| AMD 400 Series Chipset SATA Controller                                                  | 49       | 4.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 43       | 4.32%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 40       | 4.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 37       | 3.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 37       | 3.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 35       | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 31       | 3.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28       | 2.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21       | 2.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 21       | 2.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 21       | 2.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 1.91%   |
| Phison E12 NVMe Controller                                                              | 17       | 1.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14       | 1.41%   |
| AMD X370 Series Chipset SATA Controller                                                 | 14       | 1.41%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 10       | 1.01%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 10       | 1.01%   |
| AMD FCH SATA Controller D                                                               | 10       | 1.01%   |
| Kingston Company A2000 NVMe SSD                                                         | 9        | 0.9%    |
| Intel SSD 660P Series                                                                   | 9        | 0.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 9        | 0.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8        | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 8        | 0.8%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 7        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 0.7%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 6        | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6        | 0.6%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 0.6%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 6        | 0.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 0.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.6%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 0.6%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 5        | 0.5%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 5        | 0.5%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 0.5%    |
| Nvidia MCP61 SATA Controller                                                            | 5        | 0.5%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 5        | 0.5%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 5        | 0.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.5%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 4        | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 0.4%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 4        | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.4%    |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 4        | 0.4%    |
| JMicron JMB368 IDE controller                                                           | 4        | 0.4%    |
| Intel SSD 600P Series                                                                   | 4        | 0.4%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 0.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.4%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.4%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 0.4%    |
| SK Hynix Gold P31 SSD                                                                   | 3        | 0.3%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.3%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3        | 0.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 456      | 59.69%  |
| NVMe | 158      | 20.68%  |
| IDE  | 102      | 13.35%  |
| RAID | 32       | 4.19%   |
| SAS  | 8        | 1.05%   |
| SCSI | 8        | 1.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 268      | 52.55%  |
| AMD    | 242      | 47.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 15       | 2.93%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 12       | 2.34%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 2.15%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 10       | 1.95%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 10       | 1.95%   |
| AMD FX-8350 Eight-Core Processor            | 10       | 1.95%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 8        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 1.37%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 7        | 1.37%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 7        | 1.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1.17%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 6        | 1.17%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 6        | 1.17%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 6        | 1.17%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 1.17%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 6        | 1.17%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 0.98%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5        | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 0.98%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 5        | 0.98%   |
| AMD Ryzen 7 1800X Eight-Core Processor      | 5        | 0.98%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 0.98%   |
| AMD FX-8320 Eight-Core Processor            | 5        | 0.98%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 0.78%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 4        | 0.78%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 4        | 0.78%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 4        | 0.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.78%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 4        | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.78%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.78%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.78%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 4        | 0.78%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.78%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.78%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 4        | 0.78%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 4        | 0.78%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 0.78%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.78%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 4        | 0.78%   |
| AMD Phenom II X4 955 Processor              | 4        | 0.78%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.78%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 3        | 0.59%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 3        | 0.59%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 0.59%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 3        | 0.59%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 3        | 0.59%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3        | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.59%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 0.59%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 3        | 0.59%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3        | 0.59%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.59%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 0.59%   |
| AMD Athlon 5350 APU with Radeon R3          | 3        | 0.59%   |
| Intel Xeon W-1250 CPU @ 3.30GHz             | 2        | 0.39%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 2        | 0.39%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz         | 2        | 0.39%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 2        | 0.39%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 82       | 16.05%  |
| Intel Core i7           | 76       | 14.87%  |
| AMD Ryzen 5             | 63       | 12.33%  |
| AMD Ryzen 7             | 46       | 9%      |
| Intel Xeon              | 32       | 6.26%   |
| AMD FX                  | 31       | 6.07%   |
| AMD Ryzen 9             | 26       | 5.09%   |
| Intel Core i3           | 21       | 4.11%   |
| AMD Phenom II X4        | 13       | 2.54%   |
| Intel Pentium           | 10       | 1.96%   |
| Intel Core 2 Duo        | 10       | 1.96%   |
| AMD Ryzen 3             | 10       | 1.96%   |
| Intel Core i9           | 8        | 1.57%   |
| AMD Athlon              | 7        | 1.37%   |
| Intel Pentium Dual-Core | 6        | 1.17%   |
| Intel Celeron           | 6        | 1.17%   |
| AMD Athlon II X2        | 6        | 1.17%   |
| AMD A8                  | 6        | 1.17%   |
| AMD Phenom II X6        | 5        | 0.98%   |
| AMD A10                 | 5        | 0.98%   |
| Intel Pentium Silver    | 4        | 0.78%   |
| Intel Core 2 Quad       | 4        | 0.78%   |
| AMD Ryzen Threadripper  | 4        | 0.78%   |
| AMD Ryzen 5 PRO         | 3        | 0.59%   |
| Other                   | 2        | 0.39%   |
| Intel Core 2            | 2        | 0.39%   |
| AMD Turion II Neo       | 2        | 0.39%   |
| AMD E2                  | 2        | 0.39%   |
| Intel Pentium Gold      | 1        | 0.2%    |
| Intel Pentium Dual      | 1        | 0.2%    |
| Intel Pentium 4         | 1        | 0.2%    |
| Intel Genuine           | 1        | 0.2%    |
| Intel Atom              | 1        | 0.2%    |
| AMD Six-Core Opteron    | 1        | 0.2%    |
| AMD Sempron             | 1        | 0.2%    |
| AMD Ryzen 7 PRO         | 1        | 0.2%    |
| AMD Ryzen 3 PRO         | 1        | 0.2%    |
| AMD Phenom II X3        | 1        | 0.2%    |
| AMD Phenom II X2        | 1        | 0.2%    |
| AMD Phenom              | 1        | 0.2%    |
| AMD Opteron             | 1        | 0.2%    |
| AMD Athlon X4           | 1        | 0.2%    |
| AMD Athlon II X4        | 1        | 0.2%    |
| AMD Athlon II X3        | 1        | 0.2%    |
| AMD Athlon II Neo       | 1        | 0.2%    |
| AMD Athlon 64           | 1        | 0.2%    |
| AMD A6                  | 1        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 221      | 43.16%  |
| 6       | 86       | 16.8%   |
| 2       | 82       | 16.02%  |
| 8       | 62       | 12.11%  |
| 12      | 20       | 3.91%   |
| 16      | 14       | 2.73%   |
| 3       | 11       | 2.15%   |
| 1       | 6        | 1.17%   |
| 24      | 3        | 0.59%   |
| 10      | 3        | 0.59%   |
| 32      | 2        | 0.39%   |
| 44      | 1        | 0.2%    |
| Unknown | 1        | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 497      | 97.45%  |
| 2      | 13       | 2.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 328      | 64.06%  |
| 1       | 183      | 35.74%  |
| Unknown | 1        | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 481      | 93.95%  |
| Unknown        | 30       | 5.86%   |
| 32-bit         | 1        | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 9.18%   |
| 0x306c3    | 42       | 8.03%   |
| 0x206a7    | 34       | 6.5%    |
| 0x08701021 | 31       | 5.93%   |
| 0x306a9    | 29       | 5.54%   |
| 0x0800820d | 23       | 4.4%    |
| 0x06000852 | 23       | 4.4%    |
| 0x506e3    | 22       | 4.21%   |
| 0x010000c8 | 17       | 3.25%   |
| 0x906e9    | 16       | 3.06%   |
| 0x08001138 | 16       | 3.06%   |
| 0x08701013 | 15       | 2.87%   |
| 0x0a201009 | 14       | 2.68%   |
| 0x906ea    | 13       | 2.49%   |
| 0x1067a    | 13       | 2.49%   |
| 0x08108109 | 11       | 2.1%    |
| 0x08001137 | 11       | 2.1%    |
| 0x306f2    | 7        | 1.34%   |
| 0x06001119 | 7        | 1.34%   |
| 0xa0655    | 6        | 1.15%   |
| 0xa0653    | 6        | 1.15%   |
| 0x206d7    | 6        | 1.15%   |
| 0x08101016 | 6        | 1.15%   |
| 0x010000dc | 6        | 1.15%   |
| 0x906ed    | 5        | 0.96%   |
| 0x706a1    | 5        | 0.96%   |
| 0x106e5    | 5        | 0.96%   |
| 0x0600063e | 5        | 0.96%   |
| 0x010000db | 5        | 0.96%   |
| 0x306e4    | 4        | 0.76%   |
| 0x0a201016 | 4        | 0.76%   |
| 0x08600106 | 4        | 0.76%   |
| 0x6fb      | 3        | 0.57%   |
| 0x50654    | 3        | 0.57%   |
| 0x20655    | 3        | 0.57%   |
| 0x106a5    | 3        | 0.57%   |
| 0x10676    | 3        | 0.57%   |
| 0x0810100b | 3        | 0.57%   |
| 0x0700010f | 3        | 0.57%   |
| 0x06003106 | 3        | 0.57%   |
| 0xa0671    | 2        | 0.38%   |
| 0x906ec    | 2        | 0.38%   |
| 0x6fd      | 2        | 0.38%   |
| 0x406f1    | 2        | 0.38%   |
| 0x10677    | 2        | 0.38%   |
| 0x0a201204 | 2        | 0.38%   |
| 0x08001129 | 2        | 0.38%   |
| 0x05000119 | 2        | 0.38%   |
| 0x01000095 | 2        | 0.38%   |
| 0xf29      | 1        | 0.19%   |
| 0xa0652    | 1        | 0.19%   |
| 0x906eb    | 1        | 0.19%   |
| 0x706a8    | 1        | 0.19%   |
| 0x6f6      | 1        | 0.19%   |
| 0x406f0    | 1        | 0.19%   |
| 0x406c4    | 1        | 0.19%   |
| 0x306d4    | 1        | 0.19%   |
| 0x206c2    | 1        | 0.19%   |
| 0x106ca    | 1        | 0.19%   |
| 0x106a4    | 1        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 56       | 10.94%  |
| Zen 2         | 53       | 10.35%  |
| Zen           | 43       | 8.4%    |
| SandyBridge   | 40       | 7.81%   |
| KabyLake      | 40       | 7.81%   |
| Zen+          | 38       | 7.42%   |
| IvyBridge     | 35       | 6.84%   |
| Piledriver    | 32       | 6.25%   |
| K10           | 31       | 6.05%   |
| Skylake       | 27       | 5.27%   |
| Zen 3         | 23       | 4.49%   |
| Penryn        | 19       | 3.71%   |
| CometLake     | 13       | 2.54%   |
| Nehalem       | 10       | 1.95%   |
| Core          | 8        | 1.56%   |
| Goldmont plus | 6        | 1.17%   |
| Bulldozer     | 6        | 1.17%   |
| Westmere      | 4        | 0.78%   |
| Steamroller   | 4        | 0.78%   |
| Jaguar        | 4        | 0.78%   |
| Broadwell     | 4        | 0.78%   |
| K8 Hammer     | 3        | 0.59%   |
| Silvermont    | 2        | 0.39%   |
| Icelake       | 2        | 0.39%   |
| Bobcat        | 2        | 0.39%   |
| Unknown       | 2        | 0.39%   |
| Puma          | 1        | 0.2%    |
| NetBurst      | 1        | 0.2%    |
| K10 Llano     | 1        | 0.2%    |
| Excavator     | 1        | 0.2%    |
| Bonnell       | 1        | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 215      | 39.89%  |
| Nvidia                     | 198      | 36.73%  |
| Intel                      | 123      | 22.82%  |
| S3 Graphics                | 2        | 0.37%   |
| Matrox Electronics Systems | 1        | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 46       | 8.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 24       | 4.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 19       | 3.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 17       | 3.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 13       | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 11       | 1.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 1.97%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 10       | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9        | 1.61%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 1.61%   |
| Intel HD Graphics 630                                                       | 9        | 1.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 9        | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 1.43%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 8        | 1.43%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 7        | 1.25%   |
| Intel HD Graphics 530                                                       | 7        | 1.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 1.25%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 1.25%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6        | 1.07%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 1.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 6        | 1.07%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 1.07%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 6        | 1.07%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 6        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 5        | 0.89%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 5        | 0.89%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 0.89%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 5        | 0.89%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.72%   |
| Nvidia GK107GL [Quadro K2000]                                               | 4        | 0.72%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 4        | 0.72%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 4        | 0.72%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 0.72%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 4        | 0.72%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 4        | 0.72%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 4        | 0.72%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                   | 4        | 0.72%   |
| AMD Renoir                                                                  | 4        | 0.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 4        | 0.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 0.54%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3        | 0.54%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.54%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 3        | 0.54%   |
| Nvidia GM107GL [Quadro K2200]                                               | 3        | 0.54%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 0.54%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.54%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 0.54%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 0.54%   |
| Intel HD Graphics 610                                                       | 3        | 0.54%   |
| AMD Vega 20 [Radeon VII]                                                    | 3        | 0.54%   |
| AMD RS880 [Radeon HD 4250]                                                  | 3        | 0.54%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 3        | 0.54%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                     | 3        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x AMD            | 199      | 38.49%  |
| 1 x Nvidia         | 181      | 35.01%  |
| 1 x Intel          | 100      | 19.34%  |
| 2 x AMD            | 9        | 1.74%   |
| Intel + Nvidia     | 7        | 1.35%   |
| 2 x Nvidia         | 6        | 1.16%   |
| AMD + Nvidia       | 5        | 0.97%   |
| Intel + AMD        | 4        | 0.77%   |
| 1 x S3 Graphics    | 2        | 0.39%   |
| Other              | 1        | 0.19%   |
| 2 x Intel          | 1        | 0.19%   |
| 1 x Matrox         | 1        | 0.19%   |
| Intel + 2 x Nvidia | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 357      | 68.65%  |
| Proprietary | 148      | 28.46%  |
| Unknown     | 15       | 2.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 151      | 28.76%  |
| 1.01-2.0   | 84       | 16%     |
| 7.01-8.0   | 80       | 15.24%  |
| 3.01-4.0   | 65       | 12.38%  |
| 0.51-1.0   | 52       | 9.9%    |
| 0.01-0.5   | 42       | 8%      |
| 5.01-6.0   | 23       | 4.38%   |
| 8.01-16.0  | 17       | 3.24%   |
| 2.01-3.0   | 6        | 1.14%   |
| 16.01-24.0 | 4        | 0.76%   |
| 4.01-5.0   | 1        | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 95       | 16.52%  |
| Dell                 | 69       | 12%     |
| Goldstar             | 55       | 9.57%   |
| Ancor Communications | 45       | 7.83%   |
| Acer                 | 43       | 7.48%   |
| Hewlett-Packard      | 42       | 7.3%    |
| BenQ                 | 41       | 7.13%   |
| AOC                  | 25       | 4.35%   |
| Philips              | 24       | 4.17%   |
| Lenovo               | 12       | 2.09%   |
| LG Electronics       | 11       | 1.91%   |
| ASUSTek Computer     | 11       | 1.91%   |
| Iiyama               | 9        | 1.57%   |
| ViewSonic            | 8        | 1.39%   |
| Unknown              | 8        | 1.39%   |
| Sceptre Tech         | 6        | 1.04%   |
| Fujitsu Siemens      | 6        | 1.04%   |
| Eizo                 | 5        | 0.87%   |
| Vizio                | 3        | 0.52%   |
| Sony                 | 3        | 0.52%   |
| Panasonic            | 3        | 0.52%   |
| NEC Computers        | 3        | 0.52%   |
| Medion               | 3        | 0.52%   |
| Sharp                | 2        | 0.35%   |
| RS                   | 2        | 0.35%   |
| MSI                  | 2        | 0.35%   |
| Lite-On              | 2        | 0.35%   |
| HPN                  | 2        | 0.35%   |
| HKC                  | 2        | 0.35%   |
| Hitachi              | 2        | 0.35%   |
| Element              | 2        | 0.35%   |
| ___                  | 1        | 0.17%   |
| Vestel Elektronik    | 1        | 0.17%   |
| Unknown (AAA)        | 1        | 0.17%   |
| UGD                  | 1        | 0.17%   |
| Toshiba              | 1        | 0.17%   |
| TCL                  | 1        | 0.17%   |
| TAR                  | 1        | 0.17%   |
| PRI                  | 1        | 0.17%   |
| PPC                  | 1        | 0.17%   |
| Optoma               | 1        | 0.17%   |
| NEX                  | 1        | 0.17%   |
| NECCI                | 1        | 0.17%   |
| LLL                  | 1        | 0.17%   |
| Insignia             | 1        | 0.17%   |
| Hyundai ImageQuest   | 1        | 0.17%   |
| HVT                  | 1        | 0.17%   |
| HannStar Display     | 1        | 0.17%   |
| HannStar             | 1        | 0.17%   |
| Gigabyte Technology  | 1        | 0.17%   |
| Elo Touch            | 1        | 0.17%   |
| Elgato               | 1        | 0.17%   |
| DEX                  | 1        | 0.17%   |
| Denver               | 1        | 0.17%   |
| Compal               | 1        | 0.17%   |
| Belinea              | 1        | 0.17%   |
| AUS                  | 1        | 0.17%   |
| Arnos Instruments    | 1        | 0.17%   |
| Apple                | 1        | 0.17%   |
| AGO                  | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                     | 8        | 1.26%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 4        | 0.63%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 4        | 0.63%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                       | 4        | 0.63%   |
| Unknown LCD Monitor MCE Metz TV 1080 3840x1080                          | 3        | 0.47%   |
| Unknown LCD Monitor MCE Metz TV 1080                                    | 3        | 0.47%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 3        | 0.47%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch       | 3        | 0.47%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch       | 3        | 0.47%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 3        | 0.47%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3        | 0.47%   |
| Lenovo L2250p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch                | 3        | 0.47%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch              | 3        | 0.47%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 3        | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 0.47%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                  | 3        | 0.47%   |
| Dell U2713HM DEL4080 2560x1440 600x340mm 27.2-inch                      | 3        | 0.47%   |
| Dell E2214H DELA09E 1920x1080 480x270mm 21.7-inch                       | 3        | 0.47%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                       | 3        | 0.47%   |
| AOC 2460G4 AOC246A 1920x1080 531x299mm 24.0-inch                        | 3        | 0.47%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 3        | 0.47%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 600x340mm 27.2-inch   | 3        | 0.47%   |
| Sceptre Tech E24 SPT09B4 1920x1080 575x323mm 26.0-inch                  | 2        | 0.32%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                  | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch     | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM0351 1680x1050 459x296mm 21.5-inch    | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 433x271mm 20.1-inch    | 2        | 0.32%   |
| Samsung Electronics SyncMaster SAM021C 1400x1050 408x300mm 19.9-inch    | 2        | 0.32%   |
| Samsung Electronics SMS27A850T SAM0887 2560x1440 518x324mm 24.1-inch    | 2        | 0.32%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 510x290mm 23.1-inch    | 2        | 0.32%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch    | 2        | 0.32%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch       | 2        | 0.32%   |
| Samsung Electronics S22B300 SAM08AA 1920x1080 477x268mm 21.5-inch       | 2        | 0.32%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2        | 0.32%   |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch       | 2        | 0.32%   |
| RS LE2262 BTC2262 1680x1050 473x296mm 22.0-inch                         | 2        | 0.32%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                      | 2        | 0.32%   |
| Lite-On DC/EC150ATA LTN0208 1024x768 304x228mm 15.0-inch                | 2        | 0.32%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                       | 2        | 0.32%   |
| Lenovo T2224pD LEN60CA 1920x1080 476x267mm 21.5-inch                    | 2        | 0.32%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                   | 2        | 0.32%   |
| HKC CH70 HKC27A9 1920x1080 597x336mm 27.0-inch                          | 2        | 0.32%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 408x255mm 18.9-inch              | 2        | 0.32%   |
| Hewlett-Packard E273q HPN3475 2560x1440 597x336mm 27.0-inch             | 2        | 0.32%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch             | 2        | 0.32%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                | 2        | 0.32%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                    | 2        | 0.32%   |
| Goldstar L226W GSM566B 1680x1050 474x296mm 22.0-inch                    | 2        | 0.32%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 2        | 0.32%   |
| Element ELEFW504A ELE1366 1920x1080                                     | 2        | 0.32%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                       | 2        | 0.32%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                        | 2        | 0.32%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                      | 2        | 0.32%   |
| Dell S2716DG DELA0D1 2560x1440 600x340mm 27.2-inch                      | 2        | 0.32%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                       | 2        | 0.32%   |
| Dell LCD Monitor U3417W 3440x1440                                       | 2        | 0.32%   |
| BenQ SW2700 BNQ7F47 2560x1440 596x335mm 26.9-inch                       | 2        | 0.32%   |
| BenQ GL2250H BNQ78A1 1920x1080 477x268mm 21.5-inch                      | 2        | 0.32%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch            | 2        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 261      | 46.36%  |
| 2560x1440 (QHD)    | 66       | 11.72%  |
| 3840x2160 (4K)     | 41       | 7.28%   |
| 1680x1050 (WSXGA+) | 25       | 4.44%   |
| 1920x1200 (WUXGA)  | 24       | 4.26%   |
| 1280x1024 (SXGA)   | 24       | 4.26%   |
| Unknown            | 21       | 3.73%   |
| 1440x900 (WXGA+)   | 18       | 3.2%    |
| 3840x1080          | 12       | 2.13%   |
| 2560x1080          | 12       | 2.13%   |
| 1366x768 (WXGA)    | 12       | 2.13%   |
| 3440x1440          | 10       | 1.78%   |
| 1600x900 (HD+)     | 7        | 1.24%   |
| 1024x768 (XGA)     | 7        | 1.24%   |
| 3840x1200          | 3        | 0.53%   |
| 1400x1050          | 2        | 0.36%   |
| 1360x768           | 2        | 0.36%   |
| 1280x720 (HD)      | 2        | 0.36%   |
| 7680x1440          | 1        | 0.18%   |
| 7280x2160          | 1        | 0.18%   |
| 6520x1440          | 1        | 0.18%   |
| 640x480            | 1        | 0.18%   |
| 5760x2160          | 1        | 0.18%   |
| 5520x1080          | 1        | 0.18%   |
| 3200x1080          | 1        | 0.18%   |
| 2732x768           | 1        | 0.18%   |
| 2560x1600          | 1        | 0.18%   |
| 2048x1536          | 1        | 0.18%   |
| 1920x540           | 1        | 0.18%   |
| 1600x1200          | 1        | 0.18%   |
| 1280x960           | 1        | 0.18%   |
| 1280x768           | 1        | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 106      | 18.66%  |
| 24      | 93       | 16.37%  |
| 21      | 69       | 12.15%  |
| Unknown | 60       | 10.56%  |
| 23      | 55       | 9.68%   |
| 19      | 26       | 4.58%   |
| 31      | 24       | 4.23%   |
| 22      | 19       | 3.35%   |
| 34      | 15       | 2.64%   |
| 18      | 14       | 2.46%   |
| 20      | 13       | 2.29%   |
| 17      | 13       | 2.29%   |
| 15      | 12       | 2.11%   |
| 32      | 7        | 1.23%   |
| 25      | 7        | 1.23%   |
| 72      | 6        | 1.06%   |
| 26      | 5        | 0.88%   |
| 40      | 4        | 0.7%    |
| 84      | 3        | 0.53%   |
| 54      | 3        | 0.53%   |
| 29      | 3        | 0.53%   |
| 33      | 2        | 0.35%   |
| 74      | 1        | 0.18%   |
| 60      | 1        | 0.18%   |
| 49      | 1        | 0.18%   |
| 47      | 1        | 0.18%   |
| 46      | 1        | 0.18%   |
| 42      | 1        | 0.18%   |
| 39      | 1        | 0.18%   |
| 28      | 1        | 0.18%   |
| 12      | 1        | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 236      | 42.99%  |
| 401-500     | 126      | 22.95%  |
| Unknown     | 60       | 10.93%  |
| 601-700     | 41       | 7.47%   |
| 701-800     | 23       | 4.19%   |
| 301-350     | 21       | 3.83%   |
| 351-400     | 18       | 3.28%   |
| 1501-2000   | 10       | 1.82%   |
| 1001-1500   | 7        | 1.28%   |
| 801-900     | 5        | 0.91%   |
| 201-300     | 1        | 0.18%   |
| 901-1000    | 1        | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 337      | 64.31%  |
| 16/10   | 75       | 14.31%  |
| Unknown | 56       | 10.69%  |
| 5/4     | 21       | 4.01%   |
| 21/9    | 17       | 3.24%   |
| 4/3     | 14       | 2.67%   |
| 6/5     | 2        | 0.38%   |
| 3/2     | 2        | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 179      | 32.02%  |
| 301-350        | 108      | 19.32%  |
| Unknown        | 60       | 10.73%  |
| 151-200        | 57       | 10.2%   |
| 351-500        | 49       | 8.77%   |
| 251-300        | 46       | 8.23%   |
| 141-150        | 21       | 3.76%   |
| More than 1000 | 15       | 2.68%   |
| 101-110        | 11       | 1.97%   |
| 501-1000       | 8        | 1.43%   |
| 131-140        | 3        | 0.54%   |
| 71-80          | 1        | 0.18%   |
| 91-100         | 1        | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 305      | 57.44%  |
| 101-120 | 119      | 22.41%  |
| Unknown | 60       | 11.3%   |
| 121-160 | 27       | 5.08%   |
| 1-50    | 13       | 2.45%   |
| 161-240 | 7        | 1.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 380      | 72.24%  |
| 2     | 116      | 22.05%  |
| 0     | 24       | 4.56%   |
| 3     | 6        | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 324      | 45.38%  |
| Intel                                  | 221      | 30.95%  |
| Qualcomm Atheros                       | 41       | 5.74%   |
| Broadcom                               | 25       | 3.5%    |
| Ralink                                 | 11       | 1.54%   |
| TP-Link                                | 10       | 1.4%    |
| Ralink Technology                      | 9        | 1.26%   |
| Nvidia                                 | 8        | 1.12%   |
| ASIX Electronics                       | 8        | 1.12%   |
| Aquantia                               | 5        | 0.7%    |
| MediaTek                               | 4        | 0.56%   |
| Edimax Technology                      | 4        | 0.56%   |
| Microsoft                              | 3        | 0.42%   |
| Texas Instruments                      | 2        | 0.28%   |
| Samsung Electronics                    | 2        | 0.28%   |
| Qualcomm Atheros Communications        | 2        | 0.28%   |
| NetXen Incorporated                    | 2        | 0.28%   |
| NetGear                                | 2        | 0.28%   |
| Motorola PCS                           | 2        | 0.28%   |
| Marvell Technology Group               | 2        | 0.28%   |
| D-Link System                          | 2        | 0.28%   |
| D-Link                                 | 2        | 0.28%   |
| Broadcom Limited                       | 2        | 0.28%   |
| AVM                                    | 2        | 0.28%   |
| ASUSTek Computer                       | 2        | 0.28%   |
| ZyXEL Communications                   | 1        | 0.14%   |
| VIA Technologies                       | 1        | 0.14%   |
| TOMTOM                                 | 1        | 0.14%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.14%   |
| Sigma Designs                          | 1        | 0.14%   |
| ROCCAT                                 | 1        | 0.14%   |
| Microchip Technology                   | 1        | 0.14%   |
| Mellanox Technologies                  | 1        | 0.14%   |
| Intersil                               | 1        | 0.14%   |
| IMC Networks                           | 1        | 0.14%   |
| Holtek Semiconductor                   | 1        | 0.14%   |
| Google                                 | 1        | 0.14%   |
| DisplayLink                            | 1        | 0.14%   |
| BUFFALO                                | 1        | 0.14%   |
| Belkin Components                      | 1        | 0.14%   |
| ADMtek                                 | 1        | 0.14%   |
| 3Com                                   | 1        | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 275      | 34.12%  |
| Intel I211 Gigabit Network Connection                             | 46       | 5.71%   |
| Intel Wi-Fi 6 AX200                                               | 26       | 3.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 25       | 3.1%    |
| Intel Ethernet Connection (2) I219-V                              | 23       | 2.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 14       | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 12       | 1.49%   |
| Intel Wireless-AC 9260                                            | 10       | 1.24%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 1.12%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.12%   |
| Intel Wireless 7260                                               | 8        | 0.99%   |
| Intel I210 Gigabit Network Connection                             | 8        | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 8        | 0.99%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8        | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 7        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.62%   |
| Intel Wireless 8260                                               | 5        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.5%    |
| Intel I350 Gigabit Network Connection                             | 4        | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 4        | 0.5%    |
| Intel Ethernet Connection (2) I218-LM                             | 4        | 0.5%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 0.5%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 0.37%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.37%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 3        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3        | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.37%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 3        | 0.37%   |
| Nvidia MCP61 Ethernet                                             | 3        | 0.37%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.37%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 3        | 0.37%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 3        | 0.37%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                  | 3        | 0.37%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 0.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.25%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.25%   |
| Texas Instruments CC2531 ZigBee                                   | 2        | 0.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.25%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.25%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 2        | 0.25%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 79       | 37.98%  |
| Realtek Semiconductor           | 40       | 19.23%  |
| Qualcomm Atheros                | 23       | 11.06%  |
| Ralink                          | 11       | 5.29%   |
| Broadcom                        | 10       | 4.81%   |
| TP-Link                         | 9        | 4.33%   |
| Ralink Technology               | 9        | 4.33%   |
| Edimax Technology               | 4        | 1.92%   |
| Microsoft                       | 3        | 1.44%   |
| MEDIATEK                        | 3        | 1.44%   |
| Qualcomm Atheros Communications | 2        | 0.96%   |
| NetGear                         | 2        | 0.96%   |
| D-Link                          | 2        | 0.96%   |
| AVM                             | 2        | 0.96%   |
| ASUSTek Computer                | 2        | 0.96%   |
| ZyXEL Communications            | 1        | 0.48%   |
| Intersil                        | 1        | 0.48%   |
| IMC Networks                    | 1        | 0.48%   |
| D-Link System                   | 1        | 0.48%   |
| BUFFALO                         | 1        | 0.48%   |
| Broadcom Limited                | 1        | 0.48%   |
| Belkin Components               | 1        | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 26       | 12.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 14       | 6.73%   |
| Intel Wireless-AC 9260                                                                        | 10       | 4.81%   |
| Intel Wireless 7260                                                                           | 8        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 7        | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 5        | 2.4%    |
| Intel Wireless 8260                                                                           | 5        | 2.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 4        | 1.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 4        | 1.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 3        | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 1.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 3        | 1.44%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 1.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 3        | 1.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3        | 1.44%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 3        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3        | 1.44%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                                | 3        | 1.44%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 3        | 1.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2        | 0.96%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 2        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 2        | 0.96%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2        | 0.96%   |
| Ralink RT5572 Wireless Adapter                                                                | 2        | 0.96%   |
| Ralink RT5370 Wireless Adapter                                                                | 2        | 0.96%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 2        | 0.96%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 2        | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2        | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 2        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 0.96%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 0.96%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                                                 | 2        | 0.96%   |
| Intel Wireless 8265 / 8275                                                                    | 2        | 0.96%   |
| Intel Wireless 7265                                                                           | 2        | 0.96%   |
| Intel Wireless 3165                                                                           | 2        | 0.96%   |
| Intel Wireless 3160                                                                           | 2        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2        | 0.96%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                                  | 1        | 0.48%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 1        | 0.48%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 1        | 0.48%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1        | 0.48%   |
| TP-Link Archer T4U ver.3                                                                      | 1        | 0.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1        | 0.48%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1        | 0.48%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 1        | 0.48%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                                      | 1        | 0.48%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 0.48%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.48%   |
| Realtek 802.11ac WLAN Adapter                                                                 | 1        | 0.48%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.48%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.48%   |
| Ralink RT3072 Wireless Adapter                                                                | 1        | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 314      | 55.09%  |
| Intel                                  | 181      | 31.75%  |
| Qualcomm Atheros                       | 20       | 3.51%   |
| Broadcom                               | 16       | 2.81%   |
| Nvidia                                 | 8        | 1.4%    |
| ASIX Electronics                       | 8        | 1.4%    |
| Aquantia                               | 5        | 0.88%   |
| Samsung Electronics                    | 2        | 0.35%   |
| NetXen Incorporated                    | 2        | 0.35%   |
| Motorola PCS                           | 2        | 0.35%   |
| Marvell Technology Group               | 2        | 0.35%   |
| VIA Technologies                       | 1        | 0.18%   |
| TP-Link                                | 1        | 0.18%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.18%   |
| MediaTek                               | 1        | 0.18%   |
| Google                                 | 1        | 0.18%   |
| DisplayLink                            | 1        | 0.18%   |
| D-Link System                          | 1        | 0.18%   |
| Broadcom Limited                       | 1        | 0.18%   |
| ADMtek                                 | 1        | 0.18%   |
| 3Com                                   | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 275      | 46.61%  |
| Intel I211 Gigabit Network Connection                                | 46       | 7.8%    |
| Realtek RTL8125 2.5GbE Controller                                    | 25       | 4.24%   |
| Intel Ethernet Connection (2) I219-V                                 | 23       | 3.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 17       | 2.88%   |
| Intel Ethernet Connection I217-LM                                    | 12       | 2.03%   |
| Intel Ethernet Connection (7) I219-V                                 | 9        | 1.53%   |
| Intel 82579V Gigabit Network Connection                              | 9        | 1.53%   |
| Intel I210 Gigabit Network Connection                                | 8        | 1.36%   |
| Intel Ethernet Connection I217-V                                     | 8        | 1.36%   |
| Intel 82574L Gigabit Network Connection                              | 8        | 1.36%   |
| ASIX AX88179 Gigabit Ethernet                                        | 8        | 1.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7        | 1.19%   |
| Intel Ethernet Connection (2) I218-V                                 | 7        | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                           | 6        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                | 5        | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 4        | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 4        | 0.68%   |
| Intel I350 Gigabit Network Connection                                | 4        | 0.68%   |
| Intel Ethernet Controller I225-V                                     | 4        | 0.68%   |
| Intel Ethernet Connection (2) I218-LM                                | 4        | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]    | 4        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 3        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 3        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 3        | 0.51%   |
| Nvidia MCP61 Ethernet                                                | 3        | 0.51%   |
| Intel Ethernet Connection (11) I219-V                                | 3        | 0.51%   |
| Intel 82541PI Gigabit Ethernet Controller                            | 3        | 0.51%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                     | 3        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 2        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 2        | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 2        | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 2        | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 2        | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 2        | 0.34%   |
| Nvidia MCP77 Ethernet                                                | 2        | 0.34%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 2        | 0.34%   |
| Motorola PCS XT1058                                                  | 2        | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller              | 2        | 0.34%   |
| Intel Ethernet Connection (7) I219-LM                                | 2        | 0.34%   |
| Intel Ethernet Connection (11) I219-LM                               | 2        | 0.34%   |
| Intel 82578DM Gigabit Network Connection                             | 2        | 0.34%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                       | 2        | 0.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 2        | 0.34%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                     | 2        | 0.34%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                      | 2        | 0.34%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 2        | 0.34%   |
| VIA VT6105/VT6106S [Rhine-III]                                       | 1        | 0.17%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]      | 1        | 0.17%   |
| Sony Ericsson Mobile AB H3213                                        | 1        | 0.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1        | 0.17%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1        | 0.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1        | 0.17%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                        | 1        | 0.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1        | 0.17%   |
| Nvidia MCP73 Ethernet                                                | 1        | 0.17%   |
| Nvidia MCP55 Ethernet                                                | 1        | 0.17%   |
| Nvidia CK804 Ethernet Controller                                     | 1        | 0.17%   |
| MediaTek WP7                                                         | 1        | 0.17%   |
| Intel Ethernet Controller I225-LM                                    | 1        | 0.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 507      | 70.91%  |
| WiFi     | 201      | 28.11%  |
| Unknown  | 4        | 0.56%   |
| Modem    | 3        | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 492      | 76.52%  |
| WiFi     | 150      | 23.33%  |
| Unknown  | 1        | 0.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 309      | 60.35%  |
| 2     | 152      | 29.69%  |
| 3     | 34       | 6.64%   |
| 4     | 8        | 1.56%   |
| 0     | 6        | 1.17%   |
| 5     | 3        | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 457      | 87.55%  |
| Yes  | 65       | 12.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 74       | 39.57%  |
| Cambridge Silicon Radio         | 57       | 30.48%  |
| Realtek Semiconductor           | 13       | 6.95%   |
| Broadcom                        | 12       | 6.42%   |
| ASUSTek Computer                | 11       | 5.88%   |
| Qualcomm Atheros Communications | 5        | 2.67%   |
| Apple                           | 3        | 1.6%    |
| MediaTek                        | 2        | 1.07%   |
| IMC Networks                    | 2        | 1.07%   |
| HTC (High Tech Computer)        | 2        | 1.07%   |
| Belkin Components               | 2        | 1.07%   |
| Realtek                         | 1        | 0.53%   |
| Mobile Action Technology        | 1        | 0.53%   |
| Lite-On Technology              | 1        | 0.53%   |
| Dell                            | 1        | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 57       | 30.48%  |
| Intel AX200 Bluetooth                                                | 24       | 12.83%  |
| Intel Bluetooth wireless interface                                   | 19       | 10.16%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 13       | 6.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 11       | 5.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 6        | 3.21%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 5        | 2.67%   |
| Realtek Bluetooth Radio                                              | 5        | 2.67%   |
| Intel Bluetooth Device                                               | 4        | 2.14%   |
| ASUS Bluetooth Adapter                                               | 4        | 2.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3        | 1.6%    |
| Realtek RTL8821A Bluetooth                                           | 2        | 1.07%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 1.07%   |
| MediaTek Wireless_Device                                             | 2        | 1.07%   |
| IMC Networks Bluetooth Radio                                         | 2        | 1.07%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 1.07%   |
| Broadcom BCM2045 Bluetooth                                           | 2        | 1.07%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2        | 1.07%   |
| ASUS ASUS USB-BT500                                                  | 2        | 1.07%   |
| Apple Bluetooth USB Host Controller                                  | 2        | 1.07%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 1        | 0.53%   |
| Realtek Bluetooth Radio                                              | 1        | 0.53%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1        | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.53%   |
| Mobile Action MA-730/MA-730G Bluetooth Adapter                       | 1        | 0.53%   |
| Lite-On Bluetooth Device                                             | 1        | 0.53%   |
| Dell Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.53%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.53%   |
| Broadcom BCM43142A0 Bluetooth Device                                 | 1        | 0.53%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.53%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter         | 1        | 0.53%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.53%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.53%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.53%   |
| ASUS Bluetooth Device                                                | 1        | 0.53%   |
| ASUS BCM20702A0                                                      | 1        | 0.53%   |
| Apple Bluetooth HCI                                                  | 1        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 281      | 32.22%  |
| Intel                       | 251      | 28.78%  |
| Nvidia                      | 188      | 21.56%  |
| C-Media Electronics         | 26       | 2.98%   |
| Creative Labs               | 18       | 2.06%   |
| Logitech                    | 13       | 1.49%   |
| Texas Instruments           | 9        | 1.03%   |
| Generalplus Technology      | 7        | 0.8%    |
| Sennheiser Communications   | 5        | 0.57%   |
| JMTek                       | 5        | 0.57%   |
| SteelSeries ApS             | 4        | 0.46%   |
| M-Audio                     | 4        | 0.46%   |
| Corsair                     | 4        | 0.46%   |
| Yamaha                      | 3        | 0.34%   |
| Samson Technologies         | 3        | 0.34%   |
| Kingston Technology         | 3        | 0.34%   |
| Focusrite-Novation          | 3        | 0.34%   |
| Creative Technology         | 3        | 0.34%   |
| ASUSTek Computer            | 3        | 0.34%   |
| VIA Technologies            | 2        | 0.23%   |
| RODE Microphones            | 2        | 0.23%   |
| Razer USA                   | 2        | 0.23%   |
| Plantronics                 | 2        | 0.23%   |
| Hewlett-Packard             | 2        | 0.23%   |
| GN Netcom                   | 2        | 0.23%   |
| Fry's Electronics           | 2        | 0.23%   |
| Dell                        | 2        | 0.23%   |
| Blue Microphones            | 2        | 0.23%   |
| BEHRINGER International     | 2        | 0.23%   |
| ZOOM                        | 1        | 0.11%   |
| XMOS                        | 1        | 0.11%   |
| TerraTec Electronic         | 1        | 0.11%   |
| Syntek                      | 1        | 0.11%   |
| Superlux digit              | 1        | 0.11%   |
| Schiit Audio                | 1        | 0.11%   |
| SAVITECH                    | 1        | 0.11%   |
| Native Instruments          | 1        | 0.11%   |
| FiiO Electronics Technology | 1        | 0.11%   |
| Ensoniq                     | 1        | 0.11%   |
| EGO SYStems                 | 1        | 0.11%   |
| DYNEX                       | 1        | 0.11%   |
| Cooler Master               | 1        | 0.11%   |
| CME                         | 1        | 0.11%   |
| Chicony Electronics         | 1        | 0.11%   |
| Best Buy                    | 1        | 0.11%   |
| Antlion Audio               | 1        | 0.11%   |
| Alesis                      | 1        | 0.11%   |
| AKAI Professional M.I.      | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 66       | 6.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 57       | 5.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 53       | 5.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 47       | 4.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 37       | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 35       | 3.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 29       | 2.75%   |
| AMD Family 17h/19h HD Audio Controller                                            | 29       | 2.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 24       | 2.27%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 24       | 2.27%   |
| Nvidia GP104 High Definition Audio Controller                                     | 22       | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 22       | 2.08%   |
| AMD Navi 10 HDMI Audio                                                            | 21       | 1.99%   |
| Intel 200 Series PCH HD Audio                                                     | 20       | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 19       | 1.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 18       | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                        | 16       | 1.52%   |
| AMD FCH Azalia Controller                                                         | 16       | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 15       | 1.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 13       | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                                     | 12       | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 12       | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                                     | 11       | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 10       | 0.95%   |
| Nvidia GM206 High Definition Audio Controller                                     | 9        | 0.85%   |
| Nvidia GK104 HDMI Audio Controller                                                | 9        | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9        | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                                     | 8        | 0.76%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 8        | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 8        | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 8        | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                                     | 7        | 0.66%   |
| Nvidia GP102 HDMI Audio Controller                                                | 7        | 0.66%   |
| Nvidia GA102 High Definition Audio Controller                                     | 7        | 0.66%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 0.66%   |
| Generalplus Technology USB Audio Device                                           | 7        | 0.66%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 7        | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                | 6        | 0.57%   |
| Nvidia GK106 HDMI Audio Controller                                                | 6        | 0.57%   |
| Intel Comet Lake PCH cAVS                                                         | 6        | 0.57%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 6        | 0.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6        | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                          | 6        | 0.57%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 0.57%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 0.47%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 0.47%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 0.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 5        | 0.47%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 5        | 0.47%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 5        | 0.47%   |
| Texas Instruments PCM2900 Audio Codec                                             | 4        | 0.38%   |
| Nvidia High Definition Audio Controller                                           | 4        | 0.38%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4        | 0.38%   |
| Nvidia GF116 High Definition Audio Controller                                     | 4        | 0.38%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 0.38%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]         | 4        | 0.38%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 4        | 0.38%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 4        | 0.38%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 4        | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 73       | 18.96%  |
| Unknown             | 55       | 14.29%  |
| Crucial             | 45       | 11.69%  |
| Corsair             | 45       | 11.69%  |
| G.Skill             | 41       | 10.65%  |
| Samsung Electronics | 30       | 7.79%   |
| SK Hynix            | 23       | 5.97%   |
| Micron Technology   | 22       | 5.71%   |
| Patriot             | 10       | 2.6%    |
| Nanya Technology    | 6        | 1.56%   |
| Elpida              | 4        | 1.04%   |
| Avant               | 3        | 0.78%   |
| A-DATA Technology   | 3        | 0.78%   |
| Transcend           | 2        | 0.52%   |
| Team                | 2        | 0.52%   |
| AMD                 | 2        | 0.52%   |
| Unknown (ABCD)      | 1        | 0.26%   |
| Unknown (0x02BA)    | 1        | 0.26%   |
| Unknown (07FB)      | 1        | 0.26%   |
| Unifosa             | 1        | 0.26%   |
| TakeMS              | 1        | 0.26%   |
| Smart               | 1        | 0.26%   |
| Silicon Power       | 1        | 0.26%   |
| SanDisk             | 1        | 0.26%   |
| Ramaxel Technology  | 1        | 0.26%   |
| PRINCETON           | 1        | 0.26%   |
| Neo Forza           | 1        | 0.26%   |
| Kllisre             | 1        | 0.26%   |
| Klevv               | 1        | 0.26%   |
| GeIL                | 1        | 0.26%   |
| Exceleram           | 1        | 0.26%   |
| binful              | 1        | 0.26%   |
| ASint Technology    | 1        | 0.26%   |
| Apacer              | 1        | 0.26%   |
| Unknown             | 1        | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 9        | 2.13%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 5        | 1.18%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s          | 5        | 1.18%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s      | 5        | 1.18%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 4        | 0.95%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 3        | 0.71%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 3        | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 3        | 0.71%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s      | 3        | 0.71%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s        | 3        | 0.71%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 3        | 0.71%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 3        | 0.71%   |
| Nanya RAM NT2GC64B88G0NF-CG 2048MB DIMM DDR3 1333MT/s      | 3        | 0.71%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s       | 3        | 0.71%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 3        | 0.71%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s     | 3        | 0.71%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s      | 3        | 0.71%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s     | 3        | 0.71%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 3        | 0.71%   |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s      | 3        | 0.71%   |
| Avant RAM F6451U67G1600G 4GB DIMM DDR3 800MT/s             | 3        | 0.71%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s               | 2        | 0.47%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                     | 2        | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                    | 2        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                | 2        | 0.47%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2        | 0.47%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                     | 2        | 0.47%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 2        | 0.47%   |
| SK Hynix RAM HMT351U6BFR8C-H9 4096MB DIMM DDR3 1333MT/s    | 2        | 0.47%   |
| SK Hynix RAM HMA81GU7DJR8N-VK 8GB DIMM DDR4 2666MT/s       | 2        | 0.47%   |
| Samsung RAM M393A2G40DB0-CPB 16384MB DIMM DDR4 2133MT/s    | 2        | 0.47%   |
| Samsung RAM M378B1G73QH0-CK0 8192MB DIMM DDR3 1600MT/s     | 2        | 0.47%   |
| Patriot RAM PSD416G24002 16GB DIMM DDR4 2400MT/s           | 2        | 0.47%   |
| Patriot RAM PSD34G133381 4GB DIMM DDR3 1333MT/s            | 2        | 0.47%   |
| Patriot RAM 1600 CL9 Series 4GB DIMM DDR3 1600MT/s         | 2        | 0.47%   |
| Micron RAM 4JTF25664AZ-1G6E1 2048MB DIMM DDR3 1600MT/s     | 2        | 0.47%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s               | 2        | 0.47%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s               | 2        | 0.47%   |
| Kingston RAM Module 1024MB DIMM DDR2 667MT/s               | 2        | 0.47%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s     | 2        | 0.47%   |
| Kingston RAM KHX3333C16D4/8GX 8GB DIMM DDR4 3800MT/s       | 2        | 0.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s          | 2        | 0.47%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 3200MT/s       | 2        | 0.47%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s        | 2        | 0.47%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 2        | 0.47%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s       | 2        | 0.47%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s      | 2        | 0.47%   |
| Kingston RAM 9905458-026.A00LF 4096MB DIMM DDR3 1333MT/s   | 2        | 0.47%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s     | 2        | 0.47%   |
| G.Skill RAM F4-3200C16-8GTZKW 8GB DIMM DDR4 3200MT/s       | 2        | 0.47%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s       | 2        | 0.47%   |
| G.Skill RAM F3-1866C9-8GX 8192MB DIMM DDR3 1333MT/s        | 2        | 0.47%   |
| Crucial RAM CT8G4DFD8213.C16FHP 8GB DIMM DDR4 2133MT/s     | 2        | 0.47%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3800MT/s   | 2        | 0.47%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s   | 2        | 0.47%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s     | 2        | 0.47%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s      | 2        | 0.47%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s        | 2        | 0.47%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s     | 2        | 0.47%   |
| Unknown RAM V02D4L88GB1G81G82400 8192MB DIMM DDR4 2400MT/s | 1        | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 169      | 50.6%   |
| DDR3    | 108      | 32.34%  |
| Unknown | 30       | 8.98%   |
| DDR2    | 15       | 4.49%   |
| SDRAM   | 9        | 2.69%   |
| DDR     | 2        | 0.6%    |
| LPDDR4  | 1        | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 313      | 94.28%  |
| SODIMM  | 15       | 4.52%   |
| RIMM    | 2        | 0.6%    |
| FB-DIMM | 2        | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 144      | 39.34%  |
| 4096  | 87       | 23.77%  |
| 16384 | 63       | 17.21%  |
| 2048  | 44       | 12.02%  |
| 32768 | 13       | 3.55%   |
| 1024  | 13       | 3.55%   |
| 512   | 2        | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 61       | 16.58%  |
| 1333    | 55       | 14.95%  |
| 3200    | 34       | 9.24%   |
| 2400    | 28       | 7.61%   |
| 3600    | 26       | 7.07%   |
| 2667    | 24       | 6.52%   |
| 2133    | 24       | 6.52%   |
| 800     | 16       | 4.35%   |
| 2666    | 11       | 2.99%   |
| 2933    | 9        | 2.45%   |
| 667     | 9        | 2.45%   |
| 3466    | 7        | 1.9%    |
| 3800    | 6        | 1.63%   |
| 1867    | 6        | 1.63%   |
| 3000    | 5        | 1.36%   |
| 2800    | 4        | 1.09%   |
| 1866    | 4        | 1.09%   |
| 1066    | 4        | 1.09%   |
| 3533    | 3        | 0.82%   |
| 3400    | 3        | 0.82%   |
| Unknown | 3        | 0.82%   |
| 3151    | 2        | 0.54%   |
| 3007    | 2        | 0.54%   |
| 400     | 2        | 0.54%   |
| 49926   | 1        | 0.27%   |
| 4199    | 1        | 0.27%   |
| 4133    | 1        | 0.27%   |
| 3733    | 1        | 0.27%   |
| 3666    | 1        | 0.27%   |
| 3500    | 1        | 0.27%   |
| 3334    | 1        | 0.27%   |
| 3100    | 1        | 0.27%   |
| 3066    | 1        | 0.27%   |
| 2934    | 1        | 0.27%   |
| 2733    | 1        | 0.27%   |
| 2048    | 1        | 0.27%   |
| 1800    | 1        | 0.27%   |
| 1639    | 1        | 0.27%   |
| 1400    | 1        | 0.27%   |
| 1200    | 1        | 0.27%   |
| 1067    | 1        | 0.27%   |
| 533     | 1        | 0.27%   |
| 333     | 1        | 0.27%   |
| 200     | 1        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 14       | 41.18%  |
| Samsung Electronics | 7        | 20.59%  |
| Brother Industries  | 6        | 17.65%  |
| Seiko Epson         | 4        | 11.76%  |
| Prolific Technology | 1        | 2.94%   |
| Kyocera             | 1        | 2.94%   |
| Canon               | 1        | 2.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Samsung M262x/M282x Xpress Series Laser Printer | 2        | 5.71%   |
| Seiko Epson XP-243 245 247 Series               | 1        | 2.86%   |
| Seiko Epson XP-235 Series                       | 1        | 2.86%   |
| Seiko Epson L1300 Series                        | 1        | 2.86%   |
| Seiko Epson ET-2720 Series                      | 1        | 2.86%   |
| Seiko Epson ET-2710 Series                      | 1        | 2.86%   |
| Samsung SCX-4200 series                         | 1        | 2.86%   |
| Samsung SCX-3400 Series                         | 1        | 2.86%   |
| Samsung ML-1865                                 | 1        | 2.86%   |
| Samsung M267x 287x Series                       | 1        | 2.86%   |
| Samsung M2020 Series                            | 1        | 2.86%   |
| Prolific PL2305 Parallel Port                   | 1        | 2.86%   |
| Kyocera FS-1030D printer                        | 1        | 2.86%   |
| HP Smart Tank Plus 550 series                   | 1        | 2.86%   |
| HP OfficeJet 5200 series                        | 1        | 2.86%   |
| HP Officejet 4620 series                        | 1        | 2.86%   |
| HP LaserJet Professional P1606dn                | 1        | 2.86%   |
| HP LaserJet Professional P 1102w                | 1        | 2.86%   |
| HP LaserJet P1102                               | 1        | 2.86%   |
| HP LaserJet 1320                                | 1        | 2.86%   |
| HP LaserJet 1018                                | 1        | 2.86%   |
| HP ENVY 4520 series                             | 1        | 2.86%   |
| HP ENVY 4500 series                             | 1        | 2.86%   |
| HP DeskJet 6940 series                          | 1        | 2.86%   |
| HP DeskJet 5940                                 | 1        | 2.86%   |
| HP DeskJet 3630 series                          | 1        | 2.86%   |
| HP DeskJet 2620 All-in-One Printer              | 1        | 2.86%   |
| Canon CanoScan LiDE 300                         | 1        | 2.86%   |
| Brother Printer                                 | 1        | 2.86%   |
| Brother MFC-7360N                               | 1        | 2.86%   |
| Brother HL-L3290CDW                             | 1        | 2.86%   |
| Brother HL-L3210CW series                       | 1        | 2.86%   |
| Brother HL-4150CDN series                       | 1        | 2.86%   |
| Brother HL-2240D series                         | 1        | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 5        | 38.46%  |
| Seiko Epson     | 3        | 23.08%  |
| Hewlett-Packard | 2        | 15.38%  |
| AGFA-Gevaert NV | 2        | 15.38%  |
| Mustek Systems  | 1        | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                             | 2        | 15.38%  |
| Seiko Epson Scanner                                 | 1        | 7.69%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1        | 7.69%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1        | 7.69%   |
| Mustek Systems ScanExpress A3 USB                   | 1        | 7.69%   |
| HP ScanJet 5300c/5370c                              | 1        | 7.69%   |
| HP ScanJet 3970c                                    | 1        | 7.69%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1        | 7.69%   |
| Canon CanoScan N1240U/LiDE 30                       | 1        | 7.69%   |
| Canon CanoScan LiDE 110                             | 1        | 7.69%   |
| AGFA-Gevaert NV SnapScan e20                        | 1        | 7.69%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                  | 1        | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 56       | 52.34%  |
| Microdia                      | 10       | 9.35%   |
| Microsoft                     | 8        | 7.48%   |
| Samsung Electronics           | 4        | 3.74%   |
| Z-Star Microelectronics       | 3        | 2.8%    |
| Chicony Electronics           | 3        | 2.8%    |
| Trust                         | 2        | 1.87%   |
| Generalplus Technology        | 2        | 1.87%   |
| Arkmicro Technologies         | 2        | 1.87%   |
| Unknown                       | 1        | 0.93%   |
| Sweex                         | 1        | 0.93%   |
| Sunplus Innovation Technology | 1        | 0.93%   |
| Sonix Technology              | 1        | 0.93%   |
| Realtek Semiconductor         | 1        | 0.93%   |
| Quanta                        | 1        | 0.93%   |
| Philips (or NXP)              | 1        | 0.93%   |
| lihappe8                      | 1        | 0.93%   |
| IPEVO                         | 1        | 0.93%   |
| HTC (High Tech Computer)      | 1        | 0.93%   |
| Hewlett-Packard               | 1        | 0.93%   |
| Guillemot                     | 1        | 0.93%   |
| Cubeternet                    | 1        | 0.93%   |
| Creative Technology           | 1        | 0.93%   |
| AVerMedia Technologies        | 1        | 0.93%   |
| ARC International             | 1        | 0.93%   |
| Apple                         | 1        | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 19       | 17.76%  |
| Logitech HD Pro Webcam C920             | 6        | 5.61%   |
| Logitech C922 Pro Stream Webcam         | 6        | 5.61%   |
| Logitech Webcam C310                    | 5        | 4.67%   |
| Samsung Galaxy A5 (MTP)                 | 4        | 3.74%   |
| Microdia Webcam Vitade AF               | 3        | 2.8%    |
| Microdia USB 2.0 Camera                 | 3        | 2.8%    |
| Microdia Sonix USB 2.0 Camera           | 3        | 2.8%    |
| Logitech HD Webcam C525                 | 3        | 2.8%    |
| Logitech B525 HD Webcam                 | 3        | 2.8%    |
| Z-Star Venus USB2.0 Camera              | 2        | 1.87%   |
| Microsoft MicrosoftÃ‚ LifeCam Cinema | 2        | 1.87%   |
| Microsoft LifeCam VX-800                | 2        | 1.87%   |
| Logitech Webcam C925e                   | 2        | 1.87%   |
| Logitech Webcam C250                    | 2        | 1.87%   |
| Logitech HD Webcam C615                 | 2        | 1.87%   |
| Logitech BRIO                           | 2        | 1.87%   |
| Chicony HP Webcam                       | 2        | 1.87%   |
| Arkmicro USB2.0 PC CAMERA               | 2        | 1.87%   |
| Z-Star Vimicro USB Camera (Altair)      | 1        | 0.93%   |
| Unknown ET13R                           | 1        | 0.93%   |
| Trust Widescreen 3MP Webcam             | 1        | 0.93%   |
| Trust USB Camera                        | 1        | 0.93%   |
| Sweex WC060 Series HD Webcam            | 1        | 0.93%   |
| Sunplus UHD Capture                     | 1        | 0.93%   |
| Sonix GENERAL WEBCAM                    | 1        | 0.93%   |
| Realtek NexiGo N960E FHD Webcam         | 1        | 0.93%   |
| Quanta Astro HD Camera                  | 1        | 0.93%   |
| Philips (or NXP) SPC 1000NC PC Camera   | 1        | 0.93%   |
| Microsoft LifeCam VX-700                | 1        | 0.93%   |
| Microsoft LifeCam VX-500 [1357]         | 1        | 0.93%   |
| Microsoft LifeCam VX-2000               | 1        | 0.93%   |
| Microsoft LifeCam HD-3000               | 1        | 0.93%   |
| Microdia Camera                         | 1        | 0.93%   |
| Logitech Webcam Pro 9000                | 1        | 0.93%   |
| Logitech StreamCam                      | 1        | 0.93%   |
| Logitech QuickCam Pro 5000              | 1        | 0.93%   |
| Logitech QuickCam Express               | 1        | 0.93%   |
| Logitech HD Webcam C510                 | 1        | 0.93%   |
| Logitech C505 HD Webcam                 | 1        | 0.93%   |
| lihappe8 USB 2.0 Camera                 | 1        | 0.93%   |
| IPEVO Point 2 View                      | 1        | 0.93%   |
| HTC (High Tech Computer) VIVE COSMOS    | 1        | 0.93%   |
| HP Webcam 3110                          | 1        | 0.93%   |
| Guillemot USB Camera                    | 1        | 0.93%   |
| Generalplus GENERAL WEBCAM              | 1        | 0.93%   |
| Generalplus 2K HD Camera                | 1        | 0.93%   |
| Cubeternet USB2.0 Camera                | 1        | 0.93%   |
| Creative Live! Cam Sync 1080p           | 1        | 0.93%   |
| Chicony HP Deluxe Webcam KQ246AA        | 1        | 0.93%   |
| AVerMedia Live Streamer CAM 315         | 1        | 0.93%   |
| ARC International Camera                | 1        | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE               | 1        | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 2        | 28.57%  |
| Gemalto (was Gemplus) | 2        | 28.57%  |
| Yubico.com            | 1        | 14.29%  |
| Watchdata             | 1        | 14.29%  |
| Clay Logic            | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Hewlett-Packard SC Keyboard - Apollo (Liteon)     | 2        | 28.57%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 28.57%  |
| Yubico.com Yubikey 4/5 U2F+CCID                   | 1        | 14.29%  |
| Watchdata USB Key                                 | 1        | 14.29%  |
| Clay Logic Nitrokey HSM                           | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 457      | 86.06%  |
| 1     | 59       | 11.11%  |
| 2     | 9        | 1.69%   |
| 3     | 5        | 0.94%   |
| 5     | 1        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 26       | 30.59%  |
| Net/wireless             | 20       | 23.53%  |
| Unassigned class         | 11       | 12.94%  |
| Sound                    | 5        | 5.88%   |
| Card reader              | 5        | 5.88%   |
| Communication controller | 3        | 3.53%   |
| Chipcard                 | 3        | 3.53%   |
| Network                  | 2        | 2.35%   |
| Multimedia controller    | 2        | 2.35%   |
| Firewire controller      | 2        | 2.35%   |
| Fingerprint reader       | 2        | 2.35%   |
| Camera                   | 2        | 2.35%   |
| Net/ethernet             | 1        | 1.18%   |
| Bluetooth                | 1        | 1.18%   |

