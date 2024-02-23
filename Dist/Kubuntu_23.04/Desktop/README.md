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

Total: 148

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 6.2.0-20-generic       | 17       | 14.05%  |
| 6.2.0-27-generic       | 14       | 11.57%  |
| 6.2.0-34-generic       | 12       | 9.92%   |
| 6.2.0-32-generic       | 9        | 7.44%   |
| 6.2.0-33-generic       | 8        | 6.61%   |
| 6.2.0-24-generic       | 8        | 6.61%   |
| 6.2.0-26-generic       | 6        | 4.96%   |
| 6.2.0-23-generic       | 6        | 4.96%   |
| 6.2.0-25-generic       | 5        | 4.13%   |
| 6.2.0-36-generic       | 4        | 3.31%   |
| 6.2.0-31-generic       | 4        | 3.31%   |
| 6.2.0-39-generic       | 3        | 2.48%   |
| 6.2.0-1003-lowlatency  | 3        | 2.48%   |
| 6.2.0-35-generic       | 2        | 1.65%   |
| 6.2.0-1013-lowlatency  | 2        | 1.65%   |
| 6.5.1-060501-generic   | 1        | 0.83%   |
| 6.4.6-060406-generic   | 1        | 0.83%   |
| 6.4.3-1-liquorix-amd64 | 1        | 0.83%   |
| 6.4.1-2-liquorix-amd64 | 1        | 0.83%   |
| 6.4.0-060400-generic   | 1        | 0.83%   |
| 6.3.5-060305-generic   | 1        | 0.83%   |
| 6.3.10                 | 1        | 0.83%   |
| 6.2.5-060205-generic   | 1        | 0.83%   |
| 6.2.0-1015-lowlatency  | 1        | 0.83%   |
| 6.2.0-1014-lowlatency  | 1        | 0.83%   |
| 6.2.0-1009-lowlatency  | 1        | 0.83%   |
| 6.2.0-1008-lowlatency  | 1        | 0.83%   |
| 6.2.0-1007-lowlatency  | 1        | 0.83%   |
| 6.1.0-16-generic       | 1        | 0.83%   |
| 5.19.0-42-generic      | 1        | 0.83%   |
| 5.19.0-28-generic      | 1        | 0.83%   |
| 5.19.0-1023-lowlatency | 1        | 0.83%   |
| 5.15.0-86-generic      | 1        | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 104      | 88.89%  |
| 5.19.0  | 3        | 2.56%   |
| 6.5.1   | 1        | 0.85%   |
| 6.4.6   | 1        | 0.85%   |
| 6.4.3   | 1        | 0.85%   |
| 6.4.1   | 1        | 0.85%   |
| 6.4.0   | 1        | 0.85%   |
| 6.3.5   | 1        | 0.85%   |
| 6.3.10  | 1        | 0.85%   |
| 6.2.5   | 1        | 0.85%   |
| 6.1.0   | 1        | 0.85%   |
| 5.15.0  | 1        | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 105      | 89.74%  |
| 6.4     | 4        | 3.42%   |
| 5.19    | 3        | 2.56%   |
| 6.3     | 2        | 1.71%   |
| 6.5     | 1        | 0.85%   |
| 6.1     | 1        | 0.85%   |
| 5.15    | 1        | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 115      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 112      | 97.39%  |
| KDE  | 3        | 2.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 98       | 84.48%  |
| Wayland | 17       | 14.66%  |
| Tty     | 1        | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 72       | 62.07%  |
| Unknown | 40       | 34.48%  |
| LightDM | 2        | 1.72%   |
| GDM3    | 2        | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 51       | 43.97%  |
| de_DE | 13       | 11.21%  |
| en_GB | 9        | 7.76%   |
| it_IT | 8        | 6.9%    |
| fr_FR | 8        | 6.9%    |
| ru_RU | 5        | 4.31%   |
| pt_BR | 4        | 3.45%   |
| sv_SE | 2        | 1.72%   |
| pl_PL | 2        | 1.72%   |
| en_CA | 2        | 1.72%   |
| C     | 2        | 1.72%   |
| zh_TW | 1        | 0.86%   |
| fr_BE | 1        | 0.86%   |
| es_MX | 1        | 0.86%   |
| es_ES | 1        | 0.86%   |
| es_CO | 1        | 0.86%   |
| es_CL | 1        | 0.86%   |
| en_IN | 1        | 0.86%   |
| en_IL | 1        | 0.86%   |
| de_CH | 1        | 0.86%   |
| da_DK | 1        | 0.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 66       | 56.9%   |
| EFI  | 50       | 43.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 83       | 72.17%  |
| Tmpfs   | 21       | 18.26%  |
| Btrfs   | 8        | 6.96%   |
| Xfs     | 1        | 0.87%   |
| Overlay | 1        | 0.87%   |
| F2fs    | 1        | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 69       | 59.48%  |
| Unknown | 39       | 33.62%  |
| MBR     | 8        | 6.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 74.78%  |
| Yes       | 29       | 25.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 65.22%  |
| Yes       | 40       | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 38       | 33.04%  |
| Gigabyte Technology | 20       | 17.39%  |
| MSI                 | 17       | 14.78%  |
| ASRock              | 10       | 8.7%    |
| Hewlett-Packard     | 4        | 3.48%   |
| Dell                | 4        | 3.48%   |
| Intel               | 3        | 2.61%   |
| Unknown             | 3        | 2.61%   |
| Lenovo              | 2        | 1.74%   |
| Fujitsu             | 2        | 1.74%   |
| Seco                | 1        | 0.87%   |
| Pegatron            | 1        | 0.87%   |
| Huanan              | 1        | 0.87%   |
| Google              | 1        | 0.87%   |
| Gateway             | 1        | 0.87%   |
| Foxconn             | 1        | 0.87%   |
| Colorful Technology | 1        | 0.87%   |
| Biostar             | 1        | 0.87%   |
| BESSTAR Tech        | 1        | 0.87%   |
| AZW                 | 1        | 0.87%   |
| Alienware           | 1        | 0.87%   |
| Acer                | 1        | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Unknown                                     | 3        | 2.61%   |
| MSI MS-7D75                                 | 2        | 1.74%   |
| MSI MS-7C95                                 | 2        | 1.74%   |
| MSI MS-7C56                                 | 2        | 1.74%   |
| MSI MS-7B86                                 | 2        | 1.74%   |
| Gigabyte B550 AORUS ELITE V2                | 2        | 1.74%   |
| ASUS TUF Gaming B550-PLUS                   | 2        | 1.74%   |
| ASUS ROG STRIX B550-F GAMING                | 2        | 1.74%   |
| ASUS All Series                             | 2        | 1.74%   |
| Seco C40                                    | 1        | 0.87%   |
| Pegatron 520-1000nl                         | 1        | 0.87%   |
| MSI MS-7D74                                 | 1        | 0.87%   |
| MSI MS-7D17                                 | 1        | 0.87%   |
| MSI MS-7C37                                 | 1        | 0.87%   |
| MSI MS-7B24                                 | 1        | 0.87%   |
| MSI MS-7B23                                 | 1        | 0.87%   |
| MSI MS-7A32                                 | 1        | 0.87%   |
| MSI MS-7924                                 | 1        | 0.87%   |
| MSI MS-7846                                 | 1        | 0.87%   |
| MSI MS-7693                                 | 1        | 0.87%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T100BHMZ | 1        | 0.87%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS      | 1        | 0.87%   |
| Intel SHARKBAY                              | 1        | 0.87%   |
| Intel H61                                   | 1        | 0.87%   |
| Intel H55                                   | 1        | 0.87%   |
| Huanan X99-F8 GAMING V5.0                   | 1        | 0.87%   |
| HP Z220 CMT Workstation                     | 1        | 0.87%   |
| HP EliteDesk 705 G4 DM 35W (TAA)            | 1        | 0.87%   |
| HP Compaq Elite 8300 SFF                    | 1        | 0.87%   |
| HP 870-119                                  | 1        | 0.87%   |
| Google Zako                                 | 1        | 0.87%   |
| Gigabyte Z390 M GAMING                      | 1        | 0.87%   |
| Gigabyte Z390 GAMING X                      | 1        | 0.87%   |
| Gigabyte Z370P D3                           | 1        | 0.87%   |
| Gigabyte X570S UD                           | 1        | 0.87%   |
| Gigabyte X570S AORUS ELITE AX               | 1        | 0.87%   |
| Gigabyte X470 AORUS ULTRA GAMING            | 1        | 0.87%   |
| Gigabyte H87-HD3                            | 1        | 0.87%   |
| Gigabyte GA-MA770-US3                       | 1        | 0.87%   |
| Gigabyte GA-970A-DS3                        | 1        | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 14       | 12.17%  |
| ASUS ROG            | 7        | 6.09%   |
| ASUS TUF            | 6        | 5.22%   |
| Gigabyte B550       | 4        | 3.48%   |
| Unknown             | 3        | 2.61%   |
| MSI MS-7D75         | 2        | 1.74%   |
| MSI MS-7C95         | 2        | 1.74%   |
| MSI MS-7C56         | 2        | 1.74%   |
| MSI MS-7B86         | 2        | 1.74%   |
| Lenovo IdeaCentre   | 2        | 1.74%   |
| Gigabyte Z390       | 2        | 1.74%   |
| Gigabyte X570S      | 2        | 1.74%   |
| Gigabyte B365M      | 2        | 1.74%   |
| Dell Precision      | 2        | 1.74%   |
| ASUS Maximus        | 2        | 1.74%   |
| ASUS All            | 2        | 1.74%   |
| ASRock X370         | 2        | 1.74%   |
| Seco C40            | 1        | 0.87%   |
| Pegatron 520-1000nl | 1        | 0.87%   |
| MSI MS-7D74         | 1        | 0.87%   |
| MSI MS-7D17         | 1        | 0.87%   |
| MSI MS-7C37         | 1        | 0.87%   |
| MSI MS-7B24         | 1        | 0.87%   |
| MSI MS-7B23         | 1        | 0.87%   |
| MSI MS-7A32         | 1        | 0.87%   |
| MSI MS-7924         | 1        | 0.87%   |
| MSI MS-7846         | 1        | 0.87%   |
| MSI MS-7693         | 1        | 0.87%   |
| Intel SHARKBAY      | 1        | 0.87%   |
| Intel H61           | 1        | 0.87%   |
| Intel H55           | 1        | 0.87%   |
| Huanan X99-F8       | 1        | 0.87%   |
| HP Z220             | 1        | 0.87%   |
| HP EliteDesk        | 1        | 0.87%   |
| HP Compaq           | 1        | 0.87%   |
| HP 870-119          | 1        | 0.87%   |
| Google Zako         | 1        | 0.87%   |
| Gigabyte Z370P      | 1        | 0.87%   |
| Gigabyte X470       | 1        | 0.87%   |
| Gigabyte H87-HD3    | 1        | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 19       | 16.52%  |
| 2019 | 17       | 14.78%  |
| 2018 | 15       | 13.04%  |
| 2022 | 12       | 10.43%  |
| 2021 | 10       | 8.7%    |
| 2017 | 8        | 6.96%   |
| 2012 | 7        | 6.09%   |
| 2011 | 7        | 6.09%   |
| 2014 | 6        | 5.22%   |
| 2013 | 4        | 3.48%   |
| 2010 | 3        | 2.61%   |
| 2023 | 2        | 1.74%   |
| 2016 | 2        | 1.74%   |
| 2009 | 2        | 1.74%   |
| 2015 | 1        | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 115      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 113      | 98.26%  |
| Enabled  | 2        | 1.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 114      | 99.13%  |
| Yes  | 1        | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 31       | 26.96%  |
| 16.01-24.0  | 31       | 26.96%  |
| 8.01-16.0   | 17       | 14.78%  |
| 4.01-8.0    | 16       | 13.91%  |
| 24.01-32.0  | 8        | 6.96%   |
| 64.01-256.0 | 8        | 6.96%   |
| 3.01-4.0    | 4        | 3.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 40       | 32.79%  |
| 3.01-4.0   | 25       | 20.49%  |
| 2.01-3.0   | 25       | 20.49%  |
| 1.01-2.0   | 17       | 13.93%  |
| 8.01-16.0  | 12       | 9.84%   |
| 16.01-24.0 | 3        | 2.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 26.72%  |
| 1      | 26       | 22.41%  |
| 3      | 24       | 20.69%  |
| 4      | 20       | 17.24%  |
| 5      | 7        | 6.03%   |
| 6      | 4        | 3.45%   |
| 8      | 2        | 1.72%   |
| 7      | 2        | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 64.35%  |
| Yes       | 41       | 35.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 114      | 99.13%  |
| No        | 1        | 0.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 55.65%  |
| Yes       | 51       | 44.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 59.13%  |
| Yes       | 47       | 40.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 24       | 20.87%  |
| Germany      | 16       | 13.91%  |
| UK           | 10       | 8.7%    |
| France       | 9        | 7.83%   |
| Italy        | 7        | 6.09%   |
| Russia       | 6        | 5.22%   |
| Canada       | 5        | 4.35%   |
| Switzerland  | 4        | 3.48%   |
| Sweden       | 4        | 3.48%   |
| Poland       | 4        | 3.48%   |
| Brazil       | 4        | 3.48%   |
| Turkey       | 2        | 1.74%   |
| Spain        | 2        | 1.74%   |
| Serbia       | 2        | 1.74%   |
| Netherlands  | 2        | 1.74%   |
| Taiwan       | 1        | 0.87%   |
| Saudi Arabia | 1        | 0.87%   |
| Romania      | 1        | 0.87%   |
| Portugal     | 1        | 0.87%   |
| Mexico       | 1        | 0.87%   |
| Kazakhstan   | 1        | 0.87%   |
| Israel       | 1        | 0.87%   |
| Indonesia    | 1        | 0.87%   |
| India        | 1        | 0.87%   |
| Denmark      | 1        | 0.87%   |
| Colombia     | 1        | 0.87%   |
| Chile        | 1        | 0.87%   |
| Belgium      | 1        | 0.87%   |
| Bangladesh   | 1        | 0.87%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| London               | 3        | 2.56%   |
| Virginia Beach       | 2        | 1.71%   |
| Oberburg             | 2        | 1.71%   |
| Hamburg              | 2        | 1.71%   |
| Florence             | 2        | 1.71%   |
| Arzamas              | 2        | 1.71%   |
| Zuchwil              | 1        | 0.85%   |
| Wiesmoor             | 1        | 0.85%   |
| West Valley          | 1        | 0.85%   |
| Wellsboro            | 1        | 0.85%   |
| Weilmuenster         | 1        | 0.85%   |
| Warsaw               | 1        | 0.85%   |
| Victoria             | 1        | 0.85%   |
| Vaggeryd             | 1        | 0.85%   |
| Ufa                  | 1        | 0.85%   |
| Uelversheim          | 1        | 0.85%   |
| Tilburg              | 1        | 0.85%   |
| The Hague            | 1        | 0.85%   |
| Taichung             | 1        | 0.85%   |
| Sutton               | 1        | 0.85%   |
| Sundsvall            | 1        | 0.85%   |
| Strasbourg           | 1        | 0.85%   |
| Stone Mountain       | 1        | 0.85%   |
| Simpsonville         | 1        | 0.85%   |
| Sibiu                | 1        | 0.85%   |
| Sherbrooke           | 1        | 0.85%   |
| Saskatoon            | 1        | 0.85%   |
| Saro                 | 1        | 0.85%   |
| Sao Paulo            | 1        | 0.85%   |
| Santo André         | 1        | 0.85%   |
| Santiago             | 1        | 0.85%   |
| San Jose             | 1        | 0.85%   |
| San Francisco        | 1        | 0.85%   |
| San Cesario di Lecce | 1        | 0.85%   |
| Rzeszów             | 1        | 0.85%   |
| Riverview            | 1        | 0.85%   |
| Rho                  | 1        | 0.85%   |
| Porto Alegre         | 1        | 0.85%   |
| Portimao             | 1        | 0.85%   |
| Porter               | 1        | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 40       | 65     | 15.44%  |
| Seagate                     | 39       | 66     | 15.06%  |
| WDC                         | 36       | 47     | 13.9%   |
| Sandisk                     | 21       | 25     | 8.11%   |
| Crucial                     | 14       | 17     | 5.41%   |
| Kingston                    | 13       | 18     | 5.02%   |
| Toshiba                     | 11       | 13     | 4.25%   |
| Hitachi                     | 6        | 6      | 2.32%   |
| Phison Electronics          | 5        | 5      | 1.93%   |
| Kingston Technology Company | 5        | 8      | 1.93%   |
| HGST                        | 5        | 6      | 1.93%   |
| A-DATA Technology           | 5        | 6      | 1.93%   |
| Intel                       | 4        | 5      | 1.54%   |
| SPCC                        | 3        | 7      | 1.16%   |
| Silicon Motion              | 3        | 4      | 1.16%   |
| PNY                         | 3        | 3      | 1.16%   |
| Patriot                     | 3        | 3      | 1.16%   |
| Maxtor                      | 3        | 3      | 1.16%   |
| Unknown                     | 2        | 2      | 0.77%   |
| Micron/Crucial Technology   | 2        | 4      | 0.77%   |
| Intenso                     | 2        | 3      | 0.77%   |
| Hewlett-Packard             | 2        | 3      | 0.77%   |
| Corsair                     | 2        | 2      | 0.77%   |
| China                       | 2        | 2      | 0.77%   |
| ADATA Technology            | 2        | 2      | 0.77%   |
| Unknown                     | 2        | 2      | 0.77%   |
| Vaseky                      | 1        | 1      | 0.39%   |
| Transcend                   | 1        | 1      | 0.39%   |
| Team                        | 1        | 1      | 0.39%   |
| SSI                         | 1        | 1      | 0.39%   |
| Smartbuy                    | 1        | 1      | 0.39%   |
| S3+                         | 1        | 1      | 0.39%   |
| Realtek Semiconductor       | 1        | 1      | 0.39%   |
| Plextor                     | 1        | 1      | 0.39%   |
| PHD 3.0                     | 1        | 1      | 0.39%   |
| OCZ                         | 1        | 1      | 0.39%   |
| Neo                         | 1        | 1      | 0.39%   |
| Micron Technology           | 1        | 1      | 0.39%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.39%   |
| Lexar                       | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                     | 7        | 2.25%   |
| Seagate ST4000DM004-2CV104 4TB                     | 5        | 1.61%   |
| Samsung SSD 860 EVO 500GB                          | 5        | 1.61%   |
| Seagate ST2000DM001-1ER164 2TB                     | 4        | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4        | 1.29%   |
| Seagate ST1000DM003-1ER162 1TB                     | 3        | 0.96%   |
| Seagate ST1000DM003-1CH162 1TB                     | 3        | 0.96%   |
| SanDisk NVMe SSD Drive 1TB                         | 3        | 0.96%   |
| Samsung SSD 980 1TB                                | 3        | 0.96%   |
| Samsung SSD 850 EVO 250GB                          | 3        | 0.96%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 3        | 0.96%   |
| Kingston SA400S37480G 480GB SSD                    | 3        | 0.96%   |
| Crucial CT250MX500SSD1 250GB                       | 3        | 0.96%   |
| WDC WD5000AAKX-60U6AA0 500GB                       | 2        | 0.64%   |
| WDC WD10EZEX-60WN4A0 1TB                           | 2        | 0.64%   |
| Toshiba DT01ACA100 1TB                             | 2        | 0.64%   |
| Seagate ST31000528AS 1TB                           | 2        | 0.64%   |
| Seagate ST2000DM001-1CH164 2TB                     | 2        | 0.64%   |
| Sandisk WD_BLACK SN850X 4000GB                     | 2        | 0.64%   |
| Sandisk WD_BLACK SN770 1TB                         | 2        | 0.64%   |
| Sandisk WD Black SN850 1024GB                      | 2        | 0.64%   |
| SanDisk SSD PLUS 1000GB                            | 2        | 0.64%   |
| Samsung SSD 980 PRO 2TB                            | 2        | 0.64%   |
| Samsung SSD 980 PRO 1TB                            | 2        | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB                     | 2        | 0.64%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2        | 0.64%   |
| Samsung SSD 870 QVO 2TB                            | 2        | 0.64%   |
| Samsung SSD 860 EVO 1TB                            | 2        | 0.64%   |
| Samsung SSD 850 PRO 512GB                          | 2        | 0.64%   |
| Samsung SSD 850 PRO 256GB                          | 2        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2        | 0.64%   |
| Samsung HD103SI 1TB                                | 2        | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 2        | 0.64%   |
| Kingston Company SNV2S1000G 1TB                    | 2        | 0.64%   |
| Kingston Company A2000 NVMe SSD 500GB              | 2        | 0.64%   |
| Kingston SA400S37240G 240GB SSD                    | 2        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                    | 2        | 0.64%   |
| Kingston SA400M8240G 240GB SSD                     | 2        | 0.64%   |
| Hitachi HDP725050GLA360 500GB                      | 2        | 0.64%   |
| Crucial CT1000BX500SSD1 1TB                        | 2        | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 63     | 37.76%  |
| WDC                 | 27       | 36     | 27.55%  |
| Toshiba             | 11       | 12     | 11.22%  |
| Hitachi             | 6        | 6      | 6.12%   |
| Samsung Electronics | 5        | 5      | 5.1%    |
| HGST                | 5        | 6      | 5.1%    |
| Maxtor              | 3        | 3      | 3.06%   |
| Unknown             | 1        | 1      | 1.02%   |
| SSI                 | 1        | 1      | 1.02%   |
| JMicron Technology  | 1        | 1      | 1.02%   |
| Apple               | 1        | 1      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 34     | 23.71%  |
| Kingston            | 12       | 17     | 12.37%  |
| Crucial             | 10       | 12     | 10.31%  |
| SanDisk             | 9        | 12     | 9.28%   |
| WDC                 | 7        | 8      | 7.22%   |
| PNY                 | 3        | 3      | 3.09%   |
| A-DATA Technology   | 3        | 4      | 3.09%   |
| SPCC                | 2        | 6      | 2.06%   |
| Seagate             | 2        | 2      | 2.06%   |
| Patriot             | 2        | 2      | 2.06%   |
| Intel               | 2        | 2      | 2.06%   |
| Hewlett-Packard     | 2        | 2      | 2.06%   |
| China               | 2        | 2      | 2.06%   |
| Vaseky              | 1        | 1      | 1.03%   |
| Transcend           | 1        | 1      | 1.03%   |
| Toshiba             | 1        | 1      | 1.03%   |
| Team                | 1        | 1      | 1.03%   |
| Smartbuy            | 1        | 1      | 1.03%   |
| S3+                 | 1        | 1      | 1.03%   |
| Plextor             | 1        | 1      | 1.03%   |
| PHD 3.0             | 1        | 1      | 1.03%   |
| OCZ                 | 1        | 1      | 1.03%   |
| Neo                 | 1        | 1      | 1.03%   |
| Micron Technology   | 1        | 1      | 1.03%   |
| INNOVATION IT       | 1        | 1      | 1.03%   |
| Hoodisk             | 1        | 1      | 1.03%   |
| Gigabyte Technology | 1        | 1      | 1.03%   |
| Emtec               | 1        | 2      | 1.03%   |
| CT1000MX            | 1        | 1      | 1.03%   |
| Corsair             | 1        | 1      | 1.03%   |
| AMD                 | 1        | 1      | 1.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 80       | 125    | 37.91%  |
| HDD     | 66       | 135    | 31.28%  |
| NVMe    | 58       | 84     | 27.49%  |
| Unknown | 6        | 7      | 2.84%   |
| MMC     | 1        | 1      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 100      | 252    | 58.82%  |
| NVMe | 58       | 84     | 34.12%  |
| SAS  | 11       | 15     | 6.47%   |
| MMC  | 1        | 1      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 75       | 111    | 43.1%   |
| 0.51-1.0   | 48       | 74     | 27.59%  |
| 1.01-2.0   | 29       | 43     | 16.67%  |
| 3.01-4.0   | 11       | 16     | 6.32%   |
| 4.01-10.0  | 9        | 14     | 5.17%   |
| 2.01-3.0   | 1        | 1      | 0.57%   |
| 10.01-20.0 | 1        | 1      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 26       | 22.22%  |
| More than 3000 | 22       | 18.8%   |
| 101-250        | 22       | 18.8%   |
| 251-500        | 16       | 13.68%  |
| 1001-2000      | 15       | 12.82%  |
| 2001-3000      | 8        | 6.84%   |
| 51-100         | 4        | 3.42%   |
| 21-50          | 2        | 1.71%   |
| 1-20           | 2        | 1.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 21       | 17.65%  |
| 501-1000       | 19       | 15.97%  |
| 251-500        | 17       | 14.29%  |
| 21-50          | 17       | 14.29%  |
| 1-20           | 15       | 12.61%  |
| 51-100         | 11       | 9.24%   |
| More than 3000 | 10       | 8.4%    |
| 1001-2000      | 7        | 5.88%   |
| 2001-3000      | 2        | 1.68%   |

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
| Detected | 70       | 205    | 51.47%  |
| Works    | 52       | 123    | 38.24%  |
| Malfunc  | 13       | 22     | 9.56%   |
| Failed   | 1        | 2      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 58       | 29.44%  |
| AMD                          | 57       | 28.93%  |
| Samsung Electronics          | 20       | 10.15%  |
| SanDisk                      | 15       | 7.61%   |
| ASMedia Technology           | 7        | 3.55%   |
| Phison Electronics           | 6        | 3.05%   |
| Micron/Crucial Technology    | 6        | 3.05%   |
| Silicon Motion               | 5        | 2.54%   |
| Kingston Technology Company  | 5        | 2.54%   |
| Realtek Semiconductor        | 3        | 1.52%   |
| Marvell Technology Group     | 3        | 1.52%   |
| JMicron Technology           | 3        | 1.52%   |
| ADATA Technology             | 3        | 1.52%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.02%   |
| VIA Technologies             | 1        | 0.51%   |
| Silicon Image                | 1        | 0.51%   |
| Shenzhen Longsys Electronics | 1        | 0.51%   |
| LSI Logic / Symbios Logic    | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28       | 11.86%  |
| AMD 500 Series Chipset SATA Controller                                                  | 13       | 5.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 5.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 4.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.97%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 2.97%   |
| AMD 600 Series Chipset SATA Controller                                                  | 7        | 2.97%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 6        | 2.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 2.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 2.12%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 2.12%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.69%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.69%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 3        | 1.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.27%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.27%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.27%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.85%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 2        | 0.85%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.85%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                                      | 2        | 0.85%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2        | 0.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.85%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.85%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.42%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.42%   |
| Shenzhen Longsys FORESEE XP2000, Lexar NM760 NVME SSD (DRAM-less)                       | 1        | 0.42%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                                      | 1        | 0.42%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 105      | 58.01%  |
| NVMe | 58       | 32.04%  |
| IDE  | 9        | 4.97%   |
| RAID | 8        | 4.42%   |
| SAS  | 1        | 0.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 58       | 50.43%  |
| AMD    | 57       | 49.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 6        | 5.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 4        | 3.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 3        | 2.61%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 3        | 2.61%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 2.61%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 2.61%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.74%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.74%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 2        | 1.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 1.74%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 1.74%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 2        | 1.74%   |
| Intel Core i5-3330 CPU @ 3.00GHz       | 2        | 1.74%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 2        | 1.74%   |
| AMD Ryzen 7 5700X 8-Core Processor     | 2        | 1.74%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 2        | 1.74%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 2        | 1.74%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 2        | 1.74%   |
| AMD FX-6300 Six-Core Processor         | 2        | 1.74%   |
| Intel Xeon W-2104 CPU @ 3.20GHz        | 1        | 0.87%   |
| Intel Xeon CPU W3580 @ 3.33GHz         | 1        | 0.87%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz    | 1        | 0.87%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz    | 1        | 0.87%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz | 1        | 0.87%   |
| Intel Pentium CPU N4200 @ 1.10GHz      | 1        | 0.87%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 0.87%   |
| Intel N100                             | 1        | 0.87%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 0.87%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 0.87%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 0.87%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 1        | 0.87%   |
| Intel Core i7-4960X CPU @ 3.60GHz      | 1        | 0.87%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 0.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1        | 0.87%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1        | 0.87%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 0.87%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 1        | 0.87%   |
| Intel Core i5-9600KF CPU @ 3.70GHz     | 1        | 0.87%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 0.87%   |
| Intel Core i5-8500 CPU @ 3.00GHz       | 1        | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| AMD Ryzen 5        | 22       | 19.13%  |
| Intel Core i7      | 20       | 17.39%  |
| Intel Core i5      | 18       | 15.65%  |
| AMD Ryzen 7        | 17       | 14.78%  |
| Other              | 8        | 6.96%   |
| AMD Ryzen 9        | 6        | 5.22%   |
| Intel Xeon         | 4        | 3.48%   |
| AMD FX             | 3        | 2.61%   |
| Intel Pentium      | 2        | 1.74%   |
| Intel Core i3      | 2        | 1.74%   |
| Intel Celeron      | 2        | 1.74%   |
| AMD Ryzen 5 PRO    | 2        | 1.74%   |
| AMD Phenom II X4   | 2        | 1.74%   |
| Intel Pentium Gold | 1        | 0.87%   |
| Intel Core i9      | 1        | 0.87%   |
| AMD Ryzen Embedded | 1        | 0.87%   |
| AMD Ryzen 3 PRO    | 1        | 0.87%   |
| AMD Phenom II X6   | 1        | 0.87%   |
| AMD Athlon II X3   | 1        | 0.87%   |
| AMD Athlon         | 1        | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 42       | 36.52%  |
| 6      | 35       | 30.43%  |
| 8      | 20       | 17.39%  |
| 2      | 7        | 6.09%   |
| 12     | 4        | 3.48%   |
| 16     | 3        | 2.61%   |
| 3      | 3        | 2.61%   |
| 10     | 1        | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 115      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 82       | 71.3%   |
| 1      | 33       | 28.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 115      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 90       | 76.92%  |
| 0x0a601203 | 6        | 5.13%   |
| 0x0a20120a | 3        | 2.56%   |
| 0x08701021 | 3        | 2.56%   |
| 0x0800820d | 2        | 1.71%   |
| 0x306c3    | 1        | 0.85%   |
| 0x0a50000d | 1        | 0.85%   |
| 0x0a50000c | 1        | 0.85%   |
| 0x0a201025 | 1        | 0.85%   |
| 0x08701030 | 1        | 0.85%   |
| 0x08701013 | 1        | 0.85%   |
| 0x08108109 | 1        | 0.85%   |
| 0x0810100b | 1        | 0.85%   |
| 0x08101007 | 1        | 0.85%   |
| 0x08001138 | 1        | 0.85%   |
| 0x0700010f | 1        | 0.85%   |
| 0x06000852 | 1        | 0.85%   |
| 0x010000dc | 1        | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 15       | 12.93%  |
| KabyLake         | 15       | 12.93%  |
| Haswell          | 12       | 10.34%  |
| Zen+             | 11       | 9.48%   |
| Zen 2            | 11       | 9.48%   |
| Unknown          | 11       | 9.48%   |
| SandyBridge      | 8        | 6.9%    |
| Zen              | 5        | 4.31%   |
| IvyBridge        | 5        | 4.31%   |
| K10              | 4        | 3.45%   |
| Skylake          | 3        | 2.59%   |
| Piledriver       | 3        | 2.59%   |
| Icelake          | 3        | 2.59%   |
| Nehalem          | 2        | 1.72%   |
| Alderlake Hybrid | 2        | 1.72%   |
| Westmere         | 1        | 0.86%   |
| Tremont          | 1        | 0.86%   |
| Jaguar           | 1        | 0.86%   |
| Goldmont         | 1        | 0.86%   |
| CometLake        | 1        | 0.86%   |
| Broadwell        | 1        | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 52       | 41.6%   |
| Nvidia | 45       | 36%     |
| Intel  | 28       | 22.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 9.3%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 5.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 4.65%   |
| AMD Raphael                                                                 | 6        | 4.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.1%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.33%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 2.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.55%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.55%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 1.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.55%   |
| Intel DG2 [Arc A380]                                                        | 2        | 1.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.55%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.55%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 1.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.78%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.78%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.78%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.78%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.78%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 0.78%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 44       | 38.26%  |
| 1 x Nvidia      | 40       | 34.78%  |
| 1 x Intel       | 20       | 17.39%  |
| 2 x AMD         | 3        | 2.61%   |
| Intel + AMD     | 3        | 2.61%   |
| Intel + Nvidia  | 2        | 1.74%   |
| 2 x Nvidia      | 1        | 0.87%   |
| Intel + 2 x AMD | 1        | 0.87%   |
| AMD + Nvidia    | 1        | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 77       | 66.38%  |
| Proprietary | 38       | 32.76%  |
| Unknown     | 1        | 0.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 42.74%  |
| 7.01-8.0   | 17       | 14.53%  |
| 1.01-2.0   | 12       | 10.26%  |
| 3.01-4.0   | 11       | 9.4%    |
| 8.01-16.0  | 8        | 6.84%   |
| 5.01-6.0   | 7        | 5.98%   |
| 0.01-0.5   | 5        | 4.27%   |
| 16.01-24.0 | 3        | 2.56%   |
| 2.01-3.0   | 2        | 1.71%   |
| 4.01-5.0   | 1        | 0.85%   |
| 0.51-1.0   | 1        | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 13.74%  |
| Dell                 | 15       | 11.45%  |
| Hewlett-Packard      | 11       | 8.4%    |
| Iiyama               | 10       | 7.63%   |
| Goldstar             | 9        | 6.87%   |
| Acer                 | 9        | 6.87%   |
| Ancor Communications | 8        | 6.11%   |
| Philips              | 7        | 5.34%   |
| ASUSTek Computer     | 6        | 4.58%   |
| BenQ                 | 5        | 3.82%   |
| AOC                  | 5        | 3.82%   |
| Eizo                 | 4        | 3.05%   |
| Lenovo               | 3        | 2.29%   |
| Gigabyte Technology  | 3        | 2.29%   |
| MSI                  | 2        | 1.53%   |
| Wacom                | 1        | 0.76%   |
| Vizio                | 1        | 0.76%   |
| VIZ                  | 1        | 0.76%   |
| ViewSonic            | 1        | 0.76%   |
| RTK                  | 1        | 0.76%   |
| ONN                  | 1        | 0.76%   |
| NEC Computers        | 1        | 0.76%   |
| Mi                   | 1        | 0.76%   |
| Medion Akoya         | 1        | 0.76%   |
| INS                  | 1        | 0.76%   |
| HYU                  | 1        | 0.76%   |
| HKC                  | 1        | 0.76%   |
| Haier                | 1        | 0.76%   |
| GDH                  | 1        | 0.76%   |
| DENON                | 1        | 0.76%   |
| CVT                  | 1        | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 1.33%   |
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                 | 2        | 1.33%   |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                  | 2        | 1.33%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 2        | 1.33%   |
| Ancor Communications MX259 ACI25C2 1920x1080 553x309mm 24.9-inch      | 2        | 1.33%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1        | 0.67%   |
| Vizio D32h-F0 VIZ1028 1366x768 697x392mm 31.5-inch                    | 1        | 0.67%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                    | 1        | 0.67%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 1        | 0.67%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch     | 1        | 0.67%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.67%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1        | 0.67%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch  | 1        | 0.67%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch    | 1        | 0.67%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch    | 1        | 0.67%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch     | 1        | 0.67%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1        | 0.67%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch     | 1        | 0.67%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 0.67%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch     | 1        | 0.67%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch     | 1        | 0.67%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch     | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 950x540mm 43.0-inch | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0992 1920x1080 700x390mm 31.5-inch | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 890x500mm 40.2-inch | 1        | 0.67%   |
| Samsung Electronics LCD Monitor SAM0679 1360x768 410x256mm 19.0-inch  | 1        | 0.67%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch    | 1        | 0.67%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 797x333mm 34.0-inch       | 1        | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 0.67%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 0.67%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch             | 1        | 0.67%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch              | 1        | 0.67%   |
| Philips PHL 240V5A PHLC10C 1920x1080 527x296mm 23.8-inch              | 1        | 0.67%   |
| Philips PHL 230B8Q PHL0936 1920x1200 488x297mm 22.5-inch              | 1        | 0.67%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1        | 0.67%   |
| Philips 27M1N3200V PHLC279 1920x1080 598x336mm 27.0-inch              | 1        | 0.67%   |
| Philips 191V PHL0887 1366x768 409x230mm 18.5-inch                     | 1        | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 46.51%  |
| 3840x2160 (4K)     | 21       | 16.28%  |
| 2560x1440 (QHD)    | 13       | 10.08%  |
| 1920x1200 (WUXGA)  | 6        | 4.65%   |
| 1440x900 (WXGA+)   | 5        | 3.88%   |
| 3440x1440          | 4        | 3.1%    |
| 2560x1080          | 4        | 3.1%    |
| 1600x900 (HD+)     | 4        | 3.1%    |
| 1366x768 (WXGA)    | 4        | 3.1%    |
| 1680x1050 (WSXGA+) | 3        | 2.33%   |
| 3840x1080          | 1        | 0.78%   |
| 2560x1600          | 1        | 0.78%   |
| 1360x768           | 1        | 0.78%   |
| 1280x1024 (SXGA)   | 1        | 0.78%   |
| Unknown            | 1        | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 30       | 22.22%  |
| 27      | 27       | 20%     |
| 23      | 15       | 11.11%  |
| 31      | 12       | 8.89%   |
| 21      | 10       | 7.41%   |
| 19      | 9        | 6.67%   |
| 34      | 7        | 5.19%   |
| 28      | 3        | 2.22%   |
| 22      | 3        | 2.22%   |
| 18      | 3        | 2.22%   |
| 46      | 2        | 1.48%   |
| 40      | 2        | 1.48%   |
| Unknown | 2        | 1.48%   |
| 84      | 1        | 0.74%   |
| 72      | 1        | 0.74%   |
| 69      | 1        | 0.74%   |
| 52      | 1        | 0.74%   |
| 43      | 1        | 0.74%   |
| 33      | 1        | 0.74%   |
| 26      | 1        | 0.74%   |
| 25      | 1        | 0.74%   |
| 20      | 1        | 0.74%   |
| 17      | 1        | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 67       | 51.94%  |
| 401-500     | 24       | 18.6%   |
| 601-700     | 18       | 13.95%  |
| 701-800     | 8        | 6.2%    |
| 1501-2000   | 3        | 2.33%   |
| 1001-1500   | 3        | 2.33%   |
| 801-900     | 2        | 1.55%   |
| Unknown     | 2        | 1.55%   |
| 301-350     | 1        | 0.78%   |
| 901-1000    | 1        | 0.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 89       | 76.07%  |
| 16/10   | 17       | 14.53%  |
| 21/9    | 8        | 6.84%   |
| Unknown | 2        | 1.71%   |
| 5/4     | 1        | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 31.58%  |
| 301-350        | 27       | 20.3%   |
| 351-500        | 22       | 16.54%  |
| 251-300        | 16       | 12.03%  |
| 151-200        | 11       | 8.27%   |
| 501-1000       | 5        | 3.76%   |
| More than 1000 | 4        | 3.01%   |
| 141-150        | 4        | 3.01%   |
| Unknown        | 2        | 1.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 76       | 63.33%  |
| 101-120 | 24       | 20%     |
| 121-160 | 11       | 9.17%   |
| 1-50    | 4        | 3.33%   |
| 161-240 | 3        | 2.5%    |
| Unknown | 2        | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 69.57%  |
| 2     | 28       | 24.35%  |
| 3     | 6        | 5.22%   |
| 4     | 1        | 0.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 84       | 49.7%   |
| Intel                             | 39       | 23.08%  |
| MediaTek                          | 9        | 5.33%   |
| TP-Link                           | 6        | 3.55%   |
| Qualcomm Atheros                  | 6        | 3.55%   |
| Broadcom                          | 5        | 2.96%   |
| ASUSTek Computer                  | 4        | 2.37%   |
| Ralink                            | 3        | 1.78%   |
| Arduino SA                        | 2        | 1.18%   |
| Van Ooijen Technische Informatica | 1        | 0.59%   |
| Texas Instruments                 | 1        | 0.59%   |
| Tehuti Networks                   | 1        | 0.59%   |
| QinHeng Electronics               | 1        | 0.59%   |
| NetGear                           | 1        | 0.59%   |
| Microsoft                         | 1        | 0.59%   |
| Linksys                           | 1        | 0.59%   |
| Huawei Technologies               | 1        | 0.59%   |
| Google                            | 1        | 0.59%   |
| D-Link System                     | 1        | 0.59%   |
| Aquantia                          | 1        | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 55       | 29.73%  |
| Realtek RTL8125 2.5GbE Controller                                             | 19       | 10.27%  |
| Intel I211 Gigabit Network Connection                                         | 10       | 5.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 5        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 2.16%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.16%   |
| Intel Ethernet Connection (7) I219-V                                          | 4        | 2.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.62%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 1.08%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 1.08%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 1.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 1.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2        | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.08%   |
| Realtek 802.11ac NIC                                                          | 2        | 1.08%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 1.08%   |
| Intel Wireless 7265                                                           | 2        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 1.08%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.08%   |
| ASUS 802.11ac NIC                                                             | 2        | 1.08%   |
| Van Ooijen Technische Informatica Teensyduino Serial                          | 1        | 0.54%   |
| TP-Link 802.11n NIC                                                           | 1        | 0.54%   |
| Texas Instruments TI CC2540 USB CDC                                           | 1        | 0.54%   |
| Tehuti Networks TN9210 10GBase-T Ethernet Adapter                             | 1        | 0.54%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 0.54%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.54%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.54%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.54%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 0.54%   |
| QinHeng USB Single Serial                                                     | 1        | 0.54%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                               | 1        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 23.64%  |
| Intel                 | 10       | 18.18%  |
| MediaTek              | 8        | 14.55%  |
| TP-Link               | 6        | 10.91%  |
| Qualcomm Atheros      | 5        | 9.09%   |
| ASUSTek Computer      | 4        | 7.27%   |
| Ralink                | 3        | 5.45%   |
| Broadcom              | 2        | 3.64%   |
| NetGear               | 1        | 1.82%   |
| Microsoft             | 1        | 1.82%   |
| Linksys               | 1        | 1.82%   |
| D-Link System         | 1        | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 5        | 8.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 3.57%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 3.57%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 3.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 3.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 3.57%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 3.57%   |
| Realtek 802.11ac NIC                                                          | 2        | 3.57%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 3.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 3.57%   |
| Intel Wireless 7265                                                           | 2        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 3.57%   |
| ASUS 802.11ac NIC                                                             | 2        | 3.57%   |
| TP-Link 802.11n NIC                                                           | 1        | 1.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 1.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 1.79%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 1.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.79%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.79%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                               | 1        | 1.79%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 1        | 1.79%   |
| MediaTek WiFi                                                                 | 1        | 1.79%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                     | 1        | 1.79%   |
| Intel Wireless 8260                                                           | 1        | 1.79%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 1.79%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.79%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 1.79%   |
| Intel CNVi: Wi-Fi                                                             | 1        | 1.79%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]    | 1        | 1.79%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.79%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.79%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                | 1        | 1.79%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 80       | 65.04%  |
| Intel                 | 33       | 26.83%  |
| Broadcom              | 3        | 2.44%   |
| Qualcomm Atheros      | 2        | 1.63%   |
| Tehuti Networks       | 1        | 0.81%   |
| MediaTek              | 1        | 0.81%   |
| Huawei Technologies   | 1        | 0.81%   |
| Google                | 1        | 0.81%   |
| Aquantia              | 1        | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 55       | 44.35%  |
| Realtek RTL8125 2.5GbE Controller                                              | 19       | 15.32%  |
| Intel I211 Gigabit Network Connection                                          | 10       | 8.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4        | 3.23%   |
| Intel Ethernet Controller I225-V                                               | 4        | 3.23%   |
| Intel Ethernet Connection (7) I219-V                                           | 4        | 3.23%   |
| Intel Ethernet Connection (2) I219-V                                           | 4        | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 2.42%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 1.61%   |
| Tehuti Networks TN9210 10GBase-T Ethernet Adapter                              | 1        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.81%   |
| MediaTek File-CD Gadget                                                        | 1        | 0.81%   |
| Intel Ethernet Controller I219-V                                               | 1        | 0.81%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.81%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 0.81%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 0.81%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.81%   |
| Huawei STG-LX1                                                                 | 1        | 0.81%   |
| Google Pixel 8                                                                 | 1        | 0.81%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                        | 1        | 0.81%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1        | 0.81%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 1        | 0.81%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 114      | 67.46%  |
| WiFi     | 51       | 30.18%  |
| Modem    | 4        | 2.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 94       | 75.2%   |
| WiFi     | 31       | 24.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 68.97%  |
| 2     | 31       | 26.72%  |
| 3     | 2        | 1.72%   |
| 0     | 2        | 1.72%   |
| 5     | 1        | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 80       | 68.97%  |
| Yes  | 36       | 31.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 14       | 28%     |
| Intel                           | 11       | 22%     |
| Realtek Semiconductor           | 7        | 14%     |
| MediaTek                        | 5        | 10%     |
| ASUSTek Computer                | 3        | 6%      |
| TP-Link                         | 2        | 4%      |
| Qualcomm Atheros Communications | 2        | 4%      |
| Realtek                         | 1        | 2%      |
| Logitech                        | 1        | 2%      |
| Lite-On Technology              | 1        | 2%      |
| IMC Networks                    | 1        | 2%      |
| Foxconn / Hon Hai               | 1        | 2%      |
| Broadcom                        | 1        | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 28%     |
| Realtek Bluetooth Radio                             | 7        | 14%     |
| MediaTek Wireless_Device                            | 5        | 10%     |
| Intel Bluetooth wireless interface                  | 3        | 6%      |
| TP-Link UB500 Adapter                               | 2        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4%      |
| Intel AX210 Bluetooth                               | 2        | 4%      |
| Intel AX201 Bluetooth                               | 2        | 4%      |
| Realtek Bluetooth Radio                             | 1        | 2%      |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2%      |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 2%      |
| Lite-On Bluetooth Device                            | 1        | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2%      |
| Intel AX200 Bluetooth                               | 1        | 2%      |
| IMC Networks BCM20702A0                             | 1        | 2%      |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 2%      |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 2%      |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 2%      |
| ASUS Bluetooth Radio                                | 1        | 2%      |
| ASUS ASUS USB-BT500                                 | 1        | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 71       | 31.84%  |
| Intel                     | 60       | 26.91%  |
| Nvidia                    | 44       | 19.73%  |
| C-Media Electronics       | 8        | 3.59%   |
| Logitech                  | 6        | 2.69%   |
| Focusrite-Novation        | 4        | 1.79%   |
| Texas Instruments         | 3        | 1.35%   |
| Generalplus Technology    | 3        | 1.35%   |
| VIA Technologies          | 2        | 0.9%    |
| SteelSeries ApS           | 2        | 0.9%    |
| SAVITECH                  | 2        | 0.9%    |
| Micro Star International  | 2        | 0.9%    |
| Creative Labs             | 2        | 0.9%    |
| Trust                     | 1        | 0.45%   |
| TEAC                      | 1        | 0.45%   |
| Sennheiser Communications | 1        | 0.45%   |
| Realtek Semiconductor     | 1        | 0.45%   |
| Mackie Designs            | 1        | 0.45%   |
| JMTek                     | 1        | 0.45%   |
| GN Netcom                 | 1        | 0.45%   |
| Dell                      | 1        | 0.45%   |
| Creative Technology       | 1        | 0.45%   |
| Corsair                   | 1        | 0.45%   |
| AudioQuest                | 1        | 0.45%   |
| ASUSTek Computer          | 1        | 0.45%   |
| Asahi Kasei Microsystems  | 1        | 0.45%   |
| 2.4G Composite Device     | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 21       | 7.81%   |
| AMD Family 17h/19h HD Audio Controller                                     | 18       | 6.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12       | 4.46%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 4.09%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 2.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 2.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 2.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.23%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 1.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.49%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.49%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.12%   |
| Generalplus Technology USB Audio Device                                    | 3        | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.12%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 2        | 0.74%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.74%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.74%   |
| Micro Star International USB Audio                                         | 2        | 0.74%   |
| Intel DG2 Audio Controller                                                 | 2        | 0.74%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.74%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.74%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 2        | 0.74%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 16       | 23.19%  |
| Corsair             | 10       | 14.49%  |
| G.Skill             | 9        | 13.04%  |
| Samsung Electronics | 8        | 11.59%  |
| Crucial             | 6        | 8.7%    |
| SK hynix            | 3        | 4.35%   |
| Patriot             | 3        | 4.35%   |
| A-DATA Technology   | 3        | 4.35%   |
| Unknown             | 2        | 2.9%    |
| Team                | 2        | 2.9%    |
| Micron Technology   | 2        | 2.9%    |
| Unknown (ABCD)      | 1        | 1.45%   |
| Ramaxel Technology  | 1        | 1.45%   |
| Nanya Technology    | 1        | 1.45%   |
| Atermiter           | 1        | 1.45%   |
| Unknown             | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s            | 2        | 2.78%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 2        | 2.78%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 2        | 2.78%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 2.78%   |
| Unknown RAM Module 8GB DIMM 667MT/s                            | 1        | 1.39%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1        | 1.39%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 1.39%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s        | 1        | 1.39%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 1.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1        | 1.39%   |
| Samsung RAM M391B5773CH0-YH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.39%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 1.39%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s            | 1        | 1.39%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 1        | 1.39%   |
| Samsung RAM M378A2G43AB3-CWE 16GB DIMM DDR4 3200MT/s           | 1        | 1.39%   |
| Samsung RAM 53D512M64D4RQ-046 4GB Row Of Chips LPDDR4 4267MT/s | 1        | 1.39%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2400MT/s         | 1        | 1.39%   |
| Patriot RAM PSD44G240041 4GB DIMM DDR4 2400MT/s                | 1        | 1.39%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.39%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1        | 1.39%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 1.39%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s           | 1        | 1.39%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s         | 1        | 1.39%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1600MT/s         | 1        | 1.39%   |
| Kingston RAM KF560C36-32 32GB DIMM DDR5 4800MT/s               | 1        | 1.39%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s               | 1        | 1.39%   |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 6400MT/s               | 1        | 1.39%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s          | 1        | 1.39%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 1        | 1.39%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 1        | 1.39%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s             | 1        | 1.39%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 1.39%   |
| Kingston RAM 9965646-035.B00G 8GB SODIMM DDR4 2933MT/s         | 1        | 1.39%   |
| Kingston RAM 9905678-042.A00G 8GB DIMM DDR4 2400MT/s           | 1        | 1.39%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.39%   |
| Kingston RAM 9905403-038.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 38       | 62.3%   |
| DDR3    | 14       | 22.95%  |
| DDR5    | 6        | 9.84%   |
| LPDDR4  | 2        | 3.28%   |
| Unknown | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 57       | 93.44%  |
| SODIMM       | 3        | 4.92%   |
| Row Of Chips | 1        | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 24       | 36.36%  |
| 16384 | 22       | 33.33%  |
| 4096  | 13       | 19.7%   |
| 32768 | 5        | 7.58%   |
| 2048  | 2        | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 11       | 15.94%  |
| 2400  | 10       | 14.49%  |
| 3600  | 9        | 13.04%  |
| 1333  | 5        | 7.25%   |
| 1800  | 4        | 5.8%    |
| 2667  | 3        | 4.35%   |
| 1600  | 3        | 4.35%   |
| 6400  | 2        | 2.9%    |
| 6000  | 2        | 2.9%    |
| 4800  | 2        | 2.9%    |
| 3733  | 2        | 2.9%    |
| 2933  | 2        | 2.9%    |
| 2666  | 2        | 2.9%    |
| 2133  | 2        | 2.9%    |
| 4267  | 1        | 1.45%   |
| 3800  | 1        | 1.45%   |
| 3666  | 1        | 1.45%   |
| 3400  | 1        | 1.45%   |
| 3334  | 1        | 1.45%   |
| 3266  | 1        | 1.45%   |
| 3066  | 1        | 1.45%   |
| 2473  | 1        | 1.45%   |
| 1866  | 1        | 1.45%   |
| 667   | 1        | 1.45%   |

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
| USB Camera                    | 1        | 3.7%    |
| Trust                         | 1        | 3.7%    |
| Sunplus Innovation Technology | 1        | 3.7%    |
| Realtek Semiconductor         | 1        | 3.7%    |
| OPPO Electronics              | 1        | 3.7%    |
| Microsoft                     | 1        | 3.7%    |
| MacroSilicon                  | 1        | 3.7%    |
| Jieli Technology              | 1        | 3.7%    |
| Generalplus Technology        | 1        | 3.7%    |
| GEMBIRD                       | 1        | 3.7%    |
| Chicony Electronics           | 1        | 3.7%    |
| AVerMedia Technologies        | 1        | 3.7%    |
| A4Tech                        | 1        | 3.7%    |
| 04004000_P040200_SN0002       | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 7.41%   |
| Microdia Webcam Vitade AF                         | 2        | 7.41%   |
| Microdia USB 2.0 Camera                           | 2        | 7.41%   |
| Microdia Camera                                   | 2        | 7.41%   |
| USB Camera USB Camera                             | 1        | 3.7%    |
| Trust Full HD Webcam                              | 1        | 3.7%    |
| Sunplus FHD Camera Microphone                     | 1        | 3.7%    |
| Realtek Full HD webcam                            | 1        | 3.7%    |
| OPPO Oppo N1                                      | 1        | 3.7%    |
| Microsoft LifeCam Cinema                          | 1        | 3.7%    |
| MacroSilicon USB3. 0 capture                      | 1        | 3.7%    |
| Logitech Webcam C270                              | 1        | 3.7%    |
| Logitech HD Webcam C615                           | 1        | 3.7%    |
| Logitech C922 Pro Stream Webcam                   | 1        | 3.7%    |
| Logitech C920 PRO HD Webcam                       | 1        | 3.7%    |
| Logitech BRIO Ultra HD Webcam                     | 1        | 3.7%    |
| Jieli USB PHY 2.0                                 | 1        | 3.7%    |
| Generalplus 808 Camera                            | 1        | 3.7%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 3.7%    |
| Chicony HP High Definition 1MP Webcam             | 1        | 3.7%    |
| AVerMedia PW310O Webcam                           | 1        | 3.7%    |
| A4Tech FHD 1080P PC Camera                        | 1        | 3.7%    |
| 04004000_P040200_SN0002 1080P Web Camera          | 1        | 3.7%    |

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
| 0     | 100      | 85.47%  |
| 1     | 15       | 12.82%  |
| 3     | 1        | 0.85%   |
| 2     | 1        | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 6        | 35.29%  |
| Graphics card            | 3        | 17.65%  |
| Unassigned class         | 2        | 11.76%  |
| Communication controller | 2        | 11.76%  |
| Storage/raid             | 1        | 5.88%   |
| Sound                    | 1        | 5.88%   |
| Net/ethernet             | 1        | 5.88%   |
| Camera                   | 1        | 5.88%   |

