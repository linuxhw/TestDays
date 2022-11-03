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

Total: 254

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 7737               | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5fa4e96f1c](https://linux-hardware.org/?probe=5fa4e96f1c) | Oct 18, 2022 |
| ASUSTek       | X555LAB                     | [b0fb3c2590](https://linux-hardware.org/?probe=b0fb3c2590) | Oct 18, 2022 |
| Gigabyte      | G5 MD                       | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 15 9500                 | [e744ed6ac6](https://linux-hardware.org/?probe=e744ed6ac6) | Oct 12, 2022 |
| HP            | ProBook 640 G1              | [06fbfa78a5](https://linux-hardware.org/?probe=06fbfa78a5) | Oct 11, 2022 |
| Acer          | Swift SF314-42              | [e009be07a6](https://linux-hardware.org/?probe=e009be07a6) | Oct 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
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
| Acer          | Aspire A515-51G             | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Dell          | Latitude E5450              | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | Pavilion dv6                | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
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
| Garuda Linux Soaring | 128       | 71.11%  |
| Garuda Linux         | 46        | 25.56%  |
| Garuda Linux Rolling | 6         | 3.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Garuda Linux | 177       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.17.9-zen1-1-zen  | 6         | 2.96%   |
| 6.0.2-zen1-1-zen   | 5         | 2.46%   |
| 5.16.16-zen1-1-zen | 4         | 1.97%   |
| 5.14.14-zen1-1-zen | 4         | 1.97%   |
| 5.13.13-zen1-1-zen | 4         | 1.97%   |
| 5.19.7-zen2-1-zen  | 3         | 1.48%   |
| 5.19.13-zen1-1-zen | 3         | 1.48%   |
| 5.19.10-zen1-1-zen | 3         | 1.48%   |
| 5.18.16-zen1-1-zen | 3         | 1.48%   |
| 5.17.3-zen1-1-zen  | 3         | 1.48%   |
| 5.17.1-zen1-1-zen  | 3         | 1.48%   |
| 5.16.4-zen1-1-zen  | 3         | 1.48%   |
| 5.16.2-zen1-1-zen  | 3         | 1.48%   |
| 5.15.6-zen2-1-zen  | 3         | 1.48%   |
| 5.15.2-zen1-1-zen  | 3         | 1.48%   |
| 5.15.12-zen1-1-zen | 3         | 1.48%   |
| 5.14.6-zen1-1-zen  | 3         | 1.48%   |
| 5.13.9-zen1-1-zen  | 3         | 1.48%   |
| 5.11.11-zen1-1-zen | 3         | 1.48%   |
| 5.10.1-103-tkg-bmq | 3         | 1.48%   |
| 5.19.2-zen1-1-zen  | 2         | 0.99%   |
| 5.19.11-zen1-1-zen | 2         | 0.99%   |
| 5.18.6-zen1-1-zen  | 2         | 0.99%   |
| 5.18.3-zen1-1-zen  | 2         | 0.99%   |
| 5.18.14-zen1-1-zen | 2         | 0.99%   |
| 5.17.5-zen1-1-zen  | 2         | 0.99%   |
| 5.16.8-arch1-1     | 2         | 0.99%   |
| 5.16.5-zen1-1-zen  | 2         | 0.99%   |
| 5.16.14-zen1-1-zen | 2         | 0.99%   |
| 5.16.1-zen1-1-zen  | 2         | 0.99%   |
| 5.15.5-zen1-1-zen  | 2         | 0.99%   |
| 5.15.4-zen1-1-zen  | 2         | 0.99%   |
| 5.15.13-zen1-1-zen | 2         | 0.99%   |
| 5.14.9-zen2-1-zen  | 2         | 0.99%   |
| 5.14.8-zen1-1-zen  | 2         | 0.99%   |
| 5.14.15-zen1-1-zen | 2         | 0.99%   |
| 5.13.5-zen1-1-zen  | 2         | 0.99%   |
| 5.12.9-zen1-1-zen  | 2         | 0.99%   |
| 5.12.15-zen1-1-zen | 2         | 0.99%   |
| 5.11.16-zen1-1-zen | 2         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.2   | 6         | 2.96%   |
| 5.17.9  | 6         | 2.96%   |
| 5.19.7  | 4         | 1.97%   |
| 5.18.16 | 4         | 1.97%   |
| 5.17.3  | 4         | 1.97%   |
| 5.17.1  | 4         | 1.97%   |
| 5.16.16 | 4         | 1.97%   |
| 5.14.14 | 4         | 1.97%   |
| 5.13.13 | 4         | 1.97%   |
| 5.11.11 | 4         | 1.97%   |
| 5.19.2  | 3         | 1.48%   |
| 5.19.13 | 3         | 1.48%   |
| 5.19.10 | 3         | 1.48%   |
| 5.18.3  | 3         | 1.48%   |
| 5.17.5  | 3         | 1.48%   |
| 5.16.4  | 3         | 1.48%   |
| 5.16.2  | 3         | 1.48%   |
| 5.15.6  | 3         | 1.48%   |
| 5.15.2  | 3         | 1.48%   |
| 5.15.12 | 3         | 1.48%   |
| 5.14.6  | 3         | 1.48%   |
| 5.13.9  | 3         | 1.48%   |
| 5.12.9  | 3         | 1.48%   |
| 5.10.15 | 3         | 1.48%   |
| 5.10.1  | 3         | 1.48%   |
| 6.0.1   | 2         | 0.99%   |
| 5.19.6  | 2         | 0.99%   |
| 5.19.11 | 2         | 0.99%   |
| 5.18.6  | 2         | 0.99%   |
| 5.18.5  | 2         | 0.99%   |
| 5.18.14 | 2         | 0.99%   |
| 5.16.8  | 2         | 0.99%   |
| 5.16.5  | 2         | 0.99%   |
| 5.16.14 | 2         | 0.99%   |
| 5.16.1  | 2         | 0.99%   |
| 5.15.7  | 2         | 0.99%   |
| 5.15.5  | 2         | 0.99%   |
| 5.15.4  | 2         | 0.99%   |
| 5.15.13 | 2         | 0.99%   |
| 5.15.11 | 2         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 29        | 14.72%  |
| 5.19    | 22        | 11.17%  |
| 5.16    | 21        | 10.66%  |
| 5.10    | 20        | 10.15%  |
| 5.14    | 19        | 9.64%   |
| 5.18    | 18        | 9.14%   |
| 5.17    | 18        | 9.14%   |
| 5.12    | 12        | 6.09%   |
| 5.11    | 12        | 6.09%   |
| 5.13    | 11        | 5.58%   |
| 6.0     | 9         | 4.57%   |
| 5.9     | 4         | 2.03%   |
| 5.6     | 1         | 0.51%   |
| 5.4     | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 177       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 115       | 63.89%  |
| GNOME             | 24        | 13.33%  |
| KDE               | 12        | 6.67%   |
| XFCE              | 9         | 5%      |
| X-Cinnamon        | 5         | 2.78%   |
| sway              | 5         | 2.78%   |
| qtile-default     | 2         | 1.11%   |
| Deepin            | 2         | 1.11%   |
| Yaru:ubuntu:GNOME | 1         | 0.56%   |
| Unity             | 1         | 0.56%   |
| MATE              | 1         | 0.56%   |
| i3                | 1         | 0.56%   |
| awesome           | 1         | 0.56%   |
| Unknown           | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 158       | 88.27%  |
| Wayland | 16        | 8.94%   |
| Unknown | 4         | 2.23%   |
| Tty     | 1         | 0.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 90        | 50%     |
| Unknown | 53        | 29.44%  |
| LightDM | 18        | 10%     |
| GDM     | 16        | 8.89%   |
| GREETD  | 3         | 1.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 88        | 49.16%  |
| en_GB   | 21        | 11.73%  |
| en_IN   | 15        | 8.38%   |
| de_DE   | 9         | 5.03%   |
| it_IT   | 8         | 4.47%   |
| pt_BR   | 5         | 2.79%   |
| en_CA   | 5         | 2.79%   |
| ru_RU   | 3         | 1.68%   |
| pl_PL   | 3         | 1.68%   |
| es_MX   | 3         | 1.68%   |
| nl_NL   | 2         | 1.12%   |
| fi_FI   | 2         | 1.12%   |
| es_CO   | 2         | 1.12%   |
| uk_UA   | 1         | 0.56%   |
| tr_TR   | 1         | 0.56%   |
| sv_SE   | 1         | 0.56%   |
| ko_KR   | 1         | 0.56%   |
| ja_JP   | 1         | 0.56%   |
| es_VE   | 1         | 0.56%   |
| es_ES   | 1         | 0.56%   |
| es_EC   | 1         | 0.56%   |
| en_ZA   | 1         | 0.56%   |
| en_DK   | 1         | 0.56%   |
| en_AG   | 1         | 0.56%   |
| de_AT   | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 119       | 66.48%  |
| BIOS | 60        | 33.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 173       | 97.74%  |
| Overlay | 2         | 1.13%   |
| XXXXX   | 1         | 0.56%   |
| F2fs    | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 116       | 65.17%  |
| Unknown | 52        | 29.21%  |
| MBR     | 10        | 5.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 165       | 92.7%   |
| Yes       | 13        | 7.3%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 68.72%  |
| Yes       | 56        | 31.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 39        | 22.03%  |
| Hewlett-Packard     | 29        | 16.38%  |
| ASUSTek Computer    | 26        | 14.69%  |
| Dell                | 25        | 14.12%  |
| Acer                | 18        | 10.17%  |
| MSI                 | 8         | 4.52%   |
| Samsung Electronics | 3         | 1.69%   |
| Razer               | 3         | 1.69%   |
| Notebook            | 3         | 1.69%   |
| Unknown             | 3         | 1.69%   |
| Toshiba             | 2         | 1.13%   |
| Medion              | 2         | 1.13%   |
| HUAWEI              | 2         | 1.13%   |
| Apple               | 2         | 1.13%   |
| Sony                | 1         | 0.56%   |
| PC Specialist       | 1         | 0.56%   |
| Panasonic           | 1         | 0.56%   |
| HONOR               | 1         | 0.56%   |
| GPU Company         | 1         | 0.56%   |
| Google              | 1         | 0.56%   |
| Gigabyte Technology | 1         | 0.56%   |
| Fujitsu Siemens     | 1         | 0.56%   |
| Fujitsu             | 1         | 0.56%   |
| Chuwi               | 1         | 0.56%   |
| Casper              | 1         | 0.56%   |
| Alienware           | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 4         | 2.26%   |
| Unknown                                    | 4         | 2.26%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 1.13%   |
| HP ProBook 640 G1                          | 2         | 1.13%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 1.13%   |
| HP Notebook                                | 2         | 1.13%   |
| Dell XPS 15 9500                           | 2         | 1.13%   |
| Dell Latitude E6420                        | 2         | 1.13%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 1.13%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 1.13%   |
| Acer Nitro AN515-44                        | 2         | 1.13%   |
| Acer Aspire A515-51G                       | 2         | 1.13%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.56%   |
| Toshiba Satellite C55-A                    | 1         | 0.56%   |
| Sony VPCSB1C5E                             | 1         | 0.56%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.56%   |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.56%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.56%   |
| Razer Blade 17 (Mid 2021) - RZ09-0406      | 1         | 0.56%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.56%   |
| Razer Blade                                | 1         | 0.56%   |
| PC Specialist GK5NPFO                      | 1         | 0.56%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.56%   |
| Notebook W54_W550SU2                       | 1         | 0.56%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.56%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.56%   |
| MSI Sword 15 A11UD                         | 1         | 0.56%   |
| MSI GS76 Stealth 11UG                      | 1         | 0.56%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.56%   |
| MSI GF63 Thin 9SC                          | 1         | 0.56%   |
| MSI GF63 Thin 10SC                         | 1         | 0.56%   |
| MSI GE75 Raider 9SE                        | 1         | 0.56%   |
| MSI GE72VR 6RF                             | 1         | 0.56%   |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.56%   |
| Medion P861X                               | 1         | 0.56%   |
| Medion E7419 MD60025                       | 1         | 0.56%   |
| Lenovo Z50-70 20354                        | 1         | 0.56%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB005WUS   | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8002MUS   | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 14        | 7.91%   |
| Lenovo IdeaPad         | 14        | 7.91%   |
| Dell Inspiron          | 9         | 5.08%   |
| ASUS VivoBook          | 9         | 5.08%   |
| Acer Aspire            | 9         | 5.08%   |
| HP Pavilion            | 8         | 4.52%   |
| Dell Latitude          | 8         | 4.52%   |
| HP Laptop              | 6         | 3.39%   |
| ASUS ROG               | 6         | 3.39%   |
| Lenovo Legion          | 5         | 2.82%   |
| Dell XPS               | 5         | 2.82%   |
| HP OMEN                | 4         | 2.26%   |
| Acer Swift             | 4         | 2.26%   |
| Acer Nitro             | 4         | 2.26%   |
| Unknown                | 4         | 2.26%   |
| Razer Blade            | 3         | 1.69%   |
| Toshiba Satellite      | 2         | 1.13%   |
| MSI GF63               | 2         | 1.13%   |
| HP ProBook             | 2         | 1.13%   |
| HP Notebook            | 2         | 1.13%   |
| HP EliteBook           | 2         | 1.13%   |
| Dell Precision         | 2         | 1.13%   |
| ASUS TUF               | 2         | 1.13%   |
| ASUS ASUS              | 2         | 1.13%   |
| Sony VPCSB1C5E         | 1         | 0.56%   |
| Samsung 550XCJ         | 1         | 0.56%   |
| Samsung 340XAA         | 1         | 0.56%   |
| Samsung 300V3A         | 1         | 0.56%   |
| PC Specialist GK5NPFO  | 1         | 0.56%   |
| Panasonic CF-191HYAX1M | 1         | 0.56%   |
| Notebook W54           | 1         | 0.56%   |
| Notebook P7xxDM2(-G)   | 1         | 0.56%   |
| Notebook N85           | 1         | 0.56%   |
| MSI Sword              | 1         | 0.56%   |
| MSI GS76               | 1         | 0.56%   |
| MSI GP75               | 1         | 0.56%   |
| MSI GE75               | 1         | 0.56%   |
| MSI GE72VR             | 1         | 0.56%   |
| MSI GE63               | 1         | 0.56%   |
| Medion P861X           | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 35        | 19.77%  |
| 2021 | 29        | 16.38%  |
| 2019 | 16        | 9.04%   |
| 2018 | 15        | 8.47%   |
| 2017 | 13        | 7.34%   |
| 2016 | 13        | 7.34%   |
| 2013 | 12        | 6.78%   |
| 2014 | 10        | 5.65%   |
| 2012 | 9         | 5.08%   |
| 2015 | 7         | 3.95%   |
| 2011 | 7         | 3.95%   |
| 2009 | 3         | 1.69%   |
| 2022 | 2         | 1.13%   |
| 2010 | 2         | 1.13%   |
| 2008 | 2         | 1.13%   |
| 2007 | 2         | 1.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 177       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 177       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 176       | 99.44%  |
| Yes  | 1         | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 32.4%   |
| 8.01-16.0   | 45        | 25.14%  |
| 16.01-24.0  | 43        | 24.02%  |
| 3.01-4.0    | 15        | 8.38%   |
| 32.01-64.0  | 12        | 6.7%    |
| 24.01-32.0  | 4         | 2.23%   |
| 2.01-3.0    | 1         | 0.56%   |
| 64.01-256.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 66        | 34.02%  |
| 2.01-3.0  | 53        | 27.32%  |
| 3.01-4.0  | 50        | 25.77%  |
| 1.01-2.0  | 15        | 7.73%   |
| 8.01-16.0 | 9         | 4.64%   |
| 0.51-1.0  | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 62.09%  |
| 2      | 56        | 30.77%  |
| 3      | 11        | 6.04%   |
| 4      | 1         | 0.55%   |
| 0      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 75.56%  |
| Yes       | 44        | 24.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 75.84%  |
| No        | 43        | 24.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 98.31%  |
| No        | 3         | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 88.76%  |
| No        | 20        | 11.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 49        | 27.37%  |
| India        | 15        | 8.38%   |
| Germany      | 15        | 8.38%   |
| UK           | 14        | 7.82%   |
| Italy        | 10        | 5.59%   |
| Canada       | 9         | 5.03%   |
| Poland       | 8         | 4.47%   |
| Brazil       | 7         | 3.91%   |
| Mexico       | 5         | 2.79%   |
| Netherlands  | 4         | 2.23%   |
| Russia       | 3         | 1.68%   |
| Romania      | 3         | 1.68%   |
| Finland      | 3         | 1.68%   |
| Turkey       | 2         | 1.12%   |
| Sweden       | 2         | 1.12%   |
| Spain        | 2         | 1.12%   |
| Singapore    | 2         | 1.12%   |
| France       | 2         | 1.12%   |
| Denmark      | 2         | 1.12%   |
| Colombia     | 2         | 1.12%   |
| Belgium      | 2         | 1.12%   |
| Venezuela    | 1         | 0.56%   |
| Switzerland  | 1         | 0.56%   |
| South Korea  | 1         | 0.56%   |
| South Africa | 1         | 0.56%   |
| Slovenia     | 1         | 0.56%   |
| Serbia       | 1         | 0.56%   |
| Oman         | 1         | 0.56%   |
| Luxembourg   | 1         | 0.56%   |
| Kuwait       | 1         | 0.56%   |
| Kenya        | 1         | 0.56%   |
| Japan        | 1         | 0.56%   |
| Indonesia    | 1         | 0.56%   |
| Hungary      | 1         | 0.56%   |
| Ecuador      | 1         | 0.56%   |
| Czechia      | 1         | 0.56%   |
| China        | 1         | 0.56%   |
| Bahrain      | 1         | 0.56%   |
| Austria      | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 4         | 2.13%   |
| Berlin             | 3         | 1.6%    |
| Wroclaw            | 2         | 1.06%   |
| Warsaw             | 2         | 1.06%   |
| Turin              | 2         | 1.06%   |
| Toronto            | 2         | 1.06%   |
| Singapore          | 2         | 1.06%   |
| San Jose           | 2         | 1.06%   |
| Portland           | 2         | 1.06%   |
| Peterborough       | 2         | 1.06%   |
| Mumbai             | 2         | 1.06%   |
| Milan              | 2         | 1.06%   |
| Helsinki           | 2         | 1.06%   |
| Düsseldorf        | 2         | 1.06%   |
| Delhi              | 2         | 1.06%   |
| Copenhagen         | 2         | 1.06%   |
| Chennai            | 2         | 1.06%   |
| Big Bend           | 2         | 1.06%   |
| Winston-Salem      | 1         | 0.53%   |
| Welwyn Garden City | 1         | 0.53%   |
| Wasilla            | 1         | 0.53%   |
| Vancouver          | 1         | 0.53%   |
| Valencia           | 1         | 0.53%   |
| Tustin             | 1         | 0.53%   |
| Turku              | 1         | 0.53%   |
| Tucson             | 1         | 0.53%   |
| Timișoara         | 1         | 0.53%   |
| Tarczyn            | 1         | 0.53%   |
| Sunrise Beach      | 1         | 0.53%   |
| Steenwijk          | 1         | 0.53%   |
| Sparks             | 1         | 0.53%   |
| Southampton        | 1         | 0.53%   |
| Sitka              | 1         | 0.53%   |
| Sighetu Marmaţiei | 1         | 0.53%   |
| Seattle            | 1         | 0.53%   |
| San Francisco      | 1         | 0.53%   |
| San Antonio        | 1         | 0.53%   |
| Rugby              | 1         | 0.53%   |
| Rotterdam          | 1         | 0.53%   |
| Rome               | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 41        | 52     | 16.47%  |
| Seagate                     | 32        | 36     | 12.85%  |
| WDC                         | 24        | 26     | 9.64%   |
| SK hynix                    | 19        | 25     | 7.63%   |
| SanDisk                     | 17        | 21     | 6.83%   |
| Intel                       | 11        | 14     | 4.42%   |
| HGST                        | 11        | 11     | 4.42%   |
| Unknown                     | 10        | 10     | 4.02%   |
| Toshiba                     | 10        | 12     | 4.02%   |
| Kingston                    | 8         | 8      | 3.21%   |
| Crucial                     | 7         | 10     | 2.81%   |
| Micron Technology           | 5         | 5      | 2.01%   |
| Hitachi                     | 5         | 5      | 2.01%   |
| KIOXIA                      | 4         | 6      | 1.61%   |
| Silicon Motion              | 3         | 3      | 1.2%    |
| PNY                         | 3         | 3      | 1.2%    |
| Phison Electronics          | 3         | 3      | 1.2%    |
| Phison                      | 3         | 3      | 1.2%    |
| LITEON                      | 3         | 3      | 1.2%    |
| Corsair                     | 3         | 3      | 1.2%    |
| Union Memory (Shenzhen)     | 2         | 2      | 0.8%    |
| China                       | 2         | 2      | 0.8%    |
| A-DATA Technology           | 2         | 2      | 0.8%    |
| Yangtze Memory Technologies | 1         | 1      | 0.4%    |
| WODPOSIT                    | 1         | 2      | 0.4%    |
| WDC WDS                     | 1         | 1      | 0.4%    |
| VisionTek                   | 1         | 2      | 0.4%    |
| UMIS                        | 1         | 2      | 0.4%    |
| SSSTC                       | 1         | 1      | 0.4%    |
| SPCC                        | 1         | 1      | 0.4%    |
| ShanDianZhe                 | 1         | 1      | 0.4%    |
| SABRENT                     | 1         | 2      | 0.4%    |
| PNY CS90                    | 1         | 1      | 0.4%    |
| Netac                       | 1         | 1      | 0.4%    |
| Mushkin                     | 1         | 1      | 0.4%    |
| Micron/Crucial Technology   | 1         | 1      | 0.4%    |
| LITEONIT                    | 1         | 1      | 0.4%    |
| Lenovo                      | 1         | 1      | 0.4%    |
| KIOXIA-EXCERIA              | 1         | 1      | 0.4%    |
| JMicron Technology          | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 8         | 3.07%   |
| Samsung NVMe SSD Drive 1TB             | 6         | 2.3%    |
| Seagate ST1000LM049-2GH172 1TB         | 5         | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 4         | 1.53%   |
| Samsung SSD 860 EVO 1TB                | 4         | 1.53%   |
| HGST HTS721010A9E630 1TB               | 4         | 1.53%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 1.15%   |
| Seagate ST1000LM014-1EJ164 1TB         | 3         | 1.15%   |
| Intel SSDPEKNU512GZ 512GB              | 3         | 1.15%   |
| WDC WDBNCE5000PNC 500GB SSD            | 2         | 0.77%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 2         | 0.77%   |
| Unknown MMC Card  16GB                 | 2         | 0.77%   |
| SK hynix SC311 SATA 256GB SSD          | 2         | 0.77%   |
| SK hynix NVMe SSD Drive 512GB          | 2         | 0.77%   |
| SK hynix HFM001TD3JX013N 1TB           | 2         | 0.77%   |
| Seagate ST2000LM015-2E8174 2TB         | 2         | 0.77%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.77%   |
| SanDisk NVMe SSD Drive 512GB           | 2         | 0.77%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 0.77%   |
| Samsung SSD 870 QVO 1TB                | 2         | 0.77%   |
| Samsung SSD 870 EVO 500GB              | 2         | 0.77%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.77%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD   | 2         | 0.77%   |
| PNY ELITE PSSD 240GB                   | 2         | 0.77%   |
| KIOXIA NVMe SSD Drive 512GB            | 2         | 0.77%   |
| Intel SSDPEKNW010T8 1TB                | 2         | 0.77%   |
| Intel SSD 660P Series 1024GB           | 2         | 0.77%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.77%   |
| HGST HTS541075A9E680 752GB             | 2         | 0.77%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.77%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 0.77%   |
| Corsair Force MP300 960GB              | 2         | 0.77%   |
| Yangtze Memory NVMe SSD Drive 256GB    | 1         | 0.38%   |
| WODPOSIT SSD WPSM28-256G               | 1         | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.38%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 1         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.38%   |
| WDC WDS 500G2B0B-00YS70 500GB SSD      | 1         | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.38%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 31        | 34     | 51.67%  |
| HGST    | 11        | 11     | 18.33%  |
| WDC     | 6         | 7      | 10%     |
| Toshiba | 5         | 7      | 8.33%   |
| Hitachi | 5         | 5      | 8.33%   |
| Unknown | 1         | 1      | 1.67%   |
| SABRENT | 1         | 2      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 25     | 28.38%  |
| SanDisk             | 8         | 11     | 10.81%  |
| Crucial             | 6         | 9      | 8.11%   |
| WDC                 | 5         | 6      | 6.76%   |
| Kingston            | 5         | 5      | 6.76%   |
| SK hynix            | 4         | 5      | 5.41%   |
| PNY                 | 3         | 3      | 4.05%   |
| LITEON              | 3         | 3      | 4.05%   |
| China               | 2         | 2      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| WODPOSIT            | 1         | 2      | 1.35%   |
| WDC WDS             | 1         | 1      | 1.35%   |
| VisionTek           | 1         | 2      | 1.35%   |
| Toshiba             | 1         | 1      | 1.35%   |
| PNY CS90            | 1         | 1      | 1.35%   |
| Netac               | 1         | 1      | 1.35%   |
| Mushkin             | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 1      | 1.35%   |
| LITEONIT            | 1         | 1      | 1.35%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.35%   |
| Intenso             | 1         | 1      | 1.35%   |
| FORESEE             | 1         | 1      | 1.35%   |
| Corsair             | 1         | 1      | 1.35%   |
| ASMT                | 1         | 1      | 1.35%   |
| Unknown             | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 91        | 122    | 39.39%  |
| SSD     | 70        | 88     | 30.3%   |
| HDD     | 57        | 67     | 24.68%  |
| MMC     | 10        | 10     | 4.33%   |
| Unknown | 3         | 3      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 103       | 141    | 47.25%  |
| NVMe | 90        | 121    | 41.28%  |
| SAS  | 15        | 18     | 6.88%   |
| MMC  | 10        | 10     | 4.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 75     | 50.39%  |
| 0.51-1.0   | 55        | 72     | 43.31%  |
| 1.01-2.0   | 6         | 6      | 4.72%   |
| 3.01-4.0   | 1         | 1      | 0.79%   |
| 4.01-10.0  | 1         | 1      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 67        | 36.81%  |
| 501-1000       | 38        | 20.88%  |
| 1001-2000      | 36        | 19.78%  |
| 2001-3000      | 17        | 9.34%   |
| Unknown        | 10        | 5.49%   |
| 251-500        | 6         | 3.3%    |
| 1-20           | 6         | 3.3%    |
| 101-250        | 2         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 28.88%  |
| 251-500        | 35        | 18.72%  |
| 501-1000       | 27        | 14.44%  |
| 1001-2000      | 25        | 13.37%  |
| 51-100         | 21        | 11.23%  |
| Unknown        | 10        | 5.35%   |
| 1-20           | 6         | 3.21%   |
| 2001-3000      | 5         | 2.67%   |
| More than 3000 | 4         | 2.14%   |

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
| Works    | 96        | 139    | 48.98%  |
| Detected | 89        | 140    | 45.41%  |
| Malfunc  | 11        | 11     | 5.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 115       | 48.94%  |
| AMD                            | 31        | 13.19%  |
| Samsung Electronics            | 21        | 8.94%   |
| SanDisk                        | 19        | 8.09%   |
| SK hynix                       | 15        | 6.38%   |
| Phison Electronics             | 9         | 3.83%   |
| KIOXIA                         | 4         | 1.7%    |
| Union Memory (Shenzhen)        | 3         | 1.28%   |
| Toshiba America Info Systems   | 3         | 1.28%   |
| Silicon Motion                 | 3         | 1.28%   |
| Micron Technology              | 3         | 1.28%   |
| Kingston Technology Company    | 3         | 1.28%   |
| Micron/Crucial Technology      | 2         | 0.85%   |
| Yangtze Memory Technologies    | 1         | 0.43%   |
| Solid State Storage Technology | 1         | 0.43%   |
| Nvidia                         | 1         | 0.43%   |
| Lenovo                         | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30        | 12.24%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 6.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 5.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 5.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 4.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 3.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.27%   |
| SK hynix Gold P31 SSD                                                          | 7         | 2.86%   |
| Intel SSD 660P Series                                                          | 6         | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.45%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.04%   |
| Phison E12 NVMe Controller                                                     | 5         | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 2.04%   |
| Intel Non-Volatile memory controller                                           | 5         | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 2.04%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 1.63%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.63%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.22%   |
| Micron Non-Volatile memory controller                                          | 3         | 1.22%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.22%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.82%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.82%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 0.82%   |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.41%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.41%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 119       | 51.29%  |
| NVMe | 88        | 37.93%  |
| RAID | 22        | 9.48%   |
| IDE  | 3         | 1.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 124       | 70.06%  |
| AMD    | 53        | 29.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 5.08%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 4.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 2.82%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 2.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 2.26%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.69%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.69%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 1.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.69%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.69%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.69%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.13%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.13%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.13%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.13%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.13%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 1.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.13%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.13%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.13%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.13%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 2         | 1.13%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 2         | 1.13%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 2         | 1.13%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.13%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.13%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.13%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 1.13%   |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz          | 1         | 0.56%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.56%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 52        | 29.38%  |
| Intel Core i5           | 31        | 17.51%  |
| AMD Ryzen 7             | 18        | 10.17%  |
| AMD Ryzen 5             | 17        | 9.6%    |
| Intel Core i3           | 16        | 9.04%   |
| Other                   | 13        | 7.34%   |
| Intel Celeron           | 5         | 2.82%   |
| AMD Ryzen 9             | 4         | 2.26%   |
| AMD A8                  | 4         | 2.26%   |
| Intel Pentium Silver    | 2         | 1.13%   |
| Intel Pentium           | 2         | 1.13%   |
| Intel Core 2 Duo        | 2         | 1.13%   |
| AMD Ryzen 7 PRO         | 2         | 1.13%   |
| AMD A10                 | 2         | 1.13%   |
| Intel Xeon              | 1         | 0.56%   |
| Intel Pentium Dual-Core | 1         | 0.56%   |
| Intel Core m3           | 1         | 0.56%   |
| AMD Turion              | 1         | 0.56%   |
| AMD FX                  | 1         | 0.56%   |
| AMD A6                  | 1         | 0.56%   |
| AMD A4                  | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 38.98%  |
| 4      | 56        | 31.64%  |
| 6      | 28        | 15.82%  |
| 8      | 24        | 13.56%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 177       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 157       | 88.7%   |
| 1      | 20        | 11.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 177       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 40.66%  |
| 0x306a9    | 8         | 4.4%    |
| 0x0a50000c | 8         | 4.4%    |
| 0x906ea    | 6         | 3.3%    |
| 0xa0652    | 5         | 2.75%   |
| 0x906e9    | 5         | 2.75%   |
| 0x806c1    | 5         | 2.75%   |
| 0x206a7    | 5         | 2.75%   |
| 0x08108109 | 5         | 2.75%   |
| 0x806ea    | 4         | 2.2%    |
| 0x306c3    | 4         | 2.2%    |
| 0x08600106 | 4         | 2.2%    |
| 0x08600103 | 4         | 2.2%    |
| 0x806e9    | 3         | 1.65%   |
| 0x506e3    | 3         | 1.65%   |
| 0x406e3    | 3         | 1.65%   |
| 0x08600104 | 3         | 1.65%   |
| 0x08108102 | 3         | 1.65%   |
| 0x806ec    | 2         | 1.1%    |
| 0x40651    | 2         | 1.1%    |
| 0x106e5    | 2         | 1.1%    |
| 0x0a50000b | 2         | 1.1%    |
| 0x08608103 | 2         | 1.1%    |
| 0x08101007 | 2         | 1.1%    |
| 0x06006705 | 2         | 1.1%    |
| 0xa0660    | 1         | 0.55%   |
| 0x806d1    | 1         | 0.55%   |
| 0x706e5    | 1         | 0.55%   |
| 0x706a8    | 1         | 0.55%   |
| 0x706a1    | 1         | 0.55%   |
| 0x506c9    | 1         | 0.55%   |
| 0x406c4    | 1         | 0.55%   |
| 0x306d4    | 1         | 0.55%   |
| 0x20655    | 1         | 0.55%   |
| 0x20652    | 1         | 0.55%   |
| 0x1067a    | 1         | 0.55%   |
| 0x10676    | 1         | 0.55%   |
| 0x07030106 | 1         | 0.55%   |
| 0x0700010f | 1         | 0.55%   |
| 0x06006110 | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 36        | 20.34%  |
| Zen 2           | 16        | 9.04%   |
| Zen 3           | 12        | 6.78%   |
| Skylake         | 12        | 6.78%   |
| Haswell         | 12        | 6.78%   |
| CometLake       | 11        | 6.21%   |
| SandyBridge     | 10        | 5.65%   |
| IvyBridge       | 10        | 5.65%   |
| Zen+            | 9         | 5.08%   |
| TigerLake       | 7         | 3.95%   |
| Broadwell       | 7         | 3.95%   |
| Unknown         | 5         | 2.82%   |
| Excavator       | 4         | 2.26%   |
| Puma            | 3         | 1.69%   |
| Penryn          | 3         | 1.69%   |
| Icelake         | 3         | 1.69%   |
| Goldmont plus   | 3         | 1.69%   |
| Zen             | 2         | 1.13%   |
| Westmere        | 2         | 1.13%   |
| Silvermont      | 2         | 1.13%   |
| Piledriver      | 2         | 1.13%   |
| Nehalem         | 2         | 1.13%   |
| Steamroller     | 1         | 0.56%   |
| K8 & K10 hybrid | 1         | 0.56%   |
| Jaguar          | 1         | 0.56%   |
| Goldmont        | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 44.79%  |
| Nvidia | 85        | 32.82%  |
| AMD    | 58        | 22.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                            | 16        | 5.99%   |
| AMD Cezanne                                                                           | 12        | 4.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 11        | 4.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 10        | 3.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 10        | 3.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 9         | 3.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 9         | 3.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 9         | 3.37%   |
| Intel UHD Graphics 620                                                                | 8         | 3%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 6         | 2.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 2.25%   |
| Intel HD Graphics 5500                                                                | 6         | 2.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 6         | 2.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 6         | 2.25%   |
| Nvidia TU117M                                                                         | 5         | 1.87%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 5         | 1.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 5         | 1.87%   |
| Intel HD Graphics 630                                                                 | 5         | 1.87%   |
| Intel HD Graphics 620                                                                 | 5         | 1.87%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 4         | 1.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 1.12%   |
| Nvidia GM108M [GeForce 840M]                                                          | 3         | 1.12%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 1.12%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                              | 3         | 1.12%   |
| Intel HD Graphics 530                                                                 | 3         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.12%   |
| Nvidia GM108M [GeForce MX110]                                                         | 2         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.75%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 2         | 0.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 2         | 0.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 2         | 0.75%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 2         | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 57        | 32.2%   |
| Intel + Nvidia     | 52        | 29.38%  |
| 1 x AMD            | 27        | 15.25%  |
| AMD + Nvidia       | 23        | 12.99%  |
| 1 x Nvidia         | 8         | 4.52%   |
| Intel + AMD        | 5         | 2.82%   |
| 2 x AMD            | 3         | 1.69%   |
| Intel + 2 x Nvidia | 2         | 1.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 114       | 63.69%  |
| Proprietary | 65        | 36.31%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 125       | 68.31%  |
| 0.01-0.5   | 29        | 15.85%  |
| 1.01-2.0   | 14        | 7.65%   |
| 3.01-4.0   | 6         | 3.28%   |
| 5.01-6.0   | 5         | 2.73%   |
| 0.51-1.0   | 3         | 1.64%   |
| 7.01-8.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 21.15%  |
| LG Display              | 32        | 15.38%  |
| BOE                     | 29        | 13.94%  |
| Chimei Innolux          | 28        | 13.46%  |
| Samsung Electronics     | 19        | 9.13%   |
| Sharp                   | 10        | 4.81%   |
| PANDA                   | 9         | 4.33%   |
| Dell                    | 6         | 2.88%   |
| Lenovo                  | 5         | 2.4%    |
| Goldstar                | 3         | 1.44%   |
| Sony                    | 2         | 0.96%   |
| CSO                     | 2         | 0.96%   |
| BenQ                    | 2         | 0.96%   |
| Apple                   | 2         | 0.96%   |
| AOC                     | 2         | 0.96%   |
| Acer                    | 2         | 0.96%   |
| Vizio                   | 1         | 0.48%   |
| Philips                 | 1         | 0.48%   |
| MStar                   | 1         | 0.48%   |
| Mi                      | 1         | 0.48%   |
| InfoVision              | 1         | 0.48%   |
| Hewlett-Packard         | 1         | 0.48%   |
| G-Story                 | 1         | 0.48%   |
| Eizo                    | 1         | 0.48%   |
| CPT                     | 1         | 0.48%   |
| Chi Mei Optoelectronics | 1         | 0.48%   |
| ASUSTek Computer        | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 1.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.92%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.44%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch               | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch  | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.96%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.96%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.96%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.96%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch           | 2         | 0.96%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 0.96%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 2         | 0.96%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.96%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 0.96%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                 | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch         | 2         | 0.96%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.48%   |
| Sony TV SNYA301 1920x1080                                             | 1         | 0.48%   |
| Sony TV *30 SNYB905 3840x2160 952x535mm 43.0-inch                     | 1         | 0.48%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 0.48%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.48%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.48%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch     | 1         | 0.48%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4652 1366x768 344x194mm 15.5-inch  | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 108       | 55.38%  |
| 1366x768 (WXGA)    | 35        | 17.95%  |
| 1600x900 (HD+)     | 11        | 5.64%   |
| 3840x2160 (4K)     | 9         | 4.62%   |
| 2560x1440 (QHD)    | 7         | 3.59%   |
| 2560x1600          | 4         | 2.05%   |
| 1920x1200 (WUXGA)  | 4         | 2.05%   |
| 1680x1050 (WSXGA+) | 4         | 2.05%   |
| 1280x800 (WXGA)    | 2         | 1.03%   |
| 3840x2400          | 1         | 0.51%   |
| 3440x1440          | 1         | 0.51%   |
| 3200x1800 (QHD+)   | 1         | 0.51%   |
| 2880x1800          | 1         | 0.51%   |
| 2880x1440          | 1         | 0.51%   |
| 2256x1504          | 1         | 0.51%   |
| 2160x1440          | 1         | 0.51%   |
| 1680x945           | 1         | 0.51%   |
| 1600x1200          | 1         | 0.51%   |
| 1440x900 (WXGA+)   | 1         | 0.51%   |
| 1280x720 (HD)      | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 107       | 51.69%  |
| 14      | 27        | 13.04%  |
| 13      | 16        | 7.73%   |
| 17      | 14        | 6.76%   |
| 27      | 8         | 3.86%   |
| 23      | 4         | 1.93%   |
| 21      | 4         | 1.93%   |
| 16      | 4         | 1.93%   |
| 31      | 3         | 1.45%   |
| 18      | 3         | 1.45%   |
| 24      | 2         | 0.97%   |
| 22      | 2         | 0.97%   |
| 20      | 2         | 0.97%   |
| Unknown | 2         | 0.97%   |
| 85      | 1         | 0.48%   |
| 72      | 1         | 0.48%   |
| 54      | 1         | 0.48%   |
| 52      | 1         | 0.48%   |
| 47      | 1         | 0.48%   |
| 43      | 1         | 0.48%   |
| 34      | 1         | 0.48%   |
| 12      | 1         | 0.48%   |
| 11      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 144       | 69.57%  |
| 351-400     | 16        | 7.73%   |
| 501-600     | 14        | 6.76%   |
| 401-500     | 11        | 5.31%   |
| 201-300     | 10        | 4.83%   |
| 601-700     | 3         | 1.45%   |
| 1001-1500   | 3         | 1.45%   |
| 1501-2000   | 2         | 0.97%   |
| Unknown     | 2         | 0.97%   |
| 701-800     | 1         | 0.48%   |
| 901-1000    | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 164       | 88.17%  |
| 16/10 | 17        | 9.14%   |
| 3/2   | 2         | 1.08%   |
| 4/3   | 1         | 0.54%   |
| 21/9  | 1         | 0.54%   |
| 2.00  | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 52.17%  |
| 81-90          | 38        | 18.36%  |
| 121-130        | 14        | 6.76%   |
| 201-250        | 11        | 5.31%   |
| 301-350        | 8         | 3.86%   |
| 71-80          | 5         | 2.42%   |
| More than 1000 | 4         | 1.93%   |
| 351-500        | 4         | 1.93%   |
| 141-150        | 3         | 1.45%   |
| 151-200        | 2         | 0.97%   |
| 111-120        | 2         | 0.97%   |
| 501-1000       | 2         | 0.97%   |
| Unknown        | 2         | 0.97%   |
| 61-70          | 1         | 0.48%   |
| 51-60          | 1         | 0.48%   |
| 251-300        | 1         | 0.48%   |
| 91-100         | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 110       | 53.92%  |
| 101-120       | 49        | 24.02%  |
| 51-100        | 21        | 10.29%  |
| 161-240       | 10        | 4.9%    |
| More than 240 | 7         | 3.43%   |
| 1-50          | 5         | 2.45%   |
| Unknown       | 2         | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 139       | 76.8%   |
| 2     | 41        | 22.65%  |
| 0     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 102       | 35.05%  |
| Intel                             | 100       | 34.36%  |
| Qualcomm Atheros                  | 41        | 14.09%  |
| Broadcom                          | 13        | 4.47%   |
| MediaTek                          | 8         | 2.75%   |
| Samsung Electronics               | 4         | 1.37%   |
| TP-Link                           | 2         | 0.69%   |
| Ralink Technology                 | 2         | 0.69%   |
| Qualcomm                          | 2         | 0.69%   |
| NetGear                           | 2         | 0.69%   |
| DisplayLink                       | 2         | 0.69%   |
| ASUSTek Computer                  | 2         | 0.69%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.34%   |
| Xiaomi                            | 1         | 0.34%   |
| Wacom                             | 1         | 0.34%   |
| Sierra Wireless                   | 1         | 0.34%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.34%   |
| Nvidia                            | 1         | 0.34%   |
| Motorola PCS                      | 1         | 0.34%   |
| Lenovo                            | 1         | 0.34%   |
| Ericsson Business Mobile Networks | 1         | 0.34%   |
| Dell                              | 1         | 0.34%   |
| ASIX Electronics                  | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 19.58%  |
| Intel Wi-Fi 6 AX200                                               | 20        | 5.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.78%   |
| Intel Wireless 7265                                               | 6         | 1.78%   |
| Intel Wireless 7260                                               | 6         | 1.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.48%   |
| Intel Wireless 3165                                               | 5         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 1.19%   |
| Intel Wireless 8260                                               | 4         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.19%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.89%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.89%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.89%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.89%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 96        | 51.06%  |
| Qualcomm Atheros      | 34        | 18.09%  |
| Realtek Semiconductor | 28        | 14.89%  |
| Broadcom              | 11        | 5.85%   |
| MediaTek              | 8         | 4.26%   |
| TP-Link               | 2         | 1.06%   |
| Ralink Technology     | 2         | 1.06%   |
| NetGear               | 2         | 1.06%   |
| ASUSTek Computer      | 2         | 1.06%   |
| Wacom                 | 1         | 0.53%   |
| Sierra Wireless       | 1         | 0.53%   |
| Dell                  | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 20        | 10.53%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 10        | 5.26%   |
| Intel Comet Lake PCH CNVi WiFi                                | 10        | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 9         | 4.74%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 9         | 4.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 8         | 4.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 3.68%   |
| Intel Wireless 8265 / 8275                                    | 6         | 3.16%   |
| Intel Wireless 7265                                           | 6         | 3.16%   |
| Intel Wireless 7260                                           | 6         | 3.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 5         | 2.63%   |
| Intel Wireless 3165                                           | 5         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 4         | 2.11%   |
| Intel Wireless 8260                                           | 4         | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 4         | 2.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 3         | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 1.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3         | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 1.58%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 1.58%   |
| Intel Centrino Advanced-N 6200                                | 3         | 1.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 1.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2         | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 2         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 1.05%   |
| Intel Centrino Ultimate-N 6300                                | 2         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                 | 2         | 1.05%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                      | 1         | 0.53%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A           | 1         | 0.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 0.53%   |
| Realtek RTL8191SEvA Wireless LAN Controller                   | 1         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.53%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 88        | 61.11%  |
| Intel                      | 27        | 18.75%  |
| Qualcomm Atheros           | 12        | 8.33%   |
| Samsung Electronics        | 4         | 2.78%   |
| Broadcom                   | 4         | 2.78%   |
| Qualcomm                   | 2         | 1.39%   |
| DisplayLink                | 2         | 1.39%   |
| ZTE WCDMA Technologies MSM | 1         | 0.69%   |
| Xiaomi                     | 1         | 0.69%   |
| Nvidia                     | 1         | 0.69%   |
| Lenovo                     | 1         | 0.69%   |
| ASIX Electronics           | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 45.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 2.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 2.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 2.08%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.08%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.39%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.69%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.69%   |
| Qualcomm SDM845-BERYLLIUM _SN:CD5379A7                            | 1         | 0.69%   |
| Qualcomm Mobile Router                                            | 1         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.69%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.69%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.69%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.69%   |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 55.77%  |
| Ethernet | 135       | 43.27%  |
| Unknown  | 2         | 0.64%   |
| Modem    | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 81.67%  |
| Ethernet | 33        | 18.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 121       | 68.36%  |
| 1     | 53        | 29.94%  |
| 3     | 2         | 1.13%   |
| 0     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 136       | 75.56%  |
| Yes  | 44        | 24.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 51.25%  |
| Qualcomm Atheros Communications | 21        | 13.13%  |
| Realtek Semiconductor           | 19        | 11.88%  |
| IMC Networks                    | 10        | 6.25%   |
| Foxconn / Hon Hai               | 7         | 4.38%   |
| Lite-On Technology              | 5         | 3.13%   |
| Broadcom                        | 5         | 3.13%   |
| Hewlett-Packard                 | 2         | 1.25%   |
| Dell                            | 2         | 1.25%   |
| Cambridge Silicon Radio         | 2         | 1.25%   |
| Apple                           | 2         | 1.25%   |
| Realtek                         | 1         | 0.63%   |
| ASUSTek Computer                | 1         | 0.63%   |
| AboCom Systems                  | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 15%     |
| Intel AX200 Bluetooth                                                               | 20        | 12.5%   |
| Intel AX201 Bluetooth                                                               | 16        | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 9.38%   |
| Realtek Bluetooth Radio                                                             | 9         | 5.63%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 5.63%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 4.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 3.75%   |
| IMC Networks Wireless_Device                                                        | 4         | 2.5%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.5%    |
| Intel AX210 Bluetooth                                                               | 3         | 1.88%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.25%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.25%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.63%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.63%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.63%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.63%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.63%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.63%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.63%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.63%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.63%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.63%   |
| ASUS BCM20702A0                                                                     | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 123       | 53.71%  |
| AMD                   | 53        | 23.14%  |
| Nvidia                | 41        | 17.9%   |
| Corsair               | 2         | 0.87%   |
| C-Media Electronics   | 2         | 0.87%   |
| Turtle Beach          | 1         | 0.44%   |
| RODE Microphones      | 1         | 0.44%   |
| Realtek Semiconductor | 1         | 0.44%   |
| Phison Electronics    | 1         | 0.44%   |
| JMTek                 | 1         | 0.44%   |
| Jieli Technology      | 1         | 0.44%   |
| Huawei Technologies   | 1         | 0.44%   |
| GN Netcom             | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 40        | 13.94%  |
| Intel Sunrise Point-LP HD Audio                                            | 22        | 7.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 6.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 4.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 4.18%   |
| Intel Comet Lake PCH cAVS                                                  | 10        | 3.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9         | 3.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.44%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.44%   |
| AMD FCH Azalia Controller                                                  | 7         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.09%   |
| Intel CM238 HD Audio Controller                                            | 6         | 2.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.09%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.09%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 2.09%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.39%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.39%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.39%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.05%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.7%    |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 0.7%    |
| Nvidia Audio device                                                        | 2         | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.7%    |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.7%    |
| AMD High Definition Audio Controller                                       | 2         | 0.7%    |
| Turtle Beach Ear Force P11 Headset                                         | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 30.32%  |
| SK hynix            | 30        | 19.35%  |
| Micron Technology   | 20        | 12.9%   |
| Crucial             | 13        | 8.39%   |
| Kingston            | 8         | 5.16%   |
| Ramaxel Technology  | 7         | 4.52%   |
| A-DATA Technology   | 6         | 3.87%   |
| Unknown             | 4         | 2.58%   |
| Corsair             | 4         | 2.58%   |
| Smart               | 3         | 1.94%   |
| Nanya Technology    | 3         | 1.94%   |
| Unknown (ABCD)      | 2         | 1.29%   |
| Transcend           | 1         | 0.65%   |
| Timetec             | 1         | 0.65%   |
| Patriot             | 1         | 0.65%   |
| G.Skill             | 1         | 0.65%   |
| Elpida              | 1         | 0.65%   |
| CSX                 | 1         | 0.65%   |
| Avant               | 1         | 0.65%   |
| 48spaces            | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 4.24%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 3.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 3.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.42%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.21%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.21%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.21%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.21%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 1.21%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.21%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.21%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.21%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 1.21%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.21%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 1.21%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.61%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.61%   |
| Timetec RAM SD4-3200 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.61%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.61%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.61%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.61%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.61%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 81        | 62.79%  |
| DDR3   | 37        | 28.68%  |
| LPDDR4 | 6         | 4.65%   |
| LPDDR3 | 3         | 2.33%   |
| DDR2   | 2         | 1.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 120       | 90.91%  |
| Row Of Chips | 10        | 7.58%   |
| Chip         | 1         | 0.76%   |
| Unknown      | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 71        | 49.65%  |
| 4096  | 47        | 32.87%  |
| 16384 | 20        | 13.99%  |
| 2048  | 5         | 3.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 43        | 30.07%  |
| 2667  | 31        | 21.68%  |
| 1600  | 31        | 21.68%  |
| 2400  | 15        | 10.49%  |
| 1334  | 4         | 2.8%    |
| 4266  | 3         | 2.1%    |
| 3266  | 3         | 2.1%    |
| 2133  | 3         | 2.1%    |
| 1867  | 2         | 1.4%    |
| 1333  | 2         | 1.4%    |
| 667   | 2         | 1.4%    |
| 8400  | 1         | 0.7%    |
| 3733  | 1         | 0.7%    |
| 1866  | 1         | 0.7%    |
| 800   | 1         | 0.7%    |

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
| Chicony Electronics                    | 40        | 25.16%  |
| IMC Networks                           | 23        | 14.47%  |
| Microdia                               | 13        | 8.18%   |
| Acer                                   | 12        | 7.55%   |
| Sunplus Innovation Technology          | 10        | 6.29%   |
| Realtek Semiconductor                  | 10        | 6.29%   |
| Quanta                                 | 10        | 6.29%   |
| Syntek                                 | 6         | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.77%   |
| Suyin                                  | 4         | 2.52%   |
| Luxvisions Innotech Limited            | 4         | 2.52%   |
| Silicon Motion                         | 3         | 1.89%   |
| Logitech                               | 3         | 1.89%   |
| Lite-On Technology                     | 3         | 1.89%   |
| Apple                                  | 3         | 1.89%   |
| Microsoft                              | 2         | 1.26%   |
| WaveRider Communications               | 1         | 0.63%   |
| Sonix Technology                       | 1         | 0.63%   |
| Samsung Electronics                    | 1         | 0.63%   |
| Lenovo                                 | 1         | 0.63%   |
| Importek                               | 1         | 0.63%   |
| Genesys Logic                          | 1         | 0.63%   |
| Creative Technology                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 12        | 7.5%    |
| Microdia Integrated_Webcam_HD                                   | 7         | 4.38%   |
| Chicony Integrated Camera                                       | 7         | 4.38%   |
| Chicony HD WebCam                                               | 7         | 4.38%   |
| IMC Networks Integrated Camera                                  | 6         | 3.75%   |
| Syntek Integrated Camera                                        | 4         | 2.5%    |
| Sunplus Integrated_Webcam_HD                                    | 4         | 2.5%    |
| Chicony HD User Facing                                          | 4         | 2.5%    |
| Acer HD Webcam                                                  | 4         | 2.5%    |
| Quanta HP Wide Vision HD Camera                                 | 3         | 1.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 1.88%   |
| Chicony HP Wide Vision HD Camera                                | 3         | 1.88%   |
| Acer Integrated Camera                                          | 3         | 1.88%   |
| Silicon Motion Web Camera                                       | 2         | 1.25%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 1.25%   |
| Quanta HD User Facing                                           | 2         | 1.25%   |
| Microdia Webcam Vitade AF                                       | 2         | 1.25%   |
| Logitech HD Pro Webcam C920                                     | 2         | 1.25%   |
| Lite-On HP Wide Vision HD Camera                                | 2         | 1.25%   |
| IMC Networks HD Camera                                          | 2         | 1.25%   |
| Chicony USB2.0 HD UVC WebCam                                    | 2         | 1.25%   |
| Chicony USB2.0 Camera                                           | 2         | 1.25%   |
| Chicony USB 2.0 Camera                                          | 2         | 1.25%   |
| Chicony HP Truevision HD                                        | 2         | 1.25%   |
| Chicony EasyCamera                                              | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 2         | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 2         | 1.25%   |
| WaveRider USB Live camera                                       | 1         | 0.63%   |
| Syntek Lenovo EasyCamera                                        | 1         | 0.63%   |
| Syntek EasyCamera                                               | 1         | 0.63%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 0.63%   |
| Suyin HP Truevision HD                                          | 1         | 0.63%   |
| Suyin HD WebCam                                                 | 1         | 0.63%   |
| Suyin Acer CrystalEye Webcam                                    | 1         | 0.63%   |
| Sunplus MTD Camera                                              | 1         | 0.63%   |
| Sunplus Lenovo EasyCamera                                       | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_FHD                            | 1         | 0.63%   |
| Sunplus Integrated Webcam                                       | 1         | 0.63%   |
| Sunplus Integrated Camera                                       | 1         | 0.63%   |

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
| LighTuning EgisTec_ES603                          | 1         | 3.23%   |
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
| 1     | 87        | 48.33%  |
| 2     | 45        | 25%     |
| 0     | 40        | 22.22%  |
| 3     | 7         | 3.89%   |
| 4     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 118       | 57.84%  |
| Fingerprint reader       | 31        | 15.2%   |
| Graphics card            | 14        | 6.86%   |
| Chipcard                 | 14        | 6.86%   |
| Net/wireless             | 7         | 3.43%   |
| Net/ethernet             | 5         | 2.45%   |
| Multimedia controller    | 5         | 2.45%   |
| Camera                   | 4         | 1.96%   |
| Storage                  | 3         | 1.47%   |
| Wireless                 | 1         | 0.49%   |
| Network                  | 1         | 0.49%   |
| Bluetooth                | 1         | 0.49%   |

