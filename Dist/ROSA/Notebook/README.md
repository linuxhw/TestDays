ROSA - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for ROSA.

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

Total: 19503

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MS-N0E1 Ver                 | [9c4dcef9c6](https://linux-hardware.org/?probe=9c4dcef9c6) | Feb 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [de3138b686](https://linux-hardware.org/?probe=de3138b686) | Feb 01, 2023 |
| Acer          | Nitro AN515-52              | [86156a3b50](https://linux-hardware.org/?probe=86156a3b50) | Jan 31, 2023 |
| ASUSTek       | 1011PX                      | [204706229b](https://linux-hardware.org/?probe=204706229b) | Jan 31, 2023 |
| MSI           | GL75 Leopard 10SCSR         | [8e30762127](https://linux-hardware.org/?probe=8e30762127) | Jan 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | [d826805d37](https://linux-hardware.org/?probe=d826805d37) | Jan 30, 2023 |
| Lenovo        | Z50-70 20354                | [54f6c27c09](https://linux-hardware.org/?probe=54f6c27c09) | Jan 30, 2023 |
| HP            | Pavilion g6                 | [d25ed40cf3](https://linux-hardware.org/?probe=d25ed40cf3) | Jan 30, 2023 |
| ASUSTek       | 1011PX                      | [7359bcfbfb](https://linux-hardware.org/?probe=7359bcfbfb) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | [c8c73a9f67](https://linux-hardware.org/?probe=c8c73a9f67) | Jan 29, 2023 |
| Unknown       | Unknown                     | [23d04579d4](https://linux-hardware.org/?probe=23d04579d4) | Jan 29, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [93e0f40842](https://linux-hardware.org/?probe=93e0f40842) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | [2fb747792d](https://linux-hardware.org/?probe=2fb747792d) | Jan 29, 2023 |
| ASUSTek       | X550MJ                      | [51fd1f6c24](https://linux-hardware.org/?probe=51fd1f6c24) | Jan 28, 2023 |
| ASUSTek       | N56DP                       | [a746d3fd78](https://linux-hardware.org/?probe=a746d3fd78) | Jan 27, 2023 |
| ASUSTek       | N56VJ                       | [6ad6470149](https://linux-hardware.org/?probe=6ad6470149) | Jan 27, 2023 |
| Acer          | Aspire 5532                 | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [acbaa4516c](https://linux-hardware.org/?probe=acbaa4516c) | Jan 27, 2023 |
| Clevo         | M770SUA                     | [3a19bae169](https://linux-hardware.org/?probe=3a19bae169) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ecd1e46811](https://linux-hardware.org/?probe=ecd1e46811) | Jan 27, 2023 |
| Lenovo        | G480 20156                  | [9e09139dbc](https://linux-hardware.org/?probe=9e09139dbc) | Jan 26, 2023 |
| ASUSTek       | 1201N                       | [ddc52a086f](https://linux-hardware.org/?probe=ddc52a086f) | Jan 26, 2023 |
| Notebook      | P15SM-A/SM1-A               | [7f70263934](https://linux-hardware.org/?probe=7f70263934) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | [02dffce8d7](https://linux-hardware.org/?probe=02dffce8d7) | Jan 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6290f61a46](https://linux-hardware.org/?probe=6290f61a46) | Jan 26, 2023 |
| Acer          | Nitro AN517-51              | [8c568dd8e5](https://linux-hardware.org/?probe=8c568dd8e5) | Jan 26, 2023 |
| Infinix       | INBOOK X2 GEN11             | [ee7b9f5fd0](https://linux-hardware.org/?probe=ee7b9f5fd0) | Jan 26, 2023 |
| HP            | EliteBook 840 G4            | [ee6e7a2924](https://linux-hardware.org/?probe=ee6e7a2924) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | [fe11977488](https://linux-hardware.org/?probe=fe11977488) | Jan 25, 2023 |
| HP            | Laptop 15-bw0xx             | [c2867457c2](https://linux-hardware.org/?probe=c2867457c2) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | [d56d0b1732](https://linux-hardware.org/?probe=d56d0b1732) | Jan 25, 2023 |
| Acer          | Extensa 2540                | [af5b1ea485](https://linux-hardware.org/?probe=af5b1ea485) | Jan 25, 2023 |
| HP            | Laptop 15-db0xxx            | [a9dace6356](https://linux-hardware.org/?probe=a9dace6356) | Jan 24, 2023 |
| Acer          | Aspire 5742G                | [e7afbd79e9](https://linux-hardware.org/?probe=e7afbd79e9) | Jan 24, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | [3b1ce8fc77](https://linux-hardware.org/?probe=3b1ce8fc77) | Jan 24, 2023 |
| Alienware     | 18                          | [982870ed1f](https://linux-hardware.org/?probe=982870ed1f) | Jan 24, 2023 |
| Alienware     | 18                          | [afe83f1946](https://linux-hardware.org/?probe=afe83f1946) | Jan 24, 2023 |
| Acer          | Extensa 5630                | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| Lenovo        | IdeaPad S510p 20298         | [18fdd7a490](https://linux-hardware.org/?probe=18fdd7a490) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [37f26b2f10](https://linux-hardware.org/?probe=37f26b2f10) | Jan 23, 2023 |
| Samsung       | NC10                        | [6bd13301d9](https://linux-hardware.org/?probe=6bd13301d9) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [b1ced07f7b](https://linux-hardware.org/?probe=b1ced07f7b) | Jan 22, 2023 |
| HP            | ProBook 5330m               | [989327864b](https://linux-hardware.org/?probe=989327864b) | Jan 22, 2023 |
| ASUSTek       | N56VJ                       | [167dae47d7](https://linux-hardware.org/?probe=167dae47d7) | Jan 22, 2023 |
| MSI           | CR500                       | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Dell          | Vostro 3460                 | [569626e023](https://linux-hardware.org/?probe=569626e023) | Jan 22, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d63d494c6](https://linux-hardware.org/?probe=7d63d494c6) | Jan 21, 2023 |
| Samsung       | RV408/RV508                 | [0d5c4881c1](https://linux-hardware.org/?probe=0d5c4881c1) | Jan 21, 2023 |
| Toshiba       | Satellite P200              | [cdc37dfe5e](https://linux-hardware.org/?probe=cdc37dfe5e) | Jan 20, 2023 |
| Sony          | VGN-FJ3SR_B                 | [4dc8b8d09d](https://linux-hardware.org/?probe=4dc8b8d09d) | Jan 20, 2023 |
| Lenovo        | B450                        | [96b87672bf](https://linux-hardware.org/?probe=96b87672bf) | Jan 20, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [459b2e28d0](https://linux-hardware.org/?probe=459b2e28d0) | Jan 20, 2023 |
| Acer          | Nitro AN515-52              | [9abd51692e](https://linux-hardware.org/?probe=9abd51692e) | Jan 20, 2023 |
| Lenovo        | G70-80 80FF                 | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Acer          | Aspire E5-573G              | [cfe663eeb9](https://linux-hardware.org/?probe=cfe663eeb9) | Jan 19, 2023 |
| Chuwi         | HeroBook Pro                | [42bf8b9a0d](https://linux-hardware.org/?probe=42bf8b9a0d) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [82eea2cc7b](https://linux-hardware.org/?probe=82eea2cc7b) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | [02a6db2951](https://linux-hardware.org/?probe=02a6db2951) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | [a9de8742d5](https://linux-hardware.org/?probe=a9de8742d5) | Jan 17, 2023 |
| HP            | Notebook                    | [a998060574](https://linux-hardware.org/?probe=a998060574) | Jan 17, 2023 |
| Lenovo        | Flex 2-14 20404             | [bdfe91e3c9](https://linux-hardware.org/?probe=bdfe91e3c9) | Jan 17, 2023 |
| Acer          | Nitro AN515-52              | [4507d2f32d](https://linux-hardware.org/?probe=4507d2f32d) | Jan 17, 2023 |
| Lenovo        | G500 20236                  | [37891c1ea9](https://linux-hardware.org/?probe=37891c1ea9) | Jan 16, 2023 |
| HP            | Laptop 15-db0xxx            | [363f8daa52](https://linux-hardware.org/?probe=363f8daa52) | Jan 16, 2023 |
| Unknown       | Unknown                     | [84f591bd6b](https://linux-hardware.org/?probe=84f591bd6b) | Jan 16, 2023 |
| HP            | Notebook                    | [219540f0f7](https://linux-hardware.org/?probe=219540f0f7) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2ec1685227](https://linux-hardware.org/?probe=2ec1685227) | Jan 15, 2023 |
| Lenovo        | IdeaPad Z580                | [f51c90cadc](https://linux-hardware.org/?probe=f51c90cadc) | Jan 15, 2023 |
| Acer          | Aspire V3-772G              | [832efe11f1](https://linux-hardware.org/?probe=832efe11f1) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bf4ea0ba42](https://linux-hardware.org/?probe=bf4ea0ba42) | Jan 15, 2023 |
| Kraftway      | ACCORD                      | [63039ae17f](https://linux-hardware.org/?probe=63039ae17f) | Jan 15, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [b5b29198b0](https://linux-hardware.org/?probe=b5b29198b0) | Jan 15, 2023 |
| ASUSTek       | G75VW                       | [adc92101d7](https://linux-hardware.org/?probe=adc92101d7) | Jan 15, 2023 |
| Irbis         | NB264                       | [ed534a1d30](https://linux-hardware.org/?probe=ed534a1d30) | Jan 15, 2023 |
| HP            | 15                          | [6df03629da](https://linux-hardware.org/?probe=6df03629da) | Jan 15, 2023 |
| Toshiba       | Satellite L300              | [282e0e478f](https://linux-hardware.org/?probe=282e0e478f) | Jan 15, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [17487f7b28](https://linux-hardware.org/?probe=17487f7b28) | Jan 14, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [fd3560384c](https://linux-hardware.org/?probe=fd3560384c) | Jan 14, 2023 |
| Dell          | Inspiron 15-3552            | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Mini 110-3700               | [564cb84405](https://linux-hardware.org/?probe=564cb84405) | Jan 14, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [a02f812ef3](https://linux-hardware.org/?probe=a02f812ef3) | Jan 14, 2023 |
| Fujitsu       | LIFEBOOK A530               | [64e3a1d972](https://linux-hardware.org/?probe=64e3a1d972) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | [853b489238](https://linux-hardware.org/?probe=853b489238) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | [e806b368b7](https://linux-hardware.org/?probe=e806b368b7) | Jan 14, 2023 |
| HP            | Notebook                    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| HP            | Laptop 14s-dq3xxx           | [19be6bae3d](https://linux-hardware.org/?probe=19be6bae3d) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [9ebcc90bcf](https://linux-hardware.org/?probe=9ebcc90bcf) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [71f6d9b711](https://linux-hardware.org/?probe=71f6d9b711) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c551a35ec7](https://linux-hardware.org/?probe=c551a35ec7) | Jan 12, 2023 |
| Acer          | Aspire ES1-331              | [970c4e185f](https://linux-hardware.org/?probe=970c4e185f) | Jan 12, 2023 |
| Acer          | Aspire A315-41G             | [2bfe8a0134](https://linux-hardware.org/?probe=2bfe8a0134) | Jan 12, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [5c4331e8b9](https://linux-hardware.org/?probe=5c4331e8b9) | Jan 11, 2023 |
| Clevo         | E512xQ/E4129                | [6c78caccf5](https://linux-hardware.org/?probe=6c78caccf5) | Jan 11, 2023 |
| Acer          | Aspire ES1-512              | [9d614553aa](https://linux-hardware.org/?probe=9d614553aa) | Jan 11, 2023 |
| MSI           | GP60 2OD                    | [dbd191a73b](https://linux-hardware.org/?probe=dbd191a73b) | Jan 11, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [8d567b585a](https://linux-hardware.org/?probe=8d567b585a) | Jan 10, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [c4de77365a](https://linux-hardware.org/?probe=c4de77365a) | Jan 10, 2023 |
| Positivo B... | VJFE52F11X-B0611H           | [91caa09e7b](https://linux-hardware.org/?probe=91caa09e7b) | Jan 10, 2023 |
| Acer          | Aspire 5733Z                | [87c8f3902d](https://linux-hardware.org/?probe=87c8f3902d) | Jan 10, 2023 |
| Samsung       | RV420/RV520/RV720           | [c0697ead47](https://linux-hardware.org/?probe=c0697ead47) | Jan 09, 2023 |
| ASUSTek       | K54L                        | [88b71478e6](https://linux-hardware.org/?probe=88b71478e6) | Jan 09, 2023 |
| ASUSTek       | K61IC                       | [c593968311](https://linux-hardware.org/?probe=c593968311) | Jan 09, 2023 |
| MSI           | GV72 8RD                    | [5fa5d4ef58](https://linux-hardware.org/?probe=5fa5d4ef58) | Jan 09, 2023 |
| Acer          | TravelMate P278-M           | [6b2be0a8cc](https://linux-hardware.org/?probe=6b2be0a8cc) | Jan 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [71bd754745](https://linux-hardware.org/?probe=71bd754745) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [505cec778a](https://linux-hardware.org/?probe=505cec778a) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9924742c7d](https://linux-hardware.org/?probe=9924742c7d) | Jan 08, 2023 |
| Dell          | Latitude 5490               | [8fd07b1457](https://linux-hardware.org/?probe=8fd07b1457) | Jan 08, 2023 |
| ASUSTek       | 1003HAG                     | [0b411dbd38](https://linux-hardware.org/?probe=0b411dbd38) | Jan 08, 2023 |
| Lenovo        | B590 20208                  | [e082e7aece](https://linux-hardware.org/?probe=e082e7aece) | Jan 07, 2023 |
| ASUSTek       | 1003HAG                     | [eb8e81a088](https://linux-hardware.org/?probe=eb8e81a088) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [57ec88a87b](https://linux-hardware.org/?probe=57ec88a87b) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7f2254139c](https://linux-hardware.org/?probe=7f2254139c) | Jan 07, 2023 |
| HP            | Compaq 515                  | [6cc60c3d13](https://linux-hardware.org/?probe=6cc60c3d13) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | [1b36fc58ae](https://linux-hardware.org/?probe=1b36fc58ae) | Jan 05, 2023 |
| Chuwi         | CoreBook X                  | [bf8c10bdca](https://linux-hardware.org/?probe=bf8c10bdca) | Jan 05, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [729add189b](https://linux-hardware.org/?probe=729add189b) | Jan 05, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c2df57a53f](https://linux-hardware.org/?probe=c2df57a53f) | Jan 05, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [5be962cfea](https://linux-hardware.org/?probe=5be962cfea) | Jan 05, 2023 |
| HP            | ProBook 640 G1              | [e3fd4121a2](https://linux-hardware.org/?probe=e3fd4121a2) | Jan 04, 2023 |
| HUAWEI        | BOM-WXX9                    | [f4631a1285](https://linux-hardware.org/?probe=f4631a1285) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| Acer          | Swift SF114-32              | [50315135d2](https://linux-hardware.org/?probe=50315135d2) | Jan 04, 2023 |
| Dell          | Inspiron 1525               | [c3c074f183](https://linux-hardware.org/?probe=c3c074f183) | Jan 03, 2023 |
| Acer          | Aspire 5738                 | [aa99474aec](https://linux-hardware.org/?probe=aa99474aec) | Jan 03, 2023 |
| Gigabyte      | G5 KD                       | [b86543e8cf](https://linux-hardware.org/?probe=b86543e8cf) | Jan 03, 2023 |
| ASUSTek       | N551JM                      | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Dell          | Precision M6400             | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Acer          | Aspire 5349                 | [b482fc96ea](https://linux-hardware.org/?probe=b482fc96ea) | Jan 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [63a14c970b](https://linux-hardware.org/?probe=63a14c970b) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8eef31a350](https://linux-hardware.org/?probe=8eef31a350) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4842e4b3e5](https://linux-hardware.org/?probe=4842e4b3e5) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a959b07b66](https://linux-hardware.org/?probe=a959b07b66) | Jan 02, 2023 |
| Lenovo        | G500 20236                  | [75f2e6fae1](https://linux-hardware.org/?probe=75f2e6fae1) | Dec 31, 2022 |
| Lenovo        | G500 20236                  | [0d3ed20685](https://linux-hardware.org/?probe=0d3ed20685) | Dec 31, 2022 |
| Lenovo        | G780 20138                  | [896aeb4e20](https://linux-hardware.org/?probe=896aeb4e20) | Dec 31, 2022 |
| Dell          | Inspiron 15-3552            | [e8b804ddd5](https://linux-hardware.org/?probe=e8b804ddd5) | Dec 31, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [14b589709d](https://linux-hardware.org/?probe=14b589709d) | Dec 31, 2022 |
| HP            | Pavilion g6                 | [6f29ccd86e](https://linux-hardware.org/?probe=6f29ccd86e) | Dec 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5710b93654](https://linux-hardware.org/?probe=5710b93654) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2d63537d23](https://linux-hardware.org/?probe=2d63537d23) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [41da11b027](https://linux-hardware.org/?probe=41da11b027) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [954fdfcd25](https://linux-hardware.org/?probe=954fdfcd25) | Dec 30, 2022 |
| Prestigio     | PSB141C04CGH                | [591f91b689](https://linux-hardware.org/?probe=591f91b689) | Dec 29, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [83acd419e0](https://linux-hardware.org/?probe=83acd419e0) | Dec 29, 2022 |
| ASUSTek       | K40IN                       | [1b4a2d0604](https://linux-hardware.org/?probe=1b4a2d0604) | Dec 29, 2022 |
| Aquarius      | NS685U R11                  | [d99ae12a0c](https://linux-hardware.org/?probe=d99ae12a0c) | Dec 29, 2022 |
| Lenovo        | V14-IIL 82C4                | [221e9b9fd6](https://linux-hardware.org/?probe=221e9b9fd6) | Dec 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e36e85614e](https://linux-hardware.org/?probe=e36e85614e) | Dec 28, 2022 |
| Toshiba       | Satellite U300              | [88861461c8](https://linux-hardware.org/?probe=88861461c8) | Dec 27, 2022 |
| HP            | Compaq Presario CQ50        | [802e160a5a](https://linux-hardware.org/?probe=802e160a5a) | Dec 27, 2022 |
| Lenovo        | V14-IIL 82C4                | [2b7f53c989](https://linux-hardware.org/?probe=2b7f53c989) | Dec 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [155c738d10](https://linux-hardware.org/?probe=155c738d10) | Dec 27, 2022 |
| Dell          | Inspiron N4050              | [542b5ae2f6](https://linux-hardware.org/?probe=542b5ae2f6) | Dec 27, 2022 |
| HP            | Compaq Mini CQ10-100        | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| Gigabyte      | i1520N                      | [4f94938d1b](https://linux-hardware.org/?probe=4f94938d1b) | Dec 27, 2022 |
| MSI           | Modern 14 B4MW              | [17bd139f0c](https://linux-hardware.org/?probe=17bd139f0c) | Dec 26, 2022 |
| ASUSTek       | N56VZ                       | [1ba62f0fab](https://linux-hardware.org/?probe=1ba62f0fab) | Dec 26, 2022 |
| Dell          | G5 5590                     | [43fbc3b36d](https://linux-hardware.org/?probe=43fbc3b36d) | Dec 26, 2022 |
| Acer          | Acadia V1.45                | [2d98a8cef2](https://linux-hardware.org/?probe=2d98a8cef2) | Dec 25, 2022 |
| Unknown       | Unknown                     | [8f4d031a78](https://linux-hardware.org/?probe=8f4d031a78) | Dec 25, 2022 |
| Pegatron      | C15B                        | [f838b3f22c](https://linux-hardware.org/?probe=f838b3f22c) | Dec 25, 2022 |
| Acer          | Nitro AN515-52              | [1571f74238](https://linux-hardware.org/?probe=1571f74238) | Dec 25, 2022 |
| ASUSTek       | X551CAP                     | [3442037418](https://linux-hardware.org/?probe=3442037418) | Dec 25, 2022 |
| Intel         | ChiefRiver                  | [a23ea2e43e](https://linux-hardware.org/?probe=a23ea2e43e) | Dec 23, 2022 |
| Acer          | Aspire A315-51              | [b53beddded](https://linux-hardware.org/?probe=b53beddded) | Dec 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [672c320794](https://linux-hardware.org/?probe=672c320794) | Dec 22, 2022 |
| HP            | G62                         | [00b47da7dc](https://linux-hardware.org/?probe=00b47da7dc) | Dec 22, 2022 |
| Lenovo        | G700 20251                  | [1a8f388366](https://linux-hardware.org/?probe=1a8f388366) | Dec 22, 2022 |
| Toshiba       | Satellite A300              | [8981102ebe](https://linux-hardware.org/?probe=8981102ebe) | Dec 22, 2022 |
| Acer          | Aspire A315-51              | [4fc8630d91](https://linux-hardware.org/?probe=4fc8630d91) | Dec 22, 2022 |
| HP            | ProBook 440 G6              | [ad317dc4fd](https://linux-hardware.org/?probe=ad317dc4fd) | Dec 22, 2022 |
| Lenovo        | G700 20251                  | [afac6a5bfa](https://linux-hardware.org/?probe=afac6a5bfa) | Dec 21, 2022 |
| MSI           | Alpha 15 B5EEK              | [d6e55e247a](https://linux-hardware.org/?probe=d6e55e247a) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cc485cc076](https://linux-hardware.org/?probe=cc485cc076) | Dec 21, 2022 |
| eMachines     | E525                        | [8368666118](https://linux-hardware.org/?probe=8368666118) | Dec 21, 2022 |
| ASUSTek       | X555SJ                      | [c580c82fe2](https://linux-hardware.org/?probe=c580c82fe2) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | [ba8b12c87e](https://linux-hardware.org/?probe=ba8b12c87e) | Dec 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c56023ff15](https://linux-hardware.org/?probe=c56023ff15) | Dec 21, 2022 |
| Pegatron      | A17                         | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| Acer          | Aspire A315-51              | [8777d682b0](https://linux-hardware.org/?probe=8777d682b0) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | [faf7ad4c29](https://linux-hardware.org/?probe=faf7ad4c29) | Dec 19, 2022 |
| MSI           | X460/X460DX                 | [6fff37a8a5](https://linux-hardware.org/?probe=6fff37a8a5) | Dec 18, 2022 |
| MSI           | X460/X460DX                 | [71ca32ac12](https://linux-hardware.org/?probe=71ca32ac12) | Dec 18, 2022 |
| MSI           | Delta 15 A5EFK              | [c793cb6f38](https://linux-hardware.org/?probe=c793cb6f38) | Dec 18, 2022 |
| Acer          | Nitro AN515-56              | [cac9892365](https://linux-hardware.org/?probe=cac9892365) | Dec 18, 2022 |
| eMachines     | E525                        | [2a0aeb50bf](https://linux-hardware.org/?probe=2a0aeb50bf) | Dec 18, 2022 |
| Acer          | AO533                       | [1639951fe5](https://linux-hardware.org/?probe=1639951fe5) | Dec 18, 2022 |
| ASUSTek       | 1201N                       | [214a7002b9](https://linux-hardware.org/?probe=214a7002b9) | Dec 18, 2022 |
| Dell          | Inspiron 15-3552            | [0dc1961e62](https://linux-hardware.org/?probe=0dc1961e62) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [6a1a042504](https://linux-hardware.org/?probe=6a1a042504) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [465a08d81a](https://linux-hardware.org/?probe=465a08d81a) | Dec 18, 2022 |
| Lenovo        | G580 20157                  | [c6cce8ff6d](https://linux-hardware.org/?probe=c6cce8ff6d) | Dec 18, 2022 |
| Dell          | Inspiron 1525               | [216bedab36](https://linux-hardware.org/?probe=216bedab36) | Dec 18, 2022 |
| Prestigio     | PSB141C04CGH                | [60f02a4cb4](https://linux-hardware.org/?probe=60f02a4cb4) | Dec 17, 2022 |
| ICL           | RAYbook Si1511              | [9994b3ec08](https://linux-hardware.org/?probe=9994b3ec08) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [c04b0805ad](https://linux-hardware.org/?probe=c04b0805ad) | Dec 17, 2022 |
| Acer          | Aspire ES1-521              | [4f4f04579a](https://linux-hardware.org/?probe=4f4f04579a) | Dec 17, 2022 |
| Maibenben     | MaiBook M                   | [a216b90cac](https://linux-hardware.org/?probe=a216b90cac) | Dec 17, 2022 |
| 3Logic Gro... | Graviton N15i               | [9d85f624db](https://linux-hardware.org/?probe=9d85f624db) | Dec 16, 2022 |
| Acer          | Aspire A315-51              | [116b321e68](https://linux-hardware.org/?probe=116b321e68) | Dec 16, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [a04f7471b9](https://linux-hardware.org/?probe=a04f7471b9) | Dec 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [66d31fc2c8](https://linux-hardware.org/?probe=66d31fc2c8) | Dec 16, 2022 |
| Acer          | Aspire A315-51              | [5f2e420614](https://linux-hardware.org/?probe=5f2e420614) | Dec 15, 2022 |
| Digma         | EVE 11 C421Y ES1067EW       | [458afe13df](https://linux-hardware.org/?probe=458afe13df) | Dec 14, 2022 |
| Apple         | MacBookPro5,4               | [902c809015](https://linux-hardware.org/?probe=902c809015) | Dec 14, 2022 |
| ASUSTek       | F7Z                         | [3c42714822](https://linux-hardware.org/?probe=3c42714822) | Dec 14, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7040d4353c](https://linux-hardware.org/?probe=7040d4353c) | Dec 14, 2022 |
| ASUSTek       | N73SV                       | [7b729a3a7c](https://linux-hardware.org/?probe=7b729a3a7c) | Dec 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [1457c2669d](https://linux-hardware.org/?probe=1457c2669d) | Dec 13, 2022 |
| Acer          | Aspire 5720                 | [5940b07034](https://linux-hardware.org/?probe=5940b07034) | Dec 13, 2022 |
| ASUSTek       | N73SV                       | [c696bac1dd](https://linux-hardware.org/?probe=c696bac1dd) | Dec 13, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b479704ea5](https://linux-hardware.org/?probe=b479704ea5) | Dec 13, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d01e578aa0](https://linux-hardware.org/?probe=d01e578aa0) | Dec 13, 2022 |
| Sony          | VPCEJ1L1R                   | [25ab3e0119](https://linux-hardware.org/?probe=25ab3e0119) | Dec 13, 2022 |
| MSI           | GF65 Thin 10UE              | [ff4ab808c0](https://linux-hardware.org/?probe=ff4ab808c0) | Dec 13, 2022 |
| Clevo         | M7x0K                       | [08ce94ab11](https://linux-hardware.org/?probe=08ce94ab11) | Dec 13, 2022 |
| Lenovo        | V14-IIL 82C4                | [8c4853dba7](https://linux-hardware.org/?probe=8c4853dba7) | Dec 12, 2022 |
| Sony          | SVE1111M1RW                 | [bc29721da9](https://linux-hardware.org/?probe=bc29721da9) | Dec 12, 2022 |
| Acer          | Aspire 5740                 | [5b35ba45a3](https://linux-hardware.org/?probe=5b35ba45a3) | Dec 12, 2022 |
| Acer          | Aspire A315-42G             | [1d93c8b401](https://linux-hardware.org/?probe=1d93c8b401) | Dec 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [f803c32eae](https://linux-hardware.org/?probe=f803c32eae) | Dec 11, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c90a3cb8c2](https://linux-hardware.org/?probe=c90a3cb8c2) | Dec 11, 2022 |
| ASUSTek       | UL30A                       | [f24e02511f](https://linux-hardware.org/?probe=f24e02511f) | Dec 11, 2022 |
| Lenovo        | G700 20251                  | [0400a58c53](https://linux-hardware.org/?probe=0400a58c53) | Dec 11, 2022 |
| Samsung       | SQ45/Q70C/P200              | [4a96589cf5](https://linux-hardware.org/?probe=4a96589cf5) | Dec 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bb4615bd96](https://linux-hardware.org/?probe=bb4615bd96) | Dec 10, 2022 |
| Samsung       | RC530/RC730                 | [4b7783525a](https://linux-hardware.org/?probe=4b7783525a) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa13871cf9](https://linux-hardware.org/?probe=fa13871cf9) | Dec 10, 2022 |
| MSI           | Modern 15 B12M              | [b5f43a3075](https://linux-hardware.org/?probe=b5f43a3075) | Dec 09, 2022 |
| ASUSTek       | UX310UQK                    | [c4a573e93c](https://linux-hardware.org/?probe=c4a573e93c) | Dec 08, 2022 |
| Acer          | Aspire F5-571G              | [dedd56f0fe](https://linux-hardware.org/?probe=dedd56f0fe) | Dec 08, 2022 |
| Lenovo        | B590 20206                  | [969ca94bb7](https://linux-hardware.org/?probe=969ca94bb7) | Dec 08, 2022 |
| ASUSTek       | K42F                        | [ee90271b2d](https://linux-hardware.org/?probe=ee90271b2d) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | [1b1e1ae174](https://linux-hardware.org/?probe=1b1e1ae174) | Dec 08, 2022 |
| Dell          | Inspiron 3721               | [3bfc5892fe](https://linux-hardware.org/?probe=3bfc5892fe) | Dec 08, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c6d0984a2c](https://linux-hardware.org/?probe=c6d0984a2c) | Dec 08, 2022 |
| ASUSTek       | U24E                        | [e8bdc6be97](https://linux-hardware.org/?probe=e8bdc6be97) | Dec 08, 2022 |
| Acer          | Aspire A114-33              | [0bb6c29bb6](https://linux-hardware.org/?probe=0bb6c29bb6) | Dec 07, 2022 |
| Dell          | Inspiron 3137               | [2f74d45567](https://linux-hardware.org/?probe=2f74d45567) | Dec 07, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fd694a5ddd](https://linux-hardware.org/?probe=fd694a5ddd) | Dec 07, 2022 |
| Pegatron      | C17A                        | [5fc3c61389](https://linux-hardware.org/?probe=5fc3c61389) | Dec 07, 2022 |
| Lenovo        | G700 20251                  | [0613a1c41e](https://linux-hardware.org/?probe=0613a1c41e) | Dec 06, 2022 |
| HP            | Pavilion 15                 | [eb3caff76e](https://linux-hardware.org/?probe=eb3caff76e) | Dec 06, 2022 |
| Acer          | Nitro AN517-51              | [6b5fd6a48c](https://linux-hardware.org/?probe=6b5fd6a48c) | Dec 05, 2022 |
| Apple         | MacBookPro5,4               | [bd98ec1bcb](https://linux-hardware.org/?probe=bd98ec1bcb) | Dec 05, 2022 |
| HONOR         | BOHK-WAX9X                  | [543eb800d7](https://linux-hardware.org/?probe=543eb800d7) | Dec 05, 2022 |
| Acer          | Aspire A315-51              | [26828f578e](https://linux-hardware.org/?probe=26828f578e) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | [44f8fe348a](https://linux-hardware.org/?probe=44f8fe348a) | Dec 05, 2022 |
| Dell          | Vostro 1310                 | [60bdc28f50](https://linux-hardware.org/?probe=60bdc28f50) | Dec 04, 2022 |
| ASUSTek       | F3Sg                        | [f5ae748125](https://linux-hardware.org/?probe=f5ae748125) | Dec 04, 2022 |
| Lenovo        | ThinkPad L420 7854RP1       | [3216e34b2e](https://linux-hardware.org/?probe=3216e34b2e) | Dec 04, 2022 |
| Acer          | Nitro AN515-43              | [f18907cee0](https://linux-hardware.org/?probe=f18907cee0) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [c795306dd2](https://linux-hardware.org/?probe=c795306dd2) | Dec 03, 2022 |
| Dell          | Inspiron 5570               | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [91bffab1ae](https://linux-hardware.org/?probe=91bffab1ae) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [795327c2b7](https://linux-hardware.org/?probe=795327c2b7) | Dec 03, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6cb73d5a1c](https://linux-hardware.org/?probe=6cb73d5a1c) | Dec 03, 2022 |
| MSI           | GE72 6QC                    | [8411668d4d](https://linux-hardware.org/?probe=8411668d4d) | Dec 02, 2022 |
| Acer          | Aspire 5951G                | [0b1e900a8c](https://linux-hardware.org/?probe=0b1e900a8c) | Dec 02, 2022 |
| HP            | 635                         | [cf79165440](https://linux-hardware.org/?probe=cf79165440) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | [638e9873a7](https://linux-hardware.org/?probe=638e9873a7) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | [711acef394](https://linux-hardware.org/?probe=711acef394) | Dec 02, 2022 |
| Samsung       | R410                        | [7c2a18f2cc](https://linux-hardware.org/?probe=7c2a18f2cc) | Dec 01, 2022 |
| Acer          | Aspire V3-571G              | [bbb0c707bb](https://linux-hardware.org/?probe=bbb0c707bb) | Dec 01, 2022 |
| Acer          | Aspire V3-771               | [38dfcb79d5](https://linux-hardware.org/?probe=38dfcb79d5) | Dec 01, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [a8156db955](https://linux-hardware.org/?probe=a8156db955) | Dec 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| Acer          | Aspire 5336                 | [65be105c02](https://linux-hardware.org/?probe=65be105c02) | Dec 01, 2022 |
| Acer          | Aspire 5741G                | [0a336099ba](https://linux-hardware.org/?probe=0a336099ba) | Dec 01, 2022 |
| Lenovo        | B450 1S1680033610187        | [e33670a27b](https://linux-hardware.org/?probe=e33670a27b) | Nov 30, 2022 |
| MSI           | GE72 6QC                    | [ba4847397e](https://linux-hardware.org/?probe=ba4847397e) | Nov 30, 2022 |
| Pegatron      | C15B                        | [defacd8748](https://linux-hardware.org/?probe=defacd8748) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [65c3211b0a](https://linux-hardware.org/?probe=65c3211b0a) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a8dbc14ef](https://linux-hardware.org/?probe=2a8dbc14ef) | Nov 30, 2022 |
| Lenovo        | G500 20236                  | [43815283d9](https://linux-hardware.org/?probe=43815283d9) | Nov 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [b245f9da58](https://linux-hardware.org/?probe=b245f9da58) | Nov 30, 2022 |
| Dell          | Inspiron 3558               | [481755baa3](https://linux-hardware.org/?probe=481755baa3) | Nov 30, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [8a99ec717f](https://linux-hardware.org/?probe=8a99ec717f) | Nov 29, 2022 |
| Lenovo        | G500 20236                  | [6ece9d62e6](https://linux-hardware.org/?probe=6ece9d62e6) | Nov 29, 2022 |
| Lenovo        | G565 20071                  | [659a9a89b9](https://linux-hardware.org/?probe=659a9a89b9) | Nov 28, 2022 |
| Acer          | Aspire ES1-522              | [114c1d0914](https://linux-hardware.org/?probe=114c1d0914) | Nov 28, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [4fbe923ad2](https://linux-hardware.org/?probe=4fbe923ad2) | Nov 28, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [e117f07f42](https://linux-hardware.org/?probe=e117f07f42) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [0c1dece352](https://linux-hardware.org/?probe=0c1dece352) | Nov 28, 2022 |
| Lenovo        | ThinkPad L540 20AVA07BJP    | [cfc9d5c8a2](https://linux-hardware.org/?probe=cfc9d5c8a2) | Nov 27, 2022 |
| Quanta        | JW6H                        | [12c85e1c14](https://linux-hardware.org/?probe=12c85e1c14) | Nov 27, 2022 |
| HP            | Notebook                    | [4ff28b891c](https://linux-hardware.org/?probe=4ff28b891c) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [c5f8f3f82b](https://linux-hardware.org/?probe=c5f8f3f82b) | Nov 26, 2022 |
| Acer          | Aspire 5733Z                | [7fc415db1f](https://linux-hardware.org/?probe=7fc415db1f) | Nov 26, 2022 |
| Sony          | VGN-P31ZRK_G                | [3c0c707fd4](https://linux-hardware.org/?probe=3c0c707fd4) | Nov 26, 2022 |
| HP            | Notebook                    | [6a8992e3ee](https://linux-hardware.org/?probe=6a8992e3ee) | Nov 26, 2022 |
| Acer          | Aspire E1-570G              | [9c2f530d6a](https://linux-hardware.org/?probe=9c2f530d6a) | Nov 25, 2022 |
| Insyde        | CherryTrail                 | [f7728857e6](https://linux-hardware.org/?probe=f7728857e6) | Nov 25, 2022 |
| HP            | Pavilion g7                 | [9b84cb2362](https://linux-hardware.org/?probe=9b84cb2362) | Nov 25, 2022 |
| Acer          | Aspire A315-51              | [e08bf40900](https://linux-hardware.org/?probe=e08bf40900) | Nov 25, 2022 |
| DEPO Compu... | DPC156                      | [9607de1a9c](https://linux-hardware.org/?probe=9607de1a9c) | Nov 25, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [41fc6614f7](https://linux-hardware.org/?probe=41fc6614f7) | Nov 25, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [0bb72a6a2a](https://linux-hardware.org/?probe=0bb72a6a2a) | Nov 25, 2022 |
| MSI           | GE72 6QC                    | [07084dd8f9](https://linux-hardware.org/?probe=07084dd8f9) | Nov 24, 2022 |
| Acer          | Aspire A315-51              | [a636cfb9ff](https://linux-hardware.org/?probe=a636cfb9ff) | Nov 24, 2022 |
| Lenovo        | B590 20208                  | [b1551151f5](https://linux-hardware.org/?probe=b1551151f5) | Nov 24, 2022 |
| Aquarius      | NS685U R11                  | [866e6d043c](https://linux-hardware.org/?probe=866e6d043c) | Nov 24, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [a31935f117](https://linux-hardware.org/?probe=a31935f117) | Nov 24, 2022 |
| HP            | Notebook                    | [f81a524d22](https://linux-hardware.org/?probe=f81a524d22) | Nov 23, 2022 |
| HP            | Pavilion dv6                | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [2485671def](https://linux-hardware.org/?probe=2485671def) | Nov 23, 2022 |
| Toshiba       | Satellite U300              | [f24a55abbf](https://linux-hardware.org/?probe=f24a55abbf) | Nov 23, 2022 |
| MSI           | MS-N051                     | [efb37aedbe](https://linux-hardware.org/?probe=efb37aedbe) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [ab91a099a5](https://linux-hardware.org/?probe=ab91a099a5) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [149f57ad9c](https://linux-hardware.org/?probe=149f57ad9c) | Nov 22, 2022 |
| Acer          | Aspire V3-771               | [c0a3895ac4](https://linux-hardware.org/?probe=c0a3895ac4) | Nov 22, 2022 |
| Notebook      | W65_67SF                    | [91f6aa0bfb](https://linux-hardware.org/?probe=91f6aa0bfb) | Nov 22, 2022 |
| Toshiba       | Satellite L45Dt-B           | [9cdcee20dc](https://linux-hardware.org/?probe=9cdcee20dc) | Nov 22, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [ed6bb8845a](https://linux-hardware.org/?probe=ed6bb8845a) | Nov 21, 2022 |
| Acer          | Extensa 2519                | [1ab63c7353](https://linux-hardware.org/?probe=1ab63c7353) | Nov 21, 2022 |
| Lenovo        | B590 20206                  | [7d8faca25a](https://linux-hardware.org/?probe=7d8faca25a) | Nov 21, 2022 |
| HP            | Notebook                    | [c8bac5b72d](https://linux-hardware.org/?probe=c8bac5b72d) | Nov 20, 2022 |
| Acer          | Extensa 2519                | [fc5526a30f](https://linux-hardware.org/?probe=fc5526a30f) | Nov 20, 2022 |
| Acer          | Extensa 2519                | [5ae619eb32](https://linux-hardware.org/?probe=5ae619eb32) | Nov 20, 2022 |
| Acer          | Extensa 2540                | [2cd32708f2](https://linux-hardware.org/?probe=2cd32708f2) | Nov 20, 2022 |
| HP            | Compaq Presario CQ60        | [3f18cccea5](https://linux-hardware.org/?probe=3f18cccea5) | Nov 20, 2022 |
| HP            | Compaq nx9020 (PG641ES#A... | [ba63296d55](https://linux-hardware.org/?probe=ba63296d55) | Nov 20, 2022 |
| ASUSTek       | X550CC                      | [a2eae9195c](https://linux-hardware.org/?probe=a2eae9195c) | Nov 20, 2022 |
| Lenovo        | G560 20042                  | [e2ea91a4ca](https://linux-hardware.org/?probe=e2ea91a4ca) | Nov 20, 2022 |
| Acer          | Aspire E5-771G              | [5099a55836](https://linux-hardware.org/?probe=5099a55836) | Nov 20, 2022 |
| Pegatron      | A15                         | [dea0a0c81e](https://linux-hardware.org/?probe=dea0a0c81e) | Nov 20, 2022 |
| Acer          | Aspire 5750G                | [8b000b014f](https://linux-hardware.org/?probe=8b000b014f) | Nov 20, 2022 |
| Samsung       | R528/R728                   | [ea586efd66](https://linux-hardware.org/?probe=ea586efd66) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| ASUSTek       | K53SD                       | [7620fe2bdd](https://linux-hardware.org/?probe=7620fe2bdd) | Nov 19, 2022 |
| Dell          | Inspiron 1525               | [3e09380a65](https://linux-hardware.org/?probe=3e09380a65) | Nov 18, 2022 |
| Haier         | U1520HD                     | [7a9c0df4f1](https://linux-hardware.org/?probe=7a9c0df4f1) | Nov 18, 2022 |
| ASUSTek       | X507UA                      | [9a2fe77bac](https://linux-hardware.org/?probe=9a2fe77bac) | Nov 16, 2022 |
| Lenovo        | V14 G2 ALC 82KC             | [cf10680f5f](https://linux-hardware.org/?probe=cf10680f5f) | Nov 15, 2022 |
| Samsung       | NC210/NC110                 | [31ebbfaf58](https://linux-hardware.org/?probe=31ebbfaf58) | Nov 15, 2022 |
| Toshiba       | Satellite A300D             | [c5dc216e31](https://linux-hardware.org/?probe=c5dc216e31) | Nov 15, 2022 |
| Acer          | Aspire ES1-512              | [5802f0db59](https://linux-hardware.org/?probe=5802f0db59) | Nov 15, 2022 |
| HP            | ENVY m6                     | [4397c54e20](https://linux-hardware.org/?probe=4397c54e20) | Nov 14, 2022 |
| ASUSTek       | K42DY                       | [f7a61f85d9](https://linux-hardware.org/?probe=f7a61f85d9) | Nov 14, 2022 |
| ASUSTek       | UX330CAK                    | [bd7d377985](https://linux-hardware.org/?probe=bd7d377985) | Nov 14, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [34a5f361bd](https://linux-hardware.org/?probe=34a5f361bd) | Nov 14, 2022 |
| ASUSTek       | K53SM                       | [297194e8e4](https://linux-hardware.org/?probe=297194e8e4) | Nov 13, 2022 |
| Toshiba       | Satellite P300              | [02285947b8](https://linux-hardware.org/?probe=02285947b8) | Nov 13, 2022 |
| Acer          | Aspire E1-531G              | [9f3c8742f7](https://linux-hardware.org/?probe=9f3c8742f7) | Nov 13, 2022 |
| Sony          | SVE1512H1RW                 | [032fdf5260](https://linux-hardware.org/?probe=032fdf5260) | Nov 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [e8e7b815c4](https://linux-hardware.org/?probe=e8e7b815c4) | Nov 13, 2022 |
| Lenovo        | B590 20208                  | [af898e0d66](https://linux-hardware.org/?probe=af898e0d66) | Nov 13, 2022 |
| Dell          | Inspiron 3521               | [10482f151a](https://linux-hardware.org/?probe=10482f151a) | Nov 12, 2022 |
| Dell          | Inspiron 3521               | [5f20ed2dd2](https://linux-hardware.org/?probe=5f20ed2dd2) | Nov 12, 2022 |
| HP            | Compaq nc6120 (PY507EA#A... | [a4c594d8db](https://linux-hardware.org/?probe=a4c594d8db) | Nov 12, 2022 |
| Acer          | Acadia V1.45                | [c6a91498cc](https://linux-hardware.org/?probe=c6a91498cc) | Nov 12, 2022 |
| Acer          | Swift SF314-43              | [1243c9795a](https://linux-hardware.org/?probe=1243c9795a) | Nov 12, 2022 |
| ASUSTek       | K53BR                       | [15838034f5](https://linux-hardware.org/?probe=15838034f5) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [4838271135](https://linux-hardware.org/?probe=4838271135) | Nov 11, 2022 |
| Acer          | Acadia V1.19                | [f43450e9d4](https://linux-hardware.org/?probe=f43450e9d4) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [cbd9e440a6](https://linux-hardware.org/?probe=cbd9e440a6) | Nov 11, 2022 |
| Acer          | Aspire E5-573               | [b8b0c9fae3](https://linux-hardware.org/?probe=b8b0c9fae3) | Nov 11, 2022 |
| Samsung       | R519/R719                   | [31260d4616](https://linux-hardware.org/?probe=31260d4616) | Nov 11, 2022 |
| Sony          | VPCEH3J1R                   | [4944a2e287](https://linux-hardware.org/?probe=4944a2e287) | Nov 11, 2022 |
| HP            | Pavilion g6                 | [fc422ba1a4](https://linux-hardware.org/?probe=fc422ba1a4) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [f56dc1af6b](https://linux-hardware.org/?probe=f56dc1af6b) | Nov 10, 2022 |
| Acer          | Aspire V5-572G              | [bd537cc78c](https://linux-hardware.org/?probe=bd537cc78c) | Nov 10, 2022 |
| Sony          | VPCS11V9R                   | [a0b4bf7869](https://linux-hardware.org/?probe=a0b4bf7869) | Nov 10, 2022 |
| HP            | Laptop 14s-dq3xxx           | [2da4055f76](https://linux-hardware.org/?probe=2da4055f76) | Nov 09, 2022 |
| Lenovo        | E31-70 80KX                 | [61343c5ca1](https://linux-hardware.org/?probe=61343c5ca1) | Nov 09, 2022 |
| ASUSTek       | X507UB                      | [2790049313](https://linux-hardware.org/?probe=2790049313) | Nov 09, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [97ed2f1140](https://linux-hardware.org/?probe=97ed2f1140) | Nov 09, 2022 |
| MSI           | GE70 2PL                    | [d09e002aa8](https://linux-hardware.org/?probe=d09e002aa8) | Nov 09, 2022 |
| ASUSTek       | X550CC                      | [46dd8a0416](https://linux-hardware.org/?probe=46dd8a0416) | Nov 08, 2022 |
| ASUSTek       | U24E                        | [a51fe3226f](https://linux-hardware.org/?probe=a51fe3226f) | Nov 08, 2022 |
| MSI           | GE70 2PL                    | [8752dacd05](https://linux-hardware.org/?probe=8752dacd05) | Nov 08, 2022 |
| Acer          | Nitro AN517-52              | [3a2bb9e1e9](https://linux-hardware.org/?probe=3a2bb9e1e9) | Nov 08, 2022 |
| Acer          | Aspire E5-573G              | [b6a1f08748](https://linux-hardware.org/?probe=b6a1f08748) | Nov 08, 2022 |
| HP            | Notebook                    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| HP            | EliteBook 2540p             | [515cdf3f6c](https://linux-hardware.org/?probe=515cdf3f6c) | Nov 08, 2022 |
| Toshiba       | Satellite C660              | [5e972fdb95](https://linux-hardware.org/?probe=5e972fdb95) | Nov 07, 2022 |
| HP            | Pavilion g6                 | [9992a08641](https://linux-hardware.org/?probe=9992a08641) | Nov 07, 2022 |
| Acer          | Aspire A315-51              | [d5c179046a](https://linux-hardware.org/?probe=d5c179046a) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | [e75f44efd0](https://linux-hardware.org/?probe=e75f44efd0) | Nov 07, 2022 |
| eMachines     | eM350                       | [ac6dda5ddb](https://linux-hardware.org/?probe=ac6dda5ddb) | Nov 07, 2022 |
| Sony          | VPCZ13S9R                   | [9a0f47ed25](https://linux-hardware.org/?probe=9a0f47ed25) | Nov 07, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [614a486442](https://linux-hardware.org/?probe=614a486442) | Nov 07, 2022 |
| MSI           | GP66 Leopard 11UG           | [0dab96ade2](https://linux-hardware.org/?probe=0dab96ade2) | Nov 06, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [db56889368](https://linux-hardware.org/?probe=db56889368) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [05ac02550e](https://linux-hardware.org/?probe=05ac02550e) | Nov 06, 2022 |
| Samsung       | R510/P510                   | [4921b97206](https://linux-hardware.org/?probe=4921b97206) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [19304dd869](https://linux-hardware.org/?probe=19304dd869) | Nov 06, 2022 |
| Acer          | Aspire A317-52              | [e9ed162010](https://linux-hardware.org/?probe=e9ed162010) | Nov 06, 2022 |
| Toshiba       | Satellite L550              | [3b95d22100](https://linux-hardware.org/?probe=3b95d22100) | Nov 06, 2022 |
| Acer          | Nitro AN515-42              | [a89bc09dca](https://linux-hardware.org/?probe=a89bc09dca) | Nov 05, 2022 |
| Lenovo        | V14-ADA 82C6                | [92be197f2d](https://linux-hardware.org/?probe=92be197f2d) | Nov 05, 2022 |
| ASUSTek       | N76VB                       | [c46794ba60](https://linux-hardware.org/?probe=c46794ba60) | Nov 05, 2022 |
| Fujitsu Si... | AMILO Pro V3205             | [7a03ef6ae1](https://linux-hardware.org/?probe=7a03ef6ae1) | Nov 05, 2022 |
| Dell          | Inspiron N5110              | [698596bd58](https://linux-hardware.org/?probe=698596bd58) | Nov 05, 2022 |
| HP            | Pavilion dv7                | [d17019e1f7](https://linux-hardware.org/?probe=d17019e1f7) | Nov 05, 2022 |
| ASUSTek       | N56VJ                       | [1685737249](https://linux-hardware.org/?probe=1685737249) | Nov 05, 2022 |
| ASUSTek       | F5N                         | [f1efa34bf8](https://linux-hardware.org/?probe=f1efa34bf8) | Nov 04, 2022 |
| ASUSTek       | X75VD                       | [60e91d212e](https://linux-hardware.org/?probe=60e91d212e) | Nov 04, 2022 |
| Lenovo        | B590 20206                  | [6807b6b584](https://linux-hardware.org/?probe=6807b6b584) | Nov 04, 2022 |
| Lenovo        | B590 20206                  | [d0267472d6](https://linux-hardware.org/?probe=d0267472d6) | Nov 04, 2022 |
| Lenovo        | G500 20236                  | [82213a5471](https://linux-hardware.org/?probe=82213a5471) | Nov 04, 2022 |
| ASUSTek       | F5N                         | [8e3878fe4d](https://linux-hardware.org/?probe=8e3878fe4d) | Nov 04, 2022 |
| ASUSTek       | F5N                         | [f95b9890f6](https://linux-hardware.org/?probe=f95b9890f6) | Nov 04, 2022 |
| HUAWEI        | HKD-WXX                     | [7a8f33b5bf](https://linux-hardware.org/?probe=7a8f33b5bf) | Nov 04, 2022 |
| Fujitsu       | LIFEBOOK A512               | [8732711bf0](https://linux-hardware.org/?probe=8732711bf0) | Nov 04, 2022 |
| ASUSTek       | U24E                        | [6303641e69](https://linux-hardware.org/?probe=6303641e69) | Nov 04, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d7c44d9e94](https://linux-hardware.org/?probe=d7c44d9e94) | Nov 04, 2022 |
| Lenovo        | G580 20157                  | [16cd4b28ce](https://linux-hardware.org/?probe=16cd4b28ce) | Nov 04, 2022 |
| ASUSTek       | 1215B                       | [eeff579fe6](https://linux-hardware.org/?probe=eeff579fe6) | Nov 03, 2022 |
| ASUSTek       | K501LB                      | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| ASUSTek       | 1215B                       | [3cc2c5ad48](https://linux-hardware.org/?probe=3cc2c5ad48) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [28d7daff10](https://linux-hardware.org/?probe=28d7daff10) | Nov 02, 2022 |
| Acer          | Nitro AN515-54              | [710ab678b2](https://linux-hardware.org/?probe=710ab678b2) | Nov 02, 2022 |
| Acer          | Aspire A515-54G             | [519fa92199](https://linux-hardware.org/?probe=519fa92199) | Nov 02, 2022 |
| ASUSTek       | 1215B                       | [21694405a9](https://linux-hardware.org/?probe=21694405a9) | Nov 02, 2022 |
| Acer          | Aspire 5750G                | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [6f89789444](https://linux-hardware.org/?probe=6f89789444) | Nov 02, 2022 |
| HP            | Laptop 14s-fq0xxx           | [fe23529093](https://linux-hardware.org/?probe=fe23529093) | Nov 01, 2022 |
| Lenovo        | V14-ADA 82C6                | [a54d6876b6](https://linux-hardware.org/?probe=a54d6876b6) | Nov 01, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [406aae2f66](https://linux-hardware.org/?probe=406aae2f66) | Nov 01, 2022 |
| Apple         | MacBookPro8,1               | [da912b99f4](https://linux-hardware.org/?probe=da912b99f4) | Nov 01, 2022 |
| Acer          | Aspire A315-51              | [eaa9bcaadb](https://linux-hardware.org/?probe=eaa9bcaadb) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | [7b016c85d8](https://linux-hardware.org/?probe=7b016c85d8) | Oct 31, 2022 |
| Acer          | Aspire 5733                 | [bcc1836178](https://linux-hardware.org/?probe=bcc1836178) | Oct 31, 2022 |
| ASUSTek       | K43SJ                       | [778e6caf06](https://linux-hardware.org/?probe=778e6caf06) | Oct 31, 2022 |
| Sony          | VGN-AR71MR                  | [4ecd695b12](https://linux-hardware.org/?probe=4ecd695b12) | Oct 31, 2022 |
| HP            | Laptop 14s-dq3xxx           | [674ced10f2](https://linux-hardware.org/?probe=674ced10f2) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [cb2a07da11](https://linux-hardware.org/?probe=cb2a07da11) | Oct 30, 2022 |
| ASUSTek       | X501A1                      | [037e1402b1](https://linux-hardware.org/?probe=037e1402b1) | Oct 30, 2022 |
| MSI           | Sword 15 A11UE              | [c039d4321b](https://linux-hardware.org/?probe=c039d4321b) | Oct 30, 2022 |
| HP            | Pavilion g6                 | [666a829545](https://linux-hardware.org/?probe=666a829545) | Oct 30, 2022 |
| HIPER         | WORKBOOK                    | [0a3eb12b15](https://linux-hardware.org/?probe=0a3eb12b15) | Oct 30, 2022 |
| Acer          | Nitro AN515-42              | [763e5e0492](https://linux-hardware.org/?probe=763e5e0492) | Oct 29, 2022 |
| ASUSTek       | ZenBook 13 UX310UFR         | [11b52c3e1f](https://linux-hardware.org/?probe=11b52c3e1f) | Oct 29, 2022 |
| ASUSTek       | X550DP                      | [b0a52fe296](https://linux-hardware.org/?probe=b0a52fe296) | Oct 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0a24d1491a](https://linux-hardware.org/?probe=0a24d1491a) | Oct 29, 2022 |
| Lenovo        | B560                        | [f8676b0e49](https://linux-hardware.org/?probe=f8676b0e49) | Oct 28, 2022 |
| ASUSTek       | F3Ka                        | [06235844a1](https://linux-hardware.org/?probe=06235844a1) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [f845ed2866](https://linux-hardware.org/?probe=f845ed2866) | Oct 28, 2022 |
| Dell          | Inspiron 3542               | [a3a24a81fa](https://linux-hardware.org/?probe=a3a24a81fa) | Oct 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [26311f56d7](https://linux-hardware.org/?probe=26311f56d7) | Oct 28, 2022 |
| ASUSTek       | K501LB                      | [25003181f1](https://linux-hardware.org/?probe=25003181f1) | Oct 27, 2022 |
| Acer          | Aspire E5-573G              | [6f926eed65](https://linux-hardware.org/?probe=6f926eed65) | Oct 27, 2022 |
| ASUSTek       | K501LB                      | [2481764903](https://linux-hardware.org/?probe=2481764903) | Oct 27, 2022 |
| HP            | Laptop 14s-fq0xxx           | [377893cdc6](https://linux-hardware.org/?probe=377893cdc6) | Oct 27, 2022 |
| Acer          | Aspire A315-51              | [17faa0d40a](https://linux-hardware.org/?probe=17faa0d40a) | Oct 27, 2022 |
| ASUSTek       | N56VZ                       | [399d92f9e0](https://linux-hardware.org/?probe=399d92f9e0) | Oct 27, 2022 |
| HP            | Compaq 610                  | [5adc7e0aba](https://linux-hardware.org/?probe=5adc7e0aba) | Oct 26, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [9bb0c7d3b0](https://linux-hardware.org/?probe=9bb0c7d3b0) | Oct 26, 2022 |
| Acer          | Nitro AN515-54              | [89180ba46b](https://linux-hardware.org/?probe=89180ba46b) | Oct 26, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [70ea39404e](https://linux-hardware.org/?probe=70ea39404e) | Oct 26, 2022 |
| HP            | EliteBook 840 G4            | [73ee5ace17](https://linux-hardware.org/?probe=73ee5ace17) | Oct 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [8b68d25121](https://linux-hardware.org/?probe=8b68d25121) | Oct 26, 2022 |
| HP            | Laptop 15s-fq2xxx           | [a7a7e4b82c](https://linux-hardware.org/?probe=a7a7e4b82c) | Oct 26, 2022 |
| HP            | Pavilion dv7                | [1b53255010](https://linux-hardware.org/?probe=1b53255010) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [09eec214ae](https://linux-hardware.org/?probe=09eec214ae) | Oct 25, 2022 |
| Acer          | Extensa 5630                | [bdc63e9670](https://linux-hardware.org/?probe=bdc63e9670) | Oct 25, 2022 |
| Toshiba       | Satellite C660              | [b9d0cd845c](https://linux-hardware.org/?probe=b9d0cd845c) | Oct 25, 2022 |
| Toshiba       | Satellite C660              | [36faa336cf](https://linux-hardware.org/?probe=36faa336cf) | Oct 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f426a7b690](https://linux-hardware.org/?probe=f426a7b690) | Oct 24, 2022 |
| MSI           | GE60 2PC                    | [e4378edb2b](https://linux-hardware.org/?probe=e4378edb2b) | Oct 24, 2022 |
| Sony          | SVE1513U1RW                 | [019c35087a](https://linux-hardware.org/?probe=019c35087a) | Oct 24, 2022 |
| MSI           | GE60 2PC                    | [930a153301](https://linux-hardware.org/?probe=930a153301) | Oct 24, 2022 |
| ASUSTek       | N56DY                       | [2d308224ee](https://linux-hardware.org/?probe=2d308224ee) | Oct 23, 2022 |
| ASUSTek       | N56DY                       | [d0caa49d24](https://linux-hardware.org/?probe=d0caa49d24) | Oct 23, 2022 |
| HUAWEI        | NBD-WXX9                    | [c6c2d4cab0](https://linux-hardware.org/?probe=c6c2d4cab0) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [1c355f37b9](https://linux-hardware.org/?probe=1c355f37b9) | Oct 23, 2022 |
| HP            | Compaq 610                  | [9a584886fe](https://linux-hardware.org/?probe=9a584886fe) | Oct 23, 2022 |
| ASUSTek       | W7S                         | [5797f4be95](https://linux-hardware.org/?probe=5797f4be95) | Oct 23, 2022 |
| HP            | Pavilion dv7                | [acaa8b9309](https://linux-hardware.org/?probe=acaa8b9309) | Oct 23, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [e0face3bcb](https://linux-hardware.org/?probe=e0face3bcb) | Oct 22, 2022 |
| HP            | Pavilion dv7                | [ede1ff6d62](https://linux-hardware.org/?probe=ede1ff6d62) | Oct 22, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [eb7a276b51](https://linux-hardware.org/?probe=eb7a276b51) | Oct 22, 2022 |
| Shanghai Z... | ZXE CRB                     | [166b646956](https://linux-hardware.org/?probe=166b646956) | Oct 22, 2022 |
| Acer          | Aspire E1-571G              | [3440b5765d](https://linux-hardware.org/?probe=3440b5765d) | Oct 21, 2022 |
| 3Logic Gro... | APM Graviton                | [0dd152f1d6](https://linux-hardware.org/?probe=0dd152f1d6) | Oct 21, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6c8562fa45](https://linux-hardware.org/?probe=6c8562fa45) | Oct 21, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [123b6fc51a](https://linux-hardware.org/?probe=123b6fc51a) | Oct 21, 2022 |
| Acer          | Aspire A315-51              | [244d93ab06](https://linux-hardware.org/?probe=244d93ab06) | Oct 21, 2022 |
| Acer          | Aspire A315-51              | [dc26121480](https://linux-hardware.org/?probe=dc26121480) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4c95f64c92](https://linux-hardware.org/?probe=4c95f64c92) | Oct 20, 2022 |
| Acer          | Aspire E5-575G              | [66cfe85e96](https://linux-hardware.org/?probe=66cfe85e96) | Oct 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [344040aee1](https://linux-hardware.org/?probe=344040aee1) | Oct 19, 2022 |
| HP            | Pavilion g6                 | [8744b669fe](https://linux-hardware.org/?probe=8744b669fe) | Oct 19, 2022 |
| Pegatron      | A17                         | [14f7d2a90d](https://linux-hardware.org/?probe=14f7d2a90d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d6d2256d26](https://linux-hardware.org/?probe=d6d2256d26) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [3c2bd41b69](https://linux-hardware.org/?probe=3c2bd41b69) | Oct 19, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [71f188e90c](https://linux-hardware.org/?probe=71f188e90c) | Oct 19, 2022 |
| Dell          | Inspiron 15-3567            | [4727244665](https://linux-hardware.org/?probe=4727244665) | Oct 18, 2022 |
| eMachines     | E525                        | [6b500273c6](https://linux-hardware.org/?probe=6b500273c6) | Oct 18, 2022 |
| Lenovo        | G565 20071                  | [52758e9b4b](https://linux-hardware.org/?probe=52758e9b4b) | Oct 18, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [b8a2cca654](https://linux-hardware.org/?probe=b8a2cca654) | Oct 18, 2022 |
| Maibenben     | ZiMai Z5                    | [96d25004be](https://linux-hardware.org/?probe=96d25004be) | Oct 18, 2022 |
| Lenovo        | V310-15IKB 80T3             | [c56ac0436c](https://linux-hardware.org/?probe=c56ac0436c) | Oct 18, 2022 |
| Lenovo        | G480                        | [55e0ad0e82](https://linux-hardware.org/?probe=55e0ad0e82) | Oct 17, 2022 |
| Acer          | Aspire 5740                 | [83bb80a8d4](https://linux-hardware.org/?probe=83bb80a8d4) | Oct 17, 2022 |
| Maibenben     | MaiBook M                   | [ca20ade584](https://linux-hardware.org/?probe=ca20ade584) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [2740d3c96e](https://linux-hardware.org/?probe=2740d3c96e) | Oct 16, 2022 |
| HONOR         | NBR-WAX9                    | [3862d6fc41](https://linux-hardware.org/?probe=3862d6fc41) | Oct 16, 2022 |
| Lenovo        | B580 20144                  | [3de13d5e45](https://linux-hardware.org/?probe=3de13d5e45) | Oct 16, 2022 |
| Samsung       | RV413/RV513                 | [22d5794b5d](https://linux-hardware.org/?probe=22d5794b5d) | Oct 16, 2022 |
| Sony          | SVE1512H1RW                 | [bdc28748b2](https://linux-hardware.org/?probe=bdc28748b2) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [7782926601](https://linux-hardware.org/?probe=7782926601) | Oct 16, 2022 |
| MSI           | Sword 15 A11UE              | [514b1ab74d](https://linux-hardware.org/?probe=514b1ab74d) | Oct 16, 2022 |
| Pegatron      | A15                         | [25bf0fe850](https://linux-hardware.org/?probe=25bf0fe850) | Oct 15, 2022 |
| ASUSTek       | K53TA                       | [8759f9f39c](https://linux-hardware.org/?probe=8759f9f39c) | Oct 15, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [f7b75c7dff](https://linux-hardware.org/?probe=f7b75c7dff) | Oct 14, 2022 |
| Acer          | Aspire E5-511               | [823f951e7a](https://linux-hardware.org/?probe=823f951e7a) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [2356263af1](https://linux-hardware.org/?probe=2356263af1) | Oct 14, 2022 |
| ASUSTek       | K53TA                       | [dd95142fda](https://linux-hardware.org/?probe=dd95142fda) | Oct 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [9f4368b685](https://linux-hardware.org/?probe=9f4368b685) | Oct 14, 2022 |
| eMachines     | E525                        | [a2c8a5cadb](https://linux-hardware.org/?probe=a2c8a5cadb) | Oct 14, 2022 |
| ASUSTek       | K55N                        | [8a7b8b14f3](https://linux-hardware.org/?probe=8a7b8b14f3) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [54d1a0ebb2](https://linux-hardware.org/?probe=54d1a0ebb2) | Oct 13, 2022 |
| Acer          | Aspire E1-571G              | [75b10196e0](https://linux-hardware.org/?probe=75b10196e0) | Oct 13, 2022 |
| Acer          | Aspire 5742G                | [b9da06eb9c](https://linux-hardware.org/?probe=b9da06eb9c) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34481... | [adce18affa](https://linux-hardware.org/?probe=adce18affa) | Oct 13, 2022 |
| Lenovo        | G50-30 80G0                 | [f3bdfee67a](https://linux-hardware.org/?probe=f3bdfee67a) | Oct 13, 2022 |
| HP            | Laptop 15-db0xxx            | [16bb04d1db](https://linux-hardware.org/?probe=16bb04d1db) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7969631063](https://linux-hardware.org/?probe=7969631063) | Oct 11, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDA00... | [7bc7561ab1](https://linux-hardware.org/?probe=7bc7561ab1) | Oct 11, 2022 |
| Lenovo        | G710 20252                  | [d83e7270f9](https://linux-hardware.org/?probe=d83e7270f9) | Oct 11, 2022 |
| Aquarius      | NS685U R11                  | [ce27c5e6f7](https://linux-hardware.org/?probe=ce27c5e6f7) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f5e933eaac](https://linux-hardware.org/?probe=f5e933eaac) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [52c4e232f3](https://linux-hardware.org/?probe=52c4e232f3) | Oct 10, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [efabc0c1ba](https://linux-hardware.org/?probe=efabc0c1ba) | Oct 09, 2022 |
| Unknown       | Unknown                     | [d00832c27c](https://linux-hardware.org/?probe=d00832c27c) | Oct 09, 2022 |
| Dell          | Inspiron 3520               | [12650c819a](https://linux-hardware.org/?probe=12650c819a) | Oct 09, 2022 |
| Lenovo        | G50-70 20351                | [300cc7d78f](https://linux-hardware.org/?probe=300cc7d78f) | Oct 09, 2022 |
| MSI           | GF63 Thin 9RCX              | [b8e1d8da2a](https://linux-hardware.org/?probe=b8e1d8da2a) | Oct 09, 2022 |
| Acer          | Aspire 5742G                | [d7c3182832](https://linux-hardware.org/?probe=d7c3182832) | Oct 08, 2022 |
| MSI           | GF63 Thin 9RCX              | [64bcf40d38](https://linux-hardware.org/?probe=64bcf40d38) | Oct 08, 2022 |
| HP            | Pavilion g6                 | [1c2fd7400d](https://linux-hardware.org/?probe=1c2fd7400d) | Oct 08, 2022 |
| HP            | EliteBook 6930p             | [6f175167b8](https://linux-hardware.org/?probe=6f175167b8) | Oct 08, 2022 |
| HONOR         | NBR-WAX9                    | [2f0c3ba507](https://linux-hardware.org/?probe=2f0c3ba507) | Oct 08, 2022 |
| Acer          | Nitro AN515-54              | [dc5782e5a2](https://linux-hardware.org/?probe=dc5782e5a2) | Oct 08, 2022 |
| Dell          | Vostro 15 7510              | [b9ab199135](https://linux-hardware.org/?probe=b9ab199135) | Oct 07, 2022 |
| Clevo         | W210CUQ                     | [d698b7fe27](https://linux-hardware.org/?probe=d698b7fe27) | Oct 07, 2022 |
| MSI           | CX62 6QD                    | [cf52082ecb](https://linux-hardware.org/?probe=cf52082ecb) | Oct 07, 2022 |
| HP            | ProBook 450 G6              | [646d9b09b3](https://linux-hardware.org/?probe=646d9b09b3) | Oct 07, 2022 |
| HUAWEI        | HLY-WX9XX                   | [af5d214080](https://linux-hardware.org/?probe=af5d214080) | Oct 06, 2022 |
| Sony          | VPCSB1V9R                   | [c19abb47cc](https://linux-hardware.org/?probe=c19abb47cc) | Oct 06, 2022 |
| HP            | Pavilion dv7                | [13e60be2de](https://linux-hardware.org/?probe=13e60be2de) | Oct 06, 2022 |
| Acer          | Extensa 4220                | [10e3973e91](https://linux-hardware.org/?probe=10e3973e91) | Oct 06, 2022 |
| HP            | ProBook 4310s               | [ac57665927](https://linux-hardware.org/?probe=ac57665927) | Oct 06, 2022 |
| HP            | Notebook                    | [49ab3eec39](https://linux-hardware.org/?probe=49ab3eec39) | Oct 06, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [75a7a7f691](https://linux-hardware.org/?probe=75a7a7f691) | Oct 05, 2022 |
| Samsung       | NC110P/NC108P/NC111P        | [33b573e4a1](https://linux-hardware.org/?probe=33b573e4a1) | Oct 04, 2022 |
| ASUSTek       | X101CH                      | [c90b38a699](https://linux-hardware.org/?probe=c90b38a699) | Oct 04, 2022 |
| Clevo         | P150HMx                     | [48c8941ee9](https://linux-hardware.org/?probe=48c8941ee9) | Oct 04, 2022 |
| Lenovo        | Legion Y-540-17IRH-PG0 8... | [3dbbfc44f6](https://linux-hardware.org/?probe=3dbbfc44f6) | Oct 04, 2022 |
| ASUSTek       | K43SJ                       | [826d1c0dc8](https://linux-hardware.org/?probe=826d1c0dc8) | Oct 04, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [a38d4c3754](https://linux-hardware.org/?probe=a38d4c3754) | Oct 04, 2022 |
| ASUSTek       | T101MT                      | [d0fc7c3dae](https://linux-hardware.org/?probe=d0fc7c3dae) | Oct 04, 2022 |
| Acer          | Nitro AN515-52              | [9a69b6dc4a](https://linux-hardware.org/?probe=9a69b6dc4a) | Oct 03, 2022 |
| Lenovo        | B590 62743BG                | [8c120b5fea](https://linux-hardware.org/?probe=8c120b5fea) | Oct 03, 2022 |
| Sony          | VPCF12Z1R                   | [6d7cd0d51d](https://linux-hardware.org/?probe=6d7cd0d51d) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [2ac8b7a157](https://linux-hardware.org/?probe=2ac8b7a157) | Oct 03, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | [7f5e71e099](https://linux-hardware.org/?probe=7f5e71e099) | Oct 02, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | [8b81fb7c67](https://linux-hardware.org/?probe=8b81fb7c67) | Oct 02, 2022 |
| HP            | Pavilion dv7                | [219524e854](https://linux-hardware.org/?probe=219524e854) | Oct 02, 2022 |
| BenQ          | Joybook S32                 | [ba2b78c3e4](https://linux-hardware.org/?probe=ba2b78c3e4) | Oct 02, 2022 |
| HP            | Pavilion g7                 | [458c7b0f65](https://linux-hardware.org/?probe=458c7b0f65) | Oct 02, 2022 |
| Sony          | VPCEB1M1R                   | [343feefe62](https://linux-hardware.org/?probe=343feefe62) | Oct 02, 2022 |
| Acer          | Aspire A315-42G             | [84345ea89c](https://linux-hardware.org/?probe=84345ea89c) | Oct 02, 2022 |
| Lenovo        | G550 20023                  | [68961f954b](https://linux-hardware.org/?probe=68961f954b) | Oct 02, 2022 |
| ASUSTek       | K53SM                       | [49967682a7](https://linux-hardware.org/?probe=49967682a7) | Oct 02, 2022 |
| Dell          | Inspiron 3520               | [5fdeec4922](https://linux-hardware.org/?probe=5fdeec4922) | Oct 02, 2022 |
| Quanta        | TWC                         | [423f504621](https://linux-hardware.org/?probe=423f504621) | Oct 02, 2022 |
| HP            | 650                         | [162893e9ad](https://linux-hardware.org/?probe=162893e9ad) | Oct 01, 2022 |
| Lenovo        | G770 20089                  | [e06e588d62](https://linux-hardware.org/?probe=e06e588d62) | Oct 01, 2022 |
| ASUSTek       | F5V                         | [463cd15493](https://linux-hardware.org/?probe=463cd15493) | Oct 01, 2022 |
| Dell          | Inspiron 5737               | [14113affa1](https://linux-hardware.org/?probe=14113affa1) | Oct 01, 2022 |
| Dell          | Inspiron 5737               | [6893292144](https://linux-hardware.org/?probe=6893292144) | Oct 01, 2022 |
| Acer          | Aspire 5750G                | [8e87575f75](https://linux-hardware.org/?probe=8e87575f75) | Oct 01, 2022 |
| Acer          | Extensa 4220                | [c35a0a579a](https://linux-hardware.org/?probe=c35a0a579a) | Sep 30, 2022 |
| HP            | Pavilion dv7                | [4d54db9389](https://linux-hardware.org/?probe=4d54db9389) | Sep 30, 2022 |
| Acer          | Aspire A514-54              | [b8b0da1194](https://linux-hardware.org/?probe=b8b0da1194) | Sep 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [9ccd242ca4](https://linux-hardware.org/?probe=9ccd242ca4) | Sep 30, 2022 |
| Lenovo        | G580 20150                  | [d057161e9d](https://linux-hardware.org/?probe=d057161e9d) | Sep 30, 2022 |
| Acer          | Aspire 5741G                | [837c4599cc](https://linux-hardware.org/?probe=837c4599cc) | Sep 29, 2022 |
| Acer          | AOD257                      | [87b7501836](https://linux-hardware.org/?probe=87b7501836) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [4a8bc2a5e5](https://linux-hardware.org/?probe=4a8bc2a5e5) | Sep 28, 2022 |
| Acer          | Aspire A715-42G             | [44d8521e1d](https://linux-hardware.org/?probe=44d8521e1d) | Sep 28, 2022 |
| Acer          | Aspire A715-42G             | [ecbc8d9288](https://linux-hardware.org/?probe=ecbc8d9288) | Sep 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [6ce327114c](https://linux-hardware.org/?probe=6ce327114c) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d0fd059ca7](https://linux-hardware.org/?probe=d0fd059ca7) | Sep 28, 2022 |
| Acer          | Aspire A515-45G             | [0e8bdd2e37](https://linux-hardware.org/?probe=0e8bdd2e37) | Sep 27, 2022 |
| Samsung       | R530/R730                   | [e6168a9f1a](https://linux-hardware.org/?probe=e6168a9f1a) | Sep 27, 2022 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | [bb1530a50e](https://linux-hardware.org/?probe=bb1530a50e) | Sep 27, 2022 |
| Lenovo        | IdeaPad S340-15IML 81NA     | [03d36518de](https://linux-hardware.org/?probe=03d36518de) | Sep 27, 2022 |
| Medion        | C15MU-N                     | [e4a1e96ebd](https://linux-hardware.org/?probe=e4a1e96ebd) | Sep 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [efcbc52fcd](https://linux-hardware.org/?probe=efcbc52fcd) | Sep 25, 2022 |
| MSI           | GL65 Leopard 10SCSR         | [d1b60d3f52](https://linux-hardware.org/?probe=d1b60d3f52) | Sep 25, 2022 |
| Lenovo        | Legion Y-540-17IRH-PG0 8... | [29c967b4ec](https://linux-hardware.org/?probe=29c967b4ec) | Sep 25, 2022 |
| MSI           | GL65 Leopard 10SCSR         | [1487715bc7](https://linux-hardware.org/?probe=1487715bc7) | Sep 25, 2022 |
| Unknown       | Unknown                     | [d5d8bdbf34](https://linux-hardware.org/?probe=d5d8bdbf34) | Sep 25, 2022 |
| HP            | Pavilion g6                 | [915b5a320a](https://linux-hardware.org/?probe=915b5a320a) | Sep 25, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [436bfa4c50](https://linux-hardware.org/?probe=436bfa4c50) | Sep 25, 2022 |
| HP            | Pavilion g6                 | [2c685dca1c](https://linux-hardware.org/?probe=2c685dca1c) | Sep 24, 2022 |
| Samsung       | R540/R580/R780/SA41/E452    | [fe4a71500c](https://linux-hardware.org/?probe=fe4a71500c) | Sep 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [bf6e11dcf3](https://linux-hardware.org/?probe=bf6e11dcf3) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | [ea756ff16b](https://linux-hardware.org/?probe=ea756ff16b) | Sep 24, 2022 |
| ASUSTek       | X541NC                      | [226d4d741d](https://linux-hardware.org/?probe=226d4d741d) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| Acer          | Aspire 5253G                | [098f7ee3ed](https://linux-hardware.org/?probe=098f7ee3ed) | Sep 24, 2022 |
| Acer          | Aspire 5733Z                | [c22d27a781](https://linux-hardware.org/?probe=c22d27a781) | Sep 23, 2022 |
| ASUSTek       | X550EA                      | [256620a993](https://linux-hardware.org/?probe=256620a993) | Sep 23, 2022 |
| Haier         | GG1560XT                    | [fbdbeb0e82](https://linux-hardware.org/?probe=fbdbeb0e82) | Sep 22, 2022 |
| Acer          | Aspire A315-51              | [29e3f57ef9](https://linux-hardware.org/?probe=29e3f57ef9) | Sep 22, 2022 |
| Dell          | Inspiron 5547               | [e3a9b82c15](https://linux-hardware.org/?probe=e3a9b82c15) | Sep 22, 2022 |
| ASUSTek       | X550LC                      | [03f4677430](https://linux-hardware.org/?probe=03f4677430) | Sep 22, 2022 |
| ASUSTek       | K50IJ                       | [a0d9805cbb](https://linux-hardware.org/?probe=a0d9805cbb) | Sep 22, 2022 |
| Unknown       | Unknown                     | [a3dbfe1076](https://linux-hardware.org/?probe=a3dbfe1076) | Sep 22, 2022 |
| Lenovo        | ThinkPad L13 20R3000CRT     | [cec261f5e2](https://linux-hardware.org/?probe=cec261f5e2) | Sep 22, 2022 |
| ASUSTek       | K53E                        | [dc270d21ac](https://linux-hardware.org/?probe=dc270d21ac) | Sep 22, 2022 |
| MSI           | Katana GF66 11UE            | [b418d015a6](https://linux-hardware.org/?probe=b418d015a6) | Sep 22, 2022 |
| Lenovo        | G500 20236                  | [ede942e5a1](https://linux-hardware.org/?probe=ede942e5a1) | Sep 21, 2022 |
| DEXP          | Notebook                    | [2caa8c0be4](https://linux-hardware.org/?probe=2caa8c0be4) | Sep 21, 2022 |
| Acer          | Aspire A315-23              | [204980d2bd](https://linux-hardware.org/?probe=204980d2bd) | Sep 21, 2022 |
| ASUSTek       | X550LC                      | [018ca85503](https://linux-hardware.org/?probe=018ca85503) | Sep 21, 2022 |
| ASUSTek       | K50IJ                       | [3662255ac7](https://linux-hardware.org/?probe=3662255ac7) | Sep 20, 2022 |
| ASUSTek       | BU401LG                     | [12d87b6cad](https://linux-hardware.org/?probe=12d87b6cad) | Sep 20, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [1db8da5821](https://linux-hardware.org/?probe=1db8da5821) | Sep 20, 2022 |
| HP            | Pavilion g6                 | [930de8d94d](https://linux-hardware.org/?probe=930de8d94d) | Sep 20, 2022 |
| ASUSTek       | X550LC                      | [3683e3fd1b](https://linux-hardware.org/?probe=3683e3fd1b) | Sep 20, 2022 |
| Intel         | ChiefRiver Platform         | [87cff551c8](https://linux-hardware.org/?probe=87cff551c8) | Sep 20, 2022 |
| Intel         | ChiefRiver Platform         | [ffaa34d0c1](https://linux-hardware.org/?probe=ffaa34d0c1) | Sep 20, 2022 |
| HP            | Pavilion g6                 | [dfd4d1f4e2](https://linux-hardware.org/?probe=dfd4d1f4e2) | Sep 20, 2022 |
| HP            | ProBook 5330m               | [659bc725a3](https://linux-hardware.org/?probe=659bc725a3) | Sep 19, 2022 |
| HP            | EliteBook 840 G4            | [32b16880e2](https://linux-hardware.org/?probe=32b16880e2) | Sep 19, 2022 |
| ASUSTek       | X550MJ                      | [8b3130c363](https://linux-hardware.org/?probe=8b3130c363) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [d9742b9445](https://linux-hardware.org/?probe=d9742b9445) | Sep 19, 2022 |
| Aquarius      | NS685U R11                  | [f1f88e57c5](https://linux-hardware.org/?probe=f1f88e57c5) | Sep 19, 2022 |
| HP            | Pavilion g6                 | [4d623b8260](https://linux-hardware.org/?probe=4d623b8260) | Sep 19, 2022 |
| HP            | Notebook                    | [91f7c83215](https://linux-hardware.org/?probe=91f7c83215) | Sep 18, 2022 |
| Sony          | VGN-FW245J                  | [ab3391f43e](https://linux-hardware.org/?probe=ab3391f43e) | Sep 18, 2022 |
| ASUSTek       | F3Sa                        | [0950d9df40](https://linux-hardware.org/?probe=0950d9df40) | Sep 18, 2022 |
| Acer          | Ferrari 3200                | [ca5401c49c](https://linux-hardware.org/?probe=ca5401c49c) | Sep 18, 2022 |
| Samsung       | N150P/N210P/N220P           | [0dc99cefb4](https://linux-hardware.org/?probe=0dc99cefb4) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6c5e991427](https://linux-hardware.org/?probe=6c5e991427) | Sep 18, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bf101b4985](https://linux-hardware.org/?probe=bf101b4985) | Sep 17, 2022 |
| Acer          | Aspire ES1-523              | [cf05d4169b](https://linux-hardware.org/?probe=cf05d4169b) | Sep 17, 2022 |
| HP            | Compaq Presario CQ50        | [dce2af5435](https://linux-hardware.org/?probe=dce2af5435) | Sep 16, 2022 |
| HP            | Pavilion g6                 | [ba360b5712](https://linux-hardware.org/?probe=ba360b5712) | Sep 16, 2022 |
| HP            | Laptop 15-bs1xx             | [5529c09c5e](https://linux-hardware.org/?probe=5529c09c5e) | Sep 16, 2022 |
| ASUSTek       | X550MD                      | [69cce160a1](https://linux-hardware.org/?probe=69cce160a1) | Sep 16, 2022 |
| Aquarius      | NS685U R11                  | [3b687d6944](https://linux-hardware.org/?probe=3b687d6944) | Sep 16, 2022 |
| Aquarius      | NS685U R11                  | [9e626224d3](https://linux-hardware.org/?probe=9e626224d3) | Sep 16, 2022 |
| MSI           | GS66 Stealth 10SE           | [de4d4f5b61](https://linux-hardware.org/?probe=de4d4f5b61) | Sep 16, 2022 |
| Acer          | Aspire A717-72G             | [b0f989d584](https://linux-hardware.org/?probe=b0f989d584) | Sep 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [f632794c70](https://linux-hardware.org/?probe=f632794c70) | Sep 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d99530ffd0](https://linux-hardware.org/?probe=d99530ffd0) | Sep 15, 2022 |
| Aquarius      | NS685U R11                  | [37cfe22203](https://linux-hardware.org/?probe=37cfe22203) | Sep 15, 2022 |
| Aquarius      | NS685U R11                  | [e8ba91b867](https://linux-hardware.org/?probe=e8ba91b867) | Sep 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b731b95d0f](https://linux-hardware.org/?probe=b731b95d0f) | Sep 15, 2022 |
| Timi          | RedmiBook Pro 14S           | [1662163cb8](https://linux-hardware.org/?probe=1662163cb8) | Sep 15, 2022 |
| HP            | Notebook                    | [65621e9bea](https://linux-hardware.org/?probe=65621e9bea) | Sep 14, 2022 |
| Acer          | Extensa 215-52              | [cb38a4efeb](https://linux-hardware.org/?probe=cb38a4efeb) | Sep 14, 2022 |
| Acer          | TravelMate 5744Z            | [f9846e0165](https://linux-hardware.org/?probe=f9846e0165) | Sep 13, 2022 |
| Chuwi         | HeroBook Pro                | [aa99b0558b](https://linux-hardware.org/?probe=aa99b0558b) | Sep 13, 2022 |
| Acer          | Nitro AN515-54              | [552b310540](https://linux-hardware.org/?probe=552b310540) | Sep 13, 2022 |
| ASUSTek       | 1005HA                      | [93ee340172](https://linux-hardware.org/?probe=93ee340172) | Sep 12, 2022 |
| Aquarius      | win10 HOME rs10             | [988e1b3035](https://linux-hardware.org/?probe=988e1b3035) | Sep 12, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0d14398a88](https://linux-hardware.org/?probe=0d14398a88) | Sep 12, 2022 |
| HP            | EliteBook 2530p             | [4bae06f3d0](https://linux-hardware.org/?probe=4bae06f3d0) | Sep 12, 2022 |
| ASUSTek       | F5N                         | [343f77754d](https://linux-hardware.org/?probe=343f77754d) | Sep 12, 2022 |
| ASUSTek       | X550LC                      | [124bce938e](https://linux-hardware.org/?probe=124bce938e) | Sep 12, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [017c9c9f8f](https://linux-hardware.org/?probe=017c9c9f8f) | Sep 11, 2022 |
| ASUSTek       | N56VJ                       | [a67b781113](https://linux-hardware.org/?probe=a67b781113) | Sep 11, 2022 |
| ASUSTek       | N56VJ                       | [c384cac71a](https://linux-hardware.org/?probe=c384cac71a) | Sep 11, 2022 |
| HP            | Pavilion g6                 | [15a646b1af](https://linux-hardware.org/?probe=15a646b1af) | Sep 11, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | [404a01ee53](https://linux-hardware.org/?probe=404a01ee53) | Sep 11, 2022 |
| HP            | Pavilion g6                 | [abeefb9863](https://linux-hardware.org/?probe=abeefb9863) | Sep 11, 2022 |
| Lenovo        | IdeaPad Y510                | [460d140033](https://linux-hardware.org/?probe=460d140033) | Sep 11, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [d26f8478cf](https://linux-hardware.org/?probe=d26f8478cf) | Sep 10, 2022 |
| ASUSTek       | X705UQ                      | [8afcde5edb](https://linux-hardware.org/?probe=8afcde5edb) | Sep 10, 2022 |
| HP            | Presario CQ56               | [9ab1ac3d7d](https://linux-hardware.org/?probe=9ab1ac3d7d) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [894e7133b8](https://linux-hardware.org/?probe=894e7133b8) | Sep 10, 2022 |
| Toshiba       | Satellite A200              | [ce084887f1](https://linux-hardware.org/?probe=ce084887f1) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7d63a02b7a](https://linux-hardware.org/?probe=7d63a02b7a) | Sep 09, 2022 |
| ASUSTek       | X401A1                      | [8da7efe143](https://linux-hardware.org/?probe=8da7efe143) | Sep 09, 2022 |
| ASUSTek       | X55A                        | [3164e4194b](https://linux-hardware.org/?probe=3164e4194b) | Sep 09, 2022 |
| ASUSTek       | 1225C                       | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Dell          | Inspiron N5110              | [6743b005a2](https://linux-hardware.org/?probe=6743b005a2) | Sep 09, 2022 |
| Acer          | Aspire 5742G                | [64789ba939](https://linux-hardware.org/?probe=64789ba939) | Sep 08, 2022 |
| Acer          | Aspire 7530G                | [c60f3942b7](https://linux-hardware.org/?probe=c60f3942b7) | Sep 08, 2022 |
| Dell          | Inspiron 3521               | [684eb65731](https://linux-hardware.org/?probe=684eb65731) | Sep 08, 2022 |
| Aquarius      | win10 HOME rs10             | [6d31915653](https://linux-hardware.org/?probe=6d31915653) | Sep 08, 2022 |
| System76      | Lemur                       | [5993c130bc](https://linux-hardware.org/?probe=5993c130bc) | Sep 07, 2022 |
| Apple         | MacBook4,1                  | [dcc65ebdf1](https://linux-hardware.org/?probe=dcc65ebdf1) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c22457dc35](https://linux-hardware.org/?probe=c22457dc35) | Sep 07, 2022 |
| Toshiba       | Satellite Pro L630          | [9f20969845](https://linux-hardware.org/?probe=9f20969845) | Sep 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c0933e083b](https://linux-hardware.org/?probe=c0933e083b) | Sep 06, 2022 |
| HP            | Pavilion g6                 | [fe038c57a9](https://linux-hardware.org/?probe=fe038c57a9) | Sep 06, 2022 |
| Aquarius      | NS685U R11                  | [e4b0733994](https://linux-hardware.org/?probe=e4b0733994) | Sep 06, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd9555b23](https://linux-hardware.org/?probe=edd9555b23) | Sep 06, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [93d596fc4f](https://linux-hardware.org/?probe=93d596fc4f) | Sep 05, 2022 |
| Lenovo        | B50-10 80QR                 | [983c62f244](https://linux-hardware.org/?probe=983c62f244) | Sep 05, 2022 |
| MSI           | GP60 2OD                    | [edfcc5eb89](https://linux-hardware.org/?probe=edfcc5eb89) | Sep 05, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [0e3fd8d374](https://linux-hardware.org/?probe=0e3fd8d374) | Sep 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [90f0d2a48d](https://linux-hardware.org/?probe=90f0d2a48d) | Sep 04, 2022 |
| Lenovo        | G710 20252                  | [f43077f02f](https://linux-hardware.org/?probe=f43077f02f) | Sep 04, 2022 |
| MSI           | MS-N051                     | [a7ae139021](https://linux-hardware.org/?probe=a7ae139021) | Sep 03, 2022 |
| Dell          | Inspiron N5110              | [5201cd643e](https://linux-hardware.org/?probe=5201cd643e) | Sep 03, 2022 |
| ASUSTek       | U24E                        | [2b872b7fa8](https://linux-hardware.org/?probe=2b872b7fa8) | Sep 03, 2022 |
| ASUSTek       | K50IJ                       | [8fd7454abf](https://linux-hardware.org/?probe=8fd7454abf) | Sep 03, 2022 |
| HP            | Compaq nx7300 (RU373ES#A... | [e32e503c04](https://linux-hardware.org/?probe=e32e503c04) | Sep 03, 2022 |
| Dell          | Inspiron 3531               | [929b1f8bf4](https://linux-hardware.org/?probe=929b1f8bf4) | Sep 02, 2022 |
| Acer          | Aspire A315-34              | [35cbd90c30](https://linux-hardware.org/?probe=35cbd90c30) | Sep 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cbab6ab08c](https://linux-hardware.org/?probe=cbab6ab08c) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [23e052db95](https://linux-hardware.org/?probe=23e052db95) | Sep 01, 2022 |
| Notebook      | W65_67SB                    | [38393a5559](https://linux-hardware.org/?probe=38393a5559) | Sep 01, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [6aba706c0c](https://linux-hardware.org/?probe=6aba706c0c) | Aug 31, 2022 |
| Lenovo        | G710 20252                  | [37b1f6e81c](https://linux-hardware.org/?probe=37b1f6e81c) | Aug 31, 2022 |
| ASUSTek       | K46CM                       | [742d7047ea](https://linux-hardware.org/?probe=742d7047ea) | Aug 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9da97f5dea](https://linux-hardware.org/?probe=9da97f5dea) | Aug 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [8036c3df64](https://linux-hardware.org/?probe=8036c3df64) | Aug 30, 2022 |
| Dell          | G3 3579                     | [fd78a1cf65](https://linux-hardware.org/?probe=fd78a1cf65) | Aug 30, 2022 |
| Packard Be... | EasyNote LM85               | [4294f9bdaf](https://linux-hardware.org/?probe=4294f9bdaf) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [339b12ba13](https://linux-hardware.org/?probe=339b12ba13) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [3236ef3b00](https://linux-hardware.org/?probe=3236ef3b00) | Aug 30, 2022 |
| Acer          | Aspire V3-731               | [19d7285e0f](https://linux-hardware.org/?probe=19d7285e0f) | Aug 30, 2022 |
| Google        | Rammus                      | [cd31fc11aa](https://linux-hardware.org/?probe=cd31fc11aa) | Aug 29, 2022 |
| HP            | Pavilion g6                 | [d127560ff3](https://linux-hardware.org/?probe=d127560ff3) | Aug 29, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [eedd8fa1eb](https://linux-hardware.org/?probe=eedd8fa1eb) | Aug 29, 2022 |
| ASUSTek       | X550LC                      | [3507f6f2ba](https://linux-hardware.org/?probe=3507f6f2ba) | Aug 29, 2022 |
| Dell          | Vostro 1014                 | [bf43d87a11](https://linux-hardware.org/?probe=bf43d87a11) | Aug 29, 2022 |
| HP            | Notebook                    | [e00cfcb387](https://linux-hardware.org/?probe=e00cfcb387) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| ASUSTek       | F3E                         | [1314dc63b6](https://linux-hardware.org/?probe=1314dc63b6) | Aug 28, 2022 |
| Samsung       | R580/R590                   | [cb30537ee4](https://linux-hardware.org/?probe=cb30537ee4) | Aug 28, 2022 |
| Acer          | Nitro AN515-42              | [a82d7c03b0](https://linux-hardware.org/?probe=a82d7c03b0) | Aug 28, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6cd83991d9](https://linux-hardware.org/?probe=6cd83991d9) | Aug 28, 2022 |
| HP            | Pavilion g6                 | [709d3e19e8](https://linux-hardware.org/?probe=709d3e19e8) | Aug 28, 2022 |
| Acer          | Aspire E5-573G              | [70ea653c9c](https://linux-hardware.org/?probe=70ea653c9c) | Aug 28, 2022 |
| HP            | Laptop 15-bw0xx             | [90fa9c15ec](https://linux-hardware.org/?probe=90fa9c15ec) | Aug 27, 2022 |
| Acer          | Aspire V3-571G              | [e584bee2db](https://linux-hardware.org/?probe=e584bee2db) | Aug 27, 2022 |
| Lenovo        | V14-ADA 82C6                | [46741f4613](https://linux-hardware.org/?probe=46741f4613) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Acer          | Nitro AN515-42              | [063eca4290](https://linux-hardware.org/?probe=063eca4290) | Aug 26, 2022 |
| Acer          | Aspire 5570Z                | [38fe74cbe3](https://linux-hardware.org/?probe=38fe74cbe3) | Aug 26, 2022 |
| Acer          | Nitro AN517-52              | [8732c0caef](https://linux-hardware.org/?probe=8732c0caef) | Aug 26, 2022 |
| ASUSTek       | K52Dr                       | [aa74e72258](https://linux-hardware.org/?probe=aa74e72258) | Aug 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [619be9ede9](https://linux-hardware.org/?probe=619be9ede9) | Aug 26, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [635925265e](https://linux-hardware.org/?probe=635925265e) | Aug 25, 2022 |
| Unknown       | Unknown                     | [b9616ab32f](https://linux-hardware.org/?probe=b9616ab32f) | Aug 25, 2022 |
| Acer          | AO533                       | [5150a8b326](https://linux-hardware.org/?probe=5150a8b326) | Aug 25, 2022 |
| HP            | Pavilion 17                 | [e252f6b16e](https://linux-hardware.org/?probe=e252f6b16e) | Aug 25, 2022 |
| 3Logic Gro... | APM Graviton                | [03fd96a27c](https://linux-hardware.org/?probe=03fd96a27c) | Aug 24, 2022 |
| HP            | Compaq 610                  | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Pavilion g6                 | [4c027aa104](https://linux-hardware.org/?probe=4c027aa104) | Aug 24, 2022 |
| Samsung       | NC210/NC110                 | [8063d3ecff](https://linux-hardware.org/?probe=8063d3ecff) | Aug 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [37c239f9d1](https://linux-hardware.org/?probe=37c239f9d1) | Aug 24, 2022 |
| HP            | Pavilion g6                 | [96672b6762](https://linux-hardware.org/?probe=96672b6762) | Aug 24, 2022 |
| HP            | Laptop 15s-fq2xxx           | [3c37e04cf3](https://linux-hardware.org/?probe=3c37e04cf3) | Aug 24, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b5dea99797](https://linux-hardware.org/?probe=b5dea99797) | Aug 24, 2022 |
| HP            | Compaq Presario CQ50        | [ca5e35f5fd](https://linux-hardware.org/?probe=ca5e35f5fd) | Aug 24, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [b8859a4f21](https://linux-hardware.org/?probe=b8859a4f21) | Aug 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ce734a061a](https://linux-hardware.org/?probe=ce734a061a) | Aug 23, 2022 |
| Unknown       | Unknown                     | [40c763302e](https://linux-hardware.org/?probe=40c763302e) | Aug 22, 2022 |
| ASUSTek       | K55DR                       | [3620d3d416](https://linux-hardware.org/?probe=3620d3d416) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0d73b91195](https://linux-hardware.org/?probe=0d73b91195) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [7e345d980f](https://linux-hardware.org/?probe=7e345d980f) | Aug 21, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [8756581baa](https://linux-hardware.org/?probe=8756581baa) | Aug 21, 2022 |
| Acer          | Aspire E1-572G              | [d3d75b83d2](https://linux-hardware.org/?probe=d3d75b83d2) | Aug 21, 2022 |
| HP            | Pavilion m6                 | [54fcf9b1b4](https://linux-hardware.org/?probe=54fcf9b1b4) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [8ab10bdcff](https://linux-hardware.org/?probe=8ab10bdcff) | Aug 21, 2022 |
| HP            | 255 G7 Notebook PC          | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| Acer          | Aspire A315-23              | [cedbeec8c7](https://linux-hardware.org/?probe=cedbeec8c7) | Aug 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0008792e11](https://linux-hardware.org/?probe=0008792e11) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [8fd948229f](https://linux-hardware.org/?probe=8fd948229f) | Aug 19, 2022 |
| Acer          | Nitro AN517-52              | [8a1b401faa](https://linux-hardware.org/?probe=8a1b401faa) | Aug 19, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [b1602685e4](https://linux-hardware.org/?probe=b1602685e4) | Aug 19, 2022 |
| eMachines     | E525                        | [90d5ce71fa](https://linux-hardware.org/?probe=90d5ce71fa) | Aug 19, 2022 |
| Acer          | TravelMate B118-M           | [e35887bbe0](https://linux-hardware.org/?probe=e35887bbe0) | Aug 18, 2022 |
| HP            | Compaq 610                  | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| Lenovo        | ACLUAB                      | [3dcd5fa41c](https://linux-hardware.org/?probe=3dcd5fa41c) | Aug 18, 2022 |
| ASUSTek       | X551MA                      | [7baf2d8841](https://linux-hardware.org/?probe=7baf2d8841) | Aug 18, 2022 |
| Lenovo        | B590 20206                  | [d2d8a01f80](https://linux-hardware.org/?probe=d2d8a01f80) | Aug 18, 2022 |
| HP            | ProBook 440 G4              | [7bdaf1eeed](https://linux-hardware.org/?probe=7bdaf1eeed) | Aug 18, 2022 |
| HUAWEI        | NBD-WXX9                    | [fa32705b39](https://linux-hardware.org/?probe=fa32705b39) | Aug 18, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [7e5604ed7a](https://linux-hardware.org/?probe=7e5604ed7a) | Aug 17, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0VB0... | [0c8e0377e6](https://linux-hardware.org/?probe=0c8e0377e6) | Aug 17, 2022 |
| Apple         | MacBookAir7,2               | [1bbad39284](https://linux-hardware.org/?probe=1bbad39284) | Aug 17, 2022 |
| Lenovo        | G505 20240                  | [fa8889478b](https://linux-hardware.org/?probe=fa8889478b) | Aug 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| Acer          | AOD260                      | [f9256627d2](https://linux-hardware.org/?probe=f9256627d2) | Aug 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [8057f74fa1](https://linux-hardware.org/?probe=8057f74fa1) | Aug 16, 2022 |
| Pegatron      | A17                         | [18101d1b69](https://linux-hardware.org/?probe=18101d1b69) | Aug 16, 2022 |
| Pegatron      | A17                         | [a845e63b56](https://linux-hardware.org/?probe=a845e63b56) | Aug 16, 2022 |
| Sony          | VPCSB1V9R                   | [6c72559c96](https://linux-hardware.org/?probe=6c72559c96) | Aug 16, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [51cb006bb3](https://linux-hardware.org/?probe=51cb006bb3) | Aug 16, 2022 |
| Sony          | VPCSB1V9R                   | [6aee1e8e96](https://linux-hardware.org/?probe=6aee1e8e96) | Aug 15, 2022 |
| Acer          | AOD260                      | [ba32775bba](https://linux-hardware.org/?probe=ba32775bba) | Aug 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [44af3a6839](https://linux-hardware.org/?probe=44af3a6839) | Aug 15, 2022 |
| Lenovo        | ThinkPad X220 4291B66       | [4e32cfa8bb](https://linux-hardware.org/?probe=4e32cfa8bb) | Aug 15, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [3a6b82f27f](https://linux-hardware.org/?probe=3a6b82f27f) | Aug 15, 2022 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [f2e01b5017](https://linux-hardware.org/?probe=f2e01b5017) | Aug 14, 2022 |
| Acer          | Nitro AN515-43              | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| HP            | 550                         | [620939b295](https://linux-hardware.org/?probe=620939b295) | Aug 14, 2022 |
| Dell          | Inspiron 3537               | [bcd6162709](https://linux-hardware.org/?probe=bcd6162709) | Aug 14, 2022 |
| ASUSTek       | 1215N                       | [40d99f3703](https://linux-hardware.org/?probe=40d99f3703) | Aug 14, 2022 |
| ASUSTek       | X550DP                      | [ce42b65252](https://linux-hardware.org/?probe=ce42b65252) | Aug 13, 2022 |
| Dell          | Vostro 15 3515              | [442f64dba9](https://linux-hardware.org/?probe=442f64dba9) | Aug 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [4602665059](https://linux-hardware.org/?probe=4602665059) | Aug 13, 2022 |
| Dell          | Inspiron 7720               | [0435e973e0](https://linux-hardware.org/?probe=0435e973e0) | Aug 13, 2022 |
| Dell          | Precision M6600             | [7fcd14ca35](https://linux-hardware.org/?probe=7fcd14ca35) | Aug 13, 2022 |
| Acer          | Extensa 215-32              | [1a14e5a16b](https://linux-hardware.org/?probe=1a14e5a16b) | Aug 12, 2022 |
| Lenovo        | ThinkPad SL500 2746AA3      | [c4535a80a1](https://linux-hardware.org/?probe=c4535a80a1) | Aug 12, 2022 |
| ASUSTek       | K52Dr                       | [df4d29153d](https://linux-hardware.org/?probe=df4d29153d) | Aug 12, 2022 |
| HP            | 240 G8 Notebook PC          | [65080f426a](https://linux-hardware.org/?probe=65080f426a) | Aug 12, 2022 |
| ASUSTek       | F5N                         | [27348ad31d](https://linux-hardware.org/?probe=27348ad31d) | Aug 11, 2022 |
| Acer          | Unknown                     | [da56362a7e](https://linux-hardware.org/?probe=da56362a7e) | Aug 11, 2022 |
| MSI           | FX610                       | [60d49d467b](https://linux-hardware.org/?probe=60d49d467b) | Aug 11, 2022 |
| Dell          | Vostro 3460                 | [fbaf8208cb](https://linux-hardware.org/?probe=fbaf8208cb) | Aug 11, 2022 |
| eMachines     | eME728                      | [951d4614b6](https://linux-hardware.org/?probe=951d4614b6) | Aug 11, 2022 |
| Acer          | Aspire 5730                 | [34e252c0e0](https://linux-hardware.org/?probe=34e252c0e0) | Aug 11, 2022 |
| Acer          | AOHAPPY2                    | [dbed059d31](https://linux-hardware.org/?probe=dbed059d31) | Aug 10, 2022 |
| Acer          | Extensa 2519                | [674500aced](https://linux-hardware.org/?probe=674500aced) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4f4d3ac481](https://linux-hardware.org/?probe=4f4d3ac481) | Aug 10, 2022 |
| HP            | 255 G4                      | [44b5858d14](https://linux-hardware.org/?probe=44b5858d14) | Aug 10, 2022 |
| HP            | Compaq Presario CQ60        | [20f30b16e5](https://linux-hardware.org/?probe=20f30b16e5) | Aug 09, 2022 |
| Haier         | GG1560XT                    | [5b42159441](https://linux-hardware.org/?probe=5b42159441) | Aug 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d37a512899](https://linux-hardware.org/?probe=d37a512899) | Aug 09, 2022 |
| Dell          | XPS 15 9550                 | [abf6de9a2d](https://linux-hardware.org/?probe=abf6de9a2d) | Aug 09, 2022 |
| Lenovo        | ThinkPad X220 4291B66       | [e3362a3a9f](https://linux-hardware.org/?probe=e3362a3a9f) | Aug 09, 2022 |
| Acer          | Aspire ES1-522              | [bcde4c3494](https://linux-hardware.org/?probe=bcde4c3494) | Aug 08, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [06d7313a34](https://linux-hardware.org/?probe=06d7313a34) | Aug 08, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c11322ce1e](https://linux-hardware.org/?probe=c11322ce1e) | Aug 08, 2022 |
| Lenovo        | G70-80 80FF                 | [495516e19d](https://linux-hardware.org/?probe=495516e19d) | Aug 08, 2022 |
| ASUSTek       | X101CH                      | [07505fcd44](https://linux-hardware.org/?probe=07505fcd44) | Aug 07, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [091037a7fb](https://linux-hardware.org/?probe=091037a7fb) | Aug 07, 2022 |
| Acer          | Swift SF114-34              | [12de778ffd](https://linux-hardware.org/?probe=12de778ffd) | Aug 07, 2022 |
| ASUSTek       | F5N                         | [82b1172101](https://linux-hardware.org/?probe=82b1172101) | Aug 06, 2022 |
| eMachines     | eME728                      | [4000a32585](https://linux-hardware.org/?probe=4000a32585) | Aug 06, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [f801b501ae](https://linux-hardware.org/?probe=f801b501ae) | Aug 06, 2022 |
| Lenovo        | G50-80 80L0                 | [eb58813044](https://linux-hardware.org/?probe=eb58813044) | Aug 06, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [36d7a0a9bd](https://linux-hardware.org/?probe=36d7a0a9bd) | Aug 05, 2022 |
| Dell          | Latitude E5550              | [cecf472493](https://linux-hardware.org/?probe=cecf472493) | Aug 05, 2022 |
| Acer          | Extensa 2509                | [5093176e6c](https://linux-hardware.org/?probe=5093176e6c) | Aug 05, 2022 |
| Acer          | Extensa 5220                | [d9bdf6e628](https://linux-hardware.org/?probe=d9bdf6e628) | Aug 05, 2022 |
| Lenovo        | IdeaPad S20-30              | [f845cb2e0e](https://linux-hardware.org/?probe=f845cb2e0e) | Aug 04, 2022 |
| Samsung       | R528/R728                   | [8681847134](https://linux-hardware.org/?probe=8681847134) | Aug 04, 2022 |
| Pegatron      | A17                         | [15db0a3ade](https://linux-hardware.org/?probe=15db0a3ade) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| Lenovo        | B550 20053                  | [e42ac0b420](https://linux-hardware.org/?probe=e42ac0b420) | Aug 03, 2022 |
| eMachines     | E725                        | [12668c1e21](https://linux-hardware.org/?probe=12668c1e21) | Aug 03, 2022 |
| ASUSTek       | N56VV                       | [cc6eac0001](https://linux-hardware.org/?probe=cc6eac0001) | Aug 03, 2022 |
| eMachines     | E725                        | [3d751e0afa](https://linux-hardware.org/?probe=3d751e0afa) | Aug 03, 2022 |
| HP            | Pavilion dv7                | [895d651847](https://linux-hardware.org/?probe=895d651847) | Aug 02, 2022 |
| ASUSTek       | X550LC                      | [e430c69fbc](https://linux-hardware.org/?probe=e430c69fbc) | Aug 02, 2022 |
| ASUSTek       | X301A1                      | [60d9f2bc4d](https://linux-hardware.org/?probe=60d9f2bc4d) | Aug 02, 2022 |
| Acer          | Aspire A315-42              | [7d8e339d92](https://linux-hardware.org/?probe=7d8e339d92) | Aug 02, 2022 |
| Lenovo        | ThinkPad Edge E545 20B2A... | [51fe5d6f47](https://linux-hardware.org/?probe=51fe5d6f47) | Aug 02, 2022 |
| BBEN          | MN9                         | [d6ce556349](https://linux-hardware.org/?probe=d6ce556349) | Aug 02, 2022 |
| HP            | Pavilion dv6                | [28cf5336ab](https://linux-hardware.org/?probe=28cf5336ab) | Aug 02, 2022 |
| Dell          | Latitude 3490               | [3cd8f6d390](https://linux-hardware.org/?probe=3cd8f6d390) | Aug 02, 2022 |
| Lenovo        | B560                        | [010fb7ada1](https://linux-hardware.org/?probe=010fb7ada1) | Aug 01, 2022 |
| Shenzhen B... | XN1A                        | [6b1dd20a55](https://linux-hardware.org/?probe=6b1dd20a55) | Aug 01, 2022 |
| Samsung       | R530/R730/R540              | [73f8fb9528](https://linux-hardware.org/?probe=73f8fb9528) | Aug 01, 2022 |
| ASUSTek       | 1011PX                      | [c95aa572a4](https://linux-hardware.org/?probe=c95aa572a4) | Aug 01, 2022 |
| Acer          | Aspire 5830TG               | [7eb001e6b4](https://linux-hardware.org/?probe=7eb001e6b4) | Jul 31, 2022 |
| Aquarius      | Pro, Std, Elt Series        | [3f08a29e9a](https://linux-hardware.org/?probe=3f08a29e9a) | Jul 31, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | [d27e88a924](https://linux-hardware.org/?probe=d27e88a924) | Jul 31, 2022 |
| ASUSTek       | X550LC                      | [841508c072](https://linux-hardware.org/?probe=841508c072) | Jul 31, 2022 |
| Lenovo        | G580 20157                  | [a2270894c7](https://linux-hardware.org/?probe=a2270894c7) | Jul 31, 2022 |
| Acer          | Aspire 5730                 | [1541bd94e2](https://linux-hardware.org/?probe=1541bd94e2) | Jul 31, 2022 |
| MSI           | GL65 Leopard 10SCSR         | [2cbf6d3aae](https://linux-hardware.org/?probe=2cbf6d3aae) | Jul 31, 2022 |
| Acer          | Aspire 3610                 | [d56c48ade2](https://linux-hardware.org/?probe=d56c48ade2) | Jul 31, 2022 |
| Acer          | Unknown                     | [99992e8b67](https://linux-hardware.org/?probe=99992e8b67) | Jul 30, 2022 |
| Sony          | VPCEH2E1R                   | [24d621e667](https://linux-hardware.org/?probe=24d621e667) | Jul 30, 2022 |
| HP            | Laptop 15-db1xxx            | [dcbb6ec79b](https://linux-hardware.org/?probe=dcbb6ec79b) | Jul 30, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8ad22205d4](https://linux-hardware.org/?probe=8ad22205d4) | Jul 30, 2022 |
| Acer          | Aspire 5730                 | [8ac8b8a87a](https://linux-hardware.org/?probe=8ac8b8a87a) | Jul 30, 2022 |
| HP            | Pavilion g6                 | [ea628a71ee](https://linux-hardware.org/?probe=ea628a71ee) | Jul 29, 2022 |
| Acer          | Swift SF314-52              | [e9f0b2fcb7](https://linux-hardware.org/?probe=e9f0b2fcb7) | Jul 29, 2022 |
| ASUSTek       | P50IJ                       | [b11ce03a3b](https://linux-hardware.org/?probe=b11ce03a3b) | Jul 29, 2022 |
| Kraftway      | ACCORD                      | [1d694d32ba](https://linux-hardware.org/?probe=1d694d32ba) | Jul 29, 2022 |
| MSI           | FX610                       | [9e545d6a24](https://linux-hardware.org/?probe=9e545d6a24) | Jul 29, 2022 |
| Packard Be... | EasyNote LJ75               | [a883180728](https://linux-hardware.org/?probe=a883180728) | Jul 29, 2022 |
| Lenovo        | V14-IIL 82C4                | [9be688b59e](https://linux-hardware.org/?probe=9be688b59e) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4947baccf9](https://linux-hardware.org/?probe=4947baccf9) | Jul 28, 2022 |
| Sony          | VGN-TT31MR_N                | [b1a4f2a68c](https://linux-hardware.org/?probe=b1a4f2a68c) | Jul 27, 2022 |
| Acer          | Aspire 5741G                | [bb63a4917e](https://linux-hardware.org/?probe=bb63a4917e) | Jul 27, 2022 |
| ASUSTek       | X55A                        | [61d57c4e59](https://linux-hardware.org/?probe=61d57c4e59) | Jul 26, 2022 |
| Toshiba       | Satellite L750D             | [c8e9ea3fdd](https://linux-hardware.org/?probe=c8e9ea3fdd) | Jul 26, 2022 |
| Acer          | Iconia W700                 | [694887391c](https://linux-hardware.org/?probe=694887391c) | Jul 26, 2022 |
| ASUSTek       | X550LC                      | [e38c3e6cb5](https://linux-hardware.org/?probe=e38c3e6cb5) | Jul 26, 2022 |
| Acer          | Aspire 4720Z                | [0233e1c451](https://linux-hardware.org/?probe=0233e1c451) | Jul 26, 2022 |
| HP            | ENVY dv6                    | [7f8e688cc4](https://linux-hardware.org/?probe=7f8e688cc4) | Jul 26, 2022 |
| Acer          | TravelMate 5744Z            | [aa1416d2e3](https://linux-hardware.org/?probe=aa1416d2e3) | Jul 26, 2022 |
| Lenovo        | Legion Y-540-17IRH-PG0 8... | [22ded313b5](https://linux-hardware.org/?probe=22ded313b5) | Jul 25, 2022 |
| HP            | ENVY dv6                    | [97d752c934](https://linux-hardware.org/?probe=97d752c934) | Jul 25, 2022 |
| Acer          | Aspire A315-51              | [b9d14045a3](https://linux-hardware.org/?probe=b9d14045a3) | Jul 25, 2022 |
| Acer          | Aspire E5-551G              | [8c94f9bae3](https://linux-hardware.org/?probe=8c94f9bae3) | Jul 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [80334990e7](https://linux-hardware.org/?probe=80334990e7) | Jul 25, 2022 |
| ASUSTek       | T200TAC                     | [a8314ae281](https://linux-hardware.org/?probe=a8314ae281) | Jul 24, 2022 |
| HP            | Pavilion dv6                | [0a3ef4b5dd](https://linux-hardware.org/?probe=0a3ef4b5dd) | Jul 24, 2022 |
| ASUSTek       | S300CA                      | [08b3fe2c70](https://linux-hardware.org/?probe=08b3fe2c70) | Jul 24, 2022 |
| ASUSTek       | K53SJ                       | [d8eb4baf45](https://linux-hardware.org/?probe=d8eb4baf45) | Jul 24, 2022 |
| ASUSTek       | K53SJ                       | [5d5189c2d1](https://linux-hardware.org/?probe=5d5189c2d1) | Jul 24, 2022 |
| Lenovo        | B590 20208                  | [35decc70d1](https://linux-hardware.org/?probe=35decc70d1) | Jul 23, 2022 |
| Timi          | TM1701                      | [387e7a36d8](https://linux-hardware.org/?probe=387e7a36d8) | Jul 23, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [3181f43aef](https://linux-hardware.org/?probe=3181f43aef) | Jul 23, 2022 |
| Lenovo        | G710 20252                  | [87b375d9cf](https://linux-hardware.org/?probe=87b375d9cf) | Jul 22, 2022 |
| HP            | ProBook 4540s               | [d70dbfeecb](https://linux-hardware.org/?probe=d70dbfeecb) | Jul 22, 2022 |
| ASUSTek       | 1215N                       | [5ef0576222](https://linux-hardware.org/?probe=5ef0576222) | Jul 22, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [dd0034072b](https://linux-hardware.org/?probe=dd0034072b) | Jul 22, 2022 |
| Dell          | XPS 15 9550                 | [b4691ae23b](https://linux-hardware.org/?probe=b4691ae23b) | Jul 22, 2022 |
| ASUSTek       | F5N                         | [5dc4f489d9](https://linux-hardware.org/?probe=5dc4f489d9) | Jul 22, 2022 |
| Dell          | Inspiron MM061              | [8e0cd55a28](https://linux-hardware.org/?probe=8e0cd55a28) | Jul 22, 2022 |
| ASUSTek       | 1005HA                      | [5fca7b8752](https://linux-hardware.org/?probe=5fca7b8752) | Jul 21, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [b7d05f361c](https://linux-hardware.org/?probe=b7d05f361c) | Jul 21, 2022 |
| HP            | Pavilion dv7                | [8975495225](https://linux-hardware.org/?probe=8975495225) | Jul 21, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | [de71ab8780](https://linux-hardware.org/?probe=de71ab8780) | Jul 21, 2022 |
| Lenovo        | IdeaPad S340-15IML 81NA     | [bff95aa218](https://linux-hardware.org/?probe=bff95aa218) | Jul 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [81020ca308](https://linux-hardware.org/?probe=81020ca308) | Jul 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [914c4b3782](https://linux-hardware.org/?probe=914c4b3782) | Jul 21, 2022 |
| Lenovo        | ThinkPad T60 1953D9U        | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Dell          | Inspiron N5110              | [30a3da64bf](https://linux-hardware.org/?probe=30a3da64bf) | Jul 20, 2022 |
| Dell          | Latitude 3500               | [9f3c591e61](https://linux-hardware.org/?probe=9f3c591e61) | Jul 20, 2022 |
| Acer          | Acadia V1.45                | [73f544e6cb](https://linux-hardware.org/?probe=73f544e6cb) | Jul 20, 2022 |
| ASUSTek       | 1011PX                      | [fd9099b538](https://linux-hardware.org/?probe=fd9099b538) | Jul 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [1c39715e4d](https://linux-hardware.org/?probe=1c39715e4d) | Jul 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a85dfe6cdd](https://linux-hardware.org/?probe=a85dfe6cdd) | Jul 20, 2022 |
| Fujitsu Si... | AMILO Pi 3540               | [47c0c1f4eb](https://linux-hardware.org/?probe=47c0c1f4eb) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [4e1321f550](https://linux-hardware.org/?probe=4e1321f550) | Jul 19, 2022 |
| Fujitsu Si... | AMILO Pi 3540               | [4efd4113d7](https://linux-hardware.org/?probe=4efd4113d7) | Jul 19, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [6dbaa4c42a](https://linux-hardware.org/?probe=6dbaa4c42a) | Jul 19, 2022 |
| Acer          | Aspire 5730                 | [27c09757d3](https://linux-hardware.org/?probe=27c09757d3) | Jul 19, 2022 |
| Lenovo        | B590 20206                  | [bdd7a06914](https://linux-hardware.org/?probe=bdd7a06914) | Jul 18, 2022 |
| Toshiba       | Satellite C55-B             | [70c17c522d](https://linux-hardware.org/?probe=70c17c522d) | Jul 18, 2022 |
| Packard Be... | EasyNote TJ71               | [9a533d59ac](https://linux-hardware.org/?probe=9a533d59ac) | Jul 18, 2022 |
| HP            | Notebook                    | [d917f9c8a4](https://linux-hardware.org/?probe=d917f9c8a4) | Jul 18, 2022 |
| Dell          | Vostro 3500                 | [a0599c411c](https://linux-hardware.org/?probe=a0599c411c) | Jul 18, 2022 |
| Acer          | Aspire 5715Z                | [ee2710b5c5](https://linux-hardware.org/?probe=ee2710b5c5) | Jul 17, 2022 |
| Irbis         | NB660                       | [ca5b5a40a8](https://linux-hardware.org/?probe=ca5b5a40a8) | Jul 17, 2022 |
| HP            | Laptop 15-bw0xx             | [9acefdf3c8](https://linux-hardware.org/?probe=9acefdf3c8) | Jul 17, 2022 |
| ASUSTek       | X55VD                       | [7748a75672](https://linux-hardware.org/?probe=7748a75672) | Jul 17, 2022 |
| Lenovo        | G580 20157                  | [20e895d9f0](https://linux-hardware.org/?probe=20e895d9f0) | Jul 17, 2022 |
| Lenovo        | B590 20206                  | [e072d299e3](https://linux-hardware.org/?probe=e072d299e3) | Jul 16, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | [01bb777843](https://linux-hardware.org/?probe=01bb777843) | Jul 16, 2022 |
| eMachines     | E525                        | [da97665159](https://linux-hardware.org/?probe=da97665159) | Jul 16, 2022 |
| HP            | Pavilion g6                 | [3549fb92f1](https://linux-hardware.org/?probe=3549fb92f1) | Jul 15, 2022 |
| ASUSTek       | X550LC                      | [5ff99910a2](https://linux-hardware.org/?probe=5ff99910a2) | Jul 15, 2022 |
| Fujitsu       | AMILO Pi 3560               | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Acer          | Aspire A315-51              | [0ececc803e](https://linux-hardware.org/?probe=0ececc803e) | Jul 15, 2022 |
| Acer          | Aspire ES1-524              | [686edf54b2](https://linux-hardware.org/?probe=686edf54b2) | Jul 15, 2022 |
| Packard Be... | EasyNote TJ71               | [b8e077b663](https://linux-hardware.org/?probe=b8e077b663) | Jul 15, 2022 |
| Acer          | Iconia W700                 | [f290f68268](https://linux-hardware.org/?probe=f290f68268) | Jul 14, 2022 |
| Dell          | 500                         | [9c1b1d5349](https://linux-hardware.org/?probe=9c1b1d5349) | Jul 14, 2022 |
| ASUSTek       | K43SJ                       | [41d331904e](https://linux-hardware.org/?probe=41d331904e) | Jul 14, 2022 |
| ASUSTek       | X553MA                      | [b78b735f01](https://linux-hardware.org/?probe=b78b735f01) | Jul 14, 2022 |
| Toshiba       | Satellite C660              | [fa23f41617](https://linux-hardware.org/?probe=fa23f41617) | Jul 13, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [cf23beb6c1](https://linux-hardware.org/?probe=cf23beb6c1) | Jul 13, 2022 |
| ASUSTek       | X550LC                      | [059c605792](https://linux-hardware.org/?probe=059c605792) | Jul 13, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | [eb06d804a9](https://linux-hardware.org/?probe=eb06d804a9) | Jul 13, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [19209d1119](https://linux-hardware.org/?probe=19209d1119) | Jul 12, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8604a047fc](https://linux-hardware.org/?probe=8604a047fc) | Jul 12, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [7af17249cf](https://linux-hardware.org/?probe=7af17249cf) | Jul 11, 2022 |
| Lenovo        | 3000 G430 4153/200          | [b262119cef](https://linux-hardware.org/?probe=b262119cef) | Jul 11, 2022 |
| HP            | Laptop 15-db1xxx            | [5c94e19aab](https://linux-hardware.org/?probe=5c94e19aab) | Jul 11, 2022 |
| HP            | Laptop 15-db1xxx            | [f843bd9b84](https://linux-hardware.org/?probe=f843bd9b84) | Jul 11, 2022 |
| Irbis         | NB20                        | [8dc53febc0](https://linux-hardware.org/?probe=8dc53febc0) | Jul 11, 2022 |
| ASUSTek       | X51RL                       | [3da6910e57](https://linux-hardware.org/?probe=3da6910e57) | Jul 10, 2022 |
| ASUSTek       | N750JK                      | [efede6fbcd](https://linux-hardware.org/?probe=efede6fbcd) | Jul 10, 2022 |
| Lenovo        | ThinkPad L390 20NR0013RK    | [57447f37e2](https://linux-hardware.org/?probe=57447f37e2) | Jul 10, 2022 |
| Dell          | Precision M4800             | [d28fa75d0e](https://linux-hardware.org/?probe=d28fa75d0e) | Jul 10, 2022 |
| HP            | Pavilion g6                 | [19081f813f](https://linux-hardware.org/?probe=19081f813f) | Jul 10, 2022 |
| Lenovo        | E31-70 80KX                 | [ba73d295c1](https://linux-hardware.org/?probe=ba73d295c1) | Jul 10, 2022 |
| Acer          | Extensa 2509                | [b6374137c9](https://linux-hardware.org/?probe=b6374137c9) | Jul 09, 2022 |
| Dell          | Inspiron N5110              | [8c9cb805af](https://linux-hardware.org/?probe=8c9cb805af) | Jul 09, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | [318bcea56d](https://linux-hardware.org/?probe=318bcea56d) | Jul 09, 2022 |
| Sony          | VGN-FS515BR                 | [d8f67da4b1](https://linux-hardware.org/?probe=d8f67da4b1) | Jul 09, 2022 |
| Toshiba       | Satellite A300              | [0cdf2eabc3](https://linux-hardware.org/?probe=0cdf2eabc3) | Jul 09, 2022 |
| Packard Be... | EasyNote TE11HC             | [5b42305918](https://linux-hardware.org/?probe=5b42305918) | Jul 09, 2022 |
| Dell          | Inspiron N5110              | [efd3d0395b](https://linux-hardware.org/?probe=efd3d0395b) | Jul 09, 2022 |
| THD           | PX1 01                      | [5da95870c5](https://linux-hardware.org/?probe=5da95870c5) | Jul 09, 2022 |
| Acer          | Swift SF114-34              | [469f6147b8](https://linux-hardware.org/?probe=469f6147b8) | Jul 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [499be72aa8](https://linux-hardware.org/?probe=499be72aa8) | Jul 08, 2022 |
| ASUSTek       | N56VZ                       | [be74c56d76](https://linux-hardware.org/?probe=be74c56d76) | Jul 08, 2022 |
| Acer          | Aspire A315-51              | [6e44a5f157](https://linux-hardware.org/?probe=6e44a5f157) | Jul 08, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | F3JR                        | [9a1e994bcb](https://linux-hardware.org/?probe=9a1e994bcb) | Jul 08, 2022 |
| Aquarius      | NS685U R11                  | [ad52e2f253](https://linux-hardware.org/?probe=ad52e2f253) | Jul 08, 2022 |
| Sony          | SVE1512H1RW                 | [6aa6a13a40](https://linux-hardware.org/?probe=6aa6a13a40) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | [f2151c1737](https://linux-hardware.org/?probe=f2151c1737) | Jul 07, 2022 |
| Notebook      | W250EGQ / W270EGQ           | [189e78b17c](https://linux-hardware.org/?probe=189e78b17c) | Jul 07, 2022 |
| ASUSTek       | X550LC                      | [d9ce56c2f6](https://linux-hardware.org/?probe=d9ce56c2f6) | Jul 07, 2022 |
| ASUSTek       | K501LB                      | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| Acer          | Aspire E5-573G              | [cda7a71bd9](https://linux-hardware.org/?probe=cda7a71bd9) | Jul 07, 2022 |
| Acer          | Aspire A315-51              | [4fbcdebde9](https://linux-hardware.org/?probe=4fbcdebde9) | Jul 07, 2022 |
| Insyde        | CherryTrail                 | [6e2e30eb92](https://linux-hardware.org/?probe=6e2e30eb92) | Jul 07, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ROSA/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| ROSA R10     | 2144      | 14.75%  |
| ROSA R11     | 1939      | 13.34%  |
| ROSA R8      | 1703      | 11.71%  |
| ROSA R6      | 1686      | 11.6%   |
| ROSA R7      | 1566      | 10.77%  |
| ROSA R8.1    | 1349      | 9.28%   |
| ROSA R9      | 1217      | 8.37%   |
| ROSA R11.1   | 1050      | 7.22%   |
| ROSA 12.2    | 896       | 6.16%   |
| ROSA R5      | 321       | 2.21%   |
| ROSA 12.3    | 271       | 1.86%   |
| ROSA 12.1    | 145       | 1%      |
| ROSA R4      | 78        | 0.54%   |
| ROSA 12      | 62        | 0.43%   |
| ROSA R3      | 56        | 0.39%   |
| ROSA R12     | 24        | 0.17%   |
| ROSA R2      | 10        | 0.07%   |
| ROSA 2012.0  | 6         | 0.04%   |
| ROSA 2019.05 | 4         | 0.03%   |
| ROSA R9-R11  | 3         | 0.02%   |
| ROSA DX 2.0  | 2         | 0.01%   |
| ROSA DX 1.0  | 2         | 0.01%   |
| ROSA R4-R8   | 1         | 0.01%   |
| ROSA 2019.0  | 1         | 0.01%   |
| ROSA 13.0    | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| ROSA | 12065     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 954       | 6.09%   |
| 3.14.44-nrj-desktop-2rosa-x86_64    | 890       | 5.68%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 852       | 5.44%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 846       | 5.4%    |
| 5.10.74-generic-2rosa2021.1-x86_64  | 772       | 4.93%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 724       | 4.62%   |
| 4.1.15-nrj-desktop-1rosa-x86_64     | 621       | 3.96%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 458       | 2.92%   |
| 3.14.44-nrj-desktop-2rosa-i586      | 391       | 2.49%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 370       | 2.36%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 353       | 2.25%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 287       | 1.83%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 285       | 1.82%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 271       | 1.73%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 249       | 1.59%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 228       | 1.45%   |
| 4.15.0-desktop-45.1rosa-i586        | 227       | 1.45%   |
| 4.1.15-nrj-desktop-1rosa-i586       | 226       | 1.44%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 220       | 1.4%    |
| 4.15.0-desktop-68.5rosa-x86_64      | 216       | 1.38%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 214       | 1.37%   |
| 5.4.32-generic-2rosa-x86_64         | 211       | 1.35%   |
| 4.1.16-nrj-desktop-1rosa-x86_64     | 199       | 1.27%   |
| 5.4.83-generic-2rosa-x86_64         | 182       | 1.16%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 182       | 1.16%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 172       | 1.1%    |
| 5.10.118-generic-2rosa2021.1-x86_64 | 168       | 1.07%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 159       | 1.01%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 146       | 0.93%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 137       | 0.87%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 130       | 0.83%   |
| 3.14.25-nrj-desktop-1rosa           | 129       | 0.82%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 128       | 0.82%   |
| 3.14.53-nrj-desktop-1rosa-x86_64    | 127       | 0.81%   |
| 4.1.33-nrj-desktop-1rosa-x86_64     | 114       | 0.73%   |
| 4.1.22-nrj-desktop-2rosa-x86_64     | 113       | 0.72%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 111       | 0.71%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 98        | 0.63%   |
| 3.14.33-nrj-desktop-1rosa           | 98        | 0.63%   |
| 4.1.13-nrj-desktop-1rosa-x86_64     | 95        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 2062      | 13.4%   |
| 3.14.44  | 1283      | 8.34%   |
| 4.9.60   | 1238      | 8.04%   |
| 4.9.20   | 1106      | 7.19%   |
| 4.1.25   | 994       | 6.46%   |
| 4.1.15   | 850       | 5.52%   |
| 5.10.74  | 809       | 5.26%   |
| 4.1.34   | 643       | 4.18%   |
| 4.1.38   | 507       | 3.29%   |
| 4.9.124  | 484       | 3.15%   |
| 4.9.9    | 480       | 3.12%   |
| 4.9.155  | 306       | 1.99%   |
| 4.9.76   | 303       | 1.97%   |
| 4.9.41   | 296       | 1.92%   |
| 5.4.32   | 293       | 1.9%    |
| 4.1.16   | 292       | 1.9%    |
| 5.4.83   | 241       | 1.57%   |
| 4.1.19   | 197       | 1.28%   |
| 3.14.53  | 191       | 1.24%   |
| 5.10.118 | 173       | 1.12%   |
| 4.9.95   | 168       | 1.09%   |
| 4.1.22   | 168       | 1.09%   |
| 4.1.33   | 158       | 1.03%   |
| 4.1.13   | 155       | 1.01%   |
| 3.14.25  | 132       | 0.86%   |
| 5.15.75  | 108       | 0.7%    |
| 4.9.111  | 107       | 0.7%    |
| 3.14.33  | 103       | 0.67%   |
| 3.14.39  | 81        | 0.53%   |
| 4.9.87   | 76        | 0.49%   |
| 5.15.79  | 68        | 0.44%   |
| 5.10.71  | 61        | 0.4%    |
| 4.9.14   | 54        | 0.35%   |
| 3.14.15  | 54        | 0.35%   |
| 5.4.40   | 50        | 0.32%   |
| 4.13.0   | 49        | 0.32%   |
| 5.17.11  | 37        | 0.24%   |
| 3.10.34  | 34        | 0.22%   |
| 4.9.34   | 33        | 0.21%   |
| 3.14.22  | 31        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 4050      | 29.04%  |
| 4.1     | 3560      | 25.53%  |
| 4.15    | 2070      | 14.84%  |
| 3.14    | 1737      | 12.45%  |
| 5.10    | 1028      | 7.37%   |
| 5.4     | 604       | 4.33%   |
| 5.15    | 243       | 1.74%   |
| 4.4     | 75        | 0.54%   |
| 3.10    | 65        | 0.47%   |
| 4.13    | 64        | 0.46%   |
| 5.17    | 38        | 0.27%   |
| 4.0     | 38        | 0.27%   |
| 4.8     | 37        | 0.27%   |
| 5.0     | 30        | 0.22%   |
| 4.6     | 25        | 0.18%   |
| 5.18    | 21        | 0.15%   |
| 4.16    | 21        | 0.15%   |
| 4.7     | 20        | 0.14%   |
| 3.18    | 19        | 0.14%   |
| 4.19    | 18        | 0.13%   |
| 4.18    | 18        | 0.13%   |
| 4.14    | 18        | 0.13%   |
| 4.3     | 15        | 0.11%   |
| 4.5     | 13        | 0.09%   |
| 4.2     | 13        | 0.09%   |
| 6.0     | 11        | 0.08%   |
| 6.1     | 10        | 0.07%   |
| 5.16    | 10        | 0.07%   |
| 4.11    | 10        | 0.07%   |
| 4.17    | 9         | 0.06%   |
| 4.10    | 9         | 0.06%   |
| 3.17    | 7         | 0.05%   |
| 3.0     | 7         | 0.05%   |
| 4.12    | 6         | 0.04%   |
| 5.13    | 4         | 0.03%   |
| 5.9     | 3         | 0.02%   |
| 5.6     | 3         | 0.02%   |
| 5.5     | 3         | 0.02%   |
| 5.2     | 3         | 0.02%   |
| 5.8     | 2         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 9314      | 75.4%   |
| i686   | 3038      | 24.6%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE4    | 8628      | 66.33%  |
| KDE5    | 2873      | 22.09%  |
| GNOME   | 625       | 4.8%    |
| LXQt    | 475       | 3.65%   |
| MATE    | 175       | 1.35%   |
| XFCE    | 108       | 0.83%   |
| LXDE    | 89        | 0.68%   |
| Unknown | 33        | 0.25%   |
| KDE     | 1         | 0.01%   |
| Budgie  | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 11143     | 90.9%   |
| Wayland | 1110      | 9.05%   |
| Tty     | 6         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 8690      | 67.27%  |
| SDDM    | 3198      | 24.75%  |
| GDM     | 871       | 6.74%   |
| LightDM | 76        | 0.59%   |
| TDM     | 64        | 0.5%    |
| XDM     | 10        | 0.08%   |
| Unknown | 10        | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 10114     | 81.03%  |
| ru_RU   | 2087      | 16.72%  |
| en_US   | 76        | 0.61%   |
| pl_PL   | 35        | 0.28%   |
| de_DE   | 34        | 0.27%   |
| es_ES   | 22        | 0.18%   |
| en_GB   | 19        | 0.15%   |
| pt_BR   | 18        | 0.14%   |
| it_IT   | 13        | 0.1%    |
| fr_FR   | 12        | 0.1%    |
| ru_UA   | 7         | 0.06%   |
| tr_TR   | 3         | 0.02%   |
| pt_PT   | 3         | 0.02%   |
| es_PE   | 3         | 0.02%   |
| C       | 3         | 0.02%   |
| ro_RO   | 2         | 0.02%   |
| nl_NL   | 2         | 0.02%   |
| lv_LV   | 2         | 0.02%   |
| es_MX   | 2         | 0.02%   |
| es_CO   | 2         | 0.02%   |
| en_IN   | 2         | 0.02%   |
| da_DK   | 2         | 0.02%   |
| bg_BG   | 2         | 0.02%   |
| tt_RU   | 1         | 0.01%   |
| sv_SE   | 1         | 0.01%   |
| sr_RS   | 1         | 0.01%   |
| sk_SK   | 1         | 0.01%   |
| ru_BY   | 1         | 0.01%   |
| lt_LT   | 1         | 0.01%   |
| hu_HU   | 1         | 0.01%   |
| fr_BE   | 1         | 0.01%   |
| et_EE   | 1         | 0.01%   |
| es_VE   | 1         | 0.01%   |
| en_AU   | 1         | 0.01%   |
| de_AT   | 1         | 0.01%   |
| cs_CZ   | 1         | 0.01%   |
| ca_AD   | 1         | 0.01%   |
| be_BY   | 1         | 0.01%   |
| ba_RU   | 1         | 0.01%   |
| ar_DZ   | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 9265      | 75.23%  |
| EFI  | 3051      | 24.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Unknown  | 7904      | 61.63%  |
| Ext4     | 4682      | 36.51%  |
| Btrfs    | 174       | 1.36%   |
| Ext3     | 28        | 0.22%   |
| Aufs     | 11        | 0.09%   |
| Xfs      | 9         | 0.07%   |
| Ext2     | 8         | 0.06%   |
| F2fs     | 3         | 0.02%   |
| Reiserfs | 2         | 0.02%   |
| Overlay  | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| 20G      | 1         | 0.01%   |
| 12G      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 7508      | 57.85%  |
| GPT     | 2932      | 22.59%  |
| Unknown | 2539      | 19.56%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11254     | 90.93%  |
| Yes       | 1123      | 9.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10458     | 83.27%  |
| Yes       | 2101      | 16.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 2188      | 18.14%  |
| Lenovo                         | 1977      | 16.39%  |
| Acer                           | 1839      | 15.24%  |
| Hewlett-Packard                | 1767      | 14.65%  |
| Samsung Electronics            | 912       | 7.56%   |
| Dell                           | 846       | 7.01%   |
| Toshiba                        | 473       | 3.92%   |
| Sony                           | 311       | 2.58%   |
| Packard Bell                   | 243       | 2.01%   |
| MSI                            | 228       | 1.89%   |
| eMachines                      | 166       | 1.38%   |
| Notebook                       | 101       | 0.84%   |
| Clevo                          | 97        | 0.8%    |
| Fujitsu Siemens                | 75        | 0.62%   |
| Pegatron                       | 71        | 0.59%   |
| Apple                          | 65        | 0.54%   |
| Unknown                        | 62        | 0.51%   |
| Fujitsu                        | 54        | 0.45%   |
| Intel                          | 49        | 0.41%   |
| DNS                            | 47        | 0.39%   |
| Quanta                         | 35        | 0.29%   |
| DEXP                           | 29        | 0.24%   |
| Medion                         | 21        | 0.17%   |
| Irbis                          | 20        | 0.17%   |
| Aquarius                       | 19        | 0.16%   |
| Prestigio                      | 16        | 0.13%   |
| Insyde                         | 16        | 0.13%   |
| Infomash                       | 15        | 0.12%   |
| Compal                         | 15        | 0.12%   |
| LG Electronics                 | 14        | 0.12%   |
| Digma                          | 14        | 0.12%   |
| IBM                            | 13        | 0.11%   |
| BenQ                           | 13        | 0.11%   |
| Alienware                      | 13        | 0.11%   |
| Matsushita Electric Industrial | 11        | 0.09%   |
| Gigabyte Technology            | 11        | 0.09%   |
| HUAWEI                         | 10        | 0.08%   |
| Timi                           | 9         | 0.07%   |
| Chuwi                          | 8         | 0.07%   |
| Gateway                        | 7         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Pavilion g6                             | 177       | 1.47%   |
| Unknown                                    | 153       | 1.27%   |
| HP Pavilion dv6                            | 108       | 0.9%    |
| HP Notebook                                | 76        | 0.63%   |
| Acer Aspire V3-571G                        | 66        | 0.55%   |
| Lenovo G570 20079                          | 65        | 0.54%   |
| Lenovo B590 20206                          | 56        | 0.46%   |
| HP Pavilion dv7                            | 53        | 0.44%   |
| Packard Bell EasyNote TE11HC               | 52        | 0.43%   |
| Lenovo G50-30 80G0                         | 51        | 0.42%   |
| HP Pavilion g7                             | 51        | 0.42%   |
| Lenovo G500 20236                          | 48        | 0.4%    |
| HP Pavilion 15                             | 47        | 0.39%   |
| Dell Inspiron N5110                        | 46        | 0.38%   |
| Lenovo G50-45 80E3                         | 43        | 0.36%   |
| Acer Aspire 5750G                          | 43        | 0.36%   |
| Acer Aspire 5742G                          | 42        | 0.35%   |
| Toshiba Satellite C660                     | 41        | 0.34%   |
| Lenovo B570e HuronRiver Platform           | 38        | 0.31%   |
| Lenovo G580 20157                          | 37        | 0.31%   |
| Lenovo G580 20150                          | 37        | 0.31%   |
| HP G62                                     | 37        | 0.31%   |
| ASUS X101CH                                | 37        | 0.31%   |
| ASUS K53U                                  | 37        | 0.31%   |
| ASUS K50IJ                                 | 36        | 0.3%    |
| HP Laptop 15-bw0xx                         | 35        | 0.29%   |
| Acer Aspire E1-571G                        | 35        | 0.29%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 34        | 0.28%   |
| Lenovo B590 20208                          | 34        | 0.28%   |
| HP 15                                      | 33        | 0.27%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 32        | 0.27%   |
| Lenovo G560 20042                          | 32        | 0.27%   |
| Dell Inspiron 3542                         | 32        | 0.27%   |
| Dell Inspiron 3521                         | 32        | 0.27%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 31        | 0.26%   |
| Lenovo G505 20240                          | 31        | 0.26%   |
| ASUS X550CC                                | 30        | 0.25%   |
| Acer Extensa 5220                          | 30        | 0.25%   |
| Toshiba Satellite A200                     | 29        | 0.24%   |
| Lenovo V580c 20160                         | 29        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1321      | 10.95%  |
| HP Pavilion           | 622       | 5.16%   |
| Lenovo IdeaPad        | 487       | 4.04%   |
| Dell Inspiron         | 464       | 3.85%   |
| Toshiba Satellite     | 429       | 3.56%   |
| Lenovo ThinkPad       | 353       | 2.93%   |
| Packard Bell EasyNote | 206       | 1.71%   |
| HP Compaq             | 204       | 1.69%   |
| Dell Latitude         | 201       | 1.67%   |
| HP ProBook            | 188       | 1.56%   |
| Acer Extensa          | 165       | 1.37%   |
| Unknown               | 153       | 1.27%   |
| HP Laptop             | 113       | 0.94%   |
| Lenovo G580           | 100       | 0.83%   |
| HP EliteBook          | 95        | 0.79%   |
| Lenovo B590           | 94        | 0.78%   |
| Dell Vostro           | 86        | 0.71%   |
| Acer TravelMate       | 85        | 0.7%    |
| HP Notebook           | 76        | 0.63%   |
| Lenovo G570           | 66        | 0.55%   |
| ASUS VivoBook         | 66        | 0.55%   |
| Samsung 355V4C        | 54        | 0.45%   |
| HP ENVY               | 52        | 0.43%   |
| Lenovo G50-30         | 51        | 0.42%   |
| HP Mini               | 50        | 0.41%   |
| HP Presario           | 49        | 0.41%   |
| Lenovo G500           | 48        | 0.4%    |
| Fujitsu LIFEBOOK      | 48        | 0.4%    |
| Notebook W65          | 46        | 0.38%   |
| Samsung 300V3A        | 45        | 0.37%   |
| Lenovo G50-45         | 45        | 0.37%   |
| HP 250                | 40        | 0.33%   |
| Fujitsu Siemens AMILO | 40        | 0.33%   |
| Samsung 300E4A        | 38        | 0.31%   |
| Lenovo B570e          | 38        | 0.31%   |
| HP G62                | 37        | 0.31%   |
| ASUS X101CH           | 37        | 0.31%   |
| ASUS K53U             | 37        | 0.31%   |
| Samsung R540          | 36        | 0.3%    |
| ASUS K50IJ            | 36        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 2011      | 16.67%  |
| 2012    | 1768      | 14.65%  |
| 2010    | 1458      | 12.08%  |
| 2013    | 1148      | 9.52%   |
| 2009    | 952       | 7.89%   |
| 2008    | 936       | 7.76%   |
| 2007    | 757       | 6.27%   |
| 2014    | 733       | 6.08%   |
| 2015    | 546       | 4.53%   |
| 2016    | 369       | 3.06%   |
| 2006    | 353       | 2.93%   |
| 2017    | 282       | 2.34%   |
| 2018    | 231       | 1.91%   |
| 2019    | 145       | 1.2%    |
| 2020    | 117       | 0.97%   |
| 2021    | 98        | 0.81%   |
| 2005    | 88        | 0.73%   |
| 2022    | 31        | 0.26%   |
| 2004    | 22        | 0.18%   |
| Unknown | 14        | 0.12%   |
| 2003    | 4         | 0.03%   |
| 2002    | 1         | 0.01%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 12065     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 12063     | 99.96%  |
| Enabled  | 5         | 0.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12058     | 99.94%  |
| Yes  | 7         | 0.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 4505      | 35.66%  |
| 4.01-8.0   | 2337      | 18.5%   |
| 1.01-2.0   | 2030      | 16.07%  |
| 2.01-3.0   | 1425      | 11.28%  |
| 8.01-16.0  | 1316      | 10.42%  |
| 0.51-1.0   | 459       | 3.63%   |
| 16.01-24.0 | 271       | 2.15%   |
| Unknown    | 223       | 1.77%   |
| 32.01-64.0 | 33        | 0.26%   |
| 0.01-0.5   | 20        | 0.16%   |
| 24.01-32.0 | 14        | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 6510      | 46.8%   |
| 1.01-2.0   | 5367      | 38.59%  |
| 2.01-3.0   | 849       | 6.1%    |
| 0.01-0.5   | 612       | 4.4%    |
| Unknown    | 260       | 1.87%   |
| 3.01-4.0   | 194       | 1.39%   |
| 4.01-8.0   | 103       | 0.74%   |
| 8.01-16.0  | 12        | 0.09%   |
| 16.01-24.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 10004     | 79.82%  |
| 2       | 2213      | 17.66%  |
| 3       | 211       | 1.68%   |
| 0       | 92        | 0.73%   |
| 4       | 8         | 0.06%   |
| 5       | 4         | 0.03%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8103      | 66.04%  |
| No        | 4167      | 33.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 11478     | 95.05%  |
| No        | 598       | 4.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 11873     | 98.23%  |
| No        | 214       | 1.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7381      | 59.87%  |
| No        | 4948      | 40.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Russia      | 6610      | 51.89%  |
| Unknown     | 3872      | 30.4%   |
| Ukraine     | 530       | 4.16%   |
| Belarus     | 234       | 1.84%   |
| Germany     | 182       | 1.43%   |
| Poland      | 179       | 1.41%   |
| Kazakhstan  | 111       | 0.87%   |
| USA         | 94        | 0.74%   |
| Italy       | 85        | 0.67%   |
| France      | 73        | 0.57%   |
| Spain       | 54        | 0.42%   |
| Brazil      | 52        | 0.41%   |
| UK          | 36        | 0.28%   |
| Canada      | 36        | 0.28%   |
| Latvia      | 35        | 0.27%   |
| Romania     | 32        | 0.25%   |
| Bulgaria    | 28        | 0.22%   |
| Moldova     | 26        | 0.2%    |
| Turkey      | 22        | 0.17%   |
| Serbia      | 22        | 0.17%   |
| Belgium     | 18        | 0.14%   |
| India       | 16        | 0.13%   |
| Czechia     | 16        | 0.13%   |
| Uzbekistan  | 15        | 0.12%   |
| Slovakia    | 15        | 0.12%   |
| Mexico      | 15        | 0.12%   |
| Lithuania   | 15        | 0.12%   |
| Finland     | 15        | 0.12%   |
| Switzerland | 14        | 0.11%   |
| Israel      | 14        | 0.11%   |
| Colombia    | 14        | 0.11%   |
| Estonia     | 13        | 0.1%    |
| Chile       | 13        | 0.1%    |
| Hungary     | 12        | 0.09%   |
| Greece      | 12        | 0.09%   |
| Portugal    | 11        | 0.09%   |
| Austria     | 11        | 0.09%   |
| Indonesia   | 10        | 0.08%   |
| Azerbaijan  | 10        | 0.08%   |
| Australia   | 10        | 0.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 3873      | 28.47%  |
| Moscow           | 1133      | 8.33%   |
| St Petersburg    | 506       | 3.72%   |
| Pecherskoye      | 337       | 2.48%   |
| Novosibirsk      | 230       | 1.69%   |
| Krasnodar        | 229       | 1.68%   |
| Yekaterinburg    | 201       | 1.48%   |
| Nizhniy Novgorod | 155       | 1.14%   |
| Samara           | 137       | 1.01%   |
| Chelyabinsk      | 131       | 0.96%   |
| Voronezh         | 124       | 0.91%   |
| Perm             | 122       | 0.9%    |
| Rostov-on-Don    | 116       | 0.85%   |
| Saratov          | 95        | 0.7%    |
| Krasnoyarsk      | 95        | 0.7%    |
| Minsk            | 88        | 0.65%   |
| Khabarovsk       | 78        | 0.57%   |
| Kazan’         | 75        | 0.55%   |
| Omsk             | 69        | 0.51%   |
| Ufa              | 68        | 0.5%    |
| Volgograd        | 67        | 0.49%   |
| Kyiv             | 64        | 0.47%   |
| Tyumen           | 63        | 0.46%   |
| Barnaul          | 61        | 0.45%   |
| Kaliningrad      | 59        | 0.43%   |
| Irkutsk          | 59        | 0.43%   |
| Yaroslavl        | 58        | 0.43%   |
| Stavropol        | 53        | 0.39%   |
| Kemerovo         | 53        | 0.39%   |
| Simferopol       | 51        | 0.37%   |
| Surgut           | 49        | 0.36%   |
| Tula             | 48        | 0.35%   |
| Kirov            | 48        | 0.35%   |
| Vladivostok      | 47        | 0.35%   |
| Novokuznetsk     | 46        | 0.34%   |
| Vitebsk          | 44        | 0.32%   |
| Penza            | 44        | 0.32%   |
| Sevastopol       | 43        | 0.32%   |
| Belgorod         | 41        | 0.3%    |
| Warsaw           | 40        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives  | Percent |
|---------------------|-----------|---------|---------|
| WDC                 | 2986      | 4144    | 20.48%  |
| Seagate             | 2957      | 4027    | 20.28%  |
| Toshiba             | 1655      | 2215    | 11.35%  |
| Hitachi             | 1536      | 2080    | 10.53%  |
| Samsung Electronics | 882       | 1210    | 6.05%   |
| HGST                | 725       | 1079    | 4.97%   |
| Unknown             | 697       | 891     | 4.78%   |
| Kingston            | 546       | 701     | 3.74%   |
| SanDisk             | 290       | 395     | 1.99%   |
| Fujitsu             | 253       | 309     | 1.73%   |
| China               | 147       | 188     | 1.01%   |
| Intel               | 134       | 169     | 0.92%   |
| HUAWEI              | 132       | 151     | 0.91%   |
| A-DATA Technology   | 127       | 168     | 0.87%   |
| Crucial             | 114       | 135     | 0.78%   |
| SPCC                | 107       | 164     | 0.73%   |
| OCZ                 | 100       | 139     | 0.69%   |
| SK hynix            | 98        | 132     | 0.67%   |
| Plextor             | 77        | 102     | 0.53%   |
| Smartbuy            | 76        | 93      | 0.52%   |
| Transcend           | 62        | 93      | 0.43%   |
| KingSpec            | 62        | 92      | 0.43%   |
| Micron Technology   | 49        | 62      | 0.34%   |
| GOODRAM             | 49        | 56      | 0.34%   |
| Apacer              | 46        | 58      | 0.32%   |
| Corsair             | 45        | 63      | 0.31%   |
| Patriot             | 41        | 51      | 0.28%   |
| AMD                 | 40        | 47      | 0.27%   |
| TF CARD             | 37        | 52      | 0.25%   |
| LITEONIT            | 29        | 43      | 0.2%    |
| KingDian            | 26        | 38      | 0.18%   |
| Apple               | 24        | 30      | 0.16%   |
| Netac               | 19        | 22      | 0.13%   |
| LITEON              | 19        | 26      | 0.13%   |
| Gigabyte Technology | 18        | 22      | 0.12%   |
| Mass                | 16        | Unknown | 0.11%   |
| ZTE                 | 15        | 18      | 0.1%    |
| JMicron Technology  | 15        | 14      | 0.1%    |
| Kingmax             | 13        | 29      | 0.09%   |
| KIOXIA              | 12        | 12      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 367       | 2.47%   |
| Seagate ST500LT012-1DG142 500GB     | 343       | 2.31%   |
| Seagate ST9500325AS 500GB           | 305       | 2.05%   |
| Toshiba MQ01ABF050 500GB            | 275       | 1.85%   |
| Seagate ST9320325AS 320GB           | 215       | 1.45%   |
| Unknown xD/SD/M.S.                  | 200       | 1.35%   |
| HGST HTS545050A7E680 500GB          | 192       | 1.29%   |
| Seagate ST500LT012-9WS142 500GB     | 163       | 1.1%    |
| Hitachi HTS543232A7A384 320GB       | 163       | 1.1%    |
| Seagate ST9250315AS 250GB           | 152       | 1.02%   |
| Toshiba MQ01ABD100 1TB              | 148       | 1%      |
| Seagate ST500LM012 HN-M500MBB 500GB | 138       | 0.93%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 129       | 0.87%   |
| Seagate ST320LT020-9YG142 320GB     | 127       | 0.86%   |
| Hitachi HTS547550A9E384 500GB       | 119       | 0.8%    |
| HGST HTS545050A7E380 500GB          | 117       | 0.79%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 111       | 0.75%   |
| Hitachi HTS545025B9A300 250GB       | 111       | 0.75%   |
| HGST HTS541010A9E680 1TB            | 109       | 0.73%   |
| Kingston SV300S37A120G 120GB SSD    | 103       | 0.69%   |
| Hitachi HTS547575A9E384 752GB       | 102       | 0.69%   |
| Toshiba MQ01ABD050 500GB            | 92        | 0.62%   |
| Hitachi HTS545050A7E380 500GB       | 92        | 0.62%   |
| Hitachi HTS545032B9A300 320GB       | 91        | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB            | 89        | 0.6%    |
| HGST HTS721010A9E630 1TB            | 89        | 0.6%    |
| Hitachi HTS545050B9A300 500GB       | 81        | 0.55%   |
| HGST HTS725050A7E630 500GB          | 79        | 0.53%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 77        | 0.52%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 77        | 0.52%   |
| Toshiba MQ01ABD075 752GB            | 76        | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB      | 75        | 0.51%   |
| Samsung HM321HI 320GB               | 72        | 0.48%   |
| HUAWEI TF CARD Storage 16GB         | 70        | 0.47%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 68        | 0.46%   |
| Toshiba MQ01ABD032 320GB            | 68        | 0.46%   |
| Samsung HM250HI 250GB               | 65        | 0.44%   |
| Kingston SA400S37120G 120GB SSD     | 65        | 0.44%   |
| Hitachi HTS541612J9SA00 119GB       | 59        | 0.4%    |
| WDC WD5000LPCX-24VHAT0 500GB        | 57        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2945      | 4004   | 28.67%  |
| WDC                 | 2819      | 3911   | 27.45%  |
| Toshiba             | 1569      | 2101   | 15.28%  |
| Hitachi             | 1536      | 2080   | 14.95%  |
| HGST                | 725       | 1079   | 7.06%   |
| Samsung Electronics | 379       | 482    | 3.69%   |
| Fujitsu             | 252       | 307    | 2.45%   |
| IBM/Hitachi         | 12        | 12     | 0.12%   |
| Unknown             | 10        | 13     | 0.1%    |
| Apple               | 5         | 5      | 0.05%   |
| JMicron Technology  | 2         | 2      | 0.02%   |
| HGST HTS            | 2         | 2      | 0.02%   |
| ASMT                | 2         | 3      | 0.02%   |
| ASMedia             | 2         | 3      | 0.02%   |
| ZALMAN              | 1         | 1      | 0.01%   |
| WD MediaMax         | 1         | 2      | 0.01%   |
| SILICONMOTION       | 1         | 1      | 0.01%   |
| SABRENT             | 1         | 1      | 0.01%   |
| PHD 3.0             | 1         | 1      | 0.01%   |
| OEM                 | 1         | 2      | 0.01%   |
| Maxtor              | 1         | 1      | 0.01%   |
| MARSHAL             | 1         | 2      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM                 | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 518       | 662    | 17.28%  |
| Samsung Electronics | 421       | 592    | 14.04%  |
| SanDisk             | 245       | 342    | 8.17%   |
| China               | 147       | 188    | 4.9%    |
| WDC                 | 135       | 159    | 4.5%    |
| A-DATA Technology   | 117       | 158    | 3.9%    |
| Crucial             | 111       | 132    | 3.7%    |
| SPCC                | 107       | 164    | 3.57%   |
| Intel               | 103       | 128    | 3.44%   |
| OCZ                 | 100       | 139    | 3.34%   |
| Plextor             | 77        | 102    | 2.57%   |
| Toshiba             | 73        | 94     | 2.43%   |
| Smartbuy            | 73        | 90     | 2.43%   |
| KingSpec            | 62        | 92     | 2.07%   |
| Transcend           | 61        | 91     | 2.03%   |
| GOODRAM             | 49        | 56     | 1.63%   |
| Corsair             | 45        | 63     | 1.5%    |
| Patriot             | 41        | 51     | 1.37%   |
| Apacer              | 41        | 52     | 1.37%   |
| SK hynix            | 38        | 51     | 1.27%   |
| AMD                 | 37        | 44     | 1.23%   |
| LITEONIT            | 29        | 43     | 0.97%   |
| Micron Technology   | 27        | 36     | 0.9%    |
| KingDian            | 25        | 37     | 0.83%   |
| LITEON              | 19        | 26     | 0.63%   |
| Apple               | 19        | 25     | 0.63%   |
| Netac               | 17        | 20     | 0.57%   |
| Kingmax             | 13        | 29     | 0.43%   |
| Team                | 11        | 13     | 0.37%   |
| KingFast            | 10        | 12     | 0.33%   |
| Gigabyte Technology | 10        | 12     | 0.33%   |
| PNY                 | 9         | 12     | 0.3%    |
| JMicron Technology  | 9         | 10     | 0.3%    |
| Zheino              | 8         | 10     | 0.27%   |
| ASUS-PHISON         | 8         | 21     | 0.27%   |
| XrayDisk            | 7         | 8      | 0.23%   |
| TO Exter            | 7         | 9      | 0.23%   |
| Londisk             | 7         | 9      | 0.23%   |
| OCZ-VERTEX3         | 6         | 8      | 0.2%    |
| Mushkin             | 6         | 6      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 9893      | 14019  | 70.68%  |
| SSD     | 2800      | 3989   | 20%     |
| MMC     | 531       | 712    | 3.79%   |
| Unknown | 421       | 495    | 3.01%   |
| NVMe    | 352       | 503    | 2.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11583     | 17855  | 89.09%  |
| SAS  | 539       | 653    | 4.15%   |
| MMC  | 531       | 712    | 4.08%   |
| NVMe | 348       | 498    | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9965      | 14686  | 81.65%  |
| 0.51-1.0   | 2199      | 3268   | 18.02%  |
| 1.01-2.0   | 32        | 39     | 0.26%   |
| 4.01-10.0  | 4         | 6      | 0.03%   |
| 3.01-4.0   | 3         | 7      | 0.02%   |
| 2.01-3.0   | 2         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 3596      | 26.19%  |
| 251-500        | 3567      | 25.98%  |
| 1-20           | 2046      | 14.9%   |
| 51-100         | 1442      | 10.5%   |
| 21-50          | 1275      | 9.29%   |
| 501-1000       | 1231      | 8.97%   |
| Unknown        | 267       | 1.94%   |
| 1001-2000      | 249       | 1.81%   |
| 2001-3000      | 36        | 0.26%   |
| More than 3000 | 20        | 0.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 9339      | 67.57%  |
| 21-50          | 1376      | 9.96%   |
| 101-250        | 1002      | 7.25%   |
| 51-100         | 966       | 6.99%   |
| 251-500        | 565       | 4.09%   |
| Unknown        | 267       | 1.93%   |
| 501-1000       | 240       | 1.74%   |
| 1001-2000      | 50        | 0.36%   |
| More than 3000 | 9         | 0.07%   |
| 2001-3000      | 8         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 219       | 306    | 4.81%   |
| Seagate ST500LT012-9WS142 500GB     | 158       | 202    | 3.47%   |
| Seagate ST9320325AS 320GB           | 125       | 159    | 2.75%   |
| Seagate ST9250315AS 250GB           | 101       | 126    | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 92        | 109    | 2.02%   |
| HGST HTS545050A7E680 500GB          | 91        | 120    | 2%      |
| Seagate ST500LT012-1DG142 500GB     | 86        | 106    | 1.89%   |
| Seagate ST320LT020-9YG142 320GB     | 77        | 111    | 1.69%   |
| Hitachi HTS543232A7A384 320GB       | 70        | 87     | 1.54%   |
| HGST HTS545050A7E380 500GB          | 62        | 98     | 1.36%   |
| Hitachi HTS545025B9A300 250GB       | 60        | 75     | 1.32%   |
| Seagate ST320LT012-9WS14C 320GB     | 52        | 76     | 1.14%   |
| Toshiba MQ01ABD050 500GB            | 50        | 65     | 1.1%    |
| Hitachi HTS547575A9E384 752GB       | 50        | 70     | 1.1%    |
| Hitachi HTS547550A9E384 500GB       | 50        | 69     | 1.1%    |
| Hitachi HTS541612J9SA00 119GB       | 50        | 63     | 1.1%    |
| Seagate ST9500420AS 500GB           | 45        | 63     | 0.99%   |
| Hitachi HTS545050B9A300 500GB       | 44        | 62     | 0.97%   |
| Hitachi HTS545050A7E380 500GB       | 44        | 57     | 0.97%   |
| Hitachi HTS545032B9A300 320GB       | 43        | 52     | 0.95%   |
| Samsung Electronics HM160HI 160GB   | 41        | 51     | 0.9%    |
| Toshiba MQ01ABF050 500GB            | 40        | 45     | 0.88%   |
| Hitachi HTS541680J9SA00 80GB        | 39        | 51     | 0.86%   |
| Toshiba MK3265GSX 320GB             | 37        | 50     | 0.81%   |
| Seagate ST9160821AS 160GB           | 33        | 41     | 0.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 33        | 43     | 0.73%   |
| Hitachi HTS542512K9SA00 120GB       | 33        | 43     | 0.73%   |
| HGST HTS541010A9E680 1TB            | 31        | 53     | 0.68%   |
| Hitachi HTS542516K9SA00 160GB       | 28        | 45     | 0.62%   |
| Hitachi HTS543216L9A300 160GB       | 26        | 27     | 0.57%   |
| Hitachi HTS542525K9SA00 250GB       | 26        | 33     | 0.57%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 24        | 30     | 0.53%   |
| WDC WD2500BEVT-22A23T0 250GB        | 23        | 28     | 0.51%   |
| Toshiba MQ01ABD100 1TB              | 23        | 35     | 0.51%   |
| Toshiba MK3259GSXP 320GB            | 23        | 39     | 0.51%   |
| Seagate ST9160310AS 160GB           | 23        | 28     | 0.51%   |
| Samsung Electronics HM321HI 320GB   | 23        | 31     | 0.51%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 22        | 27     | 0.48%   |
| Toshiba MK2555GSX 250GB             | 21        | 24     | 0.46%   |
| Seagate ST9250827AS 250GB           | 21        | 25     | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1401      | 1821   | 30.98%  |
| Hitachi             | 877       | 1146   | 19.39%  |
| WDC                 | 713       | 928    | 15.76%  |
| Toshiba             | 662       | 866    | 14.64%  |
| HGST                | 256       | 366    | 5.66%   |
| Samsung Electronics | 183       | 226    | 4.05%   |
| Fujitsu             | 105       | 129    | 2.32%   |
| Kingston            | 63        | 77     | 1.39%   |
| SanDisk             | 41        | 49     | 0.91%   |
| Intel               | 21        | 26     | 0.46%   |
| SPCC                | 18        | 19     | 0.4%    |
| OCZ                 | 18        | 28     | 0.4%    |
| A-DATA Technology   | 17        | 25     | 0.38%   |
| China               | 15        | 20     | 0.33%   |
| Crucial             | 14        | 17     | 0.31%   |
| Corsair             | 12        | 12     | 0.27%   |
| IBM/Hitachi         | 11        | 11     | 0.24%   |
| SK hynix            | 10        | 14     | 0.22%   |
| KingSpec            | 10        | 18     | 0.22%   |
| LITEONIT            | 9         | 14     | 0.2%    |
| Plextor             | 8         | 9      | 0.18%   |
| Transcend           | 5         | 7      | 0.11%   |
| Micron Technology   | 5         | 10     | 0.11%   |
| Kingmax             | 5         | 5      | 0.11%   |
| AMD                 | 5         | 7      | 0.11%   |
| Mushkin             | 3         | 3      | 0.07%   |
| Apple               | 3         | 3      | 0.07%   |
| Team                | 2         | 2      | 0.04%   |
| SSSTC               | 2         | 2      | 0.04%   |
| PNY                 | 2         | 4      | 0.04%   |
| Patriot             | 2         | 2      | 0.04%   |
| OCZ-VERTEX3         | 2         | 3      | 0.04%   |
| Netac               | 2         | 3      | 0.04%   |
| KingFast            | 2         | 2      | 0.04%   |
| KingDian            | 2         | 3      | 0.04%   |
| Zheino              | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |
| SMI                 | 1         | 1      | 0.02%   |
| Smartbuy            | 1         | 1      | 0.02%   |
| SemsoTai            | 1         | 1      | 0.02%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1401      | 1821   | 33.54%  |
| Hitachi             | 877       | 1146   | 21%     |
| WDC                 | 697       | 912    | 16.69%  |
| Toshiba             | 657       | 861    | 15.73%  |
| HGST                | 256       | 366    | 6.13%   |
| Samsung Electronics | 170       | 212    | 4.07%   |
| Fujitsu             | 105       | 129    | 2.51%   |
| IBM/Hitachi         | 11        | 11     | 0.26%   |
| MARSHAL             | 1         | 2      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| Apple               | 1         | 1      | 0.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4116      | 5462   | 92.31%  |
| SSD  | 340       | 432    | 7.63%   |
| NVMe | 3         | 3      | 0.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 6         | 8      | 4.26%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 5         | 6      | 3.55%   |
| Samsung Electronics HM321HI 320GB  | 5         | 6      | 3.55%   |
| HGST HTS545050A7E680 500GB         | 5         | 5      | 3.55%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 2.84%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 2.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 2.84%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 3      | 2.13%   |
| Toshiba MQ01ABD050 500GB           | 3         | 3      | 2.13%   |
| Toshiba MK6465GSX 640GB            | 3         | 5      | 2.13%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 2.13%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 2.13%   |
| Samsung Electronics HM160HI 160GB  | 3         | 3      | 2.13%   |
| HGST HTS721010A9E630 1TB           | 3         | 4      | 2.13%   |
| WDC WD1600BEVS-22RST0 160GB        | 2         | 2      | 1.42%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 1.42%   |
| Toshiba MK2565GSX 250GB            | 2         | 2      | 1.42%   |
| Seagate ST9250315AS 250GB          | 2         | 2      | 1.42%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 2      | 1.42%   |
| Hitachi HTS547575A9E384 752GB      | 2         | 2      | 1.42%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 1.42%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.42%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 2      | 1.42%   |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 1.42%   |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 1.42%   |
| WDC WD800BEVS-75RST0 80GB          | 1         | 2      | 0.71%   |
| WDC WD800BEVS-22RST0 80GB          | 1         | 1      | 0.71%   |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 1      | 0.71%   |
| WDC WD7500BPVT-22HXZT1 752GB       | 1         | 1      | 0.71%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 1      | 0.71%   |
| WDC WD5000BPVT-80HXZT3 500GB       | 1         | 1      | 0.71%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 0.71%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 0.71%   |
| WDC WD5000BPVT-00HXZT1 500GB       | 1         | 1      | 0.71%   |
| WDC WD5000BEVT-35ZAT0 500GB        | 1         | 1      | 0.71%   |
| WDC WD5000BEVT-26A0RT0 500GB       | 1         | 1      | 0.71%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 0.71%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.71%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 0.71%   |
| WDC WD3200BEVT-24A23T0 320GB       | 1         | 1      | 0.71%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 42     | 27.66%  |
| Toshiba             | 28        | 34     | 19.86%  |
| Seagate             | 27        | 31     | 19.15%  |
| Samsung Electronics | 17        | 18     | 12.06%  |
| Hitachi             | 14        | 15     | 9.93%   |
| HGST                | 12        | 14     | 8.51%   |
| Fujitsu             | 2         | 2      | 1.42%   |
| Maxtor              | 1         | 1      | 0.71%   |
| Apple               | 1         | 2      | 0.71%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 7840      | 11850  | 57.28%  |
| Malfunc  | 4411      | 5897   | 32.23%  |
| Detected | 1294      | 1812   | 9.45%   |
| Failed   | 141       | 159    | 1.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 9272      | 75.7%   |
| AMD                              | 2240      | 18.29%  |
| Nvidia                           | 190       | 1.55%   |
| Silicon Integrated Systems [SiS] | 117       | 0.96%   |
| Samsung Electronics              | 100       | 0.82%   |
| SanDisk                          | 57        | 0.47%   |
| SK hynix                         | 45        | 0.37%   |
| JMicron Technology               | 41        | 0.33%   |
| Kingston Technology Company      | 28        | 0.23%   |
| VIA Technologies                 | 26        | 0.21%   |
| Micron Technology                | 22        | 0.18%   |
| Phison Electronics               | 17        | 0.14%   |
| Silicon Motion                   | 14        | 0.11%   |
| KIOXIA                           | 13        | 0.11%   |
| Union Memory (Shenzhen)          | 11        | 0.09%   |
| Toshiba America Info Systems     | 10        | 0.08%   |
| Solid State Storage Technology   | 9         | 0.07%   |
| ADATA Technology                 | 9         | 0.07%   |
| Realtek Semiconductor            | 7         | 0.06%   |
| Silicon Image                    | 4         | 0.03%   |
| Micron/Crucial Technology        | 3         | 0.02%   |
| Shenzhen Longsys Electronics     | 2         | 0.02%   |
| Netac Technology                 | 2         | 0.02%   |
| Marvell Technology Group         | 2         | 0.02%   |
| Zhaoxin                          | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.01%   |
| Lite-On Technology               | 1         | 0.01%   |
| Lenovo                           | 1         | 0.01%   |
| ASMedia Technology               | 1         | 0.01%   |
| Apple                            | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 1694      | 12.01%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1203      | 8.53%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1159      | 8.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 845       | 5.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 706       | 5.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 694       | 4.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 595       | 4.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 588       | 4.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 473       | 3.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 420       | 2.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 329       | 2.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 326       | 2.31%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 322       | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 310       | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 215       | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 208       | 1.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 192       | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 191       | 1.35%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 185       | 1.31%   |
| AMD SB600 IDE                                                                          | 182       | 1.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 180       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 175       | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 173       | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 150       | 1.06%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 123       | 0.87%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 122       | 0.87%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 110       | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 105       | 0.74%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 99        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 84        | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 83        | 0.59%   |
| AMD FCH IDE Controller                                                                 | 79        | 0.56%   |
| AMD IXP SB4x0 IDE Controller                                                           | 77        | 0.55%   |
| Nvidia MCP79 AHCI Controller                                                           | 75        | 0.53%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 70        | 0.5%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 67        | 0.48%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 67        | 0.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 66        | 0.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 64        | 0.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 60        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 10213     | 76.51%  |
| IDE  | 2541      | 19.04%  |
| NVMe | 351       | 2.63%   |
| RAID | 243       | 1.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 9797      | 81.2%   |
| AMD          | 2260      | 18.73%  |
| CentaurHauls | 9         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz           | 211       | 1.74%   |
| Intel Atom CPU N450 @ 1.66GHz               | 168       | 1.39%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 161       | 1.33%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 154       | 1.27%   |
| Intel Atom CPU N270 @ 1.60GHz               | 154       | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 151       | 1.25%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 149       | 1.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 143       | 1.18%   |
| AMD E-450 APU with Radeon HD Graphics       | 136       | 1.12%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 135       | 1.12%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 128       | 1.06%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 127       | 1.05%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 127       | 1.05%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 124       | 1.02%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 123       | 1.02%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 122       | 1.01%   |
| Intel Atom CPU N455 @ 1.66GHz               | 112       | 0.93%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 104       | 0.86%   |
| Intel Atom CPU N570 @ 1.66GHz               | 100       | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 98        | 0.81%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 97        | 0.8%    |
| Intel Core i3-2330M CPU @ 2.20GHz           | 88        | 0.73%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 85        | 0.7%    |
| AMD A10-4600M APU with Radeon HD Graphics   | 80        | 0.66%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 79        | 0.65%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 78        | 0.64%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 78        | 0.64%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 77        | 0.64%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 75        | 0.62%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 75        | 0.62%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 73        | 0.6%    |
| Intel Core i5-3337U CPU @ 1.80GHz           | 72        | 0.59%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 69        | 0.57%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 68        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 67        | 0.55%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 66        | 0.55%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 66        | 0.55%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 65        | 0.54%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 65        | 0.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 64        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 1994      | 16.48%  |
| Intel Core i3                  | 1593      | 13.17%  |
| Intel Celeron                  | 1023      | 8.46%   |
| Intel Pentium                  | 1018      | 8.42%   |
| Intel Core 2 Duo               | 976       | 8.07%   |
| Intel Atom                     | 976       | 8.07%   |
| Intel Core i7                  | 868       | 7.18%   |
| Intel Pentium Dual-Core        | 318       | 2.63%   |
| AMD A6                         | 254       | 2.1%    |
| AMD E                          | 245       | 2.03%   |
| AMD A8                         | 194       | 1.6%    |
| AMD A4                         | 187       | 1.55%   |
| Intel Genuine                  | 186       | 1.54%   |
| Intel Pentium Dual             | 170       | 1.41%   |
| Intel Core 2                   | 170       | 1.41%   |
| AMD E1                         | 163       | 1.35%   |
| AMD A10                        | 153       | 1.26%   |
| Intel Celeron M                | 136       | 1.12%   |
| AMD Turion 64 X2 Mobile        | 115       | 0.95%   |
| Intel Celeron Dual-Core        | 114       | 0.94%   |
| AMD Phenom II                  | 99        | 0.82%   |
| Intel Pentium M                | 97        | 0.8%    |
| AMD E2                         | 96        | 0.79%   |
| AMD Athlon II                  | 91        | 0.75%   |
| AMD Ryzen 5                    | 69        | 0.57%   |
| Other                          | 66        | 0.55%   |
| AMD C-60                       | 57        | 0.47%   |
| AMD Athlon X2                  | 52        | 0.43%   |
| Intel Core Duo                 | 45        | 0.37%   |
| AMD C-50                       | 38        | 0.31%   |
| AMD Athlon 64 X2               | 38        | 0.31%   |
| AMD Turion X2 Dual-Core Mobile | 35        | 0.29%   |
| Intel Celeron D                | 31        | 0.26%   |
| AMD Athlon                     | 31        | 0.26%   |
| Intel Pentium Silver           | 30        | 0.25%   |
| AMD Ryzen 3                    | 30        | 0.25%   |
| AMD Turion II Dual-Core        | 29        | 0.24%   |
| AMD Turion II                  | 29        | 0.24%   |
| AMD Ryzen 7                    | 27        | 0.22%   |
| AMD Turion 64 Mobile           | 25        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 8704      | 71.19%  |
| 4       | 1698      | 13.89%  |
| 1       | 1093      | 8.94%   |
| Unknown | 591       | 4.83%   |
| 6       | 76        | 0.62%   |
| 3       | 37        | 0.3%    |
| 8       | 25        | 0.2%    |
| 192     | 2         | 0.02%   |
| 10      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 11999     | 99.17%  |
| Unknown | 85        | 0.7%    |
| 2       | 10        | 0.08%   |
| 4       | 6         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 6079      | 49.57%  |
| 2       | 5594      | 45.61%  |
| Unknown | 591       | 4.82%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11122     | 91.08%  |
| 32-bit         | 650       | 5.32%   |
| Unknown        | 357       | 2.92%   |
| 64-bit         | 82        | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 1751      | 14.26%  |
| 0x306a9    | 1367      | 11.13%  |
| 0x1067a    | 772       | 6.29%   |
| 0x20655    | 656       | 5.34%   |
| 0x6fd      | 565       | 4.6%    |
| Unknown    | 522       | 4.25%   |
| 0x106ca    | 452       | 3.68%   |
| 0x40651    | 424       | 3.45%   |
| 0x30678    | 364       | 2.96%   |
| 0x306c3    | 328       | 2.67%   |
| 0x10676    | 245       | 2%      |
| 0x20652    | 225       | 1.83%   |
| 0x05000119 | 220       | 1.79%   |
| 0x06001119 | 210       | 1.71%   |
| 0x010000c8 | 206       | 1.68%   |
| 0x106c2    | 203       | 1.65%   |
| 0x30661    | 199       | 1.62%   |
| 0x306d4    | 191       | 1.56%   |
| 0x03000027 | 172       | 1.4%    |
| 0x406e3    | 170       | 1.38%   |
| 0x10661    | 165       | 1.34%   |
| 0x07030105 | 159       | 1.29%   |
| 0x6f6      | 138       | 1.12%   |
| 0x406c4    | 136       | 1.11%   |
| 0x6e8      | 130       | 1.06%   |
| 0x406c3    | 130       | 1.06%   |
| 0x6d8      | 119       | 0.97%   |
| 0x806e9    | 107       | 0.87%   |
| 0x6ec      | 97        | 0.79%   |
| 0x0700010f | 86        | 0.7%    |
| 0x806ea    | 84        | 0.68%   |
| 0x6fb      | 77        | 0.63%   |
| 0x05000101 | 75        | 0.61%   |
| 0x906ea    | 63        | 0.51%   |
| 0x506c9    | 63        | 0.51%   |
| 0x05000029 | 63        | 0.51%   |
| 0x02000032 | 62        | 0.5%    |
| 0x06006705 | 60        | 0.49%   |
| 0x010000b6 | 58        | 0.47%   |
| 0x02000057 | 56        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 1763      | 14.56%  |
| IvyBridge        | 1376      | 11.36%  |
| Core             | 1056      | 8.72%   |
| Penryn           | 1016      | 8.39%   |
| Westmere         | 893       | 7.37%   |
| Bonnell          | 814       | 6.72%   |
| Haswell          | 763       | 6.3%    |
| Silvermont       | 678       | 5.6%    |
| Bobcat           | 424       | 3.5%    |
| KabyLake         | 355       | 2.93%   |
| P6               | 334       | 2.76%   |
| K10              | 324       | 2.68%   |
| Piledriver       | 265       | 2.19%   |
| K8 Hammer        | 224       | 1.85%   |
| K10 Llano        | 214       | 1.77%   |
| Skylake          | 212       | 1.75%   |
| Puma             | 206       | 1.7%    |
| Broadwell        | 196       | 1.62%   |
| Unknown          | 191       | 1.58%   |
| Jaguar           | 143       | 1.18%   |
| Excavator        | 135       | 1.11%   |
| K8 & K10 hybrid  | 118       | 0.97%   |
| Goldmont         | 66        | 0.55%   |
| Goldmont plus    | 65        | 0.54%   |
| Zen+             | 60        | 0.5%    |
| Nehalem          | 45        | 0.37%   |
| TigerLake        | 29        | 0.24%   |
| Zen 2            | 27        | 0.22%   |
| IceLake          | 23        | 0.19%   |
| Zen 3            | 22        | 0.18%   |
| Zen              | 21        | 0.17%   |
| CometLake        | 16        | 0.13%   |
| Steamroller      | 14        | 0.12%   |
| NetBurst         | 11        | 0.09%   |
| Tremont          | 10        | 0.08%   |
| Alderlake Hybrid | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7907      | 52.07%  |
| AMD                              | 3707      | 24.41%  |
| Nvidia                           | 3495      | 23.01%  |
| Silicon Integrated Systems [SiS] | 54        | 0.36%   |
| VIA Technologies                 | 20        | 0.13%   |
| Zhaoxin                          | 1         | 0.01%   |
| Trident Microsystems             | 1         | 0.01%   |
| ATI Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1592      | 9.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1335      | 8.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 578       | 3.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 504       | 3.04%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 446       | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 424       | 2.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 413       | 2.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 408       | 2.46%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 371       | 2.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 365       | 2.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 365       | 2.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 314       | 1.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 274       | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 270       | 1.63%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 234       | 1.41%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 226       | 1.36%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 208       | 1.25%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 197       | 1.19%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 178       | 1.07%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 174       | 1.05%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 163       | 0.98%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 161       | 0.97%   |
| Intel HD Graphics 5500                                                                   | 159       | 0.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 149       | 0.9%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 144       | 0.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 139       | 0.84%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 124       | 0.75%   |
| Nvidia GM108M [GeForce 840M]                                                             | 121       | 0.73%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 118       | 0.71%   |
| Intel HD Graphics 620                                                                    | 115       | 0.69%   |
| Nvidia GT218M [GeForce 310M]                                                             | 114       | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 114       | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 112       | 0.68%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 105       | 0.63%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 103       | 0.62%   |
| Nvidia GF119M [GeForce 610M]                                                             | 101       | 0.61%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 101       | 0.61%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 97        | 0.59%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 95        | 0.57%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                                    | 90        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 4833      | 39.93%  |
| Intel + Nvidia           | 2451      | 20.25%  |
| 1 x AMD                  | 2412      | 19.93%  |
| 1 x Nvidia               | 1012      | 8.36%   |
| 2 x AMD                  | 641       | 5.3%    |
| Intel + AMD              | 632       | 5.22%   |
| 1 x SiS                  | 54        | 0.45%   |
| AMD + Nvidia             | 31        | 0.26%   |
| 1 x VIA                  | 20        | 0.17%   |
| Other                    | 12        | 0.1%    |
| 2 x Nvidia               | 4         | 0.03%   |
| 1 x Zhaoxin              | 1         | 0.01%   |
| 1 x Trident Microsystems | 1         | 0.01%   |
| Intel + 2 x Nvidia       | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 11061     | 88.74%  |
| Proprietary | 788       | 6.32%   |
| Unknown     | 616       | 4.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 4990      | 39.46%  |
| 0.01-0.5   | 3822      | 30.23%  |
| Unknown    | 2349      | 18.58%  |
| 0.51-1.0   | 873       | 6.9%    |
| 3.01-4.0   | 574       | 4.54%   |
| 5.01-6.0   | 15        | 0.12%   |
| 2.01-3.0   | 14        | 0.11%   |
| 7.01-8.0   | 7         | 0.06%   |
| 8.01-16.0  | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2747      | 22.74%  |
| LG Display              | 2204      | 18.25%  |
| Samsung Electronics     | 2172      | 17.98%  |
| Chi Mei Optoelectronics | 1163      | 9.63%   |
| Chimei Innolux          | 961       | 7.96%   |
| BOE                     | 624       | 5.17%   |
| LG Philips              | 417       | 3.45%   |
| Lenovo                  | 276       | 2.29%   |
| HannStar                | 276       | 2.29%   |
| CPT                     | 181       | 1.5%    |
| InfoVision              | 122       | 1.01%   |
| Goldstar                | 97        | 0.8%    |
| Apple                   | 79        | 0.65%   |
| Sony                    | 64        | 0.53%   |
| BenQ                    | 56        | 0.46%   |
| Acer                    | 56        | 0.46%   |
| Quanta Display          | 48        | 0.4%    |
| InnoLux Display         | 48        | 0.4%    |
| Dell                    | 46        | 0.38%   |
| Philips                 | 42        | 0.35%   |
| Toshiba                 | 33        | 0.27%   |
| Hewlett-Packard         | 33        | 0.27%   |
| Ancor Communications    | 33        | 0.27%   |
| Sharp                   | 31        | 0.26%   |
| PANDA                   | 30        | 0.25%   |
| ViewSonic               | 28        | 0.23%   |
| AOC                     | 23        | 0.19%   |
| NEC Computers           | 18        | 0.15%   |
| Nvidia                  | 16        | 0.13%   |
| Panasonic               | 12        | 0.1%    |
| Iiyama                  | 11        | 0.09%   |
| IBM                     | 7         | 0.06%   |
| CSO                     | 7         | 0.06%   |
| ___                     | 6         | 0.05%   |
| MStar                   | 6         | 0.05%   |
| Unknown                 | 5         | 0.04%   |
| MiTAC                   | 5         | 0.04%   |
| S2-Tek                  | 4         | 0.03%   |
| Fujitsu Siemens         | 4         | 0.03%   |
| CVT                     | 4         | 0.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 327       | 2.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 306       | 2.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 241       | 1.98%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 211       | 1.73%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 154       | 1.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 133       | 1.09%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 128       | 1.05%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                  | 119       | 0.98%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 115       | 0.95%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 105       | 0.86%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 103       | 0.85%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 96        | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 95        | 0.78%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 220x130mm 10.1-inch             | 95        | 0.78%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 92        | 0.76%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 89        | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 75        | 0.62%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 75        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 69        | 0.57%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 68        | 0.56%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 66        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 65        | 0.53%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 62        | 0.51%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 62        | 0.51%   |
| AU Optronics LCD Monitor AUO139E 1600x900 380x210mm 17.1-inch             | 60        | 0.49%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                  | 58        | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 57        | 0.47%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch             | 57        | 0.47%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch      | 56        | 0.46%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch               | 55        | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 55        | 0.45%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 54        | 0.44%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch               | 53        | 0.44%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 52        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch           | 52        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 51        | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 51        | 0.42%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 50        | 0.41%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 50        | 0.41%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 49        | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 6424      | 53.61%  |
| 1920x1080 (FHD)    | 1664      | 13.89%  |
| 1280x800 (WXGA)    | 1273      | 10.62%  |
| 1600x900 (HD+)     | 1034      | 8.63%   |
| 1024x600           | 588       | 4.91%   |
| 1440x900 (WXGA+)   | 290       | 2.42%   |
| 1280x1024 (SXGA)   | 144       | 1.2%    |
| 1920x1200 (WUXGA)  | 117       | 0.98%   |
| 1680x1050 (WSXGA+) | 110       | 0.92%   |
| 3840x2160 (4K)     | 91        | 0.76%   |
| 1024x768 (XGA)     | 60        | 0.5%    |
| 1360x768           | 22        | 0.18%   |
| 1680x945           | 20        | 0.17%   |
| 1280x720 (HD)      | 20        | 0.17%   |
| 2560x1440 (QHD)    | 19        | 0.16%   |
| 1400x1050          | 19        | 0.16%   |
| 2288x1287          | 18        | 0.15%   |
| 1600x1200          | 11        | 0.09%   |
| 2560x1600          | 10        | 0.08%   |
| 1920x540           | 10        | 0.08%   |
| 1024x576           | 8         | 0.07%   |
| 2880x1800          | 4         | 0.03%   |
| 1280x768           | 4         | 0.03%   |
| 3200x1800 (QHD+)   | 3         | 0.03%   |
| 2160x1440          | 3         | 0.03%   |
| 1152x864           | 3         | 0.03%   |
| 2736x1824          | 2         | 0.02%   |
| 2560x1080          | 2         | 0.02%   |
| 2048x1536          | 2         | 0.02%   |
| 4093x4093          | 1         | 0.01%   |
| 3440x1440          | 1         | 0.01%   |
| 2880x1920          | 1         | 0.01%   |
| 2520x1680          | 1         | 0.01%   |
| 2048x1152          | 1         | 0.01%   |
| 1792x768           | 1         | 0.01%   |
| 1360x765           | 1         | 0.01%   |
| Unknown            | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 7391      | 61.18%  |
| 17      | 1230      | 10.18%  |
| 14      | 834       | 6.9%    |
| 13      | 623       | 5.16%   |
| 10      | 601       | 4.98%   |
| 11      | 301       | 2.49%   |
| 12      | 241       | 2%      |
| 18      | 119       | 0.99%   |
| 23      | 113       | 0.94%   |
| 21      | 99        | 0.82%   |
| 19      | 89        | 0.74%   |
| 24      | 72        | 0.6%    |
| 27      | 51        | 0.42%   |
| 20      | 35        | 0.29%   |
| 16      | 35        | 0.29%   |
| 8       | 34        | 0.28%   |
| Unknown | 34        | 0.28%   |
| 22      | 26        | 0.22%   |
| 31      | 24        | 0.2%    |
| 54      | 18        | 0.15%   |
| 40      | 14        | 0.12%   |
| 72      | 13        | 0.11%   |
| 32      | 11        | 0.09%   |
| 52      | 10        | 0.08%   |
| 84      | 7         | 0.06%   |
| 26      | 7         | 0.06%   |
| 48      | 5         | 0.04%   |
| 46      | 5         | 0.04%   |
| 34      | 5         | 0.04%   |
| 25      | 5         | 0.04%   |
| 9       | 5         | 0.04%   |
| 42      | 4         | 0.03%   |
| 37      | 3         | 0.02%   |
| 142     | 2         | 0.02%   |
| 57      | 2         | 0.02%   |
| 55      | 2         | 0.02%   |
| 50      | 2         | 0.02%   |
| 36      | 2         | 0.02%   |
| 29      | 2         | 0.02%   |
| 115     | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 8277      | 68.92%  |
| 201-300        | 1519      | 12.65%  |
| 351-400        | 1480      | 12.32%  |
| 401-500        | 291       | 2.42%   |
| 501-600        | 235       | 1.96%   |
| 1001-1500      | 43        | 0.36%   |
| 101-200        | 36        | 0.3%    |
| Unknown        | 34        | 0.28%   |
| 601-700        | 29        | 0.24%   |
| 1501-2000      | 22        | 0.18%   |
| 701-800        | 18        | 0.15%   |
| 801-900        | 17        | 0.14%   |
| 901-1000       | 6         | 0.05%   |
| More than 2000 | 3         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 9598      | 82.01%  |
| 16/10   | 1811      | 15.47%  |
| 5/4     | 128       | 1.09%   |
| 4/3     | 110       | 0.94%   |
| 3/2     | 33        | 0.28%   |
| 6/5     | 7         | 0.06%   |
| Unknown | 5         | 0.04%   |
| 21/9    | 4         | 0.03%   |
| 32/9    | 3         | 0.03%   |
| 1.00    | 2         | 0.02%   |
| 2.21    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7329      | 60.64%  |
| 81-90          | 1115      | 9.23%   |
| 121-130        | 872       | 7.21%   |
| 41-50          | 604       | 5%      |
| 51-60          | 301       | 2.49%   |
| 71-80          | 300       | 2.48%   |
| 131-140        | 299       | 2.47%   |
| 201-250        | 259       | 2.14%   |
| 61-70          | 235       | 1.94%   |
| 141-150        | 173       | 1.43%   |
| 151-200        | 162       | 1.34%   |
| 91-100         | 129       | 1.07%   |
| More than 1000 | 62        | 0.51%   |
| 301-350        | 54        | 0.45%   |
| 351-500        | 40        | 0.33%   |
| 1-40           | 36        | 0.3%    |
| Unknown        | 34        | 0.28%   |
| 501-1000       | 32        | 0.26%   |
| 251-300        | 29        | 0.24%   |
| 111-120        | 21        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 6943      | 58.12%  |
| 51-100        | 2762      | 23.12%  |
| 121-160       | 2000      | 16.74%  |
| 161-240       | 106       | 0.89%   |
| 1-50          | 81        | 0.68%   |
| Unknown       | 34        | 0.28%   |
| More than 240 | 21        | 0.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11452     | 93.36%  |
| 2     | 635       | 5.18%   |
| 0     | 160       | 1.3%    |
| 3     | 19        | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6613      | 30.88%  |
| Qualcomm Atheros                       | 5898      | 27.54%  |
| Intel                                  | 2852      | 13.32%  |
| Broadcom                               | 2605      | 12.17%  |
| Marvell Technology Group               | 682       | 3.18%   |
| Broadcom Limited                       | 665       | 3.11%   |
| Ralink                                 | 498       | 2.33%   |
| Huawei Technologies                    | 310       | 1.45%   |
| JMicron Technology                     | 164       | 0.77%   |
| Attansic Technology                    | 151       | 0.71%   |
| Nvidia                                 | 114       | 0.53%   |
| Ralink Technology                      | 100       | 0.47%   |
| MediaTek                               | 88        | 0.41%   |
| Silicon Integrated Systems [SiS]       | 79        | 0.37%   |
| ZTE WCDMA Technologies MSM             | 53        | 0.25%   |
| Ericsson Business Mobile Networks      | 39        | 0.18%   |
| Samsung Electronics                    | 38        | 0.18%   |
| Qualcomm Atheros Communications        | 37        | 0.17%   |
| ASUSTek Computer                       | 32        | 0.15%   |
| D-Link                                 | 31        | 0.14%   |
| Xiaomi                                 | 28        | 0.13%   |
| TP-Link                                | 28        | 0.13%   |
| Gemtek                                 | 27        | 0.13%   |
| Hewlett-Packard                        | 22        | 0.1%    |
| HTC (High Tech Computer)               | 21        | 0.1%    |
| VIA Technologies                       | 17        | 0.08%   |
| Qualcomm                               | 15        | 0.07%   |
| Dell                                   | 14        | 0.07%   |
| AMD                                    | 14        | 0.07%   |
| NTmore                                 | 11        | 0.05%   |
| ASIX Electronics                       | 11        | 0.05%   |
| D-Link System                          | 10        | 0.05%   |
| Nokia Mobile Phones                    | 9         | 0.04%   |
| Vimtron Electronics                    | 8         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 8         | 0.04%   |
| Lenovo                                 | 8         | 0.04%   |
| T & A Mobile Phones                    | 7         | 0.03%   |
| Sierra Wireless                        | 7         | 0.03%   |
| GCT Semiconductor                      | 7         | 0.03%   |
| Linksys                                | 5         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 3731      | 15.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2239      | 9.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1894      | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1048      | 4.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 850       | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 708       | 2.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 565       | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 466       | 1.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 449       | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 381       | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 330       | 1.34%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 316       | 1.28%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 260       | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 257       | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 255       | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 234       | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 233       | 0.95%   |
| Intel WiFi Link 5100                                                    | 219       | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 210       | 0.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 208       | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 198       | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 187       | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 181       | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 176       | 0.71%   |
| Huawei Modem/Networkcard                                                | 168       | 0.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 166       | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 163       | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 162       | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 158       | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 157       | 0.64%   |
| Intel Centrino Wireless-N 130                                           | 156       | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 151       | 0.61%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 151       | 0.61%   |
| Intel Wireless 7260                                                     | 141       | 0.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 140       | 0.57%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 138       | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 137       | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 136       | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 136       | 0.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 132       | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 5055      | 41.39%  |
| Intel                             | 2688      | 22.01%  |
| Broadcom                          | 1842      | 15.08%  |
| Realtek Semiconductor             | 1455      | 11.91%  |
| Ralink                            | 498       | 4.08%   |
| Broadcom Limited                  | 332       | 2.72%   |
| Ralink Technology                 | 100       | 0.82%   |
| MediaTek                          | 55        | 0.45%   |
| Qualcomm Atheros Communications   | 37        | 0.3%    |
| ASUSTek Computer                  | 28        | 0.23%   |
| D-Link                            | 26        | 0.21%   |
| TP-Link                           | 25        | 0.2%    |
| D-Link System                     | 10        | 0.08%   |
| Dell                              | 8         | 0.07%   |
| Sierra Wireless                   | 7         | 0.06%   |
| Linksys                           | 5         | 0.04%   |
| Hewlett-Packard                   | 5         | 0.04%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Qualcomm                          | 3         | 0.02%   |
| Micro Star International          | 3         | 0.02%   |
| Fujitsu Siemens Computers         | 3         | 0.02%   |
| Edimax Technology                 | 3         | 0.02%   |
| Belkin Components                 | 3         | 0.02%   |
| ZyDAS                             | 2         | 0.02%   |
| Tenda                             | 2         | 0.02%   |
| Sagem                             | 2         | 0.02%   |
| Qcom                              | 2         | 0.02%   |
| Mercucys                          | 2         | 0.02%   |
| Xiaomi                            | 1         | 0.01%   |
| Wacom                             | 1         | 0.01%   |
| Sitecom Europe                    | 1         | 0.01%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.01%   |
| NetGear                           | 1         | 0.01%   |
| Marvell Technology Group          | 1         | 0.01%   |
| Fibocom                           | 1         | 0.01%   |
| ASUSTek Computer (wrong ID)       | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1894      | 15.46%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1048      | 8.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 850       | 6.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 708       | 5.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 565       | 4.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 466       | 3.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 449       | 3.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 381       | 3.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 257       | 2.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 234       | 1.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 233       | 1.9%    |
| Intel WiFi Link 5100                                                    | 219       | 1.79%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 208       | 1.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 181       | 1.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 163       | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 158       | 1.29%   |
| Intel Centrino Wireless-N 130                                           | 156       | 1.27%   |
| Intel Wireless 7260                                                     | 141       | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 140       | 1.14%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 138       | 1.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 137       | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 132       | 1.08%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 126       | 1.03%   |
| Intel Centrino Wireless-N 2230                                          | 116       | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 109       | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 105       | 0.86%   |
| Intel Wireless 7265                                                     | 100       | 0.82%   |
| Intel WiMAX/WiFi Link 5150                                              | 100       | 0.82%   |
| Intel Centrino Wireless-N 100                                           | 93        | 0.76%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 91        | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 84        | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 70        | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 69        | 0.56%   |
| Intel Centrino Advanced-N 6200                                          | 69        | 0.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 68        | 0.55%   |
| Intel Wireless 3165                                                     | 66        | 0.54%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 65        | 0.53%   |
| Broadcom BCM43227 802.11b/g/n                                           | 64        | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 62        | 0.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 59        | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6245      | 52.5%   |
| Qualcomm Atheros                       | 1901      | 15.98%  |
| Broadcom                               | 1034      | 8.69%   |
| Intel                                  | 792       | 6.66%   |
| Marvell Technology Group               | 681       | 5.72%   |
| Broadcom Limited                       | 350       | 2.94%   |
| JMicron Technology                     | 164       | 1.38%   |
| Attansic Technology                    | 151       | 1.27%   |
| Nvidia                                 | 113       | 0.95%   |
| Silicon Integrated Systems [SiS]       | 78        | 0.66%   |
| Huawei Technologies                    | 66        | 0.55%   |
| ZTE WCDMA Technologies MSM             | 48        | 0.4%    |
| Samsung Electronics                    | 35        | 0.29%   |
| MediaTek                               | 31        | 0.26%   |
| Xiaomi                                 | 27        | 0.23%   |
| Gemtek                                 | 27        | 0.23%   |
| HTC (High Tech Computer)               | 21        | 0.18%   |
| VIA Technologies                       | 16        | 0.13%   |
| Qualcomm                               | 12        | 0.1%    |
| NTmore                                 | 11        | 0.09%   |
| ASIX Electronics                       | 11        | 0.09%   |
| Vimtron Electronics                    | 8         | 0.07%   |
| GCT Semiconductor                      | 7         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.05%   |
| Lenovo                                 | 6         | 0.05%   |
| D-Link                                 | 5         | 0.04%   |
| ASUSTek Computer                       | 5         | 0.04%   |
| T & A Mobile Phones                    | 4         | 0.03%   |
| Motorola PCS                           | 4         | 0.03%   |
| TP-Link                                | 3         | 0.03%   |
| Spreadtrum Communications              | 3         | 0.03%   |
| LSI                                    | 3         | 0.03%   |
| LG Electronics                         | 3         | 0.03%   |
| ICS Advent                             | 3         | 0.03%   |
| HMD Global                             | 3         | 0.03%   |
| Android                                | 3         | 0.03%   |
| Research In Motion                     | 2         | 0.02%   |
| Hewlett-Packard                        | 2         | 0.02%   |
| 3Com                                   | 2         | 0.02%   |
| Prestigio                              | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3731      | 31.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2239      | 18.79%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 330       | 2.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 316       | 2.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 260       | 2.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 255       | 2.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 210       | 1.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 198       | 1.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 187       | 1.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 176       | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 166       | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 162       | 1.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 157       | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 151       | 1.27%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 151       | 1.27%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 136       | 1.14%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 136       | 1.14%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 129       | 1.08%   |
| Intel WiMAX Connection 2400m                                                   | 120       | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 115       | 0.97%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 111       | 0.93%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 107       | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 94        | 0.79%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 81        | 0.68%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 77        | 0.65%   |
| Intel 82567LM Gigabit Network Connection                                       | 77        | 0.65%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 74        | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 72        | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 64        | 0.54%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 62        | 0.52%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 60        | 0.5%    |
| Intel 82566MM Gigabit Network Connection                                       | 50        | 0.42%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 48        | 0.4%    |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 48        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 46        | 0.39%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 46        | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 45        | 0.38%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                                  | 43        | 0.36%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 42        | 0.35%   |
| Huawei E353/E3131                                                              | 42        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 11872     | 49.91%  |
| Ethernet | 11471     | 48.22%  |
| Modem    | 432       | 1.82%   |
| Unknown  | 14        | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9855      | 77.97%  |
| Ethernet | 2771      | 21.92%  |
| Unknown  | 9         | 0.07%   |
| Modem    | 4         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 11154     | 92.19%  |
| 1     | 782       | 6.46%   |
| 0     | 153       | 1.26%   |
| 3     | 10        | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 8729      | 68.8%   |
| Unknown | 3872      | 30.52%  |
| Yes     | 86        | 0.68%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 1285      | 17.24%  |
| Intel                           | 1042      | 13.98%  |
| Broadcom                        | 934       | 12.53%  |
| Realtek Semiconductor           | 738       | 9.9%    |
| Foxconn / Hon Hai               | 563       | 7.55%   |
| IMC Networks                    | 552       | 7.41%   |
| Lite-On Technology              | 546       | 7.33%   |
| ASUSTek Computer                | 261       | 3.5%    |
| Ralink                          | 257       | 3.45%   |
| Toshiba                         | 226       | 3.03%   |
| Hewlett-Packard                 | 226       | 3.03%   |
| Dell                            | 191       | 2.56%   |
| Foxconn International           | 179       | 2.4%    |
| Cambridge Silicon Radio         | 140       | 1.88%   |
| Alps Electric                   | 74        | 0.99%   |
| Apple                           | 63        | 0.85%   |
| Ralink Technology               | 60        | 0.81%   |
| Chicony Electronics             | 21        | 0.28%   |
| MediaTek                        | 16        | 0.21%   |
| Taiyo Yuden                     | 15        | 0.2%    |
| Micro Star International        | 13        | 0.17%   |
| Askey Computer                  | 12        | 0.16%   |
| Realtek                         | 9         | 0.12%   |
| USI                             | 6         | 0.08%   |
| Qcom                            | 5         | 0.07%   |
| Syntek                          | 4         | 0.05%   |
| Integrated System Solution      | 4         | 0.05%   |
| Samsung Electronics             | 3         | 0.04%   |
| Unknown                         | 1         | 0.01%   |
| TP-Link                         | 1         | 0.01%   |
| Qualcomm Atheros                | 1         | 0.01%   |
| Opticis                         | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Belkin Components               | 1         | 0.01%   |
| Actiontec Electronics           | 1         | 0.01%   |
| AboCom Systems                  | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth                                                   | 479       | 6.42%   |
| Intel Bluetooth wireless interface                                                  | 437       | 5.86%   |
| Realtek Bluetooth Radio                                                             | 387       | 5.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 332       | 4.45%   |
| Ralink RT3290 Bluetooth                                                             | 257       | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 213       | 2.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 205       | 2.75%   |
| Lite-On Bluetooth Device                                                            | 202       | 2.71%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 194       | 2.6%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 191       | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 188       | 2.52%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 177       | 2.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 173       | 2.32%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 162       | 2.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 151       | 2.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 140       | 1.88%   |
| Realtek RTL8723B Bluetooth                                                          | 131       | 1.76%   |
| Broadcom BCM2045 Bluetooth                                                          | 125       | 1.68%   |
| IMC Networks Bluetooth Device                                                       | 122       | 1.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 117       | 1.57%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 109       | 1.46%   |
| Qualcomm Atheros Bluetooth                                                          | 100       | 1.34%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 98        | 1.31%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 95        | 1.27%   |
| Toshiba Integrated Bluetooth HCI                                                    | 89        | 1.19%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 89        | 1.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 85        | 1.14%   |
| Broadcom HP Portable Valentine                                                      | 84        | 1.13%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 82        | 1.1%    |
| ASUS BT-270 Bluetooth Adapter                                                       | 78        | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 73        | 0.98%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 72        | 0.97%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 70        | 0.94%   |
| IMC Networks Bluetooth Radio                                                        | 66        | 0.88%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 65        | 0.87%   |
| Realtek RTL8723A Bluetooth                                                          | 64        | 0.86%   |
| IMC Networks Bluetooth module                                                       | 62        | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 59        | 0.79%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 49        | 0.66%   |
| Intel Bluetooth Device                                                              | 44        | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 9325      | 69.63%  |
| AMD                                  | 2903      | 21.68%  |
| Nvidia                               | 867       | 6.47%   |
| Silicon Integrated Systems [SiS]     | 117       | 0.87%   |
| C-Media Electronics                  | 31        | 0.23%   |
| VIA Technologies                     | 23        | 0.17%   |
| Creative Technology                  | 19        | 0.14%   |
| Logitech                             | 12        | 0.09%   |
| Generalplus Technology               | 9         | 0.07%   |
| Texas Instruments                    | 6         | 0.04%   |
| JMTek                                | 6         | 0.04%   |
| GYROCOM C&C                          | 5         | 0.04%   |
| Plantronics                          | 4         | 0.03%   |
| M-Audio                              | 4         | 0.03%   |
| iCreate Technologies                 | 4         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.02%   |
| Roland                               | 3         | 0.02%   |
| ASUSTek Computer                     | 3         | 0.02%   |
| Yealink Network Technology           | 2         | 0.01%   |
| Yamaha                               | 2         | 0.01%   |
| XMOS                                 | 2         | 0.01%   |
| TEAC                                 | 2         | 0.01%   |
| Samson Technologies                  | 2         | 0.01%   |
| GN Netcom                            | 2         | 0.01%   |
| Focusrite-Novation                   | 2         | 0.01%   |
| DigiTech                             | 2         | 0.01%   |
| Cambridge Silicon Radio              | 2         | 0.01%   |
| A4Tech                               | 2         | 0.01%   |
| Zhaoxin                              | 1         | 0.01%   |
| USB MICROPHONE                       | 1         | 0.01%   |
| ULi Electronics                      | 1         | 0.01%   |
| Trust                                | 1         | 0.01%   |
| Tenx Technology                      | 1         | 0.01%   |
| Shenzhen Rapoo Technology            | 1         | 0.01%   |
| SG.Ltd                               | 1         | 0.01%   |
| Sennheiser Communications            | 1         | 0.01%   |
| Pixart Imaging                       | 1         | 0.01%   |
| Pioneer                              | 1         | 0.01%   |
| Nordic Semiconductor ASA             | 1         | 0.01%   |
| Nektar                               | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1860      | 11.46%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1275      | 7.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1170      | 7.21%   |
| AMD FCH Azalia Controller                                                                         | 968       | 5.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 961       | 5.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 958       | 5.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 937       | 5.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 662       | 4.08%   |
| Intel 8 Series HD Audio Controller                                                                | 429       | 2.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 428       | 2.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 386       | 2.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 371       | 2.29%   |
| AMD Wrestler HDMI Audio                                                                           | 353       | 2.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 344       | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 334       | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 322       | 1.98%   |
| AMD Trinity HDMI Audio Controller                                                                 | 271       | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 239       | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 223       | 1.37%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 215       | 1.32%   |
| Intel Broadwell-U Audio Controller                                                                | 196       | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 195       | 1.2%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 188       | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 179       | 1.1%    |
| Nvidia High Definition Audio Controller                                                           | 158       | 0.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 146       | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 137       | 0.84%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 127       | 0.78%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 120       | 0.74%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 112       | 0.69%   |
| AMD High Definition Audio Controller                                                              | 112       | 0.69%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 100       | 0.62%   |
| Nvidia MCP79 High Definition Audio                                                                | 94        | 0.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 77        | 0.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 70        | 0.43%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 70        | 0.43%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 67        | 0.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 66        | 0.41%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 65        | 0.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 64        | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 3052      | 22.06%  |
| SK hynix              | 2553      | 18.45%  |
| Unknown               | 2263      | 16.36%  |
| Kingston              | 1478      | 10.68%  |
| Micron Technology     | 882       | 6.37%   |
| Elpida                | 711       | 5.14%   |
| Nanya Technology      | 592       | 4.28%   |
| Ramaxel Technology    | 469       | 3.39%   |
| A-DATA Technology     | 397       | 2.87%   |
| Crucial               | 198       | 1.43%   |
| ASint Technology      | 173       | 1.25%   |
| 48spaces              | 121       | 0.87%   |
| Goldkey               | 104       | 0.75%   |
| Corsair               | 93        | 0.67%   |
| AMD                   | 83        | 0.6%    |
| SHARETRONIC           | 75        | 0.54%   |
| Patriot               | 62        | 0.45%   |
| Qimonda               | 54        | 0.39%   |
| Transcend             | 51        | 0.37%   |
| Goodram               | 35        | 0.25%   |
| Unknown (ABCD)        | 34        | 0.25%   |
| Unifosa               | 30        | 0.22%   |
| Toshiba               | 27        | 0.2%    |
| Apacer                | 26        | 0.19%   |
| Foxline               | 20        | 0.14%   |
| Silicon Power         | 18        | 0.13%   |
| Qumo                  | 18        | 0.13%   |
| Team                  | 17        | 0.12%   |
| Kllisre               | 16        | 0.12%   |
| Kingmax               | 15        | 0.11%   |
| Smart                 | 14        | 0.1%    |
| Kingmax Semiconductor | 14        | 0.1%    |
| Unknown               | 12        | 0.09%   |
| GeIL                  | 7         | 0.05%   |
| Infineon              | 5         | 0.04%   |
| G.Skill               | 5         | 0.04%   |
| Teikon                | 4         | 0.03%   |
| pqi                   | 4         | 0.03%   |
| Netlist               | 4         | 0.03%   |
| Kreton                | 4         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 309       | 2.03%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 223       | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 218       | 1.43%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                        | 206       | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 198       | 1.3%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 198       | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 185       | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 181       | 1.19%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 181       | 1.19%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                        | 176       | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 157       | 1.03%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                                | 152       | 1%      |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                       | 131       | 0.86%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                        | 129       | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 126       | 0.83%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                        | 122       | 0.8%    |
| 48spaces RAM 012345678901234567890123456789012345 1024MB SODIMM DDR2 667MT/s | 116       | 0.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                        | 113       | 0.74%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                         | 106       | 0.7%    |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                            | 106       | 0.7%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                             | 99        | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR                                         | 94        | 0.62%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                        | 94        | 0.62%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                       | 92        | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 91        | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DRAM                                        | 90        | 0.59%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                        | 85        | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                | 83        | 0.55%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                         | 83        | 0.55%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s                        | 82        | 0.54%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                                       | 81        | 0.53%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 81        | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 78        | 0.51%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 78        | 0.51%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                       | 78        | 0.51%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 77        | 0.51%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s                        | 77        | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 73        | 0.48%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                       | 72        | 0.47%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s                       | 72        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 7448      | 63.67%  |
| DDR2    | 1791      | 15.31%  |
| SDRAM   | 892       | 7.63%   |
| DDR4    | 816       | 6.98%   |
| DDR     | 252       | 2.15%   |
| Unknown | 196       | 1.68%   |
| DRAM    | 177       | 1.51%   |
| LPDDR4  | 99        | 0.85%   |
| LPDDR3  | 23        | 0.2%    |
| LPDDR5  | 2         | 0.02%   |
| SRAM    | 1         | 0.01%   |
| RAM     | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11102     | 98.38%  |
| DIMM         | 93        | 0.82%   |
| Row Of Chips | 62        | 0.55%   |
| Chip         | 21        | 0.19%   |
| Unknown      | 7         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 5545      | 40.87%  |
| 2048    | 4768      | 35.14%  |
| 1024    | 1730      | 12.75%  |
| 8192    | 1126      | 8.3%    |
| 512     | 265       | 1.95%   |
| 16384   | 84        | 0.62%   |
| 256     | 32        | 0.24%   |
| Unknown | 10        | 0.07%   |
| 32768   | 5         | 0.04%   |
| 1536    | 1         | 0.01%   |
| 128     | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 4236      | 32.51%  |
| 1334    | 2009      | 15.42%  |
| 1333    | 1219      | 9.36%   |
| 667     | 1090      | 8.37%   |
| Unknown | 1042      | 8%      |
| 4199    | 464       | 3.56%   |
| 2667    | 446       | 3.42%   |
| 1067    | 439       | 3.37%   |
| 800     | 385       | 2.95%   |
| 2400    | 281       | 2.16%   |
| 533     | 248       | 1.9%    |
| 3200    | 219       | 1.68%   |
| 2048    | 215       | 1.65%   |
| 1066    | 137       | 1.05%   |
| 975     | 123       | 0.94%   |
| 2133    | 112       | 0.86%   |
| 333     | 83        | 0.64%   |
| 3266    | 56        | 0.43%   |
| 1867    | 51        | 0.39%   |
| 400     | 49        | 0.38%   |
| 1639    | 39        | 0.3%    |
| 1866    | 16        | 0.12%   |
| 266     | 13        | 0.1%    |
| 4267    | 7         | 0.05%   |
| 2933    | 6         | 0.05%   |
| 1776    | 6         | 0.05%   |
| 65535   | 4         | 0.03%   |
| 200     | 4         | 0.03%   |
| 1       | 4         | 0.03%   |
| 4266    | 3         | 0.02%   |
| 100     | 3         | 0.02%   |
| 8400    | 2         | 0.02%   |
| 6400    | 2         | 0.02%   |
| 3733    | 2         | 0.02%   |
| 2666    | 2         | 0.02%   |
| 666     | 2         | 0.02%   |
| 166     | 2         | 0.02%   |
| 133     | 2         | 0.02%   |
| 4800    | 1         | 0.01%   |
| 2267    | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 85        | 30.04%  |
| Canon                  | 66        | 23.32%  |
| Samsung Electronics    | 47        | 16.61%  |
| Seiko Epson            | 27        | 9.54%   |
| Brother Industries     | 18        | 6.36%   |
| Panasonic (Matsushita) | 13        | 4.59%   |
| Xerox                  | 10        | 3.53%   |
| Pantum                 | 6         | 2.12%   |
| Ricoh                  | 3         | 1.06%   |
| Prolific Technology    | 3         | 1.06%   |
| Xiaomi                 | 1         | 0.35%   |
| QinHeng Electronics    | 1         | 0.35%   |
| Kyocera                | 1         | 0.35%   |
| Dell                   | 1         | 0.35%   |
| Apple                  | 1         | 0.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 11        | 3.73%   |
| HP LaserJet P1102                                            | 10        | 3.39%   |
| Samsung SCX-4200 series                                      | 9         | 3.05%   |
| HP LaserJet 1018                                             | 9         | 3.05%   |
| Panasonic (Matsushita) KX-MB1500RU                           | 8         | 2.71%   |
| Samsung SCX-3400 Series                                      | 5         | 1.69%   |
| Samsung SCX-3200 Series                                      | 5         | 1.69%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 5         | 1.69%   |
| Canon LBP2900                                                | 5         | 1.69%   |
| Brother HL-1110 series                                       | 5         | 1.69%   |
| Seiko Epson Printer                                          | 4         | 1.36%   |
| Seiko Epson L210 Series                                      | 4         | 1.36%   |
| Samsung ML-1210 Printer                                      | 4         | 1.36%   |
| HP LaserJet Professional P1102w                              | 4         | 1.36%   |
| Canon PIXMA MG2500 Series                                    | 4         | 1.36%   |
| Canon MF4410                                                 | 4         | 1.36%   |
| Canon LBP6000                                                | 4         | 1.36%   |
| Canon LBP3010/LBP3018/LBP3050                                | 4         | 1.36%   |
| Xerox Phaser 3040                                            | 3         | 1.02%   |
| Xerox Phaser 3010                                            | 3         | 1.02%   |
| Samsung M2070 Series                                         | 3         | 1.02%   |
| Prolific PL2305 Parallel Port                                | 3         | 1.02%   |
| HP LaserJet 1200                                             | 3         | 1.02%   |
| HP LaserJet 1010                                             | 3         | 1.02%   |
| HP Deskjet 2050 J510                                         | 3         | 1.02%   |
| Canon PIXMA MP280                                            | 3         | 1.02%   |
| Canon MG2400 series                                          | 3         | 1.02%   |
| Canon MF3010                                                 | 3         | 1.02%   |
| Canon LBP7010C/7018C                                         | 3         | 1.02%   |
| Canon LBP6020                                                | 3         | 1.02%   |
| Canon LaserShot LBP-1120 Printer                             | 3         | 1.02%   |
| Canon iP2700 series                                          | 3         | 1.02%   |
| Canon G1000 series                                           | 3         | 1.02%   |
| Brother HL-2030 Laser Printer                                | 3         | 1.02%   |
| Xerox Phaser 6000B                                           | 2         | 0.68%   |
| Xerox Phaser 3020                                            | 2         | 0.68%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                        | 2         | 0.68%   |
| Seiko Epson L365 Series                                      | 2         | 0.68%   |
| Seiko Epson L200 Series                                      | 2         | 0.68%   |
| Seiko Epson L132 Series                                      | 2         | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 21        | 28%     |
| Seiko Epson                 | 19        | 25.33%  |
| Hewlett-Packard             | 13        | 17.33%  |
| Mustek Systems              | 10        | 13.33%  |
| Ultima Electronics          | 3         | 4%      |
| Acer Peripherals (now BenQ) | 3         | 4%      |
| KYE Systems (Mouse Systems) | 2         | 2.67%   |
| Visioneer                   | 1         | 1.33%   |
| Papillon Systems            | 1         | 1.33%   |
| Microtek International      | 1         | 1.33%   |
| Fujitsu                     | 1         | 1.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 6.67%   |
| HP ScanJet 2400c                                                                      | 5         | 6.67%   |
| Canon CanoScan LiDE 110                                                               | 5         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4         | 5.33%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 3         | 4%      |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 3         | 4%      |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 4%      |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 3         | 4%      |
| HP Scanjet 200                                                                        | 3         | 4%      |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2         | 2.67%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 2.67%   |
| HP ScanJet 3770                                                                       | 2         | 2.67%   |
| Canon CanoScan LIDE 25                                                                | 2         | 2.67%   |
| Canon CanoScan LiDE 220                                                               | 2         | 2.67%   |
| Canon CanoScan LiDE 120                                                               | 2         | 2.67%   |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 2         | 2.67%   |
| Visioneer DM 152                                                                      | 1         | 1.33%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 1.33%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 1         | 1.33%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 1.33%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1         | 1.33%   |
| Seiko Epson ES-7000H [GT-15000]                                                       | 1         | 1.33%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                                            | 1         | 1.33%   |
| Papillon Systems Scanner DS45USB                                                      | 1         | 1.33%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.33%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 1.33%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 1         | 1.33%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 1         | 1.33%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 1         | 1.33%   |
| Microtek International USB1200 Scanner                                                | 1         | 1.33%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 1         | 1.33%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE                                   | 1         | 1.33%   |
| HP ScanJet G4010                                                                      | 1         | 1.33%   |
| HP ScanJet 3500c                                                                      | 1         | 1.33%   |
| HP ScanJet 3400cse                                                                    | 1         | 1.33%   |
| Fujitsu fi-4120c Scanner                                                              | 1         | 1.33%   |
| Canon CanoScan LiDE 70                                                                | 1         | 1.33%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 1.33%   |
| Canon CanoScan LiDE 210                                                               | 1         | 1.33%   |
| Canon CanoScan LiDE 100                                                               | 1         | 1.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2824      | 27.52%  |
| Acer                                   | 975       | 9.5%    |
| Suyin                                  | 913       | 8.9%    |
| IMC Networks                           | 846       | 8.24%   |
| Realtek Semiconductor                  | 662       | 6.45%   |
| Silicon Motion                         | 565       | 5.51%   |
| Sunplus Innovation Technology          | 550       | 5.36%   |
| Microdia                               | 537       | 5.23%   |
| Cheng Uei Precision Industry (Foxlink) | 321       | 3.13%   |
| Alcor Micro                            | 313       | 3.05%   |
| Syntek                                 | 293       | 2.86%   |
| Z-Star Microelectronics                | 214       | 2.09%   |
| Quanta                                 | 166       | 1.62%   |
| ALi                                    | 163       | 1.59%   |
| Ricoh                                  | 146       | 1.42%   |
| DigiTech                               | 124       | 1.21%   |
| Apple                                  | 81        | 0.79%   |
| Lenovo                                 | 66        | 0.64%   |
| Lite-On Technology                     | 61        | 0.59%   |
| Logitech                               | 58        | 0.57%   |
| Importek                               | 52        | 0.51%   |
| Primax Electronics                     | 46        | 0.45%   |
| Samsung Electronics                    | 38        | 0.37%   |
| OmniVision Technologies                | 25        | 0.24%   |
| Sunplus Technology                     | 22        | 0.21%   |
| Luxvisions Innotech Limited            | 19        | 0.19%   |
| Image Processor                        | 17        | 0.17%   |
| Genesys Logic                          | 14        | 0.14%   |
| Unknown                                | 14        | 0.14%   |
| Sonix Technology                       | 11        | 0.11%   |
| Pixart Imaging                         | 9         | 0.09%   |
| GEMBIRD                                | 9         | 0.09%   |
| Foxconn / Hon Hai                      | 8         | 0.08%   |
| Microsoft                              | 7         | 0.07%   |
| O2 Micro                               | 6         | 0.06%   |
| Nokia Mobile Phones                    | 6         | 0.06%   |
| Y Media                                | 5         | 0.05%   |
| KYE Systems (Mouse Systems)            | 5         | 0.05%   |
| Cubeternet                             | 5         | 0.05%   |
| Arkmicro Technologies                  | 5         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Acer Lenovo EasyCamera                                      | 357       | 3.48%   |
| Chicony HD Webcam                                           | 302       | 2.94%   |
| Chicony Lenovo EasyCamera                                   | 274       | 2.67%   |
| IMC Networks UVC VGA Webcam                                 | 202       | 1.97%   |
| Sunplus HD WebCam                                           | 197       | 1.92%   |
| Chicony USB 2.0 Camera                                      | 178       | 1.73%   |
| Chicony USB2.0 HD UVC WebCam                                | 156       | 1.52%   |
| Acer BisonCam, NB Pro                                       | 154       | 1.5%    |
| Realtek USB Camera                                          | 130       | 1.27%   |
| Chicony Integrated Camera                                   | 122       | 1.19%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 120       | 1.17%   |
| Realtek Lenovo EasyCamera                                   | 118       | 1.15%   |
| Silicon Motion WebCam SC-0311139N                           | 112       | 1.09%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 112       | 1.09%   |
| ALi Gateway Webcam                                          | 112       | 1.09%   |
| Syntek Lenovo EasyCamera                                    | 109       | 1.06%   |
| IMC Networks Integrated Webcam                              | 109       | 1.06%   |
| Alcor Micro Asus Integrated Webcam                          | 109       | 1.06%   |
| Acer Lenovo Integrated Webcam                               | 106       | 1.03%   |
| DigiTech USB 2.0 PC Camera                                  | 103       | 1%      |
| Chicony USB2.0 VGA UVC WebCam                               | 95        | 0.93%   |
| Sunplus Asus Webcam                                         | 92        | 0.9%    |
| Suyin 1.3M HD WebCam                                        | 90        | 0.88%   |
| Chicony HP Truevision HD                                    | 90        | 0.88%   |
| Chicony USB2.0 0.3M UVC WebCam                              | 86        | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 79        | 0.77%   |
| Chicony HP Webcam                                           | 79        | 0.77%   |
| Suyin Acer CrystalEye Webcam                                | 77        | 0.75%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 77        | 0.75%   |
| Chicony VGA Webcam                                          | 77        | 0.75%   |
| Chicony 1.3M Webcam                                         | 77        | 0.75%   |
| IMC Networks USB 2.0 UVC VGA WebCam                         | 76        | 0.74%   |
| Chicony Webcam                                              | 76        | 0.74%   |
| Silicon Motion WebCam SCB-1100N                             | 75        | 0.73%   |
| Microdia Sonix USB 2.0 Camera                               | 75        | 0.73%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 72        | 0.7%    |
| Silicon Motion WebCam SCB-0355N                             | 71        | 0.69%   |
| Chicony CNF9055 Toshiba Webcam                              | 70        | 0.68%   |
| Suyin HP TrueVision HD                                      | 69        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 67        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 426       | 43.6%   |
| AuthenTec                  | 224       | 22.93%  |
| Upek                       | 156       | 15.97%  |
| STMicroelectronics         | 72        | 7.37%   |
| LighTuning Technology      | 63        | 6.45%   |
| Shenzhen Goodix Technology | 14        | 1.43%   |
| Elan Microelectronics      | 12        | 1.23%   |
| Synaptics                  | 9         | 0.92%   |
| Focal-systems.Corp         | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 139       | 14.23%  |
| Validity Sensors Fingerprint scanner                                       | 114       | 11.67%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 87        | 8.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 73        | 7.47%   |
| STMicroelectronics Fingerprint Reader                                      | 72        | 7.37%   |
| AuthenTec AES1600                                                          | 62        | 6.35%   |
| AuthenTec AES2810                                                          | 55        | 5.63%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 4.61%   |
| LighTuning Fingerprint Reader                                              | 40        | 4.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 39        | 3.99%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 31        | 3.17%   |
| Validity Sensors VFS491                                                    | 26        | 2.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 2.56%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 24        | 2.46%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 19        | 1.94%   |
| Upek TCS5B Fingerprint sensor                                              | 17        | 1.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.74%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 1.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.23%   |
| Elan ELAN:Fingerprint                                                      | 10        | 1.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 0.82%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.72%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.61%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 0.41%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.31%   |
| Synaptics  WBDI                                                            | 2         | 0.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.1%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.1%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.1%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.1%    |
| Elan ELAN:ARM-M4                                                           | 1         | 0.1%    |
| AuthenTec AES2501                                                          | 1         | 0.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 101       | 41.22%  |
| O2 Micro                  | 52        | 21.22%  |
| Lenovo                    | 27        | 11.02%  |
| Upek                      | 26        | 10.61%  |
| Alcor Micro               | 25        | 10.2%   |
| Gemalto (was Gemplus)     | 4         | 1.63%   |
| OmniKey                   | 3         | 1.22%   |
| Aladdin Knowledge Systems | 3         | 1.22%   |
| Realtek Semiconductor     | 1         | 0.41%   |
| In Focus Systems          | 1         | 0.41%   |
| Aladdin R.D.              | 1         | 0.41%   |
| Aktiv                     | 1         | 0.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 67        | 27.35%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 36        | 14.69%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 11.02%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 10.61%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 25        | 10.2%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 9.8%    |
| O2 Micro Oz776 SmartCard Reader                                              | 16        | 6.53%   |
| Broadcom 5880                                                                | 7         | 2.86%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.22%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 1.22%   |
| OmniKey CardMan 1021                                                         | 2         | 0.82%   |
| Broadcom 58200                                                               | 2         | 0.82%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.41%   |
| OmniKey CardMan 4321                                                         | 1         | 0.41%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.41%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.41%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.41%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.41%   |
| Aktiv Rutoken lite                                                           | 1         | 0.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 8843      | 69.72%  |
| 1     | 3040      | 23.97%  |
| 2     | 697       | 5.5%    |
| 3     | 84        | 0.66%   |
| 4     | 18        | 0.14%   |
| 5     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1955      | 45.62%  |
| Fingerprint reader       | 977       | 22.8%   |
| Bluetooth                | 342       | 7.98%   |
| Net/wireless             | 296       | 6.91%   |
| Chipcard                 | 236       | 5.51%   |
| Storage                  | 118       | 2.75%   |
| Flash memory             | 96        | 2.24%   |
| Multimedia controller    | 83        | 1.94%   |
| Camera                   | 70        | 1.63%   |
| Communication controller | 65        | 1.52%   |
| Card reader              | 20        | 0.47%   |
| Sound                    | 10        | 0.23%   |
| Dvb card                 | 5         | 0.12%   |
| Net/ethernet             | 4         | 0.09%   |
| Video                    | 3         | 0.07%   |
| Modem                    | 2         | 0.05%   |
| Wireless                 | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |
| Network                  | 1         | 0.02%   |

