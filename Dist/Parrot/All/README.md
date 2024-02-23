Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 809

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro11,1              | Notebook    | [fcabd4a1f4](https://linux-hardware.org/?probe=fcabd4a1f4) | Feb 01, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [b31d7d9323](https://linux-hardware.org/?probe=b31d7d9323) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [7acd38748f](https://linux-hardware.org/?probe=7acd38748f) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0a1087fdad](https://linux-hardware.org/?probe=0a1087fdad) | Jan 29, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b7fff52e41](https://linux-hardware.org/?probe=b7fff52e41) | Jan 29, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [7c4514376b](https://linux-hardware.org/?probe=7c4514376b) | Jan 27, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [f1117537a5](https://linux-hardware.org/?probe=f1117537a5) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [fad23c2b03](https://linux-hardware.org/?probe=fad23c2b03) | Jan 27, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [fb1c7c4cab](https://linux-hardware.org/?probe=fb1c7c4cab) | Jan 26, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2JW0... | Notebook    | [59d637113b](https://linux-hardware.org/?probe=59d637113b) | Jan 26, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [a43c97b66c](https://linux-hardware.org/?probe=a43c97b66c) | Jan 26, 2024 |
| HP            | ProBook 455 G4              | Notebook    | [6490d02d72](https://linux-hardware.org/?probe=6490d02d72) | Jan 22, 2024 |
| ASRock        | Z77M                        | Desktop     | [f3bd1cdf2c](https://linux-hardware.org/?probe=f3bd1cdf2c) | Jan 19, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [bb5610a4f5](https://linux-hardware.org/?probe=bb5610a4f5) | Jan 17, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [538c5ee96f](https://linux-hardware.org/?probe=538c5ee96f) | Jan 16, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [ca8734dc63](https://linux-hardware.org/?probe=ca8734dc63) | Jan 11, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [feaf3edd58](https://linux-hardware.org/?probe=feaf3edd58) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | Notebook    | [ce82358c06](https://linux-hardware.org/?probe=ce82358c06) | Jan 04, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | Notebook    | [ffe96991b4](https://linux-hardware.org/?probe=ffe96991b4) | Jan 04, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [b80a7c9287](https://linux-hardware.org/?probe=b80a7c9287) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1f44330bcf](https://linux-hardware.org/?probe=1f44330bcf) | Dec 31, 2023 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | Notebook    | [0afd47e9fc](https://linux-hardware.org/?probe=0afd47e9fc) | Dec 31, 2023 |
| Google        | Blorb                       | Notebook    | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [404320e4d7](https://linux-hardware.org/?probe=404320e4d7) | Dec 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [62a002d063](https://linux-hardware.org/?probe=62a002d063) | Dec 26, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [980280224f](https://linux-hardware.org/?probe=980280224f) | Dec 18, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [41f03f0699](https://linux-hardware.org/?probe=41f03f0699) | Dec 18, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [72facc22f6](https://linux-hardware.org/?probe=72facc22f6) | Dec 14, 2023 |
| Toshiba       | PORTEGE R930                | Notebook    | [e341599417](https://linux-hardware.org/?probe=e341599417) | Dec 14, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [d90c13f9c6](https://linux-hardware.org/?probe=d90c13f9c6) | Dec 12, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [baf21dcbce](https://linux-hardware.org/?probe=baf21dcbce) | Dec 06, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [86295630b8](https://linux-hardware.org/?probe=86295630b8) | Dec 06, 2023 |
| Alienware     | 17 R5                       | Notebook    | [e0fdc679e3](https://linux-hardware.org/?probe=e0fdc679e3) | Dec 04, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1e44992982](https://linux-hardware.org/?probe=1e44992982) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d416d62cf1](https://linux-hardware.org/?probe=d416d62cf1) | Nov 29, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [a54c387b5f](https://linux-hardware.org/?probe=a54c387b5f) | Nov 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3242361790](https://linux-hardware.org/?probe=3242361790) | Nov 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8ad2369936](https://linux-hardware.org/?probe=8ad2369936) | Nov 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | Notebook    | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| Acer          | TravelMate 5760             | Notebook    | [f90be838c9](https://linux-hardware.org/?probe=f90be838c9) | Nov 18, 2023 |
| Acer          | TravelMate 5760             | Notebook    | [db234d226d](https://linux-hardware.org/?probe=db234d226d) | Nov 18, 2023 |
| Dell          | Latitude E6530              | Notebook    | [f43bd72db4](https://linux-hardware.org/?probe=f43bd72db4) | Nov 16, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [20394838bd](https://linux-hardware.org/?probe=20394838bd) | Nov 11, 2023 |
| Gateway       | TBGM01                      | Desktop     | [3ca4695541](https://linux-hardware.org/?probe=3ca4695541) | Nov 07, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [e7b5bfa0b4](https://linux-hardware.org/?probe=e7b5bfa0b4) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [9b13411bc8](https://linux-hardware.org/?probe=9b13411bc8) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ce8997d5a](https://linux-hardware.org/?probe=4ce8997d5a) | Nov 05, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [98e32e98bf](https://linux-hardware.org/?probe=98e32e98bf) | Oct 31, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [be57c0ce22](https://linux-hardware.org/?probe=be57c0ce22) | Oct 29, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [3c959b9af8](https://linux-hardware.org/?probe=3c959b9af8) | Oct 25, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [e3540cf969](https://linux-hardware.org/?probe=e3540cf969) | Oct 23, 2023 |
| Google        | Reef                        | Notebook    | [819e00dd76](https://linux-hardware.org/?probe=819e00dd76) | Oct 22, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [fb0b3ea9e7](https://linux-hardware.org/?probe=fb0b3ea9e7) | Oct 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0755ce07a3](https://linux-hardware.org/?probe=0755ce07a3) | Oct 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [35081bd0e8](https://linux-hardware.org/?probe=35081bd0e8) | Oct 08, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [a13621c5d3](https://linux-hardware.org/?probe=a13621c5d3) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [144cbc70d0](https://linux-hardware.org/?probe=144cbc70d0) | Oct 03, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [5ef983c393](https://linux-hardware.org/?probe=5ef983c393) | Oct 01, 2023 |
| HP            | 8619                        | Desktop     | [d631850d2f](https://linux-hardware.org/?probe=d631850d2f) | Sep 28, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [34e34036d7](https://linux-hardware.org/?probe=34e34036d7) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| HP            | 8714                        | Desktop     | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e10f21c5c5](https://linux-hardware.org/?probe=e10f21c5c5) | Sep 22, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [648ac87a81](https://linux-hardware.org/?probe=648ac87a81) | Sep 21, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [faf0bfe427](https://linux-hardware.org/?probe=faf0bfe427) | Sep 17, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [2f99528572](https://linux-hardware.org/?probe=2f99528572) | Sep 16, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [6495df6735](https://linux-hardware.org/?probe=6495df6735) | Sep 15, 2023 |
| Acer          | Aspire C20-820              | All in one  | [1b2bdeafca](https://linux-hardware.org/?probe=1b2bdeafca) | Sep 11, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e59c5b4fda](https://linux-hardware.org/?probe=e59c5b4fda) | Sep 10, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| Toshiba       | Satellite L775D             | Notebook    | [681dab0969](https://linux-hardware.org/?probe=681dab0969) | Sep 09, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [694ffed41f](https://linux-hardware.org/?probe=694ffed41f) | Sep 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [039aa353eb](https://linux-hardware.org/?probe=039aa353eb) | Sep 06, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [101a39c37a](https://linux-hardware.org/?probe=101a39c37a) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [da3ab01b3a](https://linux-hardware.org/?probe=da3ab01b3a) | Aug 25, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [57f24399d5](https://linux-hardware.org/?probe=57f24399d5) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [a7c7baada2](https://linux-hardware.org/?probe=a7c7baada2) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [8b42955659](https://linux-hardware.org/?probe=8b42955659) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| MSI           | 3666h                       | Desktop     | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Dell          | 0100P6 A01                  | Desktop     | [2cf993001c](https://linux-hardware.org/?probe=2cf993001c) | Aug 13, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3e66a1f712](https://linux-hardware.org/?probe=3e66a1f712) | Aug 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b76b1bf00a](https://linux-hardware.org/?probe=b76b1bf00a) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63665fca24](https://linux-hardware.org/?probe=63665fca24) | Aug 08, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [324819c88d](https://linux-hardware.org/?probe=324819c88d) | Aug 08, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| Dell          | Precision 7730              | Notebook    | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [48ec623298](https://linux-hardware.org/?probe=48ec623298) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [7979e7ce95](https://linux-hardware.org/?probe=7979e7ce95) | Aug 05, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [70c6936cfc](https://linux-hardware.org/?probe=70c6936cfc) | Aug 04, 2023 |
| Dell          | 0RY007                      | Desktop     | [8317045335](https://linux-hardware.org/?probe=8317045335) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [ad4e7cf4ad](https://linux-hardware.org/?probe=ad4e7cf4ad) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [36d9df3244](https://linux-hardware.org/?probe=36d9df3244) | Jul 31, 2023 |
| MSI           | Katana 17 B13VFK            | Notebook    | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [d047b35269](https://linux-hardware.org/?probe=d047b35269) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [af539103c5](https://linux-hardware.org/?probe=af539103c5) | Jul 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [58882ecdfe](https://linux-hardware.org/?probe=58882ecdfe) | Jul 20, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [3e6412c30b](https://linux-hardware.org/?probe=3e6412c30b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [c4b019ee7f](https://linux-hardware.org/?probe=c4b019ee7f) | Jul 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d7c21e7889](https://linux-hardware.org/?probe=d7c21e7889) | Jul 13, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Samsung       | 750XED                      | Notebook    | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [70a6354074](https://linux-hardware.org/?probe=70a6354074) | Jul 05, 2023 |
| Dell          | Latitude 3410               | Notebook    | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [4a4b49a909](https://linux-hardware.org/?probe=4a4b49a909) | Jul 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b4d959d91f](https://linux-hardware.org/?probe=b4d959d91f) | Jul 02, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [12871de62d](https://linux-hardware.org/?probe=12871de62d) | Jun 30, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [a4b38b88cc](https://linux-hardware.org/?probe=a4b38b88cc) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [e28a0d43ed](https://linux-hardware.org/?probe=e28a0d43ed) | Jun 27, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [ee31bf4efe](https://linux-hardware.org/?probe=ee31bf4efe) | Jun 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| Samsung       | 530XBB                      | Notebook    | [51007aebd3](https://linux-hardware.org/?probe=51007aebd3) | Jun 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [190d408bc2](https://linux-hardware.org/?probe=190d408bc2) | Jun 23, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [fa49028492](https://linux-hardware.org/?probe=fa49028492) | Jun 23, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [3055046330](https://linux-hardware.org/?probe=3055046330) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | Notebook    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [2102fc8523](https://linux-hardware.org/?probe=2102fc8523) | Jun 19, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [464db6c1df](https://linux-hardware.org/?probe=464db6c1df) | Jun 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [11161fa30c](https://linux-hardware.org/?probe=11161fa30c) | Jun 18, 2023 |
| Lenovo        | ThinkPad L520 78595GJ       | Notebook    | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [e25ec87b40](https://linux-hardware.org/?probe=e25ec87b40) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [35c6e2b80e](https://linux-hardware.org/?probe=35c6e2b80e) | Jun 17, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [20a66afa75](https://linux-hardware.org/?probe=20a66afa75) | Jun 14, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [dbf4a1d57c](https://linux-hardware.org/?probe=dbf4a1d57c) | Jun 12, 2023 |
| HP            | 339A                        | Desktop     | [d1fa07d03f](https://linux-hardware.org/?probe=d1fa07d03f) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f72410be27](https://linux-hardware.org/?probe=f72410be27) | Jun 08, 2023 |
| HP            | 339A                        | Desktop     | [f2147ed11b](https://linux-hardware.org/?probe=f2147ed11b) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f0e52437a7](https://linux-hardware.org/?probe=f0e52437a7) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [59e64db8de](https://linux-hardware.org/?probe=59e64db8de) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [15b23b6779](https://linux-hardware.org/?probe=15b23b6779) | May 30, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | Notebook    | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4c3bfe7a9d](https://linux-hardware.org/?probe=4c3bfe7a9d) | May 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Latitude 7280               | Notebook    | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2ddb8221f](https://linux-hardware.org/?probe=d2ddb8221f) | May 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [719fbbd5a5](https://linux-hardware.org/?probe=719fbbd5a5) | May 23, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| Lenovo        | ThinkPad E14 20RA0059VA     | Notebook    | [72280fb1c5](https://linux-hardware.org/?probe=72280fb1c5) | May 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [689db5f7b4](https://linux-hardware.org/?probe=689db5f7b4) | May 14, 2023 |
| Dell          | Latitude 7370               | Notebook    | [78654593c7](https://linux-hardware.org/?probe=78654593c7) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4ea44288b5](https://linux-hardware.org/?probe=4ea44288b5) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| HP            | Notebook                    | Notebook    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [e9c446ce66](https://linux-hardware.org/?probe=e9c446ce66) | May 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | Notebook    | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b4861cf35c](https://linux-hardware.org/?probe=b4861cf35c) | Apr 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | Notebook    | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0f3f45f8e9](https://linux-hardware.org/?probe=0f3f45f8e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [2f61bfa5a5](https://linux-hardware.org/?probe=2f61bfa5a5) | Apr 04, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1e81e330e1](https://linux-hardware.org/?probe=1e81e330e1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Google        | Lillipup                    | Notebook    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASRock        | B560M-C                     | Desktop     | [a93d64aa2c](https://linux-hardware.org/?probe=a93d64aa2c) | Feb 28, 2023 |
| ASRock        | B560M-C                     | Desktop     | [cbbd0a63d4](https://linux-hardware.org/?probe=cbbd0a63d4) | Feb 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | 0C1R19 A02                  | Desktop     | [42ff2c0844](https://linux-hardware.org/?probe=42ff2c0844) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| ASRock        | B560M-C                     | Desktop     | [0641c704e9](https://linux-hardware.org/?probe=0641c704e9) | Feb 20, 2023 |
| Biostar       | B450MH                      | Desktop     | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| Google        | Robo360                     | Notebook    | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bfb29a2d13](https://linux-hardware.org/?probe=bfb29a2d13) | Feb 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | Notebook    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [6552c7b8b3](https://linux-hardware.org/?probe=6552c7b8b3) | Jan 22, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [64164ef7df](https://linux-hardware.org/?probe=64164ef7df) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [46befb7112](https://linux-hardware.org/?probe=46befb7112) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | Notebook    | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | Notebook    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | Notebook    | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9496d56fab](https://linux-hardware.org/?probe=9496d56fab) | Jan 04, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| HP            | 3397                        | Desktop     | [33ba62be32](https://linux-hardware.org/?probe=33ba62be32) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Dell          | G3 3500                     | Notebook    | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | Notebook    | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d57a12d93c](https://linux-hardware.org/?probe=d57a12d93c) | Nov 20, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [7928d11567](https://linux-hardware.org/?probe=7928d11567) | Nov 19, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| Dell          | 0C1R19 A02                  | Desktop     | [514ae17aa9](https://linux-hardware.org/?probe=514ae17aa9) | Nov 06, 2022 |
| HP            | 89B5 A                      | Desktop     | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | Notebook    | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [d84fc5ce81](https://linux-hardware.org/?probe=d84fc5ce81) | Oct 13, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [2a896ec4f6](https://linux-hardware.org/?probe=2a896ec4f6) | Oct 13, 2022 |
| Clevo         | W25xHPx                     | Notebook    | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | Notebook    | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | Notebook    | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | Notebook    | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| HP            | Presario CQ58               | Notebook    | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [7ad1831ce9](https://linux-hardware.org/?probe=7ad1831ce9) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fa26302bd8](https://linux-hardware.org/?probe=fa26302bd8) | Aug 27, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | Notebook    | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| Gateway       | SX2855                      | Desktop     | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [007eeacf86](https://linux-hardware.org/?probe=007eeacf86) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8ce974e537](https://linux-hardware.org/?probe=8ce974e537) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | Notebook    | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [623281f994](https://linux-hardware.org/?probe=623281f994) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f6c3c6f86e](https://linux-hardware.org/?probe=f6c3c6f86e) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c680f5f212](https://linux-hardware.org/?probe=c680f5f212) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | Notebook    | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7e3fc5fe06](https://linux-hardware.org/?probe=7e3fc5fe06) | Jun 02, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [02ace99875](https://linux-hardware.org/?probe=02ace99875) | Jun 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [449fc46111](https://linux-hardware.org/?probe=449fc46111) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Unknown       | TB-4000                     | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Unknown       | TB-4000                     | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Radxa         | ROCK 5B                     | Soc         | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | Notebook    | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | Notebook    | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | Notebook    | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Dell          | Latitude E6420              | Notebook    | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| ASUSTek       | K31CD-K                     | Desktop     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| Dell          | Inspiron 5721               | Notebook    | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | Notebook    | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [224ebfd9b3](https://linux-hardware.org/?probe=224ebfd9b3) | Mar 30, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [79e98a64cf](https://linux-hardware.org/?probe=79e98a64cf) | Mar 30, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | Notebook    | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [cf7e8cd869](https://linux-hardware.org/?probe=cf7e8cd869) | Mar 16, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Notebook      | W510TU                      | Notebook    | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | Notebook    | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | Notebook    | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | Notebook    | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | Notebook    | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | Notebook    | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | Notebook    | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | Notebook    | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Parrot/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.3   | 120       | 20.37%  |
| Parrot 5.0   | 119       | 20.2%   |
| Parrot 4.11  | 98        | 16.64%  |
| Parrot 5.1   | 74        | 12.56%  |
| Parrot 4.10  | 60        | 10.19%  |
| Parrot 5.2   | 36        | 6.11%   |
| Parrot 4.8   | 23        | 3.9%    |
| Parrot 4.9   | 22        | 3.74%   |
| Parrot 6.0   | 18        | 3.06%   |
| Parrot 4.7   | 13        | 2.21%   |
| Parrot 4.6   | 2         | 0.34%   |
| Parrot 4.5   | 1         | 0.17%   |
| Parrot 4.4   | 1         | 0.17%   |
| Parrot 4.2.2 | 1         | 0.17%   |
| Parrot 3.10  | 1         | 0.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 562       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 6.1.0-1parrot1-amd64      | 117       | 19.53%  |
| 5.16.0-12parrot1-amd64    | 56        | 9.35%   |
| 5.14.0-9parrot1-amd64     | 54        | 9.02%   |
| 6.0.0-12parrot1-amd64     | 47        | 7.85%   |
| 5.10.0-6parrot1-amd64     | 35        | 5.84%   |
| 5.18.0-14parrot1-amd64    | 34        | 5.68%   |
| 6.0.0-2parrot1-amd64      | 33        | 5.51%   |
| 5.7.0-2parrot2-amd64      | 33        | 5.51%   |
| 5.5.0-1parrot1-amd64      | 24        | 4.01%   |
| 5.10.0-8parrot1-amd64     | 18        | 3.01%   |
| 5.18.0-1parrot1-amd64     | 17        | 2.84%   |
| 5.4.0-4parrot1-amd64      | 16        | 2.67%   |
| 6.5.0-13parrot1-amd64     | 11        | 1.84%   |
| 5.15.0-15parrot1-amd64    | 11        | 1.84%   |
| 5.14.0-2parrot1-amd64     | 11        | 1.84%   |
| 5.6.0-2parrot1-amd64      | 10        | 1.67%   |
| 5.9.0-2parrot1-amd64      | 9         | 1.5%    |
| 5.8.0-2parrot1-amd64      | 6         | 1%      |
| 6.5.0-3parrot1-amd64      | 5         | 0.83%   |
| 5.4.0-2parrot1-amd64      | 5         | 0.83%   |
| 5.10.0-3parrot1-amd64     | 5         | 0.83%   |
| 5.8.0-1parrot1-amd64      | 4         | 0.67%   |
| 5.10.0-5parrot1-amd64     | 4         | 0.67%   |
| 5.4.0-3parrot1-amd64      | 3         | 0.5%    |
| 5.3.0-3parrot3-amd64      | 3         | 0.5%    |
| 5.2.0-2parrot1-amd64      | 3         | 0.5%    |
| 4.19.0-parrot4-28t-amd64  | 3         | 0.5%    |
| 6.0.5-x64v1-xanmod1       | 2         | 0.33%   |
| 5.10.92-v8+               | 2         | 0.33%   |
| 4.18.0-parrot10-amd64     | 2         | 0.33%   |
| 6.5.0-kali3-amd64         | 1         | 0.17%   |
| 6.1.27chrultrabook-fixups | 1         | 0.17%   |
| 6.1.0-0.deb11.5-amd64     | 1         | 0.17%   |
| 5.7.0-rc6-galliumos       | 1         | 0.17%   |
| 5.4.0-2parrot1-686-pae    | 1         | 0.17%   |
| 5.4.0-1parrot1-amd64      | 1         | 0.17%   |
| 5.3.0-3parrot3-686-pae    | 1         | 0.17%   |
| 5.3.0-1parrot1-amd64      | 1         | 0.17%   |
| 5.16.0-12parrot1-686-pae  | 1         | 0.17%   |
| 5.15.0-5parrot1-amd64     | 1         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 118       | 19.83%  |
| 6.0.0   | 79        | 13.28%  |
| 5.10.0  | 64        | 10.76%  |
| 5.14.0  | 63        | 10.59%  |
| 5.16.0  | 57        | 9.58%   |
| 5.18.0  | 50        | 8.4%    |
| 5.7.0   | 34        | 5.71%   |
| 5.4.0   | 26        | 4.37%   |
| 5.5.0   | 24        | 4.03%   |
| 6.5.0   | 17        | 2.86%   |
| 5.15.0  | 12        | 2.02%   |
| 5.8.0   | 10        | 1.68%   |
| 5.6.0   | 10        | 1.68%   |
| 5.9.0   | 9         | 1.51%   |
| 5.3.0   | 5         | 0.84%   |
| 4.19.0  | 4         | 0.67%   |
| 5.2.0   | 3         | 0.5%    |
| 6.0.5   | 2         | 0.34%   |
| 5.10.92 | 2         | 0.34%   |
| 4.18.0  | 2         | 0.34%   |
| 6.1.27  | 1         | 0.17%   |
| 5.1.0   | 1         | 0.17%   |
| 4.14.0  | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 119       | 20%     |
| 6.0     | 81        | 13.61%  |
| 5.10    | 66        | 11.09%  |
| 5.14    | 63        | 10.59%  |
| 5.16    | 57        | 9.58%   |
| 5.18    | 50        | 8.4%    |
| 5.7     | 34        | 5.71%   |
| 5.4     | 26        | 4.37%   |
| 5.5     | 24        | 4.03%   |
| 6.5     | 17        | 2.86%   |
| 5.15    | 12        | 2.02%   |
| 5.8     | 10        | 1.68%   |
| 5.6     | 10        | 1.68%   |
| 5.9     | 9         | 1.51%   |
| 5.3     | 5         | 0.84%   |
| 4.19    | 4         | 0.67%   |
| 5.2     | 3         | 0.5%    |
| 4.18    | 2         | 0.34%   |
| 5.1     | 1         | 0.17%   |
| 4.14    | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 558       | 99.29%  |
| i686    | 2         | 0.36%   |
| aarch64 | 2         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| MATE            | 427       | 74.13%  |
| KDE5            | 80        | 13.89%  |
| Unknown         | 23        | 3.99%   |
| KDE             | 20        | 3.47%   |
| XFCE            | 15        | 2.6%    |
| GNOME           | 4         | 0.69%   |
| X-Cinnamon      | 2         | 0.35%   |
| LXDE            | 1         | 0.17%   |
| GNOME Flashback | 1         | 0.17%   |
| GNOME Classic   | 1         | 0.17%   |
| Cinnamon        | 1         | 0.17%   |
| bspwm           | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 551       | 98.04%  |
| Wayland | 5         | 0.89%   |
| Tty     | 4         | 0.71%   |
| Unknown | 2         | 0.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 308       | 53.38%  |
| Unknown | 173       | 29.98%  |
| TDM     | 71        | 12.31%  |
| SDDM    | 16        | 2.77%   |
| GDM     | 9         | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 313       | 55.4%   |
| en_GB   | 35        | 6.19%   |
| fr_FR   | 22        | 3.89%   |
| es_ES   | 19        | 3.36%   |
| de_DE   | 17        | 3.01%   |
| ru_RU   | 16        | 2.83%   |
| en_AU   | 15        | 2.65%   |
| Unknown | 15        | 2.65%   |
| en_IN   | 14        | 2.48%   |
| pt_BR   | 13        | 2.3%    |
| pl_PL   | 12        | 2.12%   |
| it_IT   | 11        | 1.95%   |
| en_CA   | 7         | 1.24%   |
| es_MX   | 6         | 1.06%   |
| cs_CZ   | 4         | 0.71%   |
| tr_TR   | 3         | 0.53%   |
| es_CO   | 3         | 0.53%   |
| es_AR   | 3         | 0.53%   |
| en_IE   | 3         | 0.53%   |
| C       | 3         | 0.53%   |
| id_ID   | 2         | 0.35%   |
| es_PE   | 2         | 0.35%   |
| es_CL   | 2         | 0.35%   |
| en_ZA   | 2         | 0.35%   |
| en_NZ   | 2         | 0.35%   |
| en_HK   | 2         | 0.35%   |
| en_DK   | 2         | 0.35%   |
| sk_SK   | 1         | 0.18%   |
| ru_UA   | 1         | 0.18%   |
| pt_PT   | 1         | 0.18%   |
| nl_BE   | 1         | 0.18%   |
| nb_NO   | 1         | 0.18%   |
| mk_MK   | 1         | 0.18%   |
| lt_LT   | 1         | 0.18%   |
| fr_CH   | 1         | 0.18%   |
| fr_CA   | 1         | 0.18%   |
| fi_FI   | 1         | 0.18%   |
| en_ZW   | 1         | 0.18%   |
| en_ZM   | 1         | 0.18%   |
| en_NG   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 316       | 55.24%  |
| EFI  | 256       | 44.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 436       | 76.63%  |
| Ext4    | 74        | 13.01%  |
| Overlay | 23        | 4.04%   |
| Tmpfs   | 15        | 2.64%   |
| Xfs     | 14        | 2.46%   |
| Unknown | 7         | 1.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 275       | 47.83%  |
| Unknown | 205       | 35.65%  |
| MBR     | 95        | 16.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 491       | 86.29%  |
| Yes       | 78        | 13.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 361       | 63.67%  |
| Yes       | 206       | 36.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 97        | 17.26%  |
| Hewlett-Packard                      | 96        | 17.08%  |
| ASUSTek Computer                     | 79        | 14.06%  |
| Dell                                 | 78        | 13.88%  |
| Acer                                 | 35        | 6.23%   |
| MSI                                  | 34        | 6.05%   |
| Gigabyte Technology                  | 20        | 3.56%   |
| Apple                                | 18        | 3.2%    |
| Toshiba                              | 11        | 1.96%   |
| Samsung Electronics                  | 8         | 1.42%   |
| ASRock                               | 6         | 1.07%   |
| Unknown                              | 6         | 1.07%   |
| HUAWEI                               | 5         | 0.89%   |
| Alienware                            | 5         | 0.89%   |
| Microsoft                            | 4         | 0.71%   |
| Google                               | 4         | 0.71%   |
| Gateway                              | 4         | 0.71%   |
| Sony                                 | 3         | 0.53%   |
| Fujitsu                              | 3         | 0.53%   |
| Foxconn                              | 3         | 0.53%   |
| Razer                                | 2         | 0.36%   |
| Raspberry Pi Foundation              | 2         | 0.36%   |
| Quanta                               | 2         | 0.36%   |
| Positivo                             | 2         | 0.36%   |
| Pegatron                             | 2         | 0.36%   |
| Notebook                             | 2         | 0.36%   |
| ECS                                  | 2         | 0.36%   |
| Biostar                              | 2         | 0.36%   |
| ZOTAC                                | 1         | 0.18%   |
| Wortmann AG                          | 1         | 0.18%   |
| Wistron                              | 1         | 0.18%   |
| Toxic                                | 1         | 0.18%   |
| Timi                                 | 1         | 0.18%   |
| System76                             | 1         | 0.18%   |
| Standard                             | 1         | 0.18%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.18%   |
| Radxa                                | 1         | 0.18%   |
| Positivo Bahia - VAIO                | 1         | 0.18%   |
| Panasonic                            | 1         | 0.18%   |
| Onda TLC                             | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 9         | 1.6%    |
| HP Notebook                          | 4         | 0.71%   |
| HP Laptop 15-dy2xxx                  | 4         | 0.71%   |
| MSI Modern 15 A5M                    | 3         | 0.53%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 3         | 0.53%   |
| HP Pavilion 15                       | 3         | 0.53%   |
| HP ENVY x360 Convertible 13-bd0xxx   | 3         | 0.53%   |
| HP EliteBook 8470p                   | 3         | 0.53%   |
| Dell Latitude E6420                  | 3         | 0.53%   |
| Dell Inspiron MM061                  | 3         | 0.53%   |
| ASUS M5A78L-M/USB3                   | 3         | 0.53%   |
| Toshiba Satellite L775D              | 2         | 0.36%   |
| RPi Raspberry Pi 4 Model B Rev 1.5   | 2         | 0.36%   |
| Quanta TW9/SW9                       | 2         | 0.36%   |
| MSI Katana GF66 12UC                 | 2         | 0.36%   |
| Microsoft Surface Pro 3              | 2         | 0.36%   |
| HP ProDesk 600 G1 SFF                | 2         | 0.36%   |
| HP ProBook 650 G1                    | 2         | 0.36%   |
| HP Pavilion g6                       | 2         | 0.36%   |
| HP Pavilion dv6                      | 2         | 0.36%   |
| HP ENVY x360 2-in-1 Laptop 15-ew0xxx | 2         | 0.36%   |
| HP Compaq 8200 Elite SFF PC          | 2         | 0.36%   |
| Gigabyte AX370-Gaming                | 2         | 0.36%   |
| Foxconn s5710t                       | 2         | 0.36%   |
| Dell XPS 13 9350                     | 2         | 0.36%   |
| Dell OptiPlex 7010                   | 2         | 0.36%   |
| Dell OptiPlex 3020                   | 2         | 0.36%   |
| Dell Latitude E7440                  | 2         | 0.36%   |
| Dell Latitude E6410                  | 2         | 0.36%   |
| Dell Latitude 7280                   | 2         | 0.36%   |
| Dell Inspiron N5110                  | 2         | 0.36%   |
| Dell Inspiron 5676                   | 2         | 0.36%   |
| ASUS Q524UQ                          | 2         | 0.36%   |
| ASUS PRIME X399-A                    | 2         | 0.36%   |
| ASUS M5A99X EVO                      | 2         | 0.36%   |
| ASUS H110I-PLUS                      | 2         | 0.36%   |
| ASUS Basic 3221BM                    | 2         | 0.36%   |
| Apple MacBookPro8,1                  | 2         | 0.36%   |
| Apple MacBookPro11,1                 | 2         | 0.36%   |
| Apple MacBookAir7,2                  | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 49        | 8.72%   |
| Dell Latitude      | 26        | 4.63%   |
| Dell Inspiron      | 24        | 4.27%   |
| Lenovo IdeaPad     | 23        | 4.09%   |
| HP Pavilion        | 18        | 3.2%    |
| Acer Aspire        | 18        | 3.2%    |
| HP Laptop          | 14        | 2.49%   |
| HP EliteBook       | 13        | 2.31%   |
| HP ENVY            | 11        | 1.96%   |
| Toshiba Satellite  | 9         | 1.6%    |
| HP ProBook         | 9         | 1.6%    |
| Dell OptiPlex      | 9         | 1.6%    |
| Unknown            | 9         | 1.6%    |
| HP Compaq          | 8         | 1.42%   |
| ASUS ROG           | 8         | 1.42%   |
| ASUS PRIME         | 8         | 1.42%   |
| Dell XPS           | 7         | 1.25%   |
| Acer Nitro         | 7         | 1.25%   |
| MSI Katana         | 6         | 1.07%   |
| ASUS VivoBook      | 6         | 1.07%   |
| Lenovo Legion      | 5         | 0.89%   |
| ASUS ASUS          | 5         | 0.89%   |
| Microsoft Surface  | 4         | 0.71%   |
| HP ZBook           | 4         | 0.71%   |
| HP Victus          | 4         | 0.71%   |
| HP Notebook        | 4         | 0.71%   |
| Dell Vostro        | 4         | 0.71%   |
| Dell Precision     | 4         | 0.71%   |
| MSI Modern         | 3         | 0.53%   |
| Lenovo Yoga        | 3         | 0.53%   |
| HP ProDesk         | 3         | 0.53%   |
| Fujitsu LIFEBOOK   | 3         | 0.53%   |
| ASUS Zenbook       | 3         | 0.53%   |
| ASUS TUF           | 3         | 0.53%   |
| ASUS M5A78L-M      | 3         | 0.53%   |
| Apple MacBookPro11 | 3         | 0.53%   |
| Acer Swift         | 3         | 0.53%   |
| Acer Predator      | 3         | 0.53%   |
| Razer Blade        | 2         | 0.36%   |
| RPi Raspberry      | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 64        | 11.39%  |
| 2019    | 55        | 9.79%   |
| 2011    | 53        | 9.43%   |
| 2020    | 47        | 8.36%   |
| 2018    | 42        | 7.47%   |
| 2012    | 42        | 7.47%   |
| 2013    | 39        | 6.94%   |
| 2022    | 38        | 6.76%   |
| 2016    | 37        | 6.58%   |
| 2017    | 31        | 5.52%   |
| 2014    | 25        | 4.45%   |
| 2015    | 21        | 3.74%   |
| 2010    | 20        | 3.56%   |
| 2008    | 12        | 2.14%   |
| 2007    | 11        | 1.96%   |
| 2009    | 10        | 1.78%   |
| 2023    | 9         | 1.6%    |
| 2006    | 4         | 0.71%   |
| Unknown | 2         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 396       | 70.46%  |
| Desktop        | 131       | 23.31%  |
| Convertible    | 19        | 3.38%   |
| Tablet         | 5         | 0.89%   |
| All in one     | 5         | 0.89%   |
| System on chip | 3         | 0.53%   |
| Mini pc        | 3         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 562       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 558       | 99.29%  |
| Yes  | 4         | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 151       | 26.54%  |
| 16.01-24.0  | 132       | 23.2%   |
| 8.01-16.0   | 117       | 20.56%  |
| 3.01-4.0    | 85        | 14.94%  |
| 32.01-64.0  | 50        | 8.79%   |
| 1.01-2.0    | 13        | 2.28%   |
| 64.01-256.0 | 11        | 1.93%   |
| 24.01-32.0  | 7         | 1.23%   |
| 2.01-3.0    | 3         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 205       | 34.45%  |
| 1.01-2.0   | 183       | 30.76%  |
| 3.01-4.0   | 89        | 14.96%  |
| 4.01-8.0   | 77        | 12.94%  |
| 0.51-1.0   | 25        | 4.2%    |
| 8.01-16.0  | 11        | 1.85%   |
| 0.01-0.5   | 3         | 0.5%    |
| 16.01-24.0 | 2         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 357       | 61.98%  |
| 2      | 166       | 28.82%  |
| 3      | 30        | 5.21%   |
| 4      | 13        | 2.26%   |
| 5      | 6         | 1.04%   |
| 6      | 2         | 0.35%   |
| 0      | 2         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 409       | 72.01%  |
| Yes       | 159       | 27.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 464       | 82.27%  |
| No        | 100       | 17.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 513       | 90.8%   |
| No        | 52        | 9.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 396       | 69.72%  |
| No        | 172       | 30.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 177       | 31.16%  |
| Germany      | 35        | 6.16%   |
| Spain        | 22        | 3.87%   |
| France       | 22        | 3.87%   |
| UK           | 21        | 3.7%    |
| Russia       | 19        | 3.35%   |
| Brazil       | 19        | 3.35%   |
| Italy        | 18        | 3.17%   |
| India        | 18        | 3.17%   |
| Netherlands  | 17        | 2.99%   |
| Canada       | 15        | 2.64%   |
| Australia    | 13        | 2.29%   |
| Mexico       | 12        | 2.11%   |
| Kenya        | 8         | 1.41%   |
| Poland       | 7         | 1.23%   |
| Indonesia    | 7         | 1.23%   |
| Sweden       | 6         | 1.06%   |
| Czechia      | 6         | 1.06%   |
| Turkey       | 5         | 0.88%   |
| Denmark      | 5         | 0.88%   |
| Bangladesh   | 5         | 0.88%   |
| Algeria      | 5         | 0.88%   |
| Switzerland  | 4         | 0.7%    |
| South Africa | 4         | 0.7%    |
| Egypt        | 4         | 0.7%    |
| Austria      | 4         | 0.7%    |
| UAE          | 3         | 0.53%   |
| Portugal     | 3         | 0.53%   |
| Peru         | 3         | 0.53%   |
| Pakistan     | 3         | 0.53%   |
| Nepal        | 3         | 0.53%   |
| Mongolia     | 3         | 0.53%   |
| Luxembourg   | 3         | 0.53%   |
| Ireland      | 3         | 0.53%   |
| Iraq         | 3         | 0.53%   |
| Finland      | 3         | 0.53%   |
| Colombia     | 3         | 0.53%   |
| Chile        | 3         | 0.53%   |
| Bulgaria     | 3         | 0.53%   |
| Argentina    | 3         | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 8         | 1.35%   |
| Nairobi             | 7         | 1.18%   |
| Dallas              | 6         | 1.02%   |
| Saint Paul          | 5         | 0.85%   |
| Moscow              | 5         | 0.85%   |
| Melbourne           | 5         | 0.85%   |
| Los Angeles         | 5         | 0.85%   |
| Dublin              | 5         | 0.85%   |
| Berlin              | 5         | 0.85%   |
| Sydney              | 4         | 0.68%   |
| Seattle             | 4         | 0.68%   |
| Madrid              | 4         | 0.68%   |
| Lyon                | 4         | 0.68%   |
| London              | 4         | 0.68%   |
| Indianapolis        | 4         | 0.68%   |
| Houston             | 4         | 0.68%   |
| Dhaka               | 4         | 0.68%   |
| Chicago             | 4         | 0.68%   |
| Barcelona           | 4         | 0.68%   |
| Atlanta             | 4         | 0.68%   |
| Warsaw              | 3         | 0.51%   |
| Vienna              | 3         | 0.51%   |
| Ulan Bator          | 3         | 0.51%   |
| Toronto             | 3         | 0.51%   |
| Stockholm           | 3         | 0.51%   |
| Rome                | 3         | 0.51%   |
| Prague              | 3         | 0.51%   |
| Pensacola           | 3         | 0.51%   |
| Paris               | 3         | 0.51%   |
| Minneapolis         | 3         | 0.51%   |
| Luxembourg          | 3         | 0.51%   |
| Eugene              | 3         | 0.51%   |
| Chennai             | 3         | 0.51%   |
| Alexandria          | 3         | 0.51%   |
| Zurich              | 2         | 0.34%   |
| Visalia             | 2         | 0.34%   |
| Villa del Rio       | 2         | 0.34%   |
| Uherské Hradiště | 2         | 0.34%   |
| Tokyo               | 2         | 0.34%   |
| Tangier             | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 117       | 155    | 14.9%   |
| WDC                         | 112       | 144    | 14.27%  |
| Seagate                     | 91        | 116    | 11.59%  |
| Toshiba                     | 78        | 85     | 9.94%   |
| Unknown                     | 44        | 46     | 5.61%   |
| Kingston                    | 43        | 46     | 5.48%   |
| SanDisk                     | 35        | 44     | 4.46%   |
| SK hynix                    | 27        | 32     | 3.44%   |
| Hitachi                     | 26        | 32     | 3.31%   |
| Micron Technology           | 23        | 23     | 2.93%   |
| Crucial                     | 21        | 26     | 2.68%   |
| HGST                        | 17        | 20     | 2.17%   |
| Intel                       | 16        | 33     | 2.04%   |
| A-DATA Technology           | 13        | 13     | 1.66%   |
| Apple                       | 10        | 10     | 1.27%   |
| China                       | 8         | 11     | 1.02%   |
| KIOXIA                      | 7         | 8      | 0.89%   |
| Team                        | 6         | 7      | 0.76%   |
| SPCC                        | 5         | 5      | 0.64%   |
| Silicon Motion              | 4         | 4      | 0.51%   |
| Phison                      | 4         | 4      | 0.51%   |
| LITEON                      | 4         | 4      | 0.51%   |
| YMTC                        | 3         | 3      | 0.38%   |
| PNY                         | 3         | 3      | 0.38%   |
| LITEONIT                    | 3         | 3      | 0.38%   |
| Kingston Technology Company | 3         | 4      | 0.38%   |
| KingFast                    | 3         | 4      | 0.38%   |
| JMicron Technology          | 3         | 3      | 0.38%   |
| Intenso                     | 3         | 4      | 0.38%   |
| Fujitsu                     | 3         | 3      | 0.38%   |
| Unknown                     | 3         | 3      | 0.38%   |
| Lexar                       | 2         | 2      | 0.25%   |
| HUAWEI                      | 2         | 2      | 0.25%   |
| GOODRAM                     | 2         | 2      | 0.25%   |
| Fanxiang                    | 2         | 2      | 0.25%   |
| Corsair                     | 2         | 3      | 0.25%   |
| BR                          | 2         | 2      | 0.25%   |
| Apacer                      | 2         | 3      | 0.25%   |
| Zheino                      | 1         | 1      | 0.13%   |
| Wdxsky                      | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB               | 10        | 1.17%   |
| Samsung SSD 860 EVO 500GB            | 9         | 1.05%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 0.93%   |
| Unknown SD/MMC/MS PRO 256GB          | 7         | 0.82%   |
| Toshiba MQ01ABF050 500GB             | 7         | 0.82%   |
| Toshiba MQ01ABD100 1TB               | 7         | 0.82%   |
| Toshiba DT01ACA200 2TB               | 6         | 0.7%    |
| Unknown MMC Card  32GB               | 5         | 0.58%   |
| Toshiba MQ01ABD075 752GB             | 5         | 0.58%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 5         | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.58%   |
| Seagate Expansion 1TB                | 5         | 0.58%   |
| Samsung SSD 980 1TB                  | 5         | 0.58%   |
| Samsung SSD 850 EVO 250GB            | 5         | 0.58%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 0.58%   |
| Kingston NVMe SSD Drive 512GB        | 5         | 0.58%   |
| HGST HTS721010A9E630 1TB             | 5         | 0.58%   |
| HGST HTS541010A9E680 1TB             | 5         | 0.58%   |
| Unknown MMC Card  64GB               | 4         | 0.47%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 0.47%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 0.47%   |
| Seagate ST31000528AS 1TB             | 4         | 0.47%   |
| SanDisk SSD PLUS 1000GB              | 4         | 0.47%   |
| SanDisk NVMe SSD Drive 1TB           | 4         | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 0.47%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 0.47%   |
| Intel HBRPEKNX0202AH 512GB           | 4         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.35%   |
| WDC WD5000AADS-00S9B0 500GB          | 3         | 0.35%   |
| WDC WD10SPZX-75Z10T2 1TB             | 3         | 0.35%   |
| Toshiba KXG6AZNV256G 256GB           | 3         | 0.35%   |
| Toshiba DT01ACA050 500GB             | 3         | 0.35%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 3         | 0.35%   |
| Seagate ST9250315AS 250GB            | 3         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.35%   |
| Seagate ST250DM000-1BD141 250GB      | 3         | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.35%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 115    | 29.9%   |
| WDC                 | 79        | 103    | 26.25%  |
| Toshiba             | 63        | 68     | 20.93%  |
| Hitachi             | 26        | 32     | 8.64%   |
| HGST                | 17        | 20     | 5.65%   |
| Samsung Electronics | 12        | 14     | 3.99%   |
| Unknown             | 7         | 8      | 2.33%   |
| JMicron Technology  | 3         | 3      | 1%      |
| TO Exter            | 1         | 1      | 0.33%   |
| Fujitsu             | 1         | 1      | 0.33%   |
| CLOVER              | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 62     | 19.64%  |
| Kingston            | 26        | 28     | 11.61%  |
| SanDisk             | 19        | 21     | 8.48%   |
| WDC                 | 17        | 19     | 7.59%   |
| Crucial             | 17        | 22     | 7.59%   |
| China               | 8         | 11     | 3.57%   |
| Apple               | 7         | 7      | 3.13%   |
| Toshiba             | 5         | 6      | 2.23%   |
| Micron Technology   | 5         | 5      | 2.23%   |
| A-DATA Technology   | 5         | 5      | 2.23%   |
| Team                | 4         | 5      | 1.79%   |
| LITEON              | 4         | 4      | 1.79%   |
| SPCC                | 3         | 3      | 1.34%   |
| SK hynix            | 3         | 3      | 1.34%   |
| PNY                 | 3         | 3      | 1.34%   |
| LITEONIT            | 3         | 3      | 1.34%   |
| KingFast            | 3         | 3      | 1.34%   |
| Intenso             | 3         | 4      | 1.34%   |
| Unknown             | 2         | 2      | 0.89%   |
| Intel               | 2         | 2      | 0.89%   |
| GOODRAM             | 2         | 2      | 0.89%   |
| Fujitsu             | 2         | 2      | 0.89%   |
| Fanxiang            | 2         | 2      | 0.89%   |
| Corsair             | 2         | 3      | 0.89%   |
| BR                  | 2         | 2      | 0.89%   |
| Apacer              | 2         | 3      | 0.89%   |
| Unknown             | 2         | 2      | 0.89%   |
| Zheino              | 1         | 1      | 0.45%   |
| Wdxsky              | 1         | 1      | 0.45%   |
| WALRAM              | 1         | 1      | 0.45%   |
| W800SH              | 1         | 1      | 0.45%   |
| TSA 256G            | 1         | 1      | 0.45%   |
| Transcend           | 1         | 1      | 0.45%   |
| Teclast             | 1         | 1      | 0.45%   |
| Seagate             | 1         | 1      | 0.45%   |
| SCY                 | 1         | 1      | 0.45%   |
| S3+                 | 1         | 1      | 0.45%   |
| RZX                 | 1         | 1      | 0.45%   |
| PNY USB             | 1         | 1      | 0.45%   |
| Plextor             | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 256       | 367    | 36.21%  |
| NVMe    | 210       | 277    | 29.7%   |
| SSD     | 202       | 262    | 28.57%  |
| MMC     | 33        | 37     | 4.67%   |
| Unknown | 6         | 6      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 378       | 595    | 57.45%  |
| NVMe | 210       | 276    | 31.91%  |
| SAS  | 37        | 41     | 5.62%   |
| MMC  | 33        | 37     | 5.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 272       | 389    | 57.63%  |
| 0.51-1.0   | 156       | 187    | 33.05%  |
| 1.01-2.0   | 32        | 38     | 6.78%   |
| 3.01-4.0   | 6         | 7      | 1.27%   |
| 2.01-3.0   | 4         | 6      | 0.85%   |
| 4.01-10.0  | 2         | 2      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 137       | 23.66%  |
| 101-250        | 114       | 19.69%  |
| 501-1000       | 108       | 18.65%  |
| 1001-2000      | 68        | 11.74%  |
| Unknown        | 53        | 9.15%   |
| 51-100         | 36        | 6.22%   |
| 21-50          | 19        | 3.28%   |
| 1-20           | 19        | 3.28%   |
| More than 3000 | 15        | 2.59%   |
| 2001-3000      | 10        | 1.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 181       | 30.63%  |
| 51-100         | 105       | 17.77%  |
| 1-20           | 89        | 15.06%  |
| 101-250        | 81        | 13.71%  |
| Unknown        | 53        | 8.97%   |
| 251-500        | 46        | 7.78%   |
| 501-1000       | 22        | 3.72%   |
| 1001-2000      | 8         | 1.35%   |
| More than 3000 | 3         | 0.51%   |
| 0              | 2         | 0.34%   |
| 2001-3000      | 1         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB    | 3         | 3      | 3.75%   |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 2.5%    |
| SanDisk SD6SF1M128G1022I 128GB SSD   | 2         | 3      | 2.5%    |
| LITEON CV8-8E128-HP 128GB SSD        | 2         | 2      | 2.5%    |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 1      | 1.25%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 1      | 1.25%   |
| WDC WD3200BPVT-00JJ5T0 320GB         | 1         | 1      | 1.25%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1      | 1.25%   |
| WDC WD3200AVJS-63B6A0 320GB          | 1         | 1      | 1.25%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 1      | 1.25%   |
| WDC WD2003FZEX-00Z4SA0 2TB           | 1         | 1      | 1.25%   |
| WDC WD10JUCX-63WPNY0 1TB             | 1         | 1      | 1.25%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1      | 1.25%   |
| WDC WD10EADS-22M2B0 1TB              | 1         | 1      | 1.25%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.25%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 1.25%   |
| Toshiba MK5059GSXP 500GB             | 1         | 1      | 1.25%   |
| Toshiba MK3265GSXF 320GB             | 1         | 1      | 1.25%   |
| Toshiba MK3261GSYN 320GB             | 1         | 1      | 1.25%   |
| Toshiba DT01ACA050 500GB             | 1         | 1      | 1.25%   |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1      | 1.25%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.25%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.25%   |
| Seagate ST940210AS 40GB              | 1         | 1      | 1.25%   |
| Seagate ST9250410AS 250GB            | 1         | 1      | 1.25%   |
| Seagate ST500NM0011 500GB            | 1         | 1      | 1.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1      | 1.25%   |
| Seagate ST380215AS 80GB              | 1         | 1      | 1.25%   |
| Seagate ST3802110A 80GB              | 1         | 1      | 1.25%   |
| Seagate ST3500413AS 500GB            | 1         | 1      | 1.25%   |
| Seagate ST3320418AS 320GB            | 1         | 1      | 1.25%   |
| Seagate ST3250824AS 250GB            | 1         | 1      | 1.25%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 1      | 1.25%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1         | 1      | 1.25%   |
| Seagate ST3160215AS 160GB            | 1         | 1      | 1.25%   |
| Seagate ST31000528AS 1TB             | 1         | 1      | 1.25%   |
| Seagate ST250DM000-1BD141 250GB      | 1         | 1      | 1.25%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1      | 1.25%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 2      | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 20     | 20.78%  |
| WDC                 | 10        | 10     | 12.99%  |
| Samsung Electronics | 9         | 10     | 11.69%  |
| Toshiba             | 8         | 8      | 10.39%  |
| SanDisk             | 7         | 8      | 9.09%   |
| Hitachi             | 7         | 7      | 9.09%   |
| HGST                | 3         | 3      | 3.9%    |
| A-DATA Technology   | 3         | 3      | 3.9%    |
| LITEON              | 2         | 2      | 2.6%    |
| SPCC                | 1         | 1      | 1.3%    |
| SK hynix            | 1         | 1      | 1.3%    |
| Plextor             | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| Kingston            | 1         | 1      | 1.3%    |
| Intenso             | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| Hewlett-Packard     | 1         | 1      | 1.3%    |
| Fujitsu             | 1         | 1      | 1.3%    |
| Crucial             | 1         | 1      | 1.3%    |
| CLOVER              | 1         | 1      | 1.3%    |
| Unknown             | 1         | 1      | 1.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 20     | 30.19%  |
| WDC                 | 10        | 10     | 18.87%  |
| Toshiba             | 8         | 8      | 15.09%  |
| Samsung Electronics | 7         | 7      | 13.21%  |
| Hitachi             | 7         | 7      | 13.21%  |
| HGST                | 3         | 3      | 5.66%   |
| Fujitsu             | 1         | 1      | 1.89%   |
| CLOVER              | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 57     | 66.2%   |
| SSD  | 19        | 21     | 26.76%  |
| NVMe | 5         | 5      | 7.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 50%     |
| Intenso SSD SATAIII 1024GB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Intenso | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 304       | 414    | 47.65%  |
| Detected | 266       | 450    | 41.69%  |
| Malfunc  | 66        | 83     | 10.34%  |
| Failed   | 2         | 2      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 376       | 53.87%  |
| AMD                            | 87        | 12.46%  |
| Samsung Electronics            | 69        | 9.89%   |
| SanDisk                        | 34        | 4.87%   |
| SK hynix                       | 24        | 3.44%   |
| Kingston Technology Company    | 20        | 2.87%   |
| Micron Technology              | 18        | 2.58%   |
| Toshiba America Info Systems   | 10        | 1.43%   |
| Nvidia                         | 8         | 1.15%   |
| Silicon Motion                 | 7         | 1%      |
| KIOXIA                         | 7         | 1%      |
| ASMedia Technology             | 6         | 0.86%   |
| ADATA Technology               | 6         | 0.86%   |
| Phison Electronics             | 5         | 0.72%   |
| Micron/Crucial Technology      | 5         | 0.72%   |
| JMicron Technology             | 4         | 0.57%   |
| Yangtze Memory Technologies    | 3         | 0.43%   |
| Realtek Semiconductor          | 3         | 0.43%   |
| Marvell Technology Group       | 2         | 0.29%   |
| VIA Technologies               | 1         | 0.14%   |
| Solidigm                       | 1         | 0.14%   |
| Solid State Storage Technology | 1         | 0.14%   |
| Apple                          | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63        | 7.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 42        | 5.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 37        | 4.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 28        | 3.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26        | 3.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 25        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 23        | 2.9%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 17        | 2.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 1.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 13        | 1.64%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 13        | 1.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 13        | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 1.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 12        | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8         | 1.01%   |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 8         | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 7         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 0.88%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 7         | 0.88%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 7         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 7         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7         | 0.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 0.88%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 6         | 0.76%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 6         | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 6         | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 6         | 0.76%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                      | 6         | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6         | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 6         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 0.76%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 374       | 52.38%  |
| NVMe | 210       | 29.41%  |
| RAID | 70        | 9.8%    |
| IDE  | 60        | 8.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 451       | 80.25%  |
| AMD    | 109       | 19.4%   |
| ARM    | 2         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 2.31%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 1.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 1.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 1.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.42%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.07%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.89%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.89%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 0.89%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 0.89%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.89%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.89%   |
| Intel 12th Gen Core i7-1255U                  | 5         | 0.89%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 0.89%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.89%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.71%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 4         | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.71%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.71%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 0.71%   |
| Intel 12th Gen Core i5-12500H                 | 4         | 0.71%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.71%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 0.71%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.71%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.71%   |
| AMD FX-8350 Eight-Core Processor              | 4         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 3         | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.53%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3         | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 134       | 23.84%  |
| Intel Core i7           | 108       | 19.22%  |
| Other                   | 91        | 16.19%  |
| Intel Core i3           | 47        | 8.36%   |
| AMD Ryzen 7             | 26        | 4.63%   |
| AMD Ryzen 5             | 25        | 4.45%   |
| Intel Celeron           | 23        | 4.09%   |
| Intel Core 2 Duo        | 15        | 2.67%   |
| AMD A6                  | 10        | 1.78%   |
| AMD FX                  | 9         | 1.6%    |
| Intel Pentium           | 8         | 1.42%   |
| Intel Pentium Dual-Core | 6         | 1.07%   |
| Intel Xeon              | 5         | 0.89%   |
| AMD Ryzen 3             | 5         | 0.89%   |
| AMD A4                  | 5         | 0.89%   |
| Intel Core 2            | 4         | 0.71%   |
| Intel Pentium Silver    | 3         | 0.53%   |
| Intel Atom              | 3         | 0.53%   |
| AMD Ryzen 9             | 3         | 0.53%   |
| AMD E1                  | 3         | 0.53%   |
| Intel Core i9           | 2         | 0.36%   |
| Intel Core 2 Quad       | 2         | 0.36%   |
| AMD Ryzen Threadripper  | 2         | 0.36%   |
| AMD Phenom II X4        | 2         | 0.36%   |
| AMD Athlon II X2        | 2         | 0.36%   |
| AMD A8                  | 2         | 0.36%   |
| AMD A10                 | 2         | 0.36%   |
| Intel Pentium Dual      | 1         | 0.18%   |
| Intel Genuine           | 1         | 0.18%   |
| Intel Core m5           | 1         | 0.18%   |
| Intel Core M            | 1         | 0.18%   |
| Intel Core 2 Extreme    | 1         | 0.18%   |
| AMD Sempron             | 1         | 0.18%   |
| AMD Ryzen 5 PRO         | 1         | 0.18%   |
| AMD Phenom              | 1         | 0.18%   |
| AMD E2                  | 1         | 0.18%   |
| AMD E                   | 1         | 0.18%   |
| AMD C-50                | 1         | 0.18%   |
| AMD Athlon X2           | 1         | 0.18%   |
| AMD Athlon 64 X2        | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 235       | 41.81%  |
| 4      | 187       | 33.27%  |
| 6      | 49        | 8.72%   |
| 8      | 34        | 6.05%   |
| 10     | 18        | 3.2%    |
| 12     | 16        | 2.85%   |
| 14     | 9         | 1.6%    |
| 1      | 7         | 1.25%   |
| 16     | 3         | 0.53%   |
| 3      | 3         | 0.53%   |
| 24     | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 561       | 99.82%  |
| 2      | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 386       | 68.68%  |
| 1      | 175       | 31.14%  |
| 8      | 1         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 557       | 99.11%  |
| Unknown        | 5         | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 252       | 43.6%   |
| 0x206a7    | 29        | 5.02%   |
| 0x806c1    | 22        | 3.81%   |
| 0x306a9    | 21        | 3.63%   |
| 0x906a3    | 19        | 3.29%   |
| 0x806ec    | 17        | 2.94%   |
| 0x406e3    | 15        | 2.6%    |
| 0xa0652    | 11        | 1.9%    |
| 0x906ea    | 10        | 1.73%   |
| 0x906a4    | 10        | 1.73%   |
| 0x806e9    | 10        | 1.73%   |
| 0x806ea    | 9         | 1.56%   |
| 0x306c3    | 9         | 1.56%   |
| 0x906e9    | 8         | 1.38%   |
| 0x706a8    | 7         | 1.21%   |
| 0x40651    | 7         | 1.21%   |
| 0x1067a    | 7         | 1.21%   |
| 0x0a50000c | 7         | 1.21%   |
| 0x08108109 | 7         | 1.21%   |
| 0x806d1    | 6         | 1.04%   |
| 0x706e5    | 5         | 0.87%   |
| 0x6f6      | 4         | 0.69%   |
| 0x406c4    | 4         | 0.69%   |
| 0x306d4    | 4         | 0.69%   |
| 0x08608103 | 4         | 0.69%   |
| 0x08600106 | 4         | 0.69%   |
| 0x06006705 | 4         | 0.69%   |
| 0x06000852 | 4         | 0.69%   |
| 0x90672    | 3         | 0.52%   |
| 0x07030105 | 3         | 0.52%   |
| 0x03000027 | 3         | 0.52%   |
| 0x010000c8 | 3         | 0.52%   |
| 0xb06a2    | 2         | 0.35%   |
| 0xb0671    | 2         | 0.35%   |
| 0x906ed    | 2         | 0.35%   |
| 0x806eb    | 2         | 0.35%   |
| 0x806c2    | 2         | 0.35%   |
| 0x706a1    | 2         | 0.35%   |
| 0x6fd      | 2         | 0.35%   |
| 0x506c9    | 2         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 94        | 16.73%  |
| SandyBridge      | 50        | 8.9%    |
| Haswell          | 41        | 7.3%    |
| IvyBridge        | 39        | 6.94%   |
| Alderlake Hybrid | 39        | 6.94%   |
| TigerLake        | 33        | 5.87%   |
| Skylake          | 32        | 5.69%   |
| Penryn           | 22        | 3.91%   |
| Unknown          | 19        | 3.38%   |
| Zen+             | 16        | 2.85%   |
| Zen 3            | 16        | 2.85%   |
| CometLake        | 16        | 2.85%   |
| Broadwell        | 15        | 2.67%   |
| Zen 2            | 13        | 2.31%   |
| Piledriver       | 13        | 2.31%   |
| IceLake          | 13        | 2.31%   |
| Silvermont       | 12        | 2.14%   |
| Goldmont plus    | 12        | 2.14%   |
| Core             | 11        | 1.96%   |
| Zen              | 9         | 1.6%    |
| Excavator        | 9         | 1.6%    |
| Westmere         | 7         | 1.25%   |
| K10              | 7         | 1.25%   |
| Nehalem          | 4         | 0.71%   |
| K10 Llano        | 4         | 0.71%   |
| Jaguar           | 4         | 0.71%   |
| Puma             | 3         | 0.53%   |
| Goldmont         | 3         | 0.53%   |
| K8 Hammer        | 2         | 0.36%   |
| Bobcat           | 2         | 0.36%   |
| Steamroller      | 1         | 0.18%   |
| K8 & K10 hybrid  | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 394       | 55.18%  |
| Nvidia | 186       | 26.05%  |
| AMD    | 134       | 18.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 42        | 5.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 29        | 4.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 29        | 4.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 3.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 2.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 2.63%   |
| Intel UHD Graphics 620                                                                   | 16        | 2.22%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 16        | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 1.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.8%    |
| Intel HD Graphics 620                                                                    | 12        | 1.66%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 1.66%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 10        | 1.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.25%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 1.25%   |
| Intel HD Graphics 630                                                                    | 9         | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.25%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 9         | 1.25%   |
| AMD Lucienne                                                                             | 8         | 1.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.11%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 0.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 0.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.69%   |
| Intel HD Graphics 530                                                                    | 5         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 253       | 44.78%  |
| Intel + Nvidia | 108       | 19.12%  |
| 1 x AMD        | 98        | 17.35%  |
| 1 x Nvidia     | 66        | 11.68%  |
| Intel + AMD    | 20        | 3.54%   |
| AMD + Nvidia   | 13        | 2.3%    |
| Other          | 3         | 0.53%   |
| 2 x AMD        | 3         | 0.53%   |
| 2 x Nvidia     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 489       | 86.7%   |
| Proprietary | 60        | 10.64%  |
| Unknown     | 15        | 2.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 419       | 73.64%  |
| 1.01-2.0   | 35        | 6.15%   |
| 3.01-4.0   | 30        | 5.27%   |
| 0.01-0.5   | 29        | 5.1%    |
| 0.51-1.0   | 26        | 4.57%   |
| 7.01-8.0   | 15        | 2.64%   |
| 5.01-6.0   | 10        | 1.76%   |
| 8.01-16.0  | 3         | 0.53%   |
| 2.01-3.0   | 2         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 97        | 15.62%  |
| BOE                     | 77        | 12.4%   |
| LG Display              | 75        | 12.08%  |
| Samsung Electronics     | 66        | 10.63%  |
| Chimei Innolux          | 63        | 10.14%  |
| Dell                    | 25        | 4.03%   |
| Apple                   | 17        | 2.74%   |
| Acer                    | 16        | 2.58%   |
| Sharp                   | 15        | 2.42%   |
| Hewlett-Packard         | 14        | 2.25%   |
| Goldstar                | 12        | 1.93%   |
| Chi Mei Optoelectronics | 11        | 1.77%   |
| BenQ                    | 11        | 1.77%   |
| Ancor Communications    | 10        | 1.61%   |
| PANDA                   | 8         | 1.29%   |
| Unknown                 | 7         | 1.13%   |
| Philips                 | 7         | 1.13%   |
| InfoVision              | 7         | 1.13%   |
| AOC                     | 7         | 1.13%   |
| Lenovo                  | 5         | 0.81%   |
| ViewSonic               | 4         | 0.64%   |
| Sony                    | 4         | 0.64%   |
| Panasonic               | 4         | 0.64%   |
| CSO                     | 4         | 0.64%   |
| Vizio                   | 3         | 0.48%   |
| Toshiba                 | 3         | 0.48%   |
| NEC Computers           | 3         | 0.48%   |
| Iiyama                  | 3         | 0.48%   |
| Eizo                    | 3         | 0.48%   |
| AUS                     | 3         | 0.48%   |
| ___                     | 2         | 0.32%   |
| STD                     | 2         | 0.32%   |
| Sceptre Tech            | 2         | 0.32%   |
| Insignia                | 2         | 0.32%   |
| ASUSTek Computer        | 2         | 0.32%   |
| VOR                     | 1         | 0.16%   |
| VIZ                     | 1         | 0.16%   |
| Unknown (AAA)           | 1         | 0.16%   |
| STA                     | 1         | 0.16%   |
| SGT                     | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.79%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.63%   |
| Sony TV SNYF301 1920x1080                                             | 3         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 3         | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 0.47%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.47%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.47%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 0.47%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.47%   |
| ___ LCDTV16 ___9000 1360x768                                          | 2         | 0.32%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2         | 0.32%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2         | 0.32%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.32%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 600x340mm 27.2-inch              | 2         | 0.32%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 2         | 0.32%   |
| Panasonic TV MEIA08F 1920x540                                         | 2         | 0.32%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2         | 0.32%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 2         | 0.32%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 2         | 0.32%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 276       | 46.86%  |
| 1366x768 (WXGA)    | 140       | 23.77%  |
| 3840x2160 (4K)     | 23        | 3.9%    |
| 1600x900 (HD+)     | 22        | 3.74%   |
| 1920x1200 (WUXGA)  | 16        | 2.72%   |
| 1680x1050 (WSXGA+) | 16        | 2.72%   |
| 1440x900 (WXGA+)   | 12        | 2.04%   |
| 1280x800 (WXGA)    | 12        | 2.04%   |
| 1280x1024 (SXGA)   | 12        | 2.04%   |
| 2560x1440 (QHD)    | 9         | 1.53%   |
| 1360x768           | 7         | 1.19%   |
| 2560x1600          | 5         | 0.85%   |
| 2880x1800          | 4         | 0.68%   |
| 2560x1080          | 4         | 0.68%   |
| 2160x1440          | 4         | 0.68%   |
| 1920x540           | 4         | 0.68%   |
| Unknown            | 4         | 0.68%   |
| 3440x1440          | 3         | 0.51%   |
| 3840x2400          | 2         | 0.34%   |
| 3840x1080          | 2         | 0.34%   |
| 3200x1080          | 2         | 0.34%   |
| 1280x720 (HD)      | 2         | 0.34%   |
| 1024x768 (XGA)     | 2         | 0.34%   |
| 5200x1080          | 1         | 0.17%   |
| 3200x1800 (QHD+)   | 1         | 0.17%   |
| 2496x1664          | 1         | 0.17%   |
| 2240x1400          | 1         | 0.17%   |
| 1920x515           | 1         | 0.17%   |
| 1600x1200          | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 207       | 33.44%  |
| 14      | 64        | 10.34%  |
| 13      | 60        | 9.69%   |
| 17      | 42        | 6.79%   |
| 24      | 36        | 5.82%   |
| 27      | 26        | 4.2%    |
| Unknown | 24        | 3.88%   |
| 23      | 21        | 3.39%   |
| 12      | 17        | 2.75%   |
| 21      | 15        | 2.42%   |
| 31      | 13        | 2.1%    |
| 22      | 13        | 2.1%    |
| 11      | 12        | 1.94%   |
| 19      | 10        | 1.62%   |
| 16      | 9         | 1.45%   |
| 72      | 6         | 0.97%   |
| 40      | 6         | 0.97%   |
| 32      | 5         | 0.81%   |
| 18      | 5         | 0.81%   |
| 34      | 4         | 0.65%   |
| 20      | 4         | 0.65%   |
| 84      | 3         | 0.48%   |
| 54      | 3         | 0.48%   |
| 48      | 2         | 0.32%   |
| 47      | 2         | 0.32%   |
| 69      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 46      | 1         | 0.16%   |
| 43      | 1         | 0.16%   |
| 42      | 1         | 0.16%   |
| 41      | 1         | 0.16%   |
| 36      | 1         | 0.16%   |
| 29      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 25      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 313       | 51.31%  |
| 501-600     | 77        | 12.62%  |
| 201-300     | 56        | 9.18%   |
| 351-400     | 47        | 7.7%    |
| 401-500     | 40        | 6.56%   |
| Unknown     | 24        | 3.93%   |
| 601-700     | 15        | 2.46%   |
| 701-800     | 10        | 1.64%   |
| 1501-2000   | 10        | 1.64%   |
| 1001-1500   | 9         | 1.48%   |
| 801-900     | 6         | 0.98%   |
| 901-1000    | 3         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 450       | 80.36%  |
| 16/10   | 64        | 11.43%  |
| Unknown | 16        | 2.86%   |
| 5/4     | 9         | 1.61%   |
| 4/3     | 6         | 1.07%   |
| 21/9    | 5         | 0.89%   |
| 32/9    | 4         | 0.71%   |
| 3/2     | 4         | 0.71%   |
| 6/5     | 1         | 0.18%   |
| 3.73    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 209       | 33.87%  |
| 81-90          | 100       | 16.21%  |
| 201-250        | 69        | 11.18%  |
| 121-130        | 33        | 5.35%   |
| 301-350        | 28        | 4.54%   |
| 71-80          | 25        | 4.05%   |
| Unknown        | 24        | 3.89%   |
| 351-500        | 22        | 3.57%   |
| 151-200        | 18        | 2.92%   |
| 61-70          | 16        | 2.59%   |
| More than 1000 | 15        | 2.43%   |
| 501-1000       | 13        | 2.11%   |
| 51-60          | 12        | 1.94%   |
| 251-300        | 12        | 1.94%   |
| 141-150        | 11        | 1.78%   |
| 111-120        | 7         | 1.13%   |
| 131-140        | 3         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 215       | 35.83%  |
| 101-120       | 145       | 24.17%  |
| 51-100        | 144       | 24%     |
| 161-240       | 40        | 6.67%   |
| Unknown       | 24        | 4%      |
| 1-50          | 19        | 3.17%   |
| More than 240 | 13        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 461       | 80.31%  |
| 2     | 87        | 15.16%  |
| 0     | 15        | 2.61%   |
| 3     | 11        | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 315       | 33.19%  |
| Intel                                  | 302       | 31.82%  |
| Qualcomm Atheros                       | 92        | 9.69%   |
| Broadcom                               | 42        | 4.43%   |
| Ralink Technology                      | 22        | 2.32%   |
| MediaTek                               | 19        | 2%      |
| TP-Link                                | 18        | 1.9%    |
| Samsung Electronics                    | 15        | 1.58%   |
| Broadcom Limited                       | 14        | 1.48%   |
| Xiaomi                                 | 9         | 0.95%   |
| Qualcomm Atheros Communications        | 9         | 0.95%   |
| Ralink                                 | 7         | 0.74%   |
| Nvidia                                 | 7         | 0.74%   |
| NetGear                                | 7         | 0.74%   |
| Huawei Technologies                    | 6         | 0.63%   |
| ASUSTek Computer                       | 5         | 0.53%   |
| ASIX Electronics                       | 5         | 0.53%   |
| Qualcomm                               | 4         | 0.42%   |
| OPPO Electronics                       | 4         | 0.42%   |
| Microsoft                              | 4         | 0.42%   |
| Marvell Technology Group               | 4         | 0.42%   |
| Mercucys                               | 3         | 0.32%   |
| Lenovo                                 | 3         | 0.32%   |
| D-Link System                          | 3         | 0.32%   |
| vivo                                   | 2         | 0.21%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.21%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.21%   |
| Linksys                                | 2         | 0.21%   |
| JMicron Technology                     | 2         | 0.21%   |
| Google                                 | 2         | 0.21%   |
| Ericsson Business Mobile Networks      | 2         | 0.21%   |
| D-Link                                 | 2         | 0.21%   |
| Apple                                  | 2         | 0.21%   |
| ZyXEL Communications                   | 1         | 0.11%   |
| STMicroelectronics                     | 1         | 0.11%   |
| Sagem                                  | 1         | 0.11%   |
| Microchip Technology                   | 1         | 0.11%   |
| ICS Advent                             | 1         | 0.11%   |
| Gemtek                                 | 1         | 0.11%   |
| Fibocom                                | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 186       | 16.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 30        | 2.68%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 29        | 2.59%   |
| Intel Wi-Fi 6 AX201                                                    | 23        | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 19        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 18        | 1.61%   |
| Intel Wireless 8265 / 8275                                             | 17        | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 1.25%   |
| Intel Wi-Fi 6 AX200                                                    | 14        | 1.25%   |
| Intel Wireless 7265                                                    | 13        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 13        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 12        | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 10        | 0.89%   |
| Intel Wireless 7260                                                    | 10        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 9         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                        | 9         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.8%    |
| Intel Wireless 8260                                                    | 9         | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 8         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 8         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 8         | 0.71%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.71%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 7         | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 7         | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7         | 0.62%   |
| Realtek 802.11ac NIC                                                   | 7         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 0.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 6         | 0.54%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 6         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 260       | 43.55%  |
| Realtek Semiconductor             | 112       | 18.76%  |
| Qualcomm Atheros                  | 71        | 11.89%  |
| Broadcom                          | 36        | 6.03%   |
| Ralink Technology                 | 22        | 3.69%   |
| TP-Link                           | 18        | 3.02%   |
| MediaTek                          | 16        | 2.68%   |
| Broadcom Limited                  | 11        | 1.84%   |
| Qualcomm Atheros Communications   | 9         | 1.51%   |
| Ralink                            | 7         | 1.17%   |
| NetGear                           | 7         | 1.17%   |
| ASUSTek Computer                  | 5         | 0.84%   |
| Microsoft                         | 4         | 0.67%   |
| Mercucys                          | 3         | 0.5%    |
| Marvell Technology Group          | 3         | 0.5%    |
| Linksys                           | 2         | 0.34%   |
| D-Link                            | 2         | 0.34%   |
| ZyXEL Communications              | 1         | 0.17%   |
| Sagem                             | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| Gemtek                            | 1         | 0.17%   |
| Fibocom                           | 1         | 0.17%   |
| Ericsson Business Mobile Networks | 1         | 0.17%   |
| Dell                              | 1         | 0.17%   |
| D-Link System                     | 1         | 0.17%   |
| Belkin Components                 | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 29        | 4.83%   |
| Intel Wi-Fi 6 AX201                                            | 23        | 3.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 19        | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 3%      |
| Intel Wireless 8265 / 8275                                     | 17        | 2.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.33%   |
| Intel Wi-Fi 6 AX200                                            | 14        | 2.33%   |
| Intel Wireless 7265                                            | 13        | 2.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 1.66%   |
| Intel Wireless 7260                                            | 10        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 9         | 1.5%    |
| Qualcomm Atheros AR9271 802.11n                                | 9         | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 1.5%    |
| Intel Wireless 8260                                            | 9         | 1.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 8         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8         | 1.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 1.16%   |
| Realtek 802.11ac NIC                                           | 7         | 1.16%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 6         | 1%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 6         | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1%      |
| Intel Wireless 3165                                            | 6         | 1%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 6         | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1%      |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1%      |
| Ralink MT7601U Wireless Adapter                                | 5         | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 0.83%   |
| Intel Wireless 3160                                            | 5         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 267       | 53.29%  |
| Intel                                  | 120       | 23.95%  |
| Qualcomm Atheros                       | 34        | 6.79%   |
| Samsung Electronics                    | 15        | 2.99%   |
| Broadcom                               | 12        | 2.4%    |
| Xiaomi                                 | 9         | 1.8%    |
| Nvidia                                 | 7         | 1.4%    |
| ASIX Electronics                       | 5         | 1%      |
| OPPO Electronics                       | 4         | 0.8%    |
| Qualcomm                               | 3         | 0.6%    |
| MediaTek                               | 3         | 0.6%    |
| Lenovo                                 | 3         | 0.6%    |
| Broadcom Limited                       | 3         | 0.6%    |
| JMicron Technology                     | 2         | 0.4%    |
| Huawei Technologies                    | 2         | 0.4%    |
| Google                                 | 2         | 0.4%    |
| D-Link System                          | 2         | 0.4%    |
| Apple                                  | 2         | 0.4%    |
| vivo                                   | 1         | 0.2%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.2%    |
| Marvell Technology Group               | 1         | 0.2%    |
| ICS Advent                             | 1         | 0.2%    |
| DisplayLink                            | 1         | 0.2%    |
| Davicom Semiconductor                  | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 186       | 36.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 7.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 30        | 5.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 4.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 1.57%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 1.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 7         | 1.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 1.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 6         | 1.18%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.18%   |
| Intel Ethernet Connection (2) I219-V                                   | 6         | 1.18%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.98%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.98%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.79%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.59%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.59%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.59%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.59%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.59%   |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.59%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 3         | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.39%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 514       | 52.08%  |
| Ethernet | 461       | 46.71%  |
| Modem    | 7         | 0.71%   |
| Unknown  | 5         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 391       | 67.18%  |
| Ethernet | 189       | 32.47%  |
| Unknown  | 2         | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 323       | 57.17%  |
| 1     | 219       | 38.76%  |
| 0     | 12        | 2.12%   |
| 3     | 9         | 1.59%   |
| 5     | 1         | 0.18%   |
| 4     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 443       | 77.58%  |
| Yes     | 127       | 22.24%  |
| Unknown | 1         | 0.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 201       | 50.25%  |
| Realtek Semiconductor           | 38        | 9.5%    |
| Qualcomm Atheros Communications | 38        | 9.5%    |
| Broadcom                        | 20        | 5%      |
| IMC Networks                    | 17        | 4.25%   |
| Apple                           | 15        | 3.75%   |
| Lite-On Technology              | 13        | 3.25%   |
| Cambridge Silicon Radio         | 13        | 3.25%   |
| Foxconn / Hon Hai               | 12        | 3%      |
| MediaTek                        | 5         | 1.25%   |
| Dell                            | 5         | 1.25%   |
| ASUSTek Computer                | 5         | 1.25%   |
| Toshiba                         | 3         | 0.75%   |
| Marvell Semiconductor           | 3         | 0.75%   |
| TP-Link                         | 2         | 0.5%    |
| Realtek                         | 2         | 0.5%    |
| Ralink                          | 2         | 0.5%    |
| Dynex                           | 2         | 0.5%    |
| Logitech                        | 1         | 0.25%   |
| Hewlett-Packard                 | 1         | 0.25%   |
| Alps Electric                   | 1         | 0.25%   |
| Unknown                         | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 61        | 15.25%  |
| Intel AX201 Bluetooth                               | 57        | 14.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 8%      |
| Realtek Bluetooth Radio                             | 27        | 6.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 20        | 5%      |
| Intel Bluetooth Device                              | 19        | 4.75%   |
| Intel AX200 Bluetooth                               | 13        | 3.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 3.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 1.5%    |
| IMC Networks Wireless_Device                        | 6         | 1.5%    |
| IMC Networks Bluetooth Radio                        | 6         | 1.5%    |
| Apple Bluetooth Host Controller                     | 6         | 1.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.25%   |
| MediaTek Wireless_Device                            | 5         | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.25%   |
| IMC Networks Bluetooth Device                       | 5         | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.25%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.25%   |
| Dell DW375 Bluetooth Module                         | 4         | 1%      |
| Broadcom HP Portable SoftSailing                    | 4         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 1%      |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.75%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.75%   |
| Lite-On Wireless_Device                             | 3         | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.75%   |
| Intel AX210 Bluetooth                               | 3         | 0.75%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.75%   |
| TP-Link UB500 Adapter                               | 2         | 0.5%    |
| Realtek Bluetooth Radio                             | 2         | 0.5%    |
| Ralink RT3290 Bluetooth                             | 2         | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.5%    |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.5%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.5%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 441       | 59.76%  |
| Nvidia                   | 131       | 17.75%  |
| AMD                      | 130       | 17.62%  |
| C-Media Electronics      | 7         | 0.95%   |
| JMTek                    | 4         | 0.54%   |
| GN Netcom                | 3         | 0.41%   |
| Realtek Semiconductor    | 2         | 0.27%   |
| Logitech                 | 2         | 0.27%   |
| Generalplus Technology   | 2         | 0.27%   |
| Corsair                  | 2         | 0.27%   |
| Yamaha                   | 1         | 0.14%   |
| USB-MIC                  | 1         | 0.14%   |
| Tenx Technology          | 1         | 0.14%   |
| SteelSeries ApS          | 1         | 0.14%   |
| Samson Technologies      | 1         | 0.14%   |
| Razer USA                | 1         | 0.14%   |
| Micro Star International | 1         | 0.14%   |
| Lenovo                   | 1         | 0.14%   |
| Kingston Technology      | 1         | 0.14%   |
| GYROCOM C&C              | 1         | 0.14%   |
| Guillemot                | 1         | 0.14%   |
| Creative Labs            | 1         | 0.14%   |
| Conexant Systems         | 1         | 0.14%   |
| Apple                    | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 53        | 6.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 45        | 5.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 44        | 5.02%   |
| AMD Family 17h/19h HD Audio Controller                                     | 44        | 5.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 33        | 3.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 33        | 3.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 2.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 20        | 2.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 2.17%   |
| Intel 8 Series HD Audio Controller                                         | 19        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18        | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18        | 2.05%   |
| AMD FCH Azalia Controller                                                  | 18        | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.71%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 1.71%   |
| Nvidia GA106 High Definition Audio Controller                              | 14        | 1.6%    |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 1.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12        | 1.37%   |
| Nvidia Audio device                                                        | 12        | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 1.37%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 9         | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 0.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8         | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7         | 0.8%    |
| AMD High Definition Audio Controller                                       | 7         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 113       | 25.92%  |
| SK hynix            | 72        | 16.51%  |
| Micron Technology   | 64        | 14.68%  |
| Kingston            | 34        | 7.8%    |
| Crucial             | 29        | 6.65%   |
| Unknown             | 27        | 6.19%   |
| Corsair             | 16        | 3.67%   |
| Elpida              | 11        | 2.52%   |
| A-DATA Technology   | 10        | 2.29%   |
| Ramaxel Technology  | 9         | 2.06%   |
| Unknown (ABCD)      | 7         | 1.61%   |
| G.Skill             | 7         | 1.61%   |
| Team                | 6         | 1.38%   |
| Nanya Technology    | 6         | 1.38%   |
| Unknown             | 5         | 1.15%   |
| Smart               | 3         | 0.69%   |
| Transcend           | 2         | 0.46%   |
| PNY                 | 2         | 0.46%   |
| Unifosa             | 1         | 0.23%   |
| Timetec             | 1         | 0.23%   |
| Teikon              | 1         | 0.23%   |
| Silicon Power       | 1         | 0.23%   |
| Saikano             | 1         | 0.23%   |
| S                   | 1         | 0.23%   |
| Ramos Technology    | 1         | 0.23%   |
| Patriot             | 1         | 0.23%   |
| fef5                | 1         | 0.23%   |
| ChangXin Memory     | 1         | 0.23%   |
| Avant               | 1         | 0.23%   |
| Asgard              | 1         | 0.23%   |
| AMD                 | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 8         | 1.75%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 7         | 1.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 1.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 1.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 1.09%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.09%   |
| Unknown                                                             | 5         | 1.09%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.88%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.88%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 4         | 0.88%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 3         | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.66%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.66%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 3         | 0.66%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 3         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 2         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 2         | 0.44%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s                 | 2         | 0.44%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 2         | 0.44%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 2         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.44%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s    | 2         | 0.44%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 2         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 179       | 47.73%  |
| DDR3    | 118       | 31.47%  |
| LPDDR4  | 24        | 6.4%    |
| Unknown | 13        | 3.47%   |
| LPDDR3  | 12        | 3.2%    |
| DDR5    | 11        | 2.93%   |
| DDR2    | 8         | 2.13%   |
| LPDDR5  | 5         | 1.33%   |
| SDRAM   | 4         | 1.07%   |
| DDR     | 1         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 263       | 70.89%  |
| DIMM         | 68        | 18.33%  |
| Row Of Chips | 36        | 9.7%    |
| Unknown      | 3         | 0.81%   |
| Chip         | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 173       | 42.3%   |
| 4096  | 110       | 26.89%  |
| 16384 | 56        | 13.69%  |
| 2048  | 40        | 9.78%   |
| 32768 | 16        | 3.91%   |
| 1024  | 14        | 3.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 80        | 19.61%  |
| 1600    | 76        | 18.63%  |
| 2667    | 69        | 16.91%  |
| 2400    | 29        | 7.11%   |
| 1334    | 19        | 4.66%   |
| 1333    | 18        | 4.41%   |
| 2133    | 17        | 4.17%   |
| 4800    | 11        | 2.7%    |
| 3600    | 10        | 2.45%   |
| 1867    | 10        | 2.45%   |
| 4267    | 7         | 1.72%   |
| 1067    | 6         | 1.47%   |
| 6400    | 5         | 1.23%   |
| Unknown | 5         | 1.23%   |
| 1800    | 4         | 0.98%   |
| 1066    | 4         | 0.98%   |
| 667     | 4         | 0.98%   |
| 5600    | 3         | 0.74%   |
| 3733    | 3         | 0.74%   |
| 3266    | 3         | 0.74%   |
| 1866    | 3         | 0.74%   |
| 800     | 3         | 0.74%   |
| 3800    | 2         | 0.49%   |
| 8400    | 1         | 0.25%   |
| 6800    | 1         | 0.25%   |
| 4266    | 1         | 0.25%   |
| 3866    | 1         | 0.25%   |
| 3534    | 1         | 0.25%   |
| 3533    | 1         | 0.25%   |
| 3100    | 1         | 0.25%   |
| 3000    | 1         | 0.25%   |
| 2933    | 1         | 0.25%   |
| 2666    | 1         | 0.25%   |
| 2200    | 1         | 0.25%   |
| 2132    | 1         | 0.25%   |
| 2048    | 1         | 0.25%   |
| 1227    | 1         | 0.25%   |
| 975     | 1         | 0.25%   |
| 533     | 1         | 0.25%   |
| 400     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 33.33%  |
| Seiko Epson         | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Dymo-CoStar         | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Seiko Epson L120 Series      | 1         | 16.67%  |
| Samsung ML-2850 Series       | 1         | 16.67%  |
| HP OfficeJet Pro 7720 series | 1         | 16.67%  |
| HP Deskjet 2050 J510         | 1         | 16.67%  |
| Dymo-CoStar LabelWriter 450  | 1         | 16.67%  |
| Brother HL-1210W series      | 1         | 16.67%  |

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


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 94        | 23.56%  |
| IMC Networks                           | 42        | 10.53%  |
| Microdia                               | 34        | 8.52%   |
| Bison Electronics                      | 26        | 6.52%   |
| Realtek Semiconductor                  | 23        | 5.76%   |
| Quanta                                 | 23        | 5.76%   |
| Sunplus Innovation Technology          | 20        | 5.01%   |
| Apple                                  | 17        | 4.26%   |
| Acer                                   | 14        | 3.51%   |
| Syntek                                 | 11        | 2.76%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.76%   |
| Luxvisions Innotech Limited            | 10        | 2.51%   |
| Logitech                               | 7         | 1.75%   |
| Lite-On Technology                     | 7         | 1.75%   |
| Suyin                                  | 6         | 1.5%    |
| Ricoh                                  | 6         | 1.5%    |
| Silicon Motion                         | 5         | 1.25%   |
| Samsung Electronics                    | 5         | 1.25%   |
| USB Camera                             | 4         | 1%      |
| Sonix Technology                       | 4         | 1%      |
| Alcor Micro                            | 4         | 1%      |
| Microsoft                              | 3         | 0.75%   |
| Primax Electronics                     | 2         | 0.5%    |
| LG Electronics                         | 2         | 0.5%    |
| Importek                               | 2         | 0.5%    |
| Generalplus Technology                 | 2         | 0.5%    |
| Creative Technology                    | 2         | 0.5%    |
| USB Camera CS                          | 1         | 0.25%   |
| Tobii Technology AB                    | 1         | 0.25%   |
| Teslong Camera                         | 1         | 0.25%   |
| SunplusIT                              | 1         | 0.25%   |
| Razer USA                              | 1         | 0.25%   |
| Jieli Technology                       | 1         | 0.25%   |
| Goertek Electronics                    | 1         | 0.25%   |
| Genesys Logic                          | 1         | 0.25%   |
| AVerMedia Technologies                 | 1         | 0.25%   |
| ARC International                      | 1         | 0.25%   |
| ALi                                    | 1         | 0.25%   |
| 8SSC21K12273V1SR33X2817                | 1         | 0.25%   |
| 8SSC21D67422V1SR3AV5KW1                | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 20        | 4.98%   |
| Realtek Integrated_Webcam_HD                         | 12        | 2.99%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 12        | 2.99%   |
| IMC Networks Integrated Camera                       | 12        | 2.99%   |
| Bison Integrated Camera                              | 9         | 2.24%   |
| Syntek Integrated Camera                             | 8         | 1.99%   |
| Microdia Integrated_Webcam_HD                        | 8         | 1.99%   |
| Chicony HD User Facing                               | 7         | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 7         | 1.74%   |
| Quanta HD User Facing                                | 6         | 1.49%   |
| Chicony HP Truevision HD                             | 6         | 1.49%   |
| Chicony HD Webcam                                    | 6         | 1.49%   |
| Bison HD Webcam                                      | 6         | 1.49%   |
| Sunplus Integrated_Webcam_HD                         | 5         | 1.24%   |
| Samsung Galaxy series, misc. (MTP mode)              | 5         | 1.24%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 1.24%   |
| Chicony USB2.0 Camera                                | 5         | 1.24%   |
| Chicony HP HD Camera                                 | 5         | 1.24%   |
| Acer SunplusIT Integrated Camera                     | 5         | 1.24%   |
| USB Camera USB Camera                                | 4         | 1%      |
| Microdia Webcam Vitade AF                            | 4         | 1%      |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 1%      |
| Chicony EasyCamera                                   | 4         | 1%      |
| Apple Built-in iSight                                | 4         | 1%      |
| Acer HD Webcam                                       | 4         | 1%      |
| Quanta HP TrueVision HD Camera                       | 3         | 0.75%   |
| Quanta ACER HD User Facing                           | 3         | 0.75%   |
| Microdia PC Microscope camera                        | 3         | 0.75%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 3         | 0.75%   |
| Microdia Integrated Webcam HD                        | 3         | 0.75%   |
| Microdia Integrated Webcam                           | 3         | 0.75%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 0.75%   |
| IMC Networks HD Camera                               | 3         | 0.75%   |
| Chicony Integrated Camera (1280x720@30)              | 3         | 0.75%   |
| Bison Lenovo EasyCamera                              | 3         | 0.75%   |
| Apple FaceTime HD Camera                             | 3         | 0.75%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 0.75%   |
| Acer EasyCamera                                      | 3         | 0.75%   |
| Syntek Lenovo EasyCamera                             | 2         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 32        | 40.51%  |
| Validity Sensors           | 24        | 30.38%  |
| Shenzhen Goodix Technology | 9         | 11.39%  |
| Elan Microelectronics      | 5         | 6.33%   |
| Upek                       | 3         | 3.8%    |
| AuthenTec                  | 3         | 3.8%    |
| LighTuning Technology      | 2         | 2.53%   |
| Samsung Electronics        | 1         | 1.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 11.39%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 7.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 6.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 6.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.06%   |
| Synaptics UWP WBDI Device                                                  | 4         | 5.06%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.8%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 3.8%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 3.8%    |
| Synaptics UWP WBDI                                                         | 3         | 3.8%    |
| Elan ELAN:Fingerprint                                                      | 3         | 3.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.53%   |
| Validity Sensors VFS491                                                    | 2         | 2.53%   |
| Synaptics WBDI                                                             | 2         | 2.53%   |
| Synaptics  WBDI                                                            | 2         | 2.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.53%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.53%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.53%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 2.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.27%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.27%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.27%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.27%   |
| Samsung Fingerprint Device                                                 | 1         | 1.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.27%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 14        | 56%     |
| Alcor Micro      | 7         | 28%     |
| Upek             | 1         | 4%      |
| SCM Microsystems | 1         | 4%      |
| OmniKey          | 1         | 4%      |
| O2 Micro         | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 28%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 28%     |
| Broadcom 5880                                                                | 4         | 16%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4%      |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 4%      |
| OmniKey CardMan Smart@Link                                                   | 1         | 4%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 355       | 61.85%  |
| 1     | 176       | 30.66%  |
| 2     | 40        | 6.97%   |
| 3     | 3         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 80        | 31.37%  |
| Graphics card            | 49        | 19.22%  |
| Net/wireless             | 37        | 14.51%  |
| Chipcard                 | 23        | 9.02%   |
| Multimedia controller    | 20        | 7.84%   |
| Camera                   | 12        | 4.71%   |
| Net/ethernet             | 9         | 3.53%   |
| Storage                  | 6         | 2.35%   |
| Network                  | 4         | 1.57%   |
| Bluetooth                | 4         | 1.57%   |
| Sound                    | 3         | 1.18%   |
| Communication controller | 3         | 1.18%   |
| Dvb card                 | 2         | 0.78%   |
| Storage/raid             | 1         | 0.39%   |
| Modem                    | 1         | 0.39%   |
| Card reader              | 1         | 0.39%   |

