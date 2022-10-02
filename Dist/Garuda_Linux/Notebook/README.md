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

Total: 245

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Notebook                    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Fujitsu       | FMVA1200G                   | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Acer          | Aspire V5-552P              | [46395f51b5](https://linux-hardware.org/?probe=46395f51b5) | Sep 27, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| HP            | Notebook                    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Dell          | Precision 7510              | [5f94678049](https://linux-hardware.org/?probe=5f94678049) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| HP            | ProBook 470 G5              | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1cf1136fb8](https://linux-hardware.org/?probe=1cf1136fb8) | Sep 13, 2022 |
| Dell          | Inspiron 5548               | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [c1c2e05a86](https://linux-hardware.org/?probe=c1c2e05a86) | Sep 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| HP            | Victus by Gaming Laptop ... | [1a8681a1f5](https://linux-hardware.org/?probe=1a8681a1f5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Acer          | Aspire E5-573G              | [cfb1abc54b](https://linux-hardware.org/?probe=cfb1abc54b) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [87fac1a064](https://linux-hardware.org/?probe=87fac1a064) | Sep 02, 2022 |
| HP            | Laptop 15-da0xxx            | [2c79168e77](https://linux-hardware.org/?probe=2c79168e77) | Sep 01, 2022 |
| HP            | Laptop 15-da0xxx            | [40482ce9a3](https://linux-hardware.org/?probe=40482ce9a3) | Sep 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| HP            | Notebook                    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| MSI           | Sword 15 A11UD              | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| Acer          | Aspire A515-51G             | [9d271daa54](https://linux-hardware.org/?probe=9d271daa54) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [27eb779b2a](https://linux-hardware.org/?probe=27eb779b2a) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Dell          | Latitude E5450              | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| Dell          | Latitude E5450              | [2c6979fb39](https://linux-hardware.org/?probe=2c6979fb39) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | Pavilion dv6                | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7d5ee550de](https://linux-hardware.org/?probe=7d5ee550de) | Jul 04, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| HP            | Laptop 15-ef0xxx            | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Acer          | Swift SF315-41              | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
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
| Garuda Linux Soaring | 123       | 72.78%  |
| Garuda Linux         | 46        | 27.22%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Garuda Linux | 168       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.17.9-zen1-1-zen   | 6         | 3.14%   |
| 5.16.16-zen1-1-zen  | 4         | 2.09%   |
| 5.14.14-zen1-1-zen  | 4         | 2.09%   |
| 5.13.13-zen1-1-zen  | 4         | 2.09%   |
| 5.19.7-zen2-1-zen   | 3         | 1.57%   |
| 5.19.10-zen1-1-zen  | 3         | 1.57%   |
| 5.18.16-zen1-1-zen  | 3         | 1.57%   |
| 5.17.3-zen1-1-zen   | 3         | 1.57%   |
| 5.17.1-zen1-1-zen   | 3         | 1.57%   |
| 5.16.4-zen1-1-zen   | 3         | 1.57%   |
| 5.16.2-zen1-1-zen   | 3         | 1.57%   |
| 5.15.6-zen2-1-zen   | 3         | 1.57%   |
| 5.15.2-zen1-1-zen   | 3         | 1.57%   |
| 5.15.12-zen1-1-zen  | 3         | 1.57%   |
| 5.14.6-zen1-1-zen   | 3         | 1.57%   |
| 5.13.9-zen1-1-zen   | 3         | 1.57%   |
| 5.11.11-zen1-1-zen  | 3         | 1.57%   |
| 5.10.1-103-tkg-bmq  | 3         | 1.57%   |
| 5.19.2-zen1-1-zen   | 2         | 1.05%   |
| 5.19.11-zen1-1-zen  | 2         | 1.05%   |
| 5.18.6-zen1-1-zen   | 2         | 1.05%   |
| 5.18.3-zen1-1-zen   | 2         | 1.05%   |
| 5.18.14-zen1-1-zen  | 2         | 1.05%   |
| 5.17.5-zen1-1-zen   | 2         | 1.05%   |
| 5.16.8-arch1-1      | 2         | 1.05%   |
| 5.16.5-zen1-1-zen   | 2         | 1.05%   |
| 5.16.14-zen1-1-zen  | 2         | 1.05%   |
| 5.16.1-zen1-1-zen   | 2         | 1.05%   |
| 5.15.5-zen1-1-zen   | 2         | 1.05%   |
| 5.15.4-zen1-1-zen   | 2         | 1.05%   |
| 5.15.13-zen1-1-zen  | 2         | 1.05%   |
| 5.14.9-zen2-1-zen   | 2         | 1.05%   |
| 5.14.8-zen1-1-zen   | 2         | 1.05%   |
| 5.14.15-zen1-1-zen  | 2         | 1.05%   |
| 5.13.5-zen1-1-zen   | 2         | 1.05%   |
| 5.12.9-zen1-1-zen   | 2         | 1.05%   |
| 5.12.15-zen1-1-zen  | 2         | 1.05%   |
| 5.11.16-zen1-1-zen  | 2         | 1.05%   |
| 5.10.2-104-tkg-bmq  | 2         | 1.05%   |
| 5.10.15-120-tkg-bmq | 2         | 1.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.9  | 6         | 3.14%   |
| 5.18.16 | 5         | 2.62%   |
| 5.19.7  | 4         | 2.09%   |
| 5.17.3  | 4         | 2.09%   |
| 5.17.1  | 4         | 2.09%   |
| 5.16.16 | 4         | 2.09%   |
| 5.14.14 | 4         | 2.09%   |
| 5.13.13 | 4         | 2.09%   |
| 5.11.11 | 4         | 2.09%   |
| 5.19.2  | 3         | 1.57%   |
| 5.19.10 | 3         | 1.57%   |
| 5.18.3  | 3         | 1.57%   |
| 5.17.5  | 3         | 1.57%   |
| 5.16.4  | 3         | 1.57%   |
| 5.16.2  | 3         | 1.57%   |
| 5.15.6  | 3         | 1.57%   |
| 5.15.2  | 3         | 1.57%   |
| 5.15.12 | 3         | 1.57%   |
| 5.14.6  | 3         | 1.57%   |
| 5.13.9  | 3         | 1.57%   |
| 5.12.9  | 3         | 1.57%   |
| 5.10.15 | 3         | 1.57%   |
| 5.10.1  | 3         | 1.57%   |
| 5.19.6  | 2         | 1.05%   |
| 5.19.11 | 2         | 1.05%   |
| 5.18.6  | 2         | 1.05%   |
| 5.18.5  | 2         | 1.05%   |
| 5.18.14 | 2         | 1.05%   |
| 5.16.8  | 2         | 1.05%   |
| 5.16.5  | 2         | 1.05%   |
| 5.16.14 | 2         | 1.05%   |
| 5.16.1  | 2         | 1.05%   |
| 5.15.7  | 2         | 1.05%   |
| 5.15.5  | 2         | 1.05%   |
| 5.15.4  | 2         | 1.05%   |
| 5.15.13 | 2         | 1.05%   |
| 5.15.11 | 2         | 1.05%   |
| 5.14.9  | 2         | 1.05%   |
| 5.14.8  | 2         | 1.05%   |
| 5.14.15 | 2         | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 27        | 14.67%  |
| 5.16    | 21        | 11.41%  |
| 5.10    | 20        | 10.87%  |
| 5.19    | 19        | 10.33%  |
| 5.14    | 19        | 10.33%  |
| 5.18    | 18        | 9.78%   |
| 5.17    | 18        | 9.78%   |
| 5.12    | 12        | 6.52%   |
| 5.11    | 12        | 6.52%   |
| 5.13    | 11        | 5.98%   |
| 5.9     | 4         | 2.17%   |
| 6.0     | 1         | 0.54%   |
| 5.6     | 1         | 0.54%   |
| 5.4     | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 168       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 108       | 63.16%  |
| GNOME             | 23        | 13.45%  |
| KDE               | 12        | 7.02%   |
| XFCE              | 9         | 5.26%   |
| X-Cinnamon        | 5         | 2.92%   |
| sway              | 5         | 2.92%   |
| qtile-default     | 2         | 1.17%   |
| Deepin            | 2         | 1.17%   |
| Yaru:ubuntu:GNOME | 1         | 0.58%   |
| MATE              | 1         | 0.58%   |
| i3                | 1         | 0.58%   |
| awesome           | 1         | 0.58%   |
| Unknown           | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 150       | 88.76%  |
| Wayland | 14        | 8.28%   |
| Unknown | 4         | 2.37%   |
| Tty     | 1         | 0.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 87        | 50.88%  |
| Unknown | 49        | 28.65%  |
| LightDM | 18        | 10.53%  |
| GDM     | 14        | 8.19%   |
| GREETD  | 3         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 82        | 48.24%  |
| en_GB   | 21        | 12.35%  |
| en_IN   | 15        | 8.82%   |
| it_IT   | 8         | 4.71%   |
| de_DE   | 8         | 4.71%   |
| pt_BR   | 5         | 2.94%   |
| en_CA   | 4         | 2.35%   |
| ru_RU   | 3         | 1.76%   |
| pl_PL   | 3         | 1.76%   |
| es_MX   | 3         | 1.76%   |
| fi_FI   | 2         | 1.18%   |
| es_CO   | 2         | 1.18%   |
| uk_UA   | 1         | 0.59%   |
| tr_TR   | 1         | 0.59%   |
| sv_SE   | 1         | 0.59%   |
| nl_NL   | 1         | 0.59%   |
| ko_KR   | 1         | 0.59%   |
| ja_JP   | 1         | 0.59%   |
| es_VE   | 1         | 0.59%   |
| es_ES   | 1         | 0.59%   |
| es_EC   | 1         | 0.59%   |
| en_ZA   | 1         | 0.59%   |
| en_DK   | 1         | 0.59%   |
| en_AG   | 1         | 0.59%   |
| de_AT   | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 114       | 67.06%  |
| BIOS | 56        | 32.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 164       | 97.62%  |
| Overlay | 2         | 1.19%   |
| XXXXX   | 1         | 0.6%    |
| F2fs    | 1         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 111       | 65.68%  |
| Unknown | 48        | 28.4%   |
| MBR     | 10        | 5.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 157       | 92.9%   |
| Yes       | 12        | 7.1%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 68.24%  |
| Yes       | 54        | 31.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 38        | 22.62%  |
| Hewlett-Packard     | 27        | 16.07%  |
| ASUSTek Computer    | 24        | 14.29%  |
| Dell                | 23        | 13.69%  |
| Acer                | 17        | 10.12%  |
| MSI                 | 8         | 4.76%   |
| Samsung Electronics | 3         | 1.79%   |
| Razer               | 3         | 1.79%   |
| Notebook            | 3         | 1.79%   |
| Unknown             | 3         | 1.79%   |
| Toshiba             | 2         | 1.19%   |
| Medion              | 2         | 1.19%   |
| HUAWEI              | 2         | 1.19%   |
| Apple               | 2         | 1.19%   |
| Sony                | 1         | 0.6%    |
| PC Specialist       | 1         | 0.6%    |
| Panasonic           | 1         | 0.6%    |
| HONOR               | 1         | 0.6%    |
| GPU Company         | 1         | 0.6%    |
| Google              | 1         | 0.6%    |
| Fujitsu Siemens     | 1         | 0.6%    |
| Fujitsu             | 1         | 0.6%    |
| Chuwi               | 1         | 0.6%    |
| Casper              | 1         | 0.6%    |
| Alienware           | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 4         | 2.38%   |
| Unknown                                    | 4         | 2.38%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 1.19%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 1.19%   |
| HP Notebook                                | 2         | 1.19%   |
| Dell Latitude E6420                        | 2         | 1.19%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 1.19%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 1.19%   |
| Acer Nitro AN515-44                        | 2         | 1.19%   |
| Acer Aspire A515-51G                       | 2         | 1.19%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.6%    |
| Toshiba Satellite C55-A                    | 1         | 0.6%    |
| Sony VPCSB1C5E                             | 1         | 0.6%    |
| Samsung 550XCJ/550XCR                      | 1         | 0.6%    |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.6%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.6%    |
| Razer Blade 17 (Mid 2021) - RZ09-0406      | 1         | 0.6%    |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.6%    |
| Razer Blade                                | 1         | 0.6%    |
| PC Specialist GK5NPFO                      | 1         | 0.6%    |
| Panasonic CF-191HYAX1M                     | 1         | 0.6%    |
| Notebook W54_W550SU2                       | 1         | 0.6%    |
| Notebook P7xxDM2(-G)                       | 1         | 0.6%    |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.6%    |
| MSI Sword 15 A11UD                         | 1         | 0.6%    |
| MSI GS76 Stealth 11UG                      | 1         | 0.6%    |
| MSI GP75 Leopard 9SD                       | 1         | 0.6%    |
| MSI GF63 Thin 9SC                          | 1         | 0.6%    |
| MSI GF63 Thin 10SC                         | 1         | 0.6%    |
| MSI GE75 Raider 9SE                        | 1         | 0.6%    |
| MSI GE72VR 6RF                             | 1         | 0.6%    |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.6%    |
| Medion P861X                               | 1         | 0.6%    |
| Medion E7419 MD60025                       | 1         | 0.6%    |
| Lenovo Z50-70 20354                        | 1         | 0.6%    |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon 4th 20FB005WUS   | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon 2nd 20A8002MUS   | 1         | 0.6%    |
| Lenovo ThinkPad T530 24296KG               | 1         | 0.6%    |
| Lenovo ThinkPad T510 4384WB4               | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 14        | 8.33%   |
| Lenovo IdeaPad         | 13        | 7.74%   |
| Acer Aspire            | 9         | 5.36%   |
| HP Pavilion            | 8         | 4.76%   |
| Dell Latitude          | 8         | 4.76%   |
| Dell Inspiron          | 8         | 4.76%   |
| ASUS VivoBook          | 8         | 4.76%   |
| HP Laptop              | 6         | 3.57%   |
| ASUS ROG               | 6         | 3.57%   |
| Lenovo Legion          | 5         | 2.98%   |
| HP OMEN                | 4         | 2.38%   |
| Dell XPS               | 4         | 2.38%   |
| Acer Nitro             | 4         | 2.38%   |
| Unknown                | 4         | 2.38%   |
| Razer Blade            | 3         | 1.79%   |
| Acer Swift             | 3         | 1.79%   |
| Toshiba Satellite      | 2         | 1.19%   |
| MSI GF63               | 2         | 1.19%   |
| HP Notebook            | 2         | 1.19%   |
| HP EliteBook           | 2         | 1.19%   |
| Dell Precision         | 2         | 1.19%   |
| ASUS TUF               | 2         | 1.19%   |
| ASUS ASUS              | 2         | 1.19%   |
| Sony VPCSB1C5E         | 1         | 0.6%    |
| Samsung 550XCJ         | 1         | 0.6%    |
| Samsung 340XAA         | 1         | 0.6%    |
| Samsung 300V3A         | 1         | 0.6%    |
| PC Specialist GK5NPFO  | 1         | 0.6%    |
| Panasonic CF-191HYAX1M | 1         | 0.6%    |
| Notebook W54           | 1         | 0.6%    |
| Notebook P7xxDM2(-G)   | 1         | 0.6%    |
| Notebook N85           | 1         | 0.6%    |
| MSI Sword              | 1         | 0.6%    |
| MSI GS76               | 1         | 0.6%    |
| MSI GP75               | 1         | 0.6%    |
| MSI GE75               | 1         | 0.6%    |
| MSI GE72VR             | 1         | 0.6%    |
| MSI GE63               | 1         | 0.6%    |
| Medion P861X           | 1         | 0.6%    |
| Medion E7419           | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 33        | 19.64%  |
| 2021 | 27        | 16.07%  |
| 2019 | 16        | 9.52%   |
| 2018 | 14        | 8.33%   |
| 2017 | 13        | 7.74%   |
| 2016 | 13        | 7.74%   |
| 2013 | 10        | 5.95%   |
| 2014 | 9         | 5.36%   |
| 2012 | 8         | 4.76%   |
| 2015 | 7         | 4.17%   |
| 2011 | 7         | 4.17%   |
| 2009 | 3         | 1.79%   |
| 2022 | 2         | 1.19%   |
| 2010 | 2         | 1.19%   |
| 2008 | 2         | 1.19%   |
| 2007 | 2         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 168       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 168       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 99.4%   |
| Yes  | 1         | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 55        | 32.54%  |
| 8.01-16.0  | 42        | 24.85%  |
| 16.01-24.0 | 40        | 23.67%  |
| 3.01-4.0   | 15        | 8.88%   |
| 32.01-64.0 | 12        | 7.1%    |
| 24.01-32.0 | 4         | 2.37%   |
| 2.01-3.0   | 1         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 62        | 34.25%  |
| 2.01-3.0  | 51        | 28.18%  |
| 3.01-4.0  | 46        | 25.41%  |
| 1.01-2.0  | 13        | 7.18%   |
| 8.01-16.0 | 8         | 4.42%   |
| 0.51-1.0  | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 62.21%  |
| 2      | 52        | 30.23%  |
| 3      | 11        | 6.4%    |
| 4      | 1         | 0.58%   |
| 0      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 76.61%  |
| Yes       | 40        | 23.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 75.74%  |
| No        | 41        | 24.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 98.81%  |
| No        | 2         | 1.19%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 88.17%  |
| No        | 20        | 11.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 45        | 26.47%  |
| India        | 15        | 8.82%   |
| UK           | 14        | 8.24%   |
| Germany      | 14        | 8.24%   |
| Italy        | 10        | 5.88%   |
| Poland       | 8         | 4.71%   |
| Canada       | 8         | 4.71%   |
| Brazil       | 7         | 4.12%   |
| Mexico       | 5         | 2.94%   |
| Russia       | 3         | 1.76%   |
| Romania      | 3         | 1.76%   |
| Netherlands  | 3         | 1.76%   |
| Finland      | 3         | 1.76%   |
| Turkey       | 2         | 1.18%   |
| Sweden       | 2         | 1.18%   |
| Spain        | 2         | 1.18%   |
| Denmark      | 2         | 1.18%   |
| Colombia     | 2         | 1.18%   |
| Belgium      | 2         | 1.18%   |
| Venezuela    | 1         | 0.59%   |
| Switzerland  | 1         | 0.59%   |
| South Korea  | 1         | 0.59%   |
| South Africa | 1         | 0.59%   |
| Slovenia     | 1         | 0.59%   |
| Singapore    | 1         | 0.59%   |
| Serbia       | 1         | 0.59%   |
| Oman         | 1         | 0.59%   |
| Luxembourg   | 1         | 0.59%   |
| Kuwait       | 1         | 0.59%   |
| Kenya        | 1         | 0.59%   |
| Japan        | 1         | 0.59%   |
| Indonesia    | 1         | 0.59%   |
| Hungary      | 1         | 0.59%   |
| France       | 1         | 0.59%   |
| Ecuador      | 1         | 0.59%   |
| Czechia      | 1         | 0.59%   |
| China        | 1         | 0.59%   |
| Bahrain      | 1         | 0.59%   |
| Austria      | 1         | 0.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 4         | 2.23%   |
| Berlin             | 3         | 1.68%   |
| Wroclaw            | 2         | 1.12%   |
| Warsaw             | 2         | 1.12%   |
| Turin              | 2         | 1.12%   |
| Toronto            | 2         | 1.12%   |
| San Jose           | 2         | 1.12%   |
| Portland           | 2         | 1.12%   |
| Peterborough       | 2         | 1.12%   |
| Mumbai             | 2         | 1.12%   |
| Milan              | 2         | 1.12%   |
| Helsinki           | 2         | 1.12%   |
| Düsseldorf        | 2         | 1.12%   |
| Delhi              | 2         | 1.12%   |
| Copenhagen         | 2         | 1.12%   |
| Chennai            | 2         | 1.12%   |
| Winston-Salem      | 1         | 0.56%   |
| Welwyn Garden City | 1         | 0.56%   |
| Wasilla            | 1         | 0.56%   |
| Vancouver          | 1         | 0.56%   |
| Valencia           | 1         | 0.56%   |
| Tustin             | 1         | 0.56%   |
| Turku              | 1         | 0.56%   |
| Tucson             | 1         | 0.56%   |
| Timișoara         | 1         | 0.56%   |
| Tarczyn            | 1         | 0.56%   |
| Sunrise Beach      | 1         | 0.56%   |
| Steenwijk          | 1         | 0.56%   |
| Stawiszyn          | 1         | 0.56%   |
| Sparks             | 1         | 0.56%   |
| Southampton        | 1         | 0.56%   |
| Sitka              | 1         | 0.56%   |
| Singapore          | 1         | 0.56%   |
| Sighetu Marmaţiei | 1         | 0.56%   |
| Seattle            | 1         | 0.56%   |
| San Francisco      | 1         | 0.56%   |
| San Antonio        | 1         | 0.56%   |
| Rugby              | 1         | 0.56%   |
| Rotterdam          | 1         | 0.56%   |
| Rome               | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 39        | 50     | 16.53%  |
| Seagate                     | 29        | 32     | 12.29%  |
| WDC                         | 24        | 25     | 10.17%  |
| SK hynix                    | 17        | 24     | 7.2%    |
| SanDisk                     | 16        | 19     | 6.78%   |
| Intel                       | 11        | 13     | 4.66%   |
| HGST                        | 11        | 11     | 4.66%   |
| Unknown                     | 10        | 10     | 4.24%   |
| Toshiba                     | 10        | 12     | 4.24%   |
| Kingston                    | 7         | 7      | 2.97%   |
| Crucial                     | 7         | 10     | 2.97%   |
| Micron Technology           | 5         | 5      | 2.12%   |
| Hitachi                     | 5         | 5      | 2.12%   |
| Silicon Motion              | 3         | 3      | 1.27%   |
| PNY                         | 3         | 3      | 1.27%   |
| LITEON                      | 3         | 3      | 1.27%   |
| KIOXIA                      | 3         | 5      | 1.27%   |
| Corsair                     | 3         | 3      | 1.27%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.85%   |
| Phison                      | 2         | 2      | 0.85%   |
| China                       | 2         | 2      | 0.85%   |
| A-DATA Technology           | 2         | 2      | 0.85%   |
| Yangtze Memory Technologies | 1         | 1      | 0.42%   |
| WODPOSIT                    | 1         | 2      | 0.42%   |
| WDC WDS                     | 1         | 1      | 0.42%   |
| VisionTek                   | 1         | 2      | 0.42%   |
| UMIS                        | 1         | 2      | 0.42%   |
| SSSTC                       | 1         | 1      | 0.42%   |
| SPCC                        | 1         | 1      | 0.42%   |
| ShanDianZhe                 | 1         | 1      | 0.42%   |
| SABRENT                     | 1         | 2      | 0.42%   |
| PNY CS90                    | 1         | 1      | 0.42%   |
| Phison Electronics          | 1         | 1      | 0.42%   |
| Netac                       | 1         | 1      | 0.42%   |
| Mushkin                     | 1         | 1      | 0.42%   |
| Micron/Crucial Technology   | 1         | 1      | 0.42%   |
| LITEONIT                    | 1         | 1      | 0.42%   |
| Lenovo                      | 1         | 1      | 0.42%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.42%   |
| JMicron Technology          | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 7         | 2.83%   |
| Seagate ST1000LM049-2GH172 1TB       | 5         | 2.02%   |
| Samsung NVMe SSD Drive 1TB           | 5         | 2.02%   |
| HGST HTS721010A9E630 1TB             | 4         | 1.62%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.21%   |
| Samsung SSD 860 EVO 1TB              | 3         | 1.21%   |
| Intel SSDPEKNU512GZ 512GB            | 3         | 1.21%   |
| WDC WDBNCE5000PNC 500GB SSD          | 2         | 0.81%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 2         | 0.81%   |
| Unknown MMC Card  16GB               | 2         | 0.81%   |
| SK hynix SC311 SATA 256GB SSD        | 2         | 0.81%   |
| SK hynix NVMe SSD Drive 512GB        | 2         | 0.81%   |
| SK hynix HFM001TD3JX013N 1024GB      | 2         | 0.81%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.81%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.81%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 0.81%   |
| SanDisk NVMe SSD Drive 512GB         | 2         | 0.81%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 0.81%   |
| Samsung SSD 870 QVO 1TB              | 2         | 0.81%   |
| Samsung SSD 870 EVO 500GB            | 2         | 0.81%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.81%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD | 2         | 0.81%   |
| PNY ELITE PSSD 240GB                 | 2         | 0.81%   |
| KIOXIA NVMe SSD Drive 512GB          | 2         | 0.81%   |
| Intel SSDPEKNW010T8 1TB              | 2         | 0.81%   |
| Intel SSD 660P Series 512GB          | 2         | 0.81%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.81%   |
| HGST HTS541075A9E680 752GB           | 2         | 0.81%   |
| HGST HTS541010A9E680 1TB             | 2         | 0.81%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.81%   |
| Corsair Force MP300 960GB            | 2         | 0.81%   |
| Yangtze Memory NVMe SSD Drive 256GB  | 1         | 0.4%    |
| WODPOSIT SSD WPSM28-256G             | 1         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.4%    |
| WDC WDS 500G2B0B-00YS70 500GB SSD    | 1         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.4%    |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 30     | 50%     |
| HGST    | 11        | 11     | 19.64%  |
| WDC     | 6         | 6      | 10.71%  |
| Toshiba | 5         | 7      | 8.93%   |
| Hitachi | 5         | 5      | 8.93%   |
| Unknown | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 24     | 28.57%  |
| SanDisk             | 7         | 10     | 10%     |
| Crucial             | 6         | 9      | 8.57%   |
| WDC                 | 5         | 6      | 7.14%   |
| Kingston            | 4         | 4      | 5.71%   |
| SK hynix            | 3         | 4      | 4.29%   |
| PNY                 | 3         | 3      | 4.29%   |
| LITEON              | 3         | 3      | 4.29%   |
| China               | 2         | 2      | 2.86%   |
| A-DATA Technology   | 2         | 2      | 2.86%   |
| WODPOSIT            | 1         | 2      | 1.43%   |
| WDC WDS             | 1         | 1      | 1.43%   |
| VisionTek           | 1         | 2      | 1.43%   |
| Toshiba             | 1         | 1      | 1.43%   |
| PNY CS90            | 1         | 1      | 1.43%   |
| Netac               | 1         | 1      | 1.43%   |
| Mushkin             | 1         | 1      | 1.43%   |
| Micron Technology   | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.43%   |
| Intenso             | 1         | 1      | 1.43%   |
| FORESEE             | 1         | 1      | 1.43%   |
| Corsair             | 1         | 1      | 1.43%   |
| ASMT                | 1         | 1      | 1.43%   |
| Unknown             | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 86        | 117    | 39.45%  |
| SSD     | 66        | 84     | 30.28%  |
| HDD     | 53        | 60     | 24.31%  |
| MMC     | 10        | 10     | 4.59%   |
| Unknown | 3         | 3      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 132    | 47.12%  |
| NVMe | 85        | 114    | 40.87%  |
| SAS  | 15        | 18     | 7.21%   |
| MMC  | 10        | 10     | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 73     | 51.67%  |
| 0.51-1.0   | 51        | 64     | 42.5%   |
| 1.01-2.0   | 6         | 6      | 5%      |
| 3.01-4.0   | 1         | 1      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 63        | 36.84%  |
| 501-1000       | 36        | 21.05%  |
| 1001-2000      | 34        | 19.88%  |
| 2001-3000      | 16        | 9.36%   |
| Unknown        | 10        | 5.85%   |
| 251-500        | 6         | 3.51%   |
| 1-20           | 4         | 2.34%   |
| 101-250        | 2         | 1.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 27.68%  |
| 251-500        | 34        | 19.21%  |
| 501-1000       | 26        | 14.69%  |
| 1001-2000      | 24        | 13.56%  |
| 51-100         | 21        | 11.86%  |
| Unknown        | 10        | 5.65%   |
| 2001-3000      | 5         | 2.82%   |
| More than 3000 | 4         | 2.26%   |
| 1-20           | 4         | 2.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB         | 1         | 1      | 9.09%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 9.09%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 9.09%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 9.09%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 1      | 9.09%   |
| Hitachi HTS547575A9E384 752GB        | 1         | 1      | 9.09%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB           | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 9.09%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 4      | 36.36%  |
| HGST     | 3         | 3      | 27.27%  |
| Hitachi  | 2         | 2      | 18.18%  |
| WDC      | 1         | 1      | 9.09%   |
| SK hynix | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 40%     |
| HGST    | 3         | 3      | 30%     |
| Hitachi | 2         | 2      | 20%     |
| WDC     | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 90.91%  |
| NVMe | 1         | 1      | 9.09%   |

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
| Works    | 92        | 134    | 49.2%   |
| Detected | 84        | 129    | 44.92%  |
| Malfunc  | 11        | 11     | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 109       | 49.32%  |
| AMD                            | 29        | 13.12%  |
| Samsung Electronics            | 20        | 9.05%   |
| SanDisk                        | 19        | 8.6%    |
| SK hynix                       | 14        | 6.33%   |
| Phison Electronics             | 6         | 2.71%   |
| Union Memory (Shenzhen)        | 3         | 1.36%   |
| Toshiba America Info Systems   | 3         | 1.36%   |
| Silicon Motion                 | 3         | 1.36%   |
| Micron Technology              | 3         | 1.36%   |
| KIOXIA                         | 3         | 1.36%   |
| Kingston Technology Company    | 3         | 1.36%   |
| Micron/Crucial Technology      | 2         | 0.9%    |
| Yangtze Memory Technologies    | 1         | 0.45%   |
| Solid State Storage Technology | 1         | 0.45%   |
| Nvidia                         | 1         | 0.45%   |
| Lenovo                         | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28        | 12.12%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 6.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 6.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 5.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 4.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 3.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.46%   |
| SK hynix Gold P31 SSD                                                          | 6         | 2.6%    |
| Intel SSD 660P Series                                                          | 6         | 2.6%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 2.16%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 2.16%   |
| Intel Non-Volatile memory controller                                           | 5         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 2.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 2.16%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 1.73%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.73%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.73%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.3%    |
| Micron Non-Volatile memory controller                                          | 3         | 1.3%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.3%    |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.3%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.87%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.87%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.87%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.87%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.43%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.43%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.43%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 112       | 51.14%  |
| NVMe | 83        | 37.9%   |
| RAID | 21        | 9.59%   |
| IDE  | 3         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 69.64%  |
| AMD    | 51        | 30.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 4.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 4.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.98%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 2.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 2.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 2.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.79%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.79%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.79%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.19%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.19%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.19%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.19%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.19%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.19%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.19%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.19%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 2         | 1.19%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 2         | 1.19%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 2         | 1.19%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.19%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.19%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.19%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.19%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.19%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.19%   |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz          | 1         | 0.6%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.6%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.6%    |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 48        | 28.57%  |
| Intel Core i5           | 30        | 17.86%  |
| AMD Ryzen 7             | 17        | 10.12%  |
| AMD Ryzen 5             | 16        | 9.52%   |
| Intel Core i3           | 15        | 8.93%   |
| Other                   | 12        | 7.14%   |
| Intel Celeron           | 5         | 2.98%   |
| AMD Ryzen 9             | 4         | 2.38%   |
| AMD A8                  | 4         | 2.38%   |
| Intel Pentium Silver    | 2         | 1.19%   |
| Intel Pentium           | 2         | 1.19%   |
| Intel Core 2 Duo        | 2         | 1.19%   |
| AMD Ryzen 7 PRO         | 2         | 1.19%   |
| AMD A10                 | 2         | 1.19%   |
| Intel Xeon              | 1         | 0.6%    |
| Intel Pentium Dual-Core | 1         | 0.6%    |
| Intel Core m3           | 1         | 0.6%    |
| AMD Turion              | 1         | 0.6%    |
| AMD FX                  | 1         | 0.6%    |
| AMD A6                  | 1         | 0.6%    |
| AMD A4                  | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 39.29%  |
| 4      | 55        | 32.74%  |
| 6      | 24        | 14.29%  |
| 8      | 23        | 13.69%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 168       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 149       | 88.69%  |
| 1      | 19        | 11.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 168       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 38.73%  |
| 0x306a9    | 7         | 4.05%   |
| 0x0a50000c | 7         | 4.05%   |
| 0x906ea    | 6         | 3.47%   |
| 0xa0652    | 5         | 2.89%   |
| 0x906e9    | 5         | 2.89%   |
| 0x806c1    | 5         | 2.89%   |
| 0x206a7    | 5         | 2.89%   |
| 0x08108109 | 5         | 2.89%   |
| 0x806ea    | 4         | 2.31%   |
| 0x306c3    | 4         | 2.31%   |
| 0x08600106 | 4         | 2.31%   |
| 0x08600103 | 4         | 2.31%   |
| 0x806e9    | 3         | 1.73%   |
| 0x506e3    | 3         | 1.73%   |
| 0x406e3    | 3         | 1.73%   |
| 0x08600104 | 3         | 1.73%   |
| 0x08108102 | 3         | 1.73%   |
| 0x806ec    | 2         | 1.16%   |
| 0x40651    | 2         | 1.16%   |
| 0x106e5    | 2         | 1.16%   |
| 0x0a50000b | 2         | 1.16%   |
| 0x08608103 | 2         | 1.16%   |
| 0x08101007 | 2         | 1.16%   |
| 0x06006705 | 2         | 1.16%   |
| 0xa0660    | 1         | 0.58%   |
| 0x806d1    | 1         | 0.58%   |
| 0x706e5    | 1         | 0.58%   |
| 0x706a8    | 1         | 0.58%   |
| 0x706a1    | 1         | 0.58%   |
| 0x506c9    | 1         | 0.58%   |
| 0x406c4    | 1         | 0.58%   |
| 0x306d4    | 1         | 0.58%   |
| 0x20655    | 1         | 0.58%   |
| 0x20652    | 1         | 0.58%   |
| 0x1067a    | 1         | 0.58%   |
| 0x10676    | 1         | 0.58%   |
| 0x07030106 | 1         | 0.58%   |
| 0x0700010f | 1         | 0.58%   |
| 0x06006110 | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 35        | 20.83%  |
| Zen 2           | 15        | 8.93%   |
| Skylake         | 12        | 7.14%   |
| Zen 3           | 11        | 6.55%   |
| SandyBridge     | 10        | 5.95%   |
| Haswell         | 10        | 5.95%   |
| CometLake       | 10        | 5.95%   |
| Zen+            | 9         | 5.36%   |
| IvyBridge       | 9         | 5.36%   |
| TigerLake       | 7         | 4.17%   |
| Broadwell       | 6         | 3.57%   |
| Excavator       | 4         | 2.38%   |
| Unknown         | 4         | 2.38%   |
| Puma            | 3         | 1.79%   |
| Penryn          | 3         | 1.79%   |
| IceLake         | 3         | 1.79%   |
| Goldmont plus   | 3         | 1.79%   |
| Zen             | 2         | 1.19%   |
| Westmere        | 2         | 1.19%   |
| Silvermont      | 2         | 1.19%   |
| Piledriver      | 2         | 1.19%   |
| Nehalem         | 2         | 1.19%   |
| Steamroller     | 1         | 0.6%    |
| K8 & K10 hybrid | 1         | 0.6%    |
| Jaguar          | 1         | 0.6%    |
| Goldmont        | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 109       | 44.67%  |
| Nvidia | 79        | 32.38%  |
| AMD    | 56        | 22.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                            | 15        | 5.95%   |
| AMD Cezanne                                                                           | 11        | 4.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 10        | 3.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 10        | 3.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 9         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 9         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 9         | 3.57%   |
| Intel UHD Graphics 620                                                                | 8         | 3.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 8         | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 5         | 1.98%   |
| Nvidia TU117M                                                                         | 5         | 1.98%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 5         | 1.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 5         | 1.98%   |
| Intel HD Graphics 630                                                                 | 5         | 1.98%   |
| Intel HD Graphics 620                                                                 | 5         | 1.98%   |
| Intel HD Graphics 5500                                                                | 5         | 1.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 5         | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 1.98%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 4         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 1.19%   |
| Nvidia GM108M [GeForce 840M]                                                          | 3         | 1.19%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                              | 3         | 1.19%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 3         | 1.19%   |
| Intel HD Graphics 530                                                                 | 3         | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.19%   |
| Nvidia GM108M [GeForce MX110]                                                         | 2         | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.79%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 2         | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 0.79%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 0.79%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 2         | 0.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 0.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 55        | 32.74%  |
| Intel + Nvidia     | 47        | 27.98%  |
| 1 x AMD            | 26        | 15.48%  |
| AMD + Nvidia       | 22        | 13.1%   |
| 1 x Nvidia         | 8         | 4.76%   |
| Intel + AMD        | 5         | 2.98%   |
| 2 x AMD            | 3         | 1.79%   |
| Intel + 2 x Nvidia | 2         | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 63.53%  |
| Proprietary | 62        | 36.47%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 67.82%  |
| 0.01-0.5   | 28        | 16.09%  |
| 1.01-2.0   | 14        | 8.05%   |
| 5.01-6.0   | 5         | 2.87%   |
| 3.01-4.0   | 5         | 2.87%   |
| 0.51-1.0   | 3         | 1.72%   |
| 7.01-8.0   | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 21.83%  |
| LG Display              | 28        | 14.21%  |
| Chimei Innolux          | 28        | 14.21%  |
| BOE                     | 28        | 14.21%  |
| Samsung Electronics     | 18        | 9.14%   |
| Sharp                   | 9         | 4.57%   |
| PANDA                   | 9         | 4.57%   |
| Dell                    | 5         | 2.54%   |
| Lenovo                  | 4         | 2.03%   |
| Goldstar                | 3         | 1.52%   |
| Sony                    | 2         | 1.02%   |
| CSO                     | 2         | 1.02%   |
| BenQ                    | 2         | 1.02%   |
| Apple                   | 2         | 1.02%   |
| AOC                     | 2         | 1.02%   |
| Acer                    | 2         | 1.02%   |
| Philips                 | 1         | 0.51%   |
| MStar                   | 1         | 0.51%   |
| Mi                      | 1         | 0.51%   |
| InfoVision              | 1         | 0.51%   |
| Hewlett-Packard         | 1         | 0.51%   |
| G-Story                 | 1         | 0.51%   |
| Eizo                    | 1         | 0.51%   |
| CPT                     | 1         | 0.51%   |
| Chi Mei Optoelectronics | 1         | 0.51%   |
| ASUSTek Computer        | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 4         | 2.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 4         | 2.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.52%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch                | 2         | 1.02%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch   | 2         | 1.02%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 1.02%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 1.02%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 1.02%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 2         | 1.02%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 1.02%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 1.02%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                  | 2         | 1.02%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                  | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch          | 2         | 1.02%   |
| Sony TV SNYA301 1920x1080                                              | 1         | 0.51%   |
| Sony TV *30 SNYB905 3840x2160 952x535mm 43.0-inch                      | 1         | 0.51%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.51%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                | 1         | 0.51%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.51%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.51%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.51%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                | 1         | 0.51%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.51%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 1         | 0.51%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4652 1366x768 344x194mm 15.5-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 102       | 55.14%  |
| 1366x768 (WXGA)    | 33        | 17.84%  |
| 1600x900 (HD+)     | 11        | 5.95%   |
| 3840x2160 (4K)     | 9         | 4.86%   |
| 2560x1440 (QHD)    | 6         | 3.24%   |
| 2560x1600          | 4         | 2.16%   |
| 1680x1050 (WSXGA+) | 4         | 2.16%   |
| 1920x1200 (WUXGA)  | 3         | 1.62%   |
| 1280x800 (WXGA)    | 2         | 1.08%   |
| 3840x2400          | 1         | 0.54%   |
| 3440x1440          | 1         | 0.54%   |
| 3200x1800 (QHD+)   | 1         | 0.54%   |
| 2880x1800          | 1         | 0.54%   |
| 2880x1440          | 1         | 0.54%   |
| 2256x1504          | 1         | 0.54%   |
| 2160x1440          | 1         | 0.54%   |
| 1680x945           | 1         | 0.54%   |
| 1600x1200          | 1         | 0.54%   |
| 1440x900 (WXGA+)   | 1         | 0.54%   |
| 1280x720 (HD)      | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 102       | 52.04%  |
| 14      | 25        | 12.76%  |
| 13      | 16        | 8.16%   |
| 17      | 13        | 6.63%   |
| 27      | 7         | 3.57%   |
| 21      | 4         | 2.04%   |
| 16      | 4         | 2.04%   |
| 23      | 3         | 1.53%   |
| 18      | 3         | 1.53%   |
| 31      | 2         | 1.02%   |
| 24      | 2         | 1.02%   |
| 22      | 2         | 1.02%   |
| 20      | 2         | 1.02%   |
| Unknown | 2         | 1.02%   |
| 85      | 1         | 0.51%   |
| 72      | 1         | 0.51%   |
| 54      | 1         | 0.51%   |
| 52      | 1         | 0.51%   |
| 47      | 1         | 0.51%   |
| 43      | 1         | 0.51%   |
| 34      | 1         | 0.51%   |
| 12      | 1         | 0.51%   |
| 11      | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 137       | 69.9%   |
| 351-400     | 15        | 7.65%   |
| 501-600     | 12        | 6.12%   |
| 401-500     | 11        | 5.61%   |
| 201-300     | 10        | 5.1%    |
| 1001-1500   | 3         | 1.53%   |
| 601-700     | 2         | 1.02%   |
| 1501-2000   | 2         | 1.02%   |
| Unknown     | 2         | 1.02%   |
| 701-800     | 1         | 0.51%   |
| 901-1000    | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 155       | 88.07%  |
| 16/10 | 16        | 9.09%   |
| 3/2   | 2         | 1.14%   |
| 4/3   | 1         | 0.57%   |
| 21/9  | 1         | 0.57%   |
| 2.00  | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 103       | 52.55%  |
| 81-90          | 36        | 18.37%  |
| 121-130        | 13        | 6.63%   |
| 201-250        | 10        | 5.1%    |
| 301-350        | 7         | 3.57%   |
| 71-80          | 5         | 2.55%   |
| More than 1000 | 4         | 2.04%   |
| 351-500        | 3         | 1.53%   |
| 141-150        | 3         | 1.53%   |
| 151-200        | 2         | 1.02%   |
| 111-120        | 2         | 1.02%   |
| 501-1000       | 2         | 1.02%   |
| Unknown        | 2         | 1.02%   |
| 61-70          | 1         | 0.51%   |
| 51-60          | 1         | 0.51%   |
| 251-300        | 1         | 0.51%   |
| 91-100         | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 53.89%  |
| 101-120       | 46        | 23.83%  |
| 51-100        | 19        | 9.84%   |
| 161-240       | 10        | 5.18%   |
| More than 240 | 7         | 3.63%   |
| 1-50          | 5         | 2.59%   |
| Unknown       | 2         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 132       | 76.74%  |
| 2     | 39        | 22.67%  |
| 0     | 1         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 98        | 35.64%  |
| Intel                             | 93        | 33.82%  |
| Qualcomm Atheros                  | 41        | 14.91%  |
| Broadcom                          | 12        | 4.36%   |
| MediaTek                          | 7         | 2.55%   |
| Samsung Electronics               | 3         | 1.09%   |
| TP-Link                           | 2         | 0.73%   |
| Ralink Technology                 | 2         | 0.73%   |
| Qualcomm                          | 2         | 0.73%   |
| NetGear                           | 2         | 0.73%   |
| ASUSTek Computer                  | 2         | 0.73%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.36%   |
| Xiaomi                            | 1         | 0.36%   |
| Wacom                             | 1         | 0.36%   |
| Sierra Wireless                   | 1         | 0.36%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.36%   |
| Nvidia                            | 1         | 0.36%   |
| Lenovo                            | 1         | 0.36%   |
| Ericsson Business Mobile Networks | 1         | 0.36%   |
| DisplayLink                       | 1         | 0.36%   |
| Dell                              | 1         | 0.36%   |
| ASIX Electronics                  | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 19.75%  |
| Intel Wi-Fi 6 AX200                                               | 18        | 5.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 2.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.19%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.88%   |
| Intel Wireless 7265                                               | 6         | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.57%   |
| Intel Wireless 7260                                               | 5         | 1.57%   |
| Intel Wireless 3165                                               | 5         | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 1.25%   |
| Intel Wireless 8260                                               | 4         | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.94%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.94%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 89        | 49.72%  |
| Qualcomm Atheros      | 34        | 18.99%  |
| Realtek Semiconductor | 28        | 15.64%  |
| Broadcom              | 10        | 5.59%   |
| MediaTek              | 7         | 3.91%   |
| TP-Link               | 2         | 1.12%   |
| Ralink Technology     | 2         | 1.12%   |
| NetGear               | 2         | 1.12%   |
| ASUSTek Computer      | 2         | 1.12%   |
| Wacom                 | 1         | 0.56%   |
| Sierra Wireless       | 1         | 0.56%   |
| Dell                  | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 18        | 9.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 10        | 5.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 9         | 4.97%   |
| Intel Comet Lake PCH CNVi WiFi                                | 9         | 4.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 8         | 4.42%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 8         | 4.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 3.87%   |
| Intel Wireless 8265 / 8275                                    | 6         | 3.31%   |
| Intel Wireless 7265                                           | 6         | 3.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 5         | 2.76%   |
| Intel Wireless 7260                                           | 5         | 2.76%   |
| Intel Wireless 3165                                           | 5         | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 4         | 2.21%   |
| Intel Wireless 8260                                           | 4         | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 4         | 2.21%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 3         | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 1.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3         | 1.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 1.66%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 1.66%   |
| Intel Centrino Advanced-N 6200                                | 3         | 1.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 1.66%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 2         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                | 2         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                 | 2         | 1.1%    |
| Wacom ACK-40401 [Wireless Accessory Kit]                      | 1         | 0.55%   |
| Sierra Wireless EM7455                                        | 1         | 0.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.55%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.55%   |
| Realtek RTL8191SEvA Wireless LAN Controller                   | 1         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.55%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.55%   |
| Realtek 802.11ac NIC                                          | 1         | 0.55%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 84        | 61.76%  |
| Intel                      | 25        | 18.38%  |
| Qualcomm Atheros           | 12        | 8.82%   |
| Broadcom                   | 4         | 2.94%   |
| Samsung Electronics        | 3         | 2.21%   |
| Qualcomm                   | 2         | 1.47%   |
| ZTE WCDMA Technologies MSM | 1         | 0.74%   |
| Xiaomi                     | 1         | 0.74%   |
| Nvidia                     | 1         | 0.74%   |
| Lenovo                     | 1         | 0.74%   |
| DisplayLink                | 1         | 0.74%   |
| ASIX Electronics           | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 46.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 8.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 2.94%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 2.21%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 2.21%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.47%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.47%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.47%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.74%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.74%   |
| Qualcomm Redmi 5 Plus                                             | 1         | 0.74%   |
| Qualcomm Mobile Router                                            | 1         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.74%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.74%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.74%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.74%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.74%   |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 56.08%  |
| Ethernet | 128       | 43.24%  |
| Modem    | 1         | 0.34%   |
| Unknown  | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 139       | 80.81%  |
| Ethernet | 33        | 19.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 116       | 69.05%  |
| 1     | 49        | 29.17%  |
| 3     | 2         | 1.19%   |
| 0     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 76.61%  |
| Yes  | 40        | 23.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 49.67%  |
| Qualcomm Atheros Communications | 21        | 13.91%  |
| Realtek Semiconductor           | 19        | 12.58%  |
| IMC Networks                    | 10        | 6.62%   |
| Foxconn / Hon Hai               | 7         | 4.64%   |
| Lite-On Technology              | 5         | 3.31%   |
| Broadcom                        | 5         | 3.31%   |
| Hewlett-Packard                 | 2         | 1.32%   |
| Dell                            | 2         | 1.32%   |
| Apple                           | 2         | 1.32%   |
| Realtek                         | 1         | 0.66%   |
| Cambridge Silicon Radio         | 1         | 0.66%   |
| AboCom Systems                  | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 23        | 15.23%  |
| Intel AX200 Bluetooth                                                               | 18        | 11.92%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 14        | 9.27%   |
| Intel AX201 Bluetooth                                                               | 14        | 9.27%   |
| Realtek Bluetooth Radio                                                             | 11        | 7.28%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 5.96%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 4.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 3.97%   |
| IMC Networks Wireless_Device                                                        | 4         | 2.65%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.65%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.99%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.32%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.66%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.66%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.66%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.66%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.66%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.66%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.66%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.66%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.66%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.66%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.66%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.66%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.66%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 116       | 53.21%  |
| AMD                   | 51        | 23.39%  |
| Nvidia                | 39        | 17.89%  |
| Corsair               | 2         | 0.92%   |
| C-Media Electronics   | 2         | 0.92%   |
| Turtle Beach          | 1         | 0.46%   |
| RODE Microphones      | 1         | 0.46%   |
| Realtek Semiconductor | 1         | 0.46%   |
| Phison Electronics    | 1         | 0.46%   |
| JMTek                 | 1         | 0.46%   |
| Huawei Technologies   | 1         | 0.46%   |
| GN Netcom             | 1         | 0.46%   |
| BR25                  | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 38        | 14.02%  |
| Intel Sunrise Point-LP HD Audio                                            | 22        | 8.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 5.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 4.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 3.32%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 3.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.58%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 2.21%   |
| Intel CM238 HD Audio Controller                                            | 6         | 2.21%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 2.21%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 2.21%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.85%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.11%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.11%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.11%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.74%   |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.74%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.74%   |
| AMD High Definition Audio Controller                                       | 2         | 0.74%   |
| Turtle Beach Ear Force P11 Headset                                         | 1         | 0.37%   |
| RODE Microphones RODE NT-USB                                               | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 30.2%   |
| SK hynix            | 29        | 19.46%  |
| Micron Technology   | 20        | 13.42%  |
| Crucial             | 13        | 8.72%   |
| Kingston            | 7         | 4.7%    |
| Ramaxel Technology  | 6         | 4.03%   |
| A-DATA Technology   | 5         | 3.36%   |
| Unknown             | 4         | 2.68%   |
| Corsair             | 4         | 2.68%   |
| Smart               | 3         | 2.01%   |
| Nanya Technology    | 3         | 2.01%   |
| Unknown (ABCD)      | 2         | 1.34%   |
| Transcend           | 1         | 0.67%   |
| Timetec             | 1         | 0.67%   |
| Patriot             | 1         | 0.67%   |
| G.Skill             | 1         | 0.67%   |
| Elpida              | 1         | 0.67%   |
| CSX                 | 1         | 0.67%   |
| Avant               | 1         | 0.67%   |
| 48spaces            | 1         | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 3.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 3.77%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 3.14%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 2.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.89%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.89%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.26%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.26%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.26%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.26%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 1.26%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.26%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.26%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.26%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s       | 2         | 1.26%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.26%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.63%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.63%   |
| Timetec RAM SD4-3200 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.63%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.63%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.63%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.63%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.63%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.63%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.63%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.63%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 79        | 63.71%  |
| DDR3   | 35        | 28.23%  |
| LPDDR4 | 5         | 4.03%   |
| LPDDR3 | 3         | 2.42%   |
| DDR2   | 2         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 90.55%  |
| Row Of Chips | 10        | 7.87%   |
| Chip         | 1         | 0.79%   |
| Unknown      | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 68        | 49.64%  |
| 4096  | 45        | 32.85%  |
| 16384 | 19        | 13.87%  |
| 2048  | 5         | 3.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 41        | 29.71%  |
| 2667  | 31        | 22.46%  |
| 1600  | 29        | 21.01%  |
| 2400  | 15        | 10.87%  |
| 1334  | 4         | 2.9%    |
| 4266  | 3         | 2.17%   |
| 3266  | 3         | 2.17%   |
| 2133  | 3         | 2.17%   |
| 1867  | 2         | 1.45%   |
| 1333  | 2         | 1.45%   |
| 667   | 2         | 1.45%   |
| 8400  | 1         | 0.72%   |
| 1866  | 1         | 0.72%   |
| 800   | 1         | 0.72%   |

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
| Chicony Electronics                    | 38        | 25%     |
| IMC Networks                           | 22        | 14.47%  |
| Microdia                               | 12        | 7.89%   |
| Acer                                   | 12        | 7.89%   |
| Sunplus Innovation Technology          | 10        | 6.58%   |
| Realtek Semiconductor                  | 9         | 5.92%   |
| Quanta                                 | 9         | 5.92%   |
| Syntek                                 | 6         | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.95%   |
| Suyin                                  | 4         | 2.63%   |
| Luxvisions Innotech Limited            | 4         | 2.63%   |
| Silicon Motion                         | 3         | 1.97%   |
| Logitech                               | 3         | 1.97%   |
| Apple                                  | 3         | 1.97%   |
| Microsoft                              | 2         | 1.32%   |
| Lite-On Technology                     | 2         | 1.32%   |
| WaveRider Communications               | 1         | 0.66%   |
| Sonix Technology                       | 1         | 0.66%   |
| Samsung Electronics                    | 1         | 0.66%   |
| Lenovo                                 | 1         | 0.66%   |
| Importek                               | 1         | 0.66%   |
| Genesys Logic                          | 1         | 0.66%   |
| Creative Technology                    | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 7.19%   |
| Microdia Integrated_Webcam_HD                       | 7         | 4.58%   |
| Chicony Integrated Camera                           | 7         | 4.58%   |
| Chicony HD WebCam                                   | 7         | 4.58%   |
| IMC Networks Integrated Camera                      | 6         | 3.92%   |
| Syntek Integrated Camera                            | 4         | 2.61%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 2.61%   |
| Chicony HD User Facing                              | 4         | 2.61%   |
| Acer HD Webcam                                      | 4         | 2.61%   |
| Quanta HP Wide Vision HD Camera                     | 3         | 1.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.96%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.96%   |
| Acer Integrated Camera                              | 3         | 1.96%   |
| Silicon Motion Web Camera                           | 2         | 1.31%   |
| Microdia Webcam Vitade AF                           | 2         | 1.31%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.31%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 1.31%   |
| IMC Networks HD Camera                              | 2         | 1.31%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.31%   |
| Chicony USB 2.0 Camera                              | 2         | 1.31%   |
| Chicony HP Truevision HD                            | 2         | 1.31%   |
| Chicony EasyCamera                                  | 2         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.31%   |
| Apple iPhone5/5C/5S/6                               | 2         | 1.31%   |
| WaveRider USB Live camera                           | 1         | 0.65%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.65%   |
| Syntek EasyCamera                                   | 1         | 0.65%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.65%   |
| Suyin HP Truevision HD                              | 1         | 0.65%   |
| Suyin HD WebCam                                     | 1         | 0.65%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.65%   |
| Sunplus MTD Camera                                  | 1         | 0.65%   |
| Sunplus Lenovo EasyCamera                           | 1         | 0.65%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.65%   |
| Sunplus Integrated Webcam                           | 1         | 0.65%   |
| Sunplus Integrated Camera                           | 1         | 0.65%   |
| Sunplus HD User Facing                              | 1         | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.65%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.65%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 25.81%  |
| Elan Microelectronics      | 6         | 19.35%  |
| Synaptics                  | 5         | 16.13%  |
| Shenzhen Goodix Technology | 5         | 16.13%  |
| LighTuning Technology      | 4         | 12.9%   |
| AuthenTec                  | 2         | 6.45%   |
| Focal-systems.Corp         | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device               | 3         | 9.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 3         | 9.68%   |
| Elan ELAN:Fingerprint                             | 3         | 9.68%   |
| Elan ELAN:ARM-M4                                  | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 6.45%   |
| Validity Sensors Synaptics WBDI                   | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 6.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 3.23%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 3.23%   |
| Validity Sensors Fingerprint scanner              | 1         | 3.23%   |
| Synaptics WBDI Device                             | 1         | 3.23%   |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 3.23%   |
| Shenzhen Goodix FingerPrint                       | 1         | 3.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 3.23%   |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 3.23%   |
| AuthenTec AES2810                                 | 1         | 3.23%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 10        | 66.67%  |
| Alcor Micro      | 2         | 13.33%  |
| Upek             | 1         | 6.67%   |
| SCM Microsystems | 1         | 6.67%   |
| Lenovo           | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 20%     |
| Broadcom 5880                                                                | 3         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.67%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 82        | 47.95%  |
| 2     | 42        | 24.56%  |
| 0     | 39        | 22.81%  |
| 3     | 7         | 4.09%   |
| 4     | 1         | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 111       | 57.51%  |
| Fingerprint reader       | 31        | 16.06%  |
| Chipcard                 | 14        | 7.25%   |
| Graphics card            | 12        | 6.22%   |
| Net/wireless             | 6         | 3.11%   |
| Multimedia controller    | 5         | 2.59%   |
| Net/ethernet             | 4         | 2.07%   |
| Camera                   | 4         | 2.07%   |
| Storage                  | 3         | 1.55%   |
| Wireless                 | 1         | 0.52%   |
| Network                  | 1         | 0.52%   |
| Bluetooth                | 1         | 0.52%   |

