Linux in Brazil - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 10016

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [4d7f89dc6d](https://linux-hardware.org/?probe=4d7f89dc6d) | Dec 31, 2022 |
| Valve         | Jupiter                     | [97da60caa9](https://linux-hardware.org/?probe=97da60caa9) | Dec 31, 2022 |
| HP            | Folio 13                    | [9f00cfe432](https://linux-hardware.org/?probe=9f00cfe432) | Dec 31, 2022 |
| HP            | Folio 13                    | [3ed5b405cb](https://linux-hardware.org/?probe=3ed5b405cb) | Dec 31, 2022 |
| Unknown       | Unknown                     | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [18827f3f77](https://linux-hardware.org/?probe=18827f3f77) | Dec 31, 2022 |
| Acer          | Predator G3-572             | [ab03199a79](https://linux-hardware.org/?probe=ab03199a79) | Dec 30, 2022 |
| Compaq        | CQ-27                       | [fc5b98e1db](https://linux-hardware.org/?probe=fc5b98e1db) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| HP            | Pavilion dv6                | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| Acer          | Predator G3-572             | [f99480426f](https://linux-hardware.org/?probe=f99480426f) | Dec 29, 2022 |
| Samsung       | 550XBE/350XBE               | [33c4b80d0a](https://linux-hardware.org/?probe=33c4b80d0a) | Dec 29, 2022 |
| Dell          | Inspiron N4050              | [b34f09894d](https://linux-hardware.org/?probe=b34f09894d) | Dec 29, 2022 |
| Dell          | Inspiron 3583               | [35f6da18cc](https://linux-hardware.org/?probe=35f6da18cc) | Dec 29, 2022 |
| HP            | 250 G8 Notebook PC          | [754ba4696d](https://linux-hardware.org/?probe=754ba4696d) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| Acer          | Aspire A515-55              | [296961ae2d](https://linux-hardware.org/?probe=296961ae2d) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| Acer          | Predator PH315-53           | [d5d0e740c1](https://linux-hardware.org/?probe=d5d0e740c1) | Dec 29, 2022 |
| Dell          | G5 5590                     | [58bd69f40b](https://linux-hardware.org/?probe=58bd69f40b) | Dec 28, 2022 |
| Dell          | Inspiron 5458               | [269d455191](https://linux-hardware.org/?probe=269d455191) | Dec 28, 2022 |
| Lenovo        | 100-14IBY 80R7              | [92b2614ac2](https://linux-hardware.org/?probe=92b2614ac2) | Dec 28, 2022 |
| Samsung       | 550XDA                      | [6d744c7602](https://linux-hardware.org/?probe=6d744c7602) | Dec 28, 2022 |
| Samsung       | 550XDA                      | [b463fa7a54](https://linux-hardware.org/?probe=b463fa7a54) | Dec 28, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [5383fb814b](https://linux-hardware.org/?probe=5383fb814b) | Dec 28, 2022 |
| Positivo      | Hendrix                     | [55aa2f92d7](https://linux-hardware.org/?probe=55aa2f92d7) | Dec 27, 2022 |
| Acer          | Aspire E5-574               | [15e48d4c24](https://linux-hardware.org/?probe=15e48d4c24) | Dec 27, 2022 |
| Acer          | Nitro AN515-54              | [5205b7c248](https://linux-hardware.org/?probe=5205b7c248) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | [22540f4247](https://linux-hardware.org/?probe=22540f4247) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | [b47449f70f](https://linux-hardware.org/?probe=b47449f70f) | Dec 27, 2022 |
| Dell          | Inspiron N4050              | [542b5ae2f6](https://linux-hardware.org/?probe=542b5ae2f6) | Dec 27, 2022 |
| Dell          | Vostro 5490                 | [d32b30987a](https://linux-hardware.org/?probe=d32b30987a) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Samsung       | 300E5M/300E5L               | [669e014ee6](https://linux-hardware.org/?probe=669e014ee6) | Dec 27, 2022 |
| Dell          | Inspiron 15-3567            | [2f5381fa26](https://linux-hardware.org/?probe=2f5381fa26) | Dec 26, 2022 |
| Dell          | Inspiron 7580               | [a1638729b2](https://linux-hardware.org/?probe=a1638729b2) | Dec 26, 2022 |
| Dell          | Vostro 5490                 | [97677e7c79](https://linux-hardware.org/?probe=97677e7c79) | Dec 26, 2022 |
| Dell          | Inspiron 5458               | [4e393c7334](https://linux-hardware.org/?probe=4e393c7334) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | SVF15213CBB                 | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
| HP            | ProBook 6465b               | [d0f5218f72](https://linux-hardware.org/?probe=d0f5218f72) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| Toshiba       | PORTEGE Z930                | [4a77067c41](https://linux-hardware.org/?probe=4a77067c41) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [ccd5d4bac3](https://linux-hardware.org/?probe=ccd5d4bac3) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| HP            | Pavilion g4                 | [a5d26c4498](https://linux-hardware.org/?probe=a5d26c4498) | Dec 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c95a4418f0](https://linux-hardware.org/?probe=c95a4418f0) | Dec 24, 2022 |
| Dell          | Vostro 3500                 | [0d59e2b098](https://linux-hardware.org/?probe=0d59e2b098) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [28b89e2321](https://linux-hardware.org/?probe=28b89e2321) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Dell          | XPS L322X                   | [c127721464](https://linux-hardware.org/?probe=c127721464) | Dec 24, 2022 |
| Samsung       | RF511/RF411/RF711           | [b0a9f1ed91](https://linux-hardware.org/?probe=b0a9f1ed91) | Dec 24, 2022 |
| Valve         | Jupiter                     | [a38f241e2e](https://linux-hardware.org/?probe=a38f241e2e) | Dec 24, 2022 |
| Acer          | Aspire A514-54              | [ea57f4aa3a](https://linux-hardware.org/?probe=ea57f4aa3a) | Dec 24, 2022 |
| Samsung       | 550XBE/350XBE               | [4ea620705d](https://linux-hardware.org/?probe=4ea620705d) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Positivo      | Mobile                      | [6031910e64](https://linux-hardware.org/?probe=6031910e64) | Dec 24, 2022 |
| Avell High... | B.ON                        | [ea8a4babbf](https://linux-hardware.org/?probe=ea8a4babbf) | Dec 24, 2022 |
| Dell          | Latitude 5420               | [201e81d0ed](https://linux-hardware.org/?probe=201e81d0ed) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Positivo      | H14BT58                     | [9914219613](https://linux-hardware.org/?probe=9914219613) | Dec 23, 2022 |
| Chuwi         | HeroBook Air                | [8f4eea6be8](https://linux-hardware.org/?probe=8f4eea6be8) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [6b2cd55178](https://linux-hardware.org/?probe=6b2cd55178) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Dell          | G3 3590                     | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | [22eafd12e4](https://linux-hardware.org/?probe=22eafd12e4) | Dec 23, 2022 |
| Acer          | Aspire M5-481T              | [f250052dff](https://linux-hardware.org/?probe=f250052dff) | Dec 23, 2022 |
| Positivo      | C4128E-S                    | [2fce43e57f](https://linux-hardware.org/?probe=2fce43e57f) | Dec 23, 2022 |
| Samsung       | 270E5J/2570EJ               | [7efb2defb9](https://linux-hardware.org/?probe=7efb2defb9) | Dec 23, 2022 |
| Acer          | Nitro AN515-51              | [9dca0f7674](https://linux-hardware.org/?probe=9dca0f7674) | Dec 22, 2022 |
| Dell          | Vostro 5490                 | [2d85a576e1](https://linux-hardware.org/?probe=2d85a576e1) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [37f100cf13](https://linux-hardware.org/?probe=37f100cf13) | Dec 22, 2022 |
| Dell          | Inspiron 5590               | [4e4cf63a0a](https://linux-hardware.org/?probe=4e4cf63a0a) | Dec 22, 2022 |
| Acer          | Nitro AN517-54              | [08539171a8](https://linux-hardware.org/?probe=08539171a8) | Dec 22, 2022 |
| Dell          | System XPS L502X            | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Positivo      | S14SL01                     | [476e8a784c](https://linux-hardware.org/?probe=476e8a784c) | Dec 21, 2022 |
| Positivo      | S14SL01                     | [08e3a4d7f2](https://linux-hardware.org/?probe=08e3a4d7f2) | Dec 21, 2022 |
| ASUSTek       | X450CA                      | [5b793f14ff](https://linux-hardware.org/?probe=5b793f14ff) | Dec 21, 2022 |
| Multilaser    | MLSH1H LINUX                | [70695e9f3b](https://linux-hardware.org/?probe=70695e9f3b) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [77c9275988](https://linux-hardware.org/?probe=77c9275988) | Dec 21, 2022 |
| Positivo      | C14CR21                     | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [ec20f98178](https://linux-hardware.org/?probe=ec20f98178) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Dell          | Latitude 3420               | [99d501d768](https://linux-hardware.org/?probe=99d501d768) | Dec 20, 2022 |
| Samsung       | 300E5M/300E5L               | [4c6ab7c16e](https://linux-hardware.org/?probe=4c6ab7c16e) | Dec 20, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [383b0f3311](https://linux-hardware.org/?probe=383b0f3311) | Dec 20, 2022 |
| Positivo      | Master N8340                | [643f2e00e0](https://linux-hardware.org/?probe=643f2e00e0) | Dec 20, 2022 |
| Dell          | Inspiron 15 5510            | [e1d9b06871](https://linux-hardware.org/?probe=e1d9b06871) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Acer          | Extensa 5230                | [0cfe897a2b](https://linux-hardware.org/?probe=0cfe897a2b) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Multilaser    | UB23X LINUX                 | [9f7503d89d](https://linux-hardware.org/?probe=9f7503d89d) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [751834957d](https://linux-hardware.org/?probe=751834957d) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Multilaser    | UB23X LINUX                 | [502d9cd6ce](https://linux-hardware.org/?probe=502d9cd6ce) | Dec 19, 2022 |
| Sony          | VPCEA23FB                   | [a374bedbed](https://linux-hardware.org/?probe=a374bedbed) | Dec 19, 2022 |
| Acer          | Extensa 5230                | [dfe70c9fdc](https://linux-hardware.org/?probe=dfe70c9fdc) | Dec 19, 2022 |
| HP            | ProBook 4530s               | [2c6a27a08d](https://linux-hardware.org/?probe=2c6a27a08d) | Dec 19, 2022 |
| HP            | ProBook 4530s               | [19892439d6](https://linux-hardware.org/?probe=19892439d6) | Dec 19, 2022 |
| Acer          | Nitro AN515-54              | [5254697dbb](https://linux-hardware.org/?probe=5254697dbb) | Dec 19, 2022 |
| Alienware     | m15 R7                      | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| ASUSTek       | X451CAP                     | [358fa50e0c](https://linux-hardware.org/?probe=358fa50e0c) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b1655d054](https://linux-hardware.org/?probe=7b1655d054) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [07ae580adc](https://linux-hardware.org/?probe=07ae580adc) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Gateway       | NV55C                       | [150f4e3dbc](https://linux-hardware.org/?probe=150f4e3dbc) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c0150b6ae](https://linux-hardware.org/?probe=5c0150b6ae) | Dec 17, 2022 |
| Samsung       | RV415/RV515                 | [dcf4e8200b](https://linux-hardware.org/?probe=dcf4e8200b) | Dec 17, 2022 |
| Sony          | VPCCW21FX                   | [9d82e3655b](https://linux-hardware.org/?probe=9d82e3655b) | Dec 17, 2022 |
| Avell High... | B.ON                        | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| Dell          | Inspiron 5547               | [9dede41c5d](https://linux-hardware.org/?probe=9dede41c5d) | Dec 17, 2022 |
| Dell          | Inspiron 3583               | [5629961182](https://linux-hardware.org/?probe=5629961182) | Dec 17, 2022 |
| Apple         | MacBookPro8,1               | [a30cdfc558](https://linux-hardware.org/?probe=a30cdfc558) | Dec 16, 2022 |
| Digibras      | US41II1                     | [6b1d584ff8](https://linux-hardware.org/?probe=6b1d584ff8) | Dec 16, 2022 |
| Chuwi         | HeroBook Air                | [6da143680b](https://linux-hardware.org/?probe=6da143680b) | Dec 16, 2022 |
| Dell          | Inspiron 5458               | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| Dell          | Latitude 5480               | [43e6598fd7](https://linux-hardware.org/?probe=43e6598fd7) | Dec 16, 2022 |
| Dell          | Inspiron 5566               | [ccfc358303](https://linux-hardware.org/?probe=ccfc358303) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0f73c873b1](https://linux-hardware.org/?probe=0f73c873b1) | Dec 16, 2022 |
| Toshiba       | IS 1442                     | [c028a09103](https://linux-hardware.org/?probe=c028a09103) | Dec 15, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [87f99a0bb2](https://linux-hardware.org/?probe=87f99a0bb2) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0da6ba8094](https://linux-hardware.org/?probe=0da6ba8094) | Dec 15, 2022 |
| Avell High... | A60 MUV                     | [204d35bad7](https://linux-hardware.org/?probe=204d35bad7) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f5a317963c](https://linux-hardware.org/?probe=f5a317963c) | Dec 15, 2022 |
| Dell          | G15 5511                    | [8454bbb59e](https://linux-hardware.org/?probe=8454bbb59e) | Dec 15, 2022 |
| Acer          | Nitro AN517-51              | [a621dbb00e](https://linux-hardware.org/?probe=a621dbb00e) | Dec 15, 2022 |
| Lenovo        | ThinkPad X230 23245QP       | [e525a77c95](https://linux-hardware.org/?probe=e525a77c95) | Dec 15, 2022 |
| Lenovo        | G460 20041                  | [b76fa704f7](https://linux-hardware.org/?probe=b76fa704f7) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| Dell          | Inspiron 5584               | [274fa56da6](https://linux-hardware.org/?probe=274fa56da6) | Dec 13, 2022 |
| Acer          | Aspire A514-54              | [6aa836cfc6](https://linux-hardware.org/?probe=6aa836cfc6) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [726380956e](https://linux-hardware.org/?probe=726380956e) | Dec 13, 2022 |
| Apple         | MacBookPro8,2               | [05ef133104](https://linux-hardware.org/?probe=05ef133104) | Dec 12, 2022 |
| Positivo B... | VJFE44F11X-B2111H           | [903b25c77f](https://linux-hardware.org/?probe=903b25c77f) | Dec 12, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [304bad9c19](https://linux-hardware.org/?probe=304bad9c19) | Dec 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ce1ae34933](https://linux-hardware.org/?probe=ce1ae34933) | Dec 12, 2022 |
| Dell          | Inspiron 15 3511            | [db4a92dae2](https://linux-hardware.org/?probe=db4a92dae2) | Dec 11, 2022 |
| Dell          | Inspiron 1545               | [31ad9ff6a7](https://linux-hardware.org/?probe=31ad9ff6a7) | Dec 10, 2022 |
| Dell          | Inspiron 1545               | [f147df85e6](https://linux-hardware.org/?probe=f147df85e6) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [e80dfca4a8](https://linux-hardware.org/?probe=e80dfca4a8) | Dec 10, 2022 |
| Acer          | Predator PH315-52           | [72f0e70b26](https://linux-hardware.org/?probe=72f0e70b26) | Dec 10, 2022 |
| Samsung       | 270E5K                      | [9164b7d324](https://linux-hardware.org/?probe=9164b7d324) | Dec 09, 2022 |
| Dell          | Inspiron 3583               | [93934b74f5](https://linux-hardware.org/?probe=93934b74f5) | Dec 09, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [63e4c154a2](https://linux-hardware.org/?probe=63e4c154a2) | Dec 09, 2022 |
| Positivo      | Mobile                      | [bc5f4e6c85](https://linux-hardware.org/?probe=bc5f4e6c85) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| Dell          | Latitude 3400               | [d01726a4d0](https://linux-hardware.org/?probe=d01726a4d0) | Dec 08, 2022 |
| Digibras      | US41II1                     | [b4651a173e](https://linux-hardware.org/?probe=b4651a173e) | Dec 08, 2022 |
| Dell          | Inspiron 5566               | [dcf5539e74](https://linux-hardware.org/?probe=dcf5539e74) | Dec 08, 2022 |
| Notebook      | NJx0MU                      | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | [00995baaae](https://linux-hardware.org/?probe=00995baaae) | Dec 07, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [8575adb47e](https://linux-hardware.org/?probe=8575adb47e) | Dec 07, 2022 |
| Digibras      | US41II1                     | [eafbffa1b4](https://linux-hardware.org/?probe=eafbffa1b4) | Dec 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [db53a5df72](https://linux-hardware.org/?probe=db53a5df72) | Dec 07, 2022 |
| Positivo      | H14BT58                     | [c038df5c8c](https://linux-hardware.org/?probe=c038df5c8c) | Dec 07, 2022 |
| Dell          | Latitude E6420              | [e87ced9ea4](https://linux-hardware.org/?probe=e87ced9ea4) | Dec 06, 2022 |
| Dell          | Latitude E6420              | [17c9263444](https://linux-hardware.org/?probe=17c9263444) | Dec 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [87d3ead3ba](https://linux-hardware.org/?probe=87d3ead3ba) | Dec 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4eaf92f82b](https://linux-hardware.org/?probe=4eaf92f82b) | Dec 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [abe6a39746](https://linux-hardware.org/?probe=abe6a39746) | Dec 06, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| Acer          | Aspire F5-573               | [c5f8c3ee20](https://linux-hardware.org/?probe=c5f8c3ee20) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0e42e5cbeb](https://linux-hardware.org/?probe=0e42e5cbeb) | Dec 06, 2022 |
| Acer          | Aspire A515-56              | [9cb1b48840](https://linux-hardware.org/?probe=9cb1b48840) | Dec 05, 2022 |
| Acer          | Aspire A515-56              | [5108572656](https://linux-hardware.org/?probe=5108572656) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Dell          | Vostro 1310                 | [60bdc28f50](https://linux-hardware.org/?probe=60bdc28f50) | Dec 04, 2022 |
| Acer          | Aspire 5750                 | [bfe28498bd](https://linux-hardware.org/?probe=bfe28498bd) | Dec 04, 2022 |
| Dell          | Inspiron 5566               | [fb9c1854a2](https://linux-hardware.org/?probe=fb9c1854a2) | Dec 04, 2022 |
| Acer          | Aspire A515-45              | [48d98f5da4](https://linux-hardware.org/?probe=48d98f5da4) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [05ae64c1b8](https://linux-hardware.org/?probe=05ae64c1b8) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [ae6745045a](https://linux-hardware.org/?probe=ae6745045a) | Dec 04, 2022 |
| Samsung       | 270E5J/2570EJ               | [084c39f0b7](https://linux-hardware.org/?probe=084c39f0b7) | Dec 04, 2022 |
| Acer          | Swift SF514-56T             | [07e72975a2](https://linux-hardware.org/?probe=07e72975a2) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [d64c6bc6f4](https://linux-hardware.org/?probe=d64c6bc6f4) | Dec 03, 2022 |
| Dell          | Inspiron 5567               | [a9f812a233](https://linux-hardware.org/?probe=a9f812a233) | Dec 03, 2022 |
| Sony          | SVE14A18ECH                 | [4ea36d0512](https://linux-hardware.org/?probe=4ea36d0512) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Acer          | Aspire A515-54G             | [0bcc1e2664](https://linux-hardware.org/?probe=0bcc1e2664) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2bde4950e9](https://linux-hardware.org/?probe=2bde4950e9) | Dec 02, 2022 |
| Acer          | Aspire A515-45              | [495abda40a](https://linux-hardware.org/?probe=495abda40a) | Dec 02, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ae8f8361c1](https://linux-hardware.org/?probe=ae8f8361c1) | Dec 02, 2022 |
| Positivo B... | VJFE53F11X-B0511H           | [24b1be97d6](https://linux-hardware.org/?probe=24b1be97d6) | Dec 01, 2022 |
| Positivo B... | VJFE53F11X-B0511H           | [a2e91cba31](https://linux-hardware.org/?probe=a2e91cba31) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Samsung       | 300E5K/300E5Q               | [f6bb652f5a](https://linux-hardware.org/?probe=f6bb652f5a) | Nov 30, 2022 |
| Samsung       | 550XDA                      | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [d95adc01a7](https://linux-hardware.org/?probe=d95adc01a7) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Philco        | 14H                         | [8d29065667](https://linux-hardware.org/?probe=8d29065667) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Positivo B... | S14SL03                     | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| Dell          | Vostro 5470                 | [15c504a6ef](https://linux-hardware.org/?probe=15c504a6ef) | Nov 29, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [adb0404576](https://linux-hardware.org/?probe=adb0404576) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Acer          | TravelMate B113             | [567c2d2e20](https://linux-hardware.org/?probe=567c2d2e20) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Dell          | G15 5520                    | [251078d1b4](https://linux-hardware.org/?probe=251078d1b4) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [ab9e6cc193](https://linux-hardware.org/?probe=ab9e6cc193) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [a4d6ce5fa1](https://linux-hardware.org/?probe=a4d6ce5fa1) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | [99e1d10484](https://linux-hardware.org/?probe=99e1d10484) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | [7d3bf460f7](https://linux-hardware.org/?probe=7d3bf460f7) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [c41d8da6ac](https://linux-hardware.org/?probe=c41d8da6ac) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [47d9a5f1ca](https://linux-hardware.org/?probe=47d9a5f1ca) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | [5d324af4d0](https://linux-hardware.org/?probe=5d324af4d0) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c3e10b2149](https://linux-hardware.org/?probe=c3e10b2149) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [cd5eb0566d](https://linux-hardware.org/?probe=cd5eb0566d) | Nov 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [3e969e8aa0](https://linux-hardware.org/?probe=3e969e8aa0) | Nov 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2965050f1a](https://linux-hardware.org/?probe=2965050f1a) | Nov 25, 2022 |
| ASUSTek       | Z450LA                      | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| Notebook      | NJx0MU                      | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| Acer          | Nitro AN515-52              | [c639db74cb](https://linux-hardware.org/?probe=c639db74cb) | Nov 25, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| Avell High... | STORM TWO                   | [d8a406b26c](https://linux-hardware.org/?probe=d8a406b26c) | Nov 24, 2022 |
| Sony          | VPCEA23FB                   | [187f57793d](https://linux-hardware.org/?probe=187f57793d) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47116ddd3e](https://linux-hardware.org/?probe=47116ddd3e) | Nov 24, 2022 |
| Toshiba       | IS 1442                     | [8a2d7b5a48](https://linux-hardware.org/?probe=8a2d7b5a48) | Nov 23, 2022 |
| Notebook      | NJx0MU                      | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Dell          | System Vostro 3460          | [4f9fb6602d](https://linux-hardware.org/?probe=4f9fb6602d) | Nov 23, 2022 |
| Samsung       | 270E5K                      | [871e23c67c](https://linux-hardware.org/?probe=871e23c67c) | Nov 23, 2022 |
| Samsung       | 270E5K                      | [398893bbd1](https://linux-hardware.org/?probe=398893bbd1) | Nov 23, 2022 |
| Positivo      | Mobile                      | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [0fd3b230e0](https://linux-hardware.org/?probe=0fd3b230e0) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Acer          | Aspire E5-574G              | [703b6ee54d](https://linux-hardware.org/?probe=703b6ee54d) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| Acer          | Nitro AN515-52              | [57b2e84560](https://linux-hardware.org/?probe=57b2e84560) | Nov 22, 2022 |
| Dell          | Latitude 5480               | [5b9f1e717c](https://linux-hardware.org/?probe=5b9f1e717c) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Dell          | Inspiron 5548               | [8d8a193e7b](https://linux-hardware.org/?probe=8d8a193e7b) | Nov 21, 2022 |
| Dell          | Inspiron 3442               | [d9678fb5a7](https://linux-hardware.org/?probe=d9678fb5a7) | Nov 21, 2022 |
| Acer          | Nitro AN515-52              | [308968646b](https://linux-hardware.org/?probe=308968646b) | Nov 21, 2022 |
| Toshiba       | IS 1422                     | [aa59e6576d](https://linux-hardware.org/?probe=aa59e6576d) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | [aa4d9601ee](https://linux-hardware.org/?probe=aa4d9601ee) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [5739045caa](https://linux-hardware.org/?probe=5739045caa) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Acer          | Aspire A515-45              | [11e00d597d](https://linux-hardware.org/?probe=11e00d597d) | Nov 20, 2022 |
| Acer          | Nitro AN515-44              | [c6b85f956a](https://linux-hardware.org/?probe=c6b85f956a) | Nov 20, 2022 |
| Acer          | Aspire E1-571               | [35fc3411ec](https://linux-hardware.org/?probe=35fc3411ec) | Nov 20, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [1253590f60](https://linux-hardware.org/?probe=1253590f60) | Nov 20, 2022 |
| Samsung       | 767XCL                      | [729f4f303e](https://linux-hardware.org/?probe=729f4f303e) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e777561ba5](https://linux-hardware.org/?probe=e777561ba5) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [496647cddb](https://linux-hardware.org/?probe=496647cddb) | Nov 19, 2022 |
| Dell          | Inspiron 15-3567            | [5d6f9e57c5](https://linux-hardware.org/?probe=5d6f9e57c5) | Nov 19, 2022 |
| Dell          | Vostro 3501                 | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [1d527a6849](https://linux-hardware.org/?probe=1d527a6849) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| HP            | Presario CQ43               | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [f796cfccaa](https://linux-hardware.org/?probe=f796cfccaa) | Nov 17, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [873552cfae](https://linux-hardware.org/?probe=873552cfae) | Nov 17, 2022 |
| Compaq        | 420                         | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | [7d7f4061fa](https://linux-hardware.org/?probe=7d7f4061fa) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | [d36317c3be](https://linux-hardware.org/?probe=d36317c3be) | Nov 17, 2022 |
| Dell          | G15 5510                    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [7aa6773734](https://linux-hardware.org/?probe=7aa6773734) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [d5c4a2f02e](https://linux-hardware.org/?probe=d5c4a2f02e) | Nov 16, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Dell          | Inspiron 3583               | [1dc59dc45d](https://linux-hardware.org/?probe=1dc59dc45d) | Nov 16, 2022 |
| Sony          | SVE14A15FBB                 | [1b368520d1](https://linux-hardware.org/?probe=1b368520d1) | Nov 16, 2022 |
| Positivo B... | VJFE44F11X-B2111H           | [070af1bd42](https://linux-hardware.org/?probe=070af1bd42) | Nov 16, 2022 |
| Notebook      | NJx0MU                      | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Acer          | Aspire E5-571               | [3e04c315ee](https://linux-hardware.org/?probe=3e04c315ee) | Nov 15, 2022 |
| Daten Tecn... | DT02-M4                     | [783a9a5607](https://linux-hardware.org/?probe=783a9a5607) | Nov 15, 2022 |
| Gateway       | NV55C                       | [64d8e467d4](https://linux-hardware.org/?probe=64d8e467d4) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [a21cf96dd6](https://linux-hardware.org/?probe=a21cf96dd6) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | [14e272fe11](https://linux-hardware.org/?probe=14e272fe11) | Nov 15, 2022 |
| Samsung       | RV411                       | [ded212573f](https://linux-hardware.org/?probe=ded212573f) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | [c6b6ee8cc8](https://linux-hardware.org/?probe=c6b6ee8cc8) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | [e751f32d49](https://linux-hardware.org/?probe=e751f32d49) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Lenovo        | G50-80 80R0                 | [35193d2431](https://linux-hardware.org/?probe=35193d2431) | Nov 14, 2022 |
| Dell          | Vostro 5470                 | [5b542891b7](https://linux-hardware.org/?probe=5b542891b7) | Nov 14, 2022 |
| Multilaser    | PC121                       | [5870f0d565](https://linux-hardware.org/?probe=5870f0d565) | Nov 14, 2022 |
| Acer          | Nitro AN517-54              | [b5c1404ef7](https://linux-hardware.org/?probe=b5c1404ef7) | Nov 13, 2022 |
| Dell          | G15 5510                    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| Google        | Celes                       | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Standard      | MB40II                      | [c95529c90a](https://linux-hardware.org/?probe=c95529c90a) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | [d3b618e418](https://linux-hardware.org/?probe=d3b618e418) | Nov 12, 2022 |
| Apple         | MacBookPro6,2               | [3c63d3fb1e](https://linux-hardware.org/?probe=3c63d3fb1e) | Nov 11, 2022 |
| Notebook      | NJx0MU                      | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| LG Electro... | 15Z970-E.BH91P1             | [347940efc3](https://linux-hardware.org/?probe=347940efc3) | Nov 11, 2022 |
| Toshiba       | IS 1422+                    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [fb2b32db6a](https://linux-hardware.org/?probe=fb2b32db6a) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Acer          | Aspire 5742                 | [9c688c611e](https://linux-hardware.org/?probe=9c688c611e) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| HP            | Pavilion dv2700             | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [63b53e81ed](https://linux-hardware.org/?probe=63b53e81ed) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [22b8b36df5](https://linux-hardware.org/?probe=22b8b36df5) | Nov 08, 2022 |
| Alienware     | m15 R6                      | [3e808157a3](https://linux-hardware.org/?probe=3e808157a3) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a4bce0a93a](https://linux-hardware.org/?probe=a4bce0a93a) | Nov 07, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [589354a449](https://linux-hardware.org/?probe=589354a449) | Nov 07, 2022 |
| Dell          | Latitude 3410               | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [c2f8bf4caf](https://linux-hardware.org/?probe=c2f8bf4caf) | Nov 07, 2022 |
| ASUSTek       | K52Jr                       | [7be3408f46](https://linux-hardware.org/?probe=7be3408f46) | Nov 07, 2022 |
| Lenovo        | G475 20080                  | [f0f78f8e7e](https://linux-hardware.org/?probe=f0f78f8e7e) | Nov 07, 2022 |
| Acer          | Aspire 5742                 | [028e3c3f64](https://linux-hardware.org/?probe=028e3c3f64) | Nov 06, 2022 |
| Samsung       | 550XDA                      | [a57a40964e](https://linux-hardware.org/?probe=a57a40964e) | Nov 06, 2022 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [5afc3788fc](https://linux-hardware.org/?probe=5afc3788fc) | Nov 06, 2022 |
| Quanta        | TWS                         | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Positivo      | W940TU                      | [ad13b613fa](https://linux-hardware.org/?probe=ad13b613fa) | Nov 06, 2022 |
| Quanta        | TWS                         | [a800f54191](https://linux-hardware.org/?probe=a800f54191) | Nov 06, 2022 |
| Positivo      | W940TU                      | [ee23486fc7](https://linux-hardware.org/?probe=ee23486fc7) | Nov 06, 2022 |
| Acer          | Nitro AN515-44              | [91851e068d](https://linux-hardware.org/?probe=91851e068d) | Nov 06, 2022 |
| Dell          | Inspiron 15-3552            | [f72391a03b](https://linux-hardware.org/?probe=f72391a03b) | Nov 05, 2022 |
| Dell          | Inspiron 5402               | [109f44c580](https://linux-hardware.org/?probe=109f44c580) | Nov 05, 2022 |
| Samsung       | 270E5J/2570EJ               | [1466580b6e](https://linux-hardware.org/?probe=1466580b6e) | Nov 05, 2022 |
| Dell          | Vostro 13 5310              | [c25e192969](https://linux-hardware.org/?probe=c25e192969) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| Dell          | Inspiron 11-3168            | [71fac7ca47](https://linux-hardware.org/?probe=71fac7ca47) | Nov 05, 2022 |
| Toshiba       | IS 1422                     | [2ea67b9fac](https://linux-hardware.org/?probe=2ea67b9fac) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| Acer          | Nitro AN515-44              | [03176fa010](https://linux-hardware.org/?probe=03176fa010) | Nov 04, 2022 |
| Dell          | G15 5511                    | [68f1e6d4f0](https://linux-hardware.org/?probe=68f1e6d4f0) | Nov 04, 2022 |
| Sony          | VPCEA23FB                   | [ff50b0dd2a](https://linux-hardware.org/?probe=ff50b0dd2a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| Sony          | VPCEB4L1E                   | [5448ca63bc](https://linux-hardware.org/?probe=5448ca63bc) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 14S           | [9fbf084c28](https://linux-hardware.org/?probe=9fbf084c28) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Avell High... | B.ON                        | [f0ea745f7d](https://linux-hardware.org/?probe=f0ea745f7d) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| Intel         | powered classmate PC        | [5e9392864a](https://linux-hardware.org/?probe=5e9392864a) | Nov 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [43609f5bd5](https://linux-hardware.org/?probe=43609f5bd5) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| Positivo      | Mobile                      | [f35235fdfa](https://linux-hardware.org/?probe=f35235fdfa) | Nov 03, 2022 |
| Positivo      | Mobile                      | [581c79bdee](https://linux-hardware.org/?probe=581c79bdee) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | [cdd5c3cca0](https://linux-hardware.org/?probe=cdd5c3cca0) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | [7d43f3c00b](https://linux-hardware.org/?probe=7d43f3c00b) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| Samsung       | 550P5C/550P7C               | [39cb4cb083](https://linux-hardware.org/?probe=39cb4cb083) | Nov 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | [09c2704bb0](https://linux-hardware.org/?probe=09c2704bb0) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| HP            | Pavilion 15                 | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Samsung       | 800G5M/800G5W               | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [973fc77891](https://linux-hardware.org/?probe=973fc77891) | Oct 31, 2022 |
| LG Electro... | A560-T.BG77P1               | [cad4120a42](https://linux-hardware.org/?probe=cad4120a42) | Oct 31, 2022 |
| Avell High... | B.ON                        | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c8970ae94a](https://linux-hardware.org/?probe=c8970ae94a) | Oct 31, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Samsung       | 800G5M/800G5W               | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| Dell          | Precision 5750              | [9b9addd3b7](https://linux-hardware.org/?probe=9b9addd3b7) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| Samsung       | 670Z5E                      | [159f89858c](https://linux-hardware.org/?probe=159f89858c) | Oct 28, 2022 |
| Avell High... | B.ON                        | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Samsung       | 275E4E/275E5E               | [d3aebcbac6](https://linux-hardware.org/?probe=d3aebcbac6) | Oct 27, 2022 |
| Lenovo        | Unknown                     | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [fe1166a134](https://linux-hardware.org/?probe=fe1166a134) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [b35b1298a8](https://linux-hardware.org/?probe=b35b1298a8) | Oct 27, 2022 |
| Acer          | Aspire A315-54              | [6de38f7802](https://linux-hardware.org/?probe=6de38f7802) | Oct 27, 2022 |
| Acer          | Nitro AN515-44              | [189ac65e5b](https://linux-hardware.org/?probe=189ac65e5b) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Dell          | Inspiron 5402               | [a7a8cc4cff](https://linux-hardware.org/?probe=a7a8cc4cff) | Oct 27, 2022 |
| Avell High... | A60 MUV                     | [ccdf105523](https://linux-hardware.org/?probe=ccdf105523) | Oct 26, 2022 |
| Sony          | VPCEA23FB                   | [1b9688e23f](https://linux-hardware.org/?probe=1b9688e23f) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | [a0adbfd7fe](https://linux-hardware.org/?probe=a0adbfd7fe) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | [519384ee8a](https://linux-hardware.org/?probe=519384ee8a) | Oct 26, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [562c9438d1](https://linux-hardware.org/?probe=562c9438d1) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | G40-80 80JE                 | [97dfa18602](https://linux-hardware.org/?probe=97dfa18602) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Acer          | Nitro AN515-43              | [9a9880cc6a](https://linux-hardware.org/?probe=9a9880cc6a) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | S500CA                      | [bc57450141](https://linux-hardware.org/?probe=bc57450141) | Oct 24, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [edfb470814](https://linux-hardware.org/?probe=edfb470814) | Oct 23, 2022 |
| Acer          | Aspire A315-53              | [5388646329](https://linux-hardware.org/?probe=5388646329) | Oct 23, 2022 |
| Dell          | Inspiron 3576               | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| Avell High... | C62 MOB                     | [3baeb7ee26](https://linux-hardware.org/?probe=3baeb7ee26) | Oct 22, 2022 |
| Acer          | Aspire A315-53              | [72f0c231fb](https://linux-hardware.org/?probe=72f0c231fb) | Oct 21, 2022 |
| Positivo      | S14CT01                     | [1a5f77c8f9](https://linux-hardware.org/?probe=1a5f77c8f9) | Oct 21, 2022 |
| Microboard    | Cantiga & ICH9M Chipset     | [1fffce3846](https://linux-hardware.org/?probe=1fffce3846) | Oct 21, 2022 |
| Avell High... | B.ON                        | [17ce0979b3](https://linux-hardware.org/?probe=17ce0979b3) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Dell          | Latitude E5410              | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| Positivo      | C4120F                      | [92338290da](https://linux-hardware.org/?probe=92338290da) | Oct 20, 2022 |
| Acer          | Aspire E5-574               | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Samsung       | 550XDA                      | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| Samsung       | 270E5J/2570EJ               | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| Lenovo        | G480                        | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| Avell High... | B.ON                        | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Teclast       | F7 Plus                     | [e77cad05c2](https://linux-hardware.org/?probe=e77cad05c2) | Oct 17, 2022 |
| ASUSTek       | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| Dell          | Inspiron 5447               | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Multilaser    | PC024                       | [892f53a067](https://linux-hardware.org/?probe=892f53a067) | Oct 17, 2022 |
| Acer          | Aspire 5750                 | [4e90ad293c](https://linux-hardware.org/?probe=4e90ad293c) | Oct 17, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [81cec7c137](https://linux-hardware.org/?probe=81cec7c137) | Oct 16, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [2d843ba905](https://linux-hardware.org/?probe=2d843ba905) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| Acer          | Nitro AN515-44              | [7293f219d8](https://linux-hardware.org/?probe=7293f219d8) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Alienware     | m15 R6                      | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| Acer          | Nitro AN515-44              | [8e16d67f02](https://linux-hardware.org/?probe=8e16d67f02) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Compaq        | 420                         | [cc3fae2a79](https://linux-hardware.org/?probe=cc3fae2a79) | Oct 15, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [19d249aa9c](https://linux-hardware.org/?probe=19d249aa9c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b5cfcb5d6c](https://linux-hardware.org/?probe=b5cfcb5d6c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a65b043bb7](https://linux-hardware.org/?probe=a65b043bb7) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | [491ba5984a](https://linux-hardware.org/?probe=491ba5984a) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | [d22d4118a7](https://linux-hardware.org/?probe=d22d4118a7) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| Acer          | Aspire A315-34              | [a95d9e55ba](https://linux-hardware.org/?probe=a95d9e55ba) | Oct 14, 2022 |
| Samsung       | 300E5M/300E5L               | [f8eae084ac](https://linux-hardware.org/?probe=f8eae084ac) | Oct 13, 2022 |
| Lenovo        | G50-80 80R0                 | [990bec11d7](https://linux-hardware.org/?probe=990bec11d7) | Oct 13, 2022 |
| Dell          | Inspiron 5567               | [754608b701](https://linux-hardware.org/?probe=754608b701) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Acer          | Aspire A315-53              | [3c99de982b](https://linux-hardware.org/?probe=3c99de982b) | Oct 13, 2022 |
| HP            | G42                         | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [d800a06da5](https://linux-hardware.org/?probe=d800a06da5) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [9d4c4f0c96](https://linux-hardware.org/?probe=9d4c4f0c96) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| Lenovo        | ThinkPad T480 20L6S1U700    | [df4489e9fb](https://linux-hardware.org/?probe=df4489e9fb) | Oct 12, 2022 |
| Acer          | Aspire ES1-572              | [7741ed43d0](https://linux-hardware.org/?probe=7741ed43d0) | Oct 12, 2022 |
| Acer          | Aspire A514-54              | [b566c0179a](https://linux-hardware.org/?probe=b566c0179a) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Acer          | Nitro AN515-52              | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| Acer          | Aspire E1-572               | [4097531dec](https://linux-hardware.org/?probe=4097531dec) | Oct 10, 2022 |
| Dell          | Latitude 5410               | [c69cc79a8e](https://linux-hardware.org/?probe=c69cc79a8e) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Samsung       | 550XBE/350XBE               | [bfce31736f](https://linux-hardware.org/?probe=bfce31736f) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Acer          | Nitro AN515-44              | [be45a704e2](https://linux-hardware.org/?probe=be45a704e2) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [acd8e18972](https://linux-hardware.org/?probe=acd8e18972) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| Acer          | Aspire A315-53              | [cdd4dd4637](https://linux-hardware.org/?probe=cdd4dd4637) | Oct 08, 2022 |
| Positivo      | Q232A                       | [658da8785e](https://linux-hardware.org/?probe=658da8785e) | Oct 08, 2022 |
| Standard      | MB40II                      | [97b446abda](https://linux-hardware.org/?probe=97b446abda) | Oct 08, 2022 |
| Unknown       | Unknown                     | [b941499384](https://linux-hardware.org/?probe=b941499384) | Oct 08, 2022 |
| Quanta        | TWS                         | [f7ba149979](https://linux-hardware.org/?probe=f7ba149979) | Oct 08, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [dd91590e9f](https://linux-hardware.org/?probe=dd91590e9f) | Oct 07, 2022 |
| Acer          | Aspire E1-571               | [fe1e7b060c](https://linux-hardware.org/?probe=fe1e7b060c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| Dell          | Inspiron 3542               | [f8d7d79e14](https://linux-hardware.org/?probe=f8d7d79e14) | Oct 07, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [6f08bf3d68](https://linux-hardware.org/?probe=6f08bf3d68) | Oct 07, 2022 |
| Positivo      | Mobile                      | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| Positivo      | W940SU2                     | [d403edabc4](https://linux-hardware.org/?probe=d403edabc4) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| Dell          | Inspiron 5537               | [75f96017fd](https://linux-hardware.org/?probe=75f96017fd) | Oct 05, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| Positivo      | C14CR01                     | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| Avell High... | B.ON                        | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Dell          | Inspiron 3442               | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Unknown       | Unknown                     | [23c45d949c](https://linux-hardware.org/?probe=23c45d949c) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [10fec0d039](https://linux-hardware.org/?probe=10fec0d039) | Oct 04, 2022 |
| Intel         | W7645                       | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | [f30bf7e978](https://linux-hardware.org/?probe=f30bf7e978) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [a9281e38d4](https://linux-hardware.org/?probe=a9281e38d4) | Oct 04, 2022 |
| Dell          | G3 3500                     | [9a574c1075](https://linux-hardware.org/?probe=9a574c1075) | Oct 04, 2022 |
| Dell          | Latitude E6420              | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c277d88bb6](https://linux-hardware.org/?probe=c277d88bb6) | Oct 03, 2022 |
| Sony          | VPCCA15FX                   | [c6c2a651b9](https://linux-hardware.org/?probe=c6c2a651b9) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | Inspiron 5590               | [bdb7d444f0](https://linux-hardware.org/?probe=bdb7d444f0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Dell          | XPS 13 9300                 | [00ecde42a1](https://linux-hardware.org/?probe=00ecde42a1) | Oct 02, 2022 |
| Unknown       | Unknown                     | [fc558ece05](https://linux-hardware.org/?probe=fc558ece05) | Oct 02, 2022 |
| Dell          | XPS L421X                   | [dc90cf9dbf](https://linux-hardware.org/?probe=dc90cf9dbf) | Oct 02, 2022 |
| Samsung       | 275E4E/275E5E               | [ba82d9366c](https://linux-hardware.org/?probe=ba82d9366c) | Oct 02, 2022 |
| Avell High... | B.ON                        | [240b350525](https://linux-hardware.org/?probe=240b350525) | Oct 02, 2022 |
| Positivo      | Mobile                      | [640bc1a962](https://linux-hardware.org/?probe=640bc1a962) | Oct 01, 2022 |
| Itautec       | Infoway a7420               | [bb52fe66cf](https://linux-hardware.org/?probe=bb52fe66cf) | Oct 01, 2022 |
| Sony          | VPCCA15FX                   | [96eb3d8cf7](https://linux-hardware.org/?probe=96eb3d8cf7) | Oct 01, 2022 |
| Lenovo        | G400s VILG1                 | [e666344187](https://linux-hardware.org/?probe=e666344187) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [b62ddbdab0](https://linux-hardware.org/?probe=b62ddbdab0) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | [9a047ee214](https://linux-hardware.org/?probe=9a047ee214) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | [4c0a153a12](https://linux-hardware.org/?probe=4c0a153a12) | Oct 01, 2022 |
| Chuwi         | HeroBook Air                | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| Positivo      | Mobile                      | [dcf8b09bec](https://linux-hardware.org/?probe=dcf8b09bec) | Sep 30, 2022 |
| Positivo      | Mobile                      | [6d2584bcb8](https://linux-hardware.org/?probe=6d2584bcb8) | Sep 30, 2022 |
| Acer          | Nitro AN515-44              | [149337514c](https://linux-hardware.org/?probe=149337514c) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fa00f3d0ca](https://linux-hardware.org/?probe=fa00f3d0ca) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| Dell          | Inspiron 5447               | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | [8272a6655b](https://linux-hardware.org/?probe=8272a6655b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | [be9d7b3e42](https://linux-hardware.org/?probe=be9d7b3e42) | Sep 28, 2022 |
| Dell          | Vostro 15 3515              | [7e4413a053](https://linux-hardware.org/?probe=7e4413a053) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bbd715eb5a](https://linux-hardware.org/?probe=bbd715eb5a) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire E5-573               | [f7e628a5a1](https://linux-hardware.org/?probe=f7e628a5a1) | Sep 28, 2022 |
| Positivo      | S14CT01                     | [66e0c53646](https://linux-hardware.org/?probe=66e0c53646) | Sep 28, 2022 |
| Unknown       | Unknown                     | [3e450900da](https://linux-hardware.org/?probe=3e450900da) | Sep 28, 2022 |
| LG Electro... | C400-G.BC22P1               | [a325f5eb86](https://linux-hardware.org/?probe=a325f5eb86) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Philco        | PNB14.1AC14S128W10          | [ee4bc98535](https://linux-hardware.org/?probe=ee4bc98535) | Sep 27, 2022 |
| Lenovo        | ThinkPad T410 2537AT9       | [553490bb4c](https://linux-hardware.org/?probe=553490bb4c) | Sep 27, 2022 |
| Standard      | AHV                         | [a80b2d344d](https://linux-hardware.org/?probe=a80b2d344d) | Sep 27, 2022 |
| Acer          | Nitro AN515-45              | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| Dell          | Latitude 5420               | [bd81c07917](https://linux-hardware.org/?probe=bd81c07917) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | [60933ed48b](https://linux-hardware.org/?probe=60933ed48b) | Sep 26, 2022 |
| Acer          | Aspire A514-54              | [bab009e0b7](https://linux-hardware.org/?probe=bab009e0b7) | Sep 26, 2022 |
| Positivo      | S14CT01                     | [2191cd2dd1](https://linux-hardware.org/?probe=2191cd2dd1) | Sep 26, 2022 |
| HP            | G42                         | [39a4836398](https://linux-hardware.org/?probe=39a4836398) | Sep 26, 2022 |
| Samsung       | 670Z5E                      | [6bce247e38](https://linux-hardware.org/?probe=6bce247e38) | Sep 26, 2022 |
| Positivo      | S14SL01                     | [a6b3c260f4](https://linux-hardware.org/?probe=a6b3c260f4) | Sep 25, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [07554a7a2b](https://linux-hardware.org/?probe=07554a7a2b) | Sep 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| Positivo      | S14SL01                     | [e09fcd6e38](https://linux-hardware.org/?probe=e09fcd6e38) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [939bba43d1](https://linux-hardware.org/?probe=939bba43d1) | Sep 25, 2022 |
| Avell High... | A70 MOB                     | [b867406b76](https://linux-hardware.org/?probe=b867406b76) | Sep 25, 2022 |
| Acer          | AO532h                      | [383ce70d97](https://linux-hardware.org/?probe=383ce70d97) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | [7fb024bb5d](https://linux-hardware.org/?probe=7fb024bb5d) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | [1190ad2886](https://linux-hardware.org/?probe=1190ad2886) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [118cf21173](https://linux-hardware.org/?probe=118cf21173) | Sep 24, 2022 |
| Dell          | Latitude E5400              | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| Dell          | Latitude 3410               | [ba10ea9fc5](https://linux-hardware.org/?probe=ba10ea9fc5) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2322475867](https://linux-hardware.org/?probe=2322475867) | Sep 24, 2022 |
| Dell          | Latitude 5420               | [170a3248f6](https://linux-hardware.org/?probe=170a3248f6) | Sep 24, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| Dell          | Inspiron 5566               | [4ed9eae431](https://linux-hardware.org/?probe=4ed9eae431) | Sep 23, 2022 |
| Acer          | Nitro AN515-44              | [b02d161acb](https://linux-hardware.org/?probe=b02d161acb) | Sep 23, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Sony          | SVE15125CBW                 | [50b65906b1](https://linux-hardware.org/?probe=50b65906b1) | Sep 22, 2022 |
| Dell          | Inspiron 5566               | [183f486a54](https://linux-hardware.org/?probe=183f486a54) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [74d69dbd69](https://linux-hardware.org/?probe=74d69dbd69) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| ASUSTek       | X451CA                      | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| LG Electro... | C400-G.BC22P1               | [b5aad7f903](https://linux-hardware.org/?probe=b5aad7f903) | Sep 20, 2022 |
| ASUSTek       | K46CB                       | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| LG Electro... | C400-G.BC31P1               | [66c8977810](https://linux-hardware.org/?probe=66c8977810) | Sep 19, 2022 |
| Samsung       | 300E5K/300E5Q               | [aaedf90f31](https://linux-hardware.org/?probe=aaedf90f31) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [40629d6fbc](https://linux-hardware.org/?probe=40629d6fbc) | Sep 19, 2022 |
| Acer          | Aspire E1-571               | [b98206a5fb](https://linux-hardware.org/?probe=b98206a5fb) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| Positivo      | C14CR21                     | [e72ef2677b](https://linux-hardware.org/?probe=e72ef2677b) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Samsung       | 370E4K                      | [1a297b75f9](https://linux-hardware.org/?probe=1a297b75f9) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Gateway       | NV55C                       | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Samsung       | 670Z5E                      | [50758a53dd](https://linux-hardware.org/?probe=50758a53dd) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| HP            | ProBook 6470b               | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [edc0c871cb](https://linux-hardware.org/?probe=edc0c871cb) | Sep 17, 2022 |
| Acer          | Aspire A315-23G             | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| Samsung       | 275E4E/275E5E               | [89706d3dac](https://linux-hardware.org/?probe=89706d3dac) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| Dell          | Vostro 15 3510              | [d70dc7ab47](https://linux-hardware.org/?probe=d70dc7ab47) | Sep 16, 2022 |
| Dell          | Vostro 15 3510              | [0bcb975501](https://linux-hardware.org/?probe=0bcb975501) | Sep 16, 2022 |
| Lenovo        | G480 20149                  | [8fed7863dd](https://linux-hardware.org/?probe=8fed7863dd) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Acer          | Aspire A515-51              | [59811273b4](https://linux-hardware.org/?probe=59811273b4) | Sep 16, 2022 |
| Unknown       | Unknown                     | [d391ace7f8](https://linux-hardware.org/?probe=d391ace7f8) | Sep 16, 2022 |
| Dell          | G7 7588                     | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| HP            | Compaq Presario CQ50        | [41dcd9ffc4](https://linux-hardware.org/?probe=41dcd9ffc4) | Sep 16, 2022 |
| HP            | ProBook 4530s               | [821a6eda47](https://linux-hardware.org/?probe=821a6eda47) | Sep 16, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Acer          | Aspire E5-571G              | [0a02b8ef94](https://linux-hardware.org/?probe=0a02b8ef94) | Sep 15, 2022 |
| Positivo      | Mobile                      | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| Dell          | Latitude 3420               | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| HP            | 1000                        | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [16cf967fc8](https://linux-hardware.org/?probe=16cf967fc8) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Compal        | NCL60/61                    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| Dell          | Inspiron 5458               | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | RV415/RV515                 | [bc83707f72](https://linux-hardware.org/?probe=bc83707f72) | Sep 12, 2022 |
| HP            | EliteBook 2530p             | [4bae06f3d0](https://linux-hardware.org/?probe=4bae06f3d0) | Sep 12, 2022 |
| Dell          | Inspiron 5548               | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Avell High... | B.ON                        | [f30bca74ab](https://linux-hardware.org/?probe=f30bca74ab) | Sep 12, 2022 |
| Acer          | Aspire ES1-411              | [064b2bd5f2](https://linux-hardware.org/?probe=064b2bd5f2) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| Toshiba       | IS 1413G                    | [fab48b6c15](https://linux-hardware.org/?probe=fab48b6c15) | Sep 10, 2022 |
| Acer          | Aspire ES1-411              | [6bbebcbcb1](https://linux-hardware.org/?probe=6bbebcbcb1) | Sep 10, 2022 |
| ASUSTek       | K53E                        | [d39f35f5d9](https://linux-hardware.org/?probe=d39f35f5d9) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Acer          | Nitro AN515-44              | [9f5bc258b6](https://linux-hardware.org/?probe=9f5bc258b6) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [823dbe2390](https://linux-hardware.org/?probe=823dbe2390) | Sep 10, 2022 |
| Acer          | Aspire E1-572               | [1cfbfd9b91](https://linux-hardware.org/?probe=1cfbfd9b91) | Sep 09, 2022 |
| HP            | ProBook 640 G1              | [e6c0d3de61](https://linux-hardware.org/?probe=e6c0d3de61) | Sep 09, 2022 |
| Avell High... | A70 MOB                     | [1cc84e9a0d](https://linux-hardware.org/?probe=1cc84e9a0d) | Sep 09, 2022 |
| Acer          | Aspire A515-54              | [745c098d8a](https://linux-hardware.org/?probe=745c098d8a) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc0a825c8e](https://linux-hardware.org/?probe=cc0a825c8e) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| Positivo      | H14BT58                     | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Dell          | Vostro 3500                 | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| Dell          | Inspiron 5457               | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| Dell          | Vostro 3550                 | [f04353bb0e](https://linux-hardware.org/?probe=f04353bb0e) | Sep 08, 2022 |
| ASUSTek       | K46CB                       | [9449630b6a](https://linux-hardware.org/?probe=9449630b6a) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | [1d73ebcfb8](https://linux-hardware.org/?probe=1d73ebcfb8) | Sep 08, 2022 |
| Acer          | Aspire ES1-411              | [d3df9a2592](https://linux-hardware.org/?probe=d3df9a2592) | Sep 08, 2022 |
| Digibras      | US41II1                     | [890a4894cf](https://linux-hardware.org/?probe=890a4894cf) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | [de1ddd77dd](https://linux-hardware.org/?probe=de1ddd77dd) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| Positivo      | Mobile                      | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [104331cf4c](https://linux-hardware.org/?probe=104331cf4c) | Sep 07, 2022 |
| Positivo      | Smash                       | [0051f458c6](https://linux-hardware.org/?probe=0051f458c6) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| LG Electro... | A530-T.BE76P1               | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | [b12a6d2146](https://linux-hardware.org/?probe=b12a6d2146) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | [48a1236943](https://linux-hardware.org/?probe=48a1236943) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [93d596fc4f](https://linux-hardware.org/?probe=93d596fc4f) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Alienware     | m15 R7                      | [c9d5bcb40f](https://linux-hardware.org/?probe=c9d5bcb40f) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| ASUSTek       | X45C                        | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [0e3fd8d374](https://linux-hardware.org/?probe=0e3fd8d374) | Sep 05, 2022 |
| Lenovo        | G40-80 80JE                 | [c876beae17](https://linux-hardware.org/?probe=c876beae17) | Sep 04, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | [e6fa43e12e](https://linux-hardware.org/?probe=e6fa43e12e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [920bfdae34](https://linux-hardware.org/?probe=920bfdae34) | Sep 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| Timi          | TM1701                      | [740d59830a](https://linux-hardware.org/?probe=740d59830a) | Sep 03, 2022 |
| Samsung       | 300E5M/300E5L               | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Itautec       | Infoway                     | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| Daten Tecn... | DT02-M4                     | [b697980a15](https://linux-hardware.org/?probe=b697980a15) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Samsung       | 670Z5E                      | [0e65ce891e](https://linux-hardware.org/?probe=0e65ce891e) | Sep 02, 2022 |
| Samsung       | 670Z5E                      | [595f13e0b9](https://linux-hardware.org/?probe=595f13e0b9) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | G15 5510                    | [78f2f5c95a](https://linux-hardware.org/?probe=78f2f5c95a) | Sep 01, 2022 |
| Dell          | G3 3590                     | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Avell High... | C62 MOB                     | [ab93c1f314](https://linux-hardware.org/?probe=ab93c1f314) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | [6e337cb132](https://linux-hardware.org/?probe=6e337cb132) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | [cdac9cafaf](https://linux-hardware.org/?probe=cdac9cafaf) | Sep 01, 2022 |
| Acer          | Aspire E5-571               | [7759e41b1d](https://linux-hardware.org/?probe=7759e41b1d) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [c1d60c7b0b](https://linux-hardware.org/?probe=c1d60c7b0b) | Aug 31, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [dafd789095](https://linux-hardware.org/?probe=dafd789095) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Dell          | Vostro 3550                 | [c26bf23cdd](https://linux-hardware.org/?probe=c26bf23cdd) | Aug 31, 2022 |
| Samsung       | 670Z5E                      | [c72797ddaa](https://linux-hardware.org/?probe=c72797ddaa) | Aug 31, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [454c7382bd](https://linux-hardware.org/?probe=454c7382bd) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| Dell          | Inspiron N5110              | [9fe8c04ec6](https://linux-hardware.org/?probe=9fe8c04ec6) | Aug 30, 2022 |
| Avell High... | B.ON                        | [dbc18dad43](https://linux-hardware.org/?probe=dbc18dad43) | Aug 30, 2022 |
| Samsung       | 300E5M/300E5L               | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [eedd8fa1eb](https://linux-hardware.org/?probe=eedd8fa1eb) | Aug 29, 2022 |
| Samsung       | 670Z5E                      | [59959102e0](https://linux-hardware.org/?probe=59959102e0) | Aug 29, 2022 |
| Positivo      | W942SW_SW1                  | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| Sony          | VPCEB36GM                   | [4495872308](https://linux-hardware.org/?probe=4495872308) | Aug 29, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [ee3156dfc5](https://linux-hardware.org/?probe=ee3156dfc5) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| Google        | Eve                         | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Acer          | Nitro AN515-54              | [211edd7b18](https://linux-hardware.org/?probe=211edd7b18) | Aug 28, 2022 |
| Acer          | Aspire A315-53              | [6ba36ee616](https://linux-hardware.org/?probe=6ba36ee616) | Aug 28, 2022 |
| Samsung       | 670Z5E                      | [8d86f689b4](https://linux-hardware.org/?probe=8d86f689b4) | Aug 28, 2022 |
| Dell          | Inspiron 5567               | [09d8066f44](https://linux-hardware.org/?probe=09d8066f44) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| HP            | ENVY dv7                    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Dell          | Inspiron 3442               | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Acer          | Nitro AN515-44              | [7d3e13cfa9](https://linux-hardware.org/?probe=7d3e13cfa9) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Acer          | Nitro AN515-54              | [975f6a801d](https://linux-hardware.org/?probe=975f6a801d) | Aug 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [85e0bc5d57](https://linux-hardware.org/?probe=85e0bc5d57) | Aug 27, 2022 |
| Positivo      | C14CR01                     | [bb9a4c427a](https://linux-hardware.org/?probe=bb9a4c427a) | Aug 27, 2022 |
| Alienware     | m15 R6                      | [d39642f1ce](https://linux-hardware.org/?probe=d39642f1ce) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Dell          | Vostro 1520                 | [b51f7dfba6](https://linux-hardware.org/?probe=b51f7dfba6) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [c8d0dcb323](https://linux-hardware.org/?probe=c8d0dcb323) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [f2de49c59b](https://linux-hardware.org/?probe=f2de49c59b) | Aug 26, 2022 |
| Acer          | Aspire A315-34              | [d71a1ce240](https://linux-hardware.org/?probe=d71a1ce240) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [21e69486fd](https://linux-hardware.org/?probe=21e69486fd) | Aug 26, 2022 |
| Dell          | Inspiron 1525               | [46512c691b](https://linux-hardware.org/?probe=46512c691b) | Aug 26, 2022 |
| Dell          | Inspiron 1525               | [47efe2482f](https://linux-hardware.org/?probe=47efe2482f) | Aug 25, 2022 |
| Dell          | Inspiron 5537               | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Samsung       | 550XDA                      | [505f5100d0](https://linux-hardware.org/?probe=505f5100d0) | Aug 25, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [635925265e](https://linux-hardware.org/?probe=635925265e) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Dell          | Inspiron 3583               | [37c79f953b](https://linux-hardware.org/?probe=37c79f953b) | Aug 24, 2022 |
| Dell          | Latitude 5400               | [fce2c90c7e](https://linux-hardware.org/?probe=fce2c90c7e) | Aug 24, 2022 |
| Acer          | Nitro AN515-44              | [b456a14fe0](https://linux-hardware.org/?probe=b456a14fe0) | Aug 24, 2022 |
| ASUSTek       | X202E                       | [b814b9f427](https://linux-hardware.org/?probe=b814b9f427) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Acer          | Aspire A315-42G             | [d5b057d1c9](https://linux-hardware.org/?probe=d5b057d1c9) | Aug 23, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3507cf3eab](https://linux-hardware.org/?probe=3507cf3eab) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [d394d086d9](https://linux-hardware.org/?probe=d394d086d9) | Aug 23, 2022 |
| Acer          | Aspire A315-54K             | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| LG Electro... | S430-G.BC33P1               | [d0b4cf47fe](https://linux-hardware.org/?probe=d0b4cf47fe) | Aug 23, 2022 |
| Dell          | Inspiron 3501               | [514172ddcc](https://linux-hardware.org/?probe=514172ddcc) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [dd86526296](https://linux-hardware.org/?probe=dd86526296) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| Acer          | Nitro AN515-44              | [092dcdf5b7](https://linux-hardware.org/?probe=092dcdf5b7) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c41ecc4e0](https://linux-hardware.org/?probe=3c41ecc4e0) | Aug 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [323faca611](https://linux-hardware.org/?probe=323faca611) | Aug 22, 2022 |
| AMI           | Unknown                     | [b6004987ab](https://linux-hardware.org/?probe=b6004987ab) | Aug 22, 2022 |
| ASUSTek       | X45U                        | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| ASUSTek       | K53E                        | [65ddd1bb6f](https://linux-hardware.org/?probe=65ddd1bb6f) | Aug 22, 2022 |
| Dell          | Inspiron 13-5368            | [9d0f972a5f](https://linux-hardware.org/?probe=9d0f972a5f) | Aug 22, 2022 |
| Dell          | Inspiron 3501               | [2f3937854b](https://linux-hardware.org/?probe=2f3937854b) | Aug 22, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [64b9832653](https://linux-hardware.org/?probe=64b9832653) | Aug 22, 2022 |
| Notebook      | NJx0MU                      | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| HP            | Mini 110-3100               | [1e27123078](https://linux-hardware.org/?probe=1e27123078) | Aug 22, 2022 |
| Acer          | Unknown                     | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | [d9ab8accea](https://linux-hardware.org/?probe=d9ab8accea) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | [6ff066abac](https://linux-hardware.org/?probe=6ff066abac) | Aug 21, 2022 |
| Positivo      | C14RV01                     | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| Samsung       | 550XCJ/550XCR               | [cae0d518ee](https://linux-hardware.org/?probe=cae0d518ee) | Aug 21, 2022 |
| Positivo      | C14CU51                     | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| Acer          | Aspire A315-23G             | [e31fb3f3cf](https://linux-hardware.org/?probe=e31fb3f3cf) | Aug 21, 2022 |
| Positivo      | Mobile                      | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| Positivo      | Q4128C-S                    | [abe16f9b0c](https://linux-hardware.org/?probe=abe16f9b0c) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | [3b7d550ab9](https://linux-hardware.org/?probe=3b7d550ab9) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | [9b438d4bbf](https://linux-hardware.org/?probe=9b438d4bbf) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| Gateway       | NV55C                       | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| ASUSTek       | K45A                        | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Acer          | Aspire A515-52G             | [00a40c053e](https://linux-hardware.org/?probe=00a40c053e) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| Acer          | Nitro AN515-44              | [aa18fee893](https://linux-hardware.org/?probe=aa18fee893) | Aug 18, 2022 |
| Samsung       | 670Z5E                      | [039ab9ead1](https://linux-hardware.org/?probe=039ab9ead1) | Aug 17, 2022 |
| HP            | 14                          | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| Positivo      | S14CT01                     | [22d8d4f3a2](https://linux-hardware.org/?probe=22d8d4f3a2) | Aug 17, 2022 |
| Positivo      | S14CT01                     | [2b561def97](https://linux-hardware.org/?probe=2b561def97) | Aug 17, 2022 |
| ASUSTek       | K45A                        | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| TPVAOC        | AA183M                      | [089472ea13](https://linux-hardware.org/?probe=089472ea13) | Aug 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35cd057234](https://linux-hardware.org/?probe=35cd057234) | Aug 16, 2022 |
| AMI           | Unknown                     | [a1a8c0b2c5](https://linux-hardware.org/?probe=a1a8c0b2c5) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| Sony          | VGN-NR230AE                 | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | [3a6b82f27f](https://linux-hardware.org/?probe=3a6b82f27f) | Aug 15, 2022 |
| ASUSTek       | K84C                        | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| Itautec       | Infoway W7425               | [64b3153e8a](https://linux-hardware.org/?probe=64b3153e8a) | Aug 15, 2022 |
| Dell          | Vostro 5490                 | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Lenovo        | G470 20078                  | [cafdc06a51](https://linux-hardware.org/?probe=cafdc06a51) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| Dell          | Inspiron 5420               | [83b14f40e6](https://linux-hardware.org/?probe=83b14f40e6) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | [42223a802a](https://linux-hardware.org/?probe=42223a802a) | Aug 14, 2022 |
| Acer          | Aspire A315-23G             | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| HP            | ProBook 640 G1              | [7f8289a8f3](https://linux-hardware.org/?probe=7f8289a8f3) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| Samsung       | 300E5M/300E5L               | [e39c1b59a6](https://linux-hardware.org/?probe=e39c1b59a6) | Aug 13, 2022 |
| HP            | EliteBook 8460p             | [b7418c601b](https://linux-hardware.org/?probe=b7418c601b) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [837e6e891d](https://linux-hardware.org/?probe=837e6e891d) | Aug 13, 2022 |
| Positivo      | Mobile                      | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| Samsung       | 550XDA                      | [4964cf32aa](https://linux-hardware.org/?probe=4964cf32aa) | Aug 12, 2022 |
| Acer          | Aspire A514-54              | [be52876050](https://linux-hardware.org/?probe=be52876050) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [dcf4a63c1e](https://linux-hardware.org/?probe=dcf4a63c1e) | Aug 12, 2022 |
| Samsung       | R430/R480/R440              | [39323c99dc](https://linux-hardware.org/?probe=39323c99dc) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| Positivo      | Q4128C-S                    | [4f8b07c958](https://linux-hardware.org/?probe=4f8b07c958) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [074b25e3a3](https://linux-hardware.org/?probe=074b25e3a3) | Aug 12, 2022 |
| Positivo      | C14CR21                     | [6e7b0da365](https://linux-hardware.org/?probe=6e7b0da365) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| Avell High... | B.ON                        | [b057c64850](https://linux-hardware.org/?probe=b057c64850) | Aug 11, 2022 |
| Dell          | Vostro 15 3515              | [087818a904](https://linux-hardware.org/?probe=087818a904) | Aug 11, 2022 |
| Dell          | Vostro 3460                 | [fbaf8208cb](https://linux-hardware.org/?probe=fbaf8208cb) | Aug 11, 2022 |
| Acer          | Aspire 4736Z                | [16cf1afc2a](https://linux-hardware.org/?probe=16cf1afc2a) | Aug 11, 2022 |
| ASUSTek       | X510UR                      | [3faeed2cc1](https://linux-hardware.org/?probe=3faeed2cc1) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Dell          | G3 3590                     | [6284e4a400](https://linux-hardware.org/?probe=6284e4a400) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [19c10fbafb](https://linux-hardware.org/?probe=19c10fbafb) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [84453db535](https://linux-hardware.org/?probe=84453db535) | Aug 10, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3151f7847e](https://linux-hardware.org/?probe=3151f7847e) | Aug 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [87e84c988f](https://linux-hardware.org/?probe=87e84c988f) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Compaq        | Presario CQ-31              | [d22794a255](https://linux-hardware.org/?probe=d22794a255) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d34fcfc4f7](https://linux-hardware.org/?probe=d34fcfc4f7) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [350a6d8583](https://linux-hardware.org/?probe=350a6d8583) | Aug 09, 2022 |
| Alienware     | x15 R1                      | [59b6412e2f](https://linux-hardware.org/?probe=59b6412e2f) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Acer          | Aspire A315-56              | [95de2fe5b3](https://linux-hardware.org/?probe=95de2fe5b3) | Aug 08, 2022 |
| Acer          | Aspire A315-56              | [742452483f](https://linux-hardware.org/?probe=742452483f) | Aug 08, 2022 |
| Lenovo        | ThinkPad L450 20DSS0DH1N    | [1aa79c3fef](https://linux-hardware.org/?probe=1aa79c3fef) | Aug 08, 2022 |
| Dell          | Inspiron 5447               | [65b4e485ad](https://linux-hardware.org/?probe=65b4e485ad) | Aug 08, 2022 |
| Acer          | Nitro AN515-54              | [221d7636db](https://linux-hardware.org/?probe=221d7636db) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| HP            | Mini 110-3100               | [f91eefcb06](https://linux-hardware.org/?probe=f91eefcb06) | Aug 07, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| Avell High... | B.ON                        | [d16f62f2b9](https://linux-hardware.org/?probe=d16f62f2b9) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| Dell          | XPS 13 9310                 | [7e9a6b9e85](https://linux-hardware.org/?probe=7e9a6b9e85) | Aug 06, 2022 |
| Positivo      | Mobile                      | [017b8eeb6b](https://linux-hardware.org/?probe=017b8eeb6b) | Aug 06, 2022 |
| Positivo      | Mobile                      | [fe169d2119](https://linux-hardware.org/?probe=fe169d2119) | Aug 06, 2022 |
| Sony          | VPCSB35FB                   | [edbd7a9cb8](https://linux-hardware.org/?probe=edbd7a9cb8) | Aug 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [2f96d2d61a](https://linux-hardware.org/?probe=2f96d2d61a) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Acer          | Swift SF314-511             | [39b2c17704](https://linux-hardware.org/?probe=39b2c17704) | Aug 06, 2022 |
| Toshiba       | PORTEGE Z930                | [6cec3fa330](https://linux-hardware.org/?probe=6cec3fa330) | Aug 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [a711d41e0d](https://linux-hardware.org/?probe=a711d41e0d) | Aug 05, 2022 |
| Dell          | Inspiron 5402               | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Compaq        | 430                         | [581a8bbf00](https://linux-hardware.org/?probe=581a8bbf00) | Aug 05, 2022 |
| HP            | ProBook 4440s               | [cb7b9336ac](https://linux-hardware.org/?probe=cb7b9336ac) | Aug 04, 2022 |
| MSI           | Katana GF66 11UC            | [8d210c5007](https://linux-hardware.org/?probe=8d210c5007) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | [508f6ab592](https://linux-hardware.org/?probe=508f6ab592) | Aug 04, 2022 |
| HP            | ProBook 645 G1              | [0183d60d2c](https://linux-hardware.org/?probe=0183d60d2c) | Aug 04, 2022 |
| Dell          | Latitude E5470              | [9e78351999](https://linux-hardware.org/?probe=9e78351999) | Aug 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0ef9fef16d](https://linux-hardware.org/?probe=0ef9fef16d) | Aug 04, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [8bd9c2f957](https://linux-hardware.org/?probe=8bd9c2f957) | Aug 04, 2022 |
| Positivo      | S14BW01                     | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| Sony          | VPCCW13FB                   | [34db85d2d4](https://linux-hardware.org/?probe=34db85d2d4) | Aug 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Dell          | Inspiron 5566               | [91ecf4a05f](https://linux-hardware.org/?probe=91ecf4a05f) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Acer          | Aspire A315-23G             | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Dell          | Inspiron 5502               | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Acer          | Aspire A315-56              | [aed4690a47](https://linux-hardware.org/?probe=aed4690a47) | Aug 03, 2022 |
| Apple         | MacBookPro9,2               | [a1eb69af2d](https://linux-hardware.org/?probe=a1eb69af2d) | Aug 03, 2022 |
| Clevo         | W240BU                      | [df5302b1c3](https://linux-hardware.org/?probe=df5302b1c3) | Aug 03, 2022 |
| Positivo      | Smash                       | [fd44d353d3](https://linux-hardware.org/?probe=fd44d353d3) | Aug 03, 2022 |
| Daten Tecn... | DT02-M4                     | [1dfd4fe5ba](https://linux-hardware.org/?probe=1dfd4fe5ba) | Aug 03, 2022 |
| Sony          | VPCCW13FB                   | [2d36ec46e0](https://linux-hardware.org/?probe=2d36ec46e0) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03770f280e](https://linux-hardware.org/?probe=03770f280e) | Aug 02, 2022 |
| Dell          | Inspiron 5547               | [cd42712c4c](https://linux-hardware.org/?probe=cd42712c4c) | Aug 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8a4208caa8](https://linux-hardware.org/?probe=8a4208caa8) | Aug 02, 2022 |
| Dell          | Inspiron 5547               | [be6e34d630](https://linux-hardware.org/?probe=be6e34d630) | Aug 02, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | G15 5510                    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| HP            | Laptop 15-db0xxx            | [ec7e5864c2](https://linux-hardware.org/?probe=ec7e5864c2) | Aug 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ed743724e7](https://linux-hardware.org/?probe=ed743724e7) | Aug 02, 2022 |
| Positivo      | Q232A                       | [da99b8ab1e](https://linux-hardware.org/?probe=da99b8ab1e) | Aug 01, 2022 |
| Positivo      | Q232A                       | [7d860e8f5d](https://linux-hardware.org/?probe=7d860e8f5d) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4e2361dd88](https://linux-hardware.org/?probe=4e2361dd88) | Aug 01, 2022 |
| Unknown       | Unknown                     | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Sony          | VPCCW13FB                   | [453d0f75cc](https://linux-hardware.org/?probe=453d0f75cc) | Jul 31, 2022 |
| Dell          | Inspiron 5590               | [4d91f51698](https://linux-hardware.org/?probe=4d91f51698) | Jul 31, 2022 |
| Clevo         | W240BU                      | [7f4a0b1995](https://linux-hardware.org/?probe=7f4a0b1995) | Jul 31, 2022 |
| Unknown       | Unknown                     | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| Compaq        | Presario CQ-23              | [76ea82c314](https://linux-hardware.org/?probe=76ea82c314) | Jul 30, 2022 |
| Acer          | Nitro AN515-44              | [1c907403d4](https://linux-hardware.org/?probe=1c907403d4) | Jul 30, 2022 |
| Positivo      | C4128E-S                    | [03150bf5fa](https://linux-hardware.org/?probe=03150bf5fa) | Jul 29, 2022 |
| Acer          | Aspire A514-54              | [9a18d7476f](https://linux-hardware.org/?probe=9a18d7476f) | Jul 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [c8609ab506](https://linux-hardware.org/?probe=c8609ab506) | Jul 29, 2022 |
| Acer          | Aspire E1-531               | [e9161d7c33](https://linux-hardware.org/?probe=e9161d7c33) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| Positivo      | C4128E-S                    | [a06c799159](https://linux-hardware.org/?probe=a06c799159) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| Dell          | Inspiron 5402               | [90df51f92b](https://linux-hardware.org/?probe=90df51f92b) | Jul 29, 2022 |
| Dell          | Inspiron 15-3567            | [ceb521429a](https://linux-hardware.org/?probe=ceb521429a) | Jul 29, 2022 |
| Acer          | Aspire 5750                 | [e3f2dd0271](https://linux-hardware.org/?probe=e3f2dd0271) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| Dell          | Inspiron 3501               | [be3c46490f](https://linux-hardware.org/?probe=be3c46490f) | Jul 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [fdb481a551](https://linux-hardware.org/?probe=fdb481a551) | Jul 28, 2022 |
| Acer          | Aspire A514-54              | [4a6c9ef157](https://linux-hardware.org/?probe=4a6c9ef157) | Jul 28, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [adb71c8acc](https://linux-hardware.org/?probe=adb71c8acc) | Jul 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu 20.04     | 908       | 12.65%  |
| Ubuntu 18.04     | 591       | 8.23%   |
| Pop!_OS 20.04    | 193       | 2.69%   |
| Ubuntu 22.04     | 189       | 2.63%   |
| Linux Mint 20    | 189       | 2.63%   |
| Linux Mint 19.3  | 165       | 2.3%    |
| OpenMandriva 4.2 | 155       | 2.16%   |
| OpenMandriva 4.3 | 141       | 1.96%   |
| Linux Mint 20.3  | 133       | 1.85%   |
| Linux Mint 19.1  | 122       | 1.7%    |
| Ubuntu 19.04     | 117       | 1.63%   |
| Linux Mint 20.1  | 117       | 1.63%   |
| Arch             | 114       | 1.59%   |
| KDE neon 20.04   | 112       | 1.56%   |
| Linux Mint 20.2  | 111       | 1.55%   |
| Ubuntu 19.10     | 106       | 1.48%   |
| Manjaro          | 105       | 1.46%   |
| Pop!_OS 22.04    | 96        | 1.34%   |
| Zorin 15         | 91        | 1.27%   |
| Zorin 16         | 89        | 1.24%   |
| Debian 10        | 83        | 1.16%   |
| Debian 11        | 81        | 1.13%   |
| Fedora 35        | 78        | 1.09%   |
| Fedora 34        | 72        | 1%      |
| Pop!_OS 21.10    | 71        | 0.99%   |
| Fedora 32        | 69        | 0.96%   |
| Endless 3.7.8    | 69        | 0.96%   |
| Xubuntu 20.04    | 67        | 0.93%   |
| Pop!_OS 21.04    | 67        | 0.93%   |
| Endless 3.9.5    | 67        | 0.93%   |
| Fedora 36        | 64        | 0.89%   |
| Kubuntu 20.04    | 62        | 0.86%   |
| Pop!_OS 20.10    | 60        | 0.84%   |
| Fedora 33        | 60        | 0.84%   |
| Ubuntu 20.10     | 56        | 0.78%   |
| Linux Mint 19.2  | 55        | 0.77%   |
| Linux Mint 21    | 53        | 0.74%   |
| Endless 3.9.1    | 53        | 0.74%   |
| Arch Rolling     | 53        | 0.74%   |
| Ubuntu 18.10     | 47        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2074      | 30.21%  |
| Linux Mint    | 927       | 13.5%   |
| Endless       | 830       | 12.09%  |
| Pop!_OS       | 468       | 6.82%   |
| Fedora        | 398       | 5.8%    |
| OpenMandriva  | 326       | 4.75%   |
| Debian        | 209       | 3.04%   |
| Manjaro       | 200       | 2.91%   |
| Zorin         | 184       | 2.68%   |
| Arch          | 157       | 2.29%   |
| KDE neon      | 135       | 1.97%   |
| Xubuntu       | 118       | 1.72%   |
| Kubuntu       | 115       | 1.68%   |
| Lubuntu       | 68        | 0.99%   |
| Elementary    | 61        | 0.89%   |
| Ubuntu MATE   | 60        | 0.87%   |
| openSUSE      | 56        | 0.82%   |
| ROSA          | 52        | 0.76%   |
| Ubuntu Unity  | 50        | 0.73%   |
| Kali          | 37        | 0.54%   |
| LMDE          | 34        | 0.5%    |
| Deepin        | 30        | 0.44%   |
| Ubuntu Budgie | 28        | 0.41%   |
| Clear Linux   | 26        | 0.38%   |
| LinuxFX       | 21        | 0.31%   |
| ArcoLinux     | 19        | 0.28%   |
| EndeavourOS   | 12        | 0.17%   |
| BigLinux      | 12        | 0.17%   |
| BlackPanther  | 11        | 0.16%   |
| CentOS        | 10        | 0.15%   |
| Reborn OS     | 9         | 0.13%   |
| UbuntuDDE     | 8         | 0.12%   |
| Peppermint    | 8         | 0.12%   |
| Parrot        | 8         | 0.12%   |
| MX            | 8         | 0.12%   |
| Garuda Linux  | 8         | 0.12%   |
| Gentoo        | 7         | 0.1%    |
| Solus         | 6         | 0.09%   |
| Slackware     | 5         | 0.07%   |
| Linux Lite    | 5         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 471       | 6.11%   |
| 5.8.0-14-generic         | 275       | 3.57%   |
| 5.10.14-desktop-1omv4002 | 149       | 1.93%   |
| 5.16.7-desktop-1omv4003  | 136       | 1.77%   |
| 5.4.0-19-generic         | 114       | 1.48%   |
| 5.3.0-28-generic         | 108       | 1.4%    |
| 5.11.0-35-generic        | 83        | 1.08%   |
| 5.4.0-7634-generic       | 74        | 0.96%   |
| 5.4.0-48-generic         | 72        | 0.93%   |
| 5.4.0-40-generic         | 70        | 0.91%   |
| 4.15.0-46-generic        | 70        | 0.91%   |
| 5.4.0-26-generic         | 63        | 0.82%   |
| 5.4.0-58-generic         | 59        | 0.77%   |
| 5.4.0-52-generic         | 57        | 0.74%   |
| 5.4.0-47-generic         | 54        | 0.7%    |
| 5.15.0-56-generic        | 51        | 0.66%   |
| 5.3.0-19-generic         | 50        | 0.65%   |
| 5.3.0-23-generic         | 47        | 0.61%   |
| 5.3.0-46-generic         | 46        | 0.6%    |
| 5.0.0-32-generic         | 46        | 0.6%    |
| 5.4.0-29-generic         | 44        | 0.57%   |
| 4.18.0-15-generic        | 44        | 0.57%   |
| 5.3.0-40-generic         | 43        | 0.56%   |
| 5.4.0-65-generic         | 42        | 0.55%   |
| 5.4.0-39-generic         | 41        | 0.53%   |
| 5.0.0-37-generic         | 41        | 0.53%   |
| 5.4.0-80-generic         | 40        | 0.52%   |
| 5.15.0-46-generic        | 40        | 0.52%   |
| 5.4.0-70-generic         | 39        | 0.51%   |
| 5.0.0-25-generic         | 39        | 0.51%   |
| 5.13.0-30-generic        | 38        | 0.49%   |
| 5.11.0-7620-generic      | 38        | 0.49%   |
| 4.18.0-16-generic        | 38        | 0.49%   |
| 5.4.0-91-generic         | 37        | 0.48%   |
| 5.4.0-37-generic         | 37        | 0.48%   |
| 4.15.0-20-generic        | 37        | 0.48%   |
| 5.15.0-52-generic        | 36        | 0.47%   |
| 5.4.0-74-generic         | 35        | 0.45%   |
| 5.3.0-51-generic         | 35        | 0.45%   |
| 5.11.0-27-generic        | 35        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1826      | 25.01%  |
| 5.8.0   | 607       | 8.31%   |
| 5.3.0   | 535       | 7.33%   |
| 4.15.0  | 514       | 7.04%   |
| 5.11.0  | 422       | 5.78%   |
| 5.15.0  | 350       | 4.79%   |
| 5.0.0   | 320       | 4.38%   |
| 5.13.0  | 267       | 3.66%   |
| 4.18.0  | 231       | 3.16%   |
| 5.10.14 | 151       | 2.07%   |
| 5.16.7  | 136       | 1.86%   |
| 5.10.0  | 113       | 1.55%   |
| 4.19.0  | 101       | 1.38%   |
| 5.19.0  | 48        | 0.66%   |
| 5.17.5  | 35        | 0.48%   |
| 5.16.11 | 29        | 0.4%    |
| 5.7.9   | 26        | 0.36%   |
| 4.4.0   | 26        | 0.36%   |
| 5.14.0  | 24        | 0.33%   |
| 5.15.15 | 20        | 0.27%   |
| 5.15.5  | 19        | 0.26%   |
| 4.9.0   | 19        | 0.26%   |
| 5.9.16  | 17        | 0.23%   |
| 5.7.0   | 17        | 0.23%   |
| 5.6.19  | 16        | 0.22%   |
| 5.3.18  | 15        | 0.21%   |
| 5.16.19 | 15        | 0.21%   |
| 5.16.15 | 15        | 0.21%   |
| 5.11.12 | 15        | 0.21%   |
| 5.18.10 | 14        | 0.19%   |
| 5.9.11  | 13        | 0.18%   |
| 5.6.0   | 13        | 0.18%   |
| 5.15.8  | 13        | 0.18%   |
| 6.0.6   | 12        | 0.16%   |
| 6.0.12  | 12        | 0.16%   |
| 5.7.10  | 12        | 0.16%   |
| 5.17.0  | 12        | 0.16%   |
| 5.13.13 | 12        | 0.16%   |
| 4.18.16 | 12        | 0.16%   |
| 6.0.0   | 11        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1897      | 26.28%  |
| 5.8     | 676       | 9.36%   |
| 5.3     | 579       | 8.02%   |
| 4.15    | 514       | 7.12%   |
| 5.15    | 504       | 6.98%   |
| 5.11    | 488       | 6.76%   |
| 5.10    | 368       | 5.1%    |
| 5.0     | 345       | 4.78%   |
| 5.13    | 321       | 4.45%   |
| 5.16    | 259       | 3.59%   |
| 4.18    | 247       | 3.42%   |
| 4.19    | 118       | 1.63%   |
| 5.7     | 101       | 1.4%    |
| 5.17    | 95        | 1.32%   |
| 5.19    | 94        | 1.3%    |
| 5.14    | 81        | 1.12%   |
| 6.0     | 76        | 1.05%   |
| 5.18    | 75        | 1.04%   |
| 5.6     | 68        | 0.94%   |
| 5.9     | 66        | 0.91%   |
| 5.12    | 61        | 0.84%   |
| 4.9     | 43        | 0.6%    |
| 5.5     | 32        | 0.44%   |
| 4.4     | 29        | 0.4%    |
| 5.1     | 28        | 0.39%   |
| 5.2     | 15        | 0.21%   |
| 4.13    | 7         | 0.1%    |
| 6.1     | 6         | 0.08%   |
| 4.20    | 5         | 0.07%   |
| 4.14    | 4         | 0.06%   |
| 4.10    | 4         | 0.06%   |
| 4.1     | 4         | 0.06%   |
| 3.10    | 3         | 0.04%   |
| 4.17    | 2         | 0.03%   |
| 6       | 1         | 0.01%   |
| 4.8     | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 6407      | 97.39%  |
| i686   | 170       | 2.58%   |
| armv7l | 2         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3421      | 49.94%  |
| Unknown         | 973       | 14.2%   |
| KDE5            | 682       | 9.96%   |
| X-Cinnamon      | 537       | 7.84%   |
| XFCE            | 429       | 6.26%   |
| MATE            | 178       | 2.6%    |
| KDE             | 159       | 2.32%   |
| Cinnamon        | 126       | 1.84%   |
| LXQt            | 66        | 0.96%   |
| Pantheon        | 54        | 0.79%   |
| Unity           | 51        | 0.74%   |
| Deepin          | 39        | 0.57%   |
| Budgie          | 37        | 0.54%   |
| LXDE            | 29        | 0.42%   |
| KDE4            | 25        | 0.36%   |
| i3              | 19        | 0.28%   |
| GNOME Classic   | 8         | 0.12%   |
| awesome         | 5         | 0.07%   |
| GNOME Flashback | 3         | 0.04%   |
| sway            | 2         | 0.03%   |
| Enlightenment   | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Openbox         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| bspwm           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 5570      | 82.62%  |
| Wayland | 656       | 9.73%   |
| Unknown | 489       | 7.25%   |
| Tty     | 27        | 0.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4478      | 65.74%  |
| GDM     | 726       | 10.66%  |
| SDDM    | 611       | 8.97%   |
| GDM3    | 353       | 5.18%   |
| LightDM | 316       | 4.64%   |
| TDM     | 292       | 4.29%   |
| KDM     | 26        | 0.38%   |
| XDM     | 5         | 0.07%   |
| SLiM    | 3         | 0.04%   |
| MDM     | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang      | Notebooks | Percent |
|-----------|-----------|---------|
| pt_BR     | 4492      | 66.9%   |
| en_US     | 1138      | 16.95%  |
| Unknown   | 911       | 13.57%  |
| C         | 88        | 1.31%   |
| en_GB     | 29        | 0.43%   |
| pt_PT     | 25        | 0.37%   |
| es_ES     | 9         | 0.13%   |
| POSIX     | 3         | 0.04%   |
| fr_FR     | 3         | 0.04%   |
| en_CA     | 3         | 0.04%   |
| de_DE     | 3         | 0.04%   |
| ja_JP     | 2         | 0.03%   |
| it_IT     | 2         | 0.03%   |
| ru_RU     | 1         | 0.01%   |
| pt_BRutf8 | 1         | 0.01%   |
| es_MX     | 1         | 0.01%   |
| es_CL     | 1         | 0.01%   |
| es_AR     | 1         | 0.01%   |
| em_US     | 1         | 0.01%   |
| ar_EG     | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3385      | 50.27%  |
| EFI  | 3349      | 49.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5391      | 80.22%  |
| Btrfs   | 424       | 6.31%   |
| Overlay | 414       | 6.16%   |
| Unknown | 386       | 5.74%   |
| Xfs     | 41        | 0.61%   |
| Zfs     | 23        | 0.34%   |
| Tmpfs   | 15        | 0.22%   |
| Ext3    | 10        | 0.15%   |
| Ext2    | 10        | 0.15%   |
| F2fs    | 4         | 0.06%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4697      | 69.75%  |
| GPT     | 1451      | 21.55%  |
| MBR     | 586       | 8.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6049      | 91.1%   |
| Yes       | 591       | 8.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5206      | 78.1%   |
| Yes       | 1460      | 21.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1510      | 22.96%  |
| Acer                   | 1310      | 19.91%  |
| Lenovo                 | 809       | 12.3%   |
| Samsung Electronics    | 560       | 8.51%   |
| Hewlett-Packard        | 448       | 6.81%   |
| Positivo               | 439       | 6.67%   |
| ASUSTek Computer       | 360       | 5.47%   |
| Sony                   | 147       | 2.23%   |
| LG Electronics         | 89        | 1.35%   |
| Apple                  | 80        | 1.22%   |
| Avell High Performance | 69        | 1.05%   |
| Digibras               | 63        | 0.96%   |
| Itautec                | 62        | 0.94%   |
| Semp Toshiba           | 61        | 0.93%   |
| Unknown                | 59        | 0.9%    |
| Intel                  | 47        | 0.71%   |
| Philco                 | 36        | 0.55%   |
| Multilaser             | 36        | 0.55%   |
| Positivo Bahia - VAIO  | 34        | 0.52%   |
| Compaq                 | 34        | 0.52%   |
| Toshiba                | 33        | 0.5%    |
| OEM                    | 31        | 0.47%   |
| Notebook               | 24        | 0.36%   |
| Clevo                  | 21        | 0.32%   |
| Gateway                | 20        | 0.3%    |
| Compal                 | 18        | 0.27%   |
| MSI                    | 15        | 0.23%   |
| Google                 | 15        | 0.23%   |
| Alienware              | 12        | 0.18%   |
| Standard               | 10        | 0.15%   |
| Quanta                 | 10        | 0.15%   |
| eMachines              | 10        | 0.15%   |
| Timi                   | 7         | 0.11%   |
| Daten Tecnologia       | 7         | 0.11%   |
| Chuwi                  | 7         | 0.11%   |
| CCE                    | 7         | 0.11%   |
| Login Informatica      | 5         | 0.08%   |
| LNV                    | 5         | 0.08%   |
| TPVAOC                 | 4         | 0.06%   |
| IDEALMAX               | 4         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 134       | 2.04%   |
| Positivo Mobile                             | 117       | 1.78%   |
| Unknown                                     | 100       | 1.52%   |
| Acer Nitro AN515-44                         | 76        | 1.16%   |
| Acer Aspire A315-53                         | 67        | 1.02%   |
| Samsung 340XAA/350XAA/550XAA                | 66        | 1%      |
| Dell Inspiron 5566                          | 58        | 0.88%   |
| Lenovo IdeaPad S145-15API 81V7              | 56        | 0.85%   |
| Dell Inspiron 3583                          | 56        | 0.85%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 52        | 0.79%   |
| Acer Aspire A315-34                         | 52        | 0.79%   |
| Acer Nitro AN517-51                         | 51        | 0.78%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 49        | 0.74%   |
| Dell Inspiron 15-3567                       | 49        | 0.74%   |
| Acer Nitro AN515-43                         | 45        | 0.68%   |
| Acer Aspire A515-51                         | 44        | 0.67%   |
| Samsung 300E5M/300E5L                       | 39        | 0.59%   |
| HP G42                                      | 39        | 0.59%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 38        | 0.58%   |
| Positivo S14CT01                            | 37        | 0.56%   |
| Dell Inspiron 3442                          | 36        | 0.55%   |
| Acer Nitro AN515-52                         | 36        | 0.55%   |
| Dell Inspiron 3421                          | 35        | 0.53%   |
| Dell Inspiron N4050                         | 34        | 0.52%   |
| Dell Inspiron 7520                          | 33        | 0.5%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 32        | 0.49%   |
| Dell Inspiron 1545                          | 32        | 0.49%   |
| HP Pavilion g4                              | 31        | 0.47%   |
| Acer Aspire E1-571                          | 31        | 0.47%   |
| Dell Inspiron 5458                          | 30        | 0.46%   |
| Samsung 550XDA                              | 29        | 0.44%   |
| Itautec Infoway                             | 28        | 0.43%   |
| Digibras NH4CU03                            | 28        | 0.43%   |
| Dell Inspiron 5437                          | 28        | 0.43%   |
| Acer Aspire E5-571                          | 28        | 0.43%   |
| Dell G3 3590                                | 27        | 0.41%   |
| Digibras NH4CU53                            | 26        | 0.4%    |
| Dell Inspiron 1525                          | 26        | 0.4%    |
| Acer Aspire A515-54G                        | 26        | 0.4%    |
| Acer Aspire A515-51G                        | 26        | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 994       | 15.11%  |
| Acer Aspire       | 848       | 12.89%  |
| Lenovo IdeaPad    | 433       | 6.58%   |
| Acer Nitro        | 375       | 5.7%    |
| Dell Vostro       | 204       | 3.1%    |
| Lenovo ThinkPad   | 184       | 2.8%    |
| HP Pavilion       | 182       | 2.77%   |
| Dell Latitude     | 161       | 2.45%   |
| Positivo Mobile   | 117       | 1.78%   |
| Unknown           | 100       | 1.52%   |
| ASUS VivoBook     | 93        | 1.41%   |
| Samsung 340XAA    | 66        | 1%      |
| Itautec Infoway   | 62        | 0.94%   |
| Dell G3           | 50        | 0.76%   |
| HP ProBook        | 46        | 0.7%    |
| Samsung RV411     | 45        | 0.68%   |
| Samsung 300E5M    | 39        | 0.59%   |
| HP G42            | 39        | 0.59%   |
| Positivo S14CT01  | 37        | 0.56%   |
| Dell System       | 37        | 0.56%   |
| HP EliteBook      | 34        | 0.52%   |
| Acer Predator     | 31        | 0.47%   |
| Semp Toshiba IS   | 30        | 0.46%   |
| Samsung 550XDA    | 29        | 0.44%   |
| Digibras NH4CU03  | 28        | 0.43%   |
| Toshiba Satellite | 27        | 0.41%   |
| Compaq Presario   | 27        | 0.41%   |
| Digibras NH4CU53  | 26        | 0.4%    |
| Samsung 550XBE    | 24        | 0.36%   |
| Samsung 270E5J    | 24        | 0.36%   |
| Samsung RV415     | 23        | 0.35%   |
| Samsung 370E4K    | 23        | 0.35%   |
| Positivo H14BT58  | 23        | 0.35%   |
| Lenovo G400s      | 23        | 0.35%   |
| Positivo Q232A    | 22        | 0.33%   |
| Dell XPS          | 22        | 0.33%   |
| Samsung 300E5EV   | 21        | 0.32%   |
| Samsung 300E4C    | 21        | 0.32%   |
| HP Compaq         | 21        | 0.32%   |
| Positivo CHT14B   | 20        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 884       | 13.44%  |
| 2012    | 696       | 10.58%  |
| 2011    | 615       | 9.35%   |
| 2018    | 557       | 8.47%   |
| 2013    | 525       | 7.98%   |
| 2017    | 494       | 7.51%   |
| 2016    | 489       | 7.43%   |
| 2010    | 415       | 6.31%   |
| 2014    | 361       | 5.49%   |
| 2020    | 359       | 5.46%   |
| 2015    | 304       | 4.62%   |
| 2021    | 245       | 3.72%   |
| 2008    | 244       | 3.71%   |
| 2009    | 213       | 3.24%   |
| 2007    | 85        | 1.29%   |
| 2006    | 34        | 0.52%   |
| Unknown | 23        | 0.35%   |
| 2022    | 22        | 0.33%   |
| 2005    | 9         | 0.14%   |
| 2004    | 4         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6578      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5598      | 84.43%  |
| Enabled  | 1032      | 15.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6561      | 99.74%  |
| Yes  | 17        | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2194      | 32.93%  |
| 3.01-4.0    | 1856      | 27.86%  |
| 8.01-16.0   | 921       | 13.82%  |
| 16.01-24.0  | 831       | 12.47%  |
| 1.01-2.0    | 506       | 7.59%   |
| 2.01-3.0    | 166       | 2.49%   |
| 32.01-64.0  | 104       | 1.56%   |
| 0.51-1.0    | 33        | 0.5%    |
| 24.01-32.0  | 30        | 0.45%   |
| 64.01-256.0 | 21        | 0.32%   |
| 0.01-0.5    | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2696      | 37.26%  |
| 2.01-3.0   | 2019      | 27.9%   |
| 3.01-4.0   | 964       | 13.32%  |
| 4.01-8.0   | 844       | 11.66%  |
| 0.51-1.0   | 506       | 6.99%   |
| 8.01-16.0  | 155       | 2.14%   |
| 0.01-0.5   | 40        | 0.55%   |
| 16.01-24.0 | 8         | 0.11%   |
| 32.01-64.0 | 2         | 0.03%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4697      | 70.22%  |
| 2      | 1802      | 26.94%  |
| 3      | 131       | 1.96%   |
| 0      | 48        | 0.72%   |
| 4      | 11        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4003      | 60.6%   |
| Yes       | 2603      | 39.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5873      | 89.11%  |
| No        | 718       | 10.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6378      | 96.77%  |
| No        | 213       | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4694      | 70.66%  |
| No        | 1949      | 29.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 6578      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 817       | 11.86%  |
| Rio de Janeiro        | 362       | 5.25%   |
| Brasília             | 217       | 3.15%   |
| Curitiba              | 203       | 2.95%   |
| Belo Horizonte        | 196       | 2.85%   |
| Fortaleza             | 161       | 2.34%   |
| Porto Alegre          | 139       | 2.02%   |
| Salvador              | 113       | 1.64%   |
| Recife                | 96        | 1.39%   |
| Campinas              | 96        | 1.39%   |
| Goiânia              | 80        | 1.16%   |
| Santo André          | 74        | 1.07%   |
| Florianópolis        | 74        | 1.07%   |
| Natal                 | 68        | 0.99%   |
| Sao Luís             | 58        | 0.84%   |
| Manaus                | 56        | 0.81%   |
| Campo Grande          | 56        | 0.81%   |
| Osasco                | 54        | 0.78%   |
| Sao José dos Campos  | 53        | 0.77%   |
| Teresina              | 48        | 0.7%    |
| Niterói              | 47        | 0.68%   |
| Belém                | 47        | 0.68%   |
| Maringá              | 46        | 0.67%   |
| Sorocaba              | 45        | 0.65%   |
| Guarulhos             | 45        | 0.65%   |
| Joao Pessoa           | 44        | 0.64%   |
| Joinville             | 41        | 0.6%    |
| Aracaju               | 41        | 0.6%    |
| Uberlândia           | 40        | 0.58%   |
| Ribeirao Preto        | 38        | 0.55%   |
| Maceió               | 38        | 0.55%   |
| Londrina              | 37        | 0.54%   |
| Sao Jose              | 36        | 0.52%   |
| Cuiabá               | 32        | 0.46%   |
| Canoas                | 31        | 0.45%   |
| Sao Carlos            | 30        | 0.44%   |
| Vitória              | 29        | 0.42%   |
| Juiz de Fora          | 29        | 0.42%   |
| Sao Bernardo do Campo | 27        | 0.39%   |
| Americana             | 27        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 1854      | 2250   | 22.81%  |
| Seagate                        | 1274      | 1515   | 15.68%  |
| Kingston                       | 763       | 918    | 9.39%   |
| Toshiba                        | 586       | 677    | 7.21%   |
| Samsung Electronics            | 582       | 749    | 7.16%   |
| SanDisk                        | 468       | 607    | 5.76%   |
| Unknown                        | 357       | 475    | 4.39%   |
| A-DATA Technology              | 318       | 401    | 3.91%   |
| Intel                          | 259       | 309    | 3.19%   |
| Hitachi                        | 187       | 227    | 2.3%    |
| Crucial                        | 140       | 190    | 1.72%   |
| ADATA Technology               | 130       | 154    | 1.6%    |
| China                          | 128       | 156    | 1.57%   |
| SK hynix                       | 101       | 128    | 1.24%   |
| LITEON                         | 101       | 120    | 1.24%   |
| HGST                           | 96        | 115    | 1.18%   |
| Silicon Motion                 | 59        | 69     | 0.73%   |
| KingSpec                       | 50        | 56     | 0.62%   |
| Fujitsu                        | 42        | 49     | 0.52%   |
| JMicron Technology             | 35        | 41     | 0.43%   |
| Lexar                          | 33        | 42     | 0.41%   |
| Apple                          | 31        | 38     | 0.38%   |
| Solid State Storage Technology | 30        | 40     | 0.37%   |
| Phison                         | 29        | 31     | 0.36%   |
| SSSTC                          | 27        | 28     | 0.33%   |
| KIOXIA                         | 26        | 30     | 0.32%   |
| Corsair                        | 24        | 24     | 0.3%    |
| Netac                          | 21        | 23     | 0.26%   |
| Solid State Storage            | 20        | 21     | 0.25%   |
| Realtek Semiconductor          | 20        | 26     | 0.25%   |
| PNY                            | 19        | 26     | 0.23%   |
| Unknown                        | 19        | 19     | 0.23%   |
| Smart                          | 17        | 19     | 0.21%   |
| Micron Technology              | 17        | 18     | 0.21%   |
| Patriot                        | 15        | 18     | 0.18%   |
| Hewlett-Packard                | 15        | 18     | 0.18%   |
| XPG                            | 14        | 17     | 0.17%   |
| Micron/Crucial Technology      | 13        | 14     | 0.16%   |
| LITEONIT                       | 13        | 19     | 0.16%   |
| KingDian                       | 13        | 19     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 457       | 5.47%   |
| Kingston SA400S37240G 240GB SSD     | 271       | 3.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 249       | 2.98%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 208       | 2.49%   |
| Kingston SA400S37480G 480GB SSD     | 137       | 1.64%   |
| Toshiba MQ01ABD100 1TB              | 132       | 1.58%   |
| Kingston SA400S37120G 120GB SSD     | 122       | 1.46%   |
| WDC WD10SPZX-24Z10 1TB              | 118       | 1.41%   |
| Unknown MMC Card  32GB              | 112       | 1.34%   |
| Intel NVMe SSD Drive 512GB          | 98        | 1.17%   |
| Seagate ST1000LM035-1RK172 1TB      | 93        | 1.11%   |
| WDC WD10JPVX-22JC3T0 1TB            | 92        | 1.1%    |
| A-DATA IM2S3338-128GD2 128GB SSD    | 87        | 1.04%   |
| WDC WD10SPZX-75Z10T2 1TB            | 76        | 0.91%   |
| Samsung HM321HI 320GB               | 75        | 0.9%    |
| Seagate ST9500325AS 500GB           | 72        | 0.86%   |
| Intel SSDPEKKW256G7 256GB           | 70        | 0.84%   |
| SanDisk NVMe SSD Drive 512GB        | 69        | 0.83%   |
| Toshiba MQ04ABF100 1TB              | 67        | 0.8%    |
| ADATA NVMe SSD Drive 256GB          | 67        | 0.8%    |
| SanDisk SSD PLUS 240GB              | 65        | 0.78%   |
| Kingston SV300S37A120G 120GB SSD    | 58        | 0.69%   |
| WDC WD10JPVX-75JC3T0 1TB            | 57        | 0.68%   |
| Toshiba MQ01ABF050 500GB            | 56        | 0.67%   |
| SanDisk SSD PLUS 120GB              | 56        | 0.67%   |
| Seagate Expansion 4TB               | 55        | 0.66%   |
| Seagate ST2000LM007-1R8174 2TB      | 53        | 0.63%   |
| Seagate ST500LT012-9WS142 500GB     | 51        | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 50        | 0.6%    |
| Seagate ST320LM001 HN-M320MBB 320GB | 49        | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 47        | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 42        | 0.5%    |
| WDC WD10JPCX-24UE4T0 1TB            | 42        | 0.5%    |
| Intel NVMe SSD Drive 256GB          | 40        | 0.48%   |
| WDC WD10SPZX-75Z10T1 1TB            | 39        | 0.47%   |
| Seagate ST1000LM014-1EJ164 1TB      | 39        | 0.47%   |
| Toshiba MQ01ABD050 500GB            | 38        | 0.46%   |
| Crucial CT240BX500SSD1 240GB        | 38        | 0.46%   |
| SanDisk SDSSDA240G 240GB            | 37        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB     | 35        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1664      | 1950   | 40.41%  |
| Seagate             | 1267      | 1505   | 30.77%  |
| Toshiba             | 555       | 641    | 13.48%  |
| Samsung Electronics | 267       | 308    | 6.48%   |
| Hitachi             | 187       | 227    | 4.54%   |
| HGST                | 96        | 115    | 2.33%   |
| Fujitsu             | 41        | 47     | 1%      |
| Unknown             | 17        | 20     | 0.41%   |
| Apple               | 11        | 14     | 0.27%   |
| SAGE                | 4         | 6      | 0.1%    |
| JMicron Technology  | 3         | 3      | 0.07%   |
| Maxtor 6            | 1         | 1      | 0.02%   |
| Maxtor              | 1         | 1      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 2      | 0.02%   |
| CLOVER              | 1         | 1      | 0.02%   |
| ASMT                | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 733       | 873    | 30.25%  |
| SanDisk             | 317       | 435    | 13.08%  |
| Samsung Electronics | 212       | 290    | 8.75%   |
| WDC                 | 185       | 227    | 7.64%   |
| A-DATA Technology   | 180       | 219    | 7.43%   |
| Crucial             | 132       | 179    | 5.45%   |
| China               | 128       | 156    | 5.28%   |
| LITEON              | 92        | 111    | 3.8%    |
| KingSpec            | 49        | 55     | 2.02%   |
| Lexar               | 32        | 41     | 1.32%   |
| JMicron Technology  | 27        | 33     | 1.11%   |
| Intel               | 22        | 26     | 0.91%   |
| Netac               | 20        | 22     | 0.83%   |
| PNY                 | 19        | 26     | 0.78%   |
| Corsair             | 19        | 19     | 0.78%   |
| Apple               | 19        | 22     | 0.78%   |
| Smart               | 17        | 19     | 0.7%    |
| SK hynix            | 14        | 17     | 0.58%   |
| Patriot             | 14        | 17     | 0.58%   |
| Unknown             | 13        | 14     | 0.54%   |
| LITEONIT            | 13        | 19     | 0.54%   |
| KingDian            | 12        | 18     | 0.5%    |
| Gigabyte Technology | 12        | 16     | 0.5%    |
| Unknown             | 12        | 12     | 0.5%    |
| Hewlett-Packard     | 11        | 13     | 0.45%   |
| Toshiba             | 8         | 9      | 0.33%   |
| Micron Technology   | 8         | 9      | 0.33%   |
| Seagate             | 7         | 7      | 0.29%   |
| BHT                 | 6         | 6      | 0.25%   |
| BIWIN               | 5         | 5      | 0.21%   |
| XrayDisk            | 4         | 5      | 0.17%   |
| Win Memory          | 4         | 5      | 0.17%   |
| S3+                 | 4         | 4      | 0.17%   |
| Maxtor              | 4         | 4      | 0.17%   |
| walram              | 3         | 3      | 0.12%   |
| Vaseky              | 3         | 3      | 0.12%   |
| Transcend           | 3         | 3      | 0.12%   |
| RZX                 | 3         | 4      | 0.12%   |
| Plextor             | 3         | 3      | 0.12%   |
| OCZ                 | 3         | 3      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4048      | 4843   | 51.33%  |
| SSD     | 2263      | 3009   | 28.7%   |
| NVMe    | 1229      | 1580   | 15.58%  |
| MMC     | 287       | 403    | 3.64%   |
| Unknown | 59        | 71     | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5585      | 7721   | 76.95%  |
| NVMe | 1228      | 1579   | 16.92%  |
| MMC  | 287       | 403    | 3.95%   |
| SAS  | 158       | 203    | 2.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3935      | 5172   | 63.84%  |
| 0.51-1.0   | 2057      | 2468   | 33.37%  |
| 1.01-2.0   | 109       | 132    | 1.77%   |
| 3.01-4.0   | 58        | 74     | 0.94%   |
| 4.01-10.0  | 5         | 6      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2060      | 29.88%  |
| 251-500        | 1779      | 25.81%  |
| 501-1000       | 1262      | 18.31%  |
| 1-20           | 471       | 6.83%   |
| 51-100         | 417       | 6.05%   |
| 1001-2000      | 360       | 5.22%   |
| 21-50          | 340       | 4.93%   |
| Unknown        | 94        | 1.36%   |
| 2001-3000      | 61        | 0.88%   |
| More than 3000 | 50        | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2723      | 38.07%  |
| 21-50          | 1699      | 23.75%  |
| 51-100         | 950       | 13.28%  |
| 101-250        | 932       | 13.03%  |
| 251-500        | 455       | 6.36%   |
| 501-1000       | 210       | 2.94%   |
| Unknown        | 94        | 1.31%   |
| 1001-2000      | 74        | 1.03%   |
| 2001-3000      | 9         | 0.13%   |
| More than 3000 | 7         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 29        | 31     | 6.76%   |
| Seagate ST9500325AS 500GB           | 21        | 23     | 4.9%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 16        | 18     | 3.73%   |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 12     | 2.8%    |
| Toshiba MQ01ABD100 1TB              | 11        | 11     | 2.56%   |
| Seagate ST500LT012-9WS142 500GB     | 9         | 11     | 2.1%    |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 1.63%   |
| Toshiba MQ02ABD100H 1TB             | 6         | 9      | 1.4%    |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 1.4%    |
| Seagate ST9320325AS 320GB           | 6         | 6      | 1.4%    |
| Kingston SV300S37A120G 120GB SSD    | 6         | 7      | 1.4%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 5         | 5      | 1.17%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 5         | 6      | 1.17%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 1.17%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 1.17%   |
| Samsung Electronics HM321HI 320GB   | 5         | 5      | 1.17%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 5      | 1.17%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 1.17%   |
| WDC WD10JPCX-24UE4T0 1TB            | 4         | 4      | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB      | 4         | 4      | 0.93%   |
| Seagate ST1000LM014-1EJ164 1TB      | 4         | 4      | 0.93%   |
| SanDisk SSD PLUS 480GB              | 4         | 4      | 0.93%   |
| Samsung Electronics HM160HI 160GB   | 4         | 4      | 0.93%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 4      | 0.93%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 3         | 3      | 0.7%    |
| WDC WD3200BPVT-24JJ5T0 320GB        | 3         | 3      | 0.7%    |
| WDC WD3200BPVT-00JJ5T0 320GB        | 3         | 5      | 0.7%    |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 4      | 0.7%    |
| WDC WD10SPZX-24Z10 1TB              | 3         | 3      | 0.7%    |
| Toshiba MQ01ACF050 500GB            | 3         | 3      | 0.7%    |
| Toshiba MQ01ABD032 320GB            | 3         | 3      | 0.7%    |
| Toshiba MK5061GSYN 500GB            | 3         | 3      | 0.7%    |
| Toshiba MK3259GSXP 320GB            | 3         | 3      | 0.7%    |
| Seagate ST9500423AS 500GB           | 3         | 3      | 0.7%    |
| Seagate ST9320423AS 320GB           | 3         | 3      | 0.7%    |
| Seagate ST9250410AS 250GB           | 3         | 3      | 0.7%    |
| Seagate ST9160314AS 160GB           | 3         | 4      | 0.7%    |
| Seagate ST500LM030-2E717D 500GB     | 3         | 3      | 0.7%    |
| Seagate ST320LM001 HN-M320MBB 320GB | 3         | 3      | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB      | 3         | 3      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 150       | 162    | 35.29%  |
| WDC                 | 76        | 85     | 17.88%  |
| Toshiba             | 67        | 73     | 15.76%  |
| Hitachi             | 27        | 29     | 6.35%   |
| Samsung Electronics | 25        | 33     | 5.88%   |
| Kingston            | 22        | 26     | 5.18%   |
| SanDisk             | 11        | 11     | 2.59%   |
| China               | 8         | 9      | 1.88%   |
| HGST                | 7         | 7      | 1.65%   |
| A-DATA Technology   | 7         | 7      | 1.65%   |
| Fujitsu             | 4         | 5      | 0.94%   |
| PNY                 | 3         | 5      | 0.71%   |
| Intel               | 3         | 3      | 0.71%   |
| walram              | 2         | 2      | 0.47%   |
| LITEON              | 2         | 2      | 0.47%   |
| Crucial             | 2         | 2      | 0.47%   |
| Apple               | 2         | 2      | 0.47%   |
| XPG                 | 1         | 1      | 0.24%   |
| SK hynix            | 1         | 1      | 0.24%   |
| ShiJi               | 1         | 1      | 0.24%   |
| OCZ                 | 1         | 1      | 0.24%   |
| Micron Technology   | 1         | 1      | 0.24%   |
| LITEONIT            | 1         | 2      | 0.24%   |
| KingSpec            | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 150       | 162    | 43.35%  |
| WDC                 | 70        | 79     | 20.23%  |
| Toshiba             | 66        | 72     | 19.08%  |
| Hitachi             | 27        | 29     | 7.8%    |
| Samsung Electronics | 21        | 29     | 6.07%   |
| HGST                | 7         | 7      | 2.02%   |
| Fujitsu             | 4         | 5      | 1.16%   |
| Apple               | 1         | 1      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 345       | 384    | 81.37%  |
| SSD  | 69        | 77     | 16.27%  |
| NVMe | 10        | 10     | 2.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 18.18%  |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 9.09%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 9.09%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 9.09%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 9.09%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 36.36%  |
| WDC                 | 2         | 2      | 18.18%  |
| Toshiba             | 2         | 2      | 18.18%  |
| Seagate             | 2         | 2      | 18.18%  |
| Maxtor              | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4855      | 7245   | 70.83%  |
| Works    | 1571      | 2179   | 22.92%  |
| Malfunc  | 417       | 471    | 6.08%   |
| Failed   | 11        | 11     | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5510      | 75.48%  |
| AMD                              | 595       | 8.15%   |
| ADATA Technology                 | 280       | 3.84%   |
| SanDisk                          | 180       | 2.47%   |
| Samsung Electronics              | 124       | 1.7%    |
| Silicon Integrated Systems [SiS] | 94        | 1.29%   |
| Solid State Storage Technology   | 90        | 1.23%   |
| SK hynix                         | 82        | 1.12%   |
| Silicon Motion                   | 67        | 0.92%   |
| Phison Electronics               | 38        | 0.52%   |
| Kingston Technology Company      | 37        | 0.51%   |
| Realtek Semiconductor            | 32        | 0.44%   |
| Nvidia                           | 32        | 0.44%   |
| KIOXIA                           | 25        | 0.34%   |
| VIA Technologies                 | 24        | 0.33%   |
| Toshiba America Info Systems     | 22        | 0.3%    |
| Micron/Crucial Technology        | 20        | 0.27%   |
| Lite-On Technology               | 18        | 0.25%   |
| Micron Technology                | 9         | 0.12%   |
| Union Memory (Shenzhen)          | 5         | 0.07%   |
| Marvell Technology Group         | 5         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.04%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| Apple                            | 2         | 0.03%   |
| Seagate Technology               | 1         | 0.01%   |
| Netac Technology                 | 1         | 0.01%   |
| Lenovo                           | 1         | 0.01%   |
| Beijing Starblaze Technology     | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 910       | 11.29%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 760       | 9.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 596       | 7.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 425       | 5.27%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 423       | 5.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 357       | 4.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 293       | 3.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 289       | 3.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 228       | 2.83%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 202       | 2.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 191       | 2.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 140       | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 131       | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 125       | 1.55%   |
| ADATA Non-Volatile memory controller                                             | 122       | 1.51%   |
| Intel Comet Lake SATA AHCI Controller                                            | 117       | 1.45%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                      | 116       | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 115       | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 115       | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 112       | 1.39%   |
| Intel Tiger Lake-LP SATA Controller                                              | 99        | 1.23%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 93        | 1.15%   |
| Solid State Storage Non-Volatile memory controller                               | 90        | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 89        | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 87        | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 82        | 1.02%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 77        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 71        | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 70        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 67        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 64        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 63        | 0.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 59        | 0.73%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 55        | 0.68%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 55        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 45        | 0.56%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 44        | 0.55%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 43        | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 42        | 0.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 33        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5377      | 69.35%  |
| NVMe | 1233      | 15.9%   |
| RAID | 607       | 7.83%   |
| IDE  | 536       | 6.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 5936      | 90.24%  |
| AMD    | 640       | 9.73%   |
| ARM    | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 231       | 3.51%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 159       | 2.42%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 140       | 2.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 124       | 1.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 123       | 1.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 122       | 1.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 119       | 1.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 117       | 1.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 113       | 1.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 107       | 1.63%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 89        | 1.35%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 89        | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 86        | 1.31%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 86        | 1.31%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 85        | 1.29%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 83        | 1.26%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 80        | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 78        | 1.19%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 76        | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 76        | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 75        | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 72        | 1.09%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 72        | 1.09%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 71        | 1.08%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 71        | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 68        | 1.03%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 63        | 0.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 62        | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 61        | 0.93%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 61        | 0.93%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 59        | 0.9%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 57        | 0.87%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 56        | 0.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 55        | 0.84%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 54        | 0.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 53        | 0.81%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 52        | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 52        | 0.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 49        | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 48        | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 1961      | 29.81%  |
| Intel Core i7                  | 1359      | 20.66%  |
| Intel Core i3                  | 1028      | 15.63%  |
| Intel Celeron                  | 495       | 7.52%   |
| Intel Core 2 Duo               | 252       | 3.83%   |
| Intel Atom                     | 233       | 3.54%   |
| Other                          | 197       | 2.99%   |
| AMD Ryzen 5                    | 153       | 2.33%   |
| AMD Ryzen 7                    | 144       | 2.19%   |
| Intel Pentium Dual-Core        | 134       | 2.04%   |
| Intel Pentium                  | 127       | 1.93%   |
| Intel Pentium Dual             | 70        | 1.06%   |
| AMD E                          | 46        | 0.7%    |
| AMD C-60                       | 37        | 0.56%   |
| AMD E1                         | 31        | 0.47%   |
| AMD A4                         | 27        | 0.41%   |
| Intel Genuine                  | 26        | 0.4%    |
| AMD A6                         | 24        | 0.36%   |
| AMD C-70                       | 21        | 0.32%   |
| AMD A10                        | 20        | 0.3%    |
| Intel Core 2                   | 18        | 0.27%   |
| Intel Celeron Dual-Core        | 15        | 0.23%   |
| AMD C-50                       | 15        | 0.23%   |
| AMD Ryzen 3                    | 12        | 0.18%   |
| AMD Mobile Sempron             | 12        | 0.18%   |
| Intel Celeron M                | 11        | 0.17%   |
| AMD A12                        | 11        | 0.17%   |
| AMD Athlon II                  | 9         | 0.14%   |
| AMD Ryzen 9                    | 7         | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 6         | 0.09%   |
| AMD Turion 64 Mobile           | 6         | 0.09%   |
| AMD Turion II                  | 5         | 0.08%   |
| AMD Turion 64 X2 Mobile        | 5         | 0.08%   |
| AMD Phenom II                  | 5         | 0.08%   |
| Intel Pentium M                | 4         | 0.06%   |
| Intel Pentium Gold             | 4         | 0.06%   |
| AMD Ryzen 7 PRO                | 4         | 0.06%   |
| AMD Athlon 64 X2               | 4         | 0.06%   |
| AMD A8                         | 4         | 0.06%   |
| AMD V120                       | 3         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4219      | 64.12%  |
| 4       | 1834      | 27.87%  |
| 6       | 252       | 3.83%   |
| 1       | 143       | 2.17%   |
| 8       | 116       | 1.76%   |
| 14      | 5         | 0.08%   |
| Unknown | 3         | 0.05%   |
| 12      | 2         | 0.03%   |
| 10      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 3       | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6578      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4943      | 75.11%  |
| 1       | 1634      | 24.83%  |
| Unknown | 3         | 0.05%   |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6261      | 94.65%  |
| Unknown        | 295       | 4.46%   |
| 32-bit         | 44        | 0.67%   |
| 64-bit         | 15        | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1226      | 18.03%  |
| 0x306a9    | 576       | 8.47%   |
| 0x206a7    | 562       | 8.26%   |
| 0x806e9    | 363       | 5.34%   |
| 0x40651    | 323       | 4.75%   |
| 0x806ec    | 303       | 4.46%   |
| 0x906ea    | 289       | 4.25%   |
| 0x20655    | 284       | 4.18%   |
| 0x306d4    | 262       | 3.85%   |
| 0x406e3    | 261       | 3.84%   |
| 0x1067a    | 250       | 3.68%   |
| 0x806ea    | 241       | 3.54%   |
| 0x406c4    | 141       | 2.07%   |
| 0x6fd      | 139       | 2.04%   |
| 0x806c1    | 136       | 2%      |
| 0x05000119 | 84        | 1.24%   |
| 0x906e9    | 82        | 1.21%   |
| 0x30678    | 82        | 1.21%   |
| 0x08600103 | 76        | 1.12%   |
| 0x08108109 | 69        | 1.01%   |
| 0x706e5    | 60        | 0.88%   |
| 0x906ed    | 58        | 0.85%   |
| 0x08108102 | 58        | 0.85%   |
| 0x706a1    | 57        | 0.84%   |
| 0x306c3    | 53        | 0.78%   |
| 0x20652    | 48        | 0.71%   |
| 0x806eb    | 47        | 0.69%   |
| 0x406c3    | 47        | 0.69%   |
| 0x706a8    | 45        | 0.66%   |
| 0x106ca    | 45        | 0.66%   |
| 0xa0652    | 42        | 0.62%   |
| 0x10676    | 32        | 0.47%   |
| 0x30661    | 31        | 0.46%   |
| 0x506c9    | 27        | 0.4%    |
| 0x05000029 | 27        | 0.4%    |
| 0x03000027 | 27        | 0.4%    |
| 0x506e3    | 24        | 0.35%   |
| 0x10661    | 24        | 0.35%   |
| 0x0810100b | 21        | 0.31%   |
| 0x0700010f | 19        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1645      | 25%     |
| IvyBridge        | 685       | 10.41%  |
| SandyBridge      | 651       | 9.9%    |
| Haswell          | 441       | 6.7%    |
| Westmere         | 390       | 5.93%   |
| Skylake          | 332       | 5.05%   |
| Penryn           | 330       | 5.02%   |
| Silvermont       | 323       | 4.91%   |
| Broadwell        | 303       | 4.61%   |
| Core             | 214       | 3.25%   |
| TigerLake        | 170       | 2.58%   |
| Zen+             | 162       | 2.46%   |
| Bobcat           | 139       | 2.11%   |
| Goldmont plus    | 113       | 1.72%   |
| Bonnell          | 93        | 1.41%   |
| IceLake          | 86        | 1.31%   |
| Zen 2            | 84        | 1.28%   |
| CometLake        | 70        | 1.06%   |
| Unknown          | 49        | 0.74%   |
| K8 Hammer        | 39        | 0.59%   |
| Excavator        | 36        | 0.55%   |
| Goldmont         | 33        | 0.5%    |
| K10 Llano        | 31        | 0.47%   |
| Zen              | 29        | 0.44%   |
| K10              | 27        | 0.41%   |
| P6               | 24        | 0.36%   |
| Jaguar           | 21        | 0.32%   |
| Zen 3            | 16        | 0.24%   |
| Nehalem          | 12        | 0.18%   |
| K8 & K10 hybrid  | 10        | 0.15%   |
| Piledriver       | 8         | 0.12%   |
| Alderlake Hybrid | 6         | 0.09%   |
| Puma             | 4         | 0.06%   |
| Steamroller      | 2         | 0.03%   |
| NetBurst         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5684      | 66.48%  |
| Nvidia                           | 1726      | 20.19%  |
| AMD                              | 1022      | 11.95%  |
| Silicon Integrated Systems [SiS] | 94        | 1.1%    |
| VIA Technologies                 | 24        | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 677       | 7.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 640       | 7.29%   |
| Intel HD Graphics 620                                                                    | 452       | 5.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 374       | 4.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 365       | 4.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 364       | 4.15%   |
| Intel HD Graphics 5500                                                                   | 285       | 3.25%   |
| Intel UHD Graphics 620                                                                   | 275       | 3.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 272       | 3.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 262       | 2.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 257       | 2.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 241       | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 224       | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 161       | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 156       | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 144       | 1.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 140       | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 128       | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 128       | 1.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 113       | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 99        | 1.13%   |
| Intel HD Graphics 630                                                                    | 97        | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                                            | 93        | 1.06%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 91        | 1.04%   |
| Nvidia TU117M                                                                            | 89        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 87        | 0.99%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 86        | 0.98%   |
| AMD Renoir                                                                               | 83        | 0.95%   |
| Nvidia GM108M [GeForce MX110]                                                            | 82        | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 82        | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 65        | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 65        | 0.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 64        | 0.73%   |
| Nvidia GP108M [GeForce MX250]                                                            | 53        | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 50        | 0.57%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 49        | 0.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 43        | 0.49%   |
| Nvidia GP108M [GeForce MX230]                                                            | 42        | 0.48%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 42        | 0.48%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 39        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 3851      | 58.45%  |
| Intel + Nvidia | 1472      | 22.34%  |
| 1 x AMD        | 454       | 6.89%   |
| Intel + AMD    | 365       | 5.54%   |
| AMD + Nvidia   | 134       | 2.03%   |
| 1 x Nvidia     | 119       | 1.81%   |
| 1 x SiS        | 94        | 1.43%   |
| 2 x AMD        | 68        | 1.03%   |
| 1 x VIA        | 24        | 0.36%   |
| Other          | 4         | 0.06%   |
| 2 x Intel      | 3         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5353      | 80.65%  |
| Proprietary | 1085      | 16.35%  |
| Unknown     | 199       | 3%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4638      | 69.14%  |
| 1.01-2.0   | 975       | 14.53%  |
| 0.01-0.5   | 485       | 7.23%   |
| 3.01-4.0   | 354       | 5.28%   |
| 0.51-1.0   | 166       | 2.47%   |
| 5.01-6.0   | 63        | 0.94%   |
| 2.01-3.0   | 15        | 0.22%   |
| 7.01-8.0   | 11        | 0.16%   |
| 8.01-16.0  | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1448      | 19.2%   |
| BOE                     | 1379      | 18.29%  |
| Chimei Innolux          | 1073      | 14.23%  |
| LG Display              | 1055      | 13.99%  |
| Samsung Electronics     | 775       | 10.28%  |
| Goldstar                | 396       | 5.25%   |
| Dell                    | 152       | 2.02%   |
| AOC                     | 152       | 2.02%   |
| Chi Mei Optoelectronics | 143       | 1.9%    |
| InfoVision              | 115       | 1.52%   |
| PANDA                   | 104       | 1.38%   |
| Philips                 | 89        | 1.18%   |
| Apple                   | 78        | 1.03%   |
| Lenovo                  | 56        | 0.74%   |
| HannStar                | 47        | 0.62%   |
| CPT                     | 46        | 0.61%   |
| Acer                    | 46        | 0.61%   |
| LG Philips              | 34        | 0.45%   |
| Sony                    | 32        | 0.42%   |
| InnoLux Display         | 28        | 0.37%   |
| Hewlett-Packard         | 28        | 0.37%   |
| SLD                     | 22        | 0.29%   |
| Sharp                   | 21        | 0.28%   |
| MTD                     | 17        | 0.23%   |
| Panasonic               | 13        | 0.17%   |
| KDC                     | 11        | 0.15%   |
| BenQ                    | 10        | 0.13%   |
| Toshiba                 | 9         | 0.12%   |
| SKY                     | 9         | 0.12%   |
| Unknown                 | 8         | 0.11%   |
| STA                     | 8         | 0.11%   |
| ASUSTek Computer        | 8         | 0.11%   |
| NCS                     | 7         | 0.09%   |
| GDH                     | 7         | 0.09%   |
| RTK                     | 6         | 0.08%   |
| MStar                   | 6         | 0.08%   |
| HB@                     | 6         | 0.08%   |
| AGO                     | 6         | 0.08%   |
| Unknown (XXX)           | 5         | 0.07%   |
| Quanta Display          | 5         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 113       | 1.49%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 105       | 1.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 104       | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 99        | 1.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 99        | 1.31%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 96        | 1.27%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch          | 96        | 1.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 93        | 1.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 78        | 1.03%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 73        | 0.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 71        | 0.94%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 65        | 0.86%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 64        | 0.84%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 62        | 0.82%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 61        | 0.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 60        | 0.79%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 57        | 0.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 55        | 0.73%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.71%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 54        | 0.71%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 54        | 0.71%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 53        | 0.7%    |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 50        | 0.66%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 50        | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 49        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 48        | 0.63%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 44        | 0.58%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 44        | 0.58%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 41        | 0.54%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 41        | 0.54%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 40        | 0.53%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 40        | 0.53%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 39        | 0.51%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 39        | 0.51%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 39        | 0.51%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch        | 37        | 0.49%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 35        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 35        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 35        | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 34        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3994      | 55.53%  |
| 1920x1080 (FHD)    | 2088      | 29.03%  |
| 1280x800 (WXGA)    | 278       | 3.86%   |
| 1600x900 (HD+)     | 158       | 2.2%    |
| 2560x1080          | 143       | 1.99%   |
| 3840x2160 (4K)     | 93        | 1.29%   |
| 1440x900 (WXGA+)   | 90        | 1.25%   |
| 1360x768           | 66        | 0.92%   |
| 1920x1200 (WUXGA)  | 44        | 0.61%   |
| 2560x1440 (QHD)    | 40        | 0.56%   |
| 1024x600           | 39        | 0.54%   |
| 1680x1050 (WSXGA+) | 28        | 0.39%   |
| 1280x1024 (SXGA)   | 28        | 0.39%   |
| 1024x768 (XGA)     | 21        | 0.29%   |
| 1920x540           | 15        | 0.21%   |
| 1280x720 (HD)      | 10        | 0.14%   |
| 2560x1600          | 8         | 0.11%   |
| 2288x1287          | 8         | 0.11%   |
| Unknown            | 7         | 0.1%    |
| 3840x2400          | 3         | 0.04%   |
| 3840x1080          | 3         | 0.04%   |
| 3200x1800 (QHD+)   | 3         | 0.04%   |
| 2880x1800          | 3         | 0.04%   |
| 1280x960           | 3         | 0.04%   |
| 800x1280           | 2         | 0.03%   |
| 4240x1080          | 1         | 0.01%   |
| 3600x1080          | 1         | 0.01%   |
| 3440x1440          | 1         | 0.01%   |
| 3286x1080          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |
| 2304x1440          | 1         | 0.01%   |
| 2256x1504          | 1         | 0.01%   |
| 2160x1440          | 1         | 0.01%   |
| 2160x1350          | 1         | 0.01%   |
| 1792x768           | 1         | 0.01%   |
| 1680x945           | 1         | 0.01%   |
| 1600x1200          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3260      | 43.3%   |
| 14      | 1417      | 18.82%  |
| 13      | 1212      | 16.1%   |
| 21      | 223       | 2.96%   |
| 23      | 199       | 2.64%   |
| 17      | 166       | 2.2%    |
| 18      | 157       | 2.09%   |
| 34      | 134       | 1.78%   |
| 11      | 106       | 1.41%   |
| 24      | 98        | 1.3%    |
| 27      | 88        | 1.17%   |
| 12      | 53        | 0.7%    |
| 31      | 52        | 0.69%   |
| Unknown | 45        | 0.6%    |
| 20      | 44        | 0.58%   |
| 10      | 44        | 0.58%   |
| 19      | 42        | 0.56%   |
| 40      | 24        | 0.32%   |
| 72      | 18        | 0.24%   |
| 32      | 18        | 0.24%   |
| 22      | 16        | 0.21%   |
| 28      | 15        | 0.2%    |
| 54      | 14        | 0.19%   |
| 52      | 14        | 0.19%   |
| 16      | 14        | 0.19%   |
| 84      | 13        | 0.17%   |
| 47      | 8         | 0.11%   |
| 46      | 7         | 0.09%   |
| 37      | 6         | 0.08%   |
| 26      | 4         | 0.05%   |
| 58      | 3         | 0.04%   |
| 48      | 3         | 0.04%   |
| 65      | 2         | 0.03%   |
| 7       | 2         | 0.03%   |
| 142     | 1         | 0.01%   |
| 60      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |
| 55      | 1         | 0.01%   |
| 49      | 1         | 0.01%   |
| 42      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5592      | 74.85%  |
| 401-500        | 475       | 6.36%   |
| 201-300        | 378       | 5.06%   |
| 501-600        | 371       | 4.97%   |
| 351-400        | 262       | 3.51%   |
| 701-800        | 152       | 2.03%   |
| 601-700        | 74        | 0.99%   |
| 1001-1500      | 55        | 0.74%   |
| Unknown        | 45        | 0.6%    |
| 801-900        | 31        | 0.41%   |
| 1501-2000      | 31        | 0.41%   |
| 901-1000       | 2         | 0.03%   |
| 1-100          | 2         | 0.03%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5892      | 89.1%   |
| 16/10   | 469       | 7.09%   |
| 21/9    | 145       | 2.19%   |
| 4/3     | 39        | 0.59%   |
| 5/4     | 29        | 0.44%   |
| Unknown | 21        | 0.32%   |
| 3/2     | 13        | 0.2%    |
| 32/9    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 1.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3241      | 43.1%   |
| 81-90          | 2494      | 33.16%  |
| 201-250        | 463       | 6.16%   |
| 351-500        | 208       | 2.77%   |
| 151-200        | 160       | 2.13%   |
| 141-150        | 158       | 2.1%    |
| 71-80          | 131       | 1.74%   |
| 121-130        | 120       | 1.6%    |
| 51-60          | 106       | 1.41%   |
| 301-350        | 89        | 1.18%   |
| More than 1000 | 70        | 0.93%   |
| 501-1000       | 50        | 0.66%   |
| Unknown        | 45        | 0.6%    |
| 41-50          | 44        | 0.59%   |
| 61-70          | 40        | 0.53%   |
| 91-100         | 34        | 0.45%   |
| 251-300        | 29        | 0.39%   |
| 131-140        | 25        | 0.33%   |
| 111-120        | 11        | 0.15%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 4108      | 55.91%  |
| 121-160       | 1852      | 25.2%   |
| 51-100        | 1114      | 15.16%  |
| 1-50          | 108       | 1.47%   |
| 161-240       | 103       | 1.4%    |
| Unknown       | 45        | 0.61%   |
| More than 240 | 18        | 0.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5306      | 78.7%   |
| 2     | 1188      | 17.62%  |
| 0     | 189       | 2.8%    |
| 3     | 57        | 0.85%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4792      | 41.48%  |
| Qualcomm Atheros                  | 2949      | 25.53%  |
| Intel                             | 2042      | 17.68%  |
| Broadcom                          | 641       | 5.55%   |
| JMicron Technology                | 180       | 1.56%   |
| Marvell Technology Group          | 176       | 1.52%   |
| Broadcom Limited                  | 141       | 1.22%   |
| Ralink                            | 122       | 1.06%   |
| Silicon Integrated Systems [SiS]  | 94        | 0.81%   |
| Ralink Technology                 | 81        | 0.7%    |
| TP-Link                           | 51        | 0.44%   |
| Samsung Electronics               | 43        | 0.37%   |
| Motorola PCS                      | 30        | 0.26%   |
| VIA Technologies                  | 24        | 0.21%   |
| ASIX Electronics                  | 24        | 0.21%   |
| Qualcomm Atheros Communications   | 23        | 0.2%    |
| Nvidia                            | 22        | 0.19%   |
| Xiaomi                            | 20        | 0.17%   |
| D-Link                            | 14        | 0.12%   |
| MediaTek                          | 11        | 0.1%    |
| ICS Advent                        | 10        | 0.09%   |
| D-Link System                     | 7         | 0.06%   |
| DisplayLink                       | 6         | 0.05%   |
| Lenovo                            | 5         | 0.04%   |
| Attansic Technology               | 4         | 0.03%   |
| LG Electronics                    | 3         | 0.03%   |
| Huawei Technologies               | 3         | 0.03%   |
| Ericsson Business Mobile Networks | 3         | 0.03%   |
| Dell                              | 3         | 0.03%   |
| AMD                               | 3         | 0.03%   |
| OPPO Electronics                  | 2         | 0.02%   |
| NetGear                           | 2         | 0.02%   |
| Microsoft                         | 2         | 0.02%   |
| Micro Star International          | 2         | 0.02%   |
| Edimax Technology                 | 2         | 0.02%   |
| ASUSTek Computer                  | 2         | 0.02%   |
| Arduino SA                        | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| Sierra Wireless                   | 1         | 0.01%   |
| Qualcomm                          | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2817      | 22.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1319      | 10.41%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 783       | 6.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 702       | 5.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 549       | 4.33%   |
| Intel Wi-Fi 6 AX200                                               | 298       | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 284       | 2.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 281       | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 277       | 2.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 203       | 1.6%    |
| Intel Wi-Fi 6 AX201                                               | 160       | 1.26%   |
| Intel Wireless 7265                                               | 152       | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 148       | 1.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 131       | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 126       | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 110       | 0.87%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 99        | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 95        | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 93        | 0.73%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 91        | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 90        | 0.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82        | 0.65%   |
| Intel Wireless 3165                                               | 79        | 0.62%   |
| Intel Wireless 7260                                               | 78        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 76        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 75        | 0.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 75        | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 74        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 70        | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 66        | 0.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 63        | 0.5%    |
| Realtek 802.11n WLAN Adapter                                      | 62        | 0.49%   |
| Intel Centrino Advanced-N 6235                                    | 61        | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 60        | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 56        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 55        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 55        | 0.43%   |
| Intel Wireless 3160                                               | 55        | 0.43%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 54        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 2777      | 42.08%  |
| Intel                                 | 1993      | 30.2%   |
| Realtek Semiconductor                 | 964       | 14.61%  |
| Broadcom                              | 461       | 6.99%   |
| Ralink                                | 122       | 1.85%   |
| Broadcom Limited                      | 90        | 1.36%   |
| Ralink Technology                     | 81        | 1.23%   |
| TP-Link                               | 41        | 0.62%   |
| Qualcomm Atheros Communications       | 23        | 0.35%   |
| D-Link                                | 14        | 0.21%   |
| MediaTek                              | 9         | 0.14%   |
| D-Link System                         | 7         | 0.11%   |
| NetGear                               | 2         | 0.03%   |
| Microsoft                             | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Edimax Technology                     | 2         | 0.03%   |
| Dell                                  | 2         | 0.03%   |
| Sierra Wireless                       | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Pegatron                              | 1         | 0.02%   |
| Mercucys                              | 1         | 0.02%   |
| Linksys                               | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 783       | 11.8%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 702       | 10.58%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 549       | 8.28%   |
| Intel Wi-Fi 6 AX200                                                     | 298       | 4.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 284       | 4.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 281       | 4.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 277       | 4.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 203       | 3.06%   |
| Intel Wi-Fi 6 AX201                                                     | 160       | 2.41%   |
| Intel Wireless 7265                                                     | 152       | 2.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 148       | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 126       | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 110       | 1.66%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 99        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 93        | 1.4%    |
| Intel Wireless 3165                                                     | 79        | 1.19%   |
| Intel Wireless 7260                                                     | 78        | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 76        | 1.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 75        | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 74        | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 0.95%   |
| Realtek 802.11n WLAN Adapter                                            | 62        | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 61        | 0.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 60        | 0.9%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 56        | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 55        | 0.83%   |
| Intel Wireless 3160                                                     | 55        | 0.83%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 54        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 54        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 50        | 0.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 50        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                         | 49        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 47        | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 0.69%   |
| Intel Wireless 8265 / 8275                                              | 46        | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 44        | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 38        | 0.57%   |
| Intel WiFi Link 5100                                                    | 37        | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 36        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4326      | 72.47%  |
| Qualcomm Atheros                 | 389       | 6.52%   |
| Intel                            | 298       | 4.99%   |
| Broadcom                         | 250       | 4.19%   |
| JMicron Technology               | 180       | 3.02%   |
| Marvell Technology Group         | 176       | 2.95%   |
| Silicon Integrated Systems [SiS] | 94        | 1.57%   |
| Broadcom Limited                 | 57        | 0.95%   |
| Samsung Electronics              | 43        | 0.72%   |
| VIA Technologies                 | 24        | 0.4%    |
| ASIX Electronics                 | 24        | 0.4%    |
| Motorola PCS                     | 23        | 0.39%   |
| Nvidia                           | 21        | 0.35%   |
| Xiaomi                           | 20        | 0.34%   |
| TP-Link                          | 10        | 0.17%   |
| ICS Advent                       | 10        | 0.17%   |
| DisplayLink                      | 6         | 0.1%    |
| Lenovo                           | 5         | 0.08%   |
| Attansic Technology              | 4         | 0.07%   |
| OPPO Electronics                 | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| Qualcomm                         | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| MediaTek                         | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2817      | 46.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1319      | 21.99%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 131       | 2.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 95        | 1.58%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 91        | 1.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 90        | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 82        | 1.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 75        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 70        | 1.17%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 66        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 55        | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 55        | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 50        | 0.83%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 49        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 42        | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 37        | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 31        | 0.52%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 30        | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                          | 29        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 28        | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 28        | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 27        | 0.45%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 26        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 24        | 0.4%    |
| Motorola PCS moto g(9) play                                                    | 23        | 0.38%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 23        | 0.38%   |
| Intel 82577LM Gigabit Network Connection                                       | 22        | 0.37%   |
| Realtek RTL8125 2.5GbE Controller                                              | 21        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 20        | 0.33%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 20        | 0.33%   |
| Intel Ethernet Connection I219-LM                                              | 20        | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 19        | 0.32%   |
| Intel Ethernet Connection I218-LM                                              | 19        | 0.32%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 19        | 0.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 17        | 0.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 16        | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 16        | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 15        | 0.25%   |
| Intel Ethernet Connection I217-LM                                              | 15        | 0.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 14        | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6377      | 51.94%  |
| Ethernet | 5866      | 47.78%  |
| Modem    | 24        | 0.2%    |
| Unknown  | 10        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5518      | 79.75%  |
| Ethernet | 1400      | 20.23%  |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5531      | 83.94%  |
| 1     | 842       | 12.78%  |
| 0     | 208       | 3.16%   |
| 3     | 8         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5287      | 78.49%  |
| Yes  | 1449      | 21.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1676      | 35.49%  |
| Qualcomm Atheros Communications | 1397      | 29.58%  |
| Lite-On Technology              | 614       | 13%     |
| Broadcom                        | 197       | 4.17%   |
| Realtek Semiconductor           | 150       | 3.18%   |
| Foxconn / Hon Hai               | 114       | 2.41%   |
| IMC Networks                    | 110       | 2.33%   |
| Cambridge Silicon Radio         | 88        | 1.86%   |
| Apple                           | 79        | 1.67%   |
| Dell                            | 74        | 1.57%   |
| Hewlett-Packard                 | 49        | 1.04%   |
| Ralink                          | 47        | 1%      |
| Unknown                         | 38        | 0.8%    |
| Qcom                            | 25        | 0.53%   |
| Ralink Technology               | 16        | 0.34%   |
| Alps Electric                   | 13        | 0.28%   |
| Foxconn International           | 12        | 0.25%   |
| Askey Computer                  | 8         | 0.17%   |
| Toshiba                         | 4         | 0.08%   |
| ASUSTek Computer                | 4         | 0.08%   |
| Micro Star International        | 3         | 0.06%   |
| Opticis                         | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 796       | 16.86%  |
| Intel Bluetooth wireless interface                                                  | 563       | 11.92%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 454       | 9.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 352       | 7.45%   |
| Intel AX200 Bluetooth                                                               | 295       | 6.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 226       | 4.79%   |
| Intel AX201 Bluetooth                                                               | 151       | 3.2%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 127       | 2.69%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 125       | 2.65%   |
| Realtek Bluetooth Radio                                                             | 114       | 2.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 110       | 2.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 88        | 1.86%   |
| Lite-On Bluetooth Device                                                            | 85        | 1.8%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 84        | 1.78%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 83        | 1.76%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 62        | 1.31%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 58        | 1.23%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 55        | 1.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 53        | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 48        | 1.02%   |
| Ralink RT3290 Bluetooth                                                             | 47        | 1%      |
| IMC Networks Bluetooth Radio                                                        | 46        | 0.97%   |
| Unknown Bluetooth Device                                                            | 38        | 0.8%    |
| Apple Bluetooth Host Controller                                                     | 35        | 0.74%   |
| Dell Wireless 365 Bluetooth                                                         | 32        | 0.68%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 30        | 0.64%   |
| IMC Networks Bluetooth Device                                                       | 28        | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 27        | 0.57%   |
| Apple Bluetooth USB Host Controller                                                 | 27        | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 26        | 0.55%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 23        | 0.49%   |
| Lite-On Atheros Bluetooth                                                           | 22        | 0.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 19        | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 17        | 0.36%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 17        | 0.36%   |
| Dell DW375 Bluetooth Module                                                         | 16        | 0.34%   |
| Realtek RTL8723A Bluetooth                                                          | 15        | 0.32%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 15        | 0.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 15        | 0.32%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 15        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 5662      | 74.76%  |
| Nvidia                                          | 817       | 10.79%  |
| AMD                                             | 671       | 8.86%   |
| Silicon Integrated Systems [SiS]                | 94        | 1.24%   |
| C-Media Electronics                             | 65        | 0.86%   |
| Generalplus Technology                          | 39        | 0.51%   |
| Logitech                                        | 38        | 0.5%    |
| VIA Technologies                                | 24        | 0.32%   |
| Kingston Technology                             | 19        | 0.25%   |
| JMTek                                           | 17        | 0.22%   |
| Plantronics                                     | 10        | 0.13%   |
| Corsair                                         | 10        | 0.13%   |
| Texas Instruments                               | 9         | 0.12%   |
| Realtek Semiconductor                           | 9         | 0.12%   |
| GN Netcom                                       | 9         | 0.12%   |
| Microsoft                                       | 8         | 0.11%   |
| Samsung Electronics                             | 6         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.08%   |
| Sony                                            | 5         | 0.07%   |
| Samson Technologies                             | 4         | 0.05%   |
| SteelSeries ApS                                 | 3         | 0.04%   |
| Razer USA                                       | 3         | 0.04%   |
| Meizu                                           | 3         | 0.04%   |
| Lenovo                                          | 3         | 0.04%   |
| JBL                                             | 3         | 0.04%   |
| Turtle Beach                                    | 2         | 0.03%   |
| Tdlasunnic                                      | 2         | 0.03%   |
| M-Audio                                         | 2         | 0.03%   |
| Goldvish                                        | 2         | 0.03%   |
| Focusrite-Novation                              | 2         | 0.03%   |
| Dell                                            | 2         | 0.03%   |
| BY EDIFIER                                      | 2         | 0.03%   |
| BR25                                            | 2         | 0.03%   |
| BEHRINGER International                         | 2         | 0.03%   |
| Astro Gaming                                    | 2         | 0.03%   |
| Winbond Electronics                             | 1         | 0.01%   |
| Unknown (ABC)                                   | 1         | 0.01%   |
| Tenx Technology                                 | 1         | 0.01%   |
| Syntek                                          | 1         | 0.01%   |
| SOMIC Industrial                                | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1039      | 11.77%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 884       | 10.01%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 452       | 5.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 401       | 4.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 380       | 4.3%    |
| Intel 8 Series HD Audio Controller                                                                | 374       | 4.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 370       | 4.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 317       | 3.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 309       | 3.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 302       | 3.42%   |
| Intel Broadwell-U Audio Controller                                                                | 302       | 3.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 274       | 3.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 259       | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 186       | 2.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 172       | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 169       | 1.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 148       | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 142       | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 138       | 1.56%   |
| AMD Wrestler HDMI Audio                                                                           | 131       | 1.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 116       | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 113       | 1.28%   |
| AMD FCH Azalia Controller                                                                         | 112       | 1.27%   |
| Intel CM238 HD Audio Controller                                                                   | 98        | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 93        | 1.05%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 91        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 91        | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 79        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 72        | 0.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 68        | 0.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 63        | 0.71%   |
| Intel Comet Lake PCH cAVS                                                                         | 54        | 0.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 52        | 0.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 48        | 0.54%   |
| Generalplus Technology USB Audio Device                                                           | 39        | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 38        | 0.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 38        | 0.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 36        | 0.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 0.37%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 31        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 475       | 19.14%  |
| Samsung Electronics | 338       | 13.62%  |
| Unknown             | 237       | 9.55%   |
| Kingston            | 237       | 9.55%   |
| SK hynix            | 229       | 9.23%   |
| A-DATA Technology   | 191       | 7.7%    |
| Teikon              | 136       | 5.48%   |
| Micron Technology   | 106       | 4.27%   |
| Smart Brazil        | 95        | 3.83%   |
| Crucial             | 61        | 2.46%   |
| Corsair             | 59        | 2.38%   |
| High Bridge         | 58        | 2.34%   |
| Elpida              | 40        | 1.61%   |
| Unknown (ABCD)      | 22        | 0.89%   |
| Multilaser          | 22        | 0.89%   |
| Apacer              | 18        | 0.73%   |
| Nanya Technology    | 16        | 0.64%   |
| Unknown             | 13        | 0.52%   |
| Patriot             | 12        | 0.48%   |
| Ramaxel Technology  | 11        | 0.44%   |
| HT Micron           | 11        | 0.44%   |
| Kllisre             | 10        | 0.4%    |
| Smart Modular       | 5         | 0.2%    |
| PUSKILL             | 5         | 0.2%    |
| Avant               | 5         | 0.2%    |
| RZX                 | 4         | 0.16%   |
| Carry               | 4         | 0.16%   |
| Team                | 3         | 0.12%   |
| Kreton              | 3         | 0.12%   |
| Kingmax             | 3         | 0.12%   |
| HBS                 | 3         | 0.12%   |
| G.Skill             | 3         | 0.12%   |
| Atermiter           | 3         | 0.12%   |
| Walton Chaintech    | 2         | 0.08%   |
| Unknown (8A02)      | 2         | 0.08%   |
| Unknown (898F)      | 2         | 0.08%   |
| Transcend           | 2         | 0.08%   |
| Super Talent        | 2         | 0.08%   |
| Qimonda             | 2         | 0.08%   |
| Positivo            | 2         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s  | 72        | 2.67%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 47        | 1.74%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 43        | 1.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 41        | 1.52%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 39        | 1.45%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 36        | 1.34%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s         | 34        | 1.26%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 32        | 1.19%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 29        | 1.08%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 28        | 1.04%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 22        | 0.82%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 22        | 0.82%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 22        | 0.82%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 21        | 0.78%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 21        | 0.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.74%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 19        | 0.71%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8192MB SODIMM DDR4 2400MT/s        | 17        | 0.63%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 17        | 0.63%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 17        | 0.63%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 17        | 0.63%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 16        | 0.59%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 15        | 0.56%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 15        | 0.56%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 15        | 0.56%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 15        | 0.56%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 14        | 0.52%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 14        | 0.52%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 14        | 0.52%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 14        | 0.52%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 14        | 0.52%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s             | 13        | 0.48%   |
| Unknown                                                          | 13        | 0.48%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 12        | 0.45%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s        | 12        | 0.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 0.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 11        | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 11        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 964       | 46.77%  |
| DDR4    | 785       | 38.09%  |
| DDR2    | 130       | 6.31%   |
| SDRAM   | 60        | 2.91%   |
| LPDDR4  | 53        | 2.57%   |
| LPDDR3  | 26        | 1.26%   |
| DRAM    | 18        | 0.87%   |
| DDR     | 12        | 0.58%   |
| Unknown | 7         | 0.34%   |
| DDR5    | 3         | 0.15%   |
| LPDDR5  | 2         | 0.1%    |
| RAM     | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1958      | 96.03%  |
| Row Of Chips | 64        | 3.14%   |
| Unknown      | 9         | 0.44%   |
| DIMM         | 6         | 0.29%   |
| Chip         | 2         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 951       | 40.45%  |
| 8192  | 595       | 25.31%  |
| 2048  | 491       | 20.88%  |
| 16384 | 211       | 8.97%   |
| 1024  | 78        | 3.32%   |
| 32768 | 20        | 0.85%   |
| 512   | 5         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 604       | 25.82%  |
| 2667    | 449       | 19.2%   |
| 2400    | 275       | 11.76%  |
| 1334    | 208       | 8.89%   |
| 1333    | 182       | 7.78%   |
| 3200    | 113       | 4.83%   |
| Unknown | 85        | 3.63%   |
| 2133    | 76        | 3.25%   |
| 800     | 52        | 2.22%   |
| 667     | 48        | 2.05%   |
| 4199    | 37        | 1.58%   |
| 1067    | 37        | 1.58%   |
| 1066    | 33        | 1.41%   |
| 4267    | 23        | 0.98%   |
| 975     | 21        | 0.9%    |
| 533     | 20        | 0.86%   |
| 2048    | 19        | 0.81%   |
| 3266    | 9         | 0.38%   |
| 2933    | 9         | 0.38%   |
| 1867    | 9         | 0.38%   |
| 8400    | 6         | 0.26%   |
| 1200    | 4         | 0.17%   |
| 4800    | 3         | 0.13%   |
| 6400    | 2         | 0.09%   |
| 3733    | 2         | 0.09%   |
| 400     | 2         | 0.09%   |
| 3466    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 1866    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1400    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 2       | 1         | 0.04%   |
| 1       | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 39.62%  |
| Seiko Epson         | 19        | 35.85%  |
| Canon               | 5         | 9.43%   |
| Samsung Electronics | 4         | 7.55%   |
| Brother Industries  | 2         | 3.77%   |
| Xerox               | 1         | 1.89%   |
| MIIIW               | 1         | 1.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                     | 7         | 13.21%  |
| HP DeskJet 2700 series                       | 3         | 5.66%   |
| Seiko Epson L355 Series                      | 2         | 3.77%   |
| Seiko Epson ET-3750 Series                   | 2         | 3.77%   |
| Seiko Epson ET-2600 Series                   | 2         | 3.77%   |
| HP LaserJet Professional P1102w              | 2         | 3.77%   |
| HP LaserJet 1020                             | 2         | 3.77%   |
| HP Ink Tank Wireless 410 series              | 2         | 3.77%   |
| HP Deskjet 3050 J610 series                  | 2         | 3.77%   |
| HP Deskjet 2540 series                       | 2         | 3.77%   |
| Canon G3000 series                           | 2         | 3.77%   |
| Xerox Phaser 3040                            | 1         | 1.89%   |
| Seiko Epson XP-230 Series                    | 1         | 1.89%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.89%   |
| Seiko Epson L805 Series                      | 1         | 1.89%   |
| Seiko Epson L4150 Series                     | 1         | 1.89%   |
| Seiko Epson L380 Series                      | 1         | 1.89%   |
| Seiko Epson L220 Series                      | 1         | 1.89%   |
| Samsung SCX-4623 Series                      | 1         | 1.89%   |
| Samsung SCX-4200 series                      | 1         | 1.89%   |
| Samsung M332x 382x 402x Series               | 1         | 1.89%   |
| Samsung M2020 Series                         | 1         | 1.89%   |
| MIIIW MW Keyboard Air Mini                   | 1         | 1.89%   |
| HP LaserJet 1018                             | 1         | 1.89%   |
| HP DeskJet F4200 series                      | 1         | 1.89%   |
| HP DeskJet F4100 Printer series              | 1         | 1.89%   |
| HP DeskJet D1360                             | 1         | 1.89%   |
| HP DeskJet 3630 series                       | 1         | 1.89%   |
| HP DeskJet 2300 series                       | 1         | 1.89%   |
| HP DeskJet 2130 series                       | 1         | 1.89%   |
| HP Deskjet 1510                              | 1         | 1.89%   |
| Canon G4010 series                           | 1         | 1.89%   |
| Canon G4000 series                           | 1         | 1.89%   |
| Canon G3010 series                           | 1         | 1.89%   |
| Brother HL-5250DN Printer                    | 1         | 1.89%   |
| Brother DCP-7040                             | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Hewlett-Packard | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP ScanJet 2400c                   | 1         | 20%     |
| HP Scanjet 200                     | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 110            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1291      | 21.45%  |
| Microdia                               | 719       | 11.95%  |
| Realtek Semiconductor                  | 609       | 10.12%  |
| Quanta                                 | 567       | 9.42%   |
| Silicon Motion                         | 500       | 8.31%   |
| Sunplus Innovation Technology          | 462       | 7.68%   |
| Acer                                   | 411       | 6.83%   |
| IMC Networks                           | 275       | 4.57%   |
| Suyin                                  | 263       | 4.37%   |
| Syntek                                 | 189       | 3.14%   |
| Alcor Micro                            | 114       | 1.89%   |
| Apple                                  | 79        | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) | 76        | 1.26%   |
| Samsung Electronics                    | 51        | 0.85%   |
| Logitech                               | 47        | 0.78%   |
| Ricoh                                  | 46        | 0.76%   |
| ALi                                    | 42        | 0.7%    |
| Unknown                                | 24        | 0.4%    |
| Lite-On Technology                     | 22        | 0.37%   |
| Importek                               | 21        | 0.35%   |
| OmniVision Technologies                | 20        | 0.33%   |
| Z-Star Microelectronics                | 19        | 0.32%   |
| Sonix Technology                       | 15        | 0.25%   |
| USB Camera                             | 12        | 0.2%    |
| Lenovo                                 | 12        | 0.2%    |
| LG Electronics                         | 10        | 0.17%   |
| Generalplus Technology                 | 10        | 0.17%   |
| Y Media                                | 9         | 0.15%   |
| Intel                                  | 9         | 0.15%   |
| SunplusIT                              | 8         | 0.13%   |
| Pixart Imaging                         | 7         | 0.12%   |
| Microsoft                              | 7         | 0.12%   |
| Primax Electronics                     | 6         | 0.1%    |
| Camera                                 | 6         | 0.1%    |
| Sunplus Technology                     | 5         | 0.08%   |
| Jieli Technology                       | 5         | 0.08%   |
| Image Processor                        | 5         | 0.08%   |
| GEMBIRD                                | 5         | 0.08%   |
| Foxconn / Hon Hai                      | 5         | 0.08%   |
| DigiTech                               | 5         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 275       | 4.57%   |
| Realtek Integrated_Webcam_HD              | 268       | 4.45%   |
| Quanta HD User Facing                     | 241       | 4%      |
| Chicony HD User Facing                    | 200       | 3.32%   |
| Chicony HD Webcam                         | 188       | 3.12%   |
| Silicon Motion Web Camera                 | 187       | 3.1%    |
| Sunplus Integrated_Webcam_HD              | 185       | 3.07%   |
| Quanta VGA WebCam                         | 173       | 2.87%   |
| Chicony USB 2.0 Camera                    | 139       | 2.31%   |
| Chicony VGA WebCam                        | 132       | 2.19%   |
| Chicony Integrated Camera                 | 132       | 2.19%   |
| Syntek Integrated Camera                  | 103       | 1.71%   |
| Sunplus HD WebCam                         | 103       | 1.71%   |
| Realtek Integrated Webcam                 | 98        | 1.63%   |
| Quanta HD Webcam                          | 95        | 1.58%   |
| Microdia Laptop_Integrated_Webcam_HD      | 74        | 1.23%   |
| Alcor Micro USB 2.0 Camera                | 70        | 1.16%   |
| Acer Lenovo EasyCamera                    | 63        | 1.05%   |
| Acer BisonCam, NB Pro                     | 63        | 1.05%   |
| Acer EasyCamera                           | 60        | 1%      |
| Realtek USB Camera                        | 56        | 0.93%   |
| Microdia Dell Laptop Integrated Webcam HD | 53        | 0.88%   |
| Samsung Galaxy A5 (MTP)                   | 51        | 0.85%   |
| Silicon Motion WebCam SC-10HDD12636N      | 48        | 0.8%    |
| Microdia Integrated Webcam HD             | 45        | 0.75%   |
| IMC Networks Integrated Camera            | 45        | 0.75%   |
| Suyin Integrated_Webcam_HD                | 44        | 0.73%   |
| Acer VGA WebCam                           | 43        | 0.71%   |
| Silicon Motion WebCam SCB-1100N           | 40        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 40        | 0.66%   |
| Realtek HD WebCam                         | 39        | 0.65%   |
| Silicon Motion WebCam SC-13HDL11939N      | 38        | 0.63%   |
| Silicon Motion WebCam SC-0311139N         | 36        | 0.6%    |
| IMC Networks USB2.0 HD UVC WebCam         | 36        | 0.6%    |
| Syntek EasyCamera                         | 35        | 0.58%   |
| Acer HD Webcam                            | 35        | 0.58%   |
| Sunplus Integrated Webcam                 | 34        | 0.56%   |
| Chicony EasyCamera                        | 34        | 0.56%   |
| Acer USB Camera                           | 34        | 0.56%   |
| Silicon Motion WebCam SCB-0385N           | 32        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 265       | 49.91%  |
| AuthenTec                  | 55        | 10.36%  |
| Upek                       | 53        | 9.98%   |
| Synaptics                  | 52        | 9.79%   |
| Shenzhen Goodix Technology | 46        | 8.66%   |
| LighTuning Technology      | 29        | 5.46%   |
| Samsung Electronics        | 15        | 2.82%   |
| Elan Microelectronics      | 8         | 1.51%   |
| STMicroelectronics         | 3         | 0.56%   |
| Focal-systems.Corp         | 2         | 0.38%   |
| Next Biometrics            | 1         | 0.19%   |
| DigitalPersona             | 1         | 0.19%   |
| Dell                       | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 101       | 19.02%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 45        | 8.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 4.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 4.9%    |
| Shenzhen Goodix Fingerprint Reader                                         | 26        | 4.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 24        | 4.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 23        | 4.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 3.95%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 3.95%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 3.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 15        | 2.82%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 2.82%   |
| Samsung Fingerprint Device                                                 | 15        | 2.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.26%   |
| AuthenTec AES2810                                                          | 12        | 2.26%   |
| Validity Sensors VFS491                                                    | 11        | 2.07%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 2.07%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.69%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.51%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.51%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.32%   |
| Synaptics  WBDI                                                            | 7         | 1.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.32%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.13%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.94%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.94%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.38%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.38%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.38%   |
| AuthenTec AES1600                                                          | 2         | 0.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.19%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.19%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.19%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.19%   |
| Next Biometrics NB-2020-U Fingerprint Reader                               | 1         | 0.19%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 76        | 53.15%  |
| Alcor Micro               | 23        | 16.08%  |
| Lenovo                    | 13        | 9.09%   |
| Upek                      | 9         | 6.29%   |
| Giesecke & Devrient       | 7         | 4.9%    |
| Aladdin Knowledge Systems | 5         | 3.5%    |
| Watchdata                 | 4         | 2.8%    |
| O2 Micro                  | 3         | 2.1%    |
| SCM Microsystems          | 1         | 0.7%    |
| Gemalto (was Gemplus)     | 1         | 0.7%    |
| Advanced Card Systems     | 1         | 0.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 16.08%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 13.99%  |
| Broadcom 58200                                                               | 20        | 13.99%  |
| Broadcom 5880                                                                | 19        | 13.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 11.89%  |
| Lenovo Integrated Smart Card Reader                                          | 13        | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 6.29%   |
| Giesecke & Devrient StarSign CUT                                             | 5         | 3.5%    |
| Aladdin Knowledge Systems Token JC                                           | 5         | 3.5%    |
| Watchdata USB Key                                                            | 4         | 2.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.4%    |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 1.4%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.7%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.7%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5141      | 76.96%  |
| 1     | 1340      | 20.06%  |
| 2     | 167       | 2.5%    |
| 3     | 17        | 0.25%   |
| 4     | 7         | 0.1%    |
| 7     | 4         | 0.06%   |
| 8     | 2         | 0.03%   |
| 5     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 529       | 30.23%  |
| Graphics card            | 476       | 27.2%   |
| Multimedia controller    | 178       | 10.17%  |
| Net/wireless             | 139       | 7.94%   |
| Chipcard                 | 127       | 7.26%   |
| Bluetooth                | 77        | 4.4%    |
| Camera                   | 53        | 3.03%   |
| Communication controller | 39        | 2.23%   |
| Storage                  | 38        | 2.17%   |
| Sound                    | 29        | 1.66%   |
| Net/ethernet             | 20        | 1.14%   |
| Flash memory             | 20        | 1.14%   |
| Card reader              | 8         | 0.46%   |
| Modem                    | 7         | 0.4%    |
| Firewire controller      | 4         | 0.23%   |
| Network                  | 3         | 0.17%   |
| Unassigned class         | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |

