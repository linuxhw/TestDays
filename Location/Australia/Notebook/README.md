Linux in Australia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

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

Total: 2569

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T410 2522PT3       | [db100cd948](https://linux-hardware.org/?probe=db100cd948) | Jan 02, 2024 |
| System76      | Oryx Pro                    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Valve         | Jupiter                     | [b16497fbfc](https://linux-hardware.org/?probe=b16497fbfc) | Jan 01, 2024 |
| Apple         | MacBookPro10,2              | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [7b1fe348e4](https://linux-hardware.org/?probe=7b1fe348e4) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [7130d1a699](https://linux-hardware.org/?probe=7130d1a699) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [d04c4d749f](https://linux-hardware.org/?probe=d04c4d749f) | Dec 31, 2023 |
| Metabox       | Alpha-X NH58HP              | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0060... | [485c94e992](https://linux-hardware.org/?probe=485c94e992) | Dec 29, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [5ef2e29839](https://linux-hardware.org/?probe=5ef2e29839) | Dec 27, 2023 |
| Apple         | MacBookAir9,1               | [22b65c12f2](https://linux-hardware.org/?probe=22b65c12f2) | Dec 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0W32L    | [55200b6aa5](https://linux-hardware.org/?probe=55200b6aa5) | Dec 26, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3fd8513ee7](https://linux-hardware.org/?probe=3fd8513ee7) | Dec 26, 2023 |
| Apple         | MacBookAir7,2               | [2a8ca288fb](https://linux-hardware.org/?probe=2a8ca288fb) | Dec 25, 2023 |
| Panasonic     | FZG1-4                      | [f6c98a5b67](https://linux-hardware.org/?probe=f6c98a5b67) | Dec 24, 2023 |
| HP            | ENVY 15                     | [2997ffe5cf](https://linux-hardware.org/?probe=2997ffe5cf) | Dec 22, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [fa4275395f](https://linux-hardware.org/?probe=fa4275395f) | Dec 22, 2023 |
| Dell          | Precision 5680              | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | [bc7fc2be74](https://linux-hardware.org/?probe=bc7fc2be74) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | [11f3b9c9d6](https://linux-hardware.org/?probe=11f3b9c9d6) | Dec 20, 2023 |
| Dell          | XPS 15 9560                 | [1bd33b2c6b](https://linux-hardware.org/?probe=1bd33b2c6b) | Dec 18, 2023 |
| Apple         | MacBookPro12,1              | [6db91b5eb2](https://linux-hardware.org/?probe=6db91b5eb2) | Dec 18, 2023 |
| ASUSTek       | X580VD                      | [8629995933](https://linux-hardware.org/?probe=8629995933) | Dec 17, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [eb941689a4](https://linux-hardware.org/?probe=eb941689a4) | Dec 17, 2023 |
| Apple         | MacBookPro10,1              | [adc736fc8d](https://linux-hardware.org/?probe=adc736fc8d) | Dec 16, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | [b5b534e106](https://linux-hardware.org/?probe=b5b534e106) | Dec 14, 2023 |
| HP            | Laptop 15-fc0xxx            | [e49be74129](https://linux-hardware.org/?probe=e49be74129) | Dec 13, 2023 |
| Acer          | Aspire R3-131T              | [5fc8de17bb](https://linux-hardware.org/?probe=5fc8de17bb) | Dec 13, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [625439b5a5](https://linux-hardware.org/?probe=625439b5a5) | Dec 13, 2023 |
| Lenovo        | G50-70 20351                | [d22fb3a791](https://linux-hardware.org/?probe=d22fb3a791) | Dec 11, 2023 |
| Valve         | Jupiter                     | [b78720dbf3](https://linux-hardware.org/?probe=b78720dbf3) | Dec 11, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2aef9deafb](https://linux-hardware.org/?probe=2aef9deafb) | Dec 10, 2023 |
| HP            | ProBook 6460b               | [99fa9c84ca](https://linux-hardware.org/?probe=99fa9c84ca) | Dec 10, 2023 |
| Dell          | Inspiron 1525               | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [afc78e9ba2](https://linux-hardware.org/?probe=afc78e9ba2) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a6b0055398](https://linux-hardware.org/?probe=a6b0055398) | Dec 08, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | [1229fd52f5](https://linux-hardware.org/?probe=1229fd52f5) | Dec 08, 2023 |
| Acer          | Extensa 4210                | [4f8a82394a](https://linux-hardware.org/?probe=4f8a82394a) | Dec 07, 2023 |
| HP            | 250 G7 Notebook PC          | [bed4fa69c4](https://linux-hardware.org/?probe=bed4fa69c4) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | [52cdd2c7b2](https://linux-hardware.org/?probe=52cdd2c7b2) | Dec 06, 2023 |
| Dell          | Latitude E6410              | [65b6e47cf8](https://linux-hardware.org/?probe=65b6e47cf8) | Dec 04, 2023 |
| Dell          | Latitude 5520               | [5b61695af2](https://linux-hardware.org/?probe=5b61695af2) | Dec 01, 2023 |
| Lenovo        | Z50-70 20354                | [44ad415f8f](https://linux-hardware.org/?probe=44ad415f8f) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | [c781f63b2a](https://linux-hardware.org/?probe=c781f63b2a) | Nov 30, 2023 |
| HP            | Laptop 15s-du0xxx           | [bf583ba008](https://linux-hardware.org/?probe=bf583ba008) | Nov 29, 2023 |
| Acer          | Nitro AN515-56              | [b2dd77b768](https://linux-hardware.org/?probe=b2dd77b768) | Nov 28, 2023 |
| MSI           | GF63 Thin 10SCXR            | [20e52e5c9b](https://linux-hardware.org/?probe=20e52e5c9b) | Nov 28, 2023 |
| MSI           | GF63 Thin 10SCXR            | [09dfe90de1](https://linux-hardware.org/?probe=09dfe90de1) | Nov 28, 2023 |
| Toshiba       | PORTEGE X30-E               | [9b85473f0f](https://linux-hardware.org/?probe=9b85473f0f) | Nov 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [aadba04a83](https://linux-hardware.org/?probe=aadba04a83) | Nov 27, 2023 |
| Dell          | Latitude 7490               | [4d59532412](https://linux-hardware.org/?probe=4d59532412) | Nov 27, 2023 |
| HP            | 245 G6 Notebook PC          | [1256303ece](https://linux-hardware.org/?probe=1256303ece) | Nov 26, 2023 |
| HP            | 245 G6 Notebook PC          | [0b00139036](https://linux-hardware.org/?probe=0b00139036) | Nov 26, 2023 |
| HP            | Pavilion dv6                | [e09777761c](https://linux-hardware.org/?probe=e09777761c) | Nov 26, 2023 |
| Dell          | Vostro 3401                 | [3496a45338](https://linux-hardware.org/?probe=3496a45338) | Nov 25, 2023 |
| Matsushita... | CF-30FCDALAM                | [94d60b91d5](https://linux-hardware.org/?probe=94d60b91d5) | Nov 25, 2023 |
| HP            | Laptop 15s-du0xxx           | [7e541895b2](https://linux-hardware.org/?probe=7e541895b2) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [145e6fbb42](https://linux-hardware.org/?probe=145e6fbb42) | Nov 24, 2023 |
| Valve         | Jupiter                     | [a4f7cad00f](https://linux-hardware.org/?probe=a4f7cad00f) | Nov 22, 2023 |
| Valve         | Jupiter                     | [bdb118e120](https://linux-hardware.org/?probe=bdb118e120) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | [6ca712a0bb](https://linux-hardware.org/?probe=6ca712a0bb) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | [09108a2bc4](https://linux-hardware.org/?probe=09108a2bc4) | Nov 22, 2023 |
| Acer          | Nitro AN515-56              | [9eb5267c48](https://linux-hardware.org/?probe=9eb5267c48) | Nov 22, 2023 |
| HP            | ProBook 430 G2              | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| Dell          | XPS 15 9560                 | [be841a1ee6](https://linux-hardware.org/?probe=be841a1ee6) | Nov 19, 2023 |
| Acer          | Nitro AN515-56              | [507f6c2a0d](https://linux-hardware.org/?probe=507f6c2a0d) | Nov 19, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [8ebb2df251](https://linux-hardware.org/?probe=8ebb2df251) | Nov 18, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [80f392bd0d](https://linux-hardware.org/?probe=80f392bd0d) | Nov 18, 2023 |
| Dell          | Inspiron M5010              | [77b9c09532](https://linux-hardware.org/?probe=77b9c09532) | Nov 18, 2023 |
| Toshiba       | PORTEGE Z20t-B              | [052540adc3](https://linux-hardware.org/?probe=052540adc3) | Nov 18, 2023 |
| Acer          | Nitro AN515-56              | [dc208dca03](https://linux-hardware.org/?probe=dc208dca03) | Nov 18, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [fb9543ab29](https://linux-hardware.org/?probe=fb9543ab29) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | [f61bc8d881](https://linux-hardware.org/?probe=f61bc8d881) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | [53dd735333](https://linux-hardware.org/?probe=53dd735333) | Nov 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [029e25867a](https://linux-hardware.org/?probe=029e25867a) | Nov 17, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3f4cd8d065](https://linux-hardware.org/?probe=3f4cd8d065) | Nov 14, 2023 |
| Acer          | Nitro AN515-56              | [3ad9fc243a](https://linux-hardware.org/?probe=3ad9fc243a) | Nov 14, 2023 |
| MSI           | Katana GF66 12UC            | [bd156c9515](https://linux-hardware.org/?probe=bd156c9515) | Nov 13, 2023 |
| ASUSTek       | X580VD                      | [d0809a2221](https://linux-hardware.org/?probe=d0809a2221) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [47d681f4e6](https://linux-hardware.org/?probe=47d681f4e6) | Nov 13, 2023 |
| COM1          | NBINF-X5-9G5                | [4e24a48715](https://linux-hardware.org/?probe=4e24a48715) | Nov 13, 2023 |
| Dell          | Inspiron 1525               | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| HP            | Pavilion g6                 | [1215d8475b](https://linux-hardware.org/?probe=1215d8475b) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Dell          | Precision 5520              | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Apple         | MacBookPro13,1              | [e5ae7e8a94](https://linux-hardware.org/?probe=e5ae7e8a94) | Nov 07, 2023 |
| Dell          | G7 7700                     | [0fc7811fdd](https://linux-hardware.org/?probe=0fc7811fdd) | Nov 07, 2023 |
| Acer          | TM8573T                     | [d78cdb2bdc](https://linux-hardware.org/?probe=d78cdb2bdc) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [94fdbbd7bd](https://linux-hardware.org/?probe=94fdbbd7bd) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [231b5b8ef8](https://linux-hardware.org/?probe=231b5b8ef8) | Nov 06, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [b88b3757af](https://linux-hardware.org/?probe=b88b3757af) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Sony          | SVE15137CGW                 | [5d2a4746af](https://linux-hardware.org/?probe=5d2a4746af) | Nov 04, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | [044aa1f9b5](https://linux-hardware.org/?probe=044aa1f9b5) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [75a224b797](https://linux-hardware.org/?probe=75a224b797) | Nov 02, 2023 |
| Valve         | Jupiter                     | [b5bd58d350](https://linux-hardware.org/?probe=b5bd58d350) | Oct 31, 2023 |
| MSI           | Creator 15 A11UE            | [e8b0c2a2b5](https://linux-hardware.org/?probe=e8b0c2a2b5) | Oct 31, 2023 |
| HP            | EliteBook 820 G3            | [e131dccf11](https://linux-hardware.org/?probe=e131dccf11) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Valve         | Jupiter                     | [e73e0881d6](https://linux-hardware.org/?probe=e73e0881d6) | Oct 30, 2023 |
| Dell          | Latitude 5530               | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Dell          | XPS 15 9510                 | [ab707308db](https://linux-hardware.org/?probe=ab707308db) | Oct 30, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [649b911963](https://linux-hardware.org/?probe=649b911963) | Oct 29, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [bc2ed6322b](https://linux-hardware.org/?probe=bc2ed6322b) | Oct 29, 2023 |
| Google        | Taniks                      | [c864f19e03](https://linux-hardware.org/?probe=c864f19e03) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| Dell          | Latitude 5430               | [af33081c9b](https://linux-hardware.org/?probe=af33081c9b) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [3bc6d6cfda](https://linux-hardware.org/?probe=3bc6d6cfda) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [755d25d933](https://linux-hardware.org/?probe=755d25d933) | Oct 26, 2023 |
| HP            | EliteBook Folio 9470m       | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d69762902a](https://linux-hardware.org/?probe=d69762902a) | Oct 25, 2023 |
| Lenovo        | V110-15IAP 80TG             | [455780b267](https://linux-hardware.org/?probe=455780b267) | Oct 25, 2023 |
| Acer          | Aspire V3-572               | [f873d7efd9](https://linux-hardware.org/?probe=f873d7efd9) | Oct 24, 2023 |
| ASUSTek       | X541UJ                      | [833d4435d4](https://linux-hardware.org/?probe=833d4435d4) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | [5fbee8e341](https://linux-hardware.org/?probe=5fbee8e341) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | [a95ab8b563](https://linux-hardware.org/?probe=a95ab8b563) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Acer          | Aspire V3-572               | [974d64f7a8](https://linux-hardware.org/?probe=974d64f7a8) | Oct 23, 2023 |
| Dell          | Latitude 5430               | [8d552380c4](https://linux-hardware.org/?probe=8d552380c4) | Oct 23, 2023 |
| Apple         | MacBookPro9,2               | [dac0aa7f70](https://linux-hardware.org/?probe=dac0aa7f70) | Oct 22, 2023 |
| Acer          | Nitro AN515-45              | [310d794691](https://linux-hardware.org/?probe=310d794691) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| HP            | ProBook 4340s               | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| HP            | Pavilion g6                 | [2fc9736b9e](https://linux-hardware.org/?probe=2fc9736b9e) | Oct 22, 2023 |
| HP            | Pavilion g6                 | [7514db3c84](https://linux-hardware.org/?probe=7514db3c84) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [09ad44bf2e](https://linux-hardware.org/?probe=09ad44bf2e) | Oct 19, 2023 |
| Dell          | XPS 13 9360                 | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| Apple         | MacBookPro11,1              | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [cf477f62d0](https://linux-hardware.org/?probe=cf477f62d0) | Oct 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Acer          | Aspire E1-531               | [4e585c2b99](https://linux-hardware.org/?probe=4e585c2b99) | Oct 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| HP            | Laptop 15s-du4xxx           | [8bec0ea3db](https://linux-hardware.org/?probe=8bec0ea3db) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [f35263745a](https://linux-hardware.org/?probe=f35263745a) | Oct 14, 2023 |
| HP            | Notebook                    | [221bc048b5](https://linux-hardware.org/?probe=221bc048b5) | Oct 13, 2023 |
| Apple         | MacBookPro11,4              | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [e6c5f903ce](https://linux-hardware.org/?probe=e6c5f903ce) | Oct 12, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| ASUSTek       | K42F                        | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Acer          | Aspire A114-33              | [53a1dce896](https://linux-hardware.org/?probe=53a1dce896) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Acer          | Nitro AN515-56              | [6a98464415](https://linux-hardware.org/?probe=6a98464415) | Oct 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d8d241531e](https://linux-hardware.org/?probe=d8d241531e) | Oct 07, 2023 |
| HP            | EliteBook 8460p             | [9b6cb6738d](https://linux-hardware.org/?probe=9b6cb6738d) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [226b534a32](https://linux-hardware.org/?probe=226b534a32) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [dfec5c18d5](https://linux-hardware.org/?probe=dfec5c18d5) | Oct 04, 2023 |
| MSI           | PR600                       | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| Dell          | Latitude E7440              | [3cb4fc2857](https://linux-hardware.org/?probe=3cb4fc2857) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Apple         | MacBookPro16,2              | [66ee93331d](https://linux-hardware.org/?probe=66ee93331d) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | [a7374560fe](https://linux-hardware.org/?probe=a7374560fe) | Oct 02, 2023 |
| Apple         | MacBookPro8,1               | [5488654867](https://linux-hardware.org/?probe=5488654867) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | [2f046de8e8](https://linux-hardware.org/?probe=2f046de8e8) | Oct 02, 2023 |
| Apple         | MacBookPro14,3              | [e26d66c131](https://linux-hardware.org/?probe=e26d66c131) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [21f405ccbe](https://linux-hardware.org/?probe=21f405ccbe) | Oct 01, 2023 |
| Toshiba       | Satellite P750              | [6edbfaa1b1](https://linux-hardware.org/?probe=6edbfaa1b1) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Metabox       | Prime-X X170KM              | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| Apple         | MacBookAir7,2               | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| ASUSTek       | X550CC                      | [001231c730](https://linux-hardware.org/?probe=001231c730) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| Apple         | MacBookPro15,2              | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| Apple         | MacBookAir5,2               | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | [c834abf6b2](https://linux-hardware.org/?probe=c834abf6b2) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | [bf8f7a55ae](https://linux-hardware.org/?probe=bf8f7a55ae) | Sep 24, 2023 |
| Acer          | Aspire R3-131T              | [a426f4a94e](https://linux-hardware.org/?probe=a426f4a94e) | Sep 24, 2023 |
| Dell          | Inspiron 14 5420            | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| COM1          | NBINF-X5-9G5                | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| HP            | EliteBook Folio 9470m       | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| Panasonic     | FZG1-4                      | [bb4677655e](https://linux-hardware.org/?probe=bb4677655e) | Sep 23, 2023 |
| Apple         | MacBookPro14,1              | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| Dell          | Precision 5680              | [55deb46665](https://linux-hardware.org/?probe=55deb46665) | Sep 21, 2023 |
| HP            | Pavilion dv7                | [a879a0a88f](https://linux-hardware.org/?probe=a879a0a88f) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | [c5e9108ee7](https://linux-hardware.org/?probe=c5e9108ee7) | Sep 20, 2023 |
| Dell          | Precision 5560              | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | [7a6c8c1d0a](https://linux-hardware.org/?probe=7a6c8c1d0a) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | [6f7974b0f0](https://linux-hardware.org/?probe=6f7974b0f0) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [eeeb11e211](https://linux-hardware.org/?probe=eeeb11e211) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [82e9cc2c9a](https://linux-hardware.org/?probe=82e9cc2c9a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Dell          | Latitude 7490               | [91a3ecf449](https://linux-hardware.org/?probe=91a3ecf449) | Sep 18, 2023 |
| Apple         | MacBookPro16,2              | [42bb973998](https://linux-hardware.org/?probe=42bb973998) | Sep 16, 2023 |
| Apple         | MacBookPro16,2              | [d5c797d43b](https://linux-hardware.org/?probe=d5c797d43b) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| COM1          | NBINF-X5-9G5                | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| Dell          | XPS L322X                   | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [fac3b5ba62](https://linux-hardware.org/?probe=fac3b5ba62) | Sep 08, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| Valve         | Jupiter                     | [d4ca58e970](https://linux-hardware.org/?probe=d4ca58e970) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| Dell          | Latitude 7280               | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 G1            | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Apple         | MacBookPro16,2              | [ae41ba8b62](https://linux-hardware.org/?probe=ae41ba8b62) | Sep 04, 2023 |
| Apple         | MacBookPro8,1               | [6cbaac077e](https://linux-hardware.org/?probe=6cbaac077e) | Sep 03, 2023 |
| Dell          | Latitude E6520              | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Dell          | G15 5520                    | [796ae7cf79](https://linux-hardware.org/?probe=796ae7cf79) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| ASUSTek       | K53SD                       | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| HP            | EliteBook Folio 1040 G1     | [1c496aba4a](https://linux-hardware.org/?probe=1c496aba4a) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| Dell          | Latitude 7340               | [d6d1df94f5](https://linux-hardware.org/?probe=d6d1df94f5) | Aug 31, 2023 |
| Apple         | MacBookPro8,1               | [a99931801d](https://linux-hardware.org/?probe=a99931801d) | Aug 31, 2023 |
| HP            | ENVY m6                     | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Dell          | Latitude 7390               | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Apple         | MacBookPro10,1              | [7741e9850b](https://linux-hardware.org/?probe=7741e9850b) | Aug 31, 2023 |
| Apple         | MacBookPro15,2              | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| Apple         | MacBookPro16,2              | [9782f69f43](https://linux-hardware.org/?probe=9782f69f43) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| Dell          | Latitude 3350               | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Apple         | MacBookPro8,1               | [43db739186](https://linux-hardware.org/?probe=43db739186) | Aug 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4c46f7ae80](https://linux-hardware.org/?probe=4c46f7ae80) | Aug 28, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [c96c172d03](https://linux-hardware.org/?probe=c96c172d03) | Aug 27, 2023 |
| HP            | Compaq 6710b (GE822PA#AB... | [134d0685ff](https://linux-hardware.org/?probe=134d0685ff) | Aug 26, 2023 |
| Acer          | Predator G9-793             | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| Dell          | XPS 17 9700                 | [93fec269da](https://linux-hardware.org/?probe=93fec269da) | Aug 25, 2023 |
| Dell          | Vostro 2520                 | [96018ae096](https://linux-hardware.org/?probe=96018ae096) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| HP            | Pavilion dv6                | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| Fujitsu       | S6420                       | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| Apple         | MacBookPro9,2               | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Kogan         | KAL14N360PA                 | [527a0d3cba](https://linux-hardware.org/?probe=527a0d3cba) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | [b7cecb1518](https://linux-hardware.org/?probe=b7cecb1518) | Aug 20, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [b42f885e14](https://linux-hardware.org/?probe=b42f885e14) | Aug 18, 2023 |
| Toshiba       | Satellite L550              | [4c331017e2](https://linux-hardware.org/?probe=4c331017e2) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Acer          | Aspire E5-571               | [8a924c30e6](https://linux-hardware.org/?probe=8a924c30e6) | Aug 17, 2023 |
| MSI           | GS60 6QE                    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| Google        | Phaser360                   | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Dell          | Precision 5520              | [0516c33229](https://linux-hardware.org/?probe=0516c33229) | Aug 16, 2023 |
| Dell          | Precision 5520              | [b9a35fa791](https://linux-hardware.org/?probe=b9a35fa791) | Aug 16, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| HP            | Notebook                    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Dell          | Latitude E7470              | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| HP            | ProBook 6450b               | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| Dell          | Latitude E6410              | [8ed9952374](https://linux-hardware.org/?probe=8ed9952374) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| Panasonic     | CF-19ADNAXDA                | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Dell          | G7 7790                     | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [359d84713c](https://linux-hardware.org/?probe=359d84713c) | Aug 11, 2023 |
| Acer          | TMP255-M                    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Leader        | SC404PRO                    | [6f24ee5e0c](https://linux-hardware.org/?probe=6f24ee5e0c) | Aug 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Dell          | Inspiron M5010              | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Vostro 5581                 | [b4495daa07](https://linux-hardware.org/?probe=b4495daa07) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| Dell          | XPS 13 9350                 | [fb1aaeae43](https://linux-hardware.org/?probe=fb1aaeae43) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Acer          | Aspire 5750G                | [3b589d53bc](https://linux-hardware.org/?probe=3b589d53bc) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Dell          | Latitude E6220              | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| Acer          | AS E5-523G                  | [b37e833d1e](https://linux-hardware.org/?probe=b37e833d1e) | Aug 05, 2023 |
| Acer          | Aspire 8943G                | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S84H0... | [d64e9809fa](https://linux-hardware.org/?probe=d64e9809fa) | Aug 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Dell          | Inspiron M5010              | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [bc18b4b7ed](https://linux-hardware.org/?probe=bc18b4b7ed) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [9b4b9b9d59](https://linux-hardware.org/?probe=9b4b9b9d59) | Jul 29, 2023 |
| Toshiba       | PORTEGE X30-E               | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| Acer          | TMP255-M                    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| Acer          | TMP255-M                    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| Dell          | Latitude 5410               | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| MSI           | Cyborg 15 A13VE             | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f525252834](https://linux-hardware.org/?probe=f525252834) | Jul 23, 2023 |
| MSI           | MEGA BOOK GX620             | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Apple         | MacBookPro14,3              | [e24c8a224e](https://linux-hardware.org/?probe=e24c8a224e) | Jul 21, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| HP            | 250 G5 Notebook PC          | [572537c287](https://linux-hardware.org/?probe=572537c287) | Jul 19, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [afdd53cd2f](https://linux-hardware.org/?probe=afdd53cd2f) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | [23c31a7c87](https://linux-hardware.org/?probe=23c31a7c87) | Jul 17, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Dell          | G5 5505                     | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| MSI           | Stealth 16Studio A13VG      | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| HP            | 250 G2                      | [7fd1832150](https://linux-hardware.org/?probe=7fd1832150) | Jul 11, 2023 |
| HP            | 250 G2                      | [738b04c947](https://linux-hardware.org/?probe=738b04c947) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX431FA             | [09edc8f932](https://linux-hardware.org/?probe=09edc8f932) | Jul 11, 2023 |
| Acer          | ConceptD CN315-71P          | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| Acer          | Aspire One 753              | [f47888ce55](https://linux-hardware.org/?probe=f47888ce55) | Jul 08, 2023 |
| Acer          | Aspire One 753              | [9f56cc566d](https://linux-hardware.org/?probe=9f56cc566d) | Jul 08, 2023 |
| Toshiba       | PORTEGE X30-E               | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| HP            | ProBook 4540s               | [cccf56865c](https://linux-hardware.org/?probe=cccf56865c) | Jul 06, 2023 |
| Acer          | TravelMate 8572T            | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| Lenovo        | ThinkPad P50 20EQS48H00     | [7f64164b64](https://linux-hardware.org/?probe=7f64164b64) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| Acer          | TravelMate 8572T            | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [04738ce824](https://linux-hardware.org/?probe=04738ce824) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [9cfe4d5036](https://linux-hardware.org/?probe=9cfe4d5036) | Jun 29, 2023 |
| Unknown       | Unknown                     | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| Acer          | Aspire xxxx                 | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [ba0db6c3e9](https://linux-hardware.org/?probe=ba0db6c3e9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| Apple         | MacBookPro11,1              | [06a581d65d](https://linux-hardware.org/?probe=06a581d65d) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | [a105b6264f](https://linux-hardware.org/?probe=a105b6264f) | Jun 25, 2023 |
| Toshiba       | Satellite L550              | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| ASUSTek       | X550LA                      | [225516996c](https://linux-hardware.org/?probe=225516996c) | Jun 25, 2023 |
| HP            | Laptop 15-db0xxx            | [79979ceac7](https://linux-hardware.org/?probe=79979ceac7) | Jun 25, 2023 |
| Acer          | Aspire A315-22              | [5e2e395efd](https://linux-hardware.org/?probe=5e2e395efd) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| ASUSTek       | X550LC                      | [30369c12e1](https://linux-hardware.org/?probe=30369c12e1) | Jun 24, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| HP            | Pavilion dv6                | [fa9045c36f](https://linux-hardware.org/?probe=fa9045c36f) | Jun 22, 2023 |
| ASUSTek       | X550LA                      | [9b58f1abd3](https://linux-hardware.org/?probe=9b58f1abd3) | Jun 20, 2023 |
| COM1          | NBINF-X5-9G5                | [fe2f1cfef6](https://linux-hardware.org/?probe=fe2f1cfef6) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| Dell          | Latitude E7440              | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Alienware     | M14xR2                      | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Acer          | Aspire A315-510P            | [d1be914db1](https://linux-hardware.org/?probe=d1be914db1) | Jun 17, 2023 |
| Dell          | XPS 13 9360                 | [852d16ee14](https://linux-hardware.org/?probe=852d16ee14) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [99cc4bf84b](https://linux-hardware.org/?probe=99cc4bf84b) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Dell          | Inspiron M5010              | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2eb89c4fd](https://linux-hardware.org/?probe=b2eb89c4fd) | Jun 13, 2023 |
| Acer          | Aspire A315-510P            | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| COM1          | NBINF-X5-9G5                | [755841cee1](https://linux-hardware.org/?probe=755841cee1) | Jun 11, 2023 |
| MSI           | GS60 6QE                    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| MSI           | GS60 6QE                    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Toshiba       | Satellite P870              | [559a48c91b](https://linux-hardware.org/?probe=559a48c91b) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Intel Clie... | LAPRC710                    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| Acer          | Predator G9-793             | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| Acer          | E5-551G-871W                | [8034a1ee0b](https://linux-hardware.org/?probe=8034a1ee0b) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| Toshiba       | Satellite C665              | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| Toshiba       | Satellite P870              | [2b57ca6d62](https://linux-hardware.org/?probe=2b57ca6d62) | May 29, 2023 |
| Valve         | Jupiter                     | [e6e97426e3](https://linux-hardware.org/?probe=e6e97426e3) | May 29, 2023 |
| HP            | EliteBook 840 G1            | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Apple         | MacBookPro10,2              | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| Acer          | Aspire A315-22              | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Dell          | Latitude 5430               | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Apple         | MacBookPro8,1               | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Dell          | Latitude 7280               | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | K56CA                       | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| MSI           | VR601                       | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| HP            | Pavilion 15                 | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| Dell          | Vostro V131                 | [e20ddd5bca](https://linux-hardware.org/?probe=e20ddd5bca) | May 18, 2023 |
| Dell          | Vostro V131                 | [7714e1784a](https://linux-hardware.org/?probe=7714e1784a) | May 18, 2023 |
| HP            | Notebook                    | [8d3bd6a690](https://linux-hardware.org/?probe=8d3bd6a690) | May 17, 2023 |
| Acer          | Predator G9-793             | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| Acer          | Aspire ES1-531              | [56cdac831f](https://linux-hardware.org/?probe=56cdac831f) | May 13, 2023 |
| Gigabyte      | P34V7                       | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| Unknown       | Unknown                     | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Acer          | Predator G9-793             | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Dell          | Inspiron N5010              | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Inspiron N5010              | [2a418b4e97](https://linux-hardware.org/?probe=2a418b4e97) | May 07, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| Toshiba       | PORTEGE Z30t-A              | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| System76      | Oryx Pro                    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Acer          | Predator G9-793             | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Intel Clie... | LAPRC510                    | [40c181b615](https://linux-hardware.org/?probe=40c181b615) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [925b5748b9](https://linux-hardware.org/?probe=925b5748b9) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| ASUSTek       | X501A1                      | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| ASUSTek       | X550CA                      | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Dell          | Inspiron 5548               | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Dell          | System XPS L702X            | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Valve         | Jupiter                     | [b5be7aa6ff](https://linux-hardware.org/?probe=b5be7aa6ff) | Apr 21, 2023 |
| Acer          | Predator G9-793             | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Acer          | Aspire 5733Z                | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| Dell          | Latitude 5420               | [03247dc98c](https://linux-hardware.org/?probe=03247dc98c) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Apple         | MacBookPro7,1               | [3470b35550](https://linux-hardware.org/?probe=3470b35550) | Apr 15, 2023 |
| Toshiba       | QOSMIO F750                 | [590801670a](https://linux-hardware.org/?probe=590801670a) | Apr 15, 2023 |
| Toshiba       | Satellite L850              | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Dell          | Latitude E6540              | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| Acer          | Aspire 5720Z                | [1ac7eb0d0c](https://linux-hardware.org/?probe=1ac7eb0d0c) | Apr 13, 2023 |
| Acer          | TM6495T                     | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| Dell          | Latitude E5470              | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| Apple         | MacBookAir7,2               | [5aad90904c](https://linux-hardware.org/?probe=5aad90904c) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion dv6                | [be695e2cd4](https://linux-hardware.org/?probe=be695e2cd4) | Apr 06, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| HP            | Notebook                    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HP            | EliteBook Folio 1040 G3     | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Dell          | XPS 15 9570                 | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| HP            | ProBook 450 G5              | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Dell          | Precision 5550              | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| HUAWEI        | NBD-WXX9                    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| Dell          | Latitude E6520              | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Dell          | G3 3590                     | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Acer          | Swift SFX14-41G             | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Laptop 15-db0xxx            | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Google        | Ultima                      | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| Valve         | Jupiter                     | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| HP            | Pavilion Notebook           | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Apple         | MacBookPro10,1              | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| HP            | Notebook                    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| Apple         | MacBookAir7,2               | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Dell          | Latitude 5430               | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a647dd6b9](https://linux-hardware.org/?probe=4a647dd6b9) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8b26ec07a6](https://linux-hardware.org/?probe=8b26ec07a6) | Feb 07, 2023 |
| Acer          | Aspire E3-111               | [a7c14e51ff](https://linux-hardware.org/?probe=a7c14e51ff) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a0fc4f78ea](https://linux-hardware.org/?probe=a0fc4f78ea) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [5a7ae4b151](https://linux-hardware.org/?probe=5a7ae4b151) | Feb 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| ASUSTek       | X550LC                      | [f22682c35f](https://linux-hardware.org/?probe=f22682c35f) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| Lenovo        | ThinkPad T420s 4173CTO      | [232ff7a382](https://linux-hardware.org/?probe=232ff7a382) | Feb 02, 2023 |
| HP            | 250 G5 Notebook PC          | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Alienware     | 15 R4                       | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| Dell          | XPS 15 7590                 | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| Acer          | Aspire R3-131T              | [268413b274](https://linux-hardware.org/?probe=268413b274) | Jan 15, 2023 |
| Valve         | Jupiter                     | [8830efc64d](https://linux-hardware.org/?probe=8830efc64d) | Jan 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [3837db6f8a](https://linux-hardware.org/?probe=3837db6f8a) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| Dell          | Inspiron 5770               | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| Dell          | XPS 17 9700                 | [09f6a754d6](https://linux-hardware.org/?probe=09f6a754d6) | Jan 12, 2023 |
| Acer          | Swift SF514-54T             | [98a18475e8](https://linux-hardware.org/?probe=98a18475e8) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Dell          | Inspiron 3543               | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| Dell          | XPS 13 9333                 | [f291c4d057](https://linux-hardware.org/?probe=f291c4d057) | Jan 09, 2023 |
| HP            | EliteBook Folio 9470m       | [1c4f7f2f2a](https://linux-hardware.org/?probe=1c4f7f2f2a) | Jan 09, 2023 |
| Dell          | Latitude 7280               | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Dell          | Latitude E7450              | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Lenovo        | ThinkPad W530 2463B87       | [5ac9828d4c](https://linux-hardware.org/?probe=5ac9828d4c) | Jan 08, 2023 |
| Acer          | Predator G9-793             | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [263354b92e](https://linux-hardware.org/?probe=263354b92e) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [99bf8fff2f](https://linux-hardware.org/?probe=99bf8fff2f) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [d9fa2355b0](https://linux-hardware.org/?probe=d9fa2355b0) | Jan 05, 2023 |
| HP            | Laptop 15s-fq1xxx           | [488e1f656c](https://linux-hardware.org/?probe=488e1f656c) | Jan 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [d0ac402ed9](https://linux-hardware.org/?probe=d0ac402ed9) | Jan 03, 2023 |
| HP            | Pavilion                    | [466e855af1](https://linux-hardware.org/?probe=466e855af1) | Jan 03, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| MSI           | GP62M 7REX                  | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| Dell          | XPS L521X                   | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Acer          | Aspire A515-45              | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | G15 5511                    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| AMI           | Intel                       | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Acer          | Aspire R3-131T              | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| MSI           | GP62M 7REX                  | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| ASUSTek       | X550CC                      | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| ASUSTek       | K53E                        | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| MSI           | Katana GF76 12UC            | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| ASUSTek       | U50Vg                       | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Apple         | MacBookAir7,2               | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Dell          | Inspiron 15 7510            | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Acer          | TMP645-M                    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | Precision 7760              | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Dell          | Latitude E7470              | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| HP            | Pavilion dv6500             | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| HP            | EliteBook 830 G6            | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| Dell          | XPS 13 7390                 | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASUSTek       | X756UAK                     | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Dell          | XPS 9320                    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Acer          | ConceptD CN315-71P          | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire 5742G                | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Dell          | Latitude E7250              | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3400               | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Apple         | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Google        | Peppy                       | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Dell          | Latitude 5430               | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| HP            | EliteBook 850 G1            | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| Dell          | Latitude 5430               | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Dell          | G3 3500                     | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Dell          | Vostro 1500                 | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| HP            | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Acer          | Aspire R3-131T              | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Acer          | Nitro AN515-55              | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 201       | 11.39%  |
| Ubuntu 22.04       | 85        | 4.82%   |
| Ubuntu 18.04       | 82        | 4.65%   |
| Pop!_OS 22.04      | 61        | 3.46%   |
| Debian 11          | 37        | 2.1%    |
| Arch Rolling       | 37        | 2.1%    |
| Zorin 16           | 32        | 1.81%   |
| KDE neon 20.04     | 31        | 1.76%   |
| Linux Mint 20.2    | 30        | 1.7%    |
| Fedora 36          | 29        | 1.64%   |
| Linux Mint 20.3    | 28        | 1.59%   |
| Pop!_OS 21.04      | 27        | 1.53%   |
| Fedora 38          | 27        | 1.53%   |
| Pop!_OS 20.04      | 25        | 1.42%   |
| OpenMandriva 4.3   | 25        | 1.42%   |
| Fedora 37          | 25        | 1.42%   |
| Manjaro            | 24        | 1.36%   |
| Arch               | 24        | 1.36%   |
| Linux Mint 20      | 22        | 1.25%   |
| ArcoLinux Rolling  | 22        | 1.25%   |
| Ubuntu 20.10       | 21        | 1.19%   |
| OpenMandriva 4.2   | 20        | 1.13%   |
| Linux Mint 21.1    | 20        | 1.13%   |
| Linux Mint 20.1    | 20        | 1.13%   |
| Pop!_OS 20.10      | 19        | 1.08%   |
| Ubuntu 21.10       | 18        | 1.02%   |
| Ubuntu 19.04       | 18        | 1.02%   |
| Ubuntu 23.04       | 17        | 0.96%   |
| Ubuntu 19.10       | 17        | 0.96%   |
| Linux Mint 21.2    | 17        | 0.96%   |
| Debian 12          | 17        | 0.96%   |
| Zorin 15           | 16        | 0.91%   |
| Fedora 33          | 16        | 0.91%   |
| Fedora 35          | 15        | 0.85%   |
| Ubuntu 21.04       | 14        | 0.79%   |
| KDE neon 22.04     | 14        | 0.79%   |
| Xubuntu 18.04      | 13        | 0.74%   |
| Ubuntu 22.10       | 13        | 0.74%   |
| OpenMandriva 23.03 | 13        | 0.74%   |
| Linux Mint 21      | 13        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 469       | 28.42%  |
| Linux Mint    | 158       | 9.58%   |
| Pop!_OS       | 134       | 8.12%   |
| Fedora        | 130       | 7.88%   |
| OpenMandriva  | 89        | 5.39%   |
| Debian        | 72        | 4.36%   |
| Arch          | 59        | 3.58%   |
| Zorin         | 55        | 3.33%   |
| Manjaro       | 52        | 3.15%   |
| KDE neon      | 48        | 2.91%   |
| Kubuntu       | 37        | 2.24%   |
| Xubuntu       | 36        | 2.18%   |
| Kali          | 30        | 1.82%   |
| Elementary    | 25        | 1.52%   |
| ArcoLinux     | 22        | 1.33%   |
| Gentoo        | 17        | 1.03%   |
| openSUSE      | 15        | 0.91%   |
| Clear Linux   | 14        | 0.85%   |
| SteamOS       | 13        | 0.79%   |
| Lubuntu       | 12        | 0.73%   |
| Endless       | 12        | 0.73%   |
| Ubuntu Unity  | 11        | 0.67%   |
| EndeavourOS   | 11        | 0.67%   |
| ROSA          | 10        | 0.61%   |
| MX            | 10        | 0.61%   |
| LMDE          | 10        | 0.61%   |
| Ubuntu MATE   | 9         | 0.55%   |
| Parrot        | 8         | 0.48%   |
| Ubuntu Budgie | 6         | 0.36%   |
| LinuxFX       | 6         | 0.36%   |
| BlackPanther  | 6         | 0.36%   |
| Xero          | 4         | 0.24%   |
| Reborn OS     | 4         | 0.24%   |
| Nobara        | 4         | 0.24%   |
| TUXEDO OS     | 3         | 0.18%   |
| Solus         | 3         | 0.18%   |
| Oracle Linux  | 3         | 0.18%   |
| Void Linux    | 2         | 0.12%   |
| RHEL          | 2         | 0.12%   |
| PureOS        | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 33        | 1.67%   |
| 5.16.7-desktop-1omv4003  | 24        | 1.22%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.01%   |
| 5.4.0-58-generic         | 18        | 0.91%   |
| 5.15.0-56-generic        | 16        | 0.81%   |
| 5.4.0-26-generic         | 15        | 0.76%   |
| 5.4.0-40-generic         | 14        | 0.71%   |
| 5.11.0-7620-generic      | 14        | 0.71%   |
| 6.2.6-desktop-1omv2390   | 13        | 0.66%   |
| 6.2.6-76060206-generic   | 13        | 0.66%   |
| 5.4.0-29-generic         | 13        | 0.66%   |
| 5.4.0-48-generic         | 12        | 0.61%   |
| 5.17.5-76051705-generic  | 12        | 0.61%   |
| 5.15.0-58-generic        | 12        | 0.61%   |
| 5.11.0-38-generic        | 12        | 0.61%   |
| 6.2.0-20-generic         | 11        | 0.56%   |
| 5.11.0-37-generic        | 11        | 0.56%   |
| 5.11.0-27-generic        | 11        | 0.56%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.51%   |
| 5.4.0-52-generic         | 10        | 0.51%   |
| 6.2.0-26-generic         | 9         | 0.46%   |
| 5.8.0-63-generic         | 9         | 0.46%   |
| 5.4.0-81-generic         | 9         | 0.46%   |
| 5.4.0-74-generic         | 9         | 0.46%   |
| 5.3.0-40-generic         | 9         | 0.46%   |
| 5.8.0-7630-generic       | 8         | 0.41%   |
| 5.8.0-59-generic         | 8         | 0.41%   |
| 5.4.0-7634-generic       | 8         | 0.41%   |
| 5.4.0-65-generic         | 8         | 0.41%   |
| 5.4.0-54-generic         | 8         | 0.41%   |
| 5.3.0-28-generic         | 8         | 0.41%   |
| 5.19.0-46-generic        | 8         | 0.41%   |
| 5.19.0-38-generic        | 8         | 0.41%   |
| 5.15.0-52-generic        | 8         | 0.41%   |
| 5.15.0-46-generic        | 8         | 0.41%   |
| 5.13.0-7620-generic      | 8         | 0.41%   |
| 5.13.0-40-generic        | 8         | 0.41%   |
| 5.11.0-40-generic        | 8         | 0.41%   |
| 5.0.0-13-generic         | 8         | 0.41%   |
| 6.2.0-35-generic         | 7         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 271       | 14.76%  |
| 5.15.0  | 139       | 7.57%   |
| 5.11.0  | 101       | 5.5%    |
| 5.13.0  | 85        | 4.63%   |
| 5.8.0   | 84        | 4.58%   |
| 4.15.0  | 70        | 3.81%   |
| 5.19.0  | 57        | 3.1%    |
| 6.2.0   | 56        | 3.05%   |
| 5.3.0   | 52        | 2.83%   |
| 5.10.0  | 51        | 2.78%   |
| 5.0.0   | 41        | 2.23%   |
| 4.18.0  | 31        | 1.69%   |
| 6.2.6   | 26        | 1.42%   |
| 5.16.7  | 25        | 1.36%   |
| 6.1.0   | 23        | 1.25%   |
| 5.10.14 | 20        | 1.09%   |
| 5.17.5  | 18        | 0.98%   |
| 6.5.0   | 17        | 0.93%   |
| 6.1.1   | 14        | 0.76%   |
| 6.0.0   | 14        | 0.76%   |
| 6.0.12  | 11        | 0.6%    |
| 4.19.0  | 11        | 0.6%    |
| 5.18.0  | 10        | 0.54%   |
| 6.5.6   | 9         | 0.49%   |
| 6.4.11  | 8         | 0.44%   |
| 5.18.10 | 8         | 0.44%   |
| 6.5.5   | 7         | 0.38%   |
| 6.4.6   | 7         | 0.38%   |
| 6.0.9   | 7         | 0.38%   |
| 6.0.7   | 7         | 0.38%   |
| 5.14.0  | 7         | 0.38%   |
| 6.4.10  | 6         | 0.33%   |
| 6.4.0   | 6         | 0.33%   |
| 5.18.12 | 6         | 0.33%   |
| 5.17.15 | 6         | 0.33%   |
| 6.6.6   | 5         | 0.27%   |
| 6.2.9   | 5         | 0.27%   |
| 6.1.11  | 5         | 0.27%   |
| 5.8.16  | 5         | 0.27%   |
| 5.16.11 | 5         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 295       | 16.39%  |
| 5.15    | 178       | 9.89%   |
| 5.11    | 115       | 6.39%   |
| 6.2     | 101       | 5.61%   |
| 5.8     | 101       | 5.61%   |
| 5.13    | 99        | 5.5%    |
| 5.10    | 95        | 5.28%   |
| 6.1     | 74        | 4.11%   |
| 5.19    | 73        | 4.06%   |
| 4.15    | 70        | 3.89%   |
| 5.16    | 58        | 3.22%   |
| 5.3     | 56        | 3.11%   |
| 6.0     | 54        | 3%      |
| 6.5     | 48        | 2.67%   |
| 5.0     | 45        | 2.5%    |
| 6.4     | 43        | 2.39%   |
| 5.17    | 39        | 2.17%   |
| 5.18    | 37        | 2.06%   |
| 4.18    | 36        | 2%      |
| 6.3     | 24        | 1.33%   |
| 5.6     | 19        | 1.06%   |
| 5.14    | 18        | 1%      |
| 5.9     | 17        | 0.94%   |
| 6.6     | 16        | 0.89%   |
| 5.12    | 15        | 0.83%   |
| 4.19    | 14        | 0.78%   |
| 5.5     | 12        | 0.67%   |
| 5.7     | 11        | 0.61%   |
| 4.9     | 11        | 0.61%   |
| 5.2     | 5         | 0.28%   |
| 4.4     | 5         | 0.28%   |
| 4.1     | 3         | 0.17%   |
| 5.1     | 2         | 0.11%   |
| 4.8     | 2         | 0.11%   |
| 4.20    | 2         | 0.11%   |
| 3.16    | 2         | 0.11%   |
| 3.10    | 2         | 0.11%   |
| 4.14    | 1         | 0.06%   |
| 4.13    | 1         | 0.06%   |
| 4.11    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1510      | 97.55%  |
| i686    | 33        | 2.13%   |
| aarch64 | 3         | 0.19%   |
| i586    | 2         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 743       | 44.92%  |
| KDE5            | 284       | 17.17%  |
| Unknown         | 150       | 9.07%   |
| X-Cinnamon      | 137       | 8.28%   |
| XFCE            | 127       | 7.68%   |
| MATE            | 37        | 2.24%   |
| KDE             | 32        | 1.93%   |
| Cinnamon        | 26        | 1.57%   |
| Pantheon        | 23        | 1.39%   |
| i3              | 15        | 0.91%   |
| Unity           | 13        | 0.79%   |
| LXQt            | 11        | 0.67%   |
| LXDE            | 10        | 0.6%    |
| Budgie          | 9         | 0.54%   |
| KDE4            | 8         | 0.48%   |
| Deepin          | 6         | 0.36%   |
| BunsenLabs      | 3         | 0.18%   |
| awesome         | 3         | 0.18%   |
| Openbox         | 2         | 0.12%   |
| Hyprland        | 2         | 0.12%   |
| GNOME Flashback | 2         | 0.12%   |
| GNOME Classic   | 2         | 0.12%   |
| sway            | 1         | 0.06%   |
| qtile-default   | 1         | 0.06%   |
| qtile           | 1         | 0.06%   |
| LeftWM          | 1         | 0.06%   |
| icewm           | 1         | 0.06%   |
| herbstluftwm    | 1         | 0.06%   |
| dwm             | 1         | 0.06%   |
| dusk            | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1198      | 74.5%   |
| Wayland | 293       | 18.22%  |
| Unknown | 84        | 5.22%   |
| Tty     | 32        | 1.99%   |
| Web     | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 818       | 50.28%  |
| SDDM    | 227       | 13.95%  |
| GDM     | 184       | 11.31%  |
| GDM3    | 175       | 10.76%  |
| LightDM | 170       | 10.45%  |
| TDM     | 39        | 2.4%    |
| KDM     | 8         | 0.49%   |
| SLiM    | 2         | 0.12%   |
| LXDM    | 2         | 0.12%   |
| XDM     | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_AU        | 1134      | 70.3%   |
| en_US        | 254       | 15.75%  |
| Unknown      | 135       | 8.37%   |
| C            | 42        | 2.6%    |
| en_GB        | 31        | 1.92%   |
| C.UTF8       | 4         | 0.25%   |
| zh_CN        | 1         | 0.06%   |
| ru_RU        | 1         | 0.06%   |
| POSIX        | 1         | 0.06%   |
| it_IT        | 1         | 0.06%   |
| fr_FR        | 1         | 0.06%   |
| es_ES        | 1         | 0.06%   |
| en_ZA        | 1         | 0.06%   |
| en_IN        | 1         | 0.06%   |
| en_GB.UTF-12 | 1         | 0.06%   |
| en_DK        | 1         | 0.06%   |
| en_CA        | 1         | 0.06%   |
| en_AU.UFT-8  | 1         | 0.06%   |
| de_DE        | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 813       | 51.07%  |
| BIOS | 779       | 48.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1188      | 74.25%  |
| Btrfs   | 179       | 11.19%  |
| Overlay | 99        | 6.19%   |
| Tmpfs   | 43        | 2.69%   |
| Unknown | 39        | 2.44%   |
| Xfs     | 21        | 1.31%   |
| Zfs     | 19        | 1.19%   |
| Ext2    | 5         | 0.31%   |
| XXXXXXX | 3         | 0.19%   |
| Ext3    | 3         | 0.19%   |
| F2fs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 860       | 53.99%  |
| GPT     | 590       | 37.04%  |
| MBR     | 143       | 8.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1402      | 89.02%  |
| Yes       | 173       | 10.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1227      | 77.66%  |
| Yes       | 353       | 22.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 275       | 17.79%  |
| Dell                           | 264       | 17.08%  |
| Lenovo                         | 256       | 16.56%  |
| ASUSTek Computer               | 149       | 9.64%   |
| Acer                           | 140       | 9.06%   |
| Apple                          | 120       | 7.76%   |
| Toshiba                        | 108       | 6.99%   |
| MSI                            | 40        | 2.59%   |
| Samsung Electronics            | 16        | 1.03%   |
| Alienware                      | 16        | 1.03%   |
| Sony                           | 11        | 0.71%   |
| Valve                          | 10        | 0.65%   |
| Notebook                       | 10        | 0.65%   |
| Gigabyte Technology            | 10        | 0.65%   |
| Panasonic                      | 9         | 0.58%   |
| Timi                           | 8         | 0.52%   |
| Metabox                        | 8         | 0.52%   |
| IT Channel Pty                 | 7         | 0.45%   |
| HUAWEI                         | 7         | 0.45%   |
| Framework                      | 7         | 0.45%   |
| Unknown                        | 7         | 0.45%   |
| Razer                          | 6         | 0.39%   |
| Google                         | 6         | 0.39%   |
| System76                       | 5         | 0.32%   |
| Intel Client Systems           | 5         | 0.32%   |
| AMI                            | 4         | 0.26%   |
| Medion                         | 3         | 0.19%   |
| LG Electronics                 | 3         | 0.19%   |
| Kogan                          | 3         | 0.19%   |
| Fujitsu                        | 3         | 0.19%   |
| Purism                         | 2         | 0.13%   |
| Pine Microsystems              | 2         | 0.13%   |
| Matsushita Electric Industrial | 2         | 0.13%   |
| LEADER                         | 2         | 0.13%   |
| IBM                            | 2         | 0.13%   |
| COM1                           | 2         | 0.13%   |
| Star Labs                      | 1         | 0.06%   |
| Pendo Industries               | 1         | 0.06%   |
| ONE-NETBOOK TECHNOLOGY         | 1         | 0.06%   |
| One Education                  | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion dv6                        | 18        | 1.16%   |
| HP Notebook                            | 14        | 0.91%   |
| HP Pavilion g6                         | 13        | 0.84%   |
| Apple MacBookAir7,2                    | 11        | 0.71%   |
| Valve Jupiter                          | 10        | 0.65%   |
| Apple MacBookPro9,2                    | 10        | 0.65%   |
| Apple MacBookPro8,1                    | 10        | 0.65%   |
| Apple MacBookPro10,1                   | 10        | 0.65%   |
| Unknown                                | 10        | 0.65%   |
| HP Pavilion 15                         | 9         | 0.58%   |
| Dell XPS 15 9570                       | 7         | 0.45%   |
| Dell XPS 15 9560                       | 7         | 0.45%   |
| Dell XPS 13 9360                       | 7         | 0.45%   |
| Toshiba Satellite L850                 | 6         | 0.39%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 6         | 0.39%   |
| Apple MacBookPro11,1                   | 6         | 0.39%   |
| Acer ConceptD CN315-71P                | 6         | 0.39%   |
| Toshiba Satellite P750                 | 5         | 0.32%   |
| Dell Latitude E7450                    | 5         | 0.32%   |
| Apple MacBookPro10,2                   | 5         | 0.32%   |
| Apple MacBookAir6,2                    | 5         | 0.32%   |
| Acer Aspire A315-22                    | 5         | 0.32%   |
| Acer Aspire 5750G                      | 5         | 0.32%   |
| Toshiba Satellite L750                 | 4         | 0.26%   |
| Toshiba Satellite L500                 | 4         | 0.26%   |
| Toshiba Satellite L50-A                | 4         | 0.26%   |
| Toshiba Satellite C660                 | 4         | 0.26%   |
| Lenovo IdeaPad 1 14IGL05 81VU          | 4         | 0.26%   |
| Lenovo G50-45 80E3                     | 4         | 0.26%   |
| HP ProBook 430 G2                      | 4         | 0.26%   |
| HP Pavilion Notebook                   | 4         | 0.26%   |
| HP Pavilion dv7                        | 4         | 0.26%   |
| HP Laptop 15s-eq2xxx                   | 4         | 0.26%   |
| HP Laptop 15-db0xxx                    | 4         | 0.26%   |
| HP ENVY 17                             | 4         | 0.26%   |
| HP EliteBook Folio 9470m               | 4         | 0.26%   |
| HP EliteBook 8460p                     | 4         | 0.26%   |
| Dell XPS 17 9700                       | 4         | 0.26%   |
| Dell XPS 15 9550                       | 4         | 0.26%   |
| Dell XPS 15 9500                       | 4         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 160       | 10.35%  |
| Acer Aspire        | 96        | 6.21%   |
| Dell Latitude      | 90        | 5.82%   |
| Toshiba Satellite  | 84        | 5.43%   |
| HP Pavilion        | 71        | 4.59%   |
| Dell XPS           | 62        | 4.01%   |
| Dell Inspiron      | 57        | 3.69%   |
| HP EliteBook       | 52        | 3.36%   |
| Lenovo IdeaPad     | 49        | 3.17%   |
| HP ProBook         | 36        | 2.33%   |
| HP Laptop          | 29        | 1.88%   |
| Dell Precision     | 24        | 1.55%   |
| ASUS ZenBook       | 18        | 1.16%   |
| ASUS VivoBook      | 16        | 1.03%   |
| HP ENVY            | 15        | 0.97%   |
| Apple MacBookPro10 | 15        | 0.97%   |
| Toshiba PORTEGE    | 14        | 0.91%   |
| HP Notebook        | 14        | 0.91%   |
| Lenovo Yoga        | 13        | 0.84%   |
| ASUS ROG           | 12        | 0.78%   |
| Apple MacBookPro9  | 11        | 0.71%   |
| Apple MacBookPro11 | 11        | 0.71%   |
| Apple MacBookAir7  | 11        | 0.71%   |
| Acer Swift         | 11        | 0.71%   |
| Valve Jupiter      | 10        | 0.65%   |
| HP 250             | 10        | 0.65%   |
| Apple MacBookPro8  | 10        | 0.65%   |
| Acer Nitro         | 10        | 0.65%   |
| Unknown            | 10        | 0.65%   |
| HP ZBook           | 9         | 0.58%   |
| Dell Vostro        | 9         | 0.58%   |
| ASUS TUF           | 9         | 0.58%   |
| HP Compaq          | 8         | 0.52%   |
| Apple MacBookAir6  | 8         | 0.52%   |
| Toshiba TECRA      | 7         | 0.45%   |
| Lenovo Legion      | 7         | 0.45%   |
| HP OMEN            | 7         | 0.45%   |
| Framework Laptop   | 7         | 0.45%   |
| Razer Blade        | 6         | 0.39%   |
| Dell G3            | 6         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 139       | 8.99%   |
| 2012    | 134       | 8.67%   |
| 2020    | 126       | 8.15%   |
| 2011    | 122       | 7.89%   |
| 2018    | 116       | 7.5%    |
| 2013    | 113       | 7.31%   |
| 2021    | 104       | 6.73%   |
| 2014    | 100       | 6.47%   |
| 2016    | 91        | 5.89%   |
| 2015    | 89        | 5.76%   |
| 2017    | 87        | 5.63%   |
| 2010    | 84        | 5.43%   |
| 2022    | 65        | 4.2%    |
| 2008    | 57        | 3.69%   |
| 2009    | 42        | 2.72%   |
| 2007    | 37        | 2.39%   |
| 2023    | 23        | 1.49%   |
| 2005    | 6         | 0.39%   |
| 2006    | 5         | 0.32%   |
| Unknown | 5         | 0.32%   |
| 2003    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1546      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1397      | 89.55%  |
| Enabled  | 163       | 10.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1534      | 99.22%  |
| Yes  | 12        | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 443       | 28.29%  |
| 16.01-24.0  | 325       | 20.75%  |
| 3.01-4.0    | 314       | 20.05%  |
| 8.01-16.0   | 236       | 15.07%  |
| 32.01-64.0  | 136       | 8.68%   |
| 1.01-2.0    | 55        | 3.51%   |
| 64.01-256.0 | 23        | 1.47%   |
| 24.01-32.0  | 14        | 0.89%   |
| 2.01-3.0    | 12        | 0.77%   |
| 0.51-1.0    | 4         | 0.26%   |
| 0.01-0.5    | 4         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 586       | 32.87%  |
| 2.01-3.0   | 500       | 28.04%  |
| 4.01-8.0   | 253       | 14.19%  |
| 3.01-4.0   | 232       | 13.01%  |
| 0.51-1.0   | 96        | 5.38%   |
| 8.01-16.0  | 84        | 4.71%   |
| 0.01-0.5   | 16        | 0.9%    |
| 16.01-24.0 | 10        | 0.56%   |
| 24.01-32.0 | 3         | 0.17%   |
| 0          | 2         | 0.11%   |
| 32.01-64.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1142      | 70.98%  |
| 2      | 371       | 23.06%  |
| 3      | 63        | 3.92%   |
| 0      | 17        | 1.06%   |
| 4      | 12        | 0.75%   |
| 5      | 2         | 0.12%   |
| 8      | 1         | 0.06%   |
| 7      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1011      | 64.81%  |
| Yes       | 549       | 35.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1248      | 80.41%  |
| No        | 304       | 19.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1518      | 98%     |
| No        | 31        | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1229      | 78.23%  |
| No        | 342       | 21.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 1546      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sydney         | 423       | 25.61%  |
| Melbourne      | 362       | 21.91%  |
| Brisbane       | 264       | 15.98%  |
| Perth          | 128       | 7.75%   |
| Adelaide       | 99        | 5.99%   |
| Canberra       | 31        | 1.88%   |
| Hobart         | 20        | 1.21%   |
| Launceston     | 10        | 0.61%   |
| Gold Coast     | 10        | 0.61%   |
| Richmond       | 8         | 0.48%   |
| Central Coast  | 7         | 0.42%   |
| Woolloongabba  | 6         | 0.36%   |
| Southport      | 6         | 0.36%   |
| Geelong        | 6         | 0.36%   |
| Wollongong     | 5         | 0.3%    |
| Parramatta     | 5         | 0.3%    |
| Newcastle      | 5         | 0.3%    |
| Mitcham        | 5         | 0.3%    |
| Alexandria     | 5         | 0.3%    |
| West End       | 4         | 0.24%   |
| Wahroonga      | 4         | 0.24%   |
| Traralgon      | 4         | 0.24%   |
| Townsville     | 4         | 0.24%   |
| Point Cook     | 4         | 0.24%   |
| Nyngan         | 4         | 0.24%   |
| Mandurah       | 4         | 0.24%   |
| Leinster       | 4         | 0.24%   |
| Geraldton      | 4         | 0.24%   |
| Artarmon       | 4         | 0.24%   |
| Warragul       | 3         | 0.18%   |
| Surry Hills    | 3         | 0.18%   |
| Spring Field   | 3         | 0.18%   |
| Parkdale       | 3         | 0.18%   |
| Mount Waverley | 3         | 0.18%   |
| Hawthorn       | 3         | 0.18%   |
| Doncaster      | 3         | 0.18%   |
| Clifton Hill   | 3         | 0.18%   |
| Campbellfield  | 3         | 0.18%   |
| Brighton       | 3         | 0.18%   |
| Ballarat       | 3         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 350       | 461    | 18.1%   |
| WDC                          | 200       | 283    | 10.34%  |
| Seagate                      | 198       | 314    | 10.24%  |
| Toshiba                      | 163       | 235    | 8.43%   |
| SanDisk                      | 104       | 137    | 5.38%   |
| Unknown                      | 96        | 124    | 4.96%   |
| Intel                        | 79        | 122    | 4.08%   |
| SK hynix                     | 74        | 96     | 3.83%   |
| Kingston                     | 74        | 93     | 3.83%   |
| Crucial                      | 74        | 99     | 3.83%   |
| Apple                        | 74        | 100    | 3.83%   |
| Hitachi                      | 67        | 81     | 3.46%   |
| Micron Technology            | 55        | 69     | 2.84%   |
| HGST                         | 50        | 68     | 2.59%   |
| KIOXIA                       | 22        | 24     | 1.14%   |
| Fujitsu                      | 16        | 21     | 0.83%   |
| Phison                       | 15        | 22     | 0.78%   |
| Phison Electronics           | 14        | 19     | 0.72%   |
| A-DATA Technology            | 13        | 19     | 0.67%   |
| LITEON                       | 12        | 18     | 0.62%   |
| Micron/Crucial Technology    | 10        | 11     | 0.52%   |
| LITEONIT                     | 10        | 12     | 0.52%   |
| Kingston Technology Company  | 9         | 11     | 0.47%   |
| Unknown                      | 9         | 10     | 0.47%   |
| JMicron Technology           | 8         | 13     | 0.41%   |
| SPCC                         | 7         | 9      | 0.36%   |
| Transcend                    | 6         | 8      | 0.31%   |
| OCZ                          | 6         | 8      | 0.31%   |
| KingSpec                     | 6         | 9      | 0.31%   |
| China                        | 5         | 5      | 0.26%   |
| ASMT                         | 5         | 7      | 0.26%   |
| Patriot                      | 4         | 6      | 0.21%   |
| LaCie                        | 4         | 8      | 0.21%   |
| XPG                          | 3         | 3      | 0.16%   |
| Shenzhen Longsys Electronics | 3         | 3      | 0.16%   |
| Realtek                      | 3         | 3      | 0.16%   |
| OWC                          | 3         | 10     | 0.16%   |
| Lite-On                      | 3         | 3      | 0.16%   |
| Gigabyte Technology          | 3         | 6      | 0.16%   |
| ADATA Technology             | 3         | 10     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                              | 21        | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 19        | 0.94%   |
| Toshiba MQ01ABD100 1TB                              | 18        | 0.89%   |
| Seagate ST500LT012-1DG142 500GB                     | 16        | 0.79%   |
| Seagate Expansion 2TB                               | 16        | 0.79%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 14        | 0.69%   |
| Unknown MMC Card  128GB                             | 13        | 0.64%   |
| Toshiba MQ01ABF050 500GB                            | 13        | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB                      | 13        | 0.64%   |
| Samsung NVMe SSD Drive 512GB                        | 13        | 0.64%   |
| HGST HTS721010A9E630 1TB                            | 13        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 12        | 0.59%   |
| Kingston SA400S37240G 240GB SSD                     | 12        | 0.59%   |
| Apple SSD SM0128G 121GB                             | 12        | 0.59%   |
| Unknown MMC Card  32GB                              | 11        | 0.54%   |
| Samsung SSD 850 EVO 250GB                           | 11        | 0.54%   |
| HGST HTS545050A7E680 500GB                          | 11        | 0.54%   |
| Crucial CT500MX500SSD1 500GB                        | 11        | 0.54%   |
| Seagate ST9500325AS 500GB                           | 10        | 0.49%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.49%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 10        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                         | 10        | 0.49%   |
| Crucial CT1000BX500SSD1 1TB                         | 10        | 0.49%   |
| Toshiba MQ04ABF100 1TB                              | 9         | 0.45%   |
| Toshiba MQ01ABD075 752GB                            | 9         | 0.45%   |
| SK hynix NVMe SSD Drive 256GB                       | 9         | 0.45%   |
| Seagate ST2000LM007-1R8174 2TB                      | 9         | 0.45%   |
| Samsung SSD 870 EVO 500GB                           | 9         | 0.45%   |
| Hitachi HTS547575A9E384 752GB                       | 9         | 0.45%   |
| Unknown                                             | 9         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 8         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB                        | 8         | 0.4%    |
| Unknown MMC Card  16GB                              | 8         | 0.4%    |
| Toshiba NVMe SSD Drive 512GB                        | 8         | 0.4%    |
| SanDisk NVMe SSD Drive 256GB                        | 8         | 0.4%    |
| Samsung SSD 860 EVO 1TB                             | 8         | 0.4%    |
| Intel NVMe SSD Drive 512GB                          | 8         | 0.4%    |
| Hitachi HTS545050B9A300 500GB                       | 8         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 192       | 305    | 32.11%  |
| WDC                 | 132       | 188    | 22.07%  |
| Toshiba             | 98        | 150    | 16.39%  |
| Hitachi             | 67        | 81     | 11.2%   |
| HGST                | 50        | 68     | 8.36%   |
| Fujitsu             | 16        | 21     | 2.68%   |
| Samsung Electronics | 12        | 15     | 2.01%   |
| Unknown             | 7         | 7      | 1.17%   |
| Apple               | 5         | 6      | 0.84%   |
| LaCie               | 4         | 7      | 0.67%   |
| ASMT                | 3         | 5      | 0.5%    |
| TO Exter            | 2         | 2      | 0.33%   |
| KESU                | 2         | 2      | 0.33%   |
| HGST HUS            | 2         | 2      | 0.33%   |
| External            | 2         | 2      | 0.33%   |
| USB3.0              | 1         | 1      | 0.17%   |
| USB                 | 1         | 2      | 0.17%   |
| IBM/Hitachi         | 1         | 1      | 0.17%   |
| AAPL                | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 175       | 217    | 28.32%  |
| Crucial             | 62        | 85     | 10.03%  |
| SanDisk             | 54        | 67     | 8.74%   |
| Apple               | 50        | 58     | 8.09%   |
| Kingston            | 49        | 61     | 7.93%   |
| WDC                 | 33        | 44     | 5.34%   |
| Toshiba             | 25        | 35     | 4.05%   |
| Intel               | 25        | 49     | 4.05%   |
| SK hynix            | 24        | 30     | 3.88%   |
| Micron Technology   | 18        | 19     | 2.91%   |
| LITEON              | 11        | 17     | 1.78%   |
| LITEONIT            | 10        | 12     | 1.62%   |
| SPCC                | 7         | 9      | 1.13%   |
| JMicron Technology  | 7         | 11     | 1.13%   |
| A-DATA Technology   | 7         | 9      | 1.13%   |
| Transcend           | 6         | 8      | 0.97%   |
| OCZ                 | 6         | 8      | 0.97%   |
| KingSpec            | 6         | 9      | 0.97%   |
| China               | 5         | 5      | 0.81%   |
| Patriot             | 4         | 6      | 0.65%   |
| Seagate             | 3         | 4      | 0.49%   |
| OWC                 | 3         | 10     | 0.49%   |
| Plextor             | 2         | 6      | 0.32%   |
| Gigabyte Technology | 2         | 2      | 0.32%   |
| FORESEE             | 2         | 2      | 0.32%   |
| WDC WDS2            | 1         | 1      | 0.16%   |
| T-CREATE            | 1         | 1      | 0.16%   |
| SAMSWEET            | 1         | 1      | 0.16%   |
| PNY CS90            | 1         | 1      | 0.16%   |
| PNY                 | 1         | 1      | 0.16%   |
| Mushkin             | 1         | 1      | 0.16%   |
| LT                  | 1         | 1      | 0.16%   |
| Leven               | 1         | 1      | 0.16%   |
| Kston               | 1         | 1      | 0.16%   |
| Kingmax             | 1         | 1      | 0.16%   |
| KingFast            | 1         | 1      | 0.16%   |
| KingDian            | 1         | 1      | 0.16%   |
| INDMEM              | 1         | 1      | 0.16%   |
| HS-SSD-E100         | 1         | 1      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 579       | 806    | 31.94%  |
| HDD     | 560       | 866    | 30.89%  |
| NVMe    | 554       | 822    | 30.56%  |
| MMC     | 93        | 119    | 5.13%   |
| Unknown | 27        | 29     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1009      | 1549   | 57.33%  |
| NVMe | 554       | 817    | 31.48%  |
| SAS  | 104       | 157    | 5.91%   |
| MMC  | 93        | 119    | 5.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 742       | 1058   | 64.13%  |
| 0.51-1.0   | 319       | 448    | 27.57%  |
| 1.01-2.0   | 74        | 132    | 6.4%    |
| 4.01-10.0  | 10        | 13     | 0.86%   |
| 3.01-4.0   | 9         | 14     | 0.78%   |
| 2.01-3.0   | 2         | 5      | 0.17%   |
| 10.01-20.0 | 1         | 2      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 444       | 26.56%  |
| 251-500        | 412       | 24.64%  |
| 501-1000       | 272       | 16.27%  |
| 1-20           | 140       | 8.37%   |
| 1001-2000      | 116       | 6.94%   |
| 51-100         | 115       | 6.88%   |
| More than 3000 | 55        | 3.29%   |
| 21-50          | 42        | 2.51%   |
| Unknown        | 42        | 2.51%   |
| 2001-3000      | 34        | 2.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 715       | 40.46%  |
| 21-50          | 346       | 19.58%  |
| 51-100         | 202       | 11.43%  |
| 101-250        | 187       | 10.58%  |
| 251-500        | 131       | 7.41%   |
| 501-1000       | 78        | 4.41%   |
| Unknown        | 42        | 2.38%   |
| 1001-2000      | 36        | 2.04%   |
| More than 3000 | 14        | 0.79%   |
| 2001-3000      | 14        | 0.79%   |
| 0              | 2         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 3.37%   |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 3.37%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 2.25%   |
| Seagate ST9500325AS 500GB               | 2         | 2      | 2.25%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 2.25%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 2.25%   |
| Micron Technology 1100 SATA 256GB SSD   | 2         | 2      | 2.25%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 2.25%   |
| Hitachi HTS547564A9E384 640GB           | 2         | 2      | 2.25%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 2      | 1.12%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 2      | 1.12%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 3      | 1.12%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 1.12%   |
| WDC WD3200BEVT-75ZCT0 320GB             | 1         | 1      | 1.12%   |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 1      | 1.12%   |
| WDC WD20 EARS-00J2GB0 2TB               | 1         | 1      | 1.12%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2      | 1.12%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.12%   |
| WDC WD Blue SA510 M.2 2280 1000GB       | 1         | 1      | 1.12%   |
| Transcend TS256GSSD230S 256GB           | 1         | 1      | 1.12%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 1         | 1      | 1.12%   |
| Toshiba MQ01ACF032 320GB                | 1         | 1      | 1.12%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.12%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.12%   |
| Toshiba MK5065GSX 500GB                 | 1         | 1      | 1.12%   |
| Toshiba MK5055GSX 500GB                 | 1         | 5      | 1.12%   |
| Toshiba MK3265GSX 320GB                 | 1         | 1      | 1.12%   |
| SK hynix SC308 SATA 256GB SSD           | 1         | 1      | 1.12%   |
| Seagate ST9500423AS 500GB               | 1         | 2      | 1.12%   |
| Seagate ST9500325ASG 500GB              | 1         | 1      | 1.12%   |
| Seagate ST9320423AS 320GB               | 1         | 2      | 1.12%   |
| Seagate ST9250410AS 250GB               | 1         | 1      | 1.12%   |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.12%   |
| Seagate ST9160821AS 160GB               | 1         | 5      | 1.12%   |
| Seagate ST9160310AS 160GB               | 1         | 1      | 1.12%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 2      | 1.12%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.12%   |
| Seagate ST320LT012-9WS14C 320GB         | 1         | 1      | 1.12%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1      | 1.12%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 1      | 1.12%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 21        | 30     | 23.6%   |
| Hitachi                  | 12        | 12     | 13.48%  |
| WDC                      | 10        | 16     | 11.24%  |
| Toshiba                  | 9         | 13     | 10.11%  |
| Samsung Electronics      | 6         | 6      | 6.74%   |
| HGST                     | 6         | 7      | 6.74%   |
| Fujitsu                  | 5         | 5      | 5.62%   |
| Micron Technology        | 4         | 4      | 4.49%   |
| SanDisk                  | 3         | 3      | 3.37%   |
| Kingston                 | 3         | 3      | 3.37%   |
| Intel                    | 2         | 3      | 2.25%   |
| Crucial                  | 2         | 2      | 2.25%   |
| Transcend                | 1         | 1      | 1.12%   |
| SK hynix                 | 1         | 1      | 1.12%   |
| KingSpec                 | 1         | 3      | 1.12%   |
| Biwin Storage Technology | 1         | 1      | 1.12%   |
| Apple                    | 1         | 1      | 1.12%   |
| A-DATA Technology        | 1         | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 30     | 33.87%  |
| Hitachi             | 12        | 12     | 19.35%  |
| WDC                 | 9         | 15     | 14.52%  |
| Toshiba             | 8         | 12     | 12.9%   |
| HGST                | 6         | 7      | 9.68%   |
| Fujitsu             | 5         | 5      | 8.06%   |
| Samsung Electronics | 1         | 1      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 82     | 69.32%  |
| SSD  | 23        | 26     | 26.14%  |
| NVMe | 4         | 4      | 4.55%   |

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
| Detected | 981       | 1656   | 60.04%  |
| Works    | 566       | 874    | 34.64%  |
| Malfunc  | 87        | 112    | 5.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1071      | 58.94%  |
| Samsung Electronics                     | 196       | 10.79%  |
| AMD                                     | 144       | 7.93%   |
| SanDisk                                 | 85        | 4.68%   |
| SK hynix                                | 50        | 2.75%   |
| Toshiba America Info Systems            | 40        | 2.2%    |
| Micron Technology                       | 37        | 2.04%   |
| Kingston Technology Company             | 34        | 1.87%   |
| Phison Electronics                      | 30        | 1.65%   |
| Micron/Crucial Technology               | 23        | 1.27%   |
| KIOXIA                                  | 20        | 1.1%    |
| Apple                                   | 18        | 0.99%   |
| Nvidia                                  | 16        | 0.88%   |
| ADATA Technology                        | 11        | 0.61%   |
| Marvell Technology Group                | 9         | 0.5%    |
| Solid State Storage Technology          | 5         | 0.28%   |
| Silicon Motion                          | 5         | 0.28%   |
| Lite-On Technology                      | 4         | 0.22%   |
| Shenzhen Longsys Electronics            | 3         | 0.17%   |
| Union Memory (Shenzhen)                 | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.11%   |
| Realtek Semiconductor                   | 2         | 0.11%   |
| O2 Micro                                | 2         | 0.11%   |
| Lenovo                                  | 2         | 0.11%   |
| ULi Electronics                         | 1         | 0.06%   |
| Solidigm                                | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| JMicron Technology                      | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |
| ASMedia Technology                      | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 130       | 6.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 129       | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 109       | 5.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 107       | 5.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 101       | 5.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 92        | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 59        | 3.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 57        | 2.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 51        | 2.64%   |
| Intel Volume Management Device NVMe RAID Controller                              | 50        | 2.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 44        | 2.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 41        | 2.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 37        | 1.91%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 33        | 1.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 27        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 25        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 25        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 24        | 1.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 23        | 1.19%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 20        | 1.03%   |
| Intel SSD 660P Series                                                            | 20        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 19        | 0.98%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 0.93%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 17        | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 17        | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 17        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                              | 16        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 0.78%   |
| Phison E12 NVMe Controller                                                       | 14        | 0.72%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 13        | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 13        | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 0.67%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 12        | 0.62%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 12        | 0.62%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 12        | 0.62%   |
| Apple ANS2 NVMe Controller                                                       | 12        | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 11        | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 0.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 10        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1040      | 56.13%  |
| NVMe | 557       | 30.06%  |
| RAID | 167       | 9.01%   |
| IDE  | 89        | 4.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1315      | 85.06%  |
| AMD    | 228       | 14.75%  |
| ARM    | 3         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 35        | 2.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 27        | 1.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 24        | 1.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 23        | 1.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 22        | 1.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 20        | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 20        | 1.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 19        | 1.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 19        | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 18        | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 18        | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 18        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 17        | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 17        | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 17        | 1.1%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 17        | 1.1%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 15        | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 15        | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 0.97%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 14        | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 14        | 0.9%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 14        | 0.9%    |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 14        | 0.9%    |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 13        | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 12        | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 12        | 0.78%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 12        | 0.78%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 11        | 0.71%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 11        | 0.71%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 11        | 0.71%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 11        | 0.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 11        | 0.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 11        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 10        | 0.65%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 10        | 0.65%   |
| Intel 12th Gen Core i7-12700H           | 10        | 0.65%   |
| AMD Custom APU 0405                     | 10        | 0.65%   |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 9         | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 501       | 32.39%  |
| Intel Core i5                  | 386       | 24.95%  |
| Other                          | 150       | 9.7%    |
| Intel Core 2 Duo               | 68        | 4.4%    |
| Intel Core i3                  | 63        | 4.07%   |
| Intel Celeron                  | 62        | 4.01%   |
| AMD Ryzen 7                    | 49        | 3.17%   |
| AMD Ryzen 5                    | 37        | 2.39%   |
| Intel Pentium                  | 29        | 1.87%   |
| AMD A6                         | 22        | 1.42%   |
| AMD A4                         | 21        | 1.36%   |
| Intel Atom                     | 15        | 0.97%   |
| AMD Ryzen 7 PRO                | 10        | 0.65%   |
| AMD E2                         | 10        | 0.65%   |
| AMD Ryzen 9                    | 9         | 0.58%   |
| Intel Core i9                  | 8         | 0.52%   |
| AMD A8                         | 8         | 0.52%   |
| AMD A10                        | 8         | 0.52%   |
| Intel Pentium Dual-Core        | 7         | 0.45%   |
| Intel Core M                   | 7         | 0.45%   |
| Intel Core 2                   | 7         | 0.45%   |
| AMD E1                         | 7         | 0.45%   |
| Intel Genuine                  | 6         | 0.39%   |
| Intel Xeon                     | 5         | 0.32%   |
| Intel Pentium Dual             | 5         | 0.32%   |
| Intel Core m3                  | 5         | 0.32%   |
| AMD Ryzen 3                    | 5         | 0.32%   |
| Intel Celeron Dual-Core        | 4         | 0.26%   |
| AMD E                          | 4         | 0.26%   |
| Intel Pentium M                | 3         | 0.19%   |
| Intel Core m7                  | 3         | 0.19%   |
| Intel Celeron M                | 3         | 0.19%   |
| Intel Core Duo                 | 2         | 0.13%   |
| AMD V120                       | 2         | 0.13%   |
| AMD FX                         | 2         | 0.13%   |
| AMD A12                        | 2         | 0.13%   |
| Intel Mobile Pentium 4         | 1         | 0.06%   |
| Intel Core m5                  | 1         | 0.06%   |
| AMD V140                       | 1         | 0.06%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 740       | 47.8%   |
| 4      | 515       | 33.27%  |
| 6      | 123       | 7.95%   |
| 8      | 85        | 5.49%   |
| 1      | 34        | 2.2%    |
| 10     | 18        | 1.16%   |
| 14     | 17        | 1.1%    |
| 12     | 12        | 0.78%   |
| 16     | 2         | 0.13%   |
| 24     | 1         | 0.06%   |
| 5      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1544      | 99.87%  |
| 2      | 2         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1226      | 79.2%   |
| 1      | 319       | 20.61%  |
| 4      | 2         | 0.13%   |
| 8      | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1516      | 97.55%  |
| 32-bit         | 19        | 1.22%   |
| Unknown        | 17        | 1.09%   |
| 64-bit         | 2         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 549       | 33.81%  |
| 0x206a7    | 94        | 5.79%   |
| 0x306a9    | 84        | 5.17%   |
| 0x406e3    | 52        | 3.2%    |
| 0x40651    | 52        | 3.2%    |
| 0x906ea    | 51        | 3.14%   |
| 0x306d4    | 43        | 2.65%   |
| 0x806ec    | 42        | 2.59%   |
| 0x1067a    | 42        | 2.59%   |
| 0x20655    | 39        | 2.4%    |
| 0x806ea    | 38        | 2.34%   |
| 0x806c1    | 35        | 2.16%   |
| 0x306c3    | 35        | 2.16%   |
| 0x806e9    | 32        | 1.97%   |
| 0x906e9    | 22        | 1.35%   |
| 0xa0652    | 21        | 1.29%   |
| 0x20652    | 20        | 1.23%   |
| 0x06006705 | 19        | 1.17%   |
| 0x0a50000c | 18        | 1.11%   |
| 0x806eb    | 16        | 0.99%   |
| 0x30678    | 15        | 0.92%   |
| 0x07030105 | 15        | 0.92%   |
| 0x706e5    | 13        | 0.8%    |
| 0x506e3    | 13        | 0.8%    |
| 0x906a3    | 12        | 0.74%   |
| 0x806d1    | 12        | 0.74%   |
| 0x0700010f | 12        | 0.74%   |
| 0x106e5    | 11        | 0.68%   |
| 0x10676    | 11        | 0.68%   |
| 0x08108102 | 10        | 0.62%   |
| 0x406c4    | 9         | 0.55%   |
| 0x406c3    | 9         | 0.55%   |
| 0x08108109 | 9         | 0.55%   |
| 0x6fd      | 8         | 0.49%   |
| 0x906a4    | 7         | 0.43%   |
| 0x08600106 | 7         | 0.43%   |
| 0x08600103 | 7         | 0.43%   |
| 0x06001119 | 7         | 0.43%   |
| 0x6f6      | 6         | 0.37%   |
| 0x506c9    | 6         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 286       | 18.48%  |
| IvyBridge        | 142       | 9.17%   |
| Haswell          | 132       | 8.53%   |
| SandyBridge      | 130       | 8.4%    |
| Skylake          | 106       | 6.85%   |
| Westmere         | 71        | 4.59%   |
| Penryn           | 69        | 4.46%   |
| Broadwell        | 63        | 4.07%   |
| Unknown          | 61        | 3.94%   |
| TigerLake        | 53        | 3.42%   |
| CometLake        | 41        | 2.65%   |
| IceLake          | 39        | 2.52%   |
| Silvermont       | 38        | 2.45%   |
| Alderlake Hybrid | 35        | 2.26%   |
| Excavator        | 32        | 2.07%   |
| Zen 3            | 30        | 1.94%   |
| Core             | 26        | 1.68%   |
| Zen+             | 24        | 1.55%   |
| Zen 2            | 24        | 1.55%   |
| Puma             | 20        | 1.29%   |
| Goldmont plus    | 16        | 1.03%   |
| Jaguar           | 14        | 0.9%    |
| P6               | 13        | 0.84%   |
| Nehalem          | 13        | 0.84%   |
| Zen              | 12        | 0.78%   |
| Piledriver       | 10        | 0.65%   |
| Goldmont         | 9         | 0.58%   |
| Bonnell          | 8         | 0.52%   |
| K10 Llano        | 7         | 0.45%   |
| K10              | 6         | 0.39%   |
| Steamroller      | 5         | 0.32%   |
| Bobcat           | 5         | 0.32%   |
| Tremont          | 3         | 0.19%   |
| K8 & K10 hybrid  | 2         | 0.13%   |
| NetBurst         | 1         | 0.06%   |
| K8 Hammer        | 1         | 0.06%   |
| Gracemont        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1164      | 58.17%  |
| Nvidia                           | 490       | 24.49%  |
| AMD                              | 343       | 17.14%  |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| Neomagic                         | 2         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 124       | 5.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 115       | 5.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 78        | 3.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 75        | 3.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 67        | 3.23%   |
| Intel UHD Graphics 620                                                                   | 58        | 2.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 50        | 2.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 50        | 2.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 47        | 2.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 1.93%   |
| Intel HD Graphics 5500                                                                   | 40        | 1.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 33        | 1.59%   |
| Intel HD Graphics 620                                                                    | 32        | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 28        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 1.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 27        | 1.3%    |
| Intel HD Graphics 630                                                                    | 25        | 1.2%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 23        | 1.11%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 1.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.01%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.96%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 18        | 0.87%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 18        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.82%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 17        | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 15        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.72%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 15        | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 15        | 0.72%   |
| Intel HD Graphics 530                                                                    | 15        | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 13        | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 13        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 743       | 47.75%  |
| Intel + Nvidia           | 348       | 22.37%  |
| 1 x AMD                  | 199       | 12.79%  |
| 1 x Nvidia               | 103       | 6.62%   |
| Intel + AMD              | 61        | 3.92%   |
| 2 x AMD                  | 45        | 2.89%   |
| AMD + Nvidia             | 38        | 2.44%   |
| 2 x Intel                | 8         | 0.51%   |
| Other                    | 3         | 0.19%   |
| 1 x SiS                  | 2         | 0.13%   |
| 1 x Neomagic             | 2         | 0.13%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.13%   |
| 2 x Nvidia               | 1         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1297      | 81.78%  |
| Proprietary | 243       | 15.32%  |
| Unknown     | 46        | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1036      | 64.67%  |
| 1.01-2.0   | 164       | 10.24%  |
| 0.01-0.5   | 154       | 9.61%   |
| 3.01-4.0   | 96        | 5.99%   |
| 0.51-1.0   | 89        | 5.56%   |
| 5.01-6.0   | 30        | 1.87%   |
| 7.01-8.0   | 20        | 1.25%   |
| 2.01-3.0   | 8         | 0.5%    |
| 8.01-16.0  | 5         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 366       | 20.29%  |
| LG Display              | 245       | 13.58%  |
| Chimei Innolux          | 184       | 10.2%   |
| Samsung Electronics     | 177       | 9.81%   |
| BOE                     | 163       | 9.04%   |
| Apple                   | 117       | 6.49%   |
| Sharp                   | 75        | 4.16%   |
| Dell                    | 55        | 3.05%   |
| Chi Mei Optoelectronics | 45        | 2.49%   |
| Lenovo                  | 32        | 1.77%   |
| Goldstar                | 28        | 1.55%   |
| Acer                    | 26        | 1.44%   |
| PANDA                   | 25        | 1.39%   |
| Hewlett-Packard         | 24        | 1.33%   |
| Philips                 | 23        | 1.27%   |
| BenQ                    | 22        | 1.22%   |
| Sony                    | 12        | 0.67%   |
| AOC                     | 12        | 0.67%   |
| ViewSonic               | 11        | 0.61%   |
| Valve                   | 10        | 0.55%   |
| InfoVision              | 9         | 0.5%    |
| Unknown                 | 8         | 0.44%   |
| CSO                     | 8         | 0.44%   |
| Ancor Communications    | 8         | 0.44%   |
| LG Philips              | 7         | 0.39%   |
| Toshiba                 | 6         | 0.33%   |
| Panasonic               | 6         | 0.33%   |
| CPT                     | 6         | 0.33%   |
| LGD                     | 5         | 0.28%   |
| Hitachi                 | 5         | 0.28%   |
| GKK                     | 5         | 0.28%   |
| SAC                     | 4         | 0.22%   |
| Kogan                   | 4         | 0.22%   |
| HannStar                | 4         | 0.22%   |
| GDH                     | 4         | 0.22%   |
| eMachines               | 4         | 0.22%   |
| ASUSTek Computer        | 4         | 0.22%   |
| ___                     | 3         | 0.17%   |
| InnoLux Display         | 3         | 0.17%   |
| Unknown (XXX)           | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 19        | 1.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 16        | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 12        | 0.65%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.6%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 10        | 0.54%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 10        | 0.54%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 10        | 0.54%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 10        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.49%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 9         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 8         | 0.43%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 8         | 0.43%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 7         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 7         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 7         | 0.38%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 7         | 0.38%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 7         | 0.38%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.38%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 6         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 6         | 0.33%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 6         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 6         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 6         | 0.33%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 6         | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 6         | 0.33%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 6         | 0.33%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.27%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 5         | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.27%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 642       | 37.94%  |
| 1366x768 (WXGA)    | 502       | 29.67%  |
| 3840x2160 (4K)     | 101       | 5.97%   |
| 1280x800 (WXGA)    | 73        | 4.31%   |
| 1600x900 (HD+)     | 54        | 3.19%   |
| 1440x900 (WXGA+)   | 43        | 2.54%   |
| 2560x1440 (QHD)    | 36        | 2.13%   |
| 1920x1200 (WUXGA)  | 36        | 2.13%   |
| 2560x1600          | 35        | 2.07%   |
| 2880x1800          | 27        | 1.6%    |
| 3840x2400          | 15        | 0.89%   |
| 1680x1050 (WSXGA+) | 15        | 0.89%   |
| 3440x1440          | 12        | 0.71%   |
| 800x1280           | 10        | 0.59%   |
| 3200x1800 (QHD+)   | 9         | 0.53%   |
| 1360x768           | 7         | 0.41%   |
| 1280x1024 (SXGA)   | 7         | 0.41%   |
| 1024x600           | 6         | 0.35%   |
| 3840x1080          | 5         | 0.3%    |
| 3200x2000          | 5         | 0.3%    |
| 3072x1920          | 5         | 0.3%    |
| 2256x1504          | 5         | 0.3%    |
| Unknown            | 5         | 0.3%    |
| 2240x1400          | 4         | 0.24%   |
| 2160x1440          | 4         | 0.24%   |
| 2304x1440          | 3         | 0.18%   |
| 5760x2160          | 2         | 0.12%   |
| 3840x1600          | 2         | 0.12%   |
| 3840x1100          | 2         | 0.12%   |
| 3456x2160          | 2         | 0.12%   |
| 3286x1080          | 2         | 0.12%   |
| 2560x1080          | 2         | 0.12%   |
| 2288x1287          | 2         | 0.12%   |
| 1920x540           | 2         | 0.12%   |
| 1680x945           | 2         | 0.12%   |
| 1280x720 (HD)      | 2         | 0.12%   |
| 1024x768 (XGA)     | 2         | 0.12%   |
| 3000x2000          | 1         | 0.06%   |
| 2880x1620          | 1         | 0.06%   |
| 2726x768           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 702       | 38.78%  |
| 13      | 272       | 15.03%  |
| 14      | 192       | 10.61%  |
| 17      | 107       | 5.91%   |
| 27      | 76        | 4.2%    |
| 24      | 62        | 3.43%   |
| 12      | 51        | 2.82%   |
| 23      | 45        | 2.49%   |
| 11      | 45        | 2.49%   |
| 21      | 35        | 1.93%   |
| 16      | 28        | 1.55%   |
| Unknown | 28        | 1.55%   |
| 31      | 25        | 1.38%   |
| 72      | 12        | 0.66%   |
| 18      | 12        | 0.66%   |
| 84      | 10        | 0.55%   |
| 34      | 10        | 0.55%   |
| 19      | 10        | 0.55%   |
| 7       | 10        | 0.55%   |
| 40      | 8         | 0.44%   |
| 22      | 8         | 0.44%   |
| 10      | 8         | 0.44%   |
| 52      | 7         | 0.39%   |
| 20      | 6         | 0.33%   |
| 54      | 4         | 0.22%   |
| 48      | 4         | 0.22%   |
| 37      | 4         | 0.22%   |
| 86      | 3         | 0.17%   |
| 35      | 3         | 0.17%   |
| 32      | 3         | 0.17%   |
| 142     | 2         | 0.11%   |
| 49      | 2         | 0.11%   |
| 46      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 25      | 2         | 0.11%   |
| 8       | 2         | 0.11%   |
| 78      | 1         | 0.06%   |
| 63      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 38      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 993       | 55.47%  |
| 201-300        | 279       | 15.59%  |
| 501-600        | 156       | 8.72%   |
| 351-400        | 137       | 7.65%   |
| 401-500        | 64        | 3.58%   |
| 601-700        | 39        | 2.18%   |
| Unknown        | 28        | 1.56%   |
| 1001-1500      | 24        | 1.34%   |
| 1501-2000      | 23        | 1.28%   |
| 801-900        | 16        | 0.89%   |
| 701-800        | 15        | 0.84%   |
| 1-100          | 10        | 0.56%   |
| More than 2000 | 2         | 0.11%   |
| 101-200        | 2         | 0.11%   |
| 901-1000       | 2         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1233      | 78.29%  |
| 16/10   | 253       | 16.06%  |
| Unknown | 20        | 1.27%   |
| 3/2     | 16        | 1.02%   |
| 21/9    | 16        | 1.02%   |
| 0.67    | 10        | 0.63%   |
| 5/4     | 8         | 0.51%   |
| 32/9    | 7         | 0.44%   |
| 4/3     | 3         | 0.19%   |
| 0.56    | 3         | 0.19%   |
| 3.40    | 2         | 0.13%   |
| 1.00    | 2         | 0.13%   |
| 6/5     | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 697       | 38.64%  |
| 81-90          | 341       | 18.9%   |
| 71-80          | 124       | 6.87%   |
| 201-250        | 120       | 6.65%   |
| 121-130        | 90        | 4.99%   |
| 301-350        | 76        | 4.21%   |
| 61-70          | 47        | 2.61%   |
| 51-60          | 47        | 2.61%   |
| 351-500        | 42        | 2.33%   |
| More than 1000 | 40        | 2.22%   |
| 111-120        | 31        | 1.72%   |
| 151-200        | 28        | 1.55%   |
| Unknown        | 28        | 1.55%   |
| 501-1000       | 24        | 1.33%   |
| 251-300        | 17        | 0.94%   |
| 131-140        | 15        | 0.83%   |
| 1-40           | 12        | 0.67%   |
| 141-150        | 12        | 0.67%   |
| 41-50          | 9         | 0.5%    |
| 91-100         | 4         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 621       | 35.36%  |
| 101-120       | 518       | 29.5%   |
| 51-100        | 286       | 16.29%  |
| 161-240       | 169       | 9.62%   |
| More than 240 | 98        | 5.58%   |
| 1-50          | 36        | 2.05%   |
| Unknown       | 28        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1245      | 77.28%  |
| 2     | 273       | 16.95%  |
| 0     | 49        | 3.04%   |
| 3     | 39        | 2.42%   |
| 4     | 5         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 843       | 33.35%  |
| Realtek Semiconductor             | 773       | 30.58%  |
| Qualcomm Atheros                  | 328       | 12.97%  |
| Broadcom                          | 193       | 7.63%   |
| Broadcom Limited                  | 63        | 2.49%   |
| MediaTek                          | 32        | 1.27%   |
| Sierra Wireless                   | 28        | 1.11%   |
| Ralink                            | 28        | 1.11%   |
| Marvell Technology Group          | 21        | 0.83%   |
| DisplayLink                       | 19        | 0.75%   |
| Samsung Electronics               | 16        | 0.63%   |
| Dell                              | 15        | 0.59%   |
| Huawei Technologies               | 12        | 0.47%   |
| Hewlett-Packard                   | 12        | 0.47%   |
| Apple                             | 12        | 0.47%   |
| Nvidia                            | 10        | 0.4%    |
| NetGear                           | 10        | 0.4%    |
| Lenovo                            | 10        | 0.4%    |
| TP-Link                           | 9         | 0.36%   |
| Ralink Technology                 | 9         | 0.36%   |
| ZTE WCDMA Technologies MSM        | 8         | 0.32%   |
| ASIX Electronics                  | 8         | 0.32%   |
| Edimax Technology                 | 7         | 0.28%   |
| Qualcomm                          | 6         | 0.24%   |
| OPPO Electronics                  | 6         | 0.24%   |
| JMicron Technology                | 4         | 0.16%   |
| Google                            | 4         | 0.16%   |
| Ericsson Business Mobile Networks | 4         | 0.16%   |
| ASUSTek Computer                  | 4         | 0.16%   |
| Xiaomi                            | 3         | 0.12%   |
| Motorola PCS                      | 3         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.08%   |
| Qualcomm Atheros Communications   | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| ICS Advent                        | 2         | 0.08%   |
| Dresden Elektronik                | 2         | 0.08%   |
| D-Link                            | 2         | 0.08%   |
| Arduino SA                        | 2         | 0.08%   |
| Wilocity                          | 1         | 0.04%   |
| ULi Electronics                   | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 450       | 14.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 129       | 4.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 94        | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 70        | 2.31%   |
| Intel Wireless 8260                                                  | 62        | 2.04%   |
| Intel Wi-Fi 6 AX200                                                  | 61        | 2.01%   |
| Intel Wireless 8265 / 8275                                           | 57        | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 50        | 1.65%   |
| Intel Wireless 7260                                                  | 50        | 1.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 49        | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 48        | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 46        | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 42        | 1.39%   |
| Intel Wi-Fi 6 AX201                                                  | 41        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 38        | 1.25%   |
| Intel Ethernet Connection I219-LM                                    | 38        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 37        | 1.22%   |
| Intel Wireless 3165                                                  | 37        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 36        | 1.19%   |
| Intel Centrino Ultimate-N 6300                                       | 35        | 1.15%   |
| Intel Wireless 7265                                                  | 30        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 30        | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 29        | 0.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 28        | 0.92%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 26        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 25        | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 25        | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 25        | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 24        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                | 23        | 0.76%   |
| Intel Wireless 3160                                                  | 22        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 21        | 0.69%   |
| Intel Wireless-AC 9260                                               | 21        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                             | 21        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 21        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 19        | 0.63%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                    | 18        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 18        | 0.59%   |
| Intel Ethernet Connection I218-LM                                    | 17        | 0.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 17        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 818       | 50.46%  |
| Qualcomm Atheros                | 276       | 17.03%  |
| Realtek Semiconductor           | 173       | 10.67%  |
| Broadcom                        | 153       | 9.44%   |
| Broadcom Limited                | 52        | 3.21%   |
| MediaTek                        | 31        | 1.91%   |
| Sierra Wireless                 | 28        | 1.73%   |
| Ralink                          | 28        | 1.73%   |
| Dell                            | 13        | 0.8%    |
| NetGear                         | 10        | 0.62%   |
| Ralink Technology               | 9         | 0.56%   |
| TP-Link                         | 8         | 0.49%   |
| Qualcomm                        | 5         | 0.31%   |
| ASUSTek Computer                | 4         | 0.25%   |
| Hewlett-Packard                 | 3         | 0.19%   |
| Edimax Technology               | 3         | 0.19%   |
| Qualcomm Atheros Communications | 2         | 0.12%   |
| D-Link                          | 2         | 0.12%   |
| Xiaomi                          | 1         | 0.06%   |
| Wilocity                        | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 62        | 3.81%   |
| Intel Wi-Fi 6 AX200                                                     | 61        | 3.74%   |
| Intel Wireless 8265 / 8275                                              | 57        | 3.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 50        | 3.07%   |
| Intel Wireless 7260                                                     | 50        | 3.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 49        | 3.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 48        | 2.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 46        | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 2.58%   |
| Intel Wi-Fi 6 AX201                                                     | 41        | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 38        | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 2.27%   |
| Intel Wireless 3165                                                     | 37        | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 36        | 2.21%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 2.15%   |
| Intel Wireless 7265                                                     | 30        | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 30        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 28        | 1.72%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 26        | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 1.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 25        | 1.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 24        | 1.47%   |
| Intel Wireless 3160                                                     | 22        | 1.35%   |
| Intel Wireless-AC 9260                                                  | 21        | 1.29%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 19        | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.1%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 17        | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 0.98%   |
| Intel Centrino Advanced-N 6235                                          | 16        | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 0.92%   |
| Intel Centrino Advanced-N 6200                                          | 15        | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 14        | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.8%    |
| Intel WiFi Link 5100                                                    | 13        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 12        | 0.74%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 12        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 696       | 52.13%  |
| Intel                            | 303       | 22.7%   |
| Qualcomm Atheros                 | 98        | 7.34%   |
| Broadcom                         | 85        | 6.37%   |
| Marvell Technology Group         | 21        | 1.57%   |
| DisplayLink                      | 19        | 1.42%   |
| Samsung Electronics              | 12        | 0.9%    |
| Apple                            | 12        | 0.9%    |
| Broadcom Limited                 | 11        | 0.82%   |
| Nvidia                           | 10        | 0.75%   |
| Lenovo                           | 10        | 0.75%   |
| Huawei Technologies              | 9         | 0.67%   |
| ZTE WCDMA Technologies MSM       | 8         | 0.6%    |
| ASIX Electronics                 | 8         | 0.6%    |
| OPPO Electronics                 | 6         | 0.45%   |
| JMicron Technology               | 4         | 0.3%    |
| Google                           | 4         | 0.3%    |
| Edimax Technology                | 4         | 0.3%    |
| Hewlett-Packard                  | 3         | 0.22%   |
| Xiaomi                           | 2         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| Microsoft                        | 2         | 0.15%   |
| ICS Advent                       | 2         | 0.15%   |
| T & A Mobile Phones              | 1         | 0.07%   |
| Qualcomm                         | 1         | 0.07%   |
| Motorola PCS                     | 1         | 0.07%   |
| Attansic Technology              | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 450       | 33.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 129       | 9.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 94        | 6.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 5.15%   |
| Intel Ethernet Connection I219-LM                                 | 38        | 2.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 23        | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 1.55%   |
| Intel 82577LM Gigabit Network Connection                          | 21        | 1.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 1.55%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 18        | 1.32%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.88%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 10        | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.74%   |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.74%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 9         | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.59%   |
| Realtek Killer E3000 2.5GbE Controller                            | 8         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 8         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.44%   |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 6         | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.44%   |
| Huawei E353/E3131                                                 | 6         | 0.44%   |
| DisplayLink Dell Universal Dock D6000                             | 6         | 0.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1518      | 54.19%  |
| Ethernet | 1242      | 44.34%  |
| Modem    | 36        | 1.29%   |
| Unknown  | 5         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1259      | 77.76%  |
| Ethernet | 360       | 22.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1116      | 71.95%  |
| 1     | 412       | 26.56%  |
| 0     | 13        | 0.84%   |
| 3     | 10        | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1348      | 85.81%  |
| Yes  | 223       | 14.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 617       | 49.6%   |
| Qualcomm Atheros Communications | 101       | 8.12%   |
| Apple                           | 99        | 7.96%   |
| Broadcom                        | 75        | 6.03%   |
| Realtek Semiconductor           | 72        | 5.79%   |
| IMC Networks                    | 54        | 4.34%   |
| Foxconn / Hon Hai               | 46        | 3.7%    |
| Lite-On Technology              | 45        | 3.62%   |
| Toshiba                         | 37        | 2.97%   |
| Hewlett-Packard                 | 22        | 1.77%   |
| Dell                            | 17        | 1.37%   |
| Ralink                          | 15        | 1.21%   |
| Cambridge Silicon Radio         | 10        | 0.8%    |
| Alps Electric                   | 8         | 0.64%   |
| Realtek                         | 6         | 0.48%   |
| ASUSTek Computer                | 6         | 0.48%   |
| Ralink Technology               | 4         | 0.32%   |
| USI                             | 3         | 0.24%   |
| Micro Star International        | 2         | 0.16%   |
| MediaTek                        | 2         | 0.16%   |
| Taiyo Yuden                     | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 242       | 19.45%  |
| Intel Bluetooth Device                              | 154       | 12.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 74        | 5.95%   |
| Intel AX200 Bluetooth                               | 61        | 4.9%    |
| Apple Bluetooth Host Controller                     | 54        | 4.34%   |
| Realtek Bluetooth Radio                             | 40        | 3.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 39        | 3.14%   |
| Apple Bluetooth USB Host Controller                 | 35        | 2.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 1.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 22        | 1.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 22        | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.69%   |
| Intel AX210 Bluetooth                               | 21        | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.29%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.29%   |
| Ralink RT3290 Bluetooth                             | 15        | 1.21%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 1.21%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 1.13%   |
| Toshiba Bluetooth Device                            | 13        | 1.05%   |
| IMC Networks Wireless_Device                        | 13        | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 1.05%   |
| IMC Networks Bluetooth Radio                        | 12        | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 0.88%   |
| IMC Networks 802.11ac WLAN Adapter                  | 10        | 0.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 0.8%    |
| Lite-On Bluetooth Device                            | 9         | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.72%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.64%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.64%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.56%   |
| Realtek Bluetooth Radio                             | 6         | 0.48%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.48%   |
| Broadcom BCM20702A0                                 | 6         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1283      | 63.61%  |
| AMD                                          | 283       | 14.03%  |
| Nvidia                                       | 281       | 13.93%  |
| Realtek Semiconductor                        | 22        | 1.09%   |
| Apple                                        | 12        | 0.59%   |
| GN Netcom                                    | 10        | 0.5%    |
| Generalplus Technology                       | 9         | 0.45%   |
| Razer USA                                    | 8         | 0.4%    |
| Lenovo                                       | 8         | 0.4%    |
| Logitech                                     | 7         | 0.35%   |
| C-Media Electronics                          | 7         | 0.35%   |
| Kingston Technology                          | 6         | 0.3%    |
| Creative Technology                          | 6         | 0.3%    |
| Hewlett-Packard                              | 5         | 0.25%   |
| Texas Instruments                            | 4         | 0.2%    |
| Plantronics                                  | 4         | 0.2%    |
| JMTek                                        | 4         | 0.2%    |
| OPPO Electronics                             | 3         | 0.15%   |
| Native Instruments                           | 3         | 0.15%   |
| Microsoft                                    | 3         | 0.15%   |
| Corsair                                      | 3         | 0.15%   |
| Thermaltake                                  | 2         | 0.1%    |
| SteelSeries ApS                              | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 2         | 0.1%    |
| Sennheiser Communications                    | 2         | 0.1%    |
| Samsung Electronics                          | 2         | 0.1%    |
| Micro Star International                     | 2         | 0.1%    |
| M-Audio                                      | 2         | 0.1%    |
| Dell                                         | 2         | 0.1%    |
| Conexant Systems                             | 2         | 0.1%    |
| Chicony Electronics                          | 2         | 0.1%    |
| Blue Microphones                             | 2         | 0.1%    |
| Antlion Audio                                | 2         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| ZOOM                                         | 1         | 0.05%   |
| XMOS                                         | 1         | 0.05%   |
| ULi Electronics                              | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| Spreadtrum Communications                    | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 185       | 7.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 156       | 6.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 115       | 4.79%   |
| AMD Family 17h/19h HD Audio Controller                                     | 113       | 4.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 84        | 3.5%    |
| Intel 8 Series HD Audio Controller                                         | 78        | 3.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 77        | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 73        | 3.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 63        | 2.62%   |
| Intel Broadwell-U Audio Controller                                         | 63        | 2.62%   |
| AMD FCH Azalia Controller                                                  | 57        | 2.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 55        | 2.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 54        | 2.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 53        | 2.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 48        | 2%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 45        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 44        | 1.83%   |
| Intel Comet Lake PCH cAVS                                                  | 39        | 1.62%   |
| AMD Kabini HDMI/DP Audio                                                   | 39        | 1.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 34        | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 33        | 1.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 32        | 1.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 31        | 1.29%   |
| Intel CM238 HD Audio Controller                                            | 30        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 28        | 1.17%   |
| AMD High Definition Audio Controller                                       | 27        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 25        | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                         | 24        | 1%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 23        | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 22        | 0.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 0.87%   |
| Nvidia Audio device                                                        | 20        | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 20        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 20        | 0.83%   |
| Realtek Semiconductor USB Audio                                            | 19        | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 19        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 16        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 285       | 31.28%  |
| SK hynix                   | 227       | 24.92%  |
| Micron Technology          | 130       | 14.27%  |
| Kingston                   | 77        | 8.45%   |
| Crucial                    | 46        | 5.05%   |
| Unknown                    | 32        | 3.51%   |
| Elpida                     | 24        | 2.63%   |
| Ramaxel Technology         | 12        | 1.32%   |
| Corsair                    | 11        | 1.21%   |
| Team                       | 10        | 1.1%    |
| Nanya Technology           | 10        | 1.1%    |
| A-DATA Technology          | 8         | 0.88%   |
| G.Skill                    | 5         | 0.55%   |
| Unknown                    | 5         | 0.55%   |
| Apacer                     | 4         | 0.44%   |
| Silicon Power              | 3         | 0.33%   |
| Unknown (ABCD)             | 2         | 0.22%   |
| Transcend                  | 2         | 0.22%   |
| Toshiba                    | 2         | 0.22%   |
| Smart                      | 2         | 0.22%   |
| Patriot                    | 2         | 0.22%   |
| Unknown (0x89AD)           | 1         | 0.11%   |
| Unknown (0x873E)           | 1         | 0.11%   |
| Qimonda                    | 1         | 0.11%   |
| pqi                        | 1         | 0.11%   |
| Netlist                    | 1         | 0.11%   |
| Neo Forza                  | 1         | 0.11%   |
| GSkill                     | 1         | 0.11%   |
| ff                         | 1         | 0.11%   |
| Avant                      | 1         | 0.11%   |
| ASint Technology           | 1         | 0.11%   |
| Anucell Technology Holding | 1         | 0.11%   |
| 4ea5                       | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 19        | 1.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 1.34%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 1.34%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 12        | 1.24%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.14%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 11        | 1.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 1.03%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 9         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.72%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.72%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 7         | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.62%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.62%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 6         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.62%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.62%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 6         | 0.62%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.62%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.52%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.52%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 0.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.52%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.52%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.52%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 5         | 0.52%   |
| Unknown                                                          | 5         | 0.52%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 0.41%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 4         | 0.41%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 332       | 42.35%  |
| DDR3    | 299       | 38.14%  |
| LPDDR3  | 49        | 6.25%   |
| LPDDR4  | 30        | 3.83%   |
| DDR2    | 27        | 3.44%   |
| LPDDR5  | 17        | 2.17%   |
| DDR5    | 14        | 1.79%   |
| SDRAM   | 10        | 1.28%   |
| Unknown | 3         | 0.38%   |
| DDR     | 2         | 0.26%   |
| DRAM    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 683       | 87.01%  |
| Row Of Chips | 89        | 11.34%  |
| Chip         | 9         | 1.15%   |
| Unknown      | 3         | 0.38%   |
| DIMM         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 333       | 39.74%  |
| 4096  | 226       | 26.97%  |
| 16384 | 141       | 16.83%  |
| 2048  | 91        | 10.86%  |
| 32768 | 29        | 3.46%   |
| 1024  | 12        | 1.43%   |
| 512   | 4         | 0.48%   |
| 1536  | 1         | 0.12%   |
| 256   | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 211       | 25%     |
| 2667    | 167       | 19.79%  |
| 3200    | 129       | 15.28%  |
| 1334    | 56        | 6.64%   |
| 2133    | 50        | 5.92%   |
| 2400    | 45        | 5.33%   |
| 1333    | 25        | 2.96%   |
| 1867    | 19        | 2.25%   |
| 1067    | 18        | 2.13%   |
| 6400    | 17        | 2.01%   |
| 4800    | 17        | 2.01%   |
| 667     | 13        | 1.54%   |
| Unknown | 13        | 1.54%   |
| 4267    | 11        | 1.3%    |
| 8400    | 7         | 0.83%   |
| 4266    | 7         | 0.83%   |
| 3266    | 7         | 0.83%   |
| 1066    | 7         | 0.83%   |
| 800     | 6         | 0.71%   |
| 2048    | 4         | 0.47%   |
| 5600    | 3         | 0.36%   |
| 4199    | 3         | 0.36%   |
| 533     | 3         | 0.36%   |
| 3733    | 2         | 0.24%   |
| 975     | 2         | 0.24%   |
| 1776    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 6         | 46.15%  |
| Hewlett-Packard     | 3         | 23.08%  |
| Canon               | 2         | 15.38%  |
| Samsung Electronics | 1         | 7.69%   |
| Dymo-CoStar         | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon TS3100 series              | 2         | 15.38%  |
| Brother HL-1110 series           | 2         | 15.38%  |
| Samsung ML-1865                  | 1         | 7.69%   |
| HP LaserJet Pro M201dw           | 1         | 7.69%   |
| HP ENVY Inspire 7900 series      | 1         | 7.69%   |
| HP DeskJet 2300 series           | 1         | 7.69%   |
| Dymo-CoStar DYMO LabelWriter 4XL | 1         | 7.69%   |
| Brother MFC-1810                 | 1         | 7.69%   |
| Brother HL-2240D series          | 1         | 7.69%   |
| Brother HL-2140 series           | 1         | 7.69%   |
| Brother HL-1210W series          | 1         | 7.69%   |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 365       | 25.98%  |
| Microdia                               | 128       | 9.11%   |
| Realtek Semiconductor                  | 112       | 7.97%   |
| IMC Networks                           | 111       | 7.9%    |
| Sunplus Innovation Technology          | 105       | 7.47%   |
| Apple                                  | 85        | 6.05%   |
| Bison Electronics                      | 68        | 4.84%   |
| Quanta                                 | 62        | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 56        | 3.99%   |
| Suyin                                  | 52        | 3.7%    |
| Logitech                               | 37        | 2.63%   |
| Acer                                   | 29        | 2.06%   |
| Lite-On Technology                     | 23        | 1.64%   |
| Syntek                                 | 21        | 1.49%   |
| Luxvisions Innotech Limited            | 17        | 1.21%   |
| Silicon Motion                         | 13        | 0.93%   |
| Samsung Electronics                    | 13        | 0.93%   |
| Importek                               | 12        | 0.85%   |
| Ricoh                                  | 11        | 0.78%   |
| Sonix Technology                       | 10        | 0.71%   |
| Alcor Micro                            | 9         | 0.64%   |
| Primax Electronics                     | 7         | 0.5%    |
| Lenovo                                 | 7         | 0.5%    |
| OmniVision Technologies                | 5         | 0.36%   |
| Razer USA                              | 4         | 0.28%   |
| Magic Control Technology               | 4         | 0.28%   |
| DigiTech                               | 4         | 0.28%   |
| ALi                                    | 4         | 0.28%   |
| Z-Star Microelectronics                | 3         | 0.21%   |
| LG Electronics                         | 3         | 0.21%   |
| icSpring                               | 3         | 0.21%   |
| SunplusIT                              | 2         | 0.14%   |
| OPPO Electronics                       | 2         | 0.14%   |
| Microsoft                              | 2         | 0.14%   |
| Genesys Logic                          | 2         | 0.14%   |
| GEMBIRD                                | 2         | 0.14%   |
| Tobii Technology AB                    | 1         | 0.07%   |
| Sunplus Technology                     | 1         | 0.07%   |
| Solid Year                             | 1         | 0.07%   |
| Mimaki Engineering                     | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 72        | 5.05%   |
| Chicony Integrated Camera                               | 64        | 4.49%   |
| Chicony HD Webcam                                       | 34        | 2.38%   |
| Sunplus Integrated_Webcam_HD                            | 33        | 2.31%   |
| Realtek Integrated_Webcam_HD                            | 32        | 2.24%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 30        | 2.1%    |
| Chicony TOSHIBA Web Camera - HD                         | 27        | 1.89%   |
| IMC Networks Integrated Camera                          | 25        | 1.75%   |
| Apple FaceTime HD Camera (Built-in)                     | 25        | 1.75%   |
| Realtek USB Camera                                      | 20        | 1.4%    |
| Apple iPhone 5/5C/5S/6/SE                               | 19        | 1.33%   |
| Apple FaceTime HD Camera                                | 19        | 1.33%   |
| Apple Built-in iSight                                   | 19        | 1.33%   |
| Chicony HP TrueVision HD Camera                         | 18        | 1.26%   |
| Bison Integrated Camera                                 | 18        | 1.26%   |
| Chicony HP TrueVision HD                                | 17        | 1.19%   |
| Chicony HD User Facing                                  | 16        | 1.12%   |
| Sunplus HD WebCam                                       | 14        | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.98%   |
| Syntek Integrated Camera                                | 13        | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 13        | 0.91%   |
| Suyin HP Truevision HD                                  | 12        | 0.84%   |
| Chicony USB 2.0 Camera                                  | 12        | 0.84%   |
| Chicony HP HD Camera                                    | 12        | 0.84%   |
| Quanta HP TrueVision HD Camera                          | 11        | 0.77%   |
| Quanta HD User Facing                                   | 11        | 0.77%   |
| Lite-On Integrated Camera                               | 11        | 0.77%   |
| Chicony USB2.0 Camera                                   | 11        | 0.77%   |
| Chicony CNF9055 Toshiba Webcam                          | 11        | 0.77%   |
| Bison HD Webcam                                         | 11        | 0.77%   |
| Microdia Integrated Webcam                              | 10        | 0.7%    |
| Quanta HP Webcam                                        | 9         | 0.63%   |
| Chicony TOSHIBA Web Camera - FHD                        | 9         | 0.63%   |
| Chicony Integrated Camera (1280x720@30)                 | 9         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 9         | 0.63%   |
| Realtek Integrated Webcam HD                            | 8         | 0.56%   |
| Quanta HD Webcam                                        | 8         | 0.56%   |
| Logitech Webcam C270                                    | 8         | 0.56%   |
| Chicony VGA WebCam                                      | 8         | 0.56%   |
| Bison SunplusIT Integrated Camera                       | 8         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 135       | 44.41%  |
| Synaptics                          | 58        | 19.08%  |
| Shenzhen Goodix Technology         | 34        | 11.18%  |
| LighTuning Technology              | 22        | 7.24%   |
| AuthenTec                          | 18        | 5.92%   |
| Upek                               | 14        | 4.61%   |
| Elan Microelectronics              | 14        | 4.61%   |
| STMicroelectronics                 | 7         | 2.3%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.33%   |
| Focal-systems.Corp                 | 1         | 0.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 9.21%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 7.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 4.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 4.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 3.95%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.95%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.95%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 3.95%   |
| Validity Sensors VFS491                                                    | 11        | 3.62%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 3.62%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 3.62%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 10        | 3.29%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.96%   |
| Validity Sensors VFS Fingerprint sensor                                    | 8         | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.3%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.3%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 2.3%    |
| Elan ELAN:Fingerprint                                                      | 7         | 2.3%    |
| Elan ELAN:ARM-M4                                                           | 7         | 2.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.97%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.97%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.64%   |
| Synaptics WBDI Device                                                      | 5         | 1.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.32%   |
| AuthenTec AES1600                                                          | 4         | 1.32%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.99%   |
| Synaptics  WBDI                                                            | 3         | 0.99%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.99%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.66%   |
| Synaptics UWP WBDI                                                         | 2         | 0.66%   |
| Synaptics TouchPad                                                         | 2         | 0.66%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.66%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.66%   |
| AuthenTec AES2810                                                          | 2         | 0.66%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 40        | 62.5%   |
| Alcor Micro           | 13        | 20.31%  |
| Upek                  | 4         | 6.25%   |
| Lenovo                | 3         | 4.69%   |
| O2 Micro              | 2         | 3.13%   |
| Gemalto (was Gemplus) | 1         | 1.56%   |
| Advanced Card Systems | 1         | 1.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 28.13%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 20.31%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 12.5%   |
| Broadcom 5880                                                                | 7         | 10.94%  |
| Broadcom 58200                                                               | 7         | 10.94%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.13%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.56%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 938       | 58.19%  |
| 1     | 545       | 33.81%  |
| 2     | 107       | 6.64%   |
| 3     | 15        | 0.93%   |
| 4     | 6         | 0.37%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 301       | 38.25%  |
| Graphics card            | 168       | 21.35%  |
| Net/wireless             | 71        | 9.02%   |
| Multimedia controller    | 60        | 7.62%   |
| Chipcard                 | 58        | 7.37%   |
| Bluetooth                | 26        | 3.3%    |
| Camera                   | 24        | 3.05%   |
| Storage                  | 17        | 2.16%   |
| Net/ethernet             | 17        | 2.16%   |
| Communication controller | 14        | 1.78%   |
| Modem                    | 10        | 1.27%   |
| Sound                    | 8         | 1.02%   |
| Card reader              | 8         | 1.02%   |
| Video                    | 1         | 0.13%   |
| Unassigned class         | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |
| Storage/ata              | 1         | 0.13%   |
| Flash memory             | 1         | 0.13%   |

