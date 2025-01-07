Linux in Sweden - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

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

Total: 2235

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [f10a0edbdf](https://linux-hardware.org/?probe=f10a0edbdf) | Jan 06, 2025 |
| Apple         | MacBook3,1                  | [be78213991](https://linux-hardware.org/?probe=be78213991) | Jan 05, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [891b36fe2c](https://linux-hardware.org/?probe=891b36fe2c) | Jan 04, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [7b5bde2cbf](https://linux-hardware.org/?probe=7b5bde2cbf) | Jan 04, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [437234b838](https://linux-hardware.org/?probe=437234b838) | Jan 04, 2025 |
| Maibenben     | MaiBook M Series            | [0d480fbbc9](https://linux-hardware.org/?probe=0d480fbbc9) | Jan 04, 2025 |
| Acer          | Nitro AN16-41               | [dedf248848](https://linux-hardware.org/?probe=dedf248848) | Jan 03, 2025 |
| HP            | Laptop 15s-eq2xxx           | [37b47880bb](https://linux-hardware.org/?probe=37b47880bb) | Jan 02, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3df95b02eb](https://linux-hardware.org/?probe=3df95b02eb) | Jan 02, 2025 |
| HP            | ZBook 15u G3                | [da5c26013c](https://linux-hardware.org/?probe=da5c26013c) | Jan 02, 2025 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [97c438ca9c](https://linux-hardware.org/?probe=97c438ca9c) | Jan 01, 2025 |
| Lenovo        | G50-30 80G0                 | [f9d8f3d7a1](https://linux-hardware.org/?probe=f9d8f3d7a1) | Jan 01, 2025 |
| Packard Be... | EasyNote MH36               | [f8b0243bfd](https://linux-hardware.org/?probe=f8b0243bfd) | Jan 01, 2025 |
| Acer          | Predator PH315-53           | [17816e7d6b](https://linux-hardware.org/?probe=17816e7d6b) | Jan 01, 2025 |
| Acer          | Aspire AG14-31P             | [7c9a6f02f0](https://linux-hardware.org/?probe=7c9a6f02f0) | Dec 29, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [4d428ff2fd](https://linux-hardware.org/?probe=4d428ff2fd) | Dec 28, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [e443699b8d](https://linux-hardware.org/?probe=e443699b8d) | Dec 28, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [fd2a217520](https://linux-hardware.org/?probe=fd2a217520) | Dec 28, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [0ac54971da](https://linux-hardware.org/?probe=0ac54971da) | Dec 28, 2024 |
| Acer          | Nitro AN16-41               | [8521ef1a55](https://linux-hardware.org/?probe=8521ef1a55) | Dec 27, 2024 |
| Acer          | Aspire ES1-311              | [d4cf291b46](https://linux-hardware.org/?probe=d4cf291b46) | Dec 26, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B3404CVA... | [8bc927ee5a](https://linux-hardware.org/?probe=8bc927ee5a) | Dec 26, 2024 |
| ASUSTek       | G75VW                       | [6f5eceb221](https://linux-hardware.org/?probe=6f5eceb221) | Dec 26, 2024 |
| HP            | ZBook 15u G5                | [639f1b214f](https://linux-hardware.org/?probe=639f1b214f) | Dec 24, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [0a16cb4410](https://linux-hardware.org/?probe=0a16cb4410) | Dec 22, 2024 |
| HP            | ZBook 15 G2                 | [64c7294576](https://linux-hardware.org/?probe=64c7294576) | Dec 22, 2024 |
| HP            | Notebook                    | [0382c42708](https://linux-hardware.org/?probe=0382c42708) | Dec 21, 2024 |
| Lenovo        | ThinkPad T410 2518R8G       | [03e23c615f](https://linux-hardware.org/?probe=03e23c615f) | Dec 21, 2024 |
| HP            | Laptop 15s-eq2xxx           | [ff85345164](https://linux-hardware.org/?probe=ff85345164) | Dec 21, 2024 |
| ASUSTek       | N61Vn                       | [47db61a704](https://linux-hardware.org/?probe=47db61a704) | Dec 20, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [224bf763b0](https://linux-hardware.org/?probe=224bf763b0) | Dec 19, 2024 |
| Sony          | VGN-FZ31M                   | [11db51fc55](https://linux-hardware.org/?probe=11db51fc55) | Dec 17, 2024 |
| HP            | Notebook                    | [cd9bb8bac9](https://linux-hardware.org/?probe=cd9bb8bac9) | Dec 17, 2024 |
| Packard Be... | EasyNote MH36               | [504944e21f](https://linux-hardware.org/?probe=504944e21f) | Dec 15, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [e73050a450](https://linux-hardware.org/?probe=e73050a450) | Dec 15, 2024 |
| Lenovo        | G50-30 80G0                 | [5720b04708](https://linux-hardware.org/?probe=5720b04708) | Dec 13, 2024 |
| HP            | ProBook 445 14 inch G9 N... | [2b25226ef6](https://linux-hardware.org/?probe=2b25226ef6) | Dec 13, 2024 |
| Lenovo        | G50-30 80G0                 | [7c957f114c](https://linux-hardware.org/?probe=7c957f114c) | Dec 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [66470f4176](https://linux-hardware.org/?probe=66470f4176) | Dec 12, 2024 |
| HP            | EliteBook 8740w             | [70d44e5e32](https://linux-hardware.org/?probe=70d44e5e32) | Dec 10, 2024 |
| HP            | EliteBook 8740w             | [88b25b7b18](https://linux-hardware.org/?probe=88b25b7b18) | Dec 10, 2024 |
| HP            | ZBook 15v G5                | [9db28aa3ea](https://linux-hardware.org/?probe=9db28aa3ea) | Dec 09, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | [132e6e2862](https://linux-hardware.org/?probe=132e6e2862) | Dec 09, 2024 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | [ecbb2dfb26](https://linux-hardware.org/?probe=ecbb2dfb26) | Dec 07, 2024 |
| Notebook      | NS5x_NS7xAU                 | [dd558adef8](https://linux-hardware.org/?probe=dd558adef8) | Dec 07, 2024 |
| Acer          | Aspire ES1-311              | [e5308635b1](https://linux-hardware.org/?probe=e5308635b1) | Dec 06, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3497127dba](https://linux-hardware.org/?probe=3497127dba) | Dec 05, 2024 |
| Lenovo        | ThinkPad Edge E540 20C60... | [8270c3a002](https://linux-hardware.org/?probe=8270c3a002) | Dec 05, 2024 |
| MSI           | GE60 2PE                    | [bab5d77c34](https://linux-hardware.org/?probe=bab5d77c34) | Dec 04, 2024 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [6d37f99660](https://linux-hardware.org/?probe=6d37f99660) | Dec 04, 2024 |
| HP            | ZBook 15v G5                | [0d4d759913](https://linux-hardware.org/?probe=0d4d759913) | Dec 03, 2024 |
| HP            | ZBook 15u G3                | [c4aba38081](https://linux-hardware.org/?probe=c4aba38081) | Dec 01, 2024 |
| HP            | Laptop 17-cp0xxx            | [f9f30dfbbc](https://linux-hardware.org/?probe=f9f30dfbbc) | Nov 29, 2024 |
| ASUSTek       | G75VW                       | [4dd4121257](https://linux-hardware.org/?probe=4dd4121257) | Nov 28, 2024 |
| Dell          | XPS 9320                    | [eade833b62](https://linux-hardware.org/?probe=eade833b62) | Nov 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [bbcfd5f2d1](https://linux-hardware.org/?probe=bbcfd5f2d1) | Nov 26, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [a6e55209bb](https://linux-hardware.org/?probe=a6e55209bb) | Nov 26, 2024 |
| Valve         | Jupiter                     | [99d0e12698](https://linux-hardware.org/?probe=99d0e12698) | Nov 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0ff652bb11](https://linux-hardware.org/?probe=0ff652bb11) | Nov 23, 2024 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | [c2678e2d05](https://linux-hardware.org/?probe=c2678e2d05) | Nov 23, 2024 |
| HONOR         | MRA-XXX                     | [eeaf09c1eb](https://linux-hardware.org/?probe=eeaf09c1eb) | Nov 22, 2024 |
| HONOR         | MRA-XXX                     | [605e47c8d8](https://linux-hardware.org/?probe=605e47c8d8) | Nov 22, 2024 |
| Acer          | Aspire 5740                 | [53795ba4cd](https://linux-hardware.org/?probe=53795ba4cd) | Nov 22, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [40b777045b](https://linux-hardware.org/?probe=40b777045b) | Nov 21, 2024 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [70dcc9416f](https://linux-hardware.org/?probe=70dcc9416f) | Nov 19, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [91797321da](https://linux-hardware.org/?probe=91797321da) | Nov 18, 2024 |
| Acer          | Aspire V5-552               | [a8ad78f7fb](https://linux-hardware.org/?probe=a8ad78f7fb) | Nov 13, 2024 |
| HP            | ZBook Firefly 15 inch G8... | [b1f86eb24f](https://linux-hardware.org/?probe=b1f86eb24f) | Nov 13, 2024 |
| HP            | ZBook Firefly 15 inch G8... | [4bbedaf665](https://linux-hardware.org/?probe=4bbedaf665) | Nov 13, 2024 |
| Acer          | Aspire ES1-311              | [eec78bb1ce](https://linux-hardware.org/?probe=eec78bb1ce) | Nov 13, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | [a74cceeb11](https://linux-hardware.org/?probe=a74cceeb11) | Nov 12, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [7ed663f998](https://linux-hardware.org/?probe=7ed663f998) | Nov 10, 2024 |
| HP            | Pavilion Notebook           | [f28a41ee26](https://linux-hardware.org/?probe=f28a41ee26) | Nov 09, 2024 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | [4f605f33f1](https://linux-hardware.org/?probe=4f605f33f1) | Nov 07, 2024 |
| Lenovo        | ThinkPad T480s 20L8S3YG2... | [1fc7c10c39](https://linux-hardware.org/?probe=1fc7c10c39) | Nov 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8S3YG2... | [bb9e9ced42](https://linux-hardware.org/?probe=bb9e9ced42) | Nov 06, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [689c7827b7](https://linux-hardware.org/?probe=689c7827b7) | Nov 06, 2024 |
| Packard Be... | EasyNote TE69KB             | [a9167be106](https://linux-hardware.org/?probe=a9167be106) | Nov 04, 2024 |
| Dell          | Vostro 3400                 | [40faeffee1](https://linux-hardware.org/?probe=40faeffee1) | Nov 01, 2024 |
| HP            | Laptop 14-em0xxx            | [21d6b4b16b](https://linux-hardware.org/?probe=21d6b4b16b) | Oct 31, 2024 |
| HUAWEI        | MACH-WX9                    | [2bbf4ba8da](https://linux-hardware.org/?probe=2bbf4ba8da) | Oct 31, 2024 |
| ASUSTek       | X555LN                      | [f2a9ec42b4](https://linux-hardware.org/?probe=f2a9ec42b4) | Oct 30, 2024 |
| Valve         | Jupiter                     | [9da334fd4b](https://linux-hardware.org/?probe=9da334fd4b) | Oct 27, 2024 |
| Dell          | XPS 13 9310                 | [581cea7035](https://linux-hardware.org/?probe=581cea7035) | Oct 26, 2024 |
| ASUSTek       | G75VW                       | [16c95d4388](https://linux-hardware.org/?probe=16c95d4388) | Oct 22, 2024 |
| Lenovo        | ThinkPad T490 20N2005TMX    | [ae1d5a2073](https://linux-hardware.org/?probe=ae1d5a2073) | Oct 21, 2024 |
| ASUSTek       | K73BY                       | [183ebc94a6](https://linux-hardware.org/?probe=183ebc94a6) | Oct 20, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [fee3d99904](https://linux-hardware.org/?probe=fee3d99904) | Oct 19, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [bf4364a524](https://linux-hardware.org/?probe=bf4364a524) | Oct 18, 2024 |
| ASUSTek       | Adol_ADOLBOOK I1403ZA_AD... | [def48960d1](https://linux-hardware.org/?probe=def48960d1) | Oct 18, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | [d4a940d38f](https://linux-hardware.org/?probe=d4a940d38f) | Oct 18, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [c0db693df2](https://linux-hardware.org/?probe=c0db693df2) | Oct 17, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | [e43e055615](https://linux-hardware.org/?probe=e43e055615) | Oct 17, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9b96b8b957](https://linux-hardware.org/?probe=9b96b8b957) | Oct 17, 2024 |
| Apple         | MacBookPro11,1              | [0b14e22f7e](https://linux-hardware.org/?probe=0b14e22f7e) | Oct 16, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [721f67c310](https://linux-hardware.org/?probe=721f67c310) | Oct 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [ae22524e06](https://linux-hardware.org/?probe=ae22524e06) | Oct 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [e86ff90245](https://linux-hardware.org/?probe=e86ff90245) | Oct 15, 2024 |
| Dell          | Latitude E7250              | [ce90b269d6](https://linux-hardware.org/?probe=ce90b269d6) | Oct 14, 2024 |
| HP            | EliteBook 830 G5            | [bab49b9805](https://linux-hardware.org/?probe=bab49b9805) | Oct 14, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a9c9a656c3](https://linux-hardware.org/?probe=a9c9a656c3) | Oct 14, 2024 |
| HP            | EliteBook 830 G7 Noteboo... | [2f02059daf](https://linux-hardware.org/?probe=2f02059daf) | Oct 13, 2024 |
| Acer          | Aspire ES1-311              | [ad611bc852](https://linux-hardware.org/?probe=ad611bc852) | Oct 12, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5ff6f3f1a8](https://linux-hardware.org/?probe=5ff6f3f1a8) | Oct 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [8e06db2e61](https://linux-hardware.org/?probe=8e06db2e61) | Oct 11, 2024 |
| HP            | EliteBook 8740w             | [4721f064f7](https://linux-hardware.org/?probe=4721f064f7) | Oct 10, 2024 |
| HP            | EliteBook 830 G5            | [64cebe30ad](https://linux-hardware.org/?probe=64cebe30ad) | Oct 10, 2024 |
| Lenovo        | ThinkPad T480s 20L7S0BM0... | [64ef0dbb14](https://linux-hardware.org/?probe=64ef0dbb14) | Oct 09, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED1H    | [4994171903](https://linux-hardware.org/?probe=4994171903) | Oct 09, 2024 |
| Apple         | MacBookAir6,2               | [280f27da52](https://linux-hardware.org/?probe=280f27da52) | Oct 08, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [58dc343bfd](https://linux-hardware.org/?probe=58dc343bfd) | Oct 08, 2024 |
| Acer          | Predator PT516-51s          | [86cb6e091c](https://linux-hardware.org/?probe=86cb6e091c) | Oct 08, 2024 |
| Dell          | XPS 15 9500                 | [855ca0cb21](https://linux-hardware.org/?probe=855ca0cb21) | Oct 08, 2024 |
| Acer          | Extensa 5620                | [82f3c9f52b](https://linux-hardware.org/?probe=82f3c9f52b) | Oct 08, 2024 |
| MSI           | Cyborg 15 A12VE             | [9130fd797f](https://linux-hardware.org/?probe=9130fd797f) | Oct 07, 2024 |
| HP            | EliteBook 830 G5            | [c8c6a6269b](https://linux-hardware.org/?probe=c8c6a6269b) | Oct 06, 2024 |
| Apple         | MacBookAir4,2               | [7b9cf12f0d](https://linux-hardware.org/?probe=7b9cf12f0d) | Oct 05, 2024 |
| Acer          | Aspire A515-56              | [bac3fde948](https://linux-hardware.org/?probe=bac3fde948) | Oct 05, 2024 |
| ASUSTek       | G75VW                       | [6be09afc6e](https://linux-hardware.org/?probe=6be09afc6e) | Oct 05, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | [306ac3f0e3](https://linux-hardware.org/?probe=306ac3f0e3) | Oct 03, 2024 |
| Valve         | Jupiter                     | [27563b6975](https://linux-hardware.org/?probe=27563b6975) | Oct 01, 2024 |
| Acer          | Aspire ES1-311              | [ef3968a3cc](https://linux-hardware.org/?probe=ef3968a3cc) | Sep 30, 2024 |
| Acer          | Aspire ES1-311              | [e4398bf85e](https://linux-hardware.org/?probe=e4398bf85e) | Sep 30, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [6696fe76a8](https://linux-hardware.org/?probe=6696fe76a8) | Sep 29, 2024 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f4697c886f](https://linux-hardware.org/?probe=f4697c886f) | Sep 28, 2024 |
| ASUSTek       | G75VW                       | [6629e094c4](https://linux-hardware.org/?probe=6629e094c4) | Sep 28, 2024 |
| Acer          | Swift SFG14-72              | [e00b023510](https://linux-hardware.org/?probe=e00b023510) | Sep 26, 2024 |
| Acer          | Swift SFG14-72              | [a3c8cdd8b8](https://linux-hardware.org/?probe=a3c8cdd8b8) | Sep 26, 2024 |
| Apple         | MacBookAir7,2               | [8173fdd55a](https://linux-hardware.org/?probe=8173fdd55a) | Sep 23, 2024 |
| Lenovo        | LOQ 15IRX9 83DV             | [0fc0afe81f](https://linux-hardware.org/?probe=0fc0afe81f) | Sep 23, 2024 |
| Samsung       | 700Z7C                      | [8107298d16](https://linux-hardware.org/?probe=8107298d16) | Sep 23, 2024 |
| Samsung       | 700Z7C                      | [bfbda5980e](https://linux-hardware.org/?probe=bfbda5980e) | Sep 20, 2024 |
| Insyde        | I86                         | [e9c8a3bdcc](https://linux-hardware.org/?probe=e9c8a3bdcc) | Sep 17, 2024 |
| Insyde        | I86                         | [ad18628c42](https://linux-hardware.org/?probe=ad18628c42) | Sep 16, 2024 |
| Apple         | MacBookPro11,1              | [b57903987f](https://linux-hardware.org/?probe=b57903987f) | Sep 16, 2024 |
| HP            | Pavilion Aero Laptop        | [378a1e1ce9](https://linux-hardware.org/?probe=378a1e1ce9) | Sep 14, 2024 |
| SLIMBOOK      | EXCALIBUR-16-AMD7           | [1ba71f53bd](https://linux-hardware.org/?probe=1ba71f53bd) | Sep 12, 2024 |
| Dell          | Latitude 5310               | [96dff33ea9](https://linux-hardware.org/?probe=96dff33ea9) | Sep 12, 2024 |
| Acer          | Aspire A315-58              | [8992e454d0](https://linux-hardware.org/?probe=8992e454d0) | Sep 11, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [5996ac2bac](https://linux-hardware.org/?probe=5996ac2bac) | Sep 11, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [6095a51efd](https://linux-hardware.org/?probe=6095a51efd) | Sep 11, 2024 |
| Lenovo        | ThinkPad Z13 Gen 2 21JV0... | [a1bce3188b](https://linux-hardware.org/?probe=a1bce3188b) | Sep 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7244b83192](https://linux-hardware.org/?probe=7244b83192) | Sep 11, 2024 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [19682cb902](https://linux-hardware.org/?probe=19682cb902) | Sep 10, 2024 |
| HP            | ProBook 640 G1              | [f07399d748](https://linux-hardware.org/?probe=f07399d748) | Sep 09, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [34e49e5b88](https://linux-hardware.org/?probe=34e49e5b88) | Sep 09, 2024 |
| Acer          | Predator PT516-51s          | [5e00825e4e](https://linux-hardware.org/?probe=5e00825e4e) | Sep 08, 2024 |
| Dell          | Latitude 5310               | [bc6b54c956](https://linux-hardware.org/?probe=bc6b54c956) | Sep 07, 2024 |
| ASUSTek       | VivoBook E14 E402YA_F402... | [f5b06832d9](https://linux-hardware.org/?probe=f5b06832d9) | Sep 06, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [ffa315e87c](https://linux-hardware.org/?probe=ffa315e87c) | Sep 05, 2024 |
| Dell          | Latitude 5431               | [f3fcf01119](https://linux-hardware.org/?probe=f3fcf01119) | Sep 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [be36fd0490](https://linux-hardware.org/?probe=be36fd0490) | Sep 04, 2024 |
| Lenovo        | IdeaPad S510p 20298         | [58d94e136f](https://linux-hardware.org/?probe=58d94e136f) | Sep 04, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [2bf6c6f2fc](https://linux-hardware.org/?probe=2bf6c6f2fc) | Sep 03, 2024 |
| Dell          | Precision 7540              | [c2661e531c](https://linux-hardware.org/?probe=c2661e531c) | Sep 01, 2024 |
| Samsung       | 700Z7C                      | [2af9db39e9](https://linux-hardware.org/?probe=2af9db39e9) | Sep 01, 2024 |
| Lenovo        | Yoga Slim 9 14IAP7 82T0     | [da5afe15a6](https://linux-hardware.org/?probe=da5afe15a6) | Aug 31, 2024 |
| HP            | EliteBook 840 G3            | [cd36835fcb](https://linux-hardware.org/?probe=cd36835fcb) | Aug 29, 2024 |
| Dell          | Latitude 5310               | [77dd128cef](https://linux-hardware.org/?probe=77dd128cef) | Aug 28, 2024 |
| Acer          | Aspire A315-58              | [da5322547c](https://linux-hardware.org/?probe=da5322547c) | Aug 28, 2024 |
| Lenovo        | ThinkPad X260 20F5S0NV00    | [471dab4a49](https://linux-hardware.org/?probe=471dab4a49) | Aug 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [42e8bb1d69](https://linux-hardware.org/?probe=42e8bb1d69) | Aug 26, 2024 |
| HP            | ZBook Power 16 inch G11 ... | [570df618ae](https://linux-hardware.org/?probe=570df618ae) | Aug 26, 2024 |
| HP            | Laptop 15s-eq2xxx           | [0d00087eaf](https://linux-hardware.org/?probe=0d00087eaf) | Aug 25, 2024 |
| Lenovo        | ThinkPad X260 20F5S3Y901    | [95bbbfc253](https://linux-hardware.org/?probe=95bbbfc253) | Aug 24, 2024 |
| Toshiba       | Satellite C660D             | [fb51658e06](https://linux-hardware.org/?probe=fb51658e06) | Aug 23, 2024 |
| Dell          | Precision 7760              | [d4eac98edf](https://linux-hardware.org/?probe=d4eac98edf) | Aug 23, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [3938561e8d](https://linux-hardware.org/?probe=3938561e8d) | Aug 22, 2024 |
| Lenovo        | IdeaPad S210 Touch 20257    | [74e33c3513](https://linux-hardware.org/?probe=74e33c3513) | Aug 22, 2024 |
| Lenovo        | IdeaPad S210 Touch 20257    | [6c78e1b0ae](https://linux-hardware.org/?probe=6c78e1b0ae) | Aug 21, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [5d03c0ea61](https://linux-hardware.org/?probe=5d03c0ea61) | Aug 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2fd0923759](https://linux-hardware.org/?probe=2fd0923759) | Aug 18, 2024 |
| HP            | Pavilion g6                 | [e3bdaf36c1](https://linux-hardware.org/?probe=e3bdaf36c1) | Aug 17, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [a8047d0691](https://linux-hardware.org/?probe=a8047d0691) | Aug 16, 2024 |
| Lenovo        | ThinkPad T460 20FMS1CJ02    | [6fd4716585](https://linux-hardware.org/?probe=6fd4716585) | Aug 16, 2024 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | [0a192bfe6e](https://linux-hardware.org/?probe=0a192bfe6e) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7e1480b2f1](https://linux-hardware.org/?probe=7e1480b2f1) | Aug 15, 2024 |
| ASUSTek       | K73BY                       | [887351841f](https://linux-hardware.org/?probe=887351841f) | Aug 13, 2024 |
| HP            | 255 G6 Notebook PC          | [4c21812738](https://linux-hardware.org/?probe=4c21812738) | Aug 13, 2024 |
| Lenovo        | IdeaPad S340-15API 81NC     | [f11f0f999f](https://linux-hardware.org/?probe=f11f0f999f) | Aug 10, 2024 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [9ce87357ac](https://linux-hardware.org/?probe=9ce87357ac) | Aug 10, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cb3afecba9](https://linux-hardware.org/?probe=cb3afecba9) | Aug 10, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [c222ed88f2](https://linux-hardware.org/?probe=c222ed88f2) | Aug 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c1512a68e2](https://linux-hardware.org/?probe=c1512a68e2) | Aug 08, 2024 |
| Apple         | MacBookAir4,2               | [463b931271](https://linux-hardware.org/?probe=463b931271) | Aug 08, 2024 |
| Lenovo        | ThinkPad X230 2325L19       | [c3a54deca3](https://linux-hardware.org/?probe=c3a54deca3) | Aug 07, 2024 |
| ASUSTek       | G75VW                       | [b69646717f](https://linux-hardware.org/?probe=b69646717f) | Aug 07, 2024 |
| HP            | ProBook 640 G1              | [bb4912b46b](https://linux-hardware.org/?probe=bb4912b46b) | Aug 07, 2024 |
| Lenovo        | ThinkPad T460 20FMS1CJ02    | [26759106a5](https://linux-hardware.org/?probe=26759106a5) | Aug 06, 2024 |
| Lenovo        | ThinkPad T460 20FMS1CJ02    | [b36d4e7b4f](https://linux-hardware.org/?probe=b36d4e7b4f) | Aug 06, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [d5c3de32a3](https://linux-hardware.org/?probe=d5c3de32a3) | Aug 06, 2024 |
| HP            | ProBook 640 G1              | [dd3248cc1d](https://linux-hardware.org/?probe=dd3248cc1d) | Aug 06, 2024 |
| Acer          | Aspire ES1-311              | [1130f68b30](https://linux-hardware.org/?probe=1130f68b30) | Aug 04, 2024 |
| Apple         | MacBookPro10,1              | [e9d84d00b2](https://linux-hardware.org/?probe=e9d84d00b2) | Aug 02, 2024 |
| Acer          | Aspire ES1-311              | [3cd7fba406](https://linux-hardware.org/?probe=3cd7fba406) | Aug 02, 2024 |
| Dell          | Latitude D620               | [3e87cb22fe](https://linux-hardware.org/?probe=3e87cb22fe) | Aug 01, 2024 |
| Dell          | Latitude D620               | [33b3f24a56](https://linux-hardware.org/?probe=33b3f24a56) | Aug 01, 2024 |
| ASUSTek       | ZenBook UX431DA_UX431DA     | [118fd7e8da](https://linux-hardware.org/?probe=118fd7e8da) | Jul 31, 2024 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [2432557e37](https://linux-hardware.org/?probe=2432557e37) | Jul 30, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [2e31f232bd](https://linux-hardware.org/?probe=2e31f232bd) | Jul 29, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1972507830](https://linux-hardware.org/?probe=1972507830) | Jul 28, 2024 |
| ASUSTek       | G75VW                       | [34e2d2c812](https://linux-hardware.org/?probe=34e2d2c812) | Jul 27, 2024 |
| Apple         | MacBookAir4,2               | [9d37505b50](https://linux-hardware.org/?probe=9d37505b50) | Jul 26, 2024 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [fe899545c2](https://linux-hardware.org/?probe=fe899545c2) | Jul 24, 2024 |
| HP            | 250 G5 Notebook PC          | [7124648707](https://linux-hardware.org/?probe=7124648707) | Jul 23, 2024 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [ae0429a983](https://linux-hardware.org/?probe=ae0429a983) | Jul 22, 2024 |
| MSI           | Unknown                     | [4b4e40df91](https://linux-hardware.org/?probe=4b4e40df91) | Jul 22, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [149e07d159](https://linux-hardware.org/?probe=149e07d159) | Jul 21, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | [de956ddbce](https://linux-hardware.org/?probe=de956ddbce) | Jul 21, 2024 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [34f9adbd72](https://linux-hardware.org/?probe=34f9adbd72) | Jul 18, 2024 |
| HP            | Laptop 15s-fq0xxx           | [8d36ed03a5](https://linux-hardware.org/?probe=8d36ed03a5) | Jul 18, 2024 |
| HP            | Laptop 15s-eq2xxx           | [c815b96dc2](https://linux-hardware.org/?probe=c815b96dc2) | Jul 18, 2024 |
| Valve         | Jupiter                     | [7cc0040262](https://linux-hardware.org/?probe=7cc0040262) | Jul 18, 2024 |
| HP            | Compaq CQ58                 | [ae1095b995](https://linux-hardware.org/?probe=ae1095b995) | Jul 18, 2024 |
| Lenovo        | ThinkPad X280 20KF001JMX    | [e84abf379c](https://linux-hardware.org/?probe=e84abf379c) | Jul 18, 2024 |
| HP            | EliteBook 1040 14 inch G... | [87a8b1e557](https://linux-hardware.org/?probe=87a8b1e557) | Jul 17, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [0f214ed3c8](https://linux-hardware.org/?probe=0f214ed3c8) | Jul 16, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [d512ac275e](https://linux-hardware.org/?probe=d512ac275e) | Jul 14, 2024 |
| PINE64        | Pinebook Pro                | [6b187afafa](https://linux-hardware.org/?probe=6b187afafa) | Jul 14, 2024 |
| HP            | Pavilion dv7                | [54f99671a4](https://linux-hardware.org/?probe=54f99671a4) | Jul 12, 2024 |
| Acer          | Aspire One 721              | [1561681cfd](https://linux-hardware.org/?probe=1561681cfd) | Jul 12, 2024 |
| HP            | EliteBook 840 G2            | [b356fb5f84](https://linux-hardware.org/?probe=b356fb5f84) | Jul 12, 2024 |
| Dell          | Precision 5480              | [137f1e1804](https://linux-hardware.org/?probe=137f1e1804) | Jul 10, 2024 |
| HP            | Compaq CQ58                 | [06e8fd63ee](https://linux-hardware.org/?probe=06e8fd63ee) | Jul 06, 2024 |
| Notebook      | PB50_70EF,ED,EC             | [9d7e31a9f6](https://linux-hardware.org/?probe=9d7e31a9f6) | Jul 06, 2024 |
| ASUSTek       | G75VW                       | [bca863a045](https://linux-hardware.org/?probe=bca863a045) | Jul 05, 2024 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [f3f50ce879](https://linux-hardware.org/?probe=f3f50ce879) | Jul 05, 2024 |
| Sony          | VGN-FW21L                   | [0e8d7d8b94](https://linux-hardware.org/?probe=0e8d7d8b94) | Jul 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [7433897585](https://linux-hardware.org/?probe=7433897585) | Jul 04, 2024 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [e474ecc123](https://linux-hardware.org/?probe=e474ecc123) | Jul 03, 2024 |
| Acer          | Aspire A514-55              | [0427aadc8e](https://linux-hardware.org/?probe=0427aadc8e) | Jul 02, 2024 |
| Dell          | Precision 5480              | [550a668587](https://linux-hardware.org/?probe=550a668587) | Jul 02, 2024 |
| ASUSTek       | X540YA                      | [d9a366d91f](https://linux-hardware.org/?probe=d9a366d91f) | Jul 01, 2024 |
| Acer          | Aspire A514-55              | [4a5f7c1085](https://linux-hardware.org/?probe=4a5f7c1085) | Jul 01, 2024 |
| HP            | ProBook 430 G1              | [979d9c3cba](https://linux-hardware.org/?probe=979d9c3cba) | Jun 30, 2024 |
| Valve         | Jupiter                     | [162c4ed949](https://linux-hardware.org/?probe=162c4ed949) | Jun 29, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [61769941cf](https://linux-hardware.org/?probe=61769941cf) | Jun 28, 2024 |
| Valve         | Jupiter                     | [f8b7ac5efe](https://linux-hardware.org/?probe=f8b7ac5efe) | Jun 28, 2024 |
| Lenovo        | IdeaPad Y510P 20217         | [236d773cf5](https://linux-hardware.org/?probe=236d773cf5) | Jun 26, 2024 |
| Dell          | XPS 13 9310                 | [653089da88](https://linux-hardware.org/?probe=653089da88) | Jun 26, 2024 |
| HP            | ProBook 440 G7              | [7dab9ce9ad](https://linux-hardware.org/?probe=7dab9ce9ad) | Jun 22, 2024 |
| Acer          | Aspire ES1-311              | [2eca3a5800](https://linux-hardware.org/?probe=2eca3a5800) | Jun 21, 2024 |
| HP            | EliteBook 8740w             | [6bcb30794d](https://linux-hardware.org/?probe=6bcb30794d) | Jun 20, 2024 |
| Dell          | XPS 13 9370                 | [4fbc36019a](https://linux-hardware.org/?probe=4fbc36019a) | Jun 20, 2024 |
| HP            | OMEN by Laptop              | [d9937127b8](https://linux-hardware.org/?probe=d9937127b8) | Jun 19, 2024 |
| Acer          | Aspire A315-42              | [7582481d6b](https://linux-hardware.org/?probe=7582481d6b) | Jun 19, 2024 |
| HP            | ProBook 440 G7              | [69cba96a78](https://linux-hardware.org/?probe=69cba96a78) | Jun 19, 2024 |
| ASUSTek       | S551LB                      | [a41a1c5447](https://linux-hardware.org/?probe=a41a1c5447) | Jun 18, 2024 |
| HP            | Laptop 15s-fq0xxx           | [d406bb46f8](https://linux-hardware.org/?probe=d406bb46f8) | Jun 18, 2024 |
| Lenovo        | ThinkPad T490s 20NX0056M... | [152002ea0d](https://linux-hardware.org/?probe=152002ea0d) | Jun 17, 2024 |
| Google        | Eldrid                      | [f88483c5cd](https://linux-hardware.org/?probe=f88483c5cd) | Jun 17, 2024 |
| HP            | ENVY Laptop 17-ch2xxx       | [cb2ef411da](https://linux-hardware.org/?probe=cb2ef411da) | Jun 14, 2024 |
| Acer          | Nitro AN515-54              | [d206754d7d](https://linux-hardware.org/?probe=d206754d7d) | Jun 14, 2024 |
| Notebook      | PCx0Dx                      | [a4312875de](https://linux-hardware.org/?probe=a4312875de) | Jun 14, 2024 |
| Acer          | Aspire E5-552               | [de63cc3364](https://linux-hardware.org/?probe=de63cc3364) | Jun 12, 2024 |
| Valve         | Jupiter                     | [a6e9eed9e2](https://linux-hardware.org/?probe=a6e9eed9e2) | Jun 08, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [2f685aa1e2](https://linux-hardware.org/?probe=2f685aa1e2) | Jun 08, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7acd354a76](https://linux-hardware.org/?probe=7acd354a76) | Jun 06, 2024 |
| ASUSTek       | U38N                        | [8e2ffe04bc](https://linux-hardware.org/?probe=8e2ffe04bc) | Jun 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b71f68fad4](https://linux-hardware.org/?probe=b71f68fad4) | Jun 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JRC... | [5f45e3b98b](https://linux-hardware.org/?probe=5f45e3b98b) | Jun 04, 2024 |
| HP            | EliteBook 745 G5            | [684a8af276](https://linux-hardware.org/?probe=684a8af276) | Jun 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [17e0305307](https://linux-hardware.org/?probe=17e0305307) | Jun 03, 2024 |
| Acer          | Nitro AN515-54              | [1ec0639f14](https://linux-hardware.org/?probe=1ec0639f14) | Jun 02, 2024 |
| Toshiba       | Satellite C850D-121         | [a58883b3d8](https://linux-hardware.org/?probe=a58883b3d8) | Jun 02, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [fa1fa5d6ef](https://linux-hardware.org/?probe=fa1fa5d6ef) | Jun 01, 2024 |
| Dynabook      | Satellite Pro C50-G-10M     | [333ff84280](https://linux-hardware.org/?probe=333ff84280) | May 31, 2024 |
| ASUSTek       | G75VW                       | [a61c1daa1a](https://linux-hardware.org/?probe=a61c1daa1a) | May 31, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FD... | [62005c1b3e](https://linux-hardware.org/?probe=62005c1b3e) | May 29, 2024 |
| Dell          | Precision M4600             | [0877f5550f](https://linux-hardware.org/?probe=0877f5550f) | May 28, 2024 |
| Lenovo        | ThinkPad T420s 4174PEG      | [ace0d96f73](https://linux-hardware.org/?probe=ace0d96f73) | May 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f872b53297](https://linux-hardware.org/?probe=f872b53297) | May 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [621c3eb0bf](https://linux-hardware.org/?probe=621c3eb0bf) | May 26, 2024 |
| Lenovo        | Y50-70 20378                | [8dacf8fe97](https://linux-hardware.org/?probe=8dacf8fe97) | May 24, 2024 |
| Acer          | Aspire ES1-311              | [f0470e4941](https://linux-hardware.org/?probe=f0470e4941) | May 24, 2024 |
| HP            | EliteBook 840 G6            | [63d3b721de](https://linux-hardware.org/?probe=63d3b721de) | May 23, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [e392c108f7](https://linux-hardware.org/?probe=e392c108f7) | May 22, 2024 |
| Dell          | Latitude 7410               | [84d4852ba0](https://linux-hardware.org/?probe=84d4852ba0) | May 20, 2024 |
| HP            | Pavilion Sleekbook 14 PC    | [aa7dc152cd](https://linux-hardware.org/?probe=aa7dc152cd) | May 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [873f394626](https://linux-hardware.org/?probe=873f394626) | May 19, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [26de605fb9](https://linux-hardware.org/?probe=26de605fb9) | May 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [533a0b51a1](https://linux-hardware.org/?probe=533a0b51a1) | May 18, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [71b182358a](https://linux-hardware.org/?probe=71b182358a) | May 18, 2024 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [5a33c3946a](https://linux-hardware.org/?probe=5a33c3946a) | May 18, 2024 |
| HP            | EliteBook 8740w             | [87a15cb71a](https://linux-hardware.org/?probe=87a15cb71a) | May 17, 2024 |
| HP            | ZBook Studio G5             | [ca7c92b09f](https://linux-hardware.org/?probe=ca7c92b09f) | May 15, 2024 |
| Dell          | XPS 13 9380                 | [c455fe7d68](https://linux-hardware.org/?probe=c455fe7d68) | May 14, 2024 |
| Apple         | MacBookAir4,1               | [9051848f26](https://linux-hardware.org/?probe=9051848f26) | May 13, 2024 |
| Apple         | MacBookAir4,1               | [6ce2799571](https://linux-hardware.org/?probe=6ce2799571) | May 12, 2024 |
| HP            | EliteBook 8570w             | [daea39278a](https://linux-hardware.org/?probe=daea39278a) | May 11, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [6ac93f82e9](https://linux-hardware.org/?probe=6ac93f82e9) | May 08, 2024 |
| MSI           | GF63 Thin 10SC              | [d419afc35f](https://linux-hardware.org/?probe=d419afc35f) | May 08, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [276faea129](https://linux-hardware.org/?probe=276faea129) | May 06, 2024 |
| MSI           | Alpha 17 B5EEK              | [8f78e61ba3](https://linux-hardware.org/?probe=8f78e61ba3) | May 06, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [d73bdd4b76](https://linux-hardware.org/?probe=d73bdd4b76) | May 06, 2024 |
| MSI           | Alpha 17 B5EEK              | [38d719b3cc](https://linux-hardware.org/?probe=38d719b3cc) | May 05, 2024 |
| Fujitsu       | LIFEBOOK T900               | [d396d19b06](https://linux-hardware.org/?probe=d396d19b06) | May 05, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [b950303950](https://linux-hardware.org/?probe=b950303950) | May 04, 2024 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [f4e6daf83f](https://linux-hardware.org/?probe=f4e6daf83f) | May 04, 2024 |
| HP            | EliteBook 820 G3            | [73f06a8daf](https://linux-hardware.org/?probe=73f06a8daf) | May 03, 2024 |
| ASUSTek       | G75VW                       | [151ab0d8e9](https://linux-hardware.org/?probe=151ab0d8e9) | May 01, 2024 |
| HP            | EliteBook 8570p             | [03f63c8caf](https://linux-hardware.org/?probe=03f63c8caf) | Apr 29, 2024 |
| HP            | EliteBook 8570p             | [5c699c7770](https://linux-hardware.org/?probe=5c699c7770) | Apr 29, 2024 |
| Dell          | Latitude 5540               | [71894c9703](https://linux-hardware.org/?probe=71894c9703) | Apr 29, 2024 |
| ASUSTek       | UX32VD                      | [1377417777](https://linux-hardware.org/?probe=1377417777) | Apr 29, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [40c7e6e4a3](https://linux-hardware.org/?probe=40c7e6e4a3) | Apr 28, 2024 |
| Acer          | Swift SF314-41              | [240aeeb256](https://linux-hardware.org/?probe=240aeeb256) | Apr 28, 2024 |
| Acer          | Nitro AN16-41               | [4cfb726ac6](https://linux-hardware.org/?probe=4cfb726ac6) | Apr 23, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [72b47f3d18](https://linux-hardware.org/?probe=72b47f3d18) | Apr 23, 2024 |
| Lenovo        | Legion 7 16IAX7 82TD        | [7c88cac728](https://linux-hardware.org/?probe=7c88cac728) | Apr 22, 2024 |
| Dell          | XPS 15 9530                 | [500ffeec7b](https://linux-hardware.org/?probe=500ffeec7b) | Apr 22, 2024 |
| Samsung       | N150/N210/N220              | [73f5edc5e5](https://linux-hardware.org/?probe=73f5edc5e5) | Apr 22, 2024 |
| Dell          | XPS 9320                    | [162d7ddcd3](https://linux-hardware.org/?probe=162d7ddcd3) | Apr 22, 2024 |
| Lenovo        | Z50-75 80EC                 | [62fb9d9789](https://linux-hardware.org/?probe=62fb9d9789) | Apr 21, 2024 |
| Acer          | Swift SF514-52T             | [d89f8a89a9](https://linux-hardware.org/?probe=d89f8a89a9) | Apr 20, 2024 |
| Lenovo        | ThinkPad X270 20HN0016MX    | [cd5fff4dcd](https://linux-hardware.org/?probe=cd5fff4dcd) | Apr 20, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [3c9edd18cd](https://linux-hardware.org/?probe=3c9edd18cd) | Apr 19, 2024 |
| Acer          | Swift SF314-71              | [4dbbe8a263](https://linux-hardware.org/?probe=4dbbe8a263) | Apr 18, 2024 |
| HP            | OMEN by Laptop 17-cb0xxx    | [50987e4554](https://linux-hardware.org/?probe=50987e4554) | Apr 18, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [3d43cbd697](https://linux-hardware.org/?probe=3d43cbd697) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | [3d679e4ec2](https://linux-hardware.org/?probe=3d679e4ec2) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | [b2d528d9b4](https://linux-hardware.org/?probe=b2d528d9b4) | Apr 16, 2024 |
| ASUSTek       | G75VW                       | [21e80243e1](https://linux-hardware.org/?probe=21e80243e1) | Apr 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [1450416558](https://linux-hardware.org/?probe=1450416558) | Apr 11, 2024 |
| Acer          | Aspire ES1-311              | [cd38e8b3bd](https://linux-hardware.org/?probe=cd38e8b3bd) | Apr 09, 2024 |
| HP            | ProBook 430 G3              | [2dff62b8e0](https://linux-hardware.org/?probe=2dff62b8e0) | Apr 09, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [543136ea4b](https://linux-hardware.org/?probe=543136ea4b) | Apr 08, 2024 |
| Apple         | MacBookPro5,4               | [3ab1d66e10](https://linux-hardware.org/?probe=3ab1d66e10) | Apr 08, 2024 |
| ASUSTek       | G752VSK                     | [49116bb834](https://linux-hardware.org/?probe=49116bb834) | Apr 08, 2024 |
| Dell          | Latitude E7450              | [80c9756b52](https://linux-hardware.org/?probe=80c9756b52) | Apr 08, 2024 |
| Acer          | Predator PH315-54           | [23dae5c2e2](https://linux-hardware.org/?probe=23dae5c2e2) | Apr 07, 2024 |
| Dell          | Latitude 5401               | [50c9a92ed4](https://linux-hardware.org/?probe=50c9a92ed4) | Apr 07, 2024 |
| Apple         | MacBookPro12,1              | [50c4a83180](https://linux-hardware.org/?probe=50c4a83180) | Apr 07, 2024 |
| Lenovo        | ThinkPad T490s 20NX0056M... | [3945b47d9b](https://linux-hardware.org/?probe=3945b47d9b) | Apr 07, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [b743bdc5b7](https://linux-hardware.org/?probe=b743bdc5b7) | Apr 06, 2024 |
| Acer          | Aspire ES1-311              | [9a68d90ab7](https://linux-hardware.org/?probe=9a68d90ab7) | Apr 05, 2024 |
| HP            | ZBook Studio 15.6 inch G... | [eb1f637530](https://linux-hardware.org/?probe=eb1f637530) | Apr 04, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [91906af7e3](https://linux-hardware.org/?probe=91906af7e3) | Apr 03, 2024 |
| HP            | EliteBook 840 G3            | [3ddde931c2](https://linux-hardware.org/?probe=3ddde931c2) | Apr 03, 2024 |
| HP            | Laptop 15-db0xxx            | [86bf1e5346](https://linux-hardware.org/?probe=86bf1e5346) | Apr 03, 2024 |
| Lenovo        | ThinkPad X280 20KF001RMX    | [0caddb11a4](https://linux-hardware.org/?probe=0caddb11a4) | Apr 02, 2024 |
| Apple         | MacBookPro15,2              | [fb59e4c861](https://linux-hardware.org/?probe=fb59e4c861) | Apr 01, 2024 |
| Apple         | MacBookPro11,2              | [7ccfbb7054](https://linux-hardware.org/?probe=7ccfbb7054) | Mar 31, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [63f04a080c](https://linux-hardware.org/?probe=63f04a080c) | Mar 31, 2024 |
| ASUSTek       | G75VW                       | [cff197ffbf](https://linux-hardware.org/?probe=cff197ffbf) | Mar 30, 2024 |
| Lenovo        | ThinkPad R400 7440WWQ       | [7c62efd0a5](https://linux-hardware.org/?probe=7c62efd0a5) | Mar 29, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [400955763a](https://linux-hardware.org/?probe=400955763a) | Mar 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [eb09797dad](https://linux-hardware.org/?probe=eb09797dad) | Mar 25, 2024 |
| MSI           | Bravo 15 C7UDX              | [6fb8db02b9](https://linux-hardware.org/?probe=6fb8db02b9) | Mar 25, 2024 |
| Lenovo        | VIWGQ                       | [881674c100](https://linux-hardware.org/?probe=881674c100) | Mar 24, 2024 |
| HP            | 15                          | [139e556699](https://linux-hardware.org/?probe=139e556699) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [4d1bc02be0](https://linux-hardware.org/?probe=4d1bc02be0) | Mar 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [0f6120fef2](https://linux-hardware.org/?probe=0f6120fef2) | Mar 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a20d8894bd](https://linux-hardware.org/?probe=a20d8894bd) | Mar 23, 2024 |
| HP            | ZBook 15 G2                 | [2ba706d8c9](https://linux-hardware.org/?probe=2ba706d8c9) | Mar 21, 2024 |
| Dell          | Precision M4600             | [ae97b86b04](https://linux-hardware.org/?probe=ae97b86b04) | Mar 20, 2024 |
| HP            | ZBook 15 G4                 | [1752ff36c3](https://linux-hardware.org/?probe=1752ff36c3) | Mar 20, 2024 |
| Dell          | Precision M4800             | [a6e69c7950](https://linux-hardware.org/?probe=a6e69c7950) | Mar 20, 2024 |
| HP            | EliteBook 840 G4            | [d6c0c2ac98](https://linux-hardware.org/?probe=d6c0c2ac98) | Mar 20, 2024 |
| eMachines     | eME642G                     | [8759a11aca](https://linux-hardware.org/?probe=8759a11aca) | Mar 20, 2024 |
| HP            | ProBook 440 G6              | [15167e6cda](https://linux-hardware.org/?probe=15167e6cda) | Mar 19, 2024 |
| Dell          | XPS 13 7390                 | [bd22d0e0ca](https://linux-hardware.org/?probe=bd22d0e0ca) | Mar 18, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [4ade0c63a8](https://linux-hardware.org/?probe=4ade0c63a8) | Mar 17, 2024 |
| Lenovo        | Legion 9 16IRX8 83AG        | [ca665b8165](https://linux-hardware.org/?probe=ca665b8165) | Mar 16, 2024 |
| System76      | Gazelle                     | [e4a975b366](https://linux-hardware.org/?probe=e4a975b366) | Mar 16, 2024 |
| eMachines     | eME642G                     | [7d7230a747](https://linux-hardware.org/?probe=7d7230a747) | Mar 16, 2024 |
| HP            | Pavilion Laptop 14-bf0xx    | [7ded8b5e80](https://linux-hardware.org/?probe=7ded8b5e80) | Mar 15, 2024 |
| MSI           | Bravo 15 C7UDX              | [4441dff3bf](https://linux-hardware.org/?probe=4441dff3bf) | Mar 15, 2024 |
| Unknown       | Unknown                     | [a4e49121d0](https://linux-hardware.org/?probe=a4e49121d0) | Mar 15, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [2d1ccd0458](https://linux-hardware.org/?probe=2d1ccd0458) | Mar 15, 2024 |
| Samsung       | 940XFG                      | [b60ac199c7](https://linux-hardware.org/?probe=b60ac199c7) | Mar 15, 2024 |
| Samsung       | 940XFG                      | [2698d3e097](https://linux-hardware.org/?probe=2698d3e097) | Mar 15, 2024 |
| HP            | Pavilion 15                 | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [944358baac](https://linux-hardware.org/?probe=944358baac) | Mar 11, 2024 |
| Apple         | MacBookAir7,2               | [89b268f1f8](https://linux-hardware.org/?probe=89b268f1f8) | Mar 11, 2024 |
| Valve         | Jupiter                     | [0a31a36586](https://linux-hardware.org/?probe=0a31a36586) | Mar 10, 2024 |
| ASUSTek       | G75VW                       | [c22c7f9510](https://linux-hardware.org/?probe=c22c7f9510) | Mar 10, 2024 |
| Toshiba       | Satellite L650              | [46a8d42eaa](https://linux-hardware.org/?probe=46a8d42eaa) | Mar 10, 2024 |
| Dell          | Latitude E6420              | [7ae5cc22b0](https://linux-hardware.org/?probe=7ae5cc22b0) | Mar 09, 2024 |
| Dell          | XPS 13 9370                 | [96e1e8d964](https://linux-hardware.org/?probe=96e1e8d964) | Mar 07, 2024 |
| Dell          | Latitude 7390               | [7eed1415ba](https://linux-hardware.org/?probe=7eed1415ba) | Mar 05, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [6fd9429f1c](https://linux-hardware.org/?probe=6fd9429f1c) | Mar 05, 2024 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [dee02a2e0f](https://linux-hardware.org/?probe=dee02a2e0f) | Mar 04, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [78090262bb](https://linux-hardware.org/?probe=78090262bb) | Mar 02, 2024 |
| Acer          | Predator PT516-51s          | [f3e05a8ef2](https://linux-hardware.org/?probe=f3e05a8ef2) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [88e7a5c628](https://linux-hardware.org/?probe=88e7a5c628) | Feb 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a387b3439f](https://linux-hardware.org/?probe=a387b3439f) | Feb 29, 2024 |
| HP            | Pavilion Laptop 14-bf0xx    | [7a9345dd2c](https://linux-hardware.org/?probe=7a9345dd2c) | Feb 28, 2024 |
| LG Electro... | 15Z980-A.AAS7U1             | [845caa9a4d](https://linux-hardware.org/?probe=845caa9a4d) | Feb 28, 2024 |
| IBM           | ThinkPad T43 18714AG        | [ac4a5c44a6](https://linux-hardware.org/?probe=ac4a5c44a6) | Feb 28, 2024 |
| Dell          | Latitude E6430              | [1121d113bf](https://linux-hardware.org/?probe=1121d113bf) | Feb 26, 2024 |
| Dell          | Latitude E6430              | [860bbdc112](https://linux-hardware.org/?probe=860bbdc112) | Feb 26, 2024 |
| Lenovo        | ThinkPad X260 20F6009SMS    | [027f3ceeb3](https://linux-hardware.org/?probe=027f3ceeb3) | Feb 26, 2024 |
| Lenovo        | ThinkPad L412 44034KG       | [93c5498399](https://linux-hardware.org/?probe=93c5498399) | Feb 25, 2024 |
| HP            | EliteBook 850 G6            | [7ed2cffcae](https://linux-hardware.org/?probe=7ed2cffcae) | Feb 23, 2024 |
| HP            | Laptop 15-db0xxx            | [8808c41478](https://linux-hardware.org/?probe=8808c41478) | Feb 22, 2024 |
| Dell          | Latitude E5420              | [910bc98f57](https://linux-hardware.org/?probe=910bc98f57) | Feb 21, 2024 |
| HP            | EliteBook 840 G3            | [aef715ec84](https://linux-hardware.org/?probe=aef715ec84) | Feb 20, 2024 |
| HP            | EliteBook 840 G3            | [8287dc23bb](https://linux-hardware.org/?probe=8287dc23bb) | Feb 20, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [760267fc7e](https://linux-hardware.org/?probe=760267fc7e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [78587a5ad4](https://linux-hardware.org/?probe=78587a5ad4) | Feb 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b5e81cd1b4](https://linux-hardware.org/?probe=b5e81cd1b4) | Feb 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [04c342c7e3](https://linux-hardware.org/?probe=04c342c7e3) | Feb 20, 2024 |
| Dell          | Latitude E7250              | [4dbb95d349](https://linux-hardware.org/?probe=4dbb95d349) | Feb 19, 2024 |
| HP            | Compaq nx7400 (RU427ET#A... | [3eb06482d0](https://linux-hardware.org/?probe=3eb06482d0) | Feb 19, 2024 |
| Acer          | Swift SFG14-72              | [24e5b8861c](https://linux-hardware.org/?probe=24e5b8861c) | Feb 19, 2024 |
| HP            | Compaq nx7400 (RU427ET#A... | [c00066136f](https://linux-hardware.org/?probe=c00066136f) | Feb 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [5b768d1518](https://linux-hardware.org/?probe=5b768d1518) | Feb 18, 2024 |
| ASUSTek       | G75VW                       | [ff0a6068a5](https://linux-hardware.org/?probe=ff0a6068a5) | Feb 17, 2024 |
| ASUSTek       | G75VW                       | [5ad9c09f49](https://linux-hardware.org/?probe=5ad9c09f49) | Feb 16, 2024 |
| Acer          | Aspire S3                   | [015a6bdb09](https://linux-hardware.org/?probe=015a6bdb09) | Feb 16, 2024 |
| HP            | EliteBook 820 G3            | [c9895bde68](https://linux-hardware.org/?probe=c9895bde68) | Feb 14, 2024 |
| HP            | EliteBook 820 G3            | [7fe1594df6](https://linux-hardware.org/?probe=7fe1594df6) | Feb 14, 2024 |
| ASUSTek       | G75VW                       | [a829d5fb44](https://linux-hardware.org/?probe=a829d5fb44) | Feb 14, 2024 |
| Lenovo        | ThinkPad X280 20KF001JMX    | [d370fcec49](https://linux-hardware.org/?probe=d370fcec49) | Feb 13, 2024 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [908b0efb23](https://linux-hardware.org/?probe=908b0efb23) | Feb 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [166c275408](https://linux-hardware.org/?probe=166c275408) | Feb 10, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [8e506a8c7e](https://linux-hardware.org/?probe=8e506a8c7e) | Feb 09, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [1c4b5365af](https://linux-hardware.org/?probe=1c4b5365af) | Feb 07, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [63843cbf43](https://linux-hardware.org/?probe=63843cbf43) | Feb 07, 2024 |
| Dell          | XPS 13 9370                 | [d29438d6d7](https://linux-hardware.org/?probe=d29438d6d7) | Feb 06, 2024 |
| HP            | EliteBook 8570w             | [4a1938d727](https://linux-hardware.org/?probe=4a1938d727) | Feb 06, 2024 |
| HP            | ZBook 15u G2                | [28b76e7488](https://linux-hardware.org/?probe=28b76e7488) | Feb 06, 2024 |
| Apple         | MacBookPro8,2               | [69a19c7a1d](https://linux-hardware.org/?probe=69a19c7a1d) | Feb 06, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [72e1aa0f99](https://linux-hardware.org/?probe=72e1aa0f99) | Feb 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [34e9a5b730](https://linux-hardware.org/?probe=34e9a5b730) | Feb 04, 2024 |
| HP            | EliteBook 8570w             | [57f28e0095](https://linux-hardware.org/?probe=57f28e0095) | Feb 04, 2024 |
| ASUSTek       | UX430UAR                    | [cc89a20253](https://linux-hardware.org/?probe=cc89a20253) | Feb 04, 2024 |
| Fujitsu Si... | AMILO Li3910                | [ecde56e2bb](https://linux-hardware.org/?probe=ecde56e2bb) | Feb 04, 2024 |
| Unknown       | Apple MacBook Air (M1, 2... | [c16e6118de](https://linux-hardware.org/?probe=c16e6118de) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | [47c6ea83ea](https://linux-hardware.org/?probe=47c6ea83ea) | Feb 03, 2024 |
| HP            | ZBook 15 G4                 | [72ea56fdbe](https://linux-hardware.org/?probe=72ea56fdbe) | Feb 03, 2024 |
| Schenker      | XMG APEX 15 MAX (E22)       | [cf8a09526d](https://linux-hardware.org/?probe=cf8a09526d) | Jan 30, 2024 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [aecdf1facc](https://linux-hardware.org/?probe=aecdf1facc) | Jan 30, 2024 |
| Gigabyte      | AORUS 15P XD                | [72e109e02a](https://linux-hardware.org/?probe=72e109e02a) | Jan 30, 2024 |
| Dell          | G3 3590                     | [7fb3fcb32c](https://linux-hardware.org/?probe=7fb3fcb32c) | Jan 28, 2024 |
| Dell          | Inspiron 13-5378            | [a742fdf96d](https://linux-hardware.org/?probe=a742fdf96d) | Jan 27, 2024 |
| Gigabyte      | AORUS 15P XD                | [fc6193b5bf](https://linux-hardware.org/?probe=fc6193b5bf) | Jan 26, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2be9790ea](https://linux-hardware.org/?probe=c2be9790ea) | Jan 25, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [362ad8ae7e](https://linux-hardware.org/?probe=362ad8ae7e) | Jan 24, 2024 |
| Lenovo        | ThinkPad X270 20HN0012MX    | [ac867529fa](https://linux-hardware.org/?probe=ac867529fa) | Jan 24, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [15666b6776](https://linux-hardware.org/?probe=15666b6776) | Jan 23, 2024 |
| Acer          | Aspire E5-551G              | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| HP            | Pavilion g6                 | [bac27c78e2](https://linux-hardware.org/?probe=bac27c78e2) | Jan 19, 2024 |
| HP            | Pavilion g6                 | [30da02f122](https://linux-hardware.org/?probe=30da02f122) | Jan 19, 2024 |
| Apple         | MacBookPro6,2               | [d39ea787aa](https://linux-hardware.org/?probe=d39ea787aa) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [187a8a84af](https://linux-hardware.org/?probe=187a8a84af) | Jan 18, 2024 |
| Dell          | Precision 5680              | [f52bddf877](https://linux-hardware.org/?probe=f52bddf877) | Jan 18, 2024 |
| Dell          | Precision 5680              | [2585a4f840](https://linux-hardware.org/?probe=2585a4f840) | Jan 18, 2024 |
| Lenovo        | ThinkPad X260 20F5S0NV00    | [cda7600532](https://linux-hardware.org/?probe=cda7600532) | Jan 18, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [694f38f139](https://linux-hardware.org/?probe=694f38f139) | Jan 16, 2024 |
| Unknown       | A70M                        | [b6a6c2e947](https://linux-hardware.org/?probe=b6a6c2e947) | Jan 14, 2024 |
| Apple         | MacBookAir3,1               | [043258f53d](https://linux-hardware.org/?probe=043258f53d) | Jan 14, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [d2db433ab2](https://linux-hardware.org/?probe=d2db433ab2) | Jan 12, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [0d7230b853](https://linux-hardware.org/?probe=0d7230b853) | Jan 11, 2024 |
| Valve         | Jupiter                     | [ab13227de0](https://linux-hardware.org/?probe=ab13227de0) | Jan 10, 2024 |
| Acer          | Aspire 6530G                | [184836d752](https://linux-hardware.org/?probe=184836d752) | Jan 09, 2024 |
| HP            | ZBook 17 G4                 | [5dc1550956](https://linux-hardware.org/?probe=5dc1550956) | Jan 09, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [96d648fbd8](https://linux-hardware.org/?probe=96d648fbd8) | Jan 07, 2024 |
| Acer          | Aspire ES1-512              | [c24ea3ef71](https://linux-hardware.org/?probe=c24ea3ef71) | Jan 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4c5cb3c1d4](https://linux-hardware.org/?probe=4c5cb3c1d4) | Jan 05, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [36f9070500](https://linux-hardware.org/?probe=36f9070500) | Jan 04, 2024 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [a37ab2b577](https://linux-hardware.org/?probe=a37ab2b577) | Jan 04, 2024 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [8d22dafe25](https://linux-hardware.org/?probe=8d22dafe25) | Jan 03, 2024 |
| Acer          | Aspire ES1-523              | [6b5ef78cce](https://linux-hardware.org/?probe=6b5ef78cce) | Jan 02, 2024 |
| HP            | Laptop 15-db0xxx            | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| Dell          | Latitude 7490               | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| ASUSTek       | UX550VE                     | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| ASUSTek       | G75VW                       | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a7878eaed](https://linux-hardware.org/?probe=2a7878eaed) | Dec 28, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [424a79de6b](https://linux-hardware.org/?probe=424a79de6b) | Dec 28, 2023 |
| Dell          | Latitude 5420               | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| PC Special... | N150CU                      | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1RS0... | [5c4efd5165](https://linux-hardware.org/?probe=5c4efd5165) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | [18ef14b687](https://linux-hardware.org/?probe=18ef14b687) | Dec 23, 2023 |
| HP            | ProBook 445 14 inch G10 ... | [5b3a77bd87](https://linux-hardware.org/?probe=5b3a77bd87) | Dec 20, 2023 |
| HP            | ProBook 650 G1              | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | ThinkPad X270 20HMS0B60H    | [059545a4ad](https://linux-hardware.org/?probe=059545a4ad) | Dec 17, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [c95903375b](https://linux-hardware.org/?probe=c95903375b) | Dec 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3324746751](https://linux-hardware.org/?probe=3324746751) | Dec 16, 2023 |
| PC Special... | N150CU                      | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [984c55c6a2](https://linux-hardware.org/?probe=984c55c6a2) | Dec 16, 2023 |
| PC Special... | N150CU                      | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [92b42d7c3e](https://linux-hardware.org/?probe=92b42d7c3e) | Dec 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [49278a194a](https://linux-hardware.org/?probe=49278a194a) | Dec 14, 2023 |
| HP            | Unknown                     | [6a46b87d41](https://linux-hardware.org/?probe=6a46b87d41) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| Acer          | Extensa 2509                | [ee00581b3a](https://linux-hardware.org/?probe=ee00581b3a) | Dec 11, 2023 |
| Dell          | XPS 9320                    | [91f9b06d7f](https://linux-hardware.org/?probe=91f9b06d7f) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| Acer          | Swift SFE16-43              | [e31c4454c6](https://linux-hardware.org/?probe=e31c4454c6) | Dec 04, 2023 |
| Acer          | Aspire V3-571               | [90e07856e4](https://linux-hardware.org/?probe=90e07856e4) | Dec 01, 2023 |
| HUAWEI        | KLVC-WXX9                   | [dd49d338b4](https://linux-hardware.org/?probe=dd49d338b4) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| HP            | Laptop 14-em0xxx            | [9530bb80db](https://linux-hardware.org/?probe=9530bb80db) | Nov 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [24e86fc568](https://linux-hardware.org/?probe=24e86fc568) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [288151e67d](https://linux-hardware.org/?probe=288151e67d) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Acer          | Predator PH315-53           | [8139afea1a](https://linux-hardware.org/?probe=8139afea1a) | Nov 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [94927ee986](https://linux-hardware.org/?probe=94927ee986) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8cb9c3b0a7](https://linux-hardware.org/?probe=8cb9c3b0a7) | Nov 24, 2023 |
| HP            | Presario CQ61               | [5c7a775c76](https://linux-hardware.org/?probe=5c7a775c76) | Nov 24, 2023 |
| HP            | EliteBook 6930p             | [6bc9169e34](https://linux-hardware.org/?probe=6bc9169e34) | Nov 23, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| Acer          | Aspire V3-571G              | [63c8984ac3](https://linux-hardware.org/?probe=63c8984ac3) | Nov 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e42bab7bfa](https://linux-hardware.org/?probe=e42bab7bfa) | Nov 15, 2023 |
| System76      | Adder WS                    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| Lenovo        | G50-30 80G0                 | [36d24b7c8b](https://linux-hardware.org/?probe=36d24b7c8b) | Nov 11, 2023 |
| Valve         | Jupiter                     | [040bcdd741](https://linux-hardware.org/?probe=040bcdd741) | Nov 10, 2023 |
| Apple         | MacBookPro11,1              | [224a0992ae](https://linux-hardware.org/?probe=224a0992ae) | Nov 08, 2023 |
| Apple         | MacBookPro11,1              | [9a3d616dad](https://linux-hardware.org/?probe=9a3d616dad) | Nov 08, 2023 |
| HP            | EliteBook 2570p             | [de38771bec](https://linux-hardware.org/?probe=de38771bec) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [5191c2b469](https://linux-hardware.org/?probe=5191c2b469) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| Dell          | Latitude 3190               | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| Dell          | Inspiron 14 Plus 7440       | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Acer          | Swift SF113-31              | [a6fbe4af41](https://linux-hardware.org/?probe=a6fbe4af41) | Nov 05, 2023 |
| HP            | Unknown                     | [c8cff9e339](https://linux-hardware.org/?probe=c8cff9e339) | Nov 05, 2023 |
| Dell          | XPS 13 9310                 | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [7b64212148](https://linux-hardware.org/?probe=7b64212148) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [0e71b912ec](https://linux-hardware.org/?probe=0e71b912ec) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A532               | [b596813aeb](https://linux-hardware.org/?probe=b596813aeb) | Nov 02, 2023 |
| Panasonic     | CF-54-1                     | [b7d7cde99a](https://linux-hardware.org/?probe=b7d7cde99a) | Nov 01, 2023 |
| Dell          | Precision 5570              | [fb83199260](https://linux-hardware.org/?probe=fb83199260) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9dd62a1bb2](https://linux-hardware.org/?probe=9dd62a1bb2) | Oct 31, 2023 |
| Dell          | Latitude 7370               | [f47b42c0b0](https://linux-hardware.org/?probe=f47b42c0b0) | Oct 30, 2023 |
| HP            | Unknown                     | [3aadbc5c33](https://linux-hardware.org/?probe=3aadbc5c33) | Oct 30, 2023 |
| HP            | Laptop 15-bw0xx             | [b61ad8059a](https://linux-hardware.org/?probe=b61ad8059a) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| HP            | G62                         | [bd714e9671](https://linux-hardware.org/?probe=bd714e9671) | Oct 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| ASUSTek       | G75VW                       | [e3bde6ede0](https://linux-hardware.org/?probe=e3bde6ede0) | Oct 28, 2023 |
| HP            | EliteBook 850 G4            | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| Fujitsu       | LIFEBOOK E752               | [c1078c11fb](https://linux-hardware.org/?probe=c1078c11fb) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | [b05283573c](https://linux-hardware.org/?probe=b05283573c) | Oct 26, 2023 |
| HP            | EliteBook 8560p             | [101037a3e1](https://linux-hardware.org/?probe=101037a3e1) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | [b98bc11e71](https://linux-hardware.org/?probe=b98bc11e71) | Oct 25, 2023 |
| Acer          | Aspire ES1-311              | [c505d21099](https://linux-hardware.org/?probe=c505d21099) | Oct 25, 2023 |
| Notebook      | NS5x_NS7xAU                 | [ad7033d138](https://linux-hardware.org/?probe=ad7033d138) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | [51f3725a80](https://linux-hardware.org/?probe=51f3725a80) | Oct 24, 2023 |
| Dell          | Latitude 3190               | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [88e833ab8a](https://linux-hardware.org/?probe=88e833ab8a) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [62ca050eaf](https://linux-hardware.org/?probe=62ca050eaf) | Oct 24, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 13 9310                 | [cceff4e3b1](https://linux-hardware.org/?probe=cceff4e3b1) | Oct 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0feec3b3ab](https://linux-hardware.org/?probe=0feec3b3ab) | Oct 19, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [0815767d1d](https://linux-hardware.org/?probe=0815767d1d) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| HP            | EliteBook 8760w             | [d5febd2212](https://linux-hardware.org/?probe=d5febd2212) | Oct 17, 2023 |
| HP            | EliteBook 8570p             | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Notebook      | NS5x_NS7xAU                 | [1568dbcf9b](https://linux-hardware.org/?probe=1568dbcf9b) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [80bd4e2684](https://linux-hardware.org/?probe=80bd4e2684) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [7901d1df27](https://linux-hardware.org/?probe=7901d1df27) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| HP            | ProBook 640 G1              | [f6fbcbf614](https://linux-hardware.org/?probe=f6fbcbf614) | Oct 11, 2023 |
| Dell          | Latitude 7420               | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c360c7552a](https://linux-hardware.org/?probe=c360c7552a) | Oct 08, 2023 |
| Dell          | Vostro 3550                 | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | [e5b3d089e8](https://linux-hardware.org/?probe=e5b3d089e8) | Oct 06, 2023 |
| Apple         | MacBook4,1                  | [11497e61f8](https://linux-hardware.org/?probe=11497e61f8) | Oct 06, 2023 |
| HP            | ZBook 14u G4                | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [071eee1057](https://linux-hardware.org/?probe=071eee1057) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420s 4170CTO      | [f141fc2bd7](https://linux-hardware.org/?probe=f141fc2bd7) | Oct 02, 2023 |
| Apple         | MacBookPro7,1               | [d88817f79c](https://linux-hardware.org/?probe=d88817f79c) | Oct 02, 2023 |
| HP            | ZBook Studio G5             | [3f96bd2883](https://linux-hardware.org/?probe=3f96bd2883) | Sep 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| HP            | ZBook Studio G5             | [239b5a3fd5](https://linux-hardware.org/?probe=239b5a3fd5) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| Dell          | Vostro 3550                 | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Latitude E7270              | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| Dell          | Latitude E5270              | [d091c4fa0e](https://linux-hardware.org/?probe=d091c4fa0e) | Sep 24, 2023 |
| Dell          | Inspiron 3541               | [da796376e1](https://linux-hardware.org/?probe=da796376e1) | Sep 23, 2023 |
| Valve         | Jupiter                     | [3889f9ca9d](https://linux-hardware.org/?probe=3889f9ca9d) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [1893bb3992](https://linux-hardware.org/?probe=1893bb3992) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| Dell          | XPS 13 9370                 | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [79142d7f53](https://linux-hardware.org/?probe=79142d7f53) | Sep 17, 2023 |
| ASUSTek       | K55DR                       | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| Samsung       | R530/R730/P590              | [d9bd973c79](https://linux-hardware.org/?probe=d9bd973c79) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Apple         | MacBookPro8,1               | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| Dell          | Precision M4800             | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| ASUSTek       | X453MA                      | [b73ef6339a](https://linux-hardware.org/?probe=b73ef6339a) | Sep 08, 2023 |
| ASUSTek       | X453MA                      | [e71f333094](https://linux-hardware.org/?probe=e71f333094) | Sep 07, 2023 |
| ASUSTek       | X453MA                      | [c48759c297](https://linux-hardware.org/?probe=c48759c297) | Sep 07, 2023 |
| Dell          | Latitude 7440               | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell          | Latitude 7440               | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [806eed53dc](https://linux-hardware.org/?probe=806eed53dc) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [377d5352d8](https://linux-hardware.org/?probe=377d5352d8) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Acer          | Aspire 5755G                | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| HP            | ProBook 6360b               | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| Apple         | MacBookAir6,2               | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Acer          | Aspire ES1-311              | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [f8f097e135](https://linux-hardware.org/?probe=f8f097e135) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| Dell          | Latitude 3350               | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [d989b68c65](https://linux-hardware.org/?probe=d989b68c65) | Aug 19, 2023 |
| ASUSTek       | M3N                         | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| Dell          | XPS 15 9570                 | [91b8c2a5eb](https://linux-hardware.org/?probe=91b8c2a5eb) | Aug 17, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Dell          | Inspiron 5559               | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [836fcda626](https://linux-hardware.org/?probe=836fcda626) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [3e208faa6e](https://linux-hardware.org/?probe=3e208faa6e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| HP            | Unknown                     | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| Acer          | Aspire 4810T                | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Toshiba       | Satellite C670D-11P         | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| ASUSTek       | G75VW                       | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3190               | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| HP            | Unknown                     | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Apple         | MacBookPro6,2               | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| HP            | EliteBook 745 G6            | [d8272e8eeb](https://linux-hardware.org/?probe=d8272e8eeb) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| ASUSTek       | K55DR                       | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| HP            | ProBook 4530s               | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| MSI           | GF65 Thin 10SER             | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [801eb1eb3c](https://linux-hardware.org/?probe=801eb1eb3c) | Jul 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Alienware     | x15 R1                      | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | G75VW                       | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [4b33cf2e09](https://linux-hardware.org/?probe=4b33cf2e09) | Jul 09, 2023 |
| IBM           | ThinkPad T43 18714AG        | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| Medion        | ML-210007                   | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [b6d0f85342](https://linux-hardware.org/?probe=b6d0f85342) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e0fc7e357f](https://linux-hardware.org/?probe=e0fc7e357f) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [0ca36f92b8](https://linux-hardware.org/?probe=0ca36f92b8) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| Acer          | Predator G9-593             | [127df9999f](https://linux-hardware.org/?probe=127df9999f) | Jul 01, 2023 |
| Acer          | Predator G9-593             | [d4dca39223](https://linux-hardware.org/?probe=d4dca39223) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| MSI           | GX60 1AC                    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| MSI           | Katana GF76 12UD            | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| Acer          | Aspire ES1-311              | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Acer          | Aspire ES1-311              | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Dell          | Latitude 7480               | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Dell          | Latitude 3320               | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Dell          | Latitude 3340               | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | X505BP                      | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Timi          | RedmiBook 14 II             | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| MSI           | Katana GF76 12UD            | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | G75VW                       | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| HP            | Compaq 6730s                | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [dbfc9be02f](https://linux-hardware.org/?probe=dbfc9be02f) | May 26, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25f6dcaefc](https://linux-hardware.org/?probe=25f6dcaefc) | May 25, 2023 |
| HP            | Laptop 14s-fq1xxx           | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [117bc29848](https://linux-hardware.org/?probe=117bc29848) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [e3af81180a](https://linux-hardware.org/?probe=e3af81180a) | May 22, 2023 |
| Acer          | Aspire E1-571               | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| HP            | Compaq 6730s                | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| Notebook      | NLx0MU                      | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| HP            | EliteBook 850 G6            | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| HP            | EliteBook 840 G5            | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | ProBook 6470b               | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| MSI           | Stealth 16Studio A13VG      | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| HP            | EliteBook 840 G6            | [bd7c97ad54](https://linux-hardware.org/?probe=bd7c97ad54) | May 11, 2023 |
| HP            | EliteBook 840 G6            | [483f4bbb5d](https://linux-hardware.org/?probe=483f4bbb5d) | May 10, 2023 |
| Dynabook      | Satellite Pro C50-J         | [535cc48341](https://linux-hardware.org/?probe=535cc48341) | May 08, 2023 |
| Dell          | Vostro 3360                 | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | Latitude 5430               | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Dell          | Latitude 7490               | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| Unknown       | Unknown                     | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |
| Dell          | XPS 13 9370                 | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| Acer          | Aspire ES1-311              | [810aed46d0](https://linux-hardware.org/?probe=810aed46d0) | Apr 11, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| HP            | ProBook 4530s               | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| LG Electro... | Kabylake Platform           | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| HP            | ProBook 450 G1              | [f49ec499ed](https://linux-hardware.org/?probe=f49ec499ed) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Dell          | Precision 5530              | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Acer          | Swift SF113-31              | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | ENVY TS Sleekbook 4         | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| GPD           | P2 MAX                      | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| HP            | Presario CQ57               | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| HP            | EliteBook Folio 9470m       | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| ASUSTek       | G75VW                       | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| GPD           | P2 MAX                      | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | EliteBook 820 G3            | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Apple         | MacBookPro10,1              | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| HP            | Laptop 15-dw1xxx            | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| Dell          | Latitude 7420               | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Valve         | Jupiter                     | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| AMI           | Intel                       | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Acer          | Aspire V3-571               | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| Star Labs     | StarBook                    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Dell          | Studio 1749                 | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Acer          | Aspire V3-571G              | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Lenovo        | Z70-80 80FG                 | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Valve         | Jupiter                     | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| Dell          | Latitude 3380               | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | Latitude 3380               | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | Latitude E7240              | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| Insyde        | G0975                       | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Dell          | Latitude 5430               | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| Sony          | VPCEB1M1E                   | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| Dell          | XPS 9320                    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| HP            | ZBook 15u G6                | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| HP            | EliteBook 830 G5            | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 150       | 9.24%   |
| Ubuntu 22.04                 | 119       | 7.33%   |
| Ubuntu 18.04                 | 74        | 4.56%   |
| Debian 12                    | 60        | 3.69%   |
| Arch Rolling                 | 51        | 3.14%   |
| Pop!_OS 22.04                | 48        | 2.96%   |
| Debian 11                    | 32        | 1.97%   |
| Zorin 16                     | 29        | 1.79%   |
| Manjaro                      | 29        | 1.79%   |
| Fedora 40                    | 29        | 1.79%   |
| Ubuntu 24.04                 | 27        | 1.66%   |
| ArcoLinux Rolling            | 25        | 1.54%   |
| openSUSE Tumbleweed-XXXXXXXX | 22        | 1.35%   |
| Pop!_OS 21.04                | 21        | 1.29%   |
| OpenMandriva 4.3             | 21        | 1.29%   |
| OpenMandriva 4.2             | 21        | 1.29%   |
| Arch                         | 21        | 1.29%   |
| Ubuntu 23.10                 | 20        | 1.23%   |
| Linux Mint 21.1              | 20        | 1.23%   |
| Fedora 35                    | 20        | 1.23%   |
| Ubuntu 19.04                 | 19        | 1.17%   |
| Zorin 15                     | 16        | 0.99%   |
| Ubuntu 21.10                 | 16        | 0.99%   |
| Pop!_OS 20.10                | 16        | 0.99%   |
| Pop!_OS 20.04                | 16        | 0.99%   |
| Linux Mint 20.3              | 15        | 0.92%   |
| KDE neon 20.04               | 15        | 0.92%   |
| Fedora 39                    | 15        | 0.92%   |
| Zorin 17                     | 14        | 0.86%   |
| Linux Mint 21.2              | 14        | 0.86%   |
| Linux Mint 20.2              | 14        | 0.86%   |
| Fedora 38                    | 14        | 0.86%   |
| Fedora 37                    | 14        | 0.86%   |
| EndeavourOS Rolling          | 14        | 0.86%   |
| Ubuntu 19.10                 | 13        | 0.8%    |
| Linux Mint 21.3              | 13        | 0.8%    |
| Linux Mint 20.1              | 12        | 0.74%   |
| Fedora 34                    | 12        | 0.74%   |
| Xubuntu 22.04                | 11        | 0.68%   |
| Ubuntu 21.04                 | 11        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 461       | 29.84%  |
| Fedora        | 145       | 9.39%   |
| Linux Mint    | 120       | 7.77%   |
| Debian        | 107       | 6.93%   |
| Pop!_OS       | 105       | 6.8%    |
| OpenMandriva  | 71        | 4.6%    |
| Arch          | 71        | 4.6%    |
| Manjaro       | 59        | 3.82%   |
| Zorin         | 58        | 3.75%   |
| Xubuntu       | 29        | 1.88%   |
| ArcoLinux     | 28        | 1.81%   |
| KDE neon      | 27        | 1.75%   |
| openSUSE      | 26        | 1.68%   |
| Kubuntu       | 23        | 1.49%   |
| Kali          | 18        | 1.17%   |
| EndeavourOS   | 17        | 1.1%    |
| SteamOS       | 15        | 0.97%   |
| Gentoo        | 14        | 0.91%   |
| Elementary    | 13        | 0.84%   |
| Endless       | 11        | 0.71%   |
| Ubuntu MATE   | 9         | 0.58%   |
| ROSA          | 9         | 0.58%   |
| LMDE          | 9         | 0.58%   |
| Parrot        | 7         | 0.45%   |
| NixOS         | 6         | 0.39%   |
| CentOS        | 6         | 0.39%   |
| BunsenLabs    | 6         | 0.39%   |
| Lubuntu       | 5         | 0.32%   |
| Garuda Linux  | 5         | 0.32%   |
| Ubuntu Budgie | 4         | 0.26%   |
| Peppermint    | 4         | 0.26%   |
| MX            | 4         | 0.26%   |
| Clear Linux   | 4         | 0.26%   |
| CachyOS       | 4         | 0.26%   |
| BlackPanther  | 4         | 0.26%   |
| Ubuntu Unity  | 3         | 0.19%   |
| Nobara        | 3         | 0.19%   |
| GNOME OS      | 3         | 0.19%   |
| Vanilla       | 2         | 0.13%   |
| Slackware     | 2         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 21        | 1.18%   |
| 5.16.7-desktop-1omv4003  | 20        | 1.13%   |
| 5.15.0-56-generic        | 19        | 1.07%   |
| 5.4.0-42-generic         | 18        | 1.01%   |
| 5.4.0-58-generic         | 12        | 0.68%   |
| 5.4.0-48-generic         | 12        | 0.68%   |
| 5.15.0-52-generic        | 12        | 0.68%   |
| 6.1.0-7-amd64            | 10        | 0.56%   |
| 5.3.0-40-generic         | 10        | 0.56%   |
| 5.15.0-91-generic        | 10        | 0.56%   |
| 5.15.0-60-generic        | 10        | 0.56%   |
| 5.13.0-30-generic        | 10        | 0.56%   |
| 6.4.11-desktop-1omv2390  | 9         | 0.51%   |
| 6.1.0-9-amd64            | 9         | 0.51%   |
| 6.1.0-18-amd64           | 9         | 0.51%   |
| 5.4.0-52-generic         | 9         | 0.51%   |
| 5.4.0-40-generic         | 9         | 0.51%   |
| 5.15.0-78-generic        | 9         | 0.51%   |
| 5.11.0-37-generic        | 9         | 0.51%   |
| 6.8.0-45-generic         | 8         | 0.45%   |
| 6.8.0-40-generic         | 8         | 0.45%   |
| 6.5.0-26-generic         | 8         | 0.45%   |
| 5.8.0-48-generic         | 8         | 0.45%   |
| 5.15.0-48-generic        | 8         | 0.45%   |
| 5.13.0-7614-generic      | 8         | 0.45%   |
| 6.8.0-31-generic         | 7         | 0.39%   |
| 6.6.10-76060610-generic  | 7         | 0.39%   |
| 6.5.0-14-generic         | 7         | 0.39%   |
| 5.4.0-70-generic         | 7         | 0.39%   |
| 5.4.0-65-generic         | 7         | 0.39%   |
| 5.19.0-35-generic        | 7         | 0.39%   |
| 5.15.0-76-generic        | 7         | 0.39%   |
| 5.13.0-39-generic        | 7         | 0.39%   |
| 5.10.0-8-amd64           | 7         | 0.39%   |
| 5.10.0-21-amd64          | 7         | 0.39%   |
| 4.15.0-47-generic        | 7         | 0.39%   |
| 6.5.0-28-generic         | 6         | 0.34%   |
| 6.1.0-21-amd64           | 6         | 0.34%   |
| 6.1.0-13-amd64           | 6         | 0.34%   |
| 5.8.0-7630-generic       | 6         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 179       | 10.6%   |
| 5.15.0  | 151       | 8.95%   |
| 6.1.0   | 80        | 4.74%   |
| 5.13.0  | 66        | 3.91%   |
| 5.11.0  | 66        | 3.91%   |
| 6.5.0   | 65        | 3.85%   |
| 6.8.0   | 57        | 3.38%   |
| 5.8.0   | 51        | 3.02%   |
| 5.3.0   | 46        | 2.73%   |
| 4.15.0  | 46        | 2.73%   |
| 5.10.0  | 45        | 2.67%   |
| 5.19.0  | 40        | 2.37%   |
| 6.2.0   | 39        | 2.31%   |
| 5.0.0   | 34        | 2.01%   |
| 4.18.0  | 23        | 1.36%   |
| 5.16.7  | 21        | 1.24%   |
| 5.10.14 | 21        | 1.24%   |
| 6.4.11  | 10        | 0.59%   |
| 6.11.0  | 10        | 0.59%   |
| 6.6.10  | 9         | 0.53%   |
| 6.2.6   | 9         | 0.53%   |
| 5.14.0  | 9         | 0.53%   |
| 6.9.3   | 8         | 0.47%   |
| 6.5.6   | 8         | 0.47%   |
| 6.0.12  | 7         | 0.41%   |
| 5.17.5  | 7         | 0.41%   |
| 6.1.52  | 6         | 0.36%   |
| 6.1.1   | 6         | 0.36%   |
| 5.16.0  | 6         | 0.36%   |
| 6.8.11  | 5         | 0.3%    |
| 6.7.9   | 5         | 0.3%    |
| 6.5.7   | 5         | 0.3%    |
| 6.4.0   | 5         | 0.3%    |
| 6.12.1  | 5         | 0.3%    |
| 6.10.6  | 5         | 0.3%    |
| 5.7.0   | 5         | 0.3%    |
| 5.18.0  | 5         | 0.3%    |
| 6.8.9   | 4         | 0.24%   |
| 6.8.5   | 4         | 0.24%   |
| 6.8.4   | 4         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 186       | 11.21%  |
| 5.15    | 184       | 11.09%  |
| 6.1     | 118       | 7.11%   |
| 6.5     | 87        | 5.24%   |
| 6.8     | 84        | 5.06%   |
| 5.10    | 83        | 5%      |
| 5.11    | 78        | 4.7%    |
| 5.13    | 76        | 4.58%   |
| 6.2     | 67        | 4.04%   |
| 5.8     | 63        | 3.8%    |
| 5.3     | 52        | 3.13%   |
| 5.19    | 47        | 2.83%   |
| 5.16    | 47        | 2.83%   |
| 4.15    | 46        | 2.77%   |
| 6.6     | 41        | 2.47%   |
| 5.0     | 36        | 2.17%   |
| 6.4     | 32        | 1.93%   |
| 6.10    | 29        | 1.75%   |
| 4.18    | 29        | 1.75%   |
| 6.11    | 26        | 1.57%   |
| 6.0     | 26        | 1.57%   |
| 6.9     | 23        | 1.39%   |
| 6.7     | 22        | 1.33%   |
| 5.14    | 21        | 1.27%   |
| 5.18    | 20        | 1.21%   |
| 5.17    | 20        | 1.21%   |
| 6.3     | 16        | 0.96%   |
| 6.12    | 14        | 0.84%   |
| 5.9     | 14        | 0.84%   |
| 5.12    | 14        | 0.84%   |
| 5.7     | 11        | 0.66%   |
| 5.6     | 11        | 0.66%   |
| 4.19    | 8         | 0.48%   |
| 5.5     | 7         | 0.42%   |
| 5.2     | 6         | 0.36%   |
| 4.9     | 5         | 0.3%    |
| 5.1     | 4         | 0.24%   |
| 4.14    | 2         | 0.12%   |
| 4.1     | 2         | 0.12%   |
| 4.20    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1456      | 98.64%  |
| i686    | 17        | 1.15%   |
| aarch64 | 3         | 0.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 758       | 48.71%  |
| KDE5            | 195       | 12.53%  |
| Unknown         | 158       | 10.15%  |
| XFCE            | 121       | 7.78%   |
| X-Cinnamon      | 109       | 7.01%   |
| MATE            | 34        | 2.19%   |
| KDE6            | 33        | 2.12%   |
| KDE             | 33        | 2.12%   |
| i3              | 16        | 1.03%   |
| Pantheon        | 13        | 0.84%   |
| Cinnamon        | 12        | 0.77%   |
| LXQt            | 11        | 0.71%   |
| sway            | 7         | 0.45%   |
| KDE4            | 7         | 0.45%   |
| Hyprland        | 6         | 0.39%   |
| LXDE            | 5         | 0.32%   |
| GNOME Flashback | 5         | 0.32%   |
| BunsenLabs      | 4         | 0.26%   |
| Budgie          | 4         | 0.26%   |
| Unity           | 3         | 0.19%   |
| awesome         | 3         | 0.19%   |
| qtile           | 2         | 0.13%   |
| Endless:GNOME   | 2         | 0.13%   |
| DWM             | 2         | 0.13%   |
| Deepin          | 2         | 0.13%   |
| xmonad          | 1         | 0.06%   |
| Unicorn:XFCE    | 1         | 0.06%   |
| Trinity         | 1         | 0.06%   |
| spectrwm        | 1         | 0.06%   |
| river:wlroots   | 1         | 0.06%   |
| none+i3         | 1         | 0.06%   |
| none+awesome    | 1         | 0.06%   |
| niri            | 1         | 0.06%   |
| LeftWM          | 1         | 0.06%   |
| DDE             | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 993       | 65.07%  |
| Wayland | 420       | 27.52%  |
| Unknown | 85        | 5.57%   |
| Tty     | 28        | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 706       | 45.73%  |
| GDM3    | 253       | 16.39%  |
| SDDM    | 205       | 13.28%  |
| LightDM | 173       | 11.2%   |
| GDM     | 165       | 10.69%  |
| TDM     | 28        | 1.81%   |
| LXDM    | 4         | 0.26%   |
| XDM     | 3         | 0.19%   |
| KDM     | 3         | 0.19%   |
| Ly      | 2         | 0.13%   |
| WDM     | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 763       | 50.26%  |
| sv_SE      | 406       | 26.75%  |
| Unknown    | 130       | 8.56%   |
| en_GB      | 101       | 6.65%   |
| C          | 26        | 1.71%   |
| ru_RU      | 16        | 1.05%   |
| de_DE      | 12        | 0.79%   |
| pl_PL      | 9         | 0.59%   |
| en_SE      | 5         | 0.33%   |
| it_IT      | 4         | 0.26%   |
| fr_FR      | 4         | 0.26%   |
| fi_FI      | 4         | 0.26%   |
| en_CA      | 4         | 0.26%   |
| el_GR      | 4         | 0.26%   |
| en_DK      | 3         | 0.2%    |
| zh_CN      | 2         | 0.13%   |
| uk_UA      | 2         | 0.13%   |
| sv_FI      | 2         | 0.13%   |
| POSIX      | 2         | 0.13%   |
| lt_LT      | 2         | 0.13%   |
| en_IE      | 2         | 0.13%   |
| en_AG      | 2         | 0.13%   |
| C.UTF8     | 2         | 0.13%   |
| tr_TR      | 1         | 0.07%   |
| sv_SE.UTF8 | 1         | 0.07%   |
| nn_NO      | 1         | 0.07%   |
| nb_NO      | 1         | 0.07%   |
| hu_HU      | 1         | 0.07%   |
| gl_ES      | 1         | 0.07%   |
| es_ES      | 1         | 0.07%   |
| en_US.UTF8 | 1         | 0.07%   |
| en_AU      | 1         | 0.07%   |
| da_DK      | 1         | 0.07%   |
| bg_BG      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 810       | 53.47%  |
| BIOS | 705       | 46.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1061      | 69.44%  |
| Btrfs   | 215       | 14.07%  |
| Tmpfs   | 94        | 6.15%   |
| Overlay | 79        | 5.17%   |
| Unknown | 32        | 2.09%   |
| Xfs     | 18        | 1.18%   |
| Zfs     | 16        | 1.05%   |
| Ext2    | 7         | 0.46%   |
| F2fs    | 4         | 0.26%   |
| XXXXXXX | 1         | 0.07%   |
| Ext3    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 704       | 46.44%  |
| GPT     | 685       | 45.18%  |
| MBR     | 127       | 8.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1367      | 91.38%  |
| Yes       | 129       | 8.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1210      | 81.26%  |
| Yes       | 279       | 18.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 370       | 25.07%  |
| Hewlett-Packard     | 309       | 20.93%  |
| Dell                | 208       | 14.09%  |
| ASUSTek Computer    | 190       | 12.87%  |
| Acer                | 107       | 7.25%   |
| Apple               | 65        | 4.4%    |
| MSI                 | 32        | 2.17%   |
| Toshiba             | 19        | 1.29%   |
| Sony                | 17        | 1.15%   |
| Valve               | 15        | 1.02%   |
| Samsung Electronics | 14        | 0.95%   |
| Packard Bell        | 12        | 0.81%   |
| Notebook            | 12        | 0.81%   |
| Fujitsu             | 11        | 0.75%   |
| Google              | 10        | 0.68%   |
| Unknown             | 10        | 0.68%   |
| Fujitsu Siemens     | 8         | 0.54%   |
| HUAWEI              | 6         | 0.41%   |
| TUXEDO              | 4         | 0.27%   |
| System76            | 3         | 0.2%    |
| Star Labs           | 3         | 0.2%    |
| LG Electronics      | 3         | 0.2%    |
| Gigabyte Technology | 3         | 0.2%    |
| eMachines           | 3         | 0.2%    |
| Clevo               | 3         | 0.2%    |
| Alienware           | 3         | 0.2%    |
| Timi                | 2         | 0.14%   |
| SLIMBOOK            | 2         | 0.14%   |
| Schenker            | 2         | 0.14%   |
| Razer               | 2         | 0.14%   |
| PC Specialist       | 2         | 0.14%   |
| Insyde              | 2         | 0.14%   |
| Dynabook            | 2         | 0.14%   |
| ZEPTO               | 1         | 0.07%   |
| YJKC                | 1         | 0.07%   |
| win element         | 1         | 0.07%   |
| Purism              | 1         | 0.07%   |
| PINE64              | 1         | 0.07%   |
| Panasonic           | 1         | 0.07%   |
| On by NetOnNet      | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Valve Jupiter                        | 15        | 1.02%   |
| Unknown                              | 15        | 1.02%   |
| Dell XPS 13 9370                     | 9         | 0.61%   |
| Dell XPS 13 9310                     | 9         | 0.61%   |
| HP EliteBook 840 G3                  | 8         | 0.54%   |
| Apple MacBookAir7,2                  | 8         | 0.54%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5     | 6         | 0.41%   |
| HP Pavilion dv7                      | 6         | 0.41%   |
| HP Pavilion 15                       | 6         | 0.41%   |
| HP EliteBook Folio 9470m             | 6         | 0.41%   |
| HP EliteBook 840 G2                  | 6         | 0.41%   |
| Dell Precision 5540                  | 6         | 0.41%   |
| Apple MacBookPro9,2                  | 6         | 0.41%   |
| Acer Aspire V3-571                   | 6         | 0.41%   |
| Lenovo G50-30 80G0                   | 5         | 0.34%   |
| HP ZBook 15 G2                       | 5         | 0.34%   |
| HP ProBook 640 G1                    | 5         | 0.34%   |
| HP Pavilion g6                       | 5         | 0.34%   |
| HP EliteBook 840 G6                  | 5         | 0.34%   |
| HP EliteBook 820 G3                  | 5         | 0.34%   |
| Dell XPS 15 9570                     | 5         | 0.34%   |
| Dell XPS 15 9500                     | 5         | 0.34%   |
| ASUS G75VW                           | 5         | 0.34%   |
| Apple MacBookPro8,1                  | 5         | 0.34%   |
| Apple MacBookPro12,1                 | 5         | 0.34%   |
| Apple MacBookPro11,3                 | 5         | 0.34%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS   | 4         | 0.27%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX | 4         | 0.27%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00 | 4         | 0.27%   |
| HP ZBook Studio G5                   | 4         | 0.27%   |
| HP ProBook 430 G1                    | 4         | 0.27%   |
| HP Pavilion Notebook                 | 4         | 0.27%   |
| HP Laptop 15s-eq2xxx                 | 4         | 0.27%   |
| HP Laptop 15-db0xxx                  | 4         | 0.27%   |
| HP EliteBook 8570p                   | 4         | 0.27%   |
| HP EliteBook 8440p                   | 4         | 0.27%   |
| HP EliteBook 830 G6                  | 4         | 0.27%   |
| Dell XPS 9320                        | 4         | 0.27%   |
| Dell Precision M4800                 | 4         | 0.27%   |
| Dell Latitude E7240                  | 4         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 227       | 15.38%  |
| HP EliteBook          | 110       | 7.45%   |
| Dell Latitude         | 82        | 5.56%   |
| Acer Aspire           | 68        | 4.61%   |
| Lenovo IdeaPad        | 62        | 4.2%    |
| Dell XPS              | 56        | 3.79%   |
| HP ProBook            | 47        | 3.18%   |
| HP Pavilion           | 47        | 3.18%   |
| Dell Precision        | 47        | 3.18%   |
| HP ZBook              | 35        | 2.37%   |
| ASUS VivoBook         | 33        | 2.24%   |
| ASUS ROG              | 25        | 1.69%   |
| HP Laptop             | 23        | 1.56%   |
| Lenovo Yoga           | 20        | 1.36%   |
| Lenovo Legion         | 18        | 1.22%   |
| Acer Swift            | 18        | 1.22%   |
| Toshiba Satellite     | 17        | 1.15%   |
| ASUS ZenBook          | 17        | 1.15%   |
| ASUS ASUS             | 16        | 1.08%   |
| Valve Jupiter         | 15        | 1.02%   |
| HP Compaq             | 15        | 1.02%   |
| Unknown               | 15        | 1.02%   |
| Dell Inspiron         | 12        | 0.81%   |
| Packard Bell EasyNote | 11        | 0.75%   |
| Fujitsu LIFEBOOK      | 10        | 0.68%   |
| Apple MacBookPro11    | 10        | 0.68%   |
| Dell Vostro           | 9         | 0.61%   |
| Acer Nitro            | 9         | 0.61%   |
| HP ENVY               | 8         | 0.54%   |
| Apple MacBookAir7     | 8         | 0.54%   |
| Acer Predator         | 7         | 0.47%   |
| ASUS TUF              | 6         | 0.41%   |
| Apple MacBookPro9     | 6         | 0.41%   |
| Apple MacBookPro8     | 6         | 0.41%   |
| Apple MacBookAir6     | 6         | 0.41%   |
| Lenovo ThinkBook      | 5         | 0.34%   |
| Lenovo G50-30         | 5         | 0.34%   |
| HP OMEN               | 5         | 0.34%   |
| ASUS G75VW            | 5         | 0.34%   |
| Apple MacBookPro12    | 5         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 140       | 9.49%   |
| 2018    | 123       | 8.33%   |
| 2019    | 120       | 8.13%   |
| 2020    | 119       | 8.06%   |
| 2013    | 113       | 7.66%   |
| 2012    | 106       | 7.18%   |
| 2014    | 91        | 6.17%   |
| 2017    | 88        | 5.96%   |
| 2011    | 88        | 5.96%   |
| 2022    | 76        | 5.15%   |
| 2016    | 74        | 5.01%   |
| 2015    | 74        | 5.01%   |
| 2010    | 65        | 4.4%    |
| 2023    | 62        | 4.2%    |
| 2008    | 47        | 3.18%   |
| 2007    | 31        | 2.1%    |
| 2009    | 25        | 1.69%   |
| 2024    | 15        | 1.02%   |
| 2006    | 10        | 0.68%   |
| 2005    | 6         | 0.41%   |
| Unknown | 2         | 0.14%   |
| 2004    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1476      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1299      | 87.36%  |
| Enabled  | 188       | 12.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1461      | 98.98%  |
| Yes  | 15        | 1.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 412       | 27.6%   |
| 16.01-24.0  | 296       | 19.83%  |
| 8.01-16.0   | 272       | 18.22%  |
| 3.01-4.0    | 226       | 15.14%  |
| 32.01-64.0  | 183       | 12.26%  |
| 1.01-2.0    | 43        | 2.88%   |
| 24.01-32.0  | 31        | 2.08%   |
| 64.01-256.0 | 15        | 1%      |
| 2.01-3.0    | 10        | 0.67%   |
| 0.51-1.0    | 5         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 507       | 31.18%  |
| 2.01-3.0   | 407       | 25.03%  |
| 4.01-8.0   | 294       | 18.08%  |
| 3.01-4.0   | 252       | 15.5%   |
| 8.01-16.0  | 74        | 4.55%   |
| 0.51-1.0   | 62        | 3.81%   |
| 16.01-24.0 | 14        | 0.86%   |
| 0.01-0.5   | 12        | 0.74%   |
| 32.01-64.0 | 2         | 0.12%   |
| 24.01-32.0 | 2         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1201      | 80.01%  |
| 2      | 257       | 17.12%  |
| 3      | 28        | 1.87%   |
| 0      | 9         | 0.6%    |
| 4      | 5         | 0.33%   |
| 5      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1091      | 73.67%  |
| Yes       | 390       | 26.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1176      | 79.3%   |
| No        | 307       | 20.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1441      | 97.5%   |
| No        | 37        | 2.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1252      | 83.8%   |
| No        | 242       | 16.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 1476      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Stockholm         | 319       | 19.86%  |
| Gothenburg        | 154       | 9.59%   |
| Malmo             | 75        | 4.67%   |
| Uppsala           | 40        | 2.49%   |
| Västerås        | 23        | 1.43%   |
| Linköping        | 23        | 1.43%   |
| Lund              | 22        | 1.37%   |
| Solna             | 21        | 1.31%   |
| Bromma            | 21        | 1.31%   |
| Örebro           | 20        | 1.25%   |
| Umeå             | 19        | 1.18%   |
| Sollentuna        | 17        | 1.06%   |
| Saltsjoe-Boo      | 17        | 1.06%   |
| Vaxjo             | 16        | 1%      |
| Huddinge          | 15        | 0.93%   |
| Sundsvall         | 14        | 0.87%   |
| Norrköping       | 14        | 0.87%   |
| Helsingborg       | 14        | 0.87%   |
| Jönköping       | 13        | 0.81%   |
| Sundbyberg        | 12        | 0.75%   |
| Karlskrona        | 12        | 0.75%   |
| Bandhagen         | 12        | 0.75%   |
| Vaestra Froelunda | 11        | 0.68%   |
| Taby              | 11        | 0.68%   |
| Kista             | 11        | 0.68%   |
| Karlstad          | 11        | 0.68%   |
| Halmstad          | 11        | 0.68%   |
| Gävle            | 11        | 0.68%   |
| Spanga            | 9         | 0.56%   |
| Södertälje      | 9         | 0.56%   |
| Norsborg          | 9         | 0.56%   |
| Luleå            | 9         | 0.56%   |
| Haegersten        | 9         | 0.56%   |
| Ängelholm        | 9         | 0.56%   |
| Mjoelby           | 8         | 0.5%    |
| Landskrona        | 8         | 0.5%    |
| Eskilstuna        | 8         | 0.5%    |
| Uddevalla         | 7         | 0.44%   |
| Staffanstorp      | 7         | 0.44%   |
| Moelndal          | 7         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 386       | 527    | 22.01%  |
| WDC                            | 140       | 176    | 7.98%   |
| SanDisk                        | 129       | 162    | 7.35%   |
| Kingston                       | 117       | 153    | 6.67%   |
| Seagate                        | 114       | 137    | 6.5%    |
| Toshiba                        | 112       | 140    | 6.39%   |
| Intel                          | 108       | 123    | 6.16%   |
| SK hynix                       | 106       | 115    | 6.04%   |
| Unknown                        | 83        | 104    | 4.73%   |
| Micron Technology              | 80        | 88     | 4.56%   |
| Hitachi                        | 48        | 56     | 2.74%   |
| Apple                          | 45        | 60     | 2.57%   |
| HGST                           | 36        | 42     | 2.05%   |
| Crucial                        | 30        | 39     | 1.71%   |
| KIOXIA                         | 21        | 24     | 1.2%    |
| LITEON                         | 19        | 24     | 1.08%   |
| Kingston Technology Company    | 17        | 18     | 0.97%   |
| Phison Electronics             | 10        | 11     | 0.57%   |
| A-DATA Technology              | 10        | 10     | 0.57%   |
| OCZ                            | 9         | 9      | 0.51%   |
| LITEONIT                       | 8         | 13     | 0.46%   |
| Lenovo                         | 6         | 6      | 0.34%   |
| Intenso                        | 6         | 6      | 0.34%   |
| Phison                         | 5         | 5      | 0.29%   |
| JMicron Technology             | 5         | 5      | 0.29%   |
| Fujitsu                        | 5         | 7      | 0.29%   |
| China                          | 5         | 5      | 0.29%   |
| Unknown                        | 5         | 5      | 0.29%   |
| Transcend                      | 4         | 4      | 0.23%   |
| PNY                            | 4         | 4      | 0.23%   |
| Micron/Crucial Technology      | 4         | 5      | 0.23%   |
| Union Memory                   | 3         | 3      | 0.17%   |
| SSSTC                          | 3         | 4      | 0.17%   |
| Solid State Storage Technology | 3         | 3      | 0.17%   |
| Silicon Motion                 | 3         | 15     | 0.17%   |
| Verbatim                       | 2         | 8      | 0.11%   |
| UMIS                           | 2         | 2      | 0.11%   |
| Star Drive                     | 2         | 2      | 0.11%   |
| SSK                            | 2         | 2      | 0.11%   |
| ROG                            | 2         | 2      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 31        | 1.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 21        | 1.16%   |
| Kingston SA400S37480G 480GB SSD                      | 16        | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 14        | 0.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 13        | 0.72%   |
| SanDisk NVMe SSD Drive 512GB                         | 13        | 0.72%   |
| Kingston SA400S37120G 120GB SSD                      | 13        | 0.72%   |
| Unknown MMC Card  32GB                               | 12        | 0.66%   |
| Toshiba NVMe SSD Drive 512GB                         | 12        | 0.66%   |
| Unknown MMC Card  64GB                               | 11        | 0.61%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 11        | 0.61%   |
| SK hynix NVMe SSD Drive 512GB                        | 11        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 11        | 0.61%   |
| Samsung SSD 850 EVO 250GB                            | 11        | 0.61%   |
| Samsung NVMe SSD Drive 512GB                         | 11        | 0.61%   |
| Unknown MMC Card  16GB                               | 10        | 0.55%   |
| Samsung SSD 850 EVO 500GB                            | 10        | 0.55%   |
| Kingston SA400S37240G 240GB SSD                      | 10        | 0.55%   |
| HGST HTS721010A9E630 1TB                             | 10        | 0.55%   |
| Seagate ST9500325AS 500GB                            | 9         | 0.5%    |
| Samsung SSD 860 EVO 500GB                            | 9         | 0.5%    |
| Samsung NVMe SSD Drive 256GB                         | 9         | 0.5%    |
| Samsung NVMe SSD Drive 1024GB                        | 9         | 0.5%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD                  | 9         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                      | 8         | 0.44%   |
| SanDisk NVMe SSD Drive 1TB                           | 8         | 0.44%   |
| Intel SSDPEKNU512GZ 512GB                            | 8         | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 7         | 0.39%   |
| Unknown MMC Card  128GB                              | 7         | 0.39%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB               | 7         | 0.39%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 7         | 0.39%   |
| Intel SSDPEKNW010T8 1TB                              | 7         | 0.39%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 512GB        | 7         | 0.39%   |
| Intel NVMe SSD Drive 256GB                           | 7         | 0.39%   |
| Apple SSD SD0128F 121GB                              | 7         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 6         | 0.33%   |
| Toshiba XG4 NVMe SSD Controller 512GB                | 6         | 0.33%   |
| Toshiba NVMe SSD Drive 256GB                         | 6         | 0.33%   |
| Seagate ST320LT007-9ZV142 320GB                      | 6         | 0.33%   |
| Seagate ST1000LM035-1RK172 1TB                       | 6         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 130    | 31.96%  |
| WDC                 | 76        | 96     | 22.29%  |
| Hitachi             | 48        | 56     | 14.08%  |
| Toshiba             | 42        | 51     | 12.32%  |
| HGST                | 36        | 42     | 10.56%  |
| Samsung Electronics | 8         | 8      | 2.35%   |
| Fujitsu             | 5         | 7      | 1.47%   |
| Unknown             | 4         | 5      | 1.17%   |
| Apple               | 4         | 4      | 1.17%   |
| JMicron Technology  | 2         | 2      | 0.59%   |
| ASMT                | 2         | 2      | 0.59%   |
| TO Exter            | 1         | 1      | 0.29%   |
| Intenso             | 1         | 1      | 0.29%   |
| HGST HTS            | 1         | 1      | 0.29%   |
| Apricorn            | 1         | 1      | 0.29%   |
| Unknown             | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 166       | 245    | 26.9%   |
| Kingston            | 90        | 120    | 14.59%  |
| SanDisk             | 59        | 74     | 9.56%   |
| Intel               | 53        | 59     | 8.59%   |
| Apple               | 35        | 42     | 5.67%   |
| Micron Technology   | 32        | 36     | 5.19%   |
| Crucial             | 29        | 38     | 4.7%    |
| WDC                 | 28        | 37     | 4.54%   |
| SK hynix            | 21        | 23     | 3.4%    |
| LITEON              | 18        | 23     | 2.92%   |
| Toshiba             | 15        | 23     | 2.43%   |
| OCZ                 | 9         | 9      | 1.46%   |
| LITEONIT            | 8         | 13     | 1.3%    |
| A-DATA Technology   | 6         | 6      | 0.97%   |
| China               | 5         | 5      | 0.81%   |
| Transcend           | 4         | 4      | 0.65%   |
| PNY                 | 4         | 4      | 0.65%   |
| Intenso             | 4         | 4      | 0.65%   |
| Verbatim            | 2         | 8      | 0.32%   |
| SSSTC               | 2         | 3      | 0.32%   |
| M4-CT128            | 2         | 2      | 0.32%   |
| KingSpec            | 2         | 2      | 0.32%   |
| Corsair             | 2         | 2      | 0.32%   |
| Unknown             | 1         | 1      | 0.16%   |
| Team                | 1         | 1      | 0.16%   |
| Star                | 1         | 1      | 0.16%   |
| SPCC                | 1         | 1      | 0.16%   |
| Seagate             | 1         | 1      | 0.16%   |
| SATECHI             | 1         | 1      | 0.16%   |
| Radeon              | 1         | 2      | 0.16%   |
| OCZ-VERTEX3         | 1         | 1      | 0.16%   |
| Netac               | 1         | 1      | 0.16%   |
| Neo                 | 1         | 1      | 0.16%   |
| MyDigitalSSD        | 1         | 1      | 0.16%   |
| Maxtor              | 1         | 1      | 0.16%   |
| Lexar               | 1         | 1      | 0.16%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.16%   |
| KingFast            | 1         | 1      | 0.16%   |
| JD                  | 1         | 1      | 0.16%   |
| GOODRAM             | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 658       | 856    | 39.81%  |
| SSD     | 566       | 805    | 34.24%  |
| HDD     | 332       | 408    | 20.08%  |
| MMC     | 81        | 100    | 4.9%    |
| Unknown | 16        | 15     | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 817       | 1182   | 50.97%  |
| NVMe | 656       | 851    | 40.92%  |
| MMC  | 81        | 100    | 5.05%   |
| SAS  | 49        | 51     | 3.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 690       | 965    | 77.62%  |
| 0.51-1.0   | 181       | 229    | 20.36%  |
| 1.01-2.0   | 14        | 15     | 1.57%   |
| 4.01-10.0  | 2         | 2      | 0.22%   |
| 3.01-4.0   | 1         | 1      | 0.11%   |
| 10.01-20.0 | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 486       | 31.23%  |
| 251-500        | 395       | 25.39%  |
| 501-1000       | 228       | 14.65%  |
| 1-20           | 113       | 7.26%   |
| 1001-2000      | 95        | 6.11%   |
| 51-100         | 83        | 5.33%   |
| Unknown        | 68        | 4.37%   |
| 21-50          | 45        | 2.89%   |
| More than 3000 | 24        | 1.54%   |
| 2001-3000      | 19        | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 628       | 39.01%  |
| 21-50          | 285       | 17.7%   |
| 101-250        | 239       | 14.84%  |
| 51-100         | 192       | 11.93%  |
| 251-500        | 103       | 6.4%    |
| Unknown        | 68        | 4.22%   |
| 501-1000       | 64        | 3.98%   |
| 1001-2000      | 22        | 1.37%   |
| 2001-3000      | 4         | 0.25%   |
| More than 3000 | 3         | 0.19%   |
| 0              | 2         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 4         | 4      | 5.56%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 3         | 4      | 4.17%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 2      | 2.78%   |
| Seagate ST9250410AS 250GB                           | 2         | 3      | 2.78%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 2.78%   |
| Intel SSDSC2BW240A4 240GB                           | 2         | 3      | 2.78%   |
| HGST HTS725032A7E630 320GB                          | 2         | 2      | 2.78%   |
| HGST HTS545050A7E380 500GB                          | 2         | 3      | 2.78%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 2.78%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB             | 1         | 1      | 1.39%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 1      | 1.39%   |
| Toshiba MK6465GSX 640GB                             | 1         | 1      | 1.39%   |
| Toshiba MK4026GAX RoHS 40GB                         | 1         | 2      | 1.39%   |
| Toshiba MK1633GSG 160GB                             | 1         | 1      | 1.39%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 1.39%   |
| Team L5 LITE SSD 240GB                              | 1         | 1      | 1.39%   |
| SSSTC CV8-8E128-HP 128GB SSD                        | 1         | 1      | 1.39%   |
| SK hynix SH920 mSATA 128GB SSD                      | 1         | 1      | 1.39%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD               | 1         | 1      | 1.39%   |
| Silicon Motion 1TB PCS PCIe M.2 SSD                 | 1         | 1      | 1.39%   |
| Seagate ST980817AS 80GB                             | 1         | 1      | 1.39%   |
| Seagate ST96812A 64GB                               | 1         | 1      | 1.39%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 1.39%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 1.39%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 1.39%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 2      | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 1.39%   |
| SanDisk SD9SN8W-256G-1006 256GB SSD                 | 1         | 1      | 1.39%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1         | 1      | 1.39%   |
| Samsung Electronics SSD PM810 2.5 7mm 256GB         | 1         | 1      | 1.39%   |
| Samsung Electronics SSD 980 1TB                     | 1         | 1      | 1.39%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 1.39%   |
| Samsung Electronics MZ7PA128HMCD-010L1 128GB SSD    | 1         | 1      | 1.39%   |
| OCZ AGILITY3 120GB SSD                              | 1         | 1      | 1.39%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 1.39%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD      | 1         | 1      | 1.39%   |
| LITEONIT LMT-256M6M-HP 256GB SSD                    | 1         | 1      | 1.39%   |
| Kingston SKC6001024G 1024GB SSD                     | 1         | 1      | 1.39%   |
| Intel SSDSCKKF256H6 SATA 256GB                      | 1         | 1      | 1.39%   |
| Intel SSDSCKJF180A5H RSED 180GB                     | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 20.83%  |
| HGST                | 9         | 10     | 12.5%   |
| Hitachi             | 8         | 10     | 11.11%  |
| Intel               | 6         | 7      | 8.33%   |
| Micron Technology   | 5         | 6      | 6.94%   |
| Toshiba             | 4         | 5      | 5.56%   |
| Samsung Electronics | 4         | 4      | 5.56%   |
| WDC                 | 2         | 2      | 2.78%   |
| SK hynix            | 2         | 2      | 2.78%   |
| SanDisk             | 2         | 2      | 2.78%   |
| Crucial             | 2         | 3      | 2.78%   |
| Apple               | 2         | 2      | 2.78%   |
| Union Memory        | 1         | 1      | 1.39%   |
| Transcend           | 1         | 1      | 1.39%   |
| Team                | 1         | 1      | 1.39%   |
| SSSTC               | 1         | 1      | 1.39%   |
| Silicon Motion      | 1         | 1      | 1.39%   |
| OCZ                 | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| Kingston            | 1         | 1      | 1.39%   |
| Corsair             | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| ADATA Technology    | 1         | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 17     | 38.46%  |
| HGST    | 9         | 10     | 23.08%  |
| Hitachi | 8         | 10     | 20.51%  |
| Toshiba | 4         | 5      | 10.26%  |
| WDC     | 2         | 2      | 5.13%   |
| Apple   | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 45     | 54.17%  |
| SSD  | 29        | 32     | 40.28%  |
| NVMe | 4         | 4      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 50%     |
| Hitachi HTS727575A9E364 752GB                                   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 884       | 1322   | 56.85%  |
| Works    | 599       | 779    | 38.52%  |
| Malfunc  | 70        | 81     | 4.5%    |
| Failed   | 2         | 2      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 877       | 51.02%  |
| Samsung Electronics                     | 235       | 13.67%  |
| AMD                                     | 159       | 9.25%   |
| SanDisk                                 | 102       | 5.93%   |
| SK hynix                                | 84        | 4.89%   |
| Toshiba America Info Systems            | 59        | 3.43%   |
| Micron Technology                       | 48        | 2.79%   |
| Kingston Technology Company             | 43        | 2.5%    |
| KIOXIA                                  | 18        | 1.05%   |
| Phison Electronics                      | 17        | 0.99%   |
| Nvidia                                  | 12        | 0.7%    |
| Marvell Technology Group                | 10        | 0.58%   |
| Lenovo                                  | 6         | 0.35%   |
| ADATA Technology                        | 6         | 0.35%   |
| Union Memory (Shenzhen)                 | 5         | 0.29%   |
| Solid State Storage Technology          | 5         | 0.29%   |
| Silicon Motion                          | 5         | 0.29%   |
| Lite-On Technology                      | 5         | 0.29%   |
| Apple                                   | 5         | 0.29%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.23%   |
| Micron/Crucial Technology               | 4         | 0.23%   |
| Realtek Semiconductor                   | 2         | 0.12%   |
| O2 Micro                                | 2         | 0.12%   |
| Yangtze Memory Technologies             | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| Shenzhen Longsys Electronics            | 1         | 0.06%   |
| Seagate Technology                      | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.06%   |
| INNOGRIT                                | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 131       | 7.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 108       | 5.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 101       | 5.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 94        | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 69        | 3.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 67        | 3.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 55        | 3.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 51        | 2.8%    |
| Intel Volume Management Device NVMe RAID Controller                            | 48        | 2.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 46        | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 40        | 2.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 39        | 2.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 37        | 2.03%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 36        | 1.98%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 30        | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 1.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 26        | 1.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 24        | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 1.26%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 22        | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 20        | 1.1%    |
| Intel SSD 660P Series                                                          | 19        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 18        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 18        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 17        | 0.93%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 15        | 0.82%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 15        | 0.82%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 14        | 0.77%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 14        | 0.77%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 13        | 0.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 0.71%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 12        | 0.66%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 12        | 0.66%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 11        | 0.6%    |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 11        | 0.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 0.6%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 10        | 0.55%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 10        | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 10        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 873       | 49.8%   |
| NVMe | 657       | 37.48%  |
| RAID | 130       | 7.42%   |
| IDE  | 93        | 5.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1166      | 79%     |
| AMD     | 307       | 20.8%   |
| Unknown | 2         | 0.14%   |
| ARM     | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 32        | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 32        | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 23        | 1.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 21        | 1.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 20        | 1.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 19        | 1.29%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 16        | 1.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 1.02%   |
| AMD Custom APU 0405                     | 15        | 1.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 14        | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 14        | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 13        | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 13        | 0.88%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 13        | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 12        | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 12        | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 12        | 0.81%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 12        | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 11        | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 10        | 0.68%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 10        | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.68%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 10        | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 10        | 0.68%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 9         | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 9         | 0.61%   |
| Intel 12th Gen Core i7-12700H           | 9         | 0.61%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 9         | 0.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 9         | 0.61%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 9         | 0.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 8         | 0.54%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 8         | 0.54%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 8         | 0.54%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 8         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 377       | 25.54%  |
| Intel Core i5                  | 356       | 24.12%  |
| Other                          | 198       | 13.41%  |
| AMD Ryzen 7                    | 81        | 5.49%   |
| Intel Core i3                  | 70        | 4.74%   |
| AMD Ryzen 5                    | 56        | 3.79%   |
| Intel Core 2 Duo               | 51        | 3.46%   |
| Intel Celeron                  | 51        | 3.46%   |
| AMD Ryzen 9                    | 19        | 1.29%   |
| AMD A8                         | 18        | 1.22%   |
| Intel Pentium                  | 16        | 1.08%   |
| Intel Atom                     | 15        | 1.02%   |
| AMD Ryzen 3                    | 14        | 0.95%   |
| AMD A6                         | 12        | 0.81%   |
| Intel Genuine                  | 11        | 0.75%   |
| Intel Core 2                   | 11        | 0.75%   |
| AMD Ryzen 7 PRO                | 11        | 0.75%   |
| AMD Ryzen 5 PRO                | 9         | 0.61%   |
| AMD E1                         | 9         | 0.61%   |
| AMD A10                        | 9         | 0.61%   |
| Intel Xeon                     | 7         | 0.47%   |
| Intel Core i9                  | 7         | 0.47%   |
| AMD A4                         | 7         | 0.47%   |
| AMD E                          | 6         | 0.41%   |
| Intel Pentium Silver           | 4         | 0.27%   |
| Intel Pentium M                | 4         | 0.27%   |
| Intel Pentium Dual             | 4         | 0.27%   |
| Intel Core m3                  | 4         | 0.27%   |
| AMD E2                         | 4         | 0.27%   |
| Intel Core                     | 3         | 0.2%    |
| Intel Celeron Dual-Core        | 3         | 0.2%    |
| AMD Turion 64 X2 Mobile        | 3         | 0.2%    |
| Intel Pentium Dual-Core        | 2         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.14%   |
| AMD Sempron                    | 2         | 0.14%   |
| AMD Athlon II Dual-Core        | 2         | 0.14%   |
| AMD Athlon II                  | 2         | 0.14%   |
| AMD Athlon 64 X2               | 2         | 0.14%   |
| Intel Core m7                  | 1         | 0.07%   |
| Intel Core m5                  | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 654       | 44.28%  |
| 4      | 491       | 33.24%  |
| 8      | 131       | 8.87%   |
| 6      | 108       | 7.31%   |
| 14     | 29        | 1.96%   |
| 1      | 22        | 1.49%   |
| 10     | 18        | 1.22%   |
| 12     | 17        | 1.15%   |
| 24     | 4         | 0.27%   |
| 16     | 3         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1476      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1192      | 80.49%  |
| 1      | 289       | 19.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1451      | 98.11%  |
| Unknown        | 16        | 1.08%   |
| 32-bit         | 9         | 0.61%   |
| 64-bit         | 3         | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 607       | 39.57%  |
| 0x306a9    | 64        | 4.17%   |
| 0x206a7    | 53        | 3.46%   |
| 0x40651    | 49        | 3.19%   |
| 0x806c1    | 48        | 3.13%   |
| 0x306d4    | 45        | 2.93%   |
| 0x306c3    | 45        | 2.93%   |
| 0x406e3    | 43        | 2.8%    |
| 0x806ea    | 41        | 2.67%   |
| 0x806ec    | 38        | 2.48%   |
| 0x806e9    | 35        | 2.28%   |
| 0x906ea    | 26        | 1.69%   |
| 0x906e9    | 25        | 1.63%   |
| 0x20655    | 25        | 1.63%   |
| 0x1067a    | 24        | 1.56%   |
| 0x0a50000c | 19        | 1.24%   |
| 0x6fd      | 14        | 0.91%   |
| 0x08600106 | 14        | 0.91%   |
| 0xa0652    | 13        | 0.85%   |
| 0x906a3    | 12        | 0.78%   |
| 0x806eb    | 12        | 0.78%   |
| 0x08108109 | 12        | 0.78%   |
| 0x08608103 | 11        | 0.72%   |
| 0x0700010f | 11        | 0.72%   |
| 0x806d1    | 10        | 0.65%   |
| 0x406c4    | 10        | 0.65%   |
| 0x506e3    | 9         | 0.59%   |
| 0x30678    | 9         | 0.59%   |
| 0x20652    | 8         | 0.52%   |
| 0x08108102 | 8         | 0.52%   |
| 0x0810100b | 8         | 0.52%   |
| 0x05000119 | 8         | 0.52%   |
| 0x706e5    | 7         | 0.46%   |
| 0x6fb      | 7         | 0.46%   |
| 0x6f6      | 7         | 0.46%   |
| 0x0a404102 | 7         | 0.46%   |
| 0x06001119 | 7         | 0.46%   |
| 0x906ed    | 6         | 0.39%   |
| 0x10676    | 6         | 0.39%   |
| 0x0a50000d | 6         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 295       | 19.96%  |
| Haswell           | 134       | 9.07%   |
| Unknown           | 123       | 8.32%   |
| IvyBridge         | 98        | 6.63%   |
| SandyBridge       | 87        | 5.89%   |
| Skylake           | 81        | 5.48%   |
| TigerLake         | 76        | 5.14%   |
| Broadwell         | 58        | 3.92%   |
| Zen 3             | 56        | 3.79%   |
| Alderlake Hybrid  | 46        | 3.11%   |
| Westmere          | 45        | 3.04%   |
| Silvermont        | 42        | 2.84%   |
| Penryn            | 42        | 2.84%   |
| Core              | 42        | 2.84%   |
| Zen 2             | 33        | 2.23%   |
| Zen+              | 26        | 1.76%   |
| CometLake         | 26        | 1.76%   |
| Icelake           | 23        | 1.56%   |
| Excavator         | 17        | 1.15%   |
| Zen               | 15        | 1.01%   |
| Puma              | 14        | 0.95%   |
| Piledriver        | 14        | 0.95%   |
| Jaguar            | 12        | 0.81%   |
| Goldmont plus     | 11        | 0.74%   |
| Bobcat            | 10        | 0.68%   |
| K10               | 8         | 0.54%   |
| K8 Hammer         | 7         | 0.47%   |
| P6                | 6         | 0.41%   |
| K10 Llano         | 6         | 0.41%   |
| Bonnell           | 6         | 0.41%   |
| Nehalem           | 5         | 0.34%   |
| K8 & K10 hybrid   | 5         | 0.34%   |
| Goldmont          | 5         | 0.34%   |
| Steamroller       | 2         | 0.14%   |
| Tremont           | 1         | 0.07%   |
| Meteorlake Hybrid | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1054      | 57.13%  |
| Nvidia                           | 425       | 23.04%  |
| AMD                              | 362       | 19.62%  |
| Silicon Integrated Systems [SiS] | 4         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 84        | 4.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 78        | 4.09%   |
| Intel UHD Graphics 620                                                                   | 72        | 3.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 3.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 68        | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 64        | 3.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 53        | 2.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 51        | 2.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 2.41%   |
| Intel HD Graphics 620                                                                    | 43        | 2.26%   |
| Intel HD Graphics 5500                                                                   | 42        | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 41        | 2.15%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 33        | 1.73%   |
| Intel HD Graphics 630                                                                    | 30        | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 30        | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.31%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 24        | 1.26%   |
| AMD Lucienne                                                                             | 24        | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 1.05%   |
| AMD Rembrandt [Radeon 680M]                                                              | 19        | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 18        | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 18        | 0.94%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 18        | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.79%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 15        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.73%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 13        | 0.68%   |
| AMD Barcelo                                                                              | 12        | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.58%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 11        | 0.58%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 0.52%   |
| Nvidia GM108M [GeForce 840M]                                                             | 10        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 731       | 49.39%  |
| Intel + Nvidia | 283       | 19.12%  |
| 1 x AMD        | 242       | 16.35%  |
| 1 x Nvidia     | 90        | 6.08%   |
| AMD + Nvidia   | 52        | 3.51%   |
| Intel + AMD    | 36        | 2.43%   |
| 2 x AMD        | 32        | 2.16%   |
| 2 x Intel      | 6         | 0.41%   |
| Other          | 4         | 0.27%   |
| 1 x SiS        | 4         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1207      | 80.52%  |
| Proprietary | 240       | 16.01%  |
| Unknown     | 52        | 3.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1027      | 68.1%   |
| 0.01-0.5   | 168       | 11.14%  |
| 1.01-2.0   | 139       | 9.22%   |
| 0.51-1.0   | 68        | 4.51%   |
| 3.01-4.0   | 64        | 4.24%   |
| 7.01-8.0   | 19        | 1.26%   |
| 5.01-6.0   | 17        | 1.13%   |
| 2.01-3.0   | 5         | 0.33%   |
| 8.01-16.0  | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 365       | 21.13%  |
| LG Display              | 218       | 12.62%  |
| Chimei Innolux          | 208       | 12.04%  |
| Samsung Electronics     | 177       | 10.25%  |
| BOE                     | 147       | 8.51%   |
| Sharp                   | 73        | 4.23%   |
| Apple                   | 65        | 3.76%   |
| Dell                    | 56        | 3.24%   |
| Lenovo                  | 40        | 2.32%   |
| Philips                 | 31        | 1.8%    |
| Hewlett-Packard         | 30        | 1.74%   |
| CSO                     | 30        | 1.74%   |
| Chi Mei Optoelectronics | 29        | 1.68%   |
| InfoVision              | 28        | 1.62%   |
| Goldstar                | 20        | 1.16%   |
| PANDA                   | 19        | 1.1%    |
| BenQ                    | 19        | 1.1%    |
| LG Philips              | 18        | 1.04%   |
| ASUSTek Computer        | 17        | 0.98%   |
| AOC                     | 14        | 0.81%   |
| Ancor Communications    | 14        | 0.81%   |
| Acer                    | 14        | 0.81%   |
| Valve                   | 11        | 0.64%   |
| Panasonic               | 7         | 0.41%   |
| Sony                    | 6         | 0.35%   |
| Vestel Elektronik       | 5         | 0.29%   |
| LGD                     | 5         | 0.29%   |
| BOE Technology Group    | 5         | 0.29%   |
| Quanta Display          | 4         | 0.23%   |
| Unknown                 | 3         | 0.17%   |
| Toshiba                 | 3         | 0.17%   |
| MSI                     | 3         | 0.17%   |
| Eizo                    | 3         | 0.17%   |
| Analogix                | 3         | 0.17%   |
| TMX                     | 2         | 0.12%   |
| Positivo                | 2         | 0.12%   |
| Nvidia                  | 2         | 0.12%   |
| Fujitsu Siemens         | 2         | 0.12%   |
| CPT                     | 2         | 0.12%   |
| VOXICON                 | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 18        | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 13        | 0.74%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 13        | 0.74%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 13        | 0.74%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.57%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 9         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 8         | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.46%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 8         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.4%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.4%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 6         | 0.34%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 6         | 0.34%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 6         | 0.34%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 6         | 0.34%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 6         | 0.34%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 5         | 0.28%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 5         | 0.28%   |
| Hewlett-Packard E243i HPN3462 1920x1200 518x324mm 24.1-inch           | 5         | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.28%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.28%   |
| AU Optronics LCD Monitor AUOA48F 1920x1080 309x174mm 14.0-inch        | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 5         | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 5         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 706       | 42.94%  |
| 1366x768 (WXGA)    | 327       | 19.89%  |
| 3840x2160 (4K)     | 98        | 5.96%   |
| 2560x1440 (QHD)    | 77        | 4.68%   |
| 1920x1200 (WUXGA)  | 64        | 3.89%   |
| 1600x900 (HD+)     | 53        | 3.22%   |
| 1280x800 (WXGA)    | 53        | 3.22%   |
| 2560x1600          | 51        | 3.1%    |
| 2880x1800          | 35        | 2.13%   |
| 1440x900 (WXGA+)   | 32        | 1.95%   |
| 3440x1440          | 24        | 1.46%   |
| 3840x2400          | 20        | 1.22%   |
| 1680x1050 (WSXGA+) | 19        | 1.16%   |
| 800x1280           | 14        | 0.85%   |
| 3200x1800 (QHD+)   | 9         | 0.55%   |
| 1024x768 (XGA)     | 6         | 0.36%   |
| 1024x600           | 6         | 0.36%   |
| 3200x2000          | 5         | 0.3%    |
| 1280x1024 (SXGA)   | 5         | 0.3%    |
| Unknown            | 5         | 0.3%    |
| 3840x1080          | 4         | 0.24%   |
| 2160x1440          | 4         | 0.24%   |
| 1920x540           | 4         | 0.24%   |
| 1360x768           | 4         | 0.24%   |
| 2288x1287          | 3         | 0.18%   |
| 2560x1080          | 2         | 0.12%   |
| 1920x1280          | 2         | 0.12%   |
| 1400x1050          | 2         | 0.12%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1100          | 1         | 0.06%   |
| 3456x2160          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2880x1920          | 1         | 0.06%   |
| 2560x1700          | 1         | 0.06%   |
| 2256x1504          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1680x945           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 533       | 30.79%  |
| 13      | 319       | 18.43%  |
| 14      | 248       | 14.33%  |
| 17      | 94        | 5.43%   |
| 27      | 90        | 5.2%    |
| 12      | 77        | 4.45%   |
| 24      | 64        | 3.7%    |
| 16      | 45        | 2.6%    |
| 23      | 32        | 1.85%   |
| 31      | 31        | 1.79%   |
| 11      | 28        | 1.62%   |
| Unknown | 27        | 1.56%   |
| 34      | 21        | 1.21%   |
| 21      | 14        | 0.81%   |
| 7       | 11        | 0.64%   |
| 22      | 10        | 0.58%   |
| 84      | 9         | 0.52%   |
| 18      | 8         | 0.46%   |
| 32      | 7         | 0.4%    |
| 25      | 5         | 0.29%   |
| 19      | 5         | 0.29%   |
| 10      | 5         | 0.29%   |
| 65      | 4         | 0.23%   |
| 54      | 4         | 0.23%   |
| 40      | 3         | 0.17%   |
| 39      | 3         | 0.17%   |
| 35      | 3         | 0.17%   |
| 29      | 3         | 0.17%   |
| 3       | 3         | 0.17%   |
| 142     | 2         | 0.12%   |
| 72      | 2         | 0.12%   |
| 48      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 37      | 2         | 0.12%   |
| 33      | 2         | 0.12%   |
| 26      | 2         | 0.12%   |
| 20      | 2         | 0.12%   |
| 86      | 1         | 0.06%   |
| 85      | 1         | 0.06%   |
| 75      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 946       | 55.32%  |
| 201-300        | 294       | 17.19%  |
| 501-600        | 171       | 10%     |
| 351-400        | 107       | 6.26%   |
| 601-700        | 42        | 2.46%   |
| 401-500        | 35        | 2.05%   |
| 701-800        | 28        | 1.64%   |
| Unknown        | 27        | 1.58%   |
| 1501-2000      | 14        | 0.82%   |
| 1001-1500      | 14        | 0.82%   |
| 1-100          | 14        | 0.82%   |
| 801-900        | 10        | 0.58%   |
| 901-1000       | 5         | 0.29%   |
| More than 2000 | 2         | 0.12%   |
| 101-200        | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1153      | 75.02%  |
| 16/10   | 285       | 18.54%  |
| 21/9    | 28        | 1.82%   |
| Unknown | 23        | 1.5%    |
| 3/2     | 13        | 0.85%   |
| 0.67    | 11        | 0.72%   |
| 4/3     | 7         | 0.46%   |
| 5/4     | 6         | 0.39%   |
| 6/5     | 4         | 0.26%   |
| 32/9    | 3         | 0.2%    |
| 1.00    | 2         | 0.13%   |
| 3.40    | 1         | 0.07%   |
| 0.56    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 526       | 30.46%  |
| 81-90          | 415       | 24.03%  |
| 71-80          | 149       | 8.63%   |
| 301-350        | 91        | 5.27%   |
| 201-250        | 86        | 4.98%   |
| 121-130        | 82        | 4.75%   |
| 61-70          | 73        | 4.23%   |
| 351-500        | 66        | 3.82%   |
| 111-120        | 47        | 2.72%   |
| 251-300        | 36        | 2.08%   |
| 51-60          | 29        | 1.68%   |
| More than 1000 | 27        | 1.56%   |
| Unknown        | 27        | 1.56%   |
| 131-140        | 15        | 0.87%   |
| 1-40           | 14        | 0.81%   |
| 501-1000       | 13        | 0.75%   |
| 151-200        | 10        | 0.58%   |
| 141-150        | 8         | 0.46%   |
| 91-100         | 7         | 0.41%   |
| 41-50          | 6         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 708       | 41.89%  |
| 101-120       | 383       | 22.66%  |
| 51-100        | 234       | 13.85%  |
| 161-240       | 224       | 13.25%  |
| More than 240 | 92        | 5.44%   |
| Unknown       | 27        | 1.6%    |
| 1-50          | 22        | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1176      | 77.98%  |
| 2     | 259       | 17.18%  |
| 3     | 35        | 2.32%   |
| 0     | 34        | 2.25%   |
| 4     | 3         | 0.2%    |
| 5     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 869       | 38.2%   |
| Realtek Semiconductor                  | 608       | 26.73%  |
| Qualcomm Atheros                       | 242       | 10.64%  |
| Broadcom                               | 150       | 6.59%   |
| MediaTek                               | 77        | 3.38%   |
| Broadcom Limited                       | 50        | 2.2%    |
| ASIX Electronics                       | 26        | 1.14%   |
| Hewlett-Packard                        | 23        | 1.01%   |
| Marvell Technology Group               | 19        | 0.84%   |
| Sierra Wireless                        | 17        | 0.75%   |
| Ralink                                 | 16        | 0.7%    |
| Lenovo                                 | 15        | 0.66%   |
| Dell                                   | 15        | 0.66%   |
| ASUSTek Computer                       | 11        | 0.48%   |
| TP-Link                                | 10        | 0.44%   |
| Qualcomm                               | 10        | 0.44%   |
| Ericsson Business Mobile Networks      | 10        | 0.44%   |
| DisplayLink                            | 10        | 0.44%   |
| Nvidia                                 | 9         | 0.4%    |
| Fibocom                                | 8         | 0.35%   |
| Samsung Electronics                    | 7         | 0.31%   |
| Ralink Technology                      | 7         | 0.31%   |
| Huawei Technologies                    | 6         | 0.26%   |
| D-Link                                 | 5         | 0.22%   |
| Xiaomi                                 | 4         | 0.18%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.18%   |
| NetGear                                | 4         | 0.18%   |
| Linksys                                | 3         | 0.13%   |
| Google                                 | 3         | 0.13%   |
| Texas Instruments                      | 2         | 0.09%   |
| STMicroelectronics                     | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.09%   |
| Qualcomm Atheros Communications        | 2         | 0.09%   |
| Microsoft                              | 2         | 0.09%   |
| JMicron Technology                     | 2         | 0.09%   |
| ICS Advent                             | 2         | 0.09%   |
| Arduino SA                             | 2         | 0.09%   |
| ZyXEL Communications                   | 1         | 0.04%   |
| Wacom                                  | 1         | 0.04%   |
| U-Blox                                 | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 354       | 12.46%  |
| Intel Wireless 8265 / 8275                                             | 109       | 3.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 91        | 3.2%    |
| Intel Wi-Fi 6 AX200                                                    | 68        | 2.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 66        | 2.32%   |
| Intel Wireless 7260                                                    | 64        | 2.25%   |
| Intel Wireless 8260                                                    | 59        | 2.08%   |
| Intel Wi-Fi 6 AX201                                                    | 58        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 58        | 2.04%   |
| Intel Wireless 7265                                                    | 52        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 40        | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 39        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 39        | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 36        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 35        | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 34        | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 32        | 1.13%   |
| Intel Ethernet Connection (4) I219-V                                   | 32        | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                                  | 31        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 30        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 30        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 30        | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 28        | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                                  | 27        | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 25        | 0.88%   |
| Intel Ethernet Connection I219-LM                                      | 25        | 0.88%   |
| Intel Ethernet Connection I218-LM                                      | 25        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                          | 23        | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 22        | 0.77%   |
| Intel Ethernet Connection I219-V                                       | 21        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 21        | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 20        | 0.7%    |
| Intel Raptor Lake PCH CNVi WiFi                                        | 20        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 20        | 0.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                        | 20        | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 19        | 0.67%   |
| Intel Wireless 3160                                                    | 19        | 0.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 19        | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 19        | 0.67%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 832       | 54.17%  |
| Qualcomm Atheros                | 206       | 13.41%  |
| Realtek Semiconductor           | 174       | 11.33%  |
| Broadcom                        | 113       | 7.36%   |
| MediaTek                        | 63        | 4.1%    |
| Broadcom Limited                | 35        | 2.28%   |
| Sierra Wireless                 | 17        | 1.11%   |
| Ralink                          | 16        | 1.04%   |
| ASUSTek Computer                | 11        | 0.72%   |
| Qualcomm                        | 9         | 0.59%   |
| TP-Link                         | 8         | 0.52%   |
| Fibocom                         | 8         | 0.52%   |
| Dell                            | 8         | 0.52%   |
| Ralink Technology               | 7         | 0.46%   |
| Hewlett-Packard                 | 6         | 0.39%   |
| NetGear                         | 4         | 0.26%   |
| D-Link                          | 4         | 0.26%   |
| Qualcomm Atheros Communications | 2         | 0.13%   |
| Linksys                         | 2         | 0.13%   |
| ZyXEL Communications            | 1         | 0.07%   |
| Wacom                           | 1         | 0.07%   |
| Qcom                            | 1         | 0.07%   |
| Microsoft                       | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| IMC Networks                    | 1         | 0.07%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| Chu Yuen Enterprise             | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 109       | 7.06%   |
| Intel Wi-Fi 6 AX200                                                  | 68        | 4.4%    |
| Intel Wireless 7260                                                  | 64        | 4.15%   |
| Intel Wireless 8260                                                  | 59        | 3.82%   |
| Intel Wi-Fi 6 AX201                                                  | 58        | 3.76%   |
| Intel Wireless 7265                                                  | 52        | 3.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 40        | 2.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 39        | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 39        | 2.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 35        | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 35        | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 34        | 2.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 32        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 30        | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 30        | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 30        | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 28        | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 22        | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 21        | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 20        | 1.3%    |
| Intel Raptor Lake PCH CNVi WiFi                                      | 20        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 20        | 1.3%    |
| Broadcom BCM43228 802.11a/b/g/n                                      | 20        | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 19        | 1.23%   |
| Intel Wireless 3160                                                  | 19        | 1.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 19        | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 19        | 1.23%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 17        | 1.1%    |
| Intel Centrino Advanced-N 6200                                       | 16        | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 15        | 0.97%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 15        | 0.97%   |
| Intel Centrino Ultimate-N 6300                                       | 15        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 15        | 0.97%   |
| Intel Centrino Advanced-N 6235                                       | 14        | 0.91%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                    | 12        | 0.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 12        | 0.78%   |
| Sierra Wireless EM7455                                               | 11        | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 11        | 0.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 11        | 0.71%   |
| Intel Centrino Wireless-N 2230                                       | 11        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 533       | 43.26%  |
| Intel                                  | 405       | 32.87%  |
| Qualcomm Atheros                       | 75        | 6.09%   |
| Broadcom                               | 65        | 5.28%   |
| ASIX Electronics                       | 26        | 2.11%   |
| Marvell Technology Group               | 19        | 1.54%   |
| Broadcom Limited                       | 16        | 1.3%    |
| Lenovo                                 | 15        | 1.22%   |
| MediaTek                               | 14        | 1.14%   |
| DisplayLink                            | 10        | 0.81%   |
| Nvidia                                 | 9         | 0.73%   |
| Hewlett-Packard                        | 9         | 0.73%   |
| Samsung Electronics                    | 6         | 0.49%   |
| Huawei Technologies                    | 5         | 0.41%   |
| Xiaomi                                 | 4         | 0.32%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.24%   |
| Google                                 | 3         | 0.24%   |
| TP-Link                                | 2         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.16%   |
| JMicron Technology                     | 2         | 0.16%   |
| ICS Advent                             | 2         | 0.16%   |
| Qualcomm                               | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.08%   |
| Microsoft                              | 1         | 0.08%   |
| Linksys                                | 1         | 0.08%   |
| Gemtek                                 | 1         | 0.08%   |
| D-Link                                 | 1         | 0.08%   |
| Apple                                  | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 354       | 28.37%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 91        | 7.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 66        | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 58        | 4.65%   |
| Intel Ethernet Connection (4) I219-V                                   | 32        | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 31        | 2.48%   |
| Intel Ethernet Connection (3) I218-LM                                  | 27        | 2.16%   |
| Intel Ethernet Connection I219-LM                                      | 25        | 2%      |
| Intel Ethernet Connection I218-LM                                      | 25        | 2%      |
| ASIX AX88179 Gigabit Ethernet                                          | 23        | 1.84%   |
| Intel Ethernet Connection I219-V                                       | 21        | 1.68%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 1.52%   |
| Intel Ethernet Connection I217-LM                                      | 17        | 1.36%   |
| Intel Ethernet Connection (6) I219-V                                   | 17        | 1.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 17        | 1.36%   |
| Intel Ethernet Connection (13) I219-V                                  | 16        | 1.28%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 14        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13        | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 12        | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 12        | 0.96%   |
| Intel Ethernet Connection I217-V                                       | 10        | 0.8%    |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                      | 9         | 0.72%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                               | 8         | 0.64%   |
| Intel 82566MM Gigabit Network Connection                               | 8         | 0.64%   |
| HP HP lt4120 Snapdragon X5 LTE                                         | 8         | 0.64%   |
| Intel Ethernet Connection (14) I219-LM                                 | 7         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.48%   |
| Realtek Killer E2600 GbE Controller                                    | 6         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 6         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 6         | 0.48%   |
| Lenovo Thinkpad LAN                                                    | 6         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.48%   |
| DisplayLink Dell Universal Dock D6000                                  | 6         | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 6         | 0.48%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 6         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1441      | 54.21%  |
| Ethernet | 1169      | 43.98%  |
| Modem    | 44        | 1.66%   |
| Unknown  | 4         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1181      | 75.22%  |
| Ethernet | 388       | 24.71%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1003      | 67.82%  |
| 1     | 453       | 30.63%  |
| 3     | 13        | 0.88%   |
| 0     | 10        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1364      | 91.18%  |
| Yes  | 132       | 8.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 662       | 52.67%  |
| Realtek Semiconductor           | 102       | 8.11%   |
| IMC Networks                    | 85        | 6.76%   |
| Foxconn / Hon Hai               | 73        | 5.81%   |
| Qualcomm Atheros Communications | 72        | 5.73%   |
| Broadcom                        | 61        | 4.85%   |
| Apple                           | 58        | 4.61%   |
| Lite-On Technology              | 41        | 3.26%   |
| Hewlett-Packard                 | 23        | 1.83%   |
| Dell                            | 19        | 1.51%   |
| ASUSTek Computer                | 11        | 0.88%   |
| Cambridge Silicon Radio         | 9         | 0.72%   |
| Ralink                          | 8         | 0.64%   |
| Toshiba                         | 7         | 0.56%   |
| MediaTek                        | 7         | 0.56%   |
| USI                             | 3         | 0.24%   |
| Realtek                         | 3         | 0.24%   |
| Alps Electric                   | 3         | 0.24%   |
| Taiyo Yuden                     | 2         | 0.16%   |
| Ralink Technology               | 2         | 0.16%   |
| Chicony Electronics             | 2         | 0.16%   |
| TP-Link                         | 1         | 0.08%   |
| Fujitsu                         | 1         | 0.08%   |
| Foxconn International           | 1         | 0.08%   |
| Creative Technology             | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 293       | 23.2%   |
| Intel AX201 Bluetooth                               | 114       | 9.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 70        | 5.54%   |
| Realtek Bluetooth Radio                             | 68        | 5.38%   |
| Intel AX200 Bluetooth                               | 67        | 5.3%    |
| Intel AX211 Bluetooth                               | 50        | 3.96%   |
| Apple Bluetooth Host Controller                     | 34        | 2.69%   |
| IMC Networks Bluetooth Radio                        | 31        | 2.45%   |
| IMC Networks Wireless_Device                        | 29        | 2.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 1.98%   |
| Foxconn / Hon Hai Bluetooth Device                  | 25        | 1.98%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 1.66%   |
| Apple Bluetooth USB Host Controller                 | 20        | 1.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 1.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 1.27%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.19%   |
| Intel AX210 Bluetooth                               | 15        | 1.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                    | 12        | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.95%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.95%   |
| Lite-On Bluetooth Device                            | 11        | 0.87%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.87%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.87%   |
| IMC Networks Bluetooth Device                       | 10        | 0.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 0.71%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 0.63%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 8         | 0.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 6         | 0.48%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 0.48%   |
| Lite-On Wireless_Device                             | 5         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1143      | 61.32%  |
| AMD                              | 330       | 17.7%   |
| Nvidia                           | 241       | 12.93%  |
| C-Media Electronics              | 19        | 1.02%   |
| Logitech                         | 13        | 0.7%    |
| GN Netcom                        | 13        | 0.7%    |
| Realtek Semiconductor            | 12        | 0.64%   |
| Lenovo                           | 9         | 0.48%   |
| Hewlett-Packard                  | 9         | 0.48%   |
| Plantronics                      | 6         | 0.32%   |
| Kingston Technology              | 6         | 0.32%   |
| ASUSTek Computer                 | 5         | 0.27%   |
| Apple                            | 5         | 0.27%   |
| Texas Instruments                | 4         | 0.21%   |
| SteelSeries ApS                  | 4         | 0.21%   |
| Silicon Integrated Systems [SiS] | 4         | 0.21%   |
| SAVITECH                         | 3         | 0.16%   |
| RODE Microphones                 | 3         | 0.16%   |
| DSEA A/S                         | 3         | 0.16%   |
| JMTek                            | 2         | 0.11%   |
| Creative Technology              | 2         | 0.11%   |
| Corsair                          | 2         | 0.11%   |
| XMOS                             | 1         | 0.05%   |
| Unknown                          | 1         | 0.05%   |
| Sony                             | 1         | 0.05%   |
| SlrTek                           | 1         | 0.05%   |
| Samson Technologies              | 1         | 0.05%   |
| Razer USA                        | 1         | 0.05%   |
| QinHeng Electronics              | 1         | 0.05%   |
| PreSonus Audio Electronics       | 1         | 0.05%   |
| No brand                         | 1         | 0.05%   |
| Line6                            | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| JBL                              | 1         | 0.05%   |
| Huawei Technologies              | 1         | 0.05%   |
| GYROCOM C&C                      | 1         | 0.05%   |
| Generalplus Technology           | 1         | 0.05%   |
| Focusrite-Novation               | 1         | 0.05%   |
| FiiO Electronics Technology      | 1         | 0.05%   |
| Elite Silicon                    | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 190       | 8.28%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 190       | 8.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 105       | 4.58%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 98        | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 79        | 3.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 76        | 3.31%   |
| Intel Haswell-ULT HD Audio Controller                                      | 70        | 3.05%   |
| Intel 8 Series HD Audio Controller                                         | 70        | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 62        | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 60        | 2.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 58        | 2.53%   |
| Intel Broadwell-U Audio Controller                                         | 58        | 2.53%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 52        | 2.27%   |
| AMD FCH Azalia Controller                                                  | 52        | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 51        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 50        | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 1.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 43        | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 37        | 1.61%   |
| Intel CM238 HD Audio Controller                                            | 35        | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 34        | 1.48%   |
| AMD Kabini HDMI/DP Audio                                                   | 34        | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 28        | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 27        | 1.18%   |
| Intel Comet Lake PCH cAVS                                                  | 24        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 24        | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                              | 21        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 21        | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 20        | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20        | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 19        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19        | 0.83%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 19        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 17        | 0.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17        | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 15        | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 14        | 0.61%   |
| AMD Trinity HDMI Audio Controller                                          | 14        | 0.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 292       | 31.6%   |
| SK hynix            | 216       | 23.38%  |
| Micron Technology   | 154       | 16.67%  |
| Kingston            | 63        | 6.82%   |
| Unknown             | 57        | 6.17%   |
| Crucial             | 27        | 2.92%   |
| Corsair             | 25        | 2.71%   |
| Elpida              | 17        | 1.84%   |
| Ramaxel Technology  | 16        | 1.73%   |
| A-DATA Technology   | 16        | 1.73%   |
| Unknown             | 10        | 1.08%   |
| Nanya Technology    | 5         | 0.54%   |
| G.Skill             | 5         | 0.54%   |
| Patriot             | 3         | 0.32%   |
| Unknown (ABCD)      | 2         | 0.22%   |
| Team                | 2         | 0.22%   |
| GSkill              | 2         | 0.22%   |
| Unknown (83DA)      | 1         | 0.11%   |
| TEXTORM             | 1         | 0.11%   |
| Qimonda             | 1         | 0.11%   |
| Netlist             | 1         | 0.11%   |
| Neo Forza           | 1         | 0.11%   |
| GOODRAM             | 1         | 0.11%   |
| fef5                | 1         | 0.11%   |
| Avant               | 1         | 0.11%   |
| ASint Technology    | 1         | 0.11%   |
| Apacer              | 1         | 0.11%   |
| 8CB900000080        | 1         | 0.11%   |
| 48spaces            | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 18        | 1.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 13        | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 12        | 1.22%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 12        | 1.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 12        | 1.22%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 11        | 1.12%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 11        | 1.12%   |
| Unknown                                                       | 10        | 1.02%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                  | 9         | 0.92%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s      | 9         | 0.92%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s        | 8         | 0.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 8         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 8         | 0.81%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 8         | 0.81%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 0.81%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 7         | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s          | 7         | 0.71%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s           | 6         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 6         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 0.61%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 6         | 0.61%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                  | 6         | 0.61%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 6         | 0.61%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s   | 6         | 0.61%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                 | 5         | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 5         | 0.51%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s        | 5         | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 5         | 0.51%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 5         | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                  | 5         | 0.51%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 5         | 0.51%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 5         | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 5         | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 5         | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 5         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 5         | 0.51%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 5         | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s          | 5         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 353       | 43.53%  |
| DDR3    | 251       | 30.95%  |
| LPDDR4  | 53        | 6.54%   |
| LPDDR3  | 40        | 4.93%   |
| LPDDR5  | 39        | 4.81%   |
| DDR5    | 31        | 3.82%   |
| DDR2    | 23        | 2.84%   |
| SDRAM   | 10        | 1.23%   |
| DRAM    | 4         | 0.49%   |
| DDR     | 4         | 0.49%   |
| Unknown | 3         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 680       | 83.44%  |
| Row Of Chips | 119       | 14.6%   |
| Chip         | 10        | 1.23%   |
| Unknown      | 4         | 0.49%   |
| DIMM         | 2         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 355       | 40.02%  |
| 4096  | 209       | 23.56%  |
| 16384 | 190       | 21.42%  |
| 2048  | 93        | 10.48%  |
| 32768 | 22        | 2.48%   |
| 1024  | 15        | 1.69%   |
| 512   | 3         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 176       | 20.37%  |
| 3200    | 162       | 18.75%  |
| 2667    | 144       | 16.67%  |
| 2133    | 58        | 6.71%   |
| 2400    | 53        | 6.13%   |
| 1334    | 39        | 4.51%   |
| 4267    | 34        | 3.94%   |
| 6400    | 25        | 2.89%   |
| 1333    | 23        | 2.66%   |
| 4800    | 18        | 2.08%   |
| 667     | 16        | 1.85%   |
| Unknown | 16        | 1.85%   |
| 1867    | 14        | 1.62%   |
| 5600    | 12        | 1.39%   |
| 7500    | 11        | 1.27%   |
| 4266    | 11        | 1.27%   |
| 1067    | 11        | 1.27%   |
| 3266    | 8         | 0.93%   |
| 800     | 6         | 0.69%   |
| 4199    | 5         | 0.58%   |
| 8400    | 3         | 0.35%   |
| 5500    | 2         | 0.23%   |
| 3733    | 2         | 0.23%   |
| 2048    | 2         | 0.23%   |
| 1066    | 2         | 0.23%   |
| 975     | 2         | 0.23%   |
| 533     | 2         | 0.23%   |
| 333     | 2         | 0.23%   |
| 7467    | 1         | 0.12%   |
| 7400    | 1         | 0.12%   |
| 5200    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |
| 266     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 55.56%  |
| Samsung Electronics | 2         | 22.22%  |
| Oki Data            | 1         | 11.11%  |
| Brother Industries  | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Notebooks | Percent |
|------------------------------|-----------|---------|
| HP ENVY 4520 series          | 2         | 22.22%  |
| Samsung SCX-3200 Series      | 1         | 11.11%  |
| Samsung M2070 Series         | 1         | 11.11%  |
| Oki Data USB Device          | 1         | 11.11%  |
| HP HP LaserJet P2035         | 1         | 11.11%  |
| HP DeskJet 5650c             | 1         | 11.11%  |
| HP DeskJet 2700 series       | 1         | 11.11%  |
| Brother QL-500 label printer | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 25%     |
| HP ScanJet 2200c                            | 1         | 25%     |
| Canon CanoScan LiDE 100                     | 1         | 25%     |
| Canon CanoScan 4400F                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 340       | 26.4%   |
| IMC Networks                           | 124       | 9.63%   |
| Microdia                               | 108       | 8.39%   |
| Bison Electronics                      | 94        | 7.3%    |
| Realtek Semiconductor                  | 93        | 7.22%   |
| Sunplus Innovation Technology          | 61        | 4.74%   |
| Cheng Uei Precision Industry (Foxlink) | 59        | 4.58%   |
| Quanta                                 | 53        | 4.11%   |
| Lite-On Technology                     | 53        | 4.11%   |
| Apple                                  | 47        | 3.65%   |
| Suyin                                  | 34        | 2.64%   |
| Syntek                                 | 33        | 2.56%   |
| Luxvisions Innotech Limited            | 28        | 2.17%   |
| Logitech                               | 26        | 2.02%   |
| Acer                                   | 25        | 1.94%   |
| Ricoh                                  | 13        | 1.01%   |
| Sonix Technology                       | 11        | 0.85%   |
| Lenovo                                 | 11        | 0.85%   |
| Alcor Micro                            | 9         | 0.7%    |
| ShineTech                              | 8         | 0.62%   |
| Samsung Electronics                    | 8         | 0.62%   |
| Silicon Motion                         | 7         | 0.54%   |
| ALi                                    | 6         | 0.47%   |
| DigiTech                               | 4         | 0.31%   |
| SunplusIT                              | 3         | 0.23%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.23%   |
| Primax Electronics                     | 3         | 0.23%   |
| Microsoft                              | 3         | 0.23%   |
| Importek                               | 3         | 0.23%   |
| Z-Star Microelectronics                | 2         | 0.16%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Polycom                                | 2         | 0.16%   |
| Creative Technology                    | 2         | 0.16%   |
| LG Electronics                         | 1         | 0.08%   |
| kingcome                               | 1         | 0.08%   |
| Intel                                  | 1         | 0.08%   |
| Generalplus Technology                 | 1         | 0.08%   |
| Etron Technology                       | 1         | 0.08%   |
| Elgato Systems                         | 1         | 0.08%   |
| DX-230705-A                            | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 89        | 6.86%   |
| Microdia Integrated_Webcam_HD                                            | 52        | 4.01%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 49        | 3.78%   |
| IMC Networks Integrated Camera                                           | 40        | 3.08%   |
| Realtek Integrated_Webcam_HD                                             | 34        | 2.62%   |
| Chicony HP HD Camera                                                     | 28        | 2.16%   |
| Bison Integrated Camera                                                  | 28        | 2.16%   |
| Syntek Integrated Camera                                                 | 24        | 1.85%   |
| Chicony HD WebCam                                                        | 23        | 1.77%   |
| Lite-On HP HD Camera                                                     | 18        | 1.39%   |
| Quanta HP HD Camera                                                      | 16        | 1.23%   |
| Lite-On Integrated Camera                                                | 16        | 1.23%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                       | 16        | 1.23%   |
| Sunplus Integrated_Webcam_HD                                             | 14        | 1.08%   |
| Sunplus HD WebCam                                                        | 13        | 1%      |
| Lite-On HP HD Webcam                                                     | 13        | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 13        | 1%      |
| Bison SunplusIT Integrated Camera                                        | 13        | 1%      |
| Quanta HD User Facing                                                    | 12        | 0.93%   |
| Chicony HP HD Webcam [Fixed]                                             | 11        | 0.85%   |
| Bison Lenovo EasyCamera                                                  | 11        | 0.85%   |
| Apple FaceTime HD Camera                                                 | 11        | 0.85%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 10        | 0.77%   |
| Chicony USB2.0 HD UVC WebCam                                             | 10        | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 10        | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 10        | 0.77%   |
| Sonix USB2.0 HD UVC WebCam                                               | 9         | 0.69%   |
| Quanta HP TrueVision HD Camera                                           | 9         | 0.69%   |
| Luxvisions Innotech Limited Integrated Camera                            | 9         | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 9         | 0.69%   |
| Chicony HP Truevision HD                                                 | 9         | 0.69%   |
| Chicony HP HD Webcam                                                     | 9         | 0.69%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 8         | 0.62%   |
| Realtek USB2.0 HD UVC WebCam                                             | 8         | 0.62%   |
| Chicony Integrated HP HD Webcam                                          | 8         | 0.62%   |
| Chicony Integrated Camera (1280x720@30)                                  | 8         | 0.62%   |
| Bison HD Webcam                                                          | 8         | 0.62%   |
| Apple Built-in iSight                                                    | 8         | 0.62%   |
| Acer Lenovo EasyCamera                                                   | 8         | 0.62%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 147       | 42.24%  |
| Synaptics                  | 111       | 31.9%   |
| Shenzhen Goodix Technology | 28        | 8.05%   |
| Elan Microelectronics      | 20        | 5.75%   |
| Upek                       | 15        | 4.31%   |
| AuthenTec                  | 12        | 3.45%   |
| LighTuning Technology      | 9         | 2.59%   |
| STMicroelectronics         | 6         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 54        | 15.52%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 7.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 7.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 5.75%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 4.89%   |
| Validity Sensors VFS491                                                    | 13        | 3.74%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 3.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 3.74%   |
| Synaptics Prometheus Fingerprint Reader                                    | 10        | 2.87%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 2.87%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.87%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.59%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 2.3%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.01%   |
| Elan ELAN:ARM-M4                                                           | 7         | 2.01%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 1.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.72%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.72%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.72%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.44%   |
| AuthenTec AES2810                                                          | 5         | 1.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.86%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.86%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.86%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 0.86%   |
| Unknown                                                                    | 3         | 0.86%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.57%   |
| Synaptics WBDI                                                             | 2         | 0.57%   |
| Synaptics  WBDI                                                            | 2         | 0.57%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.57%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.29%   |
| Synaptics WBDI Device                                                      | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Alcor Micro         | 91        | 46.19%  |
| Broadcom            | 75        | 38.07%  |
| O2 Micro            | 14        | 7.11%   |
| Lenovo              | 7         | 3.55%   |
| Upek                | 6         | 3.05%   |
| Yubico.com          | 3         | 1.52%   |
| Chicony Electronics | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 91        | 46.19%  |
| Broadcom 58200                                                               | 26        | 13.2%   |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 10.66%  |
| Broadcom 5880                                                                | 14        | 7.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 6.6%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 5.58%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.05%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.52%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.51%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 799       | 52.74%  |
| 1     | 532       | 35.12%  |
| 2     | 163       | 10.76%  |
| 3     | 16        | 1.06%   |
| 4     | 3         | 0.2%    |
| 7     | 1         | 0.07%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 347       | 38.43%  |
| Chipcard                 | 175       | 19.38%  |
| Graphics card            | 125       | 13.84%  |
| Net/wireless             | 78        | 8.64%   |
| Multimedia controller    | 67        | 7.42%   |
| Camera                   | 33        | 3.65%   |
| Bluetooth                | 23        | 2.55%   |
| Communication controller | 19        | 2.1%    |
| Storage                  | 10        | 1.11%   |
| Sound                    | 7         | 0.78%   |
| Card reader              | 7         | 0.78%   |
| Net/ethernet             | 5         | 0.55%   |
| Modem                    | 2         | 0.22%   |
| Flash memory             | 2         | 0.22%   |
| Storage/nvme             | 1         | 0.11%   |
| Storage/ide              | 1         | 0.11%   |
| Storage/ata              | 1         | 0.11%   |

