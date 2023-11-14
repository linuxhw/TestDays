ALT Linux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ALT Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ALT_Linux/Desktop/README.md) and [notebooks](/Dist/ALT_Linux/Notebook/README.md).

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

Total: 884

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Aquarius      | AQX300M                     | Desktop     | [b70a012245](https://linux-hardware.org/?probe=b70a012245) | Nov 01, 2023 |
| Dell          | Inspiron N5050              | Notebook    | [2ec8097b67](https://linux-hardware.org/?probe=2ec8097b67) | Oct 31, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [d7dd5dbdf7](https://linux-hardware.org/?probe=d7dd5dbdf7) | Oct 30, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [bcc4e567f3](https://linux-hardware.org/?probe=bcc4e567f3) | Oct 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [63c6987bfa](https://linux-hardware.org/?probe=63c6987bfa) | Oct 28, 2023 |
| Huanan        | X99-T8 GAMING V2.0          | Desktop     | [27d22c45c8](https://linux-hardware.org/?probe=27d22c45c8) | Oct 26, 2023 |
| Acer          | Ferrari 3200                | Notebook    | [52f9e06bf9](https://linux-hardware.org/?probe=52f9e06bf9) | Oct 25, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f8f7f85d08](https://linux-hardware.org/?probe=f8f7f85d08) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [d0e546f6d6](https://linux-hardware.org/?probe=d0e546f6d6) | Oct 25, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [178fe3a497](https://linux-hardware.org/?probe=178fe3a497) | Oct 25, 2023 |
| HONOR         | NMH-WDX9                    | Notebook    | [3a0782c335](https://linux-hardware.org/?probe=3a0782c335) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | Notebook    | [1b58a52442](https://linux-hardware.org/?probe=1b58a52442) | Oct 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [1e239308b1](https://linux-hardware.org/?probe=1e239308b1) | Oct 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [125d0eedc8](https://linux-hardware.org/?probe=125d0eedc8) | Oct 21, 2023 |
| HP            | 255 G4                      | Notebook    | [0290beac3f](https://linux-hardware.org/?probe=0290beac3f) | Oct 19, 2023 |
| AZW           | MINI S                      | Desktop     | [0083fabd4c](https://linux-hardware.org/?probe=0083fabd4c) | Oct 15, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [901cc6bd8a](https://linux-hardware.org/?probe=901cc6bd8a) | Oct 14, 2023 |
| Biostar       | H510MHP                     | Desktop     | [1de1d57c17](https://linux-hardware.org/?probe=1de1d57c17) | Oct 13, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [d6cf338b8c](https://linux-hardware.org/?probe=d6cf338b8c) | Oct 12, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [b809251676](https://linux-hardware.org/?probe=b809251676) | Oct 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [52694348d2](https://linux-hardware.org/?probe=52694348d2) | Oct 10, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [7f32c31118](https://linux-hardware.org/?probe=7f32c31118) | Oct 09, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [7623527bdb](https://linux-hardware.org/?probe=7623527bdb) | Oct 08, 2023 |
| ROMBICA       | myBook Eclipse              | Notebook    | [d56fec4995](https://linux-hardware.org/?probe=d56fec4995) | Oct 07, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [1bbe75aa56](https://linux-hardware.org/?probe=1bbe75aa56) | Oct 04, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [61278c0720](https://linux-hardware.org/?probe=61278c0720) | Oct 04, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [06499eec7c](https://linux-hardware.org/?probe=06499eec7c) | Oct 04, 2023 |
| F-PLUS EQU... | Unknown                     | Notebook    | [104a5f30e4](https://linux-hardware.org/?probe=104a5f30e4) | Oct 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [90cb02d71d](https://linux-hardware.org/?probe=90cb02d71d) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | Notebook    | [aa9a99ccb5](https://linux-hardware.org/?probe=aa9a99ccb5) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | Notebook    | [200217831d](https://linux-hardware.org/?probe=200217831d) | Oct 04, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [38db8e9cf2](https://linux-hardware.org/?probe=38db8e9cf2) | Oct 04, 2023 |
| Lenovo        | G700                        | Notebook    | [7090569f96](https://linux-hardware.org/?probe=7090569f96) | Oct 03, 2023 |
| HIPER         | WORKBOOK                    | Notebook    | [902f508256](https://linux-hardware.org/?probe=902f508256) | Oct 03, 2023 |
| Biostar       | H510MHP                     | Desktop     | [1d6b309a9a](https://linux-hardware.org/?probe=1d6b309a9a) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [b2a213cc18](https://linux-hardware.org/?probe=b2a213cc18) | Sep 30, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [60e32143f5](https://linux-hardware.org/?probe=60e32143f5) | Sep 29, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7cc521d927](https://linux-hardware.org/?probe=7cc521d927) | Sep 29, 2023 |
| ROMBICA       | myBook Eclipse              | Notebook    | [004e1dc4fd](https://linux-hardware.org/?probe=004e1dc4fd) | Sep 28, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [2ac0204275](https://linux-hardware.org/?probe=2ac0204275) | Sep 28, 2023 |
| Pegatron      | IPMSB-H61                   | Desktop     | [d0e64d2ebf](https://linux-hardware.org/?probe=d0e64d2ebf) | Sep 28, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1458dfe403](https://linux-hardware.org/?probe=1458dfe403) | Sep 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [8b0d086b89](https://linux-hardware.org/?probe=8b0d086b89) | Sep 27, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [45d07666f9](https://linux-hardware.org/?probe=45d07666f9) | Sep 26, 2023 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [a0fa16f85c](https://linux-hardware.org/?probe=a0fa16f85c) | Sep 25, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [df4d5654d5](https://linux-hardware.org/?probe=df4d5654d5) | Sep 21, 2023 |
| iRU           | 17ALC                       | Notebook    | [2d0b23c813](https://linux-hardware.org/?probe=2d0b23c813) | Sep 18, 2023 |
| Lenovo        | ThinkPad X250 20CMS0A200    | Notebook    | [43df4bd3f3](https://linux-hardware.org/?probe=43df4bd3f3) | Sep 18, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [5e6499e724](https://linux-hardware.org/?probe=5e6499e724) | Sep 17, 2023 |
| HP            | 85A2                        | All in one  | [f1a642ea93](https://linux-hardware.org/?probe=f1a642ea93) | Sep 14, 2023 |
| ASRock        | K10N78D                     | Desktop     | [fa2852026b](https://linux-hardware.org/?probe=fa2852026b) | Sep 13, 2023 |
| ASRock        | K10N78D                     | Desktop     | [adf8e09915](https://linux-hardware.org/?probe=adf8e09915) | Sep 13, 2023 |
| on Gravito... | Graviton M42i               | All in one  | [3d738e533d](https://linux-hardware.org/?probe=3d738e533d) | Sep 12, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [53cdc3e4f0](https://linux-hardware.org/?probe=53cdc3e4f0) | Sep 12, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [5e87de3be1](https://linux-hardware.org/?probe=5e87de3be1) | Sep 11, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [d83ba68fcb](https://linux-hardware.org/?probe=d83ba68fcb) | Sep 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| ASUSTek       | V221IC                      | All in one  | [1abad6ed2e](https://linux-hardware.org/?probe=1abad6ed2e) | Sep 03, 2023 |
| ASUSTek       | V221IC                      | All in one  | [06240bab5b](https://linux-hardware.org/?probe=06240bab5b) | Sep 03, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6b33c9cb36](https://linux-hardware.org/?probe=6b33c9cb36) | Sep 02, 2023 |
| Intel         | B75                         | Desktop     | [55695d0962](https://linux-hardware.org/?probe=55695d0962) | Aug 31, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [861e741d6a](https://linux-hardware.org/?probe=861e741d6a) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [09ed405682](https://linux-hardware.org/?probe=09ed405682) | Aug 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [59cfa4ea58](https://linux-hardware.org/?probe=59cfa4ea58) | Aug 29, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [ad478d48ad](https://linux-hardware.org/?probe=ad478d48ad) | Aug 27, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [dfc1f52af5](https://linux-hardware.org/?probe=dfc1f52af5) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1510eba46f](https://linux-hardware.org/?probe=1510eba46f) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [cc7efa7eba](https://linux-hardware.org/?probe=cc7efa7eba) | Aug 11, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [18ace46778](https://linux-hardware.org/?probe=18ace46778) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a43111576a](https://linux-hardware.org/?probe=a43111576a) | Aug 09, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [4b7e9a8b93](https://linux-hardware.org/?probe=4b7e9a8b93) | Aug 09, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [71b00682fc](https://linux-hardware.org/?probe=71b00682fc) | Aug 07, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [baf3a83d91](https://linux-hardware.org/?probe=baf3a83d91) | Aug 06, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [163708151e](https://linux-hardware.org/?probe=163708151e) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [28007801d5](https://linux-hardware.org/?probe=28007801d5) | Aug 03, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [5e3a46dee8](https://linux-hardware.org/?probe=5e3a46dee8) | Aug 03, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [c12e9ed368](https://linux-hardware.org/?probe=c12e9ed368) | Aug 02, 2023 |
| ASUSTek       | P7F-M                       | Desktop     | [5c04bf12d0](https://linux-hardware.org/?probe=5c04bf12d0) | Aug 02, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [1096cf2959](https://linux-hardware.org/?probe=1096cf2959) | Jul 31, 2023 |
| HP            | 0AA8h                       | Desktop     | [76dbb0d0a3](https://linux-hardware.org/?probe=76dbb0d0a3) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | Notebook    | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| ASRock        | G41M-VS2                    | Desktop     | [74564d3418](https://linux-hardware.org/?probe=74564d3418) | Jul 28, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [543257c1b1](https://linux-hardware.org/?probe=543257c1b1) | Jul 25, 2023 |
| INSYS         | IP1-XN23                    | Notebook    | [4212432f00](https://linux-hardware.org/?probe=4212432f00) | Jul 24, 2023 |
| ASUSTek       | X55A                        | Notebook    | [6818ec7338](https://linux-hardware.org/?probe=6818ec7338) | Jul 21, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [6284551b74](https://linux-hardware.org/?probe=6284551b74) | Jul 20, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [4b683fcc22](https://linux-hardware.org/?probe=4b683fcc22) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [0cf82c02d3](https://linux-hardware.org/?probe=0cf82c02d3) | Jul 18, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [da27044389](https://linux-hardware.org/?probe=da27044389) | Jul 17, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [a24026d3c6](https://linux-hardware.org/?probe=a24026d3c6) | Jul 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Graviton      | N15I-T                      | Notebook    | [b457883ad3](https://linux-hardware.org/?probe=b457883ad3) | Jul 04, 2023 |
| Graviton      | N15I-T                      | Notebook    | [305390c16e](https://linux-hardware.org/?probe=305390c16e) | Jul 03, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [2d91c7c05a](https://linux-hardware.org/?probe=2d91c7c05a) | Jun 28, 2023 |
| Gigabyte      | MRHM3AP                     | Desktop     | [7007bb2db5](https://linux-hardware.org/?probe=7007bb2db5) | Jun 27, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [a2dbae939a](https://linux-hardware.org/?probe=a2dbae939a) | Jun 27, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [1f7adfe250](https://linux-hardware.org/?probe=1f7adfe250) | Jun 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [91bb626fa8](https://linux-hardware.org/?probe=91bb626fa8) | Jun 26, 2023 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [929fce049c](https://linux-hardware.org/?probe=929fce049c) | Jun 26, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| ASUSTek       | V221IC                      | All in one  | [c54f07785e](https://linux-hardware.org/?probe=c54f07785e) | Jun 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c4198042a](https://linux-hardware.org/?probe=0c4198042a) | Jun 18, 2023 |
| Alienware     | M14xR2                      | Notebook    | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
| Biostar       | H610MH                      | Desktop     | [a2c82f65b6](https://linux-hardware.org/?probe=a2c82f65b6) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [5a66eed08e](https://linux-hardware.org/?probe=5a66eed08e) | Jun 05, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| HP            | Mini 210-1000               | Notebook    | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| ICL           | RAYbook Si1407              | Notebook    | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Timi          | TM1701                      | Notebook    | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [e34e6ab643](https://linux-hardware.org/?probe=e34e6ab643) | May 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [91ad90fd67](https://linux-hardware.org/?probe=91ad90fd67) | May 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9c184f4251](https://linux-hardware.org/?probe=9c184f4251) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [1bfbf34771](https://linux-hardware.org/?probe=1bfbf34771) | May 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d9cac69c4c](https://linux-hardware.org/?probe=d9cac69c4c) | May 16, 2023 |
| HP            | 8374 1100                   | All in one  | [2e31c0e1d5](https://linux-hardware.org/?probe=2e31c0e1d5) | May 12, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [0959f95f56](https://linux-hardware.org/?probe=0959f95f56) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [b502077711](https://linux-hardware.org/?probe=b502077711) | May 12, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ab733d41de](https://linux-hardware.org/?probe=ab733d41de) | May 12, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [dea48fc3fa](https://linux-hardware.org/?probe=dea48fc3fa) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [f0fbd1eda9](https://linux-hardware.org/?probe=f0fbd1eda9) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [096f897a80](https://linux-hardware.org/?probe=096f897a80) | May 11, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [7a1acf3851](https://linux-hardware.org/?probe=7a1acf3851) | May 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [3c0893a822](https://linux-hardware.org/?probe=3c0893a822) | May 11, 2023 |
| DEPO Compu... | DPA520S                     | Desktop     | [848dc775e0](https://linux-hardware.org/?probe=848dc775e0) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [ce24dc022b](https://linux-hardware.org/?probe=ce24dc022b) | May 10, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [1d50da2ba5](https://linux-hardware.org/?probe=1d50da2ba5) | May 05, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [3ed55d530a](https://linux-hardware.org/?probe=3ed55d530a) | May 04, 2023 |
| F-PLUS EQU... | FNB-140-P1                  | Notebook    | [f78d6739f5](https://linux-hardware.org/?probe=f78d6739f5) | May 03, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [67b2580836](https://linux-hardware.org/?probe=67b2580836) | May 03, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [1ba45b2b8f](https://linux-hardware.org/?probe=1ba45b2b8f) | May 03, 2023 |
| HP            | 8374 1100                   | All in one  | [68015b73d0](https://linux-hardware.org/?probe=68015b73d0) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [2f1b310ca2](https://linux-hardware.org/?probe=2f1b310ca2) | Apr 21, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [a61ffc94f5](https://linux-hardware.org/?probe=a61ffc94f5) | Apr 18, 2023 |
| Unknown       | DMB-A520-MCA01              | Desktop     | [d0c1433d54](https://linux-hardware.org/?probe=d0c1433d54) | Apr 18, 2023 |
| Intel         | SKYBAY                      | Desktop     | [ec2b541d85](https://linux-hardware.org/?probe=ec2b541d85) | Apr 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [322f62ae77](https://linux-hardware.org/?probe=322f62ae77) | Apr 11, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [3504e8b3bd](https://linux-hardware.org/?probe=3504e8b3bd) | Apr 11, 2023 |
| Aquarius      | Cmp NS483                   | Convertible | [2a8ffe8e0d](https://linux-hardware.org/?probe=2a8ffe8e0d) | Apr 11, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [720eed31f6](https://linux-hardware.org/?probe=720eed31f6) | Apr 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [5fddb7053d](https://linux-hardware.org/?probe=5fddb7053d) | Apr 07, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [e734b33010](https://linux-hardware.org/?probe=e734b33010) | Apr 07, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [b0f85c7afd](https://linux-hardware.org/?probe=b0f85c7afd) | Apr 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [67615ec9ff](https://linux-hardware.org/?probe=67615ec9ff) | Apr 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bec5bda3bd](https://linux-hardware.org/?probe=bec5bda3bd) | Apr 05, 2023 |
| Timi          | TM1701                      | Notebook    | [5fc6e30961](https://linux-hardware.org/?probe=5fc6e30961) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [68a8171c0a](https://linux-hardware.org/?probe=68a8171c0a) | Mar 31, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [9ec66a8f48](https://linux-hardware.org/?probe=9ec66a8f48) | Mar 31, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [45162c9123](https://linux-hardware.org/?probe=45162c9123) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [c19cd604b3](https://linux-hardware.org/?probe=c19cd604b3) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | Notebook    | [fc942702db](https://linux-hardware.org/?probe=fc942702db) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | Notebook    | [ab5d4b339b](https://linux-hardware.org/?probe=ab5d4b339b) | Mar 30, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [69abc76758](https://linux-hardware.org/?probe=69abc76758) | Mar 29, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [9d7a43d81f](https://linux-hardware.org/?probe=9d7a43d81f) | Mar 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [60191a33b8](https://linux-hardware.org/?probe=60191a33b8) | Mar 27, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [b56bf816d5](https://linux-hardware.org/?probe=b56bf816d5) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [88a5d2eb30](https://linux-hardware.org/?probe=88a5d2eb30) | Mar 23, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [123e95cee1](https://linux-hardware.org/?probe=123e95cee1) | Mar 22, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [430f11129e](https://linux-hardware.org/?probe=430f11129e) | Mar 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5d06af8741](https://linux-hardware.org/?probe=5d06af8741) | Mar 22, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9fbef1354b](https://linux-hardware.org/?probe=9fbef1354b) | Mar 21, 2023 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [24b07c4402](https://linux-hardware.org/?probe=24b07c4402) | Mar 21, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [8e021e8177](https://linux-hardware.org/?probe=8e021e8177) | Mar 21, 2023 |
| Intel         | NUC7JYB M37329-601          | Mini pc     | [b9649aaa48](https://linux-hardware.org/?probe=b9649aaa48) | Mar 21, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [1b993725aa](https://linux-hardware.org/?probe=1b993725aa) | Mar 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [743d04e5fc](https://linux-hardware.org/?probe=743d04e5fc) | Mar 16, 2023 |
| Biostar       | TB250-BTC                   | Desktop     | [59d148cedc](https://linux-hardware.org/?probe=59d148cedc) | Mar 11, 2023 |
| Gigabyte      | 965GM-S2                    | Desktop     | [8a58676b8d](https://linux-hardware.org/?probe=8a58676b8d) | Mar 10, 2023 |
| Gigabyte      | 965GM-S2                    | Desktop     | [e514c2892e](https://linux-hardware.org/?probe=e514c2892e) | Mar 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9e620a10f2](https://linux-hardware.org/?probe=9e620a10f2) | Mar 09, 2023 |
| Intel         | SKYBAY                      | Desktop     | [226b8468d4](https://linux-hardware.org/?probe=226b8468d4) | Mar 09, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d62a6bc830](https://linux-hardware.org/?probe=d62a6bc830) | Mar 07, 2023 |
| DEPO Compu... | DPH410S                     | Desktop     | [5fb80da27b](https://linux-hardware.org/?probe=5fb80da27b) | Mar 07, 2023 |
| ICL           | H310SB-TM                   | All in one  | [63dbb9394e](https://linux-hardware.org/?probe=63dbb9394e) | Mar 07, 2023 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [4b3689dc5c](https://linux-hardware.org/?probe=4b3689dc5c) | Mar 05, 2023 |
| ICL           | H510SB-TM v2.0              | All in one  | [2e8dc3ddd2](https://linux-hardware.org/?probe=2e8dc3ddd2) | Mar 03, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [dcc115a880](https://linux-hardware.org/?probe=dcc115a880) | Mar 02, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [5ab1863f2b](https://linux-hardware.org/?probe=5ab1863f2b) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| MSI           | MS-7357                     | Desktop     | [84cadfbabc](https://linux-hardware.org/?probe=84cadfbabc) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [d7f1d6a937](https://linux-hardware.org/?probe=d7f1d6a937) | Feb 14, 2023 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [a9267dffac](https://linux-hardware.org/?probe=a9267dffac) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| ASUSTek       | P5B-E                       | Desktop     | [92bf62be3c](https://linux-hardware.org/?probe=92bf62be3c) | Feb 11, 2023 |
| Acer          | RS880M05                    | Desktop     | [c585589925](https://linux-hardware.org/?probe=c585589925) | Feb 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | Notebook    | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | Notebook    | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [788d1d408b](https://linux-hardware.org/?probe=788d1d408b) | Feb 06, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [97252e199d](https://linux-hardware.org/?probe=97252e199d) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | Notebook    | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ab13127567](https://linux-hardware.org/?probe=ab13127567) | Jan 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [560cc09a5a](https://linux-hardware.org/?probe=560cc09a5a) | Jan 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [347446f16f](https://linux-hardware.org/?probe=347446f16f) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| Lenovo        | B560                        | Notebook    | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [0d2187e1bd](https://linux-hardware.org/?probe=0d2187e1bd) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [1781c6451f](https://linux-hardware.org/?probe=1781c6451f) | Jan 23, 2023 |
| Acer          | Aspire E1-530G              | Notebook    | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Eii           | P612F                       | All in one  | [29acda8f67](https://linux-hardware.org/?probe=29acda8f67) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [bb4c5c0f73](https://linux-hardware.org/?probe=bb4c5c0f73) | Jan 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [c531fbad47](https://linux-hardware.org/?probe=c531fbad47) | Jan 14, 2023 |
| Timi          | Redmi Book Pro 14S          | Notebook    | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [fdf24274c5](https://linux-hardware.org/?probe=fdf24274c5) | Jan 13, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [8228b94c50](https://linux-hardware.org/?probe=8228b94c50) | Jan 11, 2023 |
| Yadro         | YadroB560                   | Desktop     | [9d45ee1c8c](https://linux-hardware.org/?probe=9d45ee1c8c) | Jan 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [b6402cdd5e](https://linux-hardware.org/?probe=b6402cdd5e) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [c896f4d5ee](https://linux-hardware.org/?probe=c896f4d5ee) | Jan 11, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [808e7e41c5](https://linux-hardware.org/?probe=808e7e41c5) | Jan 10, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [914e3f30cc](https://linux-hardware.org/?probe=914e3f30cc) | Jan 08, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [bed374999d](https://linux-hardware.org/?probe=bed374999d) | Jan 06, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [2952e11cdb](https://linux-hardware.org/?probe=2952e11cdb) | Jan 01, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [9a8967485d](https://linux-hardware.org/?probe=9a8967485d) | Dec 26, 2022 |
| LTD Delovo... | 15Y                         | Notebook    | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [0456782550](https://linux-hardware.org/?probe=0456782550) | Dec 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ad56cab50](https://linux-hardware.org/?probe=5ad56cab50) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [e06ebbd650](https://linux-hardware.org/?probe=e06ebbd650) | Dec 19, 2022 |
| Pegatron      | C15B                        | Notebook    | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [00dd0bc59e](https://linux-hardware.org/?probe=00dd0bc59e) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | Notebook    | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [afd0404144](https://linux-hardware.org/?probe=afd0404144) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [e7e9b42211](https://linux-hardware.org/?probe=e7e9b42211) | Dec 16, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Irbis         | NB264                       | Notebook    | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [25e63313c0](https://linux-hardware.org/?probe=25e63313c0) | Dec 13, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [b58d61f85f](https://linux-hardware.org/?probe=b58d61f85f) | Dec 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [2f5b88399a](https://linux-hardware.org/?probe=2f5b88399a) | Dec 13, 2022 |
| Graviton      | DMB-H610-TMI01              | All in one  | [0b2b77d521](https://linux-hardware.org/?probe=0b2b77d521) | Dec 12, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| HP            | 255 G4                      | Notebook    | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | Notebook    | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| Samsung       | R560                        | Notebook    | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | Notebook    | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | Notebook    | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| MSI           | J1800I                      | Desktop     | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | Notebook    | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | Notebook    | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | Notebook    | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [ece886e874](https://linux-hardware.org/?probe=ece886e874) | Nov 17, 2022 |
| Timi          | TM1701                      | Notebook    | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | Notebook    | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | Desktop     | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| Acer          | TravelMate 6292             | Notebook    | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [b388ac6776](https://linux-hardware.org/?probe=b388ac6776) | Oct 27, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [89e7931244](https://linux-hardware.org/?probe=89e7931244) | Oct 27, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [cea24a780a](https://linux-hardware.org/?probe=cea24a780a) | Oct 26, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a876af89ec](https://linux-hardware.org/?probe=a876af89ec) | Oct 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [25db5739b7](https://linux-hardware.org/?probe=25db5739b7) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | Notebook    | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [18d8d35afa](https://linux-hardware.org/?probe=18d8d35afa) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae13c0bb6b](https://linux-hardware.org/?probe=ae13c0bb6b) | Oct 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | Notebook    | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [d0d194fbdc](https://linux-hardware.org/?probe=d0d194fbdc) | Oct 15, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [355974871d](https://linux-hardware.org/?probe=355974871d) | Oct 12, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [a28efd61d1](https://linux-hardware.org/?probe=a28efd61d1) | Oct 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [02395d2c6f](https://linux-hardware.org/?probe=02395d2c6f) | Oct 07, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [79b160283f](https://linux-hardware.org/?probe=79b160283f) | Oct 05, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [8e3ee86b79](https://linux-hardware.org/?probe=8e3ee86b79) | Oct 05, 2022 |
| ASUSTek       | D300TA                      | Desktop     | [7c175e4db4](https://linux-hardware.org/?probe=7c175e4db4) | Oct 03, 2022 |
| Acer          | AOA150                      | Notebook    | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | Notebook    | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | Notebook    | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [b8609443fe](https://linux-hardware.org/?probe=b8609443fe) | Sep 17, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [0384b171c7](https://linux-hardware.org/?probe=0384b171c7) | Sep 03, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | Notebook    | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [a6a798ce96](https://linux-hardware.org/?probe=a6a798ce96) | Aug 16, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [315c1df30c](https://linux-hardware.org/?probe=315c1df30c) | Aug 16, 2022 |
| HP            | Pavilion g7                 | Notebook    | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| HP            | 83EB                        | All in one  | [beb4a8d108](https://linux-hardware.org/?probe=beb4a8d108) | Aug 03, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [7d9b8e0f96](https://linux-hardware.org/?probe=7d9b8e0f96) | Aug 01, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | Notebook    | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| OEM           | KX-18 V1.0                  | Desktop     | [a68e653aa9](https://linux-hardware.org/?probe=a68e653aa9) | Jul 14, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c8051cd18e](https://linux-hardware.org/?probe=c8051cd18e) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | Notebook    | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | Notebook    | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [7a95d588c4](https://linux-hardware.org/?probe=7a95d588c4) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [8598f1f5ee](https://linux-hardware.org/?probe=8598f1f5ee) | Jun 30, 2022 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [7411d7a561](https://linux-hardware.org/?probe=7411d7a561) | Jun 23, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2724c1558a](https://linux-hardware.org/?probe=2724c1558a) | Jun 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [8fe4a74fa3](https://linux-hardware.org/?probe=8fe4a74fa3) | Jun 10, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [31ab5150ea](https://linux-hardware.org/?probe=31ab5150ea) | Jun 06, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4fa81ba66a](https://linux-hardware.org/?probe=4fa81ba66a) | Jun 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [fb935ea1d0](https://linux-hardware.org/?probe=fb935ea1d0) | Jun 03, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [7bfddcecee](https://linux-hardware.org/?probe=7bfddcecee) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| Panasonic     | CF-20-1                     | Notebook    | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| ICL           | Unknown                     | Notebook    | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| iRU           | LPGR.469559.012             | Desktop     | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ICL           | H310SB-TM                   | All in one  | [72c2889a81](https://linux-hardware.org/?probe=72c2889a81) | May 18, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | Desktop     | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [96e5d68181](https://linux-hardware.org/?probe=96e5d68181) | May 06, 2022 |
| ASRock        | H61M-GE                     | Desktop     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| ICL           | H310SB-TM                   | All in one  | [8aca897292](https://linux-hardware.org/?probe=8aca897292) | May 05, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| ICL           | H310SB-TM                   | All in one  | [5e24e4a45d](https://linux-hardware.org/?probe=5e24e4a45d) | May 04, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| Lenovo        | NOK                         | Desktop     | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| ICL           | H310SB-TM                   | All in one  | [11db07be56](https://linux-hardware.org/?probe=11db07be56) | Apr 25, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [651d569b66](https://linux-hardware.org/?probe=651d569b66) | Apr 18, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b97ab9e5ca](https://linux-hardware.org/?probe=b97ab9e5ca) | Apr 18, 2022 |
| ICL           | H310SB-TM                   | All in one  | [75dab395ac](https://linux-hardware.org/?probe=75dab395ac) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [faeb46556e](https://linux-hardware.org/?probe=faeb46556e) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [1ec31e58eb](https://linux-hardware.org/?probe=1ec31e58eb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [558e7d71c5](https://linux-hardware.org/?probe=558e7d71c5) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [58d8d12597](https://linux-hardware.org/?probe=58d8d12597) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [352ed8f1aa](https://linux-hardware.org/?probe=352ed8f1aa) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [f23db30412](https://linux-hardware.org/?probe=f23db30412) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3fa8965015](https://linux-hardware.org/?probe=3fa8965015) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [287eb4cfbb](https://linux-hardware.org/?probe=287eb4cfbb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [8c69097ae0](https://linux-hardware.org/?probe=8c69097ae0) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| Timi          | TM1701                      | Notebook    | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [567d83946c](https://linux-hardware.org/?probe=567d83946c) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [84e70046d5](https://linux-hardware.org/?probe=84e70046d5) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [92f6d24bde](https://linux-hardware.org/?probe=92f6d24bde) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [8e924a50c1](https://linux-hardware.org/?probe=8e924a50c1) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [99d19658b8](https://linux-hardware.org/?probe=99d19658b8) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b6bcbc6a65](https://linux-hardware.org/?probe=b6bcbc6a65) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3e7d8951a2](https://linux-hardware.org/?probe=3e7d8951a2) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [71dfb9a346](https://linux-hardware.org/?probe=71dfb9a346) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [7cf5bcdb89](https://linux-hardware.org/?probe=7cf5bcdb89) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [6aaab98810](https://linux-hardware.org/?probe=6aaab98810) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [dde0916ae5](https://linux-hardware.org/?probe=dde0916ae5) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [68041f0a96](https://linux-hardware.org/?probe=68041f0a96) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [87858c448c](https://linux-hardware.org/?probe=87858c448c) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a7e615a620](https://linux-hardware.org/?probe=a7e615a620) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [5b340e2b7f](https://linux-hardware.org/?probe=5b340e2b7f) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a20cfb8d86](https://linux-hardware.org/?probe=a20cfb8d86) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [19d0ee846e](https://linux-hardware.org/?probe=19d0ee846e) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [9e2f7749b8](https://linux-hardware.org/?probe=9e2f7749b8) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [a473baa2ff](https://linux-hardware.org/?probe=a473baa2ff) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [12009b21d8](https://linux-hardware.org/?probe=12009b21d8) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [3f2bf77788](https://linux-hardware.org/?probe=3f2bf77788) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| Acer          | Aspire 5745G                | Notebook    | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | Notebook    | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| HP            | 250 G3                      | Notebook    | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [83881d4eb6](https://linux-hardware.org/?probe=83881d4eb6) | Mar 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [2379c7546f](https://linux-hardware.org/?probe=2379c7546f) | Mar 09, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [92fc99440a](https://linux-hardware.org/?probe=92fc99440a) | Mar 08, 2022 |
| Dell          | G5 5590                     | Notebook    | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [4f93db2c52](https://linux-hardware.org/?probe=4f93db2c52) | Mar 05, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [04a1a09e43](https://linux-hardware.org/?probe=04a1a09e43) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [f7f470651e](https://linux-hardware.org/?probe=f7f470651e) | Feb 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| Gigabyte      | X79-UD3                     | Desktop     | [452ebf6a67](https://linux-hardware.org/?probe=452ebf6a67) | Feb 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [921e224ec5](https://linux-hardware.org/?probe=921e224ec5) | Feb 12, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | Notebook    | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| T-Platform... | TF307-MB                    | Soc         | [c34cd190e4](https://linux-hardware.org/?probe=c34cd190e4) | Feb 01, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [351b2e5344](https://linux-hardware.org/?probe=351b2e5344) | Jan 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [481e745592](https://linux-hardware.org/?probe=481e745592) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [8c31667834](https://linux-hardware.org/?probe=8c31667834) | Jan 20, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [edd6464f18](https://linux-hardware.org/?probe=edd6464f18) | Jan 19, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [93fef2e073](https://linux-hardware.org/?probe=93fef2e073) | Jan 19, 2022 |
| Dell          | Latitude 3590               | Notebook    | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| MSI           | MS-AC16 100                 | All in one  | [3a3bfc48f7](https://linux-hardware.org/?probe=3a3bfc48f7) | Jan 17, 2022 |
| MSI           | A68HM-P33 V2                | Desktop     | [98e05db690](https://linux-hardware.org/?probe=98e05db690) | Jan 17, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [0c802de596](https://linux-hardware.org/?probe=0c802de596) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c8ff16f0ed](https://linux-hardware.org/?probe=c8ff16f0ed) | Dec 24, 2021 |
| Supermicro    | X11SDW-14CNT-TP13F          | Desktop     | [4d8499f8ba](https://linux-hardware.org/?probe=4d8499f8ba) | Dec 23, 2021 |
| Supermicro    | X10SDV-TP8F                 | Server      | [adc426b903](https://linux-hardware.org/?probe=adc426b903) | Dec 23, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9180a824d8](https://linux-hardware.org/?probe=9180a824d8) | Dec 23, 2021 |
| Samsung       | 750XDA                      | Notebook    | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [7ef05a32a9](https://linux-hardware.org/?probe=7ef05a32a9) | Dec 17, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [2aff2121af](https://linux-hardware.org/?probe=2aff2121af) | Dec 16, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [30eab5f54f](https://linux-hardware.org/?probe=30eab5f54f) | Dec 15, 2021 |
| Unknown       | Baikal Electronics Baika... | Soc         | [b4e6606b42](https://linux-hardware.org/?probe=b4e6606b42) | Dec 10, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [c853f62ddd](https://linux-hardware.org/?probe=c853f62ddd) | Dec 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [0f5c69902a](https://linux-hardware.org/?probe=0f5c69902a) | Dec 01, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [68a1f83b4f](https://linux-hardware.org/?probe=68a1f83b4f) | Nov 28, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [058d8a0404](https://linux-hardware.org/?probe=058d8a0404) | Nov 19, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [70ee05a53e](https://linux-hardware.org/?probe=70ee05a53e) | Oct 28, 2021 |
| HUAWEI        | BC11SPSCB0 V100R005         | Server      | [ad903545ce](https://linux-hardware.org/?probe=ad903545ce) | Oct 14, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9dd1b763b](https://linux-hardware.org/?probe=d9dd1b763b) | Oct 08, 2021 |
| Dell          | 0U649C                      | Desktop     | [80e138d949](https://linux-hardware.org/?probe=80e138d949) | Sep 24, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [92829c951d](https://linux-hardware.org/?probe=92829c951d) | Sep 21, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [da7d22c384](https://linux-hardware.org/?probe=da7d22c384) | Sep 16, 2021 |
| Timi          | TM1701                      | Notebook    | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | Notebook    | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [132286ab64](https://linux-hardware.org/?probe=132286ab64) | Aug 17, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [85ce2f74c4](https://linux-hardware.org/?probe=85ce2f74c4) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [624e92e15e](https://linux-hardware.org/?probe=624e92e15e) | Aug 11, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | Notebook    | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [db68dde16d](https://linux-hardware.org/?probe=db68dde16d) | Aug 04, 2021 |
| Durabook      | Z14                         | Notebook    | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b01641d467](https://linux-hardware.org/?probe=b01641d467) | Jul 25, 2021 |
| Aquarius      | NS483                       | Convertible | [bc5d045def](https://linux-hardware.org/?probe=bc5d045def) | Jul 20, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [8687a8809b](https://linux-hardware.org/?probe=8687a8809b) | Jul 14, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [05be9fcdec](https://linux-hardware.org/?probe=05be9fcdec) | Jul 03, 2021 |
| Aquarius      | NS585                       | Notebook    | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [24bd5ac93f](https://linux-hardware.org/?probe=24bd5ac93f) | Jun 27, 2021 |
| Kraftway      | KWH310                      | Desktop     | [f470a86a1c](https://linux-hardware.org/?probe=f470a86a1c) | Jun 26, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [87ab7018c4](https://linux-hardware.org/?probe=87ab7018c4) | Jun 24, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [d31e4518a6](https://linux-hardware.org/?probe=d31e4518a6) | Jun 22, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [21a019dcb3](https://linux-hardware.org/?probe=21a019dcb3) | Jun 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [8325754280](https://linux-hardware.org/?probe=8325754280) | Jun 13, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [96cc5b470f](https://linux-hardware.org/?probe=96cc5b470f) | Jun 12, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [cfeb0493d3](https://linux-hardware.org/?probe=cfeb0493d3) | Jun 11, 2021 |
| Dell          | G3 3779                     | Notebook    | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | Notebook    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [13396a7347](https://linux-hardware.org/?probe=13396a7347) | May 19, 2021 |
| DEPO Compu... | T09-D                       | Stick pc    | [678542f4fe](https://linux-hardware.org/?probe=678542f4fe) | May 18, 2021 |
| DEPO Compu... | DPH410S                     | Desktop     | [0d1000e904](https://linux-hardware.org/?probe=0d1000e904) | May 14, 2021 |
| DEPO Compu... | DPA320S G10g                | Desktop     | [5ecc011c34](https://linux-hardware.org/?probe=5ecc011c34) | May 14, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [97b70c1bac](https://linux-hardware.org/?probe=97b70c1bac) | Apr 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| Lenovo        | 3184 No DPK                 | All in one  | [bd5551c49a](https://linux-hardware.org/?probe=bd5551c49a) | Mar 31, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [34997240d5](https://linux-hardware.org/?probe=34997240d5) | Mar 30, 2021 |
| ECS           | BAT-I2                      | Desktop     | [037e6e58e6](https://linux-hardware.org/?probe=037e6e58e6) | Mar 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [f0c7659cf9](https://linux-hardware.org/?probe=f0c7659cf9) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [8e53d68603](https://linux-hardware.org/?probe=8e53d68603) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [7467b59c82](https://linux-hardware.org/?probe=7467b59c82) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| iRU           | IRUB365M                    | Desktop     | [b7d5dda036](https://linux-hardware.org/?probe=b7d5dda036) | Mar 11, 2021 |
| Dell          | 04G47W A00                  | All in one  | [3a565370de](https://linux-hardware.org/?probe=3a565370de) | Feb 15, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [6651c76da3](https://linux-hardware.org/?probe=6651c76da3) | Feb 07, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [d63a1e9eef](https://linux-hardware.org/?probe=d63a1e9eef) | Feb 02, 2021 |
| ASUSTek       | P5B                         | Desktop     | [e0fc318a34](https://linux-hardware.org/?probe=e0fc318a34) | Jan 28, 2021 |
| Supermicro    | X11DPH-i                    | Server      | [8d109ac7b4](https://linux-hardware.org/?probe=8d109ac7b4) | Jan 26, 2021 |
| EPoX Compu... | GeForce6100 + nForce410 ... | Desktop     | [99f734d52e](https://linux-hardware.org/?probe=99f734d52e) | Jan 18, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [38ae5dd532](https://linux-hardware.org/?probe=38ae5dd532) | Jan 14, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [593a489e8d](https://linux-hardware.org/?probe=593a489e8d) | Jan 13, 2021 |
| Intel         | B75                         | Desktop     | [34d29fb066](https://linux-hardware.org/?probe=34d29fb066) | Jan 12, 2021 |
| Acer          | NC-ES1-131-C1NL             | Notebook    | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [2c49129777](https://linux-hardware.org/?probe=2c49129777) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [31d84f6485](https://linux-hardware.org/?probe=31d84f6485) | Dec 31, 2020 |
| Irbis         | TW100                       | Tablet      | [23c593482c](https://linux-hardware.org/?probe=23c593482c) | Dec 28, 2020 |
| SYS           | H310SB                      | Desktop     | [ba93a151f2](https://linux-hardware.org/?probe=ba93a151f2) | Dec 24, 2020 |
| HP            | 877E A                      | Desktop     | [4456ec4081](https://linux-hardware.org/?probe=4456ec4081) | Dec 23, 2020 |
| MSI           | MS-AC16 100                 | All in one  | [8df63d744b](https://linux-hardware.org/?probe=8df63d744b) | Dec 23, 2020 |
| HP            | 877E A                      | Desktop     | [145b54d631](https://linux-hardware.org/?probe=145b54d631) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | Notebook    | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Irbis         | TW100                       | Tablet      | [5ebe1b6e89](https://linux-hardware.org/?probe=5ebe1b6e89) | Dec 19, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [dbc40fef9d](https://linux-hardware.org/?probe=dbc40fef9d) | Dec 18, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bb4bd8f82f](https://linux-hardware.org/?probe=bb4bd8f82f) | Dec 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5cf089cfa1](https://linux-hardware.org/?probe=5cf089cfa1) | Dec 07, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [fdfcfb17c6](https://linux-hardware.org/?probe=fdfcfb17c6) | Dec 03, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [98800b881c](https://linux-hardware.org/?probe=98800b881c) | Dec 03, 2020 |
| Gigabyte      | H310N x.x                   | Desktop     | [b0ca19ee36](https://linux-hardware.org/?probe=b0ca19ee36) | Dec 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4ec24e5c24](https://linux-hardware.org/?probe=4ec24e5c24) | Nov 27, 2020 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [2758f1ff94](https://linux-hardware.org/?probe=2758f1ff94) | Nov 21, 2020 |
| Acer          | Veriton Z4860G              | All in one  | [8adebb44d3](https://linux-hardware.org/?probe=8adebb44d3) | Nov 20, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ab7e110c9a](https://linux-hardware.org/?probe=ab7e110c9a) | Nov 17, 2020 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ed5fee32dd](https://linux-hardware.org/?probe=ed5fee32dd) | Nov 13, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c878b046bc](https://linux-hardware.org/?probe=c878b046bc) | Nov 13, 2020 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [5ad12e4b3b](https://linux-hardware.org/?probe=5ad12e4b3b) | Nov 12, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [e25041fb04](https://linux-hardware.org/?probe=e25041fb04) | Nov 09, 2020 |
| ASUSTek       | A8N-E                       | Desktop     | [f716673893](https://linux-hardware.org/?probe=f716673893) | Oct 24, 2020 |
| ASUSTek       | P5B-MX                      | Desktop     | [0779d0f18c](https://linux-hardware.org/?probe=0779d0f18c) | Oct 24, 2020 |
| MSI           | X300/X340/X400 series       | Notebook    | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [f587011ab7](https://linux-hardware.org/?probe=f587011ab7) | Sep 10, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [fb4e557598](https://linux-hardware.org/?probe=fb4e557598) | Aug 16, 2020 |
| ASRock        | 4CoreN73PV-HD720p           | Desktop     | [ac70970005](https://linux-hardware.org/?probe=ac70970005) | Aug 16, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [4c98d77a2f](https://linux-hardware.org/?probe=4c98d77a2f) | Aug 07, 2020 |
| Samsung       | R510/P510                   | Notebook    | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [cee7ed2ce9](https://linux-hardware.org/?probe=cee7ed2ce9) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [f31ffbf544](https://linux-hardware.org/?probe=f31ffbf544) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [72c1d1ffca](https://linux-hardware.org/?probe=72c1d1ffca) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [298376a45e](https://linux-hardware.org/?probe=298376a45e) | Jun 23, 2020 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [b03abee3fb](https://linux-hardware.org/?probe=b03abee3fb) | Jun 12, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [70139de021](https://linux-hardware.org/?probe=70139de021) | Jun 10, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ee83d50faa](https://linux-hardware.org/?probe=ee83d50faa) | Jun 10, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [c4c8bad6ca](https://linux-hardware.org/?probe=c4c8bad6ca) | May 31, 2020 |
| HP            | 255 G2                      | Notebook    | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [74899486ac](https://linux-hardware.org/?probe=74899486ac) | May 26, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [861b6c69a0](https://linux-hardware.org/?probe=861b6c69a0) | May 21, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ae09cd2a40](https://linux-hardware.org/?probe=ae09cd2a40) | May 21, 2020 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Acer          | Aspire E1-571G              | Notebook    | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | Notebook    | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a644a3a3ad](https://linux-hardware.org/?probe=a644a3a3ad) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | Notebook    | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| HP            | 09F0h                       | Desktop     | [7f6c26af5d](https://linux-hardware.org/?probe=7f6c26af5d) | Oct 25, 2019 |
| HUAWEI        | BC11HGSB0 V100R003          | Server      | [5eb4dfc951](https://linux-hardware.org/?probe=5eb4dfc951) | Oct 22, 2019 |
| Dell          | 0F96C8 A00                  | All in one  | [29d0ad2441](https://linux-hardware.org/?probe=29d0ad2441) | Oct 22, 2019 |
| MSI           | B350M PRO-VDH               | Desktop     | [525f09653e](https://linux-hardware.org/?probe=525f09653e) | Oct 08, 2019 |
| MSI           | MEGA BOOK S430              | Notebook    | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Gigabyte      | GA-890XA-UD3                | Desktop     | [1536999c3e](https://linux-hardware.org/?probe=1536999c3e) | Sep 13, 2019 |
| ASRock        | Z77 Pro3                    | Desktop     | [a1db2eb143](https://linux-hardware.org/?probe=a1db2eb143) | Sep 13, 2019 |
| ASRock        | B85M                        | Desktop     | [5a36ce2620](https://linux-hardware.org/?probe=5a36ce2620) | Sep 13, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | Notebook    | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [68dbf33470](https://linux-hardware.org/?probe=68dbf33470) | Aug 03, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [5814b6a2af](https://linux-hardware.org/?probe=5814b6a2af) | Mar 28, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [34b40d93fc](https://linux-hardware.org/?probe=34b40d93fc) | Oct 30, 2018 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [d55532d7a9](https://linux-hardware.org/?probe=d55532d7a9) | Oct 29, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Biostar       | NF720D A2G+                 | Desktop     | [ef09cb18cc](https://linux-hardware.org/?probe=ef09cb18cc) | Oct 29, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [572c918e8a](https://linux-hardware.org/?probe=572c918e8a) | Oct 27, 2018 |
| Acer          | Aspire ES1-523              | Notebook    | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | Notebook    | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ALT_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 165       | 25.27%  |
| ALT Linux 10.1     | 128       | 19.6%   |
| ALT Linux 9.1      | 65        | 9.95%   |
| MOS 10             | 61        | 9.34%   |
| ALT Linux 10.0     | 57        | 8.73%   |
| ALT Linux 10.2     | 40        | 6.13%   |
| ALT Linux 9.0      | 31        | 4.75%   |
| ALT Linux 9.2      | 18        | 2.76%   |
| ALT Linux P10      | 11        | 1.68%   |
| ALT Linux 8.4      | 11        | 1.68%   |
| ALT Linux 10.1.900 | 8         | 1.23%   |
| ALT Linux 10       | 7         | 1.07%   |
| ALT Linux 10.0.900 | 6         | 0.92%   |
| ALT Linux P8       | 5         | 0.77%   |
| ALT Linux 8.2      | 5         | 0.77%   |
| ALT Linux P9       | 4         | 0.61%   |
| ALT Linux 20220110 | 4         | 0.61%   |
| ALT Linux 20201124 | 4         | 0.61%   |
| ALT Linux 7.0.5    | 2         | 0.31%   |
| ALT Linux 20191026 | 2         | 0.31%   |
| Kometa 1           | 1         | 0.15%   |
| ALT Linux 9.1.990  | 1         | 0.15%   |
| ALT Linux 9        | 1         | 0.15%   |
| ALT Linux 8.990    | 1         | 0.15%   |
| ALT Linux 8.93     | 1         | 0.15%   |
| ALT Linux 8.920    | 1         | 0.15%   |
| ALT Linux 8.3      | 1         | 0.15%   |
| ALT Linux 8.2.0    | 1         | 0.15%   |
| ALT Linux 8.0.0    | 1         | 0.15%   |
| ALT Linux 8.0      | 1         | 0.15%   |
| ALT Linux 20190624 | 1         | 0.15%   |
| ALT Linux 20190303 | 1         | 0.15%   |
| ALT Linux 10.1.990 | 1         | 0.15%   |
| ALT Linux 10.0.920 | 1         | 0.15%   |
| ALT Linux 10.0.910 | 1         | 0.15%   |
| ALT Linux 0.9      | 1         | 0.15%   |
| ALT Linux 0.8.1    | 1         | 0.15%   |
| ALT Linux 0.7.6    | 1         | 0.15%   |
| ALT Linux          | 1         | 0.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ALT Linux | 618       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.109-std-def-alt1      | 85        | 12.45%  |
| 5.10.102-std-def-alt1      | 80        | 11.71%  |
| 5.15.72-un-def-alt1        | 21        | 3.07%   |
| 5.15.34-un-def-alt1        | 19        | 2.78%   |
| 5.10.139-std-def-alt1      | 18        | 2.64%   |
| 5.15.80-un-def-alt1        | 16        | 2.34%   |
| 5.10.82-std-def-alt1       | 16        | 2.34%   |
| 5.10.164-std-def-alt1      | 16        | 2.34%   |
| 5.10.156-std-def-alt1      | 14        | 2.05%   |
| 5.10.123-std-def-alt1      | 13        | 1.9%    |
| 5.4.51-std-def-alt1        | 12        | 1.76%   |
| 5.10.88-std-def-alt1       | 11        | 1.61%   |
| 4.19.79-std-def-alt1       | 11        | 1.61%   |
| 5.4.68-std-def-alt1.1      | 10        | 1.46%   |
| 6.1.49-un-def-alt1         | 8         | 1.17%   |
| 6.1.38-un-def-alt1         | 7         | 1.02%   |
| 5.4.28-std-def-alt1        | 7         | 1.02%   |
| 5.10.152-std-def-alt1      | 7         | 1.02%   |
| 6.1.54-un-def-alt1         | 5         | 0.73%   |
| 5.15.76-un-def-alt1        | 5         | 0.73%   |
| 5.15.32-un-def-alt1        | 5         | 0.73%   |
| 5.10.93-std-def-alt1       | 5         | 0.73%   |
| 5.10.83-std-def-alt0.c9f.2 | 5         | 0.73%   |
| 5.10.32-un-def-alt1        | 5         | 0.73%   |
| 5.10.145-std-def-alt1      | 5         | 0.73%   |
| 6.1.55-un-def-alt1         | 4         | 0.59%   |
| 5.7.19-un-def-alt1         | 4         | 0.59%   |
| 5.4.62-std-def-alt1        | 4         | 0.59%   |
| 5.4.41-std-def-alt1        | 4         | 0.59%   |
| 5.15.63-un-def-alt1        | 4         | 0.59%   |
| 5.15.105-un-def-alt1       | 4         | 0.59%   |
| 5.10.35-un-def-alt1        | 4         | 0.59%   |
| 5.10.179-std-def-alt1      | 4         | 0.59%   |
| 5.10.17-un-def-alt1        | 4         | 0.59%   |
| 6.1.29-un-def-alt1         | 3         | 0.44%   |
| 5.4.85-std-def-alt1        | 3         | 0.44%   |
| 5.4.127-std-def-alt1       | 3         | 0.44%   |
| 5.15.79-un-def-alt1        | 3         | 0.44%   |
| 5.15.74-un-def-alt1        | 3         | 0.44%   |
| 5.15.73-un-def-alt1        | 3         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.109 | 85        | 12.45%  |
| 5.10.102 | 80        | 11.71%  |
| 5.15.72  | 21        | 3.07%   |
| 5.15.34  | 19        | 2.78%   |
| 5.10.139 | 18        | 2.64%   |
| 5.15.80  | 17        | 2.49%   |
| 5.10.82  | 16        | 2.34%   |
| 5.10.164 | 16        | 2.34%   |
| 5.10.156 | 15        | 2.2%    |
| 5.10.123 | 13        | 1.9%    |
| 5.4.51   | 12        | 1.76%   |
| 5.10.88  | 11        | 1.61%   |
| 4.19.79  | 11        | 1.61%   |
| 5.4.68   | 10        | 1.46%   |
| 6.1.49   | 8         | 1.17%   |
| 6.1.38   | 7         | 1.02%   |
| 5.4.28   | 7         | 1.02%   |
| 5.10.152 | 7         | 1.02%   |
| 6.1.54   | 5         | 0.73%   |
| 5.15.76  | 5         | 0.73%   |
| 5.15.32  | 5         | 0.73%   |
| 5.10.93  | 5         | 0.73%   |
| 5.10.83  | 5         | 0.73%   |
| 5.10.35  | 5         | 0.73%   |
| 5.10.32  | 5         | 0.73%   |
| 5.10.145 | 5         | 0.73%   |
| 6.1.55   | 4         | 0.59%   |
| 5.7.19   | 4         | 0.59%   |
| 5.4.62   | 4         | 0.59%   |
| 5.4.41   | 4         | 0.59%   |
| 5.15.63  | 4         | 0.59%   |
| 5.15.105 | 4         | 0.59%   |
| 5.10.179 | 4         | 0.59%   |
| 5.10.17  | 4         | 0.59%   |
| 5.10.118 | 4         | 0.59%   |
| 6.1.29   | 3         | 0.44%   |
| 5.4.85   | 3         | 0.44%   |
| 5.4.127  | 3         | 0.44%   |
| 5.15.79  | 3         | 0.44%   |
| 5.15.74  | 3         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 367       | 57.08%  |
| 5.15    | 107       | 16.64%  |
| 5.4     | 65        | 10.11%  |
| 6.1     | 40        | 6.22%   |
| 4.19    | 26        | 4.04%   |
| 4.9     | 7         | 1.09%   |
| 5.7     | 5         | 0.78%   |
| 6.2     | 3         | 0.47%   |
| 5.2     | 3         | 0.47%   |
| 5.18    | 3         | 0.47%   |
| 5.13    | 3         | 0.47%   |
| 6.5     | 2         | 0.31%   |
| 6.4     | 2         | 0.31%   |
| 5.14    | 2         | 0.31%   |
| 4.14    | 2         | 0.31%   |
| 5.9     | 1         | 0.16%   |
| 5.3     | 1         | 0.16%   |
| 5.16    | 1         | 0.16%   |
| 5.12    | 1         | 0.16%   |
| 4.4     | 1         | 0.16%   |
| 4.20    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 595       | 96.28%  |
| i686    | 16        | 2.59%   |
| aarch64 | 4         | 0.65%   |
| e2k     | 3         | 0.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 406       | 64.34%  |
| XFCE            | 94        | 14.9%   |
| Unknown         | 86        | 13.63%  |
| MATE            | 21        | 3.33%   |
| LXQt            | 7         | 1.11%   |
| GNOME           | 6         | 0.95%   |
| Cinnamon        | 6         | 0.95%   |
| KDE             | 2         | 0.32%   |
| GNOME Flashback | 2         | 0.32%   |
| X-Cinnamon      | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 597       | 96.14%  |
| Unknown | 11        | 1.77%   |
| Tty     | 7         | 1.13%   |
| Wayland | 6         | 0.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 318       | 50.24%  |
| LightDM | 158       | 24.96%  |
| Unknown | 91        | 14.38%  |
| TDM     | 62        | 9.79%   |
| GDM     | 2         | 0.32%   |
| XDM     | 1         | 0.16%   |
| WDM     | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| ru_RU      | 524       | 82.91%  |
| Unknown    | 81        | 12.82%  |
| en_US      | 18        | 2.85%   |
| POSIX      | 6         | 0.95%   |
| it_IT@euro | 1         | 0.16%   |
| el_GR      | 1         | 0.16%   |
| C          | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 396       | 63.56%  |
| BIOS | 227       | 36.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 548       | 88.1%   |
| Overlay | 39        | 6.27%   |
| Btrfs   | 32        | 5.14%   |
| Unknown | 2         | 0.32%   |
| Xfs     | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 382       | 60.93%  |
| MBR     | 151       | 24.08%  |
| Unknown | 94        | 14.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 557       | 89.26%  |
| Yes       | 67        | 10.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 435       | 69.49%  |
| Yes       | 191       | 30.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| ASUSTek Computer                  | 82        | 13.27%  |
| Hewlett-Packard                   | 74        | 11.97%  |
| Intel                             | 58        | 9.39%   |
| Lenovo                            | 48        | 7.77%   |
| Gigabyte Technology               | 43        | 6.96%   |
| Acer                              | 39        | 6.31%   |
| Clevo                             | 32        | 5.18%   |
| 3Logic Group                      | 28        | 4.53%   |
| MSI                               | 25        | 4.05%   |
| ASRock                            | 24        | 3.88%   |
| ICL                               | 21        | 3.4%    |
| Unknown                           | 18        | 2.91%   |
| Dell                              | 15        | 2.43%   |
| HUAWEI                            | 12        | 1.94%   |
| DEPO Computers                    | 11        | 1.78%   |
| Samsung Electronics               | 6         | 0.97%   |
| Graviton                          | 6         | 0.97%   |
| Aquarius                          | 6         | 0.97%   |
| Apple                             | 5         | 0.81%   |
| Supermicro                        | 4         | 0.65%   |
| MAINBRD                           | 4         | 0.65%   |
| iRU                               | 4         | 0.65%   |
| Biostar                           | 4         | 0.65%   |
| Toshiba                           | 3         | 0.49%   |
| Kraftway                          | 3         | 0.49%   |
| F-PLUS EQUIPMENT AND DEVELOPMENTS | 3         | 0.49%   |
| Timi                              | 2         | 0.32%   |
| Pegatron                          | 2         | 0.32%   |
| Panasonic                         | 2         | 0.32%   |
| Irbis                             | 2         | 0.32%   |
| Huanan                            | 2         | 0.32%   |
| Yadro                             | 1         | 0.16%   |
| VIA Technologies                  | 1         | 0.16%   |
| Valve                             | 1         | 0.16%   |
| T-Platforms                       | 1         | 0.16%   |
| SYS                               | 1         | 0.16%   |
| Sony                              | 1         | 0.16%   |
| ROMBICA                           | 1         | 0.16%   |
| Raspberry Pi Foundation           | 1         | 0.16%   |
| on Graviton                       | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel SKYBAY                             | 47        | 7.61%   |
| Clevo NL41MU2                            | 32        | 5.18%   |
| 3Logic Group Graviton                    | 21        | 3.4%    |
| Unknown                                  | 21        | 3.4%    |
| HP 250 G7 Notebook PC                    | 12        | 1.94%   |
| ASUS PRIME B450-PLUS                     | 12        | 1.94%   |
| Lenovo V540-24IWL AIO 10YS0031RU         | 10        | 1.62%   |
| Acer Veriton X2640G                      | 10        | 1.62%   |
| HP ZBook 17 G5                           | 9         | 1.46%   |
| HP ProBook 440 G5                        | 8         | 1.29%   |
| ICL RAYbook Si1512                       | 6         | 0.97%   |
| Lenovo ThinkSystem SR590 -[7X99CTO1WW]-  | 5         | 0.81%   |
| MAINBRD OPS62A-SHA                       | 4         | 0.65%   |
| ICL RAY Si105.Mi                         | 4         | 0.65%   |
| ICL RAY S122.Mi                          | 4         | 0.65%   |
| Gigabyte H110M-S2H                       | 4         | 0.65%   |
| DEPO Computers DPC156                    | 4         | 0.65%   |
| Lenovo ThinkBook 15 G2 ITL 20VE          | 3         | 0.49%   |
| HUAWEI NBD-WXX9                          | 3         | 0.49%   |
| HP EliteBook 840 G4                      | 3         | 0.49%   |
| HP 250 G6 Notebook PC                    | 3         | 0.49%   |
| DEPO Computers DPA520S                   | 3         | 0.49%   |
| Dell Latitude 3420                       | 3         | 0.49%   |
| ASUS VivoBook_ASUSLaptop M1503QA_M1503QA | 3         | 0.49%   |
| ASUS H110M-R                             | 3         | 0.49%   |
| 3Logic Group Graviton N15i-K2            | 3         | 0.49%   |
| 3Logic Group Graviton N15i               | 3         | 0.49%   |
| Supermicro Super Server                  | 2         | 0.32%   |
| MSI MS-7D46                              | 2         | 0.32%   |
| MSI MPG B560 Trident A (MS-B926)         | 2         | 0.32%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT     | 2         | 0.32%   |
| Kraftway ACCORD                          | 2         | 0.32%   |
| iRU 515                                  | 2         | 0.32%   |
| Irbis TW100                              | 2         | 0.32%   |
| Intel B75                                | 2         | 0.32%   |
| ICL NJ50_70CU                            | 2         | 0.32%   |
| ICL H510SB-TM                            | 2         | 0.32%   |
| HUAWEI KLVL-WXXW                         | 2         | 0.32%   |
| HP ProBook 440 G4                        | 2         | 0.32%   |
| HP EliteBook 8470p                       | 2         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Intel SKYBAY           | 47        | 7.61%   |
| Clevo NL41MU2          | 32        | 5.18%   |
| 3Logic Group Graviton  | 28        | 4.53%   |
| Unknown                | 21        | 3.4%    |
| ASUS PRIME             | 18        | 2.91%   |
| HP 250                 | 17        | 2.75%   |
| Acer Veriton           | 16        | 2.59%   |
| HP ProBook             | 13        | 2.1%    |
| Acer Aspire            | 13        | 2.1%    |
| HP Pavilion            | 11        | 1.78%   |
| Lenovo V540-24IWL      | 10        | 1.62%   |
| HP ZBook               | 9         | 1.46%   |
| ICL RAY                | 8         | 1.29%   |
| HP EliteBook           | 8         | 1.29%   |
| Lenovo IdeaPad         | 7         | 1.13%   |
| ICL RAYbook            | 7         | 1.13%   |
| ASUS VivoBook          | 7         | 1.13%   |
| Lenovo ThinkPad        | 6         | 0.97%   |
| HP Laptop              | 6         | 0.97%   |
| ASUS ASUS              | 6         | 0.97%   |
| Lenovo ThinkSystem     | 5         | 0.81%   |
| Dell Latitude          | 5         | 0.81%   |
| MAINBRD OPS62A-SHA     | 4         | 0.65%   |
| Gigabyte H110M-S2H     | 4         | 0.65%   |
| DEPO Computers DPC156  | 4         | 0.65%   |
| Dell OptiPlex          | 4         | 0.65%   |
| Acer TravelMate        | 4         | 0.65%   |
| Lenovo ThinkBook       | 3         | 0.49%   |
| HUAWEI NBD-WXX9        | 3         | 0.49%   |
| DEPO Computers DPA520S | 3         | 0.49%   |
| ASUS P7H55-M           | 3         | 0.49%   |
| ASUS H110M-R           | 3         | 0.49%   |
| Toshiba Satellite      | 2         | 0.32%   |
| Supermicro Super       | 2         | 0.32%   |
| MSI MS-7D46            | 2         | 0.32%   |
| MSI MPG                | 2         | 0.32%   |
| Lenovo V15             | 2         | 0.32%   |
| Lenovo ThinkCentre     | 2         | 0.32%   |
| Kraftway ACCORD        | 2         | 0.32%   |
| iRU 515                | 2         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 92        | 14.89%  |
| 2018    | 79        | 12.78%  |
| 2020    | 67        | 10.84%  |
| 2017    | 63        | 10.19%  |
| 2021    | 59        | 9.55%   |
| 2019    | 45        | 7.28%   |
| 2016    | 34        | 5.5%    |
| 2012    | 24        | 3.88%   |
| 2010    | 22        | 3.56%   |
| 2011    | 21        | 3.4%    |
| 2008    | 17        | 2.75%   |
| 2009    | 16        | 2.59%   |
| 2014    | 15        | 2.43%   |
| 2015    | 12        | 1.94%   |
| 2013    | 12        | 1.94%   |
| 2023    | 10        | 1.62%   |
| 2007    | 10        | 1.62%   |
| 2006    | 9         | 1.46%   |
| Unknown | 5         | 0.81%   |
| 2005    | 3         | 0.49%   |
| 2004    | 2         | 0.32%   |
| 2003    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 272       | 44.01%  |
| Desktop        | 264       | 42.72%  |
| All in one     | 56        | 9.06%   |
| Server         | 10        | 1.62%   |
| Mini pc        | 5         | 0.81%   |
| System on chip | 4         | 0.65%   |
| Convertible    | 4         | 0.65%   |
| Tablet         | 2         | 0.32%   |
| Stick pc       | 1         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 541       | 86.7%   |
| Enabled  | 83        | 13.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 618       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 218       | 35.22%  |
| 8.01-16.0       | 130       | 21%     |
| 16.01-24.0      | 120       | 19.39%  |
| 3.01-4.0        | 80        | 12.92%  |
| 1.01-2.0        | 24        | 3.88%   |
| 32.01-64.0      | 16        | 2.58%   |
| 64.01-256.0     | 15        | 2.42%   |
| 2.01-3.0        | 7         | 1.13%   |
| 24.01-32.0      | 4         | 0.65%   |
| 0.51-1.0        | 4         | 0.65%   |
| More than 256.0 | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 323       | 49.46%  |
| 2.01-3.0   | 118       | 18.07%  |
| 0.51-1.0   | 83        | 12.71%  |
| 4.01-8.0   | 54        | 8.27%   |
| 3.01-4.0   | 49        | 7.5%    |
| 8.01-16.0  | 12        | 1.84%   |
| 0.01-0.5   | 11        | 1.68%   |
| 16.01-24.0 | 2         | 0.31%   |
| 32.01-64.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 460       | 73.13%  |
| 2       | 109       | 17.33%  |
| 3       | 29        | 4.61%   |
| 4       | 13        | 2.07%   |
| 5       | 7         | 1.11%   |
| 0       | 6         | 0.95%   |
| 8       | 2         | 0.32%   |
| 9       | 1         | 0.16%   |
| 6       | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 429       | 69.08%  |
| Yes       | 192       | 30.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 569       | 92.07%  |
| No        | 49        | 7.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 382       | 61.61%  |
| No        | 238       | 38.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 328       | 52.9%   |
| No        | 292       | 47.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Russia     | 589       | 95.31%  |
| Greece     | 6         | 0.97%   |
| Ukraine    | 4         | 0.65%   |
| Belarus    | 3         | 0.49%   |
| Egypt      | 2         | 0.32%   |
| Uzbekistan | 1         | 0.16%   |
| USA        | 1         | 0.16%   |
| UK         | 1         | 0.16%   |
| Moldova    | 1         | 0.16%   |
| Kazakhstan | 1         | 0.16%   |
| Italy      | 1         | 0.16%   |
| France     | 1         | 0.16%   |
| Finland    | 1         | 0.16%   |
| Estonia    | 1         | 0.16%   |
| Czechia    | 1         | 0.16%   |
| Costa Rica | 1         | 0.16%   |
| Colombia   | 1         | 0.16%   |
| China      | 1         | 0.16%   |
| Australia  | 1         | 0.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 374       | 59.27%  |
| St Petersburg     | 38        | 6.02%   |
| Samara            | 12        | 1.9%    |
| Novosibirsk       | 11        | 1.74%   |
| Barnaul           | 11        | 1.74%   |
| Obninsk           | 7         | 1.11%   |
| Krasnoyarsk       | 7         | 1.11%   |
| Irkutsk           | 6         | 0.95%   |
| Chelyabinsk       | 6         | 0.95%   |
| Perm              | 5         | 0.79%   |
| Yekaterinburg     | 4         | 0.63%   |
| Saratov           | 4         | 0.63%   |
| Kaliningrad       | 4         | 0.63%   |
| Vladimir          | 3         | 0.48%   |
| Ufa               | 3         | 0.48%   |
| Surgut            | 3         | 0.48%   |
| Sevastopol        | 3         | 0.48%   |
| Rostov-on-Don     | 3         | 0.48%   |
| Krasnodar         | 3         | 0.48%   |
| Korolyov          | 3         | 0.48%   |
| Kirov             | 3         | 0.48%   |
| Belgorod          | 3         | 0.48%   |
| Astrakhan         | 3         | 0.48%   |
| Zheleznodorozhnyy | 2         | 0.32%   |
| Zelenodolsk       | 2         | 0.32%   |
| Voronezh          | 2         | 0.32%   |
| Vladivostok       | 2         | 0.32%   |
| Verkhnyaya Pyshma | 2         | 0.32%   |
| Vergina           | 2         | 0.32%   |
| Tyumen            | 2         | 0.32%   |
| Thessaloniki      | 2         | 0.32%   |
| Tambov            | 2         | 0.32%   |
| Stavropol         | 2         | 0.32%   |
| Nizhny Tagil      | 2         | 0.32%   |
| Nizhniy Novgorod  | 2         | 0.32%   |
| Murmansk          | 2         | 0.32%   |
| Lipetsk           | 2         | 0.32%   |
| Kostroma          | 2         | 0.32%   |
| Khabarovsk        | 2         | 0.32%   |
| Kemerovo          | 2         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 105       | 145    | 13.22%  |
| Seagate             | 101       | 140    | 12.72%  |
| Samsung Electronics | 83        | 105    | 10.45%  |
| Toshiba             | 52        | 72     | 6.55%   |
| Kingston            | 48        | 54     | 6.05%   |
| Apacer              | 37        | 43     | 4.66%   |
| Intel               | 33        | 42     | 4.16%   |
| BIWIN               | 33        | 34     | 4.16%   |
| SK hynix            | 30        | 32     | 3.78%   |
| AXIOMTEK            | 29        | 31     | 3.65%   |
| A-DATA Technology   | 23        | 27     | 2.9%    |
| Hitachi             | 15        | 16     | 1.89%   |
| China               | 14        | 15     | 1.76%   |
| Unknown             | 10        | 19     | 1.26%   |
| SanDisk             | 10        | 10     | 1.26%   |
| Foxline             | 10        | 10     | 1.26%   |
| Crucial             | 10        | 12     | 1.26%   |
| Phison              | 9         | 10     | 1.13%   |
| HGST                | 9         | 9      | 1.13%   |
| Micron Technology   | 7         | 12     | 0.88%   |
| Gigabyte Technology | 7         | 7      | 0.88%   |
| AMD                 | 7         | 7      | 0.88%   |
| XPG                 | 6         | 7      | 0.76%   |
| Smartbuy            | 5         | 5      | 0.63%   |
| Silicon Motion      | 5         | 6      | 0.63%   |
| Plextor             | 5         | 5      | 0.63%   |
| Patriot             | 5         | 7      | 0.63%   |
| Transcend           | 4         | 5      | 0.5%    |
| Netac               | 4         | 4      | 0.5%    |
| KingSpec            | 4         | 4      | 0.5%    |
| Fujitsu             | 4         | 4      | 0.5%    |
| FORESEE             | 4         | 5      | 0.5%    |
| SPCC                | 3         | 3      | 0.38%   |
| Phison Electronics  | 3         | 3      | 0.38%   |
| External            | 3         | 5      | 0.38%   |
| Unknown             | 3         | 3      | 0.38%   |
| XrayDisk            | 2         | 2      | 0.25%   |
| TMI                 | 2         | 3      | 0.25%   |
| Team                | 2         | 2      | 0.25%   |
| SSSTC               | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| BIWIN CE480T5D101-256 256GB                           | 32        | 3.84%   |
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD                  | 29        | 3.48%   |
| Samsung MZVLW128HEGR-00000 128GB                      | 18        | 2.16%   |
| Apacer AS2280P4 256GB                                 | 18        | 2.16%   |
| Toshiba HDWD120 2TB                                   | 13        | 1.56%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB               | 13        | 1.56%   |
| Seagate ST1000LM049-2GH172 1TB                        | 11        | 1.32%   |
| WDC WD5000AZLX-21K2TA0 500GB                          | 10        | 1.2%    |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB             | 9         | 1.08%   |
| Foxline FLSSD256M80E13TCX5 256GB                      | 9         | 1.08%   |
| Toshiba HDWD110 1TB                                   | 8         | 0.96%   |
| Intel SSDPEMKF256G8H 256GB                            | 8         | 0.96%   |
| Intel SSDPEKKF256G7H 256GB                            | 8         | 0.96%   |
| Toshiba DT01ACA100 1TB                                | 6         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 6         | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB                        | 6         | 0.72%   |
| Samsung SSD 860 EVO 250GB                             | 6         | 0.72%   |
| Kingston SA400S37240G 240GB SSD                       | 6         | 0.72%   |
| Samsung SSD 970 EVO Plus 250GB                        | 5         | 0.6%    |
| Phison 311CD0512GB                                    | 5         | 0.6%    |
| Kingston RBUSC180S37256GJ 256GB SSD                   | 5         | 0.6%    |
| Intel SSDPEKNU512GZ 512GB                             | 5         | 0.6%    |
| Crucial CT240BX500SSD1 240GB                          | 5         | 0.6%    |
| Apacer AS350 256GB SSD                                | 5         | 0.6%    |
| A-DATA SU650 240GB SSD                                | 5         | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 4         | 0.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4         | 0.48%   |
| Seagate ST380815AS 80GB                               | 4         | 0.48%   |
| Seagate ST1000LM048-2E7172 1TB                        | 4         | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 4         | 0.48%   |
| Samsung MZALQ256HAJD-000L2 256GB                      | 4         | 0.48%   |
| Kingston SV300S37A120G 120GB SSD                      | 4         | 0.48%   |
| Kingston SA400S37120G 120GB SSD                       | 4         | 0.48%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB                      | 4         | 0.48%   |
| Apacer AS2280P4 512GB                                 | 4         | 0.48%   |
| XPG SPECTRIX S40G 1TB                                 | 3         | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 3         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 3         | 0.36%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                      | 3         | 0.36%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 134    | 36.94%  |
| WDC                 | 81        | 116    | 30.22%  |
| Toshiba             | 49        | 68     | 18.28%  |
| Hitachi             | 15        | 16     | 5.6%    |
| HGST                | 9         | 9      | 3.36%   |
| Samsung Electronics | 6         | 7      | 2.24%   |
| Fujitsu             | 4         | 4      | 1.49%   |
| External            | 3         | 5      | 1.12%   |
| SINTECHI            | 1         | 1      | 0.37%   |
| Maxtor              | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 34        | 38     | 13.71%  |
| AXIOMTEK            | 29        | 31     | 11.69%  |
| Samsung Electronics | 23        | 26     | 9.27%   |
| A-DATA Technology   | 17        | 19     | 6.85%   |
| WDC                 | 16        | 19     | 6.45%   |
| Apacer              | 15        | 19     | 6.05%   |
| China               | 14        | 15     | 5.65%   |
| Crucial             | 9         | 11     | 3.63%   |
| AMD                 | 6         | 6      | 2.42%   |
| Smartbuy            | 5         | 5      | 2.02%   |
| SanDisk             | 5         | 5      | 2.02%   |
| Plextor             | 5         | 5      | 2.02%   |
| Patriot             | 5         | 7      | 2.02%   |
| Intel               | 5         | 9      | 2.02%   |
| Transcend           | 4         | 5      | 1.61%   |
| Micron Technology   | 4         | 9      | 1.61%   |
| KingSpec            | 4         | 4      | 1.61%   |
| Gigabyte Technology | 3         | 3      | 1.21%   |
| XrayDisk            | 2         | 2      | 0.81%   |
| TMI                 | 2         | 3      | 0.81%   |
| Team                | 2         | 2      | 0.81%   |
| SK hynix            | 2         | 2      | 0.81%   |
| Seagate             | 2         | 6      | 0.81%   |
| PNY                 | 2         | 2      | 0.81%   |
| Phison              | 2         | 2      | 0.81%   |
| Netac               | 2         | 2      | 0.81%   |
| GOODRAM             | 2         | 2      | 0.81%   |
| Foxline             | 2         | 2      | 0.81%   |
| DEPO                | 2         | 2      | 0.81%   |
| Unknown             | 2         | 2      | 0.81%   |
| SPCC                | 1         | 1      | 0.4%    |
| SP-8                | 1         | 1      | 0.4%    |
| SABRENT             | 1         | 1      | 0.4%    |
| Qumo                | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 1      | 0.4%    |
| MaiChai             | 1         | 1      | 0.4%    |
| LuminouTek          | 1         | 1      | 0.4%    |
| LITEON              | 1         | 1      | 0.4%    |
| KingDian            | 1         | 1      | 0.4%    |
| HYDRA               | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 257       | 309    | 34.92%  |
| HDD  | 238       | 361    | 32.34%  |
| SSD  | 229       | 290    | 31.11%  |
| MMC  | 12        | 20     | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 388       | 636    | 58%     |
| NVMe | 256       | 307    | 38.27%  |
| SAS  | 13        | 17     | 1.94%   |
| MMC  | 12        | 20     | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 304       | 393    | 64.82%  |
| 0.51-1.0   | 119       | 173    | 25.37%  |
| 1.01-2.0   | 34        | 71     | 7.25%   |
| 2.01-3.0   | 5         | 6      | 1.07%   |
| 3.01-4.0   | 3         | 3      | 0.64%   |
| 4.01-10.0  | 3         | 4      | 0.64%   |
| 0          | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 315       | 49.07%  |
| 251-500        | 102       | 15.89%  |
| 1001-2000      | 50        | 7.79%   |
| 501-1000       | 47        | 7.32%   |
| 51-100         | 47        | 7.32%   |
| 21-50          | 29        | 4.52%   |
| 1-20           | 25        | 3.89%   |
| More than 3000 | 12        | 1.87%   |
| 2001-3000      | 12        | 1.87%   |
| Unknown        | 3         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 337       | 52.09%  |
| 21-50          | 140       | 21.64%  |
| 51-100         | 56        | 8.66%   |
| 101-250        | 47        | 7.26%   |
| 251-500        | 23        | 3.55%   |
| 501-1000       | 22        | 3.4%    |
| 1001-2000      | 11        | 1.7%    |
| More than 3000 | 5         | 0.77%   |
| 2001-3000      | 3         | 0.46%   |
| Unknown        | 3         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                  | Computers | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB                              | 3         | 3      | 5.17%   |
| Seagate ST380815AS 80GB                                | 2         | 2      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 7      | 3.45%   |
| XrayDisk 512GB SSD                                     | 1         | 1      | 1.72%   |
| XrayDisk 240GB SSD                                     | 1         | 1      | 1.72%   |
| WDC WD7501AALS-00E3A0 752GB                            | 1         | 1      | 1.72%   |
| WDC WD7500AAKS-00RBA0 752GB                            | 1         | 2      | 1.72%   |
| WDC WD5000LPVX-60V0TT0 500GB                           | 1         | 1      | 1.72%   |
| WDC WD5000LPLX-60ZNTT2 500GB                           | 1         | 1      | 1.72%   |
| WDC WD5000AAKX-001CA0 500GB                            | 1         | 1      | 1.72%   |
| WDC WD3200AAKS-00V1A0 320GB                            | 1         | 1      | 1.72%   |
| WDC WD2500KS-00MJB0 250GB                              | 1         | 1      | 1.72%   |
| WDC WD2500BEVT-60ZCT1 250GB                            | 1         | 3      | 1.72%   |
| WDC WD20EARX-008FB0 2TB                                | 1         | 1      | 1.72%   |
| WDC WD2005FBYZ-01YCBB3 2TB                             | 1         | 1      | 1.72%   |
| WDC WD1200BEVS-60UST0 120GB                            | 1         | 1      | 1.72%   |
| WDC WD1003FBYX-01Y7B0 1TB                              | 1         | 1      | 1.72%   |
| Toshiba MQ01ABD050 500GB                               | 1         | 1      | 1.72%   |
| Toshiba MK1637GSX 160GB                                | 1         | 1      | 1.72%   |
| Toshiba DT01ACA050 500GB                               | 1         | 1      | 1.72%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                  | 1         | 1      | 1.72%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                | 1         | 1      | 1.72%   |
| Shenzhen Longsys Electronics FORESEE XP1000F512G 512GB | 1         | 1      | 1.72%   |
| Seagate STM3500418AS 500GB                             | 1         | 1      | 1.72%   |
| Seagate ST9640320AS 640GB                              | 1         | 1      | 1.72%   |
| Seagate ST9500530NS 42D0743 42D0746IBM 500GB           | 1         | 1      | 1.72%   |
| Seagate ST9500325AS 500GB                              | 1         | 1      | 1.72%   |
| Seagate ST9320423AS 320GB                              | 1         | 1      | 1.72%   |
| Seagate ST380811AS 80GB                                | 1         | 1      | 1.72%   |
| Seagate ST3320418AS 320GB                              | 1         | 1      | 1.72%   |
| Seagate ST32000641AS 2TB                               | 1         | 2      | 1.72%   |
| Seagate ST3000DM001-1CH166 3TB                         | 1         | 1      | 1.72%   |
| Seagate ST250DM000-1BD141 250GB                        | 1         | 2      | 1.72%   |
| Seagate ST1000DL004 HD105SI 1TB                        | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 870 EVO 500GB                  | 1         | 1      | 1.72%   |
| Samsung Electronics HD250HJ 250GB                      | 1         | 1      | 1.72%   |
| Netac SSD 480GB                                        | 1         | 1      | 1.72%   |
| Intel SSDSCKKF256H6H 256GB                             | 1         | 1      | 1.72%   |
| Intel SSDSC2BW480A4 480GB                              | 1         | 1      | 1.72%   |
| Hitachi HUA722010CLA330 1TB                            | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 18        | 25     | 31.03%  |
| WDC                          | 12        | 15     | 20.69%  |
| Hitachi                      | 8         | 9      | 13.79%  |
| Toshiba                      | 3         | 3      | 5.17%   |
| XrayDisk                     | 2         | 2      | 3.45%   |
| SK hynix                     | 2         | 2      | 3.45%   |
| Samsung Electronics          | 2         | 2      | 3.45%   |
| Intel                        | 2         | 2      | 3.45%   |
| HGST                         | 2         | 2      | 3.45%   |
| AMD                          | 2         | 2      | 3.45%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.72%   |
| Netac                        | 1         | 1      | 1.72%   |
| Fujitsu                      | 1         | 1      | 1.72%   |
| DEPO                         | 1         | 1      | 1.72%   |
| Corsair                      | 1         | 3      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 25     | 40%     |
| WDC                 | 12        | 15     | 26.67%  |
| Hitachi             | 8         | 9      | 17.78%  |
| Toshiba             | 3         | 3      | 6.67%   |
| HGST                | 2         | 2      | 4.44%   |
| Samsung Electronics | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 56     | 76.36%  |
| SSD  | 11        | 13     | 20%     |
| NVMe | 2         | 2      | 3.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5001AALS-00E3A0 500GB     | 1         | 1      | 50%     |
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 467       | 666    | 72.18%  |
| Detected | 124       | 241    | 19.17%  |
| Malfunc  | 54        | 71     | 8.35%   |
| Failed   | 2         | 2      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 474       | 55.9%   |
| AMD                              | 79        | 9.32%   |
| Samsung Electronics              | 55        | 6.49%   |
| Phison Electronics               | 43        | 5.07%   |
| INNOGRIT                         | 33        | 3.89%   |
| SK hynix                         | 27        | 3.18%   |
| Kingston Technology Company      | 17        | 2%      |
| Nvidia                           | 15        | 1.77%   |
| SanDisk                          | 14        | 1.65%   |
| JMicron Technology               | 10        | 1.18%   |
| Silicon Motion                   | 8         | 0.94%   |
| Realtek Semiconductor            | 8         | 0.94%   |
| Broadcom / LSI                   | 8         | 0.94%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.83%   |
| ASMedia Technology               | 7         | 0.83%   |
| Shenzhen Longsys Electronics     | 6         | 0.71%   |
| Marvell Technology Group         | 5         | 0.59%   |
| ADATA Technology                 | 4         | 0.47%   |
| VIA Technologies                 | 3         | 0.35%   |
| Toshiba America Info Systems     | 3         | 0.35%   |
| Micron Technology                | 3         | 0.35%   |
| MCST                             | 3         | 0.35%   |
| KIOXIA                           | 3         | 0.35%   |
| Solid State Storage Technology   | 2         | 0.24%   |
| Micron/Crucial Technology        | 2         | 0.24%   |
| LSI Logic / Symbios Logic        | 2         | 0.24%   |
| Zhaoxin                          | 1         | 0.12%   |
| Yangtze Memory Technologies      | 1         | 0.12%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.12%   |
| Netac Technology                 | 1         | 0.12%   |
| Jiangsu Huacun Elec.             | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |
| Adaptec                          | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 74        | 7.66%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 60        | 6.21%   |
| Intel Tiger Lake-LP SATA Controller                                            | 52        | 5.38%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 39        | 4.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 34        | 3.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 33        | 3.42%   |
| INNOGRIT NVMe SSD Controller IG5216 (DRAM-less)                                | 33        | 3.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 21        | 2.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 20        | 2.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 1.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 1.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 18        | 1.86%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 15        | 1.55%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13        | 1.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 1.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 12        | 1.24%   |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 1.24%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 11        | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.04%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 9         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 0.93%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 9         | 0.93%   |
| Intel SSD 600P Series                                                          | 9         | 0.93%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 8         | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 0.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 0.83%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 7         | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                             | 7         | 0.72%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 7         | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 0.72%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 6         | 0.62%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 6         | 0.62%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 6         | 0.62%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 487       | 56.43%  |
| NVMe | 256       | 29.66%  |
| IDE  | 78        | 9.04%   |
| RAID | 41        | 4.75%   |
| SAS  | 1         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 498       | 80.58%  |
| AMD          | 111       | 17.96%  |
| ARM          | 4         | 0.65%   |
| CentaurHauls | 2         | 0.32%   |
| Elbrus-MCST  | 1         | 0.16%   |
| E8C/EATX     | 1         | 0.16%   |
| E8C-SWTX     | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 54        | 8.71%   |
| Intel Core i3-6100TE CPU @ 2.70GHz            | 46        | 7.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 24        | 3.87%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 19        | 3.06%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 14        | 2.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 2.1%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 12        | 1.94%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 11        | 1.77%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 10        | 1.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.61%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 8         | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.29%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 0.97%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 6         | 0.97%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz          | 5         | 0.81%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 5         | 0.81%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 0.81%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 5         | 0.81%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 4         | 0.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.65%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 0.65%   |
| ARM Processor                                 | 4         | 0.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.65%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.65%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.65%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 3         | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.48%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.48%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 3         | 0.48%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.48%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.48%   |
| Intel Celeron CPU G3900 @ 2.80GHz             | 3         | 0.48%   |
| Intel 12th Gen Core i5-12400                  | 3         | 0.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.48%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.48%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 2         | 0.32%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 2         | 0.32%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 130       | 21%     |
| Intel Core i3           | 115       | 18.58%  |
| Other                   | 94        | 15.19%  |
| AMD Ryzen 5             | 36        | 5.82%   |
| Intel Core i7           | 35        | 5.65%   |
| Intel Celeron           | 26        | 4.2%    |
| Intel Pentium           | 22        | 3.55%   |
| AMD Ryzen 7             | 22        | 3.55%   |
| Intel Core 2 Duo        | 19        | 3.07%   |
| Intel Xeon              | 10        | 1.62%   |
| Intel Pentium Dual-Core | 8         | 1.29%   |
| Intel Atom              | 8         | 1.29%   |
| AMD A8                  | 7         | 1.13%   |
| Intel Xeon Silver       | 6         | 0.97%   |
| Intel Pentium Gold      | 6         | 0.97%   |
| Intel Core 2 Quad       | 6         | 0.97%   |
| AMD A10                 | 6         | 0.97%   |
| AMD Athlon 64 X2        | 5         | 0.81%   |
| Intel Genuine           | 4         | 0.65%   |
| Intel Core i9           | 4         | 0.65%   |
| AMD Ryzen 3             | 4         | 0.65%   |
| AMD A6                  | 4         | 0.65%   |
| Intel Pentium Silver    | 3         | 0.48%   |
| AMD FX                  | 3         | 0.48%   |
| AMD Athlon              | 3         | 0.48%   |
| AMD Ryzen 9             | 2         | 0.32%   |
| AMD Phenom II X4        | 2         | 0.32%   |
| AMD E1                  | 2         | 0.32%   |
| AMD Athlon II X4        | 2         | 0.32%   |
| AMD Athlon II X2        | 2         | 0.32%   |
| Intel Xeon Gold         | 1         | 0.16%   |
| Intel Pentium Dual      | 1         | 0.16%   |
| Intel Pentium D         | 1         | 0.16%   |
| Intel Pentium 4         | 1         | 0.16%   |
| Intel Core m5           | 1         | 0.16%   |
| Intel Core Duo          | 1         | 0.16%   |
| Intel Core 2 Solo       | 1         | 0.16%   |
| Intel Core 2            | 1         | 0.16%   |
| Intel Celeron M         | 1         | 0.16%   |
| Intel Celeron Dual-Core | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 237       | 38.29%  |
| 4      | 214       | 34.57%  |
| 6      | 87        | 14.05%  |
| 8      | 35        | 5.65%   |
| 1      | 16        | 2.58%   |
| 10     | 8         | 1.29%   |
| 12     | 7         | 1.13%   |
| 20     | 5         | 0.81%   |
| 16     | 3         | 0.48%   |
| 32     | 2         | 0.32%   |
| 18     | 2         | 0.32%   |
| 3      | 2         | 0.32%   |
| 14     | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 607       | 98.22%  |
| 2      | 9         | 1.46%   |
| 4      | 2         | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 442       | 71.52%  |
| 1      | 176       | 28.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 605       | 97.9%   |
| 32-bit         | 7         | 1.13%   |
| Unknown        | 6         | 0.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 21.28%  |
| 0x806c1    | 59        | 9.44%   |
| 0x506e3    | 54        | 8.64%   |
| 0x906ea    | 35        | 5.6%    |
| 0x1067a    | 23        | 3.68%   |
| 0x806e9    | 21        | 3.36%   |
| 0x806ec    | 20        | 3.2%    |
| 0xa0653    | 18        | 2.88%   |
| 0x806ea    | 16        | 2.56%   |
| 0x08001138 | 14        | 2.24%   |
| 0x906e9    | 13        | 2.08%   |
| 0x0a50000c | 12        | 1.92%   |
| 0x306a9    | 11        | 1.76%   |
| 0x806eb    | 10        | 1.6%    |
| 0x206a7    | 10        | 1.6%    |
| 0x08108109 | 9         | 1.44%   |
| 0xa0660    | 8         | 1.28%   |
| 0x906eb    | 8         | 1.28%   |
| 0x50657    | 8         | 1.28%   |
| 0xa0671    | 6         | 0.96%   |
| 0x906a4    | 6         | 0.96%   |
| 0x306c3    | 6         | 0.96%   |
| 0x906ed    | 5         | 0.8%    |
| 0x706e5    | 5         | 0.8%    |
| 0x506c9    | 5         | 0.8%    |
| 0x406e3    | 5         | 0.8%    |
| 0x08600106 | 5         | 0.8%    |
| 0x06001119 | 5         | 0.8%    |
| 0x906a3    | 4         | 0.64%   |
| 0x6fd      | 4         | 0.64%   |
| 0x20655    | 4         | 0.64%   |
| 0x90675    | 3         | 0.48%   |
| 0x706a8    | 3         | 0.48%   |
| 0x40651    | 3         | 0.48%   |
| 0x106ca    | 3         | 0.48%   |
| 0x906c0    | 2         | 0.32%   |
| 0x806c2    | 2         | 0.32%   |
| 0x706a1    | 2         | 0.32%   |
| 0x6e8      | 2         | 0.32%   |
| 0x406c4    | 2         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 147       | 23.75%  |
| Skylake          | 75        | 12.12%  |
| TigerLake        | 65        | 10.5%   |
| CometLake        | 34        | 5.49%   |
| Penryn           | 28        | 4.52%   |
| Unknown          | 28        | 4.52%   |
| Zen 3            | 23        | 3.72%   |
| SandyBridge      | 22        | 3.55%   |
| IvyBridge        | 22        | 3.55%   |
| Zen              | 16        | 2.58%   |
| Haswell          | 16        | 2.58%   |
| Zen+             | 13        | 2.1%    |
| Alderlake Hybrid | 12        | 1.94%   |
| Westmere         | 11        | 1.78%   |
| Silvermont       | 11        | 1.78%   |
| Core             | 10        | 1.62%   |
| Zen 2            | 9         | 1.45%   |
| K8 Hammer        | 9         | 1.45%   |
| Piledriver       | 8         | 1.29%   |
| K10              | 7         | 1.13%   |
| Icelake          | 7         | 1.13%   |
| Goldmont plus    | 6         | 0.97%   |
| Bonnell          | 6         | 0.97%   |
| Steamroller      | 5         | 0.81%   |
| Goldmont         | 5         | 0.81%   |
| Excavator        | 4         | 0.65%   |
| P6               | 3         | 0.48%   |
| NetBurst         | 3         | 0.48%   |
| Nehalem          | 3         | 0.48%   |
| K10 Llano        | 3         | 0.48%   |
| Tremont          | 2         | 0.32%   |
| Jaguar           | 2         | 0.32%   |
| Bobcat           | 2         | 0.32%   |
| Puma             | 1         | 0.16%   |
| Broadwell        | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 416       | 62.46%  |
| Nvidia                     | 123       | 18.47%  |
| AMD                        | 111       | 16.67%  |
| Matrox Electronics Systems | 5         | 0.75%   |
| ASPEED Technology          | 5         | 0.75%   |
| Silicon Motion             | 2         | 0.3%    |
| Huawei Technologies        | 2         | 0.3%    |
| Zhaoxin                    | 1         | 0.15%   |
| VIA Technologies           | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 58        | 8.45%   |
| Intel HD Graphics 530                                                                    | 54        | 7.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 34        | 4.96%   |
| Intel HD Graphics 620                                                                    | 29        | 4.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 3.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 20        | 2.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19        | 2.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 2.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.6%    |
| Intel HD Graphics 610                                                                    | 10        | 1.46%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 10        | 1.46%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 9         | 1.31%   |
| Intel Comet Lake UHD Graphics                                                            | 8         | 1.17%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 7         | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.02%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 1.02%   |
| Intel UHD Graphics 620                                                                   | 6         | 0.87%   |
| Intel HD Graphics 510                                                                    | 6         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.87%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 6         | 0.87%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 0.73%   |
| Intel HD Graphics 630                                                                    | 5         | 0.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.73%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 0.73%   |
| AMD Lucienne                                                                             | 5         | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.58%   |
| Intel HD Graphics 500                                                                    | 4         | 0.58%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 4         | 0.58%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.58%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.58%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 0.44%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 3         | 0.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.44%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 370       | 59.68%  |
| 1 x AMD                 | 86        | 13.87%  |
| 1 x Nvidia              | 82        | 13.23%  |
| Intel + Nvidia          | 35        | 5.65%   |
| 2 x AMD                 | 13        | 2.1%    |
| Other                   | 6         | 0.97%   |
| Intel + AMD             | 6         | 0.97%   |
| 1 x Matrox              | 5         | 0.81%   |
| 1 x ASPEED              | 5         | 0.81%   |
| AMD + Nvidia            | 5         | 0.81%   |
| 1 x Silicon Motion      | 2         | 0.32%   |
| 1 x Huawei Technologies | 2         | 0.32%   |
| 2 x Intel               | 1         | 0.16%   |
| 1 x VIA                 | 1         | 0.16%   |
| Nvidia + Zhaoxin        | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 529       | 85.05%  |
| Proprietary | 69        | 11.09%  |
| Unknown     | 24        | 3.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 467       | 74.6%   |
| 0.01-0.5   | 49        | 7.83%   |
| 3.01-4.0   | 36        | 5.75%   |
| 0.51-1.0   | 31        | 4.95%   |
| 1.01-2.0   | 30        | 4.79%   |
| 7.01-8.0   | 5         | 0.8%    |
| 8.01-16.0  | 5         | 0.8%    |
| 5.01-6.0   | 2         | 0.32%   |
| 2.01-3.0   | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 68        | 10.63%  |
| Chimei Innolux          | 60        | 9.38%   |
| Samsung Electronics     | 57        | 8.91%   |
| HHT                     | 48        | 7.5%    |
| AU Optronics            | 42        | 6.56%   |
| Acer                    | 36        | 5.63%   |
| AOC                     | 34        | 5.31%   |
| LG Display              | 30        | 4.69%   |
| BenQ                    | 29        | 4.53%   |
| ECS                     | 22        | 3.44%   |
| Goldstar                | 21        | 3.28%   |
| Philips                 | 19        | 2.97%   |
| PANDA                   | 14        | 2.19%   |
| Dell                    | 14        | 2.19%   |
| Lenovo                  | 13        | 2.03%   |
| ViewSonic               | 10        | 1.56%   |
| Sharp                   | 8         | 1.25%   |
| CHR                     | 7         | 1.09%   |
| Chi Mei Optoelectronics | 7         | 1.09%   |
| Hewlett-Packard         | 6         | 0.94%   |
| Apple                   | 6         | 0.94%   |
| Ancor Communications    | 6         | 0.94%   |
| PRM                     | 5         | 0.78%   |
| STA                     | 4         | 0.63%   |
| RTK                     | 4         | 0.63%   |
| PRW                     | 4         | 0.63%   |
| Iiyama                  | 4         | 0.63%   |
| ASUSTek Computer        | 4         | 0.63%   |
| WBT                     | 3         | 0.47%   |
| VIE                     | 3         | 0.47%   |
| LG Electronics          | 3         | 0.47%   |
| HannStar                | 3         | 0.47%   |
| Toshiba                 | 2         | 0.31%   |
| STD                     | 2         | 0.31%   |
| NEC Computers           | 2         | 0.31%   |
| MSI                     | 2         | 0.31%   |
| JRY                     | 2         | 0.31%   |
| AGO                     | 2         | 0.31%   |
| Unknown                 | 2         | 0.31%   |
| ZCS                     | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch              | 48        | 7.38%   |
| ECS AIO PC ECS2486 1920x1080 520x300mm 23.6-inch                     | 22        | 3.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 12        | 1.85%   |
| AOC LCD Monitor 2778X 2560x1440                                      | 11        | 1.69%   |
| Lenovo LEN-V3V5-B-A LENE288 1920x1080 527x296mm 23.8-inch            | 10        | 1.54%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                    | 10        | 1.54%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch              | 9         | 1.38%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch     | 9         | 1.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 9         | 1.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 8         | 1.23%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                       | 8         | 1.23%   |
| CHR CH7511B CHR7511 800x600 519x324mm 24.1-inch                      | 6         | 0.92%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                | 6         | 0.92%   |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                | 6         | 0.92%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 5         | 0.77%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 5         | 0.77%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch       | 5         | 0.77%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch        | 4         | 0.62%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                | 4         | 0.62%   |
| PRW AP7_Titanium PRW4200 3840x2160                                   | 4         | 0.62%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 4         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 4         | 0.62%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 4         | 0.62%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 4         | 0.62%   |
| AOC 22P1W AOC2201 1920x1080 477x268mm 21.5-inch                      | 4         | 0.62%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                     | 3         | 0.46%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 3         | 0.46%   |
| Sharp LCD Monitor SHP1540 1920x1080 309x174mm 14.0-inch              | 3         | 0.46%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 3         | 0.46%   |
| RTK HDMI RTK2380 1920x1080 530x290mm 23.8-inch                       | 3         | 0.46%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch         | 3         | 0.46%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch               | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 0.46%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 3         | 0.46%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                     | 3         | 0.46%   |
| AOC 2475W1 AOC2475 1920x1080 527x296mm 23.8-inch                     | 3         | 0.46%   |
| Acer AIO LCD ACRF132 1920x1080 509x286mm 23.0-inch                   | 3         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 351       | 57.26%  |
| 3840x2160 (4K)     | 63        | 10.28%  |
| 1366x768 (WXGA)    | 51        | 8.32%   |
| 2560x1440 (QHD)    | 32        | 5.22%   |
| 1280x1024 (SXGA)   | 31        | 5.06%   |
| 1600x900 (HD+)     | 18        | 2.94%   |
| 1280x800 (WXGA)    | 13        | 2.12%   |
| 1680x1050 (WSXGA+) | 11        | 1.79%   |
| 1440x900 (WXGA+)   | 7         | 1.14%   |
| 1920x1200 (WUXGA)  | 5         | 0.82%   |
| Unknown            | 5         | 0.82%   |
| 2560x1600          | 4         | 0.65%   |
| 1024x600           | 3         | 0.49%   |
| 3840x1080          | 2         | 0.33%   |
| 2160x1440          | 2         | 0.33%   |
| 1600x1200          | 2         | 0.33%   |
| 1360x768           | 2         | 0.33%   |
| 800x1280           | 1         | 0.16%   |
| 4480x1440          | 1         | 0.16%   |
| 3840x1600          | 1         | 0.16%   |
| 3840x1440          | 1         | 0.16%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 2880x1620          | 1         | 0.16%   |
| 2560x1080          | 1         | 0.16%   |
| 2160x1200          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |
| 1024x768 (XGA)     | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 127       | 20.03%  |
| 23      | 75        | 11.83%  |
| 24      | 60        | 9.46%   |
| 13      | 51        | 8.04%   |
| 40      | 50        | 7.89%   |
| 21      | 45        | 7.1%    |
| 14      | 44        | 6.94%   |
| 17      | 41        | 6.47%   |
| Unknown | 40        | 6.31%   |
| 27      | 26        | 4.1%    |
| 19      | 18        | 2.84%   |
| 12      | 10        | 1.58%   |
| 26      | 6         | 0.95%   |
| 20      | 6         | 0.95%   |
| 31      | 5         | 0.79%   |
| 11      | 5         | 0.79%   |
| 22      | 3         | 0.47%   |
| 18      | 3         | 0.47%   |
| 16      | 3         | 0.47%   |
| 10      | 3         | 0.47%   |
| 85      | 1         | 0.16%   |
| 72      | 1         | 0.16%   |
| 59      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 50      | 1         | 0.16%   |
| 46      | 1         | 0.16%   |
| 39      | 1         | 0.16%   |
| 37      | 1         | 0.16%   |
| 33      | 1         | 0.16%   |
| 32      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |
| 8       | 1         | 0.16%   |
| 7       | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 226       | 36.04%  |
| 501-600     | 157       | 25.04%  |
| 401-500     | 65        | 10.37%  |
| 901-1000    | 49        | 7.81%   |
| Unknown     | 40        | 6.38%   |
| 351-400     | 35        | 5.58%   |
| 201-300     | 31        | 4.94%   |
| 601-700     | 11        | 1.75%   |
| 1001-1500   | 4         | 0.64%   |
| 801-900     | 3         | 0.48%   |
| 701-800     | 2         | 0.32%   |
| 1501-2000   | 2         | 0.32%   |
| 101-200     | 1         | 0.16%   |
| 1-100       | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 433       | 71.93%  |
| 21/9    | 50        | 8.31%   |
| 16/10   | 49        | 8.14%   |
| 5/4     | 29        | 4.82%   |
| Unknown | 26        | 4.32%   |
| 4/3     | 8         | 1.33%   |
| 3/2     | 5         | 0.83%   |
| 6/5     | 1         | 0.17%   |
| 0.67    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 152       | 24.17%  |
| 101-110        | 128       | 20.35%  |
| 81-90          | 88        | 13.99%  |
| 501-1000       | 53        | 8.43%   |
| Unknown        | 40        | 6.36%   |
| 151-200        | 36        | 5.72%   |
| 301-350        | 32        | 5.09%   |
| 121-130        | 23        | 3.66%   |
| 141-150        | 19        | 3.02%   |
| 251-300        | 15        | 2.38%   |
| 71-80          | 10        | 1.59%   |
| 351-500        | 8         | 1.27%   |
| 61-70          | 7         | 1.11%   |
| More than 1000 | 5         | 0.79%   |
| 51-60          | 5         | 0.79%   |
| 41-50          | 3         | 0.48%   |
| 1-40           | 2         | 0.32%   |
| 111-120        | 2         | 0.32%   |
| 131-140        | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 206       | 32.96%  |
| 121-160       | 204       | 32.64%  |
| 101-120       | 149       | 23.84%  |
| Unknown       | 40        | 6.4%    |
| 161-240       | 17        | 2.72%   |
| 1-50          | 7         | 1.12%   |
| More than 240 | 2         | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 542       | 86.86%  |
| 2     | 58        | 9.29%   |
| 0     | 22        | 3.53%   |
| 3     | 2         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 375       | 42.52%  |
| Intel                           | 318       | 36.05%  |
| Qualcomm Atheros                | 59        | 6.69%   |
| Broadcom                        | 28        | 3.17%   |
| Nvidia                          | 14        | 1.59%   |
| Marvell Technology Group        | 10        | 1.13%   |
| D-Link                          | 9         | 1.02%   |
| MediaTek                        | 8         | 0.91%   |
| Ralink Technology               | 5         | 0.57%   |
| IBM                             | 5         | 0.57%   |
| Broadcom Limited                | 5         | 0.57%   |
| TP-Link                         | 4         | 0.45%   |
| Ralink                          | 4         | 0.45%   |
| ASIX Electronics                | 4         | 0.45%   |
| Xiaomi                          | 3         | 0.34%   |
| Microchip Technology            | 3         | 0.34%   |
| MCST                            | 3         | 0.34%   |
| JMicron Technology              | 3         | 0.34%   |
| Huawei Technologies             | 3         | 0.34%   |
| ASUSTek Computer                | 3         | 0.34%   |
| VIA Technologies                | 2         | 0.23%   |
| Sierra Wireless                 | 2         | 0.23%   |
| Qualcomm                        | 2         | 0.23%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.11%   |
| Vimtron Electronics             | 1         | 0.11%   |
| U-Blox                          | 1         | 0.11%   |
| Samsung Electronics             | 1         | 0.11%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| Exar                            | 1         | 0.11%   |
| DisplayLink                     | 1         | 0.11%   |
| Attansic Technology             | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 265       | 24.77%  |
| Intel Wi-Fi 6 AX201                                               | 55        | 5.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 48        | 4.49%   |
| Intel Ethernet Connection (13) I219-V                             | 45        | 4.21%   |
| Intel Ethernet Connection I219-LM                                 | 37        | 3.46%   |
| Intel Wireless 3165                                               | 22        | 2.06%   |
| Intel Wi-Fi 6 AX200                                               | 19        | 1.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 1.68%   |
| Intel Wireless 8265 / 8275                                        | 17        | 1.59%   |
| Intel Wireless 7265                                               | 17        | 1.59%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 1.31%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 12        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.65%   |
| Intel Ethernet Connection X722 for 1GbE                           | 7         | 0.65%   |
| Intel Ethernet Connection (14) I219-V                             | 7         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.56%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 6         | 0.56%   |
| Intel Ethernet Connection (17) I219-V                             | 6         | 0.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 5         | 0.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 5         | 0.47%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 5         | 0.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 0.47%   |
| IBM RNDIS/Ethernet Gadget                                         | 5         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 225       | 57.54%  |
| Realtek Semiconductor           | 71        | 18.16%  |
| Qualcomm Atheros                | 40        | 10.23%  |
| Broadcom                        | 21        | 5.37%   |
| MediaTek                        | 8         | 2.05%   |
| Ralink Technology               | 5         | 1.28%   |
| TP-Link                         | 4         | 1.02%   |
| Ralink                          | 4         | 1.02%   |
| Broadcom Limited                | 3         | 0.77%   |
| ASUSTek Computer                | 3         | 0.77%   |
| Sierra Wireless                 | 2         | 0.51%   |
| D-Link                          | 2         | 0.51%   |
| Qualcomm Atheros Communications | 1         | 0.26%   |
| Qualcomm                        | 1         | 0.26%   |
| Micro Star International        | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 55        | 14.03%  |
| Intel Wireless 3165                                                     | 22        | 5.61%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 4.85%   |
| Intel Wireless 8265 / 8275                                              | 17        | 4.34%   |
| Intel Wireless 7265                                                     | 17        | 4.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 3.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 3.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 3.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 3.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 1.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.02%   |
| Realtek 802.11ac NIC                                                    | 4         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.77%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.77%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.77%   |
| Intel WiFi Link 5100                                                    | 3         | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.77%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.51%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 350       | 54.1%   |
| Intel                      | 196       | 30.29%  |
| Qualcomm Atheros           | 28        | 4.33%   |
| Nvidia                     | 14        | 2.16%   |
| Marvell Technology Group   | 10        | 1.55%   |
| Broadcom                   | 10        | 1.55%   |
| D-Link                     | 7         | 1.08%   |
| IBM                        | 5         | 0.77%   |
| ASIX Electronics           | 4         | 0.62%   |
| Xiaomi                     | 3         | 0.46%   |
| MCST                       | 3         | 0.46%   |
| JMicron Technology         | 3         | 0.46%   |
| Huawei Technologies        | 3         | 0.46%   |
| VIA Technologies           | 2         | 0.31%   |
| Broadcom Limited           | 2         | 0.31%   |
| ZTE WCDMA Technologies MSM | 1         | 0.15%   |
| Vimtron Electronics        | 1         | 0.15%   |
| TP-Link                    | 1         | 0.15%   |
| Samsung Electronics        | 1         | 0.15%   |
| Qualcomm                   | 1         | 0.15%   |
| DisplayLink                | 1         | 0.15%   |
| Attansic Technology        | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 265       | 39.49%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 48        | 7.15%   |
| Intel Ethernet Connection (13) I219-V                             | 45        | 6.71%   |
| Intel Ethernet Connection I219-LM                                 | 37        | 5.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 2.68%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 2.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 2.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 1.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.34%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.04%   |
| Intel Ethernet Connection X722 for 1GbE                           | 7         | 1.04%   |
| Intel Ethernet Connection (14) I219-V                             | 7         | 1.04%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 6         | 0.89%   |
| Intel Ethernet Connection (17) I219-V                             | 6         | 0.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 5         | 0.75%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 5         | 0.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 0.75%   |
| IBM RNDIS/Ethernet Gadget                                         | 5         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.6%    |
| Intel I350 Gigabit Network Connection                             | 4         | 0.6%    |
| Intel I211 Gigabit Network Connection                             | 4         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.6%    |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.45%   |
| Nvidia MCP77 Ethernet                                             | 3         | 0.45%   |
| Nvidia MCP51 Ethernet Controller                                  | 3         | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.45%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.45%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 3         | 0.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.3%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 569       | 59.39%  |
| WiFi     | 382       | 39.87%  |
| Modem    | 6         | 0.63%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 342       | 54.37%  |
| WiFi     | 287       | 45.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 315       | 50.89%  |
| 1     | 277       | 44.75%  |
| 0     | 12        | 1.94%   |
| 6     | 5         | 0.81%   |
| 3     | 4         | 0.65%   |
| 4     | 3         | 0.48%   |
| 13    | 1         | 0.16%   |
| 12    | 1         | 0.16%   |
| 8     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 591       | 95.48%  |
| Yes  | 28        | 4.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 208       | 62.65%  |
| Realtek Semiconductor           | 27        | 8.13%   |
| IMC Networks                    | 19        | 5.72%   |
| Cambridge Silicon Radio         | 14        | 4.22%   |
| Broadcom                        | 14        | 4.22%   |
| Qualcomm Atheros Communications | 8         | 2.41%   |
| Foxconn / Hon Hai               | 8         | 2.41%   |
| Lite-On Technology              | 7         | 2.11%   |
| Hewlett-Packard                 | 5         | 1.51%   |
| Realtek                         | 4         | 1.2%    |
| ASUSTek Computer                | 4         | 1.2%    |
| Apple                           | 4         | 1.2%    |
| Foxconn International           | 2         | 0.6%    |
| USI                             | 1         | 0.3%    |
| Toshiba                         | 1         | 0.3%    |
| Ralink                          | 1         | 0.3%    |
| Opticis                         | 1         | 0.3%    |
| MediaTek                        | 1         | 0.3%    |
| Logitech                        | 1         | 0.3%    |
| HTC (High Tech Computer)        | 1         | 0.3%    |
| Chicony Electronics             | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 66        | 19.88%  |
| Intel AX201 Bluetooth                               | 62        | 18.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 12.65%  |
| Realtek Bluetooth Radio                             | 20        | 6.02%   |
| Intel AX200 Bluetooth                               | 19        | 5.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14        | 4.22%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 3.61%   |
| IMC Networks Wireless_Device                        | 7         | 2.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.51%   |
| IMC Networks Bluetooth Device                       | 5         | 1.51%   |
| Realtek Bluetooth Radio                             | 4         | 1.2%    |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.2%    |
| IMC Networks Bluetooth Radio                        | 4         | 1.2%    |
| Broadcom BCM2045 Bluetooth                          | 4         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.9%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.9%    |
| Apple Bluetooth Host Controller                     | 3         | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.6%    |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.6%    |
| Intel AX210 Bluetooth                               | 2         | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.6%    |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.6%    |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.6%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.6%    |
| USI Bluetooth Module BCM92070                       | 1         | 0.3%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.3%    |
| Realtek RTL8821A Bluetooth                          | 1         | 0.3%    |
| Realtek RTL8723A Bluetooth                          | 1         | 0.3%    |
| Ralink RT3290 Bluetooth                             | 1         | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.3%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.3%    |
| Opticis Bluetooth Radio                             | 1         | 0.3%    |
| MediaTek Wireless_Device                            | 1         | 0.3%    |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.3%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.3%    |
| Lite-On Bluetooth Radio                             | 1         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 478       | 61.36%  |
| AMD                                          | 122       | 15.66%  |
| Nvidia                                       | 98        | 12.58%  |
| C-Media Electronics                          | 43        | 5.52%   |
| Promethean Limited                           | 7         | 0.9%    |
| VIA Technologies                             | 3         | 0.39%   |
| MCST                                         | 3         | 0.39%   |
| JMTek                                        | 3         | 0.39%   |
| Creative Technology                          | 3         | 0.39%   |
| Realtek Semiconductor                        | 2         | 0.26%   |
| Logitech                                     | 2         | 0.26%   |
| Generalplus Technology                       | 2         | 0.26%   |
| Apple                                        | 2         | 0.26%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.13%   |
| Zhaoxin                                      | 1         | 0.13%   |
| Texas Instruments                            | 1         | 0.13%   |
| KTMicro                                      | 1         | 0.13%   |
| Goldvish                                     | 1         | 0.13%   |
| Focusrite-Novation                           | 1         | 0.13%   |
| FIFINE Microphones                           | 1         | 0.13%   |
| EasyPass Industrial                          | 1         | 0.13%   |
| Creative Labs                                | 1         | 0.13%   |
| ASUSTek Computer                             | 1         | 0.13%   |
| A4Tech                                       | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 74        | 8.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 65        | 7.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 42        | 4.87%   |
| Intel Sunrise Point-LP HD Audio                                            | 40        | 4.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 36        | 4.17%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 3.82%   |
| C-Media Electronics USB Advanced Audio Device                              | 33        | 3.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 30        | 3.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 28        | 3.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25        | 2.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 2.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19        | 2.2%    |
| AMD FCH Azalia Controller                                                  | 17        | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16        | 1.85%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 15        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9         | 1.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9         | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 8         | 0.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 0.93%   |
| Promethean Limited Audio                                                   | 7         | 0.81%   |
| Intel Comet Lake PCH-V cAVS                                                | 7         | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 7         | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.7%    |
| Intel Alder Lake-S HD Audio Controller                                     | 6         | 0.7%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 6         | 0.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5         | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 92        | 18.11%  |
| Crucial                      | 75        | 14.76%  |
| SK hynix                     | 56        | 11.02%  |
| Unknown                      | 52        | 10.24%  |
| Kingston                     | 48        | 9.45%   |
| Micron Technology            | 34        | 6.69%   |
| ACPI Digital                 | 32        | 6.3%    |
| A-DATA Technology            | 17        | 3.35%   |
| Ramaxel Technology           | 16        | 3.15%   |
| Foxline                      | 12        | 2.36%   |
| Apacer                       | 11        | 2.17%   |
| Unknown                      | 7         | 1.38%   |
| Elpida                       | 6         | 1.18%   |
| AMD                          | 6         | 1.18%   |
| Unknown (ABCD)               | 5         | 0.98%   |
| Patriot                      | 5         | 0.98%   |
| Corsair                      | 5         | 0.98%   |
| GOODRAM                      | 4         | 0.79%   |
| Lexar Co Limited             | 3         | 0.59%   |
| ChangXin Memory              | 3         | 0.59%   |
| Shenzhen Longsys             | 2         | 0.39%   |
| Goldkey                      | 2         | 0.39%   |
| G.Skill                      | 2         | 0.39%   |
| Wilk                         | 1         | 0.2%    |
| Unknown (0x7FFF)             | 1         | 0.2%    |
| Unknown (0x0B92)             | 1         | 0.2%    |
| Unknown (0x0B7A)             | 1         | 0.2%    |
| Unknown (081A)               | 1         | 0.2%    |
| tigo                         | 1         | 0.2%    |
| Shenzhen Giant Hui Kang Tech | 1         | 0.2%    |
| SHARETRONIC                  | 1         | 0.2%    |
| Qumo                         | 1         | 0.2%    |
| Kimtigo                      | 1         | 0.2%    |
| Juhor                        | 1         | 0.2%    |
| Golden Empire                | 1         | 0.2%    |
| ATLA                         | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 32        | 6.07%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s          | 17        | 3.23%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 2.47%   |
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s             | 13        | 2.47%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 10        | 1.9%    |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10        | 1.9%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 1.71%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 7         | 1.33%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 7         | 1.33%   |
| Unknown                                                          | 7         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.14%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 0.95%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.95%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 5         | 0.95%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 4         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.76%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.76%   |
| Samsung RAM M393A2K43CB2-CVF 16384MB DIMM DDR4 2933MT/s          | 4         | 0.76%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4         | 0.76%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 4         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.57%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 3         | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.57%   |
| Lexar Co Limited RAM LD4AS008G-3200ST 8GB SODIMM DDR4 3200MT/s   | 3         | 0.57%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s           | 3         | 0.57%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.57%   |
| Crucial RAM CT8G4SFRA266.C16FG 8GB SODIMM DDR4 2667MT/s          | 3         | 0.57%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s           | 3         | 0.57%   |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s              | 3         | 0.57%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 3         | 0.57%   |
| Apacer RAM D12.2755BS.001 16GB DIMM DDR4 3200MT/s                | 3         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 327       | 68.84%  |
| DDR3    | 72        | 15.16%  |
| DDR2    | 26        | 5.47%   |
| Unknown | 18        | 3.79%   |
| LPDDR4  | 17        | 3.58%   |
| SDRAM   | 6         | 1.26%   |
| DDR     | 3         | 0.63%   |
| LPDDR5  | 2         | 0.42%   |
| DDR5    | 2         | 0.42%   |
| LPDDR3  | 1         | 0.21%   |
| DRAM    | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 289       | 60.59%  |
| DIMM         | 163       | 34.17%  |
| Row Of Chips | 25        | 5.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 214       | 43.67%  |
| 4096  | 126       | 25.71%  |
| 16384 | 77        | 15.71%  |
| 2048  | 42        | 8.57%   |
| 1024  | 20        | 4.08%   |
| 512   | 5         | 1.02%   |
| 32768 | 4         | 0.82%   |
| 65536 | 1         | 0.2%    |
| 1536  | 1         | 0.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 119       | 23.94%  |
| 3200    | 113       | 22.74%  |
| 2400    | 56        | 11.27%  |
| 1600    | 44        | 8.85%   |
| 2133    | 27        | 5.43%   |
| 667     | 15        | 3.02%   |
| 1333    | 14        | 2.82%   |
| 2933    | 12        | 2.41%   |
| Unknown | 12        | 2.41%   |
| 1334    | 10        | 2.01%   |
| 800     | 10        | 2.01%   |
| 3266    | 8         | 1.61%   |
| 3733    | 5         | 1.01%   |
| 4267    | 4         | 0.8%    |
| 1067    | 4         | 0.8%    |
| 533     | 4         | 0.8%    |
| 400     | 4         | 0.8%    |
| 3466    | 3         | 0.6%    |
| 1866    | 3         | 0.6%    |
| 333     | 3         | 0.6%    |
| 6400    | 2         | 0.4%    |
| 4800    | 2         | 0.4%    |
| 3066    | 2         | 0.4%    |
| 2666    | 2         | 0.4%    |
| 1867    | 2         | 0.4%    |
| 1066    | 2         | 0.4%    |
| 4333    | 1         | 0.2%    |
| 4199    | 1         | 0.2%    |
| 3866    | 1         | 0.2%    |
| 3600    | 1         | 0.2%    |
| 3534    | 1         | 0.2%    |
| 3533    | 1         | 0.2%    |
| 3333    | 1         | 0.2%    |
| 3151    | 1         | 0.2%    |
| 3000    | 1         | 0.2%    |
| 2866    | 1         | 0.2%    |
| 2800    | 1         | 0.2%    |
| 2448    | 1         | 0.2%    |
| 1800    | 1         | 0.2%    |
| 1648    | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Canon                  | 11        | 28.21%  |
| Samsung Electronics    | 9         | 23.08%  |
| Hewlett-Packard        | 6         | 15.38%  |
| Pantum                 | 3         | 7.69%   |
| Xerox                  | 2         | 5.13%   |
| Ricoh                  | 2         | 5.13%   |
| QinHeng Electronics    | 2         | 5.13%   |
| Brother Industries     | 2         | 5.13%   |
| Seiko Epson            | 1         | 2.56%   |
| Panasonic (Matsushita) | 1         | 2.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SCX-3400 Series              | 4         | 10.26%  |
| QinHeng CH340S                       | 2         | 5.13%   |
| Pantum P2200 series                  | 2         | 5.13%   |
| HP LaserJet P1102                    | 2         | 5.13%   |
| HP LaserJet 1010                     | 2         | 5.13%   |
| Canon MF4410                         | 2         | 5.13%   |
| Canon MF4010 series                  | 2         | 5.13%   |
| Brother HL-L2300D series             | 2         | 5.13%   |
| Xerox WorkCentre 5222                | 1         | 2.56%   |
| Xerox WorkCentre 3220                | 1         | 2.56%   |
| Seiko Epson L132 Series              | 1         | 2.56%   |
| Samsung SCX-4200 series              | 1         | 2.56%   |
| Samsung SCX-3200 Series              | 1         | 2.56%   |
| Samsung ML-1640 Series Laser Printer | 1         | 2.56%   |
| Samsung M332x 382x 402x Series       | 1         | 2.56%   |
| Samsung CLX-3180 Series              | 1         | 2.56%   |
| Ricoh SP 210SU                       | 1         | 2.56%   |
| Ricoh Aficio SP C240DN               | 1         | 2.56%   |
| Pantum M6500-series                  | 1         | 2.56%   |
| Panasonic (Matsushita) KX-MB283RU    | 1         | 2.56%   |
| HP LaserJet M402dn                   | 1         | 2.56%   |
| HP LaserJet 3055                     | 1         | 2.56%   |
| Canon PIXMA MP190                    | 1         | 2.56%   |
| Canon MF420 Series                   | 1         | 2.56%   |
| Canon MF3110                         | 1         | 2.56%   |
| Canon imageRUNNER1133 series         | 1         | 2.56%   |
| Canon I-SENSYS MF4550d               | 1         | 2.56%   |
| Canon G3010 series                   | 1         | 2.56%   |
| Canon G1010 series                   | 1         | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 66.67%  |
| Canon CanoScan LIDE 25  | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 69        | 19.33%  |
| Acer                                   | 38        | 10.64%  |
| Cheng Uei Precision Industry (Foxlink) | 33        | 9.24%   |
| IMC Networks                           | 29        | 8.12%   |
| Realtek Semiconductor                  | 24        | 6.72%   |
| Alcor Micro                            | 24        | 6.72%   |
| Logitech                               | 22        | 6.16%   |
| Sunplus Innovation Technology          | 19        | 5.32%   |
| Microdia                               | 13        | 3.64%   |
| Bison Electronics                      | 13        | 3.64%   |
| Quanta                                 | 12        | 3.36%   |
| Syntek                                 | 10        | 2.8%    |
| Suyin                                  | 10        | 2.8%    |
| Apple                                  | 6         | 1.68%   |
| lihappe8                               | 5         | 1.4%    |
| Z-Star Microelectronics                | 4         | 1.12%   |
| Sonix Technology                       | 3         | 0.84%   |
| Luxvisions Innotech Limited            | 3         | 0.84%   |
| Unknown                                | 2         | 0.56%   |
| Silicon Motion                         | 2         | 0.56%   |
| Microsoft                              | 2         | 0.56%   |
| Lite-On Technology                     | 2         | 0.56%   |
| Y Media                                | 1         | 0.28%   |
| SunplusIT                              | 1         | 0.28%   |
| Ricoh                                  | 1         | 0.28%   |
| Primax Electronics                     | 1         | 0.28%   |
| Importek                               | 1         | 0.28%   |
| icSpring                               | 1         | 0.28%   |
| Hewlett-Packard                        | 1         | 0.28%   |
| GEMBIRD                                | 1         | 0.28%   |
| DX-221104-A                            | 1         | 0.28%   |
| BRS 2Mp Camera                         | 1         | 0.28%   |
| ALi                                    | 1         | 0.28%   |
| Unknown                                | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Acer BisonCam,NB Pro                                                   | 33        | 9.17%   |
| Alcor Micro USB 2.0 PC Camera                                          | 21        | 5.83%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera         | 15        | 4.17%   |
| Chicony Integrated Camera                                              | 14        | 3.89%   |
| Logitech Webcam C270                                                   | 12        | 3.33%   |
| Chicony HP HD Camera                                                   | 11        | 3.06%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                          | 11        | 3.06%   |
| IMC Networks USB2.0 HD UVC WebCam                                      | 10        | 2.78%   |
| Realtek USB2.0 camera                                                  | 9         | 2.5%    |
| Syntek Integrated Camera                                               | 7         | 1.94%   |
| Sunplus Integrated_Webcam_HD                                           | 7         | 1.94%   |
| Realtek USB Camera                                                     | 7         | 1.94%   |
| Chicony USB2.0 Camera                                                  | 7         | 1.94%   |
| Chicony USB camera                                                     | 6         | 1.67%   |
| Microdia Webcam Vitade AF                                              | 5         | 1.39%   |
| lihappe8 USB 2.0 Camera                                                | 5         | 1.39%   |
| IMC Networks HD Camera                                                 | 5         | 1.39%   |
| Chicony HD WebCam                                                      | 5         | 1.39%   |
| Sunplus BKX Usb FHD Camera                                             | 4         | 1.11%   |
| Quanta ov9734_techfront_camera                                         | 4         | 1.11%   |
| Microdia USB 2.0 Camera                                                | 4         | 1.11%   |
| IMC Networks Integrated Camera                                         | 4         | 1.11%   |
| Sunplus USB Microphone                                                 | 3         | 0.83%   |
| Quanta HP TrueVision HD Camera                                         | 3         | 0.83%   |
| IMC Networks UVC VGA Webcam                                            | 3         | 0.83%   |
| Chicony USB2.0 FHD Camera                                              | 3         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP 2.0MP High Definition Webcam | 3         | 0.83%   |
| Bison BisonCam,NB Pro                                                  | 3         | 0.83%   |
| Apple Built-in iSight                                                  | 3         | 0.83%   |
| Z-Star Vega USB 2.0 Camera                                             | 2         | 0.56%   |
| Syntek Lenovo EasyCamera                                               | 2         | 0.56%   |
| Suyin 1.3M HD WebCam                                                   | 2         | 0.56%   |
| Sunplus Asus Webcam                                                    | 2         | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                                             | 2         | 0.56%   |
| Realtek 1080p Camera                                                   | 2         | 0.56%   |
| Microdia Integrated_Webcam_HD                                          | 2         | 0.56%   |
| Microdia Camera                                                        | 2         | 0.56%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                   | 2         | 0.56%   |
| Logitech HD Pro Webcam C920                                            | 2         | 0.56%   |
| Logitech C505 HD Webcam                                                | 2         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 10        | 25.64%  |
| Validity Sensors           | 8         | 20.51%  |
| Elan Microelectronics      | 8         | 20.51%  |
| Synaptics                  | 4         | 10.26%  |
| LighTuning Technology      | 4         | 10.26%  |
| Upek                       | 3         | 7.69%   |
| Focal-systems.Corp         | 2         | 5.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 10        | 25.64%  |
| Elan ELAN:Fingerprint                                    | 5         | 12.82%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 7.69%   |
| LighTuning Fingerprint Reader                            | 3         | 7.69%   |
| Elan ELAN:ARM-M4                                         | 3         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader               | 2         | 5.13%   |
| Validity Sensors VFS491                                  | 2         | 5.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 5.13%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 2         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader               | 1         | 2.56%   |
| Validity Sensors Fingerprint scanner                     | 1         | 2.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.56%   |
| Synaptics Fingerprint reader [HP G6]                     | 1         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Alcor Micro  | 3         | 50%     |
| Broadcom     | 1         | 16.67%  |
| Aladdin R.D. | 1         | 16.67%  |
| Aktiv        | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 50%     |
| Broadcom 5880                       | 1         | 16.67%  |
| Aladdin R.D. JaCarta                | 1         | 16.67%  |
| Aktiv Rutoken lite                  | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 521       | 83.49%  |
| 1     | 71        | 11.38%  |
| 2     | 16        | 2.56%   |
| 4     | 7         | 1.12%   |
| 3     | 5         | 0.8%    |
| 5     | 4         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 27.86%  |
| Graphics card            | 27        | 19.29%  |
| Communication controller | 27        | 19.29%  |
| Unassigned class         | 10        | 7.14%   |
| Multimedia controller    | 10        | 7.14%   |
| Net/ethernet             | 6         | 4.29%   |
| Chipcard                 | 6         | 4.29%   |
| Net/wireless             | 5         | 3.57%   |
| Sound                    | 3         | 2.14%   |
| Camera                   | 3         | 2.14%   |
| Flash memory             | 2         | 1.43%   |
| Bluetooth                | 2         | 1.43%   |

