NixOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 522

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T490 20N20030US    | [d4dd35d7dc](https://linux-hardware.org/?probe=d4dd35d7dc) | Jan 04, 2025 |
| HP            | Pavilion Laptop 14-ec0xx... | [9bb39e061b](https://linux-hardware.org/?probe=9bb39e061b) | Jan 04, 2025 |
| Lenovo        | Legion 7 16IRX9 83FD        | [7bb0cafb81](https://linux-hardware.org/?probe=7bb0cafb81) | Jan 04, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [041f977a25](https://linux-hardware.org/?probe=041f977a25) | Jan 03, 2025 |
| Framework     | Laptop                      | [a74fd192f3](https://linux-hardware.org/?probe=a74fd192f3) | Jan 03, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [0793ac2320](https://linux-hardware.org/?probe=0793ac2320) | Dec 31, 2024 |
| Acer          | Aspire 5742Z                | [0cda57368f](https://linux-hardware.org/?probe=0cda57368f) | Dec 28, 2024 |
| Dell          | Precision 5690              | [5219297c0d](https://linux-hardware.org/?probe=5219297c0d) | Dec 26, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [95d37ca286](https://linux-hardware.org/?probe=95d37ca286) | Dec 25, 2024 |
| Apple         | MacBookPro11,3              | [b6aa51489b](https://linux-hardware.org/?probe=b6aa51489b) | Dec 22, 2024 |
| ASUSTek       | ROG Zephyrus G16 GA605WI... | [0b5149cbce](https://linux-hardware.org/?probe=0b5149cbce) | Dec 18, 2024 |
| HP            | EliteBook 2560p             | [084e229e45](https://linux-hardware.org/?probe=084e229e45) | Dec 18, 2024 |
| Samsung       | 900X3N                      | [672751a071](https://linux-hardware.org/?probe=672751a071) | Dec 17, 2024 |
| GPD           | G1622-01                    | [daa5825210](https://linux-hardware.org/?probe=daa5825210) | Dec 17, 2024 |
| GPD           | G1622-01                    | [bd716cf271](https://linux-hardware.org/?probe=bd716cf271) | Dec 17, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | [063c4b21a8](https://linux-hardware.org/?probe=063c4b21a8) | Dec 16, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21NQ    | [5c45e2bfee](https://linux-hardware.org/?probe=5c45e2bfee) | Dec 16, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [083f4404b5](https://linux-hardware.org/?probe=083f4404b5) | Dec 14, 2024 |
| Apple         | MacBookPro11,5              | [76bab8abed](https://linux-hardware.org/?probe=76bab8abed) | Dec 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [b5059cca85](https://linux-hardware.org/?probe=b5059cca85) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [c43e0a8e7d](https://linux-hardware.org/?probe=c43e0a8e7d) | Dec 10, 2024 |
| HP            | Laptop 15-dy2xxx            | [5fd9df1c27](https://linux-hardware.org/?probe=5fd9df1c27) | Dec 07, 2024 |
| Lenovo        | G570 20079                  | [d7ca5ffb0b](https://linux-hardware.org/?probe=d7ca5ffb0b) | Dec 06, 2024 |
| Dell          | Precision 3591              | [af761ba6a9](https://linux-hardware.org/?probe=af761ba6a9) | Dec 05, 2024 |
| Lenovo        | ThinkPad X230 23252CG       | [614068917c](https://linux-hardware.org/?probe=614068917c) | Dec 04, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [12db03cac4](https://linux-hardware.org/?probe=12db03cac4) | Dec 01, 2024 |
| Lenovo        | ThinkPad T450s 20BWS3TM0... | [c32b3f2dd0](https://linux-hardware.org/?probe=c32b3f2dd0) | Nov 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | [773e88d3be](https://linux-hardware.org/?probe=773e88d3be) | Nov 27, 2024 |
| Dell          | XPS 15 9530                 | [df0fd1e685](https://linux-hardware.org/?probe=df0fd1e685) | Nov 27, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [032327d915](https://linux-hardware.org/?probe=032327d915) | Nov 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [24a75e17ae](https://linux-hardware.org/?probe=24a75e17ae) | Nov 26, 2024 |
| HP            | OmniBook Ultra Laptop 14... | [5c64854b38](https://linux-hardware.org/?probe=5c64854b38) | Nov 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | [59205e96b5](https://linux-hardware.org/?probe=59205e96b5) | Nov 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [fa8c5128c6](https://linux-hardware.org/?probe=fa8c5128c6) | Nov 25, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [de16a781fa](https://linux-hardware.org/?probe=de16a781fa) | Nov 24, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [e7b45b99c1](https://linux-hardware.org/?probe=e7b45b99c1) | Nov 23, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [1d2005d912](https://linux-hardware.org/?probe=1d2005d912) | Nov 23, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [bdcf6c541a](https://linux-hardware.org/?probe=bdcf6c541a) | Nov 21, 2024 |
| Lenovo        | ThinkPad T450s 20BWS3TM0... | [0e39a0bdbe](https://linux-hardware.org/?probe=0e39a0bdbe) | Nov 21, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [81b39da9fd](https://linux-hardware.org/?probe=81b39da9fd) | Nov 19, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [24d0062e37](https://linux-hardware.org/?probe=24d0062e37) | Nov 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [fe024604b1](https://linux-hardware.org/?probe=fe024604b1) | Nov 17, 2024 |
| Dell          | Vostro 3500                 | [48169a4553](https://linux-hardware.org/?probe=48169a4553) | Nov 17, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [cf12d8256f](https://linux-hardware.org/?probe=cf12d8256f) | Nov 15, 2024 |
| PC Special... | NS50MU                      | [65a6da58c1](https://linux-hardware.org/?probe=65a6da58c1) | Nov 14, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [68df2e0f71](https://linux-hardware.org/?probe=68df2e0f71) | Nov 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [665265a239](https://linux-hardware.org/?probe=665265a239) | Nov 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3a28af2ad6](https://linux-hardware.org/?probe=3a28af2ad6) | Nov 13, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [193f9b2369](https://linux-hardware.org/?probe=193f9b2369) | Nov 12, 2024 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [6370e4afbb](https://linux-hardware.org/?probe=6370e4afbb) | Nov 10, 2024 |
| Dell          | G5 5590                     | [b797a36b4c](https://linux-hardware.org/?probe=b797a36b4c) | Nov 10, 2024 |
| Apple         | MacBookPro11,5              | [43a210e9cb](https://linux-hardware.org/?probe=43a210e9cb) | Nov 08, 2024 |
| Apple         | MacBookPro11,5              | [502004fe3d](https://linux-hardware.org/?probe=502004fe3d) | Nov 08, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [142462821d](https://linux-hardware.org/?probe=142462821d) | Nov 03, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [f1282c521a](https://linux-hardware.org/?probe=f1282c521a) | Oct 30, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [712493f433](https://linux-hardware.org/?probe=712493f433) | Oct 28, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [7e5bbb938b](https://linux-hardware.org/?probe=7e5bbb938b) | Oct 28, 2024 |
| Framework     | Laptop                      | [072ab62076](https://linux-hardware.org/?probe=072ab62076) | Oct 27, 2024 |
| HP            | ZBook Fury 16 G10 Mobile... | [e903944a84](https://linux-hardware.org/?probe=e903944a84) | Oct 26, 2024 |
| HUAWEI        | HVY-WXX9                    | [9dcb081b32](https://linux-hardware.org/?probe=9dcb081b32) | Oct 25, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [3d80b9eead](https://linux-hardware.org/?probe=3d80b9eead) | Oct 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [51f11aa9f2](https://linux-hardware.org/?probe=51f11aa9f2) | Oct 25, 2024 |
| Dell          | XPS 13 9310                 | [56d5b77e54](https://linux-hardware.org/?probe=56d5b77e54) | Oct 25, 2024 |
| HUAWEI        | HVY-WXX9                    | [04f2f2787e](https://linux-hardware.org/?probe=04f2f2787e) | Oct 25, 2024 |
| Acer          | Aspire A315-24PT            | [5e327ea424](https://linux-hardware.org/?probe=5e327ea424) | Oct 22, 2024 |
| Acer          | Swift SFG14-71              | [3cfedf7732](https://linux-hardware.org/?probe=3cfedf7732) | Oct 21, 2024 |
| Dell          | Latitude 5550               | [31ec440570](https://linux-hardware.org/?probe=31ec440570) | Oct 16, 2024 |
| Lenovo        | Legion 7 16IRX9 83FD        | [bf913685ba](https://linux-hardware.org/?probe=bf913685ba) | Oct 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4dbeafbd5f](https://linux-hardware.org/?probe=4dbeafbd5f) | Oct 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [329cd43769](https://linux-hardware.org/?probe=329cd43769) | Oct 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [661649b768](https://linux-hardware.org/?probe=661649b768) | Oct 13, 2024 |
| Lenovo        | ThinkPad T420 4180DY4       | [5afcda3ff3](https://linux-hardware.org/?probe=5afcda3ff3) | Oct 13, 2024 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [20b06b0861](https://linux-hardware.org/?probe=20b06b0861) | Oct 13, 2024 |
| Lenovo        | Yoga 500-14IBD 80N4         | [634a88ef95](https://linux-hardware.org/?probe=634a88ef95) | Oct 12, 2024 |
| Lenovo        | ThinkPad L380 20M6S3UN00    | [8b17bec7be](https://linux-hardware.org/?probe=8b17bec7be) | Oct 12, 2024 |
| Dell          | Latitude E6540              | [ea8afd6f6b](https://linux-hardware.org/?probe=ea8afd6f6b) | Oct 12, 2024 |
| Dell          | Inspiron 5580               | [6e246c56fb](https://linux-hardware.org/?probe=6e246c56fb) | Oct 12, 2024 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [3d7009833d](https://linux-hardware.org/?probe=3d7009833d) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [491f1090ca](https://linux-hardware.org/?probe=491f1090ca) | Oct 10, 2024 |
| Lenovo        | ThinkPad T480s 20L7S0BM0... | [64ef0dbb14](https://linux-hardware.org/?probe=64ef0dbb14) | Oct 09, 2024 |
| Acer          | Aspire A315-44P             | [65b854b6d3](https://linux-hardware.org/?probe=65b854b6d3) | Oct 08, 2024 |
| Dell          | G15 5511                    | [ed9b86e723](https://linux-hardware.org/?probe=ed9b86e723) | Oct 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [160ad6e49e](https://linux-hardware.org/?probe=160ad6e49e) | Oct 07, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [1e2e268764](https://linux-hardware.org/?probe=1e2e268764) | Oct 06, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [728d0f4561](https://linux-hardware.org/?probe=728d0f4561) | Oct 06, 2024 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [d44dc9b966](https://linux-hardware.org/?probe=d44dc9b966) | Oct 04, 2024 |
| Acer          | Aspire A315-44P             | [3aaeee6d1b](https://linux-hardware.org/?probe=3aaeee6d1b) | Oct 03, 2024 |
| Lenovo        | ThinkPad X250 20CLS02000    | [bb75759114](https://linux-hardware.org/?probe=bb75759114) | Sep 26, 2024 |
| Acer          | Aspire A715-41G             | [28630e6b4e](https://linux-hardware.org/?probe=28630e6b4e) | Sep 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2fc188f296](https://linux-hardware.org/?probe=2fc188f296) | Sep 25, 2024 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [2282ce51ba](https://linux-hardware.org/?probe=2282ce51ba) | Sep 25, 2024 |
| Dell          | Inspiron N5110              | [cf26c5a0b7](https://linux-hardware.org/?probe=cf26c5a0b7) | Sep 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [34bb43620b](https://linux-hardware.org/?probe=34bb43620b) | Sep 24, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [fd06da7fc1](https://linux-hardware.org/?probe=fd06da7fc1) | Sep 22, 2024 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [6cdf2f1f7f](https://linux-hardware.org/?probe=6cdf2f1f7f) | Sep 22, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [ab1b90b470](https://linux-hardware.org/?probe=ab1b90b470) | Sep 21, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [3febc58555](https://linux-hardware.org/?probe=3febc58555) | Sep 21, 2024 |
| MSI           | Alpha 15 B5EEK              | [404017af65](https://linux-hardware.org/?probe=404017af65) | Sep 20, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [fdcd6421d6](https://linux-hardware.org/?probe=fdcd6421d6) | Sep 20, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [a3f44fecb0](https://linux-hardware.org/?probe=a3f44fecb0) | Sep 18, 2024 |
| Lenovo        | ThinkPad X250 20CLS02000    | [add0feabb8](https://linux-hardware.org/?probe=add0feabb8) | Sep 17, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [28e8212852](https://linux-hardware.org/?probe=28e8212852) | Sep 16, 2024 |
| Acer          | Swift SF314-43              | [58150ad2bf](https://linux-hardware.org/?probe=58150ad2bf) | Sep 11, 2024 |
| Acer          | Predator PT316-51s          | [6115a8c519](https://linux-hardware.org/?probe=6115a8c519) | Sep 11, 2024 |
| Acer          | Predator PH315-54           | [c781f9222b](https://linux-hardware.org/?probe=c781f9222b) | Sep 10, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [97358eeb4e](https://linux-hardware.org/?probe=97358eeb4e) | Sep 09, 2024 |
| Dell          | Precision 3520              | [860ad42896](https://linux-hardware.org/?probe=860ad42896) | Sep 09, 2024 |
| Dell          | XPS 17 9700                 | [c91858771e](https://linux-hardware.org/?probe=c91858771e) | Sep 09, 2024 |
| Dell          | Inspiron 7548               | [150c9ec14f](https://linux-hardware.org/?probe=150c9ec14f) | Sep 09, 2024 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [cc11d84cd6](https://linux-hardware.org/?probe=cc11d84cd6) | Sep 09, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [b06892eff4](https://linux-hardware.org/?probe=b06892eff4) | Sep 09, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [062d642cdc](https://linux-hardware.org/?probe=062d642cdc) | Sep 09, 2024 |
| Framework     | Laptop                      | [2e42d66339](https://linux-hardware.org/?probe=2e42d66339) | Sep 09, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [a9c678a896](https://linux-hardware.org/?probe=a9c678a896) | Sep 08, 2024 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [224c031297](https://linux-hardware.org/?probe=224c031297) | Sep 08, 2024 |
| Dell          | Inspiron 7577               | [fd08888941](https://linux-hardware.org/?probe=fd08888941) | Sep 08, 2024 |
| MSI           | Modern 14 B5M               | [9978e53d19](https://linux-hardware.org/?probe=9978e53d19) | Sep 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [69d9359729](https://linux-hardware.org/?probe=69d9359729) | Sep 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | [5d86305564](https://linux-hardware.org/?probe=5d86305564) | Sep 08, 2024 |
| Apple         | MacBookAir5,2               | [c0b8fe17cd](https://linux-hardware.org/?probe=c0b8fe17cd) | Sep 08, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [1ef6ad8d15](https://linux-hardware.org/?probe=1ef6ad8d15) | Sep 08, 2024 |
| Razer         | Blade                       | [b0a9880c36](https://linux-hardware.org/?probe=b0a9880c36) | Sep 08, 2024 |
| Dell          | Inspiron 7570               | [8487de4413](https://linux-hardware.org/?probe=8487de4413) | Sep 08, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [b44174619d](https://linux-hardware.org/?probe=b44174619d) | Sep 08, 2024 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [e23fc38add](https://linux-hardware.org/?probe=e23fc38add) | Sep 08, 2024 |
| Dell          | Latitude 7390 2-in-1        | [0acf653766](https://linux-hardware.org/?probe=0acf653766) | Sep 08, 2024 |
| Dell          | G5 5500                     | [047302a678](https://linux-hardware.org/?probe=047302a678) | Sep 08, 2024 |
| Razer         | Blade Stealth 13 (Early ... | [55cb30169f](https://linux-hardware.org/?probe=55cb30169f) | Sep 08, 2024 |
| Timi          | Redmi Book Pro 14 2022      | [7dfc2463f0](https://linux-hardware.org/?probe=7dfc2463f0) | Sep 06, 2024 |
| Apple         | MacBookPro11,5              | [62a1441324](https://linux-hardware.org/?probe=62a1441324) | Sep 05, 2024 |
| MSI           | Modern 14 B5M               | [3d4ad593f5](https://linux-hardware.org/?probe=3d4ad593f5) | Sep 02, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [7b534afcea](https://linux-hardware.org/?probe=7b534afcea) | Sep 02, 2024 |
| HP            | ZBook 14 G2                 | [7f0dc8a5ee](https://linux-hardware.org/?probe=7f0dc8a5ee) | Aug 30, 2024 |
| HP            | ZBook 14 G2                 | [0afb138cf7](https://linux-hardware.org/?probe=0afb138cf7) | Aug 30, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [62b809ea1a](https://linux-hardware.org/?probe=62b809ea1a) | Aug 28, 2024 |
| Samsung       | 960XFH                      | [a7b8e567a2](https://linux-hardware.org/?probe=a7b8e567a2) | Aug 23, 2024 |
| TUXEDO        | Pulse 15 Gen2               | [cb12a91b1e](https://linux-hardware.org/?probe=cb12a91b1e) | Aug 23, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [179947d1fc](https://linux-hardware.org/?probe=179947d1fc) | Aug 23, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [06ff184117](https://linux-hardware.org/?probe=06ff184117) | Aug 23, 2024 |
| Dell          | XPS 15 9530                 | [ac9fcbda82](https://linux-hardware.org/?probe=ac9fcbda82) | Aug 20, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e0af5cb80e](https://linux-hardware.org/?probe=e0af5cb80e) | Aug 19, 2024 |
| Acer          | Nitro AN515-42              | [87094d4adb](https://linux-hardware.org/?probe=87094d4adb) | Aug 18, 2024 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | [01ce920620](https://linux-hardware.org/?probe=01ce920620) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [4168e29e3b](https://linux-hardware.org/?probe=4168e29e3b) | Aug 16, 2024 |
| Unknown       | Unknown                     | [00173eebcb](https://linux-hardware.org/?probe=00173eebcb) | Aug 16, 2024 |
| System76      | Darter Pro                  | [1fbb688f8e](https://linux-hardware.org/?probe=1fbb688f8e) | Aug 16, 2024 |
| Razer         | Blade 14 - RZ09-0370        | [aec3920dda](https://linux-hardware.org/?probe=aec3920dda) | Aug 15, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [aa503d6674](https://linux-hardware.org/?probe=aa503d6674) | Aug 15, 2024 |
| Dell          | Vostro 3500                 | [647b4d4e05](https://linux-hardware.org/?probe=647b4d4e05) | Aug 14, 2024 |
| Acer          | Aspire A715-42G             | [59afb561de](https://linux-hardware.org/?probe=59afb561de) | Aug 14, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [e7ab69fde0](https://linux-hardware.org/?probe=e7ab69fde0) | Aug 11, 2024 |
| System76      | Pangolin                    | [322cfe0ba1](https://linux-hardware.org/?probe=322cfe0ba1) | Aug 09, 2024 |
| Chuwi         | MiniBook X                  | [6440423423](https://linux-hardware.org/?probe=6440423423) | Aug 08, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [9465561e04](https://linux-hardware.org/?probe=9465561e04) | Aug 08, 2024 |
| Google        | Nami                        | [73af4eb516](https://linux-hardware.org/?probe=73af4eb516) | Aug 07, 2024 |
| Acer          | Aspire A515-56              | [79f287dfa8](https://linux-hardware.org/?probe=79f287dfa8) | Aug 06, 2024 |
| HP            | Laptop 15s-eq2xxx           | [851c57320e](https://linux-hardware.org/?probe=851c57320e) | Aug 06, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [22d2660f10](https://linux-hardware.org/?probe=22d2660f10) | Aug 04, 2024 |
| Dell          | XPS 9315                    | [0532ec9631](https://linux-hardware.org/?probe=0532ec9631) | Aug 03, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [2f0fc05b00](https://linux-hardware.org/?probe=2f0fc05b00) | Aug 01, 2024 |
| Dell          | Latitude E7240              | [11f88b9caf](https://linux-hardware.org/?probe=11f88b9caf) | Jul 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [9f8143243c](https://linux-hardware.org/?probe=9f8143243c) | Jul 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [1038ccd86b](https://linux-hardware.org/?probe=1038ccd86b) | Jul 28, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [a717781b71](https://linux-hardware.org/?probe=a717781b71) | Jul 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a158056c57](https://linux-hardware.org/?probe=a158056c57) | Jul 27, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [0219498bb7](https://linux-hardware.org/?probe=0219498bb7) | Jul 26, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [2a25ba03a4](https://linux-hardware.org/?probe=2a25ba03a4) | Jul 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7ddcc47c13](https://linux-hardware.org/?probe=7ddcc47c13) | Jul 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4c5754c4b3](https://linux-hardware.org/?probe=4c5754c4b3) | Jul 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [08c05a5904](https://linux-hardware.org/?probe=08c05a5904) | Jul 24, 2024 |
| Apple         | MacBookPro16,1              | [45cee76121](https://linux-hardware.org/?probe=45cee76121) | Jul 21, 2024 |
| Acer          | Predator PH315-51           | [f36e31d89f](https://linux-hardware.org/?probe=f36e31d89f) | Jul 20, 2024 |
| Lenovo        | ThinkBook 14 G5+ APO 21J... | [c544d39f9f](https://linux-hardware.org/?probe=c544d39f9f) | Jul 20, 2024 |
| MSI           | Katana GF76 11UC            | [8ef6e6c1ae](https://linux-hardware.org/?probe=8ef6e6c1ae) | Jul 20, 2024 |
| HP            | EliteBook 840 14 inch G1... | [90031d618e](https://linux-hardware.org/?probe=90031d618e) | Jul 18, 2024 |
| Acer          | Predator PH315-51           | [c0fb0f5d78](https://linux-hardware.org/?probe=c0fb0f5d78) | Jul 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [aed926371d](https://linux-hardware.org/?probe=aed926371d) | Jul 15, 2024 |
| Lenovo        | Legion Y7000 81FW           | [828ea2e910](https://linux-hardware.org/?probe=828ea2e910) | Jul 13, 2024 |
| Lenovo        | ThinkPad P51s 20HB000VPG    | [fc2a09d595](https://linux-hardware.org/?probe=fc2a09d595) | Jul 11, 2024 |
| Lenovo        | ThinkPad T495 20NKS2JD00    | [c4c6fededf](https://linux-hardware.org/?probe=c4c6fededf) | Jul 11, 2024 |
| Apple         | MacBookPro11,1              | [ea25c8dde3](https://linux-hardware.org/?probe=ea25c8dde3) | Jul 11, 2024 |
| HUAWEI        | BOM-WXX9                    | [e1097cce91](https://linux-hardware.org/?probe=e1097cce91) | Jul 10, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [2d96a14cd7](https://linux-hardware.org/?probe=2d96a14cd7) | Jul 07, 2024 |
| Acer          | Nitro AN515-52              | [96d82e2cb3](https://linux-hardware.org/?probe=96d82e2cb3) | Jul 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f846e6d9a0](https://linux-hardware.org/?probe=f846e6d9a0) | Jul 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JS0... | [8aec324881](https://linux-hardware.org/?probe=8aec324881) | Jul 03, 2024 |
| Dynabook      | PORTEGE X30L-K              | [20e1176fed](https://linux-hardware.org/?probe=20e1176fed) | Jul 03, 2024 |
| HUAWEI        | VGHH-XX                     | [3676bfc771](https://linux-hardware.org/?probe=3676bfc771) | Jun 24, 2024 |
| Apple         | MacBookPro11,4              | [e77b8b7c1a](https://linux-hardware.org/?probe=e77b8b7c1a) | Jun 22, 2024 |
| HP            | OMEN by Transcend Gaming... | [f95edc487c](https://linux-hardware.org/?probe=f95edc487c) | Jun 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [238ea6a5e2](https://linux-hardware.org/?probe=238ea6a5e2) | Jun 16, 2024 |
| PC Special... | Recoil II                   | [9003dfdb47](https://linux-hardware.org/?probe=9003dfdb47) | Jun 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [021499aed9](https://linux-hardware.org/?probe=021499aed9) | Jun 08, 2024 |
| HP            | EliteBook Folio 9470m       | [d9e925bab3](https://linux-hardware.org/?probe=d9e925bab3) | Jun 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1be0efeb19](https://linux-hardware.org/?probe=1be0efeb19) | Jun 07, 2024 |
| Dell          | G3 3500                     | [e7ad9fe987](https://linux-hardware.org/?probe=e7ad9fe987) | Jun 06, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [2c59b90cde](https://linux-hardware.org/?probe=2c59b90cde) | Jun 06, 2024 |
| HP            | Laptop 15-dy2xxx            | [5ef8fbaf58](https://linux-hardware.org/?probe=5ef8fbaf58) | Jun 06, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [0e6ffaf99b](https://linux-hardware.org/?probe=0e6ffaf99b) | Jun 02, 2024 |
| Lenovo        | ThinkPad X250 20CLS1EW00    | [6f51b55a35](https://linux-hardware.org/?probe=6f51b55a35) | Jun 01, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [12df9c0f8e](https://linux-hardware.org/?probe=12df9c0f8e) | Jun 01, 2024 |
| PC Special... | Recoil II                   | [0e6bc15b29](https://linux-hardware.org/?probe=0e6bc15b29) | May 30, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [38e45316b1](https://linux-hardware.org/?probe=38e45316b1) | May 28, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [e63220aa5e](https://linux-hardware.org/?probe=e63220aa5e) | May 27, 2024 |
| Dell          | G3 3779                     | [26ce6cbc7d](https://linux-hardware.org/?probe=26ce6cbc7d) | May 25, 2024 |
| Dell          | Inspiron 7577               | [db403a9f18](https://linux-hardware.org/?probe=db403a9f18) | May 21, 2024 |
| Apple         | MacBookAir7,2               | [3caec5604a](https://linux-hardware.org/?probe=3caec5604a) | May 20, 2024 |
| Google        | Babytiger                   | [9fe14fb0f5](https://linux-hardware.org/?probe=9fe14fb0f5) | May 14, 2024 |
| Google        | Babytiger                   | [b0f37ce546](https://linux-hardware.org/?probe=b0f37ce546) | May 14, 2024 |
| Lenovo        | ThinkPad X395 20NM0002GE    | [2deda1aba0](https://linux-hardware.org/?probe=2deda1aba0) | May 13, 2024 |
| Apple         | MacBookPro8,1               | [3598463988](https://linux-hardware.org/?probe=3598463988) | May 12, 2024 |
| Acer          | Predator PH315-51           | [a065a819ff](https://linux-hardware.org/?probe=a065a819ff) | May 11, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9c7ba4a173](https://linux-hardware.org/?probe=9c7ba4a173) | May 10, 2024 |
| Razer         | Blade 14 - RZ09-0508        | [2f6237a9a5](https://linux-hardware.org/?probe=2f6237a9a5) | May 10, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [161509c62b](https://linux-hardware.org/?probe=161509c62b) | May 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [44f44fe800](https://linux-hardware.org/?probe=44f44fe800) | May 06, 2024 |
| Apple         | MacBookPro16,2              | [fe05b165fb](https://linux-hardware.org/?probe=fe05b165fb) | May 04, 2024 |
| Acer          | Predator PH315-51           | [6cadb88b1d](https://linux-hardware.org/?probe=6cadb88b1d) | May 01, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [90807317fb](https://linux-hardware.org/?probe=90807317fb) | May 01, 2024 |
| Apple         | MacBookPro11,2              | [5cd273406c](https://linux-hardware.org/?probe=5cd273406c) | Apr 30, 2024 |
| ASUSTek       | K53SJ                       | [45bc744085](https://linux-hardware.org/?probe=45bc744085) | Apr 28, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [86305e383e](https://linux-hardware.org/?probe=86305e383e) | Apr 25, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [113c93d444](https://linux-hardware.org/?probe=113c93d444) | Apr 25, 2024 |
| Dell          | Latitude 7330 Rugged Ext... | [787276b922](https://linux-hardware.org/?probe=787276b922) | Apr 25, 2024 |
| Dell          | XPS 15 9530                 | [e1d4486b51](https://linux-hardware.org/?probe=e1d4486b51) | Apr 24, 2024 |
| HP            | ProBook 440 G2              | [e5a4a84406](https://linux-hardware.org/?probe=e5a4a84406) | Apr 23, 2024 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [bf31c1e8e2](https://linux-hardware.org/?probe=bf31c1e8e2) | Apr 22, 2024 |
| Razer         | Blade 14 - RZ09-0508        | [cc1f5421e7](https://linux-hardware.org/?probe=cc1f5421e7) | Apr 21, 2024 |
| MSI           | GE60 2PE                    | [38cce299c6](https://linux-hardware.org/?probe=38cce299c6) | Apr 18, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ba533ecb3a](https://linux-hardware.org/?probe=ba533ecb3a) | Apr 18, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MH     | [d56c554eed](https://linux-hardware.org/?probe=d56c554eed) | Apr 16, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [6a7d29fe24](https://linux-hardware.org/?probe=6a7d29fe24) | Apr 15, 2024 |
| Razer         | Blade                       | [8ff543883a](https://linux-hardware.org/?probe=8ff543883a) | Apr 14, 2024 |
| Apple         | MacBookPro11,3              | [159bfe4be5](https://linux-hardware.org/?probe=159bfe4be5) | Apr 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [90946053e1](https://linux-hardware.org/?probe=90946053e1) | Apr 11, 2024 |
| Apple         | MacBookPro11,5              | [d48fd50ca7](https://linux-hardware.org/?probe=d48fd50ca7) | Apr 11, 2024 |
| Apple         | MacBookPro10,1              | [c468075794](https://linux-hardware.org/?probe=c468075794) | Apr 11, 2024 |
| MSI           | GL65 9SC                    | [7bc8965c5e](https://linux-hardware.org/?probe=7bc8965c5e) | Apr 10, 2024 |
| Google        | Redrix                      | [6dd8afed85](https://linux-hardware.org/?probe=6dd8afed85) | Apr 10, 2024 |
| Apple         | MacBookPro12,1              | [50c4a83180](https://linux-hardware.org/?probe=50c4a83180) | Apr 07, 2024 |
| System76      | Oryx Pro                    | [4592d774b4](https://linux-hardware.org/?probe=4592d774b4) | Apr 06, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [81925bcc23](https://linux-hardware.org/?probe=81925bcc23) | Apr 05, 2024 |
| Acer          | Swift SF514-54GT            | [c0a1536935](https://linux-hardware.org/?probe=c0a1536935) | Mar 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [57aabe3115](https://linux-hardware.org/?probe=57aabe3115) | Mar 26, 2024 |
| Dell          | Latitude 7420               | [511721b690](https://linux-hardware.org/?probe=511721b690) | Mar 23, 2024 |
| Lenovo        | V15-ADA 82C7                | [9fce956c50](https://linux-hardware.org/?probe=9fce956c50) | Mar 23, 2024 |
| HONOR         | BMH-WDX9                    | [4445879c66](https://linux-hardware.org/?probe=4445879c66) | Mar 21, 2024 |
| Timi          | Redmi Book Pro 14 2022      | [164d9ccd8d](https://linux-hardware.org/?probe=164d9ccd8d) | Mar 21, 2024 |
| HONOR         | BMH-WDX9                    | [01284be05a](https://linux-hardware.org/?probe=01284be05a) | Mar 20, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [027fecc047](https://linux-hardware.org/?probe=027fecc047) | Mar 18, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [def7c584ff](https://linux-hardware.org/?probe=def7c584ff) | Mar 17, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [3906b06830](https://linux-hardware.org/?probe=3906b06830) | Mar 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [5bad97c6ec](https://linux-hardware.org/?probe=5bad97c6ec) | Mar 15, 2024 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [06ecea6114](https://linux-hardware.org/?probe=06ecea6114) | Mar 12, 2024 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [10e971349c](https://linux-hardware.org/?probe=10e971349c) | Mar 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [25074d4407](https://linux-hardware.org/?probe=25074d4407) | Mar 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [8a0a1f3b4a](https://linux-hardware.org/?probe=8a0a1f3b4a) | Mar 01, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | [ce625cdb1a](https://linux-hardware.org/?probe=ce625cdb1a) | Feb 29, 2024 |
| HP            | Pavilion Power Laptop 15... | [43919c6c44](https://linux-hardware.org/?probe=43919c6c44) | Feb 29, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | [7b3b02bc41](https://linux-hardware.org/?probe=7b3b02bc41) | Feb 28, 2024 |
| MSI           | GL65 9SC                    | [6981398659](https://linux-hardware.org/?probe=6981398659) | Feb 28, 2024 |
| Lenovo        | ThinkPad T480s 20L7S3750... | [8bdc7efaf7](https://linux-hardware.org/?probe=8bdc7efaf7) | Feb 28, 2024 |
| Dell          | Latitude 7420               | [fd13235e39](https://linux-hardware.org/?probe=fd13235e39) | Feb 27, 2024 |
| Lenovo        | Yoga 2 Pro 20266            | [6185ab568b](https://linux-hardware.org/?probe=6185ab568b) | Feb 27, 2024 |
| Lenovo        | Legion R9000P ARX8 82WM     | [f6c8d11592](https://linux-hardware.org/?probe=f6c8d11592) | Feb 26, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [848c852446](https://linux-hardware.org/?probe=848c852446) | Feb 25, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [f4e1c02b92](https://linux-hardware.org/?probe=f4e1c02b92) | Feb 21, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [bccce50111](https://linux-hardware.org/?probe=bccce50111) | Feb 21, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [d8f261643b](https://linux-hardware.org/?probe=d8f261643b) | Feb 21, 2024 |
| Lenovo        | Y720-15IKB 81CQ             | [c62e8797a8](https://linux-hardware.org/?probe=c62e8797a8) | Feb 19, 2024 |
| Lenovo        | ThinkPad Edge E531 68859... | [45a495ee7d](https://linux-hardware.org/?probe=45a495ee7d) | Feb 14, 2024 |
| Acer          | AOD270                      | [a0b7e5e68a](https://linux-hardware.org/?probe=a0b7e5e68a) | Feb 11, 2024 |
| Lenovo        | XiaoXinPro-13IML 2019 81... | [66c0cc51e3](https://linux-hardware.org/?probe=66c0cc51e3) | Feb 06, 2024 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [ea8930c46e](https://linux-hardware.org/?probe=ea8930c46e) | Feb 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [fe7dfd8247](https://linux-hardware.org/?probe=fe7dfd8247) | Feb 02, 2024 |
| Apple         | MacBookPro11,5              | [55197489b0](https://linux-hardware.org/?probe=55197489b0) | Feb 02, 2024 |
| Corsair       | Voyager a1600               | [86aec463cc](https://linux-hardware.org/?probe=86aec463cc) | Jan 30, 2024 |
| Corsair       | Voyager a1600               | [00605bf92c](https://linux-hardware.org/?probe=00605bf92c) | Jan 28, 2024 |
| Sony          | VGN-CS11S_Q                 | [df687ca726](https://linux-hardware.org/?probe=df687ca726) | Jan 26, 2024 |
| Apple         | MacBookPro11,5              | [d7308911e4](https://linux-hardware.org/?probe=d7308911e4) | Jan 26, 2024 |
| Framework     | Laptop                      | [64d0e147fe](https://linux-hardware.org/?probe=64d0e147fe) | Jan 25, 2024 |
| Sony          | VGN-CS11S_Q                 | [4c9e427a30](https://linux-hardware.org/?probe=4c9e427a30) | Jan 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [4a41cdcc67](https://linux-hardware.org/?probe=4a41cdcc67) | Jan 25, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2be9790ea](https://linux-hardware.org/?probe=c2be9790ea) | Jan 25, 2024 |
| Lenovo        | ThinkPad T495 20NJ0016MX    | [31aa08c915](https://linux-hardware.org/?probe=31aa08c915) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [553986db8b](https://linux-hardware.org/?probe=553986db8b) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f73bc25ab5](https://linux-hardware.org/?probe=f73bc25ab5) | Jan 17, 2024 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [ca16a763c8](https://linux-hardware.org/?probe=ca16a763c8) | Jan 17, 2024 |
| System76      | Oryx Pro                    | [db771e1a08](https://linux-hardware.org/?probe=db771e1a08) | Jan 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8578d3d843](https://linux-hardware.org/?probe=8578d3d843) | Jan 15, 2024 |
| Apple         | MacBookPro3,1               | [87d8854210](https://linux-hardware.org/?probe=87d8854210) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | [9297ef72df](https://linux-hardware.org/?probe=9297ef72df) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | [17fa0ca044](https://linux-hardware.org/?probe=17fa0ca044) | Jan 12, 2024 |
| Timi          | Xiaomi Book Pro 16 2022     | [ee3988fb25](https://linux-hardware.org/?probe=ee3988fb25) | Jan 09, 2024 |
| Dell          | XPS 15 9530                 | [40a1d7ca08](https://linux-hardware.org/?probe=40a1d7ca08) | Jan 08, 2024 |
| HUAWEI        | WRT-WX9                     | [5b9a494436](https://linux-hardware.org/?probe=5b9a494436) | Jan 08, 2024 |
| Dell          | XPS 9315                    | [af18bb67fd](https://linux-hardware.org/?probe=af18bb67fd) | Jan 08, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [00c7d53339](https://linux-hardware.org/?probe=00c7d53339) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U7412              | [e7b60f15e8](https://linux-hardware.org/?probe=e7b60f15e8) | Jan 08, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [739eae84a2](https://linux-hardware.org/?probe=739eae84a2) | Jan 07, 2024 |
| Dell          | Inspiron 5767               | [460e0f5fa4](https://linux-hardware.org/?probe=460e0f5fa4) | Jan 05, 2024 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [8d22dafe25](https://linux-hardware.org/?probe=8d22dafe25) | Jan 03, 2024 |
| Dynabook      | PORTEGE X30L-K              | [9c965e61f4](https://linux-hardware.org/?probe=9c965e61f4) | Jan 02, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [5ea7f924df](https://linux-hardware.org/?probe=5ea7f924df) | Jan 02, 2024 |
| Lenovo        | ThinkPad Twist 33476LU      | [bb88a71510](https://linux-hardware.org/?probe=bb88a71510) | Jan 01, 2024 |
| System76      | Serval WS                   | [3dd4d45859](https://linux-hardware.org/?probe=3dd4d45859) | Dec 30, 2023 |
| Acer          | Aspire A515-54G             | [35e2f8c10c](https://linux-hardware.org/?probe=35e2f8c10c) | Dec 29, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Dell          | XPS 13 9380                 | [541f2d959f](https://linux-hardware.org/?probe=541f2d959f) | Dec 26, 2023 |
| Fujitsu       | LIFEBOOK U7412              | [a2797ec36b](https://linux-hardware.org/?probe=a2797ec36b) | Dec 26, 2023 |
| HP            | ZBook 17 G5                 | [ad6c489ffc](https://linux-hardware.org/?probe=ad6c489ffc) | Dec 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ef18e09b69](https://linux-hardware.org/?probe=ef18e09b69) | Dec 23, 2023 |
| Lenovo        | Legion Y7000 81FW           | [f67367aa62](https://linux-hardware.org/?probe=f67367aa62) | Dec 23, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [fb187c2fa4](https://linux-hardware.org/?probe=fb187c2fa4) | Dec 20, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [73693b1a91](https://linux-hardware.org/?probe=73693b1a91) | Dec 17, 2023 |
| Lenovo        | Legion Y7000 81FW           | [71c27a1bf6](https://linux-hardware.org/?probe=71c27a1bf6) | Dec 17, 2023 |
| Medion        | M14L-256                    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [87be870a89](https://linux-hardware.org/?probe=87be870a89) | Dec 09, 2023 |
| MSI           | Prestige 14 A10SC           | [85d6d037cc](https://linux-hardware.org/?probe=85d6d037cc) | Dec 09, 2023 |
| Dell          | G5 5590                     | [6970987854](https://linux-hardware.org/?probe=6970987854) | Dec 08, 2023 |
| HP            | EliteBook 850 G5            | [aae20908c5](https://linux-hardware.org/?probe=aae20908c5) | Dec 05, 2023 |
| Dell          | Latitude 5290 2-in-1        | [525166f0d5](https://linux-hardware.org/?probe=525166f0d5) | Dec 04, 2023 |
| Apple         | MacBookPro9,2               | [1784c4c5b0](https://linux-hardware.org/?probe=1784c4c5b0) | Dec 01, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [9f7f83e1ee](https://linux-hardware.org/?probe=9f7f83e1ee) | Nov 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [05c1dddd8d](https://linux-hardware.org/?probe=05c1dddd8d) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450s 20BX001MU... | [80d4678e90](https://linux-hardware.org/?probe=80d4678e90) | Nov 23, 2023 |
| HP            | EliteBook 850 G5            | [602aeb4101](https://linux-hardware.org/?probe=602aeb4101) | Nov 22, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [4065934176](https://linux-hardware.org/?probe=4065934176) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [fbde674650](https://linux-hardware.org/?probe=fbde674650) | Nov 22, 2023 |
| Apple         | MacBookPro11,4              | [f21a42a965](https://linux-hardware.org/?probe=f21a42a965) | Nov 16, 2023 |
| Apple         | MacBookPro9,2               | [ac7deed0de](https://linux-hardware.org/?probe=ac7deed0de) | Nov 16, 2023 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [455efd5541](https://linux-hardware.org/?probe=455efd5541) | Nov 15, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [ce6a10d6a3](https://linux-hardware.org/?probe=ce6a10d6a3) | Nov 15, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [789eee99a6](https://linux-hardware.org/?probe=789eee99a6) | Nov 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [c55053fa25](https://linux-hardware.org/?probe=c55053fa25) | Nov 12, 2023 |
| HP            | EliteBook 845 14 inch G1... | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [79e23fd44a](https://linux-hardware.org/?probe=79e23fd44a) | Nov 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [2f6078ab72](https://linux-hardware.org/?probe=2f6078ab72) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | [0e5f976d6b](https://linux-hardware.org/?probe=0e5f976d6b) | Nov 02, 2023 |
| Dell          | XPS 9315                    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| HP            | EliteBook 850 G4            | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Apple         | MacBookPro9,2               | [b075cf8841](https://linux-hardware.org/?probe=b075cf8841) | Oct 28, 2023 |
| HP            | EliteBook Folio 9470m       | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | [a80fcc753e](https://linux-hardware.org/?probe=a80fcc753e) | Oct 25, 2023 |
| MSI           | GE70 2PE                    | [c0bcd133c9](https://linux-hardware.org/?probe=c0bcd133c9) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Framework     | Laptop                      | [e765d5da63](https://linux-hardware.org/?probe=e765d5da63) | Oct 18, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [7ff5fe9fdd](https://linux-hardware.org/?probe=7ff5fe9fdd) | Oct 11, 2023 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | [a4d6af03fe](https://linux-hardware.org/?probe=a4d6af03fe) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| Dell          | Latitude E6540              | [fc3ea4bb32](https://linux-hardware.org/?probe=fc3ea4bb32) | Oct 08, 2023 |
| Dell          | Inspiron 3542               | [90f777d9cc](https://linux-hardware.org/?probe=90f777d9cc) | Oct 07, 2023 |
| Dell          | Latitude E6540              | [a4fbd5793d](https://linux-hardware.org/?probe=a4fbd5793d) | Oct 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [c67f66f5e3](https://linux-hardware.org/?probe=c67f66f5e3) | Oct 01, 2023 |
| Dell          | Latitude E6540              | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| Dell          | Latitude 5430               | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| Dell          | XPS 15 9560                 | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| Dell          | Latitude E6540              | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
| Dell          | Precision 5680              | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Lenovo        | G50-70 20351                | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| HP            | EliteBook 8470p             | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Apple         | MacBookPro11,3              | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| MSI           | Alpha 15 B5EEK              | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| MACHENIKE     | F117-7P                     | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Dell          | Latitude 5290 2-in-1        | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Apple         | MacBookPro11,5              | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| UNOWHY        | Y13G011S4EI                 | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Lenovo        | G50-70 20351                | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| Apple         | MacBookPro11,3              | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Avell High... | A70 MOB                     | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Dell          | XPS 9320                    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| ASUSTek       | 1005HA                      | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| Dell          | Latitude 7420               | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Dell          | Precision M4800             | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| Dell          | XPS 15 7590                 | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Acer          | Aspire A315-54K             | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| Dell          | Precision 5760              | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Dell          | XPS 13 9310                 | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Dell          | Precision M4800             | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Apple         | MacBookPro11,5              | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| Apple         | MacBookPro11,5              | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| Dell          | XPS 13 9310                 | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| Apple         | MacBookPro11,5              | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| GPD           | MicroPC                     | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | ProBook 445 G7              | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Latitude 7420               | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| HP            | ZBook Studio G5             | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| Lenovo        | ThinkPad T580 20L90024PB    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| Dell          | XPS 15 9550                 | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/NixOS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| NixOS 24.05                      | 113       | 26.22%  |
| NixOS 24.11                      | 105       | 24.36%  |
| NixOS 23.11                      | 72        | 16.71%  |
| NixOS 23.05                      | 62        | 14.39%  |
| NixOS 22.11                      | 27        | 6.26%   |
| NixOS 22.05                      | 18        | 4.18%   |
| NixOS 25.05                      | 11        | 2.55%   |
| NixOS 21.11                      | 9         | 2.09%   |
| NixOS                            | 2         | 0.46%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.23%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.23%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.23%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.23%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.23%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.23%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.23%   |
| NixOS 20.09pre-git               | 1         | 0.23%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.23%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.23%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.23%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 394       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 6.6.32      | 8         | 1.77%   |
| 6.1.69      | 8         | 1.77%   |
| 6.6.45      | 7         | 1.55%   |
| 6.6.63      | 6         | 1.33%   |
| 6.6.48      | 6         | 1.33%   |
| 6.10.1-zen1 | 6         | 1.33%   |
| 6.6.8       | 5         | 1.11%   |
| 6.6.54      | 5         | 1.11%   |
| 6.6.49      | 5         | 1.11%   |
| 6.6.28      | 5         | 1.11%   |
| 6.12.1      | 5         | 1.11%   |
| 6.10.8      | 5         | 1.11%   |
| 6.10.6      | 5         | 1.11%   |
| 6.1.82      | 5         | 1.11%   |
| 6.1.55      | 5         | 1.11%   |
| 6.6.43      | 4         | 0.89%   |
| 6.6.39      | 4         | 0.89%   |
| 6.6.30      | 4         | 0.89%   |
| 6.5.5       | 4         | 0.89%   |
| 6.3.8       | 4         | 0.89%   |
| 6.1.68      | 4         | 0.89%   |
| 6.1.64      | 4         | 0.89%   |
| 6.1.53      | 4         | 0.89%   |
| 6.1.51      | 4         | 0.89%   |
| 6.9.8       | 3         | 0.67%   |
| 6.8.9       | 3         | 0.67%   |
| 6.8.1       | 3         | 0.67%   |
| 6.6.52      | 3         | 0.67%   |
| 6.6.51      | 3         | 0.67%   |
| 6.6.44      | 3         | 0.67%   |
| 6.6.42      | 3         | 0.67%   |
| 6.6.41      | 3         | 0.67%   |
| 6.6.37      | 3         | 0.67%   |
| 6.6.0       | 3         | 0.67%   |
| 6.3.3       | 3         | 0.67%   |
| 6.11.5      | 3         | 0.67%   |
| 6.10.3      | 3         | 0.67%   |
| 6.1.74      | 3         | 0.67%   |
| 6.1.72      | 3         | 0.67%   |
| 6.1.61      | 3         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6.32  | 8         | 1.77%   |
| 6.10.6  | 8         | 1.77%   |
| 6.1.69  | 8         | 1.77%   |
| 6.6.45  | 7         | 1.55%   |
| 6.10.8  | 7         | 1.55%   |
| 6.6.8   | 6         | 1.33%   |
| 6.6.63  | 6         | 1.33%   |
| 6.6.48  | 6         | 1.33%   |
| 6.10.1  | 6         | 1.33%   |
| 6.6.54  | 5         | 1.11%   |
| 6.6.49  | 5         | 1.11%   |
| 6.6.28  | 5         | 1.11%   |
| 6.12.1  | 5         | 1.11%   |
| 6.11.5  | 5         | 1.11%   |
| 6.10.7  | 5         | 1.11%   |
| 6.1.82  | 5         | 1.11%   |
| 6.1.55  | 5         | 1.11%   |
| 6.6.43  | 4         | 0.89%   |
| 6.6.39  | 4         | 0.89%   |
| 6.6.30  | 4         | 0.89%   |
| 6.5.5   | 4         | 0.89%   |
| 6.3.8   | 4         | 0.89%   |
| 6.12.0  | 4         | 0.89%   |
| 6.10.5  | 4         | 0.89%   |
| 6.10.3  | 4         | 0.89%   |
| 6.1.68  | 4         | 0.89%   |
| 6.1.64  | 4         | 0.89%   |
| 6.1.53  | 4         | 0.89%   |
| 6.1.51  | 4         | 0.89%   |
| 6.9.8   | 3         | 0.67%   |
| 6.8.9   | 3         | 0.67%   |
| 6.8.1   | 3         | 0.67%   |
| 6.7.5   | 3         | 0.67%   |
| 6.7.0   | 3         | 0.67%   |
| 6.6.67  | 3         | 0.67%   |
| 6.6.52  | 3         | 0.67%   |
| 6.6.51  | 3         | 0.67%   |
| 6.6.44  | 3         | 0.67%   |
| 6.6.42  | 3         | 0.67%   |
| 6.6.41  | 3         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 118       | 27.44%  |
| 6.1     | 95        | 22.09%  |
| 6.10    | 42        | 9.77%   |
| 5.15    | 31        | 7.21%   |
| 6.11    | 17        | 3.95%   |
| 6.9     | 14        | 3.26%   |
| 6.8     | 14        | 3.26%   |
| 6.7     | 14        | 3.26%   |
| 6.12    | 14        | 3.26%   |
| 6.5     | 11        | 2.56%   |
| 6.3     | 11        | 2.56%   |
| 6.4     | 7         | 1.63%   |
| 6.2     | 6         | 1.4%    |
| 6.0     | 6         | 1.4%    |
| 5.16    | 6         | 1.4%    |
| 5.8     | 3         | 0.7%    |
| 5.19    | 3         | 0.7%    |
| 5.13    | 3         | 0.7%    |
| 5.10    | 3         | 0.7%    |
| 5.7     | 2         | 0.47%   |
| 5.4     | 2         | 0.47%   |
| 5.18    | 2         | 0.47%   |
| 5.17    | 2         | 0.47%   |
| 4.19    | 2         | 0.47%   |
| 5.12    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 393       | 99.75%  |
| i686   | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| GNOME        | 96        | 23.13%  |
| Unknown      | 73        | 17.59%  |
| Hyprland     | 58        | 13.98%  |
| sway         | 38        | 9.16%   |
| KDE6         | 36        | 8.67%   |
| KDE5         | 29        | 6.99%   |
| KDE          | 29        | 6.99%   |
| none+i3      | 16        | 3.86%   |
| XFCE         | 6         | 1.45%   |
| none+awesome | 5         | 1.2%    |
| niri         | 5         | 1.2%    |
| COSMIC       | 5         | 1.2%    |
| X-Cinnamon   | 3         | 0.72%   |
| Pantheon     | 3         | 0.72%   |
| none+xmonad  | 3         | 0.72%   |
| Budgie       | 3         | 0.72%   |
| LXQt         | 2         | 0.48%   |
| Unity        | 1         | 0.24%   |
| qtile        | 1         | 0.24%   |
| none+qtile   | 1         | 0.24%   |
| none+bspwm   | 1         | 0.24%   |
| MATE         | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 220       | 52.76%  |
| Unknown | 115       | 27.58%  |
| X11     | 67        | 16.07%  |
| Tty     | 15        | 3.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| GDM                   | 119       | 29.24%  |
| Unknown               | 109       | 26.78%  |
| SDDM                  | 103       | 25.31%  |
| LightDM               | 47        | 11.55%  |
| GREETD                | 26        | 6.39%   |
| DISPLAY-MANAGER-START | 2         | 0.49%   |
| LEMURS                | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 269       | 67.25%  |
| Unknown | 40        | 10%     |
| en_GB   | 31        | 7.75%   |
| de_DE   | 14        | 3.5%    |
| fr_FR   | 6         | 1.5%    |
| en_CA   | 5         | 1.25%   |
| pt_PT   | 4         | 1%      |
| en_IN   | 4         | 1%      |
| en_DK   | 4         | 1%      |
| en_AU   | 4         | 1%      |
| ru_RU   | 3         | 0.75%   |
| zh_CN   | 2         | 0.5%    |
| pt_BR   | 2         | 0.5%    |
| pl_PL   | 2         | 0.5%    |
| C       | 2         | 0.5%    |
| ro_RO   | 1         | 0.25%   |
| lv_LV   | 1         | 0.25%   |
| lt_LT   | 1         | 0.25%   |
| it_IT   | 1         | 0.25%   |
| es_MX   | 1         | 0.25%   |
| es_ES   | 1         | 0.25%   |
| en_SG   | 1         | 0.25%   |
| en_IE   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 371       | 93.92%  |
| BIOS | 24        | 6.08%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 237       | 58.96%  |
| Btrfs    | 85        | 21.14%  |
| Tmpfs    | 32        | 7.96%   |
| Zfs      | 28        | 6.97%   |
| Xfs      | 11        | 2.74%   |
| Unknown  | 4         | 1%      |
| Bcachefs | 3         | 0.75%   |
| F2fs     | 2         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 376       | 94.95%  |
| MBR     | 15        | 3.79%   |
| Unknown | 5         | 1.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 345       | 86.25%  |
| Yes       | 55        | 13.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 306       | 77.08%  |
| Yes       | 91        | 22.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 137       | 34.77%  |
| Dell                   | 50        | 12.69%  |
| ASUSTek Computer       | 45        | 11.42%  |
| Hewlett-Packard        | 37        | 9.39%   |
| Apple                  | 24        | 6.09%   |
| Framework              | 20        | 5.08%   |
| Acer                   | 19        | 4.82%   |
| MSI                    | 11        | 2.79%   |
| Razer                  | 5         | 1.27%   |
| HUAWEI                 | 5         | 1.27%   |
| System76               | 4         | 1.02%   |
| GPD                    | 4         | 1.02%   |
| TUXEDO                 | 3         | 0.76%   |
| Timi                   | 3         | 0.76%   |
| Samsung Electronics    | 3         | 0.76%   |
| Google                 | 3         | 0.76%   |
| PC Specialist          | 2         | 0.51%   |
| MECHREVO               | 2         | 0.51%   |
| Toshiba                | 1         | 0.25%   |
| Sony                   | 1         | 0.25%   |
| OBSIDIAN-PC            | 1         | 0.25%   |
| Microtech              | 1         | 0.25%   |
| Medion                 | 1         | 0.25%   |
| MACHENIKE              | 1         | 0.25%   |
| Intel                  | 1         | 0.25%   |
| HONOR                  | 1         | 0.25%   |
| Gigabyte Technology    | 1         | 0.25%   |
| Fujitsu                | 1         | 0.25%   |
| Dynabook               | 1         | 0.25%   |
| Corsair                | 1         | 0.25%   |
| Chuwi                  | 1         | 0.25%   |
| Blackview              | 1         | 0.25%   |
| Avell High Performance | 1         | 0.25%   |
| Alienware              | 1         | 0.25%   |
| Unknown                | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Apple MacBookPro11,5                                 | 8         | 2.03%   |
| Framework Laptop 16 (AMD Ryzen 7040 Series)          | 6         | 1.52%   |
| Framework Laptop                                     | 6         | 1.52%   |
| Framework Laptop 13 (AMD Ryzen 7040Series)           | 4         | 1.02%   |
| Framework Laptop (12th Gen Intel Core)               | 4         | 1.02%   |
| Apple MacBookPro11,3                                 | 4         | 1.02%   |
| Lenovo ThinkPad T480 20L5CTO1WW                      | 3         | 0.76%   |
| ASUS Zenbook 15 UM3504DA_UM3504DA                    | 3         | 0.76%   |
| Razer Blade                                          | 2         | 0.51%   |
| MSI Modern 14 B5M                                    | 2         | 0.51%   |
| MSI Alpha 15 B5EEK                                   | 2         | 0.51%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW          | 2         | 0.51%   |
| Lenovo Legion R9000P ARX8 82WM                       | 2         | 0.51%   |
| Lenovo Legion 7 16IRX9 83FD                          | 2         | 0.51%   |
| Lenovo IdeaPad Pro 5 14IMH9 83D2                     | 2         | 0.51%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2                  | 2         | 0.51%   |
| Lenovo IdeaPad 3 14ITL05 81X7                        | 2         | 0.51%   |
| HP ZBook Firefly 14 inch G10 A Mobile Workstation PC | 2         | 0.51%   |
| HP EliteBook 8470p                                   | 2         | 0.51%   |
| Dell XPS 9315                                        | 2         | 0.51%   |
| Dell XPS 15 9530                                     | 2         | 0.51%   |
| Dell XPS 13 9310                                     | 2         | 0.51%   |
| Dell Latitude E6540                                  | 2         | 0.51%   |
| Dell Latitude 7420                                   | 2         | 0.51%   |
| Dell Inspiron 7577                                   | 2         | 0.51%   |
| Dell G5 5590                                         | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop K3605ZF_K3605ZF             | 2         | 0.51%   |
| ASUS Vivobook Go E1404FA_E1404FA                     | 2         | 0.51%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK                | 2         | 0.51%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM                | 2         | 0.51%   |
| ASUS ASUS Zenbook S 16 UM5606WA_UM5606WA             | 2         | 0.51%   |
| TUXEDO Pulse 15 Gen2                                 | 1         | 0.25%   |
| TUXEDO InfinityBook Pro Gen7 (MK2)                   | 1         | 0.25%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)                   | 1         | 0.25%   |
| Toshiba Satellite L50-B                              | 1         | 0.25%   |
| Timi Xiaomi Book Pro 16 2022                         | 1         | 0.25%   |
| Timi Redmi Book Pro 15 2022                          | 1         | 0.25%   |
| Timi Redmi Book Pro 14 2022                          | 1         | 0.25%   |
| System76 Serval WS                                   | 1         | 0.25%   |
| System76 Pangolin                                    | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 86        | 21.83%  |
| Framework Laptop    | 20        | 5.08%   |
| Lenovo IdeaPad      | 17        | 4.31%   |
| ASUS ROG            | 17        | 4.31%   |
| Apple MacBookPro11  | 15        | 3.81%   |
| Lenovo Legion       | 14        | 3.55%   |
| Dell XPS            | 14        | 3.55%   |
| Dell Latitude       | 12        | 3.05%   |
| HP EliteBook        | 10        | 2.54%   |
| Dell Inspiron       | 10        | 2.54%   |
| ASUS Zenbook        | 10        | 2.54%   |
| Acer Aspire         | 10        | 2.54%   |
| HP Pavilion         | 9         | 2.28%   |
| Lenovo ThinkBook    | 8         | 2.03%   |
| ASUS Vivobook       | 8         | 2.03%   |
| Lenovo Yoga         | 6         | 1.52%   |
| HP ZBook            | 6         | 1.52%   |
| Dell Precision      | 6         | 1.52%   |
| ASUS ASUS           | 6         | 1.52%   |
| Razer Blade         | 5         | 1.27%   |
| HP ProBook          | 5         | 1.27%   |
| Dell G5             | 3         | 0.76%   |
| Acer Swift          | 3         | 0.76%   |
| Acer Predator       | 3         | 0.76%   |
| TUXEDO InfinityBook | 2         | 0.51%   |
| Timi Redmi          | 2         | 0.51%   |
| MSI Prestige        | 2         | 0.51%   |
| MSI Modern          | 2         | 0.51%   |
| MSI Alpha           | 2         | 0.51%   |
| HP Laptop           | 2         | 0.51%   |
| Dell G3             | 2         | 0.51%   |
| Apple MacBookPro16  | 2         | 0.51%   |
| Acer Nitro          | 2         | 0.51%   |
| TUXEDO Pulse        | 1         | 0.25%   |
| Toshiba Satellite   | 1         | 0.25%   |
| Timi Xiaomi         | 1         | 0.25%   |
| System76 Serval     | 1         | 0.25%   |
| System76 Pangolin   | 1         | 0.25%   |
| System76 Oryx       | 1         | 0.25%   |
| System76 Darter     | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2023 | 65        | 16.5%   |
| 2021 | 59        | 14.97%  |
| 2022 | 43        | 10.91%  |
| 2020 | 36        | 9.14%   |
| 2018 | 31        | 7.87%   |
| 2024 | 29        | 7.36%   |
| 2019 | 26        | 6.6%    |
| 2016 | 20        | 5.08%   |
| 2017 | 16        | 4.06%   |
| 2013 | 15        | 3.81%   |
| 2015 | 14        | 3.55%   |
| 2014 | 13        | 3.3%    |
| 2012 | 9         | 2.28%   |
| 2011 | 9         | 2.28%   |
| 2008 | 4         | 1.02%   |
| 2010 | 2         | 0.51%   |
| 2007 | 2         | 0.51%   |
| 2009 | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 394       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 374       | 94.21%  |
| Enabled  | 23        | 5.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 386       | 97.97%  |
| Yes  | 8         | 2.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 101       | 25.57%  |
| 32.01-64.0  | 93        | 23.54%  |
| 16.01-24.0  | 92        | 23.29%  |
| 4.01-8.0    | 54        | 13.67%  |
| 24.01-32.0  | 21        | 5.32%   |
| 64.01-256.0 | 21        | 5.32%   |
| 3.01-4.0    | 11        | 2.78%   |
| 2.01-3.0    | 1         | 0.25%   |
| 0.51-1.0    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 144       | 33.33%  |
| 2.01-3.0   | 79        | 18.29%  |
| 3.01-4.0   | 76        | 17.59%  |
| 8.01-16.0  | 61        | 14.12%  |
| 1.01-2.0   | 34        | 7.87%   |
| 16.01-24.0 | 16        | 3.7%    |
| 0.51-1.0   | 9         | 2.08%   |
| 24.01-32.0 | 7         | 1.62%   |
| 0.01-0.5   | 4         | 0.93%   |
| 32.01-64.0 | 2         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 301       | 75.63%  |
| 2      | 89        | 22.36%  |
| 3      | 5         | 1.26%   |
| 6      | 1         | 0.25%   |
| 4      | 1         | 0.25%   |
| 0      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 369       | 93.65%  |
| Yes       | 25        | 6.35%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 263       | 66.08%  |
| No        | 135       | 33.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 380       | 96.45%  |
| No        | 14        | 3.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 366       | 92.42%  |
| No        | 30        | 7.58%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 76        | 19.19%  |
| Germany      | 50        | 12.63%  |
| Russia       | 21        | 5.3%    |
| France       | 19        | 4.8%    |
| UK           | 16        | 4.04%   |
| Italy        | 13        | 3.28%   |
| Czechia      | 11        | 2.78%   |
| Canada       | 11        | 2.78%   |
| Netherlands  | 10        | 2.53%   |
| Brazil       | 10        | 2.53%   |
| Portugal     | 9         | 2.27%   |
| Poland       | 9         | 2.27%   |
| Spain        | 8         | 2.02%   |
| India        | 8         | 2.02%   |
| Japan        | 7         | 1.77%   |
| Sweden       | 6         | 1.52%   |
| Vietnam      | 5         | 1.26%   |
| Ukraine      | 5         | 1.26%   |
| Romania      | 5         | 1.26%   |
| Switzerland  | 4         | 1.01%   |
| Norway       | 4         | 1.01%   |
| Finland      | 4         | 1.01%   |
| Austria      | 4         | 1.01%   |
| Thailand     | 3         | 0.76%   |
| Slovakia     | 3         | 0.76%   |
| Singapore    | 3         | 0.76%   |
| Mexico       | 3         | 0.76%   |
| Indonesia    | 3         | 0.76%   |
| Hong Kong    | 3         | 0.76%   |
| Georgia      | 3         | 0.76%   |
| Denmark      | 3         | 0.76%   |
| China        | 3         | 0.76%   |
| Belgium      | 3         | 0.76%   |
| Australia    | 3         | 0.76%   |
| Uruguay      | 2         | 0.51%   |
| Turkey       | 2         | 0.51%   |
| Tunisia      | 2         | 0.51%   |
| Saudi Arabia | 2         | 0.51%   |
| Qatar        | 2         | 0.51%   |
| Morocco      | 2         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 7         | 1.69%   |
| Berlin           | 6         | 1.45%   |
| Amsterdam        | 5         | 1.2%    |
| Warsaw           | 4         | 0.96%   |
| Vienna           | 4         | 0.96%   |
| Tokyo            | 4         | 0.96%   |
| Prague           | 4         | 0.96%   |
| Ho Chi Minh City | 4         | 0.96%   |
| Tbilisi          | 3         | 0.72%   |
| Singapore        | 3         | 0.72%   |
| Rochester        | 3         | 0.72%   |
| Richmond         | 3         | 0.72%   |
| Porto            | 3         | 0.72%   |
| Paris            | 3         | 0.72%   |
| Los Angeles      | 3         | 0.72%   |
| London           | 3         | 0.72%   |
| Hanover          | 3         | 0.72%   |
| Dresden          | 3         | 0.72%   |
| Craigsville      | 3         | 0.72%   |
| Cologne          | 3         | 0.72%   |
| Central          | 3         | 0.72%   |
| Bedford          | 3         | 0.72%   |
| Tehran           | 2         | 0.48%   |
| Stockholm        | 2         | 0.48%   |
| St Petersburg    | 2         | 0.48%   |
| Sorocaba         | 2         | 0.48%   |
| Sofia            | 2         | 0.48%   |
| Seattle          | 2         | 0.48%   |
| Saratov          | 2         | 0.48%   |
| San Diego        | 2         | 0.48%   |
| Salt Lake City   | 2         | 0.48%   |
| Pradamano        | 2         | 0.48%   |
| Phoenix          | 2         | 0.48%   |
| Perth            | 2         | 0.48%   |
| Ottawa           | 2         | 0.48%   |
| Oslo             | 2         | 0.48%   |
| Osaka            | 2         | 0.48%   |
| Norfolk          | 2         | 0.48%   |
| Montpellier      | 2         | 0.48%   |
| Montevideo       | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 122       | 156    | 24.95%  |
| SanDisk                        | 54        | 57     | 11.04%  |
| SK hynix                       | 35        | 43     | 7.16%   |
| Unknown                        | 34        | 35     | 6.95%   |
| Micron Technology              | 25        | 26     | 5.11%   |
| Apple                          | 20        | 23     | 4.09%   |
| Seagate                        | 19        | 21     | 3.89%   |
| WDC                            | 17        | 17     | 3.48%   |
| Kingston                       | 17        | 22     | 3.48%   |
| Toshiba                        | 16        | 17     | 3.27%   |
| Intel                          | 16        | 17     | 3.27%   |
| Crucial                        | 15        | 16     | 3.07%   |
| KIOXIA                         | 13        | 16     | 2.66%   |
| MAXIO Technology (Hangzhou)    | 7         | 8      | 1.43%   |
| Union Memory (Shenzhen)        | 6         | 8      | 1.23%   |
| Phison Electronics             | 6         | 8      | 1.23%   |
| Kingston Technology Company    | 6         | 7      | 1.23%   |
| A-DATA Technology              | 6         | 7      | 1.23%   |
| Micron/Crucial Technology      | 4         | 4      | 0.82%   |
| Yangtze Memory Technologies    | 3         | 4      | 0.61%   |
| Silicon Motion                 | 3         | 3      | 0.61%   |
| Shenzhen Longsys Electronics   | 3         | 4      | 0.61%   |
| Realtek                        | 3         | 3      | 0.61%   |
| LITEONIT                       | 3         | 3      | 0.61%   |
| Transcend                      | 2         | 2      | 0.41%   |
| PNY                            | 2         | 4      | 0.41%   |
| Lexar                          | 2         | 2      | 0.41%   |
| Hitachi                        | 2         | 3      | 0.41%   |
| HGST                           | 2         | 3      | 0.41%   |
| China                          | 2         | 2      | 0.41%   |
| Union Memory                   | 1         | 1      | 0.2%    |
| SPCC                           | 1         | 1      | 0.2%    |
| Solid State Storage Technology | 1         | 1      | 0.2%    |
| Solid State Storage            | 1         | 1      | 0.2%    |
| S3+                            | 1         | 1      | 0.2%    |
| Realtek Semiconductor          | 1         | 1      | 0.2%    |
| Ramaxel Technology             | 1         | 1      | 0.2%    |
| Phison                         | 1         | 1      | 0.2%    |
| Patriot                        | 1         | 1      | 0.2%    |
| Netac                          | 1         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 22        | 4.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 22        | 4.34%   |
| Unknown NVMe SSD Drive 1TB                           | 10        | 1.97%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 7         | 1.38%   |
| Apple SSD SM0512G 500GB                              | 7         | 1.38%   |
| Micron MTFDKBA1T0QFM-1BD1AABGB 1024GB                | 6         | 1.18%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 6         | 1.18%   |
| Intel SSDPEKNU512GZ 512GB                            | 6         | 1.18%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 5         | 0.99%   |
| Sandisk WD_BLACK SN770 1TB                           | 5         | 0.99%   |
| Samsung SSD 990 PRO 1TB                              | 5         | 0.99%   |
| Unknown NVMe SSD Drive 2TB                           | 4         | 0.79%   |
| Unknown MMC Card  32GB                               | 4         | 0.79%   |
| Samsung SSD 870 EVO 500GB                            | 4         | 0.79%   |
| Samsung SSD 850 EVO 250GB                            | 4         | 0.79%   |
| KIOXIA KBG50ZNV512G 512GB                            | 4         | 0.79%   |
| Unknown MMC Card  64GB                               | 3         | 0.59%   |
| SK hynix SKHynix_HFS001TEJ9X162N 1TB                 | 3         | 0.59%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1TB                 | 3         | 0.59%   |
| SK hynix HFM001TD3JX013N 1024GB                      | 3         | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB                       | 3         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 3         | 0.59%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB      | 3         | 0.59%   |
| Samsung SSD 980 1TB                                  | 3         | 0.59%   |
| Samsung SSD 850 EVO 500GB                            | 3         | 0.59%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                     | 3         | 0.59%   |
| Phison PS5013 E13 NVMe Controller 512GB              | 3         | 0.59%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 3         | 0.59%   |
| Micron 2450_MTFDKBA512TFK 512GB                      | 3         | 0.59%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 3         | 0.59%   |
| Intel SSDPEKNU010TZ 1TB                              | 3         | 0.59%   |
| Unknown USB DISK 3.2 1TB                             | 2         | 0.39%   |
| Unknown MMC Card  16GB                               | 2         | 0.39%   |
| Unknown MMC Card  128GB                              | 2         | 0.39%   |
| Union Memory (Shenzhen) UMIS RPJTJ512MGE1QDQ 512GB   | 2         | 0.39%   |
| Union Memory (Shenzhen) UMIS RPETJ1T24MKP2QDQ 1TB    | 2         | 0.39%   |
| SK hynix SKHynix_HFS001TEJ4X112N 1TB                 | 2         | 0.39%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                 | 2         | 0.39%   |
| SK hynix PC801 NVMe 512GB                            | 2         | 0.39%   |
| SK hynix PC801 NVMe 1TB                              | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 18        | 20     | 50%     |
| WDC      | 8         | 8      | 22.22%  |
| Toshiba  | 4         | 4      | 11.11%  |
| Hitachi  | 2         | 3      | 5.56%   |
| HGST     | 2         | 3      | 5.56%   |
| External | 1         | 1      | 2.78%   |
| Apple    | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 33     | 26.17%  |
| Apple               | 17        | 20     | 15.89%  |
| Crucial             | 11        | 12     | 10.28%  |
| SanDisk             | 10        | 10     | 9.35%   |
| Kingston            | 6         | 10     | 5.61%   |
| SK hynix            | 3         | 4      | 2.8%    |
| LITEONIT            | 3         | 3      | 2.8%    |
| Transcend           | 2         | 2      | 1.87%   |
| Toshiba             | 2         | 2      | 1.87%   |
| PNY                 | 2         | 4      | 1.87%   |
| Micron Technology   | 2         | 2      | 1.87%   |
| Lexar               | 2         | 2      | 1.87%   |
| China               | 2         | 2      | 1.87%   |
| WDC                 | 1         | 1      | 0.93%   |
| Unknown             | 1         | 1      | 0.93%   |
| SPCC                | 1         | 1      | 0.93%   |
| S3+                 | 1         | 1      | 0.93%   |
| Ramaxel Technology  | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| Neo Forza           | 1         | 1      | 0.93%   |
| INNOVATION IT       | 1         | 1      | 0.93%   |
| Indilinx            | 1         | 1      | 0.93%   |
| GOODRAM             | 1         | 1      | 0.93%   |
| Dogfish             | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |
| BIWIN               | 1         | 1      | 0.93%   |
| Apacer              | 1         | 1      | 0.93%   |
| A-DATA Technology   | 1         | 1      | 0.93%   |
| Unknown             | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 299       | 384    | 65.71%  |
| SSD     | 101       | 123    | 22.2%   |
| HDD     | 36        | 40     | 7.91%   |
| MMC     | 15        | 16     | 3.3%    |
| Unknown | 4         | 4      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 298       | 380    | 66.97%  |
| SATA | 113       | 149    | 25.39%  |
| SAS  | 19        | 22     | 4.27%   |
| MMC  | 15        | 16     | 3.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 86        | 104    | 61.87%  |
| 0.51-1.0   | 44        | 49     | 31.65%  |
| 1.01-2.0   | 8         | 9      | 5.76%   |
| 4.01-10.0  | 1         | 1      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 121       | 29.88%  |
| 251-500        | 66        | 16.3%   |
| 101-250        | 53        | 13.09%  |
| 501-1000       | 51        | 12.59%  |
| Unknown        | 44        | 10.86%  |
| 1001-2000      | 31        | 7.65%   |
| More than 3000 | 25        | 6.17%   |
| 2001-3000      | 12        | 2.96%   |
| 51-100         | 2         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 152       | 36.45%  |
| 101-250        | 58        | 13.91%  |
| Unknown        | 44        | 10.55%  |
| 21-50          | 39        | 9.35%   |
| 251-500        | 36        | 8.63%   |
| 51-100         | 35        | 8.39%   |
| 501-1000       | 20        | 4.8%    |
| 1001-2000      | 15        | 3.6%    |
| More than 3000 | 11        | 2.64%   |
| 2001-3000      | 7         | 1.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| A-DATA Technology IM2P33F3A NVMe 256GB                          | 2         | 3      | 8.7%    |
| WDC WD10JPVX-08JC3T5 1TB                                        | 1         | 1      | 4.35%   |
| WDC WD10 JPLX-00MBPT0 1TB                                       | 1         | 1      | 4.35%   |
| Union Memory UMIS RPITJ512PED2OWX 512GB                         | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 4.35%   |
| Toshiba MK2565GSXV 250GB                                        | 1         | 1      | 4.35%   |
| SK hynix SC210 2.5 7MM 256GB SSD                                | 1         | 1      | 4.35%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                            | 1         | 1      | 4.35%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                           | 1         | 2      | 4.35%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 1         | 1      | 4.35%   |
| Seagate ST9320325AS 320GB                                       | 1         | 2      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB                                 | 1         | 1      | 4.35%   |
| Seagate ST2000LM015-2E8174 2TB                                  | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 500GB                           | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 2TB                             | 1         | 1      | 4.35%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 1         | 1      | 4.35%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB                  | 1         | 1      | 4.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD                  | 1         | 1      | 4.35%   |
| Intel SSDPEKKF512G8L 512GB                                      | 1         | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB                                   | 1         | 1      | 4.35%   |
| Crucial CT120M500SSD3 120GB                                     | 1         | 1      | 4.35%   |
| Corsair Force GS 240GB SSD                                      | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| SK hynix                  | 4         | 5      | 17.39%  |
| Seagate                   | 3         | 4      | 13.04%  |
| Samsung Electronics       | 3         | 3      | 13.04%  |
| WDC                       | 2         | 2      | 8.7%    |
| Toshiba                   | 2         | 2      | 8.7%    |
| A-DATA Technology         | 2         | 3      | 8.7%    |
| Union Memory              | 1         | 1      | 4.35%   |
| Micron/Crucial Technology | 1         | 1      | 4.35%   |
| Micron Technology         | 1         | 1      | 4.35%   |
| Intel                     | 1         | 1      | 4.35%   |
| Hitachi                   | 1         | 1      | 4.35%   |
| Crucial                   | 1         | 1      | 4.35%   |
| Corsair                   | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 37.5%   |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 2         | 2      | 25%     |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 8         | 9      | 34.78%  |
| HDD  | 8         | 9      | 34.78%  |
| SSD  | 7         | 8      | 30.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 362       | 484    | 83.03%  |
| Detected | 51        | 56     | 11.7%   |
| Malfunc  | 22        | 26     | 5.05%   |
| Failed   | 1         | 1      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 157       | 31.59%  |
| Samsung Electronics                     | 108       | 21.73%  |
| SanDisk                                 | 64        | 12.88%  |
| SK hynix                                | 32        | 6.44%   |
| Micron Technology                       | 24        | 4.83%   |
| AMD                                     | 18        | 3.62%   |
| Kingston Technology Company             | 17        | 3.42%   |
| KIOXIA                                  | 12        | 2.41%   |
| Toshiba America Info Systems            | 11        | 2.21%   |
| Phison Electronics                      | 7         | 1.41%   |
| Micron/Crucial Technology               | 7         | 1.41%   |
| MAXIO Technology (Hangzhou)             | 7         | 1.41%   |
| ADATA Technology                        | 6         | 1.21%   |
| Shenzhen Unionmemory Information System | 4         | 0.8%    |
| Yangtze Memory Technologies             | 3         | 0.6%    |
| Union Memory (Shenzhen)                 | 3         | 0.6%    |
| Silicon Motion                          | 3         | 0.6%    |
| Shenzhen Longsys Electronics            | 3         | 0.6%    |
| Solid State Storage Technology          | 2         | 0.4%    |
| Apple                                   | 2         | 0.4%    |
| Solidigm                                | 1         | 0.2%    |
| Realtek Semiconductor                   | 1         | 0.2%    |
| Netac Technology                        | 1         | 0.2%    |
| Marvell Technology Group                | 1         | 0.2%    |
| Lite-On Technology                      | 1         | 0.2%    |
| Biwin Storage Technology                | 1         | 0.2%    |
| Unknown                                 | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 31        | 6.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 27        | 5.29%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 21        | 4.12%   |
| Intel Volume Management Device NVMe RAID Controller                           | 18        | 3.53%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 18        | 3.53%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 17        | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 17        | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 15        | 2.94%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 12        | 2.35%   |
| Intel SSD 670p Series [Keystone Harbor]                                       | 12        | 2.35%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                            | 11        | 2.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 11        | 2.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 11        | 2.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 11        | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 10        | 1.96%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 9         | 1.76%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 9         | 1.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 9         | 1.76%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 8         | 1.57%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 8         | 1.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 7         | 1.37%   |
| Sandisk WD Black SN850X NVMe SSD                                              | 7         | 1.37%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                 | 6         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation         | 6         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 1.18%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                             | 5         | 0.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 5         | 0.98%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                            | 5         | 0.98%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 5         | 0.98%   |
| KIOXIA NVMe SSD Controller XG8                                                | 5         | 0.98%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 5         | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                           | 5         | 0.98%   |
| Intel Tiger Lake SATA AHCI Controller                                         | 5         | 0.98%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 4         | 0.78%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 4         | 0.78%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                | 4         | 0.78%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                 | 4         | 0.78%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 4         | 0.78%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                      | 4         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 4         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 297       | 62.13%  |
| SATA | 145       | 30.33%  |
| RAID | 34        | 7.11%   |
| IDE  | 2         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 269       | 68.27%  |
| AMD    | 125       | 31.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 2.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 2.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.78%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 7         | 1.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.52%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 1.52%   |
| Intel 12th Gen Core i7-12700H                 | 6         | 1.52%   |
| Intel 12th Gen Core i7-1260P                  | 6         | 1.52%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 1.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.52%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 1.52%   |
| Intel Core Ultra 9 185H                       | 5         | 1.27%   |
| Intel Core Ultra 7 155H                       | 5         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.27%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 1.27%   |
| AMD Ryzen 7 PRO 7840U w/ Radeon 780M Graphics | 5         | 1.27%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics    | 5         | 1.27%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 1.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.02%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.02%   |
| Intel 13th Gen Core i7-13700H                 | 4         | 1.02%   |
| AMD Ryzen AI 9 HX 370 w/ Radeon 890M          | 4         | 1.02%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 1.02%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 4         | 1.02%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 1.02%   |
| AMD Ryzen 7 5800HS with Radeon Graphics       | 4         | 1.02%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.02%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 1.02%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.76%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.76%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.76%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 3         | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 97        | 24.62%  |
| Other              | 93        | 23.6%   |
| Intel Core i5      | 48        | 12.18%  |
| AMD Ryzen 7        | 46        | 11.68%  |
| AMD Ryzen 5        | 24        | 6.09%   |
| AMD Ryzen 7 PRO    | 22        | 5.58%   |
| AMD Ryzen 9        | 20        | 5.08%   |
| Intel Core         | 13        | 3.3%    |
| Intel Celeron      | 6         | 1.52%   |
| AMD Ryzen 5 PRO    | 5         | 1.27%   |
| Intel Core i9      | 4         | 1.02%   |
| Intel Pentium      | 3         | 0.76%   |
| Intel Core i3      | 3         | 0.76%   |
| Intel Xeon         | 2         | 0.51%   |
| Intel Core 2 Duo   | 2         | 0.51%   |
| Intel Atom         | 2         | 0.51%   |
| Intel Pentium Gold | 1         | 0.25%   |
| Intel Core m3      | 1         | 0.25%   |
| AMD Ryzen 3        | 1         | 0.25%   |
| AMD A12            | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 122       | 30.96%  |
| 8      | 96        | 24.37%  |
| 2      | 66        | 16.75%  |
| 6      | 35        | 8.88%   |
| 12     | 22        | 5.58%   |
| 14     | 17        | 4.31%   |
| 10     | 16        | 4.06%   |
| 16     | 13        | 3.3%    |
| 24     | 6         | 1.52%   |
| 1      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 394       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 375       | 95.18%  |
| 1      | 19        | 4.82%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 393       | 99.49%  |
| 32-bit         | 1         | 0.25%   |
| Unknown        | 1         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 226       | 55.8%   |
| 0x0a50000c | 18        | 4.44%   |
| 0x08600106 | 12        | 2.96%   |
| 0x806ea    | 8         | 1.98%   |
| 0x40661    | 8         | 1.98%   |
| 0x906ea    | 7         | 1.73%   |
| 0x806c1    | 7         | 1.73%   |
| 0x306d4    | 7         | 1.73%   |
| 0x0a50000d | 6         | 1.48%   |
| 0x906a3    | 5         | 1.23%   |
| 0x806e9    | 5         | 1.23%   |
| 0x306c3    | 5         | 1.23%   |
| 0x0a704104 | 5         | 1.23%   |
| 0x0a704103 | 5         | 1.23%   |
| 0x08608103 | 5         | 1.23%   |
| 0x906e9    | 4         | 0.99%   |
| 0x806ec    | 4         | 0.99%   |
| 0x806eb    | 4         | 0.99%   |
| 0x406e3    | 4         | 0.99%   |
| 0x40651    | 4         | 0.99%   |
| 0x306a9    | 4         | 0.99%   |
| 0x0a404102 | 4         | 0.99%   |
| 0x08108109 | 4         | 0.99%   |
| 0x506e3    | 3         | 0.74%   |
| 0x0a404101 | 3         | 0.74%   |
| 0xb06a3    | 2         | 0.49%   |
| 0xb06a2    | 2         | 0.49%   |
| 0xb0671    | 2         | 0.49%   |
| 0xa0660    | 2         | 0.49%   |
| 0x906ed    | 2         | 0.49%   |
| 0x906a4    | 2         | 0.49%   |
| 0x706a8    | 2         | 0.49%   |
| 0x706a1    | 2         | 0.49%   |
| 0x0a704107 | 2         | 0.49%   |
| 0x0a404105 | 2         | 0.49%   |
| 0x08a00008 | 2         | 0.49%   |
| 0x08600104 | 2         | 0.49%   |
| 0x08108102 | 2         | 0.49%   |
| 0xa0652    | 1         | 0.25%   |
| 0x806d1    | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 75        | 19.04%  |
| KabyLake          | 69        | 17.51%  |
| Alderlake Hybrid  | 49        | 12.44%  |
| Zen 3             | 33        | 8.38%   |
| Haswell           | 28        | 7.11%   |
| TigerLake         | 26        | 6.6%    |
| Zen 2             | 15        | 3.81%   |
| Skylake           | 14        | 3.55%   |
| Broadwell         | 13        | 3.3%    |
| Meteorlake Hybrid | 12        | 3.05%   |
| IvyBridge         | 11        | 2.79%   |
| Icelake           | 10        | 2.54%   |
| Zen+              | 8         | 2.03%   |
| SandyBridge       | 7         | 1.78%   |
| CometLake         | 7         | 1.78%   |
| Goldmont plus     | 4         | 1.02%   |
| Gracemont         | 2         | 0.51%   |
| Goldmont          | 2         | 0.51%   |
| Bonnell           | 2         | 0.51%   |
| Zen               | 1         | 0.25%   |
| Westmere          | 1         | 0.25%   |
| Silvermont        | 1         | 0.25%   |
| Penryn            | 1         | 0.25%   |
| Lunarlake Hybrid  | 1         | 0.25%   |
| Excavator         | 1         | 0.25%   |
| Core              | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 251       | 48.64%  |
| AMD    | 142       | 27.52%  |
| Nvidia | 123       | 23.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 27        | 5.07%   |
| AMD Phoenix1                                                                          | 23        | 4.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 22        | 4.13%   |
| Intel UHD Graphics 620                                                                | 19        | 3.56%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 18        | 3.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 17        | 3.19%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 17        | 3.19%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 15        | 2.81%   |
| AMD Rembrandt [Radeon 680M]                                                           | 14        | 2.63%   |
| AMD Lucienne                                                                          | 14        | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 2.06%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                       | 10        | 1.88%   |
| Intel HD Graphics 5500                                                                | 10        | 1.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 10        | 1.88%   |
| Intel Raptor Lake-S UHD Graphics                                                      | 9         | 1.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 8         | 1.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 8         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 8         | 1.5%    |
| Intel Meteor Lake-P [Intel Arc Graphics]                                              | 8         | 1.5%    |
| Intel HD Graphics 620                                                                 | 8         | 1.5%    |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 8         | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 1.5%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 7         | 1.31%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 7         | 1.31%   |
| Intel HD Graphics 630                                                                 | 7         | 1.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 7         | 1.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 7         | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 6         | 1.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 6         | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 6         | 1.13%   |
| AMD Strix [Radeon 880M / 890M]                                                        | 6         | 1.13%   |
| AMD Barcelo                                                                           | 6         | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 5         | 0.94%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 5         | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 5         | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 5         | 0.94%   |
| AMD Phoenix3                                                                          | 5         | 0.94%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]                 | 5         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 154       | 38.99%  |
| 1 x AMD        | 91        | 23.04%  |
| Intel + Nvidia | 85        | 21.52%  |
| AMD + Nvidia   | 26        | 6.58%   |
| 2 x AMD        | 15        | 3.8%    |
| 1 x Nvidia     | 12        | 3.04%   |
| Intel + AMD    | 10        | 2.53%   |
| 2 x Intel      | 2         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 301       | 75.44%  |
| Proprietary | 88        | 22.06%  |
| Unknown     | 10        | 2.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 247       | 61.9%   |
| 0.01-0.5   | 64        | 16.04%  |
| 1.01-2.0   | 34        | 8.52%   |
| 3.01-4.0   | 25        | 6.27%   |
| 0.51-1.0   | 15        | 3.76%   |
| 7.01-8.0   | 10        | 2.51%   |
| 8.01-16.0  | 3         | 0.75%   |
| 5.01-6.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 91        | 19.04%  |
| AU Optronics         | 85        | 17.78%  |
| Samsung Electronics  | 51        | 10.67%  |
| LG Display           | 46        | 9.62%   |
| Chimei Innolux       | 43        | 9%      |
| Apple                | 24        | 5.02%   |
| Dell                 | 19        | 3.97%   |
| Sharp                | 18        | 3.77%   |
| Goldstar             | 15        | 3.14%   |
| CSO                  | 13        | 2.72%   |
| PANDA                | 9         | 1.88%   |
| Lenovo               | 7         | 1.46%   |
| Hewlett-Packard      | 7         | 1.46%   |
| Acer                 | 7         | 1.46%   |
| InfoVision           | 6         | 1.26%   |
| TMX                  | 5         | 1.05%   |
| ASUSTek Computer     | 5         | 1.05%   |
| Philips              | 4         | 0.84%   |
| Ancor Communications | 3         | 0.63%   |
| Toshiba              | 2         | 0.42%   |
| Panasonic            | 2         | 0.42%   |
| HannStar             | 2         | 0.42%   |
| VXN                  | 1         | 0.21%   |
| VLK                  | 1         | 0.21%   |
| ViewSonic            | 1         | 0.21%   |
| Nreal Air            | 1         | 0.21%   |
| Mi                   | 1         | 0.21%   |
| KDB                  | 1         | 0.21%   |
| JDI                  | 1         | 0.21%   |
| Iiyama               | 1         | 0.21%   |
| Fujitsu Siemens      | 1         | 0.21%   |
| Eizo                 | 1         | 0.21%   |
| DENON                | 1         | 0.21%   |
| BenQ                 | 1         | 0.21%   |
| AOC                  | 1         | 0.21%   |
| AML                  | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                  | 9         | 1.88%   |
| BOE LCD Monitor BOE0BC9 2560x1600 345x215mm 16.0-inch                  | 6         | 1.25%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                  | 6         | 1.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 5         | 1.04%   |
| Chimei Innolux LCD Monitor CMN1614 1920x1200 344x215mm 16.0-inch       | 4         | 0.84%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                  | 4         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch  | 3         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 3         | 0.63%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 3         | 0.63%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 3         | 0.63%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                      | 3         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 3         | 0.63%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch         | 3         | 0.63%   |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                  | 3         | 0.63%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                  | 3         | 0.63%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                  | 2         | 0.42%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                  | 2         | 0.42%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 2         | 0.42%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC419F 2880x1800 302x189mm 14.0-inch  | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC419D 2880x1800 302x189mm 14.0-inch  | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch  | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch  | 2         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch  | 2         | 0.42%   |
| Samsung Electronics ATNA60CL10-0 SDC41AF 2880x1800 344x215mm 16.0-inch | 2         | 0.42%   |
| Samsung Electronics ATNA40CU05-0 SDC419C 2880x1800 302x189mm 14.0-inch | 2         | 0.42%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch            | 2         | 0.42%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 2         | 0.42%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 0.42%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch           | 2         | 0.42%   |
| Lenovo LEN T32p-20 LEN61F2 3840x2160 697x392mm 31.5-inch               | 2         | 0.42%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 2         | 0.42%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2         | 0.42%   |
| CSO LCD Monitor CSO1628 2560x1600 344x215mm 16.0-inch                  | 2         | 0.42%   |
| CSO LCD Monitor CSO1626 3200x2000 344x215mm 16.0-inch                  | 2         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 191       | 41.61%  |
| 2880x1800          | 42        | 9.15%   |
| 1920x1200 (WUXGA)  | 37        | 8.06%   |
| 2560x1600          | 35        | 7.63%   |
| 3840x2160 (4K)     | 33        | 7.19%   |
| 1366x768 (WXGA)    | 30        | 6.54%   |
| 2560x1440 (QHD)    | 29        | 6.32%   |
| 2256x1504          | 14        | 3.05%   |
| 3840x2400          | 5         | 1.09%   |
| 3440x1440          | 5         | 1.09%   |
| 1600x900 (HD+)     | 5         | 1.09%   |
| 3200x2000          | 4         | 0.87%   |
| 2240x1400          | 4         | 0.87%   |
| 2560x1080          | 3         | 0.65%   |
| 1680x1050 (WSXGA+) | 3         | 0.65%   |
| 2880x1620          | 2         | 0.44%   |
| 1440x900 (WXGA+)   | 2         | 0.44%   |
| 1280x800 (WXGA)    | 2         | 0.44%   |
| 1280x1024 (SXGA)   | 2         | 0.44%   |
| 1024x600           | 2         | 0.44%   |
| Unknown            | 2         | 0.44%   |
| 3840x1200          | 1         | 0.22%   |
| 3840x1080          | 1         | 0.22%   |
| 3456x2160          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 3072x1920          | 1         | 0.22%   |
| 2160x1440          | 1         | 0.22%   |
| 1920x1280          | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 131       | 27.64%  |
| 14      | 101       | 21.31%  |
| 13      | 75        | 15.82%  |
| 16      | 43        | 9.07%   |
| 27      | 32        | 6.75%   |
| 24      | 17        | 3.59%   |
| 17      | 13        | 2.74%   |
| 12      | 13        | 2.74%   |
| 31      | 10        | 2.11%   |
| 34      | 7         | 1.48%   |
| 23      | 6         | 1.27%   |
| 21      | 4         | 0.84%   |
| 86      | 3         | 0.63%   |
| 22      | 3         | 0.63%   |
| 25      | 2         | 0.42%   |
| 10      | 2         | 0.42%   |
| Unknown | 2         | 0.42%   |
| 60      | 1         | 0.21%   |
| 48      | 1         | 0.21%   |
| 46      | 1         | 0.21%   |
| 43      | 1         | 0.21%   |
| 39      | 1         | 0.21%   |
| 36      | 1         | 0.21%   |
| 35      | 1         | 0.21%   |
| 26      | 1         | 0.21%   |
| 20      | 1         | 0.21%   |
| 18      | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 287       | 61.06%  |
| 201-300     | 74        | 15.74%  |
| 501-600     | 53        | 11.28%  |
| 351-400     | 15        | 3.19%   |
| 601-700     | 14        | 2.98%   |
| 401-500     | 8         | 1.7%    |
| 701-800     | 7         | 1.49%   |
| 1001-1500   | 6         | 1.28%   |
| 801-900     | 2         | 0.43%   |
| Unknown     | 2         | 0.43%   |
| 1501-2000   | 1         | 0.21%   |
| 901-1000    | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 257       | 60.33%  |
| 16/10   | 136       | 31.92%  |
| 3/2     | 16        | 3.76%   |
| 21/9    | 9         | 2.11%   |
| 5/4     | 2         | 0.47%   |
| 0.56    | 2         | 0.47%   |
| Unknown | 2         | 0.47%   |
| 32/9    | 1         | 0.23%   |
| 3.20    | 1         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 143       | 30.17%  |
| 101-110        | 133       | 28.06%  |
| 111-120        | 40        | 8.44%   |
| 71-80          | 33        | 6.96%   |
| 301-350        | 33        | 6.96%   |
| 201-250        | 23        | 4.85%   |
| 351-500        | 18        | 3.8%    |
| 61-70          | 13        | 2.74%   |
| 121-130        | 11        | 2.32%   |
| 251-300        | 7         | 1.48%   |
| 501-1000       | 5         | 1.05%   |
| More than 1000 | 4         | 0.84%   |
| 151-200        | 3         | 0.63%   |
| 141-150        | 3         | 0.63%   |
| 41-50          | 2         | 0.42%   |
| Unknown        | 2         | 0.42%   |
| 131-140        | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 188       | 40.78%  |
| 161-240       | 128       | 27.77%  |
| 101-120       | 50        | 10.85%  |
| 51-100        | 48        | 10.41%  |
| More than 240 | 40        | 8.68%   |
| 1-50          | 5         | 1.08%   |
| Unknown       | 2         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 304       | 74.51%  |
| 2     | 81        | 19.85%  |
| 0     | 14        | 3.43%   |
| 3     | 9         | 2.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 244       | 41.5%   |
| Realtek Semiconductor             | 174       | 29.59%  |
| MediaTek                          | 60        | 10.2%   |
| Qualcomm Atheros                  | 25        | 4.25%   |
| Broadcom                          | 23        | 3.91%   |
| Qualcomm                          | 13        | 2.21%   |
| ASIX Electronics                  | 9         | 1.53%   |
| Lenovo                            | 7         | 1.19%   |
| Broadcom Limited                  | 4         | 0.68%   |
| Xiaomi                            | 3         | 0.51%   |
| Apple                             | 3         | 0.51%   |
| TP-Link                           | 2         | 0.34%   |
| Marvell Technology Group          | 2         | 0.34%   |
| Framework Computer                | 2         | 0.34%   |
| Ericsson Business Mobile Networks | 2         | 0.34%   |
| DisplayLink                       | 2         | 0.34%   |
| Quectel Wireless Solutions        | 1         | 0.17%   |
| Qualcomm Technologies             | 1         | 0.17%   |
| Qualcomm Atheros Communications   | 1         | 0.17%   |
| QinHeng Electronics               | 1         | 0.17%   |
| Microsoft                         | 1         | 0.17%   |
| ICS Advent                        | 1         | 0.17%   |
| Fibocom                           | 1         | 0.17%   |
| Espressif                         | 1         | 0.17%   |
| Edimax Technology                 | 1         | 0.17%   |
| Dell                              | 1         | 0.17%   |
| D-Link                            | 1         | 0.17%   |
| Comneon                           | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 105       | 15.26%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 5.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 27        | 3.92%   |
| Intel Wi-Fi 6 AX200                                                    | 26        | 3.78%   |
| Intel Wireless 8265 / 8275                                             | 23        | 3.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 20        | 2.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 19        | 2.76%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 17        | 2.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 15        | 2.18%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 1.89%   |
| Intel Wireless 7265                                                    | 12        | 1.74%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 11        | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 11        | 1.6%    |
| Intel Meteor Lake PCH CNVi WiFi                                        | 10        | 1.45%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 10        | 1.45%   |
| Intel Wireless 8260                                                    | 9         | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 9         | 1.31%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 1.31%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 8         | 1.16%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 8         | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 8         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 1.16%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 7         | 1.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 1.02%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 7         | 1.02%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 7         | 1.02%   |
| Intel Wireless 3160                                                    | 7         | 1.02%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 7         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 0.87%   |
| Intel Wireless 7260                                                    | 6         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.87%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 5         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 239       | 61.44%  |
| MediaTek                        | 53        | 13.62%  |
| Realtek Semiconductor           | 29        | 7.46%   |
| Qualcomm Atheros                | 22        | 5.66%   |
| Broadcom                        | 21        | 5.4%    |
| Qualcomm                        | 12        | 3.08%   |
| Broadcom Limited                | 4         | 1.03%   |
| TP-Link                         | 1         | 0.26%   |
| Quectel Wireless Solutions      | 1         | 0.26%   |
| Qualcomm Technologies           | 1         | 0.26%   |
| Qualcomm Atheros Communications | 1         | 0.26%   |
| Microsoft                       | 1         | 0.26%   |
| Fibocom                         | 1         | 0.26%   |
| Edimax Technology               | 1         | 0.26%   |
| Dell                            | 1         | 0.26%   |
| D-Link                          | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                             | 26        | 6.68%   |
| Intel Wireless 8265 / 8275                                      | 23        | 5.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter   | 20        | 5.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 20        | 5.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                                | 19        | 4.88%   |
| Intel Raptor Lake PCH CNVi WiFi                                 | 17        | 4.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter   | 15        | 3.86%   |
| Intel Wi-Fi 6 AX201                                             | 13        | 3.34%   |
| Intel Wireless 7265                                             | 12        | 3.08%   |
| Qualcomm QCNFA765 Wireless Network Adapter                      | 11        | 2.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 11        | 2.83%   |
| Intel Meteor Lake PCH CNVi WiFi                                 | 10        | 2.57%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                     | 10        | 2.57%   |
| Intel Wireless 8260                                             | 9         | 2.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 9         | 2.31%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller     | 8         | 2.06%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 8         | 2.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 8         | 2.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter        | 7         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 7         | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 7         | 1.8%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter               | 7         | 1.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 7         | 1.8%    |
| Intel Wireless 3160                                             | 7         | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 7         | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 6         | 1.54%   |
| Intel Wireless 7260                                             | 6         | 1.54%   |
| Intel Raptor Lake-S PCH CNVi WiFi                               | 6         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 5         | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 5         | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 4         | 1.03%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 4         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 3         | 0.77%   |
| MediaTek WLAN controller                                        | 3         | 0.77%   |
| Intel Wireless 3165                                             | 3         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 3         | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 2         | 0.51%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2 | 2         | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 2         | 0.51%   |
| Intel Centrino Advanced-N 6235                                  | 2         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 159       | 56.79%  |
| Intel                    | 74        | 26.43%  |
| ASIX Electronics         | 9         | 3.21%   |
| MediaTek                 | 7         | 2.5%    |
| Lenovo                   | 7         | 2.5%    |
| Qualcomm Atheros         | 5         | 1.79%   |
| Broadcom                 | 5         | 1.79%   |
| Xiaomi                   | 3         | 1.07%   |
| Apple                    | 3         | 1.07%   |
| Marvell Technology Group | 2         | 0.71%   |
| DisplayLink              | 2         | 0.71%   |
| TP-Link                  | 1         | 0.36%   |
| Qualcomm                 | 1         | 0.36%   |
| ICS Advent               | 1         | 0.36%   |
| ASUSTek Computer         | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 105       | 35.96%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 41        | 14.04%  |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 3.08%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 2.74%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 2.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 2.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 2.05%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 2.05%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.71%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.37%   |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 1.03%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 3         | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 1.03%   |
| Lenovo USB-C Dock Ethernet                                             | 3         | 1.03%   |
| Intel Ethernet Controller I219-V                                       | 3         | 1.03%   |
| Intel Ethernet Controller I219-LM                                      | 3         | 1.03%   |
| Intel Ethernet Connection (23) I219-V                                  | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.03%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 1.03%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 2         | 0.68%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 2         | 0.68%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.68%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                       | 2         | 0.68%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.68%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.68%   |
| Intel Ethernet Connection (13) I219-LM                                 | 2         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.68%   |
| Apple iBridge                                                          | 2         | 0.68%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.34%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.34%   |
| Qualcomm Airtel 4G                                                     | 1         | 0.34%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 380       | 58.46%  |
| Ethernet | 263       | 40.46%  |
| Modem    | 7         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 341       | 80.24%  |
| Ethernet | 84        | 19.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 199       | 50.51%  |
| 1     | 186       | 47.21%  |
| 3     | 8         | 2.03%   |
| 0     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 277       | 68.91%  |
| Yes  | 125       | 31.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 221       | 60.38%  |
| Foxconn / Hon Hai               | 23        | 6.28%   |
| Apple                           | 22        | 6.01%   |
| Realtek Semiconductor           | 21        | 5.74%   |
| MediaTek                        | 20        | 5.46%   |
| IMC Networks                    | 20        | 5.46%   |
| Qualcomm Atheros Communications | 10        | 2.73%   |
| USI                             | 8         | 2.19%   |
| Lite-On Technology              | 8         | 2.19%   |
| Broadcom                        | 5         | 1.37%   |
| Realtek                         | 2         | 0.55%   |
| Opticis                         | 2         | 0.55%   |
| Integrated System Solution      | 1         | 0.27%   |
| Chicony Electronics             | 1         | 0.27%   |
| ASUSTek Computer                | 1         | 0.27%   |
| Alps Electric                   | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 53        | 14.48%  |
| Intel AX211 Bluetooth                            | 46        | 12.57%  |
| Intel AX201 Bluetooth                            | 33        | 9.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 26        | 7.1%    |
| Intel AX200 Bluetooth                            | 26        | 7.1%    |
| MediaTek Wireless_Device                         | 20        | 5.46%   |
| Intel AX210 Bluetooth                            | 20        | 5.46%   |
| Realtek Bluetooth Radio                          | 18        | 4.92%   |
| IMC Networks Wireless_Device                     | 18        | 4.92%   |
| Apple Bluetooth Host Controller                  | 18        | 4.92%   |
| Foxconn / Hon Hai Wireless_Device                | 13        | 3.55%   |
| USI Bluetooth Device                             | 8         | 2.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 7         | 1.91%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter     | 5         | 1.37%   |
| Qualcomm Atheros  Bluetooth Device               | 4         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 4         | 1.09%   |
| Lite-On Wireless_Device                          | 4         | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device               | 4         | 1.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 3         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 3         | 0.82%   |
| Intel Bluetooth Device                           | 3         | 0.82%   |
| Realtek Bluetooth Radio                          | 2         | 0.55%   |
| Opticis Bluetooth Radio                          | 2         | 0.55%   |
| Intel Wireless-AC 3168 Bluetooth                 | 2         | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 2         | 0.55%   |
| Broadcom HP Portable SoftSailing                 | 2         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 0.55%   |
| Apple Bluetooth USB Host Controller              | 2         | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter          | 1         | 0.27%   |
| Realtek RTL8821A Bluetooth                       | 1         | 0.27%   |
| Realtek 802.11ac WLAN Adapter                    | 1         | 0.27%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 0.27%   |
| Lite-On Bluetooth Device                         | 1         | 0.27%   |
| Integrated System Solution Bluetooth Device      | 1         | 0.27%   |
| IMC Networks Bluetooth Device                    | 1         | 0.27%   |
| IMC Networks BCM20702A0                          | 1         | 0.27%   |
| Foxconn / Hon Hai Bluetooth Radio                | 1         | 0.27%   |
| Chicony Bluetooth (RTL8723BE)                    | 1         | 0.27%   |
| Broadcom BCM20702A0                              | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 269       | 50.85%  |
| AMD                    | 135       | 25.52%  |
| Nvidia                 | 71        | 13.42%  |
| Lenovo                 | 10        | 1.89%   |
| C-Media Electronics    | 7         | 1.32%   |
| Realtek Semiconductor  | 4         | 0.76%   |
| Logitech               | 3         | 0.57%   |
| Kingston Technology    | 3         | 0.57%   |
| Synaptics              | 2         | 0.38%   |
| Razer USA              | 2         | 0.38%   |
| Hewlett-Packard        | 2         | 0.38%   |
| DSEA A/S               | 2         | 0.38%   |
| Apple                  | 2         | 0.38%   |
| Trust                  | 1         | 0.19%   |
| Texas Instruments      | 1         | 0.19%   |
| Satechi                | 1         | 0.19%   |
| Native Instruments     | 1         | 0.19%   |
| KTMicro                | 1         | 0.19%   |
| JMTek                  | 1         | 0.19%   |
| Jieli Technology       | 1         | 0.19%   |
| Goldvish               | 1         | 0.19%   |
| GN Netcom              | 1         | 0.19%   |
| Generalplus Technology | 1         | 0.19%   |
| Focusrite-Novation     | 1         | 0.19%   |
| ESS Technology         | 1         | 0.19%   |
| EDFIER                 | 1         | 0.19%   |
| Creative Technology    | 1         | 0.19%   |
| Corsair                | 1         | 0.19%   |
| AudioQuest             | 1         | 0.19%   |
| (LCS) USB Audio Device | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 122       | 17.68%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 59        | 8.55%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 51        | 7.39%   |
| Intel Sunrise Point-LP HD Audio                                            | 36        | 5.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 26        | 3.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 24        | 3.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 3.04%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 19        | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 2.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 1.88%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 1.88%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 12        | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 1.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.3%    |
| Intel Raptor Lake High Definition Audio Controller                         | 9         | 1.3%    |
| Nvidia AD107 High Definition Audio Controller                              | 8         | 1.16%   |
| Nvidia AD106M High Definition Audio Controller                             | 8         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8         | 1.16%   |
| Nvidia GA107 High Definition Audio Controller                              | 7         | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.01%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.01%   |
| Intel CM238 HD Audio Controller                                            | 7         | 1.01%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 0.87%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.72%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 5         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.58%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.58%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 123       | 26.45%  |
| SK hynix                     | 111       | 23.87%  |
| Micron Technology            | 88        | 18.92%  |
| Kingston                     | 39        | 8.39%   |
| Crucial                      | 28        | 6.02%   |
| Unknown                      | 13        | 2.8%    |
| Unknown                      | 12        | 2.58%   |
| Ramaxel Technology           | 9         | 1.94%   |
| A-DATA Technology            | 9         | 1.94%   |
| Team                         | 7         | 1.51%   |
| G.Skill                      | 5         | 1.08%   |
| Unknown (ABCD)               | 3         | 0.65%   |
| Corsair                      | 3         | 0.65%   |
| Avant                        | 3         | 0.65%   |
| Patriot                      | 2         | 0.43%   |
| Lexar                        | 2         | 0.43%   |
| Smart Brazil                 | 1         | 0.22%   |
| Silicon Power                | 1         | 0.22%   |
| PNY                          | 1         | 0.22%   |
| Patriot Memory (PDP Systems) | 1         | 0.22%   |
| GOODRAM                      | 1         | 0.22%   |
| fef5                         | 1         | 0.22%   |
| Apacer                       | 1         | 0.22%   |
| AMD                          | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 13        | 2.69%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 12        | 2.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 2.07%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.65%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.45%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 6         | 1.24%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 6         | 1.24%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 5         | 1.03%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 1.03%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 5         | 1.03%   |
| Samsung RAM K3KL9L90CM-MGCT 4GB Row Of Chips LPDDR5 7500MT/s     | 5         | 1.03%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s       | 5         | 1.03%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.03%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.83%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 4         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.83%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.83%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.83%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.83%   |
| Micron RAM MT62F2G32D4DS-026 4GB Row Of Chips LPDDR5 7467MT/s    | 4         | 0.83%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 4         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 3         | 0.62%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.62%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.62%   |
| SK hynix RAM H58G66BK7BX067 8GB Row Of Chips LPDDR5 7500MT/s     | 3         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.62%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.62%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 3         | 0.62%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.62%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 3         | 0.62%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 3         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 181       | 46.29%  |
| LPDDR5  | 60        | 15.35%  |
| DDR3    | 58        | 14.83%  |
| DDR5    | 46        | 11.76%  |
| LPDDR4  | 27        | 6.91%   |
| LPDDR3  | 12        | 3.07%   |
| SDRAM   | 3         | 0.77%   |
| DDR2    | 2         | 0.51%   |
| Unknown | 2         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 314       | 78.3%   |
| Row Of Chips | 78        | 19.45%  |
| Unknown      | 5         | 1.25%   |
| Chip         | 4         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 199       | 47.04%  |
| 16384 | 101       | 23.88%  |
| 4096  | 68        | 16.08%  |
| 32768 | 39        | 9.22%   |
| 2048  | 10        | 2.36%   |
| 1024  | 3         | 0.71%   |
| 49152 | 1         | 0.24%   |
| 6144  | 1         | 0.24%   |
| 3072  | 1         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 102       | 24.52%  |
| 2667    | 69        | 16.59%  |
| 1600    | 50        | 12.02%  |
| 5600    | 29        | 6.97%   |
| 6400    | 28        | 6.73%   |
| 2400    | 24        | 5.77%   |
| 7500    | 23        | 5.53%   |
| 2133    | 21        | 5.05%   |
| 4800    | 19        | 4.57%   |
| 4267    | 13        | 3.13%   |
| 7467    | 6         | 1.44%   |
| 4266    | 6         | 1.44%   |
| 1867    | 6         | 1.44%   |
| 3266    | 4         | 0.96%   |
| 1333    | 4         | 0.96%   |
| Unknown | 3         | 0.72%   |
| 5500    | 2         | 0.48%   |
| 4199    | 2         | 0.48%   |
| 8533    | 1         | 0.24%   |
| 5200    | 1         | 0.24%   |
| 1334    | 1         | 0.24%   |
| 800     | 1         | 0.24%   |
| 667     | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Dymo-CoStar | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Dymo-CoStar DYMO LabelPOINT 350 | 1         | 100%    |

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
| Chicony Electronics                    | 79        | 22.77%  |
| IMC Networks                           | 43        | 12.39%  |
| Bison Electronics                      | 33        | 9.51%   |
| Microdia                               | 29        | 8.36%   |
| Realtek Semiconductor                  | 26        | 7.49%   |
| Quanta                                 | 18        | 5.19%   |
| Luxvisions Innotech Limited            | 18        | 5.19%   |
| Sunplus Innovation Technology          | 16        | 4.61%   |
| ShineTech                              | 15        | 4.32%   |
| Logitech                               | 10        | 2.88%   |
| Syntek                                 | 9         | 2.59%   |
| Apple                                  | 7         | 2.02%   |
| Lite-On Technology                     | 6         | 1.73%   |
| Acer                                   | 6         | 1.73%   |
| Sonix Technology                       | 5         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 0.86%   |
| Silicon Motion                         | 2         | 0.58%   |
| Samsung Electronics                    | 2         | 0.58%   |
| Primax Electronics                     | 2         | 0.58%   |
| icSpring                               | 2         | 0.58%   |
| Alcor Micro                            | 2         | 0.58%   |
| Z-Star Microelectronics                | 1         | 0.29%   |
| SunplusIT                              | 1         | 0.29%   |
| Ricoh                                  | 1         | 0.29%   |
| OmniVision Technologies                | 1         | 0.29%   |
| Microsoft                              | 1         | 0.29%   |
| MacroSilicon                           | 1         | 0.29%   |
| kingcome                               | 1         | 0.29%   |
| HYGD-220831-A                          | 1         | 0.29%   |
| Hopewin Electronic Material            | 1         | 0.29%   |
| globaloptics                           | 1         | 0.29%   |
| DRFCB0ABIHX4E3                         | 1         | 0.29%   |
| Aveo Technology                        | 1         | 0.29%   |
| ALi                                    | 1         | 0.29%   |
| 2M UVC CAMERA                          | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 37        | 10.54%  |
| IMC Networks Integrated Camera                      | 23        | 6.55%   |
| Microdia Integrated_Webcam_HD                       | 17        | 4.84%   |
| Bison Integrated Camera                             | 17        | 4.84%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 3.13%   |
| Luxvisions Innotech Limited Integrated Camera       | 9         | 2.56%   |
| Syntek Integrated Camera                            | 8         | 2.28%   |
| Realtek Laptop Camera                               | 8         | 2.28%   |
| Chicony HP HD Camera                                | 8         | 2.28%   |
| Shinetech USB2.0 FHD UVC WebCam                     | 7         | 1.99%   |
| Realtek Integrated_Webcam_HD                        | 7         | 1.99%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 1.71%   |
| Sunplus Integrated_Webcam_FHD                       | 5         | 1.42%   |
| ShineTech USB2.0 HD UVC WebCam                      | 5         | 1.42%   |
| Lite-On Integrated Camera                           | 5         | 1.42%   |
| Microdia Integrated Webcam                          | 4         | 1.14%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 4         | 1.14%   |
| Logitech HD Pro Webcam C920                         | 4         | 1.14%   |
| IMC Networks HD Camera                              | 4         | 1.14%   |
| Chicony HP 5MP Camera                               | 4         | 1.14%   |
| Chicony HD User Facing                              | 4         | 1.14%   |
| Bison SunplusIT Integrated Camera                   | 4         | 1.14%   |
| Bison HD Webcam                                     | 4         | 1.14%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 1.14%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 0.85%   |
| Shinetech ASUS FHD webcam                           | 3         | 0.85%   |
| Quanta USB2.0 HD UVC WebCam                         | 3         | 0.85%   |
| Quanta HD Webcam                                    | 3         | 0.85%   |
| Quanta HD User Facing                               | 3         | 0.85%   |
| Chicony USB2.0 Camera                               | 3         | 0.85%   |
| Chicony FHD Webcam                                  | 3         | 0.85%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.57%   |
| Realtek Bluetooth Radio                             | 2         | 0.57%   |
| Quanta ACER HD User Facing                          | 2         | 0.57%   |
| Primax HP HD Webcam [Fixed]                         | 2         | 0.57%   |
| Microdia Webcam Vitade AF                           | 2         | 0.57%   |
| Microdia USB 2.0 Camera                             | 2         | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 41        | 46.07%  |
| Validity Sensors                   | 20        | 22.47%  |
| Shenzhen Goodix Technology         | 18        | 20.22%  |
| Elan Microelectronics              | 4         | 4.49%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.25%   |
| Samsung Electronics                | 1         | 1.12%   |
| LighTuning Technology              | 1         | 1.12%   |
| HOLTEK                             | 1         | 1.12%   |
| Focal-systems.Corp                 | 1         | 1.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 16.85%  |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 10.11%  |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 8.99%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 7.87%   |
| Synaptics UWP WBDI Device                                                  | 6         | 6.74%   |
| Synaptics Prometheus Fingerprint Reader                                    | 6         | 6.74%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 5.62%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 4.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.49%   |
| Elan ELAN:ARM-M4                                                           | 4         | 4.49%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 2.25%   |
| Validity Sensors VFS491                                                    | 2         | 2.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 2.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.12%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.12%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.12%   |
| Synaptics UWP WBDI                                                         | 1         | 1.12%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.12%   |
| Samsung Fingerprint Device                                                 | 1         | 1.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.12%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 1.12%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 1.12%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 34        | 62.96%  |
| Broadcom    | 11        | 20.37%  |
| Yubico.com  | 7         | 12.96%  |
| Upek        | 2         | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 62.96%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 11.11%  |
| Broadcom 58200                                                               | 4         | 7.41%   |
| Broadcom 5880                                                                | 3         | 5.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 3.7%    |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 216       | 53.2%   |
| 1     | 131       | 32.27%  |
| 2     | 49        | 12.07%  |
| 3     | 8         | 1.97%   |
| 4     | 2         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 87        | 34.66%  |
| Multimedia controller    | 50        | 19.92%  |
| Chipcard                 | 43        | 17.13%  |
| Graphics card            | 28        | 11.16%  |
| Camera                   | 12        | 4.78%   |
| Net/wireless             | 11        | 4.38%   |
| Communication controller | 5         | 1.99%   |
| Card reader              | 5         | 1.99%   |
| Bluetooth                | 3         | 1.2%    |
| Network                  | 2         | 0.8%    |
| Modem                    | 2         | 0.8%    |
| Unassigned class         | 1         | 0.4%    |
| Net/ethernet             | 1         | 0.4%    |
| Firewire controller      | 1         | 0.4%    |

