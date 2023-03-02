Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 3657

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 08NPPY A00                  | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| MSI           | 970A-G43                    | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| HP            | 8053                        | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | 0T568R A00                  | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASRock        | B460M-HDV                   | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Gigabyte      | Z87N-WIFI                   | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| HP            | 805A                        | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | GD30CI                      | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Shuttle       | FS61                        | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Intel         | DG35EC AAE29266-205         | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| Lenovo        | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASUSTek       | B85M-E/BR                   | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Dell          | 0PU052                      | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| Dell          | 04YP6J A02                  | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| Dell          | 0TTDMJ A00                  | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| ASRock        | X670E Pro RS                | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Dell          | 0GY6Y8 A02                  | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HP            | 8053                        | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| ASRock        | X670E Taichi                | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Gigabyte      | B460M AORUS PRO             | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Gigabyte      | H510M H                     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| ZOTAC         | ION                         | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| MSI           | B250 GAMING M3              | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [0973466d88](https://linux-hardware.org/?probe=0973466d88) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [9d2ef8adf1](https://linux-hardware.org/?probe=9d2ef8adf1) | Dec 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [e843a9c61d](https://linux-hardware.org/?probe=e843a9c61d) | Dec 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| Gigabyte      | B550M S2H                   | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d6666dccec](https://linux-hardware.org/?probe=d6666dccec) | Dec 08, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c6895362e6](https://linux-hardware.org/?probe=c6895362e6) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [037c8e9cbc](https://linux-hardware.org/?probe=037c8e9cbc) | Dec 06, 2022 |
| Gigabyte      | F2A58M-HD2                  | [61c23e2501](https://linux-hardware.org/?probe=61c23e2501) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ddd1487d81](https://linux-hardware.org/?probe=ddd1487d81) | Dec 05, 2022 |
| HP            | 8053                        | [5fad592ef3](https://linux-hardware.org/?probe=5fad592ef3) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b3b5eb90e5](https://linux-hardware.org/?probe=b3b5eb90e5) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Dell          | 09WH54 A00                  | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| HP            | 3397                        | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Gigabyte      | B550M S2H                   | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| ASRock        | B550M Pro4                  | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| ASRock        | X300M-STX                   | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASRock        | B550M Pro4                  | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| ASRock        | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| ASUSTek       | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | 8460                        | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| ASUSTek       | P6X58-E-WS                  | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Dell          | 0NW73C A00                  | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 87D6 SMVB                   | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Dell          | 0HN7XN A00                  | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| Huanan        | X99-TF                      | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| HP            | 212B                        | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X99-DELUXE II               | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| Foxconn       | 2ADA                        | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Intel         | Unknown                     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| ASRock        | B550M Pro4                  | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| ASRock        | X99 WS                      | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | B550M S2H                   | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| ASUSTek       | PRIME B365M-C               | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | 82A2                        | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| ASRock        | 990FX Extreme3              | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| HP            | 8053                        | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| Unknown       | Unknown                     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| ECS           | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | 0D24M8 A00                  | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Gigabyte      | H97-Gaming 3                | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| ASRock        | B550M Pro4                  | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| BESSTAR Te... | UM350                       | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| ASUSTek       | PRIME Z390-P                | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [be4dd3360f](https://linux-hardware.org/?probe=be4dd3360f) | Jun 28, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [0441b2cf28](https://linux-hardware.org/?probe=0441b2cf28) | Jun 27, 2022 |
| HP            | 212B                        | [687ca162d2](https://linux-hardware.org/?probe=687ca162d2) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [ca055793c5](https://linux-hardware.org/?probe=ca055793c5) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-K               | [441cba3212](https://linux-hardware.org/?probe=441cba3212) | Jun 27, 2022 |
| Gigabyte      | H370M DS3H-CF               | [862d58f1a4](https://linux-hardware.org/?probe=862d58f1a4) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [da1c9472bd](https://linux-hardware.org/?probe=da1c9472bd) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [0e8993f232](https://linux-hardware.org/?probe=0e8993f232) | Jun 27, 2022 |
| ASRock        | B550M Pro4                  | [92d424a6b5](https://linux-hardware.org/?probe=92d424a6b5) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [4fd5881226](https://linux-hardware.org/?probe=4fd5881226) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [01e2541b47](https://linux-hardware.org/?probe=01e2541b47) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [6b2aa6c257](https://linux-hardware.org/?probe=6b2aa6c257) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [dae78cdc9e](https://linux-hardware.org/?probe=dae78cdc9e) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [b397f63621](https://linux-hardware.org/?probe=b397f63621) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| ASRock        | B450M Pro4 R2.0             | [f1e0998426](https://linux-hardware.org/?probe=f1e0998426) | Jun 25, 2022 |
| ASRock        | B450M Pro4 R2.0             | [abdb925c2a](https://linux-hardware.org/?probe=abdb925c2a) | Jun 24, 2022 |
| Gigabyte      | MQLP5AP-00                  | [fad6b4b320](https://linux-hardware.org/?probe=fad6b4b320) | Jun 24, 2022 |
| Gigabyte      | B450M S2H V2                | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| ECS           | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7063b6a7ef](https://linux-hardware.org/?probe=7063b6a7ef) | Jun 21, 2022 |
| ASRock        | B550M Pro4                  | [ab46a92e42](https://linux-hardware.org/?probe=ab46a92e42) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d908e7db](https://linux-hardware.org/?probe=75d908e7db) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Gigabyte      | B450 AORUS M                | [8b1fb7056f](https://linux-hardware.org/?probe=8b1fb7056f) | Jun 17, 2022 |
| Gigabyte      | B450 AORUS M                | [277df992e4](https://linux-hardware.org/?probe=277df992e4) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| ASRock        | AB350M-HDV                  | [65478d1857](https://linux-hardware.org/?probe=65478d1857) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [b9de371265](https://linux-hardware.org/?probe=b9de371265) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [d987e4522e](https://linux-hardware.org/?probe=d987e4522e) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a8163d07f](https://linux-hardware.org/?probe=4a8163d07f) | Jun 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Unknown       | Unknown                     | [87eb57392c](https://linux-hardware.org/?probe=87eb57392c) | Jun 16, 2022 |
| MSI           | B360M PRO-VD                | [fa86b2da10](https://linux-hardware.org/?probe=fa86b2da10) | Jun 15, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASRock        | B550M Pro4                  | [4dc0746a65](https://linux-hardware.org/?probe=4dc0746a65) | Jun 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7587cca95a](https://linux-hardware.org/?probe=7587cca95a) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d0050d4fcd](https://linux-hardware.org/?probe=d0050d4fcd) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| ASRock        | B550M Pro4                  | [5c9ca9542b](https://linux-hardware.org/?probe=5c9ca9542b) | Jun 13, 2022 |
| HP            | 212B                        | [2680c53ca7](https://linux-hardware.org/?probe=2680c53ca7) | Jun 13, 2022 |
| ASRock        | B550M Pro4                  | [275c522503](https://linux-hardware.org/?probe=275c522503) | Jun 13, 2022 |
| Unknown       | 1.0                         | [8c8f612260](https://linux-hardware.org/?probe=8c8f612260) | Jun 13, 2022 |
| Huanan        | X99-TF V2.0                 | [cf8091c979](https://linux-hardware.org/?probe=cf8091c979) | Jun 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [feca5f6bb5](https://linux-hardware.org/?probe=feca5f6bb5) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| HP            | 0A9Ch                       | [bd8345d324](https://linux-hardware.org/?probe=bd8345d324) | Jun 12, 2022 |
| Gigabyte      | H510M H                     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| Gigabyte      | Z68P-DS3                    | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Gigabyte      | B550M DS3H                  | [32415f8bd1](https://linux-hardware.org/?probe=32415f8bd1) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0dd5653fc1](https://linux-hardware.org/?probe=0dd5653fc1) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1b4307a298](https://linux-hardware.org/?probe=1b4307a298) | Jun 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | 1998                        | [fd5184fe12](https://linux-hardware.org/?probe=fd5184fe12) | Jun 08, 2022 |
| ASRock        | B550M Pro4                  | [10fbde5027](https://linux-hardware.org/?probe=10fbde5027) | Jun 07, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [25213ed098](https://linux-hardware.org/?probe=25213ed098) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| MSI           | B350M PRO-VDH               | [ae45bf67a3](https://linux-hardware.org/?probe=ae45bf67a3) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| BESSTAR Te... | UM700                       | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [829ee446bd](https://linux-hardware.org/?probe=829ee446bd) | Jun 02, 2022 |
| MSI           | B350 TOMAHAWK               | [b9cdc775ea](https://linux-hardware.org/?probe=b9cdc775ea) | Jun 02, 2022 |
| ASRock        | B550M Pro4                  | [9ac2f5ba04](https://linux-hardware.org/?probe=9ac2f5ba04) | Jun 01, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| MSI           | B250M PRO-VDH               | [eede963720](https://linux-hardware.org/?probe=eede963720) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | [e2dd690b16](https://linux-hardware.org/?probe=e2dd690b16) | May 31, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| ASRock        | B550M Pro4                  | [a5eee874a5](https://linux-hardware.org/?probe=a5eee874a5) | May 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0050247c85](https://linux-hardware.org/?probe=0050247c85) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| Google        | Guado                       | [d026c0565d](https://linux-hardware.org/?probe=d026c0565d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [4e2d37a90d](https://linux-hardware.org/?probe=4e2d37a90d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [b861a73ade](https://linux-hardware.org/?probe=b861a73ade) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c3d1916e14](https://linux-hardware.org/?probe=c3d1916e14) | May 28, 2022 |
| Gigabyte      | MCMLUCB-00                  | [90c886e471](https://linux-hardware.org/?probe=90c886e471) | May 27, 2022 |
| Dell          | 0KP561                      | [2435960bba](https://linux-hardware.org/?probe=2435960bba) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bf3f9d0ed3](https://linux-hardware.org/?probe=bf3f9d0ed3) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [c8f47b62d2](https://linux-hardware.org/?probe=c8f47b62d2) | May 26, 2022 |
| ASRock        | B550M Pro4                  | [d5df82a4ce](https://linux-hardware.org/?probe=d5df82a4ce) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | [c11c9ac073](https://linux-hardware.org/?probe=c11c9ac073) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0390e0a7c2](https://linux-hardware.org/?probe=0390e0a7c2) | May 25, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| ASRock        | B550M Pro4                  | [35ba2b5a7a](https://linux-hardware.org/?probe=35ba2b5a7a) | May 24, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [7375e6d7ec](https://linux-hardware.org/?probe=7375e6d7ec) | May 24, 2022 |
| Unknown       | Unknown                     | [62b61f57ef](https://linux-hardware.org/?probe=62b61f57ef) | May 24, 2022 |
| Gigabyte      | Z77M-D3H                    | [b7369242f9](https://linux-hardware.org/?probe=b7369242f9) | May 23, 2022 |
| Google        | Guado                       | [3245615e95](https://linux-hardware.org/?probe=3245615e95) | May 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [de3cd5c495](https://linux-hardware.org/?probe=de3cd5c495) | May 23, 2022 |
| ASRock        | Z77 Extreme4                | [198a8b039a](https://linux-hardware.org/?probe=198a8b039a) | May 22, 2022 |
| ASRock        | Z77 Extreme4                | [3c45f702eb](https://linux-hardware.org/?probe=3c45f702eb) | May 22, 2022 |
| MSI           | H97M-G43                    | [3869b1146e](https://linux-hardware.org/?probe=3869b1146e) | May 22, 2022 |
| ASRock        | B550M Pro4                  | [85974104c5](https://linux-hardware.org/?probe=85974104c5) | May 21, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [4dce3bdb3a](https://linux-hardware.org/?probe=4dce3bdb3a) | May 21, 2022 |
| Chatreey      | AC1-DP                      | [aefe90ce82](https://linux-hardware.org/?probe=aefe90ce82) | May 20, 2022 |
| HP            | 212B                        | [a52da35d02](https://linux-hardware.org/?probe=a52da35d02) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bcb2dd930d](https://linux-hardware.org/?probe=bcb2dd930d) | May 19, 2022 |
| HP            | 8053                        | [67ea3799ad](https://linux-hardware.org/?probe=67ea3799ad) | May 18, 2022 |
| MSI           | X99S GAMING 7               | [ff6fe109c0](https://linux-hardware.org/?probe=ff6fe109c0) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [0e0b2d38d8](https://linux-hardware.org/?probe=0e0b2d38d8) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [a80d230e6e](https://linux-hardware.org/?probe=a80d230e6e) | May 17, 2022 |
| ASRock        | B550M Pro4                  | [acd5c94fc8](https://linux-hardware.org/?probe=acd5c94fc8) | May 16, 2022 |
| HP            | 3031h                       | [9a6723ea52](https://linux-hardware.org/?probe=9a6723ea52) | May 16, 2022 |
| HP            | 3031h                       | [414614ec5d](https://linux-hardware.org/?probe=414614ec5d) | May 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| Gigabyte      | MCMLUCB-00                  | [1ad57be6ad](https://linux-hardware.org/?probe=1ad57be6ad) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| HP            | 8053                        | [35d3caac96](https://linux-hardware.org/?probe=35d3caac96) | May 16, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [178d910ec8](https://linux-hardware.org/?probe=178d910ec8) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| ASRock        | B550M Pro4                  | [289c04b1dd](https://linux-hardware.org/?probe=289c04b1dd) | May 14, 2022 |
| Dell          | 0C27VV A01                  | [bf0f5c5d07](https://linux-hardware.org/?probe=bf0f5c5d07) | May 14, 2022 |
| ASRock        | X570 Taichi                 | [4d3e26ea12](https://linux-hardware.org/?probe=4d3e26ea12) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| ASUSTek       | Acacia                      | [4b633150fa](https://linux-hardware.org/?probe=4b633150fa) | May 14, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [7a7065c273](https://linux-hardware.org/?probe=7a7065c273) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| ASRock        | B550M Pro4                  | [9f9e071e39](https://linux-hardware.org/?probe=9f9e071e39) | May 12, 2022 |
| ASRock        | B550M Pro4                  | [fad48ff5dd](https://linux-hardware.org/?probe=fad48ff5dd) | May 12, 2022 |
| ASUSTek       | P8P67 DELUXE                | [4293bc4b1c](https://linux-hardware.org/?probe=4293bc4b1c) | May 12, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 GAMING X V2            | [326b50009b](https://linux-hardware.org/?probe=326b50009b) | May 12, 2022 |
| ASUSTek       | PRIME X570-PRO              | [23b8b07484](https://linux-hardware.org/?probe=23b8b07484) | May 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fa341f81f](https://linux-hardware.org/?probe=3fa341f81f) | May 11, 2022 |
| Gigabyte      | H97M-HD3                    | [5b0d379b54](https://linux-hardware.org/?probe=5b0d379b54) | May 11, 2022 |
| HP            | 1905                        | [91a5807da1](https://linux-hardware.org/?probe=91a5807da1) | May 10, 2022 |
| HP            | 1905                        | [40dbe34df3](https://linux-hardware.org/?probe=40dbe34df3) | May 10, 2022 |
| MSI           | Z170A GAMING M5             | [766ec913a6](https://linux-hardware.org/?probe=766ec913a6) | May 09, 2022 |
| BESSTAR Te... | UM350                       | [c5234552de](https://linux-hardware.org/?probe=c5234552de) | May 09, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1906da1cb4](https://linux-hardware.org/?probe=1906da1cb4) | May 08, 2022 |
| Intel         | X79M-S                      | [770b00ef16](https://linux-hardware.org/?probe=770b00ef16) | May 08, 2022 |
| ASRock        | B550M Steel Legend          | [a384972a7a](https://linux-hardware.org/?probe=a384972a7a) | May 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Pegatron      | NARRA5                      | [bfe1e3f80d](https://linux-hardware.org/?probe=bfe1e3f80d) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |
| ASRock        | X370 Taichi                 | [256b60b267](https://linux-hardware.org/?probe=256b60b267) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| ASRock        | H470M-HDV                   | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| MSI           | MEG Z590 GODLIKE            | [0b88e8e449](https://linux-hardware.org/?probe=0b88e8e449) | May 06, 2022 |
| ASRock        | AB350 Pro4                  | [2ce796a070](https://linux-hardware.org/?probe=2ce796a070) | May 05, 2022 |
| MSI           | MEG Z590 GODLIKE            | [ce253bc962](https://linux-hardware.org/?probe=ce253bc962) | May 05, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3a3a4e634d](https://linux-hardware.org/?probe=3a3a4e634d) | May 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9a2b895663](https://linux-hardware.org/?probe=9a2b895663) | May 04, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [0a2ba1d529](https://linux-hardware.org/?probe=0a2ba1d529) | May 04, 2022 |
| ASUSTek       | P8Z77-V LX                  | [97185f1809](https://linux-hardware.org/?probe=97185f1809) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [473e906b63](https://linux-hardware.org/?probe=473e906b63) | May 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9176b48887](https://linux-hardware.org/?probe=9176b48887) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2089066a7d](https://linux-hardware.org/?probe=2089066a7d) | May 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [edc5f16866](https://linux-hardware.org/?probe=edc5f16866) | May 03, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [26aa108efd](https://linux-hardware.org/?probe=26aa108efd) | May 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | [142c1f1a2f](https://linux-hardware.org/?probe=142c1f1a2f) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [1fea9af929](https://linux-hardware.org/?probe=1fea9af929) | May 03, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [d49d0283d4](https://linux-hardware.org/?probe=d49d0283d4) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| Gigabyte      | A520M H                     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| MSI           | B450 GAMING PLUS            | [a792e309de](https://linux-hardware.org/?probe=a792e309de) | May 02, 2022 |
| ASRock        | B550AM Gaming               | [e31ad2a03f](https://linux-hardware.org/?probe=e31ad2a03f) | May 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [45a9821bc8](https://linux-hardware.org/?probe=45a9821bc8) | May 02, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a19c88dc27](https://linux-hardware.org/?probe=a19c88dc27) | May 02, 2022 |
| MSI           | Z77A-G43                    | [2c6195f0b8](https://linux-hardware.org/?probe=2c6195f0b8) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | PRIME B350M-A               | [87542ba2c2](https://linux-hardware.org/?probe=87542ba2c2) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [da04f72dfc](https://linux-hardware.org/?probe=da04f72dfc) | Apr 30, 2022 |
| ASRock        | Z370 Gaming K6              | [63d2d272b6](https://linux-hardware.org/?probe=63d2d272b6) | Apr 30, 2022 |
| MSI           | MEG Z590 GODLIKE            | [d0ca0e52ad](https://linux-hardware.org/?probe=d0ca0e52ad) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [29e1e28903](https://linux-hardware.org/?probe=29e1e28903) | Apr 28, 2022 |
| MSI           | MEG Z590 GODLIKE            | [a2f86e2fea](https://linux-hardware.org/?probe=a2f86e2fea) | Apr 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6f7b2f6a78](https://linux-hardware.org/?probe=6f7b2f6a78) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | [31f358fdd0](https://linux-hardware.org/?probe=31f358fdd0) | Apr 28, 2022 |
| Gigabyte      | X570 UD                     | [67f24b974b](https://linux-hardware.org/?probe=67f24b974b) | Apr 27, 2022 |
| ASRock        | AB350M-HDV                  | [6ee4ea44a8](https://linux-hardware.org/?probe=6ee4ea44a8) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [7c7b023841](https://linux-hardware.org/?probe=7c7b023841) | Apr 27, 2022 |
| Dell          | 00V62H A01                  | [eddac3b03f](https://linux-hardware.org/?probe=eddac3b03f) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | [003eab04ae](https://linux-hardware.org/?probe=003eab04ae) | Apr 26, 2022 |
| MSI           | MEG X570 UNIFY              | [4f7c3fc75d](https://linux-hardware.org/?probe=4f7c3fc75d) | Apr 26, 2022 |
| AZW           | U59                         | [ecee060925](https://linux-hardware.org/?probe=ecee060925) | Apr 26, 2022 |
| Gigabyte      | Z590 D                      | [afad17a56d](https://linux-hardware.org/?probe=afad17a56d) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [6bee5ac8c6](https://linux-hardware.org/?probe=6bee5ac8c6) | Apr 26, 2022 |
| ASUSTek       | PRIME X570-P                | [a304ccdfb1](https://linux-hardware.org/?probe=a304ccdfb1) | Apr 26, 2022 |
| Alienware     | 02XRCM A01                  | [90cc83b1aa](https://linux-hardware.org/?probe=90cc83b1aa) | Apr 26, 2022 |
| ASRock        | H97 Pro4                    | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Dell          | 042P49 A02                  | [cc2266d5aa](https://linux-hardware.org/?probe=cc2266d5aa) | Apr 25, 2022 |
| MSI           | MEG B550 UNIFY              | [3cf3319591](https://linux-hardware.org/?probe=3cf3319591) | Apr 25, 2022 |
| Dell          | 0KP561                      | [0467bf679e](https://linux-hardware.org/?probe=0467bf679e) | Apr 25, 2022 |
| ASRock        | H110 Pro BTC+               | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [81f1c06851](https://linux-hardware.org/?probe=81f1c06851) | Apr 23, 2022 |
| Alienware     | 07HV66 A00                  | [7b889c5010](https://linux-hardware.org/?probe=7b889c5010) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [afcef911ce](https://linux-hardware.org/?probe=afcef911ce) | Apr 23, 2022 |
| ASRock        | AB350M Pro4                 | [544c5dbbf7](https://linux-hardware.org/?probe=544c5dbbf7) | Apr 22, 2022 |
| ASUSTek       | H81M-K                      | [95a2757020](https://linux-hardware.org/?probe=95a2757020) | Apr 22, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME A320M-K               | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| Gigabyte      | B450 AORUS M                | [ff11434d18](https://linux-hardware.org/?probe=ff11434d18) | Apr 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [34c876e7e6](https://linux-hardware.org/?probe=34c876e7e6) | Apr 19, 2022 |
| Dell          | 0C522T A00                  | [8684c390a7](https://linux-hardware.org/?probe=8684c390a7) | Apr 19, 2022 |
| Dell          | 09M8Y8 A01                  | [8b989c82a2](https://linux-hardware.org/?probe=8b989c82a2) | Apr 18, 2022 |
| Dell          | 09M8Y8 A01                  | [fff624b795](https://linux-hardware.org/?probe=fff624b795) | Apr 18, 2022 |
| ECS           | H61H2-M13                   | [f3d574e81e](https://linux-hardware.org/?probe=f3d574e81e) | Apr 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ff70aec1ae](https://linux-hardware.org/?probe=ff70aec1ae) | Apr 18, 2022 |
| Foxconn       | 2ABF                        | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| MSI           | B350M PRO-VDH               | [884f15c1df](https://linux-hardware.org/?probe=884f15c1df) | Apr 17, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [271eb8380b](https://linux-hardware.org/?probe=271eb8380b) | Apr 17, 2022 |
| Lenovo        | 3714 NOK                    | [80ed454cc3](https://linux-hardware.org/?probe=80ed454cc3) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| MSI           | MAG B460M MORTAR            | [278ccbaf44](https://linux-hardware.org/?probe=278ccbaf44) | Apr 17, 2022 |
| MSI           | MS-7438 100                 | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [3e3e2fd22f](https://linux-hardware.org/?probe=3e3e2fd22f) | Apr 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [4702e93a67](https://linux-hardware.org/?probe=4702e93a67) | Apr 16, 2022 |
| ASUSTek       | GRYPHON Z87                 | [557390f9cf](https://linux-hardware.org/?probe=557390f9cf) | Apr 15, 2022 |
| Dell          | 0C522T A00                  | [593941cc0a](https://linux-hardware.org/?probe=593941cc0a) | Apr 15, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [bd378877e0](https://linux-hardware.org/?probe=bd378877e0) | Apr 14, 2022 |
| ASRock        | B550M Pro4                  | [e1b00199f8](https://linux-hardware.org/?probe=e1b00199f8) | Apr 14, 2022 |
| ASRock        | AB350 Pro4                  | [137e25f240](https://linux-hardware.org/?probe=137e25f240) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| ASRock        | AB350M                      | [f79bfabcf5](https://linux-hardware.org/?probe=f79bfabcf5) | Apr 14, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5d45d7b3f7](https://linux-hardware.org/?probe=5d45d7b3f7) | Apr 13, 2022 |
| ASRock        | X570M Pro4                  | [b7373e1f8f](https://linux-hardware.org/?probe=b7373e1f8f) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| Dell          | 03V3TG A00                  | [a91e96515c](https://linux-hardware.org/?probe=a91e96515c) | Apr 13, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| HP            | 18E4                        | [83cf0afd92](https://linux-hardware.org/?probe=83cf0afd92) | Apr 13, 2022 |
| HP            | 18E4                        | [61a163f744](https://linux-hardware.org/?probe=61a163f744) | Apr 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [81ef10ca5d](https://linux-hardware.org/?probe=81ef10ca5d) | Apr 13, 2022 |
| Gigabyte      | 970A-DS3P                   | [8101ed4e60](https://linux-hardware.org/?probe=8101ed4e60) | Apr 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [bf61a75cfd](https://linux-hardware.org/?probe=bf61a75cfd) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| ASRock        | B250M Performance           | [3d9af3df5a](https://linux-hardware.org/?probe=3d9af3df5a) | Apr 11, 2022 |
| MSI           | 760GM-P34                   | [c346a58754](https://linux-hardware.org/?probe=c346a58754) | Apr 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [1a475ba1e6](https://linux-hardware.org/?probe=1a475ba1e6) | Apr 11, 2022 |
| HP            | 1998                        | [28dcd611cc](https://linux-hardware.org/?probe=28dcd611cc) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| Gigabyte      | H61M-S2PV                   | [8760e3254a](https://linux-hardware.org/?probe=8760e3254a) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [885cbd9d0c](https://linux-hardware.org/?probe=885cbd9d0c) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [645fb7bb30](https://linux-hardware.org/?probe=645fb7bb30) | Apr 09, 2022 |
| ASUSTek       | Z87-K                       | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASRock        | Z77 Pro4                    | [38eeb648af](https://linux-hardware.org/?probe=38eeb648af) | Apr 09, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [a618981311](https://linux-hardware.org/?probe=a618981311) | Apr 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [2db23c062e](https://linux-hardware.org/?probe=2db23c062e) | Apr 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [94f4873110](https://linux-hardware.org/?probe=94f4873110) | Apr 06, 2022 |
| MSI           | Z370-A PRO                  | [c4f0f0573c](https://linux-hardware.org/?probe=c4f0f0573c) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| Dell          | 0D24M8 A00                  | [4f81a4a54a](https://linux-hardware.org/?probe=4f81a4a54a) | Apr 06, 2022 |
| ASUSTek       | A8N-VM CSM                  | [eac824e348](https://linux-hardware.org/?probe=eac824e348) | Apr 06, 2022 |
| Biostar       | TB250-BTC                   | [d6ef15453d](https://linux-hardware.org/?probe=d6ef15453d) | Apr 05, 2022 |
| ASUSTek       | Z97-A-USB31                 | [cd6f73403e](https://linux-hardware.org/?probe=cd6f73403e) | Apr 05, 2022 |
| ASRock        | B450 Pro4                   | [47ff657a18](https://linux-hardware.org/?probe=47ff657a18) | Apr 04, 2022 |
| Dell          | 0C522T A00                  | [4a42777634](https://linux-hardware.org/?probe=4a42777634) | Apr 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5348103896](https://linux-hardware.org/?probe=5348103896) | Apr 03, 2022 |
| Intel         | DH67BL AAG10189-207         | [2daa6a85f4](https://linux-hardware.org/?probe=2daa6a85f4) | Apr 03, 2022 |
| MSI           | X470 GAMING PLUS            | [b7cf273d03](https://linux-hardware.org/?probe=b7cf273d03) | Apr 03, 2022 |
| ASRock        | 960GM-GS3 FX                | [cf80b64dad](https://linux-hardware.org/?probe=cf80b64dad) | Apr 02, 2022 |
| ASRock        | 960GM-GS3 FX                | [50c200ee58](https://linux-hardware.org/?probe=50c200ee58) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [a11d93b9d5](https://linux-hardware.org/?probe=a11d93b9d5) | Apr 02, 2022 |
| Acer          | Aspire TC-120               | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASUSTek       | Z97-A-USB31                 | [6f40a4ebce](https://linux-hardware.org/?probe=6f40a4ebce) | Apr 02, 2022 |
| Dell          | 0N867P A02                  | [aaf4c4cf2b](https://linux-hardware.org/?probe=aaf4c4cf2b) | Apr 01, 2022 |
| ASRock        | Z390 Taichi                 | [b5995c13e5](https://linux-hardware.org/?probe=b5995c13e5) | Mar 31, 2022 |
| ASRock        | Z390 Taichi                 | [308ec93236](https://linux-hardware.org/?probe=308ec93236) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [101c38851b](https://linux-hardware.org/?probe=101c38851b) | Mar 31, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [5f25594023](https://linux-hardware.org/?probe=5f25594023) | Mar 31, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [42e098223b](https://linux-hardware.org/?probe=42e098223b) | Mar 30, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0deba367b9](https://linux-hardware.org/?probe=0deba367b9) | Mar 30, 2022 |
| ASRock        | Z77 Extreme4                | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| Gigabyte      | Z87MX-D3H-CF                | [0401591ebc](https://linux-hardware.org/?probe=0401591ebc) | Mar 29, 2022 |
| HP            | 1998                        | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [a10bdc00e2](https://linux-hardware.org/?probe=a10bdc00e2) | Mar 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0bcee9c78e](https://linux-hardware.org/?probe=0bcee9c78e) | Mar 28, 2022 |
| MSI           | H81M-E34                    | [42ff46ca6c](https://linux-hardware.org/?probe=42ff46ca6c) | Mar 28, 2022 |
| Gigabyte      | M68MT-D3P                   | [8d596570ed](https://linux-hardware.org/?probe=8d596570ed) | Mar 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3ed10cce06](https://linux-hardware.org/?probe=3ed10cce06) | Mar 27, 2022 |
| ASRock        | B550M Pro4                  | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| AMD           | 970A-D3                     | [010b978f01](https://linux-hardware.org/?probe=010b978f01) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | P8H61-M LE/BR               | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| Alienware     | 0R3FWM A00                  | [46a5c111c3](https://linux-hardware.org/?probe=46a5c111c3) | Mar 25, 2022 |
| Gigabyte      | 990XA-UD3                   | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [40ec2200ee](https://linux-hardware.org/?probe=40ec2200ee) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [cb639d5f0a](https://linux-hardware.org/?probe=cb639d5f0a) | Mar 25, 2022 |
| Acer          | Veriton M6660G V:1.0        | [ee5d755daf](https://linux-hardware.org/?probe=ee5d755daf) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [994cca77b2](https://linux-hardware.org/?probe=994cca77b2) | Mar 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [fe7be471b2](https://linux-hardware.org/?probe=fe7be471b2) | Mar 24, 2022 |
| ASRock        | B550 Taichi                 | [2c71d397fd](https://linux-hardware.org/?probe=2c71d397fd) | Mar 24, 2022 |
| Unknown       | Unknown                     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [bb1d6b4aae](https://linux-hardware.org/?probe=bb1d6b4aae) | Mar 24, 2022 |
| Intel         | Unknown                     | [169b017d29](https://linux-hardware.org/?probe=169b017d29) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c5a0300da9](https://linux-hardware.org/?probe=c5a0300da9) | Mar 23, 2022 |
| ASUSTek       | B150I PRO GAMING/AURA       | [0839d5feb0](https://linux-hardware.org/?probe=0839d5feb0) | Mar 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [d24fcefe24](https://linux-hardware.org/?probe=d24fcefe24) | Mar 22, 2022 |
| Acer          | Veriton M6660G V:1.0        | [228974c486](https://linux-hardware.org/?probe=228974c486) | Mar 22, 2022 |
| Dell          | 0K3CM7 A00                  | [8f5ec6c004](https://linux-hardware.org/?probe=8f5ec6c004) | Mar 22, 2022 |
| Apple         | Mac-27AD2F918AE68F61        | [03e06a3a70](https://linux-hardware.org/?probe=03e06a3a70) | Mar 22, 2022 |
| Gigabyte      | G31M-ES2L                   | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Gigabyte      | A320M-H-CF                  | [1462cd20b7](https://linux-hardware.org/?probe=1462cd20b7) | Mar 22, 2022 |
| MSI           | B450M PRO-VDH MAX           | [a6718f483b](https://linux-hardware.org/?probe=a6718f483b) | Mar 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [747e4d92cf](https://linux-hardware.org/?probe=747e4d92cf) | Mar 21, 2022 |
| ASRock        | B550 Extreme4               | [9c194b83e5](https://linux-hardware.org/?probe=9c194b83e5) | Mar 21, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [daa5dd8024](https://linux-hardware.org/?probe=daa5dd8024) | Mar 20, 2022 |
| ASUSTek       | H170 PRO GAMING             | [8ce1eed900](https://linux-hardware.org/?probe=8ce1eed900) | Mar 20, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | [1897912bfc](https://linux-hardware.org/?probe=1897912bfc) | Mar 19, 2022 |
| TPV-INVENT... | 2AF2 A01                    | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| Dell          | 040DDP A01                  | [4cf633a014](https://linux-hardware.org/?probe=4cf633a014) | Mar 18, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [d2378fc2ac](https://linux-hardware.org/?probe=d2378fc2ac) | Mar 18, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [af8d9c8c06](https://linux-hardware.org/?probe=af8d9c8c06) | Mar 18, 2022 |
| ASUSTek       | PRIME B460M-A               | [bb8e459621](https://linux-hardware.org/?probe=bb8e459621) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9ebb2a429f](https://linux-hardware.org/?probe=9ebb2a429f) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b844e23ce9](https://linux-hardware.org/?probe=b844e23ce9) | Mar 17, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| MSI           | B75MA-P45                   | [f617b8e30b](https://linux-hardware.org/?probe=f617b8e30b) | Mar 16, 2022 |
| System76      | Thelio thelio-r2            | [ac96c74ffa](https://linux-hardware.org/?probe=ac96c74ffa) | Mar 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ca405b99d5](https://linux-hardware.org/?probe=ca405b99d5) | Mar 16, 2022 |
| MSI           | MEG X570 UNIFY              | [0927f69114](https://linux-hardware.org/?probe=0927f69114) | Mar 15, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [1b6764fd97](https://linux-hardware.org/?probe=1b6764fd97) | Mar 15, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [a4cc8c4dda](https://linux-hardware.org/?probe=a4cc8c4dda) | Mar 15, 2022 |
| MSI           | MEG X570 UNIFY              | [a4dd59149a](https://linux-hardware.org/?probe=a4dd59149a) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-R               | [4bc060dc9d](https://linux-hardware.org/?probe=4bc060dc9d) | Mar 14, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [e0efdaa76a](https://linux-hardware.org/?probe=e0efdaa76a) | Mar 13, 2022 |
| Gigabyte      | H310M H x.x                 | [0a16c273a4](https://linux-hardware.org/?probe=0a16c273a4) | Mar 13, 2022 |
| ASRock        | H61 Pro BTC                 | [43528c8a20](https://linux-hardware.org/?probe=43528c8a20) | Mar 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [75561646a7](https://linux-hardware.org/?probe=75561646a7) | Mar 13, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [693ec12319](https://linux-hardware.org/?probe=693ec12319) | Mar 12, 2022 |
| MSI           | H81M-P33                    | [138594b67f](https://linux-hardware.org/?probe=138594b67f) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e8c3922bb3](https://linux-hardware.org/?probe=e8c3922bb3) | Mar 12, 2022 |
| MSI           | H81M-E34                    | [8d5b326668](https://linux-hardware.org/?probe=8d5b326668) | Mar 12, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| HP            | 1850                        | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| Gigabyte      | B75M-D3H                    | [30df05cc2f](https://linux-hardware.org/?probe=30df05cc2f) | Mar 11, 2022 |
| HP            | 3396                        | [7bd27c71ed](https://linux-hardware.org/?probe=7bd27c71ed) | Mar 11, 2022 |
| HP            | 3396                        | [adeef3162a](https://linux-hardware.org/?probe=adeef3162a) | Mar 11, 2022 |
| Gigabyte      | H61M-S2PV                   | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| ASRock        | H81M-VG4 R2.0               | [2d72940994](https://linux-hardware.org/?probe=2d72940994) | Mar 10, 2022 |
| Gigabyte      | X570 GAMING X               | [4f7aa0f57c](https://linux-hardware.org/?probe=4f7aa0f57c) | Mar 10, 2022 |
| HP            | 1497                        | [f67b96c14e](https://linux-hardware.org/?probe=f67b96c14e) | Mar 07, 2022 |
| ASRock        | H97 Pro4                    | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | Z68P-DS3                    | [0bb1088899](https://linux-hardware.org/?probe=0bb1088899) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [783c8d9097](https://linux-hardware.org/?probe=783c8d9097) | Mar 06, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [68250a6d74](https://linux-hardware.org/?probe=68250a6d74) | Mar 06, 2022 |
| Dell          | 0YXT71 A03                  | [b1ac4ae8e7](https://linux-hardware.org/?probe=b1ac4ae8e7) | Mar 05, 2022 |
| MSI           | X99A SLI PLUS               | [b56033aa1d](https://linux-hardware.org/?probe=b56033aa1d) | Mar 05, 2022 |
| Gigabyte      | 2AC8                        | [af655fd169](https://linux-hardware.org/?probe=af655fd169) | Mar 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e27cc62b4](https://linux-hardware.org/?probe=8e27cc62b4) | Mar 04, 2022 |
| ASRock        | AB350M Pro4                 | [6ea2fbdb95](https://linux-hardware.org/?probe=6ea2fbdb95) | Mar 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ee8029d2c8](https://linux-hardware.org/?probe=ee8029d2c8) | Mar 03, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [cff135fa1e](https://linux-hardware.org/?probe=cff135fa1e) | Mar 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [eb3d721453](https://linux-hardware.org/?probe=eb3d721453) | Mar 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5f0757c539](https://linux-hardware.org/?probe=5f0757c539) | Mar 02, 2022 |
| ASRock        | Z77 Pro4                    | [ae5611419f](https://linux-hardware.org/?probe=ae5611419f) | Mar 02, 2022 |
| ASRock        | X370 Killer SLI/ac          | [07f8fcde55](https://linux-hardware.org/?probe=07f8fcde55) | Mar 02, 2022 |
| HP            | 18E4                        | [192b302f41](https://linux-hardware.org/?probe=192b302f41) | Feb 27, 2022 |
| ASRock        | H61M-ITX                    | [081ea4e585](https://linux-hardware.org/?probe=081ea4e585) | Feb 26, 2022 |
| AIO           | H61H-G11                    | [137ec871e7](https://linux-hardware.org/?probe=137ec871e7) | Feb 25, 2022 |
| ASUSTek       | PRIME B450M-K               | [6f1958559b](https://linux-hardware.org/?probe=6f1958559b) | Feb 24, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [b6891f77df](https://linux-hardware.org/?probe=b6891f77df) | Feb 24, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f2a6491fc3](https://linux-hardware.org/?probe=f2a6491fc3) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| HP            | 21D0                        | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| Dell          | 00V62H A01                  | [e6564282e5](https://linux-hardware.org/?probe=e6564282e5) | Feb 23, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [2f53cef399](https://linux-hardware.org/?probe=2f53cef399) | Feb 23, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [6d2bec51f3](https://linux-hardware.org/?probe=6d2bec51f3) | Feb 23, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE Ser... | [17aa7b3d5b](https://linux-hardware.org/?probe=17aa7b3d5b) | Feb 23, 2022 |
| Gigabyte      | B460M DS3H                  | [c2ed3df75c](https://linux-hardware.org/?probe=c2ed3df75c) | Feb 23, 2022 |
| MSI           | 880G-E45                    | [e6f9c8c9f6](https://linux-hardware.org/?probe=e6f9c8c9f6) | Feb 23, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [db907dad62](https://linux-hardware.org/?probe=db907dad62) | Feb 21, 2022 |
| Gigabyte      | 2AC8                        | [90d30ccc29](https://linux-hardware.org/?probe=90d30ccc29) | Feb 21, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [03491eae09](https://linux-hardware.org/?probe=03491eae09) | Feb 21, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [e1943c32e9](https://linux-hardware.org/?probe=e1943c32e9) | Feb 20, 2022 |
| HP            | 1998                        | [1cd99a92d0](https://linux-hardware.org/?probe=1cd99a92d0) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | [90154b9001](https://linux-hardware.org/?probe=90154b9001) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | [b42d2ce48e](https://linux-hardware.org/?probe=b42d2ce48e) | Feb 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Manjaro           | 1050     | 40.48%  |
| Manjaro 20.1      | 135      | 5.2%    |
| Manjaro 20.2.1    | 108      | 4.16%   |
| Manjaro 22.0.0    | 102      | 3.93%   |
| Manjaro 20.2      | 89       | 3.43%   |
| Manjaro 20.0.3    | 81       | 3.12%   |
| Manjaro 18.1.5    | 56       | 2.16%   |
| Manjaro 21.2.6    | 53       | 2.04%   |
| Manjaro 21.2.5    | 53       | 2.04%   |
| Manjaro 21.1.0    | 53       | 2.04%   |
| Manjaro 18.0.4    | 46       | 1.77%   |
| Manjaro 21.2.0    | 45       | 1.73%   |
| Manjaro 20.0      | 45       | 1.73%   |
| Manjaro 21.1.6    | 38       | 1.46%   |
| Manjaro 21.0.7    | 36       | 1.39%   |
| Manjaro 21.0.5    | 35       | 1.35%   |
| Manjaro 21.0      | 35       | 1.35%   |
| Manjaro 19.0.2    | 31       | 1.2%    |
| Manjaro 20.1.2    | 29       | 1.12%   |
| Manjaro 20.0.1    | 29       | 1.12%   |
| Manjaro 21.2.3    | 27       | 1.04%   |
| Manjaro 20.1.1    | 24       | 0.93%   |
| Manjaro 21.2.1    | 23       | 0.89%   |
| Manjaro 21.3.7    | 20       | 0.77%   |
| Manjaro 21.3.6    | 17       | 0.66%   |
| Manjaro 21.0.4    | 16       | 0.62%   |
| Manjaro 21.0.1    | 14       | 0.54%   |
| Manjaro 21.0.2    | 13       | 0.5%    |
| Manjaro 21.2rc    | 12       | 0.46%   |
| Manjaro 21.2.4    | 12       | 0.46%   |
| Manjaro 21.1.2    | 12       | 0.46%   |
| Manjaro 21.0.3    | 12       | 0.46%   |
| Manjaro 18.0.0-rc | 12       | 0.46%   |
| Manjaro 22.0      | 11       | 0.42%   |
| Manjaro 21.3.1    | 11       | 0.42%   |
| Manjaro 21.1.5    | 11       | 0.42%   |
| Manjaro 21.3.0    | 10       | 0.39%   |
| Manjaro 21.2.2    | 10       | 0.39%   |
| Manjaro 21.1.4    | 10       | 0.39%   |
| Manjaro 22.0.3    | 9        | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2381     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 115      | 4%      |
| 5.8.6-1-MANJARO   | 68       | 2.36%   |
| 5.13.19-2-MANJARO | 65       | 2.26%   |
| 5.15.28-1-MANJARO | 49       | 1.7%    |
| 5.9.11-3-MANJARO  | 47       | 1.63%   |
| 5.8.11-1-MANJARO  | 46       | 1.6%    |
| 5.10.42-1-MANJARO | 40       | 1.39%   |
| 6.1.1-1-MANJARO   | 38       | 1.32%   |
| 5.8.18-1-MANJARO  | 38       | 1.32%   |
| 5.15.32-1-MANJARO | 32       | 1.11%   |
| 5.6.16-1-MANJARO  | 31       | 1.08%   |
| 5.15.60-1-MANJARO | 30       | 1.04%   |
| 5.10.36-2-MANJARO | 30       | 1.04%   |
| 5.7.9-1-MANJARO   | 29       | 1.01%   |
| 5.15.12-1-MANJARO | 29       | 1.01%   |
| 5.8.3-2-MANJARO   | 25       | 0.87%   |
| 5.8.16-2-MANJARO  | 25       | 0.87%   |
| 5.6.19-2-MANJARO  | 24       | 0.83%   |
| 5.6.15-1-MANJARO  | 24       | 0.83%   |
| 5.17.1-3-MANJARO  | 24       | 0.83%   |
| 5.7.0-3-MANJARO   | 23       | 0.8%    |
| 5.10.2-2-MANJARO  | 23       | 0.8%    |
| 5.6.7-1-MANJARO   | 22       | 0.76%   |
| 5.6.12-1-MANJARO  | 22       | 0.76%   |
| 5.16.14-1-MANJARO | 22       | 0.76%   |
| 5.15.2-2-MANJARO  | 22       | 0.76%   |
| 5.10.23-1-MANJARO | 22       | 0.76%   |
| 5.9.1-1-MANJARO   | 21       | 0.73%   |
| 5.11.6-1-MANJARO  | 21       | 0.73%   |
| 5.4.15-2-MANJARO  | 20       | 0.7%    |
| 5.7.17-2-MANJARO  | 19       | 0.66%   |
| 5.4.6-2-MANJARO   | 19       | 0.66%   |
| 5.10.7-3-MANJARO  | 19       | 0.66%   |
| 5.10.15-1-MANJARO | 19       | 0.66%   |
| 5.14.10-1-MANJARO | 17       | 0.59%   |
| 5.11.2-1-MANJARO  | 17       | 0.59%   |
| 5.10.53-1-MANJARO | 17       | 0.59%   |
| 5.9.3-1-MANJARO   | 16       | 0.56%   |
| 5.6.11-1-MANJARO  | 16       | 0.56%   |
| 5.15.74-3-MANJARO | 16       | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 115      | 4%      |
| 5.8.6   | 68       | 2.37%   |
| 5.13.19 | 65       | 2.26%   |
| 5.9.11  | 50       | 1.74%   |
| 5.15.28 | 49       | 1.7%    |
| 5.8.11  | 47       | 1.63%   |
| 5.10.42 | 40       | 1.39%   |
| 6.1.1   | 38       | 1.32%   |
| 5.8.18  | 38       | 1.32%   |
| 5.15.32 | 32       | 1.11%   |
| 5.6.16  | 31       | 1.08%   |
| 5.15.60 | 30       | 1.04%   |
| 5.10.36 | 30       | 1.04%   |
| 5.7.9   | 29       | 1.01%   |
| 5.7.0   | 29       | 1.01%   |
| 5.17.1  | 29       | 1.01%   |
| 5.15.12 | 29       | 1.01%   |
| 5.9.1   | 28       | 0.97%   |
| 5.6.19  | 27       | 0.94%   |
| 5.8.3   | 26       | 0.9%    |
| 5.8.16  | 25       | 0.87%   |
| 5.6.15  | 24       | 0.83%   |
| 5.6.12  | 23       | 0.8%    |
| 5.15.2  | 23       | 0.8%    |
| 5.10.2  | 23       | 0.8%    |
| 5.6.7   | 22       | 0.77%   |
| 5.16.14 | 22       | 0.77%   |
| 5.10.23 | 22       | 0.77%   |
| 5.11.6  | 21       | 0.73%   |
| 5.7.17  | 20       | 0.7%    |
| 5.4.15  | 20       | 0.7%    |
| 5.10.7  | 20       | 0.7%    |
| 5.4.6   | 19       | 0.66%   |
| 5.10.15 | 19       | 0.66%   |
| 5.15.7  | 17       | 0.59%   |
| 5.14.10 | 17       | 0.59%   |
| 5.14.0  | 17       | 0.59%   |
| 5.11.2  | 17       | 0.59%   |
| 5.10.53 | 17       | 0.59%   |
| 5.9.3   | 16       | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 416      | 15.45%  |
| 5.10    | 357      | 13.26%  |
| 5.4     | 253      | 9.39%   |
| 5.9     | 229      | 8.5%    |
| 5.8     | 228      | 8.47%   |
| 5.6     | 172      | 6.39%   |
| 5.13    | 125      | 4.64%   |
| 5.7     | 109      | 4.05%   |
| 5.11    | 91       | 3.38%   |
| 6.1     | 87       | 3.23%   |
| 4.19    | 66       | 2.45%   |
| 5.17    | 64       | 2.38%   |
| 5.16    | 64       | 2.38%   |
| 5.14    | 61       | 2.27%   |
| 6.0     | 56       | 2.08%   |
| 5.18    | 55       | 2.04%   |
| 5.19    | 53       | 1.97%   |
| 5.12    | 49       | 1.82%   |
| 5.5     | 39       | 1.45%   |
| 4.14    | 33       | 1.23%   |
| 5.3     | 23       | 0.85%   |
| 5.2     | 17       | 0.63%   |
| 5.1     | 13       | 0.48%   |
| 5.0     | 11       | 0.41%   |
| 4.20    | 5        | 0.19%   |
| 4.18    | 5        | 0.19%   |
| 4.17    | 3        | 0.11%   |
| 4.16    | 3        | 0.11%   |
| 4.9     | 2        | 0.07%   |
| 4.7     | 2        | 0.07%   |
| 4.4     | 2        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2381     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 894      | 35.8%   |
| XFCE                     | 547      | 21.91%  |
| GNOME                    | 481      | 19.26%  |
| KDE                      | 247      | 9.89%   |
| Unknown                  | 102      | 4.08%   |
| X-Cinnamon               | 78       | 3.12%   |
| i3                       | 44       | 1.76%   |
| MATE                     | 22       | 0.88%   |
| Cinnamon                 | 22       | 0.88%   |
| Deepin                   | 21       | 0.84%   |
| Budgie                   | 13       | 0.52%   |
| LXQt                     | 7        | 0.28%   |
| Awesome                  | 4        | 0.16%   |
| sway                     | 3        | 0.12%   |
| Bspwm                    | 3        | 0.12%   |
| ICEWM                    | 2        | 0.08%   |
| GNOME Classic            | 2        | 0.08%   |
| openbox                  | 1        | 0.04%   |
| LXDE                     | 1        | 0.04%   |
| Enlightenment            | 1        | 0.04%   |
| DWM                      | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2177     | 89.81%  |
| Wayland | 185      | 7.63%   |
| Unknown | 38       | 1.57%   |
| Tty     | 24       | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1045     | 42.48%  |
| SDDM    | 619      | 25.16%  |
| LightDM | 419      | 17.03%  |
| GDM     | 277      | 11.26%  |
| TDM     | 89       | 3.62%   |
| LXDM    | 5        | 0.2%    |
| SLiM    | 2        | 0.08%   |
| GREETD  | 2        | 0.08%   |
| XDM     | 1        | 0.04%   |
| LYNDE   | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 956      | 39.5%   |
| de_DE   | 206      | 8.51%   |
| ru_RU   | 189      | 7.81%   |
| Unknown | 153      | 6.32%   |
| en_GB   | 148      | 6.12%   |
| pt_BR   | 101      | 4.17%   |
| fr_FR   | 65       | 2.69%   |
| en_CA   | 65       | 2.69%   |
| es_ES   | 61       | 2.52%   |
| it_IT   | 53       | 2.19%   |
| pl_PL   | 46       | 1.9%    |
| en_AU   | 35       | 1.45%   |
| nl_NL   | 19       | 0.79%   |
| en_IN   | 19       | 0.79%   |
| de_AT   | 19       | 0.79%   |
| ru_UA   | 18       | 0.74%   |
| sv_SE   | 15       | 0.62%   |
| es_AR   | 15       | 0.62%   |
| zh_CN   | 13       | 0.54%   |
| es_MX   | 13       | 0.54%   |
| fi_FI   | 12       | 0.5%    |
| en_IE   | 11       | 0.45%   |
| fr_CA   | 9        | 0.37%   |
| en_ZA   | 9        | 0.37%   |
| hu_HU   | 8        | 0.33%   |
| en_PH   | 8        | 0.33%   |
| en_NZ   | 8        | 0.33%   |
| da_DK   | 8        | 0.33%   |
| pt_PT   | 7        | 0.29%   |
| es_CL   | 7        | 0.29%   |
| cs_CZ   | 7        | 0.29%   |
| en_IL   | 6        | 0.25%   |
| en_DK   | 6        | 0.25%   |
| uk_UA   | 5        | 0.21%   |
| ja_JP   | 5        | 0.21%   |
| fr_BE   | 5        | 0.21%   |
| tr_TR   | 4        | 0.17%   |
| nb_NO   | 4        | 0.17%   |
| es_UY   | 4        | 0.17%   |
| es_PE   | 4        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1514     | 62.18%  |
| EFI  | 921      | 37.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2037     | 84.14%  |
| Btrfs   | 236      | 9.75%   |
| Unknown | 40       | 1.65%   |
| Xfs     | 39       | 1.61%   |
| Overlay | 36       | 1.49%   |
| F2fs    | 12       | 0.5%    |
| Tmpfs   | 10       | 0.41%   |
| Zfs     | 4        | 0.17%   |
| Ext2    | 3        | 0.12%   |
| Ext3    | 2        | 0.08%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1146     | 46.87%  |
| GPT     | 1033     | 42.25%  |
| MBR     | 266      | 10.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2010     | 82.58%  |
| Yes       | 424      | 17.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1508     | 61.98%  |
| Yes       | 925      | 38.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 710      | 29.82%  |
| Gigabyte Technology                  | 495      | 20.79%  |
| MSI                                  | 379      | 15.92%  |
| ASRock                               | 263      | 11.05%  |
| Dell                                 | 122      | 5.12%   |
| Hewlett-Packard                      | 108      | 4.54%   |
| Intel                                | 57       | 2.39%   |
| Lenovo                               | 49       | 2.06%   |
| Acer                                 | 27       | 1.13%   |
| Unknown                              | 19       | 0.8%    |
| Biostar                              | 18       | 0.76%   |
| Pegatron                             | 15       | 0.63%   |
| Huanan                               | 12       | 0.5%    |
| Foxconn                              | 10       | 0.42%   |
| Medion                               | 8        | 0.34%   |
| Apple                                | 8        | 0.34%   |
| Fujitsu                              | 7        | 0.29%   |
| ECS                                  | 7        | 0.29%   |
| BESSTAR Tech                         | 5        | 0.21%   |
| Shuttle                              | 4        | 0.17%   |
| Positivo                             | 4        | 0.17%   |
| AZW                                  | 4        | 0.17%   |
| Alienware                            | 4        | 0.17%   |
| PCWare                               | 3        | 0.13%   |
| ZOTAC                                | 2        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.08%   |
| Minix                                | 2        | 0.08%   |
| MACHINIST                            | 2        | 0.08%   |
| Inventec                             | 2        | 0.08%   |
| Google                               | 2        | 0.08%   |
| Fujitsu Siemens                      | 2        | 0.08%   |
| XFX                                  | 1        | 0.04%   |
| VS Company                           | 1        | 0.04%   |
| TPV-INVENTA                          | 1        | 0.04%   |
| SYWZ                                 | 1        | 0.04%   |
| System76                             | 1        | 0.04%   |
| Supermicro                           | 1        | 0.04%   |
| SiYW                                 | 1        | 0.04%   |
| Samsung Electronics                  | 1        | 0.04%   |
| Packard Bell                         | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 71       | 2.98%   |
| Gigabyte B450M DS3H              | 25       | 1.05%   |
| MSI MS-7C37                      | 24       | 1.01%   |
| MSI MS-7C02                      | 23       | 0.97%   |
| Unknown                          | 21       | 0.88%   |
| ASUS TUF Gaming X570-PLUS        | 20       | 0.84%   |
| ASUS PRIME A320M-K               | 18       | 0.76%   |
| MSI MS-7C91                      | 17       | 0.71%   |
| ASRock B450M Pro4                | 16       | 0.67%   |
| MSI MS-7B79                      | 15       | 0.63%   |
| MSI MS-7B86                      | 14       | 0.59%   |
| ASUS ROG STRIX B450-F GAMING     | 14       | 0.59%   |
| MSI MS-7A38                      | 12       | 0.5%    |
| Gigabyte X570 AORUS ELITE        | 12       | 0.5%    |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.5%    |
| ASUS ROG STRIX B550-F GAMING     | 12       | 0.5%    |
| ASUS PRIME B450M-A               | 12       | 0.5%    |
| Dell OptiPlex 9020               | 11       | 0.46%   |
| ASUS PRIME B350-PLUS             | 11       | 0.46%   |
| Gigabyte X570 AORUS MASTER       | 10       | 0.42%   |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.42%   |
| Gigabyte B450 AORUS M            | 10       | 0.42%   |
| Gigabyte 970A-DS3P               | 10       | 0.42%   |
| MSI MS-7B89                      | 9        | 0.38%   |
| MSI MS-7693                      | 9        | 0.38%   |
| Dell OptiPlex 7010               | 9        | 0.38%   |
| ASUS ROG STRIX X570-E GAMING     | 9        | 0.38%   |
| ASUS ROG CROSSHAIR VIII HERO     | 9        | 0.38%   |
| ASUS PRIME X470-PRO              | 9        | 0.38%   |
| ASUS PRIME B450-PLUS             | 9        | 0.38%   |
| MSI MS-7C94                      | 8        | 0.34%   |
| MSI MS-7A34                      | 8        | 0.34%   |
| MSI MS-7817                      | 8        | 0.34%   |
| Gigabyte B450 AORUS ELITE        | 8        | 0.34%   |
| ASUS PRIME X370-PRO              | 8        | 0.34%   |
| ASUS PRIME B350M-A               | 8        | 0.34%   |
| ASRock B450M Steel Legend        | 8        | 0.34%   |
| ASRock B450 Pro4                 | 8        | 0.34%   |
| ASUS ROG STRIX X570-F GAMING     | 7        | 0.29%   |
| ASUS M5A78L-M PLUS/USB3          | 7        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 152      | 6.38%   |
| ASUS ROG           | 133      | 5.59%   |
| Dell OptiPlex      | 75       | 3.15%   |
| ASUS TUF           | 73       | 3.07%   |
| ASUS All           | 71       | 2.98%   |
| Gigabyte X570      | 46       | 1.93%   |
| Gigabyte B450M     | 42       | 1.76%   |
| HP Compaq          | 33       | 1.39%   |
| Gigabyte B450      | 32       | 1.34%   |
| ASRock B450M       | 26       | 1.09%   |
| MSI MS-7C37        | 24       | 1.01%   |
| MSI MS-7C02        | 23       | 0.97%   |
| Lenovo ThinkCentre | 23       | 0.97%   |
| Unknown            | 21       | 0.88%   |
| ASRock X570        | 19       | 0.8%    |
| Dell Precision     | 18       | 0.76%   |
| ASRock B450        | 18       | 0.76%   |
| MSI MS-7C91        | 17       | 0.71%   |
| HP EliteDesk       | 17       | 0.71%   |
| Acer Aspire        | 17       | 0.71%   |
| Gigabyte B550      | 16       | 0.67%   |
| MSI MS-7B79        | 15       | 0.63%   |
| ASUS P8Z77-V       | 15       | 0.63%   |
| MSI MS-7B86        | 14       | 0.59%   |
| Gigabyte Z390      | 14       | 0.59%   |
| ASUS M5A97         | 14       | 0.59%   |
| ASUS M5A78L-M      | 13       | 0.55%   |
| MSI MS-7A38        | 12       | 0.5%    |
| Gigabyte X470      | 12       | 0.5%    |
| ASUS Maximus       | 12       | 0.5%    |
| Gigabyte 970A-DS3P | 11       | 0.46%   |
| ASUS P8H61-M       | 11       | 0.46%   |
| Gigabyte B550M     | 10       | 0.42%   |
| MSI MS-7B89        | 9        | 0.38%   |
| MSI MS-7693        | 9        | 0.38%   |
| HP Pavilion        | 9        | 0.38%   |
| ASRock X470        | 9        | 0.38%   |
| ASRock B550M       | 9        | 0.38%   |
| MSI MS-7C94        | 8        | 0.34%   |
| MSI MS-7A34        | 8        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 394      | 16.55%  |
| 2019    | 302      | 12.68%  |
| 2020    | 260      | 10.92%  |
| 2017    | 205      | 8.61%   |
| 2012    | 201      | 8.44%   |
| 2013    | 170      | 7.14%   |
| 2014    | 141      | 5.92%   |
| 2011    | 129      | 5.42%   |
| 2016    | 105      | 4.41%   |
| 2015    | 102      | 4.28%   |
| 2021    | 85       | 3.57%   |
| 2010    | 84       | 3.53%   |
| 2009    | 72       | 3.02%   |
| 2008    | 44       | 1.85%   |
| 2007    | 43       | 1.81%   |
| 2022    | 27       | 1.13%   |
| 2006    | 12       | 0.5%    |
| 2005    | 4        | 0.17%   |
| Unknown | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2381     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2379     | 99.87%  |
| Enabled  | 3        | 0.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2379     | 99.92%  |
| Yes  | 2        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 881      | 36.33%  |
| 32.01-64.0  | 491      | 20.25%  |
| 8.01-16.0   | 442      | 18.23%  |
| 4.01-8.0    | 226      | 9.32%   |
| 3.01-4.0    | 164      | 6.76%   |
| 64.01-256.0 | 113      | 4.66%   |
| 24.01-32.0  | 73       | 3.01%   |
| 1.01-2.0    | 30       | 1.24%   |
| 2.01-3.0    | 5        | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 662      | 24.66%  |
| 1.01-2.0    | 612      | 22.79%  |
| 2.01-3.0    | 608      | 22.64%  |
| 3.01-4.0    | 440      | 16.39%  |
| 8.01-16.0   | 223      | 8.31%   |
| 0.51-1.0    | 70       | 2.61%   |
| 16.01-24.0  | 39       | 1.45%   |
| 0.01-0.5    | 11       | 0.41%   |
| 24.01-32.0  | 10       | 0.37%   |
| 32.01-64.0  | 9        | 0.34%   |
| 64.01-256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 749      | 29.94%  |
| 1      | 589      | 23.54%  |
| 3      | 505      | 20.18%  |
| 4      | 327      | 13.07%  |
| 5      | 185      | 7.39%   |
| 6      | 69       | 2.76%   |
| 7      | 36       | 1.44%   |
| 8      | 13       | 0.52%   |
| 0      | 11       | 0.44%   |
| 9      | 9        | 0.36%   |
| 11     | 4        | 0.16%   |
| 12     | 2        | 0.08%   |
| 10     | 2        | 0.08%   |
| 20     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1592     | 65.95%  |
| Yes       | 822      | 34.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2355     | 98.91%  |
| No        | 26       | 1.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1284     | 53.21%  |
| Yes       | 1129     | 46.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1444     | 59.72%  |
| Yes       | 974      | 40.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 451      | 18.83%  |
| Germany      | 288      | 12.03%  |
| Russia       | 224      | 9.35%   |
| Brazil       | 143      | 5.97%   |
| Canada       | 96       | 4.01%   |
| France       | 87       | 3.63%   |
| Spain        | 81       | 3.38%   |
| UK           | 78       | 3.26%   |
| Italy        | 74       | 3.09%   |
| Poland       | 72       | 3.01%   |
| Ukraine      | 53       | 2.21%   |
| Netherlands  | 44       | 1.84%   |
| Sweden       | 42       | 1.75%   |
| Australia    | 37       | 1.54%   |
| Austria      | 35       | 1.46%   |
| Finland      | 29       | 1.21%   |
| Belgium      | 26       | 1.09%   |
| Mexico       | 25       | 1.04%   |
| Romania      | 22       | 0.92%   |
| India        | 22       | 0.92%   |
| Argentina    | 22       | 0.92%   |
| Greece       | 20       | 0.84%   |
| Bulgaria     | 19       | 0.79%   |
| Norway       | 18       | 0.75%   |
| Portugal     | 17       | 0.71%   |
| Hungary      | 16       | 0.67%   |
| Denmark      | 16       | 0.67%   |
| Switzerland  | 15       | 0.63%   |
| South Africa | 14       | 0.58%   |
| China        | 13       | 0.54%   |
| Belarus      | 13       | 0.54%   |
| Israel       | 12       | 0.5%    |
| Turkey       | 11       | 0.46%   |
| Czechia      | 11       | 0.46%   |
| Saudi Arabia | 10       | 0.42%   |
| New Zealand  | 10       | 0.42%   |
| Lithuania    | 10       | 0.42%   |
| Ireland      | 10       | 0.42%   |
| Chile        | 9        | 0.38%   |
| Bangladesh   | 9        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 52       | 2.06%   |
| St Petersburg     | 24       | 0.95%   |
| Vienna            | 18       | 0.71%   |
| Berlin            | 18       | 0.71%   |
| Warsaw            | 17       | 0.67%   |
| Kyiv              | 17       | 0.67%   |
| Madrid            | 15       | 0.59%   |
| Toronto           | 14       | 0.55%   |
| Sao Paulo         | 14       | 0.55%   |
| Athens            | 14       | 0.55%   |
| Rome              | 13       | 0.52%   |
| Stockholm         | 12       | 0.48%   |
| Rio de Janeiro    | 12       | 0.48%   |
| Helsinki          | 11       | 0.44%   |
| Amsterdam         | 11       | 0.44%   |
| Sydney            | 10       | 0.4%    |
| Paris             | 10       | 0.4%    |
| Krakow            | 10       | 0.4%    |
| Hamburg           | 10       | 0.4%    |
| Frankfurt am Main | 10       | 0.4%    |
| Sofia             | 9        | 0.36%   |
| Portland          | 9        | 0.36%   |
| Milan             | 9        | 0.36%   |
| Dallas            | 9        | 0.36%   |
| Copenhagen        | 9        | 0.36%   |
| Bucharest         | 9        | 0.36%   |
| Barcelona         | 9        | 0.36%   |
| Stuttgart         | 8        | 0.32%   |
| New York          | 8        | 0.32%   |
| Minsk             | 8        | 0.32%   |
| Miami             | 8        | 0.32%   |
| Melbourne         | 8        | 0.32%   |
| Indianapolis      | 8        | 0.32%   |
| Austin            | 8        | 0.32%   |
| Yekaterinburg     | 7        | 0.28%   |
| Omsk              | 7        | 0.28%   |
| Montreal          | 7        | 0.28%   |
| Istanbul          | 7        | 0.28%   |
| Vilnius           | 6        | 0.24%   |
| Riyadh            | 6        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 941      | 1572   | 17.97%  |
| Seagate                     | 916      | 1477   | 17.49%  |
| Samsung Electronics         | 869      | 1515   | 16.59%  |
| Kingston                    | 335      | 470    | 6.4%    |
| Toshiba                     | 290      | 375    | 5.54%   |
| Crucial                     | 275      | 421    | 5.25%   |
| SanDisk                     | 264      | 351    | 5.04%   |
| Hitachi                     | 131      | 189    | 2.5%    |
| Intel                       | 104      | 141    | 1.99%   |
| Phison                      | 83       | 111    | 1.58%   |
| A-DATA Technology           | 81       | 112    | 1.55%   |
| HGST                        | 59       | 94     | 1.13%   |
| China                       | 48       | 68     | 0.92%   |
| Silicon Motion              | 44       | 57     | 0.84%   |
| PNY                         | 41       | 60     | 0.78%   |
| OCZ                         | 39       | 51     | 0.74%   |
| Unknown                     | 35       | 59     | 0.67%   |
| SPCC                        | 34       | 41     | 0.65%   |
| Patriot                     | 34       | 41     | 0.65%   |
| Intenso                     | 33       | 49     | 0.63%   |
| XPG                         | 32       | 36     | 0.61%   |
| Micron/Crucial Technology   | 31       | 40     | 0.59%   |
| SK hynix                    | 29       | 33     | 0.55%   |
| Corsair                     | 27       | 38     | 0.52%   |
| Micron Technology           | 23       | 29     | 0.44%   |
| Transcend                   | 21       | 21     | 0.4%    |
| Plextor                     | 21       | 24     | 0.4%    |
| JMicron Technology          | 19       | 25     | 0.36%   |
| GOODRAM                     | 19       | 23     | 0.36%   |
| Team                        | 18       | 23     | 0.34%   |
| Lexar                       | 18       | 20     | 0.34%   |
| Realtek Semiconductor       | 17       | 22     | 0.32%   |
| Phison Electronics          | 16       | 18     | 0.31%   |
| Apacer                      | 14       | 16     | 0.27%   |
| Maxtor                      | 13       | 15     | 0.25%   |
| Kingston Technology Company | 12       | 13     | 0.23%   |
| Gigabyte Technology         | 11       | 19     | 0.21%   |
| KingDian                    | 10       | 10     | 0.19%   |
| Hewlett-Packard             | 10       | 14     | 0.19%   |
| ASMT                        | 10       | 17     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 86       | 1.38%   |
| Samsung SSD 860 EVO 500GB                           | 80       | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB                      | 75       | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB                      | 70       | 1.12%   |
| Samsung NVMe SSD Drive 500GB                        | 63       | 1.01%   |
| Samsung SSD 850 EVO 500GB                           | 61       | 0.98%   |
| Samsung SSD 850 EVO 250GB                           | 59       | 0.95%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 52       | 0.83%   |
| Toshiba DT01ACA100 1TB                              | 52       | 0.83%   |
| Kingston SA400S37120G 120GB SSD                     | 52       | 0.83%   |
| Samsung NVMe SSD Drive 1TB                          | 49       | 0.79%   |
| Samsung SSD 860 EVO 1TB                             | 48       | 0.77%   |
| Crucial CT500MX500SSD1 500GB                        | 48       | 0.77%   |
| Seagate ST2000DM006-2DM164 2TB                      | 40       | 0.64%   |
| Samsung SSD 860 EVO 250GB                           | 40       | 0.64%   |
| Kingston SA400S37480G 480GB SSD                     | 40       | 0.64%   |
| Seagate ST500DM002-1BD142 500GB                     | 39       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                      | 39       | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 37       | 0.59%   |
| Toshiba HDWD110 1TB                                 | 37       | 0.59%   |
| Crucial CT1000MX500SSD1 1TB                         | 37       | 0.59%   |
| Crucial CT240BX500SSD1 240GB                        | 35       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB                      | 32       | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB                      | 31       | 0.5%    |
| SanDisk NVMe SSD Drive 500GB                        | 31       | 0.5%    |
| Kingston SV300S37A120G 120GB SSD                    | 31       | 0.5%    |
| Seagate ST3500418AS 500GB                           | 30       | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 29       | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 28       | 0.45%   |
| Toshiba DT01ACA200 2TB                              | 28       | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB                      | 27       | 0.43%   |
| Seagate Expansion 1TB                               | 26       | 0.42%   |
| Toshiba DT01ACA050 500GB                            | 25       | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB                      | 25       | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB                      | 24       | 0.38%   |
| Samsung SSD 840 EVO 250GB                           | 24       | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 23       | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 23       | 0.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 23       | 0.37%   |
| Seagate ST31000524AS 1TB                            | 22       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 897      | 1439   | 37.34%  |
| WDC                 | 834      | 1345   | 34.72%  |
| Toshiba             | 259      | 330    | 10.78%  |
| Samsung Electronics | 134      | 206    | 5.58%   |
| Hitachi             | 131      | 189    | 5.45%   |
| HGST                | 58       | 93     | 2.41%   |
| Unknown             | 16       | 25     | 0.67%   |
| Maxtor              | 13       | 15     | 0.54%   |
| JMicron Technology  | 9        | 12     | 0.37%   |
| SABRENT             | 8        | 8      | 0.33%   |
| Fujitsu             | 8        | 8      | 0.33%   |
| Intenso             | 6        | 10     | 0.25%   |
| ASMT                | 5        | 12     | 0.21%   |
| Apple               | 5        | 8      | 0.21%   |
| USB3.0              | 4        | 4      | 0.17%   |
| HGST HTS            | 3        | 3      | 0.12%   |
| ASMedia             | 3        | 3      | 0.12%   |
| USB                 | 2        | 2      | 0.08%   |
| Maxone              | 2        | 2      | 0.08%   |
| Hewlett-Packard     | 2        | 2      | 0.08%   |
| MaxDigital          | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 515      | 782    | 26.12%  |
| Kingston            | 294      | 404    | 14.91%  |
| Crucial             | 248      | 385    | 12.58%  |
| SanDisk             | 162      | 212    | 8.22%   |
| WDC                 | 128      | 181    | 6.49%   |
| A-DATA Technology   | 67       | 93     | 3.4%    |
| Intel               | 52       | 69     | 2.64%   |
| China               | 47       | 67     | 2.38%   |
| OCZ                 | 39       | 51     | 1.98%   |
| PNY                 | 36       | 55     | 1.83%   |
| Patriot             | 32       | 39     | 1.62%   |
| SPCC                | 28       | 35     | 1.42%   |
| Toshiba             | 22       | 32     | 1.12%   |
| Intenso             | 20       | 30     | 1.01%   |
| Plextor             | 19       | 22     | 0.96%   |
| Corsair             | 19       | 28     | 0.96%   |
| Lexar               | 18       | 20     | 0.91%   |
| GOODRAM             | 18       | 22     | 0.91%   |
| Transcend           | 16       | 16     | 0.81%   |
| Micron Technology   | 15       | 17     | 0.76%   |
| Team                | 14       | 19     | 0.71%   |
| Apacer              | 14       | 16     | 0.71%   |
| SK hynix            | 10       | 11     | 0.51%   |
| KingDian            | 10       | 10     | 0.51%   |
| Seagate             | 9        | 12     | 0.46%   |
| Gigabyte Technology | 9        | 12     | 0.46%   |
| Leven               | 8        | 8      | 0.41%   |
| KingSpec            | 6        | 7      | 0.3%    |
| LITEONIT            | 5        | 7      | 0.25%   |
| ASMT                | 5        | 5      | 0.25%   |
| Verbatim            | 4        | 5      | 0.2%    |
| Mushkin             | 4        | 4      | 0.2%    |
| LITEON              | 4        | 4      | 0.2%    |
| Hoodisk             | 4        | 4      | 0.2%    |
| Apple               | 4        | 4      | 0.2%    |
| TO Exter            | 3        | 3      | 0.15%   |
| NGFF                | 3        | 3      | 0.15%   |
| Kingmax             | 3        | 4      | 0.15%   |
| Hewlett-Packard     | 3        | 4      | 0.15%   |
| Smartbuy            | 2        | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1734     | 3719   | 41.16%  |
| SSD     | 1533     | 2778   | 36.39%  |
| NVMe    | 858      | 1351   | 20.37%  |
| Unknown | 83       | 114    | 1.97%   |
| MMC     | 5        | 5      | 0.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2200     | 6267   | 67.11%  |
| NVMe | 854      | 1346   | 26.05%  |
| SAS  | 219      | 349    | 6.68%   |
| MMC  | 5        | 5      | 0.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 1654     | 3185   | 44.46%  |
| 0.51-1.0        | 1147     | 1880   | 30.83%  |
| 1.01-2.0        | 498      | 739    | 13.39%  |
| 3.01-4.0        | 157      | 250    | 4.22%   |
| 4.01-10.0       | 128      | 227    | 3.44%   |
| 2.01-3.0        | 120      | 185    | 3.23%   |
| 10.01-20.0      | 14       | 29     | 0.38%   |
| More than 100.0 | 2        | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 440      | 17.32%  |
| 251-500        | 438      | 17.24%  |
| 1001-2000      | 419      | 16.5%   |
| 501-1000       | 412      | 16.22%  |
| More than 3000 | 360      | 14.17%  |
| 2001-3000      | 218      | 8.58%   |
| Unknown        | 91       | 3.58%   |
| 51-100         | 89       | 3.5%    |
| 1-20           | 40       | 1.57%   |
| 21-50          | 33       | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 409      | 15.53%  |
| 1-20           | 387      | 14.69%  |
| 501-1000       | 333      | 12.64%  |
| 21-50          | 313      | 11.88%  |
| 251-500        | 307      | 11.66%  |
| 51-100         | 284      | 10.78%  |
| 1001-2000      | 258      | 9.79%   |
| More than 3000 | 148      | 5.62%   |
| 2001-3000      | 103      | 3.91%   |
| Unknown        | 91       | 3.45%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 9      | 2.23%   |
| WDC WD5000AAKX-001CA0 500GB           | 5        | 7      | 1.59%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.59%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.59%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.59%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.27%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.27%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.27%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.27%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.96%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 0.96%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 0.96%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 0.96%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 3        | 3      | 0.96%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 0.96%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 9      | 0.96%   |
| Seagate ST31000524AS 1TB              | 3        | 5      | 0.96%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 0.96%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.96%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.96%   |
| Crucial CT525MX300SSD1 528GB          | 3        | 3      | 0.96%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.64%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.64%   |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.64%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.64%   |
| WDC WD30EZRZ-00Z5HB0 3TB              | 2        | 2      | 0.64%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.64%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.64%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.64%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.64%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.64%   |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.64%   |
| Seagate ST2000DX001-1CM164 2TB        | 2        | 2      | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.64%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 7      | 0.64%   |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 3      | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.64%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 3      | 0.64%   |
| SanDisk SSD PLUS 240GB                | 2        | 2      | 0.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 97       | 113    | 32.12%  |
| Seagate             | 84       | 121    | 27.81%  |
| Samsung Electronics | 26       | 32     | 8.61%   |
| Hitachi             | 19       | 21     | 6.29%   |
| Kingston            | 12       | 12     | 3.97%   |
| Toshiba             | 11       | 14     | 3.64%   |
| Intel               | 9        | 10     | 2.98%   |
| SanDisk             | 8        | 11     | 2.65%   |
| HGST                | 7        | 7      | 2.32%   |
| Crucial             | 7        | 7      | 2.32%   |
| A-DATA Technology   | 4        | 4      | 1.32%   |
| OCZ                 | 2        | 2      | 0.66%   |
| Apacer              | 2        | 2      | 0.66%   |
| Transcend           | 1        | 1      | 0.33%   |
| SPCC                | 1        | 1      | 0.33%   |
| SK hynix            | 1        | 2      | 0.33%   |
| Phison              | 1        | 2      | 0.33%   |
| Patriot             | 1        | 1      | 0.33%   |
| Maxtor              | 1        | 1      | 0.33%   |
| MaxDigital          | 1        | 1      | 0.33%   |
| KingSpec            | 1        | 1      | 0.33%   |
| Intenso             | 1        | 4      | 0.33%   |
| Hewlett-Packard     | 1        | 1      | 0.33%   |
| Fujitsu             | 1        | 1      | 0.33%   |
| Drevo               | 1        | 1      | 0.33%   |
| Corsair             | 1        | 5      | 0.33%   |
| ASMT                | 1        | 5      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 96       | 112    | 40.17%  |
| Seagate             | 83       | 118    | 34.73%  |
| Samsung Electronics | 19       | 24     | 7.95%   |
| Hitachi             | 19       | 21     | 7.95%   |
| Toshiba             | 11       | 14     | 4.6%    |
| HGST                | 7        | 7      | 2.93%   |
| Maxtor              | 1        | 1      | 0.42%   |
| MaxDigital          | 1        | 1      | 0.42%   |
| Fujitsu             | 1        | 1      | 0.42%   |
| ASMT                | 1        | 5      | 0.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 220      | 304    | 78.29%  |
| SSD  | 52       | 68     | 18.51%  |
| NVMe | 9        | 11     | 3.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1561     | 4934   | 56.41%  |
| Works    | 928      | 2637   | 33.54%  |
| Malfunc  | 266      | 383    | 9.61%   |
| Failed   | 12       | 13     | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1261     | 34.59%  |
| AMD                              | 1108     | 30.39%  |
| Samsung Electronics              | 368      | 10.09%  |
| ASMedia Technology               | 152      | 4.17%   |
| SanDisk                          | 137      | 3.76%   |
| Phison Electronics               | 113      | 3.1%    |
| Marvell Technology Group         | 68       | 1.87%   |
| Micron/Crucial Technology        | 60       | 1.65%   |
| Silicon Motion                   | 59       | 1.62%   |
| Kingston Technology Company      | 57       | 1.56%   |
| JMicron Technology               | 55       | 1.51%   |
| ADATA Technology                 | 42       | 1.15%   |
| Nvidia                           | 34       | 0.93%   |
| Realtek Semiconductor            | 28       | 0.77%   |
| SK hynix                         | 19       | 0.52%   |
| Toshiba America Info Systems     | 9        | 0.25%   |
| KIOXIA                           | 9        | 0.25%   |
| Seagate Technology               | 8        | 0.22%   |
| Micron Technology                | 8        | 0.22%   |
| LSI Logic / Symbios Logic        | 8        | 0.22%   |
| VIA Technologies                 | 7        | 0.19%   |
| Silicon Image                    | 5        | 0.14%   |
| Lite-On Technology               | 5        | 0.14%   |
| Broadcom / LSI                   | 4        | 0.11%   |
| Adaptec                          | 4        | 0.11%   |
| Integrated Technology Express    | 3        | 0.08%   |
| Shenzhen Longsys Electronics     | 2        | 0.05%   |
| Union Memory (Shenzhen)          | 1        | 0.03%   |
| Transcend                        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| Promise Technology               | 1        | 0.03%   |
| PMC-Sierra                       | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.03%   |
| Lenovo                           | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Dell                             | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |
| Beijing Starblaze Technology     | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 741      | 16.23%  |
| AMD 400 Series Chipset SATA Controller                                                  | 328      | 7.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 225      | 4.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 153      | 3.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 149      | 3.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 137      | 3%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 124      | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 105      | 2.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 103      | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 102      | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 99       | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 92       | 2.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 84       | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 78       | 1.71%   |
| Intel SATA Controller [RAID mode]                                                       | 75       | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 66       | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 60       | 1.31%   |
| Phison E12 NVMe Controller                                                              | 55       | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 53       | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 52       | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 51       | 1.12%   |
| AMD FCH SATA Controller D                                                               | 50       | 1.09%   |
| AMD X370 Series Chipset SATA Controller                                                 | 42       | 0.92%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41       | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 41       | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 38       | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 38       | 0.83%   |
| Kingston Company A2000 NVMe SSD                                                         | 37       | 0.81%   |
| Samsung NVMe SSD Controller 980                                                         | 35       | 0.77%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 34       | 0.74%   |
| Intel SSD 660P Series                                                                   | 33       | 0.72%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 32       | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 31       | 0.68%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 29       | 0.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 28       | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 27       | 0.59%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 26       | 0.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 25       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2107     | 60.72%  |
| NVMe | 859      | 24.76%  |
| IDE  | 359      | 10.35%  |
| RAID | 125      | 3.6%    |
| SAS  | 17       | 0.49%   |
| SCSI | 3        | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1239     | 52.02%  |
| AMD    | 1143     | 47.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 123      | 5.14%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 74       | 3.09%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 61       | 2.55%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 61       | 2.55%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 44       | 1.84%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 31       | 1.3%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 30       | 1.25%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 28       | 1.17%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 26       | 1.09%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 1.05%   |
| AMD FX-8350 Eight-Core Processor            | 25       | 1.05%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 23       | 0.96%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 22       | 0.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 22       | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 22       | 0.92%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 22       | 0.92%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 22       | 0.92%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 22       | 0.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 21       | 0.88%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 21       | 0.88%   |
| AMD FX-6300 Six-Core Processor              | 21       | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 20       | 0.84%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 20       | 0.84%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 19       | 0.79%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 19       | 0.79%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 19       | 0.79%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.79%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 18       | 0.75%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 17       | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 17       | 0.71%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 17       | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 17       | 0.71%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 17       | 0.71%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 17       | 0.71%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 16       | 0.67%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15       | 0.63%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 15       | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 409      | 17.14%  |
| AMD Ryzen 5             | 395      | 16.55%  |
| Intel Core i7           | 334      | 14%     |
| AMD Ryzen 7             | 272      | 11.4%   |
| Intel Core i3           | 125      | 5.24%   |
| Intel Xeon              | 114      | 4.78%   |
| AMD Ryzen 9             | 108      | 4.53%   |
| AMD FX                  | 104      | 4.36%   |
| Other                   | 44       | 1.84%   |
| AMD Ryzen 3             | 44       | 1.84%   |
| Intel Core 2 Duo        | 43       | 1.8%    |
| Intel Celeron           | 34       | 1.42%   |
| Intel Pentium           | 30       | 1.26%   |
| AMD Ryzen Threadripper  | 26       | 1.09%   |
| AMD Phenom II X4        | 26       | 1.09%   |
| Intel Core 2 Quad       | 25       | 1.05%   |
| Intel Pentium Dual-Core | 22       | 0.92%   |
| Intel Core i9           | 20       | 0.84%   |
| AMD Athlon II X2        | 18       | 0.75%   |
| AMD A8                  | 18       | 0.75%   |
| AMD A10                 | 18       | 0.75%   |
| AMD A4                  | 15       | 0.63%   |
| AMD Athlon              | 12       | 0.5%    |
| Intel Core 2            | 11       | 0.46%   |
| AMD Phenom II X6        | 11       | 0.46%   |
| AMD Athlon 64 X2        | 11       | 0.46%   |
| AMD Athlon II X4        | 9        | 0.38%   |
| Intel Atom              | 8        | 0.34%   |
| AMD Ryzen 5 PRO         | 8        | 0.34%   |
| AMD Athlon X4           | 8        | 0.34%   |
| AMD Phenom              | 7        | 0.29%   |
| Intel Pentium Gold      | 6        | 0.25%   |
| Intel Pentium Dual      | 6        | 0.25%   |
| AMD Ryzen 7 PRO         | 6        | 0.25%   |
| Intel Genuine           | 5        | 0.21%   |
| AMD Athlon II X3        | 5        | 0.21%   |
| Intel Pentium D         | 4        | 0.17%   |
| AMD Sempron             | 3        | 0.13%   |
| AMD Phenom II X2        | 3        | 0.13%   |
| AMD E1                  | 3        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 844      | 35.36%  |
| 6       | 561      | 23.5%   |
| 2       | 370      | 15.5%   |
| 8       | 357      | 14.96%  |
| 12      | 97       | 4.06%   |
| 16      | 60       | 2.51%   |
| 3       | 42       | 1.76%   |
| 1       | 26       | 1.09%   |
| 10      | 18       | 0.75%   |
| 24      | 5        | 0.21%   |
| 32      | 3        | 0.13%   |
| Unknown | 2        | 0.08%   |
| 20      | 1        | 0.04%   |
| 14      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2363     | 99.24%  |
| 2      | 18       | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1602     | 67.09%  |
| 1       | 784      | 32.83%  |
| Unknown | 2        | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2353     | 98.62%  |
| Unknown        | 33       | 1.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1208     | 48.97%  |
| 0x08701021 | 130      | 5.27%   |
| 0x306c3    | 101      | 4.09%   |
| 0x0800820d | 100      | 4.05%   |
| 0x08701013 | 75       | 3.04%   |
| 0x306a9    | 65       | 2.63%   |
| 0x206a7    | 61       | 2.47%   |
| 0x906ea    | 56       | 2.27%   |
| 0x506e3    | 50       | 2.03%   |
| 0x06000852 | 46       | 1.86%   |
| 0x1067a    | 34       | 1.38%   |
| 0x08001138 | 31       | 1.26%   |
| 0x906e9    | 27       | 1.09%   |
| 0x306f2    | 22       | 0.89%   |
| 0x0a201009 | 22       | 0.89%   |
| 0x010000c8 | 22       | 0.89%   |
| 0x0a201016 | 21       | 0.85%   |
| 0x08108109 | 20       | 0.81%   |
| 0x206d7    | 19       | 0.77%   |
| 0x08001137 | 19       | 0.77%   |
| 0x06003106 | 14       | 0.57%   |
| 0xa0655    | 13       | 0.53%   |
| 0x08101016 | 13       | 0.53%   |
| 0x906ed    | 12       | 0.49%   |
| 0x106e5    | 12       | 0.49%   |
| 0x06001119 | 12       | 0.49%   |
| 0x90672    | 10       | 0.41%   |
| 0x08600106 | 10       | 0.41%   |
| 0x0a50000c | 9        | 0.36%   |
| 0x08001129 | 9        | 0.36%   |
| 0xa0671    | 8        | 0.32%   |
| 0xa0653    | 8        | 0.32%   |
| 0x906ec    | 8        | 0.32%   |
| 0x906eb    | 8        | 0.32%   |
| 0x6fd      | 8        | 0.32%   |
| 0x0a20120a | 8        | 0.32%   |
| 0x10676    | 7        | 0.28%   |
| 0x0a50000d | 7        | 0.28%   |
| 0x010000dc | 7        | 0.28%   |
| 0x406f1    | 6        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 341      | 14.28%  |
| Haswell          | 255      | 10.68%  |
| KabyLake         | 240      | 10.05%  |
| Zen+             | 231      | 9.67%   |
| Zen              | 156      | 6.53%   |
| SandyBridge      | 154      | 6.45%   |
| IvyBridge        | 148      | 6.2%    |
| Zen 3            | 135      | 5.65%   |
| Piledriver       | 115      | 4.82%   |
| Skylake          | 106      | 4.44%   |
| Penryn           | 88       | 3.69%   |
| K10              | 79       | 3.31%   |
| CometLake        | 54       | 2.26%   |
| Unknown          | 41       | 1.72%   |
| Core             | 39       | 1.63%   |
| Nehalem          | 32       | 1.34%   |
| Westmere         | 29       | 1.21%   |
| Steamroller      | 24       | 1.01%   |
| Bulldozer        | 18       | 0.75%   |
| Broadwell        | 16       | 0.67%   |
| K8 Hammer        | 14       | 0.59%   |
| Alderlake Hybrid | 10       | 0.42%   |
| Excavator        | 8        | 0.34%   |
| Goldmont plus    | 7        | 0.29%   |
| Bonnell          | 7        | 0.29%   |
| Silvermont       | 6        | 0.25%   |
| NetBurst         | 6        | 0.25%   |
| Icelake          | 6        | 0.25%   |
| Goldmont         | 6        | 0.25%   |
| K10 Llano        | 5        | 0.21%   |
| Jaguar           | 4        | 0.17%   |
| Bobcat           | 4        | 0.17%   |
| Puma             | 2        | 0.08%   |
| Tremont          | 1        | 0.04%   |
| TigerLake        | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1208     | 47.1%   |
| AMD                        | 911      | 35.52%  |
| Intel                      | 444      | 17.31%  |
| Matrox Electronics Systems | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 228      | 8.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 89       | 3.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 83       | 3.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 82       | 3.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 82       | 3.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 62       | 2.35%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 52       | 1.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 52       | 1.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 49       | 1.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 47       | 1.78%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 41       | 1.55%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 41       | 1.55%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 39       | 1.48%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 38       | 1.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 36       | 1.36%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 34       | 1.29%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 32       | 1.21%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 32       | 1.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 30       | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 29       | 1.1%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 28       | 1.06%   |
| Intel HD Graphics 530                                                       | 27       | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 27       | 1.02%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 26       | 0.98%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 26       | 0.98%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 24       | 0.91%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 23       | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 22       | 0.83%   |
| Intel HD Graphics 630                                                       | 22       | 0.83%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 22       | 0.83%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 20       | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 20       | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 19       | 0.72%   |
| Nvidia GK208B [GeForce GT 730]                                              | 19       | 0.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 19       | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 19       | 0.72%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 18       | 0.68%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 18       | 0.68%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 18       | 0.68%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 17       | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1104     | 45.68%  |
| 1 x AMD            | 830      | 34.34%  |
| 1 x Intel          | 326      | 13.49%  |
| Intel + Nvidia     | 43       | 1.78%   |
| 2 x AMD            | 36       | 1.49%   |
| AMD + Nvidia       | 36       | 1.49%   |
| 2 x Nvidia         | 25       | 1.03%   |
| Intel + AMD        | 14       | 0.58%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1415     | 58.69%  |
| Proprietary | 984      | 40.81%  |
| Unknown     | 12       | 0.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 961      | 39.16%  |
| 7.01-8.0   | 380      | 15.48%  |
| 1.01-2.0   | 305      | 12.43%  |
| 3.01-4.0   | 256      | 10.43%  |
| 5.01-6.0   | 174      | 7.09%   |
| 0.51-1.0   | 149      | 6.07%   |
| 8.01-16.0  | 91       | 3.71%   |
| 0.01-0.5   | 82       | 3.34%   |
| 2.01-3.0   | 44       | 1.79%   |
| 16.01-24.0 | 10       | 0.41%   |
| 4.01-5.0   | 2        | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 447      | 15.59%  |
| Goldstar             | 320      | 11.16%  |
| Dell                 | 265      | 9.24%   |
| Acer                 | 233      | 8.12%   |
| AOC                  | 174      | 6.07%   |
| Ancor Communications | 173      | 6.03%   |
| BenQ                 | 170      | 5.93%   |
| Hewlett-Packard      | 134      | 4.67%   |
| Philips              | 118      | 4.11%   |
| LG Electronics       | 96       | 3.35%   |
| ViewSonic            | 64       | 2.23%   |
| ASUSTek Computer     | 61       | 2.13%   |
| Lenovo               | 45       | 1.57%   |
| Unknown              | 41       | 1.43%   |
| Iiyama               | 41       | 1.43%   |
| Sony                 | 26       | 0.91%   |
| Unknown              | 24       | 0.84%   |
| Vizio                | 21       | 0.73%   |
| MSI                  | 17       | 0.59%   |
| AUS                  | 17       | 0.59%   |
| Fujitsu Siemens      | 15       | 0.52%   |
| Eizo                 | 15       | 0.52%   |
| NEC Computers        | 14       | 0.49%   |
| Sceptre Tech         | 13       | 0.45%   |
| Idek Iiyama          | 13       | 0.45%   |
| Medion               | 12       | 0.42%   |
| Sharp                | 10       | 0.35%   |
| Gigabyte Technology  | 10       | 0.35%   |
| Vestel Elektronik    | 8        | 0.28%   |
| Microstep            | 8        | 0.28%   |
| HannStar             | 8        | 0.28%   |
| Toshiba              | 7        | 0.24%   |
| Panasonic            | 7        | 0.24%   |
| Lenovo Group Limited | 7        | 0.24%   |
| Pixio                | 6        | 0.21%   |
| HPN                  | 6        | 0.21%   |
| Apple                | 6        | 0.21%   |
| Vestel               | 5        | 0.17%   |
| Plain Tree Systems   | 5        | 0.17%   |
| Packard Bell         | 5        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 24       | 0.77%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 18       | 0.58%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 17       | 0.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 17       | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 12       | 0.38%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 11       | 0.35%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 10       | 0.32%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 9        | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 9        | 0.29%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 9        | 0.29%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 8        | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8        | 0.26%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 8        | 0.26%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 8        | 0.26%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 8        | 0.26%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8        | 0.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 7        | 0.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 7        | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7        | 0.22%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 6        | 0.19%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 6        | 0.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 6        | 0.19%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 6        | 0.19%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                  | 6        | 0.19%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 6        | 0.19%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 6        | 0.19%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 0.19%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                      | 6        | 0.19%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 6        | 0.19%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 6        | 0.19%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 6        | 0.19%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch      | 6        | 0.19%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6        | 0.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.19%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 6        | 0.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 5        | 0.16%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 5        | 0.16%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 5        | 0.16%   |
| MSI MAG341CQ MSI1462 3440x1440 797x334mm 34.0-inch                    | 5        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1228     | 44%     |
| 3840x2160 (4K)     | 263      | 9.42%   |
| 2560x1440 (QHD)    | 256      | 9.17%   |
| Unknown            | 154      | 5.52%   |
| 1680x1050 (WSXGA+) | 116      | 4.16%   |
| 1280x1024 (SXGA)   | 113      | 4.05%   |
| 1920x1200 (WUXGA)  | 75       | 2.69%   |
| 1366x768 (WXGA)    | 73       | 2.62%   |
| 3440x1440          | 72       | 2.58%   |
| 1440x900 (WXGA+)   | 69       | 2.47%   |
| 3840x1080          | 65       | 2.33%   |
| 2560x1080          | 64       | 2.29%   |
| 1600x900 (HD+)     | 55       | 1.97%   |
| 1360x768           | 24       | 0.86%   |
| 4480x1440          | 11       | 0.39%   |
| 5760x1080          | 10       | 0.36%   |
| 1920x540           | 10       | 0.36%   |
| 5120x1440          | 9        | 0.32%   |
| 1280x720 (HD)      | 9        | 0.32%   |
| 1024x768 (XGA)     | 9        | 0.32%   |
| 5760x2160          | 6        | 0.21%   |
| 3600x1080          | 6        | 0.21%   |
| 2560x1600          | 6        | 0.21%   |
| 3840x1600          | 5        | 0.18%   |
| 3360x1080          | 5        | 0.18%   |
| 3200x1080          | 5        | 0.18%   |
| 7680x2160          | 4        | 0.14%   |
| 6400x2160          | 4        | 0.14%   |
| 3840x1200          | 4        | 0.14%   |
| 3520x1080          | 4        | 0.14%   |
| 3286x1080          | 3        | 0.11%   |
| 1600x1200          | 3        | 0.11%   |
| 5504x1440          | 2        | 0.07%   |
| 5120x1080          | 2        | 0.07%   |
| 4480x1080          | 2        | 0.07%   |
| 4240x1440          | 2        | 0.07%   |
| 3360x1050          | 2        | 0.07%   |
| 2944x1080          | 2        | 0.07%   |
| 2880x900           | 2        | 0.07%   |
| 2720x1024          | 2        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 474      | 17.16%  |
| 24      | 397      | 14.37%  |
| 27      | 394      | 14.27%  |
| 23      | 325      | 11.77%  |
| 21      | 283      | 10.25%  |
| 19      | 122      | 4.42%   |
| 31      | 107      | 3.87%   |
| 34      | 106      | 3.84%   |
| 22      | 79       | 2.86%   |
| 18      | 67       | 2.43%   |
| 20      | 62       | 2.24%   |
| 17      | 48       | 1.74%   |
| 84      | 34       | 1.23%   |
| 72      | 21       | 0.76%   |
| 32      | 21       | 0.76%   |
| 54      | 20       | 0.72%   |
| 25      | 20       | 0.72%   |
| 40      | 18       | 0.65%   |
| 15      | 15       | 0.54%   |
| 48      | 12       | 0.43%   |
| 28      | 12       | 0.43%   |
| 49      | 10       | 0.36%   |
| 65      | 9        | 0.33%   |
| 43      | 9        | 0.33%   |
| 33      | 8        | 0.29%   |
| 46      | 7        | 0.25%   |
| 37      | 7        | 0.25%   |
| 26      | 6        | 0.22%   |
| 14      | 6        | 0.22%   |
| 39      | 5        | 0.18%   |
| 36      | 5        | 0.18%   |
| 35      | 5        | 0.18%   |
| 29      | 5        | 0.18%   |
| 12      | 5        | 0.18%   |
| 60      | 4        | 0.14%   |
| 47      | 4        | 0.14%   |
| 42      | 4        | 0.14%   |
| 64      | 3        | 0.11%   |
| 55      | 3        | 0.11%   |
| 38      | 3        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 992      | 37.63%  |
| 401-500     | 533      | 20.22%  |
| Unknown     | 474      | 17.98%  |
| 601-700     | 161      | 6.11%   |
| 701-800     | 140      | 5.31%   |
| 351-400     | 77       | 2.92%   |
| 1001-1500   | 72       | 2.73%   |
| 301-350     | 60       | 2.28%   |
| 1501-2000   | 60       | 2.28%   |
| 801-900     | 40       | 1.52%   |
| 201-300     | 14       | 0.53%   |
| 901-1000    | 13       | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1519     | 60.69%  |
| Unknown | 443      | 17.7%   |
| 16/10   | 248      | 9.91%   |
| 21/9    | 116      | 4.63%   |
| 5/4     | 106      | 4.23%   |
| 4/3     | 28       | 1.12%   |
| 3/2     | 18       | 0.72%   |
| 32/9    | 15       | 0.6%    |
| 6/5     | 5        | 0.2%    |
| 3.20    | 1        | 0.04%   |
| 1.96    | 1        | 0.04%   |
| 1.03    | 1        | 0.04%   |
| 0.80    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 868      | 32.07%  |
| Unknown        | 474      | 17.51%  |
| 301-350        | 396      | 14.63%  |
| 351-500        | 260      | 9.6%    |
| 151-200        | 251      | 9.27%   |
| 251-300        | 142      | 5.25%   |
| More than 1000 | 110      | 4.06%   |
| 141-150        | 92       | 3.4%    |
| 501-1000       | 76       | 2.81%   |
| 101-110        | 18       | 0.66%   |
| 131-140        | 7        | 0.26%   |
| 71-80          | 5        | 0.18%   |
| 81-90          | 2        | 0.07%   |
| 51-60          | 2        | 0.07%   |
| 91-100         | 2        | 0.07%   |
| 121-130        | 1        | 0.04%   |
| 111-120        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1370     | 53.35%  |
| 101-120 | 485      | 18.89%  |
| Unknown | 474      | 18.46%  |
| 121-160 | 93       | 3.62%   |
| 1-50    | 87       | 3.39%   |
| 161-240 | 59       | 2.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1760     | 72.25%  |
| 2     | 559      | 22.95%  |
| 3     | 78       | 3.2%    |
| 0     | 34       | 1.4%    |
| 4     | 5        | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1453     | 42.56%  |
| Intel                                  | 1076     | 31.52%  |
| Qualcomm Atheros                       | 184      | 5.39%   |
| Broadcom                               | 98       | 2.87%   |
| Ralink Technology                      | 86       | 2.52%   |
| TP-Link                                | 84       | 2.46%   |
| Microsoft                              | 45       | 1.32%   |
| Nvidia                                 | 30       | 0.88%   |
| Aquantia                               | 28       | 0.82%   |
| Ralink                                 | 26       | 0.76%   |
| MediaTek                               | 24       | 0.7%    |
| Qualcomm Atheros Communications        | 23       | 0.67%   |
| Samsung Electronics                    | 19       | 0.56%   |
| Xiaomi                                 | 18       | 0.53%   |
| ASUSTek Computer                       | 17       | 0.5%    |
| NetGear                                | 15       | 0.44%   |
| Marvell Technology Group               | 15       | 0.44%   |
| D-Link                                 | 15       | 0.44%   |
| Huawei Technologies                    | 12       | 0.35%   |
| Broadcom Limited                       | 12       | 0.35%   |
| Linksys                                | 11       | 0.32%   |
| Microchip Technology                   | 8        | 0.23%   |
| D-Link System                          | 8        | 0.23%   |
| Edimax Technology                      | 7        | 0.21%   |
| Mellanox Technologies                  | 6        | 0.18%   |
| Motorola PCS                           | 5        | 0.15%   |
| ASIX Electronics                       | 5        | 0.15%   |
| ZyXEL Communications                   | 4        | 0.12%   |
| InterBiometrics                        | 4        | 0.12%   |
| T & A Mobile Phones                    | 3        | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.09%   |
| SEGGER                                 | 3        | 0.09%   |
| Qualcomm                               | 3        | 0.09%   |
| OPPO                                   | 3        | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.09%   |
| JMicron Technology                     | 3        | 0.09%   |
| IMC Networks                           | 3        | 0.09%   |
| Google                                 | 3        | 0.09%   |
| Belkin Components                      | 3        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 3        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1189     | 30.3%   |
| Intel I211 Gigabit Network Connection                             | 271      | 6.91%   |
| Intel Wi-Fi 6 AX200                                               | 181      | 4.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 133      | 3.39%   |
| Intel Ethernet Connection (2) I219-V                              | 118      | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73       | 1.86%   |
| Intel Ethernet Controller I225-V                                  | 69       | 1.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 64       | 1.63%   |
| Intel Ethernet Connection (7) I219-V                              | 53       | 1.35%   |
| Intel Wireless-AC 9260                                            | 47       | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.2%    |
| Intel Ethernet Connection (2) I218-V                              | 42       | 1.07%   |
| Intel Ethernet Connection I217-V                                  | 37       | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 31       | 0.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31       | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 31       | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 30       | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29       | 0.74%   |
| Ralink MT7601U Wireless Adapter                                   | 27       | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25       | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                               | 25       | 0.64%   |
| Realtek 802.11ac NIC                                              | 24       | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                   | 23       | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 22       | 0.56%   |
| Intel Wireless 7265                                               | 22       | 0.56%   |
| Intel 82574L Gigabit Network Connection                           | 21       | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 20       | 0.51%   |
| Nvidia MCP61 Ethernet                                             | 19       | 0.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.46%   |
| Intel Wireless 8265 / 8275                                        | 18       | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 17       | 0.43%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 17       | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16       | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 16       | 0.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15       | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 15       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 444      | 36.24%  |
| Realtek Semiconductor                 | 241      | 19.67%  |
| Qualcomm Atheros                      | 92       | 7.51%   |
| Ralink Technology                     | 86       | 7.02%   |
| TP-Link                               | 83       | 6.78%   |
| Broadcom                              | 62       | 5.06%   |
| Microsoft                             | 45       | 3.67%   |
| Ralink                                | 26       | 2.12%   |
| Qualcomm Atheros Communications       | 23       | 1.88%   |
| MediaTek                              | 20       | 1.63%   |
| ASUSTek Computer                      | 17       | 1.39%   |
| NetGear                               | 15       | 1.22%   |
| D-Link                                | 15       | 1.22%   |
| Linksys                               | 11       | 0.9%    |
| Edimax Technology                     | 7        | 0.57%   |
| D-Link System                         | 5        | 0.41%   |
| Broadcom Limited                      | 5        | 0.41%   |
| ZyXEL Communications                  | 4        | 0.33%   |
| IMC Networks                          | 3        | 0.24%   |
| Belkin Components                     | 3        | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.24%   |
| ZyDAS                                 | 2        | 0.16%   |
| Tenda                                 | 2        | 0.16%   |
| Mercucys                              | 2        | 0.16%   |
| AVM                                   | 2        | 0.16%   |
| Xiaomi                                | 1        | 0.08%   |
| Wacom                                 | 1        | 0.08%   |
| Senao                                 | 1        | 0.08%   |
| Philips (or NXP)                      | 1        | 0.08%   |
| Marvell Technology Group              | 1        | 0.08%   |
| Fujitsu Siemens Computers             | 1        | 0.08%   |
| Encore Electronics                    | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 181      | 14.63%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 64       | 5.17%   |
| Intel Wireless-AC 9260                                         | 47       | 3.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 31       | 2.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31       | 2.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 30       | 2.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29       | 2.34%   |
| Ralink MT7601U Wireless Adapter                                | 27       | 2.18%   |
| Microsoft Xbox 360 Wireless Adapter                            | 25       | 2.02%   |
| Realtek 802.11ac NIC                                           | 24       | 1.94%   |
| Qualcomm Atheros AR9271 802.11n                                | 23       | 1.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 22       | 1.78%   |
| Intel Wireless 7265                                            | 22       | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 20       | 1.62%   |
| Intel Wireless 8265 / 8275                                     | 18       | 1.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17       | 1.37%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 1.37%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 16       | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15       | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 15       | 1.21%   |
| Ralink RT5370 Wireless Adapter                                 | 14       | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 13       | 1.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 13       | 1.05%   |
| Microsoft XBOX ACC                                             | 13       | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12       | 0.97%   |
| Intel Wireless 3165                                            | 12       | 0.97%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 12       | 0.97%   |
| TP-Link 802.11ac NIC                                           | 11       | 0.89%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 11       | 0.89%   |
| Intel Wireless 7260                                            | 11       | 0.89%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 10       | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 10       | 0.81%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 9        | 0.73%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 9        | 0.73%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.73%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 0.73%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 8        | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 8        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1368     | 53.48%  |
| Intel                                  | 866      | 33.85%  |
| Qualcomm Atheros                       | 107      | 4.18%   |
| Broadcom                               | 39       | 1.52%   |
| Nvidia                                 | 30       | 1.17%   |
| Aquantia                               | 28       | 1.09%   |
| Samsung Electronics                    | 19       | 0.74%   |
| Xiaomi                                 | 17       | 0.66%   |
| Marvell Technology Group               | 14       | 0.55%   |
| Huawei Technologies                    | 10       | 0.39%   |
| Broadcom Limited                       | 7        | 0.27%   |
| Mellanox Technologies                  | 6        | 0.23%   |
| ASIX Electronics                       | 5        | 0.2%    |
| Sony Ericsson Mobile Communications AB | 3        | 0.12%   |
| OPPO                                   | 3        | 0.12%   |
| MediaTek                               | 3        | 0.12%   |
| JMicron Technology                     | 3        | 0.12%   |
| Google                                 | 3        | 0.12%   |
| D-Link System                          | 3        | 0.12%   |
| T & A Mobile Phones                    | 2        | 0.08%   |
| Qualcomm                               | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.08%   |
| National Semiconductor                 | 2        | 0.08%   |
| Motorola PCS                           | 2        | 0.08%   |
| HMD Global                             | 2        | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| VIA Technologies                       | 1        | 0.04%   |
| TP-Link                                | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| NetXen Incorporated                    | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| ICS Advent                             | 1        | 0.04%   |
| Foxconn / Hon Hai                      | 1        | 0.04%   |
| DisplayLink                            | 1        | 0.04%   |
| Apple                                  | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1189     | 44.9%   |
| Intel I211 Gigabit Network Connection                             | 271      | 10.23%  |
| Realtek RTL8125 2.5GbE Controller                                 | 133      | 5.02%   |
| Intel Ethernet Connection (2) I219-V                              | 118      | 4.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73       | 2.76%   |
| Intel Ethernet Controller I225-V                                  | 69       | 2.61%   |
| Intel Ethernet Connection (7) I219-V                              | 53       | 2%      |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.77%   |
| Intel Ethernet Connection (2) I218-V                              | 42       | 1.59%   |
| Intel Ethernet Connection I217-V                                  | 37       | 1.4%    |
| Intel Ethernet Connection I217-LM                                 | 35       | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31       | 1.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25       | 0.94%   |
| Intel 82574L Gigabit Network Connection                           | 21       | 0.79%   |
| Nvidia MCP61 Ethernet                                             | 19       | 0.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17       | 0.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16       | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 13       | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 12       | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.42%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 10       | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 9        | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.34%   |
| Intel Ethernet Connection (14) I219-V                             | 9        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 8        | 0.3%    |
| Intel Ethernet Connection (2) I218-LM                             | 7        | 0.26%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 0.26%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.23%   |
| Intel 82578DC Gigabit Network Connection                          | 6        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2356     | 66.89%  |
| WiFi     | 1129     | 32.06%  |
| Modem    | 29       | 0.82%   |
| Unknown  | 8        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1890     | 76.21%  |
| WiFi     | 590      | 23.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1517     | 63.16%  |
| 2     | 743      | 30.93%  |
| 3     | 107      | 4.45%   |
| 0     | 19       | 0.79%   |
| 5     | 7        | 0.29%   |
| 4     | 7        | 0.29%   |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2020     | 83.3%   |
| Yes  | 405      | 16.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 417      | 41.37%  |
| Cambridge Silicon Radio         | 281      | 27.88%  |
| ASUSTek Computer                | 93       | 9.23%   |
| Realtek Semiconductor           | 63       | 6.25%   |
| Broadcom                        | 52       | 5.16%   |
| Qualcomm Atheros Communications | 15       | 1.49%   |
| IMC Networks                    | 13       | 1.29%   |
| Apple                           | 13       | 1.29%   |
| TP-Link                         | 7        | 0.69%   |
| MediaTek                        | 7        | 0.69%   |
| Edimax Technology               | 6        | 0.6%    |
| Dynex                           | 6        | 0.6%    |
| HTC (High Tech Computer)        | 5        | 0.5%    |
| Foxconn / Hon Hai               | 5        | 0.5%    |
| Lite-On Technology              | 4        | 0.4%    |
| Conwise Technology              | 4        | 0.4%    |
| SINO WEALTH                     | 3        | 0.3%    |
| Realtek                         | 3        | 0.3%    |
| Integrated System Solution      | 3        | 0.3%    |
| Belkin Components               | 3        | 0.3%    |
| Ralink                          | 2        | 0.2%    |
| Sitecom Europe                  | 1        | 0.1%    |
| Micro Star International        | 1        | 0.1%    |
| D-Link                          | 1        | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 281      | 27.79%  |
| Intel AX200 Bluetooth                                                | 166      | 16.42%  |
| Intel Bluetooth wireless interface                                   | 70       | 6.92%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 63       | 6.23%   |
| Realtek Bluetooth Radio                                              | 52       | 5.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 47       | 4.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 39       | 3.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 34       | 3.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 32       | 3.17%   |
| Intel AX201 Bluetooth                                                | 20       | 1.98%   |
| Intel AX210 Bluetooth                                                | 15       | 1.48%   |
| ASUS Bluetooth Radio                                                 | 14       | 1.38%   |
| ASUS Bluetooth Adapter                                               | 13       | 1.29%   |
| ASUS ASUS USB-BT500                                                  | 12       | 1.19%   |
| ASUS BCM20702A0                                                      | 10       | 0.99%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 9        | 0.89%   |
| IMC Networks Bluetooth Radio                                         | 8        | 0.79%   |
| TP-Link TPuLink UB500 Adapter                                        | 7        | 0.69%   |
| MediaTek Wireless_Device                                             | 7        | 0.69%   |
| Apple Bluetooth USB Host Controller                                  | 7        | 0.69%   |
| Qualcomm Atheros  Bluetooth Device                                   | 6        | 0.59%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.59%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.49%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 5        | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.4%    |
| Edimax Bluetooth Adapter                                             | 4        | 0.4%    |
| Conwise CW6622                                                       | 4        | 0.4%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 4        | 0.4%    |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.3%    |
| Realtek Bluetooth Radio                                              | 3        | 0.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.3%    |
| Intel Bluetooth Device                                               | 3        | 0.3%    |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.3%    |
| Ralink RT3290 Bluetooth                                              | 2        | 0.2%    |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.2%    |
| Lite-On Bluetooth Device                                             | 2        | 0.2%    |
| Integrated System Solution Bluetooth Device                          | 2        | 0.2%    |
| IMC Networks Wireless_Device                                         | 2        | 0.2%    |
| IMC Networks BCM20702A0                                              | 2        | 0.2%    |
| Foxconn / Hon Hai Wireless_Device                                    | 2        | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 1353     | 29.21%  |
| Intel                                | 1195     | 25.8%   |
| Nvidia                               | 1155     | 24.94%  |
| C-Media Electronics                  | 172      | 3.71%   |
| Creative Labs                        | 67       | 1.45%   |
| Logitech                             | 66       | 1.42%   |
| Kingston Technology                  | 44       | 0.95%   |
| JMTek                                | 37       | 0.8%    |
| Texas Instruments                    | 33       | 0.71%   |
| Corsair                              | 32       | 0.69%   |
| SteelSeries ApS                      | 28       | 0.6%    |
| Focusrite-Novation                   | 27       | 0.58%   |
| Creative Technology                  | 27       | 0.58%   |
| Blue Microphones                     | 26       | 0.56%   |
| ASUSTek Computer                     | 23       | 0.5%    |
| Razer USA                            | 22       | 0.47%   |
| Generalplus Technology               | 22       | 0.47%   |
| BEHRINGER International              | 20       | 0.43%   |
| Plantronics                          | 14       | 0.3%    |
| Sony                                 | 13       | 0.28%   |
| Realtek Semiconductor                | 11       | 0.24%   |
| GYROCOM C&C                          | 11       | 0.24%   |
| VIA Technologies                     | 9        | 0.19%   |
| M-Audio                              | 9        | 0.19%   |
| Samson Technologies                  | 8        | 0.17%   |
| Turtle Beach                         | 7        | 0.15%   |
| SAVITECH                             | 7        | 0.15%   |
| RODE Microphones                     | 7        | 0.15%   |
| GN Netcom                            | 7        | 0.15%   |
| Giga-Byte Technology                 | 7        | 0.15%   |
| Yamaha                               | 6        | 0.13%   |
| XMOS                                 | 6        | 0.13%   |
| Dell                                 | 6        | 0.13%   |
| Valve Software                       | 5        | 0.11%   |
| Micro Star International             | 5        | 0.11%   |
| Elgato Systems                       | 5        | 0.11%   |
| Astro Gaming                         | 5        | 0.11%   |
| Thesycon Systemsoftware & Consulting | 4        | 0.09%   |
| Sennheiser Communications            | 4        | 0.09%   |
| ROCCAT                               | 4        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 408      | 7.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 291      | 5.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 229      | 4.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 160      | 2.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 158      | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 147      | 2.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 145      | 2.67%   |
| Intel 200 Series PCH HD Audio                                              | 130      | 2.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 124      | 2.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 116      | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 109      | 2.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 104      | 1.92%   |
| AMD Navi 10 HDMI Audio                                                     | 104      | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 103      | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 93       | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 90       | 1.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 71       | 1.31%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 68       | 1.25%   |
| Nvidia TU116 High Definition Audio Controller                              | 67       | 1.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 66       | 1.22%   |
| AMD FCH Azalia Controller                                                  | 66       | 1.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 65       | 1.2%    |
| Nvidia GM204 High Definition Audio Controller                              | 61       | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 61       | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 59       | 1.09%   |
| Nvidia TU104 HD Audio Controller                                           | 58       | 1.07%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 56       | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 53       | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 52       | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 51       | 0.94%   |
| Nvidia GM206 High Definition Audio Controller                              | 42       | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 42       | 0.77%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 42       | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 41       | 0.76%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 41       | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 40       | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 36       | 0.66%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 35       | 0.65%   |
| Nvidia GP102 HDMI Audio Controller                                         | 34       | 0.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 33       | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 291      | 18.55%  |
| Kingston                     | 285      | 18.16%  |
| G.Skill                      | 218      | 13.89%  |
| Unknown                      | 192      | 12.24%  |
| Crucial                      | 143      | 9.11%   |
| Samsung Electronics          | 88       | 5.61%   |
| SK hynix                     | 59       | 3.76%   |
| Micron Technology            | 47       | 3%      |
| Team                         | 40       | 2.55%   |
| A-DATA Technology            | 39       | 2.49%   |
| Patriot                      | 31       | 1.98%   |
| Nanya Technology             | 11       | 0.7%    |
| Goodram                      | 11       | 0.7%    |
| Unknown                      | 11       | 0.7%    |
| Elpida                       | 8        | 0.51%   |
| Unknown (ABCD)               | 7        | 0.45%   |
| Ramaxel Technology           | 7        | 0.45%   |
| Kllisre                      | 5        | 0.32%   |
| GeIL                         | 5        | 0.32%   |
| Transcend                    | 4        | 0.25%   |
| Smart                        | 4        | 0.25%   |
| Silicon Power                | 4        | 0.25%   |
| PNY                          | 4        | 0.25%   |
| AMD                          | 4        | 0.25%   |
| Kingmax                      | 3        | 0.19%   |
| CSX                          | 3        | 0.19%   |
| Apacer                       | 3        | 0.19%   |
| Unknown (08C8)               | 2        | 0.13%   |
| Qumo                         | 2        | 0.13%   |
| Patriot Memory (PDP Systems) | 2        | 0.13%   |
| Patriot Memory               | 2        | 0.13%   |
| Neo Forza                    | 2        | 0.13%   |
| Wilk Elektronik              | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (0xAD44594E45540000) | 1        | 0.06%   |
| Unknown (0x8551)             | 1        | 0.06%   |
| Unknown (0x0416)             | 1        | 0.06%   |
| TwinMOS                      | 1        | 0.06%   |
| Thermaltake                  | 1        | 0.06%   |
| TEXTORM                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 41       | 2.36%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s          | 31       | 1.79%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 20       | 1.15%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 20       | 1.15%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 17       | 0.98%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 16       | 0.92%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 16       | 0.92%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 14       | 0.81%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 14       | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 12       | 0.69%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 12       | 0.69%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 11       | 0.63%   |
| Unknown                                                        | 11       | 0.63%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 10       | 0.58%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 10       | 0.58%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 10       | 0.58%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                    | 10       | 0.58%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 9        | 0.52%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 9        | 0.52%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 9        | 0.52%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.52%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 9        | 0.52%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 8        | 0.46%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 8        | 0.46%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 8        | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 7        | 0.4%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 7        | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7        | 0.4%    |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s            | 7        | 0.4%    |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s            | 7        | 0.4%    |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s            | 7        | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 6        | 0.35%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 6        | 0.35%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s         | 6        | 0.35%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s            | 6        | 0.35%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s          | 6        | 0.35%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 6        | 0.35%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s         | 6        | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 5        | 0.29%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 5        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 822      | 58.26%  |
| DDR3    | 400      | 28.35%  |
| Unknown | 78       | 5.53%   |
| DDR2    | 41       | 2.91%   |
| SDRAM   | 38       | 2.69%   |
| DDR     | 12       | 0.85%   |
| DDR5    | 11       | 0.78%   |
| LPDDR4  | 7        | 0.5%    |
| LPDDR3  | 1        | 0.07%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1358     | 97.35%  |
| SODIMM  | 32       | 2.29%   |
| FB-DIMM | 3        | 0.22%   |
| RIMM    | 2        | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 680      | 44.5%   |
| 4096  | 315      | 20.62%  |
| 16384 | 277      | 18.13%  |
| 2048  | 141      | 9.23%   |
| 32768 | 70       | 4.58%   |
| 1024  | 40       | 2.62%   |
| 512   | 4        | 0.26%   |
| 3072  | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 225      | 14.38%  |
| 3200    | 192      | 12.27%  |
| 3600    | 164      | 10.48%  |
| 1333    | 139      | 8.88%   |
| 2400    | 92       | 5.88%   |
| 2667    | 71       | 4.54%   |
| 2133    | 70       | 4.47%   |
| 3466    | 55       | 3.51%   |
| 3400    | 54       | 3.45%   |
| 1867    | 52       | 3.32%   |
| 3000    | 50       | 3.19%   |
| 800     | 44       | 2.81%   |
| 3800    | 30       | 1.92%   |
| 1866    | 30       | 1.92%   |
| 667     | 28       | 1.79%   |
| 3866    | 26       | 1.66%   |
| 3733    | 25       | 1.6%    |
| 2933    | 19       | 1.21%   |
| 3266    | 16       | 1.02%   |
| Unknown | 16       | 1.02%   |
| 2666    | 15       | 0.96%   |
| 1066    | 14       | 0.89%   |
| 2800    | 13       | 0.83%   |
| 1800    | 11       | 0.7%    |
| 3666    | 10       | 0.64%   |
| 4800    | 7        | 0.45%   |
| 3334    | 6        | 0.38%   |
| 1334    | 6        | 0.38%   |
| 1067    | 5        | 0.32%   |
| 333     | 5        | 0.32%   |
| 3500    | 4        | 0.26%   |
| 3100    | 4        | 0.26%   |
| 2448    | 4        | 0.26%   |
| 2048    | 4        | 0.26%   |
| 1648    | 4        | 0.26%   |
| 533     | 4        | 0.26%   |
| 400     | 4        | 0.26%   |
| 49926   | 3        | 0.19%   |
| 4000    | 3        | 0.19%   |
| 3534    | 3        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 42       | 41.58%  |
| Brother Industries    | 19       | 18.81%  |
| Canon                 | 12       | 11.88%  |
| Seiko Epson           | 6        | 5.94%   |
| Samsung Electronics   | 6        | 5.94%   |
| Pantum                | 3        | 2.97%   |
| Xerox                 | 2        | 1.98%   |
| Ricoh                 | 2        | 1.98%   |
| Prolific Technology   | 2        | 1.98%   |
| Apple                 | 2        | 1.98%   |
| QinHeng Electronics   | 1        | 0.99%   |
| Oki Data              | 1        | 0.99%   |
| Lexmark International | 1        | 0.99%   |
| Graphtec America      | 1        | 0.99%   |
| Dymo-CoStar           | 1        | 0.99%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                     | 4        | 3.92%   |
| HP LaserJet 1300                             | 3        | 2.94%   |
| Xerox Phaser 3020                            | 2        | 1.96%   |
| Seiko Epson L120 Series                      | 2        | 1.96%   |
| Samsung ML-1640 Series Laser Printer         | 2        | 1.96%   |
| Prolific PL2305 Parallel Port                | 2        | 1.96%   |
| HP Officejet 2620 series                     | 2        | 1.96%   |
| HP DeskJet 4530 series                       | 2        | 1.96%   |
| HP DeskJet 2620 All-in-One Printer           | 2        | 1.96%   |
| HP DeskJet 2130 series                       | 2        | 1.96%   |
| HP Color LaserJet Pro M453-4                 | 2        | 1.96%   |
| Canon PIXMA MG2500 Series                    | 2        | 1.96%   |
| Canon MG5700 series                          | 2        | 1.96%   |
| Brother HL-5370DW series                     | 2        | 1.96%   |
| Brother DCP-7040                             | 2        | 1.96%   |
| Apple Gamesir-G3s 2.15                       | 2        | 1.96%   |
| Seiko Epson Stylus NX230/SX235W Series       | 1        | 0.98%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.98%   |
| Seiko Epson L805 Series                      | 1        | 0.98%   |
| Seiko Epson ET-4760 Series                   | 1        | 0.98%   |
| Seiko Epson ET-3850 Series                   | 1        | 0.98%   |
| Samsung ML-1660 Series                       | 1        | 0.98%   |
| Samsung M2020 Series                         | 1        | 0.98%   |
| Samsung CLX-3300 Series                      | 1        | 0.98%   |
| Samsung CLP-310 Color Laser Printer          | 1        | 0.98%   |
| Ricoh SP 112SU                               | 1        | 0.98%   |
| Ricoh Printing Support                       | 1        | 0.98%   |
| QinHeng CH340S                               | 1        | 0.98%   |
| Pantum P2500W series                         | 1        | 0.98%   |
| Pantum P2200 series                          | 1        | 0.98%   |
| Pantum M6500 series                          | 1        | 0.98%   |
| Oki Data USB Device                          | 1        | 0.98%   |
| Lexmark International Lexmark MS312dn        | 1        | 0.98%   |
| HP Smart Install                             | 1        | 0.98%   |
| HP OfficeJet Pro 8020 series                 | 1        | 0.98%   |
| HP LaserJet P2015 series                     | 1        | 0.98%   |
| HP Laserjet P1505                            | 1        | 0.98%   |
| HP LaserJet P1005                            | 1        | 0.98%   |
| HP LaserJet 200 colorMFP M276nw              | 1        | 0.98%   |
| HP LaserJet 1020                             | 1        | 0.98%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 12       | 52.17%  |
| Seiko Epson        | 5        | 21.74%  |
| Hewlett-Packard    | 2        | 8.7%    |
| Visioneer          | 1        | 4.35%   |
| Ultima Electronics | 1        | 4.35%   |
| Mustek Systems     | 1        | 4.35%   |
| AGFA-Gevaert NV    | 1        | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 17.39%  |
| Canon CanoScan LiDE 220                                                               | 3        | 13.04%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 8.7%    |
| Canon CanoScan LIDE 25                                                                | 2        | 8.7%    |
| Visioneer OneTouch 5300 USB                                                           | 1        | 4.35%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 4.35%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 4.35%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 4.35%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 4.35%   |
| HP ScanJet 3500c                                                                      | 1        | 4.35%   |
| HP ScanJet 3400cse                                                                    | 1        | 4.35%   |
| Canon CanoScan LiDE 90                                                                | 1        | 4.35%   |
| Canon CanoScan LiDE 210                                                               | 1        | 4.35%   |
| Canon CanoScan LiDE 120                                                               | 1        | 4.35%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 232      | 41.73%  |
| Microsoft                     | 46       | 8.27%   |
| Microdia                      | 44       | 7.91%   |
| Samsung Electronics           | 23       | 4.14%   |
| Z-Star Microelectronics       | 18       | 3.24%   |
| Sunplus Innovation Technology | 13       | 2.34%   |
| Creative Technology           | 11       | 1.98%   |
| Apple                         | 10       | 1.8%    |
| Generalplus Technology        | 8        | 1.44%   |
| Realtek Semiconductor         | 7        | 1.26%   |
| MacroSilicon                  | 7        | 1.26%   |
| GEMBIRD                       | 7        | 1.26%   |
| Cubeternet                    | 7        | 1.26%   |
| LG Electronics                | 6        | 1.08%   |
| Google                        | 6        | 1.08%   |
| Chicony Electronics           | 6        | 1.08%   |
| ARC International             | 6        | 1.08%   |
| Valve Software                | 5        | 0.9%    |
| Aveo Technology               | 5        | 0.9%    |
| KYE Systems (Mouse Systems)   | 4        | 0.72%   |
| Genesys Logic                 | 4        | 0.72%   |
| Alcor Micro                   | 4        | 0.72%   |
| Xiongmai                      | 3        | 0.54%   |
| Sonix Technology              | 3        | 0.54%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.54%   |
| Razer USA                     | 3        | 0.54%   |
| Pixart Imaging                | 3        | 0.54%   |
| Jieli Technology              | 3        | 0.54%   |
| Huawei Technologies           | 3        | 0.54%   |
| AVerMedia Technologies        | 3        | 0.54%   |
| Arkmicro Technologies         | 3        | 0.54%   |
| 2M UVC CAMERA                 | 3        | 0.54%   |
| WCM_USB                       | 2        | 0.36%   |
| WaveRider Communications      | 2        | 0.36%   |
| SJ-180517-N                   | 2        | 0.36%   |
| Silicon Motion                | 2        | 0.36%   |
| Philips (or NXP)              | 2        | 0.36%   |
| OPPO Electronics              | 2        | 0.36%   |
| Linux Foundation              | 2        | 0.36%   |
| Elgato Systems                | 2        | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 57       | 10.22%  |
| Logitech HD Pro Webcam C920                           | 42       | 7.53%   |
| Samsung Galaxy A5 (MTP)                               | 23       | 4.12%   |
| Microsoft LifeCam HD-3000                             | 21       | 3.76%   |
| Logitech C922 Pro Stream Webcam                       | 18       | 3.23%   |
| Microdia Webcam Vitade AF                             | 16       | 2.87%   |
| Z-Star Venus USB2.0 Camera                            | 10       | 1.79%   |
| Logitech Webcam C310                                  | 10       | 1.79%   |
| Logitech HD Webcam C615                               | 9        | 1.61%   |
| Logitech Webcam C170                                  | 8        | 1.43%   |
| Logitech HD Webcam C525                               | 8        | 1.43%   |
| Apple iPhone 5/5C/5S/6/SE                             | 8        | 1.43%   |
| Microdia CameraA                                      | 7        | 1.25%   |
| MacroSilicon USB Video                                | 7        | 1.25%   |
| Logitech Webcam C930e                                 | 7        | 1.25%   |
| Logitech C920 PRO HD Webcam                           | 7        | 1.25%   |
| Logitech BRIO Ultra HD Webcam                         | 7        | 1.25%   |
| Sunplus FHD Camera Microphone                         | 6        | 1.08%   |
| Microsoft LifeCam VX-2000                             | 6        | 1.08%   |
| Microdia USB 2.0 Camera                               | 6        | 1.08%   |
| Logitech StreamCam                                    | 6        | 1.08%   |
| Valve Software 3D Camera                              | 5        | 0.9%    |
| Logitech Webcam Pro 9000                              | 5        | 0.9%    |
| Logitech HD Webcam C910                               | 5        | 0.9%    |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 5        | 0.9%    |
| ARC International Camera                              | 5        | 0.9%    |
| Sunplus Full HD webcam                                | 4        | 0.72%   |
| Logitech HD Webcam C510                               | 4        | 0.72%   |
| Logitech BRIO 4K Stream Edition                       | 4        | 0.72%   |
| Logitech B525 HD Webcam                               | 4        | 0.72%   |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.72%   |
| Generalplus 808 Camera                                | 4        | 0.72%   |
| GEMBIRD USB2.0 PC CAMERA                              | 4        | 0.72%   |
| Creative Live! Cam Chat HD [VF0700]                   | 4        | 0.72%   |
| Z-Star Vimicro USB Camera (Altair)                    | 3        | 0.54%   |
| Xiongmai web camera                                   | 3        | 0.54%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960        | 3        | 0.54%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 3        | 0.54%   |
| Microsoft MicrosoftÂ LifeCam Studio                  | 3        | 0.54%   |
| Microsoft LifeCam VX-800                              | 3        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 42.86%  |
| STMicroelectronics    | 1        | 14.29%  |
| LighTuning Technology | 1        | 14.29%  |
| Futronic Technology   | 1        | 14.29%  |
| AuthenTec             | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 42.86%  |
| STMicroelectronics Fingerprint Reader       | 1        | 14.29%  |
| LighTuning Fingerprint Sensor               | 1        | 14.29%  |
| Futronic FS81 Fingerprint Scanner Module    | 1        | 14.29%  |
| AuthenTec AES1600                           | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 5        | 21.74%  |
| Alcor Micro                       | 5        | 21.74%  |
| VASCO Data Security International | 4        | 17.39%  |
| Realtek Semiconductor             | 4        | 17.39%  |
| OmniKey                           | 2        | 8.7%    |
| SCM Microsystems                  | 1        | 4.35%   |
| Cherry                            | 1        | 4.35%   |
| BIT4ID                            | 1        | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 5        | 21.74%  |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 17.39%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 17.39%  |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 8.7%    |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 8.7%    |
| VASCO Data Security International DIGIPASS 920                  | 1        | 4.35%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 4.35%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 4.35%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 4.35%   |
| BIT4ID miniLector EVO                                           | 1        | 4.35%   |
| Alcor Micro Watchdata W 1981                                    | 1        | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2086     | 85.95%  |
| 1     | 305      | 12.57%  |
| 2     | 33       | 1.36%   |
| 3     | 3        | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 143      | 39.61%  |
| Graphics card            | 50       | 13.85%  |
| Unassigned class         | 47       | 13.02%  |
| Camera                   | 19       | 5.26%   |
| Chipcard                 | 15       | 4.16%   |
| Net/ethernet             | 12       | 3.32%   |
| Multimedia controller    | 12       | 3.32%   |
| Sound                    | 11       | 3.05%   |
| Communication controller | 11       | 3.05%   |
| Bluetooth                | 10       | 2.77%   |
| Dvb card                 | 9        | 2.49%   |
| Storage/raid             | 6        | 1.66%   |
| Fingerprint reader       | 6        | 1.66%   |
| Network                  | 5        | 1.39%   |
| Storage/ide              | 2        | 0.55%   |
| Video                    | 1        | 0.28%   |
| Storage/ata              | 1        | 0.28%   |
| Storage                  | 1        | 0.28%   |

