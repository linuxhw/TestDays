Kubuntu 23.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

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

Total: 152

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8Z68-V                     | [4a20d22dd5](https://linux-hardware.org/?probe=4a20d22dd5) | Nov 11, 2024 |
| ASUSTek       | P8Z68-V                     | [014f995cb5](https://linux-hardware.org/?probe=014f995cb5) | Nov 11, 2024 |
| ASUSTek       | P8Z68-V                     | [164a29cfe9](https://linux-hardware.org/?probe=164a29cfe9) | Nov 10, 2024 |
| ASUSTek       | CROSSBLADE RANGER           | [ec49fe4be2](https://linux-hardware.org/?probe=ec49fe4be2) | May 10, 2024 |
| ASRock        | X370 Gaming-ITX/ac          | [af9215d3a5](https://linux-hardware.org/?probe=af9215d3a5) | Jan 23, 2024 |
| Unknown       | AY07J                       | [1cb5749c2b](https://linux-hardware.org/?probe=1cb5749c2b) | Jan 13, 2024 |
| Gigabyte      | B550M DS3H                  | [bf4f14e416](https://linux-hardware.org/?probe=bf4f14e416) | Dec 30, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [0a531cbda1](https://linux-hardware.org/?probe=0a531cbda1) | Dec 12, 2023 |
| ASUSTek       | M4A88TD-M EVO               | [2fcc002511](https://linux-hardware.org/?probe=2fcc002511) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [d91c0b4b6f](https://linux-hardware.org/?probe=d91c0b4b6f) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [493dcbc1f8](https://linux-hardware.org/?probe=493dcbc1f8) | Nov 01, 2023 |
| ASUSTek       | BT1AD                       | [133784e5ee](https://linux-hardware.org/?probe=133784e5ee) | Oct 31, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [fe3816864f](https://linux-hardware.org/?probe=fe3816864f) | Oct 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [5d7ab82de7](https://linux-hardware.org/?probe=5d7ab82de7) | Oct 30, 2023 |
| ASUSTek       | M4A89GTD-PRO                | [b160015184](https://linux-hardware.org/?probe=b160015184) | Oct 29, 2023 |
| HP            | 1790                        | [8bde9984db](https://linux-hardware.org/?probe=8bde9984db) | Oct 29, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [67564f88a0](https://linux-hardware.org/?probe=67564f88a0) | Oct 24, 2023 |
| Colorful T... | BATTLE-AX B450M-HD V14      | [314500a8ed](https://linux-hardware.org/?probe=314500a8ed) | Oct 23, 2023 |
| Dell          | 0XR1GT A00                  | [33b1df369f](https://linux-hardware.org/?probe=33b1df369f) | Oct 21, 2023 |
| MSI           | MAG B560M MORTAR            | [a7f26cedd6](https://linux-hardware.org/?probe=a7f26cedd6) | Oct 20, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | [0c25658c6d](https://linux-hardware.org/?probe=0c25658c6d) | Oct 18, 2023 |
| ASRock        | B560M Pro4                  | [77690da2b6](https://linux-hardware.org/?probe=77690da2b6) | Oct 17, 2023 |
| Gigabyte      | GA-970A-DS3                 | [86d888a421](https://linux-hardware.org/?probe=86d888a421) | Oct 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [bc33324b0d](https://linux-hardware.org/?probe=bc33324b0d) | Oct 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | [09d2bdba5b](https://linux-hardware.org/?probe=09d2bdba5b) | Oct 12, 2023 |
| ASRock        | X79 Extreme9                | [4a0805a07a](https://linux-hardware.org/?probe=4a0805a07a) | Oct 11, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [364af80964](https://linux-hardware.org/?probe=364af80964) | Oct 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c5a3a209c0](https://linux-hardware.org/?probe=c5a3a209c0) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c35ab8ae2e](https://linux-hardware.org/?probe=c35ab8ae2e) | Oct 05, 2023 |
| ASUSTek       | Z97-K                       | [8892c7239e](https://linux-hardware.org/?probe=8892c7239e) | Oct 03, 2023 |
| Dell          | 0X8DXD A00                  | [a44e0088f6](https://linux-hardware.org/?probe=a44e0088f6) | Oct 01, 2023 |
| HP            | 1790                        | [b87e9dd9ad](https://linux-hardware.org/?probe=b87e9dd9ad) | Sep 29, 2023 |
| HP            | 1790                        | [89791e7bf0](https://linux-hardware.org/?probe=89791e7bf0) | Sep 29, 2023 |
| MSI           | H97M-G43                    | [b74346acb3](https://linux-hardware.org/?probe=b74346acb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | [76937ddbce](https://linux-hardware.org/?probe=76937ddbce) | Sep 28, 2023 |
| Unknown       | Unknown                     | [128658b9f0](https://linux-hardware.org/?probe=128658b9f0) | Sep 26, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [7f88191a7b](https://linux-hardware.org/?probe=7f88191a7b) | Sep 23, 2023 |
| ASRock        | H87 Pro4                    | [dc831a82cd](https://linux-hardware.org/?probe=dc831a82cd) | Sep 22, 2023 |
| Gigabyte      | GA-970A-DS3                 | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| ASUSTek       | Maximus IX FORMULA          | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-A               | [17e0d2ab92](https://linux-hardware.org/?probe=17e0d2ab92) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P                | [76d6f570a8](https://linux-hardware.org/?probe=76d6f570a8) | Sep 16, 2023 |
| ASRock        | B650M PG Riptide            | [3a1c100a69](https://linux-hardware.org/?probe=3a1c100a69) | Sep 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [959fc9f783](https://linux-hardware.org/?probe=959fc9f783) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [641089b224](https://linux-hardware.org/?probe=641089b224) | Sep 13, 2023 |
| AZW           | MINI S 10                   | [5cd0efea8b](https://linux-hardware.org/?probe=5cd0efea8b) | Sep 12, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [b12897892a](https://linux-hardware.org/?probe=b12897892a) | Sep 09, 2023 |
| MSI           | B360M BAZOOKA               | [33cc2ca68e](https://linux-hardware.org/?probe=33cc2ca68e) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f081f44bda](https://linux-hardware.org/?probe=f081f44bda) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [71da9ea288](https://linux-hardware.org/?probe=71da9ea288) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [31cb6a887e](https://linux-hardware.org/?probe=31cb6a887e) | Sep 04, 2023 |
| MSI           | MAG B560M MORTAR            | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Dell          | 0XPDFK A01                  | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| MSI           | MAG B550M BAZOOKA           | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| MSI           | B550-A PRO                  | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| ASRock        | X570 Steel Legend           | [65b6b29fc7](https://linux-hardware.org/?probe=65b6b29fc7) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| ASRock        | X570 Steel Legend           | [7bd62bca50](https://linux-hardware.org/?probe=7bd62bca50) | Aug 23, 2023 |
| Intel         | H55                         | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c78c246642](https://linux-hardware.org/?probe=c78c246642) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASRock        | X370 Taichi                 | [9a7f33c81b](https://linux-hardware.org/?probe=9a7f33c81b) | Aug 20, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [b5973b3c67](https://linux-hardware.org/?probe=b5973b3c67) | Aug 18, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| ASRock        | X370 Taichi                 | [e338ac8876](https://linux-hardware.org/?probe=e338ac8876) | Aug 14, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [0c8514df53](https://linux-hardware.org/?probe=0c8514df53) | Aug 13, 2023 |
| Dell          | 0HY9JP A00                  | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-K                | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| HP            | 158A                        | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| HP            | 158A                        | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| Google        | Zako                        | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Acer          | Aspire X3990                | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| ASRock        | B560M Pro4                  | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | 83E9                        | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| Gigabyte      | X570S UD                    | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| MSI           | B360M MORTAR TITANIUM       | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | PRIME H510M-K               | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| Gigabyte      | B550 AORUS PRO              | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Gigabyte      | X570S UD                    | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Intel         | SHARKBAY                    | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| MSI           | H81M-P32                    | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | Maximus IX HERO             | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| ASRock        | A320M-HDV R4.0              | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| ASUSTek       | PRIME H610M-E D4            | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| Seco          | C40 C                       | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| ASUSTek       | H81M-A                      | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| MSI           | B450M PRO-M2 V2             | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| ASUSTek       | H81M-A                      | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Alienware     | 04VWF2 A00                  | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| ASRock        | X99 Extreme6/ac             | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Alienware     | 04VWF2 A00                  | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | 3397                        | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Intel         | H61                         | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| Biostar       | AM1MHP                      | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Gigabyte      | H87-HD3                     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| HP            | 828A                        | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Unknown       | Unknown                     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Gigabyte      | B360M HD3                   | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 6.2.0-20-generic       | 18       | 14.63%  |
| 6.2.0-27-generic       | 14       | 11.38%  |
| 6.2.0-34-generic       | 12       | 9.76%   |
| 6.2.0-32-generic       | 9        | 7.32%   |
| 6.2.0-33-generic       | 8        | 6.5%    |
| 6.2.0-24-generic       | 8        | 6.5%    |
| 6.2.0-26-generic       | 6        | 4.88%   |
| 6.2.0-23-generic       | 6        | 4.88%   |
| 6.2.0-25-generic       | 5        | 4.07%   |
| 6.2.0-36-generic       | 4        | 3.25%   |
| 6.2.0-31-generic       | 4        | 3.25%   |
| 6.2.0-39-generic       | 3        | 2.44%   |
| 6.2.0-1003-lowlatency  | 3        | 2.44%   |
| 6.2.0-35-generic       | 2        | 1.63%   |
| 6.2.0-1013-lowlatency  | 2        | 1.63%   |
| 6.5.1-060501-generic   | 1        | 0.81%   |
| 6.4.6-060406-generic   | 1        | 0.81%   |
| 6.4.3-1-liquorix-amd64 | 1        | 0.81%   |
| 6.4.1-2-liquorix-amd64 | 1        | 0.81%   |
| 6.4.0-060400-generic   | 1        | 0.81%   |
| 6.3.5-060305-generic   | 1        | 0.81%   |
| 6.3.10                 | 1        | 0.81%   |
| 6.2.5-060205-generic   | 1        | 0.81%   |
| 6.2.0-1018-lowlatency  | 1        | 0.81%   |
| 6.2.0-1015-lowlatency  | 1        | 0.81%   |
| 6.2.0-1014-lowlatency  | 1        | 0.81%   |
| 6.2.0-1009-lowlatency  | 1        | 0.81%   |
| 6.2.0-1008-lowlatency  | 1        | 0.81%   |
| 6.2.0-1007-lowlatency  | 1        | 0.81%   |
| 6.1.0-16-generic       | 1        | 0.81%   |
| 5.19.0-42-generic      | 1        | 0.81%   |
| 5.19.0-28-generic      | 1        | 0.81%   |
| 5.19.0-1023-lowlatency | 1        | 0.81%   |
| 5.15.0-86-generic      | 1        | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 106      | 89.08%  |
| 5.19.0  | 3        | 2.52%   |
| 6.5.1   | 1        | 0.84%   |
| 6.4.6   | 1        | 0.84%   |
| 6.4.3   | 1        | 0.84%   |
| 6.4.1   | 1        | 0.84%   |
| 6.4.0   | 1        | 0.84%   |
| 6.3.5   | 1        | 0.84%   |
| 6.3.10  | 1        | 0.84%   |
| 6.2.5   | 1        | 0.84%   |
| 6.1.0   | 1        | 0.84%   |
| 5.15.0  | 1        | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 107      | 89.92%  |
| 6.4     | 4        | 3.36%   |
| 5.19    | 3        | 2.52%   |
| 6.3     | 2        | 1.68%   |
| 6.5     | 1        | 0.84%   |
| 6.1     | 1        | 0.84%   |
| 5.15    | 1        | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 117      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 114      | 97.44%  |
| KDE  | 3        | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 100      | 84.75%  |
| Wayland | 17       | 14.41%  |
| Tty     | 1        | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 73       | 61.86%  |
| Unknown | 41       | 34.75%  |
| LightDM | 2        | 1.69%   |
| GDM3    | 2        | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 52       | 44.07%  |
| de_DE | 14       | 11.86%  |
| en_GB | 9        | 7.63%   |
| it_IT | 8        | 6.78%   |
| fr_FR | 8        | 6.78%   |
| ru_RU | 5        | 4.24%   |
| pt_BR | 4        | 3.39%   |
| sv_SE | 2        | 1.69%   |
| pl_PL | 2        | 1.69%   |
| en_CA | 2        | 1.69%   |
| C     | 2        | 1.69%   |
| zh_TW | 1        | 0.85%   |
| fr_BE | 1        | 0.85%   |
| es_MX | 1        | 0.85%   |
| es_ES | 1        | 0.85%   |
| es_CO | 1        | 0.85%   |
| es_CL | 1        | 0.85%   |
| en_IN | 1        | 0.85%   |
| en_IL | 1        | 0.85%   |
| de_CH | 1        | 0.85%   |
| da_DK | 1        | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 69       | 58.47%  |
| EFI  | 49       | 41.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 83       | 70.94%  |
| Tmpfs   | 22       | 18.8%   |
| Btrfs   | 8        | 6.84%   |
| Overlay | 2        | 1.71%   |
| Xfs     | 1        | 0.85%   |
| F2fs    | 1        | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 70       | 59.32%  |
| Unknown | 40       | 33.9%   |
| MBR     | 8        | 6.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 75.21%  |
| Yes       | 29       | 24.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 64.96%  |
| Yes       | 41       | 35.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 40       | 34.19%  |
| Gigabyte Technology | 20       | 17.09%  |
| MSI                 | 17       | 14.53%  |
| ASRock              | 10       | 8.55%   |
| Hewlett-Packard     | 4        | 3.42%   |
| Dell                | 4        | 3.42%   |
| Intel               | 3        | 2.56%   |
| Unknown             | 3        | 2.56%   |
| Lenovo              | 2        | 1.71%   |
| Fujitsu             | 2        | 1.71%   |
| Seco                | 1        | 0.85%   |
| Pegatron            | 1        | 0.85%   |
| Huanan              | 1        | 0.85%   |
| Google              | 1        | 0.85%   |
| Gateway             | 1        | 0.85%   |
| Foxconn             | 1        | 0.85%   |
| Colorful Technology | 1        | 0.85%   |
| Biostar             | 1        | 0.85%   |
| BESSTAR Tech        | 1        | 0.85%   |
| AZW                 | 1        | 0.85%   |
| Alienware           | 1        | 0.85%   |
| Acer                | 1        | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Unknown                                     | 3        | 2.56%   |
| MSI MS-7D75                                 | 2        | 1.71%   |
| MSI MS-7C95                                 | 2        | 1.71%   |
| MSI MS-7C56                                 | 2        | 1.71%   |
| MSI MS-7B86                                 | 2        | 1.71%   |
| Gigabyte B550 AORUS ELITE V2                | 2        | 1.71%   |
| ASUS TUF Gaming B550-PLUS                   | 2        | 1.71%   |
| ASUS ROG STRIX B550-F GAMING                | 2        | 1.71%   |
| ASUS All Series                             | 2        | 1.71%   |
| Seco C40                                    | 1        | 0.85%   |
| Pegatron 520-1000nl                         | 1        | 0.85%   |
| MSI MS-7D74                                 | 1        | 0.85%   |
| MSI MS-7D17                                 | 1        | 0.85%   |
| MSI MS-7C37                                 | 1        | 0.85%   |
| MSI MS-7B24                                 | 1        | 0.85%   |
| MSI MS-7B23                                 | 1        | 0.85%   |
| MSI MS-7A32                                 | 1        | 0.85%   |
| MSI MS-7924                                 | 1        | 0.85%   |
| MSI MS-7846                                 | 1        | 0.85%   |
| MSI MS-7693                                 | 1        | 0.85%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T100BHMZ | 1        | 0.85%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS      | 1        | 0.85%   |
| Intel SHARKBAY                              | 1        | 0.85%   |
| Intel H61                                   | 1        | 0.85%   |
| Intel H55                                   | 1        | 0.85%   |
| Huanan X99-F8 GAMING V5.0                   | 1        | 0.85%   |
| HP Z220 CMT Workstation                     | 1        | 0.85%   |
| HP EliteDesk 705 G4 DM 35W (TAA)            | 1        | 0.85%   |
| HP Compaq Elite 8300 SFF                    | 1        | 0.85%   |
| HP 870-119                                  | 1        | 0.85%   |
| Google Zako                                 | 1        | 0.85%   |
| Gigabyte Z390 M GAMING                      | 1        | 0.85%   |
| Gigabyte Z390 GAMING X                      | 1        | 0.85%   |
| Gigabyte Z370P D3                           | 1        | 0.85%   |
| Gigabyte X570S UD                           | 1        | 0.85%   |
| Gigabyte X570S AORUS ELITE AX               | 1        | 0.85%   |
| Gigabyte X470 AORUS ULTRA GAMING            | 1        | 0.85%   |
| Gigabyte H87-HD3                            | 1        | 0.85%   |
| Gigabyte GA-MA770-US3                       | 1        | 0.85%   |
| Gigabyte GA-970A-DS3                        | 1        | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 14       | 11.97%  |
| ASUS ROG            | 7        | 5.98%   |
| ASUS TUF            | 6        | 5.13%   |
| Gigabyte B550       | 4        | 3.42%   |
| Unknown             | 3        | 2.56%   |
| MSI MS-7D75         | 2        | 1.71%   |
| MSI MS-7C95         | 2        | 1.71%   |
| MSI MS-7C56         | 2        | 1.71%   |
| MSI MS-7B86         | 2        | 1.71%   |
| Lenovo IdeaCentre   | 2        | 1.71%   |
| Gigabyte Z390       | 2        | 1.71%   |
| Gigabyte X570S      | 2        | 1.71%   |
| Gigabyte B365M      | 2        | 1.71%   |
| Dell Precision      | 2        | 1.71%   |
| ASUS P8Z68-V        | 2        | 1.71%   |
| ASUS Maximus        | 2        | 1.71%   |
| ASUS All            | 2        | 1.71%   |
| ASRock X370         | 2        | 1.71%   |
| Seco C40            | 1        | 0.85%   |
| Pegatron 520-1000nl | 1        | 0.85%   |
| MSI MS-7D74         | 1        | 0.85%   |
| MSI MS-7D17         | 1        | 0.85%   |
| MSI MS-7C37         | 1        | 0.85%   |
| MSI MS-7B24         | 1        | 0.85%   |
| MSI MS-7B23         | 1        | 0.85%   |
| MSI MS-7A32         | 1        | 0.85%   |
| MSI MS-7924         | 1        | 0.85%   |
| MSI MS-7846         | 1        | 0.85%   |
| MSI MS-7693         | 1        | 0.85%   |
| Intel SHARKBAY      | 1        | 0.85%   |
| Intel H61           | 1        | 0.85%   |
| Intel H55           | 1        | 0.85%   |
| Huanan X99-F8       | 1        | 0.85%   |
| HP Z220             | 1        | 0.85%   |
| HP EliteDesk        | 1        | 0.85%   |
| HP Compaq           | 1        | 0.85%   |
| HP 870-119          | 1        | 0.85%   |
| Google Zako         | 1        | 0.85%   |
| Gigabyte Z370P      | 1        | 0.85%   |
| Gigabyte X470       | 1        | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 19       | 16.24%  |
| 2019 | 17       | 14.53%  |
| 2018 | 15       | 12.82%  |
| 2022 | 12       | 10.26%  |
| 2021 | 10       | 8.55%   |
| 2017 | 8        | 6.84%   |
| 2011 | 8        | 6.84%   |
| 2012 | 7        | 5.98%   |
| 2014 | 6        | 5.13%   |
| 2013 | 4        | 3.42%   |
| 2016 | 3        | 2.56%   |
| 2010 | 3        | 2.56%   |
| 2023 | 2        | 1.71%   |
| 2009 | 2        | 1.71%   |
| 2015 | 1        | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 117      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 115      | 98.29%  |
| Enabled  | 2        | 1.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 116      | 99.15%  |
| Yes  | 1        | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 32       | 27.35%  |
| 32.01-64.0  | 31       | 26.5%   |
| 8.01-16.0   | 18       | 15.38%  |
| 4.01-8.0    | 16       | 13.68%  |
| 24.01-32.0  | 8        | 6.84%   |
| 64.01-256.0 | 8        | 6.84%   |
| 3.01-4.0    | 4        | 3.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 40       | 32.26%  |
| 3.01-4.0   | 27       | 21.77%  |
| 2.01-3.0   | 26       | 20.97%  |
| 1.01-2.0   | 17       | 13.71%  |
| 8.01-16.0  | 11       | 8.87%   |
| 16.01-24.0 | 3        | 2.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 26.27%  |
| 1      | 27       | 22.88%  |
| 3      | 25       | 21.19%  |
| 4      | 20       | 16.95%  |
| 5      | 7        | 5.93%   |
| 6      | 4        | 3.39%   |
| 8      | 2        | 1.69%   |
| 7      | 2        | 1.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 63.56%  |
| Yes       | 43       | 36.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 116      | 99.15%  |
| No        | 1        | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 57.26%  |
| Yes       | 50       | 42.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 58.97%  |
| Yes       | 48       | 41.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 25       | 21.37%  |
| Germany      | 17       | 14.53%  |
| UK           | 10       | 8.55%   |
| France       | 9        | 7.69%   |
| Italy        | 7        | 5.98%   |
| Russia       | 6        | 5.13%   |
| Canada       | 5        | 4.27%   |
| Switzerland  | 4        | 3.42%   |
| Sweden       | 4        | 3.42%   |
| Poland       | 4        | 3.42%   |
| Brazil       | 4        | 3.42%   |
| Turkey       | 2        | 1.71%   |
| Spain        | 2        | 1.71%   |
| Serbia       | 2        | 1.71%   |
| Netherlands  | 2        | 1.71%   |
| Taiwan       | 1        | 0.85%   |
| Saudi Arabia | 1        | 0.85%   |
| Romania      | 1        | 0.85%   |
| Portugal     | 1        | 0.85%   |
| Mexico       | 1        | 0.85%   |
| Kazakhstan   | 1        | 0.85%   |
| Israel       | 1        | 0.85%   |
| Indonesia    | 1        | 0.85%   |
| India        | 1        | 0.85%   |
| Denmark      | 1        | 0.85%   |
| Colombia     | 1        | 0.85%   |
| Chile        | 1        | 0.85%   |
| Belgium      | 1        | 0.85%   |
| Bangladesh   | 1        | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| London               | 3        | 2.52%   |
| Virginia Beach       | 2        | 1.68%   |
| Oberburg             | 2        | 1.68%   |
| Hamburg              | 2        | 1.68%   |
| Frankfurt am Main    | 2        | 1.68%   |
| Florence             | 2        | 1.68%   |
| Arzamas              | 2        | 1.68%   |
| Zuchwil              | 1        | 0.84%   |
| Wiesmoor             | 1        | 0.84%   |
| West Valley          | 1        | 0.84%   |
| Wellsboro            | 1        | 0.84%   |
| Weilmuenster         | 1        | 0.84%   |
| Warsaw               | 1        | 0.84%   |
| Victoria             | 1        | 0.84%   |
| Vaggeryd             | 1        | 0.84%   |
| Ufa                  | 1        | 0.84%   |
| Uelversheim          | 1        | 0.84%   |
| Tilburg              | 1        | 0.84%   |
| The Hague            | 1        | 0.84%   |
| Taichung             | 1        | 0.84%   |
| Sutton               | 1        | 0.84%   |
| Sundsvall            | 1        | 0.84%   |
| Strasbourg           | 1        | 0.84%   |
| Stone Mountain       | 1        | 0.84%   |
| Simpsonville         | 1        | 0.84%   |
| Sibiu                | 1        | 0.84%   |
| Sherbrooke           | 1        | 0.84%   |
| Saskatoon            | 1        | 0.84%   |
| Saro                 | 1        | 0.84%   |
| Sao Paulo            | 1        | 0.84%   |
| Santo André         | 1        | 0.84%   |
| Santiago             | 1        | 0.84%   |
| San Jose             | 1        | 0.84%   |
| San Francisco        | 1        | 0.84%   |
| San Cesario di Lecce | 1        | 0.84%   |
| Rzeszów             | 1        | 0.84%   |
| Riverview            | 1        | 0.84%   |
| Rho                  | 1        | 0.84%   |
| Porto Alegre         | 1        | 0.84%   |
| Portimao             | 1        | 0.84%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 41       | 66     | 15.65%  |
| Seagate                     | 39       | 66     | 14.89%  |
| WDC                         | 37       | 49     | 14.12%  |
| Sandisk                     | 22       | 26     | 8.4%    |
| Crucial                     | 14       | 17     | 5.34%   |
| Kingston                    | 13       | 18     | 4.96%   |
| Toshiba                     | 11       | 13     | 4.2%    |
| Hitachi                     | 6        | 6      | 2.29%   |
| Phison Electronics          | 5        | 5      | 1.91%   |
| Kingston Technology Company | 5        | 8      | 1.91%   |
| HGST                        | 5        | 6      | 1.91%   |
| A-DATA Technology           | 5        | 6      | 1.91%   |
| Intel                       | 4        | 5      | 1.53%   |
| SPCC                        | 3        | 7      | 1.15%   |
| Silicon Motion              | 3        | 4      | 1.15%   |
| PNY                         | 3        | 3      | 1.15%   |
| Patriot                     | 3        | 3      | 1.15%   |
| Maxtor                      | 3        | 3      | 1.15%   |
| Unknown                     | 2        | 2      | 0.76%   |
| Micron/Crucial Technology   | 2        | 4      | 0.76%   |
| Intenso                     | 2        | 3      | 0.76%   |
| Hewlett-Packard             | 2        | 3      | 0.76%   |
| Corsair                     | 2        | 2      | 0.76%   |
| China                       | 2        | 2      | 0.76%   |
| ADATA Technology            | 2        | 2      | 0.76%   |
| Unknown                     | 2        | 2      | 0.76%   |
| Vaseky                      | 1        | 1      | 0.38%   |
| Transcend                   | 1        | 1      | 0.38%   |
| Team                        | 1        | 1      | 0.38%   |
| SSI                         | 1        | 1      | 0.38%   |
| Smartbuy                    | 1        | 1      | 0.38%   |
| S3+                         | 1        | 1      | 0.38%   |
| Realtek Semiconductor       | 1        | 1      | 0.38%   |
| Plextor                     | 1        | 1      | 0.38%   |
| PHD 3.0                     | 1        | 1      | 0.38%   |
| OCZ                         | 1        | 1      | 0.38%   |
| Neo                         | 1        | 1      | 0.38%   |
| Micron Technology           | 1        | 1      | 0.38%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.38%   |
| Lexar                       | 1        | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                       | 7        | 2.22%   |
| Seagate ST4000DM004-2CV104 4TB                       | 5        | 1.59%   |
| Samsung SSD 860 EVO 500GB                            | 5        | 1.59%   |
| Seagate ST2000DM001-1ER164 2TB                       | 4        | 1.27%   |
| Samsung SSD 850 EVO 250GB                            | 4        | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 4        | 1.27%   |
| Seagate ST1000DM003-1ER162 1TB                       | 3        | 0.95%   |
| Seagate ST1000DM003-1CH162 1TB                       | 3        | 0.95%   |
| SanDisk SSD PLUS 1000GB                              | 3        | 0.95%   |
| SanDisk NVMe SSD Drive 1TB                           | 3        | 0.95%   |
| Samsung SSD 980 1TB                                  | 3        | 0.95%   |
| Phison PS5013 E13 NVMe Controller 512GB              | 3        | 0.95%   |
| Kingston SA400S37480G 480GB SSD                      | 3        | 0.95%   |
| Crucial CT250MX500SSD1 250GB                         | 3        | 0.95%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 2        | 0.63%   |
| WDC WD5000AAKX-60U6AA0 500GB                         | 2        | 0.63%   |
| WDC WD10EZEX-60WN4A0 1TB                             | 2        | 0.63%   |
| Toshiba DT01ACA100 1TB                               | 2        | 0.63%   |
| Seagate ST31000528AS 1TB                             | 2        | 0.63%   |
| Seagate ST2000DM001-1CH164 2TB                       | 2        | 0.63%   |
| Sandisk WD_BLACK SN850X 4000GB                       | 2        | 0.63%   |
| Sandisk WD_BLACK SN770 1TB                           | 2        | 0.63%   |
| Sandisk WD Black SN850 2TB                           | 2        | 0.63%   |
| Samsung SSD 980 PRO 2TB                              | 2        | 0.63%   |
| Samsung SSD 980 PRO 1TB                              | 2        | 0.63%   |
| Samsung SSD 970 EVO Plus 500GB                       | 2        | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB                         | 2        | 0.63%   |
| Samsung SSD 870 QVO 2TB                              | 2        | 0.63%   |
| Samsung SSD 860 EVO 1TB                              | 2        | 0.63%   |
| Samsung SSD 850 PRO 512GB                            | 2        | 0.63%   |
| Samsung SSD 850 PRO 256GB                            | 2        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 2        | 0.63%   |
| Samsung HD103SI 1TB                                  | 2        | 0.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 2        | 0.63%   |
| Kingston Company SNV2S1000G 1TB                      | 2        | 0.63%   |
| Kingston Company A2000 NVMe SSD 500GB                | 2        | 0.63%   |
| Kingston SA400S37240G 240GB SSD                      | 2        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                      | 2        | 0.63%   |
| Kingston SA400M8240G 240GB SSD                       | 2        | 0.63%   |
| Hitachi HDP725050GLA360 500GB                        | 2        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 63     | 37.37%  |
| WDC                 | 28       | 37     | 28.28%  |
| Toshiba             | 11       | 12     | 11.11%  |
| Hitachi             | 6        | 6      | 6.06%   |
| Samsung Electronics | 5        | 5      | 5.05%   |
| HGST                | 5        | 6      | 5.05%   |
| Maxtor              | 3        | 3      | 3.03%   |
| Unknown             | 1        | 1      | 1.01%   |
| SSI                 | 1        | 1      | 1.01%   |
| JMicron Technology  | 1        | 1      | 1.01%   |
| Apple               | 1        | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 35     | 24%     |
| Kingston            | 12       | 17     | 12%     |
| SanDisk             | 10       | 13     | 10%     |
| Crucial             | 10       | 12     | 10%     |
| WDC                 | 8        | 9      | 8%      |
| PNY                 | 3        | 3      | 3%      |
| A-DATA Technology   | 3        | 4      | 3%      |
| SPCC                | 2        | 6      | 2%      |
| Seagate             | 2        | 2      | 2%      |
| Patriot             | 2        | 2      | 2%      |
| Intel               | 2        | 2      | 2%      |
| Hewlett-Packard     | 2        | 2      | 2%      |
| China               | 2        | 2      | 2%      |
| Vaseky              | 1        | 1      | 1%      |
| Transcend           | 1        | 1      | 1%      |
| Toshiba             | 1        | 1      | 1%      |
| Team                | 1        | 1      | 1%      |
| Smartbuy            | 1        | 1      | 1%      |
| S3+                 | 1        | 1      | 1%      |
| Plextor             | 1        | 1      | 1%      |
| PHD 3.0             | 1        | 1      | 1%      |
| OCZ                 | 1        | 1      | 1%      |
| Neo                 | 1        | 1      | 1%      |
| Micron Technology   | 1        | 1      | 1%      |
| INNOVATION IT       | 1        | 1      | 1%      |
| Hoodisk             | 1        | 1      | 1%      |
| Gigabyte Technology | 1        | 1      | 1%      |
| Emtec               | 1        | 2      | 1%      |
| CT1000MX            | 1        | 1      | 1%      |
| Corsair             | 1        | 1      | 1%      |
| AMD                 | 1        | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 82       | 128    | 38.32%  |
| HDD     | 67       | 136    | 31.31%  |
| NVMe    | 58       | 84     | 27.1%   |
| Unknown | 6        | 7      | 2.8%    |
| MMC     | 1        | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 102      | 256    | 59.3%   |
| NVMe | 58       | 84     | 33.72%  |
| SAS  | 11       | 15     | 6.4%    |
| MMC  | 1        | 1      | 0.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 76       | 113    | 42.94%  |
| 0.51-1.0   | 49       | 74     | 27.68%  |
| 1.01-2.0   | 29       | 44     | 16.38%  |
| 3.01-4.0   | 13       | 18     | 7.34%   |
| 4.01-10.0  | 8        | 13     | 4.52%   |
| 2.01-3.0   | 1        | 1      | 0.56%   |
| 10.01-20.0 | 1        | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 26       | 21.85%  |
| 101-250        | 23       | 19.33%  |
| More than 3000 | 22       | 18.49%  |
| 251-500        | 16       | 13.45%  |
| 1001-2000      | 14       | 11.76%  |
| 2001-3000      | 9        | 7.56%   |
| 51-100         | 4        | 3.36%   |
| 1-20           | 3        | 2.52%   |
| 21-50          | 2        | 1.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 22       | 18.18%  |
| 501-1000       | 19       | 15.7%   |
| 251-500        | 17       | 14.05%  |
| 21-50          | 17       | 14.05%  |
| 1-20           | 16       | 13.22%  |
| 51-100         | 11       | 9.09%   |
| More than 3000 | 10       | 8.26%   |
| 1001-2000      | 7        | 5.79%   |
| 2001-3000      | 2        | 1.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68N32N0 4TB                     | 1        | 2      | 5.26%   |
| WDC WD3200AAJS-65M0A0 320GB                  | 1        | 1      | 5.26%   |
| WDC WD10EZEX-22MFCA0 1TB                     | 1        | 1      | 5.26%   |
| WDC WD10EURX-63UY4Y0 1TB                     | 1        | 1      | 5.26%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1        | 1      | 5.26%   |
| WDC WD10EADS-65L5B1 1TB                      | 1        | 1      | 5.26%   |
| WDC WD Blue SA510 2.5 1000GB SSD             | 1        | 1      | 5.26%   |
| Seagate ST3500320AS 500GB                    | 1        | 1      | 5.26%   |
| Seagate ST31500341AS 1TB                     | 1        | 1      | 5.26%   |
| Seagate ST1000VX000-1CU162 1TB               | 1        | 1      | 5.26%   |
| Seagate ST1000DM003-1CH162 1TB               | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1        | 1      | 5.26%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 2      | 5.26%   |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 5.26%   |
| Neo Forza NFS121SA312-6007000 120GB SSD      | 1        | 1      | 5.26%   |
| Maxtor STM3160215AS 160GB                    | 1        | 1      | 5.26%   |
| Intel SSDSCKKW240H6 240GB                    | 1        | 1      | 5.26%   |
| Intel SSDPEKNW512G8 512GB                    | 1        | 2      | 5.26%   |
| Apple HDD HTS541010A9E662 1TB                | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 36.84%  |
| Seagate             | 4        | 4      | 21.05%  |
| Samsung Electronics | 3        | 4      | 15.79%  |
| Intel               | 2        | 3      | 10.53%  |
| Neo                 | 1        | 1      | 5.26%   |
| Maxtor              | 1        | 1      | 5.26%   |
| Apple               | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 46.15%  |
| Seagate             | 4        | 4      | 30.77%  |
| Samsung Electronics | 1        | 1      | 7.69%   |
| Maxtor              | 1        | 1      | 7.69%   |
| Apple               | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 14     | 64.29%  |
| SSD  | 4        | 6      | 28.57%  |
| NVMe | 1        | 2      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 72       | 209    | 52.17%  |
| Works    | 52       | 123    | 37.68%  |
| Malfunc  | 13       | 22     | 9.42%   |
| Failed   | 1        | 2      | 0.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 59       | 29.5%   |
| AMD                          | 58       | 29%     |
| Samsung Electronics          | 20       | 10%     |
| Sandisk                      | 15       | 7.5%    |
| ASMedia Technology           | 7        | 3.5%    |
| Phison Electronics           | 6        | 3%      |
| Micron/Crucial Technology    | 6        | 3%      |
| Silicon Motion               | 5        | 2.5%    |
| Kingston Technology Company  | 5        | 2.5%    |
| JMicron Technology           | 4        | 2%      |
| Realtek Semiconductor        | 3        | 1.5%    |
| Marvell Technology Group     | 3        | 1.5%    |
| ADATA Technology             | 3        | 1.5%    |
| MAXIO Technology (Hangzhou)  | 2        | 1%      |
| VIA Technologies             | 1        | 0.5%    |
| Silicon Image                | 1        | 0.5%    |
| Shenzhen Longsys Electronics | 1        | 0.5%    |
| LSI Logic / Symbios Logic    | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29       | 12.13%  |
| AMD 500 Series Chipset SATA Controller                                                  | 13       | 5.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 5.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 4.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 2.93%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 2.93%   |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 2.93%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 6        | 2.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 2.09%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 2.09%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 2.09%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.67%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.67%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 3        | 1.26%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.26%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.26%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 3        | 1.26%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.84%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2        | 0.84%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.84%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 2        | 0.84%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 2        | 0.84%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.84%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.84%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.84%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.42%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.42%   |
| Shenzhen Longsys FORESEE XP2000, Lexar NM760 NVME SSD (DRAM-less)                       | 1        | 0.42%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                                      | 1        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 107      | 58.47%  |
| NVMe | 58       | 31.69%  |
| IDE  | 9        | 4.92%   |
| RAID | 8        | 4.37%   |
| SAS  | 1        | 0.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 59       | 50.43%  |
| AMD    | 58       | 49.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 6        | 5.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 5        | 4.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 3        | 2.56%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 3        | 2.56%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 2.56%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 2.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.71%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.71%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 2        | 1.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 1.71%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 1.71%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 2        | 1.71%   |
| Intel Core i5-3330 CPU @ 3.00GHz       | 2        | 1.71%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 2        | 1.71%   |
| AMD Ryzen 7 5700X 8-Core Processor     | 2        | 1.71%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 2        | 1.71%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 2        | 1.71%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 2        | 1.71%   |
| AMD FX-6300 Six-Core Processor         | 2        | 1.71%   |
| Intel Xeon W-2104 CPU @ 3.20GHz        | 1        | 0.85%   |
| Intel Xeon CPU W3580 @ 3.33GHz         | 1        | 0.85%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz    | 1        | 0.85%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz    | 1        | 0.85%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz | 1        | 0.85%   |
| Intel Pentium CPU N4200 @ 1.10GHz      | 1        | 0.85%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 0.85%   |
| Intel N100                             | 1        | 0.85%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 0.85%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 0.85%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 1        | 0.85%   |
| Intel Core i7-4960X CPU @ 3.60GHz      | 1        | 0.85%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1        | 0.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1        | 0.85%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 0.85%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 1        | 0.85%   |
| Intel Core i5-9600KF CPU @ 3.70GHz     | 1        | 0.85%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 0.85%   |
| Intel Core i5-8500 CPU @ 3.00GHz       | 1        | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| AMD Ryzen 5        | 22       | 18.8%   |
| Intel Core i7      | 20       | 17.09%  |
| Intel Core i5      | 19       | 16.24%  |
| AMD Ryzen 7        | 17       | 14.53%  |
| Other              | 8        | 6.84%   |
| AMD Ryzen 9        | 6        | 5.13%   |
| Intel Xeon         | 4        | 3.42%   |
| AMD FX             | 3        | 2.56%   |
| Intel Pentium      | 2        | 1.71%   |
| Intel Core i3      | 2        | 1.71%   |
| Intel Celeron      | 2        | 1.71%   |
| AMD Ryzen 5 PRO    | 2        | 1.71%   |
| AMD Phenom II X4   | 2        | 1.71%   |
| Intel Pentium Gold | 1        | 0.85%   |
| Intel Core i9      | 1        | 0.85%   |
| AMD Ryzen Embedded | 1        | 0.85%   |
| AMD Ryzen 3 PRO    | 1        | 0.85%   |
| AMD Phenom II X6   | 1        | 0.85%   |
| AMD Athlon II X3   | 1        | 0.85%   |
| AMD Athlon         | 1        | 0.85%   |
| AMD A10            | 1        | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 43       | 36.75%  |
| 6      | 35       | 29.91%  |
| 8      | 20       | 17.09%  |
| 2      | 8        | 6.84%   |
| 12     | 4        | 3.42%   |
| 16     | 3        | 2.56%   |
| 3      | 3        | 2.56%   |
| 10     | 1        | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 117      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 83       | 70.94%  |
| 1      | 34       | 29.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 117      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 92       | 77.31%  |
| 0x0a601203 | 6        | 5.04%   |
| 0x0a20120a | 3        | 2.52%   |
| 0x08701021 | 3        | 2.52%   |
| 0x0800820d | 2        | 1.68%   |
| 0x306c3    | 1        | 0.84%   |
| 0x0a50000d | 1        | 0.84%   |
| 0x0a50000c | 1        | 0.84%   |
| 0x0a201025 | 1        | 0.84%   |
| 0x08701030 | 1        | 0.84%   |
| 0x08701013 | 1        | 0.84%   |
| 0x08108109 | 1        | 0.84%   |
| 0x0810100b | 1        | 0.84%   |
| 0x08101007 | 1        | 0.84%   |
| 0x08001138 | 1        | 0.84%   |
| 0x0700010f | 1        | 0.84%   |
| 0x06000852 | 1        | 0.84%   |
| 0x010000dc | 1        | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 15       | 12.71%  |
| KabyLake         | 15       | 12.71%  |
| Haswell          | 12       | 10.17%  |
| Zen+             | 11       | 9.32%   |
| Zen 2            | 11       | 9.32%   |
| Unknown          | 11       | 9.32%   |
| SandyBridge      | 9        | 7.63%   |
| Zen              | 5        | 4.24%   |
| IvyBridge        | 5        | 4.24%   |
| K10              | 4        | 3.39%   |
| Skylake          | 3        | 2.54%   |
| Piledriver       | 3        | 2.54%   |
| Icelake          | 3        | 2.54%   |
| Nehalem          | 2        | 1.69%   |
| Alderlake Hybrid | 2        | 1.69%   |
| Westmere         | 1        | 0.85%   |
| Tremont          | 1        | 0.85%   |
| Steamroller      | 1        | 0.85%   |
| Jaguar           | 1        | 0.85%   |
| Goldmont         | 1        | 0.85%   |
| CometLake        | 1        | 0.85%   |
| Broadwell        | 1        | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 53       | 41.73%  |
| Nvidia | 46       | 36.22%  |
| Intel  | 28       | 22.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 9.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 5.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 4.58%   |
| AMD Raphael                                                                 | 6        | 4.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 3.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.29%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.29%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.29%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 2.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.29%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.53%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.53%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 1.53%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.53%   |
| Intel DG2 [Arc A380]                                                        | 2        | 1.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.53%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.53%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 1.53%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.53%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.76%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.76%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.76%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.76%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.76%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.76%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 45       | 38.46%  |
| 1 x Nvidia      | 41       | 35.04%  |
| 1 x Intel       | 20       | 17.09%  |
| 2 x AMD         | 3        | 2.56%   |
| Intel + AMD     | 3        | 2.56%   |
| Intel + Nvidia  | 2        | 1.71%   |
| 2 x Nvidia      | 1        | 0.85%   |
| Intel + 2 x AMD | 1        | 0.85%   |
| AMD + Nvidia    | 1        | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 77       | 65.25%  |
| Proprietary | 39       | 33.05%  |
| Unknown     | 2        | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 52       | 43.7%   |
| 7.01-8.0   | 17       | 14.29%  |
| 3.01-4.0   | 12       | 10.08%  |
| 1.01-2.0   | 12       | 10.08%  |
| 8.01-16.0  | 8        | 6.72%   |
| 5.01-6.0   | 7        | 5.88%   |
| 0.01-0.5   | 4        | 3.36%   |
| 16.01-24.0 | 3        | 2.52%   |
| 2.01-3.0   | 2        | 1.68%   |
| 4.01-5.0   | 1        | 0.84%   |
| 0.51-1.0   | 1        | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 14.18%  |
| Dell                 | 15       | 11.19%  |
| Hewlett-Packard      | 11       | 8.21%   |
| Iiyama               | 10       | 7.46%   |
| Goldstar             | 9        | 6.72%   |
| Acer                 | 9        | 6.72%   |
| Ancor Communications | 8        | 5.97%   |
| Philips              | 7        | 5.22%   |
| ASUSTek Computer     | 6        | 4.48%   |
| BenQ                 | 5        | 3.73%   |
| AOC                  | 5        | 3.73%   |
| Eizo                 | 4        | 2.99%   |
| Lenovo               | 3        | 2.24%   |
| Gigabyte Technology  | 3        | 2.24%   |
| MSI                  | 2        | 1.49%   |
| Wacom                | 1        | 0.75%   |
| Vizio                | 1        | 0.75%   |
| VIZ                  | 1        | 0.75%   |
| ViewSonic            | 1        | 0.75%   |
| RTK                  | 1        | 0.75%   |
| ONN                  | 1        | 0.75%   |
| NEC Computers        | 1        | 0.75%   |
| Mi                   | 1        | 0.75%   |
| Medion Akoya         | 1        | 0.75%   |
| INS                  | 1        | 0.75%   |
| HYU                  | 1        | 0.75%   |
| HKC                  | 1        | 0.75%   |
| Hannspree            | 1        | 0.75%   |
| Haier                | 1        | 0.75%   |
| GDH                  | 1        | 0.75%   |
| DENON                | 1        | 0.75%   |
| CVT                  | 1        | 0.75%   |
| Unknown              | 1        | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 2        | 1.31%   |
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                  | 2        | 1.31%   |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                   | 2        | 1.31%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                      | 2        | 1.31%   |
| Ancor Communications MX259 ACI25C2 1920x1080 550x310mm 24.9-inch       | 2        | 1.31%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch               | 1        | 0.65%   |
| Vizio D24h-G9 VIZ1028 1366x768 521x293mm 23.5-inch                     | 1        | 0.65%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                     | 1        | 0.65%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                 | 1        | 0.65%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch      | 1        | 0.65%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch      | 1        | 0.65%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.65%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch   | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 340x270mm 17.1-inch   | 1        | 0.65%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch     | 1        | 0.65%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch     | 1        | 0.65%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch      | 1        | 0.65%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 0.65%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch      | 1        | 0.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 1        | 0.65%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch      | 1        | 0.65%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch      | 1        | 0.65%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1110x620mm 50.1-inch | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0992 1920x1080 890x500mm 40.2-inch  | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch  | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0679 1360x768 410x256mm 19.0-inch   | 1        | 0.65%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch     | 1        | 0.65%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 797x333mm 34.0-inch        | 1        | 0.65%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1        | 0.65%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                      | 1        | 0.65%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch              | 1        | 0.65%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch               | 1        | 0.65%   |
| Philips PHL 240V5A PHLC10C 1920x1080 530x300mm 24.0-inch               | 1        | 0.65%   |
| Philips PHL 230B8Q PHL0936 1920x1200 488x297mm 22.5-inch               | 1        | 0.65%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 0.65%   |
| Philips 27M1N3200V PHLC279 1920x1080 598x336mm 27.0-inch               | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 45.8%   |
| 3840x2160 (4K)     | 23       | 17.56%  |
| 2560x1440 (QHD)    | 13       | 9.92%   |
| 1920x1200 (WUXGA)  | 6        | 4.58%   |
| 1600x900 (HD+)     | 5        | 3.82%   |
| 1440x900 (WXGA+)   | 5        | 3.82%   |
| 3440x1440          | 4        | 3.05%   |
| 2560x1080          | 4        | 3.05%   |
| 1366x768 (WXGA)    | 4        | 3.05%   |
| 1680x1050 (WSXGA+) | 3        | 2.29%   |
| 3840x1080          | 1        | 0.76%   |
| 1360x768           | 1        | 0.76%   |
| 1280x1024 (SXGA)   | 1        | 0.76%   |
| Unknown            | 1        | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 30       | 21.58%  |
| 27      | 27       | 19.42%  |
| 23      | 15       | 10.79%  |
| 31      | 14       | 10.07%  |
| 21      | 9        | 6.47%   |
| 19      | 9        | 6.47%   |
| 34      | 7        | 5.04%   |
| 28      | 3        | 2.16%   |
| 22      | 3        | 2.16%   |
| 18      | 3        | 2.16%   |
| Unknown | 3        | 2.16%   |
| 46      | 2        | 1.44%   |
| 40      | 2        | 1.44%   |
| 20      | 2        | 1.44%   |
| 84      | 1        | 0.72%   |
| 72      | 1        | 0.72%   |
| 69      | 1        | 0.72%   |
| 52      | 1        | 0.72%   |
| 43      | 1        | 0.72%   |
| 33      | 1        | 0.72%   |
| 32      | 1        | 0.72%   |
| 26      | 1        | 0.72%   |
| 25      | 1        | 0.72%   |
| 17      | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 67       | 50.38%  |
| 401-500     | 24       | 18.05%  |
| 601-700     | 20       | 15.04%  |
| 701-800     | 9        | 6.77%   |
| 1501-2000   | 3        | 2.26%   |
| 1001-1500   | 3        | 2.26%   |
| Unknown     | 3        | 2.26%   |
| 801-900     | 2        | 1.5%    |
| 301-350     | 1        | 0.75%   |
| 901-1000    | 1        | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 92       | 76.03%  |
| 16/10   | 17       | 14.05%  |
| 21/9    | 8        | 6.61%   |
| Unknown | 3        | 2.48%   |
| 5/4     | 1        | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 41       | 29.93%  |
| 301-350        | 27       | 19.71%  |
| 351-500        | 25       | 18.25%  |
| 251-300        | 16       | 11.68%  |
| 151-200        | 12       | 8.76%   |
| 501-1000       | 5        | 3.65%   |
| More than 1000 | 4        | 2.92%   |
| 141-150        | 4        | 2.92%   |
| Unknown        | 3        | 2.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 78       | 63.41%  |
| 101-120 | 23       | 18.7%   |
| 121-160 | 12       | 9.76%   |
| 1-50    | 4        | 3.25%   |
| 161-240 | 3        | 2.44%   |
| Unknown | 3        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 82       | 70.09%  |
| 2     | 28       | 23.93%  |
| 3     | 6        | 5.13%   |
| 4     | 1        | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 85       | 49.13%  |
| Intel                             | 41       | 23.7%   |
| MediaTek                          | 9        | 5.2%    |
| TP-Link                           | 6        | 3.47%   |
| Qualcomm Atheros                  | 6        | 3.47%   |
| Broadcom                          | 5        | 2.89%   |
| ASUSTek Computer                  | 4        | 2.31%   |
| Ralink                            | 3        | 1.73%   |
| Arduino SA                        | 2        | 1.16%   |
| Xiaomi                            | 1        | 0.58%   |
| Van Ooijen Technische Informatica | 1        | 0.58%   |
| Texas Instruments                 | 1        | 0.58%   |
| Tehuti Networks                   | 1        | 0.58%   |
| QinHeng Electronics               | 1        | 0.58%   |
| NetGear                           | 1        | 0.58%   |
| Microsoft                         | 1        | 0.58%   |
| Linksys                           | 1        | 0.58%   |
| Huawei Technologies               | 1        | 0.58%   |
| Google                            | 1        | 0.58%   |
| D-Link System                     | 1        | 0.58%   |
| Aquantia                          | 1        | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 55       | 29.1%   |
| Realtek RTL8125 2.5GbE Controller                                             | 19       | 10.05%  |
| Intel I211 Gigabit Network Connection                                         | 11       | 5.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 5        | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 2.12%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.12%   |
| Intel Ethernet Connection (7) I219-V                                          | 4        | 2.12%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 1.59%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 1.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 1.06%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 1.06%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.06%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2        | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.06%   |
| Realtek 802.11ac NIC                                                          | 2        | 1.06%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 1.06%   |
| Intel Wireless 7265                                                           | 2        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 1.06%   |
| ASUS 802.11ac NIC                                                             | 2        | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 0.53%   |
| Van Ooijen Technische Informatica Teensyduino Serial                          | 1        | 0.53%   |
| TP-Link 802.11n NIC                                                           | 1        | 0.53%   |
| Texas Instruments TI CC2540 USB CDC                                           | 1        | 0.53%   |
| Tehuti Networks TN9210 10GBase-T Ethernet Adapter                             | 1        | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 0.53%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.53%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.53%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 0.53%   |
| QinHeng USB Single Serial                                                     | 1        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 25.93%  |
| Intel                 | 9        | 16.67%  |
| MediaTek              | 7        | 12.96%  |
| TP-Link               | 6        | 11.11%  |
| Qualcomm Atheros      | 5        | 9.26%   |
| ASUSTek Computer      | 4        | 7.41%   |
| Ralink                | 3        | 5.56%   |
| Broadcom              | 2        | 3.7%    |
| NetGear               | 1        | 1.85%   |
| Microsoft             | 1        | 1.85%   |
| Linksys               | 1        | 1.85%   |
| D-Link System         | 1        | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 4        | 7.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 3.64%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 3.64%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 3.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 3.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 3.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 3.64%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2        | 3.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 3.64%   |
| Realtek 802.11ac NIC                                                          | 2        | 3.64%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 3.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 3.64%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 3.64%   |
| Intel Wireless 7265                                                           | 2        | 3.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 3.64%   |
| ASUS 802.11ac NIC                                                             | 2        | 3.64%   |
| TP-Link 802.11n NIC                                                           | 1        | 1.82%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 1.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 1.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 1.82%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.82%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.82%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                               | 1        | 1.82%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 1        | 1.82%   |
| MediaTek WiFi                                                                 | 1        | 1.82%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                     | 1        | 1.82%   |
| Intel Wireless 8260                                                           | 1        | 1.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 1.82%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 1.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 1.82%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1        | 1.82%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.82%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.82%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                | 1        | 1.82%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 1        | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 80       | 62.5%   |
| Intel                 | 36       | 28.13%  |
| Broadcom              | 3        | 2.34%   |
| Qualcomm Atheros      | 2        | 1.56%   |
| MediaTek              | 2        | 1.56%   |
| Xiaomi                | 1        | 0.78%   |
| Tehuti Networks       | 1        | 0.78%   |
| Huawei Technologies   | 1        | 0.78%   |
| Google                | 1        | 0.78%   |
| Aquantia              | 1        | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 55       | 42.64%  |
| Realtek RTL8125 2.5GbE Controller                                              | 19       | 14.73%  |
| Intel I211 Gigabit Network Connection                                          | 11       | 8.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4        | 3.1%    |
| Intel Ethernet Controller I225-V                                               | 4        | 3.1%    |
| Intel Ethernet Connection (7) I219-V                                           | 4        | 3.1%    |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 2.33%   |
| Intel 82579V Gigabit Network Connection                                        | 3        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1        | 0.78%   |
| Tehuti Networks TN9210 10GBase-T Ethernet Adapter                              | 1        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1        | 0.78%   |
| MediaTek Infinix SMART 5                                                       | 1        | 0.78%   |
| Intel Ethernet Controller I219-V                                               | 1        | 0.78%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 0.78%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.78%   |
| Intel CNVi: Wi-Fi                                                              | 1        | 0.78%   |
| Huawei FOA-LX9                                                                 | 1        | 0.78%   |
| Google Pixel 6a                                                                | 1        | 0.78%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                        | 1        | 0.78%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1        | 0.78%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 1        | 0.78%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 68.24%  |
| WiFi     | 50       | 29.41%  |
| Modem    | 4        | 2.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 96       | 75.59%  |
| WiFi     | 31       | 24.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 81       | 68.64%  |
| 2     | 32       | 27.12%  |
| 3     | 2        | 1.69%   |
| 0     | 2        | 1.69%   |
| 5     | 1        | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 69.49%  |
| Yes  | 36       | 30.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 14       | 27.45%  |
| Intel                           | 11       | 21.57%  |
| Realtek Semiconductor           | 7        | 13.73%  |
| MediaTek                        | 5        | 9.8%    |
| Qualcomm Atheros Communications | 3        | 5.88%   |
| ASUSTek Computer                | 3        | 5.88%   |
| TP-Link                         | 2        | 3.92%   |
| Realtek                         | 1        | 1.96%   |
| Logitech                        | 1        | 1.96%   |
| Lite-On Technology              | 1        | 1.96%   |
| IMC Networks                    | 1        | 1.96%   |
| Foxconn / Hon Hai               | 1        | 1.96%   |
| Broadcom                        | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 27.45%  |
| Realtek Bluetooth Radio                             | 7        | 13.73%  |
| MediaTek Wireless_Device                            | 5        | 9.8%    |
| Intel Bluetooth wireless interface                  | 3        | 5.88%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2        | 3.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2        | 3.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 3.92%   |
| Intel AX210 Bluetooth                               | 2        | 3.92%   |
| Intel AX201 Bluetooth                               | 2        | 3.92%   |
| Realtek Bluetooth Radio                             | 1        | 1.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.96%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 1.96%   |
| Lite-On Bluetooth Device                            | 1        | 1.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.96%   |
| Intel AX200 Bluetooth                               | 1        | 1.96%   |
| IMC Networks BCM20702A0                             | 1        | 1.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 1.96%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 1.96%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.96%   |
| ASUS Bluetooth Radio                                | 1        | 1.96%   |
| ASUS ASUS USB-BT500                                 | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 72       | 31.86%  |
| Intel                    | 61       | 26.99%  |
| Nvidia                   | 45       | 19.91%  |
| C-Media Electronics      | 8        | 3.54%   |
| Logitech                 | 6        | 2.65%   |
| Focusrite-Novation       | 4        | 1.77%   |
| Texas Instruments        | 3        | 1.33%   |
| Generalplus Technology   | 3        | 1.33%   |
| VIA Technologies         | 2        | 0.88%   |
| SteelSeries ApS          | 2        | 0.88%   |
| SAVITECH                 | 2        | 0.88%   |
| Micro Star International | 2        | 0.88%   |
| Creative Labs            | 2        | 0.88%   |
| Trust                    | 1        | 0.44%   |
| TEAC                     | 1        | 0.44%   |
| Realtek Semiconductor    | 1        | 0.44%   |
| Mackie Designs           | 1        | 0.44%   |
| JMTek                    | 1        | 0.44%   |
| GN Netcom                | 1        | 0.44%   |
| DSEA A/S                 | 1        | 0.44%   |
| Dell                     | 1        | 0.44%   |
| Creative Technology      | 1        | 0.44%   |
| Corsair                  | 1        | 0.44%   |
| AudioQuest               | 1        | 0.44%   |
| ASUSTek Computer         | 1        | 0.44%   |
| Asahi Kasei Microsystems | 1        | 0.44%   |
| 2.4G Composite Device    | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 21       | 7.69%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 18       | 6.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 4.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 3.66%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 3.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 2.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 2.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 2.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6        | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 1.83%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.47%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 1.47%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 1.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.1%    |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.1%    |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.1%    |
| Generalplus Technology USB Audio Device                                    | 3        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.1%    |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 2        | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.73%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.73%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.73%   |
| Micro Star International USB Audio                                         | 2        | 0.73%   |
| Intel DG2 Audio Controller                                                 | 2        | 0.73%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.73%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.73%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 2        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 16       | 22.86%  |
| Corsair             | 10       | 14.29%  |
| Samsung Electronics | 9        | 12.86%  |
| G.Skill             | 9        | 12.86%  |
| Crucial             | 6        | 8.57%   |
| SK hynix            | 3        | 4.29%   |
| Patriot             | 3        | 4.29%   |
| A-DATA Technology   | 3        | 4.29%   |
| Unknown             | 2        | 2.86%   |
| Team                | 2        | 2.86%   |
| Micron Technology   | 2        | 2.86%   |
| Unknown (ABCD)      | 1        | 1.43%   |
| Ramaxel Technology  | 1        | 1.43%   |
| Nanya Technology    | 1        | 1.43%   |
| Atermiter           | 1        | 1.43%   |
| Unknown             | 1        | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s             | 2        | 2.74%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s            | 2        | 2.74%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 2        | 2.74%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 2.74%   |
| Unknown RAM Module 8GB DIMM 667MT/s                            | 1        | 1.37%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 1.37%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s   | 1        | 1.37%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 1        | 1.37%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1        | 1.37%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 1.37%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s           | 1        | 1.37%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 1.37%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s       | 1        | 1.37%   |
| Samsung RAM M391B5773CH0-YH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.37%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s         | 1        | 1.37%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s         | 1        | 1.37%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s            | 1        | 1.37%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 1        | 1.37%   |
| Samsung RAM M378A2G43AB3-CWE 16GB DIMM DDR4 3200MT/s           | 1        | 1.37%   |
| Samsung RAM 53D512M64D4RQ-046 4GB Row Of Chips LPDDR4 4267MT/s | 1        | 1.37%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2400MT/s         | 1        | 1.37%   |
| Patriot RAM PSD44G240041 4GB DIMM DDR4 2400MT/s                | 1        | 1.37%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.37%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1        | 1.37%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 1.37%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s           | 1        | 1.37%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3800MT/s         | 1        | 1.37%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s            | 1        | 1.37%   |
| Kingston RAM KF560C36-32 32GB DIMM DDR5 6000MT/s               | 1        | 1.37%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s               | 1        | 1.37%   |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 12800MT/s              | 1        | 1.37%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s          | 1        | 1.37%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 1        | 1.37%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 1        | 1.37%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s             | 1        | 1.37%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 1.37%   |
| Kingston RAM 9965646-035.B00G 8GB SODIMM DDR4 2933MT/s         | 1        | 1.37%   |
| Kingston RAM 9905678-042.A00G 8GB DIMM DDR4 2400MT/s           | 1        | 1.37%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 38       | 61.29%  |
| DDR3    | 14       | 22.58%  |
| DDR5    | 6        | 9.68%   |
| LPDDR4  | 2        | 3.23%   |
| SDRAM   | 1        | 1.61%   |
| Unknown | 1        | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 58       | 93.55%  |
| SODIMM       | 3        | 4.84%   |
| Row Of Chips | 1        | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 34.33%  |
| 16384 | 22       | 32.84%  |
| 4096  | 13       | 19.4%   |
| 32768 | 5        | 7.46%   |
| 2048  | 3        | 4.48%   |
| 12288 | 1        | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 11       | 15.71%  |
| 2400  | 11       | 15.71%  |
| 3600  | 8        | 11.43%  |
| 1333  | 6        | 8.57%   |
| 1800  | 4        | 5.71%   |
| 6000  | 3        | 4.29%   |
| 3800  | 3        | 4.29%   |
| 2667  | 3        | 4.29%   |
| 1600  | 3        | 4.29%   |
| 2933  | 2        | 2.86%   |
| 2666  | 2        | 2.86%   |
| 12800 | 1        | 1.43%   |
| 6400  | 1        | 1.43%   |
| 4800  | 1        | 1.43%   |
| 4267  | 1        | 1.43%   |
| 3733  | 1        | 1.43%   |
| 3666  | 1        | 1.43%   |
| 3400  | 1        | 1.43%   |
| 3334  | 1        | 1.43%   |
| 3266  | 1        | 1.43%   |
| 3066  | 1        | 1.43%   |
| 2473  | 1        | 1.43%   |
| 2133  | 1        | 1.43%   |
| 1866  | 1        | 1.43%   |
| 667   | 1        | 1.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 2        | 50%     |
| Pantum             | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-7100 Series | 1        | 25%     |
| Seiko Epson XP-2200 Series | 1        | 25%     |
| Pantum P2200W series       | 1        | 25%     |
| Brother HL-L2310D series   | 1        | 25%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia                      | 6        | 22.22%  |
| Logitech                      | 5        | 18.52%  |
| Samsung Electronics           | 2        | 7.41%   |
| Trust                         | 1        | 3.7%    |
| Sunplus Innovation Technology | 1        | 3.7%    |
| SN0002                        | 1        | 3.7%    |
| Realtek Semiconductor         | 1        | 3.7%    |
| OPPO Electronics              | 1        | 3.7%    |
| Microsoft                     | 1        | 3.7%    |
| MacroSilicon                  | 1        | 3.7%    |
| Jieli Technology              | 1        | 3.7%    |
| icSpring                      | 1        | 3.7%    |
| Generalplus Technology        | 1        | 3.7%    |
| GEMBIRD                       | 1        | 3.7%    |
| Chicony Electronics           | 1        | 3.7%    |
| AVerMedia Technologies        | 1        | 3.7%    |
| A4Tech                        | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 7.41%   |
| Microdia Webcam Vitade AF                         | 2        | 7.41%   |
| Microdia Camera                                   | 2        | 7.41%   |
| Trust Trust Full HD Webcam                        | 1        | 3.7%    |
| Sunplus DICOTA 4K                                 | 1        | 3.7%    |
| SN0002 1080P Web Camera                           | 1        | 3.7%    |
| Realtek FULL HD 1080P Webcam                      | 1        | 3.7%    |
| OPPO Oppo N1                                      | 1        | 3.7%    |
| Microsoft LifeCam Cinema                          | 1        | 3.7%    |
| Microdia USB 2.0 Camera                           | 1        | 3.7%    |
| Microdia Streaming Camera W8GS                    | 1        | 3.7%    |
| MacroSilicon USB Video                            | 1        | 3.7%    |
| Logitech Webcam C270                              | 1        | 3.7%    |
| Logitech HD Webcam C615                           | 1        | 3.7%    |
| Logitech HD Pro Webcam C920                       | 1        | 3.7%    |
| Logitech C922 Pro Stream Webcam                   | 1        | 3.7%    |
| Logitech BRIO Ultra HD Webcam                     | 1        | 3.7%    |
| Jieli USB PHY 2.0                                 | 1        | 3.7%    |
| icSpring camera                                   | 1        | 3.7%    |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 3.7%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 3.7%    |
| Chicony HP High Definition 1MP Webcam             | 1        | 3.7%    |
| AVerMedia AVerMedia PW310O Webcam                 | 1        | 3.7%    |
| A4Tech FHD 1080P PC Camera                        | 1        | 3.7%    |

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
| 0     | 101      | 84.87%  |
| 1     | 16       | 13.45%  |
| 3     | 1        | 0.84%   |
| 2     | 1        | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 6        | 33.33%  |
| Graphics card            | 4        | 22.22%  |
| Unassigned class         | 2        | 11.11%  |
| Communication controller | 2        | 11.11%  |
| Storage/raid             | 1        | 5.56%   |
| Sound                    | 1        | 5.56%   |
| Net/ethernet             | 1        | 5.56%   |
| Camera                   | 1        | 5.56%   |

