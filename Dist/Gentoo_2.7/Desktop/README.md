Gentoo 2.7 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.7.

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

Total: 417

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B450 Pro4                   | [9d03e8cba7](https://linux-hardware.org/?probe=9d03e8cba7) | Jun 18, 2022 |
| ASUSTek       | M3A78-CM                    | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| ASUSTek       | M3A78-CM                    | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| ASRockRack    | E3C232D2I                   | [0442460b97](https://linux-hardware.org/?probe=0442460b97) | May 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| ASUSTek       | M3A78-CM                    | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [818ee286b7](https://linux-hardware.org/?probe=818ee286b7) | May 17, 2022 |
| MSI           | X570-A PRO                  | [28b47bc364](https://linux-hardware.org/?probe=28b47bc364) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| HP            | 8704                        | [b66f290b02](https://linux-hardware.org/?probe=b66f290b02) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| ASRock        | A320M Pro4                  | [b51c7ae18b](https://linux-hardware.org/?probe=b51c7ae18b) | May 04, 2022 |
| Gigabyte      | GA-970A-D3                  | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| ASUSTek       | Z97-K/USB                   | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASRock        | Z390 Extreme4               | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | PRIME X570-PRO              | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| MSI           | B560M PRO-VDH WIFI          | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| Alienware     | 0TYR0X A00                  | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Alienware     | 0TYR0X A00                  | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| MSI           | H81I                        | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| Gigabyte      | B460 HD3                    | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| ASUSTek       | PRIME B450M-K               | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |
| ASRock        | 970 Pro3 R2.0               | [d1697052d6](https://linux-hardware.org/?probe=d1697052d6) | Jan 20, 2022 |
| ASRock        | AM1H-ITX                    | [d22612635e](https://linux-hardware.org/?probe=d22612635e) | Jan 16, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | [73773b7de6](https://linux-hardware.org/?probe=73773b7de6) | Jan 16, 2022 |
| ASRock        | AM1H-ITX                    | [32aec4ead0](https://linux-hardware.org/?probe=32aec4ead0) | Jan 10, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [596fafa091](https://linux-hardware.org/?probe=596fafa091) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [d4b7cd87ac](https://linux-hardware.org/?probe=d4b7cd87ac) | Jan 05, 2022 |
| ASRock        | Q1900-ITX                   | [e7b19454b7](https://linux-hardware.org/?probe=e7b19454b7) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [519b9f223e](https://linux-hardware.org/?probe=519b9f223e) | Jan 03, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| Dell          | 0J3C2F A02                  | [a450e584b2](https://linux-hardware.org/?probe=a450e584b2) | Dec 22, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| Dell          | 0J3C2F A02                  | [b6d326beab](https://linux-hardware.org/?probe=b6d326beab) | Dec 16, 2021 |
| MSI           | Z87-G45 GAMING              | [882428b431](https://linux-hardware.org/?probe=882428b431) | Dec 15, 2021 |
| ASUSTek       | M3N78-EM                    | [bf180c5c33](https://linux-hardware.org/?probe=bf180c5c33) | Dec 11, 2021 |
| MSI           | B450 TOMAHAWK               | [4b39700892](https://linux-hardware.org/?probe=4b39700892) | Dec 09, 2021 |
| Dell          | 0J584C A00                  | [d443412bd4](https://linux-hardware.org/?probe=d443412bd4) | Dec 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [b0329b0b3f](https://linux-hardware.org/?probe=b0329b0b3f) | Nov 25, 2021 |
| MSI           | MEG X570 UNIFY              | [4492677869](https://linux-hardware.org/?probe=4492677869) | Nov 24, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [ddb6ba2a2b](https://linux-hardware.org/?probe=ddb6ba2a2b) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | [f8501c9239](https://linux-hardware.org/?probe=f8501c9239) | Nov 21, 2021 |
| HP            | ProLiant ML150 G6           | [734028d2b9](https://linux-hardware.org/?probe=734028d2b9) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Gigabyte      | H310M S2H x.x               | [10578c9535](https://linux-hardware.org/?probe=10578c9535) | Nov 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6d93d44cf9](https://linux-hardware.org/?probe=6d93d44cf9) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| ASRock        | B550M Steel Legend          | [fada2e4c02](https://linux-hardware.org/?probe=fada2e4c02) | Nov 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| ASUSTek       | PRIME X570-P                | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Gigabyte      | B460 HD3                    | [d3aa74a821](https://linux-hardware.org/?probe=d3aa74a821) | Oct 29, 2021 |
| ASRock        | B550M Steel Legend          | [df8ab9effb](https://linux-hardware.org/?probe=df8ab9effb) | Oct 28, 2021 |
| HP            | 0B4Ch D                     | [eb0c052885](https://linux-hardware.org/?probe=eb0c052885) | Oct 26, 2021 |
| ASUSTek       | PRIME A520M-K               | [740c97fb1c](https://linux-hardware.org/?probe=740c97fb1c) | Oct 26, 2021 |
| ASUSTek       | M3A78-CM                    | [aa48dedaf3](https://linux-hardware.org/?probe=aa48dedaf3) | Oct 25, 2021 |
| ASRock        | X570 Pro4                   | [ba339b925b](https://linux-hardware.org/?probe=ba339b925b) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-PRO              | [7ffce9bbc2](https://linux-hardware.org/?probe=7ffce9bbc2) | Oct 21, 2021 |
| ASUSTek       | PRIME X570-P                | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [8b5c674cb9](https://linux-hardware.org/?probe=8b5c674cb9) | Oct 17, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [38a6005914](https://linux-hardware.org/?probe=38a6005914) | Oct 15, 2021 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [a6457a6f8e](https://linux-hardware.org/?probe=a6457a6f8e) | Oct 15, 2021 |
| ASRock        | Z390 Extreme4               | [2da9a06ef2](https://linux-hardware.org/?probe=2da9a06ef2) | Oct 11, 2021 |
| MSI           | MEG X570 UNIFY              | [2e312a734f](https://linux-hardware.org/?probe=2e312a734f) | Oct 08, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [8319b2b5c6](https://linux-hardware.org/?probe=8319b2b5c6) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H V2               | [233f451319](https://linux-hardware.org/?probe=233f451319) | Oct 06, 2021 |
| HP            | 0B4Ch D                     | [02b5492901](https://linux-hardware.org/?probe=02b5492901) | Oct 06, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [67fc73c11e](https://linux-hardware.org/?probe=67fc73c11e) | Oct 04, 2021 |
| MSI           | Z370-A PRO                  | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [5ce182d7ae](https://linux-hardware.org/?probe=5ce182d7ae) | Oct 01, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [4044b3b3b2](https://linux-hardware.org/?probe=4044b3b3b2) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [6b625a8736](https://linux-hardware.org/?probe=6b625a8736) | Oct 01, 2021 |
| ASUSTek       | Maximus VIII HERO           | [1fce457ac6](https://linux-hardware.org/?probe=1fce457ac6) | Oct 01, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [87f779767d](https://linux-hardware.org/?probe=87f779767d) | Oct 01, 2021 |
| Acer          | Aspire XC-780               | [f723ac396a](https://linux-hardware.org/?probe=f723ac396a) | Oct 01, 2021 |
| ASRock        | H170 Pro4                   | [a0d0f5002e](https://linux-hardware.org/?probe=a0d0f5002e) | Sep 29, 2021 |
| ASRock        | H170 Pro4                   | [5a3652f38b](https://linux-hardware.org/?probe=5a3652f38b) | Sep 29, 2021 |
| Gigabyte      | 990FXA-UD5                  | [c3bb6d3afa](https://linux-hardware.org/?probe=c3bb6d3afa) | Sep 29, 2021 |
| Dell          | 0J3C2F A02                  | [88104169a4](https://linux-hardware.org/?probe=88104169a4) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [241866fa37](https://linux-hardware.org/?probe=241866fa37) | Sep 26, 2021 |
| ASRock        | X370 Professional Gaming    | [546f692061](https://linux-hardware.org/?probe=546f692061) | Sep 23, 2021 |
| Intel         | DG31PR AAD97573-205         | [2c022c21f0](https://linux-hardware.org/?probe=2c022c21f0) | Sep 22, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [86d356f643](https://linux-hardware.org/?probe=86d356f643) | Sep 16, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [308d39b0dc](https://linux-hardware.org/?probe=308d39b0dc) | Sep 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [19555ed132](https://linux-hardware.org/?probe=19555ed132) | Sep 07, 2021 |
| ASRock        | B450M-HDV R4.0              | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | P5P41C                      | [e68f372c7b](https://linux-hardware.org/?probe=e68f372c7b) | Sep 05, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [f63a2003ab](https://linux-hardware.org/?probe=f63a2003ab) | Sep 05, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [40d01ef03e](https://linux-hardware.org/?probe=40d01ef03e) | Aug 31, 2021 |
| Packard Be... | FMCP7AM                     | [6872ae9fb4](https://linux-hardware.org/?probe=6872ae9fb4) | Aug 31, 2021 |
| Gigabyte      | EP43-DS3                    | [0eaf518e06](https://linux-hardware.org/?probe=0eaf518e06) | Aug 29, 2021 |
| Dell          | 0U1325                      | [0a58fab188](https://linux-hardware.org/?probe=0a58fab188) | Aug 28, 2021 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | [00b0f43680](https://linux-hardware.org/?probe=00b0f43680) | Aug 28, 2021 |
| Packard Be... | FMCP7AM                     | [07fb4f5678](https://linux-hardware.org/?probe=07fb4f5678) | Aug 28, 2021 |
| MSI           | MS-7369                     | [0c6668dee5](https://linux-hardware.org/?probe=0c6668dee5) | Aug 28, 2021 |
| Dell          | 0U1325                      | [1b5dfb4b59](https://linux-hardware.org/?probe=1b5dfb4b59) | Aug 28, 2021 |
| ASUSTek       | P9X79 WS                    | [0569365ea0](https://linux-hardware.org/?probe=0569365ea0) | Aug 26, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [f521a0c69c](https://linux-hardware.org/?probe=f521a0c69c) | Aug 25, 2021 |
| MSI           | B450M PRO-M2 MAX            | [c09944da60](https://linux-hardware.org/?probe=c09944da60) | Aug 24, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [ae02b6e88b](https://linux-hardware.org/?probe=ae02b6e88b) | Aug 19, 2021 |
| ASUSTek       | P5P41C                      | [0eb4111089](https://linux-hardware.org/?probe=0eb4111089) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [4eb4c77752](https://linux-hardware.org/?probe=4eb4c77752) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5ffe57957d](https://linux-hardware.org/?probe=5ffe57957d) | Aug 18, 2021 |
| NZXT          | N7 Z370                     | [40f0739800](https://linux-hardware.org/?probe=40f0739800) | Aug 17, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [211803a510](https://linux-hardware.org/?probe=211803a510) | Aug 15, 2021 |
| MSI           | B550-A PRO                  | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| HP            | 158B                        | [d47aa82b20](https://linux-hardware.org/?probe=d47aa82b20) | Aug 12, 2021 |
| Intel         | D525MW AAE93082-301         | [fc72f0a0ea](https://linux-hardware.org/?probe=fc72f0a0ea) | Aug 11, 2021 |
| ASUSTek       | PRIME X470-PRO              | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [d74d9e37ce](https://linux-hardware.org/?probe=d74d9e37ce) | Aug 10, 2021 |
| Tekram Tec... | P6B40-A4X-i440BX Rev        | [33fffaf1c3](https://linux-hardware.org/?probe=33fffaf1c3) | Aug 07, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [ef7a0635f4](https://linux-hardware.org/?probe=ef7a0635f4) | Aug 04, 2021 |
| ASUSTek       | P6T DELUXE V2               | [51a1b8132e](https://linux-hardware.org/?probe=51a1b8132e) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| Dell          | 09WH54 A00                  | [9885d45d4f](https://linux-hardware.org/?probe=9885d45d4f) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [46b71409d7](https://linux-hardware.org/?probe=46b71409d7) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| Gigabyte      | 990FXA-UD5                  | [5a32ec902e](https://linux-hardware.org/?probe=5a32ec902e) | Jul 22, 2021 |
| Gigabyte      | H110-D3-CF                  | [7d25217f50](https://linux-hardware.org/?probe=7d25217f50) | Jul 22, 2021 |
| Gigabyte      | B460 HD3                    | [a43624a24b](https://linux-hardware.org/?probe=a43624a24b) | Jul 18, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [9356542b15](https://linux-hardware.org/?probe=9356542b15) | Jul 12, 2021 |
| ASRock        | B550M Steel Legend          | [4d378eb681](https://linux-hardware.org/?probe=4d378eb681) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| ASRock        | B550M Steel Legend          | [ab93056d13](https://linux-hardware.org/?probe=ab93056d13) | Jul 08, 2021 |
| MSI           | Z590-A PRO                  | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [4ef1e3ccac](https://linux-hardware.org/?probe=4ef1e3ccac) | Jul 03, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e618f85f9](https://linux-hardware.org/?probe=4e618f85f9) | Jul 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a2acbde7fd](https://linux-hardware.org/?probe=a2acbde7fd) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| MSI           | B450 TOMAHAWK               | [ac2a4b3aea](https://linux-hardware.org/?probe=ac2a4b3aea) | Jul 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b8cc7c380d](https://linux-hardware.org/?probe=b8cc7c380d) | Jun 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2831e5a8cf](https://linux-hardware.org/?probe=2831e5a8cf) | Jun 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d442a66371](https://linux-hardware.org/?probe=d442a66371) | Jun 27, 2021 |
| Apple         | Mac-F221BEC8                | [84bf6743c1](https://linux-hardware.org/?probe=84bf6743c1) | Jun 25, 2021 |
| Apple         | Mac-F221BEC8                | [ced7e0d00d](https://linux-hardware.org/?probe=ced7e0d00d) | Jun 25, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f0c7a3a628](https://linux-hardware.org/?probe=f0c7a3a628) | Jun 15, 2021 |
| ASUSTek       | P7P55D-E PRO                | [9a91c78c7a](https://linux-hardware.org/?probe=9a91c78c7a) | Jun 14, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [704bf0bba3](https://linux-hardware.org/?probe=704bf0bba3) | Jun 12, 2021 |
| MSI           | Z97 PC Mate                 | [73ece6c322](https://linux-hardware.org/?probe=73ece6c322) | Jun 02, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [a04eb698f8](https://linux-hardware.org/?probe=a04eb698f8) | May 30, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [2767965856](https://linux-hardware.org/?probe=2767965856) | May 27, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [843f1d9b38](https://linux-hardware.org/?probe=843f1d9b38) | May 25, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | [5794d366c2](https://linux-hardware.org/?probe=5794d366c2) | May 25, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [49458a2df1](https://linux-hardware.org/?probe=49458a2df1) | May 24, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [73ff247804](https://linux-hardware.org/?probe=73ff247804) | May 24, 2021 |
| MSI           | X570-A PRO                  | [61a5d17b5b](https://linux-hardware.org/?probe=61a5d17b5b) | May 22, 2021 |
| MSI           | Z590-A PRO                  | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Unknown       | Cubietech Cubieboard2       | [d777d4b535](https://linux-hardware.org/?probe=d777d4b535) | May 22, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [95fb77ceae](https://linux-hardware.org/?probe=95fb77ceae) | May 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [1c2f94847e](https://linux-hardware.org/?probe=1c2f94847e) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | [5104abb7a7](https://linux-hardware.org/?probe=5104abb7a7) | May 20, 2021 |
| HP            | 8643 SMVB                   | [b183baddef](https://linux-hardware.org/?probe=b183baddef) | May 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4f3165b957](https://linux-hardware.org/?probe=4f3165b957) | May 19, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2679a5931a](https://linux-hardware.org/?probe=2679a5931a) | May 19, 2021 |
| ASRock        | B450 Pro4                   | [7ae6a0f74b](https://linux-hardware.org/?probe=7ae6a0f74b) | May 18, 2021 |
| ASUSTek       | PRIME B450M-K               | [8110fad44d](https://linux-hardware.org/?probe=8110fad44d) | May 17, 2021 |
| MSI           | Z590-A PRO                  | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| ASUSTek       | PRIME X470-PRO              | [065d69be16](https://linux-hardware.org/?probe=065d69be16) | May 13, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| ASUSTek       | M3A78-CM                    | [e305a7301f](https://linux-hardware.org/?probe=e305a7301f) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| ASUSTek       | PRIME B450M-K               | [ae4420d3a9](https://linux-hardware.org/?probe=ae4420d3a9) | May 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [aff27ae264](https://linux-hardware.org/?probe=aff27ae264) | Apr 29, 2021 |
| MSI           | MEG X570 UNIFY              | [fe32c3d470](https://linux-hardware.org/?probe=fe32c3d470) | Apr 29, 2021 |
| Unknown       | Freecom Silverstore HNCN... | [c54d9f2c0c](https://linux-hardware.org/?probe=c54d9f2c0c) | Apr 23, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [0db8148a33](https://linux-hardware.org/?probe=0db8148a33) | Apr 17, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5bc34889b8](https://linux-hardware.org/?probe=5bc34889b8) | Apr 17, 2021 |
| MSI           | H310M PRO-VD PLUS           | [de7b86720f](https://linux-hardware.org/?probe=de7b86720f) | Apr 10, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [07427b8218](https://linux-hardware.org/?probe=07427b8218) | Apr 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | [ab8b789fc2](https://linux-hardware.org/?probe=ab8b789fc2) | Apr 06, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [1f560968ab](https://linux-hardware.org/?probe=1f560968ab) | Apr 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | [d51b8b7f04](https://linux-hardware.org/?probe=d51b8b7f04) | Apr 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| ASUSTek       | P8H67-M PRO                 | [95722413a6](https://linux-hardware.org/?probe=95722413a6) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [65b87ee7d8](https://linux-hardware.org/?probe=65b87ee7d8) | Mar 29, 2021 |
| ASRock        | 970 Pro3 R2.0               | [58e2163a18](https://linux-hardware.org/?probe=58e2163a18) | Mar 29, 2021 |
| ASUSTek       | PRIME TRX40-PRO             | [f4da24790d](https://linux-hardware.org/?probe=f4da24790d) | Mar 27, 2021 |
| BESSTAR Te... | DMAF5 V1.0                  | [ea2ebcb877](https://linux-hardware.org/?probe=ea2ebcb877) | Mar 26, 2021 |
| ASUSTek       | M4N78-VM                    | [b3d61c6fbd](https://linux-hardware.org/?probe=b3d61c6fbd) | Mar 24, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [b89f0d11bd](https://linux-hardware.org/?probe=b89f0d11bd) | Mar 23, 2021 |
| Gigabyte      | Z490 AORUS MASTER           | [c17cb184a4](https://linux-hardware.org/?probe=c17cb184a4) | Mar 22, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [26b5c18aba](https://linux-hardware.org/?probe=26b5c18aba) | Mar 22, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| ASRock        | B450M Pro4                  | [41c48a20a2](https://linux-hardware.org/?probe=41c48a20a2) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASRock        | B450M Pro4                  | [b075ade19c](https://linux-hardware.org/?probe=b075ade19c) | Mar 18, 2021 |
| ASUSTek       | P5Q-E                       | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| ASUSTek       | B85M-E                      | [46c2411987](https://linux-hardware.org/?probe=46c2411987) | Mar 17, 2021 |
| ASRock        | X370 Professional Gaming    | [677c76f624](https://linux-hardware.org/?probe=677c76f624) | Mar 17, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [fb88aba821](https://linux-hardware.org/?probe=fb88aba821) | Mar 17, 2021 |
| MSI           | B450I GAMING PLUS AC        | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| ASUSTek       | PRIME X570-P                | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [bf856bd378](https://linux-hardware.org/?probe=bf856bd378) | Mar 11, 2021 |
| MSI           | X570-A PRO                  | [c19dde029b](https://linux-hardware.org/?probe=c19dde029b) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [0c34f3246f](https://linux-hardware.org/?probe=0c34f3246f) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [fb91319fa1](https://linux-hardware.org/?probe=fb91319fa1) | Mar 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [9f55c5ece0](https://linux-hardware.org/?probe=9f55c5ece0) | Mar 06, 2021 |
| ASRock        | B550M Steel Legend          | [4c28c6d22c](https://linux-hardware.org/?probe=4c28c6d22c) | Mar 03, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [6cd953f597](https://linux-hardware.org/?probe=6cd953f597) | Mar 02, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [d7a5611d8a](https://linux-hardware.org/?probe=d7a5611d8a) | Feb 23, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d854654bad](https://linux-hardware.org/?probe=d854654bad) | Feb 23, 2021 |
| MSI           | 970 GAMING                  | [062ccac9ff](https://linux-hardware.org/?probe=062ccac9ff) | Feb 22, 2021 |
| ASUSTek       | PRIME H470M-PLUS            | [0e4ce5d923](https://linux-hardware.org/?probe=0e4ce5d923) | Feb 22, 2021 |
| ASUSTek       | M3A78-CM                    | [ae309000e1](https://linux-hardware.org/?probe=ae309000e1) | Feb 22, 2021 |
| ASRock        | X370 Gaming X               | [97b686fad6](https://linux-hardware.org/?probe=97b686fad6) | Feb 21, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [f9639ea950](https://linux-hardware.org/?probe=f9639ea950) | Feb 20, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [ac8250480a](https://linux-hardware.org/?probe=ac8250480a) | Feb 16, 2021 |
| MSI           | MEG X570 UNIFY              | [8565fa7232](https://linux-hardware.org/?probe=8565fa7232) | Feb 15, 2021 |
| MSI           | B350M BAZOOKA               | [19cf6a4def](https://linux-hardware.org/?probe=19cf6a4def) | Feb 15, 2021 |
| ASUSTek       | P8Z68-V LX                  | [47dbd40dae](https://linux-hardware.org/?probe=47dbd40dae) | Feb 13, 2021 |
| ASRock        | AM1H-ITX                    | [a1c5772342](https://linux-hardware.org/?probe=a1c5772342) | Feb 03, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0d787440f2](https://linux-hardware.org/?probe=0d787440f2) | Feb 01, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [ec933f8e8a](https://linux-hardware.org/?probe=ec933f8e8a) | Jan 31, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6d86921fcf](https://linux-hardware.org/?probe=6d86921fcf) | Jan 26, 2021 |
| ASRock        | X370 Gaming X               | [8f0d93f4e1](https://linux-hardware.org/?probe=8f0d93f4e1) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [1b3702adc5](https://linux-hardware.org/?probe=1b3702adc5) | Jan 25, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [8eb3edac54](https://linux-hardware.org/?probe=8eb3edac54) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [dc087e0399](https://linux-hardware.org/?probe=dc087e0399) | Jan 24, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [de171f7a35](https://linux-hardware.org/?probe=de171f7a35) | Jan 24, 2021 |
| MSI           | Z170-A PRO                  | [6c8926dc8c](https://linux-hardware.org/?probe=6c8926dc8c) | Jan 23, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [23602ad020](https://linux-hardware.org/?probe=23602ad020) | Jan 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [b5f6cc5993](https://linux-hardware.org/?probe=b5f6cc5993) | Jan 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8c1e988f7e](https://linux-hardware.org/?probe=8c1e988f7e) | Jan 18, 2021 |
| MSI           | MEG X570 GODLIKE            | [5964a40d34](https://linux-hardware.org/?probe=5964a40d34) | Jan 17, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | [25fb58cc9f](https://linux-hardware.org/?probe=25fb58cc9f) | Jan 16, 2021 |
| Gigabyte      | Z170X-Gaming 3              | [e4ab17605e](https://linux-hardware.org/?probe=e4ab17605e) | Jan 13, 2021 |
| ASRock        | J3455-ITX                   | [89257face1](https://linux-hardware.org/?probe=89257face1) | Jan 12, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [38332ee350](https://linux-hardware.org/?probe=38332ee350) | Jan 11, 2021 |
| HP            | 158B                        | [6bc73950dd](https://linux-hardware.org/?probe=6bc73950dd) | Jan 10, 2021 |
| ASRock        | B450 Pro4                   | [1b9975eef6](https://linux-hardware.org/?probe=1b9975eef6) | Jan 08, 2021 |
| ASRock        | X570 Steel Legend           | [48d53df339](https://linux-hardware.org/?probe=48d53df339) | Jan 08, 2021 |
| MSI           | 990FXA-GD80                 | [cc4b365068](https://linux-hardware.org/?probe=cc4b365068) | Jan 08, 2021 |
| ASRock        | B550M Steel Legend          | [a6b6bbef69](https://linux-hardware.org/?probe=a6b6bbef69) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| ASRock        | AB350M Pro4                 | [b75dcb6545](https://linux-hardware.org/?probe=b75dcb6545) | Jan 05, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6f95de2b32](https://linux-hardware.org/?probe=6f95de2b32) | Jan 05, 2021 |
| ASUSTek       | P5Q-E                       | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a011c9b38f](https://linux-hardware.org/?probe=a011c9b38f) | Jan 02, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [182deb31fb](https://linux-hardware.org/?probe=182deb31fb) | Jan 02, 2021 |
| ASRock        | 970 Pro3 R2.0               | [b83ea4b5b3](https://linux-hardware.org/?probe=b83ea4b5b3) | Jan 02, 2021 |
| ASRock        | AM1H-ITX                    | [2bd69bdc3e](https://linux-hardware.org/?probe=2bd69bdc3e) | Dec 27, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [87e72db668](https://linux-hardware.org/?probe=87e72db668) | Dec 23, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d00787942f](https://linux-hardware.org/?probe=d00787942f) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a733d01196](https://linux-hardware.org/?probe=a733d01196) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [bd927d4e12](https://linux-hardware.org/?probe=bd927d4e12) | Dec 22, 2020 |
| ASRock        | B550M Steel Legend          | [a41b1e7e12](https://linux-hardware.org/?probe=a41b1e7e12) | Dec 22, 2020 |
| ASRock        | X570 Taichi                 | [29d14ce28a](https://linux-hardware.org/?probe=29d14ce28a) | Dec 19, 2020 |
| ASRock        | H170M Pro4S                 | [debbcde352](https://linux-hardware.org/?probe=debbcde352) | Dec 11, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | [e8e2d0cdfc](https://linux-hardware.org/?probe=e8e2d0cdfc) | Dec 05, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [3dc100c9a1](https://linux-hardware.org/?probe=3dc100c9a1) | Dec 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [50917002e1](https://linux-hardware.org/?probe=50917002e1) | Dec 01, 2020 |
| MSI           | B450M PRO-VDH MAX           | [03753743e7](https://linux-hardware.org/?probe=03753743e7) | Nov 30, 2020 |
| Gigabyte      | EP45T-DS3                   | [45142a6931](https://linux-hardware.org/?probe=45142a6931) | Nov 30, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7eeb446aee](https://linux-hardware.org/?probe=7eeb446aee) | Nov 30, 2020 |
| ASUSTek       | P9X79 WS                    | [24cfa19ea6](https://linux-hardware.org/?probe=24cfa19ea6) | Nov 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ba86d65e42](https://linux-hardware.org/?probe=ba86d65e42) | Nov 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78d68d35d8](https://linux-hardware.org/?probe=78d68d35d8) | Nov 26, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [35233c6000](https://linux-hardware.org/?probe=35233c6000) | Nov 26, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dcaf1f3521](https://linux-hardware.org/?probe=dcaf1f3521) | Nov 24, 2020 |
| ASUSTek       | P8Z77-V LX                  | [af91f8b0d0](https://linux-hardware.org/?probe=af91f8b0d0) | Nov 24, 2020 |
| MSI           | B350 GAMING PLUS            | [3e9e5d4c8d](https://linux-hardware.org/?probe=3e9e5d4c8d) | Nov 22, 2020 |
| ASUSTek       | PRIME TRX40-PRO             | [9b888a1a9c](https://linux-hardware.org/?probe=9b888a1a9c) | Nov 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [a6ab09a54b](https://linux-hardware.org/?probe=a6ab09a54b) | Nov 19, 2020 |
| ASRock        | X570 Pro4                   | [963200e763](https://linux-hardware.org/?probe=963200e763) | Nov 18, 2020 |
| ASUSTek       | PRIME X370-PRO              | [04abcfd451](https://linux-hardware.org/?probe=04abcfd451) | Nov 18, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [7ac134ec7a](https://linux-hardware.org/?probe=7ac134ec7a) | Nov 18, 2020 |
| ASUSTek       | PRIME X470-PRO              | [a4bdac2cea](https://linux-hardware.org/?probe=a4bdac2cea) | Nov 18, 2020 |
| ASRock        | B450 Pro4                   | [c920df4f73](https://linux-hardware.org/?probe=c920df4f73) | Nov 13, 2020 |
| MSI           | B450-A PRO                  | [00aeeab6da](https://linux-hardware.org/?probe=00aeeab6da) | Nov 08, 2020 |
| MSI           | B450-A PRO                  | [cd67b65826](https://linux-hardware.org/?probe=cd67b65826) | Nov 06, 2020 |
| ASUSTek       | A88XM-A                     | [45cf973d9c](https://linux-hardware.org/?probe=45cf973d9c) | Oct 31, 2020 |
| MSI           | Z170-A PRO                  | [6f36f04e56](https://linux-hardware.org/?probe=6f36f04e56) | Oct 31, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | [539bba5a4d](https://linux-hardware.org/?probe=539bba5a4d) | Oct 26, 2020 |
| ASRock        | AM1H-ITX                    | [4a6634694e](https://linux-hardware.org/?probe=4a6634694e) | Oct 25, 2020 |
| ASRock        | X370 Gaming X               | [7b50c1e794](https://linux-hardware.org/?probe=7b50c1e794) | Oct 25, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | PRIME X570-PRO              | [3a4156ad86](https://linux-hardware.org/?probe=3a4156ad86) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [3264edefe8](https://linux-hardware.org/?probe=3264edefe8) | Oct 17, 2020 |
| MSI           | H110M PRO-VD PLUS           | [49f9ade50f](https://linux-hardware.org/?probe=49f9ade50f) | Oct 17, 2020 |
| Gigabyte      | H110M-S2V-CF                | [2fe8128b94](https://linux-hardware.org/?probe=2fe8128b94) | Oct 15, 2020 |
| HP            | 8643 SMVB                   | [b1ebd820ea](https://linux-hardware.org/?probe=b1ebd820ea) | Oct 14, 2020 |
| ASRock        | N3150-ITX                   | [50872ff699](https://linux-hardware.org/?probe=50872ff699) | Oct 14, 2020 |
| MSI           | Z370 PC PRO                 | [6fdfdd701e](https://linux-hardware.org/?probe=6fdfdd701e) | Oct 14, 2020 |
| Dell          | 0PC5F7 A02                  | [0b4436db73](https://linux-hardware.org/?probe=0b4436db73) | Oct 14, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [bb7e9817f3](https://linux-hardware.org/?probe=bb7e9817f3) | Oct 13, 2020 |
| ASUSTek       | H97M-PLUS                   | [979e26a9ff](https://linux-hardware.org/?probe=979e26a9ff) | Oct 13, 2020 |
| Gigabyte      | H110M-S2V-CF                | [e13bfd8911](https://linux-hardware.org/?probe=e13bfd8911) | Oct 13, 2020 |
| ASRock        | X570M Pro4                  | [11624f2e68](https://linux-hardware.org/?probe=11624f2e68) | Oct 12, 2020 |
| ASRock        | X370 Professional Gaming    | [2b432df0be](https://linux-hardware.org/?probe=2b432df0be) | Oct 12, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [4c9fc71c64](https://linux-hardware.org/?probe=4c9fc71c64) | Oct 06, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f3201a0e2c](https://linux-hardware.org/?probe=f3201a0e2c) | Oct 06, 2020 |
| ASUSTek       | H61M-K                      | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| MSI           | X370 XPOWER GAMING TITAN... | [f09de8f7dc](https://linux-hardware.org/?probe=f09de8f7dc) | Oct 01, 2020 |
| Unknown       | Intel X79                   | [3849825892](https://linux-hardware.org/?probe=3849825892) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [b048626385](https://linux-hardware.org/?probe=b048626385) | Sep 29, 2020 |
| ASUSTek       | PRIME X470-PRO              | [e26cc6bcb0](https://linux-hardware.org/?probe=e26cc6bcb0) | Sep 29, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [c8d28c60cd](https://linux-hardware.org/?probe=c8d28c60cd) | Sep 27, 2020 |
| ASRock        | Z170 OC Formula             | [b478607fef](https://linux-hardware.org/?probe=b478607fef) | Sep 26, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | [0997ff40b0](https://linux-hardware.org/?probe=0997ff40b0) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [00290a5d85](https://linux-hardware.org/?probe=00290a5d85) | Sep 26, 2020 |
| MSI           | B350 TOMAHAWK               | [449d8022e1](https://linux-hardware.org/?probe=449d8022e1) | Sep 26, 2020 |
| ASUSTek       | H81M-PLUS                   | [87f345b258](https://linux-hardware.org/?probe=87f345b258) | Sep 24, 2020 |
| Acer          | Aspire XC-710 V:1.1         | [644c742328](https://linux-hardware.org/?probe=644c742328) | Sep 23, 2020 |
| MSI           | B450M PRO-VDH PLUS          | [aac147ef3c](https://linux-hardware.org/?probe=aac147ef3c) | Sep 22, 2020 |
| ASRock        | AB350M Pro4                 | [6cd6f20aef](https://linux-hardware.org/?probe=6cd6f20aef) | Sep 22, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f2bdd44684](https://linux-hardware.org/?probe=f2bdd44684) | Sep 18, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [15e4e278e8](https://linux-hardware.org/?probe=15e4e278e8) | Sep 18, 2020 |
| ASRock        | 970A-G                      | [c76564a1e5](https://linux-hardware.org/?probe=c76564a1e5) | Sep 16, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a1cc53584d](https://linux-hardware.org/?probe=a1cc53584d) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [cf465b6ceb](https://linux-hardware.org/?probe=cf465b6ceb) | Sep 05, 2020 |
| ASRock        | B450M-HDV R4.0              | [34b84c17b7](https://linux-hardware.org/?probe=34b84c17b7) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [4a62067798](https://linux-hardware.org/?probe=4a62067798) | Sep 03, 2020 |
| Gigabyte      | Z77X-UD5H                   | [ced4076cfe](https://linux-hardware.org/?probe=ced4076cfe) | Sep 03, 2020 |
| MSI           | B450M MORTAR MAX            | [aacb67377f](https://linux-hardware.org/?probe=aacb67377f) | Sep 03, 2020 |
| MSI           | B450M PRO-VDH MAX           | [3aacd1b61b](https://linux-hardware.org/?probe=3aacd1b61b) | Sep 03, 2020 |
| MSI           | Z97-G45 GAMING              | [e86bf6dfb8](https://linux-hardware.org/?probe=e86bf6dfb8) | Sep 03, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4bf504d82b](https://linux-hardware.org/?probe=4bf504d82b) | Sep 03, 2020 |
| MSI           | X470 GAMING PLUS            | [84aef475d9](https://linux-hardware.org/?probe=84aef475d9) | Sep 02, 2020 |
| MSI           | Z77IA-E53                   | [bf99082e95](https://linux-hardware.org/?probe=bf99082e95) | Aug 28, 2020 |
| ASUSTek       | Z170-A                      | [af1f86e610](https://linux-hardware.org/?probe=af1f86e610) | Aug 25, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d17e5bf1f8](https://linux-hardware.org/?probe=d17e5bf1f8) | Aug 25, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0230526040](https://linux-hardware.org/?probe=0230526040) | Aug 20, 2020 |
| Unknown       | Unknown                     | [41ab260322](https://linux-hardware.org/?probe=41ab260322) | Aug 20, 2020 |
| Unknown       | Unknown                     | [6a7fc0088c](https://linux-hardware.org/?probe=6a7fc0088c) | Aug 19, 2020 |
| MSI           | B350 GAMING PRO CARBON      | [762b0fed7b](https://linux-hardware.org/?probe=762b0fed7b) | Aug 18, 2020 |
| Unknown       | Unknown                     | [3d3ed1b8ce](https://linux-hardware.org/?probe=3d3ed1b8ce) | Aug 15, 2020 |
| Unknown       | Unknown                     | [55f1b3cdce](https://linux-hardware.org/?probe=55f1b3cdce) | Aug 15, 2020 |
| ASUSTek       | PRIME X370-PRO              | [7d01f814d5](https://linux-hardware.org/?probe=7d01f814d5) | Aug 10, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| ASUSTek       | P6X58D-E                    | [3db01937e1](https://linux-hardware.org/?probe=3db01937e1) | Aug 05, 2020 |
| ASRock        | X370 Taichi                 | [e08f62cb80](https://linux-hardware.org/?probe=e08f62cb80) | Jul 23, 2020 |
| ASUSTek       | X99-M WS                    | [7a813c93b0](https://linux-hardware.org/?probe=7a813c93b0) | Jul 15, 2020 |
| Unknown       | Unknown                     | [d83097e656](https://linux-hardware.org/?probe=d83097e656) | Jul 13, 2020 |
| ASUSTek       | GRYPHON Z97                 | [e7b3ad7e11](https://linux-hardware.org/?probe=e7b3ad7e11) | Jul 07, 2020 |
| ASUSTek       | PRIME X570-PRO              | [dd3e957888](https://linux-hardware.org/?probe=dd3e957888) | Jul 03, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [f54a86a6b4](https://linux-hardware.org/?probe=f54a86a6b4) | Jun 30, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [c9529f922d](https://linux-hardware.org/?probe=c9529f922d) | Jun 29, 2020 |
| ASRockRack    | C226M WS                    | [adb729fe45](https://linux-hardware.org/?probe=adb729fe45) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [12ca04e727](https://linux-hardware.org/?probe=12ca04e727) | Jun 27, 2020 |
| ASUSTek       | PRIME X570-P                | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASRock        | X370 Killer SLI             | [e68e55ff91](https://linux-hardware.org/?probe=e68e55ff91) | Jun 20, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a91b7a6ef3](https://linux-hardware.org/?probe=a91b7a6ef3) | Jun 16, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [78a788e5aa](https://linux-hardware.org/?probe=78a788e5aa) | Jun 14, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [d1c9757c3c](https://linux-hardware.org/?probe=d1c9757c3c) | Jun 11, 2020 |
| MSI           | X570-A PRO                  | [d330af6317](https://linux-hardware.org/?probe=d330af6317) | Jun 09, 2020 |
| ASUSTek       | Z170-A                      | [81dbec3df4](https://linux-hardware.org/?probe=81dbec3df4) | Jun 09, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [40b9dbe4a5](https://linux-hardware.org/?probe=40b9dbe4a5) | Jun 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [50cf5c19df](https://linux-hardware.org/?probe=50cf5c19df) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | WS X299 SAGE                | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [9c7b7cde1e](https://linux-hardware.org/?probe=9c7b7cde1e) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [e64653b77c](https://linux-hardware.org/?probe=e64653b77c) | Jun 04, 2020 |
| ASRock        | X399 Taichi                 | [ff470637f1](https://linux-hardware.org/?probe=ff470637f1) | Jun 04, 2020 |
| ASUSTek       | PRIME B450M-A               | [38d7220c47](https://linux-hardware.org/?probe=38d7220c47) | Jun 04, 2020 |
| ASRock        | Z390 Extreme4               | [b379b98120](https://linux-hardware.org/?probe=b379b98120) | Jun 04, 2020 |
| Gigabyte      | X570 AORUS XTREME           | [cf5cf7d297](https://linux-hardware.org/?probe=cf5cf7d297) | Jun 04, 2020 |
| ASUSTek       | P6X58D-E                    | [219e253757](https://linux-hardware.org/?probe=219e253757) | Jun 04, 2020 |
| MSI           | X470 GAMING PLUS            | [713a47cd93](https://linux-hardware.org/?probe=713a47cd93) | Jun 04, 2020 |
| ASUSTek       | PRIME X370-PRO              | [66b855cb1f](https://linux-hardware.org/?probe=66b855cb1f) | Jun 04, 2020 |
| ASUSTek       | P8H67-M PRO                 | [3eeead93cd](https://linux-hardware.org/?probe=3eeead93cd) | Jun 03, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | [19202ed9bc](https://linux-hardware.org/?probe=19202ed9bc) | Jun 03, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [781f2cda04](https://linux-hardware.org/?probe=781f2cda04) | Jun 03, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [03524be236](https://linux-hardware.org/?probe=03524be236) | Jun 03, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [452ae63632](https://linux-hardware.org/?probe=452ae63632) | Jun 03, 2020 |
| Intel         | DH77KC AAG39641-400         | [c70d57d5e5](https://linux-hardware.org/?probe=c70d57d5e5) | Jun 03, 2020 |
| ASRock        | X399 Taichi                 | [9c9844febe](https://linux-hardware.org/?probe=9c9844febe) | Jun 03, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [656aaf0582](https://linux-hardware.org/?probe=656aaf0582) | Jun 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [e69d1396bf](https://linux-hardware.org/?probe=e69d1396bf) | Jun 03, 2020 |
| ASRock        | X570 Steel Legend           | [379b9c17e4](https://linux-hardware.org/?probe=379b9c17e4) | May 31, 2020 |
| ASRock        | B450M-HDV R4.0              | [e0cde3f93b](https://linux-hardware.org/?probe=e0cde3f93b) | May 25, 2020 |
| ASUSTek       | P6TD DELUXE                 | [2a97c35b6b](https://linux-hardware.org/?probe=2a97c35b6b) | May 23, 2020 |
| Sun Micros... | Ultra 24 50                 | [2541d35bd4](https://linux-hardware.org/?probe=2541d35bd4) | May 23, 2020 |
| Gigabyte      | H370M D3H-CF                | [1f405a7557](https://linux-hardware.org/?probe=1f405a7557) | May 23, 2020 |
| HP            | 3648h                       | [14b2a01c1d](https://linux-hardware.org/?probe=14b2a01c1d) | May 23, 2020 |
| ASRockRack    | X470D4U                     | [09640a1376](https://linux-hardware.org/?probe=09640a1376) | May 23, 2020 |
| HP            | 0B54h D                     | [4ef026497f](https://linux-hardware.org/?probe=4ef026497f) | May 23, 2020 |
| Gigabyte      | A320M-S2H-CF                | [7d37b8ad19](https://linux-hardware.org/?probe=7d37b8ad19) | May 12, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [4e05b9111b](https://linux-hardware.org/?probe=4e05b9111b) | May 12, 2020 |
| HP            | 83C1                        | [8b7d6722b2](https://linux-hardware.org/?probe=8b7d6722b2) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | [42ec09f78b](https://linux-hardware.org/?probe=42ec09f78b) | May 11, 2020 |
| ASRock        | X370 Gaming K4              | [6874d82c83](https://linux-hardware.org/?probe=6874d82c83) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | [86a0177aac](https://linux-hardware.org/?probe=86a0177aac) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | [8bca8a21eb](https://linux-hardware.org/?probe=8bca8a21eb) | May 11, 2020 |
| ASRock        | X470 Taichi                 | [8ca172b725](https://linux-hardware.org/?probe=8ca172b725) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| ASUSTek       | P8B75-V                     | [05258aea35](https://linux-hardware.org/?probe=05258aea35) | May 11, 2020 |
| ASUSTek       | PRIME X470-PRO              | [0a33d02a42](https://linux-hardware.org/?probe=0a33d02a42) | May 10, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9fce6c2df1](https://linux-hardware.org/?probe=9fce6c2df1) | Apr 25, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [8625c51506](https://linux-hardware.org/?probe=8625c51506) | Apr 19, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [baaff2d847](https://linux-hardware.org/?probe=baaff2d847) | Mar 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [22662aad4d](https://linux-hardware.org/?probe=22662aad4d) | Mar 26, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [4514d59538](https://linux-hardware.org/?probe=4514d59538) | Mar 19, 2020 |
| ASRock        | Z68 Extreme4 Gen3           | [26c5187786](https://linux-hardware.org/?probe=26c5187786) | Mar 19, 2020 |
| ASRock        | Z170 OC Formula             | [189475c3f5](https://linux-hardware.org/?probe=189475c3f5) | Mar 04, 2020 |
| ASRock        | Z170 OC Formula             | [a405f01061](https://linux-hardware.org/?probe=a405f01061) | Mar 04, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b417c8e979](https://linux-hardware.org/?probe=b417c8e979) | Feb 24, 2020 |
| Gigabyte      | GA-990FXA-UD5               | [24bf705591](https://linux-hardware.org/?probe=24bf705591) | Feb 14, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [169fe41d8b](https://linux-hardware.org/?probe=169fe41d8b) | Jan 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.7.0-gentoo          | 8        | 2.34%   |
| 5.10.61-gentoo        | 8        | 2.34%   |
| 5.10.27-gentoo        | 8        | 2.34%   |
| 5.10.27-gentoo-x86_64 | 7        | 2.05%   |
| 5.10.61-gentoo-x86_64 | 6        | 1.75%   |
| 5.6.15-gentoo         | 5        | 1.46%   |
| 5.6.11-gentoo         | 5        | 1.46%   |
| 5.4.97-gentoo         | 5        | 1.46%   |
| 5.15.32-gentoo-r1     | 5        | 1.46%   |
| 5.10.52-gentoo        | 5        | 1.46%   |
| 5.9.11-gentoo         | 4        | 1.17%   |
| 5.10.76-gentoo-r1     | 4        | 1.17%   |
| 5.9.9-gentoo          | 3        | 0.88%   |
| 5.9.8-gentoo          | 3        | 0.88%   |
| 5.9.11                | 3        | 0.88%   |
| 5.9.1-gentoo          | 3        | 0.88%   |
| 5.6.15-gentoo-x86_64  | 3        | 0.88%   |
| 5.4.80-gentoo-r1      | 3        | 0.88%   |
| 5.13.5-gentoo         | 3        | 0.88%   |
| 5.11.6-gentoo         | 3        | 0.88%   |
| 5.10.4-gentoo         | 3        | 0.88%   |
| 5.10.35-gentoo        | 3        | 0.88%   |
| 5.10.2-gentoo         | 3        | 0.88%   |
| 5.9.8                 | 2        | 0.58%   |
| 5.9.13-gentoo         | 2        | 0.58%   |
| 5.8.10-gentoo         | 2        | 0.58%   |
| 5.8.0-gentoo-r1       | 2        | 0.58%   |
| 5.7.9-gentoo          | 2        | 0.58%   |
| 5.7.6-gentoo          | 2        | 0.58%   |
| 5.6.2-gentoo          | 2        | 0.58%   |
| 5.6.14-gentoo         | 2        | 0.58%   |
| 5.6.13                | 2        | 0.58%   |
| 5.5.0-gentoo-x86_64   | 2        | 0.58%   |
| 5.4.97-gentoo-x86_64  | 2        | 0.58%   |
| 5.4.72-gentoo         | 2        | 0.58%   |
| 5.17.5-gentoo         | 2        | 0.58%   |
| 5.15.23-gentoo        | 2        | 0.58%   |
| 5.14.14-gentoo        | 2        | 0.58%   |
| 5.13.12               | 2        | 0.58%   |
| 5.13.0-gentoo         | 2        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.27 | 19       | 5.56%   |
| 5.10.61 | 16       | 4.68%   |
| 5.7.0   | 11       | 3.22%   |
| 5.6.15  | 11       | 3.22%   |
| 5.10.52 | 11       | 3.22%   |
| 5.10.76 | 10       | 2.92%   |
| 5.9.11  | 9        | 2.63%   |
| 5.4.97  | 8        | 2.34%   |
| 5.15.32 | 8        | 2.34%   |
| 5.9.8   | 6        | 1.75%   |
| 5.8.10  | 6        | 1.75%   |
| 5.6.11  | 6        | 1.75%   |
| 5.11.6  | 6        | 1.75%   |
| 5.9.0   | 4        | 1.17%   |
| 5.8.0   | 4        | 1.17%   |
| 5.6.14  | 4        | 1.17%   |
| 5.6.13  | 4        | 1.17%   |
| 5.6.0   | 4        | 1.17%   |
| 5.4.80  | 4        | 1.17%   |
| 5.10.5  | 4        | 1.17%   |
| 5.10.2  | 4        | 1.17%   |
| 5.10.10 | 4        | 1.17%   |
| 5.9.9   | 3        | 0.88%   |
| 5.9.1   | 3        | 0.88%   |
| 5.7.9   | 3        | 0.88%   |
| 5.7.6   | 3        | 0.88%   |
| 5.5.0   | 3        | 0.88%   |
| 5.17.1  | 3        | 0.88%   |
| 5.13.5  | 3        | 0.88%   |
| 5.13.12 | 3        | 0.88%   |
| 5.13.0  | 3        | 0.88%   |
| 5.12.5  | 3        | 0.88%   |
| 5.11.2  | 3        | 0.88%   |
| 5.11.10 | 3        | 0.88%   |
| 5.10.6  | 3        | 0.88%   |
| 5.10.4  | 3        | 0.88%   |
| 5.10.35 | 3        | 0.88%   |
| 5.9.13  | 2        | 0.58%   |
| 5.8.9   | 2        | 0.58%   |
| 5.8.6   | 2        | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 92       | 27.96%  |
| 5.6     | 36       | 10.94%  |
| 5.8     | 31       | 9.42%   |
| 5.9     | 29       | 8.81%   |
| 5.4     | 24       | 7.29%   |
| 5.7     | 23       | 6.99%   |
| 5.11    | 20       | 6.08%   |
| 5.13    | 17       | 5.17%   |
| 5.15    | 15       | 4.56%   |
| 5.14    | 14       | 4.26%   |
| 5.12    | 11       | 3.34%   |
| 5.5     | 7        | 2.13%   |
| 5.17    | 5        | 1.52%   |
| 4.19    | 3        | 0.91%   |
| 5.16    | 1        | 0.3%    |
| 4.9     | 1        | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 261      | 96.31%  |
| i686     | 7        | 2.58%   |
| ppc64le  | 1        | 0.37%   |
| armv7l   | 1        | 0.37%   |
| armv5tel | 1        | 0.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 103      | 35.52%  |
| KDE5          | 61       | 21.03%  |
| GNOME         | 47       | 16.21%  |
| XFCE          | 30       | 10.34%  |
| KDE           | 20       | 6.9%    |
| MATE          | 13       | 4.48%   |
| X-Cinnamon    | 3        | 1.03%   |
| sway          | 2        | 0.69%   |
| LXQt          | 2        | 0.69%   |
| Enlightenment | 2        | 0.69%   |
| DWM           | 2        | 0.69%   |
| XSession      | 1        | 0.34%   |
| openbox       | 1        | 0.34%   |
| LXDE          | 1        | 0.34%   |
| i3            | 1        | 0.34%   |
| awesome       | 1        | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 164      | 57.34%  |
| Unknown | 60       | 20.98%  |
| Tty     | 50       | 17.48%  |
| Wayland | 12       | 4.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 126      | 44.52%  |
| SDDM    | 71       | 25.09%  |
| LightDM | 39       | 13.78%  |
| GDM     | 28       | 9.89%   |
| SLiM    | 7        | 2.47%   |
| XDM     | 5        | 1.77%   |
| LXDM    | 5        | 1.77%   |
| TDM     | 2        | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| en_US          | 110      | 39.43%  |
| en_GB          | 22       | 7.89%   |
| Unknown        | 20       | 7.17%   |
| de_DE          | 19       | 6.81%   |
| ru_RU          | 15       | 5.38%   |
| C.UTF8         | 11       | 3.94%   |
| es_ES          | 10       | 3.58%   |
| C              | 10       | 3.58%   |
| en_CA          | 8        | 2.87%   |
| pl_PL          | 7        | 2.51%   |
| ru_RU.UTF8     | 5        | 1.79%   |
| fr_FR          | 5        | 1.79%   |
| sv_SE          | 4        | 1.43%   |
| pt_BR          | 3        | 1.08%   |
| nl_NL          | 3        | 1.08%   |
| fi_FI          | 3        | 1.08%   |
| ja_JP          | 2        | 0.72%   |
| en_US.UTF8     | 2        | 0.72%   |
| en_AU          | 2        | 0.72%   |
| ca_ES          | 2        | 0.72%   |
| uk_UA          | 1        | 0.36%   |
| ru_UA          | 1        | 0.36%   |
| pt_PT          | 1        | 0.36%   |
| it_IT          | 1        | 0.36%   |
| hu_HU          | 1        | 0.36%   |
| fr_FR.UTF8     | 1        | 0.36%   |
| et_EE          | 1        | 0.36%   |
| es_AR          | 1        | 0.36%   |
| en_NZ          | 1        | 0.36%   |
| en_IE          | 1        | 0.36%   |
| en_GB.iso88591 | 1        | 0.36%   |
| en_EN          | 1        | 0.36%   |
| en_DK          | 1        | 0.36%   |
| en_DE          | 1        | 0.36%   |
| el_GR          | 1        | 0.36%   |
| de_CH          | 1        | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 173      | 63.14%  |
| BIOS | 101      | 36.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 167      | 60.07%  |
| Btrfs    | 54       | 19.42%  |
| Xfs      | 16       | 5.76%   |
| Zfs      | 14       | 5.04%   |
| F2fs     | 14       | 5.04%   |
| Reiserfs | 7        | 2.52%   |
| XXX      | 2        | 0.72%   |
| Unknown  | 2        | 0.72%   |
| Jfs      | 1        | 0.36%   |
| Ext3     | 1        | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 224      | 81.75%  |
| MBR     | 37       | 13.5%   |
| Unknown | 13       | 4.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 166      | 57.84%  |
| Yes       | 121      | 42.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 170      | 61.15%  |
| Yes       | 108      | 38.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 101      | 37.27%  |
| MSI                 | 45       | 16.61%  |
| ASRock              | 40       | 14.76%  |
| Gigabyte Technology | 39       | 14.39%  |
| Hewlett-Packard     | 8        | 2.95%   |
| Unknown             | 6        | 2.21%   |
| Intel               | 5        | 1.85%   |
| Fujitsu             | 5        | 1.85%   |
| Dell                | 5        | 1.85%   |
| Tekram Technology   | 3        | 1.11%   |
| ASRockRack          | 3        | 1.11%   |
| Apple               | 2        | 0.74%   |
| Acer                | 2        | 0.74%   |
| Sun Microsystems    | 1        | 0.37%   |
| QDI                 | 1        | 0.37%   |
| Packard Bell        | 1        | 0.37%   |
| NZXT                | 1        | 0.37%   |
| Lenovo              | 1        | 0.37%   |
| BESSTAR Tech        | 1        | 0.37%   |
| Alienware           | 1        | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS PRIME X470-PRO            | 7        | 2.58%   |
| ASUS All Series                | 6        | 2.21%   |
| Unknown                        | 6        | 2.21%   |
| MSI MS-7A38                    | 4        | 1.48%   |
| ASUS ROG STRIX B550-F GAMING   | 4        | 1.48%   |
| ASRock B550M Steel Legend      | 4        | 1.48%   |
| Tekram P6B40-A4X-i440BX Rev    | 3        | 1.11%   |
| MSI MS-7C35                    | 3        | 1.11%   |
| MSI MS-7C02                    | 3        | 1.11%   |
| MSI MS-7B79                    | 3        | 1.11%   |
| ASUS Z170 PRO GAMING           | 3        | 1.11%   |
| ASUS TUF Gaming X570-PLUS      | 3        | 1.11%   |
| ASUS ROG CROSSHAIR VIII HERO   | 3        | 1.11%   |
| ASUS PRIME X570-PRO            | 3        | 1.11%   |
| ASUS PRIME X370-PRO            | 3        | 1.11%   |
| ASRock B450M-HDV R4.0          | 3        | 1.11%   |
| MSI MS-7C84                    | 2        | 0.74%   |
| MSI MS-7C37                    | 2        | 0.74%   |
| MSI MS-7C34                    | 2        | 0.74%   |
| MSI MS-7A34                    | 2        | 0.74%   |
| Gigabyte X570 AORUS XTREME     | 2        | 0.74%   |
| Gigabyte X570 AORUS ELITE      | 2        | 0.74%   |
| Gigabyte AB350-Gaming 3        | 2        | 0.74%   |
| Fujitsu ESPRIMO P7935          | 2        | 0.74%   |
| Fujitsu D3401-H1               | 2        | 0.74%   |
| ASUS TUF Gaming Z590-PLUS WIFI | 2        | 0.74%   |
| ASUS TUF Gaming B550-PLUS      | 2        | 0.74%   |
| ASUS SABERTOOTH 990FX R2.0     | 2        | 0.74%   |
| ASUS ROG STRIX X570-F GAMING   | 2        | 0.74%   |
| ASUS ROG STRIX B550-I GAMING   | 2        | 0.74%   |
| ASUS ROG CROSSHAIR VII HERO    | 2        | 0.74%   |
| ASUS PRIME X570-P              | 2        | 0.74%   |
| ASUS P6X58D-E                  | 2        | 0.74%   |
| ASUS P5LD2-Deluxe              | 2        | 0.74%   |
| ASUS M4A89GTD-PRO/USB3         | 2        | 0.74%   |
| ASRock Z390 Extreme4           | 2        | 0.74%   |
| ASRock X570 Steel Legend       | 2        | 0.74%   |
| ASRock X399 Taichi             | 2        | 0.74%   |
| ASRock B450 Pro4               | 2        | 0.74%   |
| ASRock AM1H-ITX                | 2        | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 26       | 9.59%   |
| ASUS ROG                | 24       | 8.86%   |
| ASUS TUF                | 11       | 4.06%   |
| Gigabyte X570           | 6        | 2.21%   |
| ASUS All                | 6        | 2.21%   |
| ASRock X570             | 6        | 2.21%   |
| Unknown                 | 6        | 2.21%   |
| ASRock X370             | 5        | 1.85%   |
| MSI MS-7A38             | 4        | 1.48%   |
| ASRock B550M            | 4        | 1.48%   |
| Tekram P6B40-A4X-i440BX | 3        | 1.11%   |
| MSI MS-7C35             | 3        | 1.11%   |
| MSI MS-7C02             | 3        | 1.11%   |
| MSI MS-7B79             | 3        | 1.11%   |
| Gigabyte B450           | 3        | 1.11%   |
| Gigabyte AB350-Gaming   | 3        | 1.11%   |
| Dell OptiPlex           | 3        | 1.11%   |
| ASUS Z170               | 3        | 1.11%   |
| ASRock B450M-HDV        | 3        | 1.11%   |
| MSI MS-7C84             | 2        | 0.74%   |
| MSI MS-7C37             | 2        | 0.74%   |
| MSI MS-7C34             | 2        | 0.74%   |
| MSI MS-7A34             | 2        | 0.74%   |
| Gigabyte Z390           | 2        | 0.74%   |
| Gigabyte B450M          | 2        | 0.74%   |
| Fujitsu ESPRIMO         | 2        | 0.74%   |
| Fujitsu D3401-H1        | 2        | 0.74%   |
| ASUS STRIX              | 2        | 0.74%   |
| ASUS SABERTOOTH         | 2        | 0.74%   |
| ASUS P6X58D-E           | 2        | 0.74%   |
| ASUS P5LD2-Deluxe       | 2        | 0.74%   |
| ASUS M4A89GTD-PRO       | 2        | 0.74%   |
| ASRock Z390             | 2        | 0.74%   |
| ASRock X399             | 2        | 0.74%   |
| ASRock B450             | 2        | 0.74%   |
| ASRock AM1H-ITX         | 2        | 0.74%   |
| Acer Aspire             | 2        | 0.74%   |
| Sun Microsystems Ultra  | 1        | 0.37%   |
| QDI P4I865A             | 1        | 0.37%   |
| Packard Bell IMEDIA     | 1        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 52       | 19.19%  |
| 2018    | 42       | 15.5%   |
| 2020    | 38       | 14.02%  |
| 2017    | 26       | 9.59%   |
| 2015    | 15       | 5.54%   |
| 2016    | 13       | 4.8%    |
| 2013    | 12       | 4.43%   |
| 2012    | 12       | 4.43%   |
| 2010    | 10       | 3.69%   |
| 2008    | 10       | 3.69%   |
| 2011    | 8        | 2.95%   |
| 2009    | 8        | 2.95%   |
| 2021    | 7        | 2.58%   |
| 2014    | 6        | 2.21%   |
| 2000    | 3        | 1.11%   |
| Unknown | 3        | 1.11%   |
| 2007    | 2        | 0.74%   |
| 2005    | 2        | 0.74%   |
| 2004    | 1        | 0.37%   |
| 2003    | 1        | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 271      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 269      | 99.26%  |
| Enabled  | 2        | 0.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 271      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 102      | 36.69%  |
| 16.01-24.0  | 68       | 24.46%  |
| 64.01-256.0 | 46       | 16.55%  |
| 8.01-16.0   | 23       | 8.27%   |
| 3.01-4.0    | 11       | 3.96%   |
| 24.01-32.0  | 11       | 3.96%   |
| 4.01-8.0    | 10       | 3.6%    |
| 0.51-1.0    | 4        | 1.44%   |
| 2.01-3.0    | 1        | 0.36%   |
| 1.01-2.0    | 1        | 0.36%   |
| 0.01-0.5    | 1        | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 76       | 23.9%   |
| 2.01-3.0    | 54       | 16.98%  |
| 1.01-2.0    | 48       | 15.09%  |
| 8.01-16.0   | 43       | 13.52%  |
| 3.01-4.0    | 37       | 11.64%  |
| 0.01-0.5    | 22       | 6.92%   |
| 16.01-24.0  | 15       | 4.72%   |
| 0.51-1.0    | 13       | 4.09%   |
| 32.01-64.0  | 6        | 1.89%   |
| 24.01-32.0  | 3        | 0.94%   |
| 64.01-256.0 | 1        | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 78       | 26.71%  |
| 3      | 66       | 22.6%   |
| 4      | 47       | 16.1%   |
| 1      | 45       | 15.41%  |
| 5      | 30       | 10.27%  |
| 6      | 10       | 3.42%   |
| 7      | 7        | 2.4%    |
| 9      | 2        | 0.68%   |
| 8      | 2        | 0.68%   |
| 18     | 1        | 0.34%   |
| 17     | 1        | 0.34%   |
| 13     | 1        | 0.34%   |
| 11     | 1        | 0.34%   |
| 0      | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 192      | 68.82%  |
| Yes       | 87       | 31.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 266      | 98.15%  |
| No        | 5        | 1.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 172      | 62.32%  |
| Yes       | 104      | 37.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 168      | 61.31%  |
| Yes       | 106      | 38.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 52       | 18.98%  |
| Germany     | 43       | 15.69%  |
| Russia      | 24       | 8.76%   |
| UK          | 19       | 6.93%   |
| Spain       | 14       | 5.11%   |
| Poland      | 13       | 4.74%   |
| Finland     | 12       | 4.38%   |
| Canada      | 12       | 4.38%   |
| France      | 10       | 3.65%   |
| Ukraine     | 8        | 2.92%   |
| Sweden      | 8        | 2.92%   |
| Netherlands | 6        | 2.19%   |
| Greece      | 4        | 1.46%   |
| Switzerland | 3        | 1.09%   |
| Norway      | 3        | 1.09%   |
| Japan       | 3        | 1.09%   |
| China       | 3        | 1.09%   |
| Brazil      | 3        | 1.09%   |
| Australia   | 3        | 1.09%   |
| Slovakia    | 2        | 0.73%   |
| Mexico      | 2        | 0.73%   |
| Jamaica     | 2        | 0.73%   |
| Italy       | 2        | 0.73%   |
| Hong Kong   | 2        | 0.73%   |
| Czechia     | 2        | 0.73%   |
| Belarus     | 2        | 0.73%   |
| Austria     | 2        | 0.73%   |
| Argentina   | 2        | 0.73%   |
| Tunisia     | 1        | 0.36%   |
| Slovenia    | 1        | 0.36%   |
| Romania     | 1        | 0.36%   |
| Réunion    | 1        | 0.36%   |
| Philippines | 1        | 0.36%   |
| New Zealand | 1        | 0.36%   |
| Ireland     | 1        | 0.36%   |
| Hungary     | 1        | 0.36%   |
| Estonia     | 1        | 0.36%   |
| El Salvador | 1        | 0.36%   |
| Denmark     | 1        | 0.36%   |
| Bulgaria    | 1        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Warsaw               | 5        | 1.75%   |
| Vladivostok          | 5        | 1.75%   |
| Ottawa               | 5        | 1.75%   |
| St Petersburg        | 4        | 1.4%    |
| Oulu                 | 4        | 1.4%    |
| Moscow               | 4        | 1.4%    |
| Kyiv                 | 4        | 1.4%    |
| Helsinki             | 4        | 1.4%    |
| Dienheim             | 4        | 1.4%    |
| Berlin               | 4        | 1.4%    |
| Athens               | 4        | 1.4%    |
| Zurich               | 3        | 1.05%   |
| Swansea              | 3        | 1.05%   |
| Sao Paulo            | 3        | 1.05%   |
| Munich               | 3        | 1.05%   |
| Falkenstein          | 3        | 1.05%   |
| Combrit              | 3        | 1.05%   |
| Cieszyn              | 3        | 1.05%   |
| Yuen Long            | 2        | 0.7%    |
| Yekaterinburg        | 2        | 0.7%    |
| Vechelde             | 2        | 0.7%    |
| Vancouver            | 2        | 0.7%    |
| Vallejo              | 2        | 0.7%    |
| Tampere              | 2        | 0.7%    |
| Suffolk              | 2        | 0.7%    |
| Rosario              | 2        | 0.7%    |
| Nuremberg            | 2        | 0.7%    |
| Novosibirsk          | 2        | 0.7%    |
| Marburg              | 2        | 0.7%    |
| Los Angeles          | 2        | 0.7%    |
| London               | 2        | 0.7%    |
| Kingston             | 2        | 0.7%    |
| Karlstad             | 2        | 0.7%    |
| Hamburg              | 2        | 0.7%    |
| Geleshan             | 2        | 0.7%    |
| Freiburg im Breisgau | 2        | 0.7%    |
| Frankfurt am Main    | 2        | 0.7%    |
| Ferrol               | 2        | 0.7%    |
| Baton Rouge          | 2        | 0.7%    |
| Barcelona            | 2        | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 125      | 257    | 20.94%  |
| Samsung Electronics | 121      | 257    | 20.27%  |
| Seagate             | 101      | 211    | 16.92%  |
| Kingston            | 42       | 56     | 7.04%   |
| Intel               | 26       | 37     | 4.36%   |
| Toshiba             | 23       | 34     | 3.85%   |
| Hitachi             | 21       | 52     | 3.52%   |
| Crucial             | 19       | 27     | 3.18%   |
| SanDisk             | 18       | 26     | 3.02%   |
| A-DATA Technology   | 16       | 23     | 2.68%   |
| Phison              | 10       | 16     | 1.68%   |
| Corsair             | 10       | 15     | 1.68%   |
| HGST                | 8        | 17     | 1.34%   |
| Unknown             | 5        | 5      | 0.84%   |
| OCZ                 | 5        | 5      | 0.84%   |
| GOODRAM             | 5        | 10     | 0.84%   |
| Plextor             | 4        | 4      | 0.67%   |
| IBM                 | 4        | 5      | 0.67%   |
| Mushkin             | 3        | 3      | 0.5%    |
| Gigabyte Technology | 3        | 4      | 0.5%    |
| XPG                 | 2        | 2      | 0.34%   |
| Team                | 2        | 5      | 0.34%   |
| SPCC                | 2        | 2      | 0.34%   |
| Patriot             | 2        | 3      | 0.34%   |
| MDT                 | 2        | 2      | 0.34%   |
| Intenso             | 2        | 3      | 0.34%   |
| Apacer              | 2        | 3      | 0.34%   |
| Transcend           | 1        | 1      | 0.17%   |
| SK hynix            | 1        | 2      | 0.17%   |
| Silicon Motion      | 1        | 4      | 0.17%   |
| PNY                 | 1        | 1      | 0.17%   |
| Micron Technology   | 1        | 2      | 0.17%   |
| LITEONIT            | 1        | 1      | 0.17%   |
| Leven               | 1        | 2      | 0.17%   |
| KIOXIA              | 1        | 2      | 0.17%   |
| KingDian            | 1        | 1      | 0.17%   |
| Kingchuxing         | 1        | 2      | 0.17%   |
| EMTEC               | 1        | 3      | 0.17%   |
| China               | 1        | 1      | 0.17%   |
| AMD-RAID            | 1        | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB        | 11       | 1.46%   |
| Samsung SSD 970 EVO 500GB        | 9        | 1.2%    |
| Samsung SSD 860 EVO 1TB          | 9        | 1.2%    |
| Samsung SSD 850 EVO 250GB        | 9        | 1.2%    |
| Samsung SSD 840 EVO 120GB        | 9        | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB   | 8        | 1.06%   |
| Samsung SSD 860 EVO 250GB        | 8        | 1.06%   |
| WDC WD40EFRX-68WT0N0 4TB         | 7        | 0.93%   |
| WDC WD30EFRX-68EUZN0 3TB         | 7        | 0.93%   |
| WDC WD40EFRX-68N32N0 4TB         | 6        | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB         | 6        | 0.8%    |
| Seagate ST2000DM001-1ER164 2TB   | 6        | 0.8%    |
| Samsung SSD 970 EVO Plus 500GB   | 6        | 0.8%    |
| Samsung SSD 970 EVO 250GB        | 6        | 0.8%    |
| Samsung SSD 970 EVO 1TB          | 6        | 0.8%    |
| Samsung SSD 960 EVO 500GB        | 6        | 0.8%    |
| Samsung SSD 860 EVO 500GB        | 6        | 0.8%    |
| Kingston SA400S37480G 480GB SSD  | 6        | 0.8%    |
| Kingston SA400S37240G 240GB SSD  | 6        | 0.8%    |
| WDC WD40EZRZ-00GXCB0 4TB         | 5        | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB         | 5        | 0.66%   |
| Seagate ST4000DM004-2CV104 4TB   | 5        | 0.66%   |
| Seagate ST3500418AS 500GB        | 5        | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB   | 5        | 0.66%   |
| Samsung SSD 970 EVO Plus 1TB     | 5        | 0.66%   |
| Samsung SSD 840 PRO Series 256GB | 5        | 0.66%   |
| Samsung SSD 840 EVO 250GB        | 5        | 0.66%   |
| Kingston SA400S37120G 120GB SSD  | 5        | 0.66%   |
| Kingston SA2000M81000G 1TB       | 5        | 0.66%   |
| WDC WD2003FZEX-00Z4SA0 2TB       | 4        | 0.53%   |
| WDC WD10EZEX-08M2NA0 1TB         | 4        | 0.53%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 4        | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB   | 4        | 0.53%   |
| Seagate ST2000DM006-2DM164 2TB   | 4        | 0.53%   |
| Samsung SSD 980 PRO 1TB          | 4        | 0.53%   |
| Samsung SSD 850 EVO 1TB          | 4        | 0.53%   |
| Phison Sabrent Rocket 4.0 1TB    | 4        | 0.53%   |
| Kingston SUV400S37120G 120GB SSD | 4        | 0.53%   |
| Intel SSDPEKNW512G8 512GB        | 4        | 0.53%   |
| Crucial CT275MX300SSD1 275GB     | 4        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 112      | 224    | 40%     |
| Seagate             | 98       | 208    | 35%     |
| Toshiba             | 21       | 32     | 7.5%    |
| Hitachi             | 21       | 52     | 7.5%    |
| Samsung Electronics | 11       | 16     | 3.93%   |
| HGST                | 8        | 17     | 2.86%   |
| IBM                 | 4        | 5      | 1.43%   |
| Unknown             | 3        | 3      | 1.07%   |
| MDT                 | 2        | 2      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 77       | 131    | 37.56%  |
| Kingston            | 34       | 42     | 16.59%  |
| Crucial             | 18       | 26     | 8.78%   |
| SanDisk             | 15       | 23     | 7.32%   |
| WDC                 | 9        | 11     | 4.39%   |
| Intel               | 9        | 10     | 4.39%   |
| OCZ                 | 5        | 5      | 2.44%   |
| GOODRAM             | 5        | 10     | 2.44%   |
| A-DATA Technology   | 5        | 7      | 2.44%   |
| Plextor             | 4        | 4      | 1.95%   |
| Corsair             | 4        | 5      | 1.95%   |
| Mushkin             | 2        | 2      | 0.98%   |
| Intenso             | 2        | 3      | 0.98%   |
| Unknown             | 1        | 1      | 0.49%   |
| Transcend           | 1        | 1      | 0.49%   |
| Toshiba             | 1        | 1      | 0.49%   |
| Team                | 1        | 2      | 0.49%   |
| SPCC                | 1        | 1      | 0.49%   |
| PNY                 | 1        | 1      | 0.49%   |
| Patriot             | 1        | 2      | 0.49%   |
| Micron Technology   | 1        | 2      | 0.49%   |
| LITEONIT            | 1        | 1      | 0.49%   |
| Leven               | 1        | 2      | 0.49%   |
| KingDian            | 1        | 1      | 0.49%   |
| EMTEC               | 1        | 3      | 0.49%   |
| China               | 1        | 1      | 0.49%   |
| Apacer              | 1        | 2      | 0.49%   |
| AMD-RAID            | 1        | 2      | 0.49%   |
| AMD                 | 1        | 1      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 200      | 559    | 39.53%  |
| SSD     | 158      | 303    | 31.23%  |
| NVMe    | 146      | 245    | 28.85%  |
| MMC     | 1        | 1      | 0.2%    |
| Unknown | 1        | 1      | 0.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 237      | 852    | 60.31%  |
| NVMe | 146      | 245    | 37.15%  |
| SAS  | 9        | 11     | 2.29%   |
| MMC  | 1        | 1      | 0.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 166      | 350    | 40.1%   |
| 0.51-1.0   | 107      | 180    | 25.85%  |
| 1.01-2.0   | 61       | 135    | 14.73%  |
| 3.01-4.0   | 36       | 75     | 8.7%    |
| 2.01-3.0   | 24       | 45     | 5.8%    |
| 4.01-10.0  | 16       | 69     | 3.86%   |
| 10.01-20.0 | 3        | 7      | 0.72%   |
| 20.01-50.0 | 1        | 1      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 57       | 19.66%  |
| 501-1000       | 51       | 17.59%  |
| 1001-2000      | 44       | 15.17%  |
| 251-500        | 41       | 14.14%  |
| 101-250        | 34       | 11.72%  |
| 2001-3000      | 25       | 8.62%   |
| Unknown        | 13       | 4.48%   |
| 1-20           | 11       | 3.79%   |
| 51-100         | 8        | 2.76%   |
| 21-50          | 6        | 2.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 41       | 13.4%   |
| 1001-2000      | 40       | 13.07%  |
| 251-500        | 39       | 12.75%  |
| 101-250        | 39       | 12.75%  |
| 21-50          | 35       | 11.44%  |
| 1-20           | 33       | 10.78%  |
| More than 3000 | 29       | 9.48%   |
| 51-100         | 22       | 7.19%   |
| 2001-3000      | 15       | 4.9%    |
| Unknown        | 13       | 4.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                    | 4        | 5      | 4.17%   |
| WDC WD40EFRX-68WT0N0 4TB                     | 3        | 13     | 3.13%   |
| Seagate ST8000AS0002-1NA17Z 8TB              | 3        | 15     | 3.13%   |
| Seagate ST500DM002-1BC142 500GB              | 3        | 3      | 3.13%   |
| IBM DJSA-220 12GB                            | 3        | 3      | 3.13%   |
| Seagate ST31000340NS 1TB                     | 2        | 3      | 2.08%   |
| Seagate ST2000DL003-9VT166 2TB               | 2        | 3      | 2.08%   |
| Seagate ST1000NM0011 1TB                     | 2        | 6      | 2.08%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 2        | 4      | 2.08%   |
| MDT MD2000KS-00MJB0 200GB                    | 2        | 2      | 2.08%   |
| Hitachi HDS722020ALA330 2TB                  | 2        | 14     | 2.08%   |
| WDC WD80EFZX-68UW8N0 8TB                     | 1        | 2      | 1.04%   |
| WDC WD6400AAKS-65A7B2 640GB                  | 1        | 1      | 1.04%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 1        | 1      | 1.04%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 6      | 1.04%   |
| WDC WD5000AAVS-22G9B1 500GB                  | 1        | 1      | 1.04%   |
| WDC WD5000AAKX-003CA0 500GB                  | 1        | 1      | 1.04%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1        | 1      | 1.04%   |
| WDC WD4004FZWX-00GBGB0 4TB                   | 1        | 1      | 1.04%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1        | 1      | 1.04%   |
| WDC WD30EFRX-68AX9N0 3TB                     | 1        | 1      | 1.04%   |
| WDC WD2502ABYS-02B7A0 256GB                  | 1        | 1      | 1.04%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1        | 1      | 1.04%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1        | 2      | 1.04%   |
| WDC WD2003FZEX-00Z4SA0 2TB                   | 1        | 1      | 1.04%   |
| WDC WD2002FAEX-007BA0 2TB                    | 1        | 1      | 1.04%   |
| WDC WD1600AAJS-75B4A0 160GB                  | 1        | 1      | 1.04%   |
| WDC WD10EZRX-00A8LB0 1TB                     | 1        | 1      | 1.04%   |
| WDC WD10EACS-22D6B0 1TB                      | 1        | 1      | 1.04%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1        | 2      | 1.04%   |
| Toshiba MQ04ABF100 1TB                       | 1        | 1      | 1.04%   |
| Toshiba HDWD130 3TB                          | 1        | 1      | 1.04%   |
| Toshiba HDWD105 500GB                        | 1        | 2      | 1.04%   |
| Toshiba DT01ACA300 3TB                       | 1        | 1      | 1.04%   |
| Toshiba DT01ABA100V 1TB                      | 1        | 1      | 1.04%   |
| Seagate ST8000VX0022-2EJ112 8TB              | 1        | 2      | 1.04%   |
| Seagate ST500LT012-1DG142 500GB              | 1        | 1      | 1.04%   |
| Seagate ST4000DM004-2CV104 4TB               | 1        | 1      | 1.04%   |
| Seagate ST4000DM000-1F2168 4TB               | 1        | 1      | 1.04%   |
| Seagate ST3808110AS 80GB                     | 1        | 1      | 1.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 53     | 32.58%  |
| WDC                 | 20       | 40     | 22.47%  |
| Samsung Electronics | 10       | 15     | 11.24%  |
| Hitachi             | 6        | 18     | 6.74%   |
| Toshiba             | 5        | 6      | 5.62%   |
| IBM                 | 3        | 3      | 3.37%   |
| Plextor             | 2        | 2      | 2.25%   |
| MDT                 | 2        | 2      | 2.25%   |
| Kingston            | 2        | 2      | 2.25%   |
| HGST                | 2        | 3      | 2.25%   |
| Crucial             | 2        | 2      | 2.25%   |
| SanDisk             | 1        | 1      | 1.12%   |
| OCZ                 | 1        | 1      | 1.12%   |
| Mushkin             | 1        | 1      | 1.12%   |
| Intel               | 1        | 1      | 1.12%   |
| EMTEC               | 1        | 2      | 1.12%   |
| Corsair             | 1        | 2      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 53     | 42.65%  |
| WDC                 | 20       | 40     | 29.41%  |
| Hitachi             | 6        | 18     | 8.82%   |
| Toshiba             | 5        | 6      | 7.35%   |
| IBM                 | 3        | 3      | 4.41%   |
| MDT                 | 2        | 2      | 2.94%   |
| HGST                | 2        | 3      | 2.94%   |
| Samsung Electronics | 1        | 2      | 1.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 62       | 127    | 74.7%   |
| SSD  | 16       | 20     | 19.28%  |
| NVMe | 5        | 7      | 6.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB                     | 1        | 1      | 33.33%  |
| Seagate ST31500341AS 1TB                         | 1        | 1      | 33.33%  |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 33.33%  |
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 254      | 891    | 70.17%  |
| Malfunc  | 81       | 154    | 22.38%  |
| Detected | 24       | 60     | 6.63%   |
| Failed   | 3        | 4      | 0.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| AMD                           | 146      | 31.06%  |
| Intel                         | 121      | 25.74%  |
| Samsung Electronics           | 67       | 14.26%  |
| ASMedia Technology            | 27       | 5.74%   |
| Phison Electronics            | 22       | 4.68%   |
| SanDisk                       | 16       | 3.4%    |
| ADATA Technology              | 13       | 2.77%   |
| Marvell Technology Group      | 11       | 2.34%   |
| Kingston Technology Company   | 10       | 2.13%   |
| JMicron Technology            | 6        | 1.28%   |
| Nvidia                        | 4        | 0.85%   |
| LSI Logic / Symbios Logic     | 4        | 0.85%   |
| Silicon Motion                | 3        | 0.64%   |
| Silicon Image                 | 3        | 0.64%   |
| Realtek Semiconductor         | 3        | 0.64%   |
| Adaptec                       | 3        | 0.64%   |
| Toshiba America Info Systems  | 2        | 0.43%   |
| Seagate Technology            | 2        | 0.43%   |
| Broadcom / LSI                | 2        | 0.43%   |
| VIA Technologies              | 1        | 0.21%   |
| SK hynix                      | 1        | 0.21%   |
| Micron/Crucial Technology     | 1        | 0.21%   |
| Lite-On IT Corp. / Plextor    | 1        | 0.21%   |
| Integrated Technology Express | 1        | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 110      | 18.93%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 44       | 7.57%   |
| AMD 400 Series Chipset SATA Controller                                         | 44       | 7.57%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 27       | 4.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 22       | 3.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 16       | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 13       | 2.24%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 13       | 2.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12       | 2.07%   |
| AMD X370 Series Chipset SATA Controller                                        | 12       | 2.07%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 11       | 1.89%   |
| Phison E16 PCIe4 NVMe Controller                                               | 10       | 1.72%   |
| Intel SATA Controller [RAID mode]                                              | 10       | 1.72%   |
| Intel SSD 660P Series                                                          | 9        | 1.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9        | 1.55%   |
| AMD 300 Series Chipset SATA Controller                                         | 9        | 1.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8        | 1.38%   |
| Phison E12 NVMe Controller                                                     | 7        | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7        | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7        | 1.2%    |
| Kingston Company A2000 NVMe SSD                                                | 6        | 1.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5        | 0.86%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 5        | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5        | 0.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5        | 0.86%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 4        | 0.69%   |
| Intel Optane SSD 900P Series                                                   | 4        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4        | 0.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 0.52%   |
| Samsung NVMe SSD Controller 980                                                | 3        | 0.52%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3        | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 0.52%   |
| JMicron JMB368 IDE controller                                                  | 3        | 0.52%   |
| Intel SSD 600P Series                                                          | 3        | 0.52%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 3        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 243      | 54.24%  |
| NVMe | 146      | 32.59%  |
| IDE  | 31       | 6.92%   |
| RAID | 20       | 4.46%   |
| SAS  | 4        | 0.89%   |
| SCSI | 4        | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 152      | 56.09%  |
| Intel                    | 116      | 42.8%   |
| PowerNV C1P9S01 REV 1.01 | 1        | 0.37%   |
| Marvell Semiconductor    | 1        | 0.37%   |
| ARM                      | 1        | 0.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 15       | 5.47%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 13       | 4.74%   |
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 4.01%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 10       | 3.65%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 10       | 3.65%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 8        | 2.92%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 2.92%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 6        | 2.19%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 2.19%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 5        | 1.82%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 1.82%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.82%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 1.82%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 1.46%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 4        | 1.46%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 1.46%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 1.46%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 4        | 1.46%   |
| Intel Pentium III (Katmai)                  | 3        | 1.09%   |
| Intel Pentium 4 CPU 3.20GHz                 | 3        | 1.09%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.09%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.09%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.09%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 3        | 1.09%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 1.09%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 2        | 0.73%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 2        | 0.73%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.73%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.73%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 0.73%   |
| Intel Core i7 CPU X 980 @ 3.33GHz           | 2        | 0.73%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 0.73%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.73%   |
| Intel Core i5-10600KF CPU @ 4.10GHz         | 2        | 0.73%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.73%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 2        | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 0.73%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 2        | 0.73%   |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz    | 2        | 0.73%   |
| AMD Sempron 3850 APU with Radeon R3         | 2        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 7            | 52       | 19.12%  |
| AMD Ryzen 5            | 42       | 15.44%  |
| Intel Core i7          | 37       | 13.6%   |
| AMD Ryzen 9            | 25       | 9.19%   |
| Intel Core i5          | 23       | 8.46%   |
| Intel Xeon             | 14       | 5.15%   |
| AMD FX                 | 10       | 3.68%   |
| Intel Core i9          | 7        | 2.57%   |
| Intel Core 2 Quad      | 7        | 2.57%   |
| Other                  | 6        | 2.21%   |
| Intel Core i3          | 5        | 1.84%   |
| AMD Ryzen 3            | 5        | 1.84%   |
| Intel Pentium 4        | 4        | 1.47%   |
| Intel Pentium          | 4        | 1.47%   |
| Intel Core 2 Duo       | 4        | 1.47%   |
| AMD Ryzen Threadripper | 4        | 1.47%   |
| AMD Phenom II X4       | 4        | 1.47%   |
| Intel Pentium III      | 3        | 1.1%    |
| Intel Celeron          | 2        | 0.74%   |
| AMD Sempron            | 2        | 0.74%   |
| AMD Ryzen 7 PRO        | 2        | 0.74%   |
| AMD Phenom II X6       | 2        | 0.74%   |
| AMD Athlon 64 X2       | 2        | 0.74%   |
| AMD A10                | 2        | 0.74%   |
| Intel Core 2           | 1        | 0.37%   |
| Intel Atom             | 1        | 0.37%   |
| ARM Allwinner          | 1        | 0.37%   |
| AMD Ryzen 5 PRO        | 1        | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 78       | 28.68%  |
| 8      | 67       | 24.63%  |
| 6      | 61       | 22.43%  |
| 2      | 20       | 7.35%   |
| 16     | 16       | 5.88%   |
| 12     | 14       | 5.15%   |
| 1      | 8        | 2.94%   |
| 10     | 2        | 0.74%   |
| 3      | 2        | 0.74%   |
| 64     | 1        | 0.37%   |
| 24     | 1        | 0.37%   |
| 18     | 1        | 0.37%   |
| 14     | 1        | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 266      | 98.15%  |
| 2      | 5        | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 203      | 74.63%  |
| 1      | 68       | 25%     |
| 4      | 1        | 0.37%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 263      | 97.05%  |
| 32-bit         | 5        | 1.85%   |
| Unknown        | 3        | 1.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 14.13%  |
| 0x08701021 | 31       | 10.95%  |
| 0x0800820d | 26       | 9.19%   |
| 0x08701013 | 21       | 7.42%   |
| 0x506e3    | 15       | 5.3%    |
| 0x0a201009 | 14       | 4.95%   |
| 0x08001138 | 11       | 3.89%   |
| 0x906e9    | 10       | 3.53%   |
| 0x306c3    | 10       | 3.53%   |
| 0xa0655    | 8        | 2.83%   |
| 0x0a201016 | 8        | 2.83%   |
| 0x306a9    | 7        | 2.47%   |
| 0x1067a    | 7        | 2.47%   |
| 0x906ea    | 5        | 1.77%   |
| 0x906ec    | 4        | 1.41%   |
| 0x206c2    | 4        | 1.41%   |
| 0xa0671    | 3        | 1.06%   |
| 0x673      | 3        | 1.06%   |
| 0x206a7    | 3        | 1.06%   |
| 0x106a5    | 3        | 1.06%   |
| 0x0810100b | 3        | 1.06%   |
| 0xf43      | 2        | 0.71%   |
| 0x906ed    | 2        | 0.71%   |
| 0x306e4    | 2        | 0.71%   |
| 0x08600106 | 2        | 0.71%   |
| 0x08301039 | 2        | 0.71%   |
| 0x08101013 | 2        | 0.71%   |
| 0x08008206 | 2        | 0.71%   |
| 0x08001129 | 2        | 0.71%   |
| 0x0700010f | 2        | 0.71%   |
| 0x06000852 | 2        | 0.71%   |
| 0x06000822 | 2        | 0.71%   |
| 0x010000c8 | 2        | 0.71%   |
| 0xf29      | 1        | 0.35%   |
| 0xa0653    | 1        | 0.35%   |
| 0x806ec    | 1        | 0.35%   |
| 0x6fd      | 1        | 0.35%   |
| 0x6fb      | 1        | 0.35%   |
| 0x6f6      | 1        | 0.35%   |
| 0x506c9    | 1        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 61       | 22.26%  |
| Zen+        | 31       | 11.31%  |
| KabyLake    | 25       | 9.12%   |
| Zen 3       | 21       | 7.66%   |
| Zen         | 20       | 7.3%    |
| Skylake     | 17       | 6.2%    |
| Haswell     | 11       | 4.01%   |
| Piledriver  | 9        | 3.28%   |
| Penryn      | 9        | 3.28%   |
| IvyBridge   | 9        | 3.28%   |
| CometLake   | 9        | 3.28%   |
| Nehalem     | 7        | 2.55%   |
| Unknown     | 7        | 2.55%   |
| K10         | 6        | 2.19%   |
| SandyBridge | 5        | 1.82%   |
| Westmere    | 4        | 1.46%   |
| NetBurst    | 4        | 1.46%   |
| Core        | 4        | 1.46%   |
| P6          | 3        | 1.09%   |
| K8 Hammer   | 2        | 0.73%   |
| Jaguar      | 2        | 0.73%   |
| Bulldozer   | 2        | 0.73%   |
| Broadwell   | 2        | 0.73%   |
| Silvermont  | 1        | 0.36%   |
| Goldmont    | 1        | 0.36%   |
| Excavator   | 1        | 0.36%   |
| Bonnell     | 1        | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 132      | 45.99%  |
| Nvidia                     | 113      | 39.37%  |
| Intel                      | 36       | 12.54%  |
| ASPEED Technology          | 4        | 1.39%   |
| Matrox Electronics Systems | 2        | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 38       | 12.62%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 20       | 6.64%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 14       | 4.65%   |
| Intel HD Graphics 530                                                       | 9        | 2.99%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 1.99%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6        | 1.99%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 1.99%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 1.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.66%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 1.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.33%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.33%   |
| ASPEED Technology ASPEED Graphics Family                                    | 4        | 1.33%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 1.33%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 1%      |
| Nvidia GT200GL [Quadro FX 4800]                                             | 3        | 1%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1%      |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1%      |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 1%      |
| Intel HD Graphics 630                                                       | 3        | 1%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1%      |
| AMD RS880 [Radeon HD 4290]                                                  | 3        | 1%      |
| AMD Renoir                                                                  | 3        | 1%      |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 1%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.66%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.66%   |
| Nvidia NV5 [Riva TNT2 Model 64 / Model 64 Pro]                              | 2        | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.66%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 2        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.66%   |
| Nvidia GK107 [GeForce GT 740]                                               | 2        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x AMD                  | 117      | 42.7%   |
| 1 x Nvidia               | 99       | 36.13%  |
| 1 x Intel                | 28       | 10.22%  |
| AMD + Nvidia             | 6        | 2.19%   |
| Other                    | 5        | 1.82%   |
| 2 x AMD                  | 5        | 1.82%   |
| 2 x Nvidia               | 3        | 1.09%   |
| Intel + Nvidia           | 3        | 1.09%   |
| 1 x ASPEED               | 3        | 1.09%   |
| Nvidia + Matrox          | 1        | 0.36%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.36%   |
| Intel + AMD              | 1        | 0.36%   |
| AMD + Matrox             | 1        | 0.36%   |
| AMD + ASPEED             | 1        | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 172      | 62.55%  |
| Proprietary | 84       | 30.55%  |
| Unknown     | 19       | 6.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 76       | 26.57%  |
| 7.01-8.0   | 73       | 25.52%  |
| 1.01-2.0   | 32       | 11.19%  |
| 3.01-4.0   | 30       | 10.49%  |
| 0.01-0.5   | 24       | 8.39%   |
| 5.01-6.0   | 15       | 5.24%   |
| 0.51-1.0   | 14       | 4.9%    |
| 8.01-16.0  | 12       | 4.2%    |
| 2.01-3.0   | 7        | 2.45%   |
| 16.01-24.0 | 3        | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 40       | 12.74%  |
| Dell                 | 39       | 12.42%  |
| Goldstar             | 38       | 12.1%   |
| BenQ                 | 21       | 6.69%   |
| AOC                  | 18       | 5.73%   |
| Ancor Communications | 18       | 5.73%   |
| Iiyama               | 17       | 5.41%   |
| Hewlett-Packard      | 17       | 5.41%   |
| Acer                 | 12       | 3.82%   |
| Philips              | 11       | 3.5%    |
| ViewSonic            | 10       | 3.18%   |
| Lenovo               | 7        | 2.23%   |
| ASUSTek Computer     | 7        | 2.23%   |
| Fujitsu Siemens      | 6        | 1.91%   |
| MSI                  | 5        | 1.59%   |
| Idek Iiyama          | 5        | 1.59%   |
| Eizo                 | 5        | 1.59%   |
| Unknown              | 3        | 0.96%   |
| LG Electronics       | 3        | 0.96%   |
| Envision Peripherals | 3        | 0.96%   |
| NEC Computers        | 2        | 0.64%   |
| Gigabyte Technology  | 2        | 0.64%   |
| AUS                  | 2        | 0.64%   |
| Apple                | 2        | 0.64%   |
| Yamaha               | 1        | 0.32%   |
| Vizio                | 1        | 0.32%   |
| Vestel Elektronik    | 1        | 0.32%   |
| Sunplus              | 1        | 0.32%   |
| Sony                 | 1        | 0.32%   |
| RTK                  | 1        | 0.32%   |
| PNP                  | 1        | 0.32%   |
| PKB                  | 1        | 0.32%   |
| Panasonic            | 1        | 0.32%   |
| Packard Bell         | 1        | 0.32%   |
| Lenovo Group Limited | 1        | 0.32%   |
| KTC                  | 1        | 0.32%   |
| Impression           | 1        | 0.32%   |
| HVR                  | 1        | 0.32%   |
| HJW                  | 1        | 0.32%   |
| HannStar Display     | 1        | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                  | 4        | 1.17%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                  | 4        | 1.17%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 4        | 1.17%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 4        | 1.17%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 4        | 1.17%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch       | 4        | 1.17%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 4        | 1.17%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 3        | 0.87%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 3        | 0.87%   |
| Envision Peripherals LCD2361 ENV2361 1920x1080 521x293mm 23.5-inch     | 3        | 0.87%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                     | 3        | 0.87%   |
| BenQ LCD BNQ801E 3840x2160 596x335mm 26.9-inch                         | 3        | 0.87%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 2        | 0.58%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 2        | 0.58%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 2        | 0.58%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 2        | 0.58%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 2        | 0.58%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 2        | 0.58%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 2        | 0.58%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch               | 2        | 0.58%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                 | 2        | 0.58%   |
| MSI MAG274QRF MSI3CA8 2560x1440 597x336mm 27.0-inch                    | 2        | 0.58%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                   | 2        | 0.58%   |
| Idek Iiyama LCD Monitor PLE2607WS                                      | 2        | 0.58%   |
| Hewlett-Packard LA1951 HWP285B 1280x1024 380x300mm 19.1-inch           | 2        | 0.58%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 0.58%   |
| Goldstar 27MB85Z GSM5A72 2560x1440 597x336mm 27.0-inch                 | 2        | 0.58%   |
| Fujitsu Siemens P24W-5 ECO FUS06A7 1920x1200 518x324mm 24.1-inch       | 2        | 0.58%   |
| Dell U2720Q DEL41B3 3840x2160 597x336mm 27.0-inch                      | 2        | 0.58%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                      | 2        | 0.58%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 2        | 0.58%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 2        | 0.58%   |
| AOC 2473W1M AOC2473 1920x1080 527x296mm 23.8-inch                      | 2        | 0.58%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2        | 0.58%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch       | 2        | 0.58%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 2        | 0.58%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.58%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch  | 2        | 0.58%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch  | 2        | 0.58%   |
| Yamaha HTR-6064 YMH3169 1920x540                                       | 1        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 121      | 39.03%  |
| 2560x1440 (QHD)    | 42       | 13.55%  |
| 3840x2160 (4K)     | 39       | 12.58%  |
| 1920x1200 (WUXGA)  | 20       | 6.45%   |
| 3440x1440          | 17       | 5.48%   |
| 1280x1024 (SXGA)   | 13       | 4.19%   |
| 1680x1050 (WSXGA+) | 9        | 2.9%    |
| 3840x1080          | 8        | 2.58%   |
| Unknown            | 8        | 2.58%   |
| 2560x1080          | 7        | 2.26%   |
| 1600x900 (HD+)     | 6        | 1.94%   |
| 1440x900 (WXGA+)   | 3        | 0.97%   |
| 3840x1200          | 2        | 0.65%   |
| 1600x1200          | 2        | 0.65%   |
| 1366x768 (WXGA)    | 2        | 0.65%   |
| 1280x960           | 2        | 0.65%   |
| 6720x2160          | 1        | 0.32%   |
| 4880x1080          | 1        | 0.32%   |
| 3926x1440          | 1        | 0.32%   |
| 3600x1080          | 1        | 0.32%   |
| 2560x1600          | 1        | 0.32%   |
| 2160x1200          | 1        | 0.32%   |
| 2048x1152          | 1        | 0.32%   |
| 1920x540           | 1        | 0.32%   |
| 1400x1050          | 1        | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 61       | 19.68%  |
| 24      | 58       | 18.71%  |
| 23      | 48       | 15.48%  |
| Unknown | 33       | 10.65%  |
| 21      | 24       | 7.74%   |
| 34      | 18       | 5.81%   |
| 19      | 13       | 4.19%   |
| 31      | 7        | 2.26%   |
| 20      | 7        | 2.26%   |
| 17      | 6        | 1.94%   |
| 48      | 5        | 1.61%   |
| 25      | 5        | 1.61%   |
| 22      | 5        | 1.61%   |
| 32      | 4        | 1.29%   |
| 84      | 3        | 0.97%   |
| 54      | 2        | 0.65%   |
| 49      | 2        | 0.65%   |
| 47      | 2        | 0.65%   |
| 43      | 1        | 0.32%   |
| 40      | 1        | 0.32%   |
| 33      | 1        | 0.32%   |
| 26      | 1        | 0.32%   |
| 18      | 1        | 0.32%   |
| 14      | 1        | 0.32%   |
| 11      | 1        | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 145      | 49.66%  |
| 401-500     | 40       | 13.7%   |
| Unknown     | 33       | 11.3%   |
| 701-800     | 23       | 7.88%   |
| 601-700     | 18       | 6.16%   |
| 1001-1500   | 11       | 3.77%   |
| 351-400     | 9        | 3.08%   |
| 301-350     | 7        | 2.4%    |
| 1501-2000   | 3        | 1.03%   |
| 801-900     | 1        | 0.34%   |
| 201-300     | 1        | 0.34%   |
| 901-1000    | 1        | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 171      | 61.29%  |
| 16/10   | 37       | 13.26%  |
| Unknown | 30       | 10.75%  |
| 21/9    | 18       | 6.45%   |
| 5/4     | 13       | 4.66%   |
| 32/9    | 7        | 2.51%   |
| 4/3     | 2        | 0.72%   |
| 6/5     | 1        | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 99       | 32.57%  |
| 301-350        | 61       | 20.07%  |
| Unknown        | 33       | 10.86%  |
| 251-300        | 32       | 10.53%  |
| 351-500        | 30       | 9.87%   |
| 151-200        | 24       | 7.89%   |
| 501-1000       | 10       | 3.29%   |
| 141-150        | 7        | 2.3%    |
| More than 1000 | 6        | 1.97%   |
| 81-90          | 1        | 0.33%   |
| 51-60          | 1        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 150      | 52.08%  |
| 101-120 | 63       | 21.88%  |
| Unknown | 33       | 11.46%  |
| 121-160 | 22       | 7.64%   |
| 161-240 | 13       | 4.51%   |
| 1-50    | 7        | 2.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 183      | 64.89%  |
| 2     | 62       | 21.99%  |
| 0     | 26       | 9.22%   |
| 3     | 9        | 3.19%   |
| 4     | 2        | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 160      | 43.13%  |
| Realtek Semiconductor           | 130      | 35.04%  |
| Qualcomm Atheros                | 21       | 5.66%   |
| Broadcom                        | 15       | 4.04%   |
| Aquantia                        | 7        | 1.89%   |
| Marvell Technology Group        | 6        | 1.62%   |
| ASIX Electronics                | 5        | 1.35%   |
| TP-Link                         | 4        | 1.08%   |
| Nvidia                          | 3        | 0.81%   |
| Qualcomm Atheros Communications | 2        | 0.54%   |
| Netchip Technology              | 2        | 0.54%   |
| Metrologic Instruments          | 2        | 0.54%   |
| D-Link                          | 2        | 0.54%   |
| 3Com                            | 2        | 0.54%   |
| Texas Instruments               | 1        | 0.27%   |
| Ralink Technology               | 1        | 0.27%   |
| Ralink                          | 1        | 0.27%   |
| QLogic                          | 1        | 0.27%   |
| Pulse-Eight                     | 1        | 0.27%   |
| MediaTek                        | 1        | 0.27%   |
| Kyocera                         | 1        | 0.27%   |
| InterBiometrics                 | 1        | 0.27%   |
| Davicom Semiconductor           | 1        | 0.27%   |
| D-Link System                   | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106      | 24.04%  |
| Intel I211 Gigabit Network Connection                             | 57       | 12.93%  |
| Intel Wi-Fi 6 AX200                                               | 32       | 7.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18       | 4.08%   |
| Intel Ethernet Connection (2) I219-V                              | 14       | 3.17%   |
| Intel Ethernet Controller I225-V                                  | 12       | 2.72%   |
| Intel 82574L Gigabit Network Connection                           | 10       | 2.27%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 6        | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 1.36%   |
| Intel Wireless-AC 9260                                            | 5        | 1.13%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5        | 1.13%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4        | 0.91%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 4        | 0.91%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.91%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 0.91%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 0.91%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.68%   |
| Intel Wireless 8260                                               | 3        | 0.68%   |
| Intel Wireless 7260                                               | 3        | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3        | 0.68%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 3        | 0.68%   |
| Intel I350 Gigabit Network Connection                             | 3        | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.68%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2        | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.45%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 0.45%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 66       | 60%     |
| Qualcomm Atheros                | 17       | 15.45%  |
| Realtek Semiconductor           | 8        | 7.27%   |
| Broadcom                        | 8        | 7.27%   |
| TP-Link                         | 4        | 3.64%   |
| Qualcomm Atheros Communications | 2        | 1.82%   |
| D-Link                          | 2        | 1.82%   |
| Texas Instruments               | 1        | 0.91%   |
| Ralink Technology               | 1        | 0.91%   |
| Ralink                          | 1        | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 32       | 28.83%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6        | 5.41%   |
| Intel Wireless-AC 9260                                         | 5        | 4.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 4        | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4        | 3.6%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 4        | 3.6%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 4        | 3.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 4        | 3.6%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4        | 3.6%    |
| Intel Wireless 8260                                            | 3        | 2.7%    |
| Intel Wireless 7260                                            | 3        | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3        | 2.7%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 3        | 2.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 1.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2        | 1.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.8%    |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.8%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 2        | 1.8%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2        | 1.8%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 0.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 0.9%    |
| Texas Instruments ACX 100 22Mbps Wireless Interface            | 1        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 0.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 0.9%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 0.9%    |
| Ralink MT7601U Wireless Adapter                                | 1        | 0.9%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 1        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 0.9%    |
| Intel Wireless Gigabit 17265                                   | 1        | 0.9%    |
| Intel Wireless 3165                                            | 1        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1        | 0.9%    |
| D-Link DWL-G132 [Atheros AR5523]                               | 1        | 0.9%    |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]  | 1        | 0.9%    |
| Broadcom Network controller                                    | 1        | 0.9%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1        | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 133      | 44.04%  |
| Realtek Semiconductor    | 130      | 43.05%  |
| Broadcom                 | 7        | 2.32%   |
| Aquantia                 | 7        | 2.32%   |
| Marvell Technology Group | 6        | 1.99%   |
| Qualcomm Atheros         | 5        | 1.66%   |
| ASIX Electronics         | 5        | 1.66%   |
| Nvidia                   | 3        | 0.99%   |
| 3Com                     | 2        | 0.66%   |
| QLogic                   | 1        | 0.33%   |
| MediaTek                 | 1        | 0.33%   |
| Davicom Semiconductor    | 1        | 0.33%   |
| D-Link System            | 1        | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 106      | 32.82%  |
| Intel I211 Gigabit Network Connection                                         | 57       | 17.65%  |
| Realtek RTL8125 2.5GbE Controller                                             | 18       | 5.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 14       | 4.33%   |
| Intel Ethernet Controller I225-V                                              | 12       | 3.72%   |
| Intel 82574L Gigabit Network Connection                                       | 10       | 3.1%    |
| Intel Ethernet Connection (7) I219-V                                          | 7        | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 1.86%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 1.55%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 5        | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 4        | 1.24%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 1.24%   |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3        | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.93%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 3        | 0.93%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 3        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 3        | 0.93%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.93%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.62%   |
| Nvidia MCP77 Ethernet                                                         | 2        | 0.62%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 2        | 0.62%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 0.62%   |
| Intel Ethernet Connection (11) I219-V                                         | 2        | 0.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 0.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.62%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 2        | 0.62%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 0.62%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.62%   |
| ASIX AX88772                                                                  | 2        | 0.62%   |
| Realtek RTL-8029(AS)                                                          | 1        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.31%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1        | 0.31%   |
| Nvidia MCP79 Ethernet                                                         | 1        | 0.31%   |
| MediaTek Infinix NOTE 11                                                      | 1        | 0.31%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                       | 1        | 0.31%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.31%   |
| Intel Ethernet Connection I217-V                                              | 1        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 266      | 70.74%  |
| WiFi     | 103      | 27.39%  |
| Modem    | 7        | 1.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 227      | 80.78%  |
| WiFi     | 54       | 19.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 147      | 52.88%  |
| 2     | 94       | 33.81%  |
| 3     | 21       | 7.55%   |
| 4     | 6        | 2.16%   |
| 5     | 4        | 1.44%   |
| 0     | 4        | 1.44%   |
| 9     | 1        | 0.36%   |
| 6     | 1        | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 244      | 88.73%  |
| Yes  | 31       | 11.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 66       | 61.11%  |
| Cambridge Silicon Radio         | 22       | 20.37%  |
| ASUSTek Computer                | 5        | 4.63%   |
| Realtek Semiconductor           | 4        | 3.7%    |
| Broadcom                        | 4        | 3.7%    |
| Apple                           | 4        | 3.7%    |
| Qualcomm Atheros Communications | 1        | 0.93%   |
| HTC (High Tech Computer)        | 1        | 0.93%   |
| Belkin Components               | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 37       | 34.26%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 22       | 20.37%  |
| Intel AX201 Bluetooth                                                | 7        | 6.48%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 6        | 5.56%   |
| Intel Bluetooth wireless interface                                   | 6        | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5        | 4.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4        | 3.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 4        | 3.7%    |
| Realtek Bluetooth Radio                                              | 3        | 2.78%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle                   | 2        | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 1.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 2        | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.93%   |
| Intel AX210 Bluetooth                                                | 1        | 0.93%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.93%   |
| Belkin Components Bluetooth Device with trace filter                 | 1        | 0.93%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.93%   |
| Apple Bluetooth USB Host Controller                                  | 1        | 0.93%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 171      | 35.7%   |
| Nvidia                               | 100      | 20.88%  |
| Intel                                | 94       | 19.62%  |
| C-Media Electronics                  | 21       | 4.38%   |
| Logitech                             | 11       | 2.3%    |
| Creative Labs                        | 11       | 2.3%    |
| Texas Instruments                    | 7        | 1.46%   |
| Creative Technology                  | 6        | 1.25%   |
| Kingston Technology                  | 5        | 1.04%   |
| Razer USA                            | 4        | 0.84%   |
| JMTek                                | 4        | 0.84%   |
| Focusrite-Novation                   | 4        | 0.84%   |
| BEHRINGER International              | 4        | 0.84%   |
| ASUSTek Computer                     | 3        | 0.63%   |
| SteelSeries ApS                      | 2        | 0.42%   |
| SAVITECH                             | 2        | 0.42%   |
| RODE Microphones                     | 2        | 0.42%   |
| GYROCOM C&C                          | 2        | 0.42%   |
| GN Netcom                            | 2        | 0.42%   |
| AudioQuest                           | 2        | 0.42%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.21%   |
| Syntek                               | 1        | 0.21%   |
| Solid State Logic                    | 1        | 0.21%   |
| Sennheiser Communications            | 1        | 0.21%   |
| Samson Technologies                  | 1        | 0.21%   |
| Realtek Semiconductor                | 1        | 0.21%   |
| QinHeng Electronics                  | 1        | 0.21%   |
| Plantronics                          | 1        | 0.21%   |
| Nektar                               | 1        | 0.21%   |
| Microsoft                            | 1        | 0.21%   |
| Micronas                             | 1        | 0.21%   |
| JOUNIVO                              | 1        | 0.21%   |
| Generalplus Technology               | 1        | 0.21%   |
| FiiO Electronics Technology          | 1        | 0.21%   |
| Ensoniq                              | 1        | 0.21%   |
| Elgato Systems                       | 1        | 0.21%   |
| DSEA A/S                             | 1        | 0.21%   |
| Dell                                 | 1        | 0.21%   |
| Cirrus Logic                         | 1        | 0.21%   |
| Blue Microphones                     | 1        | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 72       | 12.1%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 42       | 7.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 40       | 6.72%   |
| AMD Navi 10 HDMI Audio                                                                          | 23       | 3.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 16       | 2.69%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                      | 14       | 2.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 13       | 2.18%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 10       | 1.68%   |
| Intel 200 Series PCH HD Audio                                                                   | 10       | 1.68%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 9        | 1.51%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 9        | 1.51%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 8        | 1.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 8        | 1.34%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 8        | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 7        | 1.18%   |
| Nvidia TU104 HD Audio Controller                                                                | 7        | 1.18%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 7        | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 7        | 1.18%   |
| Intel Cannon Lake PCH cAVS                                                                      | 7        | 1.18%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 6        | 1.01%   |
| Nvidia GP102 HDMI Audio Controller                                                              | 6        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 6        | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 6        | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 6        | 1.01%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 5        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 5        | 0.84%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 5        | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                                       | 5        | 0.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 5        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 5        | 0.84%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                   | 5        | 0.84%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 5        | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 4        | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 4        | 0.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 4        | 0.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 4        | 0.67%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                              | 4        | 0.67%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 56       | 19.79%  |
| G.Skill             | 56       | 19.79%  |
| Corsair             | 45       | 15.9%   |
| Unknown             | 35       | 12.37%  |
| Crucial             | 33       | 11.66%  |
| Samsung Electronics | 12       | 4.24%   |
| SK hynix            | 10       | 3.53%   |
| Micron Technology   | 6        | 2.12%   |
| Team                | 5        | 1.77%   |
| Patriot             | 5        | 1.77%   |
| Nanya Technology    | 3        | 1.06%   |
| GOODRAM             | 3        | 1.06%   |
| A-DATA Technology   | 3        | 1.06%   |
| Transcend           | 1        | 0.35%   |
| T-FORCE             | 1        | 0.35%   |
| Ramaxel Technology  | 1        | 0.35%   |
| Kllisre             | 1        | 0.35%   |
| KLEVV               | 1        | 0.35%   |
| Golden Empire       | 1        | 0.35%   |
| GeIL                | 1        | 0.35%   |
| Exceleram           | 1        | 0.35%   |
| Chun Well           | 1        | 0.35%   |
| AMD                 | 1        | 0.35%   |
| A Force             | 1        | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 6        | 1.97%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 6        | 1.97%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 5        | 1.64%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 5        | 1.64%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 3        | 0.98%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 3        | 0.98%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s     | 3        | 0.98%   |
| Kingston RAM KHX2666C15D4/8G 8GB DIMM DDR4 3200MT/s     | 3        | 0.98%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s   | 3        | 0.98%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s  | 3        | 0.98%   |
| G.Skill RAM F4-3200C16-16GTZ 16GB DIMM DDR4 3200MT/s    | 3        | 0.98%   |
| G.Skill RAM F4-3200C14-8GTZ 8GB DIMM DDR4 3733MT/s      | 3        | 0.98%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 3        | 0.98%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s    | 3        | 0.98%   |
| Crucial RAM CT4G4DFS8213.C8FAD11 4GB DIMM DDR4 2133MT/s | 3        | 0.98%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s  | 3        | 0.98%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 3        | 0.98%   |
| Unknown RAM Module 4096MB DIMM                          | 2        | 0.66%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s   | 2        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s     | 2        | 0.66%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s    | 2        | 0.66%   |
| Samsung RAM Module 4GB DIMM DDR3 1066MT/s               | 2        | 0.66%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s     | 2        | 0.66%   |
| Nanya RAM M2F4G64CB88B7N-DI 4GB DIMM DDR3 1600MT/s      | 2        | 0.66%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 0.66%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s  | 2        | 0.66%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 2        | 0.66%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 0.66%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s   | 2        | 0.66%   |
| GOODRAM RAM GR1600D364L11/2G 2GB DIMM DDR3 1333MT/s     | 2        | 0.66%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GTZB 8GB DIMM DDR4 3200MT/s     | 2        | 0.66%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s      | 2        | 0.66%   |
| G.Skill RAM F4-3200C14-16GVK 16GB DIMM DDR4 3200MT/s    | 2        | 0.66%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3000MT/s   | 2        | 0.66%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s   | 2        | 0.66%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s   | 2        | 0.66%   |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4 3000MT/s   | 2        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 181      | 69.62%  |
| DDR3    | 48       | 18.46%  |
| DDR2    | 11       | 4.23%   |
| Unknown | 11       | 4.23%   |
| SDRAM   | 7        | 2.69%   |
| DDR     | 2        | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 253      | 98.06%  |
| SODIMM | 4        | 1.55%   |
| RIMM   | 1        | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 101      | 35.94%  |
| 16384 | 93       | 33.1%   |
| 4096  | 37       | 13.17%  |
| 32768 | 21       | 7.47%   |
| 2048  | 19       | 6.76%   |
| 1024  | 7        | 2.49%   |
| 512   | 3        | 1.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 40       | 14.08%  |
| 3600    | 39       | 13.73%  |
| 1600    | 29       | 10.21%  |
| 2400    | 21       | 7.39%   |
| 1333    | 18       | 6.34%   |
| 3000    | 16       | 5.63%   |
| 2133    | 13       | 4.58%   |
| 3733    | 12       | 4.23%   |
| 800     | 10       | 3.52%   |
| 3400    | 9        | 3.17%   |
| 2933    | 8        | 2.82%   |
| 2667    | 8        | 2.82%   |
| 667     | 8        | 2.82%   |
| 3466    | 7        | 2.46%   |
| Unknown | 6        | 2.11%   |
| 2666    | 5        | 1.76%   |
| 3866    | 4        | 1.41%   |
| 3800    | 4        | 1.41%   |
| 1066    | 4        | 1.41%   |
| 3333    | 3        | 1.06%   |
| 3100    | 3        | 1.06%   |
| 4000    | 2        | 0.7%    |
| 3066    | 2        | 0.7%    |
| 2465    | 2        | 0.7%    |
| 1867    | 2        | 0.7%    |
| 1866    | 2        | 0.7%    |
| 400     | 2        | 0.7%    |
| 3666    | 1        | 0.35%   |
| 3467    | 1        | 0.35%   |
| 2800    | 1        | 0.35%   |
| 2134    | 1        | 0.35%   |
| 1800    | 1        | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 5        | 83.33%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| HP PhotoSmart 130   | 1        | 16.67%  |
| HP LaserJet M14-M17 | 1        | 16.67%  |
| HP LaserJet 1020    | 1        | 16.67%  |
| HP LaserJet 1018    | 1        | 16.67%  |
| HP LaserJet 1010    | 1        | 16.67%  |
| Brother MFC-9130CW  | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 33.33%  |
| Canon CanoScan LiDE 600F      | 1        | 33.33%  |
| Canon CanoScan LiDE 110       | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 45       | 65.22%  |
| Z-Star Microelectronics       | 4        | 5.8%    |
| Microdia                      | 4        | 5.8%    |
| Samsung Electronics           | 3        | 4.35%   |
| ARC International             | 3        | 4.35%   |
| Realtek Semiconductor         | 2        | 2.9%    |
| MacroSilicon                  | 2        | 2.9%    |
| Sunplus Innovation Technology | 1        | 1.45%   |
| KYE Systems (Mouse Systems)   | 1        | 1.45%   |
| HD 2MP WEBCAM                 | 1        | 1.45%   |
| Creative Technology           | 1        | 1.45%   |
| AVerMedia Technologies        | 1        | 1.45%   |
| A4Tech                        | 1        | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                 | 11       | 15.71%  |
| Logitech Webcam C270                        | 9        | 12.86%  |
| Logitech C922 Pro Stream Webcam             | 4        | 5.71%   |
| Z-Star Venus USB2.0 Camera                  | 3        | 4.29%   |
| Samsung Galaxy A5 (MTP)                     | 3        | 4.29%   |
| Logitech Webcam C310                        | 3        | 4.29%   |
| ARC International Camera                    | 3        | 4.29%   |
| MacroSilicon USB Video                      | 2        | 2.86%   |
| Logitech Webcam C925e                       | 2        | 2.86%   |
| Logitech Webcam C200                        | 2        | 2.86%   |
| Logitech HD Webcam C615                     | 2        | 2.86%   |
| Logitech C920 PRO HD Webcam                 | 2        | 2.86%   |
| Logitech B525 HD Webcam                     | 2        | 2.86%   |
| Z-Star Vimicro USB Camera (Altair)          | 1        | 1.43%   |
| Sunplus MYPIN HD Capture                    | 1        | 1.43%   |
| Realtek USB Camera                          | 1        | 1.43%   |
| Realtek Full HD webcam                      | 1        | 1.43%   |
| Microdia Webcam Vitade AF                   | 1        | 1.43%   |
| Microdia USB 2.0 Camera                     | 1        | 1.43%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 1        | 1.43%   |
| Microdia Camera                             | 1        | 1.43%   |
| Logitech Webcam Pro 9000                    | 1        | 1.43%   |
| Logitech Webcam C930e                       | 1        | 1.43%   |
| Logitech Webcam C300                        | 1        | 1.43%   |
| Logitech Webcam C170                        | 1        | 1.43%   |
| Logitech QuickCam Pro 9000                  | 1        | 1.43%   |
| Logitech QuickCam Communicate MP/S5500      | 1        | 1.43%   |
| Logitech HD Webcam C510                     | 1        | 1.43%   |
| Logitech C505e HD Webcam                    | 1        | 1.43%   |
| Logitech BRIO Ultra HD Webcam               | 1        | 1.43%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera  | 1        | 1.43%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                 | 1        | 1.43%   |
| Creative VF0610 Live! Cam Socialize HD      | 1        | 1.43%   |
| AVerMedia USB Device                        | 1        | 1.43%   |
| A4Tech HD 720P PC Camera                    | 1        | 1.43%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Clay Logic                        | 2        | 50%     |
| VASCO Data Security International | 1        | 25%     |
| Aktiv                             | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Clay Logic Nitrokey Pro                        | 2        | 50%     |
| VASCO Data Security International DIGIPASS 870 | 1        | 25%     |
| Aktiv Rutoken lite                             | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 171      | 58.97%  |
| 1     | 86       | 29.66%  |
| 2     | 22       | 7.59%   |
| 3     | 9        | 3.1%    |
| 5     | 1        | 0.34%   |
| 4     | 1        | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 39       | 25%     |
| Sound                    | 20       | 12.82%  |
| Bluetooth                | 20       | 12.82%  |
| Graphics card            | 19       | 12.18%  |
| Net/wireless             | 15       | 9.62%   |
| Firewire controller      | 12       | 7.69%   |
| Camera                   | 7        | 4.49%   |
| Network                  | 4        | 2.56%   |
| Net/ethernet             | 4        | 2.56%   |
| Storage/raid             | 3        | 1.92%   |
| Storage/ide              | 3        | 1.92%   |
| Tv card                  | 2        | 1.28%   |
| Chipcard                 | 2        | 1.28%   |
| Unassigned class         | 1        | 0.64%   |
| Storage                  | 1        | 0.64%   |
| Multimedia controller    | 1        | 0.64%   |
| Modem                    | 1        | 0.64%   |
| Dvb card                 | 1        | 0.64%   |
| Card reader              | 1        | 0.64%   |

