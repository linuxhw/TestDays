Linux in Brazil - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 6009

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | N68-S3 FX                   | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | H61M-P31                    | [819c124b25](https://linux-hardware.org/?probe=819c124b25) | Nov 01, 2022 |
| VS Company    | G31T-M                      | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Pegatron      | 2AABh                       | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| MSI           | Z97 GAMING 3                | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [650f1fd648](https://linux-hardware.org/?probe=650f1fd648) | Oct 29, 2022 |
| ASUSTek       | PRIME H410M-K               | [5a371accfe](https://linux-hardware.org/?probe=5a371accfe) | Oct 29, 2022 |
| ASRock        | H510M-HVS                   | [e9ce2f5011](https://linux-hardware.org/?probe=e9ce2f5011) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| ASRock        | H510M-HVS                   | [e377db3a9e](https://linux-hardware.org/?probe=e377db3a9e) | Oct 28, 2022 |
| Lenovo        | 3102 NOK                    | [973ebfcf3e](https://linux-hardware.org/?probe=973ebfcf3e) | Oct 27, 2022 |
| ASRock        | H61M-VG4                    | [25b8826346](https://linux-hardware.org/?probe=25b8826346) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Intel         | H55                         | [fb3cf518ac](https://linux-hardware.org/?probe=fb3cf518ac) | Oct 27, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [9285fb0d9d](https://linux-hardware.org/?probe=9285fb0d9d) | Oct 27, 2022 |
| Acer          | Veriton M275                | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| ASUSTek       | P7H57D-V EVO                | [785405287b](https://linux-hardware.org/?probe=785405287b) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| PCWare        | IPMH61R3                    | [9f9410b99d](https://linux-hardware.org/?probe=9f9410b99d) | Oct 25, 2022 |
| Toshiba       | STI 005492G                 | [e7fccc3a84](https://linux-hardware.org/?probe=e7fccc3a84) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| ASRock        | H61M-VG4                    | [b393d57b17](https://linux-hardware.org/?probe=b393d57b17) | Oct 24, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [31cae2266e](https://linux-hardware.org/?probe=31cae2266e) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | [1e80f1de23](https://linux-hardware.org/?probe=1e80f1de23) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4540d714bc](https://linux-hardware.org/?probe=4540d714bc) | Oct 24, 2022 |
| Biostar       | A320MH                      | [b38eca2979](https://linux-hardware.org/?probe=b38eca2979) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| ASRock        | H81M-HG4 R4.0               | [da9c01eb20](https://linux-hardware.org/?probe=da9c01eb20) | Oct 23, 2022 |
| Gigabyte      | G41MT-S2P                   | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| Gigabyte      | A520M DS3H                  | [3faf4b3ca9](https://linux-hardware.org/?probe=3faf4b3ca9) | Oct 22, 2022 |
| Philco        | DTC-A55                     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| ASUSTek       | H81M-A/BR                   | [462091e8a8](https://linux-hardware.org/?probe=462091e8a8) | Oct 21, 2022 |
| MSI           | Z97 GAMING 3                | [2b5803628a](https://linux-hardware.org/?probe=2b5803628a) | Oct 20, 2022 |
| MSI           | Z97 GAMING 3                | [94c634f9b8](https://linux-hardware.org/?probe=94c634f9b8) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| Dell          | 0YXT71 A02                  | [137e154b2d](https://linux-hardware.org/?probe=137e154b2d) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | [d46ae4e597](https://linux-hardware.org/?probe=d46ae4e597) | Oct 19, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [c395183020](https://linux-hardware.org/?probe=c395183020) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | [e57ed46372](https://linux-hardware.org/?probe=e57ed46372) | Oct 19, 2022 |
| Dell          | 0XJ8C4 A00                  | [83da6e6509](https://linux-hardware.org/?probe=83da6e6509) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [d9b4d01e7f](https://linux-hardware.org/?probe=d9b4d01e7f) | Oct 18, 2022 |
| ASRock        | X670E Steel Legend          | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| ASRock        | B450M Steel Legend          | [6718ea22a9](https://linux-hardware.org/?probe=6718ea22a9) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| PCWare        | IPMH110G                    | [cde154a026](https://linux-hardware.org/?probe=cde154a026) | Oct 16, 2022 |
| Intel         | H55                         | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Dell          | 09KPNV A01                  | [5261790ba7](https://linux-hardware.org/?probe=5261790ba7) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [b966faf224](https://linux-hardware.org/?probe=b966faf224) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A               | [f13203e3ce](https://linux-hardware.org/?probe=f13203e3ce) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Toshiba       | STI 005492G                 | [e803b9bcf3](https://linux-hardware.org/?probe=e803b9bcf3) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Pegatron      | 2AD2A                       | [01827879c5](https://linux-hardware.org/?probe=01827879c5) | Oct 13, 2022 |
| ASRock        | N68-VS3 FX                  | [b271788734](https://linux-hardware.org/?probe=b271788734) | Oct 12, 2022 |
| Gigabyte      | 945GCM-S2C                  | [d0fe56248f](https://linux-hardware.org/?probe=d0fe56248f) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| PCWare        | IPMH110G                    | [2bcf719742](https://linux-hardware.org/?probe=2bcf719742) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| Unknown       | Unknown                     | [3414f3f4c0](https://linux-hardware.org/?probe=3414f3f4c0) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| Intel         | DH67CL AAG10212-206         | [01ebc77ef1](https://linux-hardware.org/?probe=01ebc77ef1) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | A320M-A PRO MAX             | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0085d792fd](https://linux-hardware.org/?probe=0085d792fd) | Oct 07, 2022 |
| MSI           | X370 SLI PLUS               | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Dell          | 09KPNV A01                  | [6ad101df29](https://linux-hardware.org/?probe=6ad101df29) | Oct 06, 2022 |
| MSI           | MEG Z390 GODLIKE            | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Intel         | B75                         | [a15b4ede9b](https://linux-hardware.org/?probe=a15b4ede9b) | Oct 05, 2022 |
| HP            | 2AA2                        | [e6bc6050b6](https://linux-hardware.org/?probe=e6bc6050b6) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Intel         | X99 V1.0                    | [d96984ac77](https://linux-hardware.org/?probe=d96984ac77) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [16f99421ab](https://linux-hardware.org/?probe=16f99421ab) | Oct 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9954860560](https://linux-hardware.org/?probe=9954860560) | Oct 04, 2022 |
| Intel         | H55                         | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6209CM1    | [15fb3b5261](https://linux-hardware.org/?probe=15fb3b5261) | Oct 02, 2022 |
| ASUSTek       | A78M-A                      | [91434dfd86](https://linux-hardware.org/?probe=91434dfd86) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [7309d377f6](https://linux-hardware.org/?probe=7309d377f6) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [aedfaab130](https://linux-hardware.org/?probe=aedfaab130) | Oct 02, 2022 |
| Positivo      | POS-PIH81DL                 | [c17fe23ea7](https://linux-hardware.org/?probe=c17fe23ea7) | Oct 01, 2022 |
| ASUSTek       | A78M-A                      | [5ad2e5f2a6](https://linux-hardware.org/?probe=5ad2e5f2a6) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | A320MH                      | [b07b6c4fc5](https://linux-hardware.org/?probe=b07b6c4fc5) | Oct 01, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Intel         | H61                         | [37af3b0cdb](https://linux-hardware.org/?probe=37af3b0cdb) | Sep 30, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [2c08befa41](https://linux-hardware.org/?probe=2c08befa41) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | [5cdce489b9](https://linux-hardware.org/?probe=5cdce489b9) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | [3bfbb3744e](https://linux-hardware.org/?probe=3bfbb3744e) | Sep 30, 2022 |
| ASRock        | A320M-HD                    | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| ASUSTek       | P5K Premium                 | [ec3962c685](https://linux-hardware.org/?probe=ec3962c685) | Sep 28, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [88f0d42935](https://linux-hardware.org/?probe=88f0d42935) | Sep 27, 2022 |
| Intel         | H55                         | [a155052bce](https://linux-hardware.org/?probe=a155052bce) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| ASUSTek       | P7H55-M LX                  | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Intel         | X99 V1.0                    | [7565f85860](https://linux-hardware.org/?probe=7565f85860) | Sep 24, 2022 |
| Unknown       | WZBTDT1 R110                | [8b6b5af31a](https://linux-hardware.org/?probe=8b6b5af31a) | Sep 24, 2022 |
| Gigabyte      | 970A-DS3P                   | [1e9a7dd793](https://linux-hardware.org/?probe=1e9a7dd793) | Sep 24, 2022 |
| ASUSTek       | M2N68                       | [4b23dadbca](https://linux-hardware.org/?probe=4b23dadbca) | Sep 23, 2022 |
| Foxconn       | Q77M                        | [63d0fe0c57](https://linux-hardware.org/?probe=63d0fe0c57) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASRock        | G31M-S                      | [76d9b33c76](https://linux-hardware.org/?probe=76d9b33c76) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| ASUSTek       | M2N68-AM SE2                | [412f70b76b](https://linux-hardware.org/?probe=412f70b76b) | Sep 23, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [fef79bcff4](https://linux-hardware.org/?probe=fef79bcff4) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Gigabyte      | 945GM-S2                    | [9fcea940e6](https://linux-hardware.org/?probe=9fcea940e6) | Sep 22, 2022 |
| OEM           | B75 Ver:1.41                | [e22d2bac17](https://linux-hardware.org/?probe=e22d2bac17) | Sep 22, 2022 |
| Intel         | DN2800MT AAG23738-801       | [0019b51cff](https://linux-hardware.org/?probe=0019b51cff) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | [ace83d527c](https://linux-hardware.org/?probe=ace83d527c) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [38234e238c](https://linux-hardware.org/?probe=38234e238c) | Sep 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | [54d0318e27](https://linux-hardware.org/?probe=54d0318e27) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | 0D883F A06                  | [55f97310c8](https://linux-hardware.org/?probe=55f97310c8) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| MSI           | A68HM-E33                   | [2905913e7e](https://linux-hardware.org/?probe=2905913e7e) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| PCWare        | IPMH110G                    | [6ba309be15](https://linux-hardware.org/?probe=6ba309be15) | Sep 18, 2022 |
| ASUSTek       | M4A785-M                    | [411449bc6d](https://linux-hardware.org/?probe=411449bc6d) | Sep 18, 2022 |
| Intel         | H61                         | [923e50e023](https://linux-hardware.org/?probe=923e50e023) | Sep 18, 2022 |
| MSI           | J1800I                      | [ff28c29a3e](https://linux-hardware.org/?probe=ff28c29a3e) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| Intel         | X79M-S                      | [91e75d3183](https://linux-hardware.org/?probe=91e75d3183) | Sep 17, 2022 |
| Intel         | X79M-S                      | [48c5f5ed77](https://linux-hardware.org/?probe=48c5f5ed77) | Sep 17, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Intel         | H61                         | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Unknown       | Unknown                     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME B350M-A               | [47b0975057](https://linux-hardware.org/?probe=47b0975057) | Sep 13, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | [70aa78efc6](https://linux-hardware.org/?probe=70aa78efc6) | Sep 13, 2022 |
| Positivo      | POS-PQ45AU                  | [0879f8d9ce](https://linux-hardware.org/?probe=0879f8d9ce) | Sep 13, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| PCWare        | IPMH61R3                    | [2312ab0f92](https://linux-hardware.org/?probe=2312ab0f92) | Sep 12, 2022 |
| Intel         | H61                         | [d805e24841](https://linux-hardware.org/?probe=d805e24841) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [aa4d90c7e7](https://linux-hardware.org/?probe=aa4d90c7e7) | Sep 11, 2022 |
| Dell          | 01XK1W A00                  | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [d79e449b58](https://linux-hardware.org/?probe=d79e449b58) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [1d6ec4fb3b](https://linux-hardware.org/?probe=1d6ec4fb3b) | Sep 10, 2022 |
| Intel         | Unknown                     | [74059aa424](https://linux-hardware.org/?probe=74059aa424) | Sep 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8d1d861b1c](https://linux-hardware.org/?probe=8d1d861b1c) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | [944fa39fb6](https://linux-hardware.org/?probe=944fa39fb6) | Sep 09, 2022 |
| Intel         | X79G V2.x                   | [8efdbea978](https://linux-hardware.org/?probe=8efdbea978) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | [c716a6bba5](https://linux-hardware.org/?probe=c716a6bba5) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Intel         | X99                         | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [4942b09228](https://linux-hardware.org/?probe=4942b09228) | Sep 08, 2022 |
| Intel         | D33217CK G76541-301         | [1f1e6e67ab](https://linux-hardware.org/?probe=1f1e6e67ab) | Sep 07, 2022 |
| Biostar       | G41D3C                      | [2825db69bf](https://linux-hardware.org/?probe=2825db69bf) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [f547e07cca](https://linux-hardware.org/?probe=f547e07cca) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [b1bdd1703e](https://linux-hardware.org/?probe=b1bdd1703e) | Sep 06, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f61f170b4c](https://linux-hardware.org/?probe=f61f170b4c) | Sep 06, 2022 |
| Intel         | H61                         | [b2d888f266](https://linux-hardware.org/?probe=b2d888f266) | Sep 05, 2022 |
| ASUSTek       | P5GZ-MX                     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [1f5b368c96](https://linux-hardware.org/?probe=1f5b368c96) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [078680a25d](https://linux-hardware.org/?probe=078680a25d) | Sep 04, 2022 |
| Intel         | DX58SO AAE29331-702         | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Intel         | H61                         | [af78b53f51](https://linux-hardware.org/?probe=af78b53f51) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| ASUSTek       | PRIME Z270-A                | [e742b2e06c](https://linux-hardware.org/?probe=e742b2e06c) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ECS           | H61H2-M2                    | [11dd923e56](https://linux-hardware.org/?probe=11dd923e56) | Sep 02, 2022 |
| Intel         | DP55WB AAE64798-206         | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| AMI           | T3 MRD                      | [d0a254e1b7](https://linux-hardware.org/?probe=d0a254e1b7) | Sep 02, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [9525064f53](https://linux-hardware.org/?probe=9525064f53) | Sep 02, 2022 |
| Lenovo        | 3168 NOK                    | [58c82b01e2](https://linux-hardware.org/?probe=58c82b01e2) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [ea730c9b2d](https://linux-hardware.org/?probe=ea730c9b2d) | Sep 01, 2022 |
| ASRock        | B550M-ITX/ac                | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Gigabyte      | VM900M                      | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| ASUSTek       | ROG Maximus XII EXTREME     | [a77d5e141e](https://linux-hardware.org/?probe=a77d5e141e) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c7ace10271](https://linux-hardware.org/?probe=c7ace10271) | Aug 28, 2022 |
| Gigabyte      | F2A68HM-S1                  | [420036f4d6](https://linux-hardware.org/?probe=420036f4d6) | Aug 28, 2022 |
| MSI           | B560M PRO-VDH               | [d8a638184b](https://linux-hardware.org/?probe=d8a638184b) | Aug 28, 2022 |
| Intel         | H61                         | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| Gigabyte      | H61M-S1                     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7642980e6e](https://linux-hardware.org/?probe=7642980e6e) | Aug 27, 2022 |
| Dell          | 01XK1W A00                  | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [da0b51aa63](https://linux-hardware.org/?probe=da0b51aa63) | Aug 25, 2022 |
| MSI           | B560M PRO-VDH               | [437118237f](https://linux-hardware.org/?probe=437118237f) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| OEM           | A320                        | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| HP            | 3397                        | [f65d0fdb85](https://linux-hardware.org/?probe=f65d0fdb85) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| AMI           | Cherry Trail Tablet         | [8cdf70d6e3](https://linux-hardware.org/?probe=8cdf70d6e3) | Aug 23, 2022 |
| ASUSTek       | P5KPL-CM                    | [53a4b425d3](https://linux-hardware.org/?probe=53a4b425d3) | Aug 22, 2022 |
| ASUSTek       | PRIME H410M-E               | [5270930555](https://linux-hardware.org/?probe=5270930555) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Unknown       | GSUO H61V10C                | [1e7ccd0999](https://linux-hardware.org/?probe=1e7ccd0999) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASRock        | X370 Taichi                 | [8f952ff258](https://linux-hardware.org/?probe=8f952ff258) | Aug 21, 2022 |
| Intel         | DH61WW AAG23116-203         | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| Biostar       | G31-M7 TE                   | [aaacebef4a](https://linux-hardware.org/?probe=aaacebef4a) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Gigabyte      | B75M-D3H                    | [6503feb8b7](https://linux-hardware.org/?probe=6503feb8b7) | Aug 20, 2022 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [2e1445b2c8](https://linux-hardware.org/?probe=2e1445b2c8) | Aug 19, 2022 |
| Dell          | 0TVR1F A01                  | [1b8906bb20](https://linux-hardware.org/?probe=1b8906bb20) | Aug 19, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [ffb095f0c3](https://linux-hardware.org/?probe=ffb095f0c3) | Aug 19, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Arquimedes... | 760GM                       | [5f653afdff](https://linux-hardware.org/?probe=5f653afdff) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4242f8b9c2](https://linux-hardware.org/?probe=4242f8b9c2) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [bac870dd75](https://linux-hardware.org/?probe=bac870dd75) | Aug 18, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [52b9313de4](https://linux-hardware.org/?probe=52b9313de4) | Aug 18, 2022 |
| Intel         | Unknown                     | [23f3bdae8a](https://linux-hardware.org/?probe=23f3bdae8a) | Aug 18, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| ASRock        | AB350M-HDV                  | [3e3ab3842f](https://linux-hardware.org/?probe=3e3ab3842f) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Intel         | B75                         | [8eb918ea53](https://linux-hardware.org/?probe=8eb918ea53) | Aug 16, 2022 |
| Gigabyte      | B550M DS3H                  | [6ef5e022c7](https://linux-hardware.org/?probe=6ef5e022c7) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| ASRock        | B450M Steel Legend          | [1e198f7c54](https://linux-hardware.org/?probe=1e198f7c54) | Aug 15, 2022 |
| ASRock        | FM2A55M-HD+                 | [dc086ed32c](https://linux-hardware.org/?probe=dc086ed32c) | Aug 14, 2022 |
| ASUSTek       | P8H61-M LX3                 | [7c37c2a6d7](https://linux-hardware.org/?probe=7c37c2a6d7) | Aug 14, 2022 |
| ASRock        | FM2A55M-HD+                 | [6c7f56d3cd](https://linux-hardware.org/?probe=6c7f56d3cd) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [4443a6c129](https://linux-hardware.org/?probe=4443a6c129) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [082a5297bd](https://linux-hardware.org/?probe=082a5297bd) | Aug 14, 2022 |
| Gigabyte      | Z77M-D3H                    | [15633ed7b1](https://linux-hardware.org/?probe=15633ed7b1) | Aug 14, 2022 |
| Biostar       | G31-M7 TE                   | [c5737e52bd](https://linux-hardware.org/?probe=c5737e52bd) | Aug 14, 2022 |
| ASUSTek       | Z97-A                       | [14fa58515f](https://linux-hardware.org/?probe=14fa58515f) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [f17b91fcb8](https://linux-hardware.org/?probe=f17b91fcb8) | Aug 13, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [98cc4a3075](https://linux-hardware.org/?probe=98cc4a3075) | Aug 12, 2022 |
| Gigabyte      | H61M-S1                     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| MSI           | X370 SLI PLUS               | [8b4bc6f127](https://linux-hardware.org/?probe=8b4bc6f127) | Aug 11, 2022 |
| Foxconn       | 2ADA                        | [9aae49b54c](https://linux-hardware.org/?probe=9aae49b54c) | Aug 11, 2022 |
| Gigabyte      | G31M-S2C                    | [3f67c470be](https://linux-hardware.org/?probe=3f67c470be) | Aug 11, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [c66de39c4c](https://linux-hardware.org/?probe=c66de39c4c) | Aug 11, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [d081204e0a](https://linux-hardware.org/?probe=d081204e0a) | Aug 10, 2022 |
| Foxconn       | 2ABF                        | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e54e09e3cf](https://linux-hardware.org/?probe=e54e09e3cf) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a84fd5a16](https://linux-hardware.org/?probe=5a84fd5a16) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Intel         | H61                         | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [aada9001dd](https://linux-hardware.org/?probe=aada9001dd) | Aug 08, 2022 |
| HP            | 1998                        | [1ae818eb7c](https://linux-hardware.org/?probe=1ae818eb7c) | Aug 07, 2022 |
| Toshiba       | STI 006998G                 | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| PCWare        | IPX3060E                    | [3fc0886f3b](https://linux-hardware.org/?probe=3fc0886f3b) | Aug 06, 2022 |
| Gigabyte      | F2A55M-S1                   | [cf3ed2131f](https://linux-hardware.org/?probe=cf3ed2131f) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [169fcf7943](https://linux-hardware.org/?probe=169fcf7943) | Aug 05, 2022 |
| Gigabyte      | AX370-Gaming 5              | [46f109ed37](https://linux-hardware.org/?probe=46f109ed37) | Aug 05, 2022 |
| PCWare        | IPX3060E                    | [d5045f1364](https://linux-hardware.org/?probe=d5045f1364) | Aug 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [2030bc92d7](https://linux-hardware.org/?probe=2030bc92d7) | Aug 04, 2022 |
| MSI           | Boston                      | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| Biostar       | G41D3C                      | [8a5b81e472](https://linux-hardware.org/?probe=8a5b81e472) | Aug 03, 2022 |
| HP            | 3047h                       | [a8301b8155](https://linux-hardware.org/?probe=a8301b8155) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| PCWare        | IPMH61R1                    | [0843909534](https://linux-hardware.org/?probe=0843909534) | Aug 01, 2022 |
| PCWare        | IPMH61R1                    | [7da7204a12](https://linux-hardware.org/?probe=7da7204a12) | Jul 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [16f64b6f1a](https://linux-hardware.org/?probe=16f64b6f1a) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ECS           | H61H2-M12                   | [6761a8774d](https://linux-hardware.org/?probe=6761a8774d) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f6ecfb2a51](https://linux-hardware.org/?probe=f6ecfb2a51) | Jul 30, 2022 |
| MSI           | A320M-A PRO MAX             | [3249abb411](https://linux-hardware.org/?probe=3249abb411) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7ceff6f032](https://linux-hardware.org/?probe=7ceff6f032) | Jul 30, 2022 |
| MSI           | A320M-A PRO MAX             | [5a750a1294](https://linux-hardware.org/?probe=5a750a1294) | Jul 30, 2022 |
| HP            | 3047h                       | [a9b59b34f9](https://linux-hardware.org/?probe=a9b59b34f9) | Jul 29, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [8c57fbc9e8](https://linux-hardware.org/?probe=8c57fbc9e8) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [51893f2237](https://linux-hardware.org/?probe=51893f2237) | Jul 29, 2022 |
| Intel         | H61                         | [7bb7deaca9](https://linux-hardware.org/?probe=7bb7deaca9) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Digiboard     | NM70-TI                     | [007a69093c](https://linux-hardware.org/?probe=007a69093c) | Jul 29, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [e84f999c94](https://linux-hardware.org/?probe=e84f999c94) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-GAMING II       | [0cc1bc9401](https://linux-hardware.org/?probe=0cc1bc9401) | Jul 29, 2022 |
| Biostar       | B350GTN                     | [75d6302ab0](https://linux-hardware.org/?probe=75d6302ab0) | Jul 29, 2022 |
| Pegatron      | IPM41-D3                    | [ce24b0bab7](https://linux-hardware.org/?probe=ce24b0bab7) | Jul 28, 2022 |
| Positivo      | POS-RIB360EE 11158935       | [1c687dcef7](https://linux-hardware.org/?probe=1c687dcef7) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| Intel         | X99 V1.0                    | [da677f5a3b](https://linux-hardware.org/?probe=da677f5a3b) | Jul 28, 2022 |
| Intel         | B75                         | [0620ffff20](https://linux-hardware.org/?probe=0620ffff20) | Jul 27, 2022 |
| MSI           | X470 GAMING PLUS            | [722aa0951d](https://linux-hardware.org/?probe=722aa0951d) | Jul 27, 2022 |
| PCWare        | IPMH61R1                    | [18610dd9f0](https://linux-hardware.org/?probe=18610dd9f0) | Jul 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [32e82dc9ae](https://linux-hardware.org/?probe=32e82dc9ae) | Jul 27, 2022 |
| PCWare        | PW-945GCX                   | [128aafe763](https://linux-hardware.org/?probe=128aafe763) | Jul 27, 2022 |
| MSI           | 2A9C                        | [de5a8c7ecd](https://linux-hardware.org/?probe=de5a8c7ecd) | Jul 27, 2022 |
| Dell          | 01XK1W A00                  | [68159d9d39](https://linux-hardware.org/?probe=68159d9d39) | Jul 26, 2022 |
| Huanan        | X99-F8                      | [3ba1885fb4](https://linux-hardware.org/?probe=3ba1885fb4) | Jul 26, 2022 |
| Gigabyte      | Z370N WIFI-CF               | [eb3c3fceb3](https://linux-hardware.org/?probe=eb3c3fceb3) | Jul 26, 2022 |
| ASRock        | B450M Steel Legend          | [30fd52a2a5](https://linux-hardware.org/?probe=30fd52a2a5) | Jul 26, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [e471e3ed10](https://linux-hardware.org/?probe=e471e3ed10) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASRock        | H61M-DGS                    | [0dc55c5b73](https://linux-hardware.org/?probe=0dc55c5b73) | Jul 24, 2022 |
| ASUSTek       | Z87M-PLUS                   | [0efc94e34d](https://linux-hardware.org/?probe=0efc94e34d) | Jul 24, 2022 |
| PCWare        | IPX1800E2                   | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| Intel         | DH61WW AAG23116-203         | [cfd6e87e09](https://linux-hardware.org/?probe=cfd6e87e09) | Jul 23, 2022 |
| Dell          | 01XK1W A00                  | [5c8a6b6f90](https://linux-hardware.org/?probe=5c8a6b6f90) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | [c30806c628](https://linux-hardware.org/?probe=c30806c628) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | [b805fa0cd8](https://linux-hardware.org/?probe=b805fa0cd8) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-K               | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [edcecb5e13](https://linux-hardware.org/?probe=edcecb5e13) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f90d74f5b5](https://linux-hardware.org/?probe=f90d74f5b5) | Jul 22, 2022 |
| Dell          | 01XK1W A00                  | [91ce7c78ee](https://linux-hardware.org/?probe=91ce7c78ee) | Jul 22, 2022 |
| ASUSTek       | P7H55-M                     | [d7ba204d31](https://linux-hardware.org/?probe=d7ba204d31) | Jul 22, 2022 |
| ASUSTek       | M2N68                       | [e8b27563a2](https://linux-hardware.org/?probe=e8b27563a2) | Jul 22, 2022 |
| Biostar       | B450MH                      | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar       | B450MH                      | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [2af5596c9e](https://linux-hardware.org/?probe=2af5596c9e) | Jul 21, 2022 |
| ASRock        | H81M-HG4 R4.0               | [4628e310fd](https://linux-hardware.org/?probe=4628e310fd) | Jul 20, 2022 |
| ECS           | H61H2-M2                    | [c1d1e739cf](https://linux-hardware.org/?probe=c1d1e739cf) | Jul 20, 2022 |
| PCChips       | A15G                        | [4cdd689308](https://linux-hardware.org/?probe=4cdd689308) | Jul 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [e0ffe80869](https://linux-hardware.org/?probe=e0ffe80869) | Jul 20, 2022 |
| Intel         | Unknown                     | [19327f830a](https://linux-hardware.org/?probe=19327f830a) | Jul 20, 2022 |
| Positivo      | POS-PIQ77CL                 | [ce9a0fdbbc](https://linux-hardware.org/?probe=ce9a0fdbbc) | Jul 20, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [a6f87d56db](https://linux-hardware.org/?probe=a6f87d56db) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Intel         | Unknown                     | [8c87f55927](https://linux-hardware.org/?probe=8c87f55927) | Jul 19, 2022 |
| ECS           | A990FXM-A                   | [6351c9023d](https://linux-hardware.org/?probe=6351c9023d) | Jul 19, 2022 |
| MSI           | G31M3-L V2                  | [cd6d617e34](https://linux-hardware.org/?probe=cd6d617e34) | Jul 19, 2022 |
| MSI           | G31M3-L V2                  | [aaa3013f66](https://linux-hardware.org/?probe=aaa3013f66) | Jul 18, 2022 |
| Intel         | H55                         | [b58f7300e1](https://linux-hardware.org/?probe=b58f7300e1) | Jul 18, 2022 |
| Gigabyte      | H61M-S2PH                   | [554f6e65ed](https://linux-hardware.org/?probe=554f6e65ed) | Jul 18, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [39fd39c3b0](https://linux-hardware.org/?probe=39fd39c3b0) | Jul 17, 2022 |
| Dell          | 08NPPY A00                  | [23d9101cd2](https://linux-hardware.org/?probe=23d9101cd2) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | [f8585ad958](https://linux-hardware.org/?probe=f8585ad958) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | [f2372286e0](https://linux-hardware.org/?probe=f2372286e0) | Jul 17, 2022 |
| Huanan        | B75                         | [0580a5a948](https://linux-hardware.org/?probe=0580a5a948) | Jul 17, 2022 |
| Huanan        | B75                         | [e1788853ec](https://linux-hardware.org/?probe=e1788853ec) | Jul 17, 2022 |
| GALAX         | A320M Ver1.0 G10f           | [7bc0a0fe3a](https://linux-hardware.org/?probe=7bc0a0fe3a) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Dell          | 0F428D A00                  | [fb8a6009f7](https://linux-hardware.org/?probe=fb8a6009f7) | Jul 16, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [34a905d705](https://linux-hardware.org/?probe=34a905d705) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| Intel         | H61                         | [8865d7959a](https://linux-hardware.org/?probe=8865d7959a) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| Intel         | H55                         | [f8e7b20a53](https://linux-hardware.org/?probe=f8e7b20a53) | Jul 14, 2022 |
| ASUSTek       | P8B75-M LE                  | [a4246a1ea8](https://linux-hardware.org/?probe=a4246a1ea8) | Jul 14, 2022 |
| ASUSTek       | M5A97 PRO                   | [e963ba85db](https://linux-hardware.org/?probe=e963ba85db) | Jul 14, 2022 |
| Intel         | H55                         | [b199ed9707](https://linux-hardware.org/?probe=b199ed9707) | Jul 14, 2022 |
| Gigabyte      | Z690 GAMING X               | [7babf837f9](https://linux-hardware.org/?probe=7babf837f9) | Jul 14, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [eebcfac8a3](https://linux-hardware.org/?probe=eebcfac8a3) | Jul 14, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [4355281f8e](https://linux-hardware.org/?probe=4355281f8e) | Jul 13, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [36f96a4ef6](https://linux-hardware.org/?probe=36f96a4ef6) | Jul 13, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [44638b5241](https://linux-hardware.org/?probe=44638b5241) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| Dell          | 02YYK5 A00                  | [6592ae8873](https://linux-hardware.org/?probe=6592ae8873) | Jul 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8739a403bc](https://linux-hardware.org/?probe=8739a403bc) | Jul 11, 2022 |
| Positivo      | POS-MI945AA                 | [ab451b5409](https://linux-hardware.org/?probe=ab451b5409) | Jul 11, 2022 |
| ASUSTek       | H81M-A/BR                   | [851a8e12f8](https://linux-hardware.org/?probe=851a8e12f8) | Jul 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [012a999377](https://linux-hardware.org/?probe=012a999377) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ee629832da](https://linux-hardware.org/?probe=ee629832da) | Jul 09, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [8ac6704c06](https://linux-hardware.org/?probe=8ac6704c06) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| PCWare        | IPX4005G                    | [2e447eb751](https://linux-hardware.org/?probe=2e447eb751) | Jul 09, 2022 |
| ASRock        | A320M-HDV R4.0              | [a39b9bab73](https://linux-hardware.org/?probe=a39b9bab73) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| MSI           | 2A9C                        | [40457980de](https://linux-hardware.org/?probe=40457980de) | Jul 08, 2022 |
| Positivo      | POS-PIQ77CL                 | [1a40c954fc](https://linux-hardware.org/?probe=1a40c954fc) | Jul 08, 2022 |
| congatec      | TS170 B.0                   | [b9469e26f8](https://linux-hardware.org/?probe=b9469e26f8) | Jul 06, 2022 |
| MSI           | Boston                      | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| ASUSTek       | H110M-E/M.2                 | [cfe354b7b2](https://linux-hardware.org/?probe=cfe354b7b2) | Jul 06, 2022 |
| Positivo      | POS-MIG31AG                 | [3a03195633](https://linux-hardware.org/?probe=3a03195633) | Jul 06, 2022 |
| Gigabyte      | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f5e7afea43](https://linux-hardware.org/?probe=f5e7afea43) | Jul 05, 2022 |
| Intel         | H61                         | [da6d35599a](https://linux-hardware.org/?probe=da6d35599a) | Jul 04, 2022 |
| HP            | 3048h                       | [a007a37d76](https://linux-hardware.org/?probe=a007a37d76) | Jul 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [729fab1a51](https://linux-hardware.org/?probe=729fab1a51) | Jul 04, 2022 |
| ECS           | H61H2-M12                   | [e450395aeb](https://linux-hardware.org/?probe=e450395aeb) | Jul 04, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [eb89cf02af](https://linux-hardware.org/?probe=eb89cf02af) | Jul 03, 2022 |
| Positivo      | POS-EIH61CE POSITIVO        | [2d040c142f](https://linux-hardware.org/?probe=2d040c142f) | Jul 03, 2022 |
| Positivo      | POS-EIH61CE POSITIVO        | [bc149c173f](https://linux-hardware.org/?probe=bc149c173f) | Jul 03, 2022 |
| ECS           | H61H2-M12                   | [33b81dcd60](https://linux-hardware.org/?probe=33b81dcd60) | Jul 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [a746300279](https://linux-hardware.org/?probe=a746300279) | Jul 03, 2022 |
| ASRock        | N68-VS3 UCC                 | [dd43bf961c](https://linux-hardware.org/?probe=dd43bf961c) | Jul 02, 2022 |
| Pegatron      | IPM41-D3                    | [a7cc8d2654](https://linux-hardware.org/?probe=a7cc8d2654) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [2f0ac248ed](https://linux-hardware.org/?probe=2f0ac248ed) | Jul 01, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [5a6d827ebe](https://linux-hardware.org/?probe=5a6d827ebe) | Jul 01, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [a40fb66860](https://linux-hardware.org/?probe=a40fb66860) | Jun 30, 2022 |
| ASUSTek       | B85M-E/BR                   | [adfbbd03b6](https://linux-hardware.org/?probe=adfbbd03b6) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [3bceb0a396](https://linux-hardware.org/?probe=3bceb0a396) | Jun 29, 2022 |
| PCWare        | IPMH61R3                    | [492951e8cf](https://linux-hardware.org/?probe=492951e8cf) | Jun 29, 2022 |
| Gigabyte      | H81M-S1                     | [6dfee96211](https://linux-hardware.org/?probe=6dfee96211) | Jun 29, 2022 |
| Intel         | DP43BF AAE78171-302         | [0115160101](https://linux-hardware.org/?probe=0115160101) | Jun 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [a9ddf668c4](https://linux-hardware.org/?probe=a9ddf668c4) | Jun 28, 2022 |
| ASUSTek       | P5KPL-AM                    | [f9a3a492d9](https://linux-hardware.org/?probe=f9a3a492d9) | Jun 27, 2022 |
| Dell          | 0J3C2F A03                  | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| ASRock        | N68-VS3 UCC                 | [2c7959c607](https://linux-hardware.org/?probe=2c7959c607) | Jun 26, 2022 |
| ASUSTek       | PRIME H410M-E               | [3eb97735b3](https://linux-hardware.org/?probe=3eb97735b3) | Jun 26, 2022 |
| MSI           | H55M-E33                    | [035cfe1a5b](https://linux-hardware.org/?probe=035cfe1a5b) | Jun 26, 2022 |
| Intel         | X99                         | [4322217bc5](https://linux-hardware.org/?probe=4322217bc5) | Jun 26, 2022 |
| ASUSTek       | PRIME Z270-A                | [8c2de24375](https://linux-hardware.org/?probe=8c2de24375) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [fc35cfc7f6](https://linux-hardware.org/?probe=fc35cfc7f6) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [8f2b511688](https://linux-hardware.org/?probe=8f2b511688) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ace55b44d7](https://linux-hardware.org/?probe=ace55b44d7) | Jun 25, 2022 |
| Intel         | X99 V1.0                    | [17e64443b0](https://linux-hardware.org/?probe=17e64443b0) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Intel         | H61                         | [e5a2c316f3](https://linux-hardware.org/?probe=e5a2c316f3) | Jun 24, 2022 |
| Intel         | H61                         | [d3b87d18d8](https://linux-hardware.org/?probe=d3b87d18d8) | Jun 24, 2022 |
| Intel         | H55                         | [853a94f10d](https://linux-hardware.org/?probe=853a94f10d) | Jun 23, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [c44391986b](https://linux-hardware.org/?probe=c44391986b) | Jun 23, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [167acd417b](https://linux-hardware.org/?probe=167acd417b) | Jun 23, 2022 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [da57ce522d](https://linux-hardware.org/?probe=da57ce522d) | Jun 23, 2022 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [3747f62fa6](https://linux-hardware.org/?probe=3747f62fa6) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [914da7c9a4](https://linux-hardware.org/?probe=914da7c9a4) | Jun 23, 2022 |
| ASUSTek       | PRIME Z270-A                | [463b7612de](https://linux-hardware.org/?probe=463b7612de) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [836efa773c](https://linux-hardware.org/?probe=836efa773c) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [380b66353e](https://linux-hardware.org/?probe=380b66353e) | Jun 21, 2022 |
| PCWare        | IPMH61R1                    | [130bb25912](https://linux-hardware.org/?probe=130bb25912) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| ASUSTek       | M2NPV-VM                    | [818e78cbe0](https://linux-hardware.org/?probe=818e78cbe0) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASUSTek       | M5A97 PLUS                  | [bef449f943](https://linux-hardware.org/?probe=bef449f943) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [a0d16e2b3c](https://linux-hardware.org/?probe=a0d16e2b3c) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3fad3e1c0b](https://linux-hardware.org/?probe=3fad3e1c0b) | Jun 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | [6446ac4750](https://linux-hardware.org/?probe=6446ac4750) | Jun 18, 2022 |
| Dell          | 0D883F A06                  | [6296a553c6](https://linux-hardware.org/?probe=6296a553c6) | Jun 18, 2022 |
| T-bao         | MINI PC                     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| Intel         | H61                         | [358da63cbc](https://linux-hardware.org/?probe=358da63cbc) | Jun 18, 2022 |
| ASUSTek       | H110M-CS/BR                 | [35cfc3daf7](https://linux-hardware.org/?probe=35cfc3daf7) | Jun 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [494419a571](https://linux-hardware.org/?probe=494419a571) | Jun 17, 2022 |
| ASUSTek       | H110M-CS/BR                 | [47e88dae48](https://linux-hardware.org/?probe=47e88dae48) | Jun 17, 2022 |
| ASUSTek       | H110M-CS/BR                 | [772bf458a3](https://linux-hardware.org/?probe=772bf458a3) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Dell          | 01XK1W A00                  | [f73ae16c57](https://linux-hardware.org/?probe=f73ae16c57) | Jun 16, 2022 |
| ECS           | 945GZ/CT-M                  | [ca6bdad27e](https://linux-hardware.org/?probe=ca6bdad27e) | Jun 15, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [e61344b416](https://linux-hardware.org/?probe=e61344b416) | Jun 14, 2022 |
| ASRock        | B75M-DGS R2.0               | [457047ad06](https://linux-hardware.org/?probe=457047ad06) | Jun 13, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f3cb75acef](https://linux-hardware.org/?probe=f3cb75acef) | Jun 13, 2022 |
| Intel         | DH61CR AAG14064-207         | [a840bbb5a3](https://linux-hardware.org/?probe=a840bbb5a3) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| Unknown       | X99-GT                      | [6a36412f6d](https://linux-hardware.org/?probe=6a36412f6d) | Jun 12, 2022 |
| Unknown       | X99-GT                      | [0e1115fdc9](https://linux-hardware.org/?probe=0e1115fdc9) | Jun 12, 2022 |
| Biostar       | B450MX-S                    | [be9e9c5a99](https://linux-hardware.org/?probe=be9e9c5a99) | Jun 11, 2022 |
| MSI           | 2A9C                        | [c2007961e1](https://linux-hardware.org/?probe=c2007961e1) | Jun 11, 2022 |
| Intel         | H61                         | [bf862f44d2](https://linux-hardware.org/?probe=bf862f44d2) | Jun 11, 2022 |
| Dell          | 0TDG4V A01                  | [3da09dbe5d](https://linux-hardware.org/?probe=3da09dbe5d) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [ec2e52372f](https://linux-hardware.org/?probe=ec2e52372f) | Jun 10, 2022 |
| PCWare        | IPX4105G Pro                | [72ac2cedad](https://linux-hardware.org/?probe=72ac2cedad) | Jun 10, 2022 |
| ASUSTek       | P8P67-M                     | [619b49a078](https://linux-hardware.org/?probe=619b49a078) | Jun 10, 2022 |
| ASRock        | B450M Steel Legend          | [9744f09d7e](https://linux-hardware.org/?probe=9744f09d7e) | Jun 09, 2022 |
| ASRock        | B450M Steel Legend          | [75510afde6](https://linux-hardware.org/?probe=75510afde6) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d0fa25e5f0](https://linux-hardware.org/?probe=d0fa25e5f0) | Jun 08, 2022 |
| Gigabyte      | 970A-DS3P                   | [a68fb9489c](https://linux-hardware.org/?probe=a68fb9489c) | Jun 08, 2022 |
| HP            | 1998                        | [362416dfc1](https://linux-hardware.org/?probe=362416dfc1) | Jun 08, 2022 |
| PCWare        | IPX4105G Pro                | [ffccee6734](https://linux-hardware.org/?probe=ffccee6734) | Jun 07, 2022 |
| ASUSTek       | Maximus VII HERO            | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| ASRock        | H110M-HG4                   | [a25254d5c3](https://linux-hardware.org/?probe=a25254d5c3) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [f23f59523b](https://linux-hardware.org/?probe=f23f59523b) | Jun 07, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [2e5071518f](https://linux-hardware.org/?probe=2e5071518f) | Jun 07, 2022 |
| Kllisre       | B75 V1.1                    | [d9a9aa6243](https://linux-hardware.org/?probe=d9a9aa6243) | Jun 06, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Gigabyte      | H81M-S1                     | [6a2b3dfc3e](https://linux-hardware.org/?probe=6a2b3dfc3e) | Jun 06, 2022 |
| OEM           | H110                        | [d9bb28c841](https://linux-hardware.org/?probe=d9bb28c841) | Jun 05, 2022 |
| Dell          | 0YXT71 A02                  | [4dd5ceef26](https://linux-hardware.org/?probe=4dd5ceef26) | Jun 05, 2022 |
| MSI           | B85M-E45                    | [4446978a6f](https://linux-hardware.org/?probe=4446978a6f) | Jun 04, 2022 |
| Positivo      | POS-PIH55BO                 | [cffe8043b8](https://linux-hardware.org/?probe=cffe8043b8) | Jun 04, 2022 |
| HP            | 3029h                       | [6bbd8d0ebe](https://linux-hardware.org/?probe=6bbd8d0ebe) | Jun 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | PRIME Z270-A                | [5b481a2d9f](https://linux-hardware.org/?probe=5b481a2d9f) | Jun 02, 2022 |
| ASRock        | 760GM-HDV                   | [b72f6362e5](https://linux-hardware.org/?probe=b72f6362e5) | Jun 02, 2022 |
| ASUSTek       | PRIME Z270-A                | [d1cd1862cf](https://linux-hardware.org/?probe=d1cd1862cf) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASRock        | H81M-HG4 R4.0               | [2a09c108e5](https://linux-hardware.org/?probe=2a09c108e5) | Jun 02, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [0d91ffc3e9](https://linux-hardware.org/?probe=0d91ffc3e9) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [6190087942](https://linux-hardware.org/?probe=6190087942) | Jun 01, 2022 |
| Dell          | 0NK5PH A00                  | [960e8817bf](https://linux-hardware.org/?probe=960e8817bf) | Jun 01, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| Intel         | H61                         | [7f87ff703e](https://linux-hardware.org/?probe=7f87ff703e) | May 30, 2022 |
| Intel         | DG43GT AAE62768-300         | [643ebac3b3](https://linux-hardware.org/?probe=643ebac3b3) | May 29, 2022 |
| ASRock        | A320M-HD                    | [b9b89a0256](https://linux-hardware.org/?probe=b9b89a0256) | May 29, 2022 |
| ASUSTek       | AM1M-A/BR                   | [c8532fbb66](https://linux-hardware.org/?probe=c8532fbb66) | May 29, 2022 |
| Gigabyte      | H310M H                     | [60e8f2017c](https://linux-hardware.org/?probe=60e8f2017c) | May 29, 2022 |
| ASUSTek       | H61M-K                      | [1001d81aa0](https://linux-hardware.org/?probe=1001d81aa0) | May 28, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [e2e854cde1](https://linux-hardware.org/?probe=e2e854cde1) | May 28, 2022 |
| Positivo      | POS-PIQ57BQA                | [f33ecab5de](https://linux-hardware.org/?probe=f33ecab5de) | May 27, 2022 |
| Intel         | MAHOBAY                     | [1eddee7bcd](https://linux-hardware.org/?probe=1eddee7bcd) | May 26, 2022 |
| Positivo      | POS-PIQ57BQA                | [2175bbae83](https://linux-hardware.org/?probe=2175bbae83) | May 26, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| ASUSTek       | B85M-E                      | [d153ce4509](https://linux-hardware.org/?probe=d153ce4509) | May 26, 2022 |
| Intel         | H55                         | [fa014a938e](https://linux-hardware.org/?probe=fa014a938e) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [66b8c4e68c](https://linux-hardware.org/?probe=66b8c4e68c) | May 24, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [7fae2860ed](https://linux-hardware.org/?probe=7fae2860ed) | May 23, 2022 |
| Intel         | DH55HC AAE70933-505         | [6c27613f85](https://linux-hardware.org/?probe=6c27613f85) | May 23, 2022 |
| Intel         | H55                         | [8dd80b1c9d](https://linux-hardware.org/?probe=8dd80b1c9d) | May 23, 2022 |
| Intel         | H55                         | [c383403505](https://linux-hardware.org/?probe=c383403505) | May 23, 2022 |
| Unknown       | P4M800Pro-8237              | [31c80b1ea7](https://linux-hardware.org/?probe=31c80b1ea7) | May 23, 2022 |
| ASRock        | 760GM-HDV                   | [a7c99d7f14](https://linux-hardware.org/?probe=a7c99d7f14) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a37dd040cc](https://linux-hardware.org/?probe=a37dd040cc) | May 22, 2022 |
| ASUSTek       | H81M-CS/BR                  | [d7908e91b2](https://linux-hardware.org/?probe=d7908e91b2) | May 22, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [da237b1570](https://linux-hardware.org/?probe=da237b1570) | May 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [72a96fc8a3](https://linux-hardware.org/?probe=72a96fc8a3) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | ThinkCentre M57 9181A28     | [51ec46a243](https://linux-hardware.org/?probe=51ec46a243) | May 19, 2022 |
| ASUSTek       | PRIME Z270-A                | [f11849c880](https://linux-hardware.org/?probe=f11849c880) | May 19, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| ECS           | GF7050VT-M5                 | [485f780320](https://linux-hardware.org/?probe=485f780320) | May 18, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| ASRock        | B450M Steel Legend          | [82304dff79](https://linux-hardware.org/?probe=82304dff79) | May 18, 2022 |
| Gigabyte      | A520M AORUS ELITE           | [959370d8dc](https://linux-hardware.org/?probe=959370d8dc) | May 18, 2022 |
| Gigabyte      | A520M AORUS ELITE           | [3f7443585b](https://linux-hardware.org/?probe=3f7443585b) | May 18, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b93895e03f](https://linux-hardware.org/?probe=b93895e03f) | May 17, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b9f903a680](https://linux-hardware.org/?probe=b9f903a680) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [aa8b5a4aec](https://linux-hardware.org/?probe=aa8b5a4aec) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 08HPGT A01                  | [4b277b05bb](https://linux-hardware.org/?probe=4b277b05bb) | May 17, 2022 |
| Intel         | B75 V124                    | [fe86136319](https://linux-hardware.org/?probe=fe86136319) | May 17, 2022 |
| Gigabyte      | G31M-ES2L                   | [06d20940b6](https://linux-hardware.org/?probe=06d20940b6) | May 17, 2022 |
| Gigabyte      | B75M-D3H                    | [b16118393d](https://linux-hardware.org/?probe=b16118393d) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [5e9289dcf5](https://linux-hardware.org/?probe=5e9289dcf5) | May 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [ef49485481](https://linux-hardware.org/?probe=ef49485481) | May 16, 2022 |
| Gigabyte      | X38-DQ6                     | [653ffc4014](https://linux-hardware.org/?probe=653ffc4014) | May 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [e2b0f10f58](https://linux-hardware.org/?probe=e2b0f10f58) | May 15, 2022 |
| Gigabyte      | B75M-D3H                    | [285fd45173](https://linux-hardware.org/?probe=285fd45173) | May 15, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [903b5a7b61](https://linux-hardware.org/?probe=903b5a7b61) | May 15, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [803d13c6ca](https://linux-hardware.org/?probe=803d13c6ca) | May 15, 2022 |
| Positivo      | POS-PIH81DI                 | [2e519d3320](https://linux-hardware.org/?probe=2e519d3320) | May 14, 2022 |
| Intel         | X99 V1.0                    | [554b088978](https://linux-hardware.org/?probe=554b088978) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| Positivo      | POS-PIH77CM POSITIVO        | [8dbd7b8e3a](https://linux-hardware.org/?probe=8dbd7b8e3a) | May 13, 2022 |
| ASRock        | H61M-HVS                    | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| ASRock        | H61M-HP4                    | [f0bda638ba](https://linux-hardware.org/?probe=f0bda638ba) | May 13, 2022 |
| Pegatron      | IPMIP-GS                    | [76783b5ce4](https://linux-hardware.org/?probe=76783b5ce4) | May 12, 2022 |
| Pegatron      | IPMIP-GS                    | [1f60b52d11](https://linux-hardware.org/?probe=1f60b52d11) | May 12, 2022 |
| Biostar       | G31M+                       | [7440220607](https://linux-hardware.org/?probe=7440220607) | May 12, 2022 |
| ASUSTek       | PRIME B350M-E               | [c1c97167a7](https://linux-hardware.org/?probe=c1c97167a7) | May 11, 2022 |
| Positivo      | DA18HV1 POSITIVO            | [9d5e3583e2](https://linux-hardware.org/?probe=9d5e3583e2) | May 11, 2022 |
| Intel         | B75                         | [d2a9132d48](https://linux-hardware.org/?probe=d2a9132d48) | May 11, 2022 |
| MSI           | G31M3-L V2                  | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| Gigabyte      | Q35M-S2                     | [784ac96428](https://linux-hardware.org/?probe=784ac96428) | May 11, 2022 |
| Gigabyte      | H97M-HD3                    | [5b0d379b54](https://linux-hardware.org/?probe=5b0d379b54) | May 11, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [2091818d85](https://linux-hardware.org/?probe=2091818d85) | May 10, 2022 |
| ASUSTek       | PRIME B350M-E               | [11a6c9f35a](https://linux-hardware.org/?probe=11a6c9f35a) | May 10, 2022 |
| ASRock        | FM2A55M-VG3+                | [43c813fe70](https://linux-hardware.org/?probe=43c813fe70) | May 10, 2022 |
| Positivo      | POS-PIQ57BQA                | [f3abe22dd6](https://linux-hardware.org/?probe=f3abe22dd6) | May 09, 2022 |
| Intel         | H61                         | [3f5d8ae941](https://linux-hardware.org/?probe=3f5d8ae941) | May 09, 2022 |
| Dell          | 0RW203                      | [fc3e449b4d](https://linux-hardware.org/?probe=fc3e449b4d) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [344bc071a2](https://linux-hardware.org/?probe=344bc071a2) | May 09, 2022 |
| Intel         | X79M-S                      | [770b00ef16](https://linux-hardware.org/?probe=770b00ef16) | May 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [c5c38a0da4](https://linux-hardware.org/?probe=c5c38a0da4) | May 08, 2022 |
| Positivo      | POS-PIG41BA                 | [40a9a00430](https://linux-hardware.org/?probe=40a9a00430) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [d4e02db7d2](https://linux-hardware.org/?probe=d4e02db7d2) | May 07, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [4c2b573647](https://linux-hardware.org/?probe=4c2b573647) | May 07, 2022 |
| Positivo      | POS-MI945AA                 | [dffab0e390](https://linux-hardware.org/?probe=dffab0e390) | May 07, 2022 |
| ASUSTek       | PRIME A320M-K               | [39beda4841](https://linux-hardware.org/?probe=39beda4841) | May 07, 2022 |
| MSI           | 880GMA-E35                  | [a2998f652e](https://linux-hardware.org/?probe=a2998f652e) | May 07, 2022 |
| Positivo      | POS-PIH81DI                 | [f7b64e05f8](https://linux-hardware.org/?probe=f7b64e05f8) | May 06, 2022 |
| MSI           | 880GMA-E35                  | [862de68566](https://linux-hardware.org/?probe=862de68566) | May 06, 2022 |
| Intel         | H55                         | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| MSI           | B550M PRO-DASH              | [585987ecf7](https://linux-hardware.org/?probe=585987ecf7) | May 06, 2022 |
| Positivo      | POS-PARS760GCD              | [dfc00dfd71](https://linux-hardware.org/?probe=dfc00dfd71) | May 05, 2022 |
| Gigabyte      | H410M H V3                  | [ddc4d88d20](https://linux-hardware.org/?probe=ddc4d88d20) | May 05, 2022 |
| Intel         | H61                         | [ef0e75557e](https://linux-hardware.org/?probe=ef0e75557e) | May 05, 2022 |
| ASUSTek       | Z97-K                       | [f03b0f28ef](https://linux-hardware.org/?probe=f03b0f28ef) | May 05, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | [8d41e2310f](https://linux-hardware.org/?probe=8d41e2310f) | May 04, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| Lenovo        | SDK0E50515 STD              | [9a67a9ecfe](https://linux-hardware.org/?probe=9a67a9ecfe) | May 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [489d69a9ee](https://linux-hardware.org/?probe=489d69a9ee) | May 03, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [914e422e76](https://linux-hardware.org/?probe=914e422e76) | May 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | [f2de7ca21b](https://linux-hardware.org/?probe=f2de7ca21b) | May 03, 2022 |
| JINGSHA       | Unknown                     | [94dd890d71](https://linux-hardware.org/?probe=94dd890d71) | May 02, 2022 |
| Intel         | H61M-DS2                    | [78f738c029](https://linux-hardware.org/?probe=78f738c029) | May 02, 2022 |
| Intel         | H61M-DS2                    | [10c3d8c8a0](https://linux-hardware.org/?probe=10c3d8c8a0) | May 02, 2022 |
| Pegatron      | 2AB5                        | [5ad527dcd2](https://linux-hardware.org/?probe=5ad527dcd2) | May 01, 2022 |
| Intel         | DG31PR AAE58249-306         | [53f6946eba](https://linux-hardware.org/?probe=53f6946eba) | May 01, 2022 |
| Positivo      | POS-EIBTPDC                 | [a9a49f094d](https://linux-hardware.org/?probe=a9a49f094d) | May 01, 2022 |
| Positivo      | POS-EIH110EA                | [d0a20e98ac](https://linux-hardware.org/?probe=d0a20e98ac) | May 01, 2022 |
| Pegatron      | 2AB5                        | [534476ac99](https://linux-hardware.org/?probe=534476ac99) | Apr 30, 2022 |
| Positivo      | POS-ECIG41BSA               | [b622f7f43f](https://linux-hardware.org/?probe=b622f7f43f) | Apr 30, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | [6afc1a0af8](https://linux-hardware.org/?probe=6afc1a0af8) | Apr 30, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [89def966af](https://linux-hardware.org/?probe=89def966af) | Apr 30, 2022 |
| JINGSHA       | Unknown                     | [e1b9c4eab0](https://linux-hardware.org/?probe=e1b9c4eab0) | Apr 30, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [2f215a330a](https://linux-hardware.org/?probe=2f215a330a) | Apr 30, 2022 |
| Unknown       | Intel X79                   | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [a5743a1922](https://linux-hardware.org/?probe=a5743a1922) | Apr 29, 2022 |
| PCWare        | IPX4105G Pro                | [073d789fc4](https://linux-hardware.org/?probe=073d789fc4) | Apr 29, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [6a5bc03a3a](https://linux-hardware.org/?probe=6a5bc03a3a) | Apr 29, 2022 |
| Intel         | MAHOBAY                     | [ca65be05f0](https://linux-hardware.org/?probe=ca65be05f0) | Apr 28, 2022 |
| ASRock        | A320M-HDV R4.0              | [0b88a7422d](https://linux-hardware.org/?probe=0b88a7422d) | Apr 28, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [c82cd4f476](https://linux-hardware.org/?probe=c82cd4f476) | Apr 27, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [8dafe7350b](https://linux-hardware.org/?probe=8dafe7350b) | Apr 27, 2022 |
| MSI           | Z97-G45 GAMING              | [6660cb5133](https://linux-hardware.org/?probe=6660cb5133) | Apr 27, 2022 |
| Itautec       | NT 2030                     | [ce556d6808](https://linux-hardware.org/?probe=ce556d6808) | Apr 26, 2022 |
| MSI           | MS-6701                     | [8853d92523](https://linux-hardware.org/?probe=8853d92523) | Apr 26, 2022 |
| MSI           | MS-6701                     | [0bde2af604](https://linux-hardware.org/?probe=0bde2af604) | Apr 26, 2022 |
| ASRock        | A320M-HD                    | [f99a1a0591](https://linux-hardware.org/?probe=f99a1a0591) | Apr 25, 2022 |
| ASRock        | B450M Steel Legend          | [06ecfd2026](https://linux-hardware.org/?probe=06ecfd2026) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | [d7d46c682c](https://linux-hardware.org/?probe=d7d46c682c) | Apr 25, 2022 |
| Supermicro    | X7DWT                       | [4570a2caf7](https://linux-hardware.org/?probe=4570a2caf7) | Apr 25, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [b0a2546f9f](https://linux-hardware.org/?probe=b0a2546f9f) | Apr 24, 2022 |
| Positivo      | POS-EIBTDB                  | [2b6822eb50](https://linux-hardware.org/?probe=2b6822eb50) | Apr 24, 2022 |
| Biostar       | NM70I-1017U                 | [c27061c8f4](https://linux-hardware.org/?probe=c27061c8f4) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [20d9884cb6](https://linux-hardware.org/?probe=20d9884cb6) | Apr 24, 2022 |
| Gigabyte      | B450 AORUS M                | [dac092d7bc](https://linux-hardware.org/?probe=dac092d7bc) | Apr 24, 2022 |
| MSI           | H81M-E33                    | [a56e939c9f](https://linux-hardware.org/?probe=a56e939c9f) | Apr 23, 2022 |
| Pegatron      | IPMH61P1                    | [73ac7e5e3e](https://linux-hardware.org/?probe=73ac7e5e3e) | Apr 23, 2022 |
| MSI           | G41M-S01                    | [cd81f73a4d](https://linux-hardware.org/?probe=cd81f73a4d) | Apr 23, 2022 |
| Intel         | H81                         | [9720e797c4](https://linux-hardware.org/?probe=9720e797c4) | Apr 23, 2022 |
| Intel         | H81                         | [2c89989829](https://linux-hardware.org/?probe=2c89989829) | Apr 23, 2022 |
| Pegatron      | IPMH61P1                    | [26a1791ea4](https://linux-hardware.org/?probe=26a1791ea4) | Apr 22, 2022 |
| ASUSTek       | P7H55-M BR                  | [e3c7a6ade9](https://linux-hardware.org/?probe=e3c7a6ade9) | Apr 22, 2022 |
| Gigabyte      | G31M-ES2L                   | [0150424029](https://linux-hardware.org/?probe=0150424029) | Apr 22, 2022 |
| Dell          | 073MMW A03                  | [f3ecf74145](https://linux-hardware.org/?probe=f3ecf74145) | Apr 22, 2022 |
| Intel         | X99                         | [f7410bb2fd](https://linux-hardware.org/?probe=f7410bb2fd) | Apr 21, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c568c44d81](https://linux-hardware.org/?probe=c568c44d81) | Apr 20, 2022 |
| Dell          | 0200DY A01                  | [5cb77cb68e](https://linux-hardware.org/?probe=5cb77cb68e) | Apr 20, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [d126b742fe](https://linux-hardware.org/?probe=d126b742fe) | Apr 20, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [888cf862fc](https://linux-hardware.org/?probe=888cf862fc) | Apr 20, 2022 |
| ASUSTek       | PRIME A520M-E               | [0aa2639b59](https://linux-hardware.org/?probe=0aa2639b59) | Apr 20, 2022 |
| MSI           | Boston                      | [ee1d487c1e](https://linux-hardware.org/?probe=ee1d487c1e) | Apr 18, 2022 |
| Gigabyte      | G41MT-ES2L                  | [fbeec44852](https://linux-hardware.org/?probe=fbeec44852) | Apr 18, 2022 |
| Intel         | Unknown                     | [b734cf3221](https://linux-hardware.org/?probe=b734cf3221) | Apr 17, 2022 |
| Gigabyte      | 970A-UD3                    | [7128f5f2b4](https://linux-hardware.org/?probe=7128f5f2b4) | Apr 17, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [8f8f3b74e6](https://linux-hardware.org/?probe=8f8f3b74e6) | Apr 16, 2022 |
| MSI           | MS-7438 100                 | [bac261ba9a](https://linux-hardware.org/?probe=bac261ba9a) | Apr 16, 2022 |
| MSI           | A320M PRO-M2 V2             | [7a3fa3e4a4](https://linux-hardware.org/?probe=7a3fa3e4a4) | Apr 16, 2022 |
| Gigabyte      | H61M-S1                     | [dfd89c6a60](https://linux-hardware.org/?probe=dfd89c6a60) | Apr 16, 2022 |
| Dell          | 0VHXCD A03                  | [290987223e](https://linux-hardware.org/?probe=290987223e) | Apr 16, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [0a8d0e5302](https://linux-hardware.org/?probe=0a8d0e5302) | Apr 15, 2022 |
| Unknown       | Unknown                     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [172be13d6d](https://linux-hardware.org/?probe=172be13d6d) | Apr 15, 2022 |
| GALAX         | A320M G10g                  | [958fc1bf94](https://linux-hardware.org/?probe=958fc1bf94) | Apr 14, 2022 |
| Itautec       | ST 4262 ST-4262 Padrao 0... | [1dd8e2f31b](https://linux-hardware.org/?probe=1dd8e2f31b) | Apr 14, 2022 |
| Dell          | 0NW6H5 A00                  | [dd5d897f4c](https://linux-hardware.org/?probe=dd5d897f4c) | Apr 14, 2022 |
| Dell          | 0YR541 A01                  | [f206c3667e](https://linux-hardware.org/?probe=f206c3667e) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [83dda83cdf](https://linux-hardware.org/?probe=83dda83cdf) | Apr 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [92eaa72b3c](https://linux-hardware.org/?probe=92eaa72b3c) | Apr 14, 2022 |
| ASUSTek       | PRIME B360M-C               | [417d3ab696](https://linux-hardware.org/?probe=417d3ab696) | Apr 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a5c9b7fc78](https://linux-hardware.org/?probe=a5c9b7fc78) | Apr 14, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [645c74ef90](https://linux-hardware.org/?probe=645c74ef90) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | [3ac4860cb3](https://linux-hardware.org/?probe=3ac4860cb3) | Apr 13, 2022 |
| Megaware      | MW-G31T-M7                  | [ce643cbdcd](https://linux-hardware.org/?probe=ce643cbdcd) | Apr 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [33cce38b5e](https://linux-hardware.org/?probe=33cce38b5e) | Apr 13, 2022 |
| ASRock        | N68-VS3 UCC                 | [1ca06f94c7](https://linux-hardware.org/?probe=1ca06f94c7) | Apr 12, 2022 |
| ASUSTek       | SABERTOOTH 990FX R3.0       | [4f5a780267](https://linux-hardware.org/?probe=4f5a780267) | Apr 12, 2022 |
| Toshiba       | STI 010433                  | [9eb114e523](https://linux-hardware.org/?probe=9eb114e523) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [f4cb39e804](https://linux-hardware.org/?probe=f4cb39e804) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [80c51dad27](https://linux-hardware.org/?probe=80c51dad27) | Apr 12, 2022 |
| MSI           | G31TM-P21                   | [8879fa758a](https://linux-hardware.org/?probe=8879fa758a) | Apr 11, 2022 |
| ASUSTek       | H81M-CS/BR                  | [e2452fa831](https://linux-hardware.org/?probe=e2452fa831) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | [4f13d38f2e](https://linux-hardware.org/?probe=4f13d38f2e) | Apr 11, 2022 |
| MSI           | A320M PRO-M2 V2             | [0a89a1b47b](https://linux-hardware.org/?probe=0a89a1b47b) | Apr 11, 2022 |
| PCWare        | IPMH61R1                    | [4f465b1b2d](https://linux-hardware.org/?probe=4f465b1b2d) | Apr 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Positivo      | POS-MI945AA                 | [581272b7c1](https://linux-hardware.org/?probe=581272b7c1) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| Itautec       | ST 4265                     | [b2facb728e](https://linux-hardware.org/?probe=b2facb728e) | Apr 10, 2022 |
| Dell          | 08NPPY A00                  | [5c2b30a7e1](https://linux-hardware.org/?probe=5c2b30a7e1) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| ASRock        | G31M-S                      | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| Unknown       | TIGD-CI4                    | [266aef8b2e](https://linux-hardware.org/?probe=266aef8b2e) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Intel         | H81                         | [ffcfab5f12](https://linux-hardware.org/?probe=ffcfab5f12) | Apr 08, 2022 |
| ASRock        | N68-S3 FX                   | [ca818bd06d](https://linux-hardware.org/?probe=ca818bd06d) | Apr 08, 2022 |
| Intel         | Unknown                     | [28f0edef8f](https://linux-hardware.org/?probe=28f0edef8f) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| Unknown       | Unknown                     | [a78f13de9e](https://linux-hardware.org/?probe=a78f13de9e) | Apr 07, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Intel         | X99                         | [4b1591958f](https://linux-hardware.org/?probe=4b1591958f) | Apr 06, 2022 |
| Acer          | Aspire XC-605               | [201896f70b](https://linux-hardware.org/?probe=201896f70b) | Apr 06, 2022 |
| ASRock        | FM2A78M-ITX+                | [63799d0adb](https://linux-hardware.org/?probe=63799d0adb) | Apr 06, 2022 |
| HP            | 3047h                       | [6766d428ef](https://linux-hardware.org/?probe=6766d428ef) | Apr 05, 2022 |
| Gigabyte      | B450M DS3H-CF               | [adf960d914](https://linux-hardware.org/?probe=adf960d914) | Apr 05, 2022 |
| Intel         | H61                         | [d378493561](https://linux-hardware.org/?probe=d378493561) | Apr 05, 2022 |
| Dell          | 02YRK5 A03                  | [8f30fb0a3f](https://linux-hardware.org/?probe=8f30fb0a3f) | Apr 04, 2022 |
| Dell          | 02YRK5 A03                  | [4014bf184c](https://linux-hardware.org/?probe=4014bf184c) | Apr 04, 2022 |
| Gigabyte      | H55M-S2HP                   | [5079856030](https://linux-hardware.org/?probe=5079856030) | Apr 04, 2022 |
| Gigabyte      | H110M-H-CF                  | [9ca082be16](https://linux-hardware.org/?probe=9ca082be16) | Apr 04, 2022 |
| HP            | 1998                        | [d30791d695](https://linux-hardware.org/?probe=d30791d695) | Apr 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [5bbc4cbbf5](https://linux-hardware.org/?probe=5bbc4cbbf5) | Apr 03, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [40077b3761](https://linux-hardware.org/?probe=40077b3761) | Apr 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | [63408907f1](https://linux-hardware.org/?probe=63408907f1) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a8425c2df8](https://linux-hardware.org/?probe=a8425c2df8) | Apr 02, 2022 |
| ASUSTek       | P9X79 DELUXE                | [6655399773](https://linux-hardware.org/?probe=6655399773) | Apr 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | [37394c9815](https://linux-hardware.org/?probe=37394c9815) | Apr 02, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [eedbf6a10e](https://linux-hardware.org/?probe=eedbf6a10e) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [42038ab400](https://linux-hardware.org/?probe=42038ab400) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [5d3d268c96](https://linux-hardware.org/?probe=5d3d268c96) | Apr 02, 2022 |
| Intel         | DG41WV AAE90316-101         | [3dac9f017e](https://linux-hardware.org/?probe=3dac9f017e) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [ba7a9c106a](https://linux-hardware.org/?probe=ba7a9c106a) | Apr 02, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [a8331ec187](https://linux-hardware.org/?probe=a8331ec187) | Apr 02, 2022 |
| Toshiba       | STI 010433                  | [daa5ae86bc](https://linux-hardware.org/?probe=daa5ae86bc) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [c6f1665499](https://linux-hardware.org/?probe=c6f1665499) | Apr 01, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0b849ce682](https://linux-hardware.org/?probe=0b849ce682) | Apr 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [c7cd058399](https://linux-hardware.org/?probe=c7cd058399) | Apr 01, 2022 |
| HP            | 1998                        | [23ca5d6703](https://linux-hardware.org/?probe=23ca5d6703) | Apr 01, 2022 |
| ASRock        | H510M-HVS R2.0              | [a4ad860e3d](https://linux-hardware.org/?probe=a4ad860e3d) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [a8c1be0abd](https://linux-hardware.org/?probe=a8c1be0abd) | Mar 31, 2022 |
| Positivo      | POS-PIG41BO                 | [865f71148c](https://linux-hardware.org/?probe=865f71148c) | Mar 31, 2022 |
| Gigabyte      | M68MT-S2P                   | [c2daebfd60](https://linux-hardware.org/?probe=c2daebfd60) | Mar 30, 2022 |
| Pegatron      | SM 3322                     | [5f56bb615a](https://linux-hardware.org/?probe=5f56bb615a) | Mar 30, 2022 |
| Dell          | 0FR6WH A01                  | [3ebf09bc41](https://linux-hardware.org/?probe=3ebf09bc41) | Mar 30, 2022 |
| ASUSTek       | PRIME B460M-A               | [519c65be70](https://linux-hardware.org/?probe=519c65be70) | Mar 29, 2022 |
| ASUSTek       | PRIME B460M-A               | [f21f3af1ca](https://linux-hardware.org/?probe=f21f3af1ca) | Mar 29, 2022 |
| Dell          | 0JP3NX A01                  | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| ASUSTek       | B85-PRO GAMER               | [44913af0e4](https://linux-hardware.org/?probe=44913af0e4) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | [51c0f63296](https://linux-hardware.org/?probe=51c0f63296) | Mar 27, 2022 |
| MSI           | B450M PRO-M2                | [e269e3b44e](https://linux-hardware.org/?probe=e269e3b44e) | Mar 27, 2022 |
| ASUSTek       | PRIME B350M-A               | [3839ca9677](https://linux-hardware.org/?probe=3839ca9677) | Mar 27, 2022 |
| ASUSTek       | H81M-C/BR                   | [4d07e31cee](https://linux-hardware.org/?probe=4d07e31cee) | Mar 27, 2022 |
| ASUSTek       | P8H61-M LE/BR               | [732876bdd8](https://linux-hardware.org/?probe=732876bdd8) | Mar 26, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [c8acfed97a](https://linux-hardware.org/?probe=c8acfed97a) | Mar 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c4986f3f81](https://linux-hardware.org/?probe=c4986f3f81) | Mar 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [d1e5c0bc9f](https://linux-hardware.org/?probe=d1e5c0bc9f) | Mar 25, 2022 |
| Login Info... | LOG-H110M-G3                | [30a691b952](https://linux-hardware.org/?probe=30a691b952) | Mar 25, 2022 |
| ASRock        | H61M-HVS                    | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| Unknown       | Unknown                     | [e22336384e](https://linux-hardware.org/?probe=e22336384e) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| Dell          | 0D883F A06                  | [7966cb4145](https://linux-hardware.org/?probe=7966cb4145) | Mar 23, 2022 |
| MSI           | 2A9C                        | [5789a9614f](https://linux-hardware.org/?probe=5789a9614f) | Mar 23, 2022 |
| Biostar       | H61MLV2                     | [1bce4dc771](https://linux-hardware.org/?probe=1bce4dc771) | Mar 22, 2022 |
| Biostar       | H61MLV2                     | [4d97559516](https://linux-hardware.org/?probe=4d97559516) | Mar 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e3d131ff9a](https://linux-hardware.org/?probe=e3d131ff9a) | Mar 22, 2022 |
| Digiboard     | MPxx                        | [b3bb9ff288](https://linux-hardware.org/?probe=b3bb9ff288) | Mar 22, 2022 |
| ASUSTek       | P5KC                        | [b4511f91a2](https://linux-hardware.org/?probe=b4511f91a2) | Mar 22, 2022 |
| Colorful T... | A320M-K PRO YV14            | [94393a4d0a](https://linux-hardware.org/?probe=94393a4d0a) | Mar 22, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | [b789768b64](https://linux-hardware.org/?probe=b789768b64) | Mar 21, 2022 |
| ASUSTek       | P5KC                        | [b2fd45aebb](https://linux-hardware.org/?probe=b2fd45aebb) | Mar 21, 2022 |
| MSI           | B250M PRO-VH                | [d3885311bc](https://linux-hardware.org/?probe=d3885311bc) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | [f3e67de15e](https://linux-hardware.org/?probe=f3e67de15e) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | [78676e017b](https://linux-hardware.org/?probe=78676e017b) | Mar 19, 2022 |
| Dell          | 0VRWRC A01                  | [48a73bd70f](https://linux-hardware.org/?probe=48a73bd70f) | Mar 19, 2022 |
| ECS           | A990FXM-A                   | [32deb5b6a1](https://linux-hardware.org/?probe=32deb5b6a1) | Mar 19, 2022 |
| ASUSTek       | J1800I-C/BR                 | [4d11bb964b](https://linux-hardware.org/?probe=4d11bb964b) | Mar 19, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [6c60e6d6af](https://linux-hardware.org/?probe=6c60e6d6af) | Mar 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [e7534ca823](https://linux-hardware.org/?probe=e7534ca823) | Mar 19, 2022 |
| Biostar       | N68S3B                      | [736799fe08](https://linux-hardware.org/?probe=736799fe08) | Mar 18, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [6f4835e78d](https://linux-hardware.org/?probe=6f4835e78d) | Mar 18, 2022 |
| MSI           | J1900I                      | [991f20b3b8](https://linux-hardware.org/?probe=991f20b3b8) | Mar 17, 2022 |
| Gigabyte      | G31M-S2C                    | [a56fb721dd](https://linux-hardware.org/?probe=a56fb721dd) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M LX3                | [24b9866304](https://linux-hardware.org/?probe=24b9866304) | Mar 17, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9ebb2a429f](https://linux-hardware.org/?probe=9ebb2a429f) | Mar 17, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb5c244ae1](https://linux-hardware.org/?probe=cb5c244ae1) | Mar 17, 2022 |
| ASUSTek       | M5A78L/USB3                 | [15a04898a4](https://linux-hardware.org/?probe=15a04898a4) | Mar 17, 2022 |
| Unknown       | Unknown                     | [1aaee68ff4](https://linux-hardware.org/?probe=1aaee68ff4) | Mar 16, 2022 |
| HP            | 83E2                        | [d39e85ed10](https://linux-hardware.org/?probe=d39e85ed10) | Mar 16, 2022 |
| Intel         | X99 V1.0                    | [3e1b96fe9f](https://linux-hardware.org/?probe=3e1b96fe9f) | Mar 16, 2022 |
| ASUSTek       | M4N68T-M LE                 | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [220c4f69b0](https://linux-hardware.org/?probe=220c4f69b0) | Mar 15, 2022 |
| Positivo      | POS-PIH77CM POSITIVO        | [8420ad7ef2](https://linux-hardware.org/?probe=8420ad7ef2) | Mar 14, 2022 |
| Dell          | 08YDFF A01                  | [322d01a111](https://linux-hardware.org/?probe=322d01a111) | Mar 14, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [2e828331f3](https://linux-hardware.org/?probe=2e828331f3) | Mar 14, 2022 |
| Intel         | DH61WW AAG23116-303         | [8cc21d5508](https://linux-hardware.org/?probe=8cc21d5508) | Mar 13, 2022 |
| Visum         | A6VMX 0A                    | [82a79d1b3c](https://linux-hardware.org/?probe=82a79d1b3c) | Mar 13, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [9391de1a74](https://linux-hardware.org/?probe=9391de1a74) | Mar 12, 2022 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [f8ef0e1c18](https://linux-hardware.org/?probe=f8ef0e1c18) | Mar 12, 2022 |
| ASRock        | FM2A55M-VG3+                | [ebf747ad50](https://linux-hardware.org/?probe=ebf747ad50) | Mar 12, 2022 |
| ECS           | H81H3-M4                    | [40de48af24](https://linux-hardware.org/?probe=40de48af24) | Mar 12, 2022 |
| Dell          | 01XK1W A00                  | [036df95c28](https://linux-hardware.org/?probe=036df95c28) | Mar 11, 2022 |
| ASUSTek       | H61M-A/BR                   | [f3a97cad04](https://linux-hardware.org/?probe=f3a97cad04) | Mar 11, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [9de4c6210f](https://linux-hardware.org/?probe=9de4c6210f) | Mar 11, 2022 |
| Intel         | H61                         | [8ce8958b88](https://linux-hardware.org/?probe=8ce8958b88) | Mar 10, 2022 |
| Megaware      | MW-H61M-2H                  | [ceb5a251e7](https://linux-hardware.org/?probe=ceb5a251e7) | Mar 10, 2022 |
| MSI           | G31M3-L V2                  | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ef2e2e6872](https://linux-hardware.org/?probe=ef2e2e6872) | Mar 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7b7cf41624](https://linux-hardware.org/?probe=7b7cf41624) | Mar 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [418dc14fe7](https://linux-hardware.org/?probe=418dc14fe7) | Mar 10, 2022 |
| Intel         | H61                         | [cb91470ea7](https://linux-hardware.org/?probe=cb91470ea7) | Mar 10, 2022 |
| ONDA          | A68V+                       | [2c4c04ae22](https://linux-hardware.org/?probe=2c4c04ae22) | Mar 10, 2022 |
| Gigabyte      | B450 AORUS M                | [a5c7569f3c](https://linux-hardware.org/?probe=a5c7569f3c) | Mar 09, 2022 |
| Gigabyte      | H510M H                     | [78d900b185](https://linux-hardware.org/?probe=78d900b185) | Mar 09, 2022 |
| Gigabyte      | A520M DS3H                  | [1e28e34bca](https://linux-hardware.org/?probe=1e28e34bca) | Mar 08, 2022 |
| ASUSTek       | M2N-SLI                     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Intel         | H61                         | [5198074ef6](https://linux-hardware.org/?probe=5198074ef6) | Mar 07, 2022 |
| ASUSTek       | Crosshair V Formula         | [060ea89f97](https://linux-hardware.org/?probe=060ea89f97) | Mar 06, 2022 |
| Gigabyte      | G31M-S2C                    | [d419223147](https://linux-hardware.org/?probe=d419223147) | Mar 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [97eedd34f4](https://linux-hardware.org/?probe=97eedd34f4) | Mar 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [7fd2e4885c](https://linux-hardware.org/?probe=7fd2e4885c) | Mar 05, 2022 |
| Intel         | DG31PR AAE58249-302         | [fb8b615012](https://linux-hardware.org/?probe=fb8b615012) | Mar 04, 2022 |
| Dell          | 0HN7XN A00                  | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| Kllisre       | B75 V1.1                    | [f29cfed3d4](https://linux-hardware.org/?probe=f29cfed3d4) | Mar 03, 2022 |
| Intel         | H61                         | [86f2038ab2](https://linux-hardware.org/?probe=86f2038ab2) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [0875be36f0](https://linux-hardware.org/?probe=0875be36f0) | Mar 03, 2022 |
| Intel         | DG31PR AAE58249-302         | [71344b6640](https://linux-hardware.org/?probe=71344b6640) | Mar 03, 2022 |
| MSI           | MS-7255 V2.0                | [5874b1887d](https://linux-hardware.org/?probe=5874b1887d) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| ECS           | A785GM-AD3                  | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| Positivo      | POS-RIQ370ED                | [0fa80fe8c0](https://linux-hardware.org/?probe=0fa80fe8c0) | Mar 02, 2022 |
| ASUSTek       | H81M-CS/BR                  | [7fb5d56fdd](https://linux-hardware.org/?probe=7fb5d56fdd) | Mar 02, 2022 |
| Unknown       | Phitronics G31VS-M          | [0a32bd76ae](https://linux-hardware.org/?probe=0a32bd76ae) | Mar 01, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [6a159a891a](https://linux-hardware.org/?probe=6a159a891a) | Mar 01, 2022 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [4448b7c526](https://linux-hardware.org/?probe=4448b7c526) | Mar 01, 2022 |
| Intel         | H55                         | [2f52a73f85](https://linux-hardware.org/?probe=2f52a73f85) | Feb 27, 2022 |
| ASUSTek       | B85M-E                      | [c607041591](https://linux-hardware.org/?probe=c607041591) | Feb 27, 2022 |
| Digiboard     | MPxx                        | [9ad44a5962](https://linux-hardware.org/?probe=9ad44a5962) | Feb 26, 2022 |
| ASRock        | A320M-HDV R4.0              | [f5ae3c9897](https://linux-hardware.org/?probe=f5ae3c9897) | Feb 26, 2022 |
| ASRock        | A320M-HDV R4.0              | [d55cc6eae3](https://linux-hardware.org/?probe=d55cc6eae3) | Feb 26, 2022 |
| Biostar       | NM70I-1017U                 | [f35ed03897](https://linux-hardware.org/?probe=f35ed03897) | Feb 25, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [ac581c6a60](https://linux-hardware.org/?probe=ac581c6a60) | Feb 25, 2022 |
| Dell          | 0KRXWM A02                  | [01a5ebd96b](https://linux-hardware.org/?probe=01a5ebd96b) | Feb 25, 2022 |
| MSI           | H110M PRO-VH PLUS           | [6754afe86b](https://linux-hardware.org/?probe=6754afe86b) | Feb 25, 2022 |
| ASUSTek       | H81M-C/BR                   | [7e14c1aa3b](https://linux-hardware.org/?probe=7e14c1aa3b) | Feb 25, 2022 |
| Positivo      | POS-AG31AP                  | [87841e3821](https://linux-hardware.org/?probe=87841e3821) | Feb 24, 2022 |
| Gigabyte      | B450 AORUS M                | [b94d0c6e20](https://linux-hardware.org/?probe=b94d0c6e20) | Feb 24, 2022 |
| Positivo      | POS-AG31AP                  | [cbca5bf3a8](https://linux-hardware.org/?probe=cbca5bf3a8) | Feb 23, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [2f53cef399](https://linux-hardware.org/?probe=2f53cef399) | Feb 23, 2022 |
| Intel         | H55                         | [39bf688b34](https://linux-hardware.org/?probe=39bf688b34) | Feb 23, 2022 |
| ASUSTek       | M4N68T-M LE                 | [da3e382cd2](https://linux-hardware.org/?probe=da3e382cd2) | Feb 23, 2022 |
| ASUSTek       | H81M-CS/BR                  | [7cd7c3a4ab](https://linux-hardware.org/?probe=7cd7c3a4ab) | Feb 23, 2022 |
| ASUSTek       | H81M-CS/BR                  | [b460bc4c34](https://linux-hardware.org/?probe=b460bc4c34) | Feb 23, 2022 |
| Lenovo        | ThinkCentre M90p 5485AG8    | [413a69681a](https://linux-hardware.org/?probe=413a69681a) | Feb 22, 2022 |
| Unknown       | PCWARE APMCP68              | [4a123c183a](https://linux-hardware.org/?probe=4a123c183a) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c671dad477](https://linux-hardware.org/?probe=c671dad477) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [6e37f69275](https://linux-hardware.org/?probe=6e37f69275) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5031241166](https://linux-hardware.org/?probe=5031241166) | Feb 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [d6b6cbe6c9](https://linux-hardware.org/?probe=d6b6cbe6c9) | Feb 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [5431dfb2ef](https://linux-hardware.org/?probe=5431dfb2ef) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [558ef9e9d4](https://linux-hardware.org/?probe=558ef9e9d4) | Feb 20, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [b9e6d11567](https://linux-hardware.org/?probe=b9e6d11567) | Feb 20, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5d16d8202f](https://linux-hardware.org/?probe=5d16d8202f) | Feb 20, 2022 |
| Dell          | 07N90W A02                  | [caa8d90509](https://linux-hardware.org/?probe=caa8d90509) | Feb 20, 2022 |
| Digitron      | G31T-M7                     | [8c83de382a](https://linux-hardware.org/?probe=8c83de382a) | Feb 19, 2022 |
| ASRock        | N68-S3 FX                   | [00427ca464](https://linux-hardware.org/?probe=00427ca464) | Feb 19, 2022 |
| ASRock        | FM2A55M-VG3+                | [546d09f207](https://linux-hardware.org/?probe=546d09f207) | Feb 19, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [59a321d574](https://linux-hardware.org/?probe=59a321d574) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | HURONRIVER                  | [d0372ba4af](https://linux-hardware.org/?probe=d0372ba4af) | Feb 18, 2022 |
| ASUSTek       | Z97-A                       | [b1ab92368d](https://linux-hardware.org/?probe=b1ab92368d) | Feb 17, 2022 |
| Intel         | DH55PJ AAE93812-302         | [491016ec7c](https://linux-hardware.org/?probe=491016ec7c) | Feb 16, 2022 |
| HP            | 3048h                       | [6f448e856a](https://linux-hardware.org/?probe=6f448e856a) | Feb 16, 2022 |
| Intel         | H55                         | [b890b6f13e](https://linux-hardware.org/?probe=b890b6f13e) | Feb 16, 2022 |
| Huanan        | X79-ZD3 V2.3                | [c20523ee1f](https://linux-hardware.org/?probe=c20523ee1f) | Feb 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [f84382df07](https://linux-hardware.org/?probe=f84382df07) | Feb 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [32b28f79c9](https://linux-hardware.org/?probe=32b28f79c9) | Feb 15, 2022 |
| Centrium      | C2014-H81H3-M4              | [6b0be9c067](https://linux-hardware.org/?probe=6b0be9c067) | Feb 15, 2022 |
| Gigabyte      | H110M-M2-CF                 | [b36ee90ac0](https://linux-hardware.org/?probe=b36ee90ac0) | Feb 15, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [2504c5ff16](https://linux-hardware.org/?probe=2504c5ff16) | Feb 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [19c20b4b30](https://linux-hardware.org/?probe=19c20b4b30) | Feb 15, 2022 |
| Philco        | 10D                         | [2efb7555a1](https://linux-hardware.org/?probe=2efb7555a1) | Feb 14, 2022 |
| Positivo      | POS-PIH81DI                 | [64c37730f6](https://linux-hardware.org/?probe=64c37730f6) | Feb 13, 2022 |
| ASUSTek       | P7H55-M                     | [295d9daf15](https://linux-hardware.org/?probe=295d9daf15) | Feb 12, 2022 |
| ECS           | A785GM-AD3                  | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| ASUSTek       | P8Z77-M                     | [2662081a67](https://linux-hardware.org/?probe=2662081a67) | Feb 12, 2022 |
| Positivo      | POS-EAA75DE                 | [1b14cace5c](https://linux-hardware.org/?probe=1b14cace5c) | Feb 11, 2022 |
| Positivo      | POS-EIBTPDC                 | [ff7b84fe78](https://linux-hardware.org/?probe=ff7b84fe78) | Feb 11, 2022 |
| Dell          | 0K240Y A04                  | [4342c15fb0](https://linux-hardware.org/?probe=4342c15fb0) | Feb 11, 2022 |
| Gigabyte      | H270-Gaming 3               | [98a3f252a8](https://linux-hardware.org/?probe=98a3f252a8) | Feb 11, 2022 |
| Gigabyte      | B75M-HD3                    | [81fb0bce4d](https://linux-hardware.org/?probe=81fb0bce4d) | Feb 11, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [2885a7e3ed](https://linux-hardware.org/?probe=2885a7e3ed) | Feb 11, 2022 |
| Intel         | H61                         | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| PCWare        | IPMH61R3 8MB                | [58a0a81447](https://linux-hardware.org/?probe=58a0a81447) | Feb 11, 2022 |
| Positivo      | POS-EIBTPDC                 | [5b9ae01006](https://linux-hardware.org/?probe=5b9ae01006) | Feb 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | [1b903af2df](https://linux-hardware.org/?probe=1b903af2df) | Feb 10, 2022 |
| Gigabyte      | Z77X-D3H                    | [62d5812547](https://linux-hardware.org/?probe=62d5812547) | Feb 09, 2022 |
| Intel         | DH55HC AAE70933-502         | [daabbb468a](https://linux-hardware.org/?probe=daabbb468a) | Feb 09, 2022 |
| Gigabyte      | H310M M.2                   | [41502e29af](https://linux-hardware.org/?probe=41502e29af) | Feb 09, 2022 |
| ASUSTek       | H61M-A/BR                   | [48e68c86d6](https://linux-hardware.org/?probe=48e68c86d6) | Feb 09, 2022 |
| Positivo      | POS-EINM70CS POSITIVO       | [28b687e587](https://linux-hardware.org/?probe=28b687e587) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b6402a0817](https://linux-hardware.org/?probe=b6402a0817) | Feb 09, 2022 |
| Kennex        | POS-PIG41BA                 | [54cfa11e20](https://linux-hardware.org/?probe=54cfa11e20) | Feb 09, 2022 |
| SUPoX COMP... | B250A-BTC PRO               | [780b5cb42e](https://linux-hardware.org/?probe=780b5cb42e) | Feb 09, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [1dac9367c9](https://linux-hardware.org/?probe=1dac9367c9) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [9f8ac3fe7f](https://linux-hardware.org/?probe=9f8ac3fe7f) | Feb 08, 2022 |
| Intel         | H61                         | [71ed0d632b](https://linux-hardware.org/?probe=71ed0d632b) | Feb 08, 2022 |
| PCChips       | A51G                        | [c3b2b7a8a3](https://linux-hardware.org/?probe=c3b2b7a8a3) | Feb 08, 2022 |
| Dell          | 0KWVT8 A02                  | [d48b27d912](https://linux-hardware.org/?probe=d48b27d912) | Feb 08, 2022 |
| PCChips       | A51G                        | [7f3ae0e392](https://linux-hardware.org/?probe=7f3ae0e392) | Feb 08, 2022 |
| Supermicro    | X9DAi                       | [ea3cbb18b7](https://linux-hardware.org/?probe=ea3cbb18b7) | Feb 08, 2022 |
| Supermicro    | X9DAi                       | [f4ce79a016](https://linux-hardware.org/?probe=f4ce79a016) | Feb 08, 2022 |
| Gigabyte      | GA-990XA-UD3                | [6bb9884c12](https://linux-hardware.org/?probe=6bb9884c12) | Feb 08, 2022 |
| ASRock        | N68-GS4 FX                  | [d08f0c4b79](https://linux-hardware.org/?probe=d08f0c4b79) | Feb 08, 2022 |
| Digiboard     | NM70-TI                     | [94fb04410f](https://linux-hardware.org/?probe=94fb04410f) | Feb 08, 2022 |
| ASUSTek       | H81M-A/BR                   | [5195720c69](https://linux-hardware.org/?probe=5195720c69) | Feb 08, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [cdab54c6de](https://linux-hardware.org/?probe=cdab54c6de) | Feb 07, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4ceccc2e76](https://linux-hardware.org/?probe=4ceccc2e76) | Feb 07, 2022 |
| HP            | 859C                        | [e984dd6733](https://linux-hardware.org/?probe=e984dd6733) | Feb 07, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [733ee79a8f](https://linux-hardware.org/?probe=733ee79a8f) | Feb 07, 2022 |
| ASRock        | 970A-G                      | [de12500bf9](https://linux-hardware.org/?probe=de12500bf9) | Feb 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c8c77fd622](https://linux-hardware.org/?probe=c8c77fd622) | Feb 07, 2022 |
| Intel         | X79G V2.x                   | [a6b95e1220](https://linux-hardware.org/?probe=a6b95e1220) | Feb 07, 2022 |
| Biostar       | H81A                        | [e045b16856](https://linux-hardware.org/?probe=e045b16856) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| Gigabyte      | H310M M.2 x.x               | [824af874a4](https://linux-hardware.org/?probe=824af874a4) | Feb 06, 2022 |
| Gigabyte      | GA-990XA-UD3                | [74ebb0645d](https://linux-hardware.org/?probe=74ebb0645d) | Feb 06, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [9ac652a7bf](https://linux-hardware.org/?probe=9ac652a7bf) | Feb 06, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [7030f02dfa](https://linux-hardware.org/?probe=7030f02dfa) | Feb 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [a07e2de32a](https://linux-hardware.org/?probe=a07e2de32a) | Feb 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 562      | 12.96%  |
| Ubuntu 18.04      | 405      | 9.34%   |
| OpenMandriva 4.2  | 171      | 3.94%   |
| Linux Mint 20     | 118      | 2.72%   |
| Linux Mint 19.3   | 114      | 2.63%   |
| Pop!_OS 20.04     | 113      | 2.61%   |
| OpenMandriva 4.3  | 111      | 2.56%   |
| Linux Mint 19.1   | 110      | 2.54%   |
| KDE neon 20.04    | 97       | 2.24%   |
| Ubuntu 19.04      | 95       | 2.19%   |
| Linux Mint 20.1   | 84       | 1.94%   |
| Ubuntu 22.04      | 80       | 1.84%   |
| Arch              | 69       | 1.59%   |
| Linux Mint 20.2   | 63       | 1.45%   |
| Linux Mint 20.3   | 62       | 1.43%   |
| Pop!_OS 20.10     | 61       | 1.41%   |
| Debian 10         | 61       | 1.41%   |
| Ubuntu MATE 20.04 | 58       | 1.34%   |
| Ubuntu 19.10      | 58       | 1.34%   |
| Pop!_OS 21.04     | 57       | 1.31%   |
| Manjaro           | 56       | 1.29%   |
| Zorin 16          | 55       | 1.27%   |
| Zorin 15          | 53       | 1.22%   |
| Debian 11         | 48       | 1.11%   |
| Linux Mint 19.2   | 47       | 1.08%   |
| Fedora 36         | 45       | 1.04%   |
| Xubuntu 20.04     | 44       | 1.01%   |
| Fedora 34         | 43       | 0.99%   |
| Arch Rolling      | 42       | 0.97%   |
| Fedora 32         | 39       | 0.9%    |
| Fedora 33         | 38       | 0.88%   |
| Ubuntu 18.10      | 36       | 0.83%   |
| Kubuntu 20.04     | 36       | 0.83%   |
| Ubuntu 20.10      | 35       | 0.81%   |
| Xubuntu 18.04     | 33       | 0.76%   |
| Ubuntu 21.10      | 31       | 0.71%   |
| Pop!_OS 22.04     | 31       | 0.71%   |
| Pop!_OS 21.10     | 31       | 0.71%   |
| Fedora 35         | 28       | 0.65%   |
| Ubuntu 21.04      | 25       | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1308     | 31.46%  |
| Linux Mint    | 615      | 14.79%  |
| OpenMandriva  | 311      | 7.48%   |
| Pop!_OS       | 282      | 6.78%   |
| Fedora        | 210      | 5.05%   |
| Endless       | 158      | 3.8%    |
| Debian        | 153      | 3.68%   |
| Manjaro       | 130      | 3.13%   |
| Zorin         | 113      | 2.72%   |
| KDE neon      | 111      | 2.67%   |
| Arch          | 109      | 2.62%   |
| Xubuntu       | 89       | 2.14%   |
| Kubuntu       | 74       | 1.78%   |
| ROSA          | 69       | 1.66%   |
| Ubuntu MATE   | 68       | 1.64%   |
| openSUSE      | 39       | 0.94%   |
| Ubuntu Unity  | 28       | 0.67%   |
| Lubuntu       | 28       | 0.67%   |
| Elementary    | 25       | 0.6%    |
| LMDE          | 21       | 0.51%   |
| ArcoLinux     | 19       | 0.46%   |
| LinuxFX       | 16       | 0.38%   |
| BlackPanther  | 16       | 0.38%   |
| Deepin        | 15       | 0.36%   |
| CentOS        | 15       | 0.36%   |
| Ubuntu Budgie | 10       | 0.24%   |
| Kali          | 10       | 0.24%   |
| Gentoo        | 8        | 0.19%   |
| Clear Linux   | 8        | 0.19%   |
| BigLinux      | 7        | 0.17%   |
| Peppermint    | 6        | 0.14%   |
| Parrot        | 6        | 0.14%   |
| Linux Lite    | 6        | 0.14%   |
| Ubuntu Studio | 5        | 0.12%   |
| Solus         | 5        | 0.12%   |
| EndeavourOS   | 5        | 0.12%   |
| UbuntuDDE     | 4        | 0.1%    |
| MX            | 4        | 0.1%    |
| Garuda Linux  | 4        | 0.1%    |
| Void Linux    | 3        | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 228      | 4.86%   |
| 5.10.14-desktop-1omv4002 | 166      | 3.54%   |
| 5.16.7-desktop-1omv4003  | 108      | 2.3%    |
| 4.15.0-46-generic        | 84       | 1.79%   |
| 5.4.0-48-generic         | 65       | 1.39%   |
| 4.18.0-15-generic        | 49       | 1.05%   |
| 5.4.0-7634-generic       | 48       | 1.02%   |
| 5.4.0-58-generic         | 45       | 0.96%   |
| 5.4.0-52-generic         | 43       | 0.92%   |
| 5.3.0-40-generic         | 43       | 0.92%   |
| 5.4.0-40-generic         | 41       | 0.87%   |
| 5.4.0-47-generic         | 40       | 0.85%   |
| 5.11.0-7620-generic      | 37       | 0.79%   |
| 5.3.0-28-generic         | 36       | 0.77%   |
| 5.4.0-26-generic         | 35       | 0.75%   |
| 4.15.0-20-generic        | 33       | 0.7%    |
| 5.4.0-70-generic         | 32       | 0.68%   |
| 5.4.0-72-generic         | 31       | 0.66%   |
| 5.0.0-32-generic         | 30       | 0.64%   |
| 5.3.0-46-generic         | 28       | 0.6%    |
| 5.0.0-37-generic         | 28       | 0.6%    |
| 5.8.0-7630-generic       | 27       | 0.58%   |
| 4.15.0-54-generic        | 27       | 0.58%   |
| 5.4.0-33-generic         | 26       | 0.55%   |
| 5.4.0-91-generic         | 25       | 0.53%   |
| 5.15.0-46-generic        | 24       | 0.51%   |
| 5.11.0-37-generic        | 24       | 0.51%   |
| 5.8.0-59-generic         | 23       | 0.49%   |
| 5.8.0-14-generic         | 23       | 0.49%   |
| 5.4.0-74-generic         | 23       | 0.49%   |
| 5.4.0-66-generic         | 23       | 0.49%   |
| 5.4.0-54-generic         | 23       | 0.49%   |
| 5.4.0-37-generic         | 23       | 0.49%   |
| 5.11.0-27-generic        | 23       | 0.49%   |
| 5.0.0-13-generic         | 23       | 0.49%   |
| 4.18.0-16-generic        | 23       | 0.49%   |
| 5.4.0-80-generic         | 22       | 0.47%   |
| 5.4.0-77-generic         | 22       | 0.47%   |
| 5.4.0-19-generic         | 22       | 0.47%   |
| 4.15.0-47-generic        | 22       | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 1098     | 24.85%  |
| 4.15.0  | 413      | 9.35%   |
| 5.8.0   | 257      | 5.82%   |
| 5.11.0  | 245      | 5.55%   |
| 5.3.0   | 244      | 5.52%   |
| 5.0.0   | 229      | 5.18%   |
| 4.18.0  | 173      | 3.92%   |
| 5.13.0  | 172      | 3.89%   |
| 5.10.14 | 166      | 3.76%   |
| 5.15.0  | 143      | 3.24%   |
| 5.16.7  | 108      | 2.44%   |
| 4.19.0  | 74       | 1.67%   |
| 5.10.0  | 67       | 1.52%   |
| 5.7.9   | 21       | 0.48%   |
| 5.17.5  | 19       | 0.43%   |
| 4.9.0   | 18       | 0.41%   |
| 4.4.0   | 18       | 0.41%   |
| 4.9.60  | 15       | 0.34%   |
| 5.19.0  | 14       | 0.32%   |
| 5.13.19 | 14       | 0.32%   |
| 5.7.0   | 13       | 0.29%   |
| 5.15.5  | 12       | 0.27%   |
| 4.18.16 | 12       | 0.27%   |
| 5.18.12 | 11       | 0.25%   |
| 5.17.15 | 11       | 0.25%   |
| 5.16.11 | 11       | 0.25%   |
| 5.16.0  | 11       | 0.25%   |
| 5.14.0  | 11       | 0.25%   |
| 5.12.4  | 11       | 0.25%   |
| 4.9.20  | 11       | 0.25%   |
| 5.6.19  | 10       | 0.23%   |
| 5.7.10  | 9        | 0.2%    |
| 5.6.15  | 9        | 0.2%    |
| 5.9.16  | 8        | 0.18%   |
| 5.7.7   | 7        | 0.16%   |
| 5.6.14  | 7        | 0.16%   |
| 5.4.32  | 7        | 0.16%   |
| 5.3.18  | 7        | 0.16%   |
| 5.19.9  | 7        | 0.16%   |
| 5.15.15 | 7        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 1145     | 26.24%  |
| 4.15    | 413      | 9.46%   |
| 5.10    | 312      | 7.15%   |
| 5.8     | 299      | 6.85%   |
| 5.11    | 270      | 6.19%   |
| 5.3     | 264      | 6.05%   |
| 5.0     | 243      | 5.57%   |
| 5.15    | 209      | 4.79%   |
| 5.13    | 205      | 4.7%    |
| 4.18    | 189      | 4.33%   |
| 5.16    | 156      | 3.57%   |
| 4.19    | 90       | 2.06%   |
| 5.7     | 70       | 1.6%    |
| 5.19    | 59       | 1.35%   |
| 4.9     | 55       | 1.26%   |
| 5.18    | 53       | 1.21%   |
| 5.6     | 52       | 1.19%   |
| 5.17    | 50       | 1.15%   |
| 5.12    | 49       | 1.12%   |
| 5.14    | 41       | 0.94%   |
| 5.9     | 35       | 0.8%    |
| 4.4     | 18       | 0.41%   |
| 5.5     | 16       | 0.37%   |
| 5.2     | 13       | 0.3%    |
| 5.1     | 11       | 0.25%   |
| 6.0     | 8        | 0.18%   |
| 4.1     | 8        | 0.18%   |
| 3.10    | 7        | 0.16%   |
| 4.13    | 6        | 0.14%   |
| 4.20    | 5        | 0.11%   |
| 4.12    | 5        | 0.11%   |
| 4.10    | 4        | 0.09%   |
| 4.8     | 2        | 0.05%   |
| 6.1     | 1        | 0.02%   |
| 4.14    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3878     | 96.95%  |
| i686   | 122      | 3.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 1627     | 38.79%  |
| Unknown                  | 760      | 18.12%  |
| KDE5                     | 583      | 13.9%   |
| X-Cinnamon               | 353      | 8.42%   |
| XFCE                     | 295      | 7.03%   |
| MATE                     | 145      | 3.46%   |
| KDE                      | 140      | 3.34%   |
| Cinnamon                 | 83       | 1.98%   |
| KDE4                     | 38       | 0.91%   |
| Unity                    | 29       | 0.69%   |
| LXQt                     | 25       | 0.6%    |
| Pantheon                 | 21       | 0.5%    |
| Budgie                   | 19       | 0.45%   |
| Deepin                   | 18       | 0.43%   |
| LXDE                     | 16       | 0.38%   |
| GNOME Flashback          | 13       | 0.31%   |
| i3                       | 6        | 0.14%   |
| GNOME Classic            | 4        | 0.1%    |
| awesome                  | 4        | 0.1%    |
| openbox                  | 3        | 0.07%   |
| Enlightenment            | 3        | 0.07%   |
| sway                     | 2        | 0.05%   |
| qtile                    | 2        | 0.05%   |
| bspwm                    | 2        | 0.05%   |
| icewm                    | 1        | 0.02%   |
| 03WindowMaker            | 1        | 0.02%   |
| /usr/bin/openbox-session | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3385     | 83.09%  |
| Unknown | 354      | 8.69%   |
| Wayland | 302      | 7.41%   |
| Tty     | 31       | 0.76%   |
| Web     | 2        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2576     | 62.65%  |
| SDDM    | 514      | 12.5%   |
| GDM     | 381      | 9.27%   |
| TDM     | 236      | 5.74%   |
| LightDM | 185      | 4.5%    |
| GDM3    | 172      | 4.18%   |
| KDM     | 39       | 0.95%   |
| XDM     | 4        | 0.1%    |
| SLiM    | 2        | 0.05%   |
| SLIMSKI | 1        | 0.02%   |
| MDM     | 1        | 0.02%   |
| LXDM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pt_BR       | 2627     | 64.25%  |
| Unknown     | 746      | 18.24%  |
| en_US       | 624      | 15.26%  |
| C           | 51       | 1.25%   |
| en_GB       | 14       | 0.34%   |
| pt_PT       | 12       | 0.29%   |
| es_ES       | 5        | 0.12%   |
| en_CA       | 3        | 0.07%   |
| en_AG       | 2        | 0.05%   |
| eo          | 1        | 0.02%   |
| en_US.utf-8 | 1        | 0.02%   |
| en_IN       | 1        | 0.02%   |
| de_DE       | 1        | 0.02%   |
| C.UTF8      | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2849     | 69.86%  |
| EFI  | 1229     | 30.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3098     | 75.82%  |
| Overlay | 377      | 9.23%   |
| Unknown | 304      | 7.44%   |
| Btrfs   | 228      | 5.58%   |
| Xfs     | 34       | 0.83%   |
| Zfs     | 16       | 0.39%   |
| Ext3    | 8        | 0.2%    |
| F2fs    | 7        | 0.17%   |
| Ext2    | 7        | 0.17%   |
| Tmpfs   | 6        | 0.15%   |
| Aufs    | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2730     | 66.86%  |
| GPT     | 763      | 18.69%  |
| MBR     | 590      | 14.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3465     | 84.93%  |
| Yes       | 615      | 15.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2751     | 67.43%  |
| Yes       | 1329     | 32.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1074     | 26.88%  |
| Gigabyte Technology | 690      | 17.27%  |
| ASRock              | 352      | 8.81%   |
| Intel               | 314      | 7.86%   |
| Dell                | 230      | 5.76%   |
| Positivo            | 174      | 4.35%   |
| MSI                 | 168      | 4.2%    |
| Unknown             | 139      | 3.48%   |
| Hewlett-Packard     | 125      | 3.13%   |
| PCWare              | 98       | 2.45%   |
| Biostar             | 78       | 1.95%   |
| Lenovo              | 68       | 1.7%    |
| Pegatron            | 61       | 1.53%   |
| ECS                 | 58       | 1.45%   |
| Semp Toshiba        | 42       | 1.05%   |
| Itautec             | 35       | 0.88%   |
| Foxconn             | 27       | 0.68%   |
| Megaware            | 25       | 0.63%   |
| Huanan              | 24       | 0.6%    |
| OEM                 | 16       | 0.4%    |
| Login Informatica   | 13       | 0.33%   |
| Qbex                | 12       | 0.3%    |
| PCChips             | 10       | 0.25%   |
| Digiboard           | 10       | 0.25%   |
| VS Company          | 9        | 0.23%   |
| Philco              | 9        | 0.23%   |
| Supermicro          | 8        | 0.2%    |
| AMD                 | 8        | 0.2%    |
| Digitron            | 7        | 0.18%   |
| Phitronics          | 6        | 0.15%   |
| MACHINIST           | 6        | 0.15%   |
| INTELBRAS           | 6        | 0.15%   |
| IBM                 | 5        | 0.13%   |
| Centrium            | 5        | 0.13%   |
| CCE                 | 5        | 0.13%   |
| AMI                 | 5        | 0.13%   |
| MEGA                | 4        | 0.1%    |
| Kllisre             | 4        | 0.1%    |
| Daten Tecnologia    | 4        | 0.1%    |
| GALAX               | 3        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 153      | 3.83%   |
| ASUS All Series               | 131      | 3.28%   |
| Intel H61                     | 62       | 1.55%   |
| ASUS PRIME B450M-GAMING/BR    | 53       | 1.33%   |
| ASRock A320M-HD               | 47       | 1.18%   |
| ASUS PRIME A320M-K/BR         | 46       | 1.15%   |
| Semp Toshiba STI              | 41       | 1.03%   |
| Intel H55                     | 41       | 1.03%   |
| ASUS M5A78L-M LX/BR           | 41       | 1.03%   |
| Gigabyte H61M-S1              | 34       | 0.85%   |
| ASUS P8H61-M LX3 R2.0         | 31       | 0.78%   |
| Gigabyte A320M-S2H            | 30       | 0.75%   |
| Gigabyte B75M-D3H             | 29       | 0.73%   |
| ASUS M5A78L-M PLUS/USB3       | 29       | 0.73%   |
| ASRock N68-S3 FX              | 27       | 0.68%   |
| ASRock B450M Steel Legend     | 27       | 0.68%   |
| Gigabyte B450M DS3H           | 23       | 0.58%   |
| ASUS M5A78L-M/USB3            | 23       | 0.58%   |
| ASUS H61M-A/BR                | 23       | 0.58%   |
| ASUS TUF Gaming X570-PLUS_BR  | 21       | 0.53%   |
| ASUS P5G41T-M LX2/BR          | 21       | 0.53%   |
| Intel MAHOBAY                 | 20       | 0.5%    |
| Gigabyte AB350M-DS3H V2       | 20       | 0.5%    |
| ASUS P8H61-M LX2 R2.0         | 20       | 0.5%    |
| ASUS M4N68T-M LE              | 19       | 0.48%   |
| Positivo POS-EIH61CE          | 18       | 0.45%   |
| Gigabyte 970A-DS3P            | 18       | 0.45%   |
| HP Compaq 6005 Pro SFF PC     | 17       | 0.43%   |
| ASUS TUF B360M-PLUS GAMING/BR | 17       | 0.43%   |
| Intel B75                     | 15       | 0.38%   |
| Gigabyte G31M-ES2C            | 15       | 0.38%   |
| Gigabyte 945GCM-S2C           | 15       | 0.38%   |
| ASUS PRIME H310M-E R2.0/BR    | 15       | 0.38%   |
| ASUS PRIME A320M-K            | 15       | 0.38%   |
| ASUS P8H61-M LE/BR            | 15       | 0.38%   |
| ASRock N68-GS4 FX R2.0        | 15       | 0.38%   |
| MSI MS-7788                   | 14       | 0.35%   |
| Gigabyte G31M-ES2L            | 14       | 0.35%   |
| Dell XPS 8700                 | 14       | 0.35%   |
| Positivo POS-MI945AA          | 13       | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 204      | 5.11%   |
| Unknown                | 153      | 3.83%   |
| Dell OptiPlex          | 136      | 3.4%    |
| ASUS All               | 131      | 3.28%   |
| ASUS M5A78L-M          | 109      | 2.73%   |
| ASUS TUF               | 85       | 2.13%   |
| ASUS P8H61-M           | 75       | 1.88%   |
| HP Compaq              | 66       | 1.65%   |
| Intel H61              | 64       | 1.6%    |
| ASRock A320M-HD        | 48       | 1.2%    |
| Lenovo ThinkCentre     | 46       | 1.15%   |
| ASUS ROG               | 44       | 1.1%    |
| Semp Toshiba STI       | 42       | 1.05%   |
| Intel H55              | 41       | 1.03%   |
| Gigabyte H61M-S1       | 34       | 0.85%   |
| Itautec Infoway        | 32       | 0.8%    |
| Gigabyte B450M         | 31       | 0.78%   |
| Gigabyte A320M-S2H     | 30       | 0.75%   |
| Gigabyte B75M-D3H      | 29       | 0.73%   |
| ASRock N68-S3          | 28       | 0.7%    |
| ASRock B450M           | 27       | 0.68%   |
| Gigabyte GA-78LMT-USB3 | 25       | 0.63%   |
| Dell XPS               | 25       | 0.63%   |
| Dell Precision         | 24       | 0.6%    |
| ASUS P5G41T-M          | 24       | 0.6%    |
| Dell Inspiron          | 23       | 0.58%   |
| ASUS H61M-A            | 23       | 0.58%   |
| HP EliteDesk           | 22       | 0.55%   |
| Gigabyte B450          | 21       | 0.53%   |
| Intel MAHOBAY          | 20       | 0.5%    |
| Gigabyte AB350M-DS3H   | 20       | 0.5%    |
| ASUS M4N68T-M          | 19       | 0.48%   |
| ASRock N68-GS4         | 19       | 0.48%   |
| Positivo POS-EIH61CE   | 18       | 0.45%   |
| Gigabyte 970A-DS3P     | 18       | 0.45%   |
| ASUS P5GC-MX           | 18       | 0.45%   |
| ASUS M5A97             | 18       | 0.45%   |
| Intel X99              | 17       | 0.43%   |
| Intel B75              | 17       | 0.43%   |
| Dell Vostro            | 17       | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2011    | 427      | 10.69%  |
| 2018    | 424      | 10.61%  |
| 2012    | 421      | 10.54%  |
| 2017    | 337      | 8.43%   |
| 2013    | 310      | 7.76%   |
| 2010    | 302      | 7.56%   |
| 2014    | 284      | 7.11%   |
| 2009    | 254      | 6.36%   |
| 2019    | 249      | 6.23%   |
| 2008    | 211      | 5.28%   |
| 2016    | 180      | 4.5%    |
| 2007    | 179      | 4.48%   |
| 2020    | 162      | 4.05%   |
| 2015    | 98       | 2.45%   |
| 2021    | 61       | 1.53%   |
| 2006    | 59       | 1.48%   |
| 2005    | 17       | 0.43%   |
| 2022    | 10       | 0.25%   |
| 2004    | 5        | 0.13%   |
| Unknown | 5        | 0.13%   |
| 2003    | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3996     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3929     | 98.03%  |
| Enabled  | 79       | 1.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3996     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 1012     | 24.77%  |
| 8.01-16.0       | 950      | 23.26%  |
| 16.01-24.0      | 748      | 18.31%  |
| 4.01-8.0        | 731      | 17.89%  |
| 1.01-2.0        | 240      | 5.88%   |
| 32.01-64.0      | 206      | 5.04%   |
| 2.01-3.0        | 77       | 1.88%   |
| 24.01-32.0      | 53       | 1.3%    |
| 64.01-256.0     | 45       | 1.1%    |
| 0.51-1.0        | 19       | 0.47%   |
| Unknown         | 2        | 0.05%   |
| More than 256.0 | 1        | 0.02%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1702     | 38.61%  |
| 2.01-3.0   | 1108     | 25.14%  |
| 4.01-8.0   | 505      | 11.46%  |
| 3.01-4.0   | 500      | 11.34%  |
| 0.51-1.0   | 412      | 9.35%   |
| 8.01-16.0  | 102      | 2.31%   |
| 0.01-0.5   | 57       | 1.29%   |
| 16.01-24.0 | 15       | 0.34%   |
| 24.01-32.0 | 5        | 0.11%   |
| Unknown    | 2        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2075     | 50.01%  |
| 2       | 1172     | 28.25%  |
| 3       | 499      | 12.03%  |
| 4       | 225      | 5.42%   |
| 5       | 71       | 1.71%   |
| 0       | 46       | 1.11%   |
| 6       | 41       | 0.99%   |
| 7       | 10       | 0.24%   |
| 8       | 6        | 0.14%   |
| 9       | 3        | 0.07%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2449     | 60.63%  |
| Yes       | 1590     | 39.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3928     | 98.27%  |
| No        | 69       | 1.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2632     | 64.94%  |
| Yes       | 1421     | 35.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3389     | 83.99%  |
| Yes       | 646      | 16.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 3996     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Sao Paulo             | 562      | 13.52%  |
| Rio de Janeiro        | 264      | 6.35%   |
| Brasília             | 119      | 2.86%   |
| Belo Horizonte        | 114      | 2.74%   |
| Porto Alegre          | 97       | 2.33%   |
| Curitiba              | 96       | 2.31%   |
| Fortaleza             | 72       | 1.73%   |
| Campinas              | 58       | 1.4%    |
| Salvador              | 54       | 1.3%    |
| Recife                | 52       | 1.25%   |
| Goiânia              | 48       | 1.15%   |
| Santo André          | 43       | 1.03%   |
| Florianópolis        | 41       | 0.99%   |
| Guarulhos             | 38       | 0.91%   |
| Niterói              | 34       | 0.82%   |
| Manaus                | 33       | 0.79%   |
| Osasco                | 30       | 0.72%   |
| Sorocaba              | 28       | 0.67%   |
| Juiz de Fora          | 28       | 0.67%   |
| Campo Grande          | 28       | 0.67%   |
| Sao José dos Campos  | 27       | 0.65%   |
| Natal                 | 26       | 0.63%   |
| Maringá              | 26       | 0.63%   |
| Serra                 | 25       | 0.6%    |
| Londrina              | 25       | 0.6%    |
| Joinville             | 24       | 0.58%   |
| Duque de Caxias       | 24       | 0.58%   |
| Belém                | 23       | 0.55%   |
| Blumenau              | 22       | 0.53%   |
| Maceió               | 20       | 0.48%   |
| Ribeirao Preto        | 19       | 0.46%   |
| Teresina              | 18       | 0.43%   |
| Sao Luís             | 18       | 0.43%   |
| Sao Jose              | 18       | 0.43%   |
| Sao Goncalo           | 18       | 0.43%   |
| Cuiabá               | 18       | 0.43%   |
| Uberlândia           | 17       | 0.41%   |
| Joao Pessoa           | 17       | 0.41%   |
| Vitória              | 16       | 0.38%   |
| Sao Bernardo do Campo | 16       | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 1626     | 2462   | 25.37%  |
| WDC                   | 1219     | 1659   | 19.02%  |
| Samsung Electronics   | 890      | 1275   | 13.89%  |
| Kingston              | 714      | 964    | 11.14%  |
| Toshiba               | 289      | 343    | 4.51%   |
| SanDisk               | 280      | 399    | 4.37%   |
| Hitachi               | 167      | 200    | 2.61%   |
| China                 | 149      | 171    | 2.32%   |
| Crucial               | 116      | 142    | 1.81%   |
| Maxtor                | 110      | 129    | 1.72%   |
| A-DATA Technology     | 87       | 101    | 1.36%   |
| Silicon Motion        | 80       | 105    | 1.25%   |
| Lexar                 | 47       | 51     | 0.73%   |
| XPG                   | 40       | 50     | 0.62%   |
| Unknown               | 40       | 56     | 0.62%   |
| Realtek Semiconductor | 38       | 46     | 0.59%   |
| Intel                 | 34       | 39     | 0.53%   |
| Corsair               | 33       | 44     | 0.51%   |
| Phison                | 32       | 50     | 0.5%    |
| KingSpec              | 31       | 38     | 0.48%   |
| HGST                  | 27       | 31     | 0.42%   |
| Hewlett-Packard       | 23       | 28     | 0.36%   |
| JMicron Technology    | 19       | 21     | 0.3%    |
| PNY                   | 18       | 19     | 0.28%   |
| Patriot               | 17       | 25     | 0.27%   |
| Netac                 | 16       | 25     | 0.25%   |
| Gigabyte Technology   | 16       | 24     | 0.25%   |
| XrayDisk              | 13       | 16     | 0.2%    |
| LITEON                | 13       | 13     | 0.2%    |
| KingDian              | 13       | 14     | 0.2%    |
| OCZ                   | 11       | 11     | 0.17%   |
| Fujitsu               | 11       | 12     | 0.17%   |
| Smart                 | 9        | 11     | 0.14%   |
| ExcelStor             | 9        | 10     | 0.14%   |
| SK hynix              | 8        | 20     | 0.12%   |
| ADATA Technology      | 8        | 10     | 0.12%   |
| BHT                   | 7        | 11     | 0.11%   |
| Unknown               | 7        | 7      | 0.11%   |
| WALRAM                | 5        | 5      | 0.08%   |
| Team                  | 5        | 5      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD     | 237      | 3.32%   |
| Seagate ST500DM002-1BD142 500GB     | 225      | 3.16%   |
| Seagate ST1000DM010-2EP102 1TB      | 182      | 2.55%   |
| Kingston SA400S37120G 120GB SSD     | 148      | 2.08%   |
| Samsung HD322HJ 320GB               | 110      | 1.54%   |
| Kingston SA400S37480G 480GB SSD     | 104      | 1.46%   |
| Samsung HD161HJ 160GB               | 94       | 1.32%   |
| Samsung HD502HJ 500GB               | 89       | 1.25%   |
| Samsung HD502HI 500GB               | 89       | 1.25%   |
| Seagate ST1000DM003-1ER162 1TB      | 88       | 1.23%   |
| Seagate ST1000DM003-1CH162 1TB      | 82       | 1.15%   |
| WDC WD5000AAKX-003CA0 500GB         | 73       | 1.02%   |
| Kingston SV300S37A120G 120GB SSD    | 73       | 1.02%   |
| WDC WD10EARS-00Y5B1 1TB             | 63       | 0.88%   |
| Seagate ST3500418AS 500GB           | 62       | 0.87%   |
| SanDisk SSD PLUS 240GB              | 61       | 0.86%   |
| Seagate ST3500312CS 500GB           | 57       | 0.8%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 56       | 0.79%   |
| WDC WD10EZEX-00WN4A0 1TB            | 52       | 0.73%   |
| WDC WD10EZEX-00BN5A0 1TB            | 52       | 0.73%   |
| Toshiba DT01ACA050 500GB            | 52       | 0.73%   |
| Seagate ST2000DM006-2DM164 2TB      | 52       | 0.73%   |
| Seagate Expansion 2TB               | 52       | 0.73%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 50       | 0.7%    |
| Seagate ST31000524AS 1TB            | 50       | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 47       | 0.66%   |
| Toshiba HDWD110 1TB                 | 46       | 0.65%   |
| Crucial CT240BX500SSD1 240GB        | 46       | 0.65%   |
| Seagate ST3320418AS 320GB           | 44       | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 44       | 0.62%   |
| SanDisk SDSSDA120G 120GB            | 43       | 0.6%    |
| Samsung HD103SI 1TB                 | 42       | 0.59%   |
| Samsung HD161GJ 160GB               | 41       | 0.58%   |
| Samsung HD103SJ 1TB                 | 40       | 0.56%   |
| Seagate ST3500413AS 500GB           | 39       | 0.55%   |
| Seagate ST31000528AS 1TB            | 39       | 0.55%   |
| SanDisk SDSSDA240G 240GB            | 39       | 0.55%   |
| SanDisk SSD PLUS 120GB              | 38       | 0.53%   |
| Toshiba DT01ACA100 1TB              | 37       | 0.52%   |
| Maxtor STM3160215AS 160GB           | 34       | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1622     | 2446   | 39.49%  |
| WDC                 | 1092     | 1468   | 26.59%  |
| Samsung Electronics | 761      | 1029   | 18.53%  |
| Toshiba             | 278      | 329    | 6.77%   |
| Hitachi             | 167      | 200    | 4.07%   |
| Maxtor              | 105      | 123    | 2.56%   |
| HGST                | 27       | 31     | 0.66%   |
| Hewlett-Packard     | 13       | 15     | 0.32%   |
| Fujitsu             | 11       | 12     | 0.27%   |
| Unknown             | 9        | 9      | 0.22%   |
| ExcelStor           | 9        | 10     | 0.22%   |
| JMicron Technology  | 2        | 3      | 0.05%   |
| USB3.0              | 1        | 1      | 0.02%   |
| SAGE                | 1        | 2      | 0.02%   |
| SABRENT             | 1        | 1      | 0.02%   |
| MDT                 | 1        | 1      | 0.02%   |
| Lenovo              | 1        | 1      | 0.02%   |
| Initio              | 1        | 1      | 0.02%   |
| IBM                 | 1        | 3      | 0.02%   |
| FEASSO              | 1        | 2      | 0.02%   |
| China               | 1        | 1      | 0.02%   |
| Apple               | 1        | 1      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 699      | 935    | 37.46%  |
| SanDisk             | 255      | 364    | 13.67%  |
| China               | 148      | 170    | 7.93%   |
| WDC                 | 138      | 173    | 7.4%    |
| Crucial             | 111      | 136    | 5.95%   |
| Samsung Electronics | 97       | 176    | 5.2%    |
| A-DATA Technology   | 68       | 75     | 3.64%   |
| Lexar               | 47       | 51     | 2.52%   |
| KingSpec            | 31       | 38     | 1.66%   |
| Corsair             | 26       | 34     | 1.39%   |
| Intel               | 25       | 28     | 1.34%   |
| PNY                 | 16       | 17     | 0.86%   |
| Patriot             | 16       | 23     | 0.86%   |
| KingDian            | 13       | 14     | 0.7%    |
| Netac               | 12       | 20     | 0.64%   |
| Gigabyte Technology | 12       | 19     | 0.64%   |
| OCZ                 | 11       | 11     | 0.59%   |
| Smart               | 9        | 11     | 0.48%   |
| LITEON              | 9        | 9      | 0.48%   |
| Toshiba             | 7        | 9      | 0.38%   |
| Hewlett-Packard     | 7        | 9      | 0.38%   |
| Unknown             | 6        | 6      | 0.32%   |
| Seagate             | 6        | 7      | 0.32%   |
| BHT                 | 6        | 10     | 0.32%   |
| Unknown             | 6        | 6      | 0.32%   |
| Team                | 5        | 5      | 0.27%   |
| Maxtor              | 5        | 6      | 0.27%   |
| SK hynix            | 4        | 5      | 0.21%   |
| RZX                 | 4        | 6      | 0.21%   |
| Apacer              | 4        | 4      | 0.21%   |
| XrayDisk            | 3        | 3      | 0.16%   |
| Plextor             | 3        | 4      | 0.16%   |
| Pichau              | 3        | 3      | 0.16%   |
| KODAK               | 3        | 3      | 0.16%   |
| KINGBANK            | 3        | 5      | 0.16%   |
| HS-SSD-C100         | 3        | 3      | 0.16%   |
| Colorful            | 3        | 3      | 0.16%   |
| Zheino              | 2        | 5      | 0.11%   |
| SuperSSpeed         | 2        | 4      | 0.11%   |
| S3+                 | 2        | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3269     | 5690   | 60.98%  |
| SSD     | 1637     | 2459   | 30.54%  |
| NVMe    | 391      | 568    | 7.29%   |
| Unknown | 59       | 83     | 1.1%    |
| MMC     | 5        | 6      | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3849     | 8028   | 87.88%  |
| NVMe | 375      | 549    | 8.56%   |
| SAS  | 151      | 223    | 3.45%   |
| MMC  | 5        | 6      | 0.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3202     | 5411   | 63.08%  |
| 0.51-1.0   | 1365     | 1984   | 26.89%  |
| 1.01-2.0   | 345      | 514    | 6.8%    |
| 3.01-4.0   | 63       | 98     | 1.24%   |
| 2.01-3.0   | 59       | 81     | 1.16%   |
| 4.01-10.0  | 38       | 55     | 0.75%   |
| 10.01-20.0 | 4        | 6      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1056     | 24.84%  |
| 251-500        | 963      | 22.65%  |
| 501-1000       | 622      | 14.63%  |
| 1001-2000      | 421      | 9.9%    |
| 1-20           | 331      | 7.78%   |
| 51-100         | 299      | 7.03%   |
| 21-50          | 172      | 4.05%   |
| 2001-3000      | 160      | 3.76%   |
| More than 3000 | 134      | 3.15%   |
| Unknown        | 94       | 2.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1675     | 38.44%  |
| 21-50          | 768      | 17.63%  |
| 101-250        | 509      | 11.68%  |
| 51-100         | 449      | 10.31%  |
| 251-500        | 313      | 7.18%   |
| 501-1000       | 305      | 7%      |
| 1001-2000      | 154      | 3.53%   |
| Unknown        | 94       | 2.16%   |
| 2001-3000      | 50       | 1.15%   |
| More than 3000 | 40       | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 40       | 43     | 5.93%   |
| WDC WD5000AAKX-003CA0 500GB         | 24       | 24     | 3.56%   |
| Samsung Electronics HD322HJ 320GB   | 19       | 21     | 2.81%   |
| Samsung Electronics HD161HJ 160GB   | 17       | 18     | 2.52%   |
| Samsung Electronics HD502HI 500GB   | 16       | 18     | 2.37%   |
| Samsung Electronics HD502HJ 500GB   | 13       | 13     | 1.93%   |
| WDC WD10EARS-00Y5B1 1TB             | 11       | 13     | 1.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10       | 10     | 1.48%   |
| WDC WD3200AAJS-00L7A0 320GB         | 9        | 9      | 1.33%   |
| Seagate ST3500418AS 500GB           | 9        | 13     | 1.33%   |
| Samsung Electronics HD080HJ 80GB    | 9        | 11     | 1.33%   |
| Maxtor STM3160215AS 160GB           | 9        | 10     | 1.33%   |
| Seagate ST1000DM010-2EP102 1TB      | 8        | 11     | 1.19%   |
| Samsung Electronics HD103SJ 1TB     | 8        | 10     | 1.19%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 7        | 8      | 1.04%   |
| Seagate ST3320418AS 320GB           | 7        | 11     | 1.04%   |
| Seagate ST1500DL003-9VT16L 1TB      | 7        | 7      | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7        | 8      | 1.04%   |
| Seagate ST1000DM003-1CH162 1TB      | 7        | 9      | 1.04%   |
| Samsung Electronics HD250HJ 250GB   | 7        | 8      | 1.04%   |
| Seagate ST2000DM001-1CH164 2TB      | 6        | 7      | 0.89%   |
| Seagate ST1000DM003-9YN162 1TB      | 6        | 6      | 0.89%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 9      | 0.89%   |
| WDC WD5000AAKX-083CA1 500GB         | 5        | 5      | 0.74%   |
| Toshiba MQ01ABD050 500GB            | 5        | 5      | 0.74%   |
| Toshiba DT01ACA050 500GB            | 5        | 5      | 0.74%   |
| Seagate ST3500413AS 500GB           | 5        | 6      | 0.74%   |
| Seagate ST3500312CS 500GB           | 5        | 5      | 0.74%   |
| Seagate ST3250318AS 250GB           | 5        | 5      | 0.74%   |
| Seagate ST31000528AS 1TB            | 5        | 8      | 0.74%   |
| Samsung Electronics HD103SI 1TB     | 5        | 6      | 0.74%   |
| Samsung Electronics HD081GJ 80GB    | 5        | 5      | 0.74%   |
| Kingston SV300S37A120G 120GB SSD    | 5        | 5      | 0.74%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4        | 5      | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4        | 4      | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4        | 4      | 0.59%   |
| Seagate ST9320325AS 320GB           | 4        | 4      | 0.59%   |
| Seagate ST3160318AS 160GB           | 4        | 4      | 0.59%   |
| Seagate ST31000524AS 1TB            | 4        | 4      | 0.59%   |
| Seagate ST1000DM003-1ER162 1TB      | 4        | 6      | 0.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 206      | 258    | 32.54%  |
| WDC                 | 161      | 180    | 25.43%  |
| Samsung Electronics | 132      | 161    | 20.85%  |
| Hitachi             | 29       | 30     | 4.58%   |
| Toshiba             | 27       | 29     | 4.27%   |
| Kingston            | 22       | 26     | 3.48%   |
| Maxtor              | 18       | 19     | 2.84%   |
| SanDisk             | 6        | 6      | 0.95%   |
| China               | 6        | 6      | 0.95%   |
| XPG                 | 3        | 3      | 0.47%   |
| Intel               | 3        | 3      | 0.47%   |
| A-DATA Technology   | 3        | 3      | 0.47%   |
| OCZ                 | 2        | 2      | 0.32%   |
| Crucial             | 2        | 2      | 0.32%   |
| PNY                 | 1        | 1      | 0.16%   |
| Plextor             | 1        | 1      | 0.16%   |
| OCZ-VERTEX3         | 1        | 1      | 0.16%   |
| Netac               | 1        | 1      | 0.16%   |
| Mushkin             | 1        | 1      | 0.16%   |
| Initio              | 1        | 1      | 0.16%   |
| HGST                | 1        | 1      | 0.16%   |
| Hewlett-Packard     | 1        | 1      | 0.16%   |
| Fujitsu             | 1        | 1      | 0.16%   |
| FEASSO              | 1        | 2      | 0.16%   |
| ExcelStor           | 1        | 2      | 0.16%   |
| Corsair             | 1        | 1      | 0.16%   |
| Unknown             | 1        | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 206      | 258    | 35.95%  |
| WDC                 | 155      | 174    | 27.05%  |
| Samsung Electronics | 132      | 161    | 23.04%  |
| Hitachi             | 29       | 30     | 5.06%   |
| Toshiba             | 27       | 29     | 4.71%   |
| Maxtor              | 18       | 19     | 3.14%   |
| Initio              | 1        | 1      | 0.17%   |
| HGST                | 1        | 1      | 0.17%   |
| Hewlett-Packard     | 1        | 1      | 0.17%   |
| Fujitsu             | 1        | 1      | 0.17%   |
| FEASSO              | 1        | 2      | 0.17%   |
| ExcelStor           | 1        | 2      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 500      | 679    | 89.45%  |
| SSD  | 53       | 58     | 9.48%   |
| NVMe | 6        | 6      | 1.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 15.38%  |
| WDC WD1600BEVT-22ZCT0 160GB       | 1        | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 7.69%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 7.69%   |
| Seagate ST31000340NS 1TB          | 1        | 1      | 7.69%   |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 7.69%   |
| Samsung Electronics HD502HJ 500GB | 1        | 3      | 7.69%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 7.69%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 7.69%   |
| Samsung Electronics HD080HJ 80GB  | 1        | 1      | 7.69%   |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 38.46%  |
| Samsung Electronics | 5        | 7      | 38.46%  |
| WDC                 | 1        | 1      | 7.69%   |
| Toshiba             | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2770     | 6136   | 63.42%  |
| Works    | 1048     | 1912   | 23.99%  |
| Malfunc  | 537      | 743    | 12.29%  |
| Failed   | 13       | 15     | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2633     | 56.87%  |
| AMD                              | 1097     | 23.69%  |
| Nvidia                           | 206      | 4.45%   |
| Silicon Motion                   | 91       | 1.97%   |
| JMicron Technology               | 76       | 1.64%   |
| Marvell Technology Group         | 73       | 1.58%   |
| ASMedia Technology               | 61       | 1.32%   |
| Realtek Semiconductor            | 59       | 1.27%   |
| Samsung Electronics              | 55       | 1.19%   |
| Phison Electronics               | 49       | 1.06%   |
| VIA Technologies                 | 46       | 0.99%   |
| SanDisk                          | 43       | 0.93%   |
| ADATA Technology                 | 43       | 0.93%   |
| Kingston Technology Company      | 22       | 0.48%   |
| Micron/Crucial Technology        | 11       | 0.24%   |
| Silicon Integrated Systems [SiS] | 8        | 0.17%   |
| Broadcom / LSI                   | 8        | 0.17%   |
| LSI Logic / Symbios Logic        | 7        | 0.15%   |
| Lite-On Technology               | 6        | 0.13%   |
| Silicon Image                    | 5        | 0.11%   |
| SK hynix                         | 4        | 0.09%   |
| Seagate Technology               | 4        | 0.09%   |
| OCZ Technology Group             | 4        | 0.09%   |
| MAXIO Technology (Hangzhou)      | 3        | 0.06%   |
| Adaptec                          | 3        | 0.06%   |
| Shenzhen Longsys Electronics     | 2        | 0.04%   |
| Beijing Starblaze Technology     | 2        | 0.04%   |
| Unknown                          | 1        | 0.02%   |
| ULi Electronics                  | 1        | 0.02%   |
| Solid State Storage Technology   | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |
| Micron Technology                | 1        | 0.02%   |
| Lenovo                           | 1        | 0.02%   |
| Broadcom                         | 1        | 0.02%   |
| Biwin Storage Technology         | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 601      | 9.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 533      | 8.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 412      | 6.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 360      | 5.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 276      | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 274      | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 222      | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 222      | 3.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 218      | 3.29%   |
| AMD FCH SATA Controller D                                                               | 196      | 2.96%   |
| AMD 400 Series Chipset SATA Controller                                                  | 190      | 2.87%   |
| Nvidia MCP61 SATA Controller                                                            | 170      | 2.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 151      | 2.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 147      | 2.22%   |
| Nvidia MCP61 IDE                                                                        | 139      | 2.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 137      | 2.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 100      | 1.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 98       | 1.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 83       | 1.25%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 78       | 1.18%   |
| Intel SATA Controller [RAID mode]                                                       | 78       | 1.18%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 75       | 1.13%   |
| AMD 300 Series Chipset SATA Controller                                                  | 75       | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 61       | 0.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 59       | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 52       | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 51       | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 51       | 0.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 46       | 0.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 46       | 0.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 43       | 0.65%   |
| AMD FCH IDE Controller                                                                  | 39       | 0.59%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 37       | 0.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 37       | 0.56%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 36       | 0.54%   |
| JMicron JMB368 IDE controller                                                           | 35       | 0.53%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 34       | 0.51%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 33       | 0.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 31       | 0.47%   |
| AMD X370 Series Chipset SATA Controller                                                 | 31       | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2656     | 55.12%  |
| IDE  | 1647     | 34.18%  |
| NVMe | 381      | 7.91%   |
| RAID | 121      | 2.51%   |
| SCSI | 8        | 0.17%   |
| SAS  | 6        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 2695     | 67.44%  |
| AMD          | 1295     | 32.41%  |
| CentaurHauls | 5        | 0.13%   |
| Unknown      | 1        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor              | 88       | 2.19%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 73       | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 70       | 1.74%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 66       | 1.64%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 58       | 1.44%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 56       | 1.39%   |
| AMD Ryzen 5 3600 6-Core Processor           | 54       | 1.34%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 51       | 1.27%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 50       | 1.24%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 49       | 1.22%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 49       | 1.22%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 49       | 1.22%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 47       | 1.17%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 47       | 1.17%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 45       | 1.12%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 45       | 1.12%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 43       | 1.07%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 42       | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 40       | 1%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 38       | 0.95%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 37       | 0.92%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 33       | 0.82%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 32       | 0.8%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 30       | 0.75%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 29       | 0.72%   |
| AMD FX-8300 Eight-Core Processor            | 29       | 0.72%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 28       | 0.7%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 27       | 0.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 27       | 0.67%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 27       | 0.67%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 26       | 0.65%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 26       | 0.65%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 26       | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 25       | 0.62%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 25       | 0.62%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 25       | 0.62%   |
| AMD FX-8350 Eight-Core Processor            | 25       | 0.62%   |
| AMD FX-4300 Quad-Core Processor             | 25       | 0.62%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 24       | 0.6%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 23       | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 672      | 16.74%  |
| Intel Core i3           | 460      | 11.46%  |
| Intel Core i7           | 369      | 9.19%   |
| AMD Ryzen 5             | 300      | 7.47%   |
| AMD FX                  | 242      | 6.03%   |
| Intel Core 2 Duo        | 220      | 5.48%   |
| Intel Celeron           | 209      | 5.21%   |
| Intel Xeon              | 168      | 4.18%   |
| Intel Pentium Dual-Core | 167      | 4.16%   |
| AMD Ryzen 7             | 130      | 3.24%   |
| Intel Pentium           | 118      | 2.94%   |
| Intel Core 2 Quad       | 93       | 2.32%   |
| AMD Ryzen 3             | 85       | 2.12%   |
| Intel Pentium Dual      | 71       | 1.77%   |
| AMD Phenom II X4        | 70       | 1.74%   |
| AMD Athlon II X2        | 64       | 1.59%   |
| AMD Athlon 64 X2        | 41       | 1.02%   |
| AMD A8                  | 38       | 0.95%   |
| AMD Athlon              | 36       | 0.9%    |
| AMD A10                 | 35       | 0.87%   |
| Intel Core 2            | 32       | 0.8%    |
| Intel Atom              | 31       | 0.77%   |
| AMD A4                  | 31       | 0.77%   |
| AMD Sempron             | 30       | 0.75%   |
| Intel Pentium 4         | 28       | 0.7%    |
| AMD Ryzen 9             | 26       | 0.65%   |
| AMD Phenom II X6        | 26       | 0.65%   |
| AMD A6                  | 20       | 0.5%    |
| AMD Athlon II X4        | 18       | 0.45%   |
| Intel Pentium Gold      | 17       | 0.42%   |
| AMD Phenom II X2        | 17       | 0.42%   |
| Other                   | 16       | 0.4%    |
| Intel Core i9           | 16       | 0.4%    |
| AMD Phenom              | 14       | 0.35%   |
| Intel Genuine           | 13       | 0.32%   |
| Intel Pentium D         | 12       | 0.3%    |
| AMD Athlon II X3        | 12       | 0.3%    |
| AMD Ryzen 3 PRO         | 7        | 0.17%   |
| AMD E                   | 6        | 0.15%   |
| CentaurHauls VIA C7     | 5        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1572     | 39.16%  |
| 4       | 1440     | 35.87%  |
| 6       | 428      | 10.66%  |
| 8       | 194      | 4.83%   |
| 1       | 173      | 4.31%   |
| 3       | 126      | 3.14%   |
| 12      | 35       | 0.87%   |
| 16      | 15       | 0.37%   |
| 10      | 14       | 0.35%   |
| Unknown | 11       | 0.27%   |
| 24      | 2        | 0.05%   |
| 14      | 2        | 0.05%   |
| 28      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3978     | 99.52%  |
| 2       | 18       | 0.45%   |
| Unknown | 1        | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2065     | 51.6%   |
| 2       | 1926     | 48.13%  |
| Unknown | 11       | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3751     | 93.24%  |
| Unknown        | 228      | 5.67%   |
| 64-bit         | 29       | 0.72%   |
| 32-bit         | 15       | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 734      | 17.81%  |
| 0x306a9    | 349      | 8.47%   |
| 0x206a7    | 347      | 8.42%   |
| 0x1067a    | 346      | 8.39%   |
| 0x306c3    | 282      | 6.84%   |
| 0x06000852 | 147      | 3.57%   |
| 0x906e9    | 118      | 2.86%   |
| 0x010000c8 | 106      | 2.57%   |
| 0x906ea    | 102      | 2.47%   |
| 0x6fd      | 98       | 2.38%   |
| 0x0800820d | 74       | 1.8%    |
| 0x20655    | 67       | 1.63%   |
| 0x08701021 | 67       | 1.63%   |
| 0x08108109 | 65       | 1.58%   |
| 0x6fb      | 50       | 1.21%   |
| 0x08701013 | 49       | 1.19%   |
| 0x20652    | 43       | 1.04%   |
| 0x506e3    | 42       | 1.02%   |
| 0x10676    | 39       | 0.95%   |
| 0x306f2    | 38       | 0.92%   |
| 0x06001119 | 38       | 0.92%   |
| 0x30678    | 35       | 0.85%   |
| 0x08101016 | 35       | 0.85%   |
| 0x010000db | 31       | 0.75%   |
| 0x106e5    | 30       | 0.73%   |
| 0x08001138 | 30       | 0.73%   |
| 0x06003106 | 29       | 0.7%    |
| 0xa0653    | 27       | 0.66%   |
| 0x906ed    | 27       | 0.66%   |
| 0x906eb    | 26       | 0.63%   |
| 0x306e4    | 26       | 0.63%   |
| 0x10661    | 25       | 0.61%   |
| 0x010000dc | 25       | 0.61%   |
| 0x0600611a | 24       | 0.58%   |
| 0x0600063e | 23       | 0.56%   |
| 0x0810100b | 22       | 0.53%   |
| 0x206d7    | 20       | 0.49%   |
| 0x08001137 | 20       | 0.49%   |
| 0x6f2      | 18       | 0.44%   |
| 0x08108102 | 17       | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 442      | 11.04%  |
| Penryn           | 441      | 11.01%  |
| SandyBridge      | 416      | 10.39%  |
| Haswell          | 378      | 9.44%   |
| KabyLake         | 332      | 8.29%   |
| Piledriver       | 252      | 6.29%   |
| K10              | 251      | 6.27%   |
| Core             | 228      | 5.69%   |
| Zen+             | 201      | 5.02%   |
| Zen              | 173      | 4.32%   |
| Zen 2            | 152      | 3.8%    |
| Westmere         | 133      | 3.32%   |
| Silvermont       | 65       | 1.62%   |
| K8 Hammer        | 62       | 1.55%   |
| Skylake          | 60       | 1.5%    |
| CometLake        | 55       | 1.37%   |
| Zen 3            | 52       | 1.3%    |
| Nehalem          | 50       | 1.25%   |
| NetBurst         | 48       | 1.2%    |
| Bulldozer        | 39       | 0.97%   |
| Steamroller      | 36       | 0.9%    |
| Excavator        | 30       | 0.75%   |
| Bonnell          | 26       | 0.65%   |
| Bobcat           | 17       | 0.42%   |
| Jaguar           | 16       | 0.4%    |
| K10 Llano        | 13       | 0.32%   |
| Unknown          | 10       | 0.25%   |
| Broadwell        | 9        | 0.22%   |
| Goldmont plus    | 8        | 0.2%    |
| Icelake          | 5        | 0.12%   |
| Alderlake Hybrid | 3        | 0.07%   |
| Puma             | 1        | 0.02%   |
| K6               | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1521     | 36.21%  |
| Nvidia                           | 1459     | 34.74%  |
| AMD                              | 1169     | 27.83%  |
| VIA Technologies                 | 30       | 0.71%   |
| Matrox Electronics Systems       | 7        | 0.17%   |
| Silicon Integrated Systems [SiS] | 5        | 0.12%   |
| Silicon Motion                   | 4        | 0.1%    |
| ATI Technologies                 | 3        | 0.07%   |
| S3 Graphics                      | 1        | 0.02%   |
| ASPEED Technology                | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 246      | 5.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 214      | 4.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 165      | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 151      | 3.52%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 151      | 3.52%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 144      | 3.36%   |
| Nvidia GT218 [GeForce 210]                                                  | 136      | 3.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 95       | 2.22%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 94       | 2.19%   |
| Intel Core Processor Integrated Graphics Controller                         | 90       | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 80       | 1.87%   |
| AMD RS780L [Radeon 3000]                                                    | 74       | 1.73%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 74       | 1.73%   |
| Nvidia GK208B [GeForce GT 710]                                              | 66       | 1.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 63       | 1.47%   |
| Intel HD Graphics 630                                                       | 62       | 1.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 62       | 1.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 58       | 1.35%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 56       | 1.31%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 55       | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 55       | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 48       | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 46       | 1.07%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 46       | 1.07%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 44       | 1.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 43       | 1%      |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 42       | 0.98%   |
| Nvidia GF108 [GeForce GT 730]                                               | 36       | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 33       | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 32       | 0.75%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 32       | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 30       | 0.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 29       | 0.68%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 28       | 0.65%   |
| AMD RS880 [Radeon HD 4200]                                                  | 28       | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 26       | 0.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 26       | 0.61%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 25       | 0.58%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 24       | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 24       | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 1399     | 34.51%  |
| 1 x Nvidia              | 1379     | 34.02%  |
| 1 x AMD                 | 1106     | 27.28%  |
| Intel + Nvidia          | 39       | 0.96%   |
| 2 x AMD                 | 33       | 0.81%   |
| 1 x VIA                 | 29       | 0.72%   |
| Intel + AMD             | 18       | 0.44%   |
| AMD + Nvidia            | 16       | 0.39%   |
| 2 x Nvidia              | 13       | 0.32%   |
| 1 x Matrox              | 6        | 0.15%   |
| 1 x SiS                 | 5        | 0.12%   |
| Intel + Silicon Motion  | 2        | 0.05%   |
| Other                   | 1        | 0.02%   |
| 2 x Intel               | 1        | 0.02%   |
| 1 x Silicon Motion      | 1        | 0.02%   |
| 1 x S3 Graphics         | 1        | 0.02%   |
| Nvidia + Silicon Motion | 1        | 0.02%   |
| Intel + 2 x AMD         | 1        | 0.02%   |
| 1 x ASPEED              | 1        | 0.02%   |
| AMD + 2 x Nvidia        | 1        | 0.02%   |
| AMD + Matrox            | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3082     | 75.91%  |
| Proprietary | 779      | 19.19%  |
| Unknown     | 199      | 4.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1796     | 43.54%  |
| 1.01-2.0   | 638      | 15.47%  |
| 0.51-1.0   | 575      | 13.94%  |
| 0.01-0.5   | 454      | 11.01%  |
| 3.01-4.0   | 349      | 8.46%   |
| 7.01-8.0   | 149      | 3.61%   |
| 5.01-6.0   | 103      | 2.5%    |
| 2.01-3.0   | 39       | 0.95%   |
| 8.01-16.0  | 18       | 0.44%   |
| 4.01-5.0   | 2        | 0.05%   |
| 16.01-24.0 | 2        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 1050     | 26.62%  |
| Samsung Electronics  | 894      | 22.66%  |
| AOC                  | 599      | 15.18%  |
| Dell                 | 313      | 7.93%   |
| Philips              | 212      | 5.37%   |
| LG Electronics       | 137      | 3.47%   |
| Acer                 | 126      | 3.19%   |
| Hewlett-Packard      | 80       | 2.03%   |
| BenQ                 | 52       | 1.32%   |
| Sony                 | 47       | 1.19%   |
| Unknown              | 46       | 1.17%   |
| Positivo             | 35       | 0.89%   |
| Lenovo               | 33       | 0.84%   |
| Ancor Communications | 21       | 0.53%   |
| Panasonic            | 16       | 0.41%   |
| ASUSTek Computer     | 14       | 0.35%   |
| TXD                  | 12       | 0.3%    |
| Daewoo               | 12       | 0.3%    |
| GDH                  | 11       | 0.28%   |
| Toshiba              | 9        | 0.23%   |
| RTK                  | 9        | 0.23%   |
| NCS                  | 9        | 0.23%   |
| HB@                  | 9        | 0.23%   |
| Envision             | 9        | 0.23%   |
| AGO                  | 8        | 0.2%    |
| VIE                  | 7        | 0.18%   |
| JRY                  | 7        | 0.18%   |
| Unknown (XXX)        | 6        | 0.15%   |
| STA                  | 6        | 0.15%   |
| PZG                  | 6        | 0.15%   |
| MSI                  | 6        | 0.15%   |
| CVT                  | 6        | 0.15%   |
| ___                  | 5        | 0.13%   |
| Proview              | 5        | 0.13%   |
| MStar                | 5        | 0.13%   |
| Envision Peripherals | 5        | 0.13%   |
| SKY                  | 4        | 0.1%    |
| Semp Toshiba         | 4        | 0.1%    |
| Philco               | 4        | 0.1%    |
| AU Optronics         | 4        | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 87       | 2.06%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 56       | 1.33%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 51       | 1.21%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 47       | 1.11%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 42       | 1%      |
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 34       | 0.81%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 29       | 0.69%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 29       | 0.69%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 29       | 0.69%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 26       | 0.62%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 26       | 0.62%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 26       | 0.62%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 25       | 0.59%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                       | 24       | 0.57%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 23       | 0.55%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 22       | 0.52%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 22       | 0.52%   |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                | 21       | 0.5%    |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 20       | 0.47%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 20       | 0.47%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 19       | 0.45%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                       | 19       | 0.45%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 19       | 0.45%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch            | 18       | 0.43%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch               | 17       | 0.4%    |
| AOC 1943W AOC1943 1366x768 410x230mm 18.5-inch                       | 17       | 0.4%    |
| AOC 1619w AOC1619 1366x768 340x190mm 15.3-inch                       | 17       | 0.4%    |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 16       | 0.38%   |
| AOC 712Sa AOC1712 1280x1024 340x270mm 17.1-inch                      | 16       | 0.38%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 609x347mm 27.6-inch | 15       | 0.36%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                 | 15       | 0.36%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 15       | 0.36%   |
| Goldstar L1552S GSM3BAE 1024x768 304x228mm 15.0-inch                 | 15       | 0.36%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 15       | 0.36%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch | 14       | 0.33%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch    | 14       | 0.33%   |
| Samsung Electronics SA300/SA350 SAM0789 1366x768 410x230mm 18.5-inch | 14       | 0.33%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                   | 14       | 0.33%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 14       | 0.33%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 14       | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1329     | 33.36%  |
| 1366x768 (WXGA)    | 651      | 16.34%  |
| 1600x900 (HD+)     | 301      | 7.56%   |
| 1440x900 (WXGA+)   | 281      | 7.05%   |
| 1280x1024 (SXGA)   | 272      | 6.83%   |
| 1360x768           | 245      | 6.15%   |
| 2560x1080          | 198      | 4.97%   |
| 3840x2160 (4K)     | 147      | 3.69%   |
| 1680x1050 (WSXGA+) | 135      | 3.39%   |
| 1024x768 (XGA)     | 93       | 2.33%   |
| Unknown            | 88       | 2.21%   |
| 2560x1440 (QHD)    | 42       | 1.05%   |
| 1280x720 (HD)      | 36       | 0.9%    |
| 3840x1080          | 24       | 0.6%    |
| 1920x540           | 17       | 0.43%   |
| 1920x1200 (WUXGA)  | 15       | 0.38%   |
| 2288x1287          | 12       | 0.3%    |
| 3440x1440          | 11       | 0.28%   |
| 1152x864           | 9        | 0.23%   |
| 1280x800 (WXGA)    | 6        | 0.15%   |
| 4480x1080          | 5        | 0.13%   |
| 5760x1080          | 4        | 0.1%    |
| 3360x1080          | 4        | 0.1%    |
| 3286x1080          | 4        | 0.1%    |
| 3200x1080          | 4        | 0.1%    |
| 1600x1200          | 4        | 0.1%    |
| 2732x768           | 3        | 0.08%   |
| 6400x1080          | 2        | 0.05%   |
| 3520x1080          | 2        | 0.05%   |
| 3360x1050          | 2        | 0.05%   |
| 2800x900           | 2        | 0.05%   |
| 2720x1024          | 2        | 0.05%   |
| 2646x768           | 2        | 0.05%   |
| 2646x1024          | 2        | 0.05%   |
| 2560x1600          | 2        | 0.05%   |
| 1280x960           | 2        | 0.05%   |
| 640x480            | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 5760x2160          | 1        | 0.03%   |
| 5440x1080          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 604      | 15.1%   |
| 21      | 474      | 11.85%  |
| Unknown | 426      | 10.65%  |
| 23      | 413      | 10.33%  |
| 17      | 308      | 7.7%    |
| 15      | 271      | 6.78%   |
| 19      | 227      | 5.68%   |
| 20      | 217      | 5.43%   |
| 24      | 211      | 5.28%   |
| 27      | 167      | 4.18%   |
| 34      | 164      | 4.1%    |
| 22      | 89       | 2.23%   |
| 31      | 67       | 1.68%   |
| 72      | 40       | 1%      |
| 32      | 31       | 0.78%   |
| 28      | 31       | 0.78%   |
| 40      | 27       | 0.68%   |
| 84      | 26       | 0.65%   |
| 54      | 25       | 0.63%   |
| 26      | 24       | 0.6%    |
| 16      | 20       | 0.5%    |
| 46      | 19       | 0.48%   |
| 52      | 16       | 0.4%    |
| 14      | 15       | 0.38%   |
| 12      | 14       | 0.35%   |
| 13      | 12       | 0.3%    |
| 142     | 8        | 0.2%    |
| 47      | 7        | 0.18%   |
| 48      | 6        | 0.15%   |
| 39      | 5        | 0.13%   |
| 37      | 5        | 0.13%   |
| 25      | 5        | 0.13%   |
| 65      | 3        | 0.08%   |
| 50      | 3        | 0.08%   |
| 43      | 3        | 0.08%   |
| 41      | 3        | 0.08%   |
| 29      | 2        | 0.05%   |
| 8       | 2        | 0.05%   |
| 75      | 1        | 0.03%   |
| 64      | 1        | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 1507     | 38.73%  |
| 501-600        | 749      | 19.25%  |
| 301-350        | 508      | 13.06%  |
| Unknown        | 426      | 10.95%  |
| 701-800        | 195      | 5.01%   |
| 351-400        | 148      | 3.8%    |
| 601-700        | 123      | 3.16%   |
| 1001-1500      | 81       | 2.08%   |
| 1501-2000      | 67       | 1.72%   |
| 801-900        | 38       | 0.98%   |
| 201-300        | 32       | 0.82%   |
| More than 2000 | 8        | 0.21%   |
| 901-1000       | 7        | 0.18%   |
| 101-200        | 2        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2403     | 63.81%  |
| Unknown | 380      | 10.09%  |
| 16/10   | 363      | 9.64%   |
| 5/4     | 270      | 7.17%   |
| 21/9    | 181      | 4.81%   |
| 4/3     | 128      | 3.4%    |
| 3/2     | 31       | 0.82%   |
| 1.00    | 8        | 0.21%   |
| 6/5     | 1        | 0.03%   |
| 0.31    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 991      | 25.09%  |
| 141-150        | 765      | 19.37%  |
| 151-200        | 618      | 15.65%  |
| Unknown        | 426      | 10.78%  |
| 351-500        | 274      | 6.94%   |
| 101-110        | 247      | 6.25%   |
| 301-350        | 169      | 4.28%   |
| More than 1000 | 130      | 3.29%   |
| 251-300        | 87       | 2.2%    |
| 131-140        | 82       | 2.08%   |
| 501-1000       | 72       | 1.82%   |
| 111-120        | 27       | 0.68%   |
| 81-90          | 16       | 0.41%   |
| 91-100         | 16       | 0.41%   |
| 71-80          | 14       | 0.35%   |
| 121-130        | 12       | 0.3%    |
| 1-40           | 2        | 0.05%   |
| 51-60          | 1        | 0.03%   |
| 41-50          | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2435     | 64.03%  |
| 101-120 | 681      | 17.91%  |
| Unknown | 427      | 11.23%  |
| 1-50    | 187      | 4.92%   |
| 121-160 | 43       | 1.13%   |
| 161-240 | 30       | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3268     | 80.53%  |
| 2     | 523      | 12.89%  |
| 0     | 233      | 5.74%   |
| 3     | 30       | 0.74%   |
| 4     | 4        | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2812     | 52.4%   |
| Intel                             | 728      | 13.57%  |
| Qualcomm Atheros                  | 485      | 9.04%   |
| Ralink Technology                 | 304      | 5.67%   |
| Nvidia                            | 176      | 3.28%   |
| Broadcom                          | 127      | 2.37%   |
| TP-Link                           | 106      | 1.98%   |
| Qualcomm Atheros Communications   | 95       | 1.77%   |
| Ralink                            | 74       | 1.38%   |
| Samsung Electronics               | 52       | 0.97%   |
| D-Link                            | 48       | 0.89%   |
| VIA Technologies                  | 44       | 0.82%   |
| Marvell Technology Group          | 39       | 0.73%   |
| Microsoft                         | 37       | 0.69%   |
| D-Link System                     | 25       | 0.47%   |
| Broadcom Limited                  | 25       | 0.47%   |
| Xiaomi                            | 21       | 0.39%   |
| JMicron Technology                | 19       | 0.35%   |
| MediaTek                          | 17       | 0.32%   |
| Motorola PCS                      | 15       | 0.28%   |
| Motorola                          | 13       | 0.24%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.11%   |
| ASIX Electronics                  | 6        | 0.11%   |
| Mercucys                          | 5        | 0.09%   |
| ICS Advent                        | 5        | 0.09%   |
| Edimax Technology                 | 5        | 0.09%   |
| ASUSTek Computer                  | 5        | 0.09%   |
| 3Com                              | 5        | 0.09%   |
| Sundance Technology Inc / IC Plus | 4        | 0.07%   |
| DisplayLink                       | 4        | 0.07%   |
| Qualcomm                          | 3        | 0.06%   |
| LG Electronics                    | 3        | 0.06%   |
| Huawei Technologies               | 3        | 0.06%   |
| Hangzhou Silan Microelectronics   | 3        | 0.06%   |
| Encore Electronics                | 3        | 0.06%   |
| Accton Technology                 | 3        | 0.06%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.04%   |
| T & A Mobile Phones               | 2        | 0.04%   |
| STMicroelectronics                | 2        | 0.04%   |
| Linksys                           | 2        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2164     | 37.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 390      | 6.71%   |
| Ralink MT7601U Wireless Adapter                                   | 167      | 2.87%   |
| Nvidia MCP61 Ethernet                                             | 150      | 2.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 86       | 1.48%   |
| Qualcomm Atheros AR9271 802.11n                                   | 85       | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83       | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 79       | 1.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 76       | 1.31%   |
| Intel I211 Gigabit Network Connection                             | 73       | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 71       | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 69       | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 68       | 1.17%   |
| Ralink RT5370 Wireless Adapter                                    | 63       | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 61       | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 57       | 0.98%   |
| Intel Wi-Fi 6 AX200                                               | 49       | 0.84%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 46       | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 42       | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 42       | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 38       | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37       | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 33       | 0.57%   |
| Microsoft Xbox 360 Wireless Adapter                               | 32       | 0.55%   |
| Intel 82578DC Gigabit Network Connection                          | 32       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 31       | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 29       | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 29       | 0.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 27       | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 26       | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 26       | 0.45%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 25       | 0.43%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 25       | 0.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 24       | 0.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 22       | 0.38%   |
| Realtek 802.11ac NIC                                              | 22       | 0.38%   |
| Intel 82578DM Gigabit Network Connection                          | 22       | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 21       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 389      | 25.83%  |
| Ralink Technology                     | 304      | 20.19%  |
| Qualcomm Atheros                      | 226      | 15.01%  |
| Intel                                 | 139      | 9.23%   |
| TP-Link                               | 103      | 6.84%   |
| Qualcomm Atheros Communications       | 95       | 6.31%   |
| Ralink                                | 74       | 4.91%   |
| D-Link                                | 48       | 3.19%   |
| Microsoft                             | 37       | 2.46%   |
| Broadcom                              | 31       | 2.06%   |
| D-Link System                         | 16       | 1.06%   |
| MediaTek                              | 11       | 0.73%   |
| Mercucys                              | 5        | 0.33%   |
| Marvell Technology Group              | 5        | 0.33%   |
| Edimax Technology                     | 5        | 0.33%   |
| Encore Electronics                    | 3        | 0.2%    |
| Linksys                               | 2        | 0.13%   |
| IMC Networks                          | 2        | 0.13%   |
| Broadcom Limited                      | 2        | 0.13%   |
| ASUSTek Computer                      | 2        | 0.13%   |
| Texas Instruments                     | 1        | 0.07%   |
| Samsung Electronics                   | 1        | 0.07%   |
| Philips (or NXP)                      | 1        | 0.07%   |
| NetGear                               | 1        | 0.07%   |
| Micro Star International              | 1        | 0.07%   |
| Accton Technology                     | 1        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                      | 167      | 10.98%  |
| Qualcomm Atheros AR9271 802.11n                                      | 85       | 5.59%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 76       | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 68       | 4.47%   |
| Ralink RT5370 Wireless Adapter                                       | 63       | 4.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 57       | 3.75%   |
| Intel Wi-Fi 6 AX200                                                  | 49       | 3.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 38       | 2.5%    |
| Microsoft Xbox 360 Wireless Adapter                                  | 32       | 2.1%    |
| Realtek RTL8188EE Wireless Network Adapter                           | 29       | 1.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 27       | 1.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 26       | 1.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 25       | 1.64%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 25       | 1.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 24       | 1.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 22       | 1.45%   |
| Realtek 802.11ac NIC                                                 | 22       | 1.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 21       | 1.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 21       | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 21       | 1.38%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 21       | 1.38%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter           | 20       | 1.31%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 17       | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 16       | 1.05%   |
| Intel Wireless-AC 9260                                               | 15       | 0.99%   |
| Intel Wireless 7260                                                  | 14       | 0.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 14       | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 13       | 0.85%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter             | 13       | 0.85%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 13       | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 12       | 0.79%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 12       | 0.79%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 11       | 0.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 10       | 0.66%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 10       | 0.66%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 10       | 0.66%   |
| Ralink RT2070 Wireless Adapter                                       | 10       | 0.66%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 10       | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 10       | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 10       | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2689     | 64.44%  |
| Intel                             | 655      | 15.7%   |
| Qualcomm Atheros                  | 277      | 6.64%   |
| Nvidia                            | 176      | 4.22%   |
| Broadcom                          | 97       | 2.32%   |
| Samsung Electronics               | 51       | 1.22%   |
| VIA Technologies                  | 43       | 1.03%   |
| Marvell Technology Group          | 34       | 0.81%   |
| Broadcom Limited                  | 23       | 0.55%   |
| Xiaomi                            | 21       | 0.5%    |
| JMicron Technology                | 19       | 0.46%   |
| Motorola PCS                      | 11       | 0.26%   |
| D-Link System                     | 9        | 0.22%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.14%   |
| MediaTek                          | 6        | 0.14%   |
| ASIX Electronics                  | 6        | 0.14%   |
| ICS Advent                        | 5        | 0.12%   |
| 3Com                              | 5        | 0.12%   |
| Sundance Technology Inc / IC Plus | 4        | 0.1%    |
| DisplayLink                       | 4        | 0.1%    |
| TP-Link                           | 3        | 0.07%   |
| Qualcomm                          | 3        | 0.07%   |
| LG Electronics                    | 3        | 0.07%   |
| Hangzhou Silan Microelectronics   | 3        | 0.07%   |
| ASUSTek Computer                  | 3        | 0.07%   |
| T & A Mobile Phones               | 2        | 0.05%   |
| Huawei Technologies               | 2        | 0.05%   |
| Aquantia                          | 2        | 0.05%   |
| Apple                             | 2        | 0.05%   |
| Accton Technology                 | 2        | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.02%   |
| Spreadtrum Communications         | 1        | 0.02%   |
| SK hynix                          | 1        | 0.02%   |
| OPPO Electronics                  | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| AMD                               | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2164     | 50.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 390      | 9.18%   |
| Nvidia MCP61 Ethernet                                             | 150      | 3.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 86       | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83       | 1.95%   |
| Intel Ethernet Connection (2) I219-V                              | 79       | 1.86%   |
| Intel I211 Gigabit Network Connection                             | 73       | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 71       | 1.67%   |
| Intel Ethernet Connection (7) I219-V                              | 69       | 1.62%   |
| Intel 82579V Gigabit Network Connection                           | 61       | 1.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 46       | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 42       | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 42       | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37       | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 0.82%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 33       | 0.78%   |
| Intel 82578DC Gigabit Network Connection                          | 32       | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 31       | 0.73%   |
| Intel Ethernet Connection (2) I218-V                              | 29       | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 26       | 0.61%   |
| Intel 82578DM Gigabit Network Connection                          | 22       | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 21       | 0.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 19       | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19       | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18       | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17       | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 17       | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15       | 0.35%   |
| Intel Ethernet Controller I225-V                                  | 14       | 0.33%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 14       | 0.33%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 13       | 0.31%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 13       | 0.31%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 13       | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.28%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 0.28%   |
| Motorola PCS moto g(6) plus                                       | 11       | 0.26%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 11       | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 10       | 0.24%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 10       | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3928     | 72.9%   |
| WiFi     | 1421     | 26.37%  |
| Modem    | 28       | 0.52%   |
| Unknown  | 11       | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3141     | 76.89%  |
| WiFi     | 943      | 23.08%  |
| Unknown  | 1        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3154     | 78.38%  |
| 2     | 743      | 18.46%  |
| 0     | 65       | 1.62%   |
| 3     | 55       | 1.37%   |
| 4     | 5        | 0.12%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3346     | 81.81%  |
| Yes  | 744      | 18.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 359      | 55.15%  |
| Intel                           | 122      | 18.74%  |
| Qualcomm Atheros Communications | 50       | 7.68%   |
| Realtek Semiconductor           | 44       | 6.76%   |
| Broadcom                        | 21       | 3.23%   |
| ASUSTek Computer                | 17       | 2.61%   |
| MediaTek                        | 7        | 1.08%   |
| Integrated System Solution      | 7        | 1.08%   |
| IMC Networks                    | 5        | 0.77%   |
| Apple                           | 5        | 0.77%   |
| Conwise Technology              | 3        | 0.46%   |
| Unknown                         | 3        | 0.46%   |
| Foxconn / Hon Hai               | 2        | 0.31%   |
| SINO WEALTH                     | 1        | 0.15%   |
| Realtek                         | 1        | 0.15%   |
| Ralink                          | 1        | 0.15%   |
| Motorola PCS                    | 1        | 0.15%   |
| Micro Star International        | 1        | 0.15%   |
| D-Link                          | 1        | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 359      | 55.06%  |
| Realtek Bluetooth Radio                               | 42       | 6.44%   |
| Intel AX200 Bluetooth                                 | 42       | 6.44%   |
| Intel Bluetooth wireless interface                    | 34       | 5.21%   |
| Qualcomm Atheros  Bluetooth Device                    | 20       | 3.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 15       | 2.3%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 14       | 2.15%   |
| Intel Wireless-AC 3168 Bluetooth                      | 10       | 1.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 9        | 1.38%   |
| MediaTek Wireless_Device                              | 7        | 1.07%   |
| Intel AX210 Bluetooth                                 | 7        | 1.07%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 5        | 0.77%   |
| ASUS Bluetooth Radio                                  | 5        | 0.77%   |
| Apple Bluetooth USB Host Controller                   | 5        | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 4        | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4        | 0.61%   |
| Intel AX201 Bluetooth                                 | 4        | 0.61%   |
| Integrated System Solution Bluetooth Device           | 4        | 0.61%   |
| Broadcom BCM92045B3 ROM                               | 4        | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 0.61%   |
| ASUS Bluetooth Adapter                                | 4        | 0.61%   |
| Qualcomm Atheros Bluetooth                            | 3        | 0.46%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.46%   |
| IMC Networks Bluetooth Radio                          | 3        | 0.46%   |
| Conwise CW6622                                        | 3        | 0.46%   |
| Unknown                                               | 3        | 0.46%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 0.31%   |
| Broadcom Bluetooth Controller                         | 2        | 0.31%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 2        | 0.31%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle    | 2        | 0.31%   |
| Broadcom BCM2210 Bluetooth                            | 2        | 0.31%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 0.31%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.31%   |
| ASUS BCM20702A0                                       | 2        | 0.31%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.15%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 0.15%   |
| Realtek 802.11n WLAN Adapter                          | 1        | 0.15%   |
| Realtek Bluetooth Radio                               | 1        | 0.15%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.15%   |
| Motorola PCS Bluetooth Device                         | 1        | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 2593     | 43.12%  |
| AMD                                             | 1466     | 24.38%  |
| Nvidia                                          | 1295     | 21.53%  |
| C-Media Electronics                             | 159      | 2.64%   |
| Generalplus Technology                          | 70       | 1.16%   |
| VIA Technologies                                | 48       | 0.8%    |
| JMTek                                           | 41       | 0.68%   |
| Logitech                                        | 40       | 0.67%   |
| Creative Labs                                   | 36       | 0.6%    |
| Texas Instruments                               | 25       | 0.42%   |
| Kingston Technology                             | 23       | 0.38%   |
| Corsair                                         | 17       | 0.28%   |
| Microsoft                                       | 14       | 0.23%   |
| Tenx Technology                                 | 12       | 0.2%    |
| BEHRINGER International                         | 11       | 0.18%   |
| Razer USA                                       | 10       | 0.17%   |
| Plantronics                                     | 9        | 0.15%   |
| Licensed by Sony Computer Entertainment America | 9        | 0.15%   |
| Silicon Integrated Systems [SiS]                | 7        | 0.12%   |
| GN Netcom                                       | 7        | 0.12%   |
| Sony                                            | 6        | 0.1%    |
| M-Audio                                         | 6        | 0.1%    |
| Fry's Electronics                               | 6        | 0.1%    |
| Philips (or NXP)                                | 5        | 0.08%   |
| Focusrite-Novation                              | 5        | 0.08%   |
| Creative Technology                             | 5        | 0.08%   |
| Cirrus Logic                                    | 5        | 0.08%   |
| BY EDIFIER                                      | 5        | 0.08%   |
| SteelSeries ApS                                 | 4        | 0.07%   |
| Goldvish                                        | 4        | 0.07%   |
| Dell                                            | 4        | 0.07%   |
| UCQ01000                                        | 3        | 0.05%   |
| JBL                                             | 3        | 0.05%   |
| Elite Silicon                                   | 3        | 0.05%   |
| Cambridge Silicon Radio                         | 3        | 0.05%   |
| ATI Technologies                                | 3        | 0.05%   |
| ASUSTek Computer                                | 3        | 0.05%   |
| Turtle Beach                                    | 2        | 0.03%   |
| Tdlasunnic                                      | 2        | 0.03%   |
| LG Electronics                                  | 2        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 591      | 8.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 533      | 7.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 360      | 5.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 291      | 4.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 222      | 3.19%   |
| AMD Family 17h/19h HD Audio Controller                                            | 209      | 3%      |
| Nvidia High Definition Audio Controller                                           | 194      | 2.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 192      | 2.76%   |
| AMD Starship/Matisse HD Audio Controller                                          | 175      | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 172      | 2.47%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 167      | 2.4%    |
| Nvidia MCP61 High Definition Audio                                                | 164      | 2.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 153      | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 152      | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 143      | 2.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 134      | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 129      | 1.85%   |
| AMD FCH Azalia Controller                                                         | 123      | 1.77%   |
| Intel 200 Series PCH HD Audio                                                     | 121      | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                        | 113      | 1.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 105      | 1.51%   |
| Nvidia GF108 High Definition Audio Controller                                     | 92       | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 88       | 1.26%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 78       | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                     | 76       | 1.09%   |
| Generalplus Technology USB Audio Device                                           | 70       | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 67       | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 55       | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                                     | 51       | 0.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 47       | 0.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 47       | 0.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 46       | 0.66%   |
| Nvidia GP104 High Definition Audio Controller                                     | 45       | 0.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 43       | 0.62%   |
| Nvidia GF119 HDMI Audio Controller                                                | 42       | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                                | 39       | 0.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 39       | 0.56%   |
| Nvidia GM206 High Definition Audio Controller                                     | 38       | 0.55%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                | 38       | 0.55%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 37       | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 544      | 29.68%  |
| Kingston            | 464      | 25.31%  |
| Corsair             | 154      | 8.4%    |
| Smart               | 112      | 6.11%   |
| Crucial             | 87       | 4.75%   |
| A-DATA Technology   | 60       | 3.27%   |
| Samsung Electronics | 57       | 3.11%   |
| SK hynix            | 51       | 2.78%   |
| Team                | 33       | 1.8%    |
| G.Skill             | 32       | 1.75%   |
| Unknown             | 25       | 1.36%   |
| Teikon              | 23       | 1.25%   |
| Micron Technology   | 22       | 1.2%    |
| Multilaser          | 19       | 1.04%   |
| Patriot             | 12       | 0.65%   |
| Apacer              | 10       | 0.55%   |
| Atermiter           | 8        | 0.44%   |
| GeIL                | 7        | 0.38%   |
| Kreton              | 6        | 0.33%   |
| Avant               | 6        | 0.33%   |
| Unknown (82B5)      | 5        | 0.27%   |
| HBS                 | 5        | 0.27%   |
| Elpida              | 5        | 0.27%   |
| CSX                 | 5        | 0.27%   |
| RZX                 | 4        | 0.22%   |
| Nanya Technology    | 4        | 0.22%   |
| MemoWise            | 4        | 0.22%   |
| Kllisre             | 4        | 0.22%   |
| GLOWAY              | 4        | 0.22%   |
| Smart Modular       | 3        | 0.16%   |
| Qbex                | 3        | 0.16%   |
| Positivo            | 3        | 0.16%   |
| Kingmax             | 3        | 0.16%   |
| AMD                 | 3        | 0.16%   |
| Transcend           | 2        | 0.11%   |
| Silicon Power       | 2        | 0.11%   |
| SanDisk             | 2        | 0.11%   |
| Qimonda             | 2        | 0.11%   |
| PUSKILL             | 2        | 0.11%   |
| pqi                 | 2        | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 41       | 2%      |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 30       | 1.46%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 30       | 1.46%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 29       | 1.42%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 28       | 1.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 26       | 1.27%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 26       | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 25       | 1.22%   |
| Unknown                                                | 25       | 1.22%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 17       | 0.83%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s    | 16       | 0.78%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 15       | 0.73%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 15       | 0.73%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 15       | 0.73%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 15       | 0.73%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 14       | 0.68%   |
| Smart RAM SH564128FH8N6TNSQG 4096MB DIMM DDR3 1600MT/s | 14       | 0.68%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s  | 13       | 0.63%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 12       | 0.59%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 12       | 0.59%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 12       | 0.59%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 11       | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 11       | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2                    | 11       | 0.54%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s  | 11       | 0.54%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s   | 11       | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 10       | 0.49%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s    | 10       | 0.49%   |
| Smart RAM SH564568FH8N0QHSCR 2GB DIMM DDR3 1333MT/s    | 10       | 0.49%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s          | 10       | 0.49%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s    | 10       | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 9        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 9        | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 9        | 0.44%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s    | 9        | 0.44%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 9        | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 8        | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s           | 8        | 0.39%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 8        | 0.39%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 8        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 648      | 40.15%  |
| DDR4         | 520      | 32.22%  |
| Unknown      | 175      | 10.84%  |
| DDR2         | 125      | 7.74%   |
| SDRAM        | 110      | 6.82%   |
| DDR          | 32       | 1.98%   |
| LPDDR4       | 1        | 0.06%   |
| DRAM         | 1        | 0.06%   |
| DDR5         | 1        | 0.06%   |
| DDR2 FB-DIMM | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1536     | 96.24%  |
| SODIMM  | 56       | 3.51%   |
| RIMM    | 3        | 0.19%   |
| FB-DIMM | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 610      | 33.81%  |
| 8192  | 553      | 30.65%  |
| 2048  | 380      | 21.06%  |
| 16384 | 141      | 7.82%   |
| 1024  | 70       | 3.88%   |
| 32768 | 34       | 1.88%   |
| 512   | 12       | 0.67%   |
| 256   | 2        | 0.11%   |
| 1536  | 1        | 0.06%   |
| 16    | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 371      | 20.85%  |
| 1600    | 306      | 17.2%   |
| Unknown | 137      | 7.7%    |
| 2400    | 116      | 6.52%   |
| 800     | 93       | 5.23%   |
| 667     | 78       | 4.38%   |
| 2667    | 68       | 3.82%   |
| 3200    | 57       | 3.2%    |
| 3400    | 54       | 3.04%   |
| 3600    | 53       | 2.98%   |
| 3000    | 53       | 2.98%   |
| 2133    | 53       | 2.98%   |
| 1867    | 37       | 2.08%   |
| 1866    | 30       | 1.69%   |
| 3466    | 29       | 1.63%   |
| 2800    | 23       | 1.29%   |
| 1066    | 22       | 1.24%   |
| 1067    | 18       | 1.01%   |
| 2666    | 17       | 0.96%   |
| 3151    | 16       | 0.9%    |
| 2933    | 14       | 0.79%   |
| 400     | 14       | 0.79%   |
| 333     | 14       | 0.79%   |
| 533     | 11       | 0.62%   |
| 3800    | 10       | 0.56%   |
| 3733    | 10       | 0.56%   |
| 3334    | 8        | 0.45%   |
| 3333    | 6        | 0.34%   |
| 1334    | 6        | 0.34%   |
| 41632   | 4        | 0.22%   |
| 3266    | 3        | 0.17%   |
| 3066    | 3        | 0.17%   |
| 2733    | 3        | 0.17%   |
| 2132    | 3        | 0.17%   |
| 49926   | 2        | 0.11%   |
| 5354    | 2        | 0.11%   |
| 3100    | 2        | 0.11%   |
| 3007    | 2        | 0.11%   |
| 1400    | 2        | 0.11%   |
| 1332    | 2        | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 84       | 47.46%  |
| Seiko Epson           | 40       | 22.6%   |
| Samsung Electronics   | 16       | 9.04%   |
| Canon                 | 14       | 7.91%   |
| Brother Industries    | 13       | 7.34%   |
| QinHeng Electronics   | 2        | 1.13%   |
| Lexmark International | 2        | 1.13%   |
| Apple                 | 2        | 1.13%   |
| Ricoh                 | 1        | 0.56%   |
| Prolific Technology   | 1        | 0.56%   |
| Oki Data              | 1        | 0.56%   |
| ARGOX                 | 1        | 0.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson L395 Series                      | 8        | 4.49%   |
| HP DeskJet 2130 series                       | 7        | 3.93%   |
| Seiko Epson L365 Series                      | 6        | 3.37%   |
| HP Ink Tank Wireless 410 series              | 6        | 3.37%   |
| Seiko Epson L355 Series                      | 5        | 2.81%   |
| Seiko Epson ET-2710 Series                   | 5        | 2.81%   |
| HP Deskjet 3050 J610 series                  | 5        | 2.81%   |
| HP Deskjet 2540 series                       | 5        | 2.81%   |
| Canon G3010 series                           | 5        | 2.81%   |
| Samsung SCX-4200 series                      | 4        | 2.25%   |
| Samsung M2070 Series                         | 4        | 2.25%   |
| HP LaserJet P1005                            | 4        | 2.25%   |
| HP DeskJet F4100 Printer series              | 4        | 2.25%   |
| HP DeskJet 2620 All-in-One Printer           | 4        | 2.25%   |
| HP Deskjet 2050 J510                         | 4        | 2.25%   |
| HP LaserJet Professional P1102w              | 3        | 1.69%   |
| HP LaserJet 1020                             | 3        | 1.69%   |
| HP Deskjet F4400 series                      | 3        | 1.69%   |
| HP DeskJet F4200 series                      | 3        | 1.69%   |
| HP DeskJet 3630 series                       | 3        | 1.69%   |
| Brother HL-1200 series                       | 3        | 1.69%   |
| Seiko Epson XP-243 245 247 Series            | 2        | 1.12%   |
| Seiko Epson L375 Series                      | 2        | 1.12%   |
| Seiko Epson L3110 Series                     | 2        | 1.12%   |
| Seiko Epson L210 Series                      | 2        | 1.12%   |
| Samsung SCX-3200 Series                      | 2        | 1.12%   |
| Samsung M2020 Series                         | 2        | 1.12%   |
| QinHeng CH340S                               | 2        | 1.12%   |
| HP Printing Support                          | 2        | 1.12%   |
| HP LaserJet 1018                             | 2        | 1.12%   |
| HP Deskjet 4620 series                       | 2        | 1.12%   |
| HP DeskJet 2700 series                       | 2        | 1.12%   |
| Canon PIXMA MG3000 series                    | 2        | 1.12%   |
| Brother HL-1210W series                      | 2        | 1.12%   |
| Brother DCP-7055 scanner/printer             | 2        | 1.12%   |
| Apple Gamesir-T1s 2.0b                       | 2        | 1.12%   |
| Seiko Epson XP-211 214 216 Series            | 1        | 0.56%   |
| Seiko Epson Printer                          | 1        | 0.56%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 0.56%   |
| Seiko Epson L4150 Series                     | 1        | 0.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 6        | 42.86%  |
| Canon           | 5        | 35.71%  |
| Seiko Epson     | 2        | 14.29%  |
| Mustek Systems  | 1        | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                        | 4        | 28.57%  |
| Canon CanoScan LIDE 25                                  | 4        | 28.57%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 7.14%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 7.14%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 7.14%   |
| HP ScanJet G4050                                        | 1        | 7.14%   |
| HP ScanJet 3800c                                        | 1        | 7.14%   |
| Canon CanoScan LiDE 210                                 | 1        | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 187      | 31.69%  |
| Generalplus Technology        | 42       | 7.12%   |
| Microsoft                     | 40       | 6.78%   |
| Z-Star Microelectronics       | 33       | 5.59%   |
| Samsung Electronics           | 33       | 5.59%   |
| Microdia                      | 32       | 5.42%   |
| Aveo Technology               | 26       | 4.41%   |
| GEMBIRD                       | 16       | 2.71%   |
| Cubeternet                    | 13       | 2.2%    |
| Sunplus Innovation Technology | 11       | 1.86%   |
| Pixart Imaging                | 11       | 1.86%   |
| Jieli Technology              | 11       | 1.86%   |
| Chicony Electronics           | 10       | 1.69%   |
| LG Electronics                | 8        | 1.36%   |
| Genesys Logic                 | 8        | 1.36%   |
| Alcor Micro                   | 8        | 1.36%   |
| MacroSilicon                  | 6        | 1.02%   |
| Arkmicro Technologies         | 6        | 1.02%   |
| Philips (or NXP)              | 5        | 0.85%   |
| KYE Systems (Mouse Systems)   | 5        | 0.85%   |
| Hewlett-Packard               | 5        | 0.85%   |
| Apple                         | 5        | 0.85%   |
| Acer                          | 5        | 0.85%   |
| Sunplus Technology            | 4        | 0.68%   |
| Realtek Semiconductor         | 4        | 0.68%   |
| Lenovo                        | 4        | 0.68%   |
| Huawei Technologies           | 4        | 0.68%   |
| Sonix Technology              | 3        | 0.51%   |
| Silicon Motion                | 3        | 0.51%   |
| IMC Networks                  | 3        | 0.51%   |
| A4Tech                        | 3        | 0.51%   |
| Xiongmai                      | 2        | 0.34%   |
| SunplusIT                     | 2        | 0.34%   |
| Mimaki Engineering            | 2        | 0.34%   |
| GenesysLogic Technology       | 2        | 0.34%   |
| Creative Technology           | 2        | 0.34%   |
| AVerMedia Technologies        | 2        | 0.34%   |
| Asuscom Network               | 2        | 0.34%   |
| ARC International             | 2        | 0.34%   |
| WCM_USB                       | 1        | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 73       | 12.33%  |
| Logitech HD Pro Webcam C920             | 42       | 7.09%   |
| Samsung Galaxy series, misc. (MTP mode) | 32       | 5.41%   |
| Generalplus GENERAL WEBCAM              | 32       | 5.41%   |
| Logitech C922 Pro Stream Webcam         | 17       | 2.87%   |
| GEMBIRD USB2.0 PC CAMERA                | 15       | 2.53%   |
| Z-Star Venus USB2.0 Camera              | 14       | 2.36%   |
| Aveo USB2.0 Camera                      | 12       | 2.03%   |
| Logitech HD Webcam C525                 | 11       | 1.86%   |
| Logitech BRIO Ultra HD Webcam           | 11       | 1.86%   |
| Jieli USB PHY 2.0                       | 11       | 1.86%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro    | 10       | 1.69%   |
| Generalplus 808 Camera                  | 10       | 1.69%   |
| Z-Star USB2.0 Camera                    | 8        | 1.35%   |
| Microsoft LifeCam VX-500 [1357]         | 8        | 1.35%   |
| Microdia Integrated Camera              | 8        | 1.35%   |
| Microsoft LifeCam HD-3000               | 7        | 1.18%   |
| Microdia USB Live camera                | 7        | 1.18%   |
| Logitech C920 PRO HD Webcam             | 7        | 1.18%   |
| Aveo Camera                             | 7        | 1.18%   |
| Microsoft LifeCam VX-800                | 6        | 1.01%   |
| Microsoft LifeCam VX-2000               | 6        | 1.01%   |
| Microsoft LifeCam HD-5000               | 6        | 1.01%   |
| Microsoft LifeCam Cinema                | 6        | 1.01%   |
| Logitech Webcam C925e                   | 6        | 1.01%   |
| Chicony HP Webcam                       | 6        | 1.01%   |
| Alcor Micro USB 2.0 PC Camera           | 6        | 1.01%   |
| Sunplus FHD Camera Microphone           | 5        | 0.84%   |
| Philips (or NXP) Webcam SPC530NC        | 5        | 0.84%   |
| Microdia Sonix USB 2.0 Camera           | 5        | 0.84%   |
| MacroSilicon USB Video                  | 5        | 0.84%   |
| Cubeternet GL-UPC822 UVC WebCam         | 5        | 0.84%   |
| Aveo UVC camera (Bresser microscope)    | 5        | 0.84%   |
| Lenovo FHD Webcam                       | 4        | 0.68%   |
| Huawei HiCamera                         | 4        | 0.68%   |
| Acer BisonCam, NB Pro                   | 4        | 0.68%   |
| Z-Star Sirius USB2.0 Camera             | 3        | 0.51%   |
| Sunplus USB Web-CAM                     | 3        | 0.51%   |
| Sunplus Full HD webcam                  | 3        | 0.51%   |
| Microdia Webcam Vitade AF               | 3        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Futronic Technology | 1        | 50%     |
| Dell                | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Futronic FS81 Fingerprint Scanner Module       | 1        | 50%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 13       | 39.39%  |
| Giesecke & Devrient               | 4        | 12.12%  |
| Alcor Micro                       | 4        | 12.12%  |
| Chicony Electronics               | 3        | 9.09%   |
| Watchdata                         | 2        | 6.06%   |
| SCM Microsystems                  | 2        | 6.06%   |
| OmniKey                           | 2        | 6.06%   |
| VASCO Data Security International | 1        | 3.03%   |
| Realtek Semiconductor             | 1        | 3.03%   |
| Aladdin Knowledge Systems         | 1        | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 12       | 36.36%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 12.12%  |
| Giesecke & Devrient StarSign CUT S                              | 3        | 9.09%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 3        | 9.09%   |
| Watchdata USB Key                                               | 2        | 6.06%   |
| OmniKey CardMan 3021 / 3121                                     | 2        | 6.06%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 3.03%   |
| SCM Microsystems SCR35xx Smart Card Reader                      | 1        | 3.03%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 1        | 3.03%   |
| Realtek Semiconductor Smart Card Reader Interface               | 1        | 3.03%   |
| Giesecke & Devrient StarSign CUT                                | 1        | 3.03%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                | 1        | 3.03%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3477     | 85.56%  |
| 1     | 526      | 12.94%  |
| 2     | 46       | 1.13%   |
| 3     | 10       | 0.25%   |
| 4     | 5        | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 241      | 38.25%  |
| Net/wireless             | 165      | 26.19%  |
| Communication controller | 44       | 6.98%   |
| Unassigned class         | 41       | 6.51%   |
| Sound                    | 24       | 3.81%   |
| Multimedia controller    | 22       | 3.49%   |
| Chipcard                 | 22       | 3.49%   |
| Modem                    | 16       | 2.54%   |
| Camera                   | 16       | 2.54%   |
| Net/ethernet             | 9        | 1.43%   |
| Storage/ide              | 6        | 0.95%   |
| Bluetooth                | 6        | 0.95%   |
| Network                  | 5        | 0.79%   |
| Card reader              | 5        | 0.79%   |
| Storage/raid             | 4        | 0.63%   |
| Video                    | 1        | 0.16%   |
| Storage                  | 1        | 0.16%   |
| Firewire controller      | 1        | 0.16%   |
| Dvb card                 | 1        | 0.16%   |

