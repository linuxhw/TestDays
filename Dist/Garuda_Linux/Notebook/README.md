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

Total: 321

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Standard      | Unknown                     | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | Pavilion dv6                | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| HP            | Pavilion dv6                | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| HP            | Pavilion dv6                | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Unknown       | Unknown                     | [39bd375140](https://linux-hardware.org/?probe=39bd375140) | Jan 19, 2023 |
| HP            | ProBook 6570b               | [919b330a89](https://linux-hardware.org/?probe=919b330a89) | Jan 15, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [06fc7ee349](https://linux-hardware.org/?probe=06fc7ee349) | Jan 10, 2023 |
| Acer          | Aspire A515-46              | [1ba0c80baf](https://linux-hardware.org/?probe=1ba0c80baf) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| HP            | ProBook 6570b               | [71e645c6db](https://linux-hardware.org/?probe=71e645c6db) | Jan 08, 2023 |
| Lenovo        | G570 4334                   | [c3162b7bfa](https://linux-hardware.org/?probe=c3162b7bfa) | Jan 07, 2023 |
| Lenovo        | G570 4334                   | [8d0c80e474](https://linux-hardware.org/?probe=8d0c80e474) | Jan 07, 2023 |
| HP            | ProBook 6570b               | [6db7bfdd12](https://linux-hardware.org/?probe=6db7bfdd12) | Jan 07, 2023 |
| Dell          | G15 5515                    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| HP            | ProBook 6570b               | [32d96991fd](https://linux-hardware.org/?probe=32d96991fd) | Jan 06, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Gigabyte      | G5 MD                       | [901f1e43f0](https://linux-hardware.org/?probe=901f1e43f0) | Dec 31, 2022 |
| Gigabyte      | G5 MD                       | [631ee5c81c](https://linux-hardware.org/?probe=631ee5c81c) | Dec 31, 2022 |
| MSI           | Stealth 15M B12UE           | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| Acer          | Aspire F5-572G              | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| HP            | Compaq CQ58                 | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| HONOR         | BOD-WXX9                    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| HP            | Dev One Notebook PC         | [0e92e9aaf2](https://linux-hardware.org/?probe=0e92e9aaf2) | Dec 23, 2022 |
| Acer          | Nitro AN515-45              | [5cc9050d12](https://linux-hardware.org/?probe=5cc9050d12) | Dec 22, 2022 |
| Alienware     | m15 R7                      | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [b262201707](https://linux-hardware.org/?probe=b262201707) | Dec 10, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [0247b424ca](https://linux-hardware.org/?probe=0247b424ca) | Dec 04, 2022 |
| Dell          | Latitude E5450              | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| Dell          | Latitude E7450              | [2df62b206f](https://linux-hardware.org/?probe=2df62b206f) | Dec 03, 2022 |
| Dell          | XPS 13 9360                 | [93aed684b7](https://linux-hardware.org/?probe=93aed684b7) | Dec 03, 2022 |
| Standard      | Unknown                     | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| HP            | EliteBook 840 G5            | [8967d04a19](https://linux-hardware.org/?probe=8967d04a19) | Nov 25, 2022 |
| HP            | 250 G6 Notebook PC          | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| ASUSTek       | X541UV                      | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| MSI           | Modern 14 B4MW              | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [5c079d3e41](https://linux-hardware.org/?probe=5c079d3e41) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| Dell          | Precision 3571              | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | ProBook 640 G1              | [8641947cf9](https://linux-hardware.org/?probe=8641947cf9) | Nov 05, 2022 |
| Unknown       | Unknown                     | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| Unknown       | Unknown                     | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
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
| Unknown       | Unknown                     | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
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
| Unknown       | Unknown                     | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Razer         | Blade                       | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| Unknown       | Unknown                     | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
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
| Unknown       | Unknown                     | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| HUAWEI        | CREM-WXX9                   | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| Casper        | EXCALIBUR G770              | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| Dell          | Latitude E7250              | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| Unknown       | Unknown                     | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
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
| Unknown       | Unknown                     | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| HONOR         | HLYL-WXX9                   | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| Unknown       | Unknown                     | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| Unknown       | Unknown                     | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
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
| Unknown       | Unknown                     | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
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
| Unknown       | Unknown                     | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Panasonic     | CF-191HYAX1M                | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| Unknown       | Unknown                     | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
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
| Unknown       | Unknown                     | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
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
| Garuda Linux Soaring | 151       | 70.23%  |
| Garuda Linux         | 46        | 21.4%   |
| Garuda Linux Rolling | 18        | 8.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Garuda Linux | 211       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 6.1.1-zen1-1-zen   | 8         | 3.15%   |
| 6.0.2-zen1-1-zen   | 8         | 3.15%   |
| 5.17.9-zen1-1-zen  | 6         | 2.36%   |
| 6.1.7-zen1-1-zen   | 4         | 1.57%   |
| 6.0.9-zen1-1-zen   | 4         | 1.57%   |
| 6.0.6-zen1-1-zen   | 4         | 1.57%   |
| 6.0.10-zen2-1-zen  | 4         | 1.57%   |
| 5.16.16-zen1-1-zen | 4         | 1.57%   |
| 5.14.14-zen1-1-zen | 4         | 1.57%   |
| 5.13.13-zen1-1-zen | 4         | 1.57%   |
| 6.0.8-zen1-1-zen   | 3         | 1.18%   |
| 5.19.7-zen2-1-zen  | 3         | 1.18%   |
| 5.19.13-zen1-1-zen | 3         | 1.18%   |
| 5.19.10-zen1-1-zen | 3         | 1.18%   |
| 5.18.16-zen1-1-zen | 3         | 1.18%   |
| 5.17.3-zen1-1-zen  | 3         | 1.18%   |
| 5.17.1-zen1-1-zen  | 3         | 1.18%   |
| 5.16.4-zen1-1-zen  | 3         | 1.18%   |
| 5.16.2-zen1-1-zen  | 3         | 1.18%   |
| 5.15.6-zen2-1-zen  | 3         | 1.18%   |
| 5.15.2-zen1-1-zen  | 3         | 1.18%   |
| 5.15.12-zen1-1-zen | 3         | 1.18%   |
| 5.14.6-zen1-1-zen  | 3         | 1.18%   |
| 5.13.9-zen1-1-zen  | 3         | 1.18%   |
| 5.11.11-zen1-1-zen | 3         | 1.18%   |
| 5.10.1-103-tkg-bmq | 3         | 1.18%   |
| 6.0.12-zen1-1-zen  | 2         | 0.79%   |
| 5.19.3-zen1-1-zen  | 2         | 0.79%   |
| 5.19.2-zen1-1-zen  | 2         | 0.79%   |
| 5.19.11-zen1-1-zen | 2         | 0.79%   |
| 5.18.6-zen1-1-zen  | 2         | 0.79%   |
| 5.18.3-zen1-1-zen  | 2         | 0.79%   |
| 5.18.14-zen1-1-zen | 2         | 0.79%   |
| 5.17.5-zen1-1-zen  | 2         | 0.79%   |
| 5.16.8-arch1-1     | 2         | 0.79%   |
| 5.16.5-zen1-1-zen  | 2         | 0.79%   |
| 5.16.14-zen1-1-zen | 2         | 0.79%   |
| 5.16.1-zen1-1-zen  | 2         | 0.79%   |
| 5.15.5-zen1-1-zen  | 2         | 0.79%   |
| 5.15.4-zen1-1-zen  | 2         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.2   | 9         | 3.54%   |
| 6.1.1   | 8         | 3.15%   |
| 5.17.9  | 6         | 2.36%   |
| 6.0.10  | 5         | 1.97%   |
| 5.17.1  | 5         | 1.97%   |
| 6.1.7   | 4         | 1.57%   |
| 6.0.9   | 4         | 1.57%   |
| 6.0.8   | 4         | 1.57%   |
| 6.0.6   | 4         | 1.57%   |
| 5.19.7  | 4         | 1.57%   |
| 5.18.16 | 4         | 1.57%   |
| 5.17.5  | 4         | 1.57%   |
| 5.17.3  | 4         | 1.57%   |
| 5.16.2  | 4         | 1.57%   |
| 5.16.16 | 4         | 1.57%   |
| 5.14.14 | 4         | 1.57%   |
| 5.13.13 | 4         | 1.57%   |
| 5.11.11 | 4         | 1.57%   |
| 5.19.2  | 3         | 1.18%   |
| 5.19.13 | 3         | 1.18%   |
| 5.19.10 | 3         | 1.18%   |
| 5.18.3  | 3         | 1.18%   |
| 5.16.5  | 3         | 1.18%   |
| 5.16.4  | 3         | 1.18%   |
| 5.15.6  | 3         | 1.18%   |
| 5.15.5  | 3         | 1.18%   |
| 5.15.2  | 3         | 1.18%   |
| 5.15.12 | 3         | 1.18%   |
| 5.14.6  | 3         | 1.18%   |
| 5.13.9  | 3         | 1.18%   |
| 5.12.9  | 3         | 1.18%   |
| 5.10.15 | 3         | 1.18%   |
| 5.10.1  | 3         | 1.18%   |
| 6.1.3   | 2         | 0.79%   |
| 6.0.12  | 2         | 0.79%   |
| 6.0.1   | 2         | 0.79%   |
| 5.19.6  | 2         | 0.79%   |
| 5.19.3  | 2         | 0.79%   |
| 5.19.11 | 2         | 0.79%   |
| 5.18.6  | 2         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 32        | 13.22%  |
| 5.15    | 31        | 12.81%  |
| 5.19    | 23        | 9.5%    |
| 5.16    | 22        | 9.09%   |
| 5.14    | 20        | 8.26%   |
| 5.10    | 20        | 8.26%   |
| 5.17    | 19        | 7.85%   |
| 5.18    | 18        | 7.44%   |
| 6.1     | 15        | 6.2%    |
| 5.13    | 12        | 4.96%   |
| 5.12    | 12        | 4.96%   |
| 5.11    | 12        | 4.96%   |
| 5.9     | 4         | 1.65%   |
| 5.6     | 1         | 0.41%   |
| 5.4     | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 211       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KDE5              | 145       | 67.76%  |
| GNOME             | 27        | 12.62%  |
| KDE               | 12        | 5.61%   |
| XFCE              | 9         | 4.21%   |
| X-Cinnamon        | 6         | 2.8%    |
| sway              | 5         | 2.34%   |
| qtile-default     | 2         | 0.93%   |
| Deepin            | 2         | 0.93%   |
| Yaru:ubuntu:GNOME | 1         | 0.47%   |
| Unity             | 1         | 0.47%   |
| MATE              | 1         | 0.47%   |
| i3                | 1         | 0.47%   |
| awesome           | 1         | 0.47%   |
| Unknown           | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 187       | 87.38%  |
| Wayland | 19        | 8.88%   |
| Unknown | 5         | 2.34%   |
| Tty     | 3         | 1.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 112       | 52.09%  |
| Unknown | 65        | 30.23%  |
| LightDM | 19        | 8.84%   |
| GDM     | 16        | 7.44%   |
| GREETD  | 3         | 1.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 107       | 50.23%  |
| en_GB   | 24        | 11.27%  |
| en_IN   | 17        | 7.98%   |
| de_DE   | 11        | 5.16%   |
| it_IT   | 9         | 4.23%   |
| pt_BR   | 6         | 2.82%   |
| en_CA   | 5         | 2.35%   |
| ru_RU   | 3         | 1.41%   |
| pl_PL   | 3         | 1.41%   |
| nl_NL   | 3         | 1.41%   |
| es_MX   | 3         | 1.41%   |
| fi_FI   | 2         | 0.94%   |
| es_ES   | 2         | 0.94%   |
| es_CO   | 2         | 0.94%   |
| en_ZA   | 2         | 0.94%   |
| en_DK   | 2         | 0.94%   |
| en_AG   | 2         | 0.94%   |
| uk_UA   | 1         | 0.47%   |
| tr_TR   | 1         | 0.47%   |
| sv_SE   | 1         | 0.47%   |
| ko_KR   | 1         | 0.47%   |
| ja_JP   | 1         | 0.47%   |
| fr_FR   | 1         | 0.47%   |
| es_VE   | 1         | 0.47%   |
| es_EC   | 1         | 0.47%   |
| de_AT   | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 140       | 65.42%  |
| BIOS | 74        | 34.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 205       | 97.16%  |
| Overlay | 4         | 1.9%    |
| XXXXX   | 1         | 0.47%   |
| F2fs    | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 139       | 65.26%  |
| Unknown | 64        | 30.05%  |
| MBR     | 10        | 4.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 197       | 92.49%  |
| Yes       | 16        | 7.51%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 67.29%  |
| Yes       | 70        | 32.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 46        | 21.8%   |
| Hewlett-Packard     | 39        | 18.48%  |
| Dell                | 28        | 13.27%  |
| ASUSTek Computer    | 28        | 13.27%  |
| Acer                | 21        | 9.95%   |
| MSI                 | 10        | 4.74%   |
| Unknown             | 4         | 1.9%    |
| Samsung Electronics | 3         | 1.42%   |
| Razer               | 3         | 1.42%   |
| Notebook            | 3         | 1.42%   |
| Toshiba             | 2         | 0.95%   |
| Sony                | 2         | 0.95%   |
| Medion              | 2         | 0.95%   |
| HUAWEI              | 2         | 0.95%   |
| HONOR               | 2         | 0.95%   |
| Gigabyte Technology | 2         | 0.95%   |
| Apple               | 2         | 0.95%   |
| Alienware           | 2         | 0.95%   |
| Standard            | 1         | 0.47%   |
| PC Specialist       | 1         | 0.47%   |
| Panasonic           | 1         | 0.47%   |
| Kogan               | 1         | 0.47%   |
| GPU Company         | 1         | 0.47%   |
| Google              | 1         | 0.47%   |
| Fujitsu Siemens     | 1         | 0.47%   |
| Fujitsu             | 1         | 0.47%   |
| Chuwi               | 1         | 0.47%   |
| Casper              | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 6         | 2.84%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 5         | 2.37%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.95%   |
| HP ProBook 640 G1                          | 2         | 0.95%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.95%   |
| HP Pavilion dv6                            | 2         | 0.95%   |
| HP Notebook                                | 2         | 0.95%   |
| Gigabyte G5 MD                             | 2         | 0.95%   |
| Dell XPS 15 9500                           | 2         | 0.95%   |
| Dell Latitude E6420                        | 2         | 0.95%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.95%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 0.95%   |
| Acer Nitro AN515-44                        | 2         | 0.95%   |
| Acer Aspire A515-51G                       | 2         | 0.95%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.47%   |
| Toshiba Satellite C55-A                    | 1         | 0.47%   |
| Sony VPCSB1C5E                             | 1         | 0.47%   |
| Sony SVF1521Q1EW                           | 1         | 0.47%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.47%   |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.47%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.47%   |
| Razer Blade 17 (Mid 2021) - RZ09-0406      | 1         | 0.47%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.47%   |
| Razer Blade                                | 1         | 0.47%   |
| PC Specialist GK5NPFO                      | 1         | 0.47%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.47%   |
| Notebook W54_W550SU2                       | 1         | 0.47%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.47%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.47%   |
| MSI Sword 15 A11UD                         | 1         | 0.47%   |
| MSI Stealth 15M B12UE                      | 1         | 0.47%   |
| MSI Modern 14 B4MW                         | 1         | 0.47%   |
| MSI GS76 Stealth 11UG                      | 1         | 0.47%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.47%   |
| MSI GF63 Thin 9SC                          | 1         | 0.47%   |
| MSI GF63 Thin 10SC                         | 1         | 0.47%   |
| MSI GE75 Raider 9SE                        | 1         | 0.47%   |
| MSI GE72VR 6RF                             | 1         | 0.47%   |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.47%   |
| Medion P861X                               | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 17        | 8.06%   |
| Lenovo ThinkPad        | 16        | 7.58%   |
| Acer Aspire            | 11        | 5.21%   |
| HP Pavilion            | 10        | 4.74%   |
| Dell Latitude          | 9         | 4.27%   |
| Dell Inspiron          | 9         | 4.27%   |
| ASUS VivoBook          | 9         | 4.27%   |
| HP Laptop              | 7         | 3.32%   |
| Lenovo Legion          | 6         | 2.84%   |
| Dell XPS               | 6         | 2.84%   |
| ASUS ROG               | 6         | 2.84%   |
| Unknown                | 6         | 2.84%   |
| HP OMEN                | 5         | 2.37%   |
| Acer Nitro             | 5         | 2.37%   |
| Acer Swift             | 4         | 1.9%    |
| Razer Blade            | 3         | 1.42%   |
| HP ProBook             | 3         | 1.42%   |
| HP EliteBook           | 3         | 1.42%   |
| Toshiba Satellite      | 2         | 0.95%   |
| MSI GF63               | 2         | 0.95%   |
| HP Victus              | 2         | 0.95%   |
| HP Notebook            | 2         | 0.95%   |
| HP Compaq              | 2         | 0.95%   |
| Gigabyte G5            | 2         | 0.95%   |
| Dell Precision         | 2         | 0.95%   |
| ASUS TUF               | 2         | 0.95%   |
| ASUS ASUS              | 2         | 0.95%   |
| Sony VPCSB1C5E         | 1         | 0.47%   |
| Sony SVF1521Q1EW       | 1         | 0.47%   |
| Samsung 550XCJ         | 1         | 0.47%   |
| Samsung 340XAA         | 1         | 0.47%   |
| Samsung 300V3A         | 1         | 0.47%   |
| PC Specialist GK5NPFO  | 1         | 0.47%   |
| Panasonic CF-191HYAX1M | 1         | 0.47%   |
| Notebook W54           | 1         | 0.47%   |
| Notebook P7xxDM2(-G)   | 1         | 0.47%   |
| Notebook N85           | 1         | 0.47%   |
| MSI Sword              | 1         | 0.47%   |
| MSI Stealth            | 1         | 0.47%   |
| MSI Modern             | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 40        | 18.96%  |
| 2021 | 37        | 17.54%  |
| 2019 | 19        | 9%      |
| 2018 | 17        | 8.06%   |
| 2016 | 16        | 7.58%   |
| 2017 | 14        | 6.64%   |
| 2013 | 13        | 6.16%   |
| 2014 | 11        | 5.21%   |
| 2012 | 11        | 5.21%   |
| 2015 | 8         | 3.79%   |
| 2011 | 8         | 3.79%   |
| 2022 | 7         | 3.32%   |
| 2009 | 3         | 1.42%   |
| 2008 | 3         | 1.42%   |
| 2010 | 2         | 0.95%   |
| 2007 | 2         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 211       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 211       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 210       | 99.53%  |
| Yes  | 1         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 66        | 30.84%  |
| 8.01-16.0   | 56        | 26.17%  |
| 16.01-24.0  | 51        | 23.83%  |
| 32.01-64.0  | 17        | 7.94%   |
| 3.01-4.0    | 17        | 7.94%   |
| 24.01-32.0  | 4         | 1.87%   |
| 64.01-256.0 | 2         | 0.93%   |
| 2.01-3.0    | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 73        | 31.6%   |
| 2.01-3.0   | 62        | 26.84%  |
| 3.01-4.0   | 60        | 25.97%  |
| 1.01-2.0   | 17        | 7.36%   |
| 8.01-16.0  | 17        | 7.36%   |
| 32.01-64.0 | 1         | 0.43%   |
| 0.51-1.0   | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 134       | 61.75%  |
| 2      | 68        | 31.34%  |
| 3      | 13        | 5.99%   |
| 4      | 1         | 0.46%   |
| 0      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 162       | 75.7%   |
| Yes       | 52        | 24.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 75%     |
| No        | 53        | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 98.11%  |
| No        | 4         | 1.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 88.68%  |
| No        | 24        | 11.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 61        | 28.5%   |
| India        | 18        | 8.41%   |
| Germany      | 18        | 8.41%   |
| UK           | 15        | 7.01%   |
| Italy        | 11        | 5.14%   |
| Poland       | 9         | 4.21%   |
| Canada       | 9         | 4.21%   |
| Brazil       | 9         | 4.21%   |
| Netherlands  | 5         | 2.34%   |
| Mexico       | 5         | 2.34%   |
| Spain        | 4         | 1.87%   |
| South Africa | 3         | 1.4%    |
| Russia       | 3         | 1.4%    |
| Romania      | 3         | 1.4%    |
| France       | 3         | 1.4%    |
| Finland      | 3         | 1.4%    |
| Denmark      | 3         | 1.4%    |
| Turkey       | 2         | 0.93%   |
| Switzerland  | 2         | 0.93%   |
| Sweden       | 2         | 0.93%   |
| Singapore    | 2         | 0.93%   |
| Colombia     | 2         | 0.93%   |
| Belgium      | 2         | 0.93%   |
| Venezuela    | 1         | 0.47%   |
| Thailand     | 1         | 0.47%   |
| South Korea  | 1         | 0.47%   |
| Slovenia     | 1         | 0.47%   |
| Serbia       | 1         | 0.47%   |
| Portugal     | 1         | 0.47%   |
| Oman         | 1         | 0.47%   |
| Luxembourg   | 1         | 0.47%   |
| Latvia       | 1         | 0.47%   |
| Kuwait       | 1         | 0.47%   |
| Kenya        | 1         | 0.47%   |
| Japan        | 1         | 0.47%   |
| Indonesia    | 1         | 0.47%   |
| Hungary      | 1         | 0.47%   |
| Ecuador      | 1         | 0.47%   |
| Czechia      | 1         | 0.47%   |
| China        | 1         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| London             | 4         | 1.77%   |
| Mumbai             | 3         | 1.33%   |
| Copenhagen         | 3         | 1.33%   |
| Cape Town          | 3         | 1.33%   |
| Berlin             | 3         | 1.33%   |
| Wroclaw            | 2         | 0.88%   |
| Warsaw             | 2         | 0.88%   |
| Turin              | 2         | 0.88%   |
| Toronto            | 2         | 0.88%   |
| Singapore          | 2         | 0.88%   |
| San Jose           | 2         | 0.88%   |
| Portland           | 2         | 0.88%   |
| Peterborough       | 2         | 0.88%   |
| Noida              | 2         | 0.88%   |
| New York           | 2         | 0.88%   |
| Milan              | 2         | 0.88%   |
| Los Angeles        | 2         | 0.88%   |
| Lancaster          | 2         | 0.88%   |
| Kansas City        | 2         | 0.88%   |
| Helsinki           | 2         | 0.88%   |
| Frankfurt am Main  | 2         | 0.88%   |
| Düsseldorf        | 2         | 0.88%   |
| Delhi              | 2         | 0.88%   |
| Chennai            | 2         | 0.88%   |
| Big Bend           | 2         | 0.88%   |
| Belo Horizonte     | 2         | 0.88%   |
| Zafra              | 1         | 0.44%   |
| Winston-Salem      | 1         | 0.44%   |
| Welwyn Garden City | 1         | 0.44%   |
| Wasilla            | 1         | 0.44%   |
| Vancouver          | 1         | 0.44%   |
| Valencia           | 1         | 0.44%   |
| Tustin             | 1         | 0.44%   |
| Turku              | 1         | 0.44%   |
| Tucson             | 1         | 0.44%   |
| Troy               | 1         | 0.44%   |
| Timișoara         | 1         | 0.44%   |
| Terneuzen          | 1         | 0.44%   |
| Tarczyn            | 1         | 0.44%   |
| Tacoma             | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 49        | 81     | 16.5%   |
| Seagate                     | 35        | 49     | 11.78%  |
| WDC                         | 27        | 29     | 9.09%   |
| SK hynix                    | 25        | 32     | 8.42%   |
| Sandisk                     | 22        | 28     | 7.41%   |
| Unknown                     | 12        | 12     | 4.04%   |
| Toshiba                     | 12        | 15     | 4.04%   |
| Intel                       | 12        | 17     | 4.04%   |
| HGST                        | 11        | 11     | 3.7%    |
| Micron Technology           | 9         | 11     | 3.03%   |
| Crucial                     | 9         | 12     | 3.03%   |
| Kingston                    | 8         | 8      | 2.69%   |
| Phison Electronics          | 6         | 6      | 2.02%   |
| Hitachi                     | 6         | 6      | 2.02%   |
| KIOXIA                      | 5         | 7      | 1.68%   |
| SPCC                        | 4         | 4      | 1.35%   |
| Silicon Motion              | 4         | 4      | 1.35%   |
| PNY                         | 3         | 3      | 1.01%   |
| Phison                      | 3         | 3      | 1.01%   |
| LITEON                      | 3         | 3      | 1.01%   |
| Corsair                     | 3         | 3      | 1.01%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.67%   |
| JMicron Technology          | 2         | 2      | 0.67%   |
| China                       | 2         | 2      | 0.67%   |
| A-DATA Technology           | 2         | 2      | 0.67%   |
| Yangtze Memory Technologies | 1         | 1      | 0.34%   |
| WODPOSIT                    | 1         | 2      | 0.34%   |
| WDC WDS                     | 1         | 1      | 0.34%   |
| VisionTek                   | 1         | 2      | 0.34%   |
| UMIS                        | 1         | 2      | 0.34%   |
| SSSTC                       | 1         | 1      | 0.34%   |
| ShanDianZhe                 | 1         | 1      | 0.34%   |
| SABRENT                     | 1         | 2      | 0.34%   |
| PNY CS90                    | 1         | 1      | 0.34%   |
| Netac                       | 1         | 1      | 0.34%   |
| Mushkin                     | 1         | 1      | 0.34%   |
| Micron/Crucial Technology   | 1         | 1      | 0.34%   |
| LITEONIT                    | 1         | 1      | 0.34%   |
| Lenovo                      | 1         | 1      | 0.34%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 2.55%   |
| Samsung NVMe SSD Drive 1TB                          | 6         | 1.91%   |
| Seagate ST1000LM049-2GH172 1TB                      | 5         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 1.59%   |
| Samsung SSD 860 EVO 1TB                             | 4         | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4         | 1.27%   |
| HGST HTS721010A9E630 1TB                            | 4         | 1.27%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.96%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 3         | 0.96%   |
| Phison E16 PCIe4 NVMe Controller 2TB                | 3         | 0.96%   |
| Intel SSDPEKNU512GZ 512GB                           | 3         | 0.96%   |
| Intel SSD 660P Series 512GB                         | 3         | 0.96%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.96%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 2         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.64%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                | 2         | 0.64%   |
| Unknown MMC Card  64GB                              | 2         | 0.64%   |
| Unknown MMC Card  16GB                              | 2         | 0.64%   |
| SPCC Solid State Disk 512GB                         | 2         | 0.64%   |
| SK hynix SC311 SATA 256GB SSD                       | 2         | 0.64%   |
| SK hynix NVMe SSD Drive 512GB                       | 2         | 0.64%   |
| SK hynix HFM512GD3JX013N 512GB                      | 2         | 0.64%   |
| SK hynix HFM001TD3JX013N 1TB                        | 2         | 0.64%   |
| Seagate ST2000LM015-2E8174 2TB                      | 2         | 0.64%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.64%   |
| SanDisk X400 M.2 2280 128GB SSD                     | 2         | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 2         | 0.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB      | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                        | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 0.64%   |
| Samsung SSD 870 QVO 1TB                             | 2         | 0.64%   |
| Samsung SSD 870 EVO 500GB                           | 2         | 0.64%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 2         | 0.64%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD                | 2         | 0.64%   |
| PNY ELITE PSSD 240GB                                | 2         | 0.64%   |
| Phison E12 NVMe Controller 1TB                      | 2         | 0.64%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 2         | 0.64%   |
| KIOXIA NVMe SSD Drive 512GB                         | 2         | 0.64%   |
| Intel SSDPEKNW010T8 1TB                             | 2         | 0.64%   |
| HGST HTS725050A7E630 500GB                          | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 47     | 47.89%  |
| HGST                | 11        | 11     | 15.49%  |
| WDC                 | 9         | 10     | 12.68%  |
| Toshiba             | 7         | 9      | 9.86%   |
| Hitachi             | 6         | 6      | 8.45%   |
| Unknown             | 1         | 1      | 1.41%   |
| Samsung Electronics | 1         | 1      | 1.41%   |
| SABRENT             | 1         | 2      | 1.41%   |
| ASMT                | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 27     | 26.44%  |
| SanDisk             | 9         | 14     | 10.34%  |
| Crucial             | 8         | 11     | 9.2%    |
| WDC                 | 5         | 6      | 5.75%   |
| SK hynix            | 5         | 6      | 5.75%   |
| Kingston            | 5         | 5      | 5.75%   |
| Micron Technology   | 4         | 5      | 4.6%    |
| SPCC                | 3         | 3      | 3.45%   |
| PNY                 | 3         | 3      | 3.45%   |
| LITEON              | 3         | 3      | 3.45%   |
| Toshiba             | 2         | 2      | 2.3%    |
| China               | 2         | 2      | 2.3%    |
| A-DATA Technology   | 2         | 2      | 2.3%    |
| WODPOSIT            | 1         | 2      | 1.15%   |
| WDC WDS             | 1         | 1      | 1.15%   |
| VisionTek           | 1         | 2      | 1.15%   |
| PNY CS90            | 1         | 1      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| Mushkin             | 1         | 1      | 1.15%   |
| LITEONIT            | 1         | 1      | 1.15%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.15%   |
| JMicron Technology  | 1         | 1      | 1.15%   |
| Intenso             | 1         | 1      | 1.15%   |
| FORESEE             | 1         | 1      | 1.15%   |
| Corsair             | 1         | 1      | 1.15%   |
| Unknown             | 1         | 1      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 111       | 170    | 39.93%  |
| SSD     | 83        | 104    | 29.86%  |
| HDD     | 68        | 88     | 24.46%  |
| MMC     | 12        | 12     | 4.32%   |
| Unknown | 4         | 4      | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 121       | 175    | 46.18%  |
| NVMe | 111       | 170    | 42.37%  |
| SAS  | 18        | 21     | 6.87%   |
| MMC  | 12        | 12     | 4.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 76        | 92     | 51.35%  |
| 0.51-1.0   | 63        | 80     | 42.57%  |
| 1.01-2.0   | 6         | 16     | 4.05%   |
| 3.01-4.0   | 2         | 3      | 1.35%   |
| 4.01-10.0  | 1         | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 81        | 37.16%  |
| 1001-2000      | 44        | 20.18%  |
| 501-1000       | 44        | 20.18%  |
| 2001-3000      | 21        | 9.63%   |
| Unknown        | 11        | 5.05%   |
| 1-20           | 8         | 3.67%   |
| 251-500        | 7         | 3.21%   |
| 101-250        | 2         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 28.19%  |
| 251-500        | 41        | 18.06%  |
| 501-1000       | 35        | 15.42%  |
| 1001-2000      | 29        | 12.78%  |
| 51-100         | 25        | 11.01%  |
| Unknown        | 11        | 4.85%   |
| More than 3000 | 8         | 3.52%   |
| 1-20           | 8         | 3.52%   |
| 2001-3000      | 6         | 2.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 7.14%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 7.14%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 1         | 1      | 7.14%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 7.14%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 7.14%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 980 1TB       | 1         | 6      | 7.14%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 5      | 7.14%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 7.14%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 7.14%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 7.14%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 7.14%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 30.77%  |
| HGST                | 3         | 3      | 23.08%  |
| SK hynix            | 2         | 2      | 15.38%  |
| Hitachi             | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 11     | 7.69%   |

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
| HDD  | 10        | 10     | 76.92%  |
| NVMe | 3         | 13     | 23.08%  |

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
| Works    | 117       | 190    | 49.58%  |
| Detected | 106       | 165    | 44.92%  |
| Malfunc  | 13        | 23     | 5.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 135       | 47.2%   |
| AMD                            | 39        | 13.64%  |
| Samsung Electronics            | 26        | 9.09%   |
| SanDisk                        | 23        | 8.04%   |
| SK hynix                       | 20        | 6.99%   |
| Phison Electronics             | 12        | 4.2%    |
| KIOXIA                         | 5         | 1.75%   |
| Silicon Motion                 | 4         | 1.4%    |
| Micron Technology              | 4         | 1.4%    |
| Kingston Technology Company    | 4         | 1.4%    |
| Union Memory (Shenzhen)        | 3         | 1.05%   |
| Toshiba America Info Systems   | 3         | 1.05%   |
| Micron/Crucial Technology      | 2         | 0.7%    |
| Yangtze Memory Technologies    | 1         | 0.35%   |
| Solid State Storage Technology | 1         | 0.35%   |
| Nvidia                         | 1         | 0.35%   |
| Lenovo                         | 1         | 0.35%   |
| ASMedia Technology             | 1         | 0.35%   |
| ADATA Technology               | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 38        | 12.71%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 6.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 6.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 5.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 4.68%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 10        | 3.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 10        | 3.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 2.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 2.68%   |
| Intel SSD 660P Series                                                          | 7         | 2.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.34%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.01%   |
| Phison E12 NVMe Controller                                                     | 6         | 2.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 2.01%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 5         | 1.67%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 5         | 1.67%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.67%   |
| Intel Non-Volatile memory controller                                           | 5         | 1.67%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.67%   |
| Micron Non-Volatile memory controller                                          | 4         | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.34%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1%      |
| SK hynix Non-Volatile memory controller                                        | 3         | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1%      |
| SanDisk Non-Volatile memory controller                                         | 3         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1%      |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 1%      |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1%      |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.67%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.67%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 140       | 50%     |
| NVMe | 109       | 38.93%  |
| RAID | 28        | 10%     |
| IDE  | 3         | 1.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 145       | 68.72%  |
| AMD    | 66        | 31.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 4.25%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 3.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 3.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 2.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 2.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.89%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.89%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 1.89%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 1.89%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.42%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.42%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 1.42%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 3         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.42%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.94%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.94%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.94%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.94%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.94%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.94%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 0.94%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.94%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 2         | 0.94%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.94%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 0.94%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 2         | 0.94%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 2         | 0.94%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 55        | 26.07%  |
| Intel Core i5           | 39        | 18.48%  |
| AMD Ryzen 7             | 24        | 11.37%  |
| AMD Ryzen 5             | 21        | 9.95%   |
| Other                   | 19        | 9%      |
| Intel Core i3           | 17        | 8.06%   |
| Intel Celeron           | 7         | 3.32%   |
| AMD Ryzen 9             | 4         | 1.9%    |
| AMD A8                  | 4         | 1.9%    |
| Intel Pentium           | 3         | 1.42%   |
| AMD Ryzen 7 PRO         | 3         | 1.42%   |
| Intel Pentium Silver    | 2         | 0.95%   |
| Intel Core 2 Duo        | 2         | 0.95%   |
| AMD Ryzen 3             | 2         | 0.95%   |
| AMD A10                 | 2         | 0.95%   |
| Intel Xeon              | 1         | 0.47%   |
| Intel Pentium Dual-Core | 1         | 0.47%   |
| Intel Core m3           | 1         | 0.47%   |
| AMD Turion              | 1         | 0.47%   |
| AMD FX                  | 1         | 0.47%   |
| AMD A6                  | 1         | 0.47%   |
| AMD A4                  | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 82        | 38.86%  |
| 4      | 62        | 29.38%  |
| 6      | 33        | 15.64%  |
| 8      | 32        | 15.17%  |
| 14     | 2         | 0.95%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 211       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 186       | 88.15%  |
| 1      | 25        | 11.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 211       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 43.84%  |
| 0x0a50000c | 10        | 4.57%   |
| 0x306a9    | 9         | 4.11%   |
| 0x806c1    | 7         | 3.2%    |
| 0xa0652    | 6         | 2.74%   |
| 0x906ea    | 6         | 2.74%   |
| 0x206a7    | 6         | 2.74%   |
| 0x08108109 | 6         | 2.74%   |
| 0x906e9    | 5         | 2.28%   |
| 0x806ea    | 5         | 2.28%   |
| 0x806e9    | 4         | 1.83%   |
| 0x306c3    | 4         | 1.83%   |
| 0x08600106 | 4         | 1.83%   |
| 0x08600103 | 4         | 1.83%   |
| 0x506e3    | 3         | 1.37%   |
| 0x406e3    | 3         | 1.37%   |
| 0x08600104 | 3         | 1.37%   |
| 0x08108102 | 3         | 1.37%   |
| 0x906a3    | 2         | 0.91%   |
| 0x806ec    | 2         | 0.91%   |
| 0x40651    | 2         | 0.91%   |
| 0x106e5    | 2         | 0.91%   |
| 0x0a50000b | 2         | 0.91%   |
| 0x08608103 | 2         | 0.91%   |
| 0x08101007 | 2         | 0.91%   |
| 0x06006705 | 2         | 0.91%   |
| 0xa0660    | 1         | 0.46%   |
| 0x806d1    | 1         | 0.46%   |
| 0x706e5    | 1         | 0.46%   |
| 0x706a8    | 1         | 0.46%   |
| 0x706a1    | 1         | 0.46%   |
| 0x506c9    | 1         | 0.46%   |
| 0x406c4    | 1         | 0.46%   |
| 0x306d4    | 1         | 0.46%   |
| 0x20655    | 1         | 0.46%   |
| 0x20652    | 1         | 0.46%   |
| 0x1067a    | 1         | 0.46%   |
| 0x10676    | 1         | 0.46%   |
| 0x0a404102 | 1         | 0.46%   |
| 0x0a20120a | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 18.87%  |
| Zen 3            | 18        | 8.49%   |
| Zen 2            | 18        | 8.49%   |
| Skylake          | 14        | 6.6%    |
| Zen+             | 13        | 6.13%   |
| IvyBridge        | 13        | 6.13%   |
| Haswell          | 13        | 6.13%   |
| SandyBridge      | 12        | 5.66%   |
| CometLake        | 12        | 5.66%   |
| TigerLake        | 9         | 4.25%   |
| Unknown          | 9         | 4.25%   |
| Broadwell        | 8         | 3.77%   |
| Excavator        | 4         | 1.89%   |
| Puma             | 3         | 1.42%   |
| Penryn           | 3         | 1.42%   |
| IceLake          | 3         | 1.42%   |
| Goldmont plus    | 3         | 1.42%   |
| Zen              | 2         | 0.94%   |
| Westmere         | 2         | 0.94%   |
| Silvermont       | 2         | 0.94%   |
| Piledriver       | 2         | 0.94%   |
| Nehalem          | 2         | 0.94%   |
| Goldmont         | 2         | 0.94%   |
| Alderlake Hybrid | 2         | 0.94%   |
| Steamroller      | 1         | 0.47%   |
| K8 & K10 hybrid  | 1         | 0.47%   |
| Jaguar           | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 44.05%  |
| Nvidia | 102       | 32.8%   |
| AMD    | 72        | 23.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                    | 18        | 5.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 17        | 5.33%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 13        | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 12        | 3.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 12        | 3.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 11        | 3.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 10        | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 9         | 2.82%   |
| Intel UHD Graphics 620                                                        | 9         | 2.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 8         | 2.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 8         | 2.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 2.19%   |
| Intel HD Graphics 620                                                         | 7         | 2.19%   |
| Intel HD Graphics 5500                                                        | 7         | 2.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 7         | 2.19%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 6         | 1.88%   |
| Nvidia TU117M                                                                 | 6         | 1.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 6         | 1.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 6         | 1.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 5         | 1.57%   |
| Intel HD Graphics 630                                                         | 5         | 1.57%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 4         | 1.25%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 4         | 1.25%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 4         | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 3         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 0.94%   |
| Nvidia GM108M [GeForce 840M]                                                  | 3         | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 3         | 0.94%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 3         | 0.94%   |
| Intel HD Graphics 530                                                         | 3         | 0.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 2         | 0.63%   |
| Nvidia GM108M [GeForce MX110]                                                 | 2         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 2         | 0.63%   |
| Nvidia GM108M [GeForce 920MX]                                                 | 2         | 0.63%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 2         | 0.63%   |
| Nvidia GK107GLM [Quadro K1000M]                                               | 2         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 67        | 31.6%   |
| Intel + Nvidia     | 62        | 29.25%  |
| 1 x AMD            | 34        | 16.04%  |
| AMD + Nvidia       | 29        | 13.68%  |
| 1 x Nvidia         | 9         | 4.25%   |
| Intel + AMD        | 6         | 2.83%   |
| 2 x AMD            | 3         | 1.42%   |
| Intel + 2 x Nvidia | 2         | 0.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 137       | 64.02%  |
| Proprietary | 77        | 35.98%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 153       | 69.86%  |
| 0.01-0.5   | 32        | 14.61%  |
| 1.01-2.0   | 15        | 6.85%   |
| 3.01-4.0   | 6         | 2.74%   |
| 5.01-6.0   | 5         | 2.28%   |
| 7.01-8.0   | 4         | 1.83%   |
| 0.51-1.0   | 3         | 1.37%   |
| 8.01-16.0  | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 50        | 19.76%  |
| BOE                     | 37        | 14.62%  |
| LG Display              | 35        | 13.83%  |
| Chimei Innolux          | 33        | 13.04%  |
| Samsung Electronics     | 24        | 9.49%   |
| PANDA                   | 12        | 4.74%   |
| Sharp                   | 11        | 4.35%   |
| Dell                    | 8         | 3.16%   |
| Goldstar                | 6         | 2.37%   |
| Lenovo                  | 5         | 1.98%   |
| InfoVision              | 3         | 1.19%   |
| CSO                     | 3         | 1.19%   |
| Chi Mei Optoelectronics | 3         | 1.19%   |
| Acer                    | 3         | 1.19%   |
| Sony                    | 2         | 0.79%   |
| Philips                 | 2         | 0.79%   |
| Mi                      | 2         | 0.79%   |
| BenQ                    | 2         | 0.79%   |
| Apple                   | 2         | 0.79%   |
| AOC                     | 2         | 0.79%   |
| Vizio                   | 1         | 0.4%    |
| OUT                     | 1         | 0.4%    |
| MStar                   | 1         | 0.4%    |
| Hewlett-Packard         | 1         | 0.4%    |
| G-Story                 | 1         | 0.4%    |
| Eizo                    | 1         | 0.4%    |
| CPT                     | 1         | 0.4%    |
| ASUSTek Computer        | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 1.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 1.58%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 1.19%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 1.19%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.19%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.79%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.79%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 2         | 0.79%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.79%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 2         | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.79%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch      | 2         | 0.79%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 2         | 0.79%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.79%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 0.79%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                 | 2         | 0.79%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch         | 2         | 0.79%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.4%    |
| Sony TV SNYA301 1920x1080                                             | 1         | 0.4%    |
| Sony TV *30 SNYB905 3840x2160 952x535mm 43.0-inch                     | 1         | 0.4%    |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 0.4%    |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.4%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.4%    |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch     | 1         | 0.4%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 131       | 55.27%  |
| 1366x768 (WXGA)    | 42        | 17.72%  |
| 3840x2160 (4K)     | 12        | 5.06%   |
| 1600x900 (HD+)     | 11        | 4.64%   |
| 2560x1440 (QHD)    | 10        | 4.22%   |
| 2560x1600          | 5         | 2.11%   |
| 1920x1200 (WUXGA)  | 4         | 1.69%   |
| 1680x1050 (WSXGA+) | 4         | 1.69%   |
| 3440x1440          | 3         | 1.27%   |
| 2880x1800          | 2         | 0.84%   |
| 1280x800 (WXGA)    | 2         | 0.84%   |
| 3840x2400          | 1         | 0.42%   |
| 3200x1800 (QHD+)   | 1         | 0.42%   |
| 2880x1440          | 1         | 0.42%   |
| 2560x1080          | 1         | 0.42%   |
| 2256x1504          | 1         | 0.42%   |
| 2160x1440          | 1         | 0.42%   |
| 1680x945           | 1         | 0.42%   |
| 1600x1200          | 1         | 0.42%   |
| 1440x900 (WXGA+)   | 1         | 0.42%   |
| 1280x768           | 1         | 0.42%   |
| 1280x720 (HD)      | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 128       | 50.79%  |
| 14      | 32        | 12.7%   |
| 13      | 19        | 7.54%   |
| 17      | 15        | 5.95%   |
| 27      | 9         | 3.57%   |
| 16      | 8         | 3.17%   |
| 21      | 5         | 1.98%   |
| 24      | 4         | 1.59%   |
| 23      | 4         | 1.59%   |
| 34      | 3         | 1.19%   |
| 31      | 3         | 1.19%   |
| 18      | 3         | 1.19%   |
| 43      | 2         | 0.79%   |
| 22      | 2         | 0.79%   |
| 20      | 2         | 0.79%   |
| 11      | 2         | 0.79%   |
| Unknown | 2         | 0.79%   |
| 85      | 1         | 0.4%    |
| 72      | 1         | 0.4%    |
| 54      | 1         | 0.4%    |
| 52      | 1         | 0.4%    |
| 47      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 35      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 12      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 172       | 68.8%   |
| 351-400     | 19        | 7.6%    |
| 501-600     | 17        | 6.8%    |
| 401-500     | 12        | 4.8%    |
| 201-300     | 12        | 4.8%    |
| 601-700     | 4         | 1.6%    |
| 701-800     | 3         | 1.2%    |
| 1001-1500   | 3         | 1.2%    |
| 801-900     | 2         | 0.8%    |
| 1501-2000   | 2         | 0.8%    |
| 901-1000    | 2         | 0.8%    |
| Unknown     | 2         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 196       | 87.5%   |
| 16/10 | 19        | 8.48%   |
| 21/9  | 4         | 1.79%   |
| 4/3   | 2         | 0.89%   |
| 3/2   | 2         | 0.89%   |
| 2.00  | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 131       | 52.19%  |
| 81-90          | 44        | 17.53%  |
| 121-130        | 15        | 5.98%   |
| 201-250        | 14        | 5.58%   |
| 301-350        | 9         | 3.59%   |
| 351-500        | 8         | 3.19%   |
| 71-80          | 6         | 2.39%   |
| More than 1000 | 4         | 1.59%   |
| 501-1000       | 4         | 1.59%   |
| 141-150        | 3         | 1.2%    |
| 111-120        | 3         | 1.2%    |
| 51-60          | 2         | 0.8%    |
| 151-200        | 2         | 0.8%    |
| Unknown        | 2         | 0.8%    |
| 61-70          | 1         | 0.4%    |
| 251-300        | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 131       | 53.04%  |
| 101-120       | 60        | 24.29%  |
| 51-100        | 26        | 10.53%  |
| 161-240       | 15        | 6.07%   |
| More than 240 | 8         | 3.24%   |
| 1-50          | 5         | 2.02%   |
| Unknown       | 2         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 76.15%  |
| 2     | 51        | 23.39%  |
| 0     | 1         | 0.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 124       | 35.94%  |
| Intel                             | 121       | 35.07%  |
| Qualcomm Atheros                  | 47        | 13.62%  |
| Broadcom                          | 15        | 4.35%   |
| MediaTek                          | 10        | 2.9%    |
| Samsung Electronics               | 4         | 1.16%   |
| TP-Link                           | 3         | 0.87%   |
| Ralink Technology                 | 2         | 0.58%   |
| Qualcomm                          | 2         | 0.58%   |
| NetGear                           | 2         | 0.58%   |
| DisplayLink                       | 2         | 0.58%   |
| ASUSTek Computer                  | 2         | 0.58%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.29%   |
| Xiaomi                            | 1         | 0.29%   |
| Wacom                             | 1         | 0.29%   |
| Sierra Wireless                   | 1         | 0.29%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.29%   |
| Nvidia                            | 1         | 0.29%   |
| Motorola PCS                      | 1         | 0.29%   |
| Lenovo                            | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 20.2%   |
| Intel Wi-Fi 6 AX200                                               | 24        | 6.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 2.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 1.77%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.77%   |
| Intel Wireless 7265                                               | 7         | 1.77%   |
| Intel Wireless 7260                                               | 7         | 1.77%   |
| Intel Wireless 3165                                               | 6         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.26%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 1.01%   |
| Intel Wireless 8260                                               | 4         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.76%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 116       | 52.02%  |
| Qualcomm Atheros      | 40        | 17.94%  |
| Realtek Semiconductor | 32        | 14.35%  |
| Broadcom              | 13        | 5.83%   |
| MediaTek              | 10        | 4.48%   |
| TP-Link               | 3         | 1.35%   |
| Ralink Technology     | 2         | 0.9%    |
| NetGear               | 2         | 0.9%    |
| ASUSTek Computer      | 2         | 0.9%    |
| Wacom                 | 1         | 0.45%   |
| Sierra Wireless       | 1         | 0.45%   |
| Dell                  | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 24        | 10.67%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 4.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 4.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 4%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 7         | 3.11%   |
| Intel Wireless 8265 / 8275                                     | 7         | 3.11%   |
| Intel Wireless 7265                                            | 7         | 3.11%   |
| Intel Wireless 7260                                            | 7         | 3.11%   |
| Intel Wireless 3165                                            | 6         | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 2.22%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.78%   |
| Intel Wireless 8260                                            | 4         | 1.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.33%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.89%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 0.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.89%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                       | 1         | 0.44%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                          | 1         | 0.44%   |
| Sierra Wireless EM7455                                         | 1         | 0.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 107       | 63.69%  |
| Intel                      | 31        | 18.45%  |
| Qualcomm Atheros           | 13        | 7.74%   |
| Samsung Electronics        | 4         | 2.38%   |
| Broadcom                   | 4         | 2.38%   |
| Qualcomm                   | 2         | 1.19%   |
| DisplayLink                | 2         | 1.19%   |
| ZTE WCDMA Technologies MSM | 1         | 0.6%    |
| Xiaomi                     | 1         | 0.6%    |
| Nvidia                     | 1         | 0.6%    |
| Lenovo                     | 1         | 0.6%    |
| ASIX Electronics           | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 47.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 2.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 2.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.19%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.19%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.19%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.19%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.19%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.6%    |
| Qualcomm FP3                                                      | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.6%    |
| Qualcomm Android                                                  | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.6%    |
| Lenovo ThinkPad Lan                                               | 1         | 0.6%    |
| Intel I211 Gigabit Network Connection                             | 1         | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.6%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.6%    |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.6%    |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 208       | 56.22%  |
| Ethernet | 159       | 42.97%  |
| Unknown  | 2         | 0.54%   |
| Modem    | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 83.33%  |
| Ethernet | 36        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 145       | 68.4%   |
| 1     | 64        | 30.19%  |
| 3     | 2         | 0.94%   |
| 0     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 72.56%  |
| Yes  | 59        | 27.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 101       | 52.88%  |
| Qualcomm Atheros Communications | 23        | 12.04%  |
| Realtek Semiconductor           | 22        | 11.52%  |
| IMC Networks                    | 11        | 5.76%   |
| Foxconn / Hon Hai               | 9         | 4.71%   |
| Lite-On Technology              | 7         | 3.66%   |
| Broadcom                        | 6         | 3.14%   |
| Hewlett-Packard                 | 2         | 1.05%   |
| Dell                            | 2         | 1.05%   |
| Cambridge Silicon Radio         | 2         | 1.05%   |
| Apple                           | 2         | 1.05%   |
| Realtek                         | 1         | 0.52%   |
| Edimax Technology               | 1         | 0.52%   |
| ASUSTek Computer                | 1         | 0.52%   |
| AboCom Systems                  | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 28        | 14.66%  |
| Intel Bluetooth Device                                                              | 23        | 12.04%  |
| Intel AX200 Bluetooth                                                               | 23        | 12.04%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 7.85%   |
| Realtek Bluetooth Radio                                                             | 11        | 5.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 5.76%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 4.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 3.14%   |
| Intel AX210 Bluetooth                                                               | 5         | 2.62%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 2.62%   |
| Lite-On Bluetooth Device                                                            | 4         | 2.09%   |
| IMC Networks Wireless_Device                                                        | 4         | 2.09%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.09%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.57%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 1.57%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.05%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.52%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.52%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.52%   |
| Lite-On Wireless_Device                                                             | 1         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.52%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.52%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.52%   |
| Edimax Bluetooth Adapter                                                            | 1         | 0.52%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.52%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.52%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.52%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.52%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 51.25%  |
| AMD                   | 66        | 23.49%  |
| Nvidia                | 54        | 19.22%  |
| RODE Microphones      | 2         | 0.71%   |
| Logitech              | 2         | 0.71%   |
| Corsair               | 2         | 0.71%   |
| C-Media Electronics   | 2         | 0.71%   |
| Turtle Beach          | 1         | 0.36%   |
| Sony                  | 1         | 0.36%   |
| Realtek Semiconductor | 1         | 0.36%   |
| Phison Electronics    | 1         | 0.36%   |
| JMTek                 | 1         | 0.36%   |
| Jieli Technology      | 1         | 0.36%   |
| Huawei Technologies   | 1         | 0.36%   |
| GN Netcom             | 1         | 0.36%   |
| DSEA A/S              | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 52        | 14.81%  |
| Intel Sunrise Point-LP HD Audio                                            | 27        | 7.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21        | 5.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 4.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 3.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 3.42%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 3.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10        | 2.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 2.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 2.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 2.28%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 2.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.99%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.71%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 1.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 1.71%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.71%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.71%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.42%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.14%   |
| Nvidia Audio device                                                        | 4         | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.85%   |
| RODE Microphones RODE NT-USB                                               | 2         | 0.57%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.57%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.57%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.57%   |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 0.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 27.87%  |
| SK hynix            | 40        | 21.86%  |
| Micron Technology   | 25        | 13.66%  |
| Crucial             | 15        | 8.2%    |
| Kingston            | 9         | 4.92%   |
| Ramaxel Technology  | 8         | 4.37%   |
| A-DATA Technology   | 6         | 3.28%   |
| Corsair             | 5         | 2.73%   |
| Unknown             | 4         | 2.19%   |
| Smart               | 3         | 1.64%   |
| Nanya Technology    | 3         | 1.64%   |
| Unknown (ABCD)      | 2         | 1.09%   |
| Transcend           | 2         | 1.09%   |
| Timetec             | 1         | 0.55%   |
| Team                | 1         | 0.55%   |
| PNY                 | 1         | 0.55%   |
| Patriot             | 1         | 0.55%   |
| GOODRAM             | 1         | 0.55%   |
| G.Skill             | 1         | 0.55%   |
| Elpida              | 1         | 0.55%   |
| CSX                 | 1         | 0.55%   |
| Avant               | 1         | 0.55%   |
| 48spaces            | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 3.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 3.09%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 2.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.06%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.03%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.03%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.03%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 2         | 1.03%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 1.03%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.03%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.03%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.03%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 2         | 1.03%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.03%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 1.03%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.52%   |
| Transcend RAM JM3200HSG-8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.52%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.52%   |
| Timetec RAM SD4-3200 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.52%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.52%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.52%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.52%   |
| Smart RAM SF4641G8CK8IEGKSBG 8192MB SODIMM DDR4 2400MT/s         | 1         | 0.52%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 97        | 63.82%  |
| DDR3   | 40        | 26.32%  |
| LPDDR4 | 8         | 5.26%   |
| LPDDR3 | 3         | 1.97%   |
| DDR5   | 2         | 1.32%   |
| DDR2   | 2         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 140       | 90.91%  |
| Row Of Chips | 11        | 7.14%   |
| DIMM         | 1         | 0.65%   |
| Chip         | 1         | 0.65%   |
| Unknown      | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 87        | 52.1%   |
| 4096  | 49        | 29.34%  |
| 16384 | 24        | 14.37%  |
| 2048  | 5         | 2.99%   |
| 32768 | 2         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 52        | 31.14%  |
| 2667  | 36        | 21.56%  |
| 1600  | 34        | 20.36%  |
| 2400  | 16        | 9.58%   |
| 1334  | 5         | 2.99%   |
| 4266  | 4         | 2.4%    |
| 2133  | 4         | 2.4%    |
| 3266  | 3         | 1.8%    |
| 4800  | 2         | 1.2%    |
| 1867  | 2         | 1.2%    |
| 1333  | 2         | 1.2%    |
| 667   | 2         | 1.2%    |
| 8400  | 1         | 0.6%    |
| 3733  | 1         | 0.6%    |
| 2933  | 1         | 0.6%    |
| 1866  | 1         | 0.6%    |
| 800   | 1         | 0.6%    |

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
| Chicony Electronics                    | 49        | 25.65%  |
| IMC Networks                           | 26        | 13.61%  |
| Quanta                                 | 14        | 7.33%   |
| Microdia                               | 14        | 7.33%   |
| Realtek Semiconductor                  | 13        | 6.81%   |
| Acer                                   | 13        | 6.81%   |
| Sunplus Innovation Technology          | 11        | 5.76%   |
| Luxvisions Innotech Limited            | 8         | 4.19%   |
| Syntek                                 | 7         | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.14%   |
| Suyin                                  | 5         | 2.62%   |
| Logitech                               | 5         | 2.62%   |
| Silicon Motion                         | 3         | 1.57%   |
| Lite-On Technology                     | 3         | 1.57%   |
| Apple                                  | 3         | 1.57%   |
| Microsoft                              | 2         | 1.05%   |
| WaveRider Communications               | 1         | 0.52%   |
| Sonix Technology                       | 1         | 0.52%   |
| Samsung Electronics                    | 1         | 0.52%   |
| Primax Electronics                     | 1         | 0.52%   |
| Lenovo                                 | 1         | 0.52%   |
| Importek                               | 1         | 0.52%   |
| Genesys Logic                          | 1         | 0.52%   |
| GEMBIRD                                | 1         | 0.52%   |
| Creative Technology                    | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 13        | 6.77%   |
| Chicony HD Webcam                                    | 9         | 4.69%   |
| Microdia Integrated_Webcam_HD                        | 8         | 4.17%   |
| IMC Networks Integrated Camera                       | 8         | 4.17%   |
| Chicony Integrated Camera                            | 7         | 3.65%   |
| Syntek Integrated Camera                             | 5         | 2.6%    |
| Sunplus Integrated_Webcam_HD                         | 5         | 2.6%    |
| Realtek Integrated_Webcam_HD                         | 4         | 2.08%   |
| Quanta HD User Facing                                | 4         | 2.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 2.08%   |
| Chicony HP Wide Vision HD Camera                     | 4         | 2.08%   |
| Chicony HD User Facing                               | 4         | 2.08%   |
| Acer Integrated Camera                               | 4         | 2.08%   |
| Acer HD Webcam                                       | 4         | 2.08%   |
| Quanta HP Wide Vision HD Camera                      | 3         | 1.56%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 1.56%   |
| Logitech HD Pro Webcam C920                          | 3         | 1.56%   |
| Chicony USB2.0 Camera                                | 3         | 1.56%   |
| Silicon Motion Web Camera                            | 2         | 1.04%   |
| Quanta HD Camera                                     | 2         | 1.04%   |
| Microdia Webcam Vitade AF                            | 2         | 1.04%   |
| Lite-On HP Wide Vision HD Camera                     | 2         | 1.04%   |
| IMC Networks HD Camera                               | 2         | 1.04%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.04%   |
| Chicony USB2.0 HD UVC WebCam                         | 2         | 1.04%   |
| Chicony USB 2.0 Camera                               | 2         | 1.04%   |
| Chicony Lenovo EasyCamera                            | 2         | 1.04%   |
| Chicony HP Truevision HD                             | 2         | 1.04%   |
| Chicony EasyCamera                                   | 2         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 2         | 1.04%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 1.04%   |
| WaveRider USB 2.0 Camera                             | 1         | 0.52%   |
| Syntek Lenovo EasyCamera                             | 1         | 0.52%   |
| Syntek EasyCamera                                    | 1         | 0.52%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.52%   |
| Suyin HP TrueVision HD Integrated Webcam             | 1         | 0.52%   |
| Suyin HP Truevision HD                               | 1         | 0.52%   |
| Suyin HD WebCam                                      | 1         | 0.52%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.52%   |
| Sunplus USB Camera                                   | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 33.33%  |
| Elan Microelectronics      | 7         | 19.44%  |
| Synaptics                  | 5         | 13.89%  |
| Shenzhen Goodix Technology | 5         | 13.89%  |
| LighTuning Technology      | 4         | 11.11%  |
| AuthenTec                  | 2         | 5.56%   |
| Focal-systems.Corp         | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                           | 4         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 8.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 8.33%   |
| Elan ELAN:Fingerprint                                                      | 3         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.56%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 5.56%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.78%   |
| Validity Sensors VFS491                                                    | 1         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Synaptics WBDI Device                                                      | 1         | 2.78%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.78%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.78%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.78%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.78%   |
| AuthenTec AES2810                                                          | 1         | 2.78%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.78%   |

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
| 1     | 104       | 48.15%  |
| 0     | 52        | 24.07%  |
| 2     | 50        | 23.15%  |
| 3     | 9         | 4.17%   |
| 4     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 139       | 58.65%  |
| Fingerprint reader       | 36        | 15.19%  |
| Graphics card            | 19        | 8.02%   |
| Chipcard                 | 14        | 5.91%   |
| Net/wireless             | 7         | 2.95%   |
| Multimedia controller    | 7         | 2.95%   |
| Net/ethernet             | 5         | 2.11%   |
| Camera                   | 4         | 1.69%   |
| Storage                  | 3         | 1.27%   |
| Wireless                 | 1         | 0.42%   |
| Network                  | 1         | 0.42%   |
| Bluetooth                | 1         | 0.42%   |

