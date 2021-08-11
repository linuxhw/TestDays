Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | 300E5M/300E5L               | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| HP            | 250 G4                      | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Apple         | MacBookAir7,1               | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Google        | Parrot                      | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Dell          | Latitude E7240              | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| Google        | Stout                       | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| Casper        | C17B                        | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| Apple         | MacBookPro11,4              | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Dell          | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP            | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell          | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer          | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Dell          | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI           | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| HP            | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP            | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| HP            | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 170       | 58.62%  |
| 5.10.0-7-amd64             | 62        | 21.38%  |
| 5.10.0-6-amd64             | 23        | 7.93%   |
| 5.10.0-8-686-pae           | 4         | 1.38%   |
| 5.10.0-8-686               | 3         | 1.03%   |
| 5.12.0-19.3-liquorix-amd64 | 2         | 0.69%   |
| 4.19.0-14-amd64            | 2         | 0.69%   |
| 5.14.0-rc3-prygun          | 1         | 0.34%   |
| 5.13.8-xanmod1             | 1         | 0.34%   |
| 5.13.8                     | 1         | 0.34%   |
| 5.13.5-xanmod1             | 1         | 0.34%   |
| 5.13.4-e5520               | 1         | 0.34%   |
| 5.12.10                    | 1         | 0.34%   |
| 5.12.1                     | 1         | 0.34%   |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.34%   |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.34%   |
| 5.11.9+                    | 1         | 0.34%   |
| 5.11.22-1-pve              | 1         | 0.34%   |
| 5.11.15-051115-generic     | 1         | 0.34%   |
| 5.11.14                    | 1         | 0.34%   |
| 5.11.0-rc6                 | 1         | 0.34%   |
| 5.10.40-ismynik            | 1         | 0.34%   |
| 5.10.10-64                 | 1         | 0.34%   |
| 5.10.0-io7-amd64           | 1         | 0.34%   |
| 5.10.0-6-rt-amd64          | 1         | 0.34%   |
| 5.10.0-6-686               | 1         | 0.34%   |
| 5.10.0-5-amd64             | 1         | 0.34%   |
| 5.10.0-4-amd64             | 1         | 0.34%   |
| 4.19.181-z580322           | 1         | 0.34%   |
| 4.19.0-16-amd64            | 1         | 0.34%   |
| 4.19.0-16-686-pae          | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 261       | 92.23%  |
| 4.19.0   | 4         | 1.41%   |
| 5.12.0   | 3         | 1.06%   |
| 5.13.8   | 2         | 0.71%   |
| 5.14.0   | 1         | 0.35%   |
| 5.13.5   | 1         | 0.35%   |
| 5.13.4   | 1         | 0.35%   |
| 5.12.10  | 1         | 0.35%   |
| 5.12.1   | 1         | 0.35%   |
| 5.11.9   | 1         | 0.35%   |
| 5.11.22  | 1         | 0.35%   |
| 5.11.15  | 1         | 0.35%   |
| 5.11.14  | 1         | 0.35%   |
| 5.11.0   | 1         | 0.35%   |
| 5.10.40  | 1         | 0.35%   |
| 5.10.10  | 1         | 0.35%   |
| 4.19.181 | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 263       | 92.93%  |
| 5.12    | 5         | 1.77%   |
| 5.11    | 5         | 1.77%   |
| 4.19    | 5         | 1.77%   |
| 5.13    | 4         | 1.41%   |
| 5.14    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 274       | 96.82%  |
| i686   | 9         | 3.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 90        | 31.58%  |
| KDE5             | 60        | 21.05%  |
| Unknown          | 46        | 16.14%  |
| XFCE             | 30        | 10.53%  |
| MATE             | 15        | 5.26%   |
| LXQt             | 7         | 2.46%   |
| i3               | 7         | 2.46%   |
| X-Cinnamon       | 5         | 1.75%   |
| LXDE             | 5         | 1.75%   |
| KDE              | 4         | 1.4%    |
| Cinnamon         | 4         | 1.4%    |
| lightdm-xsession | 3         | 1.05%   |
| openbox          | 2         | 0.7%    |
| GNOME Flashback  | 2         | 0.7%    |
| sway             | 1         | 0.35%   |
| ICEWM            | 1         | 0.35%   |
| Enlightenment    | 1         | 0.35%   |
| default          | 1         | 0.35%   |
| awesome          | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 160       | 55.94%  |
| Wayland | 74        | 25.87%  |
| Unknown | 37        | 12.94%  |
| Tty     | 15        | 5.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 84        | 29.58%  |
| TDM     | 66        | 23.24%  |
| Unknown | 66        | 23.24%  |
| SDDM    | 64        | 22.54%  |
| LightDM | 2         | 0.7%    |
| XDM     | 1         | 0.35%   |
| KDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 111       | 39.22%  |
| Unknown | 24        | 8.48%   |
| ru_RU   | 22        | 7.77%   |
| en_GB   | 18        | 6.36%   |
| fr_FR   | 15        | 5.3%    |
| de_DE   | 14        | 4.95%   |
| es_ES   | 9         | 3.18%   |
| pt_BR   | 8         | 2.83%   |
| en_IN   | 7         | 2.47%   |
| pl_PL   | 6         | 2.12%   |
| it_IT   | 4         | 1.41%   |
| tr_TR   | 3         | 1.06%   |
| sv_SE   | 3         | 1.06%   |
| nn_NO   | 3         | 1.06%   |
| en_CA   | 3         | 1.06%   |
| de_CH   | 3         | 1.06%   |
| pt_PT   | 2         | 0.71%   |
| ja_JP   | 2         | 0.71%   |
| es_MX   | 2         | 0.71%   |
| es_CO   | 2         | 0.71%   |
| en_SG   | 2         | 0.71%   |
| en_AU   | 2         | 0.71%   |
| cs_CZ   | 2         | 0.71%   |
| C       | 2         | 0.71%   |
| uk_UA   | 1         | 0.35%   |
| ru_UA   | 1         | 0.35%   |
| ro_RO   | 1         | 0.35%   |
| nl_BE   | 1         | 0.35%   |
| hu_HU   | 1         | 0.35%   |
| hr_HR   | 1         | 0.35%   |
| gl_ES   | 1         | 0.35%   |
| fi_FI   | 1         | 0.35%   |
| es_UY   | 1         | 0.35%   |
| es_EC   | 1         | 0.35%   |
| en_SI   | 1         | 0.35%   |
| en_IE   | 1         | 0.35%   |
| en_HK   | 1         | 0.35%   |
| ca_ES   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 186       | 65.49%  |
| BIOS | 98        | 34.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 216       | 76.33%  |
| Overlay | 44        | 15.55%  |
| Btrfs   | 16        | 5.65%   |
| Zfs     | 2         | 0.71%   |
| Xfs     | 2         | 0.71%   |
| Unknown | 2         | 0.71%   |
| Rootfs  | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 197       | 69.37%  |
| MBR     | 65        | 22.89%  |
| Unknown | 22        | 7.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 252       | 88.73%  |
| Yes       | 32        | 11.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 210       | 74.2%   |
| Yes       | 73        | 25.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 95        | 33.57%  |
| Hewlett-Packard     | 48        | 16.96%  |
| Dell                | 42        | 14.84%  |
| ASUSTek Computer    | 22        | 7.77%   |
| Acer                | 20        | 7.07%   |
| Apple               | 17        | 6.01%   |
| MSI                 | 5         | 1.77%   |
| Google              | 4         | 1.41%   |
| Toshiba             | 3         | 1.06%   |
| Samsung Electronics | 3         | 1.06%   |
| HUAWEI              | 3         | 1.06%   |
| Fujitsu             | 3         | 1.06%   |
| Clevo               | 3         | 1.06%   |
| Notebook            | 2         | 0.71%   |
| Gigabyte Technology | 2         | 0.71%   |
| UNOWHY              | 1         | 0.35%   |
| TUXEDO              | 1         | 0.35%   |
| Sony                | 1         | 0.35%   |
| SLIMBOOK            | 1         | 0.35%   |
| Quanta              | 1         | 0.35%   |
| Pegatron            | 1         | 0.35%   |
| PC Specialist       | 1         | 0.35%   |
| Panasonic           | 1         | 0.35%   |
| Monster             | 1         | 0.35%   |
| Itautec             | 1         | 0.35%   |
| Casper              | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                         | 5         | 1.77%   |
| Apple MacBookAir7,1                         | 4         | 1.41%   |
| Lenovo ThinkPad T490 20N2CTO1WW             | 2         | 0.71%   |
| Lenovo ThinkPad E475 20H40006US             | 2         | 0.71%   |
| Lenovo ThinkBook 14 G2 ARE 20VF             | 2         | 0.71%   |
| Lenovo G50-80 80E5                          | 2         | 0.71%   |
| HUAWEI NBLK-WAX9X                           | 2         | 0.71%   |
| HP Laptop 15s-fq2xxx                        | 2         | 0.71%   |
| HP EliteBook 8460p                          | 2         | 0.71%   |
| HP Compaq nx6125 (PZ849UA#ABA)              | 2         | 0.71%   |
| HP Compaq nx6110 (PZ065UA#ABA)              | 2         | 0.71%   |
| Google Enguarde                             | 2         | 0.71%   |
| Dell XPS 13 9370                            | 2         | 0.71%   |
| Dell XPS 13 9310                            | 2         | 0.71%   |
| Dell XPS 13 7390                            | 2         | 0.71%   |
| Dell Precision 3540                         | 2         | 0.71%   |
| Dell Latitude 7480                          | 2         | 0.71%   |
| Dell Inspiron 5570                          | 2         | 0.71%   |
| Dell Inspiron 3793                          | 2         | 0.71%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA     | 2         | 0.71%   |
| Apple MacBook5,2                            | 2         | 0.71%   |
| Acer Aspire 5315                            | 2         | 0.71%   |
| UNOWHY Y13G002S4EI                          | 1         | 0.35%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.35%   |
| Toshiba Satellite U800W                     | 1         | 0.35%   |
| Toshiba Satellite S55-A                     | 1         | 0.35%   |
| Toshiba Satellite C45-A                     | 1         | 0.35%   |
| Sony VPCF21AFX                              | 1         | 0.35%   |
| SLIMBOOK PROX14-AMD                         | 1         | 0.35%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D  | 1         | 0.35%   |
| Samsung 370E4K                              | 1         | 0.35%   |
| Samsung 300E5M/300E5L                       | 1         | 0.35%   |
| Quanta TWC                                  | 1         | 0.35%   |
| Pegatron A15                                | 1         | 0.35%   |
| PC Specialist NV4XMB,ME,MZ                  | 1         | 0.35%   |
| Panasonic CF-AX2LDCZMF                      | 1         | 0.35%   |
| Notebook NJ50_70CU                          | 1         | 0.35%   |
| Notebook N13_N140ZU                         | 1         | 0.35%   |
| MSI U90/U100                                | 1         | 0.35%   |
| MSI Modern 15 A11M                          | 1         | 0.35%   |
| MSI GP60 2PE                                | 1         | 0.35%   |
| MSI GF65 Thin 10UE                          | 1         | 0.35%   |
| MSI CX700                                   | 1         | 0.35%   |
| Monster ABRA A5 V15.2                       | 1         | 0.35%   |
| Lenovo Yoga 300-11IBR 80M1                  | 1         | 0.35%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00       | 1         | 0.35%   |
| Lenovo ThinkPad X260 20F5S46R00             | 1         | 0.35%   |
| Lenovo ThinkPad X260 20F5S0JF00             | 1         | 0.35%   |
| Lenovo ThinkPad X240 20AMS0BU0T             | 1         | 0.35%   |
| Lenovo ThinkPad X240 20AL008EUK             | 1         | 0.35%   |
| Lenovo ThinkPad X230 2325BQ3                | 1         | 0.35%   |
| Lenovo ThinkPad X230 2325AZ8                | 1         | 0.35%   |
| Lenovo ThinkPad X230 23252FG                | 1         | 0.35%   |
| Lenovo ThinkPad X220 Tablet 4298A24         | 1         | 0.35%   |
| Lenovo ThinkPad X201 3626ES3                | 1         | 0.35%   |
| Lenovo ThinkPad X200 7458B64                | 1         | 0.35%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 0.35%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT    | 1         | 0.35%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002RMX    | 1         | 0.35%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQ0008VN    | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 75        | 26.5%   |
| Dell Inspiron          | 15        | 5.3%    |
| Acer Aspire            | 15        | 5.3%    |
| Lenovo IdeaPad         | 14        | 4.95%   |
| Dell XPS               | 11        | 3.89%   |
| HP ProBook             | 10        | 3.53%   |
| Apple MacBookAir7      | 9         | 3.18%   |
| HP EliteBook           | 8         | 2.83%   |
| Dell Latitude          | 8         | 2.83%   |
| HP Laptop              | 7         | 2.47%   |
| HP Compaq              | 7         | 2.47%   |
| ASUS VivoBook          | 5         | 1.77%   |
| Dell Precision         | 4         | 1.41%   |
| ASUS ZenBook           | 4         | 1.41%   |
| Toshiba Satellite      | 3         | 1.06%   |
| HP Pavilion            | 3         | 1.06%   |
| HP 250                 | 3         | 1.06%   |
| Fujitsu LIFEBOOK       | 3         | 1.06%   |
| ASUS ROG               | 3         | 1.06%   |
| Lenovo ThinkBook       | 2         | 0.71%   |
| Lenovo G50-80          | 2         | 0.71%   |
| HUAWEI NBLK-WAX9X      | 2         | 0.71%   |
| HP ZBook               | 2         | 0.71%   |
| HP OMEN                | 2         | 0.71%   |
| Google Enguarde        | 2         | 0.71%   |
| Gigabyte AERO          | 2         | 0.71%   |
| Dell Vostro            | 2         | 0.71%   |
| Apple MacBook5         | 2         | 0.71%   |
| Acer Swift             | 2         | 0.71%   |
| Acer Nitro             | 2         | 0.71%   |
| UNOWHY Y13G002S4EI     | 1         | 0.35%   |
| TUXEDO Pulse           | 1         | 0.35%   |
| Sony VPCF21AFX         | 1         | 0.35%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.35%   |
| Samsung 900X3C         | 1         | 0.35%   |
| Samsung 370E4K         | 1         | 0.35%   |
| Samsung 300E5M         | 1         | 0.35%   |
| Quanta TWC             | 1         | 0.35%   |
| Pegatron A15           | 1         | 0.35%   |
| PC Specialist NV4XMB   | 1         | 0.35%   |
| Panasonic CF-AX2LDCZMF | 1         | 0.35%   |
| Notebook NJ50          | 1         | 0.35%   |
| Notebook N13           | 1         | 0.35%   |
| MSI U90                | 1         | 0.35%   |
| MSI Modern             | 1         | 0.35%   |
| MSI GP60               | 1         | 0.35%   |
| MSI GF65               | 1         | 0.35%   |
| MSI CX700              | 1         | 0.35%   |
| Monster ABRA           | 1         | 0.35%   |
| Lenovo Yoga            | 1         | 0.35%   |
| Lenovo B51-35          | 1         | 0.35%   |
| Itautec Infoway        | 1         | 0.35%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.35%   |
| HP Stream              | 1         | 0.35%   |
| HP Split               | 1         | 0.35%   |
| HP Presario            | 1         | 0.35%   |
| HP ENVY                | 1         | 0.35%   |
| HP 630                 | 1         | 0.35%   |
| HP 2000                | 1         | 0.35%   |
| Google Stout           | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 64        | 22.61%  |
| 2021 | 56        | 19.79%  |
| 2019 | 38        | 13.43%  |
| 2018 | 19        | 6.71%   |
| 2013 | 14        | 4.95%   |
| 2012 | 13        | 4.59%   |
| 2011 | 12        | 4.24%   |
| 2008 | 11        | 3.89%   |
| 2016 | 10        | 3.53%   |
| 2017 | 9         | 3.18%   |
| 2009 | 9         | 3.18%   |
| 2015 | 8         | 2.83%   |
| 2014 | 8         | 2.83%   |
| 2010 | 3         | 1.06%   |
| 2007 | 3         | 1.06%   |
| 2006 | 2         | 0.71%   |
| 2005 | 2         | 0.71%   |
| 2004 | 2         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 283       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 246       | 86.32%  |
| Enabled  | 39        | 13.68%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 279       | 98.59%  |
| Yes  | 4         | 1.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 85        | 30.04%  |
| 16.01-24.0  | 65        | 22.97%  |
| 8.01-16.0   | 46        | 16.25%  |
| 3.01-4.0    | 38        | 13.43%  |
| 32.01-64.0  | 16        | 5.65%   |
| 1.01-2.0    | 15        | 5.3%    |
| 2.01-3.0    | 4         | 1.41%   |
| 64.01-256.0 | 4         | 1.41%   |
| 0.51-1.0    | 4         | 1.41%   |
| 0.01-0.5    | 4         | 1.41%   |
| 24.01-32.0  | 2         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 82        | 28.47%  |
| 2.01-3.0   | 70        | 24.31%  |
| 4.01-8.0   | 46        | 15.97%  |
| 3.01-4.0   | 30        | 10.42%  |
| 0.51-1.0   | 24        | 8.33%   |
| 8.01-16.0  | 22        | 7.64%   |
| 0.01-0.5   | 13        | 4.51%   |
| 32.01-64.0 | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 193       | 68.2%   |
| 2      | 81        | 28.62%  |
| 3      | 5         | 1.77%   |
| 4      | 2         | 0.71%   |
| 0      | 2         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 207       | 73.14%  |
| Yes       | 76        | 26.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 80.57%  |
| No        | 55        | 19.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 277       | 97.88%  |
| No        | 6         | 2.12%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 77.74%  |
| No        | 63        | 22.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 63        | 22.26%  |
| Germany     | 24        | 8.48%   |
| France      | 23        | 8.13%   |
| Russia      | 20        | 7.07%   |
| Spain       | 12        | 4.24%   |
| Ukraine     | 10        | 3.53%   |
| Poland      | 10        | 3.53%   |
| Brazil      | 10        | 3.53%   |
| UK          | 9         | 3.18%   |
| Switzerland | 7         | 2.47%   |
| India       | 7         | 2.47%   |
| Netherlands | 6         | 2.12%   |
| Canada      | 6         | 2.12%   |
| Turkey      | 5         | 1.77%   |
| Portugal    | 5         | 1.77%   |
| Greece      | 5         | 1.77%   |
| Thailand    | 4         | 1.41%   |
| Sweden      | 4         | 1.41%   |
| Norway      | 4         | 1.41%   |
| Kazakhstan  | 4         | 1.41%   |
| Italy       | 4         | 1.41%   |
| Belarus     | 4         | 1.41%   |
| Mexico      | 3         | 1.06%   |
| Czechia     | 3         | 1.06%   |
| Slovenia    | 2         | 0.71%   |
| Japan       | 2         | 0.71%   |
| Indonesia   | 2         | 0.71%   |
| Ecuador     | 2         | 0.71%   |
| Croatia     | 2         | 0.71%   |
| Colombia    | 2         | 0.71%   |
| China       | 2         | 0.71%   |
| Australia   | 2         | 0.71%   |
| Uruguay     | 1         | 0.35%   |
| South Sudan | 1         | 0.35%   |
| Romania     | 1         | 0.35%   |
| Philippines | 1         | 0.35%   |
| Mongolia    | 1         | 0.35%   |
| Malaysia    | 1         | 0.35%   |
| Ireland     | 1         | 0.35%   |
| Hungary     | 1         | 0.35%   |
| Finland     | 1         | 0.35%   |
| Denmark     | 1         | 0.35%   |
| Bulgaria    | 1         | 0.35%   |
| Belgium     | 1         | 0.35%   |
| Bangladesh  | 1         | 0.35%   |
| Austria     | 1         | 0.35%   |
| Argentina   | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Portland          | 33        | 11.58%  |
| St Petersburg     | 10        | 3.51%   |
| Paris             | 8         | 2.81%   |
| Berlin            | 4         | 1.4%    |
| Bengaluru         | 4         | 1.4%    |
| Bangkok           | 4         | 1.4%    |
| Zurich            | 3         | 1.05%   |
| Lyon              | 3         | 1.05%   |
| London            | 3         | 1.05%   |
| Athens            | 3         | 1.05%   |
| Yevpatoriya       | 2         | 0.7%    |
| Toronto           | 2         | 0.7%    |
| Sunnyvale         | 2         | 0.7%    |
| Sevastopol        | 2         | 0.7%    |
| S??o Paulo        | 2         | 0.7%    |
| Rio de Janeiro    | 2         | 0.7%    |
| Offenburg         | 2         | 0.7%    |
| Moscow            | 2         | 0.7%    |
| Molde             | 2         | 0.7%    |
| Mesa              | 2         | 0.7%    |
| Madrid            | 2         | 0.7%    |
| Kyiv              | 2         | 0.7%    |
| Kalamazoo         | 2         | 0.7%    |
| Istanbul          | 2         | 0.7%    |
| Halifax           | 2         | 0.7%    |
| Gorinchem         | 2         | 0.7%    |
| Gloucester        | 2         | 0.7%    |
| Fryazino          | 2         | 0.7%    |
| Denpasar          | 2         | 0.7%    |
| Ankara            | 2         | 0.7%    |
| Ajdov????ina      | 2         | 0.7%    |
| Zhuhai            | 1         | 0.35%   |
| Zaragoza          | 1         | 0.35%   |
| Zagreb            | 1         | 0.35%   |
| Wroclaw           | 1         | 0.35%   |
| Waterloo          | 1         | 0.35%   |
| Warsaw            | 1         | 0.35%   |
| Waregem           | 1         | 0.35%   |
| Vitória          | 1         | 0.35%   |
| Vitry-sur-Seine   | 1         | 0.35%   |
| Vigo              | 1         | 0.35%   |
| Vienna            | 1         | 0.35%   |
| Valladolid        | 1         | 0.35%   |
| Utrecht           | 1         | 0.35%   |
| Tyumen            | 1         | 0.35%   |
| Tyreso Strand     | 1         | 0.35%   |
| Turin             | 1         | 0.35%   |
| Touques           | 1         | 0.35%   |
| Toul              | 1         | 0.35%   |
| Thonex            | 1         | 0.35%   |
| Thermopolis       | 1         | 0.35%   |
| The Hague         | 1         | 0.35%   |
| The Colony        | 1         | 0.35%   |
| Tarn??w           | 1         | 0.35%   |
| Sydney            | 1         | 0.35%   |
| Stockholm         | 1         | 0.35%   |
| Stepnogorsk       | 1         | 0.35%   |
| Srednyaya Akhtuba | 1         | 0.35%   |
| Solymar           | 1         | 0.35%   |
| Sofia             | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 76        | 85     | 20.99%  |
| WDC                       | 39        | 45     | 10.77%  |
| Seagate                   | 32        | 36     | 8.84%   |
| Kingston                  | 25        | 27     | 6.91%   |
| Toshiba                   | 22        | 23     | 6.08%   |
| Unknown                   | 18        | 21     | 4.97%   |
| Intel                     | 14        | 14     | 3.87%   |
| Crucial                   | 14        | 14     | 3.87%   |
| SK Hynix                  | 13        | 13     | 3.59%   |
| SABRENT                   | 12        | 12     | 3.31%   |
| Hitachi                   | 11        | 11     | 3.04%   |
| Apple                     | 11        | 11     | 3.04%   |
| SanDisk                   | 7         | 9      | 1.93%   |
| A-DATA Technology         | 7         | 9      | 1.93%   |
| Micron Technology         | 6         | 6      | 1.66%   |
| China                     | 6         | 6      | 1.66%   |
| Transcend                 | 4         | 4      | 1.1%    |
| KIOXIA                    | 4         | 4      | 1.1%    |
| Fujitsu                   | 4         | 4      | 1.1%    |
| Union Memory              | 3         | 3      | 0.83%   |
| LITEONIT                  | 3         | 3      | 0.83%   |
| LITEON                    | 3         | 3      | 0.83%   |
| JMicron                   | 3         | 3      | 0.83%   |
| HGST                      | 3         | 3      | 0.83%   |
| ZTC                       | 2         | 2      | 0.55%   |
| Patriot                   | 2         | 2      | 0.55%   |
| Lenovo                    | 2         | 2      | 0.55%   |
| Intenso                   | 2         | 2      | 0.55%   |
| XPG                       | 1         | 1      | 0.28%   |
| SPCC                      | 1         | 1      | 0.28%   |
| SILICONMOTION             | 1         | 1      | 0.28%   |
| Silicon Motion            | 1         | 2      | 0.28%   |
| PNY                       | 1         | 1      | 0.28%   |
| Phison                    | 1         | 4      | 0.28%   |
| MyDigitalSSD              | 1         | 1      | 0.28%   |
| Micron/Crucial Technology | 1         | 1      | 0.28%   |
| Maxtor                    | 1         | 2      | 0.28%   |
| LDLC                      | 1         | 1      | 0.28%   |
| GOODRAM                   | 1         | 1      | 0.28%   |
| ASUS-PHISON               | 1         | 1      | 0.28%   |
| Apacer                    | 1         | 1      | 0.28%   |
| AMD                       | 1         | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SABRENT Disk 4TB                        | 12        | 3.17%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 1.32%   |
| Samsung SSD 970 EVO Plus 500GB          | 5         | 1.32%   |
| Kingston SA400S37120G 120GB SSD         | 5         | 1.32%   |
| Apple SSD SM0128G 121GB                 | 5         | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 1.06%   |
| Samsung SSD 970 EVO Plus 1TB            | 4         | 1.06%   |
| Samsung SSD 860 EVO 500GB               | 4         | 1.06%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.06%   |
| Apple SSD AP0128H 121GB                 | 4         | 1.06%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB                | 3         | 0.79%   |
| Unknown DA4064  64GB                    | 3         | 0.79%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.79%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.79%   |
| Samsung SSD 860 EVO M.2 1TB             | 3         | 0.79%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.79%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.79%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 3         | 0.79%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 0.79%   |
| Hitachi HTS543216L9A300 160GB           | 3         | 0.79%   |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.79%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.79%   |
| ZTC SM201-512G SSD                      | 2         | 0.53%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 2         | 0.53%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 2         | 0.53%   |
| Unknown HAG2e  16GB                     | 2         | 0.53%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.53%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 2         | 0.53%   |
| SK Hynix HFM001TD3JX013N 1TB            | 2         | 0.53%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 0.53%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.53%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.53%   |
| Samsung SSD 850 PRO 1TB                 | 2         | 0.53%   |
| Samsung SSD 850 EVO M.2 250GB           | 2         | 0.53%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.53%   |
| Samsung MZVLB512HAJQ-000L7 512GB        | 2         | 0.53%   |
| Samsung MZ7TE256HMHP-000L7 256GB SSD    | 2         | 0.53%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.53%   |
| Kingston SUV400S37120G 120GB SSD        | 2         | 0.53%   |
| Kingston OM8PCP3512F-AI1 512GB          | 2         | 0.53%   |
| JMicron Generic 256GB                   | 2         | 0.53%   |
| Intel SSDPEKNW010T8 1TB                 | 2         | 0.53%   |
| Hitachi HTS541040G9AT00 40GB            | 2         | 0.53%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.53%   |
| Fujitsu MHZ2160BH FFS G1 160GB          | 2         | 0.53%   |
| Crucial M4-CT256M4SSD2 256GB            | 2         | 0.53%   |
| Crucial CT1000P1SSD8 1TB                | 2         | 0.53%   |
| XPG NVMe SSD Drive 1024GB               | 1         | 0.26%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.26%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.26%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.26%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.26%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 0.26%   |
| WDC WD5000LPVX-55V0TT0 500GB            | 1         | 0.26%   |
| WDC WD5000BPVT-00HXZT3 500GB            | 1         | 0.26%   |
| WDC WD50 00LPCX-24VHA 500GB             | 1         | 0.26%   |
| WDC WD2500BEKT-00PVMT0 250GB            | 1         | 0.26%   |
| WDC WD1600BUDT-63DPZY0 160GB            | 1         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 32     | 35%     |
| WDC                 | 20        | 21     | 25%     |
| Toshiba             | 11        | 11     | 13.75%  |
| Hitachi             | 11        | 11     | 13.75%  |
| Fujitsu             | 4         | 4      | 5%      |
| HGST                | 3         | 3      | 3.75%   |
| Samsung Electronics | 2         | 2      | 2.5%    |
| SILICONMOTION       | 1         | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 47     | 28.19%  |
| Kingston            | 17        | 19     | 11.41%  |
| SABRENT             | 12        | 12     | 8.05%   |
| Crucial             | 10        | 10     | 6.71%   |
| Intel               | 7         | 7      | 4.7%    |
| Apple               | 7         | 7      | 4.7%    |
| SanDisk             | 6         | 8      | 4.03%   |
| China               | 6         | 6      | 4.03%   |
| Transcend           | 4         | 4      | 2.68%   |
| WDC                 | 3         | 5      | 2.01%   |
| SK Hynix            | 3         | 3      | 2.01%   |
| LITEONIT            | 3         | 3      | 2.01%   |
| A-DATA Technology   | 3         | 3      | 2.01%   |
| ZTC                 | 2         | 2      | 1.34%   |
| Toshiba             | 2         | 2      | 1.34%   |
| Seagate             | 2         | 2      | 1.34%   |
| Patriot             | 2         | 2      | 1.34%   |
| Micron Technology   | 2         | 2      | 1.34%   |
| LITEON              | 2         | 2      | 1.34%   |
| JMicron             | 2         | 2      | 1.34%   |
| Intenso             | 2         | 2      | 1.34%   |
| Union Memory        | 1         | 1      | 0.67%   |
| SPCC                | 1         | 1      | 0.67%   |
| PNY                 | 1         | 1      | 0.67%   |
| MyDigitalSSD        | 1         | 1      | 0.67%   |
| Maxtor              | 1         | 2      | 0.67%   |
| LDLC                | 1         | 1      | 0.67%   |
| GOODRAM             | 1         | 1      | 0.67%   |
| ASUS-PHISON         | 1         | 1      | 0.67%   |
| Apacer              | 1         | 1      | 0.67%   |
| AMD                 | 1         | 2      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 135       | 162    | 39.24%  |
| NVMe    | 108       | 126    | 31.4%   |
| HDD     | 80        | 85     | 23.26%  |
| MMC     | 17        | 20     | 4.94%   |
| Unknown | 4         | 4      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 181       | 225    | 55.02%  |
| NVMe | 108       | 126    | 32.83%  |
| SAS  | 23        | 26     | 6.99%   |
| MMC  | 17        | 20     | 5.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 140       | 165    | 64.52%  |
| 0.51-1.0   | 57        | 61     | 26.27%  |
| 3.01-4.0   | 13        | 13     | 5.99%   |
| 1.01-2.0   | 6         | 7      | 2.76%   |
| 2.01-3.0   | 1         | 1      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 91        | 31.93%  |
| 251-500        | 61        | 21.4%   |
| 501-1000       | 38        | 13.33%  |
| 1001-2000      | 24        | 8.42%   |
| 1-20           | 24        | 8.42%   |
| 51-100         | 16        | 5.61%   |
| 21-50          | 12        | 4.21%   |
| Unknown        | 11        | 3.86%   |
| More than 3000 | 6         | 2.11%   |
| 2001-3000      | 2         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 99        | 34.38%  |
| 21-50     | 40        | 13.89%  |
| 101-250   | 39        | 13.54%  |
| 51-100    | 37        | 12.85%  |
| 251-500   | 29        | 10.07%  |
| 501-1000  | 20        | 6.94%   |
| Unknown   | 11        | 3.82%   |
| 1001-2000 | 9         | 3.13%   |
| 0         | 3         | 1.04%   |
| 2001-3000 | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 2      | 6.25%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 3.13%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 3.13%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 3.13%   |
| Seagate ST960822A 64GB                         | 1         | 1      | 3.13%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 3.13%   |
| Seagate ST9160310AS 160GB                      | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 3.13%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 3.13%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 850 EVO 1TB            | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 2      | 3.13%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 3.13%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.13%   |
| LITEONIT LMT-64M6M-HP 64GB SSD                 | 1         | 1      | 3.13%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 3.13%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 1      | 3.13%   |
| Intel SSDSC2KW120H6 120GB                      | 1         | 1      | 3.13%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 3.13%   |
| Intel SSDSA2M160G2HP 160GB                     | 1         | 1      | 3.13%   |
| Intel SSDPEKKF256G7H 256GB                     | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 3.13%   |
| Hitachi HTS543212L9A300 120GB                  | 1         | 1      | 3.13%   |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 3.13%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 3.13%   |
| Hitachi HTS541040G9AT00 40GB                   | 1         | 1      | 3.13%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 3.13%   |
| A-DATA Technology SU630 480GB SSD              | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 21.88%  |
| Hitachi             | 5         | 5      | 15.63%  |
| Samsung Electronics | 4         | 5      | 12.5%   |
| Intel               | 4         | 4      | 12.5%   |
| WDC                 | 3         | 3      | 9.38%   |
| Toshiba             | 3         | 3      | 9.38%   |
| Kingston            | 2         | 2      | 6.25%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 35%     |
| Hitachi             | 5         | 5      | 25%     |
| WDC                 | 3         | 3      | 15%     |
| Toshiba             | 3         | 3      | 15%     |
| Samsung Electronics | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 20     | 62.5%   |
| SSD  | 11        | 12     | 34.38%  |
| NVMe | 1         | 1      | 3.13%   |

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
| Works    | 228       | 286    | 72.15%  |
| Detected | 56        | 78     | 17.72%  |
| Malfunc  | 32        | 33     | 10.13%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 182       | 55.83%  |
| Samsung Electronics          | 41        | 12.58%  |
| AMD                          | 27        | 8.28%   |
| Sandisk                      | 18        | 5.52%   |
| SK Hynix                     | 10        | 3.07%   |
| Toshiba America Info Systems | 8         | 2.45%   |
| Kingston Technology Company  | 8         | 2.45%   |
| Micron/Crucial Technology    | 5         | 1.53%   |
| KIOXIA                       | 5         | 1.53%   |
| Micron Technology            | 4         | 1.23%   |
| Apple                        | 4         | 1.23%   |
| ADATA Technology             | 4         | 1.23%   |
| Nvidia                       | 3         | 0.92%   |
| Union Memory (Shenzhen)      | 2         | 0.61%   |
| Lenovo                       | 2         | 0.61%   |
| Silicon Motion               | 1         | 0.31%   |
| Phison Electronics           | 1         | 0.31%   |
| Lite-On Technology           | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 8.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 24        | 6.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 23        | 6.69%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 6.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 4.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 3.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 3.2%    |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 2.33%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 6         | 1.74%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 1.74%   |
| Samsung NVMe Controller                                                          | 6         | 1.74%   |
| Samsung Electronics SATA controller                                              | 6         | 1.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.74%   |
| KIOXIA Non-Volatile memory controller                                            | 5         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.45%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 4         | 1.16%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.16%   |
| Intel SSD 660P Series                                                            | 4         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.16%   |
| Apple S1X NVMe Controller                                                        | 4         | 1.16%   |
| SK Hynix NVMe SSD Controller                                                     | 3         | 0.87%   |
| SK Hynix BC511                                                                   | 3         | 0.87%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.87%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.87%   |
| Sandisk Non-Volatile memory controller                                           | 3         | 0.87%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.87%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 3         | 0.87%   |
| AMD IXP SB4x0 IDE Controller                                                     | 3         | 0.87%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.58%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.58%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.58%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.58%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.58%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.58%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.58%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.58%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.58%   |
| Intel SSD 600P Series                                                            | 2         | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.58%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 0.58%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 0.58%   |
| ADATA Non-Volatile memory controller                                             | 2         | 0.58%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.29%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.29%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 180       | 53.73%  |
| NVMe | 108       | 32.24%  |
| RAID | 25        | 7.46%   |
| IDE  | 22        | 6.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 241       | 85.16%  |
| AMD    | 42        | 14.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 9         | 3.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 2.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 2.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 2.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 2.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 2.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 2.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 2.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 1.77%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 1.77%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.41%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.41%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 1.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.41%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.06%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1.06%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 3         | 1.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.06%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.06%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.71%   |
| Intel Genuine CPU T1400 @ 1.73GHz             | 2         | 0.71%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.71%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.71%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.71%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.71%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.71%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.71%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.71%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.71%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.71%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.71%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.71%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 2         | 0.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.71%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 0.71%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 2         | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.71%   |
| Intel Celeron M processor 900MHz              | 2         | 0.71%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.71%   |
| Intel Celeron CPU B800 @ 1.50GHz              | 2         | 0.71%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 2         | 0.71%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 0.71%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 89        | 31.45%  |
| Intel Core i7        | 73        | 25.8%   |
| Other                | 19        | 6.71%   |
| Intel Celeron        | 15        | 5.3%    |
| Intel Core 2 Duo     | 14        | 4.95%   |
| Intel Core i3        | 12        | 4.24%   |
| AMD Ryzen 5          | 12        | 4.24%   |
| AMD Ryzen 7          | 8         | 2.83%   |
| AMD Ryzen 7 PRO      | 7         | 2.47%   |
| Intel Pentium        | 6         | 2.12%   |
| Intel Pentium M      | 4         | 1.41%   |
| Intel Celeron M      | 3         | 1.06%   |
| Intel Genuine        | 2         | 0.71%   |
| Intel Core 2         | 2         | 0.71%   |
| Intel Atom           | 2         | 0.71%   |
| AMD Turion 64 Mobile | 2         | 0.71%   |
| AMD Ryzen 9          | 2         | 0.71%   |
| AMD Ryzen 3          | 2         | 0.71%   |
| AMD A8               | 2         | 0.71%   |
| Intel Xeon           | 1         | 0.35%   |
| Intel Pentium Gold   | 1         | 0.35%   |
| Intel Pentium Dual   | 1         | 0.35%   |
| AMD C-30             | 1         | 0.35%   |
| AMD Athlon 64        | 1         | 0.35%   |
| AMD Athlon           | 1         | 0.35%   |
| AMD A12              | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 143       | 50.53%  |
| 4      | 91        | 32.16%  |
| 6      | 17        | 6.01%   |
| 8      | 16        | 5.65%   |
| 1      | 16        | 5.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 283       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 221       | 78.09%  |
| 1      | 62        | 21.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 274       | 96.82%  |
| 32-bit         | 9         | 3.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 16.84%  |
| 0x306a9    | 24        | 8.42%   |
| 0x306d4    | 21        | 7.37%   |
| 0x206a7    | 20        | 7.02%   |
| 0x806c1    | 15        | 5.26%   |
| 0x806e9    | 13        | 4.56%   |
| 0x806ec    | 12        | 4.21%   |
| 0x806ea    | 12        | 4.21%   |
| 0xa0652    | 8         | 2.81%   |
| 0x906ea    | 8         | 2.81%   |
| 0x1067a    | 8         | 2.81%   |
| 0x08600106 | 8         | 2.81%   |
| 0x706e5    | 7         | 2.46%   |
| 0x406e3    | 7         | 2.46%   |
| 0x40651    | 7         | 2.46%   |
| 0x08108109 | 6         | 2.11%   |
| 0x806eb    | 5         | 1.75%   |
| 0x6d8      | 5         | 1.75%   |
| 0x6fd      | 4         | 1.4%    |
| 0x506c9    | 4         | 1.4%    |
| 0x20655    | 4         | 1.4%    |
| 0x306c3    | 3         | 1.05%   |
| 0x0600611a | 3         | 1.05%   |
| 0x906e9    | 2         | 0.7%    |
| 0x706a8    | 2         | 0.7%    |
| 0x6fa      | 2         | 0.7%    |
| 0x6f6      | 2         | 0.7%    |
| 0x695      | 2         | 0.7%    |
| 0x30678    | 2         | 0.7%    |
| 0x106c2    | 2         | 0.7%    |
| 0x0a50000b | 2         | 0.7%    |
| 0x08600104 | 2         | 0.7%    |
| 0x08600103 | 2         | 0.7%    |
| 0x08108102 | 2         | 0.7%    |
| 0x406c4    | 1         | 0.35%   |
| 0x406c3    | 1         | 0.35%   |
| 0x40661    | 1         | 0.35%   |
| 0x10676    | 1         | 0.35%   |
| 0x10661    | 1         | 0.35%   |
| 0x08608103 | 1         | 0.35%   |
| 0x0810100b | 1         | 0.35%   |
| 0x07030105 | 1         | 0.35%   |
| 0x06006705 | 1         | 0.35%   |
| 0x05000029 | 1         | 0.35%   |
| 0x03000027 | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 63        | 22.26%  |
| IvyBridge     | 28        | 9.89%   |
| Broadwell     | 21        | 7.42%   |
| SandyBridge   | 20        | 7.07%   |
| Haswell       | 18        | 6.36%   |
| TigerLake     | 17        | 6.01%   |
| Zen 2         | 15        | 5.3%    |
| Zen+          | 11        | 3.89%   |
| Skylake       | 11        | 3.89%   |
| Penryn        | 10        | 3.53%   |
| Core          | 10        | 3.53%   |
| CometLake     | 9         | 3.18%   |
| Westmere      | 8         | 2.83%   |
| P6            | 7         | 2.47%   |
| IceLake       | 7         | 2.47%   |
| Silvermont    | 4         | 1.41%   |
| Goldmont      | 4         | 1.41%   |
| Excavator     | 4         | 1.41%   |
| Zen 3         | 3         | 1.06%   |
| K8 Hammer     | 3         | 1.06%   |
| Zen           | 2         | 0.71%   |
| Goldmont plus | 2         | 0.71%   |
| Bonnell       | 2         | 0.71%   |
| Puma          | 1         | 0.35%   |
| K10 Llano     | 1         | 0.35%   |
| Bobcat        | 1         | 0.35%   |
| Unknown       | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 227       | 65.61%  |
| Nvidia | 60        | 17.34%  |
| AMD    | 59        | 17.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 7.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 4.99%   |
| Intel UHD Graphics 620                                                                   | 16        | 4.43%   |
| AMD Renoir                                                                               | 15        | 4.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 3.88%   |
| Intel HD Graphics 620                                                                    | 12        | 3.32%   |
| Intel HD Graphics 5500                                                                   | 12        | 3.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 3.05%   |
| AMD Picasso                                                                              | 11        | 3.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.77%   |
| Intel HD Graphics 6000                                                                   | 9         | 2.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.66%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 1.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.11%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 1.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.11%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.83%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.83%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.83%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.83%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.83%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 3         | 0.83%   |
| AMD Cezanne                                                                              | 3         | 0.83%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.55%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.55%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.55%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.55%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.55%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.55%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.55%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.55%   |
| Intel HD Graphics 630                                                                    | 2         | 0.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.55%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.55%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.55%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                                         | 2         | 0.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.28%   |
| Nvidia TU117M                                                                            | 1         | 0.28%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.28%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.28%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 168       | 58.95%  |
| Intel + Nvidia | 48        | 16.84%  |
| 1 x AMD        | 41        | 14.39%  |
| Intel + AMD    | 11        | 3.86%   |
| 1 x Nvidia     | 9         | 3.16%   |
| AMD + Nvidia   | 4         | 1.4%    |
| 2 x AMD        | 3         | 1.05%   |
| Other          | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 258       | 90.85%  |
| Proprietary | 23        | 8.1%    |
| Unknown     | 3         | 1.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 218       | 76.22%  |
| 0.01-0.5   | 29        | 10.14%  |
| 1.01-2.0   | 14        | 4.9%    |
| 0.51-1.0   | 14        | 4.9%    |
| 3.01-4.0   | 9         | 3.15%   |
| 7.01-8.0   | 1         | 0.35%   |
| 5.01-6.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 63        | 19.27%  |
| Chimei Innolux          | 47        | 14.37%  |
| BOE                     | 44        | 13.46%  |
| LG Display              | 40        | 12.23%  |
| Samsung Electronics     | 23        | 7.03%   |
| Apple                   | 17        | 5.2%    |
| Sharp                   | 13        | 3.98%   |
| Lenovo                  | 12        | 3.67%   |
| Dell                    | 9         | 2.75%   |
| Hewlett-Packard         | 5         | 1.53%   |
| Ancor Communications    | 5         | 1.53%   |
| ViewSonic               | 4         | 1.22%   |
| InfoVision              | 4         | 1.22%   |
| Chi Mei Optoelectronics | 4         | 1.22%   |
| BenQ                    | 4         | 1.22%   |
| PANDA                   | 3         | 0.92%   |
| LG Philips              | 3         | 0.92%   |
| Goldstar                | 3         | 0.92%   |
| Unknown                 | 2         | 0.61%   |
| Philips                 | 2         | 0.61%   |
| NEC Computers           | 2         | 0.61%   |
| HannStar                | 2         | 0.61%   |
| CPT                     | 2         | 0.61%   |
| AOC                     | 2         | 0.61%   |
| ___                     | 1         | 0.31%   |
| Vestel Elektronik       | 1         | 0.31%   |
| NCS                     | 1         | 0.31%   |
| MSI                     | 1         | 0.31%   |
| LPL                     | 1         | 0.31%   |
| JXG                     | 1         | 0.31%   |
| JRY                     | 1         | 0.31%   |
| IOD                     | 1         | 0.31%   |
| CSO                     | 1         | 0.31%   |
| CMN                     | 1         | 0.31%   |
| ASUSTek Computer        | 1         | 0.31%   |
| Acer                    | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 4         | 1.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 4         | 1.21%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 4         | 1.21%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 3         | 0.91%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.91%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 3         | 0.91%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.91%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 3         | 0.91%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 3         | 0.91%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 2         | 0.6%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                   | 2         | 0.6%    |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.6%    |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch               | 2         | 0.6%    |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch               | 2         | 0.6%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 2         | 0.6%    |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 0.6%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.6%    |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 2         | 0.6%    |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                     | 2         | 0.6%    |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 2         | 0.6%    |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 2         | 0.6%    |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 2         | 0.6%    |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch            | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch            | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 2         | 0.6%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 0.6%    |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 2         | 0.6%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 2         | 0.6%    |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch     | 2         | 0.6%    |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                        | 1         | 0.3%    |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch             | 1         | 0.3%    |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch                 | 1         | 0.3%    |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                    | 1         | 0.3%    |
| ViewSonic LCD Monitor XG2401 SERIES                                       | 1         | 0.3%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 1         | 0.3%    |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                       | 1         | 0.3%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.3%    |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch                   | 1         | 0.3%    |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 1         | 0.3%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 1         | 0.3%    |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                   | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 142       | 45.08%  |
| 1366x768 (WXGA)    | 73        | 23.17%  |
| 1280x800 (WXGA)    | 18        | 5.71%   |
| 1600x900 (HD+)     | 16        | 5.08%   |
| 3840x2160 (4K)     | 11        | 3.49%   |
| 1920x1200 (WUXGA)  | 11        | 3.49%   |
| 1440x900 (WXGA+)   | 10        | 3.17%   |
| 2560x1440 (QHD)    | 8         | 2.54%   |
| 1280x1024 (SXGA)   | 5         | 1.59%   |
| 1024x768 (XGA)     | 4         | 1.27%   |
| 1680x1050 (WSXGA+) | 3         | 0.95%   |
| 3440x1440          | 2         | 0.63%   |
| 1024x600           | 2         | 0.63%   |
| 3840x2400          | 1         | 0.32%   |
| 3840x1080          | 1         | 0.32%   |
| 3200x1800 (QHD+)   | 1         | 0.32%   |
| 2880x1800          | 1         | 0.32%   |
| 2560x1600          | 1         | 0.32%   |
| 2288x1287          | 1         | 0.32%   |
| 2256x1504          | 1         | 0.32%   |
| 1792x768           | 1         | 0.32%   |
| 1600x1200          | 1         | 0.32%   |
| Unknown            | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 100       | 30.58%  |
| 13      | 71        | 21.71%  |
| 14      | 45        | 13.76%  |
| 17      | 21        | 6.42%   |
| 12      | 17        | 5.2%    |
| 11      | 14        | 4.28%   |
| 24      | 12        | 3.67%   |
| 21      | 9         | 2.75%   |
| 23      | 8         | 2.45%   |
| 25      | 4         | 1.22%   |
| 27      | 3         | 0.92%   |
| 19      | 3         | 0.92%   |
| 34      | 2         | 0.61%   |
| 31      | 2         | 0.61%   |
| 10      | 2         | 0.61%   |
| Unknown | 2         | 0.61%   |
| 142     | 1         | 0.31%   |
| 84      | 1         | 0.31%   |
| 72      | 1         | 0.31%   |
| 47      | 1         | 0.31%   |
| 46      | 1         | 0.31%   |
| 40      | 1         | 0.31%   |
| 33      | 1         | 0.31%   |
| 32      | 1         | 0.31%   |
| 22      | 1         | 0.31%   |
| 20      | 1         | 0.31%   |
| 18      | 1         | 0.31%   |
| 16      | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 181       | 55.35%  |
| 201-300        | 68        | 20.8%   |
| 501-600        | 24        | 7.34%   |
| 351-400        | 23        | 7.03%   |
| 401-500        | 15        | 4.59%   |
| 701-800        | 4         | 1.22%   |
| 601-700        | 4         | 1.22%   |
| 1501-2000      | 2         | 0.61%   |
| 1001-1500      | 2         | 0.61%   |
| Unknown        | 2         | 0.61%   |
| More than 2000 | 1         | 0.31%   |
| 801-900        | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 234       | 78.79%  |
| 16/10   | 42        | 14.14%  |
| 4/3     | 6         | 2.02%   |
| 5/4     | 5         | 1.68%   |
| 3/2     | 4         | 1.35%   |
| 21/9    | 3         | 1.01%   |
| Unknown | 2         | 0.67%   |
| 1.00    | 1         | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 30.79%  |
| 81-90          | 90        | 27.44%  |
| 71-80          | 27        | 8.23%   |
| 201-250        | 23        | 7.01%   |
| 121-130        | 17        | 5.18%   |
| 61-70          | 16        | 4.88%   |
| 51-60          | 14        | 4.27%   |
| 251-300        | 9         | 2.74%   |
| 351-500        | 6         | 1.83%   |
| 151-200        | 6         | 1.83%   |
| 141-150        | 5         | 1.52%   |
| More than 1000 | 3         | 0.91%   |
| 301-350        | 3         | 0.91%   |
| 501-1000       | 3         | 0.91%   |
| 41-50          | 2         | 0.61%   |
| Unknown        | 2         | 0.61%   |
| 131-140        | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 169       | 52.81%  |
| 101-120       | 66        | 20.63%  |
| 51-100        | 52        | 16.25%  |
| 161-240       | 20        | 6.25%   |
| More than 240 | 7         | 2.19%   |
| 1-50          | 4         | 1.25%   |
| Unknown       | 2         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 228       | 80.28%  |
| 2     | 47        | 16.55%  |
| 3     | 5         | 1.76%   |
| 0     | 4         | 1.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 176       | 40.55%  |
| Realtek Semiconductor             | 124       | 28.57%  |
| Qualcomm Atheros                  | 52        | 11.98%  |
| Broadcom                          | 27        | 6.22%   |
| Broadcom Limited                  | 16        | 3.69%   |
| Marvell Technology Group          | 5         | 1.15%   |
| Ericsson Business Mobile Networks | 4         | 0.92%   |
| Sierra Wireless                   | 3         | 0.69%   |
| Nvidia                            | 3         | 0.69%   |
| AMD                               | 3         | 0.69%   |
| Ralink                            | 2         | 0.46%   |
| DisplayLink                       | 2         | 0.46%   |
| Dell                              | 2         | 0.46%   |
| Cypress Semiconductor             | 2         | 0.46%   |
| Xiaomi                            | 1         | 0.23%   |
| Qualcomm Atheros Communications   | 1         | 0.23%   |
| Qualcomm                          | 1         | 0.23%   |
| Microchip Technology              | 1         | 0.23%   |
| MEDIATEK                          | 1         | 0.23%   |
| Lenovo                            | 1         | 0.23%   |
| JMicron Technology                | 1         | 0.23%   |
| Huawei Technologies               | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| Fibocom                           | 1         | 0.23%   |
| Edimax Technology                 | 1         | 0.23%   |
| D-Link                            | 1         | 0.23%   |
| Attansic Technology               | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 84        | 15.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 22        | 4.07%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 2.77%   |
| Intel Wireless 8265 / 8275                                              | 15        | 2.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 2.4%    |
| Intel Wireless 7260                                                     | 10        | 1.85%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.66%   |
| Intel Wireless 7265                                                     | 9         | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.66%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 9         | 1.66%   |
| Intel Wireless 8260                                                     | 8         | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.29%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.29%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 0.92%   |
| Intel Wireless 3160                                                     | 5         | 0.92%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.92%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.74%   |
| Intel Wireless 3165                                                     | 4         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                   | 4         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.74%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.55%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.55%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.55%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 3         | 0.55%   |
| AMD IXP SB400 AC'97 Modem Controller                                    | 3         | 0.55%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.37%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.37%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.37%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.37%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.37%   |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                                  | 2         | 0.37%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 171       | 59.38%  |
| Qualcomm Atheros                  | 46        | 15.97%  |
| Realtek Semiconductor             | 32        | 11.11%  |
| Broadcom Limited                  | 14        | 4.86%   |
| Broadcom                          | 14        | 4.86%   |
| Sierra Wireless                   | 3         | 1.04%   |
| Ralink                            | 2         | 0.69%   |
| Qualcomm Atheros Communications   | 1         | 0.35%   |
| Qualcomm                          | 1         | 0.35%   |
| MEDIATEK                          | 1         | 0.35%   |
| Fibocom                           | 1         | 0.35%   |
| Ericsson Business Mobile Networks | 1         | 0.35%   |
| Edimax Technology                 | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 20        | 6.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 15        | 5.19%   |
| Intel Wireless 8265 / 8275                                                            | 15        | 5.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 13        | 4.5%    |
| Intel Wireless 7260                                                                   | 10        | 3.46%   |
| Intel Wi-Fi 6 AX201                                                                   | 10        | 3.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 9         | 3.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 9         | 3.11%   |
| Intel Wireless 7265                                                                   | 9         | 3.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 9         | 3.11%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 9         | 3.11%   |
| Intel Wireless 8260                                                                   | 8         | 2.77%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 8         | 2.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 7         | 2.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 7         | 2.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 7         | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 7         | 2.42%   |
| Intel Centrino Ultimate-N 6300                                                        | 6         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 6         | 2.08%   |
| Intel Wireless 3160                                                                   | 5         | 1.73%   |
| Intel Centrino Wireless-N 2230                                                        | 5         | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 4         | 1.38%   |
| Intel Wireless 3165                                                                   | 4         | 1.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 4         | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 1.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3         | 1.04%   |
| Intel Wireless-AC 9260                                                                | 3         | 1.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 3         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 1.04%   |
| Intel Centrino Advanced-N 6200                                                        | 3         | 1.04%   |
| Sierra Wireless EM7345 4G LTE                                                         | 2         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2         | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.69%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 0.69%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                             | 2         | 0.69%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 0.69%   |
| Broadcom Limited BCM4318 [AirForce 54g] 802.11a/b/g PCI Express Transceiver           | 2         | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 0.69%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 2         | 0.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 2         | 0.69%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller                   | 2         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 2         | 0.69%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                                   | 1         | 0.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.35%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.35%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.35%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.35%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.35%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                           | 1         | 0.35%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.35%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.35%   |
| MEDIATEK Network controller                                                           | 1         | 0.35%   |
| Intel Wireless Gigabit 17265                                                          | 1         | 0.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 108       | 45.57%  |
| Intel                    | 79        | 33.33%  |
| Broadcom                 | 16        | 6.75%   |
| Qualcomm Atheros         | 12        | 5.06%   |
| Marvell Technology Group | 5         | 2.11%   |
| Nvidia                   | 3         | 1.27%   |
| Broadcom Limited         | 3         | 1.27%   |
| DisplayLink              | 2         | 0.84%   |
| Cypress Semiconductor    | 2         | 0.84%   |
| Xiaomi                   | 1         | 0.42%   |
| Microchip Technology     | 1         | 0.42%   |
| Lenovo                   | 1         | 0.42%   |
| JMicron Technology       | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| D-Link                   | 1         | 0.42%   |
| Attansic Technology      | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84        | 35.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 9.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 5.86%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 2.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 2.93%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.09%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.09%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.09%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.26%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 1.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.84%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.84%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.84%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.84%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.84%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.84%   |
| Cypress K38231_03                                                 | 2         | 0.84%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.84%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.84%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.42%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.42%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.42%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.42%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.42%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.42%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.42%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.42%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.42%   |
| Intel 82801DB PRO/100 VM (MOB) Ethernet Controller                | 1         | 0.42%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.42%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.42%   |
| Huawei E353/E3131                                                 | 1         | 0.42%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 0.42%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 277       | 53.47%  |
| Ethernet | 228       | 44.02%  |
| Modem    | 13        | 2.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 263       | 62.32%  |
| Ethernet | 157       | 37.2%   |
| Modem    | 2         | 0.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 209       | 73.85%  |
| 1     | 69        | 24.38%  |
| 3     | 5         | 1.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 228       | 80.28%  |
| Yes  | 56        | 19.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 114       | 51.58%  |
| Realtek Semiconductor           | 19        | 8.6%    |
| Qualcomm Atheros Communications | 19        | 8.6%    |
| Broadcom                        | 16        | 7.24%   |
| Apple                           | 16        | 7.24%   |
| Lite-On Technology              | 11        | 4.98%   |
| IMC Networks                    | 5         | 2.26%   |
| Foxconn / Hon Hai               | 5         | 2.26%   |
| Hewlett-Packard                 | 4         | 1.81%   |
| Realtek                         | 3         | 1.36%   |
| Cambridge Silicon Radio         | 3         | 1.36%   |
| Toshiba                         | 2         | 0.9%    |
| Dell                            | 2         | 0.9%    |
| Taiyo Yuden                     | 1         | 0.45%   |
| Ralink                          | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 39        | 17.65%  |
| Intel Bluetooth wireless interface                  | 28        | 12.67%  |
| Intel AX200 Bluetooth                               | 21        | 9.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 5.88%   |
| Realtek Bluetooth Radio                             | 12        | 5.43%   |
| Apple Bluetooth USB Host Controller                 | 9         | 4.07%   |
| Lite-On Bluetooth Device                            | 7         | 3.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 2.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 2.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.81%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.36%   |
| Realtek Bluetooth Radio                             | 3         | 1.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.36%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.36%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.36%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.36%   |
| Apple Bluetooth Host Controller                     | 3         | 1.36%   |
| Toshiba Bluetooth Device                            | 2         | 0.9%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.9%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.9%    |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 2         | 0.9%    |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.45%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.45%   |
| Realtek CSR BS8510                                  | 1         | 0.45%   |
| Realtek 802.11n WLAN Adapter                        | 1         | 0.45%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.45%   |
| Lite-On Wireless_Device                             | 1         | 0.45%   |
| Lite-On BCM43142A0                                  | 1         | 0.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.45%   |
| IMC Networks Bluetooth Device                       | 1         | 0.45%   |
| IMC Networks Bluetooth                              | 1         | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.45%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.45%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.45%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 238       | 70.41%  |
| AMD                    | 46        | 13.61%  |
| Nvidia                 | 33        | 9.76%   |
| Generalplus Technology | 4         | 1.18%   |
| Plantronics            | 3         | 0.89%   |
| Logitech               | 3         | 0.89%   |
| GN Netcom              | 3         | 0.89%   |
| C-Media Electronics    | 3         | 0.89%   |
| Texas Instruments      | 2         | 0.59%   |
| Razer USA              | 1         | 0.3%    |
| Lenovo                 | 1         | 0.3%    |
| Creative Technology    | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 41        | 9.88%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 32        | 7.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 7.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 5.06%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 5.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 4.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 4.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 3.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.89%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 2.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.96%   |
| Generalplus Technology Usb Audio Device                                                           | 4         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.72%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.72%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.72%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.48%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.48%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.48%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.48%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.48%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.24%   |
| Plantronics DA40                                                                                  | 1         | 0.24%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.24%   |
| Plantronics Blackwire 315.1                                                                       | 1         | 0.24%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.24%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.24%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.24%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.24%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.24%   |
| Nvidia Audio device                                                                               | 1         | 0.24%   |
| Logitech [G533 Wireless Headset Dongle]                                                           | 1         | 0.24%   |
| Logitech USB Headset                                                                              | 1         | 0.24%   |
| Logitech Headset H340                                                                             | 1         | 0.24%   |
| Lenovo ThinkPad Dock Audio                                                                        | 1         | 0.24%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 81        | 25.96%  |
| Samsung Electronics | 80        | 25.64%  |
| Micron Technology   | 31        | 9.94%   |
| Kingston            | 28        | 8.97%   |
| Unknown             | 22        | 7.05%   |
| Crucial             | 22        | 7.05%   |
| A-DATA Technology   | 9         | 2.88%   |
| Ramaxel Technology  | 8         | 2.56%   |
| Corsair             | 7         | 2.24%   |
| Nanya Technology    | 6         | 1.92%   |
| Elpida              | 5         | 1.6%    |
| Team                | 2         | 0.64%   |
| Smart               | 2         | 0.64%   |
| Unknown (ABCD)      | 1         | 0.32%   |
| Unifosa             | 1         | 0.32%   |
| SMART Brazil        | 1         | 0.32%   |
| PNY                 | 1         | 0.32%   |
| Kllisre             | 1         | 0.32%   |
| Infineon            | 1         | 0.32%   |
| GOODRAM             | 1         | 0.32%   |
| G.Skill             | 1         | 0.32%   |
| AMD                 | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 6         | 1.83%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 1.53%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 1.22%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.22%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.22%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 1.22%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.22%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 4         | 1.22%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.92%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.92%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 3         | 0.92%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.92%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 0.92%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                       | 3         | 0.92%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.92%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 3         | 0.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.92%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s          | 3         | 0.92%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.92%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.61%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 2         | 0.61%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 2         | 0.61%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 2         | 0.61%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.61%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.61%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.61%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.61%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.61%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.61%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.61%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.61%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.61%   |
| Samsung RAM M4 70L6524CU0-CB3 512MB SODIMM DDR 333MT/s           | 2         | 0.61%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 2         | 0.61%   |
| Nanya RAM NT512D64SH8B0GN-6K 512MB SODIMM DDR 333MT/s            | 2         | 0.61%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.61%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 2         | 0.61%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.61%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.61%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 2         | 0.61%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                           | 1         | 0.31%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.31%   |
| Unknown SODIMM 1GB SODIMM DDR2 667MT/s                           | 1         | 0.31%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.31%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.31%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.31%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.31%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.31%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 117       | 44.15%  |
| DDR3   | 100       | 37.74%  |
| DDR2   | 18        | 6.79%   |
| LPDDR3 | 13        | 4.91%   |
| LPDDR4 | 7         | 2.64%   |
| DDR    | 6         | 2.26%   |
| SDRAM  | 3         | 1.13%   |
| DRAM   | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 240       | 90.57%  |
| Row Of Chips | 22        | 8.3%    |
| Chip         | 2         | 0.75%   |
| Unknown      | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 97        | 33.8%   |
| 8192  | 91        | 31.71%  |
| 16384 | 38        | 13.24%  |
| 2048  | 26        | 9.06%   |
| 1024  | 19        | 6.62%   |
| 32768 | 8         | 2.79%   |
| 512   | 6         | 2.09%   |
| 256   | 2         | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 72        | 25.44%  |
| 2667    | 56        | 19.79%  |
| 3200    | 42        | 14.84%  |
| 2400    | 22        | 7.77%   |
| 1334    | 18        | 6.36%   |
| 2133    | 17        | 6.01%   |
| 1333    | 14        | 4.95%   |
| 667     | 8         | 2.83%   |
| 1867    | 6         | 2.12%   |
| 533     | 5         | 1.77%   |
| Unknown | 5         | 1.77%   |
| 333     | 4         | 1.41%   |
| 4267    | 3         | 1.06%   |
| 400     | 3         | 1.06%   |
| 1067    | 2         | 0.71%   |
| 800     | 2         | 0.71%   |
| 4266    | 1         | 0.35%   |
| 4199    | 1         | 0.35%   |
| 1866    | 1         | 0.35%   |
| 975     | 1         | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 55        | 23.61%  |
| IMC Networks                           | 36        | 15.45%  |
| Acer                                   | 28        | 12.02%  |
| Realtek Semiconductor                  | 20        | 8.58%   |
| Microdia                               | 19        | 8.15%   |
| Quanta                                 | 12        | 5.15%   |
| Lite-On Technology                     | 10        | 4.29%   |
| Sunplus Innovation Technology          | 8         | 3.43%   |
| Suyin                                  | 7         | 3%      |
| Logitech                               | 5         | 2.15%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.15%   |
| Apple                                  | 5         | 2.15%   |
| Syntek                                 | 4         | 1.72%   |
| Luxvisions Innotech Limited            | 4         | 1.72%   |
| Lenovo                                 | 4         | 1.72%   |
| Silicon Motion                         | 2         | 0.86%   |
| Z-Star Microelectronics                | 1         | 0.43%   |
| Ricoh                                  | 1         | 0.43%   |
| Primax Electronics                     | 1         | 0.43%   |
| Pixart Imaging                         | 1         | 0.43%   |
| eMPIA Technology                       | 1         | 0.43%   |
| ALi                                    | 1         | 0.43%   |
| Alcor Micro                            | 1         | 0.43%   |
| A4Tech                                 | 1         | 0.43%   |
| 8SSC20F27114V1SR11K1SE2                | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 20        | 8.55%   |
| IMC Networks Integrated Camera                                             | 13        | 5.56%   |
| Realtek Integrated_Webcam_HD                                               | 10        | 4.27%   |
| Microdia Integrated_Webcam_HD                                              | 10        | 4.27%   |
| Acer Integrated Camera                                                     | 10        | 4.27%   |
| Chicony HD WebCam                                                          | 9         | 3.85%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 8         | 3.42%   |
| Chicony HP HD Camera                                                       | 5         | 2.14%   |
| Acer SunplusIT Integrated Camera                                           | 5         | 2.14%   |
| Lite-On Integrated Camera                                                  | 4         | 1.71%   |
| Realtek Integrated Webcam                                                  | 3         | 1.28%   |
| Quanta HD WebCam                                                           | 3         | 1.28%   |
| Microdia Integrated Webcam HD                                              | 3         | 1.28%   |
| Lenovo Integrated Webcam                                                   | 3         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.28%   |
| Chicony USB2.0 Camera                                                      | 3         | 1.28%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.28%   |
| Acer ThinkPad Integrated Camera                                            | 3         | 1.28%   |
| Syntek Integrated Camera                                                   | 2         | 0.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 2         | 0.85%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.85%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.85%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 0.85%   |
| Logitech Webcam C270                                                       | 2         | 0.85%   |
| Logitech C505 HD Webcam                                                    | 2         | 0.85%   |
| Lite-On HP Webcam                                                          | 2         | 0.85%   |
| Lite-On HP HD Camera                                                       | 2         | 0.85%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 2         | 0.85%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.85%   |
| IMC Networks Lenovo EasyCamera                                             | 2         | 0.85%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 0.85%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 0.85%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 0.85%   |
| Chicony HP HD Webcam                                                       | 2         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.85%   |
| Apple FaceTime HD Camera                                                   | 2         | 0.85%   |
| Acer Lenovo Integrated Webcam                                              | 2         | 0.85%   |
| Acer Lenovo EasyCamera                                                     | 2         | 0.85%   |
| Acer EasyCamera                                                            | 2         | 0.85%   |
| Acer BisonCam, NB Pro                                                      | 2         | 0.85%   |
| Z-Star Sirius USB2.0 Camera                                                | 1         | 0.43%   |
| Syntek USB 2.0 UVC PC Camera                                               | 1         | 0.43%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.43%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.43%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.43%   |
| Suyin HP TrueVision Full HD                                                | 1         | 0.43%   |
| Suyin HD WebCam                                                            | 1         | 0.43%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 0.43%   |
| Sunplus Laptop Integrated Webcam FHD                                       | 1         | 0.43%   |
| Sunplus HP Universal Camera                                                | 1         | 0.43%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 0.43%   |
| Sunplus 1.3M HD WebCam                                                     | 1         | 0.43%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.]                    | 1         | 0.43%   |
| Silicon Motion Web Camera                                                  | 1         | 0.43%   |
| Ricoh USB2.0 Camera                                                        | 1         | 0.43%   |
| Realtek USB2.0-Camera                                                      | 1         | 0.43%   |
| Realtek USB Camera                                                         | 1         | 0.43%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 32.2%   |
| Validity Sensors           | 15        | 25.42%  |
| Shenzhen Goodix Technology | 9         | 15.25%  |
| Upek                       | 7         | 11.86%  |
| AuthenTec                  | 4         | 6.78%   |
| Elan Microelectronics      | 3         | 5.08%   |
| LighTuning Technology      | 2         | 3.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 15.25%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 11.86%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 10.17%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 10.17%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 8.47%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 6.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 5.08%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 5.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.69%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 12        | 40%     |
| Broadcom    | 7         | 23.33%  |
| Lenovo      | 5         | 16.67%  |
| Upek        | 4         | 13.33%  |
| OmniKey     | 1         | 3.33%   |
| O2 Micro    | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 40%     |
| Lenovo Integrated Smart Card Reader                                          | 5         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 6.67%   |
| Broadcom 5880                                                                | 2         | 6.67%   |
| Broadcom 58200                                                               | 2         | 6.67%   |
| OmniKey CardMan 4321                                                         | 1         | 3.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 182       | 63.64%  |
| 1     | 73        | 25.52%  |
| 2     | 29        | 10.14%  |
| 4     | 1         | 0.35%   |
| 3     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 43.7%   |
| Chipcard                 | 26        | 19.26%  |
| Graphics card            | 16        | 11.85%  |
| Multimedia controller    | 13        | 9.63%   |
| Net/wireless             | 7         | 5.19%   |
| Communication controller | 4         | 2.96%   |
| Storage                  | 3         | 2.22%   |
| Network                  | 2         | 1.48%   |
| Card reader              | 2         | 1.48%   |
| Modem                    | 1         | 0.74%   |
| Firewire controller      | 1         | 0.74%   |
| Bluetooth                | 1         | 0.74%   |

