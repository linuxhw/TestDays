Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 9188

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Unknown       | ARM5                        | Mini pc     | [aad3a07e37](https://linux-hardware.org/?probe=aad3a07e37) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [2fee4a59ba](https://linux-hardware.org/?probe=2fee4a59ba) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| HP            | Compaq 6530b                | Notebook    | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Unknown       | ARM5                        | Mini pc     | [1b3ea4360c](https://linux-hardware.org/?probe=1b3ea4360c) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [1ae85a6add](https://linux-hardware.org/?probe=1ae85a6add) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [7f9b52e91c](https://linux-hardware.org/?probe=7f9b52e91c) | Jan 27, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [54915be6bc](https://linux-hardware.org/?probe=54915be6bc) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | Desktop     | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [027f04536c](https://linux-hardware.org/?probe=027f04536c) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [d23feafd62](https://linux-hardware.org/?probe=d23feafd62) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [405a60b1e3](https://linux-hardware.org/?probe=405a60b1e3) | Jan 24, 2023 |
| realme        | CloudProXXXX                | Notebook    | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [bf22d53528](https://linux-hardware.org/?probe=bf22d53528) | Jan 24, 2023 |
| Dell          | Inspiron 7573               | Convertible | [855d0fd69b](https://linux-hardware.org/?probe=855d0fd69b) | Jan 24, 2023 |
| Dell          | Inspiron 7573               | Convertible | [f2df75c3db](https://linux-hardware.org/?probe=f2df75c3db) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 9320                    | Notebook    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| Acer          | Aspire C22-865              | All in one  | [eb0191f969](https://linux-hardware.org/?probe=eb0191f969) | Jan 23, 2023 |
| System76      | Darter UltraThin            | Notebook    | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Samsung       | 730QDA                      | Convertible | [4796f92a58](https://linux-hardware.org/?probe=4796f92a58) | Jan 22, 2023 |
| Samsung       | 730QDA                      | Convertible | [bbd0fe538f](https://linux-hardware.org/?probe=bbd0fe538f) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| Toshiba       | Satellite C50-C             | Notebook    | [3512195f65](https://linux-hardware.org/?probe=3512195f65) | Jan 21, 2023 |
| Dell          | G7 7700                     | Notebook    | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| HP            | 85A2                        | All in one  | [13fcd2dd69](https://linux-hardware.org/?probe=13fcd2dd69) | Jan 20, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| Acer          | Aspire C22-865              | All in one  | [90ea1c9655](https://linux-hardware.org/?probe=90ea1c9655) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| AZW           | SER V01                     | Mini pc     | [b209807db5](https://linux-hardware.org/?probe=b209807db5) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [96e072d33f](https://linux-hardware.org/?probe=96e072d33f) | Jan 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | Desktop     | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [4df4c5ecc8](https://linux-hardware.org/?probe=4df4c5ecc8) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| Dell          | Inspiron 5585               | Notebook    | [b92481ca4e](https://linux-hardware.org/?probe=b92481ca4e) | Jan 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [6c8a25d916](https://linux-hardware.org/?probe=6c8a25d916) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | Desktop     | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | Notebook    | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| Intel         | X99                         | Desktop     | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [4b877715b1](https://linux-hardware.org/?probe=4b877715b1) | Jan 15, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [9ac53f405e](https://linux-hardware.org/?probe=9ac53f405e) | Jan 15, 2023 |
| LG Electro... | 17Z90N-R.AAS9U1             | Notebook    | [9d6736bccd](https://linux-hardware.org/?probe=9d6736bccd) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [4a0fec8aef](https://linux-hardware.org/?probe=4a0fec8aef) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [73533cda86](https://linux-hardware.org/?probe=73533cda86) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | Notebook    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [ff2c48315e](https://linux-hardware.org/?probe=ff2c48315e) | Jan 13, 2023 |
| realme        | CloudProXXXX                | Notebook    | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| Shuttle       | FS61                        | Desktop     | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1dc150e9db](https://linux-hardware.org/?probe=1dc150e9db) | Jan 12, 2023 |
| HP            | ProBook 6560b               | Notebook    | [9f06213ef6](https://linux-hardware.org/?probe=9f06213ef6) | Jan 12, 2023 |
| HP            | ProBook 6560b               | Notebook    | [5b71b83435](https://linux-hardware.org/?probe=5b71b83435) | Jan 12, 2023 |
| Notebook      | L14xMU                      | Notebook    | [48b282b529](https://linux-hardware.org/?probe=48b282b529) | Jan 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [ede9b6da76](https://linux-hardware.org/?probe=ede9b6da76) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [5be6eaa40c](https://linux-hardware.org/?probe=5be6eaa40c) | Jan 11, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [a67f1ee7b0](https://linux-hardware.org/?probe=a67f1ee7b0) | Jan 11, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [f78e703512](https://linux-hardware.org/?probe=f78e703512) | Jan 11, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [1fa3917cc0](https://linux-hardware.org/?probe=1fa3917cc0) | Jan 11, 2023 |
| Dell          | Precision 7710              | Notebook    | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e829eab59d](https://linux-hardware.org/?probe=e829eab59d) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [c618ab31a8](https://linux-hardware.org/?probe=c618ab31a8) | Jan 10, 2023 |
| HP            | Pavilion dv6                | Notebook    | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [99bb69023a](https://linux-hardware.org/?probe=99bb69023a) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| Dell          | Precision 7710              | Notebook    | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [af68cbff10](https://linux-hardware.org/?probe=af68cbff10) | Jan 09, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [2eaea530ea](https://linux-hardware.org/?probe=2eaea530ea) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| MSI           | GS63 Stealth 8RE            | Notebook    | [8682a08d74](https://linux-hardware.org/?probe=8682a08d74) | Jan 09, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [5feb203761](https://linux-hardware.org/?probe=5feb203761) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [da175172b3](https://linux-hardware.org/?probe=da175172b3) | Jan 08, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ca9c5df4b3](https://linux-hardware.org/?probe=ca9c5df4b3) | Jan 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| IPASON        | MaxBook P1X                 | Notebook    | [b7d1ce416f](https://linux-hardware.org/?probe=b7d1ce416f) | Jan 07, 2023 |
| Sony          | SVS1512U1RW                 | Notebook    | [c5de402a7c](https://linux-hardware.org/?probe=c5de402a7c) | Jan 06, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [5f50538338](https://linux-hardware.org/?probe=5f50538338) | Jan 06, 2023 |
| ALLDOCUBE     | i1025P                      | Tablet      | [631c1eea14](https://linux-hardware.org/?probe=631c1eea14) | Jan 06, 2023 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c298dd423d](https://linux-hardware.org/?probe=c298dd423d) | Jan 05, 2023 |
| Unknown       | AM02                        | Mini pc     | [6f6c81bf78](https://linux-hardware.org/?probe=6f6c81bf78) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [47654afbbc](https://linux-hardware.org/?probe=47654afbbc) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ac3df6f289](https://linux-hardware.org/?probe=ac3df6f289) | Jan 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [437194cbc0](https://linux-hardware.org/?probe=437194cbc0) | Jan 03, 2023 |
| Lenovo        | 31900058 STD or WIN         | Desktop     | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [c8d9352d43](https://linux-hardware.org/?probe=c8d9352d43) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [ddadb5f34d](https://linux-hardware.org/?probe=ddadb5f34d) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| Dell          | Latitude 7410               | Notebook    | [3dadd543f1](https://linux-hardware.org/?probe=3dadd543f1) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [c5d2fc381a](https://linux-hardware.org/?probe=c5d2fc381a) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | Desktop     | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [04364cac9a](https://linux-hardware.org/?probe=04364cac9a) | Jan 02, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [fbf89f7693](https://linux-hardware.org/?probe=fbf89f7693) | Jan 01, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | Desktop     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | Notebook    | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [b8cd38522a](https://linux-hardware.org/?probe=b8cd38522a) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5b5e58e433](https://linux-hardware.org/?probe=5b5e58e433) | Dec 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c2a949b725](https://linux-hardware.org/?probe=c2a949b725) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7be9115c85](https://linux-hardware.org/?probe=7be9115c85) | Dec 30, 2022 |
| Google        | Nautilus                    | Convertible | [8d1977d0ae](https://linux-hardware.org/?probe=8d1977d0ae) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [af9ab4ba4d](https://linux-hardware.org/?probe=af9ab4ba4d) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [599c42b4e6](https://linux-hardware.org/?probe=599c42b4e6) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [0e619635fe](https://linux-hardware.org/?probe=0e619635fe) | Dec 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c42c0afa9b](https://linux-hardware.org/?probe=c42c0afa9b) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | Desktop     | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [06027a53fb](https://linux-hardware.org/?probe=06027a53fb) | Dec 26, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [8d2d8be057](https://linux-hardware.org/?probe=8d2d8be057) | Dec 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a986dd2bf4](https://linux-hardware.org/?probe=a986dd2bf4) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Dell          | XPS 9320                    | Notebook    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| HP            | ProBook 6470b               | Notebook    | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | Notebook    | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| HUAWEI        | KPR-WX9                     | Notebook    | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [c36792aeaa](https://linux-hardware.org/?probe=c36792aeaa) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [434eb9ba86](https://linux-hardware.org/?probe=434eb9ba86) | Dec 23, 2022 |
| Dell          | Precision M6600             | Notebook    | [00840d085c](https://linux-hardware.org/?probe=00840d085c) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | Notebook    | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | Notebook    | [94e5bdb2cb](https://linux-hardware.org/?probe=94e5bdb2cb) | Dec 22, 2022 |
| HP            | 8053                        | Desktop     | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Acer          | Spin SP314-21               | Convertible | [3f7986b3c2](https://linux-hardware.org/?probe=3f7986b3c2) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [214d584e36](https://linux-hardware.org/?probe=214d584e36) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [59f4b3b5b4](https://linux-hardware.org/?probe=59f4b3b5b4) | Dec 21, 2022 |
| ASRock        | X670E Taichi                | Desktop     | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [4e38f93dd3](https://linux-hardware.org/?probe=4e38f93dd3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [1498d2b037](https://linux-hardware.org/?probe=1498d2b037) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [36ac1009a7](https://linux-hardware.org/?probe=36ac1009a7) | Dec 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | Notebook    | [90d1d153a4](https://linux-hardware.org/?probe=90d1d153a4) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | Notebook    | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | Notebook    | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [654a04cdc4](https://linux-hardware.org/?probe=654a04cdc4) | Dec 20, 2022 |
| ATOPNUC       | MA90                        | Mini pc     | [441c2c54c5](https://linux-hardware.org/?probe=441c2c54c5) | Dec 19, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [6ab908c6b2](https://linux-hardware.org/?probe=6ab908c6b2) | Dec 19, 2022 |
| K.A.Techno... | TM1                         | Notebook    | [88e36a5d00](https://linux-hardware.org/?probe=88e36a5d00) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | Desktop     | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| ASUSTek       | Zenbook Flip UP5302ZA_UP... | Convertible | [a9925bf157](https://linux-hardware.org/?probe=a9925bf157) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [2d6dff8209](https://linux-hardware.org/?probe=2d6dff8209) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| HP            | 2000                        | Notebook    | [6273a792ae](https://linux-hardware.org/?probe=6273a792ae) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [86fbbf1bc2](https://linux-hardware.org/?probe=86fbbf1bc2) | Dec 17, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Alienware     | 15                          | Notebook    | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [8f50c0d881](https://linux-hardware.org/?probe=8f50c0d881) | Dec 15, 2022 |
| Dell          | Vostro 7590                 | Notebook    | [c758af3223](https://linux-hardware.org/?probe=c758af3223) | Dec 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| ZOTAC         | ION                         | Desktop     | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [3878d884cb](https://linux-hardware.org/?probe=3878d884cb) | Dec 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a0d408fecd](https://linux-hardware.org/?probe=a0d408fecd) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [98f6e27cac](https://linux-hardware.org/?probe=98f6e27cac) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6b47a036ab](https://linux-hardware.org/?probe=6b47a036ab) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| MSI           | B250 GAMING M3              | Desktop     | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| K.A.Techno... | TM1                         | Notebook    | [a27835f164](https://linux-hardware.org/?probe=a27835f164) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [0d527c1b1d](https://linux-hardware.org/?probe=0d527c1b1d) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | Desktop     | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [0973466d88](https://linux-hardware.org/?probe=0973466d88) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [9d2ef8adf1](https://linux-hardware.org/?probe=9d2ef8adf1) | Dec 13, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [5b4983c74e](https://linux-hardware.org/?probe=5b4983c74e) | Dec 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [221e900b1c](https://linux-hardware.org/?probe=221e900b1c) | Dec 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [4be6aa4b7a](https://linux-hardware.org/?probe=4be6aa4b7a) | Dec 13, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [559c3f32f8](https://linux-hardware.org/?probe=559c3f32f8) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [eb0d410f64](https://linux-hardware.org/?probe=eb0d410f64) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| Unknown       | X133                        | Notebook    | [694e264bcf](https://linux-hardware.org/?probe=694e264bcf) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | Notebook    | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Medion        | E4251                       | Notebook    | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [5ddea1e0e0](https://linux-hardware.org/?probe=5ddea1e0e0) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| Teclast       | F5                          | Convertible | [02e54783b6](https://linux-hardware.org/?probe=02e54783b6) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [20a5e76a25](https://linux-hardware.org/?probe=20a5e76a25) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| Medion        | E4251                       | Notebook    | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [16232a46ed](https://linux-hardware.org/?probe=16232a46ed) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e843a9c61d](https://linux-hardware.org/?probe=e843a9c61d) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | Notebook    | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | Desktop     | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| IPASON        | MaxBook P1X                 | Notebook    | [c699081c87](https://linux-hardware.org/?probe=c699081c87) | Dec 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d6666dccec](https://linux-hardware.org/?probe=d6666dccec) | Dec 08, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [c6895362e6](https://linux-hardware.org/?probe=c6895362e6) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | Desktop     | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [be3a0b7c33](https://linux-hardware.org/?probe=be3a0b7c33) | Dec 07, 2022 |
| BESSTAR Te... | U820                        | Notebook    | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [3a8a41be2a](https://linux-hardware.org/?probe=3a8a41be2a) | Dec 07, 2022 |
| HP            | 245 G8                      | Notebook    | [2fbc616550](https://linux-hardware.org/?probe=2fbc616550) | Dec 07, 2022 |
| Clevo         | P150HMx                     | Notebook    | [f1500b1665](https://linux-hardware.org/?probe=f1500b1665) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [037c8e9cbc](https://linux-hardware.org/?probe=037c8e9cbc) | Dec 06, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Dell          | G15 5515                    | Notebook    | [63fed6d448](https://linux-hardware.org/?probe=63fed6d448) | Dec 06, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [3e1e88ac7a](https://linux-hardware.org/?probe=3e1e88ac7a) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | Notebook    | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [61c23e2501](https://linux-hardware.org/?probe=61c23e2501) | Dec 06, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [7f9c0a0974](https://linux-hardware.org/?probe=7f9c0a0974) | Dec 06, 2022 |
| Dell          | G5 5505                     | Notebook    | [c36399d764](https://linux-hardware.org/?probe=c36399d764) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| Medion        | E4251                       | Notebook    | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [6c726b6eb7](https://linux-hardware.org/?probe=6c726b6eb7) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [99b35ee6a3](https://linux-hardware.org/?probe=99b35ee6a3) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [8a91af8c9d](https://linux-hardware.org/?probe=8a91af8c9d) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ddd1487d81](https://linux-hardware.org/?probe=ddd1487d81) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| HP            | 8053                        | Desktop     | [5fad592ef3](https://linux-hardware.org/?probe=5fad592ef3) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [3ee55cc441](https://linux-hardware.org/?probe=3ee55cc441) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a8e17ad39c](https://linux-hardware.org/?probe=a8e17ad39c) | Dec 04, 2022 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [7990b26bbf](https://linux-hardware.org/?probe=7990b26bbf) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | Notebook    | [05ae64c1b8](https://linux-hardware.org/?probe=05ae64c1b8) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | Notebook    | [ae6745045a](https://linux-hardware.org/?probe=ae6745045a) | Dec 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b3b5eb90e5](https://linux-hardware.org/?probe=b3b5eb90e5) | Dec 03, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [9950cb061d](https://linux-hardware.org/?probe=9950cb061d) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | Notebook    | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | Notebook    | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| HP            | Pavilion Laptop             | Notebook    | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [04e81bb56a](https://linux-hardware.org/?probe=04e81bb56a) | Dec 02, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a203c920d4](https://linux-hardware.org/?probe=a203c920d4) | Dec 01, 2022 |
| Dell          | Precision 5540              | Notebook    | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [72ab240431](https://linux-hardware.org/?probe=72ab240431) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [952e89e25d](https://linux-hardware.org/?probe=952e89e25d) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [f5f86becf7](https://linux-hardware.org/?probe=f5f86becf7) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [2c0cb92f23](https://linux-hardware.org/?probe=2c0cb92f23) | Nov 29, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [b34e3370f4](https://linux-hardware.org/?probe=b34e3370f4) | Nov 29, 2022 |
| Samsung       | 730QED                      | Convertible | [5d62977479](https://linux-hardware.org/?probe=5d62977479) | Nov 29, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [45097ff070](https://linux-hardware.org/?probe=45097ff070) | Nov 29, 2022 |
| HP            | Notebook                    | Notebook    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460s 20FAS16J0... | Notebook    | [142a1e8a94](https://linux-hardware.org/?probe=142a1e8a94) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [69a6535286](https://linux-hardware.org/?probe=69a6535286) | Nov 28, 2022 |
| Razer         | Blade                       | Notebook    | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a1c088bc35](https://linux-hardware.org/?probe=a1c088bc35) | Nov 28, 2022 |
| Dell          | 09WH54 A00                  | Desktop     | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [0dcd2bdc50](https://linux-hardware.org/?probe=0dcd2bdc50) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [620cab185f](https://linux-hardware.org/?probe=620cab185f) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| HP            | 3397                        | Desktop     | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [7e65f428cc](https://linux-hardware.org/?probe=7e65f428cc) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | Notebook    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| Alienware     | 15                          | Notebook    | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [b4c105c294](https://linux-hardware.org/?probe=b4c105c294) | Nov 24, 2022 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [6b71a5917c](https://linux-hardware.org/?probe=6b71a5917c) | Nov 24, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| ASUSTek       | PRIME Z690-P                | Notebook    | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [60c1698203](https://linux-hardware.org/?probe=60c1698203) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6722142846](https://linux-hardware.org/?probe=6722142846) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [bb043b7575](https://linux-hardware.org/?probe=bb043b7575) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ec1395a487](https://linux-hardware.org/?probe=ec1395a487) | Nov 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | Desktop     | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | Notebook    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [95686093ce](https://linux-hardware.org/?probe=95686093ce) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [144470ec16](https://linux-hardware.org/?probe=144470ec16) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [aacdefc31b](https://linux-hardware.org/?probe=aacdefc31b) | Nov 17, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | Desktop     | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | Desktop     | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| HP            | Compaq 15                   | Notebook    | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Google        | Boten                       | Notebook    | [105e91dd04](https://linux-hardware.org/?probe=105e91dd04) | Nov 16, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [d4b09c09f0](https://linux-hardware.org/?probe=d4b09c09f0) | Nov 15, 2022 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [dcffe478fe](https://linux-hardware.org/?probe=dcffe478fe) | Nov 14, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [e6ef3b56eb](https://linux-hardware.org/?probe=e6ef3b56eb) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | Notebook    | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [e53d77c404](https://linux-hardware.org/?probe=e53d77c404) | Nov 14, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [41dbab85c0](https://linux-hardware.org/?probe=41dbab85c0) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [65526a6a14](https://linux-hardware.org/?probe=65526a6a14) | Nov 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ca85c59fad](https://linux-hardware.org/?probe=ca85c59fad) | Nov 13, 2022 |
| MSI           | Z97A GAMING 7               | Desktop     | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Dell          | G15 5510                    | Notebook    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | Desktop     | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| AZW           | SER V01                     | Mini pc     | [5123518533](https://linux-hardware.org/?probe=5123518533) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [7827dd0f86](https://linux-hardware.org/?probe=7827dd0f86) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [64d896b971](https://linux-hardware.org/?probe=64d896b971) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | Desktop     | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [950c263b8a](https://linux-hardware.org/?probe=950c263b8a) | Nov 10, 2022 |
| Dell          | Latitude E6330              | Notebook    | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| Acer          | Aspire V5-123               | Notebook    | [7e9ca0bb77](https://linux-hardware.org/?probe=7e9ca0bb77) | Nov 09, 2022 |
| HP            | ENVY 15                     | Notebook    | [716fe10a4a](https://linux-hardware.org/?probe=716fe10a4a) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | Notebook    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d93bdbd43a](https://linux-hardware.org/?probe=d93bdbd43a) | Nov 07, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [7f372be9dc](https://linux-hardware.org/?probe=7f372be9dc) | Nov 07, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | Desktop     | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | Desktop     | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | Desktop     | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | Notebook    | [f18d0b8b8a](https://linux-hardware.org/?probe=f18d0b8b8a) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | Notebook    | [141de7e9a7](https://linux-hardware.org/?probe=141de7e9a7) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| HP            | Spectre x360 Conv 15        | Convertible | [f1d5f7705f](https://linux-hardware.org/?probe=f1d5f7705f) | Nov 04, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [d70f962654](https://linux-hardware.org/?probe=d70f962654) | Nov 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3428f76054](https://linux-hardware.org/?probe=3428f76054) | Nov 04, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | Desktop     | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [ca5335acd5](https://linux-hardware.org/?probe=ca5335acd5) | Nov 03, 2022 |
| Dell          | Latitude 7280               | Notebook    | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| HP            | 8054                        | Desktop     | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| Dell          | Precision 7530              | Notebook    | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [ef6bcab217](https://linux-hardware.org/?probe=ef6bcab217) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| Lenovo        | ThinkPad L460 20FVS1Y500    | Notebook    | [5fc669ddbe](https://linux-hardware.org/?probe=5fc669ddbe) | Nov 01, 2022 |
| SANTECH       | NL5xRU                      | Notebook    | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| HP            | 3397                        | Desktop     | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | Notebook    | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| Alienware     | 15 R3                       | Notebook    | [4659975000](https://linux-hardware.org/?probe=4659975000) | Oct 31, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [0e06dcc642](https://linux-hardware.org/?probe=0e06dcc642) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| Lenovo        | MAHOBAY Win8 STD EM DPK ... | All in one  | [4b37b09299](https://linux-hardware.org/?probe=4b37b09299) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | Desktop     | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [cef88d9d62](https://linux-hardware.org/?probe=cef88d9d62) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | Notebook    | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| Chuwi         | LapBook Pro                 | Notebook    | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [806e4d754d](https://linux-hardware.org/?probe=806e4d754d) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [d6ccf0a2d8](https://linux-hardware.org/?probe=d6ccf0a2d8) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [d5c2f29c22](https://linux-hardware.org/?probe=d5c2f29c22) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | Desktop     | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [aec6edc8a0](https://linux-hardware.org/?probe=aec6edc8a0) | Oct 28, 2022 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [58d46fb47f](https://linux-hardware.org/?probe=58d46fb47f) | Oct 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [f575803f23](https://linux-hardware.org/?probe=f575803f23) | Oct 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [664bf1184f](https://linux-hardware.org/?probe=664bf1184f) | Oct 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [b9c616b406](https://linux-hardware.org/?probe=b9c616b406) | Oct 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [d9f63cbff8](https://linux-hardware.org/?probe=d9f63cbff8) | Oct 26, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26d539c606](https://linux-hardware.org/?probe=26d539c606) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ffa2d93859](https://linux-hardware.org/?probe=ffa2d93859) | Oct 26, 2022 |
| RuggedPC      | RuggedBookJ87               | Tablet      | [74d39d268f](https://linux-hardware.org/?probe=74d39d268f) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [642cfbc2d7](https://linux-hardware.org/?probe=642cfbc2d7) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [300126736b](https://linux-hardware.org/?probe=300126736b) | Oct 26, 2022 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [1ded224c69](https://linux-hardware.org/?probe=1ded224c69) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Unknown       | 1.0                         | Desktop     | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [bb90eb1ad1](https://linux-hardware.org/?probe=bb90eb1ad1) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b2bb88f27f](https://linux-hardware.org/?probe=b2bb88f27f) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [7e6d814d87](https://linux-hardware.org/?probe=7e6d814d87) | Oct 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [15ced71b20](https://linux-hardware.org/?probe=15ced71b20) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [8994af98ff](https://linux-hardware.org/?probe=8994af98ff) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fc7326f81b](https://linux-hardware.org/?probe=fc7326f81b) | Oct 24, 2022 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [37028111aa](https://linux-hardware.org/?probe=37028111aa) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [bc30c6555a](https://linux-hardware.org/?probe=bc30c6555a) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [667d235a8f](https://linux-hardware.org/?probe=667d235a8f) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| HP            | 828A                        | Desktop     | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| Tactus        | GeoBook_240                 | Notebook    | [5331bf15bd](https://linux-hardware.org/?probe=5331bf15bd) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | Desktop     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c75d0e252d](https://linux-hardware.org/?probe=c75d0e252d) | Oct 23, 2022 |
| HP            | 1489                        | All in one  | [3b3379c0e2](https://linux-hardware.org/?probe=3b3379c0e2) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| Global Dis... | W11651                      | Notebook    | [9cf1e2df07](https://linux-hardware.org/?probe=9cf1e2df07) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | Legion 5 82B5               | Notebook    | [3d67f01531](https://linux-hardware.org/?probe=3d67f01531) | Oct 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [ab90111e61](https://linux-hardware.org/?probe=ab90111e61) | Oct 21, 2022 |
| Dell          | Latitude E6400              | Notebook    | [d899ab2ef4](https://linux-hardware.org/?probe=d899ab2ef4) | Oct 21, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| Medion        | S15449                      | Notebook    | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| HP            | ProBook 6550b               | Notebook    | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [30bf540299](https://linux-hardware.org/?probe=30bf540299) | Oct 19, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [e07159c158](https://linux-hardware.org/?probe=e07159c158) | Oct 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [f329d7485d](https://linux-hardware.org/?probe=f329d7485d) | Oct 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [419bdfa23d](https://linux-hardware.org/?probe=419bdfa23d) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [0910d29ded](https://linux-hardware.org/?probe=0910d29ded) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [469118097a](https://linux-hardware.org/?probe=469118097a) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| HP            | ENVY 15                     | Notebook    | [17681478e1](https://linux-hardware.org/?probe=17681478e1) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [460ceb1307](https://linux-hardware.org/?probe=460ceb1307) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [bb58a322f3](https://linux-hardware.org/?probe=bb58a322f3) | Oct 14, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | Desktop     | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [2188336cf7](https://linux-hardware.org/?probe=2188336cf7) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a1b08d912](https://linux-hardware.org/?probe=7a1b08d912) | Oct 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [8990bf0049](https://linux-hardware.org/?probe=8990bf0049) | Oct 13, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3f808f36a0](https://linux-hardware.org/?probe=3f808f36a0) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [705931711b](https://linux-hardware.org/?probe=705931711b) | Oct 13, 2022 |
| Dell          | Latitude E7250              | Notebook    | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [1bbc611d89](https://linux-hardware.org/?probe=1bbc611d89) | Oct 12, 2022 |
| AVITA         | NS14A6                      | Notebook    | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| AVITA         | NS14A6                      | Notebook    | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [10ab944320](https://linux-hardware.org/?probe=10ab944320) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| HP            | 8460                        | Desktop     | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | Desktop     | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [09ba76a57e](https://linux-hardware.org/?probe=09ba76a57e) | Oct 09, 2022 |
| ASUSTek       | P6X58-E-WS                  | Desktop     | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Gigabyte      | MC62-G40-00 01000100        | Server      | [a4d3ab40a5](https://linux-hardware.org/?probe=a4d3ab40a5) | Oct 09, 2022 |
| Dell          | Precision 5560              | Notebook    | [001c5b0c94](https://linux-hardware.org/?probe=001c5b0c94) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| Dell          | Latitude 5310               | Notebook    | [f694e6b10e](https://linux-hardware.org/?probe=f694e6b10e) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [49802b54cd](https://linux-hardware.org/?probe=49802b54cd) | Oct 08, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [4afa1df235](https://linux-hardware.org/?probe=4afa1df235) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [d0584d3672](https://linux-hardware.org/?probe=d0584d3672) | Oct 08, 2022 |
| Dell          | 0NW73C A00                  | Desktop     | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| Dell          | 0M9KCM A01                  | Desktop     | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [829a14598f](https://linux-hardware.org/?probe=829a14598f) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [9b8147c1f7](https://linux-hardware.org/?probe=9b8147c1f7) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Toshiba       | Encore                      | Notebook    | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| CyberPower... | FANG Pro                    | Notebook    | [e8734135b0](https://linux-hardware.org/?probe=e8734135b0) | Oct 05, 2022 |
| Lenovo        | N23 80UR                    | Convertible | [f6bf19c41a](https://linux-hardware.org/?probe=f6bf19c41a) | Oct 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [4ba2e11c73](https://linux-hardware.org/?probe=4ba2e11c73) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Jumper        | Ezpad                       | Tablet      | [20a54bbe35](https://linux-hardware.org/?probe=20a54bbe35) | Oct 04, 2022 |
| Jumper        | Ezpad                       | Tablet      | [a887c036ac](https://linux-hardware.org/?probe=a887c036ac) | Oct 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| HP            | 21D0                        | Desktop     | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | Notebook    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [ca89628082](https://linux-hardware.org/?probe=ca89628082) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| GPD           | G1621-02                    | Notebook    | [1f88eb2bec](https://linux-hardware.org/?probe=1f88eb2bec) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [9c3f9bb60e](https://linux-hardware.org/?probe=9c3f9bb60e) | Oct 03, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [d433417836](https://linux-hardware.org/?probe=d433417836) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [f58849d2c7](https://linux-hardware.org/?probe=f58849d2c7) | Oct 03, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [4283f9a4bd](https://linux-hardware.org/?probe=4283f9a4bd) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [831cd8e80f](https://linux-hardware.org/?probe=831cd8e80f) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| HP            | ProBook 6470b               | Notebook    | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | 250 G3                      | Notebook    | [753ef53a5a](https://linux-hardware.org/?probe=753ef53a5a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [012add7349](https://linux-hardware.org/?probe=012add7349) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | Desktop     | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| Sony          | SVF15N17CXB                 | Notebook    | [5082dde27d](https://linux-hardware.org/?probe=5082dde27d) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Irbis         | NB121                       | Notebook    | [a2eb8c8af1](https://linux-hardware.org/?probe=a2eb8c8af1) | Sep 30, 2022 |
| Dell          | 07PR60 A01                  | Desktop     | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Irbis         | NB121                       | Notebook    | [90a0ae1cf9](https://linux-hardware.org/?probe=90a0ae1cf9) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [3ad60e2d21](https://linux-hardware.org/?probe=3ad60e2d21) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| HP            | Notebook                    | Notebook    | [e172f83238](https://linux-hardware.org/?probe=e172f83238) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [353324cbfd](https://linux-hardware.org/?probe=353324cbfd) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [a1bee52021](https://linux-hardware.org/?probe=a1bee52021) | Sep 29, 2022 |
| ASRock        | X399M Taichi                | Desktop     | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [25d3fc37f5](https://linux-hardware.org/?probe=25d3fc37f5) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [f5ddf4a2b4](https://linux-hardware.org/?probe=f5ddf4a2b4) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | Desktop     | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [72d80e02c9](https://linux-hardware.org/?probe=72d80e02c9) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [47b22afda2](https://linux-hardware.org/?probe=47b22afda2) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [9b3a3858bc](https://linux-hardware.org/?probe=9b3a3858bc) | Sep 28, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [9a1e3a98ab](https://linux-hardware.org/?probe=9a1e3a98ab) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ebfbdd37b8](https://linux-hardware.org/?probe=ebfbdd37b8) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [09d154c2f2](https://linux-hardware.org/?probe=09d154c2f2) | Sep 27, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [e27e7bfd76](https://linux-hardware.org/?probe=e27e7bfd76) | Sep 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Lenovo        | ThinkPad T460p 20FW000EG... | Notebook    | [60138ee2f9](https://linux-hardware.org/?probe=60138ee2f9) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4b6ce98f70](https://linux-hardware.org/?probe=4b6ce98f70) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| ASUSTek       | N45SF                       | Notebook    | [7461bd2562](https://linux-hardware.org/?probe=7461bd2562) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [0d1b8fe301](https://linux-hardware.org/?probe=0d1b8fe301) | Sep 25, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2fa3578315](https://linux-hardware.org/?probe=2fa3578315) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| HP            | ENVY x360 Convert13-ay00... | Convertible | [41abb17737](https://linux-hardware.org/?probe=41abb17737) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [f9c071cdd8](https://linux-hardware.org/?probe=f9c071cdd8) | Sep 23, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [321edce78d](https://linux-hardware.org/?probe=321edce78d) | Sep 23, 2022 |
| Huanan        | X99-TF                      | Desktop     | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [af65739ccc](https://linux-hardware.org/?probe=af65739ccc) | Sep 21, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6b012b0a87](https://linux-hardware.org/?probe=6b012b0a87) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | Laptop                      | Notebook    | [0cbc7e4f5a](https://linux-hardware.org/?probe=0cbc7e4f5a) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| HP            | ENVY 15                     | Notebook    | [388547d18c](https://linux-hardware.org/?probe=388547d18c) | Sep 21, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [6ffce551a0](https://linux-hardware.org/?probe=6ffce551a0) | Sep 21, 2022 |
| HP            | ProBook 4520s               | Notebook    | [af4a575c52](https://linux-hardware.org/?probe=af4a575c52) | Sep 20, 2022 |
| Minix         | NEO G41V-4 Max              | Desktop     | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f1973349](https://linux-hardware.org/?probe=f9f1973349) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Gateway       | NV57H                       | Notebook    | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [75cc4fa084](https://linux-hardware.org/?probe=75cc4fa084) | Sep 19, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [97e2956728](https://linux-hardware.org/?probe=97e2956728) | Sep 19, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [1cbec0f70e](https://linux-hardware.org/?probe=1cbec0f70e) | Sep 19, 2022 |
| HP            | 212B                        | Desktop     | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b0e746792f](https://linux-hardware.org/?probe=b0e746792f) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| Dell          | Precision M4800             | Notebook    | [73d00fe344](https://linux-hardware.org/?probe=73d00fe344) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [bbd1eb7810](https://linux-hardware.org/?probe=bbd1eb7810) | Sep 18, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [13b23fabb7](https://linux-hardware.org/?probe=13b23fabb7) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| Samsung       | 950QCG                      | Convertible | [92aaede7a0](https://linux-hardware.org/?probe=92aaede7a0) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [f045e1f138](https://linux-hardware.org/?probe=f045e1f138) | Sep 17, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [8d9f049d7e](https://linux-hardware.org/?probe=8d9f049d7e) | Sep 16, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [05b029f919](https://linux-hardware.org/?probe=05b029f919) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [31c810e744](https://linux-hardware.org/?probe=31c810e744) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [00bcfb51bd](https://linux-hardware.org/?probe=00bcfb51bd) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | Desktop     | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [df5d5b4f0d](https://linux-hardware.org/?probe=df5d5b4f0d) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [c9df1f2514](https://linux-hardware.org/?probe=c9df1f2514) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [b62bd233c2](https://linux-hardware.org/?probe=b62bd233c2) | Sep 13, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 2515      | 37.87%  |
| Manjaro 22.0.0 | 323       | 4.86%   |
| Manjaro 20.1   | 291       | 4.38%   |
| Manjaro 20.2.1 | 283       | 4.26%   |
| Manjaro 20.2   | 243       | 3.66%   |
| Manjaro 20.0.3 | 223       | 3.36%   |
| Manjaro 21.2.6 | 176       | 2.65%   |
| Manjaro 21.1.0 | 149       | 2.24%   |
| Manjaro 18.1.5 | 143       | 2.15%   |
| Manjaro 21.2.0 | 127       | 1.91%   |
| Manjaro 21.2.5 | 126       | 1.9%    |
| Manjaro 21.1.6 | 114       | 1.72%   |
| Manjaro 21.0.7 | 113       | 1.7%    |
| Manjaro 20.0   | 101       | 1.52%   |
| Manjaro 19.0.2 | 97        | 1.46%   |
| Manjaro 18.0.4 | 96        | 1.45%   |
| Manjaro 21.0   | 87        | 1.31%   |
| Manjaro 21.0.5 | 80        | 1.2%    |
| Manjaro 20.1.2 | 80        | 1.2%    |
| Manjaro 21.2.3 | 74        | 1.11%   |
| Manjaro 21.2.1 | 73        | 1.1%    |
| Manjaro 20.1.1 | 71        | 1.07%   |
| Manjaro 20.0.1 | 69        | 1.04%   |
| Manjaro 21.3.7 | 56        | 0.84%   |
| Manjaro 21.0.4 | 50        | 0.75%   |
| Manjaro 21.3.6 | 49        | 0.74%   |
| Manjaro 21.2.2 | 46        | 0.69%   |
| Manjaro 21.2.4 | 45        | 0.68%   |
| Manjaro 21.1.2 | 41        | 0.62%   |
| Manjaro 21.1.4 | 37        | 0.56%   |
| Manjaro 21.0.1 | 36        | 0.54%   |
| Manjaro 21.0.2 | 34        | 0.51%   |
| Manjaro 21.3.1 | 32        | 0.48%   |
| Manjaro 21.3.0 | 31        | 0.47%   |
| Manjaro 21.0.3 | 31        | 0.47%   |
| Manjaro 21.1.1 | 30        | 0.45%   |
| Manjaro 22.0   | 29        | 0.44%   |
| Manjaro 21.1.3 | 29        | 0.44%   |
| Manjaro 21.2rc | 28        | 0.42%   |
| Manjaro 18.1.4 | 27        | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 6103      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 294       | 4.07%   |
| 5.13.19-2-MANJARO | 179       | 2.48%   |
| 5.8.6-1-MANJARO   | 140       | 1.94%   |
| 5.9.11-3-MANJARO  | 128       | 1.77%   |
| 5.8.11-1-MANJARO  | 122       | 1.69%   |
| 5.15.28-1-MANJARO | 118       | 1.64%   |
| 5.10.42-1-MANJARO | 102       | 1.41%   |
| 6.1.1-1-MANJARO   | 101       | 1.4%    |
| 5.8.18-1-MANJARO  | 101       | 1.4%    |
| 5.15.32-1-MANJARO | 100       | 1.39%   |
| 5.15.12-1-MANJARO | 82        | 1.14%   |
| 5.6.16-1-MANJARO  | 74        | 1.03%   |
| 5.15.60-1-MANJARO | 74        | 1.03%   |
| 5.8.16-2-MANJARO  | 73        | 1.01%   |
| 5.10.2-2-MANJARO  | 65        | 0.9%    |
| 5.15.65-1-MANJARO | 62        | 0.86%   |
| 5.7.9-1-MANJARO   | 61        | 0.85%   |
| 5.10.36-2-MANJARO | 61        | 0.85%   |
| 5.6.19-2-MANJARO  | 60        | 0.83%   |
| 5.10.7-3-MANJARO  | 60        | 0.83%   |
| 5.7.0-3-MANJARO   | 58        | 0.8%    |
| 5.8.3-2-MANJARO   | 57        | 0.79%   |
| 5.6.15-1-MANJARO  | 57        | 0.79%   |
| 5.12.9-1-MANJARO  | 54        | 0.75%   |
| 5.7.17-2-MANJARO  | 52        | 0.72%   |
| 5.15.78-1-MANJARO | 51        | 0.71%   |
| 5.15.41-1-MANJARO | 51        | 0.71%   |
| 5.14.10-1-MANJARO | 51        | 0.71%   |
| 5.9.1-1-MANJARO   | 50        | 0.69%   |
| 5.17.1-3-MANJARO  | 49        | 0.68%   |
| 5.10.23-1-MANJARO | 49        | 0.68%   |
| 5.16.14-1-MANJARO | 48        | 0.67%   |
| 5.15.7-1-MANJARO  | 48        | 0.67%   |
| 5.15.74-3-MANJARO | 47        | 0.65%   |
| 5.11.6-1-MANJARO  | 47        | 0.65%   |
| 5.15.85-1-MANJARO | 45        | 0.62%   |
| 5.15.25-1-MANJARO | 45        | 0.62%   |
| 5.10.34-1-MANJARO | 45        | 0.62%   |
| 5.6.12-1-MANJARO  | 44        | 0.61%   |
| 5.6.7-1-MANJARO   | 43        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 294       | 4.08%   |
| 5.13.19 | 180       | 2.5%    |
| 5.8.6   | 140       | 1.94%   |
| 5.9.11  | 135       | 1.87%   |
| 5.8.11  | 123       | 1.71%   |
| 5.15.28 | 118       | 1.64%   |
| 5.10.42 | 102       | 1.41%   |
| 6.1.1   | 101       | 1.4%    |
| 5.8.18  | 101       | 1.4%    |
| 5.15.32 | 101       | 1.4%    |
| 5.15.12 | 82        | 1.14%   |
| 5.8.16  | 74        | 1.03%   |
| 5.6.16  | 74        | 1.03%   |
| 5.15.60 | 74        | 1.03%   |
| 5.7.0   | 73        | 1.01%   |
| 5.9.1   | 69        | 0.96%   |
| 5.6.19  | 66        | 0.92%   |
| 5.10.2  | 65        | 0.9%    |
| 5.15.65 | 62        | 0.86%   |
| 5.10.7  | 62        | 0.86%   |
| 5.7.9   | 61        | 0.85%   |
| 5.17.1  | 61        | 0.85%   |
| 5.10.36 | 61        | 0.85%   |
| 5.8.3   | 58        | 0.8%    |
| 5.6.15  | 57        | 0.79%   |
| 5.12.9  | 54        | 0.75%   |
| 5.7.17  | 53        | 0.73%   |
| 5.15.78 | 51        | 0.71%   |
| 5.15.41 | 51        | 0.71%   |
| 5.14.10 | 51        | 0.71%   |
| 5.15.7  | 50        | 0.69%   |
| 5.10.23 | 49        | 0.68%   |
| 5.16.14 | 48        | 0.67%   |
| 5.11.6  | 48        | 0.67%   |
| 5.15.74 | 47        | 0.65%   |
| 5.6.12  | 46        | 0.64%   |
| 5.15.2  | 46        | 0.64%   |
| 5.15.85 | 45        | 0.62%   |
| 5.15.25 | 45        | 0.62%   |
| 5.10.34 | 45        | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1154      | 16.95%  |
| 5.10    | 910       | 13.36%  |
| 5.4     | 627       | 9.21%   |
| 5.9     | 589       | 8.65%   |
| 5.8     | 553       | 8.12%   |
| 5.6     | 393       | 5.77%   |
| 5.13    | 357       | 5.24%   |
| 5.7     | 264       | 3.88%   |
| 4.19    | 198       | 2.91%   |
| 5.11    | 185       | 2.72%   |
| 5.16    | 175       | 2.57%   |
| 5.12    | 157       | 2.31%   |
| 6.1     | 153       | 2.25%   |
| 5.14    | 152       | 2.23%   |
| 5.17    | 142       | 2.09%   |
| 5.19    | 137       | 2.01%   |
| 6.0     | 135       | 1.98%   |
| 5.18    | 129       | 1.89%   |
| 5.5     | 109       | 1.6%    |
| 5.3     | 92        | 1.35%   |
| 4.14    | 60        | 0.88%   |
| 5.2     | 41        | 0.6%    |
| 5.0     | 30        | 0.44%   |
| 5.1     | 26        | 0.38%   |
| 4.20    | 14        | 0.21%   |
| 4.18    | 12        | 0.18%   |
| 4.9     | 4         | 0.06%   |
| 4.16    | 4         | 0.06%   |
| 4.17    | 3         | 0.04%   |
| 4.7     | 2         | 0.03%   |
| 4.4     | 2         | 0.03%   |
| 6.2     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6100      | 99.95%  |
| i686    | 2         | 0.03%   |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 2169      | 34.3%   |
| XFCE                     | 1393      | 22.03%  |
| GNOME                    | 1341      | 21.21%  |
| KDE                      | 556       | 8.79%   |
| Unknown                  | 302       | 4.78%   |
| X-Cinnamon               | 165       | 2.61%   |
| i3                       | 125       | 1.98%   |
| MATE                     | 59        | 0.93%   |
| Cinnamon                 | 56        | 0.89%   |
| Deepin                   | 50        | 0.79%   |
| Budgie                   | 29        | 0.46%   |
| Awesome                  | 16        | 0.25%   |
| LXQt                     | 15        | 0.24%   |
| sway                     | 9         | 0.14%   |
| LXDE                     | 7         | 0.11%   |
| Bspwm                    | 5         | 0.08%   |
| i3-with-shmlog           | 4         | 0.06%   |
| GNOME Classic            | 3         | 0.05%   |
| DWM                      | 3         | 0.05%   |
| LeftWM                   | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNOME Flashback          | 2         | 0.03%   |
| Enlightenment            | 2         | 0.03%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| Unity                    | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.02%   |
| qtile                    | 1         | 0.02%   |
| openbox                  | 1         | 0.02%   |
| herbstluftwm             | 1         | 0.02%   |
| /usr/bin/openbox-session | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5285      | 85.23%  |
| Wayland | 728       | 11.74%  |
| Unknown | 129       | 2.08%   |
| Tty     | 59        | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2494      | 39.8%   |
| SDDM    | 1603      | 25.58%  |
| LightDM | 1109      | 17.7%   |
| GDM     | 820       | 13.09%  |
| TDM     | 218       | 3.48%   |
| LXDM    | 9         | 0.14%   |
| GREETD  | 4         | 0.06%   |
| SLiM    | 3         | 0.05%   |
| XDM     | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| LYNDE   | 1         | 0.02%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2580      | 41.68%  |
| de_DE   | 477       | 7.71%   |
| ru_RU   | 437       | 7.06%   |
| Unknown | 407       | 6.58%   |
| en_GB   | 402       | 6.49%   |
| pt_BR   | 242       | 3.91%   |
| fr_FR   | 165       | 2.67%   |
| en_CA   | 135       | 2.18%   |
| es_ES   | 134       | 2.16%   |
| it_IT   | 130       | 2.1%    |
| pl_PL   | 115       | 1.86%   |
| en_AU   | 80        | 1.29%   |
| en_IN   | 73        | 1.18%   |
| es_MX   | 51        | 0.82%   |
| zh_CN   | 46        | 0.74%   |
| de_AT   | 40        | 0.65%   |
| ru_UA   | 39        | 0.63%   |
| nl_NL   | 36        | 0.58%   |
| es_AR   | 31        | 0.5%    |
| en_IE   | 28        | 0.45%   |
| sv_SE   | 26        | 0.42%   |
| pt_PT   | 21        | 0.34%   |
| fi_FI   | 21        | 0.34%   |
| es_CL   | 21        | 0.34%   |
| C       | 21        | 0.34%   |
| cs_CZ   | 20        | 0.32%   |
| en_ZA   | 19        | 0.31%   |
| en_DK   | 19        | 0.31%   |
| tr_TR   | 18        | 0.29%   |
| hu_HU   | 18        | 0.29%   |
| en_NZ   | 18        | 0.29%   |
| de_CH   | 17        | 0.27%   |
| es_CO   | 16        | 0.26%   |
| uk_UA   | 15        | 0.24%   |
| en_PH   | 14        | 0.23%   |
| fr_CA   | 13        | 0.21%   |
| nl_BE   | 12        | 0.19%   |
| en_IL   | 12        | 0.19%   |
| en_DE   | 11        | 0.18%   |
| el_GR   | 11        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3412      | 54.9%   |
| EFI  | 2803      | 45.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5209      | 84.44%  |
| Btrfs    | 553       | 8.96%   |
| Overlay  | 134       | 2.17%   |
| Unknown  | 129       | 2.09%   |
| Xfs      | 76        | 1.23%   |
| F2fs     | 26        | 0.42%   |
| Tmpfs    | 23        | 0.37%   |
| Ext3     | 5         | 0.08%   |
| Zfs      | 4         | 0.06%   |
| Ext2     | 4         | 0.06%   |
| Reiserfs | 3         | 0.05%   |
| XXXX     | 1         | 0.02%   |
| XXXfs    | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2898      | 46.55%  |
| Unknown | 2754      | 44.24%  |
| MBR     | 573       | 9.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5405      | 87.22%  |
| Yes       | 792       | 12.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4159      | 66.99%  |
| Yes       | 2049      | 33.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1128      | 18.48%  |
| Lenovo              | 1001      | 16.4%   |
| Hewlett-Packard     | 784       | 12.85%  |
| Dell                | 647       | 10.6%   |
| Gigabyte Technology | 501       | 8.21%   |
| MSI                 | 473       | 7.75%   |
| Acer                | 309       | 5.06%   |
| ASRock              | 258       | 4.23%   |
| Apple               | 123       | 2.02%   |
| Intel               | 82        | 1.34%   |
| Samsung Electronics | 63        | 1.03%   |
| Toshiba             | 62        | 1.02%   |
| HUAWEI              | 55        | 0.9%    |
| Unknown             | 37        | 0.61%   |
| Timi                | 36        | 0.59%   |
| Fujitsu             | 33        | 0.54%   |
| Notebook            | 29        | 0.48%   |
| Sony                | 28        | 0.46%   |
| Google              | 25        | 0.41%   |
| Microsoft           | 18        | 0.29%   |
| Biostar             | 18        | 0.29%   |
| Pegatron            | 17        | 0.28%   |
| Medion              | 17        | 0.28%   |
| Alienware           | 16        | 0.26%   |
| TUXEDO              | 15        | 0.25%   |
| Razer               | 14        | 0.23%   |
| AZW                 | 14        | 0.23%   |
| Huanan              | 12        | 0.2%    |
| Schenker            | 11        | 0.18%   |
| Positivo            | 10        | 0.16%   |
| Packard Bell        | 10        | 0.16%   |
| Foxconn             | 10        | 0.16%   |
| LG Electronics      | 9         | 0.15%   |
| BESSTAR Tech        | 9         | 0.15%   |
| System76            | 8         | 0.13%   |
| ZOTAC               | 7         | 0.11%   |
| TrekStor            | 7         | 0.11%   |
| Panasonic           | 7         | 0.11%   |
| HONOR               | 7         | 0.11%   |
| ECS                 | 7         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 67        | 1.1%    |
| Unknown                             | 49        | 0.8%    |
| Gigabyte B450M DS3H                 | 26        | 0.43%   |
| MSI MS-7C37                         | 23        | 0.38%   |
| MSI MS-7C02                         | 23        | 0.38%   |
| HP Notebook                         | 20        | 0.33%   |
| ASUS TUF Gaming X570-PLUS           | 20        | 0.33%   |
| ASUS PRIME A320M-K                  | 18        | 0.29%   |
| ASRock B450M Pro4                   | 16        | 0.26%   |
| MSI MS-7C91                         | 15        | 0.25%   |
| MSI MS-7B79                         | 15        | 0.25%   |
| MSI MS-7B86                         | 13        | 0.21%   |
| Lenovo Legion 5 15ARH05 82B5        | 13        | 0.21%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 13        | 0.21%   |
| Dell XPS 13 9310                    | 13        | 0.21%   |
| ASUS ROG STRIX B450-F GAMING        | 13        | 0.21%   |
| MSI MS-7A38                         | 12        | 0.2%    |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 12        | 0.2%    |
| Gigabyte X570 AORUS ELITE           | 12        | 0.2%    |
| Dell XPS 15 9500                    | 12        | 0.2%    |
| ASUS TUF Gaming B550M-PLUS          | 12        | 0.2%    |
| ASUS PRIME B450M-A                  | 12        | 0.2%    |
| HP Pavilion Gaming Laptop 15-ec1xxx | 11        | 0.18%   |
| Dell OptiPlex 9020                  | 11        | 0.18%   |
| ASUS ROG STRIX B550-F GAMING        | 11        | 0.18%   |
| ASUS PRIME B350-PLUS                | 11        | 0.18%   |
| HP Pavilion Notebook                | 10        | 0.16%   |
| HP Laptop 15-bs0xx                  | 10        | 0.16%   |
| Gigabyte X570 AORUS MASTER          | 10        | 0.16%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 10        | 0.16%   |
| Gigabyte B450 AORUS M               | 10        | 0.16%   |
| Gigabyte 970A-DS3P                  | 10        | 0.16%   |
| MSI MS-7B89                         | 9         | 0.15%   |
| MSI MS-7693                         | 9         | 0.15%   |
| HP Pavilion dv7                     | 9         | 0.15%   |
| HP Pavilion 15                      | 9         | 0.15%   |
| Dell XPS 15 9570                    | 9         | 0.15%   |
| Dell XPS 15 9560                    | 9         | 0.15%   |
| Dell OptiPlex 7010                  | 9         | 0.15%   |
| Dell Inspiron 3542                  | 9         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 419       | 6.87%   |
| Lenovo IdeaPad     | 241       | 3.95%   |
| Acer Aspire        | 196       | 3.21%   |
| Dell Inspiron      | 192       | 3.15%   |
| ASUS ROG           | 178       | 2.92%   |
| HP Pavilion        | 158       | 2.59%   |
| ASUS PRIME         | 147       | 2.41%   |
| Dell Latitude      | 134       | 2.2%    |
| Dell XPS           | 106       | 1.74%   |
| ASUS TUF           | 100       | 1.64%   |
| HP ProBook         | 94        | 1.54%   |
| HP Laptop          | 88        | 1.44%   |
| HP EliteBook       | 88        | 1.44%   |
| Dell OptiPlex      | 75        | 1.23%   |
| HP ENVY            | 68        | 1.11%   |
| ASUS VivoBook      | 68        | 1.11%   |
| ASUS All           | 67        | 1.1%    |
| Lenovo Legion      | 64        | 1.05%   |
| Dell Precision     | 56        | 0.92%   |
| Toshiba Satellite  | 54        | 0.88%   |
| Lenovo Yoga        | 49        | 0.8%    |
| Unknown            | 49        | 0.8%    |
| HP Compaq          | 48        | 0.79%   |
| Gigabyte X570      | 46        | 0.75%   |
| Gigabyte B450M     | 43        | 0.7%    |
| Dell Vostro        | 39        | 0.64%   |
| ASUS ZenBook       | 36        | 0.59%   |
| Acer Swift         | 33        | 0.54%   |
| Gigabyte B450      | 31        | 0.51%   |
| HP OMEN            | 28        | 0.46%   |
| Acer Nitro         | 27        | 0.44%   |
| Lenovo ThinkBook   | 25        | 0.41%   |
| Lenovo ThinkCentre | 24        | 0.39%   |
| ASRock B450M       | 24        | 0.39%   |
| MSI MS-7C37        | 23        | 0.38%   |
| MSI MS-7C02        | 23        | 0.38%   |
| ASUS ASUS          | 23        | 0.38%   |
| Fujitsu LIFEBOOK   | 22        | 0.36%   |
| Lenovo IdeaPadFlex | 21        | 0.34%   |
| HP Spectre         | 20        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 835       | 13.68%  |
| 2018    | 794       | 13.01%  |
| 2020    | 780       | 12.78%  |
| 2017    | 524       | 8.59%   |
| 2012    | 463       | 7.59%   |
| 2021    | 421       | 6.9%    |
| 2013    | 372       | 6.1%    |
| 2014    | 343       | 5.62%   |
| 2011    | 317       | 5.19%   |
| 2016    | 315       | 5.16%   |
| 2015    | 314       | 5.15%   |
| 2010    | 193       | 3.16%   |
| 2009    | 125       | 2.05%   |
| 2008    | 115       | 1.88%   |
| 2022    | 94        | 1.54%   |
| 2007    | 69        | 1.13%   |
| 2006    | 19        | 0.31%   |
| 2005    | 5         | 0.08%   |
| Unknown | 5         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3382      | 55.42%  |
| Desktop     | 2333      | 38.23%  |
| Convertible | 223       | 3.65%   |
| Mini pc     | 71        | 1.16%   |
| All in one  | 44        | 0.72%   |
| Tablet      | 41        | 0.67%   |
| Server      | 8         | 0.13%   |
| Phone       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6100      | 99.9%   |
| Enabled  | 6         | 0.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6061      | 99.31%  |
| Yes  | 42        | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1691      | 27.34%  |
| 4.01-8.0        | 1369      | 22.13%  |
| 8.01-16.0       | 1242      | 20.08%  |
| 32.01-64.0      | 737       | 11.91%  |
| 3.01-4.0        | 720       | 11.64%  |
| 64.01-256.0     | 155       | 2.51%   |
| 24.01-32.0      | 133       | 2.15%   |
| 1.01-2.0        | 104       | 1.68%   |
| 2.01-3.0        | 32        | 0.52%   |
| More than 256.0 | 2         | 0.03%   |
| 0.51-1.0        | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 1751      | 25.82%  |
| 1.01-2.0        | 1684      | 24.83%  |
| 4.01-8.0        | 1463      | 21.57%  |
| 3.01-4.0        | 1143      | 16.86%  |
| 8.01-16.0       | 432       | 6.37%   |
| 0.51-1.0        | 208       | 3.07%   |
| 16.01-24.0      | 54        | 0.8%    |
| 0.01-0.5        | 19        | 0.28%   |
| 24.01-32.0      | 14        | 0.21%   |
| 32.01-64.0      | 11        | 0.16%   |
| More than 256.0 | 1         | 0.01%   |
| 64.01-256.0     | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3195      | 50.79%  |
| 2      | 1783      | 28.35%  |
| 3      | 632       | 10.05%  |
| 4      | 331       | 5.26%   |
| 5      | 185       | 2.94%   |
| 6      | 69        | 1.1%    |
| 7      | 37        | 0.59%   |
| 0      | 29        | 0.46%   |
| 8      | 11        | 0.17%   |
| 9      | 9         | 0.14%   |
| 11     | 4         | 0.06%   |
| 12     | 2         | 0.03%   |
| 10     | 2         | 0.03%   |
| 20     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4411      | 71.57%  |
| Yes       | 1752      | 28.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5111      | 83.57%  |
| No        | 1005      | 16.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4812      | 78.4%   |
| No        | 1326      | 21.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4053      | 65.76%  |
| No        | 2110      | 34.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1027      | 16.73%  |
| Germany      | 703       | 11.45%  |
| Russia       | 552       | 8.99%   |
| Brazil       | 346       | 5.64%   |
| France       | 230       | 3.75%   |
| UK           | 215       | 3.5%    |
| Italy        | 201       | 3.27%   |
| Canada       | 198       | 3.22%   |
| Spain        | 183       | 2.98%   |
| Poland       | 183       | 2.98%   |
| Ukraine      | 144       | 2.35%   |
| Netherlands  | 134       | 2.18%   |
| India        | 115       | 1.87%   |
| Australia    | 90        | 1.47%   |
| Mexico       | 89        | 1.45%   |
| Austria      | 88        | 1.43%   |
| Sweden       | 86        | 1.4%    |
| China        | 64        | 1.04%   |
| Belgium      | 60        | 0.98%   |
| Switzerland  | 59        | 0.96%   |
| Turkey       | 58        | 0.94%   |
| Finland      | 57        | 0.93%   |
| Romania      | 54        | 0.88%   |
| Portugal     | 49        | 0.8%    |
| Czechia      | 48        | 0.78%   |
| Argentina    | 48        | 0.78%   |
| Indonesia    | 45        | 0.73%   |
| Greece       | 45        | 0.73%   |
| Bulgaria     | 44        | 0.72%   |
| Norway       | 43        | 0.7%    |
| Hungary      | 43        | 0.7%    |
| Belarus      | 41        | 0.67%   |
| Denmark      | 36        | 0.59%   |
| Colombia     | 28        | 0.46%   |
| Taiwan       | 27        | 0.44%   |
| Chile        | 27        | 0.44%   |
| Bangladesh   | 27        | 0.44%   |
| South Africa | 26        | 0.42%   |
| Ireland      | 24        | 0.39%   |
| Israel       | 23        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 126       | 1.95%   |
| St Petersburg     | 72        | 1.11%   |
| Vienna            | 55        | 0.85%   |
| Paris             | 46        | 0.71%   |
| Berlin            | 45        | 0.7%    |
| Kyiv              | 42        | 0.65%   |
| Warsaw            | 40        | 0.62%   |
| Sao Paulo         | 40        | 0.62%   |
| Amsterdam         | 35        | 0.54%   |
| Toronto           | 30        | 0.46%   |
| Milan             | 30        | 0.46%   |
| Madrid            | 30        | 0.46%   |
| Hamburg           | 27        | 0.42%   |
| Frankfurt am Main | 27        | 0.42%   |
| Stockholm         | 26        | 0.4%    |
| Rome              | 26        | 0.4%    |
| Helsinki          | 26        | 0.4%    |
| Munich            | 25        | 0.39%   |
| Athens            | 25        | 0.39%   |
| Minsk             | 24        | 0.37%   |
| Istanbul          | 23        | 0.36%   |
| Barcelona         | 23        | 0.36%   |
| Sofia             | 21        | 0.32%   |
| Novosibirsk       | 21        | 0.32%   |
| Melbourne         | 21        | 0.32%   |
| Krakow            | 21        | 0.32%   |
| Bengaluru         | 21        | 0.32%   |
| Cologne           | 20        | 0.31%   |
| Bucharest         | 20        | 0.31%   |
| Sydney            | 19        | 0.29%   |
| Mexico City       | 19        | 0.29%   |
| Yekaterinburg     | 18        | 0.28%   |
| Rio de Janeiro    | 18        | 0.28%   |
| London            | 18        | 0.28%   |
| Dhaka             | 18        | 0.28%   |
| Prague            | 17        | 0.26%   |
| Montreal          | 17        | 0.26%   |
| Copenhagen        | 17        | 0.26%   |
| Budapest          | 17        | 0.26%   |
| Atlanta           | 17        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1731      | 2633   | 17.2%   |
| WDC                         | 1458      | 2188   | 14.49%  |
| Seagate                     | 1386      | 2078   | 13.77%  |
| Toshiba                     | 655       | 792    | 6.51%   |
| Kingston                    | 594       | 771    | 5.9%    |
| SanDisk                     | 580       | 744    | 5.76%   |
| Crucial                     | 437       | 613    | 4.34%   |
| Unknown                     | 308       | 402    | 3.06%   |
| Intel                       | 282       | 373    | 2.8%    |
| SK hynix                    | 280       | 336    | 2.78%   |
| Hitachi                     | 220       | 293    | 2.19%   |
| HGST                        | 197       | 258    | 1.96%   |
| Micron Technology           | 150       | 186    | 1.49%   |
| A-DATA Technology           | 139       | 181    | 1.38%   |
| Phison                      | 128       | 175    | 1.27%   |
| China                       | 86        | 109    | 0.85%   |
| Apple                       | 72        | 86     | 0.72%   |
| KIOXIA                      | 70        | 80     | 0.7%    |
| Silicon Motion              | 68        | 86     | 0.68%   |
| Transcend                   | 54        | 60     | 0.54%   |
| PNY                         | 51        | 74     | 0.51%   |
| Micron/Crucial Technology   | 50        | 61     | 0.5%    |
| OCZ                         | 47        | 60     | 0.47%   |
| SPCC                        | 46        | 55     | 0.46%   |
| Patriot                     | 45        | 52     | 0.45%   |
| Intenso                     | 44        | 60     | 0.44%   |
| XPG                         | 43        | 54     | 0.43%   |
| GOODRAM                     | 43        | 65     | 0.43%   |
| JMicron Technology          | 40        | 48     | 0.4%    |
| Corsair                     | 35        | 46     | 0.35%   |
| Plextor                     | 34        | 45     | 0.34%   |
| LITEONIT                    | 32        | 39     | 0.32%   |
| LITEON                      | 31        | 34     | 0.31%   |
| Phison Electronics          | 26        | 28     | 0.26%   |
| Lexar                       | 23        | 25     | 0.23%   |
| Team                        | 21        | 27     | 0.21%   |
| Realtek Semiconductor       | 21        | 28     | 0.21%   |
| Apacer                      | 20        | 22     | 0.2%    |
| Kingston Technology Company | 19        | 20     | 0.19%   |
| Hewlett-Packard             | 19        | 26     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 125       | 1.11%   |
| Samsung SSD 860 EVO 500GB                           | 102       | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                      | 99        | 0.88%   |
| Samsung NVMe SSD Drive 512GB                        | 86        | 0.76%   |
| Samsung SSD 850 EVO 500GB                           | 83        | 0.74%   |
| Samsung NVMe SSD Drive 500GB                        | 83        | 0.74%   |
| Samsung NVMe SSD Drive 1TB                          | 82        | 0.73%   |
| Kingston SA400S37120G 120GB SSD                     | 76        | 0.67%   |
| Samsung SSD 850 EVO 250GB                           | 75        | 0.67%   |
| Crucial CT500MX500SSD1 500GB                        | 74        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB                      | 73        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB                      | 70        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 65        | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 62        | 0.55%   |
| Samsung SSD 860 EVO 1TB                             | 61        | 0.54%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 61        | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 60        | 0.53%   |
| Toshiba MQ01ABD100 1TB                              | 58        | 0.51%   |
| HGST HTS721010A9E630 1TB                            | 58        | 0.51%   |
| Samsung SSD 860 EVO 250GB                           | 57        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                         | 57        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                       | 55        | 0.49%   |
| Toshiba MQ04ABF100 1TB                              | 53        | 0.47%   |
| Toshiba DT01ACA100 1TB                              | 53        | 0.47%   |
| Crucial CT240BX500SSD1 240GB                        | 53        | 0.47%   |
| SanDisk NVMe SSD Drive 512GB                        | 52        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 51        | 0.45%   |
| Seagate Expansion 240GB                             | 51        | 0.45%   |
| Unknown SD/MMC/MS PRO 2GB                           | 46        | 0.41%   |
| Toshiba MQ01ABF050 500GB                            | 45        | 0.4%    |
| SanDisk NVMe SSD Drive 500GB                        | 45        | 0.4%    |
| Intel NVMe SSD Drive 512GB                          | 44        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 42        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 40        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB                      | 40        | 0.35%   |
| Unknown MMC Card  64GB                              | 39        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                      | 39        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 39        | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB                      | 38        | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 36        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1356      | 2021   | 36.45%  |
| WDC                 | 1154      | 1717   | 31.02%  |
| Toshiba             | 479       | 580    | 12.88%  |
| Hitachi             | 220       | 293    | 5.91%   |
| HGST                | 196       | 257    | 5.27%   |
| Samsung Electronics | 147       | 219    | 3.95%   |
| Unknown             | 52        | 63     | 1.4%    |
| Apple               | 17        | 22     | 0.46%   |
| Fujitsu             | 16        | 16     | 0.43%   |
| Maxtor              | 13        | 15     | 0.35%   |
| ASMT                | 13        | 23     | 0.35%   |
| SABRENT             | 12        | 12     | 0.32%   |
| Intenso             | 8         | 11     | 0.22%   |
| USB3.0              | 7         | 7      | 0.19%   |
| ASMedia             | 5         | 5      | 0.13%   |
| JMicron Technology  | 4         | 7      | 0.11%   |
| HGST HTS            | 3         | 3      | 0.08%   |
| Hewlett-Packard     | 3         | 3      | 0.08%   |
| USB                 | 2         | 2      | 0.05%   |
| Maxone              | 2         | 2      | 0.05%   |
| Apricorn            | 2         | 2      | 0.05%   |
| QNAP                | 1         | 1      | 0.03%   |
| Pioneer             | 1         | 3      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 850       | 1196   | 24.68%  |
| Kingston            | 481       | 618    | 13.97%  |
| Crucial             | 396       | 563    | 11.5%   |
| SanDisk             | 288       | 374    | 8.36%   |
| WDC                 | 213       | 283    | 6.18%   |
| A-DATA Technology   | 110       | 142    | 3.19%   |
| Intel               | 92        | 116    | 2.67%   |
| China               | 85        | 108    | 2.47%   |
| Micron Technology   | 67        | 82     | 1.95%   |
| Toshiba             | 52        | 63     | 1.51%   |
| SK hynix            | 51        | 60     | 1.48%   |
| Transcend           | 47        | 52     | 1.36%   |
| OCZ                 | 47        | 60     | 1.36%   |
| PNY                 | 45        | 68     | 1.31%   |
| Patriot             | 42        | 49     | 1.22%   |
| GOODRAM             | 41        | 63     | 1.19%   |
| Apple               | 40        | 45     | 1.16%   |
| SPCC                | 35        | 43     | 1.02%   |
| LITEONIT            | 32        | 39     | 0.93%   |
| Plextor             | 31        | 42     | 0.9%    |
| Intenso             | 29        | 40     | 0.84%   |
| LITEON              | 25        | 28     | 0.73%   |
| Corsair             | 24        | 33     | 0.7%    |
| Lexar               | 22        | 24     | 0.64%   |
| Apacer              | 19        | 21     | 0.55%   |
| Team                | 17        | 23     | 0.49%   |
| Seagate             | 16        | 23     | 0.46%   |
| JMicron Technology  | 16        | 17     | 0.46%   |
| KingSpec            | 14        | 15     | 0.41%   |
| Netac               | 12        | 18     | 0.35%   |
| KingDian            | 11        | 11     | 0.32%   |
| Gigabyte Technology | 11        | 15     | 0.32%   |
| Leven               | 10        | 11     | 0.29%   |
| TO Exter            | 9         | 11     | 0.26%   |
| Hewlett-Packard     | 8         | 11     | 0.23%   |
| Mushkin             | 7         | 8      | 0.2%    |
| Unknown             | 7         | 8      | 0.2%    |
| NGFF                | 6         | 6      | 0.17%   |
| Hoodisk             | 6         | 6      | 0.17%   |
| Unknown             | 5         | 6      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3008      | 5291   | 34.15%  |
| SSD     | 2910      | 4564   | 33.03%  |
| NVMe    | 2508      | 3553   | 28.47%  |
| MMC     | 237       | 306    | 2.69%   |
| Unknown | 146       | 185    | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4473      | 9443   | 58.59%  |
| NVMe | 2503      | 3538   | 32.78%  |
| SAS  | 422       | 612    | 5.53%   |
| MMC  | 237       | 306    | 3.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3289      | 5375   | 51.99%  |
| 0.51-1.0   | 2018      | 2923   | 31.9%   |
| 1.01-2.0   | 570       | 824    | 9.01%   |
| 3.01-4.0   | 171       | 270    | 2.7%    |
| 4.01-10.0  | 143       | 251    | 2.26%   |
| 2.01-3.0   | 119       | 186    | 1.88%   |
| 10.01-20.0 | 15        | 25     | 0.24%   |
| 20.01-50.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1499      | 23.44%  |
| 251-500        | 1424      | 22.26%  |
| 501-1000       | 1011      | 15.81%  |
| 1001-2000      | 719       | 11.24%  |
| More than 3000 | 421       | 6.58%   |
| Unknown        | 364       | 5.69%   |
| 51-100         | 338       | 5.28%   |
| 2001-3000      | 275       | 4.3%    |
| 1-20           | 187       | 2.92%   |
| 21-50          | 158       | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1348      | 20.23%  |
| 101-250        | 1092      | 16.38%  |
| 21-50          | 1081      | 16.22%  |
| 51-100         | 900       | 13.5%   |
| 251-500        | 717       | 10.76%  |
| 501-1000       | 550       | 8.25%   |
| Unknown        | 364       | 5.46%   |
| 1001-2000      | 323       | 4.85%   |
| More than 3000 | 167       | 2.51%   |
| 2001-3000      | 119       | 1.79%   |
| 0              | 4         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 11        | 12     | 2.09%   |
| HGST HTS545050A7E680 500GB                          | 9         | 9      | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 8      | 1.52%   |
| HGST HTS721010A9E630 1TB                            | 8         | 8      | 1.52%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 9      | 1.33%   |
| HGST HTS545050A7E380 500GB                          | 7         | 7      | 1.33%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 1.14%   |
| Toshiba MQ01ABD050 500GB                            | 6         | 6      | 1.14%   |
| Seagate ST500LT012-9WS142 500GB                     | 6         | 23     | 1.14%   |
| WDC WD5000AAKX-001CA0 500GB                         | 5         | 7      | 0.95%   |
| WDC WD10EARS-00Y5B1 1TB                             | 5         | 5      | 0.95%   |
| Samsung Electronics HD103SJ 1TB                     | 5         | 5      | 0.95%   |
| Hitachi HDS721010CLA332 1TB                         | 5         | 5      | 0.95%   |
| Crucial CT525MX300SSD1 528GB                        | 5         | 5      | 0.95%   |
| Seagate ST9500325AS 500GB                           | 4         | 5      | 0.76%   |
| Seagate ST9320325AS 320GB                           | 4         | 5      | 0.76%   |
| Seagate ST3500413AS 500GB                           | 4         | 5      | 0.76%   |
| Seagate ST1000DX001-1CM162 1TB                      | 4         | 6      | 0.76%   |
| Samsung Electronics SSD 960 EVO 250GB               | 4         | 5      | 0.76%   |
| Samsung Electronics HD103UJ 1TB                     | 4         | 6      | 0.76%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 4      | 0.76%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 0.76%   |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 0.76%   |
| WDC WD15EARS-00MVWB0 1TB                            | 3         | 3      | 0.57%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 0.57%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 3         | 3      | 0.57%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3         | 3      | 0.57%   |
| WDC WD10EARX-00N0YB0 1TB                            | 3         | 4      | 0.57%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 3         | 3      | 0.57%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 3      | 0.57%   |
| Seagate ST9750420AS 752GB                           | 3         | 3      | 0.57%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 0.57%   |
| Seagate ST4000DM000-1F2168 4TB                      | 3         | 8      | 0.57%   |
| Seagate ST2000DM001-1CH164 2TB                      | 3         | 3      | 0.57%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 3         | 3      | 0.57%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 3         | 3      | 0.57%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 0.57%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 3      | 0.57%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 3      | 0.57%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 137       | 201    | 26.71%  |
| WDC                 | 122       | 140    | 23.78%  |
| Hitachi             | 38        | 41     | 7.41%   |
| HGST                | 38        | 38     | 7.41%   |
| Samsung Electronics | 36        | 43     | 7.02%   |
| Toshiba             | 34        | 40     | 6.63%   |
| Crucial             | 16        | 19     | 3.12%   |
| Intel               | 15        | 17     | 2.92%   |
| SanDisk             | 14        | 17     | 2.73%   |
| Kingston            | 14        | 14     | 2.73%   |
| SK hynix            | 7         | 12     | 1.36%   |
| A-DATA Technology   | 7         | 8      | 1.36%   |
| Micron Technology   | 5         | 7      | 0.97%   |
| LITEON              | 3         | 3      | 0.58%   |
| Transcend           | 2         | 2      | 0.39%   |
| OCZ                 | 2         | 2      | 0.39%   |
| KingSpec            | 2         | 2      | 0.39%   |
| Corsair             | 2         | 6      | 0.39%   |
| ASMT                | 2         | 6      | 0.39%   |
| Apacer              | 2         | 2      | 0.39%   |
| TwinMOS             | 1         | 1      | 0.19%   |
| SPCC                | 1         | 1      | 0.19%   |
| Phison              | 1         | 2      | 0.19%   |
| Patriot             | 1         | 1      | 0.19%   |
| Maxtor              | 1         | 1      | 0.19%   |
| MaxDigital          | 1         | 1      | 0.19%   |
| LITEONIT            | 1         | 1      | 0.19%   |
| Intenso             | 1         | 4      | 0.19%   |
| IM3D                | 1         | 1      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| Fujitsu             | 1         | 1      | 0.19%   |
| Faspeed             | 1         | 1      | 0.19%   |
| Drevo               | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 136       | 198    | 35.14%  |
| WDC                 | 120       | 138    | 31.01%  |
| Hitachi             | 38        | 41     | 9.82%   |
| HGST                | 38        | 38     | 9.82%   |
| Toshiba             | 30        | 36     | 7.75%   |
| Samsung Electronics | 20        | 25     | 5.17%   |
| ASMT                | 2         | 6      | 0.52%   |
| Maxtor              | 1         | 1      | 0.26%   |
| MaxDigital          | 1         | 1      | 0.26%   |
| Fujitsu             | 1         | 1      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 367       | 485    | 74.9%   |
| SSD  | 103       | 131    | 21.02%  |
| NVMe | 20        | 23     | 4.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 249GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3881      | 8446   | 57.23%  |
| Works    | 2414      | 4798   | 35.6%   |
| Malfunc  | 471       | 639    | 6.95%   |
| Failed   | 15        | 16     | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3655      | 44.35%  |
| AMD                              | 1635      | 19.84%  |
| Samsung Electronics              | 938       | 11.38%  |
| SanDisk                          | 425       | 5.16%   |
| SK hynix                         | 226       | 2.74%   |
| Phison Electronics               | 174       | 2.11%   |
| ASMedia Technology               | 153       | 1.86%   |
| Kingston Technology Company      | 135       | 1.64%   |
| Toshiba America Info Systems     | 118       | 1.43%   |
| Micron/Crucial Technology        | 92        | 1.12%   |
| Silicon Motion                   | 86        | 1.04%   |
| Micron Technology                | 82        | 1%      |
| KIOXIA                           | 82        | 1%      |
| Marvell Technology Group         | 73        | 0.89%   |
| ADATA Technology                 | 70        | 0.85%   |
| JMicron Technology               | 58        | 0.7%    |
| Nvidia                           | 57        | 0.69%   |
| Realtek Semiconductor            | 35        | 0.42%   |
| Union Memory (Shenzhen)          | 28        | 0.34%   |
| Solid State Storage Technology   | 16        | 0.19%   |
| Lite-On Technology               | 16        | 0.19%   |
| Apple                            | 15        | 0.18%   |
| Shenzhen Longsys Electronics     | 9         | 0.11%   |
| Seagate Technology               | 9         | 0.11%   |
| LSI Logic / Symbios Logic        | 8         | 0.1%    |
| VIA Technologies                 | 7         | 0.08%   |
| Silicon Image                    | 6         | 0.07%   |
| Lenovo                           | 6         | 0.07%   |
| Broadcom / LSI                   | 4         | 0.05%   |
| Adaptec                          | 4         | 0.05%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.02%   |
| Transcend                        | 2         | 0.02%   |
| Silicon Integrated Systems [SiS] | 2         | 0.02%   |
| Promise Technology               | 1         | 0.01%   |
| PMC-Sierra                       | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1233      | 13.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 533       | 5.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 353       | 3.78%   |
| AMD 400 Series Chipset SATA Controller                                         | 326       | 3.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 261       | 2.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 248       | 2.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 226       | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 156       | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 154       | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 152       | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 150       | 1.61%   |
| Samsung NVMe SSD Controller 980                                                | 146       | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 137       | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 133       | 1.42%   |
| AMD 500 Series Chipset SATA Controller                                         | 133       | 1.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 130       | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 127       | 1.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 122       | 1.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 122       | 1.31%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 117       | 1.25%   |
| Intel SSD 660P Series                                                          | 106       | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 106       | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 101       | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 100       | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 88        | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 86        | 0.92%   |
| Phison E12 NVMe Controller                                                     | 86        | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 84        | 0.9%    |
| Micron Non-Volatile memory controller                                          | 82        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 82        | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 80        | 0.86%   |
| Intel SATA Controller [RAID mode]                                              | 80        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 79        | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 69        | 0.74%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 68        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 66        | 0.71%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 64        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 63        | 0.67%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 60        | 0.64%   |
| SanDisk Non-Volatile memory controller                                         | 59        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4673      | 57.72%  |
| NVMe | 2513      | 31.04%  |
| IDE  | 455       | 5.62%   |
| RAID | 435       | 5.37%   |
| SAS  | 17        | 0.21%   |
| SCSI | 3         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4141      | 67.84%  |
| AMD    | 1962      | 32.14%  |
| ARM    | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 122       | 1.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 92        | 1.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 77        | 1.26%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 74        | 1.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 73        | 1.19%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 70        | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 69        | 1.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 69        | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 68        | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 67        | 1.1%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 61        | 1%      |
| AMD Ryzen 5 2600 Six-Core Processor           | 60        | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 58        | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 57        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 53        | 0.87%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 52        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 0.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 49        | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 46        | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 45        | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 44        | 0.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 43        | 0.7%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 43        | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 39        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 37        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 37        | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 33        | 0.54%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 33        | 0.54%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 32        | 0.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 30        | 0.49%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 30        | 0.49%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 30        | 0.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.47%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 29        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.46%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 28        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1401      | 22.92%  |
| Intel Core i7           | 1317      | 21.54%  |
| AMD Ryzen 5             | 651       | 10.65%  |
| AMD Ryzen 7             | 524       | 8.57%   |
| Intel Core i3           | 371       | 6.07%   |
| Other                   | 273       | 4.47%   |
| Intel Celeron           | 201       | 3.29%   |
| AMD Ryzen 9             | 137       | 2.24%   |
| Intel Core 2 Duo        | 136       | 2.22%   |
| Intel Xeon              | 118       | 1.93%   |
| Intel Pentium           | 114       | 1.86%   |
| AMD FX                  | 108       | 1.77%   |
| AMD Ryzen 3             | 95        | 1.55%   |
| Intel Atom              | 46        | 0.75%   |
| Intel Pentium Dual-Core | 41        | 0.67%   |
| Intel Core i9           | 40        | 0.65%   |
| AMD Ryzen 7 PRO         | 40        | 0.65%   |
| AMD A8                  | 39        | 0.64%   |
| AMD A10                 | 39        | 0.64%   |
| AMD A4                  | 34        | 0.56%   |
| AMD A6                  | 30        | 0.49%   |
| AMD Ryzen Threadripper  | 27        | 0.44%   |
| Intel Core 2 Quad       | 26        | 0.43%   |
| AMD Phenom II X4        | 26        | 0.43%   |
| Intel Core 2            | 21        | 0.34%   |
| AMD E1                  | 19        | 0.31%   |
| AMD E                   | 19        | 0.31%   |
| AMD Athlon              | 19        | 0.31%   |
| AMD Athlon II X2        | 18        | 0.29%   |
| Intel Pentium Silver    | 17        | 0.28%   |
| AMD Ryzen 5 PRO         | 13        | 0.21%   |
| AMD Athlon 64 X2        | 12        | 0.2%    |
| AMD Phenom II X6        | 11        | 0.18%   |
| Intel Pentium Gold      | 9         | 0.15%   |
| Intel Genuine           | 9         | 0.15%   |
| AMD Athlon II X4        | 9         | 0.15%   |
| AMD E2                  | 8         | 0.13%   |
| AMD Athlon X4           | 8         | 0.13%   |
| Intel Pentium Dual      | 7         | 0.11%   |
| AMD Turion 64 X2 Mobile | 7         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2288      | 37.45%  |
| 2       | 1935      | 31.67%  |
| 6       | 916       | 14.99%  |
| 8       | 672       | 11%     |
| 12      | 109       | 1.78%   |
| 16      | 60        | 0.98%   |
| 3       | 42        | 0.69%   |
| 1       | 42        | 0.69%   |
| 10      | 21        | 0.34%   |
| 14      | 11        | 0.18%   |
| 32      | 5         | 0.08%   |
| 24      | 5         | 0.08%   |
| Unknown | 3         | 0.05%   |
| 20      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 6083      | 99.67%  |
| 2      | 19        | 0.31%   |
| 4      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4605      | 75.34%  |
| 1       | 1504      | 24.61%  |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6007      | 98.31%  |
| Unknown        | 102       | 1.67%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3023      | 47.85%  |
| 0x306a9    | 206       | 3.26%   |
| 0x906ea    | 175       | 2.77%   |
| 0x306c3    | 161       | 2.55%   |
| 0x206a7    | 138       | 2.18%   |
| 0x08701021 | 129       | 2.04%   |
| 0x806ea    | 127       | 2.01%   |
| 0x806ec    | 122       | 1.93%   |
| 0x0800820d | 99        | 1.57%   |
| 0x806c1    | 98        | 1.55%   |
| 0x806e9    | 91        | 1.44%   |
| 0x906e9    | 85        | 1.35%   |
| 0x506e3    | 81        | 1.28%   |
| 0x406e3    | 79        | 1.25%   |
| 0x08701013 | 77        | 1.22%   |
| 0x40651    | 76        | 1.2%    |
| 0x08108102 | 68        | 1.08%   |
| 0x08600106 | 66        | 1.04%   |
| 0x1067a    | 65        | 1.03%   |
| 0x0a50000c | 64        | 1.01%   |
| 0x08108109 | 60        | 0.95%   |
| 0x306d4    | 59        | 0.93%   |
| 0x706e5    | 48        | 0.76%   |
| 0x06000852 | 47        | 0.74%   |
| 0x08600103 | 46        | 0.73%   |
| 0xa0652    | 44        | 0.7%    |
| 0x806eb    | 44        | 0.7%    |
| 0x08600104 | 44        | 0.7%    |
| 0x08608103 | 35        | 0.55%   |
| 0x20655    | 32        | 0.51%   |
| 0x08001138 | 30        | 0.47%   |
| 0x0810100b | 26        | 0.41%   |
| 0x010000c8 | 26        | 0.41%   |
| 0x406c4    | 23        | 0.36%   |
| 0x08600102 | 23        | 0.36%   |
| 0x306f2    | 22        | 0.35%   |
| 0x0a201016 | 22        | 0.35%   |
| 0x0a201009 | 22        | 0.35%   |
| 0x06001119 | 22        | 0.35%   |
| 0x906ed    | 21        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1213      | 19.84%  |
| Zen 2            | 577       | 9.44%   |
| Haswell          | 542       | 8.87%   |
| IvyBridge        | 404       | 6.61%   |
| Zen+             | 401       | 6.56%   |
| SandyBridge      | 351       | 5.74%   |
| Skylake          | 322       | 5.27%   |
| Zen 3            | 241       | 3.94%   |
| Zen              | 198       | 3.24%   |
| Penryn           | 182       | 2.98%   |
| TigerLake        | 163       | 2.67%   |
| Unknown          | 159       | 2.6%    |
| Broadwell        | 155       | 2.54%   |
| CometLake        | 142       | 2.32%   |
| Piledriver       | 140       | 2.29%   |
| Westmere         | 120       | 1.96%   |
| Silvermont       | 112       | 1.83%   |
| IceLake          | 98        | 1.6%    |
| K10              | 86        | 1.41%   |
| Core             | 75        | 1.23%   |
| Goldmont plus    | 73        | 1.19%   |
| Excavator        | 62        | 1.01%   |
| Goldmont         | 44        | 0.72%   |
| Nehalem          | 42        | 0.69%   |
| Bobcat           | 32        | 0.52%   |
| Steamroller      | 29        | 0.47%   |
| K8 Hammer        | 23        | 0.38%   |
| Jaguar           | 23        | 0.38%   |
| Alderlake Hybrid | 23        | 0.38%   |
| Puma             | 22        | 0.36%   |
| Bulldozer        | 18        | 0.29%   |
| K10 Llano        | 14        | 0.23%   |
| Bonnell          | 13        | 0.21%   |
| NetBurst         | 6         | 0.1%    |
| K8 & K10 hybrid  | 5         | 0.08%   |
| Tremont          | 3         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3158      | 42.2%   |
| Nvidia                     | 2426      | 32.42%  |
| AMD                        | 1890      | 25.26%  |
| ASPEED Technology          | 5         | 0.07%   |
| ATI Technologies           | 3         | 0.04%   |
| Matrox Electronics Systems | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 246       | 3.21%   |
| AMD Renoir                                                                               | 243       | 3.18%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 228       | 2.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 210       | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 206       | 2.69%   |
| Intel UHD Graphics 620                                                                   | 203       | 2.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 199       | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 166       | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 164       | 2.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 143       | 1.87%   |
| Intel HD Graphics 620                                                                    | 143       | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 122       | 1.59%   |
| Intel HD Graphics 5500                                                                   | 122       | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 121       | 1.58%   |
| Intel HD Graphics 630                                                                    | 115       | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 109       | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 94        | 1.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 91        | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 87        | 1.14%   |
| Intel HD Graphics 530                                                                    | 85        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 84        | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 80        | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 71        | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 69        | 0.9%    |
| AMD Lucienne                                                                             | 68        | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 67        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 65        | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 62        | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 62        | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 59        | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 58        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 57        | 0.74%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 52        | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 50        | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 49        | 0.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 46        | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 45        | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 44        | 0.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 43        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1989      | 32.35%  |
| 1 x AMD            | 1488      | 24.2%   |
| 1 x Nvidia         | 1252      | 20.36%  |
| Intel + Nvidia     | 970       | 15.78%  |
| AMD + Nvidia       | 174       | 2.83%   |
| Intel + AMD        | 133       | 2.16%   |
| 2 x AMD            | 103       | 1.68%   |
| 2 x Nvidia         | 28        | 0.46%   |
| 1 x ASPEED         | 4         | 0.07%   |
| Other              | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.02%   |
| 1 x Matrox         | 1         | 0.02%   |
| Intel + 2 x AMD    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4470      | 72.44%  |
| Proprietary | 1689      | 27.37%  |
| Unknown     | 12        | 0.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3855      | 61.89%  |
| 1.01-2.0   | 543       | 8.72%   |
| 0.01-0.5   | 407       | 6.53%   |
| 7.01-8.0   | 401       | 6.44%   |
| 3.01-4.0   | 368       | 5.91%   |
| 0.51-1.0   | 261       | 4.19%   |
| 5.01-6.0   | 229       | 3.68%   |
| 8.01-16.0  | 95        | 1.53%   |
| 2.01-3.0   | 57        | 0.92%   |
| 16.01-24.0 | 11        | 0.18%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 790       | 10.92%  |
| AU Optronics            | 762       | 10.53%  |
| LG Display              | 654       | 9.04%   |
| BOE                     | 645       | 8.91%   |
| Chimei Innolux          | 622       | 8.6%    |
| Goldstar                | 432       | 5.97%   |
| Dell                    | 391       | 5.4%    |
| Acer                    | 273       | 3.77%   |
| AOC                     | 218       | 3.01%   |
| BenQ                    | 214       | 2.96%   |
| Ancor Communications    | 211       | 2.92%   |
| Hewlett-Packard         | 186       | 2.57%   |
| Philips                 | 160       | 2.21%   |
| Sharp                   | 150       | 2.07%   |
| Lenovo                  | 116       | 1.6%    |
| Apple                   | 108       | 1.49%   |
| LG Electronics          | 102       | 1.41%   |
| PANDA                   | 92        | 1.27%   |
| ViewSonic               | 87        | 1.2%    |
| Chi Mei Optoelectronics | 78        | 1.08%   |
| ASUSTek Computer        | 75        | 1.04%   |
| Iiyama                  | 55        | 0.76%   |
| Unknown                 | 45        | 0.62%   |
| InfoVision              | 40        | 0.55%   |
| Sony                    | 39        | 0.54%   |
| Panasonic               | 25        | 0.35%   |
| Unknown                 | 25        | 0.35%   |
| Vizio                   | 24        | 0.33%   |
| CSO                     | 24        | 0.33%   |
| MSI                     | 21        | 0.29%   |
| Eizo                    | 21        | 0.29%   |
| Fujitsu Siemens         | 20        | 0.28%   |
| NEC Computers           | 19        | 0.26%   |
| Sceptre Tech            | 18        | 0.25%   |
| LGD                     | 17        | 0.23%   |
| AUS                     | 17        | 0.23%   |
| Toshiba                 | 16        | 0.22%   |
| TMX                     | 16        | 0.22%   |
| LG Philips              | 14        | 0.19%   |
| Medion                  | 13        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 43        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 42        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 35        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 31        | 0.41%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 28        | 0.37%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 28        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 25        | 0.33%   |
| Unknown                                                                  | 25        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 21        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 20        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 19        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 18        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 17        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 17        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 17        | 0.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 15        | 0.2%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 14        | 0.19%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.19%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 14        | 0.19%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 13        | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 12        | 0.16%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.16%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.16%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.16%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch             | 11        | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 11        | 0.15%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 11        | 0.15%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 11        | 0.15%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 11        | 0.15%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 11        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 11        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3302      | 48.06%  |
| 1366x768 (WXGA)    | 1018      | 14.82%  |
| 3840x2160 (4K)     | 462       | 6.72%   |
| 2560x1440 (QHD)    | 377       | 5.49%   |
| 1600x900 (HD+)     | 194       | 2.82%   |
| Unknown            | 172       | 2.5%    |
| 1680x1050 (WSXGA+) | 151       | 2.2%    |
| 1920x1200 (WUXGA)  | 149       | 2.17%   |
| 1280x1024 (SXGA)   | 132       | 1.92%   |
| 1440x900 (WXGA+)   | 123       | 1.79%   |
| 2560x1080          | 96        | 1.4%    |
| 3440x1440          | 89        | 1.3%    |
| 1280x800 (WXGA)    | 81        | 1.18%   |
| 3840x1080          | 80        | 1.16%   |
| 2560x1600          | 49        | 0.71%   |
| 1360x768           | 41        | 0.6%    |
| 2880x1800          | 33        | 0.48%   |
| 2160x1440          | 24        | 0.35%   |
| 3840x2400          | 21        | 0.31%   |
| 1920x540           | 17        | 0.25%   |
| 3200x1800 (QHD+)   | 12        | 0.17%   |
| 4480x1440          | 11        | 0.16%   |
| 3840x1600          | 11        | 0.16%   |
| 1280x720 (HD)      | 10        | 0.15%   |
| 1024x768 (XGA)     | 10        | 0.15%   |
| 5120x1440          | 9         | 0.13%   |
| 3456x2160          | 9         | 0.13%   |
| 3200x2000          | 9         | 0.13%   |
| 5760x1080          | 8         | 0.12%   |
| 2736x1824          | 8         | 0.12%   |
| 5760x2160          | 7         | 0.1%    |
| 3286x1080          | 7         | 0.1%    |
| 2256x1504          | 7         | 0.1%    |
| 1920x1280          | 7         | 0.1%    |
| 1600x1200          | 7         | 0.1%    |
| 3600x1080          | 6         | 0.09%   |
| 3000x2000          | 6         | 0.09%   |
| 3360x1080          | 5         | 0.07%   |
| 3200x1080          | 5         | 0.07%   |
| 7680x2160          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1811      | 25.47%  |
| 13      | 684       | 9.62%   |
| 14      | 557       | 7.84%   |
| 24      | 546       | 7.68%   |
| 27      | 545       | 7.67%   |
| Unknown | 536       | 7.54%   |
| 23      | 453       | 6.37%   |
| 21      | 368       | 5.18%   |
| 17      | 295       | 4.15%   |
| 31      | 162       | 2.28%   |
| 19      | 148       | 2.08%   |
| 34      | 145       | 2.04%   |
| 12      | 103       | 1.45%   |
| 22      | 99        | 1.39%   |
| 18      | 90        | 1.27%   |
| 20      | 76        | 1.07%   |
| 11      | 61        | 0.86%   |
| 84      | 48        | 0.68%   |
| 16      | 44        | 0.62%   |
| 32      | 33        | 0.46%   |
| 72      | 28        | 0.39%   |
| 54      | 28        | 0.39%   |
| 40      | 27        | 0.38%   |
| 25      | 25        | 0.35%   |
| 48      | 18        | 0.25%   |
| 28      | 16        | 0.23%   |
| 26      | 16        | 0.23%   |
| 49      | 14        | 0.2%    |
| 37      | 14        | 0.2%    |
| 65      | 11        | 0.15%   |
| 33      | 11        | 0.15%   |
| 43      | 9         | 0.13%   |
| 46      | 7         | 0.1%    |
| 42      | 7         | 0.1%    |
| 35      | 7         | 0.1%    |
| 29      | 7         | 0.1%    |
| 52      | 6         | 0.08%   |
| 39      | 6         | 0.08%   |
| 10      | 6         | 0.08%   |
| 74      | 5         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2751      | 39.61%  |
| 501-600     | 1392      | 20.04%  |
| 401-500     | 690       | 9.94%   |
| Unknown     | 536       | 7.72%   |
| 201-300     | 507       | 7.3%    |
| 351-400     | 374       | 5.39%   |
| 601-700     | 239       | 3.44%   |
| 701-800     | 193       | 2.78%   |
| 1001-1500   | 98        | 1.41%   |
| 1501-2000   | 86        | 1.24%   |
| 801-900     | 59        | 0.85%   |
| 901-1000    | 16        | 0.23%   |
| 101-200     | 3         | 0.04%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4756      | 75.19%  |
| 16/10   | 618       | 9.77%   |
| Unknown | 491       | 7.76%   |
| 21/9    | 166       | 2.62%   |
| 5/4     | 123       | 1.94%   |
| 3/2     | 86        | 1.36%   |
| 4/3     | 39        | 0.62%   |
| 32/9    | 27        | 0.43%   |
| 6/5     | 6         | 0.09%   |
| 0.62    | 3         | 0.05%   |
| 3.40    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.20    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.80    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1816      | 25.8%   |
| 201-250        | 1183      | 16.8%   |
| 81-90          | 959       | 13.62%  |
| 301-350        | 554       | 7.87%   |
| Unknown        | 536       | 7.61%   |
| 351-500        | 374       | 5.31%   |
| 151-200        | 308       | 4.38%   |
| 71-80          | 285       | 4.05%   |
| 121-130        | 213       | 3.03%   |
| 251-300        | 192       | 2.73%   |
| More than 1000 | 154       | 2.19%   |
| 141-150        | 119       | 1.69%   |
| 501-1000       | 101       | 1.43%   |
| 61-70          | 89        | 1.26%   |
| 51-60          | 64        | 0.91%   |
| 131-140        | 36        | 0.51%   |
| 111-120        | 30        | 0.43%   |
| 91-100         | 18        | 0.26%   |
| 41-50          | 5         | 0.07%   |
| 1-40           | 4         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2008      | 29.42%  |
| 51-100        | 2005      | 29.38%  |
| 101-120       | 1528      | 22.39%  |
| Unknown       | 536       | 7.85%   |
| 161-240       | 438       | 6.42%   |
| More than 240 | 182       | 2.67%   |
| 1-50          | 128       | 1.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4821      | 77.43%  |
| 2     | 1196      | 19.21%  |
| 3     | 144       | 2.31%   |
| 0     | 54        | 0.87%   |
| 4     | 11        | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3445      | 37.61%  |
| Intel                             | 3149      | 34.38%  |
| Qualcomm Atheros                  | 941       | 10.27%  |
| Broadcom                          | 383       | 4.18%   |
| Ralink Technology                 | 119       | 1.3%    |
| TP-Link                           | 116       | 1.27%   |
| MediaTek                          | 100       | 1.09%   |
| Broadcom Limited                  | 89        | 0.97%   |
| Ralink                            | 69        | 0.75%   |
| Marvell Technology Group          | 55        | 0.6%    |
| Microsoft                         | 50        | 0.55%   |
| Nvidia                            | 43        | 0.47%   |
| Xiaomi                            | 41        | 0.45%   |
| Samsung Electronics               | 34        | 0.37%   |
| ASIX Electronics                  | 34        | 0.37%   |
| Qualcomm Atheros Communications   | 29        | 0.32%   |
| Aquantia                          | 29        | 0.32%   |
| Sierra Wireless                   | 28        | 0.31%   |
| ASUSTek Computer                  | 27        | 0.29%   |
| Huawei Technologies               | 26        | 0.28%   |
| Lenovo                            | 24        | 0.26%   |
| DisplayLink                       | 21        | 0.23%   |
| Dell                              | 21        | 0.23%   |
| D-Link                            | 21        | 0.23%   |
| NetGear                           | 20        | 0.22%   |
| Linksys                           | 20        | 0.22%   |
| Qualcomm                          | 17        | 0.19%   |
| JMicron Technology                | 15        | 0.16%   |
| Hewlett-Packard                   | 14        | 0.15%   |
| Edimax Technology                 | 13        | 0.14%   |
| Ericsson Business Mobile Networks | 11        | 0.12%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.1%    |
| D-Link System                     | 9         | 0.1%    |
| Microchip Technology              | 8         | 0.09%   |
| Google                            | 8         | 0.09%   |
| Motorola PCS                      | 7         | 0.08%   |
| Fibocom                           | 7         | 0.08%   |
| Apple                             | 7         | 0.08%   |
| ZyXEL Communications              | 6         | 0.07%   |
| Mellanox Technologies             | 6         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2440      | 22.66%  |
| Intel Wi-Fi 6 AX200                                               | 470       | 4.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 335       | 3.11%   |
| Intel I211 Gigabit Network Connection                             | 268       | 2.49%   |
| Intel Wireless 8265 / 8275                                        | 217       | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 189       | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 174       | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 172       | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 160       | 1.49%   |
| Intel Wireless 7265                                               | 158       | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 146       | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 145       | 1.35%   |
| Intel Wireless 7260                                               | 135       | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 130       | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 122       | 1.13%   |
| Intel Wi-Fi 6 AX201                                               | 122       | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 120       | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 117       | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 110       | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 106       | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 103       | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 98        | 0.91%   |
| Intel Wireless 8260                                               | 95        | 0.88%   |
| Intel Wireless 3165                                               | 93        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 93        | 0.86%   |
| Intel Wireless-AC 9260                                            | 88        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 87        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 79        | 0.73%   |
| Intel Ethernet Controller I225-V                                  | 71        | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 70        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 69        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 69        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 57        | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 55        | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 54        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 46        | 0.43%   |
| Intel Wireless 3160                                               | 45        | 0.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 44        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2466      | 48.31%  |
| Realtek Semiconductor                 | 878       | 17.2%   |
| Qualcomm Atheros                      | 737       | 14.44%  |
| Broadcom                              | 278       | 5.45%   |
| Ralink Technology                     | 119       | 2.33%   |
| TP-Link                               | 109       | 2.14%   |
| MediaTek                              | 90        | 1.76%   |
| Ralink                                | 69        | 1.35%   |
| Broadcom Limited                      | 66        | 1.29%   |
| Microsoft                             | 47        | 0.92%   |
| Qualcomm Atheros Communications       | 29        | 0.57%   |
| Sierra Wireless                       | 28        | 0.55%   |
| ASUSTek Computer                      | 25        | 0.49%   |
| D-Link                                | 21        | 0.41%   |
| NetGear                               | 20        | 0.39%   |
| Linksys                               | 19        | 0.37%   |
| Dell                                  | 15        | 0.29%   |
| Marvell Technology Group              | 14        | 0.27%   |
| Edimax Technology                     | 13        | 0.25%   |
| ZyXEL Communications                  | 6         | 0.12%   |
| Qualcomm                              | 6         | 0.12%   |
| Fibocom                               | 6         | 0.12%   |
| D-Link System                         | 6         | 0.12%   |
| Hewlett-Packard                       | 4         | 0.08%   |
| Ericsson Business Mobile Networks     | 4         | 0.08%   |
| Belkin Components                     | 4         | 0.08%   |
| Quectel Wireless Solutions            | 3         | 0.06%   |
| Mercucys                              | 3         | 0.06%   |
| IMC Networks                          | 3         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.06%   |
| ZyDAS                                 | 2         | 0.04%   |
| Tenda                                 | 2         | 0.04%   |
| AVM                                   | 2         | 0.04%   |
| Xiaomi                                | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 470       | 9.13%   |
| Intel Wireless 8265 / 8275                                     | 217       | 4.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 174       | 3.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 160       | 3.11%   |
| Intel Wireless 7265                                            | 158       | 3.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 146       | 2.84%   |
| Intel Wireless 7260                                            | 135       | 2.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 130       | 2.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 122       | 2.37%   |
| Intel Wi-Fi 6 AX201                                            | 122       | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 117       | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 110       | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 106       | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 103       | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 98        | 1.9%    |
| Intel Wireless 8260                                            | 95        | 1.85%   |
| Intel Wireless 3165                                            | 93        | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 93        | 1.81%   |
| Intel Wireless-AC 9260                                         | 88        | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 87        | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 79        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 70        | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 69        | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 55        | 1.07%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 54        | 1.05%   |
| Intel Wireless 3160                                            | 45        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 44        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 44        | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 41        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 41        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 40        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 40        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 40        | 0.78%   |
| Realtek 802.11ac NIC                                           | 39        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 38        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 38        | 0.74%   |
| Intel Centrino Wireless-N 2230                                 | 37        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 37        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 35        | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 31        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3100      | 57.21%  |
| Intel                                  | 1451      | 26.78%  |
| Qualcomm Atheros                       | 287       | 5.3%    |
| Broadcom                               | 156       | 2.88%   |
| Nvidia                                 | 43        | 0.79%   |
| Marvell Technology Group               | 41        | 0.76%   |
| Xiaomi                                 | 39        | 0.72%   |
| ASIX Electronics                       | 34        | 0.63%   |
| Samsung Electronics                    | 33        | 0.61%   |
| Aquantia                               | 29        | 0.54%   |
| Broadcom Limited                       | 26        | 0.48%   |
| Lenovo                                 | 24        | 0.44%   |
| DisplayLink                            | 21        | 0.39%   |
| Huawei Technologies                    | 17        | 0.31%   |
| JMicron Technology                     | 15        | 0.28%   |
| Qualcomm                               | 10        | 0.18%   |
| MediaTek                               | 9         | 0.17%   |
| Google                                 | 8         | 0.15%   |
| TP-Link                                | 7         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.11%   |
| Mellanox Technologies                  | 6         | 0.11%   |
| Apple                                  | 6         | 0.11%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.07%   |
| Motorola PCS                           | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.06%   |
| OPPO Electronics                       | 3         | 0.06%   |
| Microsoft                              | 3         | 0.06%   |
| Hewlett-Packard                        | 3         | 0.06%   |
| D-Link System                          | 3         | 0.06%   |
| Spreadtrum Communications              | 2         | 0.04%   |
| National Semiconductor                 | 2         | 0.04%   |
| ICS Advent                             | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| Foxconn / Hon Hai                      | 2         | 0.04%   |
| Attansic Technology                    | 2         | 0.04%   |
| ASUSTek Computer                       | 2         | 0.04%   |
| VIA Technologies                       | 1         | 0.02%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2440      | 44%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 335       | 6.04%   |
| Intel I211 Gigabit Network Connection                             | 268       | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 189       | 3.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 172       | 3.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 145       | 2.61%   |
| Intel Ethernet Connection (2) I219-V                              | 120       | 2.16%   |
| Intel Ethernet Controller I225-V                                  | 71        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 69        | 1.24%   |
| Intel Ethernet Connection (7) I219-V                              | 57        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 56        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 46        | 0.83%   |
| Intel Ethernet Connection (4) I219-V                              | 44        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 44        | 0.79%   |
| Intel Ethernet Connection (2) I218-V                              | 41        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 35        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 33        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 33        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 31        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 30        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 30        | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 26        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.47%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.43%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 23        | 0.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 21        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 19        | 0.34%   |
| Nvidia MCP61 Ethernet                                             | 19        | 0.34%   |
| Intel I210 Gigabit Network Connection                             | 19        | 0.34%   |
| Intel Ethernet Connection I219-V                                  | 19        | 0.34%   |
| Intel Ethernet Connection (6) I219-LM                             | 19        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5097      | 51.07%  |
| WiFi     | 4812      | 48.22%  |
| Modem    | 59        | 0.59%   |
| Unknown  | 12        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3777      | 59.2%   |
| Ethernet | 2603      | 40.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3225      | 52.64%  |
| 1     | 2680      | 43.74%  |
| 3     | 139       | 2.27%   |
| 0     | 65        | 1.06%   |
| 4     | 9         | 0.15%   |
| 5     | 7         | 0.11%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5232      | 84.43%  |
| Yes  | 965       | 15.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2092      | 50.89%  |
| Realtek Semiconductor           | 450       | 10.95%  |
| Qualcomm Atheros Communications | 315       | 7.66%   |
| Cambridge Silicon Radio         | 307       | 7.47%   |
| IMC Networks                    | 166       | 4.04%   |
| Broadcom                        | 146       | 3.55%   |
| Lite-On Technology              | 135       | 3.28%   |
| Apple                           | 109       | 2.65%   |
| ASUSTek Computer                | 97        | 2.36%   |
| Foxconn / Hon Hai               | 73        | 1.78%   |
| Realtek                         | 38        | 0.92%   |
| Ralink                          | 24        | 0.58%   |
| Dell                            | 23        | 0.56%   |
| Hewlett-Packard                 | 17        | 0.41%   |
| MediaTek                        | 15        | 0.36%   |
| Toshiba                         | 14        | 0.34%   |
| Marvell Semiconductor           | 11        | 0.27%   |
| Foxconn International           | 9         | 0.22%   |
| TP-Link                         | 8         | 0.19%   |
| Dynex                           | 7         | 0.17%   |
| Ralink Technology               | 6         | 0.15%   |
| Edimax Technology               | 6         | 0.15%   |
| Opticis                         | 5         | 0.12%   |
| HTC (High Tech Computer)        | 5         | 0.12%   |
| Belkin Components               | 5         | 0.12%   |
| Alps Electric                   | 5         | 0.12%   |
| Conwise Technology              | 4         | 0.1%    |
| Askey Computer                  | 4         | 0.1%    |
| SIN                             | 3         | 0.07%   |
| Integrated System Solution      | 3         | 0.07%   |
| Fujitsu                         | 2         | 0.05%   |
| USI                             | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 697       | 16.93%  |
| Intel AX200 Bluetooth                               | 442       | 10.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 325       | 7.9%    |
| Intel Bluetooth Device                              | 317       | 7.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 307       | 7.46%   |
| Realtek Bluetooth Radio                             | 286       | 6.95%   |
| Qualcomm Atheros  Bluetooth Device                  | 156       | 3.79%   |
| Realtek  Bluetooth 4.2 Adapter                      | 117       | 2.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 106       | 2.58%   |
| Lite-On Bluetooth Device                            | 89        | 2.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 83        | 2.02%   |
| IMC Networks Bluetooth Radio                        | 69        | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 59        | 1.43%   |
| Intel AX210 Bluetooth                               | 51        | 1.24%   |
| Apple Bluetooth USB Host Controller                 | 47        | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 43        | 1.04%   |
| Apple Bluetooth Host Controller                     | 42        | 1.02%   |
| IMC Networks Bluetooth Device                       | 40        | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 39        | 0.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 39        | 0.95%   |
| Realtek Bluetooth Radio                             | 38        | 0.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 37        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 31        | 0.75%   |
| IMC Networks Wireless_Device                        | 29        | 0.7%    |
| Ralink RT3290 Bluetooth                             | 24        | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 21        | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 18        | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 16        | 0.39%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 16        | 0.39%   |
| ASUS Bluetooth Radio                                | 14        | 0.34%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.32%   |
| MediaTek Wireless_Device                            | 13        | 0.32%   |
| ASUS Bluetooth Adapter                              | 13        | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 13        | 0.32%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.29%   |
| ASUS ASUS USB-BT500                                 | 12        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4033      | 44.2%   |
| AMD                                  | 2232      | 24.46%  |
| Nvidia                               | 1628      | 17.84%  |
| C-Media Electronics                  | 206       | 2.26%   |
| Logitech                             | 89        | 0.98%   |
| Creative Labs                        | 66        | 0.72%   |
| Kingston Technology                  | 57        | 0.62%   |
| JMTek                                | 50        | 0.55%   |
| Texas Instruments                    | 43        | 0.47%   |
| SteelSeries ApS                      | 38        | 0.42%   |
| Realtek Semiconductor                | 35        | 0.38%   |
| Focusrite-Novation                   | 34        | 0.37%   |
| Corsair                              | 34        | 0.37%   |
| Creative Technology                  | 32        | 0.35%   |
| Generalplus Technology               | 31        | 0.34%   |
| Razer USA                            | 29        | 0.32%   |
| Blue Microphones                     | 28        | 0.31%   |
| Plantronics                          | 25        | 0.27%   |
| Lenovo                               | 25        | 0.27%   |
| GN Netcom                            | 25        | 0.27%   |
| ASUSTek Computer                     | 23        | 0.25%   |
| BEHRINGER International              | 22        | 0.24%   |
| GYROCOM C&C                          | 16        | 0.18%   |
| Sony                                 | 15        | 0.16%   |
| Apple                                | 14        | 0.15%   |
| Sennheiser Communications            | 12        | 0.13%   |
| Samson Technologies                  | 11        | 0.12%   |
| M-Audio                              | 11        | 0.12%   |
| VIA Technologies                     | 10        | 0.11%   |
| RODE Microphones                     | 10        | 0.11%   |
| SAVITECH                             | 9         | 0.1%    |
| Giga-Byte Technology                 | 8         | 0.09%   |
| Yamaha                               | 7         | 0.08%   |
| Turtle Beach                         | 7         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.08%   |
| Astro Gaming                         | 7         | 0.08%   |
| KTMicro                              | 6         | 0.07%   |
| Elgato Systems                       | 6         | 0.07%   |
| Dell                                 | 6         | 0.07%   |
| Alesis                               | 6         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 782       | 7.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 514       | 4.66%   |
| AMD Starship/Matisse HD Audio Controller                                   | 406       | 3.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 397       | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 386       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 314       | 2.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 307       | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 288       | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 283       | 2.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 257       | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 228       | 2.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 194       | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 186       | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 178       | 1.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 171       | 1.55%   |
| Intel 8 Series HD Audio Controller                                         | 168       | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 167       | 1.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 163       | 1.48%   |
| AMD FCH Azalia Controller                                                  | 153       | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 143       | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 143       | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 142       | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                              | 138       | 1.25%   |
| Nvidia GP104 High Definition Audio Controller                              | 135       | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 132       | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 129       | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 128       | 1.16%   |
| AMD Navi 10 HDMI Audio                                                     | 112       | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 98        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 97        | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 95        | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 94        | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 91        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 87        | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 83        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 79        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 79        | 0.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 79        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 77        | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                              | 76        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 992       | 22.76%  |
| SK hynix            | 658       | 15.1%   |
| Kingston            | 523       | 12%     |
| Micron Technology   | 437       | 10.03%  |
| Corsair             | 323       | 7.41%   |
| Unknown             | 294       | 6.75%   |
| Crucial             | 280       | 6.42%   |
| G.Skill             | 241       | 5.53%   |
| A-DATA Technology   | 101       | 2.32%   |
| Ramaxel Technology  | 69        | 1.58%   |
| Elpida              | 55        | 1.26%   |
| Team                | 49        | 1.12%   |
| Patriot             | 44        | 1.01%   |
| Nanya Technology    | 41        | 0.94%   |
| Unknown (ABCD)      | 31        | 0.71%   |
| GOODRAM             | 27        | 0.62%   |
| Smart               | 22        | 0.5%    |
| Transcend           | 17        | 0.39%   |
| Unknown             | 16        | 0.37%   |
| Apacer              | 10        | 0.23%   |
| AMD                 | 9         | 0.21%   |
| Silicon Power       | 7         | 0.16%   |
| Kllisre             | 7         | 0.16%   |
| ASint Technology    | 7         | 0.16%   |
| GeIL                | 5         | 0.11%   |
| Teikon              | 4         | 0.09%   |
| Qumo                | 4         | 0.09%   |
| PNY                 | 4         | 0.09%   |
| Goldkey             | 4         | 0.09%   |
| Atermiter           | 4         | 0.09%   |
| Smart Brazil        | 3         | 0.07%   |
| SHARETRONIC         | 3         | 0.07%   |
| Neo Forza           | 3         | 0.07%   |
| Kingmax             | 3         | 0.07%   |
| CSX                 | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| Unknown (08C8)      | 2         | 0.05%   |
| TwinMOS             | 2         | 0.05%   |
| Timetec             | 2         | 0.05%   |
| Qimonda             | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 57        | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 55        | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 0.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 44        | 0.94%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 40        | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 38        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 35        | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 31        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.58%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 24        | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 20        | 0.43%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 20        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 19        | 0.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 18        | 0.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.36%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.36%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 17        | 0.36%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3                       | 17        | 0.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 16        | 0.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.34%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 16        | 0.34%   |
| Unknown                                                          | 16        | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 15        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 15        | 0.32%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 15        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.3%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 14        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2129      | 56.46%  |
| DDR3    | 1089      | 28.88%  |
| LPDDR4  | 154       | 4.08%   |
| LPDDR3  | 121       | 3.21%   |
| Unknown | 81        | 2.15%   |
| DDR2    | 73        | 1.94%   |
| SDRAM   | 71        | 1.88%   |
| DDR5    | 24        | 0.64%   |
| DDR     | 14        | 0.37%   |
| LPDDR5  | 12        | 0.32%   |
| DRAM    | 3         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2041      | 54.25%  |
| DIMM         | 1360      | 36.15%  |
| Row Of Chips | 328       | 8.72%   |
| Chip         | 20        | 0.53%   |
| Unknown      | 9         | 0.24%   |
| FB-DIMM      | 3         | 0.08%   |
| RIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1825      | 44.6%   |
| 4096  | 1109      | 27.1%   |
| 16384 | 605       | 14.78%  |
| 2048  | 350       | 8.55%   |
| 32768 | 130       | 3.18%   |
| 1024  | 66        | 1.61%   |
| 512   | 5         | 0.12%   |
| 65536 | 1         | 0.02%   |
| 3072  | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 758       | 18.35%  |
| 2667    | 714       | 17.28%  |
| 3200    | 680       | 16.46%  |
| 2400    | 337       | 8.16%   |
| 2133    | 228       | 5.52%   |
| 1333    | 198       | 4.79%   |
| 3600    | 162       | 3.92%   |
| 1867    | 99        | 2.4%    |
| 1334    | 95        | 2.3%    |
| 4267    | 67        | 1.62%   |
| 3266    | 66        | 1.6%    |
| 800     | 56        | 1.36%   |
| 3466    | 55        | 1.33%   |
| 3400    | 54        | 1.31%   |
| 3000    | 51        | 1.23%   |
| 667     | 47        | 1.14%   |
| Unknown | 35        | 0.85%   |
| 1866    | 33        | 0.8%    |
| 3733    | 32        | 0.77%   |
| 1067    | 32        | 0.77%   |
| 3800    | 27        | 0.65%   |
| 3866    | 26        | 0.63%   |
| 4199    | 25        | 0.61%   |
| 4800    | 23        | 0.56%   |
| 2933    | 23        | 0.56%   |
| 1066    | 22        | 0.53%   |
| 4266    | 17        | 0.41%   |
| 2666    | 16        | 0.39%   |
| 2800    | 12        | 0.29%   |
| 6400    | 11        | 0.27%   |
| 1800    | 11        | 0.27%   |
| 2048    | 10        | 0.24%   |
| 975     | 9         | 0.22%   |
| 8400    | 7         | 0.17%   |
| 333     | 7         | 0.17%   |
| 3666    | 6         | 0.15%   |
| 3334    | 6         | 0.15%   |
| 3500    | 4         | 0.1%    |
| 3100    | 4         | 0.1%    |
| 2448    | 4         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 53        | 40.46%  |
| Brother Industries    | 23        | 17.56%  |
| Canon                 | 15        | 11.45%  |
| Seiko Epson           | 11        | 8.4%    |
| Samsung Electronics   | 9         | 6.87%   |
| Pantum                | 3         | 2.29%   |
| Xerox                 | 2         | 1.53%   |
| Ricoh                 | 2         | 1.53%   |
| Prolific Technology   | 2         | 1.53%   |
| Dymo-CoStar           | 2         | 1.53%   |
| Apple                 | 2         | 1.53%   |
| Xiaomi                | 1         | 0.76%   |
| Sagem                 | 1         | 0.76%   |
| QinHeng Electronics   | 1         | 0.76%   |
| Oki Data              | 1         | 0.76%   |
| Lexmark International | 1         | 0.76%   |
| Kyocera               | 1         | 0.76%   |
| Graphtec America      | 1         | 0.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                               | 3         | 2.27%   |
| HP LaserJet 1300                                       | 3         | 2.27%   |
| HP ENVY 4520 series                                    | 3         | 2.27%   |
| Xerox Phaser 3020                                      | 2         | 1.52%   |
| Seiko Epson L120 Series                                | 2         | 1.52%   |
| Samsung ML-1640 Series Laser Printer                   | 2         | 1.52%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.52%   |
| HP Officejet 2620 series                               | 2         | 1.52%   |
| HP DeskJet 4530 series                                 | 2         | 1.52%   |
| HP DeskJet 2700 series                                 | 2         | 1.52%   |
| HP DeskJet 2600 series                                 | 2         | 1.52%   |
| HP DeskJet 2130 series                                 | 2         | 1.52%   |
| HP Color LaserJet Pro M453-4                           | 2         | 1.52%   |
| Canon MG5700 series                                    | 2         | 1.52%   |
| Brother MFC-L2710DW series                             | 2         | 1.52%   |
| Brother HL-L2300D series                               | 2         | 1.52%   |
| Brother HL-5370DW series                               | 2         | 1.52%   |
| Brother DCP-7040                                       | 2         | 1.52%   |
| Apple Gamesir-G3s 2.15                                 | 2         | 1.52%   |
| Xiaomi MiMouse 2                                       | 1         | 0.76%   |
| Seiko Epson Stylus NX230/SX235W Series                 | 1         | 0.76%   |
| Seiko Epson Printer                                    | 1         | 0.76%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.76%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]           | 1         | 0.76%   |
| Seiko Epson L805 Series                                | 1         | 0.76%   |
| Seiko Epson L365 Series                                | 1         | 0.76%   |
| Seiko Epson L355 Series                                | 1         | 0.76%   |
| Seiko Epson ET-4760 Series                             | 1         | 0.76%   |
| Seiko Epson ET-3850 Series                             | 1         | 0.76%   |
| Seiko Epson ET-2710 Series                             | 1         | 0.76%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.76%   |
| Samsung ML-1865                                        | 1         | 0.76%   |
| Samsung ML-1660 Series                                 | 1         | 0.76%   |
| Samsung M2020 Series                                   | 1         | 0.76%   |
| Samsung CLX-3300 Series                                | 1         | 0.76%   |
| Samsung CLX-3180 Series                                | 1         | 0.76%   |
| Samsung CLP-310 Color Laser Printer                    | 1         | 0.76%   |
| Sagem Laser Pro LL                                     | 1         | 0.76%   |
| Ricoh SP 112SU                                         | 1         | 0.76%   |
| Ricoh Printing Support                                 | 1         | 0.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 19        | 63.33%  |
| Seiko Epson        | 5         | 16.67%  |
| Hewlett-Packard    | 2         | 6.67%   |
| Visioneer          | 1         | 3.33%   |
| Ultima Electronics | 1         | 3.33%   |
| Mustek Systems     | 1         | 3.33%   |
| AGFA-Gevaert NV    | 1         | 3.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 5         | 16.67%  |
| Canon CanoScan LiDE 110                                                               | 5         | 16.67%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 2         | 6.67%   |
| Canon CanoScan LIDE 25                                                                | 2         | 6.67%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 3.33%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 3.33%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 3.33%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 3.33%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 3.33%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 3.33%   |
| HP ScanJet 3500c                                                                      | 1         | 3.33%   |
| HP ScanJet 3400cse                                                                    | 1         | 3.33%   |
| Canon CanoScan LiDE 90                                                                | 1         | 3.33%   |
| Canon CanoScan LiDE 500F                                                              | 1         | 3.33%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 3.33%   |
| Canon CanoScan LiDE 200                                                               | 1         | 3.33%   |
| Canon CanoScan LiDE 120                                                               | 1         | 3.33%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 3.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 797       | 20.33%  |
| IMC Networks                           | 466       | 11.89%  |
| Acer                                   | 298       | 7.6%    |
| Realtek Semiconductor                  | 294       | 7.5%    |
| Microdia                               | 290       | 7.4%    |
| Logitech                               | 277       | 7.07%   |
| Quanta                                 | 193       | 4.92%   |
| Sunplus Innovation Technology          | 174       | 4.44%   |
| Cheng Uei Precision Industry (Foxlink) | 139       | 3.55%   |
| Lite-On Technology                     | 112       | 2.86%   |
| Syntek                                 | 110       | 2.81%   |
| Apple                                  | 92        | 2.35%   |
| Suyin                                  | 89        | 2.27%   |
| Microsoft                              | 67        | 1.71%   |
| Silicon Motion                         | 53        | 1.35%   |
| Alcor Micro                            | 51        | 1.3%    |
| Luxvisions Innotech Limited            | 49        | 1.25%   |
| Samsung Electronics                    | 44        | 1.12%   |
| Z-Star Microelectronics                | 23        | 0.59%   |
| Ricoh                                  | 18        | 0.46%   |
| Lenovo                                 | 14        | 0.36%   |
| Creative Technology                    | 14        | 0.36%   |
| Sonix Technology                       | 13        | 0.33%   |
| Importek                               | 12        | 0.31%   |
| GEMBIRD                                | 11        | 0.28%   |
| MacroSilicon                           | 10        | 0.26%   |
| SunplusIT                              | 9         | 0.23%   |
| Primax Electronics                     | 9         | 0.23%   |
| Generalplus Technology                 | 9         | 0.23%   |
| ARC International                      | 9         | 0.23%   |
| LG Electronics                         | 8         | 0.2%    |
| Google                                 | 8         | 0.2%    |
| Genesys Logic                          | 8         | 0.2%    |
| KYE Systems (Mouse Systems)            | 7         | 0.18%   |
| DigiTech                               | 7         | 0.18%   |
| Cubeternet                             | 7         | 0.18%   |
| Unknown                                | 6         | 0.15%   |
| ALi                                    | 6         | 0.15%   |
| Valve Software                         | 5         | 0.13%   |
| Intel                                  | 5         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 205       | 5.19%   |
| IMC Networks Integrated Camera                      | 155       | 3.92%   |
| Microdia Integrated_Webcam_HD                       | 129       | 3.26%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 116       | 2.94%   |
| Realtek Integrated_Webcam_HD                        | 107       | 2.71%   |
| Acer Integrated Camera                              | 99        | 2.51%   |
| Chicony HD WebCam                                   | 92        | 2.33%   |
| Syntek Integrated Camera                            | 74        | 1.87%   |
| Logitech Webcam C270                                | 69        | 1.75%   |
| Sunplus Integrated_Webcam_HD                        | 49        | 1.24%   |
| Logitech HD Pro Webcam C920                         | 46        | 1.16%   |
| Samsung Galaxy A5 (MTP)                             | 44        | 1.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 42        | 1.06%   |
| Acer Lenovo EasyCamera                              | 39        | 0.99%   |
| Lite-On Integrated Camera                           | 38        | 0.96%   |
| Chicony HP Wide Vision HD Camera                    | 34        | 0.86%   |
| Acer HD Webcam                                      | 33        | 0.84%   |
| Chicony HP HD Camera                                | 31        | 0.78%   |
| Apple iPhone 5/5C/5S/6/SE                           | 31        | 0.78%   |
| Quanta HD User Facing                               | 29        | 0.73%   |
| Quanta HP TrueVision HD Camera                      | 28        | 0.71%   |
| Realtek USB Camera                                  | 26        | 0.66%   |
| Microsoft LifeCam HD-3000                           | 26        | 0.66%   |
| Lite-On HP HD Camera                                | 26        | 0.66%   |
| Chicony USB2.0 Camera                               | 26        | 0.66%   |
| Acer EasyCamera                                     | 25        | 0.63%   |
| Acer BisonCam, NB Pro                               | 25        | 0.63%   |
| Quanta HP Wide Vision HD Camera                     | 24        | 0.61%   |
| Chicony EasyCamera                                  | 24        | 0.61%   |
| Quanta HD Webcam                                    | 23        | 0.58%   |
| Microdia Integrated Webcam                          | 23        | 0.58%   |
| Chicony USB2.0 HD UVC WebCam                        | 23        | 0.58%   |
| Chicony Lenovo EasyCamera                           | 23        | 0.58%   |
| Chicony HD User Facing                              | 23        | 0.58%   |
| Acer SunplusIT Integrated Camera                    | 23        | 0.58%   |
| Syntek Lenovo EasyCamera                            | 21        | 0.53%   |
| Microdia USB 2.0 Camera                             | 21        | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.53%   |
| IMC Networks HD Camera                              | 21        | 0.53%   |
| Sunplus HD WebCam                                   | 20        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 258       | 31.46%  |
| Validity Sensors           | 232       | 28.29%  |
| Shenzhen Goodix Technology | 167       | 20.37%  |
| Elan Microelectronics      | 61        | 7.44%   |
| LighTuning Technology      | 33        | 4.02%   |
| Upek                       | 27        | 3.29%   |
| AuthenTec                  | 20        | 2.44%   |
| STMicroelectronics         | 8         | 0.98%   |
| Samsung Electronics        | 6         | 0.73%   |
| Focal-systems.Corp         | 4         | 0.49%   |
| DigitalPersona             | 2         | 0.24%   |
| HOLTEK                     | 1         | 0.12%   |
| Futronic Technology        | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 95        | 11.59%  |
| Shenzhen Goodix  Fingerprint Device                                        | 79        | 9.63%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 7.68%   |
| Shenzhen Goodix Fingerprint Reader                                         | 60        | 7.32%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 49        | 5.98%   |
| Elan ELAN:Fingerprint                                                      | 39        | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 4.02%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 3.41%   |
| Validity Sensors Synaptics WBDI                                            | 26        | 3.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 2.93%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 2.93%   |
| Synaptics  WBDI                                                            | 23        | 2.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 22        | 2.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 2.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.2%    |
| Elan ELAN:ARM-M4                                                           | 18        | 2.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.07%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 2.07%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 1.71%   |
| Validity Sensors VFS491                                                    | 13        | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.1%    |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.85%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.61%   |
| AuthenTec AES2810                                                          | 5         | 0.61%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 0.49%   |
| Synaptics WBDI Device                                                      | 4         | 0.49%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 0.49%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.49%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 4         | 0.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 0.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.37%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 87        | 34.66%  |
| Broadcom                          | 83        | 33.07%  |
| O2 Micro                          | 16        | 6.37%   |
| Lenovo                            | 16        | 6.37%   |
| Upek                              | 15        | 5.98%   |
| Yubico.com                        | 8         | 3.19%   |
| Gemalto (was Gemplus)             | 8         | 3.19%   |
| Realtek Semiconductor             | 4         | 1.59%   |
| VASCO Data Security International | 3         | 1.2%    |
| OmniKey                           | 3         | 1.2%    |
| SCM Microsystems                  | 1         | 0.4%    |
| Reiner SCT Kartensysteme          | 1         | 0.4%    |
| Hewlett-Packard                   | 1         | 0.4%    |
| Clay Logic                        | 1         | 0.4%    |
| Cherry                            | 1         | 0.4%    |
| C3PO                              | 1         | 0.4%    |
| BIT4ID                            | 1         | 0.4%    |
| Aladdin Knowledge Systems         | 1         | 0.4%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 86        | 34.26%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 13.55%  |
| Broadcom 5880                                                                | 23        | 9.16%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.37%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 5.98%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 5.98%   |
| Broadcom 58200                                                               | 14        | 5.58%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 4.78%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.79%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.99%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 1.59%   |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 1.2%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.8%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.4%    |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.4%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.4%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.4%    |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.4%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.4%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.4%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.4%    |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.4%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.4%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.4%    |
| C3PO USB SMART CARD READER                                                   | 1         | 0.4%    |
| BIT4ID miniLector EVO                                                        | 1         | 0.4%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.4%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.4%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4318      | 69.43%  |
| 1     | 1545      | 24.84%  |
| 2     | 325       | 5.23%   |
| 3     | 28        | 0.45%   |
| 4     | 3         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 804       | 36.33%  |
| Graphics card            | 387       | 17.49%  |
| Net/wireless             | 288       | 13.01%  |
| Chipcard                 | 218       | 9.85%   |
| Multimedia controller    | 165       | 7.46%   |
| Camera                   | 81        | 3.66%   |
| Net/ethernet             | 59        | 2.67%   |
| Unassigned class         | 47        | 2.12%   |
| Bluetooth                | 44        | 1.99%   |
| Sound                    | 24        | 1.08%   |
| Communication controller | 23        | 1.04%   |
| Storage                  | 20        | 0.9%    |
| Card reader              | 16        | 0.72%   |
| Dvb card                 | 12        | 0.54%   |
| Network                  | 8         | 0.36%   |
| Storage/raid             | 6         | 0.27%   |
| Modem                    | 4         | 0.18%   |
| Video                    | 2         | 0.09%   |
| Storage/nvme             | 2         | 0.09%   |
| Storage/ide              | 2         | 0.09%   |
| Storage/ata              | 1         | 0.05%   |

