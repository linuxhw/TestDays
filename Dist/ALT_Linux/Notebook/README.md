ALT Linux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

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

Total: 401

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M650... | [188dea7b4b](https://linux-hardware.org/?probe=188dea7b4b) | Dec 19, 2023 |
| Dell          | Inspiron 1545               | [cd3471d9e5](https://linux-hardware.org/?probe=cd3471d9e5) | Dec 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a53b2d9ba9](https://linux-hardware.org/?probe=a53b2d9ba9) | Dec 15, 2023 |
| Lenovo        | G700                        | [97b63677f6](https://linux-hardware.org/?probe=97b63677f6) | Dec 11, 2023 |
| Lenovo        | 3000 G410                   | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| Acer          | Nitro AN517-52              | [80b6f0b84a](https://linux-hardware.org/?probe=80b6f0b84a) | Dec 02, 2023 |
| MSI           | GT70 2PC                    | [0806985a42](https://linux-hardware.org/?probe=0806985a42) | Nov 29, 2023 |
| Dell          | Inspiron 15-3565            | [7d7541ceb2](https://linux-hardware.org/?probe=7d7541ceb2) | Nov 29, 2023 |
| Lenovo        | G700                        | [3c8ae88b16](https://linux-hardware.org/?probe=3c8ae88b16) | Nov 29, 2023 |
| HUAWEI        | CREF-XX                     | [630d8838dc](https://linux-hardware.org/?probe=630d8838dc) | Nov 27, 2023 |
| MSI           | GT70 2PC                    | [c4589b53bb](https://linux-hardware.org/?probe=c4589b53bb) | Nov 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [7078ba99e1](https://linux-hardware.org/?probe=7078ba99e1) | Nov 26, 2023 |
| HP            | Laptop 17-cn2xxx            | [59c09c7be1](https://linux-hardware.org/?probe=59c09c7be1) | Nov 11, 2023 |
| Dell          | Inspiron N5050              | [2ec8097b67](https://linux-hardware.org/?probe=2ec8097b67) | Oct 31, 2023 |
| Acer          | Extensa 2520G               | [bcc4e567f3](https://linux-hardware.org/?probe=bcc4e567f3) | Oct 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Laptop 15-bw0xx             | [63c6987bfa](https://linux-hardware.org/?probe=63c6987bfa) | Oct 28, 2023 |
| Acer          | Ferrari 3200                | [52f9e06bf9](https://linux-hardware.org/?probe=52f9e06bf9) | Oct 25, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f8f7f85d08](https://linux-hardware.org/?probe=f8f7f85d08) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | [d0e546f6d6](https://linux-hardware.org/?probe=d0e546f6d6) | Oct 25, 2023 |
| Lenovo        | V580c 20160                 | [178fe3a497](https://linux-hardware.org/?probe=178fe3a497) | Oct 25, 2023 |
| HONOR         | NMH-WDX9                    | [3a0782c335](https://linux-hardware.org/?probe=3a0782c335) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | [1b58a52442](https://linux-hardware.org/?probe=1b58a52442) | Oct 25, 2023 |
| Unknown       | Unknown                     | [1e239308b1](https://linux-hardware.org/?probe=1e239308b1) | Oct 21, 2023 |
| Unknown       | Unknown                     | [125d0eedc8](https://linux-hardware.org/?probe=125d0eedc8) | Oct 21, 2023 |
| HP            | 255 G4                      | [0290beac3f](https://linux-hardware.org/?probe=0290beac3f) | Oct 19, 2023 |
| Maibenben     | MaiBook X series            | [901cc6bd8a](https://linux-hardware.org/?probe=901cc6bd8a) | Oct 14, 2023 |
| ASUSTek       | T100TAM                     | [b809251676](https://linux-hardware.org/?probe=b809251676) | Oct 11, 2023 |
| Unknown       | Unknown                     | [52694348d2](https://linux-hardware.org/?probe=52694348d2) | Oct 10, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [7f32c31118](https://linux-hardware.org/?probe=7f32c31118) | Oct 09, 2023 |
| ROMBICA       | myBook Eclipse              | [d56fec4995](https://linux-hardware.org/?probe=d56fec4995) | Oct 07, 2023 |
| MSI           | Modern 15 B12M              | [1bbe75aa56](https://linux-hardware.org/?probe=1bbe75aa56) | Oct 04, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [61278c0720](https://linux-hardware.org/?probe=61278c0720) | Oct 04, 2023 |
| HUAWEI        | RLEF-XX                     | [06499eec7c](https://linux-hardware.org/?probe=06499eec7c) | Oct 04, 2023 |
| F-PLUS EQU... | Unknown                     | [104a5f30e4](https://linux-hardware.org/?probe=104a5f30e4) | Oct 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [90cb02d71d](https://linux-hardware.org/?probe=90cb02d71d) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [aa9a99ccb5](https://linux-hardware.org/?probe=aa9a99ccb5) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [200217831d](https://linux-hardware.org/?probe=200217831d) | Oct 04, 2023 |
| Lenovo        | G700                        | [7090569f96](https://linux-hardware.org/?probe=7090569f96) | Oct 03, 2023 |
| HIPER         | WORKBOOK                    | [902f508256](https://linux-hardware.org/?probe=902f508256) | Oct 03, 2023 |
| ROMBICA       | myBook Eclipse              | [004e1dc4fd](https://linux-hardware.org/?probe=004e1dc4fd) | Sep 28, 2023 |
| Infinix       | INBOOK X2 GEN11             | [2ac0204275](https://linux-hardware.org/?probe=2ac0204275) | Sep 28, 2023 |
| Kraftway      | ACCORD                      | [df4d5654d5](https://linux-hardware.org/?probe=df4d5654d5) | Sep 21, 2023 |
| iRU           | 17ALC                       | [2d0b23c813](https://linux-hardware.org/?probe=2d0b23c813) | Sep 18, 2023 |
| Lenovo        | ThinkPad X250 20CMS0A200    | [43df4bd3f3](https://linux-hardware.org/?probe=43df4bd3f3) | Sep 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | [5e87de3be1](https://linux-hardware.org/?probe=5e87de3be1) | Sep 11, 2023 |
| Toshiba       | Satellite A200              | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| Infinix       | INBOOK X2 GEN11             | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | 1215N                       | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| HP            | Laptop 15-ef2xxx            | [1096cf2959](https://linux-hardware.org/?probe=1096cf2959) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| INSYS         | IP1-XN23                    | [4212432f00](https://linux-hardware.org/?probe=4212432f00) | Jul 24, 2023 |
| ASUSTek       | X55A                        | [6818ec7338](https://linux-hardware.org/?probe=6818ec7338) | Jul 21, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [a24026d3c6](https://linux-hardware.org/?probe=a24026d3c6) | Jul 14, 2023 |
| HP            | ProBook 640 G1              | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Graviton      | N15I-T                      | [b457883ad3](https://linux-hardware.org/?probe=b457883ad3) | Jul 04, 2023 |
| Graviton      | N15I-T                      | [305390c16e](https://linux-hardware.org/?probe=305390c16e) | Jul 03, 2023 |
| 3Logic Gro... | Graviton N15i               | [1f7adfe250](https://linux-hardware.org/?probe=1f7adfe250) | Jun 27, 2023 |
| Clevo         | NL41MU2                     | [91bb626fa8](https://linux-hardware.org/?probe=91bb626fa8) | Jun 26, 2023 |
| Dell          | Vostro 3525                 | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| Alienware     | M14xR2                      | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Dell          | Vostro 3525                 | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| Lenovo        | G70-70 80HW                 | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| HP            | EliteBook 2560p             | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| HP            | Mini 210-1000               | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Dell          | Vostro 3525                 | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| ICL           | RAYbook Si1407              | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Timi          | TM1701                      | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| Clevo         | NL41MU2                     | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| Clevo         | NL41MU2                     | [3c0893a822](https://linux-hardware.org/?probe=3c0893a822) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [ce24dc022b](https://linux-hardware.org/?probe=ce24dc022b) | May 10, 2023 |
| Clevo         | NL41MU2                     | [1d50da2ba5](https://linux-hardware.org/?probe=1d50da2ba5) | May 05, 2023 |
| F-PLUS EQU... | FNB-140-P1                  | [f78d6739f5](https://linux-hardware.org/?probe=f78d6739f5) | May 03, 2023 |
| Clevo         | NL41MU2                     | [67b2580836](https://linux-hardware.org/?probe=67b2580836) | May 03, 2023 |
| Acer          | Aspire 5935                 | [1ba45b2b8f](https://linux-hardware.org/?probe=1ba45b2b8f) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| Valve         | Jupiter                     | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| Valve         | Jupiter                     | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| Clevo         | NL41MU2                     | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | [2f1b310ca2](https://linux-hardware.org/?probe=2f1b310ca2) | Apr 21, 2023 |
| Clevo         | NL41MU2                     | [322f62ae77](https://linux-hardware.org/?probe=322f62ae77) | Apr 11, 2023 |
| Clevo         | NL41MU2                     | [720eed31f6](https://linux-hardware.org/?probe=720eed31f6) | Apr 10, 2023 |
| HP            | Pavilion dv6                | [5fddb7053d](https://linux-hardware.org/?probe=5fddb7053d) | Apr 07, 2023 |
| HP            | Pavilion dv6                | [67615ec9ff](https://linux-hardware.org/?probe=67615ec9ff) | Apr 05, 2023 |
| Timi          | TM1701                      | [5fc6e30961](https://linux-hardware.org/?probe=5fc6e30961) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK NH532              | [68a8171c0a](https://linux-hardware.org/?probe=68a8171c0a) | Mar 31, 2023 |
| ASUSTek       | K52JB                       | [45162c9123](https://linux-hardware.org/?probe=45162c9123) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | [c19cd604b3](https://linux-hardware.org/?probe=c19cd604b3) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [fc942702db](https://linux-hardware.org/?probe=fc942702db) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [ab5d4b339b](https://linux-hardware.org/?probe=ab5d4b339b) | Mar 30, 2023 |
| Clevo         | NL41MU2                     | [69abc76758](https://linux-hardware.org/?probe=69abc76758) | Mar 29, 2023 |
| Clevo         | NL41MU2                     | [60191a33b8](https://linux-hardware.org/?probe=60191a33b8) | Mar 27, 2023 |
| Clevo         | NL41MU2                     | [b56bf816d5](https://linux-hardware.org/?probe=b56bf816d5) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [88a5d2eb30](https://linux-hardware.org/?probe=88a5d2eb30) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [430f11129e](https://linux-hardware.org/?probe=430f11129e) | Mar 22, 2023 |
| HP            | Pavilion g7                 | [9fbef1354b](https://linux-hardware.org/?probe=9fbef1354b) | Mar 21, 2023 |
| ASUSTek       | X55A                        | [743d04e5fc](https://linux-hardware.org/?probe=743d04e5fc) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9e620a10f2](https://linux-hardware.org/?probe=9e620a10f2) | Mar 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [dcc115a880](https://linux-hardware.org/?probe=dcc115a880) | Mar 02, 2023 |
| Clevo         | NL41MU2                     | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Clevo         | NL41MU2                     | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| Clevo         | NL41MU2                     | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Clevo         | NL41MU2                     | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| Clevo         | NL41MU2                     | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| Clevo         | NL41MU2                     | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| Lenovo        | B560                        | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| Acer          | Aspire E1-530G              | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Dell          | Latitude 5580               | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| HP            | ProBook 440 G4              | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Clevo         | NL41MU2                     | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Timi          | Redmi Book Pro 14S          | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| Unknown       | Unknown                     | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Clevo         | NL41MU2                     | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| LTD Delovo... | 15Y                         | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Clevo         | NL41MU2                     | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| HP            | ProBook 440 G4              | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| Pegatron      | C15B                        | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| Apple         | MacBook4,1                  | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Irbis         | NB264                       | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| Unknown       | Unknown                     | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Unknown       | Unknown                     | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| Dell          | Vostro 14 5410              | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| HP            | 255 G4                      | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Samsung       | R560                        | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Timi          | TM1701                      | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Acer          | TravelMate 6292             | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| Toshiba       | dynabook Satellite T87/8... | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Acer          | AOA150                      | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| ASUSTek       | T100TAM                     | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| HUAWEI        | BOD-WXX9                    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | X550ZE                      | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| HP            | Pavilion g7                 | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| Lenovo        | G570 20079                  | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| HP            | Pavilion dv7                | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| Kraftway      | ACCORD                      | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| Panasonic     | CF-20-1                     | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| ICL           | Unknown                     | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| Lenovo        | V130-15IKB 81HN             | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| Apple         | MacBook7,1                  | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| ICL           | NJ50_70CU                   | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| Notebook      | NLx0MU                      | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Lenovo        | G570 20079                  | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| HP            | ZBook 17 G5                 | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| HP            | EliteBook 840 G4            | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| HP            | 250 G7 Notebook PC          | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| HP            | ProBook 440 G5              | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Timi          | TM1701                      | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| HP            | EliteBook 840 G4            | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Dell          | Latitude 3420               | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| Dell          | G5 5590                     | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| ASUSTek       | X200MA                      | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| Dell          | Latitude 3590               | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Samsung       | 750XDA                      | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASUSTek       | N46VZ                       | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Timi          | TM1701                      | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | N46VZ                       | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Durabook      | Z14                         | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| Aquarius      | NS585                       | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Dell          | G3 3779                     | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| HP            | EliteBook 8470p             | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Lenovo        | B50-10 80QR                 | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Acer          | NC-ES1-131-C1NL             | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| HP            | EliteBook 8470p             | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| HP            | Laptop 14s-dq1xxx           | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| Toshiba       | Satellite A100              | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| MSI           | X300/X340/X400 series       | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| ASUSTek       | N46VZ                       | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Samsung       | R510/P510                   | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire E1-571G              | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| HP            | Pavilion dv6700             | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| MSI           | MEGA BOOK S430              | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Lenovo        | G505s 20255                 | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| Samsung       | RV413/RV513/E3413           | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| Acer          | Aspire ES1-523              | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | 1001PXD                     | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Acer          | Aspire ES1-523              | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| ALT Linux 10.1     | 66        | 22.15%  |
| Kometa P10         | 54        | 18.12%  |
| MOS 10             | 41        | 13.76%  |
| ALT Linux 10.0     | 30        | 10.07%  |
| ALT Linux 10.2     | 29        | 9.73%   |
| ALT Linux 9.1      | 22        | 7.38%   |
| ALT Linux 9.2      | 10        | 3.36%   |
| ALT Linux 9.0      | 9         | 3.02%   |
| ALT Linux P10      | 6         | 2.01%   |
| ALT Linux 10.1.900 | 4         | 1.34%   |
| ALT Linux 20201124 | 3         | 1.01%   |
| ALT Linux 10.0.900 | 3         | 1.01%   |
| ALT Linux P9       | 2         | 0.67%   |
| ALT Linux P8       | 2         | 0.67%   |
| ALT Linux 8.2      | 2         | 0.67%   |
| ALT Linux 20220110 | 2         | 0.67%   |
| ALT Linux 20191026 | 2         | 0.67%   |
| ALT Linux 9        | 1         | 0.34%   |
| ALT Linux 8.990    | 1         | 0.34%   |
| ALT Linux 8.920    | 1         | 0.34%   |
| ALT Linux 8.3      | 1         | 0.34%   |
| ALT Linux 8.0.0    | 1         | 0.34%   |
| ALT Linux 20230819 | 1         | 0.34%   |
| ALT Linux 20190624 | 1         | 0.34%   |
| ALT Linux 10.0.920 | 1         | 0.34%   |
| ALT Linux 10       | 1         | 0.34%   |
| ALT Linux 0.9      | 1         | 0.34%   |
| ALT Linux          | 1         | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 282       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.10.102-std-def-alt1 | 38        | 12.03%  |
| 5.10.109-std-def-alt1 | 19        | 6.01%   |
| 5.10.139-std-def-alt1 | 16        | 5.06%   |
| 5.10.156-std-def-alt1 | 11        | 3.48%   |
| 5.10.164-std-def-alt1 | 9         | 2.85%   |
| 5.15.72-un-def-alt1   | 8         | 2.53%   |
| 5.15.34-un-def-alt1   | 8         | 2.53%   |
| 5.15.80-un-def-alt1   | 7         | 2.22%   |
| 5.10.88-std-def-alt1  | 7         | 2.22%   |
| 5.10.152-std-def-alt1 | 7         | 2.22%   |
| 5.10.123-std-def-alt1 | 7         | 2.22%   |
| 5.10.198-std-def-alt1 | 6         | 1.9%    |
| 6.1.54-un-def-alt1    | 5         | 1.58%   |
| 6.1.55-un-def-alt1    | 4         | 1.27%   |
| 6.1.49-un-def-alt1    | 4         | 1.27%   |
| 5.15.76-un-def-alt1   | 4         | 1.27%   |
| 5.10.82-std-def-alt1  | 4         | 1.27%   |
| 6.1.38-un-def-alt1    | 3         | 0.95%   |
| 5.4.68-std-def-alt1.1 | 3         | 0.95%   |
| 5.4.28-std-def-alt1   | 3         | 0.95%   |
| 5.15.79-un-def-alt1   | 3         | 0.95%   |
| 5.15.73-un-def-alt1   | 3         | 0.95%   |
| 6.2.13-un-def-alt1    | 2         | 0.63%   |
| 6.1.30-un-def-alt1    | 2         | 0.63%   |
| 5.4.62-std-def-alt1   | 2         | 0.63%   |
| 5.4.51-std-def-alt1   | 2         | 0.63%   |
| 5.15.63-un-def-alt1   | 2         | 0.63%   |
| 5.15.52-un-def-alt1   | 2         | 0.63%   |
| 5.15.33-un-def-alt1   | 2         | 0.63%   |
| 5.15.25-un-def-alt1   | 2         | 0.63%   |
| 5.15.105-un-def-alt1  | 2         | 0.63%   |
| 5.10.62-un-def-alt1   | 2         | 0.63%   |
| 5.10.61-un-def-alt1   | 2         | 0.63%   |
| 5.10.37-un-def-alt1   | 2         | 0.63%   |
| 5.10.32-un-def-alt1   | 2         | 0.63%   |
| 5.10.194-std-def-alt1 | 2         | 0.63%   |
| 5.10.186-std-def-alt1 | 2         | 0.63%   |
| 5.10.185-std-def-alt1 | 2         | 0.63%   |
| 5.10.17-un-def-alt1   | 2         | 0.63%   |
| 5.10.168-std-def-alt1 | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.102 | 38        | 12.03%  |
| 5.10.109 | 19        | 6.01%   |
| 5.10.139 | 16        | 5.06%   |
| 5.10.156 | 11        | 3.48%   |
| 5.10.164 | 9         | 2.85%   |
| 5.15.80  | 8         | 2.53%   |
| 5.15.72  | 8         | 2.53%   |
| 5.15.34  | 8         | 2.53%   |
| 5.10.88  | 7         | 2.22%   |
| 5.10.152 | 7         | 2.22%   |
| 5.10.123 | 7         | 2.22%   |
| 5.10.198 | 6         | 1.9%    |
| 6.1.55   | 5         | 1.58%   |
| 6.1.54   | 5         | 1.58%   |
| 6.1.49   | 4         | 1.27%   |
| 5.15.76  | 4         | 1.27%   |
| 5.10.82  | 4         | 1.27%   |
| 6.1.38   | 3         | 0.95%   |
| 5.4.68   | 3         | 0.95%   |
| 5.4.28   | 3         | 0.95%   |
| 5.15.79  | 3         | 0.95%   |
| 5.15.73  | 3         | 0.95%   |
| 6.2.13   | 2         | 0.63%   |
| 6.1.30   | 2         | 0.63%   |
| 5.4.62   | 2         | 0.63%   |
| 5.4.51   | 2         | 0.63%   |
| 5.4.107  | 2         | 0.63%   |
| 5.15.91  | 2         | 0.63%   |
| 5.15.63  | 2         | 0.63%   |
| 5.15.52  | 2         | 0.63%   |
| 5.15.33  | 2         | 0.63%   |
| 5.15.25  | 2         | 0.63%   |
| 5.15.105 | 2         | 0.63%   |
| 5.10.62  | 2         | 0.63%   |
| 5.10.61  | 2         | 0.63%   |
| 5.10.37  | 2         | 0.63%   |
| 5.10.32  | 2         | 0.63%   |
| 5.10.194 | 2         | 0.63%   |
| 5.10.186 | 2         | 0.63%   |
| 5.10.185 | 2         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 169       | 57.48%  |
| 5.15    | 52        | 17.69%  |
| 6.1     | 26        | 8.84%   |
| 5.4     | 20        | 6.8%    |
| 4.19    | 11        | 3.74%   |
| 6.2     | 3         | 1.02%   |
| 4.9     | 3         | 1.02%   |
| 6.5     | 2         | 0.68%   |
| 5.18    | 2         | 0.68%   |
| 5.13    | 2         | 0.68%   |
| 5.7     | 1         | 0.34%   |
| 5.3     | 1         | 0.34%   |
| 5.16    | 1         | 0.34%   |
| 4.4     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 270       | 95.74%  |
| i686   | 12        | 4.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 186       | 64.58%  |
| XFCE            | 44        | 15.28%  |
| Unknown         | 29        | 10.07%  |
| MATE            | 10        | 3.47%   |
| LXQt            | 7         | 2.43%   |
| GNOME           | 5         | 1.74%   |
| Cinnamon        | 4         | 1.39%   |
| GNOME Flashback | 2         | 0.69%   |
| X-Cinnamon      | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 274       | 96.82%  |
| Wayland | 5         | 1.77%   |
| Tty     | 3         | 1.06%   |
| Unknown | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 140       | 48.44%  |
| LightDM | 85        | 29.41%  |
| Unknown | 39        | 13.49%  |
| TDM     | 22        | 7.61%   |
| GDM     | 2         | 0.69%   |
| XDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| ru_RU      | 244       | 85.02%  |
| Unknown    | 26        | 9.06%   |
| en_US      | 13        | 4.53%   |
| POSIX      | 2         | 0.7%    |
| it_IT@euro | 1         | 0.35%   |
| C          | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 201       | 70.77%  |
| BIOS | 83        | 29.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 245       | 86.27%  |
| Overlay | 18        | 6.34%   |
| Btrfs   | 18        | 6.34%   |
| Unknown | 2         | 0.7%    |
| Xfs     | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 171       | 59.79%  |
| MBR     | 73        | 25.52%  |
| Unknown | 42        | 14.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 263       | 91.64%  |
| Yes       | 24        | 8.36%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 195       | 68.66%  |
| Yes       | 89        | 31.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Hewlett-Packard                   | 67        | 23.76%  |
| Lenovo                            | 33        | 11.7%   |
| Clevo                             | 32        | 11.35%  |
| ASUSTek Computer                  | 28        | 9.93%   |
| Acer                              | 22        | 7.8%    |
| Dell                              | 13        | 4.61%   |
| ICL                               | 11        | 3.9%    |
| HUAWEI                            | 11        | 3.9%    |
| Samsung Electronics               | 6         | 2.13%   |
| 3Logic Group                      | 6         | 2.13%   |
| MSI                               | 5         | 1.77%   |
| Apple                             | 5         | 1.77%   |
| Unknown                           | 5         | 1.77%   |
| DEPO Computers                    | 4         | 1.42%   |
| Toshiba                           | 3         | 1.06%   |
| F-PLUS EQUIPMENT AND DEVELOPMENTS | 3         | 1.06%   |
| Timi                              | 2         | 0.71%   |
| Panasonic                         | 2         | 0.71%   |
| Kraftway                          | 2         | 0.71%   |
| Aquarius                          | 2         | 0.71%   |
| Valve                             | 1         | 0.35%   |
| Sony                              | 1         | 0.35%   |
| ROMBICA                           | 1         | 0.35%   |
| Pegatron                          | 1         | 0.35%   |
| Maibenben                         | 1         | 0.35%   |
| LTD Delovoy Office                | 1         | 0.35%   |
| iRU                               | 1         | 0.35%   |
| IP3 Technology                    | 1         | 0.35%   |
| IP3 Tech                          | 1         | 0.35%   |
| Intel                             | 1         | 0.35%   |
| INSYS                             | 1         | 0.35%   |
| Infinix                           | 1         | 0.35%   |
| HONOR                             | 1         | 0.35%   |
| HIPER                             | 1         | 0.35%   |
| Graviton                          | 1         | 0.35%   |
| Fujitsu                           | 1         | 0.35%   |
| eMachines                         | 1         | 0.35%   |
| Durabook                          | 1         | 0.35%   |
| Compumax Computer                 | 1         | 0.35%   |
| Alienware                         | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Clevo NL41MU2                             | 32        | 11.35%  |
| HP 250 G7 Notebook PC                     | 12        | 4.26%   |
| HP ZBook 17 G5                            | 9         | 3.19%   |
| HP ProBook 440 G5                         | 8         | 2.84%   |
| Unknown                                   | 8         | 2.84%   |
| ICL RAYbook Si1512                        | 6         | 2.13%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 4         | 1.42%   |
| DEPO Computers DPC156                     | 4         | 1.42%   |
| HUAWEI NBD-WXX9                           | 3         | 1.06%   |
| HP EliteBook 840 G4                       | 3         | 1.06%   |
| HP 250 G6 Notebook PC                     | 3         | 1.06%   |
| Dell Latitude 3420                        | 3         | 1.06%   |
| ASUS VivoBook_ASUSLaptop M1503QA_M1503QA  | 3         | 1.06%   |
| 3Logic Group Graviton N15i-K2             | 3         | 1.06%   |
| 3Logic Group Graviton N15i                | 3         | 1.06%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT      | 2         | 0.71%   |
| Kraftway ACCORD                           | 2         | 0.71%   |
| ICL NJ50_70CU                             | 2         | 0.71%   |
| HUAWEI KLVL-WXXW                          | 2         | 0.71%   |
| HP ProBook 440 G4                         | 2         | 0.71%   |
| HP EliteBook 8470p                        | 2         | 0.71%   |
| ASUS N46VZ                                | 2         | 0.71%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE | 2         | 0.71%   |
| Apple MacBook7,1                          | 2         | 0.71%   |
| Acer TravelMate 5760                      | 2         | 0.71%   |
| Valve Jupiter                             | 1         | 0.35%   |
| Toshiba Satellite A200                    | 1         | 0.35%   |
| Toshiba Satellite A100                    | 1         | 0.35%   |
| Toshiba dynabook Satellite T87/87M        | 1         | 0.35%   |
| Timi TM1701                               | 1         | 0.35%   |
| Timi Redmi Book Pro 14S                   | 1         | 0.35%   |
| Sony SVE1512H1RB                          | 1         | 0.35%   |
| Samsung SR70S/SR71S                       | 1         | 0.35%   |
| Samsung RV413/RV513/E3413                 | 1         | 0.35%   |
| Samsung R560                              | 1         | 0.35%   |
| Samsung R510/P510                         | 1         | 0.35%   |
| Samsung R509                              | 1         | 0.35%   |
| Samsung 750XDA                            | 1         | 0.35%   |
| ROMBICA myBook Eclipse                    | 1         | 0.35%   |
| Pegatron C15B                             | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Clevo NL41MU2         | 32        | 11.35%  |
| HP 250                | 17        | 6.03%   |
| HP ProBook            | 13        | 4.61%   |
| Acer Aspire           | 11        | 3.9%    |
| HP Pavilion           | 10        | 3.55%   |
| HP ZBook              | 9         | 3.19%   |
| ASUS VivoBook         | 8         | 2.84%   |
| Unknown               | 8         | 2.84%   |
| Lenovo IdeaPad        | 7         | 2.48%   |
| ICL RAYbook           | 7         | 2.48%   |
| HP Laptop             | 7         | 2.48%   |
| HP EliteBook          | 7         | 2.48%   |
| Lenovo ThinkPad       | 6         | 2.13%   |
| 3Logic Group Graviton | 6         | 2.13%   |
| Dell Latitude         | 5         | 1.77%   |
| ASUS ASUS             | 5         | 1.77%   |
| Lenovo ThinkBook      | 4         | 1.42%   |
| DEPO Computers DPC156 | 4         | 1.42%   |
| Dell Inspiron         | 4         | 1.42%   |
| Acer TravelMate       | 4         | 1.42%   |
| HUAWEI NBD-WXX9       | 3         | 1.06%   |
| Toshiba Satellite     | 2         | 0.71%   |
| Lenovo V15            | 2         | 0.71%   |
| Lenovo 3000           | 2         | 0.71%   |
| Kraftway ACCORD       | 2         | 0.71%   |
| ICL NJ50              | 2         | 0.71%   |
| HUAWEI KLVL-WXXW      | 2         | 0.71%   |
| HP 255                | 2         | 0.71%   |
| Dell Vostro           | 2         | 0.71%   |
| ASUS N46VZ            | 2         | 0.71%   |
| Apple MacBook7        | 2         | 0.71%   |
| Valve Jupiter         | 1         | 0.35%   |
| Toshiba dynabook      | 1         | 0.35%   |
| Timi TM1701           | 1         | 0.35%   |
| Timi Redmi            | 1         | 0.35%   |
| Sony SVE1512H1RB      | 1         | 0.35%   |
| Samsung SR70S         | 1         | 0.35%   |
| Samsung RV413         | 1         | 0.35%   |
| Samsung R560          | 1         | 0.35%   |
| Samsung R510          | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 63        | 22.34%  |
| 2021 | 33        | 11.7%   |
| 2018 | 26        | 9.22%   |
| 2017 | 23        | 8.16%   |
| 2020 | 22        | 7.8%    |
| 2019 | 17        | 6.03%   |
| 2011 | 13        | 4.61%   |
| 2010 | 11        | 3.9%    |
| 2012 | 10        | 3.55%   |
| 2008 | 10        | 3.55%   |
| 2016 | 9         | 3.19%   |
| 2014 | 9         | 3.19%   |
| 2023 | 7         | 2.48%   |
| 2013 | 7         | 2.48%   |
| 2009 | 7         | 2.48%   |
| 2007 | 6         | 2.13%   |
| 2015 | 5         | 1.77%   |
| 2006 | 3         | 1.06%   |
| 2004 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 282       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 223       | 77.97%  |
| Enabled  | 63        | 22.03%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 282       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 129       | 45.58%  |
| 16.01-24.0  | 61        | 21.55%  |
| 3.01-4.0    | 37        | 13.07%  |
| 8.01-16.0   | 28        | 9.89%   |
| 1.01-2.0    | 16        | 5.65%   |
| 32.01-64.0  | 5         | 1.77%   |
| 2.01-3.0    | 4         | 1.41%   |
| 0.51-1.0    | 2         | 0.71%   |
| 64.01-256.0 | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 140       | 46.2%   |
| 2.01-3.0  | 65        | 21.45%  |
| 0.51-1.0  | 40        | 13.2%   |
| 4.01-8.0  | 25        | 8.25%   |
| 3.01-4.0  | 23        | 7.59%   |
| 0.01-0.5  | 6         | 1.98%   |
| 8.01-16.0 | 4         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 227       | 79.09%  |
| 2      | 50        | 17.42%  |
| 3      | 6         | 2.09%   |
| 0      | 3         | 1.05%   |
| 4      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 202       | 71.13%  |
| Yes       | 82        | 28.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 242       | 85.82%  |
| No        | 40        | 14.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 279       | 98.59%  |
| No        | 4         | 1.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 238       | 84.1%   |
| No        | 45        | 15.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Russia      | 261       | 92.55%  |
| Greece      | 4         | 1.42%   |
| Egypt       | 2         | 0.71%   |
| Belarus     | 2         | 0.71%   |
| Uzbekistan  | 1         | 0.35%   |
| USA         | 1         | 0.35%   |
| Ukraine     | 1         | 0.35%   |
| Switzerland | 1         | 0.35%   |
| Moldova     | 1         | 0.35%   |
| Italy       | 1         | 0.35%   |
| France      | 1         | 0.35%   |
| Estonia     | 1         | 0.35%   |
| Czechia     | 1         | 0.35%   |
| Costa Rica  | 1         | 0.35%   |
| Colombia    | 1         | 0.35%   |
| Bulgaria    | 1         | 0.35%   |
| Australia   | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 163       | 56.4%   |
| St Petersburg     | 17        | 5.88%   |
| Novosibirsk       | 7         | 2.42%   |
| Barnaul           | 6         | 2.08%   |
| Samara            | 4         | 1.38%   |
| Obninsk           | 4         | 1.38%   |
| Krasnoyarsk       | 4         | 1.38%   |
| Astrakhan         | 3         | 1.04%   |
| Yekaterinburg     | 2         | 0.69%   |
| Voronezh          | 2         | 0.69%   |
| Vladimir          | 2         | 0.69%   |
| Ufa               | 2         | 0.69%   |
| Tyumen            | 2         | 0.69%   |
| Saratov           | 2         | 0.69%   |
| Perm              | 2         | 0.69%   |
| Korolyov          | 2         | 0.69%   |
| Khabarovsk        | 2         | 0.69%   |
| Kaliningrad       | 2         | 0.69%   |
| Belgorod          | 2         | 0.69%   |
| Vladivostok       | 1         | 0.35%   |
| Vitebsk           | 1         | 0.35%   |
| Verkhnyaya Pyshma | 1         | 0.35%   |
| Vergina           | 1         | 0.35%   |
| Tura              | 1         | 0.35%   |
| Troitsk           | 1         | 0.35%   |
| Thessaloniki      | 1         | 0.35%   |
| Tashkent          | 1         | 0.35%   |
| Tambov            | 1         | 0.35%   |
| Tallinn           | 1         | 0.35%   |
| Sydney            | 1         | 0.35%   |
| Surgut            | 1         | 0.35%   |
| Suez              | 1         | 0.35%   |
| Stavropol         | 1         | 0.35%   |
| Stary Oskol       | 1         | 0.35%   |
| Sofia             | 1         | 0.35%   |
| Shepsi            | 1         | 0.35%   |
| Sevastopol        | 1         | 0.35%   |
| Sergiyev Posad    | 1         | 0.35%   |
| San José         | 1         | 0.35%   |
| Rubtsovsk         | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 36        | 41     | 10.84%  |
| Samsung Electronics          | 35        | 50     | 10.54%  |
| BIWIN                        | 33        | 34     | 9.94%   |
| Intel                        | 30        | 34     | 9.04%   |
| WDC                          | 28        | 33     | 8.43%   |
| SK hynix                     | 21        | 23     | 6.33%   |
| Kingston                     | 16        | 17     | 4.82%   |
| Toshiba                      | 13        | 17     | 3.92%   |
| Foxline                      | 9         | 9      | 2.71%   |
| Hitachi                      | 8         | 8      | 2.41%   |
| Unknown                      | 7         | 14     | 2.11%   |
| SanDisk                      | 7         | 7      | 2.11%   |
| Phison                       | 7         | 8      | 2.11%   |
| HGST                         | 6         | 6      | 1.81%   |
| Apacer                       | 6         | 7      | 1.81%   |
| A-DATA Technology            | 6         | 8      | 1.81%   |
| Gigabyte Technology          | 4         | 4      | 1.2%    |
| Fujitsu                      | 4         | 4      | 1.2%    |
| FORESEE                      | 4         | 5      | 1.2%    |
| XPG                          | 3         | 4      | 0.9%    |
| Micron Technology            | 3         | 3      | 0.9%    |
| KingSpec                     | 3         | 3      | 0.9%    |
| External                     | 3         | 5      | 0.9%    |
| Crucial                      | 3         | 3      | 0.9%    |
| China                        | 3         | 3      | 0.9%    |
| Transcend                    | 2         | 2      | 0.6%    |
| SSSTC                        | 2         | 2      | 0.6%    |
| Smartbuy                     | 2         | 2      | 0.6%    |
| Silicon Motion               | 2         | 2      | 0.6%    |
| Phison Electronics           | 2         | 2      | 0.6%    |
| KIOXIA                       | 2         | 3      | 0.6%    |
| AMD                          | 2         | 2      | 0.6%    |
| Unknown                      | 2         | 2      | 0.6%    |
| Yangtze Memory Technologies  | 1         | 1      | 0.3%    |
| XrayDisk                     | 1         | 1      | 0.3%    |
| Shenzhen Longsys Electronics | 1         | 1      | 0.3%    |
| SCY                          | 1         | 1      | 0.3%    |
| PNY                          | 1         | 1      | 0.3%    |
| Plextor                      | 1         | 1      | 0.3%    |
| Patriot                      | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| BIWIN CE480T5D101-256 256GB             | 32        | 9.38%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 12        | 3.52%   |
| Foxline FLSSD256M80E13TCX5 256GB        | 9         | 2.64%   |
| Seagate ST1000LM049-2GH172 1TB          | 8         | 2.35%   |
| Intel SSDPEMKF256G8H 256GB              | 8         | 2.35%   |
| Intel SSDPEKKF256G7H 256GB              | 8         | 2.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 6         | 1.76%   |
| Phison 311CD0512GB                      | 5         | 1.47%   |
| Intel SSDPEKNU512GZ 512GB               | 5         | 1.47%   |
| Samsung MZALQ256HAJD-000L2 256GB        | 4         | 1.17%   |
| Samsung SSD 860 EVO 250GB               | 3         | 0.88%   |
| Kingston OM8PDP3256B-A01 256GB          | 3         | 0.88%   |
| Intel SSDPEKNW512G8H 512GB              | 3         | 0.88%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.88%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB        | 3         | 0.88%   |
| FORESEE XP1000F256G 256GB               | 3         | 0.88%   |
| External USB3.0 1TB                     | 3         | 0.88%   |
| Apacer AS2280P4 256GB                   | 3         | 0.88%   |
| XPG SPECTRIX S40G 1TB                   | 2         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.59%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 2         | 0.59%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 0.59%   |
| Unknown NVMe SSD Drive 512GB            | 2         | 0.59%   |
| Transcend TS240GSSD220S 240GB           | 2         | 0.59%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.59%   |
| Toshiba KXG50ZNV256G 256GB              | 2         | 0.59%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB          | 2         | 0.59%   |
| Seagate ST9250315AS 250GB               | 2         | 0.59%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.59%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.59%   |
| Samsung SSD 860 EVO M.2 250GB           | 2         | 0.59%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.59%   |
| Samsung MZVLQ512HALU-000H1 512GB        | 2         | 0.59%   |
| Kingston SUV400S37120G 120GB SSD        | 2         | 0.59%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.59%   |
| Crucial CT120BX500SSD1 120GB            | 2         | 0.59%   |
| Unknown                                 | 2         | 0.59%   |
| Yangtze Memory NVMe SSD Drive 256GB     | 1         | 0.29%   |
| XrayDisk 240GB SSD                      | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 36        | 41     | 41.86%  |
| WDC      | 19        | 20     | 22.09%  |
| Toshiba  | 10        | 14     | 11.63%  |
| Hitachi  | 8         | 8      | 9.3%    |
| HGST     | 6         | 6      | 6.98%   |
| Fujitsu  | 4         | 4      | 4.65%   |
| External | 3         | 5      | 3.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 19.4%   |
| Kingston            | 6         | 7      | 8.96%   |
| WDC                 | 5         | 8      | 7.46%   |
| A-DATA Technology   | 4         | 4      | 5.97%   |
| KingSpec            | 3         | 3      | 4.48%   |
| Intel               | 3         | 3      | 4.48%   |
| China               | 3         | 3      | 4.48%   |
| Transcend           | 2         | 2      | 2.99%   |
| Smartbuy            | 2         | 2      | 2.99%   |
| SK hynix            | 2         | 2      | 2.99%   |
| SanDisk             | 2         | 2      | 2.99%   |
| Micron Technology   | 2         | 2      | 2.99%   |
| Crucial             | 2         | 2      | 2.99%   |
| Apacer              | 2         | 3      | 2.99%   |
| AMD                 | 2         | 2      | 2.99%   |
| XrayDisk            | 1         | 1      | 1.49%   |
| PNY                 | 1         | 1      | 1.49%   |
| Plextor             | 1         | 1      | 1.49%   |
| Patriot             | 1         | 1      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| LuminouTek          | 1         | 1      | 1.49%   |
| KingDian            | 1         | 1      | 1.49%   |
| GOODRAM             | 1         | 1      | 1.49%   |
| Gigabyte Technology | 1         | 1      | 1.49%   |
| Foxline             | 1         | 1      | 1.49%   |
| Biwintech           | 1         | 2      | 1.49%   |
| BaseTech            | 1         | 1      | 1.49%   |
| ASint Technology    | 1         | 1      | 1.49%   |
| Unknown             | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 164       | 198    | 50.77%  |
| HDD  | 85        | 98     | 26.32%  |
| SSD  | 66        | 76     | 20.43%  |
| MMC  | 8         | 14     | 2.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 164       | 198    | 53.42%  |
| SATA | 128       | 165    | 41.69%  |
| MMC  | 8         | 14     | 2.61%   |
| SAS  | 7         | 9      | 2.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 116    | 69.44%  |
| 0.51-1.0   | 39        | 53     | 27.08%  |
| 1.01-2.0   | 5         | 5      | 3.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 146       | 49.83%  |
| 251-500        | 56        | 19.11%  |
| 51-100         | 31        | 10.58%  |
| 501-1000       | 19        | 6.48%   |
| 21-50          | 14        | 4.78%   |
| 1-20           | 12        | 4.1%    |
| 1001-2000      | 10        | 3.41%   |
| 2001-3000      | 3         | 1.02%   |
| More than 3000 | 1         | 0.34%   |
| Unknown        | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 146       | 48.83%  |
| 21-50          | 78        | 26.09%  |
| 51-100         | 30        | 10.03%  |
| 101-250        | 19        | 6.35%   |
| 251-500        | 13        | 4.35%   |
| 501-1000       | 7         | 2.34%   |
| 1001-2000      | 4         | 1.34%   |
| More than 3000 | 1         | 0.33%   |
| Unknown        | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                  | Notebooks | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB                              | 2         | 2      | 8%      |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 7      | 8%      |
| XrayDisk 240GB SSD                                     | 1         | 1      | 4%      |
| WDC WD5000LPVX-60V0TT0 500GB                           | 1         | 1      | 4%      |
| WDC WD5000LPLX-60ZNTT2 500GB                           | 1         | 1      | 4%      |
| WDC WD1200BEVS-60UST0 120GB                            | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB                               | 1         | 1      | 4%      |
| Toshiba MK1637GSX 160GB                                | 1         | 1      | 4%      |
| SK hynix HFS128G39TND-N210A 128GB SSD                  | 1         | 1      | 4%      |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                | 1         | 1      | 4%      |
| Shenzhen Longsys Electronics FORESEE XP1000F512G 512GB | 1         | 1      | 4%      |
| Seagate ST9640320AS 640GB                              | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB                              | 1         | 1      | 4%      |
| Seagate ST9320423AS 320GB                              | 1         | 1      | 4%      |
| Intel SSDSCKKF256H6H 256GB                             | 1         | 1      | 4%      |
| Intel SSDSC2BW480A4 480GB                              | 1         | 1      | 4%      |
| Hitachi HTS725050A9A364 500GB                          | 1         | 1      | 4%      |
| Hitachi HTS543225L9A300 250GB                          | 1         | 1      | 4%      |
| Hitachi HTS542525K9A300 250GB                          | 1         | 1      | 4%      |
| Hitachi HTS541610J9SA00 100GB                          | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB                             | 1         | 1      | 4%      |
| Fujitsu MHW2160BH PL 160GB                             | 1         | 1      | 4%      |
| AMD R5SL120G 120GB SSD                                 | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 7         | 12     | 28%     |
| Hitachi                      | 4         | 4      | 16%     |
| WDC                          | 3         | 3      | 12%     |
| Toshiba                      | 2         | 2      | 8%      |
| SK hynix                     | 2         | 2      | 8%      |
| Intel                        | 2         | 2      | 8%      |
| XrayDisk                     | 1         | 1      | 4%      |
| Shenzhen Longsys Electronics | 1         | 1      | 4%      |
| HGST                         | 1         | 1      | 4%      |
| Fujitsu                      | 1         | 1      | 4%      |
| AMD                          | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 12     | 38.89%  |
| Hitachi | 4         | 4      | 22.22%  |
| WDC     | 3         | 3      | 16.67%  |
| Toshiba | 2         | 2      | 11.11%  |
| HGST    | 1         | 1      | 5.56%   |
| Fujitsu | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 23     | 72%     |
| SSD  | 5         | 5      | 20%     |
| NVMe | 2         | 2      | 8%      |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 216       | 271    | 73.22%  |
| Detected | 54        | 85     | 18.31%  |
| Malfunc  | 25        | 30     | 8.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 217       | 55.5%   |
| INNOGRIT                         | 33        | 8.44%   |
| AMD                              | 23        | 5.88%   |
| Samsung Electronics              | 22        | 5.63%   |
| Phison Electronics               | 21        | 5.37%   |
| SK hynix                         | 18        | 4.6%    |
| SanDisk                          | 10        | 2.56%   |
| Kingston Technology Company      | 10        | 2.56%   |
| Shenzhen Longsys Electronics     | 6         | 1.53%   |
| Nvidia                           | 5         | 1.28%   |
| MAXIO Technology (Hangzhou)      | 4         | 1.02%   |
| KIOXIA                           | 3         | 0.77%   |
| VIA Technologies                 | 2         | 0.51%   |
| Toshiba America Info Systems     | 2         | 0.51%   |
| Solid State Storage Technology   | 2         | 0.51%   |
| Silicon Motion                   | 2         | 0.51%   |
| Realtek Semiconductor            | 2         | 0.51%   |
| ADATA Technology                 | 2         | 0.51%   |
| Yangtze Memory Technologies      | 1         | 0.26%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.26%   |
| Netac Technology                 | 1         | 0.26%   |
| Micron/Crucial Technology        | 1         | 0.26%   |
| Micron Technology                | 1         | 0.26%   |
| Jiangsu Huacun Elec.             | 1         | 0.26%   |
| Apple                            | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP SATA Controller                                            | 48        | 11.21%  |
| INNOGRIT NVMe SSD Controller IG5216 (DRAM-less)                                | 33        | 7.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 27        | 6.31%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 4.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 4.67%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 19        | 4.44%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 3.5%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 14        | 3.27%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 2.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 2.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 2.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 10        | 2.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 2.34%   |
| Intel SSD 600P Series                                                          | 9         | 2.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 2.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 1.87%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 8         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 1.87%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 1.4%    |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 5         | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.17%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 4         | 0.93%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 0.93%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 4         | 0.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 0.93%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 0.7%    |
| Intel SSD 660P Series                                                          | 3         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 0.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.7%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.47%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.47%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.47%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.47%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 0.47%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.47%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 2         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 202       | 48.56%  |
| NVMe | 164       | 39.42%  |
| RAID | 30        | 7.21%   |
| IDE  | 20        | 4.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 236       | 83.69%  |
| AMD          | 45        | 15.96%  |
| CentaurHauls | 1         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 50        | 17.73%  |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 4.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 4.61%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 11        | 3.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 3.55%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 8         | 2.84%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 2.13%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 1.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 1.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 1.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.42%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.06%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 1.06%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 1.06%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.06%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.06%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.71%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.71%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 2         | 0.71%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.71%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.71%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.71%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 0.71%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.71%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.71%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 0.71%   |
| Intel 12th Gen Core i5-12500H                 | 2         | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.71%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 0.71%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.35%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.35%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.35%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.35%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 72        | 25.53%  |
| Intel Core i5           | 61        | 21.63%  |
| Intel Core i3           | 34        | 12.06%  |
| Intel Core i7           | 25        | 8.87%   |
| AMD Ryzen 5             | 13        | 4.61%   |
| Intel Core 2 Duo        | 11        | 3.9%    |
| AMD Ryzen 7             | 11        | 3.9%    |
| Intel Celeron           | 9         | 3.19%   |
| Intel Atom              | 7         | 2.48%   |
| Intel Pentium           | 5         | 1.77%   |
| AMD A8                  | 4         | 1.42%   |
| Intel Pentium Silver    | 2         | 0.71%   |
| Intel Pentium Gold      | 2         | 0.71%   |
| Intel Pentium Dual-Core | 2         | 0.71%   |
| Intel Pentium Dual      | 2         | 0.71%   |
| AMD Ryzen 3             | 2         | 0.71%   |
| AMD E1                  | 2         | 0.71%   |
| AMD A6                  | 2         | 0.71%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core m5           | 1         | 0.35%   |
| Intel Core Duo          | 1         | 0.35%   |
| Intel Core 2 Solo       | 1         | 0.35%   |
| Intel Celeron M         | 1         | 0.35%   |
| Intel Celeron Dual-Core | 1         | 0.35%   |
| CentaurHauls VIA C7     | 1         | 0.35%   |
| AMD Turion 64 X2 Mobile | 1         | 0.35%   |
| AMD Ryzen 9             | 1         | 0.35%   |
| AMD Mobile Athlon 64    | 1         | 0.35%   |
| AMD FX                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-60                | 1         | 0.35%   |
| AMD Athlon 64 X2        | 1         | 0.35%   |
| AMD Athlon              | 1         | 0.35%   |
| AMD A10                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 123       | 43.62%  |
| 2      | 107       | 37.94%  |
| 6      | 21        | 7.45%   |
| 8      | 11        | 3.9%    |
| 1      | 9         | 3.19%   |
| 10     | 7         | 2.48%   |
| 12     | 3         | 1.06%   |
| 14     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 282       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 229       | 81.21%  |
| 1      | 53        | 18.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 275       | 97.52%  |
| 32-bit         | 6         | 2.13%   |
| Unknown        | 1         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 19.1%   |
| 0x806c1    | 54        | 18.75%  |
| 0x806e9    | 18        | 6.25%   |
| 0x806ec    | 17        | 5.9%    |
| 0x806ea    | 15        | 5.21%   |
| 0x906ea    | 11        | 3.82%   |
| 0x1067a    | 9         | 3.13%   |
| 0xa0660    | 8         | 2.78%   |
| 0x306a9    | 8         | 2.78%   |
| 0x206a7    | 7         | 2.43%   |
| 0x906a4    | 6         | 2.08%   |
| 0x0a50000c | 6         | 2.08%   |
| 0x706e5    | 5         | 1.74%   |
| 0x406e3    | 5         | 1.74%   |
| 0x906a3    | 4         | 1.39%   |
| 0x08600106 | 4         | 1.39%   |
| 0x08108109 | 4         | 1.39%   |
| 0x6fd      | 3         | 1.04%   |
| 0x40651    | 3         | 1.04%   |
| 0x106ca    | 3         | 1.04%   |
| 0x806c2    | 2         | 0.69%   |
| 0x706a8    | 2         | 0.69%   |
| 0x706a1    | 2         | 0.69%   |
| 0x6e8      | 2         | 0.69%   |
| 0x306c3    | 2         | 0.69%   |
| 0x30678    | 2         | 0.69%   |
| 0x20655    | 2         | 0.69%   |
| 0x106c2    | 2         | 0.69%   |
| 0x10676    | 2         | 0.69%   |
| 0x08608102 | 2         | 0.69%   |
| 0x0700010f | 2         | 0.69%   |
| 0x06001119 | 2         | 0.69%   |
| 0xa0652    | 1         | 0.35%   |
| 0x906e9    | 1         | 0.35%   |
| 0x906c0    | 1         | 0.35%   |
| 0x6fa      | 1         | 0.35%   |
| 0x6ec      | 1         | 0.35%   |
| 0x506c9    | 1         | 0.35%   |
| 0x406c3    | 1         | 0.35%   |
| 0x20652    | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 71        | 25.18%  |
| TigerLake        | 60        | 21.28%  |
| Unknown          | 12        | 4.26%   |
| Zen 3            | 11        | 3.9%    |
| SandyBridge      | 11        | 3.9%    |
| Penryn           | 11        | 3.9%    |
| IvyBridge        | 11        | 3.9%    |
| CometLake        | 10        | 3.55%   |
| Haswell          | 8         | 2.84%   |
| Alderlake Hybrid | 8         | 2.84%   |
| Westmere         | 6         | 2.13%   |
| Core             | 6         | 2.13%   |
| Bonnell          | 6         | 2.13%   |
| Zen+             | 5         | 1.77%   |
| Zen 2            | 5         | 1.77%   |
| Skylake          | 5         | 1.77%   |
| IceLake          | 5         | 1.77%   |
| Goldmont plus    | 5         | 1.77%   |
| Silvermont       | 4         | 1.42%   |
| P6               | 3         | 1.06%   |
| K8 Hammer        | 3         | 1.06%   |
| Excavator        | 3         | 1.06%   |
| Piledriver       | 2         | 0.71%   |
| K10 Llano        | 2         | 0.71%   |
| Jaguar           | 2         | 0.71%   |
| Bobcat           | 2         | 0.71%   |
| Tremont          | 1         | 0.35%   |
| Steamroller      | 1         | 0.35%   |
| Puma             | 1         | 0.35%   |
| Nehalem          | 1         | 0.35%   |
| Goldmont         | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 220       | 67.48%  |
| Nvidia           | 53        | 16.26%  |
| AMD              | 52        | 15.95%  |
| VIA Technologies | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 54        | 15.93%  |
| Intel HD Graphics 620                                                         | 23        | 6.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 13        | 3.83%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 3.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 11        | 3.24%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                              | 10        | 2.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 2.95%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                         | 9         | 2.65%   |
| Intel Comet Lake UHD Graphics                                                 | 8         | 2.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 7         | 2.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 7         | 2.06%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 6         | 1.77%   |
| Intel UHD Graphics 620                                                        | 5         | 1.47%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 5         | 1.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 1.47%   |
| AMD Lucienne                                                                  | 5         | 1.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 1.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 1.18%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 4         | 1.18%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 4         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 4         | 1.18%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 3         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 3         | 0.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 0.88%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 3         | 0.88%   |
| AMD Barcelo                                                                   | 3         | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 2         | 0.59%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 2         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 2         | 0.59%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 0.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 0.59%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 180       | 63.83%  |
| Intel + Nvidia | 35        | 12.41%  |
| 1 x AMD        | 35        | 12.41%  |
| 1 x Nvidia     | 12        | 4.26%   |
| 2 x AMD        | 7         | 2.48%   |
| AMD + Nvidia   | 6         | 2.13%   |
| Intel + AMD    | 4         | 1.42%   |
| Other          | 1         | 0.35%   |
| 2 x Intel      | 1         | 0.35%   |
| 1 x VIA        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 254       | 89.44%  |
| Proprietary | 22        | 7.75%   |
| Unknown     | 8         | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 227       | 79.09%  |
| 0.01-0.5   | 29        | 10.1%   |
| 0.51-1.0   | 13        | 4.53%   |
| 3.01-4.0   | 10        | 3.48%   |
| 1.01-2.0   | 8         | 2.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 70        | 22.95%  |
| Chimei Innolux          | 61        | 20%     |
| AU Optronics            | 39        | 12.79%  |
| LG Display              | 30        | 9.84%   |
| Samsung Electronics     | 19        | 6.23%   |
| PANDA                   | 14        | 4.59%   |
| Chi Mei Optoelectronics | 9         | 2.95%   |
| Sharp                   | 8         | 2.62%   |
| AOC                     | 6         | 1.97%   |
| PRM                     | 5         | 1.64%   |
| Apple                   | 5         | 1.64%   |
| STA                     | 4         | 1.31%   |
| BenQ                    | 4         | 1.31%   |
| AGO                     | 3         | 0.98%   |
| VIE                     | 2         | 0.66%   |
| HannStar                | 2         | 0.66%   |
| Goldstar                | 2         | 0.66%   |
| CPT                     | 2         | 0.66%   |
| Valve                   | 1         | 0.33%   |
| TR_                     | 1         | 0.33%   |
| Toshiba                 | 1         | 0.33%   |
| TMX                     | 1         | 0.33%   |
| SYM                     | 1         | 0.33%   |
| Sony                    | 1         | 0.33%   |
| SBI                     | 1         | 0.33%   |
| RGT                     | 1         | 0.33%   |
| Panasonic               | 1         | 0.33%   |
| OOO                     | 1         | 0.33%   |
| OBT                     | 1         | 0.33%   |
| LG Philips              | 1         | 0.33%   |
| KDC                     | 1         | 0.33%   |
| InnoLux Display         | 1         | 0.33%   |
| InfoVision              | 1         | 0.33%   |
| HKC                     | 1         | 0.33%   |
| Hitachi                 | 1         | 0.33%   |
| FME                     | 1         | 0.33%   |
| CS_                     | 1         | 0.33%   |
| Acer                    | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 12        | 3.92%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 9         | 2.94%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 9         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 8         | 2.61%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                 | 6         | 1.96%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                 | 6         | 1.96%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch        | 5         | 1.63%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                 | 4         | 1.31%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 4         | 1.31%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 4         | 1.31%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                 | 4         | 1.31%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch               | 3         | 0.98%   |
| Sharp LCD Monitor SHP1540 1920x1080 309x174mm 14.0-inch               | 3         | 0.98%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x174mm 14.0-inch          | 3         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.98%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.98%   |
| VIE IM27VL1 VIE2120 1920x1080 600x330mm 27.0-inch                     | 2         | 0.65%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 330x210mm 15.4-inch | 2         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.65%   |
| PRM UST-P1 PRM7644 1920x1080                                          | 2         | 0.65%   |
| PRM 35 PRM2733 1280x1024                                              | 2         | 0.65%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.65%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 2         | 0.65%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 181       | 63.29%  |
| 1366x768 (WXGA)    | 51        | 17.83%  |
| 1280x800 (WXGA)    | 14        | 4.9%    |
| 1600x900 (HD+)     | 10        | 3.5%    |
| 1280x1024 (SXGA)   | 6         | 2.1%    |
| 2560x1440 (QHD)    | 4         | 1.4%    |
| 2560x1600          | 3         | 1.05%   |
| 1920x1200 (WUXGA)  | 3         | 1.05%   |
| 1024x600           | 3         | 1.05%   |
| 2160x1440          | 2         | 0.7%    |
| 1680x1050 (WSXGA+) | 2         | 0.7%    |
| 1440x900 (WXGA+)   | 2         | 0.7%    |
| 800x1280           | 1         | 0.35%   |
| 3840x2160 (4K)     | 1         | 0.35%   |
| 3200x1800 (QHD+)   | 1         | 0.35%   |
| 2880x1620          | 1         | 0.35%   |
| 1400x1050          | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 129       | 42.3%   |
| 13      | 51        | 16.72%  |
| 14      | 43        | 14.1%   |
| 17      | 26        | 8.52%   |
| 12      | 10        | 3.28%   |
| Unknown | 7         | 2.3%    |
| 24      | 6         | 1.97%   |
| 23      | 6         | 1.97%   |
| 27      | 4         | 1.31%   |
| 21      | 4         | 1.31%   |
| 11      | 4         | 1.31%   |
| 19      | 3         | 0.98%   |
| 16      | 3         | 0.98%   |
| 10      | 3         | 0.98%   |
| 31      | 2         | 0.66%   |
| 59      | 1         | 0.33%   |
| 50      | 1         | 0.33%   |
| 8       | 1         | 0.33%   |
| 7       | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 210       | 68.85%  |
| 351-400     | 30        | 9.84%   |
| 201-300     | 30        | 9.84%   |
| 501-600     | 15        | 4.92%   |
| Unknown     | 7         | 2.3%    |
| 401-500     | 6         | 1.97%   |
| 601-700     | 3         | 0.98%   |
| 1001-1500   | 2         | 0.66%   |
| 101-200     | 1         | 0.33%   |
| 1-100       | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 244       | 85.61%  |
| 16/10 | 25        | 8.77%   |
| 5/4   | 5         | 1.75%   |
| 4/3   | 5         | 1.75%   |
| 3/2   | 4         | 1.4%    |
| 6/5   | 1         | 0.35%   |
| 0.67  | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 130       | 42.62%  |
| 81-90          | 87        | 28.52%  |
| 121-130        | 25        | 8.2%    |
| 71-80          | 11        | 3.61%   |
| 201-250        | 11        | 3.61%   |
| Unknown        | 7         | 2.3%    |
| 61-70          | 6         | 1.97%   |
| 51-60          | 4         | 1.31%   |
| 301-350        | 4         | 1.31%   |
| 251-300        | 4         | 1.31%   |
| 151-200        | 4         | 1.31%   |
| 41-50          | 3         | 0.98%   |
| More than 1000 | 2         | 0.66%   |
| 351-500        | 2         | 0.66%   |
| 1-40           | 2         | 0.66%   |
| 111-120        | 2         | 0.66%   |
| 131-140        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 191       | 62.83%  |
| 101-120       | 55        | 18.09%  |
| 51-100        | 32        | 10.53%  |
| 161-240       | 16        | 5.26%   |
| Unknown       | 7         | 2.3%    |
| 1-50          | 2         | 0.66%   |
| More than 240 | 1         | 0.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 247       | 86.36%  |
| 2     | 33        | 11.54%  |
| 0     | 5         | 1.75%   |
| 3     | 1         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 161       | 38.98%  |
| Realtek Semiconductor           | 123       | 29.78%  |
| Qualcomm Atheros                | 43        | 10.41%  |
| Broadcom                        | 29        | 7.02%   |
| MediaTek                        | 8         | 1.94%   |
| Marvell Technology Group        | 7         | 1.69%   |
| D-Link                          | 7         | 1.69%   |
| Broadcom Limited                | 6         | 1.45%   |
| Nvidia                          | 5         | 1.21%   |
| JMicron Technology              | 3         | 0.73%   |
| Huawei Technologies             | 3         | 0.73%   |
| ASIX Electronics                | 3         | 0.73%   |
| Sierra Wireless                 | 2         | 0.48%   |
| Qualcomm                        | 2         | 0.48%   |
| ASUSTek Computer                | 2         | 0.48%   |
| Samsung Electronics             | 1         | 0.24%   |
| Ralink Technology               | 1         | 0.24%   |
| Ralink                          | 1         | 0.24%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| Micro Star International        | 1         | 0.24%   |
| Hewlett-Packard                 | 1         | 0.24%   |
| DisplayLink                     | 1         | 0.24%   |
| D-Link System                   | 1         | 0.24%   |
| Attansic Technology             | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 81        | 14.89%  |
| Intel Wi-Fi 6 AX201                                                     | 54        | 9.93%   |
| Intel Ethernet Connection (13) I219-V                                   | 41        | 7.54%   |
| Intel Wireless 8265 / 8275                                              | 17        | 3.13%   |
| Intel Ethernet Connection (10) I219-V                                   | 15        | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 2.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13        | 2.39%   |
| Intel Wireless 7265                                                     | 13        | 2.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.65%   |
| Intel Ethernet Connection (7) I219-LM                                   | 9         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.47%   |
| Intel Ethernet Connection (6) I219-V                                    | 8         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.29%   |
| Intel Wireless 3165                                                     | 7         | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.74%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 4         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 0.74%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                | 4         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.55%   |
| Intel WiFi Link 5100                                                    | 3         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 155       | 53.63%  |
| Realtek Semiconductor           | 53        | 18.34%  |
| Qualcomm Atheros                | 36        | 12.46%  |
| Broadcom                        | 22        | 7.61%   |
| MediaTek                        | 8         | 2.77%   |
| Broadcom Limited                | 4         | 1.38%   |
| Sierra Wireless                 | 2         | 0.69%   |
| ASUSTek Computer                | 2         | 0.69%   |
| Ralink Technology               | 1         | 0.35%   |
| Ralink                          | 1         | 0.35%   |
| Qualcomm Atheros Communications | 1         | 0.35%   |
| Qualcomm                        | 1         | 0.35%   |
| Micro Star International        | 1         | 0.35%   |
| D-Link System                   | 1         | 0.35%   |
| D-Link                          | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 54        | 18.62%  |
| Intel Wireless 8265 / 8275                                              | 17        | 5.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 4.48%   |
| Intel Wireless 7265                                                     | 13        | 4.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 4.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 3.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 8         | 2.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.41%   |
| Intel Wireless 3165                                                     | 7         | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.38%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.03%   |
| Intel WiFi Link 5100                                                    | 3         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.03%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.03%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.69%   |
| Intel Wireless 7260                                                     | 2         | 0.69%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.69%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 101       | 40.24%  |
| Intel                    | 91        | 36.25%  |
| Qualcomm Atheros         | 16        | 6.37%   |
| Broadcom                 | 10        | 3.98%   |
| Marvell Technology Group | 7         | 2.79%   |
| D-Link                   | 6         | 2.39%   |
| Nvidia                   | 5         | 1.99%   |
| JMicron Technology       | 3         | 1.2%    |
| Huawei Technologies      | 3         | 1.2%    |
| ASIX Electronics         | 3         | 1.2%    |
| Broadcom Limited         | 2         | 0.8%    |
| Samsung Electronics      | 1         | 0.4%    |
| Qualcomm                 | 1         | 0.4%    |
| DisplayLink              | 1         | 0.4%    |
| Attansic Technology      | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 32.02%  |
| Intel Ethernet Connection (13) I219-V                             | 41        | 16.21%  |
| Intel Ethernet Connection (10) I219-V                             | 15        | 5.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 5.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 3.56%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 3.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.58%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 1.58%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.58%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 1.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.79%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.79%   |
| Intel WiMAX Connection 2400m                                      | 2         | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.79%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 2         | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.79%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.4%    |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.4%    |
| Nvidia MCP67 Ethernet                                             | 1         | 0.4%    |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.4%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.4%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 279       | 53.45%  |
| Ethernet | 242       | 46.36%  |
| Modem    | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 226       | 76.09%  |
| Ethernet | 71        | 23.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 226       | 79.86%  |
| 1     | 52        | 18.37%  |
| 0     | 4         | 1.41%   |
| 3     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 263       | 92.93%  |
| Yes  | 20        | 7.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 140       | 58.33%  |
| Realtek Semiconductor           | 26        | 10.83%  |
| IMC Networks                    | 16        | 6.67%   |
| Broadcom                        | 12        | 5%      |
| Qualcomm Atheros Communications | 8         | 3.33%   |
| Lite-On Technology              | 7         | 2.92%   |
| Foxconn / Hon Hai               | 7         | 2.92%   |
| Hewlett-Packard                 | 5         | 2.08%   |
| Apple                           | 4         | 1.67%   |
| Realtek                         | 3         | 1.25%   |
| Foxconn International           | 2         | 0.83%   |
| ASUSTek Computer                | 2         | 0.83%   |
| USI                             | 1         | 0.42%   |
| Toshiba                         | 1         | 0.42%   |
| Ralink                          | 1         | 0.42%   |
| Opticis                         | 1         | 0.42%   |
| MediaTek                        | 1         | 0.42%   |
| Dell                            | 1         | 0.42%   |
| Chicony Electronics             | 1         | 0.42%   |
| Cambridge Silicon Radio         | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                             | 59        | 24.58%  |
| Intel Bluetooth wireless interface                | 43        | 17.92%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 27        | 11.25%  |
| Realtek Bluetooth Radio                           | 20        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                  | 8         | 3.33%   |
| IMC Networks Wireless_Device                      | 8         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 1.67%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 1.67%   |
| Broadcom BCM2045 Bluetooth                        | 4         | 1.67%   |
| Realtek 802.11ac WLAN Adapter                     | 3         | 1.25%   |
| IMC Networks Bluetooth Device                     | 3         | 1.25%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 1.25%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 3         | 1.25%   |
| Apple Bluetooth Host Controller                   | 3         | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 0.83%   |
| Lite-On Qualcomm Atheros Bluetooth                | 2         | 0.83%   |
| IMC Networks Bluetooth Radio                      | 2         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 2         | 0.83%   |
| Foxconn International BCM43142A0 Bluetooth module | 2         | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 0.83%   |
| Broadcom HP Portable Bumble Bee                   | 2         | 0.83%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 2         | 0.83%   |
| USI Bluetooth Module BCM92070                     | 1         | 0.42%   |
| Toshiba Integrated Bluetooth HCI                  | 1         | 0.42%   |
| Realtek RTL8723A Bluetooth                        | 1         | 0.42%   |
| Realtek 802.11ac WLAN Adapter                     | 1         | 0.42%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.42%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.42%   |
| Opticis Bluetooth Radio                           | 1         | 0.42%   |
| MediaTek Wireless_Device                          | 1         | 0.42%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 1         | 0.42%   |
| Lite-On Bluetooth Radio                           | 1         | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 0.42%   |
| Intel Bluetooth Device                            | 1         | 0.42%   |
| Intel AX200 Bluetooth                             | 1         | 0.42%   |
| IMC Networks Bluetooth module                     | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 232       | 64.44%  |
| AMD                                          | 46        | 12.78%  |
| C-Media Electronics                          | 35        | 9.72%   |
| Nvidia                                       | 32        | 8.89%   |
| Promethean Limited                           | 7         | 1.94%   |
| VIA Technologies                             | 2         | 0.56%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.28%   |
| Realtek Semiconductor                        | 1         | 0.28%   |
| Logitech                                     | 1         | 0.28%   |
| Focusrite-Novation                           | 1         | 0.28%   |
| ASUSTek Computer                             | 1         | 0.28%   |
| Apple                                        | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 60        | 14.93%  |
| Intel Sunrise Point-LP HD Audio                                            | 33        | 8.21%   |
| C-Media Electronics USB Advanced Audio Device                              | 33        | 8.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 23        | 5.72%   |
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 5.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 4.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 3.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 11        | 2.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 1.99%   |
| AMD FCH Azalia Controller                                                  | 8         | 1.99%   |
| Promethean Limited Audio                                                   | 7         | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 1.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.24%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1%      |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1%      |
| Intel 8 Series HD Audio Controller                                         | 4         | 1%      |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1%      |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3         | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.5%    |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.5%    |
| Nvidia High Definition Audio Controller                                    | 2         | 0.5%    |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.5%    |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.5%    |
| Nvidia Audio device                                                        | 2         | 0.5%    |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.5%    |
| Intel CM238 HD Audio Controller                                            | 2         | 0.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.5%    |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 64        | 24.9%   |
| SK hynix                     | 45        | 17.51%  |
| ACPI Digital                 | 32        | 12.45%  |
| Unknown                      | 19        | 7.39%   |
| Kingston                     | 19        | 7.39%   |
| Micron Technology            | 18        | 7%      |
| Crucial                      | 17        | 6.61%   |
| Foxline                      | 6         | 2.33%   |
| A-DATA Technology            | 6         | 2.33%   |
| Elpida                       | 5         | 1.95%   |
| Unknown (ABCD)               | 3         | 1.17%   |
| Ramaxel Technology           | 3         | 1.17%   |
| Lexar Co Limited             | 3         | 1.17%   |
| ChangXin Memory              | 3         | 1.17%   |
| Unknown                      | 3         | 1.17%   |
| Unknown (0x0B92)             | 1         | 0.39%   |
| Shenzhen Longsys             | 1         | 0.39%   |
| Shenzhen Giant Hui Kang Tech | 1         | 0.39%   |
| SHARETRONIC                  | 1         | 0.39%   |
| Patriot                      | 1         | 0.39%   |
| Nanya Technology             | 1         | 0.39%   |
| Kimtigo                      | 1         | 0.39%   |
| GOODRAM                      | 1         | 0.39%   |
| Corsair                      | 1         | 0.39%   |
| Apacer                       | 1         | 0.39%   |
| AMD                          | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 32        | 12.21%  |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 4.96%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 3.44%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 7         | 2.67%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 1.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.91%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 1.53%   |
| Foxline RAM FL2666D4S19-8G ]. 8GB SODIMM DDR4 2667MT/s           | 4         | 1.53%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 4         | 1.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.15%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 1.15%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.15%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.15%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.15%   |
| Lexar Co Limited RAM LD4AS008G-3200ST 8GB SODIMM DDR4 3200MT/s   | 3         | 1.15%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s           | 3         | 1.15%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 1.15%   |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s              | 3         | 1.15%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 3         | 1.15%   |
| Unknown                                                          | 3         | 1.15%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.76%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.76%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.76%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.76%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 2         | 0.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.76%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.76%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 158       | 66.67%  |
| DDR3    | 39        | 16.46%  |
| DDR2    | 20        | 8.44%   |
| LPDDR4  | 11        | 4.64%   |
| LPDDR5  | 3         | 1.27%   |
| SDRAM   | 2         | 0.84%   |
| Unknown | 2         | 0.84%   |
| LPDDR3  | 1         | 0.42%   |
| DDR5    | 1         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 212       | 89.08%  |
| Row Of Chips | 25        | 10.5%   |
| DIMM         | 1         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 100       | 40.82%  |
| 4096  | 57        | 23.27%  |
| 16384 | 50        | 20.41%  |
| 2048  | 24        | 9.8%    |
| 1024  | 9         | 3.67%   |
| 32768 | 2         | 0.82%   |
| 512   | 2         | 0.82%   |
| 1536  | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 79        | 31.85%  |
| 2667    | 60        | 24.19%  |
| 1600    | 25        | 10.08%  |
| 2133    | 15        | 6.05%   |
| 2400    | 11        | 4.44%   |
| 667     | 11        | 4.44%   |
| 1334    | 10        | 4.03%   |
| Unknown | 7         | 2.82%   |
| 3266    | 5         | 2.02%   |
| 1067    | 4         | 1.61%   |
| 6400    | 3         | 1.21%   |
| 4267    | 3         | 1.21%   |
| 3733    | 3         | 1.21%   |
| 1333    | 3         | 1.21%   |
| 800     | 2         | 0.81%   |
| 4800    | 1         | 0.4%    |
| 4199    | 1         | 0.4%    |
| 2933    | 1         | 0.4%    |
| 2048    | 1         | 0.4%    |
| 1867    | 1         | 0.4%    |
| 533     | 1         | 0.4%    |
| 333     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 4         | 30.77%  |
| Xerox                  | 2         | 15.38%  |
| Samsung Electronics    | 2         | 15.38%  |
| Ricoh                  | 2         | 15.38%  |
| Brother Industries     | 2         | 15.38%  |
| Panasonic (Matsushita) | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung SCX-3400 Series           | 2         | 15.38%  |
| Brother HL-L2300D series          | 2         | 15.38%  |
| Xerox WorkCentre 5222             | 1         | 7.69%   |
| Xerox WorkCentre 3220             | 1         | 7.69%   |
| Ricoh SP 211SU                    | 1         | 7.69%   |
| Ricoh Aficio SP C240DN            | 1         | 7.69%   |
| Panasonic (Matsushita) KX-MB283RU | 1         | 7.69%   |
| Canon PIXMA MP190                 | 1         | 7.69%   |
| Canon MF4410                      | 1         | 7.69%   |
| Canon MF4010 series               | 1         | 7.69%   |
| Canon I-SENSYS MF4550d            | 1         | 7.69%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 55        | 20.99%  |
| Bison Electronics                      | 42        | 16.03%  |
| Cheng Uei Precision Industry (Foxlink) | 30        | 11.45%  |
| IMC Networks                           | 29        | 11.07%  |
| Sunplus Innovation Technology          | 16        | 6.11%   |
| Quanta                                 | 14        | 5.34%   |
| Realtek Semiconductor                  | 12        | 4.58%   |
| Suyin                                  | 10        | 3.82%   |
| Syntek                                 | 9         | 3.44%   |
| Acer                                   | 8         | 3.05%   |
| Microdia                               | 7         | 2.67%   |
| Sonix Technology                       | 4         | 1.53%   |
| Luxvisions Innotech Limited            | 4         | 1.53%   |
| Apple                                  | 4         | 1.53%   |
| Z-Star Microelectronics                | 3         | 1.15%   |
| Silicon Motion                         | 2         | 0.76%   |
| Lite-On Technology                     | 2         | 0.76%   |
| Y Media                                | 1         | 0.38%   |
| Unknown                                | 1         | 0.38%   |
| SunplusIT                              | 1         | 0.38%   |
| Ricoh                                  | 1         | 0.38%   |
| Primax Electronics                     | 1         | 0.38%   |
| Importek                               | 1         | 0.38%   |
| icSpring                               | 1         | 0.38%   |
| DX-221104-A                            | 1         | 0.38%   |
| BRS 2Mp Camera                         | 1         | 0.38%   |
| ALi                                    | 1         | 0.38%   |
| Alcor Micro                            | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Bison BisonCam,NB Pro                                          | 33        | 12.6%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 5.73%   |
| Chicony HP HD Camera                                           | 11        | 4.2%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 11        | 4.2%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 3.82%   |
| Realtek USB Camera                                             | 9         | 3.44%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 2.67%   |
| Syntek Integrated Camera                                       | 6         | 2.29%   |
| Chicony USB camera                                             | 6         | 2.29%   |
| Chicony Chicony USB2.0 Camera                                  | 6         | 2.29%   |
| IMC Networks Integrated Camera                                 | 5         | 1.91%   |
| IMC Networks HD Camera                                         | 5         | 1.91%   |
| Chicony HD WebCam                                              | 5         | 1.91%   |
| Sunplus BKX Usb FHD Camera                                     | 4         | 1.53%   |
| Quanta ov9734_techfront_camera                                 | 4         | 1.53%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.15%   |
| IMC Networks UVC VGA Webcam                                    | 3         | 1.15%   |
| Chicony Integrated Camera                                      | 3         | 1.15%   |
| Apple Built-in iSight                                          | 3         | 1.15%   |
| Acer BisonCam,NB Pro                                           | 3         | 1.15%   |
| Z-Star Vega USB 2.0 Camera                                     | 2         | 0.76%   |
| Syntek Lenovo EasyCamera                                       | 2         | 0.76%   |
| Suyin 1.3M HD WebCam                                           | 2         | 0.76%   |
| Sunplus Asus Webcam                                            | 2         | 0.76%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 0.76%   |
| Quanta FHD Camera                                              | 2         | 0.76%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 0.76%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 2         | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 0.76%   |
| Chicony VGA Webcam                                             | 2         | 0.76%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 2         | 0.76%   |
| Chicony Lenovo EasyCamera                                      | 2         | 0.76%   |
| Chicony Integrated HP HD Webcam                                | 2         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.76%   |
| Bison Lenovo Integrated Webcam                                 | 2         | 0.76%   |
| Acer USB HD Webcam                                             | 2         | 0.76%   |
| Acer BisonCam, NB Pro                                          | 2         | 0.76%   |
| Z-Star Namuga 1.3M Webcam                                      | 1         | 0.38%   |
| Y Media USB Camera                                             | 1         | 0.38%   |
| Unknown USB2.0 Webcam                                          | 1         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 10        | 25.64%  |
| Validity Sensors                   | 8         | 20.51%  |
| Elan Microelectronics              | 8         | 20.51%  |
| LighTuning Technology              | 4         | 10.26%  |
| Upek                               | 3         | 7.69%   |
| Synaptics                          | 3         | 7.69%   |
| Focal-systems.Corp                 | 2         | 5.13%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 10        | 25.64%  |
| Elan ELAN:Fingerprint                                           | 5         | 12.82%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 7.69%   |
| LighTuning Fingerprint Reader                                   | 3         | 7.69%   |
| Elan ELAN:ARM-M4                                                | 3         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 5.13%   |
| Validity Sensors VFS491                                         | 2         | 5.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 5.13%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 2         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2.56%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Alcor Micro  | 3         | 60%     |
| Broadcom     | 1         | 20%     |
| Aladdin R.D. | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 60%     |
| Broadcom 5880                       | 1         | 20%     |
| Aladdin R.D. JaCarta                | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 216       | 75.79%  |
| 1     | 50        | 17.54%  |
| 2     | 13        | 4.56%   |
| 3     | 5         | 1.75%   |
| 4     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 44.32%  |
| Graphics card            | 16        | 18.18%  |
| Communication controller | 9         | 10.23%  |
| Multimedia controller    | 6         | 6.82%   |
| Chipcard                 | 5         | 5.68%   |
| Net/wireless             | 4         | 4.55%   |
| Net/ethernet             | 3         | 3.41%   |
| Flash memory             | 2         | 2.27%   |
| Camera                   | 2         | 2.27%   |
| Sound                    | 1         | 1.14%   |
| Bluetooth                | 1         | 1.14%   |

