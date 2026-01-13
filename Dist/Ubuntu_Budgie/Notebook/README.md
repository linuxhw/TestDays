Ubuntu Budgie - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

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

Total: 788

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZBook Power 16 inch G11 ... | [e9dc3a9223](https://linux-hardware.org/?probe=e9dc3a9223) | Dec 21, 2025 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [999c27efc6](https://linux-hardware.org/?probe=999c27efc6) | Dec 15, 2025 |
| Apple         | MacBookPro8,2               | [97a87ca735](https://linux-hardware.org/?probe=97a87ca735) | Dec 15, 2025 |
| HP            | Pavilion g6                 | [7b48fc1b5f](https://linux-hardware.org/?probe=7b48fc1b5f) | Dec 15, 2025 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [2cd803c12b](https://linux-hardware.org/?probe=2cd803c12b) | Dec 10, 2025 |
| Dell          | Latitude 5480               | [f9cb3f4f06](https://linux-hardware.org/?probe=f9cb3f4f06) | Dec 08, 2025 |
| ASUSTek       | UX303UA                     | [124456c402](https://linux-hardware.org/?probe=124456c402) | Dec 01, 2025 |
| Dell          | Latitude 5480               | [c4f9267dd0](https://linux-hardware.org/?probe=c4f9267dd0) | Nov 27, 2025 |
| HP            | EliteBook 840 G1            | [2160988d70](https://linux-hardware.org/?probe=2160988d70) | Nov 26, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [ea1adee43a](https://linux-hardware.org/?probe=ea1adee43a) | Nov 15, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [b27cf5f053](https://linux-hardware.org/?probe=b27cf5f053) | Nov 15, 2025 |
| Apple         | MacBookPro15,4              | [ac5cdde42b](https://linux-hardware.org/?probe=ac5cdde42b) | Nov 14, 2025 |
| ASUSTek       | UX303UA                     | [3a42c35103](https://linux-hardware.org/?probe=3a42c35103) | Oct 31, 2025 |
| Dell          | Precision 3540              | [d3e0d0b8c1](https://linux-hardware.org/?probe=d3e0d0b8c1) | Oct 12, 2025 |
| Dell          | Inspiron 15-3552            | [f1cd55d4c2](https://linux-hardware.org/?probe=f1cd55d4c2) | Sep 26, 2025 |
| Dell          | Inspiron 15-3552            | [25f1128ac3](https://linux-hardware.org/?probe=25f1128ac3) | Sep 26, 2025 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [f4fa6052a7](https://linux-hardware.org/?probe=f4fa6052a7) | Sep 16, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [719d238f8e](https://linux-hardware.org/?probe=719d238f8e) | Sep 02, 2025 |
| Sony          | VPCEB1J8E                   | [aa25cc4ce1](https://linux-hardware.org/?probe=aa25cc4ce1) | Aug 31, 2025 |
| Acer          | Extensa 215-32              | [df20fc7d18](https://linux-hardware.org/?probe=df20fc7d18) | Aug 28, 2025 |
| HP            | EliteBook Folio 1040 G3     | [bfbcf4905c](https://linux-hardware.org/?probe=bfbcf4905c) | Aug 23, 2025 |
| HP            | Laptop 15-fc0xxx            | [a0f64b1cf2](https://linux-hardware.org/?probe=a0f64b1cf2) | Aug 06, 2025 |
| HP            | Laptop 15-fc0xxx            | [e942056aea](https://linux-hardware.org/?probe=e942056aea) | Aug 06, 2025 |
| Star Labs     | Lite                        | [f8cc5dc518](https://linux-hardware.org/?probe=f8cc5dc518) | Aug 02, 2025 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [93dde6625b](https://linux-hardware.org/?probe=93dde6625b) | Jul 30, 2025 |
| Acer          | Aspire 5935                 | [85f68eed9d](https://linux-hardware.org/?probe=85f68eed9d) | Jul 22, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d7d9ba2604](https://linux-hardware.org/?probe=d7d9ba2604) | Jul 18, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0c3728ebab](https://linux-hardware.org/?probe=0c3728ebab) | Jul 18, 2025 |
| Alienware     | m17 R3                      | [245ab94c78](https://linux-hardware.org/?probe=245ab94c78) | Jul 15, 2025 |
| Lenovo        | ThinkPad L560 20F2S0D300    | [e03ec0ce88](https://linux-hardware.org/?probe=e03ec0ce88) | Jul 12, 2025 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [03078d053e](https://linux-hardware.org/?probe=03078d053e) | Jun 27, 2025 |
| Lenovo        | ThinkPad L560 20F2S0D300    | [6b76985a0c](https://linux-hardware.org/?probe=6b76985a0c) | Jun 19, 2025 |
| Dell          | XPS 13 7390                 | [f698e62cea](https://linux-hardware.org/?probe=f698e62cea) | Jun 16, 2025 |
| ASUSTek       | NX500JK                     | [5a43953c60](https://linux-hardware.org/?probe=5a43953c60) | May 16, 2025 |
| Dell          | Latitude E6440              | [e8b6a014ef](https://linux-hardware.org/?probe=e8b6a014ef) | May 14, 2025 |
| ASUSTek       | NX500JK                     | [af2e866f25](https://linux-hardware.org/?probe=af2e866f25) | May 11, 2025 |
| Lenovo        | V14 G2 ITL 82KA             | [e4052da9b7](https://linux-hardware.org/?probe=e4052da9b7) | May 11, 2025 |
| Lenovo        | V14 G2 ITL 82KA             | [e91e334c23](https://linux-hardware.org/?probe=e91e334c23) | May 11, 2025 |
| Dell          | Vostro 1720                 | [ca796f4129](https://linux-hardware.org/?probe=ca796f4129) | May 07, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe475bd407](https://linux-hardware.org/?probe=fe475bd407) | May 02, 2025 |
| Lenovo        | ThinkPad L15 Gen 3 21C70... | [708bfb835f](https://linux-hardware.org/?probe=708bfb835f) | Apr 18, 2025 |
| Lenovo        | ThinkPad T495 20NKS0SG00    | [d4d1a81686](https://linux-hardware.org/?probe=d4d1a81686) | Apr 04, 2025 |
| HP            | Pavilion dv6                | [0c0f7f68c0](https://linux-hardware.org/?probe=0c0f7f68c0) | Apr 03, 2025 |
| Dell          | Inspiron 5548               | [80974f080f](https://linux-hardware.org/?probe=80974f080f) | Mar 29, 2025 |
| Dell          | Inspiron 5548               | [00e2021874](https://linux-hardware.org/?probe=00e2021874) | Mar 29, 2025 |
| HP            | ProBook 4510s               | [ed83f78ccb](https://linux-hardware.org/?probe=ed83f78ccb) | Mar 27, 2025 |
| Dell          | Latitude 7390               | [65f46a9c5f](https://linux-hardware.org/?probe=65f46a9c5f) | Mar 27, 2025 |
| Dell          | Precision 7510              | [8a2830d4ec](https://linux-hardware.org/?probe=8a2830d4ec) | Mar 15, 2025 |
| Dell          | Latitude 3490               | [5dc4effe69](https://linux-hardware.org/?probe=5dc4effe69) | Mar 13, 2025 |
| Dell          | Latitude 3490               | [71c238fab0](https://linux-hardware.org/?probe=71c238fab0) | Feb 25, 2025 |
| ASUSTek       | K50IJ                       | [04bb6c983f](https://linux-hardware.org/?probe=04bb6c983f) | Feb 25, 2025 |
| ASUSTek       | K50IJ                       | [7b6c9d9f33](https://linux-hardware.org/?probe=7b6c9d9f33) | Feb 24, 2025 |
| Apple         | MacBookPro9,2               | [8d69d76e67](https://linux-hardware.org/?probe=8d69d76e67) | Feb 20, 2025 |
| Apple         | MacBookAir7,1               | [f4999eb586](https://linux-hardware.org/?probe=f4999eb586) | Feb 19, 2025 |
| Dell          | Latitude 5490               | [7ab1816c17](https://linux-hardware.org/?probe=7ab1816c17) | Feb 18, 2025 |
| Dell          | XPS 13 9310                 | [00156a8fe1](https://linux-hardware.org/?probe=00156a8fe1) | Feb 17, 2025 |
| Apple         | MacBookAir4,2               | [16c250f9e9](https://linux-hardware.org/?probe=16c250f9e9) | Feb 13, 2025 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [636dc499aa](https://linux-hardware.org/?probe=636dc499aa) | Feb 12, 2025 |
| Acer          | TravelMate P614-51-G2       | [d246b80f27](https://linux-hardware.org/?probe=d246b80f27) | Feb 04, 2025 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [f33d3fc84e](https://linux-hardware.org/?probe=f33d3fc84e) | Jan 28, 2025 |
| Lenovo        | G50-45 80E3                 | [17117ae584](https://linux-hardware.org/?probe=17117ae584) | Jan 21, 2025 |
| Lenovo        | Y50-70 20378                | [639a969db0](https://linux-hardware.org/?probe=639a969db0) | Jan 21, 2025 |
| Lenovo        | Y50-70 20378                | [ff8f7a49af](https://linux-hardware.org/?probe=ff8f7a49af) | Jan 21, 2025 |
| HP            | EliteBook 2540p             | [6373ee4667](https://linux-hardware.org/?probe=6373ee4667) | Jan 14, 2025 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [3330495ac8](https://linux-hardware.org/?probe=3330495ac8) | Jan 14, 2025 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0d82f56224](https://linux-hardware.org/?probe=0d82f56224) | Jan 07, 2025 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [3a8228babe](https://linux-hardware.org/?probe=3a8228babe) | Jan 07, 2025 |
| HP            | ProBook 4510s               | [d74e06d912](https://linux-hardware.org/?probe=d74e06d912) | Jan 06, 2025 |
| HP            | ProBook 4510s               | [cf51ebf11d](https://linux-hardware.org/?probe=cf51ebf11d) | Jan 06, 2025 |
| HP            | Pavilion Laptop 15t-eg30... | [a2b911a2d0](https://linux-hardware.org/?probe=a2b911a2d0) | Jan 02, 2025 |
| Dell          | XPS 13 9310                 | [f07db9b11e](https://linux-hardware.org/?probe=f07db9b11e) | Jan 01, 2025 |
| Dell          | Latitude 5430               | [cc52da1214](https://linux-hardware.org/?probe=cc52da1214) | Dec 23, 2024 |
| Apple         | MacBookPro7,1               | [47aa54e827](https://linux-hardware.org/?probe=47aa54e827) | Dec 18, 2024 |
| HP            | ZBook 15v G5                | [9db28aa3ea](https://linux-hardware.org/?probe=9db28aa3ea) | Dec 09, 2024 |
| ASUSTek       | GL502VSK                    | [ccd94e881c](https://linux-hardware.org/?probe=ccd94e881c) | Dec 08, 2024 |
| Apple         | MacBookPro12,1              | [57ae9d7c2c](https://linux-hardware.org/?probe=57ae9d7c2c) | Nov 25, 2024 |
| Apple         | MacBookPro12,1              | [12f0f16eb4](https://linux-hardware.org/?probe=12f0f16eb4) | Nov 20, 2024 |
| Dell          | Precision M6500             | [a96322627d](https://linux-hardware.org/?probe=a96322627d) | Nov 20, 2024 |
| Dell          | XPS 13 9310                 | [7fcc13f0a5](https://linux-hardware.org/?probe=7fcc13f0a5) | Nov 17, 2024 |
| Dell          | Precision M6500             | [84f6a1c29f](https://linux-hardware.org/?probe=84f6a1c29f) | Nov 12, 2024 |
| Acer          | Extensa 5620                | [8b93a69b2b](https://linux-hardware.org/?probe=8b93a69b2b) | Nov 07, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a03f229cb3](https://linux-hardware.org/?probe=a03f229cb3) | Nov 06, 2024 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [f96d5e7cbc](https://linux-hardware.org/?probe=f96d5e7cbc) | Oct 31, 2024 |
| Dell          | Latitude 5490               | [00c2184d2d](https://linux-hardware.org/?probe=00c2184d2d) | Oct 18, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [846f23a439](https://linux-hardware.org/?probe=846f23a439) | Oct 14, 2024 |
| Acer          | TravelMate 8572             | [12985b02dc](https://linux-hardware.org/?probe=12985b02dc) | Oct 13, 2024 |
| Dell          | XPS 13 9310                 | [d05f6762f8](https://linux-hardware.org/?probe=d05f6762f8) | Oct 13, 2024 |
| ASUSTek       | UX303UA                     | [7151dfd4cb](https://linux-hardware.org/?probe=7151dfd4cb) | Oct 11, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [05af8a3249](https://linux-hardware.org/?probe=05af8a3249) | Oct 10, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [f295336477](https://linux-hardware.org/?probe=f295336477) | Oct 06, 2024 |
| HP            | 250 G7 Notebook PC          | [30f5ea4c3f](https://linux-hardware.org/?probe=30f5ea4c3f) | Oct 02, 2024 |
| ASUSTek       | K52Jc                       | [364a24826b](https://linux-hardware.org/?probe=364a24826b) | Sep 29, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | [7e49febc40](https://linux-hardware.org/?probe=7e49febc40) | Sep 27, 2024 |
| TUXEDO        | Pulse 15 Gen1               | [df83d2c6b4](https://linux-hardware.org/?probe=df83d2c6b4) | Sep 26, 2024 |
| ASUSTek       | UX303UA                     | [8cb4bb7e08](https://linux-hardware.org/?probe=8cb4bb7e08) | Sep 20, 2024 |
| Apple         | MacBookPro8,1               | [03c92f2ac0](https://linux-hardware.org/?probe=03c92f2ac0) | Sep 19, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [b39128c23f](https://linux-hardware.org/?probe=b39128c23f) | Sep 18, 2024 |
| Dell          | XPS 13 9370                 | [f77ada41b7](https://linux-hardware.org/?probe=f77ada41b7) | Sep 08, 2024 |
| Acer          | TravelMate 8572             | [9433520464](https://linux-hardware.org/?probe=9433520464) | Sep 03, 2024 |
| Lenovo        | Yoga Slim 6 14APU8 82X3     | [66bca1f436](https://linux-hardware.org/?probe=66bca1f436) | Sep 01, 2024 |
| HP            | Pavilion dv8                | [33c6d5838c](https://linux-hardware.org/?probe=33c6d5838c) | Aug 30, 2024 |
| Dell          | XPS 15 7590                 | [fc9e70c2da](https://linux-hardware.org/?probe=fc9e70c2da) | Aug 29, 2024 |
| Sony          | SVS13A25PBS                 | [1a864e2a63](https://linux-hardware.org/?probe=1a864e2a63) | Aug 28, 2024 |
| Dell          | XPS 13 9370                 | [b1e23bca9e](https://linux-hardware.org/?probe=b1e23bca9e) | Aug 26, 2024 |
| Apple         | MacBookPro11,4              | [eda7f45dd3](https://linux-hardware.org/?probe=eda7f45dd3) | Aug 16, 2024 |
| Apple         | MacBookPro11,4              | [8c01a14993](https://linux-hardware.org/?probe=8c01a14993) | Aug 16, 2024 |
| HP            | ENVY TS 15                  | [5ae88f75d1](https://linux-hardware.org/?probe=5ae88f75d1) | Aug 15, 2024 |
| Sony          | SVS13A25PBS                 | [d94f7cdf09](https://linux-hardware.org/?probe=d94f7cdf09) | Aug 01, 2024 |
| Fujitsu       | LIFEBOOK E554               | [df893fa78f](https://linux-hardware.org/?probe=df893fa78f) | Jul 30, 2024 |
| Fujitsu       | LIFEBOOK E554               | [010cf4260e](https://linux-hardware.org/?probe=010cf4260e) | Jul 30, 2024 |
| Sony          | SVS13A25PBS                 | [408978a559](https://linux-hardware.org/?probe=408978a559) | Jul 29, 2024 |
| HP            | ENVY TS 15                  | [4e23524711](https://linux-hardware.org/?probe=4e23524711) | Jul 29, 2024 |
| Notebook      | N150CU                      | [c208631141](https://linux-hardware.org/?probe=c208631141) | Jul 28, 2024 |
| Apple         | MacBookPro12,1              | [00884f6079](https://linux-hardware.org/?probe=00884f6079) | Jul 15, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [dcb527ee60](https://linux-hardware.org/?probe=dcb527ee60) | Jul 14, 2024 |
| Samsung       | 700T1C                      | [33a6415fdc](https://linux-hardware.org/?probe=33a6415fdc) | Jul 07, 2024 |
| ASUSTek       | X555LAB                     | [d81c85d9d6](https://linux-hardware.org/?probe=d81c85d9d6) | Jun 20, 2024 |
| Sony          | SVS13A25PBS                 | [ab978ada53](https://linux-hardware.org/?probe=ab978ada53) | Jun 18, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [af64297908](https://linux-hardware.org/?probe=af64297908) | Jun 01, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [584b93c097](https://linux-hardware.org/?probe=584b93c097) | May 31, 2024 |
| Toshiba       | Satellite L740              | [471713a2b2](https://linux-hardware.org/?probe=471713a2b2) | May 24, 2024 |
| HP            | Laptop 15s-fq2xxx           | [5e61a97c25](https://linux-hardware.org/?probe=5e61a97c25) | May 22, 2024 |
| HP            | Pavilion dv8                | [e9722285d5](https://linux-hardware.org/?probe=e9722285d5) | May 16, 2024 |
| HP            | Laptop 15s-fq2xxx           | [72068c6f4a](https://linux-hardware.org/?probe=72068c6f4a) | May 14, 2024 |
| Notebook      | N150CU                      | [f57c924d44](https://linux-hardware.org/?probe=f57c924d44) | May 14, 2024 |
| HP            | Pavilion dv8                | [a44fe4349b](https://linux-hardware.org/?probe=a44fe4349b) | May 13, 2024 |
| Lenovo        | G50-45 80E3                 | [55945040da](https://linux-hardware.org/?probe=55945040da) | May 09, 2024 |
| Notebook      | N150CU                      | [348d0cab2d](https://linux-hardware.org/?probe=348d0cab2d) | May 07, 2024 |
| Sony          | SVS13A25PBS                 | [32dc3304ac](https://linux-hardware.org/?probe=32dc3304ac) | May 02, 2024 |
| HP            | Spectre Pro x360 G1         | [39577e6ab0](https://linux-hardware.org/?probe=39577e6ab0) | May 01, 2024 |
| HP            | Pavilion dv8                | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| Chuwi         | X312B                       | [3623330a1c](https://linux-hardware.org/?probe=3623330a1c) | Apr 09, 2024 |
| Chuwi         | X312B                       | [5aa107f741](https://linux-hardware.org/?probe=5aa107f741) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [7bb2773966](https://linux-hardware.org/?probe=7bb2773966) | Apr 05, 2024 |
| Lenovo        | G50-45 80E3                 | [297eab2023](https://linux-hardware.org/?probe=297eab2023) | Mar 31, 2024 |
| Google        | Bobba                       | [d69b117fd0](https://linux-hardware.org/?probe=d69b117fd0) | Mar 30, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [4b22ed6279](https://linux-hardware.org/?probe=4b22ed6279) | Mar 29, 2024 |
| Sony          | SVS13A25PBS                 | [6ee5930fa8](https://linux-hardware.org/?probe=6ee5930fa8) | Mar 27, 2024 |
| Packard Be... | EasyNote TM98               | [e6c48ef91f](https://linux-hardware.org/?probe=e6c48ef91f) | Mar 22, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [d337b27afc](https://linux-hardware.org/?probe=d337b27afc) | Mar 21, 2024 |
| HP            | ProBook 450 G1              | [3bfd1620fe](https://linux-hardware.org/?probe=3bfd1620fe) | Mar 12, 2024 |
| Dell          | Latitude 5480               | [5c3376ae97](https://linux-hardware.org/?probe=5c3376ae97) | Feb 29, 2024 |
| Apple         | MacBookPro6,2               | [a3b8064ddf](https://linux-hardware.org/?probe=a3b8064ddf) | Feb 29, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [4963c40308](https://linux-hardware.org/?probe=4963c40308) | Feb 27, 2024 |
| Apple         | MacBookPro6,2               | [fd9e5de8cf](https://linux-hardware.org/?probe=fd9e5de8cf) | Feb 22, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [29aa21542a](https://linux-hardware.org/?probe=29aa21542a) | Feb 22, 2024 |
| Dell          | Vostro 5625                 | [04e53619c6](https://linux-hardware.org/?probe=04e53619c6) | Feb 19, 2024 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | [4264042062](https://linux-hardware.org/?probe=4264042062) | Feb 18, 2024 |
| ASUSTek       | G750JW                      | [1ba5260b50](https://linux-hardware.org/?probe=1ba5260b50) | Feb 13, 2024 |
| HP            | 15                          | [ef0b519e9b](https://linux-hardware.org/?probe=ef0b519e9b) | Feb 12, 2024 |
| TUXEDO        | InfinityBook S 15 Gen6      | [c80a1f64fc](https://linux-hardware.org/?probe=c80a1f64fc) | Jan 18, 2024 |
| Toshiba       | Satellite C855D-11X         | [d047649166](https://linux-hardware.org/?probe=d047649166) | Jan 14, 2024 |
| Alurin        | ALU-LPT-N4020-8256-140      | [61fdeffbaf](https://linux-hardware.org/?probe=61fdeffbaf) | Jan 12, 2024 |
| TUXEDO        | Pulse 14 Gen1               | [66efe29bec](https://linux-hardware.org/?probe=66efe29bec) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d041e87729](https://linux-hardware.org/?probe=d041e87729) | Jan 09, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [cce2fde2ac](https://linux-hardware.org/?probe=cce2fde2ac) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| Apple         | MacBookPro8,3               | [b1467995b6](https://linux-hardware.org/?probe=b1467995b6) | Jan 06, 2024 |
| Lenovo        | ThinkPad X220 4291G75       | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Toshiba       | Satellite A300              | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASUSTek       | E403SA                      | [141030490c](https://linux-hardware.org/?probe=141030490c) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| Sony          | VPCW216AG                   | [fb60613609](https://linux-hardware.org/?probe=fb60613609) | Dec 08, 2023 |
| Unknown       | Unknown                     | [00756344be](https://linux-hardware.org/?probe=00756344be) | Nov 25, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [a293b54992](https://linux-hardware.org/?probe=a293b54992) | Nov 24, 2023 |
| HP            | ZBook 17 G3                 | [5f26bd4798](https://linux-hardware.org/?probe=5f26bd4798) | Nov 21, 2023 |
| HP            | ZBook 17 G3                 | [ed1bde2ed6](https://linux-hardware.org/?probe=ed1bde2ed6) | Nov 20, 2023 |
| Dell          | Vostro 15 3510              | [9c0b7c2706](https://linux-hardware.org/?probe=9c0b7c2706) | Nov 15, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [5efa262121](https://linux-hardware.org/?probe=5efa262121) | Nov 14, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [7736f94150](https://linux-hardware.org/?probe=7736f94150) | Nov 13, 2023 |
| Lenovo        | G50-45 80E3                 | [51f7d5e2dc](https://linux-hardware.org/?probe=51f7d5e2dc) | Nov 09, 2023 |
| Lenovo        | G50-45 80E3                 | [0a23b4526a](https://linux-hardware.org/?probe=0a23b4526a) | Nov 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [143fa66e87](https://linux-hardware.org/?probe=143fa66e87) | Nov 08, 2023 |
| HONOR         | GLO-GXXX                    | [c6d6619fd9](https://linux-hardware.org/?probe=c6d6619fd9) | Nov 06, 2023 |
| Lenovo        | G50-45 80E3                 | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| Dell          | Latitude E5470              | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Sony          | SVS13A25PBS                 | [7cb087bd2d](https://linux-hardware.org/?probe=7cb087bd2d) | Oct 27, 2023 |
| Toshiba       | Satellite C650              | [5236a2eca3](https://linux-hardware.org/?probe=5236a2eca3) | Oct 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [47186b8e71](https://linux-hardware.org/?probe=47186b8e71) | Oct 24, 2023 |
| Lenovo        | G50-45 80E3                 | [41f9f44ee1](https://linux-hardware.org/?probe=41f9f44ee1) | Oct 20, 2023 |
| Lenovo        | G50-45 80E3                 | [98f1b28357](https://linux-hardware.org/?probe=98f1b28357) | Oct 20, 2023 |
| IMUZ          | STORMBOOK14 APOLLO          | [6d8e8178b0](https://linux-hardware.org/?probe=6d8e8178b0) | Oct 19, 2023 |
| Google        | Kled                        | [4d546b71e7](https://linux-hardware.org/?probe=4d546b71e7) | Oct 17, 2023 |
| Gateway       | NV59C                       | [5a0c4e72d6](https://linux-hardware.org/?probe=5a0c4e72d6) | Oct 16, 2023 |
| HP            | EliteBook 840 G2            | [3055b32637](https://linux-hardware.org/?probe=3055b32637) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| HP            | Laptop 15-fc0xxx            | [c2205d1cf2](https://linux-hardware.org/?probe=c2205d1cf2) | Oct 10, 2023 |
| HP            | EliteBook 840 G2            | [a90e584705](https://linux-hardware.org/?probe=a90e584705) | Oct 04, 2023 |
| ASUSTek       | UX303UA                     | [657233bb53](https://linux-hardware.org/?probe=657233bb53) | Oct 02, 2023 |
| HONOR         | HLYL-WXX9                   | [5a440c873d](https://linux-hardware.org/?probe=5a440c873d) | Oct 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [73b5907f17](https://linux-hardware.org/?probe=73b5907f17) | Sep 30, 2023 |
| Apple         | MacBookPro15,2              | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| COM1          | NBINF-X5-9G5                | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| Acer          | Aspire 7530G                | [37d34804dd](https://linux-hardware.org/?probe=37d34804dd) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [9a1d56bda1](https://linux-hardware.org/?probe=9a1d56bda1) | Sep 20, 2023 |
| Gateway       | NV59C                       | [0885dc9384](https://linux-hardware.org/?probe=0885dc9384) | Sep 16, 2023 |
| Dell          | Latitude 7280               | [ecca4887d5](https://linux-hardware.org/?probe=ecca4887d5) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [312d4a06dc](https://linux-hardware.org/?probe=312d4a06dc) | Sep 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | G50-45 80E3                 | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| ASUSTek       | UX303UA                     | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| ASUSTek       | X550CC                      | [934ab444f2](https://linux-hardware.org/?probe=934ab444f2) | Aug 07, 2023 |
| ASUSTek       | X550CC                      | [3f8e9bffbd](https://linux-hardware.org/?probe=3f8e9bffbd) | Aug 05, 2023 |
| Dell          | Latitude 7490               | [73efa45f4f](https://linux-hardware.org/?probe=73efa45f4f) | Aug 05, 2023 |
| Dell          | Latitude 7490               | [ce0e015b6e](https://linux-hardware.org/?probe=ce0e015b6e) | Aug 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [7466fce2a2](https://linux-hardware.org/?probe=7466fce2a2) | Jul 18, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| HP            | EliteBook 840 G3            | [95fa9e14bf](https://linux-hardware.org/?probe=95fa9e14bf) | Jul 07, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [3e7598da34](https://linux-hardware.org/?probe=3e7598da34) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Lenovo        | G50-45 80E3                 | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| BANGHO        | BES G0304                   | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| Apple         | MacBookPro9,2               | [544b40258b](https://linux-hardware.org/?probe=544b40258b) | Jun 21, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| ASUSTek       | UX303UA                     | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [3903b22ffd](https://linux-hardware.org/?probe=3903b22ffd) | Jun 02, 2023 |
| HP            | Notebook                    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| Dell          | XPS 13 9310                 | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| Unknown       | Unknown                     | [b63a3cbd7b](https://linux-hardware.org/?probe=b63a3cbd7b) | May 25, 2023 |
| Unknown       | Unknown                     | [3db7516231](https://linux-hardware.org/?probe=3db7516231) | May 25, 2023 |
| Dell          | Latitude 5521               | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Apple         | MacBookAir6,2               | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | Latitude E5420              | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Unknown       | Unknown                     | [9ed744299a](https://linux-hardware.org/?probe=9ed744299a) | May 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Dell          | Latitude E6420              | [7a26c45568](https://linux-hardware.org/?probe=7a26c45568) | May 04, 2023 |
| HP            | EliteBook 2540p             | [a0b1299baa](https://linux-hardware.org/?probe=a0b1299baa) | May 02, 2023 |
| Acer          | Aspire A317-53              | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Dell          | Latitude E5420              | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Lenovo        | B50-30 80ES                 | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [b402183807](https://linux-hardware.org/?probe=b402183807) | Apr 24, 2023 |
| Acer          | Swift SF314-42              | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| ASUSTek       | UX303UA                     | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1c517ff300](https://linux-hardware.org/?probe=1c517ff300) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| HP            | ZBook 15 G4                 | [ebd974c40f](https://linux-hardware.org/?probe=ebd974c40f) | Mar 23, 2023 |
| Dell          | Latitude 7480               | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| ASUSTek       | X555LAB                     | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | [1ade706194](https://linux-hardware.org/?probe=1ade706194) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | [45537ae306](https://linux-hardware.org/?probe=45537ae306) | Mar 17, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| MSI           | Raider GE76 12UE            | [b78033fddd](https://linux-hardware.org/?probe=b78033fddd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| HP            | ZBook 15 G4                 | [38a0ce48ed](https://linux-hardware.org/?probe=38a0ce48ed) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Google        | Boten                       | [5562b4af15](https://linux-hardware.org/?probe=5562b4af15) | Feb 11, 2023 |
| Google        | Boten                       | [d07e5295bb](https://linux-hardware.org/?probe=d07e5295bb) | Feb 11, 2023 |
| HP            | Laptop 14-cm0xxx            | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| Apple         | MacBookAir7,2               | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| Dell          | Latitude E6420              | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Google        | Banjo                       | [30a528ac6b](https://linux-hardware.org/?probe=30a528ac6b) | Jan 14, 2023 |
| Google        | Banjo                       | [66dc97b0de](https://linux-hardware.org/?probe=66dc97b0de) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
| TUXEDO        | Polaris (CML/Gen2)          | [a14e00ab97](https://linux-hardware.org/?probe=a14e00ab97) | Dec 29, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [00e25b3232](https://linux-hardware.org/?probe=00e25b3232) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| Dell          | System XPS L502X            | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| MSI           | GL65 Leopard 10SDK          | [2c6e6ec3ec](https://linux-hardware.org/?probe=2c6e6ec3ec) | Dec 21, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| THUNDEROBO... | 911MT                       | [40111c09eb](https://linux-hardware.org/?probe=40111c09eb) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Sony          | VPCEA45FG                   | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| MSI           | GL65 Leopard 10SFKV         | [84668eb3a8](https://linux-hardware.org/?probe=84668eb3a8) | Nov 16, 2022 |
| MSI           | GL65 Leopard 10SFKV         | [316e275c13](https://linux-hardware.org/?probe=316e275c13) | Nov 16, 2022 |
| Thomson       | N17V3C8WH512                | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| ASUSTek       | UX303UA                     | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| Dell          | XPS 13 9310                 | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [3cb2ce5a02](https://linux-hardware.org/?probe=3cb2ce5a02) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [cc583599ef](https://linux-hardware.org/?probe=cc583599ef) | Aug 28, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| Acer          | TravelMate P653-M           | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| Dell          | Inspiron 3793               | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2a95697c62](https://linux-hardware.org/?probe=2a95697c62) | Jul 25, 2022 |
| Alienware     | M11xR3                      | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| MSI           | GE75 Raider 10SE            | [d2ed25b6e8](https://linux-hardware.org/?probe=d2ed25b6e8) | Jul 16, 2022 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | [f1dcf09169](https://linux-hardware.org/?probe=f1dcf09169) | Jul 14, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Dell          | Latitude E7450              | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Positivo      | Q232A                       | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Pavilion dv7                | [add98928e5](https://linux-hardware.org/?probe=add98928e5) | Jun 18, 2022 |
| HP            | Pavilion dv7                | [bfecf091a6](https://linux-hardware.org/?probe=bfecf091a6) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| ASUSTek       | X555LAB                     | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Chuwi         | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| MSI           | Modern 15 A10M              | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Acer          | Swift SF114-34              | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Dell          | Inspiron 14 5401            | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| HP            | Pavilion dm4                | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| ASUSTek       | UX303UA                     | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Samsung       | 305V4A/305V5A               | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| HP            | Laptop 15s-fq1xxx           | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Lenovo        | V145-15AST 81MT             | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | G50-45 80E3                 | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| Lenovo        | G50-45 80E3                 | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| Lenovo        | V145-15AST 81MT             | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| EVOO          | EV-C-116-7                  | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| HP            | Pavilion tx1000             | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| HP            | Pavilion dm1                | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Acer          | E3-112M-C6BV                | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| Sony          | VPCEA47FX                   | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Sony          | VPCEJ1L1E                   | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Acer          | Swift SF114-32              | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Dell          | Inspiron 5515               | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Acer          | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| Lenovo        | G570 4334                   | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Inspiron 5570               | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Fujitsu       | LIFEBOOK U9311A             | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| Google        | Peppy                       | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| TUXEDO        | Book XP1511                 | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| TUXEDO        | Book_XA1510                 | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| TUXEDO        | Unknown                     | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| HP            | Notebook                    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| Toshiba       | Satellite P300              | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Acer          | Aspire A515-44              | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| AWOW          | AK41                        | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| ASUSTek       | N53SM                       | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| Dell          | Latitude D531               | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| HP            | Pavilion g6                 | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| HP            | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| Apple         | MacBookPro11,1              | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| HP            | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Timi          | TM1701                      | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| Fujitsu       | LIFEBOOK A555               | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| Dell          | XPS 13 7390                 | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| Positivo      | C14CR21TV                   | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| HUAWEI        | KLVC-WXX9                   | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Dell          | XPS L322X                   | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| ASUSTek       | N53SM                       | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| MSI           | GE70 2PC\2PE                | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Toshiba       | Satellite P750              | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| HP            | Pavilion 17                 | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| TUXEDO        | Aura 15 Gen1                | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Unknown       | Unknown                     | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| Acer          | Aspire E1-532               | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| ASUSTek       | FX503VD                     | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Packard Be... | EasyNote LE69KB             | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| HP            | Laptop 17-ak0xx             | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Sony          | SVS13A25PBS                 | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Fujitsu       | LIFEBOOK E756               | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| HP            | ZBook 14                    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| Dell          | Latitude 5400               | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | Laptop 14-dk0xxx            | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| MSI           | Modern 14 A10RB             | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| Dell          | Latitude 5400               | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| HP            | ProBook 4730s               | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Fujitsu       | LIFEBOOK A512               | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| HP            | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Dell          | Inspiron 11-3168            | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| Sony          | VPCEK20AL                   | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Standard      | MT40II                      | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Apple         | MacBook3,1                  | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| HUAWEI        | MACH-WX9                    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| Dell          | G3 3579                     | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| MSI           | GP72 7RE                    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| ASUSTek       | X510UAR                     | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| TUXEDO        | Unknown                     | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| HP            | Laptop 15-dw0xxx            | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| Acer          | Aspire R3-131T              | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | S400CA                      | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| TUXEDO        | Unknown                     | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| TUXEDO        | Unknown                     | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| TUXEDO        | Unknown                     | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| ASUSTek       | S551LN                      | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| Dell          | Inspiron 1545               | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| HP            | Notebook                    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| Dell          | Inspiron 5770               | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| HP            | Compaq 6720s                | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| Dell          | Latitude 5400               | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | Latitude E6420              | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| ASUSTek       | N501VW                      | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Unknown       | Unknown                     | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| HP            | 2000                        | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Dell          | Inspiron 5559               | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Budgie/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 174       | 31.99%  |
| Ubuntu Budgie 22.04 | 115       | 21.14%  |
| Ubuntu Budgie 24.04 | 49        | 9.01%   |
| Ubuntu Budgie 20.10 | 34        | 6.25%   |
| Ubuntu Budgie 21.10 | 33        | 6.07%   |
| Ubuntu Budgie 22.10 | 27        | 4.96%   |
| Ubuntu Budgie 18.04 | 26        | 4.78%   |
| Ubuntu Budgie 21.04 | 21        | 3.86%   |
| Ubuntu Budgie 23.04 | 17        | 3.13%   |
| Ubuntu Budgie 19.10 | 13        | 2.39%   |
| Ubuntu Budgie 24.10 | 11        | 2.02%   |
| Ubuntu Budgie 23.10 | 11        | 2.02%   |
| Ubuntu Budgie 25.04 | 9         | 1.65%   |
| Ubuntu Budgie 16.04 | 2         | 0.37%   |
| Ubuntu Budgie 25.10 | 1         | 0.18%   |
| Ubuntu Budgie       | 1         | 0.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 519       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 18        | 2.95%   |
| 5.3.0-40-generic  | 10        | 1.64%   |
| 5.4.0-40-generic  | 9         | 1.47%   |
| 5.13.0-22-generic | 9         | 1.47%   |
| 6.2.0-20-generic  | 8         | 1.31%   |
| 5.8.0-41-generic  | 7         | 1.15%   |
| 5.15.0-27-generic | 7         | 1.15%   |
| 5.13.0-28-generic | 7         | 1.15%   |
| 6.8.0-31-generic  | 6         | 0.98%   |
| 5.4.0-37-generic  | 6         | 0.98%   |
| 5.4.0-29-generic  | 6         | 0.98%   |
| 5.13.0-39-generic | 6         | 0.98%   |
| 6.8.0-51-generic  | 5         | 0.82%   |
| 6.8.0-45-generic  | 5         | 0.82%   |
| 6.2.0-26-generic  | 5         | 0.82%   |
| 5.8.0-53-generic  | 5         | 0.82%   |
| 5.8.0-48-generic  | 5         | 0.82%   |
| 5.4.0-52-generic  | 5         | 0.82%   |
| 5.4.0-48-generic  | 5         | 0.82%   |
| 5.4.0-33-generic  | 5         | 0.82%   |
| 5.19.0-46-generic | 5         | 0.82%   |
| 5.19.0-35-generic | 5         | 0.82%   |
| 5.15.0-52-generic | 5         | 0.82%   |
| 5.15.0-50-generic | 5         | 0.82%   |
| 5.15.0-48-generic | 5         | 0.82%   |
| 5.13.0-40-generic | 5         | 0.82%   |
| 5.13.0-35-generic | 5         | 0.82%   |
| 5.13.0-30-generic | 5         | 0.82%   |
| 5.13.0-19-generic | 5         | 0.82%   |
| 5.11.0-41-generic | 5         | 0.82%   |
| 6.8.0-40-generic  | 4         | 0.65%   |
| 6.5.0-9-generic   | 4         | 0.65%   |
| 6.5.0-18-generic  | 4         | 0.65%   |
| 6.5.0-15-generic  | 4         | 0.65%   |
| 6.2.0-39-generic  | 4         | 0.65%   |
| 6.2.0-33-generic  | 4         | 0.65%   |
| 6.14.0-27-generic | 4         | 0.65%   |
| 6.14.0-15-generic | 4         | 0.65%   |
| 6.11.0-18-generic | 4         | 0.65%   |
| 5.8.0-44-generic  | 4         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 107       | 19.11%  |
| 5.15.0  | 80        | 14.29%  |
| 5.8.0   | 54        | 9.64%   |
| 5.13.0  | 53        | 9.46%   |
| 5.19.0  | 41        | 7.32%   |
| 6.8.0   | 36        | 6.43%   |
| 5.11.0  | 35        | 6.25%   |
| 6.2.0   | 33        | 5.89%   |
| 6.5.0   | 26        | 4.64%   |
| 5.3.0   | 21        | 3.75%   |
| 6.14.0  | 19        | 3.39%   |
| 6.11.0  | 18        | 3.21%   |
| 4.15.0  | 12        | 2.14%   |
| 5.6.0   | 3         | 0.54%   |
| 5.12.0  | 2         | 0.36%   |
| 5.0.0   | 2         | 0.36%   |
| 4.18.0  | 2         | 0.36%   |
| 6.8.1   | 1         | 0.18%   |
| 6.5.5   | 1         | 0.18%   |
| 6.3.1   | 1         | 0.18%   |
| 6.17.0  | 1         | 0.18%   |
| 6.1.0   | 1         | 0.18%   |
| 5.9.0   | 1         | 0.18%   |
| 5.8.11  | 1         | 0.18%   |
| 5.6.7   | 1         | 0.18%   |
| 5.5.0   | 1         | 0.18%   |
| 5.18.8  | 1         | 0.18%   |
| 5.18.19 | 1         | 0.18%   |
| 5.16.14 | 1         | 0.18%   |
| 5.15.11 | 1         | 0.18%   |
| 5.10.11 | 1         | 0.18%   |
| 5.10.0  | 1         | 0.18%   |
| 4.4.0   | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 107       | 19.18%  |
| 5.15    | 81        | 14.52%  |
| 5.8     | 55        | 9.86%   |
| 5.13    | 53        | 9.5%    |
| 5.19    | 41        | 7.35%   |
| 6.8     | 36        | 6.45%   |
| 5.11    | 35        | 6.27%   |
| 6.2     | 33        | 5.91%   |
| 6.5     | 27        | 4.84%   |
| 5.3     | 21        | 3.76%   |
| 6.14    | 19        | 3.41%   |
| 6.11    | 18        | 3.23%   |
| 4.15    | 12        | 2.15%   |
| 5.6     | 4         | 0.72%   |
| 5.12    | 2         | 0.36%   |
| 5.10    | 2         | 0.36%   |
| 5.0     | 2         | 0.36%   |
| 4.18    | 2         | 0.36%   |
| 6.3     | 1         | 0.18%   |
| 6.17    | 1         | 0.18%   |
| 6.1     | 1         | 0.18%   |
| 5.9     | 1         | 0.18%   |
| 5.5     | 1         | 0.18%   |
| 5.18    | 1         | 0.18%   |
| 5.16    | 1         | 0.18%   |
| 4.4     | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 516       | 99.42%  |
| i686   | 3         | 0.58%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Budgie     | 500       | 96.34%  |
| GNOME      | 12        | 2.31%   |
| XFCE       | 2         | 0.39%   |
| KDE5       | 2         | 0.39%   |
| X-Cinnamon | 1         | 0.19%   |
| MATE       | 1         | 0.19%   |
| KDE6       | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 506       | 96.75%  |
| Wayland | 16        | 3.06%   |
| Tty     | 1         | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 261       | 49.53%  |
| Unknown | 154       | 29.22%  |
| TDM     | 58        | 11.01%  |
| GDM     | 26        | 4.93%   |
| GDM3    | 23        | 4.36%   |
| SDDM    | 5         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 195       | 37.43%  |
| de_DE   | 59        | 11.32%  |
| fr_FR   | 38        | 7.29%   |
| en_GB   | 29        | 5.57%   |
| pt_BR   | 26        | 4.99%   |
| it_IT   | 19        | 3.65%   |
| ru_RU   | 15        | 2.88%   |
| en_CA   | 15        | 2.88%   |
| en_IN   | 13        | 2.5%    |
| es_ES   | 9         | 1.73%   |
| C       | 9         | 1.73%   |
| es_MX   | 8         | 1.54%   |
| es_AR   | 8         | 1.54%   |
| es_CL   | 6         | 1.15%   |
| en_AU   | 6         | 1.15%   |
| pl_PL   | 5         | 0.96%   |
| en_IE   | 5         | 0.96%   |
| hu_HU   | 4         | 0.77%   |
| pt_PT   | 3         | 0.58%   |
| de_AT   | 3         | 0.58%   |
| cs_CZ   | 3         | 0.58%   |
| Unknown | 3         | 0.58%   |
| nl_BE   | 2         | 0.38%   |
| fr_BE   | 2         | 0.38%   |
| fi_FI   | 2         | 0.38%   |
| eu_ES   | 2         | 0.38%   |
| en_ZA   | 2         | 0.38%   |
| en_SG   | 2         | 0.38%   |
| de_CH   | 2         | 0.38%   |
| zh_TW   | 1         | 0.19%   |
| zh_CN   | 1         | 0.19%   |
| vi_VN   | 1         | 0.19%   |
| uk_UA   | 1         | 0.19%   |
| tr_TR   | 1         | 0.19%   |
| sk_SK   | 1         | 0.19%   |
| nl_NL   | 1         | 0.19%   |
| nb_NO   | 1         | 0.19%   |
| mt_MT   | 1         | 0.19%   |
| lv_LV   | 1         | 0.19%   |
| ko_KR   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 280       | 52.93%  |
| BIOS | 249       | 47.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 421       | 80.34%  |
| Tmpfs   | 66        | 12.6%   |
| Zfs     | 16        | 3.05%   |
| Overlay | 12        | 2.29%   |
| Btrfs   | 5         | 0.95%   |
| Xfs     | 3         | 0.57%   |
| Jfs     | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 289       | 54.73%  |
| Unknown | 195       | 36.93%  |
| MBR     | 44        | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 464       | 88.55%  |
| Yes       | 60        | 11.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 366       | 69.71%  |
| Yes       | 159       | 30.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 99        | 19.08%  |
| Hewlett-Packard     | 83        | 15.99%  |
| Dell                | 76        | 14.64%  |
| ASUSTek Computer    | 60        | 11.56%  |
| TUXEDO              | 46        | 8.86%   |
| Acer                | 29        | 5.59%   |
| Apple               | 28        | 5.39%   |
| MSI                 | 16        | 3.08%   |
| Sony                | 8         | 1.54%   |
| Toshiba             | 7         | 1.35%   |
| HUAWEI              | 7         | 1.35%   |
| Google              | 7         | 1.35%   |
| Samsung Electronics | 6         | 1.16%   |
| Unknown             | 5         | 0.96%   |
| Packard Bell        | 4         | 0.77%   |
| Fujitsu             | 4         | 0.77%   |
| Alienware           | 3         | 0.58%   |
| Timi                | 2         | 0.39%   |
| Standard            | 2         | 0.39%   |
| Razer               | 2         | 0.39%   |
| Positivo            | 2         | 0.39%   |
| Chuwi               | 2         | 0.39%   |
| BANGHO              | 2         | 0.39%   |
| Viglen              | 1         | 0.19%   |
| THUNDEROBOT         | 1         | 0.19%   |
| Thomson             | 1         | 0.19%   |
| Star Labs           | 1         | 0.19%   |
| Quanta              | 1         | 0.19%   |
| PC Specialist       | 1         | 0.19%   |
| Notebook            | 1         | 0.19%   |
| IMUZ                | 1         | 0.19%   |
| HONOR               | 1         | 0.19%   |
| GPU Company         | 1         | 0.19%   |
| Gigabyte Technology | 1         | 0.19%   |
| Gateway             | 1         | 0.19%   |
| EVOO                | 1         | 0.19%   |
| Digibras            | 1         | 0.19%   |
| COM1                | 1         | 0.19%   |
| AXIOO               | 1         | 0.19%   |
| AWOW                | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 15        | 2.89%   |
| TUXEDO Pulse 15 Gen1            | 4         | 0.77%   |
| HP Pavilion g6                  | 4         | 0.77%   |
| Dell Latitude 5480              | 4         | 0.77%   |
| TUXEDO InfinityBook S 15 Gen6   | 3         | 0.58%   |
| TUXEDO Aura 15 Gen1             | 3         | 0.58%   |
| Lenovo G50-45 80E3              | 3         | 0.58%   |
| HP Notebook                     | 3         | 0.58%   |
| Dell Latitude E6420             | 3         | 0.58%   |
| Apple MacBookPro9,2             | 3         | 0.58%   |
| Apple MacBookPro8,1             | 3         | 0.58%   |
| TUXEDO Polaris 15 AMD Gen1      | 2         | 0.39%   |
| TUXEDO InfinityBook S 14 Gen6   | 2         | 0.39%   |
| TUXEDO InfinityBook Pro 14 Gen6 | 2         | 0.39%   |
| TUXEDO Book XP1511              | 2         | 0.39%   |
| Standard MT40II                 | 2         | 0.39%   |
| Packard Bell EasyNote TM98      | 2         | 0.39%   |
| Lenovo Y50-70 20378             | 2         | 0.39%   |
| Lenovo ThinkPad E15 20RD003KHV  | 2         | 0.39%   |
| Lenovo ThinkBook 14-IML 20RV    | 2         | 0.39%   |
| Lenovo IdeaPad C340-14API 81N6  | 2         | 0.39%   |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 2         | 0.39%   |
| Lenovo IdeaPad 330S-15ARR 81FB  | 2         | 0.39%   |
| Lenovo IdeaPad 320-15IKB 80XL   | 2         | 0.39%   |
| Lenovo IdeaPad 110-15ISK 80UD   | 2         | 0.39%   |
| Lenovo G500 20236               | 2         | 0.39%   |
| HP ZBook Studio G3              | 2         | 0.39%   |
| HP ZBook 15 G4                  | 2         | 0.39%   |
| HP Pavilion dv7                 | 2         | 0.39%   |
| HP Pavilion dv6                 | 2         | 0.39%   |
| HP Laptop 15-fc0xxx             | 2         | 0.39%   |
| HP ENVY 17                      | 2         | 0.39%   |
| HP ENVY 15                      | 2         | 0.39%   |
| HP EliteBook 840 G8 Notebook PC | 2         | 0.39%   |
| HP EliteBook 840 G3             | 2         | 0.39%   |
| HP 2000                         | 2         | 0.39%   |
| Dell XPS 13 9380                | 2         | 0.39%   |
| Dell XPS 13 7390                | 2         | 0.39%   |
| Dell Latitude E6540             | 2         | 0.39%   |
| Dell Latitude E6410             | 2         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 47        | 9.06%   |
| Dell Latitude         | 35        | 6.74%   |
| Lenovo IdeaPad        | 27        | 5.2%    |
| HP Pavilion           | 18        | 3.47%   |
| Dell Inspiron         | 16        | 3.08%   |
| Acer Aspire           | 16        | 3.08%   |
| HP EliteBook          | 15        | 2.89%   |
| Unknown               | 15        | 2.89%   |
| Dell XPS              | 12        | 2.31%   |
| ASUS VivoBook         | 12        | 2.31%   |
| TUXEDO InfinityBook   | 11        | 2.12%   |
| HP ZBook              | 9         | 1.73%   |
| HP ProBook            | 8         | 1.54%   |
| HP Laptop             | 8         | 1.54%   |
| Toshiba Satellite     | 7         | 1.35%   |
| HP ENVY               | 7         | 1.35%   |
| TUXEDO Polaris        | 6         | 1.16%   |
| TUXEDO Book           | 6         | 1.16%   |
| Dell Vostro           | 6         | 1.16%   |
| ASUS ASUS             | 6         | 1.16%   |
| Apple MacBookPro8     | 6         | 1.16%   |
| TUXEDO Pulse          | 5         | 0.96%   |
| ASUS ZenBook          | 5         | 0.96%   |
| Acer TravelMate       | 5         | 0.96%   |
| Acer Swift            | 5         | 0.96%   |
| Lenovo ThinkBook      | 4         | 0.77%   |
| Fujitsu LIFEBOOK      | 4         | 0.77%   |
| Dell Precision        | 4         | 0.77%   |
| ASUS ROG              | 4         | 0.77%   |
| Apple MacBookPro11    | 4         | 0.77%   |
| TUXEDO Aura           | 3         | 0.58%   |
| Packard Bell EasyNote | 3         | 0.58%   |
| Lenovo Yoga           | 3         | 0.58%   |
| Lenovo G50-45         | 3         | 0.58%   |
| HP Notebook           | 3         | 0.58%   |
| HP Compaq             | 3         | 0.58%   |
| Apple MacBookPro9     | 3         | 0.58%   |
| Apple MacBookPro15    | 3         | 0.58%   |
| Apple MacBookAir7     | 3         | 0.58%   |
| TUXEDO Stellaris      | 2         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 61        | 11.75%  |
| 2019 | 61        | 11.75%  |
| 2021 | 50        | 9.63%   |
| 2018 | 49        | 9.44%   |
| 2017 | 36        | 6.94%   |
| 2011 | 32        | 6.17%   |
| 2014 | 31        | 5.97%   |
| 2012 | 31        | 5.97%   |
| 2013 | 28        | 5.39%   |
| 2016 | 27        | 5.2%    |
| 2015 | 25        | 4.82%   |
| 2010 | 23        | 4.43%   |
| 2008 | 16        | 3.08%   |
| 2009 | 14        | 2.7%    |
| 2023 | 11        | 2.12%   |
| 2022 | 11        | 2.12%   |
| 2007 | 7         | 1.35%   |
| 2024 | 4         | 0.77%   |
| 2006 | 2         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 519       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 474       | 90.98%  |
| Enabled  | 47        | 9.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 510       | 98.27%  |
| Yes  | 9         | 1.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 153       | 29.2%   |
| 16.01-24.0  | 105       | 20.04%  |
| 8.01-16.0   | 87        | 16.6%   |
| 3.01-4.0    | 85        | 16.22%  |
| 32.01-64.0  | 52        | 9.92%   |
| 64.01-256.0 | 20        | 3.82%   |
| 1.01-2.0    | 11        | 2.1%    |
| 2.01-3.0    | 6         | 1.15%   |
| 24.01-32.0  | 5         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 181       | 31.87%  |
| 1.01-2.0   | 147       | 25.88%  |
| 4.01-8.0   | 107       | 18.84%  |
| 3.01-4.0   | 91        | 16.02%  |
| 8.01-16.0  | 30        | 5.28%   |
| 16.01-24.0 | 5         | 0.88%   |
| 0.51-1.0   | 5         | 0.88%   |
| 24.01-32.0 | 2         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 394       | 75.05%  |
| 2      | 114       | 21.71%  |
| 3      | 14        | 2.67%   |
| 0      | 2         | 0.38%   |
| 4      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 381       | 73.27%  |
| Yes       | 139       | 26.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 411       | 78.59%  |
| No        | 112       | 21.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 509       | 97.88%  |
| No        | 11        | 2.12%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 440       | 84.45%  |
| No        | 81        | 15.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 75        | 14.42%  |
| Germany            | 74        | 14.23%  |
| France             | 38        | 7.31%   |
| Brazil             | 32        | 6.15%   |
| Italy              | 25        | 4.81%   |
| UK                 | 21        | 4.04%   |
| India              | 17        | 3.27%   |
| Russia             | 16        | 3.08%   |
| Canada             | 14        | 2.69%   |
| Spain              | 13        | 2.5%    |
| Netherlands        | 13        | 2.5%    |
| Poland             | 12        | 2.31%   |
| Argentina          | 10        | 1.92%   |
| Mexico             | 9         | 1.73%   |
| Chile              | 6         | 1.15%   |
| Belgium            | 6         | 1.15%   |
| Austria            | 6         | 1.15%   |
| Australia          | 6         | 1.15%   |
| Ukraine            | 5         | 0.96%   |
| Switzerland        | 5         | 0.96%   |
| South Africa       | 5         | 0.96%   |
| Ireland            | 5         | 0.96%   |
| Hungary            | 5         | 0.96%   |
| Czechia            | 5         | 0.96%   |
| Turkey             | 4         | 0.77%   |
| Sweden             | 4         | 0.77%   |
| Portugal           | 4         | 0.77%   |
| Norway             | 4         | 0.77%   |
| Iran               | 4         | 0.77%   |
| Indonesia          | 4         | 0.77%   |
| Greece             | 4         | 0.77%   |
| Finland            | 4         | 0.77%   |
| Colombia           | 4         | 0.77%   |
| Slovenia           | 3         | 0.58%   |
| Japan              | 3         | 0.58%   |
| Dominican Republic | 3         | 0.58%   |
| Slovakia           | 2         | 0.38%   |
| Singapore          | 2         | 0.38%   |
| Romania            | 2         | 0.38%   |
| Peru               | 2         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 7         | 1.29%   |
| Berlin             | 7         | 1.29%   |
| Moscow             | 6         | 1.11%   |
| Paris              | 5         | 0.92%   |
| Dublin             | 5         | 0.92%   |
| Budapest           | 5         | 0.92%   |
| Warsaw             | 4         | 0.74%   |
| Tehran             | 4         | 0.74%   |
| Ravensburg         | 4         | 0.74%   |
| Prague             | 4         | 0.74%   |
| Nuremberg          | 4         | 0.74%   |
| Munich             | 4         | 0.74%   |
| Los Angeles        | 4         | 0.74%   |
| Brasília          | 4         | 0.74%   |
| Austin             | 4         | 0.74%   |
| Athens             | 4         | 0.74%   |
| Vienna             | 3         | 0.55%   |
| St Petersburg      | 3         | 0.55%   |
| Santo Domingo Este | 3         | 0.55%   |
| Pune               | 3         | 0.55%   |
| Mumbai             | 3         | 0.55%   |
| Montreal           | 3         | 0.55%   |
| Milan              | 3         | 0.55%   |
| Kyiv               | 3         | 0.55%   |
| Hamburg            | 3         | 0.55%   |
| Frankfurt am Main  | 3         | 0.55%   |
| Dresden            | 3         | 0.55%   |
| Belo Horizonte     | 3         | 0.55%   |
| Wolfsburg          | 2         | 0.37%   |
| Victoria           | 2         | 0.37%   |
| Vancouver          | 2         | 0.37%   |
| The Hague          | 2         | 0.37%   |
| Sydney             | 2         | 0.37%   |
| Sunnyvale          | 2         | 0.37%   |
| Stuttgart          | 2         | 0.37%   |
| St Louis           | 2         | 0.37%   |
| Singapore          | 2         | 0.37%   |
| Santiago           | 2         | 0.37%   |
| San Miguel         | 2         | 0.37%   |
| San Jose           | 2         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 137       | 184    | 21.57%  |
| WDC                       | 63        | 68     | 9.92%   |
| Toshiba                   | 53        | 72     | 8.35%   |
| Seagate                   | 52        | 55     | 8.19%   |
| Unknown                   | 43        | 52     | 6.77%   |
| SanDisk                   | 36        | 42     | 5.67%   |
| Micron Technology         | 25        | 29     | 3.94%   |
| SK hynix                  | 24        | 27     | 3.78%   |
| Kingston                  | 23        | 25     | 3.62%   |
| Crucial                   | 21        | 33     | 3.31%   |
| Intel                     | 20        | 26     | 3.15%   |
| Apple                     | 14        | 14     | 2.2%    |
| Hitachi                   | 12        | 12     | 1.89%   |
| HGST                      | 11        | 15     | 1.73%   |
| A-DATA Technology         | 11        | 13     | 1.73%   |
| China                     | 8         | 13     | 1.26%   |
| SPCC                      | 7         | 8      | 1.1%    |
| KIOXIA                    | 6         | 7      | 0.94%   |
| PNY                       | 5         | 13     | 0.79%   |
| Patriot                   | 3         | 3      | 0.47%   |
| LITEON                    | 3         | 4      | 0.47%   |
| JMicron Technology        | 3         | 3      | 0.47%   |
| Unknown                   | 3         | 3      | 0.47%   |
| Transcend                 | 2         | 2      | 0.31%   |
| Micron/Crucial Technology | 2         | 2      | 0.31%   |
| Lenovo                    | 2         | 2      | 0.31%   |
| KingSpec                  | 2         | 2      | 0.31%   |
| Intenso                   | 2         | 3      | 0.31%   |
| Hewlett-Packard           | 2         | 1      | 0.31%   |
| Gigabyte Technology       | 2         | 2      | 0.31%   |
| Fujitsu                   | 2         | 2      | 0.31%   |
| Corsair                   | 2         | 3      | 0.31%   |
| YMTC                      | 1         | 1      | 0.16%   |
| VISIPRO                   | 1         | 1      | 0.16%   |
| Vaseky                    | 1         | 1      | 0.16%   |
| USB30                     | 1         | 1      | 0.16%   |
| Union Memory              | 1         | 1      | 0.16%   |
| UMAX                      | 1         | 1      | 0.16%   |
| TO Exter                  | 1         | 1      | 0.16%   |
| Teclast                   | 1         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                            | 7         | 1.07%   |
| Unknown MMC Card  32GB                            | 7         | 1.07%   |
| Toshiba MQ04ABF100 1TB                            | 7         | 1.07%   |
| Toshiba MQ01ABD100 1TB                            | 7         | 1.07%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 7         | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB                    | 6         | 0.91%   |
| Samsung SSD 860 EVO M.2 500GB                     | 6         | 0.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6         | 0.91%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 5         | 0.76%   |
| Seagate ST9500325AS 500GB                         | 5         | 0.76%   |
| Samsung SSD 860 EVO M.2 250GB                     | 5         | 0.76%   |
| Samsung SSD 860 EVO 500GB                         | 5         | 0.76%   |
| Samsung NVMe SSD Drive 1TB                        | 5         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB                      | 4         | 0.61%   |
| Unknown SD/MMC/MS PRO 2GB                         | 4         | 0.61%   |
| SK hynix NVMe SSD Drive 256GB                     | 4         | 0.61%   |
| SanDisk NVMe SSD Drive 512GB                      | 4         | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB                    | 4         | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB                      | 4         | 0.61%   |
| Samsung NVMe SSD Drive 512GB                      | 4         | 0.61%   |
| Samsung NVMe SSD Drive 500GB                      | 4         | 0.61%   |
| Kingston SA400S37240G 240GB SSD                   | 4         | 0.61%   |
| Unknown SR32G  32GB                               | 3         | 0.46%   |
| Unknown SD64G  64GB                               | 3         | 0.46%   |
| Unknown MMC Card  16GB                            | 3         | 0.46%   |
| Toshiba MQ01ABD050 500GB                          | 3         | 0.46%   |
| SPCC Solid State Disk 120GB                       | 3         | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive 512GB       | 3         | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 0.46%   |
| Seagate ST1000LX015-1U7172 1TB                    | 3         | 0.46%   |
| SanDisk SSD PLUS 480GB                            | 3         | 0.46%   |
| Samsung SSD 980 PRO 1TB                           | 3         | 0.46%   |
| Samsung SSD 980 500GB                             | 3         | 0.46%   |
| Samsung SSD 970 EVO 500GB                         | 3         | 0.46%   |
| Samsung SSD 860 EVO 250GB                         | 3         | 0.46%   |
| Samsung SSD 840 EVO 250GB                         | 3         | 0.46%   |
| Samsung SSD 750 EVO 250GB                         | 3         | 0.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB            | 3         | 0.46%   |
| Samsung NVMe SSD Drive 2TB                        | 3         | 0.46%   |
| Samsung MZALQ512HALU-000L2 512GB                  | 3         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 52     | 32.24%  |
| Toshiba             | 35        | 42     | 23.03%  |
| WDC                 | 32        | 35     | 21.05%  |
| Hitachi             | 12        | 12     | 7.89%   |
| HGST                | 11        | 15     | 7.24%   |
| Unknown             | 4         | 4      | 2.63%   |
| Samsung Electronics | 3         | 3      | 1.97%   |
| JMicron Technology  | 2         | 2      | 1.32%   |
| Fujitsu             | 2         | 2      | 1.32%   |
| TO Exter            | 1         | 1      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 82     | 25.33%  |
| SanDisk             | 21        | 22     | 9.33%   |
| Crucial             | 20        | 32     | 8.89%   |
| Kingston            | 19        | 20     | 8.44%   |
| WDC                 | 12        | 13     | 5.33%   |
| Apple               | 10        | 10     | 4.44%   |
| Micron Technology   | 9         | 10     | 4%      |
| Intel               | 8         | 9      | 3.56%   |
| China               | 8         | 13     | 3.56%   |
| SPCC                | 7         | 8      | 3.11%   |
| A-DATA Technology   | 7         | 8      | 3.11%   |
| PNY                 | 5         | 13     | 2.22%   |
| Toshiba             | 4         | 4      | 1.78%   |
| SK hynix            | 4         | 5      | 1.78%   |
| Patriot             | 3         | 3      | 1.33%   |
| LITEON              | 3         | 4      | 1.33%   |
| Transcend           | 2         | 2      | 0.89%   |
| Seagate             | 2         | 2      | 0.89%   |
| KingSpec            | 2         | 2      | 0.89%   |
| Intenso             | 2         | 3      | 0.89%   |
| Gigabyte Technology | 2         | 2      | 0.89%   |
| VISIPRO             | 1         | 1      | 0.44%   |
| Vaseky              | 1         | 1      | 0.44%   |
| USB30               | 1         | 1      | 0.44%   |
| Unknown             | 1         | 1      | 0.44%   |
| Union Memory        | 1         | 1      | 0.44%   |
| UMAX                | 1         | 1      | 0.44%   |
| Teclast             | 1         | 2      | 0.44%   |
| Star                | 1         | 1      | 0.44%   |
| Plextor             | 1         | 1      | 0.44%   |
| OWC                 | 1         | 1      | 0.44%   |
| OCZ                 | 1         | 1      | 0.44%   |
| Netac               | 1         | 1      | 0.44%   |
| LITEONIT            | 1         | 1      | 0.44%   |
| Hewlett-Packard     | 1         | 1      | 0.44%   |
| FORESEE             | 1         | 1      | 0.44%   |
| Dogfish             | 1         | 1      | 0.44%   |
| Corsair             | 1         | 2      | 0.44%   |
| BIWIN               | 1         | 1      | 0.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 209       | 287    | 34.38%  |
| NVMe    | 204       | 261    | 33.55%  |
| HDD     | 145       | 169    | 23.85%  |
| MMC     | 39        | 50     | 6.41%   |
| Unknown | 11        | 11     | 1.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 316       | 444    | 54.39%  |
| NVMe | 204       | 260    | 35.11%  |
| MMC  | 39        | 50     | 6.71%   |
| SAS  | 22        | 24     | 3.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 237       | 300    | 67.33%  |
| 0.51-1.0   | 99        | 136    | 28.13%  |
| 1.01-2.0   | 14        | 18     | 3.98%   |
| 3.01-4.0   | 2         | 2      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 171       | 32.51%  |
| 251-500        | 152       | 28.9%   |
| 501-1000       | 75        | 14.26%  |
| 51-100         | 36        | 6.84%   |
| 1001-2000      | 27        | 5.13%   |
| 21-50          | 25        | 4.75%   |
| 1-20           | 24        | 4.56%   |
| 2001-3000      | 9         | 1.71%   |
| More than 3000 | 4         | 0.76%   |
| Unknown        | 3         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 194       | 35.4%   |
| 21-50          | 112       | 20.44%  |
| 101-250        | 94        | 17.15%  |
| 51-100         | 67        | 12.23%  |
| 251-500        | 46        | 8.39%   |
| 501-1000       | 21        | 3.83%   |
| 1001-2000      | 9         | 1.64%   |
| Unknown        | 3         | 0.55%   |
| More than 3000 | 2         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                       | 2         | 2      | 7.14%   |
| Seagate ST9500325AS 500GB                    | 2         | 2      | 7.14%   |
| WDC WD6400BPVT-60HXZT3 640GB                 | 1         | 1      | 3.57%   |
| WDC WD5000BPVT-00HXZT1 500GB                 | 1         | 1      | 3.57%   |
| WDC WD2500BEKT-75PVMT1 250GB                 | 1         | 1      | 3.57%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 3.57%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD075 752GB                     | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 3.57%   |
| Toshiba MK5055GSX 500GB                      | 1         | 1      | 3.57%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 3.57%   |
| Toshiba MK2561GSYN 250GB                     | 1         | 1      | 3.57%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 3.57%   |
| Seagate ST9500423AS 500GB                    | 1         | 1      | 3.57%   |
| Seagate ST500LX012-1LM162-SSHD 500GB         | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.57%   |
| Samsung Electronics MZVLQ512HBLU-00B00 512GB | 1         | 1      | 3.57%   |
| PNY SSD2SC120G3LC709B121-460I 120GB          | 1         | 1      | 3.57%   |
| Kingston SNS4151S316G 16GB SSD               | 1         | 1      | 3.57%   |
| Intel SSDSCKKF256H6 SATA 256GB               | 1         | 1      | 3.57%   |
| HGST HTS725032A7E630 320GB                   | 1         | 2      | 3.57%   |
| HGST HTS541075A9E680 752GB                   | 1         | 1      | 3.57%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 3.57%   |
| Crucial CT500P1SSD8 500GB                    | 1         | 1      | 3.57%   |
| China SSD 256GB                              | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 8      | 28.57%  |
| Seagate             | 7         | 7      | 25%     |
| WDC                 | 4         | 4      | 14.29%  |
| HGST                | 3         | 4      | 10.71%  |
| Samsung Electronics | 1         | 1      | 3.57%   |
| PNY                 | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 8      | 36.36%  |
| Seagate | 7         | 7      | 31.82%  |
| WDC     | 4         | 4      | 18.18%  |
| HGST    | 3         | 4      | 13.64%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 23     | 78.57%  |
| SSD  | 4         | 4      | 14.29%  |
| NVMe | 2         | 2      | 7.14%   |

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
| Detected | 307       | 457    | 56.43%  |
| Works    | 210       | 292    | 38.6%   |
| Malfunc  | 27        | 29     | 4.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 351       | 57.73%  |
| Samsung Electronics            | 88        | 14.47%  |
| AMD                            | 44        | 7.24%   |
| SanDisk                        | 33        | 5.43%   |
| SK hynix                       | 18        | 2.96%   |
| Micron Technology              | 17        | 2.8%    |
| Toshiba America Info Systems   | 14        | 2.3%    |
| KIOXIA                         | 6         | 0.99%   |
| Kingston Technology Company    | 5         | 0.82%   |
| Nvidia                         | 4         | 0.66%   |
| ADATA Technology               | 4         | 0.66%   |
| Phison Electronics             | 3         | 0.49%   |
| Micron/Crucial Technology      | 3         | 0.49%   |
| Apple                          | 3         | 0.49%   |
| Solid State Storage Technology | 2         | 0.33%   |
| Silicon Motion                 | 2         | 0.33%   |
| Realtek Semiconductor          | 2         | 0.33%   |
| Lenovo                         | 2         | 0.33%   |
| Yangtze Memory Technologies    | 1         | 0.16%   |
| Union Memory (Shenzhen)        | 1         | 0.16%   |
| Solidigm                       | 1         | 0.16%   |
| Shenzhen Longsys Electronics   | 1         | 0.16%   |
| Marvell Technology Group       | 1         | 0.16%   |
| INNOGRIT                       | 1         | 0.16%   |
| Hosin Global Electronics       | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 45        | 7.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 41        | 6.44%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 40        | 6.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 34        | 5.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 28        | 4.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 3.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 18        | 2.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17        | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 15        | 2.35%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 2.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 14        | 2.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 2.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 13        | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 13        | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 1.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 10        | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 1.41%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.1%    |
| Intel SSD 660P Series                                                          | 7         | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.1%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 0.94%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.94%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 0.78%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 5         | 0.78%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 5         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 0.78%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 4         | 0.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.63%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 4         | 0.63%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 4         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 359       | 57.72%  |
| NVMe | 206       | 33.12%  |
| RAID | 41        | 6.59%   |
| IDE  | 16        | 2.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 444       | 85.55%  |
| AMD    | 75        | 14.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 3.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 2.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 2.31%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 1.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 1.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.16%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.16%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.96%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.96%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 4         | 0.77%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 4         | 0.77%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 0.77%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.77%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.77%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 0.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.77%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.58%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 0.58%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.58%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 3         | 0.58%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 3         | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.58%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 163       | 31.41%  |
| Intel Core i5                  | 120       | 23.12%  |
| Other                          | 47        | 9.06%   |
| Intel Core i3                  | 31        | 5.97%   |
| Intel Celeron                  | 25        | 4.82%   |
| AMD Ryzen 7                    | 23        | 4.43%   |
| AMD Ryzen 5                    | 19        | 3.66%   |
| Intel Core 2 Duo               | 17        | 3.28%   |
| Intel Pentium                  | 11        | 2.12%   |
| Intel Pentium Silver           | 7         | 1.35%   |
| Intel Atom                     | 7         | 1.35%   |
| AMD A6                         | 6         | 1.16%   |
| AMD Ryzen 9                    | 5         | 0.96%   |
| AMD A8                         | 4         | 0.77%   |
| Intel Pentium Dual-Core        | 3         | 0.58%   |
| Intel Pentium Dual             | 3         | 0.58%   |
| Intel Core i9                  | 3         | 0.58%   |
| AMD Ryzen 5 PRO                | 3         | 0.58%   |
| AMD Ryzen 3                    | 3         | 0.58%   |
| AMD E                          | 3         | 0.58%   |
| Intel Xeon                     | 2         | 0.39%   |
| Intel Genuine                  | 2         | 0.39%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.39%   |
| Intel Core m5                  | 1         | 0.19%   |
| Intel Core m3                  | 1         | 0.19%   |
| Intel Core                     | 1         | 0.19%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.19%   |
| AMD Ryzen 7 PRO                | 1         | 0.19%   |
| AMD Quad-Core                  | 1         | 0.19%   |
| AMD E1                         | 1         | 0.19%   |
| AMD Athlon II                  | 1         | 0.19%   |
| AMD A4                         | 1         | 0.19%   |
| AMD A10                        | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 213       | 41.04%  |
| 4      | 211       | 40.66%  |
| 8      | 39        | 7.51%   |
| 6      | 37        | 7.13%   |
| 16     | 5         | 0.96%   |
| 10     | 5         | 0.96%   |
| 1      | 4         | 0.77%   |
| 14     | 3         | 0.58%   |
| 12     | 2         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 519       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 405       | 78.03%  |
| 1      | 114       | 21.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 518       | 99.81%  |
| 32-bit         | 1         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 237       | 44.22%  |
| 0x206a7    | 26        | 4.85%   |
| 0x806ec    | 24        | 4.48%   |
| 0x306a9    | 19        | 3.54%   |
| 0x806ea    | 15        | 2.8%    |
| 0x906ea    | 14        | 2.61%   |
| 0x806c1    | 14        | 2.61%   |
| 0x406e3    | 12        | 2.24%   |
| 0x806e9    | 11        | 2.05%   |
| 0x40651    | 11        | 2.05%   |
| 0x306c3    | 10        | 1.87%   |
| 0x306d4    | 9         | 1.68%   |
| 0x906e9    | 8         | 1.49%   |
| 0x806eb    | 8         | 1.49%   |
| 0xa0652    | 7         | 1.31%   |
| 0x20655    | 7         | 1.31%   |
| 0x0a50000c | 6         | 1.12%   |
| 0x08600106 | 6         | 1.12%   |
| 0x08600103 | 6         | 1.12%   |
| 0x1067a    | 5         | 0.93%   |
| 0x806d1    | 4         | 0.75%   |
| 0x706a8    | 4         | 0.75%   |
| 0x506e3    | 4         | 0.75%   |
| 0x10676    | 4         | 0.75%   |
| 0x08600104 | 4         | 0.75%   |
| 0x08108109 | 4         | 0.75%   |
| 0xa0660    | 3         | 0.56%   |
| 0x706e5    | 3         | 0.56%   |
| 0x406c3    | 3         | 0.56%   |
| 0x30678    | 3         | 0.56%   |
| 0x08608103 | 3         | 0.56%   |
| 0x0810100b | 3         | 0.56%   |
| 0x05000119 | 3         | 0.56%   |
| 0x906c0    | 2         | 0.37%   |
| 0x906a3    | 2         | 0.37%   |
| 0x706a1    | 2         | 0.37%   |
| 0x6fd      | 2         | 0.37%   |
| 0x506c9    | 2         | 0.37%   |
| 0x40661    | 2         | 0.37%   |
| 0x20652    | 2         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 126       | 24.28%  |
| Haswell          | 37        | 7.13%   |
| SandyBridge      | 35        | 6.74%   |
| IvyBridge        | 33        | 6.36%   |
| Skylake          | 30        | 5.78%   |
| TigerLake        | 26        | 5.01%   |
| Zen 2            | 23        | 4.43%   |
| Broadwell        | 21        | 4.05%   |
| Unknown          | 19        | 3.66%   |
| Penryn           | 18        | 3.47%   |
| Westmere         | 17        | 3.28%   |
| Silvermont       | 17        | 3.28%   |
| CometLake        | 17        | 3.28%   |
| Goldmont plus    | 16        | 3.08%   |
| IceLake          | 13        | 2.5%    |
| Zen 3            | 10        | 1.93%   |
| Alderlake Hybrid | 9         | 1.73%   |
| Zen+             | 7         | 1.35%   |
| Goldmont         | 6         | 1.16%   |
| Core             | 6         | 1.16%   |
| Zen              | 4         | 0.77%   |
| Puma             | 4         | 0.77%   |
| Nehalem          | 3         | 0.58%   |
| Jaguar           | 3         | 0.58%   |
| Excavator        | 3         | 0.58%   |
| Bobcat           | 3         | 0.58%   |
| Tremont          | 2         | 0.39%   |
| Piledriver       | 2         | 0.39%   |
| K8 Hammer        | 2         | 0.39%   |
| K10 Llano        | 2         | 0.39%   |
| Bonnell          | 2         | 0.39%   |
| P6               | 1         | 0.19%   |
| K8 & K10 hybrid  | 1         | 0.19%   |
| K10              | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 414       | 63.21%  |
| Nvidia | 140       | 21.37%  |
| AMD    | 101       | 15.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 4.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 4.65%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 29        | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 3.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 3.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 22        | 3.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 2.85%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 18        | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 2.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.4%    |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 15        | 2.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 2.25%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 15        | 2.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.65%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 10        | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.05%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 6         | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.9%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.75%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 0.75%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 5         | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 0.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 4         | 0.6%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.6%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.6%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.6%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 286       | 55.11%  |
| Intel + Nvidia | 103       | 19.85%  |
| 1 x AMD        | 63        | 12.14%  |
| 1 x Nvidia     | 25        | 4.82%   |
| Intel + AMD    | 22        | 4.24%   |
| AMD + Nvidia   | 11        | 2.12%   |
| 2 x AMD        | 5         | 0.96%   |
| Other          | 2         | 0.39%   |
| 2 x Nvidia     | 1         | 0.19%   |
| 2 x Intel      | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 427       | 81.18%  |
| Proprietary | 77        | 14.64%  |
| Unknown     | 22        | 4.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 393       | 74.71%  |
| 1.01-2.0   | 40        | 7.6%    |
| 0.01-0.5   | 29        | 5.51%   |
| 3.01-4.0   | 21        | 3.99%   |
| 0.51-1.0   | 20        | 3.8%    |
| 7.01-8.0   | 11        | 2.09%   |
| 5.01-6.0   | 9         | 1.71%   |
| 8.01-16.0  | 2         | 0.38%   |
| 2.01-3.0   | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 104       | 17.08%  |
| AU Optronics            | 101       | 16.58%  |
| BOE                     | 89        | 14.61%  |
| LG Display              | 69        | 11.33%  |
| Samsung Electronics     | 51        | 8.37%   |
| Apple                   | 27        | 4.43%   |
| Dell                    | 21        | 3.45%   |
| Goldstar                | 17        | 2.79%   |
| Sharp                   | 14        | 2.3%    |
| Chi Mei Optoelectronics | 14        | 2.3%    |
| Lenovo                  | 10        | 1.64%   |
| PANDA                   | 9         | 1.48%   |
| Philips                 | 8         | 1.31%   |
| Acer                    | 8         | 1.31%   |
| Hewlett-Packard         | 7         | 1.15%   |
| BenQ                    | 7         | 1.15%   |
| InfoVision              | 5         | 0.82%   |
| AOC                     | 5         | 0.82%   |
| Ancor Communications    | 4         | 0.66%   |
| LGD                     | 3         | 0.49%   |
| LG Philips              | 3         | 0.49%   |
| ASUSTek Computer        | 3         | 0.49%   |
| Unknown (AAA)           | 2         | 0.33%   |
| Sony                    | 2         | 0.33%   |
| Iiyama                  | 2         | 0.33%   |
| HKC                     | 2         | 0.33%   |
| Fujitsu Siemens         | 2         | 0.33%   |
| CSO                     | 2         | 0.33%   |
| Vestel Elektronik       | 1         | 0.16%   |
| UPD                     | 1         | 0.16%   |
| Unknown                 | 1         | 0.16%   |
| TMX                     | 1         | 0.16%   |
| S2-Tek                  | 1         | 0.16%   |
| MStar                   | 1         | 0.16%   |
| LaCie                   | 1         | 0.16%   |
| KTC                     | 1         | 0.16%   |
| KDC                     | 1         | 0.16%   |
| JDZ                     | 1         | 0.16%   |
| JDI                     | 1         | 0.16%   |
| InnoLux Display         | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 6         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 6         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.65%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 4         | 0.65%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 4         | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.65%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 3         | 0.49%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 3         | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.49%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.49%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.49%   |
| BOE LCD Monitor BOE070D 1366x768 309x173mm 13.9-inch                  | 3         | 0.49%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch        | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 3         | 0.49%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 0.49%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2         | 0.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 0.32%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch             | 2         | 0.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.32%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 2         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 253       | 44.7%   |
| 1366x768 (WXGA)    | 147       | 25.97%  |
| 2560x1440 (QHD)    | 24        | 4.24%   |
| 1600x900 (HD+)     | 23        | 4.06%   |
| 3840x2160 (4K)     | 21        | 3.71%   |
| 1280x800 (WXGA)    | 19        | 3.36%   |
| 1920x1200 (WUXGA)  | 14        | 2.47%   |
| 1440x900 (WXGA+)   | 13        | 2.3%    |
| 2880x1800          | 8         | 1.41%   |
| 3440x1440          | 7         | 1.24%   |
| 2560x1600          | 6         | 1.06%   |
| 2560x1080          | 4         | 0.71%   |
| 1680x1050 (WSXGA+) | 4         | 0.71%   |
| 3200x1800 (QHD+)   | 3         | 0.53%   |
| 1280x1024 (SXGA)   | 3         | 0.53%   |
| 3000x2000          | 2         | 0.35%   |
| 2256x1504          | 2         | 0.35%   |
| 2160x1440          | 2         | 0.35%   |
| 1920x1280          | 2         | 0.35%   |
| 1360x768           | 2         | 0.35%   |
| 3840x2400          | 1         | 0.18%   |
| 3840x1100          | 1         | 0.18%   |
| 3840x1080          | 1         | 0.18%   |
| 3456x2160          | 1         | 0.18%   |
| 2520x1680          | 1         | 0.18%   |
| 1600x1200          | 1         | 0.18%   |
| 1280x768           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 229       | 37.3%   |
| 13      | 113       | 18.4%   |
| 14      | 70        | 11.4%   |
| 17      | 37        | 6.03%   |
| 24      | 30        | 4.89%   |
| 27      | 19        | 3.09%   |
| 23      | 16        | 2.61%   |
| 21      | 14        | 2.28%   |
| 11      | 14        | 2.28%   |
| 12      | 10        | 1.63%   |
| 34      | 8         | 1.3%    |
| 31      | 7         | 1.14%   |
| 19      | 6         | 0.98%   |
| Unknown | 6         | 0.98%   |
| 16      | 5         | 0.81%   |
| 84      | 3         | 0.49%   |
| 63      | 3         | 0.49%   |
| 40      | 3         | 0.49%   |
| 32      | 3         | 0.49%   |
| 20      | 3         | 0.49%   |
| 18      | 3         | 0.49%   |
| 72      | 2         | 0.33%   |
| 48      | 2         | 0.33%   |
| 22      | 2         | 0.33%   |
| 60      | 1         | 0.16%   |
| 54      | 1         | 0.16%   |
| 44      | 1         | 0.16%   |
| 42      | 1         | 0.16%   |
| 29      | 1         | 0.16%   |
| 10      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 356       | 58.55%  |
| 201-300     | 79        | 12.99%  |
| 501-600     | 59        | 9.7%    |
| 351-400     | 46        | 7.57%   |
| 401-500     | 25        | 4.11%   |
| 701-800     | 11        | 1.81%   |
| 601-700     | 9         | 1.48%   |
| 1001-1500   | 7         | 1.15%   |
| Unknown     | 6         | 0.99%   |
| 1501-2000   | 5         | 0.82%   |
| 801-900     | 3         | 0.49%   |
| 901-1000    | 2         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 437       | 81.53%  |
| 16/10   | 70        | 13.06%  |
| 3/2     | 10        | 1.87%   |
| 21/9    | 8         | 1.49%   |
| Unknown | 5         | 0.93%   |
| 5/4     | 3         | 0.56%   |
| 4/3     | 1         | 0.19%   |
| 32/9    | 1         | 0.19%   |
| 3.40    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 228       | 37.32%  |
| 81-90          | 147       | 24.06%  |
| 201-250        | 50        | 8.18%   |
| 71-80          | 33        | 5.4%    |
| 121-130        | 30        | 4.91%   |
| 351-500        | 19        | 3.11%   |
| 301-350        | 19        | 3.11%   |
| 51-60          | 15        | 2.45%   |
| More than 1000 | 11        | 1.8%    |
| 61-70          | 10        | 1.64%   |
| 151-200        | 10        | 1.64%   |
| 251-300        | 8         | 1.31%   |
| 131-140        | 7         | 1.15%   |
| 501-1000       | 6         | 0.98%   |
| Unknown        | 6         | 0.98%   |
| 111-120        | 5         | 0.82%   |
| 141-150        | 3         | 0.49%   |
| 91-100         | 3         | 0.49%   |
| 41-50          | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 235       | 39.3%   |
| 101-120       | 176       | 29.43%  |
| 51-100        | 92        | 15.38%  |
| 161-240       | 52        | 8.7%    |
| More than 240 | 24        | 4.01%   |
| 1-50          | 13        | 2.17%   |
| Unknown       | 6         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 415       | 77.72%  |
| 2     | 100       | 18.73%  |
| 3     | 10        | 1.87%   |
| 0     | 9         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 298       | 35.69%  |
| Realtek Semiconductor                 | 259       | 31.02%  |
| Qualcomm Atheros                      | 99        | 11.86%  |
| Broadcom                              | 56        | 6.71%   |
| Broadcom Limited                      | 19        | 2.28%   |
| MediaTek                              | 16        | 1.92%   |
| Marvell Technology Group              | 9         | 1.08%   |
| Ralink                                | 7         | 0.84%   |
| DisplayLink                           | 7         | 0.84%   |
| ASIX Electronics                      | 6         | 0.72%   |
| Lenovo                                | 5         | 0.6%    |
| Hewlett-Packard                       | 5         | 0.6%    |
| Xiaomi                                | 4         | 0.48%   |
| TP-Link                               | 4         | 0.48%   |
| Shenzhen Goodix Technology            | 4         | 0.48%   |
| Samsung Electronics                   | 4         | 0.48%   |
| JMicron Technology                    | 4         | 0.48%   |
| Sierra Wireless                       | 3         | 0.36%   |
| NetGear                               | 3         | 0.36%   |
| Huawei Technologies                   | 3         | 0.36%   |
| Ralink Technology                     | 2         | 0.24%   |
| Nvidia                                | 2         | 0.24%   |
| ASUSTek Computer                      | 2         | 0.24%   |
| ZyXEL Communications                  | 1         | 0.12%   |
| Realtek                               | 1         | 0.12%   |
| Qualcomm Atheros Communications       | 1         | 0.12%   |
| Novatek Microelectronics              | 1         | 0.12%   |
| Motorola PCS                          | 1         | 0.12%   |
| Google                                | 1         | 0.12%   |
| Fibocom                               | 1         | 0.12%   |
| Ericsson Business Mobile Networks     | 1         | 0.12%   |
| Edimax Technology                     | 1         | 0.12%   |
| Dell                                  | 1         | 0.12%   |
| D-Link                                | 1         | 0.12%   |
| BUFFALO                               | 1         | 0.12%   |
| Apple                                 | 1         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156       | 15.57%  |
| Intel Wi-Fi 6 AX200                                                    | 45        | 4.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37        | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 31        | 3.09%   |
| Intel Wireless 8265 / 8275                                             | 31        | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 20        | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 1.9%    |
| Intel Wireless 8260                                                    | 18        | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 17        | 1.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 16        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15        | 1.5%    |
| Intel Wi-Fi 6 AX201                                                    | 15        | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 15        | 1.5%    |
| Intel Wireless 7265                                                    | 14        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 13        | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.1%    |
| Intel Wireless 7260                                                    | 11        | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 10        | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10        | 1%      |
| Broadcom BCM43142 802.11b/g/n                                          | 10        | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 0.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.9%    |
| Broadcom BCM4331 802.11a/b/g/n                                         | 9         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 8         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 0.7%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 6         | 0.6%    |
| Intel Wireless 3165                                                    | 6         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6         | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                          | 6         | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 5         | 0.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 281       | 52.62%  |
| Qualcomm Atheros                      | 81        | 15.17%  |
| Realtek Semiconductor                 | 67        | 12.55%  |
| Broadcom                              | 47        | 8.8%    |
| MediaTek                              | 16        | 3%      |
| Broadcom Limited                      | 13        | 2.43%   |
| Ralink                                | 7         | 1.31%   |
| TP-Link                               | 3         | 0.56%   |
| Sierra Wireless                       | 3         | 0.56%   |
| NetGear                               | 3         | 0.56%   |
| Ralink Technology                     | 2         | 0.37%   |
| ASUSTek Computer                      | 2         | 0.37%   |
| ZyXEL Communications                  | 1         | 0.19%   |
| Realtek                               | 1         | 0.19%   |
| Qualcomm Atheros Communications       | 1         | 0.19%   |
| Hewlett-Packard                       | 1         | 0.19%   |
| Fibocom                               | 1         | 0.19%   |
| Edimax Technology                     | 1         | 0.19%   |
| D-Link                                | 1         | 0.19%   |
| BUFFALO                               | 1         | 0.19%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 45        | 8.41%   |
| Intel Wireless 8265 / 8275                                           | 31        | 5.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 20        | 3.74%   |
| Intel Wireless 8260                                                  | 18        | 3.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 17        | 3.18%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 16        | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 15        | 2.8%    |
| Intel Wi-Fi 6 AX201                                                  | 15        | 2.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 15        | 2.8%    |
| Intel Wireless 7265                                                  | 14        | 2.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 13        | 2.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 11        | 2.06%   |
| Intel Wireless 7260                                                  | 11        | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 11        | 2.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 10        | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 10        | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                        | 10        | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 9         | 1.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 9         | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 8         | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 7         | 1.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 1.31%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 6         | 1.12%   |
| Intel Wireless 3165                                                  | 6         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 6         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 5         | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 5         | 0.93%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 5         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 5         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 5         | 0.93%   |
| Intel Centrino Advanced-N 6235                                       | 5         | 0.93%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 0.93%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 5         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 4         | 0.75%   |
| Realtek 802.11n WLAN Adapter                                         | 4         | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 0.75%   |
| Intel Wireless 3160                                                  | 4         | 0.75%   |
| Intel WiFi Link 5100                                                 | 4         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 4         | 0.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 4         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 231       | 52.5%   |
| Intel                    | 105       | 23.86%  |
| Qualcomm Atheros         | 27        | 6.14%   |
| Broadcom                 | 24        | 5.45%   |
| Marvell Technology Group | 9         | 2.05%   |
| DisplayLink              | 7         | 1.59%   |
| Broadcom Limited         | 6         | 1.36%   |
| ASIX Electronics         | 6         | 1.36%   |
| Lenovo                   | 5         | 1.14%   |
| Xiaomi                   | 4         | 0.91%   |
| Samsung Electronics      | 4         | 0.91%   |
| JMicron Technology       | 4         | 0.91%   |
| Nvidia                   | 2         | 0.45%   |
| Hewlett-Packard          | 2         | 0.45%   |
| TP-Link                  | 1         | 0.23%   |
| Motorola PCS             | 1         | 0.23%   |
| Google                   | 1         | 0.23%   |
| Apple                    | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 156       | 34.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 37        | 8.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 31        | 6.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 4.19%   |
| Intel Ethernet Connection (4) I219-LM                                          | 12        | 2.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 9         | 1.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 7         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.1%    |
| Intel Ethernet Connection I219-V                                               | 5         | 1.1%    |
| Intel Ethernet Connection I219-LM                                              | 5         | 1.1%    |
| Intel Ethernet Connection I218-LM                                              | 5         | 1.1%    |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.1%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.88%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                                          | 4         | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 4         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 0.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 4         | 0.88%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 3         | 0.66%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.66%   |
| DisplayLink Dell Universal Dock D6000                                          | 3         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.44%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 508       | 54.51%  |
| Ethernet | 411       | 44.1%   |
| Modem    | 12        | 1.29%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 435       | 79.23%  |
| Ethernet | 114       | 20.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 372       | 71.54%  |
| 1     | 136       | 26.15%  |
| 0     | 10        | 1.92%   |
| 3     | 2         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 403       | 76.33%  |
| Yes  | 125       | 23.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 234       | 52.82%  |
| Realtek Semiconductor           | 39        | 8.8%    |
| Qualcomm Atheros Communications | 36        | 8.13%   |
| Apple                           | 25        | 5.64%   |
| Foxconn / Hon Hai               | 21        | 4.74%   |
| Broadcom                        | 21        | 4.74%   |
| IMC Networks                    | 19        | 4.29%   |
| Dell                            | 10        | 2.26%   |
| Lite-On Technology              | 9         | 2.03%   |
| Hewlett-Packard                 | 8         | 1.81%   |
| Realtek                         | 5         | 1.13%   |
| Ralink                          | 4         | 0.9%    |
| Cambridge Silicon Radio         | 3         | 0.68%   |
| Toshiba                         | 2         | 0.45%   |
| Foxconn International           | 2         | 0.45%   |
| Smart Modular Technologies      | 1         | 0.23%   |
| MediaTek                        | 1         | 0.23%   |
| Integrated System Solution      | 1         | 0.23%   |
| Belkin Components               | 1         | 0.23%   |
| ASUSTek Computer                | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 83        | 18.74%  |
| Intel AX200 Bluetooth                                                               | 43        | 9.71%   |
| Intel AX201 Bluetooth                                                               | 39        | 8.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 27        | 6.09%   |
| Realtek Bluetooth Radio                                                             | 22        | 4.97%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 22        | 4.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 16        | 3.61%   |
| Apple Bluetooth Host Controller                                                     | 15        | 3.39%   |
| Dell DW375 Bluetooth Module                                                         | 9         | 2.03%   |
| IMC Networks Wireless_Device                                                        | 8         | 1.81%   |
| Realtek RTL8723B Bluetooth                                                          | 7         | 1.58%   |
| Intel Bluetooth Device                                                              | 7         | 1.58%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 1.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 1.35%   |
| Intel AX210 Bluetooth                                                               | 6         | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.35%   |
| Realtek Bluetooth Radio                                                             | 5         | 1.13%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.13%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 1.13%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 0.9%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.9%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.9%    |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.68%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.45%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.45%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.45%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.45%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.45%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 435       | 66.72%  |
| AMD                      | 85        | 13.04%  |
| Nvidia                   | 79        | 12.12%  |
| Realtek Semiconductor    | 7         | 1.07%   |
| GN Netcom                | 5         | 0.77%   |
| Logitech                 | 4         | 0.61%   |
| Lenovo                   | 3         | 0.46%   |
| DSEA A/S                 | 3         | 0.46%   |
| Apple                    | 3         | 0.46%   |
| Texas Instruments        | 2         | 0.31%   |
| Samson Technologies      | 2         | 0.31%   |
| Plantronics              | 2         | 0.31%   |
| Kingston Technology      | 2         | 0.31%   |
| JMTek                    | 2         | 0.31%   |
| C-Media Electronics      | 2         | 0.31%   |
| Yamaha                   | 1         | 0.15%   |
| XMOS                     | 1         | 0.15%   |
| Sony                     | 1         | 0.15%   |
| Razer USA                | 1         | 0.15%   |
| Nordic Semiconductor ASA | 1         | 0.15%   |
| No brand                 | 1         | 0.15%   |
| LINE TECH INDUSTRIAL     | 1         | 0.15%   |
| Hewlett-Packard          | 1         | 0.15%   |
| GYROCOM C&C              | 1         | 0.15%   |
| Generalplus Technology   | 1         | 0.15%   |
| Creative Technology      | 1         | 0.15%   |
| Conexant Systems         | 1         | 0.15%   |
| CMX Systems              | 1         | 0.15%   |
| Cambridge Audio          | 1         | 0.15%   |
| Arturia                  | 1         | 0.15%   |
| AKAI Professional M.I.   | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 67        | 8.7%    |
| AMD Ryzen HD Audio Controller                                                                     | 52        | 6.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 36        | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 32        | 4.16%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 30        | 3.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 3.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 3.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 2.99%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 2.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 2.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 16        | 2.08%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 15        | 1.95%   |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 1.69%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 13        | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.04%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 7         | 0.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 0.91%   |
| Realtek Semiconductor USB Audio                                                                   | 6         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.52%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.52%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.52%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 4         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 120       | 33.99%  |
| SK hynix            | 80        | 22.66%  |
| Micron Technology   | 39        | 11.05%  |
| Kingston            | 28        | 7.93%   |
| Unknown             | 16        | 4.53%   |
| Ramaxel Technology  | 13        | 3.68%   |
| Crucial             | 13        | 3.68%   |
| Unknown (ABCD)      | 6         | 1.7%    |
| Corsair             | 5         | 1.42%   |
| A-DATA Technology   | 5         | 1.42%   |
| Elpida              | 4         | 1.13%   |
| Unknown             | 3         | 0.85%   |
| Teikon              | 2         | 0.57%   |
| Smart               | 2         | 0.57%   |
| Team                | 1         | 0.28%   |
| Smart Brazil        | 1         | 0.28%   |
| PNY                 | 1         | 0.28%   |
| Patriot             | 1         | 0.28%   |
| Nanya Technology    | 1         | 0.28%   |
| Magnum Tech         | 1         | 0.28%   |
| Lexar               | 1         | 0.28%   |
| Kingmax             | 1         | 0.28%   |
| Goldkey             | 1         | 0.28%   |
| G.Skill             | 1         | 0.28%   |
| ff                  | 1         | 0.28%   |
| fef5                | 1         | 0.28%   |
| Cors                | 1         | 0.28%   |
| ChangXin Memory     | 1         | 0.28%   |
| ASint Technology    | 1         | 0.28%   |
| 8945000080AD        | 1         | 0.28%   |
| 4ea5                | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 10        | 2.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.59%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 6         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 4         | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.06%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 1.06%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 4         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 4         | 1.06%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 4         | 1.06%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 4         | 1.06%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.06%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.06%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.8%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.8%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.8%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.8%    |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.8%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.8%    |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.8%    |
| Unknown                                                          | 3         | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.53%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 2         | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.53%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.53%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.53%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 162       | 53.82%  |
| DDR3    | 83        | 27.57%  |
| LPDDR4  | 20        | 6.64%   |
| LPDDR3  | 14        | 4.65%   |
| DDR2    | 6         | 1.99%   |
| SDRAM   | 4         | 1.33%   |
| LPDDR5  | 4         | 1.33%   |
| DDR5    | 4         | 1.33%   |
| Unknown | 3         | 1%      |
| DDR     | 1         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 259       | 86.33%  |
| Row Of Chips | 34        | 11.33%  |
| Unknown      | 4         | 1.33%   |
| Chip         | 2         | 0.67%   |
| DIMM         | 1         | 0.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 116       | 36.14%  |
| 4096  | 86        | 26.79%  |
| 16384 | 55        | 17.13%  |
| 32768 | 30        | 9.35%   |
| 2048  | 28        | 8.72%   |
| 1024  | 6         | 1.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 76        | 22.89%  |
| 3200    | 63        | 18.98%  |
| 1600    | 62        | 18.67%  |
| 2400    | 28        | 8.43%   |
| 2133    | 25        | 7.53%   |
| 1333    | 13        | 3.92%   |
| 1334    | 9         | 2.71%   |
| Unknown | 7         | 2.11%   |
| 3266    | 6         | 1.81%   |
| 8400    | 5         | 1.51%   |
| 4267    | 5         | 1.51%   |
| 1067    | 5         | 1.51%   |
| 4199    | 4         | 1.2%    |
| 1867    | 4         | 1.2%    |
| 6400    | 3         | 0.9%    |
| 4800    | 3         | 0.9%    |
| 4266    | 3         | 0.9%    |
| 3733    | 3         | 0.9%    |
| 667     | 3         | 0.9%    |
| 5600    | 1         | 0.3%    |
| 5500    | 1         | 0.3%    |
| 1066    | 1         | 0.3%    |
| 800     | 1         | 0.3%    |
| 533     | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 20%     |
| HP LaserJet 1320       | 1         | 20%     |
| HP DeskJet 2130 series | 1         | 20%     |
| Canon LiDE 400         | 1         | 20%     |
| Brother MFC-1810       | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 120       | 25.53%  |
| IMC Networks                           | 47        | 10%     |
| Sunplus Innovation Technology          | 38        | 8.09%   |
| Realtek Semiconductor                  | 38        | 8.09%   |
| Bison Electronics                      | 38        | 8.09%   |
| Microdia                               | 36        | 7.66%   |
| Quanta                                 | 20        | 4.26%   |
| Apple                                  | 19        | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 3.62%   |
| Syntek                                 | 14        | 2.98%   |
| Suyin                                  | 14        | 2.98%   |
| Luxvisions Innotech Limited            | 10        | 2.13%   |
| Silicon Motion                         | 8         | 1.7%    |
| Lite-On Technology                     | 6         | 1.28%   |
| Samsung Electronics                    | 5         | 1.06%   |
| Alcor Micro                            | 5         | 1.06%   |
| Ricoh                                  | 4         | 0.85%   |
| Logitech                               | 4         | 0.85%   |
| ShineTech                              | 3         | 0.64%   |
| Acer                                   | 3         | 0.64%   |
| Z-Star Microelectronics                | 2         | 0.43%   |
| Importek                               | 2         | 0.43%   |
| ALi                                    | 2         | 0.43%   |
| Unknown                                | 2         | 0.43%   |
| Y Media                                | 1         | 0.21%   |
| Unknown (3730304231393831325530)       | 1         | 0.21%   |
| Sonix Technology                       | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| Polycom                                | 1         | 0.21%   |
| Pixart Imaging                         | 1         | 0.21%   |
| Nokia Mobile Phones                    | 1         | 0.21%   |
| LG Electronics                         | 1         | 0.21%   |
| Lenovo                                 | 1         | 0.21%   |
| icSpring                               | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |
| Denron                                 | 1         | 0.21%   |
| Creative Technology                    | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 17        | 3.61%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 17        | 3.61%   |
| Chicony Integrated Camera                               | 16        | 3.4%    |
| Chicony HD Webcam                                       | 16        | 3.4%    |
| IMC Networks Integrated Camera                          | 14        | 2.97%   |
| Realtek Integrated_Webcam_HD                            | 12        | 2.55%   |
| Chicony Chicony USB2.0 Camera                           | 10        | 2.12%   |
| Chicony USB2.0 Camera                                   | 9         | 1.91%   |
| Chicony HP HD Camera                                    | 9         | 1.91%   |
| Apple FaceTime HD Camera                                | 9         | 1.91%   |
| Syntek Integrated Camera                                | 8         | 1.7%    |
| Sunplus Integrated_Webcam_HD                            | 7         | 1.49%   |
| Chicony Integrated IR Camera                            | 7         | 1.49%   |
| Bison Integrated Camera                                 | 7         | 1.49%   |
| Bison BisonCam,NB Pro                                   | 7         | 1.49%   |
| Bison HD Webcam                                         | 6         | 1.27%   |
| Sunplus HD WebCam                                       | 5         | 1.06%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 5         | 1.06%   |
| Realtek Integrated Webcam                               | 4         | 0.85%   |
| Luxvisions Innotech Limited Integrated Camera           | 4         | 0.85%   |
| IMC Networks VGA UVC WebCam                             | 4         | 0.85%   |
| Chicony HP Truevision HD                                | 4         | 0.85%   |
| Chicony EasyCamera                                      | 4         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 0.85%   |
| Bison SunplusIT Integrated Camera                       | 4         | 0.85%   |
| Bison EasyCamera                                        | 4         | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 4         | 0.85%   |
| Apple Built-in iSight                                   | 4         | 0.85%   |
| Suyin HP Truevision HD                                  | 3         | 0.64%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 3         | 0.64%   |
| Sunplus Integrated Camera                               | 3         | 0.64%   |
| Sunplus Asus Webcam                                     | 3         | 0.64%   |
| Realtek USB2.0 HD UVC WebCam                            | 3         | 0.64%   |
| Realtek Lenovo EasyCamera                               | 3         | 0.64%   |
| Realtek HD WebCam                                       | 3         | 0.64%   |
| Quanta USB2.0 HD UVC WebCam                             | 3         | 0.64%   |
| Quanta HD User Facing                                   | 3         | 0.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 0.64%   |
| Chicony USB2.0 VGA UVC WebCam                           | 3         | 0.64%   |
| Chicony USB2.0 0.3M UVC WebCam                          | 3         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 37        | 33.94%  |
| Synaptics                  | 37        | 33.94%  |
| Shenzhen Goodix Technology | 16        | 14.68%  |
| LighTuning Technology      | 10        | 9.17%   |
| Elan Microelectronics      | 5         | 4.59%   |
| AuthenTec                  | 4         | 3.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 11.01%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 10.09%  |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 10.09%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 5.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.67%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 3.67%   |
| Synaptics WBDI Device                                                      | 4         | 3.67%   |
| Synaptics TouchPad                                                         | 4         | 3.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 3.67%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.67%   |
| Unknown                                                                    | 4         | 3.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.75%   |
| LighTuning Fingerprint Reader                                              | 3         | 2.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.83%   |
| Validity Sensors VFS491                                                    | 2         | 1.83%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.83%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.83%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.83%   |
| AuthenTec AES1600                                                          | 2         | 1.83%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.92%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.92%   |
| Synaptics  WBDI                                                            | 1         | 0.92%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.92%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.92%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.92%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.92%   |
| AuthenTec AES2810                                                          | 1         | 0.92%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 23        | 56.1%   |
| Alcor Micro           | 10        | 24.39%  |
| Upek                  | 5         | 12.2%   |
| Lenovo                | 2         | 4.88%   |
| Gemalto (was Gemplus) | 1         | 2.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 24.39%  |
| Broadcom 5880                                                                | 9         | 21.95%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 19.51%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 12.2%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 7.32%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.44%   |
| Broadcom 58200                                                               | 1         | 2.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 289       | 54.73%  |
| 1     | 191       | 36.17%  |
| 2     | 39        | 7.39%   |
| 3     | 5         | 0.95%   |
| 7     | 2         | 0.38%   |
| 5     | 1         | 0.19%   |
| 4     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 108       | 37.5%   |
| Graphics card            | 46        | 15.97%  |
| Chipcard                 | 38        | 13.19%  |
| Net/wireless             | 24        | 8.33%   |
| Communication controller | 19        | 6.6%    |
| Multimedia controller    | 13        | 4.51%   |
| Camera                   | 11        | 3.82%   |
| Bluetooth                | 7         | 2.43%   |
| Storage                  | 6         | 2.08%   |
| Sound                    | 6         | 2.08%   |
| Card reader              | 6         | 2.08%   |
| Net/ethernet             | 4         | 1.39%   |

