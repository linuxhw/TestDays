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
| 5.10.0-8-amd64             | 160       | 57.55%  |
| 5.10.0-7-amd64             | 61        | 21.94%  |
| 5.10.0-6-amd64             | 23        | 8.27%   |
| 5.10.0-8-686-pae           | 4         | 1.44%   |
| 5.12.0-19.3-liquorix-amd64 | 2         | 0.72%   |
| 5.10.0-8-686               | 2         | 0.72%   |
| 4.19.0-14-amd64            | 2         | 0.72%   |
| 5.14.0-rc3-prygun          | 1         | 0.36%   |
| 5.13.8-xanmod1             | 1         | 0.36%   |
| 5.13.8                     | 1         | 0.36%   |
| 5.13.5-xanmod1             | 1         | 0.36%   |
| 5.13.4-e5520               | 1         | 0.36%   |
| 5.12.10                    | 1         | 0.36%   |
| 5.12.1                     | 1         | 0.36%   |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.36%   |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.36%   |
| 5.11.9+                    | 1         | 0.36%   |
| 5.11.22-1-pve              | 1         | 0.36%   |
| 5.11.15-051115-generic     | 1         | 0.36%   |
| 5.11.14                    | 1         | 0.36%   |
| 5.11.0-rc6                 | 1         | 0.36%   |
| 5.10.40-ismynik            | 1         | 0.36%   |
| 5.10.10-64                 | 1         | 0.36%   |
| 5.10.0-io7-amd64           | 1         | 0.36%   |
| 5.10.0-6-rt-amd64          | 1         | 0.36%   |
| 5.10.0-6-686               | 1         | 0.36%   |
| 5.10.0-5-amd64             | 1         | 0.36%   |
| 5.10.0-4-amd64             | 1         | 0.36%   |
| 4.19.181-z580322           | 1         | 0.36%   |
| 4.19.0-16-amd64            | 1         | 0.36%   |
| 4.19.0-16-686-pae          | 1         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 249       | 91.88%  |
| 4.19.0   | 4         | 1.48%   |
| 5.12.0   | 3         | 1.11%   |
| 5.13.8   | 2         | 0.74%   |
| 5.14.0   | 1         | 0.37%   |
| 5.13.5   | 1         | 0.37%   |
| 5.13.4   | 1         | 0.37%   |
| 5.12.10  | 1         | 0.37%   |
| 5.12.1   | 1         | 0.37%   |
| 5.11.9   | 1         | 0.37%   |
| 5.11.22  | 1         | 0.37%   |
| 5.11.15  | 1         | 0.37%   |
| 5.11.14  | 1         | 0.37%   |
| 5.11.0   | 1         | 0.37%   |
| 5.10.40  | 1         | 0.37%   |
| 5.10.10  | 1         | 0.37%   |
| 4.19.181 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 251       | 92.62%  |
| 5.12    | 5         | 1.85%   |
| 5.11    | 5         | 1.85%   |
| 4.19    | 5         | 1.85%   |
| 5.13    | 4         | 1.48%   |
| 5.14    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 263       | 97.05%  |
| i686   | 8         | 2.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 87        | 31.87%  |
| KDE5             | 57        | 20.88%  |
| Unknown          | 46        | 16.85%  |
| XFCE             | 25        | 9.16%   |
| MATE             | 14        | 5.13%   |
| LXQt             | 7         | 2.56%   |
| i3               | 7         | 2.56%   |
| X-Cinnamon       | 5         | 1.83%   |
| LXDE             | 5         | 1.83%   |
| KDE              | 4         | 1.47%   |
| Cinnamon         | 4         | 1.47%   |
| lightdm-xsession | 3         | 1.1%    |
| openbox          | 2         | 0.73%   |
| GNOME Flashback  | 2         | 0.73%   |
| sway             | 1         | 0.37%   |
| ICEWM            | 1         | 0.37%   |
| Enlightenment    | 1         | 0.37%   |
| default          | 1         | 0.37%   |
| awesome          | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 152       | 55.68%  |
| Wayland | 70        | 25.64%  |
| Unknown | 37        | 13.55%  |
| Tty     | 14        | 5.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 84        | 30.88%  |
| Unknown | 63        | 23.16%  |
| SDDM    | 61        | 22.43%  |
| TDM     | 60        | 22.06%  |
| LightDM | 2         | 0.74%   |
| XDM     | 1         | 0.37%   |
| KDM     | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 108       | 39.85%  |
| Unknown | 24        | 8.86%   |
| ru_RU   | 20        | 7.38%   |
| en_GB   | 18        | 6.64%   |
| fr_FR   | 15        | 5.54%   |
| de_DE   | 14        | 5.17%   |
| es_ES   | 8         | 2.95%   |
| pt_BR   | 7         | 2.58%   |
| en_IN   | 7         | 2.58%   |
| pl_PL   | 6         | 2.21%   |
| it_IT   | 4         | 1.48%   |
| tr_TR   | 3         | 1.11%   |
| nn_NO   | 3         | 1.11%   |
| de_CH   | 3         | 1.11%   |
| sv_SE   | 2         | 0.74%   |
| pt_PT   | 2         | 0.74%   |
| ja_JP   | 2         | 0.74%   |
| en_SG   | 2         | 0.74%   |
| en_AU   | 2         | 0.74%   |
| cs_CZ   | 2         | 0.74%   |
| C       | 2         | 0.74%   |
| uk_UA   | 1         | 0.37%   |
| ru_UA   | 1         | 0.37%   |
| ro_RO   | 1         | 0.37%   |
| nl_BE   | 1         | 0.37%   |
| hu_HU   | 1         | 0.37%   |
| hr_HR   | 1         | 0.37%   |
| gl_ES   | 1         | 0.37%   |
| fi_FI   | 1         | 0.37%   |
| es_UY   | 1         | 0.37%   |
| es_MX   | 1         | 0.37%   |
| es_EC   | 1         | 0.37%   |
| es_CO   | 1         | 0.37%   |
| en_SI   | 1         | 0.37%   |
| en_IE   | 1         | 0.37%   |
| en_HK   | 1         | 0.37%   |
| en_CA   | 1         | 0.37%   |
| ca_ES   | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 179       | 65.81%  |
| BIOS | 93        | 34.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 205       | 75.65%  |
| Overlay | 43        | 15.87%  |
| Btrfs   | 16        | 5.9%    |
| Zfs     | 2         | 0.74%   |
| Xfs     | 2         | 0.74%   |
| Unknown | 2         | 0.74%   |
| Rootfs  | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 191       | 70.22%  |
| MBR     | 62        | 22.79%  |
| Unknown | 19        | 6.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 240       | 88.24%  |
| Yes       | 32        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 200       | 73.8%   |
| Yes       | 71        | 26.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 91        | 33.58%  |
| Hewlett-Packard     | 44        | 16.24%  |
| Dell                | 40        | 14.76%  |
| ASUSTek Computer    | 22        | 8.12%   |
| Acer                | 20        | 7.38%   |
| Apple               | 17        | 6.27%   |
| MSI                 | 5         | 1.85%   |
| Google              | 4         | 1.48%   |
| Toshiba             | 3         | 1.11%   |
| HUAWEI              | 3         | 1.11%   |
| Fujitsu             | 3         | 1.11%   |
| Clevo               | 3         | 1.11%   |
| Samsung Electronics | 2         | 0.74%   |
| Gigabyte Technology | 2         | 0.74%   |
| UNOWHY              | 1         | 0.37%   |
| TUXEDO              | 1         | 0.37%   |
| Sony                | 1         | 0.37%   |
| SLIMBOOK            | 1         | 0.37%   |
| Quanta              | 1         | 0.37%   |
| Pegatron            | 1         | 0.37%   |
| PC Specialist       | 1         | 0.37%   |
| Panasonic           | 1         | 0.37%   |
| Notebook            | 1         | 0.37%   |
| Monster             | 1         | 0.37%   |
| Itautec             | 1         | 0.37%   |
| Casper              | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                         | 5         | 1.85%   |
| Apple MacBookAir7,1                         | 4         | 1.48%   |
| Lenovo ThinkPad T490 20N2CTO1WW             | 2         | 0.74%   |
| Lenovo ThinkPad E475 20H40006US             | 2         | 0.74%   |
| Lenovo G50-80 80E5                          | 2         | 0.74%   |
| HUAWEI NBLK-WAX9X                           | 2         | 0.74%   |
| HP Laptop 15s-fq2xxx                        | 2         | 0.74%   |
| HP EliteBook 8460p                          | 2         | 0.74%   |
| HP Compaq nx6125 (PZ849UA#ABA)              | 2         | 0.74%   |
| HP Compaq nx6110 (PZ065UA#ABA)              | 2         | 0.74%   |
| Google Enguarde                             | 2         | 0.74%   |
| Dell XPS 13 9370                            | 2         | 0.74%   |
| Dell XPS 13 9310                            | 2         | 0.74%   |
| Dell XPS 13 7390                            | 2         | 0.74%   |
| Dell Precision 3540                         | 2         | 0.74%   |
| Dell Latitude 7480                          | 2         | 0.74%   |
| Dell Inspiron 5570                          | 2         | 0.74%   |
| Dell Inspiron 3793                          | 2         | 0.74%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA     | 2         | 0.74%   |
| Apple MacBook5,2                            | 2         | 0.74%   |
| Acer Aspire 5315                            | 2         | 0.74%   |
| UNOWHY Y13G002S4EI                          | 1         | 0.37%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.37%   |
| Toshiba Satellite U800W                     | 1         | 0.37%   |
| Toshiba Satellite S55-A                     | 1         | 0.37%   |
| Toshiba Satellite C45-A                     | 1         | 0.37%   |
| Sony VPCF21AFX                              | 1         | 0.37%   |
| SLIMBOOK PROX14-AMD                         | 1         | 0.37%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D  | 1         | 0.37%   |
| Samsung 370E4K                              | 1         | 0.37%   |
| Quanta TWC                                  | 1         | 0.37%   |
| Pegatron A15                                | 1         | 0.37%   |
| PC Specialist NV4XMB,ME,MZ                  | 1         | 0.37%   |
| Panasonic CF-AX2LDCZMF                      | 1         | 0.37%   |
| Notebook NJ50_70CU                          | 1         | 0.37%   |
| MSI U90/U100                                | 1         | 0.37%   |
| MSI Modern 15 A11M                          | 1         | 0.37%   |
| MSI GP60 2PE                                | 1         | 0.37%   |
| MSI GF65 Thin 10UE                          | 1         | 0.37%   |
| MSI CX700                                   | 1         | 0.37%   |
| Monster ABRA A5 V15.2                       | 1         | 0.37%   |
| Lenovo Yoga 300-11IBR 80M1                  | 1         | 0.37%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00       | 1         | 0.37%   |
| Lenovo ThinkPad X260 20F5S46R00             | 1         | 0.37%   |
| Lenovo ThinkPad X260 20F5S0JF00             | 1         | 0.37%   |
| Lenovo ThinkPad X240 20AMS0BU0T             | 1         | 0.37%   |
| Lenovo ThinkPad X240 20AL008EUK             | 1         | 0.37%   |
| Lenovo ThinkPad X230 2325BQ3                | 1         | 0.37%   |
| Lenovo ThinkPad X230 2325AZ8                | 1         | 0.37%   |
| Lenovo ThinkPad X230 23252FG                | 1         | 0.37%   |
| Lenovo ThinkPad X220 Tablet 4298A24         | 1         | 0.37%   |
| Lenovo ThinkPad X201 3626ES3                | 1         | 0.37%   |
| Lenovo ThinkPad X200 7458B64                | 1         | 0.37%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 0.37%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT    | 1         | 0.37%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002RMX    | 1         | 0.37%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQ0008VN    | 1         | 0.37%   |
| Lenovo ThinkPad W520 4284CY1                | 1         | 0.37%   |
| Lenovo ThinkPad W500 406152G                | 1         | 0.37%   |
| Lenovo ThinkPad T61 7661BK7                 | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 73        | 26.94%  |
| Acer Aspire            | 15        | 5.54%   |
| Lenovo IdeaPad         | 14        | 5.17%   |
| Dell Inspiron          | 14        | 5.17%   |
| Dell XPS               | 11        | 4.06%   |
| HP ProBook             | 10        | 3.69%   |
| Apple MacBookAir7      | 9         | 3.32%   |
| HP EliteBook           | 8         | 2.95%   |
| Dell Latitude          | 8         | 2.95%   |
| HP Compaq              | 7         | 2.58%   |
| HP Laptop              | 6         | 2.21%   |
| ASUS VivoBook          | 5         | 1.85%   |
| ASUS ZenBook           | 4         | 1.48%   |
| Toshiba Satellite      | 3         | 1.11%   |
| Fujitsu LIFEBOOK       | 3         | 1.11%   |
| Dell Precision         | 3         | 1.11%   |
| ASUS ROG               | 3         | 1.11%   |
| Lenovo G50-80          | 2         | 0.74%   |
| HUAWEI NBLK-WAX9X      | 2         | 0.74%   |
| HP ZBook               | 2         | 0.74%   |
| HP Pavilion            | 2         | 0.74%   |
| HP OMEN                | 2         | 0.74%   |
| HP 250                 | 2         | 0.74%   |
| Google Enguarde        | 2         | 0.74%   |
| Gigabyte AERO          | 2         | 0.74%   |
| Dell Vostro            | 2         | 0.74%   |
| Apple MacBook5         | 2         | 0.74%   |
| Acer Swift             | 2         | 0.74%   |
| Acer Nitro             | 2         | 0.74%   |
| UNOWHY Y13G002S4EI     | 1         | 0.37%   |
| TUXEDO Pulse           | 1         | 0.37%   |
| Sony VPCF21AFX         | 1         | 0.37%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.37%   |
| Samsung 900X3C         | 1         | 0.37%   |
| Samsung 370E4K         | 1         | 0.37%   |
| Quanta TWC             | 1         | 0.37%   |
| Pegatron A15           | 1         | 0.37%   |
| PC Specialist NV4XMB   | 1         | 0.37%   |
| Panasonic CF-AX2LDCZMF | 1         | 0.37%   |
| Notebook NJ50          | 1         | 0.37%   |
| MSI U90                | 1         | 0.37%   |
| MSI Modern             | 1         | 0.37%   |
| MSI GP60               | 1         | 0.37%   |
| MSI GF65               | 1         | 0.37%   |
| MSI CX700              | 1         | 0.37%   |
| Monster ABRA           | 1         | 0.37%   |
| Lenovo Yoga            | 1         | 0.37%   |
| Lenovo ThinkBook       | 1         | 0.37%   |
| Itautec Infoway        | 1         | 0.37%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.37%   |
| HP Stream              | 1         | 0.37%   |
| HP Split               | 1         | 0.37%   |
| HP Presario            | 1         | 0.37%   |
| HP 630                 | 1         | 0.37%   |
| HP 2000                | 1         | 0.37%   |
| Google Stout           | 1         | 0.37%   |
| Google Parrot          | 1         | 0.37%   |
| Dell Studio            | 1         | 0.37%   |
| Dell G3                | 1         | 0.37%   |
| Clevo W55xEU           | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 60        | 22.14%  |
| 2021 | 55        | 20.3%   |
| 2019 | 37        | 13.65%  |
| 2018 | 18        | 6.64%   |
| 2013 | 14        | 5.17%   |
| 2012 | 13        | 4.8%    |
| 2011 | 12        | 4.43%   |
| 2008 | 11        | 4.06%   |
| 2016 | 9         | 3.32%   |
| 2009 | 9         | 3.32%   |
| 2014 | 8         | 2.95%   |
| 2017 | 7         | 2.58%   |
| 2015 | 7         | 2.58%   |
| 2010 | 3         | 1.11%   |
| 2007 | 3         | 1.11%   |
| 2005 | 2         | 0.74%   |
| 2004 | 2         | 0.74%   |
| 2006 | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 271       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 235       | 86.08%  |
| Enabled  | 38        | 13.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 267       | 98.52%  |
| Yes  | 4         | 1.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 81        | 29.89%  |
| 16.01-24.0  | 63        | 23.25%  |
| 8.01-16.0   | 42        | 15.5%   |
| 3.01-4.0    | 38        | 14.02%  |
| 32.01-64.0  | 15        | 5.54%   |
| 1.01-2.0    | 15        | 5.54%   |
| 64.01-256.0 | 4         | 1.48%   |
| 0.51-1.0    | 4         | 1.48%   |
| 0.01-0.5    | 4         | 1.48%   |
| 2.01-3.0    | 3         | 1.11%   |
| 24.01-32.0  | 2         | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 80        | 28.99%  |
| 2.01-3.0   | 66        | 23.91%  |
| 4.01-8.0   | 45        | 16.3%   |
| 3.01-4.0   | 28        | 10.14%  |
| 0.51-1.0   | 24        | 8.7%    |
| 8.01-16.0  | 20        | 7.25%   |
| 0.01-0.5   | 12        | 4.35%   |
| 32.01-64.0 | 1         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 182       | 67.16%  |
| 2      | 81        | 29.89%  |
| 3      | 4         | 1.48%   |
| 4      | 2         | 0.74%   |
| 0      | 2         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 197       | 72.69%  |
| Yes       | 74        | 27.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 217       | 80.07%  |
| No        | 54        | 19.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 97.79%  |
| No        | 6         | 2.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 77.49%  |
| No        | 61        | 22.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 62        | 22.88%  |
| Germany     | 24        | 8.86%   |
| France      | 23        | 8.49%   |
| Russia      | 20        | 7.38%   |
| Spain       | 11        | 4.06%   |
| Poland      | 10        | 3.69%   |
| UK          | 9         | 3.32%   |
| Brazil      | 9         | 3.32%   |
| Ukraine     | 8         | 2.95%   |
| Switzerland | 7         | 2.58%   |
| India       | 7         | 2.58%   |
| Netherlands | 6         | 2.21%   |
| Turkey      | 5         | 1.85%   |
| Portugal    | 5         | 1.85%   |
| Greece      | 5         | 1.85%   |
| Thailand    | 4         | 1.48%   |
| Norway      | 4         | 1.48%   |
| Kazakhstan  | 4         | 1.48%   |
| Canada      | 4         | 1.48%   |
| Belarus     | 4         | 1.48%   |
| Sweden      | 3         | 1.11%   |
| Italy       | 3         | 1.11%   |
| Czechia     | 3         | 1.11%   |
| Slovenia    | 2         | 0.74%   |
| Mexico      | 2         | 0.74%   |
| Japan       | 2         | 0.74%   |
| Indonesia   | 2         | 0.74%   |
| Ecuador     | 2         | 0.74%   |
| Croatia     | 2         | 0.74%   |
| Australia   | 2         | 0.74%   |
| Uruguay     | 1         | 0.37%   |
| South Sudan | 1         | 0.37%   |
| Romania     | 1         | 0.37%   |
| Philippines | 1         | 0.37%   |
| Mongolia    | 1         | 0.37%   |
| Malaysia    | 1         | 0.37%   |
| Ireland     | 1         | 0.37%   |
| Hungary     | 1         | 0.37%   |
| Finland     | 1         | 0.37%   |
| Denmark     | 1         | 0.37%   |
| Colombia    | 1         | 0.37%   |
| China       | 1         | 0.37%   |
| Bulgaria    | 1         | 0.37%   |
| Belgium     | 1         | 0.37%   |
| Bangladesh  | 1         | 0.37%   |
| Austria     | 1         | 0.37%   |
| Argentina   | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Portland          | 33        | 12.13%  |
| St Petersburg     | 10        | 3.68%   |
| Paris             | 8         | 2.94%   |
| Berlin            | 4         | 1.47%   |
| Bengaluru         | 4         | 1.47%   |
| Bangkok           | 4         | 1.47%   |
| Zurich            | 3         | 1.1%    |
| Lyon              | 3         | 1.1%    |
| London            | 3         | 1.1%    |
| Athens            | 3         | 1.1%    |
| Yevpatoriya       | 2         | 0.74%   |
| Toronto           | 2         | 0.74%   |
| Sunnyvale         | 2         | 0.74%   |
| Rio de Janeiro    | 2         | 0.74%   |
| Offenburg         | 2         | 0.74%   |
| Moscow            | 2         | 0.74%   |
| Molde             | 2         | 0.74%   |
| Mesa              | 2         | 0.74%   |
| Madrid            | 2         | 0.74%   |
| Kyiv              | 2         | 0.74%   |
| Kalamazoo         | 2         | 0.74%   |
| Istanbul          | 2         | 0.74%   |
| Gorinchem         | 2         | 0.74%   |
| Gloucester        | 2         | 0.74%   |
| Fryazino          | 2         | 0.74%   |
| Denpasar          | 2         | 0.74%   |
| Ankara            | 2         | 0.74%   |
| Ajdov????ina      | 2         | 0.74%   |
| Zaragoza          | 1         | 0.37%   |
| Zagreb            | 1         | 0.37%   |
| Wroclaw           | 1         | 0.37%   |
| Waterloo          | 1         | 0.37%   |
| Warsaw            | 1         | 0.37%   |
| Waregem           | 1         | 0.37%   |
| Vitória          | 1         | 0.37%   |
| Vitry-sur-Seine   | 1         | 0.37%   |
| Vienna            | 1         | 0.37%   |
| Valladolid        | 1         | 0.37%   |
| Utrecht           | 1         | 0.37%   |
| Tyumen            | 1         | 0.37%   |
| Turin             | 1         | 0.37%   |
| Touques           | 1         | 0.37%   |
| Toul              | 1         | 0.37%   |
| Thonex            | 1         | 0.37%   |
| Thermopolis       | 1         | 0.37%   |
| The Hague         | 1         | 0.37%   |
| The Colony        | 1         | 0.37%   |
| Tarn??w           | 1         | 0.37%   |
| Sydney            | 1         | 0.37%   |
| Stockholm         | 1         | 0.37%   |
| Stepnogorsk       | 1         | 0.37%   |
| Srednyaya Akhtuba | 1         | 0.37%   |
| Solymar           | 1         | 0.37%   |
| Sofia             | 1         | 0.37%   |
| Shizuoka          | 1         | 0.37%   |
| Secaucus          | 1         | 0.37%   |
| Schleswig         | 1         | 0.37%   |
| S??o Paulo        | 1         | 0.37%   |
| Saynshand         | 1         | 0.37%   |
| Saratov           | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 80     | 20.4%   |
| WDC                 | 39        | 45     | 11.21%  |
| Seagate             | 30        | 33     | 8.62%   |
| Kingston            | 25        | 27     | 7.18%   |
| Toshiba             | 22        | 23     | 6.32%   |
| Unknown             | 17        | 19     | 4.89%   |
| Crucial             | 14        | 14     | 4.02%   |
| Intel               | 13        | 13     | 3.74%   |
| SK Hynix            | 12        | 12     | 3.45%   |
| SABRENT             | 12        | 12     | 3.45%   |
| Apple               | 11        | 11     | 3.16%   |
| Hitachi             | 10        | 10     | 2.87%   |
| SanDisk             | 7         | 9      | 2.01%   |
| Micron Technology   | 6         | 6      | 1.72%   |
| China               | 6         | 6      | 1.72%   |
| A-DATA Technology   | 6         | 8      | 1.72%   |
| Transcend           | 4         | 4      | 1.15%   |
| KIOXIA              | 4         | 4      | 1.15%   |
| Fujitsu             | 4         | 4      | 1.15%   |
| Union Memory        | 3         | 3      | 0.86%   |
| LITEONIT            | 3         | 3      | 0.86%   |
| LITEON              | 3         | 3      | 0.86%   |
| JMicron             | 3         | 3      | 0.86%   |
| HGST                | 3         | 3      | 0.86%   |
| Patriot             | 2         | 2      | 0.57%   |
| Lenovo              | 2         | 2      | 0.57%   |
| Intenso             | 2         | 2      | 0.57%   |
| ZTC                 | 1         | 1      | 0.29%   |
| XPG                 | 1         | 1      | 0.29%   |
| SPCC                | 1         | 1      | 0.29%   |
| SILICONMOTION       | 1         | 1      | 0.29%   |
| Silicon Motion      | 1         | 2      | 0.29%   |
| PNY                 | 1         | 1      | 0.29%   |
| Phison              | 1         | 4      | 0.29%   |
| MyDigitalSSD        | 1         | 1      | 0.29%   |
| Maxtor              | 1         | 2      | 0.29%   |
| LDLC                | 1         | 1      | 0.29%   |
| GOODRAM             | 1         | 1      | 0.29%   |
| ASUS-PHISON         | 1         | 1      | 0.29%   |
| Apacer              | 1         | 1      | 0.29%   |
| AMD                 | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SABRENT Disk 160GB                      | 12        | 3.3%    |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 1.37%   |
| Samsung SSD 970 EVO Plus 500GB          | 5         | 1.37%   |
| Kingston SA400S37120G 120GB SSD         | 5         | 1.37%   |
| Apple SSD SM0128G 121GB                 | 5         | 1.37%   |
| Samsung SSD 970 EVO Plus 1TB            | 4         | 1.1%    |
| Samsung SSD 860 EVO 500GB               | 4         | 1.1%    |
| Samsung SSD 850 EVO 500GB               | 4         | 1.1%    |
| Apple SSD AP0128H 121GB                 | 4         | 1.1%    |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.82%   |
| WDC WD10JPVX-22JC3T0 1TB                | 3         | 0.82%   |
| Unknown DA4064  64GB                    | 3         | 0.82%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.82%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.82%   |
| Samsung SSD 860 EVO M.2 1TB             | 3         | 0.82%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.82%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.82%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 3         | 0.82%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 0.82%   |
| Hitachi HTS543216L9A300 160GB           | 3         | 0.82%   |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.82%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.82%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 2         | 0.55%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 2         | 0.55%   |
| Unknown HAG2e  16GB                     | 2         | 0.55%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.55%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 2         | 0.55%   |
| SK Hynix HFM001TD3JX013N 1TB            | 2         | 0.55%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 0.55%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.55%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.55%   |
| Samsung SSD 850 EVO M.2 250GB           | 2         | 0.55%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.55%   |
| Samsung MZVLB512HAJQ-000L7 512GB        | 2         | 0.55%   |
| Samsung MZ7TE256HMHP-000L7 256GB SSD    | 2         | 0.55%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.55%   |
| Kingston SUV400S37120G 120GB SSD        | 2         | 0.55%   |
| Kingston OM8PCP3512F-AI1 512GB          | 2         | 0.55%   |
| JMicron Generic 250GB                   | 2         | 0.55%   |
| Intel SSDPEKNW010T8 1TB                 | 2         | 0.55%   |
| Hitachi HTS541040G9AT00 40GB            | 2         | 0.55%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.55%   |
| Fujitsu MHZ2160BH FFS G1 160GB          | 2         | 0.55%   |
| Crucial M4-CT256M4SSD2 256GB            | 2         | 0.55%   |
| Crucial CT1000P1SSD8 1TB                | 2         | 0.55%   |
| ZTC SM201-512G SSD                      | 1         | 0.27%   |
| XPG NVMe SSD Drive 1024GB               | 1         | 0.27%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.27%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.27%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.27%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.27%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 0.27%   |
| WDC WD5000LPVX-55V0TT0 500GB            | 1         | 0.27%   |
| WDC WD5000BPVT-00HXZT3 500GB            | 1         | 0.27%   |
| WDC WD50 00LPCX-24VHA 500GB             | 1         | 0.27%   |
| WDC WD2500BEKT-00PVMT0 250GB            | 1         | 0.27%   |
| WDC WD1600BUDT-63DPZY0 160GB            | 1         | 0.27%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 29     | 33.77%  |
| WDC                 | 20        | 21     | 25.97%  |
| Toshiba             | 11        | 11     | 14.29%  |
| Hitachi             | 10        | 10     | 12.99%  |
| Fujitsu             | 4         | 4      | 5.19%   |
| HGST                | 3         | 3      | 3.9%    |
| Samsung Electronics | 2         | 2      | 2.6%    |
| SILICONMOTION       | 1         | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 45     | 27.59%  |
| Kingston            | 17        | 19     | 11.72%  |
| SABRENT             | 12        | 12     | 8.28%   |
| Crucial             | 10        | 10     | 6.9%    |
| Intel               | 7         | 7      | 4.83%   |
| Apple               | 7         | 7      | 4.83%   |
| SanDisk             | 6         | 8      | 4.14%   |
| China               | 6         | 6      | 4.14%   |
| Transcend           | 4         | 4      | 2.76%   |
| WDC                 | 3         | 5      | 2.07%   |
| SK Hynix            | 3         | 3      | 2.07%   |
| LITEONIT            | 3         | 3      | 2.07%   |
| Toshiba             | 2         | 2      | 1.38%   |
| Seagate             | 2         | 2      | 1.38%   |
| Patriot             | 2         | 2      | 1.38%   |
| Micron Technology   | 2         | 2      | 1.38%   |
| LITEON              | 2         | 2      | 1.38%   |
| JMicron             | 2         | 2      | 1.38%   |
| Intenso             | 2         | 2      | 1.38%   |
| A-DATA Technology   | 2         | 2      | 1.38%   |
| ZTC                 | 1         | 1      | 0.69%   |
| Union Memory        | 1         | 1      | 0.69%   |
| SPCC                | 1         | 1      | 0.69%   |
| PNY                 | 1         | 1      | 0.69%   |
| MyDigitalSSD        | 1         | 1      | 0.69%   |
| Maxtor              | 1         | 2      | 0.69%   |
| LDLC                | 1         | 1      | 0.69%   |
| GOODRAM             | 1         | 1      | 0.69%   |
| ASUS-PHISON         | 1         | 1      | 0.69%   |
| Apacer              | 1         | 1      | 0.69%   |
| AMD                 | 1         | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 132       | 157    | 39.88%  |
| NVMe    | 102       | 120    | 30.82%  |
| HDD     | 77        | 81     | 23.26%  |
| MMC     | 16        | 18     | 4.83%   |
| Unknown | 4         | 4      | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 175       | 216    | 55.38%  |
| NVMe | 102       | 120    | 32.28%  |
| SAS  | 23        | 26     | 7.28%   |
| MMC  | 16        | 18     | 5.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 137       | 172    | 68.5%   |
| 0.51-1.0   | 55        | 57     | 27.5%   |
| 1.01-2.0   | 6         | 7      | 3%      |
| 3.01-4.0   | 1         | 1      | 0.5%    |
| 2.01-3.0   | 1         | 1      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 31.5%   |
| 251-500        | 58        | 21.25%  |
| 501-1000       | 36        | 13.19%  |
| 1001-2000      | 24        | 8.79%   |
| 1-20           | 23        | 8.42%   |
| 51-100         | 16        | 5.86%   |
| 21-50          | 11        | 4.03%   |
| Unknown        | 11        | 4.03%   |
| More than 3000 | 6         | 2.2%    |
| 2001-3000      | 2         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 93        | 33.7%   |
| 21-50     | 40        | 14.49%  |
| 101-250   | 37        | 13.41%  |
| 51-100    | 35        | 12.68%  |
| 251-500   | 28        | 10.14%  |
| 501-1000  | 19        | 6.88%   |
| Unknown   | 11        | 3.99%   |
| 1001-2000 | 9         | 3.26%   |
| 0         | 3         | 1.09%   |
| 2001-3000 | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 2      | 6.67%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 3.33%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 3.33%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 3.33%   |
| Seagate ST960822A 64GB                         | 1         | 1      | 3.33%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 3.33%   |
| Seagate ST9160310AS 160GB                      | 1         | 1      | 3.33%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 3.33%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 3.33%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 850 EVO 1TB            | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 2      | 3.33%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 3.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.33%   |
| LITEONIT LMT-64M6M-HP 64GB SSD                 | 1         | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 3.33%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 1      | 3.33%   |
| Intel SSDSC2KW120H6 120GB                      | 1         | 1      | 3.33%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 3.33%   |
| Intel SSDSA2M160G2HP 160GB                     | 1         | 1      | 3.33%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 3.33%   |
| Hitachi HTS543212L9A300 120GB                  | 1         | 1      | 3.33%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 3.33%   |
| Hitachi HTS541040G9AT00 40GB                   | 1         | 1      | 3.33%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 3.33%   |
| A-DATA Technology SU630 480GB SSD              | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 23.33%  |
| Samsung Electronics | 4         | 5      | 13.33%  |
| Hitachi             | 4         | 4      | 13.33%  |
| WDC                 | 3         | 3      | 10%     |
| Toshiba             | 3         | 3      | 10%     |
| Intel               | 3         | 3      | 10%     |
| Kingston            | 2         | 2      | 6.67%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 36.84%  |
| Hitachi             | 4         | 4      | 21.05%  |
| WDC                 | 3         | 3      | 15.79%  |
| Toshiba             | 3         | 3      | 15.79%  |
| Samsung Electronics | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 63.33%  |
| SSD  | 11        | 12     | 36.67%  |

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
| Works    | 221       | 277    | 72.7%   |
| Detected | 53        | 72     | 17.43%  |
| Malfunc  | 30        | 31     | 9.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 175       | 56.27%  |
| Samsung Electronics          | 38        | 12.22%  |
| AMD                          | 24        | 7.72%   |
| Sandisk                      | 18        | 5.79%   |
| SK Hynix                     | 9         | 2.89%   |
| Toshiba America Info Systems | 8         | 2.57%   |
| Kingston Technology Company  | 8         | 2.57%   |
| KIOXIA                       | 5         | 1.61%   |
| Micron/Crucial Technology    | 4         | 1.29%   |
| Micron Technology            | 4         | 1.29%   |
| Apple                        | 4         | 1.29%   |
| ADATA Technology             | 4         | 1.29%   |
| Nvidia                       | 3         | 0.96%   |
| Union Memory (Shenzhen)      | 2         | 0.64%   |
| Lenovo                       | 2         | 0.64%   |
| Silicon Motion               | 1         | 0.32%   |
| Phison Electronics           | 1         | 0.32%   |
| Lite-On Technology           | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 8.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 24        | 7.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 6.4%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 20        | 6.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 4.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 3.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 3.05%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 2.44%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 6         | 1.83%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 1.83%   |
| Samsung Electronics SATA controller                                              | 6         | 1.83%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.83%   |
| Samsung NVMe Controller                                                          | 5         | 1.52%   |
| KIOXIA Non-Volatile memory controller                                            | 5         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.52%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.22%   |
| Intel SSD 660P Series                                                            | 4         | 1.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.22%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.22%   |
| Apple S1X NVMe Controller                                                        | 4         | 1.22%   |
| SK Hynix NVMe SSD Controller                                                     | 3         | 0.91%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.91%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.91%   |
| Sandisk Non-Volatile memory controller                                           | 3         | 0.91%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 0.91%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.91%   |
| AMD IXP SB4x0 IDE Controller                                                     | 3         | 0.91%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.61%   |
| SK Hynix BC511                                                                   | 2         | 0.61%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.61%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.61%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.61%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.61%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.61%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.61%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.61%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.61%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 0.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 0.61%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.61%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 0.61%   |
| ADATA Non-Volatile memory controller                                             | 2         | 0.61%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.3%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.3%    |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.3%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 171       | 53.61%  |
| NVMe | 102       | 31.97%  |
| RAID | 25        | 7.84%   |
| IDE  | 21        | 6.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 233       | 85.98%  |
| AMD    | 38        | 14.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz               | 9         | 3.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 8         | 2.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 8         | 2.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 7         | 2.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 7         | 2.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 6         | 2.21%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 6         | 2.21%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 6         | 2.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 5         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 5         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 1.85%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 5         | 1.85%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 5         | 1.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 4         | 1.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 4         | 1.48%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 4         | 1.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 4         | 1.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 4         | 1.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 1.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 4         | 1.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 4         | 1.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 1.48%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 3         | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.11%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 3         | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 1.11%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 1.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 1.11%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 3         | 1.11%   |
| Intel Pentium M processor 1.73GHz               | 2         | 0.74%   |
| Intel Genuine CPU T1400 @ 1.73GHz               | 2         | 0.74%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 2         | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 0.74%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 0.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 0.74%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 2         | 0.74%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 2         | 0.74%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 2         | 0.74%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 2         | 0.74%   |
| Intel Core i7-10850H CPU @ 2.70GHz              | 2         | 0.74%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 2         | 0.74%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 2         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 0.74%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 0.74%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.74%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz            | 2         | 0.74%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz            | 2         | 0.74%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 2         | 0.74%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz            | 2         | 0.74%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 0.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 0.74%   |
| Intel Celeron M processor 900MHz                | 2         | 0.74%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2         | 0.74%   |
| Intel Celeron CPU B800 @ 1.50GHz                | 2         | 0.74%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 2         | 0.74%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 2         | 0.74%   |
| AMD Turion 64 Mobile ML-30                      | 2         | 0.74%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 2         | 0.74%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 87        | 32.1%   |
| Intel Core i7        | 70        | 25.83%  |
| Other                | 19        | 7.01%   |
| Intel Core 2 Duo     | 14        | 5.17%   |
| Intel Celeron        | 14        | 5.17%   |
| Intel Core i3        | 11        | 4.06%   |
| AMD Ryzen 5          | 10        | 3.69%   |
| AMD Ryzen 7          | 8         | 2.95%   |
| AMD Ryzen 7 PRO      | 7         | 2.58%   |
| Intel Pentium        | 6         | 2.21%   |
| Intel Pentium M      | 4         | 1.48%   |
| Intel Genuine        | 2         | 0.74%   |
| Intel Core 2         | 2         | 0.74%   |
| Intel Celeron M      | 2         | 0.74%   |
| Intel Atom           | 2         | 0.74%   |
| AMD Turion 64 Mobile | 2         | 0.74%   |
| AMD Ryzen 9          | 2         | 0.74%   |
| AMD Ryzen 3          | 2         | 0.74%   |
| Intel Xeon           | 1         | 0.37%   |
| Intel Pentium Gold   | 1         | 0.37%   |
| Intel Pentium Dual   | 1         | 0.37%   |
| AMD C-30             | 1         | 0.37%   |
| AMD Athlon 64        | 1         | 0.37%   |
| AMD A8               | 1         | 0.37%   |
| AMD A12              | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 138       | 50.92%  |
| 4      | 87        | 32.1%   |
| 8      | 16        | 5.9%    |
| 6      | 15        | 5.54%   |
| 1      | 15        | 5.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 271       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 214       | 78.97%  |
| 1      | 57        | 21.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 263       | 97.05%  |
| 32-bit         | 8         | 2.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 16.85%  |
| 0x306a9    | 24        | 8.79%   |
| 0x206a7    | 20        | 7.33%   |
| 0x306d4    | 19        | 6.96%   |
| 0x806c1    | 15        | 5.49%   |
| 0x806ec    | 12        | 4.4%    |
| 0x806ea    | 11        | 4.03%   |
| 0x806e9    | 11        | 4.03%   |
| 0x906ea    | 8         | 2.93%   |
| 0x1067a    | 8         | 2.93%   |
| 0x08600106 | 8         | 2.93%   |
| 0xa0652    | 7         | 2.56%   |
| 0x706e5    | 7         | 2.56%   |
| 0x406e3    | 7         | 2.56%   |
| 0x40651    | 7         | 2.56%   |
| 0x08108109 | 6         | 2.2%    |
| 0x806eb    | 4         | 1.47%   |
| 0x6fd      | 4         | 1.47%   |
| 0x6d8      | 4         | 1.47%   |
| 0x506c9    | 4         | 1.47%   |
| 0x20655    | 4         | 1.47%   |
| 0x306c3    | 3         | 1.1%    |
| 0x0600611a | 3         | 1.1%    |
| 0x906e9    | 2         | 0.73%   |
| 0x706a8    | 2         | 0.73%   |
| 0x6fa      | 2         | 0.73%   |
| 0x6f6      | 2         | 0.73%   |
| 0x695      | 2         | 0.73%   |
| 0x30678    | 2         | 0.73%   |
| 0x106c2    | 2         | 0.73%   |
| 0x0a50000b | 2         | 0.73%   |
| 0x08600103 | 2         | 0.73%   |
| 0x08108102 | 2         | 0.73%   |
| 0x406c4    | 1         | 0.37%   |
| 0x406c3    | 1         | 0.37%   |
| 0x40661    | 1         | 0.37%   |
| 0x10676    | 1         | 0.37%   |
| 0x10661    | 1         | 0.37%   |
| 0x08608103 | 1         | 0.37%   |
| 0x08600104 | 1         | 0.37%   |
| 0x0810100b | 1         | 0.37%   |
| 0x06006705 | 1         | 0.37%   |
| 0x05000029 | 1         | 0.37%   |
| 0x03000027 | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 59        | 21.77%  |
| IvyBridge     | 28        | 10.33%  |
| SandyBridge   | 20        | 7.38%   |
| Broadwell     | 19        | 7.01%   |
| Haswell       | 18        | 6.64%   |
| TigerLake     | 17        | 6.27%   |
| Zen 2         | 14        | 5.17%   |
| Skylake       | 11        | 4.06%   |
| Zen+          | 10        | 3.69%   |
| Penryn        | 10        | 3.69%   |
| Core          | 10        | 3.69%   |
| Westmere      | 8         | 2.95%   |
| CometLake     | 8         | 2.95%   |
| IceLake       | 7         | 2.58%   |
| P6            | 6         | 2.21%   |
| Silvermont    | 4         | 1.48%   |
| Goldmont      | 4         | 1.48%   |
| Excavator     | 4         | 1.48%   |
| Zen 3         | 3         | 1.11%   |
| K8 Hammer     | 3         | 1.11%   |
| Goldmont plus | 2         | 0.74%   |
| Bonnell       | 2         | 0.74%   |
| Zen           | 1         | 0.37%   |
| K10 Llano     | 1         | 0.37%   |
| Bobcat        | 1         | 0.37%   |
| Unknown       | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 219       | 65.77%  |
| Nvidia | 59        | 17.72%  |
| AMD    | 55        | 16.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 7.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 5.17%   |
| Intel UHD Graphics 620                                                                   | 15        | 4.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 4.02%   |
| AMD Renoir                                                                               | 14        | 4.02%   |
| Intel HD Graphics 620                                                                    | 11        | 3.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.87%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.87%   |
| AMD Picasso                                                                              | 10        | 2.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.59%   |
| Intel HD Graphics 6000                                                                   | 9         | 2.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.15%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 1.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.15%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 4         | 1.15%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.86%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.86%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.86%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.86%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 3         | 0.86%   |
| AMD Cezanne                                                                              | 3         | 0.86%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.57%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.57%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.57%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.57%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.57%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.57%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.57%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.57%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.57%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.57%   |
| Intel HD Graphics 630                                                                    | 2         | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.57%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.57%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.57%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                                         | 2         | 0.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.29%   |
| Nvidia TU117M                                                                            | 1         | 0.29%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.29%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.29%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.29%   |
| Nvidia NV34M [GeForce FX Go5200 64M]                                                     | 1         | 0.29%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 161       | 58.97%  |
| Intel + Nvidia | 47        | 17.22%  |
| 1 x AMD        | 37        | 13.55%  |
| Intel + AMD    | 11        | 4.03%   |
| 1 x Nvidia     | 9         | 3.3%    |
| AMD + Nvidia   | 4         | 1.47%   |
| 2 x AMD        | 3         | 1.1%    |
| Other          | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 248       | 91.18%  |
| Proprietary | 22        | 8.09%   |
| Unknown     | 2         | 0.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 207       | 75.55%  |
| 0.01-0.5   | 29        | 10.58%  |
| 0.51-1.0   | 14        | 5.11%   |
| 1.01-2.0   | 13        | 4.74%   |
| 3.01-4.0   | 9         | 3.28%   |
| 7.01-8.0   | 1         | 0.36%   |
| 5.01-6.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 19.49%  |
| Chimei Innolux          | 44        | 14.06%  |
| BOE                     | 42        | 13.42%  |
| LG Display              | 38        | 12.14%  |
| Samsung Electronics     | 21        | 6.71%   |
| Apple                   | 17        | 5.43%   |
| Sharp                   | 13        | 4.15%   |
| Lenovo                  | 12        | 3.83%   |
| Dell                    | 9         | 2.88%   |
| Hewlett-Packard         | 5         | 1.6%    |
| Ancor Communications    | 5         | 1.6%    |
| ViewSonic               | 4         | 1.28%   |
| InfoVision              | 4         | 1.28%   |
| Chi Mei Optoelectronics | 4         | 1.28%   |
| BenQ                    | 4         | 1.28%   |
| LG Philips              | 3         | 0.96%   |
| Goldstar                | 3         | 0.96%   |
| Philips                 | 2         | 0.64%   |
| PANDA                   | 2         | 0.64%   |
| HannStar                | 2         | 0.64%   |
| CPT                     | 2         | 0.64%   |
| AOC                     | 2         | 0.64%   |
| ___                     | 1         | 0.32%   |
| Vestel Elektronik       | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| NEC Computers           | 1         | 0.32%   |
| NCS                     | 1         | 0.32%   |
| MSI                     | 1         | 0.32%   |
| LPL                     | 1         | 0.32%   |
| JXG                     | 1         | 0.32%   |
| JRY                     | 1         | 0.32%   |
| IOD                     | 1         | 0.32%   |
| CSO                     | 1         | 0.32%   |
| CMN                     | 1         | 0.32%   |
| ASUSTek Computer        | 1         | 0.32%   |
| Acer                    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 4         | 1.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 4         | 1.26%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 4         | 1.26%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 3         | 0.95%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.95%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 3         | 0.95%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 3         | 0.95%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 2         | 0.63%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                   | 2         | 0.63%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.63%   |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch               | 2         | 0.63%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 2         | 0.63%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 2         | 0.63%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch               | 2         | 0.63%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 2         | 0.63%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 0.63%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.63%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 2         | 0.63%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                     | 2         | 0.63%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 2         | 0.63%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 2         | 0.63%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 2         | 0.63%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 2         | 0.63%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 2         | 0.63%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 2         | 0.63%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch     | 2         | 0.63%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                        | 1         | 0.32%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch             | 1         | 0.32%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch                 | 1         | 0.32%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                    | 1         | 0.32%   |
| ViewSonic LCD Monitor XG2401 SERIES                                       | 1         | 0.32%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 1         | 0.32%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                       | 1         | 0.32%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch                   | 1         | 0.32%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 1         | 0.32%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 1         | 0.32%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                   | 1         | 0.32%   |
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch                   | 1         | 0.32%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                   | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 134       | 44.37%  |
| 1366x768 (WXGA)    | 70        | 23.18%  |
| 1280x800 (WXGA)    | 18        | 5.96%   |
| 1600x900 (HD+)     | 16        | 5.3%    |
| 3840x2160 (4K)     | 11        | 3.64%   |
| 1920x1200 (WUXGA)  | 10        | 3.31%   |
| 1440x900 (WXGA+)   | 10        | 3.31%   |
| 2560x1440 (QHD)    | 8         | 2.65%   |
| 1280x1024 (SXGA)   | 5         | 1.66%   |
| 1024x768 (XGA)     | 4         | 1.32%   |
| 1680x1050 (WSXGA+) | 3         | 0.99%   |
| 3440x1440          | 2         | 0.66%   |
| 1024x600           | 2         | 0.66%   |
| 3840x2400          | 1         | 0.33%   |
| 3840x1080          | 1         | 0.33%   |
| 3200x1800 (QHD+)   | 1         | 0.33%   |
| 2880x1800          | 1         | 0.33%   |
| 2560x1600          | 1         | 0.33%   |
| 2256x1504          | 1         | 0.33%   |
| 1792x768           | 1         | 0.33%   |
| 1600x1200          | 1         | 0.33%   |
| Unknown            | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 94        | 30.03%  |
| 13      | 67        | 21.41%  |
| 14      | 44        | 14.06%  |
| 17      | 21        | 6.71%   |
| 12      | 17        | 5.43%   |
| 11      | 14        | 4.47%   |
| 24      | 12        | 3.83%   |
| 21      | 9         | 2.88%   |
| 23      | 8         | 2.56%   |
| 27      | 3         | 0.96%   |
| 25      | 3         | 0.96%   |
| 19      | 3         | 0.96%   |
| 34      | 2         | 0.64%   |
| 31      | 2         | 0.64%   |
| 10      | 2         | 0.64%   |
| Unknown | 2         | 0.64%   |
| 84      | 1         | 0.32%   |
| 72      | 1         | 0.32%   |
| 47      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 33      | 1         | 0.32%   |
| 32      | 1         | 0.32%   |
| 22      | 1         | 0.32%   |
| 20      | 1         | 0.32%   |
| 18      | 1         | 0.32%   |
| 16      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 171       | 54.63%  |
| 201-300     | 67        | 21.41%  |
| 501-600     | 23        | 7.35%   |
| 351-400     | 23        | 7.35%   |
| 401-500     | 15        | 4.79%   |
| 701-800     | 4         | 1.28%   |
| 601-700     | 4         | 1.28%   |
| 1501-2000   | 2         | 0.64%   |
| Unknown     | 2         | 0.64%   |
| 801-900     | 1         | 0.32%   |
| 1001-1500   | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 223       | 78.52%  |
| 16/10   | 41        | 14.44%  |
| 4/3     | 6         | 2.11%   |
| 5/4     | 5         | 1.76%   |
| 3/2     | 4         | 1.41%   |
| 21/9    | 3         | 1.06%   |
| Unknown | 2         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 95        | 30.25%  |
| 81-90          | 86        | 27.39%  |
| 71-80          | 26        | 8.28%   |
| 201-250        | 23        | 7.32%   |
| 121-130        | 17        | 5.41%   |
| 61-70          | 16        | 5.1%    |
| 51-60          | 14        | 4.46%   |
| 251-300        | 8         | 2.55%   |
| 351-500        | 6         | 1.91%   |
| 151-200        | 6         | 1.91%   |
| 141-150        | 5         | 1.59%   |
| 301-350        | 3         | 0.96%   |
| More than 1000 | 2         | 0.64%   |
| 41-50          | 2         | 0.64%   |
| 501-1000       | 2         | 0.64%   |
| Unknown        | 2         | 0.64%   |
| 131-140        | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 162       | 52.94%  |
| 101-120       | 63        | 20.59%  |
| 51-100        | 51        | 16.67%  |
| 161-240       | 19        | 6.21%   |
| More than 240 | 7         | 2.29%   |
| 1-50          | 2         | 0.65%   |
| Unknown       | 2         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 219       | 80.51%  |
| 2     | 44        | 16.18%  |
| 3     | 5         | 1.84%   |
| 0     | 4         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 170       | 41.06%  |
| Realtek Semiconductor             | 116       | 28.02%  |
| Qualcomm Atheros                  | 50        | 12.08%  |
| Broadcom                          | 25        | 6.04%   |
| Broadcom Limited                  | 15        | 3.62%   |
| Marvell Technology Group          | 5         | 1.21%   |
| Ericsson Business Mobile Networks | 4         | 0.97%   |
| Sierra Wireless                   | 3         | 0.72%   |
| Nvidia                            | 3         | 0.72%   |
| AMD                               | 3         | 0.72%   |
| Ralink                            | 2         | 0.48%   |
| DisplayLink                       | 2         | 0.48%   |
| Dell                              | 2         | 0.48%   |
| Cypress Semiconductor             | 2         | 0.48%   |
| Xiaomi                            | 1         | 0.24%   |
| Qualcomm                          | 1         | 0.24%   |
| Microchip Technology              | 1         | 0.24%   |
| MEDIATEK                          | 1         | 0.24%   |
| Lenovo                            | 1         | 0.24%   |
| JMicron Technology                | 1         | 0.24%   |
| Huawei Technologies               | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| Fibocom                           | 1         | 0.24%   |
| Edimax Technology                 | 1         | 0.24%   |
| D-Link                            | 1         | 0.24%   |
| Attansic Technology               | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 79        | 15.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 22        | 4.26%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 3.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2.71%   |
| Intel Wireless 8265 / 8275                                              | 14        | 2.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13        | 2.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 2.51%   |
| Intel Wireless 7260                                                     | 10        | 1.93%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 9         | 1.74%   |
| Intel Wireless 8260                                                     | 8         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.35%   |
| Intel Wireless 7265                                                     | 7         | 1.35%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.16%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 0.97%   |
| Intel Wireless 3160                                                     | 5         | 0.97%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.97%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.77%   |
| Intel Wireless 3165                                                     | 4         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                   | 4         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.77%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.58%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.58%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.58%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 3         | 0.58%   |
| AMD IXP SB400 AC'97 Modem Controller                                    | 3         | 0.58%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.39%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.39%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.39%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.39%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.39%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.39%   |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 0.39%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 2         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 165       | 60%     |
| Qualcomm Atheros                  | 44        | 16%     |
| Realtek Semiconductor             | 30        | 10.91%  |
| Broadcom Limited                  | 14        | 5.09%   |
| Broadcom                          | 12        | 4.36%   |
| Sierra Wireless                   | 3         | 1.09%   |
| Ralink                            | 2         | 0.73%   |
| Qualcomm                          | 1         | 0.36%   |
| MEDIATEK                          | 1         | 0.36%   |
| Fibocom                           | 1         | 0.36%   |
| Ericsson Business Mobile Networks | 1         | 0.36%   |
| Edimax Technology                 | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 19        | 6.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 14        | 5.07%   |
| Intel Wireless 8265 / 8275                                                            | 14        | 5.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 13        | 4.71%   |
| Intel Wireless 7260                                                                   | 10        | 3.62%   |
| Intel Wi-Fi 6 AX201                                                                   | 10        | 3.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 9         | 3.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 9         | 3.26%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 9         | 3.26%   |
| Intel Wireless 8260                                                                   | 8         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 7         | 2.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 7         | 2.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 7         | 2.54%   |
| Intel Wireless 7265                                                                   | 7         | 2.54%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 7         | 2.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 7         | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                                        | 6         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 6         | 2.17%   |
| Intel Wireless 3160                                                                   | 5         | 1.81%   |
| Intel Centrino Wireless-N 2230                                                        | 5         | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 4         | 1.45%   |
| Intel Wireless 3165                                                                   | 4         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 4         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3         | 1.09%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 3         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 1.09%   |
| Intel Centrino Advanced-N 6200                                                        | 3         | 1.09%   |
| Sierra Wireless EM7345 4G LTE                                                         | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.72%   |
| Intel Wireless-AC 9260                                                                | 2         | 0.72%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 0.72%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                             | 2         | 0.72%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 0.72%   |
| Broadcom Limited BCM4318 [AirForce 54g] 802.11a/b/g PCI Express Transceiver           | 2         | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 0.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 2         | 0.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 2         | 0.72%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                                   | 1         | 0.36%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.36%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.36%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.36%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.36%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.36%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.36%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                           | 1         | 0.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.36%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.36%   |
| MEDIATEK Network controller                                                           | 1         | 0.36%   |
| Intel Wireless Gigabit 17265                                                          | 1         | 0.36%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 0.36%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                                       | 1         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 101       | 44.69%  |
| Intel                    | 76        | 33.63%  |
| Broadcom                 | 16        | 7.08%   |
| Qualcomm Atheros         | 12        | 5.31%   |
| Marvell Technology Group | 5         | 2.21%   |
| Nvidia                   | 3         | 1.33%   |
| DisplayLink              | 2         | 0.88%   |
| Cypress Semiconductor    | 2         | 0.88%   |
| Broadcom Limited         | 2         | 0.88%   |
| Xiaomi                   | 1         | 0.44%   |
| Microchip Technology     | 1         | 0.44%   |
| Lenovo                   | 1         | 0.44%   |
| JMicron Technology       | 1         | 0.44%   |
| Huawei Technologies      | 1         | 0.44%   |
| D-Link                   | 1         | 0.44%   |
| Attansic Technology      | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 34.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 9.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 5.7%    |
| Intel Ethernet Connection (4) I219-V                              | 7         | 3.07%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.19%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.19%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.19%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.32%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.88%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.88%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.88%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.88%   |
| Cypress K38231_03                                                 | 2         | 0.88%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.88%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.88%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.44%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.44%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.44%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.44%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.44%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.44%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.44%   |
| Intel 82801DB PRO/100 VM (MOB) Ethernet Controller                | 1         | 0.44%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.44%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.44%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.44%   |
| Huawei E353/E3131                                                 | 1         | 0.44%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 0.44%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.44%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1         | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 265       | 53.54%  |
| Ethernet | 217       | 43.84%  |
| Modem    | 13        | 2.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 252       | 62.84%  |
| Ethernet | 147       | 36.66%  |
| Modem    | 2         | 0.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 199       | 73.43%  |
| 1     | 67        | 24.72%  |
| 3     | 5         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 217       | 79.78%  |
| Yes  | 55        | 20.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 108       | 51.18%  |
| Qualcomm Atheros Communications | 18        | 8.53%   |
| Realtek Semiconductor           | 17        | 8.06%   |
| Apple                           | 16        | 7.58%   |
| Broadcom                        | 15        | 7.11%   |
| Lite-On Technology              | 11        | 5.21%   |
| IMC Networks                    | 5         | 2.37%   |
| Foxconn / Hon Hai               | 5         | 2.37%   |
| Hewlett-Packard                 | 4         | 1.9%    |
| Realtek                         | 3         | 1.42%   |
| Cambridge Silicon Radio         | 3         | 1.42%   |
| Toshiba                         | 2         | 0.95%   |
| Dell                            | 2         | 0.95%   |
| Taiyo Yuden                     | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 18.48%  |
| Intel Bluetooth Device                              | 24        | 11.37%  |
| Intel AX200 Bluetooth                               | 20        | 9.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 8.06%   |
| Realtek Bluetooth Radio                             | 12        | 5.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 5.69%   |
| Apple Bluetooth USB Host Controller                 | 9         | 4.27%   |
| Lite-On Bluetooth Device                            | 7         | 3.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 2.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 2.84%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.9%    |
| Realtek Bluetooth Radio                             | 3         | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.42%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.42%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.42%   |
| Apple Bluetooth Host Controller                     | 3         | 1.42%   |
| Toshiba Bluetooth Device                            | 2         | 0.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.95%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 2         | 0.95%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.47%   |
| Realtek CSR BS8510                                  | 1         | 0.47%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.47%   |
| Lite-On Wireless_Device                             | 1         | 0.47%   |
| Lite-On BCM43142A0                                  | 1         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.47%   |
| IMC Networks Bluetooth Device                       | 1         | 0.47%   |
| IMC Networks Bluetooth                              | 1         | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.47%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.47%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.47%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 230       | 70.77%  |
| AMD                    | 42        | 12.92%  |
| Nvidia                 | 33        | 10.15%  |
| Generalplus Technology | 4         | 1.23%   |
| Plantronics            | 3         | 0.92%   |
| Logitech               | 3         | 0.92%   |
| C-Media Electronics    | 3         | 0.92%   |
| Texas Instruments      | 2         | 0.62%   |
| GN Netcom              | 2         | 0.62%   |
| Razer USA              | 1         | 0.31%   |
| Lenovo                 | 1         | 0.31%   |
| Creative Technology    | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 9.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 7.83%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 29        | 7.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 4.8%    |
| Intel Broadwell-U Audio Controller                                                                | 19        | 4.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 4.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 4.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 3.03%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 3.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.01%   |
| Generalplus Technology USB Audio Device                                                           | 4         | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.01%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.76%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.76%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.51%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.51%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.51%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.51%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.51%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.51%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.51%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.25%   |
| Plantronics DA40                                                                                  | 1         | 0.25%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.25%   |
| Plantronics Blackwire 315.1                                                                       | 1         | 0.25%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.25%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.25%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.25%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.25%   |
| Nvidia Audio device                                                                               | 1         | 0.25%   |
| Logitech [G533 Wireless Headset Dongle]                                                           | 1         | 0.25%   |
| Logitech USB Headset                                                                              | 1         | 0.25%   |
| Logitech Headset H340                                                                             | 1         | 0.25%   |
| Lenovo ThinkPad Dock Audio                                                                        | 1         | 0.25%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.25%   |
| GN Netcom Jabra UC VOICE 550 MS USB                                                               | 1         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 78        | 26.09%  |
| Samsung Electronics | 77        | 25.75%  |
| Micron Technology   | 29        | 9.7%    |
| Kingston            | 27        | 9.03%   |
| Unknown             | 22        | 7.36%   |
| Crucial             | 20        | 6.69%   |
| A-DATA Technology   | 9         | 3.01%   |
| Ramaxel Technology  | 8         | 2.68%   |
| Corsair             | 7         | 2.34%   |
| Nanya Technology    | 6         | 2.01%   |
| Elpida              | 5         | 1.67%   |
| Team                | 2         | 0.67%   |
| Unknown (ABCD)      | 1         | 0.33%   |
| Unifosa             | 1         | 0.33%   |
| SMART Brazil        | 1         | 0.33%   |
| Smart               | 1         | 0.33%   |
| PNY                 | 1         | 0.33%   |
| Kllisre             | 1         | 0.33%   |
| Infineon            | 1         | 0.33%   |
| GOODRAM             | 1         | 0.33%   |
| G.Skill             | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.91%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 1.59%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 1.27%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.27%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.27%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 4         | 1.27%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.96%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.96%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.96%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 0.96%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                       | 3         | 0.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.96%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.96%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s          | 3         | 0.96%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.96%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.64%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 2         | 0.64%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 2         | 0.64%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 2         | 0.64%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.64%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.64%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.64%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.64%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.64%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.64%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.64%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.64%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.64%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.64%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.64%   |
| Samsung RAM M4 70L6524CU0-CB3 512MB SODIMM DDR 333MT/s           | 2         | 0.64%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 2         | 0.64%   |
| Nanya RAM NT512D64SH8B0GN-6K 512MB SODIMM DDR 333MT/s            | 2         | 0.64%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.64%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 2         | 0.64%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.64%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.64%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 2         | 0.64%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                           | 1         | 0.32%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.32%   |
| Unknown SODIMM 1GB SODIMM DDR2 667MT/s                           | 1         | 0.32%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.32%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.32%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.32%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 112       | 43.92%  |
| DDR3   | 97        | 38.04%  |
| DDR2   | 18        | 7.06%   |
| LPDDR3 | 12        | 4.71%   |
| LPDDR4 | 7         | 2.75%   |
| DDR    | 5         | 1.96%   |
| SDRAM  | 3         | 1.18%   |
| DRAM   | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 231       | 90.59%  |
| Row Of Chips | 21        | 8.24%   |
| Chip         | 2         | 0.78%   |
| Unknown      | 1         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 92        | 33.58%  |
| 8192  | 86        | 31.39%  |
| 16384 | 36        | 13.14%  |
| 2048  | 26        | 9.49%   |
| 1024  | 18        | 6.57%   |
| 32768 | 8         | 2.92%   |
| 512   | 6         | 2.19%   |
| 256   | 2         | 0.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 70        | 25.83%  |
| 2667    | 54        | 19.93%  |
| 3200    | 40        | 14.76%  |
| 2400    | 21        | 7.75%   |
| 1334    | 18        | 6.64%   |
| 2133    | 16        | 5.9%    |
| 1333    | 14        | 5.17%   |
| 667     | 7         | 2.58%   |
| 533     | 5         | 1.85%   |
| Unknown | 5         | 1.85%   |
| 1867    | 4         | 1.48%   |
| 333     | 4         | 1.48%   |
| 4267    | 3         | 1.11%   |
| 400     | 3         | 1.11%   |
| 1067    | 2         | 0.74%   |
| 800     | 2         | 0.74%   |
| 4266    | 1         | 0.37%   |
| 4199    | 1         | 0.37%   |
| 975     | 1         | 0.37%   |

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
| Chicony Electronics                    | 52        | 23.42%  |
| IMC Networks                           | 34        | 15.32%  |
| Acer                                   | 27        | 12.16%  |
| Realtek Semiconductor                  | 18        | 8.11%   |
| Microdia                               | 18        | 8.11%   |
| Quanta                                 | 12        | 5.41%   |
| Lite-On Technology                     | 10        | 4.5%    |
| Sunplus Innovation Technology          | 8         | 3.6%    |
| Suyin                                  | 7         | 3.15%   |
| Logitech                               | 5         | 2.25%   |
| Apple                                  | 5         | 2.25%   |
| Syntek                                 | 4         | 1.8%    |
| Luxvisions Innotech Limited            | 4         | 1.8%    |
| Lenovo                                 | 4         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.8%    |
| Z-Star Microelectronics                | 1         | 0.45%   |
| Silicon Motion                         | 1         | 0.45%   |
| Ricoh                                  | 1         | 0.45%   |
| Primax Electronics                     | 1         | 0.45%   |
| Pixart Imaging                         | 1         | 0.45%   |
| eMPIA Technology                       | 1         | 0.45%   |
| ALi                                    | 1         | 0.45%   |
| Alcor Micro                            | 1         | 0.45%   |
| A4Tech                                 | 1         | 0.45%   |
| 8SSC20F27114V1SR11K1SE2                | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 18        | 8.07%   |
| IMC Networks Integrated Camera                          | 12        | 5.38%   |
| Microdia Integrated_Webcam_HD                           | 10        | 4.48%   |
| Realtek Integrated_Webcam_HD                            | 9         | 4.04%   |
| Chicony HD WebCam                                       | 9         | 4.04%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 3.59%   |
| Acer Integrated Camera                                  | 8         | 3.59%   |
| Chicony HP HD Camera                                    | 5         | 2.24%   |
| Acer SunplusIT Integrated Camera                        | 5         | 2.24%   |
| Lite-On Integrated Camera                               | 4         | 1.79%   |
| Realtek Integrated Webcam                               | 3         | 1.35%   |
| Quanta HD WebCam                                        | 3         | 1.35%   |
| Microdia Integrated Webcam HD                           | 3         | 1.35%   |
| Lenovo Integrated Webcam                                | 3         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.35%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.35%   |
| Acer ThinkPad Integrated Camera                         | 3         | 1.35%   |
| Syntek Integrated Camera                                | 2         | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 0.9%    |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.9%    |
| Quanta HP TrueVision HD Camera                          | 2         | 0.9%    |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 0.9%    |
| Logitech Webcam C270                                    | 2         | 0.9%    |
| Logitech C505 HD Webcam                                 | 2         | 0.9%    |
| Lite-On HP Webcam                                       | 2         | 0.9%    |
| Lite-On HP HD Camera                                    | 2         | 0.9%    |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 2         | 0.9%    |
| IMC Networks ov9734_azurewave_camera                    | 2         | 0.9%    |
| IMC Networks Lenovo EasyCamera                          | 2         | 0.9%    |
| Chicony USB2.0 Camera                                   | 2         | 0.9%    |
| Chicony ThinkPad T490 Webcam                            | 2         | 0.9%    |
| Chicony Lenovo EasyCamera                               | 2         | 0.9%    |
| Chicony HP HD Webcam                                    | 2         | 0.9%    |
| Apple FaceTime HD Camera                                | 2         | 0.9%    |
| Acer SunplusIT INC. Integrated Camera                   | 2         | 0.9%    |
| Acer Lenovo Integrated Webcam                           | 2         | 0.9%    |
| Acer EasyCamera                                         | 2         | 0.9%    |
| Acer BisonCam, NB Pro                                   | 2         | 0.9%    |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.45%   |
| Syntek USB 2.0 UVC PC Camera                            | 1         | 0.45%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.45%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 1         | 0.45%   |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 0.45%   |
| Suyin HP TrueVision Full HD                             | 1         | 0.45%   |
| Suyin HD WebCam                                         | 1         | 0.45%   |
| Suyin Acer CrystalEye Webcam                            | 1         | 0.45%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 1         | 0.45%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.45%   |
| Sunplus HP Universal Camera                             | 1         | 0.45%   |
| Sunplus Dell E5570 integrated webcam                    | 1         | 0.45%   |
| Sunplus 1.3M HD WebCam                                  | 1         | 0.45%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 1         | 0.45%   |
| Ricoh USB2.0 Camera                                     | 1         | 0.45%   |
| Realtek USB2.0-Camera                                   | 1         | 0.45%   |
| Realtek USB Camera                                      | 1         | 0.45%   |
| Realtek Lenovo EasyCamera                               | 1         | 0.45%   |
| Realtek HD WebCam                                       | 1         | 0.45%   |
| Realtek EasyCamera                                      | 1         | 0.45%   |
| Realtek Acer 640 x 480 laptop camera                    | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 32.76%  |
| Validity Sensors           | 14        | 24.14%  |
| Shenzhen Goodix Technology | 9         | 15.52%  |
| Upek                       | 7         | 12.07%  |
| AuthenTec                  | 4         | 6.9%    |
| Elan Microelectronics      | 3         | 5.17%   |
| LighTuning Technology      | 2         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 15.52%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 12.07%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 10.34%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 8.62%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 8.62%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 6.9%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 5.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 5.17%   |
| Elan ELAN:Fingerprint                                                      | 3         | 5.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 5.17%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.72%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.72%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.72%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.72%   |

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
| 0     | 173       | 63.14%  |
| 1     | 71        | 25.91%  |
| 2     | 28        | 10.22%  |
| 4     | 1         | 0.36%   |
| 3     | 1         | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 44.27%  |
| Chipcard                 | 26        | 19.85%  |
| Graphics card            | 15        | 11.45%  |
| Multimedia controller    | 13        | 9.92%   |
| Net/wireless             | 6         | 4.58%   |
| Communication controller | 4         | 3.05%   |
| Storage                  | 3         | 2.29%   |
| Network                  | 2         | 1.53%   |
| Modem                    | 1         | 0.76%   |
| Firewire controller      | 1         | 0.76%   |
| Card reader              | 1         | 0.76%   |
| Bluetooth                | 1         | 0.76%   |

