Fedora - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 7394

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4A785TD-V EVO              | [d57d789e77](https://linux-hardware.org/?probe=d57d789e77) | Nov 06, 2023 |
| MSI           | X99A RAIDER                 | [3a2a72df26](https://linux-hardware.org/?probe=3a2a72df26) | Nov 06, 2023 |
| ASRock        | X670E Taichi                | [6f05d717db](https://linux-hardware.org/?probe=6f05d717db) | Nov 05, 2023 |
| ASRock        | X670E Taichi                | [a366b27921](https://linux-hardware.org/?probe=a366b27921) | Nov 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [05a8c22a35](https://linux-hardware.org/?probe=05a8c22a35) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e1d50d8743](https://linux-hardware.org/?probe=e1d50d8743) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| HP            | 1494                        | [93e0e0302f](https://linux-hardware.org/?probe=93e0e0302f) | Nov 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [4998a82a6b](https://linux-hardware.org/?probe=4998a82a6b) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-A II            | [539d8551fc](https://linux-hardware.org/?probe=539d8551fc) | Nov 05, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [a9ad2b542a](https://linux-hardware.org/?probe=a9ad2b542a) | Nov 05, 2023 |
| Pegatron      | 2AD5                        | [f8860a91a3](https://linux-hardware.org/?probe=f8860a91a3) | Nov 05, 2023 |
| Gigabyte      | B550M S2H                   | [7fb9150b16](https://linux-hardware.org/?probe=7fb9150b16) | Nov 04, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | [8edaffcccb](https://linux-hardware.org/?probe=8edaffcccb) | Nov 04, 2023 |
| Unknown       | Unknown                     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | [2ab63a2fb6](https://linux-hardware.org/?probe=2ab63a2fb6) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [a3eb4c9d76](https://linux-hardware.org/?probe=a3eb4c9d76) | Nov 04, 2023 |
| ASUSTek       | H81M-C                      | [cfb51ce306](https://linux-hardware.org/?probe=cfb51ce306) | Nov 03, 2023 |
| HP            | 859C                        | [7928158950](https://linux-hardware.org/?probe=7928158950) | Nov 03, 2023 |
| Gigabyte      | G41MT-D3                    | [3a4be91563](https://linux-hardware.org/?probe=3a4be91563) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | [3618f2a4b5](https://linux-hardware.org/?probe=3618f2a4b5) | Nov 03, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b58b97e74a](https://linux-hardware.org/?probe=b58b97e74a) | Nov 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bbe345cd5d](https://linux-hardware.org/?probe=bbe345cd5d) | Nov 02, 2023 |
| ASRock        | B760M PG SONIC WiFi         | [71e1e69f30](https://linux-hardware.org/?probe=71e1e69f30) | Nov 02, 2023 |
| MSI           | IONA                        | [579757d1cf](https://linux-hardware.org/?probe=579757d1cf) | Nov 02, 2023 |
| MSI           | B450M MORTAR MAX            | [960c1dbbd2](https://linux-hardware.org/?probe=960c1dbbd2) | Nov 01, 2023 |
| ASUSTek       | M52AD_M12AD                 | [a75715ee4a](https://linux-hardware.org/?probe=a75715ee4a) | Nov 01, 2023 |
| ASRock        | H97M Anniversary            | [6c66e3862d](https://linux-hardware.org/?probe=6c66e3862d) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [bb9a00e5b5](https://linux-hardware.org/?probe=bb9a00e5b5) | Nov 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [168597b33e](https://linux-hardware.org/?probe=168597b33e) | Nov 01, 2023 |
| HP            | 8767 A                      | [618323a058](https://linux-hardware.org/?probe=618323a058) | Nov 01, 2023 |
| ABIT          | F-I90HD                     | [2d6d01983c](https://linux-hardware.org/?probe=2d6d01983c) | Nov 01, 2023 |
| Gigabyte      | P67A-D3-B3                  | [0c51ffc039](https://linux-hardware.org/?probe=0c51ffc039) | Nov 01, 2023 |
| MSI           | B450M PRO-M2 V2             | [7296b22122](https://linux-hardware.org/?probe=7296b22122) | Oct 31, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3b79851103](https://linux-hardware.org/?probe=3b79851103) | Oct 31, 2023 |
| Gigabyte      | F2A55M-DS2                  | [069872b404](https://linux-hardware.org/?probe=069872b404) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3179102373](https://linux-hardware.org/?probe=3179102373) | Oct 31, 2023 |
| MSI           | X570-A PRO                  | [a198e0f9c2](https://linux-hardware.org/?probe=a198e0f9c2) | Oct 30, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [53e53337bb](https://linux-hardware.org/?probe=53e53337bb) | Oct 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e4d622b76b](https://linux-hardware.org/?probe=e4d622b76b) | Oct 30, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [624a99186e](https://linux-hardware.org/?probe=624a99186e) | Oct 30, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| Gigabyte      | B85M-D3V-A                  | [c35ab1031d](https://linux-hardware.org/?probe=c35ab1031d) | Oct 30, 2023 |
| ASRock        | 890GM Pro3                  | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [e41780f56a](https://linux-hardware.org/?probe=e41780f56a) | Oct 29, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [7d0eb8f922](https://linux-hardware.org/?probe=7d0eb8f922) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | [ff941d75c9](https://linux-hardware.org/?probe=ff941d75c9) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | [307134fa91](https://linux-hardware.org/?probe=307134fa91) | Oct 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [deef4da5dc](https://linux-hardware.org/?probe=deef4da5dc) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| ASRock        | X399 Taichi                 | [78ab56301b](https://linux-hardware.org/?probe=78ab56301b) | Oct 29, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [dee4ef8a3b](https://linux-hardware.org/?probe=dee4ef8a3b) | Oct 29, 2023 |
| ASRock        | Z370 Professional Gaming... | [f589e0c914](https://linux-hardware.org/?probe=f589e0c914) | Oct 28, 2023 |
| HP            | 8053                        | [352cc1bad8](https://linux-hardware.org/?probe=352cc1bad8) | Oct 28, 2023 |
| HP            | 8053                        | [25f2c6e830](https://linux-hardware.org/?probe=25f2c6e830) | Oct 28, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | [4562f80268](https://linux-hardware.org/?probe=4562f80268) | Oct 28, 2023 |
| Gigabyte      | Z77-D3H                     | [77541125c0](https://linux-hardware.org/?probe=77541125c0) | Oct 28, 2023 |
| Gigabyte      | D525TUD                     | [944bb2ecb2](https://linux-hardware.org/?probe=944bb2ecb2) | Oct 28, 2023 |
| Gigabyte      | B550 VISION D-P             | [d78b4f6222](https://linux-hardware.org/?probe=d78b4f6222) | Oct 28, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [b18bbae606](https://linux-hardware.org/?probe=b18bbae606) | Oct 27, 2023 |
| HP            | 843F                        | [c39418a5fe](https://linux-hardware.org/?probe=c39418a5fe) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [4eacfc5dd8](https://linux-hardware.org/?probe=4eacfc5dd8) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1cb73bada5](https://linux-hardware.org/?probe=1cb73bada5) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS       | [a576bfd0b1](https://linux-hardware.org/?probe=a576bfd0b1) | Oct 26, 2023 |
| Gigabyte      | B450M DS3H V2               | [3279dc82a1](https://linux-hardware.org/?probe=3279dc82a1) | Oct 26, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [fff464540a](https://linux-hardware.org/?probe=fff464540a) | Oct 26, 2023 |
| Dell          | 0KJCC5 A00                  | [f4f5605117](https://linux-hardware.org/?probe=f4f5605117) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ca40b148a0](https://linux-hardware.org/?probe=ca40b148a0) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| HP            | 8433 11                     | [902343e220](https://linux-hardware.org/?probe=902343e220) | Oct 25, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [9207de9b44](https://linux-hardware.org/?probe=9207de9b44) | Oct 25, 2023 |
| Dell          | 0C27VV A02                  | [7a88945a88](https://linux-hardware.org/?probe=7a88945a88) | Oct 25, 2023 |
| Supermicro    | X8SAX                       | [5d90e1af8c](https://linux-hardware.org/?probe=5d90e1af8c) | Oct 25, 2023 |
| ASRock        | FM2A88X+ Killer             | [c9b5ffd5b8](https://linux-hardware.org/?probe=c9b5ffd5b8) | Oct 24, 2023 |
| ASRock        | B450 Pro4                   | [d4a28890a5](https://linux-hardware.org/?probe=d4a28890a5) | Oct 24, 2023 |
| MSI           | B550-A PRO                  | [ed696b1c52](https://linux-hardware.org/?probe=ed696b1c52) | Oct 24, 2023 |
| Gigabyte      | A320M-H-CF                  | [3d211c5277](https://linux-hardware.org/?probe=3d211c5277) | Oct 24, 2023 |
| ASUSTek       | P5Q3                        | [660547e520](https://linux-hardware.org/?probe=660547e520) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [4e13c711c7](https://linux-hardware.org/?probe=4e13c711c7) | Oct 24, 2023 |
| Acer          | Aspire X1900                | [6454f71562](https://linux-hardware.org/?probe=6454f71562) | Oct 23, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [4440cac740](https://linux-hardware.org/?probe=4440cac740) | Oct 23, 2023 |
| MSI           | X370 SLI PLUS               | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [7c86d9f1e5](https://linux-hardware.org/?probe=7c86d9f1e5) | Oct 23, 2023 |
| ASRock        | D1800M                      | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | [eb9bba4f5c](https://linux-hardware.org/?probe=eb9bba4f5c) | Oct 23, 2023 |
| Gigabyte      | Z77MX-D3H                   | [1f16388df7](https://linux-hardware.org/?probe=1f16388df7) | Oct 23, 2023 |
| MSI           | IONA                        | [e444708510](https://linux-hardware.org/?probe=e444708510) | Oct 22, 2023 |
| AZW           | SER V1                      | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| Gigabyte      | G41MT-S2PT                  | [0b67401f8c](https://linux-hardware.org/?probe=0b67401f8c) | Oct 22, 2023 |
| Gigabyte      | G41MT-S2PT                  | [5a2f8368e1](https://linux-hardware.org/?probe=5a2f8368e1) | Oct 22, 2023 |
| MSI           | X99A RAIDER                 | [3ba4cde45a](https://linux-hardware.org/?probe=3ba4cde45a) | Oct 22, 2023 |
| HP            | 83E9                        | [c324d1ee0a](https://linux-hardware.org/?probe=c324d1ee0a) | Oct 22, 2023 |
| HP            | 83E9                        | [8102d00cdc](https://linux-hardware.org/?probe=8102d00cdc) | Oct 22, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [7c383004b6](https://linux-hardware.org/?probe=7c383004b6) | Oct 21, 2023 |
| Gigabyte      | F2A55M-DS2                  | [422e70640a](https://linux-hardware.org/?probe=422e70640a) | Oct 21, 2023 |
| Shenzhen M... | F6BFC                       | [64148c88c0](https://linux-hardware.org/?probe=64148c88c0) | Oct 21, 2023 |
| MSI           | B450M MORTAR MAX            | [c1ad18b5c9](https://linux-hardware.org/?probe=c1ad18b5c9) | Oct 21, 2023 |
| Gigabyte      | B85-HD3                     | [36f840931d](https://linux-hardware.org/?probe=36f840931d) | Oct 21, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [1190f127a2](https://linux-hardware.org/?probe=1190f127a2) | Oct 21, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| MSI           | X99A RAIDER                 | [edefe667a4](https://linux-hardware.org/?probe=edefe667a4) | Oct 21, 2023 |
| Packard Be... | IMEDIA S3840                | [3cc1398528](https://linux-hardware.org/?probe=3cc1398528) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [8290e4c160](https://linux-hardware.org/?probe=8290e4c160) | Oct 20, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [2d07542448](https://linux-hardware.org/?probe=2d07542448) | Oct 20, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [984eba244a](https://linux-hardware.org/?probe=984eba244a) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [6bb9b08c6e](https://linux-hardware.org/?probe=6bb9b08c6e) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | [17b8a78644](https://linux-hardware.org/?probe=17b8a78644) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3b1da376dc](https://linux-hardware.org/?probe=3b1da376dc) | Oct 19, 2023 |
| Gigabyte      | B75M-D3V                    | [b02f1b04e3](https://linux-hardware.org/?probe=b02f1b04e3) | Oct 19, 2023 |
| MACHINIST     | X99 G7 V1.0                 | [caca14cc52](https://linux-hardware.org/?probe=caca14cc52) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | [77cf0c3af6](https://linux-hardware.org/?probe=77cf0c3af6) | Oct 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [064dc574bb](https://linux-hardware.org/?probe=064dc574bb) | Oct 18, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [305b104f83](https://linux-hardware.org/?probe=305b104f83) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [0566ab2287](https://linux-hardware.org/?probe=0566ab2287) | Oct 18, 2023 |
| HP            | 2B52                        | [b14a00a196](https://linux-hardware.org/?probe=b14a00a196) | Oct 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [d7ddb794ec](https://linux-hardware.org/?probe=d7ddb794ec) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [bb941b90f8](https://linux-hardware.org/?probe=bb941b90f8) | Oct 18, 2023 |
| Gigabyte      | H77N-WIFI                   | [0c16d31374](https://linux-hardware.org/?probe=0c16d31374) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d531813a7a](https://linux-hardware.org/?probe=d531813a7a) | Oct 18, 2023 |
| Gigabyte      | G41MT-S2PT                  | [e437f5edcb](https://linux-hardware.org/?probe=e437f5edcb) | Oct 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [2530967a90](https://linux-hardware.org/?probe=2530967a90) | Oct 17, 2023 |
| HP            | 1589                        | [9fca3eb994](https://linux-hardware.org/?probe=9fca3eb994) | Oct 17, 2023 |
| AZW           | SER V1                      | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [8422037a50](https://linux-hardware.org/?probe=8422037a50) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [6f8e6d4251](https://linux-hardware.org/?probe=6f8e6d4251) | Oct 17, 2023 |
| MSI           | MS-1T31                     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| ASUSTek       | PRIME H510M-E               | [375e62bbf4](https://linux-hardware.org/?probe=375e62bbf4) | Oct 17, 2023 |
| ASRock        | B365M Pro4                  | [c84d539a84](https://linux-hardware.org/?probe=c84d539a84) | Oct 17, 2023 |
| HP            | 8AB6 SMVB                   | [e88f9153df](https://linux-hardware.org/?probe=e88f9153df) | Oct 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [3f87e6216a](https://linux-hardware.org/?probe=3f87e6216a) | Oct 16, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [01bccdaf20](https://linux-hardware.org/?probe=01bccdaf20) | Oct 16, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [bc4d536f22](https://linux-hardware.org/?probe=bc4d536f22) | Oct 16, 2023 |
| MSI           | PRO B650-P WIFI             | [55d07d6ee2](https://linux-hardware.org/?probe=55d07d6ee2) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [66c28b84cf](https://linux-hardware.org/?probe=66c28b84cf) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | [982543f4bc](https://linux-hardware.org/?probe=982543f4bc) | Oct 16, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [d294330c51](https://linux-hardware.org/?probe=d294330c51) | Oct 16, 2023 |
| ASRock        | A320M-HDV R4.0              | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [37983381b0](https://linux-hardware.org/?probe=37983381b0) | Oct 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [6082a5c0de](https://linux-hardware.org/?probe=6082a5c0de) | Oct 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5330b349cb](https://linux-hardware.org/?probe=5330b349cb) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | [8bbdd141fe](https://linux-hardware.org/?probe=8bbdd141fe) | Oct 15, 2023 |
| HP            | 1589                        | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| MSI           | PRO B660M-P DDR4            | [364fd8849a](https://linux-hardware.org/?probe=364fd8849a) | Oct 15, 2023 |
| Gigabyte      | J1900M-D2P                  | [27881eaaac](https://linux-hardware.org/?probe=27881eaaac) | Oct 15, 2023 |
| Dell          | 0TY915                      | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell          | 0TY915                      | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| ASRock        | A320M-DGS                   | [a9599537b8](https://linux-hardware.org/?probe=a9599537b8) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | [7e4e4b6a5d](https://linux-hardware.org/?probe=7e4e4b6a5d) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | [b5d7147862](https://linux-hardware.org/?probe=b5d7147862) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | [642ecadbd2](https://linux-hardware.org/?probe=642ecadbd2) | Oct 15, 2023 |
| Dell          | 0Y2K8N A01                  | [32a0d75e98](https://linux-hardware.org/?probe=32a0d75e98) | Oct 14, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [70b85fc17d](https://linux-hardware.org/?probe=70b85fc17d) | Oct 14, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a86fd4e1d](https://linux-hardware.org/?probe=0a86fd4e1d) | Oct 14, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [039e898b5d](https://linux-hardware.org/?probe=039e898b5d) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [2edd75be93](https://linux-hardware.org/?probe=2edd75be93) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| ASRock        | H87 Performance             | [5d1713de03](https://linux-hardware.org/?probe=5d1713de03) | Oct 13, 2023 |
| AMI           | Intel                       | [888a4e1a0f](https://linux-hardware.org/?probe=888a4e1a0f) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f24ebc31a5](https://linux-hardware.org/?probe=f24ebc31a5) | Oct 13, 2023 |
| Dell          | 0WR7PY A03                  | [f59286c03f](https://linux-hardware.org/?probe=f59286c03f) | Oct 13, 2023 |
| HP            | 802F                        | [ed3a09f912](https://linux-hardware.org/?probe=ed3a09f912) | Oct 12, 2023 |
| HP            | 802F                        | [c2b0f9720e](https://linux-hardware.org/?probe=c2b0f9720e) | Oct 12, 2023 |
| MSI           | A68HM-E33                   | [71c8888ea4](https://linux-hardware.org/?probe=71c8888ea4) | Oct 12, 2023 |
| Gigabyte      | X570S UD                    | [c7b68dbfe1](https://linux-hardware.org/?probe=c7b68dbfe1) | Oct 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b71efdb817](https://linux-hardware.org/?probe=b71efdb817) | Oct 11, 2023 |
| HP            | 843B                        | [652027900b](https://linux-hardware.org/?probe=652027900b) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2e77fb6729](https://linux-hardware.org/?probe=2e77fb6729) | Oct 11, 2023 |
| ASRock        | B550 Steel Legend           | [c699787ab8](https://linux-hardware.org/?probe=c699787ab8) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | [fa0785421a](https://linux-hardware.org/?probe=fa0785421a) | Oct 11, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [3ceccfff97](https://linux-hardware.org/?probe=3ceccfff97) | Oct 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [9b5d4b21a7](https://linux-hardware.org/?probe=9b5d4b21a7) | Oct 11, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5566e985cf](https://linux-hardware.org/?probe=5566e985cf) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| Gigabyte      | J1900M-D2P                  | [8091bb0ceb](https://linux-hardware.org/?probe=8091bb0ceb) | Oct 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [19f6294d43](https://linux-hardware.org/?probe=19f6294d43) | Oct 10, 2023 |
| HP            | 89B5 A                      | [746fef0fc7](https://linux-hardware.org/?probe=746fef0fc7) | Oct 10, 2023 |
| ASRock        | B365M IB-R                  | [c1ac8c374a](https://linux-hardware.org/?probe=c1ac8c374a) | Oct 10, 2023 |
| Techvision    | TVI7309X B0                 | [5954b70bb9](https://linux-hardware.org/?probe=5954b70bb9) | Oct 10, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [107d1f4d14](https://linux-hardware.org/?probe=107d1f4d14) | Oct 09, 2023 |
| MSI           | A320M-A PRO                 | [4a1888b421](https://linux-hardware.org/?probe=4a1888b421) | Oct 09, 2023 |
| Dell          | 0478VN A00                  | [8881cc216c](https://linux-hardware.org/?probe=8881cc216c) | Oct 09, 2023 |
| Dell          | 0DF42J A00                  | [830730801b](https://linux-hardware.org/?probe=830730801b) | Oct 09, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7aa0b01da6](https://linux-hardware.org/?probe=7aa0b01da6) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [b249985c20](https://linux-hardware.org/?probe=b249985c20) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [90b88ff378](https://linux-hardware.org/?probe=90b88ff378) | Oct 09, 2023 |
| Gigabyte      | B550M DS3H                  | [7070641150](https://linux-hardware.org/?probe=7070641150) | Oct 08, 2023 |
| Gigabyte      | F2A55M-DS2                  | [dd44b0dc9e](https://linux-hardware.org/?probe=dd44b0dc9e) | Oct 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [26708ac497](https://linux-hardware.org/?probe=26708ac497) | Oct 08, 2023 |
| Gigabyte      | H310M S2H x.x               | [fd3c1d1196](https://linux-hardware.org/?probe=fd3c1d1196) | Oct 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| Gigabyte      | B550 VISION D-P             | [b0a2980430](https://linux-hardware.org/?probe=b0a2980430) | Oct 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [d43dc626c0](https://linux-hardware.org/?probe=d43dc626c0) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [998f01f73b](https://linux-hardware.org/?probe=998f01f73b) | Oct 08, 2023 |
| HP            | 158A                        | [a1c0d51b9d](https://linux-hardware.org/?probe=a1c0d51b9d) | Oct 08, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [86f56798dc](https://linux-hardware.org/?probe=86f56798dc) | Oct 07, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [0d980c4a61](https://linux-hardware.org/?probe=0d980c4a61) | Oct 07, 2023 |
| Acer          | Aspire X1900                | [38b7e52e6b](https://linux-hardware.org/?probe=38b7e52e6b) | Oct 06, 2023 |
| Gigabyte      | B85M-D3V-A                  | [1a20748a43](https://linux-hardware.org/?probe=1a20748a43) | Oct 06, 2023 |
| Gigabyte      | H81M-D2V                    | [a41f086304](https://linux-hardware.org/?probe=a41f086304) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6bf5869cab](https://linux-hardware.org/?probe=6bf5869cab) | Oct 06, 2023 |
| Dell          | 0N4YC8 A00                  | [76c6fdfad6](https://linux-hardware.org/?probe=76c6fdfad6) | Oct 06, 2023 |
| MSI           | B450M MORTAR MAX            | [a2fb75cc3e](https://linux-hardware.org/?probe=a2fb75cc3e) | Oct 06, 2023 |
| Medion        | MS-7707                     | [42bc6357f7](https://linux-hardware.org/?probe=42bc6357f7) | Oct 05, 2023 |
| HP            | 8906 SMVB                   | [010c54ccaf](https://linux-hardware.org/?probe=010c54ccaf) | Oct 05, 2023 |
| Dell          | 0478VN A00                  | [511df57852](https://linux-hardware.org/?probe=511df57852) | Oct 05, 2023 |
| ASUSTek       | P8H67                       | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9948b7ed73](https://linux-hardware.org/?probe=9948b7ed73) | Oct 05, 2023 |
| Dell          | 0N4YC8 A00                  | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | [d8f9e7b32a](https://linux-hardware.org/?probe=d8f9e7b32a) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | [ae798c007e](https://linux-hardware.org/?probe=ae798c007e) | Oct 05, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [0aa9a5ddc3](https://linux-hardware.org/?probe=0aa9a5ddc3) | Oct 05, 2023 |
| ASRock        | AD2700-ITX                  | [3aea9e7d2f](https://linux-hardware.org/?probe=3aea9e7d2f) | Oct 05, 2023 |
| Shenzhen M... | HX90G                       | [135859015c](https://linux-hardware.org/?probe=135859015c) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [08f5cef7f3](https://linux-hardware.org/?probe=08f5cef7f3) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| Dell          | 0DF42J A00                  | [a98397577c](https://linux-hardware.org/?probe=a98397577c) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [400e01b1bf](https://linux-hardware.org/?probe=400e01b1bf) | Oct 03, 2023 |
| HP            | 802E                        | [2d84b83c17](https://linux-hardware.org/?probe=2d84b83c17) | Oct 03, 2023 |
| HP            | 802E                        | [10fcb68621](https://linux-hardware.org/?probe=10fcb68621) | Oct 03, 2023 |
| Supermicro    | H8DM8-2                     | [5386350e20](https://linux-hardware.org/?probe=5386350e20) | Oct 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [b225569c1d](https://linux-hardware.org/?probe=b225569c1d) | Oct 02, 2023 |
| Dell          | 0YJPT1 A00                  | [59f53b1488](https://linux-hardware.org/?probe=59f53b1488) | Oct 02, 2023 |
| Dell          | 07PR60 A01                  | [020c2fbbf8](https://linux-hardware.org/?probe=020c2fbbf8) | Oct 02, 2023 |
| Unknown       | Unknown                     | [1f2e2a6b13](https://linux-hardware.org/?probe=1f2e2a6b13) | Oct 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [76c5466daa](https://linux-hardware.org/?probe=76c5466daa) | Oct 02, 2023 |
| Intel         | H110                        | [eaf6f0f81c](https://linux-hardware.org/?probe=eaf6f0f81c) | Oct 02, 2023 |
| Acer          | Aspire X1900                | [5d958ae7d1](https://linux-hardware.org/?probe=5d958ae7d1) | Oct 02, 2023 |
| ASRock        | H370M-ITX/ac                | [cf9e8e26c2](https://linux-hardware.org/?probe=cf9e8e26c2) | Oct 02, 2023 |
| MSI           | X99A RAIDER                 | [5442de3655](https://linux-hardware.org/?probe=5442de3655) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [b27cfa6ad6](https://linux-hardware.org/?probe=b27cfa6ad6) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [45b94d86b5](https://linux-hardware.org/?probe=45b94d86b5) | Oct 02, 2023 |
| ASRock        | B650E PG-ITX WiFi           | [10e1561364](https://linux-hardware.org/?probe=10e1561364) | Oct 01, 2023 |
| MSI           | X470 GAMING PLUS            | [113ab4dbc3](https://linux-hardware.org/?probe=113ab4dbc3) | Oct 01, 2023 |
| ASUSTek       | PRIME B450M-A               | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | Z170-DELUXE                 | [9e04efc2d9](https://linux-hardware.org/?probe=9e04efc2d9) | Oct 01, 2023 |
| ASRock        | X570 Taichi                 | [7a670fe0ef](https://linux-hardware.org/?probe=7a670fe0ef) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| ASUSTek       | Z170-A                      | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| MSI           | PRO B660M-A DDR4            | [a7683dc02d](https://linux-hardware.org/?probe=a7683dc02d) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| HP            | 8055                        | [3ddf31c78e](https://linux-hardware.org/?probe=3ddf31c78e) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| ASUSTek       | PRIME B450M-A               | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Intel         | H61                         | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Intel         | H61                         | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60c04875f1](https://linux-hardware.org/?probe=60c04875f1) | Sep 29, 2023 |
| ASUSTek       | PRIME X570-PRO              | [74ec125e88](https://linux-hardware.org/?probe=74ec125e88) | Sep 29, 2023 |
| ASUSTek       | PRIME X570-PRO              | [cc8c6efba3](https://linux-hardware.org/?probe=cc8c6efba3) | Sep 28, 2023 |
| Dell          | 0YJPT1 A00                  | [a0a41d401e](https://linux-hardware.org/?probe=a0a41d401e) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| Dell          | 0XC7MM A01                  | [9fdfc5a13f](https://linux-hardware.org/?probe=9fdfc5a13f) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | [2e3d19e919](https://linux-hardware.org/?probe=2e3d19e919) | Sep 28, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| Gigabyte      | B650M K                     | [73da1b7ade](https://linux-hardware.org/?probe=73da1b7ade) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Dell          | 0773VG A00                  | [a68caa37d8](https://linux-hardware.org/?probe=a68caa37d8) | Sep 26, 2023 |
| Dell          | 0773VG A00                  | [5e34f7d424](https://linux-hardware.org/?probe=5e34f7d424) | Sep 26, 2023 |
| Gigabyte      | B550M S2H                   | [f61801ddb3](https://linux-hardware.org/?probe=f61801ddb3) | Sep 26, 2023 |
| Gigabyte      | B550M DS3H                  | [3bb1109d44](https://linux-hardware.org/?probe=3bb1109d44) | Sep 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [85c6c01e63](https://linux-hardware.org/?probe=85c6c01e63) | Sep 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [4b0aff27e8](https://linux-hardware.org/?probe=4b0aff27e8) | Sep 26, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [b49d28bbd4](https://linux-hardware.org/?probe=b49d28bbd4) | Sep 26, 2023 |
| ASRock        | B450M Steel Legend          | [ccb7f736f6](https://linux-hardware.org/?probe=ccb7f736f6) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| MSI           | X99A RAIDER                 | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| ASUSTek       | P9D WS                      | [fd2133400d](https://linux-hardware.org/?probe=fd2133400d) | Sep 25, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | [a6ef2b5028](https://linux-hardware.org/?probe=a6ef2b5028) | Sep 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [b7dae6ef48](https://linux-hardware.org/?probe=b7dae6ef48) | Sep 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [f4d45948eb](https://linux-hardware.org/?probe=f4d45948eb) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | [1b8b856469](https://linux-hardware.org/?probe=1b8b856469) | Sep 25, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [23d9e87224](https://linux-hardware.org/?probe=23d9e87224) | Sep 24, 2023 |
| Gigabyte      | X570S UD                    | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | [7c0eb47c16](https://linux-hardware.org/?probe=7c0eb47c16) | Sep 24, 2023 |
| ASRock        | B150M Pro4/Hyper            | [6bd5055b96](https://linux-hardware.org/?probe=6bd5055b96) | Sep 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5ed3f9381a](https://linux-hardware.org/?probe=5ed3f9381a) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | [fa3021d826](https://linux-hardware.org/?probe=fa3021d826) | Sep 23, 2023 |
| ASRock        | N68C-S UCC                  | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f59df7021c](https://linux-hardware.org/?probe=f59df7021c) | Sep 23, 2023 |
| Gigabyte      | MZGLKBP-00                  | [678c17756d](https://linux-hardware.org/?probe=678c17756d) | Sep 23, 2023 |
| ASRock        | H61M/U3S3                   | [1d397abb90](https://linux-hardware.org/?probe=1d397abb90) | Sep 23, 2023 |
| Dell          | 00010C A00                  | [40d7defca4](https://linux-hardware.org/?probe=40d7defca4) | Sep 23, 2023 |
| Gigabyte      | B85-HD3                     | [5da83e8683](https://linux-hardware.org/?probe=5da83e8683) | Sep 23, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [5629e161ab](https://linux-hardware.org/?probe=5629e161ab) | Sep 23, 2023 |
| MSI           | MS-7388                     | [f5ee235af0](https://linux-hardware.org/?probe=f5ee235af0) | Sep 23, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | [1a81f24fbb](https://linux-hardware.org/?probe=1a81f24fbb) | Sep 23, 2023 |
| Dell          | 0KWVT8 A03                  | [c6f224508a](https://linux-hardware.org/?probe=c6f224508a) | Sep 23, 2023 |
| HP            | 3397                        | [fa230ba389](https://linux-hardware.org/?probe=fa230ba389) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | [3b9bbcebb0](https://linux-hardware.org/?probe=3b9bbcebb0) | Sep 23, 2023 |
| Dell          | 0PP150 A00                  | [766815ba45](https://linux-hardware.org/?probe=766815ba45) | Sep 22, 2023 |
| MSI           | H110M PRO-D                 | [40380b4dce](https://linux-hardware.org/?probe=40380b4dce) | Sep 22, 2023 |
| HP            | 834F                        | [b69b667f2c](https://linux-hardware.org/?probe=b69b667f2c) | Sep 22, 2023 |
| Gigabyte      | H61M-S2PV                   | [fd5d5651ce](https://linux-hardware.org/?probe=fd5d5651ce) | Sep 22, 2023 |
| MSI           | 760GM-P33                   | [6dfb722e45](https://linux-hardware.org/?probe=6dfb722e45) | Sep 22, 2023 |
| ASUSTek       | PRIME X570-P                | [21b73523cf](https://linux-hardware.org/?probe=21b73523cf) | Sep 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [2e715ca7b2](https://linux-hardware.org/?probe=2e715ca7b2) | Sep 22, 2023 |
| ASUSTek       | Rampage V EXTREME           | [fe545c13e7](https://linux-hardware.org/?probe=fe545c13e7) | Sep 22, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [80c7b750ea](https://linux-hardware.org/?probe=80c7b750ea) | Sep 21, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [609a91b51f](https://linux-hardware.org/?probe=609a91b51f) | Sep 21, 2023 |
| ANGXUN        | X99-DM3 V3.0                | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| Intel         | B75                         | [37b59e6605](https://linux-hardware.org/?probe=37b59e6605) | Sep 21, 2023 |
| HP            | 1495                        | [ad97ea883d](https://linux-hardware.org/?probe=ad97ea883d) | Sep 21, 2023 |
| HP            | 3047h                       | [cb19fdc589](https://linux-hardware.org/?probe=cb19fdc589) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| Gigabyte      | B360M D3H-CF                | [875f4f3f2a](https://linux-hardware.org/?probe=875f4f3f2a) | Sep 21, 2023 |
| ASUSTek       | V230IC                      | [aea46e7fc6](https://linux-hardware.org/?probe=aea46e7fc6) | Sep 21, 2023 |
| MSI           | Z270M MORTAR                | [ec0adfb60f](https://linux-hardware.org/?probe=ec0adfb60f) | Sep 21, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [5e05853c00](https://linux-hardware.org/?probe=5e05853c00) | Sep 20, 2023 |
| HP            | 3397                        | [f202c90e23](https://linux-hardware.org/?probe=f202c90e23) | Sep 20, 2023 |
| Dell          | 0WN7Y6 A01                  | [f4d4f80645](https://linux-hardware.org/?probe=f4d4f80645) | Sep 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | [624ebbd6c1](https://linux-hardware.org/?probe=624ebbd6c1) | Sep 20, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [238224ef08](https://linux-hardware.org/?probe=238224ef08) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Dell          | 06HR05 A00                  | [a01d6b8630](https://linux-hardware.org/?probe=a01d6b8630) | Sep 20, 2023 |
| MSI           | A320M-A PRO MAX             | [411b34f287](https://linux-hardware.org/?probe=411b34f287) | Sep 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [56d2a67030](https://linux-hardware.org/?probe=56d2a67030) | Sep 19, 2023 |
| Gigabyte      | J1900M-D2P                  | [1bd6653d3e](https://linux-hardware.org/?probe=1bd6653d3e) | Sep 19, 2023 |
| Positivo      | POS-EIH610EX 11187943       | [10fbe8fd9b](https://linux-hardware.org/?probe=10fbe8fd9b) | Sep 18, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [96a6758726](https://linux-hardware.org/?probe=96a6758726) | Sep 18, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [39d6e8a728](https://linux-hardware.org/?probe=39d6e8a728) | Sep 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [7e05f3299f](https://linux-hardware.org/?probe=7e05f3299f) | Sep 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [517795acfd](https://linux-hardware.org/?probe=517795acfd) | Sep 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5597daf348](https://linux-hardware.org/?probe=5597daf348) | Sep 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [b0de1885b9](https://linux-hardware.org/?probe=b0de1885b9) | Sep 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8566235f94](https://linux-hardware.org/?probe=8566235f94) | Sep 17, 2023 |
| Dell          | 0MGK50 A02                  | [ec87c19874](https://linux-hardware.org/?probe=ec87c19874) | Sep 17, 2023 |
| ASRock        | B450 Pro4                   | [2e8cd612d8](https://linux-hardware.org/?probe=2e8cd612d8) | Sep 17, 2023 |
| ASUSTek       | Pro H510M-C                 | [aff784bd75](https://linux-hardware.org/?probe=aff784bd75) | Sep 16, 2023 |
| ASUSTek       | PRIME H270-PRO              | [394d932643](https://linux-hardware.org/?probe=394d932643) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [83c2fb6018](https://linux-hardware.org/?probe=83c2fb6018) | Sep 16, 2023 |
| Intel         | DQ45CB AAE30148-207         | [2c74d735db](https://linux-hardware.org/?probe=2c74d735db) | Sep 16, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| HP            | 84FD                        | [d0845ca4d2](https://linux-hardware.org/?probe=d0845ca4d2) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| HP            | 3397                        | [3cf175e939](https://linux-hardware.org/?probe=3cf175e939) | Sep 14, 2023 |
| MSI           | 2A9C                        | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| ASRock        | B450M-HDV R4.0              | [305679af22](https://linux-hardware.org/?probe=305679af22) | Sep 14, 2023 |
| HP            | 8459                        | [e7cbc6d34d](https://linux-hardware.org/?probe=e7cbc6d34d) | Sep 14, 2023 |
| Dell          | 0YXT71 A02                  | [f462fe5985](https://linux-hardware.org/?probe=f462fe5985) | Sep 14, 2023 |
| Intel         | DH87MC AAG74242-401         | [6c37cc0b51](https://linux-hardware.org/?probe=6c37cc0b51) | Sep 14, 2023 |
| HP            | 843B                        | [08ce9ca0eb](https://linux-hardware.org/?probe=08ce9ca0eb) | Sep 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI          | [2ad1c71fce](https://linux-hardware.org/?probe=2ad1c71fce) | Sep 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [418eee8ea7](https://linux-hardware.org/?probe=418eee8ea7) | Sep 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | [746f94b75d](https://linux-hardware.org/?probe=746f94b75d) | Sep 13, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [035fb7f099](https://linux-hardware.org/?probe=035fb7f099) | Sep 13, 2023 |
| MSI           | MAG B460M MORTAR            | [c0980eee03](https://linux-hardware.org/?probe=c0980eee03) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | [20ec05f55b](https://linux-hardware.org/?probe=20ec05f55b) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | [172b7a1d48](https://linux-hardware.org/?probe=172b7a1d48) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [a7e93922ce](https://linux-hardware.org/?probe=a7e93922ce) | Sep 13, 2023 |
| Acer          | F690GVM                     | [a9a370c528](https://linux-hardware.org/?probe=a9a370c528) | Sep 13, 2023 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | [fd4e189b56](https://linux-hardware.org/?probe=fd4e189b56) | Sep 12, 2023 |
| Gigabyte      | B450M S2H                   | [9099ebc0a7](https://linux-hardware.org/?probe=9099ebc0a7) | Sep 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | [e1eea73611](https://linux-hardware.org/?probe=e1eea73611) | Sep 12, 2023 |
| HP            | 3397                        | [ed9caadb58](https://linux-hardware.org/?probe=ed9caadb58) | Sep 12, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [f5b3cd74bc](https://linux-hardware.org/?probe=f5b3cd74bc) | Sep 11, 2023 |
| Dell          | 0GXM1W A01                  | [ff9bf89fad](https://linux-hardware.org/?probe=ff9bf89fad) | Sep 11, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | [baeb174dc3](https://linux-hardware.org/?probe=baeb174dc3) | Sep 10, 2023 |
| ASRock        | B550M Pro4                  | [92eb1e3aa7](https://linux-hardware.org/?probe=92eb1e3aa7) | Sep 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [6dc842bbb4](https://linux-hardware.org/?probe=6dc842bbb4) | Sep 10, 2023 |
| Dell          | 042P49 A01                  | [fc47b9c2f4](https://linux-hardware.org/?probe=fc47b9c2f4) | Sep 10, 2023 |
| Dell          | 0GM819                      | [f7d8bdb2a3](https://linux-hardware.org/?probe=f7d8bdb2a3) | Sep 10, 2023 |
| Acer          | Veriton M2631 V:1.0         | [ec947814d1](https://linux-hardware.org/?probe=ec947814d1) | Sep 10, 2023 |
| ASRock        | H570M Pro4                  | [4124ca4b35](https://linux-hardware.org/?probe=4124ca4b35) | Sep 10, 2023 |
| ASRock        | H97M Pro4                   | [a875b11982](https://linux-hardware.org/?probe=a875b11982) | Sep 10, 2023 |
| Dell          | 084J0R A00                  | [25d0f0d7ef](https://linux-hardware.org/?probe=25d0f0d7ef) | Sep 10, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [7b441b9b50](https://linux-hardware.org/?probe=7b441b9b50) | Sep 10, 2023 |
| MSI           | MPG Z790I EDGE WIFI         | [1225463e4a](https://linux-hardware.org/?probe=1225463e4a) | Sep 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [7d3f7effe2](https://linux-hardware.org/?probe=7d3f7effe2) | Sep 09, 2023 |
| Unknown       | Unknown                     | [aa67f256bc](https://linux-hardware.org/?probe=aa67f256bc) | Sep 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c8e3d0d7f9](https://linux-hardware.org/?probe=c8e3d0d7f9) | Sep 09, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [b15cd2d6e5](https://linux-hardware.org/?probe=b15cd2d6e5) | Sep 09, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [d6302862b1](https://linux-hardware.org/?probe=d6302862b1) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | [fc7937d763](https://linux-hardware.org/?probe=fc7937d763) | Sep 09, 2023 |
| ASRock        | B450M Pro4                  | [a47195331c](https://linux-hardware.org/?probe=a47195331c) | Sep 08, 2023 |
| Lenovo        | SHARKBAY NOK                | [a09c6ad4a9](https://linux-hardware.org/?probe=a09c6ad4a9) | Sep 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [b5081191af](https://linux-hardware.org/?probe=b5081191af) | Sep 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6e57fc6cf2](https://linux-hardware.org/?probe=6e57fc6cf2) | Sep 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | [03a233a395](https://linux-hardware.org/?probe=03a233a395) | Sep 08, 2023 |
| HP            | ProLiant ML110 G7           | [5f806b31b4](https://linux-hardware.org/?probe=5f806b31b4) | Sep 08, 2023 |
| Gigabyte      | G41MT-D3                    | [0940dc7ebd](https://linux-hardware.org/?probe=0940dc7ebd) | Sep 08, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [860985ecc0](https://linux-hardware.org/?probe=860985ecc0) | Sep 08, 2023 |
| MSI           | X99A RAIDER                 | [362b2dadfc](https://linux-hardware.org/?probe=362b2dadfc) | Sep 08, 2023 |
| HP            | 1497                        | [1729554f58](https://linux-hardware.org/?probe=1729554f58) | Sep 07, 2023 |
| Dell          | 0J37VM A01                  | [7781be38be](https://linux-hardware.org/?probe=7781be38be) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [d98f5a5a06](https://linux-hardware.org/?probe=d98f5a5a06) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [35b6b3a9dd](https://linux-hardware.org/?probe=35b6b3a9dd) | Sep 07, 2023 |
| Dell          | 0NDYHG A01                  | [250bc7b8ea](https://linux-hardware.org/?probe=250bc7b8ea) | Sep 07, 2023 |
| NZXT          | N7 Z370                     | [34a23bdc5f](https://linux-hardware.org/?probe=34a23bdc5f) | Sep 07, 2023 |
| Dell          | 088DT1 A01                  | [e7d12d040e](https://linux-hardware.org/?probe=e7d12d040e) | Sep 07, 2023 |
| MSI           | X99A RAIDER                 | [0434d08b59](https://linux-hardware.org/?probe=0434d08b59) | Sep 07, 2023 |
| Gigabyte      | G41MT-D3                    | [f0c3188082](https://linux-hardware.org/?probe=f0c3188082) | Sep 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [b17a5edce5](https://linux-hardware.org/?probe=b17a5edce5) | Sep 06, 2023 |
| Pegatron      | 2AB6                        | [40b17904fa](https://linux-hardware.org/?probe=40b17904fa) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [09e4ad77a9](https://linux-hardware.org/?probe=09e4ad77a9) | Sep 06, 2023 |
| HP            | 3047h                       | [9b6ecf8471](https://linux-hardware.org/?probe=9b6ecf8471) | Sep 06, 2023 |
| HP            | 3047h                       | [51ba95dc5a](https://linux-hardware.org/?probe=51ba95dc5a) | Sep 06, 2023 |
| ASRock        | B650E PG-ITX WiFi           | [9dd5c2a861](https://linux-hardware.org/?probe=9dd5c2a861) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Pegatron      | TRUCKEE                     | [145414b8e3](https://linux-hardware.org/?probe=145414b8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [7b99e058ff](https://linux-hardware.org/?probe=7b99e058ff) | Sep 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [7db6779b5c](https://linux-hardware.org/?probe=7db6779b5c) | Sep 06, 2023 |
| MSI           | A320M PRO-VH PLUS           | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | 82E0                        | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | [0fa982f7ad](https://linux-hardware.org/?probe=0fa982f7ad) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | [9ab25d4913](https://linux-hardware.org/?probe=9ab25d4913) | Sep 05, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [44c55bd588](https://linux-hardware.org/?probe=44c55bd588) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| MSI           | X99A RAIDER                 | [c06fdd0648](https://linux-hardware.org/?probe=c06fdd0648) | Sep 05, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [d20cf2e835](https://linux-hardware.org/?probe=d20cf2e835) | Sep 05, 2023 |
| ASRock        | H310M-STX                   | [5585353638](https://linux-hardware.org/?probe=5585353638) | Sep 04, 2023 |
| ASUSTek       | X99-M WS                    | [f324b3dd33](https://linux-hardware.org/?probe=f324b3dd33) | Sep 04, 2023 |
| ASUSTek       | Pro H510M-C                 | [ea823862a6](https://linux-hardware.org/?probe=ea823862a6) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [d99ec42689](https://linux-hardware.org/?probe=d99ec42689) | Sep 04, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [59b20fdfab](https://linux-hardware.org/?probe=59b20fdfab) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [80a94d69c2](https://linux-hardware.org/?probe=80a94d69c2) | Sep 04, 2023 |
| MSI           | X99A RAIDER                 | [6bf9db20f8](https://linux-hardware.org/?probe=6bf9db20f8) | Sep 04, 2023 |
| Dell          | 042P49 A01                  | [29e55d4d72](https://linux-hardware.org/?probe=29e55d4d72) | Sep 04, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [7e0c89dfdb](https://linux-hardware.org/?probe=7e0c89dfdb) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [2252b35243](https://linux-hardware.org/?probe=2252b35243) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [dd19cc0d48](https://linux-hardware.org/?probe=dd19cc0d48) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [fc0731667e](https://linux-hardware.org/?probe=fc0731667e) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | [5e3f2f01d4](https://linux-hardware.org/?probe=5e3f2f01d4) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [926751fb6e](https://linux-hardware.org/?probe=926751fb6e) | Sep 03, 2023 |
| Gigabyte      | X79-UP4                     | [3593994f4e](https://linux-hardware.org/?probe=3593994f4e) | Sep 03, 2023 |
| Dell          | 0HHV7N A00                  | [9ae746229d](https://linux-hardware.org/?probe=9ae746229d) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [c4c911d725](https://linux-hardware.org/?probe=c4c911d725) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [bc7e99e576](https://linux-hardware.org/?probe=bc7e99e576) | Sep 02, 2023 |
| Gigabyte      | MZGLKBP-00                  | [e6c5ae208f](https://linux-hardware.org/?probe=e6c5ae208f) | Sep 02, 2023 |
| Dell          | 0GY6Y8 A01                  | [f592e65a04](https://linux-hardware.org/?probe=f592e65a04) | Sep 02, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [d7fcde026e](https://linux-hardware.org/?probe=d7fcde026e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| HP            | 89B5 A                      | [3b6a46c308](https://linux-hardware.org/?probe=3b6a46c308) | Sep 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [90be513b41](https://linux-hardware.org/?probe=90be513b41) | Sep 01, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | [62d1008e3a](https://linux-hardware.org/?probe=62d1008e3a) | Sep 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [81e9e055de](https://linux-hardware.org/?probe=81e9e055de) | Sep 01, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a4ee14b9ac](https://linux-hardware.org/?probe=a4ee14b9ac) | Sep 01, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [dd5735f315](https://linux-hardware.org/?probe=dd5735f315) | Sep 01, 2023 |
| Unknown       | H110M2                      | [bff031410a](https://linux-hardware.org/?probe=bff031410a) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| Gigabyte      | Z270X-Gaming K5             | [189647b3df](https://linux-hardware.org/?probe=189647b3df) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | [c38af5d04d](https://linux-hardware.org/?probe=c38af5d04d) | Aug 31, 2023 |
| Gigabyte      | H77N-WIFI                   | [84ed05802d](https://linux-hardware.org/?probe=84ed05802d) | Aug 31, 2023 |
| Gigabyte      | D525TUD                     | [9a459d2372](https://linux-hardware.org/?probe=9a459d2372) | Aug 31, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ffb1e72844](https://linux-hardware.org/?probe=ffb1e72844) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | [e2b97e4436](https://linux-hardware.org/?probe=e2b97e4436) | Aug 31, 2023 |
| MSI           | 970 GAMING                  | [f5aaee7de3](https://linux-hardware.org/?probe=f5aaee7de3) | Aug 31, 2023 |
| ASUSTek       | PHOENIX                     | [5fa96dfd97](https://linux-hardware.org/?probe=5fa96dfd97) | Aug 31, 2023 |
| Gigabyte      | MZGLKBP-00                  | [2ed0efb0a0](https://linux-hardware.org/?probe=2ed0efb0a0) | Aug 31, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [04d647ae08](https://linux-hardware.org/?probe=04d647ae08) | Aug 30, 2023 |
| Dell          | 0J2J3Y A00                  | [57ac609885](https://linux-hardware.org/?probe=57ac609885) | Aug 30, 2023 |
| Gigabyte      | Z270X-Gaming K5             | [193a50f761](https://linux-hardware.org/?probe=193a50f761) | Aug 30, 2023 |
| MSI           | H110M PRO-VD PLUS           | [a75e60a457](https://linux-hardware.org/?probe=a75e60a457) | Aug 30, 2023 |
| ASUSTek       | PRIME Z490-A                | [3cfa79235e](https://linux-hardware.org/?probe=3cfa79235e) | Aug 30, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [b93e0fc32b](https://linux-hardware.org/?probe=b93e0fc32b) | Aug 30, 2023 |
| MSI           | Z270M MORTAR                | [416723b60c](https://linux-hardware.org/?probe=416723b60c) | Aug 30, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [44e98cb157](https://linux-hardware.org/?probe=44e98cb157) | Aug 29, 2023 |
| Gigabyte      | G41MT-D3                    | [a2f594cf56](https://linux-hardware.org/?probe=a2f594cf56) | Aug 29, 2023 |
| MSI           | Z370-A PRO                  | [d9a6d27a28](https://linux-hardware.org/?probe=d9a6d27a28) | Aug 29, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [7da432892e](https://linux-hardware.org/?probe=7da432892e) | Aug 29, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [1fd98a124f](https://linux-hardware.org/?probe=1fd98a124f) | Aug 29, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [7674d12aa5](https://linux-hardware.org/?probe=7674d12aa5) | Aug 28, 2023 |
| Fujitsu       | D3817-A1 S26361-D3817-A1... | [50e64dbfa2](https://linux-hardware.org/?probe=50e64dbfa2) | Aug 28, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [b68e4634b7](https://linux-hardware.org/?probe=b68e4634b7) | Aug 28, 2023 |
| Gigabyte      | EP45-DS3L                   | [c326205a9b](https://linux-hardware.org/?probe=c326205a9b) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [492a021411](https://linux-hardware.org/?probe=492a021411) | Aug 27, 2023 |
| Acer          | Veriton X2631G V:1.0        | [47b9d876af](https://linux-hardware.org/?probe=47b9d876af) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [c1bea53459](https://linux-hardware.org/?probe=c1bea53459) | Aug 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [d80e4744e9](https://linux-hardware.org/?probe=d80e4744e9) | Aug 27, 2023 |
| MSI           | MS-7388                     | [42530086f2](https://linux-hardware.org/?probe=42530086f2) | Aug 27, 2023 |
| Dell          | 04Y8V0 A02                  | [629b07f8bc](https://linux-hardware.org/?probe=629b07f8bc) | Aug 27, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [f71c3553e6](https://linux-hardware.org/?probe=f71c3553e6) | Aug 27, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [08748d2c86](https://linux-hardware.org/?probe=08748d2c86) | Aug 27, 2023 |
| ASUSTek       | Z170-P                      | [9e90f8b308](https://linux-hardware.org/?probe=9e90f8b308) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [9bd4ef3aac](https://linux-hardware.org/?probe=9bd4ef3aac) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [978f1e9fa5](https://linux-hardware.org/?probe=978f1e9fa5) | Aug 26, 2023 |
| AZW           | U59                         | [ea7bf087cc](https://linux-hardware.org/?probe=ea7bf087cc) | Aug 26, 2023 |
| AZW           | U59                         | [d35717e2e4](https://linux-hardware.org/?probe=d35717e2e4) | Aug 26, 2023 |
| ASRock        | B560 Steel Legend           | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| MSI           | MS-B9321                    | [07564a2fc4](https://linux-hardware.org/?probe=07564a2fc4) | Aug 25, 2023 |
| Dell          | 0HHV7N A00                  | [1bcc49b615](https://linux-hardware.org/?probe=1bcc49b615) | Aug 25, 2023 |
| MSI           | MS-B9321                    | [df54486a48](https://linux-hardware.org/?probe=df54486a48) | Aug 25, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [771adfa310](https://linux-hardware.org/?probe=771adfa310) | Aug 25, 2023 |
| MSI           | MS-7388                     | [5c1e4b0c2b](https://linux-hardware.org/?probe=5c1e4b0c2b) | Aug 25, 2023 |
| Acer          | Veriton N4640G              | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| HP            | 3047h                       | [5c415723ef](https://linux-hardware.org/?probe=5c415723ef) | Aug 24, 2023 |
| Dell          | 088DT1 A01                  | [0d9ddb7de2](https://linux-hardware.org/?probe=0d9ddb7de2) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | [ba401056e8](https://linux-hardware.org/?probe=ba401056e8) | Aug 24, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [6486781183](https://linux-hardware.org/?probe=6486781183) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | [d51fb378a1](https://linux-hardware.org/?probe=d51fb378a1) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c86651dbd3](https://linux-hardware.org/?probe=c86651dbd3) | Aug 24, 2023 |
| MSI           | A320M-A PRO                 | [25dc707bff](https://linux-hardware.org/?probe=25dc707bff) | Aug 24, 2023 |
| ASRock        | B560M-ITX/ac                | [1330f2ac2a](https://linux-hardware.org/?probe=1330f2ac2a) | Aug 24, 2023 |
| Gigabyte      | H310M M.2                   | [9b1205f50a](https://linux-hardware.org/?probe=9b1205f50a) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | [a06cf8de37](https://linux-hardware.org/?probe=a06cf8de37) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | [b6591e9fd9](https://linux-hardware.org/?probe=b6591e9fd9) | Aug 24, 2023 |
| AZW           | GTR V02                     | [6c91212b1a](https://linux-hardware.org/?probe=6c91212b1a) | Aug 24, 2023 |
| ASRock        | FP6D4-P1                    | [722789f2ac](https://linux-hardware.org/?probe=722789f2ac) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [fd9fa02e66](https://linux-hardware.org/?probe=fd9fa02e66) | Aug 23, 2023 |
| MSI           | B550-A PRO                  | [f2f57d0e61](https://linux-hardware.org/?probe=f2f57d0e61) | Aug 23, 2023 |
| Gigabyte      | B85M-D3V-A                  | [e11053f833](https://linux-hardware.org/?probe=e11053f833) | Aug 23, 2023 |
| ASRock        | Z77 Extreme6                | [6477cdd647](https://linux-hardware.org/?probe=6477cdd647) | Aug 23, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [e9b32aa827](https://linux-hardware.org/?probe=e9b32aa827) | Aug 23, 2023 |
| MSI           | Z370-OC PRO                 | [4ee0bb1c63](https://linux-hardware.org/?probe=4ee0bb1c63) | Aug 23, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [64f3da359d](https://linux-hardware.org/?probe=64f3da359d) | Aug 22, 2023 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [fe7b3d01bb](https://linux-hardware.org/?probe=fe7b3d01bb) | Aug 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [73a003bf4b](https://linux-hardware.org/?probe=73a003bf4b) | Aug 22, 2023 |
| MSI           | H510M-A PRO                 | [e405022cc9](https://linux-hardware.org/?probe=e405022cc9) | Aug 22, 2023 |
| MSI           | Z370-OC PRO                 | [bbd85c94d6](https://linux-hardware.org/?probe=bbd85c94d6) | Aug 22, 2023 |
| ASUSTek       | B460M-N                     | [382640772b](https://linux-hardware.org/?probe=382640772b) | Aug 22, 2023 |
| Gigabyte      | X570 GAMING X               | [6a3c737df2](https://linux-hardware.org/?probe=6a3c737df2) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [05c761f480](https://linux-hardware.org/?probe=05c761f480) | Aug 22, 2023 |
| Intel         | DH77EB AAG39073-304         | [70399bc4c6](https://linux-hardware.org/?probe=70399bc4c6) | Aug 21, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [fdfc3b92f9](https://linux-hardware.org/?probe=fdfc3b92f9) | Aug 21, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [09d57c6701](https://linux-hardware.org/?probe=09d57c6701) | Aug 21, 2023 |
| HP            | 3048h                       | [959637abde](https://linux-hardware.org/?probe=959637abde) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [735e03f0f9](https://linux-hardware.org/?probe=735e03f0f9) | Aug 21, 2023 |
| MSI           | PRO B650M-A WIFI            | [da3f4808a1](https://linux-hardware.org/?probe=da3f4808a1) | Aug 20, 2023 |
| ASRock        | A520M-HDV                   | [cb333c6fae](https://linux-hardware.org/?probe=cb333c6fae) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | [c3a8668cee](https://linux-hardware.org/?probe=c3a8668cee) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | [7da89c9360](https://linux-hardware.org/?probe=7da89c9360) | Aug 20, 2023 |
| MSI           | H310M PRO-VDH               | [c6f278a589](https://linux-hardware.org/?probe=c6f278a589) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | [05507d2151](https://linux-hardware.org/?probe=05507d2151) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | [b91ffcb2be](https://linux-hardware.org/?probe=b91ffcb2be) | Aug 20, 2023 |
| HP            | 3032h                       | [f3292df409](https://linux-hardware.org/?probe=f3292df409) | Aug 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [1b7a1416fc](https://linux-hardware.org/?probe=1b7a1416fc) | Aug 20, 2023 |
| Dell          | 04Y8V0 A02                  | [645bd9ed6b](https://linux-hardware.org/?probe=645bd9ed6b) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [978af80f5a](https://linux-hardware.org/?probe=978af80f5a) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [06daace50c](https://linux-hardware.org/?probe=06daace50c) | Aug 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [a15e796833](https://linux-hardware.org/?probe=a15e796833) | Aug 19, 2023 |
| ASUSTek       | M4A77                       | [89bb5a2821](https://linux-hardware.org/?probe=89bb5a2821) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [c99b76f9fe](https://linux-hardware.org/?probe=c99b76f9fe) | Aug 19, 2023 |
| Gigabyte      | B450M H                     | [722707e986](https://linux-hardware.org/?probe=722707e986) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| Dell          | 06D7TR A00                  | [f719885fe3](https://linux-hardware.org/?probe=f719885fe3) | Aug 18, 2023 |
| MSI           | X470 GAMING M7 AC           | [92f8391f8f](https://linux-hardware.org/?probe=92f8391f8f) | Aug 18, 2023 |
| ASUSTek       | Z97-PRO                     | [607356bb8f](https://linux-hardware.org/?probe=607356bb8f) | Aug 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [8958908392](https://linux-hardware.org/?probe=8958908392) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [4b8894823c](https://linux-hardware.org/?probe=4b8894823c) | Aug 17, 2023 |
| ASUSTek       | Pro B550M-C                 | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [ae88c56896](https://linux-hardware.org/?probe=ae88c56896) | Aug 17, 2023 |
| ASRock        | A320M-HD R4.0               | [f67dd298b1](https://linux-hardware.org/?probe=f67dd298b1) | Aug 16, 2023 |
| Dell          | 0VRWRC A00                  | [b27f36262e](https://linux-hardware.org/?probe=b27f36262e) | Aug 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [725cdd1013](https://linux-hardware.org/?probe=725cdd1013) | Aug 16, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [1ff9bff198](https://linux-hardware.org/?probe=1ff9bff198) | Aug 15, 2023 |
| HP            | 3047h                       | [b136128b47](https://linux-hardware.org/?probe=b136128b47) | Aug 15, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [4ac83eed41](https://linux-hardware.org/?probe=4ac83eed41) | Aug 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [12c4ed323e](https://linux-hardware.org/?probe=12c4ed323e) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [6e7b731daa](https://linux-hardware.org/?probe=6e7b731daa) | Aug 15, 2023 |
| Medion        | MS-7800                     | [afab92f1e4](https://linux-hardware.org/?probe=afab92f1e4) | Aug 14, 2023 |
| MSI           | H510M PRO                   | [df350cd466](https://linux-hardware.org/?probe=df350cd466) | Aug 14, 2023 |
| Lenovo        | 1046 SBB1C50531 WIN 3556... | [f24668bfd7](https://linux-hardware.org/?probe=f24668bfd7) | Aug 14, 2023 |
| Acer          | Veriton X2640G V:1.0        | [f4ba515a8d](https://linux-hardware.org/?probe=f4ba515a8d) | Aug 14, 2023 |
| Acer          | Veriton X2640G V:1.0        | [2473d1c807](https://linux-hardware.org/?probe=2473d1c807) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [d2ccdc066b](https://linux-hardware.org/?probe=d2ccdc066b) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [c939a92f1d](https://linux-hardware.org/?probe=c939a92f1d) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [56efab026f](https://linux-hardware.org/?probe=56efab026f) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [cc343d2dce](https://linux-hardware.org/?probe=cc343d2dce) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A               | [361ad7057c](https://linux-hardware.org/?probe=361ad7057c) | Aug 13, 2023 |
| MSI           | X99A RAIDER                 | [88056b62e3](https://linux-hardware.org/?probe=88056b62e3) | Aug 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [45cb1198bb](https://linux-hardware.org/?probe=45cb1198bb) | Aug 13, 2023 |
| HP            | 0B4Ch D                     | [b718d1c1f8](https://linux-hardware.org/?probe=b718d1c1f8) | Aug 13, 2023 |
| HP            | 3646h                       | [b3c30163f9](https://linux-hardware.org/?probe=b3c30163f9) | Aug 13, 2023 |
| HP            | 3646h                       | [180d25235f](https://linux-hardware.org/?probe=180d25235f) | Aug 13, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| ASRock        | H55M-LE                     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [57a63573fc](https://linux-hardware.org/?probe=57a63573fc) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [22690b9d65](https://linux-hardware.org/?probe=22690b9d65) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Unknown       | Unknown                     | [4b174f07d2](https://linux-hardware.org/?probe=4b174f07d2) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| ASUSTek       | P8Z68-V LE                  | [a88d7e81e5](https://linux-hardware.org/?probe=a88d7e81e5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [7da6954bc5](https://linux-hardware.org/?probe=7da6954bc5) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| Unknown       | Unknown                     | [09037ac346](https://linux-hardware.org/?probe=09037ac346) | Aug 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [466419add0](https://linux-hardware.org/?probe=466419add0) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| Unknown       | HX90                        | [7a14bb927e](https://linux-hardware.org/?probe=7a14bb927e) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS            | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| Gigabyte      | H510M S2H                   | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| HP            | 3397                        | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| ASUSTek       | PHOENIX                     | [388bcf4158](https://linux-hardware.org/?probe=388bcf4158) | Aug 08, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3d4073bb1d](https://linux-hardware.org/?probe=3d4073bb1d) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| ASRock        | X470 Taichi                 | [f9d29dca0d](https://linux-hardware.org/?probe=f9d29dca0d) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [932391bfea](https://linux-hardware.org/?probe=932391bfea) | Aug 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [8add0a69cc](https://linux-hardware.org/?probe=8add0a69cc) | Aug 05, 2023 |
| Gateway       | SX2185                      | [a6df16b355](https://linux-hardware.org/?probe=a6df16b355) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [40bc2f506a](https://linux-hardware.org/?probe=40bc2f506a) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [364b15d850](https://linux-hardware.org/?probe=364b15d850) | Aug 05, 2023 |
| Intel         | B75                         | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| ASUSTek       | PHOENIX                     | [193262b7ea](https://linux-hardware.org/?probe=193262b7ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| AZW           | GTR V02                     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| Dell          | 05XGC8 A01                  | [de1c7d119e](https://linux-hardware.org/?probe=de1c7d119e) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3c3d90d709](https://linux-hardware.org/?probe=3c3d90d709) | Aug 04, 2023 |
| ASUSTek       | PRIME B550M-A               | [c0a4bb6c7e](https://linux-hardware.org/?probe=c0a4bb6c7e) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| HP            | 1791                        | [61285d3724](https://linux-hardware.org/?probe=61285d3724) | Aug 03, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [2d10ecdff1](https://linux-hardware.org/?probe=2d10ecdff1) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3f5df1b569](https://linux-hardware.org/?probe=3f5df1b569) | Aug 03, 2023 |
| ASRock        | Z170 Gaming K4              | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c66b1ed22c](https://linux-hardware.org/?probe=c66b1ed22c) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | [b8a5aee838](https://linux-hardware.org/?probe=b8a5aee838) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| MSI           | B450M BAZOOKA V2            | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| ASRock        | H61M/U3S3                   | [33c887e577](https://linux-hardware.org/?probe=33c887e577) | Aug 01, 2023 |
| Unknown       | Unknown                     | [7a5ef06c39](https://linux-hardware.org/?probe=7a5ef06c39) | Aug 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [afbf5d75c1](https://linux-hardware.org/?probe=afbf5d75c1) | Jul 31, 2023 |
| ASRock        | H110M-HG4                   | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | [a7cf8e8ef1](https://linux-hardware.org/?probe=a7cf8e8ef1) | Jul 31, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a3bbf1ecd0](https://linux-hardware.org/?probe=a3bbf1ecd0) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| HP            | 8056                        | [3a98a11778](https://linux-hardware.org/?probe=3a98a11778) | Jul 30, 2023 |
| HP            | 0AECh D                     | [50c84d005e](https://linux-hardware.org/?probe=50c84d005e) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| HP            | 8617                        | [0c3ee28cd8](https://linux-hardware.org/?probe=0c3ee28cd8) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| MSI           | A320M PRO-VH PLUS           | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | [bcfe09b617](https://linux-hardware.org/?probe=bcfe09b617) | Jul 29, 2023 |
| HP            | 3397                        | [98e4e362d9](https://linux-hardware.org/?probe=98e4e362d9) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ASUSTek       | H110M-D                     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| MSI           | A320M PRO-VH                | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| ASRock        | H110M-HG4                   | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Gigabyte      | B550 GAMING X V2            | [dcd24dfdc7](https://linux-hardware.org/?probe=dcd24dfdc7) | Jul 28, 2023 |
| ASUSTek       | WS C246 PRO                 | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [2e0e88694a](https://linux-hardware.org/?probe=2e0e88694a) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | [f7c6565b62](https://linux-hardware.org/?probe=f7c6565b62) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [49daa98623](https://linux-hardware.org/?probe=49daa98623) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| Gigabyte      | H77N-WIFI                   | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| ASUSTek       | PHOENIX                     | [aad7b03818](https://linux-hardware.org/?probe=aad7b03818) | Jul 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [02cf19407b](https://linux-hardware.org/?probe=02cf19407b) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| MSI           | X99A RAIDER                 | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| MSI           | A520M-A PRO                 | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [0ecaae8a05](https://linux-hardware.org/?probe=0ecaae8a05) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| Unknown       | Unknown                     | [a7d120e20a](https://linux-hardware.org/?probe=a7d120e20a) | Jul 24, 2023 |
| ASUSTek       | PHOENIX                     | [66ab03991c](https://linux-hardware.org/?probe=66ab03991c) | Jul 24, 2023 |
| Gigabyte      | B75M-D2V                    | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [b892c011a8](https://linux-hardware.org/?probe=b892c011a8) | Jul 24, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [2afa2c2afe](https://linux-hardware.org/?probe=2afa2c2afe) | Jul 23, 2023 |
| Gigabyte      | H510M S2H V2                | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [e1f3c75353](https://linux-hardware.org/?probe=e1f3c75353) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| Gigabyte      | H61MS                       | [545d840e2f](https://linux-hardware.org/?probe=545d840e2f) | Jul 23, 2023 |
| ASUSTek       | PRIME Z370-A                | [9a2136d9ef](https://linux-hardware.org/?probe=9a2136d9ef) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| Dell          | 06D7TR A00                  | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [51ca7593a6](https://linux-hardware.org/?probe=51ca7593a6) | Jul 22, 2023 |
| Kllisre       | X99-B5 V1.1                 | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [8c79a454ff](https://linux-hardware.org/?probe=8c79a454ff) | Jul 21, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| MSI           | PRO B550-VC                 | [5439295c30](https://linux-hardware.org/?probe=5439295c30) | Jul 20, 2023 |
| Dell          | 00010C A00                  | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| ASUSTek       | PRIME Z270-P                | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| ASRock        | B450M Pro4 R2.0             | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | [0296e5fd5c](https://linux-hardware.org/?probe=0296e5fd5c) | Jul 18, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [14478a9226](https://linux-hardware.org/?probe=14478a9226) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3618885533](https://linux-hardware.org/?probe=3618885533) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| ASUSTek       | M11AD                       | [4019d4eb57](https://linux-hardware.org/?probe=4019d4eb57) | Jul 18, 2023 |
| MSI           | IONA                        | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [bb84df2364](https://linux-hardware.org/?probe=bb84df2364) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | [b8caf7c9a3](https://linux-hardware.org/?probe=b8caf7c9a3) | Jul 18, 2023 |
| HP            | 3048h                       | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [49e298a314](https://linux-hardware.org/?probe=49e298a314) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | [d8595efd58](https://linux-hardware.org/?probe=d8595efd58) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| Dell          | 0WMJ54 A01                  | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| MSI           | 2A9C                        | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| HP            | ProLiant ML110 G7           | [2278b34727](https://linux-hardware.org/?probe=2278b34727) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [3becbb23af](https://linux-hardware.org/?probe=3becbb23af) | Jul 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [14bae4d3e7](https://linux-hardware.org/?probe=14bae4d3e7) | Jul 15, 2023 |
| Gateway       | SX2185                      | [1fe932f485](https://linux-hardware.org/?probe=1fe932f485) | Jul 15, 2023 |
| Gateway       | SX2185                      | [00e7bb0f9f](https://linux-hardware.org/?probe=00e7bb0f9f) | Jul 15, 2023 |
| ASRock        | X670E Steel Legend          | [f25464fb37](https://linux-hardware.org/?probe=f25464fb37) | Jul 15, 2023 |
| ASUSTek       | A88XM-A                     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4e78c933e4](https://linux-hardware.org/?probe=4e78c933e4) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| ASUSTek       | PRIME B365M-A               | [62099e9da7](https://linux-hardware.org/?probe=62099e9da7) | Jul 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [065aed3358](https://linux-hardware.org/?probe=065aed3358) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [d132761a85](https://linux-hardware.org/?probe=d132761a85) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | [70345fff08](https://linux-hardware.org/?probe=70345fff08) | Jul 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [96921926b1](https://linux-hardware.org/?probe=96921926b1) | Jul 14, 2023 |
| Gigabyte      | H77N-WIFI                   | [8ee665fb8f](https://linux-hardware.org/?probe=8ee665fb8f) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| Gigabyte      | P75-D3P                     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [fadd5eeba6](https://linux-hardware.org/?probe=fadd5eeba6) | Jul 13, 2023 |
| Dell          | 0GY6Y8 A01                  | [144711a0e0](https://linux-hardware.org/?probe=144711a0e0) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| MSI           | MAG B550M BAZOOKA           | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| MSI           | 970A-G46                    | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| ASRock        | B550M Pro4                  | [18a8fc202c](https://linux-hardware.org/?probe=18a8fc202c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [5c12592f23](https://linux-hardware.org/?probe=5c12592f23) | Jul 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [2b544082c2](https://linux-hardware.org/?probe=2b544082c2) | Jul 11, 2023 |
| Gigabyte      | J1900M-D2P                  | [a9e19d3887](https://linux-hardware.org/?probe=a9e19d3887) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| ASUSTek       | PRIME B250M-D               | [304630d909](https://linux-hardware.org/?probe=304630d909) | Jul 11, 2023 |
| Gigabyte      | B75M-D2V                    | [2749c7cf78](https://linux-hardware.org/?probe=2749c7cf78) | Jul 11, 2023 |
| Pegatron      | 2AD5                        | [04c6c9ba2b](https://linux-hardware.org/?probe=04c6c9ba2b) | Jul 10, 2023 |
| ASUSTek       | PRIME X470-PRO              | [eca6eabcb2](https://linux-hardware.org/?probe=eca6eabcb2) | Jul 10, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ac8df9628d](https://linux-hardware.org/?probe=ac8df9628d) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [dcf418007d](https://linux-hardware.org/?probe=dcf418007d) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [b515a2980e](https://linux-hardware.org/?probe=b515a2980e) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | [ceccedafbd](https://linux-hardware.org/?probe=ceccedafbd) | Jul 10, 2023 |
| ASUSTek       | PHOENIX                     | [88c02f40e7](https://linux-hardware.org/?probe=88c02f40e7) | Jul 09, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c09e539c94](https://linux-hardware.org/?probe=c09e539c94) | Jul 09, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9a2170442d](https://linux-hardware.org/?probe=9a2170442d) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [150b2a2675](https://linux-hardware.org/?probe=150b2a2675) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | [a887a01dd7](https://linux-hardware.org/?probe=a887a01dd7) | Jul 09, 2023 |
| ASUSTek       | PRIME H310M-K               | [e7c0c87a14](https://linux-hardware.org/?probe=e7c0c87a14) | Jul 09, 2023 |
| Lenovo        | SHARKBAY NOK                | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [d9880a123f](https://linux-hardware.org/?probe=d9880a123f) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| MSI           | B250M PRO-VD                | [f9c2ea463a](https://linux-hardware.org/?probe=f9c2ea463a) | Jul 09, 2023 |
| Dell          | 00F82W A00                  | [603d370b5c](https://linux-hardware.org/?probe=603d370b5c) | Jul 09, 2023 |
| MSI           | Z97 GUARD-PRO               | [298da90a40](https://linux-hardware.org/?probe=298da90a40) | Jul 09, 2023 |
| MSI           | X99A RAIDER                 | [30658f7ab7](https://linux-hardware.org/?probe=30658f7ab7) | Jul 09, 2023 |
| MSI           | PRO Z690-A DDR4             | [f8aa10b5cb](https://linux-hardware.org/?probe=f8aa10b5cb) | Jul 08, 2023 |
| MSI           | PRO Z690-A DDR4             | [1027217195](https://linux-hardware.org/?probe=1027217195) | Jul 08, 2023 |
| ECS           | P43T-AD3                    | [bdbd07c719](https://linux-hardware.org/?probe=bdbd07c719) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| HP            | 0AECh D                     | [c3d2867e48](https://linux-hardware.org/?probe=c3d2867e48) | Jul 08, 2023 |
| ASRock        | X670E Pro RS                | [d41838c540](https://linux-hardware.org/?probe=d41838c540) | Jul 08, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [6cac69cac1](https://linux-hardware.org/?probe=6cac69cac1) | Jul 08, 2023 |
| MSI           | X99A RAIDER                 | [f86f946540](https://linux-hardware.org/?probe=f86f946540) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [bdaa09e52c](https://linux-hardware.org/?probe=bdaa09e52c) | Jul 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [09c80a40ac](https://linux-hardware.org/?probe=09c80a40ac) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [f12b531ae3](https://linux-hardware.org/?probe=f12b531ae3) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | [cc54a5a0bf](https://linux-hardware.org/?probe=cc54a5a0bf) | Jul 07, 2023 |
| HP            | 3397                        | [45bc734b0b](https://linux-hardware.org/?probe=45bc734b0b) | Jul 07, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| ASRock        | Z370 Professional Gaming... | [9101223f5e](https://linux-hardware.org/?probe=9101223f5e) | Jul 07, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [2eb6b1bb05](https://linux-hardware.org/?probe=2eb6b1bb05) | Jul 07, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [4068c56cd3](https://linux-hardware.org/?probe=4068c56cd3) | Jul 07, 2023 |
| Dell          | 0KRC95 A02                  | [5d0d505ca1](https://linux-hardware.org/?probe=5d0d505ca1) | Jul 07, 2023 |
| Gigabyte      | X570 AORUS PRO              | [2802b7951e](https://linux-hardware.org/?probe=2802b7951e) | Jul 06, 2023 |
| MSI           | MS-7142                     | [3247a2f71c](https://linux-hardware.org/?probe=3247a2f71c) | Jul 06, 2023 |
| MSI           | H510M PRO-E                 | [598f789eb0](https://linux-hardware.org/?probe=598f789eb0) | Jul 06, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [4122f6e73c](https://linux-hardware.org/?probe=4122f6e73c) | Jul 06, 2023 |
| HP            | 82FE 11                     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| AZW           | U59                         | [0b59408438](https://linux-hardware.org/?probe=0b59408438) | Jul 06, 2023 |
| MSI           | B150 GAMING M3              | [a8018be55a](https://linux-hardware.org/?probe=a8018be55a) | Jul 06, 2023 |
| Dell          | 06D7TR A00                  | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [3af1e33a01](https://linux-hardware.org/?probe=3af1e33a01) | Jul 06, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [ed520a330d](https://linux-hardware.org/?probe=ed520a330d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [dd020d65e5](https://linux-hardware.org/?probe=dd020d65e5) | Jul 05, 2023 |
| HP            | 304Ah                       | [029412ce85](https://linux-hardware.org/?probe=029412ce85) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [06b0f38502](https://linux-hardware.org/?probe=06b0f38502) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-K               | [65cc87f2f0](https://linux-hardware.org/?probe=65cc87f2f0) | Jul 05, 2023 |
| Shenzhen M... | F7BFC                       | [bb708e03aa](https://linux-hardware.org/?probe=bb708e03aa) | Jul 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [50edacf233](https://linux-hardware.org/?probe=50edacf233) | Jul 05, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [d816bd723e](https://linux-hardware.org/?probe=d816bd723e) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| Gigabyte      | P85-D3                      | [6b4a40a1db](https://linux-hardware.org/?probe=6b4a40a1db) | Jul 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| HP            | 212B                        | [5c022be621](https://linux-hardware.org/?probe=5c022be621) | Jul 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | [7acafd9528](https://linux-hardware.org/?probe=7acafd9528) | Jul 04, 2023 |
| Gigabyte      | G41MT-D3                    | [da0ca66579](https://linux-hardware.org/?probe=da0ca66579) | Jul 04, 2023 |
| ASUSTek       | H110M-E/M.2                 | [234c36d2ba](https://linux-hardware.org/?probe=234c36d2ba) | Jul 04, 2023 |
| MSI           | PRO Z690-A DDR4             | [d36574de10](https://linux-hardware.org/?probe=d36574de10) | Jul 03, 2023 |
| Kupi deshe... | X99Z-V102 Date 27052020     | [0cdbbfe5b3](https://linux-hardware.org/?probe=0cdbbfe5b3) | Jul 03, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [293008463e](https://linux-hardware.org/?probe=293008463e) | Jul 03, 2023 |
| MSI           | Z170A KRAIT GAMING          | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| HP            | 861A                        | [0531675f82](https://linux-hardware.org/?probe=0531675f82) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [dc77810d67](https://linux-hardware.org/?probe=dc77810d67) | Jul 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| MSI           | X99A RAIDER                 | [40ca2e97cc](https://linux-hardware.org/?probe=40ca2e97cc) | Jul 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [bdbf0fa0c3](https://linux-hardware.org/?probe=bdbf0fa0c3) | Jul 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [590efa4873](https://linux-hardware.org/?probe=590efa4873) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASRock        | Z87 Extreme6                | [d69ea1a2cb](https://linux-hardware.org/?probe=d69ea1a2cb) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| ASUSTek       | X99-M WS                    | [4f9ad96681](https://linux-hardware.org/?probe=4f9ad96681) | Jul 02, 2023 |
| AZW           | MINI S                      | [fb96f8d7bf](https://linux-hardware.org/?probe=fb96f8d7bf) | Jul 02, 2023 |
| ASUSTek       | PRIME B550M-A               | [740a0dad30](https://linux-hardware.org/?probe=740a0dad30) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS PRO              | [0a9e5c0979](https://linux-hardware.org/?probe=0a9e5c0979) | Jul 02, 2023 |
| MSI           | X99A RAIDER                 | [c2b529a2ee](https://linux-hardware.org/?probe=c2b529a2ee) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| ASRock        | B560M-ITX/ac                | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| HP            | 8061                        | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| HP            | 8054                        | [30c45def21](https://linux-hardware.org/?probe=30c45def21) | Jul 01, 2023 |
| HP            | 8054                        | [edf94b1f66](https://linux-hardware.org/?probe=edf94b1f66) | Jul 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [246d688f1c](https://linux-hardware.org/?probe=246d688f1c) | Jul 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [cfdff3114c](https://linux-hardware.org/?probe=cfdff3114c) | Jul 01, 2023 |
| MSI           | X99A RAIDER                 | [d7efa66a54](https://linux-hardware.org/?probe=d7efa66a54) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| Gigabyte      | H410M S2H V3                | [e539937c27](https://linux-hardware.org/?probe=e539937c27) | Jun 30, 2023 |
| Acer          | Predator PO5-640            | [416b01c954](https://linux-hardware.org/?probe=416b01c954) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [3749bda51b](https://linux-hardware.org/?probe=3749bda51b) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | [6ee8476c0e](https://linux-hardware.org/?probe=6ee8476c0e) | Jun 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | [bb8a8eac46](https://linux-hardware.org/?probe=bb8a8eac46) | Jun 30, 2023 |
| AZW           | MINI S 10                   | [84eec8c276](https://linux-hardware.org/?probe=84eec8c276) | Jun 29, 2023 |
| AZW           | MINI S 10                   | [d1795fbf64](https://linux-hardware.org/?probe=d1795fbf64) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [95fb20193a](https://linux-hardware.org/?probe=95fb20193a) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [5bb4af3f8b](https://linux-hardware.org/?probe=5bb4af3f8b) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| Gigabyte      | B560M DS3H V2               | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASRock        | H510M-HVS                   | [b90f532588](https://linux-hardware.org/?probe=b90f532588) | Jun 28, 2023 |
| HP            | 802F                        | [585f9bf338](https://linux-hardware.org/?probe=585f9bf338) | Jun 27, 2023 |
| HP            | 802F                        | [efceba0028](https://linux-hardware.org/?probe=efceba0028) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| Dell          | 0R6PCT A01                  | [2fd7aa28db](https://linux-hardware.org/?probe=2fd7aa28db) | Jun 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b21d5b2e0a](https://linux-hardware.org/?probe=b21d5b2e0a) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| MSI           | X99A RAIDER                 | [31fc00f1ac](https://linux-hardware.org/?probe=31fc00f1ac) | Jun 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3486e43434](https://linux-hardware.org/?probe=3486e43434) | Jun 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| MSI           | X99A RAIDER                 | [684000f2c5](https://linux-hardware.org/?probe=684000f2c5) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| ASUSTek       | P9X79 PRO                   | [3d1eeda7fa](https://linux-hardware.org/?probe=3d1eeda7fa) | Jun 24, 2023 |
| Dell          | 088DT1 A01                  | [755d1f8c03](https://linux-hardware.org/?probe=755d1f8c03) | Jun 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1c0d2d86f3](https://linux-hardware.org/?probe=1c0d2d86f3) | Jun 24, 2023 |
| ASUSTek       | P8Z77-V LK                  | [bcfc1fe2de](https://linux-hardware.org/?probe=bcfc1fe2de) | Jun 23, 2023 |
| ASRock        | B450 Pro4                   | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| MSI           | PRO B550M-VC WIFI           | [c9f86c15b7](https://linux-hardware.org/?probe=c9f86c15b7) | Jun 22, 2023 |
| Lenovo        | ThinkServer TS140           | [5043d686d8](https://linux-hardware.org/?probe=5043d686d8) | Jun 22, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [b07361bc89](https://linux-hardware.org/?probe=b07361bc89) | Jun 22, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [52bcb712ec](https://linux-hardware.org/?probe=52bcb712ec) | Jun 22, 2023 |
| Lenovo        | SHARKBAY NOK                | [c0f250b2f9](https://linux-hardware.org/?probe=c0f250b2f9) | Jun 22, 2023 |
| Unknown       | Unknown                     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| Dell          | 09KPNV A01                  | [eaa3017d03](https://linux-hardware.org/?probe=eaa3017d03) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [a5e833c54e](https://linux-hardware.org/?probe=a5e833c54e) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | TUF B360-PRO GAMING WIFI    | [52e2d1b77a](https://linux-hardware.org/?probe=52e2d1b77a) | Jun 21, 2023 |
| Pegatron      | IPMIP-H55-INSPUR            | [176a1c3e01](https://linux-hardware.org/?probe=176a1c3e01) | Jun 21, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [a1e0b61e89](https://linux-hardware.org/?probe=a1e0b61e89) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e7bb42d6d4](https://linux-hardware.org/?probe=e7bb42d6d4) | Jun 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | [2fe4bf8ad2](https://linux-hardware.org/?probe=2fe4bf8ad2) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b154e92f35](https://linux-hardware.org/?probe=b154e92f35) | Jun 20, 2023 |
| MSI           | B75MA-P45                   | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ee8a4e18c4](https://linux-hardware.org/?probe=ee8a4e18c4) | Jun 20, 2023 |
| Gigabyte      | MZBAYAB-00                  | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Gigabyte      | B365M D2V                   | [e16cbf315f](https://linux-hardware.org/?probe=e16cbf315f) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| Dell          | 0C2XKD A01                  | [15331b91ed](https://linux-hardware.org/?probe=15331b91ed) | Jun 18, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [924b6e8d54](https://linux-hardware.org/?probe=924b6e8d54) | Jun 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [73a438e6b8](https://linux-hardware.org/?probe=73a438e6b8) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Intel         | DG965RY AAD41691-301        | [3f18a24757](https://linux-hardware.org/?probe=3f18a24757) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [231a3aeb2e](https://linux-hardware.org/?probe=231a3aeb2e) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cd87a6b19f](https://linux-hardware.org/?probe=cd87a6b19f) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [ae4661e26f](https://linux-hardware.org/?probe=ae4661e26f) | Jun 17, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [c555238190](https://linux-hardware.org/?probe=c555238190) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [7e135be518](https://linux-hardware.org/?probe=7e135be518) | Jun 17, 2023 |
| Huanan        | X99-ZD4 V2.0                | [be1f0f151e](https://linux-hardware.org/?probe=be1f0f151e) | Jun 16, 2023 |
| ASUSTek       | ROG ZENITH EXTREME          | [5dc49896e5](https://linux-hardware.org/?probe=5dc49896e5) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| HP            | 212B                        | [134ff203c4](https://linux-hardware.org/?probe=134ff203c4) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a480175f8](https://linux-hardware.org/?probe=8a480175f8) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | [84b103464e](https://linux-hardware.org/?probe=84b103464e) | Jun 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | [3b83e2ea48](https://linux-hardware.org/?probe=3b83e2ea48) | Jun 16, 2023 |
| MSI           | B450 GAMING PLUS            | [8a3d74a5fa](https://linux-hardware.org/?probe=8a3d74a5fa) | Jun 16, 2023 |
| ASRock        | X399 Phantom Gaming 6       | [aad3ead710](https://linux-hardware.org/?probe=aad3ead710) | Jun 16, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [9c3bb21706](https://linux-hardware.org/?probe=9c3bb21706) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| MSI           | Z170A GAMING M5             | [a0d460b4a3](https://linux-hardware.org/?probe=a0d460b4a3) | Jun 16, 2023 |
| Gigabyte      | H97-HD3                     | [24a487274f](https://linux-hardware.org/?probe=24a487274f) | Jun 16, 2023 |
| MSI           | MAG B550M MORTAR            | [9604c6211e](https://linux-hardware.org/?probe=9604c6211e) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Fedora 38 | 871      | 17.69%  |
| Fedora 36 | 689      | 13.99%  |
| Fedora 37 | 610      | 12.39%  |
| Fedora 33 | 567      | 11.51%  |
| Fedora 35 | 535      | 10.86%  |
| Fedora 34 | 518      | 10.52%  |
| Fedora 32 | 518      | 10.52%  |
| Fedora 31 | 343      | 6.96%   |
| Fedora 30 | 132      | 2.68%   |
| Fedora 29 | 75       | 1.52%   |
| Fedora 39 | 31       | 0.63%   |
| Fedora 28 | 14       | 0.28%   |
| Fedora 27 | 9        | 0.18%   |
| Fedora 40 | 5        | 0.1%    |
| Fedora 25 | 2        | 0.04%   |
| Fedora 24 | 2        | 0.04%   |
| Fedora 4  | 1        | 0.02%   |
| Fedora 21 | 1        | 0.02%   |
| Fedora 17 | 1        | 0.02%   |
| Fedora 14 | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Fedora | 4257     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.2.9-300.fc38.x86_64   | 97       | 1.71%   |
| 6.4.15-200.fc38.x86_64  | 74       | 1.3%    |
| 6.2.15-300.fc38.x86_64  | 72       | 1.27%   |
| 6.3.8-200.fc38.x86_64   | 71       | 1.25%   |
| 6.5.5-200.fc38.x86_64   | 58       | 1.02%   |
| 5.9.16-200.fc33.x86_64  | 58       | 1.02%   |
| 5.16.18-200.fc35.x86_64 | 57       | 1%      |
| 5.17.5-300.fc36.x86_64  | 52       | 0.92%   |
| 6.2.14-300.fc38.x86_64  | 48       | 0.85%   |
| 6.0.15-300.fc37.x86_64  | 45       | 0.79%   |
| 6.0.12-300.fc37.x86_64  | 44       | 0.78%   |
| 5.18.13-200.fc36.x86_64 | 42       | 0.74%   |
| 6.5.6-200.fc38.x86_64   | 40       | 0.7%    |
| 6.3.12-200.fc38.x86_64  | 40       | 0.7%    |
| 5.19.16-200.fc36.x86_64 | 40       | 0.7%    |
| 5.13.12-200.fc34.x86_64 | 39       | 0.69%   |
| 6.0.7-301.fc37.x86_64   | 38       | 0.67%   |
| 6.4.11-200.fc38.x86_64  | 37       | 0.65%   |
| 5.14.10-300.fc35.x86_64 | 37       | 0.65%   |
| 6.5.7-200.fc38.x86_64   | 36       | 0.63%   |
| 6.0.5-200.fc36.x86_64   | 35       | 0.62%   |
| 5.11.12-300.fc34.x86_64 | 35       | 0.62%   |
| 6.2.11-300.fc38.x86_64  | 33       | 0.58%   |
| 6.1.18-200.fc37.x86_64  | 33       | 0.58%   |
| 5.8.4-200.fc32.x86_64   | 33       | 0.58%   |
| 5.8.15-301.fc33.x86_64  | 33       | 0.58%   |
| 6.3.11-200.fc38.x86_64  | 32       | 0.56%   |
| 5.18.16-200.fc36.x86_64 | 32       | 0.56%   |
| 6.0.11-300.fc37.x86_64  | 31       | 0.55%   |
| 5.19.9-200.fc36.x86_64  | 31       | 0.55%   |
| 5.18.11-200.fc36.x86_64 | 31       | 0.55%   |
| 6.5.8-200.fc38.x86_64   | 30       | 0.53%   |
| 5.6.19-300.fc32.x86_64  | 30       | 0.53%   |
| 5.18.5-200.fc36.x86_64  | 30       | 0.53%   |
| 5.12.13-300.fc34.x86_64 | 30       | 0.53%   |
| 6.4.6-200.fc38.x86_64   | 29       | 0.51%   |
| 5.8.18-300.fc33.x86_64  | 29       | 0.51%   |
| 5.15.6-200.fc35.x86_64  | 29       | 0.51%   |
| 5.8.16-300.fc33.x86_64  | 28       | 0.49%   |
| 6.0.9-300.fc37.x86_64   | 27       | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.9   | 110      | 1.94%   |
| 6.2.15  | 89       | 1.57%   |
| 6.4.15  | 76       | 1.34%   |
| 6.3.8   | 76       | 1.34%   |
| 5.17.5  | 68       | 1.2%    |
| 6.5.5   | 67       | 1.18%   |
| 5.9.16  | 67       | 1.18%   |
| 5.16.18 | 65       | 1.15%   |
| 6.2.14  | 59       | 1.04%   |
| 5.19.16 | 59       | 1.04%   |
| 6.0.12  | 53       | 0.93%   |
| 5.8.15  | 53       | 0.93%   |
| 6.0.7   | 51       | 0.9%    |
| 6.0.15  | 51       | 0.9%    |
| 5.8.18  | 47       | 0.83%   |
| 6.5.6   | 46       | 0.81%   |
| 5.18.13 | 43       | 0.76%   |
| 6.3.12  | 42       | 0.74%   |
| 6.0.8   | 40       | 0.71%   |
| 5.8.16  | 40       | 0.71%   |
| 5.13.12 | 40       | 0.71%   |
| 5.19.9  | 39       | 0.69%   |
| 5.14.10 | 39       | 0.69%   |
| 6.5.7   | 38       | 0.67%   |
| 6.4.11  | 38       | 0.67%   |
| 6.2.11  | 38       | 0.67%   |
| 6.0.5   | 38       | 0.67%   |
| 6.0.9   | 37       | 0.65%   |
| 5.11.12 | 37       | 0.65%   |
| 5.11.11 | 37       | 0.65%   |
| 6.1.18  | 36       | 0.63%   |
| 5.18.5  | 35       | 0.62%   |
| 6.0.11  | 34       | 0.6%    |
| 5.14.18 | 34       | 0.6%    |
| 5.8.4   | 33       | 0.58%   |
| 5.18.16 | 33       | 0.58%   |
| 6.5.8   | 32       | 0.56%   |
| 6.3.11  | 32       | 0.56%   |
| 5.18.11 | 32       | 0.56%   |
| 5.12.13 | 32       | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 405      | 7.52%   |
| 6.0     | 359      | 6.67%   |
| 5.8     | 307      | 5.7%    |
| 6.4     | 293      | 5.44%   |
| 5.11    | 257      | 4.77%   |
| 5.19    | 256      | 4.76%   |
| 5.18    | 252      | 4.68%   |
| 5.17    | 250      | 4.64%   |
| 6.1     | 243      | 4.51%   |
| 6.3     | 227      | 4.22%   |
| 5.16    | 224      | 4.16%   |
| 5.9     | 209      | 3.88%   |
| 5.10    | 206      | 3.83%   |
| 5.14    | 205      | 3.81%   |
| 5.6     | 195      | 3.62%   |
| 6.5     | 194      | 3.6%    |
| 5.13    | 191      | 3.55%   |
| 5.15    | 180      | 3.34%   |
| 5.12    | 176      | 3.27%   |
| 5.7     | 171      | 3.18%   |
| 5.4     | 135      | 2.51%   |
| 5.5     | 121      | 2.25%   |
| 5.3     | 116      | 2.15%   |
| 5.2     | 55       | 1.02%   |
| 5.0     | 48       | 0.89%   |
| 5.1     | 25       | 0.46%   |
| 4.19    | 22       | 0.41%   |
| 4.18    | 19       | 0.35%   |
| 4.20    | 18       | 0.33%   |
| 4.16    | 5        | 0.09%   |
| 6.6     | 4        | 0.07%   |
| 4.15    | 3        | 0.06%   |
| 4.17    | 2        | 0.04%   |
| 4.13    | 2        | 0.04%   |
| 4.11    | 2        | 0.04%   |
| 4.14    | 1        | 0.02%   |
| 4.1     | 1        | 0.02%   |
| 3.9     | 1        | 0.02%   |
| 3.17    | 1        | 0.02%   |
| 2.6.35  | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 4253     | 99.88%  |
| i686    | 3        | 0.07%   |
| ppc64le | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 2958     | 67.53%  |
| KDE5                         | 600      | 13.7%   |
| Unknown                      | 278      | 6.35%   |
| KDE                          | 116      | 2.65%   |
| XFCE                         | 102      | 2.33%   |
| X-Cinnamon                   | 80       | 1.83%   |
| Cinnamon                     | 66       | 1.51%   |
| MATE                         | 62       | 1.42%   |
| GNOME Classic                | 35       | 0.8%    |
| LXQt                         | 12       | 0.27%   |
| Deepin                       | 11       | 0.25%   |
| LXDE                         | 10       | 0.23%   |
| i3                           | 9        | 0.21%   |
| sway                         | 7        | 0.16%   |
| KDE4                         | 6        | 0.14%   |
| Budgie                       | 4        | 0.09%   |
| Xpra                         | 3        | 0.07%   |
| openbox                      | 3        | 0.07%   |
| Hyprland                     | 3        | 0.07%   |
| awesome                      | 3        | 0.07%   |
| qtile                        | 2        | 0.05%   |
| DWM                          | 2        | 0.05%   |
| bspwm                        | 2        | 0.05%   |
| Pantheon                     | 1        | 0.02%   |
| NsCDE                        | 1        | 0.02%   |
| GNUstep                      | 1        | 0.02%   |
| GNOME Flashback              | 1        | 0.02%   |
| e16-session                  | 1        | 0.02%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 2431     | 54.46%  |
| X11     | 1735     | 38.87%  |
| Tty     | 151      | 3.38%   |
| Unknown | 142      | 3.18%   |
| Web     | 5        | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2509     | 57.23%  |
| GDM     | 1230     | 28.06%  |
| SDDM    | 351      | 8.01%   |
| LightDM | 204      | 4.65%   |
| TDM     | 73       | 1.67%   |
| XDM     | 7        | 0.16%   |
| KDM     | 7        | 0.16%   |
| LXDM    | 2        | 0.05%   |
| SLiM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2026     | 46.79%  |
| en_GB   | 297      | 6.86%   |
| Unknown | 251      | 5.8%    |
| ru_RU   | 215      | 4.97%   |
| pt_BR   | 210      | 4.85%   |
| de_DE   | 197      | 4.55%   |
| fr_FR   | 134      | 3.09%   |
| en_CA   | 132      | 3.05%   |
| en_AU   | 129      | 2.98%   |
| it_IT   | 90       | 2.08%   |
| es_ES   | 72       | 1.66%   |
| pl_PL   | 64       | 1.48%   |
| es_MX   | 29       | 0.67%   |
| en_IN   | 29       | 0.67%   |
| cs_CZ   | 27       | 0.62%   |
| es_AR   | 24       | 0.55%   |
| en_NZ   | 23       | 0.53%   |
| es_CO   | 17       | 0.39%   |
| nl_NL   | 16       | 0.37%   |
| nl_BE   | 16       | 0.37%   |
| tr_TR   | 15       | 0.35%   |
| ja_JP   | 15       | 0.35%   |
| fi_FI   | 15       | 0.35%   |
| en_IE   | 15       | 0.35%   |
| de_AT   | 15       | 0.35%   |
| sv_SE   | 12       | 0.28%   |
| zh_CN   | 11       | 0.25%   |
| hu_HU   | 11       | 0.25%   |
| es_CL   | 11       | 0.25%   |
| en_DK   | 11       | 0.25%   |
| C       | 11       | 0.25%   |
| uk_UA   | 10       | 0.23%   |
| pt_PT   | 10       | 0.23%   |
| ru_UA   | 8        | 0.18%   |
| ko_KR   | 8        | 0.18%   |
| fr_CH   | 8        | 0.18%   |
| fr_BE   | 8        | 0.18%   |
| zh_TW   | 6        | 0.14%   |
| sk_SK   | 6        | 0.14%   |
| fr_CA   | 6        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 2807     | 64.9%   |
| BIOS | 1518     | 35.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Btrfs               | 2509     | 57.48%  |
| Ext4                | 1506     | 34.5%   |
| Xfs                 | 197      | 4.51%   |
| Unknown             | 132      | 3.02%   |
| Overlay             | 8        | 0.18%   |
| Zfs                 | 5        | 0.11%   |
| Ext3                | 5        | 0.11%   |
| F2fs                | 2        | 0.05%   |
| Fuse.fuse-overlayfs | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2444     | 55.72%  |
| GPT     | 1554     | 35.43%  |
| MBR     | 388      | 8.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3713     | 85.14%  |
| Yes       | 648      | 14.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3441     | 79.45%  |
| Yes       | 890      | 20.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1214     | 28.52%  |
| Gigabyte Technology                  | 823      | 19.33%  |
| MSI                                  | 660      | 15.5%   |
| ASRock                               | 438      | 10.29%  |
| Dell                                 | 298      | 7%      |
| Hewlett-Packard                      | 240      | 5.64%   |
| Lenovo                               | 125      | 2.94%   |
| Intel                                | 69       | 1.62%   |
| Unknown                              | 51       | 1.2%    |
| Acer                                 | 43       | 1.01%   |
| Pegatron                             | 26       | 0.61%   |
| Huanan                               | 19       | 0.45%   |
| Biostar                              | 18       | 0.42%   |
| Fujitsu                              | 17       | 0.4%    |
| ECS                                  | 17       | 0.4%    |
| BESSTAR Tech                         | 15       | 0.35%   |
| Supermicro                           | 13       | 0.31%   |
| Foxconn                              | 12       | 0.28%   |
| AZW                                  | 10       | 0.23%   |
| Apple                                | 9        | 0.21%   |
| Alienware                            | 9        | 0.21%   |
| Shuttle                              | 8        | 0.19%   |
| Positivo                             | 8        | 0.19%   |
| Itautec                              | 8        | 0.19%   |
| Medion                               | 7        | 0.16%   |
| Packard Bell                         | 6        | 0.14%   |
| Shenzhen Meigao Electronic Equipment | 5        | 0.12%   |
| PCWare                               | 5        | 0.12%   |
| MACHINIST                            | 5        | 0.12%   |
| System76                             | 4        | 0.09%   |
| EVGA                                 | 4        | 0.09%   |
| AMI                                  | 4        | 0.09%   |
| ABIT                                 | 4        | 0.09%   |
| ZOTAC                                | 3        | 0.07%   |
| NZXT                                 | 3        | 0.07%   |
| eMachines                            | 3        | 0.07%   |
| XFX                                  | 2        | 0.05%   |
| Techvision                           | 2        | 0.05%   |
| OEM                                  | 2        | 0.05%   |
| LattePanda                           | 2        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 120      | 2.82%   |
| Unknown                        | 54       | 1.27%   |
| MSI MS-7C37                    | 46       | 1.08%   |
| ASUS TUF Gaming X570-PLUS      | 33       | 0.78%   |
| Dell OptiPlex 7010             | 29       | 0.68%   |
| MSI MS-7A38                    | 26       | 0.61%   |
| Gigabyte B450M DS3H            | 26       | 0.61%   |
| MSI MS-7C02                    | 25       | 0.59%   |
| MSI MS-7C56                    | 22       | 0.52%   |
| MSI MS-7C91                    | 19       | 0.45%   |
| MSI MS-7B86                    | 19       | 0.45%   |
| Dell OptiPlex 9020             | 19       | 0.45%   |
| MSI MS-7B89                    | 18       | 0.42%   |
| MSI MS-7B79                    | 18       | 0.42%   |
| ASUS ROG STRIX X570-F GAMING   | 17       | 0.4%    |
| ASUS ROG STRIX B550-F GAMING   | 17       | 0.4%    |
| ASRock B450M Pro4              | 17       | 0.4%    |
| Gigabyte B450 AORUS ELITE      | 16       | 0.38%   |
| Gigabyte 970A-DS3P             | 16       | 0.38%   |
| ASUS ROG STRIX B550-I GAMING   | 15       | 0.35%   |
| ASUS PRIME X370-PRO            | 15       | 0.35%   |
| MSI MS-7C95                    | 14       | 0.33%   |
| MSI MS-7C52                    | 14       | 0.33%   |
| Gigabyte X570 I AORUS PRO WIFI | 14       | 0.33%   |
| ASUS TUF Gaming B550M-PLUS     | 14       | 0.33%   |
| ASUS ROG STRIX B450-F GAMING   | 14       | 0.33%   |
| ASUS PRIME X470-PRO            | 14       | 0.33%   |
| MSI MS-7C84                    | 13       | 0.31%   |
| Gigabyte A320M-S2H             | 13       | 0.31%   |
| ASUS PRIME A320M-K             | 13       | 0.31%   |
| MSI MS-7A34                    | 12       | 0.28%   |
| Gigabyte X570 AORUS ELITE      | 12       | 0.28%   |
| Gigabyte B550M DS3H            | 12       | 0.28%   |
| Dell OptiPlex 3020             | 12       | 0.28%   |
| ASUS TUF Gaming B550-PLUS      | 12       | 0.28%   |
| ASUS ROG STRIX X570-E GAMING   | 12       | 0.28%   |
| ASRock B450M Steel Legend      | 12       | 0.28%   |
| Gigabyte B550I AORUS PRO AX    | 11       | 0.26%   |
| Gigabyte B450 AORUS M          | 11       | 0.26%   |
| Gigabyte AB350-Gaming 3        | 11       | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS ROG            | 249      | 5.85%   |
| ASUS PRIME          | 249      | 5.85%   |
| Dell OptiPlex       | 166      | 3.9%    |
| ASUS TUF            | 151      | 3.55%   |
| ASUS All            | 120      | 2.82%   |
| Gigabyte X570       | 71       | 1.67%   |
| Lenovo ThinkCentre  | 68       | 1.6%    |
| HP Compaq           | 59       | 1.39%   |
| Unknown             | 54       | 1.27%   |
| Dell Precision      | 52       | 1.22%   |
| Gigabyte B450       | 50       | 1.17%   |
| MSI MS-7C37         | 46       | 1.08%   |
| Gigabyte B450M      | 45       | 1.06%   |
| HP EliteDesk        | 42       | 0.99%   |
| ASRock B450M        | 35       | 0.82%   |
| Gigabyte B550       | 32       | 0.75%   |
| Dell Inspiron       | 31       | 0.73%   |
| ASRock X570         | 29       | 0.68%   |
| Dell XPS            | 28       | 0.66%   |
| Acer Aspire         | 28       | 0.66%   |
| MSI MS-7A38         | 26       | 0.61%   |
| HP ProDesk          | 26       | 0.61%   |
| MSI MS-7C02         | 25       | 0.59%   |
| Gigabyte B550M      | 25       | 0.59%   |
| ASRock B450         | 23       | 0.54%   |
| MSI MS-7C56         | 22       | 0.52%   |
| MSI MS-7C91         | 19       | 0.45%   |
| MSI MS-7B86         | 19       | 0.45%   |
| MSI MS-7B89         | 18       | 0.42%   |
| MSI MS-7B79         | 18       | 0.42%   |
| ASUS P8Z77-V        | 18       | 0.42%   |
| Lenovo ThinkStation | 17       | 0.4%    |
| Gigabyte 970A-DS3P  | 17       | 0.4%    |
| Gigabyte Z390       | 16       | 0.38%   |
| ASUS SABERTOOTH     | 16       | 0.38%   |
| ASUS Maximus        | 16       | 0.38%   |
| ASUS M5A78L-M       | 16       | 0.38%   |
| Gigabyte A320M-S2H  | 15       | 0.35%   |
| ASUS ProArt         | 15       | 0.35%   |
| MSI MS-7C95         | 14       | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 588      | 13.81%  |
| 2019    | 486      | 11.42%  |
| 2020    | 452      | 10.62%  |
| 2017    | 341      | 8.01%   |
| 2012    | 323      | 7.59%   |
| 2013    | 295      | 6.93%   |
| 2021    | 281      | 6.6%    |
| 2014    | 258      | 6.06%   |
| 2011    | 202      | 4.75%   |
| 2015    | 200      | 4.7%    |
| 2016    | 190      | 4.46%   |
| 2022    | 166      | 3.9%    |
| 2010    | 135      | 3.17%   |
| 2009    | 134      | 3.15%   |
| 2008    | 92       | 2.16%   |
| 2007    | 46       | 1.08%   |
| 2023    | 39       | 0.92%   |
| 2006    | 20       | 0.47%   |
| 2005    | 5        | 0.12%   |
| Unknown | 4        | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4257     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3969     | 92.35%  |
| Enabled  | 329      | 7.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4255     | 99.95%  |
| Yes  | 2        | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1321     | 30.21%  |
| 32.01-64.0      | 1008     | 23.05%  |
| 8.01-16.0       | 719      | 16.44%  |
| 4.01-8.0        | 479      | 10.95%  |
| 64.01-256.0     | 371      | 8.48%   |
| 3.01-4.0        | 256      | 5.85%   |
| 24.01-32.0      | 168      | 3.84%   |
| 1.01-2.0        | 23       | 0.53%   |
| 2.01-3.0        | 20       | 0.46%   |
| Unknown         | 4        | 0.09%   |
| More than 256.0 | 3        | 0.07%   |
| 0.51-1.0        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1411     | 28.63%  |
| 2.01-3.0    | 1219     | 24.73%  |
| 3.01-4.0    | 997      | 20.23%  |
| 1.01-2.0    | 620      | 12.58%  |
| 8.01-16.0   | 460      | 9.33%   |
| 16.01-24.0  | 84       | 1.7%    |
| 0.51-1.0    | 66       | 1.34%   |
| 24.01-32.0  | 32       | 0.65%   |
| 32.01-64.0  | 18       | 0.37%   |
| 0.01-0.5    | 13       | 0.26%   |
| Unknown     | 6        | 0.12%   |
| 64.01-256.0 | 3        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 1406     | 31.08%  |
| 1      | 1247     | 27.56%  |
| 3      | 906      | 20.03%  |
| 4      | 472      | 10.43%  |
| 5      | 238      | 5.26%   |
| 6      | 119      | 2.63%   |
| 7      | 59       | 1.3%    |
| 8      | 28       | 0.62%   |
| 9      | 13       | 0.29%   |
| 0      | 12       | 0.27%   |
| 10     | 7        | 0.15%   |
| 11     | 5        | 0.11%   |
| 12     | 3        | 0.07%   |
| 15     | 2        | 0.04%   |
| 14     | 2        | 0.04%   |
| 410    | 1        | 0.02%   |
| 27     | 1        | 0.02%   |
| 24     | 1        | 0.02%   |
| 18     | 1        | 0.02%   |
| 13     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2838     | 65.79%  |
| Yes       | 1476     | 34.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4227     | 99.27%  |
| No        | 31       | 0.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2205     | 50.98%  |
| Yes       | 2120     | 49.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2497     | 57.55%  |
| Yes       | 1842     | 42.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 1003     | 23.42%  |
| Germany     | 328      | 7.66%   |
| Brazil      | 316      | 7.38%   |
| Russia      | 273      | 6.37%   |
| Canada      | 181      | 4.23%   |
| UK          | 163      | 3.81%   |
| France      | 158      | 3.69%   |
| Italy       | 150      | 3.5%    |
| Australia   | 142      | 3.32%   |
| Poland      | 118      | 2.76%   |
| Spain       | 112      | 2.61%   |
| Netherlands | 75       | 1.75%   |
| Sweden      | 69       | 1.61%   |
| India       | 64       | 1.49%   |
| Czechia     | 53       | 1.24%   |
| Mexico      | 52       | 1.21%   |
| Switzerland | 51       | 1.19%   |
| Belgium     | 51       | 1.19%   |
| Austria     | 44       | 1.03%   |
| Argentina   | 44       | 1.03%   |
| Ukraine     | 42       | 0.98%   |
| Norway      | 37       | 0.86%   |
| Finland     | 37       | 0.86%   |
| Turkey      | 35       | 0.82%   |
| Romania     | 34       | 0.79%   |
| Colombia    | 29       | 0.68%   |
| Portugal    | 28       | 0.65%   |
| New Zealand | 27       | 0.63%   |
| Japan       | 26       | 0.61%   |
| Greece      | 26       | 0.61%   |
| Hungary     | 25       | 0.58%   |
| Denmark     | 22       | 0.51%   |
| Indonesia   | 21       | 0.49%   |
| Chile       | 20       | 0.47%   |
| Belarus     | 19       | 0.44%   |
| Thailand    | 17       | 0.4%    |
| Philippines | 16       | 0.37%   |
| Taiwan      | 14       | 0.33%   |
| Israel      | 14       | 0.33%   |
| Ireland     | 14       | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 68       | 1.48%   |
| Sydney         | 54       | 1.18%   |
| Berlin         | 35       | 0.76%   |
| St Petersburg  | 33       | 0.72%   |
| Sao Paulo      | 33       | 0.72%   |
| Warsaw         | 30       | 0.65%   |
| Vienna         | 29       | 0.63%   |
| Melbourne      | 23       | 0.5%    |
| Brisbane       | 22       | 0.48%   |
| Toronto        | 21       | 0.46%   |
| Paris          | 21       | 0.46%   |
| Madrid         | 20       | 0.44%   |
| Rome           | 19       | 0.41%   |
| Hamburg        | 19       | 0.41%   |
| Auckland       | 19       | 0.41%   |
| Seattle        | 18       | 0.39%   |
| Rio de Janeiro | 18       | 0.39%   |
| Athens         | 18       | 0.39%   |
| Zurich         | 17       | 0.37%   |
| Prague         | 17       | 0.37%   |
| Porto Alegre   | 17       | 0.37%   |
| Palmas         | 17       | 0.37%   |
| Milan          | 17       | 0.37%   |
| Munich         | 16       | 0.35%   |
| Los Angeles    | 16       | 0.35%   |
| Buenos Aires   | 16       | 0.35%   |
| Amsterdam      | 16       | 0.35%   |
| Wroclaw        | 15       | 0.33%   |
| Minsk          | 15       | 0.33%   |
| London         | 15       | 0.33%   |
| Helsinki       | 15       | 0.33%   |
| Yekaterinburg  | 14       | 0.31%   |
| Istanbul       | 14       | 0.31%   |
| Budapest       | 14       | 0.31%   |
| Montreal       | 13       | 0.28%   |
| Mexico City    | 13       | 0.28%   |
| Belo Horizonte | 13       | 0.28%   |
| Vancouver      | 12       | 0.26%   |
| Krakow         | 12       | 0.26%   |
| Dallas         | 12       | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1567     | 3127   | 18.06%  |
| WDC                         | 1494     | 2923   | 17.22%  |
| Seagate                     | 1386     | 2509   | 15.97%  |
| Kingston                    | 583      | 864    | 6.72%   |
| SanDisk                     | 456      | 658    | 5.26%   |
| Crucial                     | 453      | 706    | 5.22%   |
| Toshiba                     | 440      | 674    | 5.07%   |
| Hitachi                     | 216      | 360    | 2.49%   |
| Intel                       | 197      | 347    | 2.27%   |
| A-DATA Technology           | 148      | 200    | 1.71%   |
| Phison                      | 109      | 152    | 1.26%   |
| Micron/Crucial Technology   | 86       | 114    | 0.99%   |
| HGST                        | 86       | 162    | 0.99%   |
| Phison Electronics          | 80       | 123    | 0.92%   |
| Unknown                     | 63       | 100    | 0.73%   |
| Silicon Motion              | 63       | 81     | 0.73%   |
| China                       | 63       | 86     | 0.73%   |
| SPCC                        | 62       | 95     | 0.71%   |
| SK hynix                    | 59       | 69     | 0.68%   |
| Corsair                     | 59       | 90     | 0.68%   |
| PNY                         | 50       | 69     | 0.58%   |
| Micron Technology           | 49       | 64     | 0.56%   |
| Patriot                     | 48       | 73     | 0.55%   |
| OCZ                         | 43       | 58     | 0.5%    |
| Intenso                     | 29       | 38     | 0.33%   |
| Realtek Semiconductor       | 28       | 37     | 0.32%   |
| Maxtor                      | 28       | 34     | 0.32%   |
| Transcend                   | 27       | 35     | 0.31%   |
| Team                        | 26       | 38     | 0.3%    |
| Kingston Technology Company | 26       | 34     | 0.3%    |
| XPG                         | 25       | 35     | 0.29%   |
| ADATA Technology            | 25       | 31     | 0.29%   |
| ASMT                        | 24       | 27     | 0.28%   |
| Hewlett-Packard             | 23       | 27     | 0.27%   |
| Gigabyte Technology         | 22       | 39     | 0.25%   |
| Plextor                     | 21       | 29     | 0.24%   |
| Apacer                      | 21       | 35     | 0.24%   |
| MAXIO Technology (Hangzhou) | 20       | 24     | 0.23%   |
| GOODRAM                     | 20       | 33     | 0.23%   |
| KingSpec                    | 19       | 29     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB                          | 137      | 1.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 135      | 1.3%    |
| Kingston SA400S37240G 240GB SSD                    | 118      | 1.13%   |
| Samsung SSD 860 EVO 500GB                          | 114      | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB                     | 111      | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB                     | 109      | 1.05%   |
| Samsung SSD 860 EVO 1TB                            | 98       | 0.94%   |
| Samsung SSD 850 EVO 500GB                          | 96       | 0.92%   |
| Seagate ST500DM002-1BD142 500GB                    | 91       | 0.87%   |
| Samsung NVMe SSD Drive 500GB                       | 91       | 0.87%   |
| Kingston SA400S37480G 480GB SSD                    | 82       | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 79       | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 78       | 0.75%   |
| Toshiba DT01ACA100 1TB                             | 78       | 0.75%   |
| Crucial CT500MX500SSD1 500GB                       | 78       | 0.75%   |
| Kingston SA400S37120G 120GB SSD                    | 76       | 0.73%   |
| Samsung NVMe SSD Drive 1TB                         | 69       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                        | 61       | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB                     | 50       | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB                     | 48       | 0.46%   |
| Samsung SSD 860 EVO 250GB                          | 48       | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                   | 47       | 0.45%   |
| Toshiba HDWD110 1TB                                | 46       | 0.44%   |
| Seagate ST4000DM004-2CV104 4TB                     | 46       | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB                     | 46       | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB                     | 45       | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                         | 42       | 0.4%    |
| SanDisk NVMe SSD Drive 500GB                       | 41       | 0.39%   |
| Crucial CT240BX500SSD1 240GB                       | 41       | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                           | 40       | 0.38%   |
| Toshiba DT01ACA200 2TB                             | 40       | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 39       | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                     | 39       | 0.37%   |
| Seagate ST1000DM003-1SB102 1TB                     | 39       | 0.37%   |
| Samsung SSD 840 EVO 250GB                          | 39       | 0.37%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB              | 38       | 0.37%   |
| Seagate ST3500418AS 500GB                          | 37       | 0.36%   |
| Samsung SSD 860 QVO 1TB                            | 37       | 0.36%   |
| Phison E12 NVMe Controller 1TB                     | 37       | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                       | 36       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1345     | 2424   | 37.5%   |
| WDC                 | 1283     | 2469   | 35.77%  |
| Toshiba             | 380      | 557    | 10.59%  |
| Hitachi             | 216      | 360    | 6.02%   |
| Samsung Electronics | 158      | 252    | 4.4%    |
| HGST                | 86       | 162    | 2.4%    |
| Maxtor              | 27       | 31     | 0.75%   |
| Unknown             | 22       | 29     | 0.61%   |
| Fujitsu             | 9        | 11     | 0.25%   |
| ASMT                | 8        | 10     | 0.22%   |
| Intenso             | 5        | 8      | 0.14%   |
| Hewlett-Packard     | 5        | 6      | 0.14%   |
| Apple               | 5        | 5      | 0.14%   |
| JMicron Technology  | 4        | 10     | 0.11%   |
| USB                 | 3        | 3      | 0.08%   |
| SSK                 | 3        | 3      | 0.08%   |
| MaxDigital          | 3        | 3      | 0.08%   |
| USB3.0              | 2        | 2      | 0.06%   |
| Synology            | 2        | 3      | 0.06%   |
| QNAP                | 2        | 2      | 0.06%   |
| LaCie               | 2        | 4      | 0.06%   |
| H/W                 | 2        | 4      | 0.06%   |
| ASMT109x            | 2        | 2      | 0.06%   |
| USB 3.0             | 1        | 3      | 0.03%   |
| SAGE                | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| Maxone              | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| Magnetic Data       | 1        | 1      | 0.03%   |
| KESU                | 1        | 1      | 0.03%   |
| IET                 | 1        | 1      | 0.03%   |
| External            | 1        | 1      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |
| ASMT106x            | 1        | 2      | 0.03%   |
| ASMedia             | 1        | 1      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 907      | 1637   | 27.2%   |
| Kingston            | 476      | 706    | 14.28%  |
| Crucial             | 416      | 652    | 12.48%  |
| SanDisk             | 251      | 326    | 7.53%   |
| WDC                 | 219      | 339    | 6.57%   |
| A-DATA Technology   | 128      | 172    | 3.84%   |
| Intel               | 98       | 186    | 2.94%   |
| China               | 63       | 86     | 1.89%   |
| SPCC                | 51       | 75     | 1.53%   |
| PNY                 | 50       | 68     | 1.5%    |
| Patriot             | 45       | 69     | 1.35%   |
| OCZ                 | 43       | 58     | 1.29%   |
| Toshiba             | 40       | 61     | 1.2%    |
| Micron Technology   | 33       | 45     | 0.99%   |
| Corsair             | 33       | 51     | 0.99%   |
| Transcend           | 27       | 35     | 0.81%   |
| Team                | 23       | 35     | 0.69%   |
| SK hynix            | 22       | 23     | 0.66%   |
| GOODRAM             | 20       | 33     | 0.6%    |
| KingSpec            | 19       | 29     | 0.57%   |
| Intenso             | 19       | 24     | 0.57%   |
| Apacer              | 19       | 32     | 0.57%   |
| SABRENT             | 18       | 22     | 0.54%   |
| Plextor             | 18       | 25     | 0.54%   |
| Seagate             | 15       | 18     | 0.45%   |
| Gigabyte Technology | 15       | 25     | 0.45%   |
| LITEONIT            | 13       | 14     | 0.39%   |
| LITEON              | 13       | 17     | 0.39%   |
| Hewlett-Packard     | 12       | 13     | 0.36%   |
| ASMT                | 12       | 13     | 0.36%   |
| Mushkin             | 11       | 16     | 0.33%   |
| KingDian            | 11       | 12     | 0.33%   |
| Verbatim            | 9        | 12     | 0.27%   |
| Unknown             | 9        | 9      | 0.27%   |
| Lexar               | 9        | 14     | 0.27%   |
| Netac               | 7        | 7      | 0.21%   |
| Leven               | 7        | 8      | 0.21%   |
| AMD                 | 7        | 10     | 0.21%   |
| Unknown             | 5        | 7      | 0.15%   |
| Smartbuy            | 4        | 4      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2750     | 6376   | 37.74%  |
| SSD     | 2659     | 5575   | 36.49%  |
| NVMe    | 1742     | 3046   | 23.91%  |
| Unknown | 126      | 173    | 1.73%   |
| MMC     | 10       | 13     | 0.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3744     | 11612  | 64.2%   |
| NVMe | 1732     | 3025   | 29.7%   |
| SAS  | 346      | 533    | 5.93%   |
| MMC  | 10       | 13     | 0.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2718     | 5960   | 45.14%  |
| 0.51-1.0   | 1819     | 3230   | 30.21%  |
| 1.01-2.0   | 752      | 1234   | 12.49%  |
| 3.01-4.0   | 319      | 599    | 5.3%    |
| 2.01-3.0   | 204      | 416    | 3.39%   |
| 4.01-10.0  | 177      | 434    | 2.94%   |
| 10.01-20.0 | 32       | 78     | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 858      | 18.69%  |
| 1001-2000      | 840      | 18.3%   |
| More than 3000 | 702      | 15.29%  |
| 251-500        | 688      | 14.99%  |
| 101-250        | 582      | 12.68%  |
| 2001-3000      | 376      | 8.19%   |
| 1-20           | 212      | 4.62%   |
| Unknown        | 178      | 3.88%   |
| 51-100         | 106      | 2.31%   |
| 21-50          | 47       | 1.02%   |
| 0              | 1        | 0.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 882      | 18.33%  |
| 101-250        | 652      | 13.55%  |
| 21-50          | 635      | 13.19%  |
| 251-500        | 577      | 11.99%  |
| 501-1000       | 572      | 11.88%  |
| 51-100         | 515      | 10.7%   |
| 1001-2000      | 418      | 8.68%   |
| More than 3000 | 215      | 4.47%   |
| Unknown        | 178      | 3.7%    |
| 2001-3000      | 167      | 3.47%   |
| 0              | 2        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 20       | 45     | 3.39%   |
| Seagate ST31000528AS 1TB              | 8        | 10     | 1.36%   |
| Seagate ST31000524AS 1TB              | 8        | 8      | 1.36%   |
| WDC WD10EZEX-00BN5A0 1TB              | 7        | 7      | 1.19%   |
| Seagate ST3500418AS 500GB             | 7        | 16     | 1.19%   |
| Samsung Electronics SSD 870 EVO 1TB   | 7        | 9      | 1.19%   |
| Intel SSDSC2CT120A3 120GB             | 6        | 35     | 1.02%   |
| Toshiba MQ01ABD050 500GB              | 5        | 6      | 0.85%   |
| Seagate ST31500341AS 1TB              | 5        | 5      | 0.85%   |
| Seagate ST2000DM001-1CH164 2TB        | 5        | 5      | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB        | 5        | 5      | 0.85%   |
| Samsung Electronics HD322HJ 320GB     | 5        | 7      | 0.85%   |
| Crucial CT128MX100SSD1 128GB          | 5        | 7      | 0.85%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 4        | 4      | 0.68%   |
| WDC WD20EZRX-00D8PB0 2TB              | 4        | 6      | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB              | 4        | 5      | 0.68%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4        | 4      | 0.68%   |
| Samsung Electronics HD501LJ 500GB     | 4        | 35     | 0.68%   |
| Crucial CT275MX300SSD1 275GB          | 4        | 5      | 0.68%   |
| Crucial CT240M500SSD1 240GB           | 4        | 4      | 0.68%   |
| WDC WD5000AAKX-603CA0 500GB           | 3        | 3      | 0.51%   |
| WDC WD10EZEX-00WN4A0 1TB              | 3        | 3      | 0.51%   |
| Toshiba MQ01ABD100 1TB                | 3        | 3      | 0.51%   |
| Toshiba DT01ACA100 1TB                | 3        | 3      | 0.51%   |
| Seagate ST500LT012-1DG142 500GB       | 3        | 3      | 0.51%   |
| Seagate ST3000DM008-2DM166 3TB        | 3        | 4      | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB        | 3        | 3      | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB        | 3        | 3      | 0.51%   |
| Seagate ST2000DL003-9VT166 2TB        | 3        | 3      | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB        | 3        | 3      | 0.51%   |
| SanDisk SSD PLUS 480GB                | 3        | 3      | 0.51%   |
| Samsung Electronics SSD 870 EVO 500GB | 3        | 4      | 0.51%   |
| Samsung Electronics SSD 870 EVO 2TB   | 3        | 3      | 0.51%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.51%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.51%   |
| Hitachi HDS721010DLE630 1TB           | 3        | 5      | 0.51%   |
| Hitachi HDS721010CLA332 1TB           | 3        | 3      | 0.51%   |
| Hitachi HDP725050GLA360 500GB         | 3        | 3      | 0.51%   |
| HGST HTS545050A7E680 500GB            | 3        | 3      | 0.51%   |
| WDC WD5000AAKX-753CA1 500GB           | 2        | 2      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 146      | 231    | 26.16%  |
| WDC                         | 139      | 204    | 24.91%  |
| Samsung Electronics         | 54       | 99     | 9.68%   |
| Hitachi                     | 41       | 54     | 7.35%   |
| Toshiba                     | 33       | 38     | 5.91%   |
| Intel                       | 23       | 54     | 4.12%   |
| Crucial                     | 23       | 33     | 4.12%   |
| SanDisk                     | 18       | 18     | 3.23%   |
| Kingston                    | 14       | 16     | 2.51%   |
| A-DATA Technology           | 11       | 11     | 1.97%   |
| Maxtor                      | 8        | 8      | 1.43%   |
| Corsair                     | 6        | 9      | 1.08%   |
| OCZ                         | 4        | 5      | 0.72%   |
| HGST                        | 4        | 6      | 0.72%   |
| SPCC                        | 3        | 4      | 0.54%   |
| SK hynix                    | 3        | 3      | 0.54%   |
| LITEON                      | 3        | 3      | 0.54%   |
| OCZ-VERTEX3                 | 2        | 2      | 0.36%   |
| Micron Technology           | 2        | 2      | 0.36%   |
| Intenso                     | 2        | 2      | 0.36%   |
| Fujitsu                     | 2        | 2      | 0.36%   |
| Verbatim                    | 1        | 1      | 0.18%   |
| Unknown                     | 1        | 1      | 0.18%   |
| Team                        | 1        | 4      | 0.18%   |
| PNY                         | 1        | 1      | 0.18%   |
| ORICO                       | 1        | 1      | 0.18%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.18%   |
| LITEONIT                    | 1        | 1      | 0.18%   |
| KingSpec                    | 1        | 1      | 0.18%   |
| KingDian                    | 1        | 1      | 0.18%   |
| HPE                         | 1        | 1      | 0.18%   |
| Hewlett-Packard             | 1        | 1      | 0.18%   |
| China                       | 1        | 1      | 0.18%   |
| BIWIN                       | 1        | 1      | 0.18%   |
| ASMT                        | 1        | 1      | 0.18%   |
| ASMedia                     | 1        | 1      | 0.18%   |
| Apacer                      | 1        | 1      | 0.18%   |
| AMD                         | 1        | 2      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 146      | 231    | 36.41%  |
| WDC                 | 136      | 200    | 33.92%  |
| Hitachi             | 41       | 54     | 10.22%  |
| Toshiba             | 33       | 38     | 8.23%   |
| Samsung Electronics | 29       | 68     | 7.23%   |
| Maxtor              | 8        | 8      | 2%      |
| HGST                | 4        | 6      | 1%      |
| Fujitsu             | 2        | 2      | 0.5%    |
| Hewlett-Packard     | 1        | 1      | 0.25%   |
| ASMT                | 1        | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 364      | 609    | 70.27%  |
| SSD  | 140      | 202    | 27.03%  |
| NVMe | 14       | 14     | 2.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000BEVT-00ZAT0 500GB       | 1        | 2      | 11.11%  |
| Toshiba HDWD130 3TB               | 1        | 1      | 11.11%  |
| SPCC M.2 PCIe SSD 2TB             | 1        | 1      | 11.11%  |
| Seagate ST3320613AS 320GB         | 1        | 1      | 11.11%  |
| Seagate ST31000528AS 1TB          | 1        | 2      | 11.11%  |
| Samsung Electronics SSD 980 500GB | 1        | 2      | 11.11%  |
| Samsung Electronics SSD 980 1TB   | 1        | 2      | 11.11%  |
| Samsung Electronics HD321HJ 320GB | 1        | 2      | 11.11%  |
| Hitachi HDS721010DLE630 1TB       | 1        | 8      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 6      | 33.33%  |
| Seagate             | 2        | 3      | 22.22%  |
| WDC                 | 1        | 2      | 11.11%  |
| Toshiba             | 1        | 1      | 11.11%  |
| SPCC                | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 8      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2580     | 8419   | 52.38%  |
| Works    | 1839     | 5918   | 37.33%  |
| Malfunc  | 499      | 825    | 10.13%  |
| Failed   | 8        | 21     | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2385     | 35.36%  |
| AMD                              | 1825     | 27.06%  |
| Samsung Electronics              | 755      | 11.19%  |
| ASMedia Technology               | 288      | 4.27%   |
| SanDisk                          | 286      | 4.24%   |
| Phison Electronics               | 216      | 3.2%    |
| Kingston Technology Company      | 150      | 2.22%   |
| Marvell Technology Group         | 132      | 1.96%   |
| Micron/Crucial Technology        | 121      | 1.79%   |
| JMicron Technology               | 92       | 1.36%   |
| Silicon Motion                   | 74       | 1.1%    |
| ADATA Technology                 | 58       | 0.86%   |
| Nvidia                           | 55       | 0.82%   |
| Realtek Semiconductor            | 37       | 0.55%   |
| SK hynix                         | 36       | 0.53%   |
| Toshiba America Info Systems     | 28       | 0.42%   |
| LSI Logic / Symbios Logic        | 25       | 0.37%   |
| Seagate Technology               | 23       | 0.34%   |
| MAXIO Technology (Hangzhou)      | 22       | 0.33%   |
| Broadcom / LSI                   | 22       | 0.33%   |
| Micron Technology                | 18       | 0.27%   |
| VIA Technologies                 | 13       | 0.19%   |
| Silicon Image                    | 13       | 0.19%   |
| KIOXIA                           | 11       | 0.16%   |
| Lite-On Technology               | 9        | 0.13%   |
| Adaptec                          | 8        | 0.12%   |
| Shenzhen Longsys Electronics     | 6        | 0.09%   |
| Netac Technology                 | 6        | 0.09%   |
| Solid State Storage Technology   | 4        | 0.06%   |
| Integrated Technology Express    | 4        | 0.06%   |
| INNOGRIT                         | 3        | 0.04%   |
| Hewlett-Packard                  | 3        | 0.04%   |
| 3ware                            | 3        | 0.04%   |
| Union Memory (Shenzhen)          | 2        | 0.03%   |
| ULi Electronics                  | 2        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.03%   |
| HighPoint Technologies           | 2        | 0.03%   |
| Solidigm                         | 1        | 0.01%   |
| Silicon Integrated Systems [SiS] | 1        | 0.01%   |
| Promise Technology               | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1168     | 14.29%  |
| AMD 400 Series Chipset SATA Controller                                                  | 441      | 5.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 439      | 5.37%   |
| AMD 500 Series Chipset SATA Controller                                                  | 291      | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 274      | 3.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 274      | 3.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 248      | 3.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 230      | 2.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 181      | 2.21%   |
| Intel SATA Controller [RAID mode]                                                       | 173      | 2.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 166      | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 165      | 2.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 155      | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 148      | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 146      | 1.79%   |
| Phison E12 NVMe Controller                                                              | 117      | 1.43%   |
| AMD 300 Series Chipset SATA Controller                                                  | 114      | 1.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 107      | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 105      | 1.28%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 97       | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 89       | 1.09%   |
| AMD FCH SATA Controller D                                                               | 79       | 0.97%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 70       | 0.86%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 68       | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 66       | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 66       | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 65       | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 61       | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 58       | 0.71%   |
| AMD X370 Series Chipset SATA Controller                                                 | 57       | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 52       | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 52       | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 52       | 0.64%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 49       | 0.6%    |
| Intel SSD 660P Series                                                                   | 48       | 0.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 48       | 0.59%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 47       | 0.57%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 46       | 0.56%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 43       | 0.53%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 42       | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3731     | 57.84%  |
| NVMe | 1729     | 26.81%  |
| IDE  | 600      | 9.3%    |
| RAID | 327      | 5.07%   |
| SAS  | 46       | 0.71%   |
| SCSI | 17       | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 2371     | 55.7%   |
| AMD                      | 1885     | 44.28%  |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 141      | 3.29%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 104      | 2.43%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 78       | 1.82%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 77       | 1.8%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 71       | 1.66%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 70       | 1.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 58       | 1.35%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 58       | 1.35%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 58       | 1.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 57       | 1.33%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 57       | 1.33%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 51       | 1.19%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 47       | 1.1%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 43       | 1%      |
| Intel Core i7-6700K CPU @ 4.00GHz           | 42       | 0.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 42       | 0.98%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 41       | 0.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 41       | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 41       | 0.96%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 40       | 0.93%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 39       | 0.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 38       | 0.89%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 37       | 0.86%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 36       | 0.84%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 35       | 0.82%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 34       | 0.79%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 34       | 0.79%   |
| AMD FX-6300 Six-Core Processor              | 34       | 0.79%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 33       | 0.77%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 32       | 0.75%   |
| AMD FX-8350 Eight-Core Processor            | 31       | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 30       | 0.7%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 27       | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 27       | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 26       | 0.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 26       | 0.61%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 26       | 0.61%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 26       | 0.61%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 26       | 0.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 25       | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 722      | 16.9%   |
| Intel Core i7           | 660      | 15.45%  |
| AMD Ryzen 5             | 612      | 14.33%  |
| AMD Ryzen 7             | 440      | 10.3%   |
| AMD Ryzen 9             | 271      | 6.34%   |
| Intel Xeon              | 227      | 5.31%   |
| Intel Core i3           | 223      | 5.22%   |
| Other                   | 176      | 4.12%   |
| AMD FX                  | 146      | 3.42%   |
| Intel Core 2 Duo        | 74       | 1.73%   |
| AMD Ryzen 3             | 66       | 1.54%   |
| Intel Core 2 Quad       | 59       | 1.38%   |
| Intel Core i9           | 57       | 1.33%   |
| Intel Celeron           | 56       | 1.31%   |
| Intel Pentium           | 49       | 1.15%   |
| AMD Ryzen Threadripper  | 49       | 1.15%   |
| AMD Phenom II X4        | 46       | 1.08%   |
| AMD A10                 | 36       | 0.84%   |
| AMD A8                  | 27       | 0.63%   |
| Intel Pentium Dual-Core | 25       | 0.59%   |
| AMD A6                  | 21       | 0.49%   |
| AMD Athlon              | 20       | 0.47%   |
| AMD Athlon II X2        | 19       | 0.44%   |
| AMD Phenom II X6        | 18       | 0.42%   |
| Intel Core 2            | 16       | 0.37%   |
| AMD Ryzen 7 PRO         | 13       | 0.3%    |
| AMD Athlon 64 X2        | 13       | 0.3%    |
| AMD A4                  | 13       | 0.3%    |
| Intel Atom              | 12       | 0.28%   |
| AMD Ryzen 5 PRO         | 12       | 0.28%   |
| AMD Phenom              | 12       | 0.28%   |
| Intel Pentium Gold      | 9        | 0.21%   |
| AMD Athlon X4           | 8        | 0.19%   |
| AMD Phenom II X2        | 7        | 0.16%   |
| AMD Athlon II X4        | 7        | 0.16%   |
| Intel Pentium Dual      | 6        | 0.14%   |
| Intel Genuine           | 4        | 0.09%   |
| AMD Athlon Dual Core    | 4        | 0.09%   |
| Intel Pentium D         | 3        | 0.07%   |
| AMD Opteron             | 3        | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1566     | 36.64%  |
| 6      | 913      | 21.36%  |
| 8      | 626      | 14.65%  |
| 2      | 592      | 13.85%  |
| 12     | 234      | 5.47%   |
| 16     | 154      | 3.6%    |
| 3      | 54       | 1.26%   |
| 10     | 53       | 1.24%   |
| 1      | 35       | 0.82%   |
| 24     | 19       | 0.44%   |
| 32     | 12       | 0.28%   |
| 14     | 11       | 0.26%   |
| 36     | 1        | 0.02%   |
| 28     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 18     | 1        | 0.02%   |
| 5      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4203     | 98.73%  |
| 2      | 54       | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2943     | 68.99%  |
| 1      | 1322     | 30.99%  |
| 4      | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4168     | 97.52%  |
| Unknown        | 106      | 2.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 764      | 17.22%  |
| 0x306c3    | 319      | 7.19%   |
| 0x08701021 | 295      | 6.65%   |
| 0x306a9    | 186      | 4.19%   |
| 0x506e3    | 176      | 3.97%   |
| 0x0800820d | 174      | 3.92%   |
| 0x206a7    | 137      | 3.09%   |
| 0x906ea    | 135      | 3.04%   |
| 0x08701013 | 123      | 2.77%   |
| 0x906e9    | 118      | 2.66%   |
| 0x0a201016 | 92       | 2.07%   |
| 0x1067a    | 88       | 1.98%   |
| 0x06000852 | 78       | 1.76%   |
| 0x0a20120a | 69       | 1.56%   |
| 0x0a201009 | 68       | 1.53%   |
| 0x08108109 | 66       | 1.49%   |
| 0x08001138 | 64       | 1.44%   |
| 0x0a601203 | 61       | 1.37%   |
| 0x906ed    | 57       | 1.28%   |
| 0x0a50000c | 54       | 1.22%   |
| 0x08001137 | 52       | 1.17%   |
| 0x010000c8 | 51       | 1.15%   |
| 0x0a50000d | 50       | 1.13%   |
| 0x90672    | 48       | 1.08%   |
| 0x306f2    | 45       | 1.01%   |
| 0xa0655    | 44       | 0.99%   |
| 0xa0653    | 41       | 0.92%   |
| 0x08101016 | 41       | 0.92%   |
| 0x06001119 | 37       | 0.83%   |
| 0x206d7    | 33       | 0.74%   |
| 0x20655    | 28       | 0.63%   |
| 0xa0671    | 27       | 0.61%   |
| 0x106a5    | 27       | 0.61%   |
| 0x10676    | 27       | 0.61%   |
| 0x6fb      | 26       | 0.59%   |
| 0x106e5    | 26       | 0.59%   |
| 0x906eb    | 25       | 0.56%   |
| 0x06000822 | 25       | 0.56%   |
| 0x06003106 | 24       | 0.54%   |
| 0x906ec    | 23       | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 492      | 11.51%  |
| KabyLake         | 482      | 11.27%  |
| Haswell          | 453      | 10.59%  |
| Zen 3            | 405      | 9.47%   |
| Zen+             | 295      | 6.9%    |
| IvyBridge        | 275      | 6.43%   |
| Skylake          | 249      | 5.82%   |
| SandyBridge      | 219      | 5.12%   |
| Zen              | 214      | 5%      |
| Piledriver       | 161      | 3.77%   |
| Penryn           | 142      | 3.32%   |
| Alderlake Hybrid | 119      | 2.78%   |
| K10              | 115      | 2.69%   |
| CometLake        | 115      | 2.69%   |
| Unknown          | 93       | 2.17%   |
| Westmere         | 67       | 1.57%   |
| Core             | 63       | 1.47%   |
| Nehalem          | 62       | 1.45%   |
| Icelake          | 45       | 1.05%   |
| Steamroller      | 34       | 0.8%    |
| Excavator        | 26       | 0.61%   |
| Bulldozer        | 26       | 0.61%   |
| K8 Hammer        | 22       | 0.51%   |
| Broadwell        | 20       | 0.47%   |
| Silvermont       | 17       | 0.4%    |
| Bonnell          | 10       | 0.23%   |
| K10 Llano        | 8        | 0.19%   |
| Tremont          | 7        | 0.16%   |
| NetBurst         | 7        | 0.16%   |
| Jaguar           | 7        | 0.16%   |
| Goldmont plus    | 7        | 0.16%   |
| Goldmont         | 5        | 0.12%   |
| Bobcat           | 5        | 0.12%   |
| Puma             | 4        | 0.09%   |
| Gracemont        | 3        | 0.07%   |
| TigerLake        | 2        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1836     | 39.49%  |
| AMD                              | 1745     | 37.53%  |
| Intel                            | 1046     | 22.5%   |
| ASPEED Technology                | 10       | 0.22%   |
| Matrox Electronics Systems       | 9        | 0.19%   |
| VIA Technologies                 | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| S3 Graphics                      | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 335      | 6.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 170      | 3.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 137      | 2.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 122      | 2.53%   |
| Intel HD Graphics 530                                                       | 117      | 2.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 114      | 2.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 104      | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 92       | 1.91%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 90       | 1.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 88       | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 82       | 1.7%    |
| Intel HD Graphics 630                                                       | 76       | 1.58%   |
| Nvidia GK208B [GeForce GT 710]                                              | 69       | 1.43%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 68       | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 65       | 1.35%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 63       | 1.31%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 61       | 1.26%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 59       | 1.22%   |
| AMD Raphael                                                                 | 58       | 1.2%    |
| Nvidia GT218 [GeForce 210]                                                  | 55       | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 51       | 1.06%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 50       | 1.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 50       | 1.04%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 49       | 1.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 48       | 0.99%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 46       | 0.95%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 46       | 0.95%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 45       | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 44       | 0.91%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 43       | 0.89%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 42       | 0.87%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 41       | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 39       | 0.81%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 38       | 0.79%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 36       | 0.75%   |
| Nvidia GK208B [GeForce GT 730]                                              | 34       | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 33       | 0.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 33       | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 32       | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 32       | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1645     | 37.99%  |
| 1 x AMD                  | 1570     | 36.26%  |
| 1 x Intel                | 778      | 17.97%  |
| Intel + Nvidia           | 104      | 2.4%    |
| 2 x AMD                  | 81       | 1.87%   |
| AMD + Nvidia             | 55       | 1.27%   |
| Intel + AMD              | 37       | 0.85%   |
| 2 x Nvidia               | 25       | 0.58%   |
| 1 x ASPEED               | 6        | 0.14%   |
| 2 x Intel                | 5        | 0.12%   |
| 1 x Matrox               | 5        | 0.12%   |
| Nvidia + Matrox          | 3        | 0.07%   |
| Nvidia + ASPEED          | 2        | 0.05%   |
| Intel + 2 x AMD          | 2        | 0.05%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.05%   |
| Other                    | 1        | 0.02%   |
| 3 x AMD                  | 1        | 0.02%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.02%   |
| 1 x VIA                  | 1        | 0.02%   |
| 1 x SiS                  | 1        | 0.02%   |
| 1 x S3 Graphics          | 1        | 0.02%   |
| Intel + 2 x Nvidia       | 1        | 0.02%   |
| AMD + 2 x Nvidia         | 1        | 0.02%   |
| AMD + Matrox             | 1        | 0.02%   |
| AMD + ASPEED             | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3210     | 73.96%  |
| Proprietary | 1004     | 23.13%  |
| Unknown     | 126      | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1471     | 33.12%  |
| 7.01-8.0   | 703      | 15.83%  |
| 1.01-2.0   | 560      | 12.61%  |
| 3.01-4.0   | 474      | 10.67%  |
| 0.51-1.0   | 404      | 9.1%    |
| 0.01-0.5   | 303      | 6.82%   |
| 8.01-16.0  | 246      | 5.54%   |
| 5.01-6.0   | 188      | 4.23%   |
| 2.01-3.0   | 61       | 1.37%   |
| 16.01-24.0 | 31       | 0.7%    |
| 4.01-5.0   | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 762      | 15.22%  |
| Dell                 | 666      | 13.3%   |
| Goldstar             | 646      | 12.9%   |
| Acer                 | 346      | 6.91%   |
| Hewlett-Packard      | 311      | 6.21%   |
| AOC                  | 287      | 5.73%   |
| BenQ                 | 259      | 5.17%   |
| Ancor Communications | 238      | 4.75%   |
| Philips              | 204      | 4.07%   |
| ViewSonic            | 125      | 2.5%    |
| Lenovo               | 116      | 2.32%   |
| ASUSTek Computer     | 109      | 2.18%   |
| Iiyama               | 103      | 2.06%   |
| MSI                  | 50       | 1%      |
| Sceptre Tech         | 49       | 0.98%   |
| Sony                 | 47       | 0.94%   |
| Unknown              | 41       | 0.82%   |
| Gigabyte Technology  | 41       | 0.82%   |
| Eizo                 | 41       | 0.82%   |
| HannStar             | 29       | 0.58%   |
| NEC Computers        | 26       | 0.52%   |
| Vizio                | 22       | 0.44%   |
| Mi                   | 19       | 0.38%   |
| LG Electronics       | 16       | 0.32%   |
| Insignia             | 16       | 0.32%   |
| Fujitsu Siemens      | 16       | 0.32%   |
| Panasonic            | 14       | 0.28%   |
| ___                  | 12       | 0.24%   |
| Pixio                | 10       | 0.2%    |
| Gateway              | 10       | 0.2%    |
| Vestel Elektronik    | 9        | 0.18%   |
| RTK                  | 9        | 0.18%   |
| HUAWEI               | 9        | 0.18%   |
| Hitachi              | 9        | 0.18%   |
| Unknown (XXX)        | 8        | 0.16%   |
| Toshiba              | 8        | 0.16%   |
| ONN                  | 7        | 0.14%   |
| Medion               | 7        | 0.14%   |
| Belinea              | 7        | 0.14%   |
| Apple                | 7        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 37       | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 37       | 0.68%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 29       | 0.53%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 28       | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 27       | 0.5%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 22       | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 21       | 0.39%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 20       | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 20       | 0.37%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 19       | 0.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 17       | 0.31%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 17       | 0.31%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 16       | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 16       | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 15       | 0.28%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 15       | 0.28%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                     | 14       | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 13       | 0.24%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 12       | 0.22%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 11       | 0.2%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 11       | 0.2%    |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 11       | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 11       | 0.2%    |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                 | 11       | 0.2%    |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                     | 11       | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 11       | 0.2%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11       | 0.2%    |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                       | 11       | 0.2%    |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 10       | 0.18%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 10       | 0.18%   |
| Acer SB220Q ACR06AB 1920x1080 476x268mm 21.5-inch                     | 10       | 0.18%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 9        | 0.17%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 9        | 0.17%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 9        | 0.17%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch | 9        | 0.17%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 9        | 0.17%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 9        | 0.17%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 9        | 0.17%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 9        | 0.17%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 9        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2153     | 44.8%   |
| 2560x1440 (QHD)    | 609      | 12.67%  |
| 3840x2160 (4K)     | 581      | 12.09%  |
| 1280x1024 (SXGA)   | 190      | 3.95%   |
| 1680x1050 (WSXGA+) | 180      | 3.75%   |
| 3440x1440          | 159      | 3.31%   |
| 1920x1200 (WUXGA)  | 155      | 3.23%   |
| 1366x768 (WXGA)    | 132      | 2.75%   |
| 1440x900 (WXGA+)   | 113      | 2.35%   |
| 2560x1080          | 109      | 2.27%   |
| 1600x900 (HD+)     | 109      | 2.27%   |
| 1360x768           | 57       | 1.19%   |
| 3840x1080          | 44       | 0.92%   |
| Unknown            | 43       | 0.89%   |
| 1600x1200          | 23       | 0.48%   |
| 2288x1287          | 22       | 0.46%   |
| 1920x540           | 18       | 0.37%   |
| 1024x768 (XGA)     | 18       | 0.37%   |
| 2560x1600          | 16       | 0.33%   |
| 2048x1152          | 9        | 0.19%   |
| 1280x720 (HD)      | 9        | 0.19%   |
| 3840x1600          | 6        | 0.12%   |
| 1280x960           | 6        | 0.12%   |
| 2160x1200          | 4        | 0.08%   |
| 5760x1080          | 3        | 0.06%   |
| 1280x768           | 3        | 0.06%   |
| 5760x2160          | 2        | 0.04%   |
| 3840x2560          | 2        | 0.04%   |
| 3840x1200          | 2        | 0.04%   |
| 1920x1440          | 2        | 0.04%   |
| 7680x2160          | 1        | 0.02%   |
| 7680x1440          | 1        | 0.02%   |
| 7120x1080          | 1        | 0.02%   |
| 6784x2160          | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 6400x1080          | 1        | 0.02%   |
| 5760x1200          | 1        | 0.02%   |
| 5120x1440          | 1        | 0.02%   |
| 4864x2160          | 1        | 0.02%   |
| 4480x1200          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 961      | 19.02%  |
| 24      | 853      | 16.88%  |
| 23      | 614      | 12.15%  |
| 21      | 571      | 11.3%   |
| 31      | 276      | 5.46%   |
| 34      | 236      | 4.67%   |
| 19      | 217      | 4.3%    |
| 18      | 156      | 3.09%   |
| 22      | 153      | 3.03%   |
| Unknown | 143      | 2.83%   |
| 20      | 135      | 2.67%   |
| 17      | 72       | 1.43%   |
| 32      | 66       | 1.31%   |
| 72      | 62       | 1.23%   |
| 84      | 61       | 1.21%   |
| 25      | 51       | 1.01%   |
| 40      | 45       | 0.89%   |
| 15      | 43       | 0.85%   |
| 54      | 35       | 0.69%   |
| 48      | 35       | 0.69%   |
| 26      | 26       | 0.51%   |
| 42      | 22       | 0.44%   |
| 28      | 22       | 0.44%   |
| 142     | 20       | 0.4%    |
| 29      | 16       | 0.32%   |
| 49      | 14       | 0.28%   |
| 16      | 13       | 0.26%   |
| 52      | 12       | 0.24%   |
| 35      | 11       | 0.22%   |
| 65      | 10       | 0.2%    |
| 46      | 10       | 0.2%    |
| 36      | 10       | 0.2%    |
| 13      | 10       | 0.2%    |
| 37      | 9        | 0.18%   |
| 69      | 7        | 0.14%   |
| 39      | 7        | 0.14%   |
| 43      | 6        | 0.12%   |
| 30      | 6        | 0.12%   |
| 33      | 5        | 0.1%    |
| 12      | 4        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2176     | 45.46%  |
| 401-500        | 1056     | 22.06%  |
| 601-700        | 422      | 8.82%   |
| 701-800        | 317      | 6.62%   |
| 351-400        | 160      | 3.34%   |
| Unknown        | 143      | 2.99%   |
| 1501-2000      | 132      | 2.76%   |
| 1001-1500      | 126      | 2.63%   |
| 301-350        | 113      | 2.36%   |
| 801-900        | 73       | 1.52%   |
| 901-1000       | 34       | 0.71%   |
| More than 2000 | 22       | 0.46%   |
| 201-300        | 13       | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3204     | 72.31%  |
| 16/10   | 525      | 11.85%  |
| 21/9    | 260      | 5.87%   |
| 5/4     | 185      | 4.18%   |
| Unknown | 94       | 2.12%   |
| 4/3     | 63       | 1.42%   |
| 32/9    | 39       | 0.88%   |
| 1.00    | 21       | 0.47%   |
| 6/5     | 18       | 0.41%   |
| 3/2     | 11       | 0.25%   |
| 1.96    | 5        | 0.11%   |
| 0.56    | 2        | 0.05%   |
| 3.20    | 1        | 0.02%   |
| 2.12    | 1        | 0.02%   |
| 0.89    | 1        | 0.02%   |
| 0.80    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1655     | 33.89%  |
| 301-350        | 978      | 20.03%  |
| 351-500        | 608      | 12.45%  |
| 151-200        | 531      | 10.87%  |
| 251-300        | 323      | 6.61%   |
| More than 1000 | 227      | 4.65%   |
| 141-150        | 179      | 3.67%   |
| 501-1000       | 157      | 3.22%   |
| Unknown        | 143      | 2.93%   |
| 101-110        | 39       | 0.8%    |
| 131-140        | 11       | 0.23%   |
| 71-80          | 7        | 0.14%   |
| 121-130        | 7        | 0.14%   |
| 91-100         | 7        | 0.14%   |
| 111-120        | 6        | 0.12%   |
| 81-90          | 5        | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2720     | 59.04%  |
| 101-120       | 1148     | 24.92%  |
| 121-160       | 276      | 5.99%   |
| 1-50          | 190      | 4.12%   |
| Unknown       | 143      | 3.1%    |
| 161-240       | 128      | 2.78%   |
| More than 240 | 2        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3058     | 69.44%  |
| 2     | 1032     | 23.43%  |
| 0     | 151      | 3.43%   |
| 3     | 138      | 3.13%   |
| 4     | 20       | 0.45%   |
| 5     | 5        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2519     | 40.49%  |
| Intel                           | 2135     | 34.31%  |
| Qualcomm Atheros                | 338      | 5.43%   |
| Broadcom                        | 175      | 2.81%   |
| TP-Link                         | 135      | 2.17%   |
| Ralink Technology               | 111      | 1.78%   |
| MediaTek                        | 108      | 1.74%   |
| Microsoft                       | 63       | 1.01%   |
| Ralink                          | 60       | 0.96%   |
| Aquantia                        | 59       | 0.95%   |
| Nvidia                          | 44       | 0.71%   |
| Qualcomm Atheros Communications | 36       | 0.58%   |
| ASUSTek Computer                | 32       | 0.51%   |
| NetGear                         | 26       | 0.42%   |
| Samsung Electronics             | 25       | 0.4%    |
| D-Link                          | 25       | 0.4%    |
| Xiaomi                          | 24       | 0.39%   |
| Marvell Technology Group        | 24       | 0.39%   |
| Google                          | 16       | 0.26%   |
| Edimax Technology               | 16       | 0.26%   |
| ASIX Electronics                | 14       | 0.23%   |
| Mellanox Technologies           | 13       | 0.21%   |
| Huawei Technologies             | 12       | 0.19%   |
| Broadcom Limited                | 12       | 0.19%   |
| Motorola PCS                    | 11       | 0.18%   |
| D-Link System                   | 11       | 0.18%   |
| Linksys                         | 10       | 0.16%   |
| DisplayLink                     | 10       | 0.16%   |
| Arduino SA                      | 8        | 0.13%   |
| Qualcomm                        | 7        | 0.11%   |
| ICS Advent                      | 7        | 0.11%   |
| Belkin Components               | 7        | 0.11%   |
| Apple                           | 7        | 0.11%   |
| Wilocity                        | 6        | 0.1%    |
| AVM                             | 6        | 0.1%    |
| OPPO Electronics                | 5        | 0.08%   |
| Microchip Technology            | 5        | 0.08%   |
| InterBiometrics                 | 5        | 0.08%   |
| HMD Global                      | 5        | 0.08%   |
| 3Com                            | 5        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1959     | 27.15%  |
| Intel I211 Gigabit Network Connection                             | 422      | 5.85%   |
| Intel Wi-Fi 6 AX200                                               | 396      | 5.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 308      | 4.27%   |
| Intel Ethernet Connection (2) I219-V                              | 229      | 3.17%   |
| Intel Ethernet Controller I225-V                                  | 203      | 2.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 146      | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 122      | 1.69%   |
| Intel Ethernet Connection (7) I219-V                              | 103      | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 88       | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 87       | 1.21%   |
| Intel Wireless-AC 9260                                            | 76       | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 73       | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 60       | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 59       | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55       | 0.76%   |
| Intel 82574L Gigabit Network Connection                           | 54       | 0.75%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 48       | 0.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47       | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 47       | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 46       | 0.64%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 46       | 0.64%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 45       | 0.62%   |
| Ralink MT7601U Wireless Adapter                                   | 44       | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 44       | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 43       | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 39       | 0.54%   |
| Intel Wireless 7260                                               | 38       | 0.53%   |
| Intel Wireless 8260                                               | 33       | 0.46%   |
| Realtek 802.11ac NIC                                              | 32       | 0.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32       | 0.44%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 31       | 0.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 29       | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29       | 0.4%    |
| Intel Wireless 7265                                               | 29       | 0.4%    |
| Intel I210 Gigabit Network Connection                             | 29       | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 27       | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 27       | 0.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26       | 0.36%   |
| Qualcomm Atheros AR9271 802.11n                                   | 26       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 981      | 42.99%  |
| Realtek Semiconductor                 | 362      | 15.86%  |
| Qualcomm Atheros                      | 184      | 8.06%   |
| TP-Link                               | 133      | 5.83%   |
| Ralink Technology                     | 111      | 4.86%   |
| MediaTek                              | 107      | 4.69%   |
| Broadcom                              | 91       | 3.99%   |
| Microsoft                             | 61       | 2.67%   |
| Ralink                                | 60       | 2.63%   |
| Qualcomm Atheros Communications       | 36       | 1.58%   |
| ASUSTek Computer                      | 30       | 1.31%   |
| NetGear                               | 25       | 1.1%    |
| D-Link                                | 21       | 0.92%   |
| Edimax Technology                     | 16       | 0.7%    |
| Linksys                               | 10       | 0.44%   |
| D-Link System                         | 7        | 0.31%   |
| Belkin Components                     | 7        | 0.31%   |
| Wilocity                              | 6        | 0.26%   |
| AVM                                   | 6        | 0.26%   |
| IMC Networks                          | 4        | 0.18%   |
| Broadcom Limited                      | 4        | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.13%   |
| Xiaomi                                | 2        | 0.09%   |
| Mercucys                              | 2        | 0.09%   |
| BUFFALO                               | 2        | 0.09%   |
| AboCom Systems                        | 2        | 0.09%   |
| ZyDAS                                 | 1        | 0.04%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.04%   |
| Wacom                                 | 1        | 0.04%   |
| Toshiba                               | 1        | 0.04%   |
| Sitecom Europe                        | 1        | 0.04%   |
| Sierra Wireless                       | 1        | 0.04%   |
| Samsung Electronics                   | 1        | 0.04%   |
| PLANEX                                | 1        | 0.04%   |
| Gemtek                                | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 396      | 17.18%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 122      | 5.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 87       | 3.77%   |
| Intel Wireless-AC 9260                                         | 76       | 3.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 48       | 2.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 46       | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 45       | 1.95%   |
| Ralink MT7601U Wireless Adapter                                | 44       | 1.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 44       | 1.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 43       | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 39       | 1.69%   |
| Intel Wireless 7260                                            | 38       | 1.65%   |
| Intel Wireless 8260                                            | 33       | 1.43%   |
| Realtek 802.11ac NIC                                           | 32       | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32       | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 29       | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 29       | 1.26%   |
| Intel Wireless 7265                                            | 29       | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26       | 1.13%   |
| Qualcomm Atheros AR9271 802.11n                                | 26       | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 26       | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 24       | 1.04%   |
| Intel Wireless 8265 / 8275                                     | 24       | 1.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 23       | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 23       | 1%      |
| Ralink RT5370 Wireless Adapter                                 | 23       | 1%      |
| Microsoft Xbox Wireless Adapter for Windows                    | 23       | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 22       | 0.95%   |
| Intel Wireless 3165                                            | 22       | 0.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 20       | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                            | 20       | 0.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 18       | 0.78%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter   | 18       | 0.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 17       | 0.74%   |
| Microsoft Wireless XBox Controller Dongle                      | 17       | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17       | 0.74%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 16       | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 16       | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 15       | 0.65%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 15       | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2368     | 50.92%  |
| Intel                                  | 1693     | 36.41%  |
| Qualcomm Atheros                       | 173      | 3.72%   |
| Broadcom                               | 84       | 1.81%   |
| Aquantia                               | 59       | 1.27%   |
| Nvidia                                 | 44       | 0.95%   |
| Samsung Electronics                    | 24       | 0.52%   |
| Marvell Technology Group               | 24       | 0.52%   |
| Xiaomi                                 | 22       | 0.47%   |
| Google                                 | 16       | 0.34%   |
| ASIX Electronics                       | 14       | 0.3%    |
| Mellanox Technologies                  | 11       | 0.24%   |
| DisplayLink                            | 10       | 0.22%   |
| Motorola PCS                           | 9        | 0.19%   |
| Broadcom Limited                       | 8        | 0.17%   |
| Qualcomm                               | 7        | 0.15%   |
| ICS Advent                             | 7        | 0.15%   |
| Huawei Technologies                    | 7        | 0.15%   |
| Apple                                  | 7        | 0.15%   |
| OPPO Electronics                       | 5        | 0.11%   |
| HMD Global                             | 5        | 0.11%   |
| 3Com                                   | 5        | 0.11%   |
| VIA Technologies                       | 4        | 0.09%   |
| D-Link System                          | 4        | 0.09%   |
| D-Link                                 | 4        | 0.09%   |
| ADMtek                                 | 3        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.04%   |
| TP-Link                                | 2        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.04%   |
| National Semiconductor                 | 2        | 0.04%   |
| Lenovo                                 | 2        | 0.04%   |
| Davicom Semiconductor                  | 2        | 0.04%   |
| ASUSTek Computer                       | 2        | 0.04%   |
| Accton Technology                      | 2        | 0.04%   |
| Xilinx                                 | 1        | 0.02%   |
| vivo                                   | 1        | 0.02%   |
| Tehuti Networks                        | 1        | 0.02%   |
| QNAP System                            | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1959     | 40.4%   |
| Intel I211 Gigabit Network Connection                                         | 422      | 8.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 308      | 6.35%   |
| Intel Ethernet Connection (2) I219-V                                          | 229      | 4.72%   |
| Intel Ethernet Controller I225-V                                              | 203      | 4.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 146      | 3.01%   |
| Intel Ethernet Connection (7) I219-V                                          | 103      | 2.12%   |
| Intel Ethernet Connection I217-LM                                             | 88       | 1.81%   |
| Intel Ethernet Connection (2) I218-V                                          | 73       | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                                         | 60       | 1.24%   |
| Intel 82579V Gigabit Network Connection                                       | 59       | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 55       | 1.13%   |
| Intel 82574L Gigabit Network Connection                                       | 54       | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 47       | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 47       | 0.97%   |
| Intel Ethernet Connection I217-V                                              | 46       | 0.95%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 31       | 0.64%   |
| Intel I210 Gigabit Network Connection                                         | 29       | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 27       | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 27       | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 24       | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 23       | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 22       | 0.45%   |
| Nvidia MCP61 Ethernet                                                         | 20       | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 19       | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 19       | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 19       | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 17       | 0.35%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]           | 17       | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 16       | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 15       | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 14       | 0.29%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 14       | 0.29%   |
| Intel Ethernet Connection (14) I219-V                                         | 13       | 0.27%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 13       | 0.27%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 12       | 0.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 12       | 0.25%   |
| Intel Ethernet Connection (2) I218-LM                                         | 12       | 0.25%   |
| Intel 82578DM Gigabit Network Connection                                      | 12       | 0.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 12       | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4225     | 65.96%  |
| WiFi     | 2119     | 33.08%  |
| Modem    | 52       | 0.81%   |
| Unknown  | 9        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3371     | 74.42%  |
| WiFi     | 1159     | 25.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2416     | 55.9%   |
| 2     | 1557     | 36.02%  |
| 3     | 257      | 5.95%   |
| 4     | 38       | 0.88%   |
| 0     | 29       | 0.67%   |
| 5     | 15       | 0.35%   |
| 6     | 7        | 0.16%   |
| 9     | 2        | 0.05%   |
| 8     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 3476     | 79.43%  |
| Yes     | 897      | 20.5%   |
| Unknown | 3        | 0.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 917      | 47.91%  |
| Cambridge Silicon Radio         | 378      | 19.75%  |
| ASUSTek Computer                | 129      | 6.74%   |
| Realtek Semiconductor           | 127      | 6.64%   |
| Broadcom                        | 87       | 4.55%   |
| MediaTek                        | 70       | 3.66%   |
| Qualcomm Atheros Communications | 45       | 2.35%   |
| TP-Link                         | 33       | 1.72%   |
| IMC Networks                    | 31       | 1.62%   |
| Apple                           | 19       | 0.99%   |
| Foxconn / Hon Hai               | 17       | 0.89%   |
| Belkin Components               | 8        | 0.42%   |
| HTC (High Tech Computer)        | 7        | 0.37%   |
| Edimax Technology               | 7        | 0.37%   |
| Lite-On Technology              | 6        | 0.31%   |
| Integrated System Solution      | 5        | 0.26%   |
| Dynex                           | 4        | 0.21%   |
| Toshiba                         | 3        | 0.16%   |
| Hewlett-Packard                 | 3        | 0.16%   |
| Dell                            | 3        | 0.16%   |
| SINO WEALTH                     | 2        | 0.1%    |
| Realtek                         | 2        | 0.1%    |
| Actions                         | 2        | 0.1%    |
| Unknown                         | 2        | 0.1%    |
| Mobile Action Technology        | 1        | 0.05%   |
| Kensington                      | 1        | 0.05%   |
| Foxconn International           | 1        | 0.05%   |
| D-Link System                   | 1        | 0.05%   |
| D-Link                          | 1        | 0.05%   |
| Creative Technology             | 1        | 0.05%   |
| BUFFALO                         | 1        | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 378      | 19.7%   |
| Intel AX200 Bluetooth                                                | 373      | 19.44%  |
| Intel Bluetooth wireless interface                                   | 146      | 7.61%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 120      | 6.25%   |
| Realtek Bluetooth Radio                                              | 99       | 5.16%   |
| Intel AX210 Bluetooth                                                | 82       | 4.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 72       | 3.75%   |
| MediaTek Wireless_Device                                             | 70       | 3.65%   |
| Intel AX201 Bluetooth                                                | 67       | 3.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 60       | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 42       | 2.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 36       | 1.88%   |
| TP-Link UB500 Adapter                                                | 33       | 1.72%   |
| ASUS Bluetooth Radio                                                 | 22       | 1.15%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 20       | 1.04%   |
| Intel Bluetooth Device                                               | 20       | 1.04%   |
| ASUS ASUS USB-BT500                                                  | 19       | 0.99%   |
| Qualcomm Atheros  Bluetooth Device                                   | 15       | 0.78%   |
| Foxconn / Hon Hai Wireless_Device                                    | 15       | 0.78%   |
| ASUS Bluetooth Adapter                                               | 15       | 0.78%   |
| Apple Bluetooth Host Controller                                      | 13       | 0.68%   |
| ASUS BCM20702A0                                                      | 12       | 0.63%   |
| IMC Networks Wireless_Device                                         | 11       | 0.57%   |
| IMC Networks Bluetooth Radio                                         | 10       | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 9        | 0.47%   |
| ASUS Bluetooth Device                                                | 8        | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 7        | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 7        | 0.36%   |
| IMC Networks Bluetooth Device                                        | 7        | 0.36%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 7        | 0.36%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 7        | 0.36%   |
| Realtek RTL8821A Bluetooth                                           | 6        | 0.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 6        | 0.31%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 6        | 0.31%   |
| Edimax Bluetooth Adapter                                             | 6        | 0.31%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 6        | 0.31%   |
| Broadcom BCM2045 Bluetooth                                           | 5        | 0.26%   |
| Lite-On Bluetooth Device                                             | 4        | 0.21%   |
| Integrated System Solution Bluetooth Device                          | 4        | 0.21%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 4        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 2326     | 29%     |
| Intel                                | 2277     | 28.38%  |
| Nvidia                               | 1767     | 22.03%  |
| C-Media Electronics                  | 273      | 3.4%    |
| Logitech                             | 133      | 1.66%   |
| Creative Labs                        | 86       | 1.07%   |
| JMTek                                | 61       | 0.76%   |
| Kingston Technology                  | 59       | 0.74%   |
| SteelSeries ApS                      | 58       | 0.72%   |
| Focusrite-Novation                   | 54       | 0.67%   |
| Razer USA                            | 51       | 0.64%   |
| ASUSTek Computer                     | 50       | 0.62%   |
| Texas Instruments                    | 49       | 0.61%   |
| Corsair                              | 46       | 0.57%   |
| Creative Technology                  | 42       | 0.52%   |
| Generalplus Technology               | 39       | 0.49%   |
| Plantronics                          | 30       | 0.37%   |
| GN Netcom                            | 30       | 0.37%   |
| Micro Star International             | 28       | 0.35%   |
| Blue Microphones                     | 25       | 0.31%   |
| Realtek Semiconductor                | 23       | 0.29%   |
| Sony                                 | 22       | 0.27%   |
| GYROCOM C&C                          | 20       | 0.25%   |
| Samson Technologies                  | 18       | 0.22%   |
| RODE Microphones                     | 17       | 0.21%   |
| XMOS                                 | 15       | 0.19%   |
| Tenx Technology                      | 13       | 0.16%   |
| Giga-Byte Technology                 | 13       | 0.16%   |
| Dell                                 | 13       | 0.16%   |
| Cambridge Silicon Radio              | 12       | 0.15%   |
| VIA Technologies                     | 11       | 0.14%   |
| Schiit Audio                         | 11       | 0.14%   |
| DSEA A/S                             | 11       | 0.14%   |
| Yamaha                               | 10       | 0.12%   |
| SAVITECH                             | 10       | 0.12%   |
| M-Audio                              | 9        | 0.11%   |
| FiiO Electronics Technology          | 9        | 0.11%   |
| Thesycon Systemsoftware & Consulting | 8        | 0.1%    |
| Lenovo                               | 8        | 0.1%    |
| BEHRINGER International              | 8        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 718      | 7.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 360      | 3.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 346      | 3.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 343      | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 288      | 3.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 261      | 2.73%   |
| Intel 200 Series PCH HD Audio                                              | 256      | 2.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 256      | 2.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 224      | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 223      | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 209      | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 192      | 2.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 185      | 1.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 177      | 1.85%   |
| AMD Navi 10 HDMI Audio                                                     | 166      | 1.73%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 154      | 1.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 151      | 1.58%   |
| Nvidia GP106 High Definition Audio Controller                              | 150      | 1.57%   |
| Nvidia GP104 High Definition Audio Controller                              | 125      | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 120      | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 114      | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 113      | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 104      | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                     | 103      | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 102      | 1.07%   |
| AMD FCH Azalia Controller                                                  | 96       | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 95       | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 83       | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 80       | 0.84%   |
| Nvidia High Definition Audio Controller                                    | 74       | 0.77%   |
| Nvidia TU104 HD Audio Controller                                           | 72       | 0.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 68       | 0.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 66       | 0.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 64       | 0.67%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 63       | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                              | 62       | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                              | 62       | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 61       | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                              | 58       | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 56       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 416      | 18.71%  |
| Corsair             | 379      | 17.04%  |
| G.Skill             | 288      | 12.95%  |
| Unknown             | 214      | 9.62%   |
| Crucial             | 174      | 7.82%   |
| Samsung Electronics | 166      | 7.46%   |
| SK hynix            | 152      | 6.83%   |
| Micron Technology   | 94       | 4.23%   |
| A-DATA Technology   | 57       | 2.56%   |
| Team                | 42       | 1.89%   |
| Patriot             | 37       | 1.66%   |
| Unknown             | 22       | 0.99%   |
| Ramaxel Technology  | 16       | 0.72%   |
| Smart               | 14       | 0.63%   |
| Nanya Technology    | 14       | 0.63%   |
| Elpida              | 10       | 0.45%   |
| GeIL                | 9        | 0.4%    |
| GOODRAM             | 8        | 0.36%   |
| AMD                 | 8        | 0.36%   |
| Silicon Power       | 7        | 0.31%   |
| PNY                 | 7        | 0.31%   |
| Transcend           | 6        | 0.27%   |
| Apacer              | 6        | 0.27%   |
| Qumo                | 4        | 0.18%   |
| Qimonda             | 4        | 0.18%   |
| Avant               | 4        | 0.18%   |
| Unknown (ABCD)      | 3        | 0.13%   |
| Unifosa             | 3        | 0.13%   |
| CSX                 | 3        | 0.13%   |
| Timetec             | 2        | 0.09%   |
| TakeMS              | 2        | 0.09%   |
| Sesame              | 2        | 0.09%   |
| Patriot Memory      | 2        | 0.09%   |
| OCZ                 | 2        | 0.09%   |
| Mushkin             | 2        | 0.09%   |
| MINPO               | 2        | 0.09%   |
| Goldkey             | 2        | 0.09%   |
| Golden Empire       | 2        | 0.09%   |
| Gold Key            | 2        | 0.09%   |
| Atermiter           | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 41       | 1.7%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 26       | 1.08%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 24       | 0.99%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 24       | 0.99%   |
| Unknown                                                | 22       | 0.91%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 18       | 0.75%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 18       | 0.75%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s | 17       | 0.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 16       | 0.66%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 15       | 0.62%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 14       | 0.58%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 14       | 0.58%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 13       | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 12       | 0.5%    |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s     | 11       | 0.46%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 11       | 0.46%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s    | 11       | 0.46%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s | 11       | 0.46%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 11       | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 10       | 0.41%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s  | 10       | 0.41%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s | 10       | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 9        | 0.37%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 9        | 0.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 9        | 0.37%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 9        | 0.37%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 9        | 0.37%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 9        | 0.37%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s  | 9        | 0.37%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 8        | 0.33%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2666MT/s      | 8        | 0.33%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 8        | 0.33%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 8        | 0.33%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s     | 8        | 0.33%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s  | 8        | 0.33%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s | 8        | 0.33%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s | 8        | 0.33%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 8        | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 7        | 0.29%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s     | 7        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1152     | 57.98%  |
| DDR3    | 539      | 27.13%  |
| Unknown | 93       | 4.68%   |
| DDR2    | 70       | 3.52%   |
| DDR5    | 65       | 3.27%   |
| SDRAM   | 48       | 2.42%   |
| DDR     | 11       | 0.55%   |
| LPDDR4  | 3        | 0.15%   |
| LPDDR3  | 3        | 0.15%   |
| DRAM    | 3        | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1850     | 94.44%  |
| SODIMM       | 94       | 4.8%    |
| RIMM         | 10       | 0.51%   |
| FB-DIMM      | 3        | 0.15%   |
| Row Of Chips | 2        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 870      | 40.79%  |
| 16384 | 469      | 21.99%  |
| 4096  | 410      | 19.22%  |
| 2048  | 189      | 8.86%   |
| 32768 | 146      | 6.84%   |
| 1024  | 42       | 1.97%   |
| 512   | 4        | 0.19%   |
| 49152 | 2        | 0.09%   |
| 256   | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 307      | 14.06%  |
| 3200    | 289      | 13.24%  |
| 3600    | 203      | 9.3%    |
| 1333    | 178      | 8.15%   |
| 2400    | 130      | 5.96%   |
| 2133    | 105      | 4.81%   |
| 2667    | 93       | 4.26%   |
| 800     | 62       | 2.84%   |
| 3733    | 55       | 2.52%   |
| 3000    | 55       | 2.52%   |
| 3400    | 53       | 2.43%   |
| 667     | 45       | 2.06%   |
| 1867    | 44       | 2.02%   |
| 2666    | 40       | 1.83%   |
| 3800    | 33       | 1.51%   |
| 1800    | 31       | 1.42%   |
| 1866    | 29       | 1.33%   |
| 3866    | 28       | 1.28%   |
| 3533    | 28       | 1.28%   |
| 2933    | 28       | 1.28%   |
| Unknown | 27       | 1.24%   |
| 4800    | 26       | 1.19%   |
| 2800    | 26       | 1.19%   |
| 3466    | 24       | 1.1%    |
| 3666    | 19       | 0.87%   |
| 1066    | 18       | 0.82%   |
| 3266    | 15       | 0.69%   |
| 1067    | 12       | 0.55%   |
| 5200    | 10       | 0.46%   |
| 3534    | 9        | 0.41%   |
| 3100    | 9        | 0.41%   |
| 6000    | 8        | 0.37%   |
| 2733    | 8        | 0.37%   |
| 1334    | 8        | 0.37%   |
| 6400    | 7        | 0.32%   |
| 5600    | 7        | 0.32%   |
| 4000    | 7        | 0.32%   |
| 3334    | 7        | 0.32%   |
| 3333    | 6        | 0.27%   |
| 533     | 6        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 72       | 38.71%  |
| Brother Industries    | 45       | 24.19%  |
| Canon                 | 19       | 10.22%  |
| Seiko Epson           | 14       | 7.53%   |
| Samsung Electronics   | 13       | 6.99%   |
| Prolific Technology   | 5        | 2.69%   |
| Lexmark International | 4        | 2.15%   |
| Dymo-CoStar           | 4        | 2.15%   |
| Xerox                 | 2        | 1.08%   |
| Kyocera               | 2        | 1.08%   |
| Star Micronics        | 1        | 0.54%   |
| QinHeng Electronics   | 1        | 0.54%   |
| Pantum                | 1        | 0.54%   |
| Graphtec America      | 1        | 0.54%   |
| Dell                  | 1        | 0.54%   |
| Boca Systems          | 1        | 0.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Samsung M2070 Series                         | 5        | 2.67%   |
| Prolific PL2305 Parallel Port                | 5        | 2.67%   |
| HP LaserJet Professional P 1102w             | 4        | 2.14%   |
| HP ENVY 5000 series                          | 4        | 2.14%   |
| Brother HL-L2340D series                     | 4        | 2.14%   |
| HP ENVY 4520 series                          | 3        | 1.6%    |
| HP DeskJet F300 series                       | 3        | 1.6%    |
| HP DeskJet 3700 series                       | 3        | 1.6%    |
| Brother Printer                              | 3        | 1.6%    |
| Brother HL-1110 series                       | 3        | 1.6%    |
| Seiko Epson WF-2860 Series                   | 2        | 1.07%   |
| Seiko Epson Printer                          | 2        | 1.07%   |
| Samsung ML-216x Series Laser Printer         | 2        | 1.07%   |
| HP OfficeJet 6950                            | 2        | 1.07%   |
| HP LaserJet Professional P1102w              | 2        | 1.07%   |
| HP LaserJet P1102                            | 2        | 1.07%   |
| HP LaserJet 1020                             | 2        | 1.07%   |
| HP LaserJet 1010                             | 2        | 1.07%   |
| HP DeskJet 3630 series                       | 2        | 1.07%   |
| HP DeskJet 2700 series                       | 2        | 1.07%   |
| HP DeskJet 2600 series                       | 2        | 1.07%   |
| HP DeskJet 2130 series                       | 2        | 1.07%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 2        | 1.07%   |
| Canon TS3300 series                          | 2        | 1.07%   |
| Canon TR4500 series                          | 2        | 1.07%   |
| Canon LiDE 300                               | 2        | 1.07%   |
| Brother MFC-9330CDW                          | 2        | 1.07%   |
| Brother HL-2230 series                       | 2        | 1.07%   |
| Brother HL-2030 Laser Printer                | 2        | 1.07%   |
| Brother HL-1440 Laser Printer                | 2        | 1.07%   |
| Xerox Phaser 6500N                           | 1        | 0.53%   |
| Xerox Phaser 3010                            | 1        | 0.53%   |
| Star Micronics TUP592 (STR_T-001)            | 1        | 0.53%   |
| Seiko Epson XP-100 Series                    | 1        | 0.53%   |
| Seiko Epson WP-4020 Series                   | 1        | 0.53%   |
| Seiko Epson WF-2510 Series                   | 1        | 0.53%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.53%   |
| Seiko Epson L360 Series                      | 1        | 0.53%   |
| Seiko Epson L3110 Series                     | 1        | 0.53%   |
| Seiko Epson L300 Series                      | 1        | 0.53%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 28       | 58.33%  |
| Seiko Epson     | 14       | 29.17%  |
| Hewlett-Packard | 4        | 8.33%   |
| UMAX            | 1        | 2.08%   |
| Mustek Systems  | 1        | 2.08%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 6        | 12.5%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 5        | 10.42%  |
| Canon CanoScan LiDE 220                                  | 4        | 8.33%   |
| Canon CanoScan LIDE 25                                   | 3        | 6.25%   |
| Canon CanoScan LiDE 110                                  | 3        | 6.25%   |
| Canon CanoScan LiDE 100                                  | 3        | 6.25%   |
| Seiko Epson GT-6600U [Perfection 610]                    | 2        | 4.17%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 4.17%   |
| Canon CanoScan 4400F                                     | 2        | 4.17%   |
| UMAX Astra 2200/2200SU                                   | 1        | 2.08%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1        | 2.08%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1        | 2.08%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]  | 1        | 2.08%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]              | 1        | 2.08%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 2.08%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1        | 2.08%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]            | 1        | 2.08%   |
| Mustek Systems BearPaw 2448 TA Plus                      | 1        | 2.08%   |
| HP ScanJet G4050                                         | 1        | 2.08%   |
| HP ScanJet 5590                                          | 1        | 2.08%   |
| HP ScanJet 3400cse                                       | 1        | 2.08%   |
| HP ScanJet 2400c                                         | 1        | 2.08%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 2.08%   |
| Canon CanoScan LiDE 700F                                 | 1        | 2.08%   |
| Canon CanoScan LiDE 70                                   | 1        | 2.08%   |
| Canon CanoScan LiDE 200                                  | 1        | 2.08%   |
| Canon CanoScan LiDE 120                                  | 1        | 2.08%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 497      | 45.31%  |
| Microsoft                              | 86       | 7.84%   |
| Microdia                               | 67       | 6.11%   |
| Apple                                  | 38       | 3.46%   |
| Samsung Electronics                    | 37       | 3.37%   |
| Sunplus Innovation Technology          | 33       | 3.01%   |
| Realtek Semiconductor                  | 23       | 2.1%    |
| KYE Systems (Mouse Systems)            | 21       | 1.91%   |
| Chicony Electronics                    | 20       | 1.82%   |
| Generalplus Technology                 | 17       | 1.55%   |
| Creative Technology                    | 15       | 1.37%   |
| Cubeternet                             | 14       | 1.28%   |
| ARC International                      | 14       | 1.28%   |
| Z-Star Microelectronics                | 13       | 1.19%   |
| HD 2MP WEBCAM                          | 13       | 1.19%   |
| Razer USA                              | 11       | 1%      |
| Jieli Technology                       | 11       | 1%      |
| AVerMedia Technologies                 | 11       | 1%      |
| Trust                                  | 10       | 0.91%   |
| MacroSilicon                           | 9        | 0.82%   |
| Hewlett-Packard                        | 8        | 0.73%   |
| Lenovo                                 | 7        | 0.64%   |
| GEMBIRD                                | 7        | 0.64%   |
| LG Electronics                         | 5        | 0.46%   |
| Aveo Technology                        | 5        | 0.46%   |
| Arkmicro Technologies                  | 5        | 0.46%   |
| SunplusIT                              | 4        | 0.36%   |
| Google                                 | 4        | 0.36%   |
| Asuscom Network                        | 4        | 0.36%   |
| Alcor Micro                            | 4        | 0.36%   |
| Unknown                                | 4        | 0.36%   |
| YGTek                                  | 3        | 0.27%   |
| Valve Software                         | 3        | 0.27%   |
| Unknown                                | 3        | 0.27%   |
| Tobii Technology AB                    | 3        | 0.27%   |
| Sunplus IT                             | 3        | 0.27%   |
| OmniVision Technologies                | 3        | 0.27%   |
| Huawei Technologies                    | 3        | 0.27%   |
| Genesys Logic                          | 3        | 0.27%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 105      | 9.46%   |
| Logitech Webcam C270                    | 103      | 9.28%   |
| Samsung Galaxy series, misc. (MTP mode) | 36       | 3.24%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 33       | 2.97%   |
| Logitech HD Webcam C525                 | 32       | 2.88%   |
| Microsoft LifeCam HD-3000               | 30       | 2.7%    |
| Logitech C922 Pro Stream Webcam         | 29       | 2.61%   |
| Microdia Webcam Vitade AF               | 25       | 2.25%   |
| Logitech HD Webcam C615                 | 23       | 2.07%   |
| Logitech Webcam C310                    | 21       | 1.89%   |
| Logitech Webcam C170                    | 20       | 1.8%    |
| Microsoft LifeCam Cinema                | 18       | 1.62%   |
| Logitech C920 PRO HD Webcam             | 18       | 1.62%   |
| Logitech BRIO Ultra HD Webcam           | 17       | 1.53%   |
| Sunplus Full HD webcam                  | 16       | 1.44%   |
| Logitech Webcam Pro 9000                | 15       | 1.35%   |
| ARC International Camera                | 14       | 1.26%   |
| Microdia USB 2.0 Camera                 | 13       | 1.17%   |
| Logitech Webcam C925e                   | 13       | 1.17%   |
| HD 2MP WEBCAM HD 2MP WEBCAM             | 13       | 1.17%   |
| Logitech Webcam C930e                   | 11       | 0.99%   |
| Logitech StreamCam                      | 11       | 0.99%   |
| Jieli USB PHY 2.0                       | 11       | 0.99%   |
| Generalplus GENERAL WEBCAM              | 10       | 0.9%    |
| Realtek Full HD webcam                  | 9        | 0.81%   |
| Microdia Camera                         | 8        | 0.72%   |
| Logitech QuickCam Pro 9000              | 8        | 0.72%   |
| Logitech BRIO 4K Stream Edition         | 8        | 0.72%   |
| Razer USA Gaming Webcam [Kiyo]          | 7        | 0.63%   |
| MacroSilicon USB Video                  | 7        | 0.63%   |
| AVerMedia Live Streamer CAM 313         | 7        | 0.63%   |
| Trust Trust USB Camera                  | 6        | 0.54%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 6        | 0.54%   |
| Microsoft LifeCam VX-5000               | 6        | 0.54%   |
| Microsoft LifeCam Studio                | 6        | 0.54%   |
| Microdia Integrated Camera              | 6        | 0.54%   |
| Logitech HD Webcam C910                 | 6        | 0.54%   |
| Microsoft LifeCam VX-2000               | 5        | 0.45%   |
| Logitech HD Webcam C510                 | 5        | 0.45%   |
| Logitech C505 HD Webcam                 | 5        | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 3        | 17.65%  |
| Elan Microelectronics | 3        | 17.65%  |
| DigitalPersona        | 3        | 17.65%  |
| AuthenTec             | 3        | 17.65%  |
| Synaptics             | 2        | 11.76%  |
| Upek                  | 1        | 5.88%   |
| Microsoft             | 1        | 5.88%   |
| Dell                  | 1        | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 3        | 17.65%  |
| DigitalPersona Fingerprint Reader              | 3        | 17.65%  |
| Synaptics  WBDI Fingerprint Reader - USB 052   | 2        | 11.76%  |
| LighTuning Fingerprint Sensor                  | 2        | 11.76%  |
| AuthenTec Fingerprint Sensor                   | 2        | 11.76%  |
| Upek TCS1C EIM/STM32 Fingerprint sensor        | 1        | 5.88%   |
| Microsoft Fingerprint Reader                   | 1        | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor    | 1        | 5.88%   |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 5.88%   |
| AuthenTec AES1600                              | 1        | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Yubico.com                        | 6        | 14.29%  |
| Realtek Semiconductor             | 5        | 11.9%   |
| Alcor Micro                       | 5        | 11.9%   |
| VASCO Data Security International | 4        | 9.52%   |
| SCM Microsystems                  | 4        | 9.52%   |
| OmniKey                           | 3        | 7.14%   |
| Gemalto (was Gemplus)             | 3        | 7.14%   |
| Cherry                            | 2        | 4.76%   |
| Aktiv                             | 2        | 4.76%   |
| Reiner SCT Kartensysteme          | 1        | 2.38%   |
| Fujitsu Siemens Computers         | 1        | 2.38%   |
| Feitian Technologies              | 1        | 2.38%   |
| Clay Logic                        | 1        | 2.38%   |
| Chicony Electronics               | 1        | 2.38%   |
| Bit4id                            | 1        | 2.38%   |
| Aladdin Knowledge Systems         | 1        | 2.38%   |
| Advanced Card Systems             | 1        | 2.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 11.9%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 4        | 9.52%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 3        | 7.14%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 7.14%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 7.14%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 7.14%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 4.76%   |
| Aktiv Rutoken lite                                                         | 2        | 4.76%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                        | 1        | 2.38%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 2.38%   |
| VASCO Data Security International DIGIPASS 870                             | 1        | 2.38%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                 | 1        | 2.38%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.38%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 2.38%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.38%   |
| OmniKey CardMan 1021                                                       | 1        | 2.38%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.38%   |
| Feitian Technologies FT SCR310                                             | 1        | 2.38%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 2.38%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 2.38%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.38%   |
| Cherry Smart Terminal XX44                                                 | 1        | 2.38%   |
| Bit4id miniLector EVO                                                      | 1        | 2.38%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 2.38%   |
| Advanced Card Systems ACR122U                                              | 1        | 2.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3700     | 85%     |
| 1     | 565      | 12.98%  |
| 2     | 58       | 1.33%   |
| 3     | 16       | 0.37%   |
| 4     | 7        | 0.16%   |
| 5     | 4        | 0.09%   |
| 6     | 2        | 0.05%   |
| 8     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 213      | 29.22%  |
| Net/wireless             | 210      | 28.81%  |
| Unassigned class         | 69       | 9.47%   |
| Sound                    | 40       | 5.49%   |
| Multimedia controller    | 38       | 5.21%   |
| Camera                   | 36       | 4.94%   |
| Communication controller | 35       | 4.8%    |
| Fingerprint reader       | 16       | 2.19%   |
| Storage/raid             | 12       | 1.65%   |
| Network                  | 11       | 1.51%   |
| Bluetooth                | 11       | 1.51%   |
| Net/ethernet             | 10       | 1.37%   |
| Card reader              | 7        | 0.96%   |
| Modem                    | 5        | 0.69%   |
| Chipcard                 | 5        | 0.69%   |
| Firewire controller      | 4        | 0.55%   |
| Dvb card                 | 2        | 0.27%   |
| Wireless                 | 1        | 0.14%   |
| Tv card                  | 1        | 0.14%   |
| Storage/nvme             | 1        | 0.14%   |
| Storage/ata              | 1        | 0.14%   |
| Storage                  | 1        | 0.14%   |

