Linux in Poland - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 3055

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z170N-WIFI-CF               | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| HP            | 83E8                        | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| Unknown       | Unknown                     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [a6eabbbfef](https://linux-hardware.org/?probe=a6eabbbfef) | Aug 09, 2023 |
| ASUSTek       | M3A78-CM                    | [a5e0e043cb](https://linux-hardware.org/?probe=a5e0e043cb) | Aug 09, 2023 |
| MSI           | 970A-G43 PLUS               | [133d4b58c9](https://linux-hardware.org/?probe=133d4b58c9) | Aug 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f2547c0339](https://linux-hardware.org/?probe=f2547c0339) | Aug 08, 2023 |
| ASUSTek       | M3A78-CM                    | [93e4fee7df](https://linux-hardware.org/?probe=93e4fee7df) | Aug 08, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [25bb416eb3](https://linux-hardware.org/?probe=25bb416eb3) | Aug 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [beecacb434](https://linux-hardware.org/?probe=beecacb434) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [fb8e926bd4](https://linux-hardware.org/?probe=fb8e926bd4) | Aug 07, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Gigabyte      | 970A-UD3P                   | [dcd061dff8](https://linux-hardware.org/?probe=dcd061dff8) | Aug 05, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [420353bf79](https://linux-hardware.org/?probe=420353bf79) | Aug 04, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ECS           | H61H2-M6                    | [12990c5c80](https://linux-hardware.org/?probe=12990c5c80) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | [9be3b9bb83](https://linux-hardware.org/?probe=9be3b9bb83) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| HP            | 8054                        | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8bc1531bf6](https://linux-hardware.org/?probe=8bc1531bf6) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | [5d63b469f8](https://linux-hardware.org/?probe=5d63b469f8) | Aug 01, 2023 |
| ECS           | H61H2-M6                    | [836267e5f7](https://linux-hardware.org/?probe=836267e5f7) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Gigabyte      | B75M-D3H                    | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| ASRock        | FM2A55M-VG3+                | [ce76d8b410](https://linux-hardware.org/?probe=ce76d8b410) | Jul 31, 2023 |
| ASUSTek       | PRIME Z270-A                | [eb13fb97fb](https://linux-hardware.org/?probe=eb13fb97fb) | Jul 30, 2023 |
| ASRock        | AM1H-ITX                    | [24b2f4274d](https://linux-hardware.org/?probe=24b2f4274d) | Jul 29, 2023 |
| Gigabyte      | EP45T-UD3LR                 | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Gigabyte      | B450M DS3H V2               | [ca9b6e0320](https://linux-hardware.org/?probe=ca9b6e0320) | Jul 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f0bd5c3409](https://linux-hardware.org/?probe=f0bd5c3409) | Jul 27, 2023 |
| ASUSTek       | P5G41T-M                    | [355fadbc12](https://linux-hardware.org/?probe=355fadbc12) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | [290a0dd297](https://linux-hardware.org/?probe=290a0dd297) | Jul 25, 2023 |
| HP            | 212B                        | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [5ec24ea9ad](https://linux-hardware.org/?probe=5ec24ea9ad) | Jul 25, 2023 |
| ASUSTek       | P8H61-M LX                  | [9ffd99b082](https://linux-hardware.org/?probe=9ffd99b082) | Jul 25, 2023 |
| HP            | 198E                        | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | [816a8d70bb](https://linux-hardware.org/?probe=816a8d70bb) | Jul 24, 2023 |
| ASUSTek       | M3A78-CM                    | [a2fcdf6c36](https://linux-hardware.org/?probe=a2fcdf6c36) | Jul 24, 2023 |
| Dell          | 0VD92X A00                  | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3032h                       | [f6a4202b21](https://linux-hardware.org/?probe=f6a4202b21) | Jul 21, 2023 |
| Gigabyte      | H270-HD3-CF                 | [73a56d2df7](https://linux-hardware.org/?probe=73a56d2df7) | Jul 21, 2023 |
| Dell          | 0HD5W2 A01                  | [26c19ee81f](https://linux-hardware.org/?probe=26c19ee81f) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [c527cf56ad](https://linux-hardware.org/?probe=c527cf56ad) | Jul 17, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f4936b2064](https://linux-hardware.org/?probe=f4936b2064) | Jul 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9e829a5538](https://linux-hardware.org/?probe=9e829a5538) | Jul 14, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| Dell          | 0T7D40 A01                  | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| ASRock        | H81M                        | [042e2e3b56](https://linux-hardware.org/?probe=042e2e3b56) | Jul 11, 2023 |
| ASRock        | H81M                        | [c4b398d08c](https://linux-hardware.org/?probe=c4b398d08c) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | [ab32a0e447](https://linux-hardware.org/?probe=ab32a0e447) | Jul 11, 2023 |
| Google        | Guado                       | [d14465ad06](https://linux-hardware.org/?probe=d14465ad06) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASUSTek       | M3A78-CM                    | [38420a6afe](https://linux-hardware.org/?probe=38420a6afe) | Jul 10, 2023 |
| MSI           | X99A GAMING 9 ACK           | [4a36d070b4](https://linux-hardware.org/?probe=4a36d070b4) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| HP            | 1998                        | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| HP            | 1998                        | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [14c6f3f286](https://linux-hardware.org/?probe=14c6f3f286) | Jul 10, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [6a55de667a](https://linux-hardware.org/?probe=6a55de667a) | Jul 09, 2023 |
| Dell          | 0KC9NP A01                  | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9ecae424ad](https://linux-hardware.org/?probe=9ecae424ad) | Jul 07, 2023 |
| Gigabyte      | B85M-HD3                    | [43034103ef](https://linux-hardware.org/?probe=43034103ef) | Jul 06, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Google        | Guado                       | [8bd38f802a](https://linux-hardware.org/?probe=8bd38f802a) | Jul 06, 2023 |
| ASRock        | Z370 Killer SLI             | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | [685f105356](https://linux-hardware.org/?probe=685f105356) | Jul 05, 2023 |
| HP            | 339A                        | [8d051ead1c](https://linux-hardware.org/?probe=8d051ead1c) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| ASRock        | Z170 Extreme4               | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| ASRock        | A320M-HDV R3.0              | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| Gigabyte      | B450M GAMING                | [22a13c2e16](https://linux-hardware.org/?probe=22a13c2e16) | Jul 03, 2023 |
| ASUSTek       | M3A78-CM                    | [67281face4](https://linux-hardware.org/?probe=67281face4) | Jul 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f928781025](https://linux-hardware.org/?probe=f928781025) | Jul 03, 2023 |
| Acer          | FX58M                       | [44e563ac2a](https://linux-hardware.org/?probe=44e563ac2a) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| Acer          | FX58M                       | [69f3a5d4fb](https://linux-hardware.org/?probe=69f3a5d4fb) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| Gigabyte      | Z77X-UD5H                   | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| Gigabyte      | GA-970A-UD3                 | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | 21B4 A01                    | [e277fd2772](https://linux-hardware.org/?probe=e277fd2772) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| Intel         | H81                         | [65ad18a4bd](https://linux-hardware.org/?probe=65ad18a4bd) | Jun 24, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [a036f44a4c](https://linux-hardware.org/?probe=a036f44a4c) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [d4d7534ac3](https://linux-hardware.org/?probe=d4d7534ac3) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Gigabyte      | H510M S2H V2                | [d7c44291c1](https://linux-hardware.org/?probe=d7c44291c1) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| Gigabyte      | H510M S2H V2                | [f2d80b2558](https://linux-hardware.org/?probe=f2d80b2558) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| ASRock        | Z87 Extreme4                | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| MSI           | B85-G43 GAMING              | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| ASRock        | H61M-VG3                    | [858be00df4](https://linux-hardware.org/?probe=858be00df4) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| MSI           | B450 TOMAHAWK               | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [dbe7676807](https://linux-hardware.org/?probe=dbe7676807) | Jun 15, 2023 |
| ASUSTek       | P5G41C-M LX                 | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| MSI           | B450M-A PRO MAX             | [de08f65c4d](https://linux-hardware.org/?probe=de08f65c4d) | Jun 11, 2023 |
| HP            | 3397                        | [9f71c4173c](https://linux-hardware.org/?probe=9f71c4173c) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| Gigabyte      | Z97M-DS3H                   | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| MSI           | Z87-G43                     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Gigabyte      | B250-FinTech-CF             | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| HP            | 21B4 A01                    | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| HP            | 845A                        | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| Dell          | 02N3WF A01                  | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Dell          | 040DDP A01                  | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| ASRock        | G41M-VS3                    | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| Gateway       | DT55                        | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| ASRock        | H81M-VG4                    | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| ASUSTek       | A8N-E                       | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Acer          | WG43M                       | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| ASRock        | AB350 Pro4                  | [53db1863ab](https://linux-hardware.org/?probe=53db1863ab) | May 25, 2023 |
| ASUSTek       | M3A78-CM                    | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| Gigabyte      | B250-FinTech-CF             | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| ASUSTek       | M3A78-CM                    | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| MSI           | B360M PRO-VDH               | [93a41eca5e](https://linux-hardware.org/?probe=93a41eca5e) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [04ea462ce6](https://linux-hardware.org/?probe=04ea462ce6) | May 21, 2023 |
| ASUSTek       | B85M-G                      | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASUSTek       | PRIME Z790-P                | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | P5G41T-M                    | [89d938fcef](https://linux-hardware.org/?probe=89d938fcef) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Pegatron      | VIOLET                      | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
| Foxconn       | P35A01                      | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| HP            | 339A                        | [35fdefb4eb](https://linux-hardware.org/?probe=35fdefb4eb) | May 15, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Inventec      | D CLASS A02                 | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Dell          | 0GWHMW A00                  | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Gigabyte      | Z97M-DS3H                   | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| HP            | 3047h                       | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| ASUSTek       | B85-PLUS                    | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| MSI           | B85-G43                     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| ASUSTek       | M3A78-CM                    | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| ASUSTek       | PRIME B550M-K               | [c0ade7c98e](https://linux-hardware.org/?probe=c0ade7c98e) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [50fba20da2](https://linux-hardware.org/?probe=50fba20da2) | May 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8774a893d6](https://linux-hardware.org/?probe=8774a893d6) | May 05, 2023 |
| Gigabyte      | Z590 UD AC                  | [b8f920797f](https://linux-hardware.org/?probe=b8f920797f) | May 05, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| ASUSTek       | M3A78-CM                    | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| MSI           | B450M MORTAR MAX            | [91f2551511](https://linux-hardware.org/?probe=91f2551511) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| HP            | 1589                        | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| HP            | 1589                        | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| Gigabyte      | H110M-DS2-CF                | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | [15c40bae27](https://linux-hardware.org/?probe=15c40bae27) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2fcc250a35](https://linux-hardware.org/?probe=2fcc250a35) | May 01, 2023 |
| MSI           | B450M PRO-M2                | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| ASRock        | Z370 Gaming K6              | [a5ff738639](https://linux-hardware.org/?probe=a5ff738639) | Apr 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [ee996917df](https://linux-hardware.org/?probe=ee996917df) | Apr 29, 2023 |
| ASRock        | Z170 Extreme4               | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | P5K/EPU                     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [f1f2ad2731](https://linux-hardware.org/?probe=f1f2ad2731) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| Dell          | 03NVJ6 A02                  | [74a0632f6e](https://linux-hardware.org/?probe=74a0632f6e) | Apr 25, 2023 |
| ASUSTek       | M3A78-CM                    | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [652e029529](https://linux-hardware.org/?probe=652e029529) | Apr 23, 2023 |
| MSI           | P55-GD65                    | [90cc53b6dd](https://linux-hardware.org/?probe=90cc53b6dd) | Apr 22, 2023 |
| MSI           | B450-A PRO MAX              | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Unknown       | Unknown                     | [be207ea29f](https://linux-hardware.org/?probe=be207ea29f) | Apr 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [904089ce14](https://linux-hardware.org/?probe=904089ce14) | Apr 20, 2023 |
| Gigabyte      | G31M-ES2L                   | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [3c77a2b081](https://linux-hardware.org/?probe=3c77a2b081) | Apr 14, 2023 |
| MSI           | B85-G43                     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Dell          | 0GXM1W A00                  | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASUSTek       | A68HM-K                     | [5586a15d29](https://linux-hardware.org/?probe=5586a15d29) | Apr 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Acer          | WG43M                       | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | [b85f3476ed](https://linux-hardware.org/?probe=b85f3476ed) | Apr 11, 2023 |
| HP            | 3032h                       | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| MSI           | MS-B0A21                    | [93db7f66f1](https://linux-hardware.org/?probe=93db7f66f1) | Apr 08, 2023 |
| ASUSTek       | M3A78-CM                    | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| ASRock        | B75 Pro3-M                  | [81b76a458e](https://linux-hardware.org/?probe=81b76a458e) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| Dell          | 0Y2K8N A01                  | [379f9d7af7](https://linux-hardware.org/?probe=379f9d7af7) | Apr 04, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6e8ca2befa](https://linux-hardware.org/?probe=6e8ca2befa) | Apr 04, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [64fa944dfd](https://linux-hardware.org/?probe=64fa944dfd) | Apr 03, 2023 |
| MSI           | PH67A-C43                   | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | [c98048fb64](https://linux-hardware.org/?probe=c98048fb64) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [b7848305ec](https://linux-hardware.org/?probe=b7848305ec) | Apr 01, 2023 |
| Intel         | DG41RQ AAE54511-203         | [383835a445](https://linux-hardware.org/?probe=383835a445) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [dff9959cd7](https://linux-hardware.org/?probe=dff9959cd7) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| Acer          | WG43M                       | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| ASUSTek       | PRIME B360M-C               | [e7b163ea80](https://linux-hardware.org/?probe=e7b163ea80) | Mar 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| ASRock        | Z77 Extreme6                | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| ASUSTek       | M3A78-CM                    | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| HP            | 1998                        | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [1c37ecb6c7](https://linux-hardware.org/?probe=1c37ecb6c7) | Mar 26, 2023 |
| ASRock        | AM1H-ITX                    | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| Acer          | WG43M                       | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [4fcf740ee9](https://linux-hardware.org/?probe=4fcf740ee9) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [caa720b95b](https://linux-hardware.org/?probe=caa720b95b) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| HP            | 304Ah                       | [43990fede2](https://linux-hardware.org/?probe=43990fede2) | Mar 24, 2023 |
| ASRock        | B550M Pro4                  | [d18034c36c](https://linux-hardware.org/?probe=d18034c36c) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Gigabyte      | A520I AC                    | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a03658793c](https://linux-hardware.org/?probe=a03658793c) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [6df656c198](https://linux-hardware.org/?probe=6df656c198) | Mar 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [1bad88b80e](https://linux-hardware.org/?probe=1bad88b80e) | Mar 20, 2023 |
| ASUSTek       | M3A78-CM                    | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Intel         | DG41RQ AAE54511-203         | [703ea3d03c](https://linux-hardware.org/?probe=703ea3d03c) | Mar 18, 2023 |
| Intel         | DG41RQ AAE54511-203         | [a5775c7491](https://linux-hardware.org/?probe=a5775c7491) | Mar 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | [2a17e297a2](https://linux-hardware.org/?probe=2a17e297a2) | Mar 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | [96742a0cb2](https://linux-hardware.org/?probe=96742a0cb2) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| ASRock        | AB350 Pro4                  | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | 03NVJ6 A02                  | [b5281b4ba4](https://linux-hardware.org/?probe=b5281b4ba4) | Mar 15, 2023 |
| ASUSTek       | M3A78-CM                    | [8c2507428d](https://linux-hardware.org/?probe=8c2507428d) | Mar 15, 2023 |
| MSI           | B85-G43                     | [d8334d09fa](https://linux-hardware.org/?probe=d8334d09fa) | Mar 15, 2023 |
| Dell          | 0773VG A00                  | [320dab99e7](https://linux-hardware.org/?probe=320dab99e7) | Mar 15, 2023 |
| Dell          | 0C96W1 A03                  | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| MSI           | B85-G43                     | [e270b5804a](https://linux-hardware.org/?probe=e270b5804a) | Mar 13, 2023 |
| Dell          | 051FJ8 A02                  | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [73d5ba11c5](https://linux-hardware.org/?probe=73d5ba11c5) | Mar 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [540bfa93eb](https://linux-hardware.org/?probe=540bfa93eb) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| MSI           | A68HM-E33 V2                | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [afe81d4bfa](https://linux-hardware.org/?probe=afe81d4bfa) | Mar 12, 2023 |
| HP            | 213D A01                    | [8c6054a4f7](https://linux-hardware.org/?probe=8c6054a4f7) | Mar 12, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| HP            | 0AA0h                       | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| ASRock        | AM1H-ITX                    | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| ASUSTek       | A68HM-K                     | [12fa2455f7](https://linux-hardware.org/?probe=12fa2455f7) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Lenovo        | MAHOBAY                     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| Dell          | 03NVJ6 A02                  | [34696138fe](https://linux-hardware.org/?probe=34696138fe) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [43a939870d](https://linux-hardware.org/?probe=43a939870d) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f64ba0ea72](https://linux-hardware.org/?probe=f64ba0ea72) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| Dell          | 0T1D10 A01                  | [ef67915ff3](https://linux-hardware.org/?probe=ef67915ff3) | Mar 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [59cb6854e5](https://linux-hardware.org/?probe=59cb6854e5) | Mar 07, 2023 |
| ASUSTek       | A88XM-E                     | [b809f137cd](https://linux-hardware.org/?probe=b809f137cd) | Mar 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0cda9f83b1](https://linux-hardware.org/?probe=0cda9f83b1) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Biostar       | TA780G M2+                  | [f5ddb4d21a](https://linux-hardware.org/?probe=f5ddb4d21a) | Mar 05, 2023 |
| MSI           | B550M PRO                   | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| HP            | 18E5                        | [969462a8a0](https://linux-hardware.org/?probe=969462a8a0) | Mar 05, 2023 |
| Dell          | 03NVJ6 A02                  | [80e769b994](https://linux-hardware.org/?probe=80e769b994) | Mar 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92b81bb3a1](https://linux-hardware.org/?probe=92b81bb3a1) | Mar 05, 2023 |
| ASUSTek       | A88XM-E                     | [ea145a8349](https://linux-hardware.org/?probe=ea145a8349) | Mar 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [d9a9f6b904](https://linux-hardware.org/?probe=d9a9f6b904) | Mar 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [cf87d901a9](https://linux-hardware.org/?probe=cf87d901a9) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [5eb43b511f](https://linux-hardware.org/?probe=5eb43b511f) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [8db9ca3a4b](https://linux-hardware.org/?probe=8db9ca3a4b) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [789ca3b7bd](https://linux-hardware.org/?probe=789ca3b7bd) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [241283977d](https://linux-hardware.org/?probe=241283977d) | Mar 04, 2023 |
| ASRock        | Z87 Extreme4                | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Dell          | 03NVJ6 A01                  | [0e8d1a9e75](https://linux-hardware.org/?probe=0e8d1a9e75) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | [a40e18910c](https://linux-hardware.org/?probe=a40e18910c) | Mar 03, 2023 |
| ASUSTek       | Maximus VII RANGER          | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [ada9b78c86](https://linux-hardware.org/?probe=ada9b78c86) | Mar 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [52522a762d](https://linux-hardware.org/?probe=52522a762d) | Feb 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | [07bb534dc9](https://linux-hardware.org/?probe=07bb534dc9) | Feb 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [409bb06e5e](https://linux-hardware.org/?probe=409bb06e5e) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [589b06afc1](https://linux-hardware.org/?probe=589b06afc1) | Feb 26, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [df54545112](https://linux-hardware.org/?probe=df54545112) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [782598981d](https://linux-hardware.org/?probe=782598981d) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [6a75456290](https://linux-hardware.org/?probe=6a75456290) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [73caef7b95](https://linux-hardware.org/?probe=73caef7b95) | Feb 25, 2023 |
| Gigabyte      | G31M-S2L                    | [563101d2b2](https://linux-hardware.org/?probe=563101d2b2) | Feb 25, 2023 |
| ASRock        | AM1H-ITX                    | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| MSI           | B350M MORTAR                | [6a7ac3b38b](https://linux-hardware.org/?probe=6a7ac3b38b) | Feb 24, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [b2681528bd](https://linux-hardware.org/?probe=b2681528bd) | Feb 24, 2023 |
| ASUSTek       | B150M-A D3                  | [01caadaee0](https://linux-hardware.org/?probe=01caadaee0) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B85M-HD3 R4                 | [db83755f3f](https://linux-hardware.org/?probe=db83755f3f) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| Gigabyte      | Z97-HD3                     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [821d952d15](https://linux-hardware.org/?probe=821d952d15) | Feb 23, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [39e6d492c4](https://linux-hardware.org/?probe=39e6d492c4) | Feb 22, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [40bc5397ea](https://linux-hardware.org/?probe=40bc5397ea) | Feb 22, 2023 |
| ASRock        | Z690 Extreme                | [16e67a28e4](https://linux-hardware.org/?probe=16e67a28e4) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [cb79c0ad47](https://linux-hardware.org/?probe=cb79c0ad47) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| ASRock        | A520M-HVS                   | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| ASUSTek       | M3A78-CM                    | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| Gigabyte      | B75M-D2V                    | [fe04dfeaac](https://linux-hardware.org/?probe=fe04dfeaac) | Feb 19, 2023 |
| Dell          | 0PU052                      | [a460806b91](https://linux-hardware.org/?probe=a460806b91) | Feb 18, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [28965259ad](https://linux-hardware.org/?probe=28965259ad) | Feb 18, 2023 |
| Dell          | 03NVJ6 A02                  | [5201547dce](https://linux-hardware.org/?probe=5201547dce) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | [a77d2c8a54](https://linux-hardware.org/?probe=a77d2c8a54) | Feb 17, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [8efdbecd75](https://linux-hardware.org/?probe=8efdbecd75) | Feb 17, 2023 |
| ASRock        | J3355M                      | [9118f960dd](https://linux-hardware.org/?probe=9118f960dd) | Feb 16, 2023 |
| Gigabyte      | EP35-DS4                    | [00d960f926](https://linux-hardware.org/?probe=00d960f926) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| MSI           | MS-7235                     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | [ae4f47209a](https://linux-hardware.org/?probe=ae4f47209a) | Feb 15, 2023 |
| Gigabyte      | H410M H V3                  | [59f88fb4d0](https://linux-hardware.org/?probe=59f88fb4d0) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | [f1c6e21bfb](https://linux-hardware.org/?probe=f1c6e21bfb) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| ASUSTek       | M3A78-CM                    | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Gigabyte      | H55M-USB3                   | [08b959d9ec](https://linux-hardware.org/?probe=08b959d9ec) | Feb 14, 2023 |
| ASUSTek       | M3A78-CM                    | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| HP            | 3397                        | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| HP            | 3397                        | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| HP            | 3397                        | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| Dell          | 04YJ19 A00                  | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| ASUSTek       | PRIME B450M-A               | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [ddaad5aa0d](https://linux-hardware.org/?probe=ddaad5aa0d) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Intel         | DG31PR AAD97573-301         | [665f8e7d81](https://linux-hardware.org/?probe=665f8e7d81) | Feb 09, 2023 |
| ASUSTek       | M3A78-CM                    | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [2b4bc22652](https://linux-hardware.org/?probe=2b4bc22652) | Feb 08, 2023 |
| ASRock        | X470 Gaming K4              | [086ea7a0e6](https://linux-hardware.org/?probe=086ea7a0e6) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| Dell          | 0DR845                      | [537252420b](https://linux-hardware.org/?probe=537252420b) | Feb 07, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | DG31PR AAD97573-301         | [2080f0edf4](https://linux-hardware.org/?probe=2080f0edf4) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Huanan        | X99-T8D V1.2                | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| MSI           | H410M-A PRO                 | [6ac747c27e](https://linux-hardware.org/?probe=6ac747c27e) | Feb 05, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| HP            | 8054                        | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [854b52f85c](https://linux-hardware.org/?probe=854b52f85c) | Feb 05, 2023 |
| Foxconn       | 2ABF                        | [54a305f83e](https://linux-hardware.org/?probe=54a305f83e) | Feb 03, 2023 |
| ASRock        | Z370 Gaming K6              | [203d5736d7](https://linux-hardware.org/?probe=203d5736d7) | Feb 03, 2023 |
| HP            | 212B                        | [f27b5c4aa0](https://linux-hardware.org/?probe=f27b5c4aa0) | Feb 03, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [a4a3ea0e4e](https://linux-hardware.org/?probe=a4a3ea0e4e) | Feb 02, 2023 |
| MSI           | X99S SLI PLUS               | [6b007d74de](https://linux-hardware.org/?probe=6b007d74de) | Feb 02, 2023 |
| Gigabyte      | B365M DS3H                  | [f04d195965](https://linux-hardware.org/?probe=f04d195965) | Feb 02, 2023 |
| ASUSTek       | P5QPL-AM                    | [c8ee9be68c](https://linux-hardware.org/?probe=c8ee9be68c) | Feb 02, 2023 |
| ASUSTek       | B85M-G                      | [de152b340c](https://linux-hardware.org/?probe=de152b340c) | Feb 01, 2023 |
| Gigabyte      | B365M DS3H                  | [d515d5d9f7](https://linux-hardware.org/?probe=d515d5d9f7) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| ASUSTek       | Maximus VII GENE            | [c936c07925](https://linux-hardware.org/?probe=c936c07925) | Jan 31, 2023 |
| Gigabyte      | Z97M-DS3H                   | [360dc83e04](https://linux-hardware.org/?probe=360dc83e04) | Jan 31, 2023 |
| HP            | 8054                        | [f2367fdcda](https://linux-hardware.org/?probe=f2367fdcda) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| Dell          | 0HY9JP A00                  | [f4aefcd670](https://linux-hardware.org/?probe=f4aefcd670) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| HP            | 8054                        | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| HP            | 3048h                       | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [9fcf89ea7c](https://linux-hardware.org/?probe=9fcf89ea7c) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASRock        | FM2A55M-VG3+                | [c5da4a997d](https://linux-hardware.org/?probe=c5da4a997d) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [076a3479fa](https://linux-hardware.org/?probe=076a3479fa) | Jan 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d251029940](https://linux-hardware.org/?probe=d251029940) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6c55213012](https://linux-hardware.org/?probe=6c55213012) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6b5c46a680](https://linux-hardware.org/?probe=6b5c46a680) | Jan 19, 2023 |
| Huanan        | X99-TF V2.0                 | [3fa0103359](https://linux-hardware.org/?probe=3fa0103359) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| Dell          | 0Y3R3K A00                  | [f2164a9c60](https://linux-hardware.org/?probe=f2164a9c60) | Jan 18, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| ASUSTek       | P5K/EPU                     | [c159b4d65b](https://linux-hardware.org/?probe=c159b4d65b) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B560M DS3H                  | [be77d8e20d](https://linux-hardware.org/?probe=be77d8e20d) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| Gigabyte      | Z97M-D3H                    | [305ff29dad](https://linux-hardware.org/?probe=305ff29dad) | Jan 14, 2023 |
| ASRock        | H110M-HDV R3.0              | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [6cc45bde0b](https://linux-hardware.org/?probe=6cc45bde0b) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek       | M3A78-CM                    | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| Gigabyte      | Z97M-DS3H                   | [3dcb242fd6](https://linux-hardware.org/?probe=3dcb242fd6) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [366e5b92d7](https://linux-hardware.org/?probe=366e5b92d7) | Jan 11, 2023 |
| Gigabyte      | B365M DS3H                  | [78153a929d](https://linux-hardware.org/?probe=78153a929d) | Jan 11, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [f3fe7611d3](https://linux-hardware.org/?probe=f3fe7611d3) | Jan 11, 2023 |
| ASUSTek       | P5K/EPU                     | [c6ffd59fb2](https://linux-hardware.org/?probe=c6ffd59fb2) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [eefd133e1f](https://linux-hardware.org/?probe=eefd133e1f) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| Dell          | 0MGK50 A02                  | [045695f1d5](https://linux-hardware.org/?probe=045695f1d5) | Jan 09, 2023 |
| Dell          | 088DT1 A00                  | [f7632cc6ba](https://linux-hardware.org/?probe=f7632cc6ba) | Jan 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| Lenovo        | SKYBAY NOK                  | [9bbe57d371](https://linux-hardware.org/?probe=9bbe57d371) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | [0f51a2d7d5](https://linux-hardware.org/?probe=0f51a2d7d5) | Jan 07, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | [531eaa88b5](https://linux-hardware.org/?probe=531eaa88b5) | Jan 07, 2023 |
| Dell          | 0J584C A00                  | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| MSI           | Z590 PRO WIFI               | [98af54429b](https://linux-hardware.org/?probe=98af54429b) | Jan 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [fd20c9e982](https://linux-hardware.org/?probe=fd20c9e982) | Jan 07, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| MSI           | A320M-A PRO                 | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| Dell          | 0Y3R3K A00                  | [8337b0691c](https://linux-hardware.org/?probe=8337b0691c) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [96150fc8a5](https://linux-hardware.org/?probe=96150fc8a5) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | [bd3d76fa53](https://linux-hardware.org/?probe=bd3d76fa53) | Jan 03, 2023 |
| HP            | 304Bh                       | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| MSI           | B250M PRO-VDH               | [0a4b320a9e](https://linux-hardware.org/?probe=0a4b320a9e) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | B450M Pro4                  | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| Gigabyte      | H61M-D2H                    | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9b264f00f0](https://linux-hardware.org/?probe=9b264f00f0) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | [fdb09844e9](https://linux-hardware.org/?probe=fdb09844e9) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | [9ff3461c31](https://linux-hardware.org/?probe=9ff3461c31) | Dec 29, 2022 |
| Gigabyte      | H270-HD3-CF                 | [031a62faa8](https://linux-hardware.org/?probe=031a62faa8) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | Z97M-DS3H                   | [02f55ff55b](https://linux-hardware.org/?probe=02f55ff55b) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | [05163a2fb9](https://linux-hardware.org/?probe=05163a2fb9) | Dec 26, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | [0836c3b800](https://linux-hardware.org/?probe=0836c3b800) | Dec 23, 2022 |
| MSI           | Z270 TOMAHAWK               | [b721ac26e2](https://linux-hardware.org/?probe=b721ac26e2) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9ada5592f6](https://linux-hardware.org/?probe=9ada5592f6) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| HP            | ProLiant ML350 G6           | [58113862ee](https://linux-hardware.org/?probe=58113862ee) | Dec 18, 2022 |
| Foxconn       | A76GMV                      | [722a9911f8](https://linux-hardware.org/?probe=722a9911f8) | Dec 18, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| POSIFLEX      | KK-3703 D0                  | [8ce9910b00](https://linux-hardware.org/?probe=8ce9910b00) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Dell          | 05XGC8 A01                  | [f0e99676be](https://linux-hardware.org/?probe=f0e99676be) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [a607679697](https://linux-hardware.org/?probe=a607679697) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [9bd8fecf82](https://linux-hardware.org/?probe=9bd8fecf82) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| ASUSTek       | P5K Deluxe                  | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [ffb030fbbf](https://linux-hardware.org/?probe=ffb030fbbf) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [fe9424a1f0](https://linux-hardware.org/?probe=fe9424a1f0) | Dec 09, 2022 |
| Dell          | 01TKCC A01                  | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e64c5d7bdc](https://linux-hardware.org/?probe=e64c5d7bdc) | Dec 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | [798cf690c5](https://linux-hardware.org/?probe=798cf690c5) | Dec 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [091b8a3a8a](https://linux-hardware.org/?probe=091b8a3a8a) | Dec 05, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [aadffecf5b](https://linux-hardware.org/?probe=aadffecf5b) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| Lenovo        | SKYBAY NOK                  | [10315500be](https://linux-hardware.org/?probe=10315500be) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | [f8dacfeca3](https://linux-hardware.org/?probe=f8dacfeca3) | Dec 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [6578471259](https://linux-hardware.org/?probe=6578471259) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [9990900d63](https://linux-hardware.org/?probe=9990900d63) | Dec 03, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [8a25bf4545](https://linux-hardware.org/?probe=8a25bf4545) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [dd124e3579](https://linux-hardware.org/?probe=dd124e3579) | Nov 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | [a5b34b67f2](https://linux-hardware.org/?probe=a5b34b67f2) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | [f0dfa48048](https://linux-hardware.org/?probe=f0dfa48048) | Nov 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| ASUSTek       | M3A78-CM                    | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Gigabyte      | Z97M-DS3H                   | [a17a108297](https://linux-hardware.org/?probe=a17a108297) | Nov 25, 2022 |
| MSI           | B350 GAMING PLUS            | [2b7bb89689](https://linux-hardware.org/?probe=2b7bb89689) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| HP            | 213D A01                    | [b0c45fb200](https://linux-hardware.org/?probe=b0c45fb200) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Unknown       | HX90                        | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| ASRock        | H410M-HVS R2.0              | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| MSI           | PRO H610M-B DDR4            | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Lenovo        | SKYBAY NOK                  | [24d16fa5df](https://linux-hardware.org/?probe=24d16fa5df) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0PU052                      | [b54afc7e1a](https://linux-hardware.org/?probe=b54afc7e1a) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| Lenovo        | MAHOBAY                     | [d74e4882d8](https://linux-hardware.org/?probe=d74e4882d8) | Nov 21, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| Gigabyte      | EP45-UD3LR                  | [75a8f2a500](https://linux-hardware.org/?probe=75a8f2a500) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [08372f6535](https://linux-hardware.org/?probe=08372f6535) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bb2db87e9a](https://linux-hardware.org/?probe=bb2db87e9a) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| Dell          | 0PU052                      | [802c39b94f](https://linux-hardware.org/?probe=802c39b94f) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [27d4e1c496](https://linux-hardware.org/?probe=27d4e1c496) | Nov 13, 2022 |
| Gigabyte      | Z97M-DS3H                   | [220c131e59](https://linux-hardware.org/?probe=220c131e59) | Nov 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| MSI           | B450M-A PRO MAX             | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| Gigabyte      | B550M DS3H                  | [6531f0596d](https://linux-hardware.org/?probe=6531f0596d) | Nov 10, 2022 |
| ASUSTek       | P8H61                       | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASUSTek       | M3A78-CM                    | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| Gigabyte      | G41MT-S2                    | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| Intel         | H55                         | [0481a6ff8e](https://linux-hardware.org/?probe=0481a6ff8e) | Nov 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| Gigabyte      | H81M-DS2                    | [5deb773641](https://linux-hardware.org/?probe=5deb773641) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Gigabyte      | B560M D3H                   | [e8364f4018](https://linux-hardware.org/?probe=e8364f4018) | Nov 04, 2022 |
| MSI           | Z97-G43                     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [a2af2980ad](https://linux-hardware.org/?probe=a2af2980ad) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [245ec71478](https://linux-hardware.org/?probe=245ec71478) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [738569f811](https://linux-hardware.org/?probe=738569f811) | Oct 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a8b08a47aa](https://linux-hardware.org/?probe=a8b08a47aa) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9914e4d771](https://linux-hardware.org/?probe=9914e4d771) | Oct 28, 2022 |
| Gigabyte      | P35-DS3L                    | [2f5cb804c0](https://linux-hardware.org/?probe=2f5cb804c0) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e98085fc5](https://linux-hardware.org/?probe=6e98085fc5) | Oct 25, 2022 |
| Dell          | 0HY9JP A00                  | [ecbfb1ca5c](https://linux-hardware.org/?probe=ecbfb1ca5c) | Oct 25, 2022 |
| Dell          | 040DDP A01                  | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7f736b0a22](https://linux-hardware.org/?probe=7f736b0a22) | Oct 19, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [fc51a7c9dc](https://linux-hardware.org/?probe=fc51a7c9dc) | Oct 18, 2022 |
| Dell          | 0XHGV1 A01                  | [fcac80ff4a](https://linux-hardware.org/?probe=fcac80ff4a) | Oct 18, 2022 |
| ASUSTek       | M3A78-CM                    | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Gigabyte      | B460M DS3H V2               | [4fe1c6d3e8](https://linux-hardware.org/?probe=4fe1c6d3e8) | Oct 17, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [2d7d5c19c0](https://linux-hardware.org/?probe=2d7d5c19c0) | Oct 17, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [7706fb5578](https://linux-hardware.org/?probe=7706fb5578) | Oct 12, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2f346a2afb](https://linux-hardware.org/?probe=2f346a2afb) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [9e82633709](https://linux-hardware.org/?probe=9e82633709) | Oct 10, 2022 |
| ASUSTek       | M3A78-CM                    | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cde031e816](https://linux-hardware.org/?probe=cde031e816) | Oct 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| ASUSTek       | P5Q Premium                 | [8c0a201199](https://linux-hardware.org/?probe=8c0a201199) | Oct 09, 2022 |
| Dell          | 0GM819                      | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | [be016db304](https://linux-hardware.org/?probe=be016db304) | Oct 08, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2423d31aeb](https://linux-hardware.org/?probe=2423d31aeb) | Oct 05, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [1348c5b5eb](https://linux-hardware.org/?probe=1348c5b5eb) | Oct 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [563ae9b3df](https://linux-hardware.org/?probe=563ae9b3df) | Oct 03, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [339dcddca7](https://linux-hardware.org/?probe=339dcddca7) | Oct 03, 2022 |
| ASUSTek       | M3A78-CM                    | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| ASUSTek       | Maximus VII HERO            | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [bc6bcfe3f2](https://linux-hardware.org/?probe=bc6bcfe3f2) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [2d1e938e68](https://linux-hardware.org/?probe=2d1e938e68) | Oct 01, 2022 |
| Gigabyte      | Z97M-DS3H                   | [fcf7e031e3](https://linux-hardware.org/?probe=fcf7e031e3) | Sep 30, 2022 |
| Dell          | 0KJCC5 A00                  | [f9582eb0a8](https://linux-hardware.org/?probe=f9582eb0a8) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | [1bdf72d415](https://linux-hardware.org/?probe=1bdf72d415) | Sep 27, 2022 |
| Intel         | DH61WW AAG23116-204         | [f35f96af50](https://linux-hardware.org/?probe=f35f96af50) | Sep 27, 2022 |
| Dell          | 0DC48C A02                  | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| HP            | 805D                        | [b023737f63](https://linux-hardware.org/?probe=b023737f63) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Gigabyte      | B85M-D3H                    | [8de01689b6](https://linux-hardware.org/?probe=8de01689b6) | Sep 24, 2022 |
| HP            | 3032h                       | [efb6671159](https://linux-hardware.org/?probe=efb6671159) | Sep 23, 2022 |
| MSI           | 760GM-P34                   | [af750add66](https://linux-hardware.org/?probe=af750add66) | Sep 22, 2022 |
| MSI           | H81M-P33                    | [05d5a24774](https://linux-hardware.org/?probe=05d5a24774) | Sep 22, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| Dell          | 0D883F A06                  | [01c50a7a4c](https://linux-hardware.org/?probe=01c50a7a4c) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [1f2bd2202c](https://linux-hardware.org/?probe=1f2bd2202c) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [b3cb8fc82e](https://linux-hardware.org/?probe=b3cb8fc82e) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| AMI           | Cherry Trail CR             | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| ASUSTek       | M3A78-CM                    | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Gigabyte      | G41MT-ES2L                  | [74ee0e38a3](https://linux-hardware.org/?probe=74ee0e38a3) | Sep 11, 2022 |
| Dell          | 01TKCC A01                  | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| HP            | 1497                        | [3cf8f5d97a](https://linux-hardware.org/?probe=3cf8f5d97a) | Sep 07, 2022 |
| Dell          | 0DR845                      | [f945fc3f5e](https://linux-hardware.org/?probe=f945fc3f5e) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| MSI           | MEG X570 ACE                | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | B85M-E43 DASH               | [f52a53f4a7](https://linux-hardware.org/?probe=f52a53f4a7) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| ASUSTek       | PRIME X470-PRO              | [87a6f9162a](https://linux-hardware.org/?probe=87a6f9162a) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS            | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [5d85db2c66](https://linux-hardware.org/?probe=5d85db2c66) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | P5K/EPU                     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock        | N68C-S UCC                  | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Unknown       | Unknown                     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| ASRock        | X370 Gaming X               | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [72c01f3cf1](https://linux-hardware.org/?probe=72c01f3cf1) | Aug 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3b245a809d](https://linux-hardware.org/?probe=3b245a809d) | Aug 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [dcb225651d](https://linux-hardware.org/?probe=dcb225651d) | Aug 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| ASUSTek       | G15DK                       | [231c2674a6](https://linux-hardware.org/?probe=231c2674a6) | Aug 28, 2022 |
| ASUSTek       | P8B WS                      | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| HP            | 8054                        | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| ASRock        | N68C-GS4 FX                 | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | P5B                         | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| ASUSTek       | P7P55D-E                    | [7c83845247](https://linux-hardware.org/?probe=7c83845247) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [d39161dc13](https://linux-hardware.org/?probe=d39161dc13) | Aug 19, 2022 |
| ASUSTek       | A88XM-E                     | [04d716a25d](https://linux-hardware.org/?probe=04d716a25d) | Aug 19, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3d5404aaff](https://linux-hardware.org/?probe=3d5404aaff) | Aug 18, 2022 |
| ASRock        | H81M                        | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| ASUSTek       | M3A78-CM                    | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| ASUSTek       | P5K-E                       | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Gigabyte      | B460M DS3H V2               | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| Gigabyte      | H270-Gaming 3               | [434ba505a3](https://linux-hardware.org/?probe=434ba505a3) | Aug 12, 2022 |
| MSI           | B365M PRO-VDH               | [213778bd3c](https://linux-hardware.org/?probe=213778bd3c) | Aug 10, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [f3dcea80d5](https://linux-hardware.org/?probe=f3dcea80d5) | Aug 10, 2022 |
| ASUSTek       | A88XM-E                     | [f496954b96](https://linux-hardware.org/?probe=f496954b96) | Aug 08, 2022 |
| ASUSTek       | A88XM-E                     | [84dcf54ab8](https://linux-hardware.org/?probe=84dcf54ab8) | Aug 08, 2022 |
| Unknown       | Unknown                     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| ASUSTek       | M3A78-CM                    | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| MSI           | A320M PRO-M2                | [43f6f3c828](https://linux-hardware.org/?probe=43f6f3c828) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b18ee3a2ff](https://linux-hardware.org/?probe=b18ee3a2ff) | Aug 06, 2022 |
| Gigabyte      | B550 GAMING X               | [b158696344](https://linux-hardware.org/?probe=b158696344) | Aug 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | [70d84ddbc1](https://linux-hardware.org/?probe=70d84ddbc1) | Aug 05, 2022 |
| Gigabyte      | B550M DS3H                  | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| ASUSTek       | M3A78-CM                    | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | [13eff519f6](https://linux-hardware.org/?probe=13eff519f6) | Jul 30, 2022 |
| HP            | 21B4 A01                    | [474779f0b9](https://linux-hardware.org/?probe=474779f0b9) | Jul 30, 2022 |
| MSI           | X470 GAMING PLUS            | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | [cb1458b51e](https://linux-hardware.org/?probe=cb1458b51e) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | [7940deabb7](https://linux-hardware.org/?probe=7940deabb7) | Jul 28, 2022 |
| HP            | ProLiant ML330 G6           | [711602c0ac](https://linux-hardware.org/?probe=711602c0ac) | Jul 28, 2022 |
| ASUSTek       | B85M-G                      | [48e8d6fba9](https://linux-hardware.org/?probe=48e8d6fba9) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| MSI           | B250 PC MATE                | [dda7519d05](https://linux-hardware.org/?probe=dda7519d05) | Jul 27, 2022 |
| Dell          | 0G261D A00                  | [f7cb8645af](https://linux-hardware.org/?probe=f7cb8645af) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| ASUSTek       | M3A78-CM                    | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| Gigabyte      | Z97M-DS3H                   | [542296a447](https://linux-hardware.org/?probe=542296a447) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [63d34f24b6](https://linux-hardware.org/?probe=63d34f24b6) | Jul 20, 2022 |
| ASUSTek       | P5K-E                       | [68023f05e9](https://linux-hardware.org/?probe=68023f05e9) | Jul 18, 2022 |
| Gigabyte      | Z590 GAMING X               | [4a97996102](https://linux-hardware.org/?probe=4a97996102) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| Intel         | DG31PR AAD97573-301         | [0ac01b7529](https://linux-hardware.org/?probe=0ac01b7529) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| MSI           | X370 KRAIT GAMING           | [e74a442ccc](https://linux-hardware.org/?probe=e74a442ccc) | Jul 17, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e6b47dedd7](https://linux-hardware.org/?probe=e6b47dedd7) | Jul 15, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [75e4cc3704](https://linux-hardware.org/?probe=75e4cc3704) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [c5695a430f](https://linux-hardware.org/?probe=c5695a430f) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [0a0ad06ece](https://linux-hardware.org/?probe=0a0ad06ece) | Jul 15, 2022 |
| ASUSTek       | M4A78 PRO                   | [119c291cd5](https://linux-hardware.org/?probe=119c291cd5) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| MSI           | B250M PRO-VH                | [d0a4b76e78](https://linux-hardware.org/?probe=d0a4b76e78) | Jul 13, 2022 |
| HP            | 83E8                        | [a2dc0fc924](https://linux-hardware.org/?probe=a2dc0fc924) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| MSI           | H81M-P33                    | [05099f85ea](https://linux-hardware.org/?probe=05099f85ea) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| Gigabyte      | Z97M-DS3H                   | [fd9365ab43](https://linux-hardware.org/?probe=fd9365ab43) | Jul 11, 2022 |
| HP            | 0B4Ch D                     | [f49fb95b26](https://linux-hardware.org/?probe=f49fb95b26) | Jul 10, 2022 |
| Lenovo        | SKYBAY NOK                  | [5e8f90f865](https://linux-hardware.org/?probe=5e8f90f865) | Jul 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c350afe818](https://linux-hardware.org/?probe=c350afe818) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| MSI           | PRO B660M-A DDR4            | [65c661af95](https://linux-hardware.org/?probe=65c661af95) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| MSI           | B250M BAZOOKA               | [e04f1fc85c](https://linux-hardware.org/?probe=e04f1fc85c) | Jul 07, 2022 |
| ASRock        | P67 Pro3                    | [b70f0fde7a](https://linux-hardware.org/?probe=b70f0fde7a) | Jul 07, 2022 |
| Dell          | 09KPNV A00                  | [7eb69e794e](https://linux-hardware.org/?probe=7eb69e794e) | Jul 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| Gigabyte      | Z97M-DS3H                   | [6ffcfe37d6](https://linux-hardware.org/?probe=6ffcfe37d6) | Jul 03, 2022 |
| ASUSTek       | M4A78 PRO                   | [d76404df8d](https://linux-hardware.org/?probe=d76404df8d) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c8b31466ed](https://linux-hardware.org/?probe=c8b31466ed) | Jul 02, 2022 |
| ASRock        | P67 Pro3                    | [9f1ed28d62](https://linux-hardware.org/?probe=9f1ed28d62) | Jul 02, 2022 |
| Dell          | 09KPNV A00                  | [163fad4354](https://linux-hardware.org/?probe=163fad4354) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8e6d23cf01](https://linux-hardware.org/?probe=8e6d23cf01) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [403db88011](https://linux-hardware.org/?probe=403db88011) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [4ba5c0b79e](https://linux-hardware.org/?probe=4ba5c0b79e) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [a32cb9b3f1](https://linux-hardware.org/?probe=a32cb9b3f1) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [632dbea587](https://linux-hardware.org/?probe=632dbea587) | Jul 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [06ca24d4e1](https://linux-hardware.org/?probe=06ca24d4e1) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | [aaf8589ded](https://linux-hardware.org/?probe=aaf8589ded) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | [bdecafbe1d](https://linux-hardware.org/?probe=bdecafbe1d) | Jun 29, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [0ea209fffe](https://linux-hardware.org/?probe=0ea209fffe) | Jun 28, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d399933441](https://linux-hardware.org/?probe=d399933441) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [1f3399d205](https://linux-hardware.org/?probe=1f3399d205) | Jun 26, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| MSI           | H81M-P33                    | [d690a68389](https://linux-hardware.org/?probe=d690a68389) | Jun 25, 2022 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6c6d94e4b7](https://linux-hardware.org/?probe=6c6d94e4b7) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [47cf388077](https://linux-hardware.org/?probe=47cf388077) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| MSI           | H81M-P33                    | [9ba6c64800](https://linux-hardware.org/?probe=9ba6c64800) | Jun 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [fe8f74c9c1](https://linux-hardware.org/?probe=fe8f74c9c1) | Jun 25, 2022 |
| ASRock        | H87 Pro4                    | [73eb3e0db6](https://linux-hardware.org/?probe=73eb3e0db6) | Jun 25, 2022 |
| Unknown       | K8NF3-VSTA                  | [f2ea6e0d83](https://linux-hardware.org/?probe=f2ea6e0d83) | Jun 24, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [6a5e82663e](https://linux-hardware.org/?probe=6a5e82663e) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Dell          | 0HY9JP A00                  | [92c1597a97](https://linux-hardware.org/?probe=92c1597a97) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [08e5f734f9](https://linux-hardware.org/?probe=08e5f734f9) | Jun 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [95d5fd3cd1](https://linux-hardware.org/?probe=95d5fd3cd1) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | B85M-E45                    | [f5e1312d31](https://linux-hardware.org/?probe=f5e1312d31) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| MSI           | B450-A PRO MAX              | [490076a383](https://linux-hardware.org/?probe=490076a383) | Jun 20, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [b9c65b6182](https://linux-hardware.org/?probe=b9c65b6182) | Jun 18, 2022 |
| ASRock        | P67 Pro3                    | [9804004de5](https://linux-hardware.org/?probe=9804004de5) | Jun 18, 2022 |
| Gigabyte      | Z97M-DS3H                   | [67757f27f2](https://linux-hardware.org/?probe=67757f27f2) | Jun 18, 2022 |
| ASUSTek       | P9X79 DELUXE                | [a6cb0e21fc](https://linux-hardware.org/?probe=a6cb0e21fc) | Jun 17, 2022 |
| Dell          | 0P9XHK A00                  | [e167c05dd2](https://linux-hardware.org/?probe=e167c05dd2) | Jun 17, 2022 |
| ASRock        | P67 Pro3                    | [2c0a807c9c](https://linux-hardware.org/?probe=2c0a807c9c) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [83733f81bd](https://linux-hardware.org/?probe=83733f81bd) | Jun 17, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| ASRock        | P67 Pro3                    | [d56de69a04](https://linux-hardware.org/?probe=d56de69a04) | Jun 14, 2022 |
| Gigabyte      | Z97M-DS3H                   | [695e3a37d4](https://linux-hardware.org/?probe=695e3a37d4) | Jun 13, 2022 |
| ASRock        | P67 Pro3                    | [48cc60a732](https://linux-hardware.org/?probe=48cc60a732) | Jun 13, 2022 |
| ASUSTek       | M3A78-CM                    | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| HP            | 3396                        | [4c0f1563a7](https://linux-hardware.org/?probe=4c0f1563a7) | Jun 12, 2022 |
| Gigabyte      | B75-D3V                     | [f0fe22dfe7](https://linux-hardware.org/?probe=f0fe22dfe7) | Jun 12, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [4e830e41ec](https://linux-hardware.org/?probe=4e830e41ec) | Jun 11, 2022 |
| MSI           | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [b0e6137115](https://linux-hardware.org/?probe=b0e6137115) | Jun 11, 2022 |
| Acer          | WG43M                       | [bdd6d72374](https://linux-hardware.org/?probe=bdd6d72374) | Jun 10, 2022 |
| Gigabyte      | H410M S2H V3                | [feaff6859d](https://linux-hardware.org/?probe=feaff6859d) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ffceb89203](https://linux-hardware.org/?probe=ffceb89203) | Jun 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [74c4c38cae](https://linux-hardware.org/?probe=74c4c38cae) | Jun 07, 2022 |
| ASRock        | P67 Pro3                    | [30155bb328](https://linux-hardware.org/?probe=30155bb328) | Jun 06, 2022 |
| ASRock        | P67 Pro3                    | [a0cc6d57b8](https://linux-hardware.org/?probe=a0cc6d57b8) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [aca6d1da03](https://linux-hardware.org/?probe=aca6d1da03) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [c0eb59d595](https://linux-hardware.org/?probe=c0eb59d595) | Jun 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [80832b1c72](https://linux-hardware.org/?probe=80832b1c72) | Jun 05, 2022 |
| Unknown       | Unknown                     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| ASUSTek       | M5A97 R2.0                  | [07468743a9](https://linux-hardware.org/?probe=07468743a9) | Jun 04, 2022 |
| Unknown       | Unknown                     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| HP            | 8056                        | [a52dec67e2](https://linux-hardware.org/?probe=a52dec67e2) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [4d3213676b](https://linux-hardware.org/?probe=4d3213676b) | Jun 04, 2022 |
| Gigabyte      | F2A88X-D3H                  | [5b7b255faf](https://linux-hardware.org/?probe=5b7b255faf) | Jun 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8ac5eb21ad](https://linux-hardware.org/?probe=8ac5eb21ad) | Jun 04, 2022 |
| ASRock        | P67 Pro3                    | [be79ac4787](https://linux-hardware.org/?probe=be79ac4787) | Jun 02, 2022 |
| Dell          | 0GDG8Y A00                  | [ae659a73f9](https://linux-hardware.org/?probe=ae659a73f9) | Jun 02, 2022 |
| ASRock        | P67 Pro3                    | [cd48749015](https://linux-hardware.org/?probe=cd48749015) | Jun 01, 2022 |
| Huanan        | X99-F8 NALEX, NALEX         | [5c3c77a5a0](https://linux-hardware.org/?probe=5c3c77a5a0) | May 31, 2022 |
| ASRock        | P67 Pro3                    | [0494b65f2c](https://linux-hardware.org/?probe=0494b65f2c) | May 31, 2022 |
| Dell          | 0J3C2F A02                  | [9ff329a1fd](https://linux-hardware.org/?probe=9ff329a1fd) | May 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Gigabyte      | EP45C-DS3R                  | [dc6dbe40d9](https://linux-hardware.org/?probe=dc6dbe40d9) | May 30, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| Huanan        | X99-F8 NALEX, NALEX         | [d6de670b16](https://linux-hardware.org/?probe=d6de670b16) | May 30, 2022 |
| Gigabyte      | Z97M-DS3H                   | [3192e3b512](https://linux-hardware.org/?probe=3192e3b512) | May 30, 2022 |
| Dell          | 0GWHMW A01                  | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| ASRock        | P67 Pro3                    | [e01dc9eb3d](https://linux-hardware.org/?probe=e01dc9eb3d) | May 30, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| ASRock        | P67 Pro3                    | [40ac10c85e](https://linux-hardware.org/?probe=40ac10c85e) | May 29, 2022 |
| ASRock        | P67 Pro3                    | [bd8541bdaa](https://linux-hardware.org/?probe=bd8541bdaa) | May 28, 2022 |
| ASRock        | P67 Pro3                    | [79a9263b65](https://linux-hardware.org/?probe=79a9263b65) | May 28, 2022 |
| ASRock        | Z87 Extreme4                | [d3315c5c94](https://linux-hardware.org/?probe=d3315c5c94) | May 27, 2022 |
| Dell          | 09M8Y8 A01                  | [7514f64b6e](https://linux-hardware.org/?probe=7514f64b6e) | May 26, 2022 |
| Dell          | 0MY171 A01                  | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ea24b77e94](https://linux-hardware.org/?probe=ea24b77e94) | May 25, 2022 |
| Dell          | 0DT029 A00                  | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| Acer          | WG43M                       | [ae5adc512f](https://linux-hardware.org/?probe=ae5adc512f) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| ASUSTek       | B150M-A/M.2                 | [3aea6596c6](https://linux-hardware.org/?probe=3aea6596c6) | May 23, 2022 |
| Unknown       | Unknown                     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| HP            | 1495                        | [adf94f2549](https://linux-hardware.org/?probe=adf94f2549) | May 23, 2022 |
| HP            | 1495                        | [be2c2cbd65](https://linux-hardware.org/?probe=be2c2cbd65) | May 23, 2022 |
| HP            | 1495                        | [9d476ad9d1](https://linux-hardware.org/?probe=9d476ad9d1) | May 23, 2022 |
| HP            | 1495                        | [61f2119a07](https://linux-hardware.org/?probe=61f2119a07) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| MSI           | MS-7235                     | [cb9b6ded76](https://linux-hardware.org/?probe=cb9b6ded76) | May 22, 2022 |
| ASRock        | P67 Pro3                    | [6bb8448487](https://linux-hardware.org/?probe=6bb8448487) | May 22, 2022 |
| MSI           | MS-7235                     | [4dfaad64fd](https://linux-hardware.org/?probe=4dfaad64fd) | May 21, 2022 |
| ASRock        | P67 Pro3                    | [855045a0fa](https://linux-hardware.org/?probe=855045a0fa) | May 21, 2022 |
| ASRock        | P67 Pro3                    | [1cbf12b67a](https://linux-hardware.org/?probe=1cbf12b67a) | May 21, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [4a971be254](https://linux-hardware.org/?probe=4a971be254) | May 19, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| Gigabyte      | Z97M-DS3H                   | [1c9a384e09](https://linux-hardware.org/?probe=1c9a384e09) | May 17, 2022 |
| ASUSTek       | M3A78-CM                    | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [528659dab4](https://linux-hardware.org/?probe=528659dab4) | May 15, 2022 |
| Gigabyte      | Z97M-DS3H                   | [82b98a2f7e](https://linux-hardware.org/?probe=82b98a2f7e) | May 15, 2022 |
| Dell          | 0HY9JP A02                  | [5f98aaf42c](https://linux-hardware.org/?probe=5f98aaf42c) | May 14, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1c124eec80](https://linux-hardware.org/?probe=1c124eec80) | May 12, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [1e1a8e1815](https://linux-hardware.org/?probe=1e1a8e1815) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [56fc7bcca2](https://linux-hardware.org/?probe=56fc7bcca2) | May 10, 2022 |
| ASRock        | B660M-ITX/ac                | [88d7b71293](https://linux-hardware.org/?probe=88d7b71293) | May 10, 2022 |
| Dell          | 07T4MC A06                  | [34e338f194](https://linux-hardware.org/?probe=34e338f194) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [027968f6e4](https://linux-hardware.org/?probe=027968f6e4) | May 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [72ae77348e](https://linux-hardware.org/?probe=72ae77348e) | May 07, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 221      | 10.88%  |
| OpenMandriva 4.2   | 129      | 6.35%   |
| OpenMandriva 4.3   | 115      | 5.66%   |
| Ubuntu 18.04       | 108      | 5.31%   |
| Arch Rolling       | 70       | 3.44%   |
| Ubuntu 22.04       | 64       | 3.15%   |
| ROSA R10           | 47       | 2.31%   |
| Debian 11          | 41       | 2.02%   |
| ROSA R11           | 39       | 1.92%   |
| Manjaro            | 33       | 1.62%   |
| Zorin 16           | 32       | 1.57%   |
| OpenMandriva 23.01 | 32       | 1.57%   |
| ROSA R9            | 31       | 1.53%   |
| OpenMandriva 23.03 | 29       | 1.43%   |
| ROSA R11.1         | 28       | 1.38%   |
| Linux Mint 20.3    | 24       | 1.18%   |
| Linux Mint 20.1    | 24       | 1.18%   |
| Arch               | 24       | 1.18%   |
| Fedora 36          | 23       | 1.13%   |
| Linux Mint 21.1    | 22       | 1.08%   |
| KDE neon 20.04     | 22       | 1.08%   |
| Fedora 37          | 22       | 1.08%   |
| Pop!_OS 22.04      | 21       | 1.03%   |
| Linux Mint 20      | 21       | 1.03%   |
| Ubuntu 20.10       | 20       | 0.98%   |
| ROSA R8.1          | 19       | 0.94%   |
| OpenMandriva 4.50  | 19       | 0.94%   |
| Ubuntu 19.10       | 18       | 0.89%   |
| Linux Mint 20.2    | 18       | 0.89%   |
| Ubuntu 19.04       | 17       | 0.84%   |
| ROSA R8            | 17       | 0.84%   |
| Fedora 35          | 17       | 0.84%   |
| Fedora 34          | 17       | 0.84%   |
| Ubuntu 21.04       | 16       | 0.79%   |
| Linux Mint 19.3    | 16       | 0.79%   |
| Kubuntu 20.04      | 16       | 0.79%   |
| Ubuntu 21.10       | 15       | 0.74%   |
| Pop!_OS 20.04      | 15       | 0.74%   |
| ArcoLinux Rolling  | 15       | 0.74%   |
| Fedora 33          | 14       | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 468      | 25.42%  |
| OpenMandriva  | 308      | 16.73%  |
| ROSA          | 147      | 7.98%   |
| Linux Mint    | 147      | 7.98%   |
| Fedora        | 112      | 6.08%   |
| Arch          | 91       | 4.94%   |
| Manjaro       | 78       | 4.24%   |
| Debian        | 69       | 3.75%   |
| Pop!_OS       | 61       | 3.31%   |
| Zorin         | 41       | 2.23%   |
| Kubuntu       | 41       | 2.23%   |
| KDE neon      | 30       | 1.63%   |
| Xubuntu       | 24       | 1.3%    |
| Gentoo        | 23       | 1.25%   |
| openSUSE      | 16       | 0.87%   |
| ArcoLinux     | 15       | 0.81%   |
| Endless       | 12       | 0.65%   |
| EndeavourOS   | 11       | 0.6%    |
| BlackPanther  | 11       | 0.6%    |
| Ubuntu MATE   | 10       | 0.54%   |
| Ubuntu Unity  | 9        | 0.49%   |
| MX            | 9        | 0.49%   |
| LMDE          | 9        | 0.49%   |
| Lubuntu       | 8        | 0.43%   |
| Elementary    | 8        | 0.43%   |
| CentOS        | 7        | 0.38%   |
| Kali          | 6        | 0.33%   |
| Clear Linux   | 6        | 0.33%   |
| Void Linux    | 5        | 0.27%   |
| Nobara        | 4        | 0.22%   |
| Xero          | 3        | 0.16%   |
| Ubuntu Budgie | 3        | 0.16%   |
| NixOS         | 3        | 0.16%   |
| Linux Lite    | 3        | 0.16%   |
| Garuda Linux  | 3        | 0.16%   |
| EuroLinux     | 3        | 0.16%   |
| Devuan        | 3        | 0.16%   |
| SteamOS       | 2        | 0.11%   |
| RHEL          | 2        | 0.11%   |
| Peppermint    | 2        | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 125      | 5.36%   |
| 5.16.7-desktop-1omv4003             | 99       | 4.24%   |
| 5.4.0-42-generic                    | 34       | 1.46%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 30       | 1.29%   |
| 6.2.6-desktop-1omv2390              | 27       | 1.16%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 27       | 1.16%   |
| 6.1.1-desktop-1omv2290              | 26       | 1.11%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 22       | 0.94%   |
| 5.4.0-26-generic                    | 19       | 0.81%   |
| 5.16.13-desktop-1omv4003            | 19       | 0.81%   |
| 5.15.0-56-generic                   | 16       | 0.69%   |
| 5.4.0-52-generic                    | 15       | 0.64%   |
| 5.4.0-58-generic                    | 13       | 0.56%   |
| 5.19.0-35-generic                   | 13       | 0.56%   |
| 5.15.0-52-generic                   | 13       | 0.56%   |
| 5.8.0-48-generic                    | 12       | 0.51%   |
| 5.4.0-72-generic                    | 12       | 0.51%   |
| 5.4.0-54-generic                    | 12       | 0.51%   |
| 5.4.0-48-generic                    | 12       | 0.51%   |
| 5.4.0-40-generic                    | 12       | 0.51%   |
| 5.15.0-43-generic                   | 12       | 0.51%   |
| 5.4.0-66-generic                    | 11       | 0.47%   |
| 5.3.0-46-generic                    | 11       | 0.47%   |
| 5.13.0-39-generic                   | 11       | 0.47%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 11       | 0.47%   |
| 5.8.0-43-generic                    | 10       | 0.43%   |
| 5.4.0-56-generic                    | 10       | 0.43%   |
| 5.4.0-29-generic                    | 10       | 0.43%   |
| 5.15.0-58-generic                   | 10       | 0.43%   |
| 5.13.0-40-generic                   | 10       | 0.43%   |
| 5.13.0-27-generic                   | 10       | 0.43%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 10       | 0.43%   |
| 5.4.0-81-generic                    | 9        | 0.39%   |
| 5.4.0-65-generic                    | 9        | 0.39%   |
| 5.4.0-47-generic                    | 9        | 0.39%   |
| 5.4.0-37-generic                    | 9        | 0.39%   |
| 5.19.0-32-generic                   | 9        | 0.39%   |
| 5.15.0-48-generic                   | 9        | 0.39%   |
| 4.18.16-desktop-1bP                 | 9        | 0.39%   |
| 5.8.0-53-generic                    | 8        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 297      | 13.69%  |
| 4.15.0  | 132      | 6.08%   |
| 5.10.14 | 126      | 5.81%   |
| 5.15.0  | 122      | 5.62%   |
| 5.16.7  | 101      | 4.65%   |
| 5.8.0   | 85       | 3.92%   |
| 5.11.0  | 71       | 3.27%   |
| 5.13.0  | 67       | 3.09%   |
| 5.3.0   | 56       | 2.58%   |
| 5.19.0  | 49       | 2.26%   |
| 5.10.0  | 42       | 1.94%   |
| 5.0.0   | 37       | 1.71%   |
| 6.2.6   | 34       | 1.57%   |
| 4.9.60  | 33       | 1.52%   |
| 4.18.0  | 30       | 1.38%   |
| 6.1.1   | 27       | 1.24%   |
| 4.9.20  | 27       | 1.24%   |
| 4.19.0  | 21       | 0.97%   |
| 5.16.13 | 19       | 0.88%   |
| 4.1.38  | 14       | 0.65%   |
| 6.1.0   | 12       | 0.55%   |
| 4.9.124 | 10       | 0.46%   |
| 4.1.34  | 10       | 0.46%   |
| 6.0.12  | 9        | 0.41%   |
| 4.9.155 | 9        | 0.41%   |
| 4.18.16 | 9        | 0.41%   |
| 5.17.5  | 8        | 0.37%   |
| 4.9.76  | 8        | 0.37%   |
| 6.0.8   | 7        | 0.32%   |
| 6.0.0   | 7        | 0.32%   |
| 5.6.0   | 7        | 0.32%   |
| 5.4.32  | 7        | 0.32%   |
| 6.2.0   | 6        | 0.28%   |
| 6.1.41  | 6        | 0.28%   |
| 6.1.4   | 6        | 0.28%   |
| 6.1.12  | 6        | 0.28%   |
| 5.9.16  | 6        | 0.28%   |
| 5.9.0   | 6        | 0.28%   |
| 5.19.5  | 6        | 0.28%   |
| 5.15.12 | 6        | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 335      | 16.15%  |
| 5.10    | 215      | 10.37%  |
| 5.15    | 183      | 8.82%   |
| 5.16    | 138      | 6.65%   |
| 4.15    | 132      | 6.36%   |
| 5.8     | 106      | 5.11%   |
| 5.11    | 97       | 4.68%   |
| 5.13    | 80       | 3.86%   |
| 6.1     | 79       | 3.81%   |
| 4.9     | 78       | 3.76%   |
| 5.19    | 71       | 3.42%   |
| 6.2     | 62       | 2.99%   |
| 5.3     | 62       | 2.99%   |
| 6.0     | 47       | 2.27%   |
| 5.0     | 41       | 1.98%   |
| 4.18    | 39       | 1.88%   |
| 5.12    | 31       | 1.49%   |
| 5.18    | 30       | 1.45%   |
| 5.14    | 29       | 1.4%    |
| 4.1     | 28       | 1.35%   |
| 6.3     | 27       | 1.3%    |
| 5.9     | 27       | 1.3%    |
| 5.17    | 27       | 1.3%    |
| 4.19    | 25       | 1.21%   |
| 5.6     | 24       | 1.16%   |
| 5.5     | 16       | 0.77%   |
| 5.7     | 13       | 0.63%   |
| 6.4     | 9        | 0.43%   |
| 4.4     | 6        | 0.29%   |
| 4.16    | 3        | 0.14%   |
| 5.1     | 2        | 0.1%    |
| 4.8     | 2        | 0.1%    |
| 4.20    | 2        | 0.1%    |
| 5.2     | 1        | 0.05%   |
| 4.7     | 1        | 0.05%   |
| 4.14    | 1        | 0.05%   |
| 4.13    | 1        | 0.05%   |
| 4.12    | 1        | 0.05%   |
| 3.16    | 1        | 0.05%   |
| 3.13    | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1722     | 97.62%  |
| i686   | 40       | 2.27%   |
| ppc64  | 1        | 0.06%   |
| ppc    | 1        | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 612      | 32.67%  |
| KDE5            | 555      | 29.63%  |
| Unknown         | 187      | 9.98%   |
| XFCE            | 123      | 6.57%   |
| X-Cinnamon      | 96       | 5.13%   |
| KDE4            | 78       | 4.16%   |
| MATE            | 55       | 2.94%   |
| KDE             | 52       | 2.78%   |
| Cinnamon        | 22       | 1.17%   |
| i3              | 18       | 0.96%   |
| LXQt            | 17       | 0.91%   |
| Unity           | 10       | 0.53%   |
| LXDE            | 9        | 0.48%   |
| Pantheon        | 8        | 0.43%   |
| Deepin          | 6        | 0.32%   |
| GNOME Flashback | 4        | 0.21%   |
| Budgie          | 4        | 0.21%   |
| GNOME Classic   | 3        | 0.16%   |
| qtile           | 2        | 0.11%   |
| openbox         | 2        | 0.11%   |
| Hyprland        | 2        | 0.11%   |
| awesome         | 2        | 0.11%   |
| xmonad          | 1        | 0.05%   |
| jwm             | 1        | 0.05%   |
| ICEWM           | 1        | 0.05%   |
| gnome-xorg      | 1        | 0.05%   |
| fluxbox         | 1        | 0.05%   |
| DWM             | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1499     | 82.23%  |
| Wayland | 194      | 10.64%  |
| Unknown | 79       | 4.33%   |
| Tty     | 51       | 2.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 787      | 42.4%   |
| SDDM    | 507      | 27.32%  |
| LightDM | 146      | 7.87%   |
| GDM     | 142      | 7.65%   |
| GDM3    | 124      | 6.68%   |
| KDM     | 86       | 4.63%   |
| TDM     | 52       | 2.8%    |
| XDM     | 4        | 0.22%   |
| SLiM    | 2        | 0.11%   |
| LXDM    | 2        | 0.11%   |
| SLIMSKI | 1        | 0.05%   |
| MDM     | 1        | 0.05%   |
| LY-DM   | 1        | 0.05%   |
| Ly      | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pl_PL       | 1049     | 56.58%  |
| en_US       | 421      | 22.71%  |
| Unknown     | 258      | 13.92%  |
| en_GB       | 51       | 2.75%   |
| C           | 29       | 1.56%   |
| ru_RU       | 10       | 0.54%   |
| en_CA       | 7        | 0.38%   |
| de_DE       | 4        | 0.22%   |
| szl_PL      | 3        | 0.16%   |
| ru_UA       | 3        | 0.16%   |
| en_AG       | 3        | 0.16%   |
| uk_UA       | 2        | 0.11%   |
| fr_FR       | 2        | 0.11%   |
| en_IE       | 2        | 0.11%   |
| en_DK       | 2        | 0.11%   |
| sv_SE       | 1        | 0.05%   |
| POSIX       | 1        | 0.05%   |
| pl_PL.UTF8  | 1        | 0.05%   |
| en_US.UTF8  | 1        | 0.05%   |
| en_US.utf-8 | 1        | 0.05%   |
| en_SE       | 1        | 0.05%   |
| en_IN       | 1        | 0.05%   |
| de_CH       | 1        | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1110     | 61.33%  |
| EFI  | 700      | 38.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1210     | 65.05%  |
| Overlay  | 293      | 15.75%  |
| Btrfs    | 170      | 9.14%   |
| Unknown  | 117      | 6.29%   |
| Xfs      | 26       | 1.4%    |
| Tmpfs    | 16       | 0.86%   |
| Zfs      | 10       | 0.54%   |
| F2fs     | 7        | 0.38%   |
| Ext2     | 4        | 0.22%   |
| Ext3     | 3        | 0.16%   |
| Jfs      | 2        | 0.11%   |
| SquXshfs | 1        | 0.05%   |
| Aufs     | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 867      | 46.94%  |
| GPT     | 628      | 34%     |
| MBR     | 352      | 19.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1371     | 74.96%  |
| Yes       | 458      | 25.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1108     | 60.98%  |
| Yes       | 709      | 39.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 415      | 23.59%  |
| ASUSTek Computer    | 385      | 21.89%  |
| MSI                 | 297      | 16.88%  |
| ASRock              | 172      | 9.78%   |
| Dell                | 150      | 8.53%   |
| Hewlett-Packard     | 118      | 6.71%   |
| Lenovo              | 62       | 3.52%   |
| Fujitsu             | 27       | 1.53%   |
| Intel               | 23       | 1.31%   |
| Acer                | 17       | 0.97%   |
| Foxconn             | 14       | 0.8%    |
| Unknown             | 12       | 0.68%   |
| Fujitsu Siemens     | 11       | 0.63%   |
| Inventec            | 6        | 0.34%   |
| Huanan              | 5        | 0.28%   |
| Medion              | 4        | 0.23%   |
| ECS                 | 4        | 0.23%   |
| Pegatron            | 3        | 0.17%   |
| Biostar             | 3        | 0.17%   |
| ABIT                | 3        | 0.17%   |
| Supermicro          | 2        | 0.11%   |
| Hardkernel          | 2        | 0.11%   |
| Gateway             | 2        | 0.11%   |
| Apple               | 2        | 0.11%   |
| AMI                 | 2        | 0.11%   |
| ACTION              | 2        | 0.11%   |
| Wortmann AG         | 1        | 0.06%   |
| WeiBu               | 1        | 0.06%   |
| Shuttle             | 1        | 0.06%   |
| Seeed Studio        | 1        | 0.06%   |
| POSIFLEX            | 1        | 0.06%   |
| OPTIMUS             | 1        | 0.06%   |
| Nvidia              | 1        | 0.06%   |
| MACHINIST           | 1        | 0.06%   |
| ITSUMI              | 1        | 0.06%   |
| HEDYCOMPUTER        | 1        | 0.06%   |
| Hampoo              | 1        | 0.06%   |
| Google              | 1        | 0.06%   |
| EVGA                | 1        | 0.06%   |
| ASRockRack          | 1        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 33       | 1.88%   |
| Gigabyte B450M DS3H          | 18       | 1.02%   |
| ASUS SABERTOOTH Z77          | 18       | 1.02%   |
| MSI MS-7B86                  | 17       | 0.97%   |
| MSI MS-7817                  | 16       | 0.91%   |
| Dell OptiPlex 780            | 15       | 0.85%   |
| MSI MS-7C37                  | 12       | 0.68%   |
| MSI MS-7C02                  | 12       | 0.68%   |
| Unknown                      | 12       | 0.68%   |
| Dell OptiPlex 7010           | 11       | 0.63%   |
| Gigabyte B450 AORUS ELITE    | 10       | 0.57%   |
| MSI MS-7B79                  | 9        | 0.51%   |
| MSI MS-7721                  | 9        | 0.51%   |
| Gigabyte B85M-D3H            | 9        | 0.51%   |
| Dell OptiPlex 755            | 9        | 0.51%   |
| ASUS TUF Gaming X570-PLUS    | 9        | 0.51%   |
| MSI MS-7A38                  | 8        | 0.45%   |
| MSI MS-7816                  | 8        | 0.45%   |
| Gigabyte B550 AORUS ELITE V2 | 8        | 0.45%   |
| ASUS PRIME B450M-A           | 8        | 0.45%   |
| MSI MS-7B89                  | 7        | 0.4%    |
| HP t620 Quad Core TC         | 7        | 0.4%    |
| ASUS PRIME X470-PRO          | 7        | 0.4%    |
| Gigabyte P31-DS3L            | 6        | 0.34%   |
| Gigabyte 970A-DS3P           | 6        | 0.34%   |
| Dell OptiPlex 9020           | 6        | 0.34%   |
| Dell OptiPlex 790            | 6        | 0.34%   |
| ASUS PRIME B350-PLUS         | 6        | 0.34%   |
| MSI MS-7D25                  | 5        | 0.28%   |
| MSI MS-7C91                  | 5        | 0.28%   |
| MSI MS-7C80                  | 5        | 0.28%   |
| MSI MS-7C52                  | 5        | 0.28%   |
| MSI MS-7B84                  | 5        | 0.28%   |
| MSI MS-7971                  | 5        | 0.28%   |
| HP EliteDesk 800 G1 SFF      | 5        | 0.28%   |
| HP Compaq Elite 8300 SFF     | 5        | 0.28%   |
| Gigabyte GA-MA770T-UD3P      | 5        | 0.28%   |
| Gigabyte G31M-S2L            | 5        | 0.28%   |
| Gigabyte G31M-ES2L           | 5        | 0.28%   |
| Gigabyte A320M-S2H           | 5        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 103      | 5.86%   |
| ASUS PRIME              | 68       | 3.87%   |
| HP Compaq               | 46       | 2.62%   |
| Lenovo ThinkCentre      | 40       | 2.27%   |
| ASUS TUF                | 35       | 1.99%   |
| ASUS All                | 33       | 1.88%   |
| ASUS ROG                | 28       | 1.59%   |
| Gigabyte B450M          | 26       | 1.48%   |
| Dell Precision          | 24       | 1.36%   |
| HP EliteDesk            | 23       | 1.31%   |
| ASUS SABERTOOTH         | 20       | 1.14%   |
| Fujitsu ESPRIMO         | 18       | 1.02%   |
| MSI MS-7B86             | 17       | 0.97%   |
| MSI MS-7817             | 16       | 0.91%   |
| Gigabyte B550           | 15       | 0.85%   |
| Gigabyte X570           | 14       | 0.8%    |
| Gigabyte B450           | 14       | 0.8%    |
| MSI MS-7C37             | 12       | 0.68%   |
| MSI MS-7C02             | 12       | 0.68%   |
| Unknown                 | 12       | 0.68%   |
| Dell Vostro             | 11       | 0.63%   |
| ASUS M5A97              | 10       | 0.57%   |
| MSI MS-7B79             | 9        | 0.51%   |
| MSI MS-7721             | 9        | 0.51%   |
| Gigabyte B85M-D3H       | 9        | 0.51%   |
| ASRock B450             | 9        | 0.51%   |
| MSI MS-7A38             | 8        | 0.45%   |
| MSI MS-7816             | 8        | 0.45%   |
| HP t620                 | 8        | 0.45%   |
| ASUS P5G41T-M           | 8        | 0.45%   |
| MSI MS-7B89             | 7        | 0.4%    |
| Lenovo ThinkStation     | 7        | 0.4%    |
| Lenovo IdeaCentre       | 7        | 0.4%    |
| HP ProDesk              | 7        | 0.4%    |
| Gigabyte GA-78LMT-USB3  | 7        | 0.4%    |
| Fujitsu Siemens ESPRIMO | 7        | 0.4%    |
| ASUS P8H61-M            | 7        | 0.4%    |
| Gigabyte Z390           | 6        | 0.34%   |
| Gigabyte P31-DS3L       | 6        | 0.34%   |
| Gigabyte B560M          | 6        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 200      | 11.37%  |
| 2012    | 172      | 9.78%   |
| 2013    | 162      | 9.21%   |
| 2019    | 121      | 6.88%   |
| 2011    | 114      | 6.48%   |
| 2009    | 114      | 6.48%   |
| 2014    | 109      | 6.2%    |
| 2020    | 105      | 5.97%   |
| 2017    | 97       | 5.51%   |
| 2010    | 93       | 5.29%   |
| 2007    | 88       | 5%      |
| 2008    | 81       | 4.6%    |
| 2015    | 78       | 4.43%   |
| 2016    | 72       | 4.09%   |
| 2021    | 67       | 3.81%   |
| 2006    | 41       | 2.33%   |
| 2022    | 24       | 1.36%   |
| 2005    | 8        | 0.45%   |
| 2023    | 4        | 0.23%   |
| 2004    | 4        | 0.23%   |
| Unknown | 4        | 0.23%   |
| 2001    | 1        | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1759     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1732     | 98.07%  |
| Enabled  | 34       | 1.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1757     | 99.89%  |
| Yes  | 2        | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 411      | 22.56%  |
| 8.01-16.0       | 391      | 21.46%  |
| 3.01-4.0        | 279      | 15.31%  |
| 4.01-8.0        | 274      | 15.04%  |
| 32.01-64.0      | 250      | 13.72%  |
| 64.01-256.0     | 78       | 4.28%   |
| 1.01-2.0        | 53       | 2.91%   |
| 24.01-32.0      | 51       | 2.8%    |
| 2.01-3.0        | 25       | 1.37%   |
| 0.51-1.0        | 9        | 0.49%   |
| More than 256.0 | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 756      | 36.7%   |
| 2.01-3.0    | 423      | 20.53%  |
| 4.01-8.0    | 285      | 13.83%  |
| 3.01-4.0    | 217      | 10.53%  |
| 0.51-1.0    | 206      | 10%     |
| 8.01-16.0   | 88       | 4.27%   |
| 0.01-0.5    | 41       | 1.99%   |
| 16.01-24.0  | 31       | 1.5%    |
| 24.01-32.0  | 7        | 0.34%   |
| 32.01-64.0  | 3        | 0.15%   |
| 64.01-256.0 | 2        | 0.1%    |
| Unknown     | 1        | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 669      | 35.47%  |
| 2      | 551      | 29.22%  |
| 3      | 344      | 18.24%  |
| 4      | 161      | 8.54%   |
| 5      | 70       | 3.71%   |
| 6      | 33       | 1.75%   |
| 0      | 26       | 1.38%   |
| 7      | 15       | 0.8%    |
| 8      | 7        | 0.37%   |
| 11     | 3        | 0.16%   |
| 9      | 3        | 0.16%   |
| 10     | 2        | 0.11%   |
| 13     | 1        | 0.05%   |
| 12     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 914      | 50.89%  |
| No        | 882      | 49.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1743     | 99.09%  |
| No        | 16       | 0.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1089     | 60.43%  |
| Yes       | 713      | 39.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1337     | 74.57%  |
| Yes       | 456      | 25.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 1759     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Warsaw                 | 365      | 18.59%  |
| Krakow                 | 131      | 6.67%   |
| Wroclaw                | 115      | 5.86%   |
| Poznan                 | 78       | 3.97%   |
| Gdansk                 | 65       | 3.31%   |
| Katowice               | 53       | 2.7%    |
| Lodz                   | 47       | 2.39%   |
| Gdynia                 | 28       | 1.43%   |
| Lublin                 | 27       | 1.38%   |
| Bialystok              | 22       | 1.12%   |
| Szczecin               | 20       | 1.02%   |
| Gliwice                | 19       | 0.97%   |
| Częstochowa           | 19       | 0.97%   |
| Strzyzow               | 18       | 0.92%   |
| Radom                  | 15       | 0.76%   |
| Bytom                  | 15       | 0.76%   |
| Torun                  | 14       | 0.71%   |
| Rybnik                 | 14       | 0.71%   |
| Rzeszów               | 13       | 0.66%   |
| Bielsko-Biala          | 13       | 0.66%   |
| Płock                 | 12       | 0.61%   |
| Bydgoszcz              | 12       | 0.61%   |
| Kielce                 | 11       | 0.56%   |
| Sosnowiec              | 10       | 0.51%   |
| Ruda Śląska          | 9        | 0.46%   |
| Zabrze                 | 8        | 0.41%   |
| Wodzisław Śląski    | 8        | 0.41%   |
| Debica                 | 8        | 0.41%   |
| Wołomin               | 7        | 0.36%   |
| Tychy                  | 7        | 0.36%   |
| Tarnów                | 7        | 0.36%   |
| Siemianowice Śląskie | 7        | 0.36%   |
| Jelenia Góra          | 7        | 0.36%   |
| Elblag                 | 7        | 0.36%   |
| Cieszyn                | 7        | 0.36%   |
| Chorzów               | 7        | 0.36%   |
| Będzin                | 7        | 0.36%   |
| Zielona Góra          | 6        | 0.31%   |
| Zdunska Wola           | 6        | 0.31%   |
| Piaseczno              | 6        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 576      | 1006   | 17.02%  |
| Seagate                   | 575      | 1021   | 16.99%  |
| Samsung Electronics       | 425      | 758    | 12.56%  |
| GOODRAM                   | 252      | 428    | 7.44%   |
| Toshiba                   | 201      | 361    | 5.94%   |
| Crucial                   | 154      | 273    | 4.55%   |
| Kingston                  | 142      | 211    | 4.19%   |
| A-DATA Technology         | 137      | 212    | 4.05%   |
| Hitachi                   | 100      | 188    | 2.95%   |
| Sandisk                   | 93       | 149    | 2.75%   |
| Patriot                   | 58       | 79     | 1.71%   |
| SPCC                      | 42       | 83     | 1.24%   |
| Intel                     | 40       | 65     | 1.18%   |
| XPG                       | 38       | 56     | 1.12%   |
| Plextor                   | 32       | 38     | 0.95%   |
| HGST                      | 31       | 44     | 0.92%   |
| PNY                       | 27       | 32     | 0.8%    |
| Phison                    | 26       | 35     | 0.77%   |
| Apacer                    | 25       | 41     | 0.74%   |
| Unknown                   | 24       | 43     | 0.71%   |
| OCZ                       | 22       | 25     | 0.65%   |
| Maxtor                    | 21       | 21     | 0.62%   |
| Micron Technology         | 20       | 28     | 0.59%   |
| Corsair                   | 20       | 29     | 0.59%   |
| China                     | 19       | 28     | 0.56%   |
| Realtek Semiconductor     | 18       | 29     | 0.53%   |
| Fujitsu                   | 17       | 20     | 0.5%    |
| SK hynix                  | 15       | 27     | 0.44%   |
| Phison Electronics        | 15       | 26     | 0.44%   |
| ASMT                      | 14       | 15     | 0.41%   |
| Silicon Motion            | 13       | 17     | 0.38%   |
| Lite-On                   | 12       | 14     | 0.35%   |
| Micron/Crucial Technology | 11       | 11     | 0.32%   |
| ADATA Technology          | 10       | 11     | 0.3%    |
| KIOXIA-EXCERIA            | 8        | 14     | 0.24%   |
| KIOXIA                    | 8        | 9      | 0.24%   |
| JMicron Technology        | 8        | 9      | 0.24%   |
| Transcend                 | 7        | 7      | 0.21%   |
| LITEON                    | 7        | 12     | 0.21%   |
| Lexar                     | 7        | 7      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                                 | 56       | 1.43%   |
| Seagate ST500DM002-1BD142 500GB                     | 38       | 0.97%   |
| Crucial CT500MX500SSD1 500GB                        | 38       | 0.97%   |
| Samsung SSD 850 EVO 250GB                           | 34       | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB                      | 32       | 0.82%   |
| Seagate ST3500418AS 500GB                           | 29       | 0.74%   |
| Seagate ST1000DM003-1ER162 1TB                      | 29       | 0.74%   |
| GOODRAM SSD 120GB                                   | 27       | 0.69%   |
| Samsung NVMe SSD Drive 500GB                        | 26       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                         | 26       | 0.66%   |
| Samsung HD502HJ 500GB                               | 25       | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                    | 24       | 0.61%   |
| Toshiba DT01ACA100 1TB                              | 23       | 0.59%   |
| Samsung SSD 860 EVO 500GB                           | 22       | 0.56%   |
| Samsung SSD 860 EVO 250GB                           | 22       | 0.56%   |
| GOODRAM SSD 240GB                                   | 22       | 0.56%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 21       | 0.54%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 21       | 0.54%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 21       | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB                      | 20       | 0.51%   |
| Crucial CT240BX500SSD1 240GB                        | 20       | 0.51%   |
| Toshiba HDWD130 3TB                                 | 19       | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 19       | 0.48%   |
| A-DATA SU800 256GB SSD                              | 18       | 0.46%   |
| Patriot Burst 120GB SSD                             | 16       | 0.41%   |
| Kingston SA400S37480G 480GB SSD                     | 16       | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 15       | 0.38%   |
| Kingston SA400S37240G 240GB SSD                     | 15       | 0.38%   |
| GOODRAM SSDPR-CX400-128 128GB                       | 15       | 0.38%   |
| GOODRAM SSDPR-CL100-120-G2 120GB                    | 15       | 0.38%   |
| A-DATA SX8200PNP 512GB                              | 15       | 0.38%   |
| Seagate ST3250410AS 250GB                           | 14       | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14       | 0.36%   |
| Samsung SSD 980 1TB                                 | 14       | 0.36%   |
| Samsung HD103SJ 1TB                                 | 14       | 0.36%   |
| A-DATA SU650 240GB SSD                              | 14       | 0.36%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 13       | 0.33%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 13       | 0.33%   |
| SPCC Solid State Disk 120GB                         | 13       | 0.33%   |
| Seagate ST3250310AS 250GB                           | 13       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 575      | 1019   | 35.38%  |
| WDC                 | 540      | 941    | 33.23%  |
| Toshiba             | 180      | 338    | 11.08%  |
| Samsung Electronics | 134      | 204    | 8.25%   |
| Hitachi             | 100      | 188    | 6.15%   |
| HGST                | 31       | 44     | 1.91%   |
| Maxtor              | 20       | 20     | 1.23%   |
| Fujitsu             | 17       | 20     | 1.05%   |
| ASMT                | 5        | 6      | 0.31%   |
| JMicron Technology  | 4        | 4      | 0.25%   |
| WD MediaMax         | 2        | 3      | 0.12%   |
| Unknown             | 2        | 2      | 0.12%   |
| PHD 3.0             | 2        | 2      | 0.12%   |
| ASMedia             | 2        | 3      | 0.12%   |
| Unknown             | 2        | 2      | 0.12%   |
| Synology            | 1        | 1      | 0.06%   |
| MARVELL             | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| HPE                 | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| Hewlett-Packard     | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| ASUSTOR             | 1        | 1      | 0.06%   |
| ASMT109x            | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| GOODRAM             | 246      | 410    | 20.21%  |
| Samsung Electronics | 183      | 287    | 15.04%  |
| Crucial             | 148      | 266    | 12.16%  |
| A-DATA Technology   | 111      | 169    | 9.12%   |
| Kingston            | 93       | 134    | 7.64%   |
| SanDisk             | 71       | 115    | 5.83%   |
| Patriot             | 51       | 72     | 4.19%   |
| SPCC                | 37       | 76     | 3.04%   |
| WDC                 | 31       | 39     | 2.55%   |
| Plextor             | 26       | 32     | 2.14%   |
| Apacer              | 24       | 40     | 1.97%   |
| OCZ                 | 22       | 25     | 1.81%   |
| PNY                 | 21       | 25     | 1.73%   |
| Intel               | 19       | 26     | 1.56%   |
| China               | 18       | 27     | 1.48%   |
| Toshiba             | 15       | 17     | 1.23%   |
| Micron Technology   | 15       | 21     | 1.23%   |
| ASMT                | 9        | 9      | 0.74%   |
| Corsair             | 8        | 9      | 0.66%   |
| Transcend           | 7        | 7      | 0.58%   |
| LITEON              | 7        | 12     | 0.58%   |
| KIOXIA-EXCERIA      | 5        | 9      | 0.41%   |
| Intenso             | 5        | 10     | 0.41%   |
| Team                | 3        | 3      | 0.25%   |
| SK hynix            | 3        | 3      | 0.25%   |
| LITEONIT            | 3        | 3      | 0.25%   |
| Lexar               | 3        | 3      | 0.25%   |
| KingSpec            | 3        | 3      | 0.25%   |
| BIWIN               | 3        | 3      | 0.25%   |
| SSSTC               | 2        | 2      | 0.16%   |
| HS-SSD-E100         | 2        | 2      | 0.16%   |
| Gigabyte Technology | 2        | 2      | 0.16%   |
| XrayDisk            | 1        | 1      | 0.08%   |
| XPG                 | 1        | 1      | 0.08%   |
| WDC WDS2            | 1        | 1      | 0.08%   |
| Valuetech           | 1        | 1      | 0.08%   |
| Unknown             | 1        | 1      | 0.08%   |
| T-FORCE             | 1        | 1      | 0.08%   |
| SAGE                | 1        | 1      | 0.08%   |
| Phison              | 1        | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1258     | 2805   | 45.19%  |
| SSD     | 986      | 1883   | 35.42%  |
| NVMe    | 487      | 863    | 17.49%  |
| Unknown | 43       | 74     | 1.54%   |
| MMC     | 10       | 10     | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1610     | 4607   | 72.85%  |
| NVMe | 487      | 863    | 22.04%  |
| SAS  | 103      | 155    | 4.66%   |
| MMC  | 10       | 10     | 0.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1317     | 2682   | 56.19%  |
| 0.51-1.0   | 664      | 1235   | 28.33%  |
| 1.01-2.0   | 191      | 340    | 8.15%   |
| 3.01-4.0   | 61       | 141    | 2.6%    |
| 2.01-3.0   | 58       | 162    | 2.47%   |
| 4.01-10.0  | 38       | 95     | 1.62%   |
| 10.01-20.0 | 15       | 33     | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 465      | 23.64%  |
| 251-500        | 282      | 14.34%  |
| 501-1000       | 261      | 13.27%  |
| 1-20           | 214      | 10.88%  |
| 1001-2000      | 211      | 10.73%  |
| 51-100         | 151      | 7.68%   |
| More than 3000 | 120      | 6.1%    |
| Unknown        | 101      | 5.13%   |
| 21-50          | 87       | 4.42%   |
| 2001-3000      | 75       | 3.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 748      | 37.27%  |
| 21-50          | 256      | 12.76%  |
| 101-250        | 213      | 10.61%  |
| 51-100         | 179      | 8.92%   |
| 501-1000       | 164      | 8.17%   |
| 251-500        | 158      | 7.87%   |
| 1001-2000      | 103      | 5.13%   |
| Unknown        | 101      | 5.03%   |
| More than 3000 | 43       | 2.14%   |
| 2001-3000      | 42       | 2.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB           | 9        | 12     | 2.36%   |
| Seagate ST500DM002-1BD142 500GB     | 8        | 8      | 2.1%    |
| Seagate ST1000DM003-9YN162 1TB      | 7        | 7      | 1.84%   |
| Seagate ST9500325AS 500GB           | 5        | 8      | 1.31%   |
| GOODRAM SSD 120GB                   | 5        | 5      | 1.31%   |
| ASMT 2135 18TB                      | 5        | 5      | 1.31%   |
| Seagate ST92505610AS 250GB          | 4        | 4      | 1.05%   |
| Seagate ST3320613AS 320GB           | 4        | 4      | 1.05%   |
| Seagate ST1000DX001-1CM162 1TB      | 4        | 7      | 1.05%   |
| WDC WD10JFCX-68N6GN0 1TB            | 3        | 4      | 0.79%   |
| Seagate ST3500312CS 500GB           | 3        | 3      | 0.79%   |
| Seagate ST3320418AS 320GB           | 3        | 3      | 0.79%   |
| Seagate ST3250410AS 250GB           | 3        | 3      | 0.79%   |
| Seagate ST31500341AS 1TB            | 3        | 4      | 0.79%   |
| Seagate ST2000DX002-2DV164 2TB      | 3        | 5      | 0.79%   |
| Samsung Electronics HD502HJ 500GB   | 3        | 3      | 0.79%   |
| Samsung Electronics HD321KJ 320GB   | 3        | 3      | 0.79%   |
| Kingston SV300S37A120G 120GB SSD    | 3        | 3      | 0.79%   |
| Kingston SA400S37480G 480GB SSD     | 3        | 3      | 0.79%   |
| WDC WD5002ABYS-01B1B0 500GB         | 2        | 14     | 0.52%   |
| WDC WD5000AVDS-63U7B1 500GB         | 2        | 2      | 0.52%   |
| WDC WD5000AACS-00G8B1 500GB         | 2        | 2      | 0.52%   |
| WDC WD3200AAJS-00B4A0 320GB         | 2        | 4      | 0.52%   |
| WDC WD2500AAJS-75M0A0 249GB         | 2        | 2      | 0.52%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 10     | 0.52%   |
| WDC WD20EARS-00MVWB0 2TB            | 2        | 2      | 0.52%   |
| WDC WD15EARS-00Z5B1 1TB             | 2        | 2      | 0.52%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2        | 3      | 0.52%   |
| WDC WD10EADS-22M2B0 1TB             | 2        | 4      | 0.52%   |
| Toshiba MQ04ABF100 1TB              | 2        | 3      | 0.52%   |
| Toshiba MQ01ABD100 1TB              | 2        | 2      | 0.52%   |
| Toshiba MK2546GSX 250GB             | 2        | 2      | 0.52%   |
| Toshiba DT01ACA100 1TB              | 2        | 2      | 0.52%   |
| SSSTC CVB-8D128-HP 128GB SSD        | 2        | 2      | 0.52%   |
| Seagate ST500LT012-9WS142 500GB     | 2        | 2      | 0.52%   |
| Seagate ST500LT012-1DG142 500GB     | 2        | 2      | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 2      | 0.52%   |
| Seagate ST3640323AS 640GB           | 2        | 2      | 0.52%   |
| Seagate ST3500320AS 500GB           | 2        | 2      | 0.52%   |
| Seagate ST3320620AS 320GB           | 2        | 2      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 116      | 154    | 32.68%  |
| WDC                   | 86       | 141    | 24.23%  |
| Samsung Electronics   | 35       | 42     | 9.86%   |
| Hitachi               | 20       | 30     | 5.63%   |
| Toshiba               | 13       | 14     | 3.66%   |
| A-DATA Technology     | 12       | 13     | 3.38%   |
| SanDisk               | 9        | 11     | 2.54%   |
| Kingston              | 9        | 9      | 2.54%   |
| GOODRAM               | 8        | 8      | 2.25%   |
| ASMT                  | 6        | 7      | 1.69%   |
| Maxtor                | 5        | 5      | 1.41%   |
| Fujitsu               | 4        | 6      | 1.13%   |
| Hewlett-Packard       | 3        | 3      | 0.85%   |
| Apacer                | 3        | 6      | 0.85%   |
| SSSTC                 | 2        | 2      | 0.56%   |
| SPCC                  | 2        | 2      | 0.56%   |
| LITEON                | 2        | 2      | 0.56%   |
| Intel                 | 2        | 2      | 0.56%   |
| HGST                  | 2        | 2      | 0.56%   |
| China                 | 2        | 2      | 0.56%   |
| XPG                   | 1        | 1      | 0.28%   |
| WDC WDS2              | 1        | 1      | 0.28%   |
| WD MediaMax           | 1        | 2      | 0.28%   |
| SAGE                  | 1        | 1      | 0.28%   |
| Realtek Semiconductor | 1        | 1      | 0.28%   |
| Patriot               | 1        | 1      | 0.28%   |
| OCZ                   | 1        | 1      | 0.28%   |
| Micron Technology     | 1        | 1      | 0.28%   |
| LITEONIT              | 1        | 1      | 0.28%   |
| KingFast              | 1        | 1      | 0.28%   |
| HPE                   | 1        | 1      | 0.28%   |
| Crucial               | 1        | 1      | 0.28%   |
| Corsair               | 1        | 2      | 0.28%   |
| Unknown               | 1        | 1      | 0.28%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 116      | 154    | 41.73%  |
| WDC                 | 85       | 139    | 30.58%  |
| Samsung Electronics | 29       | 35     | 10.43%  |
| Hitachi             | 20       | 30     | 7.19%   |
| Toshiba             | 13       | 14     | 4.68%   |
| Maxtor              | 5        | 5      | 1.8%    |
| Fujitsu             | 4        | 6      | 1.44%   |
| HGST                | 2        | 2      | 0.72%   |
| WD MediaMax         | 1        | 2      | 0.36%   |
| Hewlett-Packard     | 1        | 1      | 0.36%   |
| ASMT                | 1        | 2      | 0.36%   |
| Unknown             | 1        | 1      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 247      | 391    | 76.71%  |
| SSD  | 69       | 80     | 21.43%  |
| NVMe | 6        | 6      | 1.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB       | 1        | 1      | 12.5%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 12.5%   |
| Toshiba DT01ACA100 1TB            | 1        | 2      | 12.5%   |
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 12.5%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 12.5%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 12.5%   |
| OCZ-AGIL ITY3 64GB SSD            | 1        | 1      | 12.5%   |
| HGST HTS725025A7 250GB            | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 25%     |
| Seagate             | 2        | 2      | 25%     |
| Toshiba             | 1        | 2      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| OCZ-AGIL            | 1        | 1      | 12.5%   |
| HGST                | 1        | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 903      | 2720   | 43.98%  |
| Works    | 830      | 2429   | 40.43%  |
| Malfunc  | 312      | 477    | 15.2%   |
| Failed   | 8        | 9      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1080     | 41.76%  |
| AMD                            | 593      | 22.93%  |
| Samsung Electronics            | 166      | 6.42%   |
| ASMedia Technology             | 103      | 3.98%   |
| JMicron Technology             | 96       | 3.71%   |
| Phison Electronics             | 72       | 2.78%   |
| Nvidia                         | 70       | 2.71%   |
| ADATA Technology               | 70       | 2.71%   |
| Kingston Technology Company    | 59       | 2.28%   |
| Marvell Technology Group       | 44       | 1.7%    |
| SanDisk                        | 41       | 1.59%   |
| Realtek Semiconductor          | 26       | 1.01%   |
| Silicon Motion                 | 25       | 0.97%   |
| Lite-On Technology             | 20       | 0.77%   |
| VIA Technologies               | 16       | 0.62%   |
| Micron/Crucial Technology      | 16       | 0.62%   |
| KIOXIA                         | 13       | 0.5%    |
| LSI Logic / Symbios Logic      | 12       | 0.46%   |
| SK hynix                       | 10       | 0.39%   |
| Shenzhen Longsys Electronics   | 10       | 0.39%   |
| Silicon Image                  | 7        | 0.27%   |
| Micron Technology              | 6        | 0.23%   |
| Toshiba America Info Systems   | 5        | 0.19%   |
| Hewlett-Packard                | 4        | 0.15%   |
| Broadcom / LSI                 | 4        | 0.15%   |
| INNOGRIT                       | 3        | 0.12%   |
| Union Memory (Shenzhen)        | 2        | 0.08%   |
| ULi Electronics                | 2        | 0.08%   |
| Solid State Storage Technology | 2        | 0.08%   |
| MAXIO Technology (Hangzhou)    | 2        | 0.08%   |
| Integrated Technology Express  | 2        | 0.08%   |
| Tekram Technology              | 1        | 0.04%   |
| Seagate Technology             | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor     | 1        | 0.04%   |
| Broadcom                       | 1        | 0.04%   |
| Adaptec                        | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 340      | 10.21%  |
| AMD 400 Series Chipset SATA Controller                                                  | 163      | 4.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 145      | 4.36%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 99       | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 98       | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 96       | 2.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 95       | 2.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 92       | 2.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 90       | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 78       | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 77       | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 71       | 2.13%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 68       | 2.04%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 65       | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 64       | 1.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 62       | 1.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 58       | 1.74%   |
| AMD 500 Series Chipset SATA Controller                                                  | 56       | 1.68%   |
| Intel SATA Controller [RAID mode]                                                       | 53       | 1.59%   |
| Phison E12 NVMe Controller                                                              | 40       | 1.2%    |
| Nvidia MCP61 SATA Controller                                                            | 37       | 1.11%   |
| Nvidia MCP61 IDE                                                                        | 36       | 1.08%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 35       | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 34       | 1.02%   |
| Samsung NVMe SSD Controller 980                                                         | 32       | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 29       | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 28       | 0.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 27       | 0.81%   |
| Kingston Company A2000 NVMe SSD                                                         | 26       | 0.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 26       | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                                  | 25       | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 24       | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 22       | 0.66%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 20       | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 19       | 0.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 19       | 0.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 19       | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18       | 0.54%   |
| JMicron JMB368 IDE controller                                                           | 18       | 0.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 18       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1376     | 54.37%  |
| IDE  | 543      | 21.45%  |
| NVMe | 494      | 19.52%  |
| RAID | 95       | 3.75%   |
| SAS  | 12       | 0.47%   |
| SCSI | 11       | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1091     | 62.02%  |
| AMD          | 666      | 37.86%  |
| PowerMac11,2 | 1        | 0.06%   |
| PowerBook6,7 | 1        | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 42       | 2.36%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 36       | 2.02%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 27       | 1.52%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 27       | 1.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 25       | 1.41%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 23       | 1.29%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 22       | 1.24%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 22       | 1.24%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 21       | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 20       | 1.12%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 19       | 1.07%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 1.01%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 16       | 0.9%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16       | 0.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 0.9%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 16       | 0.9%    |
| AMD Phenom II X4 955 Processor              | 16       | 0.9%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 15       | 0.84%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 15       | 0.84%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 14       | 0.79%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 13       | 0.73%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 13       | 0.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 12       | 0.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.62%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 11       | 0.62%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 11       | 0.62%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11       | 0.62%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 11       | 0.62%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 10       | 0.56%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 10       | 0.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 0.56%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 10       | 0.56%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 10       | 0.56%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 10       | 0.56%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 10       | 0.56%   |
| AMD FX-8350 Eight-Core Processor            | 10       | 0.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 9        | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9        | 0.51%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 9        | 0.51%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 9        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 338      | 19.06%  |
| Intel Core i7           | 183      | 10.32%  |
| AMD Ryzen 5             | 172      | 9.7%    |
| Intel Core i3           | 104      | 5.87%   |
| AMD Ryzen 7             | 98       | 5.53%   |
| Intel Xeon              | 94       | 5.3%    |
| Intel Core 2 Duo        | 84       | 4.74%   |
| Intel Core 2 Quad       | 65       | 3.67%   |
| AMD Ryzen 9             | 50       | 2.82%   |
| AMD FX                  | 49       | 2.76%   |
| Intel Pentium           | 44       | 2.48%   |
| Intel Celeron           | 42       | 2.37%   |
| Other                   | 40       | 2.26%   |
| AMD Phenom II X4        | 39       | 2.2%    |
| Intel Pentium Dual-Core | 33       | 1.86%   |
| AMD Athlon 64 X2        | 31       | 1.75%   |
| AMD Ryzen 3             | 29       | 1.64%   |
| AMD Athlon II X2        | 28       | 1.58%   |
| AMD A10                 | 21       | 1.18%   |
| Intel Core 2            | 20       | 1.13%   |
| AMD Athlon II X4        | 18       | 1.02%   |
| AMD A8                  | 18       | 1.02%   |
| Intel Pentium Dual      | 16       | 0.9%    |
| Intel Core i9           | 11       | 0.62%   |
| AMD Ryzen Threadripper  | 11       | 0.62%   |
| AMD A6                  | 11       | 0.62%   |
| AMD GX                  | 10       | 0.56%   |
| AMD Athlon              | 10       | 0.56%   |
| AMD Phenom II X6        | 8        | 0.45%   |
| Intel Pentium Gold      | 7        | 0.39%   |
| Intel Pentium D         | 7        | 0.39%   |
| Intel Pentium 4         | 7        | 0.39%   |
| AMD Athlon 64           | 7        | 0.39%   |
| AMD A4                  | 7        | 0.39%   |
| AMD Sempron             | 6        | 0.34%   |
| AMD Ryzen 5 PRO         | 6        | 0.34%   |
| AMD G                   | 6        | 0.34%   |
| AMD Athlon II X3        | 6        | 0.34%   |
| Intel Atom              | 5        | 0.28%   |
| AMD Phenom II X2        | 5        | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 712      | 39.93%  |
| 2       | 448      | 25.13%  |
| 6       | 275      | 15.42%  |
| 8       | 145      | 8.13%   |
| 12      | 56       | 3.14%   |
| Unknown | 45       | 2.52%   |
| 1       | 37       | 2.08%   |
| 16      | 23       | 1.29%   |
| 3       | 21       | 1.18%   |
| 10      | 10       | 0.56%   |
| 32      | 2        | 0.11%   |
| 24      | 2        | 0.11%   |
| 20      | 2        | 0.11%   |
| 14      | 2        | 0.11%   |
| 64      | 1        | 0.06%   |
| 44      | 1        | 0.06%   |
| 18      | 1        | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1734     | 98.52%  |
| 2      | 26       | 1.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 885      | 49.78%  |
| 2       | 848      | 47.69%  |
| Unknown | 45       | 2.53%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1741     | 98.7%   |
| Unknown        | 17       | 0.96%   |
| 32-bit         | 6        | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 414      | 22.31%  |
| 0x306c3    | 158      | 8.51%   |
| 0x1067a    | 108      | 5.82%   |
| 0x306a9    | 101      | 5.44%   |
| 0x206a7    | 80       | 4.31%   |
| 0x0800820d | 67       | 3.61%   |
| 0x506e3    | 63       | 3.39%   |
| 0x08701021 | 62       | 3.34%   |
| 0x010000c8 | 51       | 2.75%   |
| 0x906ea    | 47       | 2.53%   |
| 0x906e9    | 41       | 2.21%   |
| 0x6fb      | 27       | 1.45%   |
| 0x08701013 | 27       | 1.45%   |
| 0x06001119 | 26       | 1.4%    |
| 0xa0653    | 24       | 1.29%   |
| 0x10676    | 24       | 1.29%   |
| 0x06000852 | 23       | 1.24%   |
| 0x08001138 | 22       | 1.19%   |
| 0x6fd      | 19       | 1.02%   |
| 0x06003106 | 18       | 0.97%   |
| 0x106e5    | 16       | 0.86%   |
| 0x206c2    | 15       | 0.81%   |
| 0x10677    | 15       | 0.81%   |
| 0x6f6      | 14       | 0.75%   |
| 0x0a201016 | 13       | 0.7%    |
| 0x08101016 | 13       | 0.7%    |
| 0x08108109 | 12       | 0.65%   |
| 0x08001137 | 12       | 0.65%   |
| 0x010000db | 12       | 0.65%   |
| 0x306f2    | 11       | 0.59%   |
| 0x0a50000c | 11       | 0.59%   |
| 0x0a201009 | 11       | 0.59%   |
| 0xa0671    | 10       | 0.54%   |
| 0xa0655    | 10       | 0.54%   |
| 0x206d7    | 9        | 0.48%   |
| 0x0a20120a | 9        | 0.48%   |
| 0x906ed    | 8        | 0.43%   |
| 0x906ec    | 8        | 0.43%   |
| 0x90672    | 8        | 0.43%   |
| 0x306e4    | 8        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 205      | 11.56%  |
| Penryn           | 161      | 9.08%   |
| KabyLake         | 143      | 8.07%   |
| IvyBridge        | 127      | 7.16%   |
| Zen 2            | 120      | 6.77%   |
| K10              | 112      | 6.32%   |
| SandyBridge      | 107      | 6.03%   |
| Zen+             | 104      | 5.87%   |
| Skylake          | 86       | 4.85%   |
| Core             | 84       | 4.74%   |
| Zen              | 70       | 3.95%   |
| Piledriver       | 65       | 3.67%   |
| Zen 3            | 63       | 3.55%   |
| K8 Hammer        | 51       | 2.88%   |
| CometLake        | 42       | 2.37%   |
| Unknown          | 38       | 2.14%   |
| Nehalem          | 28       | 1.58%   |
| Westmere         | 26       | 1.47%   |
| Steamroller      | 19       | 1.07%   |
| NetBurst         | 17       | 0.96%   |
| Jaguar           | 15       | 0.85%   |
| Alderlake Hybrid | 14       | 0.79%   |
| Bulldozer        | 12       | 0.68%   |
| Silvermont       | 11       | 0.62%   |
| Bobcat           | 11       | 0.62%   |
| Icelake          | 10       | 0.56%   |
| K10 Llano        | 7        | 0.39%   |
| Goldmont plus    | 7        | 0.39%   |
| Broadwell        | 7        | 0.39%   |
| Goldmont         | 4        | 0.23%   |
| Excavator        | 3        | 0.17%   |
| Puma             | 2        | 0.11%   |
| P6               | 1        | 0.06%   |
| Bonnell          | 1        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 830      | 44.15%  |
| AMD                        | 579      | 30.8%   |
| Intel                      | 463      | 24.63%  |
| ASPEED Technology          | 5        | 0.27%   |
| Matrox Electronics Systems | 2        | 0.11%   |
| S3 Graphics                | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 103      | 5.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 96       | 4.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 55       | 2.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 45       | 2.3%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 43       | 2.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 42       | 2.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 42       | 2.15%   |
| Intel HD Graphics 530                                                       | 39       | 1.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 31       | 1.59%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 30       | 1.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 29       | 1.48%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 28       | 1.43%   |
| Nvidia GK208B [GeForce GT 710]                                              | 26       | 1.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 25       | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 24       | 1.23%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 22       | 1.13%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 22       | 1.13%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 22       | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 21       | 1.07%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 20       | 1.02%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 19       | 0.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 19       | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 18       | 0.92%   |
| Intel HD Graphics 630                                                       | 18       | 0.92%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 17       | 0.87%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 17       | 0.87%   |
| Nvidia GF108 [GeForce GT 630]                                               | 16       | 0.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 16       | 0.82%   |
| Nvidia GF119 [GeForce GT 610]                                               | 15       | 0.77%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 15       | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 14       | 0.72%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 14       | 0.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 14       | 0.72%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 13       | 0.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 13       | 0.66%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13       | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 12       | 0.61%   |
| Intel AlderLake-S GT1                                                       | 12       | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 11       | 0.56%   |
| AMD RS780L [Radeon 3000]                                                    | 11       | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 781      | 43.39%  |
| 1 x AMD         | 526      | 29.22%  |
| 1 x Intel       | 390      | 21.67%  |
| 2 x AMD         | 27       | 1.5%    |
| Intel + Nvidia  | 25       | 1.39%   |
| AMD + Nvidia    | 17       | 0.94%   |
| Intel + AMD     | 14       | 0.78%   |
| 2 x Nvidia      | 5        | 0.28%   |
| 2 x Intel       | 4        | 0.22%   |
| 1 x ASPEED      | 3        | 0.17%   |
| 3 x AMD         | 2        | 0.11%   |
| Nvidia + ASPEED | 2        | 0.11%   |
| 1 x Matrox      | 2        | 0.11%   |
| Other           | 1        | 0.06%   |
| 1 x S3 Graphics | 1        | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1291     | 70.97%  |
| Proprietary | 446      | 24.52%  |
| Unknown     | 82       | 4.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 652      | 34.88%  |
| 1.01-2.0   | 261      | 13.96%  |
| 0.51-1.0   | 253      | 13.54%  |
| 0.01-0.5   | 240      | 12.84%  |
| 7.01-8.0   | 171      | 9.15%   |
| 3.01-4.0   | 153      | 8.19%   |
| 5.01-6.0   | 77       | 4.12%   |
| 8.01-16.0  | 42       | 2.25%   |
| 2.01-3.0   | 14       | 0.75%   |
| 16.01-24.0 | 5        | 0.27%   |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 321      | 16.88%  |
| Goldstar             | 224      | 11.78%  |
| Dell                 | 186      | 9.78%   |
| Philips              | 132      | 6.94%   |
| Iiyama               | 121      | 6.36%   |
| Hewlett-Packard      | 105      | 5.52%   |
| BenQ                 | 101      | 5.31%   |
| Acer                 | 99       | 5.21%   |
| AOC                  | 80       | 4.21%   |
| Eizo                 | 65       | 3.42%   |
| NEC Computers        | 58       | 3.05%   |
| Ancor Communications | 50       | 2.63%   |
| LG Electronics       | 32       | 1.68%   |
| Sony                 | 30       | 1.58%   |
| Lenovo               | 30       | 1.58%   |
| Fujitsu Siemens      | 30       | 1.58%   |
| Unknown              | 20       | 1.05%   |
| Idek Iiyama          | 16       | 0.84%   |
| ASUSTek Computer     | 16       | 0.84%   |
| Gateway              | 11       | 0.58%   |
| ViewSonic            | 10       | 0.53%   |
| Belinea              | 10       | 0.53%   |
| Toshiba              | 9        | 0.47%   |
| MSI                  | 9        | 0.47%   |
| Gigabyte Technology  | 9        | 0.47%   |
| Panasonic            | 8        | 0.42%   |
| Medion               | 7        | 0.37%   |
| Hyundai ImageQuest   | 7        | 0.37%   |
| RTK                  | 5        | 0.26%   |
| IBM                  | 5        | 0.26%   |
| Arnos Instruments    | 5        | 0.26%   |
| Unknown              | 5        | 0.26%   |
| Vestel Elektronik    | 4        | 0.21%   |
| Hitachi              | 4        | 0.21%   |
| Xiaomi               | 3        | 0.16%   |
| Vestel               | 3        | 0.16%   |
| TCL                  | 3        | 0.16%   |
| Sharp                | 3        | 0.16%   |
| Plain Tree Systems   | 3        | 0.16%   |
| Onkyo                | 3        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 14       | 0.68%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                | 14       | 0.68%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 12       | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 11       | 0.54%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 9        | 0.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 9        | 0.44%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                   | 9        | 0.44%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                     | 9        | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 8        | 0.39%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 8        | 0.39%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 8        | 0.39%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 7        | 0.34%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch             | 7        | 0.34%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 7        | 0.34%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 6        | 0.29%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 6        | 0.29%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch             | 6        | 0.29%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch              | 6        | 0.29%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x287mm 23.0-inch         | 6        | 0.29%   |
| Eizo EV2316W ENC2394 1920x1080 510x287mm 23.0-inch                   | 6        | 0.29%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                    | 6        | 0.29%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch | 5        | 0.24%   |
| Iiyama PLX2483H IVM6114 1920x1080 531x299mm 24.0-inch                | 5        | 0.24%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                 | 5        | 0.24%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                | 5        | 0.24%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                 | 5        | 0.24%   |
| Eizo EV2316W ENC2393 1920x1080 510x287mm 23.0-inch                   | 5        | 0.24%   |
| Dell U2212HM DELD047 1920x1080 475x267mm 21.5-inch                   | 5        | 0.24%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 5        | 0.24%   |
| Acer VG270U P ACR06CF 2560x1440 597x336mm 27.0-inch                  | 5        | 0.24%   |
| Unknown                                                              | 5        | 0.24%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 4        | 0.19%   |
| Toshiba TV TSB0108 1360x768 930x523mm 42.0-inch                      | 4        | 0.19%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch | 4        | 0.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch | 4        | 0.19%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 477x268mm 21.5-inch    | 4        | 0.19%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                 | 4        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                    | 4        | 0.19%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch               | 4        | 0.19%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 4        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 827      | 44.49%  |
| 1280x1024 (SXGA)   | 199      | 10.7%   |
| 2560x1440 (QHD)    | 137      | 7.37%   |
| 1680x1050 (WSXGA+) | 126      | 6.78%   |
| 3840x2160 (4K)     | 123      | 6.62%   |
| 1920x1200 (WUXGA)  | 95       | 5.11%   |
| 1440x900 (WXGA+)   | 74       | 3.98%   |
| Unknown            | 41       | 2.21%   |
| 1366x768 (WXGA)    | 35       | 1.88%   |
| 3440x1440          | 29       | 1.56%   |
| 2560x1080          | 29       | 1.56%   |
| 1360x768           | 19       | 1.02%   |
| 1600x1200          | 18       | 0.97%   |
| 3840x1080          | 14       | 0.75%   |
| 1024x768 (XGA)     | 14       | 0.75%   |
| 1600x900 (HD+)     | 10       | 0.54%   |
| 1920x540           | 9        | 0.48%   |
| 2288x1287          | 6        | 0.32%   |
| 1280x720 (HD)      | 5        | 0.27%   |
| 5120x1440          | 4        | 0.22%   |
| 2048x1152          | 4        | 0.22%   |
| 3840x1200          | 3        | 0.16%   |
| 3200x1080          | 3        | 0.16%   |
| 2560x1600          | 3        | 0.16%   |
| 1280x960           | 3        | 0.16%   |
| 5760x1080          | 2        | 0.11%   |
| 4480x1440          | 2        | 0.11%   |
| 3600x1080          | 2        | 0.11%   |
| 1280x768           | 2        | 0.11%   |
| 7280x1440          | 1        | 0.05%   |
| 720x576            | 1        | 0.05%   |
| 720x480            | 1        | 0.05%   |
| 6880x1440          | 1        | 0.05%   |
| 6400x1440          | 1        | 0.05%   |
| 5760x1200          | 1        | 0.05%   |
| 5120x2160          | 1        | 0.05%   |
| 5120x1080          | 1        | 0.05%   |
| 5040x1050          | 1        | 0.05%   |
| 4920x1200          | 1        | 0.05%   |
| 4480x1600          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 281      | 14.87%  |
| 21      | 236      | 12.49%  |
| 23      | 232      | 12.28%  |
| 27      | 221      | 11.69%  |
| Unknown | 198      | 10.48%  |
| 19      | 160      | 8.47%   |
| 17      | 89       | 4.71%   |
| 22      | 83       | 4.39%   |
| 18      | 52       | 2.75%   |
| 34      | 48       | 2.54%   |
| 31      | 46       | 2.43%   |
| 20      | 36       | 1.9%    |
| 72      | 21       | 1.11%   |
| 84      | 19       | 1.01%   |
| 25      | 19       | 1.01%   |
| 15      | 18       | 0.95%   |
| 32      | 17       | 0.9%    |
| 54      | 14       | 0.74%   |
| 40      | 14       | 0.74%   |
| 46      | 8        | 0.42%   |
| 33      | 8        | 0.42%   |
| 65      | 7        | 0.37%   |
| 142     | 6        | 0.32%   |
| 42      | 6        | 0.32%   |
| 28      | 6        | 0.32%   |
| 47      | 4        | 0.21%   |
| 39      | 4        | 0.21%   |
| 26      | 4        | 0.21%   |
| 14      | 4        | 0.21%   |
| 55      | 3        | 0.16%   |
| 50      | 3        | 0.16%   |
| 49      | 3        | 0.16%   |
| 48      | 3        | 0.16%   |
| 43      | 3        | 0.16%   |
| 29      | 3        | 0.16%   |
| 37      | 2        | 0.11%   |
| 35      | 2        | 0.11%   |
| 12      | 2        | 0.11%   |
| 85      | 1        | 0.05%   |
| 59      | 1        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 699      | 38.03%  |
| 401-500        | 453      | 24.65%  |
| Unknown        | 198      | 10.77%  |
| 351-400        | 108      | 5.88%   |
| 301-350        | 105      | 5.71%   |
| 701-800        | 74       | 4.03%   |
| 601-700        | 71       | 3.86%   |
| 1001-1500      | 46       | 2.5%    |
| 1501-2000      | 41       | 2.23%   |
| 801-900        | 23       | 1.25%   |
| 901-1000       | 9        | 0.49%   |
| More than 2000 | 6        | 0.33%   |
| 201-300        | 5        | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1001     | 56.65%  |
| 16/10   | 279      | 15.79%  |
| 5/4     | 184      | 10.41%  |
| Unknown | 179      | 10.13%  |
| 21/9    | 53       | 3%      |
| 4/3     | 36       | 2.04%   |
| 3/2     | 18       | 1.02%   |
| 32/9    | 6        | 0.34%   |
| 1.00    | 6        | 0.34%   |
| 6/5     | 4        | 0.23%   |
| 0.56    | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 647      | 34.73%  |
| 151-200        | 260      | 13.96%  |
| 301-350        | 224      | 12.02%  |
| Unknown        | 198      | 10.63%  |
| 251-300        | 137      | 7.35%   |
| 351-500        | 127      | 6.82%   |
| 141-150        | 122      | 6.55%   |
| More than 1000 | 79       | 4.24%   |
| 501-1000       | 45       | 2.42%   |
| 101-110        | 14       | 0.75%   |
| 111-120        | 4        | 0.21%   |
| 91-100         | 3        | 0.16%   |
| 71-80          | 2        | 0.11%   |
| 81-90          | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1086     | 61.29%  |
| 101-120 | 342      | 19.3%   |
| Unknown | 198      | 11.17%  |
| 1-50    | 74       | 4.18%   |
| 121-160 | 49       | 2.77%   |
| 161-240 | 23       | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1424     | 78.94%  |
| 2     | 253      | 14.02%  |
| 0     | 84       | 4.66%   |
| 3     | 37       | 2.05%   |
| 4     | 6        | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1080     | 42.49%  |
| Intel                                  | 625      | 24.59%  |
| Qualcomm Atheros                       | 189      | 7.44%   |
| TP-Link                                | 83       | 3.27%   |
| Broadcom                               | 80       | 3.15%   |
| Ralink Technology                      | 54       | 2.12%   |
| Nvidia                                 | 52       | 2.05%   |
| Qualcomm Atheros Communications        | 42       | 1.65%   |
| Ralink                                 | 34       | 1.34%   |
| Microsoft                              | 29       | 1.14%   |
| Huawei Technologies                    | 28       | 1.1%    |
| Marvell Technology Group               | 25       | 0.98%   |
| MediaTek                               | 22       | 0.87%   |
| ASUSTek Computer                       | 21       | 0.83%   |
| Xiaomi                                 | 19       | 0.75%   |
| Broadcom Limited                       | 19       | 0.75%   |
| Samsung Electronics                    | 16       | 0.63%   |
| Aquantia                               | 12       | 0.47%   |
| Edimax Technology                      | 10       | 0.39%   |
| D-Link                                 | 9        | 0.35%   |
| VIA Technologies                       | 6        | 0.24%   |
| Motorola PCS                           | 6        | 0.24%   |
| Sony Ericsson Mobile Communications AB | 5        | 0.2%    |
| NetGear                                | 5        | 0.2%    |
| OPPO Electronics                       | 4        | 0.16%   |
| D-Link System                          | 4        | 0.16%   |
| Texas Instruments                      | 3        | 0.12%   |
| Sagem                                  | 3        | 0.12%   |
| HTC (High Tech Computer)               | 3        | 0.12%   |
| ZyXEL Communications                   | 2        | 0.08%   |
| ZyDAS                                  | 2        | 0.08%   |
| Seeed Technology                       | 2        | 0.08%   |
| Research In Motion                     | 2        | 0.08%   |
| QLogic                                 | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.08%   |
| NetXen Incorporated                    | 2        | 0.08%   |
| Loupedeck                              | 2        | 0.08%   |
| ICS Advent                             | 2        | 0.08%   |
| Belkin Components                      | 2        | 0.08%   |
| ASIX Electronics                       | 2        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 873      | 31.39%  |
| Intel I211 Gigabit Network Connection                             | 82       | 2.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78       | 2.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 72       | 2.59%   |
| Intel Ethernet Connection (2) I219-V                              | 63       | 2.27%   |
| Intel Wi-Fi 6 AX200                                               | 56       | 2.01%   |
| Intel Ethernet Connection I217-LM                                 | 40       | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40       | 1.44%   |
| Intel 82579V Gigabit Network Connection                           | 37       | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35       | 1.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 34       | 1.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 31       | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                   | 31       | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 31       | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 30       | 1.08%   |
| Ralink MT7601U Wireless Adapter                                   | 24       | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 24       | 0.86%   |
| Intel Wireless-AC 9260                                            | 23       | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22       | 0.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 21       | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 21       | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20       | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18       | 0.65%   |
| Microsoft Xbox 360 Wireless Adapter                               | 18       | 0.65%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.65%   |
| Intel Ethernet Connection I217-V                                  | 17       | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 16       | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15       | 0.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 15       | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 15       | 0.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 15       | 0.54%   |
| Ralink RT5370 Wireless Adapter                                    | 14       | 0.5%    |
| Ralink RT2561/RT61 802.11g PCI                                    | 14       | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14       | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14       | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14       | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13       | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12       | 0.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 170      | 22.08%  |
| Realtek Semiconductor           | 155      | 20.13%  |
| Qualcomm Atheros                | 91       | 11.82%  |
| TP-Link                         | 82       | 10.65%  |
| Ralink Technology               | 54       | 7.01%   |
| Qualcomm Atheros Communications | 42       | 5.45%   |
| Ralink                          | 34       | 4.42%   |
| Microsoft                       | 29       | 3.77%   |
| Broadcom                        | 25       | 3.25%   |
| MediaTek                        | 21       | 2.73%   |
| ASUSTek Computer                | 21       | 2.73%   |
| Edimax Technology               | 10       | 1.3%    |
| D-Link                          | 9        | 1.17%   |
| NetGear                         | 5        | 0.65%   |
| Sagem                           | 3        | 0.39%   |
| D-Link System                   | 3        | 0.39%   |
| ZyXEL Communications            | 2        | 0.26%   |
| ZyDAS                           | 2        | 0.26%   |
| Broadcom Limited                | 2        | 0.26%   |
| Belkin Components               | 2        | 0.26%   |
| Z-Com                           | 1        | 0.13%   |
| Wacom                           | 1        | 0.13%   |
| Ovislink                        | 1        | 0.13%   |
| Marvell Technology Group        | 1        | 0.13%   |
| Linksys                         | 1        | 0.13%   |
| IMC Networks                    | 1        | 0.13%   |
| AVM                             | 1        | 0.13%   |
| Accton Technology               | 1        | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 56       | 7.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 35       | 4.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 31       | 3.99%   |
| Qualcomm Atheros AR9271 802.11n                                               | 31       | 3.99%   |
| Ralink MT7601U Wireless Adapter                                               | 24       | 3.09%   |
| Intel Wireless-AC 9260                                                        | 23       | 2.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 22       | 2.83%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 21       | 2.7%    |
| Microsoft Xbox 360 Wireless Adapter                                           | 18       | 2.32%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 15       | 1.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 15       | 1.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 15       | 1.93%   |
| Ralink RT5370 Wireless Adapter                                                | 14       | 1.8%    |
| Ralink RT2561/RT61 802.11g PCI                                                | 14       | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 14       | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 14       | 1.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 12       | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 12       | 1.54%   |
| Realtek 802.11ac NIC                                                          | 11       | 1.42%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 11       | 1.42%   |
| Microsoft Xbox Wireless Adapter for Windows                                   | 11       | 1.42%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 10       | 1.29%   |
| Intel Wireless 7260                                                           | 10       | 1.29%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 9        | 1.16%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 8        | 1.03%   |
| TP-Link 802.11ac NIC                                                          | 8        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 8        | 1.03%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 8        | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 8        | 1.03%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 8        | 1.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 7        | 0.9%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 7        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 7        | 0.9%    |
| Intel Wireless 8260                                                           | 7        | 0.9%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 6        | 0.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 6        | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 6        | 0.77%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 6        | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 6        | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 6        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1010     | 52.91%  |
| Intel                                  | 539      | 28.23%  |
| Qualcomm Atheros                       | 105      | 5.5%    |
| Broadcom                               | 55       | 2.88%   |
| Nvidia                                 | 52       | 2.72%   |
| Marvell Technology Group               | 25       | 1.31%   |
| Xiaomi                                 | 19       | 1%      |
| Broadcom Limited                       | 17       | 0.89%   |
| Huawei Technologies                    | 16       | 0.84%   |
| Aquantia                               | 12       | 0.63%   |
| Samsung Electronics                    | 10       | 0.52%   |
| VIA Technologies                       | 6        | 0.31%   |
| Motorola PCS                           | 5        | 0.26%   |
| Sony Ericsson Mobile Communications AB | 4        | 0.21%   |
| OPPO Electronics                       | 4        | 0.21%   |
| HTC (High Tech Computer)               | 3        | 0.16%   |
| TP-Link                                | 2        | 0.1%    |
| Research In Motion                     | 2        | 0.1%    |
| QLogic                                 | 2        | 0.1%    |
| NetXen Incorporated                    | 2        | 0.1%    |
| ICS Advent                             | 2        | 0.1%    |
| ASIX Electronics                       | 2        | 0.1%    |
| Apple                                  | 2        | 0.1%    |
| 3Com                                   | 2        | 0.1%    |
| ZTE WCDMA Technologies MSM             | 1        | 0.05%   |
| Qualcomm                               | 1        | 0.05%   |
| Mellanox Technologies                  | 1        | 0.05%   |
| MediaTek                               | 1        | 0.05%   |
| Lenovo                                 | 1        | 0.05%   |
| Google                                 | 1        | 0.05%   |
| Foxconn / Hon Hai                      | 1        | 0.05%   |
| D-Link System                          | 1        | 0.05%   |
| American Megatrends                    | 1        | 0.05%   |
| AMD                                    | 1        | 0.05%   |
| ADMtek                                 | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 873      | 44.54%  |
| Intel I211 Gigabit Network Connection                             | 82       | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 78       | 3.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 72       | 3.67%   |
| Intel Ethernet Connection (2) I219-V                              | 63       | 3.21%   |
| Intel Ethernet Connection I217-LM                                 | 40       | 2.04%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40       | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 37       | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 34       | 1.73%   |
| Intel Ethernet Connection (7) I219-V                              | 31       | 1.58%   |
| Nvidia MCP61 Ethernet                                             | 30       | 1.53%   |
| Intel Ethernet Controller I225-V                                  | 24       | 1.22%   |
| Intel Ethernet Connection (2) I218-V                              | 21       | 1.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20       | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18       | 0.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 17       | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 16       | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15       | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14       | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13       | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12       | 0.61%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12       | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.61%   |
| Intel Ethernet Connection (14) I219-V                             | 11       | 0.56%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 11       | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.51%   |
| Huawei E353/E3131                                                 | 10       | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10       | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9        | 0.46%   |
| Nvidia MCP55 Ethernet                                             | 8        | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 8        | 0.41%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 7        | 0.36%   |
| Intel Ethernet Connection (7) I219-LM                             | 7        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1742     | 69.93%  |
| WiFi     | 710      | 28.5%   |
| Modem    | 33       | 1.32%   |
| Unknown  | 6        | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1387     | 77.27%  |
| WiFi     | 405      | 22.56%  |
| Modem    | 2        | 0.11%   |
| Unknown  | 1        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1249     | 70.21%  |
| 2     | 450      | 25.3%   |
| 3     | 53       | 2.98%   |
| 0     | 12       | 0.67%   |
| 4     | 6        | 0.34%   |
| 5     | 4        | 0.22%   |
| 6     | 2        | 0.11%   |
| 17    | 1        | 0.06%   |
| 9     | 1        | 0.06%   |
| 7     | 1        | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1656     | 93.51%  |
| Yes  | 115      | 6.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 159      | 33.83%  |
| Cambridge Silicon Radio         | 154      | 32.77%  |
| ASUSTek Computer                | 65       | 13.83%  |
| Broadcom                        | 17       | 3.62%   |
| Realtek Semiconductor           | 15       | 3.19%   |
| Qualcomm Atheros Communications | 12       | 2.55%   |
| TP-Link                         | 10       | 2.13%   |
| MediaTek                        | 8        | 1.7%    |
| Integrated System Solution      | 4        | 0.85%   |
| Edimax Technology               | 4        | 0.85%   |
| Apple                           | 4        | 0.85%   |
| IMC Networks                    | 3        | 0.64%   |
| Foxconn / Hon Hai               | 3        | 0.64%   |
| Conwise Technology              | 3        | 0.64%   |
| Realtek                         | 2        | 0.43%   |
| Lite-On Technology              | 2        | 0.43%   |
| Unknown                         | 2        | 0.43%   |
| SINO WEALTH                     | 1        | 0.21%   |
| Logitech                        | 1        | 0.21%   |
| Belkin Components               | 1        | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 154      | 32.63%  |
| Intel AX200 Bluetooth                                 | 55       | 11.65%  |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 46       | 9.75%   |
| Intel Bluetooth wireless interface                    | 23       | 4.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 21       | 4.45%   |
| Intel Wireless-AC 3168 Bluetooth                      | 21       | 4.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 17       | 3.6%    |
| Realtek Bluetooth Radio                               | 14       | 2.97%   |
| Intel AX210 Bluetooth                                 | 12       | 2.54%   |
| TP-Link UB500 Adapter                                 | 10       | 2.12%   |
| ASUS ASUS USB-BT500                                   | 10       | 2.12%   |
| Intel AX201 Bluetooth                                 | 9        | 1.91%   |
| MediaTek Wireless_Device                              | 8        | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 7        | 1.48%   |
| Broadcom HP Portable Bumble Bee                       | 4        | 0.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 0.85%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.64%   |
| Foxconn / Hon Hai Wireless_Device                     | 3        | 0.64%   |
| Conwise CW6622                                        | 3        | 0.64%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 3        | 0.64%   |
| Broadcom BCM2045 Bluetooth                            | 3        | 0.64%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3        | 0.64%   |
| Realtek Bluetooth Radio                               | 2        | 0.42%   |
| IMC Networks Wireless_Device                          | 2        | 0.42%   |
| Edimax Bluetooth Adapter                              | 2        | 0.42%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.42%   |
| ASUS Bluetooth Radio                                  | 2        | 0.42%   |
| ASUS BCM20702A0                                       | 2        | 0.42%   |
| Unknown                                               | 2        | 0.42%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.21%   |
| Realtek RTL8821A Bluetooth                            | 1        | 0.21%   |
| Qualcomm Atheros  Bluetooth Device                    | 1        | 0.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.21%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 0.21%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1        | 0.21%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 0.21%   |
| Lite-On Bluetooth Radio                               | 1        | 0.21%   |
| Lite-On Bluetooth Device                              | 1        | 0.21%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 1035     | 34.45%  |
| AMD                                  | 789      | 26.26%  |
| Nvidia                               | 737      | 24.53%  |
| Creative Labs                        | 85       | 2.83%   |
| C-Media Electronics                  | 73       | 2.43%   |
| Creative Technology                  | 30       | 1%      |
| JMTek                                | 18       | 0.6%    |
| VIA Technologies                     | 15       | 0.5%    |
| Logitech                             | 15       | 0.5%    |
| Texas Instruments                    | 14       | 0.47%   |
| Kingston Technology                  | 13       | 0.43%   |
| GYROCOM C&C                          | 11       | 0.37%   |
| SteelSeries ApS                      | 9        | 0.3%    |
| Realtek Semiconductor                | 9        | 0.3%    |
| SAVITECH                             | 7        | 0.23%   |
| ASUSTek Computer                     | 7        | 0.23%   |
| Razer USA                            | 6        | 0.2%    |
| Plantronics                          | 6        | 0.2%    |
| Generalplus Technology               | 6        | 0.2%    |
| Dell                                 | 6        | 0.2%    |
| BEHRINGER International              | 5        | 0.17%   |
| Valve Software                       | 4        | 0.13%   |
| Trust                                | 4        | 0.13%   |
| Sony                                 | 4        | 0.13%   |
| AOKEO                                | 4        | 0.13%   |
| USB MICROPHONE                       | 3        | 0.1%    |
| Samson Technologies                  | 3        | 0.1%    |
| RODE Microphones                     | 3        | 0.1%    |
| ROCCAT                               | 3        | 0.1%    |
| PreSonus Audio Electronics           | 3        | 0.1%    |
| Micro Star International             | 3        | 0.1%    |
| M-Audio                              | 3        | 0.1%    |
| GN Netcom                            | 3        | 0.1%    |
| Focusrite-Novation                   | 3        | 0.1%    |
| Corsair                              | 3        | 0.1%    |
| AudioQuest                           | 3        | 0.1%    |
| XMOS                                 | 2        | 0.07%   |
| ULi Electronics                      | 2        | 0.07%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.07%   |
| SM900T Microphone                    | 2        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 161      | 4.62%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 146      | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 143      | 4.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 124      | 3.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 108      | 3.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 106      | 3.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 104      | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 103      | 2.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 94       | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 93       | 2.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 71       | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 71       | 2.04%   |
| AMD FCH Azalia Controller                                                  | 68       | 1.95%   |
| Intel 200 Series PCH HD Audio                                              | 67       | 1.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 66       | 1.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 61       | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 61       | 1.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 51       | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 47       | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 45       | 1.29%   |
| Nvidia High Definition Audio Controller                                    | 42       | 1.21%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 42       | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                              | 42       | 1.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 41       | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 40       | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                         | 36       | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 36       | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36       | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 36       | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 35       | 1%      |
| Nvidia MCP61 High Definition Audio                                         | 33       | 0.95%   |
| AMD Navi 10 HDMI Audio                                                     | 31       | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 30       | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                              | 29       | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 27       | 0.77%   |
| Nvidia GM204 High Definition Audio Controller                              | 26       | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                         | 24       | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 24       | 0.69%   |
| Nvidia TU104 HD Audio Controller                                           | 23       | 0.66%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 22       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 239      | 19.48%  |
| Kingston                     | 233      | 18.99%  |
| Samsung Electronics          | 105      | 8.56%   |
| Goodram                      | 103      | 8.39%   |
| SK hynix                     | 98       | 7.99%   |
| G.Skill                      | 96       | 7.82%   |
| Corsair                      | 76       | 6.19%   |
| Crucial                      | 68       | 5.54%   |
| Patriot                      | 35       | 2.85%   |
| Micron Technology            | 34       | 2.77%   |
| A-DATA Technology            | 27       | 2.2%    |
| Nanya Technology             | 16       | 1.3%    |
| Elpida                       | 12       | 0.98%   |
| Unknown                      | 10       | 0.81%   |
| Wilk Elektronik              | 9        | 0.73%   |
| GeIL                         | 9        | 0.73%   |
| Apacer                       | 9        | 0.73%   |
| Wilk                         | 7        | 0.57%   |
| Unknown (ABCD)               | 5        | 0.41%   |
| Ramaxel Technology           | 4        | 0.33%   |
| Team                         | 3        | 0.24%   |
| Silicon Power                | 3        | 0.24%   |
| Qimonda                      | 3        | 0.24%   |
| OCZ                          | 3        | 0.24%   |
| Patriot Memory (PDP Systems) | 2        | 0.16%   |
| ASint Technology             | 2        | 0.16%   |
| AMD                          | 2        | 0.16%   |
| Unknown (0x7FFF)             | 1        | 0.08%   |
| Unifosa                      | 1        | 0.08%   |
| Transcend                    | 1        | 0.08%   |
| Toshiba                      | 1        | 0.08%   |
| tigo                         | 1        | 0.08%   |
| PNY                          | 1        | 0.08%   |
| Lexar                        | 1        | 0.08%   |
| Kingmax                      | 1        | 0.08%   |
| KingFast                     | 1        | 0.08%   |
| ISD Technology Limited       | 1        | 0.08%   |
| Golden Empire                | 1        | 0.08%   |
| Aeneon                       | 1        | 0.08%   |
| A Force                      | 1        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s  | 19       | 1.36%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 18       | 1.29%   |
| Patriot RAM 3200 C16 Series 8192MB DIMM DDR4 3266MT/s  | 16       | 1.15%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 13       | 0.93%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 13       | 0.93%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 13       | 0.93%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 13       | 0.93%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 12       | 0.86%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 12       | 0.86%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s     | 12       | 0.86%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 12       | 0.86%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 11       | 0.79%   |
| GOODRAM RAM GR1600D364L11/8G 8GB DIMM DDR3 1600MT/s    | 10       | 0.72%   |
| Unknown                                                | 10       | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 9        | 0.65%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 9        | 0.65%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 8        | 0.57%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 8        | 0.57%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 8        | 0.57%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 8        | 0.57%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s    | 8        | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 7        | 0.5%    |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 7        | 0.5%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 7        | 0.5%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s | 7        | 0.5%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 7        | 0.5%    |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s    | 7        | 0.5%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s  | 7        | 0.5%    |
| GOODRAM RAM IRX3000D464L16S/8G 8GB DIMM DDR4 3333MT/s  | 7        | 0.5%    |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 6        | 0.43%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 6        | 0.43%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 6        | 0.43%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 6        | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 6        | 0.43%   |
| GOODRAM RAM IR2400D464L15S/8G 8GB DIMM DDR4 3200MT/s   | 6        | 0.43%   |
| GOODRAM RAM IR2400D464L15S/4G 4GB DIMM DDR4 2866MT/s   | 6        | 0.43%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s  | 6        | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 5        | 0.36%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 5        | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 5        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 437      | 40.02%  |
| DDR3    | 359      | 32.88%  |
| Unknown | 128      | 11.72%  |
| DDR2    | 72       | 6.59%   |
| SDRAM   | 58       | 5.31%   |
| DDR     | 21       | 1.92%   |
| DDR5    | 11       | 1.01%   |
| LPDDR4  | 5        | 0.46%   |
| DRAM    | 1        | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1023     | 95.34%  |
| SODIMM  | 47       | 4.38%   |
| RIMM    | 2        | 0.19%   |
| FB-DIMM | 1        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 380      | 31.38%  |
| 4096   | 282      | 23.29%  |
| 2048   | 233      | 19.24%  |
| 16384  | 146      | 12.06%  |
| 1024   | 88       | 7.27%   |
| 32768  | 61       | 5.04%   |
| 512    | 17       | 1.4%    |
| 131072 | 1        | 0.08%   |
| 1536   | 1        | 0.08%   |
| 256    | 1        | 0.08%   |
| 64     | 1        | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 217      | 17.92%  |
| 1333    | 132      | 10.9%   |
| 3200    | 102      | 8.42%   |
| 800     | 86       | 7.1%    |
| 3600    | 78       | 6.44%   |
| 2400    | 69       | 5.7%    |
| 2667    | 49       | 4.05%   |
| 667     | 49       | 4.05%   |
| 2133    | 39       | 3.22%   |
| 3000    | 25       | 2.06%   |
| Unknown | 25       | 2.06%   |
| 1867    | 23       | 1.9%    |
| 1800    | 20       | 1.65%   |
| 3400    | 19       | 1.57%   |
| 3266    | 19       | 1.57%   |
| 1866    | 19       | 1.57%   |
| 2933    | 16       | 1.32%   |
| 1067    | 16       | 1.32%   |
| 400     | 16       | 1.32%   |
| 3866    | 15       | 1.24%   |
| 1066    | 15       | 1.24%   |
| 3533    | 11       | 0.91%   |
| 3333    | 10       | 0.83%   |
| 2666    | 10       | 0.83%   |
| 3800    | 9        | 0.74%   |
| 3733    | 9        | 0.74%   |
| 1334    | 9        | 0.74%   |
| 533     | 9        | 0.74%   |
| 3933    | 7        | 0.58%   |
| 2866    | 7        | 0.58%   |
| 3466    | 6        | 0.5%    |
| 333     | 6        | 0.5%    |
| 49926   | 5        | 0.41%   |
| 4800    | 5        | 0.41%   |
| 2800    | 5        | 0.41%   |
| 2000    | 4        | 0.33%   |
| 1648    | 4        | 0.33%   |
| 6000    | 3        | 0.25%   |
| 3334    | 3        | 0.25%   |
| 2200    | 3        | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 37       | 45.68%  |
| Brother Industries    | 11       | 13.58%  |
| Samsung Electronics   | 10       | 12.35%  |
| Canon                 | 6        | 7.41%   |
| Prolific Technology   | 5        | 6.17%   |
| Seiko Epson           | 4        | 4.94%   |
| Lexmark International | 3        | 3.7%    |
| Zebra                 | 2        | 2.47%   |
| Xerox                 | 1        | 1.23%   |
| Minolta               | 1        | 1.23%   |
| Datamax-O'Neil        | 1        | 1.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port          | 5        | 6.02%   |
| HP LaserJet 1020                       | 4        | 4.82%   |
| HP LaserJet P2015 series               | 3        | 3.61%   |
| Canon iP7200 series                    | 3        | 3.61%   |
| Samsung ML-216x Series Laser Printer   | 2        | 2.41%   |
| Samsung ML-2010P Mono Laser Printer    | 2        | 2.41%   |
| HP LaserJet M14-M17                    | 2        | 2.41%   |
| HP Deskjet F4500 series                | 2        | 2.41%   |
| HP DeskJet F4100 Printer series        | 2        | 2.41%   |
| HP DeskJet 845c                        | 2        | 2.41%   |
| HP DeskJet 840c                        | 2        | 2.41%   |
| HP DeskJet 3700 series                 | 2        | 2.41%   |
| HP Deskjet 1050 J410                   | 2        | 2.41%   |
| Brother DCP-J105                       | 2        | 2.41%   |
| Zebra LP2844 Printer                   | 1        | 1.2%    |
| Zebra LP2824                           | 1        | 1.2%    |
| Xerox WorkCentre PE16                  | 1        | 1.2%    |
| Seiko Epson Stylus NX230/SX235W Series | 1        | 1.2%    |
| Seiko Epson L405 Series                | 1        | 1.2%    |
| Seiko Epson L1110 Series               | 1        | 1.2%    |
| Seiko Epson ET-2710 Series             | 1        | 1.2%    |
| Samsung SCX-4300 Series                | 1        | 1.2%    |
| Samsung SCX-4200 series                | 1        | 1.2%    |
| Samsung SCX-3400 Series                | 1        | 1.2%    |
| Samsung ML-3050/ML-3051 Laser Printer  | 1        | 1.2%    |
| Samsung ML-2540 Series Laser Printer   | 1        | 1.2%    |
| Samsung M2020 Series                   | 1        | 1.2%    |
| Minolta PagePro 1200W                  | 1        | 1.2%    |
| Lexmark International MS415dn          | 1        | 1.2%    |
| Lexmark International Lexmark E352dn   | 1        | 1.2%    |
| Lexmark International B2236dw          | 1        | 1.2%    |
| HP Smart Tank 510 series               | 1        | 1.2%    |
| HP PSC 1100 series                     | 1        | 1.2%    |
| HP Printing Support                    | 1        | 1.2%    |
| HP LaserJet P1102                      | 1        | 1.2%    |
| HP LaserJet M101-M106                  | 1        | 1.2%    |
| HP LaserJet CM1415fn                   | 1        | 1.2%    |
| HP LaserJet 3030                       | 1        | 1.2%    |
| HP LaserJet 1320                       | 1        | 1.2%    |
| HP LaserJet 1022                       | 1        | 1.2%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 10       | 62.5%   |
| Seiko Epson                 | 2        | 12.5%   |
| Ultima Electronics          | 1        | 6.25%   |
| Plustek                     | 1        | 6.25%   |
| Mustek Systems              | 1        | 6.25%   |
| Acer Peripherals (now BenQ) | 1        | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 5        | 31.25%  |
| Canon CanoScan LiDE 120                                  | 2        | 12.5%   |
| Ultima Artec E+ 48U                                      | 1        | 6.25%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1        | 6.25%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 6.25%   |
| Plustek OpticPro 1248U Scanner #2                        | 1        | 6.25%   |
| Mustek Systems BearPaw 2448 TA Pro                       | 1        | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 6.25%   |
| Canon CanoScan LIDE 25                                   | 1        | 6.25%   |
| Canon CanoScan LiDE 110                                  | 1        | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 78       | 33.48%  |
| Microdia                               | 25       | 10.73%  |
| Creative Technology                    | 25       | 10.73%  |
| Microsoft                              | 14       | 6.01%   |
| Samsung Electronics                    | 12       | 5.15%   |
| Z-Star Microelectronics                | 8        | 3.43%   |
| Hewlett-Packard                        | 6        | 2.58%   |
| Cubeternet                             | 6        | 2.58%   |
| Jieli Technology                       | 4        | 1.72%   |
| Generalplus Technology                 | 4        | 1.72%   |
| Aveo Technology                        | 4        | 1.72%   |
| Xiongmai                               | 3        | 1.29%   |
| Sunplus Innovation Technology          | 3        | 1.29%   |
| Razer USA                              | 3        | 1.29%   |
| GEMBIRD                                | 3        | 1.29%   |
| Chicony Electronics                    | 3        | 1.29%   |
| Apple                                  | 3        | 1.29%   |
| Alcor Micro                            | 3        | 1.29%   |
| Valve Software                         | 2        | 0.86%   |
| Trust                                  | 2        | 0.86%   |
| Realtek Semiconductor                  | 2        | 0.86%   |
| Pixart Imaging                         | 2        | 0.86%   |
| LG Electronics                         | 2        | 0.86%   |
| KYE Systems (Mouse Systems)            | 2        | 0.86%   |
| ARC International                      | 2        | 0.86%   |
| USB3.0 HD Audio Capture                | 1        | 0.43%   |
| MacroSilicon                           | 1        | 0.43%   |
| Lenovo                                 | 1        | 0.43%   |
| Huawei Technologies                    | 1        | 0.43%   |
| HRY                                    | 1        | 0.43%   |
| Google                                 | 1        | 0.43%   |
| Etron Technology                       | 1        | 0.43%   |
| DigitalPersona                         | 1        | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.43%   |
| Asuscom Network                        | 1        | 0.43%   |
| Arkmicro Technologies                  | 1        | 0.43%   |
| Unknown                                | 1        | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 18       | 7.69%   |
| Creative Live! Cam Sync HD [VF0770]               | 13       | 5.56%   |
| Samsung Galaxy series, misc. (MTP mode)           | 11       | 4.7%    |
| Logitech HD Pro Webcam C920                       | 11       | 4.7%    |
| Microdia Front camera                             | 9        | 3.85%   |
| Logitech Webcam C310                              | 9        | 3.85%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 2.56%   |
| Logitech Webcam C170                              | 6        | 2.56%   |
| Microsoft LifeCam HD-3000                         | 5        | 2.14%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 1.71%   |
| Microdia Integrated Camera                        | 4        | 1.71%   |
| Jieli USB PHY 2.0                                 | 4        | 1.71%   |
| HP Webcam HD 2300                                 | 4        | 1.71%   |
| Generalplus GENERAL WEBCAM                        | 4        | 1.71%   |
| Cubeternet USB2.0 Camera                          | 4        | 1.71%   |
| Xiongmai web camera                               | 3        | 1.28%   |
| Razer USA Gaming Webcam [Kiyo]                    | 3        | 1.28%   |
| Microdia Webcam Vitade AF                         | 3        | 1.28%   |
| Logitech Webcam C930e                             | 3        | 1.28%   |
| Logitech Webcam C120                              | 3        | 1.28%   |
| Logitech C922 Pro Stream Webcam                   | 3        | 1.28%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 1.28%   |
| Creative Live! Cam Sync 1080p                     | 3        | 1.28%   |
| Creative Live! Cam Optia                          | 3        | 1.28%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 3        | 1.28%   |
| Aveo USB2.0 Camera                                | 3        | 1.28%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 3        | 1.28%   |
| Valve Software 3D Camera                          | 2        | 0.85%   |
| Sunplus HD 720P webcam                            | 2        | 0.85%   |
| Pixart Imaging USB2.0_Camera                      | 2        | 0.85%   |
| Microsoft LifeCam VX-500 [1357]                   | 2        | 0.85%   |
| Microsoft LifeCam NX-6000                         | 2        | 0.85%   |
| Microsoft LifeCam HD-5000                         | 2        | 0.85%   |
| Microdia USB 2.0 Camera                           | 2        | 0.85%   |
| Microdia Camera                                   | 2        | 0.85%   |
| Logitech StreamCam                                | 2        | 0.85%   |
| Logitech QuickCam Pro 9000                        | 2        | 0.85%   |
| Logitech Logitech Webcam C100                     | 2        | 0.85%   |
| Logitech HD Webcam C510                           | 2        | 0.85%   |
| Logitech C920 PRO HD Webcam                       | 2        | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 40%     |
| STMicroelectronics    | 1        | 20%     |
| Elan Microelectronics | 1        | 20%     |
| AuthenTec             | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 40%     |
| STMicroelectronics Fingerprint Reader        | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 20%     |
| AuthenTec AES1600                            | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Advanced Card Systems    | 3        | 27.27%  |
| OmniKey                  | 2        | 18.18%  |
| SCM Microsystems         | 1        | 9.09%   |
| Reiner SCT Kartensysteme | 1        | 9.09%   |
| Gemalto (was Gemplus)    | 1        | 9.09%   |
| Clay Logic               | 1        | 9.09%   |
| Cherry                   | 1        | 9.09%   |
| Alcor Micro              | 1        | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                                                | 2        | 18.18%  |
| Advanced Card Systems ACR39U                                               | 2        | 18.18%  |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 9.09%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 9.09%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 9.09%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 9.09%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 9.09%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 9.09%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1536     | 84.82%  |
| 1     | 234      | 12.92%  |
| 2     | 31       | 1.71%   |
| 3     | 5        | 0.28%   |
| 4     | 3        | 0.17%   |
| 7     | 1        | 0.06%   |
| 6     | 1        | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 116      | 37.42%  |
| Net/wireless             | 67       | 21.61%  |
| Unassigned class         | 24       | 7.74%   |
| Communication controller | 24       | 7.74%   |
| Multimedia controller    | 13       | 4.19%   |
| Sound                    | 11       | 3.55%   |
| Bluetooth                | 9        | 2.9%    |
| Camera                   | 7        | 2.26%   |
| Network                  | 6        | 1.94%   |
| Storage/ide              | 5        | 1.61%   |
| Net/ethernet             | 5        | 1.61%   |
| Fingerprint reader       | 5        | 1.61%   |
| Chipcard                 | 5        | 1.61%   |
| Storage/raid             | 3        | 0.97%   |
| Firewire controller      | 3        | 0.97%   |
| Dvb card                 | 3        | 0.97%   |
| Storage                  | 2        | 0.65%   |
| Modem                    | 2        | 0.65%   |

