Kubuntu 23.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_23.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_23.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 305

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f081f44bda](https://linux-hardware.org/?probe=f081f44bda) | Sep 05, 2023 |
| Samsung       | 950QED                      | Convertible | [e15539dd35](https://linux-hardware.org/?probe=e15539dd35) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| AZW           | SER V01                     | Mini pc     | [b744dfb20a](https://linux-hardware.org/?probe=b744dfb20a) | Sep 05, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [71da9ea288](https://linux-hardware.org/?probe=71da9ea288) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [31cb6a887e](https://linux-hardware.org/?probe=31cb6a887e) | Sep 04, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1f47bfe737](https://linux-hardware.org/?probe=1f47bfe737) | Aug 26, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [65b6b29fc7](https://linux-hardware.org/?probe=65b6b29fc7) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| Dell          | Precision 7780              | Notebook    | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [7bd62bca50](https://linux-hardware.org/?probe=7bd62bca50) | Aug 23, 2023 |
| Intel         | H55                         | Desktop     | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c78c246642](https://linux-hardware.org/?probe=c78c246642) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9a7f33c81b](https://linux-hardware.org/?probe=9a7f33c81b) | Aug 20, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b5973b3c67](https://linux-hardware.org/?probe=b5973b3c67) | Aug 18, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [f0d325d7d3](https://linux-hardware.org/?probe=f0d325d7d3) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [a395628119](https://linux-hardware.org/?probe=a395628119) | Aug 15, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [e338ac8876](https://linux-hardware.org/?probe=e338ac8876) | Aug 14, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [0c8514df53](https://linux-hardware.org/?probe=0c8514df53) | Aug 13, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [97c78c17bd](https://linux-hardware.org/?probe=97c78c17bd) | Aug 12, 2023 |
| AZW           | SER V01                     | Mini pc     | [542d8da36c](https://linux-hardware.org/?probe=542d8da36c) | Aug 11, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Precision 7670              | Notebook    | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| HP            | 158A                        | Desktop     | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [5e552472e5](https://linux-hardware.org/?probe=5e552472e5) | Aug 03, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [4d21c35777](https://linux-hardware.org/?probe=4d21c35777) | Aug 03, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | 158A                        | Desktop     | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Google        | Zako                        | Desktop     | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [65a741810c](https://linux-hardware.org/?probe=65a741810c) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [e5ad011556](https://linux-hardware.org/?probe=e5ad011556) | Jul 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| AZW           | SER V01                     | Mini pc     | [440a88b8bf](https://linux-hardware.org/?probe=440a88b8bf) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [273533f7f8](https://linux-hardware.org/?probe=273533f7f8) | Jul 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| HP            | G62                         | Notebook    | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| HP            | 83E9                        | Desktop     | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [392b85a82b](https://linux-hardware.org/?probe=392b85a82b) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0008f72dbf](https://linux-hardware.org/?probe=0008f72dbf) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [745fa6a1b4](https://linux-hardware.org/?probe=745fa6a1b4) | Jul 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [6f62e1063c](https://linux-hardware.org/?probe=6f62e1063c) | Jul 11, 2023 |
| Dell          | G3 3779                     | Notebook    | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | 2B3E                        | All in one  | [9ec58b6284](https://linux-hardware.org/?probe=9ec58b6284) | Jul 09, 2023 |
| Acer          | Predator G3-572             | Notebook    | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| MSI           | B360M MORTAR TITANIUM       | Desktop     | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Dell          | G3 3779                     | Notebook    | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| AZW           | SER V01                     | Mini pc     | [49552e2240](https://linux-hardware.org/?probe=49552e2240) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | Desktop     | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0ec1b06d0c](https://linux-hardware.org/?probe=0ec1b06d0c) | Jun 13, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [787fa3215e](https://linux-hardware.org/?probe=787fa3215e) | Jun 12, 2023 |
| Dell          | G3 3779                     | Notebook    | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Seco          | C40 C                       | Desktop     | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6b694e4b4a](https://linux-hardware.org/?probe=6b694e4b4a) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [0b7fb76a0b](https://linux-hardware.org/?probe=0b7fb76a0b) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| Google        | Bluebird                    | Notebook    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| Unknown       | V00                         | Mini pc     | [79cb590ea8](https://linux-hardware.org/?probe=79cb590ea8) | May 17, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [0906223758](https://linux-hardware.org/?probe=0906223758) | May 17, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c071e02f0d](https://linux-hardware.org/?probe=c071e02f0d) | May 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| Biostar       | AM1MHP                      | Desktop     | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | Notebook    | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fee636a549](https://linux-hardware.org/?probe=fee636a549) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [09717388fb](https://linux-hardware.org/?probe=09717388fb) | Mar 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Samsung       | 950QDB                      | Convertible | [2545626207](https://linux-hardware.org/?probe=2545626207) | Feb 23, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 78        | 31.97%  |
| 6.2.0-27-generic        | 26        | 10.66%  |
| 6.2.0-26-generic        | 25        | 10.25%  |
| 6.2.0-24-generic        | 20        | 8.2%    |
| 6.2.0-23-generic        | 17        | 6.97%   |
| 6.2.0-25-generic        | 13        | 5.33%   |
| 6.2.0-32-generic        | 6         | 2.46%   |
| 6.2.0-31-generic        | 6         | 2.46%   |
| 6.2.0-18-generic        | 4         | 1.64%   |
| 6.2.0-1007-lowlatency   | 4         | 1.64%   |
| 6.2.0-1003-lowlatency   | 4         | 1.64%   |
| 6.2.0-1009-lowlatency   | 3         | 1.23%   |
| 6.4.8-060408-generic    | 2         | 0.82%   |
| 6.4.0-060400-generic    | 2         | 0.82%   |
| 6.2.0-1011-lowlatency   | 2         | 0.82%   |
| 6.2.0-1008-lowlatency   | 2         | 0.82%   |
| 6.2.0-1005-lowlatency   | 2         | 0.82%   |
| 5.19.0-28-generic       | 2         | 0.82%   |
| 6.4.6-060406-generic    | 1         | 0.41%   |
| 6.4.3-1-liquorix-amd64  | 1         | 0.41%   |
| 6.4.1-2-liquorix-amd64  | 1         | 0.41%   |
| 6.3.8-x64v3-xanmod1     | 1         | 0.41%   |
| 6.3.8                   | 1         | 0.41%   |
| 6.3.7-060307-generic    | 1         | 0.41%   |
| 6.3.6-custom            | 1         | 0.41%   |
| 6.3.5-060305-generic    | 1         | 0.41%   |
| 6.3.4-060304-generic    | 1         | 0.41%   |
| 6.3.3-060303-generic    | 1         | 0.41%   |
| 6.3.10                  | 1         | 0.41%   |
| 6.3.1-custom            | 1         | 0.41%   |
| 6.3.1-060301-generic    | 1         | 0.41%   |
| 6.2.5-060205-generic    | 1         | 0.41%   |
| 6.2.10-060210-generic   | 1         | 0.41%   |
| 6.2.0-21-generic        | 1         | 0.41%   |
| 6.2.0-060200-generic    | 1         | 0.41%   |
| 6.1.12-060112-generic   | 1         | 0.41%   |
| 6.1.11-custom           | 1         | 0.41%   |
| 6.1.0-16-generic        | 1         | 0.41%   |
| 6.1.0-14-generic        | 1         | 0.41%   |
| 6.1.0-060100rc4-generic | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 203       | 87.12%  |
| 5.19.0  | 6         | 2.58%   |
| 6.1.0   | 3         | 1.29%   |
| 6.4.8   | 2         | 0.86%   |
| 6.4.0   | 2         | 0.86%   |
| 6.3.8   | 2         | 0.86%   |
| 6.3.1   | 2         | 0.86%   |
| 6.4.6   | 1         | 0.43%   |
| 6.4.3   | 1         | 0.43%   |
| 6.4.1   | 1         | 0.43%   |
| 6.3.7   | 1         | 0.43%   |
| 6.3.6   | 1         | 0.43%   |
| 6.3.5   | 1         | 0.43%   |
| 6.3.4   | 1         | 0.43%   |
| 6.3.3   | 1         | 0.43%   |
| 6.3.10  | 1         | 0.43%   |
| 6.2.5   | 1         | 0.43%   |
| 6.2.10  | 1         | 0.43%   |
| 6.1.12  | 1         | 0.43%   |
| 6.1.11  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 205       | 87.98%  |
| 6.3     | 10        | 4.29%   |
| 6.4     | 7         | 3%      |
| 5.19    | 6         | 2.58%   |
| 6.1     | 5         | 2.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 230       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 219       | 95.22%  |
| KDE   | 8         | 3.48%   |
| GNOME | 2         | 0.87%   |
| LXQt  | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 190       | 82.25%  |
| Wayland | 39        | 16.88%  |
| Tty     | 2         | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 138       | 59.74%  |
| Unknown | 82        | 35.5%   |
| GDM3    | 7         | 3.03%   |
| LightDM | 4         | 1.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 114       | 49.57%  |
| de_DE  | 25        | 10.87%  |
| en_GB  | 17        | 7.39%   |
| ru_RU  | 11        | 4.78%   |
| fr_FR  | 8         | 3.48%   |
| pt_BR  | 7         | 3.04%   |
| pl_PL  | 7         | 3.04%   |
| it_IT  | 7         | 3.04%   |
| en_CA  | 3         | 1.3%    |
| C      | 3         | 1.3%    |
| fr_BE  | 2         | 0.87%   |
| es_MX  | 2         | 0.87%   |
| es_CR  | 2         | 0.87%   |
| es_CL  | 2         | 0.87%   |
| en_NZ  | 2         | 0.87%   |
| en_IN  | 2         | 0.87%   |
| en_AU  | 2         | 0.87%   |
| zh_TW  | 1         | 0.43%   |
| zh_HK  | 1         | 0.43%   |
| sv_SE  | 1         | 0.43%   |
| pt_PT  | 1         | 0.43%   |
| nl_NL  | 1         | 0.43%   |
| nb_NO  | 1         | 0.43%   |
| hu_HU  | 1         | 0.43%   |
| es_PE  | 1         | 0.43%   |
| es_ES  | 1         | 0.43%   |
| es_CO  | 1         | 0.43%   |
| es_419 | 1         | 0.43%   |
| en_IL  | 1         | 0.43%   |
| en_DK  | 1         | 0.43%   |
| da_DK  | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 123       | 53.25%  |
| EFI  | 108       | 46.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 159       | 68.53%  |
| Tmpfs   | 49        | 21.12%  |
| Btrfs   | 15        | 6.47%   |
| Overlay | 5         | 2.16%   |
| Zfs     | 2         | 0.86%   |
| Xfs     | 1         | 0.43%   |
| F2fs    | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 143       | 61.9%   |
| Unknown | 81        | 35.06%  |
| MBR     | 7         | 3.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 90.09%  |
| Yes       | 23        | 9.91%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 71.74%  |
| Yes       | 65        | 28.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 40        | 17.39%  |
| Lenovo                 | 35        | 15.22%  |
| Hewlett-Packard        | 35        | 15.22%  |
| Gigabyte Technology    | 19        | 8.26%   |
| Dell                   | 18        | 7.83%   |
| MSI                    | 15        | 6.52%   |
| Acer                   | 11        | 4.78%   |
| Apple                  | 7         | 3.04%   |
| ASRock                 | 6         | 2.61%   |
| Intel                  | 5         | 2.17%   |
| Google                 | 5         | 2.17%   |
| HUAWEI                 | 4         | 1.74%   |
| AZW                    | 4         | 1.74%   |
| Samsung Electronics    | 3         | 1.3%    |
| Unknown                | 3         | 1.3%    |
| Fujitsu                | 2         | 0.87%   |
| Alienware              | 2         | 0.87%   |
| TECNO                  | 1         | 0.43%   |
| Seco                   | 1         | 0.43%   |
| Pegatron               | 1         | 0.43%   |
| Medion                 | 1         | 0.43%   |
| Huanan                 | 1         | 0.43%   |
| HPE                    | 1         | 0.43%   |
| GPU Company            | 1         | 0.43%   |
| GPD                    | 1         | 0.43%   |
| Gateway                | 1         | 0.43%   |
| Framework              | 1         | 0.43%   |
| Foxconn                | 1         | 0.43%   |
| BOSGAME                | 1         | 0.43%   |
| Biostar                | 1         | 0.43%   |
| BESSTAR Tech           | 1         | 0.43%   |
| Avell High Performance | 1         | 0.43%   |
| AMI                    | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AZW SER                                     | 4         | 1.74%   |
| Unknown                                     | 3         | 1.3%    |
| MSI MS-7C95                                 | 2         | 0.87%   |
| MSI MS-7C56                                 | 2         | 0.87%   |
| Intel NUC12WSHi7                            | 2         | 0.87%   |
| HP ProBook 650 G1                           | 2         | 0.87%   |
| HP ENVY x360 Convertible 13-ay0xxx          | 2         | 0.87%   |
| Gigabyte B550 AORUS ELITE V2                | 2         | 0.87%   |
| Dell G3 3779                                | 2         | 0.87%   |
| ASUS TUF Gaming B550-PLUS                   | 2         | 0.87%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI    | 2         | 0.87%   |
| TECNO MEGABOOK T1                           | 1         | 0.43%   |
| Seco C40                                    | 1         | 0.43%   |
| Samsung 950XED                              | 1         | 0.43%   |
| Samsung 950QED                              | 1         | 0.43%   |
| Samsung 950QDB                              | 1         | 0.43%   |
| Pegatron 520-1000nl                         | 1         | 0.43%   |
| MSI Titan GT77HX 13VH                       | 1         | 0.43%   |
| MSI Raider GE67HX 12UGS                     | 1         | 0.43%   |
| MSI MS-7D75                                 | 1         | 0.43%   |
| MSI MS-7D74                                 | 1         | 0.43%   |
| MSI MS-7D17                                 | 1         | 0.43%   |
| MSI MS-7B86                                 | 1         | 0.43%   |
| MSI MS-7B23                                 | 1         | 0.43%   |
| MSI MS-7A32                                 | 1         | 0.43%   |
| MSI MS-7846                                 | 1         | 0.43%   |
| MSI MS-7693                                 | 1         | 0.43%   |
| MSI Bravo 17 A4DDK                          | 1         | 0.43%   |
| Medion E11201                               | 1         | 0.43%   |
| Lenovo Yoga Slim 7 Pro 16ACH6 82QQ          | 1         | 0.43%   |
| Lenovo Yoga C640-13IML 81UE                 | 1         | 0.43%   |
| Lenovo Yoga 6 13ALC7 82UD                   | 1         | 0.43%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LES3485R      | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB0088RT | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007ART | 1         | 0.43%   |
| Lenovo ThinkPad W510 4391EC4                | 1         | 0.43%   |
| Lenovo ThinkPad P15s Gen 2i 20W7S0SM01      | 1         | 0.43%   |
| Lenovo ThinkPad P14s Gen 1 20S5S01V00       | 1         | 0.43%   |
| Lenovo ThinkPad P1 Gen 2 20QT000LGE         | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 14        | 6.09%   |
| Lenovo IdeaPad      | 11        | 4.78%   |
| ASUS PRIME          | 10        | 4.35%   |
| ASUS ROG            | 9         | 3.91%   |
| Acer Aspire         | 7         | 3.04%   |
| HP ENVY             | 6         | 2.61%   |
| HP EliteBook        | 6         | 2.61%   |
| Dell Latitude       | 6         | 2.61%   |
| HP Pavilion         | 5         | 2.17%   |
| Gigabyte B550       | 4         | 1.74%   |
| Dell Precision      | 4         | 1.74%   |
| AZW SER             | 4         | 1.74%   |
| ASUS ASUS           | 4         | 1.74%   |
| Lenovo Yoga         | 3         | 1.3%    |
| Lenovo Legion       | 3         | 1.3%    |
| HP ProBook          | 3         | 1.3%    |
| HP Laptop           | 3         | 1.3%    |
| Dell XPS            | 3         | 1.3%    |
| ASUS VivoBook       | 3         | 1.3%    |
| ASUS TUF            | 3         | 1.3%    |
| Unknown             | 3         | 1.3%    |
| MSI MS-7C95         | 2         | 0.87%   |
| MSI MS-7C56         | 2         | 0.87%   |
| Intel NUC12WSHi7    | 2         | 0.87%   |
| HP ZBook            | 2         | 0.87%   |
| HP Compaq           | 2         | 0.87%   |
| Gigabyte X570S      | 2         | 0.87%   |
| Gigabyte G5         | 2         | 0.87%   |
| Gigabyte B365M      | 2         | 0.87%   |
| Dell Inspiron       | 2         | 0.87%   |
| Dell G3             | 2         | 0.87%   |
| ASUS Zenbook        | 2         | 0.87%   |
| Apple MacBookPro9   | 2         | 0.87%   |
| Acer Nitro          | 2         | 0.87%   |
| TECNO MEGABOOK      | 1         | 0.43%   |
| Seco C40            | 1         | 0.43%   |
| Samsung 950XED      | 1         | 0.43%   |
| Samsung 950QED      | 1         | 0.43%   |
| Samsung 950QDB      | 1         | 0.43%   |
| Pegatron 520-1000nl | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 39        | 16.96%  |
| 2022 | 37        | 16.09%  |
| 2020 | 28        | 12.17%  |
| 2019 | 26        | 11.3%   |
| 2018 | 15        | 6.52%   |
| 2011 | 12        | 5.22%   |
| 2023 | 11        | 4.78%   |
| 2012 | 11        | 4.78%   |
| 2017 | 10        | 4.35%   |
| 2014 | 9         | 3.91%   |
| 2015 | 8         | 3.48%   |
| 2013 | 8         | 3.48%   |
| 2016 | 6         | 2.61%   |
| 2010 | 5         | 2.17%   |
| 2009 | 4         | 1.74%   |
| 2007 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 124       | 53.91%  |
| Desktop     | 78        | 33.91%  |
| Convertible | 14        | 6.09%   |
| Mini pc     | 8         | 3.48%   |
| All in one  | 4         | 1.74%   |
| Tablet      | 1         | 0.43%   |
| Server      | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 218       | 94.78%  |
| Enabled  | 12        | 5.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 225       | 97.83%  |
| Yes  | 5         | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 52        | 22.51%  |
| 16.01-24.0  | 50        | 21.65%  |
| 4.01-8.0    | 44        | 19.05%  |
| 32.01-64.0  | 43        | 18.61%  |
| 3.01-4.0    | 18        | 7.79%   |
| 64.01-256.0 | 15        | 6.49%   |
| 24.01-32.0  | 8         | 3.46%   |
| 2.01-3.0    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 78        | 32.5%   |
| 2.01-3.0   | 63        | 26.25%  |
| 3.01-4.0   | 40        | 16.67%  |
| 1.01-2.0   | 33        | 13.75%  |
| 8.01-16.0  | 22        | 9.17%   |
| 16.01-24.0 | 2         | 0.83%   |
| 32.01-64.0 | 1         | 0.42%   |
| 24.01-32.0 | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 118       | 50.64%  |
| 2      | 65        | 27.9%   |
| 3      | 24        | 10.3%   |
| 4      | 16        | 6.87%   |
| 5      | 5         | 2.15%   |
| 7      | 2         | 0.86%   |
| 6      | 2         | 0.86%   |
| 8      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 80.52%  |
| Yes       | 45        | 19.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 79.65%  |
| No        | 47        | 20.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 80.87%  |
| No        | 44        | 19.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 72.61%  |
| No        | 63        | 27.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 46        | 20%     |
| Germany      | 33        | 14.35%  |
| UK           | 19        | 8.26%   |
| Russia       | 14        | 6.09%   |
| France       | 11        | 4.78%   |
| Brazil       | 9         | 3.91%   |
| Poland       | 8         | 3.48%   |
| Italy        | 6         | 2.61%   |
| Canada       | 6         | 2.61%   |
| Sweden       | 5         | 2.17%   |
| Netherlands  | 5         | 2.17%   |
| Belgium      | 5         | 2.17%   |
| Turkey       | 4         | 1.74%   |
| Switzerland  | 4         | 1.74%   |
| Mexico       | 4         | 1.74%   |
| India        | 4         | 1.74%   |
| Hungary      | 4         | 1.74%   |
| Portugal     | 3         | 1.3%    |
| Taiwan       | 2         | 0.87%   |
| Spain        | 2         | 0.87%   |
| Serbia       | 2         | 0.87%   |
| Saudi Arabia | 2         | 0.87%   |
| Peru         | 2         | 0.87%   |
| New Zealand  | 2         | 0.87%   |
| Kazakhstan   | 2         | 0.87%   |
| Israel       | 2         | 0.87%   |
| Costa Rica   | 2         | 0.87%   |
| Colombia     | 2         | 0.87%   |
| Chile        | 2         | 0.87%   |
| Australia    | 2         | 0.87%   |
| Slovakia     | 1         | 0.43%   |
| Romania      | 1         | 0.43%   |
| Norway       | 1         | 0.43%   |
| Luxembourg   | 1         | 0.43%   |
| Lithuania    | 1         | 0.43%   |
| Libya        | 1         | 0.43%   |
| Latvia       | 1         | 0.43%   |
| Ivory Coast  | 1         | 0.43%   |
| Indonesia    | 1         | 0.43%   |
| Georgia      | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Munich          | 4         | 1.72%   |
| Moscow          | 4         | 1.72%   |
| London          | 4         | 1.72%   |
| Berlin          | 4         | 1.72%   |
| Istanbul        | 3         | 1.29%   |
| Hamburg         | 3         | 1.29%   |
| Warsaw          | 2         | 0.86%   |
| Virginia Beach  | 2         | 0.86%   |
| Valley Center   | 2         | 0.86%   |
| Sherbrooke      | 2         | 0.86%   |
| Porto Alegre    | 2         | 0.86%   |
| Portimao        | 2         | 0.86%   |
| Paris           | 2         | 0.86%   |
| Oberburg        | 2         | 0.86%   |
| Münster        | 2         | 0.86%   |
| Minneapolis     | 2         | 0.86%   |
| Grecia          | 2         | 0.86%   |
| Brussels        | 2         | 0.86%   |
| Arzamas         | 2         | 0.86%   |
| Abtwil          | 2         | 0.86%   |
| Zamora          | 1         | 0.43%   |
| Yerevan         | 1         | 0.43%   |
| Woodstock       | 1         | 0.43%   |
| Wiesmoor        | 1         | 0.43%   |
| West Valley     | 1         | 0.43%   |
| West Des Moines | 1         | 0.43%   |
| Weilmuenster    | 1         | 0.43%   |
| Warwick         | 1         | 0.43%   |
| Ware            | 1         | 0.43%   |
| Waldorf         | 1         | 0.43%   |
| Waianae         | 1         | 0.43%   |
| Vsevolozhsk     | 1         | 0.43%   |
| Vol'ginskiy     | 1         | 0.43%   |
| Viña del Mar   | 1         | 0.43%   |
| Vilnius         | 1         | 0.43%   |
| Villa Dominico  | 1         | 0.43%   |
| Vienna          | 1         | 0.43%   |
| Vancouver       | 1         | 0.43%   |
| Vaggeryd        | 1         | 0.43%   |
| Ulm             | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 66        | 92     | 17.23%  |
| WDC                         | 41        | 49     | 10.7%   |
| Seagate                     | 34        | 51     | 8.88%   |
| SanDisk                     | 32        | 35     | 8.36%   |
| Kingston                    | 21        | 26     | 5.48%   |
| Crucial                     | 18        | 23     | 4.7%    |
| Toshiba                     | 17        | 21     | 4.44%   |
| Intel                       | 14        | 15     | 3.66%   |
| Micron Technology           | 13        | 14     | 3.39%   |
| SK hynix                    | 12        | 12     | 3.13%   |
| Phison Electronics          | 9         | 9      | 2.35%   |
| Hitachi                     | 7         | 7      | 1.83%   |
| Silicon Motion              | 6         | 6      | 1.57%   |
| A-DATA Technology           | 6         | 6      | 1.57%   |
| Unknown                     | 5         | 5      | 1.31%   |
| Micron/Crucial Technology   | 5         | 7      | 1.31%   |
| Kingston Technology Company | 5         | 6      | 1.31%   |
| HGST                        | 5         | 6      | 1.31%   |
| China                       | 4         | 4      | 1.04%   |
| PNY                         | 3         | 3      | 0.78%   |
| Patriot                     | 3         | 3      | 0.78%   |
| KIOXIA                      | 3         | 3      | 0.78%   |
| UMIS                        | 2         | 3      | 0.52%   |
| Team                        | 2         | 2      | 0.52%   |
| SPCC                        | 2         | 6      | 0.52%   |
| Solid State Storage         | 2         | 2      | 0.52%   |
| Maxtor                      | 2         | 2      | 0.52%   |
| Lexar                       | 2         | 2      | 0.52%   |
| Hewlett-Packard             | 2         | 3      | 0.52%   |
| Corsair                     | 2         | 2      | 0.52%   |
| Apple                       | 2         | 2      | 0.52%   |
| ADATA Technology            | 2         | 2      | 0.52%   |
| Unknown                     | 2         | 2      | 0.52%   |
| Wibtek                      | 1         | 1      | 0.26%   |
| WALRAM                      | 1         | 1      | 0.26%   |
| Vaseky                      | 1         | 1      | 0.26%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.26%   |
| Transcend                   | 1         | 1      | 0.26%   |
| SSSTC                       | 1         | 1      | 0.26%   |
| SSDPR-CX                    | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 7         | 1.64%   |
| Samsung SSD 860 EVO 500GB                             | 5         | 1.17%   |
| Intel SSD 660P Series 512GB                           | 5         | 1.17%   |
| Seagate ST4000DM004-2CV104 4TB                        | 4         | 0.94%   |
| Sandisk WD Black SN850 256GB                          | 4         | 0.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 4         | 0.94%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 4         | 0.94%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 4         | 0.94%   |
| Kingston SNVS500G 500GB                               | 4         | 0.94%   |
| Kingston SA400S37480G 480GB SSD                       | 4         | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB                        | 3         | 0.7%    |
| Sandisk WD_BLACK SN850X 4000GB                        | 3         | 0.7%    |
| SanDisk NVMe SSD Drive 2TB                            | 3         | 0.7%    |
| Samsung SSD 980 PRO 2TB                               | 3         | 0.7%    |
| Samsung SSD 980 PRO 1TB                               | 3         | 0.7%    |
| Samsung SSD 980 1TB                                   | 3         | 0.7%    |
| Samsung SSD 870 QVO 1TB                               | 3         | 0.7%    |
| Samsung SSD 850 EVO 250GB                             | 3         | 0.7%    |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 3         | 0.7%    |
| Kingston Company SNV2S1000G 1TB                       | 3         | 0.7%    |
| WDC WD5000AAKX-60U6AA0 500GB                          | 2         | 0.47%   |
| WDC WD Blue SA510 2.5 1000GB                          | 2         | 0.47%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                  | 2         | 0.47%   |
| Unknown MMC Card  32GB                                | 2         | 0.47%   |
| UMIS RPJTJ512MGE1QDQ 512GB                            | 2         | 0.47%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 0.47%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 2         | 0.47%   |
| Seagate ST1000DM003-1ER162 1TB                        | 2         | 0.47%   |
| Seagate Backup+ Hub BK 8TB                            | 2         | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 2         | 0.47%   |
| SanDisk NVMe SSD Drive 1TB                            | 2         | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2         | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 0.47%   |
| Samsung SSD 870 QVO 2TB                               | 2         | 0.47%   |
| Samsung SSD 850 PRO 512GB                             | 2         | 0.47%   |
| Samsung MZVLQ256HAJD-000H1 256GB                      | 2         | 0.47%   |
| Samsung MZVL21T0HCLR-00B00 1TB                        | 2         | 0.47%   |
| Samsung HD103SI 1TB                                   | 2         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 49     | 36.26%  |
| WDC                 | 25        | 30     | 27.47%  |
| Toshiba             | 13        | 16     | 14.29%  |
| Hitachi             | 7         | 7      | 7.69%   |
| HGST                | 5         | 6      | 5.49%   |
| Samsung Electronics | 3         | 3      | 3.3%    |
| Maxtor              | 2         | 2      | 2.2%    |
| Unknown             | 1         | 1      | 1.1%    |
| PHD 3.0             | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 32     | 17.5%   |
| Kingston            | 15        | 18     | 12.5%   |
| WDC                 | 11        | 13     | 9.17%   |
| SanDisk             | 11        | 12     | 9.17%   |
| Crucial             | 11        | 14     | 9.17%   |
| Micron Technology   | 5         | 6      | 4.17%   |
| Intel               | 4         | 5      | 3.33%   |
| China               | 4         | 4      | 3.33%   |
| PNY                 | 3         | 3      | 2.5%    |
| Patriot             | 3         | 3      | 2.5%    |
| A-DATA Technology   | 3         | 3      | 2.5%    |
| Team                | 2         | 2      | 1.67%   |
| SK hynix            | 2         | 2      | 1.67%   |
| Seagate             | 2         | 2      | 1.67%   |
| Hewlett-Packard     | 2         | 2      | 1.67%   |
| Vaseky              | 1         | 1      | 0.83%   |
| Transcend           | 1         | 1      | 0.83%   |
| SPCC                | 1         | 5      | 0.83%   |
| Smartbuy            | 1         | 1      | 0.83%   |
| S3+                 | 1         | 1      | 0.83%   |
| Neo                 | 1         | 1      | 0.83%   |
| LITEON              | 1         | 1      | 0.83%   |
| Lexar               | 1         | 1      | 0.83%   |
| Lenovo              | 1         | 1      | 0.83%   |
| JMicron Technology  | 1         | 1      | 0.83%   |
| INNOVATION IT       | 1         | 1      | 0.83%   |
| Hoodisk             | 1         | 1      | 0.83%   |
| Gigabyte Technology | 1         | 1      | 0.83%   |
| FURY                | 1         | 2      | 0.83%   |
| Emtec               | 1         | 2      | 0.83%   |
| CT2000BX            | 1         | 1      | 0.83%   |
| CT1000MX            | 1         | 1      | 0.83%   |
| Corsair             | 1         | 1      | 0.83%   |
| BAITITON            | 1         | 2      | 0.83%   |
| AMD                 | 1         | 1      | 0.83%   |
| Unknown             | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 146       | 189    | 43.84%  |
| SSD     | 106       | 149    | 31.83%  |
| HDD     | 68        | 116    | 20.42%  |
| Unknown | 9         | 10     | 2.7%    |
| MMC     | 4         | 4      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 146       | 189    | 48.5%   |
| SATA | 133       | 257    | 44.19%  |
| SAS  | 18        | 18     | 5.98%   |
| MMC  | 4         | 4      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 121    | 45.55%  |
| 0.51-1.0   | 67        | 92     | 35.08%  |
| 1.01-2.0   | 21        | 30     | 10.99%  |
| 3.01-4.0   | 7         | 9      | 3.66%   |
| 4.01-10.0  | 7         | 11     | 3.66%   |
| 2.01-3.0   | 1         | 1      | 0.52%   |
| 10.01-20.0 | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 24.68%  |
| 251-500        | 45        | 19.15%  |
| 501-1000       | 45        | 19.15%  |
| 1001-2000      | 32        | 13.62%  |
| More than 3000 | 24        | 10.21%  |
| 51-100         | 11        | 4.68%   |
| 2001-3000      | 10        | 4.26%   |
| 1-20           | 7         | 2.98%   |
| 21-50          | 3         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 50        | 20.83%  |
| 1-20           | 47        | 19.58%  |
| 101-250        | 41        | 17.08%  |
| 251-500        | 26        | 10.83%  |
| 51-100         | 25        | 10.42%  |
| 501-1000       | 24        | 10%     |
| 1001-2000      | 13        | 5.42%   |
| More than 3000 | 8         | 3.33%   |
| 2001-3000      | 6         | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 2      | 4%      |
| WDC WD3200AAJS-65M0A0 320GB                  | 1         | 1      | 4%      |
| WDC WD10EZEX-22MFCA0 1TB                     | 1         | 1      | 4%      |
| WDC WD10EURX-63UY4Y0 1TB                     | 1         | 1      | 4%      |
| WDC WD10EAVS-00D7B1 1TB                      | 1         | 1      | 4%      |
| WDC WD10EADS-65L5B1 1TB                      | 1         | 1      | 4%      |
| WDC WD Blue SA510 2.5 1000GB                 | 1         | 1      | 4%      |
| Toshiba MQ01ABD075 752GB                     | 1         | 2      | 4%      |
| Team L3 EVO SSD 120GB                        | 1         | 1      | 4%      |
| SK hynix HFS256G32MND-2900A 256GB SSD        | 1         | 1      | 4%      |
| Seagate ST3500320AS 500GB                    | 1         | 1      | 4%      |
| Seagate ST1000VX000-1CU162 1TB               | 1         | 1      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 4%      |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 4%      |
| SanDisk SDSSDXPS480G 480GB                   | 1         | 1      | 4%      |
| Samsung Electronics SSD 970 EVO Plus 1TB     | 1         | 1      | 4%      |
| Samsung Electronics SSD 850 EVO 250GB        | 1         | 1      | 4%      |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 4%      |
| Samsung Electronics HD103SI 1TB              | 1         | 1      | 4%      |
| Neo Forza NFS121SA312-6007000 120GB SSD      | 1         | 1      | 4%      |
| Maxtor STM3160215AS 160GB                    | 1         | 1      | 4%      |
| Intel SSDSCKKW240H6 240GB                    | 1         | 1      | 4%      |
| Intel SSDPEKNW512G8 512GB                    | 1         | 1      | 4%      |
| Intel SSDPEKNU512GZ 512GB                    | 1         | 1      | 4%      |
| Apple HDD HTS541010A9E662 1TB                | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 28%     |
| Seagate             | 4         | 4      | 16%     |
| Samsung Electronics | 4         | 5      | 16%     |
| Intel               | 3         | 3      | 12%     |
| Toshiba             | 1         | 2      | 4%      |
| Team                | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Neo                 | 1         | 1      | 4%      |
| Maxtor              | 1         | 1      | 4%      |
| Apple               | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 42.86%  |
| Seagate             | 4         | 4      | 28.57%  |
| Toshiba             | 1         | 2      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Maxtor              | 1         | 1      | 7.14%   |
| Apple               | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 16     | 50%     |
| SSD  | 7         | 9      | 35%     |
| NVMe | 3         | 3      | 15%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 144       | 290    | 56.92%  |
| Works    | 89        | 148    | 35.18%  |
| Malfunc  | 19        | 28     | 7.51%   |
| Failed   | 1         | 2      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 119       | 34.39%  |
| AMD                            | 61        | 17.63%  |
| Samsung Electronics            | 46        | 13.29%  |
| SanDisk                        | 27        | 7.8%    |
| Micron/Crucial Technology      | 12        | 3.47%   |
| Phison Electronics             | 11        | 3.18%   |
| SK hynix                       | 10        | 2.89%   |
| Kingston Technology Company    | 10        | 2.89%   |
| Micron Technology              | 8         | 2.31%   |
| Silicon Motion                 | 7         | 2.02%   |
| ASMedia Technology             | 5         | 1.45%   |
| ADATA Technology               | 5         | 1.45%   |
| Toshiba America Info Systems   | 4         | 1.16%   |
| Union Memory (Shenzhen)        | 3         | 0.87%   |
| Solid State Storage Technology | 3         | 0.87%   |
| KIOXIA                         | 3         | 0.87%   |
| Shenzhen Longsys Electronics   | 2         | 0.58%   |
| Realtek Semiconductor          | 2         | 0.58%   |
| JMicron Technology             | 2         | 0.58%   |
| Silicon Image                  | 1         | 0.29%   |
| Nvidia                         | 1         | 0.29%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.29%   |
| Marvell Technology Group       | 1         | 0.29%   |
| Biwin Storage Technology       | 1         | 0.29%   |
| Apple                          | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 44        | 11.64%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 19        | 5.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 3.44%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 2.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 2.91%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 2.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 9         | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 2.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 2.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 2.12%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 1.85%   |
| Intel SSD 660P Series                                                          | 7         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.85%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 6         | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 1.32%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.06%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 1.06%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.06%   |
| Kingston Company NVMe Controller                                               | 4         | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.06%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 4         | 1.06%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.79%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 3         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.79%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.79%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.79%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.79%   |
| AMD X370 Series Chipset SATA Controller                                        | 3         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 158       | 48.17%  |
| NVMe | 146       | 44.51%  |
| RAID | 18        | 5.49%   |
| IDE  | 6         | 1.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 145       | 63.04%  |
| AMD    | 85        | 36.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 3.91%   |
| Intel 12th Gen Core i7-1260P                  | 7         | 3.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.74%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.3%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.3%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 1.3%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.3%    |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 1.3%    |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 1.3%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.3%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.3%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.3%    |
| AMD Ryzen 5 5600U with Radeon Graphics        | 3         | 1.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.87%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.87%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.87%   |
| Intel Celeron N5100 @ 1.10GHz                 | 2         | 0.87%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.87%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.87%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.87%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.87%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 2         | 0.87%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.87%   |
| Intel Xeon CPU W3580 @ 3.33GHz                | 1         | 0.43%   |
| Intel Xeon CPU E5-4627 v4 @ 2.60GHz           | 1         | 0.43%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz           | 1         | 0.43%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz           | 1         | 0.43%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 18.7%   |
| Other                   | 39        | 16.96%  |
| Intel Core i7           | 36        | 15.65%  |
| AMD Ryzen 5             | 33        | 14.35%  |
| AMD Ryzen 7             | 29        | 12.61%  |
| AMD Ryzen 9             | 10        | 4.35%   |
| Intel Celeron           | 8         | 3.48%   |
| Intel Core i3           | 6         | 2.61%   |
| Intel Xeon              | 4         | 1.74%   |
| AMD Ryzen 5 PRO         | 3         | 1.3%    |
| Intel Pentium Dual-Core | 2         | 0.87%   |
| Intel Pentium           | 2         | 0.87%   |
| Intel Core 2 Duo        | 2         | 0.87%   |
| AMD FX                  | 2         | 0.87%   |
| Intel Pentium Silver    | 1         | 0.43%   |
| Intel Pentium Gold      | 1         | 0.43%   |
| Intel Core i9           | 1         | 0.43%   |
| AMD Ryzen Embedded      | 1         | 0.43%   |
| AMD Ryzen 7 PRO         | 1         | 0.43%   |
| AMD Ryzen 3 PRO         | 1         | 0.43%   |
| AMD Phenom II X4        | 1         | 0.43%   |
| AMD Athlon II X3        | 1         | 0.43%   |
| AMD Athlon              | 1         | 0.43%   |
| AMD A6                  | 1         | 0.43%   |
| AMD A4                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 84        | 36.52%  |
| 6      | 44        | 19.13%  |
| 8      | 37        | 16.09%  |
| 2      | 36        | 15.65%  |
| 12     | 12        | 5.22%   |
| 16     | 5         | 2.17%   |
| 14     | 4         | 1.74%   |
| 10     | 4         | 1.74%   |
| 24     | 2         | 0.87%   |
| 3      | 2         | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 230       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 183       | 79.57%  |
| 1      | 47        | 20.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 230       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 79.4%   |
| 0x0a50000c | 10        | 4.29%   |
| 0x0a601203 | 4         | 1.72%   |
| 0x0a404102 | 4         | 1.72%   |
| 0x08608103 | 4         | 1.72%   |
| 0x0a20120a | 3         | 1.29%   |
| 0x08701021 | 3         | 1.29%   |
| 0x08600104 | 3         | 1.29%   |
| 0x0a404101 | 2         | 0.86%   |
| 0x08108109 | 2         | 0.86%   |
| 0x906a3    | 1         | 0.43%   |
| 0x90672    | 1         | 0.43%   |
| 0x0a50000d | 1         | 0.43%   |
| 0x0a201025 | 1         | 0.43%   |
| 0x08701030 | 1         | 0.43%   |
| 0x08600106 | 1         | 0.43%   |
| 0x08108102 | 1         | 0.43%   |
| 0x0810100b | 1         | 0.43%   |
| 0x0800820d | 1         | 0.43%   |
| 0x08001138 | 1         | 0.43%   |
| 0x0700010f | 1         | 0.43%   |
| 0x06000852 | 1         | 0.43%   |
| 0x03000027 | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 38        | 16.52%  |
| KabyLake         | 34        | 14.78%  |
| Zen 3            | 28        | 12.17%  |
| Zen 2            | 14        | 6.09%   |
| Haswell          | 14        | 6.09%   |
| Alderlake Hybrid | 13        | 5.65%   |
| Skylake          | 12        | 5.22%   |
| Zen+             | 11        | 4.78%   |
| TigerLake        | 11        | 4.78%   |
| SandyBridge      | 11        | 4.78%   |
| IvyBridge        | 9         | 3.91%   |
| CometLake        | 5         | 2.17%   |
| Zen              | 4         | 1.74%   |
| Nehalem          | 4         | 1.74%   |
| Penryn           | 3         | 1.3%    |
| Icelake          | 3         | 1.3%    |
| Broadwell        | 3         | 1.3%    |
| Westmere         | 2         | 0.87%   |
| Piledriver       | 2         | 0.87%   |
| K10              | 2         | 0.87%   |
| Tremont          | 1         | 0.43%   |
| Puma             | 1         | 0.43%   |
| K10 Llano        | 1         | 0.43%   |
| Jaguar           | 1         | 0.43%   |
| Goldmont plus    | 1         | 0.43%   |
| Goldmont         | 1         | 0.43%   |
| Core             | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 118       | 41.26%  |
| AMD    | 91        | 31.82%  |
| Nvidia | 77        | 26.92%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 11        | 3.82%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 10        | 3.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 9         | 3.13%   |
| AMD Lucienne                                                                  | 9         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8         | 2.78%   |
| AMD Renoir                                                                    | 8         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 8         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 2.43%   |
| AMD Rembrandt [Radeon 680M]                                                   | 7         | 2.43%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 7         | 2.43%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 7         | 2.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 2.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 1.74%   |
| Intel HD Graphics 620                                                         | 5         | 1.74%   |
| Intel HD Graphics 530                                                         | 5         | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 1.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.39%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 1.39%   |
| Intel JasperLake [UHD Graphics]                                               | 4         | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.39%   |
| AMD Raphael                                                                   | 4         | 1.39%   |
| AMD Barcelo                                                                   | 4         | 1.39%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 3         | 1.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 1.04%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                | 3         | 1.04%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 3         | 1.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 3         | 1.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.04%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 3         | 1.04%   |
| Intel HD Graphics 630                                                         | 3         | 1.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2         | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2         | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.69%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 0.69%   |
| Intel UHD Graphics 620                                                        | 2         | 0.69%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 74        | 32.17%  |
| 1 x AMD         | 69        | 30%     |
| Intel + Nvidia  | 33        | 14.35%  |
| 1 x Nvidia      | 30        | 13.04%  |
| AMD + Nvidia    | 13        | 5.65%   |
| Intel + AMD     | 6         | 2.61%   |
| 2 x AMD         | 2         | 0.87%   |
| Other           | 1         | 0.43%   |
| 2 x Intel       | 1         | 0.43%   |
| Intel + 2 x AMD | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 169       | 72.84%  |
| Proprietary | 61        | 26.29%  |
| Unknown     | 2         | 0.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 65.09%  |
| 3.01-4.0   | 19        | 8.19%   |
| 0.01-0.5   | 17        | 7.33%   |
| 1.01-2.0   | 15        | 6.47%   |
| 7.01-8.0   | 12        | 5.17%   |
| 8.01-16.0  | 7         | 3.02%   |
| 0.51-1.0   | 4         | 1.72%   |
| 5.01-6.0   | 3         | 1.29%   |
| 2.01-3.0   | 2         | 0.86%   |
| 16.01-24.0 | 2         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 35        | 12.82%  |
| BOE                     | 31        | 11.36%  |
| AU Optronics            | 30        | 10.99%  |
| Dell                    | 19        | 6.96%   |
| Chimei Innolux          | 17        | 6.23%   |
| LG Display              | 16        | 5.86%   |
| Goldstar                | 13        | 4.76%   |
| Philips                 | 9         | 3.3%    |
| Iiyama                  | 9         | 3.3%    |
| AOC                     | 9         | 3.3%    |
| Hewlett-Packard         | 8         | 2.93%   |
| Acer                    | 8         | 2.93%   |
| ASUSTek Computer        | 7         | 2.56%   |
| Apple                   | 6         | 2.2%    |
| Ancor Communications    | 6         | 2.2%    |
| Sharp                   | 5         | 1.83%   |
| PANDA                   | 5         | 1.83%   |
| Lenovo                  | 5         | 1.83%   |
| InfoVision              | 4         | 1.47%   |
| Gigabyte Technology     | 3         | 1.1%    |
| BenQ                    | 3         | 1.1%    |
| SAC                     | 2         | 0.73%   |
| Eizo                    | 2         | 0.73%   |
| Chi Mei Optoelectronics | 2         | 0.73%   |
| Wacom                   | 1         | 0.37%   |
| VIZ                     | 1         | 0.37%   |
| UGD                     | 1         | 0.37%   |
| STA                     | 1         | 0.37%   |
| Sceptre Tech            | 1         | 0.37%   |
| RTK                     | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| ONN                     | 1         | 0.37%   |
| NEC Computers           | 1         | 0.37%   |
| MSI                     | 1         | 0.37%   |
| Medion Akoya            | 1         | 0.37%   |
| LOE                     | 1         | 0.37%   |
| KDC                     | 1         | 0.37%   |
| KDB                     | 1         | 0.37%   |
| INS                     | 1         | 0.37%   |
| GDH                     | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 3         | 1.05%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 1.05%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 3         | 1.05%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.7%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2         | 0.7%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2         | 0.7%    |
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                 | 2         | 0.7%    |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                  | 2         | 0.7%    |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 2         | 0.7%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.7%    |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.7%    |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                 | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch        | 2         | 0.7%    |
| Ancor Communications MX259 ACI25C2 1920x1080 553x309mm 24.9-inch      | 2         | 0.7%    |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1         | 0.35%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                    | 1         | 0.35%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1         | 0.35%   |
| STA SEMP LEDTV STA0030 1920x540                                       | 1         | 0.35%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.35%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.35%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch        | 1         | 0.35%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 0.35%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch     | 1         | 0.35%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.35%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                      | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0498 1600x900 443x249mm 20.0-inch   | 1         | 0.35%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch    | 1         | 0.35%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 477x268mm 21.5-inch    | 1         | 0.35%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 521x293mm 23.5-inch     | 1         | 0.35%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch     | 1         | 0.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.35%   |
| Samsung Electronics Odyssey G8 SAM7231 3440x1440 809x354mm 34.8-inch  | 1         | 0.35%   |
| Samsung Electronics LF24T35 SAM707E 1920x1080 528x297mm 23.9-inch     | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 127       | 48.66%  |
| 3840x2160 (4K)     | 28        | 10.73%  |
| 1366x768 (WXGA)    | 28        | 10.73%  |
| 2560x1440 (QHD)    | 22        | 8.43%   |
| 1920x1200 (WUXGA)  | 7         | 2.68%   |
| 1600x900 (HD+)     | 7         | 2.68%   |
| 2560x1080          | 6         | 2.3%    |
| 3440x1440          | 5         | 1.92%   |
| 1440x900 (WXGA+)   | 5         | 1.92%   |
| 2560x1600          | 4         | 1.53%   |
| 2880x1800          | 3         | 1.15%   |
| 3840x2400          | 2         | 0.77%   |
| 2240x1400          | 2         | 0.77%   |
| 1920x540           | 2         | 0.77%   |
| 1280x800 (WXGA)    | 2         | 0.77%   |
| 3840x1100          | 1         | 0.38%   |
| 3456x2160          | 1         | 0.38%   |
| 3072x1920          | 1         | 0.38%   |
| 2736x1824          | 1         | 0.38%   |
| 2256x1504          | 1         | 0.38%   |
| 2160x1440          | 1         | 0.38%   |
| 1920x1280          | 1         | 0.38%   |
| 1680x1050 (WSXGA+) | 1         | 0.38%   |
| 1360x768           | 1         | 0.38%   |
| 1280x720 (HD)      | 1         | 0.38%   |
| 1280x1024 (SXGA)   | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57        | 20.65%  |
| 27      | 33        | 11.96%  |
| 24      | 30        | 10.87%  |
| 14      | 25        | 9.06%   |
| 13      | 21        | 7.61%   |
| 17      | 19        | 6.88%   |
| 23      | 14        | 5.07%   |
| 21      | 14        | 5.07%   |
| 31      | 13        | 4.71%   |
| 34      | 10        | 3.62%   |
| 19      | 9         | 3.26%   |
| 16      | 7         | 2.54%   |
| 11      | 5         | 1.81%   |
| 18      | 3         | 1.09%   |
| 20      | 2         | 0.72%   |
| 12      | 2         | 0.72%   |
| Unknown | 2         | 0.72%   |
| 72      | 1         | 0.36%   |
| 69      | 1         | 0.36%   |
| 65      | 1         | 0.36%   |
| 54      | 1         | 0.36%   |
| 52      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 37      | 1         | 0.36%   |
| 33      | 1         | 0.36%   |
| 25      | 1         | 0.36%   |
| 22      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 35.82%  |
| 501-600     | 71        | 26.49%  |
| 401-500     | 26        | 9.7%    |
| 351-400     | 21        | 7.84%   |
| 201-300     | 18        | 6.72%   |
| 601-700     | 16        | 5.97%   |
| 701-800     | 10        | 3.73%   |
| 801-900     | 3         | 1.12%   |
| 1001-1500   | 3         | 1.12%   |
| 1501-2000   | 2         | 0.75%   |
| Unknown     | 2         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 193       | 80.08%  |
| 16/10   | 31        | 12.86%  |
| 21/9    | 10        | 4.15%   |
| 3/2     | 4         | 1.66%   |
| 5/4     | 1         | 0.41%   |
| 3.40    | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 20.8%   |
| 201-250        | 44        | 16.06%  |
| 81-90          | 35        | 12.77%  |
| 301-350        | 33        | 12.04%  |
| 351-500        | 24        | 8.76%   |
| 121-130        | 19        | 6.93%   |
| 251-300        | 13        | 4.74%   |
| 151-200        | 12        | 4.38%   |
| 71-80          | 8         | 2.92%   |
| 111-120        | 7         | 2.55%   |
| 51-60          | 6         | 2.19%   |
| More than 1000 | 5         | 1.82%   |
| 141-150        | 3         | 1.09%   |
| 61-70          | 2         | 0.73%   |
| 501-1000       | 2         | 0.73%   |
| 91-100         | 2         | 0.73%   |
| Unknown        | 2         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 84        | 32.43%  |
| 51-100        | 83        | 32.05%  |
| 101-120       | 49        | 18.92%  |
| 161-240       | 25        | 9.65%   |
| More than 240 | 12        | 4.63%   |
| 1-50          | 4         | 1.54%   |
| Unknown       | 2         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 171       | 74.03%  |
| 2     | 51        | 22.08%  |
| 3     | 6         | 2.6%    |
| 0     | 2         | 0.87%   |
| 4     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 135       | 38.79%  |
| Intel                 | 108       | 31.03%  |
| MediaTek              | 27        | 7.76%   |
| Qualcomm Atheros      | 17        | 4.89%   |
| Broadcom              | 15        | 4.31%   |
| TP-Link               | 6         | 1.72%   |
| Ralink                | 6         | 1.72%   |
| ASIX Electronics      | 5         | 1.44%   |
| Hewlett-Packard       | 3         | 0.86%   |
| Broadcom Limited      | 3         | 0.86%   |
| ASUSTek Computer      | 3         | 0.86%   |
| Samsung Electronics   | 2         | 0.57%   |
| Microsoft             | 2         | 0.57%   |
| Google                | 2         | 0.57%   |
| ZyXEL Communications  | 1         | 0.29%   |
| Xiaomi                | 1         | 0.29%   |
| U-Blox                | 1         | 0.29%   |
| Texas Instruments     | 1         | 0.29%   |
| Qualcomm              | 1         | 0.29%   |
| QinHeng Electronics   | 1         | 0.29%   |
| Nvidia                | 1         | 0.29%   |
| NetGear               | 1         | 0.29%   |
| Linksys               | 1         | 0.29%   |
| Lenovo                | 1         | 0.29%   |
| Huawei Technologies   | 1         | 0.29%   |
| Dell                  | 1         | 0.29%   |
| Arduino SA            | 1         | 0.29%   |
| Aquantia              | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 20.05%  |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 4.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 2.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 2.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 10        | 2.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 2.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 9         | 2.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 6         | 1.5%    |
| Intel Wireless 8265 / 8275                                        | 6         | 1.5%    |
| Intel Wireless 7265                                               | 6         | 1.5%    |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.5%    |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.5%    |
| Intel Ethernet Controller I225-V                                  | 6         | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5         | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1%      |
| Intel Wireless 8260                                               | 3         | 0.75%   |
| Intel Wireless 7260                                               | 3         | 0.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 3         | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.5%    |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.5%    |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 85        | 43.81%  |
| Realtek Semiconductor | 32        | 16.49%  |
| MediaTek              | 26        | 13.4%   |
| Qualcomm Atheros      | 16        | 8.25%   |
| Broadcom              | 11        | 5.67%   |
| TP-Link               | 6         | 3.09%   |
| Ralink                | 6         | 3.09%   |
| ASUSTek Computer      | 3         | 1.55%   |
| Microsoft             | 2         | 1.03%   |
| ZyXEL Communications  | 1         | 0.52%   |
| Qualcomm              | 1         | 0.52%   |
| NetGear               | 1         | 0.52%   |
| Linksys               | 1         | 0.52%   |
| Hewlett-Packard       | 1         | 0.52%   |
| Dell                  | 1         | 0.52%   |
| Broadcom Limited      | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 5.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 10        | 5.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 9         | 4.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 8         | 4.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 3.08%   |
| Intel Wireless 8265 / 8275                                     | 6         | 3.08%   |
| Intel Wireless 7265                                            | 6         | 3.08%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 3.08%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 2.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 2.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.05%   |
| Intel Wireless 8260                                            | 3         | 1.54%   |
| Intel Wireless 7260                                            | 3         | 1.54%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 3         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.54%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 1.03%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 1.03%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 2         | 1.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.03%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 2         | 1.03%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 1.03%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 2         | 1.03%   |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                  | 1         | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.51%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 1         | 0.51%   |
| TP-Link 802.11n NIC                                            | 1         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 120       | 61.22%  |
| Intel                 | 47        | 23.98%  |
| Broadcom              | 8         | 4.08%   |
| ASIX Electronics      | 5         | 2.55%   |
| Qualcomm Atheros      | 4         | 2.04%   |
| Samsung Electronics   | 2         | 1.02%   |
| Google                | 2         | 1.02%   |
| Broadcom Limited      | 2         | 1.02%   |
| Xiaomi                | 1         | 0.51%   |
| Nvidia                | 1         | 0.51%   |
| MediaTek              | 1         | 0.51%   |
| Lenovo                | 1         | 0.51%   |
| Huawei Technologies   | 1         | 0.51%   |
| Aquantia              | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 40.4%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 8.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 7         | 3.54%   |
| Intel Ethernet Controller I225-V                                  | 6         | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 2.53%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.01%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.01%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.51%   |
| MediaTek moto g22                                                 | 1         | 0.51%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.51%   |
| Intel Ethernet Controller I219-LM                                 | 1         | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.51%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 0.51%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.51%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.51%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.51%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.51%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.51%   |
| Huawei MLA-L11                                                    | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 186       | 49.73%  |
| Ethernet | 182       | 48.66%  |
| Modem    | 6         | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 59.59%  |
| Ethernet | 99        | 40.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 115       | 50%     |
| 2     | 113       | 49.13%  |
| 5     | 1         | 0.43%   |
| 3     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 157       | 67.38%  |
| Yes  | 76        | 32.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 47.93%  |
| Realtek Semiconductor           | 24        | 14.2%   |
| Cambridge Silicon Radio         | 10        | 5.92%   |
| Foxconn / Hon Hai               | 8         | 4.73%   |
| Qualcomm Atheros Communications | 7         | 4.14%   |
| MediaTek                        | 7         | 4.14%   |
| IMC Networks                    | 7         | 4.14%   |
| Apple                           | 7         | 4.14%   |
| Lite-On Technology              | 5         | 2.96%   |
| Broadcom                        | 4         | 2.37%   |
| Realtek                         | 3         | 1.78%   |
| TP-Link                         | 2         | 1.18%   |
| Toshiba                         | 1         | 0.59%   |
| Ralink                          | 1         | 0.59%   |
| Dell                            | 1         | 0.59%   |
| ASUSTek Computer                | 1         | 0.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 21        | 12.43%  |
| Intel Bluetooth wireless interface                  | 21        | 12.43%  |
| Intel Bluetooth Device                              | 18        | 10.65%  |
| Intel AX201 Bluetooth                               | 17        | 10.06%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 5.92%   |
| Intel AX210 Bluetooth                               | 9         | 5.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 4.73%   |
| MediaTek Wireless_Device                            | 7         | 4.14%   |
| Intel AX200 Bluetooth                               | 6         | 3.55%   |
| IMC Networks Wireless_Device                        | 5         | 2.96%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 2.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.78%   |
| Lite-On Wireless_Device                             | 3         | 1.78%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 1.78%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.78%   |
| TP-Link UB5A Adapter                                | 2         | 1.18%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.18%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.59%   |
| Realtek Bluetooth Radio                             | 1         | 0.59%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.59%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.59%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.59%   |
| IMC Networks BCM20702A0                             | 1         | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.59%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.59%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.59%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.59%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.59%   |
| Broadcom BCM20702A0                                 | 1         | 0.59%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.59%   |
| Apple Bluetooth Host Controller                     | 1         | 0.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 144       | 40.91%  |
| AMD                          | 101       | 28.69%  |
| Nvidia                       | 60        | 17.05%  |
| C-Media Electronics          | 9         | 2.56%   |
| Focusrite-Novation           | 4         | 1.14%   |
| Realtek Semiconductor        | 3         | 0.85%   |
| Logitech                     | 3         | 0.85%   |
| Texas Instruments            | 2         | 0.57%   |
| SteelSeries ApS              | 2         | 0.57%   |
| SAVITECH                     | 2         | 0.57%   |
| Hewlett-Packard              | 2         | 0.57%   |
| Corsair                      | 2         | 0.57%   |
| Trust                        | 1         | 0.28%   |
| TEAC                         | 1         | 0.28%   |
| Nordic Semiconductor ASA     | 1         | 0.28%   |
| Micro Star International     | 1         | 0.28%   |
| Mackie Designs               | 1         | 0.28%   |
| M-Audio                      | 1         | 0.28%   |
| Lenovo                       | 1         | 0.28%   |
| JMTek                        | 1         | 0.28%   |
| GN Netcom                    | 1         | 0.28%   |
| Generalplus Technology       | 1         | 0.28%   |
| Dell                         | 1         | 0.28%   |
| D&M Holdings (Denon/Marantz) | 1         | 0.28%   |
| Creative Technology          | 1         | 0.28%   |
| Creative Labs                | 1         | 0.28%   |
| AudioQuest                   | 1         | 0.28%   |
| ASUSTek Computer             | 1         | 0.28%   |
| Asahi Kasei Microsystems     | 1         | 0.28%   |
| 2.4G Composite Device        | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 54        | 12.59%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 30        | 6.99%   |
| AMD Starship/Matisse HD Audio Controller                                   | 16        | 3.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 2.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 2.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 2.1%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 1.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.63%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.4%    |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.4%    |
| Nvidia Audio device                                                        | 6         | 1.4%    |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 1.17%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.93%   |
| Intel Jasper Lake HD Audio                                                 | 4         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 0.93%   |
| Realtek Semiconductor USB Audio                                            | 3         | 0.7%    |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.7%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 3         | 0.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.7%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.7%    |
| AMD FCH Azalia Controller                                                  | 3         | 0.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 23.19%  |
| Micron Technology   | 24        | 17.39%  |
| SK hynix            | 21        | 15.22%  |
| Kingston            | 11        | 7.97%   |
| Crucial             | 9         | 6.52%   |
| Corsair             | 9         | 6.52%   |
| G.Skill             | 7         | 5.07%   |
| Unknown             | 4         | 2.9%    |
| A-DATA Technology   | 4         | 2.9%    |
| Ramaxel Technology  | 3         | 2.17%   |
| Unknown             | 3         | 2.17%   |
| Team                | 2         | 1.45%   |
| Unknown (ABCD)      | 1         | 0.72%   |
| Transcend           | 1         | 0.72%   |
| Timetec             | 1         | 0.72%   |
| Patriot             | 1         | 0.72%   |
| Nanya Technology    | 1         | 0.72%   |
| Micron/Elpida       | 1         | 0.72%   |
| GOODRAM             | 1         | 0.72%   |
| Atermiter           | 1         | 0.72%   |
| 4ea5                | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 2.07%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.07%   |
| Unknown                                                          | 3         | 2.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.38%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 1.38%   |
| Unknown RAM Module 8GB DIMM 667MT/s                              | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM 800MT/s                            | 1         | 0.69%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 0.69%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 0.69%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 0.69%   |
| Timetec RAM S16G-3200 16GB SODIMM DDR4 2133MT/s                  | 1         | 0.69%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.69%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s            | 1         | 0.69%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.69%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.69%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.69%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.69%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 1         | 0.69%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 1         | 0.69%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.69%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.69%   |
| SK hynix RAM HMA81GU7MFR8N-TF 8GB DIMM DDR4 2133MT/s             | 1         | 0.69%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2667MT/s             | 1         | 0.69%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.69%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.69%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 0.69%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.69%   |
| SK hynix RAM H58G66AK6BX070 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 0.69%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.69%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.69%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 0.69%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.69%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.69%   |
| Samsung RAM M471B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 1         | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 63        | 51.64%  |
| DDR3    | 22        | 18.03%  |
| LPDDR4  | 11        | 9.02%   |
| LPDDR5  | 10        | 8.2%    |
| DDR5    | 10        | 8.2%    |
| LPDDR3  | 4         | 3.28%   |
| Unknown | 2         | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 47.58%  |
| DIMM         | 36        | 29.03%  |
| Row Of Chips | 28        | 22.58%  |
| Unknown      | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 57        | 43.18%  |
| 4096  | 32        | 24.24%  |
| 16384 | 26        | 19.7%   |
| 32768 | 9         | 6.82%   |
| 2048  | 7         | 5.3%    |
| 12288 | 1         | 0.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 35        | 27.13%  |
| 6400  | 11        | 8.53%   |
| 2667  | 11        | 8.53%   |
| 1600  | 10        | 7.75%   |
| 4800  | 8         | 6.2%    |
| 2400  | 7         | 5.43%   |
| 2133  | 7         | 5.43%   |
| 4267  | 6         | 4.65%   |
| 3600  | 6         | 4.65%   |
| 1333  | 5         | 3.88%   |
| 3733  | 4         | 3.1%    |
| 3266  | 3         | 2.33%   |
| 1800  | 3         | 2.33%   |
| 2933  | 2         | 1.55%   |
| 1867  | 2         | 1.55%   |
| 8400  | 1         | 0.78%   |
| 5600  | 1         | 0.78%   |
| 3666  | 1         | 0.78%   |
| 3334  | 1         | 0.78%   |
| 2473  | 1         | 0.78%   |
| 1334  | 1         | 0.78%   |
| 1067  | 1         | 0.78%   |
| 800   | 1         | 0.78%   |
| 667   | 1         | 0.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 33.33%  |
| Canon              | 2         | 33.33%  |
| Brother Industries | 2         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-7100 Series | 1         | 16.67%  |
| Seiko Epson XP-2200 Series | 1         | 16.67%  |
| Canon PIXMA MX490 Series   | 1         | 16.67%  |
| Canon LBP6020              | 1         | 16.67%  |
| Brother HL-L2310D series   | 1         | 16.67%  |
| Brother HL-3142CW series   | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 17.61%  |
| IMC Networks                           | 12        | 8.45%   |
| Realtek Semiconductor                  | 11        | 7.75%   |
| Quanta                                 | 11        | 7.75%   |
| Microdia                               | 10        | 7.04%   |
| Bison Electronics                      | 9         | 6.34%   |
| Sunplus Innovation Technology          | 8         | 5.63%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 5.63%   |
| Apple                                  | 8         | 5.63%   |
| Syntek                                 | 7         | 4.93%   |
| Logitech                               | 7         | 4.93%   |
| Luxvisions Innotech Limited            | 6         | 4.23%   |
| SunplusIT                              | 2         | 1.41%   |
| Samsung Electronics                    | 2         | 1.41%   |
| Alcor Micro                            | 2         | 1.41%   |
| Suyin                                  | 1         | 0.7%    |
| Sonix Technology                       | 1         | 0.7%    |
| SN0002                                 | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.7%    |
| Primax Electronics                     | 1         | 0.7%    |
| OYT Tech                               | 1         | 0.7%    |
| OPPO Electronics                       | 1         | 0.7%    |
| Lite-On Technology                     | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| Generalplus Technology                 | 1         | 0.7%    |
| GEMBIRD                                | 1         | 0.7%    |
| AVerMedia Technologies                 | 1         | 0.7%    |
| Acer                                   | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 8         | 5.52%   |
| Chicony Integrated Camera                                                  | 8         | 5.52%   |
| Syntek Integrated Camera                                                   | 6         | 4.14%   |
| Realtek HP Truevision HD                                                   | 4         | 2.76%   |
| Bison Integrated Camera                                                    | 4         | 2.76%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 2.07%   |
| Quanta HD User Facing                                                      | 3         | 2.07%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.07%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 2.07%   |
| Apple FaceTime HD Camera                                                   | 3         | 2.07%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 1.38%   |
| Quanta USB2.0 HD UVC WebCam                                                | 2         | 1.38%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 2         | 1.38%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 1.38%   |
| Logitech HD Webcam C615                                                    | 2         | 1.38%   |
| Logitech HD Pro Webcam C920                                                | 2         | 1.38%   |
| Chicony HP TrueVision HD                                                   | 2         | 1.38%   |
| Chicony HD WebCam                                                          | 2         | 1.38%   |
| Chicony 720p HD Camera                                                     | 2         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 2         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 1.38%   |
| Bison Integrated RGB Camera                                                | 2         | 1.38%   |
| Bison HD Webcam                                                            | 2         | 1.38%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 2         | 1.38%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 1.38%   |
| Apple Built-in iSight                                                      | 2         | 1.38%   |
| Alcor Micro USB 2.0 PC cam                                                 | 2         | 1.38%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.69%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.69%   |
| SunplusIT USB Camera                                                       | 1         | 0.69%   |
| SunplusIT 1080p FHD Camera                                                 | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 0.69%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.69%   |
| Sunplus FHD Camera Microphone                                              | 1         | 0.69%   |
| Sunplus 1080p FHD Camera                                                   | 1         | 0.69%   |
| Sunplus 1.3M HD WebCam                                                     | 1         | 0.69%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.69%   |
| SN0002 HIK 1080P USB CAMERA                                                | 1         | 0.69%   |
| Silicon Motion HP Webcam-101                                               | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 11        | 42.31%  |
| Validity Sensors                   | 7         | 26.92%  |
| Shenzhen Goodix Technology         | 6         | 23.08%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 3.85%   |
| Elan Microelectronics              | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 4         | 15.38%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 3         | 11.54%  |
| Synaptics UWP WBDI                                              | 3         | 11.54%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 11.54%  |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 3.85%   |
| Synaptics WBDI                                                  | 1         | 3.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 3.85%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 3.85%   |
| Elan ELAN:ARM-M4                                                | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Broadcom     | 4         | 44.44%  |
| Alcor Micro  | 2         | 22.22%  |
| O2 Micro     | 1         | 11.11%  |
| Lenovo       | 1         | 11.11%  |
| Aladdin R.D. | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader            | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 11.11%  |
| Broadcom 5880                                  | 1         | 11.11%  |
| Aladdin R.D. JaCarta                           | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 161       | 70%     |
| 1     | 59        | 25.65%  |
| 2     | 9         | 3.91%   |
| 3     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 34.21%  |
| Graphics card            | 9         | 11.84%  |
| Net/wireless             | 8         | 10.53%  |
| Multimedia controller    | 8         | 10.53%  |
| Chipcard                 | 8         | 10.53%  |
| Camera                   | 8         | 10.53%  |
| Unassigned class         | 2         | 2.63%   |
| Sound                    | 2         | 2.63%   |
| Communication controller | 2         | 2.63%   |
| Storage                  | 1         | 1.32%   |
| Card reader              | 1         | 1.32%   |
| Bluetooth                | 1         | 1.32%   |

