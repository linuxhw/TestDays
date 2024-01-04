Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 10921

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15-3567            | Notebook    | [50d926ec76](https://linux-hardware.org/?probe=50d926ec76) | Jan 02, 2024 |
| Acidanther... | MacBookPro16,4              | Notebook    | [3c8c520472](https://linux-hardware.org/?probe=3c8c520472) | Jan 02, 2024 |
| Google        | Blooguard                   | Notebook    | [dc6c0354a9](https://linux-hardware.org/?probe=dc6c0354a9) | Jan 02, 2024 |
| Dell          | 0C2XKD A01                  | Desktop     | [9accd399c5](https://linux-hardware.org/?probe=9accd399c5) | Jan 02, 2024 |
| Philco        | 14M2                        | Notebook    | [b5771423fb](https://linux-hardware.org/?probe=b5771423fb) | Jan 02, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [04753e77e0](https://linux-hardware.org/?probe=04753e77e0) | Jan 02, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [68d3d8c6be](https://linux-hardware.org/?probe=68d3d8c6be) | Jan 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | Notebook    | [6ea14ec02e](https://linux-hardware.org/?probe=6ea14ec02e) | Jan 01, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f8dd732e7a](https://linux-hardware.org/?probe=f8dd732e7a) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [8a14ad7cc9](https://linux-hardware.org/?probe=8a14ad7cc9) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [a2acc5bb5f](https://linux-hardware.org/?probe=a2acc5bb5f) | Jan 01, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [67ef36b749](https://linux-hardware.org/?probe=67ef36b749) | Jan 01, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [494b496889](https://linux-hardware.org/?probe=494b496889) | Jan 01, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7cb99217f7](https://linux-hardware.org/?probe=7cb99217f7) | Jan 01, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1934632c28](https://linux-hardware.org/?probe=1934632c28) | Jan 01, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7df50c6495](https://linux-hardware.org/?probe=7df50c6495) | Jan 01, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [488deac73a](https://linux-hardware.org/?probe=488deac73a) | Jan 01, 2024 |
| Dell          | Latitude 7420               | Notebook    | [a32d08979b](https://linux-hardware.org/?probe=a32d08979b) | Dec 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [390160b8e5](https://linux-hardware.org/?probe=390160b8e5) | Dec 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [9bee55a186](https://linux-hardware.org/?probe=9bee55a186) | Dec 31, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [6eee51a63f](https://linux-hardware.org/?probe=6eee51a63f) | Dec 31, 2023 |
| ASRock        | H61M-VG4                    | Desktop     | [1c5959e766](https://linux-hardware.org/?probe=1c5959e766) | Dec 31, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [a68ce92fec](https://linux-hardware.org/?probe=a68ce92fec) | Dec 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [577f6b15de](https://linux-hardware.org/?probe=577f6b15de) | Dec 31, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [7adc50aeab](https://linux-hardware.org/?probe=7adc50aeab) | Dec 31, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [f160a53f1b](https://linux-hardware.org/?probe=f160a53f1b) | Dec 31, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [34fcef3266](https://linux-hardware.org/?probe=34fcef3266) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | Notebook    | [7130d1a699](https://linux-hardware.org/?probe=7130d1a699) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | Notebook    | [d04c4d749f](https://linux-hardware.org/?probe=d04c4d749f) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [815e8736a2](https://linux-hardware.org/?probe=815e8736a2) | Dec 31, 2023 |
| ASRock        | B760M PG SONIC WiFi         | Desktop     | [a066542ba9](https://linux-hardware.org/?probe=a066542ba9) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [4dd47839a4](https://linux-hardware.org/?probe=4dd47839a4) | Dec 31, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [451e3803a0](https://linux-hardware.org/?probe=451e3803a0) | Dec 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5d1ed5c106](https://linux-hardware.org/?probe=5d1ed5c106) | Dec 30, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [cfec230076](https://linux-hardware.org/?probe=cfec230076) | Dec 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [ff8e890649](https://linux-hardware.org/?probe=ff8e890649) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [460fe0575c](https://linux-hardware.org/?probe=460fe0575c) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [e45829bd8b](https://linux-hardware.org/?probe=e45829bd8b) | Dec 30, 2023 |
| HP            | 18E7                        | Desktop     | [f5115e035f](https://linux-hardware.org/?probe=f5115e035f) | Dec 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [24ca756f75](https://linux-hardware.org/?probe=24ca756f75) | Dec 30, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [85ac43fbee](https://linux-hardware.org/?probe=85ac43fbee) | Dec 29, 2023 |
| Unknown       | X99                         | Desktop     | [cc4f5ea8e5](https://linux-hardware.org/?probe=cc4f5ea8e5) | Dec 29, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [a9dd36da25](https://linux-hardware.org/?probe=a9dd36da25) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [36856f5ac1](https://linux-hardware.org/?probe=36856f5ac1) | Dec 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [42c812d36d](https://linux-hardware.org/?probe=42c812d36d) | Dec 29, 2023 |
| Monster       | TULPAR T5 V23.2             | Notebook    | [9592c22858](https://linux-hardware.org/?probe=9592c22858) | Dec 29, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [fa779d28cc](https://linux-hardware.org/?probe=fa779d28cc) | Dec 28, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [66f68b08bd](https://linux-hardware.org/?probe=66f68b08bd) | Dec 28, 2023 |
| Samsung       | 750QFG                      | Convertible | [e9c0f18533](https://linux-hardware.org/?probe=e9c0f18533) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [159d5b2ef2](https://linux-hardware.org/?probe=159d5b2ef2) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [42c62dac0e](https://linux-hardware.org/?probe=42c62dac0e) | Dec 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [006255c8c9](https://linux-hardware.org/?probe=006255c8c9) | Dec 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [a97c12a4c8](https://linux-hardware.org/?probe=a97c12a4c8) | Dec 28, 2023 |
| HP            | OMEN Laptop 15-ek1xxx       | Notebook    | [16c7cb0337](https://linux-hardware.org/?probe=16c7cb0337) | Dec 28, 2023 |
| Acer          | G31T-M5                     | Desktop     | [1b0e1c5154](https://linux-hardware.org/?probe=1b0e1c5154) | Dec 28, 2023 |
| TrekStor      | Notebook Slim S130          | Notebook    | [9fbe38b102](https://linux-hardware.org/?probe=9fbe38b102) | Dec 28, 2023 |
| Razer         | Blade                       | Notebook    | [bd2101718d](https://linux-hardware.org/?probe=bd2101718d) | Dec 28, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [a353ad122c](https://linux-hardware.org/?probe=a353ad122c) | Dec 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [8c5f1e135b](https://linux-hardware.org/?probe=8c5f1e135b) | Dec 28, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [cb6bd15ff8](https://linux-hardware.org/?probe=cb6bd15ff8) | Dec 27, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [3a105d883b](https://linux-hardware.org/?probe=3a105d883b) | Dec 27, 2023 |
| HP            | 2AFB                        | Desktop     | [5279d471aa](https://linux-hardware.org/?probe=5279d471aa) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [a81c208684](https://linux-hardware.org/?probe=a81c208684) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c56c8e1bcf](https://linux-hardware.org/?probe=c56c8e1bcf) | Dec 27, 2023 |
| TUXEDO        | Pulse 14 Gen3               | Notebook    | [7873276f27](https://linux-hardware.org/?probe=7873276f27) | Dec 27, 2023 |
| ASUSTek       | X75A                        | Notebook    | [a7b35ca7c8](https://linux-hardware.org/?probe=a7b35ca7c8) | Dec 27, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [cecd63878b](https://linux-hardware.org/?probe=cecd63878b) | Dec 27, 2023 |
| Lenovo        | IdeaPad S740-15IRH Touch... | Notebook    | [6584c1853d](https://linux-hardware.org/?probe=6584c1853d) | Dec 27, 2023 |
| Samsung       | 750QFG                      | Convertible | [45790ba256](https://linux-hardware.org/?probe=45790ba256) | Dec 27, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [906642b6ec](https://linux-hardware.org/?probe=906642b6ec) | Dec 27, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [c1d9037478](https://linux-hardware.org/?probe=c1d9037478) | Dec 27, 2023 |
| Biostar       | H61MHV3                     | Desktop     | [f03f05706c](https://linux-hardware.org/?probe=f03f05706c) | Dec 26, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [98aaf575cc](https://linux-hardware.org/?probe=98aaf575cc) | Dec 26, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [f8466df8c5](https://linux-hardware.org/?probe=f8466df8c5) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [f2094a7c07](https://linux-hardware.org/?probe=f2094a7c07) | Dec 26, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [6fa1156580](https://linux-hardware.org/?probe=6fa1156580) | Dec 26, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [743bed087b](https://linux-hardware.org/?probe=743bed087b) | Dec 26, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [dbb5cde105](https://linux-hardware.org/?probe=dbb5cde105) | Dec 26, 2023 |
| Dell          | Inspiron 5391               | Notebook    | [a97f2efb6f](https://linux-hardware.org/?probe=a97f2efb6f) | Dec 26, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2edba36887](https://linux-hardware.org/?probe=2edba36887) | Dec 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [77553a2b0e](https://linux-hardware.org/?probe=77553a2b0e) | Dec 26, 2023 |
| Gigabyte      | A520M K V2                  | Desktop     | [4bd90e2bd6](https://linux-hardware.org/?probe=4bd90e2bd6) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a35ed82108](https://linux-hardware.org/?probe=a35ed82108) | Dec 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [d9ec9cb0f7](https://linux-hardware.org/?probe=d9ec9cb0f7) | Dec 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [0863d91cdc](https://linux-hardware.org/?probe=0863d91cdc) | Dec 25, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0867d19407](https://linux-hardware.org/?probe=0867d19407) | Dec 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [029b043cec](https://linux-hardware.org/?probe=029b043cec) | Dec 25, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [e6cbc30aad](https://linux-hardware.org/?probe=e6cbc30aad) | Dec 25, 2023 |
| Gigabyte      | Z790 D DDR4                 | Desktop     | [68f5cfe720](https://linux-hardware.org/?probe=68f5cfe720) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [58dd947260](https://linux-hardware.org/?probe=58dd947260) | Dec 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a78cd32bbe](https://linux-hardware.org/?probe=a78cd32bbe) | Dec 25, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [00a9997bfc](https://linux-hardware.org/?probe=00a9997bfc) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [d8eafc52d5](https://linux-hardware.org/?probe=d8eafc52d5) | Dec 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ffcec7155a](https://linux-hardware.org/?probe=ffcec7155a) | Dec 25, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c70c575614](https://linux-hardware.org/?probe=c70c575614) | Dec 25, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [ee3308d282](https://linux-hardware.org/?probe=ee3308d282) | Dec 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [08d0e2e3a0](https://linux-hardware.org/?probe=08d0e2e3a0) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1RS0... | Notebook    | [5c4efd5165](https://linux-hardware.org/?probe=5c4efd5165) | Dec 24, 2023 |
| ASUSTek       | X75A                        | Notebook    | [3af5f7aed7](https://linux-hardware.org/?probe=3af5f7aed7) | Dec 24, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [a54e95fcab](https://linux-hardware.org/?probe=a54e95fcab) | Dec 24, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [d41bca7300](https://linux-hardware.org/?probe=d41bca7300) | Dec 24, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [8080c75b27](https://linux-hardware.org/?probe=8080c75b27) | Dec 24, 2023 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [27a814dd64](https://linux-hardware.org/?probe=27a814dd64) | Dec 24, 2023 |
| Samsung       | 750QFG                      | Convertible | [12b0133961](https://linux-hardware.org/?probe=12b0133961) | Dec 24, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [39e33e4510](https://linux-hardware.org/?probe=39e33e4510) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [d7b7e34741](https://linux-hardware.org/?probe=d7b7e34741) | Dec 24, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [3c53e69328](https://linux-hardware.org/?probe=3c53e69328) | Dec 24, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6c6f281927](https://linux-hardware.org/?probe=6c6f281927) | Dec 23, 2023 |
| TECNO Mobi... | MEGABOOK T15DA              | Notebook    | [82d65cfce4](https://linux-hardware.org/?probe=82d65cfce4) | Dec 23, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [5590fcbfaf](https://linux-hardware.org/?probe=5590fcbfaf) | Dec 23, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [21df7039b9](https://linux-hardware.org/?probe=21df7039b9) | Dec 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9aa71593d4](https://linux-hardware.org/?probe=9aa71593d4) | Dec 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3819a04ddd](https://linux-hardware.org/?probe=3819a04ddd) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9425eb3c77](https://linux-hardware.org/?probe=9425eb3c77) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b9b670d3c0](https://linux-hardware.org/?probe=b9b670d3c0) | Dec 23, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [569ce717aa](https://linux-hardware.org/?probe=569ce717aa) | Dec 23, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [8dad235090](https://linux-hardware.org/?probe=8dad235090) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [8a36394313](https://linux-hardware.org/?probe=8a36394313) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [eb035a95fa](https://linux-hardware.org/?probe=eb035a95fa) | Dec 22, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [e6827a291e](https://linux-hardware.org/?probe=e6827a291e) | Dec 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0280... | Notebook    | [239bc0b85a](https://linux-hardware.org/?probe=239bc0b85a) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [e1225d2a37](https://linux-hardware.org/?probe=e1225d2a37) | Dec 22, 2023 |
| HP            | G62                         | Notebook    | [9f6a13bc50](https://linux-hardware.org/?probe=9f6a13bc50) | Dec 22, 2023 |
| ASUSTek       | X75A                        | Notebook    | [ed3c88f944](https://linux-hardware.org/?probe=ed3c88f944) | Dec 22, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [3fe6ce1b31](https://linux-hardware.org/?probe=3fe6ce1b31) | Dec 22, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [b8dcef4553](https://linux-hardware.org/?probe=b8dcef4553) | Dec 22, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [45079856a0](https://linux-hardware.org/?probe=45079856a0) | Dec 22, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [37e175c7a2](https://linux-hardware.org/?probe=37e175c7a2) | Dec 21, 2023 |
| Sony          | VPCCA3X1R                   | Notebook    | [156b109950](https://linux-hardware.org/?probe=156b109950) | Dec 21, 2023 |
| HP            | ProBook 6450b               | Notebook    | [dd9c6803cb](https://linux-hardware.org/?probe=dd9c6803cb) | Dec 21, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [2bd748691b](https://linux-hardware.org/?probe=2bd748691b) | Dec 21, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [64131ee7e0](https://linux-hardware.org/?probe=64131ee7e0) | Dec 21, 2023 |
| ASUSTek       | X75A                        | Notebook    | [6d9c65c8ac](https://linux-hardware.org/?probe=6d9c65c8ac) | Dec 21, 2023 |
| ASRock        | B760M Pro RS                | Desktop     | [f648cda96d](https://linux-hardware.org/?probe=f648cda96d) | Dec 21, 2023 |
| Gigabyte      | B660I AORUS PRO DDR4        | Desktop     | [f9552f9e38](https://linux-hardware.org/?probe=f9552f9e38) | Dec 21, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e222a97c0b](https://linux-hardware.org/?probe=e222a97c0b) | Dec 21, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [8bce457975](https://linux-hardware.org/?probe=8bce457975) | Dec 21, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5c0166e1f8](https://linux-hardware.org/?probe=5c0166e1f8) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [d0d0568d9d](https://linux-hardware.org/?probe=d0d0568d9d) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| Dell          | Latitude 5590               | Notebook    | [9877862088](https://linux-hardware.org/?probe=9877862088) | Dec 21, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [6e4bcb9311](https://linux-hardware.org/?probe=6e4bcb9311) | Dec 21, 2023 |
| Lenovo        | ThinkPad X280 20KEA00SUK    | Notebook    | [bc380b4334](https://linux-hardware.org/?probe=bc380b4334) | Dec 21, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [a2194f1fc6](https://linux-hardware.org/?probe=a2194f1fc6) | Dec 21, 2023 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [c125585a5d](https://linux-hardware.org/?probe=c125585a5d) | Dec 21, 2023 |
| Lenovo        | ThinkPad SL 2746E9G         | Notebook    | [594a56a070](https://linux-hardware.org/?probe=594a56a070) | Dec 21, 2023 |
| HP            | 82F1                        | Desktop     | [6e05cf58df](https://linux-hardware.org/?probe=6e05cf58df) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5a16e00d6c](https://linux-hardware.org/?probe=5a16e00d6c) | Dec 20, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [d420770c44](https://linux-hardware.org/?probe=d420770c44) | Dec 20, 2023 |
| HP            | ProBook 445 14 inch G10 ... | Notebook    | [5b3a77bd87](https://linux-hardware.org/?probe=5b3a77bd87) | Dec 20, 2023 |
| Acer          | Aspire E1-771G              | Notebook    | [07bcd26f94](https://linux-hardware.org/?probe=07bcd26f94) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [00d649079a](https://linux-hardware.org/?probe=00d649079a) | Dec 20, 2023 |
| Gigabyte      | A520M DS3H V2               | Desktop     | [3ba51c21e8](https://linux-hardware.org/?probe=3ba51c21e8) | Dec 20, 2023 |
| ASRock        | M3A UCC                     | Desktop     | [f28e499d94](https://linux-hardware.org/?probe=f28e499d94) | Dec 20, 2023 |
| Lenovo        | 310C SDK0J40705 WIN 3425... | Desktop     | [c1ee1cd84d](https://linux-hardware.org/?probe=c1ee1cd84d) | Dec 19, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [8e6c8be806](https://linux-hardware.org/?probe=8e6c8be806) | Dec 19, 2023 |
| Google        | Pantheon                    | Notebook    | [f4640ed7c1](https://linux-hardware.org/?probe=f4640ed7c1) | Dec 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35272a3d20](https://linux-hardware.org/?probe=35272a3d20) | Dec 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [a32cb7798b](https://linux-hardware.org/?probe=a32cb7798b) | Dec 19, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [30ecc8cbbb](https://linux-hardware.org/?probe=30ecc8cbbb) | Dec 19, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [533ccb0c41](https://linux-hardware.org/?probe=533ccb0c41) | Dec 19, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0fd7e9086a](https://linux-hardware.org/?probe=0fd7e9086a) | Dec 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [8dac564efb](https://linux-hardware.org/?probe=8dac564efb) | Dec 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6184376b69](https://linux-hardware.org/?probe=6184376b69) | Dec 19, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [19af9254cb](https://linux-hardware.org/?probe=19af9254cb) | Dec 19, 2023 |
| Dell          | Inspiron 15 3535            | Notebook    | [f86bf3e2f1](https://linux-hardware.org/?probe=f86bf3e2f1) | Dec 18, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [5255e11641](https://linux-hardware.org/?probe=5255e11641) | Dec 18, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [6d81343411](https://linux-hardware.org/?probe=6d81343411) | Dec 18, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5de00ab671](https://linux-hardware.org/?probe=5de00ab671) | Dec 18, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [b6e59d6e3e](https://linux-hardware.org/?probe=b6e59d6e3e) | Dec 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6db91b5eb2](https://linux-hardware.org/?probe=6db91b5eb2) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c18f5d3a21](https://linux-hardware.org/?probe=c18f5d3a21) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [982ae3655c](https://linux-hardware.org/?probe=982ae3655c) | Dec 18, 2023 |
| Samsung       | 750XDA                      | Notebook    | [bdaba42db8](https://linux-hardware.org/?probe=bdaba42db8) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0bedf3955a](https://linux-hardware.org/?probe=0bedf3955a) | Dec 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [74cbcabaa1](https://linux-hardware.org/?probe=74cbcabaa1) | Dec 17, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [45d168f910](https://linux-hardware.org/?probe=45d168f910) | Dec 17, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [28d755787e](https://linux-hardware.org/?probe=28d755787e) | Dec 17, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [447fb33261](https://linux-hardware.org/?probe=447fb33261) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [ed79377477](https://linux-hardware.org/?probe=ed79377477) | Dec 17, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [27f1370b2c](https://linux-hardware.org/?probe=27f1370b2c) | Dec 17, 2023 |
| Acer          | Aspire M3920                | Desktop     | [ccca1b4884](https://linux-hardware.org/?probe=ccca1b4884) | Dec 17, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [28b95cc0b7](https://linux-hardware.org/?probe=28b95cc0b7) | Dec 16, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [812cd1effd](https://linux-hardware.org/?probe=812cd1effd) | Dec 16, 2023 |
| Dell          | Latitude 7350               | Notebook    | [ab9a873c1e](https://linux-hardware.org/?probe=ab9a873c1e) | Dec 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bac2e83dd7](https://linux-hardware.org/?probe=bac2e83dd7) | Dec 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fee42ea005](https://linux-hardware.org/?probe=fee42ea005) | Dec 16, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [091abf1a59](https://linux-hardware.org/?probe=091abf1a59) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e1e496f1a9](https://linux-hardware.org/?probe=e1e496f1a9) | Dec 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6689e06c77](https://linux-hardware.org/?probe=6689e06c77) | Dec 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b653a2fdf8](https://linux-hardware.org/?probe=b653a2fdf8) | Dec 15, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [88ffce598c](https://linux-hardware.org/?probe=88ffce598c) | Dec 15, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [971233beec](https://linux-hardware.org/?probe=971233beec) | Dec 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [921d38d2df](https://linux-hardware.org/?probe=921d38d2df) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4cb7a5528b](https://linux-hardware.org/?probe=4cb7a5528b) | Dec 15, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [b65075cb67](https://linux-hardware.org/?probe=b65075cb67) | Dec 14, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [0b08ee22d8](https://linux-hardware.org/?probe=0b08ee22d8) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [262bfe0585](https://linux-hardware.org/?probe=262bfe0585) | Dec 14, 2023 |
| Dell          | Precision 5680              | Notebook    | [1e063996da](https://linux-hardware.org/?probe=1e063996da) | Dec 14, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [b5b534e106](https://linux-hardware.org/?probe=b5b534e106) | Dec 14, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [277dadb387](https://linux-hardware.org/?probe=277dadb387) | Dec 13, 2023 |
| Lenovo        | ThinkPad T480 20L50004MX    | Notebook    | [691f1ae82f](https://linux-hardware.org/?probe=691f1ae82f) | Dec 13, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e101fc39e2](https://linux-hardware.org/?probe=e101fc39e2) | Dec 13, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1785db3e7b](https://linux-hardware.org/?probe=1785db3e7b) | Dec 13, 2023 |
| Timi          | TM1604                      | Notebook    | [67597f3bd5](https://linux-hardware.org/?probe=67597f3bd5) | Dec 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6a497408c3](https://linux-hardware.org/?probe=6a497408c3) | Dec 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f79863b604](https://linux-hardware.org/?probe=f79863b604) | Dec 13, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [73c69f2b50](https://linux-hardware.org/?probe=73c69f2b50) | Dec 13, 2023 |
| Canyon        | I865P/PE                    | Desktop     | [68de5ab5cb](https://linux-hardware.org/?probe=68de5ab5cb) | Dec 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [81baeeb4c6](https://linux-hardware.org/?probe=81baeeb4c6) | Dec 12, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [c05cd1b8c9](https://linux-hardware.org/?probe=c05cd1b8c9) | Dec 12, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [e340ad2e3a](https://linux-hardware.org/?probe=e340ad2e3a) | Dec 12, 2023 |
| HP            | ENVY 15                     | Notebook    | [d8a9e409c9](https://linux-hardware.org/?probe=d8a9e409c9) | Dec 12, 2023 |
| ASUSTek       | K45VD                       | Notebook    | [527a669776](https://linux-hardware.org/?probe=527a669776) | Dec 12, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1d510c91de](https://linux-hardware.org/?probe=1d510c91de) | Dec 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2eeac061b2](https://linux-hardware.org/?probe=2eeac061b2) | Dec 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [c9dd6aebbd](https://linux-hardware.org/?probe=c9dd6aebbd) | Dec 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e2d113342f](https://linux-hardware.org/?probe=e2d113342f) | Dec 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ecd2c34f0a](https://linux-hardware.org/?probe=ecd2c34f0a) | Dec 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [af38b45c59](https://linux-hardware.org/?probe=af38b45c59) | Dec 12, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [6a4ff9d940](https://linux-hardware.org/?probe=6a4ff9d940) | Dec 11, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [9311323293](https://linux-hardware.org/?probe=9311323293) | Dec 11, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [ffcb3c9798](https://linux-hardware.org/?probe=ffcb3c9798) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c71a153915](https://linux-hardware.org/?probe=c71a153915) | Dec 11, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [c136ca6eff](https://linux-hardware.org/?probe=c136ca6eff) | Dec 11, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2e767eb168](https://linux-hardware.org/?probe=2e767eb168) | Dec 11, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [2349ef67ed](https://linux-hardware.org/?probe=2349ef67ed) | Dec 11, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [db2d055fa7](https://linux-hardware.org/?probe=db2d055fa7) | Dec 11, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [15409fd336](https://linux-hardware.org/?probe=15409fd336) | Dec 11, 2023 |
| GPD           | G1619-03                    | Notebook    | [92773d52d8](https://linux-hardware.org/?probe=92773d52d8) | Dec 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [d9227b24b0](https://linux-hardware.org/?probe=d9227b24b0) | Dec 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [508ad0be0e](https://linux-hardware.org/?probe=508ad0be0e) | Dec 10, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [ba6f3ac46c](https://linux-hardware.org/?probe=ba6f3ac46c) | Dec 10, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [62b99b4cdd](https://linux-hardware.org/?probe=62b99b4cdd) | Dec 10, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [dd9345ea7d](https://linux-hardware.org/?probe=dd9345ea7d) | Dec 10, 2023 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [09d713ee95](https://linux-hardware.org/?probe=09d713ee95) | Dec 10, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [eed0305500](https://linux-hardware.org/?probe=eed0305500) | Dec 10, 2023 |
| Dell          | Latitude 7490               | Notebook    | [d9f20ad453](https://linux-hardware.org/?probe=d9f20ad453) | Dec 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6e1edcba6d](https://linux-hardware.org/?probe=6e1edcba6d) | Dec 10, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e7872542e1](https://linux-hardware.org/?probe=e7872542e1) | Dec 10, 2023 |
| Dell          | Precision 5480              | Notebook    | [e2ef5d90ca](https://linux-hardware.org/?probe=e2ef5d90ca) | Dec 10, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [c8e3c94a82](https://linux-hardware.org/?probe=c8e3c94a82) | Dec 10, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [0a40b25b2d](https://linux-hardware.org/?probe=0a40b25b2d) | Dec 10, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [9939fe96d2](https://linux-hardware.org/?probe=9939fe96d2) | Dec 10, 2023 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [69597249b3](https://linux-hardware.org/?probe=69597249b3) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G533QM_G533QM     | Notebook    | [200be2174b](https://linux-hardware.org/?probe=200be2174b) | Dec 09, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [71c6b35d56](https://linux-hardware.org/?probe=71c6b35d56) | Dec 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [31943290a3](https://linux-hardware.org/?probe=31943290a3) | Dec 09, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [c5a3d157b2](https://linux-hardware.org/?probe=c5a3d157b2) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [551b412a34](https://linux-hardware.org/?probe=551b412a34) | Dec 09, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [ac6488c0c8](https://linux-hardware.org/?probe=ac6488c0c8) | Dec 09, 2023 |
| Acer          | AOD270                      | Notebook    | [b5729a6428](https://linux-hardware.org/?probe=b5729a6428) | Dec 09, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [f061ab31d0](https://linux-hardware.org/?probe=f061ab31d0) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [051769648f](https://linux-hardware.org/?probe=051769648f) | Dec 09, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b3549a6dea](https://linux-hardware.org/?probe=b3549a6dea) | Dec 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [740c338fbe](https://linux-hardware.org/?probe=740c338fbe) | Dec 08, 2023 |
| GPD           | G1619-03                    | Notebook    | [bc2ade83b8](https://linux-hardware.org/?probe=bc2ade83b8) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [a696c1d832](https://linux-hardware.org/?probe=a696c1d832) | Dec 08, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [5775bf1613](https://linux-hardware.org/?probe=5775bf1613) | Dec 08, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [85cd0d0c3d](https://linux-hardware.org/?probe=85cd0d0c3d) | Dec 08, 2023 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | Desktop     | [78c824704d](https://linux-hardware.org/?probe=78c824704d) | Dec 08, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [d3de4cf5b2](https://linux-hardware.org/?probe=d3de4cf5b2) | Dec 08, 2023 |
| ASUSTek       | X540SC                      | Notebook    | [4d5388e6ab](https://linux-hardware.org/?probe=4d5388e6ab) | Dec 08, 2023 |
| Dell          | Latitude E5550              | Notebook    | [52866a9d1a](https://linux-hardware.org/?probe=52866a9d1a) | Dec 08, 2023 |
| Alienware     | x15 R1                      | Notebook    | [08aa034a6d](https://linux-hardware.org/?probe=08aa034a6d) | Dec 08, 2023 |
| ASRock        | M3A UCC                     | Desktop     | [f73d6783e6](https://linux-hardware.org/?probe=f73d6783e6) | Dec 08, 2023 |
| Acer          | Aspire E1-771G              | Notebook    | [099fae46db](https://linux-hardware.org/?probe=099fae46db) | Dec 07, 2023 |
| ASRock        | B760M Pro RS                | Desktop     | [77b3b5fc4d](https://linux-hardware.org/?probe=77b3b5fc4d) | Dec 07, 2023 |
| VPU Compan... | VWNC71429-S                 | Notebook    | [c0b0f86403](https://linux-hardware.org/?probe=c0b0f86403) | Dec 07, 2023 |
| Lenovo        | ThinkPad T480s 20L7001LM... | Notebook    | [37c62fe0ba](https://linux-hardware.org/?probe=37c62fe0ba) | Dec 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c37147ae36](https://linux-hardware.org/?probe=c37147ae36) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [87aa35c45c](https://linux-hardware.org/?probe=87aa35c45c) | Dec 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [3df79f79ee](https://linux-hardware.org/?probe=3df79f79ee) | Dec 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36fe4a1de9](https://linux-hardware.org/?probe=36fe4a1de9) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2a593d9294](https://linux-hardware.org/?probe=2a593d9294) | Dec 06, 2023 |
| Acer          | Aspire E1-771G              | Notebook    | [28f6aca279](https://linux-hardware.org/?probe=28f6aca279) | Dec 06, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [4c19d8a91e](https://linux-hardware.org/?probe=4c19d8a91e) | Dec 06, 2023 |
| Medion        | B550A4-EM                   | Desktop     | [bd40049c5d](https://linux-hardware.org/?probe=bd40049c5d) | Dec 06, 2023 |
| HP            | Pavilion x360 14 Convert... | Convertible | [5de0c29333](https://linux-hardware.org/?probe=5de0c29333) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ed77f35114](https://linux-hardware.org/?probe=ed77f35114) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ac764bedcc](https://linux-hardware.org/?probe=ac764bedcc) | Dec 06, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [a475eb0eb8](https://linux-hardware.org/?probe=a475eb0eb8) | Dec 06, 2023 |
| HP            | 802E                        | Desktop     | [0f4d573a9b](https://linux-hardware.org/?probe=0f4d573a9b) | Dec 06, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [af5f86d3a2](https://linux-hardware.org/?probe=af5f86d3a2) | Dec 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [58e1501577](https://linux-hardware.org/?probe=58e1501577) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [fae6162d7b](https://linux-hardware.org/?probe=fae6162d7b) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9b6c1bfbf2](https://linux-hardware.org/?probe=9b6c1bfbf2) | Dec 06, 2023 |
| Dell          | 0YWR73 A06                  | Server      | [78e594b5ad](https://linux-hardware.org/?probe=78e594b5ad) | Dec 06, 2023 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [e52613f035](https://linux-hardware.org/?probe=e52613f035) | Dec 06, 2023 |
| HP            | 802E                        | Desktop     | [9b58aa9c3a](https://linux-hardware.org/?probe=9b58aa9c3a) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [f42e951aa3](https://linux-hardware.org/?probe=f42e951aa3) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [757356c6f7](https://linux-hardware.org/?probe=757356c6f7) | Dec 05, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [1be5bb95d1](https://linux-hardware.org/?probe=1be5bb95d1) | Dec 05, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6d0f07a930](https://linux-hardware.org/?probe=6d0f07a930) | Dec 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5a7d45a007](https://linux-hardware.org/?probe=5a7d45a007) | Dec 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2d6eaf642b](https://linux-hardware.org/?probe=2d6eaf642b) | Dec 05, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3eba272feb](https://linux-hardware.org/?probe=3eba272feb) | Dec 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [a2c9c3b295](https://linux-hardware.org/?probe=a2c9c3b295) | Dec 05, 2023 |
| Intel         | ChiefRiver                  | Desktop     | [6a4b7aebe9](https://linux-hardware.org/?probe=6a4b7aebe9) | Dec 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7ccb597e5c](https://linux-hardware.org/?probe=7ccb597e5c) | Dec 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be2d11a5b9](https://linux-hardware.org/?probe=be2d11a5b9) | Dec 04, 2023 |
| Dell          | Latitude 9330               | Convertible | [1c8a7db9cf](https://linux-hardware.org/?probe=1c8a7db9cf) | Dec 04, 2023 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [a68c730c13](https://linux-hardware.org/?probe=a68c730c13) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [54b2e1f4f1](https://linux-hardware.org/?probe=54b2e1f4f1) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4d938aed80](https://linux-hardware.org/?probe=4d938aed80) | Dec 04, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [0964d78171](https://linux-hardware.org/?probe=0964d78171) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [d91e8dc1a8](https://linux-hardware.org/?probe=d91e8dc1a8) | Dec 04, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [836c545bcb](https://linux-hardware.org/?probe=836c545bcb) | Dec 04, 2023 |
| Dell          | Latitude 7350               | Notebook    | [74c3983604](https://linux-hardware.org/?probe=74c3983604) | Dec 04, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [a66e59470c](https://linux-hardware.org/?probe=a66e59470c) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b1fdfbc998](https://linux-hardware.org/?probe=b1fdfbc998) | Dec 03, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [3c9d00c839](https://linux-hardware.org/?probe=3c9d00c839) | Dec 03, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [c2e09d65d5](https://linux-hardware.org/?probe=c2e09d65d5) | Dec 03, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [2cd108c526](https://linux-hardware.org/?probe=2cd108c526) | Dec 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b052f32ef5](https://linux-hardware.org/?probe=b052f32ef5) | Dec 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6c21c9ac7d](https://linux-hardware.org/?probe=6c21c9ac7d) | Dec 03, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [e1edd54ac3](https://linux-hardware.org/?probe=e1edd54ac3) | Dec 03, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [f4c7fc7890](https://linux-hardware.org/?probe=f4c7fc7890) | Dec 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [10dbf91cb7](https://linux-hardware.org/?probe=10dbf91cb7) | Dec 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [09104cdc15](https://linux-hardware.org/?probe=09104cdc15) | Dec 03, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c608bb4e30](https://linux-hardware.org/?probe=c608bb4e30) | Dec 03, 2023 |
| System76      | Lemur Pro                   | Notebook    | [8dcc66a7e6](https://linux-hardware.org/?probe=8dcc66a7e6) | Dec 03, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [55eb62ad2f](https://linux-hardware.org/?probe=55eb62ad2f) | Dec 02, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [68c7c96b9b](https://linux-hardware.org/?probe=68c7c96b9b) | Dec 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a18c178195](https://linux-hardware.org/?probe=a18c178195) | Dec 02, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [58b6cdf11c](https://linux-hardware.org/?probe=58b6cdf11c) | Dec 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1G63Q    | Notebook    | [0bb363e4fc](https://linux-hardware.org/?probe=0bb363e4fc) | Dec 02, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [6f41c9ca50](https://linux-hardware.org/?probe=6f41c9ca50) | Dec 02, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [d01b48eb39](https://linux-hardware.org/?probe=d01b48eb39) | Dec 02, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [cc61afde30](https://linux-hardware.org/?probe=cc61afde30) | Dec 02, 2023 |
| HP            | Notebook                    | Notebook    | [399699d1ce](https://linux-hardware.org/?probe=399699d1ce) | Dec 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [7c6a2f74f0](https://linux-hardware.org/?probe=7c6a2f74f0) | Dec 02, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [5cf002f5af](https://linux-hardware.org/?probe=5cf002f5af) | Dec 02, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [c9a9c0d3b7](https://linux-hardware.org/?probe=c9a9c0d3b7) | Dec 02, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [c3ea561754](https://linux-hardware.org/?probe=c3ea561754) | Dec 02, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [34df3b2497](https://linux-hardware.org/?probe=34df3b2497) | Dec 02, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [ba6823f38e](https://linux-hardware.org/?probe=ba6823f38e) | Dec 02, 2023 |
| Framework     | Laptop                      | Notebook    | [92f0d97b05](https://linux-hardware.org/?probe=92f0d97b05) | Dec 02, 2023 |
| Framework     | Laptop                      | Notebook    | [995d231691](https://linux-hardware.org/?probe=995d231691) | Dec 02, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [f5e978e47d](https://linux-hardware.org/?probe=f5e978e47d) | Dec 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6ece5a0c44](https://linux-hardware.org/?probe=6ece5a0c44) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [27ca1601a1](https://linux-hardware.org/?probe=27ca1601a1) | Dec 01, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [a82cdb418c](https://linux-hardware.org/?probe=a82cdb418c) | Dec 01, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [a1ab0858a6](https://linux-hardware.org/?probe=a1ab0858a6) | Dec 01, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [22263182fb](https://linux-hardware.org/?probe=22263182fb) | Dec 01, 2023 |
| Lenovo        | 14w Gen 2 82N8              | Notebook    | [bc02b5a084](https://linux-hardware.org/?probe=bc02b5a084) | Dec 01, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [973b00d566](https://linux-hardware.org/?probe=973b00d566) | Dec 01, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [fb2fbabcbe](https://linux-hardware.org/?probe=fb2fbabcbe) | Dec 01, 2023 |
| Lenovo        | B5400 20278                 | Notebook    | [fd17e40f77](https://linux-hardware.org/?probe=fd17e40f77) | Dec 01, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [f98f84669d](https://linux-hardware.org/?probe=f98f84669d) | Dec 01, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [48d13cedfc](https://linux-hardware.org/?probe=48d13cedfc) | Dec 01, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [f3f624e1cf](https://linux-hardware.org/?probe=f3f624e1cf) | Nov 30, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [945c324d2b](https://linux-hardware.org/?probe=945c324d2b) | Nov 30, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [7c4f4d3207](https://linux-hardware.org/?probe=7c4f4d3207) | Nov 30, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [78a6b232e3](https://linux-hardware.org/?probe=78a6b232e3) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [e0e3a6f229](https://linux-hardware.org/?probe=e0e3a6f229) | Nov 30, 2023 |
| Lenovo        | ThinkPad T14s Gen1 20UH0... | Notebook    | [9c37d9bff8](https://linux-hardware.org/?probe=9c37d9bff8) | Nov 30, 2023 |
| Dell          | Precision M6800             | Notebook    | [0112706077](https://linux-hardware.org/?probe=0112706077) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [71cf2f0a79](https://linux-hardware.org/?probe=71cf2f0a79) | Nov 29, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [eb52097d1b](https://linux-hardware.org/?probe=eb52097d1b) | Nov 29, 2023 |
| HP            | 1495                        | Desktop     | [cf77f4899b](https://linux-hardware.org/?probe=cf77f4899b) | Nov 29, 2023 |
| HP            | 1495                        | Desktop     | [eafdff069c](https://linux-hardware.org/?probe=eafdff069c) | Nov 29, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [bb1d8fb09e](https://linux-hardware.org/?probe=bb1d8fb09e) | Nov 29, 2023 |
| HP            | EliteBook 8530p             | Notebook    | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Lenovo        | ThinkPad P52s 20LCA0ANUK    | Notebook    | [2cf85106d8](https://linux-hardware.org/?probe=2cf85106d8) | Nov 29, 2023 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [f43aaf1d39](https://linux-hardware.org/?probe=f43aaf1d39) | Nov 29, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [be0c718878](https://linux-hardware.org/?probe=be0c718878) | Nov 29, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [772e5ce3f6](https://linux-hardware.org/?probe=772e5ce3f6) | Nov 29, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [37ecb34a8a](https://linux-hardware.org/?probe=37ecb34a8a) | Nov 29, 2023 |
| Dell          | 0V0D45 A01                  | All in one  | [1976be5d27](https://linux-hardware.org/?probe=1976be5d27) | Nov 29, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [21451de65a](https://linux-hardware.org/?probe=21451de65a) | Nov 28, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [2a9b640b54](https://linux-hardware.org/?probe=2a9b640b54) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [35775b438a](https://linux-hardware.org/?probe=35775b438a) | Nov 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [9530bb80db](https://linux-hardware.org/?probe=9530bb80db) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [6eb25169c1](https://linux-hardware.org/?probe=6eb25169c1) | Nov 28, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [b8337b50d8](https://linux-hardware.org/?probe=b8337b50d8) | Nov 28, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [8b5f96b606](https://linux-hardware.org/?probe=8b5f96b606) | Nov 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5474258ca4](https://linux-hardware.org/?probe=5474258ca4) | Nov 28, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7378c9d9a4](https://linux-hardware.org/?probe=7378c9d9a4) | Nov 28, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [db37ad807a](https://linux-hardware.org/?probe=db37ad807a) | Nov 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5358617403](https://linux-hardware.org/?probe=5358617403) | Nov 28, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [92354a1a90](https://linux-hardware.org/?probe=92354a1a90) | Nov 28, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [549e026701](https://linux-hardware.org/?probe=549e026701) | Nov 28, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [f2dae5468d](https://linux-hardware.org/?probe=f2dae5468d) | Nov 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [8c51aa422e](https://linux-hardware.org/?probe=8c51aa422e) | Nov 27, 2023 |
| ASUSTek       | G11CB                       | Desktop     | [31f2fc857d](https://linux-hardware.org/?probe=31f2fc857d) | Nov 27, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [d597be352c](https://linux-hardware.org/?probe=d597be352c) | Nov 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3342bb8661](https://linux-hardware.org/?probe=3342bb8661) | Nov 27, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [bfab8a5c50](https://linux-hardware.org/?probe=bfab8a5c50) | Nov 27, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [aae9fdf3a0](https://linux-hardware.org/?probe=aae9fdf3a0) | Nov 26, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ea990a4015](https://linux-hardware.org/?probe=ea990a4015) | Nov 26, 2023 |
| HP            | 158A                        | Desktop     | [880d4cc918](https://linux-hardware.org/?probe=880d4cc918) | Nov 26, 2023 |
| Google        | Osiris                      | Notebook    | [104c509853](https://linux-hardware.org/?probe=104c509853) | Nov 26, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [5aa0f85707](https://linux-hardware.org/?probe=5aa0f85707) | Nov 26, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [9bb8e96cf9](https://linux-hardware.org/?probe=9bb8e96cf9) | Nov 26, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [5cc2969751](https://linux-hardware.org/?probe=5cc2969751) | Nov 26, 2023 |
| Acer          | Aspire Lite AL15-41         | Notebook    | [1ab369fc06](https://linux-hardware.org/?probe=1ab369fc06) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76ce86d3d6](https://linux-hardware.org/?probe=76ce86d3d6) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [41443f69e3](https://linux-hardware.org/?probe=41443f69e3) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [325261bf0d](https://linux-hardware.org/?probe=325261bf0d) | Nov 25, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [b425e66375](https://linux-hardware.org/?probe=b425e66375) | Nov 25, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e17bdfe79f](https://linux-hardware.org/?probe=e17bdfe79f) | Nov 25, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6dce0312bc](https://linux-hardware.org/?probe=6dce0312bc) | Nov 25, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [3ffe3ca5b7](https://linux-hardware.org/?probe=3ffe3ca5b7) | Nov 25, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a44be8cd81](https://linux-hardware.org/?probe=a44be8cd81) | Nov 25, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [409c3e67d2](https://linux-hardware.org/?probe=409c3e67d2) | Nov 25, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [e63dc731c2](https://linux-hardware.org/?probe=e63dc731c2) | Nov 25, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [5cbdf33238](https://linux-hardware.org/?probe=5cbdf33238) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0a8b21ee58](https://linux-hardware.org/?probe=0a8b21ee58) | Nov 25, 2023 |
| Timi          | TM1604                      | Notebook    | [6dca61908e](https://linux-hardware.org/?probe=6dca61908e) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [5b41f73363](https://linux-hardware.org/?probe=5b41f73363) | Nov 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5c29cfeb41](https://linux-hardware.org/?probe=5c29cfeb41) | Nov 25, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [0b974daf24](https://linux-hardware.org/?probe=0b974daf24) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94177be7ac](https://linux-hardware.org/?probe=94177be7ac) | Nov 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [d69be34130](https://linux-hardware.org/?probe=d69be34130) | Nov 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [e225477a30](https://linux-hardware.org/?probe=e225477a30) | Nov 24, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [f84212c870](https://linux-hardware.org/?probe=f84212c870) | Nov 24, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [432ec62dd0](https://linux-hardware.org/?probe=432ec62dd0) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1302407078](https://linux-hardware.org/?probe=1302407078) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [7871e7654b](https://linux-hardware.org/?probe=7871e7654b) | Nov 24, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [dfe4473084](https://linux-hardware.org/?probe=dfe4473084) | Nov 24, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [f6a6c2a2fe](https://linux-hardware.org/?probe=f6a6c2a2fe) | Nov 24, 2023 |
| Dell          | G3 3500                     | Notebook    | [c53dff54a2](https://linux-hardware.org/?probe=c53dff54a2) | Nov 24, 2023 |
| A14CR         | Unknown                     | Notebook    | [c0924a368e](https://linux-hardware.org/?probe=c0924a368e) | Nov 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [c45c9df0f9](https://linux-hardware.org/?probe=c45c9df0f9) | Nov 24, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [422a19e5a3](https://linux-hardware.org/?probe=422a19e5a3) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [aaccb61f12](https://linux-hardware.org/?probe=aaccb61f12) | Nov 24, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [df38b119a1](https://linux-hardware.org/?probe=df38b119a1) | Nov 23, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [04dd78f309](https://linux-hardware.org/?probe=04dd78f309) | Nov 23, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7a59ed85d0](https://linux-hardware.org/?probe=7a59ed85d0) | Nov 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f3956e461c](https://linux-hardware.org/?probe=f3956e461c) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | Notebook    | [e0be96f7e5](https://linux-hardware.org/?probe=e0be96f7e5) | Nov 23, 2023 |
| Colorful T... | iGame Z270 Ymir             | Desktop     | [62929668f5](https://linux-hardware.org/?probe=62929668f5) | Nov 23, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [e01de3faf5](https://linux-hardware.org/?probe=e01de3faf5) | Nov 23, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [a3eefd5bce](https://linux-hardware.org/?probe=a3eefd5bce) | Nov 23, 2023 |
| Acer          | Aspire E5-576               | Notebook    | [714225261c](https://linux-hardware.org/?probe=714225261c) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [193588412a](https://linux-hardware.org/?probe=193588412a) | Nov 23, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3dc5073ae3](https://linux-hardware.org/?probe=3dc5073ae3) | Nov 22, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [88c28ecfa9](https://linux-hardware.org/?probe=88c28ecfa9) | Nov 22, 2023 |
| Dell          | Latitude E6420              | Notebook    | [dab1a90459](https://linux-hardware.org/?probe=dab1a90459) | Nov 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9ae52fcb89](https://linux-hardware.org/?probe=9ae52fcb89) | Nov 22, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c1d0f0a97d](https://linux-hardware.org/?probe=c1d0f0a97d) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [7172a8aca0](https://linux-hardware.org/?probe=7172a8aca0) | Nov 22, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [2669814618](https://linux-hardware.org/?probe=2669814618) | Nov 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [b23adf2f66](https://linux-hardware.org/?probe=b23adf2f66) | Nov 22, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c6e62720db](https://linux-hardware.org/?probe=c6e62720db) | Nov 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3b58318a77](https://linux-hardware.org/?probe=3b58318a77) | Nov 22, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [5317e6d4a5](https://linux-hardware.org/?probe=5317e6d4a5) | Nov 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [522acd0620](https://linux-hardware.org/?probe=522acd0620) | Nov 22, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [df5747727b](https://linux-hardware.org/?probe=df5747727b) | Nov 22, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cd2ed07d2e](https://linux-hardware.org/?probe=cd2ed07d2e) | Nov 22, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [746bd8c3d5](https://linux-hardware.org/?probe=746bd8c3d5) | Nov 21, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [9fe4290fb6](https://linux-hardware.org/?probe=9fe4290fb6) | Nov 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [7c048e0f1a](https://linux-hardware.org/?probe=7c048e0f1a) | Nov 21, 2023 |
| Dell          | 0X4H68 A00                  | Desktop     | [93d573033d](https://linux-hardware.org/?probe=93d573033d) | Nov 21, 2023 |
| Lenovo        | ThinkPad T480s 20L7004PG... | Notebook    | [32665cdd0e](https://linux-hardware.org/?probe=32665cdd0e) | Nov 21, 2023 |
| Grupo Nucl... | Eurocase MB40               | Notebook    | [aaedd81604](https://linux-hardware.org/?probe=aaedd81604) | Nov 21, 2023 |
| Grupo Nucl... | Eurocase MB40               | Notebook    | [6c601d96d9](https://linux-hardware.org/?probe=6c601d96d9) | Nov 21, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6b88b81e69](https://linux-hardware.org/?probe=6b88b81e69) | Nov 21, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [9218c25c70](https://linux-hardware.org/?probe=9218c25c70) | Nov 21, 2023 |
| AMI           | INTEL                       | Convertible | [1a42148f23](https://linux-hardware.org/?probe=1a42148f23) | Nov 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [6c94522ba3](https://linux-hardware.org/?probe=6c94522ba3) | Nov 21, 2023 |
| Dell          | Latitude E6510              | Notebook    | [1ac84451c5](https://linux-hardware.org/?probe=1ac84451c5) | Nov 21, 2023 |
| ASUSTek       | X456UV                      | Notebook    | [f38105228e](https://linux-hardware.org/?probe=f38105228e) | Nov 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [58af364f54](https://linux-hardware.org/?probe=58af364f54) | Nov 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e1e3a4bb80](https://linux-hardware.org/?probe=e1e3a4bb80) | Nov 20, 2023 |
| ASRock        | B650M Pro RS                | Desktop     | [d5c721e44b](https://linux-hardware.org/?probe=d5c721e44b) | Nov 20, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [f9da55efe2](https://linux-hardware.org/?probe=f9da55efe2) | Nov 20, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4191c265d7](https://linux-hardware.org/?probe=4191c265d7) | Nov 20, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [9572f8f8c1](https://linux-hardware.org/?probe=9572f8f8c1) | Nov 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [6381dd5516](https://linux-hardware.org/?probe=6381dd5516) | Nov 20, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b7c606eb5e](https://linux-hardware.org/?probe=b7c606eb5e) | Nov 20, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [1252886377](https://linux-hardware.org/?probe=1252886377) | Nov 20, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [a41e49fbb9](https://linux-hardware.org/?probe=a41e49fbb9) | Nov 20, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [f4f0cc26d8](https://linux-hardware.org/?probe=f4f0cc26d8) | Nov 20, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [b9d4174713](https://linux-hardware.org/?probe=b9d4174713) | Nov 19, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [86881fc519](https://linux-hardware.org/?probe=86881fc519) | Nov 19, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [d0272f412b](https://linux-hardware.org/?probe=d0272f412b) | Nov 19, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [ceafa361bc](https://linux-hardware.org/?probe=ceafa361bc) | Nov 19, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [b20c5c71dd](https://linux-hardware.org/?probe=b20c5c71dd) | Nov 19, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [414a04328d](https://linux-hardware.org/?probe=414a04328d) | Nov 19, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [90e30a4476](https://linux-hardware.org/?probe=90e30a4476) | Nov 18, 2023 |
| Lenovo        | ThinkBook 16 G5+ ARP 21J... | Notebook    | [e5148f6b93](https://linux-hardware.org/?probe=e5148f6b93) | Nov 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [186bca6f10](https://linux-hardware.org/?probe=186bca6f10) | Nov 18, 2023 |
| Lenovo        | B5400 20278                 | Notebook    | [69336c15b9](https://linux-hardware.org/?probe=69336c15b9) | Nov 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5352f0e4f9](https://linux-hardware.org/?probe=5352f0e4f9) | Nov 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [67b231cfe0](https://linux-hardware.org/?probe=67b231cfe0) | Nov 18, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [8f5057710c](https://linux-hardware.org/?probe=8f5057710c) | Nov 18, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [f93730616e](https://linux-hardware.org/?probe=f93730616e) | Nov 18, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [da00d0b6ca](https://linux-hardware.org/?probe=da00d0b6ca) | Nov 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e551d74658](https://linux-hardware.org/?probe=e551d74658) | Nov 17, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [56b8d552fc](https://linux-hardware.org/?probe=56b8d552fc) | Nov 17, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [dd9cd5ea83](https://linux-hardware.org/?probe=dd9cd5ea83) | Nov 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5fa3bbac39](https://linux-hardware.org/?probe=5fa3bbac39) | Nov 17, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [753bf22a5f](https://linux-hardware.org/?probe=753bf22a5f) | Nov 17, 2023 |
| Dell          | Latitude 3410               | Notebook    | [edb19e1704](https://linux-hardware.org/?probe=edb19e1704) | Nov 17, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a8ac01af3d](https://linux-hardware.org/?probe=a8ac01af3d) | Nov 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [6518d0d83e](https://linux-hardware.org/?probe=6518d0d83e) | Nov 17, 2023 |
| Dell          | 0HGFJM A00                  | Desktop     | [7ef2b1b168](https://linux-hardware.org/?probe=7ef2b1b168) | Nov 17, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [644a0b97d3](https://linux-hardware.org/?probe=644a0b97d3) | Nov 16, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [8fd3066986](https://linux-hardware.org/?probe=8fd3066986) | Nov 16, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [5388f8cbdd](https://linux-hardware.org/?probe=5388f8cbdd) | Nov 16, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [0f53418be5](https://linux-hardware.org/?probe=0f53418be5) | Nov 16, 2023 |
| Dell          | 0PRR48 A01                  | Desktop     | [85839a8c00](https://linux-hardware.org/?probe=85839a8c00) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470 20HES04Q00    | Notebook    | [ebb179e02e](https://linux-hardware.org/?probe=ebb179e02e) | Nov 16, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [29dc31d4de](https://linux-hardware.org/?probe=29dc31d4de) | Nov 16, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0f5f7fb08d](https://linux-hardware.org/?probe=0f5f7fb08d) | Nov 16, 2023 |
| HP            | 802E                        | Desktop     | [9046cfa950](https://linux-hardware.org/?probe=9046cfa950) | Nov 16, 2023 |
| Dell          | G5 5505                     | Notebook    | [d764e0bb8a](https://linux-hardware.org/?probe=d764e0bb8a) | Nov 16, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [86f598c692](https://linux-hardware.org/?probe=86f598c692) | Nov 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [bc84c6feed](https://linux-hardware.org/?probe=bc84c6feed) | Nov 16, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [b612f7a489](https://linux-hardware.org/?probe=b612f7a489) | Nov 16, 2023 |
| Alienware     | m15 R6                      | Notebook    | [c341b25df2](https://linux-hardware.org/?probe=c341b25df2) | Nov 16, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [bd7e176e90](https://linux-hardware.org/?probe=bd7e176e90) | Nov 16, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [13b5345c35](https://linux-hardware.org/?probe=13b5345c35) | Nov 16, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [75a4902414](https://linux-hardware.org/?probe=75a4902414) | Nov 16, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [03c6bfd1ee](https://linux-hardware.org/?probe=03c6bfd1ee) | Nov 15, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [41ae79ffa6](https://linux-hardware.org/?probe=41ae79ffa6) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [166de89ec8](https://linux-hardware.org/?probe=166de89ec8) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [378bb9c07b](https://linux-hardware.org/?probe=378bb9c07b) | Nov 15, 2023 |
| Google        | Markarth                    | Notebook    | [5fb5241c23](https://linux-hardware.org/?probe=5fb5241c23) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [bceb77e476](https://linux-hardware.org/?probe=bceb77e476) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [fd4d64a274](https://linux-hardware.org/?probe=fd4d64a274) | Nov 15, 2023 |
| HP            | Spectre Pro x360 G2         | Convertible | [c2e9793535](https://linux-hardware.org/?probe=c2e9793535) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [0fae742aa3](https://linux-hardware.org/?probe=0fae742aa3) | Nov 15, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9113371a8d](https://linux-hardware.org/?probe=9113371a8d) | Nov 15, 2023 |
| Dell          | Latitude 3340               | Notebook    | [2b92bb812f](https://linux-hardware.org/?probe=2b92bb812f) | Nov 15, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [7725a67bda](https://linux-hardware.org/?probe=7725a67bda) | Nov 15, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [d643e4ee02](https://linux-hardware.org/?probe=d643e4ee02) | Nov 15, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [a5718f2f4d](https://linux-hardware.org/?probe=a5718f2f4d) | Nov 15, 2023 |
| HP            | 3647h                       | Desktop     | [9b0451eab9](https://linux-hardware.org/?probe=9b0451eab9) | Nov 15, 2023 |
| HP            | 3647h                       | Desktop     | [d6de3838ec](https://linux-hardware.org/?probe=d6de3838ec) | Nov 15, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [81fb4db1cc](https://linux-hardware.org/?probe=81fb4db1cc) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [340f007a69](https://linux-hardware.org/?probe=340f007a69) | Nov 14, 2023 |
| HP            | 158A                        | Desktop     | [b64a9c4033](https://linux-hardware.org/?probe=b64a9c4033) | Nov 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [4d7c838629](https://linux-hardware.org/?probe=4d7c838629) | Nov 14, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [0b16b45e10](https://linux-hardware.org/?probe=0b16b45e10) | Nov 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7a178e1a0f](https://linux-hardware.org/?probe=7a178e1a0f) | Nov 14, 2023 |
| Dell          | G3 3779                     | Notebook    | [af4af2b0b5](https://linux-hardware.org/?probe=af4af2b0b5) | Nov 14, 2023 |
| Dell          | G3 3779                     | Notebook    | [e48e3e3d67](https://linux-hardware.org/?probe=e48e3e3d67) | Nov 14, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [243bc51d12](https://linux-hardware.org/?probe=243bc51d12) | Nov 14, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [b7d9898316](https://linux-hardware.org/?probe=b7d9898316) | Nov 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b8e2bf284d](https://linux-hardware.org/?probe=b8e2bf284d) | Nov 13, 2023 |
| Lenovo        | 330B NOK                    | Mini pc     | [f720496c11](https://linux-hardware.org/?probe=f720496c11) | Nov 13, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [637f9b3da9](https://linux-hardware.org/?probe=637f9b3da9) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [f3d934ed44](https://linux-hardware.org/?probe=f3d934ed44) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ba805ada14](https://linux-hardware.org/?probe=ba805ada14) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [381c8b164d](https://linux-hardware.org/?probe=381c8b164d) | Nov 13, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [37b0caaf30](https://linux-hardware.org/?probe=37b0caaf30) | Nov 13, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [22ba69f09d](https://linux-hardware.org/?probe=22ba69f09d) | Nov 13, 2023 |
| Intel         | H61 V1.5                    | Desktop     | [798841e126](https://linux-hardware.org/?probe=798841e126) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [a3fe3d9ed8](https://linux-hardware.org/?probe=a3fe3d9ed8) | Nov 12, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [7c3fc962ca](https://linux-hardware.org/?probe=7c3fc962ca) | Nov 12, 2023 |
| AZW           | GTR V21                     | Desktop     | [8c7e39a466](https://linux-hardware.org/?probe=8c7e39a466) | Nov 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [656ba48c77](https://linux-hardware.org/?probe=656ba48c77) | Nov 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6fb9ac1dd2](https://linux-hardware.org/?probe=6fb9ac1dd2) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 42369N1       | Notebook    | [632121ae02](https://linux-hardware.org/?probe=632121ae02) | Nov 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9f68e8d365](https://linux-hardware.org/?probe=9f68e8d365) | Nov 12, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [b141c80561](https://linux-hardware.org/?probe=b141c80561) | Nov 12, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [f1f44353e2](https://linux-hardware.org/?probe=f1f44353e2) | Nov 12, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [61b583fe07](https://linux-hardware.org/?probe=61b583fe07) | Nov 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [51e8be0935](https://linux-hardware.org/?probe=51e8be0935) | Nov 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [bbf00de926](https://linux-hardware.org/?probe=bbf00de926) | Nov 12, 2023 |
| HP            | Pavilion g6                 | Notebook    | [e00bbf5062](https://linux-hardware.org/?probe=e00bbf5062) | Nov 12, 2023 |
| Dell          | 08YDFF A00                  | Desktop     | [4eee0e211a](https://linux-hardware.org/?probe=4eee0e211a) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4ba028b0e9](https://linux-hardware.org/?probe=4ba028b0e9) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a681b54073](https://linux-hardware.org/?probe=a681b54073) | Nov 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [569f3a5034](https://linux-hardware.org/?probe=569f3a5034) | Nov 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0ff417d90e](https://linux-hardware.org/?probe=0ff417d90e) | Nov 11, 2023 |
| AZW           | MINI S                      | Desktop     | [c7a46003d0](https://linux-hardware.org/?probe=c7a46003d0) | Nov 11, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [1792b41a0e](https://linux-hardware.org/?probe=1792b41a0e) | Nov 11, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [bad94e2ebe](https://linux-hardware.org/?probe=bad94e2ebe) | Nov 11, 2023 |
| MSI           | P55-GD65                    | Desktop     | [5a95aca3cc](https://linux-hardware.org/?probe=5a95aca3cc) | Nov 11, 2023 |
| Lenovo        | ThinkPad P16 Gen 2 21FAC... | Notebook    | [820f65395e](https://linux-hardware.org/?probe=820f65395e) | Nov 11, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [4f49f31e87](https://linux-hardware.org/?probe=4f49f31e87) | Nov 11, 2023 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [0483e390e3](https://linux-hardware.org/?probe=0483e390e3) | Nov 11, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [03007d4f6a](https://linux-hardware.org/?probe=03007d4f6a) | Nov 11, 2023 |
| Dell          | Latitude 7390               | Notebook    | [b1f996e81e](https://linux-hardware.org/?probe=b1f996e81e) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [4c24ca4aa2](https://linux-hardware.org/?probe=4c24ca4aa2) | Nov 11, 2023 |
| ASUSTek       | X202E                       | Notebook    | [b78da681e7](https://linux-hardware.org/?probe=b78da681e7) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [123d86a139](https://linux-hardware.org/?probe=123d86a139) | Nov 10, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b7ea934fcd](https://linux-hardware.org/?probe=b7ea934fcd) | Nov 10, 2023 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [dd73474667](https://linux-hardware.org/?probe=dd73474667) | Nov 10, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [5fb8105768](https://linux-hardware.org/?probe=5fb8105768) | Nov 10, 2023 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [aaca941b62](https://linux-hardware.org/?probe=aaca941b62) | Nov 10, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | Notebook    | [f2e379d36f](https://linux-hardware.org/?probe=f2e379d36f) | Nov 10, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [3bd9aacc85](https://linux-hardware.org/?probe=3bd9aacc85) | Nov 10, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [c997ccc4d2](https://linux-hardware.org/?probe=c997ccc4d2) | Nov 10, 2023 |
| System76      | Pangolin                    | Notebook    | [f71f405b6d](https://linux-hardware.org/?probe=f71f405b6d) | Nov 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [ebbeac415f](https://linux-hardware.org/?probe=ebbeac415f) | Nov 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [7c15ca35c4](https://linux-hardware.org/?probe=7c15ca35c4) | Nov 09, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [0172afec34](https://linux-hardware.org/?probe=0172afec34) | Nov 09, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | Notebook    | [47557dd574](https://linux-hardware.org/?probe=47557dd574) | Nov 09, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [0ffa68a85f](https://linux-hardware.org/?probe=0ffa68a85f) | Nov 09, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [4472ec34fa](https://linux-hardware.org/?probe=4472ec34fa) | Nov 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [e87d6b7612](https://linux-hardware.org/?probe=e87d6b7612) | Nov 09, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [a04987895a](https://linux-hardware.org/?probe=a04987895a) | Nov 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [656bd0c4c2](https://linux-hardware.org/?probe=656bd0c4c2) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [4af4346c2a](https://linux-hardware.org/?probe=4af4346c2a) | Nov 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [e73f300089](https://linux-hardware.org/?probe=e73f300089) | Nov 08, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [67a604ba54](https://linux-hardware.org/?probe=67a604ba54) | Nov 08, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [745cc9650d](https://linux-hardware.org/?probe=745cc9650d) | Nov 08, 2023 |
| Dell          | Latitude 7280               | Notebook    | [a91cab2bb9](https://linux-hardware.org/?probe=a91cab2bb9) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a48d1ad818](https://linux-hardware.org/?probe=a48d1ad818) | Nov 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f482f58c7c](https://linux-hardware.org/?probe=f482f58c7c) | Nov 08, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [02154de863](https://linux-hardware.org/?probe=02154de863) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [b5982ee614](https://linux-hardware.org/?probe=b5982ee614) | Nov 08, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ba5db231dd](https://linux-hardware.org/?probe=ba5db231dd) | Nov 08, 2023 |
| Dell          | Latitude 7280               | Notebook    | [22957cd62d](https://linux-hardware.org/?probe=22957cd62d) | Nov 08, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [42b79361a6](https://linux-hardware.org/?probe=42b79361a6) | Nov 08, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [c2ab637fa9](https://linux-hardware.org/?probe=c2ab637fa9) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [3cf76cfbda](https://linux-hardware.org/?probe=3cf76cfbda) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [598b5837e5](https://linux-hardware.org/?probe=598b5837e5) | Nov 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [ada9cf1c70](https://linux-hardware.org/?probe=ada9cf1c70) | Nov 07, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [88b8f4ff04](https://linux-hardware.org/?probe=88b8f4ff04) | Nov 07, 2023 |
| HP            | 83EE                        | Desktop     | [edba0a0b55](https://linux-hardware.org/?probe=edba0a0b55) | Nov 07, 2023 |
| HP            | 83EE                        | Desktop     | [d1910b3905](https://linux-hardware.org/?probe=d1910b3905) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [b9eabfe817](https://linux-hardware.org/?probe=b9eabfe817) | Nov 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [048559335e](https://linux-hardware.org/?probe=048559335e) | Nov 06, 2023 |
| HP            | 8750                        | Desktop     | [7f321e26b8](https://linux-hardware.org/?probe=7f321e26b8) | Nov 06, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [547c61e762](https://linux-hardware.org/?probe=547c61e762) | Nov 06, 2023 |
| Dell          | G15 5510                    | Notebook    | [270a41e12b](https://linux-hardware.org/?probe=270a41e12b) | Nov 06, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [1e2ba13164](https://linux-hardware.org/?probe=1e2ba13164) | Nov 06, 2023 |
| MSI           | B85M-E45                    | Desktop     | [a2b6c4ab44](https://linux-hardware.org/?probe=a2b6c4ab44) | Nov 06, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0009d8a468](https://linux-hardware.org/?probe=0009d8a468) | Nov 06, 2023 |
| ASRock        | H110M-ITX                   | Desktop     | [c384352141](https://linux-hardware.org/?probe=c384352141) | Nov 06, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9b0f4eeb46](https://linux-hardware.org/?probe=9b0f4eeb46) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cfef4c0b7](https://linux-hardware.org/?probe=5cfef4c0b7) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [f1d9fe0bb7](https://linux-hardware.org/?probe=f1d9fe0bb7) | Nov 06, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [8d789a3937](https://linux-hardware.org/?probe=8d789a3937) | Nov 06, 2023 |
| MSI           | Bravo 17 C7VF               | Notebook    | [5982277b4b](https://linux-hardware.org/?probe=5982277b4b) | Nov 06, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [07ef51bd31](https://linux-hardware.org/?probe=07ef51bd31) | Nov 05, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [3cedc8f704](https://linux-hardware.org/?probe=3cedc8f704) | Nov 05, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3f1419b0ea](https://linux-hardware.org/?probe=3f1419b0ea) | Nov 05, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [6407166dd5](https://linux-hardware.org/?probe=6407166dd5) | Nov 05, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [53f5c381aa](https://linux-hardware.org/?probe=53f5c381aa) | Nov 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [4b29646104](https://linux-hardware.org/?probe=4b29646104) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d74f909776](https://linux-hardware.org/?probe=d74f909776) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [c235d90592](https://linux-hardware.org/?probe=c235d90592) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [52a36f5268](https://linux-hardware.org/?probe=52a36f5268) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5832913981](https://linux-hardware.org/?probe=5832913981) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [4f6d5932fa](https://linux-hardware.org/?probe=4f6d5932fa) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [e95c10c89d](https://linux-hardware.org/?probe=e95c10c89d) | Nov 04, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [69cb1e7068](https://linux-hardware.org/?probe=69cb1e7068) | Nov 04, 2023 |
| Notebook      | N141CU                      | Notebook    | [8f817eeabf](https://linux-hardware.org/?probe=8f817eeabf) | Nov 04, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [0a0e80ef0f](https://linux-hardware.org/?probe=0a0e80ef0f) | Nov 04, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | Desktop     | [76acaae6cc](https://linux-hardware.org/?probe=76acaae6cc) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [34e4bd156f](https://linux-hardware.org/?probe=34e4bd156f) | Nov 04, 2023 |
| Gigabyte      | H470M K                     | Desktop     | [d69493b7d2](https://linux-hardware.org/?probe=d69493b7d2) | Nov 04, 2023 |
| Gigabyte      | H470M K                     | Desktop     | [80085c7047](https://linux-hardware.org/?probe=80085c7047) | Nov 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2d1116cd1b](https://linux-hardware.org/?probe=2d1116cd1b) | Nov 04, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2b389d48e1](https://linux-hardware.org/?probe=2b389d48e1) | Nov 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [a6ce21c9de](https://linux-hardware.org/?probe=a6ce21c9de) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [bc3444ed2f](https://linux-hardware.org/?probe=bc3444ed2f) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3c1e4ea8bf](https://linux-hardware.org/?probe=3c1e4ea8bf) | Nov 04, 2023 |
| Lenovo        | IdeaPad 710S Plus-13ISK ... | Notebook    | [f143d09ba7](https://linux-hardware.org/?probe=f143d09ba7) | Nov 04, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [ba8e987366](https://linux-hardware.org/?probe=ba8e987366) | Nov 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [d17e6059bb](https://linux-hardware.org/?probe=d17e6059bb) | Nov 03, 2023 |
| HP            | OMEN by Laptop 17-ck2xxx    | Notebook    | [e34a0ab109](https://linux-hardware.org/?probe=e34a0ab109) | Nov 03, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9501d6d6cf](https://linux-hardware.org/?probe=9501d6d6cf) | Nov 03, 2023 |
| Dell          | Latitude 7280               | Notebook    | [b795f0157b](https://linux-hardware.org/?probe=b795f0157b) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2ac0d5a547](https://linux-hardware.org/?probe=2ac0d5a547) | Nov 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [bc3b3daf33](https://linux-hardware.org/?probe=bc3b3daf33) | Nov 03, 2023 |
| Dell          | Latitude 9330               | Convertible | [d4597194bb](https://linux-hardware.org/?probe=d4597194bb) | Nov 03, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [9ea1c674f9](https://linux-hardware.org/?probe=9ea1c674f9) | Nov 03, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7aa3982cb4](https://linux-hardware.org/?probe=7aa3982cb4) | Nov 03, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [9cabd6fd2c](https://linux-hardware.org/?probe=9cabd6fd2c) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [3414d178f2](https://linux-hardware.org/?probe=3414d178f2) | Nov 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [97348209dd](https://linux-hardware.org/?probe=97348209dd) | Nov 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d17a8bc08a](https://linux-hardware.org/?probe=d17a8bc08a) | Nov 02, 2023 |
| Dell          | Latitude E6330              | Notebook    | [b31f60152f](https://linux-hardware.org/?probe=b31f60152f) | Nov 02, 2023 |
| Samsung       | 750XDA                      | Notebook    | [130a1273e5](https://linux-hardware.org/?probe=130a1273e5) | Nov 02, 2023 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b596813aeb](https://linux-hardware.org/?probe=b596813aeb) | Nov 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ee2512ba0](https://linux-hardware.org/?probe=3ee2512ba0) | Nov 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [2c454d7632](https://linux-hardware.org/?probe=2c454d7632) | Nov 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [c7d2d860fb](https://linux-hardware.org/?probe=c7d2d860fb) | Nov 02, 2023 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [4ba182f0d5](https://linux-hardware.org/?probe=4ba182f0d5) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1fd433ec1e](https://linux-hardware.org/?probe=1fd433ec1e) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [993d985e9e](https://linux-hardware.org/?probe=993d985e9e) | Nov 01, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [9fff1dc94c](https://linux-hardware.org/?probe=9fff1dc94c) | Nov 01, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b16724db59](https://linux-hardware.org/?probe=b16724db59) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3c04d0213b](https://linux-hardware.org/?probe=3c04d0213b) | Nov 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [6afebfd732](https://linux-hardware.org/?probe=6afebfd732) | Nov 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [be72cba293](https://linux-hardware.org/?probe=be72cba293) | Nov 01, 2023 |
| Dell          | 006K82 A00                  | Desktop     | [f8c521f2f6](https://linux-hardware.org/?probe=f8c521f2f6) | Nov 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1965aca64](https://linux-hardware.org/?probe=d1965aca64) | Nov 01, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1bd48815fe](https://linux-hardware.org/?probe=1bd48815fe) | Nov 01, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [301a117426](https://linux-hardware.org/?probe=301a117426) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [ba593f267b](https://linux-hardware.org/?probe=ba593f267b) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [56fe3d964b](https://linux-hardware.org/?probe=56fe3d964b) | Nov 01, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [460c9255bd](https://linux-hardware.org/?probe=460c9255bd) | Nov 01, 2023 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [a01ac98915](https://linux-hardware.org/?probe=a01ac98915) | Oct 31, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [d271d2ae41](https://linux-hardware.org/?probe=d271d2ae41) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [446efaf1bb](https://linux-hardware.org/?probe=446efaf1bb) | Oct 31, 2023 |
| ASUSTek       | F5N                         | Notebook    | [8da324b4fa](https://linux-hardware.org/?probe=8da324b4fa) | Oct 31, 2023 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [8e86103e06](https://linux-hardware.org/?probe=8e86103e06) | Oct 31, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abebb8beea](https://linux-hardware.org/?probe=abebb8beea) | Oct 31, 2023 |
| Samsung       | 750XED                      | Notebook    | [9dab50e37e](https://linux-hardware.org/?probe=9dab50e37e) | Oct 31, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [40f30de33b](https://linux-hardware.org/?probe=40f30de33b) | Oct 31, 2023 |
| Dell          | G15 5515                    | Notebook    | [c59e97ba9e](https://linux-hardware.org/?probe=c59e97ba9e) | Oct 31, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [2b4315885f](https://linux-hardware.org/?probe=2b4315885f) | Oct 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [90172d9cef](https://linux-hardware.org/?probe=90172d9cef) | Oct 31, 2023 |
| Dell          | Vostro 3549                 | Notebook    | [259c646ecb](https://linux-hardware.org/?probe=259c646ecb) | Oct 31, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [fb56165b30](https://linux-hardware.org/?probe=fb56165b30) | Oct 31, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [1323e3ad04](https://linux-hardware.org/?probe=1323e3ad04) | Oct 31, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [26533c338a](https://linux-hardware.org/?probe=26533c338a) | Oct 31, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6779e74408](https://linux-hardware.org/?probe=6779e74408) | Oct 31, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df43f845a1](https://linux-hardware.org/?probe=df43f845a1) | Oct 31, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [85cb35fdc6](https://linux-hardware.org/?probe=85cb35fdc6) | Oct 31, 2023 |
| HP            | 86F1 10100                  | All in one  | [d3079638ae](https://linux-hardware.org/?probe=d3079638ae) | Oct 31, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [38b70999b9](https://linux-hardware.org/?probe=38b70999b9) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [e0971c3b56](https://linux-hardware.org/?probe=e0971c3b56) | Oct 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ef307df799](https://linux-hardware.org/?probe=ef307df799) | Oct 31, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [01ce498c44](https://linux-hardware.org/?probe=01ce498c44) | Oct 30, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [000230db12](https://linux-hardware.org/?probe=000230db12) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ab5cef69c3](https://linux-hardware.org/?probe=ab5cef69c3) | Oct 30, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [17dd2ce988](https://linux-hardware.org/?probe=17dd2ce988) | Oct 30, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [5f8cf197d5](https://linux-hardware.org/?probe=5f8cf197d5) | Oct 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [941ca289ce](https://linux-hardware.org/?probe=941ca289ce) | Oct 30, 2023 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [47dbfa475a](https://linux-hardware.org/?probe=47dbfa475a) | Oct 30, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [2b883f993f](https://linux-hardware.org/?probe=2b883f993f) | Oct 30, 2023 |
| MSI           | GF75 Thin 10SC              | Notebook    | [7aa47ebfa1](https://linux-hardware.org/?probe=7aa47ebfa1) | Oct 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59f0a72f7b](https://linux-hardware.org/?probe=59f0a72f7b) | Oct 29, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [eeddd1e3e1](https://linux-hardware.org/?probe=eeddd1e3e1) | Oct 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE13    | Notebook    | [28a8f59777](https://linux-hardware.org/?probe=28a8f59777) | Oct 29, 2023 |
| HP            | 802E                        | Desktop     | [a57f8d5afa](https://linux-hardware.org/?probe=a57f8d5afa) | Oct 29, 2023 |
| Lenovo        | ThinkPad X250 20CMS04J00    | Notebook    | [773098b9e5](https://linux-hardware.org/?probe=773098b9e5) | Oct 29, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [85e507b8b2](https://linux-hardware.org/?probe=85e507b8b2) | Oct 29, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [b83310ffb8](https://linux-hardware.org/?probe=b83310ffb8) | Oct 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [d690fa8f27](https://linux-hardware.org/?probe=d690fa8f27) | Oct 29, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [e34ea8701a](https://linux-hardware.org/?probe=e34ea8701a) | Oct 28, 2023 |
| ASRock        | B550M-C                     | Notebook    | [51c187d805](https://linux-hardware.org/?probe=51c187d805) | Oct 28, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [df6ef51245](https://linux-hardware.org/?probe=df6ef51245) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b65d7d3b4a](https://linux-hardware.org/?probe=b65d7d3b4a) | Oct 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [bc8c6e67a9](https://linux-hardware.org/?probe=bc8c6e67a9) | Oct 28, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [60372b59fe](https://linux-hardware.org/?probe=60372b59fe) | Oct 28, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | Notebook    | [07a3c8eea8](https://linux-hardware.org/?probe=07a3c8eea8) | Oct 28, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | Notebook    | [906ed51ecf](https://linux-hardware.org/?probe=906ed51ecf) | Oct 27, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | Notebook    | [f74328fd58](https://linux-hardware.org/?probe=f74328fd58) | Oct 27, 2023 |
| HONOR         | BOD-WXX9                    | Notebook    | [6de8b3afda](https://linux-hardware.org/?probe=6de8b3afda) | Oct 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [334f8582b0](https://linux-hardware.org/?probe=334f8582b0) | Oct 27, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [5e0942e6b0](https://linux-hardware.org/?probe=5e0942e6b0) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bbba3e21c7](https://linux-hardware.org/?probe=bbba3e21c7) | Oct 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JKC... | Notebook    | [c9ba633d37](https://linux-hardware.org/?probe=c9ba633d37) | Oct 27, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [1cd579935b](https://linux-hardware.org/?probe=1cd579935b) | Oct 27, 2023 |
| Dell          | Latitude 5430               | Notebook    | [af33081c9b](https://linux-hardware.org/?probe=af33081c9b) | Oct 27, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [56f2576af1](https://linux-hardware.org/?probe=56f2576af1) | Oct 27, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [47336d64a9](https://linux-hardware.org/?probe=47336d64a9) | Oct 27, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [7ac5ac2ae2](https://linux-hardware.org/?probe=7ac5ac2ae2) | Oct 27, 2023 |
| LG Electro... | 15Z95N-G.AAC6U1             | Notebook    | [7f2e8a07de](https://linux-hardware.org/?probe=7f2e8a07de) | Oct 27, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [298718536d](https://linux-hardware.org/?probe=298718536d) | Oct 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [ae3bbe4ecf](https://linux-hardware.org/?probe=ae3bbe4ecf) | Oct 26, 2023 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [c8c1fcb418](https://linux-hardware.org/?probe=c8c1fcb418) | Oct 26, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [4d76763d2d](https://linux-hardware.org/?probe=4d76763d2d) | Oct 26, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8f2a8dec3a](https://linux-hardware.org/?probe=8f2a8dec3a) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [e3c1de1472](https://linux-hardware.org/?probe=e3c1de1472) | Oct 26, 2023 |
| HP            | 8653 A                      | Desktop     | [07aae59bf1](https://linux-hardware.org/?probe=07aae59bf1) | Oct 26, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [37eda24908](https://linux-hardware.org/?probe=37eda24908) | Oct 26, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [7277bcd3bc](https://linux-hardware.org/?probe=7277bcd3bc) | Oct 26, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | Notebook    | [cbba790d59](https://linux-hardware.org/?probe=cbba790d59) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [336fa07e6a](https://linux-hardware.org/?probe=336fa07e6a) | Oct 26, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [b74c61d287](https://linux-hardware.org/?probe=b74c61d287) | Oct 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b75faeaf8a](https://linux-hardware.org/?probe=b75faeaf8a) | Oct 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | Notebook    | [0ed2bd399f](https://linux-hardware.org/?probe=0ed2bd399f) | Oct 25, 2023 |
| BBEN          | Cherry Trail CR             | Mini pc     | [a37982a5e5](https://linux-hardware.org/?probe=a37982a5e5) | Oct 25, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [824215ab50](https://linux-hardware.org/?probe=824215ab50) | Oct 25, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [7107e2ed21](https://linux-hardware.org/?probe=7107e2ed21) | Oct 25, 2023 |
| Dell          | Latitude 9430               | Convertible | [5e0239fb7c](https://linux-hardware.org/?probe=5e0239fb7c) | Oct 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [50abb592dd](https://linux-hardware.org/?probe=50abb592dd) | Oct 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d69762902a](https://linux-hardware.org/?probe=d69762902a) | Oct 25, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [8f09f37e41](https://linux-hardware.org/?probe=8f09f37e41) | Oct 25, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [1fde726024](https://linux-hardware.org/?probe=1fde726024) | Oct 25, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f88a2686e9](https://linux-hardware.org/?probe=f88a2686e9) | Oct 25, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [a25c5e5185](https://linux-hardware.org/?probe=a25c5e5185) | Oct 25, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e51b06f086](https://linux-hardware.org/?probe=e51b06f086) | Oct 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [97f4660a4d](https://linux-hardware.org/?probe=97f4660a4d) | Oct 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [268b32d9bf](https://linux-hardware.org/?probe=268b32d9bf) | Oct 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [3907a62f64](https://linux-hardware.org/?probe=3907a62f64) | Oct 24, 2023 |
| AZW           | GTR V21                     | Desktop     | [beb87ff047](https://linux-hardware.org/?probe=beb87ff047) | Oct 24, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [332b714861](https://linux-hardware.org/?probe=332b714861) | Oct 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [87102526a5](https://linux-hardware.org/?probe=87102526a5) | Oct 24, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [24a664955f](https://linux-hardware.org/?probe=24a664955f) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [c931b1ef73](https://linux-hardware.org/?probe=c931b1ef73) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G533QM_G533QM     | Notebook    | [a4c0d7be24](https://linux-hardware.org/?probe=a4c0d7be24) | Oct 23, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [673f62810a](https://linux-hardware.org/?probe=673f62810a) | Oct 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f06b99b2e](https://linux-hardware.org/?probe=4f06b99b2e) | Oct 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [d4d7110981](https://linux-hardware.org/?probe=d4d7110981) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [817e0c8438](https://linux-hardware.org/?probe=817e0c8438) | Oct 23, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | Notebook    | [399c501d43](https://linux-hardware.org/?probe=399c501d43) | Oct 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [62ca63bc89](https://linux-hardware.org/?probe=62ca63bc89) | Oct 23, 2023 |
| Dell          | Latitude 5430               | Notebook    | [8d552380c4](https://linux-hardware.org/?probe=8d552380c4) | Oct 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f9efd677fe](https://linux-hardware.org/?probe=f9efd677fe) | Oct 23, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [60402f4ad8](https://linux-hardware.org/?probe=60402f4ad8) | Oct 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [d04399e8fd](https://linux-hardware.org/?probe=d04399e8fd) | Oct 23, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3dcdf62e73](https://linux-hardware.org/?probe=3dcdf62e73) | Oct 22, 2023 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [37680f1ed6](https://linux-hardware.org/?probe=37680f1ed6) | Oct 22, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [9538ff99bf](https://linux-hardware.org/?probe=9538ff99bf) | Oct 22, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2b88710042](https://linux-hardware.org/?probe=2b88710042) | Oct 22, 2023 |
| Gigabyte      | B660 AORUS MASTER DDR4      | Desktop     | [2157dd6b76](https://linux-hardware.org/?probe=2157dd6b76) | Oct 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [e3c5d45e2a](https://linux-hardware.org/?probe=e3c5d45e2a) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | Notebook    | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [2ee834d08a](https://linux-hardware.org/?probe=2ee834d08a) | Oct 22, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [7c81d548d6](https://linux-hardware.org/?probe=7c81d548d6) | Oct 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [b8a154c0f6](https://linux-hardware.org/?probe=b8a154c0f6) | Oct 22, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [f3cde0eac8](https://linux-hardware.org/?probe=f3cde0eac8) | Oct 22, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ed6b4ba6e8](https://linux-hardware.org/?probe=ed6b4ba6e8) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [f204c7469c](https://linux-hardware.org/?probe=f204c7469c) | Oct 21, 2023 |
| Dell          | Precision 5520              | Notebook    | [79b5c73851](https://linux-hardware.org/?probe=79b5c73851) | Oct 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7ddf7a94fd](https://linux-hardware.org/?probe=7ddf7a94fd) | Oct 21, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a7f899353b](https://linux-hardware.org/?probe=a7f899353b) | Oct 21, 2023 |
| HP            | 250 15.6 inch G10 Notebo... | Notebook    | [f5f8e6f37d](https://linux-hardware.org/?probe=f5f8e6f37d) | Oct 21, 2023 |
| Dell          | Latitude D830               | Notebook    | [53cbc541d2](https://linux-hardware.org/?probe=53cbc541d2) | Oct 20, 2023 |
| Avell High... | B.ON                        | Notebook    | [7f8ce9da76](https://linux-hardware.org/?probe=7f8ce9da76) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [7323684232](https://linux-hardware.org/?probe=7323684232) | Oct 20, 2023 |
| Dell          | Vostro 3300                 | Notebook    | [827b95e65c](https://linux-hardware.org/?probe=827b95e65c) | Oct 20, 2023 |
| ECS           | G31T-M7                     | Desktop     | [297db99cc3](https://linux-hardware.org/?probe=297db99cc3) | Oct 20, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [46d5d338b3](https://linux-hardware.org/?probe=46d5d338b3) | Oct 20, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e5b7455426](https://linux-hardware.org/?probe=e5b7455426) | Oct 19, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a6514e61a](https://linux-hardware.org/?probe=3a6514e61a) | Oct 19, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [41635aba8a](https://linux-hardware.org/?probe=41635aba8a) | Oct 19, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [a370d171d1](https://linux-hardware.org/?probe=a370d171d1) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [71ffea0397](https://linux-hardware.org/?probe=71ffea0397) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [9ab2c722a5](https://linux-hardware.org/?probe=9ab2c722a5) | Oct 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [94cd063a64](https://linux-hardware.org/?probe=94cd063a64) | Oct 19, 2023 |
| ASRock        | N100M                       | Desktop     | [a52836d33c](https://linux-hardware.org/?probe=a52836d33c) | Oct 19, 2023 |
| Dell          | Latitude E7270              | Notebook    | [673245c691](https://linux-hardware.org/?probe=673245c691) | Oct 19, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [b1f1e05664](https://linux-hardware.org/?probe=b1f1e05664) | Oct 19, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [6a2e115b95](https://linux-hardware.org/?probe=6a2e115b95) | Oct 18, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6e17195f7d](https://linux-hardware.org/?probe=6e17195f7d) | Oct 18, 2023 |
| AXDIA Inte... | PRIMO WIN 10                | Tablet      | [50f89c1f2c](https://linux-hardware.org/?probe=50f89c1f2c) | Oct 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [f25a7d5b9e](https://linux-hardware.org/?probe=f25a7d5b9e) | Oct 18, 2023 |
| Dell          | 0MWYPT A02                  | Desktop     | [c0e68da51a](https://linux-hardware.org/?probe=c0e68da51a) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [57dbbcb9f3](https://linux-hardware.org/?probe=57dbbcb9f3) | Oct 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8543bed1b3](https://linux-hardware.org/?probe=8543bed1b3) | Oct 17, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [11d2b5b9c2](https://linux-hardware.org/?probe=11d2b5b9c2) | Oct 17, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8d289561bf](https://linux-hardware.org/?probe=8d289561bf) | Oct 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [843098c658](https://linux-hardware.org/?probe=843098c658) | Oct 17, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [295c6b08bd](https://linux-hardware.org/?probe=295c6b08bd) | Oct 17, 2023 |
| Dell          | Latitude 7300               | Notebook    | [e68476c5ee](https://linux-hardware.org/?probe=e68476c5ee) | Oct 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3c93567751](https://linux-hardware.org/?probe=3c93567751) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [19d60d452f](https://linux-hardware.org/?probe=19d60d452f) | Oct 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [b962ac1dff](https://linux-hardware.org/?probe=b962ac1dff) | Oct 17, 2023 |
| Dell          | XPS 9315                    | Notebook    | [e629bbd153](https://linux-hardware.org/?probe=e629bbd153) | Oct 16, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a0b5099438](https://linux-hardware.org/?probe=a0b5099438) | Oct 16, 2023 |
| Dell          | Latitude 7424 Rugged Ext... | Notebook    | [5e2983dfb6](https://linux-hardware.org/?probe=5e2983dfb6) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [e66f442843](https://linux-hardware.org/?probe=e66f442843) | Oct 16, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [0dcdd0a6a6](https://linux-hardware.org/?probe=0dcdd0a6a6) | Oct 16, 2023 |
| BY OEM        | ZRD1103                     | Desktop     | [1f638b4369](https://linux-hardware.org/?probe=1f638b4369) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [eab86d1cc0](https://linux-hardware.org/?probe=eab86d1cc0) | Oct 16, 2023 |
| Dell          | Precision M6700             | Notebook    | [2fb2e2e9a5](https://linux-hardware.org/?probe=2fb2e2e9a5) | Oct 16, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [c78d74d584](https://linux-hardware.org/?probe=c78d74d584) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [7f9e09a9e1](https://linux-hardware.org/?probe=7f9e09a9e1) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [2571e4fd1b](https://linux-hardware.org/?probe=2571e4fd1b) | Oct 16, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f7b210b108](https://linux-hardware.org/?probe=f7b210b108) | Oct 16, 2023 |
| Dell          | Precision 3530              | Notebook    | [79e1f32ab8](https://linux-hardware.org/?probe=79e1f32ab8) | Oct 16, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [eaff1b458a](https://linux-hardware.org/?probe=eaff1b458a) | Oct 15, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [81cbdd66c8](https://linux-hardware.org/?probe=81cbdd66c8) | Oct 15, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [ba4661ac35](https://linux-hardware.org/?probe=ba4661ac35) | Oct 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a9438a93a7](https://linux-hardware.org/?probe=a9438a93a7) | Oct 15, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [97a3c4d92d](https://linux-hardware.org/?probe=97a3c4d92d) | Oct 15, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [374a5bf116](https://linux-hardware.org/?probe=374a5bf116) | Oct 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [585c33a966](https://linux-hardware.org/?probe=585c33a966) | Oct 15, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [086ecfefb8](https://linux-hardware.org/?probe=086ecfefb8) | Oct 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [33173dac85](https://linux-hardware.org/?probe=33173dac85) | Oct 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [49ffe8b6c5](https://linux-hardware.org/?probe=49ffe8b6c5) | Oct 14, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [02958738fb](https://linux-hardware.org/?probe=02958738fb) | Oct 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | Notebook    | [e9d04fdd59](https://linux-hardware.org/?probe=e9d04fdd59) | Oct 14, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [ab093317ba](https://linux-hardware.org/?probe=ab093317ba) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [5584acb2f0](https://linux-hardware.org/?probe=5584acb2f0) | Oct 14, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [c50573f4ae](https://linux-hardware.org/?probe=c50573f4ae) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [4015286a79](https://linux-hardware.org/?probe=4015286a79) | Oct 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [12de4c5026](https://linux-hardware.org/?probe=12de4c5026) | Oct 14, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40731b6ac7](https://linux-hardware.org/?probe=40731b6ac7) | Oct 14, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [0702e52c02](https://linux-hardware.org/?probe=0702e52c02) | Oct 14, 2023 |
| Acer          | Aspire C24-963              | All in one  | [2e9ddbb840](https://linux-hardware.org/?probe=2e9ddbb840) | Oct 13, 2023 |
| Sony          | VPCEB15EL                   | Notebook    | [f7a3de3793](https://linux-hardware.org/?probe=f7a3de3793) | Oct 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [08a6026b21](https://linux-hardware.org/?probe=08a6026b21) | Oct 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [3d63dd4590](https://linux-hardware.org/?probe=3d63dd4590) | Oct 13, 2023 |
| Acer          | Aspire E5-523               | Notebook    | [e45e982b6e](https://linux-hardware.org/?probe=e45e982b6e) | Oct 13, 2023 |
| ASRock        | X370 Killer Sli             | Desktop     | [7cc4b0e44f](https://linux-hardware.org/?probe=7cc4b0e44f) | Oct 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [c97af886ef](https://linux-hardware.org/?probe=c97af886ef) | Oct 12, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [32a4a9380e](https://linux-hardware.org/?probe=32a4a9380e) | Oct 12, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [541e679856](https://linux-hardware.org/?probe=541e679856) | Oct 12, 2023 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [e7252be8a1](https://linux-hardware.org/?probe=e7252be8a1) | Oct 12, 2023 |
| Dell          | G3 3500                     | Notebook    | [1f975cc52a](https://linux-hardware.org/?probe=1f975cc52a) | Oct 12, 2023 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [1328071174](https://linux-hardware.org/?probe=1328071174) | Oct 12, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d5040f4ca4](https://linux-hardware.org/?probe=d5040f4ca4) | Oct 12, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [88057db3aa](https://linux-hardware.org/?probe=88057db3aa) | Oct 11, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [6a0e699ccc](https://linux-hardware.org/?probe=6a0e699ccc) | Oct 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [904d65b1c0](https://linux-hardware.org/?probe=904d65b1c0) | Oct 11, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [81409b14c4](https://linux-hardware.org/?probe=81409b14c4) | Oct 11, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [68372adfc5](https://linux-hardware.org/?probe=68372adfc5) | Oct 10, 2023 |
| ASUSTek       | S550CM                      | Notebook    | [ad1b08de66](https://linux-hardware.org/?probe=ad1b08de66) | Oct 10, 2023 |
| HP            | Notebook                    | Notebook    | [efd1dac9ef](https://linux-hardware.org/?probe=efd1dac9ef) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [908a750a93](https://linux-hardware.org/?probe=908a750a93) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [10b2d6465f](https://linux-hardware.org/?probe=10b2d6465f) | Oct 10, 2023 |
| Dell          | Latitude E5440              | Notebook    | [2f6ed33823](https://linux-hardware.org/?probe=2f6ed33823) | Oct 10, 2023 |
| Dell          | Latitude E5440              | Notebook    | [90b9b12b1b](https://linux-hardware.org/?probe=90b9b12b1b) | Oct 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c397035651](https://linux-hardware.org/?probe=c397035651) | Oct 10, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [3bb1bed686](https://linux-hardware.org/?probe=3bb1bed686) | Oct 09, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [f9bafdf396](https://linux-hardware.org/?probe=f9bafdf396) | Oct 09, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [6e8b2311e4](https://linux-hardware.org/?probe=6e8b2311e4) | Oct 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [d739639932](https://linux-hardware.org/?probe=d739639932) | Oct 09, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [341fc3d0f1](https://linux-hardware.org/?probe=341fc3d0f1) | Oct 09, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [beac8a6b4d](https://linux-hardware.org/?probe=beac8a6b4d) | Oct 09, 2023 |
| ASRock        | X370 Killer Sli             | Desktop     | [d90cde5a73](https://linux-hardware.org/?probe=d90cde5a73) | Oct 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29c7192a14](https://linux-hardware.org/?probe=29c7192a14) | Oct 08, 2023 |
| Dell          | Latitude 3440               | Notebook    | [88a0ec8369](https://linux-hardware.org/?probe=88a0ec8369) | Oct 08, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3d6601e877](https://linux-hardware.org/?probe=3d6601e877) | Oct 08, 2023 |
| Dell          | Latitude 7430               | Notebook    | [1de7d3085b](https://linux-hardware.org/?probe=1de7d3085b) | Oct 08, 2023 |
| HP            | Notebook                    | Notebook    | [a181ec12af](https://linux-hardware.org/?probe=a181ec12af) | Oct 08, 2023 |
| HP            | Notebook                    | Notebook    | [039a70e9ce](https://linux-hardware.org/?probe=039a70e9ce) | Oct 07, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [3f3879060f](https://linux-hardware.org/?probe=3f3879060f) | Oct 07, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [93e298660d](https://linux-hardware.org/?probe=93e298660d) | Oct 07, 2023 |
| Dell          | Latitude 9330               | Convertible | [a2b0fe0523](https://linux-hardware.org/?probe=a2b0fe0523) | Oct 07, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [1423f1793b](https://linux-hardware.org/?probe=1423f1793b) | Oct 07, 2023 |
| Lenovo        | 370A SDK0J40709 WIN 3259... | Desktop     | [38c0c97684](https://linux-hardware.org/?probe=38c0c97684) | Oct 07, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [590fa0428f](https://linux-hardware.org/?probe=590fa0428f) | Oct 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [80b914414e](https://linux-hardware.org/?probe=80b914414e) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [40c01d2bf5](https://linux-hardware.org/?probe=40c01d2bf5) | Oct 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d8d241531e](https://linux-hardware.org/?probe=d8d241531e) | Oct 07, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [b30fe669c6](https://linux-hardware.org/?probe=b30fe669c6) | Oct 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [13d4e4c49f](https://linux-hardware.org/?probe=13d4e4c49f) | Oct 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [0354977d6c](https://linux-hardware.org/?probe=0354977d6c) | Oct 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [faea5bdeba](https://linux-hardware.org/?probe=faea5bdeba) | Oct 07, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [446c6847c3](https://linux-hardware.org/?probe=446c6847c3) | Oct 06, 2023 |
| HONOR         | FRI-HXX                     | Notebook    | [fd2a01c055](https://linux-hardware.org/?probe=fd2a01c055) | Oct 06, 2023 |
| HP            | 255 G4                      | Notebook    | [7097fff4ee](https://linux-hardware.org/?probe=7097fff4ee) | Oct 06, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [192654dc77](https://linux-hardware.org/?probe=192654dc77) | Oct 06, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [058c6a0ee6](https://linux-hardware.org/?probe=058c6a0ee6) | Oct 06, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9dc2fd3247](https://linux-hardware.org/?probe=9dc2fd3247) | Oct 06, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [425aa2b0f7](https://linux-hardware.org/?probe=425aa2b0f7) | Oct 05, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [39b9855097](https://linux-hardware.org/?probe=39b9855097) | Oct 05, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [74bb875f9f](https://linux-hardware.org/?probe=74bb875f9f) | Oct 05, 2023 |
| Acidanther... | MacBookPro16,4              | Notebook    | [c40356b94d](https://linux-hardware.org/?probe=c40356b94d) | Oct 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [e23d98e73b](https://linux-hardware.org/?probe=e23d98e73b) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [947c66cb1f](https://linux-hardware.org/?probe=947c66cb1f) | Oct 05, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [02ff66cc0c](https://linux-hardware.org/?probe=02ff66cc0c) | Oct 05, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [43dfd73b17](https://linux-hardware.org/?probe=43dfd73b17) | Oct 04, 2023 |
| Timi          | A30                         | Notebook    | [36d352fb7f](https://linux-hardware.org/?probe=36d352fb7f) | Oct 04, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3639fedec4](https://linux-hardware.org/?probe=3639fedec4) | Oct 04, 2023 |
| Positivo      | S14BW01                     | Notebook    | [3027fc7d9b](https://linux-hardware.org/?probe=3027fc7d9b) | Oct 04, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [ef154408cf](https://linux-hardware.org/?probe=ef154408cf) | Oct 04, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [d034b84815](https://linux-hardware.org/?probe=d034b84815) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [18c399ea1e](https://linux-hardware.org/?probe=18c399ea1e) | Oct 04, 2023 |
| Dell          | 06H91J A00                  | All in one  | [5d6d98d8ef](https://linux-hardware.org/?probe=5d6d98d8ef) | Oct 03, 2023 |
| HP            | Pavilion g7                 | Notebook    | [ec5cf4fb00](https://linux-hardware.org/?probe=ec5cf4fb00) | Oct 03, 2023 |
| Dell          | Latitude E7440              | Notebook    | [3cb4fc2857](https://linux-hardware.org/?probe=3cb4fc2857) | Oct 03, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [5276b99f12](https://linux-hardware.org/?probe=5276b99f12) | Oct 03, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [50f7cba770](https://linux-hardware.org/?probe=50f7cba770) | Oct 03, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [34d3a3bd47](https://linux-hardware.org/?probe=34d3a3bd47) | Oct 03, 2023 |
| Dell          | 0P0MXR A00                  | Desktop     | [06af26dae3](https://linux-hardware.org/?probe=06af26dae3) | Oct 03, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ab5cf455ba](https://linux-hardware.org/?probe=ab5cf455ba) | Oct 03, 2023 |
| IP3 Tech      | IB8                         | Desktop     | [ca4d58a353](https://linux-hardware.org/?probe=ca4d58a353) | Oct 03, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c5223b1e21](https://linux-hardware.org/?probe=c5223b1e21) | Oct 02, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [09b97f9681](https://linux-hardware.org/?probe=09b97f9681) | Oct 02, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [b0b5262c87](https://linux-hardware.org/?probe=b0b5262c87) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | Notebook    | [11d6cad851](https://linux-hardware.org/?probe=11d6cad851) | Oct 02, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [0620cf8cd6](https://linux-hardware.org/?probe=0620cf8cd6) | Oct 02, 2023 |
| ASRock        | B660M-C                     | Desktop     | [c4ef9b73c9](https://linux-hardware.org/?probe=c4ef9b73c9) | Oct 01, 2023 |
| HP            | ProBook 6560b               | Notebook    | [ea59e8557f](https://linux-hardware.org/?probe=ea59e8557f) | Oct 01, 2023 |
| Sony          | SVF1421PSGB                 | Notebook    | [84a0c8ea9b](https://linux-hardware.org/?probe=84a0c8ea9b) | Oct 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7109a8a11b](https://linux-hardware.org/?probe=7109a8a11b) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6801ddb23b](https://linux-hardware.org/?probe=6801ddb23b) | Oct 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [76401b3ca2](https://linux-hardware.org/?probe=76401b3ca2) | Oct 01, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [5ee355215f](https://linux-hardware.org/?probe=5ee355215f) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [b85781f0d8](https://linux-hardware.org/?probe=b85781f0d8) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef74c51c65](https://linux-hardware.org/?probe=ef74c51c65) | Oct 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [493a83e70a](https://linux-hardware.org/?probe=493a83e70a) | Sep 30, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [0fad85dfc9](https://linux-hardware.org/?probe=0fad85dfc9) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6ee0910511](https://linux-hardware.org/?probe=6ee0910511) | Sep 30, 2023 |
| HP            | ProBook 6560b               | Notebook    | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [caa5ce0b99](https://linux-hardware.org/?probe=caa5ce0b99) | Sep 29, 2023 |
| eMachines     | eME732Z                     | Notebook    | [ba03824830](https://linux-hardware.org/?probe=ba03824830) | Sep 29, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [30268d41d2](https://linux-hardware.org/?probe=30268d41d2) | Sep 29, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [0536b81a43](https://linux-hardware.org/?probe=0536b81a43) | Sep 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [eef8975f1e](https://linux-hardware.org/?probe=eef8975f1e) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6d725a3ede](https://linux-hardware.org/?probe=6d725a3ede) | Sep 29, 2023 |
| Google        | Lindar                      | Notebook    | [f8f947a025](https://linux-hardware.org/?probe=f8f947a025) | Sep 28, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [da030ed703](https://linux-hardware.org/?probe=da030ed703) | Sep 28, 2023 |
| Google        | Lindar                      | Notebook    | [9ddbc21f0d](https://linux-hardware.org/?probe=9ddbc21f0d) | Sep 28, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [451d8ac4ca](https://linux-hardware.org/?probe=451d8ac4ca) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [af9350dd38](https://linux-hardware.org/?probe=af9350dd38) | Sep 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [92d7b8d41e](https://linux-hardware.org/?probe=92d7b8d41e) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d40624877e](https://linux-hardware.org/?probe=d40624877e) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [58fdd789af](https://linux-hardware.org/?probe=58fdd789af) | Sep 28, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Dell          | G3 3590                     | Notebook    | [3523165978](https://linux-hardware.org/?probe=3523165978) | Sep 27, 2023 |
| ZOTAC         | NM10                        | Desktop     | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc0d6b9ebb](https://linux-hardware.org/?probe=cc0d6b9ebb) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [0f2a543485](https://linux-hardware.org/?probe=0f2a543485) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [75f65a0438](https://linux-hardware.org/?probe=75f65a0438) | Sep 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Arch Rolling           | 4755      | 61.25%  |
| Arch                   | 2981      | 38.4%   |
| Arch V20.4.11          | 3         | 0.04%   |
| Arch V19.11.3          | 3         | 0.04%   |
| Arch V20.5.7           | 2         | 0.03%   |
| Arch V20.3.4           | 2         | 0.03%   |
| Arch V19.04.4          | 2         | 0.03%   |
| Arch Workstation       | 1         | 0.01%   |
| Arch V6.9.2            | 1         | 0.01%   |
| Arch V19.09.1          | 1         | 0.01%   |
| Arch V19.07.9          | 1         | 0.01%   |
| Arch V19.07.11         | 1         | 0.01%   |
| Arch V19.06.1          | 1         | 0.01%   |
| Arch V19.05.2          | 1         | 0.01%   |
| Arch V19.01.4          | 1         | 0.01%   |
| Arch Breaking          | 1         | 0.01%   |
| Arch 23.0.0            | 1         | 0.01%   |
| Arch 22.10             | 1         | 0.01%   |
| Arch 20230723.0.166908 | 1         | 0.01%   |
| Arch 2020.09.05        | 1         | 0.01%   |
| Arch 20.08.3           | 1         | 0.01%   |
| Arch 2.7               | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 7565      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 6.5.9-arch2-1   | 88        | 0.98%   |
| 5.17.1-arch1-1  | 85        | 0.94%   |
| 6.6.1-arch1-1   | 84        | 0.93%   |
| 6.4.12-arch1-1  | 79        | 0.88%   |
| 6.0.2-arch1-1   | 71        | 0.79%   |
| 5.8.5-arch1-1   | 70        | 0.78%   |
| 5.9.14-arch1-1  | 61        | 0.68%   |
| 5.9.1-arch1-1   | 60        | 0.67%   |
| 5.17.5-arch1-1  | 53        | 0.59%   |
| 5.17.9-arch1-1  | 51        | 0.57%   |
| 6.6.7-arch1-1   | 49        | 0.54%   |
| 5.8.12-arch1-1  | 48        | 0.53%   |
| 5.8.10-arch1-1  | 48        | 0.53%   |
| 6.5.7-arch1-1   | 47        | 0.52%   |
| 5.8.14-arch1-1  | 47        | 0.52%   |
| 6.6.8-arch1-1   | 46        | 0.51%   |
| 6.6.2-arch1-1   | 46        | 0.51%   |
| 6.3.9-arch1-1   | 46        | 0.51%   |
| 6.1.1-arch1-1   | 46        | 0.51%   |
| 5.7.12-arch1-1  | 46        | 0.51%   |
| 6.5.5-arch1-1   | 45        | 0.5%    |
| 6.2.8-arch1-1   | 45        | 0.5%    |
| 5.13.13-arch1-1 | 45        | 0.5%    |
| 6.0.12-arch1-1  | 43        | 0.48%   |
| 5.8.1-arch1-1   | 43        | 0.48%   |
| 6.6.3-arch1-1   | 42        | 0.47%   |
| 6.0.9-arch1-1   | 42        | 0.47%   |
| 5.11.16-arch1-1 | 42        | 0.47%   |
| 6.5.3-arch1-1   | 40        | 0.44%   |
| 6.3.2-arch1-1   | 39        | 0.43%   |
| 6.2.10-arch1-1  | 37        | 0.41%   |
| 6.1.12-arch1-1  | 37        | 0.41%   |
| 5.6.15-arch1-1  | 37        | 0.41%   |
| 6.5.8-arch1-1   | 35        | 0.39%   |
| 6.4.10-arch1-1  | 35        | 0.39%   |
| 6.1.8-arch1-1   | 35        | 0.39%   |
| 6.3.5-arch1-1   | 34        | 0.38%   |
| 5.18.16-arch1-1 | 34        | 0.38%   |
| 5.11.6-arch1-1  | 34        | 0.38%   |
| 5.11.11-arch1-1 | 34        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6.1   | 121       | 1.35%   |
| 6.5.9   | 113       | 1.26%   |
| 5.17.1  | 105       | 1.17%   |
| 5.8.5   | 92        | 1.02%   |
| 6.4.12  | 91        | 1.01%   |
| 6.0.2   | 90        | 1%      |
| 5.9.1   | 77        | 0.86%   |
| 5.8.12  | 73        | 0.81%   |
| 5.9.14  | 72        | 0.8%    |
| 5.17.5  | 70        | 0.78%   |
| 6.5.5   | 67        | 0.74%   |
| 6.3.1   | 65        | 0.72%   |
| 6.5.7   | 64        | 0.71%   |
| 5.8.14  | 63        | 0.7%    |
| 5.8.10  | 62        | 0.69%   |
| 6.6.7   | 61        | 0.68%   |
| 5.17.9  | 61        | 0.68%   |
| 6.6.2   | 59        | 0.66%   |
| 6.3.9   | 59        | 0.66%   |
| 6.6.8   | 58        | 0.64%   |
| 6.1.1   | 57        | 0.63%   |
| 6.5.3   | 56        | 0.62%   |
| 5.13.13 | 56        | 0.62%   |
| 6.4.3   | 54        | 0.6%    |
| 6.2.2   | 54        | 0.6%    |
| 6.1.12  | 54        | 0.6%    |
| 6.2.8   | 53        | 0.59%   |
| 5.8.1   | 53        | 0.59%   |
| 5.7.12  | 53        | 0.59%   |
| 6.3.2   | 52        | 0.58%   |
| 6.0.9   | 52        | 0.58%   |
| 6.0.12  | 52        | 0.58%   |
| 5.11.6  | 52        | 0.58%   |
| 6.6.3   | 51        | 0.57%   |
| 6.1.9   | 51        | 0.57%   |
| 5.11.16 | 51        | 0.57%   |
| 6.3.5   | 49        | 0.54%   |
| 6.2.10  | 49        | 0.54%   |
| 6.5.8   | 46        | 0.51%   |
| 6.4.10  | 46        | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 529       | 6.11%   |
| 5.8     | 522       | 6.02%   |
| 5.15    | 480       | 5.54%   |
| 6.4     | 426       | 4.92%   |
| 6.6     | 422       | 4.87%   |
| 6.5     | 416       | 4.8%    |
| 6.0     | 414       | 4.78%   |
| 6.2     | 388       | 4.48%   |
| 5.9     | 384       | 4.43%   |
| 5.18    | 369       | 4.26%   |
| 6.3     | 368       | 4.25%   |
| 5.10    | 355       | 4.1%    |
| 5.4     | 354       | 4.09%   |
| 5.11    | 350       | 4.04%   |
| 5.19    | 343       | 3.96%   |
| 5.17    | 342       | 3.95%   |
| 5.12    | 310       | 3.58%   |
| 5.16    | 305       | 3.52%   |
| 5.6     | 263       | 3.04%   |
| 5.7     | 260       | 3%      |
| 5.14    | 237       | 2.74%   |
| 5.13    | 234       | 2.7%    |
| 5.5     | 148       | 1.71%   |
| 5.3     | 114       | 1.32%   |
| 4.19    | 56        | 0.65%   |
| 5.2     | 54        | 0.62%   |
| 5.0     | 41        | 0.47%   |
| 4.18    | 37        | 0.43%   |
| 5.1     | 32        | 0.37%   |
| 4.20    | 22        | 0.25%   |
| 4.17    | 19        | 0.22%   |
| 4.15    | 15        | 0.17%   |
| 4.14    | 10        | 0.12%   |
| 4.16    | 9         | 0.1%    |
| 4.9     | 5         | 0.06%   |
| 6.7     | 4         | 0.05%   |
| 4.7     | 4         | 0.05%   |
| 4.6     | 4         | 0.05%   |
| 4.11    | 4         | 0.05%   |
| 4.8     | 3         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7558      | 99.91%  |
| i686    | 6         | 0.08%   |
| riscv64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 2494      | 31.64%  |
| KDE5                     | 2172      | 27.55%  |
| Unknown                  | 906       | 11.49%  |
| XFCE                     | 602       | 7.64%   |
| i3                       | 395       | 5.01%   |
| KDE                      | 302       | 3.83%   |
| Hyprland                 | 112       | 1.42%   |
| X-Cinnamon               | 105       | 1.33%   |
| sway                     | 104       | 1.32%   |
| MATE                     | 93        | 1.18%   |
| Budgie                   | 88        | 1.12%   |
| Cinnamon                 | 83        | 1.05%   |
| Deepin                   | 71        | 0.9%    |
| LXQt                     | 61        | 0.77%   |
| bspwm                    | 46        | 0.58%   |
| LXDE                     | 40        | 0.51%   |
| awesome                  | 37        | 0.47%   |
| Openbox                  | 21        | 0.27%   |
| qtile                    | 20        | 0.25%   |
| DWM                      | 19        | 0.24%   |
| xmonad                   | 15        | 0.19%   |
| GNOME Flashback          | 15        | 0.19%   |
| Unity                    | 12        | 0.15%   |
| GNOME Classic            | 10        | 0.13%   |
| i3-with-shmlog           | 8         | 0.1%    |
| LeftWM                   | 6         | 0.08%   |
| Enlightenment            | 6         | 0.08%   |
| chadwm                   | 4         | 0.05%   |
| KDE6                     | 3         | 0.04%   |
| Yaru:ubuntu:GNOME        | 2         | 0.03%   |
| Wayfire                  | 2         | 0.03%   |
| river                    | 2         | 0.03%   |
| jwm                      | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNUstep                  | 2         | 0.03%   |
| GNOME-Classic            | 2         | 0.03%   |
| dusk                     | 2         | 0.03%   |
| default                  | 2         | 0.03%   |
| /usr/bin/openbox-session | 2         | 0.03%   |
| xinitrc                  | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4485      | 57.11%  |
| Wayland | 2126      | 27.07%  |
| Tty     | 703       | 8.95%   |
| Unknown | 538       | 6.85%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3231      | 41.4%   |
| SDDM    | 1905      | 24.41%  |
| GDM     | 1088      | 13.94%  |
| LightDM | 899       | 11.52%  |
| TDM     | 398       | 5.1%    |
| Ly      | 79        | 1.01%   |
| XDM     | 56        | 0.72%   |
| LXDM    | 54        | 0.69%   |
| SLiM    | 31        | 0.4%    |
| GREETD  | 25        | 0.32%   |
| LY-DM   | 20        | 0.26%   |
| EMPTTY  | 9         | 0.12%   |
| NODM    | 6         | 0.08%   |
| XINIT   | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| LEMURS  | 1         | 0.01%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 3815      | 49.36%  |
| Unknown    | 657       | 8.5%    |
| en_GB      | 458       | 5.93%   |
| C          | 421       | 5.45%   |
| de_DE      | 309       | 4%      |
| it_IT      | 261       | 3.38%   |
| ru_RU      | 253       | 3.27%   |
| pt_BR      | 212       | 2.74%   |
| fr_FR      | 177       | 2.29%   |
| pl_PL      | 95        | 1.23%   |
| zh_CN      | 89        | 1.15%   |
| es_ES      | 85        | 1.1%    |
| en_CA      | 83        | 1.07%   |
| en_AU      | 76        | 0.98%   |
| en_IN      | 73        | 0.94%   |
| en_IE      | 39        | 0.5%    |
| es_MX      | 35        | 0.45%   |
| en_DK      | 32        | 0.41%   |
| hu_HU      | 23        | 0.3%    |
| es_AR      | 23        | 0.3%    |
| de_AT      | 23        | 0.3%    |
| tr_TR      | 22        | 0.28%   |
| pt_PT      | 20        | 0.26%   |
| ja_JP      | 18        | 0.23%   |
| es_CL      | 18        | 0.23%   |
| nl_NL      | 17        | 0.22%   |
| en_NZ      | 17        | 0.22%   |
| es_CO      | 16        | 0.21%   |
| cs_CZ      | 16        | 0.21%   |
| en_DE      | 14        | 0.18%   |
| ru_UA      | 13        | 0.17%   |
| sv_SE      | 12        | 0.16%   |
| en_SG      | 12        | 0.16%   |
| en_ZA      | 11        | 0.14%   |
| fi_FI      | 10        | 0.13%   |
| en_US.UTF8 | 10        | 0.13%   |
| en_AG      | 10        | 0.13%   |
| de_CH      | 10        | 0.13%   |
| zh_TW      | 9         | 0.12%   |
| uk_UA      | 9         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4775      | 61.88%  |
| BIOS | 2941      | 38.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 5348      | 69.72%  |
| Btrfs               | 1721      | 22.44%  |
| Unknown             | 187       | 2.44%   |
| Xfs                 | 177       | 2.31%   |
| F2fs                | 98        | 1.28%   |
| Overlay             | 55        | 0.72%   |
| Zfs                 | 48        | 0.63%   |
| Tmpfs               | 13        | 0.17%   |
| Ext2                | 8         | 0.1%    |
| XXXXX               | 5         | 0.07%   |
| Ext3                | 3         | 0.04%   |
| XXX4                | 2         | 0.03%   |
| Jfs                 | 2         | 0.03%   |
| Reiserfs            | 1         | 0.01%   |
| Fuse.fuse-overlayfs | 1         | 0.01%   |
| Bcachefs            | 1         | 0.01%   |
| Aufs                | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4887      | 63.69%  |
| Unknown | 2190      | 28.54%  |
| MBR     | 596       | 7.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6613      | 86.21%  |
| Yes       | 1058      | 13.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5369      | 69.78%  |
| Yes       | 2325      | 30.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 1480      | 19.56%  |
| Lenovo                 | 1366      | 18.06%  |
| Dell                   | 806       | 10.65%  |
| Hewlett-Packard        | 800       | 10.58%  |
| MSI                    | 628       | 8.3%    |
| Gigabyte Technology    | 600       | 7.93%   |
| ASRock                 | 365       | 4.82%   |
| Acer                   | 364       | 4.81%   |
| Apple                  | 122       | 1.61%   |
| Intel                  | 89        | 1.18%   |
| HUAWEI                 | 80        | 1.06%   |
| Samsung Electronics    | 68        | 0.9%    |
| Toshiba                | 48        | 0.63%   |
| Microsoft              | 41        | 0.54%   |
| Unknown                | 39        | 0.52%   |
| Notebook               | 36        | 0.48%   |
| Timi                   | 35        | 0.46%   |
| Google                 | 33        | 0.44%   |
| Fujitsu                | 28        | 0.37%   |
| Sony                   | 27        | 0.36%   |
| Framework              | 25        | 0.33%   |
| TUXEDO                 | 24        | 0.32%   |
| Alienware              | 24        | 0.32%   |
| Razer                  | 19        | 0.25%   |
| Biostar                | 18        | 0.24%   |
| Medion                 | 14        | 0.19%   |
| ECS                    | 14        | 0.19%   |
| LG Electronics         | 13        | 0.17%   |
| System76               | 12        | 0.16%   |
| Pegatron               | 11        | 0.15%   |
| Chuwi                  | 11        | 0.15%   |
| Avell High Performance | 11        | 0.15%   |
| Schenker               | 10        | 0.13%   |
| Positivo               | 10        | 0.13%   |
| AZW                    | 10        | 0.13%   |
| Packard Bell           | 9         | 0.12%   |
| MECHREVO               | 9         | 0.12%   |
| Huanan                 | 9         | 0.12%   |
| HONOR                  | 9         | 0.12%   |
| Supermicro             | 8         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 69        | 0.91%   |
| Unknown                          | 64        | 0.85%   |
| MSI MS-7C37                      | 35        | 0.46%   |
| ASUS TUF Gaming X570-PLUS        | 34        | 0.45%   |
| MSI MS-7C02                      | 32        | 0.42%   |
| MSI MS-7B86                      | 26        | 0.34%   |
| Gigabyte B450M DS3H              | 24        | 0.32%   |
| ASUS ROG STRIX B550-F GAMING     | 22        | 0.29%   |
| MSI MS-7C91                      | 21        | 0.28%   |
| ASUS PRIME X470-PRO              | 21        | 0.28%   |
| MSI MS-7B89                      | 20        | 0.26%   |
| MSI MS-7B79                      | 19        | 0.25%   |
| HP Notebook                      | 19        | 0.25%   |
| Gigabyte X570 AORUS ELITE        | 19        | 0.25%   |
| Dell XPS 15 9500                 | 19        | 0.25%   |
| MSI MS-7C56                      | 18        | 0.24%   |
| Dell XPS 15 9570                 | 18        | 0.24%   |
| MSI MS-7A34                      | 17        | 0.22%   |
| Framework Laptop                 | 17        | 0.22%   |
| ASUS ROG STRIX B450-F GAMING     | 17        | 0.22%   |
| Gigabyte X470 AORUS ULTRA GAMING | 16        | 0.21%   |
| ASUS PRIME X370-PRO              | 16        | 0.21%   |
| ASUS PRIME B450M-A               | 16        | 0.21%   |
| MSI MS-7A38                      | 15        | 0.2%    |
| ASUS ROG STRIX X570-E GAMING     | 15        | 0.2%    |
| Dell XPS 13 9360                 | 14        | 0.19%   |
| MSI MS-7C95                      | 13        | 0.17%   |
| ASUS TUF Gaming B550-PLUS        | 13        | 0.17%   |
| ASRock B450M Pro4                | 13        | 0.17%   |
| Dell XPS 13 9310                 | 12        | 0.16%   |
| ASUS ROG Strix G513QY_G513QY     | 12        | 0.16%   |
| ASUS PRIME A320M-K               | 12        | 0.16%   |
| ASRock X570 Taichi               | 12        | 0.16%   |
| HUAWEI NBLK-WAX9X                | 11        | 0.15%   |
| Gigabyte B450 AORUS ELITE        | 11        | 0.15%   |
| Gigabyte 970A-DS3P               | 11        | 0.15%   |
| Dell XPS 13 9380                 | 11        | 0.15%   |
| ASUS ROG STRIX X470-F GAMING     | 11        | 0.15%   |
| ASUS PRIME X570-P                | 11        | 0.15%   |
| MSI MS-7B98                      | 10        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 733       | 9.69%   |
| ASUS ROG           | 300       | 3.97%   |
| ASUS PRIME         | 243       | 3.21%   |
| Lenovo IdeaPad     | 241       | 3.19%   |
| Acer Aspire        | 206       | 2.72%   |
| Dell Inspiron      | 198       | 2.62%   |
| Dell Latitude      | 190       | 2.51%   |
| Dell XPS           | 178       | 2.35%   |
| ASUS TUF           | 166       | 2.19%   |
| HP Pavilion        | 147       | 1.94%   |
| HP EliteBook       | 124       | 1.64%   |
| ASUS VivoBook      | 98        | 1.3%    |
| Lenovo Legion      | 89        | 1.18%   |
| HP Laptop          | 85        | 1.12%   |
| HP ENVY            | 74        | 0.98%   |
| Lenovo Yoga        | 70        | 0.93%   |
| HP ProBook         | 69        | 0.91%   |
| Dell Precision     | 69        | 0.91%   |
| ASUS All           | 69        | 0.91%   |
| Dell OptiPlex      | 68        | 0.9%    |
| Gigabyte X570      | 65        | 0.86%   |
| Unknown            | 64        | 0.85%   |
| Acer Nitro         | 59        | 0.78%   |
| ASUS ASUS          | 55        | 0.73%   |
| ASUS Zenbook       | 48        | 0.63%   |
| Microsoft Surface  | 41        | 0.54%   |
| Gigabyte B450M     | 41        | 0.54%   |
| Acer Swift         | 41        | 0.54%   |
| Toshiba Satellite  | 39        | 0.52%   |
| Lenovo ThinkBook   | 39        | 0.52%   |
| HP OMEN            | 39        | 0.52%   |
| Dell Vostro        | 37        | 0.49%   |
| MSI MS-7C37        | 35        | 0.46%   |
| MSI MS-7C02        | 32        | 0.42%   |
| HP Spectre         | 32        | 0.42%   |
| Gigabyte B450      | 32        | 0.42%   |
| ASRock X570        | 32        | 0.42%   |
| Lenovo ThinkCentre | 30        | 0.4%    |
| HP Compaq          | 28        | 0.37%   |
| MSI MS-7B86        | 26        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1030      | 13.62%  |
| 2019    | 990       | 13.09%  |
| 2020    | 985       | 13.02%  |
| 2021    | 721       | 9.53%   |
| 2017    | 601       | 7.94%   |
| 2022    | 442       | 5.84%   |
| 2016    | 413       | 5.46%   |
| 2012    | 401       | 5.3%    |
| 2014    | 379       | 5.01%   |
| 2013    | 371       | 4.9%    |
| 2015    | 350       | 4.63%   |
| 2011    | 298       | 3.94%   |
| 2010    | 175       | 2.31%   |
| 2023    | 147       | 1.94%   |
| 2008    | 103       | 1.36%   |
| 2009    | 93        | 1.23%   |
| 2007    | 46        | 0.61%   |
| 2006    | 11        | 0.15%   |
| Unknown | 4         | 0.05%   |
| 2005    | 3         | 0.04%   |
| 2003    | 1         | 0.01%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4145      | 54.79%  |
| Desktop        | 2913      | 38.51%  |
| Convertible    | 276       | 3.65%   |
| Tablet         | 84        | 1.11%   |
| Mini pc        | 68        | 0.9%    |
| All in one     | 48        | 0.63%   |
| Server         | 29        | 0.38%   |
| Stick pc       | 1         | 0.01%   |
| System on chip | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7479      | 98.64%  |
| Enabled  | 103       | 1.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7505      | 99.21%  |
| Yes  | 60        | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2135      | 27.82%  |
| 8.01-16.0       | 1488      | 19.39%  |
| 4.01-8.0        | 1448      | 18.87%  |
| 32.01-64.0      | 1285      | 16.75%  |
| 3.01-4.0        | 598       | 7.79%   |
| 64.01-256.0     | 330       | 4.3%    |
| 24.01-32.0      | 230       | 3%      |
| 1.01-2.0        | 89        | 1.16%   |
| 2.01-3.0        | 45        | 0.59%   |
| 0.51-1.0        | 13        | 0.17%   |
| More than 256.0 | 10        | 0.13%   |
| Unknown         | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2083      | 24.87%  |
| 2.01-3.0    | 1928      | 23.02%  |
| 1.01-2.0    | 1667      | 19.9%   |
| 3.01-4.0    | 1399      | 16.7%   |
| 8.01-16.0   | 748       | 8.93%   |
| 0.51-1.0    | 284       | 3.39%   |
| 16.01-24.0  | 117       | 1.4%    |
| 0.01-0.5    | 76        | 0.91%   |
| 24.01-32.0  | 43        | 0.51%   |
| 32.01-64.0  | 26        | 0.31%   |
| 64.01-256.0 | 2         | 0.02%   |
| Unknown     | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3940      | 50.55%  |
| 2      | 2111      | 27.08%  |
| 3      | 852       | 10.93%  |
| 4      | 403       | 5.17%   |
| 5      | 238       | 3.05%   |
| 6      | 105       | 1.35%   |
| 7      | 55        | 0.71%   |
| 0      | 25        | 0.32%   |
| 8      | 23        | 0.3%    |
| 9      | 17        | 0.22%   |
| 12     | 5         | 0.06%   |
| 11     | 5         | 0.06%   |
| 10     | 5         | 0.06%   |
| 14     | 3         | 0.04%   |
| 13     | 3         | 0.04%   |
| 22     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 17     | 1         | 0.01%   |
| 15     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6068      | 79.72%  |
| Yes       | 1544      | 20.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6280      | 82.68%  |
| No        | 1316      | 17.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5976      | 78.53%  |
| No        | 1634      | 21.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5440      | 71.07%  |
| No        | 2214      | 28.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1410      | 18.51%  |
| Germany     | 723       | 9.49%   |
| Russia      | 508       | 6.67%   |
| Italy       | 429       | 5.63%   |
| Brazil      | 395       | 5.18%   |
| France      | 329       | 4.32%   |
| UK          | 295       | 3.87%   |
| India       | 236       | 3.1%    |
| Poland      | 228       | 2.99%   |
| Canada      | 200       | 2.63%   |
| Spain       | 170       | 2.23%   |
| Netherlands | 146       | 1.92%   |
| China       | 131       | 1.72%   |
| Australia   | 128       | 1.68%   |
| Sweden      | 107       | 1.4%    |
| Austria     | 106       | 1.39%   |
| Ukraine     | 97        | 1.27%   |
| Turkey      | 94        | 1.23%   |
| Finland     | 78        | 1.02%   |
| Mexico      | 73        | 0.96%   |
| Switzerland | 72        | 0.95%   |
| Czechia     | 68        | 0.89%   |
| Romania     | 63        | 0.83%   |
| Hungary     | 62        | 0.81%   |
| Indonesia   | 60        | 0.79%   |
| Belgium     | 58        | 0.76%   |
| Argentina   | 57        | 0.75%   |
| Portugal    | 53        | 0.7%    |
| Denmark     | 52        | 0.68%   |
| Japan       | 50        | 0.66%   |
| Vietnam     | 49        | 0.64%   |
| Chile       | 48        | 0.63%   |
| Norway      | 47        | 0.62%   |
| Greece      | 45        | 0.59%   |
| New Zealand | 40        | 0.53%   |
| Colombia    | 39        | 0.51%   |
| Iran        | 38        | 0.5%    |
| Hong Kong   | 36        | 0.47%   |
| Bulgaria    | 33        | 0.43%   |
| Taiwan      | 31        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 144       | 1.78%   |
| Berlin            | 78        | 0.96%   |
| Paris             | 76        | 0.94%   |
| St Petersburg     | 75        | 0.93%   |
| Sao Paulo         | 61        | 0.75%   |
| Milan             | 61        | 0.75%   |
| Warsaw            | 58        | 0.72%   |
| Vienna            | 57        | 0.7%    |
| Melbourne         | 49        | 0.61%   |
| Munich            | 46        | 0.57%   |
| Helsinki          | 42        | 0.52%   |
| Frankfurt am Main | 39        | 0.48%   |
| Sydney            | 37        | 0.46%   |
| Amsterdam         | 37        | 0.46%   |
| Rome              | 36        | 0.44%   |
| Los Angeles       | 36        | 0.44%   |
| Istanbul          | 33        | 0.41%   |
| New York          | 32        | 0.4%    |
| Hamburg           | 32        | 0.4%    |
| Prague            | 31        | 0.38%   |
| London            | 30        | 0.37%   |
| Valencia          | 29        | 0.36%   |
| Kyiv              | 27        | 0.33%   |
| Budapest          | 27        | 0.33%   |
| Seattle           | 26        | 0.32%   |
| Madrid            | 26        | 0.32%   |
| Bengaluru         | 26        | 0.32%   |
| Singapore         | 25        | 0.31%   |
| Montreal          | 25        | 0.31%   |
| Krakow            | 25        | 0.31%   |
| Beijing           | 25        | 0.31%   |
| Zurich            | 24        | 0.3%    |
| Athens            | 24        | 0.3%    |
| Central           | 22        | 0.27%   |
| Auckland          | 22        | 0.27%   |
| Turin             | 21        | 0.26%   |
| Cologne           | 21        | 0.26%   |
| Chennai           | 21        | 0.26%   |
| Rio de Janeiro    | 20        | 0.25%   |
| Phoenix           | 20        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2513      | 3949   | 20.11%  |
| WDC                         | 1648      | 2573   | 13.19%  |
| Seagate                     | 1446      | 2173   | 11.57%  |
| Sandisk                     | 907       | 1225   | 7.26%   |
| Toshiba                     | 743       | 991    | 5.95%   |
| Kingston                    | 655       | 869    | 5.24%   |
| Crucial                     | 516       | 738    | 4.13%   |
| SK hynix                    | 401       | 497    | 3.21%   |
| Intel                       | 363       | 485    | 2.9%    |
| Unknown                     | 306       | 369    | 2.45%   |
| Micron Technology           | 257       | 310    | 2.06%   |
| HGST                        | 201       | 256    | 1.61%   |
| Hitachi                     | 190       | 235    | 1.52%   |
| A-DATA Technology           | 179       | 247    | 1.43%   |
| Micron/Crucial Technology   | 130       | 157    | 1.04%   |
| Phison                      | 118       | 152    | 0.94%   |
| Phison Electronics          | 109       | 133    | 0.87%   |
| Silicon Motion              | 92        | 113    | 0.74%   |
| KIOXIA                      | 92        | 114    | 0.74%   |
| China                       | 91        | 119    | 0.73%   |
| Apple                       | 81        | 98     | 0.65%   |
| Kingston Technology Company | 75        | 79     | 0.6%    |
| SPCC                        | 63        | 69     | 0.5%    |
| OCZ                         | 57        | 75     | 0.46%   |
| PNY                         | 54        | 69     | 0.43%   |
| ADATA Technology            | 54        | 70     | 0.43%   |
| Corsair                     | 53        | 68     | 0.42%   |
| Transcend                   | 50        | 66     | 0.4%    |
| LITEON                      | 48        | 51     | 0.38%   |
| Patriot                     | 41        | 53     | 0.33%   |
| Realtek Semiconductor       | 37        | 45     | 0.3%    |
| GOODRAM                     | 33        | 42     | 0.26%   |
| MAXIO Technology (Hangzhou) | 32        | 34     | 0.26%   |
| Team                        | 28        | 37     | 0.22%   |
| JMicron Technology          | 28        | 47     | 0.22%   |
| XPG                         | 27        | 39     | 0.22%   |
| Intenso                     | 25        | 27     | 0.2%    |
| Plextor                     | 23        | 32     | 0.18%   |
| Hewlett-Packard             | 23        | 26     | 0.18%   |
| Netac                       | 21        | 27     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 319       | 2.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 180       | 1.27%   |
| Kingston SA400S37240G 240GB SSD                     | 133       | 0.94%   |
| Samsung SSD 860 EVO 500GB                           | 131       | 0.93%   |
| Samsung SSD 850 EVO 500GB                           | 131       | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB                      | 112       | 0.79%   |
| Samsung SSD 860 EVO 1TB                             | 99        | 0.7%    |
| Samsung SSD 850 EVO 250GB                           | 99        | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB                      | 88        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 83        | 0.59%   |
| Samsung NVMe SSD Drive 512GB                        | 82        | 0.58%   |
| Crucial CT500MX500SSD1 500GB                        | 82        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                      | 79        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB                        | 78        | 0.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 69        | 0.49%   |
| Kingston SA400S37120G 120GB SSD                     | 68        | 0.48%   |
| Samsung NVMe SSD Drive 1TB                          | 67        | 0.47%   |
| Kingston SA400S37480G 480GB SSD                     | 66        | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                      | 65        | 0.46%   |
| Samsung NVMe SSD Drive 500GB                        | 64        | 0.45%   |
| HGST HTS721010A9E630 1TB                            | 64        | 0.45%   |
| Toshiba MQ01ABD100 1TB                              | 63        | 0.45%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 63        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 62        | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 62        | 0.44%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 60        | 0.42%   |
| Toshiba DT01ACA100 1TB                              | 58        | 0.41%   |
| Samsung SSD 860 EVO 250GB                           | 58        | 0.41%   |
| Samsung SSD 980 1TB                                 | 56        | 0.4%    |
| Unknown MMC Card  64GB                              | 53        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 53        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                      | 51        | 0.36%   |
| SanDisk NVMe SSD Drive 1TB                          | 51        | 0.36%   |
| Toshiba MQ04ABF100 1TB                              | 50        | 0.35%   |
| SanDisk NVMe SSD Drive 512GB                        | 50        | 0.35%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 48        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                      | 47        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 47        | 0.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 47        | 0.33%   |
| Phison E12 NVMe Controller 1TB                      | 47        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1413      | 2121   | 36.23%  |
| WDC                 | 1283      | 1980   | 32.9%   |
| Toshiba             | 516       | 682    | 13.23%  |
| HGST                | 199       | 254    | 5.1%    |
| Hitachi             | 190       | 235    | 4.87%   |
| Samsung Electronics | 123       | 163    | 3.15%   |
| Unknown             | 29        | 37     | 0.74%   |
| Apple               | 27        | 27     | 0.69%   |
| SABRENT             | 18        | 19     | 0.46%   |
| Fujitsu             | 12        | 13     | 0.31%   |
| TO Exter            | 10        | 16     | 0.26%   |
| Maxtor              | 10        | 10     | 0.26%   |
| ASMT                | 9         | 10     | 0.23%   |
| External            | 6         | 8      | 0.15%   |
| USB3.0              | 4         | 5      | 0.1%    |
| HGST HTS            | 4         | 4      | 0.1%    |
| Generic-            | 4         | 5      | 0.1%    |
| USB                 | 3         | 3      | 0.08%   |
| StoreJet            | 3         | 3      | 0.08%   |
| SSK                 | 3         | 3      | 0.08%   |
| LaCie               | 3         | 3      | 0.08%   |
| ACASIS              | 3         | 4      | 0.08%   |
| SAGE                | 2         | 3      | 0.05%   |
| NeoTech             | 2         | 2      | 0.05%   |
| KESU                | 2         | 2      | 0.05%   |
| Hewlett-Packard     | 2         | 2      | 0.05%   |
| ASUSTOR             | 2         | 2      | 0.05%   |
| WD MediaMax         | 1         | 1      | 0.03%   |
| TDAS                | 1         | 4      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 17     | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARVELL             | 1         | 1      | 0.03%   |
| LIO-ORG             | 1         | 2      | 0.03%   |
| JMicron Technology  | 1         | 16     | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1110      | 1588   | 27.41%  |
| Kingston            | 505       | 654    | 12.47%  |
| Crucial             | 475       | 677    | 11.73%  |
| SanDisk             | 393       | 541    | 9.71%   |
| WDC                 | 270       | 351    | 6.67%   |
| A-DATA Technology   | 119       | 168    | 2.94%   |
| Intel               | 94        | 112    | 2.32%   |
| China               | 91        | 118    | 2.25%   |
| Toshiba             | 59        | 101    | 1.46%   |
| OCZ                 | 57        | 75     | 1.41%   |
| SPCC                | 54        | 58     | 1.33%   |
| SK hynix            | 54        | 65     | 1.33%   |
| Micron Technology   | 51        | 61     | 1.26%   |
| PNY                 | 49        | 64     | 1.21%   |
| Transcend           | 47        | 63     | 1.16%   |
| LITEON              | 43        | 45     | 1.06%   |
| Patriot             | 41        | 53     | 1.01%   |
| Apple               | 39        | 40     | 0.96%   |
| GOODRAM             | 31        | 40     | 0.77%   |
| Corsair             | 26        | 32     | 0.64%   |
| Intenso             | 24        | 26     | 0.59%   |
| Team                | 22        | 24     | 0.54%   |
| Plextor             | 20        | 21     | 0.49%   |
| Lexar               | 19        | 26     | 0.47%   |
| JMicron Technology  | 18        | 23     | 0.44%   |
| LITEONIT            | 17        | 17     | 0.42%   |
| KingSpec            | 17        | 19     | 0.42%   |
| Netac               | 13        | 14     | 0.32%   |
| Hewlett-Packard     | 12        | 14     | 0.3%    |
| Mushkin             | 11        | 17     | 0.27%   |
| Gigabyte Technology | 11        | 12     | 0.27%   |
| ASMT                | 11        | 12     | 0.27%   |
| Unknown             | 11        | 12     | 0.27%   |
| Apacer              | 8         | 9      | 0.2%    |
| Seagate             | 7         | 7      | 0.17%   |
| AMD                 | 7         | 8      | 0.17%   |
| Verbatim            | 6         | 9      | 0.15%   |
| KingDian            | 6         | 8      | 0.15%   |
| FORESEE             | 6         | 9      | 0.15%   |
| XrayDisk            | 5         | 7      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 4047      | 6036   | 36.77%  |
| SSD     | 3377      | 5439   | 30.68%  |
| HDD     | 3202      | 5669   | 29.09%  |
| MMC     | 256       | 305    | 2.33%   |
| Unknown | 125       | 148    | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4856      | 10714  | 50.75%  |
| NVMe | 4044      | 6016   | 42.27%  |
| SAS  | 412       | 562    | 4.31%   |
| MMC  | 256       | 305    | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3417      | 5451   | 48.18%  |
| 0.51-1.0   | 2241      | 3319   | 31.6%   |
| 1.01-2.0   | 797       | 1213   | 11.24%  |
| 3.01-4.0   | 261       | 439    | 3.68%   |
| 4.01-10.0  | 188       | 361    | 2.65%   |
| 2.01-3.0   | 151       | 238    | 2.13%   |
| 10.01-20.0 | 36        | 86     | 0.51%   |
| 20.01-50.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1690      | 21.37%  |
| 101-250        | 1610      | 20.35%  |
| 501-1000       | 1466      | 18.53%  |
| 1001-2000      | 1086      | 13.73%  |
| More than 3000 | 875       | 11.06%  |
| 2001-3000      | 461       | 5.83%   |
| 51-100         | 290       | 3.67%   |
| Unknown        | 200       | 2.53%   |
| 21-50          | 119       | 1.5%    |
| 1-20           | 113       | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1558      | 18.88%  |
| 101-250        | 1427      | 17.29%  |
| 21-50          | 1135      | 13.75%  |
| 251-500        | 1019      | 12.35%  |
| 51-100         | 1008      | 12.21%  |
| 501-1000       | 853       | 10.34%  |
| 1001-2000      | 534       | 6.47%   |
| More than 3000 | 310       | 3.76%   |
| 2001-3000      | 208       | 2.52%   |
| Unknown        | 200       | 2.42%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                                 | 15        | 17     | 1.7%    |
| Seagate ST1000LM035-1RK172 1TB                                  | 15        | 16     | 1.7%    |
| HGST HTS721010A9E630 1TB                                        | 12        | 12     | 1.36%   |
| HGST HTS541010A9E680 1TB                                        | 9         | 9      | 1.02%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 8         | 9      | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 8         | 11     | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 8         | 13     | 0.91%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 7         | 9      | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB                                        | 7         | 7      | 0.8%    |
| Seagate ST9500325AS 500GB                                       | 7         | 7      | 0.8%    |
| Seagate ST500LT012-1DG142 500GB                                 | 7         | 8      | 0.8%    |
| Seagate ST500LM021-1KJ152 500GB                                 | 7         | 10     | 0.8%    |
| Seagate ST2000DM006-2DM164 2TB                                  | 7         | 8      | 0.8%    |
| Kingston SV300S37A120G 120GB SSD                                | 7         | 7      | 0.8%    |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 6         | 6      | 0.68%   |
| Toshiba MQ01ABD100 1TB                                          | 6         | 9      | 0.68%   |
| Seagate ST3500418AS 500GB                                       | 6         | 7      | 0.68%   |
| Seagate ST31000528AS 1TB                                        | 6         | 6      | 0.68%   |
| Seagate ST1000LX015-1U7172 1TB                                  | 6         | 8      | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 6         | 11     | 0.68%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 6         | 7      | 0.68%   |
| OCZ VERTEX4 256GB SSD                                           | 6         | 9      | 0.68%   |
| HGST HTS725050A7E630 500GB                                      | 6         | 6      | 0.68%   |
| HGST HTS545050A7E680 500GB                                      | 6         | 7      | 0.68%   |
| Crucial CT525MX300SSD1 528GB                                    | 6         | 9      | 0.68%   |
| WDC WD10EZEX-08M2NA0 1TB                                        | 5         | 5      | 0.57%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 5         | 7      | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 5         | 5      | 0.57%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 5         | 5      | 0.57%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 5         | 5      | 0.57%   |
| Samsung Electronics SSD 980 1TB                                 | 5         | 5      | 0.57%   |
| Samsung Electronics SSD 960 EVO 250GB                           | 5         | 11     | 0.57%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB       | 5         | 6      | 0.57%   |
| WDC WD40EFRX-68N32N0 4TB                                        | 4         | 4      | 0.45%   |
| WDC WD20EARX-00PASB0 2TB                                        | 4         | 4      | 0.45%   |
| WDC WD10EZEX-00WN4A0 1TB                                        | 4         | 4      | 0.45%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 4         | 5      | 0.45%   |
| Toshiba DT01ACA100 1TB                                          | 4         | 5      | 0.45%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 4         | 4      | 0.45%   |
| Seagate ST9250315AS 250GB                                       | 4         | 5      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 230       | 291    | 27.32%  |
| WDC                         | 192       | 261    | 22.8%   |
| Samsung Electronics         | 75        | 100    | 8.91%   |
| Toshiba                     | 54        | 67     | 6.41%   |
| Hitachi                     | 51        | 55     | 6.06%   |
| HGST                        | 41        | 42     | 4.87%   |
| SanDisk                     | 25        | 28     | 2.97%   |
| Kingston                    | 25        | 35     | 2.97%   |
| Crucial                     | 22        | 27     | 2.61%   |
| Intel                       | 21        | 24     | 2.49%   |
| SK hynix                    | 13        | 14     | 1.54%   |
| OCZ                         | 11        | 18     | 1.31%   |
| A-DATA Technology           | 11        | 12     | 1.31%   |
| Micron Technology           | 7         | 8      | 0.83%   |
| Realtek Semiconductor       | 5         | 6      | 0.59%   |
| LITEON                      | 5         | 5      | 0.59%   |
| Corsair                     | 5         | 5      | 0.59%   |
| China                       | 4         | 4      | 0.48%   |
| Transcend                   | 3         | 11     | 0.36%   |
| Maxtor                      | 3         | 3      | 0.36%   |
| Hewlett-Packard             | 3         | 3      | 0.36%   |
| Drevo                       | 3         | 4      | 0.36%   |
| ASMT                        | 3         | 3      | 0.36%   |
| Apple                       | 3         | 3      | 0.36%   |
| XrayDisk                    | 2         | 4      | 0.24%   |
| SSSTC                       | 2         | 2      | 0.24%   |
| SPCC                        | 2         | 3      | 0.24%   |
| Silicon Motion              | 2         | 2      | 0.24%   |
| PNY                         | 2         | 3      | 0.24%   |
| Plextor                     | 2         | 9      | 0.24%   |
| Patriot                     | 2         | 2      | 0.24%   |
| Fujitsu                     | 2         | 2      | 0.24%   |
| WD MediaMax                 | 1         | 1      | 0.12%   |
| VNYEZ                       | 1         | 1      | 0.12%   |
| TO Exter                    | 1         | 1      | 0.12%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.12%   |
| KingSpec                    | 1         | 1      | 0.12%   |
| Kingrich                    | 1         | 1      | 0.12%   |
| JMicron Technology          | 1         | 1      | 0.12%   |
| INNOVATION IT               | 1         | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 230       | 291    | 38.92%  |
| WDC                 | 184       | 250    | 31.13%  |
| Hitachi             | 51        | 55     | 8.63%   |
| Toshiba             | 48        | 61     | 8.12%   |
| HGST                | 41        | 42     | 6.94%   |
| Samsung Electronics | 24        | 29     | 4.06%   |
| Maxtor              | 3         | 3      | 0.51%   |
| Apple               | 3         | 3      | 0.51%   |
| Fujitsu             | 2         | 2      | 0.34%   |
| ASMT                | 2         | 2      | 0.34%   |
| WD MediaMax         | 1         | 1      | 0.17%   |
| TO Exter            | 1         | 1      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 542       | 741    | 68.78%  |
| SSD  | 192       | 248    | 24.37%  |
| NVMe | 54        | 81     | 6.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 14.29%  |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 7.14%   |
| WDC WD3200BEKT-60V5T1 320GB                      | 1         | 1      | 7.14%   |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 7.14%   |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB    | 1         | 1      | 7.14%   |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 7.14%   |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 7.14%   |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 7.14%   |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 7.14%   |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 4         | 5      | 28.57%  |
| WDC                     | 3         | 3      | 21.43%  |
| Seagate                 | 2         | 2      | 14.29%  |
| Kingston                | 2         | 2      | 14.29%  |
| Union Memory (Shenzhen) | 1         | 1      | 7.14%   |
| Transcend               | 1         | 1      | 7.14%   |
| Phison                  | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4069      | 8954   | 47.49%  |
| Detected | 3734      | 7557   | 43.58%  |
| Malfunc  | 750       | 1070   | 8.75%   |
| Failed   | 14        | 15     | 0.16%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4115      | 37.95%  |
| AMD                              | 2022      | 18.65%  |
| Samsung Electronics              | 1591      | 14.67%  |
| SanDisk                          | 675       | 6.23%   |
| SK hynix                         | 344       | 3.17%   |
| Phison Electronics               | 270       | 2.49%   |
| Kingston Technology Company      | 231       | 2.13%   |
| ASMedia Technology               | 219       | 2.02%   |
| Micron Technology                | 212       | 1.96%   |
| Toshiba America Info Systems     | 168       | 1.55%   |
| Micron/Crucial Technology        | 167       | 1.54%   |
| ADATA Technology                 | 122       | 1.13%   |
| Silicon Motion                   | 112       | 1.03%   |
| KIOXIA                           | 96        | 0.89%   |
| Marvell Technology Group         | 78        | 0.72%   |
| Realtek Semiconductor            | 48        | 0.44%   |
| JMicron Technology               | 45        | 0.42%   |
| MAXIO Technology (Hangzhou)      | 32        | 0.3%    |
| Union Memory (Shenzhen)          | 29        | 0.27%   |
| Solid State Storage Technology   | 25        | 0.23%   |
| Broadcom / LSI                   | 23        | 0.21%   |
| Yangtze Memory Technologies      | 21        | 0.19%   |
| Nvidia                           | 21        | 0.19%   |
| Lite-On Technology               | 21        | 0.19%   |
| Seagate Technology               | 20        | 0.18%   |
| Apple                            | 19        | 0.18%   |
| Lenovo                           | 18        | 0.17%   |
| Shenzhen Longsys Electronics     | 16        | 0.15%   |
| LSI Logic / Symbios Logic        | 11        | 0.1%    |
| Adaptec                          | 10        | 0.09%   |
| VIA Technologies                 | 7         | 0.06%   |
| Silicon Image                    | 7         | 0.06%   |
| INNOGRIT                         | 7         | 0.06%   |
| Hewlett-Packard                  | 6         | 0.06%   |
| Netac Technology                 | 5         | 0.05%   |
| Biwin Storage Technology         | 5         | 0.05%   |
| Silicon Integrated Systems [SiS] | 4         | 0.04%   |
| OCZ Technology Group             | 4         | 0.04%   |
| Solidigm                         | 3         | 0.03%   |
| Transcend                        | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1509      | 12.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 873       | 7.22%   |
| AMD 400 Series Chipset SATA Controller                                         | 449       | 3.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 378       | 3.13%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 261       | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 258       | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 246       | 2.03%   |
| AMD 500 Series Chipset SATA Controller                                         | 246       | 2.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 243       | 2.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 240       | 1.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 211       | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 206       | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 191       | 1.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 186       | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 182       | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 179       | 1.48%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 165       | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 143       | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 142       | 1.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 139       | 1.15%   |
| Phison E12 NVMe Controller                                                     | 136       | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 131       | 1.08%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 129       | 1.07%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 123       | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 120       | 0.99%   |
| Intel SSD 660P Series                                                          | 118       | 0.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 117       | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 96        | 0.79%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 87        | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 86        | 0.71%   |
| Intel SATA Controller [RAID mode]                                              | 83        | 0.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 80        | 0.66%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 78        | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 78        | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                         | 78        | 0.65%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 73        | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                          | 73        | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 72        | 0.6%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 71        | 0.59%   |
| AMD X370 Series Chipset SATA Controller                                        | 67        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5389      | 51.62%  |
| NVMe | 4060      | 38.89%  |
| RAID | 600       | 5.75%   |
| IDE  | 355       | 3.4%    |
| SAS  | 28        | 0.27%   |
| SCSI | 8         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Intel      | 4961      | 65.58%  |
| AMD        | 2603      | 34.41%  |
| thead,c906 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 134       | 1.77%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 120       | 1.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 108       | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 100       | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 94        | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 91        | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 84        | 1.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 83        | 1.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 83        | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 82        | 1.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 81        | 1.07%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 74        | 0.97%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 71        | 0.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 68        | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 61        | 0.8%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 60        | 0.79%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 60        | 0.79%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 59        | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 58        | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 57        | 0.75%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 57        | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 56        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 56        | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 55        | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 54        | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 53        | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 53        | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 46        | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 46        | 0.61%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 46        | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 44        | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 0.57%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 42        | 0.55%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 41        | 0.54%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 41        | 0.54%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 41        | 0.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 39        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 38        | 0.5%    |
| AMD Ryzen 5 2600X Six-Core Processor          | 38        | 0.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz             | 37        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1635      | 21.58%  |
| Intel Core i5           | 1553      | 20.5%   |
| AMD Ryzen 5             | 848       | 11.19%  |
| AMD Ryzen 7             | 801       | 10.57%  |
| Other                   | 650       | 8.58%   |
| Intel Core i3           | 335       | 4.42%   |
| AMD Ryzen 9             | 315       | 4.16%   |
| Intel Celeron           | 184       | 2.43%   |
| Intel Xeon              | 141       | 1.86%   |
| Intel Core 2 Duo        | 117       | 1.54%   |
| AMD Ryzen 3             | 108       | 1.43%   |
| Intel Pentium           | 105       | 1.39%   |
| AMD FX                  | 93        | 1.23%   |
| AMD Ryzen 7 PRO         | 90        | 1.19%   |
| Intel Core i9           | 79        | 1.04%   |
| Intel Atom              | 61        | 0.81%   |
| AMD A8                  | 37        | 0.49%   |
| AMD Ryzen 5 PRO         | 35        | 0.46%   |
| AMD Ryzen Threadripper  | 34        | 0.45%   |
| AMD A10                 | 31        | 0.41%   |
| AMD A6                  | 29        | 0.38%   |
| Intel Core 2 Quad       | 28        | 0.37%   |
| AMD Athlon              | 23        | 0.3%    |
| Intel Pentium Dual-Core | 21        | 0.28%   |
| Intel Pentium Silver    | 20        | 0.26%   |
| AMD A4                  | 19        | 0.25%   |
| AMD Phenom II X4        | 16        | 0.21%   |
| AMD E2                  | 12        | 0.16%   |
| Intel Genuine           | 10        | 0.13%   |
| Intel Core m3           | 10        | 0.13%   |
| AMD Athlon II X2        | 10        | 0.13%   |
| AMD Athlon II X4        | 9         | 0.12%   |
| Intel Pentium Dual      | 8         | 0.11%   |
| AMD E1                  | 8         | 0.11%   |
| AMD E                   | 8         | 0.11%   |
| Intel Core 2            | 7         | 0.09%   |
| AMD Phenom II X6        | 7         | 0.09%   |
| Intel Core m5           | 6         | 0.08%   |
| AMD Athlon 64 X2        | 6         | 0.08%   |
| AMD Athlon X4           | 5         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2721      | 35.9%   |
| 2       | 1862      | 24.56%  |
| 6       | 1226      | 16.17%  |
| 8       | 1154      | 15.22%  |
| 12      | 234       | 3.09%   |
| 16      | 137       | 1.81%   |
| 14      | 67        | 0.88%   |
| 10      | 64        | 0.84%   |
| 1       | 38        | 0.5%    |
| 3       | 30        | 0.4%    |
| 24      | 24        | 0.32%   |
| 32      | 8         | 0.11%   |
| 64      | 4         | 0.05%   |
| Unknown | 3         | 0.04%   |
| 28      | 2         | 0.03%   |
| 18      | 2         | 0.03%   |
| 40      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7523      | 99.44%  |
| 2       | 40        | 0.53%   |
| 4       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6113      | 80.71%  |
| 1       | 1458      | 19.25%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7455      | 98.42%  |
| Unknown        | 115       | 1.52%   |
| 32-bit         | 5         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3103      | 39.33%  |
| 0x08701021 | 221       | 2.8%    |
| 0x306a9    | 209       | 2.65%   |
| 0x906ea    | 205       | 2.6%    |
| 0x306c3    | 202       | 2.56%   |
| 0x206a7    | 181       | 2.29%   |
| 0x906e9    | 173       | 2.19%   |
| 0x806ea    | 171       | 2.17%   |
| 0x0800820d | 159       | 2.02%   |
| 0x0a50000c | 139       | 1.76%   |
| 0x806ec    | 138       | 1.75%   |
| 0x806c1    | 138       | 1.75%   |
| 0x506e3    | 123       | 1.56%   |
| 0x406e3    | 112       | 1.42%   |
| 0x806e9    | 108       | 1.37%   |
| 0x08701013 | 102       | 1.29%   |
| 0x08600106 | 96        | 1.22%   |
| 0x306d4    | 92        | 1.17%   |
| 0x08108102 | 91        | 1.15%   |
| 0x08108109 | 88        | 1.12%   |
| 0x40651    | 87        | 1.1%    |
| 0x1067a    | 68        | 0.86%   |
| 0x08001138 | 65        | 0.82%   |
| 0xa0652    | 64        | 0.81%   |
| 0x0a50000d | 62        | 0.79%   |
| 0x0a201016 | 62        | 0.79%   |
| 0x0a601203 | 61        | 0.77%   |
| 0x08608103 | 60        | 0.76%   |
| 0x08600104 | 56        | 0.71%   |
| 0x0a201009 | 53        | 0.67%   |
| 0x20655    | 50        | 0.63%   |
| 0x0a404102 | 49        | 0.62%   |
| 0x806eb    | 46        | 0.58%   |
| 0x08600103 | 44        | 0.56%   |
| 0x706e5    | 38        | 0.48%   |
| 0x906ed    | 36        | 0.46%   |
| 0x0810100b | 36        | 0.46%   |
| 0x0a20120a | 32        | 0.41%   |
| 0x06000852 | 32        | 0.41%   |
| 0x906a3    | 30        | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1556      | 20.5%   |
| Zen 2            | 712       | 9.38%   |
| Haswell          | 546       | 7.19%   |
| Zen 3            | 539       | 7.1%    |
| Unknown          | 461       | 6.07%   |
| Zen+             | 456       | 6.01%   |
| Skylake          | 434       | 5.72%   |
| IvyBridge        | 373       | 4.91%   |
| SandyBridge      | 322       | 4.24%   |
| TigerLake        | 294       | 3.87%   |
| Zen              | 234       | 3.08%   |
| CometLake        | 221       | 2.91%   |
| Broadwell        | 174       | 2.29%   |
| Alderlake Hybrid | 168       | 2.21%   |
| Penryn           | 153       | 2.02%   |
| Icelake          | 135       | 1.78%   |
| Silvermont       | 118       | 1.55%   |
| Westmere         | 113       | 1.49%   |
| Piledriver       | 113       | 1.49%   |
| Goldmont plus    | 64        | 0.84%   |
| K10              | 56        | 0.74%   |
| Excavator        | 51        | 0.67%   |
| Core             | 50        | 0.66%   |
| Nehalem          | 44        | 0.58%   |
| Goldmont         | 34        | 0.45%   |
| Puma             | 21        | 0.28%   |
| K10 Llano        | 21        | 0.28%   |
| Bonnell          | 21        | 0.28%   |
| Bobcat           | 21        | 0.28%   |
| Steamroller      | 20        | 0.26%   |
| Jaguar           | 16        | 0.21%   |
| Tremont          | 14        | 0.18%   |
| K8 Hammer        | 11        | 0.14%   |
| NetBurst         | 8         | 0.11%   |
| Bulldozer        | 8         | 0.11%   |
| Gracemont        | 4         | 0.05%   |
| P6               | 2         | 0.03%   |
| K8 & K10 hybrid  | 2         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3867      | 41.19%  |
| Nvidia                           | 2941      | 31.33%  |
| AMD                              | 2541      | 27.07%  |
| Matrox Electronics Systems       | 20        | 0.21%   |
| ASPEED Technology                | 11        | 0.12%   |
| Silicon Integrated Systems [SiS] | 4         | 0.04%   |
| ATI Technologies                 | 3         | 0.03%   |
| VIA Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 320       | 3.32%   |
| Intel UHD Graphics 620                                                                   | 270       | 2.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 258       | 2.68%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 254       | 2.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 241       | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 226       | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 224       | 2.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 221       | 2.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 216       | 2.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 184       | 1.91%   |
| Intel HD Graphics 630                                                                    | 171       | 1.77%   |
| Intel HD Graphics 620                                                                    | 171       | 1.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 165       | 1.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 156       | 1.62%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 141       | 1.46%   |
| Intel HD Graphics 5500                                                                   | 132       | 1.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 124       | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 121       | 1.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 120       | 1.25%   |
| AMD Lucienne                                                                             | 118       | 1.22%   |
| Intel HD Graphics 530                                                                    | 111       | 1.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 106       | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 103       | 1.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 93        | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 90        | 0.93%   |
| AMD Rembrandt [Radeon 680M]                                                              | 88        | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 87        | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 82        | 0.85%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 82        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 79        | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 79        | 0.82%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 70        | 0.73%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 68        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 0.71%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 67        | 0.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 67        | 0.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 65        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 63        | 0.65%   |
| AMD Raphael                                                                              | 63        | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 59        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2381      | 31.18%  |
| 1 x AMD                  | 1900      | 24.88%  |
| 1 x Nvidia               | 1400      | 18.33%  |
| Intel + Nvidia           | 1203      | 15.75%  |
| AMD + Nvidia             | 300       | 3.93%   |
| Intel + AMD              | 195       | 2.55%   |
| 2 x AMD                  | 149       | 1.95%   |
| 2 x Nvidia               | 38        | 0.5%    |
| 2 x Intel                | 18        | 0.24%   |
| 1 x Matrox               | 15        | 0.2%    |
| Other                    | 8         | 0.1%    |
| 1 x ASPEED               | 6         | 0.08%   |
| 1 x SiS                  | 4         | 0.05%   |
| AMD + ASPEED             | 4         | 0.05%   |
| Nvidia + Matrox          | 3         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.04%   |
| 2 x AMD + 1 x Nvidia     | 2         | 0.03%   |
| Intel + 2 x Nvidia       | 2         | 0.03%   |
| AMD + Matrox             | 2         | 0.03%   |
| 3 x Nvidia               | 1         | 0.01%   |
| 1 x VIA                  | 1         | 0.01%   |
| Nvidia + ASPEED          | 1         | 0.01%   |
| AMD + 2 x Nvidia         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5494      | 71.8%   |
| Proprietary | 2074      | 27.1%   |
| Unknown     | 84        | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4262      | 54.58%  |
| 7.01-8.0   | 749       | 9.59%   |
| 1.01-2.0   | 666       | 8.53%   |
| 0.01-0.5   | 603       | 7.72%   |
| 3.01-4.0   | 583       | 7.47%   |
| 0.51-1.0   | 304       | 3.89%   |
| 5.01-6.0   | 287       | 3.68%   |
| 8.01-16.0  | 258       | 3.3%    |
| 2.01-3.0   | 61        | 0.78%   |
| 16.01-24.0 | 32        | 0.41%   |
| 4.01-5.0   | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1009      | 10.99%  |
| Samsung Electronics     | 995       | 10.83%  |
| BOE                     | 855       | 9.31%   |
| Chimei Innolux          | 738       | 8.04%   |
| LG Display              | 680       | 7.4%    |
| Dell                    | 626       | 6.82%   |
| Goldstar                | 555       | 6.04%   |
| Acer                    | 361       | 3.93%   |
| AOC                     | 291       | 3.17%   |
| BenQ                    | 269       | 2.93%   |
| Hewlett-Packard         | 259       | 2.82%   |
| Sharp                   | 240       | 2.61%   |
| Ancor Communications    | 223       | 2.43%   |
| Philips                 | 179       | 1.95%   |
| Lenovo                  | 152       | 1.66%   |
| PANDA                   | 126       | 1.37%   |
| ViewSonic               | 114       | 1.24%   |
| ASUSTek Computer        | 114       | 1.24%   |
| Apple                   | 111       | 1.21%   |
| Iiyama                  | 95        | 1.03%   |
| InfoVision              | 66        | 0.72%   |
| MSI                     | 62        | 0.68%   |
| CSO                     | 62        | 0.68%   |
| LG Electronics          | 60        | 0.65%   |
| Unknown                 | 53        | 0.58%   |
| Sony                    | 49        | 0.53%   |
| Gigabyte Technology     | 46        | 0.5%    |
| Chi Mei Optoelectronics | 40        | 0.44%   |
| NEC Computers           | 39        | 0.42%   |
| Eizo                    | 35        | 0.38%   |
| TMX                     | 28        | 0.3%    |
| Panasonic               | 26        | 0.28%   |
| Unknown                 | 25        | 0.27%   |
| Fujitsu Siemens         | 24        | 0.26%   |
| Sceptre Tech            | 23        | 0.25%   |
| Vizio                   | 18        | 0.2%    |
| Toshiba                 | 18        | 0.2%    |
| HannStar                | 17        | 0.19%   |
| Valve                   | 16        | 0.17%   |
| HUAWEI                  | 15        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 55        | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 46        | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 45        | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 40        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 36        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 33        | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 32        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 32        | 0.33%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 29        | 0.3%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 29        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 27        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 27        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 26        | 0.27%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 25        | 0.26%   |
| Unknown                                                              | 25        | 0.26%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 24        | 0.25%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 23        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 22        | 0.23%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 22        | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 22        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 20        | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 19        | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 19        | 0.2%    |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch     | 19        | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 18        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 18        | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 17        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 17        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 17        | 0.18%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 17        | 0.18%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 17        | 0.18%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 16        | 0.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 16        | 0.17%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.16%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 15        | 0.16%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch             | 15        | 0.16%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 15        | 0.16%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 15        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 15        | 0.16%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 15        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4138      | 47.9%   |
| 1366x768 (WXGA)    | 972       | 11.25%  |
| 3840x2160 (4K)     | 686       | 7.94%   |
| 2560x1440 (QHD)    | 680       | 7.87%   |
| 1920x1200 (WUXGA)  | 270       | 3.13%   |
| 1600x900 (HD+)     | 220       | 2.55%   |
| 1680x1050 (WSXGA+) | 164       | 1.9%    |
| 3440x1440          | 162       | 1.88%   |
| 1280x1024 (SXGA)   | 146       | 1.69%   |
| Unknown            | 139       | 1.61%   |
| 2560x1600          | 118       | 1.37%   |
| 1440x900 (WXGA+)   | 116       | 1.34%   |
| 2560x1080          | 102       | 1.18%   |
| 2880x1800          | 69        | 0.8%    |
| 1280x800 (WXGA)    | 67        | 0.78%   |
| 3840x1080          | 62        | 0.72%   |
| 1360x768           | 51        | 0.59%   |
| 3840x2400          | 48        | 0.56%   |
| 2256x1504          | 29        | 0.34%   |
| 2160x1440          | 28        | 0.32%   |
| 3840x1600          | 25        | 0.29%   |
| 3200x1800 (QHD+)   | 25        | 0.29%   |
| 1920x540           | 22        | 0.25%   |
| 2736x1824          | 20        | 0.23%   |
| 3000x2000          | 14        | 0.16%   |
| 2288x1287          | 14        | 0.16%   |
| 3200x2000          | 13        | 0.15%   |
| 3072x1920          | 12        | 0.14%   |
| 1600x1200          | 12        | 0.14%   |
| 7680x2160          | 10        | 0.12%   |
| 4480x1440          | 10        | 0.12%   |
| 1920x1280          | 10        | 0.12%   |
| 5760x1080          | 9         | 0.1%    |
| 2240x1400          | 9         | 0.1%    |
| 1280x720 (HD)      | 9         | 0.1%    |
| 1024x600           | 9         | 0.1%    |
| 5120x1440          | 8         | 0.09%   |
| 3456x2160          | 8         | 0.09%   |
| 1024x768 (XGA)     | 8         | 0.09%   |
| 3840x1200          | 6         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2029      | 22.25%  |
| 13      | 916       | 10.04%  |
| 27      | 893       | 9.79%   |
| 24      | 849       | 9.31%   |
| 14      | 788       | 8.64%   |
| 23      | 578       | 6.34%   |
| 21      | 503       | 5.51%   |
| Unknown | 434       | 4.76%   |
| 17      | 323       | 3.54%   |
| 34      | 218       | 2.39%   |
| 31      | 203       | 2.23%   |
| 19      | 174       | 1.91%   |
| 12      | 153       | 1.68%   |
| 16      | 127       | 1.39%   |
| 18      | 122       | 1.34%   |
| 22      | 121       | 1.33%   |
| 20      | 83        | 0.91%   |
| 11      | 63        | 0.69%   |
| 84      | 48        | 0.53%   |
| 72      | 46        | 0.5%    |
| 40      | 43        | 0.47%   |
| 25      | 43        | 0.47%   |
| 32      | 33        | 0.36%   |
| 54      | 32        | 0.35%   |
| 26      | 29        | 0.32%   |
| 48      | 27        | 0.3%    |
| 28      | 26        | 0.29%   |
| 10      | 23        | 0.25%   |
| 37      | 22        | 0.24%   |
| 29      | 21        | 0.23%   |
| 142     | 14        | 0.15%   |
| 65      | 12        | 0.13%   |
| 46      | 12        | 0.13%   |
| 33      | 11        | 0.12%   |
| 49      | 10        | 0.11%   |
| 42      | 9         | 0.1%    |
| 35      | 9         | 0.1%    |
| 43      | 8         | 0.09%   |
| 39      | 7         | 0.08%   |
| 74      | 6         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3337      | 37.77%  |
| 501-600        | 2074      | 23.47%  |
| 401-500        | 883       | 9.99%   |
| 201-300        | 738       | 8.35%   |
| Unknown        | 434       | 4.91%   |
| 351-400        | 417       | 4.72%   |
| 601-700        | 339       | 3.84%   |
| 701-800        | 266       | 3.01%   |
| 1001-1500      | 118       | 1.34%   |
| 1501-2000      | 102       | 1.15%   |
| 801-900        | 87        | 0.98%   |
| 901-1000       | 18        | 0.2%    |
| More than 2000 | 15        | 0.17%   |
| 101-200        | 4         | 0.05%   |
| 1-100          | 4         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5976      | 74.95%  |
| 16/10   | 961       | 12.05%  |
| Unknown | 374       | 4.69%   |
| 21/9    | 268       | 3.36%   |
| 5/4     | 146       | 1.83%   |
| 3/2     | 134       | 1.68%   |
| 4/3     | 39        | 0.49%   |
| 32/9    | 37        | 0.46%   |
| 1.00    | 14        | 0.18%   |
| 2.65    | 4         | 0.05%   |
| 6/5     | 3         | 0.04%   |
| 3.40    | 3         | 0.04%   |
| 2.00    | 3         | 0.04%   |
| 3.20    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 1.03    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |
| 0.57    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2022      | 22.5%   |
| 201-250        | 1604      | 17.85%  |
| 81-90          | 1291      | 14.37%  |
| 301-350        | 917       | 10.21%  |
| 351-500        | 496       | 5.52%   |
| Unknown        | 434       | 4.83%   |
| 71-80          | 410       | 4.56%   |
| 151-200        | 362       | 4.03%   |
| 251-300        | 310       | 3.45%   |
| 121-130        | 235       | 2.62%   |
| More than 1000 | 187       | 2.08%   |
| 141-150        | 160       | 1.78%   |
| 501-1000       | 146       | 1.62%   |
| 61-70          | 134       | 1.49%   |
| 111-120        | 114       | 1.27%   |
| 51-60          | 68        | 0.76%   |
| 91-100         | 34        | 0.38%   |
| 131-140        | 33        | 0.37%   |
| 41-50          | 21        | 0.23%   |
| 1-40           | 7         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2613      | 30.12%  |
| 51-100        | 2520      | 29.05%  |
| 101-120       | 1833      | 21.13%  |
| 161-240       | 794       | 9.15%   |
| Unknown       | 434       | 5%      |
| More than 240 | 328       | 3.78%   |
| 1-50          | 152       | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5641      | 72.78%  |
| 2     | 1655      | 21.35%  |
| 3     | 274       | 3.54%   |
| 0     | 152       | 1.96%   |
| 4     | 26        | 0.34%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4245      | 37.56%  |
| Realtek Semiconductor             | 4095      | 36.24%  |
| Qualcomm Atheros                  | 970       | 8.58%   |
| Broadcom                          | 397       | 3.51%   |
| MediaTek                          | 321       | 2.84%   |
| TP-Link                           | 117       | 1.04%   |
| Ralink Technology                 | 88        | 0.78%   |
| Microsoft                         | 79        | 0.7%    |
| Broadcom Limited                  | 76        | 0.67%   |
| ASIX Electronics                  | 67        | 0.59%   |
| Marvell Technology Group          | 64        | 0.57%   |
| Ralink                            | 56        | 0.5%    |
| Qualcomm                          | 56        | 0.5%    |
| Lenovo                            | 54        | 0.48%   |
| Xiaomi                            | 41        | 0.36%   |
| Samsung Electronics               | 38        | 0.34%   |
| Sierra Wireless                   | 37        | 0.33%   |
| DisplayLink                       | 32        | 0.28%   |
| Aquantia                          | 32        | 0.28%   |
| Ericsson Business Mobile Networks | 27        | 0.24%   |
| D-Link                            | 26        | 0.23%   |
| NetGear                           | 24        | 0.21%   |
| Google                            | 20        | 0.18%   |
| Dell                              | 20        | 0.18%   |
| Qualcomm Atheros Communications   | 19        | 0.17%   |
| Nvidia                            | 17        | 0.15%   |
| Hewlett-Packard                   | 16        | 0.14%   |
| Apple                             | 16        | 0.14%   |
| Mellanox Technologies             | 14        | 0.12%   |
| Huawei Technologies               | 14        | 0.12%   |
| Microchip Technology              | 13        | 0.12%   |
| ASUSTek Computer                  | 12        | 0.11%   |
| Motorola PCS                      | 11        | 0.1%    |
| OPPO Electronics                  | 10        | 0.09%   |
| Fibocom                           | 10        | 0.09%   |
| Linksys                           | 9         | 0.08%   |
| D-Link System                     | 9         | 0.08%   |
| Cypress Semiconductor             | 8         | 0.07%   |
| Oculus VR                         | 7         | 0.06%   |
| JMicron Technology                | 7         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2844      | 21.35%  |
| Intel Wi-Fi 6 AX200                                               | 628       | 4.72%   |
| Intel I211 Gigabit Network Connection                             | 417       | 3.13%   |
| Intel Wireless 8265 / 8275                                        | 310       | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 307       | 2.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 289       | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 254       | 1.91%   |
| Intel Wi-Fi 6 AX201                                               | 223       | 1.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 202       | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 186       | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 182       | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 178       | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 177       | 1.33%   |
| Intel Ethernet Connection (2) I219-V                              | 172       | 1.29%   |
| Intel Wireless 7265                                               | 168       | 1.26%   |
| Intel Wireless 8260                                               | 164       | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 157       | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 143       | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 142       | 1.07%   |
| Intel Ethernet Controller I225-V                                  | 138       | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 136       | 1.02%   |
| Intel Wireless 7260                                               | 127       | 0.95%   |
| Intel Wireless-AC 9260                                            | 118       | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 117       | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 111       | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 108       | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 107       | 0.8%    |
| Intel Wireless 3165                                               | 107       | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 106       | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 103       | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 103       | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 97        | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 95        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 90        | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 88        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 83        | 0.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 70        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 66        | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 64        | 0.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 61        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3348      | 53.38%  |
| Realtek Semiconductor             | 890       | 14.19%  |
| Qualcomm Atheros                  | 762       | 12.15%  |
| MediaTek                          | 313       | 4.99%   |
| Broadcom                          | 304       | 4.85%   |
| TP-Link                           | 101       | 1.61%   |
| Ralink Technology                 | 88        | 1.4%    |
| Microsoft                         | 71        | 1.13%   |
| Broadcom Limited                  | 57        | 0.91%   |
| Ralink                            | 56        | 0.89%   |
| Qualcomm                          | 49        | 0.78%   |
| Sierra Wireless                   | 37        | 0.59%   |
| D-Link                            | 23        | 0.37%   |
| NetGear                           | 22        | 0.35%   |
| Marvell Technology Group          | 22        | 0.35%   |
| Qualcomm Atheros Communications   | 19        | 0.3%    |
| Dell                              | 14        | 0.22%   |
| Ericsson Business Mobile Networks | 11        | 0.18%   |
| ASUSTek Computer                  | 11        | 0.18%   |
| Fibocom                           | 10        | 0.16%   |
| Linksys                           | 9         | 0.14%   |
| Hewlett-Packard                   | 7         | 0.11%   |
| Edimax Technology                 | 6         | 0.1%    |
| D-Link System                     | 5         | 0.08%   |
| AVM                               | 4         | 0.06%   |
| Wilocity                          | 3         | 0.05%   |
| Tenda                             | 3         | 0.05%   |
| Mercucys                          | 3         | 0.05%   |
| IMC Networks                      | 3         | 0.05%   |
| Belkin Components                 | 3         | 0.05%   |
| Unknown                           | 3         | 0.05%   |
| Xiaomi                            | 2         | 0.03%   |
| Micro Star International          | 2         | 0.03%   |
| ZyXEL Communications              | 1         | 0.02%   |
| ZyDAS                             | 1         | 0.02%   |
| Yoctopuce Sarl                    | 1         | 0.02%   |
| Wacom                             | 1         | 0.02%   |
| Sitecom Europe                    | 1         | 0.02%   |
| Sagem                             | 1         | 0.02%   |
| Quectel Wireless Solutions        | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 628       | 9.97%   |
| Intel Wireless 8265 / 8275                                     | 310       | 4.92%   |
| Intel Wi-Fi 6 AX201                                            | 223       | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 186       | 2.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 182       | 2.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 178       | 2.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 177       | 2.81%   |
| Intel Wireless 7265                                            | 168       | 2.67%   |
| Intel Wireless 8260                                            | 164       | 2.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 157       | 2.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 143       | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 142       | 2.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 136       | 2.16%   |
| Intel Wireless 7260                                            | 127       | 2.02%   |
| Intel Wireless-AC 9260                                         | 118       | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 117       | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 111       | 1.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 108       | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 107       | 1.7%    |
| Intel Wireless 3165                                            | 107       | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 106       | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 103       | 1.63%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 99        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 97        | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 90        | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 70        | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 64        | 1.02%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 61        | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 58        | 0.92%   |
| Intel Wireless 3160                                            | 54        | 0.86%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 53        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 50        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 47        | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 42        | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 42        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                  | 39        | 0.62%   |
| Realtek 802.11ac NIC                                           | 37        | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 36        | 0.57%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 35        | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                            | 34        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3717      | 55.35%  |
| Intel                                  | 2073      | 30.87%  |
| Qualcomm Atheros                       | 279       | 4.15%   |
| Broadcom                               | 147       | 2.19%   |
| ASIX Electronics                       | 67        | 1%      |
| Lenovo                                 | 49        | 0.73%   |
| Marvell Technology Group               | 42        | 0.63%   |
| Xiaomi                                 | 39        | 0.58%   |
| DisplayLink                            | 32        | 0.48%   |
| Aquantia                               | 32        | 0.48%   |
| Samsung Electronics                    | 21        | 0.31%   |
| Broadcom Limited                       | 19        | 0.28%   |
| Google                                 | 18        | 0.27%   |
| Nvidia                                 | 17        | 0.25%   |
| TP-Link                                | 16        | 0.24%   |
| Apple                                  | 16        | 0.24%   |
| Mellanox Technologies                  | 12        | 0.18%   |
| OPPO Electronics                       | 10        | 0.15%   |
| MediaTek                               | 9         | 0.13%   |
| Motorola PCS                           | 8         | 0.12%   |
| Cypress Semiconductor                  | 8         | 0.12%   |
| Qualcomm                               | 7         | 0.1%    |
| Microsoft                              | 7         | 0.1%    |
| JMicron Technology                     | 7         | 0.1%    |
| Huawei Technologies                    | 7         | 0.1%    |
| ICS Advent                             | 5         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.06%   |
| D-Link System                          | 4         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.04%   |
| QLogic                                 | 3         | 0.04%   |
| Hewlett-Packard                        | 3         | 0.04%   |
| D-Link                                 | 3         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.03%   |
| NetGear                                | 2         | 0.03%   |
| IBM                                    | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Emulex                                 | 2         | 0.03%   |
| American Megatrends                    | 2         | 0.03%   |
| Xilinx                                 | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2844      | 41.29%  |
| Intel I211 Gigabit Network Connection                             | 417       | 6.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 307       | 4.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 289       | 4.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 254       | 3.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 202       | 2.93%   |
| Intel Ethernet Connection (2) I219-V                              | 172       | 2.5%    |
| Intel Ethernet Controller I225-V                                  | 138       | 2%      |
| Intel Ethernet Connection (7) I219-V                              | 95        | 1.38%   |
| Intel Ethernet Connection I217-LM                                 | 88        | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 83        | 1.2%    |
| Intel Ethernet Connection (4) I219-V                              | 66        | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 56        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 54        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 54        | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 51        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 51        | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 49        | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 49        | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 47        | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 44        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 44        | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 42        | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 39        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 32        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 29        | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 29        | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                             | 28        | 0.41%   |
| Intel 82567LM Gigabit Network Connection                          | 27        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 25        | 0.36%   |
| Intel Ethernet Connection I219-V                                  | 25        | 0.36%   |
| Intel Ethernet Connection (10) I219-V                             | 25        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 25        | 0.36%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 25        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 23        | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 22        | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                             | 20        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6267      | 50.7%   |
| WiFi     | 5966      | 48.27%  |
| Modem    | 110       | 0.89%   |
| Unknown  | 17        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4565      | 57.3%   |
| Ethernet | 3398      | 42.65%  |
| Modem    | 4         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4025      | 52.95%  |
| 1     | 3249      | 42.74%  |
| 3     | 217       | 2.85%   |
| 0     | 64        | 0.84%   |
| 4     | 30        | 0.39%   |
| 5     | 9         | 0.12%   |
| 6     | 5         | 0.07%   |
| 10    | 1         | 0.01%   |
| 9     | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6227      | 80.96%  |
| Yes  | 1464      | 19.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2971      | 53.78%  |
| Realtek Semiconductor           | 501       | 9.07%   |
| Cambridge Silicon Radio         | 354       | 6.41%   |
| Qualcomm Atheros Communications | 304       | 5.5%    |
| IMC Networks                    | 231       | 4.18%   |
| Broadcom                        | 196       | 3.55%   |
| Foxconn / Hon Hai               | 192       | 3.48%   |
| Lite-On Technology              | 164       | 2.97%   |
| ASUSTek Computer                | 119       | 2.15%   |
| Apple                           | 112       | 2.03%   |
| MediaTek                        | 92        | 1.67%   |
| Realtek                         | 55        | 1%      |
| Dell                            | 39        | 0.71%   |
| TP-Link                         | 26        | 0.47%   |
| USI                             | 22        | 0.4%    |
| Hewlett-Packard                 | 22        | 0.4%    |
| Marvell Semiconductor           | 20        | 0.36%   |
| HTC (High Tech Computer)        | 16        | 0.29%   |
| Toshiba                         | 14        | 0.25%   |
| Ralink                          | 14        | 0.25%   |
| Foxconn International           | 8         | 0.14%   |
| Edimax Technology               | 8         | 0.14%   |
| Dynex                           | 6         | 0.11%   |
| Opticis                         | 5         | 0.09%   |
| Integrated System Solution      | 4         | 0.07%   |
| Smart Modular Technologies      | 3         | 0.05%   |
| Micro Star International        | 3         | 0.05%   |
| Chicony Electronics             | 3         | 0.05%   |
| Belkin Components               | 3         | 0.05%   |
| Askey Computer                  | 3         | 0.05%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Ralink Technology               | 2         | 0.04%   |
| Alps Electric                   | 2         | 0.04%   |
| Actions                         | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 896       | 16.19%  |
| Intel Bluetooth Device                              | 632       | 11.42%  |
| Intel AX200 Bluetooth                               | 601       | 10.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 384       | 6.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 354       | 6.4%    |
| Realtek Bluetooth Radio                             | 329       | 5.95%   |
| Qualcomm Atheros  Bluetooth Device                  | 166       | 3%      |
| Intel AX210 Bluetooth                               | 156       | 2.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 140       | 2.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 110       | 1.99%   |
| Realtek  Bluetooth 4.2 Adapter                      | 104       | 1.88%   |
| IMC Networks Wireless_Device                        | 92        | 1.66%   |
| MediaTek Wireless_Device                            | 91        | 1.64%   |
| IMC Networks Bluetooth Radio                        | 70        | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 63        | 1.14%   |
| Realtek Bluetooth Radio                             | 55        | 0.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 53        | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 52        | 0.94%   |
| Lite-On Bluetooth Device                            | 51        | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 50        | 0.9%    |
| Apple Bluetooth USB Host Controller                 | 48        | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 47        | 0.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 46        | 0.83%   |
| Apple Bluetooth Host Controller                     | 45        | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 42        | 0.76%   |
| IMC Networks Bluetooth Device                       | 41        | 0.74%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 39        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 37        | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 33        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.51%   |
| TP-Link UB500 Adapter                               | 26        | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 24        | 0.43%   |
| Lite-On Wireless_Device                             | 24        | 0.43%   |
| ASUS Bluetooth Device                               | 23        | 0.42%   |
| USI Bluetooth Device                                | 22        | 0.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 21        | 0.38%   |
| ASUS Qualcomm Bluetooth 4.1                         | 19        | 0.34%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 18        | 0.33%   |
| Realtek RTL8821A Bluetooth                          | 17        | 0.31%   |
| Marvell Bluetooth and Wireless LAN Composite        | 16        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4816      | 40.11%  |
| AMD                                  | 2947      | 24.54%  |
| Nvidia                               | 2237      | 18.63%  |
| C-Media Electronics                  | 270       | 2.25%   |
| Logitech                             | 139       | 1.16%   |
| Kingston Technology                  | 98        | 0.82%   |
| Texas Instruments                    | 81        | 0.67%   |
| Focusrite-Novation                   | 80        | 0.67%   |
| JMTek                                | 75        | 0.62%   |
| SteelSeries ApS                      | 69        | 0.57%   |
| Razer USA                            | 67        | 0.56%   |
| Realtek Semiconductor                | 61        | 0.51%   |
| Lenovo                               | 54        | 0.45%   |
| Creative Technology                  | 49        | 0.41%   |
| Creative Labs                        | 49        | 0.41%   |
| ASUSTek Computer                     | 48        | 0.4%    |
| Corsair                              | 46        | 0.38%   |
| Blue Microphones                     | 44        | 0.37%   |
| GN Netcom                            | 39        | 0.32%   |
| Samson Technologies                  | 29        | 0.24%   |
| Generalplus Technology               | 29        | 0.24%   |
| Micro Star International             | 25        | 0.21%   |
| Valve Software                       | 24        | 0.2%    |
| Apple                                | 24        | 0.2%    |
| Sony                                 | 23        | 0.19%   |
| Yamaha                               | 22        | 0.18%   |
| GYROCOM C&C                          | 22        | 0.18%   |
| BEHRINGER International              | 21        | 0.17%   |
| RODE Microphones                     | 18        | 0.15%   |
| XMOS                                 | 16        | 0.13%   |
| Plantronics                          | 16        | 0.13%   |
| M-Audio                              | 16        | 0.13%   |
| FiiO Electronics Technology          | 16        | 0.13%   |
| SAVITECH                             | 15        | 0.12%   |
| Audio-Technica                       | 15        | 0.12%   |
| Hewlett-Packard                      | 14        | 0.12%   |
| DSEA A/S                             | 13        | 0.11%   |
| Thesycon Systemsoftware & Consulting | 12        | 0.1%    |
| Microsoft                            | 11        | 0.09%   |
| Dell                                 | 11        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1154      | 7.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 667       | 4.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 666       | 4.58%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 568       | 3.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 382       | 2.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 361       | 2.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 346       | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 322       | 2.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 294       | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 285       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 284       | 1.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 277       | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 256       | 1.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 231       | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 225       | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 203       | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 200       | 1.38%   |
| Intel 200 Series PCH HD Audio                                              | 197       | 1.36%   |
| Nvidia GP104 High Definition Audio Controller                              | 189       | 1.3%    |
| AMD Navi 10 HDMI Audio                                                     | 180       | 1.24%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 179       | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 161       | 1.11%   |
| Intel Comet Lake PCH cAVS                                                  | 161       | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                      | 158       | 1.09%   |
| Intel 8 Series HD Audio Controller                                         | 158       | 1.09%   |
| Intel Broadwell-U Audio Controller                                         | 156       | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 155       | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 154       | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                              | 152       | 1.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 151       | 1.04%   |
| Nvidia GA104 High Definition Audio Controller                              | 146       | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 142       | 0.98%   |
| Intel CM238 HD Audio Controller                                            | 135       | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                               | 129       | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 127       | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 119       | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 114       | 0.78%   |
| Nvidia Audio device                                                        | 113       | 0.78%   |
| AMD FCH Azalia Controller                                                  | 109       | 0.75%   |
| Nvidia TU104 HD Audio Controller                                           | 108       | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1340      | 20.9%   |
| SK hynix                     | 1009      | 15.74%  |
| Kingston                     | 797       | 12.43%  |
| Micron Technology            | 630       | 9.83%   |
| Corsair                      | 616       | 9.61%   |
| Crucial                      | 502       | 7.83%   |
| G.Skill                      | 392       | 6.12%   |
| Unknown                      | 324       | 5.05%   |
| A-DATA Technology            | 129       | 2.01%   |
| Ramaxel Technology           | 99        | 1.54%   |
| Team                         | 64        | 1%      |
| Elpida                       | 57        | 0.89%   |
| Patriot                      | 50        | 0.78%   |
| Unknown                      | 47        | 0.73%   |
| GOODRAM                      | 36        | 0.56%   |
| Nanya Technology             | 31        | 0.48%   |
| Unknown (ABCD)               | 23        | 0.36%   |
| Transcend                    | 22        | 0.34%   |
| Smart                        | 22        | 0.34%   |
| AMD                          | 17        | 0.27%   |
| PNY                          | 15        | 0.23%   |
| Apacer                       | 11        | 0.17%   |
| Goldkey                      | 10        | 0.16%   |
| Smart Brazil                 | 7         | 0.11%   |
| Silicon Power                | 7         | 0.11%   |
| Kingmax                      | 7         | 0.11%   |
| Teikon                       | 6         | 0.09%   |
| Golden Empire                | 6         | 0.09%   |
| GeIL                         | 5         | 0.08%   |
| Avant                        | 5         | 0.08%   |
| Wilk Elektronik              | 4         | 0.06%   |
| Patriot Memory (PDP Systems) | 4         | 0.06%   |
| Neo Forza                    | 4         | 0.06%   |
| KLEVV                        | 4         | 0.06%   |
| Wilk                         | 3         | 0.05%   |
| V-GeN                        | 3         | 0.05%   |
| V-Color                      | 3         | 0.05%   |
| Timetec                      | 3         | 0.05%   |
| Lexar                        | 3         | 0.05%   |
| Kllisre                      | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 75        | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 73        | 1.07%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 70        | 1.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 69        | 1.01%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 56        | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 49        | 0.72%   |
| Unknown                                                     | 47        | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 43        | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 41        | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s    | 39        | 0.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 38        | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 33        | 0.48%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s        | 33        | 0.48%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 31        | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 31        | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 30        | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 30        | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 29        | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 29        | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 29        | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 29        | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 28        | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s    | 28        | 0.41%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 28        | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 27        | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 26        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 26        | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 26        | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 26        | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 24        | 0.35%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 24        | 0.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s         | 24        | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s    | 23        | 0.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 22        | 0.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s   | 21        | 0.31%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 21        | 0.31%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 21        | 0.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 20        | 0.29%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 20        | 0.29%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s           | 20        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 3369      | 61.07%  |
| DDR3    | 1258      | 22.8%   |
| LPDDR4  | 219       | 3.97%   |
| DDR5    | 188       | 3.41%   |
| LPDDR3  | 158       | 2.86%   |
| LPDDR5  | 99        | 1.79%   |
| SDRAM   | 70        | 1.27%   |
| Unknown | 70        | 1.27%   |
| DDR2    | 66        | 1.2%    |
| DDR     | 17        | 0.31%   |
| DRAM    | 3         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2890      | 52.35%  |
| DIMM         | 2081      | 37.69%  |
| Row Of Chips | 486       | 8.8%    |
| Chip         | 42        | 0.76%   |
| Unknown      | 17        | 0.31%   |
| RIMM         | 3         | 0.05%   |
| FB-DIMM      | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2734      | 45.61%  |
| 4096  | 1280      | 21.35%  |
| 16384 | 1194      | 19.92%  |
| 2048  | 383       | 6.39%   |
| 32768 | 328       | 5.47%   |
| 1024  | 65        | 1.08%   |
| 512   | 7         | 0.12%   |
| 65536 | 2         | 0.03%   |
| 49152 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 1120      | 18.53%  |
| 2667    | 920       | 15.22%  |
| 1600    | 816       | 13.5%   |
| 2400    | 451       | 7.46%   |
| 3600    | 306       | 5.06%   |
| 2133    | 299       | 4.95%   |
| 1333    | 232       | 3.84%   |
| 1867    | 140       | 2.32%   |
| 4267    | 118       | 1.95%   |
| 4800    | 113       | 1.87%   |
| 6400    | 109       | 1.8%    |
| 1334    | 109       | 1.8%    |
| 3733    | 105       | 1.74%   |
| 3400    | 89        | 1.47%   |
| 3266    | 82        | 1.36%   |
| 3000    | 67        | 1.11%   |
| 3800    | 66        | 1.09%   |
| 2933    | 64        | 1.06%   |
| 3533    | 59        | 0.98%   |
| 667     | 52        | 0.86%   |
| 2666    | 49        | 0.81%   |
| 1866    | 44        | 0.73%   |
| 1067    | 41        | 0.68%   |
| Unknown | 39        | 0.65%   |
| 3866    | 36        | 0.6%    |
| 4266    | 35        | 0.58%   |
| 3666    | 34        | 0.56%   |
| 800     | 33        | 0.55%   |
| 1066    | 32        | 0.53%   |
| 5600    | 31        | 0.51%   |
| 3466    | 30        | 0.5%    |
| 2800    | 30        | 0.5%    |
| 1800    | 26        | 0.43%   |
| 6000    | 22        | 0.36%   |
| 4199    | 20        | 0.33%   |
| 8400    | 19        | 0.31%   |
| 4000    | 12        | 0.2%    |
| 3333    | 12        | 0.2%    |
| 2048    | 12        | 0.2%    |
| 400     | 12        | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 37        | 35.58%  |
| Brother Industries       | 18        | 17.31%  |
| Samsung Electronics      | 13        | 12.5%   |
| Canon                    | 13        | 12.5%   |
| Seiko Epson              | 4         | 3.85%   |
| Prolific Technology      | 4         | 3.85%   |
| Dymo-CoStar              | 3         | 2.88%   |
| Xerox                    | 2         | 1.92%   |
| STMicroelectronics       | 2         | 1.92%   |
| Zebra                    | 1         | 0.96%   |
| XiaoMi                   | 1         | 0.96%   |
| Ricoh                    | 1         | 0.96%   |
| QinHeng Electronics      | 1         | 0.96%   |
| Philips (or NXP)         | 1         | 0.96%   |
| Magic Control Technology | 1         | 0.96%   |
| Fuji Xerox               | 1         | 0.96%   |
| Dell                     | 1         | 0.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                             | 4         | 3.85%   |
| Samsung M2070 Series                                      | 3         | 2.88%   |
| HP DeskJet 2130 series                                    | 3         | 2.88%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.92%   |
| Samsung SCX-4100 Scanner                                  | 2         | 1.92%   |
| HP Officejet Pro 8100                                     | 2         | 1.92%   |
| HP LaserJet P2015 series                                  | 2         | 1.92%   |
| HP LaserJet 1022                                          | 2         | 1.92%   |
| HP LaserJet 1018                                          | 2         | 1.92%   |
| HP LaserJet 1012                                          | 2         | 1.92%   |
| HP DeskJet F4200 series                                   | 2         | 1.92%   |
| HP DeskJet 840c                                           | 2         | 1.92%   |
| HP Deskjet 3050 J610 series                               | 2         | 1.92%   |
| HP DeskJet 2600 series                                    | 2         | 1.92%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 1.92%   |
| Brother Printer                                           | 2         | 1.92%   |
| Brother HL-L2320D series                                  | 2         | 1.92%   |
| Brother HL-5370DW series                                  | 2         | 1.92%   |
| Brother DCP-1510                                          | 2         | 1.92%   |
| Zebra LP2844 Printer                                      | 1         | 0.96%   |
| XiaoMi MIIIW MECH-KBPro                                   | 1         | 0.96%   |
| Xerox Phaser 3020                                         | 1         | 0.96%   |
| Xerox Phaser 3010                                         | 1         | 0.96%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.96%   |
| Seiko Epson WF-2530 Series                                | 1         | 0.96%   |
| Seiko Epson Printer                                       | 1         | 0.96%   |
| Seiko Epson L3110 Series                                  | 1         | 0.96%   |
| Samsung SCX-4200 series                                   | 1         | 0.96%   |
| Samsung SCX-3200 Series                                   | 1         | 0.96%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 0.96%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 0.96%   |
| Samsung M267x 287x Series                                 | 1         | 0.96%   |
| Samsung M2020 Series                                      | 1         | 0.96%   |
| Samsung CLP-325 Color Laser Printer                       | 1         | 0.96%   |
| Samsung C1860 Series                                      | 1         | 0.96%   |
| Ricoh SP 150SU                                            | 1         | 0.96%   |
| QinHeng CH340S                                            | 1         | 0.96%   |
| Philips (or NXP) USB Printer                              | 1         | 0.96%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 0.96%   |
| HP PSC-1315/PSC-1317                                      | 1         | 0.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 10        | 55.56%  |
| Seiko Epson    | 6         | 33.33%  |
| Mustek Systems | 2         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2         | 11.11%  |
| Canon CanoScan N650U/N656U                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 200                                     | 2         | 11.11%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.56%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 5.56%   |
| Seiko Epson GT-F700 [Perfection V350]                       | 1         | 5.56%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.56%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 5.56%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 5.56%   |
| Canon CanoScan LiDE 60                                      | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.56%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.56%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 951       | 19.54%  |
| IMC Networks                           | 538       | 11.05%  |
| Logitech                               | 427       | 8.77%   |
| Microdia                               | 395       | 8.11%   |
| Bison Electronics                      | 353       | 7.25%   |
| Realtek Semiconductor                  | 323       | 6.64%   |
| Quanta                                 | 267       | 5.48%   |
| Sunplus Innovation Technology          | 224       | 4.6%    |
| Cheng Uei Precision Industry (Foxlink) | 152       | 3.12%   |
| Syntek                                 | 133       | 2.73%   |
| Lite-On Technology                     | 111       | 2.28%   |
| Luxvisions Innotech Limited            | 101       | 2.07%   |
| Apple                                  | 100       | 2.05%   |
| Suyin                                  | 70        | 1.44%   |
| Acer                                   | 65        | 1.34%   |
| Microsoft                              | 60        | 1.23%   |
| Samsung Electronics                    | 51        | 1.05%   |
| Sonix Technology                       | 46        | 0.94%   |
| Alcor Micro                            | 46        | 0.94%   |
| Silicon Motion                         | 45        | 0.92%   |
| Lenovo                                 | 32        | 0.66%   |
| SunplusIT                              | 27        | 0.55%   |
| Z-Star Microelectronics                | 23        | 0.47%   |
| MacroSilicon                           | 21        | 0.43%   |
| Valve Software                         | 20        | 0.41%   |
| ARC International                      | 16        | 0.33%   |
| Importek                               | 14        | 0.29%   |
| Ricoh                                  | 13        | 0.27%   |
| Razer USA                              | 13        | 0.27%   |
| Generalplus Technology                 | 12        | 0.25%   |
| Creative Technology                    | 12        | 0.25%   |
| KYE Systems (Mouse Systems)            | 11        | 0.23%   |
| ALi                                    | 11        | 0.23%   |
| Primax Electronics                     | 10        | 0.21%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.18%   |
| Jieli Technology                       | 9         | 0.18%   |
| LG Electronics                         | 8         | 0.16%   |
| Trust                                  | 6         | 0.12%   |
| Hewlett-Packard                        | 6         | 0.12%   |
| Google                                 | 6         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 279       | 5.67%   |
| Microdia Integrated_Webcam_HD                                              | 194       | 3.94%   |
| IMC Networks Integrated Camera                                             | 177       | 3.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 169       | 3.44%   |
| Bison Integrated Camera                                                    | 131       | 2.66%   |
| Realtek Integrated_Webcam_HD                                               | 124       | 2.52%   |
| Sunplus Integrated_Webcam_HD                                               | 97        | 1.97%   |
| Chicony HD WebCam                                                          | 94        | 1.91%   |
| Syntek Integrated Camera                                                   | 92        | 1.87%   |
| Logitech HD Pro Webcam C920                                                | 89        | 1.81%   |
| Logitech Webcam C270                                                       | 69        | 1.4%    |
| Lite-On Integrated Camera                                                  | 56        | 1.14%   |
| Quanta HD User Facing                                                      | 55        | 1.12%   |
| Bison HD Webcam                                                            | 54        | 1.1%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 51        | 1.04%   |
| Bison SunplusIT Integrated Camera                                          | 47        | 0.96%   |
| Chicony HD User Facing                                                     | 41        | 0.83%   |
| Chicony Integrated Camera (1280x720@30)                                    | 40        | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 39        | 0.79%   |
| Chicony HP Wide Vision HD Camera                                           | 39        | 0.79%   |
| Chicony HP HD Camera                                                       | 39        | 0.79%   |
| Chicony USB2.0 Camera                                                      | 36        | 0.73%   |
| Apple FaceTime HD Camera (Built-in)                                        | 36        | 0.73%   |
| Realtek USB Camera                                                         | 35        | 0.71%   |
| Logitech C922 Pro Stream Webcam                                            | 35        | 0.71%   |
| Microdia Integrated Webcam                                                 | 33        | 0.67%   |
| Quanta HP Wide Vision HD Camera                                            | 32        | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 32        | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 30        | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 30        | 0.61%   |
| IMC Networks HD Camera                                                     | 28        | 0.57%   |
| Chicony HP Truevision HD                                                   | 28        | 0.57%   |
| Microdia Webcam Vitade AF                                                  | 26        | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 26        | 0.53%   |
| Realtek Integrated Webcam                                                  | 25        | 0.51%   |
| Chicony Integrated IR Camera                                               | 25        | 0.51%   |
| Quanta HP TrueVision HD Camera                                             | 24        | 0.49%   |
| Logitech Webcam C310                                                       | 24        | 0.49%   |
| Chicony HP TrueVision HD Camera                                            | 24        | 0.49%   |
| Chicony EasyCamera                                                         | 24        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 386       | 37.26%  |
| Validity Sensors                   | 265       | 25.58%  |
| Shenzhen Goodix Technology         | 200       | 19.31%  |
| Elan Microelectronics              | 66        | 6.37%   |
| LighTuning Technology              | 36        | 3.47%   |
| Upek                               | 30        | 2.9%    |
| AuthenTec                          | 21        | 2.03%   |
| STMicroelectronics                 | 10        | 0.97%   |
| Samsung Electronics                | 6         | 0.58%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 0.58%   |
| Microsoft                          | 4         | 0.39%   |
| HOLTEK                             | 4         | 0.39%   |
| Focal-systems.Corp                 | 1         | 0.1%    |
| DigitalPersona                     | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 133       | 12.84%  |
| Shenzhen Goodix  Fingerprint Device                                        | 105       | 10.14%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 61        | 5.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 55        | 5.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 46        | 4.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 4.15%   |
| Shenzhen Goodix FingerPrint                                                | 40        | 3.86%   |
| Validity Sensors Synaptics WBDI                                            | 38        | 3.67%   |
| Elan ELAN:Fingerprint                                                      | 37        | 3.57%   |
| Synaptics UWP WBDI                                                         | 30        | 2.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 29        | 2.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 2.7%    |
| Elan ELAN:ARM-M4                                                           | 27        | 2.61%   |
| Synaptics WBDI                                                             | 22        | 2.12%   |
| Synaptics  WBDI                                                            | 22        | 2.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 21        | 2.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 21        | 2.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 21        | 2.03%   |
| Synaptics Fingerprint reader [HP G6]                                       | 20        | 1.93%   |
| Synaptics UWP WBDI Device                                                  | 17        | 1.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 1.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.45%   |
| Validity Sensors VFS491                                                    | 14        | 1.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 14        | 1.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 14        | 1.35%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 1.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.06%   |
| AuthenTec AES2810                                                          | 11        | 1.06%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 0.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 0.87%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 0.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.58%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 0.58%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 0.48%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 5         | 0.48%   |
| Synaptics TouchPad                                                         | 5         | 0.48%   |
| LighTuning Fingerprint Sensor                                              | 5         | 0.48%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.39%   |
| Synaptics WBDI Device                                                      | 4         | 0.39%   |
| Synaptics Fingerprint scanner                                              | 4         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 160       | 40.1%   |
| Broadcom                          | 135       | 33.83%  |
| Upek                              | 25        | 6.27%   |
| Lenovo                            | 13        | 3.26%   |
| O2 Micro                          | 12        | 3.01%   |
| Clay Logic                        | 8         | 2.01%   |
| Yubico.com                        | 7         | 1.75%   |
| Gemalto (was Gemplus)             | 7         | 1.75%   |
| Advanced Card Systems             | 7         | 1.75%   |
| SCM Microsystems                  | 6         | 1.5%    |
| Reiner SCT Kartensysteme          | 4         | 1%      |
| Aladdin Knowledge Systems         | 3         | 0.75%   |
| OmniKey                           | 2         | 0.5%    |
| Aktiv                             | 2         | 0.5%    |
| VASCO Data Security International | 1         | 0.25%   |
| Realtek Semiconductor             | 1         | 0.25%   |
| Microchip Technology              | 1         | 0.25%   |
| Hewlett-Packard                   | 1         | 0.25%   |
| Fujitsu Siemens Computers         | 1         | 0.25%   |
| Chicony Electronics               | 1         | 0.25%   |
| C3PO                              | 1         | 0.25%   |
| Aladdin R.D.                      | 1         | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 158       | 39.6%   |
| Broadcom 5880                                                                | 36        | 9.02%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 8.52%   |
| Broadcom 58200                                                               | 33        | 8.27%   |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 7.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 25        | 6.27%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 3.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 2.76%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 7         | 1.75%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 4         | 1%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.75%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.75%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.75%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.75%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.75%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.5%    |
| Clay Logic Nitrokey Start                                                    | 2         | 0.5%    |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.5%    |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.5%    |
| Aktiv Rutoken lite                                                           | 2         | 0.5%    |
| Advanced Card Systems ACR122U                                                | 2         | 0.5%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.25%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.25%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.25%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.25%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.25%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.25%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.25%   |
| OmniKey 5022 Smart Card Reader                                               | 1         | 0.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.25%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.25%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.25%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.25%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.25%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.25%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.25%   |
| C3PO LTC31v2                                                                 | 1         | 0.25%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.25%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5380      | 69.56%  |
| 1     | 1897      | 24.53%  |
| 2     | 365       | 4.72%   |
| 3     | 77        | 1%      |
| 4     | 11        | 0.14%   |
| 6     | 2         | 0.03%   |
| 7     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1011      | 35.91%  |
| Graphics card            | 540       | 19.18%  |
| Chipcard                 | 340       | 12.08%  |
| Net/wireless             | 245       | 8.7%    |
| Multimedia controller    | 204       | 7.25%   |
| Camera                   | 141       | 5.01%   |
| Unassigned class         | 60        | 2.13%   |
| Bluetooth                | 57        | 2.02%   |
| Communication controller | 53        | 1.88%   |
| Sound                    | 42        | 1.49%   |
| Net/ethernet             | 29        | 1.03%   |
| Network                  | 23        | 0.82%   |
| Storage                  | 20        | 0.71%   |
| Card reader              | 18        | 0.64%   |
| Modem                    | 11        | 0.39%   |
| Dvb card                 | 8         | 0.28%   |
| Wireless                 | 2         | 0.07%   |
| Tv card                  | 2         | 0.07%   |
| Storage/raid             | 2         | 0.07%   |
| Storage/nvme             | 2         | 0.07%   |
| Storage/ide              | 2         | 0.07%   |
| Storage/ata              | 1         | 0.04%   |
| Flash memory             | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |

