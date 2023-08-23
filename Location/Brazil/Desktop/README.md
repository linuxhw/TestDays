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

Total: 7334

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | DG31PR AAE58249-301         | [28bc891b6d](https://linux-hardware.org/?probe=28bc891b6d) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | [3050db3fbf](https://linux-hardware.org/?probe=3050db3fbf) | Aug 12, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [f8fa12cc07](https://linux-hardware.org/?probe=f8fa12cc07) | Aug 11, 2023 |
| Gigabyte      | A520M DS3H AC               | [c53eeb4caf](https://linux-hardware.org/?probe=c53eeb4caf) | Aug 11, 2023 |
| ASRock        | H310CM-HG4                  | [773b111412](https://linux-hardware.org/?probe=773b111412) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | [70c4f2863b](https://linux-hardware.org/?probe=70c4f2863b) | Aug 10, 2023 |
| ASUSTek       | P8Z68-V                     | [cff11cda6f](https://linux-hardware.org/?probe=cff11cda6f) | Aug 10, 2023 |
| Dell          | 03KWTV A02                  | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| HP            | 2AF9                        | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Dell          | OptiPlex 755                | [279ed1e2d5](https://linux-hardware.org/?probe=279ed1e2d5) | Aug 10, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [7acbd56a40](https://linux-hardware.org/?probe=7acbd56a40) | Aug 10, 2023 |
| MSI           | A68HM-E33                   | [be692e44b5](https://linux-hardware.org/?probe=be692e44b5) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [0c4903c4d2](https://linux-hardware.org/?probe=0c4903c4d2) | Aug 10, 2023 |
| Gigabyte      | G31M-ES2L                   | [1e856f651d](https://linux-hardware.org/?probe=1e856f651d) | Aug 09, 2023 |
| Gigabyte      | B450 AORUS M                | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [e315608a65](https://linux-hardware.org/?probe=e315608a65) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [0b1144add1](https://linux-hardware.org/?probe=0b1144add1) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Biostar       | X370GT3                     | [6c4e484a34](https://linux-hardware.org/?probe=6c4e484a34) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | [dace48c9ec](https://linux-hardware.org/?probe=dace48c9ec) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | [e4c0e430b2](https://linux-hardware.org/?probe=e4c0e430b2) | Aug 09, 2023 |
| Itautec       | ST 4273 ST-4273 Custom 0... | [2e2f861c7c](https://linux-hardware.org/?probe=2e2f861c7c) | Aug 09, 2023 |
| ASRock        | A320M-HDV R4.0              | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [88c76f027a](https://linux-hardware.org/?probe=88c76f027a) | Aug 08, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [b477184f03](https://linux-hardware.org/?probe=b477184f03) | Aug 08, 2023 |
| Digiboard     | NM70-I                      | [280ee6d8fe](https://linux-hardware.org/?probe=280ee6d8fe) | Aug 07, 2023 |
| Unknown       | Unknown                     | [e2427beca2](https://linux-hardware.org/?probe=e2427beca2) | Aug 07, 2023 |
| ASUSTek       | P8H61-M LX3                 | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| Gigabyte      | B450M GAMING                | [570d622bb5](https://linux-hardware.org/?probe=570d622bb5) | Aug 06, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [27792f16e2](https://linux-hardware.org/?probe=27792f16e2) | Aug 06, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | [29f8d73c0e](https://linux-hardware.org/?probe=29f8d73c0e) | Aug 05, 2023 |
| Intel         | B75                         | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| Gigabyte      | H110M-H-CF                  | [17ea53b0c6](https://linux-hardware.org/?probe=17ea53b0c6) | Aug 05, 2023 |
| Intel         | H81                         | [4441a1a1ca](https://linux-hardware.org/?probe=4441a1a1ca) | Aug 05, 2023 |
| ASUSTek       | P8Z77-V LX                  | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| MANCER        | A320M-DA 1006               | [573affec7b](https://linux-hardware.org/?probe=573affec7b) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M LX3                | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| OEM           | B75 Ver:1.44                | [6dcf79b752](https://linux-hardware.org/?probe=6dcf79b752) | Aug 03, 2023 |
| Intel         | H61                         | [7b2774c1a1](https://linux-hardware.org/?probe=7b2774c1a1) | Aug 03, 2023 |
| Intel         | H61                         | [8d450f7e6e](https://linux-hardware.org/?probe=8d450f7e6e) | Aug 03, 2023 |
| Win elemen... | M600                        | [b9537c621c](https://linux-hardware.org/?probe=b9537c621c) | Aug 02, 2023 |
| Unknown       | Unknown                     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [11d27dea01](https://linux-hardware.org/?probe=11d27dea01) | Aug 02, 2023 |
| Gigabyte      | B450 AORUS M                | [518512fe78](https://linux-hardware.org/?probe=518512fe78) | Aug 02, 2023 |
| Dell          | 0GY6Y8 A02                  | [e1d2deb748](https://linux-hardware.org/?probe=e1d2deb748) | Aug 02, 2023 |
| Dell          | 0FR6WH A01                  | [38feb4d1f7](https://linux-hardware.org/?probe=38feb4d1f7) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| Gigabyte      | B450 AORUS M                | [0ced83ffed](https://linux-hardware.org/?probe=0ced83ffed) | Aug 02, 2023 |
| ASRock        | H410M-HDV/M.2               | [71a11bdffd](https://linux-hardware.org/?probe=71a11bdffd) | Aug 02, 2023 |
| ASRock        | B650M PG Riptide            | [bdccf9a3db](https://linux-hardware.org/?probe=bdccf9a3db) | Aug 01, 2023 |
| Lenovo        | 3188 SDK0J40709 WIN 3259... | [59e7f97f2d](https://linux-hardware.org/?probe=59e7f97f2d) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [668eb36a4a](https://linux-hardware.org/?probe=668eb36a4a) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Gigabyte      | F2A68HM-H                   | [08e1a2a1e1](https://linux-hardware.org/?probe=08e1a2a1e1) | Aug 01, 2023 |
| ASRock        | H110M-HG4                   | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Positivo      | POS-PIH110DV                | [faa5c5cda0](https://linux-hardware.org/?probe=faa5c5cda0) | Jul 31, 2023 |
| Unknown       | Phitronics N68C-M           | [0c596c95da](https://linux-hardware.org/?probe=0c596c95da) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Intel         | DG41WV AAE90316-102         | [fa7d425224](https://linux-hardware.org/?probe=fa7d425224) | Jul 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fe48f2b4d4](https://linux-hardware.org/?probe=fe48f2b4d4) | Jul 30, 2023 |
| MSI           | B85M-E45                    | [dfef6fcff5](https://linux-hardware.org/?probe=dfef6fcff5) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1bcc28bd33](https://linux-hardware.org/?probe=1bcc28bd33) | Jul 29, 2023 |
| Unknown       | GSUO H61V10C                | [9fd25cd0ba](https://linux-hardware.org/?probe=9fd25cd0ba) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [90c03881ae](https://linux-hardware.org/?probe=90c03881ae) | Jul 29, 2023 |
| Positivo      | POS-EINM70CS POSITIVO       | [bee5e6175b](https://linux-hardware.org/?probe=bee5e6175b) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASRock        | H110M-HG4                   | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Digitron      | G31T-M7                     | [7b926165d9](https://linux-hardware.org/?probe=7b926165d9) | Jul 28, 2023 |
| Dell          | 0FR6WH A01                  | [d20434fd50](https://linux-hardware.org/?probe=d20434fd50) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| PCWare        | IPX1800E2                   | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| ASRock        | A320M-HD                    | [26e141980a](https://linux-hardware.org/?probe=26e141980a) | Jul 27, 2023 |
| Intel         | H55                         | [83f249e836](https://linux-hardware.org/?probe=83f249e836) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| ASRock        | H61M-HVS                    | [ac730fa4ed](https://linux-hardware.org/?probe=ac730fa4ed) | Jul 26, 2023 |
| ASRock        | H61M-HVS                    | [57d93857f1](https://linux-hardware.org/?probe=57d93857f1) | Jul 26, 2023 |
| ECS           | G41T-M7                     | [eb7ea6e3f6](https://linux-hardware.org/?probe=eb7ea6e3f6) | Jul 26, 2023 |
| Intel         | B75                         | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [55102fad5b](https://linux-hardware.org/?probe=55102fad5b) | Jul 26, 2023 |
| AZW           | SEi                         | [115142c288](https://linux-hardware.org/?probe=115142c288) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| Gigabyte      | G31M-S2L                    | [5af2ea35ee](https://linux-hardware.org/?probe=5af2ea35ee) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Dell          | 01XK1W A00                  | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | [94a5fdec96](https://linux-hardware.org/?probe=94a5fdec96) | Jul 26, 2023 |
| MSI           | 2A9C                        | [83e6501c96](https://linux-hardware.org/?probe=83e6501c96) | Jul 25, 2023 |
| MAXSUN        | MS-Terminator B660M VER:... | [5cf65783b2](https://linux-hardware.org/?probe=5cf65783b2) | Jul 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| PCWare        | IPMH61R3 8MB                | [dcbde0a01d](https://linux-hardware.org/?probe=dcbde0a01d) | Jul 24, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [2c4dce1245](https://linux-hardware.org/?probe=2c4dce1245) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | [d1ef825b01](https://linux-hardware.org/?probe=d1ef825b01) | Jul 24, 2023 |
| Intel         | B75                         | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | H81M-H                      | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M LX3                | [8982fa467c](https://linux-hardware.org/?probe=8982fa467c) | Jul 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [42d8ff9a34](https://linux-hardware.org/?probe=42d8ff9a34) | Jul 23, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| ECS           | A780LM-M2                   | [b8b1304632](https://linux-hardware.org/?probe=b8b1304632) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Biostar       | B350GT3                     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| Intel         | H61                         | [5a977f0aa9](https://linux-hardware.org/?probe=5a977f0aa9) | Jul 21, 2023 |
| Gigabyte      | B450 AORUS M                | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Kllisre       | X99-B5 V1.1                 | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [55f5c5bd48](https://linux-hardware.org/?probe=55f5c5bd48) | Jul 21, 2023 |
| Intel         | X99H                        | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| Biostar       | A320MH                      | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [e4cc108748](https://linux-hardware.org/?probe=e4cc108748) | Jul 20, 2023 |
| ASRock        | X99M Extreme4               | [caf88d9f9d](https://linux-hardware.org/?probe=caf88d9f9d) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [08fccc55c8](https://linux-hardware.org/?probe=08fccc55c8) | Jul 20, 2023 |
| Dell          | 02YRK5 A03                  | [a1f7c7f053](https://linux-hardware.org/?probe=a1f7c7f053) | Jul 19, 2023 |
| Intel         | H61                         | [10428f5c68](https://linux-hardware.org/?probe=10428f5c68) | Jul 19, 2023 |
| ASUSTek       | B85M-E/BR                   | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | P8H61-M LE/BR               | [0d9c612141](https://linux-hardware.org/?probe=0d9c612141) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| PCWare        | APM-A520G                   | [aefd780df7](https://linux-hardware.org/?probe=aefd780df7) | Jul 17, 2023 |
| Biostar       | B450MH                      | [22909715b3](https://linux-hardware.org/?probe=22909715b3) | Jul 16, 2023 |
| MSI           | A68HM-E33 V2                | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Gigabyte      | G41MT-S2P                   | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [f81eae6d45](https://linux-hardware.org/?probe=f81eae6d45) | Jul 16, 2023 |
| ASRock        | B450M Steel Legend          | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| MSI           | A320M-A PRO MAX             | [34871aac58](https://linux-hardware.org/?probe=34871aac58) | Jul 15, 2023 |
| ASRock        | G41M-VS3                    | [f472934f38](https://linux-hardware.org/?probe=f472934f38) | Jul 15, 2023 |
| ASUSTek       | A88XM-A                     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | H81M-A/BR                   | [40a2bef1f0](https://linux-hardware.org/?probe=40a2bef1f0) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| Dell          | 0T656F A02                  | [9455dc5a07](https://linux-hardware.org/?probe=9455dc5a07) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| MSI           | H510M-A PRO                 | [718dc0f09e](https://linux-hardware.org/?probe=718dc0f09e) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| ASUSTek       | STRIX Z270G GAMING          | [1857fae531](https://linux-hardware.org/?probe=1857fae531) | Jul 13, 2023 |
| Positivo      | POS-EAA75DE                 | [3307527ada](https://linux-hardware.org/?probe=3307527ada) | Jul 13, 2023 |
| Dell          | 04YP6J A03                  | [55d6cad717](https://linux-hardware.org/?probe=55d6cad717) | Jul 13, 2023 |
| Unknown       | EA A520M-E                  | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [38facb34d4](https://linux-hardware.org/?probe=38facb34d4) | Jul 12, 2023 |
| ASUSTek       | M4A78                       | [d9adfecb80](https://linux-hardware.org/?probe=d9adfecb80) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [bad8c925e6](https://linux-hardware.org/?probe=bad8c925e6) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [f754f1e59b](https://linux-hardware.org/?probe=f754f1e59b) | Jul 11, 2023 |
| OEM           | B75 Ver:1.41                | [68c3f1b61c](https://linux-hardware.org/?probe=68c3f1b61c) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| HP            | 3047h                       | [1a4c2d4702](https://linux-hardware.org/?probe=1a4c2d4702) | Jul 11, 2023 |
| Gigabyte      | F2A68HM-H                   | [e22f8030d3](https://linux-hardware.org/?probe=e22f8030d3) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [8c2add9768](https://linux-hardware.org/?probe=8c2add9768) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [2cc9f44232](https://linux-hardware.org/?probe=2cc9f44232) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| ASRock        | A320M-HD                    | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [7c3e56e08a](https://linux-hardware.org/?probe=7c3e56e08a) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9a2170442d](https://linux-hardware.org/?probe=9a2170442d) | Jul 09, 2023 |
| ASRock        | B460M-HDV                   | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M LX                 | [b4b1f263a8](https://linux-hardware.org/?probe=b4b1f263a8) | Jul 08, 2023 |
| Unknown       | X99-GT                      | [34c4fadab5](https://linux-hardware.org/?probe=34c4fadab5) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | [a2487119a6](https://linux-hardware.org/?probe=a2487119a6) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| Unknown       | X99-GT                      | [de745928b7](https://linux-hardware.org/?probe=de745928b7) | Jul 08, 2023 |
| Dell          | 0CU409                      | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| Positivo      | POS-PIG43BC SIM             | [42727a7888](https://linux-hardware.org/?probe=42727a7888) | Jul 08, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [e07a2eb978](https://linux-hardware.org/?probe=e07a2eb978) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| Compaq        | Presario CQ-14              | [9ce9813d5a](https://linux-hardware.org/?probe=9ce9813d5a) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | [f9a1d993b2](https://linux-hardware.org/?probe=f9a1d993b2) | Jul 07, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [c9ccceb765](https://linux-hardware.org/?probe=c9ccceb765) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [901c7b45c2](https://linux-hardware.org/?probe=901c7b45c2) | Jul 07, 2023 |
| MSI           | MEG Z390 GODLIKE            | [5ee0aa7d94](https://linux-hardware.org/?probe=5ee0aa7d94) | Jul 07, 2023 |
| Gigabyte      | A520M K V2                  | [7d81f81cce](https://linux-hardware.org/?probe=7d81f81cce) | Jul 06, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | [7eb9d089cf](https://linux-hardware.org/?probe=7eb9d089cf) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | [2d20ffc659](https://linux-hardware.org/?probe=2d20ffc659) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [25ea01643a](https://linux-hardware.org/?probe=25ea01643a) | Jul 06, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [f156a2bbfa](https://linux-hardware.org/?probe=f156a2bbfa) | Jul 06, 2023 |
| Gigabyte      | G1.Sniper H6                | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [919f65a256](https://linux-hardware.org/?probe=919f65a256) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [3ec7b573fc](https://linux-hardware.org/?probe=3ec7b573fc) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [eef5ee5c9a](https://linux-hardware.org/?probe=eef5ee5c9a) | Jul 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [951a1de3df](https://linux-hardware.org/?probe=951a1de3df) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6b1beb7eeb](https://linux-hardware.org/?probe=6b1beb7eeb) | Jul 05, 2023 |
| Aierben       | NA17                        | [462b502bab](https://linux-hardware.org/?probe=462b502bab) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Megaware      | MW-H61H2-M2                 | [b86248bd97](https://linux-hardware.org/?probe=b86248bd97) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| Intel         | H61                         | [e841a13522](https://linux-hardware.org/?probe=e841a13522) | Jul 03, 2023 |
| ECS           | H55H-M2                     | [344ce5bb17](https://linux-hardware.org/?probe=344ce5bb17) | Jul 03, 2023 |
| Intel         | H55                         | [1ed1ee7e20](https://linux-hardware.org/?probe=1ed1ee7e20) | Jul 03, 2023 |
| ASUSTek       | A88XM-A                     | [cfaaea2608](https://linux-hardware.org/?probe=cfaaea2608) | Jul 03, 2023 |
| Intel         | H61                         | [f18dd431c3](https://linux-hardware.org/?probe=f18dd431c3) | Jul 03, 2023 |
| Intel         | H55                         | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| Intel         | H61                         | [5b18122404](https://linux-hardware.org/?probe=5b18122404) | Jul 01, 2023 |
| Intel         | H61                         | [4664a58c9b](https://linux-hardware.org/?probe=4664a58c9b) | Jul 01, 2023 |
| Dell          | 05XGC8 A00                  | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| Daten Tecn... | DH110MXV                    | [83dd07d2a7](https://linux-hardware.org/?probe=83dd07d2a7) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| ZR            | A320M-F 1005                | [c32d8de777](https://linux-hardware.org/?probe=c32d8de777) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| Intel         | X99 V1.x                    | [8e4ce021b1](https://linux-hardware.org/?probe=8e4ce021b1) | Jun 30, 2023 |
| Gigabyte      | H81M-S2PH                   | [69b69e2a09](https://linux-hardware.org/?probe=69b69e2a09) | Jun 30, 2023 |
| MSI           | Z390-A PRO                  | [7c3ce62039](https://linux-hardware.org/?probe=7c3ce62039) | Jun 30, 2023 |
| AZW           | SEi                         | [37527da518](https://linux-hardware.org/?probe=37527da518) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| Intel         | B75                         | [73d881c953](https://linux-hardware.org/?probe=73d881c953) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Intel         | X99 V1.x                    | [1c7ef9ef35](https://linux-hardware.org/?probe=1c7ef9ef35) | Jun 29, 2023 |
| PCWare        | IPMH61R3                    | [e190259144](https://linux-hardware.org/?probe=e190259144) | Jun 29, 2023 |
| Gigabyte      | H81M-S2PH                   | [d0ec676a22](https://linux-hardware.org/?probe=d0ec676a22) | Jun 29, 2023 |
| Dell          | 0GDG8Y A00                  | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| HP            | 0B54h D                     | [c13f21ea22](https://linux-hardware.org/?probe=c13f21ea22) | Jun 29, 2023 |
| Dell          | 0T656F A02                  | [bf4264c797](https://linux-hardware.org/?probe=bf4264c797) | Jun 29, 2023 |
| MSI           | MS-7438 100                 | [4d0d23065e](https://linux-hardware.org/?probe=4d0d23065e) | Jun 29, 2023 |
| Intel         | DG41RQ AAE54511-205         | [0e896bc137](https://linux-hardware.org/?probe=0e896bc137) | Jun 29, 2023 |
| ZR            | A320M-F 1005                | [f70bb41b80](https://linux-hardware.org/?probe=f70bb41b80) | Jun 28, 2023 |
| Huanan        | Unknown                     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| Lenovo        | NO DPK                      | [2f12ef933e](https://linux-hardware.org/?probe=2f12ef933e) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASRock        | H310CM-HG4                  | [8147961b6c](https://linux-hardware.org/?probe=8147961b6c) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASUSTek       | M5A97 PLUS                  | [2faeb24e37](https://linux-hardware.org/?probe=2faeb24e37) | Jun 27, 2023 |
| Kennex        | POS-PIG41BA                 | [90addad9e1](https://linux-hardware.org/?probe=90addad9e1) | Jun 27, 2023 |
| ASRock        | H310CM-HG4                  | [16c2222f50](https://linux-hardware.org/?probe=16c2222f50) | Jun 27, 2023 |
| Gigabyte      | H310M M.2 x.x               | [6f9c836bb4](https://linux-hardware.org/?probe=6f9c836bb4) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| Intel         | DH55TC AAE70932-206         | [9ff872e2a3](https://linux-hardware.org/?probe=9ff872e2a3) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Lenovo        | 3102 NOK                    | [6277771b08](https://linux-hardware.org/?probe=6277771b08) | Jun 26, 2023 |
| ASRock        | H110M-HG4                   | [6aba51f328](https://linux-hardware.org/?probe=6aba51f328) | Jun 26, 2023 |
| Intel         | H61                         | [8013deae02](https://linux-hardware.org/?probe=8013deae02) | Jun 25, 2023 |
| Intel         | H61                         | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| Intel         | B75                         | [2456289bbd](https://linux-hardware.org/?probe=2456289bbd) | Jun 25, 2023 |
| Biostar       | G31M+                       | [d8347c5f07](https://linux-hardware.org/?probe=d8347c5f07) | Jun 25, 2023 |
| Intel         | X99H                        | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| HP            | 3397                        | [8d9ed6d13e](https://linux-hardware.org/?probe=8d9ed6d13e) | Jun 25, 2023 |
| Intel         | H55                         | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Intel         | H61                         | [df8b50eae5](https://linux-hardware.org/?probe=df8b50eae5) | Jun 25, 2023 |
| Biostar       | TH55B HD                    | [5fbef8b11a](https://linux-hardware.org/?probe=5fbef8b11a) | Jun 25, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Intel         | H61                         | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | [c8fc13e942](https://linux-hardware.org/?probe=c8fc13e942) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| MSI           | A320M-A PRO                 | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| PERTOSA       | GA-H110TN-M                 | [43b4160c55](https://linux-hardware.org/?probe=43b4160c55) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| HP            | 1495                        | [eab7d15f02](https://linux-hardware.org/?probe=eab7d15f02) | Jun 23, 2023 |
| Huanan        | X79 V6.11                   | [e94687bb6b](https://linux-hardware.org/?probe=e94687bb6b) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| ASRock        | A320M-HD                    | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS M                | [7d52f04870](https://linux-hardware.org/?probe=7d52f04870) | Jun 22, 2023 |
| ASRock        | B365 Pro4                   | [46dc8e10a8](https://linux-hardware.org/?probe=46dc8e10a8) | Jun 21, 2023 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [446992e1b5](https://linux-hardware.org/?probe=446992e1b5) | Jun 21, 2023 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [68ec70d3f8](https://linux-hardware.org/?probe=68ec70d3f8) | Jun 21, 2023 |
| Intel         | H55                         | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 339A                        | [60b0bff872](https://linux-hardware.org/?probe=60b0bff872) | Jun 21, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [6f0b6969bf](https://linux-hardware.org/?probe=6f0b6969bf) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [ae2beb307a](https://linux-hardware.org/?probe=ae2beb307a) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [c2c2365360](https://linux-hardware.org/?probe=c2c2365360) | Jun 20, 2023 |
| Positivo      | POS-ECIG41BSA               | [abaf6ee67e](https://linux-hardware.org/?probe=abaf6ee67e) | Jun 20, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Lenovo        | NO DPK                      | [fedcf5f651](https://linux-hardware.org/?probe=fedcf5f651) | Jun 19, 2023 |
| PCWare        | IPMH61R3                    | [256988a55a](https://linux-hardware.org/?probe=256988a55a) | Jun 18, 2023 |
| Standard      | Unknown                     | [4956d7fc21](https://linux-hardware.org/?probe=4956d7fc21) | Jun 18, 2023 |
| Biostar       | A320MH                      | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| ZR            | A320M-F 1005                | [e3c749da2a](https://linux-hardware.org/?probe=e3c749da2a) | Jun 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4bafdb9349](https://linux-hardware.org/?probe=4bafdb9349) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| PCWare        | IPX1800E1                   | [59b9fa6ff9](https://linux-hardware.org/?probe=59b9fa6ff9) | Jun 17, 2023 |
| ZR            | A320M-F 1005                | [c190f4fcff](https://linux-hardware.org/?probe=c190f4fcff) | Jun 17, 2023 |
| Intel         | H55                         | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [c99587d0e0](https://linux-hardware.org/?probe=c99587d0e0) | Jun 16, 2023 |
| ASUSTek       | H61M-A/BR                   | [a587493314](https://linux-hardware.org/?probe=a587493314) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [8124f64b22](https://linux-hardware.org/?probe=8124f64b22) | Jun 16, 2023 |
| Intel         | H61                         | [ac7abe7025](https://linux-hardware.org/?probe=ac7abe7025) | Jun 16, 2023 |
| Intel         | H55                         | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2a3068b835](https://linux-hardware.org/?probe=2a3068b835) | Jun 16, 2023 |
| Intel         | B85                         | [1e688ea5e1](https://linux-hardware.org/?probe=1e688ea5e1) | Jun 16, 2023 |
| Positivo      | POS-EINM70CS POS            | [a2d50f27d7](https://linux-hardware.org/?probe=a2d50f27d7) | Jun 16, 2023 |
| Pegatron      | IPMIP-GS                    | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [4cad282848](https://linux-hardware.org/?probe=4cad282848) | Jun 15, 2023 |
| Positivo      | POS-PIB150DT                | [cddf7d4ac9](https://linux-hardware.org/?probe=cddf7d4ac9) | Jun 15, 2023 |
| Unknown       | G41T-M7                     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [64da6bc381](https://linux-hardware.org/?probe=64da6bc381) | Jun 14, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5e22a31b3e](https://linux-hardware.org/?probe=5e22a31b3e) | Jun 14, 2023 |
| Intel         | H61                         | [5d4fb99018](https://linux-hardware.org/?probe=5d4fb99018) | Jun 14, 2023 |
| Biostar       | B350GT3                     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| HP            | 2AED                        | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [74b5d0e60a](https://linux-hardware.org/?probe=74b5d0e60a) | Jun 13, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [2b0095133a](https://linux-hardware.org/?probe=2b0095133a) | Jun 12, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [613d703a17](https://linux-hardware.org/?probe=613d703a17) | Jun 10, 2023 |
| Intel         | H81                         | [6a51c76e81](https://linux-hardware.org/?probe=6a51c76e81) | Jun 09, 2023 |
| Gigabyte      | 970A-DS3P                   | [1bae25f67b](https://linux-hardware.org/?probe=1bae25f67b) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [28d0a897d3](https://linux-hardware.org/?probe=28d0a897d3) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [c0fd33b9cc](https://linux-hardware.org/?probe=c0fd33b9cc) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [76c3e6625b](https://linux-hardware.org/?probe=76c3e6625b) | Jun 09, 2023 |
| Unknown       | GSUO H61V10C                | [0daf816953](https://linux-hardware.org/?probe=0daf816953) | Jun 09, 2023 |
| ASRock        | A320M-HD                    | [9e88454384](https://linux-hardware.org/?probe=9e88454384) | Jun 09, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| Gigabyte      | H610M H DDR4                | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| ASRock        | B450M Steel Legend          | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASRock        | H310M-HG4                   | [47b2817d31](https://linux-hardware.org/?probe=47b2817d31) | Jun 06, 2023 |
| Dell          | 0NW6H5 A00                  | [631e6bba84](https://linux-hardware.org/?probe=631e6bba84) | Jun 06, 2023 |
| Intel         | DP55WB AAE64798-204         | [fe09edbecc](https://linux-hardware.org/?probe=fe09edbecc) | Jun 06, 2023 |
| Unknown       | Unknown                     | [e8df83921f](https://linux-hardware.org/?probe=e8df83921f) | Jun 06, 2023 |
| ASUSTek       | M5A88-M                     | [bb29b433c0](https://linux-hardware.org/?probe=bb29b433c0) | Jun 05, 2023 |
| Intel         | DP965LT AAD41694-301        | [f72bcbf0a2](https://linux-hardware.org/?probe=f72bcbf0a2) | Jun 05, 2023 |
| Biostar       | B350GT3                     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [8cbfe4cdf0](https://linux-hardware.org/?probe=8cbfe4cdf0) | Jun 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [3a0576b177](https://linux-hardware.org/?probe=3a0576b177) | Jun 05, 2023 |
| ASUSTek       | M5A88-M                     | [e750392f99](https://linux-hardware.org/?probe=e750392f99) | Jun 04, 2023 |
| Dell          | 09D7F7 A00                  | [9b80703b01](https://linux-hardware.org/?probe=9b80703b01) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f71eae78c5](https://linux-hardware.org/?probe=f71eae78c5) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| Positivo      | POS-EINM70CS POS            | [80260b495c](https://linux-hardware.org/?probe=80260b495c) | Jun 03, 2023 |
| Positivo      | POS-PIG41BA                 | [f630c0b9cd](https://linux-hardware.org/?probe=f630c0b9cd) | Jun 03, 2023 |
| Intel         | B75                         | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Dell          | 0GX832 A01                  | [19b718a96c](https://linux-hardware.org/?probe=19b718a96c) | Jun 02, 2023 |
| Unknown       | X99                         | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [da5b2056e4](https://linux-hardware.org/?probe=da5b2056e4) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| ASUSTek       | PRIME X570-P                | [cde4aaef3e](https://linux-hardware.org/?probe=cde4aaef3e) | Jun 01, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [7ac5ec7c05](https://linux-hardware.org/?probe=7ac5ec7c05) | Jun 01, 2023 |
| AZW           | GTR V02                     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| MSI           | B450M MORTAR MAX            | [1d0c56937c](https://linux-hardware.org/?probe=1d0c56937c) | May 31, 2023 |
| ASRock        | H310CM-HG4                  | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Dell          | 0GXM1W A02                  | [9c252c8688](https://linux-hardware.org/?probe=9c252c8688) | May 30, 2023 |
| Itautec       | ST 4265                     | [8814373cb4](https://linux-hardware.org/?probe=8814373cb4) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| Itautec       | ST 4265                     | [b89c45a31d](https://linux-hardware.org/?probe=b89c45a31d) | May 29, 2023 |
| Dell          | 0NM64V A01                  | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASRock        | B450M Steel Legend          | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| ASRock        | H510M-HVS R2.0              | [c4ee84b38e](https://linux-hardware.org/?probe=c4ee84b38e) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Intel         | X99                         | [6826d78921](https://linux-hardware.org/?probe=6826d78921) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| Intel         | X58M                        | [912addab98](https://linux-hardware.org/?probe=912addab98) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [8310aaaa78](https://linux-hardware.org/?probe=8310aaaa78) | May 27, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [86545c89c0](https://linux-hardware.org/?probe=86545c89c0) | May 27, 2023 |
| Intel         | B75                         | [8dba7fa195](https://linux-hardware.org/?probe=8dba7fa195) | May 27, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1cbedc352f](https://linux-hardware.org/?probe=1cbedc352f) | May 26, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [4fedff68f1](https://linux-hardware.org/?probe=4fedff68f1) | May 26, 2023 |
| Gigabyte      | B450 AORUS M                | [40af2d79f9](https://linux-hardware.org/?probe=40af2d79f9) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| ASUSTek       | H110M-C/BR                  | [1c272c65dc](https://linux-hardware.org/?probe=1c272c65dc) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Toshiba       | STI 005492G                 | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [a49bd1dd26](https://linux-hardware.org/?probe=a49bd1dd26) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| PCWare        | IPMH110G                    | [33b6fce5ff](https://linux-hardware.org/?probe=33b6fce5ff) | May 25, 2023 |
| Biostar       | A68MHE                      | [d1ef52da36](https://linux-hardware.org/?probe=d1ef52da36) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Biostar       | A68MHE                      | [e2244a8ed0](https://linux-hardware.org/?probe=e2244a8ed0) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2c31d88fa2](https://linux-hardware.org/?probe=2c31d88fa2) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [efb5aa9bfc](https://linux-hardware.org/?probe=efb5aa9bfc) | May 24, 2023 |
| ASUSTek       | PRIME H510M-E               | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Biostar       | N61PB-M2S                   | [e4669affdb](https://linux-hardware.org/?probe=e4669affdb) | May 24, 2023 |
| AZW           | SEi                         | [bc0c7a512f](https://linux-hardware.org/?probe=bc0c7a512f) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | [bce76b90ef](https://linux-hardware.org/?probe=bce76b90ef) | May 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [44861be08c](https://linux-hardware.org/?probe=44861be08c) | May 24, 2023 |
| AZW           | SEi                         | [825fbaebcd](https://linux-hardware.org/?probe=825fbaebcd) | May 23, 2023 |
| ASUSTek       | B85M-E/BR                   | [ed20b84824](https://linux-hardware.org/?probe=ed20b84824) | May 23, 2023 |
| Intel         | H61                         | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | [9063693561](https://linux-hardware.org/?probe=9063693561) | May 23, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [61ede8f95d](https://linux-hardware.org/?probe=61ede8f95d) | May 23, 2023 |
| Intel         | DP55WB AAE64798-205         | [91bb4c8e5d](https://linux-hardware.org/?probe=91bb4c8e5d) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| ASRock        | H310CM-HG4                  | [6f698f47d8](https://linux-hardware.org/?probe=6f698f47d8) | May 21, 2023 |
| Unknown       | GSUO H61V10C                | [8e1037e4c1](https://linux-hardware.org/?probe=8e1037e4c1) | May 20, 2023 |
| ASRock        | 970A-G                      | [fd39b2185b](https://linux-hardware.org/?probe=fd39b2185b) | May 20, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| ASRock        | 970A-G                      | [fac3e3c961](https://linux-hardware.org/?probe=fac3e3c961) | May 20, 2023 |
| ASRock        | A320M-HD                    | [1a05e80ee5](https://linux-hardware.org/?probe=1a05e80ee5) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| Daten Tecn... | DA320MXV DC                 | [0b7e1e51b9](https://linux-hardware.org/?probe=0b7e1e51b9) | May 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| Gigabyte      | H510M H                     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| MSI           | H110M PRO-VH PLUS           | [14985fd04f](https://linux-hardware.org/?probe=14985fd04f) | May 18, 2023 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | [72303201a3](https://linux-hardware.org/?probe=72303201a3) | May 18, 2023 |
| PCWare        | IPX1800E2                   | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [be46da6480](https://linux-hardware.org/?probe=be46da6480) | May 18, 2023 |
| ASUSTek       | H81M-A/BR                   | [0982e8a637](https://linux-hardware.org/?probe=0982e8a637) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | [2c423cf3e9](https://linux-hardware.org/?probe=2c423cf3e9) | May 17, 2023 |
| Pegatron      | Yangtze                     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | [dc1bf86813](https://linux-hardware.org/?probe=dc1bf86813) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| Intel         | DG41WV AAE90316-101         | [9bef3b952d](https://linux-hardware.org/?probe=9bef3b952d) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3f5bade9b8](https://linux-hardware.org/?probe=3f5bade9b8) | May 16, 2023 |
| Intel         | H61                         | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [377fe6aa67](https://linux-hardware.org/?probe=377fe6aa67) | May 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | [b25434cdf3](https://linux-hardware.org/?probe=b25434cdf3) | May 15, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [dc06cb0aba](https://linux-hardware.org/?probe=dc06cb0aba) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| Dell          | 024JD7 A00                  | [904e4e2a0d](https://linux-hardware.org/?probe=904e4e2a0d) | May 15, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [58f493d242](https://linux-hardware.org/?probe=58f493d242) | May 15, 2023 |
| Gigabyte      | 970A-DS3P FX                | [7fe35591e7](https://linux-hardware.org/?probe=7fe35591e7) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Gigabyte      | 970A-DS3P FX                | [4e208c9155](https://linux-hardware.org/?probe=4e208c9155) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| Daten Tecn... | DH110MXV                    | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2c03c64f49](https://linux-hardware.org/?probe=2c03c64f49) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [e5dbe4c6f4](https://linux-hardware.org/?probe=e5dbe4c6f4) | May 13, 2023 |
| Intel         | B75                         | [da0a89cf17](https://linux-hardware.org/?probe=da0a89cf17) | May 13, 2023 |
| Dell          | 01XK1W A00                  | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| Toshiba       | STI 007567                  | [579ec5bb2b](https://linux-hardware.org/?probe=579ec5bb2b) | May 13, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [3a0e10e849](https://linux-hardware.org/?probe=3a0e10e849) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | [3293d10187](https://linux-hardware.org/?probe=3293d10187) | May 12, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [7b966568cc](https://linux-hardware.org/?probe=7b966568cc) | May 12, 2023 |
| Biostar       | A320MH                      | [d30baf9379](https://linux-hardware.org/?probe=d30baf9379) | May 12, 2023 |
| MSI           | H61M-P20/W8                 | [b727300be6](https://linux-hardware.org/?probe=b727300be6) | May 11, 2023 |
| Huanan        | B75 V10.1 376               | [3c8b5aefd8](https://linux-hardware.org/?probe=3c8b5aefd8) | May 11, 2023 |
| Gigabyte      | H61M-S1                     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [3cccf183d9](https://linux-hardware.org/?probe=3cccf183d9) | May 11, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1b0cd4f3e1](https://linux-hardware.org/?probe=1b0cd4f3e1) | May 11, 2023 |
| Dell          | 076VHM A02                  | [7f1984ec16](https://linux-hardware.org/?probe=7f1984ec16) | May 10, 2023 |
| Dell          | 0GDG8Y A00                  | [e9e13fa531](https://linux-hardware.org/?probe=e9e13fa531) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [cb4250603d](https://linux-hardware.org/?probe=cb4250603d) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| HP            | 0A60h                       | [972820a864](https://linux-hardware.org/?probe=972820a864) | May 10, 2023 |
| ASRock        | N68-S3 FX                   | [0ed94fe810](https://linux-hardware.org/?probe=0ed94fe810) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [6ddb2fa975](https://linux-hardware.org/?probe=6ddb2fa975) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [16bdfe6490](https://linux-hardware.org/?probe=16bdfe6490) | May 10, 2023 |
| Dell          | 0D883F A06                  | [18afa7a07b](https://linux-hardware.org/?probe=18afa7a07b) | May 10, 2023 |
| Dell          | 0VXN67 A01                  | [0985b52dee](https://linux-hardware.org/?probe=0985b52dee) | May 09, 2023 |
| Dell          | 0VXN67 A01                  | [b7fd2a3e2f](https://linux-hardware.org/?probe=b7fd2a3e2f) | May 09, 2023 |
| ASRock        | H310CM-HG4                  | [756ed502db](https://linux-hardware.org/?probe=756ed502db) | May 09, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [631317f909](https://linux-hardware.org/?probe=631317f909) | May 08, 2023 |
| Gigabyte      | F2A68HM-H                   | [97986b63ad](https://linux-hardware.org/?probe=97986b63ad) | May 08, 2023 |
| Gigabyte      | G41MT-S2                    | [0458d9f44b](https://linux-hardware.org/?probe=0458d9f44b) | May 08, 2023 |
| Unknown       | Unknown                     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| ASUSTek       | M4N68T-M LE                 | [0c3f2af7ad](https://linux-hardware.org/?probe=0c3f2af7ad) | May 07, 2023 |
| Intel         | H61                         | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| Lenovo        | NO DPK                      | [15e77c1f0a](https://linux-hardware.org/?probe=15e77c1f0a) | May 06, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| Gigabyte      | GA-970A-UD3                 | [05c9e752a5](https://linux-hardware.org/?probe=05c9e752a5) | May 06, 2023 |
| HP            | 1998                        | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Biostar       | G41D3C                      | [15680367e1](https://linux-hardware.org/?probe=15680367e1) | May 05, 2023 |
| ASRock        | A320M-HDV R4.0              | [d27392828f](https://linux-hardware.org/?probe=d27392828f) | May 05, 2023 |
| ASRock        | H81M-HG4 R4.0               | [cc6641b5d9](https://linux-hardware.org/?probe=cc6641b5d9) | May 04, 2023 |
| Unknown       | Unknown                     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| MSI           | MEG Z390 GODLIKE            | [89a9759dfb](https://linux-hardware.org/?probe=89a9759dfb) | May 03, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [f4678817a9](https://linux-hardware.org/?probe=f4678817a9) | May 03, 2023 |
| HP            | 83E2                        | [7facfe6465](https://linux-hardware.org/?probe=7facfe6465) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| Unknown       | Phitronics N68C-M           | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [16cac427e3](https://linux-hardware.org/?probe=16cac427e3) | May 02, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [45f6915427](https://linux-hardware.org/?probe=45f6915427) | May 02, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [a41adc3f79](https://linux-hardware.org/?probe=a41adc3f79) | May 02, 2023 |
| Intel         | H61                         | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9ff86ca1f1](https://linux-hardware.org/?probe=9ff86ca1f1) | May 01, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| Daten Tecn... | DH110MXV                    | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Lenovo        | NO DPK                      | [6997ff96eb](https://linux-hardware.org/?probe=6997ff96eb) | May 01, 2023 |
| MSI           | A520M-A PRO                 | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| PCWare        | IPMH410E                    | [9be4314a33](https://linux-hardware.org/?probe=9be4314a33) | May 01, 2023 |
| DIEBOLD       | NM70-I                      | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [68d85dd28f](https://linux-hardware.org/?probe=68d85dd28f) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [5166f820a6](https://linux-hardware.org/?probe=5166f820a6) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9109b0a7ed](https://linux-hardware.org/?probe=9109b0a7ed) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| ASRock        | B450M Steel Legend          | [fed083feba](https://linux-hardware.org/?probe=fed083feba) | Apr 30, 2023 |
| Intel         | H61                         | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Intel         | H81                         | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| ASUSTek       | PRIME H410M-E               | [44a08af32f](https://linux-hardware.org/?probe=44a08af32f) | Apr 29, 2023 |
| ASUSTek       | H81M-C/BR                   | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| Gigabyte      | G41MT-S2                    | [ba5c65f4e3](https://linux-hardware.org/?probe=ba5c65f4e3) | Apr 29, 2023 |
| ASUSTek       | P8H61-M LE/BR               | [425f1a3e08](https://linux-hardware.org/?probe=425f1a3e08) | Apr 29, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [16b28befee](https://linux-hardware.org/?probe=16b28befee) | Apr 28, 2023 |
| ASRock        | A320M-HD                    | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| HP            | 158B                        | [ee0297b0ba](https://linux-hardware.org/?probe=ee0297b0ba) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Lenovo        | NO DPK                      | [d3442220b0](https://linux-hardware.org/?probe=d3442220b0) | Apr 28, 2023 |
| Intel         | H61                         | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [9211d42ee3](https://linux-hardware.org/?probe=9211d42ee3) | Apr 27, 2023 |
| HP            | 3047h                       | [3e6dada8a9](https://linux-hardware.org/?probe=3e6dada8a9) | Apr 26, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| MSI           | MAG B550M MORTAR            | [f91ac46cfd](https://linux-hardware.org/?probe=f91ac46cfd) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| Biostar       | H610MH                      | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [a7e77375d4](https://linux-hardware.org/?probe=a7e77375d4) | Apr 26, 2023 |
| Intel         | H81                         | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| ASRock        | AB350M-HDV                  | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| Gigabyte      | H87-D3H-CF                  | [b3a3115f0c](https://linux-hardware.org/?probe=b3a3115f0c) | Apr 25, 2023 |
| OEM           | HN B85 Ver:1.4              | [1da5934b27](https://linux-hardware.org/?probe=1da5934b27) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [342918aa38](https://linux-hardware.org/?probe=342918aa38) | Apr 24, 2023 |
| AMD           | Inagua CRB                  | [085d0aa051](https://linux-hardware.org/?probe=085d0aa051) | Apr 24, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| Dell          | 0VTJVC A00                  | [da7d66917d](https://linux-hardware.org/?probe=da7d66917d) | Apr 24, 2023 |
| Gigabyte      | G41MT-S2                    | [de1981f9e6](https://linux-hardware.org/?probe=de1981f9e6) | Apr 24, 2023 |
| Huanan        | X99-8M-F V1.1               | [0621d00b73](https://linux-hardware.org/?probe=0621d00b73) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| HP            | 18E7                        | [c5bc4d9c7f](https://linux-hardware.org/?probe=c5bc4d9c7f) | Apr 23, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek       | H81M-C/BR                   | [46a27a7551](https://linux-hardware.org/?probe=46a27a7551) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [793e094165](https://linux-hardware.org/?probe=793e094165) | Apr 23, 2023 |
| Pegatron      | IPMH61P1                    | [b71d5b1a48](https://linux-hardware.org/?probe=b71d5b1a48) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| Gigabyte      | VM900M Rev2.0               | [284ada7211](https://linux-hardware.org/?probe=284ada7211) | Apr 23, 2023 |
| PCWare        | IPX1800G2                   | [f63cf0fe51](https://linux-hardware.org/?probe=f63cf0fe51) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [dfb9f87dad](https://linux-hardware.org/?probe=dfb9f87dad) | Apr 22, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [ea8fb664a3](https://linux-hardware.org/?probe=ea8fb664a3) | Apr 22, 2023 |
| ASRock        | H310CM-HG4                  | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| ASRock        | H510M-HVS R2.0              | [1de5b776a3](https://linux-hardware.org/?probe=1de5b776a3) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Gigabyte      | G31M-S2C                    | [0c45fc6929](https://linux-hardware.org/?probe=0c45fc6929) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Intel         | H61S                        | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [c0a82bb35a](https://linux-hardware.org/?probe=c0a82bb35a) | Apr 19, 2023 |
| Intel         | X79M-S                      | [0c51f5a0e0](https://linux-hardware.org/?probe=0c51f5a0e0) | Apr 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [8bb9dc2419](https://linux-hardware.org/?probe=8bb9dc2419) | Apr 18, 2023 |
| AMD           | Inagua CRB                  | [8d2ce37fca](https://linux-hardware.org/?probe=8d2ce37fca) | Apr 18, 2023 |
| Dell          | 08NPPY A00                  | [7fcc7d1b34](https://linux-hardware.org/?probe=7fcc7d1b34) | Apr 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Intel         | B75                         | [18dce6805d](https://linux-hardware.org/?probe=18dce6805d) | Apr 15, 2023 |
| AMD           | A88F2EKS                    | [48cef621bd](https://linux-hardware.org/?probe=48cef621bd) | Apr 15, 2023 |
| ASUSTek       | M4A785TD-M EVO              | [dd2d3443a9](https://linux-hardware.org/?probe=dd2d3443a9) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| ASRock        | B550M Pro4                  | [ec08193576](https://linux-hardware.org/?probe=ec08193576) | Apr 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [e2f136f068](https://linux-hardware.org/?probe=e2f136f068) | Apr 14, 2023 |
| PCWare        | IPMH61R3                    | [776a2824c5](https://linux-hardware.org/?probe=776a2824c5) | Apr 14, 2023 |
| OEM           | H110                        | [60e8c50cdd](https://linux-hardware.org/?probe=60e8c50cdd) | Apr 14, 2023 |
| ASUSTek       | Maximus IX APEX             | [f4a7db0c2a](https://linux-hardware.org/?probe=f4a7db0c2a) | Apr 14, 2023 |
| HP            | 1589                        | [b5309b9a82](https://linux-hardware.org/?probe=b5309b9a82) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [89a7f8f7e7](https://linux-hardware.org/?probe=89a7f8f7e7) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| OEM           | Intel H81                   | [1a73452d73](https://linux-hardware.org/?probe=1a73452d73) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Win elemen... | M600                        | [4268d36ca4](https://linux-hardware.org/?probe=4268d36ca4) | Apr 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [065d244d4b](https://linux-hardware.org/?probe=065d244d4b) | Apr 12, 2023 |
| Intel         | H61 V124                    | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ABIT          | NF-M2S                      | [30e3a2e8c4](https://linux-hardware.org/?probe=30e3a2e8c4) | Apr 11, 2023 |
| ASUSTek       | P5LD2-X/1333                | [e0e655f63c](https://linux-hardware.org/?probe=e0e655f63c) | Apr 11, 2023 |
| ECS           | H61H2-M12                   | [f3e8f5eb22](https://linux-hardware.org/?probe=f3e8f5eb22) | Apr 10, 2023 |
| Biostar       | A320MH                      | [a2aef00c0c](https://linux-hardware.org/?probe=a2aef00c0c) | Apr 09, 2023 |
| Gigabyte      | F2A68HM-H                   | [249b3e78ed](https://linux-hardware.org/?probe=249b3e78ed) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| Gigabyte      | F2A68HM-H                   | [8d36d0bfeb](https://linux-hardware.org/?probe=8d36d0bfeb) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| ASUSTek       | A68HM-K                     | [55d971a67f](https://linux-hardware.org/?probe=55d971a67f) | Apr 08, 2023 |
| OEM           | X99-Turbo                   | [52723223af](https://linux-hardware.org/?probe=52723223af) | Apr 08, 2023 |
| Biostar       | A520MH                      | [9cf296886b](https://linux-hardware.org/?probe=9cf296886b) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| ASUSTek       | B85M-E/BR                   | [66efb7f634](https://linux-hardware.org/?probe=66efb7f634) | Apr 07, 2023 |
| HP            | 0B54h D                     | [59e9cd0741](https://linux-hardware.org/?probe=59e9cd0741) | Apr 06, 2023 |
| Dell          | 0C2KJT A00                  | [1f006c081e](https://linux-hardware.org/?probe=1f006c081e) | Apr 06, 2023 |
| Intel         | X99H                        | [b91cbf41c0](https://linux-hardware.org/?probe=b91cbf41c0) | Apr 06, 2023 |
| Biostar       | N68S3B                      | [3b25aad650](https://linux-hardware.org/?probe=3b25aad650) | Apr 05, 2023 |
| Gigabyte      | H87M-D3H                    | [b9c169025d](https://linux-hardware.org/?probe=b9c169025d) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5f9965b18e](https://linux-hardware.org/?probe=5f9965b18e) | Apr 05, 2023 |
| MSI           | MS-7529                     | [2c6cdf6397](https://linux-hardware.org/?probe=2c6cdf6397) | Apr 04, 2023 |
| ASUSTek       | PRIME A320M-C R2.0          | [70b2a73996](https://linux-hardware.org/?probe=70b2a73996) | Apr 04, 2023 |
| Intel         | B75                         | [8d116f68cf](https://linux-hardware.org/?probe=8d116f68cf) | Apr 04, 2023 |
| Dell          | 07PR60 A02                  | [c41c1c9ead](https://linux-hardware.org/?probe=c41c1c9ead) | Apr 04, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [26e8d46d94](https://linux-hardware.org/?probe=26e8d46d94) | Apr 03, 2023 |
| Intel         | DZ87KLT75K AAG74721-304     | [4f97ce0a4b](https://linux-hardware.org/?probe=4f97ce0a4b) | Apr 03, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [22cc49b906](https://linux-hardware.org/?probe=22cc49b906) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [65668a06ad](https://linux-hardware.org/?probe=65668a06ad) | Apr 03, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [f0de4366f7](https://linux-hardware.org/?probe=f0de4366f7) | Apr 03, 2023 |
| MSI           | MEG Z390 GODLIKE            | [d447871547](https://linux-hardware.org/?probe=d447871547) | Apr 03, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [e3845b9610](https://linux-hardware.org/?probe=e3845b9610) | Apr 02, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [6bac6aa095](https://linux-hardware.org/?probe=6bac6aa095) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| ULTRATOP      | C2017-LIVA-ZE               | [96d0c389b8](https://linux-hardware.org/?probe=96d0c389b8) | Apr 02, 2023 |
| Intel         | B75                         | [caad7f240a](https://linux-hardware.org/?probe=caad7f240a) | Apr 02, 2023 |
| HOUTER        | IPMIP-GS                    | [4ef0c7aaaa](https://linux-hardware.org/?probe=4ef0c7aaaa) | Apr 02, 2023 |
| ASRock        | FM2A68M-HD+ R2.0            | [b2051ee32b](https://linux-hardware.org/?probe=b2051ee32b) | Apr 02, 2023 |
| Lenovo        | 3102 NOK                    | [3707e05f16](https://linux-hardware.org/?probe=3707e05f16) | Apr 01, 2023 |
| Unknown       | Unknown                     | [089fc02d40](https://linux-hardware.org/?probe=089fc02d40) | Apr 01, 2023 |
| Gigabyte      | H410M DS2V                  | [67b081e859](https://linux-hardware.org/?probe=67b081e859) | Apr 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [3f218796ae](https://linux-hardware.org/?probe=3f218796ae) | Apr 01, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [ee536703f8](https://linux-hardware.org/?probe=ee536703f8) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Intel         | H61 V1.1                    | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | A58M-A/BR                   | [90724dc86e](https://linux-hardware.org/?probe=90724dc86e) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [1fa3e0934f](https://linux-hardware.org/?probe=1fa3e0934f) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [ebd6135034](https://linux-hardware.org/?probe=ebd6135034) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [88864f0e2d](https://linux-hardware.org/?probe=88864f0e2d) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3aac57dfbd](https://linux-hardware.org/?probe=3aac57dfbd) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Dell          | 0KWVT8 A02                  | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| Daten Tecn... | DQ77PRO                     | [86885bfc03](https://linux-hardware.org/?probe=86885bfc03) | Mar 29, 2023 |
| Intel         | B75                         | [2bddb84c2e](https://linux-hardware.org/?probe=2bddb84c2e) | Mar 29, 2023 |
| HOUTER        | IPMH61R1                    | [bcabc2573c](https://linux-hardware.org/?probe=bcabc2573c) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| Intel         | H61 V1.1                    | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [7ec74ffcfa](https://linux-hardware.org/?probe=7ec74ffcfa) | Mar 28, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [7e5cb33850](https://linux-hardware.org/?probe=7e5cb33850) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9c9e155f84](https://linux-hardware.org/?probe=9c9e155f84) | Mar 28, 2023 |
| Intel         | H61                         | [56437a0e05](https://linux-hardware.org/?probe=56437a0e05) | Mar 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [6b4122e888](https://linux-hardware.org/?probe=6b4122e888) | Mar 28, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [727f980b20](https://linux-hardware.org/?probe=727f980b20) | Mar 27, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | [ec1f547743](https://linux-hardware.org/?probe=ec1f547743) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| PCWare        | IPMH61R3                    | [2fbd1f3f64](https://linux-hardware.org/?probe=2fbd1f3f64) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| MSI           | A520M-A PRO                 | [f2a2593a06](https://linux-hardware.org/?probe=f2a2593a06) | Mar 24, 2023 |
| Gigabyte      | H170-D3H-CF                 | [0bcd7ee5e8](https://linux-hardware.org/?probe=0bcd7ee5e8) | Mar 24, 2023 |
| Intel         | X99 V1.x                    | [391a73b307](https://linux-hardware.org/?probe=391a73b307) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [4e2b8b9de9](https://linux-hardware.org/?probe=4e2b8b9de9) | Mar 24, 2023 |
| PCWare        | IPMH310G                    | [3cc2e91e56](https://linux-hardware.org/?probe=3cc2e91e56) | Mar 24, 2023 |
| Itautec       | ST 4265                     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2536217d87](https://linux-hardware.org/?probe=2536217d87) | Mar 23, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [cd3e7fa4e5](https://linux-hardware.org/?probe=cd3e7fa4e5) | Mar 23, 2023 |
| Intel         | DH87RL AAG74240-401         | [3465e562e8](https://linux-hardware.org/?probe=3465e562e8) | Mar 23, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [7d303a08d4](https://linux-hardware.org/?probe=7d303a08d4) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Digiboard     | NM70-TI                     | [d654b9738a](https://linux-hardware.org/?probe=d654b9738a) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [47b661fcb3](https://linux-hardware.org/?probe=47b661fcb3) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | [f848ecf9cf](https://linux-hardware.org/?probe=f848ecf9cf) | Mar 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [568fac441d](https://linux-hardware.org/?probe=568fac441d) | Mar 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2e6307252f](https://linux-hardware.org/?probe=2e6307252f) | Mar 22, 2023 |
| Gigabyte      | GA-970A-UD3                 | [982f47fec3](https://linux-hardware.org/?probe=982f47fec3) | Mar 22, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | [1e299101d8](https://linux-hardware.org/?probe=1e299101d8) | Mar 22, 2023 |
| CCE           | NM70-I                      | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| Dell          | 03NVJ6 A01                  | [2060b57720](https://linux-hardware.org/?probe=2060b57720) | Mar 20, 2023 |
| Dell          | 0KWVT8 A00                  | [b15061e252](https://linux-hardware.org/?probe=b15061e252) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Win elemen... | M600                        | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [32d80303b6](https://linux-hardware.org/?probe=32d80303b6) | Mar 20, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [6e6c326058](https://linux-hardware.org/?probe=6e6c326058) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| MSI           | 970 GAMING                  | [99e92fa4df](https://linux-hardware.org/?probe=99e92fa4df) | Mar 18, 2023 |
| Gigabyte      | Z270M-D3H-CF                | [1a93d601d7](https://linux-hardware.org/?probe=1a93d601d7) | Mar 18, 2023 |
| ASRock        | FM2A68M-DG3+                | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Intel         | H61                         | [10b44e8f3e](https://linux-hardware.org/?probe=10b44e8f3e) | Mar 18, 2023 |
| ASRock        | FM2A68M-DG3+                | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| Positivo      | POS-EIH61CE SIM             | [19a69ab150](https://linux-hardware.org/?probe=19a69ab150) | Mar 17, 2023 |
| HP            | 8266                        | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [452349c032](https://linux-hardware.org/?probe=452349c032) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [2215bc867b](https://linux-hardware.org/?probe=2215bc867b) | Mar 17, 2023 |
| Intel         | X99                         | [e7d23adc36](https://linux-hardware.org/?probe=e7d23adc36) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| HP            | 8266                        | [90ee08c208](https://linux-hardware.org/?probe=90ee08c208) | Mar 16, 2023 |
| Intel         | X99 V1.0                    | [1e1b3b6542](https://linux-hardware.org/?probe=1e1b3b6542) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| HP            | 8299                        | [d76d2b1088](https://linux-hardware.org/?probe=d76d2b1088) | Mar 15, 2023 |
| PCWare        | IPX4105G Pro                | [f685771047](https://linux-hardware.org/?probe=f685771047) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | [1451ae2f05](https://linux-hardware.org/?probe=1451ae2f05) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | [26971576bb](https://linux-hardware.org/?probe=26971576bb) | Mar 14, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [7649d9be35](https://linux-hardware.org/?probe=7649d9be35) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASRock        | A320M-HDV R4.0              | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | PRIME B350M-K               | [ae6352dc35](https://linux-hardware.org/?probe=ae6352dc35) | Mar 13, 2023 |
| Biostar       | A320MH                      | [6fbd813bc2](https://linux-hardware.org/?probe=6fbd813bc2) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [89e2967e3c](https://linux-hardware.org/?probe=89e2967e3c) | Mar 12, 2023 |
| Pegatron      | SM3330B 0500B               | [1ece615e2d](https://linux-hardware.org/?probe=1ece615e2d) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| Dell          | 0HHV7N A00                  | [75e9243247](https://linux-hardware.org/?probe=75e9243247) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3e9c39ec40](https://linux-hardware.org/?probe=3e9c39ec40) | Mar 11, 2023 |
| Intel         | H61                         | [0a38ec61cc](https://linux-hardware.org/?probe=0a38ec61cc) | Mar 11, 2023 |
| Gigabyte      | H81M-H                      | [fd3c999c22](https://linux-hardware.org/?probe=fd3c999c22) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| Intel         | X99H                        | [a89ad204c8](https://linux-hardware.org/?probe=a89ad204c8) | Mar 11, 2023 |
| Positivo      | POS-PIB150DT                | [0842fc186b](https://linux-hardware.org/?probe=0842fc186b) | Mar 10, 2023 |
| Lenovo        | NOK                         | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Dell          | 0G2DM9 A02                  | [e6d8fa1563](https://linux-hardware.org/?probe=e6d8fa1563) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5a1af5afcf](https://linux-hardware.org/?probe=5a1af5afcf) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [8b2c5b902c](https://linux-hardware.org/?probe=8b2c5b902c) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [3a0c1c2237](https://linux-hardware.org/?probe=3a0c1c2237) | Mar 10, 2023 |
| HP            | 1905                        | [dc86818199](https://linux-hardware.org/?probe=dc86818199) | Mar 09, 2023 |
| Dell          | 0TW904                      | [19f37f2901](https://linux-hardware.org/?probe=19f37f2901) | Mar 09, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [a05bd1ffa7](https://linux-hardware.org/?probe=a05bd1ffa7) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Gigabyte      | A320M-S2H-CF                | [daf758d941](https://linux-hardware.org/?probe=daf758d941) | Mar 08, 2023 |
| Intel         | B75 V124                    | [8a643c9a04](https://linux-hardware.org/?probe=8a643c9a04) | Mar 08, 2023 |
| Dell          | 0TW904                      | [20e3b7cc23](https://linux-hardware.org/?probe=20e3b7cc23) | Mar 08, 2023 |
| Intel         | B75 V124                    | [777cb32ba1](https://linux-hardware.org/?probe=777cb32ba1) | Mar 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [d7ac4c2edb](https://linux-hardware.org/?probe=d7ac4c2edb) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | [1ef5bb11d6](https://linux-hardware.org/?probe=1ef5bb11d6) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | [0bad20c48c](https://linux-hardware.org/?probe=0bad20c48c) | Mar 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [4ca3d88758](https://linux-hardware.org/?probe=4ca3d88758) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [955e69578c](https://linux-hardware.org/?probe=955e69578c) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [22273fa42e](https://linux-hardware.org/?probe=22273fa42e) | Mar 06, 2023 |
| Lenovo        | ThinkCentre M91P 4518NR1    | [dfea3b8d9f](https://linux-hardware.org/?probe=dfea3b8d9f) | Mar 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [349f7731c8](https://linux-hardware.org/?probe=349f7731c8) | Mar 06, 2023 |
| Gigabyte      | B450 AORUS M                | [e67eb9d235](https://linux-hardware.org/?probe=e67eb9d235) | Mar 06, 2023 |
| MSI           | 970 GAMING                  | [ca2ad0edee](https://linux-hardware.org/?probe=ca2ad0edee) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [a21f4171f1](https://linux-hardware.org/?probe=a21f4171f1) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7e9b335ee0](https://linux-hardware.org/?probe=7e9b335ee0) | Mar 05, 2023 |
| PCWare        | APM-A320G                   | [2bc24b8935](https://linux-hardware.org/?probe=2bc24b8935) | Mar 04, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [62309a2dac](https://linux-hardware.org/?probe=62309a2dac) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b61241e05e](https://linux-hardware.org/?probe=b61241e05e) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | [871c72708d](https://linux-hardware.org/?probe=871c72708d) | Mar 04, 2023 |
| OEM           | Unknown                     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | [6396907447](https://linux-hardware.org/?probe=6396907447) | Mar 03, 2023 |
| Biostar       | B450MX-S                    | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| Gigabyte      | Z87M-D3H                    | [4f279ee581](https://linux-hardware.org/?probe=4f279ee581) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| ASUSTek       | M2N68-AM SE2                | [f4292f5622](https://linux-hardware.org/?probe=f4292f5622) | Mar 03, 2023 |
| Intel         | D525MW AAE93082-401         | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| DIEBOLD       | H55H-CM                     | [fadb939dd7](https://linux-hardware.org/?probe=fadb939dd7) | Mar 02, 2023 |
| ASRock        | 970A-G                      | [4a8ff8612a](https://linux-hardware.org/?probe=4a8ff8612a) | Mar 02, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | [ab9ad1a310](https://linux-hardware.org/?probe=ab9ad1a310) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| Pegatron      | SM3330B 0500B               | [7ec6d4d881](https://linux-hardware.org/?probe=7ec6d4d881) | Mar 01, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [44e24e77eb](https://linux-hardware.org/?probe=44e24e77eb) | Mar 01, 2023 |
| ASUSTek       | P8H61-M LX                  | [5721cbc403](https://linux-hardware.org/?probe=5721cbc403) | Feb 28, 2023 |
| ASRock        | H81M-HG4 R4.0               | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| Gigabyte      | H61M-S1                     | [ee8e20d95e](https://linux-hardware.org/?probe=ee8e20d95e) | Feb 27, 2023 |
| PCWare        | IPMH61R2                    | [52a17bf9c1](https://linux-hardware.org/?probe=52a17bf9c1) | Feb 27, 2023 |
| Gigabyte      | H110M-S2V-CF                | [509c2a6e57](https://linux-hardware.org/?probe=509c2a6e57) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Gigabyte      | B560M DS3H V2               | [31f6d9e11d](https://linux-hardware.org/?probe=31f6d9e11d) | Feb 26, 2023 |
| FIC           | PTM33 PCB                   | [b70b076cda](https://linux-hardware.org/?probe=b70b076cda) | Feb 26, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| ASRock        | H110M-HG4                   | [0a5dfbb9e6](https://linux-hardware.org/?probe=0a5dfbb9e6) | Feb 26, 2023 |
| Gigabyte      | M68MT-S2P                   | [d205de771a](https://linux-hardware.org/?probe=d205de771a) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [336a7cad31](https://linux-hardware.org/?probe=336a7cad31) | Feb 25, 2023 |
| MSI           | 970 GAMING                  | [37bcb5eb45](https://linux-hardware.org/?probe=37bcb5eb45) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [30afdb56c5](https://linux-hardware.org/?probe=30afdb56c5) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [bfa5623f15](https://linux-hardware.org/?probe=bfa5623f15) | Feb 25, 2023 |
| HP            | 2AA2                        | [b9411eadb7](https://linux-hardware.org/?probe=b9411eadb7) | Feb 25, 2023 |
| ASUSTek       | A88XM-A                     | [dff66700c0](https://linux-hardware.org/?probe=dff66700c0) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | [3f931a7600](https://linux-hardware.org/?probe=3f931a7600) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| ASRock        | N68-GS4 FX R2.0             | [6d03ea4905](https://linux-hardware.org/?probe=6d03ea4905) | Feb 24, 2023 |
| PCWare        | IPMH61R2                    | [eda674b9a5](https://linux-hardware.org/?probe=eda674b9a5) | Feb 24, 2023 |
| ASUSTek       | A68HM-K                     | [5c7e454884](https://linux-hardware.org/?probe=5c7e454884) | Feb 24, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [2a8b727725](https://linux-hardware.org/?probe=2a8b727725) | Feb 24, 2023 |
| MSI           | MEG Z390 GODLIKE            | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| ASUSTek       | B85M-E/BR                   | [e60b570c27](https://linux-hardware.org/?probe=e60b570c27) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| Intel         | H61                         | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| Positivo      | POS-PQ45AU POSITIVO         | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [fd084cb513](https://linux-hardware.org/?probe=fd084cb513) | Feb 23, 2023 |
| Intel         | H61                         | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| PCWare        | IPMH61R2                    | [f02c3d5895](https://linux-hardware.org/?probe=f02c3d5895) | Feb 22, 2023 |
| MSI           | MEG Z390 GODLIKE            | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| MSI           | B350 TOMAHAWK               | [71aa647a28](https://linux-hardware.org/?probe=71aa647a28) | Feb 22, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [aa39c9a471](https://linux-hardware.org/?probe=aa39c9a471) | Feb 22, 2023 |
| ASUSTek       | AM1M-A/BR                   | [d1c356a1c7](https://linux-hardware.org/?probe=d1c356a1c7) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ae2e7a22a0](https://linux-hardware.org/?probe=ae2e7a22a0) | Feb 21, 2023 |
| ASRock        | AM1B-MH                     | [d67d348d90](https://linux-hardware.org/?probe=d67d348d90) | Feb 20, 2023 |
| Win elemen... | M600                        | [76c26f5ebb](https://linux-hardware.org/?probe=76c26f5ebb) | Feb 20, 2023 |
| AMD           | A78FX VER                   | [36eb566c26](https://linux-hardware.org/?probe=36eb566c26) | Feb 20, 2023 |
| Intel         | H55                         | [6102979c67](https://linux-hardware.org/?probe=6102979c67) | Feb 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [8c8ae38704](https://linux-hardware.org/?probe=8c8ae38704) | Feb 19, 2023 |
| Dell          | 04YP6J A03                  | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | F2A68HM-H                   | [6be03ad579](https://linux-hardware.org/?probe=6be03ad579) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Login Info... | LOG-H61H2-M2                | [889231ad64](https://linux-hardware.org/?probe=889231ad64) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [f3c66a583b](https://linux-hardware.org/?probe=f3c66a583b) | Feb 17, 2023 |
| MSI           | B350 TOMAHAWK               | [de9c98193e](https://linux-hardware.org/?probe=de9c98193e) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9d88e03390](https://linux-hardware.org/?probe=9d88e03390) | Feb 17, 2023 |
| Lenovo        | 3164 NOK                    | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| ASUSTek       | M4N68T-M LE                 | [7b5fe965fd](https://linux-hardware.org/?probe=7b5fe965fd) | Feb 16, 2023 |
| DIEBOLD       | H55H-CM                     | [fdfc5c5e92](https://linux-hardware.org/?probe=fdfc5c5e92) | Feb 16, 2023 |
| ASUSTek       | H61M-K                      | [b66ca441a7](https://linux-hardware.org/?probe=b66ca441a7) | Feb 16, 2023 |
| Pegatron      | SM3330B 0500B               | [701fdae932](https://linux-hardware.org/?probe=701fdae932) | Feb 16, 2023 |
| ASUSTek       | H81M-A/BR                   | [37674ee96e](https://linux-hardware.org/?probe=37674ee96e) | Feb 16, 2023 |
| Itautec       | ST 4265                     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| HP            | 8434 11                     | [2f4023e5f3](https://linux-hardware.org/?probe=2f4023e5f3) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| ASRock        | A320M-HD                    | [35fcd679e5](https://linux-hardware.org/?probe=35fcd679e5) | Feb 15, 2023 |
| ASRock        | N68-S3 FX                   | [a401dfe086](https://linux-hardware.org/?probe=a401dfe086) | Feb 14, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | [3569214674](https://linux-hardware.org/?probe=3569214674) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | [5fefbd2419](https://linux-hardware.org/?probe=5fefbd2419) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [0b0a816ecc](https://linux-hardware.org/?probe=0b0a816ecc) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [4785d6d596](https://linux-hardware.org/?probe=4785d6d596) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | [60794bd7c3](https://linux-hardware.org/?probe=60794bd7c3) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| DIEBOLD       | NM70-I                      | [ed4d687c32](https://linux-hardware.org/?probe=ed4d687c32) | Feb 14, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [39564bbf72](https://linux-hardware.org/?probe=39564bbf72) | Feb 13, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | [56411004d4](https://linux-hardware.org/?probe=56411004d4) | Feb 13, 2023 |
| ASUSTek       | M5A88-M                     | [e4b1d6656b](https://linux-hardware.org/?probe=e4b1d6656b) | Feb 13, 2023 |
| Intel         | H61                         | [f220565e36](https://linux-hardware.org/?probe=f220565e36) | Feb 12, 2023 |
| Unknown       | Unknown                     | [df52d514c9](https://linux-hardware.org/?probe=df52d514c9) | Feb 12, 2023 |
| Intel         | H61                         | [800d3a961c](https://linux-hardware.org/?probe=800d3a961c) | Feb 12, 2023 |
| Intel         | H61                         | [7a6e4d8211](https://linux-hardware.org/?probe=7a6e4d8211) | Feb 12, 2023 |
| ASUSTek       | M5A88-M                     | [f1b285512e](https://linux-hardware.org/?probe=f1b285512e) | Feb 12, 2023 |
| Pegatron      | SM3330B 0500B               | [d2fec952ae](https://linux-hardware.org/?probe=d2fec952ae) | Feb 12, 2023 |
| Colorful T... | CVN B450M GAMING V14        | [fdedcd0d4a](https://linux-hardware.org/?probe=fdedcd0d4a) | Feb 11, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [1623076357](https://linux-hardware.org/?probe=1623076357) | Feb 11, 2023 |
| Compaq        | Presario CQ-14              | [515b629bbc](https://linux-hardware.org/?probe=515b629bbc) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [d85a564e73](https://linux-hardware.org/?probe=d85a564e73) | Feb 11, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [abfd3f65af](https://linux-hardware.org/?probe=abfd3f65af) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| Gigabyte      | GA-A75-UD4H                 | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Lenovo        | Unknown                     | [253bcab6fa](https://linux-hardware.org/?probe=253bcab6fa) | Feb 09, 2023 |
| ASRock        | B450M Pro4-F                | [35bd9cf04c](https://linux-hardware.org/?probe=35bd9cf04c) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3b71a70207](https://linux-hardware.org/?probe=3b71a70207) | Feb 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fe84bf2bc9](https://linux-hardware.org/?probe=fe84bf2bc9) | Feb 09, 2023 |
| Lenovo        | 3164 NOK                    | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Dell          | 0TW904                      | [01c887764a](https://linux-hardware.org/?probe=01c887764a) | Feb 08, 2023 |
| Intel         | H61                         | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Dell          | 0TW904                      | [f88778be48](https://linux-hardware.org/?probe=f88778be48) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| Lenovo        | 3102 NOK                    | [2a34c65a5d](https://linux-hardware.org/?probe=2a34c65a5d) | Feb 06, 2023 |
| Lenovo        | 3102 NOK                    | [0b35653efd](https://linux-hardware.org/?probe=0b35653efd) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cfdb3767fb](https://linux-hardware.org/?probe=cfdb3767fb) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [f0aa46956b](https://linux-hardware.org/?probe=f0aa46956b) | Feb 06, 2023 |
| Gigabyte      | B450 AORUS M                | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L LE                   | [0e0bd23571](https://linux-hardware.org/?probe=0e0bd23571) | Feb 05, 2023 |
| ASUSTek       | M5A78L LE                   | [5c63c52fd4](https://linux-hardware.org/?probe=5c63c52fd4) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| LG Electro... | R590-U.BE57P1               | [7de316c06f](https://linux-hardware.org/?probe=7de316c06f) | Feb 05, 2023 |
| ASRock        | H61M-HP4                    | [826a81ae2e](https://linux-hardware.org/?probe=826a81ae2e) | Feb 05, 2023 |
| OEM           | Intel H81                   | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [7cd8292c5f](https://linux-hardware.org/?probe=7cd8292c5f) | Feb 04, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | [01a8e618f5](https://linux-hardware.org/?probe=01a8e618f5) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [2cb7086ff1](https://linux-hardware.org/?probe=2cb7086ff1) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| HP            | 3048h                       | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | [5c7d71b636](https://linux-hardware.org/?probe=5c7d71b636) | Feb 03, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| Dell          | 0TW904                      | [83d5b82840](https://linux-hardware.org/?probe=83d5b82840) | Feb 03, 2023 |
| Gigabyte      | G31M-S2C                    | [3e5a2f20cc](https://linux-hardware.org/?probe=3e5a2f20cc) | Feb 03, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [a99bd855d2](https://linux-hardware.org/?probe=a99bd855d2) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | [2aa4452578](https://linux-hardware.org/?probe=2aa4452578) | Feb 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [516e83f7e6](https://linux-hardware.org/?probe=516e83f7e6) | Feb 02, 2023 |
| PCWare        | IPMH61R3                    | [e296e8530f](https://linux-hardware.org/?probe=e296e8530f) | Feb 02, 2023 |
| ASUSTek       | H81M-A/BR                   | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6aa10285fe](https://linux-hardware.org/?probe=6aa10285fe) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | [20868d90a7](https://linux-hardware.org/?probe=20868d90a7) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | [d67831dc82](https://linux-hardware.org/?probe=d67831dc82) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [aa3b7e2dc8](https://linux-hardware.org/?probe=aa3b7e2dc8) | Feb 01, 2023 |
| AZW           | U59                         | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| AMD           | Inagua CRB                  | [3f497311dd](https://linux-hardware.org/?probe=3f497311dd) | Jan 31, 2023 |
| Dell          | 06HR05 A00                  | [b80c55d90d](https://linux-hardware.org/?probe=b80c55d90d) | Jan 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [d8d386cb1d](https://linux-hardware.org/?probe=d8d386cb1d) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| ASUSTek       | H61M-A/BR                   | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| PCWare        | IPMH110G                    | [95fe94d9f4](https://linux-hardware.org/?probe=95fe94d9f4) | Jan 30, 2023 |
| ASUSTek       | H81M-CS/BR                  | [ca82a3e5a7](https://linux-hardware.org/?probe=ca82a3e5a7) | Jan 29, 2023 |
| Intel         | H61                         | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| Dell          | 0VRWRC A01                  | [0e6a170715](https://linux-hardware.org/?probe=0e6a170715) | Jan 29, 2023 |
| Intel         | H61                         | [0ce404915f](https://linux-hardware.org/?probe=0ce404915f) | Jan 29, 2023 |
| Toshiba       | STI 010433                  | [fead488cf1](https://linux-hardware.org/?probe=fead488cf1) | Jan 29, 2023 |
| ASUSTek       | PRIME Z690-A                | [8dee7ae6ec](https://linux-hardware.org/?probe=8dee7ae6ec) | Jan 28, 2023 |
| ASUSTek       | H81M-A/BR                   | [ca72045652](https://linux-hardware.org/?probe=ca72045652) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASRock        | N68C-S UCC                  | [de8739d9d5](https://linux-hardware.org/?probe=de8739d9d5) | Jan 28, 2023 |
| ASUSTek       | A58M-A/BR                   | [2e6e55e6ea](https://linux-hardware.org/?probe=2e6e55e6ea) | Jan 28, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [41ff395299](https://linux-hardware.org/?probe=41ff395299) | Jan 28, 2023 |
| Gigabyte      | B75M-D3H                    | [3ee2e6ab56](https://linux-hardware.org/?probe=3ee2e6ab56) | Jan 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [8965805130](https://linux-hardware.org/?probe=8965805130) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Positivo      | POS-PIB150DT                | [5a333d4e71](https://linux-hardware.org/?probe=5a333d4e71) | Jan 26, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [90de00d686](https://linux-hardware.org/?probe=90de00d686) | Jan 26, 2023 |
| HP            | 225E                        | [bace147a01](https://linux-hardware.org/?probe=bace147a01) | Jan 26, 2023 |
| HP            | 8299                        | [d73eaeeb81](https://linux-hardware.org/?probe=d73eaeeb81) | Jan 26, 2023 |
| HP            | 8299                        | [47b5f3fdef](https://linux-hardware.org/?probe=47b5f3fdef) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| Gigabyte      | B75M-D3H                    | [6eafb4ceab](https://linux-hardware.org/?probe=6eafb4ceab) | Jan 25, 2023 |
| ASUSTek       | P8H67-M LX                  | [b8045702e2](https://linux-hardware.org/?probe=b8045702e2) | Jan 25, 2023 |
| Gigabyte      | P43-ES3G                    | [5e044ca68b](https://linux-hardware.org/?probe=5e044ca68b) | Jan 25, 2023 |
| Intel         | DG31PR AAE58249-306         | [a123c38d76](https://linux-hardware.org/?probe=a123c38d76) | Jan 25, 2023 |
| MSI           | 2A9C                        | [cea7204c4b](https://linux-hardware.org/?probe=cea7204c4b) | Jan 25, 2023 |
| Gigabyte      | H310M M.2                   | [2fbe64570f](https://linux-hardware.org/?probe=2fbe64570f) | Jan 25, 2023 |
| Gigabyte      | H310M M.2                   | [30967bc549](https://linux-hardware.org/?probe=30967bc549) | Jan 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 572      | 10.79%  |
| Ubuntu 18.04                 | 410      | 7.73%   |
| Ubuntu 22.04                 | 200      | 3.77%   |
| OpenMandriva 4.2             | 173      | 3.26%   |
| OpenMandriva 4.3             | 139      | 2.62%   |
| Linux Mint 20                | 119      | 2.24%   |
| Linux Mint 19.3              | 117      | 2.21%   |
| Pop!_OS 20.04                | 114      | 2.15%   |
| Linux Mint 19.1              | 110      | 2.07%   |
| KDE neon 20.04               | 98       | 1.85%   |
| Ubuntu 19.04                 | 95       | 1.79%   |
| Zorin 16                     | 91       | 1.72%   |
| Linux Mint 20.1              | 88       | 1.66%   |
| Pop!_OS 22.04                | 81       | 1.53%   |
| Manjaro                      | 81       | 1.53%   |
| Linux Mint 20.3              | 77       | 1.45%   |
| Debian 11                    | 76       | 1.43%   |
| Arch Rolling                 | 74       | 1.4%    |
| Arch                         | 69       | 1.3%    |
| Linux Mint 21.1              | 68       | 1.28%   |
| Linux Mint 20.2              | 66       | 1.24%   |
| OpenMandriva 23.03           | 62       | 1.17%   |
| Pop!_OS 20.10                | 61       | 1.15%   |
| Debian 10                    | 61       | 1.15%   |
| Ubuntu MATE 20.04            | 59       | 1.11%   |
| Ubuntu 19.10                 | 58       | 1.09%   |
| Pop!_OS 21.04                | 57       | 1.08%   |
| Zorin 15                     | 54       | 1.02%   |
| OpenMandriva 23.01           | 51       | 0.96%   |
| Fedora 36                    | 49       | 0.92%   |
| Linux Mint 19.2              | 48       | 0.91%   |
| Fedora 37                    | 48       | 0.91%   |
| Xubuntu 20.04                | 46       | 0.87%   |
| Linux Mint 21                | 46       | 0.87%   |
| Fedora 38                    | 43       | 0.81%   |
| Fedora 34                    | 43       | 0.81%   |
| Fedora 32                    | 39       | 0.74%   |
| openSUSE Tumbleweed-XXXXXXXX | 38       | 0.72%   |
| Fedora 33                    | 38       | 0.72%   |
| Ubuntu 18.10                 | 36       | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1483     | 29.41%  |
| Linux Mint    | 740      | 14.68%  |
| OpenMandriva  | 437      | 8.67%   |
| Pop!_OS       | 329      | 6.53%   |
| Fedora        | 289      | 5.73%   |
| Debian        | 194      | 3.85%   |
| Endless       | 164      | 3.25%   |
| Manjaro       | 159      | 3.15%   |
| Zorin         | 150      | 2.98%   |
| Arch          | 140      | 2.78%   |
| KDE neon      | 120      | 2.38%   |
| Xubuntu       | 103      | 2.04%   |
| Kubuntu       | 91       | 1.8%    |
| ROSA          | 78       | 1.55%   |
| Ubuntu MATE   | 73       | 1.45%   |
| openSUSE      | 59       | 1.17%   |
| Lubuntu       | 35       | 0.69%   |
| Ubuntu Unity  | 34       | 0.67%   |
| ArcoLinux     | 33       | 0.65%   |
| Elementary    | 32       | 0.63%   |
| LMDE          | 30       | 0.6%    |
| Kali          | 18       | 0.36%   |
| LinuxFX       | 16       | 0.32%   |
| Deepin        | 16       | 0.32%   |
| CentOS        | 16       | 0.32%   |
| BlackPanther  | 16       | 0.32%   |
| BigLinux      | 15       | 0.3%    |
| Ubuntu Budgie | 14       | 0.28%   |
| Gentoo        | 11       | 0.22%   |
| Clear Linux   | 10       | 0.2%    |
| Nobara        | 8        | 0.16%   |
| Linux Lite    | 7        | 0.14%   |
| Garuda Linux  | 7        | 0.14%   |
| EndeavourOS   | 7        | 0.14%   |
| Peppermint    | 6        | 0.12%   |
| Parrot        | 6        | 0.12%   |
| MX            | 6        | 0.12%   |
| Ubuntu Studio | 5        | 0.1%    |
| Sparky        | 5        | 0.1%    |
| Solus         | 5        | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 229      | 3.99%   |
| 5.10.14-desktop-1omv4002 | 168      | 2.92%   |
| 5.16.7-desktop-1omv4003  | 128      | 2.23%   |
| 4.15.0-46-generic        | 84       | 1.46%   |
| 5.4.0-48-generic         | 65       | 1.13%   |
| 6.2.6-desktop-1omv2390   | 60       | 1.04%   |
| 4.18.0-15-generic        | 49       | 0.85%   |
| 5.4.0-7634-generic       | 48       | 0.84%   |
| 5.4.0-58-generic         | 45       | 0.78%   |
| 6.1.1-desktop-1omv2290   | 44       | 0.77%   |
| 5.4.0-52-generic         | 43       | 0.75%   |
| 5.3.0-40-generic         | 43       | 0.75%   |
| 5.4.0-40-generic         | 41       | 0.71%   |
| 5.4.0-47-generic         | 40       | 0.7%    |
| 5.11.0-7620-generic      | 37       | 0.64%   |
| 5.3.0-28-generic         | 36       | 0.63%   |
| 5.15.0-56-generic        | 36       | 0.63%   |
| 5.4.0-26-generic         | 35       | 0.61%   |
| 4.15.0-20-generic        | 33       | 0.57%   |
| 5.4.0-70-generic         | 32       | 0.56%   |
| 5.4.0-72-generic         | 31       | 0.54%   |
| 6.2.6-76060206-generic   | 30       | 0.52%   |
| 5.0.0-32-generic         | 30       | 0.52%   |
| 5.4.0-91-generic         | 28       | 0.49%   |
| 5.3.0-46-generic         | 28       | 0.49%   |
| 5.0.0-37-generic         | 28       | 0.49%   |
| 5.8.0-7630-generic       | 27       | 0.47%   |
| 5.4.0-33-generic         | 27       | 0.47%   |
| 4.15.0-54-generic        | 27       | 0.47%   |
| 5.15.0-46-generic        | 25       | 0.44%   |
| 5.15.0-52-generic        | 24       | 0.42%   |
| 5.11.0-37-generic        | 24       | 0.42%   |
| 5.8.0-59-generic         | 23       | 0.4%    |
| 5.8.0-14-generic         | 23       | 0.4%    |
| 5.4.0-74-generic         | 23       | 0.4%    |
| 5.4.0-66-generic         | 23       | 0.4%    |
| 5.4.0-54-generic         | 23       | 0.4%    |
| 5.4.0-37-generic         | 23       | 0.4%    |
| 5.15.0-67-generic        | 23       | 0.4%    |
| 5.15.0-58-generic        | 23       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 1131     | 20.86%  |
| 4.15.0  | 419      | 7.73%   |
| 5.15.0  | 366      | 6.75%   |
| 5.8.0   | 258      | 4.76%   |
| 5.11.0  | 252      | 4.65%   |
| 5.3.0   | 244      | 4.5%    |
| 5.0.0   | 232      | 4.28%   |
| 5.13.0  | 174      | 3.21%   |
| 4.18.0  | 174      | 3.21%   |
| 5.10.14 | 168      | 3.1%    |
| 5.19.0  | 142      | 2.62%   |
| 5.16.7  | 128      | 2.36%   |
| 5.10.0  | 96       | 1.77%   |
| 6.2.6   | 94       | 1.73%   |
| 4.19.0  | 74       | 1.37%   |
| 6.1.1   | 47       | 0.87%   |
| 6.2.0   | 29       | 0.53%   |
| 5.7.9   | 21       | 0.39%   |
| 5.17.5  | 21       | 0.39%   |
| 4.4.0   | 20       | 0.37%   |
| 6.1.0   | 19       | 0.35%   |
| 4.9.0   | 18       | 0.33%   |
| 4.9.60  | 15       | 0.28%   |
| 6.0.12  | 14       | 0.26%   |
| 5.18.12 | 14       | 0.26%   |
| 5.13.19 | 14       | 0.26%   |
| 5.7.0   | 13       | 0.24%   |
| 5.16.13 | 13       | 0.24%   |
| 6.0.7   | 12       | 0.22%   |
| 6.0.10  | 12       | 0.22%   |
| 5.17.15 | 12       | 0.22%   |
| 5.15.5  | 12       | 0.22%   |
| 5.14.0  | 12       | 0.22%   |
| 4.18.16 | 12       | 0.22%   |
| 6.2.9   | 11       | 0.2%    |
| 5.16.11 | 11       | 0.2%    |
| 5.16.0  | 11       | 0.2%    |
| 5.12.4  | 11       | 0.2%    |
| 4.9.20  | 11       | 0.2%    |
| 5.6.19  | 10       | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4      | 1178     | 22.02%  |
| 5.15     | 456      | 8.52%   |
| 4.15     | 419      | 7.83%   |
| 5.10     | 346      | 6.47%   |
| 5.8      | 300      | 5.61%   |
| 5.11     | 280      | 5.23%   |
| 5.3      | 264      | 4.94%   |
| 5.0      | 246      | 4.6%    |
| 5.13     | 207      | 3.87%   |
| 5.19     | 192      | 3.59%   |
| 4.18     | 190      | 3.55%   |
| 5.16     | 185      | 3.46%   |
| 6.2      | 175      | 3.27%   |
| 6.1      | 142      | 2.65%   |
| 4.19     | 90       | 1.68%   |
| 6.0      | 79       | 1.48%   |
| 5.7      | 70       | 1.31%   |
| 5.18     | 58       | 1.08%   |
| 4.9      | 56       | 1.05%   |
| 5.17     | 53       | 0.99%   |
| 5.6      | 52       | 0.97%   |
| 5.12     | 49       | 0.92%   |
| 6.3      | 47       | 0.88%   |
| 5.14     | 45       | 0.84%   |
| 5.9      | 35       | 0.65%   |
| 6.4      | 33       | 0.62%   |
| 4.4      | 20       | 0.37%   |
| 5.5      | 16       | 0.3%    |
| 5.2      | 13       | 0.24%   |
| 5.1      | 11       | 0.21%   |
| 3.10     | 9        | 0.17%   |
| 4.1      | 8        | 0.15%   |
| 4.13     | 6        | 0.11%   |
| 4.20     | 5        | 0.09%   |
| 4.12     | 5        | 0.09%   |
| 4.10     | 5        | 0.09%   |
| 4.8      | 2        | 0.04%   |
| 5.15.107 | 1        | 0.02%   |
| 4.14     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4707     | 97.39%  |
| i686   | 126      | 2.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 2012     | 39.71%  |
| KDE5                     | 806      | 15.91%  |
| Unknown                  | 782      | 15.43%  |
| X-Cinnamon               | 454      | 8.96%   |
| XFCE                     | 363      | 7.16%   |
| MATE                     | 167      | 3.3%    |
| KDE                      | 141      | 2.78%   |
| Cinnamon                 | 89       | 1.76%   |
| KDE4                     | 38       | 0.75%   |
| LXQt                     | 35       | 0.69%   |
| Unity                    | 34       | 0.67%   |
| Pantheon                 | 28       | 0.55%   |
| Budgie                   | 23       | 0.45%   |
| Deepin                   | 20       | 0.39%   |
| LXDE                     | 17       | 0.34%   |
| GNOME Flashback          | 13       | 0.26%   |
| i3                       | 12       | 0.24%   |
| GNOME Classic            | 5        | 0.1%    |
| awesome                  | 5        | 0.1%    |
| sway                     | 4        | 0.08%   |
| Openbox                  | 4        | 0.08%   |
| Enlightenment            | 4        | 0.08%   |
| bspwm                    | 3        | 0.06%   |
| qtile                    | 2        | 0.04%   |
| icewm                    | 2        | 0.04%   |
| Hyprland                 | 1        | 0.02%   |
| DDE                      | 1        | 0.02%   |
| 03WindowMaker            | 1        | 0.02%   |
| /usr/bin/openbox-session | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 3989     | 80.75%  |
| Wayland | 547      | 11.07%  |
| Unknown | 364      | 7.37%   |
| Tty     | 38       | 0.77%   |
| Web     | 2        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2948     | 59.17%  |
| SDDM    | 688      | 13.81%  |
| GDM     | 443      | 8.89%   |
| GDM3    | 344      | 6.9%    |
| LightDM | 272      | 5.46%   |
| TDM     | 236      | 4.74%   |
| KDM     | 39       | 0.78%   |
| XDM     | 5        | 0.1%    |
| SLiM    | 3        | 0.06%   |
| SLIMSKI | 2        | 0.04%   |
| MDM     | 1        | 0.02%   |
| LXDM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pt_BR       | 3239     | 65.43%  |
| en_US       | 839      | 16.95%  |
| Unknown     | 749      | 15.13%  |
| C           | 65       | 1.31%   |
| pt_PT       | 21       | 0.42%   |
| en_GB       | 16       | 0.32%   |
| es_ES       | 6        | 0.12%   |
| en_CA       | 5        | 0.1%    |
| en_AG       | 2        | 0.04%   |
| C.UTF8      | 2        | 0.04%   |
| pt_BRutf8   | 1        | 0.02%   |
| eo          | 1        | 0.02%   |
| en_US.utf-8 | 1        | 0.02%   |
| en_IN       | 1        | 0.02%   |
| en_IE.UTF8  | 1        | 0.02%   |
| de_DE       | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3350     | 67.83%  |
| EFI  | 1589     | 32.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3628     | 73.04%  |
| Overlay | 483      | 9.72%   |
| Btrfs   | 393      | 7.91%   |
| Unknown | 304      | 6.12%   |
| Tmpfs   | 66       | 1.33%   |
| Xfs     | 45       | 0.91%   |
| Zfs     | 20       | 0.4%    |
| F2fs    | 8        | 0.16%   |
| Ext3    | 8        | 0.16%   |
| Ext2    | 8        | 0.16%   |
| Aufs    | 2        | 0.04%   |
| XXXXXXX | 1        | 0.02%   |
| Jfs     | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3081     | 62.17%  |
| GPT     | 1154     | 23.28%  |
| MBR     | 721      | 14.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4160     | 84.14%  |
| Yes       | 784      | 15.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3346     | 67.83%  |
| Yes       | 1587     | 32.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1252     | 25.93%  |
| Gigabyte Technology | 820      | 16.98%  |
| ASRock              | 422      | 8.74%   |
| Intel               | 412      | 8.53%   |
| Dell                | 280      | 5.8%    |
| MSI                 | 206      | 4.27%   |
| Positivo            | 201      | 4.16%   |
| Unknown             | 159      | 3.29%   |
| Hewlett-Packard     | 151      | 3.13%   |
| PCWare              | 117      | 2.42%   |
| Biostar             | 100      | 2.07%   |
| Lenovo              | 88       | 1.82%   |
| Pegatron            | 71       | 1.47%   |
| ECS                 | 65       | 1.35%   |
| Semp Toshiba        | 46       | 0.95%   |
| Itautec             | 46       | 0.95%   |
| Huanan              | 37       | 0.77%   |
| Megaware            | 28       | 0.58%   |
| Foxconn             | 28       | 0.58%   |
| OEM                 | 23       | 0.48%   |
| MACHINIST           | 17       | 0.35%   |
| Login Informatica   | 16       | 0.33%   |
| AMD                 | 14       | 0.29%   |
| Qbex                | 12       | 0.25%   |
| Digiboard           | 11       | 0.23%   |
| VS Company          | 10       | 0.21%   |
| PCChips             | 10       | 0.21%   |
| Supermicro          | 9        | 0.19%   |
| Philco              | 9        | 0.19%   |
| Digitron            | 9        | 0.19%   |
| Daten Tecnologia    | 8        | 0.17%   |
| Colorful Technology | 7        | 0.14%   |
| Phitronics          | 6        | 0.12%   |
| INTELBRAS           | 6        | 0.12%   |
| CCE                 | 6        | 0.12%   |
| Kllisre             | 5        | 0.1%    |
| IBM                 | 5        | 0.1%    |
| Centrium            | 5        | 0.1%    |
| AZW                 | 5        | 0.1%    |
| AMI                 | 5        | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 177      | 3.67%   |
| ASUS All Series               | 151      | 3.13%   |
| Intel H61                     | 92       | 1.91%   |
| ASUS PRIME B450M-GAMING/BR    | 63       | 1.3%    |
| ASRock A320M-HD               | 55       | 1.14%   |
| ASUS PRIME A320M-K/BR         | 52       | 1.08%   |
| ASUS M5A78L-M LX/BR           | 52       | 1.08%   |
| Intel H55                     | 51       | 1.06%   |
| Semp Toshiba STI              | 45       | 0.93%   |
| Gigabyte A320M-S2H            | 40       | 0.83%   |
| Gigabyte H61M-S1              | 39       | 0.81%   |
| ASRock B450M Steel Legend     | 37       | 0.77%   |
| ASUS P8H61-M LX3 R2.0         | 36       | 0.75%   |
| Gigabyte B75M-D3H             | 34       | 0.7%    |
| ASUS M5A78L-M PLUS/USB3       | 32       | 0.66%   |
| Intel B75                     | 31       | 0.64%   |
| ASRock N68-S3 FX              | 29       | 0.6%    |
| ASUS TUF Gaming X570-PLUS_BR  | 27       | 0.56%   |
| ASUS H61M-A/BR                | 26       | 0.54%   |
| Gigabyte AB350M-DS3H V2       | 25       | 0.52%   |
| ASUS M5A78L-M/USB3            | 25       | 0.52%   |
| Gigabyte B450M DS3H           | 23       | 0.48%   |
| ASUS P5G41T-M LX2/BR          | 23       | 0.48%   |
| ASUS P8H61-M LX2 R2.0         | 22       | 0.46%   |
| Positivo POS-EIH61CE          | 20       | 0.41%   |
| Intel MAHOBAY                 | 20       | 0.41%   |
| HP Compaq 6005 Pro SFF PC     | 20       | 0.41%   |
| Gigabyte 970A-DS3P            | 20       | 0.41%   |
| Biostar A320MH                | 19       | 0.39%   |
| ASUS M4N68T-M LE              | 19       | 0.39%   |
| Gigabyte GA-78LMT-USB3 6.0    | 18       | 0.37%   |
| Gigabyte G31M-ES2C            | 18       | 0.37%   |
| Dell XPS 8700                 | 18       | 0.37%   |
| ASUS TUF B360M-PLUS GAMING/BR | 18       | 0.37%   |
| Gigabyte 945GCM-S2C           | 17       | 0.35%   |
| ASUS PRIME H310M-E R2.0/BR    | 17       | 0.35%   |
| ASUS P8H61-M LE/BR            | 17       | 0.35%   |
| Pegatron IPM41-D3             | 16       | 0.33%   |
| Gigabyte GA-78LMT-S2          | 16       | 0.33%   |
| Gigabyte B450 AORUS M         | 16       | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 244      | 5.05%   |
| Unknown                | 177      | 3.67%   |
| Dell OptiPlex          | 165      | 3.42%   |
| ASUS All               | 151      | 3.13%   |
| ASUS M5A78L-M          | 129      | 2.67%   |
| ASUS TUF               | 118      | 2.44%   |
| Intel H61              | 96       | 1.99%   |
| ASUS P8H61-M           | 91       | 1.88%   |
| HP Compaq              | 74       | 1.53%   |
| Lenovo ThinkCentre     | 62       | 1.28%   |
| ASRock A320M-HD        | 56       | 1.16%   |
| ASUS ROG               | 52       | 1.08%   |
| Intel H55              | 51       | 1.06%   |
| Semp Toshiba STI       | 46       | 0.95%   |
| Gigabyte A320M-S2H     | 40       | 0.83%   |
| Itautec Infoway        | 39       | 0.81%   |
| Gigabyte H61M-S1       | 39       | 0.81%   |
| ASRock B450M           | 39       | 0.81%   |
| Gigabyte B450M         | 37       | 0.77%   |
| Intel B75              | 34       | 0.7%    |
| Gigabyte B75M-D3H      | 34       | 0.7%    |
| Gigabyte GA-78LMT-USB3 | 32       | 0.66%   |
| Dell Inspiron          | 30       | 0.62%   |
| ASRock N68-S3          | 30       | 0.62%   |
| Dell XPS               | 29       | 0.6%    |
| HP EliteDesk           | 28       | 0.58%   |
| Dell Precision         | 27       | 0.56%   |
| Gigabyte B450          | 26       | 0.54%   |
| ASUS P5G41T-M          | 26       | 0.54%   |
| ASUS H61M-A            | 26       | 0.54%   |
| Gigabyte AB350M-DS3H   | 25       | 0.52%   |
| Intel X99              | 24       | 0.5%    |
| Dell Vostro            | 24       | 0.5%    |
| Gigabyte 970A-DS3P     | 22       | 0.46%   |
| ASUS M5A97             | 21       | 0.43%   |
| Positivo POS-EIH61CE   | 20       | 0.41%   |
| Intel MAHOBAY          | 20       | 0.41%   |
| Biostar A320MH         | 20       | 0.41%   |
| ASUS M4N68T-M          | 19       | 0.39%   |
| ASRock N68-GS4         | 19       | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 533      | 11.04%  |
| 2012    | 489      | 10.13%  |
| 2011    | 487      | 10.08%  |
| 2017    | 418      | 8.66%   |
| 2013    | 365      | 7.56%   |
| 2014    | 342      | 7.08%   |
| 2010    | 334      | 6.92%   |
| 2019    | 312      | 6.46%   |
| 2009    | 299      | 6.19%   |
| 2008    | 236      | 4.89%   |
| 2020    | 224      | 4.64%   |
| 2016    | 213      | 4.41%   |
| 2007    | 193      | 4%      |
| 2021    | 115      | 2.38%   |
| 2015    | 107      | 2.22%   |
| 2022    | 62       | 1.28%   |
| 2006    | 62       | 1.28%   |
| 2005    | 17       | 0.35%   |
| 2023    | 8        | 0.17%   |
| Unknown | 7        | 0.14%   |
| 2004    | 5        | 0.1%    |
| 2003    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4829     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4746     | 98%     |
| Enabled  | 97       | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4829     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1150     | 23.22%  |
| 3.01-4.0        | 1128     | 22.78%  |
| 16.01-24.0      | 980      | 19.79%  |
| 4.01-8.0        | 899      | 18.15%  |
| 32.01-64.0      | 279      | 5.63%   |
| 1.01-2.0        | 258      | 5.21%   |
| 2.01-3.0        | 90       | 1.82%   |
| 24.01-32.0      | 83       | 1.68%   |
| 64.01-256.0     | 61       | 1.23%   |
| 0.51-1.0        | 20       | 0.4%    |
| Unknown         | 2        | 0.04%   |
| More than 256.0 | 1        | 0.02%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1990     | 37.22%  |
| 2.01-3.0   | 1376     | 25.73%  |
| 4.01-8.0   | 667      | 12.47%  |
| 3.01-4.0   | 641      | 11.99%  |
| 0.51-1.0   | 447      | 8.36%   |
| 8.01-16.0  | 128      | 2.39%   |
| 0.01-0.5   | 68       | 1.27%   |
| 16.01-24.0 | 20       | 0.37%   |
| 24.01-32.0 | 7        | 0.13%   |
| Unknown    | 2        | 0.04%   |
| 32.01-64.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2458     | 48.86%  |
| 2       | 1431     | 28.44%  |
| 3       | 627      | 12.46%  |
| 4       | 285      | 5.66%   |
| 5       | 93       | 1.85%   |
| 0       | 59       | 1.17%   |
| 6       | 54       | 1.07%   |
| 7       | 11       | 0.22%   |
| 8       | 7        | 0.14%   |
| 9       | 4        | 0.08%   |
| 14      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3054     | 62.44%  |
| Yes       | 1837     | 37.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4749     | 98.32%  |
| No        | 81       | 1.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3162     | 64.48%  |
| Yes       | 1742     | 35.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4035     | 82.62%  |
| Yes       | 849      | 17.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 4829     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Sao Paulo             | 649      | 12.88%  |
| Rio de Janeiro        | 339      | 6.73%   |
| Brasília             | 143      | 2.84%   |
| Belo Horizonte        | 139      | 2.76%   |
| Porto Alegre          | 119      | 2.36%   |
| Curitiba              | 117      | 2.32%   |
| Fortaleza             | 89       | 1.77%   |
| Campinas              | 75       | 1.49%   |
| Salvador              | 65       | 1.29%   |
| Recife                | 60       | 1.19%   |
| Santo André          | 56       | 1.11%   |
| Goiânia              | 56       | 1.11%   |
| Florianópolis        | 53       | 1.05%   |
| Guarulhos             | 47       | 0.93%   |
| Niterói              | 41       | 0.81%   |
| Manaus                | 41       | 0.81%   |
| Osasco                | 38       | 0.75%   |
| Londrina              | 34       | 0.68%   |
| Sorocaba              | 33       | 0.66%   |
| Juiz de Fora          | 32       | 0.64%   |
| Sao José dos Campos  | 31       | 0.62%   |
| Natal                 | 31       | 0.62%   |
| Duque de Caxias       | 30       | 0.6%    |
| Maringá              | 29       | 0.58%   |
| Joinville             | 29       | 0.58%   |
| Campo Grande          | 29       | 0.58%   |
| Belém                | 29       | 0.58%   |
| Serra                 | 28       | 0.56%   |
| Blumenau              | 26       | 0.52%   |
| Palmas                | 25       | 0.5%    |
| Uberlândia           | 23       | 0.46%   |
| Sao Goncalo           | 23       | 0.46%   |
| Ribeirao Preto        | 23       | 0.46%   |
| Joao Pessoa           | 23       | 0.46%   |
| Maceió               | 22       | 0.44%   |
| Teresina              | 20       | 0.4%    |
| Sao Jose              | 20       | 0.4%    |
| Sao Bernardo do Campo | 20       | 0.4%    |
| Contagem              | 20       | 0.4%    |
| Vitória              | 19       | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1919     | 2915   | 24.22%  |
| WDC                         | 1463     | 2026   | 18.47%  |
| Samsung Electronics         | 1022     | 1494   | 12.9%   |
| Kingston                    | 903      | 1234   | 11.4%   |
| Toshiba                     | 342      | 407    | 4.32%   |
| SanDisk                     | 339      | 481    | 4.28%   |
| China                       | 236      | 276    | 2.98%   |
| Hitachi                     | 185      | 224    | 2.33%   |
| Crucial                     | 156      | 194    | 1.97%   |
| Maxtor                      | 118      | 139    | 1.49%   |
| Silicon Motion              | 114      | 150    | 1.44%   |
| A-DATA Technology           | 106      | 128    | 1.34%   |
| Realtek Semiconductor       | 64       | 79     | 0.81%   |
| Lexar                       | 60       | 65     | 0.76%   |
| KingSpec                    | 58       | 67     | 0.73%   |
| Unknown                     | 48       | 70     | 0.61%   |
| XPG                         | 45       | 56     | 0.57%   |
| Intel                       | 37       | 42     | 0.47%   |
| Corsair                     | 37       | 49     | 0.47%   |
| Phison                      | 33       | 51     | 0.42%   |
| Netac                       | 33       | 48     | 0.42%   |
| HGST                        | 33       | 38     | 0.42%   |
| Hewlett-Packard             | 30       | 36     | 0.38%   |
| XrayDisk                    | 29       | 42     | 0.37%   |
| Patriot                     | 29       | 44     | 0.37%   |
| JMicron Technology          | 29       | 31     | 0.37%   |
| PNY                         | 26       | 27     | 0.33%   |
| Gigabyte Technology         | 21       | 29     | 0.27%   |
| Unknown                     | 20       | 21     | 0.25%   |
| Phison Electronics          | 18       | 27     | 0.23%   |
| LITEON                      | 17       | 17     | 0.21%   |
| KingDian                    | 17       | 18     | 0.21%   |
| ADATA Technology            | 17       | 22     | 0.21%   |
| MAXIO Technology (Hangzhou) | 16       | 20     | 0.2%    |
| Kingston Technology Company | 14       | 17     | 0.18%   |
| SK hynix                    | 13       | 33     | 0.16%   |
| Fujitsu                     | 13       | 14     | 0.16%   |
| OCZ                         | 12       | 13     | 0.15%   |
| Micron/Crucial Technology   | 12       | 20     | 0.15%   |
| walram                      | 11       | 11     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD     | 299      | 3.39%   |
| Seagate ST500DM002-1BD142 500GB     | 262      | 2.97%   |
| Seagate ST1000DM010-2EP102 1TB      | 225      | 2.55%   |
| Kingston SA400S37120G 120GB SSD     | 172      | 1.95%   |
| Kingston SA400S37480G 480GB SSD     | 145      | 1.64%   |
| Samsung HD322HJ 320GB               | 124      | 1.41%   |
| Samsung HD502HJ 500GB               | 110      | 1.25%   |
| Samsung HD161HJ 160GB               | 106      | 1.2%    |
| Samsung HD502HI 500GB               | 102      | 1.16%   |
| Seagate ST1000DM003-1ER162 1TB      | 98       | 1.11%   |
| Seagate ST1000DM003-1CH162 1TB      | 94       | 1.07%   |
| Kingston SV300S37A120G 120GB SSD    | 87       | 0.99%   |
| WDC WD5000AAKX-003CA0 500GB         | 79       | 0.9%    |
| WDC WD10EARS-00Y5B1 1TB             | 70       | 0.79%   |
| Seagate ST3500312CS 500GB           | 70       | 0.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 69       | 0.78%   |
| Seagate ST3500418AS 500GB           | 68       | 0.77%   |
| SanDisk SSD PLUS 240GB              | 68       | 0.77%   |
| Seagate Expansion 1TB               | 64       | 0.73%   |
| Crucial CT240BX500SSD1 240GB        | 64       | 0.73%   |
| Seagate ST31000524AS 1TB            | 63       | 0.71%   |
| WDC WD10EZEX-00BN5A0 1TB            | 62       | 0.7%    |
| Toshiba DT01ACA050 500GB            | 58       | 0.66%   |
| Seagate ST2000DM006-2DM164 2TB      | 58       | 0.66%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 57       | 0.65%   |
| WDC WD10EZEX-00WN4A0 1TB            | 57       | 0.65%   |
| Toshiba HDWD110 1TB                 | 56       | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 52       | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 52       | 0.59%   |
| Seagate ST3320418AS 320GB           | 50       | 0.57%   |
| Samsung HD103SI 1TB                 | 49       | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB      | 48       | 0.54%   |
| SanDisk SDSSDA120G 120GB            | 47       | 0.53%   |
| Seagate ST3500413AS 500GB           | 46       | 0.52%   |
| Samsung HD103SJ 1TB                 | 46       | 0.52%   |
| SanDisk SSD PLUS 120GB              | 44       | 0.5%    |
| Samsung HD161GJ 160GB               | 44       | 0.5%    |
| Seagate ST31000528AS 1TB            | 43       | 0.49%   |
| SanDisk SDSSDA240G 240GB            | 43       | 0.49%   |
| Toshiba DT01ACA100 1TB              | 42       | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1914     | 2897   | 39.49%  |
| WDC                 | 1302     | 1772   | 26.86%  |
| Samsung Electronics | 873      | 1191   | 18.01%  |
| Toshiba             | 327      | 388    | 6.75%   |
| Hitachi             | 185      | 224    | 3.82%   |
| Maxtor              | 113      | 132    | 2.33%   |
| HGST                | 33       | 38     | 0.68%   |
| JMicron Technology  | 27       | 29     | 0.56%   |
| Hewlett-Packard     | 17       | 20     | 0.35%   |
| Fujitsu             | 13       | 14     | 0.27%   |
| ExcelStor           | 11       | 12     | 0.23%   |
| Unknown             | 10       | 10     | 0.21%   |
| HPE                 | 5        | 5      | 0.1%    |
| ASMT                | 3        | 3      | 0.06%   |
| USB3.0              | 2        | 2      | 0.04%   |
| Initio              | 2        | 2      | 0.04%   |
| External            | 2        | 2      | 0.04%   |
| MDT                 | 1        | 1      | 0.02%   |
| Lenovo              | 1        | 1      | 0.02%   |
| IBM                 | 1        | 3      | 0.02%   |
| HGST HTS            | 1        | 1      | 0.02%   |
| FEASSO              | 1        | 2      | 0.02%   |
| China               | 1        | 2      | 0.02%   |
| Apple               | 1        | 1      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 857      | 1165   | 35.57%  |
| SanDisk             | 302      | 423    | 12.54%  |
| China               | 234      | 273    | 9.71%   |
| WDC                 | 173      | 227    | 7.18%   |
| Crucial             | 151      | 188    | 6.27%   |
| Samsung Electronics | 106      | 209    | 4.4%    |
| A-DATA Technology   | 81       | 94     | 3.36%   |
| Lexar               | 58       | 63     | 2.41%   |
| KingSpec            | 56       | 65     | 2.32%   |
| Corsair             | 29       | 38     | 1.2%    |
| Intel               | 28       | 31     | 1.16%   |
| Patriot             | 27       | 41     | 1.12%   |
| PNY                 | 24       | 25     | 1%      |
| Netac               | 21       | 33     | 0.87%   |
| KingDian            | 17       | 18     | 0.71%   |
| Gigabyte Technology | 16       | 23     | 0.66%   |
| Unknown             | 14       | 14     | 0.58%   |
| XrayDisk            | 13       | 16     | 0.54%   |
| LITEON              | 13       | 13     | 0.54%   |
| OCZ                 | 12       | 13     | 0.5%    |
| Toshiba             | 11       | 14     | 0.46%   |
| Smart               | 9        | 11     | 0.37%   |
| Hewlett-Packard     | 9        | 11     | 0.37%   |
| Seagate             | 8        | 9      | 0.33%   |
| Team                | 7        | 7      | 0.29%   |
| BHT                 | 7        | 12     | 0.29%   |
| Unknown             | 6        | 6      | 0.25%   |
| Maxtor              | 5        | 7      | 0.21%   |
| KODAK               | 5        | 5      | 0.21%   |
| HS-SSD-C100         | 5        | 5      | 0.21%   |
| SK hynix            | 4        | 5      | 0.17%   |
| RZX                 | 4        | 10     | 0.17%   |
| Pichau              | 4        | 4      | 0.17%   |
| HUSKY               | 4        | 5      | 0.17%   |
| Colorful            | 4        | 5      | 0.17%   |
| Apacer              | 4        | 4      | 0.17%   |
| WALRAM              | 3        | 3      | 0.12%   |
| Plextor             | 3        | 4      | 0.12%   |
| NN                  | 3        | 5      | 0.12%   |
| MaxDigital          | 3        | 3      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3846     | 6753   | 58.16%  |
| SSD     | 2089     | 3203   | 31.59%  |
| NVMe    | 582      | 869    | 8.8%    |
| Unknown | 91       | 129    | 1.38%   |
| MMC     | 5        | 6      | 0.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4623     | 9804   | 85.48%  |
| NVMe | 580      | 866    | 10.72%  |
| SAS  | 200      | 284    | 3.7%    |
| MMC  | 5        | 6      | 0.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 3821     | 6541   | 62.5%   |
| 0.51-1.0        | 1718     | 2592   | 28.1%   |
| 1.01-2.0        | 373      | 532    | 6.1%    |
| 3.01-4.0        | 80       | 122    | 1.31%   |
| 2.01-3.0        | 68       | 93     | 1.11%   |
| 4.01-10.0       | 48       | 68     | 0.79%   |
| 10.01-20.0      | 5        | 7      | 0.08%   |
| More than 100.0 | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1293     | 25.02%  |
| 251-500        | 1174     | 22.72%  |
| 501-1000       | 734      | 14.21%  |
| 1001-2000      | 535      | 10.35%  |
| 1-20           | 422      | 8.17%   |
| 51-100         | 339      | 6.56%   |
| 21-50          | 192      | 3.72%   |
| 2001-3000      | 192      | 3.72%   |
| More than 3000 | 174      | 3.37%   |
| Unknown        | 112      | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1989     | 37.55%  |
| 21-50          | 933      | 17.61%  |
| 101-250        | 636      | 12.01%  |
| 51-100         | 569      | 10.74%  |
| 251-500        | 388      | 7.32%   |
| 501-1000       | 373      | 7.04%   |
| 1001-2000      | 184      | 3.47%   |
| Unknown        | 112      | 2.11%   |
| 2001-3000      | 59       | 1.11%   |
| More than 3000 | 54       | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 47       | 51     | 5.4%    |
| WDC WD5000AAKX-003CA0 500GB         | 25       | 26     | 2.87%   |
| Samsung Electronics HD322HJ 320GB   | 25       | 35     | 2.87%   |
| Samsung Electronics HD161HJ 160GB   | 23       | 24     | 2.64%   |
| Samsung Electronics HD502HI 500GB   | 20       | 24     | 2.3%    |
| Samsung Electronics HD502HJ 500GB   | 16       | 16     | 1.84%   |
| WDC WD10EARS-00Y5B1 1TB             | 12       | 14     | 1.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 12       | 12     | 1.38%   |
| Seagate ST1000DM010-2EP102 1TB      | 12       | 15     | 1.38%   |
| WDC WD3200AAJS-00L7A0 320GB         | 10       | 10     | 1.15%   |
| Maxtor STM3160215AS 160GB           | 10       | 11     | 1.15%   |
| Seagate ST3500418AS 500GB           | 9        | 14     | 1.03%   |
| Seagate ST3320418AS 320GB           | 9        | 13     | 1.03%   |
| Seagate ST31000524AS 1TB            | 9        | 9      | 1.03%   |
| Samsung Electronics HD250HJ 250GB   | 9        | 10     | 1.03%   |
| Samsung Electronics HD103SI 1TB     | 9        | 11     | 1.03%   |
| Samsung Electronics HD080HJ/ 80GB   | 9        | 11     | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8        | 10     | 0.92%   |
| Seagate ST1000DM003-1CH162 1TB      | 8        | 11     | 0.92%   |
| Samsung Electronics HD103SJ 1TB     | 8        | 10     | 0.92%   |
| Toshiba MQ01ABD050 500GB            | 7        | 7      | 0.8%    |
| Seagate ST3500413AS 500GB           | 7        | 8      | 0.8%    |
| Seagate ST3500312CS 500GB           | 7        | 7      | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB      | 7        | 9      | 0.8%    |
| Seagate ST1500DL003-9VT16L 1TB      | 7        | 8      | 0.8%    |
| Kingston SV300S37A120G 120GB SSD    | 7        | 7      | 0.8%    |
| WDC WD5000AAKX-083CA1 500GB         | 6        | 6      | 0.69%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 6        | 7      | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB            | 6        | 6      | 0.69%   |
| WDC WD10EZEX-00BN5A0 1TB            | 6        | 6      | 0.69%   |
| Seagate ST1000DM003-9YN162 1TB      | 6        | 6      | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB      | 6        | 8      | 0.69%   |
| Samsung Electronics HM321HI 320GB   | 6        | 6      | 0.69%   |
| Maxtor STM3250310AS 250GB           | 6        | 6      | 0.69%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 9      | 0.69%   |
| WDC WD5000AVCS-632DY1 500GB         | 5        | 6      | 0.57%   |
| Toshiba DT01ACA050 500GB            | 5        | 5      | 0.57%   |
| Seagate ST3250318AS 250GB           | 5        | 5      | 0.57%   |
| Seagate ST3160318AS 160GB           | 5        | 5      | 0.57%   |
| Seagate ST31000528AS 1TB            | 5        | 8      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 255      | 321    | 31.29%  |
| WDC                   | 199      | 232    | 24.42%  |
| Samsung Electronics   | 172      | 212    | 21.1%   |
| Toshiba               | 36       | 38     | 4.42%   |
| Hitachi               | 36       | 37     | 4.42%   |
| Kingston              | 27       | 31     | 3.31%   |
| Maxtor                | 21       | 23     | 2.58%   |
| China                 | 16       | 17     | 1.96%   |
| SanDisk               | 7        | 8      | 0.86%   |
| XPG                   | 6        | 6      | 0.74%   |
| A-DATA Technology     | 4        | 4      | 0.49%   |
| Netac                 | 3        | 3      | 0.37%   |
| Intel                 | 3        | 3      | 0.37%   |
| Crucial               | 3        | 3      | 0.37%   |
| Unknown               | 3        | 3      | 0.37%   |
| OCZ                   | 2        | 2      | 0.25%   |
| Hewlett-Packard       | 2        | 2      | 0.25%   |
| ExcelStor             | 2        | 3      | 0.25%   |
| XrayDisk              | 1        | 2      | 0.12%   |
| Team                  | 1        | 1      | 0.12%   |
| Realtek Semiconductor | 1        | 2      | 0.12%   |
| PNY                   | 1        | 1      | 0.12%   |
| Plextor               | 1        | 1      | 0.12%   |
| OCZ-VERTEX3           | 1        | 1      | 0.12%   |
| Mushkin               | 1        | 1      | 0.12%   |
| LITEON                | 1        | 1      | 0.12%   |
| KingSpec              | 1        | 1      | 0.12%   |
| KEEPDATA              | 1        | 1      | 0.12%   |
| JMicron Technology    | 1        | 1      | 0.12%   |
| Initio                | 1        | 1      | 0.12%   |
| HGST                  | 1        | 1      | 0.12%   |
| Fujitsu               | 1        | 1      | 0.12%   |
| FEASSO                | 1        | 2      | 0.12%   |
| Fanxiang              | 1        | 1      | 0.12%   |
| EGON                  | 1        | 1      | 0.12%   |
| Corsair               | 1        | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 255      | 321    | 35.47%  |
| WDC                 | 191      | 222    | 26.56%  |
| Samsung Electronics | 171      | 211    | 23.78%  |
| Toshiba             | 36       | 38     | 5.01%   |
| Hitachi             | 36       | 37     | 5.01%   |
| Maxtor              | 21       | 23     | 2.92%   |
| Hewlett-Packard     | 2        | 2      | 0.28%   |
| ExcelStor           | 2        | 3      | 0.28%   |
| JMicron Technology  | 1        | 1      | 0.14%   |
| Initio              | 1        | 1      | 0.14%   |
| HGST                | 1        | 1      | 0.14%   |
| Fujitsu             | 1        | 1      | 0.14%   |
| FEASSO              | 1        | 2      | 0.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 628      | 863    | 86.86%  |
| SSD  | 82       | 92     | 11.34%  |
| NVMe | 13       | 14     | 1.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 4        | 4      | 20%     |
| Samsung Electronics HD502HJ 500GB | 3        | 5      | 15%     |
| WDC WD5000AAKS-00C8A0 500GB       | 1        | 1      | 5%      |
| WDC WD3200BPVT-00JJ5T0 320GB      | 1        | 1      | 5%      |
| WDC WD1600BEVT-22ZCT0 160GB       | 1        | 1      | 5%      |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 5%      |
| Seagate ST3320613AS 320GB         | 1        | 1      | 5%      |
| Seagate ST31000528AS 1TB          | 1        | 1      | 5%      |
| Seagate ST31000340NS 1TB          | 1        | 1      | 5%      |
| Samsung Electronics HM641JI 640GB | 1        | 1      | 5%      |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 5%      |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 5%      |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 5%      |
| Samsung Electronics HD080HJ/ 80GB | 1        | 1      | 5%      |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 10     | 40%     |
| Seagate             | 7        | 7      | 35%     |
| WDC                 | 3        | 3      | 15%     |
| Toshiba             | 1        | 1      | 5%      |
| Hitachi             | 1        | 1      | 5%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3269     | 7412   | 61.24%  |
| Works    | 1360     | 2557   | 25.48%  |
| Malfunc  | 689      | 969    | 12.91%  |
| Failed   | 20       | 22     | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3166     | 55.36%  |
| AMD                              | 1367     | 23.9%   |
| Nvidia                           | 223      | 3.9%    |
| Silicon Motion                   | 129      | 2.26%   |
| Realtek Semiconductor            | 87       | 1.52%   |
| Marvell Technology Group         | 85       | 1.49%   |
| JMicron Technology               | 84       | 1.47%   |
| ASMedia Technology               | 79       | 1.38%   |
| Kingston Technology Company      | 69       | 1.21%   |
| SanDisk                          | 68       | 1.19%   |
| Samsung Electronics              | 68       | 1.19%   |
| Phison Electronics               | 65       | 1.14%   |
| ADATA Technology                 | 58       | 1.01%   |
| VIA Technologies                 | 50       | 0.87%   |
| Micron/Crucial Technology        | 18       | 0.31%   |
| MAXIO Technology (Hangzhou)      | 18       | 0.31%   |
| LSI Logic / Symbios Logic        | 9        | 0.16%   |
| Broadcom / LSI                   | 9        | 0.16%   |
| SK hynix                         | 8        | 0.14%   |
| Silicon Integrated Systems [SiS] | 8        | 0.14%   |
| Netac Technology                 | 7        | 0.12%   |
| Lite-On Technology               | 6        | 0.1%    |
| Solid State Storage Technology   | 5        | 0.09%   |
| Silicon Image                    | 5        | 0.09%   |
| Beijing Starblaze Technology     | 5        | 0.09%   |
| Seagate Technology               | 4        | 0.07%   |
| OCZ Technology Group             | 4        | 0.07%   |
| Shenzhen Longsys Electronics     | 3        | 0.05%   |
| Adaptec                          | 3        | 0.05%   |
| INNOGRIT                         | 2        | 0.03%   |
| ULi Electronics                  | 1        | 0.02%   |
| TenaFe                           | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
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
| AMD FCH SATA Controller [AHCI mode]                                                     | 743      | 9.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 590      | 7.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 450      | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 430      | 5.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 346      | 4.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 322      | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 255      | 3.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 255      | 3.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 252      | 3.14%   |
| AMD FCH SATA Controller D                                                               | 245      | 3.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 239      | 2.98%   |
| Nvidia MCP61 SATA Controller                                                            | 184      | 2.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 182      | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 180      | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 177      | 2.21%   |
| Nvidia MCP61 IDE                                                                        | 151      | 1.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 125      | 1.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 121      | 1.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 111      | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 97       | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 96       | 1.2%    |
| AMD 300 Series Chipset SATA Controller                                                  | 91       | 1.13%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 88       | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 87       | 1.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 74       | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 73       | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 62       | 0.77%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 62       | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 59       | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 51       | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 51       | 0.64%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 50       | 0.62%   |
| AMD FCH IDE Controller                                                                  | 45       | 0.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 43       | 0.54%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.52%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 40       | 0.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 40       | 0.5%    |
| JMicron JMB368 IDE controller                                                           | 39       | 0.49%   |
| Phison E12 NVMe Controller                                                              | 37       | 0.46%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 37       | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3320     | 55.96%  |
| IDE  | 1864     | 31.42%  |
| NVMe | 587      | 9.89%   |
| RAID | 144      | 2.43%   |
| SCSI | 10       | 0.17%   |
| SAS  | 8        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 3240     | 67.09%  |
| AMD          | 1583     | 32.78%  |
| CentaurHauls | 5        | 0.1%    |
| Unknown      | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor              | 101      | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 88       | 1.81%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 85       | 1.75%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 81       | 1.67%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 71       | 1.46%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 66       | 1.36%   |
| AMD Ryzen 5 3600 6-Core Processor           | 65       | 1.34%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 61       | 1.26%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 60       | 1.23%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 59       | 1.21%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 59       | 1.21%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 58       | 1.19%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 56       | 1.15%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 56       | 1.15%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 55       | 1.13%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 53       | 1.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 52       | 1.07%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 50       | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 47       | 0.97%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 42       | 0.86%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 41       | 0.84%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 38       | 0.78%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 38       | 0.78%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 36       | 0.74%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 35       | 0.72%   |
| AMD FX-8300 Eight-Core Processor            | 35       | 0.72%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 32       | 0.66%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 31       | 0.64%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 31       | 0.64%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 31       | 0.64%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 30       | 0.62%   |
| AMD FX-4300 Quad-Core Processor             | 30       | 0.62%   |
| AMD Athlon II X2 250 Processor              | 30       | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 29       | 0.6%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 29       | 0.6%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 29       | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 28       | 0.58%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 28       | 0.58%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 27       | 0.56%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 27       | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 828      | 17.05%  |
| Intel Core i3           | 563      | 11.6%   |
| Intel Core i7           | 440      | 9.06%   |
| AMD Ryzen 5             | 397      | 8.18%   |
| AMD FX                  | 279      | 5.75%   |
| Intel Core 2 Duo        | 248      | 5.11%   |
| Intel Celeron           | 244      | 5.03%   |
| Intel Xeon              | 230      | 4.74%   |
| Intel Pentium Dual-Core | 186      | 3.83%   |
| AMD Ryzen 7             | 163      | 3.36%   |
| Intel Pentium           | 142      | 2.92%   |
| Intel Core 2 Quad       | 105      | 2.16%   |
| AMD Ryzen 3             | 104      | 2.14%   |
| AMD Phenom II X4        | 82       | 1.69%   |
| AMD Athlon II X2        | 76       | 1.57%   |
| Intel Pentium Dual      | 74       | 1.52%   |
| AMD Athlon              | 49       | 1.01%   |
| AMD Athlon 64 X2        | 45       | 0.93%   |
| AMD A8                  | 44       | 0.91%   |
| AMD Ryzen 9             | 41       | 0.84%   |
| Other                   | 40       | 0.82%   |
| AMD A4                  | 38       | 0.78%   |
| AMD A10                 | 38       | 0.78%   |
| Intel Core 2            | 35       | 0.72%   |
| Intel Atom              | 35       | 0.72%   |
| AMD Sempron             | 31       | 0.64%   |
| AMD Phenom II X6        | 31       | 0.64%   |
| Intel Pentium 4         | 28       | 0.58%   |
| AMD A6                  | 27       | 0.56%   |
| Intel Pentium Gold      | 20       | 0.41%   |
| Intel Core i9           | 20       | 0.41%   |
| AMD Phenom II X2        | 20       | 0.41%   |
| AMD Athlon II X4        | 18       | 0.37%   |
| AMD Phenom              | 14       | 0.29%   |
| Intel Pentium D         | 13       | 0.27%   |
| Intel Genuine           | 13       | 0.27%   |
| AMD Athlon II X3        | 13       | 0.27%   |
| AMD Ryzen 5 PRO         | 8        | 0.16%   |
| AMD Ryzen 3 PRO         | 8        | 0.16%   |
| AMD E                   | 8        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1827     | 37.64%  |
| 4       | 1732     | 35.68%  |
| 6       | 573      | 11.8%   |
| 8       | 250      | 5.15%   |
| 1       | 196      | 4.04%   |
| 3       | 146      | 3.01%   |
| 12      | 59       | 1.22%   |
| 10      | 25       | 0.52%   |
| 16      | 19       | 0.39%   |
| Unknown | 11       | 0.23%   |
| 14      | 7        | 0.14%   |
| 24      | 5        | 0.1%    |
| 28      | 1        | 0.02%   |
| 22      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |
| 18      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 4806     | 99.5%   |
| 2       | 23       | 0.48%   |
| Unknown | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2414     | 49.89%  |
| 1       | 2413     | 49.87%  |
| Unknown | 11       | 0.23%   |
| 4       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4584     | 94.38%  |
| Unknown        | 229      | 4.71%   |
| 64-bit         | 29       | 0.6%    |
| 32-bit         | 15       | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1094     | 21.83%  |
| 0x306a9    | 410      | 8.18%   |
| 0x206a7    | 395      | 7.88%   |
| 0x1067a    | 385      | 7.68%   |
| 0x306c3    | 316      | 6.31%   |
| 0x06000852 | 157      | 3.13%   |
| 0x906e9    | 130      | 2.59%   |
| 0x906ea    | 118      | 2.35%   |
| 0x010000c8 | 118      | 2.35%   |
| 0x6fd      | 101      | 2.02%   |
| 0x08108109 | 88       | 1.76%   |
| 0x0800820d | 85       | 1.7%    |
| 0x08701021 | 76       | 1.52%   |
| 0x20655    | 75       | 1.5%    |
| 0x306f2    | 57       | 1.14%   |
| 0x08701013 | 54       | 1.08%   |
| 0x6fb      | 51       | 1.02%   |
| 0x506e3    | 50       | 1%      |
| 0x20652    | 48       | 0.96%   |
| 0x06001119 | 45       | 0.9%    |
| 0x10676    | 44       | 0.88%   |
| 0x08101016 | 43       | 0.86%   |
| 0x106e5    | 38       | 0.76%   |
| 0x08001138 | 38       | 0.76%   |
| 0xa0653    | 37       | 0.74%   |
| 0x30678    | 35       | 0.7%    |
| 0x010000db | 34       | 0.68%   |
| 0x0600611a | 32       | 0.64%   |
| 0x06003106 | 32       | 0.64%   |
| 0x906eb    | 29       | 0.58%   |
| 0x306e4    | 29       | 0.58%   |
| 0x010000dc | 29       | 0.58%   |
| 0x906ed    | 28       | 0.56%   |
| 0x0600063e | 27       | 0.54%   |
| 0x0810100b | 26       | 0.52%   |
| 0x10661    | 25       | 0.5%    |
| 0x08001137 | 22       | 0.44%   |
| 0x206d7    | 21       | 0.42%   |
| 0x6f2      | 20       | 0.4%    |
| 0x6f6      | 18       | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 542      | 11.2%   |
| Penryn           | 500      | 10.33%  |
| SandyBridge      | 490      | 10.13%  |
| Haswell          | 467      | 9.65%   |
| KabyLake         | 403      | 8.33%   |
| Piledriver       | 289      | 5.97%   |
| K10              | 284      | 5.87%   |
| Zen+             | 245      | 5.06%   |
| Core             | 242      | 5%      |
| Zen              | 208      | 4.3%    |
| Zen 2            | 190      | 3.93%   |
| Westmere         | 158      | 3.27%   |
| Zen 3            | 102      | 2.11%   |
| CometLake        | 85       | 1.76%   |
| Skylake          | 81       | 1.67%   |
| Silvermont       | 75       | 1.55%   |
| K8 Hammer        | 67       | 1.38%   |
| Nehalem          | 61       | 1.26%   |
| NetBurst         | 49       | 1.01%   |
| Bulldozer        | 47       | 0.97%   |
| Steamroller      | 43       | 0.89%   |
| Excavator        | 42       | 0.87%   |
| Unknown          | 35       | 0.72%   |
| Bonnell          | 30       | 0.62%   |
| Bobcat           | 20       | 0.41%   |
| Jaguar           | 19       | 0.39%   |
| Broadwell        | 16       | 0.33%   |
| K10 Llano        | 14       | 0.29%   |
| Icelake          | 10       | 0.21%   |
| Goldmont plus    | 9        | 0.19%   |
| Alderlake Hybrid | 9        | 0.19%   |
| Tremont          | 3        | 0.06%   |
| Puma             | 1        | 0.02%   |
| K6               | 1        | 0.02%   |
| Goldmont         | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1829     | 36%     |
| Nvidia                           | 1740     | 34.25%  |
| AMD                              | 1457     | 28.68%  |
| VIA Technologies                 | 32       | 0.63%   |
| Matrox Electronics Systems       | 8        | 0.16%   |
| Silicon Integrated Systems [SiS] | 5        | 0.1%    |
| Silicon Motion                   | 4        | 0.08%   |
| ATI Technologies                 | 4        | 0.08%   |
| S3 Graphics                      | 1        | 0.02%   |
| ASPEED Technology                | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 295      | 5.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 257      | 4.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 202      | 3.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 179      | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 169      | 3.26%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 167      | 3.22%   |
| Nvidia GT218 [GeForce 210]                                                  | 152      | 2.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 109      | 2.1%    |
| Intel Core Processor Integrated Graphics Controller                         | 106      | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 101      | 1.95%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 98       | 1.89%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 92       | 1.77%   |
| AMD RS780L [Radeon 3000]                                                    | 88       | 1.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 84       | 1.62%   |
| Nvidia GK208B [GeForce GT 710]                                              | 82       | 1.58%   |
| Intel HD Graphics 630                                                       | 74       | 1.43%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 74       | 1.43%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 64       | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 63       | 1.21%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 61       | 1.18%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 61       | 1.18%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 56       | 1.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 54       | 1.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 53       | 1.02%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 51       | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 50       | 0.96%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 50       | 0.96%   |
| Nvidia GF108 [GeForce GT 730]                                               | 42       | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 41       | 0.79%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 41       | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 36       | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 36       | 0.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 36       | 0.69%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 36       | 0.69%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 35       | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 35       | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 35       | 0.67%   |
| Intel HD Graphics 530                                                       | 34       | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                               | 31       | 0.6%    |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 31       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 1675     | 34.2%   |
| 1 x Nvidia              | 1635     | 33.39%  |
| 1 x AMD                 | 1379     | 28.16%  |
| Intel + Nvidia          | 49       | 1%      |
| 2 x AMD                 | 40       | 0.82%   |
| 1 x VIA                 | 31       | 0.63%   |
| AMD + Nvidia            | 24       | 0.49%   |
| Intel + AMD             | 21       | 0.43%   |
| 2 x Nvidia              | 18       | 0.37%   |
| 1 x Matrox              | 7        | 0.14%   |
| 1 x SiS                 | 5        | 0.1%    |
| 2 x Intel               | 3        | 0.06%   |
| Intel + Silicon Motion  | 2        | 0.04%   |
| Other                   | 1        | 0.02%   |
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
| Free        | 3755     | 76.49%  |
| Proprietary | 918      | 18.7%   |
| Unknown     | 236      | 4.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2266     | 45.39%  |
| 1.01-2.0   | 739      | 14.8%   |
| 0.51-1.0   | 653      | 13.08%  |
| 0.01-0.5   | 517      | 10.36%  |
| 3.01-4.0   | 415      | 8.31%   |
| 7.01-8.0   | 202      | 4.05%   |
| 5.01-6.0   | 127      | 2.54%   |
| 2.01-3.0   | 46       | 0.92%   |
| 8.01-16.0  | 23       | 0.46%   |
| 4.01-5.0   | 2        | 0.04%   |
| 16.01-24.0 | 2        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 1290     | 26.91%  |
| Samsung Electronics  | 1069     | 22.3%   |
| AOC                  | 714      | 14.9%   |
| Dell                 | 364      | 7.59%   |
| Philips              | 265      | 5.53%   |
| Acer                 | 156      | 3.25%   |
| LG Electronics       | 154      | 3.21%   |
| Hewlett-Packard      | 100      | 2.09%   |
| BenQ                 | 58       | 1.21%   |
| Sony                 | 55       | 1.15%   |
| Unknown              | 53       | 1.11%   |
| Lenovo               | 43       | 0.9%    |
| Positivo             | 42       | 0.88%   |
| Ancor Communications | 23       | 0.48%   |
| Panasonic            | 22       | 0.46%   |
| ASUSTek Computer     | 22       | 0.46%   |
| GDH                  | 19       | 0.4%    |
| Unknown (XXX)        | 16       | 0.33%   |
| VIE                  | 13       | 0.27%   |
| TXD                  | 13       | 0.27%   |
| NCS                  | 13       | 0.27%   |
| RTK                  | 12       | 0.25%   |
| Daewoo               | 12       | 0.25%   |
| HB@                  | 11       | 0.23%   |
| Envision             | 10       | 0.21%   |
| Toshiba              | 9        | 0.19%   |
| AGO                  | 9        | 0.19%   |
| PZG                  | 8        | 0.17%   |
| JRY                  | 8        | 0.17%   |
| STA                  | 7        | 0.15%   |
| SKY                  | 7        | 0.15%   |
| MSI                  | 7        | 0.15%   |
| Unknown              | 7        | 0.15%   |
| ___                  | 6        | 0.13%   |
| Envision Peripherals | 6        | 0.13%   |
| CVT                  | 6        | 0.13%   |
| STD                  | 5        | 0.1%    |
| Proview              | 5        | 0.1%    |
| Pixio                | 5        | 0.1%    |
| Philco               | 5        | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 106      | 2.07%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 65       | 1.27%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 65       | 1.27%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 59       | 1.15%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 45       | 0.88%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 35       | 0.68%   |
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 35       | 0.68%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 33       | 0.64%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 33       | 0.64%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 32       | 0.62%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 30       | 0.59%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 30       | 0.59%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 29       | 0.57%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 29       | 0.57%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 27       | 0.53%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                       | 27       | 0.53%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 26       | 0.51%   |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                | 26       | 0.51%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 25       | 0.49%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 24       | 0.47%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 24       | 0.47%   |
| AOC 1619w AOC1619 1366x768 340x190mm 15.3-inch                       | 24       | 0.47%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch            | 23       | 0.45%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 21       | 0.41%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 21       | 0.41%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch               | 21       | 0.41%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                       | 21       | 0.41%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 21       | 0.41%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 20       | 0.39%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch    | 19       | 0.37%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 18       | 0.35%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 18       | 0.35%   |
| AOC 712Sa AOC1712 1280x1024 340x270mm 17.1-inch                      | 18       | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 17       | 0.33%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                 | 17       | 0.33%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 17       | 0.33%   |
| AOC 1943W AOC1943 1366x768 410x230mm 18.5-inch                       | 17       | 0.33%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch  | 16       | 0.31%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                | 16       | 0.31%   |
| Goldstar E2041 GSM4EC9 1600x900 443x249mm 20.0-inch                  | 16       | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1663     | 34.42%  |
| 1366x768 (WXGA)    | 765      | 15.83%  |
| 1600x900 (HD+)     | 364      | 7.53%   |
| 1440x900 (WXGA+)   | 322      | 6.66%   |
| 1280x1024 (SXGA)   | 318      | 6.58%   |
| 1360x768           | 285      | 5.9%    |
| 2560x1080          | 249      | 5.15%   |
| 3840x2160 (4K)     | 206      | 4.26%   |
| 1680x1050 (WSXGA+) | 160      | 3.31%   |
| 1024x768 (XGA)     | 101      | 2.09%   |
| Unknown            | 99       | 2.05%   |
| 2560x1440 (QHD)    | 63       | 1.3%    |
| 1280x720 (HD)      | 41       | 0.85%   |
| 3840x1080          | 27       | 0.56%   |
| 1920x540           | 22       | 0.46%   |
| 3440x1440          | 17       | 0.35%   |
| 1920x1200 (WUXGA)  | 17       | 0.35%   |
| 2288x1287          | 15       | 0.31%   |
| 1152x864           | 9        | 0.19%   |
| 4480x1080          | 6        | 0.12%   |
| 1600x1200          | 6        | 0.12%   |
| 1280x800 (WXGA)    | 6        | 0.12%   |
| 5760x1080          | 5        | 0.1%    |
| 3360x1080          | 5        | 0.1%    |
| 3200x1080          | 5        | 0.1%    |
| 3286x1080          | 4        | 0.08%   |
| 3520x1080          | 3        | 0.06%   |
| 2732x768           | 3        | 0.06%   |
| 2560x1600          | 3        | 0.06%   |
| 6400x1080          | 2        | 0.04%   |
| 3600x1080          | 2        | 0.04%   |
| 3360x1050          | 2        | 0.04%   |
| 2800x900           | 2        | 0.04%   |
| 2720x1024          | 2        | 0.04%   |
| 2646x768           | 2        | 0.04%   |
| 2646x1024          | 2        | 0.04%   |
| 1280x960           | 2        | 0.04%   |
| 640x480            | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 5760x2160          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 722      | 14.85%  |
| 21      | 582      | 11.97%  |
| 23      | 536      | 11.02%  |
| Unknown | 474      | 9.75%   |
| 17      | 352      | 7.24%   |
| 15      | 292      | 6.01%   |
| 19      | 271      | 5.57%   |
| 24      | 269      | 5.53%   |
| 20      | 269      | 5.53%   |
| 27      | 211      | 4.34%   |
| 34      | 210      | 4.32%   |
| 22      | 103      | 2.12%   |
| 31      | 95       | 1.95%   |
| 72      | 46       | 0.95%   |
| 40      | 41       | 0.84%   |
| 32      | 40       | 0.82%   |
| 28      | 38       | 0.78%   |
| 54      | 37       | 0.76%   |
| 84      | 35       | 0.72%   |
| 26      | 27       | 0.56%   |
| 46      | 26       | 0.53%   |
| 16      | 26       | 0.53%   |
| 52      | 23       | 0.47%   |
| 14      | 23       | 0.47%   |
| 12      | 18       | 0.37%   |
| 13      | 13       | 0.27%   |
| 142     | 11       | 0.23%   |
| 47      | 9        | 0.19%   |
| 25      | 9        | 0.19%   |
| 48      | 8        | 0.16%   |
| 37      | 6        | 0.12%   |
| 39      | 5        | 0.1%    |
| 65      | 4        | 0.08%   |
| 35      | 4        | 0.08%   |
| 43      | 3        | 0.06%   |
| 41      | 3        | 0.06%   |
| 60      | 2        | 0.04%   |
| 55      | 2        | 0.04%   |
| 50      | 2        | 0.04%   |
| 38      | 2        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 1825     | 38.58%  |
| 501-600        | 959      | 20.27%  |
| 301-350        | 562      | 11.88%  |
| Unknown        | 474      | 10.02%  |
| 701-800        | 251      | 5.31%   |
| 351-400        | 179      | 3.78%   |
| 601-700        | 165      | 3.49%   |
| 1001-1500      | 115      | 2.43%   |
| 1501-2000      | 82       | 1.73%   |
| 801-900        | 58       | 1.23%   |
| 201-300        | 42       | 0.89%   |
| More than 2000 | 11       | 0.23%   |
| 901-1000       | 7        | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2970     | 65.06%  |
| 16/10   | 423      | 9.27%   |
| Unknown | 420      | 9.2%    |
| 5/4     | 312      | 6.83%   |
| 21/9    | 238      | 5.21%   |
| 4/3     | 142      | 3.11%   |
| 3/2     | 42       | 0.92%   |
| 1.00    | 13       | 0.28%   |
| 6/5     | 1        | 0.02%   |
| 32/9    | 1        | 0.02%   |
| 2.00    | 1        | 0.02%   |
| 0.56    | 1        | 0.02%   |
| 0.31    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1254     | 26.13%  |
| 141-150        | 906      | 18.88%  |
| 151-200        | 737      | 15.36%  |
| Unknown        | 474      | 9.88%   |
| 351-500        | 362      | 7.54%   |
| 101-110        | 271      | 5.65%   |
| 301-350        | 214      | 4.46%   |
| More than 1000 | 173      | 3.6%    |
| 251-300        | 109      | 2.27%   |
| 501-1000       | 98       | 2.04%   |
| 131-140        | 97       | 2.02%   |
| 111-120        | 30       | 0.63%   |
| 81-90          | 20       | 0.42%   |
| 71-80          | 18       | 0.38%   |
| 91-100         | 18       | 0.38%   |
| 121-130        | 15       | 0.31%   |
| 51-60          | 2        | 0.04%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2974     | 64.54%  |
| 101-120 | 825      | 17.9%   |
| Unknown | 475      | 10.31%  |
| 1-50    | 244      | 5.3%    |
| 121-160 | 56       | 1.22%   |
| 161-240 | 34       | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3953     | 80.49%  |
| 2     | 647      | 13.17%  |
| 0     | 267      | 5.44%   |
| 3     | 40       | 0.81%   |
| 4     | 4        | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3460     | 53.36%  |
| Intel                             | 895      | 13.8%   |
| Qualcomm Atheros                  | 555      | 8.56%   |
| Ralink Technology                 | 346      | 5.34%   |
| Nvidia                            | 191      | 2.95%   |
| Broadcom                          | 151      | 2.33%   |
| TP-Link                           | 129      | 1.99%   |
| Qualcomm Atheros Communications   | 112      | 1.73%   |
| Ralink                            | 91       | 1.4%    |
| Samsung Electronics               | 61       | 0.94%   |
| D-Link                            | 55       | 0.85%   |
| Microsoft                         | 48       | 0.74%   |
| VIA Technologies                  | 47       | 0.72%   |
| Marvell Technology Group          | 43       | 0.66%   |
| Broadcom Limited                  | 33       | 0.51%   |
| Xiaomi                            | 29       | 0.45%   |
| MediaTek                          | 29       | 0.45%   |
| D-Link System                     | 29       | 0.45%   |
| JMicron Technology                | 23       | 0.35%   |
| Motorola PCS                      | 17       | 0.26%   |
| Motorola                          | 14       | 0.22%   |
| ASIX Electronics                  | 10       | 0.15%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.09%   |
| ICS Advent                        | 6        | 0.09%   |
| Huawei Technologies               | 6        | 0.09%   |
| Edimax Technology                 | 6        | 0.09%   |
| Mercucys                          | 5        | 0.08%   |
| DisplayLink                       | 5        | 0.08%   |
| ASUSTek Computer                  | 5        | 0.08%   |
| 3Com                              | 5        | 0.08%   |
| Sundance Technology Inc / IC Plus | 4        | 0.06%   |
| STMicroelectronics                | 4        | 0.06%   |
| Encore Electronics                | 4        | 0.06%   |
| Accton Technology                 | 4        | 0.06%   |
| Qualcomm                          | 3        | 0.05%   |
| LG Electronics                    | 3        | 0.05%   |
| Hangzhou Silan Microelectronics   | 3        | 0.05%   |
| Arduino SA                        | 3        | 0.05%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.03%   |
| T & A Mobile Phones               | 2        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2685     | 38.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 456      | 6.46%   |
| Ralink MT7601U Wireless Adapter                                   | 193      | 2.73%   |
| Nvidia MCP61 Ethernet                                             | 163      | 2.31%   |
| Qualcomm Atheros AR9271 802.11n                                   | 100      | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 98       | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 93       | 1.32%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 91       | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 90       | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 83       | 1.18%   |
| Intel I211 Gigabit Network Connection                             | 83       | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 81       | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 81       | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 75       | 1.06%   |
| Ralink RT5370 Wireless Adapter                                    | 72       | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 70       | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 65       | 0.92%   |
| Intel Wi-Fi 6 AX200                                               | 62       | 0.88%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 50       | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 49       | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 48       | 0.68%   |
| Realtek 802.11ac NIC                                              | 46       | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 43       | 0.61%   |
| Microsoft Xbox 360 Wireless Adapter                               | 42       | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 40       | 0.57%   |
| Intel 82578DC Gigabit Network Connection                          | 40       | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 36       | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 36       | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 35       | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 33       | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 31       | 0.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 30       | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 29       | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 29       | 0.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 28       | 0.4%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 27       | 0.38%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 26       | 0.37%   |
| Intel 82578DM Gigabit Network Connection                          | 26       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 497      | 26.85%  |
| Ralink Technology                     | 346      | 18.69%  |
| Qualcomm Atheros                      | 262      | 14.15%  |
| Intel                                 | 196      | 10.59%  |
| TP-Link                               | 125      | 6.75%   |
| Qualcomm Atheros Communications       | 112      | 6.05%   |
| Ralink                                | 91       | 4.92%   |
| D-Link                                | 55       | 2.97%   |
| Microsoft                             | 48       | 2.59%   |
| Broadcom                              | 35       | 1.89%   |
| MediaTek                              | 22       | 1.19%   |
| D-Link System                         | 18       | 0.97%   |
| Broadcom Limited                      | 7        | 0.38%   |
| Marvell Technology Group              | 6        | 0.32%   |
| Edimax Technology                     | 6        | 0.32%   |
| Mercucys                              | 5        | 0.27%   |
| Encore Electronics                    | 4        | 0.22%   |
| Micro Star International              | 2        | 0.11%   |
| Linksys                               | 2        | 0.11%   |
| IMC Networks                          | 2        | 0.11%   |
| ASUSTek Computer                      | 2        | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.11%   |
| Xiaomi                                | 1        | 0.05%   |
| Texas Instruments                     | 1        | 0.05%   |
| Samsung Electronics                   | 1        | 0.05%   |
| Philips (or NXP)                      | 1        | 0.05%   |
| NetGear                               | 1        | 0.05%   |
| Accton Technology                     | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 193      | 10.29%  |
| Qualcomm Atheros AR9271 802.11n                                | 100      | 5.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 91       | 4.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 83       | 4.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 75       | 4%      |
| Ralink RT5370 Wireless Adapter                                 | 72       | 3.84%   |
| Intel Wi-Fi 6 AX200                                            | 62       | 3.31%   |
| Realtek 802.11ac NIC                                           | 46       | 2.45%   |
| Microsoft Xbox 360 Wireless Adapter                            | 42       | 2.24%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 40       | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 35       | 1.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 32       | 1.71%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 31       | 1.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 30       | 1.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 29       | 1.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 28       | 1.49%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 27       | 1.44%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 26       | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 24       | 1.28%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 24       | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 22       | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 21       | 1.12%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 21       | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 20       | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19       | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 18       | 0.96%   |
| Intel Wireless-AC 9260                                         | 18       | 0.96%   |
| Intel Wireless 7260                                            | 18       | 0.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 18       | 0.96%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 17       | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 15       | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 15       | 0.8%    |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 15       | 0.8%    |
| Ralink RT2561/RT61 rev B 802.11g                               | 14       | 0.75%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 13       | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13       | 0.69%   |
| Intel Wireless 7265                                            | 13       | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 12       | 0.64%   |
| Ralink RT2070 Wireless Adapter                                 | 11       | 0.59%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 11       | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3308     | 65.82%  |
| Intel                             | 784      | 15.6%   |
| Qualcomm Atheros                  | 314      | 6.25%   |
| Nvidia                            | 191      | 3.8%    |
| Broadcom                          | 117      | 2.33%   |
| Samsung Electronics               | 48       | 0.96%   |
| VIA Technologies                  | 46       | 0.92%   |
| Marvell Technology Group          | 37       | 0.74%   |
| Xiaomi                            | 28       | 0.56%   |
| Broadcom Limited                  | 26       | 0.52%   |
| JMicron Technology                | 23       | 0.46%   |
| Motorola PCS                      | 13       | 0.26%   |
| D-Link System                     | 11       | 0.22%   |
| ASIX Electronics                  | 10       | 0.2%    |
| MediaTek                          | 7        | 0.14%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.12%   |
| ICS Advent                        | 6        | 0.12%   |
| DisplayLink                       | 5        | 0.1%    |
| 3Com                              | 5        | 0.1%    |
| TP-Link                           | 4        | 0.08%   |
| Sundance Technology Inc / IC Plus | 4        | 0.08%   |
| Huawei Technologies               | 4        | 0.08%   |
| Qualcomm                          | 3        | 0.06%   |
| LG Electronics                    | 3        | 0.06%   |
| Hangzhou Silan Microelectronics   | 3        | 0.06%   |
| ASUSTek Computer                  | 3        | 0.06%   |
| Accton Technology                 | 3        | 0.06%   |
| T & A Mobile Phones               | 2        | 0.04%   |
| OPPO Electronics                  | 2        | 0.04%   |
| Aquantia                          | 2        | 0.04%   |
| Apple                             | 2        | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.02%   |
| Spreadtrum Communications         | 1        | 0.02%   |
| SK hynix                          | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| AMD                               | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2685     | 52.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 456      | 8.9%    |
| Nvidia MCP61 Ethernet                                             | 163      | 3.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 98       | 1.91%   |
| Intel Ethernet Connection (2) I219-V                              | 93       | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 90       | 1.76%   |
| Intel I211 Gigabit Network Connection                             | 83       | 1.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 81       | 1.58%   |
| Intel Ethernet Connection (7) I219-V                              | 81       | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 70       | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 65       | 1.27%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 50       | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 49       | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 48       | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 43       | 0.84%   |
| Intel 82578DC Gigabit Network Connection                          | 40       | 0.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 36       | 0.7%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 36       | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 35       | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 33       | 0.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 29       | 0.57%   |
| Intel 82578DM Gigabit Network Connection                          | 26       | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24       | 0.47%   |
| Intel Ethernet Controller I225-V                                  | 24       | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23       | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 21       | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21       | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 20       | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19       | 0.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17       | 0.33%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 17       | 0.33%   |
| Intel Ethernet Connection (12) I219-V                             | 16       | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 16       | 0.31%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 15       | 0.29%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 13       | 0.25%   |
| Motorola PCS XT1032                                               | 13       | 0.25%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 13       | 0.25%   |
| Intel 82574L Gigabit Network Connection                           | 13       | 0.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12       | 0.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4750     | 72.5%   |
| WiFi     | 1742     | 26.59%  |
| Modem    | 49       | 0.75%   |
| Unknown  | 11       | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3805     | 76.79%  |
| WiFi     | 1147     | 23.15%  |
| Modem    | 2        | 0.04%   |
| Unknown  | 1        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3792     | 77.94%  |
| 2     | 920      | 18.91%  |
| 0     | 76       | 1.56%   |
| 3     | 68       | 1.4%    |
| 4     | 7        | 0.14%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3796     | 76.62%  |
| Yes  | 1158     | 23.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 439      | 50.99%  |
| Intel                           | 175      | 20.33%  |
| Realtek Semiconductor           | 77       | 8.94%   |
| Qualcomm Atheros Communications | 65       | 7.55%   |
| Broadcom                        | 20       | 2.32%   |
| ASUSTek Computer                | 19       | 2.21%   |
| MediaTek                        | 15       | 1.74%   |
| Apple                           | 11       | 1.28%   |
| IMC Networks                    | 8        | 0.93%   |
| Integrated System Solution      | 7        | 0.81%   |
| ISSC                            | 4        | 0.46%   |
| Actions                         | 4        | 0.46%   |
| Foxconn / Hon Hai               | 3        | 0.35%   |
| Conwise Technology              | 3        | 0.35%   |
| Unknown                         | 3        | 0.35%   |
| Micro Star International        | 2        | 0.23%   |
| SINO WEALTH                     | 1        | 0.12%   |
| Realtek                         | 1        | 0.12%   |
| Ralink                          | 1        | 0.12%   |
| Qcom                            | 1        | 0.12%   |
| Motorola PCS                    | 1        | 0.12%   |
| D-Link                          | 1        | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 439      | 50.87%  |
| Realtek Bluetooth Radio                               | 70       | 8.11%   |
| Intel AX200 Bluetooth                                 | 55       | 6.37%   |
| Intel Bluetooth wireless interface                    | 51       | 5.91%   |
| Qualcomm Atheros  Bluetooth Device                    | 28       | 3.24%   |
| Intel AX210 Bluetooth                                 | 19       | 2.2%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 18       | 2.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 18       | 2.09%   |
| MediaTek Wireless_Device                              | 15       | 1.74%   |
| Intel Wireless-AC 3168 Bluetooth                      | 15       | 1.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 10       | 1.16%   |
| Apple Bluetooth USB Host Controller                   | 10       | 1.16%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 6        | 0.7%    |
| Intel AX201 Bluetooth                                 | 6        | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 5        | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 5        | 0.58%   |
| ASUS Bluetooth Radio                                  | 5        | 0.58%   |
| Realtek Bluetooth 5.1 Radio                           | 4        | 0.46%   |
| ISSC Bluetooth Device                                 | 4        | 0.46%   |
| Integrated System Solution Bluetooth Device           | 4        | 0.46%   |
| IMC Networks Bluetooth Radio                          | 4        | 0.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 0.46%   |
| ASUS Bluetooth Adapter                                | 4        | 0.46%   |
| Actions general adapter                               | 4        | 0.46%   |
| Qualcomm Atheros Bluetooth                            | 3        | 0.35%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.35%   |
| IMC Networks Wireless_Device                          | 3        | 0.35%   |
| Conwise CW6622                                        | 3        | 0.35%   |
| Broadcom Bluetooth Controller                         | 3        | 0.35%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 3        | 0.35%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3        | 0.35%   |
| Unknown                                               | 3        | 0.35%   |
| Micro Star International Bluetooth Device             | 2        | 0.23%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 0.23%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle    | 2        | 0.23%   |
| Broadcom BCM2210 Bluetooth                            | 2        | 0.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 0.23%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.23%   |
| ASUS BCM20702A0                                       | 2        | 0.23%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1        | 0.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 3133     | 42.66%  |
| AMD                                             | 1830     | 24.92%  |
| Nvidia                                          | 1554     | 21.16%  |
| C-Media Electronics                             | 189      | 2.57%   |
| Generalplus Technology                          | 85       | 1.16%   |
| VIA Technologies                                | 53       | 0.72%   |
| Logitech                                        | 51       | 0.69%   |
| JMTek                                           | 50       | 0.68%   |
| Creative Labs                                   | 40       | 0.54%   |
| Kingston Technology                             | 35       | 0.48%   |
| Texas Instruments                               | 32       | 0.44%   |
| Corsair                                         | 19       | 0.26%   |
| Microsoft                                       | 17       | 0.23%   |
| Tenx Technology                                 | 13       | 0.18%   |
| Razer USA                                       | 13       | 0.18%   |
| BEHRINGER International                         | 13       | 0.18%   |
| Plantronics                                     | 10       | 0.14%   |
| Licensed by Sony Computer Entertainment America | 10       | 0.14%   |
| Sony                                            | 8        | 0.11%   |
| Goldvish                                        | 8        | 0.11%   |
| GN Netcom                                       | 8        | 0.11%   |
| Silicon Integrated Systems [SiS]                | 7        | 0.1%    |
| Fry's Electronics                               | 7        | 0.1%    |
| M-Audio                                         | 6        | 0.08%   |
| Creative Technology                             | 6        | 0.08%   |
| ASUSTek Computer                                | 6        | 0.08%   |
| Philips (or NXP)                                | 5        | 0.07%   |
| KTMicro                                         | 5        | 0.07%   |
| JBL                                             | 5        | 0.07%   |
| Focusrite-Novation                              | 5        | 0.07%   |
| fifine Microphones                              | 5        | 0.07%   |
| Dell                                            | 5        | 0.07%   |
| Cirrus Logic                                    | 5        | 0.07%   |
| BY EDIFIER                                      | 5        | 0.07%   |
| SteelSeries ApS                                 | 4        | 0.05%   |
| Samson Technologies                             | 4        | 0.05%   |
| Medeli Electronics                              | 4        | 0.05%   |
| Jieli Technology                                | 4        | 0.05%   |
| Elite Silicon                                   | 4        | 0.05%   |
| ATI Technologies                                | 4        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 694      | 8.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 591      | 6.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 420      | 4.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 370      | 4.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 302      | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 287      | 3.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 227      | 2.66%   |
| Nvidia High Definition Audio Controller                                           | 224      | 2.62%   |
| AMD Starship/Matisse HD Audio Controller                                          | 221      | 2.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 217      | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 203      | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 186      | 2.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 185      | 2.17%   |
| Nvidia MCP61 High Definition Audio                                                | 178      | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 175      | 2.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 152      | 1.78%   |
| Intel 200 Series PCH HD Audio                                                     | 151      | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 150      | 1.76%   |
| AMD FCH Azalia Controller                                                         | 146      | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                        | 139      | 1.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 124      | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 111      | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                     | 100      | 1.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 96       | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                     | 90       | 1.05%   |
| Generalplus Technology USB Audio Device                                           | 85       | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 79       | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 70       | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                     | 69       | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 63       | 0.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 58       | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                | 55       | 0.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 52       | 0.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 51       | 0.6%    |
| Nvidia GP104 High Definition Audio Controller                                     | 50       | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                                | 49       | 0.57%   |
| Nvidia GM206 High Definition Audio Controller                                     | 48       | 0.56%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 48       | 0.56%   |
| AMD Navi 10 HDMI Audio                                                            | 46       | 0.54%   |
| Intel Comet Lake PCH-V cAVS                                                       | 45       | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 664      | 28.55%  |
| Kingston            | 586      | 25.19%  |
| Corsair             | 175      | 7.52%   |
| Smart               | 146      | 6.28%   |
| Crucial             | 104      | 4.47%   |
| A-DATA Technology   | 84       | 3.61%   |
| Samsung Electronics | 70       | 3.01%   |
| SK hynix            | 61       | 2.62%   |
| Team                | 53       | 2.28%   |
| G.Skill             | 39       | 1.68%   |
| Unknown             | 37       | 1.59%   |
| Micron Technology   | 36       | 1.55%   |
| Teikon              | 27       | 1.16%   |
| Multilaser          | 24       | 1.03%   |
| Atermiter           | 16       | 0.69%   |
| Patriot             | 15       | 0.64%   |
| Apacer              | 12       | 0.52%   |
| Avant               | 10       | 0.43%   |
| Kreton              | 9        | 0.39%   |
| GeIL                | 9        | 0.39%   |
| Kllisre             | 8        | 0.34%   |
| CSX                 | 7        | 0.3%    |
| Asgard              | 7        | 0.3%    |
| RZX                 | 6        | 0.26%   |
| Nanya Technology    | 6        | 0.26%   |
| HBS                 | 6        | 0.26%   |
| Unknown (82B5)      | 5        | 0.21%   |
| Hewlett-Packard     | 5        | 0.21%   |
| GLOWAY              | 5        | 0.21%   |
| Elpida              | 5        | 0.21%   |
| Qbex                | 4        | 0.17%   |
| PUSKILL             | 4        | 0.17%   |
| Positivo            | 4        | 0.17%   |
| MemoWise            | 4        | 0.17%   |
| Kingmax             | 4        | 0.17%   |
| Transcend           | 3        | 0.13%   |
| Smart Modular       | 3        | 0.13%   |
| Juhor               | 3        | 0.13%   |
| Goldkey             | 3        | 0.13%   |
| AMD                 | 3        | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s     | 49       | 1.89%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 38       | 1.46%   |
| Unknown                                               | 37       | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 36       | 1.39%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s   | 33       | 1.27%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s     | 32       | 1.23%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 30       | 1.16%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 29       | 1.12%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 26       | 1%      |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 20       | 0.77%   |
| Unknown RAM Module 4GB DIMM SDRAM                     | 19       | 0.73%   |
| Unknown RAM Module 2GB DIMM DDR2                      | 19       | 0.73%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s   | 19       | 0.73%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 17       | 0.66%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 17       | 0.66%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s   | 17       | 0.66%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s          | 17       | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 15       | 0.58%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 15       | 0.58%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s | 14       | 0.54%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s | 14       | 0.54%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 13       | 0.5%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s    | 13       | 0.5%    |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s         | 13       | 0.5%    |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3            | 13       | 0.5%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s          | 12       | 0.46%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                | 12       | 0.46%   |
| Smart RAM SH564568FH8N0QHSCR 2GB DIMM DDR3 1333MT/s   | 12       | 0.46%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s  | 12       | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 11       | 0.42%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s   | 11       | 0.42%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s    | 11       | 0.42%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM 1333MT/s        | 11       | 0.42%   |
| Kingston RAM 99U5403-159.A01LF 8GB DIMM DDR3 1600MT/s | 11       | 0.42%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s          | 11       | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s             | 10       | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s             | 10       | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 10       | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 10       | 0.39%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s   | 10       | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 806      | 39.63%  |
| DDR4         | 687      | 33.78%  |
| Unknown      | 205      | 10.08%  |
| DDR2         | 152      | 7.47%   |
| SDRAM        | 136      | 6.69%   |
| DDR          | 34       | 1.67%   |
| DDR5         | 10       | 0.49%   |
| LPDDR4       | 2        | 0.1%    |
| DRAM         | 1        | 0.05%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1922     | 95.62%  |
| SODIMM       | 81       | 4.03%   |
| RIMM         | 4        | 0.2%    |
| FB-DIMM      | 2        | 0.1%    |
| Row Of Chips | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 743      | 32.66%  |
| 8192  | 728      | 32%     |
| 2048  | 451      | 19.82%  |
| 16384 | 187      | 8.22%   |
| 1024  | 78       | 3.43%   |
| 32768 | 71       | 3.12%   |
| 512   | 12       | 0.53%   |
| 256   | 3        | 0.13%   |
| 1536  | 1        | 0.04%   |
| 16    | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 437      | 19.3%   |
| 1600    | 400      | 17.67%  |
| Unknown | 178      | 7.86%   |
| 2400    | 142      | 6.27%   |
| 800     | 106      | 4.68%   |
| 667     | 97       | 4.28%   |
| 2667    | 95       | 4.2%    |
| 3200    | 87       | 3.84%   |
| 3600    | 73       | 3.22%   |
| 3000    | 70       | 3.09%   |
| 2133    | 67       | 2.96%   |
| 3400    | 63       | 2.78%   |
| 1867    | 41       | 1.81%   |
| 3466    | 36       | 1.59%   |
| 1866    | 35       | 1.55%   |
| 2800    | 31       | 1.37%   |
| 1066    | 27       | 1.19%   |
| 2933    | 25       | 1.1%    |
| 2666    | 22       | 0.97%   |
| 1067    | 21       | 0.93%   |
| 400     | 20       | 0.88%   |
| 3733    | 18       | 0.8%    |
| 3151    | 17       | 0.75%   |
| 3800    | 16       | 0.71%   |
| 333     | 16       | 0.71%   |
| 533     | 15       | 0.66%   |
| 1334    | 10       | 0.44%   |
| 3334    | 9        | 0.4%    |
| 1800    | 7        | 0.31%   |
| 3333    | 6        | 0.27%   |
| 41632   | 4        | 0.18%   |
| 4800    | 4        | 0.18%   |
| 3933    | 4        | 0.18%   |
| 2448    | 4        | 0.18%   |
| 6000    | 3        | 0.13%   |
| 5354    | 3        | 0.13%   |
| 3066    | 3        | 0.13%   |
| 2733    | 3        | 0.13%   |
| 2132    | 3        | 0.13%   |
| 49926   | 2        | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 96       | 45.28%  |
| Seiko Epson           | 56       | 26.42%  |
| Samsung Electronics   | 19       | 8.96%   |
| Canon                 | 15       | 7.08%   |
| Brother Industries    | 15       | 7.08%   |
| Lexmark International | 3        | 1.42%   |
| QinHeng Electronics   | 2        | 0.94%   |
| Apple                 | 2        | 0.94%   |
| Ricoh                 | 1        | 0.47%   |
| Prolific Technology   | 1        | 0.47%   |
| Oki Data              | 1        | 0.47%   |
| ARGOX                 | 1        | 0.47%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson L396 Series                      | 9        | 4.19%   |
| Seiko Epson L365 Series                      | 8        | 3.72%   |
| HP DeskJet 2130 series                       | 8        | 3.72%   |
| Seiko Epson ET-2710 Series                   | 7        | 3.26%   |
| HP Ink Tank Wireless 410 series              | 7        | 3.26%   |
| Seiko Epson L355 Series                      | 6        | 2.79%   |
| Canon G3010 series                           | 6        | 2.79%   |
| Samsung M2070 Series                         | 5        | 2.33%   |
| HP DeskJet F4100 Printer series              | 5        | 2.33%   |
| HP Deskjet 3050 J610 series                  | 5        | 2.33%   |
| HP DeskJet 2700 series                       | 5        | 2.33%   |
| HP Deskjet 2540 series                       | 5        | 2.33%   |
| HP Deskjet 2050 J510                         | 5        | 2.33%   |
| Samsung SCX-4200 series                      | 4        | 1.86%   |
| HP LaserJet P1005                            | 4        | 1.86%   |
| HP DeskJet 2620 All-in-One Printer           | 4        | 1.86%   |
| Seiko Epson XP-240 Series                    | 3        | 1.4%    |
| Seiko Epson L375 Series                      | 3        | 1.4%    |
| Seiko Epson L360 Series                      | 3        | 1.4%    |
| Seiko Epson L3110 Series                     | 3        | 1.4%    |
| Samsung SCX-3200 Series                      | 3        | 1.4%    |
| HP LaserJet Professional P1102w              | 3        | 1.4%    |
| HP LaserJet 1020                             | 3        | 1.4%    |
| HP Deskjet F4400 series                      | 3        | 1.4%    |
| HP DeskJet F4200 series                      | 3        | 1.4%    |
| HP DeskJet 3630 series                       | 3        | 1.4%    |
| Brother HL-1200 series                       | 3        | 1.4%    |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 2        | 0.93%   |
| Seiko Epson L3250 Series                     | 2        | 0.93%   |
| Seiko Epson L210 Series                      | 2        | 0.93%   |
| Seiko Epson L120 Series                      | 2        | 0.93%   |
| Samsung SCX-3400 Series                      | 2        | 0.93%   |
| Samsung M2020 Series                         | 2        | 0.93%   |
| QinHeng CH340S                               | 2        | 0.93%   |
| HP PSC-1315/PSC-1317                         | 2        | 0.93%   |
| HP Printing Support                          | 2        | 0.93%   |
| HP LaserJet 1018                             | 2        | 0.93%   |
| HP Deskjet 4620 series                       | 2        | 0.93%   |
| HP DeskJet 1110 series                       | 2        | 0.93%   |
| Canon PIXMA MG3000 series                    | 2        | 0.93%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 6        | 40%     |
| Canon           | 6        | 40%     |
| Seiko Epson     | 2        | 13.33%  |
| Mustek Systems  | 1        | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                        | 4        | 26.67%  |
| Canon CanoScan LIDE 25                                  | 4        | 26.67%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 6.67%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 6.67%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 6.67%   |
| HP ScanJet G4050                                        | 1        | 6.67%   |
| HP ScanJet 3800c                                        | 1        | 6.67%   |
| Canon CanoScan LiDE 210                                 | 1        | 6.67%   |
| Canon CanoScan LiDE 110                                 | 1        | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 228      | 30.73%  |
| Generalplus Technology        | 59       | 7.95%   |
| Microsoft                     | 50       | 6.74%   |
| Microdia                      | 44       | 5.93%   |
| Samsung Electronics           | 41       | 5.53%   |
| Z-Star Microelectronics       | 37       | 4.99%   |
| Aveo Technology               | 28       | 3.77%   |
| GEMBIRD                       | 21       | 2.83%   |
| Jieli Technology              | 17       | 2.29%   |
| Chicony Electronics           | 17       | 2.29%   |
| Cubeternet                    | 16       | 2.16%   |
| Sunplus Innovation Technology | 15       | 2.02%   |
| Pixart Imaging                | 11       | 1.48%   |
| Apple                         | 10       | 1.35%   |
| LG Electronics                | 9        | 1.21%   |
| Genesys Logic                 | 8        | 1.08%   |
| Alcor Micro                   | 8        | 1.08%   |
| KYE Systems (Mouse Systems)   | 7        | 0.94%   |
| Arkmicro Technologies         | 7        | 0.94%   |
| Philips (or NXP)              | 6        | 0.81%   |
| MacroSilicon                  | 6        | 0.81%   |
| Hewlett-Packard               | 6        | 0.81%   |
| Bison Electronics             | 6        | 0.81%   |
| Realtek Semiconductor         | 5        | 0.67%   |
| Huawei Technologies           | 5        | 0.67%   |
| SunplusIT                     | 4        | 0.54%   |
| Sunplus Technology            | 4        | 0.54%   |
| Sonix Technology              | 4        | 0.54%   |
| Lenovo                        | 4        | 0.54%   |
| Asuscom Network               | 4        | 0.54%   |
| A4Tech                        | 4        | 0.54%   |
| Silicon Motion                | 3        | 0.4%    |
| IMC Networks                  | 3        | 0.4%    |
| GenesysLogic Technology       | 3        | 0.4%    |
| Creative Technology           | 3        | 0.4%    |
| ARC International             | 3        | 0.4%    |
| ALi                           | 3        | 0.4%    |
| Xiongmai                      | 2        | 0.27%   |
| WCM_USB                       | 2        | 0.27%   |
| WaveRider Communications      | 2        | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 85       | 11.41%  |
| Logitech HD Pro Webcam C920              | 50       | 6.71%   |
| Generalplus GENERAL WEBCAM               | 41       | 5.5%    |
| Samsung Galaxy series, misc. (MTP mode)  | 40       | 5.37%   |
| Logitech C922 Pro Stream Webcam          | 23       | 3.09%   |
| GEMBIRD USB2.0 PC CAMERA                 | 19       | 2.55%   |
| Jieli USB PHY 2.0                        | 17       | 2.28%   |
| Z-Star Venus USB2.0 Camera               | 15       | 2.01%   |
| Logitech BRIO Ultra HD Webcam            | 14       | 1.88%   |
| Generalplus 808 Camera #9 (web-cam mode) | 14       | 1.88%   |
| Aveo USB2.0 Camera                       | 14       | 1.88%   |
| Microdia Integrated Camera               | 13       | 1.74%   |
| Microdia USB 2.0 Camera                  | 11       | 1.48%   |
| Logitech HD Webcam C525                  | 11       | 1.48%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 10       | 1.34%   |
| Microsoft LifeCam VX-500 [1357]          | 10       | 1.34%   |
| Logitech Webcam C925e                    | 10       | 1.34%   |
| Logitech C920 PRO HD Webcam              | 10       | 1.34%   |
| Microsoft LifeCam VX-800                 | 9        | 1.21%   |
| Z-Star Vimicro USB Camera (Altair)       | 8        | 1.07%   |
| Sunplus 1080P Webcam                     | 8        | 1.07%   |
| Microsoft LifeCam HD-3000                | 8        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 8        | 1.07%   |
| Microsoft LifeCam VX-2000                | 7        | 0.94%   |
| Microdia Webcam Vitade AF                | 7        | 0.94%   |
| Chicony HP Webcam                        | 7        | 0.94%   |
| Aveo Camera                              | 7        | 0.94%   |
| Philips (or NXP) Webcam SPC530NC         | 6        | 0.81%   |
| Microsoft LifeCam HD-5000                | 6        | 0.81%   |
| Microsoft LifeCam Cinema                 | 6        | 0.81%   |
| Logitech Logi Webcam C920e               | 6        | 0.81%   |
| Cubeternet GL-UPC822 UVC WebCam          | 6        | 0.81%   |
| Bison BisonCam, NB Pro                   | 6        | 0.81%   |
| Microdia Sonix USB 2.0 Camera            | 5        | 0.67%   |
| MacroSilicon USB Video                   | 5        | 0.67%   |
| Huawei HiCamera                          | 5        | 0.67%   |
| Chicony HP High Definition 1MP Webcam    | 5        | 0.67%   |
| Aveo UVC camera (Bresser microscope)     | 5        | 0.67%   |
| Z-Star Vimicro USB Camera (Phosphor)     | 4        | 0.54%   |
| SunplusIT HBT Camera                     | 4        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 33.33%  |
| Futronic Technology   | 1        | 33.33%  |
| Dell                  | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor                  | 1        | 33.33%  |
| Futronic FS81 Fingerprint Scanner Module       | 1        | 33.33%  |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 15       | 38.46%  |
| Giesecke & Devrient               | 5        | 12.82%  |
| Alcor Micro                       | 4        | 10.26%  |
| SCM Microsystems                  | 3        | 7.69%   |
| Chicony Electronics               | 3        | 7.69%   |
| Watchdata                         | 2        | 5.13%   |
| OmniKey                           | 2        | 5.13%   |
| Castles Technology                | 2        | 5.13%   |
| VASCO Data Security International | 1        | 2.56%   |
| Realtek Semiconductor             | 1        | 2.56%   |
| Aladdin Knowledge Systems         | 1        | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 14       | 35.9%   |
| Giesecke & Devrient StarSign CUT S                              | 4        | 10.26%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 10.26%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 3        | 7.69%   |
| Watchdata USB Key                                               | 2        | 5.13%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 2        | 5.13%   |
| OmniKey CardMan 3021 / 3121                                     | 2        | 5.13%   |
| Castles Technology EZCCID Smart Card Reader                     | 2        | 5.13%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 2.56%   |
| SCM Microsystems SCR35xx Smart Card Reader                      | 1        | 2.56%   |
| Realtek Semiconductor Smart Card Reader Interface               | 1        | 2.56%   |
| Giesecke & Devrient StarSign CUT                                | 1        | 2.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                | 1        | 2.56%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4199     | 85.41%  |
| 1     | 635      | 12.92%  |
| 2     | 58       | 1.18%   |
| 3     | 15       | 0.31%   |
| 4     | 8        | 0.16%   |
| 6     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 295      | 37.58%  |
| Net/wireless             | 207      | 26.37%  |
| Communication controller | 58       | 7.39%   |
| Unassigned class         | 53       | 6.75%   |
| Sound                    | 28       | 3.57%   |
| Multimedia controller    | 28       | 3.57%   |
| Chipcard                 | 26       | 3.31%   |
| Camera                   | 18       | 2.29%   |
| Modem                    | 17       | 2.17%   |
| Net/ethernet             | 12       | 1.53%   |
| Bluetooth                | 9        | 1.15%   |
| Storage/ide              | 8        | 1.02%   |
| Network                  | 7        | 0.89%   |
| Storage/raid             | 5        | 0.64%   |
| Card reader              | 5        | 0.64%   |
| Storage/nvme             | 2        | 0.25%   |
| Firewire controller      | 2        | 0.25%   |
| Wireless                 | 1        | 0.13%   |
| Video                    | 1        | 0.13%   |
| Storage                  | 1        | 0.13%   |
| Fingerprint reader       | 1        | 0.13%   |
| Dvb card                 | 1        | 0.13%   |

