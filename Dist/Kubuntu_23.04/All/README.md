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

Total: 348

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0X8DXD A00                  | Desktop     | [a44e0088f6](https://linux-hardware.org/?probe=a44e0088f6) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1330485afc](https://linux-hardware.org/?probe=1330485afc) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [4a47d466d9](https://linux-hardware.org/?probe=4a47d466d9) | Sep 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [c9aca83f04](https://linux-hardware.org/?probe=c9aca83f04) | Sep 30, 2023 |
| HP            | 1790                        | Desktop     | [b87e9dd9ad](https://linux-hardware.org/?probe=b87e9dd9ad) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [89791e7bf0](https://linux-hardware.org/?probe=89791e7bf0) | Sep 29, 2023 |
| MSI           | H97M-G43                    | Desktop     | [b74346acb3](https://linux-hardware.org/?probe=b74346acb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [76937ddbce](https://linux-hardware.org/?probe=76937ddbce) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [128658b9f0](https://linux-hardware.org/?probe=128658b9f0) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| CHIPHD        | NT125D                      | Notebook    | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [1b72e3fe1c](https://linux-hardware.org/?probe=1b72e3fe1c) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [0281cc244a](https://linux-hardware.org/?probe=0281cc244a) | Sep 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7f88191a7b](https://linux-hardware.org/?probe=7f88191a7b) | Sep 23, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [dc831a82cd](https://linux-hardware.org/?probe=dc831a82cd) | Sep 22, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [d4060b585a](https://linux-hardware.org/?probe=d4060b585a) | Sep 20, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [17e0d2ab92](https://linux-hardware.org/?probe=17e0d2ab92) | Sep 17, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [76d6f570a8](https://linux-hardware.org/?probe=76d6f570a8) | Sep 16, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [a73abd96f1](https://linux-hardware.org/?probe=a73abd96f1) | Sep 15, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [3a1c100a69](https://linux-hardware.org/?probe=3a1c100a69) | Sep 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [20ad52b9a4](https://linux-hardware.org/?probe=20ad52b9a4) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [959fc9f783](https://linux-hardware.org/?probe=959fc9f783) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [641089b224](https://linux-hardware.org/?probe=641089b224) | Sep 13, 2023 |
| AZW           | MINI S 10                   | Desktop     | [5cd0efea8b](https://linux-hardware.org/?probe=5cd0efea8b) | Sep 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [b12897892a](https://linux-hardware.org/?probe=b12897892a) | Sep 09, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [33cc2ca68e](https://linux-hardware.org/?probe=33cc2ca68e) | Sep 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [23da68a72c](https://linux-hardware.org/?probe=23da68a72c) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [5180b1e51e](https://linux-hardware.org/?probe=5180b1e51e) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6f3051262d](https://linux-hardware.org/?probe=6f3051262d) | Sep 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [fe6b08c772](https://linux-hardware.org/?probe=fe6b08c772) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [c0422be924](https://linux-hardware.org/?probe=c0422be924) | Sep 08, 2023 |
| Google        | Robo360                     | Notebook    | [86308cca01](https://linux-hardware.org/?probe=86308cca01) | Sep 07, 2023 |
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


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.2.0-20-generic       | 80        | 28.37%  |
| 6.2.0-27-generic       | 26        | 9.22%   |
| 6.2.0-26-generic       | 25        | 8.87%   |
| 6.2.0-32-generic       | 20        | 7.09%   |
| 6.2.0-24-generic       | 20        | 7.09%   |
| 6.2.0-23-generic       | 17        | 6.03%   |
| 6.2.0-33-generic       | 15        | 5.32%   |
| 6.2.0-25-generic       | 13        | 4.61%   |
| 6.2.0-31-generic       | 6         | 2.13%   |
| 6.2.0-18-generic       | 4         | 1.42%   |
| 6.2.0-1007-lowlatency  | 4         | 1.42%   |
| 6.2.0-1003-lowlatency  | 4         | 1.42%   |
| 6.2.0-1009-lowlatency  | 3         | 1.06%   |
| 6.4.8-060408-generic   | 2         | 0.71%   |
| 6.4.0-060400-generic   | 2         | 0.71%   |
| 6.2.0-1013-lowlatency  | 2         | 0.71%   |
| 6.2.0-1011-lowlatency  | 2         | 0.71%   |
| 6.2.0-1008-lowlatency  | 2         | 0.71%   |
| 6.2.0-1005-lowlatency  | 2         | 0.71%   |
| 5.19.0-42-generic      | 2         | 0.71%   |
| 5.19.0-28-generic      | 2         | 0.71%   |
| 6.5.2                  | 1         | 0.35%   |
| 6.5.1-060501-generic   | 1         | 0.35%   |
| 6.4.9-060409-generic   | 1         | 0.35%   |
| 6.4.6-060406-generic   | 1         | 0.35%   |
| 6.4.3-1-liquorix-amd64 | 1         | 0.35%   |
| 6.4.1-2-liquorix-amd64 | 1         | 0.35%   |
| 6.3.8-x64v3-xanmod1    | 1         | 0.35%   |
| 6.3.8                  | 1         | 0.35%   |
| 6.3.7-060307-generic   | 1         | 0.35%   |
| 6.3.6-custom           | 1         | 0.35%   |
| 6.3.5-060305-generic   | 1         | 0.35%   |
| 6.3.4-060304-generic   | 1         | 0.35%   |
| 6.3.3-060303-generic   | 1         | 0.35%   |
| 6.3.10                 | 1         | 0.35%   |
| 6.3.1-custom           | 1         | 0.35%   |
| 6.3.1-060301-generic   | 1         | 0.35%   |
| 6.2.5-060205-generic   | 1         | 0.35%   |
| 6.2.10-060210-generic  | 1         | 0.35%   |
| 6.2.0-9032-generic     | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 234       | 87.31%  |
| 5.19.0  | 7         | 2.61%   |
| 6.1.0   | 3         | 1.12%   |
| 6.4.8   | 2         | 0.75%   |
| 6.4.0   | 2         | 0.75%   |
| 6.3.8   | 2         | 0.75%   |
| 6.3.1   | 2         | 0.75%   |
| 6.5.2   | 1         | 0.37%   |
| 6.5.1   | 1         | 0.37%   |
| 6.4.9   | 1         | 0.37%   |
| 6.4.6   | 1         | 0.37%   |
| 6.4.3   | 1         | 0.37%   |
| 6.4.1   | 1         | 0.37%   |
| 6.3.7   | 1         | 0.37%   |
| 6.3.6   | 1         | 0.37%   |
| 6.3.5   | 1         | 0.37%   |
| 6.3.4   | 1         | 0.37%   |
| 6.3.3   | 1         | 0.37%   |
| 6.3.10  | 1         | 0.37%   |
| 6.2.5   | 1         | 0.37%   |
| 6.2.10  | 1         | 0.37%   |
| 6.1.12  | 1         | 0.37%   |
| 6.1.11  | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 236       | 88.06%  |
| 6.3     | 10        | 3.73%   |
| 6.4     | 8         | 2.99%   |
| 5.19    | 7         | 2.61%   |
| 6.1     | 5         | 1.87%   |
| 6.5     | 2         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 264       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 253       | 95.83%  |
| KDE   | 8         | 3.03%   |
| GNOME | 2         | 0.76%   |
| LXQt  | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 221       | 83.08%  |
| Wayland | 43        | 16.17%  |
| Tty     | 2         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 163       | 61.51%  |
| Unknown | 91        | 34.34%  |
| GDM3    | 7         | 2.64%   |
| LightDM | 4         | 1.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 128       | 48.48%  |
| de_DE  | 29        | 10.98%  |
| en_GB  | 21        | 7.95%   |
| ru_RU  | 12        | 4.55%   |
| fr_FR  | 12        | 4.55%   |
| pl_PL  | 8         | 3.03%   |
| it_IT  | 8         | 3.03%   |
| pt_BR  | 7         | 2.65%   |
| en_CA  | 4         | 1.52%   |
| es_MX  | 3         | 1.14%   |
| C      | 3         | 1.14%   |
| zh_TW  | 2         | 0.76%   |
| fr_BE  | 2         | 0.76%   |
| es_CR  | 2         | 0.76%   |
| es_CL  | 2         | 0.76%   |
| en_NZ  | 2         | 0.76%   |
| en_IN  | 2         | 0.76%   |
| en_AU  | 2         | 0.76%   |
| zh_HK  | 1         | 0.38%   |
| sv_SE  | 1         | 0.38%   |
| pt_PT  | 1         | 0.38%   |
| nl_NL  | 1         | 0.38%   |
| nb_NO  | 1         | 0.38%   |
| hu_HU  | 1         | 0.38%   |
| es_PE  | 1         | 0.38%   |
| es_ES  | 1         | 0.38%   |
| es_CO  | 1         | 0.38%   |
| es_419 | 1         | 0.38%   |
| en_PH  | 1         | 0.38%   |
| en_IL  | 1         | 0.38%   |
| en_DK  | 1         | 0.38%   |
| de_CH  | 1         | 0.38%   |
| da_DK  | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 139       | 52.26%  |
| EFI  | 127       | 47.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 184       | 69.17%  |
| Tmpfs   | 54        | 20.3%   |
| Btrfs   | 18        | 6.77%   |
| Overlay | 6         | 2.26%   |
| Zfs     | 2         | 0.75%   |
| Xfs     | 1         | 0.38%   |
| F2fs    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 166       | 62.64%  |
| Unknown | 90        | 33.96%  |
| MBR     | 9         | 3.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 237       | 89.1%   |
| Yes       | 29        | 10.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 190       | 71.97%  |
| Yes       | 74        | 28.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 46        | 17.42%  |
| Lenovo                 | 43        | 16.29%  |
| Hewlett-Packard        | 37        | 14.02%  |
| Gigabyte Technology    | 20        | 7.58%   |
| Dell                   | 20        | 7.58%   |
| MSI                    | 19        | 7.2%    |
| Acer                   | 12        | 4.55%   |
| Apple                  | 10        | 3.79%   |
| ASRock                 | 8         | 3.03%   |
| Google                 | 6         | 2.27%   |
| Intel                  | 5         | 1.89%   |
| AZW                    | 5         | 1.89%   |
| HUAWEI                 | 4         | 1.52%   |
| Unknown                | 4         | 1.52%   |
| Samsung Electronics    | 3         | 1.14%   |
| Fujitsu                | 2         | 0.76%   |
| Alienware              | 2         | 0.76%   |
| Valve                  | 1         | 0.38%   |
| TECNO                  | 1         | 0.38%   |
| Seco                   | 1         | 0.38%   |
| Pegatron               | 1         | 0.38%   |
| Medion                 | 1         | 0.38%   |
| Huanan                 | 1         | 0.38%   |
| HPE                    | 1         | 0.38%   |
| GPU Company            | 1         | 0.38%   |
| GPD                    | 1         | 0.38%   |
| Gateway                | 1         | 0.38%   |
| Framework              | 1         | 0.38%   |
| Foxconn                | 1         | 0.38%   |
| CHIPHD                 | 1         | 0.38%   |
| BOSGAME                | 1         | 0.38%   |
| Biostar                | 1         | 0.38%   |
| BESSTAR Tech           | 1         | 0.38%   |
| Avell High Performance | 1         | 0.38%   |
| AMI                    | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AZW SER                                     | 4         | 1.52%   |
| Unknown                                     | 4         | 1.52%   |
| MSI MS-7D75                                 | 2         | 0.76%   |
| MSI MS-7C95                                 | 2         | 0.76%   |
| MSI MS-7C56                                 | 2         | 0.76%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW | 2         | 0.76%   |
| Intel NUC12WSHi7                            | 2         | 0.76%   |
| HP ProBook 650 G1                           | 2         | 0.76%   |
| HP ENVY x360 Convertible 13-ay0xxx          | 2         | 0.76%   |
| Gigabyte B550 AORUS ELITE V2                | 2         | 0.76%   |
| Dell Latitude E5470                         | 2         | 0.76%   |
| Dell G3 3779                                | 2         | 0.76%   |
| ASUS TUF Gaming B550-PLUS                   | 2         | 0.76%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI    | 2         | 0.76%   |
| Apple iMac11,1                              | 2         | 0.76%   |
| Valve Jupiter                               | 1         | 0.38%   |
| TECNO MEGABOOK T1                           | 1         | 0.38%   |
| Seco C40                                    | 1         | 0.38%   |
| Samsung 950XED                              | 1         | 0.38%   |
| Samsung 950QED                              | 1         | 0.38%   |
| Samsung 950QDB                              | 1         | 0.38%   |
| Pegatron 520-1000nl                         | 1         | 0.38%   |
| MSI Titan GT77HX 13VH                       | 1         | 0.38%   |
| MSI Raider GE67HX 12UGS                     | 1         | 0.38%   |
| MSI MS-7D74                                 | 1         | 0.38%   |
| MSI MS-7D17                                 | 1         | 0.38%   |
| MSI MS-7B86                                 | 1         | 0.38%   |
| MSI MS-7B24                                 | 1         | 0.38%   |
| MSI MS-7B23                                 | 1         | 0.38%   |
| MSI MS-7A32                                 | 1         | 0.38%   |
| MSI MS-7924                                 | 1         | 0.38%   |
| MSI MS-7846                                 | 1         | 0.38%   |
| MSI MS-7693                                 | 1         | 0.38%   |
| MSI GE75 Raider 9SE                         | 1         | 0.38%   |
| MSI Bravo 17 A4DDK                          | 1         | 0.38%   |
| Medion E11201                               | 1         | 0.38%   |
| Lenovo Yoga Slim 7 Pro 16ACH6 82QQ          | 1         | 0.38%   |
| Lenovo Yoga C640-13IML 81UE                 | 1         | 0.38%   |
| Lenovo Yoga 6 13ALC7 82UD                   | 1         | 0.38%   |
| Lenovo ThinkPad X270 W10DG 20K5S4K200       | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 18        | 6.82%   |
| Lenovo IdeaPad    | 13        | 4.92%   |
| ASUS PRIME        | 12        | 4.55%   |
| ASUS ROG          | 10        | 3.79%   |
| Acer Aspire       | 8         | 3.03%   |
| HP EliteBook      | 7         | 2.65%   |
| Dell Latitude     | 7         | 2.65%   |
| HP ENVY           | 6         | 2.27%   |
| HP Pavilion       | 5         | 1.89%   |
| Dell Precision    | 5         | 1.89%   |
| Gigabyte B550     | 4         | 1.52%   |
| AZW SER           | 4         | 1.52%   |
| ASUS VivoBook     | 4         | 1.52%   |
| ASUS ASUS         | 4         | 1.52%   |
| Unknown           | 4         | 1.52%   |
| Lenovo Yoga       | 3         | 1.14%   |
| Lenovo Legion     | 3         | 1.14%   |
| HP ProBook        | 3         | 1.14%   |
| HP Laptop         | 3         | 1.14%   |
| Dell XPS          | 3         | 1.14%   |
| ASUS TUF          | 3         | 1.14%   |
| MSI MS-7D75       | 2         | 0.76%   |
| MSI MS-7C95       | 2         | 0.76%   |
| MSI MS-7C56       | 2         | 0.76%   |
| Lenovo IdeaCentre | 2         | 0.76%   |
| Intel NUC12WSHi7  | 2         | 0.76%   |
| HP ZBook          | 2         | 0.76%   |
| HP Compaq         | 2         | 0.76%   |
| Gigabyte X570S    | 2         | 0.76%   |
| Gigabyte G5       | 2         | 0.76%   |
| Gigabyte B365M    | 2         | 0.76%   |
| Dell Inspiron     | 2         | 0.76%   |
| Dell G3           | 2         | 0.76%   |
| ASUS Zenbook      | 2         | 0.76%   |
| ASUS Maximus      | 2         | 0.76%   |
| Apple MacBookPro9 | 2         | 0.76%   |
| Apple iMac11      | 2         | 0.76%   |
| Acer Nitro        | 2         | 0.76%   |
| Valve Jupiter     | 1         | 0.38%   |
| TECNO MEGABOOK    | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 45        | 17.05%  |
| 2021 | 39        | 14.77%  |
| 2019 | 31        | 11.74%  |
| 2020 | 30        | 11.36%  |
| 2018 | 18        | 6.82%   |
| 2023 | 14        | 5.3%    |
| 2012 | 14        | 5.3%    |
| 2017 | 12        | 4.55%   |
| 2011 | 12        | 4.55%   |
| 2014 | 11        | 4.17%   |
| 2015 | 10        | 3.79%   |
| 2013 | 9         | 3.41%   |
| 2016 | 8         | 3.03%   |
| 2010 | 6         | 2.27%   |
| 2009 | 4         | 1.52%   |
| 2007 | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 139       | 52.65%  |
| Desktop     | 94        | 35.61%  |
| Convertible | 15        | 5.68%   |
| Mini pc     | 8         | 3.03%   |
| All in one  | 5         | 1.89%   |
| Tablet      | 2         | 0.76%   |
| Server      | 1         | 0.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 249       | 94.32%  |
| Enabled  | 15        | 5.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 258       | 97.73%  |
| Yes  | 6         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 62        | 23.4%   |
| 8.01-16.0   | 59        | 22.26%  |
| 4.01-8.0    | 50        | 18.87%  |
| 32.01-64.0  | 46        | 17.36%  |
| 3.01-4.0    | 21        | 7.92%   |
| 64.01-256.0 | 15        | 5.66%   |
| 24.01-32.0  | 11        | 4.15%   |
| 2.01-3.0    | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 89        | 32.25%  |
| 2.01-3.0   | 70        | 25.36%  |
| 3.01-4.0   | 49        | 17.75%  |
| 1.01-2.0   | 41        | 14.86%  |
| 8.01-16.0  | 22        | 7.97%   |
| 16.01-24.0 | 3         | 1.09%   |
| 32.01-64.0 | 1         | 0.36%   |
| 24.01-32.0 | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 137       | 50.93%  |
| 2      | 74        | 27.51%  |
| 3      | 30        | 11.15%  |
| 4      | 17        | 6.32%   |
| 5      | 5         | 1.86%   |
| 6      | 3         | 1.12%   |
| 7      | 2         | 0.74%   |
| 8      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 210       | 79.25%  |
| Yes       | 55        | 20.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 80%     |
| No        | 53        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 79.17%  |
| No        | 55        | 20.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 72.73%  |
| No        | 72        | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 55        | 20.83%  |
| Germany      | 37        | 14.02%  |
| UK           | 22        | 8.33%   |
| Russia       | 15        | 5.68%   |
| France       | 15        | 5.68%   |
| Poland       | 9         | 3.41%   |
| Brazil       | 9         | 3.41%   |
| Italy        | 8         | 3.03%   |
| Canada       | 8         | 3.03%   |
| Turkey       | 5         | 1.89%   |
| Switzerland  | 5         | 1.89%   |
| Sweden       | 5         | 1.89%   |
| Netherlands  | 5         | 1.89%   |
| Mexico       | 5         | 1.89%   |
| Belgium      | 5         | 1.89%   |
| India        | 4         | 1.52%   |
| Hungary      | 4         | 1.52%   |
| Taiwan       | 3         | 1.14%   |
| Portugal     | 3         | 1.14%   |
| Spain        | 2         | 0.76%   |
| Serbia       | 2         | 0.76%   |
| Saudi Arabia | 2         | 0.76%   |
| Peru         | 2         | 0.76%   |
| New Zealand  | 2         | 0.76%   |
| Kazakhstan   | 2         | 0.76%   |
| Israel       | 2         | 0.76%   |
| Costa Rica   | 2         | 0.76%   |
| Colombia     | 2         | 0.76%   |
| Chile        | 2         | 0.76%   |
| Australia    | 2         | 0.76%   |
| Slovakia     | 1         | 0.38%   |
| Romania      | 1         | 0.38%   |
| Philippines  | 1         | 0.38%   |
| Norway       | 1         | 0.38%   |
| Luxembourg   | 1         | 0.38%   |
| Lithuania    | 1         | 0.38%   |
| Libya        | 1         | 0.38%   |
| Latvia       | 1         | 0.38%   |
| Ivory Coast  | 1         | 0.38%   |
| Indonesia    | 1         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Munich            | 5         | 1.87%   |
| Moscow            | 4         | 1.5%    |
| London            | 4         | 1.5%    |
| Istanbul          | 4         | 1.5%    |
| Berlin            | 4         | 1.5%    |
| Hamburg           | 3         | 1.12%   |
| Warsaw            | 2         | 0.75%   |
| Virginia Beach    | 2         | 0.75%   |
| Vienna            | 2         | 0.75%   |
| Valley Center     | 2         | 0.75%   |
| Sherbrooke        | 2         | 0.75%   |
| Porto Alegre      | 2         | 0.75%   |
| Portimao          | 2         | 0.75%   |
| Paris             | 2         | 0.75%   |
| Oldenburg         | 2         | 0.75%   |
| Oberburg          | 2         | 0.75%   |
| Münster          | 2         | 0.75%   |
| Montevrain        | 2         | 0.75%   |
| Minneapolis       | 2         | 0.75%   |
| Grecia            | 2         | 0.75%   |
| Frankfurt am Main | 2         | 0.75%   |
| Elkridge          | 2         | 0.75%   |
| Brussels          | 2         | 0.75%   |
| Arzamas           | 2         | 0.75%   |
| Abtwil            | 2         | 0.75%   |
| Zuchwil           | 1         | 0.37%   |
| Zhubei            | 1         | 0.37%   |
| Zamora            | 1         | 0.37%   |
| Yerevan           | 1         | 0.37%   |
| Wooster           | 1         | 0.37%   |
| Woodstock         | 1         | 0.37%   |
| Wiesmoor          | 1         | 0.37%   |
| West Valley       | 1         | 0.37%   |
| West Des Moines   | 1         | 0.37%   |
| Weilmuenster      | 1         | 0.37%   |
| Warwick           | 1         | 0.37%   |
| Ware              | 1         | 0.37%   |
| Waldorf           | 1         | 0.37%   |
| Waianae           | 1         | 0.37%   |
| Vsevolozhsk       | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 73        | 101    | 16.63%  |
| WDC                         | 47        | 55     | 10.71%  |
| Seagate                     | 41        | 62     | 9.34%   |
| Sandisk                     | 39        | 45     | 8.88%   |
| Kingston                    | 23        | 28     | 5.24%   |
| Toshiba                     | 22        | 27     | 5.01%   |
| Crucial                     | 20        | 26     | 4.56%   |
| Micron Technology           | 16        | 17     | 3.64%   |
| Intel                       | 14        | 16     | 3.19%   |
| SK hynix                    | 12        | 12     | 2.73%   |
| Phison Electronics          | 9         | 9      | 2.05%   |
| Hitachi                     | 8         | 8      | 1.82%   |
| Unknown                     | 7         | 8      | 1.59%   |
| Silicon Motion              | 7         | 8      | 1.59%   |
| Kingston Technology Company | 6         | 7      | 1.37%   |
| HGST                        | 6         | 7      | 1.37%   |
| A-DATA Technology           | 6         | 7      | 1.37%   |
| Micron/Crucial Technology   | 5         | 7      | 1.14%   |
| KIOXIA                      | 4         | 4      | 0.91%   |
| China                       | 4         | 4      | 0.91%   |
| PNY                         | 3         | 3      | 0.68%   |
| Patriot                     | 3         | 3      | 0.68%   |
| Apple                       | 3         | 3      | 0.68%   |
| Unknown                     | 3         | 3      | 0.68%   |
| UMIS                        | 2         | 3      | 0.46%   |
| Transcend                   | 2         | 2      | 0.46%   |
| Team                        | 2         | 2      | 0.46%   |
| SPCC                        | 2         | 6      | 0.46%   |
| Solid State Storage         | 2         | 2      | 0.46%   |
| Maxtor                      | 2         | 2      | 0.46%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.46%   |
| Lexar                       | 2         | 2      | 0.46%   |
| JMicron Technology          | 2         | 2      | 0.46%   |
| Hewlett-Packard             | 2         | 3      | 0.46%   |
| Corsair                     | 2         | 2      | 0.46%   |
| ADATA Technology            | 2         | 2      | 0.46%   |
| Wibtek                      | 1         | 1      | 0.23%   |
| WALRAM                      | 1         | 1      | 0.23%   |
| Vaseky                      | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 7         | 1.44%   |
| Samsung SSD 860 EVO 500GB                             | 5         | 1.03%   |
| Intel SSD 660P Series 1024GB                          | 5         | 1.03%   |
| Seagate ST4000DM004-2CV104 4TB                        | 4         | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB                        | 4         | 0.82%   |
| Sandisk WD Black SN850 1TB                            | 4         | 0.82%   |
| SanDisk NVMe SSD Drive 2TB                            | 4         | 0.82%   |
| SanDisk NVMe SSD Drive 1TB                            | 4         | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB   | 4         | 0.82%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 4         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 4         | 0.82%   |
| Kingston SNVS500G 500GB                               | 4         | 0.82%   |
| Kingston SA400S37480G 480GB SSD                       | 4         | 0.82%   |
| Toshiba MQ04ABF100 1TB                                | 3         | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB                        | 3         | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB                        | 3         | 0.62%   |
| Sandisk WD_BLACK SN850X 4000GB                        | 3         | 0.62%   |
| Samsung SSD 980 PRO 2TB                               | 3         | 0.62%   |
| Samsung SSD 980 PRO 1TB                               | 3         | 0.62%   |
| Samsung SSD 980 1TB                                   | 3         | 0.62%   |
| Samsung SSD 970 EVO Plus 500GB                        | 3         | 0.62%   |
| Samsung SSD 870 QVO 1TB                               | 3         | 0.62%   |
| Samsung SSD 850 EVO 250GB                             | 3         | 0.62%   |
| Phison E16 PCIe4 NVMe Controller 500GB                | 3         | 0.62%   |
| Kingston Company SNV2S1000G 1TB                       | 3         | 0.62%   |
| Kingston SA400S37240G 240GB SSD                       | 3         | 0.62%   |
| Crucial CT1000BX500SSD1 1TB                           | 3         | 0.62%   |
| Unknown                                               | 3         | 0.62%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 2         | 0.41%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 2         | 0.41%   |
| WDC WD1001FALS-40U9B0 1TB                             | 2         | 0.41%   |
| WDC WD Blue SA510 2.5 1000GB                          | 2         | 0.41%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                  | 2         | 0.41%   |
| Unknown MMC Card  32GB                                | 2         | 0.41%   |
| UMIS RPJTJ512MGE1QDQ 512GB                            | 2         | 0.41%   |
| Toshiba KBG40ZNT512G MEMORY 512GB                     | 2         | 0.41%   |
| Toshiba DT01ACA100 1TB                                | 2         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 2         | 0.41%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 500GB   | 2         | 0.41%   |
| Seagate ST1000LM048-2E7172 1TB                        | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 59     | 37.14%  |
| WDC                 | 28        | 33     | 26.67%  |
| Toshiba             | 16        | 19     | 15.24%  |
| Hitachi             | 8         | 8      | 7.62%   |
| HGST                | 6         | 7      | 5.71%   |
| Samsung Electronics | 3         | 3      | 2.86%   |
| Maxtor              | 2         | 2      | 1.9%    |
| Unknown             | 1         | 1      | 0.95%   |
| ASMT                | 1         | 1      | 0.95%   |
| Apple               | 1         | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 34     | 16.67%  |
| Kingston            | 17        | 20     | 12.32%  |
| SanDisk             | 14        | 18     | 10.14%  |
| WDC                 | 13        | 15     | 9.42%   |
| Crucial             | 13        | 17     | 9.42%   |
| Micron Technology   | 6         | 7      | 4.35%   |
| Intel               | 4         | 5      | 2.9%    |
| China               | 4         | 4      | 2.9%    |
| PNY                 | 3         | 3      | 2.17%   |
| Patriot             | 3         | 3      | 2.17%   |
| A-DATA Technology   | 3         | 4      | 2.17%   |
| Transcend           | 2         | 2      | 1.45%   |
| Team                | 2         | 2      | 1.45%   |
| SK hynix            | 2         | 2      | 1.45%   |
| Seagate             | 2         | 2      | 1.45%   |
| JMicron Technology  | 2         | 2      | 1.45%   |
| Hewlett-Packard     | 2         | 2      | 1.45%   |
| Vaseky              | 1         | 1      | 0.72%   |
| Toshiba             | 1         | 1      | 0.72%   |
| SPCC                | 1         | 5      | 0.72%   |
| Smartbuy            | 1         | 1      | 0.72%   |
| SADAYU              | 1         | 1      | 0.72%   |
| S3+                 | 1         | 1      | 0.72%   |
| PHD 3.0             | 1         | 1      | 0.72%   |
| Neo                 | 1         | 1      | 0.72%   |
| LITEON              | 1         | 1      | 0.72%   |
| Lexar               | 1         | 1      | 0.72%   |
| Lenovo              | 1         | 1      | 0.72%   |
| INNOVATION IT       | 1         | 1      | 0.72%   |
| Hoodisk             | 1         | 1      | 0.72%   |
| Gigabyte Technology | 1         | 1      | 0.72%   |
| FURY                | 1         | 2      | 0.72%   |
| Emtec               | 1         | 2      | 0.72%   |
| CT2000BX            | 1         | 1      | 0.72%   |
| CT1000MX            | 1         | 1      | 0.72%   |
| Corsair             | 1         | 1      | 0.72%   |
| BAITITON            | 1         | 2      | 0.72%   |
| Apple               | 1         | 1      | 0.72%   |
| AMD                 | 1         | 1      | 0.72%   |
| Unknown             | 1         | 1      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 165       | 212    | 42.97%  |
| SSD     | 121       | 172    | 31.51%  |
| HDD     | 79        | 134    | 20.57%  |
| Unknown | 13        | 14     | 3.39%   |
| MMC     | 6         | 7      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 165       | 212    | 47.69%  |
| SATA | 154       | 296    | 44.51%  |
| SAS  | 21        | 24     | 6.07%   |
| MMC  | 6         | 7      | 1.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 139    | 45.45%  |
| 0.51-1.0   | 74        | 104    | 33.64%  |
| 1.01-2.0   | 25        | 36     | 11.36%  |
| 3.01-4.0   | 11        | 13     | 5%      |
| 4.01-10.0  | 8         | 12     | 3.64%   |
| 2.01-3.0   | 1         | 1      | 0.45%   |
| 10.01-20.0 | 1         | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 69        | 25.46%  |
| 501-1000       | 53        | 19.56%  |
| 251-500        | 50        | 18.45%  |
| 1001-2000      | 35        | 12.92%  |
| More than 3000 | 27        | 9.96%   |
| 2001-3000      | 11        | 4.06%   |
| 51-100         | 11        | 4.06%   |
| 1-20           | 8         | 2.95%   |
| 21-50          | 7         | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 62        | 22.46%  |
| 1-20           | 55        | 19.93%  |
| 101-250        | 49        | 17.75%  |
| 501-1000       | 28        | 10.14%  |
| 51-100         | 28        | 10.14%  |
| 251-500        | 26        | 9.42%   |
| 1001-2000      | 14        | 5.07%   |
| More than 3000 | 8         | 2.9%    |
| 2001-3000      | 6         | 2.17%   |

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
| Intel SSDPEKNW512G8 512GB                    | 1         | 2      | 4%      |
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
| Intel               | 3         | 4      | 12%     |
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
| NVMe | 3         | 4      | 15%     |

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
| Detected | 165       | 325    | 56.51%  |
| Works    | 107       | 183    | 36.64%  |
| Malfunc  | 19        | 29     | 6.51%   |
| Failed   | 1         | 2      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 136       | 34.69%  |
| AMD                            | 69        | 17.6%   |
| Samsung Electronics            | 53        | 13.52%  |
| SanDisk                        | 32        | 8.16%   |
| Micron/Crucial Technology      | 12        | 3.06%   |
| Phison Electronics             | 11        | 2.81%   |
| Kingston Technology Company    | 11        | 2.81%   |
| SK hynix                       | 10        | 2.55%   |
| Micron Technology              | 10        | 2.55%   |
| Silicon Motion                 | 8         | 2.04%   |
| ASMedia Technology             | 6         | 1.53%   |
| Toshiba America Info Systems   | 5         | 1.28%   |
| ADATA Technology               | 5         | 1.28%   |
| Union Memory (Shenzhen)        | 4         | 1.02%   |
| KIOXIA                         | 4         | 1.02%   |
| Solid State Storage Technology | 3         | 0.77%   |
| Shenzhen Longsys Electronics   | 2         | 0.51%   |
| Realtek Semiconductor          | 2         | 0.51%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.51%   |
| JMicron Technology             | 2         | 0.51%   |
| Silicon Image                  | 1         | 0.26%   |
| Nvidia                         | 1         | 0.26%   |
| Marvell Technology Group       | 1         | 0.26%   |
| Biwin Storage Technology       | 1         | 0.26%   |
| Apple                          | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 50        | 11.68%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 4.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 2.8%    |
| Samsung NVMe SSD Controller 980                                                | 11        | 2.57%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 2.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 2.34%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 9         | 2.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 2.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 1.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 1.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 1.64%   |
| Intel SSD 660P Series                                                          | 7         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 1.64%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 6         | 1.4%    |
| Intel SATA Controller [RAID mode]                                              | 6         | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 1.4%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 1.4%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 1.17%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 5         | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.17%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.17%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 1.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.17%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 4         | 0.93%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 0.93%   |
| Kingston Company NVMe Controller                                               | 4         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.7%    |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 0.7%    |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 179       | 47.73%  |
| NVMe | 165       | 44%     |
| RAID | 24        | 6.4%    |
| IDE  | 7         | 1.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 168       | 63.64%  |
| AMD    | 96        | 36.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 3.41%   |
| Intel 12th Gen Core i7-1260P                  | 7         | 2.65%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.89%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 1.14%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.14%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.14%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 1.14%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 1.14%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.14%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.14%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.14%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 3         | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.76%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.76%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.76%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.76%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 2         | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.76%   |
| Intel Celeron N5100 @ 1.10GHz                 | 2         | 0.76%   |
| Intel 12th Gen Core i5-1235U                  | 2         | 0.76%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.76%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.76%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.76%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.76%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 2         | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.76%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 52        | 19.7%   |
| Other                   | 45        | 17.05%  |
| Intel Core i7           | 41        | 15.53%  |
| AMD Ryzen 5             | 38        | 14.39%  |
| AMD Ryzen 7             | 31        | 11.74%  |
| Intel Celeron           | 11        | 4.17%   |
| AMD Ryzen 9             | 10        | 3.79%   |
| Intel Core i3           | 6         | 2.27%   |
| Intel Xeon              | 5         | 1.89%   |
| AMD Ryzen 5 PRO         | 3         | 1.14%   |
| AMD FX                  | 3         | 1.14%   |
| Intel Pentium Dual-Core | 2         | 0.76%   |
| Intel Pentium           | 2         | 0.76%   |
| Intel Core 2 Duo        | 2         | 0.76%   |
| Intel Pentium Silver    | 1         | 0.38%   |
| Intel Pentium Gold      | 1         | 0.38%   |
| Intel Core i9           | 1         | 0.38%   |
| AMD Ryzen Embedded      | 1         | 0.38%   |
| AMD Ryzen 7 PRO         | 1         | 0.38%   |
| AMD Ryzen 3 PRO         | 1         | 0.38%   |
| AMD Ryzen 3             | 1         | 0.38%   |
| AMD PRO A10             | 1         | 0.38%   |
| AMD Phenom II X4        | 1         | 0.38%   |
| AMD Athlon II X3        | 1         | 0.38%   |
| AMD Athlon              | 1         | 0.38%   |
| AMD A6                  | 1         | 0.38%   |
| AMD A4                  | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 98        | 37.12%  |
| 6      | 52        | 19.7%   |
| 2      | 43        | 16.29%  |
| 8      | 39        | 14.77%  |
| 12     | 12        | 4.55%   |
| 10     | 6         | 2.27%   |
| 16     | 5         | 1.89%   |
| 14     | 4         | 1.52%   |
| 3      | 3         | 1.14%   |
| 24     | 2         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 264       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 207       | 78.41%  |
| 1      | 57        | 21.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 264       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 212       | 79.1%   |
| 0x0a50000c | 10        | 3.73%   |
| 0x0a601203 | 7         | 2.61%   |
| 0x0a404102 | 4         | 1.49%   |
| 0x08608103 | 4         | 1.49%   |
| 0x0a50000d | 3         | 1.12%   |
| 0x0a20120a | 3         | 1.12%   |
| 0x08701021 | 3         | 1.12%   |
| 0x08600104 | 3         | 1.12%   |
| 0x0a404101 | 2         | 0.75%   |
| 0x08108109 | 2         | 0.75%   |
| 0x906a3    | 1         | 0.37%   |
| 0x90672    | 1         | 0.37%   |
| 0x306c3    | 1         | 0.37%   |
| 0x0a201025 | 1         | 0.37%   |
| 0x08900201 | 1         | 0.37%   |
| 0x08701030 | 1         | 0.37%   |
| 0x08701013 | 1         | 0.37%   |
| 0x08600106 | 1         | 0.37%   |
| 0x08108102 | 1         | 0.37%   |
| 0x0810100b | 1         | 0.37%   |
| 0x0800820d | 1         | 0.37%   |
| 0x08001138 | 1         | 0.37%   |
| 0x0700010f | 1         | 0.37%   |
| 0x06000852 | 1         | 0.37%   |
| 0x03000027 | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 44        | 16.6%   |
| KabyLake         | 37        | 13.96%  |
| Zen 3            | 30        | 11.32%  |
| Skylake          | 17        | 6.42%   |
| Haswell          | 17        | 6.42%   |
| Zen 2            | 16        | 6.04%   |
| Alderlake Hybrid | 15        | 5.66%   |
| Zen+             | 12        | 4.53%   |
| TigerLake        | 12        | 4.53%   |
| SandyBridge      | 12        | 4.53%   |
| IvyBridge        | 11        | 4.15%   |
| Nehalem          | 5         | 1.89%   |
| CometLake        | 5         | 1.89%   |
| Zen              | 4         | 1.51%   |
| Icelake          | 4         | 1.51%   |
| Broadwell        | 4         | 1.51%   |
| Piledriver       | 3         | 1.13%   |
| Penryn           | 3         | 1.13%   |
| Goldmont         | 3         | 1.13%   |
| Westmere         | 2         | 0.75%   |
| K10              | 2         | 0.75%   |
| Tremont          | 1         | 0.38%   |
| Puma             | 1         | 0.38%   |
| K10 Llano        | 1         | 0.38%   |
| Jaguar           | 1         | 0.38%   |
| Goldmont plus    | 1         | 0.38%   |
| Excavator        | 1         | 0.38%   |
| Core             | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 137       | 42.28%  |
| AMD    | 102       | 31.48%  |
| Nvidia | 85        | 26.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 12        | 3.66%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 10        | 3.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 9         | 2.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9         | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 9         | 2.74%   |
| AMD Lucienne                                                                  | 9         | 2.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 9         | 2.74%   |
| Intel HD Graphics 530                                                         | 8         | 2.44%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 8         | 2.44%   |
| AMD Renoir                                                                    | 8         | 2.44%   |
| AMD Rembrandt [Radeon 680M]                                                   | 7         | 2.13%   |
| AMD Raphael                                                                   | 7         | 2.13%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 7         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 6         | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 1.83%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 1.52%   |
| Intel HD Graphics 620                                                         | 5         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 1.52%   |
| AMD Barcelo                                                                   | 5         | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4         | 1.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 1.22%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 4         | 1.22%   |
| Intel JasperLake [UHD Graphics]                                               | 4         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.22%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 3         | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 0.91%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                | 3         | 0.91%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 3         | 0.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 0.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 0.91%   |
| Intel HD Graphics 630                                                         | 3         | 0.91%   |
| Intel HD Graphics 500                                                         | 3         | 0.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3         | 0.91%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.61%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2         | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 89        | 33.71%  |
| 1 x AMD         | 77        | 29.17%  |
| Intel + Nvidia  | 36        | 13.64%  |
| 1 x Nvidia      | 35        | 13.26%  |
| AMD + Nvidia    | 13        | 4.92%   |
| Intel + AMD     | 7         | 2.65%   |
| 2 x AMD         | 4         | 1.52%   |
| Other           | 1         | 0.38%   |
| 2 x Intel       | 1         | 0.38%   |
| Intel + 2 x AMD | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 197       | 73.78%  |
| Proprietary | 67        | 25.09%  |
| Unknown     | 3         | 1.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 171       | 63.81%  |
| 3.01-4.0   | 21        | 7.84%   |
| 0.01-0.5   | 20        | 7.46%   |
| 1.01-2.0   | 17        | 6.34%   |
| 7.01-8.0   | 15        | 5.6%    |
| 8.01-16.0  | 8         | 2.99%   |
| 5.01-6.0   | 6         | 2.24%   |
| 0.51-1.0   | 4         | 1.49%   |
| 16.01-24.0 | 3         | 1.12%   |
| 2.01-3.0   | 2         | 0.75%   |
| 4.01-5.0   | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 13.23%  |
| BOE                     | 36        | 11.61%  |
| AU Optronics            | 31        | 10%     |
| Chimei Innolux          | 22        | 7.1%    |
| Dell                    | 20        | 6.45%   |
| LG Display              | 17        | 5.48%   |
| Goldstar                | 14        | 4.52%   |
| Iiyama                  | 10        | 3.23%   |
| Hewlett-Packard         | 10        | 3.23%   |
| Philips                 | 9         | 2.9%    |
| AOC                     | 9         | 2.9%    |
| Acer                    | 9         | 2.9%    |
| Apple                   | 8         | 2.58%   |
| ASUSTek Computer        | 7         | 2.26%   |
| Ancor Communications    | 7         | 2.26%   |
| Sharp                   | 5         | 1.61%   |
| PANDA                   | 5         | 1.61%   |
| Lenovo                  | 5         | 1.61%   |
| InfoVision              | 5         | 1.61%   |
| Gigabyte Technology     | 3         | 0.97%   |
| BenQ                    | 3         | 0.97%   |
| ViewSonic               | 2         | 0.65%   |
| SAC                     | 2         | 0.65%   |
| MSI                     | 2         | 0.65%   |
| Eizo                    | 2         | 0.65%   |
| Chi Mei Optoelectronics | 2         | 0.65%   |
| Wacom                   | 1         | 0.32%   |
| VIZ                     | 1         | 0.32%   |
| Valve                   | 1         | 0.32%   |
| UGD                     | 1         | 0.32%   |
| STA                     | 1         | 0.32%   |
| Sceptre Tech            | 1         | 0.32%   |
| RTK                     | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| ONN                     | 1         | 0.32%   |
| NEC Computers           | 1         | 0.32%   |
| Mi                      | 1         | 0.32%   |
| Medion Akoya            | 1         | 0.32%   |
| LOE                     | 1         | 0.32%   |
| KDC                     | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 3         | 0.92%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 0.92%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 3         | 0.92%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.62%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 2         | 0.62%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2         | 0.62%   |
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                 | 2         | 0.62%   |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                  | 2         | 0.62%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 677x290mm 29.0-inch              | 2         | 0.62%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.62%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.62%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.62%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                 | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch        | 2         | 0.62%   |
| Ancor Communications MX259 ACI25C2 1920x1080 553x309mm 24.9-inch      | 2         | 0.62%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1         | 0.31%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                    | 1         | 0.31%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch             | 1         | 0.31%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 1         | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.31%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1         | 0.31%   |
| STA SEMP LEDTV STA0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.31%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.31%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.31%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.31%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch        | 1         | 0.31%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 0.31%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch     | 1         | 0.31%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1         | 0.31%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 610x350mm 27.7-inch     | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                      | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM0498 1600x900 443x249mm 20.0-inch   | 1         | 0.31%   |
| Samsung Electronics SyncMaster SAM0192 1280x1024 338x270mm 17.0-inch  | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 142       | 47.97%  |
| 1366x768 (WXGA)    | 32        | 10.81%  |
| 3840x2160 (4K)     | 31        | 10.47%  |
| 2560x1440 (QHD)    | 23        | 7.77%   |
| 1920x1200 (WUXGA)  | 9         | 3.04%   |
| 2560x1080          | 7         | 2.36%   |
| 1600x900 (HD+)     | 7         | 2.36%   |
| 1440x900 (WXGA+)   | 7         | 2.36%   |
| 3440x1440          | 6         | 2.03%   |
| 2560x1600          | 5         | 1.69%   |
| 2880x1800          | 4         | 1.35%   |
| 3840x2400          | 2         | 0.68%   |
| 2240x1400          | 2         | 0.68%   |
| 1920x540           | 2         | 0.68%   |
| 1920x1280          | 2         | 0.68%   |
| 1680x1050 (WSXGA+) | 2         | 0.68%   |
| 1280x800 (WXGA)    | 2         | 0.68%   |
| 1280x1024 (SXGA)   | 2         | 0.68%   |
| 800x1280           | 1         | 0.34%   |
| 3840x1100          | 1         | 0.34%   |
| 3456x2160          | 1         | 0.34%   |
| 3072x1920          | 1         | 0.34%   |
| 2736x1824          | 1         | 0.34%   |
| 2256x1504          | 1         | 0.34%   |
| 2160x1440          | 1         | 0.34%   |
| 1360x768           | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 61        | 19.55%  |
| 27      | 35        | 11.22%  |
| 24      | 33        | 10.58%  |
| 14      | 28        | 8.97%   |
| 13      | 24        | 7.69%   |
| 17      | 21        | 6.73%   |
| 21      | 16        | 5.13%   |
| 31      | 15        | 4.81%   |
| 23      | 15        | 4.81%   |
| 34      | 12        | 3.85%   |
| 19      | 10        | 3.21%   |
| 16      | 7         | 2.24%   |
| 12      | 6         | 1.92%   |
| 11      | 6         | 1.92%   |
| 18      | 3         | 0.96%   |
| 46      | 2         | 0.64%   |
| 20      | 2         | 0.64%   |
| Unknown | 2         | 0.64%   |
| 72      | 1         | 0.32%   |
| 69      | 1         | 0.32%   |
| 65      | 1         | 0.32%   |
| 54      | 1         | 0.32%   |
| 52      | 1         | 0.32%   |
| 43      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 37      | 1         | 0.32%   |
| 33      | 1         | 0.32%   |
| 28      | 1         | 0.32%   |
| 26      | 1         | 0.32%   |
| 25      | 1         | 0.32%   |
| 22      | 1         | 0.32%   |
| 7       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 105       | 34.54%  |
| 501-600     | 78        | 25.66%  |
| 401-500     | 29        | 9.54%   |
| 201-300     | 25        | 8.22%   |
| 351-400     | 22        | 7.24%   |
| 601-700     | 19        | 6.25%   |
| 701-800     | 12        | 3.95%   |
| 1001-1500   | 5         | 1.64%   |
| 801-900     | 3         | 0.99%   |
| 1501-2000   | 2         | 0.66%   |
| Unknown     | 2         | 0.66%   |
| 901-1000    | 1         | 0.33%   |
| 1-100       | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 214       | 78.1%   |
| 16/10   | 38        | 13.87%  |
| 21/9    | 12        | 4.38%   |
| 3/2     | 5         | 1.82%   |
| 5/4     | 2         | 0.73%   |
| 3.40    | 1         | 0.36%   |
| 0.67    | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 61        | 19.68%  |
| 201-250        | 47        | 15.16%  |
| 81-90          | 40        | 12.9%   |
| 301-350        | 35        | 11.29%  |
| 351-500        | 29        | 9.35%   |
| 121-130        | 20        | 6.45%   |
| 251-300        | 16        | 5.16%   |
| 151-200        | 14        | 4.52%   |
| 71-80          | 10        | 3.23%   |
| 51-60          | 7         | 2.26%   |
| 111-120        | 7         | 2.26%   |
| More than 1000 | 5         | 1.61%   |
| 61-70          | 5         | 1.61%   |
| 501-1000       | 5         | 1.61%   |
| 141-150        | 4         | 1.29%   |
| 91-100         | 2         | 0.65%   |
| Unknown        | 2         | 0.65%   |
| 1-40           | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 95        | 32.2%   |
| 51-100        | 94        | 31.86%  |
| 101-120       | 54        | 18.31%  |
| 161-240       | 31        | 10.51%  |
| More than 240 | 13        | 4.41%   |
| 1-50          | 6         | 2.03%   |
| Unknown       | 2         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 198       | 74.72%  |
| 2     | 56        | 21.13%  |
| 3     | 7         | 2.64%   |
| 0     | 3         | 1.13%   |
| 4     | 1         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 153       | 38.83%  |
| Intel                 | 124       | 31.47%  |
| MediaTek              | 29        | 7.36%   |
| Qualcomm Atheros      | 19        | 4.82%   |
| Broadcom              | 17        | 4.31%   |
| TP-Link               | 7         | 1.78%   |
| Ralink                | 6         | 1.52%   |
| ASIX Electronics      | 6         | 1.52%   |
| Broadcom Limited      | 5         | 1.27%   |
| Hewlett-Packard       | 3         | 0.76%   |
| ASUSTek Computer      | 3         | 0.76%   |
| Samsung Electronics   | 2         | 0.51%   |
| Microsoft             | 2         | 0.51%   |
| Google                | 2         | 0.51%   |
| ZyXEL Communications  | 1         | 0.25%   |
| Xiaomi                | 1         | 0.25%   |
| U-Blox                | 1         | 0.25%   |
| Texas Instruments     | 1         | 0.25%   |
| Qualcomm              | 1         | 0.25%   |
| QinHeng Electronics   | 1         | 0.25%   |
| Nvidia                | 1         | 0.25%   |
| NetGear               | 1         | 0.25%   |
| Linksys               | 1         | 0.25%   |
| Lenovo                | 1         | 0.25%   |
| ICS Advent            | 1         | 0.25%   |
| Huawei Technologies   | 1         | 0.25%   |
| DisplayLink           | 1         | 0.25%   |
| Dell                  | 1         | 0.25%   |
| Arduino SA            | 1         | 0.25%   |
| Aquantia              | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 19.6%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 4.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 11        | 2.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 10        | 2.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 9         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.78%   |
| Intel Wireless 7265                                               | 8         | 1.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 8         | 1.78%   |
| Intel I211 Gigabit Network Connection                             | 8         | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.56%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.56%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.56%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.34%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5         | 1.11%   |
| Intel Wireless 8260                                               | 5         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.89%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 4         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.67%   |
| Intel Wireless 7260                                               | 3         | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.45%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.45%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 97        | 44.7%   |
| Realtek Semiconductor | 37        | 17.05%  |
| MediaTek              | 28        | 12.9%   |
| Qualcomm Atheros      | 17        | 7.83%   |
| Broadcom              | 11        | 5.07%   |
| TP-Link               | 7         | 3.23%   |
| Ralink                | 6         | 2.76%   |
| Broadcom Limited      | 3         | 1.38%   |
| ASUSTek Computer      | 3         | 1.38%   |
| Microsoft             | 2         | 0.92%   |
| ZyXEL Communications  | 1         | 0.46%   |
| Qualcomm              | 1         | 0.46%   |
| NetGear               | 1         | 0.46%   |
| Linksys               | 1         | 0.46%   |
| Hewlett-Packard       | 1         | 0.46%   |
| Dell                  | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 5.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 5.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 10        | 4.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 9         | 4.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.67%   |
| Intel Wireless 7265                                            | 8         | 3.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 8         | 3.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.21%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.21%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 3.21%   |
| Intel Wireless 8265 / 8275                                     | 6         | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.29%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 2.29%   |
| Intel Wireless 8260                                            | 5         | 2.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.29%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 1.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.83%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 4         | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.38%   |
| Intel Wireless 7260                                            | 3         | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.92%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 0.92%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.92%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 2         | 0.92%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.92%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 2         | 0.92%   |
| Intel Wireless 3165                                            | 2         | 0.92%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 0.92%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 0.92%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 2         | 0.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 0.92%   |
| ZyXEL ZyXEL Dual-Band Wireless AC USB Adapter                  | 1         | 0.46%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 134       | 60.09%  |
| Intel                 | 54        | 24.22%  |
| Broadcom              | 10        | 4.48%   |
| ASIX Electronics      | 6         | 2.69%   |
| Qualcomm Atheros      | 5         | 2.24%   |
| Samsung Electronics   | 2         | 0.9%    |
| Google                | 2         | 0.9%    |
| Broadcom Limited      | 2         | 0.9%    |
| Xiaomi                | 1         | 0.45%   |
| Nvidia                | 1         | 0.45%   |
| MediaTek              | 1         | 0.45%   |
| Lenovo                | 1         | 0.45%   |
| ICS Advent            | 1         | 0.45%   |
| Huawei Technologies   | 1         | 0.45%   |
| DisplayLink           | 1         | 0.45%   |
| Aquantia              | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 39.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 9.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 5.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 4.44%   |
| Intel I211 Gigabit Network Connection                             | 8         | 3.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.11%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 2.22%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.78%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.78%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.89%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.89%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.44%   |
| MediaTek Infinix SMART 6 HD                                       | 1         | 0.44%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.44%   |
| Intel Ethernet Controller I219-LM                                 | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.44%   |
| Intel Ethernet Connection (17) I219-LM                            | 1         | 0.44%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.44%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.44%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 209       | 49.29%  |
| Ethernet | 209       | 49.29%  |
| Modem    | 6         | 1.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 164       | 58.99%  |
| Ethernet | 114       | 41.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 136       | 51.52%  |
| 2     | 125       | 47.35%  |
| 5     | 1         | 0.38%   |
| 3     | 1         | 0.38%   |
| 0     | 1         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 178       | 66.67%  |
| Yes  | 89        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 91        | 46.67%  |
| Realtek Semiconductor           | 27        | 13.85%  |
| Cambridge Silicon Radio         | 13        | 6.67%   |
| Apple                           | 10        | 5.13%   |
| IMC Networks                    | 9         | 4.62%   |
| MediaTek                        | 8         | 4.1%    |
| Foxconn / Hon Hai               | 8         | 4.1%    |
| Qualcomm Atheros Communications | 7         | 3.59%   |
| Lite-On Technology              | 6         | 3.08%   |
| Broadcom                        | 5         | 2.56%   |
| Realtek                         | 3         | 1.54%   |
| ASUSTek Computer                | 3         | 1.54%   |
| TP-Link                         | 2         | 1.03%   |
| Toshiba                         | 1         | 0.51%   |
| Ralink                          | 1         | 0.51%   |
| Dell                            | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 26        | 13.33%  |
| Realtek Bluetooth Radio                             | 24        | 12.31%  |
| Intel AX201 Bluetooth                               | 19        | 9.74%   |
| Intel Bluetooth Device                              | 18        | 9.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 4.62%   |
| Intel AX210 Bluetooth                               | 9         | 4.62%   |
| MediaTek Wireless_Device                            | 8         | 4.1%    |
| Intel AX200 Bluetooth                               | 7         | 3.59%   |
| IMC Networks Wireless_Device                        | 5         | 2.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.05%   |
| Lite-On Wireless_Device                             | 4         | 2.05%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 2.05%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 2.05%   |
| Apple Bluetooth USB Host Controller                 | 4         | 2.05%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.54%   |
| Realtek Bluetooth Radio                             | 3         | 1.54%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.54%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.54%   |
| TP-Link UB5A Adapter                                | 2         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.03%   |
| Apple Bluetooth Host Controller                     | 2         | 1.03%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.51%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.51%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.51%   |
| IMC Networks BCM20702A0                             | 1         | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.51%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.51%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.51%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.51%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.51%   |
| Broadcom BCM20702A0                                 | 1         | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.51%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 0.51%   |
| ASUS Bluetooth Radio                                | 1         | 0.51%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 167       | 41.65%  |
| AMD                          | 113       | 28.18%  |
| Nvidia                       | 67        | 16.71%  |
| C-Media Electronics          | 10        | 2.49%   |
| Logitech                     | 4         | 1%      |
| Focusrite-Novation           | 4         | 1%      |
| Realtek Semiconductor        | 3         | 0.75%   |
| VIA Technologies             | 2         | 0.5%    |
| Texas Instruments            | 2         | 0.5%    |
| SteelSeries ApS              | 2         | 0.5%    |
| SAVITECH                     | 2         | 0.5%    |
| Micro Star International     | 2         | 0.5%    |
| Hewlett-Packard              | 2         | 0.5%    |
| Creative Technology          | 2         | 0.5%    |
| Corsair                      | 2         | 0.5%    |
| Trust                        | 1         | 0.25%   |
| TEAC                         | 1         | 0.25%   |
| Sennheiser Communications    | 1         | 0.25%   |
| Nordic Semiconductor ASA     | 1         | 0.25%   |
| Mackie Designs               | 1         | 0.25%   |
| M-Audio                      | 1         | 0.25%   |
| Lenovo                       | 1         | 0.25%   |
| JMTek                        | 1         | 0.25%   |
| GN Netcom                    | 1         | 0.25%   |
| Generalplus Technology       | 1         | 0.25%   |
| Dell                         | 1         | 0.25%   |
| D&M Holdings (Denon/Marantz) | 1         | 0.25%   |
| Creative Labs                | 1         | 0.25%   |
| AudioQuest                   | 1         | 0.25%   |
| ASUSTek Computer             | 1         | 0.25%   |
| Asahi Kasei Microsystems     | 1         | 0.25%   |
| 2.4G Composite Device        | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 60        | 12.22%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 6.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 18        | 3.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 2.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 2.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 13        | 2.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 2.44%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 2.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.24%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 1.83%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 1.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.43%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.22%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.22%   |
| Nvidia Audio device                                                        | 6         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.02%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.81%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 0.81%   |
| Intel Jasper Lake HD Audio                                                 | 4         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.81%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 0.81%   |
| Realtek Semiconductor USB Audio                                            | 3         | 0.61%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 22.7%   |
| Micron Technology   | 27        | 16.56%  |
| SK hynix            | 25        | 15.34%  |
| Kingston            | 16        | 9.82%   |
| G.Skill             | 10        | 6.13%   |
| Crucial             | 10        | 6.13%   |
| Corsair             | 9         | 5.52%   |
| Unknown             | 4         | 2.45%   |
| Ramaxel Technology  | 4         | 2.45%   |
| A-DATA Technology   | 4         | 2.45%   |
| Unknown             | 3         | 1.84%   |
| Unknown (ABCD)      | 2         | 1.23%   |
| Team                | 2         | 1.23%   |
| Patriot             | 2         | 1.23%   |
| Transcend           | 1         | 0.61%   |
| Timetec             | 1         | 0.61%   |
| Nanya Technology    | 1         | 0.61%   |
| Micron/Elpida       | 1         | 0.61%   |
| GOODRAM             | 1         | 0.61%   |
| fef5                | 1         | 0.61%   |
| Atermiter           | 1         | 0.61%   |
| 4ea5                | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.75%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.75%   |
| Unknown                                                          | 3         | 1.75%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.17%   |
| Micron RAM MT53E512M32D2NP-046 4GB Row Of Chips LPDDR4 4267MT/s  | 2         | 1.17%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 2         | 1.17%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s            | 2         | 1.17%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 1.17%   |
| Unknown RAM Module 8GB DIMM 667MT/s                              | 1         | 0.58%   |
| Unknown RAM Module 4GB SODIMM 800MT/s                            | 1         | 0.58%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 0.58%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 1         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.58%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 0.58%   |
| Timetec RAM S16G-3200 16GB SODIMM DDR4 2133MT/s                  | 1         | 0.58%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.58%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s            | 1         | 0.58%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.58%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.58%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 1         | 0.58%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 1         | 0.58%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 1         | 0.58%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.58%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.58%   |
| SK hynix RAM HMA81GU7MFR8N-TF 8GB DIMM DDR4 2133MT/s             | 1         | 0.58%   |
| SK hynix RAM HMA81GU7CJR8N-VK 8GB DIMM DDR4 2667MT/s             | 1         | 0.58%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 0.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.58%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s             | 1         | 0.58%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.58%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 0.58%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.58%   |
| SK hynix RAM H58G66AK6BX070 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 71        | 49.31%  |
| DDR3    | 26        | 18.06%  |
| LPDDR4  | 15        | 10.42%  |
| DDR5    | 13        | 9.03%   |
| LPDDR5  | 12        | 8.33%   |
| LPDDR3  | 4         | 2.78%   |
| Unknown | 3         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 44.14%  |
| DIMM         | 48        | 33.1%   |
| Row Of Chips | 31        | 21.38%  |
| Unknown      | 2         | 1.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 64        | 41.56%  |
| 4096  | 40        | 25.97%  |
| 16384 | 31        | 20.13%  |
| 32768 | 9         | 5.84%   |
| 2048  | 8         | 5.19%   |
| 12288 | 1         | 0.65%   |
| 1024  | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 38        | 24.84%  |
| 6400  | 13        | 8.5%    |
| 2667  | 12        | 7.84%   |
| 2400  | 12        | 7.84%   |
| 1600  | 12        | 7.84%   |
| 4800  | 8         | 5.23%   |
| 4267  | 8         | 5.23%   |
| 3600  | 7         | 4.58%   |
| 2133  | 7         | 4.58%   |
| 1333  | 5         | 3.27%   |
| 3733  | 4         | 2.61%   |
| 1800  | 4         | 2.61%   |
| 3266  | 3         | 1.96%   |
| 6000  | 2         | 1.31%   |
| 2933  | 2         | 1.31%   |
| 2666  | 2         | 1.31%   |
| 1867  | 2         | 1.31%   |
| 8400  | 1         | 0.65%   |
| 5600  | 1         | 0.65%   |
| 4266  | 1         | 0.65%   |
| 3666  | 1         | 0.65%   |
| 3334  | 1         | 0.65%   |
| 3066  | 1         | 0.65%   |
| 2473  | 1         | 0.65%   |
| 1866  | 1         | 0.65%   |
| 1334  | 1         | 0.65%   |
| 1067  | 1         | 0.65%   |
| 800   | 1         | 0.65%   |
| 667   | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 28.57%  |
| Canon              | 2         | 28.57%  |
| Brother Industries | 2         | 28.57%  |
| Pantum             | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-7100 Series | 1         | 14.29%  |
| Seiko Epson XP-2200 Series | 1         | 14.29%  |
| Pantum P2200W series       | 1         | 14.29%  |
| Canon PIXMA MX490 Series   | 1         | 14.29%  |
| Canon LBP6020              | 1         | 14.29%  |
| Brother HL-L2310D series   | 1         | 14.29%  |
| Brother HL-3142CW series   | 1         | 14.29%  |

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
| Chicony Electronics                    | 30        | 18.29%  |
| Microdia                               | 13        | 7.93%   |
| IMC Networks                           | 13        | 7.93%   |
| Realtek Semiconductor                  | 11        | 6.71%   |
| Quanta                                 | 11        | 6.71%   |
| Apple                                  | 10        | 6.1%    |
| Sunplus Innovation Technology          | 9         | 5.49%   |
| Bison Electronics                      | 9         | 5.49%   |
| Logitech                               | 8         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.88%   |
| Syntek                                 | 7         | 4.27%   |
| Luxvisions Innotech Limited            | 7         | 4.27%   |
| Acer                                   | 4         | 2.44%   |
| Lite-On Technology                     | 3         | 1.83%   |
| SunplusIT                              | 2         | 1.22%   |
| Samsung Electronics                    | 2         | 1.22%   |
| Alcor Micro                            | 2         | 1.22%   |
| Suyin                                  | 1         | 0.61%   |
| Sonix Technology                       | 1         | 0.61%   |
| SN0002                                 | 1         | 0.61%   |
| Silicon Motion                         | 1         | 0.61%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.61%   |
| Primax Electronics                     | 1         | 0.61%   |
| OYT Tech                               | 1         | 0.61%   |
| OPPO Electronics                       | 1         | 0.61%   |
| MacroSilicon                           | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| Jieli Technology                       | 1         | 0.61%   |
| Generalplus Technology                 | 1         | 0.61%   |
| GEMBIRD                                | 1         | 0.61%   |
| AVerMedia Technologies                 | 1         | 0.61%   |
| A4Tech                                 | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 5.39%   |
| Chicony Integrated Camera                                                  | 9         | 5.39%   |
| Syntek Integrated Camera                                                   | 6         | 3.59%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 2.99%   |
| Realtek HP Truevision HD                                                   | 4         | 2.4%    |
| Bison Integrated Camera                                                    | 4         | 2.4%    |
| Quanta HD User Facing                                                      | 3         | 1.8%    |
| Microdia Integrated_Webcam_HD                                              | 3         | 1.8%    |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.8%    |
| Bison HD Webcam                                                            | 3         | 1.8%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 3         | 1.8%    |
| Apple FaceTime HD Camera                                                   | 3         | 1.8%    |
| Apple Built-in iSight                                                      | 3         | 1.8%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 1.2%    |
| Quanta USB2.0 HD UVC WebCam                                                | 2         | 1.2%    |
| Microdia Webcam Vitade AF                                                  | 2         | 1.2%    |
| Microdia USB 2.0 Camera                                                    | 2         | 1.2%    |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 2         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 1.2%    |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 1.2%    |
| Logitech HD Webcam C615                                                    | 2         | 1.2%    |
| Logitech HD Pro Webcam C920                                                | 2         | 1.2%    |
| Chicony HP Truevision HD                                                   | 2         | 1.2%    |
| Chicony HD WebCam                                                          | 2         | 1.2%    |
| Chicony 720p HD Camera                                                     | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 1.2%    |
| Bison Integrated RGB Camera                                                | 2         | 1.2%    |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 1.2%    |
| Alcor Micro USB 2.0 Web Camera                                             | 2         | 1.2%    |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.6%    |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.6%    |
| SunplusIT USB Camera                                                       | 1         | 0.6%    |
| SunplusIT 1080p FHD Camera                                                 | 1         | 0.6%    |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 0.6%    |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.6%    |
| Sunplus 1080p FHD Camera                                                   | 1         | 0.6%    |
| Sunplus 1.3M HD WebCam                                                     | 1         | 0.6%    |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 12        | 41.38%  |
| Validity Sensors                   | 8         | 27.59%  |
| Shenzhen Goodix Technology         | 7         | 24.14%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 3.45%   |
| Elan Microelectronics              | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 4         | 13.79%  |
| Shenzhen Goodix  Fingerprint Device                             | 4         | 13.79%  |
| Synaptics UWP WBDI                                              | 3         | 10.34%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 10.34%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 10.34%  |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 10.34%  |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 6.9%    |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 3.45%   |
| Synaptics WBDI                                                  | 1         | 3.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 3.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 3.45%   |
| Elan ELAN:ARM-M4                                                | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Broadcom     | 5         | 50%     |
| Alcor Micro  | 2         | 20%     |
| O2 Micro     | 1         | 10%     |
| Lenovo       | 1         | 10%     |
| Aladdin R.D. | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 2         | 20%     |
| Broadcom 58200                                 | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 10%     |
| Lenovo Integrated Smart Card Reader            | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 10%     |
| Aladdin R.D. JaCarta                           | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 186       | 70.19%  |
| 1     | 68        | 25.66%  |
| 2     | 10        | 3.77%   |
| 3     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 29        | 33.33%  |
| Multimedia controller    | 12        | 13.79%  |
| Net/wireless             | 9         | 10.34%  |
| Graphics card            | 9         | 10.34%  |
| Chipcard                 | 9         | 10.34%  |
| Camera                   | 8         | 9.2%    |
| Sound                    | 3         | 3.45%   |
| Unassigned class         | 2         | 2.3%    |
| Communication controller | 2         | 2.3%    |
| Storage/raid             | 1         | 1.15%   |
| Storage                  | 1         | 1.15%   |
| Card reader              | 1         | 1.15%   |
| Bluetooth                | 1         | 1.15%   |

