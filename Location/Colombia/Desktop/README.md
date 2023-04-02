Linux in Colombia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

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

Total: 354

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| Lenovo        | ThinkServer TS130           | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [592d9de1cb](https://linux-hardware.org/?probe=592d9de1cb) | Mar 23, 2023 |
| HP            | 18E9                        | [2cc6071591](https://linux-hardware.org/?probe=2cc6071591) | Mar 20, 2023 |
| Lenovo        | MAHOBAY NOK                 | [04ba5a6790](https://linux-hardware.org/?probe=04ba5a6790) | Mar 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [fcbb054633](https://linux-hardware.org/?probe=fcbb054633) | Mar 18, 2023 |
| HP            | 1850                        | [c805a3a08f](https://linux-hardware.org/?probe=c805a3a08f) | Mar 17, 2023 |
| Gigabyte      | B550 AORUS PRO              | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | H81M-P33                    | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| HP            | 1850                        | [c5439b2fea](https://linux-hardware.org/?probe=c5439b2fea) | Mar 15, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Biostar       | H61MHV                      | [9f184e6e93](https://linux-hardware.org/?probe=9f184e6e93) | Mar 11, 2023 |
| Intel         | DH61BF AAG81311-101         | [b960fb0ebf](https://linux-hardware.org/?probe=b960fb0ebf) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Acer          | Aspire X1400                | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | 806A                        | [66c29ddd8a](https://linux-hardware.org/?probe=66c29ddd8a) | Mar 03, 2023 |
| HP            | 2ADE                        | [b4309c2b06](https://linux-hardware.org/?probe=b4309c2b06) | Feb 23, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| HP            | 18E9                        | [e3461fcb74](https://linux-hardware.org/?probe=e3461fcb74) | Feb 16, 2023 |
| HP            | 1497                        | [b27560d384](https://linux-hardware.org/?probe=b27560d384) | Feb 14, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e4496f3ff8](https://linux-hardware.org/?probe=e4496f3ff8) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [5fe8eef781](https://linux-hardware.org/?probe=5fe8eef781) | Feb 09, 2023 |
| Unknown       | X79A                        | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [edbd391f2d](https://linux-hardware.org/?probe=edbd391f2d) | Feb 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Intel         | DH61BF AAG81311-101         | [d6ea5bde87](https://linux-hardware.org/?probe=d6ea5bde87) | Jan 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| ASRock        | G965M-S                     | [c1a6d7685b](https://linux-hardware.org/?probe=c1a6d7685b) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [d569a3f698](https://linux-hardware.org/?probe=d569a3f698) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| Gigabyte      | A520M DS3H                  | [e7107ee8b4](https://linux-hardware.org/?probe=e7107ee8b4) | Jan 06, 2023 |
| Gigabyte      | A520M DS3H                  | [e351ff5e1d](https://linux-hardware.org/?probe=e351ff5e1d) | Jan 05, 2023 |
| Intel         | DH61BF AAG81311-101         | [db8d3007ee](https://linux-hardware.org/?probe=db8d3007ee) | Jan 03, 2023 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [cb7cb7b7d7](https://linux-hardware.org/?probe=cb7cb7b7d7) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [fcd0306cd3](https://linux-hardware.org/?probe=fcd0306cd3) | Dec 19, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| HP            | 18E9                        | [9086d1a1e5](https://linux-hardware.org/?probe=9086d1a1e5) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Dell          | 0TP406                      | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| HP            | 339A                        | [ea5cacd50e](https://linux-hardware.org/?probe=ea5cacd50e) | Nov 29, 2022 |
| Dell          | 0HJ054                      | [0e3d082d5a](https://linux-hardware.org/?probe=0e3d082d5a) | Nov 22, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| MSI           | GF615M-P33                  | [1a298da454](https://linux-hardware.org/?probe=1a298da454) | Nov 09, 2022 |
| Intel         | D33217GKE G76540-207        | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6edc8b1444](https://linux-hardware.org/?probe=6edc8b1444) | Oct 06, 2022 |
| Gigabyte      | G41MT-S2                    | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| HP            | 18E7                        | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| ASRock        | A520M-HDV                   | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| HP            | 1494                        | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| ECS           | H61H2-M2                    | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [04474401fc](https://linux-hardware.org/?probe=04474401fc) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| ASUSTek       | TUF B365-PLUS GAMING        | [83e59cf9a5](https://linux-hardware.org/?probe=83e59cf9a5) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ECS           | H61H2-M2                    | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| BESSTAR Te... | TH50                        | [03159c112c](https://linux-hardware.org/?probe=03159c112c) | Aug 12, 2022 |
| ASRock        | B550M Pro4                  | [7fa92e1cb6](https://linux-hardware.org/?probe=7fa92e1cb6) | Aug 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| HP            | ProLiant ML310e Gen8        | [7a12318176](https://linux-hardware.org/?probe=7a12318176) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [68d8843883](https://linux-hardware.org/?probe=68d8843883) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [057b18a904](https://linux-hardware.org/?probe=057b18a904) | Jul 16, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Dell          | 054KM3 A01                  | [149f746382](https://linux-hardware.org/?probe=149f746382) | Jul 02, 2022 |
| ASRock        | A320M-HDV                   | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | H81M-E33                    | [d79b11186c](https://linux-hardware.org/?probe=d79b11186c) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Dell          | 0J2J3Y A00                  | [50f015312c](https://linux-hardware.org/?probe=50f015312c) | Jun 23, 2022 |
| MSI           | H81M-E33                    | [0d2ace0dde](https://linux-hardware.org/?probe=0d2ace0dde) | Jun 16, 2022 |
| MSI           | H81M-E33                    | [52dbd6f482](https://linux-hardware.org/?probe=52dbd6f482) | Jun 16, 2022 |
| Gigabyte      | H61M-HD2                    | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| HP            | 8054                        | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [af01f27647](https://linux-hardware.org/?probe=af01f27647) | Apr 30, 2022 |
| Pegatron      | 2A73h                       | [a756a0148d](https://linux-hardware.org/?probe=a756a0148d) | Apr 27, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7b24feb14a](https://linux-hardware.org/?probe=7b24feb14a) | Apr 21, 2022 |
| ASUSTek       | PRIME Z390-A                | [81d7ace164](https://linux-hardware.org/?probe=81d7ace164) | Apr 18, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [65a5442605](https://linux-hardware.org/?probe=65a5442605) | Apr 04, 2022 |
| HP            | ProLiant ML150 Gen9         | [50114897cc](https://linux-hardware.org/?probe=50114897cc) | Apr 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [066fb2b2b9](https://linux-hardware.org/?probe=066fb2b2b9) | Mar 30, 2022 |
| ASRock        | G41M-VS3                    | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek       | PRIME H410M-E               | [1f267ffe6e](https://linux-hardware.org/?probe=1f267ffe6e) | Mar 11, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d068227c07](https://linux-hardware.org/?probe=d068227c07) | Mar 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ac671d5e38](https://linux-hardware.org/?probe=ac671d5e38) | Mar 05, 2022 |
| Supermicro    | X7DA8                       | [fcf69abc8f](https://linux-hardware.org/?probe=fcf69abc8f) | Feb 25, 2022 |
| Gigabyte      | H410M H V3                  | [4c58660705](https://linux-hardware.org/?probe=4c58660705) | Feb 22, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [217c73c9a6](https://linux-hardware.org/?probe=217c73c9a6) | Feb 11, 2022 |
| ASRock        | Z77 Extreme4                | [95b7145bd2](https://linux-hardware.org/?probe=95b7145bd2) | Feb 06, 2022 |
| HP            | 1587h                       | [92625959b4](https://linux-hardware.org/?probe=92625959b4) | Feb 02, 2022 |
| ASUSTek       | H61M-K                      | [c7a35398d0](https://linux-hardware.org/?probe=c7a35398d0) | Feb 02, 2022 |
| ASUSTek       | PRIME H410M-E               | [876f78e96c](https://linux-hardware.org/?probe=876f78e96c) | Feb 01, 2022 |
| Intel         | DH61HO AAG62445-102         | [e0cbedce41](https://linux-hardware.org/?probe=e0cbedce41) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| Gigabyte      | H410M H                     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| ASUSTek       | Maximus IX CODE             | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| ASRock        | H110M-HDV R3.0              | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| MSI           | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| MSI           | B150A GAMING PRO            | [475ea42f9a](https://linux-hardware.org/?probe=475ea42f9a) | Dec 11, 2021 |
| HP            | 3047h                       | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| MSI           | 760GM-P23                   | [cbe2fcd79d](https://linux-hardware.org/?probe=cbe2fcd79d) | Nov 26, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [92d9d82670](https://linux-hardware.org/?probe=92d9d82670) | Nov 25, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [e3a6c887f6](https://linux-hardware.org/?probe=e3a6c887f6) | Nov 25, 2021 |
| ASRock        | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| ASUSTek       | PRIME X570-P                | [abd0cfab6b](https://linux-hardware.org/?probe=abd0cfab6b) | Nov 12, 2021 |
| ASUSTek       | PRIME X570-P                | [27aa14962f](https://linux-hardware.org/?probe=27aa14962f) | Nov 12, 2021 |
| ASUSTek       | PRIME B550M-K               | [de9d0e2b40](https://linux-hardware.org/?probe=de9d0e2b40) | Nov 08, 2021 |
| ASRock        | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [c196661531](https://linux-hardware.org/?probe=c196661531) | Nov 01, 2021 |
| MSI           | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Gigabyte      | H81M-H                      | [eb596b1774](https://linux-hardware.org/?probe=eb596b1774) | Oct 25, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [cdd35d634d](https://linux-hardware.org/?probe=cdd35d634d) | Oct 24, 2021 |
| ASUSTek       | PRIME B550M-K               | [d9c192ea8c](https://linux-hardware.org/?probe=d9c192ea8c) | Oct 23, 2021 |
| ASRock        | G41M-VS3                    | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| HP            | 0B4Ch D                     | [d0b6443f5b](https://linux-hardware.org/?probe=d0b6443f5b) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [05c0fc8d29](https://linux-hardware.org/?probe=05c0fc8d29) | Oct 10, 2021 |
| ASUSTek       | PRIME B550M-K               | [d034cd0b4a](https://linux-hardware.org/?probe=d034cd0b4a) | Oct 07, 2021 |
| Foxconn       | H61MXE                      | [f684b8da61](https://linux-hardware.org/?probe=f684b8da61) | Oct 06, 2021 |
| ASRock        | G41M-VS3                    | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| Pegatron      | 2AE2                        | [0309cddc66](https://linux-hardware.org/?probe=0309cddc66) | Oct 02, 2021 |
| ASUSTek       | Z97-A                       | [6476a95a04](https://linux-hardware.org/?probe=6476a95a04) | Sep 27, 2021 |
| Biostar       | G41D3C                      | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | PRIME B550M-K               | [b30800b2f9](https://linux-hardware.org/?probe=b30800b2f9) | Sep 24, 2021 |
| Gigabyte      | H81M-H                      | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| ECS           | G31T-M7                     | [60bf966d06](https://linux-hardware.org/?probe=60bf966d06) | Sep 18, 2021 |
| ASRock        | G41M-VS3                    | [7922da571d](https://linux-hardware.org/?probe=7922da571d) | Sep 16, 2021 |
| ASRock        | G41M-VS3                    | [e7afe651d3](https://linux-hardware.org/?probe=e7afe651d3) | Sep 16, 2021 |
| HP            | 18E9                        | [7a7dd34d6d](https://linux-hardware.org/?probe=7a7dd34d6d) | Sep 13, 2021 |
| MSI           | B350M GAMING PRO            | [052bfbd512](https://linux-hardware.org/?probe=052bfbd512) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | [a3b7774236](https://linux-hardware.org/?probe=a3b7774236) | Sep 09, 2021 |
| Intel         | D945GCLF2D AAE59323-101     | [d6808fecbf](https://linux-hardware.org/?probe=d6808fecbf) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| Gigabyte      | G31M-S2C                    | [15d48710db](https://linux-hardware.org/?probe=15d48710db) | Aug 24, 2021 |
| Pegatron      | 2AEE                        | [a3e6da7d21](https://linux-hardware.org/?probe=a3e6da7d21) | Aug 22, 2021 |
| Pegatron      | 2AEE                        | [0b0cf520ba](https://linux-hardware.org/?probe=0b0cf520ba) | Aug 22, 2021 |
| Gigabyte      | G31M-S2C                    | [a8d5b4ff89](https://linux-hardware.org/?probe=a8d5b4ff89) | Aug 22, 2021 |
| HP            | 18E9                        | [9ee974d2df](https://linux-hardware.org/?probe=9ee974d2df) | Aug 21, 2021 |
| HP            | 18E9                        | [838f27241e](https://linux-hardware.org/?probe=838f27241e) | Aug 21, 2021 |
| HP            | 304Ah                       | [4760a65d2f](https://linux-hardware.org/?probe=4760a65d2f) | Aug 20, 2021 |
| HP            | 304Ah                       | [67e7cc53c1](https://linux-hardware.org/?probe=67e7cc53c1) | Aug 18, 2021 |
| Intel         | DB75EN AAG39650-303         | [321af82bbf](https://linux-hardware.org/?probe=321af82bbf) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Intel         | DH55HC AAE70933-505         | [e8b5870e50](https://linux-hardware.org/?probe=e8b5870e50) | Jul 19, 2021 |
| MSI           | MS-7309                     | [8b431e8b6f](https://linux-hardware.org/?probe=8b431e8b6f) | Jul 10, 2021 |
| ASRock        | Wolfdale1333-D667           | [7b71d5854c](https://linux-hardware.org/?probe=7b71d5854c) | Jul 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| Intel         | H61                         | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [33c1ecc56e](https://linux-hardware.org/?probe=33c1ecc56e) | May 19, 2021 |
| Gigabyte      | Z68X-UD7-B3                 | [22eae98fb5](https://linux-hardware.org/?probe=22eae98fb5) | May 13, 2021 |
| ECS           | H81H3-M4                    | [6889e28bfd](https://linux-hardware.org/?probe=6889e28bfd) | May 09, 2021 |
| ECS           | H81H3-M4                    | [0ef93e6291](https://linux-hardware.org/?probe=0ef93e6291) | May 09, 2021 |
| ASRock        | G965M-S                     | [dd116582af](https://linux-hardware.org/?probe=dd116582af) | May 03, 2021 |
| Intel         | H61                         | [cca60711c8](https://linux-hardware.org/?probe=cca60711c8) | May 01, 2021 |
| ASUSTek       | M4A77T/USB3                 | [ae115d5ca8](https://linux-hardware.org/?probe=ae115d5ca8) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | [34733fe16f](https://linux-hardware.org/?probe=34733fe16f) | Apr 29, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [037a465656](https://linux-hardware.org/?probe=037a465656) | Apr 28, 2021 |
| MSI           | 970A-G46                    | [f1035827e0](https://linux-hardware.org/?probe=f1035827e0) | Apr 26, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [6410827a2f](https://linux-hardware.org/?probe=6410827a2f) | Apr 25, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [a8c42b2d94](https://linux-hardware.org/?probe=a8c42b2d94) | Apr 25, 2021 |
| MSI           | 970A-G46                    | [9aa4264419](https://linux-hardware.org/?probe=9aa4264419) | Apr 22, 2021 |
| MSI           | K9A2 Platinum               | [fc4fd8ba0e](https://linux-hardware.org/?probe=fc4fd8ba0e) | Apr 19, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [7585c05b18](https://linux-hardware.org/?probe=7585c05b18) | Apr 19, 2021 |
| MSI           | K9A2 Platinum               | [ef223aa1d5](https://linux-hardware.org/?probe=ef223aa1d5) | Apr 16, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [48ab0d2acd](https://linux-hardware.org/?probe=48ab0d2acd) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [cc61b2b6a7](https://linux-hardware.org/?probe=cc61b2b6a7) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [c079cb8fac](https://linux-hardware.org/?probe=c079cb8fac) | Apr 01, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| Dell          | 0G3HR7 A00                  | [f2760185e3](https://linux-hardware.org/?probe=f2760185e3) | Mar 26, 2021 |
| Intel         | DH55HC AAE70933-505         | [2ebfc03ce7](https://linux-hardware.org/?probe=2ebfc03ce7) | Mar 20, 2021 |
| Dell          | 0G3HR7 A00                  | [29c1565b42](https://linux-hardware.org/?probe=29c1565b42) | Mar 10, 2021 |
| Gigabyte      | H61M-S1                     | [98d2580d9e](https://linux-hardware.org/?probe=98d2580d9e) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | [91cd908a95](https://linux-hardware.org/?probe=91cd908a95) | Mar 05, 2021 |
| HP            | 2B09                        | [44e3728303](https://linux-hardware.org/?probe=44e3728303) | Mar 05, 2021 |
| ASRock        | Wolfdale1333-D667           | [4cb354b544](https://linux-hardware.org/?probe=4cb354b544) | Mar 02, 2021 |
| Intel         | DP67DE AAG10217-205         | [4b376912e1](https://linux-hardware.org/?probe=4b376912e1) | Feb 23, 2021 |
| Intel         | DP67DE AAG10217-205         | [497e0558af](https://linux-hardware.org/?probe=497e0558af) | Feb 23, 2021 |
| ASRock        | Wolfdale1333-D667           | [ed29a42a57](https://linux-hardware.org/?probe=ed29a42a57) | Feb 23, 2021 |
| MSI           | A320M-A PRO MAX             | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Dell          | 0HN7XN A01                  | [909121ec95](https://linux-hardware.org/?probe=909121ec95) | Feb 03, 2021 |
| ASRock        | G41M-VS3                    | [b7460ea1e6](https://linux-hardware.org/?probe=b7460ea1e6) | Feb 02, 2021 |
| ECS           | H81H3-M4                    | [b452e9e060](https://linux-hardware.org/?probe=b452e9e060) | Jan 27, 2021 |
| ASUSTek       | PRIME H310M-E               | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [8dcbe2b63e](https://linux-hardware.org/?probe=8dcbe2b63e) | Jan 15, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [c969271698](https://linux-hardware.org/?probe=c969271698) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9bd74368f0](https://linux-hardware.org/?probe=9bd74368f0) | Jan 15, 2021 |
| Intel         | H61                         | [d8489ff473](https://linux-hardware.org/?probe=d8489ff473) | Jan 11, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [81ab4a6cc7](https://linux-hardware.org/?probe=81ab4a6cc7) | Jan 11, 2021 |
| MSI           | B450M BAZOOKA V2            | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| Biostar       | H61MHV                      | [60f41299a7](https://linux-hardware.org/?probe=60f41299a7) | Jan 04, 2021 |
| Gigabyte      | 970A-UD3                    | [4de6e16ced](https://linux-hardware.org/?probe=4de6e16ced) | Dec 30, 2020 |
| Dell          | 0G3HR7 A00                  | [1c8f1911c4](https://linux-hardware.org/?probe=1c8f1911c4) | Dec 29, 2020 |
| PCSMART       | Unknown                     | [5c91c760a5](https://linux-hardware.org/?probe=5c91c760a5) | Dec 28, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [69e3d131e9](https://linux-hardware.org/?probe=69e3d131e9) | Dec 16, 2020 |
| ASRock        | G41M-VS3                    | [7633d83de8](https://linux-hardware.org/?probe=7633d83de8) | Dec 08, 2020 |
| ECS           | G31T-M7                     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| ECS           | H81H3-M4                    | [324e08922c](https://linux-hardware.org/?probe=324e08922c) | Nov 23, 2020 |
| ASRock        | B450M Pro4                  | [63124c698a](https://linux-hardware.org/?probe=63124c698a) | Nov 22, 2020 |
| Foxconn       | 2ABF                        | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| ASRock        | AB350M-HDV                  | [4a503972bc](https://linux-hardware.org/?probe=4a503972bc) | Nov 18, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [a802e86d43](https://linux-hardware.org/?probe=a802e86d43) | Nov 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a39151865e](https://linux-hardware.org/?probe=a39151865e) | Nov 06, 2020 |
| ASRock        | 960GM-VGS3 FX               | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| ASRock        | A320M-HDV                   | [c4f1aaa3bb](https://linux-hardware.org/?probe=c4f1aaa3bb) | Nov 02, 2020 |
| ASRock        | A320M-HDV                   | [a283f0ab00](https://linux-hardware.org/?probe=a283f0ab00) | Nov 01, 2020 |
| Foxconn       | 2ABF                        | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| ASRock        | G31M-GS                     | [ed0373efb3](https://linux-hardware.org/?probe=ed0373efb3) | Oct 22, 2020 |
| MSI           | H81M-E33                    | [dc82b20825](https://linux-hardware.org/?probe=dc82b20825) | Oct 20, 2020 |
| MSI           | H81M-E33                    | [21a8676b32](https://linux-hardware.org/?probe=21a8676b32) | Oct 20, 2020 |
| ASRock        | B450M-HDV R4.0              | [d1e0bb32d7](https://linux-hardware.org/?probe=d1e0bb32d7) | Oct 19, 2020 |
| Lenovo        | ThinkCentre A58 7515A18     | [6d228ca955](https://linux-hardware.org/?probe=6d228ca955) | Oct 05, 2020 |
| Gigabyte      | B450M DS3H-CF               | [309b4ecbe6](https://linux-hardware.org/?probe=309b4ecbe6) | Oct 02, 2020 |
| Gigabyte      | G31M-ES2C                   | [41c9698c88](https://linux-hardware.org/?probe=41c9698c88) | Oct 01, 2020 |
| Intel         | 945GCT-M                    | [c0ad55286f](https://linux-hardware.org/?probe=c0ad55286f) | Sep 26, 2020 |
| Dell          | 0MM599                      | [bf8a1f8434](https://linux-hardware.org/?probe=bf8a1f8434) | Sep 22, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [b178b5269a](https://linux-hardware.org/?probe=b178b5269a) | Sep 18, 2020 |
| ASUSTek       | M4A87TD EVO                 | [4b2b8ed64f](https://linux-hardware.org/?probe=4b2b8ed64f) | Sep 06, 2020 |
| ASRock        | X570 Steel Legend           | [fcc32617ab](https://linux-hardware.org/?probe=fcc32617ab) | Sep 06, 2020 |
| Gigabyte      | AM1M-S2H                    | [8f57e5d722](https://linux-hardware.org/?probe=8f57e5d722) | Sep 05, 2020 |
| PCSMART       | 6.0                         | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| ASRock        | H110M-HDV R3.0              | [b641263269](https://linux-hardware.org/?probe=b641263269) | Sep 04, 2020 |
| ASUSTek       | M4A87TD/USB3                | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | [131299dd43](https://linux-hardware.org/?probe=131299dd43) | Sep 02, 2020 |
| ASUSTek       | PRIME A320M-K               | [c7c173a4d6](https://linux-hardware.org/?probe=c7c173a4d6) | Aug 28, 2020 |
| ASUSTek       | PRIME H310M-E               | [07445986db](https://linux-hardware.org/?probe=07445986db) | Aug 24, 2020 |
| Dell          | 0D6H9T A01                  | [9c13b5e775](https://linux-hardware.org/?probe=9c13b5e775) | Aug 20, 2020 |
| Dell          | 0D6H9T A01                  | [40b95dab91](https://linux-hardware.org/?probe=40b95dab91) | Aug 20, 2020 |
| ECS           | H81H3-M4                    | [2a6af22359](https://linux-hardware.org/?probe=2a6af22359) | Aug 18, 2020 |
| Foxconn       | 2ABF                        | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| ECS           | H81H3-M4                    | [6edc3d456f](https://linux-hardware.org/?probe=6edc3d456f) | Aug 16, 2020 |
| MSI           | A68HM-E33                   | [819dd19a0e](https://linux-hardware.org/?probe=819dd19a0e) | Aug 14, 2020 |
| ASUSTek       | H110-PLUS                   | [28a6907d78](https://linux-hardware.org/?probe=28a6907d78) | Aug 14, 2020 |
| ASUSTek       | PRIME H310M-E               | [a10db0a0f1](https://linux-hardware.org/?probe=a10db0a0f1) | Aug 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | [76ee87fa06](https://linux-hardware.org/?probe=76ee87fa06) | Aug 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [67b506f12f](https://linux-hardware.org/?probe=67b506f12f) | Jul 16, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [65d309fa0f](https://linux-hardware.org/?probe=65d309fa0f) | Jul 16, 2020 |
| Gigabyte      | X570 UD                     | [dffcf158e7](https://linux-hardware.org/?probe=dffcf158e7) | Jul 12, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [f24093f04f](https://linux-hardware.org/?probe=f24093f04f) | Jul 09, 2020 |
| HP            | ProLiant ML310e Gen8 v2     | [b97d60900c](https://linux-hardware.org/?probe=b97d60900c) | Jul 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a57a22212c](https://linux-hardware.org/?probe=a57a22212c) | Jul 06, 2020 |
| ECS           | G31T-M7                     | [95cb3298ec](https://linux-hardware.org/?probe=95cb3298ec) | Jul 05, 2020 |
| ECS           | G31T-M7                     | [56b5cd6eac](https://linux-hardware.org/?probe=56b5cd6eac) | Jul 05, 2020 |
| Pegatron      | 2A73h                       | [58e16275bc](https://linux-hardware.org/?probe=58e16275bc) | Jul 04, 2020 |
| ECS           | H81H3-M4                    | [ed75f47aa0](https://linux-hardware.org/?probe=ed75f47aa0) | Jun 30, 2020 |
| Hardkernel    | ODROID-H2                   | [3cda40d161](https://linux-hardware.org/?probe=3cda40d161) | Jun 28, 2020 |
| ASRock        | N68C-S UCC                  | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| ECS           | H81H3-M4                    | [9dfcf2f0cb](https://linux-hardware.org/?probe=9dfcf2f0cb) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [f90ccba28d](https://linux-hardware.org/?probe=f90ccba28d) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c8a9bbbaa0](https://linux-hardware.org/?probe=c8a9bbbaa0) | Jun 20, 2020 |
| Biostar       | N68S3+                      | [3d289fd6d2](https://linux-hardware.org/?probe=3d289fd6d2) | Jun 15, 2020 |
| Dell          | 054KM3 A00                  | [3e9f988a30](https://linux-hardware.org/?probe=3e9f988a30) | Jun 11, 2020 |
| ASRock        | G41M-VS3                    | [8143bab4c5](https://linux-hardware.org/?probe=8143bab4c5) | May 30, 2020 |
| MSI           | A55M-P35                    | [1816e90106](https://linux-hardware.org/?probe=1816e90106) | May 22, 2020 |
| ASRock        | G41M-VS3                    | [a0a6bd1e26](https://linux-hardware.org/?probe=a0a6bd1e26) | May 22, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [dc1d621a65](https://linux-hardware.org/?probe=dc1d621a65) | May 15, 2020 |
| MSI           | H110M PRO-VH PLUS           | [c54d7ef6ee](https://linux-hardware.org/?probe=c54d7ef6ee) | May 10, 2020 |
| MSI           | H110M PRO-VH PLUS           | [cbf18515b3](https://linux-hardware.org/?probe=cbf18515b3) | May 10, 2020 |
| ASRock        | G965M-S                     | [9d4cff9871](https://linux-hardware.org/?probe=9d4cff9871) | May 05, 2020 |
| PCChips       | P17G ECS                    | [8220dc9d9a](https://linux-hardware.org/?probe=8220dc9d9a) | May 04, 2020 |
| ECS           | H81H3-M4                    | [c8dd8d2166](https://linux-hardware.org/?probe=c8dd8d2166) | May 02, 2020 |
| Gigabyte      | H170-Gaming 3 DDR3          | [b6540749a2](https://linux-hardware.org/?probe=b6540749a2) | May 01, 2020 |
| MSI           | 970A-G43 PLUS               | [50a3cd26c8](https://linux-hardware.org/?probe=50a3cd26c8) | Apr 25, 2020 |
| Gigabyte      | G31M-S2C                    | [2392a43f27](https://linux-hardware.org/?probe=2392a43f27) | Apr 14, 2020 |
| Gigabyte      | G31M-S2C                    | [50809e26ed](https://linux-hardware.org/?probe=50809e26ed) | Apr 14, 2020 |
| MSI           | MS-7309                     | [598ba6983d](https://linux-hardware.org/?probe=598ba6983d) | Apr 14, 2020 |
| Unknown       | Unknown                     | [6e2105feb5](https://linux-hardware.org/?probe=6e2105feb5) | Apr 03, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b3c0d80908](https://linux-hardware.org/?probe=b3c0d80908) | Mar 26, 2020 |
| HP            | 3048h                       | [6b07a41174](https://linux-hardware.org/?probe=6b07a41174) | Mar 22, 2020 |
| ASRock        | H61M-VG4                    | [9a17b3a770](https://linux-hardware.org/?probe=9a17b3a770) | Mar 21, 2020 |
| MSI           | K9N6PGM2-V2                 | [68013dac14](https://linux-hardware.org/?probe=68013dac14) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [df4df13e54](https://linux-hardware.org/?probe=df4df13e54) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [12b38c9ebd](https://linux-hardware.org/?probe=12b38c9ebd) | Mar 16, 2020 |
| Intel         | DH61WW AAG23116-302         | [239a155579](https://linux-hardware.org/?probe=239a155579) | Feb 22, 2020 |
| ASUSTek       | PRIME H310-PLUS             | [c59fbe99a2](https://linux-hardware.org/?probe=c59fbe99a2) | Feb 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | [8f38f0a1e3](https://linux-hardware.org/?probe=8f38f0a1e3) | Jan 20, 2020 |
| Dell          | 0P301D A00                  | [298fac1e53](https://linux-hardware.org/?probe=298fac1e53) | Jan 03, 2020 |
| ASRock        | G41M-VS3                    | [c4c975b9f9](https://linux-hardware.org/?probe=c4c975b9f9) | Dec 29, 2019 |
| Unknown       | GSUO H61V10C                | [96d964a1d9](https://linux-hardware.org/?probe=96d964a1d9) | Dec 23, 2019 |
| Pegatron      | 2AAE                        | [04a6d42a9c](https://linux-hardware.org/?probe=04a6d42a9c) | Dec 16, 2019 |
| Pegatron      | 2AAE                        | [e142be5f58](https://linux-hardware.org/?probe=e142be5f58) | Dec 16, 2019 |
| ASRock        | H55M                        | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| MSI           | MS-7309                     | [2e6203af14](https://linux-hardware.org/?probe=2e6203af14) | Oct 09, 2019 |
| ASUSTek       | H110M-R                     | [d98faab3bc](https://linux-hardware.org/?probe=d98faab3bc) | Oct 09, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3181aa4496](https://linux-hardware.org/?probe=3181aa4496) | Sep 02, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f063afeba7](https://linux-hardware.org/?probe=f063afeba7) | Aug 28, 2019 |
| HP            | ProLiant ML115 G1           | [8f0d70a883](https://linux-hardware.org/?probe=8f0d70a883) | Jul 29, 2019 |
| Dell          | OptiPlex GX260              | [6c061a7a15](https://linux-hardware.org/?probe=6c061a7a15) | Jul 23, 2019 |
| ASUSTek       | H81M-K                      | [b124f401f6](https://linux-hardware.org/?probe=b124f401f6) | Jul 17, 2019 |
| Intel         | DH55HC AAE70933-501         | [3462cd0ccd](https://linux-hardware.org/?probe=3462cd0ccd) | Jul 07, 2019 |
| MSI           | MS-7191                     | [d753273d7b](https://linux-hardware.org/?probe=d753273d7b) | Jul 03, 2019 |
| Dell          | 0RY206                      | [aed7ab6e58](https://linux-hardware.org/?probe=aed7ab6e58) | Jun 28, 2019 |
| Gigabyte      | H81M-H                      | [bebf195e43](https://linux-hardware.org/?probe=bebf195e43) | Jun 18, 2019 |
| ASRock        | K8Upgrade-VM800             | [83cccbaf1a](https://linux-hardware.org/?probe=83cccbaf1a) | Jun 03, 2019 |
| ASRock        | G965M-S                     | [30b8a56200](https://linux-hardware.org/?probe=30b8a56200) | May 30, 2019 |
| Dell          | 0TT708 A01                  | [b732db0128](https://linux-hardware.org/?probe=b732db0128) | May 24, 2019 |
| Dell          | 0TT708 A01                  | [fbe3c00bb0](https://linux-hardware.org/?probe=fbe3c00bb0) | May 24, 2019 |
| Unknown       | 775i65G                     | [0b6fd94458](https://linux-hardware.org/?probe=0b6fd94458) | May 19, 2019 |
| Unknown       | 775i65G                     | [2b8a659310](https://linux-hardware.org/?probe=2b8a659310) | May 18, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [29cf71291b](https://linux-hardware.org/?probe=29cf71291b) | Apr 21, 2019 |
| Biostar       | A55MLV                      | [38fd682351](https://linux-hardware.org/?probe=38fd682351) | Apr 19, 2019 |
| HP            | 0A60h                       | [c59eb70baf](https://linux-hardware.org/?probe=c59eb70baf) | Apr 11, 2019 |
| HP            | 0A60h                       | [bd74dccea9](https://linux-hardware.org/?probe=bd74dccea9) | Apr 10, 2019 |
| ASUSTek       | H81M-K                      | [c5178f5550](https://linux-hardware.org/?probe=c5178f5550) | Apr 04, 2019 |
| ASUSTek       | H81M-K                      | [ef3d04377e](https://linux-hardware.org/?probe=ef3d04377e) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [be751979a7](https://linux-hardware.org/?probe=be751979a7) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [b9c1d97ec1](https://linux-hardware.org/?probe=b9c1d97ec1) | Apr 01, 2019 |
| Biostar       | A55MLV                      | [138e3baa2d](https://linux-hardware.org/?probe=138e3baa2d) | Mar 29, 2019 |
| ASUSTek       | H81M-K                      | [d3f5c5ac28](https://linux-hardware.org/?probe=d3f5c5ac28) | Mar 29, 2019 |
| Intel         | DH61CR AAG14064-207         | [2c44dea441](https://linux-hardware.org/?probe=2c44dea441) | Mar 17, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [8d9fa49be1](https://linux-hardware.org/?probe=8d9fa49be1) | Feb 09, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [5dcbf55671](https://linux-hardware.org/?probe=5dcbf55671) | Feb 09, 2019 |
| ASRock        | Wolfdale1333-D667           | [f67c3262d4](https://linux-hardware.org/?probe=f67c3262d4) | Dec 10, 2018 |
| ASRock        | Wolfdale1333-D667           | [06bcad286b](https://linux-hardware.org/?probe=06bcad286b) | Nov 18, 2018 |
| Pegatron      | 2A73h                       | [9ab888ea4f](https://linux-hardware.org/?probe=9ab888ea4f) | Jun 19, 2018 |
| HP            | 2ADE                        | [af28bb9a2f](https://linux-hardware.org/?probe=af28bb9a2f) | Dec 01, 2017 |
| HP            | 2ADE                        | [a2ab5f4392](https://linux-hardware.org/?probe=a2ab5f4392) | Dec 01, 2017 |
| HP            | 0A54h                       | [1f795e5896](https://linux-hardware.org/?probe=1f795e5896) | Jun 29, 2017 |
| HP            | 0A54h                       | [ef67a7d651](https://linux-hardware.org/?probe=ef67a7d651) | Feb 05, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 33       | 12.79%  |
| Ubuntu 18.04        | 29       | 11.24%  |
| OpenMandriva 4.3    | 12       | 4.65%   |
| Ubuntu 22.04        | 9        | 3.49%   |
| Linux Mint 20.3     | 8        | 3.1%    |
| Linux Mint 20.2     | 8        | 3.1%    |
| KDE neon 20.04      | 7        | 2.71%   |
| Zorin 15            | 6        | 2.33%   |
| OpenMandriva 4.2    | 6        | 2.33%   |
| ArcoLinux Rolling   | 6        | 2.33%   |
| Linux Mint 19.3     | 5        | 1.94%   |
| Fedora 37           | 5        | 1.94%   |
| Fedora 35           | 5        | 1.94%   |
| Debian 11           | 5        | 1.94%   |
| Arch Rolling        | 5        | 1.94%   |
| Xubuntu 20.04       | 4        | 1.55%   |
| Zorin 16            | 3        | 1.16%   |
| Zorin 12            | 3        | 1.16%   |
| Ubuntu 19.04        | 3        | 1.16%   |
| ROSA R11            | 3        | 1.16%   |
| ROSA 12.2           | 3        | 1.16%   |
| OpenMandriva 23.01  | 3        | 1.16%   |
| Nobara 36           | 3        | 1.16%   |
| Manjaro             | 3        | 1.16%   |
| Kubuntu 20.04       | 3        | 1.16%   |
| KDE neon 22.04      | 3        | 1.16%   |
| Fedora 36           | 3        | 1.16%   |
| Fedora 32           | 3        | 1.16%   |
| Elementary 6.1      | 3        | 1.16%   |
| Arch                | 3        | 1.16%   |
| Xubuntu 22.04       | 2        | 0.78%   |
| Ubuntu Unity 16.04  | 2        | 0.78%   |
| Ubuntu Budgie 20.04 | 2        | 0.78%   |
| Ubuntu 19.10        | 2        | 0.78%   |
| ROSA R10            | 2        | 0.78%   |
| OpenMandriva 4.50   | 2        | 0.78%   |
| Manjaro 21.0.3      | 2        | 0.78%   |
| Linux Mint 21.1     | 2        | 0.78%   |
| Linux Mint 20       | 2        | 0.78%   |
| Fedora 33           | 2        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 77       | 31.17%  |
| Linux Mint    | 27       | 10.93%  |
| OpenMandriva  | 23       | 9.31%   |
| Fedora        | 18       | 7.29%   |
| Zorin         | 12       | 4.86%   |
| KDE neon      | 11       | 4.45%   |
| ROSA          | 9        | 3.64%   |
| Arch          | 8        | 3.24%   |
| Xubuntu       | 7        | 2.83%   |
| Debian        | 7        | 2.83%   |
| Manjaro       | 6        | 2.43%   |
| ArcoLinux     | 6        | 2.43%   |
| Kubuntu       | 4        | 1.62%   |
| Elementary    | 4        | 1.62%   |
| Ubuntu Unity  | 3        | 1.21%   |
| Pop!_OS       | 3        | 1.21%   |
| Nobara        | 3        | 1.21%   |
| Lubuntu       | 3        | 1.21%   |
| Ubuntu Budgie | 2        | 0.81%   |
| openSUSE      | 2        | 0.81%   |
| Endless       | 2        | 0.81%   |
| BlackPanther  | 2        | 0.81%   |
| Xero          | 1        | 0.4%    |
| Rocky Linux   | 1        | 0.4%    |
| Reborn OS     | 1        | 0.4%    |
| MX            | 1        | 0.4%    |
| LMDE          | 1        | 0.4%    |
| Kali          | 1        | 0.4%    |
| Deepin        | 1        | 0.4%    |
| CentOS        | 1        | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 11       | 3.93%   |
| 5.4.0-42-generic                   | 7        | 2.5%    |
| 5.10.14-desktop-1omv4002           | 6        | 2.14%   |
| 5.19.0-35-generic                  | 5        | 1.79%   |
| 5.15.0-56-generic                  | 5        | 1.79%   |
| 5.4.0-72-generic                   | 4        | 1.43%   |
| 5.4.0-58-generic                   | 4        | 1.43%   |
| 5.0.0-32-generic                   | 4        | 1.43%   |
| 6.1.1-desktop-1omv2290             | 3        | 1.07%   |
| 5.4.0-48-generic                   | 3        | 1.07%   |
| 5.4.0-45-generic                   | 3        | 1.07%   |
| 5.4.0-122-generic                  | 3        | 1.07%   |
| 5.15.0-67-generic                  | 3        | 1.07%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3        | 1.07%   |
| 4.18.0-16-generic                  | 3        | 1.07%   |
| 4.15.0-54-generic                  | 3        | 1.07%   |
| 6.1.18-200.fc37.x86_64             | 2        | 0.71%   |
| 5.8.0-48-generic                   | 2        | 0.71%   |
| 5.8.0-43-generic                   | 2        | 0.71%   |
| 5.4.0-97-generic                   | 2        | 0.71%   |
| 5.4.0-88-generic                   | 2        | 0.71%   |
| 5.4.0-70-generic                   | 2        | 0.71%   |
| 5.4.0-60-generic                   | 2        | 0.71%   |
| 5.4.0-52-generic                   | 2        | 0.71%   |
| 5.4.0-47-generic                   | 2        | 0.71%   |
| 5.4.0-40-generic                   | 2        | 0.71%   |
| 5.4.0-37-generic                   | 2        | 0.71%   |
| 5.4.0-31-generic                   | 2        | 0.71%   |
| 5.4.0-144-generic                  | 2        | 0.71%   |
| 5.4.0-125-generic                  | 2        | 0.71%   |
| 5.4.0-121-generic                  | 2        | 0.71%   |
| 5.4.0-107-generic                  | 2        | 0.71%   |
| 5.3.0-59-generic                   | 2        | 0.71%   |
| 5.3.0-46-generic                   | 2        | 0.71%   |
| 5.3.0-42-generic                   | 2        | 0.71%   |
| 5.15.12-200.fc35.x86_64            | 2        | 0.71%   |
| 5.15.0-53-generic                  | 2        | 0.71%   |
| 5.15.0-48-generic                  | 2        | 0.71%   |
| 5.15.0-46-generic                  | 2        | 0.71%   |
| 5.15.0-43-generic                  | 2        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 62       | 23.48%  |
| 5.15.0  | 22       | 8.33%   |
| 4.15.0  | 16       | 6.06%   |
| 5.16.7  | 11       | 4.17%   |
| 5.0.0   | 11       | 4.17%   |
| 5.3.0   | 10       | 3.79%   |
| 5.13.0  | 10       | 3.79%   |
| 5.8.0   | 8        | 3.03%   |
| 4.18.0  | 8        | 3.03%   |
| 5.19.0  | 7        | 2.65%   |
| 5.11.0  | 6        | 2.27%   |
| 5.10.14 | 6        | 2.27%   |
| 6.1.1   | 4        | 1.52%   |
| 5.10.0  | 4        | 1.52%   |
| 5.8.5   | 3        | 1.14%   |
| 5.8.18  | 3        | 1.14%   |
| 5.12.4  | 3        | 1.14%   |
| 5.10.74 | 3        | 1.14%   |
| 6.1.18  | 2        | 0.76%   |
| 6.0.10  | 2        | 0.76%   |
| 5.15.12 | 2        | 0.76%   |
| 5.14.1  | 2        | 0.76%   |
| 5.13.19 | 2        | 0.76%   |
| 4.19.0  | 2        | 0.76%   |
| 4.18.16 | 2        | 0.76%   |
| 6.2.8   | 1        | 0.38%   |
| 6.1.9   | 1        | 0.38%   |
| 6.1.6   | 1        | 0.38%   |
| 6.1.15  | 1        | 0.38%   |
| 6.1.11  | 1        | 0.38%   |
| 6.1.10  | 1        | 0.38%   |
| 6.0.7   | 1        | 0.38%   |
| 6.0.6   | 1        | 0.38%   |
| 6.0.0   | 1        | 0.38%   |
| 5.9.3   | 1        | 0.38%   |
| 5.9.0   | 1        | 0.38%   |
| 5.8.4   | 1        | 0.38%   |
| 5.7.12  | 1        | 0.38%   |
| 5.6.12  | 1        | 0.38%   |
| 5.6.0   | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 65       | 25%     |
| 5.15    | 26       | 10%     |
| 5.10    | 19       | 7.31%   |
| 4.15    | 16       | 6.15%   |
| 5.8     | 15       | 5.77%   |
| 5.16    | 15       | 5.77%   |
| 5.13    | 12       | 4.62%   |
| 5.3     | 11       | 4.23%   |
| 5.0     | 11       | 4.23%   |
| 4.18    | 10       | 3.85%   |
| 6.1     | 9        | 3.46%   |
| 5.19    | 7        | 2.69%   |
| 5.11    | 7        | 2.69%   |
| 5.14    | 6        | 2.31%   |
| 6.0     | 5        | 1.92%   |
| 5.12    | 5        | 1.92%   |
| 4.9     | 4        | 1.54%   |
| 5.17    | 3        | 1.15%   |
| 5.9     | 2        | 0.77%   |
| 5.6     | 2        | 0.77%   |
| 5.18    | 2        | 0.77%   |
| 4.19    | 2        | 0.77%   |
| 6.2     | 1        | 0.38%   |
| 5.7     | 1        | 0.38%   |
| 5.2     | 1        | 0.38%   |
| 4.12    | 1        | 0.38%   |
| 4.10    | 1        | 0.38%   |
| 4.1     | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 238      | 97.54%  |
| i686   | 6        | 2.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| GNOME        | 97       | 39.27%  |
| KDE5         | 49       | 19.84%  |
| Unknown      | 25       | 10.12%  |
| X-Cinnamon   | 20       | 8.1%    |
| XFCE         | 14       | 5.67%   |
| KDE          | 10       | 4.05%   |
| Pantheon     | 4        | 1.62%   |
| MATE         | 4        | 1.62%   |
| KDE4         | 4        | 1.62%   |
| Cinnamon     | 4        | 1.62%   |
| Unity        | 3        | 1.21%   |
| LXQt         | 3        | 1.21%   |
| i3           | 3        | 1.21%   |
| Deepin       | 2        | 0.81%   |
| Budgie       | 2        | 0.81%   |
| ubuntu=GNOME | 1        | 0.4%    |
| LXDE         | 1        | 0.4%    |
| awesome      | 1        | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 198      | 79.84%  |
| Wayland | 31       | 12.5%   |
| Unknown | 14       | 5.65%   |
| Tty     | 5        | 2.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 133      | 53.41%  |
| SDDM    | 39       | 15.66%  |
| GDM     | 29       | 11.65%  |
| LightDM | 22       | 8.84%   |
| GDM3    | 15       | 6.02%   |
| TDM     | 6        | 2.41%   |
| KDM     | 4        | 1.61%   |
| SLiM    | 1        | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CO   | 129      | 51.6%   |
| en_US   | 61       | 24.4%   |
| Unknown | 34       | 13.6%   |
| es_ES   | 17       | 6.8%    |
| es_MX   | 3        | 1.2%    |
| pt_BR   | 2        | 0.8%    |
| en_GB   | 2        | 0.8%    |
| C       | 2        | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 153      | 62.7%   |
| EFI  | 91       | 37.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 187      | 76.02%  |
| Overlay | 24       | 9.76%   |
| Btrfs   | 24       | 9.76%   |
| Unknown | 5        | 2.03%   |
| Xfs     | 4        | 1.63%   |
| Zfs     | 1        | 0.41%   |
| Ext2    | 1        | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 133      | 53.85%  |
| GPT     | 72       | 29.15%  |
| MBR     | 42       | 17%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 206      | 82.4%   |
| Yes       | 44       | 17.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 59.18%  |
| Yes       | 100      | 40.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 49       | 20.08%  |
| Gigabyte Technology | 44       | 18.03%  |
| ASRock              | 29       | 11.89%  |
| MSI                 | 28       | 11.48%  |
| Hewlett-Packard     | 25       | 10.25%  |
| Intel               | 13       | 5.33%   |
| Dell                | 13       | 5.33%   |
| Lenovo              | 9        | 3.69%   |
| ECS                 | 6        | 2.46%   |
| Biostar             | 6        | 2.46%   |
| Pegatron            | 5        | 2.05%   |
| Unknown             | 5        | 2.05%   |
| Foxconn             | 4        | 1.64%   |
| PCSMART             | 2        | 0.82%   |
| Supermicro          | 1        | 0.41%   |
| PCChips             | 1        | 0.41%   |
| Hardkernel          | 1        | 0.41%   |
| BESSTAR Tech        | 1        | 0.41%   |
| Apple               | 1        | 0.41%   |
| Acer                | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 6        | 2.46%   |
| Gigabyte B450M DS3H                  | 5        | 2.05%   |
| MSI MS-7817                          | 4        | 1.64%   |
| MSI MS-7309                          | 4        | 1.64%   |
| Gigabyte H81M-H                      | 4        | 1.64%   |
| ASUS All Series                      | 4        | 1.64%   |
| HP ProDesk 400 G1 SFF                | 3        | 1.23%   |
| Gigabyte GA-78LMT-USB3               | 3        | 1.23%   |
| Gigabyte G31M-ES2C                   | 3        | 1.23%   |
| ECS G31T-M7                          | 3        | 1.23%   |
| ASUS ROG STRIX B550-F GAMING         | 3        | 1.23%   |
| ASUS M5A78L-M/USB3                   | 3        | 1.23%   |
| ASRock Wolfdale1333-D667             | 3        | 1.23%   |
| ASRock G965M-S                       | 3        | 1.23%   |
| ASRock G41M-VS3                      | 3        | 1.23%   |
| MSI MS-7C37                          | 2        | 0.82%   |
| Intel H61                            | 2        | 0.82%   |
| HP Compaq Pro 4300 SFF PC            | 2        | 0.82%   |
| HP Compaq dc7700 Small Form Factor   | 2        | 0.82%   |
| Gigabyte X399 AORUS PRO              | 2        | 0.82%   |
| Gigabyte B550 AORUS PRO AC           | 2        | 0.82%   |
| Gigabyte A520M DS3H                  | 2        | 0.82%   |
| ECS H81H3-M4                         | 2        | 0.82%   |
| Dell Vostro 430                      | 2        | 0.82%   |
| Biostar H61MHV                       | 2        | 0.82%   |
| ASUS SABERTOOTH 990FX R2.0           | 2        | 0.82%   |
| ASUS PRIME H410M-E                   | 2        | 0.82%   |
| ASUS PRIME H310M-E                   | 2        | 0.82%   |
| ASUS PRIME A320M-K                   | 2        | 0.82%   |
| ASRock Z77 Extreme4                  | 2        | 0.82%   |
| ASRock H110M-HDV R3.0                | 2        | 0.82%   |
| Supermicro X7DA8                     | 1        | 0.41%   |
| Pegatron p6740la                     | 1        | 0.41%   |
| Pegatron CQ2722LA                    | 1        | 0.41%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.41%   |
| Pegatron 23-b030la                   | 1        | 0.41%   |
| Pegatron 100-5015la                  | 1        | 0.41%   |
| PCSMART 6.0                          | 1        | 0.41%   |
| PCChips P17G                         | 1        | 0.41%   |
| MSI MS-7C79                          | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 14       | 5.74%   |
| HP Compaq                | 12       | 4.92%   |
| Lenovo ThinkCentre       | 7        | 2.87%   |
| ASUS ROG                 | 7        | 2.87%   |
| Dell OptiPlex            | 6        | 2.46%   |
| ASUS TUF                 | 6        | 2.46%   |
| Unknown                  | 6        | 2.46%   |
| HP ProDesk               | 5        | 2.05%   |
| Gigabyte B450M           | 5        | 2.05%   |
| MSI MS-7817              | 4        | 1.64%   |
| MSI MS-7309              | 4        | 1.64%   |
| HP ProLiant              | 4        | 1.64%   |
| Gigabyte H81M-H          | 4        | 1.64%   |
| Gigabyte B550            | 4        | 1.64%   |
| ASUS All                 | 4        | 1.64%   |
| Gigabyte X399            | 3        | 1.23%   |
| Gigabyte GA-78LMT-USB3   | 3        | 1.23%   |
| Gigabyte G31M-ES2C       | 3        | 1.23%   |
| ECS G31T-M7              | 3        | 1.23%   |
| Dell Vostro              | 3        | 1.23%   |
| ASUS M5A78L-M            | 3        | 1.23%   |
| ASRock Wolfdale1333-D667 | 3        | 1.23%   |
| ASRock G965M-S           | 3        | 1.23%   |
| ASRock G41M-VS3          | 3        | 1.23%   |
| MSI MS-7C37              | 2        | 0.82%   |
| Intel H61                | 2        | 0.82%   |
| Intel DH55HC             | 2        | 0.82%   |
| Gigabyte B550M           | 2        | 0.82%   |
| Gigabyte A520M           | 2        | 0.82%   |
| ECS H81H3-M4             | 2        | 0.82%   |
| Biostar H61MHV           | 2        | 0.82%   |
| ASUS SABERTOOTH          | 2        | 0.82%   |
| ASUS M4A87TD             | 2        | 0.82%   |
| ASRock Z77               | 2        | 0.82%   |
| ASRock H110M-HDV         | 2        | 0.82%   |
| Supermicro X7DA8         | 1        | 0.41%   |
| Pegatron p6740la         | 1        | 0.41%   |
| Pegatron CQ2722LA        | 1        | 0.41%   |
| Pegatron Compaq          | 1        | 0.41%   |
| Pegatron 23-b030la       | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 27       | 11.07%  |
| 2010 | 26       | 10.66%  |
| 2013 | 23       | 9.43%   |
| 2020 | 21       | 8.61%   |
| 2018 | 20       | 8.2%    |
| 2011 | 20       | 8.2%    |
| 2008 | 14       | 5.74%   |
| 2017 | 13       | 5.33%   |
| 2009 | 13       | 5.33%   |
| 2019 | 12       | 4.92%   |
| 2007 | 11       | 4.51%   |
| 2014 | 10       | 4.1%    |
| 2006 | 9        | 3.69%   |
| 2021 | 7        | 2.87%   |
| 2016 | 6        | 2.46%   |
| 2015 | 6        | 2.46%   |
| 2022 | 3        | 1.23%   |
| 2005 | 2        | 0.82%   |
| 2003 | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 244      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 239      | 97.55%  |
| Enabled  | 6        | 2.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 244      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 56       | 22.76%  |
| 3.01-4.0    | 54       | 21.95%  |
| 4.01-8.0    | 46       | 18.7%   |
| 16.01-24.0  | 39       | 15.85%  |
| 32.01-64.0  | 21       | 8.54%   |
| 1.01-2.0    | 17       | 6.91%   |
| 24.01-32.0  | 4        | 1.63%   |
| 2.01-3.0    | 4        | 1.63%   |
| 64.01-256.0 | 3        | 1.22%   |
| 0.51-1.0    | 2        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 97       | 36.74%  |
| 2.01-3.0  | 61       | 23.11%  |
| 3.01-4.0  | 45       | 17.05%  |
| 4.01-8.0  | 34       | 12.88%  |
| 0.51-1.0  | 19       | 7.2%    |
| 8.01-16.0 | 6        | 2.27%   |
| 0.01-0.5  | 2        | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 126      | 50.2%   |
| 2      | 76       | 30.28%  |
| 3      | 28       | 11.16%  |
| 4      | 13       | 5.18%   |
| 5      | 4        | 1.59%   |
| 6      | 2        | 0.8%    |
| 8      | 1        | 0.4%    |
| 0      | 1        | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 144      | 58.54%  |
| Yes       | 102      | 41.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 244      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 151      | 61.13%  |
| Yes       | 96       | 38.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 200      | 80.97%  |
| Yes       | 47       | 19.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Colombia | 244      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Bogotá              | 99       | 39.92%  |
| Medellín            | 48       | 19.35%  |
| Santiago de Cali     | 22       | 8.87%   |
| Bucaramanga          | 11       | 4.44%   |
| Barranquilla         | 9        | 3.63%   |
| Pereira              | 4        | 1.61%   |
| Armenia              | 4        | 1.61%   |
| Villavicencio        | 3        | 1.21%   |
| Valledupar           | 3        | 1.21%   |
| Pasto                | 3        | 1.21%   |
| Ibague               | 3        | 1.21%   |
| Chia                 | 3        | 1.21%   |
| Soledad              | 2        | 0.81%   |
| Santa Marta          | 2        | 0.81%   |
| Palmira              | 2        | 0.81%   |
| Montería            | 2        | 0.81%   |
| Manizales            | 2        | 0.81%   |
| Envigado             | 2        | 0.81%   |
| Cúcuta              | 2        | 0.81%   |
| Calarcá             | 2        | 0.81%   |
| Villagarzon          | 1        | 0.4%    |
| Tunja                | 1        | 0.4%    |
| Tuluá               | 1        | 0.4%    |
| Rionegro             | 1        | 0.4%    |
| Puerto Carreño      | 1        | 0.4%    |
| Popayán             | 1        | 0.4%    |
| Mompos               | 1        | 0.4%    |
| La Loma              | 1        | 0.4%    |
| Jamundi              | 1        | 0.4%    |
| Ipiales              | 1        | 0.4%    |
| El Socorro           | 1        | 0.4%    |
| El Carmen de Bolivar | 1        | 0.4%    |
| Donmatias            | 1        | 0.4%    |
| Choachi              | 1        | 0.4%    |
| Cartagena            | 1        | 0.4%    |
| Buenaventura         | 1        | 0.4%    |
| Bello                | 1        | 0.4%    |
| Barrio San Luis      | 1        | 0.4%    |
| Barbosa              | 1        | 0.4%    |
| Agua de Dios         | 1        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 81       | 106    | 20.15%  |
| Seagate                   | 63       | 92     | 15.67%  |
| Hitachi                   | 44       | 54     | 10.95%  |
| Toshiba                   | 43       | 53     | 10.7%   |
| Samsung Electronics       | 32       | 40     | 7.96%   |
| Kingston                  | 27       | 38     | 6.72%   |
| Maxtor                    | 16       | 17     | 3.98%   |
| A-DATA Technology         | 16       | 21     | 3.98%   |
| Crucial                   | 12       | 13     | 2.99%   |
| SanDisk                   | 11       | 13     | 2.74%   |
| Phison                    | 5        | 7      | 1.24%   |
| Lexar                     | 5        | 5      | 1.24%   |
| HGST                      | 5        | 6      | 1.24%   |
| XPG                       | 4        | 5      | 1%      |
| Gigabyte Technology       | 4        | 5      | 1%      |
| PNY                       | 3        | 4      | 0.75%   |
| JMicron Technology        | 3        | 3      | 0.75%   |
| Corsair                   | 3        | 4      | 0.75%   |
| XrayDisk                  | 2        | 2      | 0.5%    |
| Unknown                   | 2        | 2      | 0.5%    |
| Transcend                 | 2        | 3      | 0.5%    |
| Team                      | 2        | 2      | 0.5%    |
| Realtek Semiconductor     | 2        | 2      | 0.5%    |
| Fujitsu                   | 2        | 2      | 0.5%    |
| XSTAR                     | 1        | 1      | 0.25%   |
| SUPERSONIC                | 1        | 1      | 0.25%   |
| SK hynix                  | 1        | 2      | 0.25%   |
| Micron/Crucial Technology | 1        | 2      | 0.25%   |
| KingSpec                  | 1        | 1      | 0.25%   |
| KingDian                  | 1        | 1      | 0.25%   |
| KINGBANK                  | 1        | 1      | 0.25%   |
| Intel                     | 1        | 1      | 0.25%   |
| Hewlett-Packard           | 1        | 1      | 0.25%   |
| ExcelStor                 | 1        | 1      | 0.25%   |
| Apple                     | 1        | 1      | 0.25%   |
| ADATA Technology          | 1        | 1      | 0.25%   |
| Unknown                   | 1        | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 19       | 4.4%    |
| Kingston SA400S37240G 240GB SSD     | 9        | 2.08%   |
| Toshiba DT01ACA200 2TB              | 7        | 1.62%   |
| Kingston SA400S37120G 120GB SSD     | 7        | 1.62%   |
| Toshiba HDWD110 1TB                 | 6        | 1.39%   |
| Hitachi HDS721050CLA362 500GB       | 6        | 1.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5        | 1.16%   |
| Toshiba DT01ACA050 500GB            | 5        | 1.16%   |
| Seagate ST500DM002-1BD142 500GB     | 5        | 1.16%   |
| Kingston SV300S37A120G 120GB SSD    | 5        | 1.16%   |
| Hitachi HDS721616PLA380 160GB       | 5        | 1.16%   |
| Crucial CT240BX500SSD1 240GB        | 5        | 1.16%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 4        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 0.93%   |
| Lexar 128GB SSD                     | 4        | 0.93%   |
| A-DATA SU630 240GB SSD              | 4        | 0.93%   |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 0.69%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 0.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 0.69%   |
| Seagate ST3500413AS 500GB           | 3        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB      | 3        | 0.69%   |
| Samsung SSD 850 EVO 250GB           | 3        | 0.69%   |
| Samsung HD322HJ 320GB               | 3        | 0.69%   |
| Maxtor STM3160215AS 160GB           | 3        | 0.69%   |
| A-DATA SU650 120GB SSD              | 3        | 0.69%   |
| XPG NVMe SSD Drive 1024GB           | 2        | 0.46%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD    | 2        | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2        | 0.46%   |
| WDC WD800JD-75MSA3 80GB             | 2        | 0.46%   |
| WDC WD800BD-22MRA1 80GB             | 2        | 0.46%   |
| WDC WD5000AVVS-63ZWB0 500GB         | 2        | 0.46%   |
| WDC WD5000AURX-63UY4Y0 500GB        | 2        | 0.46%   |
| WDC WD5000AAKX-603CA0 500GB         | 2        | 0.46%   |
| WDC WD1200BEVS-60UST0 120GB         | 2        | 0.46%   |
| WDC WD10EZRX-00D8PB0 1TB            | 2        | 0.46%   |
| WDC WD10EZEX-60WN4A0 1TB            | 2        | 0.46%   |
| Toshiba MQ01ABD100 1TB              | 2        | 0.46%   |
| Toshiba DT01ABA200V 2TB             | 2        | 0.46%   |
| Seagate ST4000DM004-2CV104 4TB      | 2        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 69       | 89     | 26.64%  |
| Seagate             | 63       | 91     | 24.32%  |
| Hitachi             | 44       | 54     | 16.99%  |
| Toshiba             | 43       | 53     | 16.6%   |
| Maxtor              | 16       | 17     | 6.18%   |
| Samsung Electronics | 15       | 19     | 5.79%   |
| HGST                | 5        | 6      | 1.93%   |
| Fujitsu             | 2        | 2      | 0.77%   |
| ExcelStor           | 1        | 1      | 0.39%   |
| Apple               | 1        | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 25       | 36     | 24.75%  |
| A-DATA Technology   | 15       | 20     | 14.85%  |
| WDC                 | 13       | 15     | 12.87%  |
| Crucial             | 10       | 11     | 9.9%    |
| Samsung Electronics | 9        | 9      | 8.91%   |
| SanDisk             | 5        | 7      | 4.95%   |
| Lexar               | 5        | 5      | 4.95%   |
| Gigabyte Technology | 3        | 4      | 2.97%   |
| Transcend           | 2        | 3      | 1.98%   |
| PNY                 | 2        | 3      | 1.98%   |
| JMicron Technology  | 2        | 2      | 1.98%   |
| Corsair             | 2        | 3      | 1.98%   |
| XSTAR               | 1        | 1      | 0.99%   |
| Unknown             | 1        | 1      | 0.99%   |
| Team                | 1        | 1      | 0.99%   |
| SK hynix            | 1        | 2      | 0.99%   |
| Seagate             | 1        | 1      | 0.99%   |
| KingSpec            | 1        | 1      | 0.99%   |
| KingDian            | 1        | 1      | 0.99%   |
| Unknown             | 1        | 1      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 191      | 333    | 58.41%  |
| SSD     | 92       | 127    | 28.13%  |
| NVMe    | 40       | 50     | 12.23%  |
| Unknown | 4        | 4      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 225      | 458    | 83.03%  |
| NVMe | 40       | 50     | 14.76%  |
| SAS  | 6        | 6      | 2.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 168      | 268    | 55.81%  |
| 0.51-1.0   | 95       | 136    | 31.56%  |
| 1.01-2.0   | 25       | 34     | 8.31%   |
| 2.01-3.0   | 5        | 5      | 1.66%   |
| 4.01-10.0  | 5        | 7      | 1.66%   |
| 3.01-4.0   | 3        | 10     | 1%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 63       | 24.42%  |
| 501-1000       | 48       | 18.6%   |
| 251-500        | 43       | 16.67%  |
| 1001-2000      | 27       | 10.47%  |
| 1-20           | 22       | 8.53%   |
| 51-100         | 22       | 8.53%   |
| More than 3000 | 10       | 3.88%   |
| 2001-3000      | 9        | 3.49%   |
| Unknown        | 8        | 3.1%    |
| 21-50          | 6        | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 104      | 39.39%  |
| 21-50          | 38       | 14.39%  |
| 101-250        | 34       | 12.88%  |
| 51-100         | 32       | 12.12%  |
| 251-500        | 17       | 6.44%   |
| 501-1000       | 15       | 5.68%   |
| 1001-2000      | 9        | 3.41%   |
| Unknown        | 8        | 3.03%   |
| More than 3000 | 4        | 1.52%   |
| 2001-3000      | 3        | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 2        | 2      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 3.33%   |
| Hitachi HDS721050CLA362 500GB         | 2        | 2      | 3.33%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1        | 2      | 1.67%   |
| WDC WD800JD-75MSA3 80GB               | 1        | 1      | 1.67%   |
| WDC WD800JD-60LSA0 80GB               | 1        | 1      | 1.67%   |
| WDC WD800BD-22MRA1 80GB               | 1        | 1      | 1.67%   |
| WDC WD6400AAKS-65Z7B0 640GB           | 1        | 1      | 1.67%   |
| WDC WD5000AAKS-08V0A0 500GB           | 1        | 1      | 1.67%   |
| WDC WD3200AVJS-63B6A0 320GB           | 1        | 1      | 1.67%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 1        | 1      | 1.67%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1        | 1      | 1.67%   |
| WDC WD20EZRX-00DC0B0 2TB              | 1        | 1      | 1.67%   |
| WDC WD2003FYPS-27W9B0 2TB             | 1        | 1      | 1.67%   |
| WDC WD1600AAJS-75M0A0 160GB           | 1        | 1      | 1.67%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1        | 1      | 1.67%   |
| WDC WD10EALX-008EA0 1TB               | 1        | 1      | 1.67%   |
| WDC WD10EACS-00D6B1 1TB               | 1        | 1      | 1.67%   |
| WDC WD1001FAES-75W7A0 1TB             | 1        | 1      | 1.67%   |
| Toshiba HDWD110 1TB                   | 1        | 1      | 1.67%   |
| Toshiba DT01ABA200V 2TB               | 1        | 1      | 1.67%   |
| Seagate ST9250315AS 250GB             | 1        | 1      | 1.67%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1        | 1      | 1.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1      | 1.67%   |
| Seagate ST3320613AS 320GB             | 1        | 3      | 1.67%   |
| Seagate ST3320311CS 320GB             | 1        | 2      | 1.67%   |
| Seagate ST3250820AS 250GB             | 1        | 1      | 1.67%   |
| Seagate ST3120026AS 120GB             | 1        | 1      | 1.67%   |
| Seagate ST2000DM001-1CH164 2TB        | 1        | 1      | 1.67%   |
| Seagate ST1000VM002-1CT162 1TB        | 1        | 1      | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1        | 1      | 1.67%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 2      | 1.67%   |
| Seagate ST1000DM003-1SB102 1TB        | 1        | 1      | 1.67%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 1.67%   |
| Seagate ST1000DM003-1CH162 1TB        | 1        | 1      | 1.67%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 1.67%   |
| Samsung Electronics HM250HI 250GB     | 1        | 1      | 1.67%   |
| Samsung Electronics HD502HJ 500GB     | 1        | 1      | 1.67%   |
| Samsung Electronics HD322HJ 320GB     | 1        | 1      | 1.67%   |
| Maxtor STM3160211AS 160GB             | 1        | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 22     | 27.45%  |
| WDC                 | 12       | 17     | 23.53%  |
| Hitachi             | 11       | 13     | 21.57%  |
| Samsung Electronics | 4        | 4      | 7.84%   |
| Maxtor              | 3        | 3      | 5.88%   |
| Toshiba             | 2        | 2      | 3.92%   |
| Kingston            | 1        | 1      | 1.96%   |
| HGST                | 1        | 1      | 1.96%   |
| Fujitsu             | 1        | 1      | 1.96%   |
| Crucial             | 1        | 1      | 1.96%   |
| A-DATA Technology   | 1        | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 22     | 30.43%  |
| WDC                 | 11       | 15     | 23.91%  |
| Hitachi             | 11       | 13     | 23.91%  |
| Samsung Electronics | 3        | 3      | 6.52%   |
| Maxtor              | 3        | 3      | 6.52%   |
| Toshiba             | 2        | 2      | 4.35%   |
| HGST                | 1        | 1      | 2.17%   |
| Fujitsu             | 1        | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 42       | 60     | 89.36%  |
| SSD  | 4        | 5      | 8.51%   |
| NVMe | 1        | 1      | 2.13%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| Maxtor STM380211AS 80GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| Maxtor | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 151      | 314    | 54.51%  |
| Works    | 78       | 133    | 28.16%  |
| Malfunc  | 47       | 66     | 16.97%  |
| Failed   | 1        | 1      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 145      | 47.7%   |
| AMD                         | 83       | 27.3%   |
| Nvidia                      | 14       | 4.61%   |
| Samsung Electronics         | 10       | 3.29%   |
| ASMedia Technology          | 9        | 2.96%   |
| SanDisk                     | 8        | 2.63%   |
| Phison Electronics          | 7        | 2.3%    |
| VIA Technologies            | 5        | 1.64%   |
| Realtek Semiconductor       | 4        | 1.32%   |
| ADATA Technology            | 4        | 1.32%   |
| JMicron Technology          | 3        | 0.99%   |
| Silicon Motion              | 2        | 0.66%   |
| Micron/Crucial Technology   | 2        | 0.66%   |
| Marvell Technology Group    | 2        | 0.66%   |
| Kingston Technology Company | 2        | 0.66%   |
| INNOGRIT                    | 2        | 0.66%   |
| Micron Technology           | 1        | 0.33%   |
| Hewlett-Packard             | 1        | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35       | 8.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 27       | 6.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23       | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23       | 5.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 4.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 3.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 3.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14       | 3.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 2.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 2.65%   |
| Nvidia MCP61 SATA Controller                                                            | 10       | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 2.41%   |
| Nvidia MCP61 IDE                                                                        | 9        | 2.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 1.93%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 1.69%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 1.69%   |
| Phison E12 NVMe Controller                                                              | 5        | 1.2%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.2%    |
| AMD FCH SATA Controller D                                                               | 5        | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 0.96%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.72%   |
| Realtek NVMe Controller                                                                 | 3        | 0.72%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 3        | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.72%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.72%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.72%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.48%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.48%   |
| SanDisk NVMe Controller                                                                 | 2        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 166      | 53.21%  |
| IDE  | 92       | 29.49%  |
| NVMe | 40       | 12.82%  |
| RAID | 14       | 4.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 146      | 59.84%  |
| AMD    | 98       | 40.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 2.85%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 7        | 2.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 2.44%   |
| AMD FX-8320 Eight-Core Processor            | 6        | 2.44%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 5        | 2.03%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 4        | 1.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.63%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 4        | 1.63%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 4        | 1.63%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 1.63%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.63%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 1.63%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 1.22%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 1.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 1.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 1.22%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 1.22%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 1.22%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 1.22%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.22%   |
| Intel Celeron CPU G1610 @ 2.60GHz           | 3        | 1.22%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.22%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 1.22%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.22%   |
| AMD Phenom II X6 1100T Processor            | 3        | 1.22%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 3        | 1.22%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 2        | 0.81%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2        | 0.81%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.81%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.81%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 0.81%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.81%   |
| Intel Core i5-3470T CPU @ 2.90GHz           | 2        | 0.81%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.81%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 2        | 0.81%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 0.81%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 0.81%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.81%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 40       | 16.26%  |
| AMD Ryzen 5             | 27       | 10.98%  |
| Intel Core i7           | 24       | 9.76%   |
| Intel Core i3           | 19       | 7.72%   |
| AMD FX                  | 14       | 5.69%   |
| AMD Ryzen 7             | 12       | 4.88%   |
| Intel Pentium Dual-Core | 11       | 4.47%   |
| Intel Core 2 Duo        | 9        | 3.66%   |
| Intel Celeron           | 9        | 3.66%   |
| Intel Xeon              | 8        | 3.25%   |
| Intel Pentium Dual      | 7        | 2.85%   |
| AMD Ryzen 3             | 6        | 2.44%   |
| Other                   | 5        | 2.03%   |
| AMD Phenom II X6        | 5        | 2.03%   |
| AMD Athlon II X2        | 5        | 2.03%   |
| AMD Athlon 64 X2        | 5        | 2.03%   |
| Intel Pentium           | 4        | 1.63%   |
| Intel Core 2 Quad       | 3        | 1.22%   |
| Intel Core 2            | 3        | 1.22%   |
| AMD Ryzen Threadripper  | 3        | 1.22%   |
| AMD Phenom              | 3        | 1.22%   |
| AMD Athlon              | 3        | 1.22%   |
| Intel Pentium D         | 2        | 0.81%   |
| Intel Pentium 4         | 2        | 0.81%   |
| AMD Sempron             | 2        | 0.81%   |
| AMD Ryzen 9             | 2        | 0.81%   |
| AMD Phenom II X4        | 2        | 0.81%   |
| AMD A8                  | 2        | 0.81%   |
| AMD A4                  | 2        | 0.81%   |
| Intel Core i9           | 1        | 0.41%   |
| Intel Celeron D         | 1        | 0.41%   |
| Intel Atom              | 1        | 0.41%   |
| AMD Athlon II X3        | 1        | 0.41%   |
| AMD Athlon 64           | 1        | 0.41%   |
| AMD A6                  | 1        | 0.41%   |
| AMD A10                 | 1        | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 85       | 34.84%  |
| 2      | 85       | 34.84%  |
| 6      | 36       | 14.75%  |
| 8      | 14       | 5.74%   |
| 1      | 9        | 3.69%   |
| 3      | 7        | 2.87%   |
| 12     | 4        | 1.64%   |
| 16     | 3        | 1.23%   |
| 10     | 1        | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 240      | 98.36%  |
| 2      | 4        | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 123      | 50%     |
| 1      | 123      | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 240      | 98.36%  |
| Unknown        | 2        | 0.82%   |
| 64-bit         | 1        | 0.41%   |
| 32-bit         | 1        | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 14.23%  |
| 0x306c3    | 20       | 8.13%   |
| 0x206a7    | 17       | 6.91%   |
| 0x306a9    | 15       | 6.1%    |
| 0x1067a    | 14       | 5.69%   |
| 0x08701021 | 11       | 4.47%   |
| 0x08108109 | 10       | 4.07%   |
| 0x06000852 | 10       | 4.07%   |
| 0x6fd      | 9        | 3.66%   |
| 0x506e3    | 6        | 2.44%   |
| 0xa0653    | 5        | 2.03%   |
| 0x906e9    | 5        | 2.03%   |
| 0x10676    | 5        | 2.03%   |
| 0x010000dc | 5        | 2.03%   |
| 0x010000c8 | 5        | 2.03%   |
| 0x906ea    | 4        | 1.63%   |
| 0x0a50000c | 4        | 1.63%   |
| 0xf65      | 3        | 1.22%   |
| 0xa0655    | 3        | 1.22%   |
| 0x6fb      | 3        | 1.22%   |
| 0x20655    | 3        | 1.22%   |
| 0x106e5    | 3        | 1.22%   |
| 0x0800820d | 3        | 1.22%   |
| 0x08001138 | 3        | 1.22%   |
| 0xa0671    | 2        | 0.81%   |
| 0x6f6      | 2        | 0.81%   |
| 0x20652    | 2        | 0.81%   |
| 0x08001137 | 2        | 0.81%   |
| 0x06001119 | 2        | 0.81%   |
| 0x03000027 | 2        | 0.81%   |
| 0x01000083 | 2        | 0.81%   |
| 0xf64      | 1        | 0.41%   |
| 0xf49      | 1        | 0.41%   |
| 0xf27      | 1        | 0.41%   |
| 0x906ed    | 1        | 0.41%   |
| 0x906eb    | 1        | 0.41%   |
| 0x90672    | 1        | 0.41%   |
| 0x806c2    | 1        | 0.41%   |
| 0x706a1    | 1        | 0.41%   |
| 0x6f2      | 1        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 21       | 8.57%   |
| Penryn        | 21       | 8.57%   |
| Haswell       | 21       | 8.57%   |
| IvyBridge     | 20       | 8.16%   |
| K10           | 18       | 7.35%   |
| Zen+          | 16       | 6.53%   |
| Zen 2         | 15       | 6.12%   |
| Piledriver    | 15       | 6.12%   |
| Core          | 15       | 6.12%   |
| KabyLake      | 12       | 4.9%    |
| Zen 3         | 11       | 4.49%   |
| K8 Hammer     | 9        | 3.67%   |
| CometLake     | 8        | 3.27%   |
| Zen           | 7        | 2.86%   |
| NetBurst      | 7        | 2.86%   |
| Skylake       | 6        | 2.45%   |
| Westmere      | 5        | 2.04%   |
| Nehalem       | 4        | 1.63%   |
| K10 Llano     | 2        | 0.82%   |
| Icelake       | 2        | 0.82%   |
| Bulldozer     | 2        | 0.82%   |
| Unknown       | 2        | 0.82%   |
| TigerLake     | 1        | 0.41%   |
| Steamroller   | 1        | 0.41%   |
| Jaguar        | 1        | 0.41%   |
| Goldmont plus | 1        | 0.41%   |
| Broadwell     | 1        | 0.41%   |
| Bonnell       | 1        | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 92       | 35.66%  |
| AMD                        | 84       | 32.56%  |
| Nvidia                     | 76       | 29.46%  |
| Matrox Electronics Systems | 4        | 1.55%   |
| VIA Technologies           | 2        | 0.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 11       | 4.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 3.8%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 3.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 10       | 3.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 9        | 3.42%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 2.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 2.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.28%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 6        | 2.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 2.28%   |
| Intel HD Graphics 530                                                       | 5        | 1.9%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 1.9%    |
| AMD RS780L [Radeon 3000]                                                    | 5        | 1.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 1.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.52%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 4        | 1.52%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 1.52%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 4        | 1.52%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 4        | 1.52%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 1.14%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.14%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.14%   |
| Nvidia GF119 [GeForce GT 610]                                               | 3        | 1.14%   |
| Matrox Electronics Systems MGA G200EH                                       | 3        | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.14%   |
| Intel HD Graphics 630                                                       | 3        | 1.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.14%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 3        | 1.14%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 1.14%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.76%   |
| Nvidia GK208 [GeForce GT 710]                                               | 2        | 0.76%   |
| Nvidia GF106GL [Quadro 2000]                                                | 2        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 0.76%   |
| Intel 82G965 Integrated Graphics Controller                                 | 2        | 0.76%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 84       | 34.15%  |
| 1 x AMD         | 76       | 30.89%  |
| 1 x Nvidia      | 71       | 28.86%  |
| 2 x AMD         | 4        | 1.63%   |
| 1 x Matrox      | 3        | 1.22%   |
| 1 x VIA         | 2        | 0.81%   |
| Intel + Nvidia  | 2        | 0.81%   |
| Intel + AMD     | 2        | 0.81%   |
| Nvidia + Matrox | 1        | 0.41%   |
| AMD + Nvidia    | 1        | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 200      | 81.63%  |
| Proprietary | 35       | 14.29%  |
| Unknown     | 10       | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 105      | 42.68%  |
| 1.01-2.0   | 38       | 15.45%  |
| 0.51-1.0   | 36       | 14.63%  |
| 0.01-0.5   | 33       | 13.41%  |
| 3.01-4.0   | 13       | 5.28%   |
| 7.01-8.0   | 9        | 3.66%   |
| 5.01-6.0   | 5        | 2.03%   |
| 8.01-16.0  | 4        | 1.63%   |
| 2.01-3.0   | 3        | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 69       | 30.8%   |
| Goldstar             | 40       | 17.86%  |
| Hewlett-Packard      | 30       | 13.39%  |
| Dell                 | 18       | 8.04%   |
| Acer                 | 13       | 5.8%    |
| AOC                  | 9        | 4.02%   |
| ViewSonic            | 4        | 1.79%   |
| LG Electronics       | 4        | 1.79%   |
| Unknown              | 3        | 1.34%   |
| RTK                  | 3        | 1.34%   |
| ASUSTek Computer     | 3        | 1.34%   |
| Ancor Communications | 3        | 1.34%   |
| SANYO                | 2        | 0.89%   |
| SAC                  | 2        | 0.89%   |
| NCS                  | 2        | 0.89%   |
| MSI                  | 2        | 0.89%   |
| Envision             | 2        | 0.89%   |
| BenQ                 | 2        | 0.89%   |
| Westinghouse         | 1        | 0.45%   |
| Unknown (XXX)        | 1        | 0.45%   |
| SMC                  | 1        | 0.45%   |
| SKG                  | 1        | 0.45%   |
| Sceptre Tech         | 1        | 0.45%   |
| PEGA                 | 1        | 0.45%   |
| MStar                | 1        | 0.45%   |
| Lenovo               | 1        | 0.45%   |
| KOA                  | 1        | 0.45%   |
| HKC                  | 1        | 0.45%   |
| HannStar             | 1        | 0.45%   |
| DENON                | 1        | 0.45%   |
| AGO                  | 1        | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 5        | 2.15%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 2.15%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                 | 4        | 1.72%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                   | 4        | 1.72%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 3        | 1.29%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 3        | 1.29%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3        | 1.29%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 3        | 1.29%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 3        | 1.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.29%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 3        | 1.29%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.86%   |
| SANYO LCD TV SAN0523 1920x1080 443x249mm 20.0-inch                    | 2        | 0.86%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 2        | 0.86%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.86%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 2        | 0.86%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch      | 2        | 0.86%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 2        | 0.86%   |
| RTK TopTech TV RTK0001 1366x768                                       | 2        | 0.86%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                 | 2        | 0.86%   |
| LG Electronics LCD Monitor E2241 1920x1080                            | 2        | 0.86%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2        | 0.86%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch     | 2        | 0.86%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 2        | 0.86%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.86%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 2        | 0.86%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 2        | 0.86%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 0.86%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                  | 2        | 0.86%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                      | 2        | 0.86%   |
| Acer V206HQLB ACR051A 1366x768 434x236mm 19.4-inch                    | 2        | 0.86%   |
| Acer AL1716 ACRAD51 1280x1024 340x270mm 17.1-inch                     | 2        | 0.86%   |
| Westinghouse WDE LCM-17v2 WDE1702 1280x1024 338x270mm 17.0-inch       | 1        | 0.43%   |
| ViewSonic VX2739 Series VSC3F24 1920x1080 598x336mm 27.0-inch         | 1        | 0.43%   |
| ViewSonic VG2239 Series VSCC42B 1920x1080 477x268mm 21.5-inch         | 1        | 0.43%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1        | 0.43%   |
| ViewSonic VA2405-FHD VSCA939 1920x1080 527x296mm 23.8-inch            | 1        | 0.43%   |
| Unknown LCD Monitor XXX MS82PV 1360x768                               | 1        | 0.43%   |
| Unknown (XXX) MS82PV XXX001A 1360x768 330x210mm 15.4-inch             | 1        | 0.43%   |
| SMC LCD-32K30TD** SMC0001 1920x540                                    | 1        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 73       | 32.88%  |
| 1366x768 (WXGA)    | 36       | 16.22%  |
| 1600x900 (HD+)     | 21       | 9.46%   |
| 1280x1024 (SXGA)   | 21       | 9.46%   |
| 1440x900 (WXGA+)   | 19       | 8.56%   |
| 3840x2160 (4K)     | 11       | 4.95%   |
| 1360x768           | 9        | 4.05%   |
| 2560x1440 (QHD)    | 8        | 3.6%    |
| 1680x1050 (WSXGA+) | 6        | 2.7%    |
| 2560x1080          | 3        | 1.35%   |
| 1024x768 (XGA)     | 3        | 1.35%   |
| Unknown            | 3        | 1.35%   |
| 3840x1080          | 2        | 0.9%    |
| 1920x1200 (WUXGA)  | 2        | 0.9%    |
| 1280x720 (HD)      | 2        | 0.9%    |
| 3200x1080          | 1        | 0.45%   |
| 1920x540           | 1        | 0.45%   |
| 1152x864           | 1        | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 37       | 16.44%  |
| 19      | 33       | 14.67%  |
| 21      | 32       | 14.22%  |
| 23      | 23       | 10.22%  |
| Unknown | 15       | 6.67%   |
| 20      | 14       | 6.22%   |
| 17      | 14       | 6.22%   |
| 31      | 9        | 4%      |
| 27      | 8        | 3.56%   |
| 24      | 8        | 3.56%   |
| 22      | 7        | 3.11%   |
| 15      | 4        | 1.78%   |
| 72      | 3        | 1.33%   |
| 47      | 3        | 1.33%   |
| 84      | 2        | 0.89%   |
| 48      | 2        | 0.89%   |
| 34      | 2        | 0.89%   |
| 12      | 2        | 0.89%   |
| 60      | 1        | 0.44%   |
| 52      | 1        | 0.44%   |
| 46      | 1        | 0.44%   |
| 40      | 1        | 0.44%   |
| 28      | 1        | 0.44%   |
| 16      | 1        | 0.44%   |
| 13      | 1        | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 116      | 52.73%  |
| 501-600     | 33       | 15%     |
| 301-350     | 16       | 7.27%   |
| Unknown     | 15       | 6.82%   |
| 601-700     | 12       | 5.45%   |
| 351-400     | 9        | 4.09%   |
| 1001-1500   | 8        | 3.64%   |
| 1501-2000   | 5        | 2.27%   |
| 201-300     | 3        | 1.36%   |
| 701-800     | 2        | 0.91%   |
| 801-900     | 1        | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 147      | 68.37%  |
| 16/10   | 25       | 11.63%  |
| 5/4     | 18       | 8.37%   |
| Unknown | 14       | 6.51%   |
| 4/3     | 6        | 2.79%   |
| 21/9    | 3        | 1.4%    |
| 32/9    | 2        | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 61       | 27.35%  |
| 151-200        | 54       | 24.22%  |
| 141-150        | 46       | 20.63%  |
| Unknown        | 15       | 6.73%   |
| 351-500        | 11       | 4.93%   |
| More than 1000 | 8        | 3.59%   |
| 301-350        | 8        | 3.59%   |
| 501-1000       | 6        | 2.69%   |
| 251-300        | 4        | 1.79%   |
| 71-80          | 2        | 0.9%    |
| 131-140        | 2        | 0.9%    |
| 111-120        | 2        | 0.9%    |
| 101-110        | 2        | 0.9%    |
| 81-90          | 1        | 0.45%   |
| 121-130        | 1        | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 143      | 65.6%   |
| 101-120 | 40       | 18.35%  |
| Unknown | 15       | 6.88%   |
| 1-50    | 14       | 6.42%   |
| 121-160 | 4        | 1.83%   |
| 161-240 | 2        | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 210      | 85.37%  |
| 2     | 18       | 7.32%   |
| 0     | 15       | 6.1%    |
| 3     | 3        | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 155      | 45.06%  |
| Intel                             | 54       | 15.7%   |
| Qualcomm Atheros                  | 30       | 8.72%   |
| Ralink Technology                 | 23       | 6.69%   |
| Broadcom                          | 14       | 4.07%   |
| TP-Link                           | 11       | 3.2%    |
| Nvidia                            | 11       | 3.2%    |
| Broadcom Limited                  | 6        | 1.74%   |
| Ralink                            | 5        | 1.45%   |
| Qualcomm Atheros Communications   | 4        | 1.16%   |
| Marvell Technology Group          | 4        | 1.16%   |
| Xiaomi                            | 3        | 0.87%   |
| Samsung Electronics               | 3        | 0.87%   |
| Mercucys                          | 3        | 0.87%   |
| MediaTek                          | 3        | 0.87%   |
| VIA Technologies                  | 2        | 0.58%   |
| Motorola PCS                      | 2        | 0.58%   |
| ICS Advent                        | 2        | 0.58%   |
| Wistron NeWeb                     | 1        | 0.29%   |
| Sundance Technology Inc / IC Plus | 1        | 0.29%   |
| Qualcomm                          | 1        | 0.29%   |
| OPPO Electronics                  | 1        | 0.29%   |
| Mellanox Technologies             | 1        | 0.29%   |
| Huawei Technologies               | 1        | 0.29%   |
| Encore Electronics                | 1        | 0.29%   |
| D-Link System                     | 1        | 0.29%   |
| Aquantia                          | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 110      | 30.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17       | 4.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 3.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 10       | 2.73%   |
| Ralink MT7601U Wireless Adapter                                   | 9        | 2.46%   |
| Nvidia MCP61 Ethernet                                             | 9        | 2.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8        | 2.19%   |
| Intel I211 Gigabit Network Connection                             | 8        | 2.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 1.64%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.37%   |
| Intel Ethernet Controller I225-V                                  | 5        | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 4        | 1.09%   |
| TP-Link 802.11n NIC                                               | 4        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 1.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4        | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 0.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.82%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 3        | 0.82%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3        | 0.82%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 3        | 0.82%   |
| Mercucys 802.11n NIC                                              | 3        | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.55%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.55%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter              | 2        | 0.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 0.55%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2        | 0.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.55%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.55%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.55%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Ralink Technology               | 23       | 22.33%  |
| Realtek Semiconductor           | 22       | 21.36%  |
| Intel                           | 16       | 15.53%  |
| Qualcomm Atheros                | 13       | 12.62%  |
| TP-Link                         | 11       | 10.68%  |
| Ralink                          | 5        | 4.85%   |
| Qualcomm Atheros Communications | 4        | 3.88%   |
| Mercucys                        | 3        | 2.91%   |
| MediaTek                        | 3        | 2.91%   |
| Wistron NeWeb                   | 1        | 0.97%   |
| Encore Electronics              | 1        | 0.97%   |
| Broadcom Limited                | 1        | 0.97%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Ralink RT2870/RT3070 Wireless Adapter                               | 10       | 9.71%   |
| Ralink MT7601U Wireless Adapter                                     | 9        | 8.74%   |
| Intel Wi-Fi 6 AX200                                                 | 5        | 4.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 4        | 3.88%   |
| TP-Link 802.11n NIC                                                 | 4        | 3.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 4        | 3.88%   |
| Qualcomm Atheros AR9271 802.11n                                     | 4        | 3.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 4        | 3.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 3        | 2.91%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller           | 3        | 2.91%   |
| Ralink RT5370 Wireless Adapter                                      | 3        | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 3        | 2.91%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 3        | 2.91%   |
| Mercucys 802.11n NIC                                                | 3        | 2.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 1.94%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                | 2        | 1.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 2        | 1.94%   |
| Ralink RT2561/RT61 rev B 802.11g                                    | 2        | 1.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 1.94%   |
| Wistron NeWeb AR9170+AR9104 802.11abgn Wireless Adapter             | 1        | 0.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.97%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                             | 1        | 0.97%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 0.97%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.97%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 0.97%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.97%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 0.97%   |
| Realtek 802.11ac NIC                                                | 1        | 0.97%   |
| Ralink RT3072 Wireless Adapter                                      | 1        | 0.97%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter              | 1        | 0.97%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                           | 1        | 0.97%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 0.97%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                    | 1        | 0.97%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter          | 1        | 0.97%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 0.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 1        | 0.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 0.97%   |
| Intel Wireless-AC 9260                                              | 1        | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 143      | 55.21%  |
| Intel                             | 47       | 18.15%  |
| Qualcomm Atheros                  | 17       | 6.56%   |
| Broadcom                          | 14       | 5.41%   |
| Nvidia                            | 11       | 4.25%   |
| Broadcom Limited                  | 5        | 1.93%   |
| Marvell Technology Group          | 4        | 1.54%   |
| Xiaomi                            | 3        | 1.16%   |
| Samsung Electronics               | 3        | 1.16%   |
| VIA Technologies                  | 2        | 0.77%   |
| ICS Advent                        | 2        | 0.77%   |
| Sundance Technology Inc / IC Plus | 1        | 0.39%   |
| Qualcomm                          | 1        | 0.39%   |
| OPPO Electronics                  | 1        | 0.39%   |
| Motorola PCS                      | 1        | 0.39%   |
| Mellanox Technologies             | 1        | 0.39%   |
| Huawei Technologies               | 1        | 0.39%   |
| D-Link System                     | 1        | 0.39%   |
| Aquantia                          | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 110      | 41.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 17       | 6.49%   |
| Realtek RTL8125 2.5GbE Controller                                          | 12       | 4.58%   |
| Nvidia MCP61 Ethernet                                                      | 9        | 3.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 8        | 3.05%   |
| Intel I211 Gigabit Network Connection                                      | 8        | 3.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 6        | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 6        | 2.29%   |
| Intel Ethernet Controller I225-V                                           | 5        | 1.91%   |
| Intel 82579V Gigabit Network Connection                                    | 5        | 1.91%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 4        | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.15%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                       | 3        | 1.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                               | 2        | 0.76%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 2        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.76%   |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.76%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 2        | 0.76%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.76%   |
| Intel Ethernet Connection (12) I219-V                                      | 2        | 0.76%   |
| Intel 82578DC Gigabit Network Connection                                   | 2        | 0.76%   |
| Intel 82566DM Gigabit Network Connection                                   | 2        | 0.76%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 2        | 0.76%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                    | 2        | 0.76%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                           | 2        | 0.76%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                            | 2        | 0.76%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                    | 2        | 0.76%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.38%   |
| Qualcomm QM215-QRD _SN:E72764DE                                            | 1        | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.38%   |
| OPPO RMX3263                                                               | 1        | 0.38%   |
| Motorola PCS moto g pure                                                   | 1        | 0.38%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                      | 1        | 0.38%   |
| Marvell Group 88E8070 based Ethernet Controller                            | 1        | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 244      | 71.76%  |
| WiFi     | 95       | 27.94%  |
| Unknown  | 1        | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 196      | 79.03%  |
| WiFi     | 52       | 20.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 182      | 74.29%  |
| 2     | 57       | 23.27%  |
| 3     | 3        | 1.22%   |
| 0     | 2        | 0.82%   |
| 7     | 1        | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 213      | 86.59%  |
| Yes  | 33       | 13.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 26       | 55.32%  |
| Intel                   | 15       | 31.91%  |
| MediaTek                | 2        | 4.26%   |
| Realtek Semiconductor   | 1        | 2.13%   |
| IMC Networks            | 1        | 2.13%   |
| Dell                    | 1        | 2.13%   |
| Apple                   | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26       | 55.32%  |
| Intel AX200 Bluetooth                               | 5        | 10.64%  |
| MediaTek Wireless_Device                            | 2        | 4.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 4.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 4.26%   |
| Intel Bluetooth wireless interface                  | 2        | 4.26%   |
| Intel AX201 Bluetooth                               | 2        | 4.26%   |
| Realtek Bluetooth Radio                             | 1        | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 2.13%   |
| Intel AX210 Bluetooth                               | 1        | 2.13%   |
| IMC Networks Wireless_Device                        | 1        | 2.13%   |
| Dell Wireless 365 Bluetooth                         | 1        | 2.13%   |
| Apple Bluetooth HCI                                 | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 139      | 37.87%  |
| AMD                                  | 110      | 29.97%  |
| Nvidia                               | 76       | 20.71%  |
| C-Media Electronics                  | 7        | 1.91%   |
| VIA Technologies                     | 4        | 1.09%   |
| Logitech                             | 4        | 1.09%   |
| Creative Labs                        | 4        | 1.09%   |
| Generalplus Technology               | 3        | 0.82%   |
| M-Audio                              | 2        | 0.54%   |
| Kingston Technology                  | 2        | 0.54%   |
| JMTek                                | 2        | 0.54%   |
| Turtle Beach                         | 1        | 0.27%   |
| Trust                                | 1        | 0.27%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.27%   |
| Texas Instruments                    | 1        | 0.27%   |
| SteelSeries ApS                      | 1        | 0.27%   |
| Realtek Semiconductor                | 1        | 0.27%   |
| Razer USA                            | 1        | 0.27%   |
| GN Netcom                            | 1        | 0.27%   |
| Earth Computer Technologies          | 1        | 0.27%   |
| Drop                                 | 1        | 0.27%   |
| Creative Technology                  | 1        | 0.27%   |
| Corsair                              | 1        | 0.27%   |
| Blue Microphones                     | 1        | 0.27%   |
| Avid Technology                      | 1        | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 33       | 7.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 27       | 6.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 25       | 5.77%   |
| AMD Starship/Matisse HD Audio Controller                                          | 20       | 4.62%   |
| AMD Family 17h/19h HD Audio Controller                                            | 19       | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18       | 4.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 11       | 2.54%   |
| Nvidia MCP61 High Definition Audio                                                | 10       | 2.31%   |
| Nvidia High Definition Audio Controller                                           | 10       | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 2.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 10       | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 9        | 2.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 9        | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8        | 1.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 8        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 1.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 7        | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 1.62%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.62%   |
| Intel Comet Lake PCH-V cAVS                                                       | 6        | 1.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 6        | 1.39%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5        | 1.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 5        | 1.15%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 0.92%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 4        | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4        | 0.92%   |
| AMD Navi 10 HDMI Audio                                                            | 4        | 0.92%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.69%   |
| Intel USB PnP Sound Device                                                        | 3        | 0.69%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 0.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3        | 0.69%   |
| Generalplus Technology USB Audio Device                                           | 3        | 0.69%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 3        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 27       | 18.75%  |
| Samsung Electronics | 17       | 11.81%  |
| Corsair             | 17       | 11.81%  |
| A-DATA Technology   | 14       | 9.72%   |
| Kingston            | 12       | 8.33%   |
| SK hynix            | 8        | 5.56%   |
| Crucial             | 8        | 5.56%   |
| G.Skill             | 5        | 3.47%   |
| Micron Technology   | 4        | 2.78%   |
| GeIL                | 4        | 2.78%   |
| Super Talent        | 3        | 2.08%   |
| Ramaxel Technology  | 3        | 2.08%   |
| Patriot             | 3        | 2.08%   |
| Team                | 2        | 1.39%   |
| PNY                 | 2        | 1.39%   |
| Nanya Technology    | 2        | 1.39%   |
| Kreton              | 2        | 1.39%   |
| Hewlett-Packard     | 2        | 1.39%   |
| Avant               | 2        | 1.39%   |
| Unknown (AD8A)      | 1        | 0.69%   |
| Transcend           | 1        | 0.69%   |
| Sesame              | 1        | 0.69%   |
| Kllisre             | 1        | 0.69%   |
| Golden Empire       | 1        | 0.69%   |
| CSX                 | 1        | 0.69%   |
| Unknown             | 1        | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                     | 4        | 2.47%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 4        | 2.47%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s | 3        | 1.85%   |
| GeIL RAM CL11-11-11 D3-1600 8GB DIMM DDR3 1600MT/s    | 3        | 1.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s | 3        | 1.85%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s           | 3        | 1.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 2        | 1.23%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s            | 2        | 1.23%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s        | 2        | 1.23%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s             | 2        | 1.23%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s   | 2        | 1.23%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s   | 2        | 1.23%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s  | 2        | 1.23%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s           | 2        | 1.23%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s          | 2        | 1.23%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s       | 2        | 1.23%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s             | 1        | 0.62%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s          | 1        | 0.62%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s          | 1        | 0.62%   |
| Unknown RAM Module 512MB DIMM DDR 333MT/s             | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 1        | 0.62%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                  | 1        | 0.62%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 1        | 0.62%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s             | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 400MT/s              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 200MT/s              | 1        | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s               | 1        | 0.62%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 1        | 0.62%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM SDRAM                     | 1        | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR2 400MT/s              | 1        | 0.62%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s            | 1        | 0.62%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s            | 1        | 0.62%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 1        | 0.62%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s            | 1        | 0.62%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s    | 1        | 0.62%   |
| Unknown (AD8A) RAM Module 16GB SODIMM DDR4 2133MT/s   | 1        | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 50       | 41.67%  |
| DDR3    | 40       | 33.33%  |
| SDRAM   | 12       | 10%     |
| DDR2    | 8        | 6.67%   |
| Unknown | 6        | 5%      |
| DDR     | 3        | 2.5%    |
| LPDDR4  | 1        | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 110      | 94.02%  |
| SODIMM       | 6        | 5.13%   |
| Row Of Chips | 1        | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 44       | 32.12%  |
| 2048  | 31       | 22.63%  |
| 4096  | 30       | 21.9%   |
| 16384 | 18       | 13.14%  |
| 32768 | 7        | 5.11%   |
| 1024  | 6        | 4.38%   |
| 512   | 1        | 0.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 19.55%  |
| 1333    | 19       | 14.29%  |
| 3600    | 11       | 8.27%   |
| 3200    | 9        | 6.77%   |
| Unknown | 9        | 6.77%   |
| 2133    | 8        | 6.02%   |
| 3000    | 6        | 4.51%   |
| 3400    | 5        | 3.76%   |
| 2400    | 5        | 3.76%   |
| 800     | 5        | 3.76%   |
| 2667    | 3        | 2.26%   |
| 1867    | 3        | 2.26%   |
| 3800    | 2        | 1.5%    |
| 3266    | 2        | 1.5%    |
| 2666    | 2        | 1.5%    |
| 1866    | 2        | 1.5%    |
| 1334    | 2        | 1.5%    |
| 667     | 2        | 1.5%    |
| 333     | 2        | 1.5%    |
| 3733    | 1        | 0.75%   |
| 3500    | 1        | 0.75%   |
| 3100    | 1        | 0.75%   |
| 3066    | 1        | 0.75%   |
| 2800    | 1        | 0.75%   |
| 2176    | 1        | 0.75%   |
| 1066    | 1        | 0.75%   |
| 533     | 1        | 0.75%   |
| 400     | 1        | 0.75%   |
| 200     | 1        | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 28.57%  |
| Seiko Epson         | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| Ricoh               | 1        | 7.14%   |
| Prolific Technology | 1        | 7.14%   |
| Canon               | 1        | 7.14%   |
| Brother Industries  | 1        | 7.14%   |
| BESTEASY            | 1        | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Seiko Epson L120 Series                                | 2        | 14.29%  |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1        | 7.14%   |
| Samsung ML-2010P Mono Laser Printer                    | 1        | 7.14%   |
| Samsung Composite Device                               | 1        | 7.14%   |
| Ricoh Printing Support                                 | 1        | 7.14%   |
| Prolific PL2305 Parallel Port                          | 1        | 7.14%   |
| HP LaserJet CP 1025                                    | 1        | 7.14%   |
| HP LaserJet 1020                                       | 1        | 7.14%   |
| HP Laser 107w                                          | 1        | 7.14%   |
| HP Deskjet 2540 series                                 | 1        | 7.14%   |
| Canon G3000 series                                     | 1        | 7.14%   |
| Brother DCP-T710W                                      | 1        | 7.14%   |
| BESTEASY BE-G42S                                       | 1        | 7.14%   |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 10       | 20.41%  |
| KYE Systems (Mouse Systems) | 7        | 14.29%  |
| Microdia                    | 6        | 12.24%  |
| Microsoft                   | 4        | 8.16%   |
| Cubeternet                  | 4        | 8.16%   |
| Chicony Electronics         | 3        | 6.12%   |
| Huawei Technologies         | 2        | 4.08%   |
| Arkmicro Technologies       | 2        | 4.08%   |
| webcam                      | 1        | 2.04%   |
| WaveRider Communications    | 1        | 2.04%   |
| Unknown                     | 1        | 2.04%   |
| Trust                       | 1        | 2.04%   |
| Samsung Electronics         | 1        | 2.04%   |
| Realtek Semiconductor       | 1        | 2.04%   |
| Pixart Imaging              | 1        | 2.04%   |
| OmniVision Technologies     | 1        | 2.04%   |
| Hewlett-Packard             | 1        | 2.04%   |
| Generalplus Technology      | 1        | 2.04%   |
| GEMBIRD                     | 1        | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Webcam C525                                             | 3        | 6.12%   |
| KYE Systems (Mouse Systems) FaceCam 1000X                           | 3        | 6.12%   |
| Cubeternet GL-UPC822 UVC WebCam                                     | 3        | 6.12%   |
| Microdia USB 2.0 Camera                                             | 2        | 4.08%   |
| Microdia Integrated Camera                                          | 2        | 4.08%   |
| Logitech Webcam C930e                                               | 2        | 4.08%   |
| Logitech Webcam C170                                                | 2        | 4.08%   |
| Huawei UVC Camera                                                   | 2        | 4.08%   |
| Chicony HP High Definition 1MP Webcam                               | 2        | 4.08%   |
| webcam webcam                                                       | 1        | 2.04%   |
| WaveRider USB 2.0 Camera                                            | 1        | 2.04%   |
| Unknown HD camera                                                   | 1        | 2.04%   |
| Trust FHD Webcam                                                    | 1        | 2.04%   |
| Samsung Galaxy A5 (MTP)                                             | 1        | 2.04%   |
| Realtek NexiGo N960E FHD Webcam                                     | 1        | 2.04%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                | 1        | 2.04%   |
| OmniVision Monitor Webcam                                           | 1        | 2.04%   |
| Microsoft MicrosoftÂ LifeCam Studio                                | 1        | 2.04%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks                 | 1        | 2.04%   |
| Microsoft LifeCam HD-3000                                           | 1        | 2.04%   |
| Microsoft LifeCam Cinema                                            | 1        | 2.04%   |
| Microdia Webcam Vitade AF                                           | 1        | 2.04%   |
| Microdia Sonix USB 2.0 Camera                                       | 1        | 2.04%   |
| Logitech HD Pro Webcam C920                                         | 1        | 2.04%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 2.04%   |
| Logitech C505 HD Webcam                                             | 1        | 2.04%   |
| KYE Systems (Mouse Systems) Genius iLook 1321 V2                    | 1        | 2.04%   |
| KYE Systems (Mouse Systems) FaceCam 310                             | 1        | 2.04%   |
| KYE Systems (Mouse Systems) FaceCam 2020                            | 1        | 2.04%   |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 2.04%   |
| HP Webcam HD-2200                                                   | 1        | 2.04%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 2.04%   |
| GEMBIRD USB2.0 PC CAMERA                                            | 1        | 2.04%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 2.04%   |
| Chicony HP WebCam                                                   | 1        | 2.04%   |
| Arkmicro Webcam Carrefour                                           | 1        | 2.04%   |
| Arkmicro USB2.0 PC CAMERA                                           | 1        | 2.04%   |

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
| 0     | 208      | 84.21%  |
| 1     | 36       | 14.57%  |
| 2     | 2        | 0.81%   |
| 4     | 1        | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 17       | 39.53%  |
| Graphics card            | 15       | 34.88%  |
| Communication controller | 4        | 9.3%    |
| Storage/raid             | 2        | 4.65%   |
| Unassigned class         | 1        | 2.33%   |
| Sound                    | 1        | 2.33%   |
| Network                  | 1        | 2.33%   |
| Multimedia controller    | 1        | 2.33%   |
| Camera                   | 1        | 2.33%   |

