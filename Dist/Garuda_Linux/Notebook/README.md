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

Total: 185

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Dell          | Latitude E7250              | [d31f6b8a4a](https://linux-hardware.org/?probe=d31f6b8a4a) | Apr 01, 2022 |
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
| Notebook      | P7xxDM2                     | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
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
| Lenovo        | LEGION 5 15IMH05 82AU       | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
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
| Dell          | XPS L702X                   | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | XPS L702X                   | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| HP            | EliteBook 8540p             | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| HP            | EliteBook 8540p             | [9dececac24](https://linux-hardware.org/?probe=9dececac24) | Feb 11, 2021 |
| HP            | EliteBook 8540p             | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | EliteBook 8540p             | [23cece38ed](https://linux-hardware.org/?probe=23cece38ed) | Feb 02, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Dell          | Latitude E6520              | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| Dell          | XPS 15 9500                 | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| HP            | EliteBook 8540p             | [c504347399](https://linux-hardware.org/?probe=c504347399) | Jan 23, 2021 |
| HP            | EliteBook 8540p             | [643af77934](https://linux-hardware.org/?probe=643af77934) | Jan 18, 2021 |
| HP            | Compaq 6735b                | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| HP            | EliteBook 8540p             | [86c3c2d1d3](https://linux-hardware.org/?probe=86c3c2d1d3) | Jan 12, 2021 |
| Unknown       | Unknown                     | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| HP            | EliteBook 8540p             | [ad733c377c](https://linux-hardware.org/?probe=ad733c377c) | Jan 09, 2021 |
| HP            | EliteBook 8540p             | [d4206bf424](https://linux-hardware.org/?probe=d4206bf424) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| Dell          | Latitude E6430              | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
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
| Garuda Linux Soaring | 95        | 76%     |
| Garuda Linux         | 30        | 24%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Garuda Linux | 125       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.17.1-zen1-1-zen           | 4         | 2.9%    |
| 5.16.16-zen1-1-zen          | 4         | 2.9%    |
| 5.14.14-zen1-1-zen          | 4         | 2.9%    |
| 5.13.13-zen1-1-zen          | 4         | 2.9%    |
| 5.16.4-zen1-1-zen           | 3         | 2.17%   |
| 5.16.2-zen1-1-zen           | 3         | 2.17%   |
| 5.15.6-zen2-1-zen           | 3         | 2.17%   |
| 5.15.2-zen1-1-zen           | 3         | 2.17%   |
| 5.15.12-zen1-1-zen          | 3         | 2.17%   |
| 5.14.6-zen1-1-zen           | 3         | 2.17%   |
| 5.13.9-zen1-1-zen           | 3         | 2.17%   |
| 5.11.11-zen1-1-zen          | 3         | 2.17%   |
| 5.10.1-103-tkg-bmq          | 3         | 2.17%   |
| 5.17.3-zen1-1-zen           | 2         | 1.45%   |
| 5.16.8-arch1-1              | 2         | 1.45%   |
| 5.16.5-zen1-1-zen           | 2         | 1.45%   |
| 5.16.14-zen1-1-zen          | 2         | 1.45%   |
| 5.16.1-zen1-1-zen           | 2         | 1.45%   |
| 5.15.5-zen1-1-zen           | 2         | 1.45%   |
| 5.15.4-zen1-1-zen           | 2         | 1.45%   |
| 5.15.13-zen1-1-zen          | 2         | 1.45%   |
| 5.14.9-zen2-1-zen           | 2         | 1.45%   |
| 5.14.15-zen1-1-zen          | 2         | 1.45%   |
| 5.13.5-zen1-1-zen           | 2         | 1.45%   |
| 5.12.9-zen1-1-zen           | 2         | 1.45%   |
| 5.12.15-zen1-1-zen          | 2         | 1.45%   |
| 5.11.16-zen1-1-zen          | 2         | 1.45%   |
| 5.10.2-104-tkg-bmq          | 2         | 1.45%   |
| 5.10.15-120-tkg-bmq         | 2         | 1.45%   |
| 5.10.10-115-tkg-bmq         | 2         | 1.45%   |
| 5.9.9-zen1-1-zen            | 1         | 0.72%   |
| 5.9.8-zen1-1-zen            | 1         | 0.72%   |
| 5.9.2-zen1-1-zen            | 1         | 0.72%   |
| 5.9.10-zen1-1-zen           | 1         | 0.72%   |
| 5.6.6-zen1-1-zen            | 1         | 0.72%   |
| 5.4.97-120-tkg-bmq          | 1         | 0.72%   |
| 5.17.5-zen1-1-zen           | 1         | 0.72%   |
| 5.17.3-xanmod1-1            | 1         | 0.72%   |
| 5.17.2-zen3-1-zen           | 1         | 0.72%   |
| 5.17.1-arch1-g14-1          | 1         | 0.72%   |
| 5.16.9-zen1-1-zen           | 1         | 0.72%   |
| 5.16.11-zen1-1-zen          | 1         | 0.72%   |
| 5.16.0-rc5-1-mainline-anbox | 1         | 0.72%   |
| 5.15.7-zen1-1-zen           | 1         | 0.72%   |
| 5.15.7-arch1-1              | 1         | 0.72%   |
| 5.15.3-zen1-1-zen           | 1         | 0.72%   |
| 5.15.22-1-lts               | 1         | 0.72%   |
| 5.15.19-1-lts               | 1         | 0.72%   |
| 5.15.18-1-lts               | 1         | 0.72%   |
| 5.15.11-zen1-1-zen          | 1         | 0.72%   |
| 5.15.11-230-tkg-cfs         | 1         | 0.72%   |
| 5.15.10-zen1-1-zen          | 1         | 0.72%   |
| 5.14.8-zen1-1-zen           | 1         | 0.72%   |
| 5.14.7-zen1-1-zen           | 1         | 0.72%   |
| 5.14.5-zen2-1-zen           | 1         | 0.72%   |
| 5.14.2-zen1-2-zen           | 1         | 0.72%   |
| 5.14.16-zen1-1-zen          | 1         | 0.72%   |
| 5.14.12-zen1-1-zen          | 1         | 0.72%   |
| 5.14.11-arch1-1             | 1         | 0.72%   |
| 5.13.4-zen1-1-zen           | 1         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 5         | 3.62%   |
| 5.16.16 | 4         | 2.9%    |
| 5.14.14 | 4         | 2.9%    |
| 5.13.13 | 4         | 2.9%    |
| 5.11.11 | 4         | 2.9%    |
| 5.17.3  | 3         | 2.17%   |
| 5.16.4  | 3         | 2.17%   |
| 5.16.2  | 3         | 2.17%   |
| 5.15.6  | 3         | 2.17%   |
| 5.15.2  | 3         | 2.17%   |
| 5.15.12 | 3         | 2.17%   |
| 5.14.6  | 3         | 2.17%   |
| 5.13.9  | 3         | 2.17%   |
| 5.12.9  | 3         | 2.17%   |
| 5.10.15 | 3         | 2.17%   |
| 5.10.1  | 3         | 2.17%   |
| 5.16.8  | 2         | 1.45%   |
| 5.16.5  | 2         | 1.45%   |
| 5.16.14 | 2         | 1.45%   |
| 5.16.1  | 2         | 1.45%   |
| 5.15.7  | 2         | 1.45%   |
| 5.15.5  | 2         | 1.45%   |
| 5.15.4  | 2         | 1.45%   |
| 5.15.13 | 2         | 1.45%   |
| 5.15.11 | 2         | 1.45%   |
| 5.14.9  | 2         | 1.45%   |
| 5.14.15 | 2         | 1.45%   |
| 5.13.5  | 2         | 1.45%   |
| 5.12.15 | 2         | 1.45%   |
| 5.11.6  | 2         | 1.45%   |
| 5.11.16 | 2         | 1.45%   |
| 5.10.4  | 2         | 1.45%   |
| 5.10.2  | 2         | 1.45%   |
| 5.10.12 | 2         | 1.45%   |
| 5.10.10 | 2         | 1.45%   |
| 5.9.9   | 1         | 0.72%   |
| 5.9.8   | 1         | 0.72%   |
| 5.9.2   | 1         | 0.72%   |
| 5.9.10  | 1         | 0.72%   |
| 5.6.6   | 1         | 0.72%   |
| 5.4.97  | 1         | 0.72%   |
| 5.17.5  | 1         | 0.72%   |
| 5.17.2  | 1         | 0.72%   |
| 5.16.9  | 1         | 0.72%   |
| 5.16.11 | 1         | 0.72%   |
| 5.16.0  | 1         | 0.72%   |
| 5.15.3  | 1         | 0.72%   |
| 5.15.22 | 1         | 0.72%   |
| 5.15.19 | 1         | 0.72%   |
| 5.15.18 | 1         | 0.72%   |
| 5.15.10 | 1         | 0.72%   |
| 5.14.8  | 1         | 0.72%   |
| 5.14.7  | 1         | 0.72%   |
| 5.14.5  | 1         | 0.72%   |
| 5.14.2  | 1         | 0.72%   |
| 5.14.16 | 1         | 0.72%   |
| 5.14.12 | 1         | 0.72%   |
| 5.14.11 | 1         | 0.72%   |
| 5.13.4  | 1         | 0.72%   |
| 5.13.1  | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 17.91%  |
| 5.16    | 21        | 15.67%  |
| 5.10    | 20        | 14.93%  |
| 5.14    | 18        | 13.43%  |
| 5.12    | 12        | 8.96%   |
| 5.11    | 12        | 8.96%   |
| 5.13    | 11        | 8.21%   |
| 5.17    | 10        | 7.46%   |
| 5.9     | 4         | 2.99%   |
| 5.6     | 1         | 0.75%   |
| 5.4     | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 125       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 76        | 60.32%  |
| GNOME             | 19        | 15.08%  |
| KDE               | 12        | 9.52%   |
| XFCE              | 8         | 6.35%   |
| X-Cinnamon        | 2         | 1.59%   |
| sway              | 2         | 1.59%   |
| qtile-default     | 2         | 1.59%   |
| Deepin            | 2         | 1.59%   |
| Yaru:ubuntu:GNOME | 1         | 0.79%   |
| MATE              | 1         | 0.79%   |
| i3                | 1         | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 115       | 92%     |
| Wayland | 8         | 6.4%    |
| Tty     | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 70        | 55.56%  |
| Unknown | 33        | 26.19%  |
| LightDM | 11        | 8.73%   |
| GDM     | 11        | 8.73%   |
| GREETD  | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 61        | 48.41%  |
| en_GB   | 19        | 15.08%  |
| en_IN   | 11        | 8.73%   |
| it_IT   | 6         | 4.76%   |
| de_DE   | 6         | 4.76%   |
| pt_BR   | 3         | 2.38%   |
| es_MX   | 3         | 2.38%   |
| ru_RU   | 2         | 1.59%   |
| pl_PL   | 2         | 1.59%   |
| fi_FI   | 2         | 1.59%   |
| es_CO   | 2         | 1.59%   |
| tr_TR   | 1         | 0.79%   |
| sv_SE   | 1         | 0.79%   |
| nl_NL   | 1         | 0.79%   |
| ko_KR   | 1         | 0.79%   |
| es_VE   | 1         | 0.79%   |
| es_ES   | 1         | 0.79%   |
| en_ZA   | 1         | 0.79%   |
| de_AT   | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 89        | 70.63%  |
| BIOS | 37        | 29.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 124       | 99.2%   |
| F2fs  | 1         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 86        | 68.8%   |
| Unknown | 30        | 24%     |
| MBR     | 9         | 7.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 92.8%   |
| Yes       | 9         | 7.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 67.2%   |
| Yes       | 41        | 32.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 31        | 24.8%   |
| Hewlett-Packard     | 19        | 15.2%   |
| Dell                | 17        | 13.6%   |
| ASUSTek Computer    | 14        | 11.2%   |
| Acer                | 11        | 8.8%    |
| MSI                 | 7         | 5.6%    |
| Notebook            | 3         | 2.4%    |
| Toshiba             | 2         | 1.6%    |
| Samsung Electronics | 2         | 1.6%    |
| Razer               | 2         | 1.6%    |
| Medion              | 2         | 1.6%    |
| Apple               | 2         | 1.6%    |
| Unknown             | 2         | 1.6%    |
| Sony                | 1         | 0.8%    |
| PC Specialist       | 1         | 0.8%    |
| Panasonic           | 1         | 0.8%    |
| HUAWEI              | 1         | 0.8%    |
| HONOR               | 1         | 0.8%    |
| GPU Company         | 1         | 0.8%    |
| Google              | 1         | 0.8%    |
| Fujitsu Siemens     | 1         | 0.8%    |
| Chuwi               | 1         | 0.8%    |
| Casper              | 1         | 0.8%    |
| Alienware           | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 3         | 2.4%    |
| Unknown                                    | 3         | 2.4%    |
| Lenovo ThinkPad W530 24474KG               | 2         | 1.6%    |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 1.6%    |
| Dell Inspiron 15 7000 Gaming               | 2         | 1.6%    |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 1.6%    |
| Acer Nitro AN515-44                        | 2         | 1.6%    |
| Toshiba Satellite E45DW-C                  | 1         | 0.8%    |
| Toshiba Satellite C55-A                    | 1         | 0.8%    |
| Sony VPCSB1C5E                             | 1         | 0.8%    |
| Samsung 550XCJ/550XCR                      | 1         | 0.8%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.8%    |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.8%    |
| Razer Blade                                | 1         | 0.8%    |
| PC Specialist GK5NPFO                      | 1         | 0.8%    |
| Panasonic CF-191HYAX1M                     | 1         | 0.8%    |
| Notebook W54_W550SU2                       | 1         | 0.8%    |
| Notebook P7xxDM2(-G)                       | 1         | 0.8%    |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.8%    |
| MSI GS76 Stealth 11UG                      | 1         | 0.8%    |
| MSI GP75 Leopard 9SD                       | 1         | 0.8%    |
| MSI GF63 Thin 9SC                          | 1         | 0.8%    |
| MSI GF63 Thin 10SC                         | 1         | 0.8%    |
| MSI GE75 Raider 9SE                        | 1         | 0.8%    |
| MSI GE72VR 6RF                             | 1         | 0.8%    |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.8%    |
| Medion P861X                               | 1         | 0.8%    |
| Medion E7419 MD60025                       | 1         | 0.8%    |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.8%    |
| Lenovo ThinkPad X1 Carbon 4th 20FB005WUS   | 1         | 0.8%    |
| Lenovo ThinkPad T530 24296KG               | 1         | 0.8%    |
| Lenovo ThinkPad T510 4384WB4               | 1         | 0.8%    |
| Lenovo ThinkPad T470s 20HGS0B900           | 1         | 0.8%    |
| Lenovo ThinkPad T470 20HD000RUS            | 1         | 0.8%    |
| Lenovo ThinkPad T440p 20AWS58F00           | 1         | 0.8%    |
| Lenovo ThinkPad T440p 20AWS4RC00           | 1         | 0.8%    |
| Lenovo ThinkPad T14 Gen 1 20UDS00N00       | 1         | 0.8%    |
| Lenovo ThinkPad S3 Yoga 14 20DM008FSC      | 1         | 0.8%    |
| Lenovo ThinkPad P1 20MDS00P00              | 1         | 0.8%    |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 0.8%    |
| Lenovo Legion S7 15ACH6 82K8               | 1         | 0.8%    |
| Lenovo Legion 7 15IMH05 81YT               | 1         | 0.8%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 1         | 0.8%    |
| Lenovo Legion 5 15IMH05H 81Y6              | 1         | 0.8%    |
| Lenovo LEGION 5 15IMH05 82AU               | 1         | 0.8%    |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 0.8%    |
| Lenovo IdeaPad S340-15API 81NC             | 1         | 0.8%    |
| Lenovo IdeaPad S340-14API 81NB             | 1         | 0.8%    |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 1         | 0.8%    |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 0.8%    |
| Lenovo IdeaPad 3 15ADA05 81W1              | 1         | 0.8%    |
| Lenovo IdeaPad 110-15ACL 80TJ              | 1         | 0.8%    |
| Lenovo G510 20238                          | 1         | 0.8%    |
| HUAWEI HVY-WXX9                            | 1         | 0.8%    |
| HONOR HLYL-WXX9                            | 1         | 0.8%    |
| HP ProBook 640 G1                          | 1         | 0.8%    |
| HP Pavilion Laptop 15z-eh100               | 1         | 0.8%    |
| HP Pavilion Laptop 15-eh0xxx               | 1         | 0.8%    |
| HP Pavilion Laptop 15-cs0xxx               | 1         | 0.8%    |
| HP Pavilion Gaming Laptop 15-dk0xxx        | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 12        | 9.6%    |
| Lenovo IdeaPad          | 10        | 8%      |
| HP Pavilion             | 7         | 5.6%    |
| Dell Inspiron           | 7         | 5.6%    |
| Lenovo LEGION           | 5         | 4%      |
| Dell Latitude           | 5         | 4%      |
| Acer Aspire             | 5         | 4%      |
| HP Laptop               | 4         | 3.2%    |
| Dell XPS                | 4         | 3.2%    |
| Acer Nitro              | 4         | 3.2%    |
| HP OMEN                 | 3         | 2.4%    |
| ASUS ROG                | 3         | 2.4%    |
| Unknown                 | 3         | 2.4%    |
| Toshiba Satellite       | 2         | 1.6%    |
| Razer Blade             | 2         | 1.6%    |
| MSI GF63                | 2         | 1.6%    |
| HP EliteBook            | 2         | 1.6%    |
| ASUS VivoBook           | 2         | 1.6%    |
| ASUS TUF                | 2         | 1.6%    |
| ASUS ASUS               | 2         | 1.6%    |
| Sony VPCSB1C5E          | 1         | 0.8%    |
| Samsung 550XCJ          | 1         | 0.8%    |
| Samsung 300V3A          | 1         | 0.8%    |
| PC Specialist GK5NPFO   | 1         | 0.8%    |
| Panasonic CF-191HYAX1M  | 1         | 0.8%    |
| Notebook W54            | 1         | 0.8%    |
| Notebook P7xxDM2(-G)    | 1         | 0.8%    |
| Notebook N85            | 1         | 0.8%    |
| MSI GS76                | 1         | 0.8%    |
| MSI GP75                | 1         | 0.8%    |
| MSI GE75                | 1         | 0.8%    |
| MSI GE72VR              | 1         | 0.8%    |
| MSI GE63                | 1         | 0.8%    |
| Medion P861X            | 1         | 0.8%    |
| Medion E7419            | 1         | 0.8%    |
| Lenovo Yoga             | 1         | 0.8%    |
| Lenovo ThinkBook        | 1         | 0.8%    |
| Lenovo G510             | 1         | 0.8%    |
| HUAWEI HVY-WXX9         | 1         | 0.8%    |
| HONOR HLYL-WXX9         | 1         | 0.8%    |
| HP ProBook              | 1         | 0.8%    |
| HP Compaq               | 1         | 0.8%    |
| HP 450                  | 1         | 0.8%    |
| GPU Company GWTN156-11  | 1         | 0.8%    |
| Google Kindred          | 1         | 0.8%    |
| Fujitsu Siemens ESPRIMO | 1         | 0.8%    |
| Dell Precision          | 1         | 0.8%    |
| Chuwi GemiBook          | 1         | 0.8%    |
| Casper EXCALIBUR        | 1         | 0.8%    |
| ASUS X550ZE             | 1         | 0.8%    |
| ASUS X550CC             | 1         | 0.8%    |
| ASUS K53SD              | 1         | 0.8%    |
| ASUS GL503VM            | 1         | 0.8%    |
| ASUS G750JZ             | 1         | 0.8%    |
| Apple MacBookPro9       | 1         | 0.8%    |
| Apple MacBookPro12      | 1         | 0.8%    |
| Alienware 17            | 1         | 0.8%    |
| Acer TravelMate         | 1         | 0.8%    |
| Acer Swift              | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 26        | 20.8%   |
| 2021 | 18        | 14.4%   |
| 2019 | 14        | 11.2%   |
| 2017 | 12        | 9.6%    |
| 2016 | 11        | 8.8%    |
| 2018 | 9         | 7.2%    |
| 2013 | 8         | 6.4%    |
| 2012 | 7         | 5.6%    |
| 2014 | 5         | 4%      |
| 2011 | 5         | 4%      |
| 2015 | 3         | 2.4%    |
| 2010 | 2         | 1.6%    |
| 2009 | 2         | 1.6%    |
| 2007 | 2         | 1.6%    |
| 2008 | 1         | 0.8%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 125       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 125       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 99.2%   |
| Yes  | 1         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 38        | 30.16%  |
| 16.01-24.0 | 34        | 26.98%  |
| 8.01-16.0  | 31        | 24.6%   |
| 3.01-4.0   | 11        | 8.73%   |
| 32.01-64.0 | 8         | 6.35%   |
| 24.01-32.0 | 3         | 2.38%   |
| 2.01-3.0   | 1         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 46        | 34.33%  |
| 2.01-3.0  | 35        | 26.12%  |
| 3.01-4.0  | 34        | 25.37%  |
| 1.01-2.0  | 10        | 7.46%   |
| 8.01-16.0 | 8         | 5.97%   |
| 0.51-1.0  | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 57.81%  |
| 2      | 42        | 32.81%  |
| 3      | 11        | 8.59%   |
| 4      | 1         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 77.34%  |
| Yes       | 29        | 22.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 77.6%   |
| No        | 28        | 22.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 98.4%   |
| No        | 2         | 1.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 88%     |
| No        | 15        | 12%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 34        | 26.98%  |
| UK           | 12        | 9.52%   |
| India        | 11        | 8.73%   |
| Germany      | 11        | 8.73%   |
| Italy        | 8         | 6.35%   |
| Poland       | 4         | 3.17%   |
| Mexico       | 4         | 3.17%   |
| Brazil       | 4         | 3.17%   |
| Romania      | 3         | 2.38%   |
| Finland      | 3         | 2.38%   |
| Turkey       | 2         | 1.59%   |
| Sweden       | 2         | 1.59%   |
| Spain        | 2         | 1.59%   |
| Russia       | 2         | 1.59%   |
| Netherlands  | 2         | 1.59%   |
| Colombia     | 2         | 1.59%   |
| Canada       | 2         | 1.59%   |
| Venezuela    | 1         | 0.79%   |
| Switzerland  | 1         | 0.79%   |
| South Korea  | 1         | 0.79%   |
| South Africa | 1         | 0.79%   |
| Slovenia     | 1         | 0.79%   |
| Singapore    | 1         | 0.79%   |
| Serbia       | 1         | 0.79%   |
| Luxembourg   | 1         | 0.79%   |
| Kuwait       | 1         | 0.79%   |
| Kenya        | 1         | 0.79%   |
| Hungary      | 1         | 0.79%   |
| France       | 1         | 0.79%   |
| Denmark      | 1         | 0.79%   |
| Czechia      | 1         | 0.79%   |
| China        | 1         | 0.79%   |
| Belgium      | 1         | 0.79%   |
| Bahrain      | 1         | 0.79%   |
| Austria      | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| London               | 4         | 3.03%   |
| Portland             | 2         | 1.52%   |
| Helsinki             | 2         | 1.52%   |
| Bryansk              | 2         | 1.52%   |
| Berlin               | 2         | 1.52%   |
| Winston-Salem        | 1         | 0.76%   |
| Welwyn Garden City   | 1         | 0.76%   |
| Warsaw               | 1         | 0.76%   |
| Vufflens-la-Ville    | 1         | 0.76%   |
| Viganello            | 1         | 0.76%   |
| Vienna               | 1         | 0.76%   |
| Valenzano            | 1         | 0.76%   |
| Valencia             | 1         | 0.76%   |
| Turku                | 1         | 0.76%   |
| Turin                | 1         | 0.76%   |
| Tucson               | 1         | 0.76%   |
| Toronto              | 1         | 0.76%   |
| TimiИ™oara        | 1         | 0.76%   |
| Sunrise Beach        | 1         | 0.76%   |
| Spring Hill          | 1         | 0.76%   |
| Spitalfields         | 1         | 0.76%   |
| Southampton          | 1         | 0.76%   |
| Singapore            | 1         | 0.76%   |
| Sighetu MarmaÅ£iei | 1         | 0.76%   |
| San Jose             | 1         | 0.76%   |
| San Francisco        | 1         | 0.76%   |
| Reno                 | 1         | 0.76%   |
| Qalali               | 1         | 0.76%   |
| Pune                 | 1         | 0.76%   |
| Puebla City          | 1         | 0.76%   |
| Poznan               | 1         | 0.76%   |
| Pompano Beach        | 1         | 0.76%   |
| Pitalito             | 1         | 0.76%   |
| Phoenix              | 1         | 0.76%   |
| Palmer               | 1         | 0.76%   |
| Oxford               | 1         | 0.76%   |
| Owings Mills         | 1         | 0.76%   |
| Olympia              | 1         | 0.76%   |
| New Delhi            | 1         | 0.76%   |
| New Baltimore        | 1         | 0.76%   |
| Nairobi              | 1         | 0.76%   |
| MГјnster           | 1         | 0.76%   |
| Mostoles             | 1         | 0.76%   |
| Montreal             | 1         | 0.76%   |
| Milan                | 1         | 0.76%   |
| Mexico City          | 1         | 0.76%   |
| Manning              | 1         | 0.76%   |
| Malatya              | 1         | 0.76%   |
| Luxembourg           | 1         | 0.76%   |
| Lucknow              | 1         | 0.76%   |
| Lubnjow              | 1         | 0.76%   |
| Lochristi            | 1         | 0.76%   |
| Ljubljana            | 1         | 0.76%   |
| Leyton               | 1         | 0.76%   |
| Leesville            | 1         | 0.76%   |
| Lancaster            | 1         | 0.76%   |
| Kuwait City          | 1         | 0.76%   |
| Koszalin             | 1         | 0.76%   |
| Kolkata              | 1         | 0.76%   |
| Kirkland             | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 32        | 40     | 17.11%  |
| Seagate                   | 23        | 24     | 12.3%   |
| WDC                       | 20        | 21     | 10.7%   |
| SK Hynix                  | 12        | 14     | 6.42%   |
| Sandisk                   | 11        | 14     | 5.88%   |
| Toshiba                   | 10        | 12     | 5.35%   |
| HGST                      | 9         | 9      | 4.81%   |
| Unknown                   | 8         | 8      | 4.28%   |
| Kingston                  | 6         | 6      | 3.21%   |
| Intel                     | 5         | 6      | 2.67%   |
| Crucial                   | 5         | 8      | 2.67%   |
| Micron Technology         | 4         | 4      | 2.14%   |
| Silicon Motion            | 3         | 3      | 1.6%    |
| PNY                       | 3         | 3      | 1.6%    |
| LITEON                    | 3         | 3      | 1.6%    |
| Hitachi                   | 3         | 3      | 1.6%    |
| Corsair                   | 3         | 3      | 1.6%    |
| Union Memory (Shenzhen)   | 2         | 2      | 1.07%   |
| Phison                    | 2         | 2      | 1.07%   |
| KIOXIA                    | 2         | 3      | 1.07%   |
| China                     | 2         | 2      | 1.07%   |
| WDC WDS                   | 1         | 1      | 0.53%   |
| VisionTek                 | 1         | 2      | 0.53%   |
| UMIS                      | 1         | 1      | 0.53%   |
| SSSTC                     | 1         | 1      | 0.53%   |
| SPCC                      | 1         | 1      | 0.53%   |
| ShanDianZhe               | 1         | 1      | 0.53%   |
| SABRENT                   | 1         | 2      | 0.53%   |
| PNY CS90                  | 1         | 1      | 0.53%   |
| Phison Electronics        | 1         | 1      | 0.53%   |
| Netac                     | 1         | 1      | 0.53%   |
| Mushkin                   | 1         | 1      | 0.53%   |
| Micron/Crucial Technology | 1         | 1      | 0.53%   |
| LITEONIT                  | 1         | 1      | 0.53%   |
| Lenovo                    | 1         | 1      | 0.53%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.53%   |
| Intenso                   | 1         | 1      | 0.53%   |
| FORESEE                   | 1         | 1      | 0.53%   |
| ASMT                      | 1         | 1      | 0.53%   |
| A-DATA Technology         | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB               | 5         | 2.58%   |
| Seagate ST1000LM035-1RK172 1TB               | 5         | 2.58%   |
| Samsung NVMe SSD Drive 1TB                   | 4         | 2.06%   |
| Toshiba MQ01ABD100 1TB                       | 3         | 1.55%   |
| Samsung SSD 860 EVO 1TB                      | 3         | 1.55%   |
| HGST HTS721010A9E630 1TB                     | 3         | 1.55%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB         | 2         | 1.03%   |
| Unknown MMC Card  16GB                       | 2         | 1.03%   |
| SK Hynix SC311 SATA 256GB SSD                | 2         | 1.03%   |
| Seagate ST2000LM015-2E8174 2TB               | 2         | 1.03%   |
| Seagate ST1000LM048-2E7172 1TB               | 2         | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 1.03%   |
| Seagate ST1000LM014-1EJ164 1TB               | 2         | 1.03%   |
| Samsung SSD 870 QVO 1TB                      | 2         | 1.03%   |
| Samsung SSD 870 EVO 500GB                    | 2         | 1.03%   |
| Samsung NVMe SSD Drive 256GB                 | 2         | 1.03%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD         | 2         | 1.03%   |
| PNY ELITE PSSD 480GB                         | 2         | 1.03%   |
| KIOXIA NVMe SSD Drive 512GB                  | 2         | 1.03%   |
| Intel SSDPEKNW010T8 1TB                      | 2         | 1.03%   |
| HGST HTS725050A7E630 500GB                   | 2         | 1.03%   |
| HGST HTS541075A9E680 752GB                   | 2         | 1.03%   |
| Corsair Force MP300 960GB                    | 2         | 1.03%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 0.52%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1         | 0.52%   |
| WDC WDS 500G2B0B-00YS70 500GB SSD            | 1         | 0.52%   |
| WDC WDBNCE5000PNC 500GB SSD                  | 1         | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 0.52%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 0.52%   |
| WDC WD5000BEVT-60A0RT0 500GB                 | 1         | 0.52%   |
| WDC WD10JPVX-11JC3T0 1TB                     | 1         | 0.52%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB           | 1         | 0.52%   |
| WDC PC SN530 SDBPTPZ-512G-1002 512GB         | 1         | 0.52%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB           | 1         | 0.52%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB         | 1         | 0.52%   |
| WDC PC SN530 SDBPNPZ-256G-1032 256GB         | 1         | 0.52%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB         | 1         | 0.52%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB         | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB         | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-128G-1006 128GB         | 1         | 0.52%   |
| WDC PC SN520 SDAPNUW-128G                    | 1         | 0.52%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB         | 1         | 0.52%   |
| VisionTek SSD 120GB                          | 1         | 0.52%   |
| Unknown SL64G  64GB                          | 1         | 0.52%   |
| Unknown SF256  256GB                         | 1         | 0.52%   |
| Unknown SD/MMC/MS PRO 16GB                   | 1         | 0.52%   |
| Unknown MMC128  128GB                        | 1         | 0.52%   |
| Unknown DA4128  128GB                        | 1         | 0.52%   |
| Unknown APPSD  16GB                          | 1         | 0.52%   |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 1         | 0.52%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.52%   |
| UMIS RPFTJ256PDD2MWX 256GB                   | 1         | 0.52%   |
| Toshiba THNSNJ128G8NY 128GB SSD              | 1         | 0.52%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.52%   |
| Toshiba MQ02ABD100H 1TB                      | 1         | 0.52%   |
| Toshiba KXG60ZNV1T02 NVMe KIOXIA 1024GB      | 1         | 0.52%   |
| Toshiba KBG40ZNT512G MEMORY 512GB            | 1         | 0.52%   |
| Toshiba KBG30ZMV256G 256GB                   | 1         | 0.52%   |
| Toshiba HDWL110 1TB                          | 1         | 0.52%   |
| SSSTC CA5-8D512 512GB                        | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 22        | 22     | 47.83%  |
| HGST    | 9         | 9      | 19.57%  |
| Toshiba | 5         | 7      | 10.87%  |
| WDC     | 4         | 4      | 8.7%    |
| Hitachi | 3         | 3      | 6.52%   |
| Unknown | 1         | 1      | 2.17%   |
| SABRENT | 1         | 2      | 2.17%   |
| ASMT    | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 29.09%  |
| SanDisk             | 5         | 8      | 9.09%   |
| Kingston            | 4         | 4      | 7.27%   |
| Crucial             | 4         | 7      | 7.27%   |
| WDC                 | 3         | 4      | 5.45%   |
| SK Hynix            | 3         | 4      | 5.45%   |
| PNY                 | 3         | 3      | 5.45%   |
| LITEON              | 3         | 3      | 5.45%   |
| China               | 2         | 2      | 3.64%   |
| WDC WDS             | 1         | 1      | 1.82%   |
| VisionTek           | 1         | 2      | 1.82%   |
| Toshiba             | 1         | 1      | 1.82%   |
| PNY CS90            | 1         | 1      | 1.82%   |
| Netac               | 1         | 1      | 1.82%   |
| Mushkin             | 1         | 1      | 1.82%   |
| LITEONIT            | 1         | 1      | 1.82%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.82%   |
| Intenso             | 1         | 1      | 1.82%   |
| FORESEE             | 1         | 1      | 1.82%   |
| Corsair             | 1         | 1      | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 66        | 84     | 38.6%   |
| SSD     | 51        | 67     | 29.82%  |
| HDD     | 43        | 49     | 25.15%  |
| MMC     | 8         | 8      | 4.68%   |
| Unknown | 3         | 3      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 75        | 103    | 46.3%   |
| NVMe | 66        | 84     | 40.74%  |
| SAS  | 13        | 16     | 8.02%   |
| MMC  | 8         | 8      | 4.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 59     | 51.55%  |
| 0.51-1.0   | 43        | 53     | 44.33%  |
| 1.01-2.0   | 4         | 4      | 4.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 45        | 35.71%  |
| 1001-2000      | 26        | 20.63%  |
| 501-1000       | 24        | 19.05%  |
| 2001-3000      | 14        | 11.11%  |
| Unknown        | 8         | 6.35%   |
| 251-500        | 5         | 3.97%   |
| 101-250        | 2         | 1.59%   |
| 1-20           | 2         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 30.3%   |
| 251-500        | 26        | 19.7%   |
| 51-100         | 19        | 14.39%  |
| 1001-2000      | 16        | 12.12%  |
| 501-1000       | 15        | 11.36%  |
| Unknown        | 8         | 6.06%   |
| More than 3000 | 3         | 2.27%   |
| 2001-3000      | 3         | 2.27%   |
| 1-20           | 2         | 1.52%   |

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
| Works    | 78        | 109    | 54.55%  |
| Detected | 57        | 94     | 39.86%  |
| Malfunc  | 8         | 8      | 5.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 80        | 46.78%  |
| AMD                            | 22        | 12.87%  |
| Samsung Electronics            | 17        | 9.94%   |
| Sandisk                        | 16        | 9.36%   |
| SK Hynix                       | 9         | 5.26%   |
| Phison Electronics             | 6         | 3.51%   |
| Union Memory (Shenzhen)        | 3         | 1.75%   |
| Toshiba America Info Systems   | 3         | 1.75%   |
| Silicon Motion                 | 3         | 1.75%   |
| Micron Technology              | 3         | 1.75%   |
| Micron/Crucial Technology      | 2         | 1.17%   |
| KIOXIA                         | 2         | 1.17%   |
| Kingston Technology Company    | 2         | 1.17%   |
| Solid State Storage Technology | 1         | 0.58%   |
| Nvidia                         | 1         | 0.58%   |
| Lenovo                         | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 21        | 11.93%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 11        | 6.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 5.68%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 9         | 5.11%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 8         | 4.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 8         | 4.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 8         | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 5         | 2.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 5         | 2.84%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 4         | 2.27%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 2.27%   |
| Phison E12 NVMe Controller                                                             | 4         | 2.27%   |
| Intel SSD 660P Series                                                                  | 4         | 2.27%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 3         | 1.7%    |
| SK Hynix Gold P31 SSD                                                                  | 3         | 1.7%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 3         | 1.7%    |
| Micron Non-Volatile memory controller                                                  | 3         | 1.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.7%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 1.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 1.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 1.7%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 1.14%   |
| Sandisk Non-Volatile memory controller                                                 | 2         | 1.14%   |
| Phison NVMe Storage Controller                                                         | 2         | 1.14%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 2         | 1.14%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 2         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.57%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 0.57%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 0.57%   |
| SK Hynix BC511                                                                         | 1         | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.57%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 1         | 0.57%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 0.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.57%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.57%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.57%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.57%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.57%   |
| Lenovo Non-Volatile memory controller                                                  | 1         | 0.57%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.57%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 0.57%   |
| Intel Non-Volatile memory controller                                                   | 1         | 0.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 86        | 52.12%  |
| NVMe | 64        | 38.79%  |
| RAID | 12        | 7.27%   |
| IDE  | 3         | 1.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 69.6%   |
| AMD    | 38        | 30.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 5.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 4.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 4%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 4%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 3.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.4%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 2.4%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 2.4%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 2.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.6%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.6%    |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 1.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.6%    |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.6%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.6%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.6%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.6%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.8%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.8%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.8%    |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.8%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.8%    |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.8%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.8%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.8%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.8%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.8%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.8%    |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.8%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.8%    |
| Intel Core i7 CPU Q 840 @ 1.87GHz             | 1         | 0.8%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.8%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.8%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 0.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.8%    |
| Intel Core i5-5257U CPU @ 2.70GHz             | 1         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.8%    |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 0.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.8%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.8%    |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.8%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 0.8%    |
| Intel Core i3-2365M CPU @ 1.40GHz             | 1         | 0.8%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 0.8%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 0.8%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 0.8%    |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 0.8%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 0.8%    |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 41        | 32.8%   |
| Intel Core i5           | 23        | 18.4%   |
| AMD Ryzen 7             | 13        | 10.4%   |
| AMD Ryzen 5             | 12        | 9.6%    |
| Other                   | 6         | 4.8%    |
| Intel Core i3           | 6         | 4.8%    |
| Intel Celeron           | 5         | 4%      |
| AMD Ryzen 9             | 3         | 2.4%    |
| Intel Pentium Silver    | 2         | 1.6%    |
| Intel Pentium           | 2         | 1.6%    |
| Intel Core 2 Duo        | 2         | 1.6%    |
| AMD Ryzen 7 PRO         | 2         | 1.6%    |
| Intel Pentium Dual-Core | 1         | 0.8%    |
| Intel Core m3           | 1         | 0.8%    |
| AMD Turion              | 1         | 0.8%    |
| AMD FX                  | 1         | 0.8%    |
| AMD A8                  | 1         | 0.8%    |
| AMD A6                  | 1         | 0.8%    |
| AMD A4                  | 1         | 0.8%    |
| AMD A10                 | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 36%     |
| 4      | 41        | 32.8%   |
| 6      | 22        | 17.6%   |
| 8      | 17        | 13.6%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 125       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 107       | 85.6%   |
| 1      | 18        | 14.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 125       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 34.38%  |
| 0x906ea    | 6         | 4.69%   |
| 0x306a9    | 6         | 4.69%   |
| 0xa0652    | 5         | 3.91%   |
| 0x906e9    | 5         | 3.91%   |
| 0x206a7    | 5         | 3.91%   |
| 0x0a50000c | 5         | 3.91%   |
| 0x306c3    | 4         | 3.13%   |
| 0x08600103 | 4         | 3.13%   |
| 0x806e9    | 3         | 2.34%   |
| 0x08600106 | 3         | 2.34%   |
| 0x08600104 | 3         | 2.34%   |
| 0x08108102 | 3         | 2.34%   |
| 0x806ec    | 2         | 1.56%   |
| 0x806ea    | 2         | 1.56%   |
| 0x506e3    | 2         | 1.56%   |
| 0x406e3    | 2         | 1.56%   |
| 0x40651    | 2         | 1.56%   |
| 0x106e5    | 2         | 1.56%   |
| 0x08608103 | 2         | 1.56%   |
| 0x08108109 | 2         | 1.56%   |
| 0x06006705 | 2         | 1.56%   |
| 0xa0660    | 1         | 0.78%   |
| 0x806c1    | 1         | 0.78%   |
| 0x706e5    | 1         | 0.78%   |
| 0x706a8    | 1         | 0.78%   |
| 0x706a1    | 1         | 0.78%   |
| 0x506c9    | 1         | 0.78%   |
| 0x406c4    | 1         | 0.78%   |
| 0x20655    | 1         | 0.78%   |
| 0x1067a    | 1         | 0.78%   |
| 0x10676    | 1         | 0.78%   |
| 0x0a50000b | 1         | 0.78%   |
| 0x08101007 | 1         | 0.78%   |
| 0x0700010f | 1         | 0.78%   |
| 0x06006110 | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 28        | 22.4%   |
| Zen 2           | 13        | 10.4%   |
| CometLake       | 9         | 7.2%    |
| Zen 3           | 8         | 6.4%    |
| IvyBridge       | 8         | 6.4%    |
| Haswell         | 8         | 6.4%    |
| Skylake         | 7         | 5.6%    |
| SandyBridge     | 7         | 5.6%    |
| Zen+            | 6         | 4.8%    |
| TigerLake       | 3         | 2.4%    |
| Penryn          | 3         | 2.4%    |
| Goldmont plus   | 3         | 2.4%    |
| Excavator       | 3         | 2.4%    |
| Broadwell       | 3         | 2.4%    |
| Unknown         | 3         | 2.4%    |
| Silvermont      | 2         | 1.6%    |
| Puma            | 2         | 1.6%    |
| Nehalem         | 2         | 1.6%    |
| Zen             | 1         | 0.8%    |
| Westmere        | 1         | 0.8%    |
| Steamroller     | 1         | 0.8%    |
| K8 & K10 hybrid | 1         | 0.8%    |
| Jaguar          | 1         | 0.8%    |
| IceLake         | 1         | 0.8%    |
| Goldmont        | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 43.41%  |
| Nvidia | 62        | 34.07%  |
| AMD    | 41        | 22.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                | 13        | 6.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 10        | 5.29%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 8         | 4.23%   |
| AMD Cezanne                                                               | 8         | 4.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 7         | 3.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 6         | 3.17%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 5         | 2.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 5         | 2.65%   |
| Intel HD Graphics 630                                                     | 5         | 2.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 2.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 4         | 2.12%   |
| Nvidia TU117M                                                             | 4         | 2.12%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 4         | 2.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 2.12%   |
| Intel HD Graphics 620                                                     | 4         | 2.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 3         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.59%   |
| Intel UHD Graphics 620                                                    | 3         | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 1.59%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 2         | 1.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.06%   |
| Intel HD Graphics 5500                                                    | 2         | 1.06%   |
| Intel HD Graphics 530                                                     | 2         | 1.06%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1.06%   |
| AMD Lucienne                                                              | 2         | 1.06%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.53%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.53%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.53%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                    | 1         | 0.53%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.53%   |
| Nvidia GT215GLM [Quadro FX 1800M]                                         | 1         | 0.53%   |
| Nvidia Graphics Device                                                    | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                               | 1         | 0.53%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.53%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                  | 1         | 0.53%   |
| Nvidia GM204M [GeForce GTX 970M]                                          | 1         | 0.53%   |
| Nvidia GM204 [GeForce GTX 980]                                            | 1         | 0.53%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.53%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.53%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.53%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.53%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.53%   |
| Nvidia GK104M [GeForce GTX 880M]                                          | 1         | 0.53%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.53%   |
| Nvidia GF106M [GeForce GT 550M]                                           | 1         | 0.53%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 0.53%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.53%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 0.53%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 0.53%   |
| Nvidia C79 [GeForce 9100M G]                                              | 1         | 0.53%   |
| Intel UHD Graphics 615                                                    | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 39        | 31.2%   |
| Intel + Nvidia     | 35        | 28%     |
| 1 x AMD            | 19        | 15.2%   |
| AMD + Nvidia       | 17        | 13.6%   |
| 1 x Nvidia         | 8         | 6.4%    |
| Intel + AMD        | 3         | 2.4%    |
| 2 x AMD            | 2         | 1.6%    |
| Intel + 2 x Nvidia | 2         | 1.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 79        | 62.7%   |
| Proprietary | 47        | 37.3%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 64.06%  |
| 0.01-0.5   | 23        | 17.97%  |
| 1.01-2.0   | 10        | 7.81%   |
| 5.01-6.0   | 5         | 3.91%   |
| 3.01-4.0   | 5         | 3.91%   |
| 0.51-1.0   | 2         | 1.56%   |
| 7.01-8.0   | 1         | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 21.38%  |
| LG Display              | 23        | 15.86%  |
| Chimei Innolux          | 19        | 13.1%   |
| BOE                     | 19        | 13.1%   |
| Samsung Electronics     | 10        | 6.9%    |
| Sharp                   | 7         | 4.83%   |
| PANDA                   | 7         | 4.83%   |
| Lenovo                  | 4         | 2.76%   |
| Dell                    | 3         | 2.07%   |
| Goldstar                | 2         | 1.38%   |
| CSO                     | 2         | 1.38%   |
| Apple                   | 2         | 1.38%   |
| AOC                     | 2         | 1.38%   |
| Acer                    | 2         | 1.38%   |
| Sony                    | 1         | 0.69%   |
| Philips                 | 1         | 0.69%   |
| MStar                   | 1         | 0.69%   |
| Mi                      | 1         | 0.69%   |
| InfoVision              | 1         | 0.69%   |
| Hewlett-Packard         | 1         | 0.69%   |
| G-Story                 | 1         | 0.69%   |
| Eizo                    | 1         | 0.69%   |
| CPT                     | 1         | 0.69%   |
| Chi Mei Optoelectronics | 1         | 0.69%   |
| BenQ                    | 1         | 0.69%   |
| ASUSTek Computer        | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 2.76%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 1.38%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 2         | 1.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.38%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.38%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 2         | 1.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.38%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 1.38%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 2         | 1.38%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.38%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 1.38%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.69%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.69%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.69%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.69%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch     | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 1         | 0.69%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1         | 0.69%   |
| Philips 272P4 PHL08C5 2560x1440 597x336mm 27.0-inch                   | 1         | 0.69%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.69%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.69%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 1         | 0.69%   |
| LG Display LCD Monitor LGD065A 1920x1080 340x190mm 15.3-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD04CC 1366x768 309x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD046A 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD03FE 1920x1080 345x194mm 15.6-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD01AF 1680x1050 331x207mm 15.4-inch          | 1         | 0.69%   |
| Lenovo LEN L27q-10 LEN65CE 2560x1440 597x336mm 27.0-inch              | 1         | 0.69%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch               | 1         | 0.69%   |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 77        | 57.04%  |
| 1366x768 (WXGA)    | 21        | 15.56%  |
| 1600x900 (HD+)     | 8         | 5.93%   |
| 3840x2160 (4K)     | 5         | 3.7%    |
| 2560x1440 (QHD)    | 4         | 2.96%   |
| 2560x1600          | 3         | 2.22%   |
| 1920x1200 (WUXGA)  | 3         | 2.22%   |
| 1680x1050 (WSXGA+) | 3         | 2.22%   |
| 1280x800 (WXGA)    | 2         | 1.48%   |
| 3840x2400          | 1         | 0.74%   |
| 3440x1440          | 1         | 0.74%   |
| 3200x1800 (QHD+)   | 1         | 0.74%   |
| 2880x1440          | 1         | 0.74%   |
| 2256x1504          | 1         | 0.74%   |
| 2160x1440          | 1         | 0.74%   |
| 1680x945           | 1         | 0.74%   |
| 1600x1200          | 1         | 0.74%   |
| 1440x900 (WXGA+)   | 1         | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 74        | 51.39%  |
| 14      | 16        | 11.11%  |
| 13      | 13        | 9.03%   |
| 17      | 10        | 6.94%   |
| 27      | 4         | 2.78%   |
| 16      | 4         | 2.78%   |
| 23      | 3         | 2.08%   |
| 21      | 3         | 2.08%   |
| 18      | 3         | 2.08%   |
| 31      | 2         | 1.39%   |
| 22      | 2         | 1.39%   |
| Unknown | 2         | 1.39%   |
| 72      | 1         | 0.69%   |
| 54      | 1         | 0.69%   |
| 52      | 1         | 0.69%   |
| 34      | 1         | 0.69%   |
| 24      | 1         | 0.69%   |
| 20      | 1         | 0.69%   |
| 12      | 1         | 0.69%   |
| 11      | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 98        | 68.06%  |
| 351-400     | 12        | 8.33%   |
| 401-500     | 9         | 6.25%   |
| 201-300     | 9         | 6.25%   |
| 501-600     | 8         | 5.56%   |
| 601-700     | 2         | 1.39%   |
| 1001-1500   | 2         | 1.39%   |
| Unknown     | 2         | 1.39%   |
| 701-800     | 1         | 0.69%   |
| 1501-2000   | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 114       | 86.36%  |
| 16/10 | 13        | 9.85%   |
| 3/2   | 2         | 1.52%   |
| 4/3   | 1         | 0.76%   |
| 21/9  | 1         | 0.76%   |
| 2.00  | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 75        | 52.08%  |
| 81-90          | 25        | 17.36%  |
| 121-130        | 10        | 6.94%   |
| 201-250        | 7         | 4.86%   |
| 71-80          | 4         | 2.78%   |
| 301-350        | 4         | 2.78%   |
| More than 1000 | 3         | 2.08%   |
| 351-500        | 3         | 2.08%   |
| 141-150        | 3         | 2.08%   |
| 151-200        | 2         | 1.39%   |
| 111-120        | 2         | 1.39%   |
| Unknown        | 2         | 1.39%   |
| 61-70          | 1         | 0.69%   |
| 51-60          | 1         | 0.69%   |
| 251-300        | 1         | 0.69%   |
| 91-100         | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 79        | 56.03%  |
| 101-120       | 31        | 21.99%  |
| 51-100        | 14        | 9.93%   |
| 161-240       | 8         | 5.67%   |
| More than 240 | 4         | 2.84%   |
| 1-50          | 3         | 2.13%   |
| Unknown       | 2         | 1.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 99        | 77.95%  |
| 2     | 27        | 21.26%  |
| 0     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 72        | 35.29%  |
| Intel                             | 70        | 34.31%  |
| Qualcomm Atheros                  | 32        | 15.69%  |
| Broadcom                          | 9         | 4.41%   |
| MEDIATEK                          | 3         | 1.47%   |
| Samsung Electronics               | 2         | 0.98%   |
| Qualcomm                          | 2         | 0.98%   |
| Xiaomi                            | 1         | 0.49%   |
| Wacom                             | 1         | 0.49%   |
| TP-Link                           | 1         | 0.49%   |
| Sierra Wireless                   | 1         | 0.49%   |
| Ralink Technology                 | 1         | 0.49%   |
| OnePlus                           | 1         | 0.49%   |
| Nvidia                            | 1         | 0.49%   |
| NetGear                           | 1         | 0.49%   |
| Lenovo                            | 1         | 0.49%   |
| Ericsson Business Mobile Networks | 1         | 0.49%   |
| DisplayLink                       | 1         | 0.49%   |
| Dell                              | 1         | 0.49%   |
| ASUSTek Computer                  | 1         | 0.49%   |
| ASIX Electronics                  | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 48        | 20.17%  |
| Intel Wi-Fi 6 AX200                                                     | 15        | 6.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 3.36%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 3.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 2.52%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.1%    |
| Intel Wireless 3165                                                     | 5         | 2.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 4         | 1.68%   |
| Intel Wireless 7260                                                     | 4         | 1.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.26%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                                | 3         | 1.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.84%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.84%   |
| Intel Wireless 8260                                                     | 2         | 0.84%   |
| Intel Wireless 7265                                                     | 2         | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.84%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.84%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.84%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 2         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.42%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                | 1         | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.42%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.42%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.42%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.42%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 1         | 0.42%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.42%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.42%   |
| Qualcomm Mobile Router                                                  | 1         | 0.42%   |
| Qualcomm Mi A1                                                          | 1         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.42%   |
| OnePlus IN2017                                                          | 1         | 0.42%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.42%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.42%   |
| MediaTek WiFi                                                           | 1         | 0.42%   |
| Lenovo ThinkPad Lan                                                     | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 51.15%  |
| Qualcomm Atheros      | 26        | 19.85%  |
| Realtek Semiconductor | 20        | 15.27%  |
| Broadcom              | 8         | 6.11%   |
| MediaTek              | 3         | 2.29%   |
| Wacom                 | 1         | 0.76%   |
| TP-Link               | 1         | 0.76%   |
| Sierra Wireless       | 1         | 0.76%   |
| Ralink Technology     | 1         | 0.76%   |
| NetGear               | 1         | 0.76%   |
| Dell                  | 1         | 0.76%   |
| ASUSTek Computer      | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 15        | 11.36%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 6.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 6.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.55%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.79%   |
| Intel Wireless 3165                                                     | 5         | 3.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 3.03%   |
| Intel Wireless 7260                                                     | 4         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.27%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.52%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.52%   |
| Intel Wireless 8260                                                     | 2         | 1.52%   |
| Intel Wireless 7265                                                     | 2         | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.52%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.52%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                | 1         | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.76%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.76%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.76%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.76%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.76%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.76%   |
| MediaTek WiFi                                                           | 1         | 0.76%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.76%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.76%   |
| Intel Centrino Wireless-N 100                                           | 1         | 0.76%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.76%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 1         | 0.76%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 0.76%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 0.76%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.76%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]          | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 62        | 59.62%  |
| Intel                 | 20        | 19.23%  |
| Qualcomm Atheros      | 10        | 9.62%   |
| Broadcom              | 3         | 2.88%   |
| Samsung Electronics   | 2         | 1.92%   |
| Qualcomm              | 2         | 1.92%   |
| Xiaomi                | 1         | 0.96%   |
| Nvidia                | 1         | 0.96%   |
| Lenovo                | 1         | 0.96%   |
| DisplayLink           | 1         | 0.96%   |
| ASIX Electronics      | 1         | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 46.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 3.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 2.88%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.92%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.92%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.96%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.96%   |
| Qualcomm Mobile Router                                            | 1         | 0.96%   |
| Qualcomm Mi A1                                                    | 1         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.96%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.96%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.96%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.96%   |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 55.41%  |
| Ethernet | 97        | 43.69%  |
| Modem    | 1         | 0.45%   |
| Unknown  | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 72.99%  |
| Ethernet | 37        | 27.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 89        | 71.2%   |
| 1     | 34        | 27.2%   |
| 3     | 1         | 0.8%    |
| 0     | 1         | 0.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 77.95%  |
| Yes  | 28        | 22.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 49.11%  |
| Qualcomm Atheros Communications | 19        | 16.96%  |
| Realtek Semiconductor           | 13        | 11.61%  |
| IMC Networks                    | 6         | 5.36%   |
| Lite-On Technology              | 4         | 3.57%   |
| Broadcom                        | 4         | 3.57%   |
| Foxconn / Hon Hai               | 3         | 2.68%   |
| Hewlett-Packard                 | 2         | 1.79%   |
| Dell                            | 2         | 1.79%   |
| Apple                           | 2         | 1.79%   |
| Realtek                         | 1         | 0.89%   |
| Cambridge Silicon Radio         | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 15        | 13.39%  |
| Intel Bluetooth wireless interface                                                  | 14        | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 12        | 10.71%  |
| Intel Bluetooth Device                                                              | 10        | 8.93%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 5.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 5.36%   |
| Realtek Bluetooth Radio                                                             | 5         | 4.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.79%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.79%   |
| Intel AX210 Bluetooth                                                               | 2         | 1.79%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.79%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.79%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.89%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.89%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.89%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.89%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.89%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.89%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.89%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.89%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.89%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.89%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.89%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.89%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.89%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 86        | 52.44%  |
| AMD                   | 38        | 23.17%  |
| Nvidia                | 30        | 18.29%  |
| Corsair               | 2         | 1.22%   |
| Turtle Beach          | 1         | 0.61%   |
| RODE Microphones      | 1         | 0.61%   |
| Realtek Semiconductor | 1         | 0.61%   |
| Phison Electronics    | 1         | 0.61%   |
| JMTek                 | 1         | 0.61%   |
| Huawei Technologies   | 1         | 0.61%   |
| GN Netcom             | 1         | 0.61%   |
| BR25                  | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 29        | 14.5%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 6.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 6%      |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 5.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 4.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 4%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 3%      |
| Intel CM238 HD Audio Controller                                                                   | 6         | 3%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 2%      |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2%      |
| AMD FCH Azalia Controller                                                                         | 4         | 2%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.5%    |
| Nvidia Audio device                                                                               | 3         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.5%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.5%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.5%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.5%    |
| Nvidia High Definition Audio Controller                                                           | 2         | 1%      |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 1%      |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 1%      |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1%      |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 1%      |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1%      |
| AMD High Definition Audio Controller                                                              | 2         | 1%      |
| Turtle Beach Ear Force P11 Headset                                                                | 1         | 0.5%    |
| RODE Microphones RODE NT-USB                                                                      | 1         | 0.5%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.5%    |
| Phison Electronics SoundYou Voyage                                                                | 1         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.5%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.5%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.5%    |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.5%    |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 0.5%    |
| GN Netcom Jabra EVOLVE 20 MS                                                                      | 1         | 0.5%    |
| Corsair VOID ELITE Wireless Gaming Dongle                                                         | 1         | 0.5%    |
| Corsair HS70 Pro Wireless Gaming Headset                                                          | 1         | 0.5%    |
| BR25 UACDemoV1.0                                                                                  | 1         | 0.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.5%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 27.83%  |
| SK Hynix            | 22        | 19.13%  |
| Micron Technology   | 15        | 13.04%  |
| Crucial             | 12        | 10.43%  |
| Kingston            | 7         | 6.09%   |
| Unknown             | 4         | 3.48%   |
| Ramaxel Technology  | 4         | 3.48%   |
| Nanya Technology    | 3         | 2.61%   |
| Corsair             | 3         | 2.61%   |
| A-DATA Technology   | 3         | 2.61%   |
| Unknown (ABCD)      | 2         | 1.74%   |
| Smart               | 2         | 1.74%   |
| Transcend           | 1         | 0.87%   |
| Patriot             | 1         | 0.87%   |
| G.Skill             | 1         | 0.87%   |
| CSX                 | 1         | 0.87%   |
| Avant               | 1         | 0.87%   |
| 48spaces            | 1         | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 4.13%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 5         | 4.13%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 2.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 2.48%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 2.48%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 1.65%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.65%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 2         | 1.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.65%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s          | 2         | 1.65%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.83%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.83%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.83%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.83%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.83%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8192MB Row Of Chips DDR4 2667MT/s  | 1         | 0.83%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s        | 1         | 0.83%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.83%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 0.83%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.83%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.83%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 0.83%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.83%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 0.83%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s           | 1         | 0.83%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s             | 1         | 0.83%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB Row Of Chips DDR4 3200MT/s  | 1         | 0.83%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 0.83%   |
| Patriot RAM PSD38G16002S 8GB SODIMM DDR3 1600MT/s                | 1         | 0.83%   |
| Nanya RAM NT8GA64D88CX3S-JR 8192MB SODIMM DDR4 3200MT/s          | 1         | 0.83%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 1         | 0.83%   |
| Micron RAM MT53E2G32D4NQ-046 16GB SODIMM LPDDR4 4266MT/s         | 1         | 0.83%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 0.83%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 1         | 0.83%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s            | 1         | 0.83%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 1         | 0.83%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 60        | 63.16%  |
| DDR3   | 26        | 27.37%  |
| LPDDR4 | 5         | 5.26%   |
| LPDDR3 | 2         | 2.11%   |
| DDR2   | 2         | 2.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 88.78%  |
| Row Of Chips | 9         | 9.18%   |
| Chip         | 1         | 1.02%   |
| Unknown      | 1         | 1.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 53.4%   |
| 4096  | 31        | 30.1%   |
| 16384 | 13        | 12.62%  |
| 2048  | 4         | 3.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 29        | 27.88%  |
| 2667  | 28        | 26.92%  |
| 1600  | 21        | 20.19%  |
| 2400  | 10        | 9.62%   |
| 4266  | 3         | 2.88%   |
| 1334  | 3         | 2.88%   |
| 3266  | 2         | 1.92%   |
| 1867  | 2         | 1.92%   |
| 1333  | 2         | 1.92%   |
| 2133  | 1         | 0.96%   |
| 1866  | 1         | 0.96%   |
| 800   | 1         | 0.96%   |
| 667   | 1         | 0.96%   |

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
| Chicony Electronics                    | 30        | 26.32%  |
| IMC Networks                           | 15        | 13.16%  |
| Microdia                               | 10        | 8.77%   |
| Acer                                   | 9         | 7.89%   |
| Realtek Semiconductor                  | 8         | 7.02%   |
| Quanta                                 | 7         | 6.14%   |
| Sunplus Innovation Technology          | 6         | 5.26%   |
| Syntek                                 | 4         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.51%   |
| Luxvisions Innotech Limited            | 3         | 2.63%   |
| Apple                                  | 3         | 2.63%   |
| Suyin                                  | 2         | 1.75%   |
| Silicon Motion                         | 2         | 1.75%   |
| Microsoft                              | 2         | 1.75%   |
| Lite-On Technology                     | 2         | 1.75%   |
| WaveRider Communications               | 1         | 0.88%   |
| Sonix Technology                       | 1         | 0.88%   |
| Samsung Electronics                    | 1         | 0.88%   |
| Logitech                               | 1         | 0.88%   |
| Lenovo                                 | 1         | 0.88%   |
| Importek                               | 1         | 0.88%   |
| Genesys Logic                          | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 7         | 6.09%   |
| Microdia Integrated_Webcam_HD                        | 6         | 5.22%   |
| IMC Networks Integrated Camera                       | 6         | 5.22%   |
| Chicony Integrated Camera                            | 6         | 5.22%   |
| Syntek Integrated Camera                             | 4         | 3.48%   |
| Chicony HD WebCam                                    | 4         | 3.48%   |
| Chicony HD User Facing                               | 4         | 3.48%   |
| Sunplus Integrated_Webcam_HD                         | 3         | 2.61%   |
| Acer HD Webcam                                       | 3         | 2.61%   |
| Quanta HP Wide Vision HD Camera                      | 2         | 1.74%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 1.74%   |
| Lite-On HP Wide Vision HD Camera                     | 2         | 1.74%   |
| Chicony USB 2.0 Camera                               | 2         | 1.74%   |
| Chicony HP Wide Vision HD Camera                     | 2         | 1.74%   |
| Chicony EasyCamera                                   | 2         | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 1.74%   |
| Acer Integrated Camera                               | 2         | 1.74%   |
| WaveRider USB Live camera                            | 1         | 0.87%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.87%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.87%   |
| Sunplus MTD Camera                                   | 1         | 0.87%   |
| Sunplus Integrated Webcam                            | 1         | 0.87%   |
| Sunplus Integrated Camera                            | 1         | 0.87%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 0.87%   |
| Silicon Motion WebCam SCB-1100N                      | 1         | 0.87%   |
| Silicon Motion Web Camera                            | 1         | 0.87%   |
| Samsung Galaxy A5 (MTP)                              | 1         | 0.87%   |
| Realtek USB Camera                                   | 1         | 0.87%   |
| Realtek Lenovo EasyCamera                            | 1         | 0.87%   |
| Realtek Integrated Webcam                            | 1         | 0.87%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.87%   |
| Realtek HD WebCam                                    | 1         | 0.87%   |
| Realtek EasyCamera                                   | 1         | 0.87%   |
| Realtek Built-In Video Camera                        | 1         | 0.87%   |
| Realtek Acer 640 x 480 laptop camera                 | 1         | 0.87%   |
| Quanta WEBCAM                                        | 1         | 0.87%   |
| Quanta USB2.0 VGA UVC WebCam                         | 1         | 0.87%   |
| Quanta USB HD Webcam                                 | 1         | 0.87%   |
| Quanta HD User Facing                                | 1         | 0.87%   |
| Quanta HD Camera                                     | 1         | 0.87%   |
| Microsoft Modern Webcam                              | 1         | 0.87%   |
| Microsoft LifeCam HD-3000                            | 1         | 0.87%   |
| Microdia Webcam Vitade AF                            | 1         | 0.87%   |
| Microdia PC Microscope camera                        | 1         | 0.87%   |
| Microdia Integrated Webcam HD                        | 1         | 0.87%   |
| Microdia HP Integrated Webcam                        | 1         | 0.87%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.87%   |
| Logitech Webcam Pro 9000                             | 1         | 0.87%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 0.87%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 0.87%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 0.87%   |
| IMC Networks HD Camera                               | 1         | 0.87%   |
| Genesys Logic USB 2.0 Camera                         | 1         | 0.87%   |
| Chicony USB2.0 VGA UVC WebCam                        | 1         | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                         | 1         | 0.87%   |
| Chicony USB2.0 Camera                                | 1         | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                      | 1         | 0.87%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 0.87%   |
| Chicony HP Webcam [2 MP Macro]                       | 1         | 0.87%   |
| Chicony HP Truevision HD                             | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 26.09%  |
| Shenzhen Goodix Technology | 5         | 21.74%  |
| Synaptics                  | 4         | 17.39%  |
| Elan Microelectronics      | 4         | 17.39%  |
| LighTuning Technology      | 2         | 8.7%    |
| AuthenTec                  | 2         | 8.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 3         | 13.04%  |
| Elan ELAN:ARM-M4                                  | 3         | 13.04%  |
| Validity Sensors Synaptics WBDI                   | 2         | 8.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 4.35%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 4.35%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 4.35%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 4.35%   |
| Synaptics WBDI Device                             | 1         | 4.35%   |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 4.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 4.35%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 4.35%   |
| Shenzhen Goodix FingerPrint                       | 1         | 4.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 4.35%   |
| Elan ELAN:Fingerprint                             | 1         | 4.35%   |
| AuthenTec AES2810                                 | 1         | 4.35%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 66.67%  |
| Upek        | 1         | 11.11%  |
| Lenovo      | 1         | 11.11%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 33.33%  |
| Broadcom 5880                                                                | 2         | 22.22%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 47.62%  |
| 2     | 31        | 24.6%   |
| 0     | 31        | 24.6%   |
| 3     | 3         | 2.38%   |
| 4     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 80        | 58.39%  |
| Fingerprint reader       | 23        | 16.79%  |
| Chipcard                 | 9         | 6.57%   |
| Graphics card            | 8         | 5.84%   |
| Net/wireless             | 4         | 2.92%   |
| Net/ethernet             | 4         | 2.92%   |
| Multimedia controller    | 3         | 2.19%   |
| Camera                   | 2         | 1.46%   |
| Wireless                 | 1         | 0.73%   |
| Storage                  | 1         | 0.73%   |
| Network                  | 1         | 0.73%   |
| Bluetooth                | 1         | 0.73%   |

