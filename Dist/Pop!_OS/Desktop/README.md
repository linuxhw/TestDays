Pop!_OS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 7833

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkCentre M90 5485WHG     | [f8da681374](https://linux-hardware.org/?probe=f8da681374) | Jan 03, 2026 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [8f17e68870](https://linux-hardware.org/?probe=8f17e68870) | Jan 02, 2026 |
| Gigabyte      | B650 GAMING X AX            | [a43d09ccc1](https://linux-hardware.org/?probe=a43d09ccc1) | Jan 02, 2026 |
| Gigabyte      | B650M GAMING PLUS WIFI      | [515f2ee055](https://linux-hardware.org/?probe=515f2ee055) | Dec 31, 2025 |
| MSI           | PRO H510M-B                 | [8036e7a91b](https://linux-hardware.org/?probe=8036e7a91b) | Dec 31, 2025 |
| Dell          | 0NW6H5 A00                  | [09c67dda57](https://linux-hardware.org/?probe=09c67dda57) | Dec 31, 2025 |
| ASUSTek       | Z170-A                      | [6ec42a46f4](https://linux-hardware.org/?probe=6ec42a46f4) | Dec 31, 2025 |
| ASRock        | B550M-HDV                   | [dd17bbedaf](https://linux-hardware.org/?probe=dd17bbedaf) | Dec 30, 2025 |
| ASUSTek       | PRIME Z790-P WIFI           | [1f02c0cdd6](https://linux-hardware.org/?probe=1f02c0cdd6) | Dec 30, 2025 |
| Gigabyte      | 990FXA-UD3                  | [60443ef738](https://linux-hardware.org/?probe=60443ef738) | Dec 30, 2025 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [1b91792792](https://linux-hardware.org/?probe=1b91792792) | Dec 30, 2025 |
| Gigabyte      | 990FXA-UD3                  | [bd9db1c966](https://linux-hardware.org/?probe=bd9db1c966) | Dec 30, 2025 |
| ASUSTek       | STRIX Z270F GAMING          | [438c445499](https://linux-hardware.org/?probe=438c445499) | Dec 30, 2025 |
| Unknown       | Unknown                     | [d78cc8f286](https://linux-hardware.org/?probe=d78cc8f286) | Dec 30, 2025 |
| Dell          | 0XJ8C4 A00                  | [e4617ec8bc](https://linux-hardware.org/?probe=e4617ec8bc) | Dec 29, 2025 |
| Gigabyte      | X870E AORUS XTREME AI TO... | [3706804c22](https://linux-hardware.org/?probe=3706804c22) | Dec 29, 2025 |
| Gigabyte      | A520M K V2                  | [9226dfb506](https://linux-hardware.org/?probe=9226dfb506) | Dec 29, 2025 |
| ASRock        | B550 Extreme4               | [5441fcc076](https://linux-hardware.org/?probe=5441fcc076) | Dec 29, 2025 |
| ASRock        | B360M IB-R1                 | [38a6afd2fc](https://linux-hardware.org/?probe=38a6afd2fc) | Dec 28, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7      | [6e610df56f](https://linux-hardware.org/?probe=6e610df56f) | Dec 28, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [fc5fecbe2d](https://linux-hardware.org/?probe=fc5fecbe2d) | Dec 28, 2025 |
| Dell          | 04Y8V0 A02                  | [7d844ec9de](https://linux-hardware.org/?probe=7d844ec9de) | Dec 28, 2025 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [1c7694ea7a](https://linux-hardware.org/?probe=1c7694ea7a) | Dec 28, 2025 |
| ASUSTek       | H81M-C                      | [b4cfb3f1d2](https://linux-hardware.org/?probe=b4cfb3f1d2) | Dec 28, 2025 |
| ASUSTek       | P8B75-M LX                  | [271e9d3d9b](https://linux-hardware.org/?probe=271e9d3d9b) | Dec 28, 2025 |
| MSI           | B550-A PRO                  | [1c4fb988c8](https://linux-hardware.org/?probe=1c4fb988c8) | Dec 28, 2025 |
| Unknown       | Unknown                     | [69e30f3ae7](https://linux-hardware.org/?probe=69e30f3ae7) | Dec 28, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [0f78f6bc68](https://linux-hardware.org/?probe=0f78f6bc68) | Dec 28, 2025 |
| Unknown       | Unknown                     | [249d2d491f](https://linux-hardware.org/?probe=249d2d491f) | Dec 28, 2025 |
| Gigabyte      | B550M K                     | [0cec765a3c](https://linux-hardware.org/?probe=0cec765a3c) | Dec 28, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [10952a16c3](https://linux-hardware.org/?probe=10952a16c3) | Dec 28, 2025 |
| Gigabyte      | B650 UD AX-Y1               | [246383b980](https://linux-hardware.org/?probe=246383b980) | Dec 27, 2025 |
| Unknown       | Unknown                     | [c7157eef56](https://linux-hardware.org/?probe=c7157eef56) | Dec 27, 2025 |
| Dell          | 0WPMFG A00                  | [a842e5a5e0](https://linux-hardware.org/?probe=a842e5a5e0) | Dec 27, 2025 |
| MSI           | PRO B550M-VC WIFI           | [5dc6665a42](https://linux-hardware.org/?probe=5dc6665a42) | Dec 27, 2025 |
| MSI           | B550M PRO-VDH WIFI          | [bfd2ab96d8](https://linux-hardware.org/?probe=bfd2ab96d8) | Dec 27, 2025 |
| Acer          | Aspire XC-895 V:1.0         | [c4dc80f25c](https://linux-hardware.org/?probe=c4dc80f25c) | Dec 27, 2025 |
| Dell          | 00V62H A00                  | [e7d7c0660b](https://linux-hardware.org/?probe=e7d7c0660b) | Dec 27, 2025 |
| MSI           | MAG X570S TORPEDO MAX       | [7430ee5a08](https://linux-hardware.org/?probe=7430ee5a08) | Dec 26, 2025 |
| ASRock        | X870 Pro RS WiFi            | [bdb20e95ee](https://linux-hardware.org/?probe=bdb20e95ee) | Dec 26, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a8807a455d](https://linux-hardware.org/?probe=a8807a455d) | Dec 26, 2025 |
| MSI           | B550-A PRO[CEC]             | [f479da3d55](https://linux-hardware.org/?probe=f479da3d55) | Dec 26, 2025 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [a36b063235](https://linux-hardware.org/?probe=a36b063235) | Dec 25, 2025 |
| Huanan        | X99-F8 GAMING V5.0          | [b73e8a3f3a](https://linux-hardware.org/?probe=b73e8a3f3a) | Dec 25, 2025 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [2c2cb1c2bb](https://linux-hardware.org/?probe=2c2cb1c2bb) | Dec 25, 2025 |
| ASRock        | B850M Pro-A WiFi            | [95e186f2a8](https://linux-hardware.org/?probe=95e186f2a8) | Dec 25, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | [6bfbb555fd](https://linux-hardware.org/?probe=6bfbb555fd) | Dec 25, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f086149978](https://linux-hardware.org/?probe=f086149978) | Dec 25, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3158013ada](https://linux-hardware.org/?probe=3158013ada) | Dec 24, 2025 |
| SZQFTX        | MI2-SC                      | [ae70515a6e](https://linux-hardware.org/?probe=ae70515a6e) | Dec 24, 2025 |
| ASRock        | B650M-H/M.2+ WiFi           | [cc16ae3bde](https://linux-hardware.org/?probe=cc16ae3bde) | Dec 24, 2025 |
| Gigabyte      | Z97X-UD3H-CF                | [6ee709c5dc](https://linux-hardware.org/?probe=6ee709c5dc) | Dec 24, 2025 |
| ASRock        | B550M PG Riptide            | [ec0cb6636f](https://linux-hardware.org/?probe=ec0cb6636f) | Dec 23, 2025 |
| ASUSTek       | H97-PLUS                    | [2c641418ff](https://linux-hardware.org/?probe=2c641418ff) | Dec 23, 2025 |
| ASRock        | B150M Pro4                  | [5379543544](https://linux-hardware.org/?probe=5379543544) | Dec 23, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [82cb92e41f](https://linux-hardware.org/?probe=82cb92e41f) | Dec 23, 2025 |
| ASUSTek       | PRIME Z270-P                | [1696744ca9](https://linux-hardware.org/?probe=1696744ca9) | Dec 23, 2025 |
| MSI           | PRO B760-VC WIFI 7 BULK     | [f0b6bc913a](https://linux-hardware.org/?probe=f0b6bc913a) | Dec 23, 2025 |
| Gigabyte      | B550M AORUS ELITE           | [92f1e09a9f](https://linux-hardware.org/?probe=92f1e09a9f) | Dec 23, 2025 |
| ASRock        | ALiveNF6G-VSTA              | [78c2fee771](https://linux-hardware.org/?probe=78c2fee771) | Dec 23, 2025 |
| ASRock        | B550M PG Riptide            | [0023cd5f96](https://linux-hardware.org/?probe=0023cd5f96) | Dec 22, 2025 |
| Fujitsu Si... | D2608-A1 S26361-D2608-A1    | [52b522c1f8](https://linux-hardware.org/?probe=52b522c1f8) | Dec 22, 2025 |
| ASUSTek       | TUF X470-PLUS GAMING        | [44722befcf](https://linux-hardware.org/?probe=44722befcf) | Dec 22, 2025 |
| ASUSTek       | PRIME B550M-A               | [89f56a9dcc](https://linux-hardware.org/?probe=89f56a9dcc) | Dec 22, 2025 |
| ASUSTek       | TUF X470-PLUS GAMING        | [0ca24c2585](https://linux-hardware.org/?probe=0ca24c2585) | Dec 22, 2025 |
| Gigabyte      | B650 EAGLE AX               | [819b645423](https://linux-hardware.org/?probe=819b645423) | Dec 22, 2025 |
| ASRock        | X470 Taichi                 | [c8ff3b62f2](https://linux-hardware.org/?probe=c8ff3b62f2) | Dec 21, 2025 |
| MSI           | MEG Z490 UNIFY              | [231bcc1089](https://linux-hardware.org/?probe=231bcc1089) | Dec 21, 2025 |
| MSI           | B550M PRO-VDH WIFI          | [12e71927ab](https://linux-hardware.org/?probe=12e71927ab) | Dec 21, 2025 |
| ASUSTek       | P8Z77-V LX                  | [43529e98e0](https://linux-hardware.org/?probe=43529e98e0) | Dec 21, 2025 |
| Biostar       | B450MHP                     | [f1be78596b](https://linux-hardware.org/?probe=f1be78596b) | Dec 21, 2025 |
| ASUSTek       | SABERTOOTH Z87              | [7cf367f714](https://linux-hardware.org/?probe=7cf367f714) | Dec 21, 2025 |
| MSI           | MEG Z490 UNIFY              | [eed2877cda](https://linux-hardware.org/?probe=eed2877cda) | Dec 21, 2025 |
| Intel         | H61                         | [ba6d50b43d](https://linux-hardware.org/?probe=ba6d50b43d) | Dec 21, 2025 |
| ASUSTek       | ROG Maximus X CODE          | [406ceeaba9](https://linux-hardware.org/?probe=406ceeaba9) | Dec 20, 2025 |
| ASRock        | A620M-C R2.0                | [a3200dc1a9](https://linux-hardware.org/?probe=a3200dc1a9) | Dec 20, 2025 |
| ASRock        | A620M-C R2.0                | [8491e98b9c](https://linux-hardware.org/?probe=8491e98b9c) | Dec 20, 2025 |
| Gigabyte      | B450M GAMING                | [3c2b56c3da](https://linux-hardware.org/?probe=3c2b56c3da) | Dec 20, 2025 |
| ASUSTek       | PRIME B650M-A AX II         | [c7dd8cb223](https://linux-hardware.org/?probe=c7dd8cb223) | Dec 20, 2025 |
| Gigabyte      | H81M-DS2                    | [cc1f98d125](https://linux-hardware.org/?probe=cc1f98d125) | Dec 20, 2025 |
| Biostar       | A520MHP                     | [7d41d5e71c](https://linux-hardware.org/?probe=7d41d5e71c) | Dec 19, 2025 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [9a84b4182d](https://linux-hardware.org/?probe=9a84b4182d) | Dec 19, 2025 |
| Gigabyte      | B85M-D3H                    | [cccd9b0dea](https://linux-hardware.org/?probe=cccd9b0dea) | Dec 19, 2025 |
| Biostar       | A520MHP                     | [3ed2f518d3](https://linux-hardware.org/?probe=3ed2f518d3) | Dec 19, 2025 |
| Gigabyte      | B560M DS3H                  | [300d8c438c](https://linux-hardware.org/?probe=300d8c438c) | Dec 19, 2025 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f8b4382a36](https://linux-hardware.org/?probe=f8b4382a36) | Dec 19, 2025 |
| Gigabyte      | Z270X-Gaming K5             | [3576b0ffec](https://linux-hardware.org/?probe=3576b0ffec) | Dec 19, 2025 |
| Gigabyte      | Z370P D3-CF                 | [a352ae0ded](https://linux-hardware.org/?probe=a352ae0ded) | Dec 18, 2025 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [6d69d9f7cf](https://linux-hardware.org/?probe=6d69d9f7cf) | Dec 18, 2025 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6241b95237](https://linux-hardware.org/?probe=6241b95237) | Dec 18, 2025 |
| ASUSTek       | Maximus VIII HERO           | [d71c1ad5f1](https://linux-hardware.org/?probe=d71c1ad5f1) | Dec 17, 2025 |
| ASUSTek       | ROG Maximus XIII HERO       | [be4cfe525d](https://linux-hardware.org/?probe=be4cfe525d) | Dec 17, 2025 |
| ASRock        | B450M-HDV R4.0              | [aaedaa2027](https://linux-hardware.org/?probe=aaedaa2027) | Dec 17, 2025 |
| ASUSTek       | E3 PRO GAMING V5            | [dafa640a04](https://linux-hardware.org/?probe=dafa640a04) | Dec 16, 2025 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [13c0fb7796](https://linux-hardware.org/?probe=13c0fb7796) | Dec 16, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [8383240fb6](https://linux-hardware.org/?probe=8383240fb6) | Dec 15, 2025 |
| Intel         | B75                         | [31661cdbba](https://linux-hardware.org/?probe=31661cdbba) | Dec 15, 2025 |
| Gigabyte      | B550M DS3H                  | [4d1f632947](https://linux-hardware.org/?probe=4d1f632947) | Dec 15, 2025 |
| Gigabyte      | H510M K V2                  | [4a0f5f2d4c](https://linux-hardware.org/?probe=4a0f5f2d4c) | Dec 15, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [19c70885bc](https://linux-hardware.org/?probe=19c70885bc) | Dec 14, 2025 |
| ASUSTek       | TUF B450M-PRO GAMING        | [205f6767c8](https://linux-hardware.org/?probe=205f6767c8) | Dec 14, 2025 |
| ASUSTek       | EX-B250-V7                  | [8cc7d81f1c](https://linux-hardware.org/?probe=8cc7d81f1c) | Dec 14, 2025 |
| MSI           | B450M PRO-VDH PLUS          | [0dc8cf39a6](https://linux-hardware.org/?probe=0dc8cf39a6) | Dec 14, 2025 |
| MSI           | B450 TOMAHAWK MAX           | [ba6482536d](https://linux-hardware.org/?probe=ba6482536d) | Dec 14, 2025 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7c873250b5](https://linux-hardware.org/?probe=7c873250b5) | Dec 14, 2025 |
| Gigabyte      | H77N-WIFI                   | [6b3fe254d3](https://linux-hardware.org/?probe=6b3fe254d3) | Dec 14, 2025 |
| Gigabyte      | H77N-WIFI                   | [7fe8596672](https://linux-hardware.org/?probe=7fe8596672) | Dec 14, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [640381dbb0](https://linux-hardware.org/?probe=640381dbb0) | Dec 14, 2025 |
| Gigabyte      | A520M K V2                  | [66f23f0ead](https://linux-hardware.org/?probe=66f23f0ead) | Dec 13, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [cfc56adf3a](https://linux-hardware.org/?probe=cfc56adf3a) | Dec 13, 2025 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [c14c21a368](https://linux-hardware.org/?probe=c14c21a368) | Dec 13, 2025 |
| HP            | 3031h                       | [68b5d8293b](https://linux-hardware.org/?probe=68b5d8293b) | Dec 13, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [150bec88af](https://linux-hardware.org/?probe=150bec88af) | Dec 13, 2025 |
| HP            | 3031h                       | [a8df00a12c](https://linux-hardware.org/?probe=a8df00a12c) | Dec 13, 2025 |
| ASUSTek       | PRIME X370-A                | [476fcd9561](https://linux-hardware.org/?probe=476fcd9561) | Dec 13, 2025 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [2da52221ca](https://linux-hardware.org/?probe=2da52221ca) | Dec 13, 2025 |
| ASRock        | B450M Pro4                  | [6a414670ad](https://linux-hardware.org/?probe=6a414670ad) | Dec 13, 2025 |
| ASUSTek       | PRIME B850-PLUS             | [3319d6f365](https://linux-hardware.org/?probe=3319d6f365) | Dec 13, 2025 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [3584c933ad](https://linux-hardware.org/?probe=3584c933ad) | Dec 12, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [32bedbfaf6](https://linux-hardware.org/?probe=32bedbfaf6) | Dec 12, 2025 |
| System76      | Thelio Mira thelio-mira-... | [6deebf3acf](https://linux-hardware.org/?probe=6deebf3acf) | Dec 12, 2025 |
| System76      | Thelio Mira thelio-mira-... | [fa9d9671cf](https://linux-hardware.org/?probe=fa9d9671cf) | Dec 12, 2025 |
| HP            | 806A                        | [7fef3c0c3e](https://linux-hardware.org/?probe=7fef3c0c3e) | Dec 12, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [f7403e8760](https://linux-hardware.org/?probe=f7403e8760) | Dec 11, 2025 |
| HP            | 89D8 SMVB                   | [314751990d](https://linux-hardware.org/?probe=314751990d) | Dec 11, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [e074efea98](https://linux-hardware.org/?probe=e074efea98) | Dec 11, 2025 |
| MARIUS        | 2016 Mainframe 4000MHz 1... | [276c9090ac](https://linux-hardware.org/?probe=276c9090ac) | Dec 10, 2025 |
| Gigabyte      | X670E AORUS PRO X           | [4094002427](https://linux-hardware.org/?probe=4094002427) | Dec 10, 2025 |
| Dell          | 0D28YY A00                  | [05523e53ef](https://linux-hardware.org/?probe=05523e53ef) | Dec 10, 2025 |
| Gigabyte      | H110M-Gaming3-CF            | [9c6c9201cb](https://linux-hardware.org/?probe=9c6c9201cb) | Dec 10, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [776d7ce967](https://linux-hardware.org/?probe=776d7ce967) | Dec 10, 2025 |
| Gigabyte      | X670E AORUS PRO X           | [606a67fef4](https://linux-hardware.org/?probe=606a67fef4) | Dec 10, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO... | [42d34857cd](https://linux-hardware.org/?probe=42d34857cd) | Dec 10, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0aa72bbcee](https://linux-hardware.org/?probe=0aa72bbcee) | Dec 10, 2025 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [4d06edb238](https://linux-hardware.org/?probe=4d06edb238) | Dec 10, 2025 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [045750805c](https://linux-hardware.org/?probe=045750805c) | Dec 09, 2025 |
| HP            | 0B4Ch D                     | [e6d202c541](https://linux-hardware.org/?probe=e6d202c541) | Dec 09, 2025 |
| Unknown (1... | MAG B550M MORTAR            | [2678a6e567](https://linux-hardware.org/?probe=2678a6e567) | Dec 09, 2025 |
| Unknown (1... | MAG B550M MORTAR            | [a44bff56ff](https://linux-hardware.org/?probe=a44bff56ff) | Dec 09, 2025 |
| ASRock        | X370 Gaming-ITX/ac          | [e46e529197](https://linux-hardware.org/?probe=e46e529197) | Dec 09, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [7619505c0d](https://linux-hardware.org/?probe=7619505c0d) | Dec 09, 2025 |
| MSI           | H510M-A PRO                 | [bb697ee959](https://linux-hardware.org/?probe=bb697ee959) | Dec 08, 2025 |
| Gigabyte      | X570 AORUS ELITE            | [b5a91c4f78](https://linux-hardware.org/?probe=b5a91c4f78) | Dec 08, 2025 |
| MSI           | MAG X870E TOMAHAWK WIFI     | [ac2b0f9bf9](https://linux-hardware.org/?probe=ac2b0f9bf9) | Dec 08, 2025 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [cfb8d44b95](https://linux-hardware.org/?probe=cfb8d44b95) | Dec 08, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [8f67fecdd0](https://linux-hardware.org/?probe=8f67fecdd0) | Dec 08, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [1c40ea2a35](https://linux-hardware.org/?probe=1c40ea2a35) | Dec 07, 2025 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [c6d9d447bb](https://linux-hardware.org/?probe=c6d9d447bb) | Dec 07, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c315ba293c](https://linux-hardware.org/?probe=c315ba293c) | Dec 06, 2025 |
| ASRock        | X870 Pro RS WiFi            | [22e6605eca](https://linux-hardware.org/?probe=22e6605eca) | Dec 06, 2025 |
| ASRock        | B550M Pro4                  | [233048ee4b](https://linux-hardware.org/?probe=233048ee4b) | Dec 05, 2025 |
| ASRock        | B550M Pro4                  | [b206dfea93](https://linux-hardware.org/?probe=b206dfea93) | Dec 05, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | [657991261f](https://linux-hardware.org/?probe=657991261f) | Dec 05, 2025 |
| ASRock        | H110M-HDV R3.0              | [1c5b6b5d0b](https://linux-hardware.org/?probe=1c5b6b5d0b) | Dec 04, 2025 |
| Gigabyte      | X570 AORUS ELITE            | [aa65b940b0](https://linux-hardware.org/?probe=aa65b940b0) | Dec 03, 2025 |
| Gigabyte      | Z490I AORUS ULTRA           | [2a7c023dc6](https://linux-hardware.org/?probe=2a7c023dc6) | Dec 03, 2025 |
| MSI           | PRO B650-VC WIFI III        | [472308ddbd](https://linux-hardware.org/?probe=472308ddbd) | Dec 03, 2025 |
| MSI           | MPG Z390 GAMING PLUS        | [74cbecb5e0](https://linux-hardware.org/?probe=74cbecb5e0) | Dec 03, 2025 |
| ASUSTek       | PRIME B850-PLUS             | [957ce1e8c2](https://linux-hardware.org/?probe=957ce1e8c2) | Dec 02, 2025 |
| Tianbei       | GEM12                       | [1942420532](https://linux-hardware.org/?probe=1942420532) | Dec 02, 2025 |
| Intel         | X99-D4-V5 BSF Ver:1.00      | [e954ec2a59](https://linux-hardware.org/?probe=e954ec2a59) | Dec 02, 2025 |
| HP            | 3397                        | [0d46b84a31](https://linux-hardware.org/?probe=0d46b84a31) | Dec 02, 2025 |
| MSI           | B350 PC MATE                | [b9ac6748b3](https://linux-hardware.org/?probe=b9ac6748b3) | Dec 01, 2025 |
| System76      | Thelio thelio-r1            | [3be8f52f2b](https://linux-hardware.org/?probe=3be8f52f2b) | Dec 01, 2025 |
| Intel         | B75                         | [8098a7c057](https://linux-hardware.org/?probe=8098a7c057) | Dec 01, 2025 |
| Acer          | Aspire TC-1760              | [1e383a6e65](https://linux-hardware.org/?probe=1e383a6e65) | Nov 30, 2025 |
| MSI           | B350 PC MATE                | [d7d04c7e51](https://linux-hardware.org/?probe=d7d04c7e51) | Nov 30, 2025 |
| Dell          | 0T10XW A01                  | [5bc3a2f132](https://linux-hardware.org/?probe=5bc3a2f132) | Nov 30, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [1d9976ca91](https://linux-hardware.org/?probe=1d9976ca91) | Nov 29, 2025 |
| Intel         | H81                         | [0e235d2382](https://linux-hardware.org/?probe=0e235d2382) | Nov 29, 2025 |
| ASUSTek       | P8H67-M LE                  | [de393a1e85](https://linux-hardware.org/?probe=de393a1e85) | Nov 29, 2025 |
| ASUSTek       | P8H67-M LE                  | [6e680a4a29](https://linux-hardware.org/?probe=6e680a4a29) | Nov 29, 2025 |
| ASUSTek       | P8H67-M LE                  | [6de0611554](https://linux-hardware.org/?probe=6de0611554) | Nov 29, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c5ee043d40](https://linux-hardware.org/?probe=c5ee043d40) | Nov 29, 2025 |
| Intel         | H81                         | [1ec4172ab3](https://linux-hardware.org/?probe=1ec4172ab3) | Nov 29, 2025 |
| Kllisre       | E5-X99 V1.0                 | [063285bc11](https://linux-hardware.org/?probe=063285bc11) | Nov 29, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [1921803972](https://linux-hardware.org/?probe=1921803972) | Nov 28, 2025 |
| Kllisre       | E5-X99 V1.0                 | [16c2db011b](https://linux-hardware.org/?probe=16c2db011b) | Nov 28, 2025 |
| MSI           | PRESTIGE X570 CREATION      | [6cbd6de07e](https://linux-hardware.org/?probe=6cbd6de07e) | Nov 27, 2025 |
| ASUSTek       | H81M-C/BR                   | [f10dcf6a5b](https://linux-hardware.org/?probe=f10dcf6a5b) | Nov 27, 2025 |
| ASRock        | B550 Phantom Gaming 4       | [87d31af2c0](https://linux-hardware.org/?probe=87d31af2c0) | Nov 27, 2025 |
| Gigabyte      | B460M DS3H AC-Y1            | [8b3ea003ac](https://linux-hardware.org/?probe=8b3ea003ac) | Nov 26, 2025 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [570ff21afb](https://linux-hardware.org/?probe=570ff21afb) | Nov 25, 2025 |
| Gigabyte      | B450M DS3H-CF               | [4870f169f6](https://linux-hardware.org/?probe=4870f169f6) | Nov 25, 2025 |
| Gigabyte      | B550M DS3H AC               | [99fe3b60f2](https://linux-hardware.org/?probe=99fe3b60f2) | Nov 25, 2025 |
| MSI           | A88X-G45 GAMING             | [116c288959](https://linux-hardware.org/?probe=116c288959) | Nov 25, 2025 |
| HP            | 3397                        | [8576ee683a](https://linux-hardware.org/?probe=8576ee683a) | Nov 25, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5f26212622](https://linux-hardware.org/?probe=5f26212622) | Nov 25, 2025 |
| ASRock        | 760GM-HD                    | [f8a558bc3b](https://linux-hardware.org/?probe=f8a558bc3b) | Nov 25, 2025 |
| ASRock        | 760GM-HD                    | [a9172032f6](https://linux-hardware.org/?probe=a9172032f6) | Nov 25, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [469b0e2c48](https://linux-hardware.org/?probe=469b0e2c48) | Nov 25, 2025 |
| ASUSTek       | P6T                         | [549ea5c8f6](https://linux-hardware.org/?probe=549ea5c8f6) | Nov 24, 2025 |
| MSI           | H310M PRO-VDH PLUS          | [90e2b7fb98](https://linux-hardware.org/?probe=90e2b7fb98) | Nov 24, 2025 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [b65d33482e](https://linux-hardware.org/?probe=b65d33482e) | Nov 24, 2025 |
| Intel         | X99E V1.0                   | [417424c46c](https://linux-hardware.org/?probe=417424c46c) | Nov 24, 2025 |
| Dell          | 0TP412                      | [89c9c1bf9d](https://linux-hardware.org/?probe=89c9c1bf9d) | Nov 23, 2025 |
| ASUSTek       | ROG STRIX B850-I GAMING ... | [1c30e18293](https://linux-hardware.org/?probe=1c30e18293) | Nov 23, 2025 |
| GMKtec        | NucBoxG2 Plus               | [54f90eb360](https://linux-hardware.org/?probe=54f90eb360) | Nov 23, 2025 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [49a66cf66f](https://linux-hardware.org/?probe=49a66cf66f) | Nov 23, 2025 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [58bb243b4c](https://linux-hardware.org/?probe=58bb243b4c) | Nov 21, 2025 |
| GMKtec        | NucBoxG2 Plus               | [131c880d29](https://linux-hardware.org/?probe=131c880d29) | Nov 21, 2025 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | [f853bbd9bf](https://linux-hardware.org/?probe=f853bbd9bf) | Nov 21, 2025 |
| Intel         | X99 V1.0                    | [7aabf3c2ad](https://linux-hardware.org/?probe=7aabf3c2ad) | Nov 21, 2025 |
| ASUSTek       | SABERTOOTH X79              | [77d79f02db](https://linux-hardware.org/?probe=77d79f02db) | Nov 20, 2025 |
| Intel         | H81                         | [fc4726b6b1](https://linux-hardware.org/?probe=fc4726b6b1) | Nov 19, 2025 |
| Gigabyte      | Z170X-Ultra Gaming-CF       | [5b62ac1768](https://linux-hardware.org/?probe=5b62ac1768) | Nov 19, 2025 |
| Gigabyte      | AB350-Gaming 3-CF           | [6c0b265a6d](https://linux-hardware.org/?probe=6c0b265a6d) | Nov 19, 2025 |
| HP            | 8433 11                     | [7a3344ccfb](https://linux-hardware.org/?probe=7a3344ccfb) | Nov 19, 2025 |
| ASUSTek       | Z87-A                       | [2526aecc7d](https://linux-hardware.org/?probe=2526aecc7d) | Nov 18, 2025 |
| Gigabyte      | B650 GAMING X               | [93382f8594](https://linux-hardware.org/?probe=93382f8594) | Nov 18, 2025 |
| System76      | Thelio thelio-r1            | [39e4998b22](https://linux-hardware.org/?probe=39e4998b22) | Nov 17, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | [146a23d283](https://linux-hardware.org/?probe=146a23d283) | Nov 17, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | [fd68b94208](https://linux-hardware.org/?probe=fd68b94208) | Nov 16, 2025 |
| Foxconn       | A74MX-S/A74MX-K             | [d86e6f4e5e](https://linux-hardware.org/?probe=d86e6f4e5e) | Nov 16, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [dc847e15c8](https://linux-hardware.org/?probe=dc847e15c8) | Nov 15, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | [acf3543886](https://linux-hardware.org/?probe=acf3543886) | Nov 15, 2025 |
| Gigabyte      | A520M DS3H                  | [09744da28b](https://linux-hardware.org/?probe=09744da28b) | Nov 15, 2025 |
| HP            | 3397                        | [6ce8d91610](https://linux-hardware.org/?probe=6ce8d91610) | Nov 15, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [fd5750ef89](https://linux-hardware.org/?probe=fd5750ef89) | Nov 15, 2025 |
| ASRock        | B250 Pro4                   | [cb22bd169a](https://linux-hardware.org/?probe=cb22bd169a) | Nov 14, 2025 |
| ASRock        | A320M-HDV                   | [5b57fb0f99](https://linux-hardware.org/?probe=5b57fb0f99) | Nov 14, 2025 |
| ASRock        | A320M-HDV                   | [2e904cc5a3](https://linux-hardware.org/?probe=2e904cc5a3) | Nov 14, 2025 |
| Alienware     | 0RV30W A00                  | [3c338acd89](https://linux-hardware.org/?probe=3c338acd89) | Nov 14, 2025 |
| ASRock        | B450 Steel Legend           | [b647cbf1a6](https://linux-hardware.org/?probe=b647cbf1a6) | Nov 14, 2025 |
| MSI           | Z270 GAMING PRO CARBON      | [739c2b146d](https://linux-hardware.org/?probe=739c2b146d) | Nov 13, 2025 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | [002a0ee63b](https://linux-hardware.org/?probe=002a0ee63b) | Nov 13, 2025 |
| ASUSTek       | SABERTOOTH Z170 S           | [3cbf396e1b](https://linux-hardware.org/?probe=3cbf396e1b) | Nov 13, 2025 |
| Sapphire      | FS-FP5V I955T029            | [a9aa85c0db](https://linux-hardware.org/?probe=a9aa85c0db) | Nov 13, 2025 |
| ASRock        | B650M-C                     | [24f4a82cd1](https://linux-hardware.org/?probe=24f4a82cd1) | Nov 13, 2025 |
| ASRock        | B650M-C                     | [ef610ea320](https://linux-hardware.org/?probe=ef610ea320) | Nov 12, 2025 |
| ASRock        | Z87 Pro3                    | [12fc2bd17c](https://linux-hardware.org/?probe=12fc2bd17c) | Nov 12, 2025 |
| Intel         | X99-P4 V9.01                | [e88b0e2914](https://linux-hardware.org/?probe=e88b0e2914) | Nov 11, 2025 |
| Dell          | 03KWTV A00                  | [2c8a78ad06](https://linux-hardware.org/?probe=2c8a78ad06) | Nov 10, 2025 |
| Dell          | 03KWTV A00                  | [32fd69dcd0](https://linux-hardware.org/?probe=32fd69dcd0) | Nov 10, 2025 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [1aadb8bed7](https://linux-hardware.org/?probe=1aadb8bed7) | Nov 09, 2025 |
| ASRock        | Z87 Pro3                    | [4cb6c44f9f](https://linux-hardware.org/?probe=4cb6c44f9f) | Nov 09, 2025 |
| System76      | Thelio Major thelio-majo... | [316f1fdb00](https://linux-hardware.org/?probe=316f1fdb00) | Nov 09, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | [c4ce15fe85](https://linux-hardware.org/?probe=c4ce15fe85) | Nov 08, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | [6dfd08c7ed](https://linux-hardware.org/?probe=6dfd08c7ed) | Nov 08, 2025 |
| ASRock        | Z87 Extreme4                | [948480a24e](https://linux-hardware.org/?probe=948480a24e) | Nov 08, 2025 |
| ASUSTek       | PRIME A320M-K               | [540b772ca7](https://linux-hardware.org/?probe=540b772ca7) | Nov 08, 2025 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [f0b4e8d121](https://linux-hardware.org/?probe=f0b4e8d121) | Nov 08, 2025 |
| Gigabyte      | Z690 UD DDR4                | [848962f6ab](https://linux-hardware.org/?probe=848962f6ab) | Nov 07, 2025 |
| Dell          | 0YXT71 A02                  | [04d83d930d](https://linux-hardware.org/?probe=04d83d930d) | Nov 07, 2025 |
| ASUSTek       | ROG Maximus X HERO          | [1c83849e66](https://linux-hardware.org/?probe=1c83849e66) | Nov 06, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1b6064170b](https://linux-hardware.org/?probe=1b6064170b) | Nov 06, 2025 |
| ASUSTek       | ROG Maximus X HERO          | [d55cef6f3f](https://linux-hardware.org/?probe=d55cef6f3f) | Nov 06, 2025 |
| MSI           | B450M MORTAR MAX            | [3cf344e190](https://linux-hardware.org/?probe=3cf344e190) | Nov 06, 2025 |
| Sapphire      | FS-FP5V I955T029            | [870f7ae608](https://linux-hardware.org/?probe=870f7ae608) | Nov 06, 2025 |
| Gigabyte      | X870E AORUS PRO ICE         | [1d2a5a0826](https://linux-hardware.org/?probe=1d2a5a0826) | Nov 06, 2025 |
| Dell          | 0YU822 A00                  | [f2cfcce379](https://linux-hardware.org/?probe=f2cfcce379) | Nov 05, 2025 |
| ASRock        | Z690 Pro RS                 | [0e5093495d](https://linux-hardware.org/?probe=0e5093495d) | Nov 05, 2025 |
| Gigabyte      | H110M-H DDR3-CF             | [e6f53e648c](https://linux-hardware.org/?probe=e6f53e648c) | Nov 04, 2025 |
| Dell          | 0RCPW3 A03                  | [729aabae9f](https://linux-hardware.org/?probe=729aabae9f) | Nov 04, 2025 |
| MSI           | MPG X870E CARBON WIFI       | [b8980caef2](https://linux-hardware.org/?probe=b8980caef2) | Nov 04, 2025 |
| Dell          | 06D7TR A00                  | [c7dd234359](https://linux-hardware.org/?probe=c7dd234359) | Nov 04, 2025 |
| Dell          | 0YXT71 A01                  | [db2d733040](https://linux-hardware.org/?probe=db2d733040) | Nov 04, 2025 |
| MSI           | MAG Z490 TOMAHAWK           | [df3e6c7b17](https://linux-hardware.org/?probe=df3e6c7b17) | Nov 03, 2025 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [0584626cbd](https://linux-hardware.org/?probe=0584626cbd) | Nov 02, 2025 |
| HP            | 212B                        | [0e093bcc0a](https://linux-hardware.org/?probe=0e093bcc0a) | Nov 01, 2025 |
| MSI           | B450M PRO-VDH MAX           | [1db545ee34](https://linux-hardware.org/?probe=1db545ee34) | Nov 01, 2025 |
| HP            | 3048h                       | [abf6592ec3](https://linux-hardware.org/?probe=abf6592ec3) | Nov 01, 2025 |
| HP            | 3048h                       | [eead500873](https://linux-hardware.org/?probe=eead500873) | Nov 01, 2025 |
| ASUSTek       | Z170-E                      | [e4178ae6f7](https://linux-hardware.org/?probe=e4178ae6f7) | Nov 01, 2025 |
| Gigabyte      | Z790 AORUS ELITE AX         | [05c2f8012d](https://linux-hardware.org/?probe=05c2f8012d) | Nov 01, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [a4d3938f5c](https://linux-hardware.org/?probe=a4d3938f5c) | Nov 01, 2025 |
| ASUSTek       | P8Z68 DELUXE                | [b6963df9f9](https://linux-hardware.org/?probe=b6963df9f9) | Nov 01, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [f24af2596b](https://linux-hardware.org/?probe=f24af2596b) | Nov 01, 2025 |
| Gigabyte      | B850M FORCE WIFI6E          | [5aaa0d6f63](https://linux-hardware.org/?probe=5aaa0d6f63) | Nov 01, 2025 |
| Gigabyte      | 970A-DS3P                   | [5e8311413c](https://linux-hardware.org/?probe=5e8311413c) | Nov 01, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | [c83f367116](https://linux-hardware.org/?probe=c83f367116) | Nov 01, 2025 |
| Dell          | 0Y7WYT A00                  | [5c60c9a614](https://linux-hardware.org/?probe=5c60c9a614) | Nov 01, 2025 |
| Gigabyte      | Z97X-SOC-CF                 | [5b683efd20](https://linux-hardware.org/?probe=5b683efd20) | Oct 31, 2025 |
| ASRock        | B150M Pro4                  | [47f9a45f65](https://linux-hardware.org/?probe=47f9a45f65) | Oct 31, 2025 |
| Dell          | 088DT1 A01                  | [c103112bc1](https://linux-hardware.org/?probe=c103112bc1) | Oct 30, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [170038a33e](https://linux-hardware.org/?probe=170038a33e) | Oct 30, 2025 |
| ASUSTek       | P8H61-M LX2 R2.0            | [660344157f](https://linux-hardware.org/?probe=660344157f) | Oct 30, 2025 |
| Dell          | 0WMJ54 A01                  | [f282d60359](https://linux-hardware.org/?probe=f282d60359) | Oct 29, 2025 |
| DUEX          | A320 Ver:1.21               | [d38354d384](https://linux-hardware.org/?probe=d38354d384) | Oct 29, 2025 |
| Huanan        | X11D-16D V1.0               | [e678133d03](https://linux-hardware.org/?probe=e678133d03) | Oct 28, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9742c2a83d](https://linux-hardware.org/?probe=9742c2a83d) | Oct 28, 2025 |
| Dell          | 0R849J A01                  | [e2d53eb637](https://linux-hardware.org/?probe=e2d53eb637) | Oct 28, 2025 |
| ASRock        | B450M Pro4                  | [f628c84427](https://linux-hardware.org/?probe=f628c84427) | Oct 28, 2025 |
| ASRock        | X870E Taichi Lite           | [2d8aeaf2ab](https://linux-hardware.org/?probe=2d8aeaf2ab) | Oct 28, 2025 |
| Gigabyte      | Z790 AORUS ELITE AX         | [d2d30274b4](https://linux-hardware.org/?probe=d2d30274b4) | Oct 27, 2025 |
| ASRock        | X670E Taichi                | [33d6d16a57](https://linux-hardware.org/?probe=33d6d16a57) | Oct 27, 2025 |
| MSI           | X370 GAMING PRO CARBON      | [71123aefe7](https://linux-hardware.org/?probe=71123aefe7) | Oct 27, 2025 |
| Dell          | 0YXT71 A01                  | [b76f26b0be](https://linux-hardware.org/?probe=b76f26b0be) | Oct 26, 2025 |
| MSI           | MPG X870E CARBON WIFI       | [5ab30e6ad1](https://linux-hardware.org/?probe=5ab30e6ad1) | Oct 26, 2025 |
| MSI           | MPG X870E CARBON WIFI       | [c9c946fc40](https://linux-hardware.org/?probe=c9c946fc40) | Oct 26, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | [d1a7e67528](https://linux-hardware.org/?probe=d1a7e67528) | Oct 25, 2025 |
| Gigabyte      | B450M S2H                   | [ce37916ab8](https://linux-hardware.org/?probe=ce37916ab8) | Oct 25, 2025 |
| ASUSTek       | PRIME B650-PLUS WIFI        | [96252c54de](https://linux-hardware.org/?probe=96252c54de) | Oct 25, 2025 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [540adbe6d4](https://linux-hardware.org/?probe=540adbe6d4) | Oct 24, 2025 |
| ASUSTek       | B650EM MAX GAMING WIFI      | [1f1cb10b5f](https://linux-hardware.org/?probe=1f1cb10b5f) | Oct 24, 2025 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f55fc2692f](https://linux-hardware.org/?probe=f55fc2692f) | Oct 24, 2025 |
| Dell          | 03KWTV A00                  | [4de8ccf53d](https://linux-hardware.org/?probe=4de8ccf53d) | Oct 22, 2025 |
| MSI           | MEG Z790 ACE MAX            | [8d6d331205](https://linux-hardware.org/?probe=8d6d331205) | Oct 22, 2025 |
| ASUSTek       | A68HM-PLUS                  | [ebb3f14b94](https://linux-hardware.org/?probe=ebb3f14b94) | Oct 21, 2025 |
| HP            | 8876 11                     | [68ca76146c](https://linux-hardware.org/?probe=68ca76146c) | Oct 21, 2025 |
| ASRock        | Z690M-ITX/ax                | [b2bd5628a2](https://linux-hardware.org/?probe=b2bd5628a2) | Oct 21, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | [271e9f5956](https://linux-hardware.org/?probe=271e9f5956) | Oct 21, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [0e9a3ecedc](https://linux-hardware.org/?probe=0e9a3ecedc) | Oct 20, 2025 |
| ASUSTek       | Maximus VII IMPACT          | [1a5768ec08](https://linux-hardware.org/?probe=1a5768ec08) | Oct 20, 2025 |
| Intel         | X99 V1.0                    | [19388c27b6](https://linux-hardware.org/?probe=19388c27b6) | Oct 20, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e00cd88d2b](https://linux-hardware.org/?probe=e00cd88d2b) | Oct 20, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f57b4ed52c](https://linux-hardware.org/?probe=f57b4ed52c) | Oct 20, 2025 |
| ASUSTek       | X99-PRO                     | [cb6b246534](https://linux-hardware.org/?probe=cb6b246534) | Oct 20, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [d1c0ee0903](https://linux-hardware.org/?probe=d1c0ee0903) | Oct 20, 2025 |
| ASRock        | B550 Phantom Gaming 4/ac    | [924e2695b4](https://linux-hardware.org/?probe=924e2695b4) | Oct 19, 2025 |
| ASUSTek       | P6T                         | [cd77346086](https://linux-hardware.org/?probe=cd77346086) | Oct 19, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [9bc47cc33e](https://linux-hardware.org/?probe=9bc47cc33e) | Oct 19, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [c3626f6d99](https://linux-hardware.org/?probe=c3626f6d99) | Oct 19, 2025 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [68108e4a14](https://linux-hardware.org/?probe=68108e4a14) | Oct 18, 2025 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [c96f5d356f](https://linux-hardware.org/?probe=c96f5d356f) | Oct 18, 2025 |
| Gigabyte      | H610M S2H V2 DDR4           | [b374216b64](https://linux-hardware.org/?probe=b374216b64) | Oct 18, 2025 |
| Gigabyte      | B850 EAGLE WIFI6E           | [0e414ce35f](https://linux-hardware.org/?probe=0e414ce35f) | Oct 18, 2025 |
| Dell          | 06D7TR A00                  | [4dbdb5fb9d](https://linux-hardware.org/?probe=4dbdb5fb9d) | Oct 18, 2025 |
| ASUSTek       | P8Z77-V LX                  | [81ab1902f3](https://linux-hardware.org/?probe=81ab1902f3) | Oct 17, 2025 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [1daa4e7576](https://linux-hardware.org/?probe=1daa4e7576) | Oct 17, 2025 |
| MSI           | B550M-A PRO                 | [3d8c0ea992](https://linux-hardware.org/?probe=3d8c0ea992) | Oct 17, 2025 |
| MSI           | B550M-A PRO                 | [ab763eaf68](https://linux-hardware.org/?probe=ab763eaf68) | Oct 17, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | [57f38a2149](https://linux-hardware.org/?probe=57f38a2149) | Oct 17, 2025 |
| ASRock        | X670E Taichi                | [faeec61f32](https://linux-hardware.org/?probe=faeec61f32) | Oct 17, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [58a03fe854](https://linux-hardware.org/?probe=58a03fe854) | Oct 17, 2025 |
| ASUSTek       | ProArt B650-CREATOR         | [97932dd11e](https://linux-hardware.org/?probe=97932dd11e) | Oct 17, 2025 |
| Gigabyte      | B650 GAMING X AX            | [a03f4edfab](https://linux-hardware.org/?probe=a03f4edfab) | Oct 16, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [005a1980d4](https://linux-hardware.org/?probe=005a1980d4) | Oct 16, 2025 |
| ASUSTek       | H110M-A/M.2                 | [ae5173dc55](https://linux-hardware.org/?probe=ae5173dc55) | Oct 16, 2025 |
| Gigabyte      | B550M AORUS ELITE           | [f969b3fe6b](https://linux-hardware.org/?probe=f969b3fe6b) | Oct 16, 2025 |
| Huanan        | X99-8M-F V1.1               | [99cdf43524](https://linux-hardware.org/?probe=99cdf43524) | Oct 15, 2025 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [bba3a4b740](https://linux-hardware.org/?probe=bba3a4b740) | Oct 15, 2025 |
| ASUSTek       | P6T                         | [ae6f6106da](https://linux-hardware.org/?probe=ae6f6106da) | Oct 15, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [1e1b6ad657](https://linux-hardware.org/?probe=1e1b6ad657) | Oct 15, 2025 |
| MSI           | Z490-A PRO                  | [796fcac7de](https://linux-hardware.org/?probe=796fcac7de) | Oct 14, 2025 |
| Gigabyte      | B550M DS3H                  | [5def16f0e5](https://linux-hardware.org/?probe=5def16f0e5) | Oct 14, 2025 |
| MSI           | Z490-A PRO                  | [835dfbf88b](https://linux-hardware.org/?probe=835dfbf88b) | Oct 13, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [1344efde3b](https://linux-hardware.org/?probe=1344efde3b) | Oct 13, 2025 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [e06fc42d72](https://linux-hardware.org/?probe=e06fc42d72) | Oct 12, 2025 |
| Intel         | B75                         | [e9ee6830cf](https://linux-hardware.org/?probe=e9ee6830cf) | Oct 12, 2025 |
| ASRock        | B650M Pro RS WiFi           | [71a0b3549d](https://linux-hardware.org/?probe=71a0b3549d) | Oct 12, 2025 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [d879e77b8b](https://linux-hardware.org/?probe=d879e77b8b) | Oct 11, 2025 |
| MSI           | Z270 SLI PLUS               | [b44aded4b0](https://linux-hardware.org/?probe=b44aded4b0) | Oct 11, 2025 |
| Dell          | 03KWTV A00                  | [5e0fa36944](https://linux-hardware.org/?probe=5e0fa36944) | Oct 10, 2025 |
| ECS           | IC43T-A2                    | [24e54ee3bb](https://linux-hardware.org/?probe=24e54ee3bb) | Oct 10, 2025 |
| ECS           | IC43T-A2                    | [504fa45ef9](https://linux-hardware.org/?probe=504fa45ef9) | Oct 10, 2025 |
| Acer          | Veriton X2610               | [09c0b8ea84](https://linux-hardware.org/?probe=09c0b8ea84) | Oct 09, 2025 |
| Dell          | 03KWTV A00                  | [8d21cd8ec8](https://linux-hardware.org/?probe=8d21cd8ec8) | Oct 09, 2025 |
| Alienware     | Aurora R6                   | [ad6c6c0210](https://linux-hardware.org/?probe=ad6c6c0210) | Oct 08, 2025 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a337b16baf](https://linux-hardware.org/?probe=a337b16baf) | Oct 08, 2025 |
| MSI           | Z270 GAMING PRO CARBON      | [8809dd754d](https://linux-hardware.org/?probe=8809dd754d) | Oct 08, 2025 |
| Lenovo        | 376A SDK0T76461 WIN 3422... | [d226504061](https://linux-hardware.org/?probe=d226504061) | Oct 08, 2025 |
| Intel         | B75                         | [119bc0844e](https://linux-hardware.org/?probe=119bc0844e) | Oct 08, 2025 |
| ASUSTek       | TUF X470-PLUS GAMING        | [da8edc054d](https://linux-hardware.org/?probe=da8edc054d) | Oct 08, 2025 |
| ASUSTek       | STRIX Z270F GAMING          | [df9639d16a](https://linux-hardware.org/?probe=df9639d16a) | Oct 08, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4099055418](https://linux-hardware.org/?probe=4099055418) | Oct 08, 2025 |
| ASUSTek       | PRIME B560M-A               | [b010295581](https://linux-hardware.org/?probe=b010295581) | Oct 08, 2025 |
| ASUSTek       | PRIME A320M-E               | [23f1424924](https://linux-hardware.org/?probe=23f1424924) | Oct 06, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | [1ab04d3c7c](https://linux-hardware.org/?probe=1ab04d3c7c) | Oct 05, 2025 |
| ASRock        | B560M-C                     | [6c01d7afea](https://linux-hardware.org/?probe=6c01d7afea) | Oct 04, 2025 |
| ASRock        | B550 Phantom Gaming 4/ac    | [10800520d4](https://linux-hardware.org/?probe=10800520d4) | Oct 04, 2025 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [1f808d3b27](https://linux-hardware.org/?probe=1f808d3b27) | Oct 04, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [8d2e865029](https://linux-hardware.org/?probe=8d2e865029) | Oct 04, 2025 |
| ASUSTek       | ROG Maximus X HERO          | [883c61a5b9](https://linux-hardware.org/?probe=883c61a5b9) | Oct 04, 2025 |
| System76      | Thelio Major thelio-majo... | [a649ef1ffe](https://linux-hardware.org/?probe=a649ef1ffe) | Oct 04, 2025 |
| System76      | Thelio Major thelio-majo... | [52aa590635](https://linux-hardware.org/?probe=52aa590635) | Oct 04, 2025 |
| ASRock        | WRX90 WS EVO                | [6b0d76d08b](https://linux-hardware.org/?probe=6b0d76d08b) | Oct 04, 2025 |
| ASRock        | Z690 Steel Legend           | [8cb3ab91e0](https://linux-hardware.org/?probe=8cb3ab91e0) | Oct 01, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | [fd7e4d8e98](https://linux-hardware.org/?probe=fd7e4d8e98) | Oct 01, 2025 |
| TGT           | H310M-T V1.0                | [74fb190de6](https://linux-hardware.org/?probe=74fb190de6) | Oct 01, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [5986ff65fd](https://linux-hardware.org/?probe=5986ff65fd) | Oct 01, 2025 |
| ASRock        | X99 Extreme4                | [417035527a](https://linux-hardware.org/?probe=417035527a) | Sep 30, 2025 |
| ASUSTek       | Z170-A                      | [2fed9be81c](https://linux-hardware.org/?probe=2fed9be81c) | Sep 29, 2025 |
| Gigabyte      | B850 GAMING X WIFI6E        | [e0bd9d5ab0](https://linux-hardware.org/?probe=e0bd9d5ab0) | Sep 29, 2025 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [aa67870e05](https://linux-hardware.org/?probe=aa67870e05) | Sep 28, 2025 |
| ASUSTek       | M5A97 LE R2.0               | [9846e21f5b](https://linux-hardware.org/?probe=9846e21f5b) | Sep 28, 2025 |
| ASUSTek       | PRIME Z270-P                | [70c5196108](https://linux-hardware.org/?probe=70c5196108) | Sep 28, 2025 |
| Dell          | 06D7TR A00                  | [914857445a](https://linux-hardware.org/?probe=914857445a) | Sep 28, 2025 |
| ASUSTek       | H110M-A/M.2                 | [3de2a87347](https://linux-hardware.org/?probe=3de2a87347) | Sep 27, 2025 |
| ASUSTek       | PRIME Z690-P D4             | [c42f538718](https://linux-hardware.org/?probe=c42f538718) | Sep 27, 2025 |
| ASUSTek       | H97-PLUS                    | [0953a679fc](https://linux-hardware.org/?probe=0953a679fc) | Sep 26, 2025 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [34d252367d](https://linux-hardware.org/?probe=34d252367d) | Sep 26, 2025 |
| ASRock        | 990FX Extreme9              | [d72b29d699](https://linux-hardware.org/?probe=d72b29d699) | Sep 25, 2025 |
| ASRock        | FM2A68M-DG3+                | [a00b5767de](https://linux-hardware.org/?probe=a00b5767de) | Sep 25, 2025 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [1ab9d22415](https://linux-hardware.org/?probe=1ab9d22415) | Sep 25, 2025 |
| MSI           | X99A GAMING 9 ACK           | [973b064889](https://linux-hardware.org/?probe=973b064889) | Sep 25, 2025 |
| Shenzhen M... | A5WSP                       | [82a824615e](https://linux-hardware.org/?probe=82a824615e) | Sep 24, 2025 |
| Shenzhen M... | A5WSP                       | [7ad92ee7ce](https://linux-hardware.org/?probe=7ad92ee7ce) | Sep 24, 2025 |
| MSI           | Z270 GAMING PRO             | [39a6e2fda4](https://linux-hardware.org/?probe=39a6e2fda4) | Sep 24, 2025 |
| ASUSTek       | M5A78L-M LX PLUS            | [c4f00607c2](https://linux-hardware.org/?probe=c4f00607c2) | Sep 23, 2025 |
| Dell          | 0PC5F7 A02                  | [801babd2d0](https://linux-hardware.org/?probe=801babd2d0) | Sep 22, 2025 |
| ASRock        | X470 Taichi                 | [ead3a22c80](https://linux-hardware.org/?probe=ead3a22c80) | Sep 22, 2025 |
| Gigabyte      | B550M DS3H                  | [fe775d015e](https://linux-hardware.org/?probe=fe775d015e) | Sep 21, 2025 |
| ASUSTek       | TUF Z390-PRO GAMING         | [ffe3bb72ff](https://linux-hardware.org/?probe=ffe3bb72ff) | Sep 21, 2025 |
| ASUSTek       | P8H67-M LE                  | [0810153573](https://linux-hardware.org/?probe=0810153573) | Sep 21, 2025 |
| HP            | 18E4                        | [aa4300a05c](https://linux-hardware.org/?probe=aa4300a05c) | Sep 20, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [6b397d668e](https://linux-hardware.org/?probe=6b397d668e) | Sep 20, 2025 |
| Gigabyte      | B550M AORUS PRO-P           | [48932f95c5](https://linux-hardware.org/?probe=48932f95c5) | Sep 19, 2025 |
| HP            | 8AB6 SMVB                   | [422151447b](https://linux-hardware.org/?probe=422151447b) | Sep 19, 2025 |
| HP            | 81C5 MVB                    | [a3e4a3ff7b](https://linux-hardware.org/?probe=a3e4a3ff7b) | Sep 18, 2025 |
| MSI           | Z270 SLI PLUS               | [4a3a4e8f9b](https://linux-hardware.org/?probe=4a3a4e8f9b) | Sep 18, 2025 |
| Gigabyte      | A520 AORUS ELITE            | [dc5d457f4c](https://linux-hardware.org/?probe=dc5d457f4c) | Sep 18, 2025 |
| ASUSTek       | Z790 MAX GAMING WIFI7       | [62d4e94e77](https://linux-hardware.org/?probe=62d4e94e77) | Sep 17, 2025 |
| ASUSTek       | Z790 MAX GAMING WIFI7       | [2a4df5cb8b](https://linux-hardware.org/?probe=2a4df5cb8b) | Sep 17, 2025 |
| Dell          | 0NK70N A04                  | [b093b0f2db](https://linux-hardware.org/?probe=b093b0f2db) | Sep 17, 2025 |
| MSI           | Z270 SLI PLUS               | [3bceb41e80](https://linux-hardware.org/?probe=3bceb41e80) | Sep 15, 2025 |
| Gigabyte      | Z170X-Ultra Gaming-CF       | [3f2fca08b4](https://linux-hardware.org/?probe=3f2fca08b4) | Sep 14, 2025 |
| ASUSTek       | P8Z77-V LK                  | [6c6fe02e8c](https://linux-hardware.org/?probe=6c6fe02e8c) | Sep 14, 2025 |
| ASUSTek       | P8Z77-V LK                  | [29d10c3330](https://linux-hardware.org/?probe=29d10c3330) | Sep 14, 2025 |
| System76      | Thelio Mira thelio-mira-... | [45bbea22ad](https://linux-hardware.org/?probe=45bbea22ad) | Sep 14, 2025 |
| ASRock        | X670E PG Lightning          | [b1f4572c4d](https://linux-hardware.org/?probe=b1f4572c4d) | Sep 13, 2025 |
| MSI           | B450 TOMAHAWK MAX           | [cd64055ce9](https://linux-hardware.org/?probe=cd64055ce9) | Sep 13, 2025 |
| Lenovo        | 3769 SDK0T76461 WIN 3422... | [ef05cc291f](https://linux-hardware.org/?probe=ef05cc291f) | Sep 12, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [b7dbfac0e0](https://linux-hardware.org/?probe=b7dbfac0e0) | Sep 12, 2025 |
| MSI           | PRO B550M-VC WIFI           | [fbf592bf5d](https://linux-hardware.org/?probe=fbf592bf5d) | Sep 12, 2025 |
| ASRock        | X300M-STX                   | [ecf5edd56b](https://linux-hardware.org/?probe=ecf5edd56b) | Sep 11, 2025 |
| ASUSTek       | Z97M-PLUS                   | [bd95faf2aa](https://linux-hardware.org/?probe=bd95faf2aa) | Sep 11, 2025 |
| ASUSTek       | ROG STRIX X870-A GAMING ... | [645aabd88e](https://linux-hardware.org/?probe=645aabd88e) | Sep 11, 2025 |
| ASRock        | B560M-HDV                   | [70da52fd1e](https://linux-hardware.org/?probe=70da52fd1e) | Sep 10, 2025 |
| Gigabyte      | A520M K V2                  | [2411d964f4](https://linux-hardware.org/?probe=2411d964f4) | Sep 10, 2025 |
| MSI           | Z97 GAMING 5                | [64bcd11a7d](https://linux-hardware.org/?probe=64bcd11a7d) | Sep 08, 2025 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | [24cf7a8f3a](https://linux-hardware.org/?probe=24cf7a8f3a) | Sep 07, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [b2dd61caee](https://linux-hardware.org/?probe=b2dd61caee) | Sep 07, 2025 |
| Intel         | MATX-CS612 plus V1.1        | [4861509c3d](https://linux-hardware.org/?probe=4861509c3d) | Sep 07, 2025 |
| MSI           | Z97 GAMING 5                | [235f45fbf4](https://linux-hardware.org/?probe=235f45fbf4) | Sep 07, 2025 |
| ASRock        | X300M-STX                   | [d73a77ca97](https://linux-hardware.org/?probe=d73a77ca97) | Sep 07, 2025 |
| Dell          | 0X4H68 A00                  | [f512670388](https://linux-hardware.org/?probe=f512670388) | Sep 07, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [eed308bbb4](https://linux-hardware.org/?probe=eed308bbb4) | Sep 06, 2025 |
| ASUSTek       | PRIME Z790-P                | [bd81b067f6](https://linux-hardware.org/?probe=bd81b067f6) | Sep 06, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [e5ce50a4f2](https://linux-hardware.org/?probe=e5ce50a4f2) | Sep 06, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [33d708eff3](https://linux-hardware.org/?probe=33d708eff3) | Sep 06, 2025 |
| ASUSTek       | PRIME Z790-P                | [1044fd09c6](https://linux-hardware.org/?probe=1044fd09c6) | Sep 06, 2025 |
| Dell          | 0KV62T A00                  | [e60392368d](https://linux-hardware.org/?probe=e60392368d) | Sep 05, 2025 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [0802078b18](https://linux-hardware.org/?probe=0802078b18) | Sep 05, 2025 |
| MSI           | Z390-A PRO                  | [f0ae304da1](https://linux-hardware.org/?probe=f0ae304da1) | Sep 05, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [bc91f55178](https://linux-hardware.org/?probe=bc91f55178) | Sep 04, 2025 |
| ASUSTek       | ProArt B660-CREATOR D4      | [2406c4e30d](https://linux-hardware.org/?probe=2406c4e30d) | Sep 04, 2025 |
| MSI           | Z370 SLI PLUS               | [2bb7b44d81](https://linux-hardware.org/?probe=2bb7b44d81) | Sep 04, 2025 |
| Gigabyte      | B650 EAGLE                  | [b56edf5a75](https://linux-hardware.org/?probe=b56edf5a75) | Sep 03, 2025 |
| Gigabyte      | Z890 EAGLE WIFI7            | [a399dadbfc](https://linux-hardware.org/?probe=a399dadbfc) | Sep 03, 2025 |
| HP            | 2B2B                        | [df9fcc43bb](https://linux-hardware.org/?probe=df9fcc43bb) | Sep 03, 2025 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [1de72e2057](https://linux-hardware.org/?probe=1de72e2057) | Sep 03, 2025 |
| eMachines     | EL1350                      | [bd82a38e11](https://linux-hardware.org/?probe=bd82a38e11) | Sep 03, 2025 |
| HP            | 82A2                        | [60418cab31](https://linux-hardware.org/?probe=60418cab31) | Sep 03, 2025 |
| ASUSTek       | PRIME B550M-A               | [9d63ea1367](https://linux-hardware.org/?probe=9d63ea1367) | Sep 02, 2025 |
| ASUSTek       | ProArt B660-CREATOR D4      | [ecc85ac387](https://linux-hardware.org/?probe=ecc85ac387) | Sep 02, 2025 |
| GEEKOM        | A5                          | [12e93a6e5f](https://linux-hardware.org/?probe=12e93a6e5f) | Sep 02, 2025 |
| Dell          | 00V62H A01                  | [d2f3c5f1a7](https://linux-hardware.org/?probe=d2f3c5f1a7) | Sep 02, 2025 |
| MSI           | MPG X570 GAMING PLUS        | [8156ebdf9f](https://linux-hardware.org/?probe=8156ebdf9f) | Sep 02, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | [e1ad1ffd10](https://linux-hardware.org/?probe=e1ad1ffd10) | Sep 01, 2025 |
| Gigabyte      | H61M-D2P-B3                 | [7a3bdd9329](https://linux-hardware.org/?probe=7a3bdd9329) | Sep 01, 2025 |
| MSI           | PRO B550M-VC WIFI           | [8dacef5ca8](https://linux-hardware.org/?probe=8dacef5ca8) | Sep 01, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [d1f4a784ad](https://linux-hardware.org/?probe=d1f4a784ad) | Sep 01, 2025 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [87e4b56ef9](https://linux-hardware.org/?probe=87e4b56ef9) | Aug 31, 2025 |
| MAXSUN        | MS-Challenger B650M         | [c8057dd7b6](https://linux-hardware.org/?probe=c8057dd7b6) | Aug 31, 2025 |
| HP            | 8595                        | [eb546aab25](https://linux-hardware.org/?probe=eb546aab25) | Aug 31, 2025 |
| MSI           | Z490-A PRO                  | [3ea4bb5b46](https://linux-hardware.org/?probe=3ea4bb5b46) | Aug 30, 2025 |
| System76      | Thelio Mira thelio-mira-... | [961c25d256](https://linux-hardware.org/?probe=961c25d256) | Aug 29, 2025 |
| ASUSTek       | PRIME B760-PLUS             | [d5cf97f3f0](https://linux-hardware.org/?probe=d5cf97f3f0) | Aug 29, 2025 |
| MACHINIST     | X99-D8 MAX V2.0             | [be53d67f7c](https://linux-hardware.org/?probe=be53d67f7c) | Aug 29, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [3a07b8ef07](https://linux-hardware.org/?probe=3a07b8ef07) | Aug 28, 2025 |
| ASRock        | B650E Steel Legend WiFi     | [5074400a85](https://linux-hardware.org/?probe=5074400a85) | Aug 26, 2025 |
| OEM           | X99-Turbo                   | [d17354036a](https://linux-hardware.org/?probe=d17354036a) | Aug 26, 2025 |
| MSI           | MAG B550M BAZOOKA           | [133460a481](https://linux-hardware.org/?probe=133460a481) | Aug 25, 2025 |
| Intel         | B75                         | [99259aaa36](https://linux-hardware.org/?probe=99259aaa36) | Aug 25, 2025 |
| MSI           | B650M GAMING PLUS WIFI      | [f61820ef05](https://linux-hardware.org/?probe=f61820ef05) | Aug 25, 2025 |
| Gigabyte      | EX58-UD4P                   | [a1d6a85d21](https://linux-hardware.org/?probe=a1d6a85d21) | Aug 24, 2025 |
| ASRock        | B650M-HDV/M.2 White         | [40d02f7288](https://linux-hardware.org/?probe=40d02f7288) | Aug 24, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | [5277a6e202](https://linux-hardware.org/?probe=5277a6e202) | Aug 24, 2025 |
| ASRock        | Z97E-ITX/ac                 | [0479f60a65](https://linux-hardware.org/?probe=0479f60a65) | Aug 23, 2025 |
| Lenovo        | MAHOBAY NO DPK              | [a8bfb0e31d](https://linux-hardware.org/?probe=a8bfb0e31d) | Aug 23, 2025 |
| Gigabyte      | Z790I AORUS ULTRA           | [06a3039912](https://linux-hardware.org/?probe=06a3039912) | Aug 23, 2025 |
| MSI           | MAG B550M BAZOOKA           | [ffe5b2e13c](https://linux-hardware.org/?probe=ffe5b2e13c) | Aug 22, 2025 |
| ASRock        | Z77 Extreme4                | [264964c469](https://linux-hardware.org/?probe=264964c469) | Aug 22, 2025 |
| ASUSTek       | PRIME B450M-K               | [678102761a](https://linux-hardware.org/?probe=678102761a) | Aug 22, 2025 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [7a7cb0a696](https://linux-hardware.org/?probe=7a7cb0a696) | Aug 21, 2025 |
| Dell          | 0WG864                      | [3bce84843b](https://linux-hardware.org/?probe=3bce84843b) | Aug 21, 2025 |
| MSI           | B450-A PRO                  | [d27e0dffc8](https://linux-hardware.org/?probe=d27e0dffc8) | Aug 21, 2025 |
| ASUSTek       | TUF Gaming B650E-PLUS WI... | [3853424c8e](https://linux-hardware.org/?probe=3853424c8e) | Aug 20, 2025 |
| ASUSTek       | TUF Gaming B650E-PLUS WI... | [2cd1d19e79](https://linux-hardware.org/?probe=2cd1d19e79) | Aug 20, 2025 |
| NZXT          | N7 B550                     | [330324cb54](https://linux-hardware.org/?probe=330324cb54) | Aug 20, 2025 |
| Gigabyte      | Z170XP-SLI-CF               | [8c8d8e34bd](https://linux-hardware.org/?probe=8c8d8e34bd) | Aug 20, 2025 |
| GEEKOM        | A5                          | [adaca09809](https://linux-hardware.org/?probe=adaca09809) | Aug 19, 2025 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [622fd55a3c](https://linux-hardware.org/?probe=622fd55a3c) | Aug 19, 2025 |
| Gigabyte      | X870E AORUS PRO ICE         | [3aad912371](https://linux-hardware.org/?probe=3aad912371) | Aug 18, 2025 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | [543177068c](https://linux-hardware.org/?probe=543177068c) | Aug 17, 2025 |
| MAXSUN        | MS-Challenger B650M         | [a7bcc9f3e3](https://linux-hardware.org/?probe=a7bcc9f3e3) | Aug 17, 2025 |
| HP            | 212A                        | [db8e885f63](https://linux-hardware.org/?probe=db8e885f63) | Aug 17, 2025 |
| Intel         | H61 V1.6B                   | [a3dfc2106a](https://linux-hardware.org/?probe=a3dfc2106a) | Aug 16, 2025 |
| Gigabyte      | A520M K V2                  | [1178c17711](https://linux-hardware.org/?probe=1178c17711) | Aug 15, 2025 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [4607649dc7](https://linux-hardware.org/?probe=4607649dc7) | Aug 15, 2025 |
| MSI           | H310M PRO-VDH PLUS          | [c6e874c32d](https://linux-hardware.org/?probe=c6e874c32d) | Aug 15, 2025 |
| Biostar       | A320MH                      | [ca286503ce](https://linux-hardware.org/?probe=ca286503ce) | Aug 14, 2025 |
| ASRock        | B150M Pro4                  | [88233855cf](https://linux-hardware.org/?probe=88233855cf) | Aug 13, 2025 |
| ASUSTek       | TUF Gaming B850-PLUS WIF... | [59d857f529](https://linux-hardware.org/?probe=59d857f529) | Aug 13, 2025 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e54b72c85d](https://linux-hardware.org/?probe=e54b72c85d) | Aug 12, 2025 |
| MSI           | B550-A PRO                  | [dc83f0e1c2](https://linux-hardware.org/?probe=dc83f0e1c2) | Aug 12, 2025 |
| MSI           | PRO Z790-P WIFI             | [f6159ebbe2](https://linux-hardware.org/?probe=f6159ebbe2) | Aug 11, 2025 |
| Dell          | 05XGC8 A01                  | [18b7b065f7](https://linux-hardware.org/?probe=18b7b065f7) | Aug 11, 2025 |
| ASUSTek       | Pro A520M-C II              | [da9ddb0009](https://linux-hardware.org/?probe=da9ddb0009) | Aug 11, 2025 |
| ASUSTek       | Pro A520M-C II              | [2311654caf](https://linux-hardware.org/?probe=2311654caf) | Aug 11, 2025 |
| Intel         | B75                         | [4118412083](https://linux-hardware.org/?probe=4118412083) | Aug 10, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E APEX    | [b804780d6e](https://linux-hardware.org/?probe=b804780d6e) | Aug 09, 2025 |
| ASRock        | B150M Pro4V                 | [5bb955f64d](https://linux-hardware.org/?probe=5bb955f64d) | Aug 08, 2025 |
| ANGXUN        | X99-P4 V1.0                 | [9a60a99d71](https://linux-hardware.org/?probe=9a60a99d71) | Aug 08, 2025 |
| Kllisre       | B450M-F V8.0                | [1af8a9240c](https://linux-hardware.org/?probe=1af8a9240c) | Aug 08, 2025 |
| ASRock        | X670E Steel Legend          | [812e3bec43](https://linux-hardware.org/?probe=812e3bec43) | Aug 08, 2025 |
| Dell          | 0KWVT8 A03                  | [ccbf5027bb](https://linux-hardware.org/?probe=ccbf5027bb) | Aug 08, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b1679266c4](https://linux-hardware.org/?probe=b1679266c4) | Aug 07, 2025 |
| HP            | 870C                        | [46b90d7385](https://linux-hardware.org/?probe=46b90d7385) | Aug 05, 2025 |
| ASUSTek       | ROG STRIX X870-A GAMING ... | [bb975c896a](https://linux-hardware.org/?probe=bb975c896a) | Aug 03, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | [090c4a356d](https://linux-hardware.org/?probe=090c4a356d) | Aug 03, 2025 |
| Gigabyte      | H61M-S2V-B3                 | [9485098722](https://linux-hardware.org/?probe=9485098722) | Aug 02, 2025 |
| MSI           | Z390-A PRO                  | [82fd212ed6](https://linux-hardware.org/?probe=82fd212ed6) | Aug 02, 2025 |
| System76      | Meerkat meer9               | [cb1ff8c576](https://linux-hardware.org/?probe=cb1ff8c576) | Aug 02, 2025 |
| Gigabyte      | Z790 D AC                   | [587da6c64c](https://linux-hardware.org/?probe=587da6c64c) | Aug 01, 2025 |
| Gigabyte      | GA-880GM-USB3               | [f456529bcb](https://linux-hardware.org/?probe=f456529bcb) | Jul 31, 2025 |
| ASRock        | B650E PG Riptide WiFi       | [a8a02f0909](https://linux-hardware.org/?probe=a8a02f0909) | Jul 30, 2025 |
| MANCER        | MCR-A520M-DXV4 V1.0         | [0121e35009](https://linux-hardware.org/?probe=0121e35009) | Jul 30, 2025 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [07ffc28338](https://linux-hardware.org/?probe=07ffc28338) | Jul 29, 2025 |
| Gigabyte      | B450M H                     | [d1aecb35f9](https://linux-hardware.org/?probe=d1aecb35f9) | Jul 29, 2025 |
| HP            | 8456                        | [8e5e40b0f3](https://linux-hardware.org/?probe=8e5e40b0f3) | Jul 28, 2025 |
| Gigabyte      | B550 GAMING X V2            | [77c10f5ef5](https://linux-hardware.org/?probe=77c10f5ef5) | Jul 28, 2025 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [3d29144a85](https://linux-hardware.org/?probe=3d29144a85) | Jul 28, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [5e7be0f69e](https://linux-hardware.org/?probe=5e7be0f69e) | Jul 27, 2025 |
| Gigabyte      | A520M S2H                   | [02dfb0db93](https://linux-hardware.org/?probe=02dfb0db93) | Jul 27, 2025 |
| MSI           | PRO B650M-P                 | [44aba35a54](https://linux-hardware.org/?probe=44aba35a54) | Jul 26, 2025 |
| HP            | 8456                        | [0b26533d03](https://linux-hardware.org/?probe=0b26533d03) | Jul 23, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | [438a0a7bf0](https://linux-hardware.org/?probe=438a0a7bf0) | Jul 23, 2025 |
| Gigabyte      | B850 AORUS ELITE WIFI7 I... | [a1181c4847](https://linux-hardware.org/?probe=a1181c4847) | Jul 23, 2025 |
| Dell          | 0PC5F7 A02                  | [9cd89ddff2](https://linux-hardware.org/?probe=9cd89ddff2) | Jul 22, 2025 |
| Gigabyte      | B850 AORUS ELITE WIFI7 I... | [d3d1a8c707](https://linux-hardware.org/?probe=d3d1a8c707) | Jul 22, 2025 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [fdad841a71](https://linux-hardware.org/?probe=fdad841a71) | Jul 22, 2025 |
| ASRock        | B550M Pro4                  | [04de4fa0e7](https://linux-hardware.org/?probe=04de4fa0e7) | Jul 21, 2025 |
| ASRock        | H110M-DS/Hyper              | [ff180c2011](https://linux-hardware.org/?probe=ff180c2011) | Jul 21, 2025 |
| MSI           | Z390-A PRO                  | [8e4bd02c2d](https://linux-hardware.org/?probe=8e4bd02c2d) | Jul 21, 2025 |
| Dell          | 0TVR1F A01                  | [7564dc18a5](https://linux-hardware.org/?probe=7564dc18a5) | Jul 20, 2025 |
| ASUSTek       | TUF Gaming H470-PRO         | [82ecfc4f2d](https://linux-hardware.org/?probe=82ecfc4f2d) | Jul 20, 2025 |
| Gateway       | FX6860                      | [71a11e53bf](https://linux-hardware.org/?probe=71a11e53bf) | Jul 20, 2025 |
| ASRock        | Z97 Extreme4                | [3808be4f7e](https://linux-hardware.org/?probe=3808be4f7e) | Jul 20, 2025 |
| ASRock        | Z97 Extreme4                | [1adfa6cf9a](https://linux-hardware.org/?probe=1adfa6cf9a) | Jul 20, 2025 |
| Medion        | D3F3-EM2                    | [3caeee00b3](https://linux-hardware.org/?probe=3caeee00b3) | Jul 19, 2025 |
| Apple         | Mac-F221BEC8                | [7b8c0e8d59](https://linux-hardware.org/?probe=7b8c0e8d59) | Jul 19, 2025 |
| Gateway       | FX6860                      | [0dba95e814](https://linux-hardware.org/?probe=0dba95e814) | Jul 18, 2025 |
| MSI           | B850 GAMING PLUS WIFI       | [6d0011febe](https://linux-hardware.org/?probe=6d0011febe) | Jul 18, 2025 |
| JINGSHA       | H311M-K Coffelake           | [09df2b2a44](https://linux-hardware.org/?probe=09df2b2a44) | Jul 17, 2025 |
| Gigabyte      | B85-HD3-A                   | [6ccc6b9382](https://linux-hardware.org/?probe=6ccc6b9382) | Jul 17, 2025 |
| Dell          | 0KWVT8 A03                  | [ec33e74ac1](https://linux-hardware.org/?probe=ec33e74ac1) | Jul 15, 2025 |
| Gigabyte      | Z170X-Gaming 3              | [01696e5fae](https://linux-hardware.org/?probe=01696e5fae) | Jul 14, 2025 |
| Gigabyte      | Z170X-Gaming 3              | [99d0462d32](https://linux-hardware.org/?probe=99d0462d32) | Jul 14, 2025 |
| Dell          | 0WMJ54 A01                  | [155f5b909e](https://linux-hardware.org/?probe=155f5b909e) | Jul 13, 2025 |
| Dell          | 0XHGV1 A02                  | [bf62e4423c](https://linux-hardware.org/?probe=bf62e4423c) | Jul 12, 2025 |
| ASUSTek       | PRIME B350-PLUS             | [d8795ca890](https://linux-hardware.org/?probe=d8795ca890) | Jul 12, 2025 |
| ASUSTek       | M5A97 R2.0                  | [8b9ea4ff9f](https://linux-hardware.org/?probe=8b9ea4ff9f) | Jul 11, 2025 |
| Dell          | 0XFWHV A00                  | [22e6b82841](https://linux-hardware.org/?probe=22e6b82841) | Jul 08, 2025 |
| ASUSTek       | PRIME B350-PLUS             | [08d65c3533](https://linux-hardware.org/?probe=08d65c3533) | Jul 08, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [664e83549f](https://linux-hardware.org/?probe=664e83549f) | Jul 07, 2025 |
| Micro Comp... | HX100G                      | [8bb9b28668](https://linux-hardware.org/?probe=8bb9b28668) | Jul 07, 2025 |
| Gigabyte      | 970A-D3                     | [1af43855ff](https://linux-hardware.org/?probe=1af43855ff) | Jul 07, 2025 |
| Dell          | 0XHGV1 A01                  | [7cefcc2113](https://linux-hardware.org/?probe=7cefcc2113) | Jul 07, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [289acb86a5](https://linux-hardware.org/?probe=289acb86a5) | Jul 06, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2257c1c75d](https://linux-hardware.org/?probe=2257c1c75d) | Jul 06, 2025 |
| ASRock        | A320M-HDV R4.0              | [e21c19a442](https://linux-hardware.org/?probe=e21c19a442) | Jul 06, 2025 |
| Biostar       | H61MHV3                     | [d01a56645d](https://linux-hardware.org/?probe=d01a56645d) | Jul 05, 2025 |
| Gigabyte      | Z170X-Gaming 7              | [bc2f7c8179](https://linux-hardware.org/?probe=bc2f7c8179) | Jul 05, 2025 |
| ASUSTek       | B850 MAX GAMING WIFI W      | [5095837f3d](https://linux-hardware.org/?probe=5095837f3d) | Jul 04, 2025 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [603da84c4d](https://linux-hardware.org/?probe=603da84c4d) | Jul 04, 2025 |
| Biostar       | H61MHV3                     | [fa26376abf](https://linux-hardware.org/?probe=fa26376abf) | Jul 03, 2025 |
| Tianbei       | GEM12                       | [e8e8cce5cb](https://linux-hardware.org/?probe=e8e8cce5cb) | Jul 03, 2025 |
| ASRock        | Z87 Extreme4                | [7c182d5f86](https://linux-hardware.org/?probe=7c182d5f86) | Jul 03, 2025 |
| Gigabyte      | Z68XP-UD3P                  | [2f6cd3acef](https://linux-hardware.org/?probe=2f6cd3acef) | Jul 03, 2025 |
| Gigabyte      | B650 EAGLE AX               | [d8fe688c12](https://linux-hardware.org/?probe=d8fe688c12) | Jul 03, 2025 |
| ASUSTek       | ROG STRIX X870-A GAMING ... | [5f8c47139e](https://linux-hardware.org/?probe=5f8c47139e) | Jul 03, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [d01e2fa12b](https://linux-hardware.org/?probe=d01e2fa12b) | Jul 02, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [8b78c2b85e](https://linux-hardware.org/?probe=8b78c2b85e) | Jul 02, 2025 |
| Intel         | H61S                        | [60452452bf](https://linux-hardware.org/?probe=60452452bf) | Jul 02, 2025 |
| Dell          | 0KJCC5 A00                  | [e30b2b43fd](https://linux-hardware.org/?probe=e30b2b43fd) | Jul 01, 2025 |
| Dell          | 0GDG8Y A00                  | [23b62d328b](https://linux-hardware.org/?probe=23b62d328b) | Jul 01, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [025f6c6554](https://linux-hardware.org/?probe=025f6c6554) | Jun 30, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8be12059dd](https://linux-hardware.org/?probe=8be12059dd) | Jun 30, 2025 |
| ASUSTek       | PRIME H510M-A               | [18356cc945](https://linux-hardware.org/?probe=18356cc945) | Jun 30, 2025 |
| ASUSTek       | PRIME H510M-A               | [a6acbbbc43](https://linux-hardware.org/?probe=a6acbbbc43) | Jun 30, 2025 |
| Gigabyte      | H87M-HD3                    | [7d51a9399e](https://linux-hardware.org/?probe=7d51a9399e) | Jun 29, 2025 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [6c60a6895e](https://linux-hardware.org/?probe=6c60a6895e) | Jun 29, 2025 |
| OEM           | A320                        | [7711dab79f](https://linux-hardware.org/?probe=7711dab79f) | Jun 29, 2025 |
| MSI           | B250M PRO-VDH               | [4b3a3d9750](https://linux-hardware.org/?probe=4b3a3d9750) | Jun 27, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | [8ab71a2e18](https://linux-hardware.org/?probe=8ab71a2e18) | Jun 27, 2025 |
| ASRock        | H510 Pro BTC+               | [20a493e44e](https://linux-hardware.org/?probe=20a493e44e) | Jun 27, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8dae128c9f](https://linux-hardware.org/?probe=8dae128c9f) | Jun 26, 2025 |
| ASRock        | B550 Steel Legend           | [a255c46bad](https://linux-hardware.org/?probe=a255c46bad) | Jun 25, 2025 |
| ASRock        | AB350 Pro4                  | [4d77d25e6a](https://linux-hardware.org/?probe=4d77d25e6a) | Jun 25, 2025 |
| ASUSTek       | PRIME B450-PLUS             | [bf1f1ca99d](https://linux-hardware.org/?probe=bf1f1ca99d) | Jun 25, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | [d97fa57fea](https://linux-hardware.org/?probe=d97fa57fea) | Jun 25, 2025 |
| ASUSTek       | PRIME H310M-A R2.0          | [82679550a3](https://linux-hardware.org/?probe=82679550a3) | Jun 24, 2025 |
| MSI           | B550 GAMING GEN3            | [5d436154ca](https://linux-hardware.org/?probe=5d436154ca) | Jun 24, 2025 |
| Dell          | 042P49 A00                  | [6b3de1100c](https://linux-hardware.org/?probe=6b3de1100c) | Jun 23, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | [5e73d92bfe](https://linux-hardware.org/?probe=5e73d92bfe) | Jun 22, 2025 |
| MSI           | MPG X570 GAMING PLUS        | [4ee47ad231](https://linux-hardware.org/?probe=4ee47ad231) | Jun 21, 2025 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [ad10597018](https://linux-hardware.org/?probe=ad10597018) | Jun 21, 2025 |
| Dell          | 0WR7PY A01                  | [5a6a31c395](https://linux-hardware.org/?probe=5a6a31c395) | Jun 20, 2025 |
| TB            | WTR R1                      | [9339bbea2a](https://linux-hardware.org/?probe=9339bbea2a) | Jun 18, 2025 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [67bbb57ac4](https://linux-hardware.org/?probe=67bbb57ac4) | Jun 18, 2025 |
| Dell          | 0MGK50 A02                  | [5f154ba5b2](https://linux-hardware.org/?probe=5f154ba5b2) | Jun 18, 2025 |
| OEM           | A320                        | [c2d0c37150](https://linux-hardware.org/?probe=c2d0c37150) | Jun 17, 2025 |
| ASUSTek       | H110M-A                     | [fff07d4b83](https://linux-hardware.org/?probe=fff07d4b83) | Jun 17, 2025 |
| ASUSTek       | Z170-A                      | [2f95408e10](https://linux-hardware.org/?probe=2f95408e10) | Jun 17, 2025 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [1c2a55b940](https://linux-hardware.org/?probe=1c2a55b940) | Jun 15, 2025 |
| Dell          | 0Y0MYH A01                  | [3b37d1be73](https://linux-hardware.org/?probe=3b37d1be73) | Jun 15, 2025 |
| MSI           | MPG X870E EDGE TI WIFI      | [4aa756f34e](https://linux-hardware.org/?probe=4aa756f34e) | Jun 14, 2025 |
| ECS           | H110M4-C23                  | [77fbbfca0a](https://linux-hardware.org/?probe=77fbbfca0a) | Jun 14, 2025 |
| ECS           | H110M4-C23                  | [95ab95e669](https://linux-hardware.org/?probe=95ab95e669) | Jun 14, 2025 |
| Gigabyte      | B450 AORUS M                | [185b31c190](https://linux-hardware.org/?probe=185b31c190) | Jun 14, 2025 |
| MSI           | MPG X870E EDGE TI WIFI      | [27b222f63b](https://linux-hardware.org/?probe=27b222f63b) | Jun 13, 2025 |
| ASUSTek       | P8H67-M LE                  | [19ded07410](https://linux-hardware.org/?probe=19ded07410) | Jun 13, 2025 |
| Gigabyte      | Z790 GAMING X AX            | [8e4e937252](https://linux-hardware.org/?probe=8e4e937252) | Jun 13, 2025 |
| ASUSTek       | PRIME B450M-K II            | [21c647bc87](https://linux-hardware.org/?probe=21c647bc87) | Jun 12, 2025 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [b9f35c3fb1](https://linux-hardware.org/?probe=b9f35c3fb1) | Jun 12, 2025 |
| ASUSTek       | PRIME Z370-A II             | [c40de95cc6](https://linux-hardware.org/?probe=c40de95cc6) | Jun 12, 2025 |
| Gigabyte      | 970A-DS3P                   | [fc089ea8ab](https://linux-hardware.org/?probe=fc089ea8ab) | Jun 12, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [c1cb60a674](https://linux-hardware.org/?probe=c1cb60a674) | Jun 12, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [34c3d89f0d](https://linux-hardware.org/?probe=34c3d89f0d) | Jun 12, 2025 |
| ASRock        | B450M Pro4                  | [f39c0bcca8](https://linux-hardware.org/?probe=f39c0bcca8) | Jun 12, 2025 |
| ASUSTek       | PRIME A320M-R               | [1ff5f95d1a](https://linux-hardware.org/?probe=1ff5f95d1a) | Jun 11, 2025 |
| Acer          | Aspire X3400                | [2cb6c08951](https://linux-hardware.org/?probe=2cb6c08951) | Jun 10, 2025 |
| Gigabyte      | B550M DS3H AC               | [90a3c74499](https://linux-hardware.org/?probe=90a3c74499) | Jun 10, 2025 |
| Gigabyte      | B550M DS3H AC               | [2ffe243a85](https://linux-hardware.org/?probe=2ffe243a85) | Jun 10, 2025 |
| Lenovo        | Annapurna CRB NO DPK        | [08e436924f](https://linux-hardware.org/?probe=08e436924f) | Jun 10, 2025 |
| Dell          | 0XFWHV A00                  | [a461dc2ba0](https://linux-hardware.org/?probe=a461dc2ba0) | Jun 10, 2025 |
| Unknown       | X99H                        | [2fa6d80bc2](https://linux-hardware.org/?probe=2fa6d80bc2) | Jun 10, 2025 |
| ASUSTek       | PRIME B350M-A               | [439ac0394d](https://linux-hardware.org/?probe=439ac0394d) | Jun 10, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [1ca7567bb8](https://linux-hardware.org/?probe=1ca7567bb8) | Jun 09, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [8cf27e6a9b](https://linux-hardware.org/?probe=8cf27e6a9b) | Jun 09, 2025 |
| Gigabyte      | B560M DS3H V2               | [467c0b4037](https://linux-hardware.org/?probe=467c0b4037) | Jun 09, 2025 |
| ASUSTek       | Z170-A                      | [67d387ebcc](https://linux-hardware.org/?probe=67d387ebcc) | Jun 08, 2025 |
| ASUSTek       | Z170-A                      | [8bfcd53f88](https://linux-hardware.org/?probe=8bfcd53f88) | Jun 08, 2025 |
| Gigabyte      | H110-D3A-CF                 | [026c5e0588](https://linux-hardware.org/?probe=026c5e0588) | Jun 08, 2025 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [e69910fd08](https://linux-hardware.org/?probe=e69910fd08) | Jun 08, 2025 |
| TB            | WTR R1                      | [eced865450](https://linux-hardware.org/?probe=eced865450) | Jun 07, 2025 |
| Gigabyte      | B360HD3                     | [628f932304](https://linux-hardware.org/?probe=628f932304) | Jun 07, 2025 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [25210c3391](https://linux-hardware.org/?probe=25210c3391) | Jun 07, 2025 |
| Gigabyte      | B360HD3                     | [2c7ce92dd7](https://linux-hardware.org/?probe=2c7ce92dd7) | Jun 07, 2025 |
| Shenzhen M... | DRFXI                       | [dffabcb1e1](https://linux-hardware.org/?probe=dffabcb1e1) | Jun 06, 2025 |
| EVGA          | 122-CK-NF68 2               | [571b56d7f4](https://linux-hardware.org/?probe=571b56d7f4) | Jun 06, 2025 |
| Dell          | 0KWVT8 A03                  | [a596a1a6b9](https://linux-hardware.org/?probe=a596a1a6b9) | Jun 05, 2025 |
| ASRock        | X670E Pro RS                | [5499fc163b](https://linux-hardware.org/?probe=5499fc163b) | Jun 05, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | [e744e49f1f](https://linux-hardware.org/?probe=e744e49f1f) | Jun 04, 2025 |
| Gigabyte      | H510M H V2                  | [0d50dcdd44](https://linux-hardware.org/?probe=0d50dcdd44) | Jun 04, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | [fd5e831244](https://linux-hardware.org/?probe=fd5e831244) | Jun 03, 2025 |
| ASRock        | B450M Steel Legend          | [cbc5d138b1](https://linux-hardware.org/?probe=cbc5d138b1) | Jun 02, 2025 |
| MSI           | B550-A PRO                  | [8748d40f65](https://linux-hardware.org/?probe=8748d40f65) | Jun 01, 2025 |
| MSI           | PRO B650-VC WIFI III        | [dfcf4497d1](https://linux-hardware.org/?probe=dfcf4497d1) | Jun 01, 2025 |
| Gigabyte      | B550 GAMING X               | [b1b086c9b3](https://linux-hardware.org/?probe=b1b086c9b3) | Jun 01, 2025 |
| HP            | 304Bh                       | [b1de5224a3](https://linux-hardware.org/?probe=b1de5224a3) | Jun 01, 2025 |
| ASRock        | X670E Pro RS                | [cc79a3efb6](https://linux-hardware.org/?probe=cc79a3efb6) | May 31, 2025 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [e11793091a](https://linux-hardware.org/?probe=e11793091a) | May 31, 2025 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [e21c4822ed](https://linux-hardware.org/?probe=e21c4822ed) | May 30, 2025 |
| Biostar       | B450MHP                     | [b45c9dfebc](https://linux-hardware.org/?probe=b45c9dfebc) | May 29, 2025 |
| Biostar       | A960D+                      | [57901d0614](https://linux-hardware.org/?probe=57901d0614) | May 29, 2025 |
| MSI           | Z97-G43 GAMING              | [11f8307447](https://linux-hardware.org/?probe=11f8307447) | May 28, 2025 |
| Dell          | 0MGK50 A02                  | [3a5f3483e9](https://linux-hardware.org/?probe=3a5f3483e9) | May 28, 2025 |
| ASUSTek       | P8H77-V                     | [0578406eab](https://linux-hardware.org/?probe=0578406eab) | May 28, 2025 |
| ASUSTek       | PRIME B550M-A               | [1aea6249c6](https://linux-hardware.org/?probe=1aea6249c6) | May 28, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b561368a00](https://linux-hardware.org/?probe=b561368a00) | May 28, 2025 |
| ASRock        | B450M/ac                    | [e173323e28](https://linux-hardware.org/?probe=e173323e28) | May 28, 2025 |
| Gigabyte      | Z97P-D3                     | [180e79f717](https://linux-hardware.org/?probe=180e79f717) | May 27, 2025 |
| ASUSTek       | H110M-C                     | [e932ca6c9e](https://linux-hardware.org/?probe=e932ca6c9e) | May 27, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | [6ca54549bc](https://linux-hardware.org/?probe=6ca54549bc) | May 27, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | [02c9278d2a](https://linux-hardware.org/?probe=02c9278d2a) | May 27, 2025 |
| Gigabyte      | GA-MA790GP-DS4H             | [1badbb9ab5](https://linux-hardware.org/?probe=1badbb9ab5) | May 25, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [9d820301d5](https://linux-hardware.org/?probe=9d820301d5) | May 25, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [96452e46ed](https://linux-hardware.org/?probe=96452e46ed) | May 25, 2025 |
| Gigabyte      | B450 AORUS ELITE            | [d10f24db70](https://linux-hardware.org/?probe=d10f24db70) | May 25, 2025 |
| ASRock        | Z170 OC Formula             | [bfae22fc32](https://linux-hardware.org/?probe=bfae22fc32) | May 24, 2025 |
| Gigabyte      | GA-MA790GP-DS4H             | [2dbc0de329](https://linux-hardware.org/?probe=2dbc0de329) | May 24, 2025 |
| ASUSTek       | PRIME Z390-P                | [093bcc8aa2](https://linux-hardware.org/?probe=093bcc8aa2) | May 23, 2025 |
| Dell          | 02GDWG A00                  | [1184ab367e](https://linux-hardware.org/?probe=1184ab367e) | May 23, 2025 |
| Gigabyte      | H61M-S2PV                   | [98d836b313](https://linux-hardware.org/?probe=98d836b313) | May 23, 2025 |
| MSI           | PRO Z690-A DDR4             | [976223f600](https://linux-hardware.org/?probe=976223f600) | May 22, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [1df2982051](https://linux-hardware.org/?probe=1df2982051) | May 22, 2025 |
| Dell          | 0XJ8C4 A00                  | [c21635ea7f](https://linux-hardware.org/?probe=c21635ea7f) | May 22, 2025 |
| MSI           | X58M                        | [a7b49fb9cd](https://linux-hardware.org/?probe=a7b49fb9cd) | May 22, 2025 |
| ASRock        | Z270 Pro4                   | [84332bc322](https://linux-hardware.org/?probe=84332bc322) | May 21, 2025 |
| Gigabyte      | A520M K V2                  | [c3a3fa7aa5](https://linux-hardware.org/?probe=c3a3fa7aa5) | May 21, 2025 |
| System76      | Thelio thelio-b3            | [f770d5052a](https://linux-hardware.org/?probe=f770d5052a) | May 21, 2025 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [6924405872](https://linux-hardware.org/?probe=6924405872) | May 20, 2025 |
| Gigabyte      | A520M K V2                  | [fa69074ff5](https://linux-hardware.org/?probe=fa69074ff5) | May 20, 2025 |
| Gigabyte      | B250M-D3H-CF                | [ad2000a55f](https://linux-hardware.org/?probe=ad2000a55f) | May 20, 2025 |
| MSI           | Z370-A PRO                  | [cc9a737d16](https://linux-hardware.org/?probe=cc9a737d16) | May 19, 2025 |
| HP            | 8054                        | [a33eed6e8b](https://linux-hardware.org/?probe=a33eed6e8b) | May 19, 2025 |
| Intel         | H61                         | [d777b95d1b](https://linux-hardware.org/?probe=d777b95d1b) | May 19, 2025 |
| Lenovo        | SHARKBAY NOK                | [61b05410fb](https://linux-hardware.org/?probe=61b05410fb) | May 18, 2025 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ff12d95a2f](https://linux-hardware.org/?probe=ff12d95a2f) | May 17, 2025 |
| ASUSTek       | Z170-K                      | [c9314de9b0](https://linux-hardware.org/?probe=c9314de9b0) | May 17, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [6542eea559](https://linux-hardware.org/?probe=6542eea559) | May 17, 2025 |
| ASUSTek       | Maximus IX HERO             | [308f34ffd6](https://linux-hardware.org/?probe=308f34ffd6) | May 17, 2025 |
| Dell          | 040DDP A01                  | [9a8028bc96](https://linux-hardware.org/?probe=9a8028bc96) | May 16, 2025 |
| System76      | Thelio Mira thelio-mira-... | [de7e35dc53](https://linux-hardware.org/?probe=de7e35dc53) | May 16, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [1042e492c6](https://linux-hardware.org/?probe=1042e492c6) | May 16, 2025 |
| HP            | 0B54h D                     | [e711359c36](https://linux-hardware.org/?probe=e711359c36) | May 15, 2025 |
| ASRock        | X300M-STX                   | [9db19f1ced](https://linux-hardware.org/?probe=9db19f1ced) | May 15, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [f6a73a5c3c](https://linux-hardware.org/?probe=f6a73a5c3c) | May 15, 2025 |
| Dell          | 08NPPY A00                  | [bd3cc94da9](https://linux-hardware.org/?probe=bd3cc94da9) | May 15, 2025 |
| Gigabyte      | A320M-S2H-CF                | [df322b9e0c](https://linux-hardware.org/?probe=df322b9e0c) | May 14, 2025 |
| ASUSTek       | Z170-K                      | [cc09c4c4bd](https://linux-hardware.org/?probe=cc09c4c4bd) | May 14, 2025 |
| Biostar       | H81MHV3 5.0                 | [cf1a9f123c](https://linux-hardware.org/?probe=cf1a9f123c) | May 14, 2025 |
| ASUSTek       | Maximus V FORMULA           | [56c89e1ee5](https://linux-hardware.org/?probe=56c89e1ee5) | May 14, 2025 |
| HP            | 845A                        | [6c65960af4](https://linux-hardware.org/?probe=6c65960af4) | May 13, 2025 |
| ASUSTek       | PRIME B450-PLUS             | [68212830e6](https://linux-hardware.org/?probe=68212830e6) | May 13, 2025 |
| HP            | 845A                        | [ae30bf928c](https://linux-hardware.org/?probe=ae30bf928c) | May 13, 2025 |
| TB            | WTR R1                      | [41a5817138](https://linux-hardware.org/?probe=41a5817138) | May 12, 2025 |
| Gigabyte      | X870 EAGLE WIFI7            | [be53c67c7a](https://linux-hardware.org/?probe=be53c67c7a) | May 12, 2025 |
| ASUSTek       | PRIME B550M-A               | [d4ddba39f5](https://linux-hardware.org/?probe=d4ddba39f5) | May 12, 2025 |
| Wistron       | JIB75Y2                     | [d5e1b44496](https://linux-hardware.org/?probe=d5e1b44496) | May 12, 2025 |
| Gigabyte      | G31M-ES2L                   | [d643da39a0](https://linux-hardware.org/?probe=d643da39a0) | May 11, 2025 |
| ASUSTek       | STRIX Z270F GAMING          | [5978297fa9](https://linux-hardware.org/?probe=5978297fa9) | May 11, 2025 |
| Gigabyte      | B550 UD AC-Y1               | [01ce7f4ada](https://linux-hardware.org/?probe=01ce7f4ada) | May 10, 2025 |
| ASUSTek       | ROG Maximus XIII HERO       | [a55c10fb98](https://linux-hardware.org/?probe=a55c10fb98) | May 09, 2025 |
| HP            | 8054                        | [7384d97f25](https://linux-hardware.org/?probe=7384d97f25) | May 09, 2025 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [c64126a67d](https://linux-hardware.org/?probe=c64126a67d) | May 08, 2025 |
| ASRock        | B550 Phantom Gaming 4/ac    | [12624942ea](https://linux-hardware.org/?probe=12624942ea) | May 07, 2025 |
| ASRock        | B450 Gaming-ITX/ac          | [7852d3931f](https://linux-hardware.org/?probe=7852d3931f) | May 07, 2025 |
| Gigabyte      | H610M H DDR4                | [d494e36786](https://linux-hardware.org/?probe=d494e36786) | May 07, 2025 |
| ASUSTek       | PRIME X570-PRO              | [24e4046c23](https://linux-hardware.org/?probe=24e4046c23) | May 07, 2025 |
| Biostar       | B350ET2                     | [319e73b776](https://linux-hardware.org/?probe=319e73b776) | May 06, 2025 |
| ASUSTek       | PRIME X470-PRO              | [f2f22305e9](https://linux-hardware.org/?probe=f2f22305e9) | May 04, 2025 |
| ASUSTek       | PRIME B450M-K II            | [e5c37bdd45](https://linux-hardware.org/?probe=e5c37bdd45) | May 04, 2025 |
| Dell          | 040DDP A01                  | [6232bb7896](https://linux-hardware.org/?probe=6232bb7896) | May 04, 2025 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [add8af650c](https://linux-hardware.org/?probe=add8af650c) | May 04, 2025 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0540f5acf8](https://linux-hardware.org/?probe=0540f5acf8) | May 03, 2025 |
| Dell          | 0GDG8Y A00                  | [1fa090d700](https://linux-hardware.org/?probe=1fa090d700) | May 03, 2025 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [285844f02b](https://linux-hardware.org/?probe=285844f02b) | May 03, 2025 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a90e40e113](https://linux-hardware.org/?probe=a90e40e113) | May 02, 2025 |
| ASUSTek       | PRIME H610M-D D4            | [744ddeb617](https://linux-hardware.org/?probe=744ddeb617) | May 02, 2025 |
| Gigabyte      | GA-78LMT-USB3               | [ad81cfdbbf](https://linux-hardware.org/?probe=ad81cfdbbf) | May 01, 2025 |
| ASUSTek       | Maximus VIII HERO           | [37cbd2416e](https://linux-hardware.org/?probe=37cbd2416e) | Apr 30, 2025 |
| MSI           | MS-B9241                    | [c250fa30e0](https://linux-hardware.org/?probe=c250fa30e0) | Apr 30, 2025 |
| MSI           | MS-B9241                    | [2642e349b4](https://linux-hardware.org/?probe=2642e349b4) | Apr 30, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | [4eba973774](https://linux-hardware.org/?probe=4eba973774) | Apr 30, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | [e8047d200e](https://linux-hardware.org/?probe=e8047d200e) | Apr 30, 2025 |
| ASUSTek       | PRIME H270M-PLUS            | [e7e1355bd7](https://linux-hardware.org/?probe=e7e1355bd7) | Apr 29, 2025 |
| ASUSTek       | Maximus VIII HERO           | [8d971924ec](https://linux-hardware.org/?probe=8d971924ec) | Apr 29, 2025 |
| Gigabyte      | X870I AORUS PRO ICE         | [b336bd93d7](https://linux-hardware.org/?probe=b336bd93d7) | Apr 29, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [799aaf1a8e](https://linux-hardware.org/?probe=799aaf1a8e) | Apr 28, 2025 |
| ASUSTek       | PRIME Z790-P WIFI           | [571b059bc7](https://linux-hardware.org/?probe=571b059bc7) | Apr 28, 2025 |
| ASUSTek       | ProArt X870E-CREATOR WIF... | [9e0366790f](https://linux-hardware.org/?probe=9e0366790f) | Apr 28, 2025 |
| Gigabyte      | 970A-DS3P                   | [c19b3fead9](https://linux-hardware.org/?probe=c19b3fead9) | Apr 28, 2025 |
| HP            | 18E7                        | [9040b2af1a](https://linux-hardware.org/?probe=9040b2af1a) | Apr 28, 2025 |
| ASUSTek       | TUF X470-PLUS GAMING        | [b536bb45e7](https://linux-hardware.org/?probe=b536bb45e7) | Apr 27, 2025 |
| HP            | 8298                        | [980290f532](https://linux-hardware.org/?probe=980290f532) | Apr 27, 2025 |
| Gigabyte      | X870E AORUS PRO ICE         | [d631797fc9](https://linux-hardware.org/?probe=d631797fc9) | Apr 27, 2025 |
| Dell          | 09KPNV A00                  | [d2e8af2579](https://linux-hardware.org/?probe=d2e8af2579) | Apr 26, 2025 |
| ASUSTek       | P8Z68-V PRO                 | [6a6d020fc0](https://linux-hardware.org/?probe=6a6d020fc0) | Apr 26, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [48a9b6ddad](https://linux-hardware.org/?probe=48a9b6ddad) | Apr 26, 2025 |
| ASUSTek       | P6T DELUXE V2               | [817145ba57](https://linux-hardware.org/?probe=817145ba57) | Apr 26, 2025 |
| ASRock        | B650 Pro RS                 | [e5275a5733](https://linux-hardware.org/?probe=e5275a5733) | Apr 25, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [a94e0d68cb](https://linux-hardware.org/?probe=a94e0d68cb) | Apr 24, 2025 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a411f0de1f](https://linux-hardware.org/?probe=a411f0de1f) | Apr 23, 2025 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [3c0d522c6e](https://linux-hardware.org/?probe=3c0d522c6e) | Apr 23, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e5a8a718bc](https://linux-hardware.org/?probe=e5a8a718bc) | Apr 23, 2025 |
| MSI           | MPG X570 GAMING PLUS        | [0a3bfe64aa](https://linux-hardware.org/?probe=0a3bfe64aa) | Apr 22, 2025 |
| ASRock        | X670E Steel Legend          | [1f273b8079](https://linux-hardware.org/?probe=1f273b8079) | Apr 22, 2025 |
| ASUSTek       | Pro WS X570-ACE             | [c16836a1f4](https://linux-hardware.org/?probe=c16836a1f4) | Apr 22, 2025 |
| ASRock        | X370M-HDV R4.0              | [0340d25697](https://linux-hardware.org/?probe=0340d25697) | Apr 22, 2025 |
| ASRock        | X370M-HDV R4.0              | [d8c2e14957](https://linux-hardware.org/?probe=d8c2e14957) | Apr 21, 2025 |
| MSI           | 870-C45                     | [70e3234b94](https://linux-hardware.org/?probe=70e3234b94) | Apr 21, 2025 |
| MSI           | PRO X870-P WIFI             | [d1b072116c](https://linux-hardware.org/?probe=d1b072116c) | Apr 21, 2025 |
| Acer          | Extensa M2610 V:1.0         | [d9c50940e3](https://linux-hardware.org/?probe=d9c50940e3) | Apr 20, 2025 |
| Acer          | Extensa M2610 V:1.0         | [088a7a8bf0](https://linux-hardware.org/?probe=088a7a8bf0) | Apr 20, 2025 |
| ASUSTek       | P9X79                       | [859c9cb904](https://linux-hardware.org/?probe=859c9cb904) | Apr 18, 2025 |
| Intel         | H61                         | [5390a250da](https://linux-hardware.org/?probe=5390a250da) | Apr 18, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | [2003d540ad](https://linux-hardware.org/?probe=2003d540ad) | Apr 18, 2025 |
| MSI           | Z390-A PRO                  | [61476bffd6](https://linux-hardware.org/?probe=61476bffd6) | Apr 18, 2025 |
| ASUSTek       | P8H67-M LE                  | [f49cf18c87](https://linux-hardware.org/?probe=f49cf18c87) | Apr 17, 2025 |
| ASRock        | B760M PG Riptide            | [433251e257](https://linux-hardware.org/?probe=433251e257) | Apr 16, 2025 |
| MSI           | 990FXA GAMING               | [408e9aac86](https://linux-hardware.org/?probe=408e9aac86) | Apr 16, 2025 |
| Gigabyte      | B660 DS3H AC DDR4-Y1        | [2ede59a32f](https://linux-hardware.org/?probe=2ede59a32f) | Apr 16, 2025 |
| ASUSTek       | PRIME A320M-K/BR            | [a0075dd3de](https://linux-hardware.org/?probe=a0075dd3de) | Apr 15, 2025 |
| ASUSTek       | PRIME A320M-K/BR            | [7166199f84](https://linux-hardware.org/?probe=7166199f84) | Apr 15, 2025 |
| Gigabyte      | B550M AORUS PRO             | [e519afbf87](https://linux-hardware.org/?probe=e519afbf87) | Apr 15, 2025 |
| HP            | 2129                        | [e99abfc91d](https://linux-hardware.org/?probe=e99abfc91d) | Apr 15, 2025 |
| GEEKOM        | A5                          | [9a2fee93f1](https://linux-hardware.org/?probe=9a2fee93f1) | Apr 15, 2025 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [12dc178928](https://linux-hardware.org/?probe=12dc178928) | Apr 15, 2025 |
| ASUSTek       | STRIX Z270F GAMING          | [e655aa4b0b](https://linux-hardware.org/?probe=e655aa4b0b) | Apr 15, 2025 |
| MSI           | B450M MORTAR MAX            | [d7d2f5a3bc](https://linux-hardware.org/?probe=d7d2f5a3bc) | Apr 15, 2025 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [6712c217a3](https://linux-hardware.org/?probe=6712c217a3) | Apr 15, 2025 |
| ASUSTek       | ROG Maximus X HERO          | [12d9b9e8e9](https://linux-hardware.org/?probe=12d9b9e8e9) | Apr 14, 2025 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [565a5da8d5](https://linux-hardware.org/?probe=565a5da8d5) | Apr 14, 2025 |
| HP            | 82F2                        | [941b1d8236](https://linux-hardware.org/?probe=941b1d8236) | Apr 14, 2025 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [2eb0f3ad52](https://linux-hardware.org/?probe=2eb0f3ad52) | Apr 14, 2025 |
| ASRock        | X79 Champion                | [cd9df643eb](https://linux-hardware.org/?probe=cd9df643eb) | Apr 14, 2025 |
| MACHINST      | X99-K9 V5.1                 | [50ee3232ee](https://linux-hardware.org/?probe=50ee3232ee) | Apr 13, 2025 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [37d3fbc4c8](https://linux-hardware.org/?probe=37d3fbc4c8) | Apr 13, 2025 |
| Gigabyte      | Z790 GAMING PLUS AX         | [f2c7e256eb](https://linux-hardware.org/?probe=f2c7e256eb) | Apr 12, 2025 |
| ASRock        | B450M Steel Legend          | [23ca13fa78](https://linux-hardware.org/?probe=23ca13fa78) | Apr 12, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [1f16c7af30](https://linux-hardware.org/?probe=1f16c7af30) | Apr 10, 2025 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [3c8abc7227](https://linux-hardware.org/?probe=3c8abc7227) | Apr 10, 2025 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [f60f1f7f95](https://linux-hardware.org/?probe=f60f1f7f95) | Apr 10, 2025 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [df97de5f07](https://linux-hardware.org/?probe=df97de5f07) | Apr 09, 2025 |
| Gigabyte      | B650M AORUS ELITE AX        | [41c1b94f08](https://linux-hardware.org/?probe=41c1b94f08) | Apr 09, 2025 |
| TB            | WTR R1                      | [2a63457459](https://linux-hardware.org/?probe=2a63457459) | Apr 08, 2025 |
| HP            | 3033h                       | [d890fc818f](https://linux-hardware.org/?probe=d890fc818f) | Apr 08, 2025 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [156543235a](https://linux-hardware.org/?probe=156543235a) | Apr 08, 2025 |
| ASRock        | B660M-HDV                   | [1f19d4d93a](https://linux-hardware.org/?probe=1f19d4d93a) | Apr 07, 2025 |
| ASUSTek       | PRIME X370-PRO              | [b1513aea2a](https://linux-hardware.org/?probe=b1513aea2a) | Apr 07, 2025 |
| HP            | 2129                        | [6169c1f6ee](https://linux-hardware.org/?probe=6169c1f6ee) | Apr 07, 2025 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [2a183dbcf6](https://linux-hardware.org/?probe=2a183dbcf6) | Apr 07, 2025 |
| AFOX          | IH61-MA5                    | [b8adb34295](https://linux-hardware.org/?probe=b8adb34295) | Apr 07, 2025 |
| Acer          | Aspire TC-885 V:1.1         | [49604bbd4d](https://linux-hardware.org/?probe=49604bbd4d) | Apr 06, 2025 |
| ASUSTek       | H97-PRO                     | [5d2df08d8f](https://linux-hardware.org/?probe=5d2df08d8f) | Apr 06, 2025 |
| Gigabyte      | Z270N-WIFI-CF               | [e7b5ee8696](https://linux-hardware.org/?probe=e7b5ee8696) | Apr 05, 2025 |
| Acer          | Aspire TC-120               | [d93c6c41c0](https://linux-hardware.org/?probe=d93c6c41c0) | Apr 05, 2025 |
| ASUSTek       | Maximus IX HERO             | [9f52c781d7](https://linux-hardware.org/?probe=9f52c781d7) | Apr 05, 2025 |
| Dell          | 02YYK5 A01                  | [448bd03bf0](https://linux-hardware.org/?probe=448bd03bf0) | Apr 02, 2025 |
| Dell          | 02YYK5 A01                  | [80f2a1878e](https://linux-hardware.org/?probe=80f2a1878e) | Apr 02, 2025 |
| Dell          | 03KWTV A02                  | [ced915c57c](https://linux-hardware.org/?probe=ced915c57c) | Apr 02, 2025 |
| Gigabyte      | Z170-HD3-CF                 | [1cd1eff9f6](https://linux-hardware.org/?probe=1cd1eff9f6) | Apr 01, 2025 |
| Gigabyte      | B650 AORUS ELITE AX         | [118e6290e0](https://linux-hardware.org/?probe=118e6290e0) | Apr 01, 2025 |
| MSI           | B450M PRO-VDH MAX           | [608481de1d](https://linux-hardware.org/?probe=608481de1d) | Mar 31, 2025 |
| Gigabyte      | B450 AORUS ELITE V2         | [e11f9d7104](https://linux-hardware.org/?probe=e11f9d7104) | Mar 31, 2025 |
| MSI           | PRO Z790-S WIFI             | [186d616593](https://linux-hardware.org/?probe=186d616593) | Mar 31, 2025 |
| Gigabyte      | Z270N-WIFI-CF               | [8bd9c00c9c](https://linux-hardware.org/?probe=8bd9c00c9c) | Mar 31, 2025 |
| ASRock        | B450M Pro4                  | [f1da31f1b0](https://linux-hardware.org/?probe=f1da31f1b0) | Mar 30, 2025 |
| ASUSTek       | ROG Maximus X HERO          | [2d6fe5fe0a](https://linux-hardware.org/?probe=2d6fe5fe0a) | Mar 29, 2025 |
| Shenzhen M... | F1FXM                       | [7b62a99717](https://linux-hardware.org/?probe=7b62a99717) | Mar 29, 2025 |
| Gigabyte      | H310M H                     | [4cc6beace6](https://linux-hardware.org/?probe=4cc6beace6) | Mar 29, 2025 |
| Gigabyte      | H110M-S2H-CF                | [3ac4120d6c](https://linux-hardware.org/?probe=3ac4120d6c) | Mar 28, 2025 |
| ASRock        | B860 Pro-A                  | [a3861bf72b](https://linux-hardware.org/?probe=a3861bf72b) | Mar 28, 2025 |
| Lenovo        | 0B98401 PRO                 | [9352add964](https://linux-hardware.org/?probe=9352add964) | Mar 28, 2025 |
| Lenovo        | 0B98401 PRO                 | [874a170776](https://linux-hardware.org/?probe=874a170776) | Mar 28, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | [4ca2360498](https://linux-hardware.org/?probe=4ca2360498) | Mar 27, 2025 |
| Lenovo        | ThinkStation S20 4157V8S    | [6bd184a1c5](https://linux-hardware.org/?probe=6bd184a1c5) | Mar 27, 2025 |
| MSI           | B450M PRO-M2 V2             | [be94c6e5e5](https://linux-hardware.org/?probe=be94c6e5e5) | Mar 27, 2025 |
| MSI           | B450M PRO-M2 V2             | [e537a268d5](https://linux-hardware.org/?probe=e537a268d5) | Mar 27, 2025 |
| ASUSTek       | TUF Gaming X870-PLUS WIF... | [90fa81b62c](https://linux-hardware.org/?probe=90fa81b62c) | Mar 26, 2025 |
| MSI           | PRO B650-S WIFI             | [da1c1d7dbb](https://linux-hardware.org/?probe=da1c1d7dbb) | Mar 26, 2025 |
| Gigabyte      | H270M-DS3H-CF               | [a88beab7b9](https://linux-hardware.org/?probe=a88beab7b9) | Mar 25, 2025 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [da2ec2fcec](https://linux-hardware.org/?probe=da2ec2fcec) | Mar 23, 2025 |
| Gigabyte      | 970A-DS3P                   | [4af0bbc6ca](https://linux-hardware.org/?probe=4af0bbc6ca) | Mar 23, 2025 |
| Gigabyte      | Z170-HD3-CF                 | [e465868c32](https://linux-hardware.org/?probe=e465868c32) | Mar 23, 2025 |
| Gigabyte      | B365M HD3                   | [d85c5b9e52](https://linux-hardware.org/?probe=d85c5b9e52) | Mar 23, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | [c32b866cf1](https://linux-hardware.org/?probe=c32b866cf1) | Mar 23, 2025 |
| MSI           | A520M-A PRO                 | [b3276b0e21](https://linux-hardware.org/?probe=b3276b0e21) | Mar 23, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f354cc4c3b](https://linux-hardware.org/?probe=f354cc4c3b) | Mar 23, 2025 |
| MSI           | MAG B460M MORTAR            | [279bdfc1a5](https://linux-hardware.org/?probe=279bdfc1a5) | Mar 23, 2025 |
| HP            | 18E7                        | [9174b401ef](https://linux-hardware.org/?probe=9174b401ef) | Mar 22, 2025 |
| MSI           | MPG X570 GAMING PLUS        | [c2cfe3d1a9](https://linux-hardware.org/?probe=c2cfe3d1a9) | Mar 22, 2025 |
| MSI           | X399 GAMING PRO CARBON A... | [5442ae4be7](https://linux-hardware.org/?probe=5442ae4be7) | Mar 22, 2025 |
| Gigabyte      | Z170-HD3-CF                 | [e98704bb5d](https://linux-hardware.org/?probe=e98704bb5d) | Mar 22, 2025 |
| Gigabyte      | H270M-DS3H-CF               | [59a8e49d1f](https://linux-hardware.org/?probe=59a8e49d1f) | Mar 22, 2025 |
| Intel         | H61                         | [5b359eabb8](https://linux-hardware.org/?probe=5b359eabb8) | Mar 21, 2025 |
| MSI           | A520M-A PRO                 | [a45e1969c8](https://linux-hardware.org/?probe=a45e1969c8) | Mar 20, 2025 |
| ASUSTek       | P8H67-M LE                  | [fc997a1e9d](https://linux-hardware.org/?probe=fc997a1e9d) | Mar 19, 2025 |
| ASRock        | H110M-STX                   | [d99ff61abb](https://linux-hardware.org/?probe=d99ff61abb) | Mar 19, 2025 |
| ASRock        | H110M-STX                   | [771b6490c6](https://linux-hardware.org/?probe=771b6490c6) | Mar 19, 2025 |
| HP            | 845A                        | [3f8889ddd4](https://linux-hardware.org/?probe=3f8889ddd4) | Mar 18, 2025 |
| Gigabyte      | Z790 GAMING PLUS AX         | [00c27a4ac8](https://linux-hardware.org/?probe=00c27a4ac8) | Mar 18, 2025 |
| ASUSTek       | ROG STRIX X870-F GAMING ... | [f16e9d97e4](https://linux-hardware.org/?probe=f16e9d97e4) | Mar 18, 2025 |
| ASUSTek       | ROG STRIX X870-F GAMING ... | [b2d3b4228d](https://linux-hardware.org/?probe=b2d3b4228d) | Mar 18, 2025 |
| Dell          | 0GDG8Y A00                  | [157c27708d](https://linux-hardware.org/?probe=157c27708d) | Mar 17, 2025 |
| MSI           | PRO Z690-A WIFI DDR4        | [98ff080f9e](https://linux-hardware.org/?probe=98ff080f9e) | Mar 17, 2025 |
| Dell          | 0GDG8Y A00                  | [a557951537](https://linux-hardware.org/?probe=a557951537) | Mar 16, 2025 |
| ASUSTek       | ROG STRIX X870-F GAMING ... | [e3a07e081b](https://linux-hardware.org/?probe=e3a07e081b) | Mar 16, 2025 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [275913962b](https://linux-hardware.org/?probe=275913962b) | Mar 16, 2025 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [2dca64128b](https://linux-hardware.org/?probe=2dca64128b) | Mar 15, 2025 |
| ASUSTek       | P8H67-M LE                  | [83e275ded1](https://linux-hardware.org/?probe=83e275ded1) | Mar 15, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [37302fc88a](https://linux-hardware.org/?probe=37302fc88a) | Mar 15, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | [bb5a7bb390](https://linux-hardware.org/?probe=bb5a7bb390) | Mar 13, 2025 |
| Unknown       | Unknown                     | [83ca282459](https://linux-hardware.org/?probe=83ca282459) | Mar 13, 2025 |
| HP            | 339A                        | [97696fbb25](https://linux-hardware.org/?probe=97696fbb25) | Mar 13, 2025 |
| ASUSTek       | PRIME B450-PLUS             | [f296eb3307](https://linux-hardware.org/?probe=f296eb3307) | Mar 12, 2025 |
| ASUSTek       | PRIME B450-PLUS             | [947a0d88f0](https://linux-hardware.org/?probe=947a0d88f0) | Mar 12, 2025 |
| Gigabyte      | X299 UD4 Pro-CF             | [04336eab3b](https://linux-hardware.org/?probe=04336eab3b) | Mar 12, 2025 |
| Shenzhen M... | AHBNB OEM                   | [4e03680f9c](https://linux-hardware.org/?probe=4e03680f9c) | Mar 11, 2025 |
| ASUSTek       | PRIME H270-PLUS             | [fbfe03f140](https://linux-hardware.org/?probe=fbfe03f140) | Mar 11, 2025 |
| Gigabyte      | AB350M-HD3-CF               | [a6689ffdf8](https://linux-hardware.org/?probe=a6689ffdf8) | Mar 11, 2025 |
| MSI           | Z490-A PRO                  | [b7b043df75](https://linux-hardware.org/?probe=b7b043df75) | Mar 11, 2025 |
| HP            | 1589                        | [90ec9d65c1](https://linux-hardware.org/?probe=90ec9d65c1) | Mar 11, 2025 |
| HP            | 1589                        | [d13b448120](https://linux-hardware.org/?probe=d13b448120) | Mar 11, 2025 |
| Intel         | IPC-ADN2L                   | [48e1bd5630](https://linux-hardware.org/?probe=48e1bd5630) | Mar 10, 2025 |
| MSI           | Z170A PC MATE               | [d005c95654](https://linux-hardware.org/?probe=d005c95654) | Mar 10, 2025 |
| MSI           | Z87-GD65 GAMING             | [a17c4c135c](https://linux-hardware.org/?probe=a17c4c135c) | Mar 09, 2025 |
| Gigabyte      | G1.Sniper B5-CF             | [380e558ea5](https://linux-hardware.org/?probe=380e558ea5) | Mar 09, 2025 |
| Gigabyte      | B550M DS3H                  | [bae7014de3](https://linux-hardware.org/?probe=bae7014de3) | Mar 08, 2025 |
| MSI           | AM1I                        | [9ac07ef6f4](https://linux-hardware.org/?probe=9ac07ef6f4) | Mar 08, 2025 |
| MSI           | AM1I                        | [f706570d70](https://linux-hardware.org/?probe=f706570d70) | Mar 08, 2025 |
| ASUSTek       | G16CHR                      | [156e3ddbd1](https://linux-hardware.org/?probe=156e3ddbd1) | Mar 08, 2025 |
| ASUSTek       | ROG Maximus Z790 DARK HE... | [bd0b1c2a0e](https://linux-hardware.org/?probe=bd0b1c2a0e) | Mar 08, 2025 |
| Gigabyte      | H370M D3H GSM-CF            | [600fe07e01](https://linux-hardware.org/?probe=600fe07e01) | Mar 07, 2025 |
| Gigabyte      | Z270M-D3H-CF                | [c574e627f9](https://linux-hardware.org/?probe=c574e627f9) | Mar 07, 2025 |
| ASUSTek       | H110M-A/M.2                 | [620eb6cb12](https://linux-hardware.org/?probe=620eb6cb12) | Mar 07, 2025 |
| System76      | Thelio Mira thelio-mira-... | [54aa975b86](https://linux-hardware.org/?probe=54aa975b86) | Mar 07, 2025 |
| MSI           | PRO B650M-A WIFI            | [9156ad042b](https://linux-hardware.org/?probe=9156ad042b) | Mar 06, 2025 |
| ASRock        | B75M R2.0                   | [bead3a3aee](https://linux-hardware.org/?probe=bead3a3aee) | Mar 06, 2025 |
| Gigabyte      | X670 AORUS ELITE AX         | [1091b54a61](https://linux-hardware.org/?probe=1091b54a61) | Mar 06, 2025 |
| Gigabyte      | 970A-DS3P                   | [46aa879d2e](https://linux-hardware.org/?probe=46aa879d2e) | Mar 06, 2025 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [1c90ce9672](https://linux-hardware.org/?probe=1c90ce9672) | Mar 06, 2025 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [69609c41fd](https://linux-hardware.org/?probe=69609c41fd) | Mar 06, 2025 |
| ASRock        | Z690 PG Riptide             | [a3d0ae24df](https://linux-hardware.org/?probe=a3d0ae24df) | Mar 05, 2025 |
| Gigabyte      | H81M-H                      | [bd39f4a655](https://linux-hardware.org/?probe=bd39f4a655) | Mar 05, 2025 |
| ASUSTek       | Maximus VII RANGER          | [642aaae24f](https://linux-hardware.org/?probe=642aaae24f) | Mar 05, 2025 |
| ASRock        | X570 Phantom Gaming 4S      | [ec6a9e0c4b](https://linux-hardware.org/?probe=ec6a9e0c4b) | Mar 04, 2025 |
| Dell          | 0GDG8Y A00                  | [338fdd5365](https://linux-hardware.org/?probe=338fdd5365) | Mar 04, 2025 |
| ASUSTek       | ROG STRIX X870-F GAMING ... | [4c767836f2](https://linux-hardware.org/?probe=4c767836f2) | Mar 04, 2025 |
| ASRock        | X79 Champion                | [9970f3187a](https://linux-hardware.org/?probe=9970f3187a) | Mar 03, 2025 |
| MSI           | B650 GAMING PLUS WIFI       | [6e190fa5a2](https://linux-hardware.org/?probe=6e190fa5a2) | Mar 01, 2025 |
| ASRock        | X79 Champion                | [e60f60a23e](https://linux-hardware.org/?probe=e60f60a23e) | Mar 01, 2025 |
| ASRock        | 960GM-GS3 FX                | [2123f2997c](https://linux-hardware.org/?probe=2123f2997c) | Feb 28, 2025 |
| ASRock        | 960GM-GS3 FX                | [9f2b1682cb](https://linux-hardware.org/?probe=9f2b1682cb) | Feb 28, 2025 |
| Intel         | IPC-ADN2L                   | [e606662480](https://linux-hardware.org/?probe=e606662480) | Feb 28, 2025 |
| HC Technol... | HCAR5000-MI                 | [714e34fa05](https://linux-hardware.org/?probe=714e34fa05) | Feb 28, 2025 |
| ASUSTek       | B150M-C/BR                  | [23c0d4b9d8](https://linux-hardware.org/?probe=23c0d4b9d8) | Feb 28, 2025 |
| HP            | 18E6                        | [416b753197](https://linux-hardware.org/?probe=416b753197) | Feb 28, 2025 |
| Gigabyte      | X570 AORUS MASTER           | [3eed998eb0](https://linux-hardware.org/?probe=3eed998eb0) | Feb 27, 2025 |
| ASUSTek       | F2A85-M                     | [720f04f49d](https://linux-hardware.org/?probe=720f04f49d) | Feb 27, 2025 |
| Shenzhen M... | DRBAA                       | [2f3fddf030](https://linux-hardware.org/?probe=2f3fddf030) | Feb 27, 2025 |
| Unknown       | DELTA-H61M2K                | [c1e85ae9ac](https://linux-hardware.org/?probe=c1e85ae9ac) | Feb 26, 2025 |
| ASUSTek       | ProArt B650-CREATOR         | [3ed834703c](https://linux-hardware.org/?probe=3ed834703c) | Feb 26, 2025 |
| Gigabyte      | B650 GAMING X AX            | [c4e0321cbe](https://linux-hardware.org/?probe=c4e0321cbe) | Feb 26, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [ca6e2a1e4a](https://linux-hardware.org/?probe=ca6e2a1e4a) | Feb 26, 2025 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [cbc35482e3](https://linux-hardware.org/?probe=cbc35482e3) | Feb 26, 2025 |
| ASUSTek       | PRIME B450M-K               | [b56c7b6f97](https://linux-hardware.org/?probe=b56c7b6f97) | Feb 25, 2025 |
| ASUSTek       | PRIME B360-PLUS             | [341db63829](https://linux-hardware.org/?probe=341db63829) | Feb 25, 2025 |
| ASUSTek       | P8H67-M LE                  | [0f74b568c0](https://linux-hardware.org/?probe=0f74b568c0) | Feb 24, 2025 |
| ASUSTek       | ROG Maximus XI HERO         | [673e7be2c0](https://linux-hardware.org/?probe=673e7be2c0) | Feb 24, 2025 |
| MSI           | B550-A PRO                  | [c46ef2e167](https://linux-hardware.org/?probe=c46ef2e167) | Feb 23, 2025 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [662d4dee99](https://linux-hardware.org/?probe=662d4dee99) | Feb 23, 2025 |
| MSI           | MPG Z690 FORCE WIFI         | [80d2aa4a01](https://linux-hardware.org/?probe=80d2aa4a01) | Feb 23, 2025 |
| Gigabyte      | B650 AORUS ELITE AX         | [f3cefe6f8a](https://linux-hardware.org/?probe=f3cefe6f8a) | Feb 22, 2025 |
| MSI           | PRO B550M-VC WIFI           | [33af398f7a](https://linux-hardware.org/?probe=33af398f7a) | Feb 22, 2025 |
| System76      | Thelio thelio-r4            | [6e7fe59d47](https://linux-hardware.org/?probe=6e7fe59d47) | Feb 22, 2025 |
| HP            | 1495                        | [f953bc5239](https://linux-hardware.org/?probe=f953bc5239) | Feb 22, 2025 |
| MSI           | MAG X870 TOMAHAWK WIFI      | [f01ceb64ec](https://linux-hardware.org/?probe=f01ceb64ec) | Feb 22, 2025 |
| Acer          | Nitro N50-656               | [2b4d98122d](https://linux-hardware.org/?probe=2b4d98122d) | Feb 21, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [495688e66a](https://linux-hardware.org/?probe=495688e66a) | Feb 21, 2025 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9e803385a4](https://linux-hardware.org/?probe=9e803385a4) | Feb 21, 2025 |
| Gigabyte      | Z790 AORUS MASTER X         | [a681c59dc5](https://linux-hardware.org/?probe=a681c59dc5) | Feb 20, 2025 |
| MSI           | PRO B760-VC WIFI 7 BULK     | [11da0f9efe](https://linux-hardware.org/?probe=11da0f9efe) | Feb 20, 2025 |
| ASUSTek       | H110M-A/M.2                 | [3cb92cf631](https://linux-hardware.org/?probe=3cb92cf631) | Feb 20, 2025 |
| ASRock        | H110M-HDV R3.0              | [01e6ab2aa8](https://linux-hardware.org/?probe=01e6ab2aa8) | Feb 20, 2025 |
| ASUSTek       | PRIME Z790-V AX             | [5140c8fb88](https://linux-hardware.org/?probe=5140c8fb88) | Feb 20, 2025 |
| ASRock        | H110M-HDV R3.0              | [5b1bd5af4b](https://linux-hardware.org/?probe=5b1bd5af4b) | Feb 20, 2025 |
| ASUSTek       | PRIME Z790-V AX             | [1c2b34cd9e](https://linux-hardware.org/?probe=1c2b34cd9e) | Feb 20, 2025 |
| System76      | Thelio Major thelio-majo... | [04d97910d0](https://linux-hardware.org/?probe=04d97910d0) | Feb 19, 2025 |
| MSI           | B450 TOMAHAWK MAX II        | [6f75598e93](https://linux-hardware.org/?probe=6f75598e93) | Feb 18, 2025 |
| Gigabyte      | AB350M-HD3-CF               | [8c61f57385](https://linux-hardware.org/?probe=8c61f57385) | Feb 18, 2025 |
| Intel         | B75                         | [bf35e48977](https://linux-hardware.org/?probe=bf35e48977) | Feb 17, 2025 |
| Dell          | 0PC5F7 A02                  | [1bb5132e4f](https://linux-hardware.org/?probe=1bb5132e4f) | Feb 17, 2025 |
| Gigabyte      | X570 AORUS PRO              | [dfcc198292](https://linux-hardware.org/?probe=dfcc198292) | Feb 17, 2025 |
| Gigabyte      | AB350M-HD3-CF               | [870892f9be](https://linux-hardware.org/?probe=870892f9be) | Feb 17, 2025 |
| ASRock        | Z690 PG Riptide             | [1267c83562](https://linux-hardware.org/?probe=1267c83562) | Feb 17, 2025 |
| MSI           | MAG B550 TOMAHAWK           | [3a409fcc65](https://linux-hardware.org/?probe=3a409fcc65) | Feb 17, 2025 |
| Gigabyte      | X299 UD4 Pro-CF             | [3b1d665d16](https://linux-hardware.org/?probe=3b1d665d16) | Feb 16, 2025 |
| Unknown       | Unknown                     | [d91b0d01b2](https://linux-hardware.org/?probe=d91b0d01b2) | Feb 16, 2025 |
| Gigabyte      | AB350M-HD3-CF               | [7dae4c1465](https://linux-hardware.org/?probe=7dae4c1465) | Feb 16, 2025 |
| ASUSTek       | P8H67-M LE                  | [fedd9a4332](https://linux-hardware.org/?probe=fedd9a4332) | Feb 16, 2025 |
| Intel         | B75                         | [4cb645f31d](https://linux-hardware.org/?probe=4cb645f31d) | Feb 15, 2025 |
| System76      | Thelio Major thelio-majo... | [3ca99ad44f](https://linux-hardware.org/?probe=3ca99ad44f) | Feb 15, 2025 |
| Lenovo        | ThinkStation S20 4157V8S    | [cbfe25ee79](https://linux-hardware.org/?probe=cbfe25ee79) | Feb 14, 2025 |
| ASUSTek       | PRIME B550M-K               | [f8dbc7c340](https://linux-hardware.org/?probe=f8dbc7c340) | Feb 14, 2025 |
| MSI           | Z97 GAMING 5                | [f1124e0e5b](https://linux-hardware.org/?probe=f1124e0e5b) | Feb 12, 2025 |
| Shenzhen M... | DRBAA                       | [14b5430a85](https://linux-hardware.org/?probe=14b5430a85) | Feb 12, 2025 |
| ASRock        | B550M-ITX/ac                | [edb8794747](https://linux-hardware.org/?probe=edb8794747) | Feb 12, 2025 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [8ba4da1fde](https://linux-hardware.org/?probe=8ba4da1fde) | Feb 12, 2025 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [f9a0f9d293](https://linux-hardware.org/?probe=f9a0f9d293) | Feb 12, 2025 |
| ASRock        | B450 Steel Legend           | [a53ef15961](https://linux-hardware.org/?probe=a53ef15961) | Feb 12, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eb28044447](https://linux-hardware.org/?probe=eb28044447) | Feb 11, 2025 |
| Alienware     | 0TYR0X A00                  | [c21af0107f](https://linux-hardware.org/?probe=c21af0107f) | Feb 11, 2025 |
| MSI           | B450M MORTAR MAX            | [2a2ff5d7d5](https://linux-hardware.org/?probe=2a2ff5d7d5) | Feb 11, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8e641b4d24](https://linux-hardware.org/?probe=8e641b4d24) | Feb 10, 2025 |
| Acer          | Nitro N50-656               | [d235f4feb8](https://linux-hardware.org/?probe=d235f4feb8) | Feb 10, 2025 |
| Dell          | 0M858N A01                  | [6ac1afc435](https://linux-hardware.org/?probe=6ac1afc435) | Feb 10, 2025 |
| ASUSTek       | PRIME Z390-A                | [26b796e58d](https://linux-hardware.org/?probe=26b796e58d) | Feb 09, 2025 |
| ASUSTek       | PRIME B350M-K               | [774f41d76d](https://linux-hardware.org/?probe=774f41d76d) | Feb 09, 2025 |
| Gigabyte      | GA-78LMT-USB3               | [3c6d817c80](https://linux-hardware.org/?probe=3c6d817c80) | Feb 09, 2025 |
| ASUSTek       | PRIME Z690-P WIFI           | [26f110784e](https://linux-hardware.org/?probe=26f110784e) | Feb 08, 2025 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [be631d81c1](https://linux-hardware.org/?probe=be631d81c1) | Feb 08, 2025 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [3cfb989ace](https://linux-hardware.org/?probe=3cfb989ace) | Feb 08, 2025 |
| Intel         | B75                         | [c476a77cbd](https://linux-hardware.org/?probe=c476a77cbd) | Feb 08, 2025 |
| HC Technol... | HCAR6000-MI2                | [ab6d7b83d3](https://linux-hardware.org/?probe=ab6d7b83d3) | Feb 07, 2025 |
| ASRock        | A520M/ac                    | [9a5d582d81](https://linux-hardware.org/?probe=9a5d582d81) | Feb 07, 2025 |
| Unknown       | DH61BR G32662-203           | [cc10f0c19b](https://linux-hardware.org/?probe=cc10f0c19b) | Feb 06, 2025 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [e80c3fc704](https://linux-hardware.org/?probe=e80c3fc704) | Feb 06, 2025 |
| Gigabyte      | B450M GAMING                | [8473d45ee1](https://linux-hardware.org/?probe=8473d45ee1) | Feb 05, 2025 |
| Gigabyte      | H510M S2H V2                | [f032e35868](https://linux-hardware.org/?probe=f032e35868) | Feb 05, 2025 |
| ASUSTek       | PRIME B660-PLUS D4          | [0a46c3ecf5](https://linux-hardware.org/?probe=0a46c3ecf5) | Feb 04, 2025 |
| Unknown       | Unknown                     | [4a74f537a8](https://linux-hardware.org/?probe=4a74f537a8) | Feb 04, 2025 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [131d6507fb](https://linux-hardware.org/?probe=131d6507fb) | Feb 04, 2025 |
| ASRock        | B650E Steel Legend WiFi     | [fa212887d9](https://linux-hardware.org/?probe=fa212887d9) | Feb 04, 2025 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6b87313423](https://linux-hardware.org/?probe=6b87313423) | Feb 04, 2025 |
| Gigabyte      | H270M-DS3H-CF               | [4d86fdba39](https://linux-hardware.org/?probe=4d86fdba39) | Feb 04, 2025 |
| ASUSTek       | Pro WS TRX50-SAGE WIFI      | [b4c850e275](https://linux-hardware.org/?probe=b4c850e275) | Feb 03, 2025 |
| ASUSTek       | PRIME Z690-P WIFI           | [78f39c9cfc](https://linux-hardware.org/?probe=78f39c9cfc) | Feb 03, 2025 |
| Shenzhen M... | DRFXI                       | [911601e74a](https://linux-hardware.org/?probe=911601e74a) | Feb 03, 2025 |
| ASUSTek       | F2A85-M                     | [fd0e83b46e](https://linux-hardware.org/?probe=fd0e83b46e) | Feb 03, 2025 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [646ecda89e](https://linux-hardware.org/?probe=646ecda89e) | Feb 01, 2025 |
| HP            | 2B17                        | [4677c280fe](https://linux-hardware.org/?probe=4677c280fe) | Feb 01, 2025 |
| MSI           | MPG Z390M GAMING EDGE AC    | [20aea4a1c1](https://linux-hardware.org/?probe=20aea4a1c1) | Feb 01, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [acba8c4cc4](https://linux-hardware.org/?probe=acba8c4cc4) | Jan 31, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [52dc11e81c](https://linux-hardware.org/?probe=52dc11e81c) | Jan 31, 2025 |
| HP            | 1790                        | [86e1a7be09](https://linux-hardware.org/?probe=86e1a7be09) | Jan 31, 2025 |
| ASUSTek       | PRIME X870-P WIFI           | [3fd4ad5eed](https://linux-hardware.org/?probe=3fd4ad5eed) | Jan 31, 2025 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Pop!_OS 22.04 | 2583     | 47.13%  |
| Pop!_OS 20.04 | 866      | 15.8%   |
| Pop!_OS 21.04 | 719      | 13.12%  |
| Pop!_OS 20.10 | 674      | 12.3%   |
| Pop!_OS 21.10 | 422      | 7.7%    |
| Pop!_OS 24.04 | 191      | 3.48%   |
| Pop!_OS 19.10 | 15       | 0.27%   |
| Pop!_OS 19.04 | 6        | 0.11%   |
| Pop!_OS 18.04 | 4        | 0.07%   |
| Pop!_OS 18.10 | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Pop!_OS | 5236     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 6.9.3-76060903-generic              | 564      | 9.37%   |
| 5.11.0-7620-generic                 | 341      | 5.67%   |
| 6.12.10-76061203-generic            | 339      | 5.63%   |
| 5.8.0-7630-generic                  | 314      | 5.22%   |
| 6.2.6-76060206-generic              | 306      | 5.08%   |
| 5.4.0-7634-generic                  | 282      | 4.69%   |
| 5.8.0-7642-generic                  | 204      | 3.39%   |
| 5.13.0-7614-generic                 | 203      | 3.37%   |
| 5.4.0-7642-generic                  | 187      | 3.11%   |
| 5.11.0-7614-generic                 | 183      | 3.04%   |
| 5.17.5-76051705-generic             | 181      | 3.01%   |
| 6.8.0-76060800daily20240311-generic | 178      | 2.96%   |
| 6.0.12-76060006-generic             | 176      | 2.92%   |
| 6.16.3-76061603-generic             | 174      | 2.89%   |
| 5.13.0-7620-generic                 | 171      | 2.84%   |
| 5.19.0-76051900-generic             | 144      | 2.39%   |
| 6.5.6-76060506-generic              | 116      | 1.93%   |
| 5.16.11-76051611-generic            | 112      | 1.86%   |
| 5.15.15-76051515-generic            | 109      | 1.81%   |
| 6.0.6-76060006-generic              | 102      | 1.69%   |
| 6.6.10-76060610-generic             | 100      | 1.66%   |
| 6.4.6-76060406-generic              | 92       | 1.53%   |
| 5.15.5-76051505-generic             | 92       | 1.53%   |
| 6.6.6-76060606-generic              | 90       | 1.5%    |
| 6.17.4-76061704-generic             | 85       | 1.41%   |
| 5.11.0-7612-generic                 | 85       | 1.41%   |
| 5.8.0-7625-generic                  | 79       | 1.31%   |
| 6.17.9-76061709-generic             | 78       | 1.3%    |
| 5.18.10-76051810-generic            | 76       | 1.26%   |
| 5.11.0-7633-generic                 | 70       | 1.16%   |
| 5.17.15-76051715-generic            | 69       | 1.15%   |
| 5.16.19-76051619-generic            | 65       | 1.08%   |
| 5.15.8-76051508-generic             | 62       | 1.03%   |
| 5.16.15-76051615-generic            | 56       | 0.93%   |
| 6.5.4-76060504-generic              | 53       | 0.88%   |
| 5.15.11-76051511-generic            | 49       | 0.81%   |
| 5.4.0-7626-generic                  | 43       | 0.71%   |
| 6.2.0-76060200-generic              | 36       | 0.6%    |
| 6.1.11-76060111-generic             | 29       | 0.48%   |
| 6.0.2-76060002-generic              | 29       | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 651      | 10.98%  |
| 5.8.0   | 569      | 9.6%    |
| 6.9.3   | 564      | 9.51%   |
| 5.4.0   | 538      | 9.07%   |
| 5.13.0  | 371      | 6.26%   |
| 6.12.10 | 339      | 5.72%   |
| 6.2.6   | 306      | 5.16%   |
| 6.0.12  | 183      | 3.09%   |
| 5.17.5  | 181      | 3.05%   |
| 6.8.0   | 178      | 3%      |
| 6.16.3  | 174      | 2.93%   |
| 5.19.0  | 144      | 2.43%   |
| 6.5.6   | 116      | 1.96%   |
| 5.16.11 | 112      | 1.89%   |
| 5.15.15 | 110      | 1.86%   |
| 6.0.6   | 103      | 1.74%   |
| 6.6.10  | 100      | 1.69%   |
| 6.4.6   | 92       | 1.55%   |
| 5.15.5  | 92       | 1.55%   |
| 6.6.6   | 90       | 1.52%   |
| 6.17.4  | 85       | 1.43%   |
| 6.17.9  | 78       | 1.32%   |
| 5.18.10 | 76       | 1.28%   |
| 5.17.15 | 69       | 1.16%   |
| 5.16.19 | 65       | 1.1%    |
| 5.15.8  | 62       | 1.05%   |
| 5.16.15 | 56       | 0.94%   |
| 6.5.4   | 53       | 0.89%   |
| 5.15.11 | 49       | 0.83%   |
| 6.2.0   | 37       | 0.62%   |
| 6.0.2   | 30       | 0.51%   |
| 6.1.11  | 29       | 0.49%   |
| 5.15.23 | 29       | 0.49%   |
| 5.19.16 | 18       | 0.3%    |
| 5.3.0   | 17       | 0.29%   |
| 6.0.3   | 14       | 0.24%   |
| 5.8.5   | 8        | 0.13%   |
| 5.0.0   | 6        | 0.1%    |
| 5.8.12  | 5        | 0.08%   |
| 6.3.7   | 3        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 653      | 11.12%  |
| 5.8     | 591      | 10.06%  |
| 6.9     | 566      | 9.64%   |
| 5.4     | 540      | 9.19%   |
| 5.13    | 376      | 6.4%    |
| 5.15    | 344      | 5.86%   |
| 6.2     | 340      | 5.79%   |
| 6.12    | 339      | 5.77%   |
| 6.0     | 325      | 5.53%   |
| 5.17    | 248      | 4.22%   |
| 5.16    | 224      | 3.81%   |
| 6.6     | 184      | 3.13%   |
| 6.8     | 179      | 3.05%   |
| 6.16    | 175      | 2.98%   |
| 6.5     | 171      | 2.91%   |
| 6.17    | 163      | 2.77%   |
| 5.19    | 162      | 2.76%   |
| 6.4     | 94       | 1.6%    |
| 5.18    | 78       | 1.33%   |
| 6.1     | 35       | 0.6%    |
| 5.3     | 17       | 0.29%   |
| 5.7     | 14       | 0.24%   |
| 5.6     | 8        | 0.14%   |
| 5.10    | 8        | 0.14%   |
| 6.3     | 6        | 0.1%    |
| 5.0     | 6        | 0.1%    |
| 5.9     | 5        | 0.09%   |
| 5.14    | 5        | 0.09%   |
| 5.12    | 4        | 0.07%   |
| 6.15    | 3        | 0.05%   |
| 6.11    | 3        | 0.05%   |
| 6.7     | 2        | 0.03%   |
| 6.13    | 2        | 0.03%   |
| 6.14    | 1        | 0.02%   |
| 6.10    | 1        | 0.02%   |
| 4.18    | 1        | 0.02%   |
| 4.15    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 5236     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 4885     | 92.47%  |
| COSMIC          | 194      | 3.67%   |
| KDE5            | 68       | 1.29%   |
| KDE             | 34       | 0.64%   |
| Unknown         | 26       | 0.49%   |
| X-Cinnamon      | 22       | 0.42%   |
| XFCE            | 12       | 0.23%   |
| MATE            | 11       | 0.21%   |
| LXQt            | 6        | 0.11%   |
| GNOME Flashback | 6        | 0.11%   |
| i3              | 5        | 0.09%   |
| Cinnamon        | 5        | 0.09%   |
| Unity           | 3        | 0.06%   |
| Budgie          | 2        | 0.04%   |
| UKUI            | 1        | 0.02%   |
| Pantheon        | 1        | 0.02%   |
| GNOME Classic   | 1        | 0.02%   |
| Deepin          | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 4925     | 93.4%   |
| Wayland | 323      | 6.13%   |
| Unknown | 15       | 0.28%   |
| Tty     | 10       | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 4365     | 82.5%   |
| GDM3           | 506      | 9.56%   |
| GDM            | 362      | 6.84%   |
| COSMIC-GREETER | 29       | 0.55%   |
| SDDM           | 21       | 0.4%    |
| LightDM        | 5        | 0.09%   |
| TDM            | 3        | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2931     | 55.43%  |
| en_GB   | 392      | 7.41%   |
| pt_BR   | 342      | 6.47%   |
| de_DE   | 318      | 6.01%   |
| C       | 216      | 4.08%   |
| en_AU   | 158      | 2.99%   |
| en_CA   | 154      | 2.91%   |
| fr_FR   | 104      | 1.97%   |
| it_IT   | 81       | 1.53%   |
| ru_RU   | 59       | 1.12%   |
| es_ES   | 58       | 1.1%    |
| pl_PL   | 46       | 0.87%   |
| sv_SE   | 32       | 0.61%   |
| nl_NL   | 32       | 0.61%   |
| Unknown | 27       | 0.51%   |
| pt_PT   | 21       | 0.4%    |
| es_AR   | 19       | 0.36%   |
| fi_FI   | 16       | 0.3%    |
| es_CL   | 15       | 0.28%   |
| fr_CA   | 14       | 0.26%   |
| en_ZA   | 14       | 0.26%   |
| da_DK   | 14       | 0.26%   |
| ja_JP   | 13       | 0.25%   |
| en_DK   | 13       | 0.25%   |
| sk_SK   | 11       | 0.21%   |
| cs_CZ   | 11       | 0.21%   |
| es_MX   | 10       | 0.19%   |
| en_NZ   | 10       | 0.19%   |
| en_IN   | 10       | 0.19%   |
| de_AT   | 10       | 0.19%   |
| nb_NO   | 9        | 0.17%   |
| hu_HU   | 9        | 0.17%   |
| zh_TW   | 8        | 0.15%   |
| tr_TR   | 8        | 0.15%   |
| nl_BE   | 8        | 0.15%   |
| de_CH   | 8        | 0.15%   |
| zh_CN   | 6        | 0.11%   |
| ro_RO   | 5        | 0.09%   |
| es_VE   | 5        | 0.09%   |
| hr_HR   | 4        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 4276     | 80.74%  |
| EFI  | 1020     | 19.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 5036     | 95.8%   |
| Btrfs   | 105      | 2%      |
| Overlay | 91       | 1.73%   |
| Xfs     | 11       | 0.21%   |
| Zfs     | 6        | 0.11%   |
| Unknown | 6        | 0.11%   |
| XXX4    | 1        | 0.02%   |
| Tmpfs   | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4348     | 82.32%  |
| GPT     | 838      | 15.87%  |
| MBR     | 96       | 1.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5067     | 96.29%  |
| Yes       | 195      | 3.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4730     | 89.72%  |
| Yes       | 542      | 10.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1510     | 28.84%  |
| Gigabyte Technology                  | 989      | 18.89%  |
| MSI                                  | 807      | 15.41%  |
| ASRock                               | 503      | 9.61%   |
| Dell                                 | 377      | 7.2%    |
| Hewlett-Packard                      | 271      | 5.18%   |
| Lenovo                               | 118      | 2.25%   |
| Intel                                | 107      | 2.04%   |
| System76                             | 56       | 1.07%   |
| Acer                                 | 43       | 0.82%   |
| Unknown                              | 43       | 0.82%   |
| Biostar                              | 34       | 0.65%   |
| Pegatron                             | 28       | 0.53%   |
| Alienware                            | 26       | 0.5%    |
| Fujitsu                              | 25       | 0.48%   |
| Apple                                | 25       | 0.48%   |
| Foxconn                              | 21       | 0.4%    |
| ECS                                  | 18       | 0.34%   |
| Huanan                               | 17       | 0.32%   |
| Supermicro                           | 13       | 0.25%   |
| Positivo                             | 13       | 0.25%   |
| Shenzhen Meigao Electronic Equipment | 12       | 0.23%   |
| Medion                               | 11       | 0.21%   |
| BESSTAR Tech                         | 10       | 0.19%   |
| PCWare                               | 8        | 0.15%   |
| MACHINIST                            | 8        | 0.15%   |
| Gateway                              | 8        | 0.15%   |
| NZXT                                 | 7        | 0.13%   |
| EVGA                                 | 7        | 0.13%   |
| AZW                                  | 7        | 0.13%   |
| OEM                                  | 6        | 0.11%   |
| Minix                                | 5        | 0.1%    |
| JGINYUE                              | 5        | 0.1%    |
| MAXSUN                               | 4        | 0.08%   |
| Kllisre                              | 4        | 0.08%   |
| Fujitsu Siemens                      | 4        | 0.08%   |
| eMachines                            | 4        | 0.08%   |
| AMI                                  | 4        | 0.08%   |
| Tianbei                              | 3        | 0.06%   |
| Samsung Electronics                  | 3        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 119      | 2.27%   |
| ASUS TUF Gaming X570-PLUS      | 56       | 1.07%   |
| Unknown                        | 44       | 0.84%   |
| ASUS ROG STRIX B550-F GAMING   | 41       | 0.78%   |
| MSI MS-7C37                    | 39       | 0.74%   |
| MSI MS-7C02                    | 39       | 0.74%   |
| Gigabyte B450M DS3H            | 35       | 0.67%   |
| ASUS ROG STRIX B450-F GAMING   | 35       | 0.67%   |
| MSI MS-7B86                    | 33       | 0.63%   |
| Dell OptiPlex 9020             | 30       | 0.57%   |
| System76 Thelio                | 27       | 0.52%   |
| MSI MS-7C91                    | 26       | 0.5%    |
| Dell OptiPlex 7010             | 26       | 0.5%    |
| Gigabyte X570 AORUS ELITE      | 25       | 0.48%   |
| ASUS PRIME B450M-A             | 25       | 0.48%   |
| MSI MS-7C56                    | 24       | 0.46%   |
| ASRock B450M Pro4              | 22       | 0.42%   |
| MSI MS-7C95                    | 20       | 0.38%   |
| Gigabyte X570 AORUS MASTER     | 20       | 0.38%   |
| Gigabyte A320M-S2H             | 20       | 0.38%   |
| ASRock B450M Steel Legend      | 19       | 0.36%   |
| Gigabyte B450 AORUS PRO WIFI   | 17       | 0.32%   |
| Gigabyte B450 AORUS M          | 17       | 0.32%   |
| MSI MS-7C84                    | 16       | 0.31%   |
| MSI MS-7B89                    | 16       | 0.31%   |
| MSI MS-7B79                    | 16       | 0.31%   |
| MSI MS-7A38                    | 16       | 0.31%   |
| ASUS ROG STRIX B550-I GAMING   | 16       | 0.31%   |
| Dell OptiPlex 790              | 15       | 0.29%   |
| Dell OptiPlex 3020             | 15       | 0.29%   |
| ASUS TUF Gaming B550M-PLUS     | 15       | 0.29%   |
| ASUS PRIME A320M-K             | 15       | 0.29%   |
| System76 Thelio Major          | 14       | 0.27%   |
| Intel B75                      | 14       | 0.27%   |
| Gigabyte B550M DS3H            | 14       | 0.27%   |
| Gigabyte B550I AORUS PRO AX    | 14       | 0.27%   |
| Gigabyte B450 I AORUS PRO WIFI | 14       | 0.27%   |
| Dell OptiPlex 3010             | 14       | 0.27%   |
| ASUS ROG STRIX X570-E GAMING   | 14       | 0.27%   |
| ASUS PRIME B450M-GAMING/BR     | 14       | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 368      | 7.03%   |
| ASUS PRIME             | 296      | 5.65%   |
| Dell OptiPlex          | 215      | 4.11%   |
| ASUS TUF               | 215      | 4.11%   |
| ASUS All               | 119      | 2.27%   |
| Gigabyte X570          | 97       | 1.85%   |
| HP Compaq              | 73       | 1.39%   |
| Lenovo ThinkCentre     | 64       | 1.22%   |
| Gigabyte B450          | 63       | 1.2%    |
| Dell Precision         | 63       | 1.2%    |
| Gigabyte B450M         | 58       | 1.11%   |
| System76 Thelio        | 55       | 1.05%   |
| Gigabyte B550          | 50       | 0.95%   |
| ASRock B450M           | 49       | 0.94%   |
| Unknown                | 44       | 0.84%   |
| ASRock X570            | 41       | 0.78%   |
| MSI MS-7C37            | 39       | 0.74%   |
| MSI MS-7C02            | 39       | 0.74%   |
| HP EliteDesk           | 37       | 0.71%   |
| Dell Inspiron          | 36       | 0.69%   |
| Gigabyte B550M         | 35       | 0.67%   |
| MSI MS-7B86            | 33       | 0.63%   |
| ASUS SABERTOOTH        | 29       | 0.55%   |
| Acer Aspire            | 29       | 0.55%   |
| Dell XPS               | 28       | 0.53%   |
| ASRock B450            | 27       | 0.52%   |
| MSI MS-7C91            | 26       | 0.5%    |
| Gigabyte Z390          | 25       | 0.48%   |
| ASUS M5A78L-M          | 25       | 0.48%   |
| MSI MS-7C56            | 24       | 0.46%   |
| Gigabyte A320M-S2H     | 24       | 0.46%   |
| HP ProDesk             | 22       | 0.42%   |
| ASUS P8Z77-V           | 22       | 0.42%   |
| ASUS M5A97             | 21       | 0.4%    |
| ASRock B550            | 21       | 0.4%    |
| MSI MS-7C95            | 20       | 0.38%   |
| Gigabyte GA-78LMT-USB3 | 20       | 0.38%   |
| ASUS Maximus           | 20       | 0.38%   |
| Lenovo IdeaCentre      | 19       | 0.36%   |
| HP OMEN                | 17       | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 713      | 13.62%  |
| 2020 | 590      | 11.27%  |
| 2019 | 539      | 10.29%  |
| 2012 | 365      | 6.97%   |
| 2017 | 338      | 6.46%   |
| 2013 | 327      | 6.25%   |
| 2021 | 324      | 6.19%   |
| 2014 | 296      | 5.65%   |
| 2022 | 262      | 5%      |
| 2011 | 253      | 4.83%   |
| 2016 | 222      | 4.24%   |
| 2015 | 213      | 4.07%   |
| 2009 | 172      | 3.28%   |
| 2023 | 163      | 3.11%   |
| 2010 | 162      | 3.09%   |
| 2024 | 108      | 2.06%   |
| 2008 | 87       | 1.66%   |
| 2007 | 63       | 1.2%    |
| 2025 | 25       | 0.48%   |
| 2006 | 13       | 0.25%   |
| 2005 | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 5236     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 5230     | 99.87%  |
| Enabled  | 7        | 0.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5233     | 99.94%  |
| Yes  | 3        | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1627     | 30.43%  |
| 32.01-64.0      | 1331     | 24.9%   |
| 8.01-16.0       | 835      | 15.62%  |
| 4.01-8.0        | 457      | 8.55%   |
| 64.01-256.0     | 455      | 8.51%   |
| 3.01-4.0        | 310      | 5.8%    |
| 24.01-32.0      | 271      | 5.07%   |
| 1.01-2.0        | 33       | 0.62%   |
| More than 256.0 | 14       | 0.26%   |
| 2.01-3.0        | 12       | 0.22%   |
| 0.51-1.0        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 1791     | 31.06%  |
| 2.01-3.0    | 1204     | 20.88%  |
| 3.01-4.0    | 973      | 16.87%  |
| 1.01-2.0    | 958      | 16.61%  |
| 8.01-16.0   | 660      | 11.45%  |
| 16.01-24.0  | 104      | 1.8%    |
| 24.01-32.0  | 32       | 0.55%   |
| 32.01-64.0  | 29       | 0.5%    |
| 0.51-1.0    | 11       | 0.19%   |
| 64.01-256.0 | 4        | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1710     | 31.49%  |
| 2      | 1656     | 30.49%  |
| 3      | 995      | 18.32%  |
| 4      | 575      | 10.59%  |
| 5      | 258      | 4.75%   |
| 6      | 119      | 2.19%   |
| 7      | 45       | 0.83%   |
| 0      | 19       | 0.35%   |
| 8      | 18       | 0.33%   |
| 9      | 11       | 0.2%    |
| 11     | 9        | 0.17%   |
| 12     | 3        | 0.06%   |
| 10     | 3        | 0.06%   |
| 20     | 2        | 0.04%   |
| 14     | 2        | 0.04%   |
| 13     | 2        | 0.04%   |
| 26     | 1        | 0.02%   |
| 23     | 1        | 0.02%   |
| 22     | 1        | 0.02%   |
| 19     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3760     | 71.19%  |
| Yes       | 1522     | 28.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5176     | 98.84%  |
| No        | 61       | 1.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2869     | 54.23%  |
| No        | 2421     | 45.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2943     | 55.61%  |
| Yes       | 2349     | 44.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1765     | 33.54%  |
| Brazil       | 455      | 8.65%   |
| Germany      | 431      | 8.19%   |
| UK           | 299      | 5.68%   |
| Canada       | 292      | 5.55%   |
| Australia    | 190      | 3.61%   |
| Italy        | 135      | 2.57%   |
| France       | 120      | 2.28%   |
| Netherlands  | 116      | 2.2%    |
| Sweden       | 100      | 1.9%    |
| Poland       | 89       | 1.69%   |
| Russia       | 75       | 1.43%   |
| Spain        | 63       | 1.2%    |
| Finland      | 54       | 1.03%   |
| South Africa | 52       | 0.99%   |
| Switzerland  | 48       | 0.91%   |
| Austria      | 47       | 0.89%   |
| India        | 46       | 0.87%   |
| Mexico       | 44       | 0.84%   |
| Norway       | 42       | 0.8%    |
| Denmark      | 40       | 0.76%   |
| Argentina    | 39       | 0.74%   |
| Romania      | 36       | 0.68%   |
| Portugal     | 36       | 0.68%   |
| New Zealand  | 36       | 0.68%   |
| Belgium      | 36       | 0.68%   |
| Greece       | 32       | 0.61%   |
| Hungary      | 31       | 0.59%   |
| Czechia      | 31       | 0.59%   |
| Bulgaria     | 25       | 0.48%   |
| Philippines  | 24       | 0.46%   |
| Japan        | 23       | 0.44%   |
| Chile        | 21       | 0.4%    |
| Malaysia     | 20       | 0.38%   |
| Slovakia     | 19       | 0.36%   |
| Indonesia    | 18       | 0.34%   |
| Turkey       | 16       | 0.3%    |
| Serbia       | 16       | 0.3%    |
| Israel       | 15       | 0.29%   |
| Ireland      | 14       | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 58       | 1.06%   |
| Sydney         | 55       | 1%      |
| Melbourne      | 39       | 0.71%   |
| Berlin         | 39       | 0.71%   |
| Rio de Janeiro | 33       | 0.6%    |
| Brisbane       | 31       | 0.56%   |
| Seattle        | 30       | 0.55%   |
| Helsinki       | 28       | 0.51%   |
| Vienna         | 27       | 0.49%   |
| Chicago        | 27       | 0.49%   |
| Montreal       | 24       | 0.44%   |
| Denver         | 24       | 0.44%   |
| Miami          | 23       | 0.42%   |
| Toronto        | 22       | 0.4%    |
| Milan          | 22       | 0.4%    |
| New York       | 19       | 0.35%   |
| Hamburg        | 19       | 0.35%   |
| Edmonton       | 19       | 0.35%   |
| Dallas         | 19       | 0.35%   |
| Warsaw         | 18       | 0.33%   |
| Los Angeles    | 18       | 0.33%   |
| London         | 18       | 0.33%   |
| Rome           | 17       | 0.31%   |
| Moscow         | 17       | 0.31%   |
| Auckland       | 17       | 0.31%   |
| Amsterdam      | 17       | 0.31%   |
| Perth          | 16       | 0.29%   |
| Cologne        | 16       | 0.29%   |
| Cape Town      | 16       | 0.29%   |
| Calgary        | 16       | 0.29%   |
| Budapest       | 16       | 0.29%   |
| Browning       | 16       | 0.29%   |
| Adelaide       | 16       | 0.29%   |
| St Louis       | 15       | 0.27%   |
| Portland       | 15       | 0.27%   |
| Phoenix        | 15       | 0.27%   |
| Stockholm      | 14       | 0.25%   |
| Sofia          | 14       | 0.25%   |
| Cleveland      | 14       | 0.25%   |
| Athens         | 14       | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 1846     | 3238   | 17.65%  |
| Seagate                     | 1648     | 2634   | 15.75%  |
| WDC                         | 1584     | 2459   | 15.14%  |
| SanDisk                     | 688      | 942    | 6.58%   |
| Kingston                    | 622      | 819    | 5.95%   |
| Crucial                     | 500      | 726    | 4.78%   |
| Toshiba                     | 425      | 548    | 4.06%   |
| Hitachi                     | 226      | 308    | 2.16%   |
| Intel                       | 192      | 292    | 1.84%   |
| Micron/Crucial Technology   | 172      | 236    | 1.64%   |
| Phison                      | 161      | 239    | 1.54%   |
| A-DATA Technology           | 156      | 193    | 1.49%   |
| Phison Electronics          | 136      | 212    | 1.3%    |
| China                       | 119      | 177    | 1.14%   |
| Silicon Motion              | 115      | 157    | 1.1%    |
| PNY                         | 112      | 145    | 1.07%   |
| Kingston Technology Company | 91       | 118    | 0.87%   |
| SK hynix                    | 90       | 124    | 0.86%   |
| Unknown                     | 88       | 181    | 0.84%   |
| HGST                        | 80       | 106    | 0.76%   |
| Micron Technology           | 74       | 91     | 0.71%   |
| SPCC                        | 68       | 101    | 0.65%   |
| OCZ                         | 62       | 84     | 0.59%   |
| Realtek Semiconductor       | 56       | 65     | 0.54%   |
| Team                        | 53       | 65     | 0.51%   |
| Corsair                     | 48       | 64     | 0.46%   |
| Patriot                     | 47       | 66     | 0.45%   |
| XPG                         | 42       | 59     | 0.4%    |
| Intenso                     | 39       | 52     | 0.37%   |
| Maxtor                      | 35       | 37     | 0.33%   |
| ADATA Technology            | 34       | 40     | 0.33%   |
| Hewlett-Packard             | 33       | 43     | 0.32%   |
| MAXIO Technology (Hangzhou) | 31       | 37     | 0.3%    |
| Lexar                       | 30       | 41     | 0.29%   |
| Netac                       | 26       | 30     | 0.25%   |
| T-FORCE                     | 25       | 32     | 0.24%   |
| Unknown                     | 25       | 28     | 0.24%   |
| JMicron Technology          | 24       | 42     | 0.23%   |
| Apple                       | 22       | 25     | 0.21%   |
| KingSpec                    | 21       | 27     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 172      | 1.41%   |
| Seagate ST2000DM008-2FR102 2TB                     | 144      | 1.18%   |
| Kingston SA400S37240G 240GB SSD                    | 141      | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB                     | 136      | 1.11%   |
| Samsung SSD 850 EVO 250GB                          | 133      | 1.09%   |
| Samsung NVMe SSD Drive 1TB                         | 132      | 1.08%   |
| Samsung NVMe SSD Drive 500GB                       | 117      | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 111      | 0.91%   |
| Samsung SSD 850 EVO 500GB                          | 109      | 0.89%   |
| Samsung SSD 860 EVO 500GB                          | 107      | 0.88%   |
| Samsung SSD 860 EVO 1TB                            | 105      | 0.86%   |
| Seagate ST500DM002-1BD142 500GB                    | 100      | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 91       | 0.74%   |
| Kingston SA400S37120G 120GB SSD                    | 90       | 0.74%   |
| Kingston SA400S37480G 480GB SSD                    | 85       | 0.7%    |
| Crucial CT1000MX500SSD1 1TB                        | 84       | 0.69%   |
| SanDisk NVMe SSD Drive 1TB                         | 81       | 0.66%   |
| Toshiba DT01ACA100 1TB                             | 70       | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB                     | 70       | 0.57%   |
| SanDisk NVMe SSD Drive 500GB                       | 67       | 0.55%   |
| Crucial CT500MX500SSD1 500GB                       | 66       | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                     | 63       | 0.52%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 62       | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB                     | 54       | 0.44%   |
| Samsung SSD 870 QVO 1TB                            | 51       | 0.42%   |
| Samsung SSD 980 1TB                                | 49       | 0.4%    |
| Samsung SSD 860 EVO 250GB                          | 49       | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                   | 49       | 0.4%    |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 47       | 0.38%   |
| Crucial CT240BX500SSD1 240GB                       | 45       | 0.37%   |
| Samsung SSD 860 QVO 1TB                            | 44       | 0.36%   |
| Toshiba HDWD110 1TB                                | 43       | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                     | 43       | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB                     | 43       | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                       | 43       | 0.35%   |
| Phison NVMe SSD Drive 1TB                          | 43       | 0.35%   |
| Phison E12 NVMe Controller 1TB                     | 43       | 0.35%   |
| Seagate Expansion 2TB                              | 41       | 0.34%   |
| Samsung SSD 870 EVO 1TB                            | 41       | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB                     | 40       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1602     | 2505   | 40.47%  |
| WDC                 | 1353     | 2074   | 34.18%  |
| Toshiba             | 368      | 478    | 9.3%    |
| Hitachi             | 226      | 308    | 5.71%   |
| Samsung Electronics | 154      | 196    | 3.89%   |
| HGST                | 80       | 106    | 2.02%   |
| Maxtor              | 31       | 33     | 0.78%   |
| Unknown             | 29       | 39     | 0.73%   |
| JMicron Technology  | 14       | 27     | 0.35%   |
| Apple               | 13       | 15     | 0.33%   |
| ASMT                | 10       | 10     | 0.25%   |
| TO Exter            | 8        | 11     | 0.2%    |
| T-FORCE             | 8        | 10     | 0.2%    |
| Hewlett-Packard     | 8        | 11     | 0.2%    |
| Fujitsu             | 6        | 10     | 0.15%   |
| USB                 | 4        | 6      | 0.1%    |
| LaCie               | 4        | 6      | 0.1%    |
| External            | 4        | 4      | 0.1%    |
| WD MediaMax         | 3        | 9      | 0.08%   |
| SABRENT             | 3        | 4      | 0.08%   |
| ExcelStor           | 3        | 3      | 0.08%   |
| Unknown             | 3        | 4      | 0.08%   |
| SATAFIRM            | 2        | 2      | 0.05%   |
| MaxDigital          | 2        | 2      | 0.05%   |
| Magnetic Data       | 2        | 2      | 0.05%   |
| Intenso             | 2        | 3      | 0.05%   |
| ASMedia             | 2        | 2      | 0.05%   |
| XrayDisk            | 1        | 1      | 0.03%   |
| USB3.0              | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| Quantum             | 1        | 1      | 0.03%   |
| OEM                 | 1        | 1      | 0.03%   |
| Maxone              | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 2      | 0.03%   |
| Inateck             | 1        | 1      | 0.03%   |
| HPE                 | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| H/W                 | 1        | 1      | 0.03%   |
| Glyph               | 1        | 2      | 0.03%   |
| Esmart              | 1        | 4      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1009     | 1578   | 26.76%  |
| Kingston            | 506      | 662    | 13.42%  |
| Crucial             | 444      | 624    | 11.78%  |
| SanDisk             | 306      | 399    | 8.12%   |
| WDC                 | 252      | 317    | 6.68%   |
| A-DATA Technology   | 136      | 171    | 3.61%   |
| China               | 118      | 176    | 3.13%   |
| PNY                 | 110      | 142    | 2.92%   |
| Intel               | 84       | 124    | 2.23%   |
| OCZ                 | 61       | 80     | 1.62%   |
| SPCC                | 54       | 67     | 1.43%   |
| Patriot             | 47       | 66     | 1.25%   |
| Team                | 45       | 56     | 1.19%   |
| SK hynix            | 36       | 57     | 0.95%   |
| Corsair             | 34       | 42     | 0.9%    |
| Micron Technology   | 31       | 36     | 0.82%   |
| Intenso             | 30       | 42     | 0.8%    |
| Seagate             | 25       | 42     | 0.66%   |
| Toshiba             | 24       | 26     | 0.64%   |
| Lexar               | 24       | 33     | 0.64%   |
| KingSpec            | 21       | 26     | 0.56%   |
| Hewlett-Packard     | 20       | 27     | 0.53%   |
| Transcend           | 18       | 22     | 0.48%   |
| GOODRAM             | 18       | 19     | 0.48%   |
| Apacer              | 18       | 22     | 0.48%   |
| Netac               | 17       | 20     | 0.45%   |
| SABRENT             | 14       | 15     | 0.37%   |
| Gigabyte Technology | 13       | 14     | 0.34%   |
| LITEONIT            | 12       | 13     | 0.32%   |
| Plextor             | 11       | 14     | 0.29%   |
| LITEON              | 11       | 17     | 0.29%   |
| Verbatim            | 10       | 14     | 0.27%   |
| Mushkin             | 10       | 13     | 0.27%   |
| Fanxiang            | 10       | 10     | 0.27%   |
| Unknown             | 9        | 10     | 0.24%   |
| KingDian            | 8        | 14     | 0.21%   |
| T-FORCE             | 7        | 8      | 0.19%   |
| Dogfish             | 6        | 10     | 0.16%   |
| ASMT                | 6        | 13     | 0.16%   |
| Apple               | 6        | 7      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3109     | 5899   | 35.58%  |
| SSD     | 3012     | 5249   | 34.47%  |
| NVMe    | 2406     | 4177   | 27.54%  |
| Unknown | 192      | 344    | 2.2%    |
| MMC     | 18       | 22     | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4382     | 10739  | 60.38%  |
| NVMe | 2402     | 4146   | 33.1%   |
| SAS  | 455      | 784    | 6.27%   |
| MMC  | 18       | 22     | 0.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3073     | 5315   | 45.37%  |
| 0.51-1.0   | 1954     | 3023   | 28.85%  |
| 1.01-2.0   | 960      | 1477   | 14.17%  |
| 3.01-4.0   | 356      | 592    | 5.26%   |
| 2.01-3.0   | 192      | 284    | 2.83%   |
| 4.01-10.0  | 191      | 350    | 2.82%   |
| 10.01-20.0 | 43       | 101    | 0.63%   |
| 20.01-50.0 | 4        | 6      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1154     | 20.96%  |
| 501-1000       | 1120     | 20.35%  |
| 251-500        | 1054     | 19.15%  |
| 1001-2000      | 843      | 15.31%  |
| More than 3000 | 627      | 11.39%  |
| 2001-3000      | 331      | 6.01%   |
| 51-100         | 153      | 2.78%   |
| 1-20           | 109      | 1.98%   |
| 21-50          | 78       | 1.42%   |
| Unknown        | 36       | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1605     | 27.93%  |
| 21-50          | 985      | 17.14%  |
| 101-250        | 747      | 13%     |
| 51-100         | 605      | 10.53%  |
| 251-500        | 567      | 9.87%   |
| 501-1000       | 484      | 8.42%   |
| 1001-2000      | 362      | 6.3%    |
| More than 3000 | 222      | 3.86%   |
| 2001-3000      | 134      | 2.33%   |
| Unknown        | 36       | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD10EZEX-08WN4A0 1TB              | 4        | 4      | 1.71%   |
| Seagate ST500DM002-1BD142 500GB       | 4        | 4      | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4        | 4      | 1.71%   |
| Kingston SA400S37120G 120GB SSD       | 4        | 6      | 1.71%   |
| WDC WD10EZEX-60WN4A0 1TB              | 3        | 3      | 1.28%   |
| Seagate ST2000DM008-2FR102 2TB        | 3        | 5      | 1.28%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3        | 6      | 1.28%   |
| Seagate ST1000DM003-9YN162 1TB        | 3        | 3      | 1.28%   |
| Samsung Electronics HD502HI 500GB     | 3        | 6      | 1.28%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 5      | 1.28%   |
| Hitachi HDS721010CLA332 1TB           | 3        | 3      | 1.28%   |
| WDC WD5000AADS-00S9B0 500GB           | 2        | 2      | 0.85%   |
| WDC WD40EZRZ-00GXCB0 4TB              | 2        | 2      | 0.85%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2        | 2      | 0.85%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 2        | 2      | 0.85%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2        | 2      | 0.85%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2        | 3      | 0.85%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 0.85%   |
| Toshiba MQ01ABD100 1TB                | 2        | 2      | 0.85%   |
| Toshiba HDWD110 1TB                   | 2        | 2      | 0.85%   |
| Seagate ST8000DM004-2CX188 8TB        | 2        | 2      | 0.85%   |
| Seagate ST3750528AS 752GB             | 2        | 2      | 0.85%   |
| Seagate ST3250310AS 250GB             | 2        | 5      | 0.85%   |
| SanDisk SSD PLUS 240GB                | 2        | 2      | 0.85%   |
| Samsung Electronics SSD 870 EVO 1TB   | 2        | 2      | 0.85%   |
| Samsung Electronics SSD 850 EVO 250GB | 2        | 2      | 0.85%   |
| Samsung Electronics HD154UI 1TB       | 2        | 2      | 0.85%   |
| Samsung Electronics HD103SJ 1TB       | 2        | 2      | 0.85%   |
| Samsung Electronics HD103SI 1TB       | 2        | 2      | 0.85%   |
| Kingston SA400S37480G 480GB SSD       | 2        | 2      | 0.85%   |
| Hitachi HDP725050GLA360 500GB         | 2        | 2      | 0.85%   |
| HGST HTS725050A7E630 500GB            | 2        | 2      | 0.85%   |
| HGST HTS721010A9E630 1TB              | 2        | 2      | 0.85%   |
| Crucial CT525MX300SSD1 528GB          | 2        | 2      | 0.85%   |
| China SSD 240GB                       | 2        | 2      | 0.85%   |
| Apple HDD WDC WD10EALX-408EA0 1TB     | 2        | 2      | 0.85%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 0.43%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1        | 1      | 0.43%   |
| WDC WD80EZZX-11CSGA0 8TB              | 1        | 2      | 0.43%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1        | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 60       | 83     | 26.67%  |
| Seagate                     | 53       | 71     | 23.56%  |
| Samsung Electronics         | 31       | 41     | 13.78%  |
| Toshiba                     | 12       | 12     | 5.33%   |
| Kingston                    | 11       | 15     | 4.89%   |
| Crucial                     | 9        | 10     | 4%      |
| Hitachi                     | 8        | 9      | 3.56%   |
| HGST                        | 8        | 8      | 3.56%   |
| SanDisk                     | 6        | 6      | 2.67%   |
| A-DATA Technology           | 5        | 5      | 2.22%   |
| Intel                       | 3        | 3      | 1.33%   |
| Apple                       | 3        | 3      | 1.33%   |
| China                       | 2        | 2      | 0.89%   |
| Unknown                     | 1        | 1      | 0.44%   |
| Team                        | 1        | 1      | 0.44%   |
| SPCC                        | 1        | 1      | 0.44%   |
| SABRENT                     | 1        | 1      | 0.44%   |
| S3+                         | 1        | 1      | 0.44%   |
| Plextor                     | 1        | 1      | 0.44%   |
| Micron Technology           | 1        | 1      | 0.44%   |
| Maxtor                      | 1        | 1      | 0.44%   |
| Kingston Technology Company | 1        | 1      | 0.44%   |
| Intenso                     | 1        | 1      | 0.44%   |
| Hewlett-Packard             | 1        | 1      | 0.44%   |
| Flashwar                    | 1        | 1      | 0.44%   |
| BAITITON                    | 1        | 1      | 0.44%   |
| ASMT                        | 1        | 1      | 0.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 58       | 81     | 36.48%  |
| Seagate             | 53       | 71     | 33.33%  |
| Samsung Electronics | 13       | 17     | 8.18%   |
| Toshiba             | 12       | 12     | 7.55%   |
| Hitachi             | 8        | 9      | 5.03%   |
| HGST                | 8        | 8      | 5.03%   |
| Apple               | 3        | 3      | 1.89%   |
| Unknown             | 1        | 1      | 0.63%   |
| Maxtor              | 1        | 1      | 0.63%   |
| Hewlett-Packard     | 1        | 1      | 0.63%   |
| ASMT                | 1        | 1      | 0.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 144      | 205    | 68.57%  |
| SSD  | 53       | 64     | 25.24%  |
| NVMe | 13       | 13     | 6.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 25%     |
| Samsung Electronics SSD 980 500GB | 1        | 1      | 25%     |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 25%     |
| Patriot Pyro SSD 120GB            | 1        | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 50%     |
| Seagate             | 1        | 1      | 25%     |
| Patriot             | 1        | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 4471     | 13104  | 79.88%  |
| Works    | 924      | 2299   | 16.51%  |
| Malfunc  | 197      | 282    | 3.52%   |
| Failed   | 4        | 5      | 0.07%   |
| Limited  | 1        | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2787     | 32.16%  |
| AMD                              | 2388     | 27.55%  |
| Samsung Electronics              | 987      | 11.39%  |
| SanDisk                          | 447      | 5.16%   |
| Phison Electronics               | 317      | 3.66%   |
| ASMedia Technology               | 312      | 3.6%    |
| Micron/Crucial Technology        | 228      | 2.63%   |
| Kingston Technology Company      | 209      | 2.41%   |
| Silicon Motion                   | 129      | 1.49%   |
| Marvell Technology Group         | 123      | 1.42%   |
| JMicron Technology               | 109      | 1.26%   |
| ADATA Technology                 | 84       | 0.97%   |
| Nvidia                           | 74       | 0.85%   |
| Realtek Semiconductor            | 70       | 0.81%   |
| SK hynix                         | 54       | 0.62%   |
| Micron Technology                | 48       | 0.55%   |
| MAXIO Technology (Hangzhou)      | 41       | 0.47%   |
| Toshiba America Info Systems     | 39       | 0.45%   |
| Broadcom / LSI                   | 28       | 0.32%   |
| Shenzhen Longsys Electronics     | 27       | 0.31%   |
| Seagate Technology               | 27       | 0.31%   |
| INNOGRIT                         | 21       | 0.24%   |
| LSI Logic / Symbios Logic        | 18       | 0.21%   |
| KIOXIA                           | 15       | 0.17%   |
| VIA Technologies                 | 12       | 0.14%   |
| Solidigm                         | 11       | 0.13%   |
| Lite-On Technology               | 10       | 0.12%   |
| Silicon Image                    | 7        | 0.08%   |
| Netac Technology                 | 7        | 0.08%   |
| Solid State Storage Technology   | 5        | 0.06%   |
| Biwin Storage Technology         | 5        | 0.06%   |
| Adaptec                          | 5        | 0.06%   |
| Apple                            | 4        | 0.05%   |
| Union Memory (Shenzhen)          | 3        | 0.03%   |
| HighPoint Technologies           | 3        | 0.03%   |
| Silicon Integrated Systems [SiS] | 2        | 0.02%   |
| OCZ Technology Group             | 2        | 0.02%   |
| Hewlett-Packard                  | 2        | 0.02%   |
| Yangtze Memory Technologies      | 1        | 0.01%   |
| Synopsys                         | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1284     | 12.37%  |
| AMD 400 Series Chipset SATA Controller                                                  | 579      | 5.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 538      | 5.18%   |
| AMD 500 Series Chipset SATA Controller                                                  | 432      | 4.16%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 293      | 2.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 292      | 2.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 244      | 2.35%   |
| AMD 600 Series Chipset SATA Controller                                                  | 244      | 2.35%   |
| Intel SATA Controller [RAID mode]                                                       | 239      | 2.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 235      | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 203      | 1.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 202      | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 183      | 1.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 165      | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 150      | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 142      | 1.37%   |
| Phison E12 NVMe Controller                                                              | 130      | 1.25%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 112      | 1.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 112      | 1.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 109      | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 108      | 1.04%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 105      | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 105      | 1.01%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 102      | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 100      | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 99       | 0.95%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 98       | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 93       | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 92       | 0.89%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 88       | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 88       | 0.85%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 84       | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 73       | 0.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 67       | 0.65%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 65       | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 64       | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 61       | 0.59%   |
| Intel SSD 660P Series                                                                   | 60       | 0.58%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 60       | 0.58%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 59       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4542     | 55.97%  |
| NVMe | 2401     | 29.59%  |
| IDE  | 708      | 8.72%   |
| RAID | 400      | 4.93%   |
| SAS  | 49       | 0.6%    |
| SCSI | 15       | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2766     | 52.83%  |
| AMD    | 2470     | 47.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 186      | 3.53%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 139      | 2.64%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 115      | 2.19%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 94       | 1.79%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 81       | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 76       | 1.44%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 73       | 1.39%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 72       | 1.37%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 69       | 1.31%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 64       | 1.22%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 63       | 1.2%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 61       | 1.16%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 53       | 1.01%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 53       | 1.01%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 51       | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 51       | 0.97%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 51       | 0.97%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 50       | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 48       | 0.91%   |
| AMD FX-8350 Eight-Core Processor            | 48       | 0.91%   |
| AMD FX-6300 Six-Core Processor              | 45       | 0.86%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 44       | 0.84%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 44       | 0.84%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 43       | 0.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 43       | 0.82%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 42       | 0.8%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 39       | 0.74%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 39       | 0.74%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 37       | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 33       | 0.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 32       | 0.61%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 32       | 0.61%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 31       | 0.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 31       | 0.59%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 31       | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 30       | 0.57%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 30       | 0.57%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 29       | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 28       | 0.53%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 28       | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 841      | 16%     |
| AMD Ryzen 5             | 829      | 15.77%  |
| Intel Core i7           | 768      | 14.61%  |
| AMD Ryzen 7             | 650      | 12.36%  |
| AMD Ryzen 9             | 366      | 6.96%   |
| Intel Xeon              | 267      | 5.08%   |
| Intel Core i3           | 234      | 4.45%   |
| Other                   | 233      | 4.43%   |
| AMD FX                  | 164      | 3.12%   |
| Intel Core i9           | 95       | 1.81%   |
| AMD Ryzen 3             | 88       | 1.67%   |
| Intel Pentium           | 64       | 1.22%   |
| Intel Core 2 Duo        | 64       | 1.22%   |
| AMD Ryzen Threadripper  | 62       | 1.18%   |
| Intel Core 2 Quad       | 56       | 1.07%   |
| Intel Celeron           | 49       | 0.93%   |
| AMD Phenom II X4        | 42       | 0.8%    |
| Intel Pentium Dual-Core | 37       | 0.7%    |
| AMD A10                 | 36       | 0.68%   |
| AMD A8                  | 30       | 0.57%   |
| AMD Athlon II X2        | 29       | 0.55%   |
| AMD Athlon              | 22       | 0.42%   |
| AMD Athlon II X4        | 20       | 0.38%   |
| Intel Core 2            | 18       | 0.34%   |
| AMD Ryzen 5 PRO         | 16       | 0.3%    |
| AMD Phenom II X6        | 16       | 0.3%    |
| AMD A6                  | 16       | 0.3%    |
| AMD A4                  | 14       | 0.27%   |
| AMD Athlon 64 X2        | 13       | 0.25%   |
| Intel Atom              | 11       | 0.21%   |
| Intel Pentium Gold      | 10       | 0.19%   |
| AMD Phenom              | 10       | 0.19%   |
| AMD Athlon X4           | 9        | 0.17%   |
| Intel Pentium Dual      | 8        | 0.15%   |
| AMD Ryzen 7 PRO         | 7        | 0.13%   |
| Intel Pentium D         | 6        | 0.11%   |
| Intel Genuine           | 5        | 0.1%    |
| AMD Sempron             | 5        | 0.1%    |
| AMD Ryzen 3 PRO         | 4        | 0.08%   |
| AMD Phenom II X3        | 4        | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1809     | 34.39%  |
| 6      | 1150     | 21.86%  |
| 8      | 887      | 16.86%  |
| 2      | 596      | 11.33%  |
| 12     | 275      | 5.23%   |
| 16     | 224      | 4.26%   |
| 10     | 75       | 1.43%   |
| 3      | 64       | 1.22%   |
| 24     | 55       | 1.05%   |
| 1      | 42       | 0.8%    |
| 14     | 30       | 0.57%   |
| 32     | 18       | 0.34%   |
| 20     | 17       | 0.32%   |
| 64     | 6        | 0.11%   |
| 36     | 3        | 0.06%   |
| 28     | 3        | 0.06%   |
| 18     | 3        | 0.06%   |
| 52     | 1        | 0.02%   |
| 22     | 1        | 0.02%   |
| 9      | 1        | 0.02%   |
| 5      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 5179     | 98.91%  |
| 2      | 57       | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 3701     | 70.52%  |
| 1      | 1539     | 29.33%  |
| 12     | 3        | 0.06%   |
| 8      | 3        | 0.06%   |
| 16     | 2        | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 5232     | 99.92%  |
| Unknown        | 4        | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4261     | 79.93%  |
| 0x08701021 | 112      | 2.1%    |
| 0x0800820d | 79       | 1.48%   |
| 0x306c3    | 78       | 1.46%   |
| 0x08701013 | 74       | 1.39%   |
| 0x306a9    | 63       | 1.18%   |
| 0x206a7    | 50       | 0.94%   |
| 0x506e3    | 42       | 0.79%   |
| 0x906ea    | 38       | 0.71%   |
| 0x906e9    | 30       | 0.56%   |
| 0x0a201016 | 28       | 0.53%   |
| 0x08001138 | 28       | 0.53%   |
| 0x1067a    | 27       | 0.51%   |
| 0x08108109 | 26       | 0.49%   |
| 0x06000852 | 25       | 0.47%   |
| 0x0a601203 | 18       | 0.34%   |
| 0x0a201009 | 17       | 0.32%   |
| 0x906ec    | 15       | 0.28%   |
| 0x906ed    | 14       | 0.26%   |
| 0x08301039 | 14       | 0.26%   |
| 0x0a20120a | 13       | 0.24%   |
| 0x08001137 | 13       | 0.24%   |
| 0xa0655    | 11       | 0.21%   |
| 0x06001119 | 11       | 0.21%   |
| 0x010000c8 | 11       | 0.21%   |
| 0x306f2    | 9        | 0.17%   |
| 0x106a5    | 9        | 0.17%   |
| 0x0a50000d | 9        | 0.17%   |
| 0x06003106 | 9        | 0.17%   |
| 0xa0653    | 8        | 0.15%   |
| 0x206c2    | 8        | 0.15%   |
| 0x0a50000c | 8        | 0.15%   |
| 0xa0671    | 7        | 0.13%   |
| 0x906eb    | 7        | 0.13%   |
| 0x90672    | 7        | 0.13%   |
| 0x08101016 | 7        | 0.13%   |
| 0x6fd      | 6        | 0.11%   |
| 0x206d7    | 6        | 0.11%   |
| 0x20655    | 6        | 0.11%   |
| 0x6fb      | 5        | 0.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 634      | 12.06%  |
| Zen 3            | 574      | 10.92%  |
| Haswell          | 507      | 9.65%   |
| Unknown          | 483      | 9.19%   |
| KabyLake         | 476      | 9.06%   |
| Zen+             | 346      | 6.58%   |
| IvyBridge        | 341      | 6.49%   |
| SandyBridge      | 290      | 5.52%   |
| Skylake          | 275      | 5.23%   |
| Zen              | 216      | 4.11%   |
| Piledriver       | 191      | 3.63%   |
| CometLake        | 155      | 2.95%   |
| Penryn           | 136      | 2.59%   |
| K10              | 133      | 2.53%   |
| Nehalem          | 103      | 1.96%   |
| Westmere         | 69       | 1.31%   |
| Core             | 63       | 1.2%    |
| Alderlake Hybrid | 50       | 0.95%   |
| Steamroller      | 32       | 0.61%   |
| Broadwell        | 29       | 0.55%   |
| Silvermont       | 23       | 0.44%   |
| K8 Hammer        | 21       | 0.4%    |
| Excavator        | 18       | 0.34%   |
| Bulldozer        | 17       | 0.32%   |
| K10 Llano        | 14       | 0.27%   |
| Goldmont plus    | 12       | 0.23%   |
| NetBurst         | 10       | 0.19%   |
| Icelake          | 9        | 0.17%   |
| Jaguar           | 8        | 0.15%   |
| Goldmont         | 5        | 0.1%    |
| Bobcat           | 5        | 0.1%    |
| Gracemont        | 3        | 0.06%   |
| Bonnell          | 3        | 0.06%   |
| Puma             | 2        | 0.04%   |
| Lunarlake Hybrid | 2        | 0.04%   |
| Tremont          | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 2843     | 49.03%  |
| AMD                              | 1956     | 33.73%  |
| Intel                            | 986      | 17%     |
| Matrox Electronics Systems       | 7        | 0.12%   |
| ASPEED Technology                | 4        | 0.07%   |
| Silicon Integrated Systems [SiS] | 2        | 0.03%   |
| 3Dfx Interactive                 | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 340      | 5.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 183      | 3.01%   |
| AMD Raphael                                                                 | 156      | 2.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 145      | 2.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 144      | 2.37%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 109      | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 105      | 1.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 100      | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 97       | 1.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 95       | 1.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 95       | 1.56%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 85       | 1.4%    |
| Nvidia GK208B [GeForce GT 710]                                              | 84       | 1.38%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 83       | 1.37%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 81       | 1.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 79       | 1.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 79       | 1.3%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 77       | 1.27%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 76       | 1.25%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 74       | 1.22%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 69       | 1.14%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 66       | 1.09%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 64       | 1.05%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 62       | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 60       | 0.99%   |
| AMD Granite Ridge [Radeon Graphics]                                         | 59       | 0.97%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 57       | 0.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 53       | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 51       | 0.84%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 51       | 0.84%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 50       | 0.82%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 49       | 0.81%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 47       | 0.77%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 46       | 0.76%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 46       | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 44       | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 44       | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 43       | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 42       | 0.69%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 40       | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| 1 x Nvidia                | 2506     | 47%     |
| 1 x AMD                   | 1579     | 29.61%  |
| 1 x Intel                 | 689      | 12.92%  |
| AMD + Nvidia              | 171      | 3.21%   |
| 2 x AMD                   | 165      | 3.09%   |
| Intel + Nvidia            | 100      | 1.88%   |
| 2 x Nvidia                | 51       | 0.96%   |
| Intel + AMD               | 41       | 0.77%   |
| Nvidia + ASPEED           | 4        | 0.08%   |
| 1 x Matrox                | 4        | 0.08%   |
| Intel + 2 x Nvidia        | 3        | 0.06%   |
| Other                     | 2        | 0.04%   |
| 4 x Nvidia                | 2        | 0.04%   |
| 3 x Nvidia                | 2        | 0.04%   |
| 1 x SiS                   | 2        | 0.04%   |
| Nvidia + Matrox           | 2        | 0.04%   |
| AMD + 2 x Nvidia          | 2        | 0.04%   |
| 5 x Nvidia                | 1        | 0.02%   |
| 2 x Intel                 | 1        | 0.02%   |
| 2 x AMD + 2 x Nvidia      | 1        | 0.02%   |
| 2 x AMD + 1 x Nvidia      | 1        | 0.02%   |
| Nvidia + 3Dfx Interactive | 1        | 0.02%   |
| Intel + AMD + 2 x Nvidia  | 1        | 0.02%   |
| AMD + Matrox              | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2929     | 54.97%  |
| Proprietary | 2116     | 39.71%  |
| Unknown     | 283      | 5.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3311     | 61.6%   |
| 7.01-8.0   | 577      | 10.73%  |
| 1.01-2.0   | 351      | 6.53%   |
| 3.01-4.0   | 336      | 6.25%   |
| 5.01-6.0   | 282      | 5.25%   |
| 8.01-16.0  | 249      | 4.63%   |
| 0.51-1.0   | 94       | 1.75%   |
| 0.01-0.5   | 69       | 1.28%   |
| 2.01-3.0   | 56       | 1.04%   |
| 16.01-24.0 | 44       | 0.82%   |
| 4.01-5.0   | 3        | 0.06%   |
| 24.01-32.0 | 2        | 0.04%   |
| 32.01-64.0 | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 954      | 15.97%  |
| Goldstar             | 690      | 11.55%  |
| Dell                 | 623      | 10.43%  |
| Acer                 | 516      | 8.64%   |
| Hewlett-Packard      | 374      | 6.26%   |
| AOC                  | 331      | 5.54%   |
| Ancor Communications | 267      | 4.47%   |
| BenQ                 | 264      | 4.42%   |
| ASUSTek Computer     | 247      | 4.14%   |
| Philips              | 172      | 2.88%   |
| MSI                  | 108      | 1.81%   |
| Lenovo               | 100      | 1.67%   |
| ViewSonic            | 99       | 1.66%   |
| Iiyama               | 91       | 1.52%   |
| Sony                 | 73       | 1.22%   |
| Sceptre Tech         | 61       | 1.02%   |
| Gigabyte Technology  | 50       | 0.84%   |
| Vizio                | 46       | 0.77%   |
| Unknown              | 37       | 0.62%   |
| Toshiba              | 30       | 0.5%    |
| Panasonic            | 27       | 0.45%   |
| Fujitsu Siemens      | 27       | 0.45%   |
| Insignia             | 25       | 0.42%   |
| Eizo                 | 25       | 0.42%   |
| NEC Computers        | 24       | 0.4%    |
| HKC                  | 21       | 0.35%   |
| Hitachi              | 20       | 0.33%   |
| Vestel Elektronik    | 18       | 0.3%    |
| Unknown (XXX)        | 18       | 0.3%    |
| Mi                   | 18       | 0.3%    |
| HannStar             | 16       | 0.27%   |
| Valve                | 15       | 0.25%   |
| MStar                | 15       | 0.25%   |
| LG Electronics       | 15       | 0.25%   |
| RTK                  | 14       | 0.23%   |
| SKG                  | 13       | 0.22%   |
| Viotek               | 12       | 0.2%    |
| Sharp                | 12       | 0.2%    |
| Pixio                | 12       | 0.2%    |
| ONN                  | 12       | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 48       | 0.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 46       | 0.72%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 33       | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 31       | 0.49%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 26       | 0.41%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 25       | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 23       | 0.36%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                   | 23       | 0.36%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch              | 20       | 0.31%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 20       | 0.31%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 19       | 0.3%    |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 19       | 0.3%    |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch | 18       | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 18       | 0.28%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch     | 18       | 0.28%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                     | 17       | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 16       | 0.25%   |
| Valve Index HMD VLV91A8                                              | 15       | 0.24%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 15       | 0.24%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                               | 15       | 0.24%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 15       | 0.24%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 14       | 0.22%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch  | 14       | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 14       | 0.22%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 14       | 0.22%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                     | 14       | 0.22%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch       | 13       | 0.2%    |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch             | 13       | 0.2%    |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 12       | 0.19%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 12       | 0.19%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch     | 12       | 0.19%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 11       | 0.17%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch               | 11       | 0.17%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 597x336mm 27.0-inch       | 11       | 0.17%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                   | 11       | 0.17%   |
| BenQ ZOWIE XL LCD BNQ7F33 1920x1080 531x298mm 24.0-inch              | 11       | 0.17%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch         | 11       | 0.17%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch         | 11       | 0.17%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch     | 11       | 0.17%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch       | 10       | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2570     | 45.33%  |
| 3840x2160 (4K)     | 795      | 14.02%  |
| 2560x1440 (QHD)    | 685      | 12.08%  |
| 3440x1440          | 249      | 4.39%   |
| 1680x1050 (WSXGA+) | 195      | 3.44%   |
| 1280x1024 (SXGA)   | 162      | 2.86%   |
| 1366x768 (WXGA)    | 159      | 2.8%    |
| 2560x1080          | 154      | 2.72%   |
| 1920x1200 (WUXGA)  | 115      | 2.03%   |
| 1440x900 (WXGA+)   | 113      | 1.99%   |
| 1600x900 (HD+)     | 107      | 1.89%   |
| 1360x768           | 69       | 1.22%   |
| 3840x1080          | 58       | 1.02%   |
| 1920x540           | 47       | 0.83%   |
| Unknown            | 46       | 0.81%   |
| 3840x1600          | 22       | 0.39%   |
| 2288x1287          | 16       | 0.28%   |
| 1024x768 (XGA)     | 15       | 0.26%   |
| 2560x1600          | 14       | 0.25%   |
| 1600x1200          | 11       | 0.19%   |
| 1280x720 (HD)      | 11       | 0.19%   |
| 3840x1200          | 6        | 0.11%   |
| 4480x1440          | 5        | 0.09%   |
| 2048x1152          | 5        | 0.09%   |
| 5120x1440          | 2        | 0.04%   |
| 2520x1680          | 2        | 0.04%   |
| 2160x1440          | 2        | 0.04%   |
| 9840x3840          | 1        | 0.02%   |
| 8320x2160          | 1        | 0.02%   |
| 8160x4627          | 1        | 0.02%   |
| 800x480            | 1        | 0.02%   |
| 7680x2160          | 1        | 0.02%   |
| 6400x1440          | 1        | 0.02%   |
| 5280x1080          | 1        | 0.02%   |
| 5200x2160          | 1        | 0.02%   |
| 4096x2160          | 1        | 0.02%   |
| 4080x2030          | 1        | 0.02%   |
| 4080x2026          | 1        | 0.02%   |
| 4000x1440          | 1        | 0.02%   |
| 3840x2560          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 1095     | 18.43%  |
| 24      | 943      | 15.87%  |
| 23      | 677      | 11.4%   |
| 31      | 484      | 8.15%   |
| 21      | 465      | 7.83%   |
| 34      | 328      | 5.52%   |
| 19      | 199      | 3.35%   |
| Unknown | 187      | 3.15%   |
| 22      | 148      | 2.49%   |
| 18      | 139      | 2.34%   |
| 84      | 126      | 2.12%   |
| 20      | 119      | 2%      |
| 32      | 92       | 1.55%   |
| 17      | 88       | 1.48%   |
| 72      | 80       | 1.35%   |
| 40      | 67       | 1.13%   |
| 15      | 67       | 1.13%   |
| 54      | 56       | 0.94%   |
| 48      | 50       | 0.84%   |
| 26      | 42       | 0.71%   |
| 25      | 39       | 0.66%   |
| 63      | 36       | 0.61%   |
| 28      | 36       | 0.61%   |
| 65      | 29       | 0.49%   |
| 52      | 26       | 0.44%   |
| 35      | 26       | 0.44%   |
| 37      | 24       | 0.4%    |
| 29      | 23       | 0.39%   |
| 49      | 21       | 0.35%   |
| 46      | 18       | 0.3%    |
| 36      | 18       | 0.3%    |
| 43      | 16       | 0.27%   |
| 74      | 15       | 0.25%   |
| 142     | 14       | 0.24%   |
| 42      | 14       | 0.24%   |
| 33      | 14       | 0.24%   |
| 38      | 13       | 0.22%   |
| 44      | 10       | 0.17%   |
| 16      | 9        | 0.15%   |
| 12      | 8        | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2420     | 42.73%  |
| 401-500        | 952      | 16.81%  |
| 601-700        | 671      | 11.85%  |
| 701-800        | 436      | 7.7%    |
| 1001-1500      | 281      | 4.96%   |
| 1501-2000      | 235      | 4.15%   |
| Unknown        | 187      | 3.3%    |
| 801-900        | 148      | 2.61%   |
| 301-350        | 144      | 2.54%   |
| 351-400        | 120      | 2.12%   |
| 901-1000       | 32       | 0.56%   |
| 201-300        | 24       | 0.42%   |
| More than 2000 | 14       | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3837     | 73.87%  |
| 16/10   | 526      | 10.13%  |
| 21/9    | 399      | 7.68%   |
| 5/4     | 158      | 3.04%   |
| Unknown | 107      | 2.06%   |
| 32/9    | 65       | 1.25%   |
| 4/3     | 47       | 0.9%    |
| 3/2     | 16       | 0.31%   |
| 1.00    | 15       | 0.29%   |
| 6/5     | 8        | 0.15%   |
| 1.96    | 7        | 0.13%   |
| 3.20    | 6        | 0.12%   |
| 6.00    | 1        | 0.02%   |
| 3.75    | 1        | 0.02%   |
| 2.12    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1731     | 29.96%  |
| 301-350        | 1121     | 19.4%   |
| 351-500        | 948      | 16.41%  |
| 151-200        | 445      | 7.7%    |
| More than 1000 | 434      | 7.51%   |
| 251-300        | 359      | 6.21%   |
| 501-1000       | 256      | 4.43%   |
| Unknown        | 187      | 3.24%   |
| 141-150        | 183      | 3.17%   |
| 101-110        | 64       | 1.11%   |
| 71-80          | 13       | 0.22%   |
| 131-140        | 12       | 0.21%   |
| 111-120        | 9        | 0.16%   |
| 51-60          | 6        | 0.1%    |
| 121-130        | 5        | 0.09%   |
| 91-100         | 3        | 0.05%   |
| 81-90          | 2        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 3278     | 60.78%  |
| 101-120       | 1144     | 21.21%  |
| 121-160       | 328      | 6.08%   |
| 1-50          | 319      | 5.92%   |
| Unknown       | 187      | 3.47%   |
| 161-240       | 135      | 2.5%    |
| More than 240 | 2        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3662     | 68.26%  |
| 2     | 1181     | 22.01%  |
| 0     | 328      | 6.11%   |
| 3     | 172      | 3.21%   |
| 4     | 19       | 0.35%   |
| 5     | 2        | 0.04%   |
| 6     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 3198     | 40.72%  |
| Intel                                 | 2565     | 32.66%  |
| Qualcomm Atheros                      | 397      | 5.06%   |
| Broadcom                              | 244      | 3.11%   |
| MediaTek                              | 220      | 2.8%    |
| TP-Link                               | 153      | 1.95%   |
| Ralink Technology                     | 121      | 1.54%   |
| Microsoft                             | 97       | 1.24%   |
| Samsung Electronics                   | 65       | 0.83%   |
| Aquantia                              | 65       | 0.83%   |
| Nvidia                                | 60       | 0.76%   |
| Ralink                                | 59       | 0.75%   |
| NetGear                               | 55       | 0.7%    |
| InterBiometrics                       | 50       | 0.64%   |
| Qualcomm Atheros Communications       | 43       | 0.55%   |
| ASIX Electronics                      | 32       | 0.41%   |
| D-Link                                | 29       | 0.37%   |
| Marvell Technology Group              | 28       | 0.36%   |
| Google                                | 28       | 0.36%   |
| Xiaomi                                | 26       | 0.33%   |
| Linksys                               | 23       | 0.29%   |
| Broadcom Limited                      | 22       | 0.28%   |
| ASUSTek Computer                      | 21       | 0.27%   |
| Huawei Technologies                   | 19       | 0.24%   |
| Qualcomm Technologies                 | 14       | 0.18%   |
| OPPO Electronics                      | 12       | 0.15%   |
| D-Link System                         | 12       | 0.15%   |
| Motorola PCS                          | 11       | 0.14%   |
| Edimax Technology                     | 11       | 0.14%   |
| DisplayLink                           | 11       | 0.14%   |
| Belkin Components                     | 11       | 0.14%   |
| OnePlus Technology (Shenzhen)         | 8        | 0.1%    |
| Qualcomm                              | 6        | 0.08%   |
| QinHeng Electronics                   | 6        | 0.08%   |
| Mellanox Technologies                 | 6        | 0.08%   |
| AVM                                   | 6        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 6        | 0.08%   |
| VIA Technologies                      | 5        | 0.06%   |
| Sitecom Europe                        | 5        | 0.06%   |
| Microchip Technology                  | 5        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2290     | 24.96%  |
| Realtek RTL8125 2.5GbE Controller                                      | 558      | 6.08%   |
| Intel I211 Gigabit Network Connection                                  | 519      | 5.66%   |
| Intel Wi-Fi 6 AX200                                                    | 456      | 4.97%   |
| Intel Ethernet Controller I225-V                                       | 265      | 2.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 228      | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 168      | 1.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 139      | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 129      | 1.41%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 125      | 1.36%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 117      | 1.28%   |
| Intel Ethernet Connection I217-LM                                      | 110      | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 94       | 1.02%   |
| Realtek 802.11ac NIC                                                   | 92       | 1%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 86       | 0.94%   |
| Intel 82579V Gigabit Network Connection                                | 77       | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 73       | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 72       | 0.78%   |
| Intel Ethernet Connection (2) I218-V                                   | 66       | 0.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 61       | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 59       | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 58       | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 58       | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 55       | 0.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 55       | 0.6%    |
| Ralink MT7601U Wireless Adapter                                        | 54       | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 52       | 0.57%   |
| Intel Ethernet Controller I226-V                                       | 52       | 0.57%   |
| Intel 700 Series Chipset CNVi WiFi                                     | 51       | 0.56%   |
| InterBiometrics Io                                                     | 49       | 0.53%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 48       | 0.52%   |
| Nvidia MCP61 Ethernet                                                  | 45       | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 44       | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                  | 44       | 0.48%   |
| Intel 82574L Gigabit Network Connection                                | 43       | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 42       | 0.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 41       | 0.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 38       | 0.41%   |
| Intel Wireless 7265                                                    | 38       | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 36       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 1210     | 39.36%  |
| Realtek Semiconductor                 | 625      | 20.33%  |
| Qualcomm Atheros                      | 208      | 6.77%   |
| MediaTek                              | 194      | 6.31%   |
| Broadcom                              | 156      | 5.07%   |
| TP-Link                               | 147      | 4.78%   |
| Ralink Technology                     | 121      | 3.94%   |
| Microsoft                             | 96       | 3.12%   |
| Ralink                                | 59       | 1.92%   |
| NetGear                               | 55       | 1.79%   |
| Qualcomm Atheros Communications       | 43       | 1.4%    |
| D-Link                                | 27       | 0.88%   |
| Linksys                               | 22       | 0.72%   |
| ASUSTek Computer                      | 21       | 0.68%   |
| Edimax Technology                     | 11       | 0.36%   |
| Broadcom Limited                      | 11       | 0.36%   |
| Belkin Components                     | 11       | 0.36%   |
| D-Link System                         | 7        | 0.23%   |
| AVM                                   | 6        | 0.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 6        | 0.2%    |
| Sitecom Europe                        | 5        | 0.16%   |
| Mercucys                              | 5        | 0.16%   |
| Gemtek                                | 5        | 0.16%   |
| Realtek                               | 4        | 0.13%   |
| Qualcomm Technologies                 | 4        | 0.13%   |
| IMC Networks                          | 3        | 0.1%    |
| Micro Star International              | 2        | 0.07%   |
| Accton Technology                     | 2        | 0.07%   |
| ZyDAS                                 | 1        | 0.03%   |
| Wilocity                              | 1        | 0.03%   |
| Wacom                                 | 1        | 0.03%   |
| TRENDnet                              | 1        | 0.03%   |
| Texas Instruments                     | 1        | 0.03%   |
| Samsung Electronics                   | 1        | 0.03%   |
| Ovislink                              | 1        | 0.03%   |
| BUFFALO                               | 1        | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 456      | 14.68%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 139      | 4.48%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 125      | 4.02%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 117      | 3.77%   |
| Realtek 802.11ac NIC                                                 | 92       | 2.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 92       | 2.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 86       | 2.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 73       | 2.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 72       | 2.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 59       | 1.9%    |
| Ralink MT7601U Wireless Adapter                                      | 54       | 1.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 52       | 1.67%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 51       | 1.64%   |
| Microsoft Xbox Wireless Adapter for Windows                          | 48       | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 42       | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 41       | 1.32%   |
| Intel Wireless 7265                                                  | 38       | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 36       | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                      | 35       | 1.13%   |
| Intel Wireless 7260                                                  | 35       | 1.13%   |
| Intel Wireless 8265 / 8275                                           | 34       | 1.09%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 34       | 1.09%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 32       | 1.03%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 31       | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                       | 31       | 1%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 29       | 0.93%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 28       | 0.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 28       | 0.9%    |
| Intel Wireless 8260                                                  | 28       | 0.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 24       | 0.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 24       | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 24       | 0.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 23       | 0.74%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 23       | 0.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 22       | 0.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 22       | 0.71%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 22       | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 21       | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 19       | 0.61%   |
| NetGear A6210                                                        | 19       | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 2965     | 51.69%  |
| Intel                            | 2007     | 34.99%  |
| Qualcomm Atheros                 | 205      | 3.57%   |
| Broadcom                         | 101      | 1.76%   |
| Aquantia                         | 65       | 1.13%   |
| Samsung Electronics              | 64       | 1.12%   |
| Nvidia                           | 60       | 1.05%   |
| ASIX Electronics                 | 32       | 0.56%   |
| Marvell Technology Group         | 28       | 0.49%   |
| Google                           | 28       | 0.49%   |
| Xiaomi                           | 26       | 0.45%   |
| MediaTek                         | 18       | 0.31%   |
| Huawei Technologies              | 18       | 0.31%   |
| OPPO Electronics                 | 12       | 0.21%   |
| Motorola PCS                     | 11       | 0.19%   |
| DisplayLink                      | 11       | 0.19%   |
| Broadcom Limited                 | 11       | 0.19%   |
| Qualcomm Technologies            | 10       | 0.17%   |
| TP-Link                          | 6        | 0.1%    |
| Qualcomm                         | 6        | 0.1%    |
| VIA Technologies                 | 5        | 0.09%   |
| OnePlus Technology (Shenzhen)    | 5        | 0.09%   |
| Mellanox Technologies            | 5        | 0.09%   |
| D-Link System                    | 5        | 0.09%   |
| American Megatrends              | 4        | 0.07%   |
| Lenovo                           | 3        | 0.05%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.03%   |
| T & A Mobile Phones              | 2        | 0.03%   |
| ICS Advent                       | 2        | 0.03%   |
| D-Link                           | 2        | 0.03%   |
| 3Com                             | 2        | 0.03%   |
| Tehuti Networks                  | 1        | 0.02%   |
| Solarflare Communications        | 1        | 0.02%   |
| Silicon Integrated Systems [SiS] | 1        | 0.02%   |
| QLogic                           | 1        | 0.02%   |
| Netchip Technology               | 1        | 0.02%   |
| Motorola BCS                     | 1        | 0.02%   |
| Microsoft                        | 1        | 0.02%   |
| Linksys                          | 1        | 0.02%   |
| LG Electronics                   | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 2290     | 38.48%  |
| Realtek RTL8125 2.5GbE Controller                                              | 558      | 9.38%   |
| Intel I211 Gigabit Network Connection                                          | 519      | 8.72%   |
| Intel Ethernet Controller I225-V                                               | 265      | 4.45%   |
| Intel Ethernet Connection (2) I219-V                                           | 228      | 3.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 168      | 2.82%   |
| Intel Ethernet Connection (7) I219-V                                           | 129      | 2.17%   |
| Intel Ethernet Connection I217-LM                                              | 110      | 1.85%   |
| Intel 82579V Gigabit Network Connection                                        | 77       | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                           | 66       | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 61       | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 58       | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 58       | 0.97%   |
| Intel Ethernet Connection I217-V                                               | 55       | 0.92%   |
| Intel Ethernet Controller I226-V                                               | 52       | 0.87%   |
| Nvidia MCP61 Ethernet                                                          | 45       | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 44       | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                          | 44       | 0.74%   |
| Intel 82574L Gigabit Network Connection                                        | 43       | 0.72%   |
| Intel I210 Gigabit Network Connection                                          | 36       | 0.6%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 33       | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 32       | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 28       | 0.47%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 28       | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 26       | 0.44%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 25       | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 22       | 0.37%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 21       | 0.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 21       | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 20       | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 20       | 0.34%   |
| Intel Ethernet Connection (2) I218-LM                                          | 19       | 0.32%   |
| Intel Ethernet Connection (14) I219-V                                          | 19       | 0.32%   |
| Intel Ethernet Connection (11) I219-V                                          | 19       | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 18       | 0.3%    |
| Realtek RTL8126 5GbE Controller                                                | 17       | 0.29%   |
| Intel 82578DM Gigabit Network Connection                                       | 17       | 0.29%   |
| Huawei FOA-LX9                                                                 | 16       | 0.27%   |
| Google Nexus/Pixel Device (tether)                                             | 15       | 0.25%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 14       | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5178     | 63.43%  |
| WiFi     | 2870     | 35.16%  |
| Modem    | 92       | 1.13%   |
| Unknown  | 23       | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3912     | 70.47%  |
| WiFi     | 1637     | 29.49%  |
| Unknown  | 2        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2847     | 54.01%  |
| 2     | 2043     | 38.76%  |
| 3     | 283      | 5.37%   |
| 0     | 43       | 0.82%   |
| 4     | 41       | 0.78%   |
| 5     | 9        | 0.17%   |
| 6     | 3        | 0.06%   |
| 10    | 2        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3878     | 72.69%  |
| Yes  | 1457     | 27.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 1136     | 47.1%   |
| Cambridge Silicon Radio         | 387      | 16.04%  |
| Realtek Semiconductor           | 182      | 7.55%   |
| ASUSTek Computer                | 125      | 5.18%   |
| MediaTek                        | 118      | 4.89%   |
| Broadcom                        | 81       | 3.36%   |
| IMC Networks                    | 80       | 3.32%   |
| Foxconn / Hon Hai               | 73       | 3.03%   |
| Qualcomm Atheros Communications | 63       | 2.61%   |
| TP-Link                         | 48       | 1.99%   |
| Apple                           | 40       | 1.66%   |
| Dynex                           | 13       | 0.54%   |
| Realtek                         | 9        | 0.37%   |
| Actions                         | 8        | 0.33%   |
| Unknown                         | 7        | 0.29%   |
| Lite-On Technology              | 6        | 0.25%   |
| Integrated System Solution      | 4        | 0.17%   |
| HTC (High Tech Computer)        | 4        | 0.17%   |
| Edimax Technology               | 4        | 0.17%   |
| Dell                            | 4        | 0.17%   |
| SINO WEALTH                     | 3        | 0.12%   |
| Ralink                          | 3        | 0.12%   |
| Logitech                        | 3        | 0.12%   |
| Hewlett-Packard                 | 2        | 0.08%   |
| Creative Technology             | 2        | 0.08%   |
| Conwise Technology              | 2        | 0.08%   |
| Belkin Components               | 2        | 0.08%   |
| TDK                             | 1        | 0.04%   |
| Primax Electronics              | 1        | 0.04%   |
| Micro Star International        | 1        | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                    | 421      | 17.43%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 387      | 16.02%  |
| Intel Bluetooth wireless interface                       | 139      | 5.75%   |
| Realtek Bluetooth Radio                                  | 137      | 5.67%   |
| Intel Wireless-AC 3168 Bluetooth                         | 135      | 5.59%   |
| MediaTek Wireless_Device                                 | 118      | 4.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 115      | 4.76%   |
| Intel AX210 Bluetooth                                    | 107      | 4.43%   |
| Intel AX201 Bluetooth                                    | 88       | 3.64%   |
| Intel Bluetooth Device                                   | 63       | 2.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 63       | 2.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 59       | 2.44%   |
| TP-Link TP-T@- UB500 Adapter                             | 48       | 1.99%   |
| IMC Networks Bluetooth Radio                             | 44       | 1.82%   |
| Foxconn / Hon Hai Wireless_Device                        | 38       | 1.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 37       | 1.53%   |
| IMC Networks Wireless_Device                             | 33       | 1.37%   |
| ASUS Bluetooth Radio                                     | 32       | 1.32%   |
| Qualcomm Atheros  Bluetooth Device                       | 31       | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                       | 25       | 1.03%   |
| ASUS ASUS USB-BT500                                      | 24       | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                           | 22       | 0.91%   |
| Apple Bluetooth Host Controller                          | 20       | 0.83%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 13       | 0.54%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 11       | 0.46%   |
| ASUS BCM20702A0                                          | 10       | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 10       | 0.41%   |
| Realtek Bluetooth Radio                                  | 9        | 0.37%   |
| Realtek Bluetooth 5.3 Radio                              | 8        | 0.33%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 8        | 0.33%   |
| ASUS Qualcomm Bluetooth 4.1                              | 8        | 0.33%   |
| Actions general adapter                                  | 8        | 0.33%   |
| Unknown                                                  | 7        | 0.29%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 6        | 0.25%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 6        | 0.25%   |
| Foxconn / Hon Hai Bluetooth Radio                        | 6        | 0.25%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 6        | 0.25%   |
| Realtek RTL8821A Bluetooth                               | 5        | 0.21%   |
| Realtek Bluetooth 5.4 Radio                              | 5        | 0.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 5        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD                                          | 2921     | 27.94%  |
| Nvidia                                       | 2757     | 26.37%  |
| Intel                                        | 2664     | 25.48%  |
| C-Media Electronics                          | 271      | 2.59%   |
| Logitech                                     | 165      | 1.58%   |
| Creative Labs                                | 104      | 0.99%   |
| Razer USA                                    | 98       | 0.94%   |
| ASUSTek Computer                             | 98       | 0.94%   |
| Kingston Technology                          | 97       | 0.93%   |
| SteelSeries ApS                              | 80       | 0.77%   |
| Focusrite-Novation                           | 71       | 0.68%   |
| JMTek                                        | 70       | 0.67%   |
| Corsair                                      | 68       | 0.65%   |
| Texas Instruments                            | 65       | 0.62%   |
| Micro Star International                     | 60       | 0.57%   |
| Creative Technology                          | 50       | 0.48%   |
| Blue Microphones                             | 45       | 0.43%   |
| Generalplus Technology                       | 36       | 0.34%   |
| Hewlett-Packard                              | 30       | 0.29%   |
| Giga-Byte Technology                         | 27       | 0.26%   |
| DSEA A/S                                     | 25       | 0.24%   |
| Sony                                         | 24       | 0.23%   |
| GN Netcom                                    | 23       | 0.22%   |
| Astro Gaming                                 | 23       | 0.22%   |
| Plantronics                                  | 21       | 0.2%    |
| Valve Software                               | 20       | 0.19%   |
| Realtek Semiconductor                        | 20       | 0.19%   |
| Thesycon Systemsoftware & Consulting         | 17       | 0.16%   |
| Tenx Technology                              | 16       | 0.15%   |
| FiiO Electronics Technology                  | 15       | 0.14%   |
| BEHRINGER International                      | 15       | 0.14%   |
| Turtle Beach                                 | 14       | 0.13%   |
| M-Audio                                      | 14       | 0.13%   |
| SAVITECH                                     | 13       | 0.12%   |
| Samson Technologies                          | 13       | 0.12%   |
| RODE Microphones                             | 13       | 0.12%   |
| KTMicro                                      | 13       | 0.12%   |
| Audio-Technica                               | 13       | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 11       | 0.11%   |
| Yamaha                                       | 11       | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 1008     | 8.19%   |
| AMD Ryzen HD Audio Controller                                              | 552      | 4.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 381      | 3.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 364      | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 330      | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 300      | 2.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 268      | 2.18%   |
| Intel 200 Series PCH HD Audio                                              | 267      | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 256      | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 250      | 2.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 249      | 2.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 237      | 1.93%   |
| AMD Radeon High Definition Audio Controller                                | 231      | 1.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 202      | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 194      | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 193      | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                            | 189      | 1.54%   |
| Nvidia GA104 High Definition Audio Controller                              | 180      | 1.46%   |
| AMD Navi 10 HDMI Audio                                                     | 175      | 1.42%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 170      | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 168      | 1.36%   |
| Nvidia TU104 HD Audio Controller                                           | 155      | 1.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 154      | 1.25%   |
| Nvidia GA102 High Definition Audio Controller                              | 148      | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 122      | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 117      | 0.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 116      | 0.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 116      | 0.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 113      | 0.92%   |
| Intel Alder Lake-S HD Audio Controller                                     | 109      | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 107      | 0.87%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 101      | 0.82%   |
| AMD FCH Azalia Controller                                                  | 101      | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                              | 100      | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                              | 96       | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 89       | 0.72%   |
| Intel Raptor Lake High Definition Audio Controller                         | 82       | 0.67%   |
| ASUSTek Computer USB Audio                                                 | 79       | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                              | 78       | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 73       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 264      | 23.83%  |
| G.Skill                      | 179      | 16.16%  |
| Kingston                     | 174      | 15.7%   |
| Crucial                      | 104      | 9.39%   |
| Unknown                      | 66       | 5.96%   |
| Samsung Electronics          | 54       | 4.87%   |
| SK hynix                     | 51       | 4.6%    |
| Team                         | 48       | 4.33%   |
| Micron Technology            | 37       | 3.34%   |
| A-DATA Technology            | 27       | 2.44%   |
| Unknown                      | 21       | 1.9%    |
| Patriot                      | 17       | 1.53%   |
| Ramaxel Technology           | 5        | 0.45%   |
| Patriot Memory               | 4        | 0.36%   |
| Avant                        | 4        | 0.36%   |
| Apacer                       | 4        | 0.36%   |
| Silicon Power                | 3        | 0.27%   |
| Unknown (ABCD)               | 2        | 0.18%   |
| Unifosa                      | 2        | 0.18%   |
| Patriot Memory (PDP Systems) | 2        | 0.18%   |
| OLOY                         | 2        | 0.18%   |
| Neo Forza                    | 2        | 0.18%   |
| Juhor                        | 2        | 0.18%   |
| GOODRAM                      | 2        | 0.18%   |
| Goldkey                      | 2        | 0.18%   |
| GLOWAY                       | 2        | 0.18%   |
| ASint Technology             | 2        | 0.18%   |
| Wodposit                     | 1        | 0.09%   |
| Unknown (0x0E9D)             | 1        | 0.09%   |
| Unknown (0x0B45)             | 1        | 0.09%   |
| Unknown (0B92)               | 1        | 0.09%   |
| Transcend                    | 1        | 0.09%   |
| Toshiba                      | 1        | 0.09%   |
| Thermaltake                  | 1        | 0.09%   |
| Teikon                       | 1        | 0.09%   |
| TeamGroup                    | 1        | 0.09%   |
| Smart                        | 1        | 0.09%   |
| PNY                          | 1        | 0.09%   |
| Pioneer                      | 1        | 0.09%   |
| Nanya Technology             | 1        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 24       | 2.03%   |
| Unknown                                                 | 21       | 1.78%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s   | 20       | 1.69%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3600MT/s  | 19       | 1.61%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s     | 13       | 1.1%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 12       | 1.02%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 11       | 0.93%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 11       | 0.93%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s  | 11       | 0.93%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s     | 10       | 0.85%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s  | 9        | 0.76%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s      | 8        | 0.68%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s   | 8        | 0.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 7        | 0.59%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GiB DIMM DDR4 3600MT/s | 7        | 0.59%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s     | 7        | 0.59%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 7        | 0.59%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s             | 7        | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 6        | 0.51%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 6        | 0.51%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s    | 6        | 0.51%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 6        | 0.51%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s            | 6        | 0.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 5        | 0.42%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 5        | 0.42%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s      | 5        | 0.42%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s     | 5        | 0.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s     | 5        | 0.42%   |
| G.Skill RAM F5-6000J3040G32G 32GB DIMM DDR5 6200MT/s    | 5        | 0.42%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 5        | 0.42%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s  | 5        | 0.42%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s   | 5        | 0.42%   |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s  | 5        | 0.42%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s    | 5        | 0.42%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s  | 5        | 0.42%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3466MT/s   | 5        | 0.42%   |
| Corsair RAM CMH32GX5M2E6000C36 16GB DIMM DDR5 6000MT/s  | 5        | 0.42%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s     | 4        | 0.34%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 4        | 0.34%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3              | 4        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 682      | 66.6%   |
| DDR3    | 173      | 16.89%  |
| DDR5    | 118      | 11.52%  |
| Unknown | 17       | 1.66%   |
| DDR2    | 15       | 1.46%   |
| SDRAM   | 13       | 1.27%   |
| LPDDR4  | 3        | 0.29%   |
| DDR     | 2        | 0.2%    |
| DRAM    | 1        | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 976      | 96.06%  |
| SODIMM       | 38       | 3.74%   |
| Row Of Chips | 1        | 0.1%    |
| RIMM         | 1        | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 410      | 38.1%   |
| 16384 | 349      | 32.43%  |
| 4096  | 137      | 12.73%  |
| 32768 | 132      | 12.27%  |
| 2048  | 31       | 2.88%   |
| 1024  | 10       | 0.93%   |
| 65536 | 2        | 0.19%   |
| 49152 | 2        | 0.19%   |
| 512   | 2        | 0.19%   |
| 24576 | 1        | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 210      | 18.8%   |
| 3200    | 107      | 9.58%   |
| 1600    | 98       | 8.77%   |
| 2400    | 61       | 5.46%   |
| 3800    | 53       | 4.74%   |
| 1333    | 51       | 4.57%   |
| 2667    | 48       | 4.3%    |
| 2133    | 44       | 3.94%   |
| 6000    | 41       | 3.67%   |
| 3733    | 41       | 3.67%   |
| 3000    | 37       | 3.31%   |
| 4000    | 26       | 2.33%   |
| 3400    | 25       | 2.24%   |
| 4800    | 20       | 1.79%   |
| 2666    | 19       | 1.7%    |
| 3866    | 14       | 1.25%   |
| 3466    | 14       | 1.25%   |
| 6400    | 13       | 1.16%   |
| 5600    | 13       | 1.16%   |
| 1866    | 12       | 1.07%   |
| 1800    | 12       | 1.07%   |
| 800     | 12       | 1.07%   |
| 2933    | 10       | 0.9%    |
| 2800    | 8        | 0.72%   |
| 1867    | 8        | 0.72%   |
| 12800   | 7        | 0.63%   |
| 6200    | 7        | 0.63%   |
| 5200    | 7        | 0.63%   |
| 4400    | 7        | 0.63%   |
| 3066    | 7        | 0.63%   |
| 667     | 7        | 0.63%   |
| Unknown | 7        | 0.63%   |
| 3666    | 6        | 0.54%   |
| 3266    | 6        | 0.54%   |
| 3333    | 4        | 0.36%   |
| 6800    | 3        | 0.27%   |
| 5400    | 3        | 0.27%   |
| 3467    | 3        | 0.27%   |
| 3334    | 3        | 0.27%   |
| 3100    | 3        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 58       | 29.44%  |
| Brother Industries    | 41       | 20.81%  |
| Canon                 | 29       | 14.72%  |
| Samsung Electronics   | 23       | 11.68%  |
| Seiko Epson           | 20       | 10.15%  |
| Dymo-CoStar           | 6        | 3.05%   |
| Fuji Xerox            | 3        | 1.52%   |
| STMicroelectronics    | 2        | 1.02%   |
| QinHeng Electronics   | 2        | 1.02%   |
| Kyocera               | 2        | 1.02%   |
| Dell                  | 2        | 1.02%   |
| Xerox                 | 1        | 0.51%   |
| Sharp                 | 1        | 0.51%   |
| Ricoh                 | 1        | 0.51%   |
| Prolific Technology   | 1        | 0.51%   |
| PM                    | 1        | 0.51%   |
| Pantum                | 1        | 0.51%   |
| Oki Data              | 1        | 0.51%   |
| Lexmark International | 1        | 0.51%   |
| Apple                 | 1        | 0.51%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Brother Printer                                           | 5        | 2.53%   |
| HP Deskjet 3050 J610 series                               | 4        | 2.02%   |
| Brother HL-2130 series                                    | 4        | 2.02%   |
| Samsung SCX-3400 Series                                   | 3        | 1.52%   |
| Samsung M2070 Series                                      | 3        | 1.52%   |
| Samsung M2020 Series                                      | 3        | 1.52%   |
| HP LaserJet Professional P 1102w                          | 3        | 1.52%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 3        | 1.52%   |
| Canon PIXMA MG2500 Series                                 | 3        | 1.52%   |
| Seiko Epson WF-4830 Series                                | 2        | 1.01%   |
| Seiko Epson L355 Series                                   | 2        | 1.01%   |
| Seiko Epson L3110 Series                                  | 2        | 1.01%   |
| Seiko Epson L3050 Series                                  | 2        | 1.01%   |
| Seiko Epson ET-3710 Series                                | 2        | 1.01%   |
| Seiko Epson ET-2700 Series                                | 2        | 1.01%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.01%   |
| QinHeng CH340S                                            | 2        | 1.01%   |
| HP LaserJet M14-M17                                       | 2        | 1.01%   |
| HP ENVY Pro 6400 series                                   | 2        | 1.01%   |
| HP ENVY Photo 6200 series                                 | 2        | 1.01%   |
| HP ENVY 4500 series                                       | 2        | 1.01%   |
| HP DeskJet F4100 Printer series                           | 2        | 1.01%   |
| HP Deskjet F2280 series                                   | 2        | 1.01%   |
| HP DeskJet 2600 series                                    | 2        | 1.01%   |
| HP Deskjet 1050 J410                                      | 2        | 1.01%   |
| HP Deskjet 1000 J110 series                               | 2        | 1.01%   |
| Fuji Xerox DocuPrint CM315/318 z                          | 2        | 1.01%   |
| Dymo-CoStar LabelWriter 450                               | 2        | 1.01%   |
| Canon PIXMA MX920 Series                                  | 2        | 1.01%   |
| Canon LiDE 400                                            | 2        | 1.01%   |
| Brother HL-L3230CDW series                                | 2        | 1.01%   |
| Brother HL-2270DW Laser Printer                           | 2        | 1.01%   |
| Brother HL-1110 series                                    | 2        | 1.01%   |
| Brother DCP-L2550DW series                                | 2        | 1.01%   |
| Xerox Phaser 6000B                                        | 1        | 0.51%   |
| STMicroelectronics YICHIP3121 Virtual ComPort in FS Mode  | 1        | 0.51%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.51%   |
| Sharp MX-C301W                                            | 1        | 0.51%   |
| Seiko Epson XP-3100 Series                                | 1        | 0.51%   |
| Seiko Epson XP-240 Series                                 | 1        | 0.51%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 45.83%  |
| Seiko Epson     | 8        | 33.33%  |
| Hewlett-Packard | 4        | 16.67%  |
| Mustek Systems  | 1        | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson Perfection V37/V370                         | 2        | 8.33%   |
| Canon CanoScan N1240U/LiDE 30                           | 2        | 8.33%   |
| Canon CanoScan LiDE 210                                 | 2        | 8.33%   |
| Seiko Epson Scanner                                     | 1        | 4.17%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1        | 4.17%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1        | 4.17%   |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1        | 4.17%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 4.17%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1        | 4.17%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 4.17%   |
| HP Scanjet G2710                                        | 1        | 4.17%   |
| HP ScanJet 82x0C                                        | 1        | 4.17%   |
| HP ScanJet 2400c                                        | 1        | 4.17%   |
| HP HP Scanjet 300                                       | 1        | 4.17%   |
| Canon CanoScan N650U/N656U                              | 1        | 4.17%   |
| Canon CanoScan LiDE 60                                  | 1        | 4.17%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1        | 4.17%   |
| Canon CanoScan LiDE 220                                 | 1        | 4.17%   |
| Canon CanoScan LiDE 200                                 | 1        | 4.17%   |
| Canon CanoScan LiDE 110                                 | 1        | 4.17%   |
| Canon CanoScan 9000F Mark II                            | 1        | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 437      | 41.78%  |
| Microdia                      | 101      | 9.66%   |
| Microsoft                     | 51       | 4.88%   |
| Sunplus Innovation Technology | 44       | 4.21%   |
| Apple                         | 35       | 3.35%   |
| Generalplus Technology        | 28       | 2.68%   |
| Razer USA                     | 24       | 2.29%   |
| Samsung Electronics           | 21       | 2.01%   |
| Valve Software                | 18       | 1.72%   |
| Realtek Semiconductor         | 18       | 1.72%   |
| MacroSilicon                  | 16       | 1.53%   |
| ARC International             | 16       | 1.53%   |
| Creative Technology           | 15       | 1.43%   |
| Chicony Electronics           | 15       | 1.43%   |
| Jieli Technology              | 14       | 1.34%   |
| Z-Star Microelectronics       | 12       | 1.15%   |
| KYE Systems (Mouse Systems)   | 10       | 0.96%   |
| Hewlett-Packard               | 9        | 0.86%   |
| Trust                         | 8        | 0.76%   |
| eMeet                         | 8        | 0.76%   |
| Cubeternet                    | 7        | 0.67%   |
| AVerMedia Technologies        | 7        | 0.67%   |
| Anker PowerConf C200          | 7        | 0.67%   |
| webcam                        | 6        | 0.57%   |
| YGTek                         | 5        | 0.48%   |
| LG Electronics                | 5        | 0.48%   |
| Huawei Technologies           | 5        | 0.48%   |
| Aveo Technology               | 5        | 0.48%   |
| ValueHD                       | 4        | 0.38%   |
| Unknown                       | 3        | 0.29%   |
| SunplusIT                     | 3        | 0.29%   |
| Sunplus IT                    | 3        | 0.29%   |
| Linux Foundation              | 3        | 0.29%   |
| Lenovo                        | 3        | 0.29%   |
| Alcor Micro                   | 3        | 0.29%   |
| A4Tech                        | 3        | 0.29%   |
| WCM_USB                       | 2        | 0.19%   |
| WaveRider Communications      | 2        | 0.19%   |
| SN0002                        | 2        | 0.19%   |
| SiGma Micro                   | 2        | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920               | 91       | 8.65%   |
| Logitech Webcam C270                      | 79       | 7.51%   |
| Logitech C922 Pro Stream Webcam           | 42       | 3.99%   |
| Microdia Webcam Vitade AF                 | 36       | 3.42%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 34       | 3.23%   |
| Logitech BRIO Ultra HD Webcam             | 25       | 2.38%   |
| Logitech C920 PRO HD Webcam               | 23       | 2.19%   |
| Samsung Galaxy series, misc. (MTP mode)   | 21       | 2%      |
| Generalplus GENERAL WEBCAM                | 21       | 2%      |
| Microsoft LifeCam HD-3000                 | 20       | 1.9%    |
| Valve Software 3D Camera                  | 18       | 1.71%   |
| Microdia USB 2.0 Camera                   | 18       | 1.71%   |
| Logitech HD Webcam C615                   | 18       | 1.71%   |
| Logitech HD Webcam C525                   | 18       | 1.71%   |
| Razer USA Gaming Webcam [Kiyo]            | 17       | 1.62%   |
| ARC International Camera                  | 16       | 1.52%   |
| Sunplus Full HD webcam                    | 14       | 1.33%   |
| Logitech Logitech Webcam C925e            | 14       | 1.33%   |
| Logitech StreamCam                        | 13       | 1.24%   |
| Jieli USB PHY 2.0                         | 13       | 1.24%   |
| MacroSilicon USB Video                    | 12       | 1.14%   |
| Microdia Integrated Camera                | 11       | 1.05%   |
| Logitech Webcam C310                      | 11       | 1.05%   |
| Logitech Webcam C170                      | 11       | 1.05%   |
| Microsoft LifeCam Cinema                  | 10       | 0.95%   |
| Logitech Webcam Pro 9000                  | 10       | 0.95%   |
| Logitech Webcam C930e                     | 10       | 0.95%   |
| Microdia CyberTrack H7                    | 8        | 0.76%   |
| Logitech HD Webcam C910                   | 8        | 0.76%   |
| Sunplus Integrated Camera                 | 7        | 0.67%   |
| Microdia Camera                           | 7        | 0.67%   |
| Logitech BRIO 4K Stream Edition           | 7        | 0.67%   |
| Chicony HP High Definition 1MP Webcam     | 7        | 0.67%   |
| Anker PowerConf C200 Anker PowerConf C200 | 7        | 0.67%   |
| webcam webcam                             | 6        | 0.57%   |
| Microsoft LifeCam Studio                  | 6        | 0.57%   |
| AVerMedia Live Streamer CAM 313           | 6        | 0.57%   |
| YGTek Webcam                              | 5        | 0.48%   |
| Sunplus USB 2.0 Camera                    | 5        | 0.48%   |
| Logitech HD Webcam C510                   | 5        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Synaptics                  | 2        | 18.18%  |
| Elan Microelectronics      | 2        | 18.18%  |
| DigitalPersona             | 2        | 18.18%  |
| Validity Sensors           | 1        | 9.09%   |
| Upek                       | 1        | 9.09%   |
| Shenzhen Goodix Technology | 1        | 9.09%   |
| LighTuning Technology      | 1        | 9.09%   |
| AuthenTec                  | 1        | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2        | 18.18%  |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 2        | 18.18%  |
| DigitalPersona Fingerprint Reader                           | 2        | 18.18%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 1        | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                         | 1        | 9.09%   |
| LighTuning Fingerprint Sensor                               | 1        | 9.09%   |
| AuthenTec Fingerprint Sensor                                | 1        | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| SCM Microsystems          | 8        | 32%     |
| Alcor Micro               | 5        | 20%     |
| Realtek Semiconductor     | 3        | 12%     |
| OmniKey                   | 3        | 12%     |
| Chicony Electronics       | 2        | 8%      |
| Yubico.com                | 1        | 4%      |
| Jing-Mold Enterprise      | 1        | 4%      |
| Aladdin Knowledge Systems | 1        | 4%      |
| Advanced Card Systems     | 1        | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 5        | 20%     |
| Realtek Semiconductor Smart Card Reader Interface                 | 3        | 12%     |
| Alcor Micro AU9540 Smartcard Reader                               | 3        | 12%     |
| OmniKey CardMan 3021 / 3121                                       | 2        | 8%      |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 2        | 8%      |
| Alcor Micro Watchdata W 1981                                      | 2        | 8%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                   | 1        | 4%      |
| SCM Microsystems SCR3500 C Contact Reader                         | 1        | 4%      |
| SCM Microsystems SCR3500 A Contact Reader                         | 1        | 4%      |
| SCM Microsystems SCR331 SmartCard Reader                          | 1        | 4%      |
| OmniKey CardMan 1021                                              | 1        | 4%      |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 4%      |
| Aladdin Knowledge Systems Token JC                                | 1        | 4%      |
| Advanced Card Systems ACR1252 Dual Reader                         | 1        | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4346     | 81.1%   |
| 1     | 906      | 16.91%  |
| 2     | 87       | 1.62%   |
| 3     | 14       | 0.26%   |
| 5     | 4        | 0.07%   |
| 7     | 1        | 0.02%   |
| 4     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 384      | 34.69%  |
| Net/wireless             | 379      | 34.24%  |
| Unassigned class         | 83       | 7.5%    |
| Sound                    | 34       | 3.07%   |
| Multimedia controller    | 33       | 2.98%   |
| Bluetooth                | 31       | 2.8%    |
| Network                  | 30       | 2.71%   |
| Storage/raid             | 29       | 2.62%   |
| Communication controller | 29       | 2.62%   |
| Net/ethernet             | 18       | 1.63%   |
| Chipcard                 | 18       | 1.63%   |
| Camera                   | 11       | 0.99%   |
| Fingerprint reader       | 10       | 0.9%    |
| Card reader              | 5        | 0.45%   |
| Storage/nvme             | 4        | 0.36%   |
| Storage/ide              | 4        | 0.36%   |
| Firewire controller      | 2        | 0.18%   |
| Tv card                  | 1        | 0.09%   |
| Modem                    | 1        | 0.09%   |
| Dvb card                 | 1        | 0.09%   |

