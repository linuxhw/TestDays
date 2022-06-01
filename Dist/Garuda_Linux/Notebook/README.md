Garuda Linux - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

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

Total: 188

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Razer         | Blade                       | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| HP            | Laptop 15-bs0xx             | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| MSI           | GF63 Thin 10SC              | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| Casper        | EXCALIBUR G770              | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| Dell          | Latitude E7250              | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| Toshiba       | Satellite E45DW-C           | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| HONOR         | HLYL-WXX9                   | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Unknown       | Unknown                     | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| Acer          | Aspire F5-573G              | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire A515-51G             | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| ASUSTek       | K53SD                       | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| Lenovo        | G510 20238                  | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Panasonic     | CF-191HYAX1M                | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| Notebook      | P7xxDM2(-G)                 | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Razer         | Blade                       | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| Google        | Kindred                     | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| ASUSTek       | G750JZ                      | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| PC Special... | GK5NPFO                     | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| HP            | EliteBook 8540p             | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Alienware     | 17 R3                       | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| Acer          | Nitro AN515-44              | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| Medion        | E7419 MD60025               | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| Dell          | System XPS L702X            | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | System XPS L702X            | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| HP            | EliteBook 8540p             | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| HP            | EliteBook 8540p             | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Dell          | Latitude E6520              | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| Dell          | XPS 15 9500                 | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| HP            | Compaq 6735b                | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| Unknown       | Unknown                     | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| HP            | EliteBook 8540p             | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| Dell          | Latitude E6430              | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Unknown       | Unknown                     | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| HP            | Laptop 17-ak0xx             | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| Dell          | Latitude E6430              | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| HP            | 450                         | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 98        | 73.68%  |
| Garuda Linux         | 35        | 26.32%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Garuda Linux | 133       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.17.9-zen1-1-zen           | 6         | 4.05%   |
| 5.16.16-zen1-1-zen          | 4         | 2.7%    |
| 5.14.14-zen1-1-zen          | 4         | 2.7%    |
| 5.13.13-zen1-1-zen          | 4         | 2.7%    |
| 5.17.3-zen1-1-zen           | 3         | 2.03%   |
| 5.17.1-zen1-1-zen           | 3         | 2.03%   |
| 5.16.4-zen1-1-zen           | 3         | 2.03%   |
| 5.16.2-zen1-1-zen           | 3         | 2.03%   |
| 5.15.6-zen2-1-zen           | 3         | 2.03%   |
| 5.15.2-zen1-1-zen           | 3         | 2.03%   |
| 5.15.12-zen1-1-zen          | 3         | 2.03%   |
| 5.14.6-zen1-1-zen           | 3         | 2.03%   |
| 5.13.9-zen1-1-zen           | 3         | 2.03%   |
| 5.11.11-zen1-1-zen          | 3         | 2.03%   |
| 5.10.1-103-tkg-bmq          | 3         | 2.03%   |
| 5.17.5-zen1-1-zen           | 2         | 1.35%   |
| 5.16.8-arch1-1              | 2         | 1.35%   |
| 5.16.5-zen1-1-zen           | 2         | 1.35%   |
| 5.16.14-zen1-1-zen          | 2         | 1.35%   |
| 5.16.1-zen1-1-zen           | 2         | 1.35%   |
| 5.15.5-zen1-1-zen           | 2         | 1.35%   |
| 5.15.4-zen1-1-zen           | 2         | 1.35%   |
| 5.15.13-zen1-1-zen          | 2         | 1.35%   |
| 5.14.9-zen2-1-zen           | 2         | 1.35%   |
| 5.14.15-zen1-1-zen          | 2         | 1.35%   |
| 5.13.5-zen1-1-zen           | 2         | 1.35%   |
| 5.12.9-zen1-1-zen           | 2         | 1.35%   |
| 5.12.15-zen1-1-zen          | 2         | 1.35%   |
| 5.11.16-zen1-1-zen          | 2         | 1.35%   |
| 5.10.2-104-tkg-bmq          | 2         | 1.35%   |
| 5.10.15-120-tkg-bmq         | 2         | 1.35%   |
| 5.10.10-115-tkg-bmq         | 2         | 1.35%   |
| 5.9.9-zen1-1-zen            | 1         | 0.68%   |
| 5.9.8-zen1-1-zen            | 1         | 0.68%   |
| 5.9.2-zen1-1-zen            | 1         | 0.68%   |
| 5.9.10-zen1-1-zen           | 1         | 0.68%   |
| 5.6.6-zen1-1-zen            | 1         | 0.68%   |
| 5.4.97-120-tkg-bmq          | 1         | 0.68%   |
| 5.18.0-zen1-1-zen           | 1         | 0.68%   |
| 5.17.5-xanmod1-1            | 1         | 0.68%   |
| 5.17.3-xanmod1-1            | 1         | 0.68%   |
| 5.17.2-zen3-1-zen           | 1         | 0.68%   |
| 5.17.1-arch1-g14-1          | 1         | 0.68%   |
| 5.16.9-zen1-1-zen           | 1         | 0.68%   |
| 5.16.11-zen1-1-zen          | 1         | 0.68%   |
| 5.16.0-rc5-1-mainline-anbox | 1         | 0.68%   |
| 5.15.7-zen1-1-zen           | 1         | 0.68%   |
| 5.15.7-arch1-1              | 1         | 0.68%   |
| 5.15.38-1-lts               | 1         | 0.68%   |
| 5.15.3-zen1-1-zen           | 1         | 0.68%   |
| 5.15.22-1-lts               | 1         | 0.68%   |
| 5.15.19-1-lts               | 1         | 0.68%   |
| 5.15.18-1-lts               | 1         | 0.68%   |
| 5.15.11-zen1-1-zen          | 1         | 0.68%   |
| 5.15.11-230-tkg-cfs         | 1         | 0.68%   |
| 5.15.10-zen1-1-zen          | 1         | 0.68%   |
| 5.14.8-zen1-1-zen           | 1         | 0.68%   |
| 5.14.7-zen1-1-zen           | 1         | 0.68%   |
| 5.14.5-zen2-1-zen           | 1         | 0.68%   |
| 5.14.2-zen1-2-zen           | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.9  | 6         | 4.05%   |
| 5.17.3  | 4         | 2.7%    |
| 5.17.1  | 4         | 2.7%    |
| 5.16.16 | 4         | 2.7%    |
| 5.14.14 | 4         | 2.7%    |
| 5.13.13 | 4         | 2.7%    |
| 5.11.11 | 4         | 2.7%    |
| 5.17.5  | 3         | 2.03%   |
| 5.16.4  | 3         | 2.03%   |
| 5.16.2  | 3         | 2.03%   |
| 5.15.6  | 3         | 2.03%   |
| 5.15.2  | 3         | 2.03%   |
| 5.15.12 | 3         | 2.03%   |
| 5.14.6  | 3         | 2.03%   |
| 5.13.9  | 3         | 2.03%   |
| 5.12.9  | 3         | 2.03%   |
| 5.10.15 | 3         | 2.03%   |
| 5.10.1  | 3         | 2.03%   |
| 5.16.8  | 2         | 1.35%   |
| 5.16.5  | 2         | 1.35%   |
| 5.16.14 | 2         | 1.35%   |
| 5.16.1  | 2         | 1.35%   |
| 5.15.7  | 2         | 1.35%   |
| 5.15.5  | 2         | 1.35%   |
| 5.15.4  | 2         | 1.35%   |
| 5.15.13 | 2         | 1.35%   |
| 5.15.11 | 2         | 1.35%   |
| 5.14.9  | 2         | 1.35%   |
| 5.14.15 | 2         | 1.35%   |
| 5.13.5  | 2         | 1.35%   |
| 5.12.15 | 2         | 1.35%   |
| 5.11.6  | 2         | 1.35%   |
| 5.11.16 | 2         | 1.35%   |
| 5.10.4  | 2         | 1.35%   |
| 5.10.2  | 2         | 1.35%   |
| 5.10.10 | 2         | 1.35%   |
| 5.9.9   | 1         | 0.68%   |
| 5.9.8   | 1         | 0.68%   |
| 5.9.2   | 1         | 0.68%   |
| 5.9.10  | 1         | 0.68%   |
| 5.6.6   | 1         | 0.68%   |
| 5.4.97  | 1         | 0.68%   |
| 5.18.0  | 1         | 0.68%   |
| 5.17.2  | 1         | 0.68%   |
| 5.16.9  | 1         | 0.68%   |
| 5.16.11 | 1         | 0.68%   |
| 5.16.0  | 1         | 0.68%   |
| 5.15.38 | 1         | 0.68%   |
| 5.15.3  | 1         | 0.68%   |
| 5.15.22 | 1         | 0.68%   |
| 5.15.19 | 1         | 0.68%   |
| 5.15.18 | 1         | 0.68%   |
| 5.15.10 | 1         | 0.68%   |
| 5.14.8  | 1         | 0.68%   |
| 5.14.7  | 1         | 0.68%   |
| 5.14.5  | 1         | 0.68%   |
| 5.14.2  | 1         | 0.68%   |
| 5.14.16 | 1         | 0.68%   |
| 5.14.12 | 1         | 0.68%   |
| 5.14.11 | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 17.36%  |
| 5.16    | 21        | 14.58%  |
| 5.10    | 20        | 13.89%  |
| 5.17    | 18        | 12.5%   |
| 5.14    | 18        | 12.5%   |
| 5.12    | 12        | 8.33%   |
| 5.11    | 12        | 8.33%   |
| 5.13    | 11        | 7.64%   |
| 5.9     | 4         | 2.78%   |
| 5.6     | 1         | 0.69%   |
| 5.4     | 1         | 0.69%   |
| 5.18    | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 133       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 81        | 60.45%  |
| GNOME             | 20        | 14.93%  |
| KDE               | 12        | 8.96%   |
| XFCE              | 8         | 5.97%   |
| X-Cinnamon        | 3         | 2.24%   |
| sway              | 3         | 2.24%   |
| qtile-default     | 2         | 1.49%   |
| Deepin            | 2         | 1.49%   |
| Yaru:ubuntu:GNOME | 1         | 0.75%   |
| MATE              | 1         | 0.75%   |
| i3                | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 122       | 91.73%  |
| Wayland | 9         | 6.77%   |
| Tty     | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 71        | 52.99%  |
| Unknown | 38        | 28.36%  |
| LightDM | 12        | 8.96%   |
| GDM     | 11        | 8.21%   |
| GREETD  | 2         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 63        | 47.01%  |
| en_GB   | 19        | 14.18%  |
| en_IN   | 12        | 8.96%   |
| it_IT   | 6         | 4.48%   |
| de_DE   | 6         | 4.48%   |
| pt_BR   | 3         | 2.24%   |
| pl_PL   | 3         | 2.24%   |
| es_MX   | 3         | 2.24%   |
| ru_RU   | 2         | 1.49%   |
| fi_FI   | 2         | 1.49%   |
| es_CO   | 2         | 1.49%   |
| en_CA   | 2         | 1.49%   |
| tr_TR   | 1         | 0.75%   |
| sv_SE   | 1         | 0.75%   |
| nl_NL   | 1         | 0.75%   |
| ko_KR   | 1         | 0.75%   |
| es_VE   | 1         | 0.75%   |
| es_ES   | 1         | 0.75%   |
| es_EC   | 1         | 0.75%   |
| en_ZA   | 1         | 0.75%   |
| en_DK   | 1         | 0.75%   |
| de_AT   | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 92        | 68.66%  |
| BIOS | 42        | 31.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 132       | 99.25%  |
| F2fs  | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 89        | 66.92%  |
| Unknown | 35        | 26.32%  |
| MBR     | 9         | 6.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 122       | 91.73%  |
| Yes       | 11        | 8.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 68.42%  |
| Yes       | 42        | 31.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 24.81%  |
| Hewlett-Packard     | 20        | 15.04%  |
| Dell                | 20        | 15.04%  |
| ASUSTek Computer    | 15        | 11.28%  |
| Acer                | 11        | 8.27%   |
| MSI                 | 7         | 5.26%   |
| Notebook            | 3         | 2.26%   |
| Toshiba             | 2         | 1.5%    |
| Samsung Electronics | 2         | 1.5%    |
| Razer               | 2         | 1.5%    |
| Medion              | 2         | 1.5%    |
| HUAWEI              | 2         | 1.5%    |
| Apple               | 2         | 1.5%    |
| Unknown             | 2         | 1.5%    |
| Sony                | 1         | 0.75%   |
| PC Specialist       | 1         | 0.75%   |
| Panasonic           | 1         | 0.75%   |
| HONOR               | 1         | 0.75%   |
| GPU Company         | 1         | 0.75%   |
| Google              | 1         | 0.75%   |
| Fujitsu Siemens     | 1         | 0.75%   |
| Chuwi               | 1         | 0.75%   |
| Casper              | 1         | 0.75%   |
| Alienware           | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 4         | 3.01%   |
| Unknown                                    | 3         | 2.26%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 1.5%    |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 1.5%    |
| Dell Inspiron 15 7000 Gaming               | 2         | 1.5%    |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 1.5%    |
| Acer Nitro AN515-44                        | 2         | 1.5%    |
| Toshiba Satellite E45DW-C                  | 1         | 0.75%   |
| Toshiba Satellite C55-A                    | 1         | 0.75%   |
| Sony VPCSB1C5E                             | 1         | 0.75%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.75%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.75%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.75%   |
| Razer Blade                                | 1         | 0.75%   |
| PC Specialist GK5NPFO                      | 1         | 0.75%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.75%   |
| Notebook W54_W550SU2                       | 1         | 0.75%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.75%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.75%   |
| MSI GS76 Stealth 11UG                      | 1         | 0.75%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.75%   |
| MSI GF63 Thin 9SC                          | 1         | 0.75%   |
| MSI GF63 Thin 10SC                         | 1         | 0.75%   |
| MSI GE75 Raider 9SE                        | 1         | 0.75%   |
| MSI GE72VR 6RF                             | 1         | 0.75%   |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.75%   |
| Medion P861X                               | 1         | 0.75%   |
| Medion E7419 MD60025                       | 1         | 0.75%   |
| Lenovo Z50-70 20354                        | 1         | 0.75%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB005WUS   | 1         | 0.75%   |
| Lenovo ThinkPad T530 24296KG               | 1         | 0.75%   |
| Lenovo ThinkPad T510 4384WB4               | 1         | 0.75%   |
| Lenovo ThinkPad T470s 20HGS0B900           | 1         | 0.75%   |
| Lenovo ThinkPad T470 20HD000RUS            | 1         | 0.75%   |
| Lenovo ThinkPad T440p 20AWS58F00           | 1         | 0.75%   |
| Lenovo ThinkPad T440p 20AWS4RC00           | 1         | 0.75%   |
| Lenovo ThinkPad T14 Gen 1 20UDS00N00       | 1         | 0.75%   |
| Lenovo ThinkPad S3 Yoga 14 20DM008FSC      | 1         | 0.75%   |
| Lenovo ThinkPad P1 20MDS00P00              | 1         | 0.75%   |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 0.75%   |
| Lenovo Legion S7 15ACH6 82K8               | 1         | 0.75%   |
| Lenovo Legion 7 15IMH05 81YT               | 1         | 0.75%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 1         | 0.75%   |
| Lenovo Legion 5 15IMH05H 81Y6              | 1         | 0.75%   |
| Lenovo Legion 5 15IMH05 82AU               | 1         | 0.75%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 0.75%   |
| Lenovo IdeaPad S340-15API 81NC             | 1         | 0.75%   |
| Lenovo IdeaPad S340-14API 81NB             | 1         | 0.75%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 1         | 0.75%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 0.75%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 1         | 0.75%   |
| Lenovo IdeaPad 110-15ACL 80TJ              | 1         | 0.75%   |
| Lenovo G510 20238                          | 1         | 0.75%   |
| HUAWEI HVY-WXX9                            | 1         | 0.75%   |
| HUAWEI BOHB-WAX9                           | 1         | 0.75%   |
| HONOR HLYL-WXX9                            | 1         | 0.75%   |
| HP ProBook 640 G1                          | 1         | 0.75%   |
| HP Pavilion Laptop 15z-eh100               | 1         | 0.75%   |
| HP Pavilion Laptop 15-eh0xxx               | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 9.02%   |
| Lenovo IdeaPad          | 11        | 8.27%   |
| HP Pavilion             | 7         | 5.26%   |
| Dell Latitude           | 7         | 5.26%   |
| Dell Inspiron           | 7         | 5.26%   |
| Lenovo Legion           | 5         | 3.76%   |
| HP Laptop               | 5         | 3.76%   |
| Acer Aspire             | 5         | 3.76%   |
| Dell XPS                | 4         | 3.01%   |
| Acer Nitro              | 4         | 3.01%   |
| HP OMEN                 | 3         | 2.26%   |
| ASUS VivoBook           | 3         | 2.26%   |
| ASUS ROG                | 3         | 2.26%   |
| Unknown                 | 3         | 2.26%   |
| Toshiba Satellite       | 2         | 1.5%    |
| Razer Blade             | 2         | 1.5%    |
| MSI GF63                | 2         | 1.5%    |
| HP EliteBook            | 2         | 1.5%    |
| ASUS TUF                | 2         | 1.5%    |
| ASUS ASUS               | 2         | 1.5%    |
| Sony VPCSB1C5E          | 1         | 0.75%   |
| Samsung 550XCJ          | 1         | 0.75%   |
| Samsung 300V3A          | 1         | 0.75%   |
| PC Specialist GK5NPFO   | 1         | 0.75%   |
| Panasonic CF-191HYAX1M  | 1         | 0.75%   |
| Notebook W54            | 1         | 0.75%   |
| Notebook P7xxDM2(-G)    | 1         | 0.75%   |
| Notebook N85            | 1         | 0.75%   |
| MSI GS76                | 1         | 0.75%   |
| MSI GP75                | 1         | 0.75%   |
| MSI GE75                | 1         | 0.75%   |
| MSI GE72VR              | 1         | 0.75%   |
| MSI GE63                | 1         | 0.75%   |
| Medion P861X            | 1         | 0.75%   |
| Medion E7419            | 1         | 0.75%   |
| Lenovo Z50-70           | 1         | 0.75%   |
| Lenovo Yoga             | 1         | 0.75%   |
| Lenovo ThinkBook        | 1         | 0.75%   |
| Lenovo G510             | 1         | 0.75%   |
| HUAWEI HVY-WXX9         | 1         | 0.75%   |
| HUAWEI BOHB-WAX9        | 1         | 0.75%   |
| HONOR HLYL-WXX9         | 1         | 0.75%   |
| HP ProBook              | 1         | 0.75%   |
| HP Compaq               | 1         | 0.75%   |
| HP 450                  | 1         | 0.75%   |
| GPU Company GWTN156-11  | 1         | 0.75%   |
| Google Kindred          | 1         | 0.75%   |
| Fujitsu Siemens ESPRIMO | 1         | 0.75%   |
| Dell System             | 1         | 0.75%   |
| Dell Precision          | 1         | 0.75%   |
| Chuwi GemiBook          | 1         | 0.75%   |
| Casper EXCALIBUR        | 1         | 0.75%   |
| ASUS X550ZE             | 1         | 0.75%   |
| ASUS X550CC             | 1         | 0.75%   |
| ASUS K53SD              | 1         | 0.75%   |
| ASUS GL503VM            | 1         | 0.75%   |
| ASUS G750JZ             | 1         | 0.75%   |
| Apple MacBookPro9       | 1         | 0.75%   |
| Apple MacBookPro12      | 1         | 0.75%   |
| Alienware 17            | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 29        | 21.8%   |
| 2021 | 19        | 14.29%  |
| 2019 | 14        | 10.53%  |
| 2016 | 12        | 9.02%   |
| 2017 | 11        | 8.27%   |
| 2018 | 10        | 7.52%   |
| 2013 | 8         | 6.02%   |
| 2014 | 7         | 5.26%   |
| 2012 | 7         | 5.26%   |
| 2011 | 6         | 4.51%   |
| 2015 | 3         | 2.26%   |
| 2010 | 2         | 1.5%    |
| 2009 | 2         | 1.5%    |
| 2007 | 2         | 1.5%    |
| 2008 | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 133       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 133       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 132       | 99.25%  |
| Yes  | 1         | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 41        | 30.6%   |
| 16.01-24.0 | 36        | 26.87%  |
| 8.01-16.0  | 33        | 24.63%  |
| 3.01-4.0   | 12        | 8.96%   |
| 32.01-64.0 | 8         | 5.97%   |
| 24.01-32.0 | 3         | 2.24%   |
| 2.01-3.0   | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 51        | 35.66%  |
| 2.01-3.0  | 38        | 26.57%  |
| 3.01-4.0  | 36        | 25.17%  |
| 1.01-2.0  | 9         | 6.29%   |
| 8.01-16.0 | 8         | 5.59%   |
| 0.51-1.0  | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 60.29%  |
| 2      | 42        | 30.88%  |
| 3      | 11        | 8.09%   |
| 4      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 77.94%  |
| Yes       | 30        | 22.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 76.12%  |
| No        | 32        | 23.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 98.5%   |
| No        | 2         | 1.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 88.06%  |
| No        | 16        | 11.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 34        | 25.37%  |
| UK           | 12        | 8.96%   |
| India        | 12        | 8.96%   |
| Germany      | 11        | 8.21%   |
| Italy        | 8         | 5.97%   |
| Poland       | 5         | 3.73%   |
| Canada       | 5         | 3.73%   |
| Mexico       | 4         | 2.99%   |
| Brazil       | 4         | 2.99%   |
| Romania      | 3         | 2.24%   |
| Finland      | 3         | 2.24%   |
| Turkey       | 2         | 1.49%   |
| Sweden       | 2         | 1.49%   |
| Spain        | 2         | 1.49%   |
| Russia       | 2         | 1.49%   |
| Netherlands  | 2         | 1.49%   |
| Denmark      | 2         | 1.49%   |
| Colombia     | 2         | 1.49%   |
| Venezuela    | 1         | 0.75%   |
| Switzerland  | 1         | 0.75%   |
| South Korea  | 1         | 0.75%   |
| South Africa | 1         | 0.75%   |
| Slovenia     | 1         | 0.75%   |
| Singapore    | 1         | 0.75%   |
| Serbia       | 1         | 0.75%   |
| Oman         | 1         | 0.75%   |
| Luxembourg   | 1         | 0.75%   |
| Kuwait       | 1         | 0.75%   |
| Kenya        | 1         | 0.75%   |
| Hungary      | 1         | 0.75%   |
| France       | 1         | 0.75%   |
| Ecuador      | 1         | 0.75%   |
| Czechia      | 1         | 0.75%   |
| China        | 1         | 0.75%   |
| Belgium      | 1         | 0.75%   |
| Bahrain      | 1         | 0.75%   |
| Austria      | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 3         | 2.14%   |
| Warsaw             | 2         | 1.43%   |
| Toronto            | 2         | 1.43%   |
| San Jose           | 2         | 1.43%   |
| Portland           | 2         | 1.43%   |
| Helsinki           | 2         | 1.43%   |
| Düsseldorf        | 2         | 1.43%   |
| Delhi              | 2         | 1.43%   |
| Copenhagen         | 2         | 1.43%   |
| Berlin             | 2         | 1.43%   |
| Winston-Salem      | 1         | 0.71%   |
| Welwyn Garden City | 1         | 0.71%   |
| Wasilla            | 1         | 0.71%   |
| Vancouver          | 1         | 0.71%   |
| Valencia           | 1         | 0.71%   |
| Turku              | 1         | 0.71%   |
| Turin              | 1         | 0.71%   |
| Tucson             | 1         | 0.71%   |
| Timișoara         | 1         | 0.71%   |
| Sunrise Beach      | 1         | 0.71%   |
| Steenwijk          | 1         | 0.71%   |
| Sparks             | 1         | 0.71%   |
| Southampton        | 1         | 0.71%   |
| Singapore          | 1         | 0.71%   |
| Sighetu Marmaţiei | 1         | 0.71%   |
| San Francisco      | 1         | 0.71%   |
| San Antonio        | 1         | 0.71%   |
| Rome               | 1         | 0.71%   |
| Pune               | 1         | 0.71%   |
| Puebla City        | 1         | 0.71%   |
| Prague             | 1         | 0.71%   |
| Poznan             | 1         | 0.71%   |
| Pompano Beach      | 1         | 0.71%   |
| Pocheon-si         | 1         | 0.71%   |
| Pitalito           | 1         | 0.71%   |
| Phoenix            | 1         | 0.71%   |
| Perg               | 1         | 0.71%   |
| Paola              | 1         | 0.71%   |
| Palm Beach Gardens | 1         | 0.71%   |
| Oxford             | 1         | 0.71%   |
| Owings Mills       | 1         | 0.71%   |
| Origlio            | 1         | 0.71%   |
| Olympia            | 1         | 0.71%   |
| New Glasgow        | 1         | 0.71%   |
| New Delhi          | 1         | 0.71%   |
| New Baltimore      | 1         | 0.71%   |
| Natal              | 1         | 0.71%   |
| Nairobi            | 1         | 0.71%   |
| Muscat             | 1         | 0.71%   |
| Münster           | 1         | 0.71%   |
| Mostoles           | 1         | 0.71%   |
| Moscow             | 1         | 0.71%   |
| Montreal           | 1         | 0.71%   |
| Milan              | 1         | 0.71%   |
| Mexico City        | 1         | 0.71%   |
| Manning            | 1         | 0.71%   |
| Manama             | 1         | 0.71%   |
| Malatya            | 1         | 0.71%   |
| Mainz              | 1         | 0.71%   |
| Luxembourg         | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 34        | 43     | 17.44%  |
| Seagate                     | 24        | 26     | 12.31%  |
| WDC                         | 21        | 22     | 10.77%  |
| SK Hynix                    | 14        | 16     | 7.18%   |
| Sandisk                     | 11        | 14     | 5.64%   |
| Toshiba                     | 10        | 12     | 5.13%   |
| HGST                        | 9         | 9      | 4.62%   |
| Unknown                     | 8         | 8      | 4.1%    |
| Kingston                    | 6         | 6      | 3.08%   |
| Intel                       | 5         | 6      | 2.56%   |
| Crucial                     | 5         | 8      | 2.56%   |
| Micron Technology           | 4         | 4      | 2.05%   |
| Silicon Motion              | 3         | 3      | 1.54%   |
| PNY                         | 3         | 3      | 1.54%   |
| LITEON                      | 3         | 3      | 1.54%   |
| KIOXIA                      | 3         | 4      | 1.54%   |
| Hitachi                     | 3         | 3      | 1.54%   |
| Corsair                     | 3         | 3      | 1.54%   |
| Union Memory (Shenzhen)     | 2         | 2      | 1.03%   |
| Phison                      | 2         | 2      | 1.03%   |
| China                       | 2         | 2      | 1.03%   |
| Yangtze Memory Technologies | 1         | 1      | 0.51%   |
| WDC WDS                     | 1         | 1      | 0.51%   |
| VisionTek                   | 1         | 2      | 0.51%   |
| UMIS                        | 1         | 1      | 0.51%   |
| SSSTC                       | 1         | 1      | 0.51%   |
| SPCC                        | 1         | 1      | 0.51%   |
| ShanDianZhe                 | 1         | 1      | 0.51%   |
| SABRENT                     | 1         | 2      | 0.51%   |
| PNY CS90                    | 1         | 1      | 0.51%   |
| Phison Electronics          | 1         | 1      | 0.51%   |
| Netac                       | 1         | 1      | 0.51%   |
| Mushkin                     | 1         | 1      | 0.51%   |
| Micron/Crucial Technology   | 1         | 1      | 0.51%   |
| LITEONIT                    | 1         | 1      | 0.51%   |
| Lenovo                      | 1         | 1      | 0.51%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.51%   |
| Intenso                     | 1         | 1      | 0.51%   |
| FORESEE                     | 1         | 1      | 0.51%   |
| ASMT                        | 1         | 1      | 0.51%   |
| A-DATA Technology           | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB               | 5         | 2.48%   |
| Seagate ST1000LM035-1RK172 1TB               | 5         | 2.48%   |
| Samsung NVMe SSD Drive 1TB                   | 4         | 1.98%   |
| Toshiba MQ01ABD100 1TB                       | 3         | 1.49%   |
| Samsung SSD 860 EVO 1TB                      | 3         | 1.49%   |
| HGST HTS721010A9E630 1TB                     | 3         | 1.49%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB         | 2         | 0.99%   |
| Unknown MMC Card  16GB                       | 2         | 0.99%   |
| SK Hynix SC311 SATA 256GB SSD                | 2         | 0.99%   |
| SK Hynix NVMe SSD Drive 512GB                | 2         | 0.99%   |
| Seagate ST2000LM015-2E8174 2TB               | 2         | 0.99%   |
| Seagate ST1000LM048-2E7172 1TB               | 2         | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 0.99%   |
| Seagate ST1000LM014-1EJ164 1TB               | 2         | 0.99%   |
| Samsung SSD 870 QVO 1TB                      | 2         | 0.99%   |
| Samsung SSD 870 EVO 500GB                    | 2         | 0.99%   |
| Samsung NVMe SSD Drive 256GB                 | 2         | 0.99%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD         | 2         | 0.99%   |
| PNY ELITE PSSD 480GB                         | 2         | 0.99%   |
| KIOXIA NVMe SSD Drive 512GB                  | 2         | 0.99%   |
| Intel SSDPEKNW010T8 1TB                      | 2         | 0.99%   |
| HGST HTS725050A7E630 500GB                   | 2         | 0.99%   |
| HGST HTS541075A9E680 752GB                   | 2         | 0.99%   |
| Corsair Force MP300 960GB                    | 2         | 0.99%   |
| Yangtze Memory NVMe SSD Drive 256GB          | 1         | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1         | 0.5%    |
| WDC WDS 500G2B0B-00YS70 500GB SSD            | 1         | 0.5%    |
| WDC WDBNCE5000PNC 500GB SSD                  | 1         | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 0.5%    |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 0.5%    |
| WDC WD5000BEVT-60A0RT0 500GB                 | 1         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 0.5%    |
| WDC WD10JPVX-11JC3T0 1TB                     | 1         | 0.5%    |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB           | 1         | 0.5%    |
| WDC PC SN530 SDBPTPZ-512G-1002 512GB         | 1         | 0.5%    |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB           | 1         | 0.5%    |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB         | 1         | 0.5%    |
| WDC PC SN530 SDBPNPZ-256G-1032 256GB         | 1         | 0.5%    |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB         | 1         | 0.5%    |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB         | 1         | 0.5%    |
| WDC PC SN520 SDAPNUW-256G-1002 256GB         | 1         | 0.5%    |
| WDC PC SN520 SDAPNUW-128G-1006 128GB         | 1         | 0.5%    |
| WDC PC SN520 SDAPNUW-128G                    | 1         | 0.5%    |
| WDC PC SN520 SDAPMUW-512G-1101 512GB         | 1         | 0.5%    |
| VisionTek SSD 120GB                          | 1         | 0.5%    |
| Unknown SL64G  64GB                          | 1         | 0.5%    |
| Unknown SF256  256GB                         | 1         | 0.5%    |
| Unknown SD/MMC/MS PRO 999GB                  | 1         | 0.5%    |
| Unknown MMC128  128GB                        | 1         | 0.5%    |
| Unknown DA4128  128GB                        | 1         | 0.5%    |
| Unknown APPSD  16GB                          | 1         | 0.5%    |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 1         | 0.5%    |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.5%    |
| UMIS RPFTJ256PDD2MWX 256GB                   | 1         | 0.5%    |
| Toshiba THNSNJ128G8NY 128GB SSD              | 1         | 0.5%    |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.5%    |
| Toshiba MQ02ABD100H 1TB                      | 1         | 0.5%    |
| Toshiba KXG60ZNV1T02 NVMe KIOXIA 1024GB      | 1         | 0.5%    |
| Toshiba KBG40ZNT512G MEMORY 512GB            | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 23        | 24     | 47.92%  |
| HGST    | 9         | 9      | 18.75%  |
| WDC     | 5         | 5      | 10.42%  |
| Toshiba | 5         | 7      | 10.42%  |
| Hitachi | 3         | 3      | 6.25%   |
| Unknown | 1         | 1      | 2.08%   |
| SABRENT | 1         | 2      | 2.08%   |
| ASMT    | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 30.36%  |
| SanDisk             | 5         | 8      | 8.93%   |
| Kingston            | 4         | 4      | 7.14%   |
| Crucial             | 4         | 7      | 7.14%   |
| WDC                 | 3         | 4      | 5.36%   |
| SK Hynix            | 3         | 4      | 5.36%   |
| PNY                 | 3         | 3      | 5.36%   |
| LITEON              | 3         | 3      | 5.36%   |
| China               | 2         | 2      | 3.57%   |
| WDC WDS             | 1         | 1      | 1.79%   |
| VisionTek           | 1         | 2      | 1.79%   |
| Toshiba             | 1         | 1      | 1.79%   |
| PNY CS90            | 1         | 1      | 1.79%   |
| Netac               | 1         | 1      | 1.79%   |
| Mushkin             | 1         | 1      | 1.79%   |
| LITEONIT            | 1         | 1      | 1.79%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.79%   |
| Intenso             | 1         | 1      | 1.79%   |
| FORESEE             | 1         | 1      | 1.79%   |
| Corsair             | 1         | 1      | 1.79%   |
| A-DATA Technology   | 1         | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 71        | 90     | 39.66%  |
| SSD     | 52        | 68     | 29.05%  |
| HDD     | 45        | 52     | 25.14%  |
| MMC     | 8         | 8      | 4.47%   |
| Unknown | 3         | 3      | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 107    | 45.88%  |
| NVMe | 71        | 90     | 41.76%  |
| SAS  | 13        | 16     | 7.65%   |
| MMC  | 8         | 8      | 4.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 61     | 51.49%  |
| 0.51-1.0   | 44        | 54     | 43.56%  |
| 1.01-2.0   | 4         | 4      | 3.96%   |
| 3.01-4.0   | 1         | 1      | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 47        | 35.07%  |
| 1001-2000      | 30        | 22.39%  |
| 501-1000       | 25        | 18.66%  |
| 2001-3000      | 15        | 11.19%  |
| Unknown        | 8         | 5.97%   |
| 251-500        | 5         | 3.73%   |
| 101-250        | 2         | 1.49%   |
| 1-20           | 2         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 41        | 29.08%  |
| 251-500        | 26        | 18.44%  |
| 501-1000       | 20        | 14.18%  |
| 51-100         | 19        | 13.48%  |
| 1001-2000      | 18        | 12.77%  |
| Unknown        | 8         | 5.67%   |
| 2001-3000      | 4         | 2.84%   |
| More than 3000 | 3         | 2.13%   |
| 1-20           | 2         | 1.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB   | 1         | 1      | 12.5%   |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 12.5%   |
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 12.5%   |
| Hitachi HTS547575A9E384 752GB  | 1         | 1      | 12.5%   |
| Hitachi HTS542525K9SA00 250GB  | 1         | 1      | 12.5%   |
| HGST HTS725050A7E630 500GB     | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB       | 1         | 1      | 12.5%   |
| HGST HTS541075A9E680 752GB     | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 37.5%   |
| Seagate | 2         | 2      | 25%     |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 3         | 3      | 37.5%   |
| Seagate | 2         | 2      | 25%     |
| Hitachi | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 100%    |

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
| Works    | 79        | 112    | 52.32%  |
| Detected | 64        | 101    | 42.38%  |
| Malfunc  | 8         | 8      | 5.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 84        | 46.15%  |
| AMD                            | 24        | 13.19%  |
| Samsung Electronics            | 18        | 9.89%   |
| Sandisk                        | 16        | 8.79%   |
| SK Hynix                       | 11        | 6.04%   |
| Phison Electronics             | 6         | 3.3%    |
| Union Memory (Shenzhen)        | 3         | 1.65%   |
| Toshiba America Info Systems   | 3         | 1.65%   |
| Silicon Motion                 | 3         | 1.65%   |
| Micron Technology              | 3         | 1.65%   |
| KIOXIA                         | 3         | 1.65%   |
| Micron/Crucial Technology      | 2         | 1.1%    |
| Kingston Technology Company    | 2         | 1.1%    |
| Yangtze Memory Technologies    | 1         | 0.55%   |
| Solid State Storage Technology | 1         | 0.55%   |
| Nvidia                         | 1         | 0.55%   |
| Lenovo                         | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 23        | 12.3%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 12        | 6.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 5.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 9         | 4.81%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 8         | 4.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 4.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 8         | 4.28%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 5         | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 2.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 5         | 2.67%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 2.14%   |
| Phison E12 NVMe Controller                                                             | 4         | 2.14%   |
| Intel SSD 660P Series                                                                  | 4         | 2.14%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 4         | 2.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 2.14%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 3         | 1.6%    |
| SK Hynix Gold P31 SSD                                                                  | 3         | 1.6%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 3         | 1.6%    |
| Micron Non-Volatile memory controller                                                  | 3         | 1.6%    |
| KIOXIA Non-Volatile memory controller                                                  | 3         | 1.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 1.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 1.07%   |
| Sandisk Non-Volatile memory controller                                                 | 2         | 1.07%   |
| Phison NVMe Storage Controller                                                         | 2         | 1.07%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.07%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 2         | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.07%   |
| Yangtze Memory Non-Volatile memory controller                                          | 1         | 0.53%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.53%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 0.53%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.53%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 0.53%   |
| SK Hynix BC511                                                                         | 1         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.53%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 1         | 0.53%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 0.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.53%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.53%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.53%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.53%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.53%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 0.53%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.53%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.53%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.53%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 92        | 52.27%  |
| NVMe | 69        | 39.2%   |
| RAID | 12        | 6.82%   |
| IDE  | 3         | 1.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 92        | 69.17%  |
| AMD    | 41        | 30.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 5.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 5.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 3.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 3.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.01%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 3.01%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 2.26%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 2.26%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 2.26%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 2.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.26%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.5%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.5%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.5%    |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.5%    |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.5%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.5%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.5%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.75%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.75%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.75%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.75%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.75%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.75%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.75%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.75%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.75%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.75%   |
| Intel Core i7 CPU Q 840 @ 1.87GHz             | 1         | 0.75%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.75%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.75%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.75%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 1         | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.75%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 0.75%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 0.75%   |
| Intel Core i3-2365M CPU @ 1.40GHz             | 1         | 0.75%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 0.75%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 0.75%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 0.75%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 43        | 32.33%  |
| Intel Core i5           | 24        | 18.05%  |
| AMD Ryzen 7             | 15        | 11.28%  |
| AMD Ryzen 5             | 13        | 9.77%   |
| Intel Core i3           | 8         | 6.02%   |
| Other                   | 6         | 4.51%   |
| Intel Celeron           | 5         | 3.76%   |
| AMD Ryzen 9             | 3         | 2.26%   |
| Intel Pentium Silver    | 2         | 1.5%    |
| Intel Pentium           | 2         | 1.5%    |
| Intel Core 2 Duo        | 2         | 1.5%    |
| AMD Ryzen 7 PRO         | 2         | 1.5%    |
| Intel Pentium Dual-Core | 1         | 0.75%   |
| Intel Core m3           | 1         | 0.75%   |
| AMD Turion              | 1         | 0.75%   |
| AMD FX                  | 1         | 0.75%   |
| AMD A8                  | 1         | 0.75%   |
| AMD A6                  | 1         | 0.75%   |
| AMD A4                  | 1         | 0.75%   |
| AMD A10                 | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 36.84%  |
| 4      | 44        | 33.08%  |
| 6      | 22        | 16.54%  |
| 8      | 18        | 13.53%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 133       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 86.47%  |
| 1      | 18        | 13.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 133       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 36.76%  |
| 0x906ea    | 6         | 4.41%   |
| 0x306a9    | 6         | 4.41%   |
| 0xa0652    | 5         | 3.68%   |
| 0x906e9    | 5         | 3.68%   |
| 0x206a7    | 5         | 3.68%   |
| 0x0a50000c | 5         | 3.68%   |
| 0x306c3    | 4         | 2.94%   |
| 0x08600103 | 4         | 2.94%   |
| 0x806e9    | 3         | 2.21%   |
| 0x08600106 | 3         | 2.21%   |
| 0x08600104 | 3         | 2.21%   |
| 0x08108109 | 3         | 2.21%   |
| 0x08108102 | 3         | 2.21%   |
| 0x806ec    | 2         | 1.47%   |
| 0x806ea    | 2         | 1.47%   |
| 0x506e3    | 2         | 1.47%   |
| 0x406e3    | 2         | 1.47%   |
| 0x40651    | 2         | 1.47%   |
| 0x106e5    | 2         | 1.47%   |
| 0x08608103 | 2         | 1.47%   |
| 0x06006705 | 2         | 1.47%   |
| 0xa0660    | 1         | 0.74%   |
| 0x806c1    | 1         | 0.74%   |
| 0x706e5    | 1         | 0.74%   |
| 0x706a8    | 1         | 0.74%   |
| 0x706a1    | 1         | 0.74%   |
| 0x506c9    | 1         | 0.74%   |
| 0x406c4    | 1         | 0.74%   |
| 0x306d4    | 1         | 0.74%   |
| 0x20655    | 1         | 0.74%   |
| 0x1067a    | 1         | 0.74%   |
| 0x10676    | 1         | 0.74%   |
| 0x0a50000b | 1         | 0.74%   |
| 0x08101007 | 1         | 0.74%   |
| 0x0700010f | 1         | 0.74%   |
| 0x06006110 | 1         | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 30        | 22.56%  |
| Zen 2           | 14        | 10.53%  |
| Haswell         | 9         | 6.77%   |
| CometLake       | 9         | 6.77%   |
| Zen+            | 8         | 6.02%   |
| Zen 3           | 8         | 6.02%   |
| SandyBridge     | 8         | 6.02%   |
| IvyBridge       | 8         | 6.02%   |
| Skylake         | 7         | 5.26%   |
| Broadwell       | 4         | 3.01%   |
| TigerLake       | 3         | 2.26%   |
| Penryn          | 3         | 2.26%   |
| Goldmont plus   | 3         | 2.26%   |
| Excavator       | 3         | 2.26%   |
| Unknown         | 3         | 2.26%   |
| Silvermont      | 2         | 1.5%    |
| Puma            | 2         | 1.5%    |
| Nehalem         | 2         | 1.5%    |
| Zen             | 1         | 0.75%   |
| Westmere        | 1         | 0.75%   |
| Steamroller     | 1         | 0.75%   |
| K8 & K10 hybrid | 1         | 0.75%   |
| Jaguar          | 1         | 0.75%   |
| IceLake         | 1         | 0.75%   |
| Goldmont        | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 84        | 43.52%  |
| Nvidia | 65        | 33.68%  |
| AMD    | 44        | 22.8%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                | 14        | 7%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 10        | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                          | 8         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 8         | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 8         | 4%      |
| AMD Cezanne                                                               | 8         | 4%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 7         | 3.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 3.5%    |
| Nvidia TU117M                                                             | 5         | 2.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 5         | 2.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 5         | 2.5%    |
| Intel HD Graphics 630                                                     | 5         | 2.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 2.5%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 4         | 2%      |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 4         | 2%      |
| Intel UHD Graphics 620                                                    | 4         | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 2%      |
| Intel HD Graphics 620                                                     | 4         | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 2%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 3         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.5%    |
| Nvidia GM108M [GeForce 840M]                                              | 3         | 1.5%    |
| Intel HD Graphics 5500                                                    | 3         | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 1.5%    |
| Nvidia GK107GLM [Quadro K1000M]                                           | 2         | 1%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1%      |
| Intel HD Graphics 530                                                     | 2         | 1%      |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1%      |
| AMD Lucienne                                                              | 2         | 1%      |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.5%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.5%    |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                    | 1         | 0.5%    |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.5%    |
| Nvidia GT215GLM [Quadro FX 1800M]                                         | 1         | 0.5%    |
| Nvidia Graphics Device                                                    | 1         | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 1         | 0.5%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.5%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                  | 1         | 0.5%    |
| Nvidia GM204M [GeForce GTX 970M]                                          | 1         | 0.5%    |
| Nvidia GM204 [GeForce GTX 980]                                            | 1         | 0.5%    |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.5%    |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.5%    |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.5%    |
| Nvidia GK104M [GeForce GTX 880M]                                          | 1         | 0.5%    |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.5%    |
| Nvidia GF106M [GeForce GT 550M]                                           | 1         | 0.5%    |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 0.5%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.5%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 0.5%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 0.5%    |
| Nvidia C79 [GeForce 9100M G]                                              | 1         | 0.5%    |
| Intel UHD Graphics 615                                                    | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 42        | 31.58%  |
| Intel + Nvidia     | 37        | 27.82%  |
| 1 x AMD            | 21        | 15.79%  |
| AMD + Nvidia       | 18        | 13.53%  |
| 1 x Nvidia         | 8         | 6.02%   |
| Intel + AMD        | 3         | 2.26%   |
| 2 x AMD            | 2         | 1.5%    |
| Intel + 2 x Nvidia | 2         | 1.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 84        | 62.69%  |
| Proprietary | 50        | 37.31%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 64.96%  |
| 0.01-0.5   | 23        | 16.79%  |
| 1.01-2.0   | 12        | 8.76%   |
| 5.01-6.0   | 5         | 3.65%   |
| 3.01-4.0   | 5         | 3.65%   |
| 0.51-1.0   | 2         | 1.46%   |
| 7.01-8.0   | 1         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 21.15%  |
| LG Display              | 24        | 15.38%  |
| BOE                     | 21        | 13.46%  |
| Chimei Innolux          | 20        | 12.82%  |
| Samsung Electronics     | 12        | 7.69%   |
| Sharp                   | 8         | 5.13%   |
| PANDA                   | 8         | 5.13%   |
| Lenovo                  | 4         | 2.56%   |
| Dell                    | 3         | 1.92%   |
| Goldstar                | 2         | 1.28%   |
| CSO                     | 2         | 1.28%   |
| BenQ                    | 2         | 1.28%   |
| Apple                   | 2         | 1.28%   |
| AOC                     | 2         | 1.28%   |
| Acer                    | 2         | 1.28%   |
| Sony                    | 1         | 0.64%   |
| Philips                 | 1         | 0.64%   |
| MStar                   | 1         | 0.64%   |
| Mi                      | 1         | 0.64%   |
| InfoVision              | 1         | 0.64%   |
| Hewlett-Packard         | 1         | 0.64%   |
| G-Story                 | 1         | 0.64%   |
| Eizo                    | 1         | 0.64%   |
| CPT                     | 1         | 0.64%   |
| Chi Mei Optoelectronics | 1         | 0.64%   |
| ASUSTek Computer        | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 2.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 1.92%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 1.28%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 1.28%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.28%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.28%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 1.28%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch               | 2         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 1.28%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 2         | 1.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.28%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 1.28%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                 | 2         | 1.28%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.28%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 1.28%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.64%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.64%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.64%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.64%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.64%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.64%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.64%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch     | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM07E8 1280x720 950x540mm 43.0-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 1         | 0.64%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1         | 0.64%   |
| Philips 272P4 PHL08C5 2560x1440 597x336mm 27.0-inch                   | 1         | 0.64%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.64%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.64%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.64%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.64%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.64%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 1         | 0.64%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD04CC 1366x768 309x174mm 14.0-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD046A 1366x768 344x194mm 15.5-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD03FE 1920x1080 345x194mm 15.6-inch          | 1         | 0.64%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 85        | 58.22%  |
| 1366x768 (WXGA)    | 21        | 14.38%  |
| 1600x900 (HD+)     | 9         | 6.16%   |
| 3840x2160 (4K)     | 6         | 4.11%   |
| 2560x1440 (QHD)    | 4         | 2.74%   |
| 2560x1600          | 3         | 2.05%   |
| 1920x1200 (WUXGA)  | 3         | 2.05%   |
| 1680x1050 (WSXGA+) | 3         | 2.05%   |
| 1280x800 (WXGA)    | 2         | 1.37%   |
| 3840x2400          | 1         | 0.68%   |
| 3440x1440          | 1         | 0.68%   |
| 3200x1800 (QHD+)   | 1         | 0.68%   |
| 2880x1440          | 1         | 0.68%   |
| 2256x1504          | 1         | 0.68%   |
| 2160x1440          | 1         | 0.68%   |
| 1680x945           | 1         | 0.68%   |
| 1600x1200          | 1         | 0.68%   |
| 1440x900 (WXGA+)   | 1         | 0.68%   |
| 1280x720 (HD)      | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 78        | 50.32%  |
| 14      | 19        | 12.26%  |
| 13      | 14        | 9.03%   |
| 17      | 10        | 6.45%   |
| 27      | 5         | 3.23%   |
| 16      | 4         | 2.58%   |
| 23      | 3         | 1.94%   |
| 21      | 3         | 1.94%   |
| 18      | 3         | 1.94%   |
| 31      | 2         | 1.29%   |
| 22      | 2         | 1.29%   |
| Unknown | 2         | 1.29%   |
| 72      | 1         | 0.65%   |
| 54      | 1         | 0.65%   |
| 52      | 1         | 0.65%   |
| 47      | 1         | 0.65%   |
| 43      | 1         | 0.65%   |
| 34      | 1         | 0.65%   |
| 24      | 1         | 0.65%   |
| 20      | 1         | 0.65%   |
| 12      | 1         | 0.65%   |
| 11      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 105       | 67.74%  |
| 351-400     | 12        | 7.74%   |
| 201-300     | 10        | 6.45%   |
| 501-600     | 9         | 5.81%   |
| 401-500     | 9         | 5.81%   |
| 1001-1500   | 3         | 1.94%   |
| 601-700     | 2         | 1.29%   |
| Unknown     | 2         | 1.29%   |
| 701-800     | 1         | 0.65%   |
| 1501-2000   | 1         | 0.65%   |
| 901-1000    | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 122       | 87.14%  |
| 16/10 | 13        | 9.29%   |
| 3/2   | 2         | 1.43%   |
| 4/3   | 1         | 0.71%   |
| 21/9  | 1         | 0.71%   |
| 2.00  | 1         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 79        | 50.97%  |
| 81-90          | 28        | 18.06%  |
| 121-130        | 10        | 6.45%   |
| 201-250        | 7         | 4.52%   |
| 71-80          | 5         | 3.23%   |
| 301-350        | 5         | 3.23%   |
| More than 1000 | 3         | 1.94%   |
| 351-500        | 3         | 1.94%   |
| 141-150        | 3         | 1.94%   |
| 151-200        | 2         | 1.29%   |
| 111-120        | 2         | 1.29%   |
| 501-1000       | 2         | 1.29%   |
| Unknown        | 2         | 1.29%   |
| 61-70          | 1         | 0.65%   |
| 51-60          | 1         | 0.65%   |
| 251-300        | 1         | 0.65%   |
| 91-100         | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 86        | 56.58%  |
| 101-120       | 31        | 20.39%  |
| 51-100        | 15        | 9.87%   |
| 161-240       | 8         | 5.26%   |
| More than 240 | 5         | 3.29%   |
| 1-50          | 5         | 3.29%   |
| Unknown       | 2         | 1.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 104       | 77.04%  |
| 2     | 30        | 22.22%  |
| 0     | 1         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 78        | 35.94%  |
| Intel                             | 74        | 34.1%   |
| Qualcomm Atheros                  | 33        | 15.21%  |
| Broadcom                          | 9         | 4.15%   |
| MEDIATEK                          | 3         | 1.38%   |
| TP-Link                           | 2         | 0.92%   |
| Samsung Electronics               | 2         | 0.92%   |
| Qualcomm                          | 2         | 0.92%   |
| ASUSTek Computer                  | 2         | 0.92%   |
| Xiaomi                            | 1         | 0.46%   |
| Wacom                             | 1         | 0.46%   |
| Sierra Wireless                   | 1         | 0.46%   |
| Ralink Technology                 | 1         | 0.46%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.46%   |
| Nvidia                            | 1         | 0.46%   |
| NetGear                           | 1         | 0.46%   |
| Lenovo                            | 1         | 0.46%   |
| Ericsson Business Mobile Networks | 1         | 0.46%   |
| DisplayLink                       | 1         | 0.46%   |
| Dell                              | 1         | 0.46%   |
| ASIX Electronics                  | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 50        | 19.61%  |
| Intel Wi-Fi 6 AX200                                                     | 15        | 5.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 3.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 3.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 2.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.96%   |
| Intel Wireless 3165                                                     | 5         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 4         | 1.57%   |
| Intel Wireless 7260                                                     | 4         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 1.18%   |
| Intel Wireless 7265                                                     | 3         | 1.18%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.78%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.78%   |
| Intel Wireless 8260                                                     | 2         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.78%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.78%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 2         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.39%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                | 1         | 0.39%   |
| Sierra Wireless EM7455                                                  | 1         | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.39%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.39%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.39%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.39%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.39%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.39%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.39%   |
| Qualcomm Redmi Note 9S                                                  | 1         | 0.39%   |
| Qualcomm M2012K11AG                                                     | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.39%   |
| OnePlus (Shenzhen) EB2103                                               | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 71        | 50%     |
| Qualcomm Atheros      | 27        | 19.01%  |
| Realtek Semiconductor | 24        | 16.9%   |
| Broadcom              | 8         | 5.63%   |
| MEDIATEK              | 3         | 2.11%   |
| TP-Link               | 2         | 1.41%   |
| ASUSTek Computer      | 2         | 1.41%   |
| Wacom                 | 1         | 0.7%    |
| Sierra Wireless       | 1         | 0.7%    |
| Ralink Technology     | 1         | 0.7%    |
| NetGear               | 1         | 0.7%    |
| Dell                  | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 15        | 10.42%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 6.25%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.17%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.47%   |
| Intel Wireless 3165                                                     | 5         | 3.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 2.78%   |
| Intel Wireless 7260                                                     | 4         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.78%   |
| Intel Wireless 7265                                                     | 3         | 2.08%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 1.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.39%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.39%   |
| Intel Wireless 8260                                                     | 2         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.39%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                | 1         | 0.69%   |
| Sierra Wireless EM7455                                                  | 1         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.69%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.69%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.69%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.69%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.69%   |
| MediaTek WiFi                                                           | 1         | 0.69%   |
| Intel Wireless 3160                                                     | 1         | 0.69%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.69%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.69%   |
| Intel Centrino Wireless-N 100                                           | 1         | 0.69%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.69%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 1         | 0.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 0.69%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.69%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]     | 1         | 0.69%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]          | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 65        | 59.63%  |
| Intel                 | 22        | 20.18%  |
| Qualcomm Atheros      | 10        | 9.17%   |
| Broadcom              | 3         | 2.75%   |
| Samsung Electronics   | 2         | 1.83%   |
| Qualcomm              | 2         | 1.83%   |
| Xiaomi                | 1         | 0.92%   |
| Nvidia                | 1         | 0.92%   |
| Lenovo                | 1         | 0.92%   |
| DisplayLink           | 1         | 0.92%   |
| ASIX Electronics      | 1         | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 45.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 6.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 3.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 2.75%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.83%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.83%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.83%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.92%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.92%   |
| Qualcomm Redmi Note 9S                                            | 1         | 0.92%   |
| Qualcomm M2012K11AG                                               | 1         | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.92%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.92%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.92%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.92%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.92%   |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 55.74%  |
| Ethernet | 102       | 43.4%   |
| Modem    | 1         | 0.43%   |
| Unknown  | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 79.26%  |
| Ethernet | 28        | 20.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 93        | 69.92%  |
| 1     | 38        | 28.57%  |
| 3     | 1         | 0.75%   |
| 0     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 79.26%  |
| Yes  | 28        | 20.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 48.33%  |
| Qualcomm Atheros Communications | 19        | 15.83%  |
| Realtek Semiconductor           | 16        | 13.33%  |
| IMC Networks                    | 7         | 5.83%   |
| Lite-On Technology              | 4         | 3.33%   |
| Foxconn / Hon Hai               | 4         | 3.33%   |
| Broadcom                        | 4         | 3.33%   |
| Hewlett-Packard                 | 2         | 1.67%   |
| Dell                            | 2         | 1.67%   |
| Apple                           | 2         | 1.67%   |
| Realtek                         | 1         | 0.83%   |
| Cambridge Silicon Radio         | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 13.33%  |
| Intel AX200 Bluetooth                                                               | 15        | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 10.83%  |
| Intel AX201 Bluetooth                                                               | 10        | 8.33%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 7.5%    |
| Realtek Bluetooth Radio                                                             | 7         | 5.83%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 5%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 5%      |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 2.5%    |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.67%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.67%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.67%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.83%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.83%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.83%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.83%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.83%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.83%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.83%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.83%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.83%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 52.6%   |
| AMD                   | 41        | 23.7%   |
| Nvidia                | 31        | 17.92%  |
| Corsair               | 2         | 1.16%   |
| Turtle Beach          | 1         | 0.58%   |
| RODE Microphones      | 1         | 0.58%   |
| Realtek Semiconductor | 1         | 0.58%   |
| Phison Electronics    | 1         | 0.58%   |
| JMTek                 | 1         | 0.58%   |
| Jieli Technology      | 1         | 0.58%   |
| Huawei Technologies   | 1         | 0.58%   |
| GN Netcom             | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 15.02%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 6.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 5.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 5.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 3.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 3.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.29%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.35%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.88%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.88%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.88%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.41%   |
| Nvidia Audio device                                                                               | 3         | 1.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.41%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.94%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.94%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.94%   |
| Turtle Beach Ear Force P11 Headset                                                                | 1         | 0.47%   |
| RODE Microphones RODE NT-USB                                                                      | 1         | 0.47%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.47%   |
| Phison Electronics SoundYou Voyage                                                                | 1         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.47%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.47%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.47%   |
| Jieli Technology UACDemoV1.0                                                                      | 1         | 0.47%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.47%   |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 0.47%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                                                   | 1         | 0.47%   |
| Corsair VOID ELITE Wireless Gaming Dongle                                                         | 1         | 0.47%   |
| Corsair HS70 Pro Wireless Gaming Headset                                                          | 1         | 0.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.47%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 29.41%  |
| SK Hynix            | 23        | 19.33%  |
| Micron Technology   | 15        | 12.61%  |
| Crucial             | 12        | 10.08%  |
| Kingston            | 7         | 5.88%   |
| Unknown             | 4         | 3.36%   |
| Ramaxel Technology  | 4         | 3.36%   |
| Nanya Technology    | 3         | 2.52%   |
| Corsair             | 3         | 2.52%   |
| A-DATA Technology   | 3         | 2.52%   |
| Unknown (ABCD)      | 2         | 1.68%   |
| Smart               | 2         | 1.68%   |
| Transcend           | 1         | 0.84%   |
| Patriot             | 1         | 0.84%   |
| G.Skill             | 1         | 0.84%   |
| CSX                 | 1         | 0.84%   |
| Avant               | 1         | 0.84%   |
| 48spaces            | 1         | 0.84%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 4%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 4%      |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 2.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.4%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 2.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 2         | 1.6%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.6%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.6%    |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.6%    |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 1.6%    |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.8%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.8%    |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.8%    |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.8%    |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.8%    |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.8%    |
| SK Hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.8%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.8%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 0.8%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.8%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.8%    |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1600MT/s            | 1         | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.8%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.8%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.8%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.8%    |
| Samsung RAM K4E6E304EE-EGCF 4096MB SODIMM LPDDR3 1867MT/s        | 1         | 0.8%    |
| Samsung RAM K4E6E304EE-EGCF 4096MB Chip LPDDR3 1867MT/s          | 1         | 0.8%    |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 0.8%    |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB Row Of Chips DDR4 3200MT/s  | 1         | 0.8%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 0.8%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 0.8%    |
| Patriot RAM PSD38G16002S 8GB SODIMM DDR3 1600MT/s                | 1         | 0.8%    |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s             | 1         | 0.8%    |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 1         | 0.8%    |
| Micron RAM MT53E2G32D4NQ-046 16GB SODIMM LPDDR4 4266MT/s         | 1         | 0.8%    |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.8%    |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 1         | 0.8%    |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s            | 1         | 0.8%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 61        | 62.24%  |
| DDR3   | 27        | 27.55%  |
| LPDDR4 | 5         | 5.1%    |
| LPDDR3 | 3         | 3.06%   |
| DDR2   | 2         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 88.12%  |
| Row Of Chips | 10        | 9.9%    |
| Chip         | 1         | 0.99%   |
| Unknown      | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 57        | 53.77%  |
| 4096  | 32        | 30.19%  |
| 16384 | 13        | 12.26%  |
| 2048  | 4         | 3.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 29        | 27.1%   |
| 2667  | 28        | 26.17%  |
| 1600  | 22        | 20.56%  |
| 2400  | 10        | 9.35%   |
| 4266  | 3         | 2.8%    |
| 3266  | 3         | 2.8%    |
| 1334  | 3         | 2.8%    |
| 2133  | 2         | 1.87%   |
| 1867  | 2         | 1.87%   |
| 1333  | 2         | 1.87%   |
| 1866  | 1         | 0.93%   |
| 800   | 1         | 0.93%   |
| 667   | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Kyocera             | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series  | 1         | 33.33%  |
| Kyocera FS-1030D printer        | 1         | 33.33%  |
| HP LaserJet 200 colorMFP M275nw | 1         | 33.33%  |

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
| Chicony Electronics                    | 31        | 25.62%  |
| IMC Networks                           | 17        | 14.05%  |
| Microdia                               | 11        | 9.09%   |
| Acer                                   | 10        | 8.26%   |
| Realtek Semiconductor                  | 9         | 7.44%   |
| Quanta                                 | 7         | 5.79%   |
| Sunplus Innovation Technology          | 6         | 4.96%   |
| Syntek                                 | 4         | 3.31%   |
| Luxvisions Innotech Limited            | 4         | 3.31%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.31%   |
| Apple                                  | 3         | 2.48%   |
| Suyin                                  | 2         | 1.65%   |
| Silicon Motion                         | 2         | 1.65%   |
| Microsoft                              | 2         | 1.65%   |
| Lite-On Technology                     | 2         | 1.65%   |
| WaveRider Communications               | 1         | 0.83%   |
| Sonix Technology                       | 1         | 0.83%   |
| Samsung Electronics                    | 1         | 0.83%   |
| Logitech                               | 1         | 0.83%   |
| Lenovo                                 | 1         | 0.83%   |
| Importek                               | 1         | 0.83%   |
| Genesys Logic                          | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 8         | 6.56%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 8         | 6.56%   |
| Chicony Integrated Camera                            | 7         | 5.74%   |
| IMC Networks Integrated Camera                       | 6         | 4.92%   |
| Syntek Integrated Camera                             | 4         | 3.28%   |
| Chicony HD WebCam                                    | 4         | 3.28%   |
| Chicony HD User Facing                               | 4         | 3.28%   |
| Sunplus Integrated_Webcam_HD                         | 3         | 2.46%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 2.46%   |
| Acer HD Webcam                                       | 3         | 2.46%   |
| Quanta HP Wide Vision HD Camera                      | 2         | 1.64%   |
| Lite-On HP Wide Vision HD Camera                     | 2         | 1.64%   |
| IMC Networks HD Camera                               | 2         | 1.64%   |
| Chicony USB 2.0 Camera                               | 2         | 1.64%   |
| Chicony HP Wide Vision HD Camera                     | 2         | 1.64%   |
| Chicony EasyCamera                                   | 2         | 1.64%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 1.64%   |
| Acer Integrated Camera                               | 2         | 1.64%   |
| WaveRider USB 2.0 Camera                             | 1         | 0.82%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.82%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.82%   |
| Sunplus MTD Camera                                   | 1         | 0.82%   |
| Sunplus Integrated Webcam                            | 1         | 0.82%   |
| Sunplus Integrated Camera                            | 1         | 0.82%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 0.82%   |
| Silicon Motion WebCam SCB-1100N                      | 1         | 0.82%   |
| Silicon Motion Web Camera                            | 1         | 0.82%   |
| Samsung Galaxy A5 (MTP)                              | 1         | 0.82%   |
| Realtek USB Camera                                   | 1         | 0.82%   |
| Realtek Lenovo EasyCamera                            | 1         | 0.82%   |
| Realtek Integrated_Webcam_HD                         | 1         | 0.82%   |
| Realtek Integrated Webcam                            | 1         | 0.82%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.82%   |
| Realtek HD WebCam                                    | 1         | 0.82%   |
| Realtek EasyCamera                                   | 1         | 0.82%   |
| Realtek Built-In Video Camera                        | 1         | 0.82%   |
| Realtek Acer 640 x 480 laptop camera                 | 1         | 0.82%   |
| Quanta WEBCAM                                        | 1         | 0.82%   |
| Quanta USB2.0 VGA UVC WebCam                         | 1         | 0.82%   |
| Quanta USB HD Webcam                                 | 1         | 0.82%   |
| Quanta HD User Facing                                | 1         | 0.82%   |
| Quanta HD Camera                                     | 1         | 0.82%   |
| Microsoft Modern Webcam                              | 1         | 0.82%   |
| Microsoft LifeCam HD-3000                            | 1         | 0.82%   |
| Microdia Webcam Vitade AF                            | 1         | 0.82%   |
| Microdia PC Microscope camera                        | 1         | 0.82%   |
| Microdia HP Webcam-101                               | 1         | 0.82%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.82%   |
| Logitech Webcam Pro 9000                             | 1         | 0.82%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 0.82%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 0.82%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 0.82%   |
| Genesys Logic USB 2.0 Camera                         | 1         | 0.82%   |
| Chicony USB2.0 VGA UVC WebCam                        | 1         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 0.82%   |
| Chicony USB2.0 Camera                                | 1         | 0.82%   |
| Chicony TOSHIBA Web Camera - HD                      | 1         | 0.82%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 0.82%   |
| Chicony HP Webcam [2 MP Macro]                       | 1         | 0.82%   |
| Chicony HP Truevision HD                             | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 25%     |
| Shenzhen Goodix Technology | 5         | 20.83%  |
| Elan Microelectronics      | 5         | 20.83%  |
| Synaptics                  | 4         | 16.67%  |
| LighTuning Technology      | 2         | 8.33%   |
| AuthenTec                  | 2         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 3         | 12.5%   |
| Elan ELAN:ARM-M4                                  | 3         | 12.5%   |
| Validity Sensors Synaptics WBDI                   | 2         | 8.33%   |
| Elan ELAN:Fingerprint                             | 2         | 8.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 4.17%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 4.17%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 4.17%   |
| Synaptics WBDI Device                             | 1         | 4.17%   |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 4.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 4.17%   |
| Shenzhen Goodix FingerPrint                       | 1         | 4.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 4.17%   |
| AuthenTec AES2810                                 | 1         | 4.17%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 72.73%  |
| Upek        | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 36.36%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Broadcom 5880                                                                | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 64        | 47.76%  |
| 2     | 33        | 24.63%  |
| 0     | 32        | 23.88%  |
| 3     | 4         | 2.99%   |
| 4     | 1         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 85        | 57.43%  |
| Fingerprint reader       | 24        | 16.22%  |
| Chipcard                 | 11        | 7.43%   |
| Graphics card            | 8         | 5.41%   |
| Net/wireless             | 5         | 3.38%   |
| Net/ethernet             | 4         | 2.7%    |
| Multimedia controller    | 4         | 2.7%    |
| Storage                  | 2         | 1.35%   |
| Camera                   | 2         | 1.35%   |
| Wireless                 | 1         | 0.68%   |
| Network                  | 1         | 0.68%   |
| Bluetooth                | 1         | 0.68%   |

