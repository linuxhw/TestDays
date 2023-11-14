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

Total: 142

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 6.2.0-20-generic       | 17       | 14.78%  |
| 6.2.0-27-generic       | 14       | 12.17%  |
| 6.2.0-34-generic       | 12       | 10.43%  |
| 6.2.0-32-generic       | 9        | 7.83%   |
| 6.2.0-33-generic       | 8        | 6.96%   |
| 6.2.0-24-generic       | 8        | 6.96%   |
| 6.2.0-26-generic       | 6        | 5.22%   |
| 6.2.0-23-generic       | 6        | 5.22%   |
| 6.2.0-25-generic       | 5        | 4.35%   |
| 6.2.0-31-generic       | 4        | 3.48%   |
| 6.2.0-1003-lowlatency  | 3        | 2.61%   |
| 6.2.0-36-generic       | 2        | 1.74%   |
| 6.2.0-35-generic       | 2        | 1.74%   |
| 6.2.0-1013-lowlatency  | 2        | 1.74%   |
| 6.5.1-060501-generic   | 1        | 0.87%   |
| 6.4.6-060406-generic   | 1        | 0.87%   |
| 6.4.3-1-liquorix-amd64 | 1        | 0.87%   |
| 6.4.1-2-liquorix-amd64 | 1        | 0.87%   |
| 6.4.0-060400-generic   | 1        | 0.87%   |
| 6.3.5-060305-generic   | 1        | 0.87%   |
| 6.3.10                 | 1        | 0.87%   |
| 6.2.5-060205-generic   | 1        | 0.87%   |
| 6.2.0-1015-lowlatency  | 1        | 0.87%   |
| 6.2.0-1014-lowlatency  | 1        | 0.87%   |
| 6.2.0-1009-lowlatency  | 1        | 0.87%   |
| 6.2.0-1008-lowlatency  | 1        | 0.87%   |
| 6.2.0-1007-lowlatency  | 1        | 0.87%   |
| 6.1.0-16-generic       | 1        | 0.87%   |
| 5.19.0-42-generic      | 1        | 0.87%   |
| 5.19.0-28-generic      | 1        | 0.87%   |
| 5.19.0-1023-lowlatency | 1        | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 99       | 89.19%  |
| 5.19.0  | 3        | 2.7%    |
| 6.5.1   | 1        | 0.9%    |
| 6.4.6   | 1        | 0.9%    |
| 6.4.3   | 1        | 0.9%    |
| 6.4.1   | 1        | 0.9%    |
| 6.4.0   | 1        | 0.9%    |
| 6.3.5   | 1        | 0.9%    |
| 6.3.10  | 1        | 0.9%    |
| 6.2.5   | 1        | 0.9%    |
| 6.1.0   | 1        | 0.9%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 100      | 90.09%  |
| 6.4     | 4        | 3.6%    |
| 5.19    | 3        | 2.7%    |
| 6.3     | 2        | 1.8%    |
| 6.5     | 1        | 0.9%    |
| 6.1     | 1        | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 109      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 106      | 97.25%  |
| KDE  | 3        | 2.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 92       | 83.64%  |
| Wayland | 17       | 15.45%  |
| Tty     | 1        | 0.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 67       | 60.91%  |
| Unknown | 40       | 36.36%  |
| GDM3    | 2        | 1.82%   |
| LightDM | 1        | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 47       | 42.73%  |
| de_DE | 13       | 11.82%  |
| it_IT | 8        | 7.27%   |
| fr_FR | 8        | 7.27%   |
| en_GB | 8        | 7.27%   |
| ru_RU | 5        | 4.55%   |
| pt_BR | 3        | 2.73%   |
| sv_SE | 2        | 1.82%   |
| pl_PL | 2        | 1.82%   |
| en_CA | 2        | 1.82%   |
| C     | 2        | 1.82%   |
| zh_TW | 1        | 0.91%   |
| fr_BE | 1        | 0.91%   |
| es_MX | 1        | 0.91%   |
| es_ES | 1        | 0.91%   |
| es_CO | 1        | 0.91%   |
| es_CL | 1        | 0.91%   |
| en_IN | 1        | 0.91%   |
| en_IL | 1        | 0.91%   |
| de_CH | 1        | 0.91%   |
| da_DK | 1        | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 64       | 58.18%  |
| EFI  | 46       | 41.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 79       | 72.48%  |
| Tmpfs   | 20       | 18.35%  |
| Btrfs   | 8        | 7.34%   |
| Overlay | 1        | 0.92%   |
| F2fs    | 1        | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 64       | 58.18%  |
| Unknown | 39       | 35.45%  |
| MBR     | 7        | 6.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 75.23%  |
| Yes       | 27       | 24.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 66.97%  |
| Yes       | 36       | 33.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 35       | 32.11%  |
| Gigabyte Technology | 19       | 17.43%  |
| MSI                 | 17       | 15.6%   |
| ASRock              | 9        | 8.26%   |
| Hewlett-Packard     | 4        | 3.67%   |
| Dell                | 4        | 3.67%   |
| Intel               | 3        | 2.75%   |
| Lenovo              | 2        | 1.83%   |
| Fujitsu             | 2        | 1.83%   |
| Unknown             | 2        | 1.83%   |
| Seco                | 1        | 0.92%   |
| Pegatron            | 1        | 0.92%   |
| Huanan              | 1        | 0.92%   |
| Google              | 1        | 0.92%   |
| Gateway             | 1        | 0.92%   |
| Foxconn             | 1        | 0.92%   |
| Colorful Technology | 1        | 0.92%   |
| Biostar             | 1        | 0.92%   |
| BESSTAR Tech        | 1        | 0.92%   |
| AZW                 | 1        | 0.92%   |
| Alienware           | 1        | 0.92%   |
| Acer                | 1        | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| MSI MS-7D75                                 | 2        | 1.83%   |
| MSI MS-7C95                                 | 2        | 1.83%   |
| MSI MS-7C56                                 | 2        | 1.83%   |
| MSI MS-7B86                                 | 2        | 1.83%   |
| Gigabyte B550 AORUS ELITE V2                | 2        | 1.83%   |
| ASUS TUF Gaming B550-PLUS                   | 2        | 1.83%   |
| ASUS ROG STRIX B550-F GAMING                | 2        | 1.83%   |
| ASUS All Series                             | 2        | 1.83%   |
| Unknown                                     | 2        | 1.83%   |
| Seco C40                                    | 1        | 0.92%   |
| Pegatron 520-1000nl                         | 1        | 0.92%   |
| MSI MS-7D74                                 | 1        | 0.92%   |
| MSI MS-7D17                                 | 1        | 0.92%   |
| MSI MS-7C37                                 | 1        | 0.92%   |
| MSI MS-7B24                                 | 1        | 0.92%   |
| MSI MS-7B23                                 | 1        | 0.92%   |
| MSI MS-7A32                                 | 1        | 0.92%   |
| MSI MS-7924                                 | 1        | 0.92%   |
| MSI MS-7846                                 | 1        | 0.92%   |
| MSI MS-7693                                 | 1        | 0.92%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T100BHMZ | 1        | 0.92%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS      | 1        | 0.92%   |
| Intel SHARKBAY                              | 1        | 0.92%   |
| Intel H61                                   | 1        | 0.92%   |
| Intel H55                                   | 1        | 0.92%   |
| Huanan X99-F8 GAMING V5.0                   | 1        | 0.92%   |
| HP Z220 CMT Workstation                     | 1        | 0.92%   |
| HP EliteDesk 705 G4 DM 35W (TAA)            | 1        | 0.92%   |
| HP Compaq Elite 8300 SFF                    | 1        | 0.92%   |
| HP 870-119                                  | 1        | 0.92%   |
| Google Zako                                 | 1        | 0.92%   |
| Gigabyte Z390 M GAMING                      | 1        | 0.92%   |
| Gigabyte Z390 GAMING X                      | 1        | 0.92%   |
| Gigabyte Z370P D3                           | 1        | 0.92%   |
| Gigabyte X570S UD                           | 1        | 0.92%   |
| Gigabyte X570S AORUS ELITE AX               | 1        | 0.92%   |
| Gigabyte X470 AORUS ULTRA GAMING            | 1        | 0.92%   |
| Gigabyte H87-HD3                            | 1        | 0.92%   |
| Gigabyte GA-MA770-US3                       | 1        | 0.92%   |
| Gigabyte GA-970A-DS3                        | 1        | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 14       | 12.84%  |
| ASUS ROG              | 7        | 6.42%   |
| Gigabyte B550         | 4        | 3.67%   |
| ASUS TUF              | 4        | 3.67%   |
| MSI MS-7D75           | 2        | 1.83%   |
| MSI MS-7C95           | 2        | 1.83%   |
| MSI MS-7C56           | 2        | 1.83%   |
| MSI MS-7B86           | 2        | 1.83%   |
| Lenovo IdeaCentre     | 2        | 1.83%   |
| Gigabyte Z390         | 2        | 1.83%   |
| Gigabyte X570S        | 2        | 1.83%   |
| Gigabyte B365M        | 2        | 1.83%   |
| Dell Precision        | 2        | 1.83%   |
| ASUS Maximus          | 2        | 1.83%   |
| ASUS All              | 2        | 1.83%   |
| Unknown               | 2        | 1.83%   |
| Seco C40              | 1        | 0.92%   |
| Pegatron 520-1000nl   | 1        | 0.92%   |
| MSI MS-7D74           | 1        | 0.92%   |
| MSI MS-7D17           | 1        | 0.92%   |
| MSI MS-7C37           | 1        | 0.92%   |
| MSI MS-7B24           | 1        | 0.92%   |
| MSI MS-7B23           | 1        | 0.92%   |
| MSI MS-7A32           | 1        | 0.92%   |
| MSI MS-7924           | 1        | 0.92%   |
| MSI MS-7846           | 1        | 0.92%   |
| MSI MS-7693           | 1        | 0.92%   |
| Intel SHARKBAY        | 1        | 0.92%   |
| Intel H61             | 1        | 0.92%   |
| Intel H55             | 1        | 0.92%   |
| Huanan X99-F8         | 1        | 0.92%   |
| HP Z220               | 1        | 0.92%   |
| HP EliteDesk          | 1        | 0.92%   |
| HP Compaq             | 1        | 0.92%   |
| HP 870-119            | 1        | 0.92%   |
| Google Zako           | 1        | 0.92%   |
| Gigabyte Z370P        | 1        | 0.92%   |
| Gigabyte X470         | 1        | 0.92%   |
| Gigabyte H87-HD3      | 1        | 0.92%   |
| Gigabyte GA-MA770-US3 | 1        | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 17       | 15.6%   |
| 2019 | 17       | 15.6%   |
| 2018 | 14       | 12.84%  |
| 2022 | 12       | 11.01%  |
| 2021 | 9        | 8.26%   |
| 2017 | 7        | 6.42%   |
| 2012 | 7        | 6.42%   |
| 2011 | 7        | 6.42%   |
| 2014 | 6        | 5.5%    |
| 2013 | 4        | 3.67%   |
| 2023 | 2        | 1.83%   |
| 2016 | 2        | 1.83%   |
| 2010 | 2        | 1.83%   |
| 2009 | 2        | 1.83%   |
| 2015 | 1        | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 109      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 107      | 98.17%  |
| Enabled  | 2        | 1.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 108      | 99.08%  |
| Yes  | 1        | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 30       | 27.52%  |
| 32.01-64.0  | 29       | 26.61%  |
| 8.01-16.0   | 16       | 14.68%  |
| 4.01-8.0    | 14       | 12.84%  |
| 24.01-32.0  | 8        | 7.34%   |
| 64.01-256.0 | 8        | 7.34%   |
| 3.01-4.0    | 4        | 3.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 38       | 32.76%  |
| 2.01-3.0   | 25       | 21.55%  |
| 3.01-4.0   | 23       | 19.83%  |
| 1.01-2.0   | 16       | 13.79%  |
| 8.01-16.0  | 11       | 9.48%   |
| 16.01-24.0 | 3        | 2.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 29       | 26.36%  |
| 3      | 24       | 21.82%  |
| 1      | 24       | 21.82%  |
| 4      | 19       | 17.27%  |
| 5      | 6        | 5.45%   |
| 6      | 4        | 3.64%   |
| 8      | 2        | 1.82%   |
| 7      | 2        | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 64.55%  |
| Yes       | 39       | 35.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 109      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 55.05%  |
| Yes       | 49       | 44.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 57.8%   |
| Yes       | 46       | 42.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 23       | 21.1%   |
| Germany      | 15       | 13.76%  |
| UK           | 9        | 8.26%   |
| France       | 9        | 8.26%   |
| Italy        | 7        | 6.42%   |
| Russia       | 5        | 4.59%   |
| Canada       | 5        | 4.59%   |
| Switzerland  | 4        | 3.67%   |
| Poland       | 4        | 3.67%   |
| Sweden       | 3        | 2.75%   |
| Brazil       | 3        | 2.75%   |
| Turkey       | 2        | 1.83%   |
| Spain        | 2        | 1.83%   |
| Serbia       | 2        | 1.83%   |
| Netherlands  | 2        | 1.83%   |
| Taiwan       | 1        | 0.92%   |
| Saudi Arabia | 1        | 0.92%   |
| Romania      | 1        | 0.92%   |
| Portugal     | 1        | 0.92%   |
| Mexico       | 1        | 0.92%   |
| Kazakhstan   | 1        | 0.92%   |
| Israel       | 1        | 0.92%   |
| Indonesia    | 1        | 0.92%   |
| India        | 1        | 0.92%   |
| Denmark      | 1        | 0.92%   |
| Colombia     | 1        | 0.92%   |
| Chile        | 1        | 0.92%   |
| Belgium      | 1        | 0.92%   |
| Bangladesh   | 1        | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| London               | 3        | 2.7%    |
| Virginia Beach       | 2        | 1.8%    |
| Oberburg             | 2        | 1.8%    |
| Hamburg              | 2        | 1.8%    |
| Florence             | 2        | 1.8%    |
| Arzamas              | 2        | 1.8%    |
| Zuchwil              | 1        | 0.9%    |
| Wiesmoor             | 1        | 0.9%    |
| West Valley          | 1        | 0.9%    |
| Wellsboro            | 1        | 0.9%    |
| Weilmuenster         | 1        | 0.9%    |
| Warsaw               | 1        | 0.9%    |
| Victoria             | 1        | 0.9%    |
| Vaggeryd             | 1        | 0.9%    |
| Ufa                  | 1        | 0.9%    |
| Uelversheim          | 1        | 0.9%    |
| Tilburg              | 1        | 0.9%    |
| The Hague            | 1        | 0.9%    |
| Taichung             | 1        | 0.9%    |
| Sutton               | 1        | 0.9%    |
| Sundsvall            | 1        | 0.9%    |
| Strasbourg           | 1        | 0.9%    |
| Stone Mountain       | 1        | 0.9%    |
| Simpsonville         | 1        | 0.9%    |
| Sibiu                | 1        | 0.9%    |
| Sherbrooke           | 1        | 0.9%    |
| Saskatoon            | 1        | 0.9%    |
| Saro                 | 1        | 0.9%    |
| Sao Paulo            | 1        | 0.9%    |
| Santiago             | 1        | 0.9%    |
| San Jose             | 1        | 0.9%    |
| San Francisco        | 1        | 0.9%    |
| San Cesario di Lecce | 1        | 0.9%    |
| Rzeszów             | 1        | 0.9%    |
| Rho                  | 1        | 0.9%    |
| Porto Alegre         | 1        | 0.9%    |
| Portimao             | 1        | 0.9%    |
| Porter               | 1        | 0.9%    |
| Pontarlier           | 1        | 0.9%    |
| Polkowice            | 1        | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 38       | 63     | 15.38%  |
| Samsung Electronics         | 37       | 61     | 14.98%  |
| WDC                         | 35       | 46     | 14.17%  |
| SanDisk                     | 20       | 24     | 8.1%    |
| Crucial                     | 14       | 17     | 5.67%   |
| Kingston                    | 13       | 18     | 5.26%   |
| Toshiba                     | 11       | 13     | 4.45%   |
| Hitachi                     | 6        | 6      | 2.43%   |
| Phison Electronics          | 5        | 5      | 2.02%   |
| Kingston Technology Company | 5        | 8      | 2.02%   |
| HGST                        | 5        | 6      | 2.02%   |
| Intel                       | 4        | 5      | 1.62%   |
| A-DATA Technology           | 4        | 5      | 1.62%   |
| SPCC                        | 3        | 7      | 1.21%   |
| Silicon Motion              | 3        | 4      | 1.21%   |
| PNY                         | 3        | 3      | 1.21%   |
| Patriot                     | 3        | 3      | 1.21%   |
| Micron/Crucial Technology   | 2        | 4      | 0.81%   |
| Maxtor                      | 2        | 2      | 0.81%   |
| Intenso                     | 2        | 3      | 0.81%   |
| Hewlett-Packard             | 2        | 3      | 0.81%   |
| Corsair                     | 2        | 2      | 0.81%   |
| China                       | 2        | 2      | 0.81%   |
| ADATA Technology            | 2        | 2      | 0.81%   |
| Unknown                     | 2        | 2      | 0.81%   |
| Vaseky                      | 1        | 1      | 0.4%    |
| Unknown                     | 1        | 1      | 0.4%    |
| Transcend                   | 1        | 1      | 0.4%    |
| Team                        | 1        | 1      | 0.4%    |
| Smartbuy                    | 1        | 1      | 0.4%    |
| S3+                         | 1        | 1      | 0.4%    |
| Realtek Semiconductor       | 1        | 1      | 0.4%    |
| PHD 3.0                     | 1        | 1      | 0.4%    |
| Neo                         | 1        | 1      | 0.4%    |
| Micron Technology           | 1        | 1      | 0.4%    |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.4%    |
| Lexar                       | 1        | 1      | 0.4%    |
| JMicron Technology          | 1        | 1      | 0.4%    |
| INNOVATION IT               | 1        | 1      | 0.4%    |
| HS-SSD-E100                 | 1        | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB                                    | 7        | 2.36%   |
| Seagate ST4000DM004-2CV104 4TB                                    | 5        | 1.68%   |
| Samsung SSD 860 EVO 500GB                                         | 5        | 1.68%   |
| Seagate ST2000DM001-1ER164 2TB                                    | 4        | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                 | 4        | 1.35%   |
| Seagate ST1000DM003-1ER162 1TB                                    | 3        | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB                                    | 3        | 1.01%   |
| Samsung SSD 980 1TB                                               | 3        | 1.01%   |
| Samsung SSD 850 EVO 250GB                                         | 3        | 1.01%   |
| Phison PS5013 E13 NVMe Controller 256GB                           | 3        | 1.01%   |
| Kingston SA400S37480G 480GB SSD                                   | 3        | 1.01%   |
| Crucial CT250MX500SSD1 250GB                                      | 3        | 1.01%   |
| WDC WD5000AAKX-60U6AA0 500GB                                      | 2        | 0.67%   |
| WDC WD10EZEX-60WN4A0 1TB                                          | 2        | 0.67%   |
| Toshiba DT01ACA100 1TB                                            | 2        | 0.67%   |
| Seagate ST2000DM001-1CH164 2TB                                    | 2        | 0.67%   |
| Sandisk WD_BLACK SN850X 4000GB                                    | 2        | 0.67%   |
| Sandisk WD_BLACK SN770 1TB                                        | 2        | 0.67%   |
| Sandisk WD Black SN850 1TB                                        | 2        | 0.67%   |
| SanDisk SSD PLUS 1000GB                                           | 2        | 0.67%   |
| SanDisk NVMe SSD Drive 1TB                                        | 2        | 0.67%   |
| Samsung SSD 980 PRO 2TB                                           | 2        | 0.67%   |
| Samsung SSD 980 PRO 1TB                                           | 2        | 0.67%   |
| Samsung SSD 970 EVO Plus 500GB                                    | 2        | 0.67%   |
| Samsung SSD 870 QVO 2TB                                           | 2        | 0.67%   |
| Samsung SSD 850 PRO 512GB                                         | 2        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                | 2        | 0.67%   |
| Samsung HD103SI 1TB                                               | 2        | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 2        | 0.67%   |
| Kingston Company SNV2S1000G 1TB                                   | 2        | 0.67%   |
| Kingston Company A2000 NVMe SSD 250GB                             | 2        | 0.67%   |
| Kingston SA400S37240G 240GB SSD                                   | 2        | 0.67%   |
| Kingston SA400S37120G 120GB SSD                                   | 2        | 0.67%   |
| Kingston SA400M8240G 240GB SSD                                    | 2        | 0.67%   |
| Hitachi HDP725050GLA360 500GB                                     | 2        | 0.67%   |
| Crucial CT1000BX500SSD1 1TB                                       | 2        | 0.67%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 2        | 0.67%   |
| Unknown                                                           | 2        | 0.67%   |
| WDC WUH721818ALE6L4 18TB                                          | 1        | 0.34%   |
| WDC WDS500G2B0A 500GB SSD                                         | 1        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 36       | 60     | 39.13%  |
| WDC                 | 26       | 35     | 28.26%  |
| Toshiba             | 11       | 12     | 11.96%  |
| Hitachi             | 6        | 6      | 6.52%   |
| HGST                | 5        | 6      | 5.43%   |
| Samsung Electronics | 4        | 4      | 4.35%   |
| Maxtor              | 2        | 2      | 2.17%   |
| Unknown             | 1        | 1      | 1.09%   |
| Apple               | 1        | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 32     | 22.58%  |
| Kingston            | 12       | 17     | 12.9%   |
| Crucial             | 10       | 12     | 10.75%  |
| SanDisk             | 9        | 12     | 9.68%   |
| WDC                 | 7        | 8      | 7.53%   |
| PNY                 | 3        | 3      | 3.23%   |
| A-DATA Technology   | 3        | 4      | 3.23%   |
| SPCC                | 2        | 6      | 2.15%   |
| Seagate             | 2        | 2      | 2.15%   |
| Patriot             | 2        | 2      | 2.15%   |
| Intel               | 2        | 2      | 2.15%   |
| Hewlett-Packard     | 2        | 2      | 2.15%   |
| China               | 2        | 2      | 2.15%   |
| Vaseky              | 1        | 1      | 1.08%   |
| Transcend           | 1        | 1      | 1.08%   |
| Toshiba             | 1        | 1      | 1.08%   |
| Team                | 1        | 1      | 1.08%   |
| Smartbuy            | 1        | 1      | 1.08%   |
| S3+                 | 1        | 1      | 1.08%   |
| PHD 3.0             | 1        | 1      | 1.08%   |
| Neo                 | 1        | 1      | 1.08%   |
| Micron Technology   | 1        | 1      | 1.08%   |
| INNOVATION IT       | 1        | 1      | 1.08%   |
| Hoodisk             | 1        | 1      | 1.08%   |
| Gigabyte Technology | 1        | 1      | 1.08%   |
| Emtec               | 1        | 2      | 1.08%   |
| CT1000MX            | 1        | 1      | 1.08%   |
| Corsair             | 1        | 1      | 1.08%   |
| AMD                 | 1        | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 77       | 121    | 38.5%   |
| HDD     | 62       | 127    | 31%     |
| NVMe    | 55       | 82     | 27.5%   |
| Unknown | 6        | 7      | 3%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 96       | 242    | 59.63%  |
| NVMe | 55       | 81     | 34.16%  |
| SAS  | 10       | 14     | 6.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 71       | 105    | 42.77%  |
| 0.51-1.0   | 48       | 72     | 28.92%  |
| 1.01-2.0   | 26       | 40     | 15.66%  |
| 3.01-4.0   | 11       | 16     | 6.63%   |
| 4.01-10.0  | 8        | 13     | 4.82%   |
| 2.01-3.0   | 1        | 1      | 0.6%    |
| 10.01-20.0 | 1        | 1      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 24       | 21.62%  |
| 101-250        | 22       | 19.82%  |
| More than 3000 | 21       | 18.92%  |
| 251-500        | 16       | 14.41%  |
| 1001-2000      | 15       | 13.51%  |
| 2001-3000      | 7        | 6.31%   |
| 21-50          | 2        | 1.8%    |
| 1-20           | 2        | 1.8%    |
| 51-100         | 2        | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 16.81%  |
| 501-1000       | 19       | 16.81%  |
| 251-500        | 17       | 15.04%  |
| 21-50          | 17       | 15.04%  |
| 1-20           | 13       | 11.5%   |
| 51-100         | 11       | 9.73%   |
| More than 3000 | 9        | 7.96%   |
| 1001-2000      | 6        | 5.31%   |
| 2001-3000      | 2        | 1.77%   |

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
| WDC WD Blue SA510 2.5 1000GB                 | 1        | 1      | 5.26%   |
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
| Detected | 67       | 199    | 51.94%  |
| Works    | 48       | 114    | 37.21%  |
| Malfunc  | 13       | 22     | 10.08%  |
| Failed   | 1        | 2      | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 57       | 30.65%  |
| AMD                          | 52       | 27.96%  |
| Samsung Electronics          | 19       | 10.22%  |
| SanDisk                      | 14       | 7.53%   |
| ASMedia Technology           | 7        | 3.76%   |
| Phison Electronics           | 6        | 3.23%   |
| Micron/Crucial Technology    | 6        | 3.23%   |
| Silicon Motion               | 5        | 2.69%   |
| Kingston Technology Company  | 5        | 2.69%   |
| JMicron Technology           | 3        | 1.61%   |
| ADATA Technology             | 3        | 1.61%   |
| Realtek Semiconductor        | 2        | 1.08%   |
| MAXIO Technology (Hangzhou)  | 2        | 1.08%   |
| Marvell Technology Group     | 2        | 1.08%   |
| Silicon Image                | 1        | 0.54%   |
| Shenzhen Longsys Electronics | 1        | 0.54%   |
| LSI Logic / Symbios Logic    | 1        | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 14.48%  |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 5.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 4.52%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 4.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 3.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 3.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.71%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 2.26%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 5        | 2.26%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 2.26%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 2.26%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.81%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 3        | 1.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.36%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 1.36%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.36%   |
| AMD X370 Series Chipset SATA Controller                                                 | 3        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.36%   |
| AMD FCH SATA Controller D                                                               | 3        | 1.36%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 0.9%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 2        | 0.9%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.9%    |
| Kingston Company NV2 NVMe SSD SM2267XT                                                  | 2        | 0.9%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2        | 0.9%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.9%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.9%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 0.45%   |
| Shenzhen Longsys Lexar NM760 NVME SSD (DRAM-less)                                       | 1        | 0.45%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                                      | 1        | 0.45%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 0.45%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                   | 1        | 0.45%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                                   | 1        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 99       | 57.89%  |
| NVMe | 55       | 32.16%  |
| RAID | 8        | 4.68%   |
| IDE  | 8        | 4.68%   |
| SAS  | 1        | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 57       | 52.29%  |
| AMD    | 52       | 47.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 6        | 5.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz       | 4        | 3.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 3        | 2.75%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 3        | 2.75%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 2.75%   |
| AMD Ryzen 5 2600 Six-Core Processor    | 3        | 2.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 2        | 1.83%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.83%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 2        | 1.83%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 2        | 1.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 2        | 1.83%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 2        | 1.83%   |
| Intel Core i5-3330 CPU @ 3.00GHz       | 2        | 1.83%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 2        | 1.83%   |
| AMD Ryzen 7 5700X 8-Core Processor     | 2        | 1.83%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 2        | 1.83%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 2        | 1.83%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 2        | 1.83%   |
| AMD FX-6300 Six-Core Processor         | 2        | 1.83%   |
| Intel Xeon W-2104 CPU @ 3.20GHz        | 1        | 0.92%   |
| Intel Xeon CPU W3580 @ 3.33GHz         | 1        | 0.92%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz    | 1        | 0.92%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz    | 1        | 0.92%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz | 1        | 0.92%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 0.92%   |
| Intel N100                             | 1        | 0.92%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 1        | 0.92%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 0.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 0.92%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 1        | 0.92%   |
| Intel Core i7-4960X CPU @ 3.60GHz      | 1        | 0.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 0.92%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1        | 0.92%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1        | 0.92%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 0.92%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 1        | 0.92%   |
| Intel Core i5-9600KF CPU @ 3.70GHz     | 1        | 0.92%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 0.92%   |
| Intel Core i5-8500 CPU @ 3.00GHz       | 1        | 0.92%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 1        | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i7      | 20       | 18.35%  |
| AMD Ryzen 5        | 20       | 18.35%  |
| Intel Core i5      | 18       | 16.51%  |
| AMD Ryzen 7        | 15       | 13.76%  |
| Other              | 8        | 7.34%   |
| AMD Ryzen 9        | 6        | 5.5%    |
| Intel Xeon         | 4        | 3.67%   |
| AMD FX             | 3        | 2.75%   |
| Intel Core i3      | 2        | 1.83%   |
| Intel Celeron      | 2        | 1.83%   |
| AMD Ryzen 5 PRO    | 2        | 1.83%   |
| Intel Pentium Gold | 1        | 0.92%   |
| Intel Pentium      | 1        | 0.92%   |
| Intel Core i9      | 1        | 0.92%   |
| AMD Ryzen Embedded | 1        | 0.92%   |
| AMD Ryzen 3 PRO    | 1        | 0.92%   |
| AMD Phenom II X6   | 1        | 0.92%   |
| AMD Phenom II X4   | 1        | 0.92%   |
| AMD Athlon II X3   | 1        | 0.92%   |
| AMD Athlon         | 1        | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 39       | 35.78%  |
| 6      | 34       | 31.19%  |
| 8      | 18       | 16.51%  |
| 2      | 7        | 6.42%   |
| 12     | 4        | 3.67%   |
| 16     | 3        | 2.75%   |
| 3      | 3        | 2.75%   |
| 10     | 1        | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 109      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 78       | 71.56%  |
| 1      | 31       | 28.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 109      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 87       | 78.38%  |
| 0x0a601203 | 6        | 5.41%   |
| 0x0a20120a | 3        | 2.7%    |
| 0x08701021 | 3        | 2.7%    |
| 0x306c3    | 1        | 0.9%    |
| 0x0a50000d | 1        | 0.9%    |
| 0x0a201025 | 1        | 0.9%    |
| 0x08701030 | 1        | 0.9%    |
| 0x08701013 | 1        | 0.9%    |
| 0x08108109 | 1        | 0.9%    |
| 0x0810100b | 1        | 0.9%    |
| 0x0800820d | 1        | 0.9%    |
| 0x08001138 | 1        | 0.9%    |
| 0x0700010f | 1        | 0.9%    |
| 0x06000852 | 1        | 0.9%    |
| 0x010000dc | 1        | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 15       | 13.64%  |
| Zen 3            | 14       | 12.73%  |
| Haswell          | 12       | 10.91%  |
| Unknown          | 11       | 10%     |
| Zen+             | 10       | 9.09%   |
| Zen 2            | 10       | 9.09%   |
| SandyBridge      | 8        | 7.27%   |
| IvyBridge        | 5        | 4.55%   |
| Zen              | 4        | 3.64%   |
| Skylake          | 3        | 2.73%   |
| Piledriver       | 3        | 2.73%   |
| K10              | 3        | 2.73%   |
| Icelake          | 3        | 2.73%   |
| Nehalem          | 2        | 1.82%   |
| Alderlake Hybrid | 2        | 1.82%   |
| Westmere         | 1        | 0.91%   |
| Tremont          | 1        | 0.91%   |
| Jaguar           | 1        | 0.91%   |
| CometLake        | 1        | 0.91%   |
| Broadwell        | 1        | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 48       | 40.34%  |
| Nvidia | 44       | 36.97%  |
| Intel  | 27       | 22.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11       | 9.02%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 5.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 4.92%   |
| AMD Raphael                                                                 | 6        | 4.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 4.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 3.28%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.46%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.46%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 2.46%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 2.46%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 1.64%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.64%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.64%   |
| Intel DG2 [Arc A380]                                                        | 2        | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.64%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.64%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 2        | 1.64%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.82%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.82%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.82%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1        | 0.82%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.82%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.82%   |
| Nvidia GT218 [GeForce G210]                                                 | 1        | 0.82%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.82%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.82%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.82%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 0.82%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.82%   |
| Nvidia GF108 [GeForce GT 530]                                               | 1        | 0.82%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 40       | 36.7%   |
| 1 x AMD         | 40       | 36.7%   |
| 1 x Intel       | 19       | 17.43%  |
| 2 x AMD         | 3        | 2.75%   |
| Intel + AMD     | 3        | 2.75%   |
| Intel + Nvidia  | 2        | 1.83%   |
| Intel + 2 x AMD | 1        | 0.92%   |
| AMD + Nvidia    | 1        | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 66.36%  |
| Proprietary | 37       | 33.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 43.24%  |
| 7.01-8.0   | 17       | 15.32%  |
| 1.01-2.0   | 12       | 10.81%  |
| 3.01-4.0   | 10       | 9.01%   |
| 8.01-16.0  | 8        | 7.21%   |
| 5.01-6.0   | 6        | 5.41%   |
| 0.01-0.5   | 4        | 3.6%    |
| 16.01-24.0 | 3        | 2.7%    |
| 2.01-3.0   | 2        | 1.8%    |
| 4.01-5.0   | 1        | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 17       | 13.49%  |
| Dell                 | 14       | 11.11%  |
| Hewlett-Packard      | 11       | 8.73%   |
| Iiyama               | 10       | 7.94%   |
| Acer                 | 9        | 7.14%   |
| Goldstar             | 8        | 6.35%   |
| Ancor Communications | 8        | 6.35%   |
| Philips              | 7        | 5.56%   |
| ASUSTek Computer     | 6        | 4.76%   |
| AOC                  | 5        | 3.97%   |
| Eizo                 | 4        | 3.17%   |
| BenQ                 | 4        | 3.17%   |
| Lenovo               | 3        | 2.38%   |
| Gigabyte Technology  | 3        | 2.38%   |
| Wacom                | 1        | 0.79%   |
| Vizio                | 1        | 0.79%   |
| VIZ                  | 1        | 0.79%   |
| ViewSonic            | 1        | 0.79%   |
| RTK                  | 1        | 0.79%   |
| ONN                  | 1        | 0.79%   |
| NEC Computers        | 1        | 0.79%   |
| MSI                  | 1        | 0.79%   |
| Mi                   | 1        | 0.79%   |
| Medion Akoya         | 1        | 0.79%   |
| INS                  | 1        | 0.79%   |
| HYU                  | 1        | 0.79%   |
| HKC                  | 1        | 0.79%   |
| Haier                | 1        | 0.79%   |
| GDH                  | 1        | 0.79%   |
| DENON                | 1        | 0.79%   |
| CVT                  | 1        | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2        | 1.39%   |
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                   | 2        | 1.39%   |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                    | 2        | 1.39%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                       | 2        | 1.39%   |
| Ancor Communications MX259 ACI25C2 1920x1080 553x309mm 24.9-inch        | 2        | 1.39%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1        | 0.69%   |
| Vizio D32h-G9 VIZ1028 1366x768 521x293mm 23.5-inch                      | 1        | 0.69%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                      | 1        | 0.69%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                  | 1        | 0.69%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch       | 1        | 0.69%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch       | 1        | 0.69%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch       | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch    | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch    | 1        | 0.69%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch      | 1        | 0.69%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch      | 1        | 0.69%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1        | 0.69%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch       | 1        | 0.69%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.69%   |
| Samsung Electronics S22E450 SAM0C7C 1680x1050 473x291mm 21.9-inch       | 1        | 0.69%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1        | 0.69%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch       | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0992 1920x1080 890x500mm 40.2-inch   | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080                       | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0679 1360x768 410x256mm 19.0-inch    | 1        | 0.69%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 1        | 0.69%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 797x333mm 34.0-inch         | 1        | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.69%   |
| RTK TYPE C RTKBC32 2560x1600 347x215mm 16.1-inch                        | 1        | 0.69%   |
| Philips PHL 242E1GZ PHLC24C 1920x1080 527x296mm 23.8-inch               | 1        | 0.69%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch                | 1        | 0.69%   |
| Philips PHL 240V5A PHLC10C 1920x1080 527x296mm 23.8-inch                | 1        | 0.69%   |
| Philips PHL 230B8Q PHL0936 1920x1200 488x297mm 22.5-inch                | 1        | 0.69%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1        | 0.69%   |
| Philips 27M1N3200V PHLC279 1920x1080 598x336mm 27.0-inch                | 1        | 0.69%   |
| Philips 191V PHL0887 1366x768 409x230mm 18.5-inch                       | 1        | 0.69%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                     | 1        | 0.69%   |
| NEC Computers E233WM NEC2BE4 1920x1080 509x286mm 23.0-inch              | 1        | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 47.58%  |
| 3840x2160 (4K)     | 21       | 16.94%  |
| 2560x1440 (QHD)    | 11       | 8.87%   |
| 1920x1200 (WUXGA)  | 5        | 4.03%   |
| 1440x900 (WXGA+)   | 5        | 4.03%   |
| 3440x1440          | 4        | 3.23%   |
| 1600x900 (HD+)     | 4        | 3.23%   |
| 1366x768 (WXGA)    | 4        | 3.23%   |
| 2560x1080          | 3        | 2.42%   |
| 1680x1050 (WSXGA+) | 3        | 2.42%   |
| 3840x1080          | 1        | 0.81%   |
| 2560x1600          | 1        | 0.81%   |
| 1360x768           | 1        | 0.81%   |
| 1280x1024 (SXGA)   | 1        | 0.81%   |
| Unknown            | 1        | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 29       | 22.31%  |
| 27      | 25       | 19.23%  |
| 23      | 13       | 10%     |
| 31      | 12       | 9.23%   |
| 21      | 11       | 8.46%   |
| 19      | 9        | 6.92%   |
| 34      | 7        | 5.38%   |
| 22      | 3        | 2.31%   |
| 18      | 3        | 2.31%   |
| 46      | 2        | 1.54%   |
| 40      | 2        | 1.54%   |
| 28      | 2        | 1.54%   |
| Unknown | 2        | 1.54%   |
| 84      | 1        | 0.77%   |
| 72      | 1        | 0.77%   |
| 69      | 1        | 0.77%   |
| 52      | 1        | 0.77%   |
| 43      | 1        | 0.77%   |
| 33      | 1        | 0.77%   |
| 26      | 1        | 0.77%   |
| 25      | 1        | 0.77%   |
| 20      | 1        | 0.77%   |
| 17      | 1        | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 62       | 50%     |
| 401-500     | 25       | 20.16%  |
| 601-700     | 17       | 13.71%  |
| 701-800     | 8        | 6.45%   |
| 1501-2000   | 3        | 2.42%   |
| 1001-1500   | 3        | 2.42%   |
| 801-900     | 2        | 1.61%   |
| Unknown     | 2        | 1.61%   |
| 301-350     | 1        | 0.81%   |
| 901-1000    | 1        | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 86       | 76.79%  |
| 16/10   | 16       | 14.29%  |
| 21/9    | 7        | 6.25%   |
| Unknown | 2        | 1.79%   |
| 5/4     | 1        | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 40       | 31.25%  |
| 301-350        | 25       | 19.53%  |
| 351-500        | 22       | 17.19%  |
| 251-300        | 14       | 10.94%  |
| 151-200        | 12       | 9.38%   |
| 501-1000       | 5        | 3.91%   |
| More than 1000 | 4        | 3.13%   |
| 141-150        | 4        | 3.13%   |
| Unknown        | 2        | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 72       | 62.61%  |
| 101-120 | 23       | 20%     |
| 121-160 | 11       | 9.57%   |
| 1-50    | 4        | 3.48%   |
| 161-240 | 3        | 2.61%   |
| Unknown | 2        | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 68.81%  |
| 2     | 27       | 24.77%  |
| 3     | 6        | 5.5%    |
| 4     | 1        | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 79       | 48.77%  |
| Intel                             | 38       | 23.46%  |
| MediaTek                          | 9        | 5.56%   |
| TP-Link                           | 6        | 3.7%    |
| Qualcomm Atheros                  | 6        | 3.7%    |
| Broadcom                          | 5        | 3.09%   |
| ASUSTek Computer                  | 4        | 2.47%   |
| Ralink                            | 3        | 1.85%   |
| Arduino SA                        | 2        | 1.23%   |
| Van Ooijen Technische Informatica | 1        | 0.62%   |
| Texas Instruments                 | 1        | 0.62%   |
| Tehuti Networks                   | 1        | 0.62%   |
| QinHeng Electronics               | 1        | 0.62%   |
| NetGear                           | 1        | 0.62%   |
| Microsoft                         | 1        | 0.62%   |
| Linksys                           | 1        | 0.62%   |
| Huawei Technologies               | 1        | 0.62%   |
| Google                            | 1        | 0.62%   |
| Aquantia                          | 1        | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 51       | 28.81%  |
| Realtek RTL8125 2.5GbE Controller                                             | 19       | 10.73%  |
| Intel I211 Gigabit Network Connection                                         | 9        | 5.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 5        | 2.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 4        | 2.26%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.26%   |
| Intel Ethernet Connection (7) I219-V                                          | 4        | 2.26%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 1.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 1.13%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 1.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.13%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 1.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 1.13%   |
| Intel Wireless 7265                                                           | 2        | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 1.13%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.13%   |
| ASUS 802.11ac NIC                                                             | 2        | 1.13%   |
| Van Ooijen Technische Informatica Teensyduino Serial                          | 1        | 0.56%   |
| TP-Link 802.11n NIC                                                           | 1        | 0.56%   |
| Texas Instruments TI CC2540 USB CDC                                           | 1        | 0.56%   |
| Tehuti Networks TN9210 10GBase-T Ethernet Adapter                             | 1        | 0.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 0.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1        | 0.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.56%   |
| Realtek 802.11ac NIC                                                          | 1        | 0.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 0.56%   |
| QinHeng USB Single Serial                                                     | 1        | 0.56%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                               | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 21.15%  |
| Intel                 | 10       | 19.23%  |
| MediaTek              | 8        | 15.38%  |
| TP-Link               | 6        | 11.54%  |
| Qualcomm Atheros      | 5        | 9.62%   |
| ASUSTek Computer      | 4        | 7.69%   |
| Ralink                | 3        | 5.77%   |
| Broadcom              | 2        | 3.85%   |
| NetGear               | 1        | 1.92%   |
| Microsoft             | 1        | 1.92%   |
| Linksys               | 1        | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 5        | 9.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 3.77%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 2        | 3.77%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 2        | 3.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 3.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2        | 3.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 3.77%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 2        | 3.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2        | 3.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 3.77%   |
| Intel Wireless 7265                                                           | 2        | 3.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2        | 3.77%   |
| ASUS 802.11ac NIC                                                             | 2        | 3.77%   |
| TP-Link 802.11n NIC                                                           | 1        | 1.89%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1        | 1.89%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.89%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1        | 1.89%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 1.89%   |
| Realtek 802.11ac NIC                                                          | 1        | 1.89%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 1.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 1.89%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.89%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                               | 1        | 1.89%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 1        | 1.89%   |
| MediaTek WiFi                                                                 | 1        | 1.89%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                     | 1        | 1.89%   |
| Intel Wireless-AC 9260                                                        | 1        | 1.89%   |
| Intel Wireless 8260                                                           | 1        | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 1        | 1.89%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 1.89%   |
| Intel CNVi: Wi-Fi                                                             | 1        | 1.89%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.89%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 1.89%   |
| ASUS USB-N13 802.11n Network Adapter (rev. A1) [Ralink RT3072]                | 1        | 1.89%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 1        | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 76       | 64.41%  |
| Intel                 | 32       | 27.12%  |
| Broadcom              | 3        | 2.54%   |
| Qualcomm Atheros      | 2        | 1.69%   |
| Tehuti Networks       | 1        | 0.85%   |
| MediaTek              | 1        | 0.85%   |
| Huawei Technologies   | 1        | 0.85%   |
| Google                | 1        | 0.85%   |
| Aquantia              | 1        | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51       | 42.86%  |
| Realtek RTL8125 2.5GbE Controller                                 | 19       | 15.97%  |
| Intel I211 Gigabit Network Connection                             | 9        | 7.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 3.36%   |
| Intel Ethernet Controller I225-V                                  | 4        | 3.36%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 3.36%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 3.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 2.52%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.68%   |
| Tehuti Networks TN9210 10GBase-T Ethernet Adapter                 | 1        | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.84%   |
| MediaTek Wiko U316AT                                              | 1        | 0.84%   |
| Intel Ethernet Controller I219-V                                  | 1        | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.84%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.84%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.84%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.84%   |
| Huawei ALP-AL00                                                   | 1        | 0.84%   |
| Google Pixel 8 Pro                                                | 1        | 0.84%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 0.84%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 0.84%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 0.84%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 109      | 67.28%  |
| WiFi     | 49       | 30.25%  |
| Modem    | 4        | 2.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 75.63%  |
| WiFi     | 29       | 24.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 75       | 68.18%  |
| 2     | 31       | 28.18%  |
| 3     | 2        | 1.82%   |
| 5     | 1        | 0.91%   |
| 0     | 1        | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 75       | 68.18%  |
| Yes  | 35       | 31.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 14       | 28.57%  |
| Intel                           | 11       | 22.45%  |
| Realtek Semiconductor           | 6        | 12.24%  |
| MediaTek                        | 5        | 10.2%   |
| ASUSTek Computer                | 3        | 6.12%   |
| TP-Link                         | 2        | 4.08%   |
| Qualcomm Atheros Communications | 2        | 4.08%   |
| Realtek                         | 1        | 2.04%   |
| Logitech                        | 1        | 2.04%   |
| Lite-On Technology              | 1        | 2.04%   |
| IMC Networks                    | 1        | 2.04%   |
| Foxconn / Hon Hai               | 1        | 2.04%   |
| Broadcom                        | 1        | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 28.57%  |
| Realtek Bluetooth Radio                             | 6        | 12.24%  |
| MediaTek Wireless_Device                            | 5        | 10.2%   |
| Intel Bluetooth wireless interface                  | 3        | 6.12%   |
| TP-Link UB500 Adapter                               | 2        | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4.08%   |
| Intel AX210 Bluetooth                               | 2        | 4.08%   |
| Intel AX201 Bluetooth                               | 2        | 4.08%   |
| Realtek Bluetooth Radio                             | 1        | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 2.04%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 2.04%   |
| Lite-On Bluetooth Device                            | 1        | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.04%   |
| Intel AX200 Bluetooth                               | 1        | 2.04%   |
| IMC Networks BCM20702A0                             | 1        | 2.04%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 2.04%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 2.04%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 2.04%   |
| ASUS Bluetooth Radio                                | 1        | 2.04%   |
| ASUS ASUS USB-BT500                                 | 1        | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 66       | 30.84%  |
| Intel                     | 59       | 27.57%  |
| Nvidia                    | 43       | 20.09%  |
| C-Media Electronics       | 8        | 3.74%   |
| Logitech                  | 5        | 2.34%   |
| Focusrite-Novation        | 4        | 1.87%   |
| Texas Instruments         | 3        | 1.4%    |
| VIA Technologies          | 2        | 0.93%   |
| SteelSeries ApS           | 2        | 0.93%   |
| SAVITECH                  | 2        | 0.93%   |
| Micro Star International  | 2        | 0.93%   |
| Generalplus Technology    | 2        | 0.93%   |
| Creative Labs             | 2        | 0.93%   |
| Trust                     | 1        | 0.47%   |
| TEAC                      | 1        | 0.47%   |
| Sennheiser Communications | 1        | 0.47%   |
| Realtek Semiconductor     | 1        | 0.47%   |
| Mackie Designs            | 1        | 0.47%   |
| JMTek                     | 1        | 0.47%   |
| GN Netcom                 | 1        | 0.47%   |
| Dell                      | 1        | 0.47%   |
| Creative Technology       | 1        | 0.47%   |
| Corsair                   | 1        | 0.47%   |
| AudioQuest                | 1        | 0.47%   |
| ASUSTek Computer          | 1        | 0.47%   |
| Asahi Kasei Microsystems  | 1        | 0.47%   |
| 2.4G Composite Device     | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 20       | 7.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16       | 6.27%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11       | 4.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 4.31%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 3.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 2.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 2.35%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6        | 2.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.96%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.57%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 1.57%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 1.57%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 1.57%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.18%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 1.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 1.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 1.18%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller         | 2        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.78%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 2        | 0.78%   |
| Nvidia GA102 High Definition Audio Controller                              | 2        | 0.78%   |
| Micro Star International USB Audio                                         | 2        | 0.78%   |
| Intel DG2 Audio Controller                                                 | 2        | 0.78%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.78%   |
| Generalplus Technology USB Audio Device                                    | 2        | 0.78%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 2        | 0.78%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 14       | 21.88%  |
| G.Skill             | 9        | 14.06%  |
| Corsair             | 9        | 14.06%  |
| Samsung Electronics | 8        | 12.5%   |
| Crucial             | 6        | 9.38%   |
| SK hynix            | 3        | 4.69%   |
| A-DATA Technology   | 3        | 4.69%   |
| Unknown             | 2        | 3.13%   |
| Team                | 2        | 3.13%   |
| Patriot             | 2        | 3.13%   |
| Micron Technology   | 2        | 3.13%   |
| Ramaxel Technology  | 1        | 1.56%   |
| Nanya Technology    | 1        | 1.56%   |
| Atermiter           | 1        | 1.56%   |
| Unknown             | 1        | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 2        | 2.99%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s          | 2        | 2.99%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 2        | 2.99%   |
| Unknown RAM Module 8GB DIMM 667MT/s                            | 1        | 1.49%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                     | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 1        | 1.49%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s             | 1        | 1.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s           | 1        | 1.49%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s        | 1        | 1.49%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s           | 1        | 1.49%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1        | 1.49%   |
| Samsung RAM M391B5773CH0-YH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.49%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 1        | 1.49%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s            | 1        | 1.49%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 1        | 1.49%   |
| Samsung RAM M378A2G43AB3-CWE 16GB DIMM DDR4 3200MT/s           | 1        | 1.49%   |
| Samsung RAM 53D512M64D4RQ-046 4GB Row Of Chips LPDDR4 4267MT/s | 1        | 1.49%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2400MT/s         | 1        | 1.49%   |
| Patriot RAM PSD44G240041 4GB DIMM DDR4 2400MT/s                | 1        | 1.49%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 1        | 1.49%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.49%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 1        | 1.49%   |
| Micron RAM 16KTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 1.49%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s           | 1        | 1.49%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s            | 1        | 1.49%   |
| Kingston RAM KF560C36-32 32GB DIMM DDR5 4800MT/s               | 1        | 1.49%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s               | 1        | 1.49%   |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 6400MT/s               | 1        | 1.49%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s          | 1        | 1.49%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 1        | 1.49%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 1        | 1.49%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s             | 1        | 1.49%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s          | 1        | 1.49%   |
| Kingston RAM 9965646-035.B00G 8GB SODIMM DDR4 2933MT/s         | 1        | 1.49%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.49%   |
| Kingston RAM 9905403-038.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.49%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s           | 1        | 1.49%   |
| G.Skill RAM F5-6000J3038F16G 16GB DIMM DDR5 6000MT/s           | 1        | 1.49%   |
| G.Skill RAM F4-3600C18-16GVK 16GB DIMM DDR4 3733MT/s           | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 34       | 60.71%  |
| DDR3    | 14       | 25%     |
| DDR5    | 6        | 10.71%  |
| LPDDR4  | 1        | 1.79%   |
| Unknown | 1        | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 52       | 92.86%  |
| SODIMM       | 3        | 5.36%   |
| Row Of Chips | 1        | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 37.7%   |
| 16384 | 19       | 31.15%  |
| 4096  | 13       | 21.31%  |
| 32768 | 4        | 6.56%   |
| 2048  | 2        | 3.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 11       | 17.19%  |
| 3600  | 7        | 10.94%  |
| 2400  | 7        | 10.94%  |
| 1333  | 5        | 7.81%   |
| 1800  | 4        | 6.25%   |
| 2667  | 3        | 4.69%   |
| 1600  | 3        | 4.69%   |
| 6400  | 2        | 3.13%   |
| 6000  | 2        | 3.13%   |
| 4800  | 2        | 3.13%   |
| 3733  | 2        | 3.13%   |
| 3266  | 2        | 3.13%   |
| 2933  | 2        | 3.13%   |
| 2666  | 2        | 3.13%   |
| 2133  | 2        | 3.13%   |
| 4267  | 1        | 1.56%   |
| 3666  | 1        | 1.56%   |
| 3400  | 1        | 1.56%   |
| 3334  | 1        | 1.56%   |
| 3066  | 1        | 1.56%   |
| 2473  | 1        | 1.56%   |
| 1866  | 1        | 1.56%   |
| 667   | 1        | 1.56%   |

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
| Microdia                      | 6        | 23.08%  |
| Logitech                      | 5        | 19.23%  |
| Samsung Electronics           | 2        | 7.69%   |
| Trust                         | 1        | 3.85%   |
| Sunplus Innovation Technology | 1        | 3.85%   |
| SN0002                        | 1        | 3.85%   |
| Realtek Semiconductor         | 1        | 3.85%   |
| OPPO Electronics              | 1        | 3.85%   |
| Microsoft                     | 1        | 3.85%   |
| MacroSilicon                  | 1        | 3.85%   |
| Jieli Technology              | 1        | 3.85%   |
| Generalplus Technology        | 1        | 3.85%   |
| GEMBIRD                       | 1        | 3.85%   |
| Chicony Electronics           | 1        | 3.85%   |
| AVerMedia Technologies        | 1        | 3.85%   |
| A4Tech                        | 1        | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 2        | 7.69%   |
| Microdia Webcam Vitade AF                         | 2        | 7.69%   |
| Microdia Camera                                   | 2        | 7.69%   |
| Trust Full HD Webcam                              | 1        | 3.85%   |
| Sunplus MTD Camera                                | 1        | 3.85%   |
| SN0002 1080P Web Camera                           | 1        | 3.85%   |
| Realtek Full HD webcam                            | 1        | 3.85%   |
| OPPO Oppo N1                                      | 1        | 3.85%   |
| Microsoft LifeCam Cinema                          | 1        | 3.85%   |
| Microdia USB 2.0 Camera                           | 1        | 3.85%   |
| Microdia PC-LM1E                                  | 1        | 3.85%   |
| MacroSilicon USB Video                            | 1        | 3.85%   |
| Logitech Webcam C270                              | 1        | 3.85%   |
| Logitech HD Webcam C615                           | 1        | 3.85%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 3.85%   |
| Logitech C920 PRO HD Webcam                       | 1        | 3.85%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 3.85%   |
| Jieli USB PHY 2.0                                 | 1        | 3.85%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 1        | 3.85%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 3.85%   |
| Chicony HP High Definition 1MP Webcam             | 1        | 3.85%   |
| AVerMedia PW310O Webcam                           | 1        | 3.85%   |
| A4Tech FHD 1080P PC Camera                        | 1        | 3.85%   |

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
| 0     | 96       | 86.49%  |
| 1     | 13       | 11.71%  |
| 3     | 1        | 0.9%    |
| 2     | 1        | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 33.33%  |
| Unassigned class         | 2        | 13.33%  |
| Graphics card            | 2        | 13.33%  |
| Communication controller | 2        | 13.33%  |
| Storage/raid             | 1        | 6.67%   |
| Sound                    | 1        | 6.67%   |
| Net/ethernet             | 1        | 6.67%   |
| Camera                   | 1        | 6.67%   |

