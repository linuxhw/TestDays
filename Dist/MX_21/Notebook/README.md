MX 21 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 343

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G2            | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Notebook      | NL5xNU                      | [768e7b97fc](https://linux-hardware.org/?probe=768e7b97fc) | Aug 19, 2023 |
| Dell          | Latitude E5410              | [4ae8d448a2](https://linux-hardware.org/?probe=4ae8d448a2) | Aug 14, 2023 |
| HP            | 250 G8 Notebook PC          | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| HP            | 620                         | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Acer          | Aspire E1-532               | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f84a39b436](https://linux-hardware.org/?probe=f84a39b436) | Jul 31, 2023 |
| Acer          | Aspire V3-571G              | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| CONNEX        | L1415-BAY                   | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| Acer          | Aspire 4750                 | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| Dell          | System XPS L502X            | [e6b4c3cf4e](https://linux-hardware.org/?probe=e6b4c3cf4e) | Jul 12, 2023 |
| Acer          | Aspire ES1-511              | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| HP            | 620                         | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Acer          | Aspire A515-47              | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| ASUSTek       | GL703VD                     | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| Alienware     | m16 R1 AMD                  | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| Acer          | Aspire E5-573               | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| HP            | ProBook 450 G1              | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| Dell          | Latitude E6510              | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ed43d5454c](https://linux-hardware.org/?probe=ed43d5454c) | Jun 18, 2023 |
| Dell          | Latitude 3190               | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| HP            | Laptop 15-dw1xxx            | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Dell          | Latitude E6540              | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| ASUSTek       | X205TA                      | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Dell          | Latitude 3190               | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Dell          | Latitude E6510              | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| Dell          | Latitude E6510              | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| MSI           | U200                        | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [51d10ac11e](https://linux-hardware.org/?probe=51d10ac11e) | Jun 02, 2023 |
| HP            | EliteBook 8460p             | [c46684adac](https://linux-hardware.org/?probe=c46684adac) | Jun 02, 2023 |
| Dell          | Latitude 5540               | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Unknown       | Unknown                     | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Dell          | Latitude 3190               | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Dell          | Latitude E6510              | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| Sony          | SVE1513Q1ESI                | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| Casper        | EXCALIBUR G770              | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| HUAWEI        | HLYL-WXX9                   | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| Dell          | Latitude 3190               | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Dell          | Latitude E6510              | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| Dell          | Latitude E6510              | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e6746606b4](https://linux-hardware.org/?probe=e6746606b4) | May 19, 2023 |
| Dell          | Latitude 3190               | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Acer          | Aspire A315-59              | [4c33c99aab](https://linux-hardware.org/?probe=4c33c99aab) | May 14, 2023 |
| ASUSTek       | X202E                       | [d6b7617a17](https://linux-hardware.org/?probe=d6b7617a17) | May 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [08afd40365](https://linux-hardware.org/?probe=08afd40365) | May 13, 2023 |
| Acer          | Extensa 5220                | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| Acer          | Aspire 5715Z                | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Dell          | Latitude 3190               | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| HP            | Pro Tablet 10 EE G1         | [6af53fb237](https://linux-hardware.org/?probe=6af53fb237) | May 05, 2023 |
| Lenovo        | ThinkPad T460s 20F9003GU... | [7a570efe74](https://linux-hardware.org/?probe=7a570efe74) | May 05, 2023 |
| Apple         | MacBookPro7,1               | [8349b363f4](https://linux-hardware.org/?probe=8349b363f4) | May 03, 2023 |
| Apple         | MacBookPro7,1               | [49971d9c29](https://linux-hardware.org/?probe=49971d9c29) | May 03, 2023 |
| Apple         | MacBookAir3,1               | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| Lenovo        | ThinkPad X260 20F5S89L02    | [4e2f57ccc3](https://linux-hardware.org/?probe=4e2f57ccc3) | May 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [a36c4e671d](https://linux-hardware.org/?probe=a36c4e671d) | May 02, 2023 |
| Dell          | Latitude 3190               | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Apple         | MacBookPro6,2               | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [539369db0e](https://linux-hardware.org/?probe=539369db0e) | Apr 28, 2023 |
| HP            | EliteBook 6930p             | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| Dell          | Latitude 3190               | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| HP            | G42                         | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| Compal        | HEL81I                      | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Google        | Akali 360                   | [2d18714bb2](https://linux-hardware.org/?probe=2d18714bb2) | Apr 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| HP            | Laptop 17-cn0xxx            | [843dd1e105](https://linux-hardware.org/?probe=843dd1e105) | Apr 18, 2023 |
| ASUSTek       | 1015PX                      | [c271ba95b9](https://linux-hardware.org/?probe=c271ba95b9) | Apr 16, 2023 |
| ASUSTek       | 1015PX                      | [494fc3e648](https://linux-hardware.org/?probe=494fc3e648) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | [3d53b9ee9e](https://linux-hardware.org/?probe=3d53b9ee9e) | Apr 12, 2023 |
| Dell          | Latitude 3190               | [c2a70674ac](https://linux-hardware.org/?probe=c2a70674ac) | Apr 10, 2023 |
| Lenovo        | ThinkPad X220 4290WC7       | [07ed4faaa0](https://linux-hardware.org/?probe=07ed4faaa0) | Apr 10, 2023 |
| Dell          | Latitude 3190               | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9a5c9ee256](https://linux-hardware.org/?probe=9a5c9ee256) | Apr 02, 2023 |
| Sony          | VPCCB32FD                   | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| Dell          | Latitude 3190               | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Sony          | VPCCB32FD                   | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [498bb39808](https://linux-hardware.org/?probe=498bb39808) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| Dell          | Latitude 3190               | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [978df2886a](https://linux-hardware.org/?probe=978df2886a) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Dell          | Latitude E5570              | [dc6436b8b2](https://linux-hardware.org/?probe=dc6436b8b2) | Mar 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [9f3f315f73](https://linux-hardware.org/?probe=9f3f315f73) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [42653f8c2a](https://linux-hardware.org/?probe=42653f8c2a) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [7ccc0f584e](https://linux-hardware.org/?probe=7ccc0f584e) | Mar 14, 2023 |
| Dell          | Latitude 3190               | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| HP            | Laptop 17-ak0xx             | [7d35815562](https://linux-hardware.org/?probe=7d35815562) | Mar 13, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| Dell          | Inspiron 15 3511            | [153652da71](https://linux-hardware.org/?probe=153652da71) | Mar 07, 2023 |
| Dell          | Latitude 3190               | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| HP            | 255 G3                      | [9ccab85062](https://linux-hardware.org/?probe=9ccab85062) | Mar 04, 2023 |
| Dell          | Inspiron 15 3511            | [a84948f124](https://linux-hardware.org/?probe=a84948f124) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 620                         | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | [5718d685e4](https://linux-hardware.org/?probe=5718d685e4) | Mar 02, 2023 |
| Chuwi         | GemiBook Pro                | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | [5fe3c354ff](https://linux-hardware.org/?probe=5fe3c354ff) | Mar 02, 2023 |
| Dell          | Inspiron 15 3511            | [a15227fc75](https://linux-hardware.org/?probe=a15227fc75) | Mar 02, 2023 |
| Dell          | Latitude 3190               | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| HP            | 250 G7 Notebook PC          | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| Dell          | Latitude 3190               | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| Acer          | Nitro AN515-55              | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| HP            | 450                         | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Dell          | Latitude 3190               | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | GL752VW                     | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| HP            | EliteBook 2570p             | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Dell          | Latitude 3190               | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Dell          | Latitude 3190               | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| AMI           | Intel                       | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | Latitude 3190               | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Dell          | Latitude 3190               | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| Toshiba       | Satellite M70               | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | Latitude 3190               | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| Dell          | Latitude 3190               | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | Latitude 3190               | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Dell          | Latitude 3190               | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| Acer          | Aspire ES1-732              | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| Dell          | Latitude 3190               | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| Vulcan Ele... | Excursion XB                | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Dell          | Latitude 3190               | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| win elemen... | MoreFine S500+              | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Dell          | Latitude 3190               | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| HP            | Laptop 17-ak0xx             | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Dell          | Latitude 3190               | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| HP            | 250 G6 Notebook PC          | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| Dell          | Inspiron 5521               | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Dell          | System XPS 15Z              | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Dell          | Vostro 3550                 | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Alienware     | 13 R2                       | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| Sony          | VPCSB1V9R                   | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| Acer          | Aspire A515-56              | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 25        | 10.59%  |
| 6.0.0-6mx-amd64            | 22        | 9.32%   |
| 5.10.0-23-amd64            | 16        | 6.78%   |
| 5.10.0-13-amd64            | 15        | 6.36%   |
| 5.10.0-9-amd64             | 14        | 5.93%   |
| 5.10.0-18-amd64            | 13        | 5.51%   |
| 5.10.0-16-amd64            | 9         | 3.81%   |
| 5.16.0-5mx-amd64           | 8         | 3.39%   |
| 5.14.0-4mx-amd64           | 8         | 3.39%   |
| 5.10.0-20-amd64            | 8         | 3.39%   |
| 5.10.0-19-amd64            | 8         | 3.39%   |
| 5.10.0-14-amd64            | 6         | 2.54%   |
| 5.10.0-11-amd64            | 6         | 2.54%   |
| 6.0.0-4mx-amd64            | 5         | 2.12%   |
| 5.18.0-4mx-amd64           | 5         | 2.12%   |
| 5.10.0-22-amd64            | 5         | 2.12%   |
| 5.10.0-17-amd64            | 3         | 1.27%   |
| 6.1.0-9mx-ahs-amd64        | 2         | 0.85%   |
| 6.1.0-8mx-ahs-amd64        | 2         | 0.85%   |
| 6.1.0-4mx-amd64            | 2         | 0.85%   |
| 6.0.0-3mx-amd64            | 2         | 0.85%   |
| 6.0.0-10.1-liquorix-amd64  | 2         | 0.85%   |
| 5.19.0-2mx-amd64           | 2         | 0.85%   |
| 5.16.0-6mx-amd64           | 2         | 0.85%   |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.85%   |
| 5.10.0-8-amd64             | 2         | 0.85%   |
| 5.10.0-23-686-pae          | 2         | 0.85%   |
| 5.10.0-20-686-pae          | 2         | 0.85%   |
| 5.10.0-15-amd64            | 2         | 0.85%   |
| 5.10.0-13-686-pae          | 2         | 0.85%   |
| 5.10.0-11-686-pae          | 2         | 0.85%   |
| 5.10.0-10-amd64            | 2         | 0.85%   |
| 6.4.3-1-liquorix-amd64     | 1         | 0.42%   |
| 6.3.0-2mx-ahs-amd64        | 1         | 0.42%   |
| 6.2.7-x64v4-xanmod1        | 1         | 0.42%   |
| 6.1.15-2-liquorix-amd64    | 1         | 0.42%   |
| 6.1.12-3-liquorix-amd64    | 1         | 0.42%   |
| 6.1.0-7mx-ahs-amd64        | 1         | 0.42%   |
| 6.1.0-2mx-amd64            | 1         | 0.42%   |
| 6.0.0-11.2-liquorix-amd64  | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 137       | 61.16%  |
| 6.0.0    | 32        | 14.29%  |
| 5.16.0   | 13        | 5.8%    |
| 6.1.0    | 8         | 3.57%   |
| 5.14.0   | 8         | 3.57%   |
| 5.18.0   | 7         | 3.13%   |
| 5.19.0   | 5         | 2.23%   |
| 5.17.0   | 4         | 1.79%   |
| 6.4.3    | 1         | 0.45%   |
| 6.3.0    | 1         | 0.45%   |
| 6.2.7    | 1         | 0.45%   |
| 6.1.15   | 1         | 0.45%   |
| 6.1.12   | 1         | 0.45%   |
| 5.15.0   | 1         | 0.45%   |
| 5.10.82  | 1         | 0.45%   |
| 5.10.142 | 1         | 0.45%   |
| 4.19.0   | 1         | 0.45%   |
| Unknown  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 139       | 62.05%  |
| 6.0     | 32        | 14.29%  |
| 5.16    | 13        | 5.8%    |
| 6.1     | 10        | 4.46%   |
| 5.14    | 8         | 3.57%   |
| 5.18    | 7         | 3.13%   |
| 5.19    | 5         | 2.23%   |
| 5.17    | 4         | 1.79%   |
| 6.4     | 1         | 0.45%   |
| 6.3     | 1         | 0.45%   |
| 6.2     | 1         | 0.45%   |
| 5.15    | 1         | 0.45%   |
| 4.19    | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 202       | 94.84%  |
| i686   | 11        | 5.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 154       | 70.97%  |
| KDE5             | 44        | 20.28%  |
| GNOME            | 4         | 1.84%   |
| Unknown          | 4         | 1.84%   |
| Budgie           | 3         | 1.38%   |
| lightdm-xsession | 2         | 0.92%   |
| fluxbox          | 2         | 0.92%   |
| X-Cinnamon       | 1         | 0.46%   |
| LXQt             | 1         | 0.46%   |
| i3               | 1         | 0.46%   |
| GNOME Classic    | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 210       | 98.59%  |
| Tty     | 2         | 0.94%   |
| Wayland | 1         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 169       | 78.6%   |
| SDDM    | 42        | 19.53%  |
| SLiM    | 3         | 1.4%    |
| Unknown | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 104       | 48.37%  |
| de_DE   | 27        | 12.56%  |
| en_GB   | 13        | 6.05%   |
| it_IT   | 10        | 4.65%   |
| ru_RU   | 7         | 3.26%   |
| fr_FR   | 7         | 3.26%   |
| pl_PL   | 4         | 1.86%   |
| Unknown | 4         | 1.86%   |
| es_ES   | 3         | 1.4%    |
| en_NZ   | 3         | 1.4%    |
| en_AU   | 3         | 1.4%    |
| de_CH   | 3         | 1.4%    |
| tr_TR   | 2         | 0.93%   |
| pt_BR   | 2         | 0.93%   |
| nl_NL   | 2         | 0.93%   |
| fi_FI   | 2         | 0.93%   |
| es_MX   | 2         | 0.93%   |
| es_AR   | 2         | 0.93%   |
| bg_BG   | 2         | 0.93%   |
| sk_SK   | 1         | 0.47%   |
| ro_RO   | 1         | 0.47%   |
| nl_BE   | 1         | 0.47%   |
| nb_NO   | 1         | 0.47%   |
| id_ID   | 1         | 0.47%   |
| hu_HU   | 1         | 0.47%   |
| fr_CA   | 1         | 0.47%   |
| fr_BE   | 1         | 0.47%   |
| es_VE   | 1         | 0.47%   |
| es_UY   | 1         | 0.47%   |
| es_PE   | 1         | 0.47%   |
| es_CO   | 1         | 0.47%   |
| en_CA   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 155       | 72.77%  |
| BIOS | 58        | 27.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 179       | 82.87%  |
| Overlay | 26        | 12.04%  |
| Btrfs   | 9         | 4.17%   |
| Xfs     | 1         | 0.46%   |
| F2fs    | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 159       | 74.65%  |
| MBR     | 53        | 24.88%  |
| Unknown | 1         | 0.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 77.67%  |
| Yes       | 48        | 22.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 128       | 59.81%  |
| Yes       | 86        | 40.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 41        | 19.25%  |
| Hewlett-Packard           | 39        | 18.31%  |
| ASUSTek Computer          | 26        | 12.21%  |
| Dell                      | 22        | 10.33%  |
| Acer                      | 20        | 9.39%   |
| Apple                     | 10        | 4.69%   |
| Sony                      | 8         | 3.76%   |
| MSI                       | 5         | 2.35%   |
| Toshiba                   | 4         | 1.88%   |
| Medion                    | 4         | 1.88%   |
| Alienware                 | 4         | 1.88%   |
| Samsung Electronics       | 3         | 1.41%   |
| Fujitsu Siemens           | 3         | 1.41%   |
| TUXEDO                    | 2         | 0.94%   |
| Notebook                  | 2         | 0.94%   |
| Gigabyte Technology       | 2         | 0.94%   |
| Chuwi                     | 2         | 0.94%   |
| Unknown                   | 2         | 0.94%   |
| win element               | 1         | 0.47%   |
| Vulcan Electronics        | 1         | 0.47%   |
| SANTECH                   | 1         | 0.47%   |
| RTD Embedded Technologies | 1         | 0.47%   |
| Linx                      | 1         | 0.47%   |
| HUAWEI                    | 1         | 0.47%   |
| Google                    | 1         | 0.47%   |
| Framework                 | 1         | 0.47%   |
| F-Plus Mobile             | 1         | 0.47%   |
| efirstview                | 1         | 0.47%   |
| CONNEX                    | 1         | 0.47%   |
| Compal                    | 1         | 0.47%   |
| Casper                    | 1         | 0.47%   |
| AMI                       | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 3         | 1.41%   |
| HP ProBook 450 G1                   | 2         | 0.94%   |
| HP Pavilion Laptop 15-eh1xxx        | 2         | 0.94%   |
| HP Laptop 17-ak0xx                  | 2         | 0.94%   |
| Chuwi GemiBook Pro                  | 2         | 0.94%   |
| Apple MacBookAir7,2                 | 2         | 0.94%   |
| Acer Nitro AN515-55                 | 2         | 0.94%   |
| win element MoreFine S500+          | 1         | 0.47%   |
| Vulcan Excursion XB                 | 1         | 0.47%   |
| TUXEDO N7x0WU                       | 1         | 0.47%   |
| TUXEDO InfinityBook Pro Gen7 (MK1)  | 1         | 0.47%   |
| Toshiba Satellite M70               | 1         | 0.47%   |
| Toshiba Satellite L650              | 1         | 0.47%   |
| Toshiba Satellite C845              | 1         | 0.47%   |
| Toshiba PORTEGE Z30-C               | 1         | 0.47%   |
| Sony VPCYB3V1E                      | 1         | 0.47%   |
| Sony VPCSB1V9R                      | 1         | 0.47%   |
| Sony VPCF119FX                      | 1         | 0.47%   |
| Sony VPCEH2N1E                      | 1         | 0.47%   |
| Sony VPCEC3S1E                      | 1         | 0.47%   |
| Sony VPCCB32FD                      | 1         | 0.47%   |
| Sony VGN-TZ3RXN_B                   | 1         | 0.47%   |
| Sony SVE1513Q1ESI                   | 1         | 0.47%   |
| SANTECH X170KM-G                    | 1         | 0.47%   |
| Samsung NC210/NC110                 | 1         | 0.47%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.47%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.47%   |
| RTD Embedded CMA34CR                | 1         | 0.47%   |
| Notebook PD5x_7xPNP_PNN_PNT         | 1         | 0.47%   |
| Notebook NL5xNU                     | 1         | 0.47%   |
| MSI U200                            | 1         | 0.47%   |
| MSI Modern 14 B11MOL                | 1         | 0.47%   |
| MSI GV62 8RD                        | 1         | 0.47%   |
| MSI GF63 Thin 9SC                   | 1         | 0.47%   |
| MSI Alpha 15 B5EEK                  | 1         | 0.47%   |
| Medion P6634                        | 1         | 0.47%   |
| Medion E7424 MD60750                | 1         | 0.47%   |
| Medion E14304                       | 1         | 0.47%   |
| Medion E1239T MD60139               | 1         | 0.47%   |
| Linx LINX1010B                      | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 23        | 10.8%   |
| Acer Aspire          | 13        | 6.1%    |
| HP EliteBook         | 8         | 3.76%   |
| Dell Latitude        | 8         | 3.76%   |
| Lenovo IdeaPad       | 7         | 3.29%   |
| HP ProBook           | 6         | 2.82%   |
| HP Laptop            | 6         | 2.82%   |
| Dell Inspiron        | 6         | 2.82%   |
| ASUS VivoBook        | 5         | 2.35%   |
| HP Pavilion          | 4         | 1.88%   |
| Toshiba Satellite    | 3         | 1.41%   |
| HP 250               | 3         | 1.41%   |
| Dell Vostro          | 3         | 1.41%   |
| Acer Nitro           | 3         | 1.41%   |
| Unknown              | 3         | 1.41%   |
| Lenovo ThinkBook     | 2         | 0.94%   |
| Lenovo Legion        | 2         | 0.94%   |
| HP ZBook             | 2         | 0.94%   |
| HP Compaq            | 2         | 0.94%   |
| Dell System          | 2         | 0.94%   |
| Dell Precision       | 2         | 0.94%   |
| Chuwi GemiBook       | 2         | 0.94%   |
| ASUS TUF             | 2         | 0.94%   |
| ASUS ROG             | 2         | 0.94%   |
| ASUS ASUS            | 2         | 0.94%   |
| Apple MacBookPro11   | 2         | 0.94%   |
| Apple MacBookAir7    | 2         | 0.94%   |
| Alienware m15        | 2         | 0.94%   |
| Acer Swift           | 2         | 0.94%   |
| win element MoreFine | 1         | 0.47%   |
| Vulcan Excursion     | 1         | 0.47%   |
| TUXEDO N7x0WU        | 1         | 0.47%   |
| TUXEDO InfinityBook  | 1         | 0.47%   |
| Toshiba PORTEGE      | 1         | 0.47%   |
| Sony VPCYB3V1E       | 1         | 0.47%   |
| Sony VPCSB1V9R       | 1         | 0.47%   |
| Sony VPCF119FX       | 1         | 0.47%   |
| Sony VPCEH2N1E       | 1         | 0.47%   |
| Sony VPCEC3S1E       | 1         | 0.47%   |
| Sony VPCCB32FD       | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 32        | 15.02%  |
| 2020    | 17        | 7.98%   |
| 2015    | 17        | 7.98%   |
| 2011    | 17        | 7.98%   |
| 2016    | 16        | 7.51%   |
| 2019    | 15        | 7.04%   |
| 2013    | 14        | 6.57%   |
| 2010    | 14        | 6.57%   |
| 2022    | 13        | 6.1%    |
| 2012    | 11        | 5.16%   |
| 2018    | 10        | 4.69%   |
| 2017    | 8         | 3.76%   |
| 2014    | 7         | 3.29%   |
| 2008    | 5         | 2.35%   |
| 2007    | 5         | 2.35%   |
| 2009    | 4         | 1.88%   |
| 2006    | 3         | 1.41%   |
| 2023    | 2         | 0.94%   |
| 2005    | 2         | 0.94%   |
| Unknown | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 213       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 211       | 99.06%  |
| Enabled  | 2         | 0.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 212       | 99.53%  |
| Yes  | 1         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 69        | 32.39%  |
| 8.01-16.0   | 36        | 16.9%   |
| 16.01-24.0  | 33        | 15.49%  |
| 3.01-4.0    | 31        | 14.55%  |
| 1.01-2.0    | 16        | 7.51%   |
| 32.01-64.0  | 15        | 7.04%   |
| 2.01-3.0    | 6         | 2.82%   |
| 64.01-256.0 | 3         | 1.41%   |
| 24.01-32.0  | 2         | 0.94%   |
| 0.51-1.0    | 2         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 80        | 35.4%   |
| 2.01-3.0  | 60        | 26.55%  |
| 3.01-4.0  | 38        | 16.81%  |
| 4.01-8.0  | 24        | 10.62%  |
| 0.51-1.0  | 17        | 7.52%   |
| 8.01-16.0 | 5         | 2.21%   |
| 0.01-0.5  | 2         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 150       | 69.44%  |
| 2      | 49        | 22.69%  |
| 3      | 13        | 6.02%   |
| 0      | 3         | 1.39%   |
| 4      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 149       | 69.95%  |
| Yes       | 64        | 30.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 80.28%  |
| No        | 42        | 19.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 95.79%  |
| No        | 9         | 4.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 78.97%  |
| No        | 45        | 21.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 45        | 20.93%  |
| Germany      | 28        | 13.02%  |
| Italy        | 19        | 8.84%   |
| Canada       | 12        | 5.58%   |
| Russia       | 7         | 3.26%   |
| France       | 7         | 3.26%   |
| UK           | 6         | 2.79%   |
| Poland       | 6         | 2.79%   |
| India        | 6         | 2.79%   |
| Australia    | 5         | 2.33%   |
| Serbia       | 4         | 1.86%   |
| Romania      | 4         | 1.86%   |
| New Zealand  | 4         | 1.86%   |
| Netherlands  | 4         | 1.86%   |
| Brazil       | 4         | 1.86%   |
| Belgium      | 4         | 1.86%   |
| Switzerland  | 3         | 1.4%    |
| Spain        | 3         | 1.4%    |
| Indonesia    | 3         | 1.4%    |
| Turkey       | 2         | 0.93%   |
| South Africa | 2         | 0.93%   |
| Finland      | 2         | 0.93%   |
| Egypt        | 2         | 0.93%   |
| Czechia      | 2         | 0.93%   |
| Bulgaria     | 2         | 0.93%   |
| Bangladesh   | 2         | 0.93%   |
| Austria      | 2         | 0.93%   |
| Vietnam      | 1         | 0.47%   |
| Venezuela    | 1         | 0.47%   |
| Uzbekistan   | 1         | 0.47%   |
| Uruguay      | 1         | 0.47%   |
| Tunisia      | 1         | 0.47%   |
| Sweden       | 1         | 0.47%   |
| Slovakia     | 1         | 0.47%   |
| Peru         | 1         | 0.47%   |
| Norway       | 1         | 0.47%   |
| Nepal        | 1         | 0.47%   |
| Mexico       | 1         | 0.47%   |
| Malaysia     | 1         | 0.47%   |
| Ireland      | 1         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Milan          | 4         | 1.75%   |
| Warsaw         | 3         | 1.32%   |
| Rome           | 3         | 1.32%   |
| Moscow         | 3         | 1.32%   |
| Berlin         | 3         | 1.32%   |
| Belgrade       | 3         | 1.32%   |
| Walled Lake    | 2         | 0.88%   |
| Vienna         | 2         | 0.88%   |
| St Petersburg  | 2         | 0.88%   |
| Perth          | 2         | 0.88%   |
| Orange         | 2         | 0.88%   |
| Oakland        | 2         | 0.88%   |
| New York       | 2         | 0.88%   |
| Montreal       | 2         | 0.88%   |
| Hyderabad      | 2         | 0.88%   |
| Florence       | 2         | 0.88%   |
| Doesburg       | 2         | 0.88%   |
| Dhaka          | 2         | 0.88%   |
| Casale Litta   | 2         | 0.88%   |
| Canberra       | 2         | 0.88%   |
| Cambridge      | 2         | 0.88%   |
| Cairo          | 2         | 0.88%   |
| Amsterdam      | 2         | 0.88%   |
| Zurich         | 1         | 0.44%   |
| Zeven          | 1         | 0.44%   |
| Yekaterinburg  | 1         | 0.44%   |
| Workington     | 1         | 0.44%   |
| Wola           | 1         | 0.44%   |
| Wilmslow       | 1         | 0.44%   |
| Westland       | 1         | 0.44%   |
| Wermelskirchen | 1         | 0.44%   |
| Waycross       | 1         | 0.44%   |
| Vasco da Gama  | 1         | 0.44%   |
| Vancouver      | 1         | 0.44%   |
| Uelzen         | 1         | 0.44%   |
| Turku          | 1         | 0.44%   |
| Tunis          | 1         | 0.44%   |
| Tulsa          | 1         | 0.44%   |
| Tucson         | 1         | 0.44%   |
| Traunstein     | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 52     | 14.64%  |
| WDC                 | 34        | 34     | 12.14%  |
| Seagate             | 21        | 25     | 7.5%    |
| Unknown             | 19        | 22     | 6.79%   |
| Kingston            | 18        | 20     | 6.43%   |
| SK hynix            | 17        | 18     | 6.07%   |
| Toshiba             | 16        | 16     | 5.71%   |
| Crucial             | 15        | 32     | 5.36%   |
| Intel               | 9         | 11     | 3.21%   |
| SanDisk             | 8         | 9      | 2.86%   |
| Apple               | 7         | 10     | 2.5%    |
| HGST                | 6         | 6      | 2.14%   |
| Micron Technology   | 5         | 5      | 1.79%   |
| LITEON              | 5         | 5      | 1.79%   |
| Hitachi             | 5         | 6      | 1.79%   |
| SPCC                | 4         | 4      | 1.43%   |
| KIOXIA              | 4         | 6      | 1.43%   |
| Transcend           | 3         | 3      | 1.07%   |
| PNY                 | 3         | 3      | 1.07%   |
| Netac               | 3         | 3      | 1.07%   |
| Dogfish             | 3         | 3      | 1.07%   |
| Unknown             | 3         | 3      | 1.07%   |
| Team                | 2         | 2      | 0.71%   |
| Phison              | 2         | 3      | 0.71%   |
| Patriot             | 2         | 2      | 0.71%   |
| OCZ                 | 2         | 2      | 0.71%   |
| EYOTA               | 2         | 2      | 0.71%   |
| Corsair             | 2         | 2      | 0.71%   |
| China               | 2         | 2      | 0.71%   |
| UMIS                | 1         | 1      | 0.36%   |
| Teclast             | 1         | 1      | 0.36%   |
| SWORDBILL           | 1         | 2      | 0.36%   |
| Silicon Motion      | 1         | 1      | 0.36%   |
| SABRENT             | 1         | 1      | 0.36%   |
| RENICE              | 1         | 1      | 0.36%   |
| Indilinx            | 1         | 1      | 0.36%   |
| Hewlett-Packard     | 1         | 1      | 0.36%   |
| Gigabyte Technology | 1         | 1      | 0.36%   |
| GeIL                | 1         | 1      | 0.36%   |
| G-TECH              | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 5         | 1.74%   |
| Unknown SD32G  32GB                    | 3         | 1.04%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 1.04%   |
| Samsung SSD 980 PRO 1TB                | 3         | 1.04%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 1.04%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 1.04%   |
| HGST HTS721010A9E630 1TB               | 3         | 1.04%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 1.04%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 1.04%   |
| Unknown                                | 3         | 1.04%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 0.69%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 2         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.69%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 0.69%   |
| Unknown SDW32G  32GB                   | 2         | 0.69%   |
| Unknown DA4064  64GB                   | 2         | 0.69%   |
| Toshiba MQ01ABD075 752GB               | 2         | 0.69%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 2         | 0.69%   |
| SPCC Solid State Disk 1TB              | 2         | 0.69%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 0.69%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.69%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.69%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 0.69%   |
| SanDisk NVMe SSD Drive 512GB           | 2         | 0.69%   |
| Samsung SSD 860 250GB                  | 2         | 0.69%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.69%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 0.69%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 0.69%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.69%   |
| Kingston OM8PCP3512F-AI1 512GB         | 2         | 0.69%   |
| Intel SSDPEKNU512GZ 512GB              | 2         | 0.69%   |
| Hitachi HTS54503 320GB                 | 2         | 0.69%   |
| EYOTA SSD 120GB                        | 2         | 0.69%   |
| Dogfish SSD 128GB                      | 2         | 0.69%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 0.69%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 0.69%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 0.69%   |
| Apple SSD SM0128G 121GB                | 2         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 21     | 30.88%  |
| Seagate             | 21        | 25     | 30.88%  |
| Toshiba             | 10        | 10     | 14.71%  |
| HGST                | 6         | 6      | 8.82%   |
| Hitachi             | 5         | 6      | 7.35%   |
| Samsung Electronics | 2         | 2      | 2.94%   |
| Unknown             | 1         | 1      | 1.47%   |
| SABRENT             | 1         | 1      | 1.47%   |
| Fujitsu             | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 26     | 19.05%  |
| Crucial             | 12        | 28     | 11.43%  |
| Kingston            | 10        | 11     | 9.52%   |
| Apple               | 6         | 9      | 5.71%   |
| SanDisk             | 5         | 6      | 4.76%   |
| WDC                 | 4         | 4      | 3.81%   |
| SPCC                | 4         | 4      | 3.81%   |
| LITEON              | 4         | 4      | 3.81%   |
| Transcend           | 3         | 3      | 2.86%   |
| SK hynix            | 3         | 3      | 2.86%   |
| PNY                 | 3         | 3      | 2.86%   |
| Netac               | 3         | 3      | 2.86%   |
| Dogfish             | 3         | 3      | 2.86%   |
| Toshiba             | 2         | 2      | 1.9%    |
| OCZ                 | 2         | 2      | 1.9%    |
| Intel               | 2         | 2      | 1.9%    |
| EYOTA               | 2         | 2      | 1.9%    |
| China               | 2         | 2      | 1.9%    |
| Unknown             | 2         | 2      | 1.9%    |
| Teclast             | 1         | 1      | 0.95%   |
| Team                | 1         | 1      | 0.95%   |
| SWORDBILL           | 1         | 2      | 0.95%   |
| RENICE              | 1         | 1      | 0.95%   |
| Patriot             | 1         | 1      | 0.95%   |
| Micron Technology   | 1         | 1      | 0.95%   |
| Indilinx            | 1         | 1      | 0.95%   |
| Hewlett-Packard     | 1         | 1      | 0.95%   |
| Gigabyte Technology | 1         | 1      | 0.95%   |
| GeIL                | 1         | 1      | 0.95%   |
| CT500MX5            | 1         | 1      | 0.95%   |
| Corsair             | 1         | 1      | 0.95%   |
| Apacer              | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 90        | 133    | 35.02%  |
| NVMe    | 80        | 99     | 31.13%  |
| HDD     | 67        | 73     | 26.07%  |
| MMC     | 19        | 23     | 7.39%   |
| Unknown | 1         | 1      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 136       | 201    | 56.67%  |
| NVMe | 80        | 99     | 33.33%  |
| MMC  | 19        | 23     | 7.92%   |
| SAS  | 5         | 6      | 2.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 115       | 149    | 75.16%  |
| 0.51-1.0   | 35        | 54     | 22.88%  |
| 1.01-2.0   | 2         | 2      | 1.31%   |
| 3.01-4.0   | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 57        | 25.79%  |
| 101-250        | 57        | 25.79%  |
| 21-50          | 29        | 13.12%  |
| 501-1000       | 27        | 12.22%  |
| 51-100         | 23        | 10.41%  |
| 1-20           | 12        | 5.43%   |
| 1001-2000      | 10        | 4.52%   |
| More than 3000 | 4         | 1.81%   |
| 2001-3000      | 2         | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 107       | 46.93%  |
| 21-50          | 33        | 14.47%  |
| 51-100         | 30        | 13.16%  |
| 101-250        | 24        | 10.53%  |
| 251-500        | 15        | 6.58%   |
| 501-1000       | 10        | 4.39%   |
| 1001-2000      | 6         | 2.63%   |
| More than 3000 | 2         | 0.88%   |
| 2001-3000      | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                 | 2         | 2      | 6.45%   |
| WDC WD3200BPVT-80ZEST0 320GB                 | 1         | 1      | 3.23%   |
| WDC WD3200BPVT-24JJ5T0 320GB                 | 1         | 1      | 3.23%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 3.23%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 3.23%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 3.23%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 3.23%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 3.23%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 3.23%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 3.23%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 3.23%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 3.23%   |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 3      | 3.23%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 2      | 3.23%   |
| Samsung Electronics HM080HC 80GB             | 1         | 1      | 3.23%   |
| RENICE X2 64GB SSD                           | 1         | 1      | 3.23%   |
| OCZ VERTEX2 64GB SSD                         | 1         | 1      | 3.23%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 3.23%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 3.23%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 3.23%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 3.23%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 3.23%   |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 3.23%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.23%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 3.23%   |
| HGST HTS541075A9E680 752GB                   | 1         | 1      | 3.23%   |
| Crucial CT1000MX500SSD4 1TB                  | 1         | 6      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 22.58%  |
| WDC                 | 5         | 5      | 16.13%  |
| Toshiba             | 3         | 3      | 9.68%   |
| Samsung Electronics | 3         | 4      | 9.68%   |
| Hitachi             | 3         | 3      | 9.68%   |
| HGST                | 3         | 3      | 9.68%   |
| SK hynix            | 1         | 1      | 3.23%   |
| RENICE              | 1         | 1      | 3.23%   |
| OCZ                 | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| Intel               | 1         | 2      | 3.23%   |
| Indilinx            | 1         | 1      | 3.23%   |
| Crucial             | 1         | 6      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 33.33%  |
| WDC                 | 5         | 5      | 23.81%  |
| Hitachi             | 3         | 3      | 14.29%  |
| HGST                | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 23     | 67.74%  |
| SSD  | 8         | 14     | 25.81%  |
| NVMe | 2         | 3      | 6.45%   |

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
| Works    | 173       | 257    | 74.57%  |
| Malfunc  | 31        | 40     | 13.36%  |
| Detected | 28        | 32     | 12.07%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 141       | 56.4%   |
| Samsung Electronics          | 24        | 9.6%    |
| AMD                          | 21        | 8.4%    |
| SK hynix                     | 13        | 5.2%    |
| SanDisk                      | 11        | 4.4%    |
| Kingston Technology Company  | 8         | 3.2%    |
| KIOXIA                       | 6         | 2.4%    |
| Phison Electronics           | 4         | 1.6%    |
| Nvidia                       | 4         | 1.6%    |
| Micron Technology            | 4         | 1.6%    |
| Micron/Crucial Technology    | 3         | 1.2%    |
| Toshiba America Info Systems | 2         | 0.8%    |
| Silicon Motion               | 2         | 0.8%    |
| Union Memory (Shenzhen)      | 1         | 0.4%    |
| Silicon Image                | 1         | 0.4%    |
| Shenzhen Longsys Electronics | 1         | 0.4%    |
| MAXIO Technology (Hangzhou)  | 1         | 0.4%    |
| Marvell Technology Group     | 1         | 0.4%    |
| Lite-On Technology           | 1         | 0.4%    |
| ADATA Technology             | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 7.14%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 6.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 6.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 4.51%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 2.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.26%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.88%   |
| SK hynix BC511 NVMe SSD                                                        | 5         | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.88%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.13%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.13%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.13%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.13%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 1.13%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.75%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 0.75%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.75%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.75%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 2         | 0.75%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 146       | 57.71%  |
| NVMe | 79        | 31.23%  |
| IDE  | 16        | 6.32%   |
| RAID | 12        | 4.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 173       | 81.22%  |
| AMD    | 40        | 18.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 8         | 3.76%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 5         | 2.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 5         | 2.35%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 4         | 1.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 1.41%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 3         | 1.41%   |
| Intel 12th Gen Core i7-12700H           | 3         | 1.41%   |
| Intel 12th Gen Core i5-1235U            | 3         | 1.41%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.41%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.94%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 2         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.94%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.94%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 2         | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.94%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.94%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.94%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.94%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.94%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.94%   |
| Intel Core 2 CPU T5500 @ 1.66GHz        | 2         | 0.94%   |
| Intel Celeron N4120 CPU @ 1.10GHz       | 2         | 0.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 0.94%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 2         | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 2         | 0.94%   |
| Intel Celeron CPU 1007U @ 1.50GHz       | 2         | 0.94%   |
| Intel Atom CPU N570 @ 1.66GHz           | 2         | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.94%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2         | 0.94%   |
| AMD Ryzen 5 5625U with Radeon Graphics  | 2         | 0.94%   |
| AMD Ryzen 5 5600U with Radeon Graphics  | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 18.78%  |
| Intel Core i7           | 37        | 17.37%  |
| Other                   | 25        | 11.74%  |
| Intel Core i3           | 19        | 8.92%   |
| Intel Celeron           | 17        | 7.98%   |
| AMD Ryzen 5             | 13        | 6.1%    |
| AMD Ryzen 7             | 11        | 5.16%   |
| Intel Atom              | 10        | 4.69%   |
| Intel Core 2 Duo        | 8         | 3.76%   |
| Intel Pentium           | 4         | 1.88%   |
| AMD Ryzen 9             | 3         | 1.41%   |
| AMD Ryzen 3             | 3         | 1.41%   |
| Intel Pentium M         | 2         | 0.94%   |
| Intel Pentium Dual-Core | 2         | 0.94%   |
| Intel Genuine           | 2         | 0.94%   |
| Intel Core 2            | 2         | 0.94%   |
| Intel Xeon              | 1         | 0.47%   |
| Intel Pentium Silver    | 1         | 0.47%   |
| Intel Pentium Gold      | 1         | 0.47%   |
| Intel Pentium Dual      | 1         | 0.47%   |
| Intel Celeron Dual-Core | 1         | 0.47%   |
| AMD Turion 64 X2 Mobile | 1         | 0.47%   |
| AMD Sempron             | 1         | 0.47%   |
| AMD Phenom II           | 1         | 0.47%   |
| AMD E2                  | 1         | 0.47%   |
| AMD E1                  | 1         | 0.47%   |
| AMD E                   | 1         | 0.47%   |
| AMD A8                  | 1         | 0.47%   |
| AMD A6                  | 1         | 0.47%   |
| AMD A12                 | 1         | 0.47%   |
| AMD A10                 | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 102       | 47.89%  |
| 4      | 60        | 28.17%  |
| 6      | 18        | 8.45%   |
| 8      | 16        | 7.51%   |
| 1      | 7         | 3.29%   |
| 10     | 4         | 1.88%   |
| 14     | 3         | 1.41%   |
| 12     | 2         | 0.94%   |
| 5      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 213       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 149       | 69.95%  |
| 1      | 64        | 30.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 209       | 98.12%  |
| 32-bit         | 4         | 1.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 17        | 7.83%   |
| Unknown    | 16        | 7.37%   |
| 0x306a9    | 13        | 5.99%   |
| 0x806c1    | 11        | 5.07%   |
| 0x406e3    | 11        | 5.07%   |
| 0x0a50000c | 11        | 5.07%   |
| 0x30678    | 8         | 3.69%   |
| 0x1067a    | 8         | 3.69%   |
| 0x506e3    | 7         | 3.23%   |
| 0x806e9    | 6         | 2.76%   |
| 0x306c3    | 6         | 2.76%   |
| 0x20655    | 6         | 2.76%   |
| 0x08608103 | 6         | 2.76%   |
| 0xa0652    | 5         | 2.3%    |
| 0x906ea    | 5         | 2.3%    |
| 0x906a3    | 5         | 2.3%    |
| 0x706a8    | 5         | 2.3%    |
| 0x306d4    | 5         | 2.3%    |
| 0x906a4    | 4         | 1.84%   |
| 0x806ea    | 4         | 1.84%   |
| 0x906e9    | 3         | 1.38%   |
| 0x806ec    | 3         | 1.38%   |
| 0x6fd      | 3         | 1.38%   |
| 0x406c4    | 3         | 1.38%   |
| 0x40651    | 3         | 1.38%   |
| 0x08108102 | 3         | 1.38%   |
| 0x806d1    | 2         | 0.92%   |
| 0x706a1    | 2         | 0.92%   |
| 0x106ca    | 2         | 0.92%   |
| 0x08600104 | 2         | 0.92%   |
| 0x07030106 | 2         | 0.92%   |
| 0x0600611a | 2         | 0.92%   |
| 0xb06a3    | 1         | 0.46%   |
| 0xa0671    | 1         | 0.46%   |
| 0x906ed    | 1         | 0.46%   |
| 0x906c0    | 1         | 0.46%   |
| 0x806eb    | 1         | 0.46%   |
| 0x6fb      | 1         | 0.46%   |
| 0x6f6      | 1         | 0.46%   |
| 0x6e8      | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 11.27%  |
| Skylake          | 18        | 8.45%   |
| SandyBridge      | 18        | 8.45%   |
| Unknown          | 15        | 7.04%   |
| IvyBridge        | 14        | 6.57%   |
| Zen 3            | 13        | 6.1%    |
| TigerLake        | 12        | 5.63%   |
| Silvermont       | 11        | 5.16%   |
| Haswell          | 11        | 5.16%   |
| Penryn           | 9         | 4.23%   |
| Westmere         | 8         | 3.76%   |
| Goldmont plus    | 7         | 3.29%   |
| Core             | 7         | 3.29%   |
| Zen+             | 5         | 2.35%   |
| CometLake        | 5         | 2.35%   |
| Broadwell        | 5         | 2.35%   |
| Icelake          | 4         | 1.88%   |
| Alderlake Hybrid | 4         | 1.88%   |
| Zen 2            | 3         | 1.41%   |
| P6               | 3         | 1.41%   |
| Excavator        | 3         | 1.41%   |
| Bonnell          | 3         | 1.41%   |
| Puma             | 2         | 0.94%   |
| Goldmont         | 2         | 0.94%   |
| Tremont          | 1         | 0.47%   |
| Piledriver       | 1         | 0.47%   |
| Nehalem          | 1         | 0.47%   |
| K8 Hammer        | 1         | 0.47%   |
| K8 & K10 hybrid  | 1         | 0.47%   |
| K10              | 1         | 0.47%   |
| Bobcat           | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 160       | 60.84%  |
| Nvidia | 55        | 20.91%  |
| AMD    | 48        | 18.25%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 6.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 5.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 4%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 3.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.55%   |
| AMD Lucienne                                                                             | 7         | 2.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.18%   |
| Intel HD Graphics 530                                                                    | 6         | 2.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.82%   |
| Intel HD Graphics 620                                                                    | 5         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.45%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.45%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.45%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.09%   |
| AMD Barcelo                                                                              | 3         | 1.09%   |
| Nvidia TU117M                                                                            | 2         | 0.73%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.73%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.73%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.73%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.73%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.73%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.73%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.73%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 116       | 54.46%  |
| Intel + Nvidia | 35        | 16.43%  |
| 1 x AMD        | 30        | 14.08%  |
| 1 x Nvidia     | 13        | 6.1%    |
| Intel + AMD    | 8         | 3.76%   |
| AMD + Nvidia   | 6         | 2.82%   |
| 2 x AMD        | 4         | 1.88%   |
| 2 x Intel      | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 185       | 85.25%  |
| Proprietary | 20        | 9.22%   |
| Unknown     | 12        | 5.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 163       | 75.46%  |
| 0.01-0.5   | 28        | 12.96%  |
| 3.01-4.0   | 7         | 3.24%   |
| 0.51-1.0   | 7         | 3.24%   |
| 1.01-2.0   | 6         | 2.78%   |
| 7.01-8.0   | 3         | 1.39%   |
| 5.01-6.0   | 1         | 0.46%   |
| 2.01-3.0   | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 42        | 18.26%  |
| Chimei Innolux          | 41        | 17.83%  |
| BOE                     | 27        | 11.74%  |
| Samsung Electronics     | 21        | 9.13%   |
| LG Display              | 21        | 9.13%   |
| Chi Mei Optoelectronics | 9         | 3.91%   |
| Apple                   | 9         | 3.91%   |
| PANDA                   | 8         | 3.48%   |
| Hewlett-Packard         | 8         | 3.48%   |
| Lenovo                  | 5         | 2.17%   |
| Goldstar                | 5         | 2.17%   |
| Sharp                   | 4         | 1.74%   |
| Ancor Communications    | 4         | 1.74%   |
| Sony                    | 3         | 1.3%    |
| InfoVision              | 2         | 0.87%   |
| HannStar                | 2         | 0.87%   |
| Dell                    | 2         | 0.87%   |
| CPT                     | 2         | 0.87%   |
| TMX                     | 1         | 0.43%   |
| Sunplus                 | 1         | 0.43%   |
| STA                     | 1         | 0.43%   |
| Philips                 | 1         | 0.43%   |
| Panasonic               | 1         | 0.43%   |
| Packard Bell            | 1         | 0.43%   |
| ONN                     | 1         | 0.43%   |
| NEC Computers           | 1         | 0.43%   |
| LTM                     | 1         | 0.43%   |
| LG Philips              | 1         | 0.43%   |
| KDC                     | 1         | 0.43%   |
| HKC                     | 1         | 0.43%   |
| Eizo                    | 1         | 0.43%   |
| ASUSTek Computer        | 1         | 0.43%   |
| Acer                    | 1         | 0.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 2.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.3%    |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 3         | 1.3%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.87%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 0.87%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.87%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.87%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.87%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.87%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.87%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 2         | 0.87%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch                  | 1         | 0.43%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.43%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.43%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.43%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.43%   |
| Sony LCD Monitor MS_0025 1920x1080 380x210mm 17.1-inch                   | 1         | 0.43%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.43%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.43%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.43%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.43%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.43%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch        | 1         | 0.43%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.43%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch        | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 353x198mm 15.9-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 94        | 42.92%  |
| 1366x768 (WXGA)    | 62        | 28.31%  |
| 3840x2160 (4K)     | 12        | 5.48%   |
| 1280x800 (WXGA)    | 10        | 4.57%   |
| 1600x900 (HD+)     | 8         | 3.65%   |
| 1920x1200 (WUXGA)  | 4         | 1.83%   |
| 2880x1800          | 3         | 1.37%   |
| 2560x1600          | 3         | 1.37%   |
| 1440x900 (WXGA+)   | 3         | 1.37%   |
| 2560x1440 (QHD)    | 2         | 0.91%   |
| 2560x1080          | 2         | 0.91%   |
| 2256x1504          | 2         | 0.91%   |
| 2160x1440          | 2         | 0.91%   |
| 1280x1024 (SXGA)   | 2         | 0.91%   |
| 1024x768 (XGA)     | 2         | 0.91%   |
| 1024x600           | 2         | 0.91%   |
| 3840x2400          | 1         | 0.46%   |
| 3200x2000          | 1         | 0.46%   |
| 3200x1800 (QHD+)   | 1         | 0.46%   |
| 1680x1050 (WSXGA+) | 1         | 0.46%   |
| 1400x1050          | 1         | 0.46%   |
| 1360x768           | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 97        | 42.17%  |
| 13      | 29        | 12.61%  |
| 14      | 20        | 8.7%    |
| 17      | 18        | 7.83%   |
| 24      | 11        | 4.78%   |
| 11      | 11        | 4.78%   |
| 23      | 8         | 3.48%   |
| 12      | 5         | 2.17%   |
| 21      | 4         | 1.74%   |
| 16      | 4         | 1.74%   |
| 10      | 4         | 1.74%   |
| 19      | 3         | 1.3%    |
| Unknown | 3         | 1.3%    |
| 40      | 2         | 0.87%   |
| 34      | 2         | 0.87%   |
| 27      | 2         | 0.87%   |
| 84      | 1         | 0.43%   |
| 46      | 1         | 0.43%   |
| 43      | 1         | 0.43%   |
| 36      | 1         | 0.43%   |
| 32      | 1         | 0.43%   |
| 26      | 1         | 0.43%   |
| 25      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 132       | 57.64%  |
| 201-300     | 33        | 14.41%  |
| 351-400     | 25        | 10.92%  |
| 501-600     | 22        | 9.61%   |
| 401-500     | 5         | 2.18%   |
| 701-800     | 4         | 1.75%   |
| Unknown     | 3         | 1.31%   |
| 801-900     | 2         | 0.87%   |
| 1501-2000   | 1         | 0.44%   |
| 1001-1500   | 1         | 0.44%   |
| 901-1000    | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 170       | 81.34%  |
| 16/10   | 27        | 12.92%  |
| 3/2     | 4         | 1.91%   |
| 4/3     | 3         | 1.44%   |
| 5/4     | 2         | 0.96%   |
| 21/9    | 2         | 0.96%   |
| Unknown | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 97        | 42.17%  |
| 81-90          | 41        | 17.83%  |
| 201-250        | 19        | 8.26%   |
| 121-130        | 18        | 7.83%   |
| 51-60          | 11        | 4.78%   |
| 71-80          | 7         | 3.04%   |
| 61-70          | 5         | 2.17%   |
| 501-1000       | 5         | 2.17%   |
| 41-50          | 4         | 1.74%   |
| 251-300        | 4         | 1.74%   |
| 151-200        | 4         | 1.74%   |
| 351-500        | 3         | 1.3%    |
| 301-350        | 3         | 1.3%    |
| 111-120        | 3         | 1.3%    |
| Unknown        | 3         | 1.3%    |
| 91-100         | 2         | 0.87%   |
| More than 1000 | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 99        | 44%     |
| 101-120       | 53        | 23.56%  |
| 51-100        | 44        | 19.56%  |
| 161-240       | 16        | 7.11%   |
| More than 240 | 8         | 3.56%   |
| Unknown       | 3         | 1.33%   |
| 1-50          | 2         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 174       | 79.82%  |
| 2     | 29        | 13.3%   |
| 0     | 12        | 5.5%    |
| 3     | 3         | 1.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 110       | 31.7%   |
| Intel                             | 107       | 30.84%  |
| Qualcomm Atheros                  | 44        | 12.68%  |
| Broadcom                          | 22        | 6.34%   |
| MediaTek                          | 9         | 2.59%   |
| Broadcom Limited                  | 9         | 2.59%   |
| TP-Link                           | 6         | 1.73%   |
| Marvell Technology Group          | 5         | 1.44%   |
| Samsung Electronics               | 4         | 1.15%   |
| Motorola PCS                      | 4         | 1.15%   |
| ASIX Electronics                  | 4         | 1.15%   |
| Ralink                            | 3         | 0.86%   |
| OPPO Electronics                  | 3         | 0.86%   |
| Sierra Wireless                   | 2         | 0.58%   |
| Qualcomm Atheros Communications   | 2         | 0.58%   |
| Nvidia                            | 2         | 0.58%   |
| Sweex                             | 1         | 0.29%   |
| Ralink Technology                 | 1         | 0.29%   |
| Qualcomm Technologies             | 1         | 0.29%   |
| NetGear                           | 1         | 0.29%   |
| Lenovo                            | 1         | 0.29%   |
| Foxconn / Hon Hai                 | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |
| Attansic Technology               | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 67        | 16.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 14        | 3.41%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.93%   |
| Intel Wireless 8260                                                     | 10        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 1.95%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.46%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.46%   |
| Intel Wireless 3165                                                     | 6         | 1.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.22%   |
| Intel Wireless 7265                                                     | 5         | 1.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.22%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.98%   |
| Intel Wireless 7260                                                     | 4         | 0.98%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 0.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.73%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.73%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.73%   |
| OPPO OnePlus Nord                                                       | 3         | 0.73%   |
| Motorola PCS motorola edge 20 lite                                      | 3         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.73%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 104       | 46.85%  |
| Realtek Semiconductor           | 36        | 16.22%  |
| Qualcomm Atheros                | 33        | 14.86%  |
| Broadcom                        | 14        | 6.31%   |
| MediaTek                        | 9         | 4.05%   |
| Broadcom Limited                | 8         | 3.6%    |
| TP-Link                         | 5         | 2.25%   |
| Ralink                          | 3         | 1.35%   |
| Sierra Wireless                 | 2         | 0.9%    |
| Qualcomm Atheros Communications | 2         | 0.9%    |
| Sweex                           | 1         | 0.45%   |
| Ralink Technology               | 1         | 0.45%   |
| Qualcomm Technologies           | 1         | 0.45%   |
| NetGear                         | 1         | 0.45%   |
| D-Link                          | 1         | 0.45%   |
| ASUSTek Computer                | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 12        | 5.41%   |
| Intel Wireless 8260                                                     | 10        | 4.5%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 3.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.7%    |
| Intel Wireless 8265 / 8275                                              | 6         | 2.7%    |
| Intel Wireless 3165                                                     | 6         | 2.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.25%   |
| Intel Wireless 7265                                                     | 5         | 2.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.8%    |
| Intel Wireless 7260                                                     | 4         | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.35%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.35%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.35%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.35%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.9%    |
| Intel Wireless 3160                                                     | 2         | 0.9%    |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.9%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 95        | 52.2%   |
| Intel                    | 34        | 18.68%  |
| Qualcomm Atheros         | 16        | 8.79%   |
| Broadcom                 | 11        | 6.04%   |
| Marvell Technology Group | 5         | 2.75%   |
| Samsung Electronics      | 4         | 2.2%    |
| ASIX Electronics         | 4         | 2.2%    |
| OPPO Electronics         | 3         | 1.65%   |
| Motorola PCS             | 3         | 1.65%   |
| Nvidia                   | 2         | 1.1%    |
| TP-Link                  | 1         | 0.55%   |
| Lenovo                   | 1         | 0.55%   |
| Foxconn / Hon Hai        | 1         | 0.55%   |
| Broadcom Limited         | 1         | 0.55%   |
| Attansic Technology      | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 67        | 36.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 14        | 7.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 4.35%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 2.17%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.17%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.63%   |
| OPPO OnePlus Nord                                                              | 3         | 1.63%   |
| Motorola PCS motorola edge 20 lite                                             | 3         | 1.63%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.09%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.09%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.09%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.09%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.09%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.09%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.54%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.54%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.54%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 54.09%  |
| Ethernet | 170       | 44.85%  |
| Modem    | 3         | 0.79%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 75.7%   |
| Ethernet | 52        | 24.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 152       | 71.03%  |
| 1     | 53        | 24.77%  |
| 0     | 7         | 3.27%   |
| 3     | 2         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 160       | 74.07%  |
| Yes  | 56        | 25.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 44%     |
| Realtek Semiconductor           | 19        | 10.86%  |
| Qualcomm Atheros Communications | 15        | 8.57%   |
| Foxconn / Hon Hai               | 10        | 5.71%   |
| Lite-On Technology              | 9         | 5.14%   |
| Apple                           | 9         | 5.14%   |
| IMC Networks                    | 8         | 4.57%   |
| Broadcom                        | 8         | 4.57%   |
| Cambridge Silicon Radio         | 7         | 4%      |
| Hewlett-Packard                 | 4         | 2.29%   |
| Ralink                          | 2         | 1.14%   |
| Dell                            | 2         | 1.14%   |
| Realtek                         | 1         | 0.57%   |
| Ralink Technology               | 1         | 0.57%   |
| MediaTek                        | 1         | 0.57%   |
| ASUSTek Computer                | 1         | 0.57%   |
| Alps Electric                   | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 31        | 17.71%  |
| Realtek Bluetooth Radio                                                             | 17        | 9.71%   |
| Intel AX201 Bluetooth                                                               | 13        | 7.43%   |
| Intel AX200 Bluetooth                                                               | 12        | 6.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 5.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4%      |
| Intel Bluetooth Device                                                              | 5         | 2.86%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.86%   |
| IMC Networks Wireless_Device                                                        | 4         | 2.29%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 2.29%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.71%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.71%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.71%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.14%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.14%   |
| Lite-On Wireless_Device                                                             | 2         | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.14%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.14%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.14%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.14%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.14%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.57%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.57%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.57%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.57%   |
| MediaTek Wireless_Device                                                            | 1         | 0.57%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.57%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.57%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.57%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 162       | 62.07%  |
| Nvidia                  | 42        | 16.09%  |
| AMD                     | 40        | 15.33%  |
| Realtek Semiconductor   | 2         | 0.77%   |
| JMTek                   | 2         | 0.77%   |
| VIA Technologies        | 1         | 0.38%   |
| Texas Instruments       | 1         | 0.38%   |
| Plantronics             | 1         | 0.38%   |
| Logitech                | 1         | 0.38%   |
| Lenovo                  | 1         | 0.38%   |
| Guillemot               | 1         | 0.38%   |
| Generalplus Technology  | 1         | 0.38%   |
| Focusrite-Novation      | 1         | 0.38%   |
| FIFINE 683 Microphone   | 1         | 0.38%   |
| Conexant Systems        | 1         | 0.38%   |
| CMX Systems             | 1         | 0.38%   |
| C-Media Electronics     | 1         | 0.38%   |
| BEHRINGER International | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 30        | 9.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 22        | 7.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 20        | 6.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 5.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 4.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 3.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 9         | 2.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 2.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 2.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 2.25%   |
| Nvidia Audio device                                                        | 6         | 1.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.61%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.29%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.96%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 0.96%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.96%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.64%   |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.64%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 63        | 24.71%  |
| SK hynix                       | 56        | 21.96%  |
| Unknown                        | 29        | 11.37%  |
| Micron Technology              | 24        | 9.41%   |
| Kingston                       | 20        | 7.84%   |
| Crucial                        | 14        | 5.49%   |
| Elpida                         | 7         | 2.75%   |
| Unknown (ABCD)                 | 5         | 1.96%   |
| Corsair                        | 5         | 1.96%   |
| A-DATA Technology              | 5         | 1.96%   |
| Transcend                      | 3         | 1.18%   |
| Ramaxel Technology             | 3         | 1.18%   |
| Unknown                        | 3         | 1.18%   |
| Smart                          | 2         | 0.78%   |
| G.Skill                        | 2         | 0.78%   |
| Wilk                           | 1         | 0.39%   |
| Team                           | 1         | 0.39%   |
| PNY                            | 1         | 0.39%   |
| Patriot                        | 1         | 0.39%   |
| Nanya Technology               | 1         | 0.39%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.39%   |
| Lexar Co Limited               | 1         | 0.39%   |
| Innodisk                       | 1         | 0.39%   |
| Hewlett-Packard                | 1         | 0.39%   |
| Essencore                      | 1         | 0.39%   |
| CSX                            | 1         | 0.39%   |
| Avant                          | 1         | 0.39%   |
| ASint Technology               | 1         | 0.39%   |
| 48spaces                       | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 2.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 2.21%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 1.85%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 5         | 1.85%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 1.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.48%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.11%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.11%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 1.11%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.11%   |
| Unknown                                                          | 3         | 1.11%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.74%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.74%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.74%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.74%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.74%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 2         | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.74%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.74%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.74%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.74%   |
| Crucial RAM CT16G4SFRA32A.C16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 0.74%   |
| A-DATA RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2         | 0.74%   |
| Wilk RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 95        | 43.78%  |
| DDR3    | 85        | 39.17%  |
| DDR2    | 10        | 4.61%   |
| LPDDR4  | 9         | 4.15%   |
| DDR     | 5         | 2.3%    |
| SDRAM   | 4         | 1.84%   |
| LPDDR3  | 4         | 1.84%   |
| DDR5    | 2         | 0.92%   |
| LPDDR5  | 1         | 0.46%   |
| DRAM    | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 202       | 92.24%  |
| Row Of Chips | 12        | 5.48%   |
| DIMM         | 2         | 0.91%   |
| Unknown      | 2         | 0.91%   |
| Chip         | 1         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 90        | 37.66%  |
| 4096  | 73        | 30.54%  |
| 2048  | 34        | 14.23%  |
| 16384 | 27        | 11.3%   |
| 1024  | 10        | 4.18%   |
| 32768 | 4         | 1.67%   |
| 512   | 1         | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 50        | 21.46%  |
| 1600    | 50        | 21.46%  |
| 2667    | 29        | 12.45%  |
| 2400    | 17        | 7.3%    |
| 1333    | 16        | 6.87%   |
| 1334    | 15        | 6.44%   |
| Unknown | 11        | 4.72%   |
| 2133    | 9         | 3.86%   |
| 667     | 8         | 3.43%   |
| 1067    | 7         | 3%      |
| 4199    | 3         | 1.29%   |
| 533     | 3         | 1.29%   |
| 4800    | 2         | 0.86%   |
| 4267    | 2         | 0.86%   |
| 3266    | 2         | 0.86%   |
| 1867    | 2         | 0.86%   |
| 975     | 2         | 0.86%   |
| 8400    | 1         | 0.43%   |
| 5500    | 1         | 0.43%   |
| 4266    | 1         | 0.43%   |
| 2933    | 1         | 0.43%   |
| 166     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 25%     |
| HP LaserJet 1022         | 1         | 25%     |
| Canon LiDE 400           | 1         | 25%     |
| Brother DCP-L2540DW      | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 22.65%  |
| IMC Networks                           | 20        | 11.05%  |
| Realtek Semiconductor                  | 14        | 7.73%   |
| Microdia                               | 14        | 7.73%   |
| Quanta                                 | 12        | 6.63%   |
| Bison Electronics                      | 12        | 6.63%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 6.08%   |
| Luxvisions Innotech Limited            | 8         | 4.42%   |
| Suyin                                  | 6         | 3.31%   |
| Sunplus Innovation Technology          | 6         | 3.31%   |
| Apple                                  | 6         | 3.31%   |
| Lite-On Technology                     | 5         | 2.76%   |
| Ricoh                                  | 4         | 2.21%   |
| Alcor Micro                            | 4         | 2.21%   |
| Acer                                   | 4         | 2.21%   |
| Logitech                               | 3         | 1.66%   |
| Lenovo                                 | 3         | 1.66%   |
| Silicon Motion                         | 2         | 1.1%    |
| Z-Star Microelectronics                | 1         | 0.55%   |
| Y Media                                | 1         | 0.55%   |
| Primax Electronics                     | 1         | 0.55%   |
| Novatek Microelectronics               | 1         | 0.55%   |
| Hewlett-Packard                        | 1         | 0.55%   |
| Goodong Industry                       | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 11        | 6.08%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 6         | 3.31%   |
| Microdia Integrated_Webcam_HD                        | 5         | 2.76%   |
| Realtek Integrated_Webcam_HD                         | 4         | 2.21%   |
| Quanta HD User Facing                                | 4         | 2.21%   |
| IMC Networks Integrated Camera                       | 4         | 2.21%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.66%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.66%   |
| Chicony HD User Facing                               | 3         | 1.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 3         | 1.66%   |
| Bison Integrated Camera                              | 3         | 1.66%   |
| Bison BisonCam,NB Pro                                | 3         | 1.66%   |
| Suyin Acer CrystalEye Webcam                         | 2         | 1.1%    |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.1%    |
| Sunplus HD WebCam                                    | 2         | 1.1%    |
| Ricoh USB2.0 Camera                                  | 2         | 1.1%    |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 1.1%    |
| Realtek USB Camera                                   | 2         | 1.1%    |
| Microdia Webcam Vitade AF                            | 2         | 1.1%    |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 1.1%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 1.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 1.1%    |
| Lite-On HP HD Webcam                                 | 2         | 1.1%    |
| Lite-On HP HD Camera                                 | 2         | 1.1%    |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 1.1%    |
| IMC Networks XHC Camera                              | 2         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 1.1%    |
| IMC Networks USB2.0 UVC HD Webcam                    | 2         | 1.1%    |
| Chicony HD WebCam                                    | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam  | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 2         | 1.1%    |
| Bison HD Webcam                                      | 2         | 1.1%    |
| Apple Built-in iSight                                | 2         | 1.1%    |
| Alcor Micro USB 2.0 PC cam                           | 2         | 1.1%    |
| Z-Star Venus USB2.0 Camera                           | 1         | 0.55%   |
| Y Media USB Camera                                   | 1         | 0.55%   |
| Suyin Sony Visual Communication Camera               | 1         | 0.55%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.55%   |
| Suyin HP Webcam-101                                  | 1         | 0.55%   |
| Suyin HP Webcam                                      | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 12        | 30.77%  |
| Synaptics                          | 7         | 17.95%  |
| Shenzhen Goodix Technology         | 6         | 15.38%  |
| AuthenTec                          | 5         | 12.82%  |
| Elan Microelectronics              | 4         | 10.26%  |
| Upek                               | 3         | 7.69%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.56%   |
| Focal-systems.Corp                 | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 12.82%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 12.82%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 10.26%  |
| AuthenTec AES2810                                               | 3         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 2         | 5.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 5.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 5.13%   |
| Elan ELAN:Fingerprint                                           | 2         | 5.13%   |
| Elan ELAN:ARM-M4                                                | 2         | 5.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.56%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2.56%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.56%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 2.56%   |
| Synaptics UWP WBDI Device                                       | 1         | 2.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 2.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.56%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 2.56%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 2.56%   |
| Unknown                                                         | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 42.86%  |
| Alcor Micro           | 6         | 42.86%  |
| Advanced Card Systems | 2         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 6         | 42.86%  |
| Broadcom 5880                                  | 4         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 7.14%   |
| Broadcom 58200                                 | 1         | 7.14%   |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 7.14%   |
| Advanced Card Systems ACR122U                  | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 128       | 58.45%  |
| 1     | 65        | 29.68%  |
| 2     | 23        | 10.5%   |
| 3     | 3         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 48        | 42.86%  |
| Fingerprint reader       | 39        | 34.82%  |
| Chipcard                 | 12        | 10.71%  |
| Net/wireless             | 3         | 2.68%   |
| Multimedia controller    | 3         | 2.68%   |
| Camera                   | 3         | 2.68%   |
| Net/ethernet             | 1         | 0.89%   |
| Flash memory             | 1         | 0.89%   |
| Communication controller | 1         | 0.89%   |
| Bluetooth                | 1         | 0.89%   |

